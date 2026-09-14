console.log('ads35-7');

window.bannerName = "paperio-site_multisize";
window.adsBannerId = "adsBanner";

/*window.adsBannerId = "adsBanner"
window.bannerName = "adinBanner"*/

window.ads = {};
//initAds();

//refreshAdsBanner();

window.addEventListener("load", ()=> setTimeout(initAds, 1));

window.lastTimeAds = new Date();
let onceAdsLongerTimeout = false;
let now = new Date();
window.lastTimeAds.setTime(now.getTime() - 120000);

window.checktimeForAds = function () {
  let now = new Date();
  let time = Math.floor((now.getTime() - window.lastTimeAds.getTime()) * 0.001);
  console.log('ADS: time since last  ' + time);
  return (time >= 30);
}

window.updateLastAdsTime = function () {
  let now = new Date();
  window.lastTimeAds.setTime(now.getTime());
  console.log('ADS: updated last time.');
}

function ShowInvite() {
  if (window.ga) ga('send', 'event', 'button', 'inviteFriends');
  if (window.ym) ym(window.ymId, 'reachGoal', 'btnInvite');

  document.getElementById("shareInvite").style.display = "block";
  return false;
}

function HideInvite() {
  document.getElementById("shareInvite").style.display = "none";
  return false;
}

function inviteCopyLink() {
  document.getElementById("shareLinkInput").select();
  //document.execCommand("copy");
}

window.ads.showPreroll = function ShowPreroll() {

  if (window.checktimeForAds() == true) {
    //check if the adslib is loaded correctly or blocked by adblockers etc.
    if (typeof aiptag.adplayer !== 'undefined') {
      aiptag.cmd.player.push(function () { adplayer.startPreRoll(); });
      updateLastAdsTime();
      if (!onceAdsLongerTimeout) {
        window.lastTimeAds.setTime(now.getTime() + 120000);
        onceAdsLongerTimeout = true;
      }
      HideAds();
      console.log("Showing Preroll");
      preroll.style.display = "block";
    } else {
      //Adlib didnt load this could be due to an adblocker, timeout etc.
      //Please add your script here that starts the content, this usually is the same script as added in AIP_COMPLETE or AIP_REMOVE.
      //alert("Ad Could not be loaded, load your content here");
      StartGame();
      if (document.getElementById("bottom"))
        document.getElementById("bottom").style.display = "none";
    }
  }
  else {
    StartGame();
  }

}

function ShowAbout() {
  var ab = document.getElementById("about");
  HideAds();
  if (ab.style.display === "block") {
    HideAbout();
  } else {
    ab.style.display = "block";
  }
}
function HideAbout() {
  var ab = document.getElementById("about");
  ab.style.display = "none";
  ShowAds()
}

function refreshAdsBanner() {
  if(typeof aiptag === "undefined"){
    console.log("aiptag not defined");
    return;
  }
  if(typeof aiptag.cmd === "undefined"){
    console.log("aiptag.cmd not defined");
    return;
  }
  if(typeof aiptag.cmd.display === "undefined"){
    console.log("aiptag.cmd.display not defined");
    return;
  }

  if (!document.getElementById(window.bannerName)) {
        console.log("banner not defined");
	return;
  }

	console.log("refresh ads");
  	aiptag.cmd.display.push(function () { aipDisplayTag.display(window.bannerName); });
  	checkBannerFits();
  	setTimeout(checkBannerFits, 100);
}

window.addEventListener("resize", resizeAdsCheck, false);

function resizeAdsCheck() {
  var ads = document.getElementById("adsBanner");
  let minHeight = 600;
  if (window.uiApi.curMenu == "end") {
    minHeight = 715;
  }

  if (screen.width <= 800 || window.innerWidth <= 800) {
    if (document.getElementById("right_side")) {
      if (document.getElementById("left_side"))
        document.getElementById("left_side").style.display = "none";
      document.getElementById("right_side").style.display = "none";
    }
    if (document.getElementById("leftSideUI")) {
      document.getElementById("leftSideUI").style.display = "none";
    }
  }
  else if (window.uiApi.curMenu != "game") {
    if (document.getElementById("right_side")) {
      if (document.getElementById("left_side"))
        document.getElementById("left_side").style.display = "";
      document.getElementById("right_side").style.display = "";
    }
    if (document.getElementById("leftSideUI")) {
      document.getElementById("leftSideUI").style.display = "";
    }
  }

  if (ads) {
    if ((window.uiApi.curMenu == "shop" || window.uiApi.curMenu == "game")
      || screen.height <= minHeight
      || (window.innerHeight <= minHeight)) {
      ads.style.display = 'none';
      ads.className = "hide";
      return false;
    }

    if (screen.width < 800 || window.innerWidth < 800) {

      ads.style.display = 'flex';
      ads.className = "show";
      checkBannerFits();
      return true;
    }
    else {
      ads.style.display = 'flex';
      ads.className = "show";
      checkBannerFits();
      return true;
    }
  }
  return false;
}


