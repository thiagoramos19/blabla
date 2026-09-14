(function () {
  'use strict';

  function _arrayLikeToArray(r, a) {
    (null == a || a > r.length) && (a = r.length);
    for (var e = 0, n = Array(a); e < a; e++) n[e] = r[e];
    return n;
  }
  function _arrayWithHoles(r) {
    if (Array.isArray(r)) return r;
  }
  function _arrayWithoutHoles(r) {
    if (Array.isArray(r)) return _arrayLikeToArray(r);
  }
  function _classCallCheck(a, n) {
    if (!(a instanceof n)) throw new TypeError("Cannot call a class as a function");
  }
  function _defineProperties(e, r) {
    for (var t = 0; t < r.length; t++) {
      var o = r[t];
      o.enumerable = o.enumerable || !1, o.configurable = !0, "value" in o && (o.writable = !0), Object.defineProperty(e, _toPropertyKey(o.key), o);
    }
  }
  function _createClass(e, r, t) {
    return r && _defineProperties(e.prototype, r), t && _defineProperties(e, t), Object.defineProperty(e, "prototype", {
      writable: !1
    }), e;
  }
  function _defineProperty(e, r, t) {
    return (r = _toPropertyKey(r)) in e ? Object.defineProperty(e, r, {
      value: t,
      enumerable: !0,
      configurable: !0,
      writable: !0
    }) : e[r] = t, e;
  }
  function _iterableToArray(r) {
    if ("undefined" != typeof Symbol && null != r[Symbol.iterator] || null != r["@@iterator"]) return Array.from(r);
  }
  function _iterableToArrayLimit(r, l) {
    var t = null == r ? null : "undefined" != typeof Symbol && r[Symbol.iterator] || r["@@iterator"];
    if (null != t) {
      var e,
        n,
        i,
        u,
        a = [],
        f = !0,
        o = !1;
      try {
        if (i = (t = t.call(r)).next, 0 === l) {
          if (Object(t) !== t) return;
          f = !1;
        } else for (; !(f = (e = i.call(t)).done) && (a.push(e.value), a.length !== l); f = !0);
      } catch (r) {
        o = !0, n = r;
      } finally {
        try {
          if (!f && null != t.return && (u = t.return(), Object(u) !== u)) return;
        } finally {
          if (o) throw n;
        }
      }
      return a;
    }
  }
  function _nonIterableRest() {
    throw new TypeError("Invalid attempt to destructure non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.");
  }
  function _nonIterableSpread() {
    throw new TypeError("Invalid attempt to spread non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.");
  }
  function ownKeys(e, r) {
    var t = Object.keys(e);
    if (Object.getOwnPropertySymbols) {
      var o = Object.getOwnPropertySymbols(e);
      r && (o = o.filter(function (r) {
        return Object.getOwnPropertyDescriptor(e, r).enumerable;
      })), t.push.apply(t, o);
    }
    return t;
  }
  function _objectSpread2(e) {
    for (var r = 1; r < arguments.length; r++) {
      var t = null != arguments[r] ? arguments[r] : {};
      r % 2 ? ownKeys(Object(t), !0).forEach(function (r) {
        _defineProperty(e, r, t[r]);
      }) : Object.getOwnPropertyDescriptors ? Object.defineProperties(e, Object.getOwnPropertyDescriptors(t)) : ownKeys(Object(t)).forEach(function (r) {
        Object.defineProperty(e, r, Object.getOwnPropertyDescriptor(t, r));
      });
    }
    return e;
  }
  function _slicedToArray(r, e) {
    return _arrayWithHoles(r) || _iterableToArrayLimit(r, e) || _unsupportedIterableToArray(r, e) || _nonIterableRest();
  }
  function _toConsumableArray(r) {
    return _arrayWithoutHoles(r) || _iterableToArray(r) || _unsupportedIterableToArray(r) || _nonIterableSpread();
  }
  function _toPrimitive(t, r) {
    if ("object" != typeof t || !t) return t;
    var e = t[Symbol.toPrimitive];
    if (void 0 !== e) {
      var i = e.call(t, r || "default");
      if ("object" != typeof i) return i;
      throw new TypeError("@@toPrimitive must return a primitive value.");
    }
    return ("string" === r ? String : Number)(t);
  }
  function _toPropertyKey(t) {
    var i = _toPrimitive(t, "string");
    return "symbol" == typeof i ? i : i + "";
  }
  function _typeof(o) {
    "@babel/helpers - typeof";

    return _typeof = "function" == typeof Symbol && "symbol" == typeof Symbol.iterator ? function (o) {
      return typeof o;
    } : function (o) {
      return o && "function" == typeof Symbol && o.constructor === Symbol && o !== Symbol.prototype ? "symbol" : typeof o;
    }, _typeof(o);
  }
  function _unsupportedIterableToArray(r, a) {
    if (r) {
      if ("string" == typeof r) return _arrayLikeToArray(r, a);
      var t = {}.toString.call(r).slice(8, -1);
      return "Object" === t && r.constructor && (t = r.constructor.name), "Map" === t || "Set" === t ? Array.from(r) : "Arguments" === t || /^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(t) ? _arrayLikeToArray(r, a) : void 0;
    }
  }

  var n,l$1,t$1,i$1,r$1,o$1,e$1,f$1,c$1,s$1,a$1,h$1,p$1={},v$1=[],y$1=/acit|ex(?:s|g|n|p|$)|rph|grid|ows|mnc|ntw|ine[ch]|zoo|^ord|itera/i,d$1=Array.isArray;function w$1(n,l){for(var t in l)n[t]=l[t];return n}function g(n){n&&n.parentNode&&n.parentNode.removeChild(n);}function _$1(l,t,u){var i,r,o,e={};for(o in t)"key"==o?i=t[o]:"ref"==o?r=t[o]:e[o]=t[o];if(arguments.length>2&&(e.children=arguments.length>3?n.call(arguments,2):u),"function"==typeof l&&null!=l.defaultProps)for(o in l.defaultProps)void 0===e[o]&&(e[o]=l.defaultProps[o]);return m$1(l,e,i,r,null)}function m$1(n,u,i,r,o){var e={type:n,props:u,key:i,ref:r,__k:null,__:null,__b:0,__e:null,__c:null,constructor:void 0,__v:null==o?++t$1:o,__i:-1,__u:0};return null==o&&null!=l$1.vnode&&l$1.vnode(e),e}function b(){return {current:null}}function k$1(n){return n.children}function x$1(n,l){this.props=n,this.context=l;}function S(n,l){if(null==l)return n.__?S(n.__,n.__i+1):null;for(var t;l<n.__k.length;l++)if(null!=(t=n.__k[l])&&null!=t.__e)return t.__e;return "function"==typeof n.type?S(n):null}function C$1(n){var l,t;if(null!=(n=n.__)&&null!=n.__c){for(n.__e=n.__c.base=null,l=0;l<n.__k.length;l++)if(null!=(t=n.__k[l])&&null!=t.__e){n.__e=n.__c.base=t.__e;break}return C$1(n)}}function M(n){(!n.__d&&(n.__d=!0)&&i$1.push(n)&&!$.__r++||r$1!==l$1.debounceRendering)&&((r$1=l$1.debounceRendering)||o$1)($);}function $(){for(var n,t,u,r,o,f,c,s=1;i$1.length;)i$1.length>s&&i$1.sort(e$1),n=i$1.shift(),s=i$1.length,n.__d&&(u=void 0,o=(r=(t=n).__v).__e,f=[],c=[],t.__P&&((u=w$1({},r)).__v=r.__v+1,l$1.vnode&&l$1.vnode(u),O(t.__P,u,r,t.__n,t.__P.namespaceURI,32&r.__u?[o]:null,f,null==o?S(r):o,!!(32&r.__u),c),u.__v=r.__v,u.__.__k[u.__i]=u,z$1(f,u,c),u.__e!=o&&C$1(u)));$.__r=0;}function I(n,l,t,u,i,r,o,e,f,c,s){var a,h,y,d,w,g,_=u&&u.__k||v$1,m=l.length;for(f=P(t,l,_,f,m),a=0;a<m;a++)null!=(y=t.__k[a])&&(h=-1===y.__i?p$1:_[y.__i]||p$1,y.__i=a,g=O(n,y,h,i,r,o,e,f,c,s),d=y.__e,y.ref&&h.ref!=y.ref&&(h.ref&&q(h.ref,null,y),s.push(y.ref,y.__c||d,y)),null==w&&null!=d&&(w=d),4&y.__u||h.__k===y.__k?f=A$1(y,f,n):"function"==typeof y.type&&void 0!==g?f=g:d&&(f=d.nextSibling),y.__u&=-7);return t.__e=w,f}function P(n,l,t,u,i){var r,o,e,f,c,s=t.length,a=s,h=0;for(n.__k=new Array(i),r=0;r<i;r++)null!=(o=l[r])&&"boolean"!=typeof o&&"function"!=typeof o?(f=r+h,(o=n.__k[r]="string"==typeof o||"number"==typeof o||"bigint"==typeof o||o.constructor==String?m$1(null,o,null,null,null):d$1(o)?m$1(k$1,{children:o},null,null,null):void 0===o.constructor&&o.__b>0?m$1(o.type,o.props,o.key,o.ref?o.ref:null,o.__v):o).__=n,o.__b=n.__b+1,e=null,-1!==(c=o.__i=L(o,t,f,a))&&(a--,(e=t[c])&&(e.__u|=2)),null==e||null===e.__v?(-1==c&&(i>s?h--:i<s&&h++),"function"!=typeof o.type&&(o.__u|=4)):c!=f&&(c==f-1?h--:c==f+1?h++:(c>f?h--:h++,o.__u|=4))):n.__k[r]=null;if(a)for(r=0;r<s;r++)null!=(e=t[r])&&0==(2&e.__u)&&(e.__e==u&&(u=S(e)),B$1(e,e));return u}function A$1(n,l,t){var u,i;if("function"==typeof n.type){for(u=n.__k,i=0;u&&i<u.length;i++)u[i]&&(u[i].__=n,l=A$1(u[i],l,t));return l}n.__e!=l&&(l&&n.type&&!t.contains(l)&&(l=S(n)),t.insertBefore(n.__e,l||null),l=n.__e);do{l=l&&l.nextSibling;}while(null!=l&&8==l.nodeType);return l}function L(n,l,t,u){var i,r,o=n.key,e=n.type,f=l[t];if(null===f&&null==n.key||f&&o==f.key&&e===f.type&&0==(2&f.__u))return t;if(u>(null!=f&&0==(2&f.__u)?1:0))for(i=t-1,r=t+1;i>=0||r<l.length;){if(i>=0){if((f=l[i])&&0==(2&f.__u)&&o==f.key&&e===f.type)return i;i--;}if(r<l.length){if((f=l[r])&&0==(2&f.__u)&&o==f.key&&e===f.type)return r;r++;}}return -1}function T$1(n,l,t){"-"==l[0]?n.setProperty(l,null==t?"":t):n[l]=null==t?"":"number"!=typeof t||y$1.test(l)?t:t+"px";}function j$1(n,l,t,u,i){var r;n:if("style"==l)if("string"==typeof t)n.style.cssText=t;else {if("string"==typeof u&&(n.style.cssText=u=""),u)for(l in u)t&&l in t||T$1(n.style,l,"");if(t)for(l in t)u&&t[l]===u[l]||T$1(n.style,l,t[l]);}else if("o"==l[0]&&"n"==l[1])r=l!=(l=l.replace(f$1,"$1")),l=l.toLowerCase()in n||"onFocusOut"==l||"onFocusIn"==l?l.toLowerCase().slice(2):l.slice(2),n.l||(n.l={}),n.l[l+r]=t,t?u?t.t=u.t:(t.t=c$1,n.addEventListener(l,r?a$1:s$1,r)):n.removeEventListener(l,r?a$1:s$1,r);else {if("http://www.w3.org/2000/svg"==i)l=l.replace(/xlink(H|:h)/,"h").replace(/sName$/,"s");else if("width"!=l&&"height"!=l&&"href"!=l&&"list"!=l&&"form"!=l&&"tabIndex"!=l&&"download"!=l&&"rowSpan"!=l&&"colSpan"!=l&&"role"!=l&&"popover"!=l&&l in n)try{n[l]=null==t?"":t;break n}catch(n){}"function"==typeof t||(null==t||!1===t&&"-"!=l[4]?n.removeAttribute(l):n.setAttribute(l,"popover"==l&&1==t?"":t));}}function F(n){return function(t){if(this.l){var u=this.l[t.type+n];if(null==t.u)t.u=c$1++;else if(t.u<u.t)return;return u(l$1.event?l$1.event(t):t)}}}function O(n,t,u,i,r,o,e,f,c,s){var a,h,p,v,y,_,m,b,S,C,M,$,P,A,H,L,T,j=t.type;if(void 0!==t.constructor)return null;128&u.__u&&(c=!!(32&u.__u),o=[f=t.__e=u.__e]),(a=l$1.__b)&&a(t);n:if("function"==typeof j)try{if(b=t.props,S="prototype"in j&&j.prototype.render,C=(a=j.contextType)&&i[a.__c],M=a?C?C.props.value:a.__:i,u.__c?m=(h=t.__c=u.__c).__=h.__E:(S?t.__c=h=new j(b,M):(t.__c=h=new x$1(b,M),h.constructor=j,h.render=D$1),C&&C.sub(h),h.props=b,h.state||(h.state={}),h.context=M,h.__n=i,p=h.__d=!0,h.__h=[],h._sb=[]),S&&null==h.__s&&(h.__s=h.state),S&&null!=j.getDerivedStateFromProps&&(h.__s==h.state&&(h.__s=w$1({},h.__s)),w$1(h.__s,j.getDerivedStateFromProps(b,h.__s))),v=h.props,y=h.state,h.__v=t,p)S&&null==j.getDerivedStateFromProps&&null!=h.componentWillMount&&h.componentWillMount(),S&&null!=h.componentDidMount&&h.__h.push(h.componentDidMount);else {if(S&&null==j.getDerivedStateFromProps&&b!==v&&null!=h.componentWillReceiveProps&&h.componentWillReceiveProps(b,M),!h.__e&&(null!=h.shouldComponentUpdate&&!1===h.shouldComponentUpdate(b,h.__s,M)||t.__v==u.__v)){for(t.__v!=u.__v&&(h.props=b,h.state=h.__s,h.__d=!1),t.__e=u.__e,t.__k=u.__k,t.__k.some(function(n){n&&(n.__=t);}),$=0;$<h._sb.length;$++)h.__h.push(h._sb[$]);h._sb=[],h.__h.length&&e.push(h);break n}null!=h.componentWillUpdate&&h.componentWillUpdate(b,h.__s,M),S&&null!=h.componentDidUpdate&&h.__h.push(function(){h.componentDidUpdate(v,y,_);});}if(h.context=M,h.props=b,h.__P=n,h.__e=!1,P=l$1.__r,A=0,S){for(h.state=h.__s,h.__d=!1,P&&P(t),a=h.render(h.props,h.state,h.context),H=0;H<h._sb.length;H++)h.__h.push(h._sb[H]);h._sb=[];}else do{h.__d=!1,P&&P(t),a=h.render(h.props,h.state,h.context),h.state=h.__s;}while(h.__d&&++A<25);h.state=h.__s,null!=h.getChildContext&&(i=w$1(w$1({},i),h.getChildContext())),S&&!p&&null!=h.getSnapshotBeforeUpdate&&(_=h.getSnapshotBeforeUpdate(v,y)),L=a,null!=a&&a.type===k$1&&null==a.key&&(L=N(a.props.children)),f=I(n,d$1(L)?L:[L],t,u,i,r,o,e,f,c,s),h.base=t.__e,t.__u&=-161,h.__h.length&&e.push(h),m&&(h.__E=h.__=null);}catch(n){if(t.__v=null,c||null!=o)if(n.then){for(t.__u|=c?160:128;f&&8==f.nodeType&&f.nextSibling;)f=f.nextSibling;o[o.indexOf(f)]=null,t.__e=f;}else for(T=o.length;T--;)g(o[T]);else t.__e=u.__e,t.__k=u.__k;l$1.__e(n,t,u);}else null==o&&t.__v==u.__v?(t.__k=u.__k,t.__e=u.__e):f=t.__e=V(u.__e,t,u,i,r,o,e,c,s);return (a=l$1.diffed)&&a(t),128&t.__u?void 0:f}function z$1(n,t,u){for(var i=0;i<u.length;i++)q(u[i],u[++i],u[++i]);l$1.__c&&l$1.__c(t,n),n.some(function(t){try{n=t.__h,t.__h=[],n.some(function(n){n.call(t);});}catch(n){l$1.__e(n,t.__v);}});}function N(n){return "object"!=typeof n||null==n?n:d$1(n)?n.map(N):w$1({},n)}function V(t,u,i,r,o,e,f,c,s){var a,h,v,y,w,_,m,b=i.props,k=u.props,x=u.type;if("svg"==x?o="http://www.w3.org/2000/svg":"math"==x?o="http://www.w3.org/1998/Math/MathML":o||(o="http://www.w3.org/1999/xhtml"),null!=e)for(a=0;a<e.length;a++)if((w=e[a])&&"setAttribute"in w==!!x&&(x?w.localName==x:3==w.nodeType)){t=w,e[a]=null;break}if(null==t){if(null==x)return document.createTextNode(k);t=document.createElementNS(o,x,k.is&&k),c&&(l$1.__m&&l$1.__m(u,e),c=!1),e=null;}if(null===x)b===k||c&&t.data===k||(t.data=k);else {if(e=e&&n.call(t.childNodes),b=i.props||p$1,!c&&null!=e)for(b={},a=0;a<t.attributes.length;a++)b[(w=t.attributes[a]).name]=w.value;for(a in b)if(w=b[a],"children"==a);else if("dangerouslySetInnerHTML"==a)v=w;else if(!(a in k)){if("value"==a&&"defaultValue"in k||"checked"==a&&"defaultChecked"in k)continue;j$1(t,a,null,w,o);}for(a in k)w=k[a],"children"==a?y=w:"dangerouslySetInnerHTML"==a?h=w:"value"==a?_=w:"checked"==a?m=w:c&&"function"!=typeof w||b[a]===w||j$1(t,a,w,b[a],o);if(h)c||v&&(h.__html===v.__html||h.__html===t.innerHTML)||(t.innerHTML=h.__html),u.__k=[];else if(v&&(t.innerHTML=""),I("template"===u.type?t.content:t,d$1(y)?y:[y],u,i,r,"foreignObject"==x?"http://www.w3.org/1999/xhtml":o,e,f,e?e[0]:i.__k&&S(i,0),c,s),null!=e)for(a=e.length;a--;)g(e[a]);c||(a="value","progress"==x&&null==_?t.removeAttribute("value"):void 0!==_&&(_!==t[a]||"progress"==x&&!_||"option"==x&&_!==b[a])&&j$1(t,a,_,b[a],o),a="checked",void 0!==m&&m!==t[a]&&j$1(t,a,m,b[a],o));}return t}function q(n,t,u){try{if("function"==typeof n){var i="function"==typeof n.__u;i&&n.__u(),i&&null==t||(n.__u=n(t));}else n.current=t;}catch(n){l$1.__e(n,u);}}function B$1(n,t,u){var i,r;if(l$1.unmount&&l$1.unmount(n),(i=n.ref)&&(i.current&&i.current!==n.__e||q(i,null,t)),null!=(i=n.__c)){if(i.componentWillUnmount)try{i.componentWillUnmount();}catch(n){l$1.__e(n,t);}i.base=i.__P=null;}if(i=n.__k)for(r=0;r<i.length;r++)i[r]&&B$1(i[r],t,u||"function"!=typeof n.type);u||g(n.__e),n.__c=n.__=n.__e=void 0;}function D$1(n,l,t){return this.constructor(n,t)}function E(t,u,i){var r,o,e,f;u==document&&(u=document.documentElement),l$1.__&&l$1.__(t,u),o=(r="function"==typeof i)?null:i&&i.__k||u.__k,e=[],f=[],O(u,t=(!r&&i||u).__k=_$1(k$1,null,[t]),o||p$1,p$1,u.namespaceURI,!r&&i?[i]:o?null:u.firstChild?n.call(u.childNodes):null,e,!r&&i?i:o?o.__e:u.firstChild,r,f),z$1(e,t,f);}function K(n){function l(n){var t,u;return this.getChildContext||(t=new Set,(u={})[l.__c]=this,this.getChildContext=function(){return u},this.componentWillUnmount=function(){t=null;},this.shouldComponentUpdate=function(n){this.props.value!==n.value&&t.forEach(function(n){n.__e=!0,M(n);});},this.sub=function(n){t.add(n);var l=n.componentWillUnmount;n.componentWillUnmount=function(){t&&t.delete(n),l&&l.call(n);};}),n.children}return l.__c="__cC"+h$1++,l.__=n,l.Provider=l.__l=(l.Consumer=function(n,l){return n.children(l)}).contextType=l,l}n=v$1.slice,l$1={__e:function(n,l,t,u){for(var i,r,o;l=l.__;)if((i=l.__c)&&!i.__)try{if((r=i.constructor)&&null!=r.getDerivedStateFromError&&(i.setState(r.getDerivedStateFromError(n)),o=i.__d),null!=i.componentDidCatch&&(i.componentDidCatch(n,u||{}),o=i.__d),o)return i.__E=i}catch(l){n=l;}throw n}},t$1=0,x$1.prototype.setState=function(n,l){var t;t=null!=this.__s&&this.__s!==this.state?this.__s:this.__s=w$1({},this.state),"function"==typeof n&&(n=n(w$1({},t),this.props)),n&&w$1(t,n),null!=n&&this.__v&&(l&&this._sb.push(l),M(this));},x$1.prototype.forceUpdate=function(n){this.__v&&(this.__e=!0,n&&this.__h.push(n),M(this));},x$1.prototype.render=k$1,i$1=[],o$1="function"==typeof Promise?Promise.prototype.then.bind(Promise.resolve()):setTimeout,e$1=function(n,l){return n.__v.__b-l.__v.__b},$.__r=0,f$1=/(PointerCapture)$|Capture$/i,c$1=0,s$1=F(!1),a$1=F(!0),h$1=0;

  var t,r,u,i,o=0,f=[],c=l$1,e=c.__b,a=c.__r,v=c.diffed,l=c.__c,m=c.unmount,s=c.__;function p(n,t){c.__h&&c.__h(r,n,o||t),o=0;var u=r.__H||(r.__H={__:[],__h:[]});return n>=u.__.length&&u.__.push({}),u.__[n]}function d(n){return o=1,h(D,n)}function h(n,u,i){var o=p(t++,2);if(o.t=n,!o.__c&&(o.__=[i?i(u):D(void 0,u),function(n){var t=o.__N?o.__N[0]:o.__[0],r=o.t(t,n);t!==r&&(o.__N=[r,o.__[1]],o.__c.setState({}));}],o.__c=r,!r.__f)){var f=function(n,t,r){if(!o.__c.__H)return !0;var u=o.__c.__H.__.filter(function(n){return !!n.__c});if(u.every(function(n){return !n.__N}))return !c||c.call(this,n,t,r);var i=o.__c.props!==n;return u.forEach(function(n){if(n.__N){var t=n.__[0];n.__=n.__N,n.__N=void 0,t!==n.__[0]&&(i=!0);}}),c&&c.call(this,n,t,r)||i};r.__f=!0;var c=r.shouldComponentUpdate,e=r.componentWillUpdate;r.componentWillUpdate=function(n,t,r){if(this.__e){var u=c;c=void 0,f(n,t,r),c=u;}e&&e.call(this,n,t,r);},r.shouldComponentUpdate=f;}return o.__N||o.__}function y(n,u){var i=p(t++,3);!c.__s&&C(i.__H,u)&&(i.__=n,i.u=u,r.__H.__h.push(i));}function _(n,u){var i=p(t++,4);!c.__s&&C(i.__H,u)&&(i.__=n,i.u=u,r.__h.push(i));}function A(n){return o=5,T(function(){return {current:n}},[])}function T(n,r){var u=p(t++,7);return C(u.__H,r)&&(u.__=n(),u.__H=r,u.__h=n),u.__}function x(n){var u=r.context[n.__c],i=p(t++,9);return i.c=n,u?(null==i.__&&(i.__=!0,u.sub(r)),u.props.value):n.__}function j(){for(var n;n=f.shift();)if(n.__P&&n.__H)try{n.__H.__h.forEach(z),n.__H.__h.forEach(B),n.__H.__h=[];}catch(t){n.__H.__h=[],c.__e(t,n.__v);}}c.__b=function(n){r=null,e&&e(n);},c.__=function(n,t){n&&t.__k&&t.__k.__m&&(n.__m=t.__k.__m),s&&s(n,t);},c.__r=function(n){a&&a(n),t=0;var i=(r=n.__c).__H;i&&(u===r?(i.__h=[],r.__h=[],i.__.forEach(function(n){n.__N&&(n.__=n.__N),n.u=n.__N=void 0;})):(i.__h.forEach(z),i.__h.forEach(B),i.__h=[],t=0)),u=r;},c.diffed=function(n){v&&v(n);var t=n.__c;t&&t.__H&&(t.__H.__h.length&&(1!==f.push(t)&&i===c.requestAnimationFrame||((i=c.requestAnimationFrame)||w)(j)),t.__H.__.forEach(function(n){n.u&&(n.__H=n.u),n.u=void 0;})),u=r=null;},c.__c=function(n,t){t.some(function(n){try{n.__h.forEach(z),n.__h=n.__h.filter(function(n){return !n.__||B(n)});}catch(r){t.some(function(n){n.__h&&(n.__h=[]);}),t=[],c.__e(r,n.__v);}}),l&&l(n,t);},c.unmount=function(n){m&&m(n);var t,r=n.__c;r&&r.__H&&(r.__H.__.forEach(function(n){try{z(n);}catch(n){t=n;}}),r.__H=void 0,t&&c.__e(t,r.__v));};var k="function"==typeof requestAnimationFrame;function w(n){var t,r=function(){clearTimeout(u),k&&cancelAnimationFrame(t),setTimeout(n);},u=setTimeout(r,100);k&&(t=requestAnimationFrame(r));}function z(n){var t=r,u=n.__c;"function"==typeof u&&(n.__c=void 0,u()),r=t;}function B(n){var t=r;n.__c=n.__(),r=t;}function C(n,t){return !n||n.length!==t.length||t.some(function(t,r){return t!==n[r]})}function D(n,t){return "function"==typeof t?t(n):t}

  var languages = [];
  var setLanguages = function setLanguages2(desc) {
    var en = desc.en;
    Object.entries(desc).forEach(function(_ref) {
      var _ref2 = _slicedToArray(_ref, 2), name = _ref2[0], lng = _ref2[1];
      languages.push({
        name,
        lng: _objectSpread2(_objectSpread2({}, en), lng)
      });
    });
  };
  var navigatorLanguage = (navigator.languages && navigator.languages.length && navigator.languages[0] || navigator.userLanguage || navigator.language || navigator.browserLanguage || "en").substr(0, 2).toLowerCase();
  var getDefaultLanguage = function getDefaultLanguage2() {
    return languages.find(function(lng) {
      return lng.name === navigatorLanguage;
    }) || languages.find(function(lng) {
      return lng.name === "en";
    });
  };
  var getLanguageByName = function getLanguageByName2(name) {
    if (["be", "kk", "uk", "uz"].some(function(n) {
      return n === name;
    })) {
      name = "ru";
    }
    return languages.find(function(lng) {
      return lng.name === name;
    }) || languages.find(function(lng) {
      return lng.name === "en";
    });
  };
  var LanguageContext = K();

  var IconText = function IconText2(_ref) {
    var widthScreen = _ref.widthScreen, _ref$icon = _ref.icon, icon = _ref$icon === void 0 ? "" : _ref$icon, nameOfElement = _ref.nameOfElement, classDiv = _ref.classDiv, _ref$addedTopMargin = _ref.addedTopMargin, addedTopMargin = _ref$addedTopMargin === void 0 ? 0 : _ref$addedTopMargin, _ref$textSign = _ref.textSign, textSign = _ref$textSign === void 0 ? "" : _ref$textSign, _ref$textColor = _ref.textColor, textColor = _ref$textColor === void 0 ? "white" : _ref$textColor, value = _ref.value, _ref$valueMax = _ref.valueMax, valueMax = _ref$valueMax === void 0 ? null : _ref$valueMax, _ref$iconSize = _ref.iconSize, iconSize = _ref$iconSize === void 0 ? 50 : _ref$iconSize, _ref$marginLeftAdd = _ref.marginLeftAdd, marginLeftAdd = _ref$marginLeftAdd === void 0 ? 10 : _ref$marginLeftAdd, _ref$minWidthText = _ref.minWidthText, minWidthText = _ref$minWidthText === void 0 ? 90 : _ref$minWidthText, _ref$elemHeight = _ref.elemHeight, elemHeight = _ref$elemHeight === void 0 ? 50 : _ref$elemHeight, _ref$normFont = _ref.normFont, normFont = _ref$normFont === void 0 ? 35 : _ref$normFont, _ref$sidePadding = _ref.sidePadding, sidePadding = _ref$sidePadding === void 0 ? 10 : _ref$sidePadding, _ref$widthPrc = _ref.widthPrc, widthPrc = _ref$widthPrc === void 0 ? 0.1 : _ref$widthPrc, _ref$widthMin = _ref.widthMin, widthMin = _ref$widthMin === void 0 ? 140 : _ref$widthMin, _ref$widthMax = _ref.widthMax, widthMax = _ref$widthMax === void 0 ? 170 : _ref$widthMax;
    var _useContext = x(LanguageContext); _useContext.lng;
    var resultTextShow;
    var maxAm = valueMax;
    if (nameOfElement == "ammo") {
      if (maxAm !== null) {
        maxAm = maxAm == 999 ? "\u221E" : maxAm;
        resultTextShow = " " + value + "/" + maxAm;
      } else
        resultTextShow = " " + value;
    } else {
      resultTextShow = "" + textSign + value;
    }
    y(function() {
    });
    var maxElemWidth = widthMax > widthScreen * widthPrc ? widthScreen * widthPrc : widthMax;
    var elemWidth = maxElemWidth > widthMin ? maxElemWidth : widthMin;
    var iconWidth = iconSize;
    var padding = 5;
    var fontStyle = {
      fontSize: "".concat(normFont, "px"),
      textAlign: "center",
      marginTop: "".concat(-(normFont - elemHeight) * 0.5, "px"),
      lineHeight: "100%",
      color: textColor
    };
    var textSideRight = {
      position: "relative",
      marginLeft: "".concat(-padding, "px"),
      minWidth: "".concat(minWidthText, "px")
    };
    var elementStyle = {
      display: "flex",
      justifyContent: "flex-start",
      height: "".concat(elemHeight, "px"),
      width: "".concat(elemWidth, "px"),
      margin: "".concat(sidePadding, "px"),
      marginTop: "".concat(addedTopMargin, "px"),
      marginLeft: "".concat(marginLeftAdd, "px")
    };
    var iconStyleRight = {
      position: "relative",
      padding: padding + "px",
      height: iconWidth + "px"
    };
    return _$1("div", {
      id: nameOfElement,
      style: elementStyle,
      "class": classDiv + " inGame"
    }, icon != "" && _$1("div", {
      id: nameOfElement + "IconBack",
      style: iconStyleRight,
      "class": " zeroPos noStretch"
    }, _$1("img", {
      id: nameOfElement + "Icon",
      width: iconWidth,
      height: iconWidth,
      src: "assets" + "/images/" + icon + ".png"
    })), _$1("div", {
      id: nameOfElement + "Text",
      style: textSideRight,
      "class": ""
    }, _$1("p", {
      style: fontStyle
    }, resultTextShow)));
  };

  function resizeToWindow() {
    var _useState = d({
      width: void 0,
      height: void 0
    }), _useState2 = _slicedToArray(_useState, 2), windowSize = _useState2[0], setWindowSize = _useState2[1];
    y(function() {
      function handleResize() {
        setWindowSize({
          width: window.innerWidth,
          height: window.innerHeight
        });
      }
      window.addEventListener("resize", handleResize);
      handleResize();
      return function() {
        return window.removeEventListener("resize", handleResize);
      };
    }, []);
    return windowSize;
  }

  var localStorageApi = {
    getJSON: function getJSON(storageName) {
      try {
        var storage = window.localStorage || {};
      } catch (e) {
        return "{}";
      }
      if (!localStorage)
        return "{}";
      return JSON.parse(window.localStorage[storageName] || "{}");
    },
    set: function set(storageName, data) {
      try {
        var storage = window.localStorage || {};
      } catch (e) {
        return;
      }
      if (!localStorage)
        return;
      window.localStorage[storageName] = JSON.stringify(data);
    }
  };
  var hexToRgb = function hexToRgb2(hex) {
    var r = parseInt(hex.substring(1, 3), 16);
    var g = parseInt(hex.substring(3, 5), 16);
    var b = parseInt(hex.substring(5, 7), 16);
    return {
      r,
      g,
      b
    };
  };
  var hsvToHex = function hsvToHex2(hsv) {
    return rgbToHex(hsvToRgb(hsv));
  };
  var hsvToRgb = function hsvToRgb2(_ref) {
    var h = _ref.h, s = _ref.s, v = _ref.v;
    var r, g, b;
    var i;
    var f, p, q, t;
    h = Math.max(0, Math.min(360, h));
    s = Math.max(0, Math.min(100, s));
    v = Math.max(0, Math.min(100, v));
    s /= 100;
    v /= 100;
    if (s == 0) {
      r = g = b = v;
      return {
        r: Math.round(r * 255),
        g: Math.round(g * 255),
        b: Math.round(b * 255)
      };
    }
    h /= 60;
    i = Math.floor(h);
    f = h - i;
    p = v * (1 - s);
    q = v * (1 - s * f);
    t = v * (1 - s * (1 - f));
    switch (i) {
      case 0:
        r = v;
        g = t;
        b = p;
        break;
      case 1:
        r = q;
        g = v;
        b = p;
        break;
      case 2:
        r = p;
        g = v;
        b = t;
        break;
      case 3:
        r = p;
        g = q;
        b = v;
        break;
      case 4:
        r = t;
        g = p;
        b = v;
        break;
      default:
        r = v;
        g = p;
        b = q;
    }
    return {
      r: Math.round(r * 255),
      g: Math.round(g * 255),
      b: Math.round(b * 255)
    };
  };
  var rgb2hsv = function rgb2hsv2(_ref2) {
    var r = _ref2.r, g = _ref2.g, b = _ref2.b;
    var rabs, gabs, babs, rr, gg, bb, h, s, v, diff, diffc, percentRoundFn;
    rabs = r / 255;
    gabs = g / 255;
    babs = b / 255;
    v = Math.max(rabs, gabs, babs), diff = v - Math.min(rabs, gabs, babs);
    diffc = function diffc2(c) {
      return (v - c) / 6 / diff + 1 / 2;
    };
    percentRoundFn = function percentRoundFn2(num) {
      return Math.round(num * 100) / 100;
    };
    if (diff == 0) {
      h = s = 0;
    } else {
      s = diff / v;
      rr = diffc(rabs);
      gg = diffc(gabs);
      bb = diffc(babs);
      if (rabs === v) {
        h = bb - gg;
      } else if (gabs === v) {
        h = 1 / 3 + rr - bb;
      } else if (babs === v) {
        h = 2 / 3 + gg - rr;
      }
      if (h < 0) {
        h += 1;
      } else if (h > 1) {
        h -= 1;
      }
    }
    return {
      h: Math.round(h * 360),
      s: percentRoundFn(s * 100),
      v: percentRoundFn(v * 100)
    };
  };
  var rgbToHex = function rgbToHex2(_ref3) {
    var r = _ref3.r, g = _ref3.g, b = _ref3.b;
    var colorToString = function colorToString2(color) {
      var s = color.toString(16);
      return s.length < 2 ? "0".concat(s) : s;
    };
    return "#".concat(colorToString(r)).concat(colorToString(g)).concat(colorToString(b));
  };
  function isEmpty(obj) {
    for (var prop in obj) {
      if (Object.prototype.hasOwnProperty.call(obj, prop)) {
        return false;
      }
    }
    return JSON.stringify(obj) === JSON.stringify({});
  }
  function getReq(theUrl, callback) {
    var arg = arguments.length > 2 && arguments[2] !== void 0 ? arguments[2] : null;
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.onreadystatechange = function() {
      if (xmlHttp.readyState == 4 && xmlHttp.status == 200)
        callback(xmlHttp.responseText, arg);
    };
    xmlHttp.open("GET", theUrl, true);
    xmlHttp.send(null);
  }
  var isObject = function isObject2(item) {
    return item && _typeof(item) === "object" && !Array.isArray(item);
  };
  var _mergeDeep$1 = function mergeDeep(target) {
    for (var _len = arguments.length, sources = new Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
      sources[_key - 1] = arguments[_key];
    }
    if (!sources.length)
      return target;
    var source = sources.shift();
    if (isObject(target) && isObject(source)) {
      for (var key in source) {
        if (isObject(source[key])) {
          if (!target[key])
            Object.assign(target, _defineProperty({}, key, {}));
          _mergeDeep$1(target[key], source[key]);
        } else {
          Object.assign(target, _defineProperty({}, key, source[key]));
        }
      }
    }
    return _mergeDeep$1.apply(void 0, [target].concat(sources));
  };
  var formatTime = function formatTime2(timeInSec) {
    var timeInSecnds = Math.max(0, Number(timeInSec));
    var iMins = Math.floor(timeInSecnds / 60);
    var iSecs = timeInSecnds - iMins * 60;
    iSecs = parseFloat(iSecs).toFixed(0);
    var szRet = "";
    if (iMins < 10) {
      szRet += "0" + iMins + ":";
    } else {
      szRet += iMins + ":";
    }
    if (iSecs < 10) {
      szRet += "0" + iSecs;
    } else {
      szRet += iSecs;
    }
    return szRet;
  };
  function uuid() {
    return "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g, function(c) {
      var r = Math.random() * 16 | 0, v = c == "x" ? r : r & 3 | 8;
      return v.toString(16);
    });
  }
  function isMobile() {
    var hasTouchScreen = false;
    if ("maxTouchPoints" in navigator) {
      hasTouchScreen = navigator.maxTouchPoints > 0;
    } else if ("msMaxTouchPoints" in navigator) {
      hasTouchScreen = navigator.msMaxTouchPoints > 0;
    } else {
      var mQ = window.matchMedia && matchMedia("(pointer:coarse)");
      if (mQ && mQ.media === "(pointer:coarse)") {
        hasTouchScreen = !!mQ.matches;
      } else if ("orientation" in window) {
        hasTouchScreen = true;
      } else {
        var UA = navigator.userAgent;
        hasTouchScreen = /\b(BlackBerry|webOS|iPhone|IEMobile)\b/i.test(UA) || /\b(Android|Windows Phone|iPad|iPod)\b/i.test(UA);
      }
    }
    return hasTouchScreen && window.innerHeight > window.innerWidth;
  }
  function request(url) {
    var cb = arguments.length > 1 && arguments[1] !== void 0 ? arguments[1] : null;
    var data = arguments.length > 2 && arguments[2] !== void 0 ? arguments[2] : null;
    var cbCatch = arguments.length > 3 && arguments[3] !== void 0 ? arguments[3] : null;
    var multiData = arguments.length > 4 && arguments[4] !== void 0 ? arguments[4] : false;
    var prm = new Promise(function(resolve, reject) {
      var req = new XMLHttpRequest();
      req.open("POST", url, true);
      if (!multiData)
        req.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
      else
        req.setRequestHeader("Content-type", "text/plain");
      req.onreadystatechange = function(aEvt) {
        if (req.readyState == 4) {
          if (req.status == 200) {
            resolve(req.responseText);
          } else {
            reject();
          }
        }
      };
      req.send(data);
    });
    prm.then(function(v) {
      if (cb)
        cb(v);
    })["catch"](function() {
      if (cbCatch)
        cbCatch();
    });
  }
  function requestAPI(url, data, cb) {
    var cbCatch = arguments.length > 3 && arguments[3] !== void 0 ? arguments[3] : null;
    var multiData = arguments.length > 4 && arguments[4] !== void 0 ? arguments[4] : false;
    request(url, cb, JSON.stringify(data), cbCatch, multiData);
  }

  function _assertThisInitialized(self) { if (self === void 0) { throw new ReferenceError("this hasn't been initialised - super() hasn't been called"); } return self; }

  function _inheritsLoose(subClass, superClass) { subClass.prototype = Object.create(superClass.prototype); subClass.prototype.constructor = subClass; subClass.__proto__ = superClass; }

  /*!
   * GSAP 3.12.7
   * https://gsap.com
   *
   * @license Copyright 2008-2025, GreenSock. All rights reserved.
   * Subject to the terms at https://gsap.com/standard-license or for
   * Club GSAP members, the agreement issued with that membership.
   * @author: Jack Doyle, jack@greensock.com
  */

  /* eslint-disable */
  var _config = {
    autoSleep: 120,
    force3D: "auto",
    nullTargetWarn: 1,
    units: {
      lineHeight: ""
    }
  },
      _defaults = {
    duration: .5,
    overwrite: false,
    delay: 0
  },
      _suppressOverwrites,
      _reverting$1,
      _context,
      _bigNum$1 = 1e8,
      _tinyNum = 1 / _bigNum$1,
      _2PI = Math.PI * 2,
      _HALF_PI = _2PI / 4,
      _gsID = 0,
      _sqrt = Math.sqrt,
      _cos = Math.cos,
      _sin = Math.sin,
      _isString = function _isString(value) {
    return typeof value === "string";
  },
      _isFunction = function _isFunction(value) {
    return typeof value === "function";
  },
      _isNumber = function _isNumber(value) {
    return typeof value === "number";
  },
      _isUndefined = function _isUndefined(value) {
    return typeof value === "undefined";
  },
      _isObject = function _isObject(value) {
    return typeof value === "object";
  },
      _isNotFalse = function _isNotFalse(value) {
    return value !== false;
  },
      _windowExists$1 = function _windowExists() {
    return typeof window !== "undefined";
  },
      _isFuncOrString = function _isFuncOrString(value) {
    return _isFunction(value) || _isString(value);
  },
      _isTypedArray = typeof ArrayBuffer === "function" && ArrayBuffer.isView || function () {},
      // note: IE10 has ArrayBuffer, but NOT ArrayBuffer.isView().
  _isArray = Array.isArray,
      _strictNumExp = /(?:-?\.?\d|\.)+/gi,
      //only numbers (including negatives and decimals) but NOT relative values.
  _numExp = /[-+=.]*\d+[.e\-+]*\d*[e\-+]*\d*/g,
      //finds any numbers, including ones that start with += or -=, negative numbers, and ones in scientific notation like 1e-8.
  _numWithUnitExp = /[-+=.]*\d+[.e-]*\d*[a-z%]*/g,
      _complexStringNumExp = /[-+=.]*\d+\.?\d*(?:e-|e\+)?\d*/gi,
      //duplicate so that while we're looping through matches from exec(), it doesn't contaminate the lastIndex of _numExp which we use to search for colors too.
  _relExp = /[+-]=-?[.\d]+/,
      _delimitedValueExp = /[^,'"\[\]\s]+/gi,
      // previously /[#\-+.]*\b[a-z\d\-=+%.]+/gi but didn't catch special characters.
  _unitExp = /^[+\-=e\s\d]*\d+[.\d]*([a-z]*|%)\s*$/i,
      _globalTimeline,
      _win$1,
      _coreInitted,
      _doc$1,
      _globals = {},
      _installScope = {},
      _coreReady,
      _install = function _install(scope) {
    return (_installScope = _merge(scope, _globals)) && gsap;
  },
      _missingPlugin = function _missingPlugin(property, value) {
    return console.warn("Invalid property", property, "set to", value, "Missing plugin? gsap.registerPlugin()");
  },
      _warn = function _warn(message, suppress) {
    return !suppress && console.warn(message);
  },
      _addGlobal = function _addGlobal(name, obj) {
    return name && (_globals[name] = obj) && _installScope && (_installScope[name] = obj) || _globals;
  },
      _emptyFunc = function _emptyFunc() {
    return 0;
  },
      _startAtRevertConfig = {
    suppressEvents: true,
    isStart: true,
    kill: false
  },
      _revertConfigNoKill = {
    suppressEvents: true,
    kill: false
  },
      _revertConfig = {
    suppressEvents: true
  },
      _reservedProps = {},
      _lazyTweens = [],
      _lazyLookup = {},
      _lastRenderedFrame,
      _plugins = {},
      _effects = {},
      _nextGCFrame = 30,
      _harnessPlugins = [],
      _callbackNames = "",
      _harness = function _harness(targets) {
    var target = targets[0],
        harnessPlugin,
        i;
    _isObject(target) || _isFunction(target) || (targets = [targets]);

    if (!(harnessPlugin = (target._gsap || {}).harness)) {
      // find the first target with a harness. We assume targets passed into an animation will be of similar type, meaning the same kind of harness can be used for them all (performance optimization)
      i = _harnessPlugins.length;

      while (i-- && !_harnessPlugins[i].targetTest(target)) {}

      harnessPlugin = _harnessPlugins[i];
    }

    i = targets.length;

    while (i--) {
      targets[i] && (targets[i]._gsap || (targets[i]._gsap = new GSCache(targets[i], harnessPlugin))) || targets.splice(i, 1);
    }

    return targets;
  },
      _getCache = function _getCache(target) {
    return target._gsap || _harness(toArray(target))[0]._gsap;
  },
      _getProperty = function _getProperty(target, property, v) {
    return (v = target[property]) && _isFunction(v) ? target[property]() : _isUndefined(v) && target.getAttribute && target.getAttribute(property) || v;
  },
      _forEachName = function _forEachName(names, func) {
    return (names = names.split(",")).forEach(func) || names;
  },
      //split a comma-delimited list of names into an array, then run a forEach() function and return the split array (this is just a way to consolidate/shorten some code).
  _round = function _round(value) {
    return Math.round(value * 100000) / 100000 || 0;
  },
      _roundPrecise = function _roundPrecise(value) {
    return Math.round(value * 10000000) / 10000000 || 0;
  },
      // increased precision mostly for timing values.
  _parseRelative = function _parseRelative(start, value) {
    var operator = value.charAt(0),
        end = parseFloat(value.substr(2));
    start = parseFloat(start);
    return operator === "+" ? start + end : operator === "-" ? start - end : operator === "*" ? start * end : start / end;
  },
      _arrayContainsAny = function _arrayContainsAny(toSearch, toFind) {
    //searches one array to find matches for any of the items in the toFind array. As soon as one is found, it returns true. It does NOT return all the matches; it's simply a boolean search.
    var l = toFind.length,
        i = 0;

    for (; toSearch.indexOf(toFind[i]) < 0 && ++i < l;) {}

    return i < l;
  },
      _lazyRender = function _lazyRender() {
    var l = _lazyTweens.length,
        a = _lazyTweens.slice(0),
        i,
        tween;

    _lazyLookup = {};
    _lazyTweens.length = 0;

    for (i = 0; i < l; i++) {
      tween = a[i];
      tween && tween._lazy && (tween.render(tween._lazy[0], tween._lazy[1], true)._lazy = 0);
    }
  },
      _lazySafeRender = function _lazySafeRender(animation, time, suppressEvents, force) {
    _lazyTweens.length && !_reverting$1 && _lazyRender();
    animation.render(time, suppressEvents, force || _reverting$1 && time < 0 && (animation._initted || animation._startAt));
    _lazyTweens.length && !_reverting$1 && _lazyRender(); //in case rendering caused any tweens to lazy-init, we should render them because typically when someone calls seek() or time() or progress(), they expect an immediate render.
  },
      _numericIfPossible = function _numericIfPossible(value) {
    var n = parseFloat(value);
    return (n || n === 0) && (value + "").match(_delimitedValueExp).length < 2 ? n : _isString(value) ? value.trim() : value;
  },
      _passThrough = function _passThrough(p) {
    return p;
  },
      _setDefaults = function _setDefaults(obj, defaults) {
    for (var p in defaults) {
      p in obj || (obj[p] = defaults[p]);
    }

    return obj;
  },
      _setKeyframeDefaults = function _setKeyframeDefaults(excludeDuration) {
    return function (obj, defaults) {
      for (var p in defaults) {
        p in obj || p === "duration" && excludeDuration || p === "ease" || (obj[p] = defaults[p]);
      }
    };
  },
      _merge = function _merge(base, toMerge) {
    for (var p in toMerge) {
      base[p] = toMerge[p];
    }

    return base;
  },
      _mergeDeep = function _mergeDeep(base, toMerge) {
    for (var p in toMerge) {
      p !== "__proto__" && p !== "constructor" && p !== "prototype" && (base[p] = _isObject(toMerge[p]) ? _mergeDeep(base[p] || (base[p] = {}), toMerge[p]) : toMerge[p]);
    }

    return base;
  },
      _copyExcluding = function _copyExcluding(obj, excluding) {
    var copy = {},
        p;

    for (p in obj) {
      p in excluding || (copy[p] = obj[p]);
    }

    return copy;
  },
      _inheritDefaults = function _inheritDefaults(vars) {
    var parent = vars.parent || _globalTimeline,
        func = vars.keyframes ? _setKeyframeDefaults(_isArray(vars.keyframes)) : _setDefaults;

    if (_isNotFalse(vars.inherit)) {
      while (parent) {
        func(vars, parent.vars.defaults);
        parent = parent.parent || parent._dp;
      }
    }

    return vars;
  },
      _arraysMatch = function _arraysMatch(a1, a2) {
    var i = a1.length,
        match = i === a2.length;

    while (match && i-- && a1[i] === a2[i]) {}

    return i < 0;
  },
      _addLinkedListItem = function _addLinkedListItem(parent, child, firstProp, lastProp, sortBy) {
    if (firstProp === void 0) {
      firstProp = "_first";
    }

    if (lastProp === void 0) {
      lastProp = "_last";
    }

    var prev = parent[lastProp],
        t;

    if (sortBy) {
      t = child[sortBy];

      while (prev && prev[sortBy] > t) {
        prev = prev._prev;
      }
    }

    if (prev) {
      child._next = prev._next;
      prev._next = child;
    } else {
      child._next = parent[firstProp];
      parent[firstProp] = child;
    }

    if (child._next) {
      child._next._prev = child;
    } else {
      parent[lastProp] = child;
    }

    child._prev = prev;
    child.parent = child._dp = parent;
    return child;
  },
      _removeLinkedListItem = function _removeLinkedListItem(parent, child, firstProp, lastProp) {
    if (firstProp === void 0) {
      firstProp = "_first";
    }

    if (lastProp === void 0) {
      lastProp = "_last";
    }

    var prev = child._prev,
        next = child._next;

    if (prev) {
      prev._next = next;
    } else if (parent[firstProp] === child) {
      parent[firstProp] = next;
    }

    if (next) {
      next._prev = prev;
    } else if (parent[lastProp] === child) {
      parent[lastProp] = prev;
    }

    child._next = child._prev = child.parent = null; // don't delete the _dp just so we can revert if necessary. But parent should be null to indicate the item isn't in a linked list.
  },
      _removeFromParent = function _removeFromParent(child, onlyIfParentHasAutoRemove) {
    child.parent && (!onlyIfParentHasAutoRemove || child.parent.autoRemoveChildren) && child.parent.remove && child.parent.remove(child);
    child._act = 0;
  },
      _uncache = function _uncache(animation, child) {
    if (animation && (!child || child._end > animation._dur || child._start < 0)) {
      // performance optimization: if a child animation is passed in we should only uncache if that child EXTENDS the animation (its end time is beyond the end)
      var a = animation;

      while (a) {
        a._dirty = 1;
        a = a.parent;
      }
    }

    return animation;
  },
      _recacheAncestors = function _recacheAncestors(animation) {
    var parent = animation.parent;

    while (parent && parent.parent) {
      //sometimes we must force a re-sort of all children and update the duration/totalDuration of all ancestor timelines immediately in case, for example, in the middle of a render loop, one tween alters another tween's timeScale which shoves its startTime before 0, forcing the parent timeline to shift around and shiftChildren() which could affect that next tween's render (startTime). Doesn't matter for the root timeline though.
      parent._dirty = 1;
      parent.totalDuration();
      parent = parent.parent;
    }

    return animation;
  },
      _rewindStartAt = function _rewindStartAt(tween, totalTime, suppressEvents, force) {
    return tween._startAt && (_reverting$1 ? tween._startAt.revert(_revertConfigNoKill) : tween.vars.immediateRender && !tween.vars.autoRevert || tween._startAt.render(totalTime, true, force));
  },
      _hasNoPausedAncestors = function _hasNoPausedAncestors(animation) {
    return !animation || animation._ts && _hasNoPausedAncestors(animation.parent);
  },
      _elapsedCycleDuration = function _elapsedCycleDuration(animation) {
    return animation._repeat ? _animationCycle(animation._tTime, animation = animation.duration() + animation._rDelay) * animation : 0;
  },
      // feed in the totalTime and cycleDuration and it'll return the cycle (iteration minus 1) and if the playhead is exactly at the very END, it will NOT bump up to the next cycle.
  _animationCycle = function _animationCycle(tTime, cycleDuration) {
    var whole = Math.floor(tTime = _roundPrecise(tTime / cycleDuration));
    return tTime && whole === tTime ? whole - 1 : whole;
  },
      _parentToChildTotalTime = function _parentToChildTotalTime(parentTime, child) {
    return (parentTime - child._start) * child._ts + (child._ts >= 0 ? 0 : child._dirty ? child.totalDuration() : child._tDur);
  },
      _setEnd = function _setEnd(animation) {
    return animation._end = _roundPrecise(animation._start + (animation._tDur / Math.abs(animation._ts || animation._rts || _tinyNum) || 0));
  },
      _alignPlayhead = function _alignPlayhead(animation, totalTime) {
    // adjusts the animation's _start and _end according to the provided totalTime (only if the parent's smoothChildTiming is true and the animation isn't paused). It doesn't do any rendering or forcing things back into parent timelines, etc. - that's what totalTime() is for.
    var parent = animation._dp;

    if (parent && parent.smoothChildTiming && animation._ts) {
      animation._start = _roundPrecise(parent._time - (animation._ts > 0 ? totalTime / animation._ts : ((animation._dirty ? animation.totalDuration() : animation._tDur) - totalTime) / -animation._ts));

      _setEnd(animation);

      parent._dirty || _uncache(parent, animation); //for performance improvement. If the parent's cache is already dirty, it already took care of marking the ancestors as dirty too, so skip the function call here.
    }

    return animation;
  },

  /*
  _totalTimeToTime = (clampedTotalTime, duration, repeat, repeatDelay, yoyo) => {
  	let cycleDuration = duration + repeatDelay,
  		time = _round(clampedTotalTime % cycleDuration);
  	if (time > duration) {
  		time = duration;
  	}
  	return (yoyo && (~~(clampedTotalTime / cycleDuration) & 1)) ? duration - time : time;
  },
  */
  _postAddChecks = function _postAddChecks(timeline, child) {
    var t;

    if (child._time || !child._dur && child._initted || child._start < timeline._time && (child._dur || !child.add)) {
      // in case, for example, the _start is moved on a tween that has already rendered, or if it's being inserted into a timeline BEFORE where the playhead is currently. Imagine it's at its end state, then the startTime is moved WAY later (after the end of this timeline), it should render at its beginning. Special case: if it's a timeline (has .add() method) and no duration, we can skip rendering because the user may be populating it AFTER adding it to a parent timeline (unconventional, but possible, and we wouldn't want it to get removed if the parent's autoRemoveChildren is true).
      t = _parentToChildTotalTime(timeline.rawTime(), child);

      if (!child._dur || _clamp(0, child.totalDuration(), t) - child._tTime > _tinyNum) {
        child.render(t, true);
      }
    } //if the timeline has already ended but the inserted tween/timeline extends the duration, we should enable this timeline again so that it renders properly. We should also align the playhead with the parent timeline's when appropriate.


    if (_uncache(timeline, child)._dp && timeline._initted && timeline._time >= timeline._dur && timeline._ts) {
      //in case any of the ancestors had completed but should now be enabled...
      if (timeline._dur < timeline.duration()) {
        t = timeline;

        while (t._dp) {
          t.rawTime() >= 0 && t.totalTime(t._tTime); //moves the timeline (shifts its startTime) if necessary, and also enables it. If it's currently zero, though, it may not be scheduled to render until later so there's no need to force it to align with the current playhead position. Only move to catch up with the playhead.

          t = t._dp;
        }
      }

      timeline._zTime = -_tinyNum; // helps ensure that the next render() will be forced (crossingStart = true in render()), even if the duration hasn't changed (we're adding a child which would need to get rendered). Definitely an edge case. Note: we MUST do this AFTER the loop above where the totalTime() might trigger a render() because this _addToTimeline() method gets called from the Animation constructor, BEFORE tweens even record their targets, etc. so we wouldn't want things to get triggered in the wrong order.
    }
  },
      _addToTimeline = function _addToTimeline(timeline, child, position, skipChecks) {
    child.parent && _removeFromParent(child);
    child._start = _roundPrecise((_isNumber(position) ? position : position || timeline !== _globalTimeline ? _parsePosition(timeline, position, child) : timeline._time) + child._delay);
    child._end = _roundPrecise(child._start + (child.totalDuration() / Math.abs(child.timeScale()) || 0));

    _addLinkedListItem(timeline, child, "_first", "_last", timeline._sort ? "_start" : 0);

    _isFromOrFromStart(child) || (timeline._recent = child);
    skipChecks || _postAddChecks(timeline, child);
    timeline._ts < 0 && _alignPlayhead(timeline, timeline._tTime); // if the timeline is reversed and the new child makes it longer, we may need to adjust the parent's _start (push it back)

    return timeline;
  },
      _scrollTrigger = function _scrollTrigger(animation, trigger) {
    return (_globals.ScrollTrigger || _missingPlugin("scrollTrigger", trigger)) && _globals.ScrollTrigger.create(trigger, animation);
  },
      _attemptInitTween = function _attemptInitTween(tween, time, force, suppressEvents, tTime) {
    _initTween(tween, time, tTime);

    if (!tween._initted) {
      return 1;
    }

    if (!force && tween._pt && !_reverting$1 && (tween._dur && tween.vars.lazy !== false || !tween._dur && tween.vars.lazy) && _lastRenderedFrame !== _ticker.frame) {
      _lazyTweens.push(tween);

      tween._lazy = [tTime, suppressEvents];
      return 1;
    }
  },
      _parentPlayheadIsBeforeStart = function _parentPlayheadIsBeforeStart(_ref) {
    var parent = _ref.parent;
    return parent && parent._ts && parent._initted && !parent._lock && (parent.rawTime() < 0 || _parentPlayheadIsBeforeStart(parent));
  },
      // check parent's _lock because when a timeline repeats/yoyos and does its artificial wrapping, we shouldn't force the ratio back to 0
  _isFromOrFromStart = function _isFromOrFromStart(_ref2) {
    var data = _ref2.data;
    return data === "isFromStart" || data === "isStart";
  },
      _renderZeroDurationTween = function _renderZeroDurationTween(tween, totalTime, suppressEvents, force) {
    var prevRatio = tween.ratio,
        ratio = totalTime < 0 || !totalTime && (!tween._start && _parentPlayheadIsBeforeStart(tween) && !(!tween._initted && _isFromOrFromStart(tween)) || (tween._ts < 0 || tween._dp._ts < 0) && !_isFromOrFromStart(tween)) ? 0 : 1,
        // if the tween or its parent is reversed and the totalTime is 0, we should go to a ratio of 0. Edge case: if a from() or fromTo() stagger tween is placed later in a timeline, the "startAt" zero-duration tween could initially render at a time when the parent timeline's playhead is technically BEFORE where this tween is, so make sure that any "from" and "fromTo" startAt tweens are rendered the first time at a ratio of 1.
    repeatDelay = tween._rDelay,
        tTime = 0,
        pt,
        iteration,
        prevIteration;

    if (repeatDelay && tween._repeat) {
      // in case there's a zero-duration tween that has a repeat with a repeatDelay
      tTime = _clamp(0, tween._tDur, totalTime);
      iteration = _animationCycle(tTime, repeatDelay);
      tween._yoyo && iteration & 1 && (ratio = 1 - ratio);

      if (iteration !== _animationCycle(tween._tTime, repeatDelay)) {
        // if iteration changed
        prevRatio = 1 - ratio;
        tween.vars.repeatRefresh && tween._initted && tween.invalidate();
      }
    }

    if (ratio !== prevRatio || _reverting$1 || force || tween._zTime === _tinyNum || !totalTime && tween._zTime) {
      if (!tween._initted && _attemptInitTween(tween, totalTime, force, suppressEvents, tTime)) {
        // if we render the very beginning (time == 0) of a fromTo(), we must force the render (normal tweens wouldn't need to render at a time of 0 when the prevTime was also 0). This is also mandatory to make sure overwriting kicks in immediately.
        return;
      }

      prevIteration = tween._zTime;
      tween._zTime = totalTime || (suppressEvents ? _tinyNum : 0); // when the playhead arrives at EXACTLY time 0 (right on top) of a zero-duration tween, we need to discern if events are suppressed so that when the playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callback would be triggered in this render. Basically, the callback should fire either when the playhead ARRIVES or LEAVES this exact spot, not both. Imagine doing a timeline.seek(0) and there's a callback that sits at 0. Since events are suppressed on that seek() by default, nothing will fire, but when the playhead moves off of that position, the callback should fire. This behavior is what people intuitively expect.

      suppressEvents || (suppressEvents = totalTime && !prevIteration); // if it was rendered previously at exactly 0 (_zTime) and now the playhead is moving away, DON'T fire callbacks otherwise they'll seem like duplicates.

      tween.ratio = ratio;
      tween._from && (ratio = 1 - ratio);
      tween._time = 0;
      tween._tTime = tTime;
      pt = tween._pt;

      while (pt) {
        pt.r(ratio, pt.d);
        pt = pt._next;
      }

      totalTime < 0 && _rewindStartAt(tween, totalTime, suppressEvents, true);
      tween._onUpdate && !suppressEvents && _callback(tween, "onUpdate");
      tTime && tween._repeat && !suppressEvents && tween.parent && _callback(tween, "onRepeat");

      if ((totalTime >= tween._tDur || totalTime < 0) && tween.ratio === ratio) {
        ratio && _removeFromParent(tween, 1);

        if (!suppressEvents && !_reverting$1) {
          _callback(tween, ratio ? "onComplete" : "onReverseComplete", true);

          tween._prom && tween._prom();
        }
      }
    } else if (!tween._zTime) {
      tween._zTime = totalTime;
    }
  },
      _findNextPauseTween = function _findNextPauseTween(animation, prevTime, time) {
    var child;

    if (time > prevTime) {
      child = animation._first;

      while (child && child._start <= time) {
        if (child.data === "isPause" && child._start > prevTime) {
          return child;
        }

        child = child._next;
      }
    } else {
      child = animation._last;

      while (child && child._start >= time) {
        if (child.data === "isPause" && child._start < prevTime) {
          return child;
        }

        child = child._prev;
      }
    }
  },
      _setDuration = function _setDuration(animation, duration, skipUncache, leavePlayhead) {
    var repeat = animation._repeat,
        dur = _roundPrecise(duration) || 0,
        totalProgress = animation._tTime / animation._tDur;
    totalProgress && !leavePlayhead && (animation._time *= dur / animation._dur);
    animation._dur = dur;
    animation._tDur = !repeat ? dur : repeat < 0 ? 1e10 : _roundPrecise(dur * (repeat + 1) + animation._rDelay * repeat);
    totalProgress > 0 && !leavePlayhead && _alignPlayhead(animation, animation._tTime = animation._tDur * totalProgress);
    animation.parent && _setEnd(animation);
    skipUncache || _uncache(animation.parent, animation);
    return animation;
  },
      _onUpdateTotalDuration = function _onUpdateTotalDuration(animation) {
    return animation instanceof Timeline ? _uncache(animation) : _setDuration(animation, animation._dur);
  },
      _zeroPosition = {
    _start: 0,
    endTime: _emptyFunc,
    totalDuration: _emptyFunc
  },
      _parsePosition = function _parsePosition(animation, position, percentAnimation) {
    var labels = animation.labels,
        recent = animation._recent || _zeroPosition,
        clippedDuration = animation.duration() >= _bigNum$1 ? recent.endTime(false) : animation._dur,
        //in case there's a child that infinitely repeats, users almost never intend for the insertion point of a new child to be based on a SUPER long value like that so we clip it and assume the most recently-added child's endTime should be used instead.
    i,
        offset,
        isPercent;

    if (_isString(position) && (isNaN(position) || position in labels)) {
      //if the string is a number like "1", check to see if there's a label with that name, otherwise interpret it as a number (absolute value).
      offset = position.charAt(0);
      isPercent = position.substr(-1) === "%";
      i = position.indexOf("=");

      if (offset === "<" || offset === ">") {
        i >= 0 && (position = position.replace(/=/, ""));
        return (offset === "<" ? recent._start : recent.endTime(recent._repeat >= 0)) + (parseFloat(position.substr(1)) || 0) * (isPercent ? (i < 0 ? recent : percentAnimation).totalDuration() / 100 : 1);
      }

      if (i < 0) {
        position in labels || (labels[position] = clippedDuration);
        return labels[position];
      }

      offset = parseFloat(position.charAt(i - 1) + position.substr(i + 1));

      if (isPercent && percentAnimation) {
        offset = offset / 100 * (_isArray(percentAnimation) ? percentAnimation[0] : percentAnimation).totalDuration();
      }

      return i > 1 ? _parsePosition(animation, position.substr(0, i - 1), percentAnimation) + offset : clippedDuration + offset;
    }

    return position == null ? clippedDuration : +position;
  },
      _createTweenType = function _createTweenType(type, params, timeline) {
    var isLegacy = _isNumber(params[1]),
        varsIndex = (isLegacy ? 2 : 1) + (type < 2 ? 0 : 1),
        vars = params[varsIndex],
        irVars,
        parent;

    isLegacy && (vars.duration = params[1]);
    vars.parent = timeline;

    if (type) {
      irVars = vars;
      parent = timeline;

      while (parent && !("immediateRender" in irVars)) {
        // inheritance hasn't happened yet, but someone may have set a default in an ancestor timeline. We could do vars.immediateRender = _isNotFalse(_inheritDefaults(vars).immediateRender) but that'd exact a slight performance penalty because _inheritDefaults() also runs in the Tween constructor. We're paying a small kb price here to gain speed.
        irVars = parent.vars.defaults || {};
        parent = _isNotFalse(parent.vars.inherit) && parent.parent;
      }

      vars.immediateRender = _isNotFalse(irVars.immediateRender);
      type < 2 ? vars.runBackwards = 1 : vars.startAt = params[varsIndex - 1]; // "from" vars
    }

    return new Tween(params[0], vars, params[varsIndex + 1]);
  },
      _conditionalReturn = function _conditionalReturn(value, func) {
    return value || value === 0 ? func(value) : func;
  },
      _clamp = function _clamp(min, max, value) {
    return value < min ? min : value > max ? max : value;
  },
      getUnit = function getUnit(value, v) {
    return !_isString(value) || !(v = _unitExp.exec(value)) ? "" : v[1];
  },
      // note: protect against padded numbers as strings, like "100.100". That shouldn't return "00" as the unit. If it's numeric, return no unit.
  clamp = function clamp(min, max, value) {
    return _conditionalReturn(value, function (v) {
      return _clamp(min, max, v);
    });
  },
      _slice = [].slice,
      _isArrayLike = function _isArrayLike(value, nonEmpty) {
    return value && _isObject(value) && "length" in value && (!nonEmpty && !value.length || value.length - 1 in value && _isObject(value[0])) && !value.nodeType && value !== _win$1;
  },
      _flatten = function _flatten(ar, leaveStrings, accumulator) {
    if (accumulator === void 0) {
      accumulator = [];
    }

    return ar.forEach(function (value) {
      var _accumulator;

      return _isString(value) && !leaveStrings || _isArrayLike(value, 1) ? (_accumulator = accumulator).push.apply(_accumulator, toArray(value)) : accumulator.push(value);
    }) || accumulator;
  },
      //takes any value and returns an array. If it's a string (and leaveStrings isn't true), it'll use document.querySelectorAll() and convert that to an array. It'll also accept iterables like jQuery objects.
  toArray = function toArray(value, scope, leaveStrings) {
    return _context && !scope && _context.selector ? _context.selector(value) : _isString(value) && !leaveStrings && (_coreInitted || !_wake()) ? _slice.call((scope || _doc$1).querySelectorAll(value), 0) : _isArray(value) ? _flatten(value, leaveStrings) : _isArrayLike(value) ? _slice.call(value, 0) : value ? [value] : [];
  },
      selector = function selector(value) {
    value = toArray(value)[0] || _warn("Invalid scope") || {};
    return function (v) {
      var el = value.current || value.nativeElement || value;
      return toArray(v, el.querySelectorAll ? el : el === value ? _warn("Invalid scope") || _doc$1.createElement("div") : value);
    };
  },
      shuffle = function shuffle(a) {
    return a.sort(function () {
      return .5 - Math.random();
    });
  },
      // alternative that's a bit faster and more reliably diverse but bigger:   for (let j, v, i = a.length; i; j = (Math.random() * i) | 0, v = a[--i], a[i] = a[j], a[j] = v); return a;
  //for distributing values across an array. Can accept a number, a function or (most commonly) a function which can contain the following properties: {base, amount, from, ease, grid, axis, length, each}. Returns a function that expects the following parameters: index, target, array. Recognizes the following
  distribute = function distribute(v) {
    if (_isFunction(v)) {
      return v;
    }

    var vars = _isObject(v) ? v : {
      each: v
    },
        //n:1 is just to indicate v was a number; we leverage that later to set v according to the length we get. If a number is passed in, we treat it like the old stagger value where 0.1, for example, would mean that things would be distributed with 0.1 between each element in the array rather than a total "amount" that's chunked out among them all.
    ease = _parseEase(vars.ease),
        from = vars.from || 0,
        base = parseFloat(vars.base) || 0,
        cache = {},
        isDecimal = from > 0 && from < 1,
        ratios = isNaN(from) || isDecimal,
        axis = vars.axis,
        ratioX = from,
        ratioY = from;

    if (_isString(from)) {
      ratioX = ratioY = {
        center: .5,
        edges: .5,
        end: 1
      }[from] || 0;
    } else if (!isDecimal && ratios) {
      ratioX = from[0];
      ratioY = from[1];
    }

    return function (i, target, a) {
      var l = (a || vars).length,
          distances = cache[l],
          originX,
          originY,
          x,
          y,
          d,
          j,
          max,
          min,
          wrapAt;

      if (!distances) {
        wrapAt = vars.grid === "auto" ? 0 : (vars.grid || [1, _bigNum$1])[1];

        if (!wrapAt) {
          max = -_bigNum$1;

          while (max < (max = a[wrapAt++].getBoundingClientRect().left) && wrapAt < l) {}

          wrapAt < l && wrapAt--;
        }

        distances = cache[l] = [];
        originX = ratios ? Math.min(wrapAt, l) * ratioX - .5 : from % wrapAt;
        originY = wrapAt === _bigNum$1 ? 0 : ratios ? l * ratioY / wrapAt - .5 : from / wrapAt | 0;
        max = 0;
        min = _bigNum$1;

        for (j = 0; j < l; j++) {
          x = j % wrapAt - originX;
          y = originY - (j / wrapAt | 0);
          distances[j] = d = !axis ? _sqrt(x * x + y * y) : Math.abs(axis === "y" ? y : x);
          d > max && (max = d);
          d < min && (min = d);
        }

        from === "random" && shuffle(distances);
        distances.max = max - min;
        distances.min = min;
        distances.v = l = (parseFloat(vars.amount) || parseFloat(vars.each) * (wrapAt > l ? l - 1 : !axis ? Math.max(wrapAt, l / wrapAt) : axis === "y" ? l / wrapAt : wrapAt) || 0) * (from === "edges" ? -1 : 1);
        distances.b = l < 0 ? base - l : base;
        distances.u = getUnit(vars.amount || vars.each) || 0; //unit

        ease = ease && l < 0 ? _invertEase(ease) : ease;
      }

      l = (distances[i] - distances.min) / distances.max || 0;
      return _roundPrecise(distances.b + (ease ? ease(l) : l) * distances.v) + distances.u; //round in order to work around floating point errors
    };
  },
      _roundModifier = function _roundModifier(v) {
    //pass in 0.1 get a function that'll round to the nearest tenth, or 5 to round to the closest 5, or 0.001 to the closest 1000th, etc.
    var p = Math.pow(10, ((v + "").split(".")[1] || "").length); //to avoid floating point math errors (like 24 * 0.1 == 2.4000000000000004), we chop off at a specific number of decimal places (much faster than toFixed())

    return function (raw) {
      var n = _roundPrecise(Math.round(parseFloat(raw) / v) * v * p);

      return (n - n % 1) / p + (_isNumber(raw) ? 0 : getUnit(raw)); // n - n % 1 replaces Math.floor() in order to handle negative values properly. For example, Math.floor(-150.00000000000003) is 151!
    };
  },
      snap = function snap(snapTo, value) {
    var isArray = _isArray(snapTo),
        radius,
        is2D;

    if (!isArray && _isObject(snapTo)) {
      radius = isArray = snapTo.radius || _bigNum$1;

      if (snapTo.values) {
        snapTo = toArray(snapTo.values);

        if (is2D = !_isNumber(snapTo[0])) {
          radius *= radius; //performance optimization so we don't have to Math.sqrt() in the loop.
        }
      } else {
        snapTo = _roundModifier(snapTo.increment);
      }
    }

    return _conditionalReturn(value, !isArray ? _roundModifier(snapTo) : _isFunction(snapTo) ? function (raw) {
      is2D = snapTo(raw);
      return Math.abs(is2D - raw) <= radius ? is2D : raw;
    } : function (raw) {
      var x = parseFloat(is2D ? raw.x : raw),
          y = parseFloat(is2D ? raw.y : 0),
          min = _bigNum$1,
          closest = 0,
          i = snapTo.length,
          dx,
          dy;

      while (i--) {
        if (is2D) {
          dx = snapTo[i].x - x;
          dy = snapTo[i].y - y;
          dx = dx * dx + dy * dy;
        } else {
          dx = Math.abs(snapTo[i] - x);
        }

        if (dx < min) {
          min = dx;
          closest = i;
        }
      }

      closest = !radius || min <= radius ? snapTo[closest] : raw;
      return is2D || closest === raw || _isNumber(raw) ? closest : closest + getUnit(raw);
    });
  },
      random = function random(min, max, roundingIncrement, returnFunction) {
    return _conditionalReturn(_isArray(min) ? !max : roundingIncrement === true ? !!(roundingIncrement = 0) : !returnFunction, function () {
      return _isArray(min) ? min[~~(Math.random() * min.length)] : (roundingIncrement = roundingIncrement || 1e-5) && (returnFunction = roundingIncrement < 1 ? Math.pow(10, (roundingIncrement + "").length - 2) : 1) && Math.floor(Math.round((min - roundingIncrement / 2 + Math.random() * (max - min + roundingIncrement * .99)) / roundingIncrement) * roundingIncrement * returnFunction) / returnFunction;
    });
  },
      pipe = function pipe() {
    for (var _len = arguments.length, functions = new Array(_len), _key = 0; _key < _len; _key++) {
      functions[_key] = arguments[_key];
    }

    return function (value) {
      return functions.reduce(function (v, f) {
        return f(v);
      }, value);
    };
  },
      unitize = function unitize(func, unit) {
    return function (value) {
      return func(parseFloat(value)) + (unit || getUnit(value));
    };
  },
      normalize = function normalize(min, max, value) {
    return mapRange(min, max, 0, 1, value);
  },
      _wrapArray = function _wrapArray(a, wrapper, value) {
    return _conditionalReturn(value, function (index) {
      return a[~~wrapper(index)];
    });
  },
      wrap = function wrap(min, max, value) {
    // NOTE: wrap() CANNOT be an arrow function! A very odd compiling bug causes problems (unrelated to GSAP).
    var range = max - min;
    return _isArray(min) ? _wrapArray(min, wrap(0, min.length), max) : _conditionalReturn(value, function (value) {
      return (range + (value - min) % range) % range + min;
    });
  },
      wrapYoyo = function wrapYoyo(min, max, value) {
    var range = max - min,
        total = range * 2;
    return _isArray(min) ? _wrapArray(min, wrapYoyo(0, min.length - 1), max) : _conditionalReturn(value, function (value) {
      value = (total + (value - min) % total) % total || 0;
      return min + (value > range ? total - value : value);
    });
  },
      _replaceRandom = function _replaceRandom(value) {
    //replaces all occurrences of random(...) in a string with the calculated random value. can be a range like random(-100, 100, 5) or an array like random([0, 100, 500])
    var prev = 0,
        s = "",
        i,
        nums,
        end,
        isArray;

    while (~(i = value.indexOf("random(", prev))) {
      end = value.indexOf(")", i);
      isArray = value.charAt(i + 7) === "[";
      nums = value.substr(i + 7, end - i - 7).match(isArray ? _delimitedValueExp : _strictNumExp);
      s += value.substr(prev, i - prev) + random(isArray ? nums : +nums[0], isArray ? 0 : +nums[1], +nums[2] || 1e-5);
      prev = end + 1;
    }

    return s + value.substr(prev, value.length - prev);
  },
      mapRange = function mapRange(inMin, inMax, outMin, outMax, value) {
    var inRange = inMax - inMin,
        outRange = outMax - outMin;
    return _conditionalReturn(value, function (value) {
      return outMin + ((value - inMin) / inRange * outRange || 0);
    });
  },
      interpolate = function interpolate(start, end, progress, mutate) {
    var func = isNaN(start + end) ? 0 : function (p) {
      return (1 - p) * start + p * end;
    };

    if (!func) {
      var isString = _isString(start),
          master = {},
          p,
          i,
          interpolators,
          l,
          il;

      progress === true && (mutate = 1) && (progress = null);

      if (isString) {
        start = {
          p: start
        };
        end = {
          p: end
        };
      } else if (_isArray(start) && !_isArray(end)) {
        interpolators = [];
        l = start.length;
        il = l - 2;

        for (i = 1; i < l; i++) {
          interpolators.push(interpolate(start[i - 1], start[i])); //build the interpolators up front as a performance optimization so that when the function is called many times, it can just reuse them.
        }

        l--;

        func = function func(p) {
          p *= l;
          var i = Math.min(il, ~~p);
          return interpolators[i](p - i);
        };

        progress = end;
      } else if (!mutate) {
        start = _merge(_isArray(start) ? [] : {}, start);
      }

      if (!interpolators) {
        for (p in end) {
          _addPropTween.call(master, start, p, "get", end[p]);
        }

        func = function func(p) {
          return _renderPropTweens(p, master) || (isString ? start.p : start);
        };
      }
    }

    return _conditionalReturn(progress, func);
  },
      _getLabelInDirection = function _getLabelInDirection(timeline, fromTime, backward) {
    //used for nextLabel() and previousLabel()
    var labels = timeline.labels,
        min = _bigNum$1,
        p,
        distance,
        label;

    for (p in labels) {
      distance = labels[p] - fromTime;

      if (distance < 0 === !!backward && distance && min > (distance = Math.abs(distance))) {
        label = p;
        min = distance;
      }
    }

    return label;
  },
      _callback = function _callback(animation, type, executeLazyFirst) {
    var v = animation.vars,
        callback = v[type],
        prevContext = _context,
        context = animation._ctx,
        params,
        scope,
        result;

    if (!callback) {
      return;
    }

    params = v[type + "Params"];
    scope = v.callbackScope || animation;
    executeLazyFirst && _lazyTweens.length && _lazyRender(); //in case rendering caused any tweens to lazy-init, we should render them because typically when a timeline finishes, users expect things to have rendered fully. Imagine an onUpdate on a timeline that reports/checks tweened values.

    context && (_context = context);
    result = params ? callback.apply(scope, params) : callback.call(scope);
    _context = prevContext;
    return result;
  },
      _interrupt = function _interrupt(animation) {
    _removeFromParent(animation);

    animation.scrollTrigger && animation.scrollTrigger.kill(!!_reverting$1);
    animation.progress() < 1 && _callback(animation, "onInterrupt");
    return animation;
  },
      _quickTween,
      _registerPluginQueue = [],
      _createPlugin = function _createPlugin(config) {
    if (!config) return;
    config = !config.name && config["default"] || config; // UMD packaging wraps things oddly, so for example MotionPathHelper becomes {MotionPathHelper:MotionPathHelper, default:MotionPathHelper}.

    if (_windowExists$1() || config.headless) {
      // edge case: some build tools may pass in a null/undefined value
      var name = config.name,
          isFunc = _isFunction(config),
          Plugin = name && !isFunc && config.init ? function () {
        this._props = [];
      } : config,
          //in case someone passes in an object that's not a plugin, like CustomEase
      instanceDefaults = {
        init: _emptyFunc,
        render: _renderPropTweens,
        add: _addPropTween,
        kill: _killPropTweensOf,
        modifier: _addPluginModifier,
        rawVars: 0
      },
          statics = {
        targetTest: 0,
        get: 0,
        getSetter: _getSetter,
        aliases: {},
        register: 0
      };

      _wake();

      if (config !== Plugin) {
        if (_plugins[name]) {
          return;
        }

        _setDefaults(Plugin, _setDefaults(_copyExcluding(config, instanceDefaults), statics)); //static methods


        _merge(Plugin.prototype, _merge(instanceDefaults, _copyExcluding(config, statics))); //instance methods


        _plugins[Plugin.prop = name] = Plugin;

        if (config.targetTest) {
          _harnessPlugins.push(Plugin);

          _reservedProps[name] = 1;
        }

        name = (name === "css" ? "CSS" : name.charAt(0).toUpperCase() + name.substr(1)) + "Plugin"; //for the global name. "motionPath" should become MotionPathPlugin
      }

      _addGlobal(name, Plugin);

      config.register && config.register(gsap, Plugin, PropTween);
    } else {
      _registerPluginQueue.push(config);
    }
  },

  /*
   * --------------------------------------------------------------------------------------
   * COLORS
   * --------------------------------------------------------------------------------------
   */
  _255 = 255,
      _colorLookup = {
    aqua: [0, _255, _255],
    lime: [0, _255, 0],
    silver: [192, 192, 192],
    black: [0, 0, 0],
    maroon: [128, 0, 0],
    teal: [0, 128, 128],
    blue: [0, 0, _255],
    navy: [0, 0, 128],
    white: [_255, _255, _255],
    olive: [128, 128, 0],
    yellow: [_255, _255, 0],
    orange: [_255, 165, 0],
    gray: [128, 128, 128],
    purple: [128, 0, 128],
    green: [0, 128, 0],
    red: [_255, 0, 0],
    pink: [_255, 192, 203],
    cyan: [0, _255, _255],
    transparent: [_255, _255, _255, 0]
  },
      // possible future idea to replace the hard-coded color name values - put this in the ticker.wake() where we set the _doc:
  // let ctx = _doc.createElement("canvas").getContext("2d");
  // _forEachName("aqua,lime,silver,black,maroon,teal,blue,navy,white,olive,yellow,orange,gray,purple,green,red,pink,cyan", color => {ctx.fillStyle = color; _colorLookup[color] = splitColor(ctx.fillStyle)});
  _hue = function _hue(h, m1, m2) {
    h += h < 0 ? 1 : h > 1 ? -1 : 0;
    return (h * 6 < 1 ? m1 + (m2 - m1) * h * 6 : h < .5 ? m2 : h * 3 < 2 ? m1 + (m2 - m1) * (2 / 3 - h) * 6 : m1) * _255 + .5 | 0;
  },
      splitColor = function splitColor(v, toHSL, forceAlpha) {
    var a = !v ? _colorLookup.black : _isNumber(v) ? [v >> 16, v >> 8 & _255, v & _255] : 0,
        r,
        g,
        b,
        h,
        s,
        l,
        max,
        min,
        d,
        wasHSL;

    if (!a) {
      if (v.substr(-1) === ",") {
        //sometimes a trailing comma is included and we should chop it off (typically from a comma-delimited list of values like a textShadow:"2px 2px 2px blue, 5px 5px 5px rgb(255,0,0)" - in this example "blue," has a trailing comma. We could strip it out inside parseComplex() but we'd need to do it to the beginning and ending values plus it wouldn't provide protection from other potential scenarios like if the user passes in a similar value.
        v = v.substr(0, v.length - 1);
      }

      if (_colorLookup[v]) {
        a = _colorLookup[v];
      } else if (v.charAt(0) === "#") {
        if (v.length < 6) {
          //for shorthand like #9F0 or #9F0F (could have alpha)
          r = v.charAt(1);
          g = v.charAt(2);
          b = v.charAt(3);
          v = "#" + r + r + g + g + b + b + (v.length === 5 ? v.charAt(4) + v.charAt(4) : "");
        }

        if (v.length === 9) {
          // hex with alpha, like #fd5e53ff
          a = parseInt(v.substr(1, 6), 16);
          return [a >> 16, a >> 8 & _255, a & _255, parseInt(v.substr(7), 16) / 255];
        }

        v = parseInt(v.substr(1), 16);
        a = [v >> 16, v >> 8 & _255, v & _255];
      } else if (v.substr(0, 3) === "hsl") {
        a = wasHSL = v.match(_strictNumExp);

        if (!toHSL) {
          h = +a[0] % 360 / 360;
          s = +a[1] / 100;
          l = +a[2] / 100;
          g = l <= .5 ? l * (s + 1) : l + s - l * s;
          r = l * 2 - g;
          a.length > 3 && (a[3] *= 1); //cast as number

          a[0] = _hue(h + 1 / 3, r, g);
          a[1] = _hue(h, r, g);
          a[2] = _hue(h - 1 / 3, r, g);
        } else if (~v.indexOf("=")) {
          //if relative values are found, just return the raw strings with the relative prefixes in place.
          a = v.match(_numExp);
          forceAlpha && a.length < 4 && (a[3] = 1);
          return a;
        }
      } else {
        a = v.match(_strictNumExp) || _colorLookup.transparent;
      }

      a = a.map(Number);
    }

    if (toHSL && !wasHSL) {
      r = a[0] / _255;
      g = a[1] / _255;
      b = a[2] / _255;
      max = Math.max(r, g, b);
      min = Math.min(r, g, b);
      l = (max + min) / 2;

      if (max === min) {
        h = s = 0;
      } else {
        d = max - min;
        s = l > 0.5 ? d / (2 - max - min) : d / (max + min);
        h = max === r ? (g - b) / d + (g < b ? 6 : 0) : max === g ? (b - r) / d + 2 : (r - g) / d + 4;
        h *= 60;
      }

      a[0] = ~~(h + .5);
      a[1] = ~~(s * 100 + .5);
      a[2] = ~~(l * 100 + .5);
    }

    forceAlpha && a.length < 4 && (a[3] = 1);
    return a;
  },
      _colorOrderData = function _colorOrderData(v) {
    // strips out the colors from the string, finds all the numeric slots (with units) and returns an array of those. The Array also has a "c" property which is an Array of the index values where the colors belong. This is to help work around issues where there's a mis-matched order of color/numeric data like drop-shadow(#f00 0px 1px 2px) and drop-shadow(0x 1px 2px #f00). This is basically a helper function used in _formatColors()
    var values = [],
        c = [],
        i = -1;
    v.split(_colorExp).forEach(function (v) {
      var a = v.match(_numWithUnitExp) || [];
      values.push.apply(values, a);
      c.push(i += a.length + 1);
    });
    values.c = c;
    return values;
  },
      _formatColors = function _formatColors(s, toHSL, orderMatchData) {
    var result = "",
        colors = (s + result).match(_colorExp),
        type = toHSL ? "hsla(" : "rgba(",
        i = 0,
        c,
        shell,
        d,
        l;

    if (!colors) {
      return s;
    }

    colors = colors.map(function (color) {
      return (color = splitColor(color, toHSL, 1)) && type + (toHSL ? color[0] + "," + color[1] + "%," + color[2] + "%," + color[3] : color.join(",")) + ")";
    });

    if (orderMatchData) {
      d = _colorOrderData(s);
      c = orderMatchData.c;

      if (c.join(result) !== d.c.join(result)) {
        shell = s.replace(_colorExp, "1").split(_numWithUnitExp);
        l = shell.length - 1;

        for (; i < l; i++) {
          result += shell[i] + (~c.indexOf(i) ? colors.shift() || type + "0,0,0,0)" : (d.length ? d : colors.length ? colors : orderMatchData).shift());
        }
      }
    }

    if (!shell) {
      shell = s.split(_colorExp);
      l = shell.length - 1;

      for (; i < l; i++) {
        result += shell[i] + colors[i];
      }
    }

    return result + shell[l];
  },
      _colorExp = function () {
    var s = "(?:\\b(?:(?:rgb|rgba|hsl|hsla)\\(.+?\\))|\\B#(?:[0-9a-f]{3,4}){1,2}\\b",
        //we'll dynamically build this Regular Expression to conserve file size. After building it, it will be able to find rgb(), rgba(), # (hexadecimal), and named color values like red, blue, purple, etc.,
    p;

    for (p in _colorLookup) {
      s += "|" + p + "\\b";
    }

    return new RegExp(s + ")", "gi");
  }(),
      _hslExp = /hsl[a]?\(/,
      _colorStringFilter = function _colorStringFilter(a) {
    var combined = a.join(" "),
        toHSL;
    _colorExp.lastIndex = 0;

    if (_colorExp.test(combined)) {
      toHSL = _hslExp.test(combined);
      a[1] = _formatColors(a[1], toHSL);
      a[0] = _formatColors(a[0], toHSL, _colorOrderData(a[1])); // make sure the order of numbers/colors match with the END value.

      return true;
    }
  },

  /*
   * --------------------------------------------------------------------------------------
   * TICKER
   * --------------------------------------------------------------------------------------
   */
  _tickerActive,
      _ticker = function () {
    var _getTime = Date.now,
        _lagThreshold = 500,
        _adjustedLag = 33,
        _startTime = _getTime(),
        _lastUpdate = _startTime,
        _gap = 1000 / 240,
        _nextTime = _gap,
        _listeners = [],
        _id,
        _req,
        _raf,
        _self,
        _delta,
        _i,
        _tick = function _tick(v) {
      var elapsed = _getTime() - _lastUpdate,
          manual = v === true,
          overlap,
          dispatch,
          time,
          frame;

      (elapsed > _lagThreshold || elapsed < 0) && (_startTime += elapsed - _adjustedLag);
      _lastUpdate += elapsed;
      time = _lastUpdate - _startTime;
      overlap = time - _nextTime;

      if (overlap > 0 || manual) {
        frame = ++_self.frame;
        _delta = time - _self.time * 1000;
        _self.time = time = time / 1000;
        _nextTime += overlap + (overlap >= _gap ? 4 : _gap - overlap);
        dispatch = 1;
      }

      manual || (_id = _req(_tick)); //make sure the request is made before we dispatch the "tick" event so that timing is maintained. Otherwise, if processing the "tick" requires a bunch of time (like 15ms) and we're using a setTimeout() that's based on 16.7ms, it'd technically take 31.7ms between frames otherwise.

      if (dispatch) {
        for (_i = 0; _i < _listeners.length; _i++) {
          // use _i and check _listeners.length instead of a variable because a listener could get removed during the loop, and if that happens to an element less than the current index, it'd throw things off in the loop.
          _listeners[_i](time, _delta, frame, v);
        }
      }
    };

    _self = {
      time: 0,
      frame: 0,
      tick: function tick() {
        _tick(true);
      },
      deltaRatio: function deltaRatio(fps) {
        return _delta / (1000 / (fps || 60));
      },
      wake: function wake() {
        if (_coreReady) {
          if (!_coreInitted && _windowExists$1()) {
            _win$1 = _coreInitted = window;
            _doc$1 = _win$1.document || {};
            _globals.gsap = gsap;
            (_win$1.gsapVersions || (_win$1.gsapVersions = [])).push(gsap.version);

            _install(_installScope || _win$1.GreenSockGlobals || !_win$1.gsap && _win$1 || {});

            _registerPluginQueue.forEach(_createPlugin);
          }

          _raf = typeof requestAnimationFrame !== "undefined" && requestAnimationFrame;
          _id && _self.sleep();

          _req = _raf || function (f) {
            return setTimeout(f, _nextTime - _self.time * 1000 + 1 | 0);
          };

          _tickerActive = 1;

          _tick(2);
        }
      },
      sleep: function sleep() {
        (_raf ? cancelAnimationFrame : clearTimeout)(_id);
        _tickerActive = 0;
        _req = _emptyFunc;
      },
      lagSmoothing: function lagSmoothing(threshold, adjustedLag) {
        _lagThreshold = threshold || Infinity; // zero should be interpreted as basically unlimited

        _adjustedLag = Math.min(adjustedLag || 33, _lagThreshold);
      },
      fps: function fps(_fps) {
        _gap = 1000 / (_fps || 240);
        _nextTime = _self.time * 1000 + _gap;
      },
      add: function add(callback, once, prioritize) {
        var func = once ? function (t, d, f, v) {
          callback(t, d, f, v);

          _self.remove(func);
        } : callback;

        _self.remove(callback);

        _listeners[prioritize ? "unshift" : "push"](func);

        _wake();

        return func;
      },
      remove: function remove(callback, i) {
        ~(i = _listeners.indexOf(callback)) && _listeners.splice(i, 1) && _i >= i && _i--;
      },
      _listeners: _listeners
    };
    return _self;
  }(),
      _wake = function _wake() {
    return !_tickerActive && _ticker.wake();
  },
      //also ensures the core classes are initialized.

  /*
  * -------------------------------------------------
  * EASING
  * -------------------------------------------------
  */
  _easeMap = {},
      _customEaseExp = /^[\d.\-M][\d.\-,\s]/,
      _quotesExp = /["']/g,
      _parseObjectInString = function _parseObjectInString(value) {
    //takes a string like "{wiggles:10, type:anticipate})" and turns it into a real object. Notice it ends in ")" and includes the {} wrappers. This is because we only use this function for parsing ease configs and prioritized optimization rather than reusability.
    var obj = {},
        split = value.substr(1, value.length - 3).split(":"),
        key = split[0],
        i = 1,
        l = split.length,
        index,
        val,
        parsedVal;

    for (; i < l; i++) {
      val = split[i];
      index = i !== l - 1 ? val.lastIndexOf(",") : val.length;
      parsedVal = val.substr(0, index);
      obj[key] = isNaN(parsedVal) ? parsedVal.replace(_quotesExp, "").trim() : +parsedVal;
      key = val.substr(index + 1).trim();
    }

    return obj;
  },
      _valueInParentheses = function _valueInParentheses(value) {
    var open = value.indexOf("(") + 1,
        close = value.indexOf(")"),
        nested = value.indexOf("(", open);
    return value.substring(open, ~nested && nested < close ? value.indexOf(")", close + 1) : close);
  },
      _configEaseFromString = function _configEaseFromString(name) {
    //name can be a string like "elastic.out(1,0.5)", and pass in _easeMap as obj and it'll parse it out and call the actual function like _easeMap.Elastic.easeOut.config(1,0.5). It will also parse custom ease strings as long as CustomEase is loaded and registered (internally as _easeMap._CE).
    var split = (name + "").split("("),
        ease = _easeMap[split[0]];
    return ease && split.length > 1 && ease.config ? ease.config.apply(null, ~name.indexOf("{") ? [_parseObjectInString(split[1])] : _valueInParentheses(name).split(",").map(_numericIfPossible)) : _easeMap._CE && _customEaseExp.test(name) ? _easeMap._CE("", name) : ease;
  },
      _invertEase = function _invertEase(ease) {
    return function (p) {
      return 1 - ease(1 - p);
    };
  },
      // allow yoyoEase to be set in children and have those affected when the parent/ancestor timeline yoyos.
  _propagateYoyoEase = function _propagateYoyoEase(timeline, isYoyo) {
    var child = timeline._first,
        ease;

    while (child) {
      if (child instanceof Timeline) {
        _propagateYoyoEase(child, isYoyo);
      } else if (child.vars.yoyoEase && (!child._yoyo || !child._repeat) && child._yoyo !== isYoyo) {
        if (child.timeline) {
          _propagateYoyoEase(child.timeline, isYoyo);
        } else {
          ease = child._ease;
          child._ease = child._yEase;
          child._yEase = ease;
          child._yoyo = isYoyo;
        }
      }

      child = child._next;
    }
  },
      _parseEase = function _parseEase(ease, defaultEase) {
    return !ease ? defaultEase : (_isFunction(ease) ? ease : _easeMap[ease] || _configEaseFromString(ease)) || defaultEase;
  },
      _insertEase = function _insertEase(names, easeIn, easeOut, easeInOut) {
    if (easeOut === void 0) {
      easeOut = function easeOut(p) {
        return 1 - easeIn(1 - p);
      };
    }

    if (easeInOut === void 0) {
      easeInOut = function easeInOut(p) {
        return p < .5 ? easeIn(p * 2) / 2 : 1 - easeIn((1 - p) * 2) / 2;
      };
    }

    var ease = {
      easeIn: easeIn,
      easeOut: easeOut,
      easeInOut: easeInOut
    },
        lowercaseName;

    _forEachName(names, function (name) {
      _easeMap[name] = _globals[name] = ease;
      _easeMap[lowercaseName = name.toLowerCase()] = easeOut;

      for (var p in ease) {
        _easeMap[lowercaseName + (p === "easeIn" ? ".in" : p === "easeOut" ? ".out" : ".inOut")] = _easeMap[name + "." + p] = ease[p];
      }
    });

    return ease;
  },
      _easeInOutFromOut = function _easeInOutFromOut(easeOut) {
    return function (p) {
      return p < .5 ? (1 - easeOut(1 - p * 2)) / 2 : .5 + easeOut((p - .5) * 2) / 2;
    };
  },
      _configElastic = function _configElastic(type, amplitude, period) {
    var p1 = amplitude >= 1 ? amplitude : 1,
        //note: if amplitude is < 1, we simply adjust the period for a more natural feel. Otherwise the math doesn't work right and the curve starts at 1.
    p2 = (period || (type ? .3 : .45)) / (amplitude < 1 ? amplitude : 1),
        p3 = p2 / _2PI * (Math.asin(1 / p1) || 0),
        easeOut = function easeOut(p) {
      return p === 1 ? 1 : p1 * Math.pow(2, -10 * p) * _sin((p - p3) * p2) + 1;
    },
        ease = type === "out" ? easeOut : type === "in" ? function (p) {
      return 1 - easeOut(1 - p);
    } : _easeInOutFromOut(easeOut);

    p2 = _2PI / p2; //precalculate to optimize

    ease.config = function (amplitude, period) {
      return _configElastic(type, amplitude, period);
    };

    return ease;
  },
      _configBack = function _configBack(type, overshoot) {
    if (overshoot === void 0) {
      overshoot = 1.70158;
    }

    var easeOut = function easeOut(p) {
      return p ? --p * p * ((overshoot + 1) * p + overshoot) + 1 : 0;
    },
        ease = type === "out" ? easeOut : type === "in" ? function (p) {
      return 1 - easeOut(1 - p);
    } : _easeInOutFromOut(easeOut);

    ease.config = function (overshoot) {
      return _configBack(type, overshoot);
    };

    return ease;
  }; // a cheaper (kb and cpu) but more mild way to get a parameterized weighted ease by feeding in a value between -1 (easeIn) and 1 (easeOut) where 0 is linear.
  // _weightedEase = ratio => {
  // 	let y = 0.5 + ratio / 2;
  // 	return p => (2 * (1 - p) * p * y + p * p);
  // },
  // a stronger (but more expensive kb/cpu) parameterized weighted ease that lets you feed in a value between -1 (easeIn) and 1 (easeOut) where 0 is linear.
  // _weightedEaseStrong = ratio => {
  // 	ratio = .5 + ratio / 2;
  // 	let o = 1 / 3 * (ratio < .5 ? ratio : 1 - ratio),
  // 		b = ratio - o,
  // 		c = ratio + o;
  // 	return p => p === 1 ? p : 3 * b * (1 - p) * (1 - p) * p + 3 * c * (1 - p) * p * p + p * p * p;
  // };


  _forEachName("Linear,Quad,Cubic,Quart,Quint,Strong", function (name, i) {
    var power = i < 5 ? i + 1 : i;

    _insertEase(name + ",Power" + (power - 1), i ? function (p) {
      return Math.pow(p, power);
    } : function (p) {
      return p;
    }, function (p) {
      return 1 - Math.pow(1 - p, power);
    }, function (p) {
      return p < .5 ? Math.pow(p * 2, power) / 2 : 1 - Math.pow((1 - p) * 2, power) / 2;
    });
  });

  _easeMap.Linear.easeNone = _easeMap.none = _easeMap.Linear.easeIn;

  _insertEase("Elastic", _configElastic("in"), _configElastic("out"), _configElastic());

  (function (n, c) {
    var n1 = 1 / c,
        n2 = 2 * n1,
        n3 = 2.5 * n1,
        easeOut = function easeOut(p) {
      return p < n1 ? n * p * p : p < n2 ? n * Math.pow(p - 1.5 / c, 2) + .75 : p < n3 ? n * (p -= 2.25 / c) * p + .9375 : n * Math.pow(p - 2.625 / c, 2) + .984375;
    };

    _insertEase("Bounce", function (p) {
      return 1 - easeOut(1 - p);
    }, easeOut);
  })(7.5625, 2.75);

  _insertEase("Expo", function (p) {
    return Math.pow(2, 10 * (p - 1)) * p + p * p * p * p * p * p * (1 - p);
  }); // previously 2 ** (10 * (p - 1)) but that doesn't end up with the value quite at the right spot so we do a blended ease to ensure it lands where it should perfectly.


  _insertEase("Circ", function (p) {
    return -(_sqrt(1 - p * p) - 1);
  });

  _insertEase("Sine", function (p) {
    return p === 1 ? 1 : -_cos(p * _HALF_PI) + 1;
  });

  _insertEase("Back", _configBack("in"), _configBack("out"), _configBack());

  _easeMap.SteppedEase = _easeMap.steps = _globals.SteppedEase = {
    config: function config(steps, immediateStart) {
      if (steps === void 0) {
        steps = 1;
      }

      var p1 = 1 / steps,
          p2 = steps + (immediateStart ? 0 : 1),
          p3 = immediateStart ? 1 : 0,
          max = 1 - _tinyNum;
      return function (p) {
        return ((p2 * _clamp(0, max, p) | 0) + p3) * p1;
      };
    }
  };
  _defaults.ease = _easeMap["quad.out"];

  _forEachName("onComplete,onUpdate,onStart,onRepeat,onReverseComplete,onInterrupt", function (name) {
    return _callbackNames += name + "," + name + "Params,";
  });
  /*
   * --------------------------------------------------------------------------------------
   * CACHE
   * --------------------------------------------------------------------------------------
   */


  var GSCache = function GSCache(target, harness) {
    this.id = _gsID++;
    target._gsap = this;
    this.target = target;
    this.harness = harness;
    this.get = harness ? harness.get : _getProperty;
    this.set = harness ? harness.getSetter : _getSetter;
  };
  /*
   * --------------------------------------------------------------------------------------
   * ANIMATION
   * --------------------------------------------------------------------------------------
   */

  var Animation = /*#__PURE__*/function () {
    function Animation(vars) {
      this.vars = vars;
      this._delay = +vars.delay || 0;

      if (this._repeat = vars.repeat === Infinity ? -2 : vars.repeat || 0) {
        // TODO: repeat: Infinity on a timeline's children must flag that timeline internally and affect its totalDuration, otherwise it'll stop in the negative direction when reaching the start.
        this._rDelay = vars.repeatDelay || 0;
        this._yoyo = !!vars.yoyo || !!vars.yoyoEase;
      }

      this._ts = 1;

      _setDuration(this, +vars.duration, 1, 1);

      this.data = vars.data;

      if (_context) {
        this._ctx = _context;

        _context.data.push(this);
      }

      _tickerActive || _ticker.wake();
    }

    var _proto = Animation.prototype;

    _proto.delay = function delay(value) {
      if (value || value === 0) {
        this.parent && this.parent.smoothChildTiming && this.startTime(this._start + value - this._delay);
        this._delay = value;
        return this;
      }

      return this._delay;
    };

    _proto.duration = function duration(value) {
      return arguments.length ? this.totalDuration(this._repeat > 0 ? value + (value + this._rDelay) * this._repeat : value) : this.totalDuration() && this._dur;
    };

    _proto.totalDuration = function totalDuration(value) {
      if (!arguments.length) {
        return this._tDur;
      }

      this._dirty = 0;
      return _setDuration(this, this._repeat < 0 ? value : (value - this._repeat * this._rDelay) / (this._repeat + 1));
    };

    _proto.totalTime = function totalTime(_totalTime, suppressEvents) {
      _wake();

      if (!arguments.length) {
        return this._tTime;
      }

      var parent = this._dp;

      if (parent && parent.smoothChildTiming && this._ts) {
        _alignPlayhead(this, _totalTime);

        !parent._dp || parent.parent || _postAddChecks(parent, this); // edge case: if this is a child of a timeline that already completed, for example, we must re-activate the parent.
        //in case any of the ancestor timelines had completed but should now be enabled, we should reset their totalTime() which will also ensure that they're lined up properly and enabled. Skip for animations that are on the root (wasteful). Example: a TimelineLite.exportRoot() is performed when there's a paused tween on the root, the export will not complete until that tween is unpaused, but imagine a child gets restarted later, after all [unpaused] tweens have completed. The start of that child would get pushed out, but one of the ancestors may have completed.

        while (parent && parent.parent) {
          if (parent.parent._time !== parent._start + (parent._ts >= 0 ? parent._tTime / parent._ts : (parent.totalDuration() - parent._tTime) / -parent._ts)) {
            parent.totalTime(parent._tTime, true);
          }

          parent = parent.parent;
        }

        if (!this.parent && this._dp.autoRemoveChildren && (this._ts > 0 && _totalTime < this._tDur || this._ts < 0 && _totalTime > 0 || !this._tDur && !_totalTime)) {
          //if the animation doesn't have a parent, put it back into its last parent (recorded as _dp for exactly cases like this). Limit to parents with autoRemoveChildren (like globalTimeline) so that if the user manually removes an animation from a timeline and then alters its playhead, it doesn't get added back in.
          _addToTimeline(this._dp, this, this._start - this._delay);
        }
      }

      if (this._tTime !== _totalTime || !this._dur && !suppressEvents || this._initted && Math.abs(this._zTime) === _tinyNum || !_totalTime && !this._initted && (this.add || this._ptLookup)) {
        // check for _ptLookup on a Tween instance to ensure it has actually finished being instantiated, otherwise if this.reverse() gets called in the Animation constructor, it could trigger a render() here even though the _targets weren't populated, thus when _init() is called there won't be any PropTweens (it'll act like the tween is non-functional)
        this._ts || (this._pTime = _totalTime); // otherwise, if an animation is paused, then the playhead is moved back to zero, then resumed, it'd revert back to the original time at the pause
        //if (!this._lock) { // avoid endless recursion (not sure we need this yet or if it's worth the performance hit)
        //   this._lock = 1;

        _lazySafeRender(this, _totalTime, suppressEvents); //   this._lock = 0;
        //}

      }

      return this;
    };

    _proto.time = function time(value, suppressEvents) {
      return arguments.length ? this.totalTime(Math.min(this.totalDuration(), value + _elapsedCycleDuration(this)) % (this._dur + this._rDelay) || (value ? this._dur : 0), suppressEvents) : this._time; // note: if the modulus results in 0, the playhead could be exactly at the end or the beginning, and we always defer to the END with a non-zero value, otherwise if you set the time() to the very end (duration()), it would render at the START!
    };

    _proto.totalProgress = function totalProgress(value, suppressEvents) {
      return arguments.length ? this.totalTime(this.totalDuration() * value, suppressEvents) : this.totalDuration() ? Math.min(1, this._tTime / this._tDur) : this.rawTime() >= 0 && this._initted ? 1 : 0;
    };

    _proto.progress = function progress(value, suppressEvents) {
      return arguments.length ? this.totalTime(this.duration() * (this._yoyo && !(this.iteration() & 1) ? 1 - value : value) + _elapsedCycleDuration(this), suppressEvents) : this.duration() ? Math.min(1, this._time / this._dur) : this.rawTime() > 0 ? 1 : 0;
    };

    _proto.iteration = function iteration(value, suppressEvents) {
      var cycleDuration = this.duration() + this._rDelay;

      return arguments.length ? this.totalTime(this._time + (value - 1) * cycleDuration, suppressEvents) : this._repeat ? _animationCycle(this._tTime, cycleDuration) + 1 : 1;
    } // potential future addition:
    // isPlayingBackwards() {
    // 	let animation = this,
    // 		orientation = 1; // 1 = forward, -1 = backward
    // 	while (animation) {
    // 		orientation *= animation.reversed() || (animation.repeat() && !(animation.iteration() & 1)) ? -1 : 1;
    // 		animation = animation.parent;
    // 	}
    // 	return orientation < 0;
    // }
    ;

    _proto.timeScale = function timeScale(value, suppressEvents) {
      if (!arguments.length) {
        return this._rts === -_tinyNum ? 0 : this._rts; // recorded timeScale. Special case: if someone calls reverse() on an animation with timeScale of 0, we assign it -_tinyNum to remember it's reversed.
      }

      if (this._rts === value) {
        return this;
      }

      var tTime = this.parent && this._ts ? _parentToChildTotalTime(this.parent._time, this) : this._tTime; // make sure to do the parentToChildTotalTime() BEFORE setting the new _ts because the old one must be used in that calculation.
      // future addition? Up side: fast and minimal file size. Down side: only works on this animation; if a timeline is reversed, for example, its childrens' onReverse wouldn't get called.
      //(+value < 0 && this._rts >= 0) && _callback(this, "onReverse", true);
      // prioritize rendering where the parent's playhead lines up instead of this._tTime because there could be a tween that's animating another tween's timeScale in the same rendering loop (same parent), thus if the timeScale tween renders first, it would alter _start BEFORE _tTime was set on that tick (in the rendering loop), effectively freezing it until the timeScale tween finishes.

      this._rts = +value || 0;
      this._ts = this._ps || value === -_tinyNum ? 0 : this._rts; // _ts is the functional timeScale which would be 0 if the animation is paused.

      this.totalTime(_clamp(-Math.abs(this._delay), this._tDur, tTime), suppressEvents !== false);

      _setEnd(this); // if parent.smoothChildTiming was false, the end time didn't get updated in the _alignPlayhead() method, so do it here.


      return _recacheAncestors(this);
    };

    _proto.paused = function paused(value) {
      if (!arguments.length) {
        return this._ps;
      } // possible future addition - if an animation is removed from its parent and then .restart() or .play() or .resume() is called, perhaps we should force it back into the globalTimeline but be careful because what if it's already at its end? We don't want it to just persist forever and not get released for GC.
      // !this.parent && !value && this._tTime < this._tDur && this !== _globalTimeline && _globalTimeline.add(this);


      if (this._ps !== value) {
        this._ps = value;

        if (value) {
          this._pTime = this._tTime || Math.max(-this._delay, this.rawTime()); // if the pause occurs during the delay phase, make sure that's factored in when resuming.

          this._ts = this._act = 0; // _ts is the functional timeScale, so a paused tween would effectively have a timeScale of 0. We record the "real" timeScale as _rts (recorded time scale)
        } else {
          _wake();

          this._ts = this._rts; //only defer to _pTime (pauseTime) if tTime is zero. Remember, someone could pause() an animation, then scrub the playhead and resume(). If the parent doesn't have smoothChildTiming, we render at the rawTime() because the startTime won't get updated.

          this.totalTime(this.parent && !this.parent.smoothChildTiming ? this.rawTime() : this._tTime || this._pTime, this.progress() === 1 && Math.abs(this._zTime) !== _tinyNum && (this._tTime -= _tinyNum)); // edge case: animation.progress(1).pause().play() wouldn't render again because the playhead is already at the end, but the call to totalTime() below will add it back to its parent...and not remove it again (since removing only happens upon rendering at a new time). Offsetting the _tTime slightly is done simply to cause the final render in totalTime() that'll pop it off its timeline (if autoRemoveChildren is true, of course). Check to make sure _zTime isn't -_tinyNum to avoid an edge case where the playhead is pushed to the end but INSIDE a tween/callback, the timeline itself is paused thus halting rendering and leaving a few unrendered. When resuming, it wouldn't render those otherwise.
        }
      }

      return this;
    };

    _proto.startTime = function startTime(value) {
      if (arguments.length) {
        this._start = value;
        var parent = this.parent || this._dp;
        parent && (parent._sort || !this.parent) && _addToTimeline(parent, this, value - this._delay);
        return this;
      }

      return this._start;
    };

    _proto.endTime = function endTime(includeRepeats) {
      return this._start + (_isNotFalse(includeRepeats) ? this.totalDuration() : this.duration()) / Math.abs(this._ts || 1);
    };

    _proto.rawTime = function rawTime(wrapRepeats) {
      var parent = this.parent || this._dp; // _dp = detached parent

      return !parent ? this._tTime : wrapRepeats && (!this._ts || this._repeat && this._time && this.totalProgress() < 1) ? this._tTime % (this._dur + this._rDelay) : !this._ts ? this._tTime : _parentToChildTotalTime(parent.rawTime(wrapRepeats), this);
    };

    _proto.revert = function revert(config) {
      if (config === void 0) {
        config = _revertConfig;
      }

      var prevIsReverting = _reverting$1;
      _reverting$1 = config;

      if (this._initted || this._startAt) {
        this.timeline && this.timeline.revert(config);
        this.totalTime(-0.01, config.suppressEvents);
      }

      this.data !== "nested" && config.kill !== false && this.kill();
      _reverting$1 = prevIsReverting;
      return this;
    };

    _proto.globalTime = function globalTime(rawTime) {
      var animation = this,
          time = arguments.length ? rawTime : animation.rawTime();

      while (animation) {
        time = animation._start + time / (Math.abs(animation._ts) || 1);
        animation = animation._dp;
      }

      return !this.parent && this._sat ? this._sat.globalTime(rawTime) : time; // the _startAt tweens for .fromTo() and .from() that have immediateRender should always be FIRST in the timeline (important for context.revert()). "_sat" stands for _startAtTween, referring to the parent tween that created the _startAt. We must discern if that tween had immediateRender so that we can know whether or not to prioritize it in revert().
    };

    _proto.repeat = function repeat(value) {
      if (arguments.length) {
        this._repeat = value === Infinity ? -2 : value;
        return _onUpdateTotalDuration(this);
      }

      return this._repeat === -2 ? Infinity : this._repeat;
    };

    _proto.repeatDelay = function repeatDelay(value) {
      if (arguments.length) {
        var time = this._time;
        this._rDelay = value;

        _onUpdateTotalDuration(this);

        return time ? this.time(time) : this;
      }

      return this._rDelay;
    };

    _proto.yoyo = function yoyo(value) {
      if (arguments.length) {
        this._yoyo = value;
        return this;
      }

      return this._yoyo;
    };

    _proto.seek = function seek(position, suppressEvents) {
      return this.totalTime(_parsePosition(this, position), _isNotFalse(suppressEvents));
    };

    _proto.restart = function restart(includeDelay, suppressEvents) {
      this.play().totalTime(includeDelay ? -this._delay : 0, _isNotFalse(suppressEvents));
      this._dur || (this._zTime = -_tinyNum); // ensures onComplete fires on a zero-duration animation that gets restarted.

      return this;
    };

    _proto.play = function play(from, suppressEvents) {
      from != null && this.seek(from, suppressEvents);
      return this.reversed(false).paused(false);
    };

    _proto.reverse = function reverse(from, suppressEvents) {
      from != null && this.seek(from || this.totalDuration(), suppressEvents);
      return this.reversed(true).paused(false);
    };

    _proto.pause = function pause(atTime, suppressEvents) {
      atTime != null && this.seek(atTime, suppressEvents);
      return this.paused(true);
    };

    _proto.resume = function resume() {
      return this.paused(false);
    };

    _proto.reversed = function reversed(value) {
      if (arguments.length) {
        !!value !== this.reversed() && this.timeScale(-this._rts || (value ? -_tinyNum : 0)); // in case timeScale is zero, reversing would have no effect so we use _tinyNum.

        return this;
      }

      return this._rts < 0;
    };

    _proto.invalidate = function invalidate() {
      this._initted = this._act = 0;
      this._zTime = -_tinyNum;
      return this;
    };

    _proto.isActive = function isActive() {
      var parent = this.parent || this._dp,
          start = this._start,
          rawTime;
      return !!(!parent || this._ts && this._initted && parent.isActive() && (rawTime = parent.rawTime(true)) >= start && rawTime < this.endTime(true) - _tinyNum);
    };

    _proto.eventCallback = function eventCallback(type, callback, params) {
      var vars = this.vars;

      if (arguments.length > 1) {
        if (!callback) {
          delete vars[type];
        } else {
          vars[type] = callback;
          params && (vars[type + "Params"] = params);
          type === "onUpdate" && (this._onUpdate = callback);
        }

        return this;
      }

      return vars[type];
    };

    _proto.then = function then(onFulfilled) {
      var self = this;
      return new Promise(function (resolve) {
        var f = _isFunction(onFulfilled) ? onFulfilled : _passThrough,
            _resolve = function _resolve() {
          var _then = self.then;
          self.then = null; // temporarily null the then() method to avoid an infinite loop (see https://github.com/greensock/GSAP/issues/322)

          _isFunction(f) && (f = f(self)) && (f.then || f === self) && (self.then = _then);
          resolve(f);
          self.then = _then;
        };

        if (self._initted && self.totalProgress() === 1 && self._ts >= 0 || !self._tTime && self._ts < 0) {
          _resolve();
        } else {
          self._prom = _resolve;
        }
      });
    };

    _proto.kill = function kill() {
      _interrupt(this);
    };

    return Animation;
  }();

  _setDefaults(Animation.prototype, {
    _time: 0,
    _start: 0,
    _end: 0,
    _tTime: 0,
    _tDur: 0,
    _dirty: 0,
    _repeat: 0,
    _yoyo: false,
    parent: null,
    _initted: false,
    _rDelay: 0,
    _ts: 1,
    _dp: 0,
    ratio: 0,
    _zTime: -_tinyNum,
    _prom: 0,
    _ps: false,
    _rts: 1
  });
  /*
   * -------------------------------------------------
   * TIMELINE
   * -------------------------------------------------
   */


  var Timeline = /*#__PURE__*/function (_Animation) {
    _inheritsLoose(Timeline, _Animation);

    function Timeline(vars, position) {
      var _this;

      if (vars === void 0) {
        vars = {};
      }

      _this = _Animation.call(this, vars) || this;
      _this.labels = {};
      _this.smoothChildTiming = !!vars.smoothChildTiming;
      _this.autoRemoveChildren = !!vars.autoRemoveChildren;
      _this._sort = _isNotFalse(vars.sortChildren);
      _globalTimeline && _addToTimeline(vars.parent || _globalTimeline, _assertThisInitialized(_this), position);
      vars.reversed && _this.reverse();
      vars.paused && _this.paused(true);
      vars.scrollTrigger && _scrollTrigger(_assertThisInitialized(_this), vars.scrollTrigger);
      return _this;
    }

    var _proto2 = Timeline.prototype;

    _proto2.to = function to(targets, vars, position) {
      _createTweenType(0, arguments, this);

      return this;
    };

    _proto2.from = function from(targets, vars, position) {
      _createTweenType(1, arguments, this);

      return this;
    };

    _proto2.fromTo = function fromTo(targets, fromVars, toVars, position) {
      _createTweenType(2, arguments, this);

      return this;
    };

    _proto2.set = function set(targets, vars, position) {
      vars.duration = 0;
      vars.parent = this;
      _inheritDefaults(vars).repeatDelay || (vars.repeat = 0);
      vars.immediateRender = !!vars.immediateRender;
      new Tween(targets, vars, _parsePosition(this, position), 1);
      return this;
    };

    _proto2.call = function call(callback, params, position) {
      return _addToTimeline(this, Tween.delayedCall(0, callback, params), position);
    } //ONLY for backward compatibility! Maybe delete?
    ;

    _proto2.staggerTo = function staggerTo(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams) {
      vars.duration = duration;
      vars.stagger = vars.stagger || stagger;
      vars.onComplete = onCompleteAll;
      vars.onCompleteParams = onCompleteAllParams;
      vars.parent = this;
      new Tween(targets, vars, _parsePosition(this, position));
      return this;
    };

    _proto2.staggerFrom = function staggerFrom(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams) {
      vars.runBackwards = 1;
      _inheritDefaults(vars).immediateRender = _isNotFalse(vars.immediateRender);
      return this.staggerTo(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams);
    };

    _proto2.staggerFromTo = function staggerFromTo(targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams) {
      toVars.startAt = fromVars;
      _inheritDefaults(toVars).immediateRender = _isNotFalse(toVars.immediateRender);
      return this.staggerTo(targets, duration, toVars, stagger, position, onCompleteAll, onCompleteAllParams);
    };

    _proto2.render = function render(totalTime, suppressEvents, force) {
      var prevTime = this._time,
          tDur = this._dirty ? this.totalDuration() : this._tDur,
          dur = this._dur,
          tTime = totalTime <= 0 ? 0 : _roundPrecise(totalTime),
          // if a paused timeline is resumed (or its _start is updated for another reason...which rounds it), that could result in the playhead shifting a **tiny** amount and a zero-duration child at that spot may get rendered at a different ratio, like its totalTime in render() may be 1e-17 instead of 0, for example.
      crossingStart = this._zTime < 0 !== totalTime < 0 && (this._initted || !dur),
          time,
          child,
          next,
          iteration,
          cycleDuration,
          prevPaused,
          pauseTween,
          timeScale,
          prevStart,
          prevIteration,
          yoyo,
          isYoyo;
      this !== _globalTimeline && tTime > tDur && totalTime >= 0 && (tTime = tDur);

      if (tTime !== this._tTime || force || crossingStart) {
        if (prevTime !== this._time && dur) {
          //if totalDuration() finds a child with a negative startTime and smoothChildTiming is true, things get shifted around internally so we need to adjust the time accordingly. For example, if a tween starts at -30 we must shift EVERYTHING forward 30 seconds and move this timeline's startTime backward by 30 seconds so that things align with the playhead (no jump).
          tTime += this._time - prevTime;
          totalTime += this._time - prevTime;
        }

        time = tTime;
        prevStart = this._start;
        timeScale = this._ts;
        prevPaused = !timeScale;

        if (crossingStart) {
          dur || (prevTime = this._zTime); //when the playhead arrives at EXACTLY time 0 (right on top) of a zero-duration timeline, we need to discern if events are suppressed so that when the playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callback would be triggered in this render. Basically, the callback should fire either when the playhead ARRIVES or LEAVES this exact spot, not both. Imagine doing a timeline.seek(0) and there's a callback that sits at 0. Since events are suppressed on that seek() by default, nothing will fire, but when the playhead moves off of that position, the callback should fire. This behavior is what people intuitively expect.

          (totalTime || !suppressEvents) && (this._zTime = totalTime);
        }

        if (this._repeat) {
          //adjust the time for repeats and yoyos
          yoyo = this._yoyo;
          cycleDuration = dur + this._rDelay;

          if (this._repeat < -1 && totalTime < 0) {
            return this.totalTime(cycleDuration * 100 + totalTime, suppressEvents, force);
          }

          time = _roundPrecise(tTime % cycleDuration); //round to avoid floating point errors. (4 % 0.8 should be 0 but some browsers report it as 0.79999999!)

          if (tTime === tDur) {
            // the tDur === tTime is for edge cases where there's a lengthy decimal on the duration and it may reach the very end but the time is rendered as not-quite-there (remember, tDur is rounded to 4 decimals whereas dur isn't)
            iteration = this._repeat;
            time = dur;
          } else {
            prevIteration = _roundPrecise(tTime / cycleDuration); // full decimal version of iterations, not the previous iteration (we're reusing prevIteration variable for efficiency)

            iteration = ~~prevIteration;

            if (iteration && iteration === prevIteration) {
              time = dur;
              iteration--;
            }

            time > dur && (time = dur);
          }

          prevIteration = _animationCycle(this._tTime, cycleDuration);
          !prevTime && this._tTime && prevIteration !== iteration && this._tTime - prevIteration * cycleDuration - this._dur <= 0 && (prevIteration = iteration); // edge case - if someone does addPause() at the very beginning of a repeating timeline, that pause is technically at the same spot as the end which causes this._time to get set to 0 when the totalTime would normally place the playhead at the end. See https://gsap.com/forums/topic/23823-closing-nav-animation-not-working-on-ie-and-iphone-6-maybe-other-older-browser/?tab=comments#comment-113005 also, this._tTime - prevIteration * cycleDuration - this._dur <= 0 just checks to make sure it wasn't previously in the "repeatDelay" portion

          if (yoyo && iteration & 1) {
            time = dur - time;
            isYoyo = 1;
          }
          /*
          make sure children at the end/beginning of the timeline are rendered properly. If, for example,
          a 3-second long timeline rendered at 2.9 seconds previously, and now renders at 3.2 seconds (which
          would get translated to 2.8 seconds if the timeline yoyos or 0.2 seconds if it just repeats), there
          could be a callback or a short tween that's at 2.95 or 3 seconds in which wouldn't render. So
          we need to push the timeline to the end (and/or beginning depending on its yoyo value). Also we must
          ensure that zero-duration tweens at the very beginning or end of the Timeline work.
          */


          if (iteration !== prevIteration && !this._lock) {
            var rewinding = yoyo && prevIteration & 1,
                doesWrap = rewinding === (yoyo && iteration & 1);
            iteration < prevIteration && (rewinding = !rewinding);
            prevTime = rewinding ? 0 : tTime % dur ? dur : tTime; // if the playhead is landing exactly at the end of an iteration, use that totalTime rather than only the duration, otherwise it'll skip the 2nd render since it's effectively at the same time.

            this._lock = 1;
            this.render(prevTime || (isYoyo ? 0 : _roundPrecise(iteration * cycleDuration)), suppressEvents, !dur)._lock = 0;
            this._tTime = tTime; // if a user gets the iteration() inside the onRepeat, for example, it should be accurate.

            !suppressEvents && this.parent && _callback(this, "onRepeat");
            this.vars.repeatRefresh && !isYoyo && (this.invalidate()._lock = 1);

            if (prevTime && prevTime !== this._time || prevPaused !== !this._ts || this.vars.onRepeat && !this.parent && !this._act) {
              // if prevTime is 0 and we render at the very end, _time will be the end, thus won't match. So in this edge case, prevTime won't match _time but that's okay. If it gets killed in the onRepeat, eject as well.
              return this;
            }

            dur = this._dur; // in case the duration changed in the onRepeat

            tDur = this._tDur;

            if (doesWrap) {
              this._lock = 2;
              prevTime = rewinding ? dur : -0.0001;
              this.render(prevTime, true);
              this.vars.repeatRefresh && !isYoyo && this.invalidate();
            }

            this._lock = 0;

            if (!this._ts && !prevPaused) {
              return this;
            } //in order for yoyoEase to work properly when there's a stagger, we must swap out the ease in each sub-tween.


            _propagateYoyoEase(this, isYoyo);
          }
        }

        if (this._hasPause && !this._forcing && this._lock < 2) {
          pauseTween = _findNextPauseTween(this, _roundPrecise(prevTime), _roundPrecise(time));

          if (pauseTween) {
            tTime -= time - (time = pauseTween._start);
          }
        }

        this._tTime = tTime;
        this._time = time;
        this._act = !timeScale; //as long as it's not paused, force it to be active so that if the user renders independent of the parent timeline, it'll be forced to re-render on the next tick.

        if (!this._initted) {
          this._onUpdate = this.vars.onUpdate;
          this._initted = 1;
          this._zTime = totalTime;
          prevTime = 0; // upon init, the playhead should always go forward; someone could invalidate() a completed timeline and then if they restart(), that would make child tweens render in reverse order which could lock in the wrong starting values if they build on each other, like tl.to(obj, {x: 100}).to(obj, {x: 0}).
        }

        if (!prevTime && time && !suppressEvents && !iteration) {
          _callback(this, "onStart");

          if (this._tTime !== tTime) {
            // in case the onStart triggered a render at a different spot, eject. Like if someone did animation.pause(0.5) or something inside the onStart.
            return this;
          }
        }

        if (time >= prevTime && totalTime >= 0) {
          child = this._first;

          while (child) {
            next = child._next;

            if ((child._act || time >= child._start) && child._ts && pauseTween !== child) {
              if (child.parent !== this) {
                // an extreme edge case - the child's render could do something like kill() the "next" one in the linked list, or reparent it. In that case we must re-initiate the whole render to be safe.
                return this.render(totalTime, suppressEvents, force);
              }

              child.render(child._ts > 0 ? (time - child._start) * child._ts : (child._dirty ? child.totalDuration() : child._tDur) + (time - child._start) * child._ts, suppressEvents, force);

              if (time !== this._time || !this._ts && !prevPaused) {
                //in case a tween pauses or seeks the timeline when rendering, like inside of an onUpdate/onComplete
                pauseTween = 0;
                next && (tTime += this._zTime = -_tinyNum); // it didn't finish rendering, so flag zTime as negative so that the next time render() is called it'll be forced (to render any remaining children)

                break;
              }
            }

            child = next;
          }
        } else {
          child = this._last;
          var adjustedTime = totalTime < 0 ? totalTime : time; //when the playhead goes backward beyond the start of this timeline, we must pass that information down to the child animations so that zero-duration tweens know whether to render their starting or ending values.

          while (child) {
            next = child._prev;

            if ((child._act || adjustedTime <= child._end) && child._ts && pauseTween !== child) {
              if (child.parent !== this) {
                // an extreme edge case - the child's render could do something like kill() the "next" one in the linked list, or reparent it. In that case we must re-initiate the whole render to be safe.
                return this.render(totalTime, suppressEvents, force);
              }

              child.render(child._ts > 0 ? (adjustedTime - child._start) * child._ts : (child._dirty ? child.totalDuration() : child._tDur) + (adjustedTime - child._start) * child._ts, suppressEvents, force || _reverting$1 && (child._initted || child._startAt)); // if reverting, we should always force renders of initted tweens (but remember that .fromTo() or .from() may have a _startAt but not _initted yet). If, for example, a .fromTo() tween with a stagger (which creates an internal timeline) gets reverted BEFORE some of its child tweens render for the first time, it may not properly trigger them to revert.

              if (time !== this._time || !this._ts && !prevPaused) {
                //in case a tween pauses or seeks the timeline when rendering, like inside of an onUpdate/onComplete
                pauseTween = 0;
                next && (tTime += this._zTime = adjustedTime ? -_tinyNum : _tinyNum); // it didn't finish rendering, so adjust zTime so that so that the next time render() is called it'll be forced (to render any remaining children)

                break;
              }
            }

            child = next;
          }
        }

        if (pauseTween && !suppressEvents) {
          this.pause();
          pauseTween.render(time >= prevTime ? 0 : -_tinyNum)._zTime = time >= prevTime ? 1 : -1;

          if (this._ts) {
            //the callback resumed playback! So since we may have held back the playhead due to where the pause is positioned, go ahead and jump to where it's SUPPOSED to be (if no pause happened).
            this._start = prevStart; //if the pause was at an earlier time and the user resumed in the callback, it could reposition the timeline (changing its startTime), throwing things off slightly, so we make sure the _start doesn't shift.

            _setEnd(this);

            return this.render(totalTime, suppressEvents, force);
          }
        }

        this._onUpdate && !suppressEvents && _callback(this, "onUpdate", true);
        if (tTime === tDur && this._tTime >= this.totalDuration() || !tTime && prevTime) if (prevStart === this._start || Math.abs(timeScale) !== Math.abs(this._ts)) if (!this._lock) {
          // remember, a child's callback may alter this timeline's playhead or timeScale which is why we need to add some of these checks.
          (totalTime || !dur) && (tTime === tDur && this._ts > 0 || !tTime && this._ts < 0) && _removeFromParent(this, 1); // don't remove if the timeline is reversed and the playhead isn't at 0, otherwise tl.progress(1).reverse() won't work. Only remove if the playhead is at the end and timeScale is positive, or if the playhead is at 0 and the timeScale is negative.

          if (!suppressEvents && !(totalTime < 0 && !prevTime) && (tTime || prevTime || !tDur)) {
            _callback(this, tTime === tDur && totalTime >= 0 ? "onComplete" : "onReverseComplete", true);

            this._prom && !(tTime < tDur && this.timeScale() > 0) && this._prom();
          }
        }
      }

      return this;
    };

    _proto2.add = function add(child, position) {
      var _this2 = this;

      _isNumber(position) || (position = _parsePosition(this, position, child));

      if (!(child instanceof Animation)) {
        if (_isArray(child)) {
          child.forEach(function (obj) {
            return _this2.add(obj, position);
          });
          return this;
        }

        if (_isString(child)) {
          return this.addLabel(child, position);
        }

        if (_isFunction(child)) {
          child = Tween.delayedCall(0, child);
        } else {
          return this;
        }
      }

      return this !== child ? _addToTimeline(this, child, position) : this; //don't allow a timeline to be added to itself as a child!
    };

    _proto2.getChildren = function getChildren(nested, tweens, timelines, ignoreBeforeTime) {
      if (nested === void 0) {
        nested = true;
      }

      if (tweens === void 0) {
        tweens = true;
      }

      if (timelines === void 0) {
        timelines = true;
      }

      if (ignoreBeforeTime === void 0) {
        ignoreBeforeTime = -_bigNum$1;
      }

      var a = [],
          child = this._first;

      while (child) {
        if (child._start >= ignoreBeforeTime) {
          if (child instanceof Tween) {
            tweens && a.push(child);
          } else {
            timelines && a.push(child);
            nested && a.push.apply(a, child.getChildren(true, tweens, timelines));
          }
        }

        child = child._next;
      }

      return a;
    };

    _proto2.getById = function getById(id) {
      var animations = this.getChildren(1, 1, 1),
          i = animations.length;

      while (i--) {
        if (animations[i].vars.id === id) {
          return animations[i];
        }
      }
    };

    _proto2.remove = function remove(child) {
      if (_isString(child)) {
        return this.removeLabel(child);
      }

      if (_isFunction(child)) {
        return this.killTweensOf(child);
      }

      child.parent === this && _removeLinkedListItem(this, child);

      if (child === this._recent) {
        this._recent = this._last;
      }

      return _uncache(this);
    };

    _proto2.totalTime = function totalTime(_totalTime2, suppressEvents) {
      if (!arguments.length) {
        return this._tTime;
      }

      this._forcing = 1;

      if (!this._dp && this._ts) {
        //special case for the global timeline (or any other that has no parent or detached parent).
        this._start = _roundPrecise(_ticker.time - (this._ts > 0 ? _totalTime2 / this._ts : (this.totalDuration() - _totalTime2) / -this._ts));
      }

      _Animation.prototype.totalTime.call(this, _totalTime2, suppressEvents);

      this._forcing = 0;
      return this;
    };

    _proto2.addLabel = function addLabel(label, position) {
      this.labels[label] = _parsePosition(this, position);
      return this;
    };

    _proto2.removeLabel = function removeLabel(label) {
      delete this.labels[label];
      return this;
    };

    _proto2.addPause = function addPause(position, callback, params) {
      var t = Tween.delayedCall(0, callback || _emptyFunc, params);
      t.data = "isPause";
      this._hasPause = 1;
      return _addToTimeline(this, t, _parsePosition(this, position));
    };

    _proto2.removePause = function removePause(position) {
      var child = this._first;
      position = _parsePosition(this, position);

      while (child) {
        if (child._start === position && child.data === "isPause") {
          _removeFromParent(child);
        }

        child = child._next;
      }
    };

    _proto2.killTweensOf = function killTweensOf(targets, props, onlyActive) {
      var tweens = this.getTweensOf(targets, onlyActive),
          i = tweens.length;

      while (i--) {
        _overwritingTween !== tweens[i] && tweens[i].kill(targets, props);
      }

      return this;
    };

    _proto2.getTweensOf = function getTweensOf(targets, onlyActive) {
      var a = [],
          parsedTargets = toArray(targets),
          child = this._first,
          isGlobalTime = _isNumber(onlyActive),
          // a number is interpreted as a global time. If the animation spans
      children;

      while (child) {
        if (child instanceof Tween) {
          if (_arrayContainsAny(child._targets, parsedTargets) && (isGlobalTime ? (!_overwritingTween || child._initted && child._ts) && child.globalTime(0) <= onlyActive && child.globalTime(child.totalDuration()) > onlyActive : !onlyActive || child.isActive())) {
            // note: if this is for overwriting, it should only be for tweens that aren't paused and are initted.
            a.push(child);
          }
        } else if ((children = child.getTweensOf(parsedTargets, onlyActive)).length) {
          a.push.apply(a, children);
        }

        child = child._next;
      }

      return a;
    } // potential future feature - targets() on timelines
    // targets() {
    // 	let result = [];
    // 	this.getChildren(true, true, false).forEach(t => result.push(...t.targets()));
    // 	return result.filter((v, i) => result.indexOf(v) === i);
    // }
    ;

    _proto2.tweenTo = function tweenTo(position, vars) {
      vars = vars || {};

      var tl = this,
          endTime = _parsePosition(tl, position),
          _vars = vars,
          startAt = _vars.startAt,
          _onStart = _vars.onStart,
          onStartParams = _vars.onStartParams,
          immediateRender = _vars.immediateRender,
          initted,
          tween = Tween.to(tl, _setDefaults({
        ease: vars.ease || "none",
        lazy: false,
        immediateRender: false,
        time: endTime,
        overwrite: "auto",
        duration: vars.duration || Math.abs((endTime - (startAt && "time" in startAt ? startAt.time : tl._time)) / tl.timeScale()) || _tinyNum,
        onStart: function onStart() {
          tl.pause();

          if (!initted) {
            var duration = vars.duration || Math.abs((endTime - (startAt && "time" in startAt ? startAt.time : tl._time)) / tl.timeScale());
            tween._dur !== duration && _setDuration(tween, duration, 0, 1).render(tween._time, true, true);
            initted = 1;
          }

          _onStart && _onStart.apply(tween, onStartParams || []); //in case the user had an onStart in the vars - we don't want to overwrite it.
        }
      }, vars));

      return immediateRender ? tween.render(0) : tween;
    };

    _proto2.tweenFromTo = function tweenFromTo(fromPosition, toPosition, vars) {
      return this.tweenTo(toPosition, _setDefaults({
        startAt: {
          time: _parsePosition(this, fromPosition)
        }
      }, vars));
    };

    _proto2.recent = function recent() {
      return this._recent;
    };

    _proto2.nextLabel = function nextLabel(afterTime) {
      if (afterTime === void 0) {
        afterTime = this._time;
      }

      return _getLabelInDirection(this, _parsePosition(this, afterTime));
    };

    _proto2.previousLabel = function previousLabel(beforeTime) {
      if (beforeTime === void 0) {
        beforeTime = this._time;
      }

      return _getLabelInDirection(this, _parsePosition(this, beforeTime), 1);
    };

    _proto2.currentLabel = function currentLabel(value) {
      return arguments.length ? this.seek(value, true) : this.previousLabel(this._time + _tinyNum);
    };

    _proto2.shiftChildren = function shiftChildren(amount, adjustLabels, ignoreBeforeTime) {
      if (ignoreBeforeTime === void 0) {
        ignoreBeforeTime = 0;
      }

      var child = this._first,
          labels = this.labels,
          p;

      while (child) {
        if (child._start >= ignoreBeforeTime) {
          child._start += amount;
          child._end += amount;
        }

        child = child._next;
      }

      if (adjustLabels) {
        for (p in labels) {
          if (labels[p] >= ignoreBeforeTime) {
            labels[p] += amount;
          }
        }
      }

      return _uncache(this);
    };

    _proto2.invalidate = function invalidate(soft) {
      var child = this._first;
      this._lock = 0;

      while (child) {
        child.invalidate(soft);
        child = child._next;
      }

      return _Animation.prototype.invalidate.call(this, soft);
    };

    _proto2.clear = function clear(includeLabels) {
      if (includeLabels === void 0) {
        includeLabels = true;
      }

      var child = this._first,
          next;

      while (child) {
        next = child._next;
        this.remove(child);
        child = next;
      }

      this._dp && (this._time = this._tTime = this._pTime = 0);
      includeLabels && (this.labels = {});
      return _uncache(this);
    };

    _proto2.totalDuration = function totalDuration(value) {
      var max = 0,
          self = this,
          child = self._last,
          prevStart = _bigNum$1,
          prev,
          start,
          parent;

      if (arguments.length) {
        return self.timeScale((self._repeat < 0 ? self.duration() : self.totalDuration()) / (self.reversed() ? -value : value));
      }

      if (self._dirty) {
        parent = self.parent;

        while (child) {
          prev = child._prev; //record it here in case the tween changes position in the sequence...

          child._dirty && child.totalDuration(); //could change the tween._startTime, so make sure the animation's cache is clean before analyzing it.

          start = child._start;

          if (start > prevStart && self._sort && child._ts && !self._lock) {
            //in case one of the tweens shifted out of order, it needs to be re-inserted into the correct position in the sequence
            self._lock = 1; //prevent endless recursive calls - there are methods that get triggered that check duration/totalDuration when we add().

            _addToTimeline(self, child, start - child._delay, 1)._lock = 0;
          } else {
            prevStart = start;
          }

          if (start < 0 && child._ts) {
            //children aren't allowed to have negative startTimes unless smoothChildTiming is true, so adjust here if one is found.
            max -= start;

            if (!parent && !self._dp || parent && parent.smoothChildTiming) {
              self._start += start / self._ts;
              self._time -= start;
              self._tTime -= start;
            }

            self.shiftChildren(-start, false, -1e999);
            prevStart = 0;
          }

          child._end > max && child._ts && (max = child._end);
          child = prev;
        }

        _setDuration(self, self === _globalTimeline && self._time > max ? self._time : max, 1, 1);

        self._dirty = 0;
      }

      return self._tDur;
    };

    Timeline.updateRoot = function updateRoot(time) {
      if (_globalTimeline._ts) {
        _lazySafeRender(_globalTimeline, _parentToChildTotalTime(time, _globalTimeline));

        _lastRenderedFrame = _ticker.frame;
      }

      if (_ticker.frame >= _nextGCFrame) {
        _nextGCFrame += _config.autoSleep || 120;
        var child = _globalTimeline._first;
        if (!child || !child._ts) if (_config.autoSleep && _ticker._listeners.length < 2) {
          while (child && !child._ts) {
            child = child._next;
          }

          child || _ticker.sleep();
        }
      }
    };

    return Timeline;
  }(Animation);

  _setDefaults(Timeline.prototype, {
    _lock: 0,
    _hasPause: 0,
    _forcing: 0
  });

  var _addComplexStringPropTween = function _addComplexStringPropTween(target, prop, start, end, setter, stringFilter, funcParam) {
    //note: we call _addComplexStringPropTween.call(tweenInstance...) to ensure that it's scoped properly. We may call it from within a plugin too, thus "this" would refer to the plugin.
    var pt = new PropTween(this._pt, target, prop, 0, 1, _renderComplexString, null, setter),
        index = 0,
        matchIndex = 0,
        result,
        startNums,
        color,
        endNum,
        chunk,
        startNum,
        hasRandom,
        a;
    pt.b = start;
    pt.e = end;
    start += ""; //ensure values are strings

    end += "";

    if (hasRandom = ~end.indexOf("random(")) {
      end = _replaceRandom(end);
    }

    if (stringFilter) {
      a = [start, end];
      stringFilter(a, target, prop); //pass an array with the starting and ending values and let the filter do whatever it needs to the values.

      start = a[0];
      end = a[1];
    }

    startNums = start.match(_complexStringNumExp) || [];

    while (result = _complexStringNumExp.exec(end)) {
      endNum = result[0];
      chunk = end.substring(index, result.index);

      if (color) {
        color = (color + 1) % 5;
      } else if (chunk.substr(-5) === "rgba(") {
        color = 1;
      }

      if (endNum !== startNums[matchIndex++]) {
        startNum = parseFloat(startNums[matchIndex - 1]) || 0; //these nested PropTweens are handled in a special way - we'll never actually call a render or setter method on them. We'll just loop through them in the parent complex string PropTween's render method.

        pt._pt = {
          _next: pt._pt,
          p: chunk || matchIndex === 1 ? chunk : ",",
          //note: SVG spec allows omission of comma/space when a negative sign is wedged between two numbers, like 2.5-5.3 instead of 2.5,-5.3 but when tweening, the negative value may switch to positive, so we insert the comma just in case.
          s: startNum,
          c: endNum.charAt(1) === "=" ? _parseRelative(startNum, endNum) - startNum : parseFloat(endNum) - startNum,
          m: color && color < 4 ? Math.round : 0
        };
        index = _complexStringNumExp.lastIndex;
      }
    }

    pt.c = index < end.length ? end.substring(index, end.length) : ""; //we use the "c" of the PropTween to store the final part of the string (after the last number)

    pt.fp = funcParam;

    if (_relExp.test(end) || hasRandom) {
      pt.e = 0; //if the end string contains relative values or dynamic random(...) values, delete the end it so that on the final render we don't actually set it to the string with += or -= characters (forces it to use the calculated value).
    }

    this._pt = pt; //start the linked list with this new PropTween. Remember, we call _addComplexStringPropTween.call(tweenInstance...) to ensure that it's scoped properly. We may call it from within a plugin too, thus "this" would refer to the plugin.

    return pt;
  },
      _addPropTween = function _addPropTween(target, prop, start, end, index, targets, modifier, stringFilter, funcParam, optional) {
    _isFunction(end) && (end = end(index || 0, target, targets));
    var currentValue = target[prop],
        parsedStart = start !== "get" ? start : !_isFunction(currentValue) ? currentValue : funcParam ? target[prop.indexOf("set") || !_isFunction(target["get" + prop.substr(3)]) ? prop : "get" + prop.substr(3)](funcParam) : target[prop](),
        setter = !_isFunction(currentValue) ? _setterPlain : funcParam ? _setterFuncWithParam : _setterFunc,
        pt;

    if (_isString(end)) {
      if (~end.indexOf("random(")) {
        end = _replaceRandom(end);
      }

      if (end.charAt(1) === "=") {
        pt = _parseRelative(parsedStart, end) + (getUnit(parsedStart) || 0);

        if (pt || pt === 0) {
          // to avoid isNaN, like if someone passes in a value like "!= whatever"
          end = pt;
        }
      }
    }

    if (!optional || parsedStart !== end || _forceAllPropTweens) {
      if (!isNaN(parsedStart * end) && end !== "") {
        // fun fact: any number multiplied by "" is evaluated as the number 0!
        pt = new PropTween(this._pt, target, prop, +parsedStart || 0, end - (parsedStart || 0), typeof currentValue === "boolean" ? _renderBoolean : _renderPlain, 0, setter);
        funcParam && (pt.fp = funcParam);
        modifier && pt.modifier(modifier, this, target);
        return this._pt = pt;
      }

      !currentValue && !(prop in target) && _missingPlugin(prop, end);
      return _addComplexStringPropTween.call(this, target, prop, parsedStart, end, setter, stringFilter || _config.stringFilter, funcParam);
    }
  },
      //creates a copy of the vars object and processes any function-based values (putting the resulting values directly into the copy) as well as strings with "random()" in them. It does NOT process relative values.
  _processVars = function _processVars(vars, index, target, targets, tween) {
    _isFunction(vars) && (vars = _parseFuncOrString(vars, tween, index, target, targets));

    if (!_isObject(vars) || vars.style && vars.nodeType || _isArray(vars) || _isTypedArray(vars)) {
      return _isString(vars) ? _parseFuncOrString(vars, tween, index, target, targets) : vars;
    }

    var copy = {},
        p;

    for (p in vars) {
      copy[p] = _parseFuncOrString(vars[p], tween, index, target, targets);
    }

    return copy;
  },
      _checkPlugin = function _checkPlugin(property, vars, tween, index, target, targets) {
    var plugin, pt, ptLookup, i;

    if (_plugins[property] && (plugin = new _plugins[property]()).init(target, plugin.rawVars ? vars[property] : _processVars(vars[property], index, target, targets, tween), tween, index, targets) !== false) {
      tween._pt = pt = new PropTween(tween._pt, target, property, 0, 1, plugin.render, plugin, 0, plugin.priority);

      if (tween !== _quickTween) {
        ptLookup = tween._ptLookup[tween._targets.indexOf(target)]; //note: we can't use tween._ptLookup[index] because for staggered tweens, the index from the fullTargets array won't match what it is in each individual tween that spawns from the stagger.

        i = plugin._props.length;

        while (i--) {
          ptLookup[plugin._props[i]] = pt;
        }
      }
    }

    return plugin;
  },
      _overwritingTween,
      //store a reference temporarily so we can avoid overwriting itself.
  _forceAllPropTweens,
      _initTween = function _initTween(tween, time, tTime) {
    var vars = tween.vars,
        ease = vars.ease,
        startAt = vars.startAt,
        immediateRender = vars.immediateRender,
        lazy = vars.lazy,
        onUpdate = vars.onUpdate,
        runBackwards = vars.runBackwards,
        yoyoEase = vars.yoyoEase,
        keyframes = vars.keyframes,
        autoRevert = vars.autoRevert,
        dur = tween._dur,
        prevStartAt = tween._startAt,
        targets = tween._targets,
        parent = tween.parent,
        fullTargets = parent && parent.data === "nested" ? parent.vars.targets : targets,
        autoOverwrite = tween._overwrite === "auto" && !_suppressOverwrites,
        tl = tween.timeline,
        cleanVars,
        i,
        p,
        pt,
        target,
        hasPriority,
        gsData,
        harness,
        plugin,
        ptLookup,
        index,
        harnessVars,
        overwritten;
    tl && (!keyframes || !ease) && (ease = "none");
    tween._ease = _parseEase(ease, _defaults.ease);
    tween._yEase = yoyoEase ? _invertEase(_parseEase(yoyoEase === true ? ease : yoyoEase, _defaults.ease)) : 0;

    if (yoyoEase && tween._yoyo && !tween._repeat) {
      //there must have been a parent timeline with yoyo:true that is currently in its yoyo phase, so flip the eases.
      yoyoEase = tween._yEase;
      tween._yEase = tween._ease;
      tween._ease = yoyoEase;
    }

    tween._from = !tl && !!vars.runBackwards; //nested timelines should never run backwards - the backwards-ness is in the child tweens.

    if (!tl || keyframes && !vars.stagger) {
      //if there's an internal timeline, skip all the parsing because we passed that task down the chain.
      harness = targets[0] ? _getCache(targets[0]).harness : 0;
      harnessVars = harness && vars[harness.prop]; //someone may need to specify CSS-specific values AND non-CSS values, like if the element has an "x" property plus it's a standard DOM element. We allow people to distinguish by wrapping plugin-specific stuff in a css:{} object for example.

      cleanVars = _copyExcluding(vars, _reservedProps);

      if (prevStartAt) {
        prevStartAt._zTime < 0 && prevStartAt.progress(1); // in case it's a lazy startAt that hasn't rendered yet.

        time < 0 && runBackwards && immediateRender && !autoRevert ? prevStartAt.render(-1, true) : prevStartAt.revert(runBackwards && dur ? _revertConfigNoKill : _startAtRevertConfig); // if it's a "startAt" (not "from()" or runBackwards: true), we only need to do a shallow revert (keep transforms cached in CSSPlugin)
        // don't just _removeFromParent(prevStartAt.render(-1, true)) because that'll leave inline styles. We're creating a new _startAt for "startAt" tweens that re-capture things to ensure that if the pre-tween values changed since the tween was created, they're recorded.

        prevStartAt._lazy = 0;
      }

      if (startAt) {
        _removeFromParent(tween._startAt = Tween.set(targets, _setDefaults({
          data: "isStart",
          overwrite: false,
          parent: parent,
          immediateRender: true,
          lazy: !prevStartAt && _isNotFalse(lazy),
          startAt: null,
          delay: 0,
          onUpdate: onUpdate && function () {
            return _callback(tween, "onUpdate");
          },
          stagger: 0
        }, startAt))); //copy the properties/values into a new object to avoid collisions, like var to = {x:0}, from = {x:500}; timeline.fromTo(e, from, to).fromTo(e, to, from);


        tween._startAt._dp = 0; // don't allow it to get put back into root timeline! Like when revert() is called and totalTime() gets set.

        tween._startAt._sat = tween; // used in globalTime(). _sat stands for _startAtTween

        time < 0 && (_reverting$1 || !immediateRender && !autoRevert) && tween._startAt.revert(_revertConfigNoKill); // rare edge case, like if a render is forced in the negative direction of a non-initted tween.

        if (immediateRender) {
          if (dur && time <= 0 && tTime <= 0) {
            // check tTime here because in the case of a yoyo tween whose playhead gets pushed to the end like tween.progress(1), we should allow it through so that the onComplete gets fired properly.
            time && (tween._zTime = time);
            return; //we skip initialization here so that overwriting doesn't occur until the tween actually begins. Otherwise, if you create several immediateRender:true tweens of the same target/properties to drop into a Timeline, the last one created would overwrite the first ones because they didn't get placed into the timeline yet before the first render occurs and kicks in overwriting.
          }
        }
      } else if (runBackwards && dur) {
        //from() tweens must be handled uniquely: their beginning values must be rendered but we don't want overwriting to occur yet (when time is still 0). Wait until the tween actually begins before doing all the routines like overwriting. At that time, we should render at the END of the tween to ensure that things initialize correctly (remember, from() tweens go backwards)
        if (!prevStartAt) {
          time && (immediateRender = false); //in rare cases (like if a from() tween runs and then is invalidate()-ed), immediateRender could be true but the initial forced-render gets skipped, so there's no need to force the render in this context when the _time is greater than 0

          p = _setDefaults({
            overwrite: false,
            data: "isFromStart",
            //we tag the tween with as "isFromStart" so that if [inside a plugin] we need to only do something at the very END of a tween, we have a way of identifying this tween as merely the one that's setting the beginning values for a "from()" tween. For example, clearProps in CSSPlugin should only get applied at the very END of a tween and without this tag, from(...{height:100, clearProps:"height", delay:1}) would wipe the height at the beginning of the tween and after 1 second, it'd kick back in.
            lazy: immediateRender && !prevStartAt && _isNotFalse(lazy),
            immediateRender: immediateRender,
            //zero-duration tweens render immediately by default, but if we're not specifically instructed to render this tween immediately, we should skip this and merely _init() to record the starting values (rendering them immediately would push them to completion which is wasteful in that case - we'd have to render(-1) immediately after)
            stagger: 0,
            parent: parent //ensures that nested tweens that had a stagger are handled properly, like gsap.from(".class", {y: gsap.utils.wrap([-100,100]), stagger: 0.5})

          }, cleanVars);
          harnessVars && (p[harness.prop] = harnessVars); // in case someone does something like .from(..., {css:{}})

          _removeFromParent(tween._startAt = Tween.set(targets, p));

          tween._startAt._dp = 0; // don't allow it to get put back into root timeline!

          tween._startAt._sat = tween; // used in globalTime()

          time < 0 && (_reverting$1 ? tween._startAt.revert(_revertConfigNoKill) : tween._startAt.render(-1, true));
          tween._zTime = time;

          if (!immediateRender) {
            _initTween(tween._startAt, _tinyNum, _tinyNum); //ensures that the initial values are recorded

          } else if (!time) {
            return;
          }
        }
      }

      tween._pt = tween._ptCache = 0;
      lazy = dur && _isNotFalse(lazy) || lazy && !dur;

      for (i = 0; i < targets.length; i++) {
        target = targets[i];
        gsData = target._gsap || _harness(targets)[i]._gsap;
        tween._ptLookup[i] = ptLookup = {};
        _lazyLookup[gsData.id] && _lazyTweens.length && _lazyRender(); //if other tweens of the same target have recently initted but haven't rendered yet, we've got to force the render so that the starting values are correct (imagine populating a timeline with a bunch of sequential tweens and then jumping to the end)

        index = fullTargets === targets ? i : fullTargets.indexOf(target);

        if (harness && (plugin = new harness()).init(target, harnessVars || cleanVars, tween, index, fullTargets) !== false) {
          tween._pt = pt = new PropTween(tween._pt, target, plugin.name, 0, 1, plugin.render, plugin, 0, plugin.priority);

          plugin._props.forEach(function (name) {
            ptLookup[name] = pt;
          });

          plugin.priority && (hasPriority = 1);
        }

        if (!harness || harnessVars) {
          for (p in cleanVars) {
            if (_plugins[p] && (plugin = _checkPlugin(p, cleanVars, tween, index, target, fullTargets))) {
              plugin.priority && (hasPriority = 1);
            } else {
              ptLookup[p] = pt = _addPropTween.call(tween, target, p, "get", cleanVars[p], index, fullTargets, 0, vars.stringFilter);
            }
          }
        }

        tween._op && tween._op[i] && tween.kill(target, tween._op[i]);

        if (autoOverwrite && tween._pt) {
          _overwritingTween = tween;

          _globalTimeline.killTweensOf(target, ptLookup, tween.globalTime(time)); // make sure the overwriting doesn't overwrite THIS tween!!!


          overwritten = !tween.parent;
          _overwritingTween = 0;
        }

        tween._pt && lazy && (_lazyLookup[gsData.id] = 1);
      }

      hasPriority && _sortPropTweensByPriority(tween);
      tween._onInit && tween._onInit(tween); //plugins like RoundProps must wait until ALL of the PropTweens are instantiated. In the plugin's init() function, it sets the _onInit on the tween instance. May not be pretty/intuitive, but it's fast and keeps file size down.
    }

    tween._onUpdate = onUpdate;
    tween._initted = (!tween._op || tween._pt) && !overwritten; // if overwrittenProps resulted in the entire tween being killed, do NOT flag it as initted or else it may render for one tick.

    keyframes && time <= 0 && tl.render(_bigNum$1, true, true); // if there's a 0% keyframe, it'll render in the "before" state for any staggered/delayed animations thus when the following tween initializes, it'll use the "before" state instead of the "after" state as the initial values.
  },
      _updatePropTweens = function _updatePropTweens(tween, property, value, start, startIsRelative, ratio, time, skipRecursion) {
    var ptCache = (tween._pt && tween._ptCache || (tween._ptCache = {}))[property],
        pt,
        rootPT,
        lookup,
        i;

    if (!ptCache) {
      ptCache = tween._ptCache[property] = [];
      lookup = tween._ptLookup;
      i = tween._targets.length;

      while (i--) {
        pt = lookup[i][property];

        if (pt && pt.d && pt.d._pt) {
          // it's a plugin, so find the nested PropTween
          pt = pt.d._pt;

          while (pt && pt.p !== property && pt.fp !== property) {
            // "fp" is functionParam for things like setting CSS variables which require .setProperty("--var-name", value)
            pt = pt._next;
          }
        }

        if (!pt) {
          // there is no PropTween associated with that property, so we must FORCE one to be created and ditch out of this
          // if the tween has other properties that already rendered at new positions, we'd normally have to rewind to put them back like tween.render(0, true) before forcing an _initTween(), but that can create another edge case like tweening a timeline's progress would trigger onUpdates to fire which could move other things around. It's better to just inform users that .resetTo() should ONLY be used for tweens that already have that property. For example, you can't gsap.to(...{ y: 0 }) and then tween.restTo("x", 200) for example.
          _forceAllPropTweens = 1; // otherwise, when we _addPropTween() and it finds no change between the start and end values, it skips creating a PropTween (for efficiency...why tween when there's no difference?) but in this case we NEED that PropTween created so we can edit it.

          tween.vars[property] = "+=0";

          _initTween(tween, time);

          _forceAllPropTweens = 0;
          return skipRecursion ? _warn(property + " not eligible for reset") : 1; // if someone tries to do a quickTo() on a special property like borderRadius which must get split into 4 different properties, that's not eligible for .resetTo().
        }

        ptCache.push(pt);
      }
    }

    i = ptCache.length;

    while (i--) {
      rootPT = ptCache[i];
      pt = rootPT._pt || rootPT; // complex values may have nested PropTweens. We only accommodate the FIRST value.

      pt.s = (start || start === 0) && !startIsRelative ? start : pt.s + (start || 0) + ratio * pt.c;
      pt.c = value - pt.s;
      rootPT.e && (rootPT.e = _round(value) + getUnit(rootPT.e)); // mainly for CSSPlugin (end value)

      rootPT.b && (rootPT.b = pt.s + getUnit(rootPT.b)); // (beginning value)
    }
  },
      _addAliasesToVars = function _addAliasesToVars(targets, vars) {
    var harness = targets[0] ? _getCache(targets[0]).harness : 0,
        propertyAliases = harness && harness.aliases,
        copy,
        p,
        i,
        aliases;

    if (!propertyAliases) {
      return vars;
    }

    copy = _merge({}, vars);

    for (p in propertyAliases) {
      if (p in copy) {
        aliases = propertyAliases[p].split(",");
        i = aliases.length;

        while (i--) {
          copy[aliases[i]] = copy[p];
        }
      }
    }

    return copy;
  },
      // parses multiple formats, like {"0%": {x: 100}, {"50%": {x: -20}} and { x: {"0%": 100, "50%": -20} }, and an "ease" can be set on any object. We populate an "allProps" object with an Array for each property, like {x: [{}, {}], y:[{}, {}]} with data for each property tween. The objects have a "t" (time), "v", (value), and "e" (ease) property. This allows us to piece together a timeline later.
  _parseKeyframe = function _parseKeyframe(prop, obj, allProps, easeEach) {
    var ease = obj.ease || easeEach || "power1.inOut",
        p,
        a;

    if (_isArray(obj)) {
      a = allProps[prop] || (allProps[prop] = []); // t = time (out of 100), v = value, e = ease

      obj.forEach(function (value, i) {
        return a.push({
          t: i / (obj.length - 1) * 100,
          v: value,
          e: ease
        });
      });
    } else {
      for (p in obj) {
        a = allProps[p] || (allProps[p] = []);
        p === "ease" || a.push({
          t: parseFloat(prop),
          v: obj[p],
          e: ease
        });
      }
    }
  },
      _parseFuncOrString = function _parseFuncOrString(value, tween, i, target, targets) {
    return _isFunction(value) ? value.call(tween, i, target, targets) : _isString(value) && ~value.indexOf("random(") ? _replaceRandom(value) : value;
  },
      _staggerTweenProps = _callbackNames + "repeat,repeatDelay,yoyo,repeatRefresh,yoyoEase,autoRevert",
      _staggerPropsToSkip = {};

  _forEachName(_staggerTweenProps + ",id,stagger,delay,duration,paused,scrollTrigger", function (name) {
    return _staggerPropsToSkip[name] = 1;
  });
  /*
   * --------------------------------------------------------------------------------------
   * TWEEN
   * --------------------------------------------------------------------------------------
   */


  var Tween = /*#__PURE__*/function (_Animation2) {
    _inheritsLoose(Tween, _Animation2);

    function Tween(targets, vars, position, skipInherit) {
      var _this3;

      if (typeof vars === "number") {
        position.duration = vars;
        vars = position;
        position = null;
      }

      _this3 = _Animation2.call(this, skipInherit ? vars : _inheritDefaults(vars)) || this;
      var _this3$vars = _this3.vars,
          duration = _this3$vars.duration,
          delay = _this3$vars.delay,
          immediateRender = _this3$vars.immediateRender,
          stagger = _this3$vars.stagger,
          overwrite = _this3$vars.overwrite,
          keyframes = _this3$vars.keyframes,
          defaults = _this3$vars.defaults,
          scrollTrigger = _this3$vars.scrollTrigger,
          yoyoEase = _this3$vars.yoyoEase,
          parent = vars.parent || _globalTimeline,
          parsedTargets = (_isArray(targets) || _isTypedArray(targets) ? _isNumber(targets[0]) : "length" in vars) ? [targets] : toArray(targets),
          tl,
          i,
          copy,
          l,
          p,
          curTarget,
          staggerFunc,
          staggerVarsToMerge;
      _this3._targets = parsedTargets.length ? _harness(parsedTargets) : _warn("GSAP target " + targets + " not found. https://gsap.com", !_config.nullTargetWarn) || [];
      _this3._ptLookup = []; //PropTween lookup. An array containing an object for each target, having keys for each tweening property

      _this3._overwrite = overwrite;

      if (keyframes || stagger || _isFuncOrString(duration) || _isFuncOrString(delay)) {
        vars = _this3.vars;
        tl = _this3.timeline = new Timeline({
          data: "nested",
          defaults: defaults || {},
          targets: parent && parent.data === "nested" ? parent.vars.targets : parsedTargets
        }); // we need to store the targets because for staggers and keyframes, we end up creating an individual tween for each but function-based values need to know the index and the whole Array of targets.

        tl.kill();
        tl.parent = tl._dp = _assertThisInitialized(_this3);
        tl._start = 0;

        if (stagger || _isFuncOrString(duration) || _isFuncOrString(delay)) {
          l = parsedTargets.length;
          staggerFunc = stagger && distribute(stagger);

          if (_isObject(stagger)) {
            //users can pass in callbacks like onStart/onComplete in the stagger object. These should fire with each individual tween.
            for (p in stagger) {
              if (~_staggerTweenProps.indexOf(p)) {
                staggerVarsToMerge || (staggerVarsToMerge = {});
                staggerVarsToMerge[p] = stagger[p];
              }
            }
          }

          for (i = 0; i < l; i++) {
            copy = _copyExcluding(vars, _staggerPropsToSkip);
            copy.stagger = 0;
            yoyoEase && (copy.yoyoEase = yoyoEase);
            staggerVarsToMerge && _merge(copy, staggerVarsToMerge);
            curTarget = parsedTargets[i]; //don't just copy duration or delay because if they're a string or function, we'd end up in an infinite loop because _isFuncOrString() would evaluate as true in the child tweens, entering this loop, etc. So we parse the value straight from vars and default to 0.

            copy.duration = +_parseFuncOrString(duration, _assertThisInitialized(_this3), i, curTarget, parsedTargets);
            copy.delay = (+_parseFuncOrString(delay, _assertThisInitialized(_this3), i, curTarget, parsedTargets) || 0) - _this3._delay;

            if (!stagger && l === 1 && copy.delay) {
              // if someone does delay:"random(1, 5)", repeat:-1, for example, the delay shouldn't be inside the repeat.
              _this3._delay = delay = copy.delay;
              _this3._start += delay;
              copy.delay = 0;
            }

            tl.to(curTarget, copy, staggerFunc ? staggerFunc(i, curTarget, parsedTargets) : 0);
            tl._ease = _easeMap.none;
          }

          tl.duration() ? duration = delay = 0 : _this3.timeline = 0; // if the timeline's duration is 0, we don't need a timeline internally!
        } else if (keyframes) {
          _inheritDefaults(_setDefaults(tl.vars.defaults, {
            ease: "none"
          }));

          tl._ease = _parseEase(keyframes.ease || vars.ease || "none");
          var time = 0,
              a,
              kf,
              v;

          if (_isArray(keyframes)) {
            keyframes.forEach(function (frame) {
              return tl.to(parsedTargets, frame, ">");
            });
            tl.duration(); // to ensure tl._dur is cached because we tap into it for performance purposes in the render() method.
          } else {
            copy = {};

            for (p in keyframes) {
              p === "ease" || p === "easeEach" || _parseKeyframe(p, keyframes[p], copy, keyframes.easeEach);
            }

            for (p in copy) {
              a = copy[p].sort(function (a, b) {
                return a.t - b.t;
              });
              time = 0;

              for (i = 0; i < a.length; i++) {
                kf = a[i];
                v = {
                  ease: kf.e,
                  duration: (kf.t - (i ? a[i - 1].t : 0)) / 100 * duration
                };
                v[p] = kf.v;
                tl.to(parsedTargets, v, time);
                time += v.duration;
              }
            }

            tl.duration() < duration && tl.to({}, {
              duration: duration - tl.duration()
            }); // in case keyframes didn't go to 100%
          }
        }

        duration || _this3.duration(duration = tl.duration());
      } else {
        _this3.timeline = 0; //speed optimization, faster lookups (no going up the prototype chain)
      }

      if (overwrite === true && !_suppressOverwrites) {
        _overwritingTween = _assertThisInitialized(_this3);

        _globalTimeline.killTweensOf(parsedTargets);

        _overwritingTween = 0;
      }

      _addToTimeline(parent, _assertThisInitialized(_this3), position);

      vars.reversed && _this3.reverse();
      vars.paused && _this3.paused(true);

      if (immediateRender || !duration && !keyframes && _this3._start === _roundPrecise(parent._time) && _isNotFalse(immediateRender) && _hasNoPausedAncestors(_assertThisInitialized(_this3)) && parent.data !== "nested") {
        _this3._tTime = -_tinyNum; //forces a render without having to set the render() "force" parameter to true because we want to allow lazying by default (using the "force" parameter always forces an immediate full render)

        _this3.render(Math.max(0, -delay) || 0); //in case delay is negative

      }

      scrollTrigger && _scrollTrigger(_assertThisInitialized(_this3), scrollTrigger);
      return _this3;
    }

    var _proto3 = Tween.prototype;

    _proto3.render = function render(totalTime, suppressEvents, force) {
      var prevTime = this._time,
          tDur = this._tDur,
          dur = this._dur,
          isNegative = totalTime < 0,
          tTime = totalTime > tDur - _tinyNum && !isNegative ? tDur : totalTime < _tinyNum ? 0 : totalTime,
          time,
          pt,
          iteration,
          cycleDuration,
          prevIteration,
          isYoyo,
          ratio,
          timeline,
          yoyoEase;

      if (!dur) {
        _renderZeroDurationTween(this, totalTime, suppressEvents, force);
      } else if (tTime !== this._tTime || !totalTime || force || !this._initted && this._tTime || this._startAt && this._zTime < 0 !== isNegative || this._lazy) {
        // this senses if we're crossing over the start time, in which case we must record _zTime and force the render, but we do it in this lengthy conditional way for performance reasons (usually we can skip the calculations): this._initted && (this._zTime < 0) !== (totalTime < 0)
        time = tTime;
        timeline = this.timeline;

        if (this._repeat) {
          //adjust the time for repeats and yoyos
          cycleDuration = dur + this._rDelay;

          if (this._repeat < -1 && isNegative) {
            return this.totalTime(cycleDuration * 100 + totalTime, suppressEvents, force);
          }

          time = _roundPrecise(tTime % cycleDuration); //round to avoid floating point errors. (4 % 0.8 should be 0 but some browsers report it as 0.79999999!)

          if (tTime === tDur) {
            // the tDur === tTime is for edge cases where there's a lengthy decimal on the duration and it may reach the very end but the time is rendered as not-quite-there (remember, tDur is rounded to 4 decimals whereas dur isn't)
            iteration = this._repeat;
            time = dur;
          } else {
            prevIteration = _roundPrecise(tTime / cycleDuration); // full decimal version of iterations, not the previous iteration (we're reusing prevIteration variable for efficiency)

            iteration = ~~prevIteration;

            if (iteration && iteration === prevIteration) {
              time = dur;
              iteration--;
            } else if (time > dur) {
              time = dur;
            }
          }

          isYoyo = this._yoyo && iteration & 1;

          if (isYoyo) {
            yoyoEase = this._yEase;
            time = dur - time;
          }

          prevIteration = _animationCycle(this._tTime, cycleDuration);

          if (time === prevTime && !force && this._initted && iteration === prevIteration) {
            //could be during the repeatDelay part. No need to render and fire callbacks.
            this._tTime = tTime;
            return this;
          }

          if (iteration !== prevIteration) {
            timeline && this._yEase && _propagateYoyoEase(timeline, isYoyo); //repeatRefresh functionality

            if (this.vars.repeatRefresh && !isYoyo && !this._lock && time !== cycleDuration && this._initted) {
              // this._time will === cycleDuration when we render at EXACTLY the end of an iteration. Without this condition, it'd often do the repeatRefresh render TWICE (again on the very next tick).
              this._lock = force = 1; //force, otherwise if lazy is true, the _attemptInitTween() will return and we'll jump out and get caught bouncing on each tick.

              this.render(_roundPrecise(cycleDuration * iteration), true).invalidate()._lock = 0;
            }
          }
        }

        if (!this._initted) {
          if (_attemptInitTween(this, isNegative ? totalTime : time, force, suppressEvents, tTime)) {
            this._tTime = 0; // in constructor if immediateRender is true, we set _tTime to -_tinyNum to have the playhead cross the starting point but we can't leave _tTime as a negative number.

            return this;
          }

          if (prevTime !== this._time && !(force && this.vars.repeatRefresh && iteration !== prevIteration)) {
            // rare edge case - during initialization, an onUpdate in the _startAt (.fromTo()) might force this tween to render at a different spot in which case we should ditch this render() call so that it doesn't revert the values. But we also don't want to dump if we're doing a repeatRefresh render!
            return this;
          }

          if (dur !== this._dur) {
            // while initting, a plugin like InertiaPlugin might alter the duration, so rerun from the start to ensure everything renders as it should.
            return this.render(totalTime, suppressEvents, force);
          }
        }

        this._tTime = tTime;
        this._time = time;

        if (!this._act && this._ts) {
          this._act = 1; //as long as it's not paused, force it to be active so that if the user renders independent of the parent timeline, it'll be forced to re-render on the next tick.

          this._lazy = 0;
        }

        this.ratio = ratio = (yoyoEase || this._ease)(time / dur);

        if (this._from) {
          this.ratio = ratio = 1 - ratio;
        }

        if (time && !prevTime && !suppressEvents && !iteration) {
          _callback(this, "onStart");

          if (this._tTime !== tTime) {
            // in case the onStart triggered a render at a different spot, eject. Like if someone did animation.pause(0.5) or something inside the onStart.
            return this;
          }
        }

        pt = this._pt;

        while (pt) {
          pt.r(ratio, pt.d);
          pt = pt._next;
        }

        timeline && timeline.render(totalTime < 0 ? totalTime : timeline._dur * timeline._ease(time / this._dur), suppressEvents, force) || this._startAt && (this._zTime = totalTime);

        if (this._onUpdate && !suppressEvents) {
          isNegative && _rewindStartAt(this, totalTime, suppressEvents, force); //note: for performance reasons, we tuck this conditional logic inside less traveled areas (most tweens don't have an onUpdate). We'd just have it at the end before the onComplete, but the values should be updated before any onUpdate is called, so we ALSO put it here and then if it's not called, we do so later near the onComplete.

          _callback(this, "onUpdate");
        }

        this._repeat && iteration !== prevIteration && this.vars.onRepeat && !suppressEvents && this.parent && _callback(this, "onRepeat");

        if ((tTime === this._tDur || !tTime) && this._tTime === tTime) {
          isNegative && !this._onUpdate && _rewindStartAt(this, totalTime, true, true);
          (totalTime || !dur) && (tTime === this._tDur && this._ts > 0 || !tTime && this._ts < 0) && _removeFromParent(this, 1); // don't remove if we're rendering at exactly a time of 0, as there could be autoRevert values that should get set on the next tick (if the playhead goes backward beyond the startTime, negative totalTime). Don't remove if the timeline is reversed and the playhead isn't at 0, otherwise tl.progress(1).reverse() won't work. Only remove if the playhead is at the end and timeScale is positive, or if the playhead is at 0 and the timeScale is negative.

          if (!suppressEvents && !(isNegative && !prevTime) && (tTime || prevTime || isYoyo)) {
            // if prevTime and tTime are zero, we shouldn't fire the onReverseComplete. This could happen if you gsap.to(... {paused:true}).play();
            _callback(this, tTime === tDur ? "onComplete" : "onReverseComplete", true);

            this._prom && !(tTime < tDur && this.timeScale() > 0) && this._prom();
          }
        }
      }

      return this;
    };

    _proto3.targets = function targets() {
      return this._targets;
    };

    _proto3.invalidate = function invalidate(soft) {
      // "soft" gives us a way to clear out everything EXCEPT the recorded pre-"from" portion of from() tweens. Otherwise, for example, if you tween.progress(1).render(0, true true).invalidate(), the "from" values would persist and then on the next render, the from() tweens would initialize and the current value would match the "from" values, thus animate from the same value to the same value (no animation). We tap into this in ScrollTrigger's refresh() where we must push a tween to completion and then back again but honor its init state in case the tween is dependent on another tween further up on the page.
      (!soft || !this.vars.runBackwards) && (this._startAt = 0);
      this._pt = this._op = this._onUpdate = this._lazy = this.ratio = 0;
      this._ptLookup = [];
      this.timeline && this.timeline.invalidate(soft);
      return _Animation2.prototype.invalidate.call(this, soft);
    };

    _proto3.resetTo = function resetTo(property, value, start, startIsRelative, skipRecursion) {
      _tickerActive || _ticker.wake();
      this._ts || this.play();
      var time = Math.min(this._dur, (this._dp._time - this._start) * this._ts),
          ratio;
      this._initted || _initTween(this, time);
      ratio = this._ease(time / this._dur); // don't just get tween.ratio because it may not have rendered yet.
      // possible future addition to allow an object with multiple values to update, like tween.resetTo({x: 100, y: 200}); At this point, it doesn't seem worth the added kb given the fact that most users will likely opt for the convenient gsap.quickTo() way of interacting with this method.
      // if (_isObject(property)) { // performance optimization
      // 	for (p in property) {
      // 		if (_updatePropTweens(this, p, property[p], value ? value[p] : null, start, ratio, time)) {
      // 			return this.resetTo(property, value, start, startIsRelative); // if a PropTween wasn't found for the property, it'll get forced with a re-initialization so we need to jump out and start over again.
      // 		}
      // 	}
      // } else {

      if (_updatePropTweens(this, property, value, start, startIsRelative, ratio, time, skipRecursion)) {
        return this.resetTo(property, value, start, startIsRelative, 1); // if a PropTween wasn't found for the property, it'll get forced with a re-initialization so we need to jump out and start over again.
      } //}


      _alignPlayhead(this, 0);

      this.parent || _addLinkedListItem(this._dp, this, "_first", "_last", this._dp._sort ? "_start" : 0);
      return this.render(0);
    };

    _proto3.kill = function kill(targets, vars) {
      if (vars === void 0) {
        vars = "all";
      }

      if (!targets && (!vars || vars === "all")) {
        this._lazy = this._pt = 0;
        this.parent ? _interrupt(this) : this.scrollTrigger && this.scrollTrigger.kill(!!_reverting$1);
        return this;
      }

      if (this.timeline) {
        var tDur = this.timeline.totalDuration();
        this.timeline.killTweensOf(targets, vars, _overwritingTween && _overwritingTween.vars.overwrite !== true)._first || _interrupt(this); // if nothing is left tweening, interrupt.

        this.parent && tDur !== this.timeline.totalDuration() && _setDuration(this, this._dur * this.timeline._tDur / tDur, 0, 1); // if a nested tween is killed that changes the duration, it should affect this tween's duration. We must use the ratio, though, because sometimes the internal timeline is stretched like for keyframes where they don't all add up to whatever the parent tween's duration was set to.

        return this;
      }

      var parsedTargets = this._targets,
          killingTargets = targets ? toArray(targets) : parsedTargets,
          propTweenLookup = this._ptLookup,
          firstPT = this._pt,
          overwrittenProps,
          curLookup,
          curOverwriteProps,
          props,
          p,
          pt,
          i;

      if ((!vars || vars === "all") && _arraysMatch(parsedTargets, killingTargets)) {
        vars === "all" && (this._pt = 0);
        return _interrupt(this);
      }

      overwrittenProps = this._op = this._op || [];

      if (vars !== "all") {
        //so people can pass in a comma-delimited list of property names
        if (_isString(vars)) {
          p = {};

          _forEachName(vars, function (name) {
            return p[name] = 1;
          });

          vars = p;
        }

        vars = _addAliasesToVars(parsedTargets, vars);
      }

      i = parsedTargets.length;

      while (i--) {
        if (~killingTargets.indexOf(parsedTargets[i])) {
          curLookup = propTweenLookup[i];

          if (vars === "all") {
            overwrittenProps[i] = vars;
            props = curLookup;
            curOverwriteProps = {};
          } else {
            curOverwriteProps = overwrittenProps[i] = overwrittenProps[i] || {};
            props = vars;
          }

          for (p in props) {
            pt = curLookup && curLookup[p];

            if (pt) {
              if (!("kill" in pt.d) || pt.d.kill(p) === true) {
                _removeLinkedListItem(this, pt, "_pt");
              }

              delete curLookup[p];
            }

            if (curOverwriteProps !== "all") {
              curOverwriteProps[p] = 1;
            }
          }
        }
      }

      this._initted && !this._pt && firstPT && _interrupt(this); //if all tweening properties are killed, kill the tween. Without this line, if there's a tween with multiple targets and then you killTweensOf() each target individually, the tween would technically still remain active and fire its onComplete even though there aren't any more properties tweening.

      return this;
    };

    Tween.to = function to(targets, vars) {
      return new Tween(targets, vars, arguments[2]);
    };

    Tween.from = function from(targets, vars) {
      return _createTweenType(1, arguments);
    };

    Tween.delayedCall = function delayedCall(delay, callback, params, scope) {
      return new Tween(callback, 0, {
        immediateRender: false,
        lazy: false,
        overwrite: false,
        delay: delay,
        onComplete: callback,
        onReverseComplete: callback,
        onCompleteParams: params,
        onReverseCompleteParams: params,
        callbackScope: scope
      }); // we must use onReverseComplete too for things like timeline.add(() => {...}) which should be triggered in BOTH directions (forward and reverse)
    };

    Tween.fromTo = function fromTo(targets, fromVars, toVars) {
      return _createTweenType(2, arguments);
    };

    Tween.set = function set(targets, vars) {
      vars.duration = 0;
      vars.repeatDelay || (vars.repeat = 0);
      return new Tween(targets, vars);
    };

    Tween.killTweensOf = function killTweensOf(targets, props, onlyActive) {
      return _globalTimeline.killTweensOf(targets, props, onlyActive);
    };

    return Tween;
  }(Animation);

  _setDefaults(Tween.prototype, {
    _targets: [],
    _lazy: 0,
    _startAt: 0,
    _op: 0,
    _onInit: 0
  }); //add the pertinent timeline methods to Tween instances so that users can chain conveniently and create a timeline automatically. (removed due to concerns that it'd ultimately add to more confusion especially for beginners)
  // _forEachName("to,from,fromTo,set,call,add,addLabel,addPause", name => {
  // 	Tween.prototype[name] = function() {
  // 		let tl = new Timeline();
  // 		return _addToTimeline(tl, this)[name].apply(tl, toArray(arguments));
  // 	}
  // });
  //for backward compatibility. Leverage the timeline calls.


  _forEachName("staggerTo,staggerFrom,staggerFromTo", function (name) {
    Tween[name] = function () {
      var tl = new Timeline(),
          params = _slice.call(arguments, 0);

      params.splice(name === "staggerFromTo" ? 5 : 4, 0, 0);
      return tl[name].apply(tl, params);
    };
  });
  /*
   * --------------------------------------------------------------------------------------
   * PROPTWEEN
   * --------------------------------------------------------------------------------------
   */


  var _setterPlain = function _setterPlain(target, property, value) {
    return target[property] = value;
  },
      _setterFunc = function _setterFunc(target, property, value) {
    return target[property](value);
  },
      _setterFuncWithParam = function _setterFuncWithParam(target, property, value, data) {
    return target[property](data.fp, value);
  },
      _setterAttribute = function _setterAttribute(target, property, value) {
    return target.setAttribute(property, value);
  },
      _getSetter = function _getSetter(target, property) {
    return _isFunction(target[property]) ? _setterFunc : _isUndefined(target[property]) && target.setAttribute ? _setterAttribute : _setterPlain;
  },
      _renderPlain = function _renderPlain(ratio, data) {
    return data.set(data.t, data.p, Math.round((data.s + data.c * ratio) * 1000000) / 1000000, data);
  },
      _renderBoolean = function _renderBoolean(ratio, data) {
    return data.set(data.t, data.p, !!(data.s + data.c * ratio), data);
  },
      _renderComplexString = function _renderComplexString(ratio, data) {
    var pt = data._pt,
        s = "";

    if (!ratio && data.b) {
      //b = beginning string
      s = data.b;
    } else if (ratio === 1 && data.e) {
      //e = ending string
      s = data.e;
    } else {
      while (pt) {
        s = pt.p + (pt.m ? pt.m(pt.s + pt.c * ratio) : Math.round((pt.s + pt.c * ratio) * 10000) / 10000) + s; //we use the "p" property for the text inbetween (like a suffix). And in the context of a complex string, the modifier (m) is typically just Math.round(), like for RGB colors.

        pt = pt._next;
      }

      s += data.c; //we use the "c" of the PropTween to store the final chunk of non-numeric text.
    }

    data.set(data.t, data.p, s, data);
  },
      _renderPropTweens = function _renderPropTweens(ratio, data) {
    var pt = data._pt;

    while (pt) {
      pt.r(ratio, pt.d);
      pt = pt._next;
    }
  },
      _addPluginModifier = function _addPluginModifier(modifier, tween, target, property) {
    var pt = this._pt,
        next;

    while (pt) {
      next = pt._next;
      pt.p === property && pt.modifier(modifier, tween, target);
      pt = next;
    }
  },
      _killPropTweensOf = function _killPropTweensOf(property) {
    var pt = this._pt,
        hasNonDependentRemaining,
        next;

    while (pt) {
      next = pt._next;

      if (pt.p === property && !pt.op || pt.op === property) {
        _removeLinkedListItem(this, pt, "_pt");
      } else if (!pt.dep) {
        hasNonDependentRemaining = 1;
      }

      pt = next;
    }

    return !hasNonDependentRemaining;
  },
      _setterWithModifier = function _setterWithModifier(target, property, value, data) {
    data.mSet(target, property, data.m.call(data.tween, value, data.mt), data);
  },
      _sortPropTweensByPriority = function _sortPropTweensByPriority(parent) {
    var pt = parent._pt,
        next,
        pt2,
        first,
        last; //sorts the PropTween linked list in order of priority because some plugins need to do their work after ALL of the PropTweens were created (like RoundPropsPlugin and ModifiersPlugin)

    while (pt) {
      next = pt._next;
      pt2 = first;

      while (pt2 && pt2.pr > pt.pr) {
        pt2 = pt2._next;
      }

      if (pt._prev = pt2 ? pt2._prev : last) {
        pt._prev._next = pt;
      } else {
        first = pt;
      }

      if (pt._next = pt2) {
        pt2._prev = pt;
      } else {
        last = pt;
      }

      pt = next;
    }

    parent._pt = first;
  }; //PropTween key: t = target, p = prop, r = renderer, d = data, s = start, c = change, op = overwriteProperty (ONLY populated when it's different than p), pr = priority, _next/_prev for the linked list siblings, set = setter, m = modifier, mSet = modifierSetter (the original setter, before a modifier was added)


  var PropTween = /*#__PURE__*/function () {
    function PropTween(next, target, prop, start, change, renderer, data, setter, priority) {
      this.t = target;
      this.s = start;
      this.c = change;
      this.p = prop;
      this.r = renderer || _renderPlain;
      this.d = data || this;
      this.set = setter || _setterPlain;
      this.pr = priority || 0;
      this._next = next;

      if (next) {
        next._prev = this;
      }
    }

    var _proto4 = PropTween.prototype;

    _proto4.modifier = function modifier(func, tween, target) {
      this.mSet = this.mSet || this.set; //in case it was already set (a PropTween can only have one modifier)

      this.set = _setterWithModifier;
      this.m = func;
      this.mt = target; //modifier target

      this.tween = tween;
    };

    return PropTween;
  }(); //Initialization tasks

  _forEachName(_callbackNames + "parent,duration,ease,delay,overwrite,runBackwards,startAt,yoyo,immediateRender,repeat,repeatDelay,data,paused,reversed,lazy,callbackScope,stringFilter,id,yoyoEase,stagger,inherit,repeatRefresh,keyframes,autoRevert,scrollTrigger", function (name) {
    return _reservedProps[name] = 1;
  });

  _globals.TweenMax = _globals.TweenLite = Tween;
  _globals.TimelineLite = _globals.TimelineMax = Timeline;
  _globalTimeline = new Timeline({
    sortChildren: false,
    defaults: _defaults,
    autoRemoveChildren: true,
    id: "root",
    smoothChildTiming: true
  });
  _config.stringFilter = _colorStringFilter;

  var _media = [],
      _listeners = {},
      _emptyArray = [],
      _lastMediaTime = 0,
      _contextID = 0,
      _dispatch = function _dispatch(type) {
    return (_listeners[type] || _emptyArray).map(function (f) {
      return f();
    });
  },
      _onMediaChange = function _onMediaChange() {
    var time = Date.now(),
        matches = [];

    if (time - _lastMediaTime > 2) {
      _dispatch("matchMediaInit");

      _media.forEach(function (c) {
        var queries = c.queries,
            conditions = c.conditions,
            match,
            p,
            anyMatch,
            toggled;

        for (p in queries) {
          match = _win$1.matchMedia(queries[p]).matches; // Firefox doesn't update the "matches" property of the MediaQueryList object correctly - it only does so as it calls its change handler - so we must re-create a media query here to ensure it's accurate.

          match && (anyMatch = 1);

          if (match !== conditions[p]) {
            conditions[p] = match;
            toggled = 1;
          }
        }

        if (toggled) {
          c.revert();
          anyMatch && matches.push(c);
        }
      });

      _dispatch("matchMediaRevert");

      matches.forEach(function (c) {
        return c.onMatch(c, function (func) {
          return c.add(null, func);
        });
      });
      _lastMediaTime = time;

      _dispatch("matchMedia");
    }
  };

  var Context = /*#__PURE__*/function () {
    function Context(func, scope) {
      this.selector = scope && selector(scope);
      this.data = [];
      this._r = []; // returned/cleanup functions

      this.isReverted = false;
      this.id = _contextID++; // to work around issues that frameworks like Vue cause by making things into Proxies which make it impossible to do something like _media.indexOf(this) because "this" would no longer refer to the Context instance itself - it'd refer to a Proxy! We needed a way to identify the context uniquely

      func && this.add(func);
    }

    var _proto5 = Context.prototype;

    _proto5.add = function add(name, func, scope) {
      // possible future addition if we need the ability to add() an animation to a context and for whatever reason cannot create that animation inside of a context.add(() => {...}) function.
      // if (name && _isFunction(name.revert)) {
      // 	this.data.push(name);
      // 	return (name._ctx = this);
      // }
      if (_isFunction(name)) {
        scope = func;
        func = name;
        name = _isFunction;
      }

      var self = this,
          f = function f() {
        var prev = _context,
            prevSelector = self.selector,
            result;
        prev && prev !== self && prev.data.push(self);
        scope && (self.selector = selector(scope));
        _context = self;
        result = func.apply(self, arguments);
        _isFunction(result) && self._r.push(result);
        _context = prev;
        self.selector = prevSelector;
        self.isReverted = false;
        return result;
      };

      self.last = f;
      return name === _isFunction ? f(self, function (func) {
        return self.add(null, func);
      }) : name ? self[name] = f : f;
    };

    _proto5.ignore = function ignore(func) {
      var prev = _context;
      _context = null;
      func(this);
      _context = prev;
    };

    _proto5.getTweens = function getTweens() {
      var a = [];
      this.data.forEach(function (e) {
        return e instanceof Context ? a.push.apply(a, e.getTweens()) : e instanceof Tween && !(e.parent && e.parent.data === "nested") && a.push(e);
      });
      return a;
    };

    _proto5.clear = function clear() {
      this._r.length = this.data.length = 0;
    };

    _proto5.kill = function kill(revert, matchMedia) {
      var _this4 = this;

      if (revert) {
        (function () {
          var tweens = _this4.getTweens(),
              i = _this4.data.length,
              t;

          while (i--) {
            // Flip plugin tweens are very different in that they should actually be pushed to their end. The plugin replaces the timeline's .revert() method to do exactly that. But we also need to remove any of those nested tweens inside the flip timeline so that they don't get individually reverted.
            t = _this4.data[i];

            if (t.data === "isFlip") {
              t.revert();
              t.getChildren(true, true, false).forEach(function (tween) {
                return tweens.splice(tweens.indexOf(tween), 1);
              });
            }
          } // save as an object so that we can cache the globalTime for each tween to optimize performance during the sort


          tweens.map(function (t) {
            return {
              g: t._dur || t._delay || t._sat && !t._sat.vars.immediateRender ? t.globalTime(0) : -Infinity,
              t: t
            };
          }).sort(function (a, b) {
            return b.g - a.g || -Infinity;
          }).forEach(function (o) {
            return o.t.revert(revert);
          }); // note: all of the _startAt tweens should be reverted in reverse order that they were created, and they'll all have the same globalTime (-1) so the " || -1" in the sort keeps the order properly.

          i = _this4.data.length;

          while (i--) {
            // make sure we loop backwards so that, for example, SplitTexts that were created later on the same element get reverted first
            t = _this4.data[i];

            if (t instanceof Timeline) {
              if (t.data !== "nested") {
                t.scrollTrigger && t.scrollTrigger.revert();
                t.kill(); // don't revert() the timeline because that's duplicating efforts since we already reverted all the tweens
              }
            } else {
              !(t instanceof Tween) && t.revert && t.revert(revert);
            }
          }

          _this4._r.forEach(function (f) {
            return f(revert, _this4);
          });

          _this4.isReverted = true;
        })();
      } else {
        this.data.forEach(function (e) {
          return e.kill && e.kill();
        });
      }

      this.clear();

      if (matchMedia) {
        var i = _media.length;

        while (i--) {
          // previously, we checked _media.indexOf(this), but some frameworks like Vue enforce Proxy objects that make it impossible to get the proper result that way, so we must use a unique ID number instead.
          _media[i].id === this.id && _media.splice(i, 1);
        }
      }
    } // killWithCleanup() {
    // 	this.kill();
    // 	this._r.forEach(f => f(false, this));
    // }
    ;

    _proto5.revert = function revert(config) {
      this.kill(config || {});
    };

    return Context;
  }();

  var MatchMedia = /*#__PURE__*/function () {
    function MatchMedia(scope) {
      this.contexts = [];
      this.scope = scope;
      _context && _context.data.push(this);
    }

    var _proto6 = MatchMedia.prototype;

    _proto6.add = function add(conditions, func, scope) {
      _isObject(conditions) || (conditions = {
        matches: conditions
      });
      var context = new Context(0, scope || this.scope),
          cond = context.conditions = {},
          mq,
          p,
          active;
      _context && !context.selector && (context.selector = _context.selector); // in case a context is created inside a context. Like a gsap.matchMedia() that's inside a scoped gsap.context()

      this.contexts.push(context);
      func = context.add("onMatch", func);
      context.queries = conditions;

      for (p in conditions) {
        if (p === "all") {
          active = 1;
        } else {
          mq = _win$1.matchMedia(conditions[p]);

          if (mq) {
            _media.indexOf(context) < 0 && _media.push(context);
            (cond[p] = mq.matches) && (active = 1);
            mq.addListener ? mq.addListener(_onMediaChange) : mq.addEventListener("change", _onMediaChange);
          }
        }
      }

      active && func(context, function (f) {
        return context.add(null, f);
      });
      return this;
    } // refresh() {
    // 	let time = _lastMediaTime,
    // 		media = _media;
    // 	_lastMediaTime = -1;
    // 	_media = this.contexts;
    // 	_onMediaChange();
    // 	_lastMediaTime = time;
    // 	_media = media;
    // }
    ;

    _proto6.revert = function revert(config) {
      this.kill(config || {});
    };

    _proto6.kill = function kill(revert) {
      this.contexts.forEach(function (c) {
        return c.kill(revert, true);
      });
    };

    return MatchMedia;
  }();
  /*
   * --------------------------------------------------------------------------------------
   * GSAP
   * --------------------------------------------------------------------------------------
   */


  var _gsap = {
    registerPlugin: function registerPlugin() {
      for (var _len2 = arguments.length, args = new Array(_len2), _key2 = 0; _key2 < _len2; _key2++) {
        args[_key2] = arguments[_key2];
      }

      args.forEach(function (config) {
        return _createPlugin(config);
      });
    },
    timeline: function timeline(vars) {
      return new Timeline(vars);
    },
    getTweensOf: function getTweensOf(targets, onlyActive) {
      return _globalTimeline.getTweensOf(targets, onlyActive);
    },
    getProperty: function getProperty(target, property, unit, uncache) {
      _isString(target) && (target = toArray(target)[0]); //in case selector text or an array is passed in

      var getter = _getCache(target || {}).get,
          format = unit ? _passThrough : _numericIfPossible;

      unit === "native" && (unit = "");
      return !target ? target : !property ? function (property, unit, uncache) {
        return format((_plugins[property] && _plugins[property].get || getter)(target, property, unit, uncache));
      } : format((_plugins[property] && _plugins[property].get || getter)(target, property, unit, uncache));
    },
    quickSetter: function quickSetter(target, property, unit) {
      target = toArray(target);

      if (target.length > 1) {
        var setters = target.map(function (t) {
          return gsap.quickSetter(t, property, unit);
        }),
            l = setters.length;
        return function (value) {
          var i = l;

          while (i--) {
            setters[i](value);
          }
        };
      }

      target = target[0] || {};

      var Plugin = _plugins[property],
          cache = _getCache(target),
          p = cache.harness && (cache.harness.aliases || {})[property] || property,
          // in case it's an alias, like "rotate" for "rotation".
      setter = Plugin ? function (value) {
        var p = new Plugin();
        _quickTween._pt = 0;
        p.init(target, unit ? value + unit : value, _quickTween, 0, [target]);
        p.render(1, p);
        _quickTween._pt && _renderPropTweens(1, _quickTween);
      } : cache.set(target, p);

      return Plugin ? setter : function (value) {
        return setter(target, p, unit ? value + unit : value, cache, 1);
      };
    },
    quickTo: function quickTo(target, property, vars) {
      var _setDefaults2;

      var tween = gsap.to(target, _setDefaults((_setDefaults2 = {}, _setDefaults2[property] = "+=0.1", _setDefaults2.paused = true, _setDefaults2.stagger = 0, _setDefaults2), vars || {})),
          func = function func(value, start, startIsRelative) {
        return tween.resetTo(property, value, start, startIsRelative);
      };

      func.tween = tween;
      return func;
    },
    isTweening: function isTweening(targets) {
      return _globalTimeline.getTweensOf(targets, true).length > 0;
    },
    defaults: function defaults(value) {
      value && value.ease && (value.ease = _parseEase(value.ease, _defaults.ease));
      return _mergeDeep(_defaults, value || {});
    },
    config: function config(value) {
      return _mergeDeep(_config, value || {});
    },
    registerEffect: function registerEffect(_ref3) {
      var name = _ref3.name,
          effect = _ref3.effect,
          plugins = _ref3.plugins,
          defaults = _ref3.defaults,
          extendTimeline = _ref3.extendTimeline;
      (plugins || "").split(",").forEach(function (pluginName) {
        return pluginName && !_plugins[pluginName] && !_globals[pluginName] && _warn(name + " effect requires " + pluginName + " plugin.");
      });

      _effects[name] = function (targets, vars, tl) {
        return effect(toArray(targets), _setDefaults(vars || {}, defaults), tl);
      };

      if (extendTimeline) {
        Timeline.prototype[name] = function (targets, vars, position) {
          return this.add(_effects[name](targets, _isObject(vars) ? vars : (position = vars) && {}, this), position);
        };
      }
    },
    registerEase: function registerEase(name, ease) {
      _easeMap[name] = _parseEase(ease);
    },
    parseEase: function parseEase(ease, defaultEase) {
      return arguments.length ? _parseEase(ease, defaultEase) : _easeMap;
    },
    getById: function getById(id) {
      return _globalTimeline.getById(id);
    },
    exportRoot: function exportRoot(vars, includeDelayedCalls) {
      if (vars === void 0) {
        vars = {};
      }

      var tl = new Timeline(vars),
          child,
          next;
      tl.smoothChildTiming = _isNotFalse(vars.smoothChildTiming);

      _globalTimeline.remove(tl);

      tl._dp = 0; //otherwise it'll get re-activated when adding children and be re-introduced into _globalTimeline's linked list (then added to itself).

      tl._time = tl._tTime = _globalTimeline._time;
      child = _globalTimeline._first;

      while (child) {
        next = child._next;

        if (includeDelayedCalls || !(!child._dur && child instanceof Tween && child.vars.onComplete === child._targets[0])) {
          _addToTimeline(tl, child, child._start - child._delay);
        }

        child = next;
      }

      _addToTimeline(_globalTimeline, tl, 0);

      return tl;
    },
    context: function context(func, scope) {
      return func ? new Context(func, scope) : _context;
    },
    matchMedia: function matchMedia(scope) {
      return new MatchMedia(scope);
    },
    matchMediaRefresh: function matchMediaRefresh() {
      return _media.forEach(function (c) {
        var cond = c.conditions,
            found,
            p;

        for (p in cond) {
          if (cond[p]) {
            cond[p] = false;
            found = 1;
          }
        }

        found && c.revert();
      }) || _onMediaChange();
    },
    addEventListener: function addEventListener(type, callback) {
      var a = _listeners[type] || (_listeners[type] = []);
      ~a.indexOf(callback) || a.push(callback);
    },
    removeEventListener: function removeEventListener(type, callback) {
      var a = _listeners[type],
          i = a && a.indexOf(callback);
      i >= 0 && a.splice(i, 1);
    },
    utils: {
      wrap: wrap,
      wrapYoyo: wrapYoyo,
      distribute: distribute,
      random: random,
      snap: snap,
      normalize: normalize,
      getUnit: getUnit,
      clamp: clamp,
      splitColor: splitColor,
      toArray: toArray,
      selector: selector,
      mapRange: mapRange,
      pipe: pipe,
      unitize: unitize,
      interpolate: interpolate,
      shuffle: shuffle
    },
    install: _install,
    effects: _effects,
    ticker: _ticker,
    updateRoot: Timeline.updateRoot,
    plugins: _plugins,
    globalTimeline: _globalTimeline,
    core: {
      PropTween: PropTween,
      globals: _addGlobal,
      Tween: Tween,
      Timeline: Timeline,
      Animation: Animation,
      getCache: _getCache,
      _removeLinkedListItem: _removeLinkedListItem,
      reverting: function reverting() {
        return _reverting$1;
      },
      context: function context(toAdd) {
        if (toAdd && _context) {
          _context.data.push(toAdd);

          toAdd._ctx = _context;
        }

        return _context;
      },
      suppressOverwrites: function suppressOverwrites(value) {
        return _suppressOverwrites = value;
      }
    }
  };

  _forEachName("to,from,fromTo,delayedCall,set,killTweensOf", function (name) {
    return _gsap[name] = Tween[name];
  });

  _ticker.add(Timeline.updateRoot);

  _quickTween = _gsap.to({}, {
    duration: 0
  }); // ---- EXTRA PLUGINS --------------------------------------------------------

  var _getPluginPropTween = function _getPluginPropTween(plugin, prop) {
    var pt = plugin._pt;

    while (pt && pt.p !== prop && pt.op !== prop && pt.fp !== prop) {
      pt = pt._next;
    }

    return pt;
  },
      _addModifiers = function _addModifiers(tween, modifiers) {
    var targets = tween._targets,
        p,
        i,
        pt;

    for (p in modifiers) {
      i = targets.length;

      while (i--) {
        pt = tween._ptLookup[i][p];

        if (pt && (pt = pt.d)) {
          if (pt._pt) {
            // is a plugin
            pt = _getPluginPropTween(pt, p);
          }

          pt && pt.modifier && pt.modifier(modifiers[p], tween, targets[i], p);
        }
      }
    }
  },
      _buildModifierPlugin = function _buildModifierPlugin(name, modifier) {
    return {
      name: name,
      rawVars: 1,
      //don't pre-process function-based values or "random()" strings.
      init: function init(target, vars, tween) {
        tween._onInit = function (tween) {
          var temp, p;

          if (_isString(vars)) {
            temp = {};

            _forEachName(vars, function (name) {
              return temp[name] = 1;
            }); //if the user passes in a comma-delimited list of property names to roundProps, like "x,y", we round to whole numbers.


            vars = temp;
          }

          if (modifier) {
            temp = {};

            for (p in vars) {
              temp[p] = modifier(vars[p]);
            }

            vars = temp;
          }

          _addModifiers(tween, vars);
        };
      }
    };
  }; //register core plugins


  var gsap = _gsap.registerPlugin({
    name: "attr",
    init: function init(target, vars, tween, index, targets) {
      var p, pt, v;
      this.tween = tween;

      for (p in vars) {
        v = target.getAttribute(p) || "";
        pt = this.add(target, "setAttribute", (v || 0) + "", vars[p], index, targets, 0, 0, p);
        pt.op = p;
        pt.b = v; // record the beginning value so we can revert()

        this._props.push(p);
      }
    },
    render: function render(ratio, data) {
      var pt = data._pt;

      while (pt) {
        _reverting$1 ? pt.set(pt.t, pt.p, pt.b, pt) : pt.r(ratio, pt.d); // if reverting, go back to the original (pt.b)

        pt = pt._next;
      }
    }
  }, {
    name: "endArray",
    init: function init(target, value) {
      var i = value.length;

      while (i--) {
        this.add(target, i, target[i] || 0, value[i], 0, 0, 0, 0, 0, 1);
      }
    }
  }, _buildModifierPlugin("roundProps", _roundModifier), _buildModifierPlugin("modifiers"), _buildModifierPlugin("snap", snap)) || _gsap; //to prevent the core plugins from being dropped via aggressive tree shaking, we must include them in the variable declaration in this way.

  Tween.version = Timeline.version = gsap.version = "3.12.7";
  _coreReady = 1;
  _windowExists$1() && _wake();
  _easeMap.Power0;
      _easeMap.Power1;
      _easeMap.Power2;
      _easeMap.Power3;
      _easeMap.Power4;
      _easeMap.Linear;
      _easeMap.Quad;
      _easeMap.Cubic;
      _easeMap.Quart;
      _easeMap.Quint;
      _easeMap.Strong;
      _easeMap.Elastic;
      _easeMap.Back;
      _easeMap.SteppedEase;
      _easeMap.Bounce;
      _easeMap.Sine;
      _easeMap.Expo;
      _easeMap.Circ;

  /*!
   * CSSPlugin 3.12.7
   * https://gsap.com
   *
   * Copyright 2008-2025, GreenSock. All rights reserved.
   * Subject to the terms at https://gsap.com/standard-license or for
   * Club GSAP members, the agreement issued with that membership.
   * @author: Jack Doyle, jack@greensock.com
  */

  var _win,
      _doc,
      _docElement,
      _pluginInitted,
      _tempDiv,
      _recentSetterPlugin,
      _reverting,
      _windowExists = function _windowExists() {
    return typeof window !== "undefined";
  },
      _transformProps = {},
      _RAD2DEG = 180 / Math.PI,
      _DEG2RAD = Math.PI / 180,
      _atan2 = Math.atan2,
      _bigNum = 1e8,
      _capsExp = /([A-Z])/g,
      _horizontalExp = /(left|right|width|margin|padding|x)/i,
      _complexExp = /[\s,\(]\S/,
      _propertyAliases = {
    autoAlpha: "opacity,visibility",
    scale: "scaleX,scaleY",
    alpha: "opacity"
  },
      _renderCSSProp = function _renderCSSProp(ratio, data) {
    return data.set(data.t, data.p, Math.round((data.s + data.c * ratio) * 10000) / 10000 + data.u, data);
  },
      _renderPropWithEnd = function _renderPropWithEnd(ratio, data) {
    return data.set(data.t, data.p, ratio === 1 ? data.e : Math.round((data.s + data.c * ratio) * 10000) / 10000 + data.u, data);
  },
      _renderCSSPropWithBeginning = function _renderCSSPropWithBeginning(ratio, data) {
    return data.set(data.t, data.p, ratio ? Math.round((data.s + data.c * ratio) * 10000) / 10000 + data.u : data.b, data);
  },
      //if units change, we need a way to render the original unit/value when the tween goes all the way back to the beginning (ratio:0)
  _renderRoundedCSSProp = function _renderRoundedCSSProp(ratio, data) {
    var value = data.s + data.c * ratio;
    data.set(data.t, data.p, ~~(value + (value < 0 ? -.5 : .5)) + data.u, data);
  },
      _renderNonTweeningValue = function _renderNonTweeningValue(ratio, data) {
    return data.set(data.t, data.p, ratio ? data.e : data.b, data);
  },
      _renderNonTweeningValueOnlyAtEnd = function _renderNonTweeningValueOnlyAtEnd(ratio, data) {
    return data.set(data.t, data.p, ratio !== 1 ? data.b : data.e, data);
  },
      _setterCSSStyle = function _setterCSSStyle(target, property, value) {
    return target.style[property] = value;
  },
      _setterCSSProp = function _setterCSSProp(target, property, value) {
    return target.style.setProperty(property, value);
  },
      _setterTransform = function _setterTransform(target, property, value) {
    return target._gsap[property] = value;
  },
      _setterScale = function _setterScale(target, property, value) {
    return target._gsap.scaleX = target._gsap.scaleY = value;
  },
      _setterScaleWithRender = function _setterScaleWithRender(target, property, value, data, ratio) {
    var cache = target._gsap;
    cache.scaleX = cache.scaleY = value;
    cache.renderTransform(ratio, cache);
  },
      _setterTransformWithRender = function _setterTransformWithRender(target, property, value, data, ratio) {
    var cache = target._gsap;
    cache[property] = value;
    cache.renderTransform(ratio, cache);
  },
      _transformProp = "transform",
      _transformOriginProp = _transformProp + "Origin",
      _saveStyle = function _saveStyle(property, isNotCSS) {
    var _this = this;

    var target = this.target,
        style = target.style,
        cache = target._gsap;

    if (property in _transformProps && style) {
      this.tfm = this.tfm || {};

      if (property !== "transform") {
        property = _propertyAliases[property] || property;
        ~property.indexOf(",") ? property.split(",").forEach(function (a) {
          return _this.tfm[a] = _get(target, a);
        }) : this.tfm[property] = cache.x ? cache[property] : _get(target, property); // note: scale would map to "scaleX,scaleY", thus we loop and apply them both.

        property === _transformOriginProp && (this.tfm.zOrigin = cache.zOrigin);
      } else {
        return _propertyAliases.transform.split(",").forEach(function (p) {
          return _saveStyle.call(_this, p, isNotCSS);
        });
      }

      if (this.props.indexOf(_transformProp) >= 0) {
        return;
      }

      if (cache.svg) {
        this.svgo = target.getAttribute("data-svg-origin");
        this.props.push(_transformOriginProp, isNotCSS, "");
      }

      property = _transformProp;
    }

    (style || isNotCSS) && this.props.push(property, isNotCSS, style[property]);
  },
      _removeIndependentTransforms = function _removeIndependentTransforms(style) {
    if (style.translate) {
      style.removeProperty("translate");
      style.removeProperty("scale");
      style.removeProperty("rotate");
    }
  },
      _revertStyle = function _revertStyle() {
    var props = this.props,
        target = this.target,
        style = target.style,
        cache = target._gsap,
        i,
        p;

    for (i = 0; i < props.length; i += 3) {
      // stored like this: property, isNotCSS, value
      if (!props[i + 1]) {
        props[i + 2] ? style[props[i]] = props[i + 2] : style.removeProperty(props[i].substr(0, 2) === "--" ? props[i] : props[i].replace(_capsExp, "-$1").toLowerCase());
      } else if (props[i + 1] === 2) {
        // non-CSS value (function-based)
        target[props[i]](props[i + 2]);
      } else {
        // non-CSS value (not function-based)
        target[props[i]] = props[i + 2];
      }
    }

    if (this.tfm) {
      for (p in this.tfm) {
        cache[p] = this.tfm[p];
      }

      if (cache.svg) {
        cache.renderTransform();
        target.setAttribute("data-svg-origin", this.svgo || "");
      }

      i = _reverting();

      if ((!i || !i.isStart) && !style[_transformProp]) {
        _removeIndependentTransforms(style);

        if (cache.zOrigin && style[_transformOriginProp]) {
          style[_transformOriginProp] += " " + cache.zOrigin + "px"; // since we're uncaching, we must put the zOrigin back into the transformOrigin so that we can pull it out accurately when we parse again. Otherwise, we'd lose the z portion of the origin since we extract it to protect from Safari bugs.

          cache.zOrigin = 0;
          cache.renderTransform();
        }

        cache.uncache = 1; // if it's a startAt that's being reverted in the _initTween() of the core, we don't need to uncache transforms. This is purely a performance optimization.
      }
    }
  },
      _getStyleSaver = function _getStyleSaver(target, properties) {
    var saver = {
      target: target,
      props: [],
      revert: _revertStyle,
      save: _saveStyle
    };
    target._gsap || gsap.core.getCache(target); // just make sure there's a _gsap cache defined because we read from it in _saveStyle() and it's more efficient to just check it here once.

    properties && target.style && target.nodeType && properties.split(",").forEach(function (p) {
      return saver.save(p);
    }); // make sure it's a DOM node too.

    return saver;
  },
      _supports3D,
      _createElement = function _createElement(type, ns) {
    var e = _doc.createElementNS ? _doc.createElementNS((ns || "http://www.w3.org/1999/xhtml").replace(/^https/, "http"), type) : _doc.createElement(type); //some servers swap in https for http in the namespace which can break things, making "style" inaccessible.

    return e && e.style ? e : _doc.createElement(type); //some environments won't allow access to the element's style when created with a namespace in which case we default to the standard createElement() to work around the issue. Also note that when GSAP is embedded directly inside an SVG file, createElement() won't allow access to the style object in Firefox (see https://gsap.com/forums/topic/20215-problem-using-tweenmax-in-standalone-self-containing-svg-file-err-cannot-set-property-csstext-of-undefined/).
  },
      _getComputedProperty = function _getComputedProperty(target, property, skipPrefixFallback) {
    var cs = getComputedStyle(target);
    return cs[property] || cs.getPropertyValue(property.replace(_capsExp, "-$1").toLowerCase()) || cs.getPropertyValue(property) || !skipPrefixFallback && _getComputedProperty(target, _checkPropPrefix(property) || property, 1) || ""; //css variables may not need caps swapped out for dashes and lowercase.
  },
      _prefixes = "O,Moz,ms,Ms,Webkit".split(","),
      _checkPropPrefix = function _checkPropPrefix(property, element, preferPrefix) {
    var e = element || _tempDiv,
        s = e.style,
        i = 5;

    if (property in s && !preferPrefix) {
      return property;
    }

    property = property.charAt(0).toUpperCase() + property.substr(1);

    while (i-- && !(_prefixes[i] + property in s)) {}

    return i < 0 ? null : (i === 3 ? "ms" : i >= 0 ? _prefixes[i] : "") + property;
  },
      _initCore = function _initCore() {
    if (_windowExists() && window.document) {
      _win = window;
      _doc = _win.document;
      _docElement = _doc.documentElement;
      _tempDiv = _createElement("div") || {
        style: {}
      };
      _createElement("div");
      _transformProp = _checkPropPrefix(_transformProp);
      _transformOriginProp = _transformProp + "Origin";
      _tempDiv.style.cssText = "border-width:0;line-height:0;position:absolute;padding:0"; //make sure to override certain properties that may contaminate measurements, in case the user has overreaching style sheets.

      _supports3D = !!_checkPropPrefix("perspective");
      _reverting = gsap.core.reverting;
      _pluginInitted = 1;
    }
  },
      _getReparentedCloneBBox = function _getReparentedCloneBBox(target) {
    //works around issues in some browsers (like Firefox) that don't correctly report getBBox() on SVG elements inside a <defs> element and/or <mask>. We try creating an SVG, adding it to the documentElement and toss the element in there so that it's definitely part of the rendering tree, then grab the bbox and if it works, we actually swap out the original getBBox() method for our own that does these extra steps whenever getBBox is needed. This helps ensure that performance is optimal (only do all these extra steps when absolutely necessary...most elements don't need it).
    var owner = target.ownerSVGElement,
        svg = _createElement("svg", owner && owner.getAttribute("xmlns") || "http://www.w3.org/2000/svg"),
        clone = target.cloneNode(true),
        bbox;

    clone.style.display = "block";
    svg.appendChild(clone);

    _docElement.appendChild(svg);

    try {
      bbox = clone.getBBox();
    } catch (e) {}

    svg.removeChild(clone);

    _docElement.removeChild(svg);

    return bbox;
  },
      _getAttributeFallbacks = function _getAttributeFallbacks(target, attributesArray) {
    var i = attributesArray.length;

    while (i--) {
      if (target.hasAttribute(attributesArray[i])) {
        return target.getAttribute(attributesArray[i]);
      }
    }
  },
      _getBBox = function _getBBox(target) {
    var bounds, cloned;

    try {
      bounds = target.getBBox(); //Firefox throws errors if you try calling getBBox() on an SVG element that's not rendered (like in a <symbol> or <defs>). https://bugzilla.mozilla.org/show_bug.cgi?id=612118
    } catch (error) {
      bounds = _getReparentedCloneBBox(target);
      cloned = 1;
    }

    bounds && (bounds.width || bounds.height) || cloned || (bounds = _getReparentedCloneBBox(target)); //some browsers (like Firefox) misreport the bounds if the element has zero width and height (it just assumes it's at x:0, y:0), thus we need to manually grab the position in that case.

    return bounds && !bounds.width && !bounds.x && !bounds.y ? {
      x: +_getAttributeFallbacks(target, ["x", "cx", "x1"]) || 0,
      y: +_getAttributeFallbacks(target, ["y", "cy", "y1"]) || 0,
      width: 0,
      height: 0
    } : bounds;
  },
      _isSVG = function _isSVG(e) {
    return !!(e.getCTM && (!e.parentNode || e.ownerSVGElement) && _getBBox(e));
  },
      //reports if the element is an SVG on which getBBox() actually works
  _removeProperty = function _removeProperty(target, property) {
    if (property) {
      var style = target.style,
          first2Chars;

      if (property in _transformProps && property !== _transformOriginProp) {
        property = _transformProp;
      }

      if (style.removeProperty) {
        first2Chars = property.substr(0, 2);

        if (first2Chars === "ms" || property.substr(0, 6) === "webkit") {
          //Microsoft and some Webkit browsers don't conform to the standard of capitalizing the first prefix character, so we adjust so that when we prefix the caps with a dash, it's correct (otherwise it'd be "ms-transform" instead of "-ms-transform" for IE9, for example)
          property = "-" + property;
        }

        style.removeProperty(first2Chars === "--" ? property : property.replace(_capsExp, "-$1").toLowerCase());
      } else {
        //note: old versions of IE use "removeAttribute()" instead of "removeProperty()"
        style.removeAttribute(property);
      }
    }
  },
      _addNonTweeningPT = function _addNonTweeningPT(plugin, target, property, beginning, end, onlySetAtEnd) {
    var pt = new PropTween(plugin._pt, target, property, 0, 1, onlySetAtEnd ? _renderNonTweeningValueOnlyAtEnd : _renderNonTweeningValue);
    plugin._pt = pt;
    pt.b = beginning;
    pt.e = end;

    plugin._props.push(property);

    return pt;
  },
      _nonConvertibleUnits = {
    deg: 1,
    rad: 1,
    turn: 1
  },
      _nonStandardLayouts = {
    grid: 1,
    flex: 1
  },
      //takes a single value like 20px and converts it to the unit specified, like "%", returning only the numeric amount.
  _convertToUnit = function _convertToUnit(target, property, value, unit) {
    var curValue = parseFloat(value) || 0,
        curUnit = (value + "").trim().substr((curValue + "").length) || "px",
        // some browsers leave extra whitespace at the beginning of CSS variables, hence the need to trim()
    style = _tempDiv.style,
        horizontal = _horizontalExp.test(property),
        isRootSVG = target.tagName.toLowerCase() === "svg",
        measureProperty = (isRootSVG ? "client" : "offset") + (horizontal ? "Width" : "Height"),
        amount = 100,
        toPixels = unit === "px",
        toPercent = unit === "%",
        px,
        parent,
        cache,
        isSVG;

    if (unit === curUnit || !curValue || _nonConvertibleUnits[unit] || _nonConvertibleUnits[curUnit]) {
      return curValue;
    }

    curUnit !== "px" && !toPixels && (curValue = _convertToUnit(target, property, value, "px"));
    isSVG = target.getCTM && _isSVG(target);

    if ((toPercent || curUnit === "%") && (_transformProps[property] || ~property.indexOf("adius"))) {
      px = isSVG ? target.getBBox()[horizontal ? "width" : "height"] : target[measureProperty];
      return _round(toPercent ? curValue / px * amount : curValue / 100 * px);
    }

    style[horizontal ? "width" : "height"] = amount + (toPixels ? curUnit : unit);
    parent = unit !== "rem" && ~property.indexOf("adius") || unit === "em" && target.appendChild && !isRootSVG ? target : target.parentNode;

    if (isSVG) {
      parent = (target.ownerSVGElement || {}).parentNode;
    }

    if (!parent || parent === _doc || !parent.appendChild) {
      parent = _doc.body;
    }

    cache = parent._gsap;

    if (cache && toPercent && cache.width && horizontal && cache.time === _ticker.time && !cache.uncache) {
      return _round(curValue / cache.width * amount);
    } else {
      if (toPercent && (property === "height" || property === "width")) {
        // if we're dealing with width/height that's inside a container with padding and/or it's a flexbox/grid container, we must apply it to the target itself rather than the _tempDiv in order to ensure complete accuracy, factoring in the parent's padding.
        var v = target.style[property];
        target.style[property] = amount + unit;
        px = target[measureProperty];
        v ? target.style[property] = v : _removeProperty(target, property);
      } else {
        (toPercent || curUnit === "%") && !_nonStandardLayouts[_getComputedProperty(parent, "display")] && (style.position = _getComputedProperty(target, "position"));
        parent === target && (style.position = "static"); // like for borderRadius, if it's a % we must have it relative to the target itself but that may not have position: relative or position: absolute in which case it'd go up the chain until it finds its offsetParent (bad). position: static protects against that.

        parent.appendChild(_tempDiv);
        px = _tempDiv[measureProperty];
        parent.removeChild(_tempDiv);
        style.position = "absolute";
      }

      if (horizontal && toPercent) {
        cache = _getCache(parent);
        cache.time = _ticker.time;
        cache.width = parent[measureProperty];
      }
    }

    return _round(toPixels ? px * curValue / amount : px && curValue ? amount / px * curValue : 0);
  },
      _get = function _get(target, property, unit, uncache) {
    var value;
    _pluginInitted || _initCore();

    if (property in _propertyAliases && property !== "transform") {
      property = _propertyAliases[property];

      if (~property.indexOf(",")) {
        property = property.split(",")[0];
      }
    }

    if (_transformProps[property] && property !== "transform") {
      value = _parseTransform(target, uncache);
      value = property !== "transformOrigin" ? value[property] : value.svg ? value.origin : _firstTwoOnly(_getComputedProperty(target, _transformOriginProp)) + " " + value.zOrigin + "px";
    } else {
      value = target.style[property];

      if (!value || value === "auto" || uncache || ~(value + "").indexOf("calc(")) {
        value = _specialProps[property] && _specialProps[property](target, property, unit) || _getComputedProperty(target, property) || _getProperty(target, property) || (property === "opacity" ? 1 : 0); // note: some browsers, like Firefox, don't report borderRadius correctly! Instead, it only reports every corner like  borderTopLeftRadius
      }
    }

    return unit && !~(value + "").trim().indexOf(" ") ? _convertToUnit(target, property, value, unit) + unit : value;
  },
      _tweenComplexCSSString = function _tweenComplexCSSString(target, prop, start, end) {
    // note: we call _tweenComplexCSSString.call(pluginInstance...) to ensure that it's scoped properly. We may call it from within a plugin too, thus "this" would refer to the plugin.
    if (!start || start === "none") {
      // some browsers like Safari actually PREFER the prefixed property and mis-report the unprefixed value like clipPath (BUG). In other words, even though clipPath exists in the style ("clipPath" in target.style) and it's set in the CSS properly (along with -webkit-clip-path), Safari reports clipPath as "none" whereas WebkitClipPath reports accurately like "ellipse(100% 0% at 50% 0%)", so in this case we must SWITCH to using the prefixed property instead. See https://gsap.com/forums/topic/18310-clippath-doesnt-work-on-ios/
      var p = _checkPropPrefix(prop, target, 1),
          s = p && _getComputedProperty(target, p, 1);

      if (s && s !== start) {
        prop = p;
        start = s;
      } else if (prop === "borderColor") {
        start = _getComputedProperty(target, "borderTopColor"); // Firefox bug: always reports "borderColor" as "", so we must fall back to borderTopColor. See https://gsap.com/forums/topic/24583-how-to-return-colors-that-i-had-after-reverse/
      }
    }

    var pt = new PropTween(this._pt, target.style, prop, 0, 1, _renderComplexString),
        index = 0,
        matchIndex = 0,
        a,
        result,
        startValues,
        startNum,
        color,
        startValue,
        endValue,
        endNum,
        chunk,
        endUnit,
        startUnit,
        endValues;
    pt.b = start;
    pt.e = end;
    start += ""; // ensure values are strings

    end += "";

    if (end === "auto") {
      startValue = target.style[prop];
      target.style[prop] = end;
      end = _getComputedProperty(target, prop) || end;
      startValue ? target.style[prop] = startValue : _removeProperty(target, prop);
    }

    a = [start, end];

    _colorStringFilter(a); // pass an array with the starting and ending values and let the filter do whatever it needs to the values. If colors are found, it returns true and then we must match where the color shows up order-wise because for things like boxShadow, sometimes the browser provides the computed values with the color FIRST, but the user provides it with the color LAST, so flip them if necessary. Same for drop-shadow().


    start = a[0];
    end = a[1];
    startValues = start.match(_numWithUnitExp) || [];
    endValues = end.match(_numWithUnitExp) || [];

    if (endValues.length) {
      while (result = _numWithUnitExp.exec(end)) {
        endValue = result[0];
        chunk = end.substring(index, result.index);

        if (color) {
          color = (color + 1) % 5;
        } else if (chunk.substr(-5) === "rgba(" || chunk.substr(-5) === "hsla(") {
          color = 1;
        }

        if (endValue !== (startValue = startValues[matchIndex++] || "")) {
          startNum = parseFloat(startValue) || 0;
          startUnit = startValue.substr((startNum + "").length);
          endValue.charAt(1) === "=" && (endValue = _parseRelative(startNum, endValue) + startUnit);
          endNum = parseFloat(endValue);
          endUnit = endValue.substr((endNum + "").length);
          index = _numWithUnitExp.lastIndex - endUnit.length;

          if (!endUnit) {
            //if something like "perspective:300" is passed in and we must add a unit to the end
            endUnit = endUnit || _config.units[prop] || startUnit;

            if (index === end.length) {
              end += endUnit;
              pt.e += endUnit;
            }
          }

          if (startUnit !== endUnit) {
            startNum = _convertToUnit(target, prop, startValue, endUnit) || 0;
          } // these nested PropTweens are handled in a special way - we'll never actually call a render or setter method on them. We'll just loop through them in the parent complex string PropTween's render method.


          pt._pt = {
            _next: pt._pt,
            p: chunk || matchIndex === 1 ? chunk : ",",
            //note: SVG spec allows omission of comma/space when a negative sign is wedged between two numbers, like 2.5-5.3 instead of 2.5,-5.3 but when tweening, the negative value may switch to positive, so we insert the comma just in case.
            s: startNum,
            c: endNum - startNum,
            m: color && color < 4 || prop === "zIndex" ? Math.round : 0
          };
        }
      }

      pt.c = index < end.length ? end.substring(index, end.length) : ""; //we use the "c" of the PropTween to store the final part of the string (after the last number)
    } else {
      pt.r = prop === "display" && end === "none" ? _renderNonTweeningValueOnlyAtEnd : _renderNonTweeningValue;
    }

    _relExp.test(end) && (pt.e = 0); //if the end string contains relative values or dynamic random(...) values, delete the end it so that on the final render we don't actually set it to the string with += or -= characters (forces it to use the calculated value).

    this._pt = pt; //start the linked list with this new PropTween. Remember, we call _tweenComplexCSSString.call(pluginInstance...) to ensure that it's scoped properly. We may call it from within another plugin too, thus "this" would refer to the plugin.

    return pt;
  },
      _keywordToPercent = {
    top: "0%",
    bottom: "100%",
    left: "0%",
    right: "100%",
    center: "50%"
  },
      _convertKeywordsToPercentages = function _convertKeywordsToPercentages(value) {
    var split = value.split(" "),
        x = split[0],
        y = split[1] || "50%";

    if (x === "top" || x === "bottom" || y === "left" || y === "right") {
      //the user provided them in the wrong order, so flip them
      value = x;
      x = y;
      y = value;
    }

    split[0] = _keywordToPercent[x] || x;
    split[1] = _keywordToPercent[y] || y;
    return split.join(" ");
  },
      _renderClearProps = function _renderClearProps(ratio, data) {
    if (data.tween && data.tween._time === data.tween._dur) {
      var target = data.t,
          style = target.style,
          props = data.u,
          cache = target._gsap,
          prop,
          clearTransforms,
          i;

      if (props === "all" || props === true) {
        style.cssText = "";
        clearTransforms = 1;
      } else {
        props = props.split(",");
        i = props.length;

        while (--i > -1) {
          prop = props[i];

          if (_transformProps[prop]) {
            clearTransforms = 1;
            prop = prop === "transformOrigin" ? _transformOriginProp : _transformProp;
          }

          _removeProperty(target, prop);
        }
      }

      if (clearTransforms) {
        _removeProperty(target, _transformProp);

        if (cache) {
          cache.svg && target.removeAttribute("transform");
          style.scale = style.rotate = style.translate = "none";

          _parseTransform(target, 1); // force all the cached values back to "normal"/identity, otherwise if there's another tween that's already set to render transforms on this element, it could display the wrong values.


          cache.uncache = 1;

          _removeIndependentTransforms(style);
        }
      }
    }
  },
      // note: specialProps should return 1 if (and only if) they have a non-zero priority. It indicates we need to sort the linked list.
  _specialProps = {
    clearProps: function clearProps(plugin, target, property, endValue, tween) {
      if (tween.data !== "isFromStart") {
        var pt = plugin._pt = new PropTween(plugin._pt, target, property, 0, 0, _renderClearProps);
        pt.u = endValue;
        pt.pr = -10;
        pt.tween = tween;

        plugin._props.push(property);

        return 1;
      }
    }
    /* className feature (about 0.4kb gzipped).
    , className(plugin, target, property, endValue, tween) {
    	let _renderClassName = (ratio, data) => {
    			data.css.render(ratio, data.css);
    			if (!ratio || ratio === 1) {
    				let inline = data.rmv,
    					target = data.t,
    					p;
    				target.setAttribute("class", ratio ? data.e : data.b);
    				for (p in inline) {
    					_removeProperty(target, p);
    				}
    			}
    		},
    		_getAllStyles = (target) => {
    			let styles = {},
    				computed = getComputedStyle(target),
    				p;
    			for (p in computed) {
    				if (isNaN(p) && p !== "cssText" && p !== "length") {
    					styles[p] = computed[p];
    				}
    			}
    			_setDefaults(styles, _parseTransform(target, 1));
    			return styles;
    		},
    		startClassList = target.getAttribute("class"),
    		style = target.style,
    		cssText = style.cssText,
    		cache = target._gsap,
    		classPT = cache.classPT,
    		inlineToRemoveAtEnd = {},
    		data = {t:target, plugin:plugin, rmv:inlineToRemoveAtEnd, b:startClassList, e:(endValue.charAt(1) !== "=") ? endValue : startClassList.replace(new RegExp("(?:\\s|^)" + endValue.substr(2) + "(?![\\w-])"), "") + ((endValue.charAt(0) === "+") ? " " + endValue.substr(2) : "")},
    		changingVars = {},
    		startVars = _getAllStyles(target),
    		transformRelated = /(transform|perspective)/i,
    		endVars, p;
    	if (classPT) {
    		classPT.r(1, classPT.d);
    		_removeLinkedListItem(classPT.d.plugin, classPT, "_pt");
    	}
    	target.setAttribute("class", data.e);
    	endVars = _getAllStyles(target, true);
    	target.setAttribute("class", startClassList);
    	for (p in endVars) {
    		if (endVars[p] !== startVars[p] && !transformRelated.test(p)) {
    			changingVars[p] = endVars[p];
    			if (!style[p] && style[p] !== "0") {
    				inlineToRemoveAtEnd[p] = 1;
    			}
    		}
    	}
    	cache.classPT = plugin._pt = new PropTween(plugin._pt, target, "className", 0, 0, _renderClassName, data, 0, -11);
    	if (style.cssText !== cssText) { //only apply if things change. Otherwise, in cases like a background-image that's pulled dynamically, it could cause a refresh. See https://gsap.com/forums/topic/20368-possible-gsap-bug-switching-classnames-in-chrome/.
    		style.cssText = cssText; //we recorded cssText before we swapped classes and ran _getAllStyles() because in cases when a className tween is overwritten, we remove all the related tweening properties from that class change (otherwise class-specific stuff can't override properties we've directly set on the target's style object due to specificity).
    	}
    	_parseTransform(target, true); //to clear the caching of transforms
    	data.css = new gsap.plugins.css();
    	data.css.init(target, changingVars, tween);
    	plugin._props.push(...data.css._props);
    	return 1;
    }
    */

  },

  /*
   * --------------------------------------------------------------------------------------
   * TRANSFORMS
   * --------------------------------------------------------------------------------------
   */
  _identity2DMatrix = [1, 0, 0, 1, 0, 0],
      _rotationalProperties = {},
      _isNullTransform = function _isNullTransform(value) {
    return value === "matrix(1, 0, 0, 1, 0, 0)" || value === "none" || !value;
  },
      _getComputedTransformMatrixAsArray = function _getComputedTransformMatrixAsArray(target) {
    var matrixString = _getComputedProperty(target, _transformProp);

    return _isNullTransform(matrixString) ? _identity2DMatrix : matrixString.substr(7).match(_numExp).map(_round);
  },
      _getMatrix = function _getMatrix(target, force2D) {
    var cache = target._gsap || _getCache(target),
        style = target.style,
        matrix = _getComputedTransformMatrixAsArray(target),
        parent,
        nextSibling,
        temp,
        addedToDOM;

    if (cache.svg && target.getAttribute("transform")) {
      temp = target.transform.baseVal.consolidate().matrix; //ensures that even complex values like "translate(50,60) rotate(135,0,0)" are parsed because it mashes it into a matrix.

      matrix = [temp.a, temp.b, temp.c, temp.d, temp.e, temp.f];
      return matrix.join(",") === "1,0,0,1,0,0" ? _identity2DMatrix : matrix;
    } else if (matrix === _identity2DMatrix && !target.offsetParent && target !== _docElement && !cache.svg) {
      //note: if offsetParent is null, that means the element isn't in the normal document flow, like if it has display:none or one of its ancestors has display:none). Firefox returns null for getComputedStyle() if the element is in an iframe that has display:none. https://bugzilla.mozilla.org/show_bug.cgi?id=548397
      //browsers don't report transforms accurately unless the element is in the DOM and has a display value that's not "none". Firefox and Microsoft browsers have a partial bug where they'll report transforms even if display:none BUT not any percentage-based values like translate(-50%, 8px) will be reported as if it's translate(0, 8px).
      temp = style.display;
      style.display = "block";
      parent = target.parentNode;

      if (!parent || !target.offsetParent && !target.getBoundingClientRect().width) {
        // note: in 3.3.0 we switched target.offsetParent to _doc.body.contains(target) to avoid [sometimes unnecessary] MutationObserver calls but that wasn't adequate because there are edge cases where nested position: fixed elements need to get reparented to accurately sense transforms. See https://github.com/greensock/GSAP/issues/388 and https://github.com/greensock/GSAP/issues/375. Note: position: fixed elements report a null offsetParent but they could also be invisible because they're in an ancestor with display: none, so we check getBoundingClientRect(). We only want to alter the DOM if we absolutely have to because it can cause iframe content to reload, like a Vimeo video.
        addedToDOM = 1; //flag

        nextSibling = target.nextElementSibling;

        _docElement.appendChild(target); //we must add it to the DOM in order to get values properly

      }

      matrix = _getComputedTransformMatrixAsArray(target);
      temp ? style.display = temp : _removeProperty(target, "display");

      if (addedToDOM) {
        nextSibling ? parent.insertBefore(target, nextSibling) : parent ? parent.appendChild(target) : _docElement.removeChild(target);
      }
    }

    return force2D && matrix.length > 6 ? [matrix[0], matrix[1], matrix[4], matrix[5], matrix[12], matrix[13]] : matrix;
  },
      _applySVGOrigin = function _applySVGOrigin(target, origin, originIsAbsolute, smooth, matrixArray, pluginToAddPropTweensTo) {
    var cache = target._gsap,
        matrix = matrixArray || _getMatrix(target, true),
        xOriginOld = cache.xOrigin || 0,
        yOriginOld = cache.yOrigin || 0,
        xOffsetOld = cache.xOffset || 0,
        yOffsetOld = cache.yOffset || 0,
        a = matrix[0],
        b = matrix[1],
        c = matrix[2],
        d = matrix[3],
        tx = matrix[4],
        ty = matrix[5],
        originSplit = origin.split(" "),
        xOrigin = parseFloat(originSplit[0]) || 0,
        yOrigin = parseFloat(originSplit[1]) || 0,
        bounds,
        determinant,
        x,
        y;

    if (!originIsAbsolute) {
      bounds = _getBBox(target);
      xOrigin = bounds.x + (~originSplit[0].indexOf("%") ? xOrigin / 100 * bounds.width : xOrigin);
      yOrigin = bounds.y + (~(originSplit[1] || originSplit[0]).indexOf("%") ? yOrigin / 100 * bounds.height : yOrigin); // if (!("xOrigin" in cache) && (xOrigin || yOrigin)) { // added in 3.12.3, reverted in 3.12.4; requires more exploration
      // 	xOrigin -= bounds.x;
      // 	yOrigin -= bounds.y;
      // }
    } else if (matrix !== _identity2DMatrix && (determinant = a * d - b * c)) {
      //if it's zero (like if scaleX and scaleY are zero), skip it to avoid errors with dividing by zero.
      x = xOrigin * (d / determinant) + yOrigin * (-c / determinant) + (c * ty - d * tx) / determinant;
      y = xOrigin * (-b / determinant) + yOrigin * (a / determinant) - (a * ty - b * tx) / determinant;
      xOrigin = x;
      yOrigin = y; // theory: we only had to do this for smoothing and it assumes that the previous one was not originIsAbsolute.
    }

    if (smooth || smooth !== false && cache.smooth) {
      tx = xOrigin - xOriginOld;
      ty = yOrigin - yOriginOld;
      cache.xOffset = xOffsetOld + (tx * a + ty * c) - tx;
      cache.yOffset = yOffsetOld + (tx * b + ty * d) - ty;
    } else {
      cache.xOffset = cache.yOffset = 0;
    }

    cache.xOrigin = xOrigin;
    cache.yOrigin = yOrigin;
    cache.smooth = !!smooth;
    cache.origin = origin;
    cache.originIsAbsolute = !!originIsAbsolute;
    target.style[_transformOriginProp] = "0px 0px"; //otherwise, if someone sets  an origin via CSS, it will likely interfere with the SVG transform attribute ones (because remember, we're baking the origin into the matrix() value).

    if (pluginToAddPropTweensTo) {
      _addNonTweeningPT(pluginToAddPropTweensTo, cache, "xOrigin", xOriginOld, xOrigin);

      _addNonTweeningPT(pluginToAddPropTweensTo, cache, "yOrigin", yOriginOld, yOrigin);

      _addNonTweeningPT(pluginToAddPropTweensTo, cache, "xOffset", xOffsetOld, cache.xOffset);

      _addNonTweeningPT(pluginToAddPropTweensTo, cache, "yOffset", yOffsetOld, cache.yOffset);
    }

    target.setAttribute("data-svg-origin", xOrigin + " " + yOrigin);
  },
      _parseTransform = function _parseTransform(target, uncache) {
    var cache = target._gsap || new GSCache(target);

    if ("x" in cache && !uncache && !cache.uncache) {
      return cache;
    }

    var style = target.style,
        invertedScaleX = cache.scaleX < 0,
        px = "px",
        deg = "deg",
        cs = getComputedStyle(target),
        origin = _getComputedProperty(target, _transformOriginProp) || "0",
        x,
        y,
        z,
        scaleX,
        scaleY,
        rotation,
        rotationX,
        rotationY,
        skewX,
        skewY,
        perspective,
        xOrigin,
        yOrigin,
        matrix,
        angle,
        cos,
        sin,
        a,
        b,
        c,
        d,
        a12,
        a22,
        t1,
        t2,
        t3,
        a13,
        a23,
        a33,
        a42,
        a43,
        a32;
    x = y = z = rotation = rotationX = rotationY = skewX = skewY = perspective = 0;
    scaleX = scaleY = 1;
    cache.svg = !!(target.getCTM && _isSVG(target));

    if (cs.translate) {
      // accommodate independent transforms by combining them into normal ones.
      if (cs.translate !== "none" || cs.scale !== "none" || cs.rotate !== "none") {
        style[_transformProp] = (cs.translate !== "none" ? "translate3d(" + (cs.translate + " 0 0").split(" ").slice(0, 3).join(", ") + ") " : "") + (cs.rotate !== "none" ? "rotate(" + cs.rotate + ") " : "") + (cs.scale !== "none" ? "scale(" + cs.scale.split(" ").join(",") + ") " : "") + (cs[_transformProp] !== "none" ? cs[_transformProp] : "");
      }

      style.scale = style.rotate = style.translate = "none";
    }

    matrix = _getMatrix(target, cache.svg);

    if (cache.svg) {
      if (cache.uncache) {
        // if cache.uncache is true (and maybe if origin is 0,0), we need to set element.style.transformOrigin = (cache.xOrigin - bbox.x) + "px " + (cache.yOrigin - bbox.y) + "px". Previously we let the data-svg-origin stay instead, but when introducing revert(), it complicated things.
        t2 = target.getBBox();
        origin = cache.xOrigin - t2.x + "px " + (cache.yOrigin - t2.y) + "px";
        t1 = "";
      } else {
        t1 = !uncache && target.getAttribute("data-svg-origin"); //  Remember, to work around browser inconsistencies we always force SVG elements' transformOrigin to 0,0 and offset the translation accordingly.
      }

      _applySVGOrigin(target, t1 || origin, !!t1 || cache.originIsAbsolute, cache.smooth !== false, matrix);
    }

    xOrigin = cache.xOrigin || 0;
    yOrigin = cache.yOrigin || 0;

    if (matrix !== _identity2DMatrix) {
      a = matrix[0]; //a11

      b = matrix[1]; //a21

      c = matrix[2]; //a31

      d = matrix[3]; //a41

      x = a12 = matrix[4];
      y = a22 = matrix[5]; //2D matrix

      if (matrix.length === 6) {
        scaleX = Math.sqrt(a * a + b * b);
        scaleY = Math.sqrt(d * d + c * c);
        rotation = a || b ? _atan2(b, a) * _RAD2DEG : 0; //note: if scaleX is 0, we cannot accurately measure rotation. Same for skewX with a scaleY of 0. Therefore, we default to the previously recorded value (or zero if that doesn't exist).

        skewX = c || d ? _atan2(c, d) * _RAD2DEG + rotation : 0;
        skewX && (scaleY *= Math.abs(Math.cos(skewX * _DEG2RAD)));

        if (cache.svg) {
          x -= xOrigin - (xOrigin * a + yOrigin * c);
          y -= yOrigin - (xOrigin * b + yOrigin * d);
        } //3D matrix

      } else {
        a32 = matrix[6];
        a42 = matrix[7];
        a13 = matrix[8];
        a23 = matrix[9];
        a33 = matrix[10];
        a43 = matrix[11];
        x = matrix[12];
        y = matrix[13];
        z = matrix[14];
        angle = _atan2(a32, a33);
        rotationX = angle * _RAD2DEG; //rotationX

        if (angle) {
          cos = Math.cos(-angle);
          sin = Math.sin(-angle);
          t1 = a12 * cos + a13 * sin;
          t2 = a22 * cos + a23 * sin;
          t3 = a32 * cos + a33 * sin;
          a13 = a12 * -sin + a13 * cos;
          a23 = a22 * -sin + a23 * cos;
          a33 = a32 * -sin + a33 * cos;
          a43 = a42 * -sin + a43 * cos;
          a12 = t1;
          a22 = t2;
          a32 = t3;
        } //rotationY


        angle = _atan2(-c, a33);
        rotationY = angle * _RAD2DEG;

        if (angle) {
          cos = Math.cos(-angle);
          sin = Math.sin(-angle);
          t1 = a * cos - a13 * sin;
          t2 = b * cos - a23 * sin;
          t3 = c * cos - a33 * sin;
          a43 = d * sin + a43 * cos;
          a = t1;
          b = t2;
          c = t3;
        } //rotationZ


        angle = _atan2(b, a);
        rotation = angle * _RAD2DEG;

        if (angle) {
          cos = Math.cos(angle);
          sin = Math.sin(angle);
          t1 = a * cos + b * sin;
          t2 = a12 * cos + a22 * sin;
          b = b * cos - a * sin;
          a22 = a22 * cos - a12 * sin;
          a = t1;
          a12 = t2;
        }

        if (rotationX && Math.abs(rotationX) + Math.abs(rotation) > 359.9) {
          //when rotationY is set, it will often be parsed as 180 degrees different than it should be, and rotationX and rotation both being 180 (it looks the same), so we adjust for that here.
          rotationX = rotation = 0;
          rotationY = 180 - rotationY;
        }

        scaleX = _round(Math.sqrt(a * a + b * b + c * c));
        scaleY = _round(Math.sqrt(a22 * a22 + a32 * a32));
        angle = _atan2(a12, a22);
        skewX = Math.abs(angle) > 0.0002 ? angle * _RAD2DEG : 0;
        perspective = a43 ? 1 / (a43 < 0 ? -a43 : a43) : 0;
      }

      if (cache.svg) {
        //sense if there are CSS transforms applied on an SVG element in which case we must overwrite them when rendering. The transform attribute is more reliable cross-browser, but we can't just remove the CSS ones because they may be applied in a CSS rule somewhere (not just inline).
        t1 = target.getAttribute("transform");
        cache.forceCSS = target.setAttribute("transform", "") || !_isNullTransform(_getComputedProperty(target, _transformProp));
        t1 && target.setAttribute("transform", t1);
      }
    }

    if (Math.abs(skewX) > 90 && Math.abs(skewX) < 270) {
      if (invertedScaleX) {
        scaleX *= -1;
        skewX += rotation <= 0 ? 180 : -180;
        rotation += rotation <= 0 ? 180 : -180;
      } else {
        scaleY *= -1;
        skewX += skewX <= 0 ? 180 : -180;
      }
    }

    uncache = uncache || cache.uncache;
    cache.x = x - ((cache.xPercent = x && (!uncache && cache.xPercent || (Math.round(target.offsetWidth / 2) === Math.round(-x) ? -50 : 0))) ? target.offsetWidth * cache.xPercent / 100 : 0) + px;
    cache.y = y - ((cache.yPercent = y && (!uncache && cache.yPercent || (Math.round(target.offsetHeight / 2) === Math.round(-y) ? -50 : 0))) ? target.offsetHeight * cache.yPercent / 100 : 0) + px;
    cache.z = z + px;
    cache.scaleX = _round(scaleX);
    cache.scaleY = _round(scaleY);
    cache.rotation = _round(rotation) + deg;
    cache.rotationX = _round(rotationX) + deg;
    cache.rotationY = _round(rotationY) + deg;
    cache.skewX = skewX + deg;
    cache.skewY = skewY + deg;
    cache.transformPerspective = perspective + px;

    if (cache.zOrigin = parseFloat(origin.split(" ")[2]) || !uncache && cache.zOrigin || 0) {
      style[_transformOriginProp] = _firstTwoOnly(origin);
    }

    cache.xOffset = cache.yOffset = 0;
    cache.force3D = _config.force3D;
    cache.renderTransform = cache.svg ? _renderSVGTransforms : _supports3D ? _renderCSSTransforms : _renderNon3DTransforms;
    cache.uncache = 0;
    return cache;
  },
      _firstTwoOnly = function _firstTwoOnly(value) {
    return (value = value.split(" "))[0] + " " + value[1];
  },
      //for handling transformOrigin values, stripping out the 3rd dimension
  _addPxTranslate = function _addPxTranslate(target, start, value) {
    var unit = getUnit(start);
    return _round(parseFloat(start) + parseFloat(_convertToUnit(target, "x", value + "px", unit))) + unit;
  },
      _renderNon3DTransforms = function _renderNon3DTransforms(ratio, cache) {
    cache.z = "0px";
    cache.rotationY = cache.rotationX = "0deg";
    cache.force3D = 0;

    _renderCSSTransforms(ratio, cache);
  },
      _zeroDeg = "0deg",
      _zeroPx = "0px",
      _endParenthesis = ") ",
      _renderCSSTransforms = function _renderCSSTransforms(ratio, cache) {
    var _ref = cache || this,
        xPercent = _ref.xPercent,
        yPercent = _ref.yPercent,
        x = _ref.x,
        y = _ref.y,
        z = _ref.z,
        rotation = _ref.rotation,
        rotationY = _ref.rotationY,
        rotationX = _ref.rotationX,
        skewX = _ref.skewX,
        skewY = _ref.skewY,
        scaleX = _ref.scaleX,
        scaleY = _ref.scaleY,
        transformPerspective = _ref.transformPerspective,
        force3D = _ref.force3D,
        target = _ref.target,
        zOrigin = _ref.zOrigin,
        transforms = "",
        use3D = force3D === "auto" && ratio && ratio !== 1 || force3D === true; // Safari has a bug that causes it not to render 3D transform-origin values properly, so we force the z origin to 0, record it in the cache, and then do the math here to offset the translate values accordingly (basically do the 3D transform-origin part manually)


    if (zOrigin && (rotationX !== _zeroDeg || rotationY !== _zeroDeg)) {
      var angle = parseFloat(rotationY) * _DEG2RAD,
          a13 = Math.sin(angle),
          a33 = Math.cos(angle),
          cos;

      angle = parseFloat(rotationX) * _DEG2RAD;
      cos = Math.cos(angle);
      x = _addPxTranslate(target, x, a13 * cos * -zOrigin);
      y = _addPxTranslate(target, y, -Math.sin(angle) * -zOrigin);
      z = _addPxTranslate(target, z, a33 * cos * -zOrigin + zOrigin);
    }

    if (transformPerspective !== _zeroPx) {
      transforms += "perspective(" + transformPerspective + _endParenthesis;
    }

    if (xPercent || yPercent) {
      transforms += "translate(" + xPercent + "%, " + yPercent + "%) ";
    }

    if (use3D || x !== _zeroPx || y !== _zeroPx || z !== _zeroPx) {
      transforms += z !== _zeroPx || use3D ? "translate3d(" + x + ", " + y + ", " + z + ") " : "translate(" + x + ", " + y + _endParenthesis;
    }

    if (rotation !== _zeroDeg) {
      transforms += "rotate(" + rotation + _endParenthesis;
    }

    if (rotationY !== _zeroDeg) {
      transforms += "rotateY(" + rotationY + _endParenthesis;
    }

    if (rotationX !== _zeroDeg) {
      transforms += "rotateX(" + rotationX + _endParenthesis;
    }

    if (skewX !== _zeroDeg || skewY !== _zeroDeg) {
      transforms += "skew(" + skewX + ", " + skewY + _endParenthesis;
    }

    if (scaleX !== 1 || scaleY !== 1) {
      transforms += "scale(" + scaleX + ", " + scaleY + _endParenthesis;
    }

    target.style[_transformProp] = transforms || "translate(0, 0)";
  },
      _renderSVGTransforms = function _renderSVGTransforms(ratio, cache) {
    var _ref2 = cache || this,
        xPercent = _ref2.xPercent,
        yPercent = _ref2.yPercent,
        x = _ref2.x,
        y = _ref2.y,
        rotation = _ref2.rotation,
        skewX = _ref2.skewX,
        skewY = _ref2.skewY,
        scaleX = _ref2.scaleX,
        scaleY = _ref2.scaleY,
        target = _ref2.target,
        xOrigin = _ref2.xOrigin,
        yOrigin = _ref2.yOrigin,
        xOffset = _ref2.xOffset,
        yOffset = _ref2.yOffset,
        forceCSS = _ref2.forceCSS,
        tx = parseFloat(x),
        ty = parseFloat(y),
        a11,
        a21,
        a12,
        a22,
        temp;

    rotation = parseFloat(rotation);
    skewX = parseFloat(skewX);
    skewY = parseFloat(skewY);

    if (skewY) {
      //for performance reasons, we combine all skewing into the skewX and rotation values. Remember, a skewY of 10 degrees looks the same as a rotation of 10 degrees plus a skewX of 10 degrees.
      skewY = parseFloat(skewY);
      skewX += skewY;
      rotation += skewY;
    }

    if (rotation || skewX) {
      rotation *= _DEG2RAD;
      skewX *= _DEG2RAD;
      a11 = Math.cos(rotation) * scaleX;
      a21 = Math.sin(rotation) * scaleX;
      a12 = Math.sin(rotation - skewX) * -scaleY;
      a22 = Math.cos(rotation - skewX) * scaleY;

      if (skewX) {
        skewY *= _DEG2RAD;
        temp = Math.tan(skewX - skewY);
        temp = Math.sqrt(1 + temp * temp);
        a12 *= temp;
        a22 *= temp;

        if (skewY) {
          temp = Math.tan(skewY);
          temp = Math.sqrt(1 + temp * temp);
          a11 *= temp;
          a21 *= temp;
        }
      }

      a11 = _round(a11);
      a21 = _round(a21);
      a12 = _round(a12);
      a22 = _round(a22);
    } else {
      a11 = scaleX;
      a22 = scaleY;
      a21 = a12 = 0;
    }

    if (tx && !~(x + "").indexOf("px") || ty && !~(y + "").indexOf("px")) {
      tx = _convertToUnit(target, "x", x, "px");
      ty = _convertToUnit(target, "y", y, "px");
    }

    if (xOrigin || yOrigin || xOffset || yOffset) {
      tx = _round(tx + xOrigin - (xOrigin * a11 + yOrigin * a12) + xOffset);
      ty = _round(ty + yOrigin - (xOrigin * a21 + yOrigin * a22) + yOffset);
    }

    if (xPercent || yPercent) {
      //The SVG spec doesn't support percentage-based translation in the "transform" attribute, so we merge it into the translation to simulate it.
      temp = target.getBBox();
      tx = _round(tx + xPercent / 100 * temp.width);
      ty = _round(ty + yPercent / 100 * temp.height);
    }

    temp = "matrix(" + a11 + "," + a21 + "," + a12 + "," + a22 + "," + tx + "," + ty + ")";
    target.setAttribute("transform", temp);
    forceCSS && (target.style[_transformProp] = temp); //some browsers prioritize CSS transforms over the transform attribute. When we sense that the user has CSS transforms applied, we must overwrite them this way (otherwise some browser simply won't render the transform attribute changes!)
  },
      _addRotationalPropTween = function _addRotationalPropTween(plugin, target, property, startNum, endValue) {
    var cap = 360,
        isString = _isString(endValue),
        endNum = parseFloat(endValue) * (isString && ~endValue.indexOf("rad") ? _RAD2DEG : 1),
        change = endNum - startNum,
        finalValue = startNum + change + "deg",
        direction,
        pt;

    if (isString) {
      direction = endValue.split("_")[1];

      if (direction === "short") {
        change %= cap;

        if (change !== change % (cap / 2)) {
          change += change < 0 ? cap : -cap;
        }
      }

      if (direction === "cw" && change < 0) {
        change = (change + cap * _bigNum) % cap - ~~(change / cap) * cap;
      } else if (direction === "ccw" && change > 0) {
        change = (change - cap * _bigNum) % cap - ~~(change / cap) * cap;
      }
    }

    plugin._pt = pt = new PropTween(plugin._pt, target, property, startNum, change, _renderPropWithEnd);
    pt.e = finalValue;
    pt.u = "deg";

    plugin._props.push(property);

    return pt;
  },
      _assign = function _assign(target, source) {
    // Internet Explorer doesn't have Object.assign(), so we recreate it here.
    for (var p in source) {
      target[p] = source[p];
    }

    return target;
  },
      _addRawTransformPTs = function _addRawTransformPTs(plugin, transforms, target) {
    //for handling cases where someone passes in a whole transform string, like transform: "scale(2, 3) rotate(20deg) translateY(30em)"
    var startCache = _assign({}, target._gsap),
        exclude = "perspective,force3D,transformOrigin,svgOrigin",
        style = target.style,
        endCache,
        p,
        startValue,
        endValue,
        startNum,
        endNum,
        startUnit,
        endUnit;

    if (startCache.svg) {
      startValue = target.getAttribute("transform");
      target.setAttribute("transform", "");
      style[_transformProp] = transforms;
      endCache = _parseTransform(target, 1);

      _removeProperty(target, _transformProp);

      target.setAttribute("transform", startValue);
    } else {
      startValue = getComputedStyle(target)[_transformProp];
      style[_transformProp] = transforms;
      endCache = _parseTransform(target, 1);
      style[_transformProp] = startValue;
    }

    for (p in _transformProps) {
      startValue = startCache[p];
      endValue = endCache[p];

      if (startValue !== endValue && exclude.indexOf(p) < 0) {
        //tweening to no perspective gives very unintuitive results - just keep the same perspective in that case.
        startUnit = getUnit(startValue);
        endUnit = getUnit(endValue);
        startNum = startUnit !== endUnit ? _convertToUnit(target, p, startValue, endUnit) : parseFloat(startValue);
        endNum = parseFloat(endValue);
        plugin._pt = new PropTween(plugin._pt, endCache, p, startNum, endNum - startNum, _renderCSSProp);
        plugin._pt.u = endUnit || 0;

        plugin._props.push(p);
      }
    }

    _assign(endCache, startCache);
  }; // handle splitting apart padding, margin, borderWidth, and borderRadius into their 4 components. Firefox, for example, won't report borderRadius correctly - it will only do borderTopLeftRadius and the other corners. We also want to handle paddingTop, marginLeft, borderRightWidth, etc.


  _forEachName("padding,margin,Width,Radius", function (name, index) {
    var t = "Top",
        r = "Right",
        b = "Bottom",
        l = "Left",
        props = (index < 3 ? [t, r, b, l] : [t + l, t + r, b + r, b + l]).map(function (side) {
      return index < 2 ? name + side : "border" + side + name;
    });

    _specialProps[index > 1 ? "border" + name : name] = function (plugin, target, property, endValue, tween) {
      var a, vars;

      if (arguments.length < 4) {
        // getter, passed target, property, and unit (from _get())
        a = props.map(function (prop) {
          return _get(plugin, prop, property);
        });
        vars = a.join(" ");
        return vars.split(a[0]).length === 5 ? a[0] : vars;
      }

      a = (endValue + "").split(" ");
      vars = {};
      props.forEach(function (prop, i) {
        return vars[prop] = a[i] = a[i] || a[(i - 1) / 2 | 0];
      });
      plugin.init(target, vars, tween);
    };
  });

  var CSSPlugin = {
    name: "css",
    register: _initCore,
    targetTest: function targetTest(target) {
      return target.style && target.nodeType;
    },
    init: function init(target, vars, tween, index, targets) {
      var props = this._props,
          style = target.style,
          startAt = tween.vars.startAt,
          startValue,
          endValue,
          endNum,
          startNum,
          type,
          specialProp,
          p,
          startUnit,
          endUnit,
          relative,
          isTransformRelated,
          transformPropTween,
          cache,
          smooth,
          hasPriority,
          inlineProps;
      _pluginInitted || _initCore(); // we may call init() multiple times on the same plugin instance, like when adding special properties, so make sure we don't overwrite the revert data or inlineProps

      this.styles = this.styles || _getStyleSaver(target);
      inlineProps = this.styles.props;
      this.tween = tween;

      for (p in vars) {
        if (p === "autoRound") {
          continue;
        }

        endValue = vars[p];

        if (_plugins[p] && _checkPlugin(p, vars, tween, index, target, targets)) {
          // plugins
          continue;
        }

        type = typeof endValue;
        specialProp = _specialProps[p];

        if (type === "function") {
          endValue = endValue.call(tween, index, target, targets);
          type = typeof endValue;
        }

        if (type === "string" && ~endValue.indexOf("random(")) {
          endValue = _replaceRandom(endValue);
        }

        if (specialProp) {
          specialProp(this, target, p, endValue, tween) && (hasPriority = 1);
        } else if (p.substr(0, 2) === "--") {
          //CSS variable
          startValue = (getComputedStyle(target).getPropertyValue(p) + "").trim();
          endValue += "";
          _colorExp.lastIndex = 0;

          if (!_colorExp.test(startValue)) {
            // colors don't have units
            startUnit = getUnit(startValue);
            endUnit = getUnit(endValue);
          }

          endUnit ? startUnit !== endUnit && (startValue = _convertToUnit(target, p, startValue, endUnit) + endUnit) : startUnit && (endValue += startUnit);
          this.add(style, "setProperty", startValue, endValue, index, targets, 0, 0, p);
          props.push(p);
          inlineProps.push(p, 0, style[p]);
        } else if (type !== "undefined") {
          if (startAt && p in startAt) {
            // in case someone hard-codes a complex value as the start, like top: "calc(2vh / 2)". Without this, it'd use the computed value (always in px)
            startValue = typeof startAt[p] === "function" ? startAt[p].call(tween, index, target, targets) : startAt[p];
            _isString(startValue) && ~startValue.indexOf("random(") && (startValue = _replaceRandom(startValue));
            getUnit(startValue + "") || startValue === "auto" || (startValue += _config.units[p] || getUnit(_get(target, p)) || ""); // for cases when someone passes in a unitless value like {x: 100}; if we try setting translate(100, 0px) it won't work.

            (startValue + "").charAt(1) === "=" && (startValue = _get(target, p)); // can't work with relative values
          } else {
            startValue = _get(target, p);
          }

          startNum = parseFloat(startValue);
          relative = type === "string" && endValue.charAt(1) === "=" && endValue.substr(0, 2);
          relative && (endValue = endValue.substr(2));
          endNum = parseFloat(endValue);

          if (p in _propertyAliases) {
            if (p === "autoAlpha") {
              //special case where we control the visibility along with opacity. We still allow the opacity value to pass through and get tweened.
              if (startNum === 1 && _get(target, "visibility") === "hidden" && endNum) {
                //if visibility is initially set to "hidden", we should interpret that as intent to make opacity 0 (a convenience)
                startNum = 0;
              }

              inlineProps.push("visibility", 0, style.visibility);

              _addNonTweeningPT(this, style, "visibility", startNum ? "inherit" : "hidden", endNum ? "inherit" : "hidden", !endNum);
            }

            if (p !== "scale" && p !== "transform") {
              p = _propertyAliases[p];
              ~p.indexOf(",") && (p = p.split(",")[0]);
            }
          }

          isTransformRelated = p in _transformProps; //--- TRANSFORM-RELATED ---

          if (isTransformRelated) {
            this.styles.save(p);

            if (!transformPropTween) {
              cache = target._gsap;
              cache.renderTransform && !vars.parseTransform || _parseTransform(target, vars.parseTransform); // if, for example, gsap.set(... {transform:"translateX(50vw)"}), the _get() call doesn't parse the transform, thus cache.renderTransform won't be set yet so force the parsing of the transform here.

              smooth = vars.smoothOrigin !== false && cache.smooth;
              transformPropTween = this._pt = new PropTween(this._pt, style, _transformProp, 0, 1, cache.renderTransform, cache, 0, -1); //the first time through, create the rendering PropTween so that it runs LAST (in the linked list, we keep adding to the beginning)

              transformPropTween.dep = 1; //flag it as dependent so that if things get killed/overwritten and this is the only PropTween left, we can safely kill the whole tween.
            }

            if (p === "scale") {
              this._pt = new PropTween(this._pt, cache, "scaleY", cache.scaleY, (relative ? _parseRelative(cache.scaleY, relative + endNum) : endNum) - cache.scaleY || 0, _renderCSSProp);
              this._pt.u = 0;
              props.push("scaleY", p);
              p += "X";
            } else if (p === "transformOrigin") {
              inlineProps.push(_transformOriginProp, 0, style[_transformOriginProp]);
              endValue = _convertKeywordsToPercentages(endValue); //in case something like "left top" or "bottom right" is passed in. Convert to percentages.

              if (cache.svg) {
                _applySVGOrigin(target, endValue, 0, smooth, 0, this);
              } else {
                endUnit = parseFloat(endValue.split(" ")[2]) || 0; //handle the zOrigin separately!

                endUnit !== cache.zOrigin && _addNonTweeningPT(this, cache, "zOrigin", cache.zOrigin, endUnit);

                _addNonTweeningPT(this, style, p, _firstTwoOnly(startValue), _firstTwoOnly(endValue));
              }

              continue;
            } else if (p === "svgOrigin") {
              _applySVGOrigin(target, endValue, 1, smooth, 0, this);

              continue;
            } else if (p in _rotationalProperties) {
              _addRotationalPropTween(this, cache, p, startNum, relative ? _parseRelative(startNum, relative + endValue) : endValue);

              continue;
            } else if (p === "smoothOrigin") {
              _addNonTweeningPT(this, cache, "smooth", cache.smooth, endValue);

              continue;
            } else if (p === "force3D") {
              cache[p] = endValue;
              continue;
            } else if (p === "transform") {
              _addRawTransformPTs(this, endValue, target);

              continue;
            }
          } else if (!(p in style)) {
            p = _checkPropPrefix(p) || p;
          }

          if (isTransformRelated || (endNum || endNum === 0) && (startNum || startNum === 0) && !_complexExp.test(endValue) && p in style) {
            startUnit = (startValue + "").substr((startNum + "").length);
            endNum || (endNum = 0); // protect against NaN

            endUnit = getUnit(endValue) || (p in _config.units ? _config.units[p] : startUnit);
            startUnit !== endUnit && (startNum = _convertToUnit(target, p, startValue, endUnit));
            this._pt = new PropTween(this._pt, isTransformRelated ? cache : style, p, startNum, (relative ? _parseRelative(startNum, relative + endNum) : endNum) - startNum, !isTransformRelated && (endUnit === "px" || p === "zIndex") && vars.autoRound !== false ? _renderRoundedCSSProp : _renderCSSProp);
            this._pt.u = endUnit || 0;

            if (startUnit !== endUnit && endUnit !== "%") {
              //when the tween goes all the way back to the beginning, we need to revert it to the OLD/ORIGINAL value (with those units). We record that as a "b" (beginning) property and point to a render method that handles that. (performance optimization)
              this._pt.b = startValue;
              this._pt.r = _renderCSSPropWithBeginning;
            }
          } else if (!(p in style)) {
            if (p in target) {
              //maybe it's not a style - it could be a property added directly to an element in which case we'll try to animate that.
              this.add(target, p, startValue || target[p], relative ? relative + endValue : endValue, index, targets);
            } else if (p !== "parseTransform") {
              _missingPlugin(p, endValue);

              continue;
            }
          } else {
            _tweenComplexCSSString.call(this, target, p, startValue, relative ? relative + endValue : endValue);
          }

          isTransformRelated || (p in style ? inlineProps.push(p, 0, style[p]) : typeof target[p] === "function" ? inlineProps.push(p, 2, target[p]()) : inlineProps.push(p, 1, startValue || target[p]));
          props.push(p);
        }
      }

      hasPriority && _sortPropTweensByPriority(this);
    },
    render: function render(ratio, data) {
      if (data.tween._time || !_reverting()) {
        var pt = data._pt;

        while (pt) {
          pt.r(ratio, pt.d);
          pt = pt._next;
        }
      } else {
        data.styles.revert();
      }
    },
    get: _get,
    aliases: _propertyAliases,
    getSetter: function getSetter(target, property, plugin) {
      //returns a setter function that accepts target, property, value and applies it accordingly. Remember, properties like "x" aren't as simple as target.style.property = value because they've got to be applied to a proxy object and then merged into a transform string in a renderer.
      var p = _propertyAliases[property];
      p && p.indexOf(",") < 0 && (property = p);
      return property in _transformProps && property !== _transformOriginProp && (target._gsap.x || _get(target, "x")) ? plugin && _recentSetterPlugin === plugin ? property === "scale" ? _setterScale : _setterTransform : (_recentSetterPlugin = plugin || {}) && (property === "scale" ? _setterScaleWithRender : _setterTransformWithRender) : target.style && !_isUndefined(target.style[property]) ? _setterCSSStyle : ~property.indexOf("-") ? _setterCSSProp : _getSetter(target, property);
    },
    core: {
      _removeProperty: _removeProperty,
      _getMatrix: _getMatrix
    }
  };
  gsap.utils.checkPrefix = _checkPropPrefix;
  gsap.core.getStyleSaver = _getStyleSaver;

  (function (positionAndScale, rotation, others, aliases) {
    var all = _forEachName(positionAndScale + "," + rotation + "," + others, function (name) {
      _transformProps[name] = 1;
    });

    _forEachName(rotation, function (name) {
      _config.units[name] = "deg";
      _rotationalProperties[name] = 1;
    });

    _propertyAliases[all[13]] = positionAndScale + "," + rotation;

    _forEachName(aliases, function (name) {
      var split = name.split(":");
      _propertyAliases[split[1]] = all[split[0]];
    });
  })("x,y,z,scale,scaleX,scaleY,xPercent,yPercent", "rotation,rotationX,rotationY,skewX,skewY", "transform,transformOrigin,svgOrigin,force3D,smoothOrigin,transformPerspective", "0:translateX,1:translateY,2:translateZ,8:rotate,8:rotationZ,8:rotateZ,9:rotateX,10:rotateY");

  _forEachName("x,y,z,top,right,bottom,left,width,height,fontSize,padding,margin,perspective", function (name) {
    _config.units[name] = "px";
  });

  gsap.registerPlugin(CSSPlugin);

  var gsapWithCSS = gsap.registerPlugin(CSSPlugin) || gsap;
      // to protect from tree shaking
  gsapWithCSS.core.Tween;

  var AnimationCtrl = function AnimationCtrl2(_ref) {
    var elementInside = _ref.elementInside, _ref$animTime = _ref.animTime, animTime = _ref$animTime === void 0 ? 2 : _ref$animTime, _ref$waitHide = _ref.waitHide, waitHide = _ref$waitHide === void 0 ? 2 : _ref$waitHide, _ref$startVal = _ref.startVal, startVal = _ref$startVal === void 0 ? 0 : _ref$startVal, _ref$endVal = _ref.endVal, endVal = _ref$endVal === void 0 ? 1 : _ref$endVal, _ref$needStart = _ref.needStart, needStart = _ref$needStart === void 0 ? false : _ref$needStart, setNeedShow = _ref.setNeedShow, finishCb = _ref.finishCb, data = _ref.data, dataId = _ref.dataId, _ref$needHide = _ref.needHide, needHide = _ref$needHide === void 0 ? true : _ref$needHide, classDiv = _ref.classDiv;
    var _useState = d(false), _useState2 = _slicedToArray(_useState, 2); _useState2[0]; var setVisible = _useState2[1];
    var _useState3 = d(needStart), _useState4 = _slicedToArray(_useState3, 2), inNeedStart = _useState4[0], setNeedStart = _useState4[1];
    var _useState5 = d(needStart), _useState6 = _slicedToArray(_useState5, 2); _useState6[0]; _useState6[1];
    var _useState7 = d(dataId), _useState8 = _slicedToArray(_useState7, 2), lastDataId = _useState8[0], setLastDataId = _useState8[1];
    var _useState9 = d(null), _useState10 = _slicedToArray(_useState9, 2), curAnim = _useState10[0], setCurAnim = _useState10[1];
    var nodeRef = A(null);
    var hide = function hide2() {
      setCurAnim(fadeOutAnim());
    };
    var fadeOutAnim = function fadeOutAnim2() {
      return gsapWithCSS.fromTo(nodeRef.current, {
        opacity: endVal
      }, {
        duration: animTime * 0.5,
        delay: waitHide,
        opacity: startVal,
        onComplete: function onComplete() {
          setVisible(false);
          setNeedShow && setNeedShow(false);
          finishCb && finishCb(data);
        }
      });
    };
    var fadeInAnim = function fadeInAnim2() {
      return gsapWithCSS.fromTo(nodeRef.current, {
        opacity: startVal
      }, {
        duration: animTime * 0.5,
        opacity: endVal,
        onComplete: function onComplete() {
          setVisible(true);
          if (needHide)
            hide();
        }
      });
    };
    var appear = function appear2() {
      if (curAnim)
        curAnim.progress(1).kill();
      setNeedStart(false);
      needStart = false;
      setCurAnim(fadeInAnim());
    };
    _(function() {
      if (dataId !== lastDataId) {
        setNeedStart(true);
        setLastDataId(dataId);
      }
      if (inNeedStart)
        appear();
    });
    return _$1("div", {
      "class": classDiv,
      ref: nodeRef
    }, elementInside);
  };

  function clog() {
  }

  var NotificationMngr = function NotificationMngr2(_ref) {
    var type = _ref.type, notificationsAr = _ref.notificationsAr, updateNotificationAr = _ref.updateNotificationAr; _ref.arrayData; _ref.removeElem; var _ref$maxLines = _ref.maxLines, maxLines = _ref$maxLines === void 0 ? 3 : _ref$maxLines, _ref$waitHide = _ref.waitHide, waitHide = _ref$waitHide === void 0 ? 3 : _ref$waitHide, _ref$animTime = _ref.animTime, animTime = _ref$animTime === void 0 ? 2 : _ref$animTime; _ref.replaceCurrent; _ref.setNeedShow; var _ref$classDiv = _ref.classDiv, classDiv = _ref$classDiv === void 0 ? "" : _ref$classDiv;
    var _useContext = x(LanguageContext); _useContext.lng;
    var removeNotificationFromList = function removeNotificationFromList2(notificationId) {
      var remainingTasks = window.uiApi.notificationsToShow[type].filter(function(elem) {
        return notificationId !== elem.id;
      });
      window.uiApi.notificationsToShow[type] = remainingTasks;
      updateNotificationAr(remainingTasks);
    };
    var getLine = function getLine2(line, i) {
      if (i >= maxLines) {
        return null;
      }
      return _$1(AnimationCtrl, {
        elementInside: line.drawElement(),
        data: line,
        dataId: line.id,
        classDiv: "inGame animation",
        needHide: true,
        needStart: true,
        animTime,
        waitHide,
        finishCb: function finishCb(line2) {
          clog("Finish line", line2.id);
          removeNotificationFromList(line2.id);
        }
      });
    };
    return _$1("div", {
      "class": classDiv + " notifMngr"
    }, notificationsAr.map(function(line, i) {
      return getLine(line, i);
    }));
  };

  var ElementsLine = function ElementsLine2(_ref) {
    _ref.widthScreen; var icon1 = _ref.icon1, text1 = _ref.text1, btwIcon = _ref.btwIcon, nameOfElement = _ref.nameOfElement, icon2 = _ref.icon2, text2 = _ref.text2, _ref$justifyContent = _ref.justifyContent, justifyContent = _ref$justifyContent === void 0 ? "flex-start" : _ref$justifyContent, _ref$classDiv = _ref.classDiv, classDiv = _ref$classDiv === void 0 ? "backPlate" : _ref$classDiv, _ref$addedTopMargin = _ref.addedTopMargin, addedTopMargin = _ref$addedTopMargin === void 0 ? 0 : _ref$addedTopMargin, _ref$iconSize = _ref.iconSize, iconSize = _ref$iconSize === void 0 ? 25 : _ref$iconSize, _ref$marginLeftAdd = _ref.marginLeftAdd, marginLeftAdd = _ref$marginLeftAdd === void 0 ? 10 : _ref$marginLeftAdd, _ref$fontClass = _ref.fontClass, fontClass = _ref$fontClass === void 0 ? "" : _ref$fontClass; _ref.minWidthText; var _ref$elemHeight = _ref.elemHeight, elemHeight = _ref$elemHeight === void 0 ? 40 : _ref$elemHeight, _ref$normFont = _ref.normFont, normFont = _ref$normFont === void 0 ? 15 : _ref$normFont; _ref.widthPrc; _ref.widthMin; _ref.widthMax;
    var _useContext = x(LanguageContext); _useContext.lng;
    y(function() {
    }, []);
    var elemWidth = "100%";
    var iconWidth = iconSize;
    var padding = 5;
    var sidePadding = 10;
    var fontStyle = {
      textAlign: "center",
      marginTop: "".concat(-(normFont - elemHeight) * 0.5, "px"),
      lineHeight: "100%",
      paddingRight: "5px"
    };
    var textSideRight = {
      position: "relative"
    };
    var elementStyle = {
      color: "white",
      fontSize: "".concat(normFont, "px"),
      display: "flex",
      justifyContent,
      height: "".concat(elemHeight, "px"),
      width: "".concat(elemWidth ),
      margin: "".concat(sidePadding, "px"),
      marginTop: "".concat(addedTopMargin, "px"),
      marginLeft: "".concat(marginLeftAdd, "px")
    };
    var iconStyleRight = {
      position: "relative",
      padding: padding + "px",
      display: "flex",
      alignItems: "center",
      alignContent: "center"
    };
    return _$1("div", {
      id: nameOfElement,
      style: elementStyle,
      "class": classDiv + " inGame "
    }, icon1 && _$1("div", {
      style: iconStyleRight,
      "class": " zeroPos noStretch"
    }, _$1("img", {
      width: iconWidth,
      height: iconWidth,
      src: "assets" + "/images/" + icon1 + ".png"
    })), _$1("div", {
      style: textSideRight,
      "class": fontClass
    }, _$1("p", {
      style: fontStyle
    }, text1)), btwIcon && _$1("div", {
      style: iconStyleRight,
      "class": " zeroPos noStretch"
    }, _$1("img", {
      width: iconWidth,
      height: iconWidth,
      src: "assets" + "/images/" + btwIcon + ".png"
    })), icon2 && _$1("div", {
      style: iconStyleRight,
      "class": " zeroPos noStretch"
    }, _$1("img", {
      width: iconWidth,
      height: iconWidth,
      src: "assets" + "/images/" + icon2 + ".png"
    })), text2 && _$1("div", {
      style: textSideRight,
      "class": fontClass
    }, _$1("p", {
      style: fontStyle
    }, text2)));
  };

  var IconPopUp = function IconPopUp2(_ref) {
    _ref.widthScreen; var icon = _ref.icon, _ref$img = _ref.img2, img2 = _ref$img === void 0 ? "aim" : _ref$img, nameOfElement = _ref.nameOfElement, classDiv = _ref.classDiv, _ref$addedTopMargin = _ref.addedTopMargin, addedTopMargin = _ref$addedTopMargin === void 0 ? 10 : _ref$addedTopMargin; _ref.value; _ref.valueMax; var _ref$iconSize = _ref.iconSize, iconSize = _ref$iconSize === void 0 ? 50 : _ref$iconSize; _ref.marginLeftAdd; _ref.minWidthText; _ref.elemHeight; _ref.normFont; _ref.sidePadding; _ref.widthPrc; _ref.widthMin; _ref.widthMax;
    var _useContext = x(LanguageContext); _useContext.lng;
    y(function() {
    });
    var iconWidth = iconSize;
    var padding = 5;
    var elementStyle = {
      display: "flex",
      justifyContent: "flex-start",
      height: "100%",
      width: "100%",
      marginTop: "".concat(addedTopMargin, "px")
    };
    var iconStyleRight = {
      position: "relative",
      padding: padding + "px"
    };
    var styleTopIcon = {
      position: "absolute",
      transform: "translate(" + "-".concat(iconWidth * 1.5, "px,-").concat(iconWidth * 0.5, "px") + ")"
    };
    return _$1("div", {
      id: nameOfElement,
      style: elementStyle,
      "class": classDiv + " inGame"
    }, _$1("div", {
      id: nameOfElement + "IconBack",
      style: iconStyleRight,
      "class": " zeroPos noStretch"
    }, _$1("img", {
      id: nameOfElement + "Icon",
      width: iconWidth,
      height: iconWidth,
      src: "assets" + "/images/" + icon + ".png"
    }), _$1("img", {
      style: styleTopIcon,
      width: iconWidth * 2,
      height: iconWidth * 2,
      src: "assets" + "/images/" + img2 + ".png"
    })));
  };

  var PrcBar = function PrcBar2(_ref) {
    var widthScreen = _ref.widthScreen, heightScreen = _ref.heightScreen, curPrc = _ref.curPrc, newAm = _ref.newAm, updateShowPrc = _ref.updateShowPrc, maxAm = _ref.maxAm, _ref$maxWidth = _ref.maxWidth, maxWidth = _ref$maxWidth === void 0 ? 350 : _ref$maxWidth, _ref$minWidth = _ref.minWidth, minWidth = _ref$minWidth === void 0 ? 150 : _ref$minWidth, _ref$widthPrc = _ref.widthPrc, widthPrc = _ref$widthPrc === void 0 ? 0.3 : _ref$widthPrc, _ref$barCol = _ref.barCol, barCol = _ref$barCol === void 0 ? "green" : _ref$barCol, _ref$backCol = _ref.backCol, backCol = _ref$backCol === void 0 ? "darkGreen" : _ref$backCol, _ref$barHeight = _ref.barHeight, barHeight = _ref$barHeight === void 0 ? 40 : _ref$barHeight, _ref$name = _ref.name, name = _ref$name === void 0 ? "prcBar" : _ref$name, _ref$classes = _ref.classes, classes = _ref$classes === void 0 ? "" : _ref$classes;
    var _useState = d(curPrc), _useState2 = _slicedToArray(_useState, 2), prc = _useState2[0], setPrc = _useState2[1];
    var _useState3 = d(false), _useState4 = _slicedToArray(_useState3, 2); _useState4[0]; _useState4[1];
    var _useState5 = d(false), _useState6 = _slicedToArray(_useState5, 2); _useState6[0]; _useState6[1];
    var _useContext = x(LanguageContext); _useContext.lng;
    var resultTextNew = newAm;
    var resultTextShow = " " + resultTextNew + "%";
    var tweenHp = function tweenHp2() {
      if (newAm === curPrc)
        return;
      var newPrc = newAm / maxAm * 100;
      newPrc = newPrc > 100 ? 100 : newPrc;
      if (!newPrc)
        newPrc = 0;
      setPrc(newPrc);
      updateShowPrc(newPrc);
    };
    y(function() {
      tweenHp();
    });
    var padding = 5;
    var textSize = 25;
    if (heightScreen > widthScreen) {
      textSize = 18;
      maxWidth = 180;
      minWidth = 80;
      widthPrc = 0.35;
      barHeight = 25;
    }
    var maxBarWidth = maxWidth > widthScreen * widthPrc ? widthScreen * widthPrc : maxWidth;
    var barWidth = maxBarWidth > minWidth ? maxBarWidth : minWidth;
    var textSide = {
      fontSize: "".concat(textSize, "px"),
      color: "#000000a3"
    };
    var textInnerStyle = {
      lineHeight: "".concat(barHeight, "px"),
      margin: "0px",
      marginLeft: "10px"
    };
    var backBarsStyle = {
      width: "100%"
    };
    var emptyBar = {
      position: "absolute",
      width: "100%",
      height: "".concat(barHeight, "px"),
      backgroundColor: "#5454548a",
      borderRadius: "0px ".concat(Math.floor(barHeight * 0.4), "px ").concat(Math.floor(barHeight * 0.4), "px 0px"),
      boxShadow: "0px 6px 0px 0px #5454548a"
    };
    var fullBar = {
      position: "absolute",
      height: "".concat(barHeight, "px"),
      backgroundColor: barCol,
      width: "".concat(prc, "%"),
      borderRadius: "0px ".concat(Math.floor(barHeight * 0.4), "px ").concat(Math.floor(barHeight * 0.4), "px 0px"),
      boxShadow: "0px 6px 0px 0px " + backCol
    };
    var barStyle = {
      display: "flex",
      justifyContent: "center",
      height: "".concat(barHeight + padding * 2, "px"),
      width: "".concat(barWidth + padding * 2, "px"),
      minWidth: "".concat(maxBarWidth, "px")
    };
    return _$1("div", {
      id: name,
      style: barStyle,
      "class": classes + " inGame"
    }, _$1("div", {
      style: backBarsStyle
    }, _$1("div", {
      "class": "emptyBar",
      style: emptyBar
    }), _$1("div", {
      "class": "fullBar",
      style: fullBar
    })), _$1("div", {
      id: name + "Text",
      style: textSide,
      "class": "zeroPos"
    }, _$1("p", {
      style: textInnerStyle
    }, resultTextShow)));
  };

  var InGameLbBasic = function InGameLbBasic2(_ref) {
    _ref.skins; var widthScreen = _ref.widthScreen, heightScreen = _ref.heightScreen, nameOfElement = _ref.nameOfElement, classDiv = _ref.classDiv, _ref$lineAm = _ref.lineAm, lineAm = _ref$lineAm === void 0 ? 5 : _ref$lineAm, skinColsInfo = _ref.skinColsInfo, _ref$widthPrc = _ref.widthPrc, widthPrc = _ref$widthPrc === void 0 ? 0.44 : _ref$widthPrc, _ref$widthMin = _ref.widthMin, widthMin = _ref$widthMin === void 0 ? 240 : _ref$widthMin, _ref$widthMax = _ref.widthMax, widthMax = _ref$widthMax === void 0 ? 300 : _ref$widthMax, _ref$offsetX = _ref.offsetX, offsetX = _ref$offsetX === void 0 ? 6 : _ref$offsetX, dataAr = _ref.dataAr, _ref$typeSort = _ref.typeSort, typeSort = _ref$typeSort === void 0 ? "score" : _ref$typeSort;
    var lineHeight = 35;
    var lineFontSize = 16;
    if (heightScreen > widthScreen) {
      widthPrc = 0.5;
      lineHeight = 25;
      lineFontSize = 15;
    }
    var maxNameLength = 11;
    var maxElemWidth = widthMax > widthScreen * widthPrc ? widthScreen * widthPrc : widthMax;
    var elemWidth = maxElemWidth > widthMin ? maxElemWidth : widthMin;
    var style = {
      marginRight: "-".concat(offsetX * lineAm, "px"),
      width: "".concat(elemWidth, "px")
    };
    var getColor = function getColor2(code) {
      return skinColsInfo[code];
    };
    return _$1("div", {
      id: nameOfElement,
      style,
      "class": classDiv + " inGame"
    }, dataAr.map(function(userData, i) {
      return _$1(LbLine$1, {
        nameOfElement,
        color: getColor(userData.code).main,
        textCol: getColor(userData.code).lbTextColor,
        backCol: getColor(userData.code).back,
        icon: null,
        place: userData.place + 1,
        widthScreen,
        elemHeight: lineHeight,
        normFont: lineFontSize,
        classDiv,
        marginRightAdd: "-25",
        marginLeftAdd: i < 5 ? offsetX * i : offsetX * 10,
        addedTopMargin: i < 5 ? 0 : 20,
        name: userData.nickName.length > maxNameLength ? userData.nickName.substring(0, maxNameLength) + ".." : userData.nickName,
        amount: userData[typeSort].toFixed(2)
      });
    }));
  };
  var LbLine$1 = function LbLine2(_ref2) {
    var widthScreen = _ref2.widthScreen, nameOfElement = _ref2.nameOfElement, classDiv = _ref2.classDiv, place = _ref2.place, name = _ref2.name, amount = _ref2.amount, _ref2$color = _ref2.color, color = _ref2$color === void 0 ? "#7b6f6fbf" : _ref2$color, _ref2$textCol = _ref2.textCol, textCol = _ref2$textCol === void 0 ? "#ffffff" : _ref2$textCol, _ref2$backCol = _ref2.backCol, backCol = _ref2$backCol === void 0 ? "#000000" : _ref2$backCol, _ref2$addedTopMargin = _ref2.addedTopMargin, addedTopMargin = _ref2$addedTopMargin === void 0 ? 0 : _ref2$addedTopMargin; _ref2.icon; _ref2.iconSize; var _ref2$marginLeftAdd = _ref2.marginLeftAdd, marginLeftAdd = _ref2$marginLeftAdd === void 0 ? 0 : _ref2$marginLeftAdd, _ref2$marginRightAdd = _ref2.marginRightAdd, marginRightAdd = _ref2$marginRightAdd === void 0 ? 0 : _ref2$marginRightAdd, _ref2$marginBottomAdd = _ref2.marginBottomAdd, marginBottomAdd = _ref2$marginBottomAdd === void 0 ? 8 : _ref2$marginBottomAdd, _ref2$borderRadius = _ref2.borderRadius, borderRadius = _ref2$borderRadius === void 0 ? 15 : _ref2$borderRadius, _ref2$minWidthText = _ref2.minWidthText, minWidthText = _ref2$minWidthText === void 0 ? 90 : _ref2$minWidthText, _ref2$elemHeight = _ref2.elemHeight, elemHeight = _ref2$elemHeight === void 0 ? 35 : _ref2$elemHeight, _ref2$normFont = _ref2.normFont, normFont = _ref2$normFont === void 0 ? 18 : _ref2$normFont, _ref2$widthPrc = _ref2.widthPrc, widthPrc = _ref2$widthPrc === void 0 ? 0.2 : _ref2$widthPrc, _ref2$widthMin = _ref2.widthMin, widthMin = _ref2$widthMin === void 0 ? 270 : _ref2$widthMin, _ref2$widthMax = _ref2.widthMax, widthMax = _ref2$widthMax === void 0 ? 350 : _ref2$widthMax;
    var _useContext = x(LanguageContext); _useContext.lng;
    var resultTextShow;
    resultTextShow = " - " + amount + "% " + name;
    y(function() {
    });
    var maxElemWidth = widthMax > widthScreen * widthPrc ? widthScreen * widthPrc : widthMax;
    var elemWidth = maxElemWidth > widthMin ? maxElemWidth : widthMin;
    var padding = 5;
    var sidePadding = 5;
    var fontStyle = {
      fontSize: "".concat(normFont, "px"),
      textAlign: "center",
      marginTop: "".concat(-(normFont - elemHeight) * 0.5, "px"),
      lineHeight: "100%",
      color: "".concat(textCol)
    };
    var textSideRight = {
      position: "relative",
      display: "flex",
      margin: "0px",
      marginLeft: "".concat(padding + 4, "px"),
      minWidth: "".concat(minWidthText, "px")
    };
    var elementStyle = {
      boxShadow: "3px 9px 0px 0px rgba(34, 60, 80, 0.2)",
      backgroundColor: color,
      display: "flex",
      justifyContent: "flex-start",
      borderRadius: "".concat(borderRadius, "px"),
      borderTopRightRadius: "0px",
      borderBottomRightRadius: "0px",
      height: "".concat(elemHeight, "px"),
      width: "".concat(elemWidth, "px"),
      margin: "".concat(sidePadding, "px"),
      marginTop: "".concat(addedTopMargin, "px"),
      marginLeft: "".concat(marginLeftAdd, "px"),
      marginBottom: "".concat(marginBottomAdd, "px"),
      marginRight: "".concat(marginRightAdd, "px")
    };
    var backStyle = {
      boxShadow: "2px 4px 0px 0px ".concat(backCol),
      width: "100%",
      position: "absolute",
      height: "".concat(elemHeight, "px"),
      borderRadius: "12px 0px 0px ".concat(borderRadius + 1, "px")
    };
    return _$1("div", {
      id: nameOfElement,
      style: elementStyle,
      "class": classDiv + " inGame"
    }, _$1("div", {
      id: nameOfElement + "Text",
      style: textSideRight,
      "class": ""
    }, _$1("p", {
      style: fontStyle
    }, place), _$1("p", {
      style: fontStyle
    }, resultTextShow)), _$1("div", {
      style: backStyle
    }));
  };

  window.requestAnimFrameFrwrks = function() {
    return window.requestAnimationFrame || window.webkitRequestAnimationFrame || window.mozRequestAnimationFrame || function(callback) {
      window.setTimeout(callback, 1e3 / 60);
    };
  }();
  var createFireworks = function createFireworks2(canvasId) {
    function acceptCanvas(canvasId2) {
      var canvas2 = document.getElementById(canvasId2);
      if (canvas2) {
        var ctx = canvas2.getContext("2d");
        exprt.ctx = ctx;
        exprt.canvasActivated = true;
      } else {
        console.log("canvas not found", canvasId2);
      }
    }
    var canvas = document.getElementById(canvasId);
    var exprt = {};
    exprt.canvasId = canvasId;
    exprt.isOn = false;
    if (canvas) {
      acceptCanvas(exprt.canvasId);
    } else {
      exprt.canvasActivated = false;
      console.warn("NO Canvas provided");
    }
    var cw = window.innerWidth, ch = window.innerHeight, fireworks = [], particles = [], hue = 120, timerTotal = 0.85, timerCur = 0;
    var now = 0;
    var dt = 0;
    var animationId = -1;
    var lastUpdate = Date.now();
    exprt.fireworks = fireworks;
    window.addEventListener("resize", function() {
      ch = window.innerHeight;
      cw = window.innerWidth;
      if (exprt.canvasActivated) {
        canvas.width = cw;
        canvas.height = ch;
      }
    }, false);
    function random(min, max) {
      return Math.random() * (max - min) + min;
    }
    function calculateDistance(p1x, p1y, p2x, p2y) {
      var xDistance = p1x - p2x, yDistance = p1y - p2y;
      return Math.sqrt(Math.pow(xDistance, 2) + Math.pow(yDistance, 2));
    }
    var Firework = /* @__PURE__ */ function() {
      function Firework2(startX, startY, targetX, targetY) {
        _classCallCheck(this, Firework2);
        this.x = startX;
        this.y = startY;
        this.startX = startX;
        this.startY = startY;
        this.targetX = targetX;
        this.targetY = targetY;
        this.distanceToTarget = calculateDistance(startX, startY, targetX, targetY);
        this.distanceTraveled = 0;
        this.coordinates = [];
        this.coordinateCount = 3;
        while (this.coordinateCount--) {
          this.coordinates.push([this.x, this.y]);
        }
        this.angle = Math.atan2(targetY - startY, targetX - startX);
        this.speed = 150;
        this.acceleration = 1.05;
        this.brightness = random(50, 70);
        this.targetRadius = 1;
      }
      return _createClass(Firework2, [{
        key: "update",
        value: function update(index) {
          this.coordinates.pop();
          this.coordinates.unshift([this.x, this.y]);
          if (this.targetRadius < 8) {
            this.targetRadius += 0.3;
          } else {
            this.targetRadius = 1;
          }
          this.speed *= this.acceleration;
          var velocityX = Math.cos(this.angle) * this.speed, velocityY = Math.sin(this.angle) * this.speed;
          this.distanceTraveled = calculateDistance(this.startX, this.startY, this.x + velocityX * dt, this.y + velocityY * dt);
          if (this.distanceTraveled >= this.distanceToTarget) {
            createParticles(this.targetX, this.targetY);
            fireworks.splice(index, 1);
          } else {
            this.x += velocityX * dt;
            this.y += velocityY * dt;
          }
        }
      }, {
        key: "draw",
        value: function draw() {
          if (!exprt.canvasActivated)
            return;
          exprt.ctx.beginPath();
          exprt.ctx.moveTo(this.coordinates[this.coordinates.length - 1][0], this.coordinates[this.coordinates.length - 1][1]);
          exprt.ctx.lineTo(this.x, this.y);
          exprt.ctx.strokeStyle = "hsl(" + hue + ", 100%, " + this.brightness + "%)";
          exprt.ctx.stroke();
        }
      }]);
    }();
    var Particle = /* @__PURE__ */ function() {
      function Particle2(x, y) {
        _classCallCheck(this, Particle2);
        this.x = x;
        this.y = y;
        this.coordinates = [];
        this.coordinateCount = 5;
        while (this.coordinateCount--) {
          this.coordinates.push([this.x, this.y]);
        }
        this.angle = random(0, Math.PI * 2);
        this.speed = random(300, 900);
        this.friction = 0.95;
        this.gravity = 14;
        this.hue = random(hue - 50, hue + 50);
        this.brightness = random(50, 80);
        this.alpha = 1;
        this.decay = random(5e-3, 0.01);
      }
      return _createClass(Particle2, [{
        key: "update",
        value: function update(index, dt2) {
          this.coordinates.pop();
          this.coordinates.unshift([this.x, this.y]);
          this.speed *= this.friction;
          this.x += Math.cos(this.angle) * this.speed * dt2;
          this.y += Math.sin(this.angle) * this.speed * dt2 + this.gravity * dt2;
          this.alpha -= this.decay;
          if (this.alpha <= this.decay) {
            particles.splice(index, 1);
          }
        }
      }, {
        key: "draw",
        value: function draw() {
          if (!exprt.canvasActivated)
            return;
          exprt.ctx.lineWidth = 2;
          exprt.ctx.beginPath();
          exprt.ctx.moveTo(this.coordinates[this.coordinates.length - 1][0], this.coordinates[this.coordinates.length - 1][1]);
          exprt.ctx.lineTo(this.x, this.y);
          exprt.ctx.strokeStyle = "hsla(" + this.hue + ", 100%, " + this.brightness + "%, " + this.alpha + ")";
          exprt.ctx.stroke();
        }
      }]);
    }();
    function createParticles(x, y) {
      var particleCount = 26;
      while (particleCount--) {
        particles.push(new Particle(x, y));
      }
    }
    function loop() {
      if (!exprt.canvasActivated) {
        start();
        return;
      }
      now = Date.now();
      dt = (now - lastUpdate) / 1e3;
      lastUpdate = now;
      hue = random(0, 360);
      exprt.ctx.globalCompositeOperation = "destination-out";
      exprt.ctx.fillStyle = "rgba(0, 0, 0, 0.5)";
      exprt.ctx.fillRect(0, 0, cw, ch);
      exprt.ctx.globalCompositeOperation = "lighter";
      var i = fireworks.length;
      while (i--) {
        fireworks[i].draw();
        fireworks[i].update(i, dt);
      }
      var i = particles.length;
      while (i--) {
        particles[i].draw();
        particles[i].update(i, dt);
      }
      if (timerCur >= timerTotal) {
        fireworks.push(new Firework(cw / 2, ch, random(cw * 0.2, cw * 0.7), random(ch * 0.3, ch * 0.7)));
        timerCur = 0;
      } else {
        timerCur += dt;
      }
      exprt.dt = dt;
      start();
    }
    var start = function start2() {
      if (!exprt.canvasActivated) {
        acceptCanvas(exprt.canvasId);
      }
      if (!exprt.isOn) {
        exprt.ctx.clearRect(0, 0, canvas.width, canvas.height);
      }
      exprt.animationId = animationId = requestAnimFrameFrwrks(loop);
      exprt.isOn = true;
    };
    var stop = function stop2() {
      if (animationId != -1)
        window.cancelAnimationFrame(animationId);
      exprt.ctx.clearRect(0, 0, canvas.width, canvas.height);
      fireworks.splice(0, fireworks.length);
      particles.splice(0, particles.length);
    };
    exprt.start = function() {
      start();
    };
    exprt.stop = function() {
      stop();
    };
    exprt.loop = function() {
      loop();
    };
    exprt.animationId = animationId;
    exprt.isOn = false;
    return exprt;
  };

  var PositionBlock = function PositionBlock2(props) {
    var styleCenter = {
      display: "flex",
      justifyContent: "flex-center",
      minWidth: props.minWidth || "250px"
    };
    y(function() {
    }, []);
    return _$1("div", {
      className: "positionBlock",
      style: styleCenter
    }, props.children);
  };

  var Paper3Game = function Paper3Game2(_ref) {
    var skins = _ref.skins; _ref.skin; _ref.config;
    var size2 = resizeToWindow();
    var lng = x(LanguageContext).lng;
    var _useState = d(0), _useState2 = _slicedToArray(_useState, 2), curKills = _useState2[0], setCurKills = _useState2[1];
    var _useState3 = d(0), _useState4 = _slicedToArray(_useState3, 2), curScore = _useState4[0], setCurScore = _useState4[1];
    var _useState5 = d(0), _useState6 = _slicedToArray(_useState5, 2), curPrc = _useState6[0], setCurPrc = _useState6[1];
    var _useState7 = d(0), _useState8 = _slicedToArray(_useState7, 2), curBestPrc = _useState8[0], setCurBestPrc = _useState8[1];
    var _useState9 = d(-1), _useState10 = _slicedToArray(_useState9, 2); _useState10[0]; _useState10[1];
    var _useState11 = d([]), _useState12 = _slicedToArray(_useState11, 2), skinsColsAr = _useState12[0], setSkinsColsAr = _useState12[1];
    var _useState13 = d([]), _useState14 = _slicedToArray(_useState13, 2), localNotificationsAr = _useState14[0], setLocalNotificationsAr2 = _useState14[1];
    var _useState15 = d(false), _useState16 = _slicedToArray(_useState15, 2); _useState16[0]; _useState16[1];
    var _useState17 = d("score"), _useState18 = _slicedToArray(_useState17, 2), lbSortProp = _useState18[0]; _useState18[1];
    var _useState19 = d([]), _useState20 = _slicedToArray(_useState19, 2), sortedUsers = _useState20[0], setSortedUsers = _useState20[1];
    var _useState21 = d([]), _useState22 = _slicedToArray(_useState21, 2); _useState22[0]; _useState22[1];
    var _useState23 = d(null), _useState24 = _slicedToArray(_useState23, 2); _useState24[0]; _useState24[1];
    //!lets notif mngr update!
    var _useState25 = d(window.uiApi.saveData.userId), _useState26 = _slicedToArray(_useState25, 2), overlayUserId = _useState26[0], setOverlayUserId = _useState26[1];
    var _useState27 = d(-1), _useState28 = _slicedToArray(_useState27, 2); _useState28[0]; _useState28[1];
    var styleFirwrks = {
      top: 0,
      left: 0,
      width: "100%",
      height: "100%",
      position: "fixed",
      background: "rgb(255 255 255 / 0%)"
    };
    window.uiApi.getNewMapPopUp = function(mapName) {
      var name = lng.maps[mapName];
      window.uiApi.innerEventReact(TOP_POP_UP, "", "New Map: " + name + " unlocked!");
    };
    var updateDivs = function updateDivs2(newObj) {
      var userData = newObj;
      sortUsers(lbSortProp, newObj.users);
      setOverlayUserId(newObj.overlayUserId);
      var showPrc = userData.scores / userData.best * 100;
      setCurPrc && setCurPrc(showPrc > 100 ? 100 : showPrc);
      setCurScore && setCurScore(userData.scores);
      setCurBestPrc && setCurBestPrc(userData.best);
      setCurKills(userData.kills);
    };
    var sortUsers = function sortUsers2() {
      var lbSortProp2 = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : "score";
      var users = arguments.length > 1 && arguments[1] !== void 0 ? arguments[1] : [];
      var addSortProp = arguments.length > 2 && arguments[2] !== void 0 ? arguments[2] : "code";
      var ar = _toConsumableArray(users);
      ar = ar.filter(function(user) {
        return user[lbSortProp2] !== 0;
      });
      ar.sort(function(a, b) {
        if (a[lbSortProp2] > b[lbSortProp2]) {
          return -1;
        }
        if (a[lbSortProp2] < b[lbSortProp2]) {
          return 1;
        }
        if (a[addSortProp] > b[addSortProp]) {
          return -1;
        }
        return 0;
      });
      var posToCheck = 5;
      var hasPlayerInFirsts = false;
      ar.forEach(function(userData, i) {
        if (i < posToCheck) {
          if (userData.code == overlayUserId) {
            hasPlayerInFirsts = true;
            userData.isPlayer = true;
            userData.skin = window.uiApi.saveData.skin;
          }
        }
        userData.place = i;
      });
      var shortAr = ar.splice(0, posToCheck);
      if (!hasPlayerInFirsts) {
        var playerInfo = ar.find(function(el) {
          return el.code + "" == overlayUserId;
        });
        if (playerInfo) {
          playerInfo.isPlayer = true;
          playerInfo.skin = window.uiApi.saveData.skin;
          shortAr.push(playerInfo);
        }
      }
      setSortedUsers(shortAr);
      return shortAr;
    };
    window.uiApi.updateDivsCb = updateDivs;
    var getColor = function getColor2(code) {
      if (skinsColsAr[code])
        return skinsColsAr[code];
      else {
        return {
          main: "#3b7dd8",
          back: "#245fb2",
          nickColor: "#245fb2",
          lbTextColor: "#245fb2",
          particles: ["#3b7dd8", "#9fbadf"]
        };
      }
    };
    var genColorsAr = function genColorsAr2(shortPalette) {
      var ar = [];
      shortPalette.forEach(function(color, i) {
        ar.push(genColInfo(color));
      });
      return ar;
    };
    var genColInfo = function genColInfo2(color) {
      var rgb = hexToRgb(color);
      var hsv = rgb2hsv(rgb);
      var darker = function darker2(hsv2, value) {
        var h2 = hsv2.h, s = hsv2.s, v = hsv2.v;
        v *= value;
        return {
          h: h2,
          s,
          v
        };
      };
      var lighter = function lighter2(hsv2, value) {
        var h2 = hsv2.h, s = hsv2.s, v = hsv2.v;
        var k = 100 - v;
        v = Math.max(v * value, v + value * k / 4);
        return {
          h: h2,
          s,
          v
        };
      };
      var scale = function scale2(hsv2, value) {
        var h2 = hsv2.h, s = hsv2.s, v = hsv2.v;
        v = value;
        return {
          h: h2,
          s,
          v
        };
      };
      var backHSV = darker(hsv, 0.75);
      var back = hsvToHex(backHSV);
      var darkHSV = darker(hsv, 0.5);
      var dark = hsvToHex(darkHSV);
      var halfLightHSV = lighter(hsv, 1.5);
      hsvToHex(halfLightHSV);
      var lightHSV = lighter(hsv, 2);
      var light = hsvToHex(lightHSV);
      return {
        main: color,
        back,
        nickColor: dark,
        lbTextColor: hsv.v > 50 ? dark : light,
        particles: [hsvToHex(scale(hsv, 100)), hsvToHex(scale(hsv, 90)), hsvToHex(scale(hsv, 80)), hsvToHex(scale(hsv, 70)), hsvToHex(scale(hsv, 60)), hsvToHex(scale(hsv, 50)), hsvToHex(scale(hsv, 40)), hsvToHex(scale(hsv, 30)), hsvToHex(scale(hsv, 20))]
      };
    };
    y(function() {
      window.uiApi.fireworks = createFireworks("canvasEffects");
    }, []);
    y(function() {
      setSkinsColsAr(genColorsAr(window.p3ShortPalette));
    }, []);
    return _$1("div", {
      id: "ingameUI",
      "class": "doClick"
    }, _$1("div", {
      "class": "centerXC centerYC inGame",
      id: "fireworks",
      style: styleFirwrks
    }, window.uiApi.effectsCanvasReturned()), (localNotificationsAr.length > 0 || window.uiApi.notificationsToShow && window.uiApi.notificationsToShow[IN_GAME_NOTIFICATION] && window.uiApi.notificationsToShow[IN_GAME_NOTIFICATION].length > 0) && _$1(NotificationMngr, {
      type: IN_GAME_NOTIFICATION,
      arrayData: window.uiApi.notificationsToShow[IN_GAME_NOTIFICATION],
      notificationsAr: localNotificationsAr,
      updateNotificationAr: setLocalNotificationsAr2,
      maxLines: 1,
      classDiv: "innerNotif centerXC top40C topZ",
      waitHide: 5,
      animTime: 0.5,
      replaceCurrent: false
    }), _$1("div", {
      id: "leftTopCornerUi",
      "class": "leftC topC"
    }, _$1("div", {
      "class": "vertBlock"
    }, _$1(PrcBar, {
      widthScreen: size2.width || window.innerWidth,
      heightScreen: size2.height || window.innerHeight,
      curPrc,
      updateShowPrc: setCurPrc,
      newAm: curScore.toFixed(2),
      maxAm: curBestPrc,
      minWidth: 120,
      barHeight: 33,
      barCol: getColor(overlayUserId).main,
      backCol: getColor(overlayUserId).back
    }), _$1(IconText, {
      widthScreen: size2.width || window.innerWidth,
      normFont: window.innerHeight > window.innerWidth ? 18 : 19,
      icon: "",
      classDiv: "leftBorder",
      textColor: "#02030269",
      nameOfElement: "best",
      elemHeight: 25,
      widthPrc: window.innerHeight > window.innerWidth ? 0.1 : 0.17,
      sidePadding: 0,
      marginLeftAdd: 5,
      iconSize: 40,
      widthMin: 130,
      widthMax: 160,
      value: lng.bestTxt + " " + curBestPrc.toFixed(2) + "%"
    }), _$1(IconText, {
      widthScreen: size2.width || window.innerWidth,
      normFont: 25,
      icon: "skull",
      classDiv: "backPlate leftBorder",
      nameOfElement: "kills",
      textSign: "x",
      marginLeftAdd: 0,
      elemHeight: 40,
      iconSize: 30,
      minWidthText: 40,
      widthMin: 90,
      widthMax: 90,
      value: curKills
    }))), _$1("div", {
      "class": "rightC topC"
    }, _$1(InGameLbBasic, {
      skins,
      widthScreen: size2.width || window.innerWidth,
      heightScreen: size2.height || window.innerHeight,
      skinColsInfo: skinsColsAr,
      nameOfElement: "inGameLb",
      classDiv: "",
      dataAr: sortedUsers
    })));
  };
  var initMode = function initMode2(config) {
    window.uiApi.config = config;
    window.uiApi.customModeCb = function(map) {
      window.changeModel(map);
    };
    window.uiApi.testUnlockMap = function() {
      var mapName = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : "cube";
      window.uiApi.getSaveData().map = mapName;
      window.uiApi.gameOverShow({
        "score": 100,
        "kills": 3
      });
    };
    window.uiApi.gameOverCustom = function(results, config2) {
      var curData = window.uiApi.getCurData();
      if (curData.deathTime) {
        curData.deathTime - curData.spawnTime;
      }
      results["play"] = 1;
      results["deaths"] = 1;
      var saveDataObj = Object.assign({}, window.uiApi.getSaveData());
      config2.bestProps.forEach(function(propAr) {
        var propName = propAr[1];
        var propBestName = propAr[0];
        if (results[propName]) {
          if (propName == "score") {
            var mapName = saveDataObj.map;
            var prevBestMapScore = saveDataObj.mapsBestPrc[mapName];
            var newBestMapScore = results[propName];
            if (newBestMapScore > prevBestMapScore) {
              saveDataObj.mapsBestPrc[mapName] = newBestMapScore;
            }
            results[propBestName] = saveDataObj.mapsBestPrc[mapName];
          } else {
            var oldVal = window.uiApi.getSaveData()[propBestName] || 0;
            var newVal = results[propName];
            if (newVal > oldVal) {
              saveDataObj[propBestName] = newVal;
            }
            results[propBestName] = saveDataObj[propBestName];
          }
        }
      });
      config2.accumProps.forEach(function(propAr) {
        var propName = propAr[1];
        var propAllName = propAr[0];
        if (results[propName]) {
          if (propName == "score") {
            var mapName = saveDataObj.map;
            var allMapScore = saveDataObj.mapsAllPrc[mapName];
            var newScore = parseFloat(results[propName]);
            var sumVal = allMapScore + newScore;
            saveDataObj.mapsAllPrc[mapName] = sumVal;
          } else {
            var oldVal = window.uiApi.getSaveData()[propAllName] || 0;
            var newVal = parseFloat(results[propName]);
            var _sumVal = oldVal + newVal;
            saveDataObj[propAllName] = _sumVal;
            saveDataObj[propName] = results[propName];
          }
        }
      });
      window.uiApi.setSaveData(saveDataObj);
      unlockLevels(config2);
      config2.resultPropNames.forEach(function(propName) {
        if (!results[propName]) {
          results[propName] = curData[propName];
          if (window.uiApi.getSaveData()[propName] && propName == "best") {
            results[propName] = window.uiApi.getSaveData()[propName];
          }
        }
        if (results[propName] === void 0)
          results[propName] = 0;
      });
      return results;
    };
    window.uiApi.showYouWin = function() {
      window.uiApi.innerEventReact(IN_GAME_NOTIFICATION, "");
    };
    window.uiApi.innerEventReact = function() {
      var type = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : "";
      var posClass = arguments.length > 1 && arguments[1] !== void 0 ? arguments[1] : "";
      var title = arguments.length > 2 && arguments[2] !== void 0 ? arguments[2] : "Title";
      var info = arguments.length > 3 && arguments[3] !== void 0 ? arguments[3] : {};
      if (type == TOP_POP_UP) {
        window.uiApi.basicEventReact && window.uiApi.basicEventReact(type, posClass, title, info);
        return;
      }
      if (!window.uiApi.notificationsToShow[type])
        window.uiApi.notificationsToShow[type] = [];
      var drawElement;
      switch (type) {
        case IN_GAME_NOTIFICATION:
          drawElement = function drawElement2() {
            return _$1(PositionBlock, {
              minWidth: 250
            }, _$1(ElementsLine, {
              nameOfElement: "newInGameNotif",
              icon1: null,
              normFont: 25,
              widthScreen: size.width,
              text1: "YOU WIN!",
              fontClass: "winText",
              elemHeight: 33,
              justifyContent: "center",
              classDiv: "inGame midMoveX",
              widthMax: 250
            }));
          };
          break;
      }
      var id = uuid();
      window.uiApi.notificationsToShow[type].push({
        type,
        posClass,
        title,
        info,
        drawElement,
        id
      });
      switch (type) {
        case IN_GAME_NOTIFICATION:
          setLocalNotificationsAr(window.uiApi.notificationsToShow[type]);
          break;
      }
      setLastEventInfo({
        type,
        posClass,
        title,
        info,
        id
      });
    };
    unlockLevels(config);
  };
  function unlockLevels(config) {
    var data = window.uiApi.getSaveData();
    var lastUnlockedMapName = data.lastUnlockedMap;
    var bestResultsByName = data.mapsBestPrc;
    var mapNames = config.modeSelect.list;
    var unlocksConditions = config.modeSelect.unlocksConditions;
    var unlockedIndx = Math.max(0, mapNames.indexOf(lastUnlockedMapName));
    for (var i = unlockedIndx + 1; i < mapNames.length; i++) {
      var map = mapNames[i];
      var prevMap = mapNames[i - 1];
      if (bestResultsByName[prevMap] >= unlocksConditions[map].value) {
        window.ga && window.ga("send", "event", "paper3d", map);
        window.uiApi.getSaveData().lastUnlockedMap = map;
        window.uiApi.getNewMapPopUp && window.uiApi.getNewMapPopUp(map);
        window.uiApi.setMenu();
      } else {
        return;
      }
    }
  }

  var LBItem = function LBItem2(_ref) {
    var name = _ref.name, scores = _ref.scores, place = _ref.place, player = _ref.player;
    return _$1("li", {
      "class": place > 11 ? "extra_margin" : ""
    }, _$1("div", {
      "class": "lb_item_left"
    }, place <= 99 && _$1("span", {
      "class": "top top".concat(place, " ").concat(place > 99 ? "extra" : "")
    }, place), place > 99 && _$1("span", {
      "class": "empty"
    }), _$1("span", {
      "class": "title".concat(player ? " player" : "")
    }, name)), _$1("span", null, scores));
  };
  var Leaderboard = function Leaderboard2(_ref2) {
    var leaderboard = _ref2.leaderboard, title = _ref2.title;
    return leaderboard && _$1("div", {
      "class": "leaderboard"
    }, _$1("div", {
      "class": "wrapper"
    }, _$1("h3", null, title), _$1("ul", null, leaderboard.map(function(c) {
      return _$1(LBItem, {
        place: c.leaderboardPosition,
        name: c.userName.length > 15 ? c.userName.substring(0, 15) + "..." : c.userName,
        scores: ~~c.leaderboardValue
      });
    }))));
  };

  var Tips = function Tips2(_ref) {
    var messages = _ref.messages;
    var _useState = d(0), _useState2 = _slicedToArray(_useState, 2), index = _useState2[0], setIndex = _useState2[1];
    y(function() {
      var timer = setInterval(function() {
        return setIndex(function(index2) {
          return (index2 + 1) % messages.length;
        });
      }, 3e3);
      return function() {
        return clearInterval(timer);
      };
    }, []);
    return _$1("div", {
      "class": "tips"
    }, _$1("div", {
      "class": "tip",
      key: index
    }, messages[index]));
  };

  var ModeSelect = function ModeSelect2(_ref) {
    var setMode = _ref.setMode, modes = _ref.modes, currentMode = _ref.currentMode, _ref$preparing = _ref.preparing, preparing = _ref$preparing === void 0 ? false : _ref$preparing;
    var _useContext = x(LanguageContext), lng = _useContext.lng;
    console.log("Mode select", modes, currentMode);
    var _useState = d(false), _useState2 = _slicedToArray(_useState, 2), open = _useState2[0], setOpen = _useState2[1];
    var toggleOptions = function toggleOptions2() {
      !preparing && setOpen(!open);
    };
    var onSelect = function onSelect2(mode) {
      toggleOptions();
      setMode(mode);
      window.uiApi.setSaveData({
        map: mode
      });
    };
    var banner = document.getElementById(window.bannerName);
    if (banner) {
      if (window.innerHeight < 710) {
        if (window.innerWidth > 450)
          banner.className = open ? "openedSmSelect" : "";
        else
          banner.className = open ? "openedSelect" : "";
        if (window.innerHeight < 650)
          banner.className = open ? "openedSmSelect" : "";
        else if (window.innerHeight < 420)
          banner.className = "hidden";
      } else {
        banner.className = "";
      }
    }
    var filteredModes = modes;
    return filteredModes.length > 1 && _$1("div", {
      "class": "mode-select"
    }, _$1("div", {
      "class": "mode-selected",
      onClick: toggleOptions
    }, _$1("div", {
      "class": "mode-label"
    }, _$1("span", null, lng.maps[currentMode])), _$1("span", {
      "class": "arrow-down"
    }, "\u25BE")), open && _$1("div", {
      "class": "mode-options"
    }, filteredModes.map(function(c, i) {
      return _$1("div", {
        "class": "mode-option",
        key: i,
        tabIndex: "0",
        onClick: function onClick() {
          return onSelect(c);
        }
      }, _$1("div", {
        "class": "mode-label"
      }, _$1("span", null, lng.maps[c])));
    })));
  };

  var ModeSelectWithLocks = function ModeSelectWithLocks2(_ref) {
    var setMode = _ref.setMode, modes = _ref.modes, currentMode = _ref.currentMode, modesDetails = _ref.modesDetails, lastUnlocked = _ref.lastUnlocked, unlocksConditions = _ref.unlocksConditions, _ref$preparing = _ref.preparing, preparing = _ref$preparing === void 0 ? false : _ref$preparing;
    var _useContext = x(LanguageContext), lng = _useContext.lng;
    var _useState = d(false), _useState2 = _slicedToArray(_useState, 2), open = _useState2[0], setOpen = _useState2[1];
    var toggleOptions = function toggleOptions2() {
      !preparing && setOpen(!open);
    };
    var onSelect = function onSelect2(mode) {
      toggleOptions();
      setMode(mode);
      window.uiApi.setSaveData({
        map: mode
      });
      checkBannerForOpen();
    };
    var banner = document.getElementById(window.adsBannerId);
    var checkBannerForOpen = function checkBannerForOpen2() {
      if (banner) {
        if (open)
          banner.className = "hidden";
        else {
          window.ads.resizeAds && window.ads.resizeAds();
          showBanner();
        }
      }
    };
    var showBanner = function showBanner2() {
      if (banner) {
        if (window.innerHeight < 910) {
          if (window.innerWidth > 450)
            banner.className = open ? "openedSmSelect" : "";
          else
            banner.className = open ? "openedSelect" : "";
          if (window.innerHeight < 650)
            banner.className = open ? "openedSmSelect" : "";
          else if (window.innerHeight < 420) {
            banner.className = "hidden";
          }
        } else {
          banner.className = "";
        }
      }
    };
    y(function() {
      checkBannerForOpen();
    }, [open]);
    var checkCurTaskDetails = function checkCurTaskDetails2(mapName) {
      var unlockedIndx = modes.indexOf(lastUnlocked);
      var checkTaskIndx = modes.indexOf(mapName);
      if (checkTaskIndx > unlockedIndx + 1) {
        return _$1("img", {
          id: "lockIcon",
          width: 15,
          height: 15,
          src: "assets" + "/images/lock.png"
        });
      } else if (checkTaskIndx == unlockedIndx + 1) {
        var prevMapName = modes[checkTaskIndx - 1];
        return lng.maps[prevMapName] + " " + modesDetails[prevMapName].toFixed(2) + "/" + unlocksConditions[mapName].value + "%";
      } else {
        return modesDetails[mapName].toFixed(2) + "%";
      }
    };
    var locked = function locked2(mapName) {
      var unlockedIndx = modes.indexOf(lastUnlocked);
      var checkTaskIndx = modes.indexOf(mapName);
      return checkTaskIndx > unlockedIndx;
    };
    var getSideDetail = function getSideDetail2(mapName) {
      return checkCurTaskDetails(mapName);
    };
    var filteredModes = modes;
    return _$1("div", {
      "class": "mode-select"
    }, _$1("div", {
      "class": "mode-selected",
      onClick: toggleOptions
    }, _$1("div", {
      "class": "mode-label"
    }, _$1("span", null, lng.maps[currentMode])), _$1("span", {
      "class": "arrow-down"
    }, "\u25BE")), open && _$1("div", {
      "class": "mode-options"
    }, filteredModes.map(function(mapName, i) {
      return _$1("div", {
        "class": "mode-option",
        key: i,
        tabIndex: "0",
        onClick: function onClick() {
          if (!locked(mapName))
            onSelect(mapName);
        }
      }, _$1("div", {
        "class": "mode-label spaced"
      }, _$1("span", null, lng.maps[mapName]), _$1("span", null, getSideDetail(mapName))));
    })));
  };

  var Menu = function Menu2(_ref) {
    var nickName = _ref.nickName, setNickName = _ref.setNickName, setState = _ref.setState, playable = _ref.playable, startGame = _ref.startGame, curLeaderbType = _ref.curLeaderbType, curLeaderbAr = _ref.curLeaderbAr, switchLeaderb = _ref.switchLeaderb, config = _ref.config, setMode = _ref.setMode, currentMode = _ref.currentMode, modeSelect = _ref.modeSelect, skin = _ref.skin, logo = _ref.logo;
    var _useContext = x(LanguageContext), lng = _useContext.lng;
    var onNickChange = function onNickChange2(event) {
      return setNickName(event.target.value);
    };
    var _useState = d(playable), _useState2 = _slicedToArray(_useState, 2); _useState2[0]; _useState2[1];
    var playCb = function playCb2(event) {
      if (playable === false) {
        return;
      }
      event.preventDefault();
      window.ga && window.ga("send", "event", "paper3d", "start_play");
      startGame && startGame();
    };
    var _useState3 = d(false), _useState4 = _slicedToArray(_useState3, 2); _useState4[0]; var setNeedsLeaderb = _useState4[1];
    var _useState5 = d(lng.topKills), _useState6 = _slicedToArray(_useState5, 2), curLeaderbTitleText = _useState6[0], setCurLeaderbTitleText = _useState6[1];
    var _useState7 = d(lng.killsLeaderSwitch), _useState8 = _slicedToArray(_useState7, 2), curLeaderbBtnText = _useState8[0], setCurLeaderbBtnText = _useState8[1];
    window.uiApi.curMenu = "menu";
    var checkNeedsLeaderb = function checkNeedsLeaderb2(leaderboardAr) {
      setNeedsLeaderb(true);
      if (!leaderboardAr) {
        setNeedsLeaderb(false);
      } else {
        setNeedsLeaderb(true);
      }
    };
    var updateLbName = function updateLbName2() {
      var curIndx = config.lbTypes.indexOf(curLeaderbType);
      var nextNameIndx = curIndx >= config.lbTypes.length - 1 ? 0 : curIndx + 1;
      var nextLbName = config.lbTypes[nextNameIndx];
      switch (curLeaderbType) {
        case "time":
          setCurLeaderbTitleText(lng.topTime);
          break;
        case "money":
          setCurLeaderbTitleText(lng.topMoney);
          break;
        case "score":
          setCurLeaderbTitleText(lng.topScores);
          break;
        case "kills":
          setCurLeaderbTitleText(lng.topKills);
          break;
      }
      switch (nextLbName) {
        case "time":
          setCurLeaderbBtnText(lng.timeLeaderSwitch);
          break;
        case "money":
          setCurLeaderbBtnText(lng.moneyLeaderSwitch);
          break;
        case "score":
          setCurLeaderbBtnText(lng.scoreLeaderSwitch);
          break;
        case "kills":
          setCurLeaderbBtnText(lng.killsLeaderSwitch);
          break;
      }
    };
    updateLbName();
    var chooseMode = function chooseMode2() {
      if (!modeSelect) {
        return null;
      }
      if (!modeSelect.unlocksPrc) {
        return _$1(ModeSelect, {
          setMode,
          modes: modeSelect.list,
          currentMode
        });
      } else {
        return _$1(ModeSelectWithLocks, {
          setMode,
          lastUnlocked: window.uiApi.getSaveData().lastUnlockedMap,
          modes: modeSelect.list,
          modesDetails: window.uiApi.getSaveData().mapsBestPrc,
          currentMode,
          unlocksConditions: modeSelect.unlocksConditions
        });
      }
    };
    y(function() {
      window.showMenuElements && window.showMenuElements("menu");
      window.ads && window.ads.showAds && window.ads.showAds();
      checkNeedsLeaderb(curLeaderbAr);
    }, [curLeaderbType]);
    return _$1(k$1, null, _$1("div", {
      id: "left_side"
    }), _$1("div", {
      "class": "uibox"
    }, _$1("div", {
      "class": "logo"
    }, _$1("img", {
      src: logo
    })), _$1(Tips, {
      messages: lng.messages
    }), _$1("div", {
      "class": "play"
    }, _$1("input", {
      type: "text",
      id: "nick",
      name: "nick",
      value: nickName,
      autocomplete: "off",
      placeholder: lng.placeholderText,
      maxlength: "11",
      oninput: onNickChange
    }), _$1("button", {
      id: "play",
      name: "play",
      "class": "yellow" + (playable ? "" : " disabled"),
      onClick: playCb
    }, lng.btnPlay), config.gameSettings.skins != null && _$1("button", {
      id: "skins",
      name: "skins",
      "class": "orange noPadding",
      onClick: function onClick() {
        return setState("skins");
      }
    }, _$1("img", {
      width: "30",
      height: "30",
      src: "".concat("assets", "/images/skins/").concat(skin.toLowerCase().replace(/\s+/g, ""), ".png")
    }))), chooseMode(), _$1("div", {
      id: window.adsBannerId
    }, _$1("div", {
      id: window.bannerName,
      style: 'width: "'.concat(window.adsBannerWidth, '" px; height: "').concat(window.adsBannerHeight, '"px;  text-align: center;')
    }))), _$1("div", {
      id: "right_side"
    }, curLeaderbAr && curLeaderbAr[0].userName && _$1("div", null, _$1(Leaderboard, {
      leaderboard: curLeaderbAr,
      title: curLeaderbTitleText
    }), _$1("button", {
      "class": "switchLeadBtn",
      onClick: switchLeaderb
    }, curLeaderbBtnText))));
  };

  var Results = function Results2(_ref) {
    var results = _ref.results, setResults = _ref.setResults, wasRewarded = _ref.wasRewarded, callRewardAds = _ref.callRewardAds, config = _ref.config, setState = _ref.setState; _ref.nickName; var startGame = _ref.startGame, curLeaderbType = _ref.curLeaderbType, curLeaderbAr = _ref.curLeaderbAr, switchLeaderb = _ref.switchLeaderb, logo = _ref.logo;
    var btnPlayAgain = function btnPlayAgain2() {
      window.ga && window.ga("send", "event", "paper3d", "play_again");
      setResults(null);
      startGame && startGame();
    };
    var btnMenu = function btnMenu2() {
      setState("menu");
      setResults(null);
    };
    var btnChangeMode = function btnChangeMode2() {
      location.replace("https://paperio.site");
    };
    var _useContext = x(LanguageContext), lng = _useContext.lng; _useContext.name;
    config.leaderboardName;
    var _useState = d(false), _useState2 = _slicedToArray(_useState, 2); _useState2[0]; var setNeedsLeaderb = _useState2[1];
    var _useState3 = d(lng.topKills), _useState4 = _slicedToArray(_useState3, 2), curLeaderbTitleText = _useState4[0], setCurLeaderbTitleText = _useState4[1];
    var _useState5 = d(lng.killsLeaderSwitch), _useState6 = _slicedToArray(_useState5, 2), curLeaderbBtnText = _useState6[0], setCurLeaderbBtnText = _useState6[1];
    window.uiApi.curMenu = "end";
    var checkNeedsLeaderb = function checkNeedsLeaderb2(leaderboardAr) {
      setNeedsLeaderb(true);
      if (!leaderboardAr || leaderboardAr.length < 10) {
        setNeedsLeaderb(false);
      } else {
        setNeedsLeaderb(true);
      }
    };
    var updateLbName = function updateLbName2() {
      var curIndx = config.lbTypes.indexOf(curLeaderbType);
      var nextNameIndx = curIndx >= config.lbTypes.length - 1 ? 0 : curIndx + 1;
      var nextLbName = config.lbTypes[nextNameIndx];
      switch (curLeaderbType) {
        case "time":
          setCurLeaderbTitleText(lng.topTime);
          break;
        case "money":
          setCurLeaderbTitleText(lng.topMoney);
          break;
        case "score":
          setCurLeaderbTitleText(lng.topScores);
          break;
        case "kills":
          setCurLeaderbTitleText(lng.topKills);
          break;
      }
      switch (nextLbName) {
        case "time":
          setCurLeaderbBtnText(lng.timeLeaderSwitch);
          break;
        case "money":
          setCurLeaderbBtnText(lng.moneyLeaderSwitch);
          break;
        case "score":
          setCurLeaderbBtnText(lng.scoreLeaderSwitch);
          break;
        case "kills":
          setCurLeaderbBtnText(lng.killsLeaderSwitch);
          break;
      }
    };
    updateLbName();
    y(function() {
      window.showMenuElements("menu");
      window.ads && window.ads.showAds && window.ads.showAds();
      checkNeedsLeaderb(curLeaderbAr);
    }, [curLeaderbType]);
    return _$1(k$1, null, _$1("div", {
      id: "left_side"
    }), _$1("div", {
      "class": "uibox"
    }, _$1("div", {
      "class": "logo"
    }, _$1("img", {
      src: logo
    })), _$1("div", {
      "class": "resultbox"
    }, _$1(
      "div",
      {
        "class": "results"
      },
      _$1("div", {
        "class": "left"
      }, _$1("div", {
        "class": "slider-1"
      }, lng.yourScore, ":"), _$1("div", {
        "class": "slider-2"
      }, results.newBest && _$1("span", {
        "class": "newScore"
      }, lng.newText, " "), lng.bestScore, ":"), _$1("div", {
        "class": "slider-3"
      }, lng.timePlayed, ":"), _$1("div", {
        "class": "slider-4"
      }, lng.playersKilled, ":")),
      _$1("div", {
        "class": "right"
      }, _$1("div", {
        "class": "slider-1"
      }, "".concat((results[config.resultPropNames[0]] || 0).toFixed(2))), _$1("div", {
        "class": "slider-2"
      }, (results[config.resultPropNames[1]] || 0).toFixed(2) + ""), _$1("div", {
        "class": "slider-3"
      }, formatTime(results[config.resultPropNames[2]] || 0)), _$1("div", {
        "class": "slider-4"
      }, results[config.resultPropNames[3]] || 0))
    )), _$1("div", {
      "class": "nav"
    }, _$1("button", {
      "class": "yellow slider-5",
      id: "menuContinue",
      onClick: btnPlayAgain
    }, lng.btnPlayAgain), _$1("button", {
      "class": "green slider-5",
      id: "menuMain",
      onClick: btnMenu
    }, lng.btnMenu), _$1("button", {
      "class": "green slider-5",
      id: "menuChangeMode",
      onClick: btnChangeMode
    }, lng.btnChangeMode), config.extraLife && !wasRewarded && _$1("button", {
      "class": "green stretched slider-5",
      id: "extra",
      onClick: callRewardAds
    }, _$1("img", {
      src: "".concat("assets", "/images/videoIcon.svg")
    }), lng.extraLife)), _$1("div", {
      id: window.adsBannerId
    }, _$1("div", {
      id: window.bannerName,
      style: 'width: "'.concat(window.adsBannerWidth, '" px; height: "').concat(window.adsBannerHeight, '"px;  text-align: center;')
    }))), _$1("div", {
      id: "right_side"
    }, curLeaderbAr && curLeaderbAr[0].userName && _$1("div", null, _$1(Leaderboard, {
      leaderboard: curLeaderbAr,
      title: curLeaderbTitleText
    }), _$1("button", {
      "class": "switchLeadBtn",
      onClick: switchLeaderb
    }, curLeaderbBtnText))));
  };

  var Skin = function Skin2(_ref) {
    var name = _ref.name, title = _ref.title, description = _ref.description, earned = _ref.earned, selected = _ref.selected, onClick = _ref.onClick;
    return _$1("div", {
      "class": "skin ".concat(selected ? "selected" : "", " ").concat(earned ? "earned" : ""),
      onClick
    }, _$1("div", {
      "class": "skin-view"
    }, _$1("h3", null, title), _$1("img", {
      src: "".concat("assets", "/images/skins/").concat(name.toLowerCase().replace(/\s+/g, ""), ".png"),
      "class": earned ? "" : "grayscale"
    })), !earned && _$1("p", {
      "class": "skin-description"
    }, description), !earned && _$1("img", {
      src: "".concat("assets", "/images/lock.png"),
      "class": "earnedImg"
    }));
  };
  var SkinSelector = function SkinSelector2(_ref2) {
    var skins = _ref2.skins, skin = _ref2.skin, menu = _ref2.menu, setSkin = _ref2.setSkin;
    var _useContext = x(LanguageContext), lng = _useContext.lng;
    var ci = skins.findIndex(function(s) {
      return s.name === skin;
    });
    var _useState = d(0), _useState2 = _slicedToArray(_useState, 2), first = _useState2[0], setFirst = _useState2[1];
    var _useState3 = d(ci === -1 ? 0 : ci), _useState4 = _slicedToArray(_useState3, 2), current = _useState4[0], setCurrent = _useState4[1];
    var range = function range2(from, length) {
      var range3 = [];
      for (var i = 0; i < length; i++) {
        range3.push(from + i);
      }
      return range3;
    };
    var height = window.innerHeight;
    var count = height > 580 ? 6 : 3;
    var displayedSkins = range(first, count);
    return _$1("div", {
      "class": "skinbox"
    }, _$1("div", {
      "class": "skins-container"
    }, displayedSkins.map(function(index) {
      var skin2 = skins[index];
      return skin2 && _$1(Skin, {
        name: skin2.name || "noskin",
        title: skin2.title,
        description: skin2.description,
        earned: skin2.earned,
        selected: index === current,
        onClick: function onClick() {
          if (skin2.earned) {
            setCurrent(index);
          }
        }
      });
    })), _$1("div", {
      "class": "nav"
    }, _$1("button", {
      name: "left",
      "class": "orange",
      onClick: function onClick() {
        if (first >= count) {
          setFirst(first - count);
        }
      }
    }, "<"), _$1("button", {
      "class": "green",
      onClick: function onClick() {
        setSkin(skins[current].name);
        menu();
      }
    }, lng.btnSelect), _$1("button", {
      name: "right",
      "class": "orange",
      onClick: function onClick() {
        if (first < skins.length - count) {
          setFirst(first + count);
        }
      }
    }, ">")));
  };
  var Skins = function Skins2(_ref3) {
    var skins = _ref3.skins, skin = _ref3.skin, route = _ref3.route, setSkin = _ref3.setSkin, logo = _ref3.logo, unlockedSkins = _ref3.unlockedSkins;
    var menu = function menu2() {
      return route("menu");
    };
    var _useContext2 = x(LanguageContext), lng = _useContext2.lng;
    window.uiApi.curMenu = "shop";
    window.ads.hideAds && window.ads.hideAds();
    var skinsDescriptors = skins.filter(function(skin2) {
      return skin2.forceUnlock || unlockedSkins.some(function(u) {
        return u === skin2.name;
      });
    }).map(function(skin2) {
      return {
        name: skin2.name,
        title: lng.skinNames[skin2.name],
        earned: true,
        description: ""
      };
    });
    skinsDescriptors.unshift({
      name: "noskin",
      title: lng.skinNames.noskin,
      earned: true,
      description: ""
    });
    y(function() {
      window.HideAds && window.HideAds();
    }, []);
    return _$1(k$1, null, _$1("div", {
      id: "left_side"
    }), _$1("div", {
      "class": "uibox"
    }, _$1("div", {
      "class": "logo"
    }, _$1("img", {
      src: logo
    })), _$1(SkinSelector, {
      skins: skinsDescriptors,
      menu,
      setSkin,
      skin
    })), _$1("div", {
      id: "right_side"
    }));
  };

  var InGameLb = function InGameLb2(_ref) {
    var skins = _ref.skins, widthScreen = _ref.widthScreen, nameOfElement = _ref.nameOfElement, classDiv = _ref.classDiv, _ref$lineAm = _ref.lineAm, lineAm = _ref$lineAm === void 0 ? 5 : _ref$lineAm, _ref$widthPrc = _ref.widthPrc, widthPrc = _ref$widthPrc === void 0 ? 0.15 : _ref$widthPrc, _ref$widthMin = _ref.widthMin, widthMin = _ref$widthMin === void 0 ? 255 : _ref$widthMin, _ref$widthMax = _ref.widthMax, widthMax = _ref$widthMax === void 0 ? 265 : _ref$widthMax, _ref$minValueWidth = _ref.minValueWidth, minValueWidth = _ref$minValueWidth === void 0 ? 30 : _ref$minValueWidth, dataAr = _ref.dataAr, _ref$typeSort = _ref.typeSort, typeSort = _ref$typeSort === void 0 ? "money" : _ref$typeSort, _ref$namesProps = _ref.namesProps, namesProps = _ref$namesProps === void 0 ? ["money", "kills", "deaths"] : _ref$namesProps, _ref$iconProps = _ref.iconProps, iconProps = _ref$iconProps === void 0 ? ["money", "skull", "skullRed"] : _ref$iconProps;
    var _useContext = x(LanguageContext); _useContext.lng;
    var maxNameLength = 11;
    var offsetX = 0;
    var maxElemWidth = widthMax > widthScreen * widthPrc ? widthScreen * widthPrc : widthMax;
    var elemWidth = maxElemWidth > widthMin ? maxElemWidth : widthMin;
    var iconWidth = 20;
    var padding = 0;
    var lineHeight = 30;
    var style = {
      marginRight: "-".concat(offsetX * lineAm, "px"),
      width: "".concat(elemWidth, "px")
    };
    var iconStyle = {
      display: "flex",
      position: "relative",
      padding: padding + "px",
      height: iconWidth + "px",
      justifyContent: "center",
      marginTop: "".concat(-(iconWidth - lineHeight) * 0.5, "px"),
      paddingRight: "0px",
      minWidth: "".concat(minValueWidth + "px")
    };
    var linePropsStyle = {
      display: "flex",
      flexDirection: "row",
      justifyContent: "flex-end",
      width: "100%",
      height: "".concat(lineHeight, "px"),
      borderTopRightRadius: "0px",
      borderBottomRightRadius: "0px"
    };
    var lineIconsStyle = {
      display: "flex",
      justifyContent: "flex-end",
      width: "40%"
    };
    var playerBorder = "solid white 5px";
    var findInfoForSkin = function findInfoForSkin2(skin) {
      var skinInfo = skins.find(function(element) {
        return element.name == skin;
      });
      if (skinInfo)
        return skinInfo;
      else
        return {
          colors: {
            main: "#00000091",
            lbTextColor: "#ffffff"
          },
          icon: "noskin"
        };
    };
    return _$1("div", {
      id: nameOfElement,
      style,
      "class": classDiv + " inGame "
    }, _$1("div", {
      id: nameOfElement + "NameLine",
      "class": "backPlate",
      style: linePropsStyle
    }, _$1("div", {
      "class": "LineIcons",
      style: lineIconsStyle
    }, iconProps.map(function(prop, i) {
      return _$1("div", {
        id: nameOfElement + "IconBack",
        style: iconStyle,
        "class": "zeroPos noStretch"
      }, _$1("img", {
        id: nameOfElement + "LineIcon",
        width: iconWidth,
        height: iconWidth,
        src: "assets" + "/images/" + prop + ".png"
      }));
    }))), dataAr.map(function(userData, i) {
      return _$1(LbLine, {
        nameOfElement,
        color: findInfoForSkin(userData[1].skin).colors.main,
        textCol: findInfoForSkin(userData[1].skin).colors.lbTextColor,
        icon: findInfoForSkin(userData[1].skin).icon,
        place: userData[1].place + 1,
        widthScreen,
        classDiv,
        elemWidth,
        amount1: userData[1][namesProps[0]],
        amount2: userData[1][namesProps[1]],
        amount3: userData[1][namesProps[2]],
        border: userData[1].isPlayer === true ? playerBorder : "",
        minValueWidth,
        widthMin,
        marginLeftAdd: i < 5 ? offsetX * i : offsetX * 10,
        addedTopMargin: i < 5 ? 0 : 20,
        name: userData[1].nickName.length > maxNameLength ? userData[1].nickName.substring(0, maxNameLength) + "" : userData[1].nickName,
        amount: ~~userData[1][typeSort]
      });
    }));
  };
  var LbLine = function LbLine2(_ref2) {
    _ref2.widthScreen; var nameOfElement = _ref2.nameOfElement, classDiv = _ref2.classDiv, place = _ref2.place, name = _ref2.name, amount1 = _ref2.amount1, amount2 = _ref2.amount2, amount3 = _ref2.amount3, _ref2$color = _ref2.color, color = _ref2$color === void 0 ? "#00000091" : _ref2$color, _ref2$textCol = _ref2.textCol, textCol = _ref2$textCol === void 0 ? "#ffffff" : _ref2$textCol, _ref2$border = _ref2.border, border = _ref2$border === void 0 ? "" : _ref2$border, _ref2$addedTopMargin = _ref2.addedTopMargin, addedTopMargin = _ref2$addedTopMargin === void 0 ? 0 : _ref2$addedTopMargin, _ref2$icon = _ref2.icon, icon = _ref2$icon === void 0 ? null : _ref2$icon, _ref2$iconSize = _ref2.iconSize, iconSize = _ref2$iconSize === void 0 ? 20 : _ref2$iconSize, _ref2$marginLeftAdd = _ref2.marginLeftAdd, marginLeftAdd = _ref2$marginLeftAdd === void 0 ? 0 : _ref2$marginLeftAdd, _ref2$marginRightAdd = _ref2.marginRightAdd, marginRightAdd = _ref2$marginRightAdd === void 0 ? 0 : _ref2$marginRightAdd, _ref2$minWidthText = _ref2.minWidthText, minWidthText = _ref2$minWidthText === void 0 ? 115 : _ref2$minWidthText, _ref2$elemHeight = _ref2.elemHeight, elemHeight = _ref2$elemHeight === void 0 ? 32 : _ref2$elemHeight, _ref2$normFont = _ref2.normFont, normFont = _ref2$normFont === void 0 ? 15 : _ref2$normFont, _ref2$minValueWidth = _ref2.minValueWidth, minValueWidth = _ref2$minValueWidth === void 0 ? 40 : _ref2$minValueWidth, _ref2$elemWidth = _ref2.elemWidth, elemWidth = _ref2$elemWidth === void 0 ? 300 : _ref2$elemWidth;
    var nameText;
    var prop1 = "" + amount1;
    var prop2 = "" + amount2;
    var prop3 = "" + amount3;
    nameText = " " + name + " ";
    y(function() {
    });
    var iconWidth = iconSize;
    var padding = 5;
    var sidePadding = 5;
    var fontStyle = {
      fontSize: "".concat(normFont, "px"),
      textAlign: "center",
      marginTop: "".concat(-(normFont - elemHeight) * 0.5, "px"),
      lineHeight: "100%",
      color: "".concat(textCol)
    };
    var fontValueStyle = {
      fontSize: "".concat(normFont, "px"),
      textAlign: "center",
      marginTop: "".concat(-(normFont - elemHeight) * 0.5, "px"),
      lineHeight: "100%",
      color: "".concat(textCol),
      marginLeft: "".concat(-marginLeftAdd, "px"),
      minWidth: "".concat(minValueWidth + "px")
    };
    var textSideRight = {
      position: "relative",
      display: "flex",
      margin: "0px",
      marginLeft: "".concat(padding + 4, "px")
    };
    var elementStyle = {
      boxShadow: "3px 5px 0px 0px rgba(34, 60, 80, 0.2)",
      backgroundColor: color,
      display: "flex",
      justifyContent: "flex-start",
      borderRadius: "20px",
      borderTopRightRadius: "0px",
      borderBottomRightRadius: "0px",
      border,
      height: "".concat(elemHeight, "px"),
      width: "".concat(elemWidth, "px"),
      margin: "".concat(sidePadding, "px"),
      marginTop: "".concat(addedTopMargin, "px"),
      marginLeft: "".concat(marginLeftAdd, "px"),
      marginRight: "".concat(marginRightAdd, "px")
    };
    var rightSide = {
      justifyContent: "flex-end",
      width: "40%",
      display: "flex"
    };
    var leftSide = {
      display: "flex",
      width: "60%",
      minWidth: "".concat(minWidthText, "px")
    };
    var iconStyleRight = {
      position: "relative",
      padding: padding + "px",
      height: iconWidth + "px",
      marginTop: "".concat(-(iconWidth - elemHeight) * 0.25, "px"),
      paddingRight: "2px",
      paddingLeft: "2px"
    };
    return _$1("div", {
      id: nameOfElement,
      style: elementStyle,
      "class": classDiv + " inGame"
    }, _$1("div", {
      "class": "leftSide",
      style: leftSide
    }, _$1("div", {
      id: nameOfElement + "Text",
      style: textSideRight,
      "class": ""
    }, _$1("p", {
      style: fontStyle
    }, place), icon && _$1("div", {
      id: nameOfElement + "IconBack",
      style: iconStyleRight,
      "class": " zeroPos noStretch"
    }, _$1("img", {
      id: nameOfElement + "Icon",
      width: iconWidth,
      height: iconWidth,
      src: "assets" + "/images/skins/" + icon + ".png"
    }))), _$1("p", {
      style: fontStyle
    }, nameText)), _$1("div", {
      "class": "rightSide",
      style: rightSide
    }, _$1("p", {
      style: fontValueStyle
    }, prop1), _$1("p", {
      style: fontValueStyle
    }, prop2), _$1("p", {
      style: fontValueStyle
    }, prop3)));
  };

  var TwoTextWithIcon = function TwoTextWithIcon2(_ref) {
    var widthScreen = _ref.widthScreen, icon = _ref.icon, nameOfElement = _ref.nameOfElement; _ref.textOnLeft; var value = _ref.value, _ref$valueMax = _ref.valueMax, valueMax = _ref$valueMax === void 0 ? null : _ref$valueMax, _ref$widthPrc = _ref.widthPrc, widthPrc = _ref$widthPrc === void 0 ? 0.1 : _ref$widthPrc, _ref$widthMin = _ref.widthMin, widthMin = _ref$widthMin === void 0 ? 90 : _ref$widthMin, _ref$widthMax = _ref.widthMax, widthMax = _ref$widthMax === void 0 ? 120 : _ref$widthMax;
    var _useContext = x(LanguageContext); _useContext.lng;
    var result1TextShow;
    var result2TextShow;
    var maxAm = valueMax;
    if (maxAm !== null) {
      maxAm = maxAm == 999 ? "\u221E" : maxAm;
      result2TextShow = maxAm;
    }
    result1TextShow = value + "/";
    y(function() {
    });
    var elemHeight = 50;
    var maxElemWidth = widthMax > widthScreen * widthPrc ? widthScreen * widthPrc : widthMax;
    var elemWidth = maxElemWidth > widthMin ? maxElemWidth : widthMin;
    var iconWidth = 50;
    var padding = 5;
    var minWidthText = 60;
    var normFont = 35;
    var fontStyle = {
      fontSize: "".concat(normFont, "px"),
      textAlign: "center",
      marginTop: "".concat(-(normFont - elemHeight) * 0.5, "px"),
      lineHeight: "100%",
      marginLeft: "5px",
      color: "white"
    };
    var bigFont = 65;
    var fontStyleBig = {
      fontSize: "".concat(bigFont, "px"),
      textAlign: "center",
      marginLeft: "5px",
      marginTop: "".concat(-(bigFont - elemHeight) * 0.5, "px"),
      lineHeight: "100%",
      color: "white"
    };
    var textSideRight = {
      position: "relative",
      marginRight: "".concat(-padding * 3, "px"),
      minWidth: "".concat(minWidthText, "px")
    };
    var text2SideRight = {
      position: "relative",
      marginRight: "".concat(0, "px"),
      minWidth: "".concat(minWidthText, "px")
    };
    var elementStyle = {
      display: "flex",
      justifyContent: "flex-end",
      height: "".concat(elemHeight, "px"),
      width: "".concat(elemWidth + padding * 2, "px"),
      margin: "10px"
    };
    var iconStyleRight = {
      position: "relative",
      padding: padding + "px",
      height: iconWidth + "px"
    };
    var backForTextsStyle = {
      flexDirection: "row",
      display: "flex",
      justifyContent: "center",
      marginTop: "".concat(padding, "px"),
      marginRight: "".concat(padding, "px")
    };
    return _$1("div", {
      id: nameOfElement,
      style: elementStyle,
      "class": "rightC bottomC inGame"
    }, _$1("div", {
      id: nameOfElement + "BackTexts",
      style: backForTextsStyle,
      "class": "backPlate"
    }, _$1("div", {
      id: nameOfElement + "1Text",
      style: textSideRight,
      "class": ""
    }, _$1("p", {
      style: fontStyle
    }, result1TextShow)), _$1("div", {
      id: nameOfElement + "2Text",
      style: text2SideRight,
      "class": ""
    }, _$1("p", {
      style: fontStyleBig
    }, result2TextShow))), _$1("div", {
      id: nameOfElement + "IconBack",
      style: iconStyleRight,
      "class": "backPlate zeroPos noStretch"
    }, _$1("img", {
      id: nameOfElement + "Icon",
      width: iconWidth,
      height: iconWidth,
      src: "assets" + "/images/" + icon + ".png"
    })));
  };

  var HpandExpaBar = function HpandExpaBar2(_ref) {
    var widthScreen = _ref.widthScreen, curHpPrc = _ref.curHpPrc, newHpAm = _ref.newHpAm, updateShowHpPrc = _ref.updateShowHpPrc, maxHpAm = _ref.maxHpAm, curExpaPrc = _ref.curExpaPrc, newExpaAm = _ref.newExpaAm, updateShowExpaPrc = _ref.updateShowExpaPrc, maxExpaAm = _ref.maxExpaAm; _ref.isAlive; var _ref$skinIcon = _ref.skinIcon, skinIcon = _ref$skinIcon === void 0 ? "doge" : _ref$skinIcon;
    var _useState = d(curHpPrc), _useState2 = _slicedToArray(_useState, 2), hpPrc = _useState2[0], setHpPrc = _useState2[1];
    var _useState3 = d(curExpaPrc), _useState4 = _slicedToArray(_useState3, 2); _useState4[0]; var setExpaPrc = _useState4[1];
    var _useState5 = d(false), _useState6 = _slicedToArray(_useState5, 2); _useState6[0]; _useState6[1];
    var _useState7 = d(false), _useState8 = _slicedToArray(_useState7, 2); _useState8[0]; _useState8[1];
    var _useContext = x(LanguageContext); _useContext.lng;
    var resultTextNew = newHpAm;
    var resultTextMax = maxHpAm;
    var resultTextShow = " " + resultTextNew + "/" + resultTextMax;
    var expaTextNew = newExpaAm;
    var expaTextMax = maxExpaAm;
    var expaTextShow = " " + expaTextNew + "/" + expaTextMax;
    var tweenHp = function tweenHp2() {
      if (newHpAm === curHpPrc)
        return;
      var newPrc = newHpAm / maxHpAm * 100;
      if (!newPrc)
        newPrc = 0;
      setHpPrc(newPrc);
      updateShowHpPrc(newPrc);
    };
    var tweenExpa = function tweenExpa2() {
      if (newExpaAm === curExpaPrc)
        return;
      var newPrc = newExpaAm / maxExpaAm * 100;
      if (!newPrc)
        newPrc = 0;
      setExpaPrc(newPrc);
      updateShowExpaPrc(newPrc);
    };
    y(function() {
      tweenHp();
      tweenExpa();
    });
    var barHeight = 25;
    var maxBarWidth = 390 > widthScreen * 0.3 ? widthScreen * 0.3 : 390;
    var barWidth = maxBarWidth > 120 ? maxBarWidth : 120;
    var padding = 3;
    var skinWidth = barHeight * 2 + padding * 5 - 3;
    var hpIconSize = 20;
    var textSize = 21;
    var sideStyle = {
      marginLeft: "".concat(skinWidth + padding * 3, "px")
    };
    var textSide = {
      fontSize: "".concat(textSize, "px"),
      marginLeft: "".concat(padding * 7 + skinWidth + hpIconSize, "px"),
      color: "white"
    };
    var textSideLow = {
      fontSize: "".concat(textSize, "px"),
      marginLeft: "".concat(padding * 7 + skinWidth + hpIconSize, "px"),
      color: "white",
      top: "".concat(barHeight + padding * 2, "px"),
      position: "absolute",
      left: "0px"
    };
    var textInnerStyle = {
      lineHeight: "100%",
      marginTop: "".concat(hpIconSize * 0.5, "px")
    };
    var backBarsStyle = {
      position: "absolute",
      width: "calc(100% - ".concat(Math.abs(padding * 8 + hpIconSize + skinWidth), "px)")
    };
    var emptyBar = {
      position: "relative",
      width: "100%",
      height: "".concat(barHeight, "px"),
      left: "".concat(padding * 3 + hpIconSize * 1 + barWidth * 0, "px"),
      top: "".concat(barHeight * 0.5 - padding * 2, "px"),
      backgroundColor: "#081609",
      borderRadius: "10px"
    };
    var fullBar = {
      position: "relative",
      height: "".concat(barHeight, "px"),
      left: "".concat(padding * 3 + hpIconSize * 1 + barWidth * 0, "px"),
      top: "".concat(-barHeight * 1 + padding * 2, "px"),
      backgroundColor: "#0ab216",
      width: "".concat(hpPrc, "%"),
      borderRadius: "10px"
    };
    var emptyLowerBar = {
      position: "relative",
      width: "100%",
      height: "".concat(barHeight, "px"),
      left: "".concat(padding * 3 + hpIconSize * 1 + barWidth * 0, "px"),
      top: "".concat(barHeight * 1 + padding * 5, "px"),
      backgroundColor: "#081609",
      borderRadius: "10px"
    };
    var fullLowerBar = {
      position: "relative",
      height: "".concat(barHeight, "px"),
      left: "".concat(padding * 3 + hpIconSize * 1 + barWidth * 0, "px"),
      top: "".concat(barHeight * 0 + padding * 5, "px"),
      backgroundColor: "#0ab216",
      width: "".concat(hpPrc, "%"),
      borderRadius: "10px"
    };
    var hpBarStyle = {
      justifyContent: "center",
      height: "".concat(barHeight * 2 + padding * 4, "px"),
      width: "".concat(barWidth + padding * 2, "px"),
      minWidth: "250px",
      margin: "10px"
    };
    var hpHeartIconStyle = {
      position: "absolute",
      top: "".concat(hpIconSize * 0.5, "px"),
      left: "".concat(skinWidth + padding + hpIconSize * 0.5, "px")
    };
    var hpBarBack = {
      left: "".concat(skinWidth, "px"),
      height: "".concat(barHeight * 2 + padding * 6, "px")
    };
    var hpBarSkinBackStyle = {
      padding: padding + "px",
      height: skinWidth + "px"
    };
    var name = "hpExpaBar";
    var nameHp = "hpBar";
    var nameExpa = "expaBar";
    return _$1("div", {
      id: name,
      style: hpBarStyle,
      "class": "leftC bottomC inGame"
    }, _$1("div", {
      id: name + "AndText",
      style: sideStyle
    }, _$1("div", {
      id: name + "Back",
      style: hpBarBack,
      "class": "backPlate"
    }, _$1("img", {
      id: name + "HeartIcon",
      style: hpHeartIconStyle,
      width: hpIconSize,
      height: hpIconSize,
      src: "assets" + "/images/hp.png"
    }), _$1("div", {
      id: nameHp + "BarsBack",
      style: backBarsStyle
    }, _$1("div", {
      "class": "emptyBar",
      style: emptyBar
    }), _$1("div", {
      "class": "fullBar",
      style: fullBar
    })), _$1("div", {
      id: nameExpa + "BarsBack",
      style: backBarsStyle
    }, _$1("div", {
      "class": "emptyBar",
      style: emptyLowerBar
    }), _$1("div", {
      "class": "fullBar",
      style: fullLowerBar
    }))), _$1("div", {
      id: nameHp + "Text",
      style: textSide,
      "class": "zeroPos"
    }, _$1("p", {
      style: textInnerStyle
    }, resultTextShow)), _$1("div", {
      id: nameExpa + "Text",
      style: textSideLow
    }, _$1("p", {
      style: textInnerStyle
    }, expaTextShow))), _$1("div", {
      id: name + "SkinBack",
      style: hpBarSkinBackStyle,
      "class": "backPlate zeroPos noStretch"
    }, _$1("img", {
      id: name + "SkinIcon",
      width: skinWidth,
      height: skinWidth,
      src: "assets" + "/images/skins/" + skinIcon + ".png"
    })));
  };

  var KILL_LINE_TYPE = "killLine";
  var ICON_POPUP = "iconPopup";
  var ShooterGame = function ShooterGame2(_ref) {
    var skins = _ref.skins, skin = _ref.skin;
    var size = resizeToWindow();
    var _useState = d(0), _useState2 = _slicedToArray(_useState, 2), curKills = _useState2[0], setCurKills = _useState2[1];
    var _useState3 = d(0), _useState4 = _slicedToArray(_useState3, 2), curDeaths = _useState4[0], setCurDeaths = _useState4[1];
    var _useState5 = d(0), _useState6 = _slicedToArray(_useState5, 2), curPlayHp = _useState6[0], setCurPlayHp = _useState6[1];
    var _useState7 = d(0), _useState8 = _slicedToArray(_useState7, 2), curPlayExpa = _useState8[0]; _useState8[1];
    var _useState9 = d(0), _useState10 = _slicedToArray(_useState9, 2), curHpMax = _useState10[0], setCurHpMax = _useState10[1];
    var _useState11 = d(0), _useState12 = _slicedToArray(_useState11, 2), curExpaMax = _useState12[0]; _useState12[1];
    var _useState13 = d(0), _useState14 = _slicedToArray(_useState13, 2), curAmmo = _useState14[0], setCurAmmo = _useState14[1];
    var _useState15 = d(-1), _useState16 = _slicedToArray(_useState15, 2), timeCur = _useState16[0]; _useState16[1];
    var _useState17 = d(null), _useState18 = _slicedToArray(_useState17, 2); _useState18[0]; var setLastEventInfo = _useState18[1];
    //!lets notif mngr update!
    var _useState19 = d(false), _useState20 = _slicedToArray(_useState19, 2); _useState20[0]; var setNeedPopUp = _useState20[1];
    var _useState21 = d(false), _useState22 = _slicedToArray(_useState21, 2); _useState22[0]; var setKillLinesUpdate = _useState22[1];
    var _useState23 = d("money"), _useState24 = _slicedToArray(_useState23, 2), lbSortProp = _useState24[0]; _useState24[1];
    var _useState25 = d([]), _useState26 = _slicedToArray(_useState25, 2), sortedUsers = _useState26[0], setSortedUsers = _useState26[1];
    var _useState27 = d([]), _useState28 = _slicedToArray(_useState27, 2), notificationsKillsAr = _useState28[0], setNotificationsKillsAr = _useState28[1];
    var _useState29 = d([]), _useState30 = _slicedToArray(_useState29, 2), notificationsIconsAr = _useState30[0], setNotificationsIconsAr = _useState30[1];
    var _useState31 = d(window.uiApi.saveData.userId), _useState32 = _slicedToArray(_useState31, 2), overlayUserId = _useState32[0], setOverlayUserId = _useState32[1];
    var _useState33 = d(-1), _useState34 = _slicedToArray(_useState33, 2); _useState34[0]; _useState34[1];
    var _useState35 = d(curPlayHp / curHpMax * 100 || 0), _useState36 = _slicedToArray(_useState35, 2), curHpPrc = _useState36[0], setShowHpPrc = _useState36[1];
    var _useState37 = d(curPlayHp / curHpMax * 100 || 0), _useState38 = _slicedToArray(_useState37, 2); _useState38[0]; var setShowExpaPrc = _useState38[1];
    var updateDivs = function updateDivs2(newObj) {
      var userData = newObj.users[newObj.overlayUserId];
      sortUsers(lbSortProp, newObj.users);
      setOverlayUserId(newObj.overlayUserId);
      setCurPlayHp && setCurPlayHp(userData.hpCurrent);
      setCurHpMax && setCurHpMax(userData.hpMax);
      setCurAmmo(userData.ammoCurrent);
      setCurKills(userData.kills);
      setCurDeaths(userData.deaths);
    };
    window.uiApi.gameOverCustom = function(results, config) {
      var userData = window.uiApi.getCurData().users[window.uiApi.getCurData().overlayUserId];
      var timeAlive = 0;
      if (userData.deathTime) {
        timeAlive = userData.deathTime - userData.spawnTime;
      }
      console.log("Counted timeAlive:", timeAlive);
      results["timeAlive"] = timeAlive;
      results["play"] = 1;
      results["deaths"] = 1;
      config.resultPropNames.forEach(function(propName) {
        if (!results[propName]) {
          results[propName] = userData[propName];
          if (window.uiApi.getSaveData()[propName]) {
            results[propName] = window.uiApi.getSaveData()[propName];
          }
        }
        if (results[propName] === void 0)
          results[propName] = 0;
      });
      return results;
    };
    window.uiApi.killToast = function(killerID, victimID, weapon, isHeadshot) {
      if (killerID == void 0 || killerID == null || victimID == void 0 || victimID == null) {
        console.warn("Can't show kill toast - no id. KillerId:", killerID, ". VictimId", victimID);
        return;
      }
      var killerSkin = window.uiApi.getCurData().users[killerID].skin || "noskin";
      var victimSkin = window.uiApi.getCurData().users[victimID].skin || "noskin";
      if (killerID == window.uiApi.getCurData().overlayUserId) {
        window.uiApi.innerEventReact(ICON_POPUP, "", "", {
          killerID,
          weapon,
          isHeadshot
        });
      }
      window.uiApi.innerEventReact(KILL_LINE_TYPE, "side", "Kill", {
        killerID,
        killerSkin,
        victimID,
        victimSkin,
        weapon,
        isHeadshot
      });
    };
    window.uiApi.innerEventReact = function() {
      var type = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : "";
      var posClass = arguments.length > 1 && arguments[1] !== void 0 ? arguments[1] : "";
      var title = arguments.length > 2 && arguments[2] !== void 0 ? arguments[2] : "Title";
      var info = arguments.length > 3 && arguments[3] !== void 0 ? arguments[3] : {};
      if (!window.uiApi.notificationsToShow[type])
        window.uiApi.notificationsToShow[type] = [];
      var drawElement;
      switch (type) {
        case KILL_LINE_TYPE:
          setKillLinesUpdate(true);
          var killerNick = window.uiApi.getCurData().users[info.killerID].nickName;
          var victimNick = window.uiApi.getCurData().users[info.victimID].nickName;
          var maxNameLength = 11;
          killerNick = killerNick.length > maxNameLength ? killerNick.substring(0, maxNameLength) + "" : killerNick;
          victimNick = victimNick.length > maxNameLength ? victimNick.substring(0, maxNameLength) + "" : victimNick;
          drawElement = function drawElement2() {
            return _$1(ElementsLine, {
              nameOfElement: "killLine",
              icon1: "skins/" + info.killerSkin,
              icon2: "skins/" + info.victimSkin,
              widthScreen: size.width,
              text1: killerNick,
              text2: victimNick,
              btwIcon: info.weapon,
              elemHeight: 33
            });
          };
          break;
        case ICON_POPUP:
          setNeedPopUp(true);
          drawElement = function drawElement2() {
            return _$1(IconPopUp, {
              widthScreen: size.width || window.innerWidth,
              icon: "skull",
              classDiv: "inGame midMoveX",
              nameOfElement: "iconKill",
              value: "",
              iconSize: 30,
              sidePadding: 0,
              elemHeight: 40,
              addedTopMargin: 10,
              marginLeftAdd: 0,
              minWidthText: 0,
              normFont: 23,
              widthMin: 0,
              widthMax: 78
            });
          };
          break;
      }
      var id = uuid();
      window.uiApi.notificationsToShow[type].push({
        type,
        posClass,
        title,
        info,
        drawElement,
        id
      });
      console.log("add notification", id);
      switch (type) {
        case KILL_LINE_TYPE:
          setNotificationsKillsAr(window.uiApi.notificationsToShow[type]);
          break;
        case ICON_POPUP:
          setNotificationsIconsAr(window.uiApi.notificationsToShow[type]);
          break;
      }
      setLastEventInfo({
        type,
        posClass,
        title,
        info,
        id
      });
    };
    var sortUsers = function sortUsers2(lbSortProp2, usersObj) {
      var ar = Object.entries(usersObj);
      ar.sort(function(_ref2, _ref3) {
        var _ref4 = _slicedToArray(_ref2, 2), a = _ref4[1];
        var _ref5 = _slicedToArray(_ref3, 2), b = _ref5[1];
        if (a[lbSortProp2] > b[lbSortProp2]) {
          return -1;
        }
        if (a[lbSortProp2] < b[lbSortProp2]) {
          return 1;
        }
        return 0;
      });
      var posToCheck = 5;
      var hasPlayerInFirsts = false;
      ar.forEach(function(userData, i) {
        if (i < posToCheck) {
          if (userData[0] == overlayUserId) {
            hasPlayerInFirsts = true;
            userData[1].isPlayer = true;
            userData[1].skin = window.uiApi.saveData.skin;
          }
        }
        userData[1].place = i;
      });
      var shortAr = ar.splice(0, posToCheck);
      if (!hasPlayerInFirsts) {
        var playerInfo = ar.find(function(el) {
          return el[0] + "" == overlayUserId;
        });
        if (playerInfo) {
          playerInfo[1].isPlayer = true;
          playerInfo[1].skin = window.uiApi.saveData.skin;
          shortAr.push(playerInfo);
        }
      }
      setSortedUsers(shortAr);
      return shortAr;
    };
    window.uiApi.updateDivsCb = updateDivs;
    var killsStyle = {
      display: "flex",
      flexDirection: "row",
      marginTop: "-15px",
      marginLeft: "10px"
    };
    var getTime = function getTime2() {
      if (timeCur == -1)
        return "\u221E";
      return formatTime(timeCur);
    };
    var findInfoForSkin = function findInfoForSkin2(skin2) {
      var skinInfo = skins.find(function(element) {
        return element.name == skin2;
      });
      if (skinInfo)
        return skinInfo;
      else
        return {
          colors: {
            main: "#00000091",
            lbTextColor: "#ffffff"
          },
          icon: "noskin"
        };
    };
    return _$1("div", {
      id: "ingameUI",
      "class": "doClick"
    }, _$1("button", {
      "class": "purple sm noPadding centerYC",
      id: "menu",
      onClick: function onClick() {
        window.uiApi.setMenu("menu");
      }
    }, "Menu"), _$1("button", {
      "class": "purple sm noPadding y30C",
      id: "gameOver",
      onClick: function onClick() {
        window.uiApi.gameOverShow();
      }
    }, "Game Over"), _$1(HpandExpaBar, {
      widthScreen: size.width || window.innerWidth,
      skinIcon: findInfoForSkin(skin).icon,
      curHpPrc,
      updateShowHpPrc: setShowHpPrc,
      updateShowExpaPrc: setShowExpaPrc,
      newHpAm: curPlayHp,
      maxHpAm: curHpMax,
      newExpaAm: curPlayExpa,
      maxExpaAm: curExpaMax
    }), _$1(TwoTextWithIcon, {
      widthScreen: size.width || window.innerWidth,
      icon: "ammo",
      nameOfElement: "ammo",
      classDiv: "rightC bottomC inGame",
      value: curAmmo,
      valueMax: 999,
      textOnLeft: false
    }), _$1("div", {
      id: "leftTopCornerUi",
      "class": "leftC topC"
    }, _$1(IconText, {
      widthScreen: size.width || window.innerWidth,
      normFont: getTime() === "\u221E" ? 75 : 35,
      icon: "timeIcon",
      classDiv: "backPlate inGame",
      nameOfElement: "time",
      iconSize: 40,
      widthMin: 160,
      widthMax: 160,
      value: getTime()
    }), _$1("div", {
      style: killsStyle
    }, _$1(IconText, {
      widthScreen: size.width || window.innerWidth,
      icon: "skull",
      classDiv: "backPlate inGame",
      nameOfElement: "kills",
      value: curKills,
      iconSize: 30,
      elemHeight: 40,
      addedTopMargin: 10,
      marginLeftAdd: 0,
      minWidthText: 40,
      normFont: 23,
      widthMin: 78,
      widthMax: 78
    }), _$1(IconText, {
      widthScreen: size.width || window.innerWidth,
      icon: "skullRed",
      classDiv: "backPlate inGame",
      nameOfElement: "deaths",
      value: curDeaths,
      iconSize: 30,
      elemHeight: 40,
      addedTopMargin: 10,
      minWidthText: 40,
      marginLeftAdd: -5,
      normFont: 23,
      widthMin: 78,
      widthMax: 78
    })), (notificationsKillsAr.length > 0 || window.uiApi.notificationsToShow && window.uiApi.notificationsToShow[KILL_LINE_TYPE] && window.uiApi.notificationsToShow[KILL_LINE_TYPE].length > 0) && _$1(NotificationMngr, {
      type: KILL_LINE_TYPE,
      arrayData: window.uiApi.notificationsToShow[KILL_LINE_TYPE],
      notificationsAr: notificationsKillsAr,
      updateNotificationAr: setNotificationsKillsAr,
      maxLines: 3,
      classDiv: "",
      animTime: 2,
      replaceCurrent: false
    })), _$1("div", {
      "class": "rightC topC"
    }, _$1(InGameLb, {
      skins,
      widthScreen: size.width || window.innerWidth,
      nameOfElement: "inGameLb",
      classDiv: "",
      dataAr: sortedUsers
    })), _$1("div", {
      "class": "centerXC topC"
    }, (notificationsIconsAr.length > 0 || window.uiApi.notificationsToShow && window.uiApi.notificationsToShow[ICON_POPUP] && window.uiApi.notificationsToShow[ICON_POPUP].length > 0) && _$1(NotificationMngr, {
      type: ICON_POPUP,
      arrayData: window.uiApi.notificationsToShow[ICON_POPUP],
      notificationsAr: notificationsIconsAr,
      updateNotificationAr: setNotificationsIconsAr,
      maxLines: 1,
      classDiv: "",
      waitHide: 1,
      animTime: 0.5,
      replaceCurrent: false
    })));
  };

  var TOP_POP_UP = "topPopUp";
  var IN_GAME_NOTIFICATION = "in_game_notification";
  var App = function App2(_ref) {
    var skins = _ref.skins, serverParser = _ref.serverParser, saveLeaderboard = _ref.saveLeaderboard, config = _ref.config, doSave = _ref.doSave, loadedData = _ref.loadedData;
    var savedLanguage = "en";
    var size = resizeToWindow();
    window.uiApi.getSaveData = function() {
      return window.uiApi.saveData;
    };
    window.uiApi.setSaveData = function(data) {
      var newBest = false;
      if (data[config.resultPropNames[1]]) {
        if (window.uiApi.getSaveData()[config.resultPropNames[1]] < data[config.resultPropNames[1]])
          newBest = true;
        else
          newBest = false;
      }
      var newData = Object.assign(window.uiApi.getSaveData(), data);
      newData.newBest = newBest;
      window.uiApi.saveData = newData;
      setSavesData && setSavesData(newData);
      serverParser.updateSaves(newData);
    };
    var _useState = d(getLanguageByName(savedLanguage) || getDefaultLanguage()), _useState2 = _slicedToArray(_useState, 2), language = _useState2[0]; _useState2[1];
    var externalSaveData = loadedData;
    var _useState3 = d(externalSaveData || window.uiApi.saveData), _useState4 = _slicedToArray(_useState3, 2), savesData = _useState4[0], setSavesData = _useState4[1];
    var _useState5 = d(window.uiApi.curData || config.curData), _useState6 = _slicedToArray(_useState5, 2), curData = _useState6[0], setCurData = _useState6[1];
    var _useState7 = d(true), _useState8 = _slicedToArray(_useState7, 2); _useState8[0]; _useState8[1];
    var _useState9 = d(serverParser.curLeaderbType), _useState10 = _slicedToArray(_useState9, 2), curLeaderbType = _useState10[0], setCurLeaderbType = _useState10[1];
    var _useState11 = d(serverParser.curLeaderbData), _useState12 = _slicedToArray(_useState11, 2), curLeaderbData = _useState12[0], setCurLeaderbData = _useState12[1];
    serverParser.setCurLeaderbType = setCurLeaderbType;
    serverParser.setCurLeaderbData = setCurLeaderbData;
    var _useState13 = d(externalSaveData || window.uiApi.saveData), _useState14 = _slicedToArray(_useState13, 2), resultsData = _useState14[0], setResultsData = _useState14[1];
    var _useState15 = d(window.uiApi.playableFromStart), _useState16 = _slicedToArray(_useState15, 2), playable = _useState16[0], setPlayable = _useState16[1];
    var _useState17 = d(true), _useState18 = _slicedToArray(_useState17, 2), preparing = _useState18[0]; _useState18[1];
    var _useState19 = d(false), _useState20 = _slicedToArray(_useState19, 2), wasRewarded = _useState20[0]; _useState20[1];
    var _useState21 = d(config.saveTemplate.map), _useState22 = _slicedToArray(_useState21, 2), mode = _useState22[0], setMode = _useState22[1];
    var _useState23 = d([]), _useState24 = _slicedToArray(_useState23, 2), notificationsAr = _useState24[0], setNotificationsAr = _useState24[1];
    var _useState25 = d(null), _useState26 = _slicedToArray(_useState25, 2); _useState26[0]; var setLastEventInfo = _useState26[1];
    //!lets notif mngr update!
    var _useState27 = d("menu"), _useState28 = _slicedToArray(_useState27, 2), uiStateName = _useState28[0], setUiStateName = _useState28[1];
    var _useState29 = d(false), _useState30 = _slicedToArray(_useState29, 2); _useState30[0]; _useState30[1];
    language.name === "ru";
    window.uiApi.setCurData = function(dataObj) {
      var newObj = _mergeDeep$1(window.uiApi.getCurData() || {}, dataObj);
      window.uiApi.curData = newObj;
      window.uiApi.updateDivsCb && window.uiApi.updateDivsCb(newObj);
      setCurData(newObj);
    };
    window.uiApi.updateCurDataFromUi = function(data) {
      window.uiApi.setCurData(data);
      window.uiApi.curDataInGameUpdate && window.uiApi.curDataInGameUpdate(data);
    };
    window.uiApi.getCurData = function() {
      return window.uiApi.curData;
    };
    window.uiApi.setMenu = function(name) {
      window.uiApi.curMenu = name;
      if (name == "game") {
        var gameUI = document.getElementById("gameUI");
        gameUI.classList.remove("doClick");
        gameUI.classList.add("noClick");
      } else {
        var ingameUI = document.getElementById("gameUI");
        ingameUI.classList.add("doClick");
        ingameUI.classList.remove("noClick");
      }
      setUiStateName(name);
    };
    window.uiApi.getEvent = function() {
      var type = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : "";
      var posClass = arguments.length > 1 && arguments[1] !== void 0 ? arguments[1] : "";
      var title = arguments.length > 2 && arguments[2] !== void 0 ? arguments[2] : "Title";
      var info = arguments.length > 3 && arguments[3] !== void 0 ? arguments[3] : [];
      window.uiApi.innerEventReact && window.uiApi.innerEventReact(type, posClass, title, info);
    };
    window.uiApi.gameOverCustom = function(results) {
      var saveDataObj = Object.assign({}, window.uiApi.getSaveData());
      config.bestProps.forEach(function(propAr) {
        var propName = propAr[1];
        var propBestName = propAr[0];
        if (results[propName]) {
          var oldVal = window.uiApi.getSaveData()[propBestName] || 0;
          var newVal = results[propName];
          if (newVal > oldVal) {
            saveDataObj[propBestName] = newVal;
          }
          results[propBestName] = saveDataObj[propBestName];
        }
      });
      config.accumProps.forEach(function(propAr) {
        var propName = propAr[1];
        var propAllName = propAr[0];
        if (results[propName]) {
          var oldVal = window.uiApi.getSaveData()[propAllName] || 0;
          var newVal = parseFloat(results[propName]);
          var sumVal = oldVal + newVal;
          saveDataObj[propAllName] = sumVal;
          saveDataObj[propName] = results[propName];
        }
      });
      window.uiApi.setSaveData(saveDataObj);
      unlockLevels(config);
      return results;
    };
    window.uiApi.gameOverShow = function() {
      var results = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : {};
      results = Object.assign(results, window.uiApi.getCurData());
      results = window.uiApi.gameOverCustom(results, config);
      setResultsData(results);
      saveLeaderboard(nickName, results, function() {
      }, function() {
        console.log("ERROR save leaderboard");
      });
      window.uiApi.setMenu && window.uiApi.setMenu("results");
    };
    window.uiApi.getStartData = function() {
      var obj = {};
      config.startProps.forEach(function(prop) {
        obj[prop] = window.uiApi.getSaveData()[prop];
      });
      return obj;
    };
    window.uiApi.togglePlayable = function(on) {
      setPlayable(on);
    };
    window.uiApi.initGame = function(saveUpdateInGame, getCurDataInGame, gameStartMethod) {
      window.uiApi.startGame = function() {
        gameStartMethod(window.uiApi.getSaveData());
      };
      window.uiApi.curDataInGameUpdate = getCurDataInGame;
      window.uiApi.gameSaveUpdate = saveUpdateInGame;
      window.initAds();
      return window.uiApi.getSaveData();
    };
    var setRawMap = function setRawMap2(map) {
      setMode(map);
      window.uiApi.setSaveData && window.uiApi.setSaveData({
        map
      });
      window.uiApi.customModeCb && window.uiApi.customModeCb(map);
    };
    var _useState31 = d(savesData.nickName || ""), _useState32 = _slicedToArray(_useState31, 2), nickName = _useState32[0], setRawNickName = _useState32[1];
    var setNickName = function setNickName2(newName) {
      setRawNickName(newName);
      window.uiApi.setSaveData && window.uiApi.setSaveData({
        nickName: newName
      });
    };
    var _useState33 = d(savesData.skin || ""), _useState34 = _slicedToArray(_useState33, 2), skin = _useState34[0], setRawSkin = _useState34[1];
    var setSkin = function setSkin2(newSkin) {
      setRawSkin(newSkin);
      console.log("!!Set new skin", newSkin);
      window.uiApi.setSaveData && window.uiApi.setSaveData({
        skin: newSkin
      });
    };
    var _useState35 = d(savesData.bestScore || 0), _useState36 = _slicedToArray(_useState35, 2), bestScore = _useState36[0]; _useState36[1];
    if (nickName !== savesData.nickName || bestScore !== savesData.bestScore || skin !== savesData.skin) {
      doSave && doSave({
        nickName,
        skin,
        bestScore
      });
    }
    var callRewardAds = function callRewardAds2() {
    };
    y(function() {
    }, []);
    var getGameUi = function getGameUi2(gameType, curData2) {
      if (!curData2)
        return;
      switch (gameType) {
        case "paper":
          return _$1(Paper3Game, {
            skins,
            skin,
            config
          });
        case "shooter":
          return _$1(ShooterGame, {
            skins,
            skin,
            config
          });
      }
    };
    window.uiApi.basicEventReact = function() {
      var type = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : "";
      var posClass = arguments.length > 1 && arguments[1] !== void 0 ? arguments[1] : "";
      var title = arguments.length > 2 && arguments[2] !== void 0 ? arguments[2] : "Title";
      var info = arguments.length > 3 && arguments[3] !== void 0 ? arguments[3] : {};
      if (type != TOP_POP_UP)
        return;
      if (!window.uiApi.notificationsToShow[type])
        window.uiApi.notificationsToShow[type] = [];
      var drawElement;
      switch (type) {
        case TOP_POP_UP:
          drawElement = function drawElement2() {
            return _$1(PositionBlock, {
              minWidth: 250
            }, _$1(ElementsLine, {
              nameOfElement: "newMapNotif",
              icon1: null,
              widthScreen: size.width,
              text1: title,
              elemHeight: 33,
              justifyContent: "center",
              classDiv: "inGame midMoveX backPlate",
              widthMax: 250
            }));
          };
          break;
      }
      var id = uuid();
      window.uiApi.notificationsToShow[type].push({
        type,
        posClass,
        title,
        info,
        drawElement,
        id
      });
      setNotificationsAr(window.uiApi.notificationsToShow[type]);
      console.log("add notification", id);
      setLastEventInfo({
        type,
        posClass,
        title,
        info,
        id
      });
    };
    var adsOrGameStart = function adsOrGameStart2() {
      window.ads.showPreroll && window.ads.showPreroll();
      window.ads.hideAds && window.ads.hideAds();
      window.uiApi.setMenu("game");
    };
    var uiNormStyle = {
      display: "flex",
      justifyContent: "flex-start",
      flexDirection: "row",
      alignItems: "flex-start",
      alignContent: "flex-start",
      flexWrap: "nowrap"
    };
    var uiMobileStyle = {
      display: "flex",
      justifyContent: "flex-start",
      flexDirection: "column",
      alignItems: "flex-start",
      alignContent: "center",
      flexWrap: "wrap"
    };
    var needMobileUi = function needMobileUi2() {
      if (window.innerWidth < 800 && uiStateName != "game")
        return true;
      return false;
    };
    var logo = "".concat("assets", "/images/logo.png");
    return _$1(k$1, null, uiStateName !== "game" && _$1("div", {
      id: "darkOverlayUI"
    }), _$1(LanguageContext.Provider, {
      value: language
    }, _$1("div", {
      id: "ui",
      style: needMobileUi() ? uiMobileStyle : uiNormStyle
    }, " ", uiStateName === "menu" && _$1(Menu, {
      config,
      nickName,
      setNickName,
      playable,
      preparing,
      modeSelect: config.modeSelect,
      setMode: setRawMap,
      currentMode: mode,
      skin,
      startGame: adsOrGameStart,
      setState: window.uiApi.setMenu,
      curLeaderbAr: curLeaderbData,
      curLeaderbType,
      switchLeaderb: serverParser.switchLeaderb,
      logo
    }), uiStateName === "game" && getGameUi("paper", curData), uiStateName === "results" && _$1(Results, {
      nickName,
      results: resultsData,
      curLeaderbAr: curLeaderbData,
      curLeaderbType,
      switchLeaderb: serverParser.switchLeaderb,
      setResults: setResultsData,
      config,
      wasRewarded,
      startGame: adsOrGameStart,
      callRewardAds,
      setState: window.uiApi.setMenu,
      skin,
      logo
    }), uiStateName === "skins" && _$1(Skins, {
      config,
      skins,
      skin,
      route: window.uiApi.setMenu,
      setSkin,
      logo,
      unlockedSkins: []
    })), _$1("div", {
      "class": "centerXC topC topZ"
    }, (notificationsAr.length > 0 || window.uiApi.notificationsToShow && window.uiApi.notificationsToShow[TOP_POP_UP] && window.uiApi.notificationsToShow[TOP_POP_UP].length > 0) && _$1(NotificationMngr, {
      type: TOP_POP_UP,
      arrayData: window.uiApi.notificationsToShow[TOP_POP_UP],
      notificationsAr,
      updateNotificationAr: setNotificationsAr,
      maxLines: 1,
      classDiv: "appNotif",
      waitHide: 5,
      animTime: 0.5,
      replaceCurrent: false
    }))), _$1("div", {
      id: "overlay"
    }));
  };

  var expires = {
    expires: 365
  };
  var SAVE_API_NAME = "api.gameads.io";
  var LEADER_API_NAME = "topgamedata.com";
  var ServerParser = /* @__PURE__ */ function() {
    function ServerParser2(config) {
      var _this = this;
      _classCallCheck(this, ServerParser2);
      _defineProperty(this, "checkId", function() {
        if (_this.localSaveProfile["userId"] && _this.localSaveProfile["userId"] != 0) {
          window.player_id = _this.localSaveProfile["userId"];
        }
        if (!window.player_id) {
          window.player_id = ~~(Math.random() * 9999999);
        }
      });
      _defineProperty(this, "loadAllLbs", function() {
        _this.config.lbTypes.forEach(function(lbName) {
          _this.getTypeOfLeaderboard(lbName, _this.parseLeaderboardData);
        });
      });
      _defineProperty(this, "requestSave", function() {
        var cb = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : null;
        var data = _this.getUniversalSave();
        requestAPI("https://" + SAVE_API_NAME + "/save-progress.php", {
          gameCode: "PAPER3D",
          userId: window.player_id,
          gameData: data
        }, cb);
      });
      _defineProperty(this, "requestLoad", function() {
        var cbSuccess = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : null;
        var cbError = arguments.length > 1 && arguments[1] !== void 0 ? arguments[1] : null;
        requestAPI("https://" + SAVE_API_NAME + "/load-progress.php", {
          gameCode: "PAPER3D",
          userId: window.player_id
        }, cbSuccess, cbError);
      });
      _defineProperty(this, "setFromServerData", function(serverSave) {
        if (!serverSave)
          return;
        window.uiApi.firstServerUpdateDone = true;
        serverSave = JSON.parse(serverSave);
        if (typeof serverSave == "undefined") {
          return;
        }
        if (!window.uiApi.serverGameData) {
          window.uiApi.serverGameData = {};
        }
        Object.assign(window.uiApi.serverGameData, serverSave);
        clog(window.uiApi.serverGameData);
      });
      _defineProperty(this, "getUniversalSave", function() {
        var saveProfile = _this.localSaveProfile;
        var localObj = localStorageApi.getJSON(window.uiApi.localStorageName);
        if (_this.config.useServerSave && !window.uiApi.needUpdateSaveFromLocal && window.uiApi.serverGameData) {
          saveProfile = window.uiApi.serverGameData;
        } else if (localObj && isEmpty(localObj) == false) {
          saveProfile = localStorageApi.getJSON(window.uiApi.localStorageName);
          _this.checkId();
        } else {
          saveProfile = _this.emptySave();
        }
        return saveProfile;
      });
      _defineProperty(this, "emptySave", function() {
        if (!window.player_id || window.player_id == 0)
          window.player_id = ~~(Math.random() * 9999999);
        window.uiApi.saveData.userId = window.player_id;
        return window.uiApi.saveData;
      });
      _defineProperty(this, "checkSaveOkOrRetry", function(data) {
        var obj = JSON.parse(data);
        if (typeof obj != "undefined" && obj && typeof obj.result != "undefined") {
          if (obj.result == "ok") {
            window.uiApi.needUpdateSaveFromLocal = false;
          } else if (obj.result != "ok") {
            _this.requestSave(_this.checkSaveOkOrRetry);
          }
        }
      });
      _defineProperty(this, "updateSaves", function(newDataObj) {
        _this.updateSavesLocal(newDataObj);
        window.uiApi.callServerSave();
      });
      _defineProperty(this, "updateSavesLocal", function(newDataObj) {
        var saveProfile = localStorageApi.getJSON(window.uiApi.localStorageName);
        if (isEmpty(saveProfile)) {
          saveProfile = _this.getDefSaveObj();
        }
        Object.assign(saveProfile, newDataObj);
        var _saveProfile = saveProfile, userId = _saveProfile.userId; _saveProfile.nickName; _saveProfile.skin;
        if (!userId || userId == -1) {
          userId = saveProfile.userId;
          if (!userId || userId == -1) {
            if (window.player_id)
              userId = window.player_id;
            else {
              userId = window.player_id = ~~(Math.random() * 9999999);
            }
          }
        }
        window.uiApi.needUpdateSaveFromLocal = true;
        localStorageApi.set(window.uiApi.localStorageName, saveProfile, expires);
      });
      _defineProperty(this, "saveLeaderboard", function(nickName, results, cbSuccess, cbError) {
        if (nickName == "" || !nickName) {
          nickName = _this.localSaveProfile.nickName;
        }
        if (nickName == "" || !nickName) {
          nickName = "\u0421\u0430\u0448\u0430";
        }
        var resultsAr = [];
        var saveVal = 0;
        _this.config.lbTypes.forEach(function(lbName) {
          switch (lbName) {
            case "score":
              saveVal = parseInt(results.score * 100 || 0);
              break;
            case "money":
              saveVal = parseInt(results.money || 0);
              break;
            case "time":
              saveVal = parseInt(results.timeAlive || 0);
              break;
            case "kills":
              saveVal = parseInt(results.kills || 0);
              break;
          }
          resultsAr.push({
            leaderboardType: lbName,
            leaderboardValue: saveVal
          });
        });
        requestAPI("https://" + LEADER_API_NAME + "/save", {
          gameCode: "PAPER3D",
          userId: window.player_id,
          userName: nickName,
          results: resultsAr
        }, cbSuccess, cbError, true);
      });
      _defineProperty(this, "getTypeOfLeaderboard", function() {
        var type = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : "money";
        var cb = arguments.length > 1 ? arguments[1] : void 0;
        var nameGame = _this.config.leaderboardName;
        var name = "/json/" + nameGame + "_" + type + "_1";
        return getReq("https://" + LEADER_API_NAME + name + ".json", cb, type);
      });
      _defineProperty(this, "parseLeaderboardData", function(newData, type) {
        var dataAr = JSON.parse(newData);
        dataAr = dataAr.slice(0, 10);
        _this.leaderboardsObjData[type] = dataAr;
        _this.loadCurLeaderboard();
        return dataAr;
      });
      _defineProperty(this, "loadCurLeaderboard", function() {
        _this.curLeaderbData = _this.leaderboardsObjData[_this.curLeaderbType];
        _this.setCurLeaderbData && _this.setCurLeaderbData(_this.curLeaderbData);
      });
      _defineProperty(this, "switchLeaderb", function() {
        var curIndx = _this.config.lbTypes.indexOf(_this.curLeaderbType);
        var nextNameIndx = curIndx >= _this.config.lbTypes.length - 1 ? 0 : curIndx + 1;
        var nextLbName = _this.config.lbTypes[nextNameIndx];
        _this.curLeaderbType = nextLbName;
        _this.setCurLeaderbType && _this.setCurLeaderbType(_this.curLeaderbType);
        _this.loadCurLeaderboard();
      });
      this.curLeaderbData = null;
      this.curLeaderbType = "kills";
      this.leaderboardsObjData = null;
      this.config = config;
      var localSaveProfile = localStorageApi.getJSON(config.storageName) || {};
      this.localSaveProfile = localSaveProfile;
      window.uiApi.doServerLoad = function() {
        _this.checkId();
        return _this.requestLoad(_this.setFromServerData, function(data) {
          return clog();
        });
      };
      window.uiApi.callServerSave = function() {
        {
          try {
            _this.requestSave(_this.checkSaveOkOrRetry);
          } catch (e) {
            console.warn("Saving results to server failed", e);
          }
        }
      };
      if (config.useServerSave)
        window.uiApi.doServerLoad();
      if (!this.leaderboardsObjData && !isMobile() && !window["location"]["host"] == "localhost:5000") {
        this.leaderboardsObjData = {};
        this.loadAllLbs();
      }
    }
    return _createClass(ServerParser2, [{
      key: "getDefSaveObj",
      value: function getDefSaveObj() {
        return window.uiApi.saveData || this.config.saveTemplate;
      }
    }]);
  }();

  var modeSelectP3 = {
    unlocksPrc: {
      "cube": 0,
      "cruash": 0,
      "duck": 0,
      "star": 0,
      "cupcake": 0,
      "heart": 0,
      "lightbulb": 0
    },
    list: ["cube", "cruash", "duck", "star", "cupcake", "heart", "lightbulb"],
    unlocksConditions: {
      "cube": {
        type: "prevMap",
        "value": 0
      },
      "cruash": {
        type: "prevMap",
        "value": 5
      },
      "duck": {
        type: "prevMap",
        "value": 10
      },
      "star": {
        type: "prevMap",
        "value": 15
      },
      "cupcake": {
        type: "prevMap",
        "value": 20
      },
      "heart": {
        type: "prevMap",
        "value": 25
      },
      "lightbulb": {
        type: "prevMap",
        "value": 30
      }
    },
    models: [{
      "label": "cube",
      "name": "0-cube"
    }, {
      "label": "cruash",
      "name": "1-cruash"
    }, {
      "label": "duck",
      "name": "3-duck-eq"
    }, {
      "label": "star",
      "name": "6-star-eq"
    }, {
      "label": "cupcake",
      "name": "7-cupcake-eq"
    }, {
      "label": "heart",
      "name": "8-heart-eq"
    }, {
      "label": "lightbulb",
      "name": "12-lightbulb-eq"
    }]
  };
  var resultPropNamesP3 = ["score", "best", "timeAlive", "kills"];
  var startPropNamesP3 = ["nickName", "skin", "map", "best"];
  var propsToAccumulatePaper3 = [["allScore", "score"], ["allKills", "kills"]];
  var propsWithBestP3 = [["best", "score"], ["killsBest", "kills"], ["timeBest", "time"]];
  var emptySaveP3 = {
    nickName: "Player",
    language: "en",
    skin: 0,
    userId: window.player_id || 0,
    timeBest: 0,
    killsBest: 0,
    scoreBest: 0,
    allScore: 0,
    allKills: 0,
    allDeaths: 0,
    allTimes: 0,
    allPlays: 0,
    map: "cube",
    lastUnlockedMap: "cube",
    mapsBestPrc: {
      cube: 0,
      cruash: 0,
      duck: 0,
      star: 0,
      cupcake: 0,
      heart: 0,
      lightbulb: 0
    },
    mapsAllPrc: {
      cube: 0,
      cruash: 0,
      duck: 0,
      star: 0,
      cupcake: 0,
      heart: 0,
      lightbulb: 0
    }
  };
  var curUserDataP3 = {
    nickName: "Player",
    skin: "",
    best: 0,
    spawnTime: 0,
    deathTime: 0,
    kills: 0,
    lastAdded: 0,
    overlayUserId: 0
  };
  var gameSettingsP3 = {
    skins: null
  };

  var resultPropNamesShooter = ["money", "moneyBest", "timeAlive", "kills"];
  var startPropNamesShooter = ["nickName", "skin", "userId"];
  var propsToAccumulateShooter = [["allMoney", "money"], ["allKills", "kills"], ["allDeaths", "deaths"], ["allTimes", "timeAlive"], ["allPlays", "play"]];
  var propsWithBestShooter = [["expaBest", "expa"], ["moneyBest", "money"], ["killsBest", "kills"], ["timeBest", "time"]];
  var emptySaveShooter = {
    nickName: "Player",
    language: "en",
    skin: 0,
    userId: window.player_id || 0,
    timeBest: 0,
    killsBest: 0,
    moneyBest: 0,
    allMoney: 0,
    allKills: 0,
    allDeaths: 0,
    allTimes: 0,
    allPlays: 0
  };
  var curUserDataShooter = {
    nickName: "Player",
    skin: "",
    gun: "",
    isAlive: 0,
    deaths: 0,
    kills: 0,
    money: 0,
    spawnTime: 0,
    deathTime: 0,
    hpCurrent: 0,
    hpMax: 100,
    ammoCurrent: 0,
    ammoMax: 100,
    lvl: 0,
    expCurrent: 0,
    expMax: 0,
    timeAlive: 0,
    roundTimeStart: 0,
    roundTimeMax: -1,
    overlayUserId: 0,
    users: {},
    curSortLbType: "money",
    sortedUsers: []
  };
  var gameSettingsSh = {};

  var createApi = function createApi2(templateForSaves, nickNames) {
    window.uiApi = {
      fireworks: null,
      effectsCanvas: document.getElementById("uiEffectCanvas"),
      startGame: null,
      setMenu: function setMenu() {
      },
      curMenu: "",
      initGame: null,
      gameOverShow: null,
      setSaveData: function setSaveData(newSave) {
        var newData = Object.assign(templateForSaves, newSave);
        window.uiApi.saveData = newData;
      },
      setCurData: function setCurData(ingameData) {
      },
      getSaveData: function getSaveData() {
        return window.uiApi.saveData;
      },
      curData: null,
      saveData: templateForSaves,
      gameSaveUpdate: null,
      curDataInGameUpdate: null,
      nickNames,
      ingame: {},
      notificationsToShow: [],
      togglePlayable: function togglePlayable() {
        var on = arguments.length > 0 && arguments[0] !== void 0 ? arguments[0] : true;
        return window.uiApi.playableFromStart = on;
      },
      playableFromStart: false,
      innerEventReact: null
    };
  };

  var names = "hi\nlol\n.\npro\nBOB\nMe\nTifo\nking\na\nhello\n:)\nQueen\nyour name\nE\nIndia\nkiller\nm\n123\nNO ME MATES\nnoob\npoop\nSus\nimposter\nk\nimpostor\n...\nXD\nwinner\nPAPER\nunicorn\nSub2SSundee\nDont kill me\nAmong us\nh\nNo\nok\nUwU\ngg\nYo\njelly\nidk\nlily\nD\n1\nBts\nangel\nJ\nCAT\nRainbow\no\nssundee\nHacker\nWATERMELON\nAlex\nMax\nS\nlove\nemma\nb\ncoco\nl\nJess\nbb\ntom\ng\nboss\nyou\nGOD\nkk\nash\nsam\nxxx\nbruh\nyeet\npakistan\nisa\nwojan\nLUCAS\nThanos\nz\nI\njo\nYour Mom\npizza\nP\nsara\nname\nr\nCOVID-19\nPennywise\nBella\nUSA\nJJ\nt\ncake\nJojo\namogus\nLisa\nrose\nur mom\nEmily\nmimi\nBOi\njulia\nbanana\nNINJA\nred\nnaruto\ngabriel\nhehe\nLULU\nava\n3\nnyan cat\nnick\nMobileNation\n0\nf\nDaniel\nlevi\nethan\nAdam\nhey\nDream\nZoe \nfgteev\nbite\nLadybug\nella\nKiki\nben\nana\nbeast\nN\nBrasil\nhola\nmia\njack\nchris\nTurkey\nx\nDavid\nlia\ncookie\nsushi\ndantdm\nJoe\n100%\naaa\ny\nkitty\nanna\nChicken\n?\nio\npp\nbro\ncool\nLala\nKill\nSofia\njeff\nC\nsonic\nspiderman\npanda\nnathan\nfreddy\nDuck\nGaby\nblue\nSUP\nmaria\nhannah\nLuna\nEli\n666\nDucky\nhoi\nhaha\nstar\namy\nASHRAF\nali\npeter\nliv\nV\nsans\ndavi\nBATMAN\nBOOM\n:D\nUtah\nSPAIN\nRafa\nMmm\nGamer\noi\nyour mum\nCAndice\nmiguel\nTHE BEST\nABC\nkevin\nAlexa\ncamila\nchloe\nkillzone\nmoon\nIsaac\ndylan\nnat\naa\npoo\nLili\nFox\nitalia\nLOLA\nbat\nfelipe\nJuan\nBoo\ngodzilla\nEllie\ned\nMr Pro\nLuitch!\nPrincess\njuju\nslogo\nNico\nbruno\ncaca\nwiski\npaper.io\nJK\nyes\n-_-\nasdf\ntank\nJAMES\nALICE\nOVERPUNCH!\nRuby\n505\nloser\ndaddy\nHALLO\nmanu\nArmy\nPEDRO\ncutie\nJesus\ndeez\nmeh\nsussy baka\npapa\nDemon\nMeow\nkate\ndie\nhii\njimmy\nff\nTIM\nRay\n!\nFinn\nNO ONE\nsarah\nmama\n..\nw\nDababy\nAAAAAAAAAAAA\nzo\nnoah\nluke\nagus\naaron\nEva\nNimmersatt\nMaddie\nClara\nmoi\niris\nryan\nadolf hitler\nolivia\nThomas\nciao\ndestroyer\n???\nPat\nyay\nNICE\nbest\nToby\nlolo\nhaker\nloki\nHappy\nfoot\nWASD\nBLACKPINK\nokay\nSerbia\nabby\nHanna\nOof\nLARA\nKatie\nizzy\nAttalus\nhugo\nBot\nGigi\nGermany\nMaisie\nlkp\nVictor\noo\nahmed\nWOW\nGoku\nGhost\nkarol\ndragon\nKira\ncovid 19\nAs\ndontkillme\nmelon\nMango\n?\nMiku\nspider man\njohn\nkittycat\nvivi\nQuack\nmario\nxiomara\nhahaha\nCash\nmexico\nUnknown\nwildfire\ncupcake\nLin\nOwO\njay\nrobin\nkral\nsophie\nPoland\nEMI\nmjmm\ngabi\nliam\nlegend\nSophia\nOMG\nJim\nzipi\nqwerty\nSpieler\nstun seed\nJoe Mama\nno name\nDAD\nkim\nBLAH\nez\nll\ndoctor\nPUPPY\nNIGHTMARE\nJoshua\ndevil\nmike\n123456789\nHunter\njoao\ndanny\nsheesh\nMaster\nWill\nWolf\nTraitor\ntyler\nRiley\nlv\nFoxy\nNina\ncarina\nmaja\nK?LLER GAME\ndj\nMurrr\nHi there!\nari\npotato\nMONSTER\ngood\nit\nSamy\nShadow\nfree\nasd\nLenny\nPepe\nPapa YEY\nJan\nErica\ncheese\nDan\n1H\nxqcOw\njjordan\n-\nFFCS\nanthony\nperson\nFlop\ntrump\nI WIN\nrat\ncorona\noulii !!!\nKILLIN\nAphmau\nUSSR\n;)\nMatias\nGoose\nCaNdy\nCherry\njason\nget lost\nInDiAn\nisrael\nPlay\nMartin\nBaby\nAddie\n1234\nnana\nsch\nThe queen\nraghav\nSteve\ngrace\nMariana\ngalaxy\namelia\nALE\nmc\nwn-rn\nMari\nDetectiveSma\nJens1955DK\nparan?\nMini\nJR.\nlayla\nJoueur\nHihi\ndamn\nlilly\nchase\nerik\nenzo\nMegan\ncharlie\nMarinette\nkoala\nKat\nmy name\nPhoenix\nFrance\nDazzle\njulie\nAlvin\nugh\nguh\nTT\nmoin\nThe King \nOTTOMAN\nU\nelsa\nop\nAJ\nLaura\ntiger\nAdeptstores\nMARIA NAO ME\nBOSSSS\nSa\npop\nWHY\naarav\nDisney\nnyomi\npalestine\nMuffin\npaperio2\nDino\nhpp\nghhiuehg\nvietnam\ncatie\nJayden\nimthequeen\nthe_ares07AZ\nMan\nrayray\n[T]Team.VN\nje moeder\nFIRE_DRAGON\nAliceDiamond\nLANDLORD\nAndy\nbobby\nTJ\nlina\njulian\nnyanCAt\n:(\nss\nfITT\nnyan husky\nflamenco\nIsabella\nDAISY\nWw\nMr. X\nrussia\nDave\nCroatia\nYathartha\nEmperor\nkiller.game\nCanada\nluis\nyuri\nPaper.io 2\nya?mur\neu\nplikplak\nadrian\nHi!\nsheeeeeeeesh\nY Tho\nFRANCISCO\ncancer\n;-;\nJordan\nAzerbaijan\njade\nsomeone\nbangladesh\nLuca\nSheep8\npikachu\nPoppy\nKorea\nHarry\nasafe\n_MyLoveTurk_\nSomaditya\nABDIEL\nBunny\nSol\nmel\nbia\nKaylee\njj mc\nSpeler\njose\nFBi\nmila\nTomtom\nrushininja\nMaya\navi\nChina\n#TigerLove\ni am noob 2\npaula\nsmolpps bro\nLogan\nCCCP\n007 band\nTech X\nPreston\nAnnabeth\nwilliam\nChallengers\nYOLO\njenna\nsori\nputo\nbla\nSmash\narthur\nDUDE\nWin\nGeraldina\nloading...\nJopa\nGoofy\nmm\nLu\nYeah\nanne\nKay\nNova\nJaco\nja\nmarshmello\nddd\nPenguinGamer\nduda\nSpoidermon\nhash\nMIKA\nlinda\nVenom\nshhhhh\nklaus\nevi\nmary\nooooof\njas\nFLA\nERIC\nha\nreaperblack8\nLizzy\nLil\ngirl\nmikasa\nWillow\nblake\nlucy\nYAYA\nLuigi\nMR BEAST\namber\n*\nannie\nRuben\nL O L O H\njenny\nZANZIBAR:)\nJanek\nKOKO\nBrexit\nSpaceBreaker\nlykheang\nIm th Queen\nVALEN\nHIIIIIIIIIII\nel hiper\nvitoria\norange\nguest\nnao sei kKkK\nmad\nMert\nJogador\ndodo\nSTERNENKO\nPopo\nsuper\nColombia\nyoo\ni luv jamaca\nSubtoSsundee\nGABBY\nerikcarr\n:P\nitaly\nsky\nSnoopy\ndeath\nPaper Io\nSummer\nKarma\nsweet\n100%\nbjk\nye\nkiwi\nLucifer\nARCOIRIS\n.....\nECOLISA\nmbt\nNik\nLeonel\nmateo\neren\nskeleton\naustralia\nyoyo\nSHH TREASURE\n???????\njuig\nnoname\nlexi\npidoras\ntatakae\nkai\nIan\nSSS\ngo\nderyk\njungkook\nVSCO girl\nCakey\nAryan\nGreece\nJACOB\nLava\nCome\nAlan\nBTS ARMY\nWalter\nMELIODAS\nbibi\nlul\nmika 635\ncc\nmariaparizzi\nFuria\nAlicia\nhhhh\nJP\nengland\nMEHMET\nelifim\ndua lipa\nEminem\nVI?T NAM\nBomb\nreina\nharry potter\nem\nOle\ndummy\nFrostPopone\nbo\nTIRED BY IK\nstella\nkill me\ncute\nbosta\nBig\nGaram\nmobilenatian\nwww\namina\nminions\nAvengers\nVeronica\nAria\nthe killer\n:o\nsakin!\nclare\npls dont kil\nmmmm\nMARINA\nMAFE\nandres\nMommio\nBananas\nbrazil\n??\nMicha\nIg:Zhenhinsh\nAnonymous00\nDOMIDIOS\ndiana\nmy\nSetriDolpen\nsheller\n+\nsamuel\nRocky\nshmads\ntoto\nlink\nCityzen\ncock\nmiki\nOreo\njeff.io\naja queu\nMoo\nSANJ\nLKZinhu_dbr\n: )\npo\nTNT\nAndrea\nPritam\ngdjgujhghfug\nfatima\npinto coc?\nTaiwan\nspd???????\nkim soobin\nTheo\nShoryaa_24\nherzog\nZach\npro gamer\ngoat\nraven\nlover\nryan games\nalpaca\nSweet spot\nLele\nKaas\npiru kkkkkkk\nPer?n\nkek\nlll\nLaurie\nFlo\nfrozen peas\nSatie\nkinglollypop\nhlm\nerik carr\nNicole\nV00d00Debug2\nnora\nMi\nlong\nFortnite\nsebastian\n??\nSussyBaka\nChamp\nbelarus\nLista\nSmit\n????\nPaper.io2\nThe Boss\nYour+Name\nshahid\nanannya\nmillie\nElias\nreeeee\nnezuko\nzeze\nL?ON\nNikolai\nGio\nTu abuela\nSteal!\ncocomelon\nlazerbeam\nBuster\nRamdai\nBOSS TITAN\nhana\nCan\nEma\nmj\nNobody\n12345678910\nhope\njkjkjkjkkjkj\nGlarak\nyour\nVaishwik\nhenrypikachu\ncavolate\nregteg\nbox boney\nspy\nambar\n12345\nPeru\nezikler\neeeeeeeeeeee\nGamerDuck100\nRawr\nsajid 911\nDiscopants\nAmongUs\nDoNuT\nEmilie\npink\nhhh\nNOA\nnope\nmina\n??\nshark\nensarnasyone\nnbhjvuyj\nLucky\nSavage\nkika\nb?a?ejito\nline\nkeshav\nKlara\nAntoine\nOSMANLI\nmilly\nSaris\nMGS\ncovid\nNapol?on\nLAMA\nXX\namazingfatty\nrafael\n:3\nfabian\nnono\naya\nggg\n404\nSRBIJA KAC\nvictoria\nroblox\nju\nshoto\nMatthew\nAIDEN\nfree fire\nJitterbug\nrapmonster\nbenny\nCUNNING FOX\nkoymoy\njessica\nMeme\nluffy\nhulk\nheart\nBilly\nzeina\nEmma C\nMemphis\nkartilk\nmony\nboffa\nytra\nLorena\nGMO\ndot\nevrytngisawe\nTEAM\nsub2mrbeast\nDavid77\nyon\nFRED\nWar+head\naK\npiper\nDeku\njake\nPlayerKing\nAllan\nnehemiah\njennie\nACE\nKaren\nkuba\nminno?\nFotz\nAmerica\nAgent P\nRofl\nPlayer174062\nunspeakable\ngreen\nmohammed\nnickname\nTy\nzizi\nKarthi\nsnake\nhuh\nBEST PLAYER\nollie\nmr floppy\nWESTBROUCK\nPascool\nHood\nuk\npop it\n";
  var engNames = names.split("\n");

  var LB_TYPE_STR = "" + "kills_score";
  var LB_TYPES_AR = LB_TYPE_STR.split("_");
  var templateForSaves = {
    nickName: "Player",
    language: "en",
    skin: 0,
    allMoney: 0,
    userId: window.player_id || 0,
    timeAlive: 0,
    timeBest: 0,
    killsBest: 0,
    moneyBest: 0
  };
  var templateForGameSettings = {};
  var templateForCurData = {
    hp: 0,
    maxHp: 0
  };
  var templateAccumulated = ["allScore", "allKills"];
  var templateBest = ["scoreBest"];
  var templateResults = ["scoreCur", "scoreBest", "timeAlive", "kills"];
  var templateStart = ["nickName", "skin", "userId"];
  var modeSelect = null;
  switch ("paper") {
    case "paper":
      templateForCurData = curUserDataP3;
      templateStart = startPropNamesP3;
      templateForSaves = emptySaveP3;
      templateAccumulated = propsToAccumulatePaper3;
      templateBest = propsWithBestP3;
      templateResults = resultPropNamesP3;
      modeSelect = modeSelectP3;
      templateForGameSettings = gameSettingsP3;
      break;
    case "shooter":
      templateForCurData = curUserDataShooter;
      templateStart = startPropNamesShooter;
      templateForSaves = emptySaveShooter;
      templateResults = resultPropNamesShooter;
      templateAccumulated = propsToAccumulateShooter;
      templateBest = propsWithBestShooter;
      templateForGameSettings = gameSettingsSh;
      break;
  }
  var config = {
    leaderboardName: "paper3d",
    lbTypes: LB_TYPES_AR,
    extraLife: false,
    storageName: "PAPER3D",
    gameType: "paper",
    saveTemplate: templateForSaves,
    useServerSave: false,
    resultPropNames: templateResults,
    accumProps: templateAccumulated,
    bestProps: templateBest,
    startProps: templateStart,
    modeSelect,
    curData: templateForCurData,
    gameSettings: templateForGameSettings,
    levels: []
  };
  createApi(templateForSaves, engNames);
  var serverParser = new ServerParser(config);
  window.uiApi.localStorageName = config.storageName;
  window.uiApi.serverParse = serverParser;
  window.uiApi.canvasRef = b();
  window.uiApi.effectsCanvasReturned = function() {
    return _$1("canvas", {
      id: "canvasEffects",
      ref: window.uiApi.canvasRef,
      width: window.innerWidth,
      height: window.innerHeight
    });
  };
  window.uiApi.killToast = function() {
    console.warn("Notifications are only available inside the game");
  };
  window.uiApi.setSaveData(serverParser.getUniversalSave());
  var fetchAsset = function fetchAsset2(name) {
    return fetch("".concat("assets", "/").concat(name, "?v").concat(Math.random())).then(function(response) {
      return response.json();
    });
  };
  Promise.all([fetchAsset("languages.json"), fetchAsset("skins.json"), fetchAsset("config.json")]).then(function(_ref) {
    var _ref2 = _slicedToArray(_ref, 3), languages = _ref2[0], skins = _ref2[1], configJson = _ref2[2];
    setLanguages(languages);
    if (configJson) {
      Object.assign(config, configJson);
    }
    if (config.stages) {
      var sgs = config.stages;
      config.modeSelect = {
        unlocksPrc: Object.fromEntries(sgs.map(function(s) {
          return [s.name, 0];
        })),
        list: sgs.map(function(s) {
          return s.name;
        }),
        unlocksConditions: Object.fromEntries(sgs.map(function(s) {
          return [s.name, {
            "type": "prevMap",
            "value": s.prevMapUnlock || 1e3
          }];
        })),
        models: sgs.map(function(s) {
          return {
            label: s.name,
            name: s.model
          };
        })
      };
    }
    initMode(config);
    E(_$1(App, {
      skins,
      serverParser,
      saveLeaderboard: serverParser.saveLeaderboard,
      doSave: window.uiApi.setSaveData,
      loadedData: serverParser.getUniversalSave(),
      curLeaderbData: serverParser.curLeaderbData,
      curLeaderbType: serverParser.curLeaderbType,
      leaderboardsObjData: serverParser.leaderboardsObjData,
      config
    }), document.getElementById("gameUI"));
  });

})();
