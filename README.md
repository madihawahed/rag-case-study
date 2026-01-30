# rag-case-study[index.html.html](https://github.com/user-attachments/files/24951931/index.html.html)
<html lang="en"><head><script>(function(firebaseConfig, initialAuthToken, appId) {
        window.__firebase_config = firebaseConfig;
        window.__initial_auth_token = initialAuthToken;
        window.__app_id = appId;
            })("\n{\n  \"apiKey\": \"AIzaSyCqyCcs2R2e7AegGjvFAwG98wlamtbHvZY\",\n  \"authDomain\": \"bard-frontend.firebaseapp.com\",\n  \"projectId\": \"bard-frontend\",\n  \"storageBucket\": \"bard-frontend.firebasestorage.app\",\n  \"messagingSenderId\": \"175205271074\",\n  \"appId\": \"1:175205271074:web:2b7bd4d34d33bf38e6ec7b\"\n}\n","eyJhbGciOiJSUzI1NiIsImtpZCI6IjI2NmM5YTIxZDM4NGQzZmU0OGMyZjNhYjNiZmE1NjQ0Yzk0ZmY3Y2UiLCJ0eXAiOiJKV1QifQ.eyJzdWIiOiJmaXJlYmFzZS1hZG1pbnNkay1mYnN2Y0BiYXJkLWZyb250ZW5kLmlhbS5nc2VydmljZWFjY291bnQuY29tIiwiYXVkIjoiaHR0cHM6Ly9pZGVudGl0eXRvb2xraXQuZ29vZ2xlYXBpcy5jb20vZ29vZ2xlLmlkZW50aXR5LmlkZW50aXR5dG9vbGtpdC52MS5JZGVudGl0eVRvb2xraXQiLCJ1aWQiOiIwODk3MjI0NzI4MTY0NzUyMzk4NCIsImlzcyI6ImZpcmViYXNlLWFkbWluc2RrLWZic3ZjQGJhcmQtZnJvbnRlbmQuaWFtLmdzZXJ2aWNlYWNjb3VudC5jb20iLCJjbGFpbXMiOnsiYXBwSWQiOiJjXzQwNTEwOTRhOGZkMzY5MGZfcmFnX2Nhc2Vfc3R1ZHlfcmVwb3J0Lmh0bWwtNTg3In0sImV4cCI6MTc2OTQ4MDQ3OSwiaWF0IjoxNzY5NDc2ODc5LCJhbGciOiJSUzI1NiJ9.CPn-UoNIe9wkw9aLobkqqlsviy_ZnxuIXv5J9kOvrvU60LE_pFuK4TCgQLsis5Dv-tmI8qkODiYmWbphQH4zrEA3E3wXA47yaIb5DXRcuoIzkLb3ZSOLiTs9xLIl5xTPoHEnJkzhRZkLgs73pYzTAnn3uXvrA6VGFSSegLKMBeDN0WdhLPSQ9eHZXbkPOB4BEwHvtXCaSK6nII_QOv8s-S7OO8yTW_v-NyvNVl3mk10w4mh_laOMtkXxaKzj_sIBBkIzIxJ4qWKnpcqo6X28g5gaXvgR_qGyGMPmY3yRgSnQYFQupzHFefhMmfGLjicfOa_cphEIdMRsOzH421go9w","c_4051094a8fd3690f_rag_case_study_report.html-587")</script><script>'use strict';var h=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,d){if(a==Array.prototype||a==Object.prototype)return a;a[b]=d.value;return a};function l(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var d=a[b];if(d&&d.Math==Math)return d}throw Error("Cannot find global object");}var n=l(this);