function resizeDiv(divId, _maxHeight) {
  if (document.getElementById(divId)) {
    let maxHeight = _maxHeight;//window.innerHeight*0.3;
    let proportion = window.innerHeight / window.innerWidth;

    let maxWidth = window.innerWidth;
    let bannerHeight = document.getElementById(divId).clientHeight;
    let bannerWidth = document.getElementById(divId).clientWidth;
    let newHeight = bannerHeight;
    let newWidth = bannerWidth;
    if (bannerHeight > maxHeight) {
      let idToScale = divId;
      var diffScale = maxHeight / bannerHeight;

      if (maxWidth < bannerWidth) {
        var diffScaleWidth = maxWidth / bannerWidth;
        if (diffScaleWidth < diffScale)
          diffScale = diffScaleWidth;
      }


      document.getElementById(idToScale).style.transform = "scale(" + diffScale + ")";
      // if(bannerHeight > maxHeight)
      newHeight = bannerHeight * diffScale;
      newWidth = bannerWidth * diffScale;
      let widthDiff = -(bannerWidth - newWidth) * 0.5;

      document.getElementById(idToScale).style.marginTop = (1 - (bannerHeight - maxHeight) * 0.5) + "px";

      let multiForWidth = 1;
      if (bannerWidth > maxWidth) {
        multiForWidth = -1;
      }
    }

    document.getElementById(divId).style.top = (window.innerHeight - newHeight - 10) + "px";
  }
}

function checkBannerFits() {
  let bannerName = window.bannerName;
  let maxBannerHaight = 270;
  if (document.getElementById(bannerName)) {
    if (document.getElementById(bannerName).firstElementChild)
      resizeDiv(document.getElementById(bannerName).firstElementChild.id, maxBannerHaight);

    document.getElementById(bannerName).style.display = "flex";
  }
}

checkBannerFits();

function ShowAds() {
  //console.log("call show ads");

  var okToShowAds = resizeAdsCheck();//shows or hides banner as well

  if (okToShowAds) {
    refreshAdsBanner();
  }

}

function showMenuElements(menu = "") {
  window.uiApi.curMenu = menu;

  document.getElementById("bottom").style.display = "block";
  document.getElementById("leftSideUI").style.display = "block";

  ShowAds();
}

function hideMenuElements(menu = "") {
  window.uiApi.curMenu = menu;
  HideAbout();
  document.getElementById("bottom").style.display = "none";
  document.getElementById("leftSideUI").style.display = "none";
  HideAds();
}

function HideAds() {
  preroll.style.display = "none";
  var ads = document.getElementById("adsBanner");
  if (!ads) return;
  ads.style.display = 'none';
  ads.className = "hide";
}

function StartGame() {
  hideMenuElements("game");
  window.uiApi && window.uiApi.startGame && window.uiApi.startGame();
}

initAdsComplete = false;

function initAds() {
	window.aiptag = window.aiptag || {cmd: []};
  
  if(initAdsComplete)
    return;
  
  if(typeof aiptag === "undefined" || document.getElementById(window.bannerName) == null){
    setTimeout(initAds, 1000);
    return;
  }
  
	aiptag.cmd.display = aiptag.cmd.display || [];	aiptag.cmd.player = aiptag.cmd.player || [];
    aiptag.cmd.player = aiptag.cmd.player || [];
    // Show GDPR consent tool
    aiptag.gdprShowConsentTool = true;
    // If you use your own GDPR consent tool please set aiptag.gdprConsent = false; if an EU user has declined or not yet accepted marketing cookies, for users outside the EU or for users that accepted the GDPR please use aiptag.gdprConsent = true;

    aiptag.subid = "paper_3d";

	aiptag.cmd.player.push(function() {
		adplayer = new aipPlayer({			
			AD_WIDTH: 960,
			AD_HEIGHT: 540,
			AD_FULLSCREEN: true,
			AD_CENTERPLAYER: false,
			LOADING_TEXT: 'loading advertisement',
			PREROLL_ELEM: function(){return document.getElementById('preroll')},
			AIP_COMPLETE: function ()  {
				/*******************
				 ***** WARNING *****
				 *******************
				 Please do not remove the PREROLL_ELEM
				 from the page, it will be hidden automaticly.
				 If you do want to remove it use the AIP_REMOVE callback.
				*/
			        window.updateLastAdsTime();
			        window.StartGame();

			},
			AIP_REMOVE: function ()  {
				// Here it's save to remove the PREROLL_ELEM from the page.
				// But it's not necessary.
			}		});
	});


  var ad = document.getElementById(window.bannerName);
  ad.style.display = 'block';

  aiptag.cmd.display.push(function () {
    aipDisplayTag.display(window.bannerName);
  });
  var rb = document.getElementById('rightbanner');
  if (window.innerWidth > 1000) {
    GameAdsRenew("gameadsbanner");
    if (rb)
      rb.style.display = 'block';
  } else {
    if (rb)
      rb.style.display = 'none';
  }
  
  initAdsComplete = true;
}
