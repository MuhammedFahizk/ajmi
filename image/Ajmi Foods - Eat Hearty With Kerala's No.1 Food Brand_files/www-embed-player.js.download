(function(){'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function u(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function fa(a){return a.raw=a}
function ha(a,b){a.raw=b;return a}
function v(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if("number"==typeof a.length)return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function ja(a){if(!(a instanceof Array)){a=v(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function na(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var oa="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)na(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||oa});
var pa="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},qa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=pa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),sa;
if("function"==typeof Object.setPrototypeOf)sa=Object.setPrototypeOf;else{var ta;a:{var ua={a:!0},va={};try{va.__proto__=ua;ta=va.a;break a}catch(a){}ta=!1}sa=ta?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var wa=sa;
function w(a,b){a.prototype=pa(b.prototype);a.prototype.constructor=a;if(wa)wa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function xa(){this.s=!1;this.m=null;this.i=void 0;this.h=1;this.G=this.l=0;this.D=this.j=null}
function ya(a){if(a.s)throw new TypeError("Generator is already running");a.s=!0}
xa.prototype.la=function(a){this.i=a};
function za(a,b){a.j={exception:b,pd:!0};a.h=a.l||a.G}
xa.prototype.return=function(a){this.j={return:a};this.h=this.G};
xa.prototype.yield=function(a,b){this.h=b;return{value:a}};
xa.prototype.v=function(a){this.h=a};
function Aa(a,b,c){a.l=b;void 0!=c&&(a.G=c)}
function Ba(a){a.l=0;var b=a.j.exception;a.j=null;return b}
function Ca(a){var b=a.D.splice(0)[0];(b=a.j=a.j||b)?b.pd?a.h=a.l||a.G:void 0!=b.v&&a.G<b.v?(a.h=b.v,a.j=null):a.h=a.G:a.h=0}
function Da(a){this.h=new xa;this.i=a}
function Ea(a,b){ya(a.h);var c=a.h.m;if(c)return Ga(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ha(a)}
function Ga(a,b,c,d){try{var e=b.call(a.h.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.s=!1,e;var f=e.value}catch(g){return a.h.m=null,za(a.h,g),Ha(a)}a.h.m=null;d.call(a.h,f);return Ha(a)}
function Ha(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.s=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,za(a.h,c)}a.h.s=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.pd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ia(a){this.next=function(b){ya(a.h);a.h.m?b=Ga(a,a.h.m.next,b,a.h.la):(a.h.la(b),b=Ha(a));return b};
this.throw=function(b){ya(a.h);a.h.m?b=Ga(a,a.h.m["throw"],b,a.h.la):(za(a.h,b),b=Ha(a));return b};
this.return=function(b){return Ea(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ja(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function A(a){return Ja(new Ia(new Da(a)))}
function B(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return qa});
u("Reflect.setPrototypeOf",function(a){return a?a:wa?function(b,c){try{return wa(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.s=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.W),reject:g(this.m)}};
b.prototype.W=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.da(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.S(g):this.G(g)}};
b.prototype.S=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ea(h,g):this.G(g)};
b.prototype.m=function(g){this.la(2,g)};
b.prototype.G=function(g){this.la(1,g)};
b.prototype.la=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Y();this.D()};
b.prototype.Y=function(){var g=this;e(function(){if(g.R()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.R=function(){if(this.s)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.D=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.da=function(g){var h=this.l();g.Zb(h.resolve,h.reject)};
b.prototype.ea=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(t,r){return"function"==typeof t?function(x){try{l(t(x))}catch(y){n(y)}}:r}
var l,n,p=new b(function(t,r){l=t;n=r});
this.Zb(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Zb=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.s=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=v(g),n=l.next();!n.done;n=l.next())d(n.value).Zb(h,k)})};
b.all=function(g){var h=v(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(x){return function(y){t[x]=y;r--;0==r&&l(t)}}
var t=[],r=0;do t.push(void 0),r++,d(k.value).Zb(p(t.length-1),n),k=h.next();while(!k.done)})};
return b});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=v(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!na(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!na(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&na(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&na(k,g)&&na(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&na(k,g)&&na(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ea(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h[0][l];if(n&&na(h[0],l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=v(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(v([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ka(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
u("Object.setPrototypeOf",function(a){return a||wa});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
function La(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.keys",function(a){return a?a:function(){return La(this,function(b){return b})}});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=v(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(v([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
u("Array.prototype.values",function(a){return a?a:function(){return La(this,function(b,c){return c})}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)na(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ka(this,b,"includes").indexOf(b,c||0)}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Array.prototype.entries",function(a){return a?a:function(){return La(this,function(b,c){return[b,c]})}});
u("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)na(b,d)&&c.push([d,b[d]]);return c}});
u("globalThis",function(a){return a||da});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Ma=Ma||{},C=this||self;function D(a,b,c){a=a.split(".");c=c||C;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function E(a,b){a=a.split(".");b=b||C;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Na(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Oa(a){var b=Na(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Pa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Qa(a){return Object.prototype.hasOwnProperty.call(a,Ra)&&a[Ra]||(a[Ra]=++Sa)}
var Ra="closure_uid_"+(1E9*Math.random()>>>0),Sa=0;function Ta(a,b,c){return a.call.apply(a.bind,arguments)}
function Ua(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Va(a,b,c){Va=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ta:Ua;return Va.apply(null,arguments)}
function Wa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Xa(){return Date.now()}
function Ya(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Za(a){return a}
;function $a(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,$a);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Ya($a,Error);$a.prototype.name="CustomError";function ab(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function bb(){}
function cb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var db=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},eb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},fb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},gb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},hb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
eb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function ib(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function jb(a,b){b=db(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function kb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Oa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function lb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function mb(a){var b=nb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function ob(a){for(var b in a)return!1;return!0}
function pb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function qb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function rb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function sb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function tb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=tb(a[c]);return b}
var ub="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function vb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<ub.length;f++)c=ub[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var wb;function xb(){if(void 0===wb){var a=null,b=C.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Za,createScript:Za,createScriptURL:Za})}catch(c){C.console&&C.console.error(c.message)}wb=a}else wb=a}return wb}
;function yb(){}
function zb(a){return new yb(Ab,a)}
var Ab={};zb("");var Bb={};function Cb(a){this.h=a}
Cb.prototype.toString=function(){return this.h.toString()};function Db(a){this.h=a}
Db.prototype.toString=function(){return this.h+""};
function Eb(a){if(a instanceof Db&&a.constructor===Db)return a.h;Na(a);return"type_error:TrustedResourceUrl"}
var Fb={};function Gb(a){var b=xb();a=b?b.createScriptURL(a):a;return new Db(a,Fb)}
;var Hb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};function Ib(a){this.h=a}
Ib.prototype.toString=function(){return this.h.toString()};
var Jb={},Kb=new Ib("about:invalid#zClosurez",Jb);var Lb,Mb=E("CLOSURE_FLAGS"),Nb=Mb&&Mb[610401301];Lb=null!=Nb?Nb:!1;function Ob(){var a=C.navigator;return a&&(a=a.userAgent)?a:""}
var Pb,Qb=C.navigator;Pb=Qb?Qb.userAgentData||null:null;function Rb(a){return Lb?Pb?Pb.brands.some(function(b){return(b=b.brand)&&-1!=b.indexOf(a)}):!1:!1}
function F(a){return-1!=Ob().indexOf(a)}
;function Sb(){return Lb?!!Pb&&0<Pb.brands.length:!1}
function Tb(){return Sb()?!1:F("Opera")}
function Ub(){return Sb()?!1:F("Trident")||F("MSIE")}
function Vb(){return F("Firefox")||F("FxiOS")}
function Wb(){return Sb()?Rb("Chromium"):(F("Chrome")||F("CriOS"))&&!(Sb()?0:F("Edge"))||F("Silk")}
;function Xb(a){this.h=a}
Xb.prototype.toString=function(){return this.h.toString()};function Yb(){a:{var a=C.document;if(a.querySelector&&(a=a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&Zb.test(a))break a;a=""}return a}
var Zb=/^[\w+/_-]+[=]{0,2}$/;function $b(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var ac=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function bc(a){return a?decodeURI(a):a}
function cc(a,b){return b.match(ac)[a]||null}
function dc(a){return bc(cc(3,a))}
function ec(a){var b=a.match(ac);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function fc(a){var b=a.indexOf("#");return 0>b?a:a.slice(0,b)}
function ic(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function jc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)jc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function kc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)jc(a[b],a[b+1],c);return c.join("&")}
function lc(a){var b=[],c;for(c in a)jc(c,a[c],b);return b.join("&")}
function mc(a,b){var c=2==arguments.length?kc(arguments[1],0):kc(arguments,1);return ic(a,c)}
function nc(a,b){b=lc(b);return ic(a,b)}
function oc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return ic(a,b+c)}
function pc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var qc=/#|$/,rc=/[?&]($|#)/;function sc(a,b){for(var c=a.search(qc),d=0,e,f=[];0<=(e=pc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(rc,"$1")}
;function tc(a){this.dd=a}
;function uc(a,b,c){this.i=a;this.l=b;this.h=c||[];this.pb=new Map}
m=uc.prototype;m.Pd=function(a){var b=B.apply(1,arguments),c=this.Ac(b);c?c.push(new tc(a)):this.Bd(a,b)};
m.Bd=function(a){var b=this.getKey(B.apply(1,arguments));this.pb.set(b,[new tc(a)])};
m.Ac=function(){var a=this.getKey(B.apply(0,arguments));return this.pb.has(a)?this.pb.get(a):void 0};
m.he=function(){var a=this.Ac(B.apply(0,arguments));return a&&a.length?a[0]:void 0};
m.clear=function(){this.pb.clear()};
m.getKey=function(){var a=B.apply(0,arguments);return a?a.join(","):"key"};function vc(a,b){uc.call(this,a,3,b)}
w(vc,uc);vc.prototype.j=function(a){var b=B.apply(1,arguments),c=0,d=this.he(b);d&&(c=d.dd);this.Bd(c+a,b)};function wc(a,b){uc.call(this,a,2,b)}
w(wc,uc);wc.prototype.record=function(a){this.Pd(a,B.apply(1,arguments))};function xc(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function yc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Oa(d)?yc.apply(null,d):xc(d)}}
;function G(){this.la=this.la;this.G=this.G}
G.prototype.la=!1;G.prototype.Z=function(){return this.la};
G.prototype.dispose=function(){this.la||(this.la=!0,this.M())};
function zc(a,b){Ac(a,Wa(xc,b))}
function Ac(a,b){a.la?b():(a.G||(a.G=[]),a.G.push(b))}
G.prototype.M=function(){if(this.G)for(;this.G.length;)this.G.shift()()};function Bc(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Bc.prototype.stopPropagation=function(){this.j=!0};
Bc.prototype.preventDefault=function(){this.defaultPrevented=!0};function Cc(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function Dc(a){var b=E("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||C.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Ec(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Fc[c])c=Fc[c];else{c=String(c);if(!Fc[c]){var f=/function\s+([^\(]+)/m.exec(c);Fc[c]=f?f[1]:"[Anonymous]"}c=Fc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Ec(a,b){b||(b={});b[Gc(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Gc(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Ec(a,b));return c}
function Gc(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Fc={};var Hc=function(){if(!C.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
C.addEventListener("test",c,b);C.removeEventListener("test",c,b)}catch(d){}return a}();function Ic(){return Lb?!!Pb&&!!Pb.platform:!1}
function Jc(){return F("iPhone")&&!F("iPod")&&!F("iPad")}
;function Kc(a){Kc[" "](a);return a}
Kc[" "]=function(){};var Lc=Tb(),Mc=Ub(),Nc=F("Edge"),Oc=F("Gecko")&&!(-1!=Ob().toLowerCase().indexOf("webkit")&&!F("Edge"))&&!(F("Trident")||F("MSIE"))&&!F("Edge"),Pc=-1!=Ob().toLowerCase().indexOf("webkit")&&!F("Edge");Pc&&F("Mobile");Ic()||F("Macintosh");Ic()||F("Windows");(Ic()?"Linux"===Pb.platform:F("Linux"))||Ic()||F("CrOS");var Qc=C.navigator||null;Qc&&(Qc.appVersion||"").indexOf("X11");var Rc=Ic()?"Android"===Pb.platform:F("Android");Jc();F("iPad");F("iPod");Jc()||F("iPad")||F("iPod");Ob().toLowerCase().indexOf("kaios");
function Sc(){var a=C.document;return a?a.documentMode:void 0}
var Tc;a:{var Uc="",Vc=function(){var a=Ob();if(Oc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Nc)return/Edge\/([\d\.]+)/.exec(a);if(Mc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Pc)return/WebKit\/(\S+)/.exec(a);if(Lc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Vc&&(Uc=Vc?Vc[1]:"");if(Mc){var Wc=Sc();if(null!=Wc&&Wc>parseFloat(Uc)){Tc=String(Wc);break a}}Tc=Uc}var Xc=Tc,Yc;if(C.document&&Mc){var Zc=Sc();Yc=Zc?Zc:parseInt(Xc,10)||void 0}else Yc=void 0;var $c=Yc;function ad(a,b){Bc.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Ya(ad,Bc);var bd={2:"touch",3:"pen",4:"mouse"};
ad.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Oc){a:{try{Kc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:bd[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&ad.Aa.preventDefault.call(this)};
ad.prototype.stopPropagation=function(){ad.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
ad.prototype.preventDefault=function(){ad.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var cd="closure_listenable_"+(1E6*Math.random()|0);var dd=0;function ed(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.ec=e;this.key=++dd;this.Sb=this.Yb=!1}
function fd(a){a.Sb=!0;a.listener=null;a.proxy=null;a.src=null;a.ec=null}
;function gd(a){this.src=a;this.listeners={};this.h=0}
gd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=hd(a,b,d,e);-1<g?(b=a[g],c||(b.Yb=!1)):(b=new ed(b,this.src,f,!!d,e),b.Yb=c,a.push(b));return b};
gd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=hd(e,b,c,d);return-1<b?(fd(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function id(a,b){var c=b.type;c in a.listeners&&jb(a.listeners[c],b)&&(fd(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function hd(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Sb&&f.listener==b&&f.capture==!!c&&f.ec==d)return e}return-1}
;var jd="closure_lm_"+(1E6*Math.random()|0),kd={},ld=0;function md(a,b,c,d,e){if(d&&d.once)nd(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)md(a,b[f],c,d,e);else c=od(c),a&&a[cd]?a.listen(b,c,Pa(d)?!!d.capture:!!d,e):pd(a,b,c,!1,d,e)}
function pd(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Pa(e)?!!e.capture:!!e,h=qd(a);h||(a[jd]=h=new gd(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=rd();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Hc||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(sd(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");ld++}}
function rd(){function a(c){return b.call(a.src,a.listener,c)}
var b=td;return a}
function nd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)nd(a,b[f],c,d,e);else c=od(c),a&&a[cd]?a.h.add(String(b),c,!0,Pa(d)?!!d.capture:!!d,e):pd(a,b,c,!0,d,e)}
function ud(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ud(a,b[f],c,d,e);else(d=Pa(d)?!!d.capture:!!d,c=od(c),a&&a[cd])?a.h.remove(String(b),c,d,e):a&&(a=qd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=hd(b,c,d,e)),(c=-1<a?b[a]:null)&&vd(c))}
function vd(a){if("number"!==typeof a&&a&&!a.Sb){var b=a.src;if(b&&b[cd])id(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(sd(c),d):b.addListener&&b.removeListener&&b.removeListener(d);ld--;(c=qd(b))?(id(c,a),0==c.h&&(c.src=null,b[jd]=null)):fd(a)}}}
function sd(a){return a in kd?kd[a]:kd[a]="on"+a}
function td(a,b){if(a.Sb)a=!0;else{b=new ad(b,this);var c=a.listener,d=a.ec||a.src;a.Yb&&vd(a);a=c.call(d,b)}return a}
function qd(a){a=a[jd];return a instanceof gd?a:null}
var wd="__closure_events_fn_"+(1E9*Math.random()>>>0);function od(a){if("function"===typeof a)return a;a[wd]||(a[wd]=function(b){return a.handleEvent(b)});
return a[wd]}
;function xd(){G.call(this);this.h=new gd(this);this.Ja=this;this.ea=null}
Ya(xd,G);xd.prototype[cd]=!0;m=xd.prototype;m.addEventListener=function(a,b,c,d){md(this,a,b,c,d)};
m.removeEventListener=function(a,b,c,d){ud(this,a,b,c,d)};
function yd(a,b){var c=a.ea;if(c){var d=[];for(var e=1;c;c=c.ea)d.push(c),++e}a=a.Ja;c=b.type||b;"string"===typeof b?b=new Bc(b,a):b instanceof Bc?b.target=b.target||a:(e=b,b=new Bc(c,a),vb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=zd(g,c,!0,b)&&e}b.j||(g=b.h=a,e=zd(g,c,!0,b)&&e,b.j||(e=zd(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=zd(g,c,!1,b)&&e}
m.M=function(){xd.Aa.M.call(this);this.removeAllListeners();this.ea=null};
m.listen=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
m.removeAllListeners=function(a){if(this.h){var b=this.h;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,fd(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function zd(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Sb&&g.capture==c){var h=g.listener,k=g.ec||g.src;g.Yb&&id(a.h,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Ad(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Ad.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Bd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function Cd(a,b){return a+Math.random()*(b-a)}
;function Dd(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=Dd.prototype;m.clone=function(){return new Dd(this.x,this.y)};
m.equals=function(a){return a instanceof Dd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function Ed(a,b){this.width=a;this.height=b}
m=Ed.prototype;m.clone=function(){return new Ed(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.Nb=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function Fd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Gd(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function Hd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Id;function Jd(){var a=C.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!F("Presto")&&(a=function(){var e=Gd("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Va(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Ub()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.cd;c.cd=null;e()}};
return function(e){d.next={cd:e};d=d.next;b.port2.postMessage(0)}}return function(e){C.setTimeout(e,0)}}
;function Kd(a){C.setTimeout(function(){throw a;},0)}
;function Ld(){this.i=this.h=null}
Ld.prototype.add=function(a,b){var c=Md.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Ld.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Md=new Ad(function(){return new Nd},function(a){return a.reset()});
function Nd(){this.next=this.scope=this.h=null}
Nd.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Nd.prototype.reset=function(){this.next=this.scope=this.h=null};var Od,Pd=!1,Qd=new Ld;function Rd(a,b){Od||Sd();Pd||(Od(),Pd=!0);Qd.add(a,b)}
function Sd(){if(C.Promise&&C.Promise.resolve){var a=C.Promise.resolve(void 0);Od=function(){a.then(Td)}}else Od=function(){var b=Td;
"function"!==typeof C.setImmediate||C.Window&&C.Window.prototype&&(Sb()||!F("Edge"))&&C.Window.prototype.setImmediate==C.setImmediate?(Id||(Id=Jd()),Id(b)):C.setImmediate(b)}}
function Td(){for(var a;a=Qd.remove();){try{a.h.call(a.scope)}catch(b){Kd(b)}Bd(Md,a)}Pd=!1}
;function Ud(a){this.h=0;this.s=void 0;this.l=this.i=this.j=null;this.m=this.G=!1;if(a!=bb)try{var b=this;a.call(void 0,function(c){Vd(b,2,c)},function(c){Vd(b,3,c)})}catch(c){Vd(this,3,c)}}
function Wd(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
Wd.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Xd=new Ad(function(){return new Wd},function(a){a.reset()});
function Yd(a,b,c){var d=Xd.get();d.i=a;d.h=b;d.context=c;return d}
function Zd(a){return new Ud(function(b,c){c(a)})}
Ud.prototype.then=function(a,b,c){return $d(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Ud.prototype.$goog_Thenable=!0;m=Ud.prototype;m.sc=function(a,b){return $d(this,null,a,b)};
m.catch=Ud.prototype.sc;m.cancel=function(a){if(0==this.h){var b=new ae(a);Rd(function(){be(this,b)},this)}};
function be(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?be(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):ce(c),de(c,e,3,b)))}a.j=null}else Vd(a,3,b)}
function ee(a,b){a.i||2!=a.h&&3!=a.h||fe(a);a.l?a.l.next=b:a.i=b;a.l=b}
function $d(a,b,c,d){var e=Yd(null,null,null);e.child=new Ud(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof ae?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;ee(a,e);return e.child}
m.ef=function(a){this.h=0;Vd(this,2,a)};
m.ff=function(a){this.h=0;Vd(this,3,a)};
function Vd(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.ef,f=a.ff;if(d instanceof Ud){ee(d,Yd(e||bb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Pa(d))try{var k=d.then;if("function"===typeof k){ge(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.s=c,a.h=b,a.j=null,fe(a),3!=b||c instanceof ae||he(a,c))}}
function ge(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function fe(a){a.G||(a.G=!0,Rd(a.be,a))}
function ce(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
m.be=function(){for(var a;a=ce(this);)de(this,a,this.h,this.s);this.G=!1};
function de(a,b,c,d){if(3==c&&b.h&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.child)b.child.j=null,ie(b,c,d);else try{b.j?b.i.call(b.context):ie(b,c,d)}catch(e){je.call(null,e)}Bd(Xd,b)}
function ie(a,b,c){2==b?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function he(a,b){a.m=!0;Rd(function(){a.m&&je.call(null,b)})}
var je=Kd;function ae(a){$a.call(this,a)}
Ya(ae,$a);ae.prototype.name="cancel";function ke(a,b){xd.call(this);this.j=a||1;this.i=b||C;this.l=Va(this.cf,this);this.m=Xa()}
Ya(ke,xd);m=ke.prototype;m.enabled=!1;m.Fa=null;m.setInterval=function(a){this.j=a;this.Fa&&this.enabled?(this.stop(),this.start()):this.Fa&&this.stop()};
m.cf=function(){if(this.enabled){var a=Xa()-this.m;0<a&&a<.8*this.j?this.Fa=this.i.setTimeout(this.l,this.j-a):(this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null),yd(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
m.start=function(){this.enabled=!0;this.Fa||(this.Fa=this.i.setTimeout(this.l,this.j),this.m=Xa())};
m.stop=function(){this.enabled=!1;this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null)};
m.M=function(){ke.Aa.M.call(this);this.stop();delete this.i};
function le(a,b,c){if("function"===typeof a)c&&(a=Va(a,c));else if(a&&"function"==typeof a.handleEvent)a=Va(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:C.setTimeout(a,b||0)}
;function me(a){G.call(this);this.D=a;this.i=new Map;this.s=new Set;this.j=0;this.l=100;this.flushInterval=3E4;this.h=new ke(this.flushInterval);this.h.listen("tick",this.mb,!1,this);zc(this,this.h);this.m=!1}
w(me,G);m=me.prototype;m.sendIsolatedPayload=function(a){this.m=a;this.l=1};
function ne(a){a.h.enabled||a.h.start();a.j++;a.j>=a.l&&a.mb()}
m.mb=function(){var a=this.i.values();a=[].concat(ja(a)).filter(function(b){return b.pb.size});
a.length&&this.D.flush(a,this.m);oe(a);this.j=0;this.h.enabled&&this.h.stop()};
m.Wc=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new vc(a,b))};
m.Xc=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new wc(a,b))};
function pe(a,b){return a.s.has(b)?void 0:a.i.get(b)}
m.uc=function(a){this.Nd.apply(this,[a,1].concat(ja(B.apply(1,arguments))))};
m.Nd=function(a,b){var c=B.apply(2,arguments),d=pe(this,a);d&&d instanceof vc&&(d.j(b,c),ne(this))};
m.record=function(a,b){var c=B.apply(2,arguments),d=pe(this,a);d&&d instanceof wc&&(d.record(b,c),ne(this))};
function oe(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function qe(a){this.h=a;this.h.Wc("/client_streamz/bg/fiec",{sb:3,rb:"rk"},{sb:2,rb:"ec"},{sb:3,rb:"em"})}
function re(a,b,c,d){a.h.uc("/client_streamz/bg/fiec",b,c,d)}
function se(a){this.h=a;this.h.Xc("/client_streamz/bg/fil",{sb:3,rb:"rk"})}
se.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fil",a,b)};
function te(a){this.h=a;this.h.Wc("/client_streamz/bg/fsc",{sb:3,rb:"rk"})}
function ue(a){this.h=a;this.h.Xc("/client_streamz/bg/fsl",{sb:3,rb:"rk"})}
ue.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fsl",a,b)};var ve={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function we(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=xe(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=ye(a,h),d+=ye(a,h+4),e+=ye(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return ve.toString(e)}
function xe(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function ye(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;Vb();var ze=Jc()||F("iPod"),Ae=F("iPad");!F("Android")||Wb()||Vb()||Tb()||F("Silk");Wb();var Be=F("Safari")&&!(Wb()||(Sb()?0:F("Coast"))||Tb()||(Sb()?0:F("Edge"))||(Sb()?Rb("Microsoft Edge"):F("Edg/"))||(Sb()?Rb("Opera"):F("OPR"))||Vb()||F("Silk")||F("Android"))&&!(Jc()||F("iPad")||F("iPod"));var Ce={},De=null;function Ee(a,b){Oa(a);void 0===b&&(b=0);Fe();b=Ce[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function Ge(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;He(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function He(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),n=De[l];if(null!=n)return n;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
Fe();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function Fe(){if(!De){De={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));Ce[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===De[f]&&(De[f]=e)}}}}
;var Ie="undefined"!==typeof Uint8Array,Je=!Mc&&"function"===typeof btoa;function Ke(a){if(!Je)return Ee(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var Le=/[-_.]/g,Me={"-":"+",_:"/",".":"="};function Ne(a){return Me[a]||""}
function Oe(a){return Ie&&null!=a&&a instanceof Uint8Array}
var Pe={};var Qe;function Re(a){if(a!==Pe)throw Error("illegal external caller");}
function Se(a,b){Re(b);this.value_=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
Se.prototype.Nb=function(){return null==this.value_};
Se.prototype.sizeBytes=function(){Re(Pe);var a=this.value_;if(null!=a&&!Oe(a))if("string"===typeof a)if(Je){Le.test(a)&&(a=a.replace(Le,Ne));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=Ge(a);else Na(a),a=null;return(a=null==a?a:this.value_=a)?a.length:0};function Te(a){return Array.prototype.slice.call(a)}
;var Ue="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;Math.max.apply(Math,ja(Object.values({Gf:1,Ef:2,Df:4,Jf:8,If:16,Hf:32,wf:64,Kf:128,Cf:256,Bf:512,Ff:1024})));var Ve=Ue?function(a,b){a[Ue]|=b}:function(a,b){void 0!==a.Da?a.Da|=b:Object.defineProperties(a,{Da:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function We(a){var b=Xe(a);1!==(b&1)&&(Object.isFrozen(a)&&(a=Te(a)),Ye(a,b|1))}
var Ze=Ue?function(a,b){a[Ue]&=~b}:function(a,b){void 0!==a.Da&&(a.Da&=~b)},Xe=Ue?function(a){return a[Ue]|0}:function(a){return a.Da|0},$e=Ue?function(a){return a[Ue]}:function(a){return a.Da},Ye=Ue?function(a,b){a[Ue]=b}:function(a,b){void 0!==a.Da?a.Da=b:Object.defineProperties(a,{Da:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function af(){var a=[];Ve(a,1);return a}
function bf(a,b){Ye(b,(a|0)&-255)}
function cf(a,b){Ye(b,(a|34)&-221)}
function df(a){a=a>>11&1023;return 0===a?536870912:a}
;var ef={};function ff(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var gf;function hf(a,b){if(null==a){if(!b)throw Error();}else if("string"===typeof a)a=a?new Se(a,Pe):Qe||(Qe=new Se(null,Pe));else if(a.constructor!==Se)if(Oe(a))a instanceof Uint8Array||Array.isArray(a),a=a.length?new Se(new Uint8Array(a),Pe):Qe||(Qe=new Se(null,Pe));else throw Error();return a}
var jf,kf=[];Ye(kf,55);jf=Object.freeze(kf);function lf(a){if(a&2)throw Error();}
;function mf(){var a=Error();Cc(a,"incident");Kd(a)}
function nf(){var a=Error();Cc(a,"warning");return a}
;function of(a){return a.displayName||a.name||"unknown type name"}
function pf(a){if(null!=a){if("boolean"!==typeof a)throw Error("Expected boolean but got "+Na(a)+": "+a);a=!!a}return a}
var qf=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function rf(a){return"number"===typeof a&&Number.isFinite(a)||!!a&&"string"===typeof a&&isFinite(a)}
function sf(a){if(null!=a){if("number"!==typeof a)throw nf();Number.isFinite(a)||mf()}return a}
function tf(a){if(null==a)return a;if("string"===typeof a){if(!a)return;a=+a}if("number"===typeof a)return a}
function uf(a){if(null!=a){if(!rf(a))throw nf();var b=typeof a;("number"===b?Number.isFinite(a):"string"!==b?0:qf.test(a))||mf();a="string"===typeof a?vf(a):wf(a)}return a}
function wf(a){rf(a);return a}
function vf(a){rf(a);return a}
function xf(a){if("string"!==typeof a)throw Error();return a}
function yf(a){if(null!=a&&"string"!==typeof a)throw Error();return a}
function zf(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+of(b)+" but got "+(a&&of(a.constructor)));}
function Af(a,b,c){var d=!1;if(null!=a&&"object"===typeof a&&!(d=Array.isArray(a))&&a.Kc===ef)return a;if(d){var e=d=Xe(a);0===e&&(e|=c&32);e|=c&2;e!==d&&Ye(a,e);return new b(a)}}
;var Bf;function Cf(a,b){Xe(b);Bf=b;a=new a(b);Bf=void 0;return a}
function Df(a,b,c){null==a&&(a=Bf);Bf=void 0;if(null==a){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-2095105|(b&1023)<<11)}else{if(!Array.isArray(a))throw Error();d=Xe(a);if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error();a:{c=a;var e=c.length;if(e){var f=e-1,g=c[f];if(ff(g)){d|=256;b=+!!(d&512)-1;e=f-b;1024<=e&&(Ef(c,b,g),e=1023);d=d&-2095105|(e&1023)<<11;break a}}b&&(g=+!!(d&512)-1,b=Math.max(b,e-g),1024<b&&(Ef(c,g,{}),d|=256,b=1023),d=d&-2095105|(b&1023)<<11)}}Ye(a,d);return a}
function Ef(a,b,c){for(var d=1023+b,e=a.length,f=d;f<e;f++){var g=a[f];null!=g&&g!==c&&(c[f-b]=g)}a.length=d+1;a[d]=c}
;function Ff(a,b){return Gf(b)}
function Gf(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a&&!Array.isArray(a)){if(Oe(a))return Ke(a);if(a instanceof Se){var b=a.value_;return null==b?"":"string"===typeof b?b:a.value_=Ke(b)}}}return a}
;function Hf(a,b,c){a=Te(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function If(a,b,c,d,e,f){if(null!=a){if(Array.isArray(a))a=e&&0==a.length&&Xe(a)&1?void 0:f&&Xe(a)&2?a:Jf(a,b,c,void 0!==d,e,f);else if(ff(a)){var g={},h;for(h in a)g[h]=If(a[h],b,c,d,e,f);a=g}else a=b(a,d);return a}}
function Jf(a,b,c,d,e,f){var g=d||c?Xe(a):0;d=d?!!(g&32):void 0;a=Te(a);for(var h=0;h<a.length;h++)a[h]=If(a[h],b,c,d,e,f);c&&c(g,a);return a}
function Kf(a){return a.Kc===ef?a.toJSON():Gf(a)}
;function Lf(a,b,c){c=void 0===c?cf:c;if(null!=a){if(Ie&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=Xe(a);if(d&2)return a;b&&(b=0===d||!!(d&32)&&!(d&64||!(d&16)));return b?(Ye(a,d|34),d&4&&Object.freeze(a),a):Jf(a,Lf,d&4?cf:c,!0,!1,!0)}a.Kc===ef&&(c=a.A,d=$e(c),a=d&2?a:Cf(a.constructor,Mf(c,d,!0)));return a}}
function Mf(a,b,c){var d=c||b&2?cf:bf,e=!!(b&32);a=Hf(a,b,function(f){return Lf(f,e,d)});
Ve(a,32|(c?2:0));return a}
function Nf(a){var b=a.A,c=$e(b);return c&2?Cf(a.constructor,Mf(b,c,!1)):a}
;function Of(a,b){a=a.A;return Pf(a,$e(a),b)}
function Pf(a,b,c,d){if(-1===c)return null;if(c>=df(b)){if(b&256)return a[a.length-1][c]}else{var e=a.length;if(d&&b&256&&(d=a[e-1][c],null!=d))return d;b=c+(+!!(b&512)-1);if(b<e)return a[b]}}
function K(a,b,c){var d=a.A,e=$e(d);lf(e);Qf(d,e,b,c);return a}
function Qf(a,b,c,d,e){ff(d);var f=df(b);if(c>=f||e){e=b;if(b&256)f=a[a.length-1];else{if(null==d)return;f=a[f+(+!!(b&512)-1)]={};e|=256}f[c]=d;e!==b&&Ye(a,e)}else a[c+(+!!(b&512)-1)]=d,b&256&&(a=a[a.length-1],c in a&&delete a[c])}
function Rf(a){return void 0!==Sf(a,Tf,11,!1)}
function Uf(a,b,c,d){var e=a.A,f=$e(e);lf(f);if(null==c)return Qf(e,f,b),a;if(!(Xe(c)&4)){Object.isFrozen(c)&&(c=Te(c));for(var g=0;g<c.length;g++)c[g]=d(c[g]);Ye(c,5)}Qf(e,f,b,c);return a}
function Vf(a,b,c,d){a=a.A;var e=$e(a);lf(e);for(var f=0,g=0;g<c.length;g++){var h=c[g];null!=Pf(a,e,h)&&(0!==f&&Qf(a,e,f),f=h)}(c=f)&&c!==b&&null!=d&&Qf(a,e,c);Qf(a,e,b,d)}
function Sf(a,b,c,d){a=a.A;var e=$e(a),f=Pf(a,e,c,d);b=Af(f,b,e);b!==f&&null!=b&&Qf(a,e,c,b,d);return b}
function Wf(a,b,c,d){d=void 0===d?!1:d;b=Sf(a,b,c,d);if(null==b)return b;a=a.A;var e=$e(a);if(!(e&2)){var f=Nf(b);f!==b&&(b=f,Qf(a,e,c,b,d))}return b}
function Xf(a,b,c,d){d=void 0===d?!1:d;var e=Xe(a),f=e|5;b=b?f|8:f&-9;b=c?b|16:b&-17;e!=b&&(c=b,Object.isFrozen(a)&&(a=Te(a)),Ye(a,c),!d&&b&2&&Object.freeze(a));return a}
function Yf(a,b,c,d){null!=d?zf(d,b):d=void 0;return K(a,c,d)}
function Zf(a,b,c,d){var e=a.A,f=$e(e);lf(f);if(null!=d){var g=!1,h=!0;if(!(Xe(d)&2)){g=!0;for(var k=0;k<d.length;k++){var l=d[k];zf(l,b);l=!!(Xe(l.A)&2);g=g&&!l;h=h&&l}}d=Xf(d,g,h)}null==d&&(d=void 0);Qf(e,f,c,d);return a}
function $f(a,b){a=Of(a,b);var c;null==a?c=a:rf(a)?"number"===typeof a?c=wf(a):c=vf(a):c=void 0;return c}
function ag(a){a=Of(a,1);a=null==a?a:rf(a)?"string"===typeof a?vf(a):wf(a):void 0;return a}
function bg(a){return hf(a,!1)}
function cg(a,b,c){null!=c&&(Number.isFinite(c)||mf());return K(a,b,c)}
;function dg(a,b,c){this.A=Df(a,b,c)}
m=dg.prototype;m.toJSON=function(){if(gf)var a=eg(this,this.A,!1);else a=Jf(this.A,Kf,void 0,void 0,!1,!1),a=eg(this,a,!0);return a};
m.serialize=function(){gf=!0;try{return JSON.stringify(this.toJSON(),Ff)}finally{gf=!1}};
m.clone=function(){var a=this.A,b=$e(a);return Cf(this.constructor,Mf(a,b,!1))};
m.Kc=ef;m.toString=function(){return eg(this,this.A,!1).toString()};
function eg(a,b,c){var d=a.constructor.Va,e=$e(c?a.A:b),f=df(e);e=!1;if(d){if(!c){b=Te(b);var g;if(b.length&&ff(g=b[b.length-1]))for(e=0;e<d.length;e++)if(d[e]>=f){Object.assign(b[b.length-1]={},g);break}e=!0}g=b;c=!c;f=$e(a.A);a=df(f);f=+!!(f&512)-1;for(var h,k,l=0;l<d.length;l++)if(k=d[l],k<a){k+=f;var n=g[k];null==n?g[k]=c?jf:af():c&&n!==jf&&We(n)}else h||(n=void 0,g.length&&ff(n=g[g.length-1])?h=n:g.push(h={})),n=h[k],null==h[k]?h[k]=c?jf:af():c&&n!==jf&&We(n)}d=b.length;if(!d)return b;var p;
if(ff(h=b[d-1])){a:{var t=h;g={};c=!1;for(var r in t)a=t[r],Array.isArray(a)&&a!=a&&(c=!0),null!=a?g[r]=a:c=!0;if(c){for(var x in g){t=g;break a}t=null}}t!=h&&(p=!0);d--}for(;0<d;d--){h=b[d-1];if(null!=h)break;var y=!0}if(!p&&!y)return b;var z;e?z=b:z=Array.prototype.slice.call(b,0,d);b=z;e&&(b.length=d);t&&b.push(t);return b}
;function fg(a){this.A=Df(a)}
w(fg,dg);var gg=[1,2,3];function hg(a){this.A=Df(a)}
w(hg,dg);var ig=[1,2,3];function jg(a){this.A=Df(a)}
w(jg,dg);jg.Va=[1];function kg(a){this.A=Df(a)}
w(kg,dg);kg.Va=[3,6,4];function lg(a){this.A=Df(a)}
w(lg,dg);lg.Va=[1];function mg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.startsWith("blob:")&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==
c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function ng(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var t=g,r=0;64>r;r+=4)t[r/4]=p[r]<<24|p[r+1]<<16|p[r+2]<<8|p[r+3];for(r=16;80>r;r++)p=t[r-3]^t[r-8]^t[r-14]^t[r-16],t[r]=(p<<1|p>>>31)&4294967295;p=e[0];var x=e[1],y=e[2],z=e[3],I=e[4];for(r=0;80>r;r++){if(40>r)if(20>r){var J=z^x&(y^z);var M=1518500249}else J=x^y^z,M=1859775393;else 60>r?(J=x&y|z&(x|y),M=2400959708):(J=x^y^z,M=3395469782);J=((p<<5|p>>>27)&4294967295)+J+I+M+t[r]&4294967295;I=z;z=y;y=(x<<30|x>>>2)&4294967295;x=p;p=J}e[0]=e[0]+p&4294967295;e[1]=e[1]+x&4294967295;e[2]=
e[2]+y&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+I&4294967295}
function c(p,t){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var r=[],x=0,y=p.length;x<y;++x)r.push(p.charCodeAt(x));p=r}t||(t=p.length);r=0;if(0==l)for(;r+64<t;)b(p.slice(r,r+64)),r+=64,n+=64;for(;r<t;)if(f[l++]=p[r++],n++,64==l)for(l=0,b(f);r+64<t;)b(p.slice(r,r+64)),r+=64,n+=64}
function d(){var p=[],t=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var r=63;56<=r;r--)f[r]=t&255,t>>>=8;b(f);for(r=t=0;5>r;r++)for(var x=24;0<=x;x-=8)p[t++]=e[r]>>x&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,Xd:function(){for(var p=d(),t="",r=0;r<p.length;r++)t+="0123456789ABCDEF".charAt(Math.floor(p[r]/16))+"0123456789ABCDEF".charAt(p[r]%16);return t}}}
;function og(a,b,c){var d=String(C.location.href);return d&&a&&b?[b,pg(mg(d),a,c||null)].join(" "):null}
function pg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],eb(d,function(h){e.push(h)}),qg(e.join(" "));
var f=[],g=[];eb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];eb(d,function(h){e.push(h)});
a=qg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function qg(a){var b=ng();b.update(a);return b.Xd().toLowerCase()}
;var rg={};function sg(a){this.h=a||{cookie:""}}
m=sg.prototype;m.isEnabled=function(){if(!C.navigator.cookieEnabled)return!1;if(!this.Nb())return!0;this.set("TESTCOOKIESENABLED","1",{ic:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.cg;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ic}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Hb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ic:0,path:b,domain:c});return d};
m.Dc=function(){return tg(this).keys};
m.Nb=function(){return!this.h.cookie};
m.clear=function(){for(var a=tg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function tg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Hb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var ug=new sg("undefined"==typeof document?null:document);function vg(a){return!!rg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function wg(a){a=void 0===a?!1:a;var b=C.__SAPISID||C.__APISID||C.__3PSAPISID||C.__OVERRIDE_SID;vg(a)&&(b=b||C.__1PSAPISID);if(b)return!0;if("undefined"!==typeof document){var c=new sg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID")||c.get("OSID");vg(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function xg(a,b,c,d){(a=C[a])||"undefined"===typeof document||(a=(new sg(document)).get(b));return a?og(a,c,d):null}
function yg(a,b){b=void 0===b?!1:b;var c=mg(String(C.location.href)),d=[];if(wg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?C.__SAPISID:C.__APISID;e||"undefined"===typeof document||(e=new sg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?og(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&vg(b)&&((b=xg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=xg("__3PSAPISID","__Secure-3PAPISID",
"SAPISID3PHASH",a))&&d.push(a))}return 0==d.length?null:d.join(" ")}
;function zg(a){this.A=Df(a)}
w(zg,dg);zg.Va=[2];function Ag(a){this.A=Df(a)}
w(Ag,dg);function Bg(a){this.A=Df(a)}
w(Bg,dg);function Cg(a){this.h=this.i=this.j=a}
Cg.prototype.reset=function(){this.h=this.i=this.j};
Cg.prototype.getValue=function(){return this.i};function Dg(a){this.A=Df(a)}
w(Dg,dg);function Eg(a){this.A=Df(a)}
w(Eg,dg);Eg.Va=[1];function Tf(a){this.A=Df(a)}
w(Tf,dg);var Fg=["platform","platformVersion","architecture","model","uaFullVersion"];new Eg;function Gg(a){this.A=Df(a)}
w(Gg,dg);function Hg(a){this.A=Df(a)}
w(Hg,dg);function Ig(a){this.A=Df(a,34)}
w(Ig,dg);Ig.Va=[3,20,27];function Jg(a){this.A=Df(a,19)}
w(Jg,dg);Jg.prototype.Tb=function(a){return cg(this,2,a)};
Jg.Va=[3,5];function Kg(a){this.A=Df(a,6)}
w(Kg,dg);var Lg=function(a){return function(b){if(null==b||""==b)b=new a;else{b=JSON.parse(b);if(!Array.isArray(b))throw Error(void 0);Ve(b,32);b=Cf(a,b)}return b}}(Kg);
Kg.Va=[5];function Mg(a){this.A=Df(a)}
w(Mg,dg);var Ng;Ng=new function(a,b,c){this.h=a;this.fieldName=b;this.ctor=c;this.isRepeated=0;this.i=Wf;this.defaultValue=void 0}(175237375,{Tf:0},Mg);function Og(a){G.call(this);var b=this;this.componentId="";this.i=[];this.na="";this.Ba=this.ea=-1;this.ma=!1;this.D=this.experimentIds=null;this.Y=this.da=this.s=this.l=0;this.Ja=1;this.timeoutMillis=0;this.R=!1;this.logSource=a.logSource;this.tb=a.tb||function(){};
this.j=new Pg(a.logSource,a.xb);this.network=a.network;this.Eb=a.Eb||null;this.bufferSize=1E3;this.nb=Wa(Cd,0,1);this.W=a.gf||null;this.sessionIndex=a.sessionIndex||null;this.Lb=a.Lb||!1;this.pageId=a.pageId||null;this.logger=null;this.withCredentials=!a.hd;this.xb=a.xb||!1;var c=cg(new Gg,1,1);Qg(this.j,c);this.m=new Cg(1E4);this.h=new ke(this.m.getValue());zc(this,this.h);a=Rg(this,a.Yc);md(this.h,"tick",a,!1,this);this.S=new ke(6E5);zc(this,this.S);md(this.S,"tick",a,!1,this);this.Lb||this.S.start();
this.xb||(md(document,"visibilitychange",function(){"hidden"===document.visibilityState&&b.yc()}),md(document,"pagehide",this.yc,!1,this))}
w(Og,G);function Rg(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
m=Og.prototype;m.M=function(){this.yc();G.prototype.M.call(this)};
function Sg(a){a.W||(a.W=.01>a.nb()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.W}
function Tg(a,b){a.m=new Cg(1>b?1:b);a.h.setInterval(a.m.getValue())}
m.log=function(a){a=a.clone();var b=this.Ja++;a=K(a,21,uf(b));this.componentId&&K(a,26,yf(this.componentId));ag(a)||(b=Date.now(),b=Number.isFinite(b)?b.toString():"0",K(a,1,uf(b)));null==$f(a,15)&&K(a,15,uf(60*(new Date).getTimezoneOffset()));this.experimentIds&&(b=this.experimentIds.clone(),Yf(a,zg,16,b));b=this.i.length-this.bufferSize+1;0<b&&(this.i.splice(0,b),this.l+=b);this.i.push(a);this.Lb||this.h.enabled||this.h.start()};
m.flush=function(a,b){var c=this;if(0===this.i.length)a&&a();else if(this.R)Ug(this.j,3),Vg(this);else{var d=Date.now();if(this.Ba>d&&this.ea<d)b&&b("throttled");else{Ug(this.j,1);var e=Wg(this.j,this.i,this.l,this.s,this.Eb,this.da,this.Y);d={};var f=this.tb();f&&(d.Authorization=f);var g=Sg(this);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,g=oc(g,"authuser",this.sessionIndex));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=oc(g,"pageId",this.pageId));if(f&&this.na===f)b&&b("stale-auth-token");
else{this.i=[];this.h.enabled&&this.h.stop();this.l=0;var h=e.serialize(),k;this.D&&this.D.isSupported(h.length)&&(k=this.D.compress(h));var l={url:g,body:h,Td:1,Oc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},n=function(r){c.m.reset();c.h.setInterval(c.m.getValue());if(r){var x=null;try{var y=JSON.stringify(JSON.parse(r.replace(")]}'\n","")));x=Lg(y)}catch(I){}if(x){r=Number;y="-1";y=void 0===y?"0":y;var z=ag(x);r=r(null!=z?z:y);0<r&&(c.ea=Date.now(),
c.Ba=c.ea+r);x=Ng.ctor?Ng.i(x,Ng.ctor,Ng.h,!0):Ng.i(x,Ng.h,null,!0);if(r=null===x?void 0:x)x=-1,x=void 0===x?0:x,r=tf(Of(r,1)),x=null!=r?r:x,-1!==x&&(c.ma||Tg(c,x))}}a&&a();c.s=0},p=function(r,x){var y=e.A,z=$e(y),I=!!(z&2);
var J=I?1:2,M=!!(z&2);var H=z&2;var O=Pf(y,z,3);Array.isArray(O)||(O=jf);var T=Xe(O);T&1||(T|=1,Ye(O,T));H?T&2||Ve(O,34):T&32&&!(T&2)&&Ze(O,32);H=O;if((O=H===jf)&&2!==J)y=H;else if(!O&&Xe(H)&4)3!==J&&(M?2===J&&(J=Xe(H),H=Te(H),Ye(H,J),Qf(y,z,3,H)):(M=Object.isFrozen(H),1===J?M||Object.freeze(H):(J=Xe(H),O=J&-33,M||J&2?(O&=-3,H=Te(H),Ye(H,O),Qf(y,z,3,H)):J!==O&&Ye(H,O)))),y=H;else{M=!!(z&2);T=!!(Xe(H)&2);O=H;!M&&T&&(H=Te(H));var Fa=T||void 0;T=z|(Fa?2:0);for(var ra=!1,ka=0,la=0;ka<H.length;ka++){var ma=
Af(H[ka],Ig,T);if(null!=ma){var hc=!!(Xe(ma.A)&2);Fa=Fa||hc;ra=ra||!hc;H[la++]=ma}}la<ka&&(H.length=la);H=Xf(H,!Fa,!ra,!0);O!==H&&Qf(y,z,3,H);(M&&2!==J||1===J)&&Object.freeze(H);y=H}if(!(I||Xe(y)&8)){for(I=0;I<y.length;I++)z=y[I],J=Nf(z),z!==J&&(y[I]=J);Ve(y,8)}I=$f(e,14);z=c.m;z.h=Math.min(3E5,2*z.h);z.i=Math.min(3E5,z.h+Math.round(.2*(Math.random()-.5)*z.h));c.h.setInterval(c.m.getValue());401===r&&f&&(c.na=f);I&&(c.l+=I);void 0===x&&(x=c.isRetryable(r));x&&(c.i=y.concat(c.i),c.Lb||c.h.enabled||
c.h.start());b&&b("net-send-failed",r);++c.s},t=function(){c.network&&c.network.send(l,n,p)};
k?k.then(function(r){l.Oc["Content-Encoding"]="gzip";l.Oc["Content-Type"]="application/binary";l.body=r;l.Td=2;t()},function(){t()}):t()}}}};
m.yc=function(){Xg(this.j,!0);this.flush();Xg(this.j,!1)};
function Vg(a){Yg(a,function(b,c){b=oc(b,"format","json");var d=!1;try{d=window.navigator.sendBeacon(b,c.serialize())}catch(e){}a.R&&!d&&(a.R=!1);return d})}
function Yg(a,b){if(0!==a.i.length){var c=sc(Sg(a),"format");c=mc(c,"auth",a.tb(),"authuser",a.sessionIndex||"0");for(var d=0;10>d&&a.i.length;++d){var e=a.i.slice(0,32),f=Wg(a.j,e,a.l,a.s,a.Eb,a.da,a.Y);if(!b(c,f)){++a.s;break}a.l=0;a.s=0;a.da=0;a.Y=0;a.i=a.i.slice(e.length)}a.h.enabled&&a.h.stop()}}
m.isRetryable=function(a){return 500<=a&&600>a||401===a||0===a};
function Pg(a,b){this.xb=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new Jg;Number.isInteger(a)&&this.h.Tb(a);b||(this.locale=document.documentElement.getAttribute("lang"));Qg(this,new Gg)}
Pg.prototype.Tb=function(a){this.h.Tb(a);return this};
function Qg(a,b){Yf(a.h,Gg,1,b);Of(b,1)||cg(b,1,1);if(!a.xb){b=Zg(a);var c=Of(b,5);(null==c||"string"===typeof c)&&c||K(b,5,yf(a.locale))}a.uach&&(b=Zg(a),Wf(b,Eg,9)||Yf(b,Eg,9,a.uach))}
function Ug(a,b){Rf($g(a))&&(a=ah(a),cg(a,1,b))}
function Xg(a,b){Rf($g(a))&&(a=ah(a),K(a,2,pf(b)))}
function $g(a){return Wf(a.h,Gg,1)}
function bh(a,b){var c=void 0===c?Fg:c;b(window,c).then(function(d){a.uach=d;d=Zg(a);Yf(d,Eg,9,a.uach);return!0}).catch(function(){return!1})}
function Zg(a){a=$g(a);var b=Wf(a,Tf,11);b||(b=new Tf,Yf(a,Tf,11,b));return b}
function ah(a){a=Zg(a);var b=Wf(a,Dg,10);b||(b=new Dg,K(b,2,pf(!1)),Yf(a,Dg,10,b));return b}
function Wg(a,b,c,d,e,f,g){c=void 0===c?0:c;f=void 0===f?0:f;g=void 0===g?0:g;d=void 0===d?0:d;if(Rf($g(a))){var h=ah(a);K(h,3,sf(d))}Rf($g(a))&&(d=ah(a),K(d,4,sf(f)));Rf($g(a))&&(f=ah(a),K(f,5,sf(g)));a=a.h.clone();g=Date.now().toString();a=K(a,4,uf(g));b=Zf(a,Ig,3,b);e&&(a=new Ag,e=K(a,13,sf(e)),a=new Bg,e=Yf(a,Ag,2,e),a=new Hg,e=Yf(a,Bg,1,e),e=cg(e,2,9),Yf(b,Hg,18,e));c&&K(b,14,uf(c));return b}
;function ch(){}
ch.prototype.serialize=function(a){var b=[];dh(this,a,b);return b.join("")};
function dh(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),dh(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),eh(d,c),c.push(":"),dh(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":eh(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var fh={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},gh=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function eh(a,b){b.push('"',a.replace(gh,function(c){var d=fh[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),fh[c]=d);return d}),'"')}
;function hh(){}
hh.prototype.h=null;hh.prototype.getOptions=function(){var a;(a=this.h)||(a={},ih(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var jh;function kh(){}
Ya(kh,hh);function lh(a){return(a=ih(a))?new ActiveXObject(a):new XMLHttpRequest}
function ih(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
jh=new kh;function mh(a){xd.call(this);this.headers=new Map;this.S=a||null;this.i=!1;this.R=this.I=null;this.l=this.da="";this.j=this.Y=this.s=this.W=!1;this.m=0;this.D=null;this.Ba="";this.ma=this.na=!1}
Ya(mh,xd);var nh=/^https?$/i,oh=["POST","PUT"],ph=[];function qh(a,b,c,d,e,f,g){var h=new mh;ph.push(h);b&&h.listen("complete",b);h.h.add("ready",h.Vd,!0,void 0,void 0);f&&(h.m=Math.max(0,f));g&&(h.na=g);h.send(a,c,d,e)}
m=mh.prototype;m.Vd=function(){this.dispose();jb(ph,this)};
m.send=function(a,b,c,d){if(this.I)throw Error("[goog.net.XhrIo] Object is active with another request="+this.da+"; newUri="+a);b=b?b.toUpperCase():"GET";this.da=a;this.l="";this.W=!1;this.i=!0;this.I=this.S?lh(this.S):lh(jh);this.R=this.S?this.S.getOptions():jh.getOptions();this.I.onreadystatechange=Va(this.sd,this);try{this.getStatus(),this.Y=!0,this.I.open(b,String(a),!0),this.Y=!1}catch(g){this.getStatus();rh(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=v(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=C.FormData&&a instanceof C.FormData;!(0<=db(oh,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=v(c);for(d=b.next();!d.done;d=b.next())c=v(d.value),d=c.next().value,c=c.next().value,this.I.setRequestHeader(d,c);this.Ba&&(this.I.responseType=this.Ba);"withCredentials"in this.I&&this.I.withCredentials!==this.na&&(this.I.withCredentials=this.na);try{sh(this),0<this.m&&(this.ma=th(this.I),this.getStatus(),this.ma?(this.I.timeout=this.m,this.I.ontimeout=Va(this.Gd,
this)):this.D=le(this.Gd,this.m,this)),this.getStatus(),this.s=!0,this.I.send(a),this.s=!1}catch(g){this.getStatus(),rh(this,g)}};
function th(a){return Mc&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
m.Gd=function(){"undefined"!=typeof Ma&&this.I&&(this.l="Timed out after "+this.m+"ms, aborting",this.getStatus(),yd(this,"timeout"),this.abort(8))};
function rh(a,b){a.i=!1;a.I&&(a.j=!0,a.I.abort(),a.j=!1);a.l=b;uh(a);vh(a)}
function uh(a){a.W||(a.W=!0,yd(a,"complete"),yd(a,"error"))}
m.abort=function(){this.I&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.I.abort(),this.j=!1,yd(this,"complete"),yd(this,"abort"),vh(this))};
m.M=function(){this.I&&(this.i&&(this.i=!1,this.j=!0,this.I.abort(),this.j=!1),vh(this,!0));mh.Aa.M.call(this)};
m.sd=function(){this.Z()||(this.Y||this.s||this.j?wh(this):this.Be())};
m.Be=function(){wh(this)};
function wh(a){if(a.i&&"undefined"!=typeof Ma)if(a.R[1]&&4==xh(a)&&2==a.getStatus())a.getStatus();else if(a.s&&4==xh(a))le(a.sd,0,a);else if(yd(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(yh(a))yd(a,"complete"),yd(a,"success");else{try{var b=2<xh(a)?a.I.statusText:""}catch(c){b=""}a.l=b+" ["+a.getStatus()+"]";uh(a)}}finally{vh(a)}}}
function vh(a,b){if(a.I){sh(a);var c=a.I,d=a.R[0]?function(){}:null;
a.I=null;a.R=null;b||yd(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function sh(a){a.I&&a.ma&&(a.I.ontimeout=null);a.D&&(C.clearTimeout(a.D),a.D=null)}
m.isActive=function(){return!!this.I};
m.isComplete=function(){return 4==xh(this)};
function yh(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=cc(1,String(a.da)),!a&&C.self&&C.self.location&&(a=C.self.location.protocol.slice(0,-1)),b=!nh.test(a?a.toLowerCase():"");c=b}return c}
function xh(a){return a.I?a.I.readyState:0}
m.getStatus=function(){try{return 2<xh(this)?this.I.status:-1}catch(a){return-1}};
m.getLastError=function(){return"string"===typeof this.l?this.l:String(this.l)};function zh(){}
zh.prototype.send=function(a,b,c){b=void 0===b?function(){}:b;
c=void 0===c?function(){}:c;
qh(a.url,function(d){d=d.target;if(yh(d)){try{var e=d.I?d.I.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Oc,a.timeoutMillis,a.withCredentials)};function Ah(a,b){G.call(this);this.logSource=a;this.sessionIndex=b;this.i="https://play.google.com/log?format=json&hasfast=true";this.j=!1;this.componentId="";this.network=new zh}
w(Ah,G);Ah.prototype.hd=function(){this.W=!0;return this};function Bh(a,b,c,d,e,f){a=void 0===a?-1:a;b=void 0===b?"":b;c=void 0===c?"":c;d=void 0===d?!1:d;e=void 0===e?"":e;G.call(this);f?a=f:(a=new Ah(a,"0"),a.componentId=b,zc(this,a),""!=c&&(a.i=c),d&&(a.j=!0),e&&(a.h=e),b=new Og({logSource:a.logSource,tb:a.tb?a.tb:yg,sessionIndex:a.sessionIndex,gf:a.i,xb:a.j,Lb:!1,hd:a.W,pageId:a.pageId,Yc:a.Yc,network:a.network?a.network:void 0}),zc(a,b),a.s&&Qg(b.j,a.s),a.h&&(c=a.h,d=Zg(b.j),K(d,7,yf(c))),a.m&&(b.D=a.m),a.componentId&&(b.componentId=a.componentId),
a.Eb&&(b.Eb=a.Eb),a.l&&((c=a.l)?(b.experimentIds||(b.experimentIds=new zg),c=c.serialize(),K(b.experimentIds,4,yf(c))):b.experimentIds&&K(b.experimentIds,4)),a.R&&(c=a.R,b.experimentIds||(b.experimentIds=new zg),Uf(b.experimentIds,2,c,bg)),a.D&&(c=a.D,b.ma=!0,Tg(b,c)),a.S&&bh(b.j,a.S),a.network.Tb&&a.network.Tb(a.logSource),a.network.Ve&&a.network.Ve(b),a=b);this.h=a}
w(Bh,G);
Bh.prototype.flush=function(a){var b=a||[];if(b.length){a=new lg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e;var g=new kg;g=K(g,1,yf(f.i));for(var h=f,k=[],l=0;l<h.h.length;l++)k.push(h.h[l].rb);g=Uf(g,3,k,xf);h=[];k=[];l=v(f.pb.keys());for(var n=l.next();!n.done;n=l.next())k.push(n.value.split(","));for(l=0;l<k.length;l++){n=k[l];var p=f.l;for(var t=f.Ac(n)||[],r=[],x=0;x<t.length;x++){var y=t[x],z=y&&y.dd;y=new hg;switch(p){case 3:var I=Number(z);Number.isFinite(I)&&Vf(y,1,ig,uf(I));break;case 2:I=
y;z=Number(z);if(null!=z&&"number"!==typeof z)throw Error("Value of float/double field must be a number, found "+typeof z+": "+z);Vf(I,2,ig,z)}r.push(y)}p=r;for(t=0;t<p.length;t++){r=p[t];x=new jg;r=Yf(x,hg,2,r);x=n;y=[];I=f;z=[];for(var J=0;J<I.h.length;J++)z.push(I.h[J].sb);I=z;for(z=0;z<I.length;z++){var M=I[z],H=x[z];J=new fg;switch(M){case 3:Vf(J,1,gg,yf(String(H)));break;case 2:M=Number(H);Number.isFinite(M)&&Vf(J,2,gg,sf(M));break;case 1:Vf(J,3,gg,pf("true"==H))}y.push(J)}Zf(r,fg,1,y);h.push(r)}}Zf(g,
jg,4,h);c.push(g);e.clear()}Zf(a,kg,1,c);b=this.h;a instanceof Ig?b.log(a):(c=new Ig,a=a.serialize(),a=K(c,8,yf(a)),b.log(a));this.h.flush()}};function Ch(a){this.s=Dh();this.m=new Bh(1828);this.h=new me(this.m);this.G=new se(this.h);this.j=new te(this.h);this.l=new ue(this.h);this.i=new qe(this.h);this.Qa=we(a)}
function Dh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Eh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Fh(a){function b(r,x){Promise.resolve().then(function(){var y;null!=(y=c.va)&&y.G.record(Dh()-y.s,y.Qa);g.resolve({Rd:r,Ye:x})})}
var c=this;this.h=!1;var d=a.program;var e=a.ke;if(!1!==a.He){var f;this.va=null!=(f=a.va)?f:new Ch(e)}var g=new Eh;this.i=g.promise;if(!C[e]){var h;null!=(h=this.va)&&re(h.i,h.Qa,1,"");var k;null!=(k=this.va)&&k.h.mb()}else if(!C[e].a){var l;null!=(l=this.va)&&re(l.i,l.Qa,2,"");var n;null!=(n=this.va)&&n.h.mb()}try{this.j=v((0,C[e].a)(d,b,!0,a.jg)).next().value,this.Xe=g.promise.then(function(){})}catch(r){var p;
null!=(p=this.va)&&re(p.i,p.Qa,4,r.message);var t;null!=(t=this.va)&&t.h.mb();throw r;}}
Fh.prototype.snapshot=function(a){var b=this;if(this.h)throw Error("Already disposed");var c=Dh(),d;null!=(d=this.va)&&d.j.h.uc("/client_streamz/bg/fsc",d.Qa);return this.i.then(function(e){var f=e.Rd;return new Promise(function(g){f(function(h){var k;null!=(k=b.va)&&k.l.record(Dh()-c,k.Qa);g(h)},[a.gd,
a.Ze,a.jf])})})};
Fh.prototype.Dd=function(a){if(this.h)throw Error("Already disposed");var b=Dh(),c;null!=(c=this.va)&&c.j.h.uc("/client_streamz/bg/fsc",c.Qa);a=this.j([a.gd,a.Ze,a.jf]);var d;null!=(d=this.va)&&d.l.record(Dh()-b,d.Qa);return a};
Fh.prototype.dispose=function(){var a;null!=(a=this.va)&&a.h.mb();this.h=!0;this.i.then(function(b){(b=b.Ye)&&b()})};
Fh.prototype.Z=function(){return this.h};var Gh=window;zb("csi.gstatic.com");zb("googleads.g.doubleclick.net");zb("partner.googleadservices.com");zb("pubads.g.doubleclick.net");zb("securepubads.g.doubleclick.net");zb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Hh="function"===typeof URL;function Ih(a){if(a instanceof Ib)a instanceof Ib&&a.constructor===Ib?a=a.h:(Na(a),a="type_error:SafeUrl");else{b:if(Hh){try{var b=new URL(a)}catch(c){b="https:";break b}b=b.protocol}else c:{b=document.createElement("a");try{b.href=a}catch(c){b=void 0;break c}b=b.protocol;b=":"===b||""===b?"https:":b}a="javascript:"!==b?a:void 0}return a}
;function Jh(a,b){b=Ih(b);void 0!==b&&(a.href=b)}
;var Kh={};function Lh(){}
function Mh(a){this.h=a}
w(Mh,Lh);Mh.prototype.toString=function(){return this.h};function Nh(a){var b="true".toString(),c=[new Mh(Oh[0].toLowerCase(),Kh)];if(0===c.length)throw Error("");if(c.map(function(d){if(d instanceof Mh)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Ph(){throw Error("unknown trace type");}
;var Qh="alternate author bookmark canonical cite help icon license next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Rh(a,b){if(b instanceof Db)a.href=Eb(b).toString();else{if(-1===Qh.indexOf("stylesheet"))throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=Ih(b);if(void 0===b)return;a.href=b}a.rel="stylesheet"}
;function Sh(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function Th(a,b){a.src=Eb(b);Sh(a)}
;var Uh=fa([""]),Vh=ha(["\x00"],["\\0"]),Wh=ha(["\n"],["\\n"]),Xh=ha(["\x00"],["\\u0000"]);function Yh(a){return-1===a.toString().indexOf("`")}
Yh(function(a){return a(Uh)})||Yh(function(a){return a(Vh)})||Yh(function(a){return a(Wh)})||Yh(function(a){return a(Xh)});function Zh(a){this.te=a}
function $h(a){return new Zh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var ai=[$h("data"),$h("http"),$h("https"),$h("mailto"),$h("ftp"),new Zh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function bi(a){var b=ci;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function di(){var a=[];bi(function(b){a.push(b)});
return a}
var ci={kf:"allow-forms",lf:"allow-modals",mf:"allow-orientation-lock",nf:"allow-pointer-lock",pf:"allow-popups",qf:"allow-popups-to-escape-sandbox",rf:"allow-presentation",sf:"allow-same-origin",tf:"allow-scripts",uf:"allow-top-navigation",vf:"allow-top-navigation-by-user-activation"},ei=cb(function(){return di()});
function fi(){var a=gi(),b={};eb(ei(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function gi(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function hi(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var ii=(new Date).getTime();"undefined"!==typeof TextDecoder&&new TextDecoder;var ji="undefined"!==typeof TextEncoder?new TextEncoder:null,ki=ji?function(a){return ji.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function li(a){xd.call(this);var b=this;this.s=this.j=0;this.Ea=null!=a?a:{oa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.l=function(){return A(function(e){return e.yield(mi(b),0)})};
window.addEventListener("offline",this.l);window.addEventListener("online",this.l);this.s||ni(this)}
w(li,xd);function oi(){var a=pi;li.h||(li.h=new li(a));return li.h}
li.prototype.dispose=function(){window.removeEventListener("offline",this.l);window.removeEventListener("online",this.l);this.Ea.qa(this.s);delete li.h};
li.prototype.wa=function(){return this.i};
function ni(a){a.s=a.Ea.oa(function(){var b;return A(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.v(3):c.yield(mi(a),3):c.yield(mi(a),3);ni(a);c.h=0})},3E4)}
function mi(a,b){return a.m?a.m:a.m=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,Aa(h,2,3),d&&(a.j=a.Ea.oa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.D=[h.j];h.l=0;h.G=0;a.m=void 0;a.j&&(a.Ea.qa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?yd(a,"networkstatus-online"):yd(a,"networkstatus-offline"));c(g);Ca(h);break;case 2:Ba(h),g=!1,h.v(3)}})})}
;function qi(){this.data=[];this.h=-1}
qi.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
qi.prototype.get=function(a){return!!this.data[a]};
function ri(a){-1===a.h&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function si(a,b){this.h=a[C.Symbol.iterator]();this.i=b}
si.prototype[Symbol.iterator]=function(){return this};
si.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function ti(a,b){return new si(a,b)}
;function ui(){this.blockSize=-1}
;function vi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.G=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
Ya(vi,ui);vi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function wi(a,b,c){c||(c=0);var d=a.G;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
vi.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)wi(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){wi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){wi(this,e);f=0;break}}this.i=f;this.l+=b}};
vi.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;wi(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function xi(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function yi(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function zi(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:xi(a).match(/\S+/g)||[],b=0<=db(a,b));return b}
function Ai(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):zi(a,"inverted-hdpi")&&yi(a,Array.prototype.filter.call(a.classList?a.classList:xi(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function Bi(){}
Bi.prototype.next=function(){return Ci};
var Ci={done:!0,value:void 0};function Di(a){return{value:a,done:!1}}
Bi.prototype.Ga=function(){return this};function Ei(a){if(a instanceof Fi||a instanceof Gi||a instanceof Hi)return a;if("function"==typeof a.next)return new Fi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Fi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Ga)return new Fi(function(){return a.Ga()});
throw Error("Not an iterator or iterable.");}
function Fi(a){this.i=a}
Fi.prototype.Ga=function(){return new Gi(this.i())};
Fi.prototype[Symbol.iterator]=function(){return new Hi(this.i())};
Fi.prototype.h=function(){return new Hi(this.i())};
function Gi(a){this.i=a}
w(Gi,Bi);Gi.prototype.next=function(){return this.i.next()};
Gi.prototype[Symbol.iterator]=function(){return new Hi(this.i)};
Gi.prototype.h=function(){return new Hi(this.i)};
function Hi(a){Fi.call(this,function(){return a});
this.j=a}
w(Hi,Fi);Hi.prototype.next=function(){return this.j.next()};function Ii(a,b){this.i={};this.h=[];this.Xa=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Ii)for(c=a.Dc(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
m=Ii.prototype;m.Dc=function(){Ji(this);return this.h.concat()};
m.has=function(a){return Ki(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Li;Ji(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Li(a,b){return a===b}
m.Nb=function(){return 0==this.size};
m.clear=function(){this.i={};this.Xa=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return Ki(this.i,a)?(delete this.i[a],--this.size,this.Xa++,this.h.length>2*this.size&&Ji(this),!0):!1};
function Ji(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Ki(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Ki(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return Ki(this.i,a)?this.i[a]:b};
m.set=function(a,b){Ki(this.i,a)||(this.size+=1,this.h.push(a),this.Xa++);this.i[a]=b};
m.forEach=function(a,b){for(var c=this.Dc(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new Ii(this)};
m.keys=function(){return Ei(this.Ga(!0)).h()};
m.values=function(){return Ei(this.Ga(!1)).h()};
m.entries=function(){var a=this;return ti(this.keys(),function(b){return[b,a.get(b)]})};
m.Ga=function(a){Ji(this);var b=0,c=this.Xa,d=this,e=new Bi;e.next=function(){if(c!=d.Xa)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return Ci;var f=d.h[b++];return Di(a?f:d.i[f])};
return e};
function Ki(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function L(a){G.call(this);this.m=1;this.j=[];this.l=0;this.h=[];this.i={};this.s=!!a}
Ya(L,G);m=L.prototype;m.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.m;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.m=e+3;d.push(e);return e};
m.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.Gb(a)}return!1};
m.Gb=function(a){var b=this.h[a];if(b){var c=this.i[b];0!=this.l?(this.j.push(a),this.h[a+1]=function(){}):(c&&jb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
m.Za=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.s)for(e=0;e<c.length;e++){var g=c[e];Mi(this.h[g+1],this.h[g+2],d)}else{this.l++;try{for(e=0,f=c.length;e<f&&!this.Z();e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.l--,0<this.j.length&&0==this.l)for(;c=this.j.pop();)this.Gb(c)}}return 0!=e}return!1};
function Mi(a,b,c){Rd(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.Gb,this),delete this.i[a])}else this.h.length=0,this.i={}};
m.M=function(){L.Aa.M.call(this);this.clear();this.j.length=0};function Ni(a){this.h=a}
Ni.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,(new ch).serialize(b))};
Ni.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Ni.prototype.remove=function(a){this.h.remove(a)};function Oi(a){this.h=a}
Ya(Oi,Ni);function Pi(a){this.data=a}
function Qi(a){return void 0===a||a instanceof Pi?a:new Pi(a)}
Oi.prototype.set=function(a,b){Oi.Aa.set.call(this,a,Qi(b))};
Oi.prototype.i=function(a){a=Oi.Aa.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Oi.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Ri(a){this.h=a}
Ya(Ri,Oi);Ri.prototype.set=function(a,b,c){if(b=Qi(b)){if(c){if(c<Xa()){Ri.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Xa()}Ri.Aa.set.call(this,a,b)};
Ri.prototype.i=function(a){var b=Ri.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Xa()||c&&c>Xa())Ri.prototype.remove.call(this,a);else return b}};function Si(){}
;function Ti(){}
Ya(Ti,Si);Ti.prototype[Symbol.iterator]=function(){return Ei(this.Ga(!0)).h()};
Ti.prototype.clear=function(){var a=Array.from(this);a=v(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Ui(a){this.h=a}
Ya(Ui,Ti);m=Ui.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.Ga=function(a){var b=0,c=this.h,d=new Bi;d.next=function(){if(b>=c.length)return Ci;var e=c.key(b++);if(a)return Di(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Di(e)};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function Vi(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
Ya(Vi,Ui);function Wi(a,b){this.i=a;this.h=null;var c;if(c=Mc)c=!(9<=Number($c));if(c){Xi||(Xi=new Ii);this.h=Xi.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Xi.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
Ya(Wi,Ti);var Yi={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Xi=null;function Zi(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Yi[b]})}
m=Wi.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(Zi(a),b);$i(this)};
m.get=function(a){a=this.h.getAttribute(Zi(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(Zi(a));$i(this)};
m.Ga=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new Bi;d.next=function(){if(b>=c.length)return Ci;var e=c[b++];if(a)return Di(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Di(e)};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);$i(this)};
function $i(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function aj(a,b){this.i=a;this.h=b+"::"}
Ya(aj,Ti);aj.prototype.set=function(a,b){this.i.set(this.h+a,b)};
aj.prototype.get=function(a){return this.i.get(this.h+a)};
aj.prototype.remove=function(a){this.i.remove(this.h+a)};
aj.prototype.Ga=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Bi;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return Di(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

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
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var N={},bj="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;N.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
N.Rc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var cj={ob:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
kd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},dj={ob:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
kd:function(a){return[].concat.apply([],a)}};
N.We=function(){bj?(N.lb=Uint8Array,N.Ia=Uint16Array,N.Md=Int32Array,N.assign(N,cj)):(N.lb=Array,N.Ia=Array,N.Md=Array,N.assign(N,dj))};
N.We();var ej=!0;try{new Uint8Array(1)}catch(a){ej=!1}
function fj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new N.lb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var gj={};gj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var hj={},ij,jj=[],kj=0;256>kj;kj++){ij=kj;for(var lj=0;8>lj;lj++)ij=ij&1?3988292384^ij>>>1:ij>>>1;jj[kj]=ij}hj=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^jj[(a^b[d])&255];return a^-1};var mj={};mj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function nj(a){for(var b=a.length;0<=--b;)a[b]=0}
var oj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],pj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],qj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],rj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],sj=Array(576);nj(sj);var tj=Array(60);nj(tj);var uj=Array(512);nj(uj);var vj=Array(256);nj(vj);var wj=Array(29);nj(wj);var xj=Array(30);nj(xj);function yj(a,b,c,d,e){this.Ed=a;this.de=b;this.ce=c;this.Yd=d;this.ye=e;this.nd=a&&a.length}
var zj,Aj,Bj;function Cj(a,b){this.jd=a;this.Bb=0;this.Wa=b}
function Dj(a,b){a.V[a.pending++]=b&255;a.V[a.pending++]=b>>>8&255}
function Ej(a,b,c){a.fa>16-c?(a.ka|=b<<a.fa&65535,Dj(a,a.ka),a.ka=b>>16-a.fa,a.fa+=c-16):(a.ka|=b<<a.fa&65535,a.fa+=c)}
function Fj(a,b,c){Ej(a,c[2*b],c[2*b+1])}
function Gj(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function Hj(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=Gj(d[e]++,e))}
function Ij(a){var b;for(b=0;286>b;b++)a.ra[2*b]=0;for(b=0;30>b;b++)a.bb[2*b]=0;for(b=0;19>b;b++)a.ga[2*b]=0;a.ra[512]=1;a.Pa=a.Fb=0;a.ya=a.matches=0}
function Jj(a){8<a.fa?Dj(a,a.ka):0<a.fa&&(a.V[a.pending++]=a.ka);a.ka=0;a.fa=0}
function Kj(a,b,c){Jj(a);Dj(a,c);Dj(a,~c);N.ob(a.V,a.window,b,c,a.pending);a.pending+=c}
function Lj(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Mj(a,b,c){for(var d=a.X[c],e=c<<1;e<=a.Na;){e<a.Na&&Lj(b,a.X[e+1],a.X[e],a.depth)&&e++;if(Lj(b,d,a.X[e],a.depth))break;a.X[c]=a.X[e];c=e;e<<=1}a.X[c]=d}
function Nj(a,b,c){var d=0;if(0!==a.ya){do{var e=a.V[a.Kb+2*d]<<8|a.V[a.Kb+2*d+1];var f=a.V[a.Hc+d];d++;if(0===e)Fj(a,f,b);else{var g=vj[f];Fj(a,g+256+1,b);var h=oj[g];0!==h&&(f-=wj[g],Ej(a,f,h));e--;g=256>e?uj[e]:uj[256+(e>>>7)];Fj(a,g,c);h=pj[g];0!==h&&(e-=xj[g],Ej(a,e,h))}}while(d<a.ya)}Fj(a,256,b)}
function Oj(a,b){var c=b.jd,d=b.Wa.Ed,e=b.Wa.nd,f=b.Wa.Yd,g,h=-1;a.Na=0;a.vb=573;for(g=0;g<f;g++)0!==c[2*g]?(a.X[++a.Na]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.Na;){var k=a.X[++a.Na]=2>h?++h:0;c[2*k]=1;a.depth[k]=0;a.Pa--;e&&(a.Fb-=d[2*k+1])}b.Bb=h;for(g=a.Na>>1;1<=g;g--)Mj(a,c,g);k=f;do g=a.X[1],a.X[1]=a.X[a.Na--],Mj(a,c,1),d=a.X[1],a.X[--a.vb]=g,a.X[--a.vb]=d,c[2*k]=c[2*g]+c[2*d],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=k,a.X[1]=k++,Mj(a,c,1);while(2<=a.Na);a.X[--a.vb]=
a.X[1];g=b.jd;k=b.Bb;d=b.Wa.Ed;e=b.Wa.nd;f=b.Wa.de;var l=b.Wa.ce,n=b.Wa.ye,p,t=0;for(p=0;15>=p;p++)a.Ka[p]=0;g[2*a.X[a.vb]+1]=0;for(b=a.vb+1;573>b;b++){var r=a.X[b];p=g[2*g[2*r+1]+1]+1;p>n&&(p=n,t++);g[2*r+1]=p;if(!(r>k)){a.Ka[p]++;var x=0;r>=l&&(x=f[r-l]);var y=g[2*r];a.Pa+=y*(p+x);e&&(a.Fb+=y*(d[2*r+1]+x))}}if(0!==t){do{for(p=n-1;0===a.Ka[p];)p--;a.Ka[p]--;a.Ka[p+1]+=2;a.Ka[n]--;t-=2}while(0<t);for(p=n;0!==p;p--)for(r=a.Ka[p];0!==r;)d=a.X[--b],d>k||(g[2*d+1]!==p&&(a.Pa+=(p-g[2*d+1])*g[2*d],g[2*
d+1]=p),r--)}Hj(c,h,a.Ka)}
function Pj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];++g<h&&l===f||(g<k?a.ga[2*l]+=g:0!==l?(l!==e&&a.ga[2*l]++,a.ga[32]++):10>=g?a.ga[34]++:a.ga[36]++,g=0,e=l,0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Qj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];if(!(++g<h&&l===f)){if(g<k){do Fj(a,l,a.ga);while(0!==--g)}else 0!==l?(l!==e&&(Fj(a,l,a.ga),g--),Fj(a,16,a.ga),Ej(a,g-3,2)):10>=g?(Fj(a,17,a.ga),Ej(a,g-3,3)):(Fj(a,18,a.ga),Ej(a,g-11,7));g=0;e=l;0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Rj(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.ra[2*c])return 0;if(0!==a.ra[18]||0!==a.ra[20]||0!==a.ra[26])return 1;for(c=32;256>c;c++)if(0!==a.ra[2*c])return 1;return 0}
var Sj=!1;function Tj(a,b,c){a.V[a.Kb+2*a.ya]=b>>>8&255;a.V[a.Kb+2*a.ya+1]=b&255;a.V[a.Hc+a.ya]=c&255;a.ya++;0===b?a.ra[2*c]++:(a.matches++,b--,a.ra[2*(vj[c]+256+1)]++,a.bb[2*(256>b?uj[b]:uj[256+(b>>>7)])]++);return a.ya===a.Ob-1}
;function Uj(a,b){a.msg=mj[b];return b}
function Vj(a){for(var b=a.length;0<=--b;)a[b]=0}
function Wj(a){var b=a.state,c=b.pending;c>a.K&&(c=a.K);0!==c&&(N.ob(a.output,b.V,b.Rb,c,a.Cb),a.Cb+=c,b.Rb+=c,a.Sc+=c,a.K-=c,b.pending-=c,0===b.pending&&(b.Rb=0))}
function Xj(a,b){var c=0<=a.ta?a.ta:-1,d=a.o-a.ta,e=0;if(0<a.level){2===a.H.xc&&(a.H.xc=Rj(a));Oj(a,a.hc);Oj(a,a.cc);Pj(a,a.ra,a.hc.Bb);Pj(a,a.bb,a.cc.Bb);Oj(a,a.Zc);for(e=18;3<=e&&0===a.ga[2*rj[e]+1];e--);a.Pa+=3*(e+1)+14;var f=a.Pa+3+7>>>3;var g=a.Fb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)Ej(a,b?1:0,3),Kj(a,c,d);else if(4===a.strategy||g===f)Ej(a,2+(b?1:0),3),Nj(a,sj,tj);else{Ej(a,4+(b?1:0),3);c=a.hc.Bb+1;d=a.cc.Bb+1;e+=1;Ej(a,c-257,5);Ej(a,d-1,5);Ej(a,e-4,4);for(f=0;f<e;f++)Ej(a,a.ga[2*
rj[f]+1],3);Qj(a,a.ra,c-1);Qj(a,a.bb,d-1);Nj(a,a.ra,a.bb)}Ij(a);b&&Jj(a);a.ta=a.o;Wj(a.H)}
function P(a,b){a.V[a.pending++]=b}
function Yj(a,b){a.V[a.pending++]=b>>>8&255;a.V[a.pending++]=b&255}
function Zj(a,b){var c=a.qd,d=a.o,e=a.xa,f=a.rd,g=a.o>a.ia-262?a.o-(a.ia-262):0,h=a.window,k=a.Ya,l=a.Ha,n=a.o+258,p=h[d+e-1],t=h[d+e];a.xa>=a.md&&(c>>=2);f>a.u&&(f=a.u);do{var r=b;if(h[r+e]===t&&h[r+e-1]===p&&h[r]===h[d]&&h[++r]===h[d+1]){d+=2;for(r++;h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&d<n;);r=258-(n-d);d=n-258;if(r>e){a.Ab=b;e=r;if(r>=f)break;p=h[d+e-1];t=h[d+e]}}}while((b=l[b&k])>g&&0!==--c);return e<=
a.u?e:a.u}
function ak(a){var b=a.ia,c;do{var d=a.Kd-a.u-a.o;if(a.o>=b+(b-262)){N.ob(a.window,a.window,b,b,0);a.Ab-=b;a.o-=b;a.ta-=b;var e=c=a.fc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ha[--e],a.Ha[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.H.ja)break;e=a.H;c=a.window;f=a.o+a.u;var g=e.ja;g>d&&(g=d);0===g?c=0:(e.ja-=g,N.ob(c,e.input,e.hb,g,f),1===e.state.wrap?e.F=gj(e.F,c,g,f):2===e.state.wrap&&(e.F=hj(e.F,c,g,f)),e.hb+=g,e.kb+=g,c=g);a.u+=c;if(3<=a.u+a.sa)for(d=a.o-a.sa,a.J=a.window[d],
a.J=(a.J<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.J=(a.J<<a.Ma^a.window[d+3-1])&a.La,a.Ha[d&a.Ya]=a.head[a.J],a.head[a.J]=d,d++,a.sa--,3>a.u+a.sa););}while(262>a.u&&0!==a.H.ja)}
function bk(a,b){for(var c;;){if(262>a.u){ak(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ha[a.o&a.Ya]=a.head[a.J],a.head[a.J]=a.o);0!==c&&a.o-c<=a.ia-262&&(a.P=Zj(a,c));if(3<=a.P)if(c=Tj(a,a.o-a.Ab,a.P-3),a.u-=a.P,a.P<=a.Ic&&3<=a.u){a.P--;do a.o++,a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,a.Ha[a.o&a.Ya]=a.head[a.J],a.head[a.J]=a.o;while(0!==--a.P);a.o++}else a.o+=a.P,a.P=0,a.J=a.window[a.o],a.J=(a.J<<a.Ma^a.window[a.o+1])&a.La;else c=Tj(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(Xj(a,!1),0===a.H.K))return 1}a.sa=2>a.o?a.o:2;return 4===b?(Xj(a,!0),0===a.H.K?3:4):a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function ck(a,b){for(var c,d;;){if(262>a.u){ak(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ha[a.o&a.Ya]=a.head[a.J],a.head[a.J]=a.o);a.xa=a.P;a.ud=a.Ab;a.P=2;0!==c&&a.xa<a.Ic&&a.o-c<=a.ia-262&&(a.P=Zj(a,c),5>=a.P&&(1===a.strategy||3===a.P&&4096<a.o-a.Ab)&&(a.P=2));if(3<=a.xa&&a.P<=a.xa){d=a.o+a.u-3;c=Tj(a,a.o-1-a.ud,a.xa-3);a.u-=a.xa-1;a.xa-=2;do++a.o<=d&&(a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,a.Ha[a.o&a.Ya]=a.head[a.J],a.head[a.J]=a.o);
while(0!==--a.xa);a.fb=0;a.P=2;a.o++;if(c&&(Xj(a,!1),0===a.H.K))return 1}else if(a.fb){if((c=Tj(a,0,a.window[a.o-1]))&&Xj(a,!1),a.o++,a.u--,0===a.H.K)return 1}else a.fb=1,a.o++,a.u--}a.fb&&(Tj(a,0,a.window[a.o-1]),a.fb=0);a.sa=2>a.o?a.o:2;return 4===b?(Xj(a,!0),0===a.H.K?3:4):a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function dk(a,b){for(var c,d,e,f=a.window;;){if(258>=a.u){ak(a);if(258>=a.u&&0===b)return 1;if(0===a.u)break}a.P=0;if(3<=a.u&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.P=258-(e-d);a.P>a.u&&(a.P=a.u)}3<=a.P?(c=Tj(a,1,a.P-3),a.u-=a.P,a.o+=a.P,a.P=0):(c=Tj(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(Xj(a,!1),0===a.H.K))return 1}a.sa=0;return 4===b?(Xj(a,!0),0===a.H.K?3:4):
a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function ek(a,b){for(var c;;){if(0===a.u&&(ak(a),0===a.u)){if(0===b)return 1;break}a.P=0;c=Tj(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(Xj(a,!1),0===a.H.K))return 1}a.sa=0;return 4===b?(Xj(a,!0),0===a.H.K?3:4):a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function fk(a,b,c,d,e){this.le=a;this.xe=b;this.Ae=c;this.we=d;this.ge=e}
var gk;gk=[new fk(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(1>=a.u){ak(a);if(0===a.u&&0===b)return 1;if(0===a.u)break}a.o+=a.u;a.u=0;var d=a.ta+c;if(0===a.o||a.o>=d)if(a.u=a.o-d,a.o=d,Xj(a,!1),0===a.H.K)return 1;if(a.o-a.ta>=a.ia-262&&(Xj(a,!1),0===a.H.K))return 1}a.sa=0;if(4===b)return Xj(a,!0),0===a.H.K?3:4;a.o>a.ta&&Xj(a,!1);return 1}),
new fk(4,4,8,4,bk),new fk(4,5,16,8,bk),new fk(4,6,32,32,bk),new fk(4,4,16,16,ck),new fk(8,16,32,32,ck),new fk(8,16,128,128,ck),new fk(8,32,128,256,ck),new fk(32,128,258,1024,ck),new fk(32,258,258,4096,ck)];
function hk(){this.H=null;this.status=0;this.V=null;this.wrap=this.pending=this.Rb=this.za=0;this.B=null;this.Ca=0;this.method=8;this.yb=-1;this.Ya=this.Uc=this.ia=0;this.window=null;this.Kd=0;this.head=this.Ha=null;this.rd=this.md=this.strategy=this.level=this.Ic=this.qd=this.xa=this.u=this.Ab=this.o=this.fb=this.ud=this.P=this.ta=this.Ma=this.La=this.Ec=this.fc=this.J=0;this.ra=new N.Ia(1146);this.bb=new N.Ia(122);this.ga=new N.Ia(78);Vj(this.ra);Vj(this.bb);Vj(this.ga);this.Zc=this.cc=this.hc=
null;this.Ka=new N.Ia(16);this.X=new N.Ia(573);Vj(this.X);this.vb=this.Na=0;this.depth=new N.Ia(573);Vj(this.depth);this.fa=this.ka=this.sa=this.matches=this.Fb=this.Pa=this.Kb=this.ya=this.Ob=this.Hc=0}
function ik(a,b){if(!a||!a.state||5<b||0>b)return a?Uj(a,-2):-2;var c=a.state;if(!a.output||!a.input&&0!==a.ja||666===c.status&&4!==b)return Uj(a,0===a.K?-5:-2);c.H=a;var d=c.yb;c.yb=b;if(42===c.status)if(2===c.wrap)a.F=0,P(c,31),P(c,139),P(c,8),c.B?(P(c,(c.B.text?1:0)+(c.B.Ta?2:0)+(c.B.Sa?4:0)+(c.B.name?8:0)+(c.B.comment?16:0)),P(c,c.B.time&255),P(c,c.B.time>>8&255),P(c,c.B.time>>16&255),P(c,c.B.time>>24&255),P(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),P(c,c.B.os&255),c.B.Sa&&c.B.Sa.length&&
(P(c,c.B.Sa.length&255),P(c,c.B.Sa.length>>8&255)),c.B.Ta&&(a.F=hj(a.F,c.V,c.pending,0)),c.Ca=0,c.status=69):(P(c,0),P(c,0),P(c,0),P(c,0),P(c,0),P(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),P(c,3),c.status=113);else{var e=8+(c.Uc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;Yj(c,e+(31-e%31));0!==c.o&&(Yj(c,a.F>>>16),Yj(c,a.F&65535));a.F=1}if(69===c.status)if(c.B.Sa){for(e=c.pending;c.Ca<(c.B.Sa.length&65535)&&(c.pending!==c.za||(c.B.Ta&&
c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e)),Wj(a),e=c.pending,c.pending!==c.za));)P(c,c.B.Sa[c.Ca]&255),c.Ca++;c.B.Ta&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e));c.Ca===c.B.Sa.length&&(c.Ca=0,c.status=73)}else c.status=73;if(73===c.status)if(c.B.name){e=c.pending;do{if(c.pending===c.za&&(c.B.Ta&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e)),Wj(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ca<c.B.name.length?c.B.name.charCodeAt(c.Ca++)&255:0;P(c,f)}while(0!==f);c.B.Ta&&c.pending>e&&(a.F=hj(a.F,
c.V,c.pending-e,e));0===f&&(c.Ca=0,c.status=91)}else c.status=91;if(91===c.status)if(c.B.comment){e=c.pending;do{if(c.pending===c.za&&(c.B.Ta&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e)),Wj(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ca<c.B.comment.length?c.B.comment.charCodeAt(c.Ca++)&255:0;P(c,f)}while(0!==f);c.B.Ta&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.B.Ta?(c.pending+2>c.za&&Wj(a),c.pending+2<=c.za&&(P(c,a.F&255),P(c,a.F>>
8&255),a.F=0,c.status=113)):c.status=113);if(0!==c.pending){if(Wj(a),0===a.K)return c.yb=-1,0}else if(0===a.ja&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return Uj(a,-5);if(666===c.status&&0!==a.ja)return Uj(a,-5);if(0!==a.ja||0!==c.u||0!==b&&666!==c.status){d=2===c.strategy?ek(c,b):3===c.strategy?dk(c,b):gk[c.level].ge(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.K&&(c.yb=-1),0;if(2===d&&(1===b?(Ej(c,2,3),Fj(c,256,sj),16===c.fa?(Dj(c,c.ka),c.ka=0,c.fa=0):8<=c.fa&&(c.V[c.pending++]=
c.ka&255,c.ka>>=8,c.fa-=8)):5!==b&&(Ej(c,0,3),Kj(c,0,0),3===b&&(Vj(c.head),0===c.u&&(c.o=0,c.ta=0,c.sa=0))),Wj(a),0===a.K))return c.yb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(P(c,a.F&255),P(c,a.F>>8&255),P(c,a.F>>16&255),P(c,a.F>>24&255),P(c,a.kb&255),P(c,a.kb>>8&255),P(c,a.kb>>16&255),P(c,a.kb>>24&255)):(Yj(c,a.F>>>16),Yj(c,a.F&65535));Wj(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var jk={};jk=function(){this.input=null;this.kb=this.ja=this.hb=0;this.output=null;this.Sc=this.K=this.Cb=0;this.msg="";this.state=null;this.xc=2;this.F=0};var kk=Object.prototype.toString;
function lk(a){if(!(this instanceof lk))return new lk(a);a=this.options=N.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&0<a.windowBits?a.windowBits=-a.windowBits:a.gzip&&0<a.windowBits&&16>a.windowBits&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.H=new jk;this.H.K=0;var b=this.H;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<
f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=Uj(b,-2);else{8===e&&(e=9);var k=new hk;b.state=k;k.H=b;k.wrap=h;k.B=null;k.Uc=e;k.ia=1<<k.Uc;k.Ya=k.ia-1;k.Ec=f+7;k.fc=1<<k.Ec;k.La=k.fc-1;k.Ma=~~((k.Ec+3-1)/3);k.window=new N.lb(2*k.ia);k.head=new N.Ia(k.fc);k.Ha=new N.Ia(k.ia);k.Ob=1<<f+6;k.za=4*k.Ob;k.V=new N.lb(k.za);k.Kb=1*k.Ob;k.Hc=3*k.Ob;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.kb=b.Sc=0;b.xc=2;c=b.state;c.pending=0;c.Rb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.F=2===c.wrap?
0:1;c.yb=0;if(!Sj){d=Array(16);for(f=g=0;28>f;f++)for(wj[f]=g,e=0;e<1<<oj[f];e++)vj[g++]=f;vj[g-1]=f;for(f=g=0;16>f;f++)for(xj[f]=g,e=0;e<1<<pj[f];e++)uj[g++]=f;for(g>>=7;30>f;f++)for(xj[f]=g<<7,e=0;e<1<<pj[f]-7;e++)uj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)sj[2*e+1]=8,e++,d[8]++;for(;255>=e;)sj[2*e+1]=9,e++,d[9]++;for(;279>=e;)sj[2*e+1]=7,e++,d[7]++;for(;287>=e;)sj[2*e+1]=8,e++,d[8]++;Hj(sj,287,d);for(e=0;30>e;e++)tj[2*e+1]=5,tj[2*e]=Gj(e,5);zj=new yj(sj,oj,257,286,15);Aj=new yj(tj,
pj,0,30,15);Bj=new yj([],qj,0,19,7);Sj=!0}c.hc=new Cj(c.ra,zj);c.cc=new Cj(c.bb,Aj);c.Zc=new Cj(c.ga,Bj);c.ka=0;c.fa=0;Ij(c);c=0}else c=Uj(b,-2);0===c&&(b=b.state,b.Kd=2*b.ia,Vj(b.head),b.Ic=gk[b.level].xe,b.md=gk[b.level].le,b.rd=gk[b.level].Ae,b.qd=gk[b.level].we,b.o=0,b.ta=0,b.u=0,b.sa=0,b.P=b.xa=2,b.fb=0,b.J=0);b=c}}else b=-2;if(0!==b)throw Error(mj[b]);a.header&&(b=this.H)&&b.state&&2===b.state.wrap&&(b.state.B=a.header);if(a.dictionary){var l;"string"===typeof a.dictionary?l=fj(a.dictionary):
"[object ArrayBuffer]"===kk.call(a.dictionary)?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.H;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,2===b||1===b&&42!==l.status||l.u)b=-2;else{1===b&&(a.F=gj(a.F,f,g,0));l.wrap=0;g>=l.ia&&(0===b&&(Vj(l.head),l.o=0,l.ta=0,l.sa=0),c=new N.lb(l.ia),N.ob(c,f,g-l.ia,l.ia,0),f=c,g=l.ia);c=a.ja;d=a.hb;e=a.input;a.ja=g;a.hb=0;a.input=f;for(ak(l);3<=l.u;){f=l.o;g=l.u-2;do l.J=(l.J<<l.Ma^l.window[f+3-1])&l.La,l.Ha[f&l.Ya]=l.head[l.J],l.head[l.J]=f,f++;while(--g);
l.o=f;l.u=2;ak(l)}l.o+=l.u;l.ta=l.o;l.sa=l.u;l.u=0;l.P=l.xa=2;l.fb=0;a.hb=d;a.input=e;a.ja=c;l.wrap=b;b=0}else b=-2;if(0!==b)throw Error(mj[b]);this.Lf=!0}}
lk.prototype.push=function(a,b){var c=this.H,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=fj(a):"[object ArrayBuffer]"===kk.call(a)?c.input=new Uint8Array(a):c.input=a;c.hb=0;c.ja=c.input.length;do{0===c.K&&(c.output=new N.lb(d),c.Cb=0,c.K=d);a=ik(c,e);if(1!==a&&0!==a)return mk(this,a),this.ended=!0,!1;if(0===c.K||0===c.ja&&(4===e||2===e))if("string"===this.options.to){var f=N.Rc(c.output,c.Cb);b=f;f=f.length;if(65537>f&&(b.subarray&&ej||!b.subarray))b=
String.fromCharCode.apply(null,N.Rc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=N.Rc(c.output,c.Cb),this.chunks.push(b)}while((0<c.ja||0===c.K)&&1!==a);if(4===e)return(c=this.H)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=Uj(c,-2):(c.state=null,a=113===d?Uj(c,-3):0)):a=-2,mk(this,a),this.ended=!0,0===a;2===e&&(mk(this,0),c.K=0);return!0};
function mk(a,b){0===b&&(a.result="string"===a.options.to?a.chunks.join(""):N.kd(a.chunks));a.chunks=[];a.err=b;a.msg=a.H.msg}
function nk(a,b){b=b||{};b.gzip=!0;b=new lk(b);b.push(a,!0);if(b.err)throw b.msg||mj[b.err];return b.result}
;function ok(a){return Gb(null===a?"null":void 0===a?"undefined":a)}
;function pk(a){this.name=a}
;var qk=new pk("rawColdConfigGroup");var rk=new pk("rawHotConfigGroup");function sk(a){this.A=Df(a)}
w(sk,dg);var tk=new pk("continuationCommand");var uk=new pk("webCommandMetadata");var vk=new pk("signalServiceEndpoint");var wk={Af:"EMBEDDED_PLAYER_MODE_UNKNOWN",xf:"EMBEDDED_PLAYER_MODE_DEFAULT",zf:"EMBEDDED_PLAYER_MODE_PFP",yf:"EMBEDDED_PLAYER_MODE_PFL"};var xk=new pk("feedbackEndpoint");function yk(a){this.A=Df(a)}
w(yk,dg);var zk=new pk("webPlayerShareEntityServiceEndpoint");var Ak=new pk("playlistEditEndpoint");var Bk=new pk("modifyChannelNotificationPreferenceEndpoint");var Ck=new pk("unsubscribeEndpoint");var Dk=new pk("subscribeEndpoint");function Ek(){var a=Fk;E("yt.ads.biscotti.getId_")||D("yt.ads.biscotti.getId_",a)}
function Gk(a){D("yt.ads.biscotti.lastId_",a)}
;function Hk(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Ik=C.window,Jk,Kk,Lk=(null==Ik?void 0:null==(Jk=Ik.yt)?void 0:Jk.config_)||(null==Ik?void 0:null==(Kk=Ik.ytcfg)?void 0:Kk.data_)||{};D("yt.config_",Lk);function Mk(){Hk(Lk,arguments)}
function R(a,b){return a in Lk?Lk[a]:b}
function Nk(a){var b=Lk.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var Ok=[];function Pk(a){Ok.forEach(function(b){return b(a)})}
function Qk(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Rk(b)}}:a}
function Rk(a){var b=E("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Mk("ERRORS",b));Pk(a)}
function Sk(a,b,c,d,e){var f=E("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=R("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Mk("ERRORS",f))}
;var Tk=/^[\w.]*$/,Uk={q:!0,search_query:!0};function Vk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Wk(f[0]||""),h=Wk(f[1]||"");g in c?Array.isArray(c[g])?kb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(Vk);k.args=[{key:l,value:f[1],query:a,method:Xk==n?"unchanged":n}];Uk.hasOwnProperty(l)||Sk(k)}}return c}
var Xk=String(Vk);function Yk(a){var b=[];lb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];eb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Zk(a){"?"==a.charAt(0)&&(a=a.substr(1));return Vk(a,"&")}
function $k(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Zk(1<a.length?a[1]:a[0])):{}}
function al(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Zk(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return nc(a,e)+d}
function bl(a){if(!b)var b=window.location.href;var c=cc(1,a),d=dc(a);c&&d?(a=a.match(ac),b=b.match(ac),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?dc(b)==d&&(Number(cc(4,b))||null)==(Number(cc(4,a))||null):!0;return a}
function Wk(a){return a&&a.match(Tk)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function cl(a){var b=dl;a=void 0===a?E("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=ii;e.flash="0";a:{try{var f=b.h.top.location.href}catch(ma){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Gh:g;try{var h=g.history.length}catch(ma){h=0}e.u_his=h;var k;e.u_h=null==(k=Gh.screen)?void 0:k.height;var l;e.u_w=null==(l=Gh.screen)?void 0:l.width;var n;e.u_ah=null==(n=Gh.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=Gh.screen)?void 0:p.availWidth;var t;e.u_cd=null==(t=Gh.screen)?void 0:t.colorDepth}catch(ma){}h=b.h;try{var r=h.screenX;var x=h.screenY}catch(ma){}try{var y=h.outerWidth;var z=h.outerHeight}catch(ma){}try{var I=h.innerWidth;var J=h.innerHeight}catch(ma){}try{var M=h.screenLeft;var H=h.screenTop}catch(ma){}try{I=h.innerWidth,J=h.innerHeight}catch(ma){}try{var O=h.screen.availWidth;var T=h.screen.availTop}catch(ma){}r=[M,H,r,x,O,T,y,z,I,J];try{var Fa=(b.h.top||window).document,ra="CSS1Compat"==
Fa.compatMode?Fa.documentElement:Fa.body;var ka=(new Ed(ra.clientWidth,ra.clientHeight)).round()}catch(ma){ka=new Ed(-12245933,-12245933)}Fa=ka;ka={};var la=void 0===la?C:la;ra=new qi;"SVGElement"in la&&"createElementNS"in la.document&&ra.set(0);x=fi();x["allow-top-navigation-by-user-activation"]&&ra.set(1);x["allow-popups-to-escape-sandbox"]&&ra.set(2);la.crypto&&la.crypto.subtle&&ra.set(3);"TextDecoder"in la&&"TextEncoder"in la&&ra.set(4);la=ri(ra);ka.bc=la;ka.bih=Fa.height;ka.biw=Fa.width;ka.brdim=
r.join();b=b.i;b=(ka.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,ka.wgl=!!Gh.WebGLRenderingContext,ka);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var dl=new function(){var a=window.document;this.h=window;this.i=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return Yk(cl(a))});Xa();navigator.userAgent.indexOf(" (CrKey ");function S(a){a=R("EXPERIMENT_FLAGS",{})[a];return"string"===typeof a&&"false"===a?!1:!!a}
function U(a,b){a=R("EXPERIMENT_FLAGS",{})[a];return void 0===a&&void 0!==b?b:Number(a||0)}
function el(){for(var a=[],b=R("EXPERIMENTS_FORCED_FLAGS",{}),c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=R("EXPERIMENT_FLAGS",{});var e=v(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var fl="XMLHttpRequest"in C?function(){return new XMLHttpRequest}:null;
function gl(){if(!fl)return null;var a=fl();return"open"in a?a:null}
function hl(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function il(a,b){"function"===typeof a&&(a=Qk(a));return window.setTimeout(a,b)}
;var jl="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(ja(jl),["client_dev_set_cookie"]);var kl={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},ll="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ja(jl)),ml=!1;
function nl(a,b){b=void 0===b?{}:b;var c=bl(a),d=S("web_ajax_ignore_global_headers_if_set"),e;for(e in kl){var f=R(kl[e]),g="X-Goog-AuthUser"===e||"X-Goog-PageId"===e;"X-Goog-Visitor-Id"!==e||f||(f=R("VISITOR_DATA"));!f||!c&&dc(a)||d&&void 0!==b[e]||"TVHTML5_UNPLUGGED"===R("INNERTUBE_CLIENT_NAME")&&g||(b[e]=f)}c&&R("SESSION_INDEX")&&"TVHTML5_UNPLUGGED"!==R("INNERTUBE_CLIENT_NAME")&&(b["X-Yt-Auth-Test"]="test");c&&R("WEBVIEW_EOM",!1)&&(b["X-Yt-Webview-Eom"]="1");"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in
b&&delete b["X-Goog-Visitor-Id"];if(c||!dc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!dc(a)){try{var h=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(k){}h&&(b["X-YouTube-Time-Zone"]=h)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&dc(a)||(b["X-YouTube-Ad-Signals"]=Yk(cl()));return b}
function ol(a){var b=window.location.search,c=dc(a);S("debug_handle_relative_url_for_query_forward_killswitch")||!c&&bl(a)&&(c=document.location.hostname);var d=bc(cc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Zk(b),f={};eb(ll,function(g){e[g]&&(f[g]=e[g])});
return al(a,f||{},!1)}
function pl(a,b){var c=b.format||"JSON";a=ql(a,b);var d=rl(a,b),e=!1,f=sl(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=hl(k),n=null,p=400<=k.status&&500>k.status,t=500<=k.status&&600>k.status;if(l||p||t)n=tl(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||C;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,
k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=il(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||C,f))},d)}return f}
function ql(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=al(a,b||{},!0);return a}
function rl(a,b){var c=R("XSRF_FIELD_NAME"),d=R("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||dc(a)&&!b.withCredentials&&dc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(S("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=Zk(e),vb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):lc(e));f=e||f&&!ob(f);!ml&&f&&"POST"!=b.method&&(ml=!0,Rk(Error("AJAX request with postData should use POST")));return e}
function tl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Sk(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?ul(a):null)e={},eb(a.getElementsByTagName("*"),function(g){e[g.tagName]=vl(g)})}d&&wl(e);
return e}
function wl(a){if(Pa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=xb();d=e?e.createHTML(d):d;a[c]=new Xb(d)}else wl(a[b])}}
function ul(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function vl(a){var b="";eb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function xl(a,b){b.method="POST";b.postParams||(b.postParams={});return pl(a,b)}
function sl(a,b,c,d,e,f,g,h){function k(){4==(l&&"readyState"in l?l.readyState:0)&&b&&Qk(b)(l)}
c=void 0===c?"GET":c;d=void 0===d?"":d;h=void 0===h?!1:h;var l=gl();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;S("debug_forward_web_query_parameters")&&(a=ol(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=nl(a,e))for(var n in e)l.setRequestHeader(n,e[n]),"content-type"==n.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
h&&"setAttributionReporting"in XMLHttpRequest.prototype&&l.setAttributionReporting({eventSourceEligible:!0,triggerEligible:!1});l.send(d);return l}
;var yl=[{Jc:function(a){return"Cannot read property '"+a.key+"'"},
mc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Jc:function(a){return"Cannot call '"+a.key+"'"},
mc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Jc:function(a){return a.key+" is not defined"},
mc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Al={Ua:[],Ra:[{callback:zl,weight:500}]};function zl(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Bl(){this.Ra=[];this.Ua=[]}
var Cl;function Dl(){if(!Cl){var a=Cl=new Bl;a.Ua.length=0;a.Ra.length=0;Al.Ua&&a.Ua.push.apply(a.Ua,Al.Ua);Al.Ra&&a.Ra.push.apply(a.Ra,Al.Ra)}return Cl}
;var El=new L;function Fl(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Gl(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Gl(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Gl(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Gl(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Hl(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Il(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f="string"!==typeof g||"clickTrackingParams"!==f&&"trackingParams"!==f?0:(g=Fl(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?Il(f+".ve",g,h,k):0;d+=f;d+=Il(e,a[e],b,c);if(500<d)break}}else c[b]=Jl(a),d+=c[b].length;else c[b]=Jl(a),d+=c[b].length;return d}
function Il(a,b,c,d){c+="."+a;a=Jl(b);d[c]=a;return c.length+a.length}
function Jl(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function Kl(){this.af=!0}
function Ll(){Kl.h||(Kl.h=new Kl);return Kl.h}
function Ml(a,b){a={};var c=yg([]);c&&(a.Authorization=c,c=b=null==b?void 0:b.sessionIndex,void 0===c&&(c=Number(R("SESSION_INDEX",0)),c=isNaN(c)?0:c),S("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Lk||(a["X-Origin"]=window.location.origin),void 0===b&&"DELEGATED_SESSION_ID"in Lk&&(a["X-Goog-PageId"]=R("DELEGATED_SESSION_ID")));return a}
;var Nl={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function Ol(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function Pl(){if(!C.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return C.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":C.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":C.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":C.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function Ql(a,b,c,d,e){ug.set(""+a,b,{ic:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function Rl(a){return ug.get(""+a,void 0)}
function Sl(a,b,c){ug.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function Tl(){if(!ug.isEnabled())return!1;if(!ug.Nb())return!0;ug.set("TESTCOOKIESENABLED","1",{ic:60});if("1"!==ug.get("TESTCOOKIESENABLED"))return!1;ug.remove("TESTCOOKIESENABLED");return!0}
;var Ul=E("ytglobal.prefsUserPrefsPrefs_")||{};D("ytglobal.prefsUserPrefsPrefs_",Ul);function Vl(){this.h=R("ALT_PREF_COOKIE_NAME","PREF");this.i=R("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Rl(this.h);a&&this.parse(a)}
var Wl;function Xl(){Wl||(Wl=new Vl);return Wl}
m=Vl.prototype;m.get=function(a,b){Yl(a);Zl(a);a=void 0!==Ul[a]?Ul[a].toString():null;return null!=a?a:b?b:""};
m.set=function(a,b){Yl(a);Zl(a);if(null==b)throw Error("ExpectedNotNull");Ul[a]=b.toString()};
function $l(a){return!!((am("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
m.remove=function(a){Yl(a);Zl(a);delete Ul[a]};
m.clear=function(){for(var a in Ul)delete Ul[a]};
function Zl(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Yl(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function am(a){a=void 0!==Ul[a]?Ul[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
m.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Ul[d]=c.toString())}};var bm={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},cm={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function dm(){var a=C.navigator;return a?a.connection:void 0}
function em(){var a=dm();if(a){var b=bm[a.type||"unknown"]||"CONN_UNKNOWN";a=bm[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function fm(){var a=dm();if(null!=a&&a.effectiveType)return cm.hasOwnProperty(a.effectiveType)?cm[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function V(a){var b=B.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ja(b))}
w(V,Error);function gm(){try{return hm(),!0}catch(a){return!1}}
function hm(a){if(void 0!==R("DATASYNC_ID"))return R("DATASYNC_ID");throw new V("Datasync ID not set",void 0===a?"unknown":a);}
;function im(){}
function jm(a,b){return pi.ab(a,0,b)}
im.prototype.oa=function(a,b){return this.ab(a,1,b)};
im.prototype.Hb=function(a){var b=E("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var km=U("web_emulated_idle_callback_delay",300),lm=1E3/60-3,mm=[8,5,4,3,2,1,0];
function nm(a){a=void 0===a?{}:a;G.call(this);this.i=[];this.j={};this.Y=this.h=0;this.W=this.m=!1;this.R=[];this.S=this.da=!1;for(var b=v(mm),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.l=0;this.wc=a.timeout||1;this.D=lm;this.s=0;this.ma=this.Ce.bind(this);this.vc=this.df.bind(this);this.Ba=this.Qd.bind(this);this.Ja=this.me.bind(this);this.nb=this.Fe.bind(this);this.na=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!S("disable_scheduler_requestIdleCallback");(this.ea=!1!==
a.useRaf&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.ma)}
w(nm,G);m=nm.prototype;m.Hb=function(a){var b=Xa();om(this,a);a=Xa()-b;this.m||(this.D-=a)};
m.ab=function(a,b,c){++this.Y;if(10===b)return this.Hb(a),this.Y;var d=this.Y;this.j[d]=a;this.m&&!c?this.R.push({id:d,priority:b}):(this.i[b].push(d),this.W||this.m||(0!==this.h&&pm(this)!==this.s&&this.stop(),this.start()));return d};
m.qa=function(a){delete this.j[a]};
function qm(a){a.R.length=0;for(var b=5;0<=b;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
m.isHidden=function(){return!!document.hidden||!1};
function rm(a){return!a.isHidden()&&a.ea}
function pm(a){if(a.i[8].length){if(a.S)return 4;if(rm(a))return 3}for(var b=5;b>=a.l;b--)if(0<a.i[b].length)return 0<b?rm(a)?3:2:1;return 0}
m.Pb=function(a){var b=E("yt.logging.errors.log");b&&b(a)};
function om(a,b){try{b()}catch(c){a.Pb(c)}}
function sm(a){for(var b=v(mm),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
m.me=function(a){var b=void 0;a&&(b=a.timeRemaining());this.da=!0;tm(this,b);this.da=!1};
m.df=function(){tm(this)};
m.Qd=function(){um(this)};
m.Fe=function(a){this.S=!0;var b=pm(this);4===b&&b!==this.s&&(this.stop(),this.start());tm(this,void 0,a);this.S=!1};
m.Ce=function(){this.isHidden()||um(this);this.h&&(this.stop(),this.start())};
function um(a){a.stop();a.m=!0;for(var b=Xa(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&om(a,e)}wm(a);a.m=!1;sm(a)&&a.start();b=Xa()-b;a.D-=b}
function wm(a){for(var b=0,c=a.R.length;b<c;b++){var d=a.R[b];a.i[d.priority].push(d.id)}a.R.length=0}
function tm(a,b,c){a.S&&4===a.s&&a.h||a.stop();a.m=!0;b=Xa()+(b||a.D);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Pb(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&om(a,f);d=a.da?0:1;d=a.l>d?a.l:d;if(!(Xa()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&om(a,c)}while(c&&Xa()<b)}a.m=!1;wm(a);a.D=lm;sm(a)&&a.start()}
m.start=function(){this.W=!1;if(0===this.h)switch(this.s=pm(this),this.s){case 1:var a=this.Ja;this.h=this.na?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,km);break;case 2:this.h=window.setTimeout(this.vc,this.wc);break;case 3:this.h=window.requestAnimationFrame(this.nb);break;case 4:this.h=window.setTimeout(this.Ba,0)}};
m.pause=function(){this.stop();this.W=!0};
m.stop=function(){if(this.h){switch(this.s){case 1:var a=this.h;this.na?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
m.M=function(){qm(this);this.stop();this.ea&&document.removeEventListener("visibilitychange",this.ma);G.prototype.M.call(this)};var xm=E("yt.scheduler.instance.timerIdMap_")||{},ym=U("kevlar_tuner_scheduler_soft_state_timer_ms",800),zm=0,Am=0;function Bm(){var a=E("ytglobal.schedulerInstanceInstance_");if(!a||a.Z())a=new nm(R("scheduler")||{}),D("ytglobal.schedulerInstanceInstance_",a);return a}
function Cm(){Dm();var a=E("ytglobal.schedulerInstanceInstance_");a&&(xc(a),D("ytglobal.schedulerInstanceInstance_",null))}
function Dm(){qm(Bm());for(var a in xm)xm.hasOwnProperty(a)&&delete xm[Number(a)]}
function Em(a,b,c){if(!c)return c=void 0===c,-Bm().ab(a,b,c);var d=window.setTimeout(function(){var e=Bm().ab(a,b);xm[d]=e},c);
return d}
function Fm(a){Bm().Hb(a)}
function Gm(a){var b=Bm();if(0>a)b.qa(-a);else{var c=xm[a];c?(b.qa(c),delete xm[a]):window.clearTimeout(a)}}
function Hm(){Im()}
function Im(){window.clearTimeout(zm);Bm().start()}
function Jm(){Bm().pause();window.clearTimeout(zm);zm=window.setTimeout(Hm,ym)}
function Km(){window.clearTimeout(Am);Am=window.setTimeout(function(){Lm(0)},ym)}
function Lm(a){Km();var b=Bm();b.l=a;b.start()}
function Mm(a){Km();var b=Bm();b.l>a&&(b.l=a,b.start())}
function Nm(){window.clearTimeout(Am);var a=Bm();a.l=0;a.start()}
function Om(){E("yt.scheduler.initialized")||(D("yt.scheduler.instance.dispose",Cm),D("yt.scheduler.instance.addJob",Em),D("yt.scheduler.instance.addImmediateJob",Fm),D("yt.scheduler.instance.cancelJob",Gm),D("yt.scheduler.instance.cancelAllJobs",Dm),D("yt.scheduler.instance.start",Im),D("yt.scheduler.instance.pause",Jm),D("yt.scheduler.instance.setPriorityThreshold",Lm),D("yt.scheduler.instance.enablePriorityThreshold",Mm),D("yt.scheduler.instance.clearPriorityThreshold",Nm),D("yt.scheduler.initialized",
!0))}
;function Pm(){im.apply(this,arguments)}
w(Pm,im);function Qm(){Pm.h||(Pm.h=new Pm);return Pm.h}
Pm.prototype.ab=function(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=E("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):il(a,c||0)};
Pm.prototype.qa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=E("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
Pm.prototype.start=function(){var a=E("yt.scheduler.instance.start");a&&a()};
Pm.prototype.pause=function(){var a=E("yt.scheduler.instance.pause");a&&a()};
var pi=Qm();S("web_scheduler_auto_init")&&Om();function Rm(a){var b=new Vi;(b=b.isAvailable()?a?new aj(b,a):b:null)||(a=new Wi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Ri(a):null;this.i=document.domain||window.location.hostname}
Rm.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape((new ch).serialize(b))}catch(f){return}else e=escape(b);Ql(a,e,c,this.i)};
Rm.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Rl(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Rm.prototype.remove=function(a){this.h&&this.h.remove(a);Sl(a,"/",this.i)};var Sm=function(){var a;return function(){a||(a=new Rm("ytidb"));return a}}();
function Tm(){var a;return null==(a=Sm())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Um=[],Vm,Wm=!1;function Xm(){var a={};for(Vm=new Ym(void 0===a.handleError?Zm:a.handleError,void 0===a.logEvent?$m:a.logEvent);0<Um.length;)switch(a=Um.shift(),a.type){case "ERROR":Vm.Pb(a.payload);break;case "EVENT":Vm.logEvent(a.eventType,a.payload)}}
function an(a){Wm||(Vm?Vm.Pb(a):(Um.push({type:"ERROR",payload:a}),10<Um.length&&Um.shift()))}
function bn(a,b){Wm||(Vm?Vm.logEvent(a,b):(Um.push({type:"EVENT",eventType:a,payload:b}),10<Um.length&&Um.shift()))}
;function cn(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function dn(a){return a.substr(0,a.indexOf(":"))||a}
;var en=ze||Ae;function fn(a){var b=Ob();return b?0<=b.toLowerCase().indexOf(a):!1}
;var gn={},hn=(gn.AUTH_INVALID="No user identifier specified.",gn.EXPLICIT_ABORT="Transaction was explicitly aborted.",gn.IDB_NOT_SUPPORTED="IndexedDB is not supported.",gn.MISSING_INDEX="Index not created.",gn.MISSING_OBJECT_STORES="Object stores not created.",gn.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",gn.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",gn.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
gn.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",gn.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",gn.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",gn.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",gn),jn={},kn=(jn.AUTH_INVALID="ERROR",jn.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",jn.EXPLICIT_ABORT="IGNORED",jn.IDB_NOT_SUPPORTED="ERROR",jn.MISSING_INDEX=
"WARNING",jn.MISSING_OBJECT_STORES="ERROR",jn.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",jn.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",jn.QUOTA_EXCEEDED="WARNING",jn.QUOTA_MAYBE_EXCEEDED="WARNING",jn.UNKNOWN_ABORT="WARNING",jn.INCOMPATIBLE_DB_VERSION="WARNING",jn),ln={},mn=(ln.AUTH_INVALID=!1,ln.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,ln.EXPLICIT_ABORT=!1,ln.IDB_NOT_SUPPORTED=!1,ln.MISSING_INDEX=!1,ln.MISSING_OBJECT_STORES=!1,ln.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,ln.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,ln.QUOTA_EXCEEDED=!1,ln.QUOTA_MAYBE_EXCEEDED=!0,ln.UNKNOWN_ABORT=!0,ln.INCOMPATIBLE_DB_VERSION=!1,ln);function nn(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?hn[a]:c;d=void 0===d?kn[a]:d;e=void 0===e?mn[a]:e;V.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,nn.prototype)}
w(nn,V);function on(a,b){nn.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},hn.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,on.prototype)}
w(on,nn);function pn(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,pn.prototype)}
w(pn,Error);var qn=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function rn(a,b,c,d){b=dn(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof nn)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new nn("QUOTA_EXCEEDED",a);if(Be&&"UnknownError"===e.name)return new nn("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof pn)return new nn("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&qn.some(function(f){return e.message.includes(f)}))return new nn("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new nn("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",td:e.name})];e.level="WARNING";return e}
function sn(a,b,c){var d=Tm();return new nn("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function tn(a){if(!a)throw Error();throw a;}
function un(a){return a}
function vn(a){this.h=a}
function wn(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=v(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=v(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
wn.all=function(a){return new wn(new vn(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={wb:0};f.wb<a.length;f={wb:f.wb},++f.wb)wn.resolve(a[f.wb]).then(function(g){return function(h){d[g.wb]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
wn.resolve=function(a){return new wn(new vn(function(b,c){a instanceof wn?a.then(b,c):b(a)}))};
wn.reject=function(a){return new wn(new vn(function(b,c){c(a)}))};
wn.prototype.then=function(a,b){var c=this,d=null!=a?a:un,e=null!=b?b:tn;return new wn(new vn(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){xn(c,c,d,f,g)}),c.i.push(function(){yn(c,c,e,f,g)})):"FULFILLED"===c.state.status?xn(c,c,d,f,g):"REJECTED"===c.state.status&&yn(c,c,e,f,g)}))};
wn.prototype.catch=function(a){return this.then(void 0,a)};
function xn(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof wn?zn(a,b,f,d,e):d(f)}catch(g){e(g)}}
function yn(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof wn?zn(a,b,f,d,e):d(f)}catch(g){e(g)}}
function zn(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof wn?zn(a,b,f,d,e):d(f)},function(f){e(f)})}
;function An(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Bn(a){return new Promise(function(b,c){An(a,b,c)})}
function Cn(a){return new wn(new vn(function(b,c){An(a,b,c)}))}
;function Dn(a,b){return new wn(new vn(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var En=window,W=En.ytcsi&&En.ytcsi.now?En.ytcsi.now:En.performance&&En.performance.timing&&En.performance.now&&En.performance.timing.navigationStart?function(){return En.performance.timing.navigationStart+En.performance.now()}:function(){return(new Date).getTime()};function Fn(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(W());this.i=!1}
m=Fn.prototype;m.add=function(a,b,c){return Gn(this,[a],{mode:"readwrite",ha:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return Gn(this,[a],{mode:"readwrite",ha:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return Gn(this,[a],{mode:"readonly",ha:!0},function(c){return c.objectStore(a).count(b)})};
function Hn(a,b,c){a=a.h.createObjectStore(b,c);return new In(a)}
m.delete=function(a,b){return Gn(this,[a],{mode:"readwrite",ha:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return Gn(this,[a],{mode:"readonly",ha:!0},function(c){return c.objectStore(a).get(b)})};
function Jn(a,b,c){return Gn(a,[b],{mode:"readwrite",ha:!0},function(d){d=d.objectStore(b);return Cn(d.h.put(c,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Gn(a,b,c,d){var e,f,g,h,k,l,n,p,t,r,x,y;return A(function(z){switch(z.h){case 1:var I={mode:"readonly",ha:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?I.mode=c:Object.assign(I,c);e=I;a.transactionCount++;f=e.ha?3:1;g=0;case 2:if(h){z.v(4);break}g++;k=Math.round(W());Aa(z,5);l=a.h.transaction(b,e.mode);I=z.yield;var J=new Kn(l);J=Ln(J,d);return I.call(z,J,7);case 7:return n=z.i,p=Math.round(W()),Mn(a,k,p,g,void 0,b.join(),e),z.return(n);case 5:t=Ba(z);r=Math.round(W());x=rn(t,
a.h.name,b.join(),a.h.version);if((y=x instanceof nn&&!x.h)||g>=f)Mn(a,k,r,g,x,b.join(),e),h=x;z.v(2);break;case 4:return z.return(Promise.reject(h))}})}
function Mn(a,b,c,d,e,f,g){b=c-b;e?(e instanceof nn&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&bn("QUOTA_EXCEEDED",{dbName:dn(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof nn&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),bn("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Nn(a,!1,d,f,b,g.tag),an(e)):Nn(a,!0,d,f,b,g.tag)}
function Nn(a,b,c,d,e,f){bn("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function In(a){this.h=a}
m=In.prototype;m.add=function(a,b){return Cn(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return Cn(this.h.clear()).then(function(){})};
function On(a,b,c){a.h.createIndex(b,c,{unique:!1})}
m.count=function(a){return Cn(this.h.count(a))};
function Pn(a,b){return Qn(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?Pn(this,a):Cn(this.h.delete(a))};
m.get=function(a){return Cn(this.h.get(a))};
m.index=function(a){try{return new Rn(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new pn(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function Qn(a,b,c){a=a.h.openCursor(b.query,b.direction);return Sn(a).then(function(d){return Dn(d,c)})}
function Kn(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=nn;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Ln(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return v(d).next().value})}
Kn.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new nn("EXPLICIT_ABORT");};
Kn.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new In(a),this.i.set(a,b));return b};
function Rn(a){this.h=a}
m=Rn.prototype;m.count=function(a){return Cn(this.h.count(a))};
m.delete=function(a){return Tn(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return Cn(this.h.get(a))};
m.getKey=function(a){return Cn(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function Tn(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Sn(a).then(function(d){return Dn(d,c)})}
function Un(a,b){this.request=a;this.cursor=b}
function Sn(a){return Cn(a).then(function(b){return b?new Un(a,b):null})}
m=Un.prototype;m.advance=function(a){this.cursor.advance(a);return Sn(this.request)};
m.continue=function(a){this.cursor.continue(a);return Sn(this.request)};
m.delete=function(){return Cn(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return Cn(this.cursor.update(a))};function Vn(a,b,c){return new Promise(function(d,e){function f(){t||(t=new Fn(g.result,{closed:p}));return t}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Sd,k=c.blocking,l=c.bf,n=c.upgrade,p=c.closed,t;g.addEventListener("upgradeneeded",function(r){try{if(null===r.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");r.dataLoss&&"none"!==r.dataLoss&&bn("IDB_DATA_CORRUPTED",{reason:r.dataLossMessage||"unknown reason",dbName:dn(a)});var x=f(),y=new Kn(g.transaction);
n&&n(x,function(z){return r.oldVersion<z&&r.newVersion>=z},y);
y.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var r=g.result;k&&r.addEventListener("versionchange",function(){k(f())});
r.addEventListener("close",function(){bn("IDB_UNEXPECTEDLY_CLOSED",{dbName:dn(a),dbVersion:r.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Wn(a,b,c){c=void 0===c?{}:c;return Vn(a,b,c)}
function Xn(a,b){b=void 0===b?{}:b;var c,d,e,f;return A(function(g){if(1==g.h)return Aa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Sd)&&c.addEventListener("blocked",function(){e()}),g.yield(Bn(c),4);
if(2!=g.h)g.h=0,g.l=0;else throw f=Ba(g),rn(f,a,"",-1);})}
;function Yn(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
Yn.prototype.i=function(a,b,c){c=void 0===c?{}:c;return Wn(a,b,c)};
Yn.prototype.delete=function(a){a=void 0===a?{}:a;return Xn(this.name,a)};
function Zn(a,b){return new nn("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function $n(a,b){if(!b)throw sn("openWithToken",dn(a.name));return a.open()}
Yn.prototype.open=function(){function a(){var f,g,h,k,l,n,p,t,r,x;return A(function(y){switch(y.h){case 1:return g=null!=(f=Error().stack)?f:"",Aa(y,2),y.yield(c.i(c.name,c.options.version,e),4);case 4:h=y.i;for(var z=c.options,I=[],J=v(Object.keys(z.Db)),M=J.next();!M.done;M=J.next()){M=M.value;var H=z.Db[M],O=void 0===H.Ie?Number.MAX_VALUE:H.Ie;!(h.h.version>=H.Ib)||h.h.version>=O||h.h.objectStoreNames.contains(M)||I.push(M)}k=I;if(0===k.length){y.v(5);break}l=Object.keys(c.options.Db);n=h.objectStoreNames();
if(c.m<U("ytidb_reopen_db_retries",0))return c.m++,h.close(),an(new nn("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());if(!(c.l<U("ytidb_remake_db_retries",1))){y.v(6);break}c.l++;return y.yield(c.delete(),7);case 7:return an(new nn("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());case 6:throw new on(n,l);case 5:return y.return(h);case 2:p=Ba(y);if(p instanceof DOMException?
"VersionError"!==p.name:"DOMError"in self&&p instanceof DOMError?"VersionError"!==p.name:!(p instanceof Object&&"message"in p)||"An attempt was made to open a database using a lower version than the existing version."!==p.message){y.v(8);break}return y.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:t=y.i;r=t.h.version;if(void 0!==c.options.version&&r>c.options.version+1)throw t.close(),c.j=!1,Zn(c,r);return y.return(t);case 8:throw b(),p instanceof Error&&!S("ytidb_async_stack_killswitch")&&
(p.stack=p.stack+"\n"+g.substring(g.indexOf("\n")+1)),rn(p,c.name,"",null!=(x=c.options.version)?x:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw Zn(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,bf:b,upgrade:this.options.upgrade};return this.h=d=a()};var ao=new Yn("YtIdbMeta",{Db:{databases:{Ib:1}},upgrade:function(a,b){b(1)&&Hn(a,"databases",{keyPath:"actualName"})}});
function bo(a,b){var c;return A(function(d){if(1==d.h)return d.yield($n(ao,b),2);c=d.i;return d.return(Gn(c,["databases"],{ha:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Cn(f.h.put(a,void 0)).then(function(){})})}))})}
function co(a,b){var c;return A(function(d){if(1==d.h)return a?d.yield($n(ao,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function eo(a,b){var c,d;return A(function(e){return 1==e.h?(c=[],e.yield($n(ao,b),2)):3!=e.h?(d=e.i,e.yield(Gn(d,["databases"],{ha:!0,mode:"readonly"},function(f){c.length=0;return Qn(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function fo(a){return eo(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function go(a,b,c){return eo(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function ho(a){var b,c;return A(function(d){if(1==d.h)return b=hm("YtIdbMeta hasAnyMeta other"),d.yield(eo(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var io,jo=new function(){}(new function(){});
function ko(){var a,b,c,d;return A(function(e){switch(e.h){case 1:a=Tm();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=en)f=/WebKit\/([0-9]+)/.exec(Ob()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Ob()),f=!(f&&602<=parseInt(f[1],10)));if(f||Nc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
Aa(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(bo(d,jo),4);case 4:return e.yield(co("yt-idb-test-do-not-use",jo),5);case 5:return e.return(!0);case 2:return Ba(e),e.return(!1)}})}
function lo(){if(void 0!==io)return io;Wm=!0;return io=ko().then(function(a){Wm=!1;var b;if(null!=(b=Sm())&&b.h){var c;b={hasSucceededOnce:(null==(c=Tm())?void 0:c.hasSucceededOnce)||a};var d;null==(d=Sm())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function mo(){return E("ytglobal.idbToken_")||void 0}
function no(){var a=mo();return a?Promise.resolve(a):lo().then(function(b){(b=b?jo:void 0)&&D("ytglobal.idbToken_",b);return b})}
;var oo=0;function po(a,b){oo||(oo=pi.oa(function(){var c,d,e,f,g;return A(function(h){switch(h.h){case 1:return h.yield(no(),2);case 2:c=h.i;if(!c)return h.return();d=!0;Aa(h,3);return h.yield(go(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.v(6);break}f=e[0];return h.yield(Xn(f.actualName),7);case 7:return h.yield(co(f.actualName,c),6);case 6:h.h=4;h.l=0;break;case 3:g=Ba(h),an(g),d=!1;case 4:pi.qa(oo),oo=0,d&&po(a,b),h.h=0}})}))}
function qo(){var a;return A(function(b){return 1==b.h?b.yield(no(),2):(a=b.i)?b.return(ho(a)):b.return(!1)})}
new Eh;function ro(a){if(!gm())throw a=new nn("AUTH_INVALID",{dbName:a}),an(a),a;var b=hm();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function so(a,b,c,d){var e,f,g,h,k,l;return A(function(n){switch(n.h){case 1:return f=null!=(e=Error().stack)?e:"",n.yield(no(),2);case 2:g=n.i;if(!g)throw h=sn("openDbImpl",a,b),S("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),an(h),h;cn(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:ro(a);Aa(n,3);return n.yield(bo(k,g),5);case 5:return n.yield(Wn(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=Ba(n),Aa(n,7),n.yield(co(k.actualName,
g),9);case 9:n.h=8;n.l=0;break;case 7:Ba(n);case 8:throw l;}})}
function to(a,b,c){c=void 0===c?{}:c;return so(a,b,!1,c)}
function uo(a,b,c){c=void 0===c?{}:c;return so(a,b,!0,c)}
function vo(a,b){b=void 0===b?{}:b;var c,d;return A(function(e){if(1==e.h)return e.yield(no(),2);if(3!=e.h){c=e.i;if(!c)return e.return();cn(a);d=ro(a);return e.yield(Xn(d.actualName,b),3)}return e.yield(co(d.actualName,c),0)})}
function wo(a,b,c){a=a.map(function(d){return A(function(e){return 1==e.h?e.yield(Xn(d.actualName,b),2):e.yield(co(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function xo(){var a=void 0===a?{}:a;var b,c;return A(function(d){if(1==d.h)return d.yield(no(),2);if(3!=d.h){b=d.i;if(!b)return d.return();cn("LogsDatabaseV2");return d.yield(fo(b),3)}c=d.i;return d.yield(wo(c,a,b),0)})}
function yo(a,b){b=void 0===b?{}:b;var c;return A(function(d){if(1==d.h)return d.yield(no(),2);if(3!=d.h){c=d.i;if(!c)return d.return();cn(a);return d.yield(Xn(a,b),3)}return d.yield(co(a,c),0)})}
;function zo(a,b){Yn.call(this,a,b);this.options=b;cn(a)}
w(zo,Yn);function Ao(a,b){var c;return function(){c||(c=new zo(a,b));return c}}
zo.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.qc?uo:to)(a,b,Object.assign({},c))};
zo.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.qc?yo:vo)(this.name,a)};
function Bo(a,b){return Ao(a,b)}
;var Co={},Do=Bo("ytGcfConfig",{Db:(Co.coldConfigStore={Ib:1},Co.hotConfigStore={Ib:1},Co),qc:!1,upgrade:function(a,b){b(1)&&(On(Hn(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),On(Hn(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Eo(a){return $n(Do(),a)}
function Fo(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:W()},g.yield(Eo(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(Jn(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Go(a,b,c,d){var e,f,g;return A(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:W()},h.yield(Eo(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(Jn(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Ho(a){var b,c;return A(function(d){return 1==d.h?d.yield(Eo(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(Gn(b,["coldConfigStore"],{mode:"readwrite",ha:!0},function(e){return Tn(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Io(a){var b,c;return A(function(d){return 1==d.h?d.yield(Eo(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(Gn(b,["hotConfigStore"],{mode:"readwrite",ha:!0},function(e){return Tn(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Jo(){G.call(this);this.i=[];this.h=[];var a=E("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(ja(a)),this.h=a):(this.h=[],D("yt.gcf.config.hotUpdateCallbacks",this.h))}
w(Jo,G);Jo.prototype.M=function(){for(var a=v(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);0<=b&&c.splice(b,1)}this.i.length=0;G.prototype.M.call(this)};function Ko(){this.h=0;this.i=new Jo}
function Lo(){var a;return null!=(a=E("yt.gcf.config.hotConfigGroup"))?a:null}
function Mo(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:if(!S("start_client_gcf")){g.v(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.l(b);d=mo();if(!d){g.v(3);break}if(c){g.v(4);break}return g.yield(Io(d),5);case 5:e=g.i,c=null==(f=e)?void 0:f.config;case 4:return g.yield(Fo(c,b,d),3);case 3:if(c)for(var h=c,k=v(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function No(a,b,c){var d,e,f,g;return A(function(h){if(1==h.h){if(!S("start_client_gcf"))return h.v(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=mo())?c?h.v(4):h.yield(Ho(d),5):h.v(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.v(0);g=c.configData;return h.yield(Go(c,b,g,d),0)})}
function Oo(){if(!Ko.h){var a=new Ko;Ko.h=a}a=Ko.h;var b=W()-a.h;if(!(0!==a.h&&b<U("send_config_hash_timer"))){b=E("yt.gcf.config.coldConfigData");var c=E("yt.gcf.config.hotHashData"),d=E("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=W());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
Ko.prototype.l=function(a){this.hotHashData=a;D("yt.gcf.config.hotHashData",this.hotHashData||null)};function Po(){return"INNERTUBE_API_KEY"in Lk&&"INNERTUBE_API_VERSION"in Lk}
function Qo(){return{innertubeApiKey:R("INNERTUBE_API_KEY"),innertubeApiVersion:R("INNERTUBE_API_VERSION"),ne:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),od:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Sf:R("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION"),pe:R("INNERTUBE_CONTEXT_HL"),oe:R("INNERTUBE_CONTEXT_GL"),qe:R("INNERTUBE_HOST_OVERRIDE")||"",se:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),re:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Ro(a){var b={client:{hl:a.pe,gl:a.oe,clientName:a.od,clientVersion:a.innertubeContextClientVersion,configInfo:a.ne}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=C.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=el();0<c.length&&(b.request={internalExperimentFlags:c});c=a.od;if(("WEB"===c||"MWEB"===c||1===c||2===c)&&b){var d;b.client.mainAppWebInfo=null!=(d=b.client.mainAppWebInfo)?
d:{};b.client.mainAppWebInfo.webDisplayMode=Pl()}(d=E("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(S("web_log_memory_total_kbytes")&&(null==(e=C.navigator)?0:e.deviceMemory)){var f;e=null==(f=C.navigator)?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+1E6*e)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=em())&&b&&(b.client.connectionType=a);S("web_log_effective_connection_type")&&(a=fm())&&
b&&(b.client.effectiveConnectionType=a);S("start_client_gcf")&&(e=Oo())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,a&&f&&e&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.coldConfigData=a,b.client.configInfo.coldHashData=f,b.client.configInfo.hotHashData=e));R("DELEGATED_SESSION_ID")&&!S("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});!S("fill_delegate_context_in_gel_killswitch")&&(a=R("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;f=a.assign;e=b.client;d={};c=v(Object.entries(Zk(R("DEVICE",""))));for(var g=c.next();!g.done;g=c.next()){var h=v(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?d.deviceMake=h:"cmodel"===g?d.deviceModel=h:"cbr"===g?d.browserName=h:"cbrver"===g?d.browserVersion=h:"cos"===g?d.osName=h:"cosver"===g?d.osVersion=h:"cplatform"===g&&(d.platform=h)}b.client=f.call(a,e,d);return b}
function So(a,b,c){c=void 0===c?{}:c;var d={};R("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":R("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||R("AUTHORIZATION");b||(a?b="Bearer "+E("gapi.auth.getToken")().Mf:(a=Ml(Ll()),S("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;function To(a,b){this.version=a;this.args=b}
To.prototype.serialize=function(){return{version:this.version,args:this.args}};function Uo(a,b){this.topic=a;this.h=b}
Uo.prototype.toString=function(){return this.topic};var Vo=E("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.Gb;L.prototype.publish=L.prototype.Za;L.prototype.clear=L.prototype.clear;D("ytPubsub2Pubsub2Instance",Vo);var Wo=E("ytPubsub2Pubsub2SubscribedKeys")||{};D("ytPubsub2Pubsub2SubscribedKeys",Wo);var Xo=E("ytPubsub2Pubsub2TopicToKeys")||{};D("ytPubsub2Pubsub2TopicToKeys",Xo);var Yo=E("ytPubsub2Pubsub2IsAsync")||{};D("ytPubsub2Pubsub2IsAsync",Yo);
D("ytPubsub2Pubsub2SkipSubKey",null);function Zo(a,b){var c=$o();c&&c.publish.call(c,a.toString(),a,b)}
function ap(a){var b=bp,c=$o();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=E("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Wo[d])try{if(f&&b instanceof Uo&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Xa){var l=new h;h.Xa=l.version}var n=h.Xa}catch(z){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var p=n.construct;
var t=k.args,r=t.length;if(0<r){var x=Array(r);for(k=0;k<r;k++)x[k]=t[k];var y=x}else y=[];f=p.call(n,h,y)}catch(z){throw z.message="yt.pubsub2.Data.deserialize(): "+z.message,z;}}catch(z){throw z.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+z.message,z;}a.call(window,f)}catch(z){Rk(z)}},Yo[b.toString()]?E("yt.scheduler.instance")?pi.oa(g):il(g,0):g())});
Wo[d]=!0;Xo[b.toString()]||(Xo[b.toString()]=[]);Xo[b.toString()].push(d);return d}
function cp(){var a=dp,b=ap(function(c){a.apply(void 0,arguments);ep(b)});
return b}
function ep(a){var b=$o();b&&("number"===typeof a&&(a=[a]),eb(a,function(c){b.unsubscribeByKey(c);delete Wo[c]}))}
function $o(){return E("ytPubsub2Pubsub2Instance")}
;function fp(a,b,c){c=void 0===c?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&Zo("meta_logging_csi_event",{timerName:a,ig:b})}
;var gp=void 0,hp=void 0;function ip(){if(!hp){var a=R("WORKER_SERIALIZATION_URL");hp=a?(a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue)?Gb(a):null:null}return hp||void 0}
function jp(){var a=ip();gp||void 0===a||(gp=new Worker(Eb(a),void 0));return gp}
;var kp=U("max_body_size_to_compress",5E5),lp=U("min_body_size_to_compress",500),mp=!0,np=0,op=0,pp=U("compression_performance_threshold_lr",250),qp=U("slow_compressions_before_abandon_count",4),rp=!1,sp=new Map,tp=1;function up(){if("function"===typeof Worker&&ip()){var a=function(c){c=c.data;if("gzippedGelBatch"===c.op){var d=sp.get(c.key);d&&(vp(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),sp.delete(c.key))}},b=jp();
b&&(b.addEventListener("message",a),b.onerror=function(){sp.clear()},rp=!0)}}
function wp(a,b,c,d,e){e=void 0===e?!1:e;var f={startTime:W(),ticks:{},infos:{}};if(mp)try{var g=xp(b);if(null!=g&&(g>kp||g<lp))d(a,c);else{if(S("gzip_gel_with_worker")){rp||up();var h=jp();if(h&&!e){sp.set(tp,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:tp});tp++;return}}var k=nk(ki(b));vp(k,f,a,c,d)}}catch(l){Sk(l),d(a,c)}else d(a,c)}
function vp(a,b,c,d,e){var f=W();b.ticks.gelc=f;op++;S("disable_compression_due_to_performance_degredation")&&f-b.startTime>=pp&&(np++,S("abandon_compression_after_N_slow_zips")?op===U("compression_disable_point")&&np>qp&&(mp=!1):mp=!1);yp(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function zp(a){var b=void 0===b?!1:b;var c=void 0===c?!1:c;var d=W(),e={startTime:d,ticks:{},infos:{}},f=b?E("yt.logging.gzipForFetch",!1):!0;if(mp&&f){if(!a.body)return a;try{var g=c?a.body:"string"===typeof a.body?a.body:JSON.stringify(a.body);f=g;if(!c&&"string"===typeof g){var h=xp(g);if(null!=h&&(h>kp||h<lp))return a;f=nk(ki(g),b?{level:1}:void 0);var k=W();e.ticks.gelc=k;if(b){op++;if((S("disable_compression_due_to_performance_degredation")||S("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=pp)if(np++,S("abandon_compression_after_N_slow_zips")||S("abandon_compression_after_N_slow_zips_lr")){b=np/op;var l=qp/U("compression_disable_point");0<op&&0===op%U("compression_disable_point")&&b>=l&&(mp=!1)}else mp=!1;yp(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(n){return Sk(n),a}}else return a}
function xp(a){try{return(new Blob(a.split(""))).size}catch(b){return Sk(b),null}}
function yp(a){S("gel_compression_csi_killswitch")||!S("log_gel_compression_latency")&&!S("log_gel_compression_latency_lr")||fp("gel_compression",a,{sampleRate:.1})}
;function Ap(a){a=Object.assign({},a);delete a.Authorization;var b=yg();if(b){var c=new vi;c.update(R("INNERTUBE_API_KEY"));c.update(b);a.hash=Ee(c.digest(),3)}return a}
;var Bp;function Cp(){Bp||(Bp=new Rm("yt.innertube"));return Bp}
function Dp(a,b,c,d){if(d)return null;d=Cp().get("nextId",!0)||1;var e=Cp().get("requests",!0)||{};e[d]={method:a,request:b,authState:Ap(c),requestTime:Math.round(W())};Cp().set("nextId",d+1,86400,!0);Cp().set("requests",e,86400,!0);return d}
function Ep(a){var b=Cp().get("requests",!0)||{};delete b[a];Cp().set("requests",b,86400,!0)}
function Fp(a){var b=Cp().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(W())-d.requestTime)){var e=d.authState,f=Ap(So(!1));rb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(W())),Gp(a,d.method,e,{}));delete b[c]}}Cp().set("requests",b,86400,!0)}}
;function Hp(a){this.Xb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ub=function(){};
this.now=Date.now;this.Mb=!1;var b;this.Fd=null!=(b=a.Fd)?b:100;var c;this.zd=null!=(c=a.zd)?c:1;var d;this.xd=null!=(d=a.xd)?d:2592E6;var e;this.vd=null!=(e=a.vd)?e:12E4;var f;this.yd=null!=(f=a.yd)?f:5E3;var g;this.T=null!=(g=a.T)?g:void 0;this.dc=!!a.dc;var h;this.ac=null!=(h=a.ac)?h:.1;var k;this.nc=null!=(k=a.nc)?k:10;a.handleError&&(this.handleError=a.handleError);a.ub&&(this.ub=a.ub);a.Mb&&(this.Mb=a.Mb);a.Xb&&(this.Xb=a.Xb);this.U=a.U;this.Ea=a.Ea;this.ba=a.ba;this.aa=a.aa;this.sendFn=a.sendFn;
this.Mc=a.Mc;this.Lc=a.Lc;Ip(this)&&(!this.U||this.U("networkless_logging"))&&Jp(this)}
function Jp(a){Ip(a)&&!a.Mb&&(a.h=!0,a.dc&&Math.random()<=a.ac&&a.ba.Ud(a.T),Kp(a),a.aa.wa()&&a.Vb(),a.aa.listen(a.Mc,a.Vb.bind(a)),a.aa.listen(a.Lc,a.bd.bind(a)))}
m=Hp.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Ip(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ba.set(d,this.T).then(function(e){d.id=e;c.aa.wa()&&Lp(c,d)}).catch(function(e){Lp(c,d);
Mp(c,e)})}else this.sendFn(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Ip(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.U&&this.U("nwl_skip_retry")&&(e.skipRetry=c);if(this.aa.wa()||this.U&&this.U("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(1==k.h)return k.yield(d.ba.set(e,d.T).catch(function(l){Mp(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ba.set(e,this.T).catch(function(g){d.sendFn(a,b,e.skipRetry);
Mp(d,g)})}else this.sendFn(a,b,this.U&&this.U("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Ip(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.ba.qb(d.id,c.T):e=!0;c.aa.gb&&c.U&&c.U("vss_network_hint")&&c.aa.gb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ba.set(d,this.T).then(function(g){d.id=g;e&&c.ba.qb(d.id,c.T)}).catch(function(g){Mp(c,g)})}else this.sendFn(a,b,void 0,!0)};
m.Vb=function(){var a=this;if(!Ip(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ea.oa(function(){var b;return A(function(c){if(1==c.h)return c.yield(a.ba.ld("NEW",a.T),2);if(3!=c.h)return b=c.i,b?c.yield(Lp(a,b),3):(a.bd(),c.return());a.i&&(a.i=0,a.Vb());c.h=0})},this.Fd))};
m.bd=function(){this.Ea.qa(this.i);this.i=0};
function Lp(a,b){var c;return A(function(d){switch(d.h){case 1:if(!Ip(a))throw Error("IndexedDB is not supported: immediateSend");if(void 0===b.id){d.v(2);break}return d.yield(a.ba.ue(b.id,a.T),3);case 3:(c=d.i)||a.ub(Error("The request cannot be found in the database."));case 2:if(Np(a,b,a.xd)){d.v(4);break}a.ub(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){d.v(5);break}return d.yield(a.ba.qb(b.id,a.T),5);case 5:return d.return();case 4:b.skipRetry||(b=Op(a,
b));if(!b){d.v(0);break}if(!b.skipRetry||void 0===b.id){d.v(8);break}return d.yield(a.ba.qb(b.id,a.T),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function Op(a,b){if(!Ip(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(n){switch(n.h){case 1:g=Pp(f);(h=Qp(f))&&a.U&&a.U("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.U&&a.U("nwl_consider_error_code")&&g||a.U&&!a.U("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.nc)){n.v(2);break}if(!a.aa.pc){n.v(3);break}return n.yield(a.aa.pc(),3);case 3:if(a.aa.wa()){n.v(2);break}c(e,f);if(!a.U||!a.U("nwl_consider_error_code")||void 0===(null==(k=b)?void 0:k.id)){n.v(6);
break}return n.yield(a.ba.Pc(b.id,a.T,!1),6);case 6:return n.return();case 2:if(a.U&&a.U("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.nc)return n.return();a.potentialEsfErrorCounter++;if(void 0===(null==(l=b)?void 0:l.id)){n.v(8);break}return b.sendCount<a.zd?n.yield(a.ba.Pc(b.id,a.T,!0,h?!1:void 0),12):n.yield(a.ba.qb(b.id,a.T),8);case 12:a.Ea.oa(function(){a.aa.wa()&&a.Vb()},a.yd);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.v(2):h.yield(a.ba.qb(b.id,a.T),2);a.aa.gb&&a.U&&a.U("vss_network_hint")&&a.aa.gb(!0);d(e,f);h.h=0})};
return b}
function Np(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Kp(a){if(!Ip(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ba.ld("QUEUED",a.T).then(function(b){b&&!Np(a,b,a.vd)?a.Ea.oa(function(){return A(function(c){if(1==c.h)return void 0===b.id?c.v(2):c.yield(a.ba.Pc(b.id,a.T),2);Kp(a);c.h=0})}):a.aa.wa()&&a.Vb()})}
function Mp(a,b){a.Ld&&!a.aa.wa()?a.Ld(b):a.handleError(b)}
function Ip(a){return!!a.T||a.Xb}
function Pp(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function Qp(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var Rp;
function Sp(){if(Rp)return Rp();var a={};Rp=Bo("LogsDatabaseV2",{Db:(a.LogsRequestsStore={Ib:2},a),qc:!1,upgrade:function(b,c,d){c(2)&&Hn(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),On(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Rp()}
;function Tp(a){return $n(Sp(),a)}
function Up(a,b){var c,d,e,f;return A(function(g){if(1==g.h)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(Tp(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:R("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(Jn(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=W();Vp(c);return g.return(f)})}
function Wp(a,b){var c,d,e,f,g,h,k;return A(function(l){if(1==l.h)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},l.yield(Tp(b),2);if(3!=l.h)return d=l.i,e=R("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,W()],h=IDBKeyRange.bound(f,g),k=void 0,l.yield(Gn(d,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(n){return Tn(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(p){p.getValue()&&(k=p.getValue(),"NEW"===
a&&(k.status="QUEUED",p.update(k)))})}),3);
c.ticks.tc=W();Vp(c);return l.return(k)})}
function Xp(a,b){var c;return A(function(d){if(1==d.h)return d.yield(Tp(b),2);c=d.i;return d.return(Gn(c,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Cn(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Yp(a,b,c,d){c=void 0===c?!0:c;var e;return A(function(f){if(1==f.h)return f.yield(Tp(b),2);e=f.i;return f.return(Gn(e,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),void 0!==d&&(k.options.compress=d),Cn(h.h.put(k,void 0)).then(function(){return k})):wn.resolve(void 0)})}))})}
function Zp(a,b){var c;return A(function(d){if(1==d.h)return d.yield(Tp(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function $p(a){var b,c;return A(function(d){if(1==d.h)return d.yield(Tp(a),2);b=d.i;c=W()-2592E6;return d.yield(Gn(b,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(e){return Qn(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function aq(){A(function(a){return a.yield(xo(),0)})}
function Vp(a){S("nwl_csi_killswitch")||fp("networkless_performance",a,{sampleRate:1})}
;var bq={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,mbsConnectionInitiated:138,mbsPlaybackInitiated:139,
mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,
kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,transactionFlowPaymentSubmitted:460,
transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,ypcPauseFlowSucceeded:190,
ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,ypcFamilyCreateFlowCancelled:259,
ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,accountRegistryChange:226,
userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,musicSideloadedPlaylistServiceCalled:246,
embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,yongleUsbSetup:271,touStrikeInterstitialEvent:272,
liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,
delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,
voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,
sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,
clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,
startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,
playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,genericClientExperimentEvent:423,
homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,
dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,
producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,
cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486};var cq={},dq=Bo("ServiceWorkerLogsDatabase",{Db:(cq.SWHealthLog={Ib:1},cq),qc:!0,upgrade:function(a,b){b(1)&&On(Hn(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function eq(a){return $n(dq(),a)}
function fq(a){var b,c;A(function(d){if(1==d.h)return d.yield(eq(a),2);b=d.i;c=W()-2592E6;return d.yield(Gn(b,["SWHealthLog"],{mode:"readwrite",ha:!0},function(e){return Qn(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function gq(a){var b;return A(function(c){if(1==c.h)return c.yield(eq(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var hq={},iq=0;function jq(a){var b=new Image,c=""+iq++;hq[c]=b;b.onload=b.onerror=function(){delete hq[c]};
b.src=a}
;function kq(){this.h=new Map;this.i=!1}
function lq(){if(!kq.h){var a=E("yt.networkRequestMonitor.instance")||new kq;D("yt.networkRequestMonitor.instance",a);kq.h=a}return kq.h}
kq.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
kq.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
kq.prototype.removeParams=function(a){return a.split("?")[0]};
kq.prototype.removeParams=kq.prototype.removeParams;kq.prototype.isEndpointCFR=kq.prototype.isEndpointCFR;kq.prototype.requestComplete=kq.prototype.requestComplete;kq.getInstance=lq;var mq;function nq(){mq||(mq=new Rm("yt.offline"));return mq}
function oq(a){if(S("offline_error_handling")){var b=nq().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);nq().set("errors",b,2592E3,!0)}}
;function pq(){xd.call(this);var a=this;this.j=!1;this.i=oi();this.i.listen("networkstatus-online",function(){if(a.j&&S("offline_error_handling")){var b=nq().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new V(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Rk(d)}nq().set("errors",{},2592E3,!0)}}})}
w(pq,xd);function qq(){if(!pq.h){var a=E("yt.networkStatusManager.instance")||new pq;D("yt.networkStatusManager.instance",a);pq.h=a}return pq.h}
m=pq.prototype;m.wa=function(){return this.i.wa()};
m.gb=function(a){this.i.i=a};
m.je=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.Zd=function(){this.j=!0};
m.listen=function(a,b){return this.i.listen(a,b)};
m.pc=function(a){a=mi(this.i,a);a.then(function(b){S("use_cfr_monitor")&&lq().requestComplete("generate_204",b)});
return a};
pq.prototype.sendNetworkCheckRequest=pq.prototype.pc;pq.prototype.listen=pq.prototype.listen;pq.prototype.enableErrorFlushing=pq.prototype.Zd;pq.prototype.getWindowStatus=pq.prototype.je;pq.prototype.networkStatusHint=pq.prototype.gb;pq.prototype.isNetworkAvailable=pq.prototype.wa;pq.getInstance=qq;function rq(a){a=void 0===a?{}:a;xd.call(this);var b=this;this.i=this.m=0;this.j=qq();var c=E("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){sq(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){sq(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){yd(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){yd(b,"publicytnetworkstatus-offline")})))}
w(rq,xd);rq.prototype.wa=function(){var a=E("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
rq.prototype.gb=function(a){var b=E("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
rq.prototype.pc=function(a){var b=this,c;return A(function(d){c=E("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return S("skip_network_check_if_cfr")&&lq().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.gb((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.wa())})):c?d.return(c(a)):d.return(!0)})};
function sq(a,b){a.rateLimit?a.i?(pi.qa(a.m),a.m=pi.oa(function(){a.l!==b&&(yd(a,b),a.l=b,a.i=W())},a.rateLimit-(W()-a.i))):(yd(a,b),a.l=b,a.i=W()):yd(a,b)}
;var tq;function uq(){var a=Hp.call;tq||(tq=new rq({Xf:!0,Qf:!0}));a.call(Hp,this,{ba:{Ud:$p,qb:Zp,ld:Wp,ue:Xp,Pc:Yp,set:Up},aa:tq,handleError:function(b,c,d){var e,f=null==d?void 0:null==(e=d.error)?void 0:e.code;if(400===f||415===f){var g;Sk(new V(b.message,c,null==d?void 0:null==(g=d.error)?void 0:g.code),void 0,void 0,void 0,!0)}else Rk(b)},
ub:Sk,sendFn:vq,now:W,Ld:oq,Ea:Qm(),Mc:"publicytnetworkstatus-online",Lc:"publicytnetworkstatus-offline",dc:!0,ac:.1,nc:U("potential_esf_error_limit",10),U:S,Mb:!(gm()&&wq())});this.j=new Eh;S("networkless_immediately_drop_all_requests")&&aq();yo("LogsDatabaseV2")}
w(uq,Hp);function xq(){var a=E("yt.networklessRequestController.instance");a||(a=new uq,D("yt.networklessRequestController.instance",a),S("networkless_logging")&&no().then(function(b){a.T=b;Jp(a);a.j.resolve();a.dc&&Math.random()<=a.ac&&a.T&&fq(a.T);S("networkless_immediately_drop_sw_health_store")&&yq(a)}));
return a}
uq.prototype.writeThenSend=function(a,b){b||(b={});gm()||(this.h=!1);Hp.prototype.writeThenSend.call(this,a,b)};
uq.prototype.sendThenWrite=function(a,b,c){b||(b={});gm()||(this.h=!1);Hp.prototype.sendThenWrite.call(this,a,b,c)};
uq.prototype.sendAndWrite=function(a,b){b||(b={});gm()||(this.h=!1);Hp.prototype.sendAndWrite.call(this,a,b)};
uq.prototype.awaitInitialization=function(){return this.j.promise};
function yq(a){var b;A(function(c){if(!a.T)throw b=sn("clearSWHealthLogsDb"),b;return c.return(gq(a.T).catch(function(d){a.handleError(d)}))})}
function vq(a,b,c,d){d=void 0===d?!1:d;b=S("web_fp_via_jspb")?Object.assign({},b):b;S("use_cfr_monitor")&&zq(a,b);if(S("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));else{var e;if(null==(e=b.postParams)?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(W())}if(c&&0===Object.keys(b).length){var f=void 0===f?"":f;var g=void 0===g?!1:g;var h=void 0===h?!1:h;if(a)if(f)sl(a,void 0,"POST",f);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))sl(a,
void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new ab({url:a});if(k.j&&k.i||k.l){var l=bc(cc(5,a)),n;if(!(n=!l||!l.endsWith("/aclk"))){var p=a.search(qc),t=pc(a,0,"ri",p);if(0>t)var r=null;else{var x=a.indexOf("&",t);if(0>x||x>p)x=p;r=decodeURIComponent(a.slice(t+3,-1!==x?x:0).replace(/\+/g," "))}n="1"!==r}var y=!n;break b}}catch(I){}y=!1}if(y){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(I){}z=!1}c=z?!0:!1}else c=!1;c||
jq(a)}}else b.compress?b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),wp(a,b.postBody,b,pl,d)):wp(a,JSON.stringify(b.postParams),b,xl,d):pl(a,b)}
function zq(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){lq().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){lq().requestComplete(a,!0);d(e,f)}}
function wq(){return"www.youtube-nocookie.com"!==dc(document.location.toString())}
;var Aq=!1,Bq=C.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Aq};D("ytNetworklessLoggingInitializationOptions",Bq);function Cq(){var a;A(function(b){if(1==b.h)return b.yield(no(),2);a=b.i;if(!a||!gm()&&!S("nwl_init_require_datasync_id_killswitch")||!wq())return b.v(0);Aq=!0;Bq.isNwlInitialized=Aq;return b.yield(xq().awaitInitialization(),0)})}
;function Dq(a){var b=this;this.config_=null;a?this.config_=a:Po()&&(this.config_=Qo());jm(function(){Fp(b)},5E3)}
Dq.prototype.isReady=function(){!this.config_&&Po()&&(this.config_=Qo());return!!this.config_};
function Gp(a,b,c,d){function e(x){x=void 0===x?!1:x;var y;if(d.retry&&"www.youtube-nocookie.com"!=h&&(x||S("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(y=Dp(b,c,l,k)),y)){var z=g.onSuccess,I=g.onFetchSuccess;g.onSuccess=function(H,O){Ep(y);z(H,O)};
c.onFetchSuccess=function(H,O){Ep(y);I(H,O)}}try{if(x&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?xq().writeThenSend(r,g):xq().sendAndWrite(r,g);
else if(d.compress){var J=!d.networklessOptions.writeThenSend;if(g.postBody){var M=g.postBody;"string"!==typeof M&&(M=JSON.stringify(g.postBody));wp(r,M,g,pl,J)}else wp(r,JSON.stringify(g.postParams),g,xl,J)}else S("web_all_payloads_via_jspb")?pl(r,g):xl(r,g)}catch(H){if("InvalidAccessError"==H.name)y&&(Ep(y),y=0),Sk(Error("An extension is blocking network request."));else throw H;}y&&jm(function(){Fp(a)},5E3)}
!R("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Sk(new V("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new V("innertube xhrclient not ready",b,c,d);Rk(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(x,y){if(d.onSuccess)d.onSuccess(y)},
onFetchSuccess:function(x){if(d.onSuccess)d.onSuccess(x)},
onError:function(x,y){if(d.onError)d.onError(y)},
onFetchError:function(x){if(d.onError)d.onError(x)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.qe)&&(h=f);var k=a.config_.se||!1,l=So(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},t=a.config_.re&&f;t=t&&f.startsWith("Bearer");t||(p.key=a.config_.innertubeApiKey);var r=al(""+h+n,p||{},!0);(E("ytNetworklessLoggingInitializationOptions")?
Bq.isNwlInitialized:Aq)?lo().then(function(x){e(x)}):e(!1)}
;var Eq=0,Fq=Pc?"webkit":Oc?"moz":Mc?"ms":Lc?"o":"";D("ytDomDomGetNextId",E("ytDomDomGetNextId")||function(){return++Eq});var Gq={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Hq(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Gq||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Iq(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Hq.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Hq.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Hq.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var nb=C.ytEventsEventsListeners||{};D("ytEventsEventsListeners",nb);var Jq=C.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",Jq);
function Kq(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return mb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Pa(e[4])&&Pa(d)&&rb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Lq=cb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Mq(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Kq(a,b,c,d);if(e)return e;e=++Jq.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Hq(h);if(!Hd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Hq(h);
h.currentTarget=a;return c.call(a,h)};
g=Qk(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Lq()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);nb[e]=[a,b,c,g,d];return e}
function Nq(a){a&&("string"==typeof a&&(a=[a]),eb(a,function(b){if(b in nb){var c=nb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Lq()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete nb[b]}}))}
;function Oq(a){this.D=a;this.h=null;this.l=0;this.s=null;this.m=0;this.i=[];for(a=0;4>a;a++)this.i.push(0);this.j=0;this.S=Mq(window,"mousemove",Va(this.W,this));a=Va(this.R,this);"function"===typeof a&&(a=Qk(a));this.Y=window.setInterval(a,25)}
Ya(Oq,G);Oq.prototype.W=function(a){void 0===a.h&&Iq(a);var b=a.h;void 0===a.i&&Iq(a);this.h=new Dd(b,a.i)};
Oq.prototype.R=function(){if(this.h){var a=W();if(0!=this.l){var b=this.s,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.l);this.i[this.j]=.5<Math.abs((d-this.m)/this.m)?1:0;for(c=b=0;4>c;c++)b+=this.i[c]||0;3<=b&&this.D();this.m=d}this.l=a;this.s=this.h;this.j=(this.j+1)%4}};
Oq.prototype.M=function(){window.clearInterval(this.Y);Nq(this.S)};var Pq=new Set([174,173,175]),Tq={};
function Uq(a){var b=void 0===a?{}:a;a=void 0===b.Ee?!1:b.Ee;b=void 0===b.ae?!0:b.ae;if(null==E("_lact",window)){var c=parseInt(R("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;D("_lact",c,window);D("_fact",c,window);-1==c&&Vq();Mq(document,"keydown",Vq);Mq(document,"keyup",Vq);Mq(document,"mousedown",Vq);Mq(document,"mouseup",Vq);a?Mq(window,"touchmove",function(){Wq("touchmove",200)},{passive:!0}):(Mq(window,"resize",function(){Wq("resize",200)}),b&&Mq(window,"scroll",function(){Wq("scroll",
200)}));
new Oq(function(){Wq("mouse",100)});
Mq(document,"touchstart",Vq,{passive:!0});Mq(document,"touchend",Vq,{passive:!0})}}
function Wq(a,b){Tq[a]||(Tq[a]=!0,pi.oa(function(){Vq();Tq[a]=!1},b))}
function Vq(a){var b;if(null!=(b=E("experiment.flags",window))&&b.enable_lact_reset_by_volume_buttons||!Pq.has(null==a?void 0:a.keyCode))null==E("_lact",window)&&Uq(),a=Date.now(),D("_lact",a,window),-1==E("_fact",window)&&D("_fact",a,window),(a=E("ytglobal.ytUtilActivityCallback_"))&&a()}
function Xq(){var a=E("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var Yq=C.ytPubsubPubsubInstance||new L,Zq=C.ytPubsubPubsubSubscribedKeys||{},$q=C.ytPubsubPubsubTopicToKeys||{},ar=C.ytPubsubPubsubIsSynchronous||{};function br(a,b){var c=cr();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Zq[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{ar[a]?f():il(f,0)}catch(g){Rk(g)}},void 0);
Zq[d]=!0;$q[a]||($q[a]=[]);$q[a].push(d);return d}return 0}
function dr(a){var b=cr();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),eb(a,function(c){b.unsubscribeByKey(c);delete Zq[c]}))}
function er(a,b){var c=cr();c&&c.publish.apply(c,arguments)}
function fr(a){var b=cr();if(b)if(b.clear(a),a)gr(a);else for(var c in $q)gr(c)}
function cr(){return C.ytPubsubPubsubInstance}
function gr(a){$q[a]&&(a=$q[a],eb(a,function(b){Zq[b]&&delete Zq[b]}),a.length=0)}
L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.Gb;L.prototype.publish=L.prototype.Za;L.prototype.clear=L.prototype.clear;D("ytPubsubPubsubInstance",Yq);D("ytPubsubPubsubTopicToKeys",$q);D("ytPubsubPubsubIsSynchronous",ar);D("ytPubsubPubsubSubscribedKeys",Zq);var hr=Symbol("injectionDeps");function ir(a){this.name=a}
ir.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function jr(a){this.key=a}
function kr(){this.h=new Map;this.i=new Map}
kr.prototype.resolve=function(a){return a instanceof jr?lr(this,a.key,[],!0):lr(this,a,[])};
function lr(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(void 0!==d.Id)var e=d.Id;else if(d.hf)e=d[hr]?mr(a,d[hr],c):[],e=d.hf.apply(d,ja(e));else if(d.Hd){e=d.Hd;var f=e[hr]?mr(a,e[hr],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ja(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.gg||a.i.set(b,e);return e}
function mr(a,b,c){return b?b.map(function(d){return d instanceof jr?lr(a,d.key,c,!0):lr(a,d,c)}):[]}
;var nr;function or(){nr||(nr=new kr);return nr}
;var pr=window;function qr(){var a,b;return"h5vcc"in pr&&(null==(a=pr.h5vcc.traceEvent)?0:a.traceBegin)&&(null==(b=pr.h5vcc.traceEvent)?0:b.traceEnd)?1:"performance"in pr&&pr.performance.mark&&pr.performance.measure?2:0}
function rr(a){switch(qr()){case 1:pr.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:pr.performance.mark(a+"-start");break;case 0:break;default:Ph()}}
function sr(a){switch(qr()){case 1:pr.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:var b=a+"-start",c=a+"-end";pr.performance.mark(c);pr.performance.measure(a,b,c);break;case 0:break;default:Ph()}}
;var tr=S("web_enable_lifecycle_monitoring")&&0!==qr(),ur=S("web_enable_lifecycle_monitoring");function vr(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Qm():d;this.j=c;this.scheduler=d;this.i=new Eh;this.h=a;for(a={cb:0};a.cb<this.h.length;a={Qb:a.Qb,cb:a.cb},a.cb++)a.Qb=this.h[a.cb],c=function(e){return function(){e.Qb.Gc();b.h[e.cb].oc=!0;b.h.every(function(f){return!0===f.oc})&&b.i.resolve()}}(a),d=this.getPriority(a.Qb),d=this.scheduler.ab(c,d),this.h[a.cb]=Object.assign({},a.Qb,{Gc:c,
jobId:d})}
function wr(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=v(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.oc||(a.scheduler.qa(c.jobId),a.scheduler.ab(c.Gc,10))}
vr.prototype.cancel=function(){for(var a=v(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.oc||this.scheduler.qa(b.jobId),b.oc=!0;this.i.resolve()};
vr.prototype.getPriority=function(a){var b;return null!=(b=a.priority)?b:this.j};function xr(a){this.state=a;this.plugins=[];this.l=void 0;this.s={};tr&&rr(this.state)}
m=xr.prototype;m.install=function(a){this.plugins.push(a);return this};
m.uninstall=function(){var a=this;B.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
m.transition=function(a,b){var c=this;tr&&sr(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(wr(this.j),this.j=void 0);yr(this,a,b);this.state=a;tr&&rr(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(zr(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function zr(a,b){var c=b.filter(function(e){return 10===Ar(a,e)}),d=b.filter(function(e){return 10!==Ar(a,e)});
return a.s.fg?function(){var e=B.apply(0,arguments);return A(function(f){if(1==f.h)return f.yield(a.Le.apply(a,[c].concat(ja(e))),2);a.Cd.apply(a,[d].concat(ja(e)));f.h=0})}:function(){var e=B.apply(0,arguments);
a.Me.apply(a,[c].concat(ja(e)));a.Cd.apply(a,[d].concat(ja(e)))}}
m.Me=function(a){for(var b=B.apply(1,arguments),c=Qm(),d=v(a),e=d.next(),f={};!e.done;f={zb:f.zb},e=d.next())f.zb=e.value,c.Hb(function(g){return function(){Br(g.zb.name);g.zb.callback.apply(g.zb,ja(b));Cr(g.zb.name)}}(f))};
m.Le=function(a){var b=B.apply(1,arguments),c,d,e,f,g;return A(function(h){1==h.h&&(c=Qm(),d=v(a),e=d.next(),f={});if(3!=h.h){if(e.done)return h.v(0);f.eb=e.value;f.Jb=void 0;g=function(k){return function(){Br(k.eb.name);var l=k.eb.callback.apply(k.eb,ja(b));"function"===typeof(null==l?void 0:l.then)?k.Jb=l.then(function(){Cr(k.eb.name)}):Cr(k.eb.name)}}(f);
c.Hb(g);return f.Jb?h.yield(f.Jb,3):h.v(3)}f={eb:f.eb,Jb:f.Jb};e=d.next();return h.v(2)})};
m.Cd=function(a){var b=B.apply(1,arguments),c=this,d=a.map(function(e){return{Gc:function(){Br(e.name);e.callback.apply(e,ja(b));Cr(e.name)},
priority:Ar(c,e)}});
d.length&&(this.j=new vr(d))};
function Ar(a,b){var c,d;return null!=(d=null!=(c=a.l)?c:b.priority)?d:0}
function Br(a){tr&&a&&rr(a)}
function Cr(a){tr&&a&&sr(a)}
function yr(a,b,c){ur&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
da.Object.defineProperties(xr.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Dr(a){xr.call(this,void 0===a?"none":a);this.h=null;this.l=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.m},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var Er;w(Dr,xr);Dr.prototype.i=function(a,b){var c=this;this.h=jm(function(){"application_navigating"===c.currentState&&c.transition("none")},5E3);
a(null==b?void 0:b.event)};
Dr.prototype.m=function(a,b){this.h&&(pi.qa(this.h),this.h=null);a(null==b?void 0:b.event)};
function Fr(){Er||(Er=new Dr);return Er}
;function Gr(){this.store={};this.h={}}
Gr.prototype.storePayload=function(a,b){a=Hr(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
Gr.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=Ir(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,ja(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,ja(this.store[b[d]].splice(0,a.sizeLimit))));(null==a?0:a.sizeLimit)&&c.length<(null==a?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,ja(this.smartExtractMatchingEntries(a))));return c};
Gr.prototype.extractMatchingEntries=function(a){a=Ir(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ja(this.store[a[c]])),delete this.store[a[c]]);return b};
Gr.prototype.getSequenceCount=function(a){a=Ir(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=(null==(d=this.store[a[c]])?void 0:d.length)||0}return b};
function Ir(a,b){var c=Hr(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&Hr(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(Jr(b.auth,g[0])){var h=b.isJspb;Jr(void 0===h?"undefined":h?"true":"false",g[1])&&Jr(b.cttAuthInfo,g[2])&&(h=b.tier,h=void 0===h?"undefined":JSON.stringify(h),Jr(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function Jr(a,b){return void 0===a||"undefined"===a?!0:a===b}
Gr.prototype.getSequenceCount=Gr.prototype.getSequenceCount;Gr.prototype.extractMatchingEntries=Gr.prototype.extractMatchingEntries;Gr.prototype.smartExtractMatchingEntries=Gr.prototype.smartExtractMatchingEntries;Gr.prototype.storePayload=Gr.prototype.storePayload;function Hr(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo,void 0===a.tier?"undefined":a.tier].join("/")}
;function Kr(a,b){if(a)return a[b.name]}
;var Lr=U("initial_gel_batch_timeout",2E3),Mr=U("gel_queue_timeout_max_ms",6E4),Nr=Math.pow(2,16)-1,Or=U("gel_min_batch_size",5),Pr=void 0;function Qr(){this.l=this.h=this.i=0;this.j=!1}
var Rr=new Qr,Sr=new Qr,Tr=new Qr,Ur=new Qr,Vr,Wr=!0,Xr=C.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",Xr);var Yr={};function Zr(){var a=E("yt.logging.ims");a||(a=new Gr,D("yt.logging.ims",a));return a}
function $r(a,b){if("log_event"===a.endpoint){var c=as(a),d=bs(a.payload)||"";a:{if(S("enable_web_tiered_gel")){var e=bq[d||""];var f,g,h,k=null==or().resolve(new jr(Ko))?void 0:null==(f=Lo())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.eventLoggingConfig)?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(!1===e.enabled&&!S("web_payload_policy_disabled_killswitch"))return;k=cs(e.tier);if(400===k){ds(a,b);return}}Yr[c]=
!0;e={cttAuthInfo:c,isJspb:!1,tier:k};Zr().storePayload(e,a.payload);es(b,c,e,"gelDebuggingEvent"===d)}}
function es(a,b,c,d){function e(){gs({writeThenSend:!0},S("flush_only_full_queue")?b:void 0,f,c.tier)}
var f=!1;f=void 0===f?!1:f;d=void 0===d?!1:d;a&&(Pr=new a);a=U("tvhtml5_logging_max_batch_ads_fork")||U("web_logging_max_batch")||100;var g=W(),h=hs(f,c.tier),k=h.l;d&&(h.j=!0);d=0;c&&(d=Zr().getSequenceCount(c));1E3<=d?e():d>=a?Vr||(Vr=is(function(){e();Vr=void 0},0)):10<=g-k&&(js(f,c.tier),h.l=g)}
function ds(a,b){if("log_event"===a.endpoint){var c=as(a),d=new Map;d.set(c,[a.payload]);var e=bs(a.payload)||"";b&&(Pr=new b);return new Ud(function(f,g){Pr&&Pr.isReady()?ks(d,Pr,f,g,{bypassNetworkless:!0},!0,"gelDebuggingEvent"===e):f()})}}
function as(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);Xr[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function gs(a,b,c,d){a=void 0===a?{}:a;c=void 0===c?!1:c;new Ud(function(e,f){var g=hs(c,d),h=g.j;g.j=!1;ls(g.i);ls(g.h);g.h=0;Pr&&Pr.isReady()?void 0===d&&S("enable_web_tiered_gel")?ms(e,f,a,b,c,300,h):ms(e,f,a,b,c,d,h):(js(c,d),e())})}
function ms(a,b,c,d,e,f,g){var h=Pr;c=void 0===c?{}:c;e=void 0===e?!1:e;f=void 0===f?200:f;g=void 0===g?!1:g;var k=new Map;var l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(void 0!==d)f=S("enable_web_tiered_gel")?Zr().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):Zr().extractMatchingEntries(e),k.set(d,f);else for(d=v(Object.keys(Yr)),l=d.next();!l.done;l=d.next())l=l.value,e=S("enable_web_tiered_gel")?Zr().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):Zr().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),0<e.length&&k.set(l,e),(S("web_fp_via_jspb_and_json")&&c.writeThenSend||!S("web_fp_via_jspb_and_json"))&&delete Yr[l];ks(k,h,a,b,c,!1,g)}
function js(a,b){function c(){gs({writeThenSend:!0},void 0,a,b)}
a=void 0===a?!1:a;b=void 0===b?200:b;var d=hs(a,b),e=d===Ur||d===Tr?5E3:Mr;S("web_gel_timeout_cap")&&!d.h&&(e=is(function(){c()},e),d.h=e);
ls(d.i);e=R("LOGGING_BATCH_TIMEOUT",U("web_gel_debounce_ms",1E4));S("shorten_initial_gel_batch_timeout")&&Wr&&(e=Lr);e=is(function(){0<U("gel_min_batch_size")?Zr().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=Or&&c():c()},e);
d.i=e}
function ks(a,b,c,d,e,f,g){e=void 0===e?{}:e;var h=Math.round(W()),k=a.size,l=(void 0===g?0:g)&&S("vss_through_gel_video_stats")?"video_stats":"log_event";a=v(a);var n=a.next();for(g={};!n.done;g={jc:g.jc,batchRequest:g.batchRequest,dangerousLogToVisitorSession:g.dangerousLogToVisitorSession,lc:g.lc,kc:g.kc},n=a.next()){var p=v(n.value);n=p.next().value;p=p.next().value;g.batchRequest=tb({context:Ro(b.config_||Qo())});if(!Oa(p)&&!S("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=
p;(p=Xr[n])&&ns(g.batchRequest,n,p);delete Xr[n];g.dangerousLogToVisitorSession="visitorOnlyApprovedKey"===n;ps(g.batchRequest,h,g.dangerousLogToVisitorSession);S("always_send_and_write")&&(e.writeThenSend=!1);g.lc=function(t){S("start_client_gcf")&&pi.oa(function(){return A(function(r){return r.yield(qs(t),0)})});
k--;k||c()};
g.jc=0;g.kc=function(t){return function(){t.jc++;if(e.bypassNetworkless&&1===t.jc)try{Gp(b,l,t.batchRequest,rs({writeThenSend:!0},t.dangerousLogToVisitorSession,t.lc,t.kc,f)),Wr=!1}catch(r){Rk(r),d()}k--;k||c()}}(g);
try{Gp(b,l,g.batchRequest,rs(e,g.dangerousLogToVisitorSession,g.lc,g.kc,f)),Wr=!1}catch(t){Rk(t),d()}}}
function rs(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,Nf:!!e,headers:{},postBodyFormat:"",postBody:"",compress:S("compress_gel")||S("compress_gel_lr")};ss()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));return a}
function ps(a,b,c){ss()||(a.requestTimeMs=String(b));S("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=R("EVENT_ID"))&&((c=R("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*Nr/2)),c++,c>Nr&&(c=1),Mk("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function ns(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function ss(){return S("use_request_time_ms_header")||S("lr_use_request_time_ms_header")}
function is(a,b){return S("transport_use_scheduler")?S("logging_avoid_blocking_during_navigation")||S("lr_logging_avoid_blocking_during_navigation")?jm(function(){if("none"===Fr().currentState)a();else{var c={};Fr().install((c.none={callback:a},c))}},b):jm(a,b):il(a,b)}
function ls(a){S("transport_use_scheduler")?pi.qa(a):window.clearTimeout(a)}
function qs(a){var b,c,d,e,f,g,h,k,l,n;return A(function(p){return 1==p.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=Kr(d,rk),g=null==(f=d)?void 0:f.hotHashData,h=Kr(d,qk),l=null==(k=d)?void 0:k.coldHashData,(n=or().resolve(new jr(Ko)))?g?e?p.yield(Mo(n,g,e),2):p.yield(Mo(n,g),2):p.v(2):p.return()):l?h?p.yield(No(n,l,h),0):p.yield(No(n,l),0):p.v(0)})}
function hs(a,b){b=void 0===b?200:b;return a?300===b?Ur:Sr:300===b?Tr:Rr}
function bs(a){a=Object.keys(a);a=v(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,bq[b])return b}
function cs(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var ts=C.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",ts);
function us(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||W());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=Xq();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!S("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,ts[b]=b in ts?ts[b]+1:0,a.sequence={index:ts[b],groupKey:b},d.endOfSequence&&delete ts[d.sequenceGroup]);(d.sendIsolatedPayload?ds:$r)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function $m(a,b,c){c=void 0===c?{}:c;var d=Dq;R("ytLoggingEventsDefaultDisabled",!1)&&Dq===Dq&&(d=null);S("web_all_payloads_via_jspb")&&!c.timestamp&&(c.lact=Xq(),c.timestamp=W());us(a,b,d,c)}
;D("ytLoggingGelSequenceIdObj_",C.ytLoggingGelSequenceIdObj_||{});var vs=new Set,ws=0,xs=0,ys=0,zs=[],As=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Zm(a){Bs(a)}
function Cs(a){Bs(a,"WARNING")}
function Ds(a){a instanceof Error?Bs(a):(a=Pa(a)?JSON.stringify(a):String(a),a=new V(a),a.name="RejectedPromiseError",Cs(a))}
function Bs(a,b,c,d,e,f,g,h){f=void 0===f?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),S("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(5<=ws))){d=zs;var k=Dc(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var n=l.split("\n");n.shift();l=n.join("\n")}n=k.lineNumber||"Not available";k=k.fileName||"Not available";var p=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var t=0;t<a.args.length&&!(p=Hl(a.args[t],"params."+t,c,p),
500<=p);t++);else if(a.hasOwnProperty("params")&&a.params){var r=a.params;if("object"===typeof a.params)for(t in r){if(r[t]){var x="params."+t,y=Jl(r[t]);c[x]=y;p+=x.length+y.length;if(500<p)break}}else c.params=Jl(r)}if(d.length)for(t=0;t<d.length&&!(p=Hl(d[t],"params.context."+t,c,p),500<=p);t++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);t={message:e,name:f,lineNumber:n,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(t.lineNumber=
t.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=Dl();c=v(a.Ua);for(d=c.next();!d.done;d=c.next())if(d=d.value,t.message&&t.message.match(d.Yf)){a=d.weight;break a}a=v(a.Ra);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(t)){a=c.weight;break a}a=1}t.sampleWeight=a;a=v(yl);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.mc[t.name])for(e=v(c.mc[t.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=t.message.match(f.regexp)){t.params["params.error.original"]=d[0];e=f.groups;f={};
for(n=0;n<e.length;n++)f[e[n]]=d[n+1],t.params["params.error."+e[n]]=d[n+1];t.message=c.Jc(f);break}t.params||(t.params={});a=Dl();t.params["params.errorServiceSignature"]="msg="+a.Ua.length+"&cb="+a.Ra.length;t.params["params.serviceWorker"]="false";C.document&&C.document.querySelectorAll&&(t.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));zb("sample").constructor!==yb&&(t.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(t);
if(0!==t.sampleWeight&&!vs.has(t.message)){if(g&&S("web_enable_error_204"))Es(void 0===b?"ERROR":b,t);else{b=void 0===b?"ERROR":b;"ERROR"===b?(El.Za("handleError",t),S("record_app_crashed_web")&&0===ys&&1===t.sampleWeight&&(ys++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},S("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:t.message}}}}),$m("appCrashed",g)),xs++):"WARNING"===b&&El.Za("handleWarning",t);if(S("kevlar_gel_error_routing")){g=b;h=void 0===
h?{}:h;b:{a=v(As);for(c=a.next();!c.done;c=a.next())if(fn(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:t.stack};t.fileName&&(c.filename=t.fileName);a=t.lineNumber&&t.lineNumber.split?t.lineNumber.split(":"):[];0!==a.length&&(1!==a.length||isNaN(Number(a[0]))?2!==a.length||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:t.message,errorClassName:t.name,sampleWeight:t.sampleWeight};
"ERROR"===g?a.level="ERROR_LEVEL_ERROR":"WARNING"===g&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];R("FEXP_EXPERIMENTS")&&(h.experimentIds=R("FEXP_EXPERIMENTS"));e=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Nk("web_disable_gel_stp_ecatcher_killswitch")&&e)for(f=v(Object.keys(e)),d=f.next();!d.done;d=f.next())d=d.value,h.kvPairs.push({key:d,value:String(e[d])});if(e=t.params)for(f=v(Object.keys(e)),d=f.next();!d.done;d=f.next())d=
d.value,h.kvPairs.push({key:"client."+d,value:String(e[d])});d=R("SERVER_NAME");e=R("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&($m("clientError",h),("ERROR"===g||S("errors_flush_gel_always_killswitch"))&&gs(void 0,void 0,!1))}S("suppress_error_204_logging")||Es(b,t)}try{vs.add(t.message)}catch(z){}ws++}}}
function Es(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:R("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=v(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=v(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=R("SERVER_NAME");b=R("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}pl(R("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function Fs(){this.register=new Map}
function Gs(a){a=v(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.ag("ABORTED")}
Fs.prototype.clear=function(){Gs(this);this.register.clear()};
var Hs=new Fs;var Is=Date.now().toString();
function Js(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Is)for(a=1,b=0;b<Is.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Is.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Ks,Ls=C.ytLoggingDocDocumentNonce_;Ls||(Ls=Js(),D("ytLoggingDocDocumentNonce_",Ls));Ks=Ls;function Ms(a){this.h=a}
m=Ms.prototype;m.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
m.getAsJspb=function(){var a=new yk;void 0!==this.h.trackingParams?K(a,1,hf(this.h.trackingParams,!0)):(void 0!==this.h.veType&&K(a,2,sf(this.h.veType)),void 0!==this.h.veCounter&&K(a,6,sf(this.h.veCounter)),void 0!==this.h.elementIndex&&K(a,3,sf(this.h.elementIndex)),this.h.isCounterfactual&&K(a,5,pf(!0)));if(void 0!==this.h.dataElement){var b=this.h.dataElement.getAsJspb();Yf(a,yk,7,b)}void 0!==this.h.youtubeData&&Yf(a,sk,8,this.h.jspbYoutubeData);return a};
m.toString=function(){return JSON.stringify(this.getAsJson())};
m.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
m.getLoggingDirectives=function(){return this.h.loggingDirectives};function Ns(a){return R("client-screen-nonce-store",{})[void 0===a?0:a]}
function Os(a,b){b=void 0===b?0:b;var c=R("client-screen-nonce-store");c||(c={},Mk("client-screen-nonce-store",c));c[b]=a}
function Ps(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Qs(a){return R(Ps(void 0===a?0:a))}
D("yt_logging_screen.getRootVeType",Qs);function Rs(){var a=R("csn-to-ctt-auth-info");a||(a={},Mk("csn-to-ctt-auth-info",a));return a}
function Ss(){return Object.values(R("client-screen-nonce-store",{})).filter(function(a){return void 0!==a})}
function Ts(a){a=Ns(void 0===a?0:a);if(!a&&!R("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
D("yt_logging_screen.getCurrentCsn",Ts);function Us(a,b,c){var d=Rs();(c=Ts(c))&&delete d[c];b&&(d[a]=b)}
function Vs(a){return Rs()[a]}
D("yt_logging_screen.getCttAuthInfo",Vs);D("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=void 0===c?0:c;if(a!==Ns(c)||b!==R(Ps(c)))if(Us(a,d,c),Os(a,c),Mk(Ps(c),b),b=function(){setTimeout(function(){a&&$m("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:Ks,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});var Ws=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};D("yt.msgs_",Ws);function Xs(a){Hk(Ws,arguments)}
;function Ys(){var a=sb(Zs),b;return(new Ud(function(c,d){a.onSuccess=function(e){hl(e)?c(new $s(e)):d(new at("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new at("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new at("Request timed out","net.timeout",e))};
b=pl("//googleads.g.doubleclick.net/pagead/id",a)})).sc(function(c){c instanceof ae&&b.abort();
return Zd(c)})}
function at(a,b,c){$a.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
w(at,$a);function $s(a){this.xhr=a}
;function bt(){this.h=0;this.value_=null}
bt.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.value_))&&"function"===typeof a.then?a:ct(a):2===this.h&&b?(a=b.call(c,this.value_))&&"function"===typeof a.then?a:dt(a):this};
bt.prototype.getValue=function(){return this.value_};
bt.prototype.isRejected=function(){return 2==this.h};
bt.prototype.$goog_Thenable=!0;function dt(a){var b=new bt;a=void 0===a?null:a;b.h=2;b.value_=void 0===a?null:a;return b}
function ct(a){var b=new bt;a=void 0===a?null:a;b.h=1;b.value_=void 0===a?null:a;return b}
;function et(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:bl(a)?"same-origin":"cors",credentials:bl(a)?"same-origin":"include"};b={};for(var d=v(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function ft(){return wg()||(ze||Ae)&&fn("applewebkit")&&!fn("version")&&(!fn("safari")||fn("gsa/"))||Rc&&fn("version/")?!0:R("EOM_VISITOR_DATA")?!1:!0}
;function gt(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in wk)if(wk[d]==c.embeddedPlayerMode){b=wk[d];break b}}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function ht(a){$a.call(this,a.message||a.description||a.name);this.isMissing=a instanceof jt;this.isTimeout=a instanceof at&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof ae}
w(ht,$a);ht.prototype.name="BiscottiError";function jt(){$a.call(this,"Biscotti ID is missing from server")}
w(jt,$a);jt.prototype.name="BiscottiMissingError";var Zs={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},kt=null;function lt(){if(S("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!ft())return Error("User has not consented - not fetching biscotti id.");var a=R("PLAYER_VARS",{});if("1"==qb(a))return Error("Biscotti ID is not available in private embed mode");if(gt(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Fk(){var a=lt();if(void 0!==a)return Zd(a);kt||(kt=Ys().then(mt).sc(function(b){return nt(2,b)}));
return kt}
function mt(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new jt;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new jt;a=a.id;Gk(a);kt=ct(a);ot(18E5,2);return a}
function nt(a,b){b=new ht(b);Gk("");kt=dt(b);0<a&&ot(12E4,a-1);throw b;}
function ot(a,b){il(function(){Ys().then(mt,function(c){return nt(b,c)}).sc(bb)},a)}
function pt(){try{var a=E("yt.ads.biscotti.getId_");return a?a():Fk()}catch(b){return Zd(b)}}
;function qt(a){if("1"!=qb(R("PLAYER_VARS",{}))){a&&Ek();try{pt().then(function(){},function(){}),il(qt,18E5)}catch(b){Rk(b)}}}
;function rt(){var a=Xl(),b=$l(119),c=1<window.devicePixelRatio;if(document.body&&zi(document.body,"exp-invert-logo"))if(c&&!zi(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!zi(d,"inverted-hdpi")){var e=xi(d);yi(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&zi(document.body,"inverted-hdpi")&&Ai();if(b!=c){b="f"+(Math.floor(119/31)+1);d=am(b)||0;d=c?d|67108864:d&-67108865;0===d?delete Ul[b]:(c=d.toString(16),Ul[b]=c.toString());
c=!0;S("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in Ul)Ul.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(Ul[f])));var f=d.join("&");Ql(b,f,63072E3,a.i,c)}}
;var st=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function tt(){var a=void 0===a?window.location.href:a;if(S("kevlar_disable_theme_param"))return null;bc(cc(5,a));try{var b=$k(a).theme;return st.get(b)||null}catch(c){}return null}
;function ut(){this.h={};if(this.i=Tl()){var a=Rl("CONSISTENCY");a&&vt(this,{encryptedTokenJarContents:a})}}
ut.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.Oa.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=v(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];vt(this,a)}};
function vt(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&Ql("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var wt=window.location.hostname.split(".").slice(-2).join(".");function xt(){var a=R("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===R("INNERTUBE_CLIENT_NAME")&&(this.h=zt(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var At;function Bt(){At=E("yt.clientLocationService.instance");At||(At=new xt,D("yt.clientLocationService.instance",At));return At}
m=xt.prototype;m.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
m.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===R("INNERTUBE_CLIENT_NAME")?(this.h=zt(this))&&this.h.set("yt-location-playability-token",a,15552E3):Ql("YT_CL",JSON.stringify({loctok:a}),15552E3,wt,!0))};
function zt(a){return void 0===a.h?new Rm("yt-client-location"):a.h}
m.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=zt(this))&&this.h.remove("yt-location-playability-token"):Sl("YT_CL")};
m.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===R("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
m.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
m.createLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);return b};function Ct(a,b){var c,d=null==(c=Kr(a,vk))?void 0:c.signal;if(d&&b.Ub&&(c=b.Ub[d]))return c();var e;if((c=null==(e=Kr(a,tk))?void 0:e.request)&&b.Wd&&(e=b.Wd[c]))return e();for(var f in a)if(b.ed[f]&&(a=b.ed[f]))return a()}
;function Dt(a){return function(){return new a}}
;var Et={},Ft=(Et.WEB_UNPLUGGED="^unplugged/",Et.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Et.WEB_UNPLUGGED_OPS="^unplugged/",Et.WEB_UNPLUGGED_PUBLIC="^unplugged/",Et.WEB_CREATOR="^creator/",Et.WEB_KIDS="^kids/",Et.WEB_EXPERIMENTS="^experiments/",Et.WEB_MUSIC="^music/",Et.WEB_REMIX="^music/",Et.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Et.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Et);
function Gt(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Ft[b];if(c){var d=new RegExp(c),e=v(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Ft).forEach(function(g){var h=v(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=v(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Ht(){}
Ht.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Nl:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=R("INNERTUBE_CONTEXT");if(g){g=tb(g);S("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=R("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;Xl();var l="USER_INTERFACE_THEME_LIGHT";$l(165)?l="USER_INTERFACE_THEME_DARK":$l(174)?l="USER_INTERFACE_THEME_LIGHT":!S("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");k=k?l:tt()||l;h.userInterfaceTheme=k;if(!f){if(k=em())h.connectionType=
k;S("web_log_effective_connection_type")&&(k=fm())&&(g.client.effectiveConnectionType=k)}var n;if(S("web_log_memory_total_kbytes")&&(null==(n=C.navigator)?0:n.deviceMemory)){var p;n=null==(p=C.navigator)?void 0:p.deviceMemory;g.client.memoryTotalKbytes=""+1E6*n}S("web_gcf_hashes_innertube")&&(k=Oo())&&(p=k.coldConfigData,n=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},g.client.configInfo.coldConfigData=p,g.client.configInfo.coldHashData=n,g.client.configInfo.hotHashData=
k);p=$k(C.location.href);!S("web_populate_internal_geo_killswitch")&&p.internalcountrycode&&(h.internalGeo=p.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:C.location.href},S("kevlar_woffle")&&Ol.h&&(p=Ol.h,h.mainAppWebInfo.pwaInstallabilityStatus=!p.h&&p.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=Pl(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):
"TVHTML5"===h.clientName&&(!S("web_lr_app_quality_killswitch")&&(p=R("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:p})),p=R("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:p}));if(!S("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var t=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(T){}t=void 0}t&&(h.timeZone=t)}(t=R("EXPERIMENTS_TOKEN",""))?h.experimentsToken=
t:delete h.experimentsToken;t=el();ut.h||(ut.h=new ut);h=ut.h.h;p=[];n=0;for(var r in h)p[n++]=h[r];g.request=Object.assign({},g.request,{internalExperimentFlags:t,consistencyTokenJars:p});!S("web_prequest_context_killswitch")&&(r=R("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=r);t=Xl();r=$l(58);t=t.get("gsml","");g.user=Object.assign({},g.user);r&&(g.user.enableSafetyMode=r);t&&(g.user.lockedSafetyMode=!0);S("warm_op_csn_cleanup")?e&&(f=Ts())&&(g.clientScreenNonce=f):
!f&&(f=Ts())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=E("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Bt().setLocationOnInnerTubeContext(g);try{var x=cl(),y=x.bid;delete x.bid;g.adSignalsInfo={params:[],bid:y};var z=v(Object.entries(x));for(var I=z.next();!I.done;I=z.next()){var J=v(I.value),M=J.next().value,H=J.next().value;x=M;y=H;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:x,value:""+y})}}catch(T){Bs(T)}z=g}else Bs(Error("Error: No InnerTubeContext shell provided in ytconfig.")),
z={};z={context:z};if(I=this.h(a)){this.i(z,I,b);var O;b="/youtubei/v1/"+Gt(this.j());(I=null==(O=Kr(a.commandMetadata,uk))?void 0:O.apiUrl)&&(b=I);O=b;(b=R("INNERTUBE_HOST_OVERRIDE"))&&(O=String(b)+String(ec(O)));b={};b.key=R("INNERTUBE_API_KEY");S("json_condensed_response")&&(b.prettyPrint="false");O=al(O,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:O,ib:et(O),Oa:z,config:a};a.config.Wb?a.config.Wb.identity=c:a.config.Wb={identity:c};return a}Bs(new V("Error: Failed to create Request from Command.",
a))};
da.Object.defineProperties(Ht.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function It(){}
w(It,Ht);It.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",ib:et("/getDatasyncIdsEndpoint","GET"),Oa:{}}};
It.prototype.j=function(){return[]};
It.prototype.h=function(){};
It.prototype.i=function(){};var Jt={},Kt=(Jt.GET_DATASYNC_IDS=Dt(It),Jt);var Lt="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function Mt(a,b){var c=void 0===c?!0:c;var d=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=dc(window.location.href);e&&d.push(e);e=dc(a);if(0<=db(d,e)||!e&&0==a.lastIndexOf("/",0))if(d=document.createElement("a"),Jh(d,a),a=d.href)if(a=ec(a),a=fc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Ts()},b)),f){var f=parseInt(f,10);isFinite(f)&&0<f&&Nt(a,b,f)}else Nt(a,b)}
function Nt(a,b,c){a=Ot(a);b=b?lc(b):"";c=c||5;ft()&&Ql(a,b,c)}
function Ot(a){for(var b=v(Lt),c=b.next();!c.done;c=b.next())a=sc(a,c.value);return"ST-"+$b(a).toString(36)}
;function Pt(){try{return!!self.localStorage}catch(a){return!1}}
;function Qt(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function Rt(a){if(Pt()){var b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Qt(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function St(){if(!Pt())return!1;var a=hm(),b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next())if(c=Qt(c.value),void 0!==c&&c!==a)return!0;return!1}
;function Tt(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return S("copy_login_info_to_st_cookie")&&("WEB"===R("INNERTUBE_CLIENT_NAME")||"WEB_CREATOR"===R("INNERTUBE_CLIENT_NAME"))&&a}
function Ut(a){if(R("LOGGED_IN",!0)&&Tt()){var b=R("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=dc(window.location.href);c&&b.push(c);c=dc(a);0<=db(b,c)||!c&&0==a.lastIndexOf("/",0)?(b=ec(a),(b=fc(b))?(b=Ot(b),b=(b=Rl(b)||null)?Zk(b):{}):b=null):b=null;null==b&&(b={});c=b;var d=void 0;Tt()?(d||(d=R("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&Mt(a,b)}}
;function Vt(a){var b=B.apply(1,arguments);if(!Wt(a)||b.some(function(d){return!Wt(d)}))throw Error("Only objects may be merged.");
b=v(b);for(var c=b.next();!c.done;c=b.next())Xt(a,c.value);return a}
function Xt(a,b){for(var c in b)if(Wt(b[c])){if(c in a&&!Wt(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Xt(a[c],b[c])}else if(Yt(b[c])){if(c in a&&!Yt(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Zt(a[c],b[c])}else a[c]=b[c];return a}
function Zt(a,b){b=v(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Wt(c)?a.push(Xt({},c)):Yt(c)?a.push(Zt([],c)):a.push(c);return a}
function Wt(a){return"object"===typeof a&&!Array.isArray(a)}
function Yt(a){return"object"===typeof a&&Array.isArray(a)}
;function $t(a){var b;(b=E("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},D("ytcsi."+(a||"")+"data_",b));return b}
function au(){var a=$t();a.info||(a.info={});return a.info}
function bu(a){a=$t(a);a.metadata||(a.metadata={});return a.metadata}
function cu(a){a=$t(a);a.tick||(a.tick={});return a.tick}
function du(a){a=$t(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function eu(a){a=du(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function fu(a){var b=$t(a).nonce;b||(b=Js(),$t(a).nonce=b);return b}
;function gu(){var a=E("ytcsi.debug");a||(a=[],D("ytcsi.debug",a),D("ytcsi.reference",{}));return a}
function hu(a){a=a||"";var b=E("ytcsi.reference");b||(gu(),b=E("ytcsi.reference"));if(b[a])return b[a];var c=gu(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var X={},iu=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
X["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",X["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",X["asset.composition_policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",X["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",X["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",X["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",X["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",X["asset.ownership"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",X["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",X["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",X["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",X["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",X["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",X["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",X["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",
X["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",X["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",
X["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",X["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]=
"LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",
X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.home="LATENCY_ACTION_HOME",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.onboarding="LATENCY_ACTION_ONBOARDING",X.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",
X["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",X["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",X["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",X["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",X["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",X["owner.bulk"]="LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",X["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",X["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",X["owner.channels"]=
"LATENCY_ACTION_CREATOR_CMS_CHANNELS",X["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",X["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",X["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",X["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",X["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",X["owner.pitch_music"]=
"LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",X["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",X["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",X["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",X["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",
X["playlist.videos"]="LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",X.search_ui="LATENCY_ACTION_SEARCH_UI",
X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]=
"LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",
X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",X["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant=
"LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",X),Y={},ju=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an="adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p=
"httpProtocol",Y.t="transportProtocol",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav=
"kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.pnt="performanceNavigationTiming",Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",
Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs="tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",
Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID=
"requestIds",Y),ku="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),lu={},mu=(lu.ccs="CANARY_STATE_",lu.mver="MEASUREMENT_VERSION_",lu.pis="PLAYER_INITIALIZED_STATE_",lu.yt_pt="LATENCY_PLAYER_",lu.pa="LATENCY_ACTION_",
lu.ctop="TOP_ENTITY_TYPE_",lu.yt_vst="VIDEO_STREAM_TYPE_",lu),nu="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function ou(a,b,c){c=du(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in ju){c=ju[a];0<=db(ku,c)&&(b=!!b);a in mu&&"string"===typeof b&&(b=mu[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Vt({},d)}0<=db(nu,a)||Cs(new V("Unknown label logged with GEL CSI",a))}
;function pu(a,b){To.call(this,1,arguments);this.timer=b}
w(pu,To);var qu=new Uo("aft-recorded",pu);var ru=C.ytLoggingLatencyUsageStats_||{};D("ytLoggingLatencyUsageStats_",ru);function su(){this.h=0}
function tu(){su.h||(su.h=new su);return su.h}
su.prototype.tick=function(a,b,c,d){uu(this,"tick_"+a+"_"+b)||$m("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
su.prototype.info=function(a,b,c){var d=Object.keys(a).join("");uu(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,$m("latencyActionInfo",a,{cttAuthInfo:c}))};
su.prototype.jspbInfo=function(){};
su.prototype.span=function(a,b,c){var d=Object.keys(a).join("");uu(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,$m("latencyActionSpan",a,{cttAuthInfo:c}))};
function uu(a,b){ru[b]=ru[b]||{count:0};var c=ru[b];c.count++;c.time=W();a.h||(a.h=jm(function(){var d=W(),e;for(e in ru)ru[e]&&6E4<d-ru[e].time&&delete ru[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new V("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Cs(c)),!0):!1}
;var vu=window;function wu(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function xu(){var a;if(S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==Z?void 0:null==(a=Z.getEntriesByType)?void 0:null==(b=a.call(Z,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=yu(e.requestStart),e.responseEnd=yu(e.responseEnd),e.redirectStart=yu(e.redirectStart),e.redirectEnd=yu(e.redirectEnd),e.domainLookupEnd=yu(e.domainLookupEnd),e.connectStart=yu(e.connectStart),e.connectEnd=
yu(e.connectEnd),e.responseStart=yu(e.responseStart),e.secureConnectionStart=yu(e.secureConnectionStart),e.domainLookupStart=yu(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Z.timing}else a=Z.timing;return a}
function yu(a){return Math.round(zu()+a)}
function zu(){return(S("csi_use_time_origin")||S("csi_use_time_origin_tvhtml5"))&&Z.timeOrigin?Math.floor(Z.timeOrigin):Z.timing.navigationStart}
var Z=vu.performance||vu.mozPerformance||vu.msPerformance||vu.webkitPerformance||new wu;var Au=!1,Bu={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Va(Z.clearResourceTimings||Z.webkitClearResourceTimings||Z.mozClearResourceTimings||Z.msClearResourceTimings||Z.oClearResourceTimings||bb,Z);function Cu(a,b,c){if(null!==b){if("yt_lt"===a){var d="string"===typeof b?b:""+b;bu(c).loadType=d}(a=ou(a,b,c))&&Du(a,c)}}
function Du(a,b){if(!S("web_csi_action_sampling_enabled")||!$t(b).actionDisabled){var c=hu(b||"");Vt(c.info,a);a.loadType&&(c=a.loadType,bu(b).loadType=c);Vt(eu(b),a);c=fu(b);b=$t(b).cttAuthInfo;tu().info(a,c,b)}}
function Eu(){var a,b,c,d;return(null!=(d=null==or().resolve(new jr(Ko))?void 0:null==(a=Lo())?void 0:null==(b=a.loggingHotConfig)?void 0:null==(c=b.csiConfig)?void 0:c.debugTicks)?d:[]).map(function(e){return Object.values(e)[0]})}
function Fu(a,b,c){if(!S("web_csi_action_sampling_enabled")||!$t(c).actionDisabled){var d=fu(c),e;if(e=S("web_csi_debug_sample_enabled")&&d)if(!1===$t(c).debugTicksExcludedLogged)e=!1;else if(0===Eu().length)e=$t(c).debugTicksExcludedLogged=!1;else{var f,g,h;e=(null==or().resolve(new jr(Ko))?void 0:null==(f=Lo())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.csiConfig)?void 0:h.debugSampleWeight)||0;if(f=0!==e)b:{f=Eu();if(0<f.length)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=
f=0;g<d.length;g++)f=31*f+d.charCodeAt(g),g<d.length-1&&(f%=Math.pow(2,47));e=0!==f%1E5%e;$t(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Du(f,c));$t(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){b||"_"===a[0]||(e=a,Z.mark&&(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),Z.mark(e)));e=hu(c||"");e.tick[a]=b||W();if(e.callback&&e.callback[a])for(e=v(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=du(c);e.gelTicks&&(e.gelTicks[a]=!0);f=cu(c);e=b||W();S("log_repeated_ytcsi_ticks")?
a in f||(f[a]=e):f[a]=e;f=$t(c).cttAuthInfo;"_start"===a?(a=tu(),uu(a,"baseline_"+d)||$m("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):tu().tick(a,d,b,f);Gu(c);return e}}}
function Hu(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Fq+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Iu(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);Yb()&&a.setAttribute("nonce",Yb());return c?(a=Z.getEntriesByName(c))&&a[0]&&(a=a[0],c=zu(),Fu("rsf_"+b,c+Math.round(a.fetchStart)),Fu("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Ju(){var a=window.location.protocol,b=Z.getEntriesByType("resource");b=fb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=hb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Fu("wffs",yu(b.startTime)),Fu("wffe",yu(b.responseEnd)))}
function Ku(a){var b=Lu("aft",a);if(b)return b;b=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Lu(b[d],a);if(e)return e}return NaN}
function Lu(a,b){if(a=cu(b)[a])return"number"===typeof a?a:a[a.length-1]}
function Gu(a){var b=Lu("_start",a),c=Ku(a);b&&c&&!Au&&(Zo(qu,new pu(Math.round(c-b),a)),Au=!0)}
function Mu(a,b){for(var c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!Mu(a[d],b[d]))return!1;return!0}
function Nu(){if(Z.getEntriesByType){var a=Z.getEntriesByType("paint");if(a=ib(a,function(b){return"first-paint"===b.name}))return yu(a.startTime)}a=Z.timing;
return a.ze?Math.max(0,a.ze):0}
;function Ou(a,b){Qk(function(){hu("").info.actionType=a;b&&Mk("TIMING_AFT_KEYS",b);Mk("TIMING_ACTION",a);var c=R("TIMING_INFO",{}),d;for(d in c)c.hasOwnProperty(d)&&Cu(d,c[d]);c={isNavigation:!0,actionType:iu[R("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};if(d=R("PREVIOUS_ACTION"))c.previousAction=iu[d]||"LATENCY_ACTION_UNKNOWN";if(d=R("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=R("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=Ts())&&"UNDEFINED_CSN"!==d&&(c.clientScreenNonce=d);d=Hu();if(1===d||-1===d)c.isVisible=
!0;bu();au();c.loadType="cold";d=au();var e=xu(),f=zu(),g=R("CSI_START_TIMESTAMP_MILLIS",0);0<g&&!S("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Fu("srt",e.responseStart),1!==d.prerender&&Fu("_start",f,void 0));d=Nu();0<d&&Fu("fpt",d);d=xu();d.isPerformanceNavigationTiming&&Du({performanceNavigationTiming:!0});Fu("nreqs",d.requestStart,void 0);Fu("nress",d.responseStart,void 0);Fu("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(Fu("nrs",d.redirectStart,void 0),Fu("nre",
d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(Fu("ndnss",d.domainLookupStart,void 0),Fu("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(Fu("ntcps",d.connectStart,void 0),Fu("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=zu()&&0<d.connectEnd-d.secureConnectionStart&&(Fu("nstcps",d.secureConnectionStart,void 0),Fu("ntcpe",d.connectEnd,void 0));Z&&"getEntriesByType"in Z&&Ju();d=[];if(document.querySelector&&Z&&Z.getEntriesByName)for(var h in Bu)Bu.hasOwnProperty(h)&&
(e=Bu[h],Iu(h,e)&&d.push(e));if(0<d.length)for(c.resourceInfo=[],h=v(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Du(c);c=au();h=eu();if("cold"===bu().loadType&&("cold"===c.yt_lt||"cold"===h.loadType)){d=cu();e=du();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if("number"===typeof d[k])Fu(k,Lu(k));else if(S("log_repeated_ytcsi_ticks"))for(f=v(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Fu(k.slice(1),g);k={};d=!1;e=v(Object.keys(c));for(f=e.next();!f.done;f=
e.next())f=f.value,(f=ou(f,c[f]))&&!Mu(eu(),f)&&(Vt(h,f),Vt(k,f),d=!0);d&&Du(k)}D("ytglobal.timingready_",!0);k=R("TIMING_ACTION");E("ytglobal.timingready_")&&k&&Pu()&&Ku()&&Gu()})()}
function Qu(a,b,c,d){Qk(Cu)(a,b,c,d)}
function Ru(a,b,c){return Qk(Fu)(a,b,c)}
function Pu(){return Qk(function(){return"_start"in cu()})()}
function Su(){Qk(function(){var a=fu();requestAnimationFrame(function(){setTimeout(function(){a===fu()&&Ru("ol",void 0,void 0)},0)})})()}
var Tu=window;Tu.ytcsi&&(Tu.ytcsi.info=Qu,Tu.ytcsi.tick=Ru);var Uu="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD".split(" "),Vu=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function Wu(a,b,c,d){this.m=a;this.aa=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Ub||(a.Ub={});a.Ub=Object.assign({},Kt,a.Ub)}
function Xu(a,b,c,d){if(void 0!==Wu.h){if(d=Wu.h,a=[a!==d.m,b!==d.aa,c!==d.l,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new V("InnerTubeTransportService is already initialized",a);
}else Wu.h=new Wu(a,b,c,d)}
function Yu(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Nl:c;var d=Ct(b,a.m);if(!d)return Zd(new V("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?(Ut(e.input),new Ud(function(f){var g,h,k;return A(function(l){if(1==l.h){h="cors"===(null==(g=e.ib)?void 0:g.mode)?"cors":void 0;if(a.l.af){var n=e.config,p;n=null==n?void 0:null==(p=n.Wb)?void 0:p.sessionIndex;p=Ml(0,{sessionIndex:n});k=Object.assign({},Zu(h),p);return l.v(2)}return l.yield($u(e.config,
h),3)}2!=l.h&&(k=l.i);f(av(a,e,k));l.h=0})})):Zd(new V("Error: Failed to build request for command.",b))}
function bv(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.dg)?0:d.hg)&&a.j){d=v(Uu);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function av(a,b,c){var d,e,f,g,h,k,l,n,p,t,r,x,y,z,I,J,M,H,O,T,Fa,ra,ka,la,ma,hc,Qq,Rq,Sq;return A(function(ia){switch(ia.h){case 1:ia.v(2);break;case 3:if((d=ia.i)&&!d.isExpired())return ia.return(Promise.resolve(d.h()));case 2:if(!(null==(e=b)?0:null==(f=e.Oa)?0:f.context)){ia.v(4);break}g=b.Oa.context;ia.v(5);break;case 5:h=v([]),k=h.next();case 7:if(k.done){ia.v(4);break}l=k.value;return ia.yield(l.Zf(g),8);case 8:k=h.next();ia.v(7);break;case 4:if(null==(n=a.i)||!n.eg(b.input,b.Oa)){ia.v(11);
break}return ia.yield(a.i.Wf(b.input,b.Oa),12);case 12:return p=ia.i,S("kevlar_process_local_innertube_responses_killswitch")||bv(a,p,b),ia.return(p);case 11:return(x=null==(r=b.config)?void 0:r.Qa)&&a.h.has(x)&&S("web_memoize_inflight_requests")?t=a.h.get(x):(y=JSON.stringify(b.Oa),J=null!=(I=null==(z=b.ib)?void 0:z.headers)?I:{},b.ib=Object.assign({},b.ib,{headers:Object.assign({},J,c)}),M=Object.assign({},b.ib),"POST"===b.ib.method&&(M=Object.assign({},M,{body:y})),(null==(H=b.config)?0:H.Je)&&
Ru(b.config.Je),O=function(){return a.aa.fetch(b.input,M,b.config)},t=O(),x&&a.h.set(x,t)),ia.yield(t,13);
case 13:if((T=ia.i)&&"error"in T&&(null==(Fa=T)?0:null==(ra=Fa.error)?0:ra.details))for(ka=T.error.details,la=v(ka),ma=la.next();!ma.done;ma=la.next())hc=ma.value,(Qq=hc["@type"])&&-1<Vu.indexOf(Qq)&&(delete hc["@type"],T=hc);x&&a.h.has(x)&&a.h.delete(x);(null==(Rq=b.config)?0:Rq.Ke)&&Ru(b.config.Ke);if(T||null==(Sq=a.i)||!Sq.Of(b.input,b.Oa)){ia.v(14);break}return ia.yield(a.i.Vf(b.input,b.Oa),15);case 15:T=ia.i;case 14:return bv(a,T,b),ia.return(T||void 0)}})}
function $u(a,b){var c,d,e,f;return A(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Wb)?void 0:d.sessionIndex;var h=g.yield;var k=Ml(0,{sessionIndex:e});if(!(k instanceof Ud)){var l=new Ud(bb);Vd(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Zu(b),f)))})}
function Zu(a){var b={"Content-Type":"application/json"};R("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=R("EOM_VISITOR_DATA"):R("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=R("VISITOR_DATA"));R("WEBVIEW_EOM",!1)&&(b["X-Yt-Webview-Eom"]="1");b["X-Youtube-Bootstrap-Logged-In"]=R("LOGGED_IN",!1);R("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=R("DEBUG_SETTINGS_METADATA"));"cors"!==a&&((a=R("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=R("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&
(b["X-Youtube-Client-Version"]=a),(a=R("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=R("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var cv=new ir("INNERTUBE_TRANSPORT_TOKEN");var dv=["share/get_web_player_share_panel"],ev=["feedback"],fv=["notification/modify_channel_preference"],gv=["browse/edit_playlist"],hv=["subscription/subscribe"],iv=["subscription/unsubscribe"];function jv(){}
w(jv,Ht);jv.prototype.j=function(){return hv};
jv.prototype.h=function(a){return Kr(a,Dk)||void 0};
jv.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
da.Object.defineProperties(jv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function kv(){}
w(kv,Ht);kv.prototype.j=function(){return iv};
kv.prototype.h=function(a){return Kr(a,Ck)||void 0};
kv.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
da.Object.defineProperties(kv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function lv(){}
w(lv,Ht);lv.prototype.j=function(){return ev};
lv.prototype.h=function(a){return Kr(a,xk)||void 0};
lv.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
da.Object.defineProperties(lv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function mv(){}
w(mv,Ht);mv.prototype.j=function(){return fv};
mv.prototype.h=function(a){return Kr(a,Bk)||void 0};
mv.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function nv(){}
w(nv,Ht);nv.prototype.j=function(){return gv};
nv.prototype.h=function(a){return Kr(a,Ak)||void 0};
nv.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function ov(){}
w(ov,Ht);ov.prototype.j=function(){return dv};
ov.prototype.h=function(a){return Kr(a,zk)};
ov.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var pv=new ir("NETWORK_SLI_TOKEN");function qv(a){this.h=a}
qv.prototype.fetch=function(a,b){var c=this,d,e,f;return A(function(g){c.h&&(d=bc(cc(5,sc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=b;S("wug_networking_gzip_request")&&(e=zp(b));f=new window.Request(a,e);return S("web_fetch_promise_cleanup_killswitch")?g.return(Promise.resolve(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){Cs(h)}))):g.return(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){Cs(h)}))})};
qv.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Rf(),b=b.then(function(c){Cs(new V("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
qv[hr]=[new jr(pv)];var rv=new ir("NETWORK_MANAGER_TOKEN");var sv;function tv(){var a,b,c;return A(function(d){if(1==d.h)return a=or().resolve(cv),a?d.yield(Yu(a),2):(Cs(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return Cs(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Pf;return d.return(c)}Cs(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var uv=C.caches,vv;function wv(a){var b=a.indexOf(":");return-1===b?{td:a}:{td:a.substring(0,b),datasyncId:a.substring(b+1)}}
function xv(){return A(function(a){if(void 0!==vv)return a.return(vv);vv=new Promise(function(b){var c;return A(function(d){switch(d.h){case 1:return Aa(d,2),d.yield(uv.open("test-only"),4);case 4:return d.yield(uv.delete("test-only"),5);case 5:d.h=3;d.l=0;break;case 2:if(c=Ba(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(vv)})}
function yv(a){var b,c,d,e,f,g,h;A(function(k){if(1==k.h)return k.yield(xv(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return k.yield(uv.keys(),3)}c=k.i;d=v(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=wv(f),h=g.datasyncId,!h||a.includes(h)||b.push(uv.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(n){return n})}))})}
function zv(){var a,b,c,d,e,f,g;return A(function(h){if(1==h.h)return h.yield(xv(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=hm("cache contains other");return h.yield(uv.keys(),3)}b=h.i;c=v(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=wv(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Av(){tv().then(function(a){a&&(po(a),yv(a),Rt(a))})}
function Bv(){var a=new rq;pi.oa(function(){var b,c,d,e;return A(function(f){switch(f.h){case 1:if(S("ytidb_clear_optimizations_killswitch")){f.v(2);break}b=hm("clear");if(b.startsWith("V")&&b.endsWith("||")){var g=[b];po(g);yv(g);Rt(g);return f.return()}c=St();return f.yield(zv(),3);case 3:return d=f.i,f.yield(qo(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.wa()?Av():a.h.add("publicytnetworkstatus-online",Av,!0,void 0,void 0),f.h=0}})})}
;var Oh=fa(["data-"]);function Cv(a){a&&(a.dataset?a.dataset[Dv("loaded")]="true":Nh(a))}
function Ev(a,b){return a?a.dataset?a.dataset[Dv(b)]:a.getAttribute("data-"+b):null}
var Fv={};function Dv(a){return Fv[a]||(Fv[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Gv=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Hv=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Iv(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Gv,""),c=c.replace(Hv,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Jv(a,b,c)}
function Jv(a,b,c){c=void 0===c?null:c;var d=Kv(a),e=document.getElementById(d),f=e&&Ev(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=br(d,b),b=""+Qa(b),Lv[b]=f),g||(e=Mv(a,d,function(){if(!Ev(e,"loaded")){Cv(e);er(d);var h=Wa(fr,d);il(h,0)}},c)))}
function Mv(a,b,c,d){d=void 0===d?null:d;var e=Gd("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Th(e,ok(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Nv(a){a=Kv(a);var b=document.getElementById(a);b&&(fr(a),b.parentNode.removeChild(b))}
function Ov(a,b){a&&b&&(a=""+Qa(b),(a=Lv[a])&&dr(a))}
function Kv(a){var b=document.createElement("a");Jh(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+$b(a)}
var Lv={};var Pv=[],Qv=!1;function Rv(){if(!S("disable_biscotti_fetch_for_ad_blocker_detection")&&!S("disable_biscotti_fetch_entirely_for_all_web_clients")&&ft()){var a=R("PLAYER_VARS",{});if("1"!=qb(a)&&!gt(a)){var b=function(){Qv=!0;"google_ad_status"in window?Mk("DCLKSTAT",1):Mk("DCLKSTAT",2)};
try{Iv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Pv.push(pi.oa(function(){if(!(Qv||"google_ad_status"in window)){try{Ov("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Qv=!0;Mk("DCLKSTAT",3)}},5E3))}}}
function Sv(){var a=Number(R("DCLKSTAT",0));return isNaN(a)?0:a}
;function Tv(a){xr.call(this,void 0===a?"document_active":a);var b=this;this.l=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.la},{from:"document_active",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"flush_logs",action:this.G},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.G},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
w(Tv,xr);Tv.prototype.la=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Tv.prototype.m=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Tv.prototype.G=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Tv.prototype.i=function(){this.h=new Map};function Uv(a){xr.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.G},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.m},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.G},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.G},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.m},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.m},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
S("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
w(Uv,xr);Uv.prototype.i=function(a,b){a(null==b?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Uv.prototype.h=function(a,b){a(null==b?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Uv.prototype.m=function(a,b){a(null==b?void 0:b.event)};
Uv.prototype.G=function(a,b){a(null==b?void 0:b.event)};function Vv(){this.l=new Tv;this.m=new Uv}
Vv.prototype.install=function(){var a=B.apply(0,arguments),b=this;a.forEach(function(c){b.l.install(c)});
a.forEach(function(c){b.m.install(c)})};function Wv(a){To.call(this,1,arguments);this.csn=a}
w(Wv,To);var bp=new Uo("screen-created",Wv),Xv=[],Yv=0,Zv=new Map,$v=new Map,aw=new Map;
function bw(a,b,c,d,e){e=void 0===e?!1:e;for(var f=cw({cttAuthInfo:Vs(b)||void 0},b),g=v(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(ob(k)||!k.trackingParams&&!k.veType)&&Cs(Error("Child VE logged with no data"));if(S("no_client_ve_attach_unless_shown")){var l=dw(h,b);if(k.veType&&!$v.has(l)&&!aw.has(l)&&!e){Zv.set(l,[a,b,c,h]);return}h=dw(c,b);Zv.has(h)?ew(c,b):aw.set(h,!0)}}d=d.filter(function(n){n.csn!==b?(n.csn=b,n=!0):n=!1;return n});
c={csn:b,parentVe:c.getAsJson(),childVes:gb(d,function(n){return n.getAsJson()})};
"UNDEFINED_CSN"===b?fw("visualElementAttached",f,c):a?us("visualElementAttached",c,a,f):$m("visualElementAttached",c,f)}
function fw(a,b,c){Xv.push({De:a,payload:c,Uf:void 0,options:b});Yv||(Yv=cp())}
function dp(a){if(Xv){for(var b=v(Xv),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,$m(c.De,c.payload,c.options));Xv.length=0}Yv=0}
function dw(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function ew(a,b){a=dw(a,b);Zv.has(a)&&(b=Zv.get(a)||[],bw(b[0],b[1],b[2],[b[3]],!0),Zv.delete(a))}
function cw(a,b){S("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function gw(){this.l=[];this.i=new Map;this.h=new Map;this.j=new Set}
gw.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=Ts(void 0===c?0:c)){a=this.client;d=new Ms({trackingParams:d});var e=void 0;if(S("no_client_ve_attach_unless_shown")){var f=dw(d,c);$v.set(f,!0);ew(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=cw({cttAuthInfo:Vs(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);"UNDEFINED_CSN"===c?fw("visualElementGestured",f,d):a?us("visualElementGestured",d,a,f):$m("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
gw.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new Ms({trackingParams:a}),b,void 0===c?0:c)};
gw.prototype.visualElementStateChanged=function(a,b,c){c=void 0===c?0:c;if(0===c&&this.j.has(c))this.l.push([a,b]);else{var d=c;d=void 0===d?0:d;c=Ts(d);a||(a=(a=Qs(void 0===d?0:d))?new Ms({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=cw({cttAuthInfo:Vs(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},"UNDEFINED_CSN"===c?fw("visualElementStateChanged",d,b):a?us("visualElementStateChanged",b,a,d):$m("visualElementStateChanged",b,d))}};
function hw(a,b){if(void 0===b)for(var c=Ss(),d=0;d<c.length;d++)void 0!==c[d]&&hw(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&bw(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function iw(){Vv.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));S("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a))}
w(iw,Vv);iw.prototype.j=function(){$m("finalPayload",{csn:Ts()})};
iw.prototype.h=function(){Gs(Hs)};
iw.prototype.i=function(){var a=hw;gw.h||(gw.h=new gw);a(gw.h)};function jw(){}
function kw(){var a=E("ytglobal.storage_");a||(a=new jw,D("ytglobal.storage_",a));return a}
jw.prototype.estimate=function(){var a,b,c;return A(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(lw()):d.return()})};
function lw(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
D("ytglobal.storageClass_",jw);function Ym(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=U("ytidb_transaction_ended_event_rate_limit_session",.2)}
Ym.prototype.Pb=function(a){this.handleError(a)};
Ym.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":S("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":S("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":mw(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=U("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function mw(a,b){kw().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:nw(null==c?void 0:c.usage),deviceStorageQuotaMbytes:nw(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function nw(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function ow(a,b,c){G.call(this);var d=this;c=c||R("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.i=b||null;this.targetOrigin="*";this.j=c;this.sessionId=null;this.channel="widget";this.D=!!a;this.s=function(e){a:if(!("*"!=d.j&&e.origin!=d.j||d.i&&e.source!=d.i||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.D&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.j=d.targetOrigin=e.origin);d.i=e.source;d.sessionId=f.id;d.h&&(d.h(),d.h=null);break;case "command":d.l&&(!d.m||0<=db(d.m,f.func))&&d.l(f.func,f.args,e.origin)}}};
this.m=this.h=this.l=null;window.addEventListener("message",this.s)}
w(ow,G);ow.prototype.sendMessage=function(a,b){if(b=b||this.i){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Sk(d)}}};
ow.prototype.M=function(){window.removeEventListener("message",this.s);G.prototype.M.call(this)};function pw(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new ow(!!R("WIDGET_ID_ENFORCE")),b=this.Ge.bind(this);a.l=b;a.m=null;this.h.channel="widget";if(a=R("WIDGET_ID"))this.h.sessionId=a}
m=pw.prototype;m.Ge=function(a,b,c){"addEventListener"===a&&b?this.Fc(b[0],c):this.Vc(a,b,c)};
m.Vc=function(){};
m.zc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
m.Fc=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.zc(a,b)),this.j[a]=!0)};
m.addEventListener=function(){};
m.ee=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Cc());this.sendMessage("onReady");eb(this.i,this.Ad,this);this.i=[]};
m.Cc=function(){return null};
function qw(a,b){a.sendMessage("infoDelivery",b)}
m.Ad=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.Ad({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};var rw={},sw=(rw["api.invalidparam"]=2,rw.auth=150,rw["drm.auth"]=150,rw["heartbeat.net"]=150,rw["heartbeat.servererror"]=150,rw["heartbeat.stop"]=150,rw["html5.unsupportedads"]=5,rw["fmt.noneavailable"]=5,rw["fmt.decode"]=5,rw["fmt.unplayable"]=5,rw["html5.missingapi"]=5,rw["html5.unsupportedlive"]=5,rw["drm.unavailable"]=5,rw["mrm.blocked"]=151,rw);var tw=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function uw(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function vw(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=v(tw);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function ww(a,b,c,d){if(Pa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function xw(a){pw.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Se.bind(this));this.addEventListener("onVolumeChange",this.Te.bind(this));this.addEventListener("onApiChange",this.Ne.bind(this));this.addEventListener("onPlaybackQualityChange",this.Pe.bind(this));this.addEventListener("onPlaybackRateChange",this.Qe.bind(this));this.addEventListener("onStateChange",this.Re.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Ue.bind(this))}
w(xw,pw);m=xw.prototype;
m.Vc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&uw(a)){var d=b;if(Pa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=vw(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=vw(e);break;case "loadPlaylist":case "cuePlaylist":e=ww(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);uw(a)&&qw(this,this.Cc())}};
m.Fc=function(a,b){"onReady"===a?this.api.logApiCall(a+" invocation",b):"onError"===a&&this.l&&(this.api.logApiCall(a+" invocation",b,this.errorCode),this.errorCode=void 0);this.api.logApiCall(a+" registration",b);pw.prototype.Fc.call(this,a,b)};
m.zc=function(a,b){var c=this,d=pw.prototype.zc.call(this,a,b);return function(e){"onError"===a?c.api.logApiCall(a+" invocation",b,e):c.api.logApiCall(a+" invocation",b);d(e)}};
m.onReady=function(){var a=this.ee.bind(this);this.h.h=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.errorCode=a?sw[a]||b:b;this.sendMessage("onError",this.errorCode.toString())}};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Cc=function(){if(!this.api)return null;var a=this.api.getApiInterface();jb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Re=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());qw(this,a)};
m.Pe=function(a){qw(this,{playbackQuality:a})};
m.Qe=function(a){qw(this,{playbackRate:a})};
m.Ne=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Te=function(){qw(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Se=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());qw(this,a)};
m.Ue=function(){var a={sphericalProperties:this.api.getSphericalProperties()};qw(this,a)};
m.dispose=function(){pw.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function yw(a){G.call(this);this.h={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.wd,this)}
w(yw,G);m=yw.prototype;m.start=function(){this.started||this.Z()||(this.started=!0,this.connection.jb("RECEIVING"))};
m.jb=function(a,b){this.started&&!this.Z()&&this.connection.jb(a,b)};
m.wd=function(a,b,c){if(this.started&&!this.Z()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=zw(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Aw(a,c))&&this.jb(a,c))}}};
m.addListener=function(a){if(!(a in this.h)){var b=this.Oe.bind(this,a);this.h[a]=b;this.addEventListener(a,b)}};
m.Oe=function(a,b){this.started&&!this.Z()&&this.connection.jb(a,this.Bc(a,b))};
m.Bc=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.h&&(this.removeEventListener(a,this.h[a]),delete this.h[a])};
m.M=function(){this.connection.unsubscribe("command",this.wd,this);this.connection=null;for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);G.prototype.M.call(this)};function Bw(a,b){yw.call(this,b);this.api=a;this.start()}
w(Bw,yw);Bw.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Bw.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function zw(a,b){switch(a){case "loadVideoById":return a=vw(b),[a];case "cueVideoById":return a=vw(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=ww(b),[a];case "cuePlaylist":return a=ww(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Aw(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Bw.prototype.Bc=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return yw.prototype.Bc.call(this,a,b)};
Bw.prototype.M=function(){yw.prototype.M.call(this);delete this.api};function Cw(a){a=void 0===a?!1:a;G.call(this);this.h=new L(a);zc(this,this.h)}
Ya(Cw,G);Cw.prototype.subscribe=function(a,b,c){return this.Z()?0:this.h.subscribe(a,b,c)};
Cw.prototype.unsubscribe=function(a,b,c){return this.Z()?!1:this.h.unsubscribe(a,b,c)};
Cw.prototype.l=function(a,b){this.Z()||this.h.Za.apply(this.h,arguments)};function Dw(a,b,c){Cw.call(this);this.j=a;this.i=b;this.id=c}
w(Dw,Cw);Dw.prototype.jb=function(a,b){this.Z()||this.j.jb(this.i,this.id,a,b)};
Dw.prototype.M=function(){this.i=this.j=null;Cw.prototype.M.call(this)};function Ew(a,b,c){G.call(this);this.h=a;this.origin=c;this.i=Mq(window,"message",this.j.bind(this));this.connection=new Dw(this,a,b);zc(this,this.connection)}
w(Ew,G);Ew.prototype.jb=function(a,b,c,d){this.Z()||a!==this.h||(a={id:b,command:c},d&&(a.data=d),this.h.postMessage(JSON.stringify(a),this.origin))};
Ew.prototype.j=function(a){if(!this.Z()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.Z()||c.l("command",b.command,b.data,a.origin)}}}};
Ew.prototype.M=function(){Nq(this.i);this.h=null;G.prototype.M.call(this)};function Fw(){this.state=1;this.h=null}
m=Fw.prototype;m.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){d=a.interpreterSafeScript.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var f=xb();d=f?f.createScript(d):d;d=new Cb(d,Bb)}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=a.interpreterSafeUrl,zb("From proto message. b/166824318"),e=Gb(e.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());Gw(this,d,e,a.program,b,c)}else Cs(Error("Cannot initialize botguard without program"))};
function Gw(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,Iv(c,function(){window[g]?Hw(a,d,g,e):(a.state=3,Nv(c),Cs(new V("Unable to load Botguard","from "+c)))},f)):b?(f=Gd("SCRIPT"),b instanceof Cb?(b instanceof Cb&&b.constructor===Cb?b=b.h:(Na(b),b="type_error:SafeScript"),f.textContent=b,Sh(f)):f.textContent=b,f.nonce=Yb(),document.head.appendChild(f),document.head.removeChild(f),window[g]?Hw(a,d,g,e):(a.state=4,Cs(new V("Unable to load Botguard from JS")))):Cs(new V("Unable to load VM; no url or JS provided"))}
function Hw(a,b,c,d){a.state=5;try{var e=new Fh({program:b,ke:c,He:S("att_web_record_metrics")});e.Xe.then(function(){a.state=6;d&&d(b)});
a.Qc(e)}catch(f){a.state=7,f instanceof Error&&Cs(f)}}
m.invoke=function(a){a=void 0===a?{}:a;return this.Tc()?this.Jd({gd:a}):null};
m.dispose=function(){this.Qc(null);this.state=8};
m.Tc=function(){return!!this.h};
m.Jd=function(a){return this.h.Dd(a)};
m.Qc=function(a){xc(this.h);this.h=a};function Iw(){var a=E("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function Jw(){Fw.apply(this,arguments)}
w(Jw,Fw);Jw.prototype.Qc=function(a){var b;null==(b=Iw())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Dd.bind(a)},D("yt.abuse.playerAttLoader",b),D("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(D("yt.abuse.playerAttLoader",null),D("yt.abuse.playerAttLoaderRun",null))};
Jw.prototype.Tc=function(){return!!Iw()};
Jw.prototype.Jd=function(a){return Iw().bgvmc(a)};var Kw=new Jw;function Lw(){return Kw.Tc()}
function Mw(a){a=void 0===a?{}:a;return Kw.invoke(a)}
;function Nw(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||sb(b);this.assets=a.assets||{};this.attrs=a.attrs||sb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Nw.prototype.clone=function(){var a=new Nw,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Na(c)?a[b]=sb(c):a[b]=c}return a};var Ow=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Pw(a){a=a||"";if(window.spf){var b=a.match(Ow);spf.style.load(a,b?b[1]:"",void 0)}else Qw(a)}
function Qw(a){var b=Rw(a),c=document.getElementById(b),d=c&&Ev(c,"loaded");d||c&&!d||(c=Sw(a,b,function(){if(!Ev(c,"loaded")){Cv(c);er(b);var e=Wa(fr,b);il(e,0)}}))}
function Sw(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=ok(a);Rh(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Rw(a){var b=Gd("A");Jh(b,new Ib(a,Jb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+$b(a)}
;function Tw(){G.call(this);this.h=[]}
w(Tw,G);Tw.prototype.M=function(){for(;this.h.length;){var a=this.h.pop();a.target.removeEventListener(a.name,a.callback,void 0)}G.prototype.M.call(this)};function Uw(){Tw.apply(this,arguments)}
w(Uw,Tw);function Vw(a,b,c,d,e){G.call(this);var f=this;this.l=b;this.webPlayerContextConfig=d;this.vc=e;this.Ba=!1;this.api={};this.ea=this.s=null;this.S=new L;this.h={};this.Y=this.ma=this.elementId=this.Ja=this.config=null;this.W=!1;this.j=this.D=null;this.na={};this.wc=["onReady"];this.lastError=null;this.nb=NaN;this.R={};this.Od=new Uw(this);this.da=0;this.i=this.m=a;zc(this,this.S);Ww(this);Xw(this);zc(this,this.Od);c?this.da=il(function(){f.loadNewVideoConfig(c)},0):d&&(Yw(this),Zw(this))}
w(Vw,G);m=Vw.prototype;m.getId=function(){return this.l};
m.loadNewVideoConfig=function(a){if(!this.Z()){this.da&&(window.clearTimeout(this.da),this.da=0);var b=a||{};b instanceof Nw||(b=new Nw(b));this.config=b;this.setConfig(a);Zw(this);this.isReady()&&$w(this)}};
function Yw(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.l,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.l:a.config.attrs.id=a.l);var c;(null==(c=a.i)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){this.Ja=a;this.config=ax(a);Yw(this);if(!this.ma){var b;this.ma=bx(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=hi(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=hi(Number(a)||a))};
function $w(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function cx(a){var b=!0,c=dx(a);c&&a.config&&(a=ex(a),b=Ev(c,"version")===a);return b&&!!E("yt.player.Application.create")}
function Zw(a){if(!a.Z()&&!a.W){var b=cx(a);if(b&&"html5"===(dx(a)?"html5":null))a.Y="html5",a.isReady()||fx(a);else if(gx(a),a.Y="html5",b&&a.j&&a.m)a.m.appendChild(a.j),fx(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.D=function(){c=!0;var d=hx(a,"player_bootstrap_method")?E("yt.player.Application.createAlternate")||E("yt.player.Application.create"):E("yt.player.Application.create");var e=a.config?ax(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.vc);fx(a)};
a.W=!0;b?a.D():(Iv(ex(a),a.D),(b=ix(a))&&Pw(b),jx(a)&&!c&&D("yt.player.Application.create",null))}}}
function dx(a){var b=Fd(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function fx(a){if(!a.Z()){var b=dx(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.W=!1;if(!hx(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}kx(a)}else a.nb=il(function(){fx(a)},50)}}
function kx(a){Ww(a);a.Ba=!0;var b=dx(a);if(b){a.s=lx(a,b,"addEventListener");a.ea=lx(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=lx(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.s&&a.s(g,a.h[g]);$w(a);a.ma&&a.ma(a.api);a.S.Za("onReady",a.api)}
function lx(a,b,c){var d=b[c];return function(){var e=B.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Cs(new V("PlayerProxy error in method call",{error:f,method:c,playerId:a.l})))}}}
function Ww(a){a.Ba=!1;if(a.ea)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ea(b,a.h[b]);for(var c in a.R)a.R.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.R={};a.s=null;a.ea=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ja};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ba};
function Xw(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){er("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){er("WATCH_LATER_VIDEO_REMOVED",b)})}
m.addEventListener=function(a,b){var c=this,d=bx(this,b);d&&(0<=db(this.wc,a)||this.h[a]||(b=mx(this,a),this.s&&this.s(a,b)),this.S.subscribe(a,d),"onReady"===a&&this.isReady()&&il(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.Z()||(b=bx(this,b))&&this.S.unsubscribe(a,b)};
function bx(a,b){var c=b;if("string"===typeof b){if(a.na[b])return a.na[b];c=function(){var d=B.apply(0,arguments),e=E(b);if(e)try{e.apply(C,d)}catch(f){Bs(new V("PlayerProxy error when executing callback",{error:f}))}};
a.na[b]=c}return c?c:null}
function mx(a,b){var c="ytPlayer"+b+a.l;a.h[b]=c;C[c]=function(d){var e=il(function(){if(!a.Z()){try{a.S.Za(b,null!=d?d:void 0)}catch(h){Cs(new V("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.l,data:d}))}var f=a.R,g=String(e);g in f&&delete f[g]}},0);
pb(a.R,String(e))};
return c}
m.getPlayerType=function(){return this.Y||(dx(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function gx(a){a.cancel();Ww(a);a.Y=null;a.config&&(a.config.loaded=!1);var b=dx(a);b&&(cx(a)||!jx(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.D&&Ov(ex(this),this.D);window.clearTimeout(this.nb);this.W=!1};
m.M=function(){gx(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){Bs(new V("PlayerProxy error during disposal",{error:b}))}this.na=null;for(var a in this.h)this.h.hasOwnProperty(a)&&(C[this.h[a]]=null);this.Ja=this.config=this.api=null;delete this.m;delete this.i;G.prototype.M.call(this)};
function jx(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function ex(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function ix(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function hx(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Vk(c||"","&")[b]}
function ax(a){for(var b={},c=v(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?sb(e):e}return b}
;var nx={},ox="player_uid_"+(1E9*Math.random()>>>0);function px(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?Fd(c):c;var e=ox+"_"+Qa(c),f=nx[e];if(f&&d)return qx(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Vw(c,e,a,b,void 0);nx[e]=f;er("player-added",f.api);Ac(f,function(){delete nx[f.getId()]});
return f.api}
function qx(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var rx=null,sx=null,tx=null;function ux(){vx()}
function wx(){vx()}
function vx(){var a=rx.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function xx(){rx&&rx.sendAbandonmentPing&&rx.sendAbandonmentPing();R("PL_ATT")&&Kw.dispose();for(var a=pi,b=0,c=Pv.length;b<c;b++)a.qa(Pv[b]);Pv.length=0;Nv("//static.doubleclick.net/instream/ad_status.js");Qv=!1;Mk("DCLKSTAT",0);yc(tx,sx);rx&&(rx.removeEventListener("onVideoDataChange",ux),rx.destroy())}
;function yx(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));b&&Mt(a,b);if(c)return!1;Ut(a);if((window.ytspf||{}).enabled)spf.navigate(a);else{var e=void 0===e?{}:e;var f=void 0===f?"":f;var g=void 0===g?window:g;a=nc(a,e);Ut(a);f=a+f;var h=void 0===h?ai:h;a:{h=void 0===h?ai:h;for(a=0;a<h.length;++a)if(b=h[a],b instanceof Zh&&b.te(f)){h=new Ib(f,Jb);break a}h=void 0}g=g.location;h=Ih(h||Kb);void 0!==h&&(g.href=h)}return!0}
;D("yt.setConfig",Mk);D("yt.config.set",Mk);D("yt.setMsg",Xs);D("yt.msgs.set",Xs);D("yt.logging.errors.log",Bs);
D("writeEmbed",function(){var a=R("PLAYER_CONFIG");if(!a){var b=R("PLAYER_VARS");b&&(a={args:b})}qt(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Ou("embed",["ol"]);c=R("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=$k(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;(null==(e=a.args)?0:e.autoplay)&&Ou("watch",["pbs","pbu","pbp"]);rx=px(a,c);rx.addEventListener("onVideoDataChange",ux);rx.addEventListener("onReady",wx);a=R("POST_MESSAGE_ID","player");R("ENABLE_JS_API")?tx=new xw(rx):R("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(sx=new Ew(window.parent,a,b),tx=new Bw(rx,sx.connection));Rv();S("ytidb_create_logger_embed_killswitch")||Xm();a={};iw.h||(iw.h=new iw);
iw.h.install((a.flush_logs={callback:function(){gs()}},a));
Cq();S("ytidb_clear_embedded_player")&&pi.oa(function(){var f,g;if(!sv){var h=or(),k={Nc:rv,Hd:qv};h.h.set(k.Nc,k);k={ed:{feedbackEndpoint:Dt(lv),modifyChannelNotificationPreferenceEndpoint:Dt(mv),playlistEditEndpoint:Dt(nv),subscribeEndpoint:Dt(jv),unsubscribeEndpoint:Dt(kv),webPlayerShareEntityServiceEndpoint:Dt(ov)}};var l=Bt(),n={};l&&(n.client_location=l);void 0===f&&(f=Ll());void 0===g&&(g=h.resolve(rv));Xu(k,g,f,n);f={Nc:cv,Id:Wu.h};h.h.set(f.Nc,f);sv=h.resolve(cv)}Bv()})});
var zx=Qk(function(){Su();rt()}),Ax=Qk(function(a){a.persisted||(Su(),rt())}),Bx=Qk(function(a){S("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?xx():a.persisted||xx()}),Cx=Qk(xx);
window.addEventListener?(window.addEventListener("load",zx),window.addEventListener("pageshow",Ax),window.addEventListener("pagehide",Bx)):window.attachEvent&&(window.attachEvent("onload",zx),window.attachEvent("onunload",Cx));
window.onerror=function(a,b,c,d,e){b=void 0===b?"Unknown file":b;c=void 0===c?0:c;var f=!1,g=Nk("log_window_onerror_fraction");if(g&&Math.random()<g)f=!0;else{g=document.getElementsByTagName("script");for(var h=0,k=g.length;h<k;h++)if(0<g[h].src.indexOf("/debug-")){f=!0;break}}f&&(f=!1,e?f=!0:("string"===typeof a?g=a:ErrorEvent&&a instanceof ErrorEvent?(f=!0,g=a.message,b=a.filename,c=a.lineno,d=a.colno):(g="Unknown error",b="Unknown file",c=0),e=new V(g),e.name="UnhandledWindowError",e.message=g,
e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d),f?Bs(e):Cs(e))};
je=Ds;window.addEventListener("unhandledrejection",function(a){Ds(a.reason)});
eb(R("ERRORS")||[],function(a){Bs.apply(null,a)});
Mk("ERRORS",[]);S("embeds_web_enable_scheduler_to_player_binary")&&Om();D("yt.abuse.player.botguardInitialized",E("yt.abuse.player.botguardInitialized")||Lw);D("yt.abuse.player.invokeBotguard",E("yt.abuse.player.invokeBotguard")||Mw);D("yt.abuse.dclkstatus.checkDclkStatus",E("yt.abuse.dclkstatus.checkDclkStatus")||Sv);D("yt.player.exports.navigate",E("yt.player.exports.navigate")||yx);D("yt.util.activity.init",E("yt.util.activity.init")||Uq);
D("yt.util.activity.getTimeSinceActive",E("yt.util.activity.getTimeSinceActive")||Xq);D("yt.util.activity.setTimestamp",E("yt.util.activity.setTimestamp")||Vq);}).call(this);