function p(a,b){if(b)a:{var d=n;a=a.split(".");for(var c=0;c<a.length-1;c++){var e=a[c];if(!(e in d))break a;d=d[e]}a=a[a.length-1];c=d[a];b=b(c);b!=c&&b!=null&&h(d,a,{configurable:!0,writable:!0,value:b})}}function r(a){function b(c){return a.next(c)}function d(c){return a.throw(c)}return new Promise(function(c,e){function f(g){g.done?c(g.value):Promise.resolve(g.value).then(b,d).then(f,e)}f(a.next())})}function t(a){return r(a())}
p("Object.values",function(a){return a?a:function(b){var d=[],c;for(c in b)Object.prototype.hasOwnProperty.call(b,c)&&d.push(b[c]);return d}});p("Array.prototype.includes",function(a){return a?a:function(b,d){var c=this;c instanceof String&&(c=String(c));var e=c.length;d=d||0;for(d<0&&(d=Math.max(d+e,0));d<e;d++){var f=c[d];if(f===b||Object.is(f,b))return!0}return!1}});/*

 MIT License

 Copyright (c) 2017-2023 W.Y.

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 SOFTWARE.

*/
function u(a,b){const d=a.style;b.backgroundColor&&(d.backgroundColor=b.backgroundColor);b.width&&(d.width=`${b.width}px`);b.height&&(d.height=`${b.height}px`);const c=b.style;c!=null&&Object.keys(c).forEach(e=>{d[e]=c[e]})};var v=(()=>{let a=0;return()=>{a+=1;return`u${`0000${(Math.random()*1679616<<0).toString(36)}`.slice(-4)}${a}`}})();function w(a){const b=[];for(let d=0,c=a.length;d<c;d++)b.push(a[d]);return b}let x=null;function y(a={}){return x?x:a.l?x=a.l:x=w(window.getComputedStyle(document.documentElement))}function z(a,b){return(a=(a.ownerDocument.defaultView||window).getComputedStyle(a).getPropertyValue(b))?parseFloat(a.replace("px","")):0}
function A(a,b={}){var d;if(!(d=b.width)){d=z(a,"border-left-width");var c=z(a,"border-right-width");d=a.clientWidth+d+c}(b=b.height)||(b=z(a,"border-top-width"),c=z(a,"border-bottom-width"),b=a.clientHeight+b+c);return{width:d,height:b}}function B(a){return new Promise((b,d)=>{const c=new Image;c.onload=()=>{c.decode().then(()=>{requestAnimationFrame(()=>b(c))})};c.onerror=d;c.crossOrigin="anonymous";c.decoding="async";c.src=a})}
function C(a){return t(function*(){return Promise.resolve().then(()=>(new XMLSerializer).serializeToString(a)).then(encodeURIComponent).then(b=>`data:image/svg+xml;charset=utf-8,${b}`)})}
function D(a,b,d){return t(function*(){const c=document.createElementNS("http://www.w3.org/2000/svg","svg"),e=document.createElementNS("http://www.w3.org/2000/svg","foreignObject");c.setAttribute("width",`${b}`);c.setAttribute("height",`${d}`);c.setAttribute("viewBox",`0 0 ${b} ${d}`);e.setAttribute("width","100%");e.setAttribute("height","100%");e.setAttribute("x","0");e.setAttribute("y","0");e.setAttribute("externalResourcesRequired","true");c.appendChild(e);e.appendChild(a);return C(c)})}
var E=(a,b)=>{if(a instanceof b)return!0;a=Object.getPrototypeOf(a);return a===null?!1:a.constructor.name===b.name||E(a,b)};function F(a,b){return y(b).map(d=>{const c=a.getPropertyValue(d),e=a.getPropertyPriority(d);return`${d}: ${c}${e?" !important":""};`}).join(" ")}
function G(a,b,d,c){a=window.getComputedStyle(a,d);var e=a.getPropertyValue("content");if(e!==""&&e!=="none"){var f=v();try{b.className=`${b.className} ${f}`}catch(k){return}e=document.createElement("style");var g=e.appendChild;d=`.${f}:${d}`;a.cssText?(c=a.getPropertyValue("content"),c=`${a.cssText} content: '${c.replace(/'|"/g,"")}';`):c=F(a,c);g.call(e,document.createTextNode(`${d}{${c}}`));b.appendChild(e)}};function H(a){return a.search(/^(data:)/)!==-1}function I(a,b,d){return t(function*(){const c=yield fetch(a,b);if(c.status===404)throw Error(`Resource "${c.url}" not found`);const e=yield c.blob();return new Promise((f,g)=>{const k=new FileReader;k.onerror=g;k.onloadend=()=>{try{f(d({o:c,result:k.result}))}catch(m){g(m)}};k.readAsDataURL(e)})})}const J={};function K(a,b,d){let c=a.replace(/\?.*/,"");d&&(c=a);/ttf|otf|eot|woff2?/i.test(c)&&(c=c.replace(/.*\//,""));return b?`[${b}]${c}`:c}
function L(a,b,d){return t(function*(){const c=K(a,b,d.C);if(J[c]!=null)return J[c];d.u&&(a+=(/\?/.test(a)?"&":"?")+(new Date).getTime());let e;try{const f=yield I(a,d.i,({o:g,result:k})=>{b||(b=g.headers.get("Content-Type")||"");return k.split(/,/)[1]});e=`data:${b};base64,${f}`}catch(f){e=d.B||""}return J[c]=e})};const M={P:"application/font-woff",R:"application/font-woff",N:"application/font-truetype",v:"application/vnd.ms-fontobject",H:"image/png",F:"image/jpeg",D:"image/jpeg",A:"image/gif",M:"image/tiff",L:"image/svg+xml",O:"image/webp"};function N(a){return(a=/\.([^./]*?)$/g.exec(a))?a[1]:""};function O(a){return t(function*(){const b=a.toDataURL();return b==="data:,"?a.cloneNode(!1):B(b)})}function aa(a,b){return t(function*(){if(a.currentSrc){var d=document.createElement("canvas");const c=d.getContext("2d");d.width=a.clientWidth;d.height=a.clientHeight;c==null||c.drawImage(a,0,0,d.width,d.height);d=d.toDataURL();return B(d)}d=a.poster;d=yield L(d,M[N(d).toLowerCase()]||"",b);return B(d)})}
function ba(a,b){return t(function*(){try{let d;if(a==null?0:(d=a.contentDocument)==null?0:d.body)return yield P(a.contentDocument.body,b,!0)}catch(d){}return a.cloneNode(!1)})}function ca(a,b){return t(function*(){return E(a,HTMLCanvasElement)?O(a):E(a,HTMLVideoElement)?aa(a,b):E(a,HTMLIFrameElement)?ba(a,b):a.cloneNode(a.tagName!=null&&a.tagName.toUpperCase()==="SVG")})}
function da(a,b,d){return t(function*(){if(b.tagName!=null&&b.tagName.toUpperCase()==="SVG")return b;let c=[];if(a.tagName!=null&&a.tagName.toUpperCase()==="SLOT"&&a.assignedNodes)c=w(a.assignedNodes());else{let e;if(E(a,HTMLIFrameElement)&&((e=a.contentDocument)==null?0:e.body))c=w(a.contentDocument.body.childNodes);else{let f;c=w(((f=a.shadowRoot)!=null?f:a).childNodes)}}if(c.length===0||E(a,HTMLVideoElement))return b;yield c.reduce((e,f)=>e.then(()=>P(f,d)).then(g=>{g&&b.appendChild(g)}),Promise.resolve());
return b})}function ea(a,b,d){const c=b.style;if(c){var e=window.getComputedStyle(a);e.cssText?(c.cssText=e.cssText,c.transformOrigin=e.transformOrigin):y(d).forEach(f=>{let g=e.getPropertyValue(f);f==="font-size"&&g.endsWith("px")&&(g=`${Math.floor(parseFloat(g.substring(0,g.length-2)))-.1}px`);E(a,HTMLIFrameElement)&&f==="display"&&g==="inline"&&(g="block");f==="d"&&b.getAttribute("d")&&(g=`path(${b.getAttribute("d")})`);c.setProperty(f,g,e.getPropertyPriority(f))})}}
function fa(a,b){E(a,HTMLSelectElement)&&(b=Array.from(b.children).find(d=>a.value===d.getAttribute("value")))&&b.setAttribute("selected","")}
function ha(a,b){return t(function*(){var d=a.querySelectorAll?a.querySelectorAll("use"):[];if(d.length===0)return a;var c={};for(var e=0;e<d.length;e++){var f=d[e].getAttribute("xlink:href");if(f){const g=document.querySelector(f);a.querySelector(f)||!g||c[f]||(c[f]=yield P(g,b,!0))}}d=Object.values(c);if(d.length){c=document.createElementNS("http://www.w3.org/1999/xhtml","svg");c.setAttribute("xmlns","http://www.w3.org/1999/xhtml");c.style.position="absolute";c.style.width="0";c.style.height="0";
c.style.overflow="hidden";c.style.display="none";e=document.createElementNS("http://www.w3.org/1999/xhtml","defs");c.appendChild(e);for(f=0;f<d.length;f++)e.appendChild(d[f]);a.appendChild(c)}return a})}
function P(a,b,d){return t(function*(){return d||!b.filter||b.filter(a)?Promise.resolve(a).then(c=>ca(c,b)).then(c=>da(a,c,b)).then(c=>{E(c,Element)&&(ea(a,c,b),G(a,c,":before",b),G(a,c,":after",b),E(a,HTMLTextAreaElement)&&(c.textContent=a.value),E(a,HTMLInputElement)&&c.setAttribute("value",a.value),fa(a,c));return c}).then(c=>ha(c,b)):null})};const Q=/url\((['"]?)([^'"]+?)\1\)/g,ia=/url\([^)]+\)\s*format\((["']?)([^"']+)\1\)/g,ja=/src:\s*(?:url\([^)]+\)\s*format\([^)]+\)[,;]\s*)+/g;function ka(a){const b=[];a.replace(Q,(d,c,e)=>{b.push(e);return d});return b.filter(d=>!H(d))}
function la(a,b,d,c){return t(function*(){try{const e=d?(new URL(b,d||void 0)).toString():b;let f;f=yield L(e,M[N(b).toLowerCase()]||"",c);return a.replace(new RegExp(`(url\\(['"]?)(${b.replace(/([.*+?^${}()|\[\]\/\\])/g,"\\$1")})(['"]?\\))`,"g"),`$1${f}$3`)}catch(e){}return a})}function ma(a,{I:b}){return b?a.replace(ja,d=>{for(;;){const [c,,e]=ia.exec(d)||[],f=c,g=e;if(!g)return"";if(g===b)return`src: ${f};`}}):a}
function R(a,b,d){return t(function*(){if(a.search(Q)===-1)return a;const c=ma(a,d);return ka(c).reduce((e,f)=>e.then(g=>la(g,f,b,d)),Promise.resolve(c))})};function S(a,b,d){return t(function*(){var c;const e=(c=b.style)==null?void 0:c.getPropertyValue(a);return e?(c=yield R(e,null,d),b.style.setProperty(a,c,b.style.getPropertyPriority(a)),!0):!1})}function na(a,b){return t(function*(){(yield S("background",a,b))||(yield S("background-image",a,b));(yield S("mask",a,b))||(yield S("-webkit-mask",a,b))||(yield S("mask-image",a,b))||(yield S("-webkit-mask-image",a,b))})}
function oa(a,b){return t(function*(){const d=E(a,HTMLImageElement);if(d&&!H(a.src)||E(a,SVGImageElement)&&!H(a.href.baseVal)){var c=d?a.src:a.href.baseVal,e=yield L(c,M[N(c).toLowerCase()]||"",b);yield new Promise((f,g)=>{a.onload=f;a.onerror=b.m?(...k)=>{try{f(b.m(...k))}catch(m){g(m)}}:g;a.decode&&(a.decode=f);a.loading==="lazy"&&(a.loading="eager");d?(a.srcset="",a.src=e):a.href.baseVal=e})}})}
function pa(a,b){return t(function*(){const d=w(a.childNodes).map(c=>T(c,b));yield Promise.all(d).then(()=>a)})}function T(a,b){return t(function*(){E(a,Element)&&(yield na(a,b),yield oa(a,b),yield pa(a,b))})};const U={};function V(a){return t(function*(){var b=U[a];if(b!=null)return b;b=yield(yield fetch(a)).text();b={url:a,cssText:b};return U[a]=b})}function W(a,b){return t(function*(){let d=a.cssText;const c=/url\(["']?([^"')]+)["']?\)/g,e=(d.match(/url\([^)]+\)/g)||[]).map(f=>t(function*(){let g=f.replace(c,"$1");g.startsWith("https://")||(g=(new URL(g,a.url)).href);return I(g,b.i,({result:k})=>{d=d.replace(f,`url(${k})`);return[f,k]})}));return Promise.all(e).then(()=>d)})}
function X(a){if(a==null)return[];const b=[];a=a.replace(/(\/\*[\s\S]*?\*\/)/gi,"");for(var d=RegExp("((@.*?keyframes [\\s\\S]*?){([\\s\\S]*?}\\s*?)})","gi");;){var c=d.exec(a);if(c===null)break;b.push(c[0])}a=a.replace(d,"");d=/@import[\s\S]*?url\([^)]*\)[\s\S]*?;/gi;for(c=RegExp("((\\s*?(?:\\/\\*[\\s\\S]*?\\*\\/)?\\s*?@media[\\s\\S]*?){([\\s\\S]*?)}\\s*?})|(([\\s\\S]*?){([\\s\\S]*?)})","gi");;){let e=d.exec(a);if(e===null)if(e=c.exec(a),e===null)break;else d.lastIndex=c.lastIndex;else c.lastIndex=
d.lastIndex;b.push(e[0])}return b}
function qa(a,b){return t(function*(){const d=[],c=[];a.forEach(e=>{if("cssRules"in e)try{w(e.cssRules||[]).forEach((f,g)=>{if(f.type===CSSRule.IMPORT_RULE){let k=g+1;f=V(f.href).then(m=>W(m,b)).then(m=>X(m).forEach(q=>{try{e.insertRule(q,q.startsWith("@import")?k+=1:e.cssRules.length)}catch(Da){}})).catch(()=>{});c.push(f)}})}catch(f){const g=a.find(k=>k.href==null)||document.styleSheets[0];e.href!=null&&c.push(V(e.href).then(k=>W(k,b)).then(k=>X(k).forEach(m=>{g.insertRule(m,g.cssRules.length)})).catch(()=>
{}))}});return Promise.all(c).then(()=>{a.forEach(e=>{if("cssRules"in e)try{w(e.cssRules||[]).forEach(f=>{d.push(f)})}catch(f){}});return d})})}function ra(a){return a.filter(b=>b.type===CSSRule.FONT_FACE_RULE).filter(b=>b.style.getPropertyValue("src").search(Q)!==-1)}function sa(a,b){return t(function*(){if(a.ownerDocument==null)throw Error("Provided element is not within a Document");var d=w(a.ownerDocument.styleSheets);d=yield qa(d,b);return ra(d)})}
function ta(a){function b(c){(c.style.fontFamily||getComputedStyle(c).fontFamily).split(",").forEach(e=>{d.add(e.trim().replace(/["']/g,""))});Array.from(c.children).forEach(e=>{e instanceof HTMLElement&&b(e)})}const d=new Set;b(a);return d}function ua(a,b){return t(function*(){const d=yield sa(a,b),c=ta(a);return(yield Promise.all(d.filter(e=>c.has(e.style.fontFamily.trim().replace(/["']/g,""))).map(e=>R(e.cssText,e.parentStyleSheet?e.parentStyleSheet.href:null,b)))).join("\n")})}
function va(a,b){return t(function*(){const d=b.j!=null?b.j:b.K?null:yield ua(a,b);if(d){const c=document.createElement("style");c.appendChild(document.createTextNode(d));a.firstChild?a.insertBefore(c,a.firstChild):a.appendChild(c)}})};function wa(a,b={}){return t(function*(){const {width:d,height:c}=A(a,b),e=yield P(a,b,!0);yield va(e,b);yield T(e,b);u(e,b);return yield D(e,d,c)})}
function xa(a,b={}){return t(function*(){const {width:d,height:c}=A(a,b);var e=yield wa(a,b);e=yield B(e);const f=document.createElement("canvas"),g=f.getContext("2d"),k=b.G||window.devicePixelRatio||1,m=b.h||d,q=b.g||c;f.width=m*k;f.height=q*k;!b.J&&(f.width>16384||f.height>16384)&&(f.width>16384&&f.height>16384?f.width>f.height?(f.height*=16384/f.width,f.width=16384):(f.width*=16384/f.height,f.height=16384):f.width>16384?(f.height*=16384/f.width,f.width=16384):(f.width*=16384/f.height,f.height=
16384));f.style.width=`${m}`;f.style.height=`${q}`;b.backgroundColor&&(g.fillStyle=b.backgroundColor,g.fillRect(0,0,f.width,f.height));g.drawImage(e,0,0,f.width,f.height);return f})}function ya(a,b={}){return t(function*(){return(yield xa(a,b)).toDataURL()})};const za=["gemini.google.com","corp.google.com","proxy.googlers.com"];function Y(){return document.body.querySelectorAll('[class*="animate"]').length>0}function Z(a){return t(function*(){try{return yield ya(a,{h:a.offsetWidth,g:a.offsetHeight})}catch(d){var b=a.offsetHeight;const c=document.createElement("canvas");c.width=a.offsetWidth;c.height=b;return c.toDataURL("image/png")}})}
function Aa(){return t(function*(){const a=document.body.offsetWidth,b=document.body.offsetHeight,d=document.body.cloneNode(!0);d.querySelectorAll('[class*="animate"]').forEach(c=>{c.classList.remove(...Array.from(c.classList).filter(e=>e.startsWith("animate")))});d.style.width=`${a}px`;d.style.height=`${b}px`;return d})}
function Ba(a){return t(function*(){let b=document.body;if(Y()){var d=yield Aa();b=d;document.body.appendChild(d)}d=yield Z(b);Y()&&document.body.removeChild(b);window.parent.postMessage({type:"SEND_SCREENSHOT",image:d,topOffset:document.documentElement.scrollTop},a.origin)})}function Ca(a){return t(function*(){const b={type:"SEND_SCREENSHOT_FOR_DATA_VISUALIZATION",image:yield Z(document.body),topOffset:0};window.parent.postMessage(b,a.origin)})}
window.addEventListener("message",a=>t(function*(){if(za.some(d=>a.origin.includes(d))){var b=a.data;b&&(b.type==="MAKE_SCREENSHOT"&&(yield Ba(a)),b.type==="MAKE_SCREENSHOT_FOR_DATA_VISUALIZATION"&&(yield Ca(a)))}}));
</script><script>(function() {
  // Ensure this script is executed only once
  if (window.firebaseAuthBridgeScriptLoaded) {
    return;
  }
  window.firebaseAuthBridgeScriptLoaded = true;

  let nextTokenPromiseId = 0;

  // Stores { resolve, reject } for ongoing token requests
  const pendingTokenPromises = {};

  // Listen for messages from the Host Application
  window.addEventListener('message', function(event) {

    const messageData = event.data;

  if (messageData && messageData.type === 'RESOLVE_NEW_FIREBASE_TOKEN') {
      const { success, token, error, promiseId } = messageData ?? {};
      if (pendingTokenPromises[promiseId]) {
        if (success) {
          pendingTokenPromises[promiseId].resolve(token);
        } else {
          pendingTokenPromises[promiseId].reject(new Error(error || 'Token refresh failed from host.'));
        }
        delete pendingTokenPromises[promiseId];
      }
    }
  });

  // Expose a function for the Generated App to request a new Firebase token
  window.requestNewFirebaseToken = function() {
    const currentPromiseId = nextTokenPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingTokenPromises[currentPromiseId] = { resolve, reject };
    });
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({
        type: 'REQUEST_NEW_FIREBASE_TOKEN',
        promiseId: currentPromiseId
      }, '*');
    } else {
      pendingTokenPromises[currentPromiseId].reject(new Error('No parent window to request token from.'));
      delete pendingTokenPromises[currentPromiseId];
    }
    return promise;
  };
})();</script><script>
let realOriginalGetUserMedia = null;
if (navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
  realOriginalGetUserMedia = navigator.mediaDevices.getUserMedia.bind(navigator.mediaDevices);
}

(function() {
  if (navigator.mediaDevices && navigator.mediaDevices.__proto__) {
    try {
      Object.defineProperty(navigator.mediaDevices.__proto__, 'getUserMedia', {
        get: function() {
          return undefined; // Or throw an error
        },
        configurable: false
      });
    } catch (error) {
      console.error("Error defining prototype getter:", error);
    }
  }
})();

(function() {
  const pendingMediaResolvers = {};
  let nextMediaPromiseId = 0;

  function requestMediaPermissions(constraints) {
    const mediaPromiseId = nextMediaPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingMediaResolvers[mediaPromiseId] = (granted) => {
        delete pendingMediaResolvers[mediaPromiseId];
        resolve(granted);
      };
    });

    window.parent.postMessage({
      type: 'requestMediaPermission',
      constraints: constraints,
      promiseId: mediaPromiseId,
    }, '*');

    return promise;
  }

  let originalGetUserMedia = realOriginalGetUserMedia;

  function interceptGetUserMedia() {
    if (navigator.mediaDevices) {
      Object.defineProperty(navigator.mediaDevices, 'getUserMedia', {
        value: function(constraints) {
          return requestMediaPermissions(constraints).then((granted) => {
            if (granted) {
              if (originalGetUserMedia) {
                return originalGetUserMedia(constraints);
              } else {
                throw new Error("Original getUserMedia not available.");
              }
            } else {
              throw new DOMException('Permission denied', 'NotAllowedError');
            }
          });
        },
        writable: false,
        configurable: false
      });
    }
  }

  interceptGetUserMedia();

  const observer = new MutationObserver(function(mutationsList, observer) {
    for (const mutation of mutationsList) {
      if (mutation.type === 'reconfigured' && mutation.name === 'getUserMedia' && mutation.object === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'attributes' && mutation.attributeName === 'getUserMedia' && mutation.target === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'childList' && mutation.addedNodes) {
        mutation.addedNodes.forEach(node => {
          if (node === navigator.mediaDevices) {
            interceptGetUserMedia();
          }
        });
      }
    }
  });

  function interceptSpeechRecognition() {
    if (!window.SpeechRecognition && !window.webkitSpeechRecognition) {
      return;
    }

    const OriginalSpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;

    const SpeechRecognitionWrapper = function(...args) {
      const recognizer = new OriginalSpeechRecognition(...args);
      const originalStart = recognizer.start.bind(recognizer);

      recognizer.start = function() {
        requestMediaPermissions({ audio: true }).then(granted => {
          if (granted) {
            originalStart();
          } else {
            const errorEvent = new SpeechRecognitionErrorEvent('error');
            errorEvent.error = 'not-allowed'; // This is the standard error for permission denial.
            recognizer.dispatchEvent(errorEvent);
          }
        });
      };

      return recognizer;
    };

    SpeechRecognitionWrapper.prototype = OriginalSpeechRecognition.prototype;
    SpeechRecognitionWrapper.prototype.constructor = SpeechRecognitionWrapper;

    if (window.SpeechRecognition) {
      window.SpeechRecognition = SpeechRecognitionWrapper;
    }
    if (window.webkitSpeechRecognition) {
      window.webkitSpeechRecognition = SpeechRecognitionWrapper;
    }
  }

  interceptSpeechRecognition();

  window.addEventListener('message', function(event) {
    if (event.data) {
      if (event.data.type === 'resolveMediaPermission') {
        const { promiseId, granted } = event.data;
        if (pendingMediaResolvers[promiseId]) {
          pendingMediaResolvers[promiseId](granted);
        }
      }
    }
  });

})();</script><script>((function(modelInformation) {
  const originalFetch = window.fetch;
  // TODO: b/421908508 - Move these out of the script and match all generative AI model calls.
  let googleLlmBaseApiUrls = [
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':streamGenerateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageEditModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageTransformModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.ttsModelName + ':generateContent',
  ];
  modelInformation.deprecatedTextModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
    );
  });
  modelInformation.deprecatedImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predict',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predictLongRunning',
    );
  });

  const pendingFetchResolvers = {};
  let nextPromiseId = 0;

  function handleStringInput(input, optionsArgument) {
    const actualUrl = input;
    const fetchCallArgs = [actualUrl, optionsArgument];
    const effectiveOptions = optionsArgument || {};
    const bodyForApiKeyCheck = effectiveOptions.body;
    const bodyForPostMessage = effectiveOptions.body;
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  function handleRequestInput(input, optionsArgument) {
    const actualUrl = input.url;
    const fetchCallArgs = [input, optionsArgument];
    const effectiveOptions = { method: input.method, headers: new Headers(input.headers) };
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (optionsArgument) {
      if (optionsArgument.method) effectiveOptions.method = optionsArgument.method;
      if (optionsArgument.headers) effectiveOptions.headers = new Headers(optionsArgument.headers);
      if ('body' in optionsArgument) {
        bodyForApiKeyCheck = optionsArgument.body;
        bodyForPostMessage = optionsArgument.body;
      } else {
        bodyForApiKeyCheck = undefined;
        bodyForPostMessage = input.body;
      }
    } else {
      bodyForApiKeyCheck = undefined;
      bodyForPostMessage = input.body;
    }
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  window.fetch = function(input, optionsArgument) {
    let actualUrl;
    let fetchCallArgs;
    let effectiveOptions = {};
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (typeof input === 'string') {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleStringInput(input, optionsArgument));
    } else if (input instanceof Request) {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleRequestInput(input, optionsArgument));
    } else {
      return originalFetch.apply(window, [input, optionsArgument]);
    }

    effectiveOptions.method = effectiveOptions.method || 'GET';
    if (!effectiveOptions.headers) {
      effectiveOptions.headers = new Headers();
    }


    if (typeof actualUrl === 'string' && googleLlmBaseApiUrls.some((url) => actualUrl.startsWith(url))) {
      let apiKeyIsNull = true;

      const regex = new RegExp("models/([^:]+)");
      const modelNameMatch = actualUrl.match(regex);
      const modelName = modelNameMatch ? modelNameMatch[1] : 'unspecified';


      try {
        const urlObject = new URL(actualUrl);  // Use URL object for robust parsing
        const apiKeyParam = urlObject.searchParams.get('key');
        if (apiKeyParam) {
          apiKeyIsNull = false;
        }
      } catch (e) {
        // Continue checks even if URL parsing fails
      }

      if (apiKeyIsNull && effectiveOptions.headers) {
        const h = new Headers(effectiveOptions.headers);
        const apiKeyHeaderValue = h.get('X-API-Key') || h.get('x-api-key');
        if (apiKeyHeaderValue) {
          apiKeyIsNull = false;
          return originalFetch.apply(window, fetchCallArgs);
        }
      }

      if (apiKeyIsNull && effectiveOptions.method && ['POST', 'PUT', 'PATCH'].includes(effectiveOptions.method.toUpperCase()) && typeof bodyForApiKeyCheck === 'string') {
        try {
          const bodyData = JSON.parse(bodyForApiKeyCheck);
          if (bodyData && bodyData.apiKey) {
            apiKeyIsNull = false;
            return originalFetch.apply(window, fetchCallArgs);
          }
        } catch (e) {
          // Ignore JSON parsing errors
        }
      }

      if(apiKeyIsNull) {
        const promiseId = nextPromiseId++;
        const promise = new Promise((resolve) => {
          pendingFetchResolvers[promiseId] = (resolvedResponse) => {
            delete pendingFetchResolvers[promiseId];
            resolve(resolvedResponse);
          };
        });

        let serializedBodyForPostMessage;
        if (typeof bodyForPostMessage === 'string' || bodyForPostMessage == null) {
            serializedBodyForPostMessage = bodyForPostMessage;
        } else if (bodyForPostMessage instanceof ReadableStream) {
            serializedBodyForPostMessage = null;
        } else {
            try {
                serializedBodyForPostMessage = JSON.stringify(bodyForPostMessage);
            } catch (e) {
                serializedBodyForPostMessage = null;
            }
        }

        const messageOptions = {
            method: effectiveOptions.method,
            headers: Object.fromEntries(new Headers(effectiveOptions.headers).entries()),
            body: serializedBodyForPostMessage
        };

        window.parent.postMessage({
          type: 'requestFetch',
          url: actualUrl,
          modelName: modelName,
          options: messageOptions,
          promiseId: promiseId,
        }, '*');

        return promise;
      }
      return originalFetch.apply(window, fetchCallArgs);
    }
    return originalFetch.apply(window, fetchCallArgs);
  };

  window.addEventListener('message', function(event) {
    if (event.data && event.data.type === 'resolveFetch') {
      const { promiseId, response } = event.data;
      if (pendingFetchResolvers[promiseId]) {
        try {
          const reconstructedResponse = new Response(response.body, {
            status: response.status,
            statusText: response.statusText,
            headers: new Headers(response.headers),
          });
          pendingFetchResolvers[promiseId](reconstructedResponse);
        } catch (error) {
          pendingFetchResolvers[promiseId](new Response(null, { status: 500, statusText: "Interceptor Response Reconstruction Error" }));
        }
      }
    }
  });

}))({"textModelName":"gemini-2.5-flash-preview-09-2025","imageModelName":"imagen-4.0-generate-001","imageEditModelName":"gemini-2.5-flash-image-preview","imageTransformModelName":"gemini-3-pro-image-preview-11-2025","videoModelName":"veo-2.0-generate-001","ttsModelName":"gemini-2.5-flash-preview-tts","deprecatedTextModelNames":["gemini-2.0-flash","gemini-2.5-flash-preview-04-17","gemini-2.5-flash-preview-05-20"],"deprecatedImageModelNames":["imagen-3.0-generate-001","imagen-3.0-generate-002"]})</script><script>(function() {
  const originalConsoleLog = console.log;
  const originalConsoleError = console.error;

    /**
   * Normalizes an error event or a promise rejection reason into a structured error object.
   * @param {*} errorEventOrReason The error object or reason.
   * @return {object} Structured error data { message, name, stack }.
   */
  function getErrorObject(errorEventOrReason) {
    if (errorEventOrReason instanceof Error) {
      return {
        message: errorEventOrReason.message,
        name: errorEventOrReason.name,
        stack: errorEventOrReason.stack,
      };
    }
    // Fallback for non-Error objects.
    try {
      return {
        message: JSON.stringify(errorEventOrReason),
        name: 'UnknownErrorType',
        stack: null,
      };
    } catch (e) {
      return {
        message: String(errorEventOrReason),
        name: 'UnknownErrorTypeNonStringifiable',
        stack: null,
      };
    }
  }

  /**
   * Converts an array of arguments (from log/error) into a single string.
   * Handles Error objects specially to include their message and stack.
   * @param {Array<*>} args - Arguments passed to console methods.
   * @return {string} A string representation of the arguments.
   */
  function stringifyArgs(args) {
    return args
      .map((arg) => {
        if (arg instanceof Error) {
          const {message, stack} = arg;
          return `Error: ${message}${stack ? ('\nStack: ' + stack) : ''}`;
        }
        if (typeof arg === 'object' && arg !== null) {
          try {
            return JSON.stringify(arg);
          } catch (error) {
            return '[Circular Object]';
          }
        } else {
          return String(arg);
        }
      })
      .join(' ');
  }

  console.log = function(...args) {
    const logString = stringifyArgs(args);
    window.parent.postMessage({ type: 'log', message: logString }, '*');
    originalConsoleLog.apply(console, args);
  };

  console.error = function(...args) {
    let errorData;
    if (args.length > 0 && args[0] instanceof Error) {
      const err = args[0];
      // If the first arg is an Error, capture its details.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        ...getErrorObject(err),
        rawArgsString: stringifyArgs(args.slice(1)),
        timestamp: new Date().toISOString(),
      };
    } else {
      // If not an Error object, treat all args as a general error message.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        message: stringifyArgs(args),
        name: 'ConsoleLoggedError',
        stack: null,
        timestamp: new Date().toISOString(),
      };
    }
    window.parent.postMessage(errorData, '*');
    originalConsoleError.apply(console, args);
  };

  // Listen for global unhandled synchronous errors.
  window.addEventListener('error', function(event) {
    const errorDetails = event.error ? getErrorObject(event.error) : {
      message: event.message,
      name: 'GlobalError',
      stack: null,
      filename: event.filename,
      lineno: event.lineno,
      colno: event.colno,
    };

    window.parent.postMessage({
      type: 'error',
      source: 'global',
      ...errorDetails,
      message: errorDetails.message || event.message,
      timestamp: new Date().toISOString(),
    }, '*');
  });

  // Listen for unhandled promise rejections (asynchronous errors).
  window.addEventListener('unhandledrejection', function(event) {
    const errorDetails = getErrorObject(event.reason);

    window.parent.postMessage({
      type: 'error',
      source: 'unhandledrejection',
      ...errorDetails,
      message: errorDetails.message || 'Unhandled Promise Rejection',
      timestamp: new Date().toISOString(),
    }, '*');
  });

})();</script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Case Study: RAG System for Food &amp; Beverage Compliance</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js" crossorigin="anonymous"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #f3f4f6; color: #1f2937; line-height: 1.6; }
        .page-break { border-top: 2px dashed #d1d5db; margin: 4rem 0; position: relative; }
        .page-break::after { content: "Next Section"; position: absolute; top: -14px; left: 50%; transform: translateX(-50%); background: #f3f4f6; padding: 0 1rem; font-size: 0.75rem; color: #9ca3af; text-transform: uppercase; letter-spacing: 0.1em; }
        .card { background: white; border-radius: 12px; box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1); padding: 3rem; margin-bottom: 2rem; }
        .diagram-box { background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 8px; padding: 2rem; margin: 1.5rem 0; }
        h1 { color: #1e3a8a; font-weight: 800; letter-spacing: -0.025em; }
        h2 { color: #2563eb; font-weight: 700; margin-top: 2rem; margin-bottom: 1rem; display: flex; align-items: center; }
        h3 { color: #1e40af; font-weight: 600; margin-top: 1.5rem; }
        .milestone-badge { background: #dbeafe; color: #1e40af; padding: 0.25rem 0.75rem; border-radius: 9999px; font-size: 0.75rem; font-weight: 700; margin-right: 1rem; text-transform: uppercase; }
        
        #downloadBtn {
            position: fixed;
            bottom: 2rem;
            right: 2rem;
            background-color: #1e3a8a;
            color: white;
            padding: 1rem 1.5rem;
            border-radius: 50px;
            font-weight: 600;
            box-shadow: 0 10px 20px rgba(30, 58, 138, 0.3);
            cursor: pointer;
            z-index: 100;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        #downloadBtn:hover { transform: translateY(-2px); box-shadow: 0 15px 25px rgba(30, 58, 138, 0.4); background-color: #1e40af; }
        
        @media print {
            #downloadBtn { display: none; }
            .card { box-shadow: none; border: 1px solid #eee; }
            .page-break { page-break-before: always; border: none; }
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.mx-auto{margin-left:auto;margin-right:auto}.my-4{margin-top:1rem;margin-bottom:1rem}.mb-20{margin-bottom:5rem}.mb-4{margin-bottom:1rem}.mb-6{margin-bottom:1.5rem}.mb-8{margin-bottom:2rem}.ml-5{margin-left:1.25rem}.ml-6{margin-left:1.5rem}.mt-0{margin-top:0px}.mt-12{margin-top:3rem}.mt-2{margin-top:0.5rem}.mt-4{margin-top:1rem}.mt-6{margin-top:1.5rem}.mt-8{margin-top:2rem}.block{display:block}.flex{display:flex}.grid{display:grid}.max-w-4xl{max-width:56rem}.list-disc{list-style-type:disc}.justify-center{justify-content:center}.gap-4{gap:1rem}.gap-8{gap:2rem}.space-y-2 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.5rem * var(--tw-space-y-reverse))}.space-y-4 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1rem * var(--tw-space-y-reverse))}.space-y-6 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1.5rem * var(--tw-space-y-reverse))}.rounded{border-radius:0.25rem}.rounded-lg{border-radius:0.5rem}.border{border-width:1px}.border-l-4{border-left-width:4px}.border-amber-400{--tw-border-opacity:1;border-color:rgb(251 191 36 / var(--tw-border-opacity, 1))}.border-blue-500{--tw-border-opacity:1;border-color:rgb(59 130 246 / var(--tw-border-opacity, 1))}.border-slate-200{--tw-border-opacity:1;border-color:rgb(226 232 240 / var(--tw-border-opacity, 1))}.bg-amber-50{--tw-bg-opacity:1;background-color:rgb(255 251 235 / var(--tw-bg-opacity, 1))}.bg-blue-900{--tw-bg-opacity:1;background-color:rgb(30 58 138 / var(--tw-bg-opacity, 1))}.bg-slate-50{--tw-bg-opacity:1;background-color:rgb(248 250 252 / var(--tw-bg-opacity, 1))}.p-4{padding:1rem}.p-8{padding:2rem}.px-4{padding-left:1rem;padding-right:1rem}.py-12{padding-top:3rem;padding-bottom:3rem}.py-20{padding-top:5rem;padding-bottom:5rem}.pl-4{padding-left:1rem}.text-center{text-align:center}.text-2xl{font-size:1.5rem;line-height:2rem}.text-5xl{font-size:3rem;line-height:1}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-bold{font-weight:700}.font-light{font-weight:300}.font-medium{font-weight:500}.font-semibold{font-weight:600}.uppercase{text-transform:uppercase}.text-amber-700{--tw-text-opacity:1;color:rgb(180 83 9 / var(--tw-text-opacity, 1))}.text-amber-800{--tw-text-opacity:1;color:rgb(146 64 14 / var(--tw-text-opacity, 1))}.text-blue-100{--tw-text-opacity:1;color:rgb(219 234 254 / var(--tw-text-opacity, 1))}.text-green-600{--tw-text-opacity:1;color:rgb(22 163 74 / var(--tw-text-opacity, 1))}.text-red-600{--tw-text-opacity:1;color:rgb(220 38 38 / var(--tw-text-opacity, 1))}.text-slate-400{--tw-text-opacity:1;color:rgb(148 163 184 / var(--tw-text-opacity, 1))}.text-slate-500{--tw-text-opacity:1;color:rgb(100 116 139 / var(--tw-text-opacity, 1))}.text-slate-700{--tw-text-opacity:1;color:rgb(51 65 85 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}@media (min-width: 768px){.md\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.md\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.md\:px-0{padding-left:0px;padding-right:0px}}</style></head>
<body class="py-12 px-4 md:px-0">

    <button id="downloadBtn" onclick="downloadFile()" style="display: none;">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="7 10 12 15 17 10"></polyline><line x1="12" y1="15" x2="12" y2="3"></line></svg>
        Download Report (.html)
    </button>

    <div class="max-w-4xl mx-auto">
        <!-- Cover Page -->
        <header class="card text-center py-20">
            <h1 class="text-5xl mb-4">Implementing a RAG System</h1>
            <p class="text-2xl text-slate-500 mb-8 font-light">Comprehensive Case Study: Food &amp; Beverage Industry</p>
            <div class="flex justify-center gap-4 text-sm text-slate-400 font-medium">
                <span>RETAIL OPERATIONS</span>
                <span>•</span>
                <span>AI STRATEGY</span>
                <span>•</span>
                <span>COMPLIANCE</span>
            </div>
        </header>

        <div class="page-break"></div>

        <!-- Milestone 1 -->
        <section class="card">
            <h2><span class="milestone-badge">Milestone 1</span>Use Case Definition</h2>
            <div class="space-y-4">
                <p class="text-lg font-semibold text-slate-700">Project Objective:</p>
                <p>To implement a Retrieval-Augmented Generation (RAG) system that serves as a central intelligence hub for a large food retailer, focusing on <strong>Regulatory Compliance</strong> and <strong>Internal Training</strong>.</p>
                
                <h3 class="border-l-4 border-blue-500 pl-4">Primary Use Cases</h3>
                <ul class="list-disc ml-6 space-y-2">
                    <li><strong>Labeling Compliance:</strong> Automated verification of allergen warnings and nutritional formatting against the latest 2024/2025 FDA/International guidelines.</li>
                    <li><strong>Recipe Management:</strong> Providing employees with step-by-step assembly guides for complex prepared foods while ensuring proprietary ingredient ratios remain secure.</li>
                    <li><strong>Onboarding &amp; Support:</strong> Reducing the time-to-competency for new hires by providing an "Expert Assistant" that answers operational questions instantly.</li>
                </ul>

                <h3 class="border-l-4 border-blue-500 pl-4">Key Stakeholders</h3>
                <div class="grid md:grid-cols-3 gap-4 mt-2">
                    <div class="bg-slate-50 p-4 rounded border border-slate-200">
                        <span class="block font-bold">Store Managers</span>
                        <span class="text-xs text-slate-500 uppercase">Operational Efficiency</span>
                    </div>
                    <div class="bg-slate-50 p-4 rounded border border-slate-200">
                        <span class="block font-bold">Compliance Officers</span>
                        <span class="text-xs text-slate-500 uppercase">Risk Mitigation</span>
                    </div>
                    <div class="bg-slate-50 p-4 rounded border border-slate-200">
                        <span class="block font-bold">IT/AI Architects</span>
                        <span class="text-xs text-slate-500 uppercase">System Integrity</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Milestone 2 -->
        <section class="card">
            <h2><span class="milestone-badge">Milestone 2</span>System Architecture</h2>
            <p class="mb-6">The system architecture is designed to bridge the gap between static legacy policy documents and a dynamic user interface.</p>
            
            <div class="diagram-box">
                <div class="mermaid" data-processed="true"><svg id="mermaid-1769476881102" width="100%" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="flowchart" style="max-width: 446.8203125px;" viewBox="0 0 446.8203125 1025.447265625" role="graphics-document document" aria-roledescription="flowchart-v2"><style>#mermaid-1769476881102{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1769476881102 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1769476881102 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1769476881102 .error-icon{fill:#552222;}#mermaid-1769476881102 .error-text{fill:#552222;stroke:#552222;}#mermaid-1769476881102 .edge-thickness-normal{stroke-width:1px;}#mermaid-1769476881102 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1769476881102 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1769476881102 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1769476881102 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1769476881102 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1769476881102 .marker{fill:#666;stroke:#666;}#mermaid-1769476881102 .marker.cross{stroke:#666;}#mermaid-1769476881102 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1769476881102 p{margin:0;}#mermaid-1769476881102 .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-1769476881102 .cluster-label text{fill:#333;}#mermaid-1769476881102 .cluster-label span{color:#333;}#mermaid-1769476881102 .cluster-label span p{background-color:transparent;}#mermaid-1769476881102 .label text,#mermaid-1769476881102 span{fill:#000000;color:#000000;}#mermaid-1769476881102 .node rect,#mermaid-1769476881102 .node circle,#mermaid-1769476881102 .node ellipse,#mermaid-1769476881102 .node polygon,#mermaid-1769476881102 .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-1769476881102 .rough-node .label text,#mermaid-1769476881102 .node .label text,#mermaid-1769476881102 .image-shape .label,#mermaid-1769476881102 .icon-shape .label{text-anchor:middle;}#mermaid-1769476881102 .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-1769476881102 .rough-node .label,#mermaid-1769476881102 .node .label,#mermaid-1769476881102 .image-shape .label,#mermaid-1769476881102 .icon-shape .label{text-align:center;}#mermaid-1769476881102 .node.clickable{cursor:pointer;}#mermaid-1769476881102 .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-1769476881102 .arrowheadPath{fill:#333333;}#mermaid-1769476881102 .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-1769476881102 .flowchart-link{stroke:#666;fill:none;}#mermaid-1769476881102 .edgeLabel{background-color:white;text-align:center;}#mermaid-1769476881102 .edgeLabel p{background-color:white;}#mermaid-1769476881102 .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1769476881102 .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-1769476881102 .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-1769476881102 .cluster text{fill:#333;}#mermaid-1769476881102 .cluster span{color:#333;}#mermaid-1769476881102 div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-1769476881102 .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-1769476881102 rect.text{fill:none;stroke-width:0;}#mermaid-1769476881102 .icon-shape,#mermaid-1769476881102 .image-shape{background-color:white;text-align:center;}#mermaid-1769476881102 .icon-shape p,#mermaid-1769476881102 .image-shape p{background-color:white;padding:2px;}#mermaid-1769476881102 .icon-shape rect,#mermaid-1769476881102 .image-shape rect{opacity:0.5;background-color:white;fill:white;}#mermaid-1769476881102 .label-icon{display:inline-block;height:1em;overflow:visible;vertical-align:-0.125em;}#mermaid-1769476881102 .node .label-icon path{fill:currentColor;stroke:revert;stroke-width:revert;}#mermaid-1769476881102 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}</style><g><marker id="mermaid-1769476881102_flowchart-v2-pointEnd" class="marker flowchart-v2" viewBox="0 0 10 10" refX="5" refY="5" markerUnits="userSpaceOnUse" markerWidth="8" markerHeight="8" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowMarkerPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker><marker id="mermaid-1769476881102_flowchart-v2-pointStart" class="marker flowchart-v2" viewBox="0 0 10 10" refX="4.5" refY="5" markerUnits="userSpaceOnUse" markerWidth="8" markerHeight="8" orient="auto"><path d="M 0 5 L 10 10 L 10 0 z" class="arrowMarkerPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker><marker id="mermaid-1769476881102_flowchart-v2-circleEnd" class="marker flowchart-v2" viewBox="0 0 10 10" refX="11" refY="5" markerUnits="userSpaceOnUse" markerWidth="11" markerHeight="11" orient="auto"><circle cx="5" cy="5" r="5" class="arrowMarkerPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></circle></marker><marker id="mermaid-1769476881102_flowchart-v2-circleStart" class="marker flowchart-v2" viewBox="0 0 10 10" refX="-1" refY="5" markerUnits="userSpaceOnUse" markerWidth="11" markerHeight="11" orient="auto"><circle cx="5" cy="5" r="5" class="arrowMarkerPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></circle></marker><marker id="mermaid-1769476881102_flowchart-v2-crossEnd" class="marker cross flowchart-v2" viewBox="0 0 11 11" refX="12" refY="5.2" markerUnits="userSpaceOnUse" markerWidth="11" markerHeight="11" orient="auto"><path d="M 1,1 l 9,9 M 10,1 l -9,9" class="arrowMarkerPath" style="stroke-width: 2; stroke-dasharray: 1, 0;"></path></marker><marker id="mermaid-1769476881102_flowchart-v2-crossStart" class="marker cross flowchart-v2" viewBox="0 0 11 11" refX="-1" refY="5.2" markerUnits="userSpaceOnUse" markerWidth="11" markerHeight="11" orient="auto"><path d="M 1,1 l 9,9 M 10,1 l -9,9" class="arrowMarkerPath" style="stroke-width: 2; stroke-dasharray: 1, 0;"></path></marker><g class="root"><g class="clusters"><g class="cluster" id="Retrieval_Generation" data-look="classic"><rect style="" x="13.408859252929688" y="497.4473190307617" width="351.30468368530273" height="520"></rect><g class="cluster-label" transform="translate(155.31120109558105, 497.4473190307617)"><foreignObject width="67.5" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>RAG Core</p></span></div></foreignObject></g></g><g class="cluster" id="Data_Ingestion" data-look="classic"><rect style="" x="8" y="8" width="430.82031631469727" height="439.4473190307617"></rect><g class="cluster-label" transform="translate(141.20703315734863, 8)"><foreignObject width="164.40625" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Data Ingestion Pipeline</p></span></div></foreignObject></g></g></g><g class="edgePaths"><path d="M124.516,87L124.516,91.167C124.516,95.333,124.516,103.667,131.751,111.687C138.987,119.707,153.458,127.413,160.693,131.266L167.929,135.12" id="L_PDF_C_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_PDF_C_0" data-points="W3sieCI6MTI0LjUxNTYyNSwieSI6ODd9LHsieCI6MTI0LjUxNTYyNSwieSI6MTEyfSx7IngiOjE3MS40NTk0ODU3ODc2MTE3NSwieSI6MTM3fV0=" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M319.802,87L319.802,91.167C319.802,95.333,319.802,103.667,312.567,111.687C305.331,119.707,290.86,127.413,283.624,131.266L276.389,135.12" id="L_EXL_C_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_EXL_C_0" data-points="W3sieCI6MzE5LjgwMjA4NTg3NjQ2NDg0LCJ5Ijo4N30seyJ4IjozMTkuODAyMDg1ODc2NDY0ODQsInkiOjExMn0seyJ4IjoyNzIuODU4MjI1MDg4ODUzMSwieSI6MTM3fV0=" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M222.159,191L222.159,195.167C222.159,199.333,222.159,207.667,222.159,215.333C222.159,223,222.159,230,222.159,233.5L222.159,237" id="L_C_EMB_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_C_EMB_0" data-points="W3sieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5IjoxOTF9LHsieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5IjoyMTZ9LHsieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5IjoyNDF9XQ==" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M222.159,295L222.159,299.167C222.159,303.333,222.159,311.667,222.159,319.333C222.159,327,222.159,334,222.159,337.5L222.159,341" id="L_EMB_VDB_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_EMB_VDB_0" data-points="W3sieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5IjoyOTV9LHsieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5IjozMjB9LHsieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5IjozNDV9XQ==" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M152.576,888.447L152.576,892.614C152.576,896.781,152.576,905.114,157.617,913.048C162.659,920.982,172.742,928.518,177.783,932.285L182.825,936.053" id="L_UI_Q_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_UI_Q_0" data-points="W3sieCI6MTUyLjU3NTUyMzM3NjQ2NDg0LCJ5Ijo4ODguNDQ3MzE5MDMwNzYxN30seyJ4IjoxNTIuNTc1NTIzMzc2NDY0ODQsInkiOjkxMy40NDczMTkwMzA3NjE3fSx7IngiOjE4Ni4wMjkwNDg0MDYxNjA4LCJ5Ijo5MzguNDQ3MzE5MDMwNzYxN31d" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M258.289,938.447L263.864,934.281C269.44,930.114,280.591,921.781,286.167,908.947C291.742,896.114,291.742,878.781,291.742,861.447C291.742,844.114,291.742,826.781,291.742,809.447C291.742,792.114,291.742,774.781,291.742,757.447C291.742,740.114,291.742,722.781,291.742,705.447C291.742,688.114,291.742,670.781,291.742,653.447C291.742,636.114,291.742,618.781,286.701,606.346C281.659,593.912,271.576,586.377,266.534,582.609L261.493,578.842" id="L_Q_RET_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_Q_RET_0" data-points="W3sieCI6MjU4LjI4ODY2MjQ3MDMwNDEsInkiOjkzOC40NDczMTkwMzA3NjE3fSx7IngiOjI5MS43NDIxODc1LCJ5Ijo5MTMuNDQ3MzE5MDMwNzYxN30seyJ4IjoyOTEuNzQyMTg3NSwieSI6ODYxLjQ0NzMxOTAzMDc2MTd9LHsieCI6MjkxLjc0MjE4NzUsInkiOjgwOS40NDczMTkwMzA3NjE3fSx7IngiOjI5MS43NDIxODc1LCJ5Ijo3NTcuNDQ3MzE5MDMwNzYxN30seyJ4IjoyOTEuNzQyMTg3NSwieSI6NzA1LjQ0NzMxOTAzMDc2MTd9LHsieCI6MjkxLjc0MjE4NzUsInkiOjY1My40NDczMTkwMzA3NjE3fSx7IngiOjI5MS43NDIxODc1LCJ5Ijo2MDEuNDQ3MzE5MDMwNzYxN30seyJ4IjoyNTguMjg4NjYyNDcwMzA0MSwieSI6NTc2LjQ0NzMxOTAzMDc2MTd9XQ==" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M222.159,426.447L222.159,429.947C222.159,433.447,222.159,440.447,222.159,448.114C222.159,455.781,222.159,464.114,222.159,472.447C222.159,480.781,222.159,489.114,222.159,496.781C222.159,504.447,222.159,511.447,222.159,514.947L222.159,518.447" id="L_VDB_RET_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_VDB_RET_0" data-points="W3sieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5Ijo0MjIuNDQ3MzE5MDMwNzYxN30seyJ4IjoyMjIuMTU4ODU1NDM4MjMyNDIsInkiOjQ0Ny40NDczMTkwMzA3NjE3fSx7IngiOjIyMi4xNTg4NTU0MzgyMzI0MiwieSI6NDcyLjQ0NzMxOTAzMDc2MTd9LHsieCI6MjIyLjE1ODg1NTQzODIzMjQyLCJ5Ijo0OTcuNDQ3MzE5MDMwNzYxN30seyJ4IjoyMjIuMTU4ODU1NDM4MjMyNDIsInkiOjUyMi40NDczMTkwMzA3NjE3fV0=" marker-start="url(#mermaid-1769476881102_flowchart-v2-pointStart)" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M186.029,576.447L180.453,580.614C174.878,584.781,163.727,593.114,158.151,600.781C152.576,608.447,152.576,615.447,152.576,618.947L152.576,622.447" id="L_RET_LLM_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_RET_LLM_0" data-points="W3sieCI6MTg2LjAyOTA0ODQwNjE2MDgsInkiOjU3Ni40NDczMTkwMzA3NjE3fSx7IngiOjE1Mi41NzU1MjMzNzY0NjQ4NCwieSI6NjAxLjQ0NzMxOTAzMDc2MTd9LHsieCI6MTUyLjU3NTUyMzM3NjQ2NDg0LCJ5Ijo2MjYuNDQ3MzE5MDMwNzYxN31d" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M152.576,680.447L152.576,684.614C152.576,688.781,152.576,697.114,152.576,704.781C152.576,712.447,152.576,719.447,152.576,722.947L152.576,726.447" id="L_LLM_RES_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_LLM_RES_0" data-points="W3sieCI6MTUyLjU3NTUyMzM3NjQ2NDg0LCJ5Ijo2ODAuNDQ3MzE5MDMwNzYxN30seyJ4IjoxNTIuNTc1NTIzMzc2NDY0ODQsInkiOjcwNS40NDczMTkwMzA3NjE3fSx7IngiOjE1Mi41NzU1MjMzNzY0NjQ4NCwieSI6NzMwLjQ0NzMxOTAzMDc2MTd9XQ==" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path><path d="M152.576,784.447L152.576,788.614C152.576,792.781,152.576,801.114,152.576,808.781C152.576,816.447,152.576,823.447,152.576,826.947L152.576,830.447" id="L_RES_UI_0" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" style=";" data-edge="true" data-et="edge" data-id="L_RES_UI_0" data-points="W3sieCI6MTUyLjU3NTUyMzM3NjQ2NDg0LCJ5Ijo3ODQuNDQ3MzE5MDMwNzYxN30seyJ4IjoxNTIuNTc1NTIzMzc2NDY0ODQsInkiOjgwOS40NDczMTkwMzA3NjE3fSx7IngiOjE1Mi41NzU1MjMzNzY0NjQ4NCwieSI6ODM0LjQ0NzMxOTAzMDc2MTd9XQ==" marker-end="url(#mermaid-1769476881102_flowchart-v2-pointEnd)"></path></g><g class="edgeLabels"><g class="edgeLabel"><g class="label" data-id="L_PDF_C_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_EXL_C_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_C_EMB_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_EMB_VDB_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_UI_Q_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_Q_RET_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_VDB_RET_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_RET_LLM_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_LLM_RES_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g class="label" data-id="L_RES_UI_0" transform="translate(0, 0)"><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" class="labelBkg" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g></g><g class="nodes"><g class="node default" id="flowchart-PDF-0" transform="translate(124.515625, 60)"><rect class="basic label-container" style="" x="-70.140625" y="-27" width="140.28125" height="54"></rect><g class="label" style="" transform="translate(-40.140625, -12)"><rect></rect><foreignObject width="80.28125" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Policy PDFs</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-C-1" transform="translate(222.15885543823242, 164)"><rect class="basic label-container" style="" x="-80.203125" y="-27" width="160.40625" height="54"></rect><g class="label" style="" transform="translate(-50.203125, -12)"><rect></rect><foreignObject width="100.40625" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Text Chunking</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-EXL-2" transform="translate(319.80208587646484, 60)"><rect class="basic label-container" style="" x="-75.14583587646484" y="-27" width="150.2916717529297" height="54"></rect><g class="label" style="" transform="translate(-45.145835876464844, -12)"><rect></rect><foreignObject width="90.29167175292969" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Recipe Excel</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-EMB-5" transform="translate(222.15885543823242, 268)"><rect class="basic label-container" style="" x="-92.890625" y="-27" width="185.78125" height="54"></rect><g class="label" style="" transform="translate(-62.890625, -12)"><rect></rect><foreignObject width="125.78125" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Embedding Model</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-VDB-7" transform="translate(222.15885543823242, 383.72365951538086)"><path d="M0,12.815774752226819 a65.73958587646484,12.815774752226819 0,0,0 131.4791717529297,0 a65.73958587646484,12.815774752226819 0,0,0 -131.4791717529297,0 l0,51.815774752226815 a65.73958587646484,12.815774752226819 0,0,0 131.4791717529297,0 l0,-51.815774752226815" class="basic label-container" style="fill:#dbeafe !important;stroke:#1e40af !important;stroke-width:2px !important" transform="translate(-65.73958587646484, -38.72366212834022)"></path><g class="label" style="" transform="translate(-58.239585876464844, -2)"><rect></rect><foreignObject width="116.47917175292969" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Vector Database</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-UI-8" transform="translate(152.57552337646484, 861.4473190307617)"><rect class="basic label-container" style="" x="-81.03646087646484" y="-27" width="162.0729217529297" height="54"></rect><g class="label" style="" transform="translate(-51.036460876464844, -12)"><rect></rect><foreignObject width="102.07292175292969" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>User Interface</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-Q-9" transform="translate(222.15885543823242, 965.4473190307617)"><rect class="basic label-container" style="" x="-84.29166793823242" y="-27" width="168.58333587646484" height="54"></rect><g class="label" style="" transform="translate(-54.29166793823242, -12)"><rect></rect><foreignObject width="108.58333587646484" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Query Rewriter</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-RET-11" transform="translate(222.15885543823242, 549.4473190307617)"><rect class="basic label-container" style="" x="-90.94271087646484" y="-27" width="181.8854217529297" height="54"></rect><g class="label" style="" transform="translate(-60.942710876464844, -12)"><rect></rect><foreignObject width="121.88542175292969" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Retriever Module</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-LLM-15" transform="translate(152.57552337646484, 653.4473190307617)"><rect class="basic label-container" style="fill:#fef08a !important;stroke:#a16207 !important;stroke-width:2px !important" x="-102.03125" y="-27" width="204.0625" height="54"></rect><g class="label" style="" transform="translate(-72.03125, -12)"><rect></rect><foreignObject width="144.0625" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Generative AI Model</p></span></div></foreignObject></g></g><g class="node default" id="flowchart-RES-17" transform="translate(152.57552337646484, 757.4473190307617)"><rect class="basic label-container" style="" x="-104.16667175292969" y="-27" width="208.33334350585938" height="54"></rect><g class="label" style="" transform="translate(-74.16667175292969, -12)"><rect></rect><foreignObject width="148.33334350585938" height="24"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Contextual Response</p></span></div></foreignObject></g></g></g></g></g></svg></div>
                <p class="text-center text-xs text-slate-400 mt-4">Figure 1: High-level System Architecture showing data ingestion and real-time retrieval.</p>
            </div>
            
            <div class="mt-6 space-y-2">
                <p><strong>Components:</strong></p>
                <ul class="list-disc ml-6">
                    <li><strong>Retriever:</strong> Uses semantic search to find the most relevant policy snippets.</li>
                    <li><strong>Knowledge Base:</strong> A vector-indexed store of the company’s internal training manuals.</li>
                    <li><strong>Generative Model:</strong> Summarizes retrieved data into "Natural Language" instructions.</li>
                </ul>
            </div>
        </section>

        <div class="page-break"></div>

        <!-- Milestone 3 -->
        <section class="card">
            <h2><span class="milestone-badge">Milestone 3</span>Simulated Workflow</h2>
            <p class="mb-6">This sequence demonstrates the path a query takes from the store floor to the final generated advice.</p>

            <div class="diagram-box">
                <div class="mermaid" data-processed="true"><svg id="mermaid-1769476881538" width="100%" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" style="max-width: 1246px;" viewBox="-50 -10 1246 459" role="graphics-document document" aria-roledescription="sequence"><g><rect x="996" y="373" fill="#eaeaea" stroke="#666" width="150" height="65" name="AI" rx="3" ry="3" class="actor actor-bottom"></rect><text x="1071" y="405.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="1071" dy="0">Generative LLM</tspan></text></g><g><rect x="796" y="373" fill="#eaeaea" stroke="#666" width="150" height="65" name="VDB" rx="3" ry="3" class="actor actor-bottom"></rect><text x="871" y="405.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="871" dy="0">Vector Store</tspan></text></g><g><rect x="425.5" y="373" fill="#eaeaea" stroke="#666" width="153" height="65" name="RAG" rx="3" ry="3" class="actor actor-bottom"></rect><text x="502" y="405.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="502" dy="0">RAG Orchestrator</tspan></text></g><g><rect x="0" y="373" fill="#eaeaea" stroke="#666" width="150" height="65" name="User" rx="3" ry="3" class="actor actor-bottom"></rect><text x="75" y="405.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="75" dy="0">Employee (iPad)</tspan></text></g><g><line id="actor3" x1="1071" y1="65" x2="1071" y2="373" class="actor-line 200" stroke-width="0.5px" stroke="#999" name="AI"></line><g id="root-3"><rect x="996" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" name="AI" rx="3" ry="3" class="actor actor-top"></rect><text x="1071" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="1071" dy="0">Generative LLM</tspan></text></g></g><g><line id="actor2" x1="871" y1="65" x2="871" y2="373" class="actor-line 200" stroke-width="0.5px" stroke="#999" name="VDB"></line><g id="root-2"><rect x="796" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" name="VDB" rx="3" ry="3" class="actor actor-top"></rect><text x="871" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="871" dy="0">Vector Store</tspan></text></g></g><g><line id="actor1" x1="502" y1="65" x2="502" y2="373" class="actor-line 200" stroke-width="0.5px" stroke="#999" name="RAG"></line><g id="root-1"><rect x="425.5" y="0" fill="#eaeaea" stroke="#666" width="153" height="65" name="RAG" rx="3" ry="3" class="actor actor-top"></rect><text x="502" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="502" dy="0">RAG Orchestrator</tspan></text></g></g><g><line id="actor0" x1="75" y1="65" x2="75" y2="373" class="actor-line 200" stroke-width="0.5px" stroke="#999" name="User"></line><g id="root-0"><rect x="0" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" name="User" rx="3" ry="3" class="actor actor-top"></rect><text x="75" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor actor-box" style="text-anchor: middle; font-size: 16px; font-weight: 400;"><tspan x="75" dy="0">Employee (iPad)</tspan></text></g></g><style>#mermaid-1769476881538{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1769476881538 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1769476881538 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1769476881538 .error-icon{fill:#552222;}#mermaid-1769476881538 .error-text{fill:#552222;stroke:#552222;}#mermaid-1769476881538 .edge-thickness-normal{stroke-width:1px;}#mermaid-1769476881538 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1769476881538 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1769476881538 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1769476881538 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1769476881538 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1769476881538 .marker{fill:#666;stroke:#666;}#mermaid-1769476881538 .marker.cross{stroke:#666;}#mermaid-1769476881538 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1769476881538 p{margin:0;}#mermaid-1769476881538 .actor{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1769476881538 text.actor&gt;tspan{fill:#333;stroke:none;}#mermaid-1769476881538 .actor-line{stroke:hsl(0, 0%, 83%);}#mermaid-1769476881538 .innerArc{stroke-width:1.5;stroke-dasharray:none;}#mermaid-1769476881538 .messageLine0{stroke-width:1.5;stroke-dasharray:none;stroke:#333;}#mermaid-1769476881538 .messageLine1{stroke-width:1.5;stroke-dasharray:2,2;stroke:#333;}#mermaid-1769476881538 #arrowhead path{fill:#333;stroke:#333;}#mermaid-1769476881538 .sequenceNumber{fill:white;}#mermaid-1769476881538 #sequencenumber{fill:#333;}#mermaid-1769476881538 #crosshead path{fill:#333;stroke:#333;}#mermaid-1769476881538 .messageText{fill:#333;stroke:none;}#mermaid-1769476881538 .labelBox{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1769476881538 .labelText,#mermaid-1769476881538 .labelText&gt;tspan{fill:#333;stroke:none;}#mermaid-1769476881538 .loopText,#mermaid-1769476881538 .loopText&gt;tspan{fill:#333;stroke:none;}#mermaid-1769476881538 .loopLine{stroke-width:2px;stroke-dasharray:2,2;stroke:hsl(0, 0%, 83%);fill:hsl(0, 0%, 83%);}#mermaid-1769476881538 .note{stroke:#999;fill:#666;}#mermaid-1769476881538 .noteText,#mermaid-1769476881538 .noteText&gt;tspan{fill:#fff;stroke:none;}#mermaid-1769476881538 .activation0{fill:#f4f4f4;stroke:#666;}#mermaid-1769476881538 .activation1{fill:#f4f4f4;stroke:#666;}#mermaid-1769476881538 .activation2{fill:#f4f4f4;stroke:#666;}#mermaid-1769476881538 .actorPopupMenu{position:absolute;}#mermaid-1769476881538 .actorPopupMenuPanel{position:absolute;fill:#eee;box-shadow:0px 8px 16px 0px rgba(0,0,0,0.2);filter:drop-shadow(3px 5px 2px rgb(0 0 0 / 0.4));}#mermaid-1769476881538 .actor-man line{stroke:hsl(0, 0%, 83%);fill:#eee;}#mermaid-1769476881538 .actor-man circle,#mermaid-1769476881538 line{stroke:hsl(0, 0%, 83%);fill:#eee;stroke-width:2px;}#mermaid-1769476881538 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}</style><g></g><defs><symbol id="computer" width="24" height="24"><path transform="scale(.5)" d="M2 2v13h20v-13h-20zm18 11h-16v-9h16v9zm-10.228 6l.466-1h3.524l.467 1h-4.457zm14.228 3h-24l2-6h2.104l-1.33 4h18.45l-1.297-4h2.073l2 6zm-5-10h-14v-7h14v7z"></path></symbol></defs><defs><symbol id="database" fill-rule="evenodd" clip-rule="evenodd"><path transform="scale(.5)" d="M12.258.001l.256.004.255.005.253.008.251.01.249.012.247.015.246.016.242.019.241.02.239.023.236.024.233.027.231.028.229.031.225.032.223.034.22.036.217.038.214.04.211.041.208.043.205.045.201.046.198.048.194.05.191.051.187.053.183.054.18.056.175.057.172.059.168.06.163.061.16.063.155.064.15.066.074.033.073.033.071.034.07.034.069.035.068.035.067.035.066.035.064.036.064.036.062.036.06.036.06.037.058.037.058.037.055.038.055.038.053.038.052.038.051.039.05.039.048.039.047.039.045.04.044.04.043.04.041.04.04.041.039.041.037.041.036.041.034.041.033.042.032.042.03.042.029.042.027.042.026.043.024.043.023.043.021.043.02.043.018.044.017.043.015.044.013.044.012.044.011.045.009.044.007.045.006.045.004.045.002.045.001.045v17l-.001.045-.002.045-.004.045-.006.045-.007.045-.009.044-.011.045-.012.044-.013.044-.015.044-.017.043-.018.044-.02.043-.021.043-.023.043-.024.043-.026.043-.027.042-.029.042-.03.042-.032.042-.033.042-.034.041-.036.041-.037.041-.039.041-.04.041-.041.04-.043.04-.044.04-.045.04-.047.039-.048.039-.05.039-.051.039-.052.038-.053.038-.055.038-.055.038-.058.037-.058.037-.06.037-.06.036-.062.036-.064.036-.064.036-.066.035-.067.035-.068.035-.069.035-.07.034-.071.034-.073.033-.074.033-.15.066-.155.064-.16.063-.163.061-.168.06-.172.059-.175.057-.18.056-.183.054-.187.053-.191.051-.194.05-.198.048-.201.046-.205.045-.208.043-.211.041-.214.04-.217.038-.22.036-.223.034-.225.032-.229.031-.231.028-.233.027-.236.024-.239.023-.241.02-.242.019-.246.016-.247.015-.249.012-.251.01-.253.008-.255.005-.256.004-.258.001-.258-.001-.256-.004-.255-.005-.253-.008-.251-.01-.249-.012-.247-.015-.245-.016-.243-.019-.241-.02-.238-.023-.236-.024-.234-.027-.231-.028-.228-.031-.226-.032-.223-.034-.22-.036-.217-.038-.214-.04-.211-.041-.208-.043-.204-.045-.201-.046-.198-.048-.195-.05-.19-.051-.187-.053-.184-.054-.179-.056-.176-.057-.172-.059-.167-.06-.164-.061-.159-.063-.155-.064-.151-.066-.074-.033-.072-.033-.072-.034-.07-.034-.069-.035-.068-.035-.067-.035-.066-.035-.064-.036-.063-.036-.062-.036-.061-.036-.06-.037-.058-.037-.057-.037-.056-.038-.055-.038-.053-.038-.052-.038-.051-.039-.049-.039-.049-.039-.046-.039-.046-.04-.044-.04-.043-.04-.041-.04-.04-.041-.039-.041-.037-.041-.036-.041-.034-.041-.033-.042-.032-.042-.03-.042-.029-.042-.027-.042-.026-.043-.024-.043-.023-.043-.021-.043-.02-.043-.018-.044-.017-.043-.015-.044-.013-.044-.012-.044-.011-.045-.009-.044-.007-.045-.006-.045-.004-.045-.002-.045-.001-.045v-17l.001-.045.002-.045.004-.045.006-.045.007-.045.009-.044.011-.045.012-.044.013-.044.015-.044.017-.043.018-.044.02-.043.021-.043.023-.043.024-.043.026-.043.027-.042.029-.042.03-.042.032-.042.033-.042.034-.041.036-.041.037-.041.039-.041.04-.041.041-.04.043-.04.044-.04.046-.04.046-.039.049-.039.049-.039.051-.039.052-.038.053-.038.055-.038.056-.038.057-.037.058-.037.06-.037.061-.036.062-.036.063-.036.064-.036.066-.035.067-.035.068-.035.069-.035.07-.034.072-.034.072-.033.074-.033.151-.066.155-.064.159-.063.164-.061.167-.06.172-.059.176-.057.179-.056.184-.054.187-.053.19-.051.195-.05.198-.048.201-.046.204-.045.208-.043.211-.041.214-.04.217-.038.22-.036.223-.034.226-.032.228-.031.231-.028.234-.027.236-.024.238-.023.241-.02.243-.019.245-.016.247-.015.249-.012.251-.01.253-.008.255-.005.256-.004.258-.001.258.001zm-9.258 20.499v.01l.001.021.003.021.004.022.005.021.006.022.007.022.009.023.01.022.011.023.012.023.013.023.015.023.016.024.017.023.018.024.019.024.021.024.022.025.023.024.024.025.052.049.056.05.061.051.066.051.07.051.075.051.079.052.084.052.088.052.092.052.097.052.102.051.105.052.11.052.114.051.119.051.123.051.127.05.131.05.135.05.139.048.144.049.147.047.152.047.155.047.16.045.163.045.167.043.171.043.176.041.178.041.183.039.187.039.19.037.194.035.197.035.202.033.204.031.209.03.212.029.216.027.219.025.222.024.226.021.23.02.233.018.236.016.24.015.243.012.246.01.249.008.253.005.256.004.259.001.26-.001.257-.004.254-.005.25-.008.247-.011.244-.012.241-.014.237-.016.233-.018.231-.021.226-.021.224-.024.22-.026.216-.027.212-.028.21-.031.205-.031.202-.034.198-.034.194-.036.191-.037.187-.039.183-.04.179-.04.175-.042.172-.043.168-.044.163-.045.16-.046.155-.046.152-.047.148-.048.143-.049.139-.049.136-.05.131-.05.126-.05.123-.051.118-.052.114-.051.11-.052.106-.052.101-.052.096-.052.092-.052.088-.053.083-.051.079-.052.074-.052.07-.051.065-.051.06-.051.056-.05.051-.05.023-.024.023-.025.021-.024.02-.024.019-.024.018-.024.017-.024.015-.023.014-.024.013-.023.012-.023.01-.023.01-.022.008-.022.006-.022.006-.022.004-.022.004-.021.001-.021.001-.021v-4.127l-.077.055-.08.053-.083.054-.085.053-.087.052-.09.052-.093.051-.095.05-.097.05-.1.049-.102.049-.105.048-.106.047-.109.047-.111.046-.114.045-.115.045-.118.044-.12.043-.122.042-.124.042-.126.041-.128.04-.13.04-.132.038-.134.038-.135.037-.138.037-.139.035-.142.035-.143.034-.144.033-.147.032-.148.031-.15.03-.151.03-.153.029-.154.027-.156.027-.158.026-.159.025-.161.024-.162.023-.163.022-.165.021-.166.02-.167.019-.169.018-.169.017-.171.016-.173.015-.173.014-.175.013-.175.012-.177.011-.178.01-.179.008-.179.008-.181.006-.182.005-.182.004-.184.003-.184.002h-.37l-.184-.002-.184-.003-.182-.004-.182-.005-.181-.006-.179-.008-.179-.008-.178-.01-.176-.011-.176-.012-.175-.013-.173-.014-.172-.015-.171-.016-.17-.017-.169-.018-.167-.019-.166-.02-.165-.021-.163-.022-.162-.023-.161-.024-.159-.025-.157-.026-.156-.027-.155-.027-.153-.029-.151-.03-.15-.03-.148-.031-.146-.032-.145-.033-.143-.034-.141-.035-.14-.035-.137-.037-.136-.037-.134-.038-.132-.038-.13-.04-.128-.04-.126-.041-.124-.042-.122-.042-.12-.044-.117-.043-.116-.045-.113-.045-.112-.046-.109-.047-.106-.047-.105-.048-.102-.049-.1-.049-.097-.05-.095-.05-.093-.052-.09-.051-.087-.052-.085-.053-.083-.054-.08-.054-.077-.054v4.127zm0-5.654v.011l.001.021.003.021.004.021.005.022.006.022.007.022.009.022.01.022.011.023.012.023.013.023.015.024.016.023.017.024.018.024.019.024.021.024.022.024.023.025.024.024.052.05.056.05.061.05.066.051.07.051.075.052.079.051.084.052.088.052.092.052.097.052.102.052.105.052.11.051.114.051.119.052.123.05.127.051.131.05.135.049.139.049.144.048.147.048.152.047.155.046.16.045.163.045.167.044.171.042.176.042.178.04.183.04.187.038.19.037.194.036.197.034.202.033.204.032.209.03.212.028.216.027.219.025.222.024.226.022.23.02.233.018.236.016.24.014.243.012.246.01.249.008.253.006.256.003.259.001.26-.001.257-.003.254-.006.25-.008.247-.01.244-.012.241-.015.237-.016.233-.018.231-.02.226-.022.224-.024.22-.025.216-.027.212-.029.21-.03.205-.032.202-.033.198-.035.194-.036.191-.037.187-.039.183-.039.179-.041.175-.042.172-.043.168-.044.163-.045.16-.045.155-.047.152-.047.148-.048.143-.048.139-.05.136-.049.131-.05.126-.051.123-.051.118-.051.114-.052.11-.052.106-.052.101-.052.096-.052.092-.052.088-.052.083-.052.079-.052.074-.051.07-.052.065-.051.06-.05.056-.051.051-.049.023-.025.023-.024.021-.025.02-.024.019-.024.018-.024.017-.024.015-.023.014-.023.013-.024.012-.022.01-.023.01-.023.008-.022.006-.022.006-.022.004-.021.004-.022.001-.021.001-.021v-4.139l-.077.054-.08.054-.083.054-.085.052-.087.053-.09.051-.093.051-.095.051-.097.05-.1.049-.102.049-.105.048-.106.047-.109.047-.111.046-.114.045-.115.044-.118.044-.12.044-.122.042-.124.042-.126.041-.128.04-.13.039-.132.039-.134.038-.135.037-.138.036-.139.036-.142.035-.143.033-.144.033-.147.033-.148.031-.15.03-.151.03-.153.028-.154.028-.156.027-.158.026-.159.025-.161.024-.162.023-.163.022-.165.021-.166.02-.167.019-.169.018-.169.017-.171.016-.173.015-.173.014-.175.013-.175.012-.177.011-.178.009-.179.009-.179.007-.181.007-.182.005-.182.004-.184.003-.184.002h-.37l-.184-.002-.184-.003-.182-.004-.182-.005-.181-.007-.179-.007-.179-.009-.178-.009-.176-.011-.176-.012-.175-.013-.173-.014-.172-.015-.171-.016-.17-.017-.169-.018-.167-.019-.166-.02-.165-.021-.163-.022-.162-.023-.161-.024-.159-.025-.157-.026-.156-.027-.155-.028-.153-.028-.151-.03-.15-.03-.148-.031-.146-.033-.145-.033-.143-.033-.141-.035-.14-.036-.137-.036-.136-.037-.134-.038-.132-.039-.13-.039-.128-.04-.126-.041-.124-.042-.122-.043-.12-.043-.117-.044-.116-.044-.113-.046-.112-.046-.109-.046-.106-.047-.105-.048-.102-.049-.1-.049-.097-.05-.095-.051-.093-.051-.09-.051-.087-.053-.085-.052-.083-.054-.08-.054-.077-.054v4.139zm0-5.666v.011l.001.02.003.022.004.021.005.022.006.021.007.022.009.023.01.022.011.023.012.023.013.023.015.023.016.024.017.024.018.023.019.024.021.025.022.024.023.024.024.025.052.05.056.05.061.05.066.051.07.051.075.052.079.051.084.052.088.052.092.052.097.052.102.052.105.051.11.052.114.051.119.051.123.051.127.05.131.05.135.05.139.049.144.048.147.048.152.047.155.046.16.045.163.045.167.043.171.043.176.042.178.04.183.04.187.038.19.037.194.036.197.034.202.033.204.032.209.03.212.028.216.027.219.025.222.024.226.021.23.02.233.018.236.017.24.014.243.012.246.01.249.008.253.006.256.003.259.001.26-.001.257-.003.254-.006.25-.008.247-.01.244-.013.241-.014.237-.016.233-.018.231-.02.226-.022.224-.024.22-.025.216-.027.212-.029.21-.03.205-.032.202-.033.198-.035.194-.036.191-.037.187-.039.183-.039.179-.041.175-.042.172-.043.168-.044.163-.045.16-.045.155-.047.152-.047.148-.048.143-.049.139-.049.136-.049.131-.051.126-.05.123-.051.118-.052.114-.051.11-.052.106-.052.101-.052.096-.052.092-.052.088-.052.083-.052.079-.052.074-.052.07-.051.065-.051.06-.051.056-.05.051-.049.023-.025.023-.025.021-.024.02-.024.019-.024.018-.024.017-.024.015-.023.014-.024.013-.023.012-.023.01-.022.01-.023.008-.022.006-.022.006-.022.004-.022.004-.021.001-.021.001-.021v-4.153l-.077.054-.08.054-.083.053-.085.053-.087.053-.09.051-.093.051-.095.051-.097.05-.1.049-.102.048-.105.048-.106.048-.109.046-.111.046-.114.046-.115.044-.118.044-.12.043-.122.043-.124.042-.126.041-.128.04-.13.039-.132.039-.134.038-.135.037-.138.036-.139.036-.142.034-.143.034-.144.033-.147.032-.148.032-.15.03-.151.03-.153.028-.154.028-.156.027-.158.026-.159.024-.161.024-.162.023-.163.023-.165.021-.166.02-.167.019-.169.018-.169.017-.171.016-.173.015-.173.014-.175.013-.175.012-.177.01-.178.01-.179.009-.179.007-.181.006-.182.006-.182.004-.184.003-.184.001-.185.001-.185-.001-.184-.001-.184-.003-.182-.004-.182-.006-.181-.006-.179-.007-.179-.009-.178-.01-.176-.01-.176-.012-.175-.013-.173-.014-.172-.015-.171-.016-.17-.017-.169-.018-.167-.019-.166-.02-.165-.021-.163-.023-.162-.023-.161-.024-.159-.024-.157-.026-.156-.027-.155-.028-.153-.028-.151-.03-.15-.03-.148-.032-.146-.032-.145-.033-.143-.034-.141-.034-.14-.036-.137-.036-.136-.037-.134-.038-.132-.039-.13-.039-.128-.041-.126-.041-.124-.041-.122-.043-.12-.043-.117-.044-.116-.044-.113-.046-.112-.046-.109-.046-.106-.048-.105-.048-.102-.048-.1-.05-.097-.049-.095-.051-.093-.051-.09-.052-.087-.052-.085-.053-.083-.053-.08-.054-.077-.054v4.153zm8.74-8.179l-.257.004-.254.005-.25.008-.247.011-.244.012-.241.014-.237.016-.233.018-.231.021-.226.022-.224.023-.22.026-.216.027-.212.028-.21.031-.205.032-.202.033-.198.034-.194.036-.191.038-.187.038-.183.04-.179.041-.175.042-.172.043-.168.043-.163.045-.16.046-.155.046-.152.048-.148.048-.143.048-.139.049-.136.05-.131.05-.126.051-.123.051-.118.051-.114.052-.11.052-.106.052-.101.052-.096.052-.092.052-.088.052-.083.052-.079.052-.074.051-.07.052-.065.051-.06.05-.056.05-.051.05-.023.025-.023.024-.021.024-.02.025-.019.024-.018.024-.017.023-.015.024-.014.023-.013.023-.012.023-.01.023-.01.022-.008.022-.006.023-.006.021-.004.022-.004.021-.001.021-.001.021.001.021.001.021.004.021.004.022.006.021.006.023.008.022.01.022.01.023.012.023.013.023.014.023.015.024.017.023.018.024.019.024.02.025.021.024.023.024.023.025.051.05.056.05.06.05.065.051.07.052.074.051.079.052.083.052.088.052.092.052.096.052.101.052.106.052.11.052.114.052.118.051.123.051.126.051.131.05.136.05.139.049.143.048.148.048.152.048.155.046.16.046.163.045.168.043.172.043.175.042.179.041.183.04.187.038.191.038.194.036.198.034.202.033.205.032.21.031.212.028.216.027.22.026.224.023.226.022.231.021.233.018.237.016.241.014.244.012.247.011.25.008.254.005.257.004.26.001.26-.001.257-.004.254-.005.25-.008.247-.011.244-.012.241-.014.237-.016.233-.018.231-.021.226-.022.224-.023.22-.026.216-.027.212-.028.21-.031.205-.032.202-.033.198-.034.194-.036.191-.038.187-.038.183-.04.179-.041.175-.042.172-.043.168-.043.163-.045.16-.046.155-.046.152-.048.148-.048.143-.048.139-.049.136-.05.131-.05.126-.051.123-.051.118-.051.114-.052.11-.052.106-.052.101-.052.096-.052.092-.052.088-.052.083-.052.079-.052.074-.051.07-.052.065-.051.06-.05.056-.05.051-.05.023-.025.023-.024.021-.024.02-.025.019-.024.018-.024.017-.023.015-.024.014-.023.013-.023.012-.023.01-.023.01-.022.008-.022.006-.023.006-.021.004-.022.004-.021.001-.021.001-.021-.001-.021-.001-.021-.004-.021-.004-.022-.006-.021-.006-.023-.008-.022-.01-.022-.01-.023-.012-.023-.013-.023-.014-.023-.015-.024-.017-.023-.018-.024-.019-.024-.02-.025-.021-.024-.023-.024-.023-.025-.051-.05-.056-.05-.06-.05-.065-.051-.07-.052-.074-.051-.079-.052-.083-.052-.088-.052-.092-.052-.096-.052-.101-.052-.106-.052-.11-.052-.114-.052-.118-.051-.123-.051-.126-.051-.131-.05-.136-.05-.139-.049-.143-.048-.148-.048-.152-.048-.155-.046-.16-.046-.163-.045-.168-.043-.172-.043-.175-.042-.179-.041-.183-.04-.187-.038-.191-.038-.194-.036-.198-.034-.202-.033-.205-.032-.21-.031-.212-.028-.216-.027-.22-.026-.224-.023-.226-.022-.231-.021-.233-.018-.237-.016-.241-.014-.244-.012-.247-.011-.25-.008-.254-.005-.257-.004-.26-.001-.26.001z"></path></symbol></defs><defs><symbol id="clock" width="24" height="24"><path transform="scale(.5)" d="M12 2c5.514 0 10 4.486 10 10s-4.486 10-10 10-10-4.486-10-10 4.486-10 10-10zm0-2c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm5.848 12.459c.202.038.202.333.001.372-1.907.361-6.045 1.111-6.547 1.111-.719 0-1.301-.582-1.301-1.301 0-.512.77-5.447 1.125-7.445.034-.192.312-.181.343.014l.985 6.238 5.394 1.011z"></path></symbol></defs><defs><marker id="arrowhead" refX="7.9" refY="5" markerUnits="userSpaceOnUse" markerWidth="12" markerHeight="12" orient="auto-start-reverse"><path d="M -1 0 L 10 5 L 0 10 z"></path></marker></defs><defs><marker id="crosshead" markerWidth="15" markerHeight="8" orient="auto" refX="4" refY="4.5"><path fill="none" stroke="#000000" stroke-width="1pt" d="M 1,2 L 6,7 M 6,2 L 1,7" style="stroke-dasharray: 0, 0;"></path></marker></defs><defs><marker id="filled-head" refX="15.5" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L14,7 L9,1 Z"></path></marker></defs><defs><marker id="sequencenumber" refX="15" refY="15" markerWidth="60" markerHeight="40" orient="auto"><circle cx="15" cy="15" r="6"></circle></marker></defs><text x="287" y="80" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-size: 16px; font-weight: 400;">"What is the policy for nut allergens on bread?"</text><line x1="76" y1="113" x2="498" y2="113" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="685" y="128" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-size: 16px; font-weight: 400;">Semantic Search: 'nut allergen labeling'</text><line x1="503" y1="161" x2="867" y2="161" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="688" y="176" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-size: 16px; font-weight: 400;">Returns: Policy v2.4 (Section 3)</text><line x1="870" y1="209" x2="506" y2="209" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="785" y="224" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-size: 16px; font-weight: 400;">Context + Query: Generate clear instruction</text><line x1="503" y1="257" x2="1067" y2="257" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="788" y="272" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-size: 16px; font-weight: 400;">"Bold 'Walnuts' in ingredients list..."</text><line x1="1070" y1="305" x2="506" y2="305" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="290" y="320" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-size: 16px; font-weight: 400;">Display Result with Source Link</text><line x1="501" y1="353" x2="79" y2="353" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line></svg></div>
                <p class="text-center text-xs text-slate-400 mt-4">Figure 2: Sequence diagram of a successful information retrieval cycle.</p>
            </div>

            <h3 class="mt-8">Edge Case Handling</h3>
            <div class="bg-amber-50 border-l-4 border-amber-400 p-4 my-4">
                <p class="text-sm font-bold text-amber-800">Low Confidence Scenario:</p>
                <p class="text-sm text-amber-700">If the system finds no document with a similarity score &gt; 0.7, it triggers a fallback: "I cannot find a specific policy. Connecting you to a Compliance Officer."</p>
            </div>
        </section>

        <!-- Milestone 4 -->
        <section class="card">
            <h2><span class="milestone-badge">Milestone 4</span>Evaluation and Improvement</h2>
            <p>Following a pilot program, stakeholders provided critical feedback that informed the second iteration of the system.</p>
            
            <div class="grid md:grid-cols-2 gap-8 mt-6">
                <div class="space-y-4">
                    <h3 class="text-red-600">Stakeholder Concerns</h3>
                    <ul class="list-disc ml-5 text-sm space-y-2">
                        <li><strong>Data Quality:</strong> Older policy versions (2022) were occasionally retrieved instead of 2024 updates.</li>
                        <li><strong>Security:</strong> Recipe costs were visible to general employees.</li>
                        <li><strong>Technical Jargon:</strong> AI responses were sometimes too "legalistic" for floor staff.</li>
                    </ul>
                </div>
                <div class="space-y-4">
                    <h3 class="text-green-600">Implemented Improvements</h3>
                    <ul class="list-disc ml-5 text-sm space-y-2">
                        <li><strong>Recency Boosting:</strong> Adjusted the retriever to prioritize documents with metadata 'Date &gt; 2023'.</li>
                        <li><strong>RBAC:</strong> Role-Based Access Control filters queries before they hit the database.</li>
                        <li><strong>Persona Tuning:</strong> System prompt updated to "Explain as if to a new employee."</li>
                    </ul>
                </div>
            </div>
        </section>

        <div class="page-break"></div>

        <!-- Milestone 5 -->
        <section class="card">
            <h2><span class="milestone-badge">Milestone 5</span>Final Case Study &amp; Reflection</h2>
            
            <div class="space-y-6">
                <div>
                    <h3 class="mt-0">Executive Summary</h3>
                    <p>The implementation of the RAG system transformed the food retailer's approach to knowledge management. By shifting from static PDF manuals to an interactive AI assistant, the organization saw a 40% reduction in compliance-related errors during the first quarter of deployment.</p>
                </div>

                <div>
                    <h3>Challenges Encountered</h3>
                    <ul class="list-disc ml-6">
                        <li><strong>Legacy Integration:</strong> Connecting modern vector databases to old IT infrastructure required a custom API middleware layer.</li>
                        <li><strong>Hallucination Management:</strong> Ensuring the AI didn't "invent" food safety rules was solved by strictly limiting the LLM to only answer using provided context (Strict RAG).</li>
                    </ul>
                </div>

                <div>
                    <h3>Future Outlook</h3>
                    <p>Future iterations will include <strong>Multimodal RAG</strong>, allowing employees to take a photo of a product label to have the AI check it for compliance automatically against the policy database.</p>
                </div>

                <div class="bg-blue-900 text-white p-8 rounded-lg mt-12">
                    <h3 class="text-white mt-0">Conclusion</h3>
                    <p class="text-blue-100">Leaders in the food and beverage industry must balance innovation with safety. The RAG system provides a scalable solution to the "Information Overload" problem, ensuring that the right person has the right policy at the exact moment they need it.</p>
                </div>
            </div>
        

        <footer class="text-center text-slate-400 text-sm mt-12 mb-20">
            <p>© 2025 AI Leadership Case Study Series</p>
            <p>Submitted for: 3.3 Implementing a RAG System</p>
        </footer>
    </section></div>

    <script>
        // Initialize diagrams
        mermaid.initialize({ startOnLoad: true, theme: 'neutral' });

        function downloadFile() {
            // Remove the download button from the content to be saved
            const btn = document.getElementById('downloadBtn');
            btn.style.display = 'none';
            
            const htmlContent = document.documentElement.outerHTML;
            const blob = new Blob([htmlContent], { type: 'text/html' });
            const url = window.URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'RAG_System_Case_Study_Report.html';
            document.body.appendChild(a);
            a.click();
            window.URL.revokeObjectURL(url);
            document.body.removeChild(a);
            
            // Restore button visibility
            btn.style.display = 'flex';
        }
    </script>

<div class="mermaidTooltip" style="opacity: 0;"></div></body></html>
