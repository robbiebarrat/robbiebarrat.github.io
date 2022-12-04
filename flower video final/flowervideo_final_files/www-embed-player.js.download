(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var l;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function da(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=da(this);function n(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
n("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
n("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function p(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ia(a){if(!(a instanceof Array)){a=p(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ja(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ka="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ja(d,e)&&(a[e]=d[e])}return a};
n("Object.assign",function(a){return a||ka});
var ma="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},oa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ma(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),qa;
if("function"==typeof Object.setPrototypeOf)qa=Object.setPrototypeOf;else{var ra;a:{var sa={a:!0},ta={};try{ta.__proto__=sa;ra=ta.a;break a}catch(a){}ra=!1}qa=ra?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ua=qa;
function u(a,b){a.prototype=ma(b.prototype);a.prototype.constructor=a;if(ua)ua(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Y=b.prototype}
function va(){this.B=!1;this.l=null;this.i=void 0;this.h=1;this.m=this.o=0;this.s=this.j=null}
function wa(a){if(a.B)throw new TypeError("Generator is already running");a.B=!0}
va.prototype.M=function(a){this.i=a};
function xa(a,b){a.j={Zb:b,hc:!0};a.h=a.o||a.m}
va.prototype.return=function(a){this.j={return:a};this.h=this.m};
function v(a,b,c){a.h=c;return{value:b}}
va.prototype.A=function(a){this.h=a};
function ya(a,b,c){a.o=b;void 0!=c&&(a.m=c)}
function za(a,b){a.h=b;a.o=0}
function Aa(a){a.o=0;var b=a.j.Zb;a.j=null;return b}
function Ba(a){a.s=[a.j];a.o=0;a.m=0}
function Ca(a){var b=a.s.splice(0)[0];(b=a.j=a.j||b)?b.hc?a.h=a.o||a.m:void 0!=b.A&&a.m<b.A?(a.h=b.A,a.j=null):a.h=a.m:a.h=0}
function Da(a){this.h=new va;this.i=a}
function Ea(a,b){wa(a.h);var c=a.h.l;if(c)return Fa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ga(a)}
function Fa(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.B=!1,e;var f=e.value}catch(g){return a.h.l=null,xa(a.h,g),Ga(a)}a.h.l=null;d.call(a.h,f);return Ga(a)}
function Ga(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.B=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.B=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.hc)throw b.Zb;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ha(a){this.next=function(b){wa(a.h);a.h.l?b=Fa(a,a.h.l.next,b,a.h.M):(a.h.M(b),b=Ga(a));return b};
this.throw=function(b){wa(a.h);a.h.l?b=Fa(a,a.h.l["throw"],b,a.h.M):(xa(a.h,b),b=Ga(a));return b};
this.return=function(b){return Ea(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ia(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ia(new Ha(new Da(a)))}
function Ja(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
n("Reflect",function(a){return a?a:{}});
n("Reflect.construct",function(){return oa});
n("Reflect.setPrototypeOf",function(a){return a?a:ua?function(b,c){try{return ua(b,c),!0}catch(d){return!1}}:null});
n("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.B=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=ea.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(m){this.l(m)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(m){return function(q){k||(k=!0,m.call(h,q))}}
var h=this,k=!1;return{resolve:g(this.K),reject:g(this.m)}};
b.prototype.K=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.P(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.I(g):this.o(g)}};
b.prototype.I=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.S(h,g):this.o(g)};
b.prototype.m=function(g){this.M(2,g)};
b.prototype.o=function(g){this.M(1,g)};
b.prototype.M=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.O();this.s()};
b.prototype.O=function(){var g=this;e(function(){if(g.F()){var h=ea.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.F=function(){if(this.B)return!1;var g=ea.CustomEvent,h=ea.Event,k=ea.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.s=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.P=function(g){var h=this.l();g.cb(h.resolve,h.reject)};
b.prototype.S=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(m){k.reject(m)}};
b.prototype.then=function(g,h){function k(w,t){return"function"==typeof w?function(y){try{m(w(y))}catch(E){q(E)}}:t}
var m,q,r=new b(function(w,t){m=w;q=t});
this.cb(k(g,m),k(h,q));return r};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.cb=function(g,h){function k(){switch(m.h){case 1:g(m.j);break;case 2:h(m.j);break;default:throw Error("Unexpected state: "+m.h);}}
var m=this;null==this.i?f.i(k):this.i.push(k);this.B=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var m=p(g),q=m.next();!q.done;q=m.next())d(q.value).cb(h,k)})};
b.all=function(g){var h=p(g),k=h.next();return k.done?d([]):new b(function(m,q){function r(y){return function(E){w[y]=E;t--;0==t&&m(w)}}
var w=[],t=0;do w.push(void 0),t++,d(k.value).cb(r(w.length-1),q),k=h.next();while(!k.done)})};
return b});
n("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=p(k);for(var m;!(m=k.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(k){var m=typeof k;return"object"===m&&null!==k||"function"===m}
function e(k){if(!ja(k,g)){var m=new c;ba(k,g,{value:m})}}
function f(k){var m=Object[k];m&&(Object[k]=function(q){if(q instanceof c)return q;Object.isExtensible(q)&&e(q);return m(q)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),m=Object.seal({}),q=new a([[k,2],[m,3]]);if(2!=q.get(k)||3!=q.get(m))return!1;q.delete(k);q.set(m,4);return!q.has(k)&&4==q.get(m)}catch(r){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,m){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ja(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=m;return this};
b.prototype.get=function(k){return d(k)&&ja(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.h)?delete k[g][this.h]:!1};
return b});
n("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var m=h.h;return ha(function(){if(m){for(;m.head!=h.h;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:k(m)};m=null}return{done:!0,value:void 0}})}
function d(h,k){var m=k&&typeof k;"object"==m||"function"==m?f.has(k)?m=f.get(k):(m=""+ ++g,f.set(k,m)):m="p_"+k;var q=h.data_[m];if(q&&ja(h.data_,m))for(h=0;h<q.length;h++){var r=q[h];if(k!==k&&r.key!==r.key||k===r.key)return{id:m,list:q,index:h,entry:r}}return{id:m,list:q,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=p(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(p([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var m=k.entries(),q=m.next();if(q.done||q.value[0]!=h||"s"!=q.value[1])return!1;q=m.next();return q.done||4!=q.value[0].x||"t"!=q.value[1]||!m.next().done?!1:!0}catch(r){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=k:(m.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},m.list.push(m.entry),this.h.previous.next=m.entry,this.h.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var m=this.entries(),q;!(q=m.next()).done;)q=q.value,h.call(k,q[1],q[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ka(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
n("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
n("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
n("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
n("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
n("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
n("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
function La(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
n("Array.prototype.entries",function(a){return a?a:function(){return La(this,function(b,c){return[b,c]})}});
n("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
n("Array.prototype.keys",function(a){return a?a:function(){return La(this,function(b){return b})}});
n("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
n("Object.setPrototypeOf",function(a){return a||ua});
n("Set",function(a){function b(c){this.h=new Map;if(c){c=p(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(p([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
n("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push([d,b[d]]);return c}});
n("Array.prototype.values",function(a){return a?a:function(){return La(this,function(b,c){return c})}});
n("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
n("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
n("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ka(this,b,"includes").indexOf(b,c||0)}});
n("globalThis",function(a){return a||ea});
n("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push(b[d]);return c}});
var Ma=Ma||{},z=this||self;function A(a,b,c){a=a.split(".");c=c||z;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||z;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Na(a){a.zb=void 0;a.getInstance=function(){return a.zb?a.zb:a.zb=new a}}
function Oa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Pa(a){var b=Oa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Qa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ra(a){return Object.prototype.hasOwnProperty.call(a,Sa)&&a[Sa]||(a[Sa]=++Ta)}
var Sa="closure_uid_"+(1E9*Math.random()>>>0),Ta=0;function Ua(a,b,c){return a.call.apply(a.bind,arguments)}
function Va(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Xa=Ua:Xa=Va;return Xa.apply(null,arguments)}
function Ya(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Za(a,b){function c(){}
c.prototype=b.prototype;a.Y=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.jr=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function $a(a){return a}
;function ab(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,ab);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Za(ab,Error);ab.prototype.name="CustomError";function bb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function cb(){}
function db(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var eb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},fb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},gb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},hb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},ib=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
fb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d},jb=Array.prototype.every?function(a,b){return Array.prototype.every.call(a,b,void 0)}:function(a,b){for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&!b.call(void 0,d[e],e,a))return!1;
return!0};
function kb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function mb(a,b){b=eb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function nb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Pa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function ob(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function pb(a){var b=qb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function rb(a){for(var b in a)return!1;return!0}
function sb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function tb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function ub(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function vb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function wb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=wb(a[c]);return b}
var xb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function yb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<xb.length;f++)c=xb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var zb;function Ab(){if(void 0===zb){var a=null,b=z.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:$a,createScript:$a,createScriptURL:$a})}catch(c){z.console&&z.console.error(c.message)}zb=a}else zb=a}return zb}
;function Bb(a,b){this.j=a===Cb&&b||""}
Bb.prototype.i=!0;Bb.prototype.h=function(){return this.j};
function Db(a){return new Bb(Cb,a)}
var Cb={};Db("");var Eb={};function Fb(a){this.j=Eb===Eb?a:"";this.i=!0}
Fb.prototype.toString=function(){return this.j.toString()};
Fb.prototype.h=function(){return this.j.toString()};function Ib(a,b){this.j=b===Jb?a:""}
Ib.prototype.toString=function(){return this.j+""};
Ib.prototype.i=!0;Ib.prototype.h=function(){return this.j.toString()};
function Kb(a){if(a instanceof Ib&&a.constructor===Ib)return a.j;Oa(a);return"type_error:TrustedResourceUrl"}
var Jb={};function Lb(a){var b=Ab();a=b?b.createScriptURL(a):a;return new Ib(a,Jb)}
;var Mb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Nb(a,b){return a<b?-1:a>b?1:0}
;function Ob(a,b){this.j=b===Pb?a:""}
Ob.prototype.toString=function(){return this.j.toString()};
Ob.prototype.i=!0;Ob.prototype.h=function(){return this.j.toString()};
function Qb(a){if(a instanceof Ob&&a.constructor===Ob)return a.j;Oa(a);return"type_error:SafeUrl"}
var Rb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Pb={},Sb=new Ob("about:invalid#zClosurez",Pb);function Tb(){var a=z.navigator;return a&&(a=a.userAgent)?a:""}
function C(a){return-1!=Tb().indexOf(a)}
;function Ub(){return C("Trident")||C("MSIE")}
function Vb(){return C("Firefox")||C("FxiOS")}
function Wb(){return C("Safari")&&!(Xb()||C("Coast")||C("Opera")||C("Edge")||C("Edg/")||C("OPR")||Vb()||C("Silk")||C("Android"))}
function Xb(){return(C("Chrome")||C("CriOS"))&&!C("Edge")||C("Silk")}
function $b(){return C("Android")&&!(Xb()||Vb()||C("Opera")||C("Silk"))}
function ac(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function bc(a){var b=Tb();if("Internet Explorer"===a){if(Ub())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=ac(c);
switch(a){case "Opera":if(C("Opera"))return b(["Version","Opera"]);if(C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(C("Edge"))return b(["Edge"]);if(C("Edg/"))return b(["Edg"]);break;case "Chromium":if(Xb())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&Vb()||"Safari"===a&&Wb()||"Android Browser"===a&&$b()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function cc(a){a=bc(a);if(""===a)return NaN;a=a.split(".");return 0===a.length?NaN:Number(a[0])}
;var dc={};function ec(a){this.j=dc===dc?a:"";this.i=!0}
ec.prototype.h=function(){return this.j.toString()};
ec.prototype.toString=function(){return this.j.toString()};function fc(a,b){b instanceof Ob||b instanceof Ob||(b="object"==typeof b&&b.i?b.h():String(b),Rb.test(b)||(b="about:invalid#zClosurez"),b=new Ob(b,Pb));a.href=Qb(b)}
function gc(a,b){a.rel="stylesheet";a.href=Kb(b).toString();(b=hc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function ic(){return hc("script[nonce]")}
var jc=/^[\w+/_-]+[=]{0,2}$/;function hc(a,b){b=(b||z).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&jc.test(a)?a:"":""}
;function kc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var lc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function mc(a){return a?decodeURI(a):a}
function nc(a,b){return b.match(lc)[a]||null}
function oc(a){return mc(nc(3,a))}
function pc(a){var b=a.match(lc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function qc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function rc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)rc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function sc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)rc(a[b],a[b+1],c);return c.join("&")}
function tc(a){var b=[],c;for(c in a)rc(c,a[c],b);return b.join("&")}
function uc(a,b){var c=2==arguments.length?sc(arguments[1],0):sc(arguments,1);return qc(a,c)}
function vc(a,b){b=tc(b);return qc(a,b)}
function zc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return qc(a,b+c)}
function Ac(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var Bc=/#|$/,Cc=/[?&]($|#)/;function Dc(a,b){for(var c=a.search(Bc),d=0,e,f=[];0<=(e=Ac(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Cc,"$1")}
;function Ec(a){z.setTimeout(function(){throw a;},0)}
;function Fc(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Gc(){var a=Tb();if(C("Windows")){var b=/Windows (?:NT|Phone) ([0-9.]+)/;b.exec(a)}else Fc()||C("iPad")||C("iPod")?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):C("Macintosh")?(b=/Mac OS X ([0-9_.]+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):-1!=Tb().toLowerCase().indexOf("kaios")?(b=/(?:KaiOS)\/(\S+)/i,b.exec(a)):C("Android")?(b=/Android\s+([^\);]+)(\)|;)/,b.exec(a)):C("CrOS")&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,b.exec(a))}
;function Hc(a){Hc[" "](a);return a}
Hc[" "]=function(){};
function Ic(a){var b=Jc;return Object.prototype.hasOwnProperty.call(b,9)?b[9]:b[9]=a(9)}
;var Kc=C("Opera"),Lc=Ub(),Mc=C("Edge"),Nc=C("Gecko")&&!(-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),Oc=-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"),Pc=C("Android");function Qc(){var a=z.document;return a?a.documentMode:void 0}
var Rc;a:{var Sc="",Tc=function(){var a=Tb();if(Nc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Mc)return/Edge\/([\d\.]+)/.exec(a);if(Lc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Oc)return/WebKit\/(\S+)/.exec(a);if(Kc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Tc&&(Sc=Tc?Tc[1]:"");if(Lc){var Uc=Qc();if(null!=Uc&&Uc>parseFloat(Sc)){Rc=String(Uc);break a}}Rc=Sc}var Vc=Rc,Jc={};
function Wc(){return Ic(function(){for(var a=0,b=Mb(String(Vc)).split("."),c=Mb("9").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Nb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Nb(0==f[2].length,0==g[2].length)||Nb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}return 0<=a})}
var Xc;if(z.document&&Lc){var Yc=Qc();Xc=Yc?Yc:parseInt(Vc,10)||void 0}else Xc=void 0;var Zc=Xc;var $c=Fc()||C("iPod"),ad=C("iPad");$b();Xb();var bd=Wb()&&!(Fc()||C("iPad")||C("iPod"));var cd={},dd=null;function ed(a,b){Pa(a);void 0===b&&(b=0);fd();b=cd[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],m=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+m+g+h+k}m=0;k=d;switch(a.length-e){case 2:m=a[e+1],k=b[(m&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|m>>4]+k+d}return c.join("")}
function gd(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;hd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function hd(a,b){function c(k){for(;d<a.length;){var m=a.charAt(d++),q=dd[m];if(null!=q)return q;if(!/^[\s\xa0]*$/.test(m))throw Error("Unknown base64 encoding at char: "+m);}return k}
fd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function fd(){if(!dd){dd={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));cd[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===dd[f]&&(dd[f]=e)}}}}
;var id="undefined"!==typeof Uint8Array;function jd(a){return id&&null!=a&&a instanceof Uint8Array}
var kd={};var ld;function md(a){if(a!==kd)throw Error("illegal external caller");}
function nd(a,b){md(b);this.ca=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
function sd(){return ld||(ld=new nd(null,kd))}
nd.prototype.Ma=function(){return null==this.ca};
nd.prototype.sizeBytes=function(){md(kd);var a=this.ca;null==a||jd(a)||("string"===typeof a?a=gd(a):(Oa(a),a=null));return(a=null==a?a:this.ca=a)?a.length:0};var td="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function ud(a,b){Object.isFrozen(a)||(td?a[td]|=b:void 0!==a.ga?a.ga|=b:Object.defineProperties(a,{ga:{value:b,configurable:!0,writable:!0,enumerable:!1}}))}
function vd(a,b){Object.isExtensible(a)&&(td?a[td]&&(a[td]&=~b):void 0!==a.ga&&(a.ga&=~b))}
function wd(a){var b;td?b=a[td]:b=a.ga;return null==b?0:b}
function xd(a,b){td?a[td]=b:void 0!==a.ga?a.ga=b:Object.defineProperties(a,{ga:{value:b,configurable:!0,writable:!0,enumerable:!1}})}
function yd(a){ud(a,1);return a}
function zd(a){ud(a,17);return a}
function Ad(a){return a?!!(wd(a)&2):!1}
function Bd(a){ud(a,16);return a}
function Cd(a,b){xd(b,(wd(a)|0)&-51)}
function Dd(a,b){xd(b,(wd(a)|18)&-33)}
;var Ed={};function Fd(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Gd,Hd=Object,Id=Hd.freeze,Jd=[];ud(Jd,3);var Kd=Id.call(Hd,Jd);function Ld(a){if(Ad(a.u))throw Error("Cannot mutate an immutable Message");}
;function Md(a){return a.displayName||a.name||"unknown type name"}
function Nd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Md(b)+" but got "+(a&&Md(a.constructor)));return a}
;function Od(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a&&!Array.isArray(a)){if(jd(a))return ed(a);if(a instanceof nd){var b=a.ca;return null==b?"":"string"===typeof b?b:a.ca=ed(b)}}}return a}
;function Pd(a,b,c,d){if(null!=a){if(Array.isArray(a))a=Qd(a,b,c,void 0!==d);else if(Fd(a)){var e={},f;for(f in a)e[f]=Pd(a[f],b,c,d);a=e}else a=b(a,d);return a}}
function Qd(a,b,c,d){d=d?!!(wd(a)&16):void 0;var e=Array.prototype.slice.call(a);c(a,e);for(a=0;a<e.length;a++)e[a]=Pd(e[a],b,c,d);return e}
function Rd(a){return a.ib===Ed?a.toJSON():Od(a)}
function Sd(a){if(!a)return a;if("object"===typeof a){if(jd(a))return new Uint8Array(a);if(a.ib===Ed)return a.clone()}return a}
function Td(){}
;function Ud(a,b,c){return-1===b?null:b>=a.qa?a.R?a.R[b]:void 0:(void 0===c?0:c)&&a.R&&(c=a.R[b],null!=c)?c:a.u[b+a.la]}
function D(a,b,c,d,e){d=void 0===d?!1:d;(void 0===e?0:e)||Ld(a);a.j&&(a.j=void 0);if(b>=a.qa||d)return(a.R||(a.R=a.u[a.qa+a.la]={}))[b]=c,a;void 0!==a.R&&a.qa>=a.u.length?(d=a.u.length-1,e=b+a.la,e>=d?(a.u[d]=void 0,a.u[e]=c,a.u.push(a.R)):a.u[e]=c):a.u[b+a.la]=c;void 0!==a.R&&b in a.R&&delete a.R[b];return a}
function Vd(a,b,c,d){var e=Ud(a,b,d);Array.isArray(e)||(e=Kd);var f=wd(e);f&1||yd(e);if(Ad(a.u))f&2||ud(e,2),c&1||Object.freeze(e);else if(e===Kd||!(c&1&&c&2)&&f&2)e=yd(Array.prototype.slice.call(e)),D(a,b,e,d);else if(!(c&2)&&f&16){a=e;if(!Array.isArray(a))throw Error("cannot mark non-array as shared mutably");vd(a,16)}return e}
function Wd(a,b,c,d){Ld(a);(c=Xd(a,c))&&c!==b&&null!=d&&D(a,c,void 0,!1);return D(a,b,d)}
function Xd(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Ud(a,e)&&(0!==c&&D(a,c,void 0,!1,!0),c=e)}return c}
function Yd(a,b,c,d){var e=d=void 0===d?!1:d,f=Ud(a,c,e);var g=!1;var h=null==f||"object"!==typeof f||(g=Array.isArray(f))||f.ib!==Ed?g?new b(f):void 0:f;h!==f&&null!=h&&(D(a,c,h,e,!0),ud(h.u,wd(a.u)&-33));b=h;if(null==b)return b;Ad(b.u)&&!Ad(a.u)&&(b=Zd(b),D(a,c,b,d));return b}
function $d(a,b,c,d,e){e=void 0===e?!0:e;a.h||(a.h={});var f=a.h[c],g=Vd(a,c,3,d),h=Ad(a.u);if(f)h||(Object.isFrozen(f)?e||(f=Array.prototype.slice.call(f),a.h[c]=f):e&&Object.freeze(f));else{f=[];var k=!!(wd(a.u)&16),m=Ad(g);!h&&m&&(g=yd(Array.prototype.slice.call(g)),D(a,c,g,d));d=m;for(var q=0;q<g.length;q++){var r=g[q];d=d||Ad(r);var w=b,t=k,y=!1;y=void 0===y?!1:y;t=void 0===t?!1:t;r=Array.isArray(r)?new w(t?Bd(r):r):y?new w:void 0;void 0!==r&&(f.push(r),m&&ud(r.u,2))}a.h[c]=f;a=g;b=!d;Object.isFrozen(a)||
(c=wd(a)|33,xd(a,b?c|8:c&-9));(h||e&&m)&&ud(f,2);(h||e)&&Object.freeze(f)}return f}
function ae(a,b,c,d){d=void 0===d?!1:d;var e=Ad(a.u);b=$d(a,b,c,d,e);a=Vd(a,c,3,d);if(e=!e&&a){if(!a)throw Error("cannot check mutability state of non-array");e=!(wd(a)&8)}if(e){for(e=0;e<b.length;e++)(c=b[e])&&Ad(c.u)&&(c=e,d=Zd(b[e]),b[c]=d,a[e]=b[e].u);ud(a,8)}return b}
function G(a,b,c,d){Ld(a);null!=d?Nd(d,b):d=void 0;return D(a,c,d)}
function be(a,b,c,d,e){Ld(a);null!=e?Nd(e,b):e=void 0;Wd(a,c,d,e)}
function ce(a,b,c,d,e){Ld(a);if(null!=d){var f=yd([]);for(var g=!1,h=0;h<d.length;h++)f[h]=Nd(d[h],b).u,g=g||Ad(f[h]);a.h||(a.h={});a.h[c]=d;b=f;g?vd(b,8):ud(b,8)}else a.h&&(a.h[c]=void 0),f=Kd;return D(a,c,f,e)}
function de(a,b,c,d){Ld(a);var e=$d(a,c,b,void 0,!1);c=null!=d?Nd(d,c):new c;a=Vd(a,b,2);e.push(c);a.push(c.u);Ad(c.u)&&vd(a,8)}
function ee(a,b){return Ud(a,b)}
function fe(a,b){return null==a?b:a}
;function ge(a,b){if(null!=a){if(id&&a instanceof Uint8Array)return a.length?new nd(new Uint8Array(a),kd):sd();if(Array.isArray(a)){if(Ad(a))return a;b&&(b=wd(a),b=!(b&32)&&(!!(b&16)||0===b));return b?(ud(a,2),a):Qd(a,ge,Dd)}return a.ib===Ed?he(a):a}}
function ie(a,b,c,d,e,f){(a=a.h&&a.h[c])?(d=0<a.length?a[0].constructor:void 0,Ad(a)&&Object.isFrozen(a)||(f=hb(a,he),Dd(a,f),Object.freeze(f),a=f),ce(b,d,c,a,e)):D(b,c,ge(d,f),e)}
function he(a){if(Ad(a.u))return a;a=je(a);ud(a.u,2);return a}
function je(a){var b=new a.constructor;a.La&&(b.La=a.La.slice());for(var c=a.u,d=!!(wd(c)&16),e=0;e<c.length;e++){var f=c[e];if(e===c.length-1&&Fd(f))for(var g in f){var h=+g;Number.isNaN(h)?(b.R||(b.R=b.u[b.qa+b.la]={}))[h]=f[h]:ie(a,b,h,f[g],!0,d)}else ie(a,b,e-a.la,f,!1,d)}return b}
function Zd(a){if(!Ad(a.u))return a;var b=je(a);b.j=a;return b}
;function I(a,b,c){null==a&&(a=ke);ke=null;var d=this.constructor.h||0,e=0<d,f=this.constructor.i,g=!1;if(null==a){var h=f?[f]:[];ud(h,48);a=h;h=!0}else{if(!Array.isArray(a))throw Error();if(h=!!(wd(a)&16))g=wd(a),xd(a,g|32),g=!!(g&32)}e&&0<a.length&&Fd(a[a.length-1])&&"g"in a[a.length-1]&&(d=0);this.la=(f?0:-1)-d;this.h=void 0;this.u=a;a:{f=this.u.length;d=f-1;if(f&&(f=this.u[d],Fd(f))){this.R=f;b=Object.keys(f);0<b.length&&jb(b,isNaN)?this.qa=Number.MAX_VALUE:this.qa=d-this.la;break a}void 0!==b&&
-1<b?(this.qa=Math.max(b,d+1-this.la),this.R=void 0):this.qa=Number.MAX_VALUE}if(!e&&this.R&&"g"in this.R)throw Error('Unexpected "g" flag in sparse object of message that is not a group type.');if(c)for(e=h&&!g?zd:yd,b=0;b<c.length;b++)h=c[b],(g=Ud(this,h))?Array.isArray(g)&&e(g):D(this,h,Kd,!1,!0)}
I.prototype.toJSON=function(){var a=this.u,b;Gd?b=a:b=Qd(a,Rd,Td);return b};
function le(a){Gd=!0;try{return JSON.stringify(a.toJSON(),me)}finally{Gd=!1}}
I.prototype.clone=function(){var a=Qd(this.u,Sd,Cd);Bd(a);ke=a;a=new this.constructor(a);ke=null;ne(a,this);return a};
I.prototype.ib=Ed;I.prototype.toString=function(){return this.u.toString()};
function me(a,b){return Od(b)}
function ne(a,b){b.La&&(a.La=b.La.slice());var c=b.h;if(c){b=b.R;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=ae(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)ne(f[g],e[g])}else throw Error("unexpected object: type: "+Oa(e)+": "+e);}}}}
var ke;function oe(a){var b=this.h,c=this.i;return this.isRepeated?ae(a,b,c,!0):Yd(a,b,c,!0)}
;function pe(a){this.Tb=a}
;function qe(a,b,c){this.i=a;this.l=b;this.h=c||[];this.Ba=new Map}
l=qe.prototype;l.Gc=function(a){var b=Ja.apply(1,arguments),c=this.ub(b);c?c.push(new pe(a)):this.tc(a,b)};
l.tc=function(a){this.Ba.set(this.ac(Ja.apply(1,arguments)),[new pe(a)])};
l.ub=function(){var a=this.ac(Ja.apply(0,arguments));return this.Ba.has(a)?this.Ba.get(a):void 0};
l.Tc=function(){var a=this.ub(Ja.apply(0,arguments));return a&&a.length?a[0]:void 0};
l.clear=function(){this.Ba.clear()};
l.ac=function(){var a=Ja.apply(0,arguments);return a?a.join(","):"key"};function re(a,b){qe.call(this,a,3,b)}
u(re,qe);re.prototype.j=function(a){var b=Ja.apply(1,arguments),c=0,d=this.Tc(b);d&&(c=d.Tb);this.tc(c+a,b)};function se(a,b){qe.call(this,a,2,b)}
u(se,qe);se.prototype.j=function(a){this.Gc(a,Ja.apply(1,arguments))};function te(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function ue(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Pa(d)?ue.apply(null,d):te(d)}}
;function J(){this.M=this.M;this.B=this.B}
J.prototype.M=!1;J.prototype.h=function(){return this.M};
J.prototype.dispose=function(){this.M||(this.M=!0,this.C())};
function ve(a,b){we(a,Ya(te,b))}
function we(a,b){a.M?b():(a.B||(a.B=[]),a.B.push(b))}
J.prototype.C=function(){if(this.B)for(;this.B.length;)this.B.shift()()};function Ce(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Ce.prototype.stopPropagation=function(){this.j=!0};
Ce.prototype.preventDefault=function(){this.defaultPrevented=!0};function De(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||z.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Ee(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Fe[c])c=Fe[c];else{c=String(c);if(!Fe[c]){var f=/function\s+([^\(]+)/m.exec(c);Fe[c]=f?f[1]:"[Anonymous]"}c=Fe[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Ee(a,b){b||(b={});b[Ge(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Ge(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Ee(a,b));return c}
function Ge(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Fe={};var He=function(){if(!z.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{z.addEventListener("test",function(){},b),z.removeEventListener("test",function(){},b)}catch(c){}return a}();function Ie(a,b){Ce.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Za(Ie,Ce);var Je={2:"touch",3:"pen",4:"mouse"};
Ie.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Nc){a:{try{Hc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Je[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Ie.Y.preventDefault.call(this)};
Ie.prototype.stopPropagation=function(){Ie.Y.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Ie.prototype.preventDefault=function(){Ie.Y.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Ke="closure_listenable_"+(1E6*Math.random()|0);var Le=0;function Me(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.gb=e;this.key=++Le;this.Oa=this.bb=!1}
function Ne(a){a.Oa=!0;a.listener=null;a.proxy=null;a.src=null;a.gb=null}
;function Oe(a){this.src=a;this.listeners={};this.h=0}
Oe.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Pe(a,b,d,e);-1<g?(b=a[g],c||(b.bb=!1)):(b=new Me(b,this.src,f,!!d,e),b.bb=c,a.push(b));return b};
Oe.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Pe(e,b,c,d);return-1<b?(Ne(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Qe(a,b){var c=b.type;c in a.listeners&&mb(a.listeners[c],b)&&(Ne(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Pe(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Oa&&f.listener==b&&f.capture==!!c&&f.gb==d)return e}return-1}
;var Re="closure_lm_"+(1E6*Math.random()|0),Se={},Te=0;function Ue(a,b,c,d,e){if(d&&d.once)Ve(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Ue(a,b[f],c,d,e);else c=We(c),a&&a[Ke]?a.ia(b,c,Qa(d)?!!d.capture:!!d,e):Xe(a,b,c,!1,d,e)}
function Xe(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Qa(e)?!!e.capture:!!e,h=Ye(a);h||(a[Re]=h=new Oe(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ze();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)He||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent($e(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Te++}}
function Ze(){function a(c){return b.call(a.src,a.listener,c)}
var b=af;return a}
function Ve(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ve(a,b[f],c,d,e);else c=We(c),a&&a[Ke]?a.l.add(String(b),c,!0,Qa(d)?!!d.capture:!!d,e):Xe(a,b,c,!0,d,e)}
function bf(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)bf(a,b[f],c,d,e);else(d=Qa(d)?!!d.capture:!!d,c=We(c),a&&a[Ke])?a.l.remove(String(b),c,d,e):a&&(a=Ye(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Pe(b,c,d,e)),(c=-1<a?b[a]:null)&&cf(c))}
function cf(a){if("number"!==typeof a&&a&&!a.Oa){var b=a.src;if(b&&b[Ke])Qe(b.l,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent($e(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Te--;(c=Ye(b))?(Qe(c,a),0==c.h&&(c.src=null,b[Re]=null)):Ne(a)}}}
function $e(a){return a in Se?Se[a]:Se[a]="on"+a}
function af(a,b){if(a.Oa)a=!0;else{b=new Ie(b,this);var c=a.listener,d=a.gb||a.src;a.bb&&cf(a);a=c.call(d,b)}return a}
function Ye(a){a=a[Re];return a instanceof Oe?a:null}
var df="__closure_events_fn_"+(1E9*Math.random()>>>0);function We(a){if("function"===typeof a)return a;a[df]||(a[df]=function(b){return a.handleEvent(b)});
return a[df]}
;function ef(){J.call(this);this.l=new Oe(this);this.Dc=this;this.ka=null}
Za(ef,J);ef.prototype[Ke]=!0;ef.prototype.addEventListener=function(a,b,c,d){Ue(this,a,b,c,d)};
ef.prototype.removeEventListener=function(a,b,c,d){bf(this,a,b,c,d)};
function ff(a,b){var c=a.ka;if(c){var d=[];for(var e=1;c;c=c.ka)d.push(c),++e}a=a.Dc;c=b.type||b;"string"===typeof b?b=new Ce(b,a):b instanceof Ce?b.target=b.target||a:(e=b,b=new Ce(c,a),yb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=gf(g,c,!0,b)&&e}b.j||(g=b.h=a,e=gf(g,c,!0,b)&&e,b.j||(e=gf(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=gf(g,c,!1,b)&&e}
ef.prototype.C=function(){ef.Y.C.call(this);if(this.l){var a=this.l,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Ne(d[e]);delete a.listeners[c];a.h--}}this.ka=null};
ef.prototype.ia=function(a,b,c,d){return this.l.add(String(a),b,!1,c,d)};
function gf(a,b,c,d){b=a.l.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Oa&&g.capture==c){var h=g.listener,k=g.gb||g.src;g.bb&&Qe(a.l,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function hf(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
hf.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function jf(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function kf(a,b){return a+Math.random()*(b-a)}
;function lf(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
l=lf.prototype;l.clone=function(){return new lf(this.x,this.y)};
l.equals=function(a){return a instanceof lf&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
l.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
l.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
l.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
l.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function mf(a,b){this.width=a;this.height=b}
l=mf.prototype;l.clone=function(){return new mf(this.width,this.height)};
l.aspectRatio=function(){return this.width/this.height};
l.Ma=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
l.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function nf(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function of(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function pf(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var qf;function rf(){var a=z.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=of("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Xa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Ub()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Sb;c.Sb=null;e()}};
return function(e){d.next={Sb:e};d=d.next;b.port2.postMessage(0)}}return function(e){z.setTimeout(e,0)}}
;function sf(){this.i=this.h=null}
sf.prototype.add=function(a,b){var c=tf.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
sf.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var tf=new hf(function(){return new uf},function(a){return a.reset()});
function uf(){this.next=this.scope=this.h=null}
uf.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
uf.prototype.reset=function(){this.next=this.scope=this.h=null};var vf,wf=!1,xf=new sf;function yf(a,b){vf||zf();wf||(vf(),wf=!0);xf.add(a,b)}
function zf(){if(z.Promise&&z.Promise.resolve){var a=z.Promise.resolve(void 0);vf=function(){a.then(Af)}}else vf=function(){var b=Af;
"function"!==typeof z.setImmediate||z.Window&&z.Window.prototype&&!C("Edge")&&z.Window.prototype.setImmediate==z.setImmediate?(qf||(qf=rf()),qf(b)):z.setImmediate(b)}}
function Af(){for(var a;a=xf.remove();){try{a.h.call(a.scope)}catch(b){Ec(b)}jf(tf,a)}wf=!1}
;function Bf(a){this.h=0;this.B=void 0;this.l=this.i=this.j=null;this.m=this.o=!1;if(a!=cb)try{var b=this;a.call(void 0,function(c){Cf(b,2,c)},function(c){Cf(b,3,c)})}catch(c){Cf(this,3,c)}}
function Df(){this.next=this.context=this.i=this.j=this.h=null;this.l=!1}
Df.prototype.reset=function(){this.context=this.i=this.j=this.h=null;this.l=!1};
var Ef=new hf(function(){return new Df},function(a){a.reset()});
function Ff(a,b,c){var d=Ef.get();d.j=a;d.i=b;d.context=c;return d}
function Gf(a){return new Bf(function(b,c){c(a)})}
Bf.prototype.then=function(a,b,c){return Hf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Bf.prototype.$goog_Thenable=!0;l=Bf.prototype;l.ob=function(a,b){return Hf(this,null,a,b)};
l.catch=Bf.prototype.ob;l.cancel=function(a){if(0==this.h){var b=new If(a);yf(function(){Jf(this,b)},this)}};
function Jf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.l||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Jf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Kf(c),Lf(c,e,3,b)))}a.j=null}else Cf(a,3,b)}
function Mf(a,b){a.i||2!=a.h&&3!=a.h||Nf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Hf(a,b,c,d){var e=Ff(null,null,null);e.h=new Bf(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(m){g(m)}}:f;
e.i=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof If?g(h):f(k)}catch(m){g(m)}}:g});
e.h.j=a;Mf(a,e);return e.h}
l.Cd=function(a){this.h=0;Cf(this,2,a)};
l.Dd=function(a){this.h=0;Cf(this,3,a)};
function Cf(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.Cd,f=a.Dd;if(d instanceof Bf){Mf(d,Ff(e||cb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Qa(d))try{var k=d.then;if("function"===typeof k){Of(d,k,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.B=c,a.h=b,a.j=null,Nf(a),3!=b||c instanceof If||Pf(a,c))}}
function Of(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Nf(a){a.o||(a.o=!0,yf(a.Rc,a))}
function Kf(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
l.Rc=function(){for(var a;a=Kf(this);)Lf(this,a,this.h,this.B);this.o=!1};
function Lf(a,b,c,d){if(3==c&&b.i&&!b.l)for(;a&&a.m;a=a.j)a.m=!1;if(b.h)b.h.j=null,Qf(b,c,d);else try{b.l?b.j.call(b.context):Qf(b,c,d)}catch(e){Rf.call(null,e)}jf(Ef,b)}
function Qf(a,b,c){2==b?a.j.call(a.context,c):a.i&&a.i.call(a.context,c)}
function Pf(a,b){a.m=!0;yf(function(){a.m&&Rf.call(null,b)})}
var Rf=Ec;function If(a){ab.call(this,a)}
Za(If,ab);If.prototype.name="cancel";function Sf(a,b){ef.call(this);this.j=a||1;this.i=b||z;this.m=Xa(this.Ad,this);this.o=Date.now()}
Za(Sf,ef);l=Sf.prototype;l.enabled=!1;l.ba=null;function Tf(a,b){a.j=b;a.ba&&a.enabled?(a.stop(),a.start()):a.ba&&a.stop()}
l.Ad=function(){if(this.enabled){var a=Date.now()-this.o;0<a&&a<.8*this.j?this.ba=this.i.setTimeout(this.m,this.j-a):(this.ba&&(this.i.clearTimeout(this.ba),this.ba=null),ff(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
l.start=function(){this.enabled=!0;this.ba||(this.ba=this.i.setTimeout(this.m,this.j),this.o=Date.now())};
l.stop=function(){this.enabled=!1;this.ba&&(this.i.clearTimeout(this.ba),this.ba=null)};
l.C=function(){Sf.Y.C.call(this);this.stop();delete this.i};
function Uf(a,b,c){if("function"===typeof a)c&&(a=Xa(a,c));else if(a&&"function"==typeof a.handleEvent)a=Xa(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:z.setTimeout(a,b||0)}
;function Vf(a){this.B=a;this.h=new Map;this.o=new Set;this.j=0;this.l=100;this.flushInterval=3E4;this.i=new Sf(this.flushInterval);this.i.ia("tick",this.qb,!1,this);this.m=!1}
l=Vf.prototype;l.qc=function(a){this.m=a;this.l=1};
function Wf(a){a.i.enabled||a.i.start();a.j++;a.j>=a.l&&a.qb()}
l.qb=function(){var a=this.h.values();a=[].concat(ia(a)).filter(function(b){return b.Ba.size});
a.length&&this.B.flush(a,this.m);Xf(a);this.j=0;this.i.enabled&&this.i.stop()};
l.Hc=function(a){var b=Ja.apply(1,arguments);this.h.has(a)||this.h.set(a,new re(a,b))};
l.Qb=function(a){var b=Ja.apply(1,arguments);this.h.has(a)||this.h.set(a,new se(a,b))};
function Yf(a,b){return a.o.has(b)?void 0:a.h.get(b)}
l.Lb=function(a){this.Bc.apply(this,[a,1].concat(ia(Ja.apply(1,arguments))))};
l.Bc=function(a,b){var c=Ja.apply(2,arguments),d=Yf(this,a);d&&d instanceof re&&(d.j(b,c),Wf(this))};
l.pb=function(a,b){var c=Ja.apply(2,arguments),d=Yf(this,a);d&&d instanceof se&&(d.j(b,c),Wf(this))};
function Xf(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Zf(a){this.h=a;this.h.Qb("/client_streamz/bg/fil",{tb:3,sb:"rk"})}
function $f(a){this.h=a;this.h.Hc("/client_streamz/bg/fsc",{tb:3,sb:"rk"})}
function ag(a){this.h=a;this.h.Qb("/client_streamz/bg/fsl",{tb:3,sb:"rk"})}
;function bg(a){I.call(this,a,-1,cg)}
u(bg,I);function dg(a){I.call(this,a,-1,eg)}
u(dg,I);function fg(a){I.call(this,a)}
u(fg,I);function gg(a){I.call(this,a)}
u(gg,I);var cg=[3,6,4],eg=[1],hg=[1,2,3],ig=[1,2,3];function jg(a){I.call(this,a,-1,kg)}
u(jg,I);var kg=[1];function lg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function mg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;q=m=0}
function b(r){for(var w=g,t=0;64>t;t+=4)w[t/4]=r[t]<<24|r[t+1]<<16|r[t+2]<<8|r[t+3];for(t=16;80>t;t++)r=w[t-3]^w[t-8]^w[t-14]^w[t-16],w[t]=(r<<1|r>>>31)&4294967295;r=e[0];var y=e[1],E=e[2],F=e[3],O=e[4];for(t=0;80>t;t++){if(40>t)if(20>t){var N=F^y&(E^F);var Q=1518500249}else N=y^E^F,Q=1859775393;else 60>t?(N=y&E|F&(y|E),Q=2400959708):(N=y^E^F,Q=3395469782);N=((r<<5|r>>>27)&4294967295)+N+O+Q+w[t]&4294967295;O=F;F=E;E=(y<<30|y>>>2)&4294967295;y=r;r=N}e[0]=e[0]+r&4294967295;e[1]=e[1]+y&4294967295;e[2]=
e[2]+E&4294967295;e[3]=e[3]+F&4294967295;e[4]=e[4]+O&4294967295}
function c(r,w){if("string"===typeof r){r=unescape(encodeURIComponent(r));for(var t=[],y=0,E=r.length;y<E;++y)t.push(r.charCodeAt(y));r=t}w||(w=r.length);t=0;if(0==m)for(;t+64<w;)b(r.slice(t,t+64)),t+=64,q+=64;for(;t<w;)if(f[m++]=r[t++],q++,64==m)for(m=0,b(f);t+64<w;)b(r.slice(t,t+64)),t+=64,q+=64}
function d(){var r=[],w=8*q;56>m?c(h,56-m):c(h,64-(m-56));for(var t=63;56<=t;t--)f[t]=w&255,w>>>=8;b(f);for(t=w=0;5>t;t++)for(var y=24;0<=y;y-=8)r[w++]=e[t]>>y&255;return r}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var m,q;a();return{reset:a,update:c,digest:d,Oc:function(){for(var r=d(),w="",t=0;t<r.length;t++)w+="0123456789ABCDEF".charAt(Math.floor(r[t]/16))+"0123456789ABCDEF".charAt(r[t]%16);return w}}}
;function ng(a,b,c){var d=String(z.location.href);return d&&a&&b?[b,og(lg(d),a,c||null)].join(" "):null}
function og(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],fb(d,function(h){e.push(h)}),pg(e.join(" "));
var f=[],g=[];fb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];fb(d,function(h){e.push(h)});
a=pg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function pg(a){var b=mg();b.update(a);return b.Oc().toLowerCase()}
;var qg={};function rg(a){this.h=a||{cookie:""}}
l=rg.prototype;l.isEnabled=function(){if(!z.navigator.cookieEnabled)return!1;if(!this.Ma())return!0;this.set("TESTCOOKIESENABLED","1",{hb:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
l.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Dr;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.hb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
l.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Mb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{hb:0,path:b,domain:c});return d};
l.xb=function(){return sg(this).keys};
l.Ma=function(){return!this.h.cookie};
l.clear=function(){for(var a=sg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function sg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Mb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var tg=new rg("undefined"==typeof document?null:document);function ug(a){return!!qg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function vg(a){a=void 0===a?!1:a;var b=z.__SAPISID||z.__APISID||z.__3PSAPISID||z.__OVERRIDE_SID;ug(a)&&(b=b||z.__1PSAPISID);if(b)return!0;var c=new rg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");ug(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function wg(a,b,c,d){(a=z[a])||(a=(new rg(document)).get(b));return a?ng(a,c,d):null}
function xg(a,b){b=void 0===b?!1:b;var c=lg(String(z.location.href)),d=[];if(vg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?z.__SAPISID:z.__APISID;e||(e=new rg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?ng(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&ug(b)&&((b=wg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=wg("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function yg(a){I.call(this,a,-1,zg)}
u(yg,I);var zg=[2];function Ag(a){this.h=this.i=this.j=a}
Ag.prototype.reset=function(){this.h=this.i=this.j};
Ag.prototype.getValue=function(){return this.i};function Bg(a){var b=[];Cg(new Dg,a,b);return b.join("")}
function Dg(){}
function Cg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Cg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Eg(d,c),c.push(":"),Cg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Eg(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Fg={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Gg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Eg(a,b){b.push('"',a.replace(Gg,function(c){var d=Fg[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Fg[c]=d);return d}),'"')}
;function Hg(){}
Hg.prototype.h=null;Hg.prototype.getOptions=function(){var a;(a=this.h)||(a={},Kg(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var Lg;function Mg(){}
Za(Mg,Hg);function Ng(a){return(a=Kg(a))?new ActiveXObject(a):new XMLHttpRequest}
function Kg(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
Lg=new Mg;function Og(a){ef.call(this);this.headers=new Map;this.K=a||null;this.i=!1;this.I=this.v=null;this.m=this.S="";this.j=this.P=this.s=this.O=!1;this.o=0;this.F=null;this.da="";this.W=this.X=!1}
Za(Og,ef);var Pg=/^https?$/i,Qg=["POST","PUT"],Rg=[];function Sg(a,b,c,d,e,f,g){var h=new Og;Rg.push(h);b&&h.ia("complete",b);h.l.add("ready",h.Mc,!0,void 0,void 0);f&&(h.o=Math.max(0,f));g&&(h.X=g);h.send(a,c,d,e)}
l=Og.prototype;l.Mc=function(){this.dispose();mb(Rg,this)};
l.send=function(a,b,c,d){if(this.v)throw Error("[goog.net.XhrIo] Object is active with another request="+this.S+"; newUri="+a);b=b?b.toUpperCase():"GET";this.S=a;this.m="";this.O=!1;this.i=!0;this.v=this.K?Ng(this.K):Ng(Lg);this.I=this.K?this.K.getOptions():Lg.getOptions();this.v.onreadystatechange=Xa(this.jc,this);try{this.getStatus(),this.P=!0,this.v.open(b,String(a),!0),this.P=!1}catch(g){this.getStatus();Tg(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=p(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=z.FormData&&a instanceof z.FormData;!(0<=eb(Qg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=p(c);for(d=b.next();!d.done;d=b.next())c=p(d.value),d=c.next().value,c=c.next().value,this.v.setRequestHeader(d,c);this.da&&(this.v.responseType=this.da);"withCredentials"in this.v&&this.v.withCredentials!==this.X&&(this.v.withCredentials=this.X);try{Ug(this),0<this.o&&(this.W=Vg(this.v),this.getStatus(),this.W?(this.v.timeout=this.o,this.v.ontimeout=Xa(this.wc,this)):
this.F=Uf(this.wc,this.o,this)),this.getStatus(),this.s=!0,this.v.send(a),this.s=!1}catch(g){this.getStatus(),Tg(this,g)}};
function Vg(a){return Lc&&Wc()&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
l.wc=function(){"undefined"!=typeof Ma&&this.v&&(this.m="Timed out after "+this.o+"ms, aborting",this.getStatus(),ff(this,"timeout"),this.abort(8))};
function Tg(a,b){a.i=!1;a.v&&(a.j=!0,a.v.abort(),a.j=!1);a.m=b;Wg(a);Xg(a)}
function Wg(a){a.O||(a.O=!0,ff(a,"complete"),ff(a,"error"))}
l.abort=function(){this.v&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.v.abort(),this.j=!1,ff(this,"complete"),ff(this,"abort"),Xg(this))};
l.C=function(){this.v&&(this.i&&(this.i=!1,this.j=!0,this.v.abort(),this.j=!1),Xg(this,!0));Og.Y.C.call(this)};
l.jc=function(){this.h()||(this.P||this.s||this.j?Yg(this):this.ed())};
l.ed=function(){Yg(this)};
function Yg(a){if(a.i&&"undefined"!=typeof Ma)if(a.I[1]&&4==Zg(a)&&2==a.getStatus())a.getStatus();else if(a.s&&4==Zg(a))Uf(a.jc,0,a);else if(ff(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if($g(a))ff(a,"complete"),ff(a,"success");else{try{var b=2<Zg(a)?a.v.statusText:""}catch(c){b=""}a.m=b+" ["+a.getStatus()+"]";Wg(a)}}finally{Xg(a)}}}
function Xg(a,b){if(a.v){Ug(a);var c=a.v,d=a.I[0]?function(){}:null;
a.v=null;a.I=null;b||ff(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Ug(a){a.v&&a.W&&(a.v.ontimeout=null);a.F&&(z.clearTimeout(a.F),a.F=null)}
l.isActive=function(){return!!this.v};
l.isComplete=function(){return 4==Zg(this)};
function $g(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=nc(1,String(a.S)),!a&&z.self&&z.self.location&&(a=z.self.location.protocol.slice(0,-1)),b=!Pg.test(a?a.toLowerCase():"");c=b}return c}
function Zg(a){return a.v?a.v.readyState:0}
l.getStatus=function(){try{return 2<Zg(this)?this.v.status:-1}catch(a){return-1}};
l.getLastError=function(){return"string"===typeof this.m?this.m:String(this.m)};function ah(a){I.call(this,a)}
u(ah,I);function bh(a){I.call(this,a,-1,ch)}
u(bh,I);var ch=[1];var dh=["platform","platformVersion","architecture","model","uaFullVersion"];new bh;function eh(a){I.call(this,a)}
u(eh,I);function fh(a){I.call(this,a,31,gh)}
u(fh,I);var gh=[3,20,27];function hh(a){I.call(this,a,17,ih)}
u(hh,I);var ih=[3,5];function jh(a){I.call(this,a,6,kh)}
u(jh,I);var kh=[5];function lh(a){I.call(this,a)}
u(lh,I);var mh;mh=new function(a,b,c){this.i=a;this.fieldName=b;this.h=c;this.isRepeated=0;this.j=oe}(175237375,{tr:0},lh);function nh(a,b,c,d,e,f,g,h,k,m,q){ef.call(this);var r=this;this.O="";this.j=[];this.Ob="";this.Pb=this.va=-1;this.Xa=!1;this.I=this.m=null;this.F=0;this.Ec=1;this.timeoutMillis=0;this.da=!1;ef.call(this);this.Ya=b||function(){};
this.s=new oh(a,f);this.Cc=d;this.Wa=q;this.Fc=Ya(kf,0,1);this.S=e||null;this.K=c||null;this.W=g||!1;this.pageId=k||null;this.logger=null;this.withCredentials=!h;this.Ia=f||!1;!this.Ia&&(65<=cc("Chromium")||45<=cc("Firefox")||12<=cc("Safari")||(Fc()||C("iPad")||C("iPod"))&&Gc());a=D(new eh,1,1);ph(this.s,a);this.o=new Ag(1E4);this.i=new Sf(this.o.getValue());ve(this,this.i);m=qh(this,m);Ue(this.i,"tick",m,!1,this);this.P=new Sf(6E5);ve(this,this.P);Ue(this.P,"tick",m,!1,this);this.W||this.P.start();
this.Ia||(Ue(document,"visibilitychange",function(){"hidden"===document.visibilityState&&r.X()}),Ue(document,"pagehide",this.X,!1,this))}
u(nh,ef);function qh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
nh.prototype.C=function(){this.X();ef.prototype.C.call(this)};
function rh(a){a.S||(a.S=.01>a.Fc()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.S}
function sh(a,b){a.o=new Ag(1>b?1:b);Tf(a.i,a.o.getValue())}
nh.prototype.log=function(a){a=a.clone();var b=this.Ec++;D(a,21,b);this.O&&D(a,26,this.O);if(!Ud(a,1)){b=a;var c=Date.now().toString();D(b,1,c)}null!=Ud(a,15,!1)||D(a,15,60*(new Date).getTimezoneOffset());this.m&&(b=this.m.clone(),G(a,yg,16,b));for(;1E3<=this.j.length;)this.j.shift(),++this.F;this.j.push(a);ff(this,new th(a));this.W||this.i.enabled||this.i.start()};
nh.prototype.flush=function(a,b){var c=this;if(0===this.j.length)a&&a();else if(this.da)uh(this);else{var d=Date.now();if(this.Pb>d&&this.va<d)b&&b("throttled");else{var e=vh(this.s,this.j,this.F);d={};var f=this.Ya();f&&(d.Authorization=f);var g=rh(this);this.K&&(d["X-Goog-AuthUser"]=this.K,g=zc(g,"authuser",this.K));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=zc(g,"pageId",this.pageId));if(f&&this.Ob===f)b&&b("stale-auth-token");else{this.j=[];this.i.enabled&&this.i.stop();this.F=0;var h=le(e),
k;this.I&&this.I.isSupported(h.length)&&(k=this.I.compress(h));var m={url:g,body:h,Kc:1,Gb:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},q=function(t){c.o.reset();Tf(c.i,c.o.getValue());if(t){var y=null;try{var E=JSON.parse(t.replace(")]}'\n",""));y=new jh(E)}catch(F){}y&&(t=Number(fe(Ud(y,1),"-1")),0<t&&(c.va=Date.now(),c.Pb=c.va+t),y=mh.j(y))&&(y=fe(Ud(y,1),-1),-1!=y&&(c.Xa||sh(c,y)))}a&&a()},r=function(t,y){var E=ae(e,fh,3),F=c.o;
F.h=Math.min(3E5,2*F.h);F.i=Math.min(3E5,F.h+Math.round(.2*(Math.random()-.5)*F.h));Tf(c.i,c.o.getValue());401===t&&f&&(c.Ob=f);void 0===y&&(y=500<=t&&600>t||401===t||0===t);y&&(c.j=E.concat(c.j),c.W||c.i.enabled||c.i.start());b&&b("net-send-failed",t)},w=function(){c.Wa?c.Wa.send(m,q,r):c.Cc(m,q,r)};
k?k.then(function(t){m.Gb["Content-Encoding"]="gzip";m.Gb["Content-Type"]="application/binary";m.body=t;m.Kc=2;w()},function(){w()}):w()}}}};
nh.prototype.X=function(){this.flush()};
function uh(a){wh(a,function(b,c){b=zc(b,"format","json");b=window.navigator.sendBeacon(b,le(c));a.da&&!b&&(a.da=!1);return b})}
function wh(a,b){if(0!==a.j.length){var c=Dc(rh(a),"format");c=uc(c,"auth",a.Ya(),"authuser",a.K||"0");for(var d=0;10>d&&a.j.length;++d){var e=a.j.slice(0,32),f=vh(a.s,e,a.F);if(!b(c,f))break;a.F=0;a.j=a.j.slice(e.length)}a.i.enabled&&a.i.stop()}}
function th(){Ce.call(this,"event-logged",void 0)}
u(th,Ce);function oh(a,b){this.i=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new hh;D(this.h,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));ph(this,new eh)}
function ph(a,b){G(a.h,eh,1,b);Ud(b,1)||D(b,1,1);a.i||(b=xh(a),Ud(b,5)||D(b,5,a.locale));a.uach&&(b=xh(a),Yd(b,bh,9)||G(b,bh,9,a.uach))}
function yh(a,b){var c=void 0===c?dh:c;b(window,c).then(function(d){a.uach=d;d=xh(a);G(d,bh,9,a.uach);return!0}).catch(function(){return!1})}
function xh(a){a=Yd(a.h,eh,1);var b=Yd(a,ah,11);b||(b=new ah,G(a,ah,11,b));return b}
function vh(a,b,c){c=void 0===c?0:c;a=a.h.clone();var d=Date.now().toString();a=D(a,4,d);b=ce(a,fh,3,b);c&&D(b,14,c);return b}
;function zh(a,b,c){Sg(a.url,function(d){d=d.target;if($g(d)){try{var e=d.v?d.v.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Gb,a.timeoutMillis,a.withCredentials)}
;function Ah(){this.j="https://play.google.com/log?format=json&hasfast=true";this.s=!1;this.m=zh;this.h=""}
;function Bh(){var a=void 0===a?"":a;var b=void 0===b?"":b;var c=new Ah;c.h="";""!=a&&(c.j=a);b&&(c.i=b);a=new nh(1828,c.I?c.I:xg,"0",c.m,c.j,c.s,!1,c.P,void 0,void 0,c.o?c.o:void 0);c.M&&ph(a.s,c.M);if(c.i){b=c.i;var d=xh(a.s);D(d,7,b)}c.l&&(a.I=c.l);c.h&&(a.O=c.h);c.B&&((b=c.B)?(a.m||(a.m=new yg),b=le(b),D(a.m,4,b)):a.m&&D(a.m,4,void 0,!1));c.K&&(d=c.K,a.m||(a.m=new yg),b=a.m,null==d?d=Kd:yd(d),D(b,2,d));c.F&&(b=c.F,a.Xa=!0,sh(a,b));c.O&&yh(a.s,c.O);this.h=a}
Bh.prototype.flush=function(a){var b=a||[];if(b.length){a=new jg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e,g=new bg;var h=D(g,1,f.i);var k=f;g=[];for(var m=0;m<k.h.length;m++)g.push(k.h[m].sb);if(null==g)g=Kd;else{for(k=0;k<g.length;k++);ud(g,5)}g=D(h,3,g);h=[];k=[];m=p(f.Ba.keys());for(var q=m.next();!q.done;q=m.next())k.push(q.value.split(","));for(m=0;m<k.length;m++){q=k[m];var r=f.l;for(var w=f.ub(q)||[],t=[],y=0;y<w.length;y++){var E=w[y];E=E&&E.Tb;var F=new gg;switch(r){case 3:Wd(F,1,
ig,Number(E));break;case 2:Wd(F,2,ig,Number(E))}t.push(F)}r=t;for(w=0;w<r.length;w++){t=r[w];y=new dg;t=G(y,gg,2,t);y=q;E=[];F=f;for(var O=[],N=0;N<F.h.length;N++)O.push(F.h[N].tb);F=O;for(O=0;O<F.length;O++){N=F[O];var Q=y[O],ca=new fg;switch(N){case 3:Wd(ca,1,hg,String(Q));break;case 2:Wd(ca,2,hg,Number(Q));break;case 1:Wd(ca,3,hg,"true"==Q)}E.push(ca)}ce(t,fg,1,E);h.push(t)}}ce(g,dg,4,h);c.push(g);e.clear()}ce(a,bg,1,c);b=this.h;a instanceof fh?b.log(a):(c=new fh,a=le(a),a=D(c,8,a),b.log(a));this.h.flush()}};function Ch(a){this.Ea=a;this.o=Dh();this.l=new Bh;this.h=new Vf(this.l);this.m=new Zf(this.h);this.i=new $f(this.h);this.j=new ag(this.h)}
function Dh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Eh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Fh(a){var b=this;this.i=!1;var c=a.program;var d=a.Vc;if(a.jd){var e;this.wa=null!=(e=a.wa)?e:new Ch(d)}var f=new Eh;this.j=f.promise;this.l=p((0,z[d].a)(c,function(g,h){Promise.resolve().then(function(){var k;if(null!=(k=b.wa)){var m=Dh()-k.o;k.m.h.pb("/client_streamz/bg/fil",m,k.Ea)}f.resolve({Ic:g,wd:h})})},!0)).next().value;
this.vd=f.promise.then(function(){})}
Fh.prototype.snapshot=function(a){var b=this;if(this.i)throw Error("Already disposed");var c=Dh(),d;null!=(d=this.wa)&&d.i.h.Lb("/client_streamz/bg/fsc",d.Ea);return this.j.then(function(e){var f=e.Ic;return new Promise(function(g){f(function(h){var k;if(null!=(k=b.wa)){var m=Dh()-c;k.j.h.pb("/client_streamz/bg/fsl",m,k.Ea)}g(h)},[a.Vb,
a.xd])})})};
Fh.prototype.uc=function(a){if(this.i)throw Error("Already disposed");var b=Dh(),c;null!=(c=this.wa)&&c.i.h.Lb("/client_streamz/bg/fsc",c.Ea);a=this.l([a.Vb,a.xd]);null!=(c=this.wa)&&(b=Dh()-b,c.j.h.pb("/client_streamz/bg/fsl",b,c.Ea));return a};
Fh.prototype.dispose=function(){var a;null!=(a=this.wa)&&a.h.qb();this.i=!0;this.j.then(function(b){(b=b.wd)&&b()})};
Fh.prototype.h=function(){return this.i};var Gh=window;Db("csi.gstatic.com");Db("googleads.g.doubleclick.net");Db("partner.googleadservices.com");Db("pubads.g.doubleclick.net");Db("securepubads.g.doubleclick.net");Db("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Hh;try{new URL("s://g"),Hh=!0}catch(a){Hh=!1}var Ih=Hh;function Jh(a,b){a.src=Kb(b);var c,d;(c=(b=null==(d=(c=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:d.call(c,"script[nonce]"))?b.nonce||b.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function Kh(a){var b=Lh;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Mh(){var a=[];Kh(function(b){a.push(b)});
return a}
var Lh={Rd:"allow-forms",Sd:"allow-modals",Td:"allow-orientation-lock",Ud:"allow-pointer-lock",Vd:"allow-popups",Wd:"allow-popups-to-escape-sandbox",Xd:"allow-presentation",Yd:"allow-same-origin",Zd:"allow-scripts",ae:"allow-top-navigation",be:"allow-top-navigation-by-user-activation"},Nh=db(function(){return Mh()});
function Oh(){var a=Ph(),b={};fb(Nh(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Ph(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Qh(a){this.bd=a}
function Rh(a){return new Qh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Sh=[Rh("data"),Rh("http"),Rh("https"),Rh("mailto"),Rh("ftp"),new Qh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Th(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Uh=(new Date).getTime();var Vh="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ia(Vh);function Wh(a){ef.call(this);var b=this;this.s=this.j=0;this.Z=null!=a?a:{U:function(e,f){return setTimeout(e,f)},
fa:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.m=function(){return x(function(e){return v(e,Xh(b),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.s||Yh(this)}
u(Wh,ef);function Zh(){var a=$h;Wh.h||(Wh.h=new Wh(a));return Wh.h}
Wh.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.Z.fa(this.s);delete Wh.h};
Wh.prototype.V=function(){return this.i};
function Yh(a){a.s=a.Z.U(function(){var b;return x(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.A(3):v(c,Xh(a),3):v(c,Xh(a),3);Yh(a);c.h=0})},3E4)}
function Xh(a,b){return a.o?a.o:a.o=new Promise(function(c){var d,e,f,g;return x(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.j=a.Z.U(function(){d.abort()},b||2E4)),v(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ba(h);a.o=void 0;a.j&&(a.Z.fa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?ff(a,"networkstatus-online"):ff(a,"networkstatus-offline"));c(g);Ca(h);break;case 2:Aa(h),g=!1,h.A(3)}})})}
;function ai(){this.data_=[];this.h=-1}
ai.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.h=-1)};
ai.prototype.get=function(a){return!!this.data_[a]};
function bi(a){-1===a.h&&(a.h=ib(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function ci(a,b){this.h=a[z.Symbol.iterator]();this.i=b}
ci.prototype[Symbol.iterator]=function(){return this};
ci.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function di(a,b){return new ci(a,b)}
;function ei(){this.blockSize=-1}
;function fi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.o=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
Za(fi,ei);fi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function gi(a,b,c){c||(c=0);var d=a.o;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+k+m+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
fi.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)gi(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){gi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){gi(this,e);f=0;break}}this.i=f;this.l+=b}};
fi.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;gi(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function hi(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function ii(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function ji(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:hi(a).match(/\S+/g)||[],b=0<=eb(a,b));return b}
function ki(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):ji(a,"inverted-hdpi")&&ii(a,Array.prototype.filter.call(a.classList?a.classList:hi(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function li(){}
li.prototype.next=function(){return mi};
var mi={done:!0,value:void 0};function ni(a){return{value:a,done:!1}}
li.prototype.ea=function(){return this};function oi(a){if(a instanceof pi||a instanceof qi||a instanceof ri)return a;if("function"==typeof a.next)return new pi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new pi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.ea)return new pi(function(){return a.ea()});
throw Error("Not an iterator or iterable.");}
function pi(a){this.i=a}
pi.prototype.ea=function(){return new qi(this.i())};
pi.prototype[Symbol.iterator]=function(){return new ri(this.i())};
pi.prototype.h=function(){return new ri(this.i())};
function qi(a){this.i=a}
u(qi,li);qi.prototype.next=function(){return this.i.next()};
qi.prototype[Symbol.iterator]=function(){return new ri(this.i)};
qi.prototype.h=function(){return new ri(this.i)};
function ri(a){pi.call(this,function(){return a});
this.j=a}
u(ri,pi);ri.prototype.next=function(){return this.j.next()};function si(a,b){this.i={};this.h=[];this.ra=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof si)for(c=a.xb(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
l=si.prototype;l.xb=function(){ti(this);return this.h.concat()};
l.has=function(a){return ui(this.i,a)};
l.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||vi;ti(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function vi(a,b){return a===b}
l.Ma=function(){return 0==this.size};
l.clear=function(){this.i={};this.ra=this.size=this.h.length=0};
l.remove=function(a){return this.delete(a)};
l.delete=function(a){return ui(this.i,a)?(delete this.i[a],--this.size,this.ra++,this.h.length>2*this.size&&ti(this),!0):!1};
function ti(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];ui(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],ui(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
l.get=function(a,b){return ui(this.i,a)?this.i[a]:b};
l.set=function(a,b){ui(this.i,a)||(this.size+=1,this.h.push(a),this.ra++);this.i[a]=b};
l.forEach=function(a,b){for(var c=this.xb(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
l.clone=function(){return new si(this)};
l.keys=function(){return oi(this.ea(!0)).h()};
l.values=function(){return oi(this.ea(!1)).h()};
l.entries=function(){var a=this;return di(this.keys(),function(b){return[b,a.get(b)]})};
l.ea=function(a){ti(this);var b=0,c=this.ra,d=this,e=new li;e.next=function(){if(c!=d.ra)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return mi;var f=d.h[b++];return ni(a?f:d.i[f])};
return e};
function ui(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function K(a){J.call(this);this.o=1;this.l=[];this.m=0;this.i=[];this.j={};this.s=!!a}
Za(K,J);l=K.prototype;l.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.o;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.o=e+3;d.push(e);return e};
function wi(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Ha(b)}}
l.Ha=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=function(){}):(c&&mb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
l.ta=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.s)for(e=0;e<c.length;e++){var g=c[e];xi(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.Ha(c)}}return 0!=e}return!1};
function xi(a,b,c){yf(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.Ha,this),delete this.j[a])}else this.i.length=0,this.j={}};
l.C=function(){K.Y.C.call(this);this.clear();this.l.length=0};function yi(a){this.h=a}
yi.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Bg(b))};
yi.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
yi.prototype.remove=function(a){this.h.remove(a)};function zi(a){this.h=a}
Za(zi,yi);function Ai(a){this.data=a}
function Bi(a){return void 0===a||a instanceof Ai?a:new Ai(a)}
zi.prototype.set=function(a,b){zi.Y.set.call(this,a,Bi(b))};
zi.prototype.i=function(a){a=zi.Y.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
zi.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Ci(a){this.h=a}
Za(Ci,zi);Ci.prototype.set=function(a,b,c){if(b=Bi(b)){if(c){if(c<Date.now()){Ci.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Ci.Y.set.call(this,a,b)};
Ci.prototype.i=function(a){var b=Ci.Y.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Ci.prototype.remove.call(this,a);else return b}};function Di(){}
;function Ei(){}
Za(Ei,Di);Ei.prototype[Symbol.iterator]=function(){return oi(this.ea(!0)).h()};
Ei.prototype.clear=function(){var a=Array.from(this);a=p(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Fi(a){this.h=a}
Za(Fi,Ei);l=Fi.prototype;l.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.h.removeItem(a)};
l.ea=function(a){var b=0,c=this.h,d=new li;d.next=function(){if(b>=c.length)return mi;var e=c.key(b++);if(a)return ni(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return ni(e)};
return d};
l.clear=function(){this.h.clear()};
l.key=function(a){return this.h.key(a)};function Gi(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
Za(Gi,Fi);function Hi(a,b){this.i=a;this.h=null;var c;if(c=Lc)c=!(9<=Number(Zc));if(c){Ii||(Ii=new si);this.h=Ii.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Ii.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
Za(Hi,Ei);var Ji={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Ii=null;function Ki(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Ji[b]})}
l=Hi.prototype;l.isAvailable=function(){return!!this.h};
l.set=function(a,b){this.h.setAttribute(Ki(a),b);Li(this)};
l.get=function(a){a=this.h.getAttribute(Ki(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.h.removeAttribute(Ki(a));Li(this)};
l.ea=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new li;d.next=function(){if(b>=c.length)return mi;var e=c[b++];if(a)return ni(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return ni(e)};
return d};
l.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Li(this)};
function Li(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Mi(a,b){this.i=a;this.h=b+"::"}
Za(Mi,Ei);Mi.prototype.set=function(a,b){this.i.set(this.h+a,b)};
Mi.prototype.get=function(a){return this.i.get(this.h+a)};
Mi.prototype.remove=function(a){this.i.remove(this.h+a)};
Mi.prototype.ea=function(a){var b=this.i[Symbol.iterator](),c=this,d=new li;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return ni(a?e.slice(c.h.length):c.i.get(e))};
return d};function Ni(a){I.call(this,a)}
u(Ni,I);function Oi(a){I.call(this,a)}
u(Oi,I);Oi.prototype.getKey=function(){return Ud(this,1)};
Oi.prototype.getValue=function(){return ee(this,2===Xd(this,Pi)?2:-1)};
var Pi=[2,3,4,5,6];function Qi(a){I.call(this,a)}
u(Qi,I);function Ri(a){I.call(this,a)}
u(Ri,I);function Si(a){I.call(this,a,-1,Ti)}
u(Si,I);var Ti=[2];function Ui(a){I.call(this,a,-1,Vi)}
u(Ui,I);Ui.prototype.getPlayerType=function(){return Ud(this,36)};
Ui.prototype.setHomeGroupInfo=function(a){return G(this,Si,81,a)};
Ui.prototype.clearLocationPlayabilityToken=function(){return D(this,89,void 0,!1)};
var Vi=[9,66,24,32,86,100,101];function Wi(a){I.call(this,a,-1,Xi)}
u(Wi,I);var Xi=[15,26,28];function Yi(a){I.call(this,a)}
u(Yi,I);function Zi(a){I.call(this,a,-1,$i)}
u(Zi,I);Zi.prototype.setSafetyMode=function(a){return D(this,5,a)};
var $i=[12];function aj(a){I.call(this,a,-1,bj)}
u(aj,I);aj.prototype.i=function(a){G(this,Ui,1,a)};
var bj=[12];function cj(a){this.name=a}
;var dj=new cj("continuationCommand");var ej=new cj("webCommandMetadata");var fj=new cj("signalServiceEndpoint");var gj={si:"EMBEDDED_PLAYER_MODE_UNKNOWN",ni:"EMBEDDED_PLAYER_MODE_DEFAULT",ri:"EMBEDDED_PLAYER_MODE_PFP",oi:"EMBEDDED_PLAYER_MODE_PFL"};var hj=new cj("feedbackEndpoint");var ij={Mq:"WEB_DISPLAY_MODE_UNKNOWN",Iq:"WEB_DISPLAY_MODE_BROWSER",Kq:"WEB_DISPLAY_MODE_MINIMAL_UI",Lq:"WEB_DISPLAY_MODE_STANDALONE",Jq:"WEB_DISPLAY_MODE_FULLSCREEN"};function jj(a){I.call(this,a,-1,kj)}
u(jj,I);function lj(a){I.call(this,a)}
u(lj,I);lj.prototype.getKey=function(){return fe(Ud(this,1),"")};
lj.prototype.getValue=function(){return fe(Ud(this,2),"")};
var kj=[4,5];function mj(a){I.call(this,a)}
u(mj,I);function nj(a){I.call(this,a)}
u(nj,I);var oj=[2,3,4];function pj(a){I.call(this,a)}
u(pj,I);pj.prototype.getMessage=function(){return fe(Ud(this,1),"")};function qj(a){I.call(this,a)}
u(qj,I);function rj(a){I.call(this,a)}
u(rj,I);function sj(a){I.call(this,a,-1,tj)}
u(sj,I);var tj=[10,17];function uj(a){I.call(this,a)}
u(uj,I);function vj(a){I.call(this,a)}
u(vj,I);function wj(a){I.call(this,a)}
u(wj,I);function xj(a){I.call(this,a)}
u(xj,I);function yj(a){I.call(this,a)}
u(yj,I);function zj(a,b){G(a,wj,1,b)}
yj.prototype.i=function(a){D(this,2,a)};
function Aj(a){I.call(this,a)}
u(Aj,I);function Bj(a,b){G(a,wj,1,b)}
;function Cj(a){I.call(this,a,-1,Dj)}
u(Cj,I);Cj.prototype.i=function(a){D(this,1,a)};
function Ej(a,b){G(a,wj,2,b)}
var Dj=[3];function Fj(a){I.call(this,a)}
u(Fj,I);Fj.prototype.i=function(a){D(this,1,a)};function Gj(a){I.call(this,a)}
u(Gj,I);Gj.prototype.i=function(a){D(this,1,a)};function Hj(a){I.call(this,a)}
u(Hj,I);Hj.prototype.i=function(a){D(this,1,a)};function Ij(a){I.call(this,a)}
u(Ij,I);Ij.prototype.i=function(a){D(this,1,a)};function Jj(a){I.call(this,a)}
u(Jj,I);function Kj(a){I.call(this,a)}
u(Kj,I);function Lj(a){I.call(this,a,-1,Mj)}
u(Lj,I);Lj.prototype.getPlayerType=function(){var a=Ud(this,7);return null==a?0:a};
Lj.prototype.setVideoId=function(a){return D(this,19,a)};
function Nj(a,b){de(a,68,ik,b)}
function ik(a){I.call(this,a)}
u(ik,I);ik.prototype.getId=function(){return fe(Ud(this,2),"")};
var Mj=[83,68];function jk(a){I.call(this,a)}
u(jk,I);function kk(a){I.call(this,a)}
u(kk,I);function lk(a){I.call(this,a)}
u(lk,I);function mk(a){I.call(this,a,449)}
u(mk,I);
var nk=[23,24,11,6,7,5,2,3,13,20,21,22,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,148,151,157,158,159,163,164,168,444,176,222,383,177,178,179,411,184,188,189,190,191,193,194,195,196,197,198,199,200,201,402,320,203,204,205,206,258,259,260,261,327,209,219,226,227,232,233,234,240,244,247,248,249,251,256,257,266,254,255,270,272,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,334,337,338,340,344,348,350,351,
352,353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,388,389,403,410,412,429,413,414,415,416,417,418,430,423,424,425,426,427,431,117,439,441,448];var ok={sj:0,dj:1,jj:2,kj:4,pj:8,lj:16,mj:32,rj:64,qj:128,fj:256,hj:512,oj:1024,gj:2048,ij:4096,ej:8192,nj:16384};function pk(a){I.call(this,a)}
u(pk,I);function qk(a){I.call(this,a)}
u(qk,I);qk.prototype.setVideoId=function(a){return Wd(this,1,rk,a)};
qk.prototype.getPlaylistId=function(){return ee(this,2===Xd(this,rk)?2:-1)};
var rk=[1,2];function sk(a){I.call(this,a,-1,tk)}
u(sk,I);var tk=[3];var uk=new cj("webPlayerShareEntityServiceEndpoint");var vk=new cj("playlistEditEndpoint");var wk=new cj("modifyChannelNotificationPreferenceEndpoint");var xk=new cj("unsubscribeEndpoint");var yk=new cj("subscribeEndpoint");function zk(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Ak=z.window,Bk,Ck,Dk=(null==Ak?void 0:null==(Bk=Ak.yt)?void 0:Bk.config_)||(null==Ak?void 0:null==(Ck=Ak.ytcfg)?void 0:Ck.data_)||{};A("yt.config_",Dk);function Ek(){zk(Dk,arguments)}
function L(a,b){return a in Dk?Dk[a]:b}
function Fk(){var a=Dk.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;function M(a){a=Gk(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Hk(a,b){a=Gk(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function Ik(){return L("EXPERIMENTS_TOKEN","")}
function Gk(a){var b=L("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:L("EXPERIMENT_FLAGS",{})[a]}
function Jk(){var a=[],b=L("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=L("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var Kk=[];function Lk(a){Kk.forEach(function(b){return b(a)})}
function Mk(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Nk(b)}}:a}
function Nk(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=L("ERRORS",[]),e.push([a,"ERROR",b,c,d]),Ek("ERRORS",e));Lk(a)}
function Ok(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=L("ERRORS",[]),e.push([a,"WARNING",b,c,d]),Ek("ERRORS",e))}
;function Pk(){var a=Qk;B("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a)}
function Rk(a){A("yt.ads.biscotti.lastId_",a)}
;var Sk=/^[\w.]*$/,Tk={q:!0,search_query:!0};function Uk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Vk(f[0]||""),h=Vk(f[1]||"");g in c?Array.isArray(c[g])?nb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(r){var k=r,m=f[0],q=String(Uk);k.args=[{key:m,value:f[1],query:a,method:Wk==q?"unchanged":q}];Tk.hasOwnProperty(m)||Ok(k)}}return c}
var Wk=String(Uk);function Xk(a){var b=[];ob(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];fb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Yk(a){"?"==a.charAt(0)&&(a=a.substr(1));return Uk(a,"&")}
function Zk(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Yk(1<a.length?a[1]:a[0])):{}}
function $k(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Yk(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return vc(a,e)+d}
function al(a){if(!b)var b=window.location.href;var c=nc(1,a),d=oc(a);c&&d?(a=a.match(lc),b=b.match(lc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?oc(b)==d&&(Number(nc(4,b))||null)==(Number(nc(4,a))||null):!0;return a}
function Vk(a){return a&&a.match(Sk)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function bl(a){var b=cl;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Uh;e.flash="0";a:{try{var f=b.h.top.location.href}catch(fa){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Gh:g;try{var h=g.history.length}catch(fa){h=0}e.u_his=h;var k;e.u_h=null==(k=Gh.screen)?void 0:k.height;var m;e.u_w=null==(m=Gh.screen)?void 0:m.width;var q;e.u_ah=null==(q=Gh.screen)?void 0:q.availHeight;var r;e.u_aw=
null==(r=Gh.screen)?void 0:r.availWidth;var w;e.u_cd=null==(w=Gh.screen)?void 0:w.colorDepth}catch(fa){}h=b.h;try{var t=h.screenX;var y=h.screenY}catch(fa){}try{var E=h.outerWidth;var F=h.outerHeight}catch(fa){}try{var O=h.innerWidth;var N=h.innerHeight}catch(fa){}try{var Q=h.screenLeft;var ca=h.screenTop}catch(fa){}try{O=h.innerWidth,N=h.innerHeight}catch(fa){}try{var U=h.screen.availWidth;var lb=h.screen.availTop}catch(fa){}t=[Q,ca,t,y,U,lb,E,F,O,N];try{var Wa=(b.h.top||window).document,na="CSS1Compat"==
Wa.compatMode?Wa.documentElement:Wa.body;var H=(new mf(na.clientWidth,na.clientHeight)).round()}catch(fa){H=new mf(-12245933,-12245933)}Wa=H;H={};var la=void 0===la?z:la;na=new ai;la.SVGElement&&la.document.createElementNS&&na.set(0);y=Oh();y["allow-top-navigation-by-user-activation"]&&na.set(1);y["allow-popups-to-escape-sandbox"]&&na.set(2);la.crypto&&la.crypto.subtle&&na.set(3);la.TextDecoder&&la.TextEncoder&&na.set(4);la=bi(na);H.bc=la;H.bih=Wa.height;H.biw=Wa.width;H.brdim=t.join();b=b.i;b=(H.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,H.wgl=!!Gh.WebGLRenderingContext,H);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var cl=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return Xk(bl(a))});Date.now();var dl="XMLHttpRequest"in z?function(){return new XMLHttpRequest}:null;
function el(){if(!dl)return null;var a=dl();return"open"in a?a:null}
function fl(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function gl(a,b){"function"===typeof a&&(a=Mk(a));return window.setTimeout(a,b)}
;var hl={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},il="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(Vh)),jl=!1;
function kl(a,b){b=void 0===b?{}:b;var c=al(a),d=M("web_ajax_ignore_global_headers_if_set"),e;for(e in hl){var f=L(hl[e]);"X-Goog-Visitor-Id"!==e||f||(f=L("VISITOR_DATA"));!f||!c&&oc(a)||d&&void 0!==b[e]||(b[e]=f)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!oc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!oc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}document.location.hostname.endsWith("youtubeeducation.com")||
!c&&oc(a)||(b["X-YouTube-Ad-Signals"]=Xk(bl()));return b}
function ll(a){var b=window.location.search,c=oc(a);M("debug_handle_relative_url_for_query_forward_killswitch")||!c&&al(a)&&(c=document.location.hostname);var d=mc(nc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Yk(b),f={};fb(il,function(g){e[g]&&(f[g]=e[g])});
return $k(a,f||{},!1)}
function ml(a,b){var c=b.format||"JSON";a=nl(a,b);var d=ol(a,b),e=!1,f=pl(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var m=fl(k),q=null,r=400<=k.status&&500>k.status,w=500<=k.status&&600>k.status;if(m||r||w)q=ql(a,c,k,b.convertToSafeHtml);if(m)a:if(k&&204==k.status)m=!0;else{switch(c){case "XML":m=0==parseInt(q&&q.return_code,10);break a;case "RAW":m=!0;break a}m=!!q}q=q||{};r=b.context||z;m?b.onSuccess&&b.onSuccess.call(r,k,q):b.onError&&b.onError.call(r,k,q);b.onFinish&&b.onFinish.call(r,
k,q)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=gl(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||z,f))},d)}return f}
function nl(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=L("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=$k(a,b||{},!0);return a}
function ol(a,b){var c=L("XSRF_FIELD_NAME"),d=L("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=L("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||oc(a)&&!b.withCredentials&&oc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(M("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=Yk(e),yb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):tc(e));f=e||f&&!rb(f);!jl&&f&&"POST"!=b.method&&(jl=!0,Nk(Error("AJAX request with postData should use POST")));return e}
function ql(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Ok(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?rl(a):null)e={},fb(a.getElementsByTagName("*"),function(g){e[g.tagName]=sl(g)})}d&&tl(e);
return e}
function tl(a){if(Qa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;Db("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=a[b],e=Ab();d=e?e.createHTML(d):d;a[c]=new ec(d)}else tl(a[b])}}
function rl(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function sl(a){var b="";fb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function pl(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Mk(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=el();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;M("debug_forward_web_query_parameters")&&(a=ll(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=kl(a,e))for(var m in e)k.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;function ul(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function vl(){if(!z.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return z.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":z.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":z.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":z.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function wl(a,b,c,d,e){tg.set(""+a,b,{hb:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function xl(a,b,c){tg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function yl(){if(!tg.isEnabled())return!1;if(!tg.Ma())return!0;tg.set("TESTCOOKIESENABLED","1",{hb:60});if("1"!==tg.get("TESTCOOKIESENABLED"))return!1;tg.remove("TESTCOOKIESENABLED");return!0}
;var zl=B("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",zl);function Al(){this.h=L("ALT_PREF_COOKIE_NAME","PREF");this.i=L("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=tg.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(zl[d]=c.toString())}}}
Al.prototype.get=function(a,b){Bl(a);Cl(a);a=void 0!==zl[a]?zl[a].toString():null;return null!=a?a:b?b:""};
Al.prototype.set=function(a,b){Bl(a);Cl(a);if(null==b)throw Error("ExpectedNotNull");zl[a]=b.toString()};
function Dl(a){return!!((El("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
Al.prototype.remove=function(a){Bl(a);Cl(a);delete zl[a]};
Al.prototype.clear=function(){for(var a in zl)delete zl[a]};
function Cl(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Bl(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function El(a){a=void 0!==zl[a]?zl[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Na(Al);var Fl={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Gl={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},Hl={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},Il={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Jl(){var a=z.navigator;return a?a.connection:void 0}
function Kl(){var a=Jl();if(a){var b=Fl[a.type||"unknown"]||"CONN_UNKNOWN";a=Fl[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Ll(){var a=Jl();if(null!=a&&a.effectiveType)return Il.hasOwnProperty(a.effectiveType)?Il[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function Ml(){}
function Nl(a,b){return Ol(a,0,b)}
Ml.prototype.U=function(a,b){return Ol(a,1,b)};
function Pl(a,b){Ol(a,2,b)}
function Ql(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function Rl(){Ml.apply(this,arguments)}
u(Rl,Ml);function Sl(){Rl.h||(Rl.h=new Rl);return Rl.h}
function Ol(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):gl(a,c||0)}
Rl.prototype.fa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
Rl.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
Rl.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};var $h=Sl();function P(a){var b=Ja.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
u(P,Error);function Tl(){try{return Ul(),!0}catch(a){return!1}}
function Ul(a){if(void 0!==L("DATASYNC_ID"))return L("DATASYNC_ID");throw new P("Datasync ID not set",void 0===a?"unknown":a);}
;var Vl=$c||ad;function Wl(a){var b=Tb();return b?0<=b.toLowerCase().indexOf(a):!1}
;function Xl(a){var b=new Gi;(b=b.isAvailable()?a?new Mi(b,a):b:null)||(a=new Hi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Ci(a):null;this.i=document.domain||window.location.hostname}
Xl.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Bg(b))}catch(f){return}else e=escape(b);wl(a,e,c,this.i)};
Xl.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=tg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Xl.prototype.remove=function(a){this.h&&this.h.remove(a);xl(a,"/",this.i)};var Yl=function(){var a;return function(){a||(a=new Xl("ytidb"));return a}}();
function Zl(){var a;return null==(a=Yl())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var $l=[],am,bm=!1;function cm(){var a={};for(am=new dm(void 0===a.handleError?em:a.handleError,void 0===a.logEvent?fm:a.logEvent);0<$l.length;)switch(a=$l.shift(),a.type){case "ERROR":am.handleError(a.payload);break;case "EVENT":am.logEvent(a.eventType,a.payload)}}
function gm(a){bm||(am?am.handleError(a):($l.push({type:"ERROR",payload:a}),10<$l.length&&$l.shift()))}
function hm(a,b){bm||(am?am.logEvent(a,b):($l.push({type:"EVENT",eventType:a,payload:b}),10<$l.length&&$l.shift()))}
;function im(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function jm(a){return a.substr(0,a.indexOf(":"))||a}
;var km={},lm=(km.AUTH_INVALID="No user identifier specified.",km.EXPLICIT_ABORT="Transaction was explicitly aborted.",km.IDB_NOT_SUPPORTED="IndexedDB is not supported.",km.MISSING_INDEX="Index not created.",km.MISSING_OBJECT_STORES="Object stores not created.",km.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",km.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",km.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
km.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",km.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",km.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",km.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",km),mm={},nm=(mm.AUTH_INVALID="ERROR",mm.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",mm.EXPLICIT_ABORT="IGNORED",mm.IDB_NOT_SUPPORTED="ERROR",mm.MISSING_INDEX=
"WARNING",mm.MISSING_OBJECT_STORES="ERROR",mm.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",mm.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",mm.QUOTA_EXCEEDED="WARNING",mm.QUOTA_MAYBE_EXCEEDED="WARNING",mm.UNKNOWN_ABORT="WARNING",mm.INCOMPATIBLE_DB_VERSION="WARNING",mm),om={},pm=(om.AUTH_INVALID=!1,om.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,om.EXPLICIT_ABORT=!1,om.IDB_NOT_SUPPORTED=!1,om.MISSING_INDEX=!1,om.MISSING_OBJECT_STORES=!1,om.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,om.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,om.QUOTA_EXCEEDED=!1,om.QUOTA_MAYBE_EXCEEDED=!0,om.UNKNOWN_ABORT=!0,om.INCOMPATIBLE_DB_VERSION=!1,om);function qm(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?lm[a]:c;d=void 0===d?nm[a]:d;e=void 0===e?pm[a]:e;P.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,qm.prototype)}
u(qm,P);function rm(a,b){qm.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},lm.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,rm.prototype)}
u(rm,qm);function sm(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,sm.prototype)}
u(sm,Error);var tm=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function um(a,b,c,d){b=jm(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof qm)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new qm("QUOTA_EXCEEDED",a);if(bd&&"UnknownError"===e.name)return new qm("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof sm)return new qm("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&tm.some(function(f){return e.message.includes(f)}))return new qm("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new qm("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",kc:e.name})];e.level="WARNING";return e}
function vm(a,b,c){var d=Zl();return new qm("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function wm(a){if(!a)throw Error();throw a;}
function xm(a){return a}
function ym(a){this.h=a}
function zm(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=p(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=p(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
zm.all=function(a){return new zm(new ym(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={Aa:0};f.Aa<a.length;f={Aa:f.Aa},++f.Aa)zm.resolve(a[f.Aa]).then(function(g){return function(h){d[g.Aa]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
zm.resolve=function(a){return new zm(new ym(function(b,c){a instanceof zm?a.then(b,c):b(a)}))};
zm.reject=function(a){return new zm(new ym(function(b,c){c(a)}))};
zm.prototype.then=function(a,b){var c=this,d=null!=a?a:xm,e=null!=b?b:wm;return new zm(new ym(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Am(c,c,d,f,g)}),c.i.push(function(){Bm(c,c,e,f,g)})):"FULFILLED"===c.state.status?Am(c,c,d,f,g):"REJECTED"===c.state.status&&Bm(c,c,e,f,g)}))};
zm.prototype.catch=function(a){return this.then(void 0,a)};
function Am(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof zm?Cm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Bm(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof zm?Cm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Cm(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof zm?Cm(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Dm(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Em(a){return new Promise(function(b,c){Dm(a,b,c)})}
function Fm(a){return new zm(new ym(function(b,c){Dm(a,b,c)}))}
;function Gm(a,b){return new zm(new ym(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Hm=window,R=Hm.ytcsi&&Hm.ytcsi.now?Hm.ytcsi.now:Hm.performance&&Hm.performance.timing&&Hm.performance.now&&Hm.performance.timing.navigationStart?function(){return Hm.performance.timing.navigationStart+Hm.performance.now()}:function(){return(new Date).getTime()};function Im(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(R());this.i=!1}
l=Im.prototype;l.add=function(a,b,c){return Jm(this,[a],{mode:"readwrite",T:!0},function(d){return d.objectStore(a).add(b,c)})};
l.clear=function(a){return Jm(this,[a],{mode:"readwrite",T:!0},function(b){return b.objectStore(a).clear()})};
l.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
l.count=function(a,b){return Jm(this,[a],{mode:"readonly",T:!0},function(c){return c.objectStore(a).count(b)})};
function Km(a,b,c){a=a.h.createObjectStore(b,c);return new Lm(a)}
l.delete=function(a,b){return Jm(this,[a],{mode:"readwrite",T:!0},function(c){return c.objectStore(a).delete(b)})};
l.get=function(a,b){return Jm(this,[a],{mode:"readonly",T:!0},function(c){return c.objectStore(a).get(b)})};
function Mm(a,b){return Jm(a,["LogsRequestsStore"],{mode:"readwrite",T:!0},function(c){c=c.objectStore("LogsRequestsStore");return Fm(c.h.put(b,void 0))})}
l.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Jm(a,b,c,d){var e,f,g,h,k,m,q,r,w,t,y,E;return x(function(F){switch(F.h){case 1:var O={mode:"readonly",T:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?O.mode=c:Object.assign(O,c);e=O;a.transactionCount++;f=e.T?3:1;g=0;case 2:if(h){F.A(3);break}g++;k=Math.round(R());ya(F,4);m=a.h.transaction(b,e.mode);O=new Nm(m);O=Om(O,d);return v(F,O,6);case 6:return q=F.i,r=Math.round(R()),Pm(a,k,r,g,void 0,b.join(),e),F.return(q);case 4:w=Aa(F);t=Math.round(R());y=um(w,a.h.name,b.join(),a.h.version);
if((E=y instanceof qm&&!y.h)||g>=f)Pm(a,k,t,g,y,b.join(),e),h=y;F.A(2);break;case 3:return F.return(Promise.reject(h))}})}
function Pm(a,b,c,d,e,f,g){b=c-b;e?(e instanceof qm&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&hm("QUOTA_EXCEEDED",{dbName:jm(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof qm&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),hm("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Qm(a,!1,d,f,b,g.tag),gm(e)):Qm(a,!0,d,f,b,g.tag)}
function Qm(a,b,c,d,e,f){hm("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
l.getName=function(){return this.h.name};
function Lm(a){this.h=a}
l=Lm.prototype;l.add=function(a,b){return Fm(this.h.add(a,b))};
l.autoIncrement=function(){return this.h.autoIncrement};
l.clear=function(){return Fm(this.h.clear()).then(function(){})};
l.count=function(a){return Fm(this.h.count(a))};
function Rm(a,b){return Sm(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
l.delete=function(a){return a instanceof IDBKeyRange?Rm(this,a):Fm(this.h.delete(a))};
l.get=function(a){return Fm(this.h.get(a))};
l.index=function(a){try{return new Tm(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new sm(a,this.h.name);throw b;}};
l.getName=function(){return this.h.name};
l.keyPath=function(){return this.h.keyPath};
function Sm(a,b,c){a=a.h.openCursor(b.query,b.direction);return Um(a).then(function(d){return Gm(d,c)})}
function Nm(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=qm;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Om(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return p(d).next().value})}
Nm.prototype.abort=function(){this.h.abort();this.i=!0;throw new qm("EXPLICIT_ABORT");};
Nm.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new Lm(a),this.j.set(a,b));return b};
function Tm(a){this.h=a}
l=Tm.prototype;l.count=function(a){return Fm(this.h.count(a))};
l.delete=function(a){return Vm(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
l.get=function(a){return Fm(this.h.get(a))};
l.getKey=function(a){return Fm(this.h.getKey(a))};
l.keyPath=function(){return this.h.keyPath};
l.unique=function(){return this.h.unique};
function Vm(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Um(a).then(function(d){return Gm(d,c)})}
function Wm(a,b){this.request=a;this.cursor=b}
function Um(a){return Fm(a).then(function(b){return b?new Wm(a,b):null})}
l=Wm.prototype;l.advance=function(a){this.cursor.advance(a);return Um(this.request)};
l.continue=function(a){this.cursor.continue(a);return Um(this.request)};
l.delete=function(){return Fm(this.cursor.delete()).then(function(){})};
l.getKey=function(){return this.cursor.key};
l.getValue=function(){return this.cursor.value};
l.update=function(a){return Fm(this.cursor.update(a))};function Xm(a,b,c){return new Promise(function(d,e){function f(){w||(w=new Im(g.result,{closed:r}));return w}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Jc,k=c.blocking,m=c.zd,q=c.upgrade,r=c.closed,w;g.addEventListener("upgradeneeded",function(t){try{if(null===t.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&"none"!==t.dataLoss&&hm("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:jm(a)});var y=f(),E=new Nm(g.transaction);
q&&q(y,function(F){return t.oldVersion<F&&t.newVersion>=F},E);
E.done.catch(function(F){e(F)})}catch(F){e(F)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){hm("IDB_UNEXPECTEDLY_CLOSED",{dbName:jm(a),dbVersion:t.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Ym(a,b,c){c=void 0===c?{}:c;return Xm(a,b,c)}
function Zm(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.h)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Jc)&&c.addEventListener("blocked",function(){e()}),v(g,Em(c),4);
if(2!=g.h)return za(g,0);f=Aa(g);throw um(f,a,"",-1);})}
;function $m(a){return new Promise(function(b){Pl(function(){b()},a)})}
function an(a,b){this.name=a;this.options=b;this.l=!0;this.o=this.m=0;this.i=500}
an.prototype.j=function(a,b,c){c=void 0===c?{}:c;return Ym(a,b,c)};
an.prototype.delete=function(a){a=void 0===a?{}:a;return Zm(this.name,a)};
function bn(a,b){return new qm("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function cn(a,b){if(!b)throw vm("openWithToken",jm(a.name));return dn(a)}
function dn(a){function b(){var f,g,h,k,m,q,r,w,t,y;return x(function(E){switch(E.h){case 1:return g=null!=(f=Error().stack)?f:"",ya(E,2),v(E,a.j(a.name,a.options.version,d),4);case 4:h=E.i;for(var F=a.options,O=[],N=p(Object.keys(F.Na)),Q=N.next();!Q.done;Q=N.next()){Q=Q.value;var ca=F.Na[Q],U=void 0===ca.kd?Number.MAX_VALUE:ca.kd;!(h.h.version>=ca.rb)||h.h.version>=U||h.h.objectStoreNames.contains(Q)||O.push(Q)}k=O;if(0===k.length){E.A(5);break}m=Object.keys(a.options.Na);q=h.objectStoreNames();
if(a.o<Hk("ytidb_reopen_db_retries",0))return a.o++,h.close(),gm(new qm("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),E.return(b());if(!(a.m<Hk("ytidb_remake_db_retries",1))){E.A(6);break}a.m++;if(!M("ytidb_remake_db_enable_backoff_delay")){E.A(7);break}return v(E,$m(a.i),8);case 8:a.i*=2;case 7:return v(E,a.delete(),9);case 9:return gm(new qm("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),E.return(b());
case 6:throw new rm(q,m);case 5:return E.return(h);case 2:r=Aa(E);if(r instanceof DOMException?"VersionError"!==r.name:"DOMError"in self&&r instanceof DOMError?"VersionError"!==r.name:!(r instanceof Object&&"message"in r)||"An attempt was made to open a database using a lower version than the existing version."!==r.message){E.A(10);break}return v(E,a.j(a.name,void 0,Object.assign({},d,{upgrade:void 0})),11);case 11:w=E.i;t=w.h.version;if(void 0!==a.options.version&&t>a.options.version+1)throw w.close(),
a.l=!1,bn(a,t);return E.return(w);case 10:throw c(),r instanceof Error&&!M("ytidb_async_stack_killswitch")&&(r.stack=r.stack+"\n"+g.substring(g.indexOf("\n")+1)),um(r,a.name,"",null!=(y=a.options.version)?y:-1);}})}
function c(){a.h===e&&(a.h=void 0)}
if(!a.l)throw bn(a);if(a.h)return a.h;var d={blocking:function(f){f.close()},
closed:c,zd:c,upgrade:a.options.upgrade};var e=b();a.h=e;return a.h}
;var en=new an("YtIdbMeta",{Na:{databases:{rb:1}},upgrade:function(a,b){b(1)&&Km(a,"databases",{keyPath:"actualName"})}});
function fn(a,b){var c;return x(function(d){if(1==d.h)return v(d,cn(en,b),2);c=d.i;return d.return(Jm(c,["databases"],{T:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Fm(f.h.put(a,void 0)).then(function(){})})}))})}
function gn(a,b){var c;return x(function(d){if(1==d.h)return a?v(d,cn(en,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function hn(a,b){var c,d;return x(function(e){return 1==e.h?(c=[],v(e,cn(en,b),2)):3!=e.h?(d=e.i,v(e,Jm(d,["databases"],{T:!0,mode:"readonly"},function(f){c.length=0;return Sm(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function jn(a){return hn(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function kn(a,b,c){return hn(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function ln(a){var b,c;return x(function(d){if(1==d.h)return b=Ul("YtIdbMeta hasAnyMeta other"),v(d,hn(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var mn,nn=new function(){}(new function(){});
function on(){var a,b,c,d;return x(function(e){switch(e.h){case 1:a=Zl();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=Vl)f=/WebKit\/([0-9]+)/.exec(Tb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Tb()),f=!(f&&602<=parseInt(f[1],10)));if(f||Mc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return v(e,fn(d,nn),4);case 4:return v(e,gn("yt-idb-test-do-not-use",nn),5);case 5:return e.return(!0);case 2:return Aa(e),e.return(!1)}})}
function pn(){if(void 0!==mn)return mn;bm=!0;return mn=on().then(function(a){bm=!1;var b;if(null!=(b=Yl())&&b.h){var c;b={hasSucceededOnce:(null==(c=Zl())?void 0:c.hasSucceededOnce)||a};var d;null==(d=Yl())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function qn(){var a=B("ytglobal.idbToken_")||void 0;return a?Promise.resolve(a):pn().then(function(b){(b=b?nn:void 0)&&A("ytglobal.idbToken_",b);return b})}
;var rn=0;function sn(a,b){rn||(rn=$h.U(function(){var c,d,e,f,g;return x(function(h){switch(h.h){case 1:return v(h,qn(),2);case 2:c=h.i;if(!c)return h.return();d=!0;ya(h,3);return v(h,kn(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return v(h,Zm(f.actualName),7);case 7:return v(h,gn(f.actualName,c),6);case 6:za(h,4);break;case 3:g=Aa(h),gm(g),d=!1;case 4:$h.fa(rn),rn=0,d&&sn(a,b),h.h=0}})}))}
function tn(){var a;return x(function(b){return 1==b.h?v(b,qn(),2):(a=b.i)?b.return(ln(a)):b.return(!1)})}
new Eh;function un(a){if(!Tl())throw a=new qm("AUTH_INVALID",{dbName:a}),gm(a),a;var b=Ul();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function vn(a,b,c,d){var e,f,g,h,k,m;return x(function(q){switch(q.h){case 1:return f=null!=(e=Error().stack)?e:"",v(q,qn(),2);case 2:g=q.i;if(!g)throw h=vm("openDbImpl",a,b),M("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),gm(h),h;im(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:un(a);ya(q,3);return v(q,fn(k,g),5);case 5:return v(q,Ym(k.actualName,b,d),6);case 6:return q.return(q.i);case 3:return m=Aa(q),ya(q,7),v(q,gn(k.actualName,g),9);case 9:za(q,
8);break;case 7:Aa(q);case 8:throw m;}})}
function wn(a,b,c){c=void 0===c?{}:c;return vn(a,b,!1,c)}
function xn(a,b,c){c=void 0===c?{}:c;return vn(a,b,!0,c)}
function yn(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.h)return v(e,qn(),2);if(3!=e.h){c=e.i;if(!c)return e.return();im(a);d=un(a);return v(e,Zm(d.actualName,b),3)}return v(e,gn(d.actualName,c),0)})}
function zn(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.h?v(e,Zm(d.actualName,b),2):v(e,gn(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function An(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.h)return v(d,qn(),2);if(3!=d.h){b=d.i;if(!b)return d.return();im("LogsDatabaseV2");return v(d,jn(b),3)}c=d.i;return v(d,zn(c,a,b),0)})}
function Bn(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.h)return v(d,qn(),2);if(3!=d.h){c=d.i;if(!c)return d.return();im(a);return v(d,Zm(a,b),3)}return v(d,gn(a,c),0)})}
;function Cn(a,b){an.call(this,a,b);this.options=b;im(a)}
u(Cn,an);function Dn(a,b){var c;return function(){c||(c=new Cn(a,b));return c}}
Cn.prototype.j=function(a,b,c){c=void 0===c?{}:c;return(this.options.Jb?xn:wn)(a,b,Object.assign({},c))};
Cn.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Jb?Bn:yn)(this.name,a)};
function En(a,b){return Dn(a,b)}
;function Fn(){}
;function Gn(){return"INNERTUBE_API_KEY"in Dk&&"INNERTUBE_API_VERSION"in Dk}
function Hn(){return{innertubeApiKey:L("INNERTUBE_API_KEY"),innertubeApiVersion:L("INNERTUBE_API_VERSION"),yb:L("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),dc:L("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Wc:L("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:L("INNERTUBE_CONTEXT_CLIENT_VERSION"),fc:L("INNERTUBE_CONTEXT_HL"),ec:L("INNERTUBE_CONTEXT_GL"),Xc:L("INNERTUBE_HOST_OVERRIDE")||"",Zc:!!L("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Yc:!!L("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:L("SERIALIZED_CLIENT_CONFIG_DATA")}}
function In(a){var b={client:{hl:a.fc,gl:a.ec,clientName:a.dc,clientVersion:a.innertubeContextClientVersion,configInfo:a.yb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=z.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=Ik();""!==c&&(b.client.experimentsToken=c);c=Jk();0<c.length&&(b.request={internalExperimentFlags:c});Jn(a,void 0,b);Kn(void 0,b);Ln(a,void 0,b);Mn(void 0,b);M("start_sending_config_hash")&&Nn(void 0,b);L("DELEGATED_SESSION_ID")&&
!M("pageid_as_header_web")&&(b.user={onBehalfOfUser:L("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=p(Object.entries(Yk(L("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=p(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function On(a){var b=new aj,c=new Ui;D(c,1,a.fc);D(c,2,a.ec);D(c,16,a.Wc);D(c,17,a.innertubeContextClientVersion);if(a.yb){var d=a.yb,e=new Qi;d.coldConfigData&&D(e,1,d.coldConfigData);d.appInstallData&&D(e,6,d.appInstallData);d.coldHashData&&D(e,3,d.coldHashData);d.hotHashData&&D(e,5,d.hotHashData);G(c,Qi,62,e)}(d=z.devicePixelRatio)&&1!=d&&D(c,65,d);d=Ik();""!==d&&D(c,54,d);d=Jk();if(0<d.length){e=new Wi;for(var f=0;f<d.length;f++){var g=new Oi;D(g,1,d[f].key);Wd(g,2,Pi,d[f].value);de(e,15,Oi,g)}G(b,
Wi,5,e)}Jn(a,c);Kn(c);Ln(a,c);Mn(c);M("start_sending_config_hash")&&Nn(c);L("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(a=new Zi,D(a,3,L("DELEGATED_SESSION_ID")));a=p(Object.entries(Yk(L("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=p(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?D(c,12,e):"cmodel"===d?D(c,13,e):"cbr"===d?D(c,87,e):"cbrver"===d?D(c,88,e):"cos"===d?D(c,18,e):"cosver"===d?D(c,19,e):"cplatform"===d&&D(c,42,e);b.i(c);return b}
function Jn(a,b,c){a=a.dc;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Yd(b,Ri,96)||new Ri;var d=vl();d=Object.keys(ij).indexOf(d);d=-1===d?null:d;null!==d&&D(c,3,d);G(b,Ri,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=vl())}
function Kn(a,b){var c;if(M("web_log_memory_total_kbytes")&&(null==(c=z.navigator)?0:c.deviceMemory)){var d;c=null==(d=z.navigator)?void 0:d.deviceMemory;a?D(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Ln(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Yd(b,Qi,62))?d:new Qi;D(c,6,a.appInstallData);G(b,Qi,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Mn(a,b){var c=Kl();c&&(a?D(a,61,Gl[c]):b&&(b.client.connectionType=c));M("web_log_effective_connection_type")&&(c=Ll())&&(a?D(a,94,Hl[c]):b&&(b.client.effectiveConnectionType=c))}
function Pn(a,b,c){c=void 0===c?{}:c;var d={};L("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":L("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||L("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.ir||L("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().hr:b=xg([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=L("SESSION_INDEX",0),M("pageid_as_header_web")&&(d["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return d}
function Nn(a,b){Fn.h||(Fn.h=new Fn);var c=B("yt.gcf.config.coldConfigData");var d=B("yt.gcf.config.hotHashData");var e=B("yt.gcf.config.coldHashData");if(c&&e&&d)if(a){var f;b=null!=(f=Yd(a,Qi,62))?f:new Qi;D(b,1,c);D(b,3,e);D(b,5,d);G(a,Qi,62,b)}else b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.coldConfigData=c,b.client.configInfo.coldHashData=e,b.client.configInfo.hotHashData=d)}
;function Qn(a){a=Object.assign({},a);delete a.Authorization;var b=xg();if(b){var c=new fi;c.update(L("INNERTUBE_API_KEY"));c.update(b);a.hash=ed(c.digest(),3)}return a}
;var Rn;function Sn(){Rn||(Rn=new Xl("yt.innertube"));return Rn}
function Tn(a,b,c,d){if(d)return null;d=Sn().get("nextId",!0)||1;var e=Sn().get("requests",!0)||{};e[d]={method:a,request:b,authState:Qn(c),requestTime:Math.round(R())};Sn().set("nextId",d+1,86400,!0);Sn().set("requests",e,86400,!0);return d}
function Un(a){var b=Sn().get("requests",!0)||{};delete b[a];Sn().set("requests",b,86400,!0)}
function Vn(a){var b=Sn().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(R())-d.requestTime)){var e=d.authState,f=Qn(Pn(!1));ub(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(R())),Wn(a,d.method,e,{}));delete b[c]}}Sn().set("requests",b,86400,!0)}}
;function Xn(a){this.ab=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.Da=function(){};
this.now=Date.now;this.Ka=!1;var b;this.vc=null!=(b=a.vc)?b:100;var c;this.pc=null!=(c=a.pc)?c:1;var d;this.nc=null!=(d=a.nc)?d:2592E6;var e;this.lc=null!=(e=a.lc)?e:12E4;var f;this.oc=null!=(f=a.oc)?f:5E3;var g;this.H=null!=(g=a.H)?g:void 0;this.fb=!!a.fb;var h;this.eb=null!=(h=a.eb)?h:.1;var k;this.kb=null!=(k=a.kb)?k:10;a.handleError&&(this.handleError=a.handleError);a.Da&&(this.Da=a.Da);a.Ka&&(this.Ka=a.Ka);a.ab&&(this.ab=a.ab);this.J=a.J;this.Z=a.Z;this.N=a.N;this.L=a.L;this.ja=a.ja;this.Db=
a.Db;this.Cb=a.Cb;Yn(this)&&(!this.J||this.J("networkless_logging"))&&Zn(this)}
function Zn(a){Yn(a)&&!a.Ka&&(a.h=!0,a.fb&&Math.random()<=a.eb&&a.N.Lc(a.H),$n(a),a.L.V()&&a.Qa(),a.L.ia(a.Db,a.Qa.bind(a)),a.L.ia(a.Cb,a.Rb.bind(a)))}
l=Xn.prototype;l.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Yn(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.N.set(d,this.H).then(function(e){d.id=e;c.L.V()&&ao(c,d)}).catch(function(e){ao(c,d);
bo(c,e)})}else this.ja(a,b)};
l.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Yn(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.J&&this.J("nwl_skip_retry")&&(e.skipRetry=c);if(this.L.V()||this.J&&this.J("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.h)return v(k,d.N.set(e,d.H).catch(function(m){bo(d,m)}),2);
f(g,h);k.h=0})}}this.ja(a,b,e.skipRetry)}else this.N.set(e,this.H).catch(function(g){d.ja(a,b,e.skipRetry);
bo(d,g)})}else this.ja(a,b,this.J&&this.J("nwl_skip_retry")&&c)};
l.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Yn(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.N.Ca(d.id,c.H):e=!0;c.L.xa&&c.J&&c.J("vss_network_hint")&&c.L.xa(!0);f(g,h)};
this.ja(d.url,d.options);this.N.set(d,this.H).then(function(g){d.id=g;e&&c.N.Ca(d.id,c.H)}).catch(function(g){bo(c,g)})}else this.ja(a,b)};
l.Qa=function(){var a=this;if(!Yn(this))throw vm("throttleSend");this.i||(this.i=this.Z.U(function(){var b;return x(function(c){if(1==c.h)return v(c,a.N.cc("NEW",a.H),2);if(3!=c.h)return b=c.i,b?v(c,ao(a,b),3):(a.Rb(),c.return());a.i&&(a.i=0,a.Qa());c.h=0})},this.vc))};
l.Rb=function(){this.Z.fa(this.i);this.i=0};
function ao(a,b){var c,d;return x(function(e){switch(e.h){case 1:if(!Yn(a))throw c=vm("immediateSend"),c;if(void 0===b.id){e.A(2);break}return v(e,a.N.cd(b.id,a.H),3);case 3:(d=e.i)?b=d:a.Da(Error("The request cannot be found in the database."));case 2:if(co(a,b,a.nc)){e.A(4);break}a.Da(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.A(5);break}return v(e,a.N.Ca(b.id,a.H),5);case 5:return e.return();case 4:b.skipRetry||(b=eo(a,b));if(!b){e.A(0);break}if(!b.skipRetry||
void 0===b.id){e.A(8);break}return v(e,a.N.Ca(b.id,a.H),8);case 8:a.ja(b.url,b.options,!!b.skipRetry),e.h=0}})}
function eo(a,b){if(!Yn(a))throw vm("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k;return x(function(m){switch(m.h){case 1:g=fo(f);if(!(a.J&&a.J("nwl_consider_error_code")&&g||a.J&&!a.J("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.kb)){m.A(2);break}if(!a.L.nb){m.A(3);break}return v(m,a.L.nb(),3);case 3:if(a.L.V()){m.A(2);break}c(e,f);if(!a.J||!a.J("nwl_consider_error_code")||void 0===(null==(h=b)?void 0:h.id)){m.A(6);break}return v(m,a.N.Hb(b.id,a.H,!1),6);case 6:return m.return();case 2:if(a.J&&a.J("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.kb)return m.return();a.potentialEsfErrorCounter++;if(void 0===(null==(k=b)?void 0:k.id)){m.A(8);break}return b.sendCount<a.pc?v(m,a.N.Hb(b.id,a.H),12):v(m,a.N.Ca(b.id,a.H),8);case 12:a.Z.U(function(){a.L.V()&&a.Qa()},a.oc);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.A(2):v(h,a.N.Ca(b.id,a.H),2);a.L.xa&&a.J&&a.J("vss_network_hint")&&a.L.xa(!0);d(e,f);h.h=0})};
return b}
function co(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function $n(a){if(!Yn(a))throw vm("retryQueuedRequests");a.N.cc("QUEUED",a.H).then(function(b){b&&!co(a,b,a.lc)?a.Z.U(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.A(2):v(c,a.N.Hb(b.id,a.H),2);$n(a);c.h=0})}):a.L.V()&&a.Qa()})}
function bo(a,b){a.Ac&&!a.L.V()?a.Ac(b):a.handleError(b)}
function Yn(a){return!!a.H||a.ab}
function fo(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function go(a,b){this.version=a;this.args=b}
;function ho(a,b){this.topic=a;this.h=b}
ho.prototype.toString=function(){return this.topic};var io=B("ytPubsub2Pubsub2Instance")||new K;K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Ha;K.prototype.publish=K.prototype.ta;K.prototype.clear=K.prototype.clear;A("ytPubsub2Pubsub2Instance",io);var jo=B("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",jo);var ko=B("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",ko);var lo=B("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",lo);
A("ytPubsub2Pubsub2SkipSubKey",null);function mo(a,b){var c=no();c&&c.publish.call(c,a.toString(),a,b)}
function oo(a){var b=po,c=no();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(jo[d])try{if(f&&b instanceof ho&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.ra){var m=new h;h.ra=m.version}var q=h.ra}catch(F){}if(!q||k.version!=q)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{q=Reflect;var r=q.construct;
var w=k.args,t=w.length;if(0<t){var y=Array(t);for(k=0;k<t;k++)y[k]=w[k];var E=y}else E=[];f=r.call(q,h,E)}catch(F){throw F.message="yt.pubsub2.Data.deserialize(): "+F.message,F;}}catch(F){throw F.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+F.message,F;}a.call(window,f)}catch(F){Nk(F)}},lo[b.toString()]?B("yt.scheduler.instance")?$h.U(g):gl(g,0):g())});
jo[d]=!0;ko[b.toString()]||(ko[b.toString()]=[]);ko[b.toString()].push(d);return d}
function qo(){var a=ro,b=oo(function(c){a.apply(void 0,arguments);so(b)});
return b}
function so(a){var b=no();b&&("number"===typeof a&&(a=[a]),fb(a,function(c){b.unsubscribeByKey(c);delete jo[c]}))}
function no(){return B("ytPubsub2Pubsub2Instance")}
;var to;
function uo(){if(to)return to();var a={};to=En("LogsDatabaseV2",{Na:(a.LogsRequestsStore={rb:2},a),Jb:!1,upgrade:function(b,c,d){c(2)&&Km(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return to()}
;function vo(a){return cn(uo(),a)}
function wo(a,b){var c,d,e,f;return x(function(g){if(1==g.h)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},v(g,vo(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:L("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),v(g,Mm(d,e),3);f=g.i;c.Bd=R();xo(c);return g.return(f)})}
function yo(a,b){var c,d,e,f,g,h,k;return x(function(m){if(1==m.h)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},v(m,vo(b),2);if(3!=m.h)return d=m.i,e=L("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,R()],h=IDBKeyRange.bound(f,g),k=void 0,v(m,Jm(d,["LogsRequestsStore"],{mode:"readwrite",T:!0},function(q){return Vm(q.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(r){r.getValue()&&(k=r.getValue(),"NEW"===a&&(k.status="QUEUED",
r.update(k)))})}),3);
c.Bd=R();xo(c);return m.return(k)})}
function zo(a,b){var c;return x(function(d){if(1==d.h)return v(d,vo(b),2);c=d.i;return d.return(Jm(c,["LogsRequestsStore"],{mode:"readwrite",T:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Fm(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Ao(a,b,c){c=void 0===c?!0:c;var d;return x(function(e){if(1==e.h)return v(e,vo(b),2);d=e.i;return e.return(Jm(d,["LogsRequestsStore"],{mode:"readwrite",T:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),Fm(g.h.put(h,void 0)).then(function(){return h})):zm.resolve(void 0)})}))})}
function Bo(a,b){var c;return x(function(d){if(1==d.h)return v(d,vo(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Co(a){var b,c;return x(function(d){if(1==d.h)return v(d,vo(a),2);b=d.i;c=R()-2592E6;return v(d,Jm(b,["LogsRequestsStore"],{mode:"readwrite",T:!0},function(e){return Sm(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Do(){x(function(a){return v(a,An(),0)})}
function xo(a){M("nwl_csi_killswitch")||.01>=Math.random()&&mo("nwl_transaction_latency_payload",a)}
;var Eo={},Fo=En("ServiceWorkerLogsDatabase",{Na:(Eo.SWHealthLog={rb:1},Eo),Jb:!0,upgrade:function(a,b){b(1)&&Km(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Go(a){return cn(Fo(),a)}
function Ho(a){var b,c;x(function(d){if(1==d.h)return v(d,Go(a),2);b=d.i;c=R()-2592E6;return v(d,Jm(b,["SWHealthLog"],{mode:"readwrite",T:!0},function(e){return Sm(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Io(a){var b;return x(function(c){if(1==c.h)return v(c,Go(a),2);b=c.i;return v(c,b.clear("SWHealthLog"),0)})}
;var Jo={},Ko=0;function Lo(a){var b=new Image,c=""+Ko++;Jo[c]=b;b.onload=b.onerror=function(){delete Jo[c]};
b.src=a}
;function Mo(){this.h=new Map;this.i=!1}
function No(){if(!Mo.h){var a=B("yt.networkRequestMonitor.instance")||new Mo;A("yt.networkRequestMonitor.instance",a);Mo.h=a}return Mo.h}
Mo.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Mo.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
Mo.prototype.removeParams=function(a){return a.split("?")[0]};
Mo.prototype.removeParams=Mo.prototype.removeParams;Mo.prototype.isEndpointCFR=Mo.prototype.isEndpointCFR;Mo.prototype.requestComplete=Mo.prototype.requestComplete;Mo.getInstance=No;var Oo;function Po(){Oo||(Oo=new Xl("yt.offline"));return Oo}
function Qo(a){if(M("offline_error_handling")){var b=Po().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Po().set("errors",b,2592E3,!0)}}
;function Ro(){ef.call(this);var a=this;this.j=!1;this.i=Zh();this.i.ia("networkstatus-online",function(){if(a.j&&M("offline_error_handling")){var b=Po().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new P(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Nk(d)}Po().set("errors",{},2592E3,!0)}}})}
u(Ro,ef);function So(){if(!Ro.h){var a=B("yt.networkStatusManager.instance")||new Ro;A("yt.networkStatusManager.instance",a);Ro.h=a}return Ro.h}
l=Ro.prototype;l.V=function(){return this.i.V()};
l.xa=function(a){this.i.i=a};
l.Uc=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
l.Pc=function(){this.j=!0};
l.ia=function(a,b){return this.i.ia(a,b)};
l.nb=function(a){a=Xh(this.i,a);a.then(function(b){M("use_cfr_monitor")&&No().requestComplete("generate_204",b)});
return a};
Ro.prototype.sendNetworkCheckRequest=Ro.prototype.nb;Ro.prototype.listen=Ro.prototype.ia;Ro.prototype.enableErrorFlushing=Ro.prototype.Pc;Ro.prototype.getWindowStatus=Ro.prototype.Uc;Ro.prototype.networkStatusHint=Ro.prototype.xa;Ro.prototype.isNetworkAvailable=Ro.prototype.V;Ro.getInstance=So;function To(a){a=void 0===a?{}:a;ef.call(this);var b=this;this.i=this.o=0;this.j=So();var c=B("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.mb?(this.mb=a.mb,c("networkstatus-online",function(){Uo(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Uo(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){ff(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){ff(b,"publicytnetworkstatus-offline")})))}
u(To,ef);To.prototype.V=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
To.prototype.xa=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
To.prototype.nb=function(a){var b=this,c;return x(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return M("skip_network_check_if_cfr")&&No().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.xa((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.V())})):c?d.return(c(a)):d.return(!0)})};
function Uo(a,b){a.mb?a.i?($h.fa(a.o),a.o=$h.U(function(){a.m!==b&&(ff(a,b),a.m=b,a.i=R())},a.mb-(R()-a.i))):(ff(a,b),a.m=b,a.i=R()):ff(a,b)}
;var Vo;function Wo(){var a=Xn.call;Vo||(Vo=new To({wr:!0,qr:!0}));a.call(Xn,this,{N:{Lc:Co,Ca:Bo,cc:yo,cd:zo,Hb:Ao,set:wo},L:Vo,handleError:Nk,Da:Ok,ja:Xo,now:R,Ac:Qo,Z:Sl(),Db:"publicytnetworkstatus-online",Cb:"publicytnetworkstatus-offline",fb:!0,eb:.1,kb:Hk("potential_esf_error_limit",10),J:M,Ka:!(Tl()&&Yo())});this.j=new Eh;M("networkless_immediately_drop_all_requests")&&Do();Bn("LogsDatabaseV2")}
u(Wo,Xn);function Zo(){var a=B("yt.networklessRequestController.instance");a||(a=new Wo,A("yt.networklessRequestController.instance",a),M("networkless_logging")&&qn().then(function(b){a.H=b;Zn(a);a.j.resolve();a.fb&&Math.random()<=a.eb&&a.H&&Ho(a.H);M("networkless_immediately_drop_sw_health_store")&&$o(a)}));
return a}
Wo.prototype.writeThenSend=function(a,b){b||(b={});Tl()||(this.h=!1);Xn.prototype.writeThenSend.call(this,a,b)};
Wo.prototype.sendThenWrite=function(a,b,c){b||(b={});Tl()||(this.h=!1);Xn.prototype.sendThenWrite.call(this,a,b,c)};
Wo.prototype.sendAndWrite=function(a,b){b||(b={});Tl()||(this.h=!1);Xn.prototype.sendAndWrite.call(this,a,b)};
Wo.prototype.awaitInitialization=function(){return this.j.promise};
function $o(a){var b;x(function(c){if(!a.H)throw b=vm("clearSWHealthLogsDb"),b;return c.return(Io(a.H).catch(function(d){a.handleError(d)}))})}
function Xo(a,b,c){M("use_cfr_monitor")&&ap(a,b);if(M("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(R())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(R())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;if(a)if(e)pl(a,void 0,"POST",e);else if(L("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))pl(a,void 0,"GET","",void 0,void 0,f);else{b:{try{var g=new bb({url:a});if(g.j&&g.i||
g.l){var h=mc(nc(5,a)),k;if(!(k=!h||!h.endsWith("/aclk"))){var m=a.search(Bc),q=Ac(a,0,"ri",m);if(0>q)var r=null;else{var w=a.indexOf("&",q);if(0>w||w>m)w=m;r=decodeURIComponent(a.slice(q+3,-1!==w?w:0).replace(/\+/g," "))}k="1"!==r}var t=!k;break b}}catch(E){}t=!1}if(t){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var y=!0;break b}}catch(E){}y=!1}c=y?!0:!1}else c=!1;c||Lo(a)}}else ml(a,b)}
function ap(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){No().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){No().requestComplete(a,!0);d(e,f)}}
function Yo(){return"www.youtube-nocookie.com"!==oc(document.location.toString())}
;var bp=!1,pp=z.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:bp};A("ytNetworklessLoggingInitializationOptions",pp);function Op(){var a;x(function(b){if(1==b.h)return v(b,qn(),2);a=b.i;if(!a||!Tl()&&!M("nwl_init_require_datasync_id_killswitch")||!Yo())return b.A(0);bp=!0;pp.isNwlInitialized=bp;return v(b,Zo().awaitInitialization(),0)})}
;function Pp(a){var b=this;this.config_=null;a?this.config_=a:Gn()&&(this.config_=Hn());Nl(function(){Vn(b)},5E3)}
Pp.prototype.isReady=function(){!this.config_&&Gn()&&(this.config_=Hn());return!!this.config_};
function Wn(a,b,c,d){function e(y){y=void 0===y?!1:y;var E;if(d.retry&&"www.youtube-nocookie.com"!=h&&(y||M("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(E=Tn(b,c,m,k)),E)){var F=g.onSuccess,O=g.onFetchSuccess;g.onSuccess=function(N,Q){Un(E);F(N,Q)};
c.onFetchSuccess=function(N,Q){Un(E);O(N,Q)}}try{y&&d.retry&&!d.ic.bypassNetworkless?(g.method="POST",d.ic.writeThenSend?Zo().writeThenSend(t,g):Zo().sendAndWrite(t,g)):M("web_all_payloads_via_jspb")?ml(t,g):(g.method="POST",g.postParams||(g.postParams={}),ml(t,g))}catch(N){if("InvalidAccessError"==N.name)E&&(Un(E),E=0),Ok(Error("An extension is blocking network request."));
else throw N;}E&&Nl(function(){Vn(a)},5E3)}
!L("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Ok(new P("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new P("innertube xhrclient not ready",b,c,d);Nk(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(y,E){if(d.onSuccess)d.onSuccess(E)},
onFetchSuccess:function(y){if(d.onSuccess)d.onSuccess(y)},
onError:function(y,E){if(d.onError)d.onError(E)},
onFetchError:function(y){if(d.onError)d.onError(y)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Xc)&&(h=f);var k=a.config_.Zc||!1,m=Pn(k,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var q="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,r={alt:"json"},w=a.config_.Yc&&f;w=w&&f.startsWith("Bearer");w||(r.key=a.config_.innertubeApiKey);var t=$k(""+h+q,r||{},!0);(B("ytNetworklessLoggingInitializationOptions")?
pp.isNwlInitialized:bp)?pn().then(function(y){e(y)}):e(!1)}
;var Qp=0,Rp=Oc?"webkit":Nc?"moz":Lc?"ms":Kc?"o":"";A("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++Qp});var Sp={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Tp(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Sp||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Up(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Tp.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Tp.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Tp.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var qb=z.ytEventsEventsListeners||{};A("ytEventsEventsListeners",qb);var Vp=z.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",Vp);
function Wp(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return pb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Qa(e[4])&&Qa(d)&&ub(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Xp=db(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Yp(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Wp(a,b,c,d);if(e)return e;e=++Vp.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Tp(h);if(!pf(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Tp(h);
h.currentTarget=a;return c.call(a,h)};
g=Mk(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Xp()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);qb[e]=[a,b,c,g,d];return e}
function Zp(a){a&&("string"==typeof a&&(a=[a]),fb(a,function(b){if(b in qb){var c=qb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Xp()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete qb[b]}}))}
;var $p=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function aq(a){this.F=a;this.i=null;this.m=0;this.s=null;this.o=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.K=Yp(window,"mousemove",Xa(this.O,this));a=Xa(this.I,this);"function"===typeof a&&(a=Mk(a));this.P=window.setInterval(a,25)}
Za(aq,J);aq.prototype.O=function(a){void 0===a.h&&Up(a);var b=a.h;void 0===a.i&&Up(a);this.i=new lf(b,a.i)};
aq.prototype.I=function(){if(this.i){var a=$p();if(0!=this.m){var b=this.s,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.o)/this.o)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.F();this.o=d}this.m=a;this.s=this.i;this.l=(this.l+1)%4}};
aq.prototype.C=function(){window.clearInterval(this.P);Zp(this.K)};var bq={};
function cq(a){var b=void 0===a?{}:a;a=void 0===b.gd?!1:b.gd;b=void 0===b.Qc?!0:b.Qc;if(null==B("_lact",window)){var c=parseInt(L("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&dq();Yp(document,"keydown",dq);Yp(document,"keyup",dq);Yp(document,"mousedown",dq);Yp(document,"mouseup",dq);a?Yp(window,"touchmove",function(){eq("touchmove",200)},{passive:!0}):(Yp(window,"resize",function(){eq("resize",200)}),b&&Yp(window,"scroll",function(){eq("scroll",200)}));
new aq(function(){eq("mouse",100)});
Yp(document,"touchstart",dq,{passive:!0});Yp(document,"touchend",dq,{passive:!0})}}
function eq(a,b){bq[a]||(bq[a]=!0,$h.U(function(){dq();bq[a]=!1},b))}
function dq(){null==B("_lact",window)&&cq();var a=Date.now();A("_lact",a,window);-1==B("_fact",window)&&A("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function fq(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var gq=z.ytPubsubPubsubInstance||new K,hq=z.ytPubsubPubsubSubscribedKeys||{},iq=z.ytPubsubPubsubTopicToKeys||{},jq=z.ytPubsubPubsubIsSynchronous||{};function kq(a,b){var c=lq();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){hq[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{jq[a]?f():gl(f,0)}catch(g){Nk(g)}},void 0);
hq[d]=!0;iq[a]||(iq[a]=[]);iq[a].push(d);return d}return 0}
function mq(a){var b=lq();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),fb(a,function(c){b.unsubscribeByKey(c);delete hq[c]}))}
function nq(a,b){var c=lq();c&&c.publish.apply(c,arguments)}
function oq(a){var b=lq();if(b)if(b.clear(a),a)pq(a);else for(var c in iq)pq(c)}
function lq(){return z.ytPubsubPubsubInstance}
function pq(a){iq[a]&&(a=iq[a],fb(a,function(b){hq[b]&&delete hq[b]}),a.length=0)}
K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Ha;K.prototype.publish=K.prototype.ta;K.prototype.clear=K.prototype.clear;A("ytPubsubPubsubInstance",gq);A("ytPubsubPubsubTopicToKeys",iq);A("ytPubsubPubsubIsSynchronous",jq);A("ytPubsubPubsubSubscribedKeys",hq);function qq(){this.store={};this.h={}}
qq.prototype.storePayload=function(a,b){a=rq(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
qq.prototype.extractMatchingEntries=function(a){a=sq(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ia(this.store[a[c]])),delete this.store[a[c]]);return b};
qq.prototype.getSequenceCount=function(a){a=sq(this,a);for(var b=0,c=0;c<a.length;c++)b+=this.store[a[c]].length||0;return b};
function sq(a,b){var c=rq(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&rq(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(tq(b.auth,g[0])){var h=b.isJspb;tq(void 0===h?"undefined":h?"true":"false",g[1])&&tq(b.cttAuthInfo,g[2])&&e.push(d[f])}}return a.h[c]=e}
function tq(a,b){return void 0===a||"undefined"===a?!0:a===b}
qq.prototype.getSequenceCount=qq.prototype.getSequenceCount;qq.prototype.extractMatchingEntries=qq.prototype.extractMatchingEntries;qq.prototype.storePayload=qq.prototype.storePayload;function rq(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo].join("/")}
;var uq=Hk("initial_gel_batch_timeout",2E3),vq=Math.pow(2,16)-1,wq=void 0;function xq(){this.j=this.h=this.i=0}
var yq=new xq,zq=new xq,Aq,Bq=!0,Cq=z.ytLoggingTransportGELQueue_||new Map;A("ytLoggingTransportGELQueue_",Cq);var Dq=z.ytLoggingTransportGELProtoQueue_||new Map;A("ytLoggingTransportGELProtoQueue_",Dq);var Eq=z.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",Eq);var Fq=z.ytLoggingTransportTokensToJspbCttTargetIds_||{};A("ytLoggingTransportTokensToJspbCttTargetIds_",Fq);var Gq={};function Hq(){var a=B("yt.logging.ims");a||(a=new qq,A("yt.logging.ims",a));return a}
function Iq(a,b){M("web_all_payloads_via_jspb")&&Ok(new P("transport.log called for JSON in JSPB only experiment"));if("log_event"===a.endpoint){Jq(a);var c=Kq(a);if(M("use_new_in_memory_storage")){Gq[c]=!0;var d={cttAuthInfo:c,isJspb:!1};Hq().storePayload(d,a.payload);Lq(b,[],c,!1,d)}else d=Cq.get(c)||[],Cq.set(c,d),d.push(a.payload),Lq(b,d,c)}}
function Mq(a,b){if("log_event"===a.endpoint){Jq(void 0,a);var c=Kq(a,!0);if(M("use_new_in_memory_storage")){Gq[c]=!0;var d={cttAuthInfo:c,isJspb:!0};Hq().storePayload(d,a.payload.toJSON());Lq(b,[],c,!0,d)}else d=Dq.get(c)||[],Dq.set(c,d),a=a.payload.toJSON(),d.push(a),Lq(b,d,c,!0)}}
function Lq(a,b,c,d,e){d=void 0===d?!1:d;a&&(wq=new a);a=Hk("tvhtml5_logging_max_batch")||Hk("web_logging_max_batch")||100;var f=R(),g=d?zq.j:yq.j;b=b.length;e&&(b=Hq().getSequenceCount(e));b>=a?M("background_thread_flush_logs_due_to_batch_limit")?Aq||(Aq=Nq(function(){Oq({writeThenSend:!0},M("flush_only_full_queue")?c:void 0,d);Aq=void 0},0)):Oq({writeThenSend:!0},M("flush_only_full_queue")?c:void 0,d):10<=f-g&&(Pq(d),d?zq.j=f:yq.j=f)}
function Qq(a,b){M("web_all_payloads_via_jspb")&&Ok(new P("transport.logIsolatedGelPayload called in JSPB only experiment"));if("log_event"===a.endpoint){Jq(a);var c=Kq(a),d=new Map;d.set(c,[a.payload]);b&&(wq=new b);return new Bf(function(e,f){wq&&wq.isReady()?Rq(d,wq,e,f,{bypassNetworkless:!0},!0):e()})}}
function Sq(a,b){if("log_event"===a.endpoint){Jq(void 0,a);var c=Kq(a,!0),d=new Map;d.set(c,[a.payload.toJSON()]);b&&(wq=new b);return new Bf(function(e){wq&&wq.isReady()?Tq(d,wq,e,{bypassNetworkless:!0},!0):e()})}}
function Kq(a,b){var c="";if(a.Ja)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new qk;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Wd(d,2,rk,c.playlistId);Fq[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Eq[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Oq(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;!c&&M("web_all_payloads_via_jspb")&&Ok(new P("transport.flushLogs called for JSON in JSPB only experiment"));new Bf(function(d,e){c?(Uq(zq.i),Uq(zq.h),zq.h=0):(Uq(yq.i),Uq(yq.h),yq.h=0);if(wq&&wq.isReady())if(M("use_new_in_memory_storage")){var f=a,g=c,h=wq;f=void 0===f?{}:f;g=void 0===g?!1:g;var k=new Map,m=new Map;if(void 0!==b)g?(e=Hq().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),k.set(b,e),Tq(k,h,d,f)):(k=Hq().extractMatchingEntries({isJspb:g,
cttAuthInfo:b}),m.set(b,k),Rq(m,h,d,e,f));else if(g){e=p(Object.keys(Gq));for(g=e.next();!g.done;g=e.next())m=g.value,g=Hq().extractMatchingEntries({isJspb:!0,cttAuthInfo:m}),0<g.length&&k.set(m,g),delete Gq[m];Tq(k,h,d,f)}else{k=p(Object.keys(Gq));for(g=k.next();!g.done;g=k.next()){g=g.value;var q=Hq().extractMatchingEntries({isJspb:!1,cttAuthInfo:g});0<q.length&&m.set(g,q);delete Gq[g]}Rq(m,h,d,e,f)}}else f=a,k=c,h=wq,f=void 0===f?{}:f,k=void 0===k?!1:k,void 0!==b?k?(e=new Map,k=Dq.get(b)||[],e.set(b,
k),Tq(e,h,d,f),Dq.delete(b)):(k=new Map,m=Cq.get(b)||[],k.set(b,m),Rq(k,h,d,e,f),Cq.delete(b)):k?(Tq(Dq,h,d,f),Dq.clear()):(Rq(Cq,h,d,e,f),Cq.clear());else Pq(c),d()})}
function Pq(a){a=void 0===a?!1:a;if(M("web_gel_timeout_cap")&&(!a&&!yq.h||a&&!zq.h)){var b=Nq(function(){Oq({writeThenSend:!0},void 0,a)},6E4);
a?zq.h=b:yq.h=b}Uq(a?zq.i:yq.i);b=L("LOGGING_BATCH_TIMEOUT",Hk("web_gel_debounce_ms",1E4));M("shorten_initial_gel_batch_timeout")&&Bq&&(b=uq);b=Nq(function(){Oq({writeThenSend:!0},void 0,a)},b);
a?zq.i=b:yq.i=b}
function Rq(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(R()),h=a.size,k={};a=p(a);for(var m=a.next();!m.done;k={Ta:k.Ta,sa:k.sa,Fa:k.Fa,Va:k.Va,Ua:k.Ua},m=a.next()){var q=p(m.value);m=q.next().value;q=q.next().value;k.sa=wb({context:In(b.config_||Hn())});if(!Pa(q)&&!M("throw_err_when_logevent_malformed_killswitch")){d();break}k.sa.events=q;(q=Eq[m])&&Vq(k.sa,m,q);delete Eq[m];k.Fa="visitorOnlyApprovedKey"===m;Wq(k.sa,g,k.Fa);Xq(e);k.Va=function(){h--;h||c()};
k.Ta=0;k.Ua=function(r){return function(){r.Ta++;if(e.bypassNetworkless&&1===r.Ta)try{Wn(b,"log_event",r.sa,Yq({writeThenSend:!0},r.Fa,r.Va,r.Ua,f)),Bq=!1}catch(w){Nk(w),d()}h--;h||c()}}(k);
try{Wn(b,"log_event",k.sa,Yq(e,k.Fa,k.Va,k.Ua,f)),Bq=!1}catch(r){Nk(r),d()}}}
function Tq(a,b,c,d,e){d=void 0===d?{}:d;var f=Math.round(R()),g=a.size,h=new Map([].concat(ia(a)));h=p(h);for(var k=h.next();!k.done;k=h.next()){var m=p(k.value).next().value,q=a.get(m);k=new sk;var r=On(b.config_||Hn());G(k,aj,1,r);q=q?Zq(q):[];q=p(q);for(r=q.next();!r.done;r=q.next())de(k,3,mk,r.value);(q=Fq[m])&&$q(k,m,q);delete Fq[m];m="visitorOnlyApprovedKey"===m;ar(k,f,m);Xq(d);k=le(k);m=Yq(d,m,function(){g--;g||c()},function(){g--;
g||c()},e);
m.headers["Content-Type"]="application/json+protobuf";m.postBodyFormat="JSPB";m.postBody=k;Wn(b,"log_event","",m);Bq=!1}}
function Xq(a){M("always_send_and_write")&&(a.writeThenSend=!1)}
function Yq(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,ic:a,Ja:b,kr:!!e,headers:{},postBodyFormat:"",postBody:""};br()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(R())));return a}
function Wq(a,b,c){br()||(a.requestTimeMs=String(b));M("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=L("EVENT_ID"))&&(c=cr(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function ar(a,b,c){br()||D(a,2,b);if(!c&&(b=L("EVENT_ID"))){c=cr();var d=new pk;D(d,1,b);D(d,2,c);G(a,pk,5,d)}}
function cr(){var a=L("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*vq/2));a++;a>vq&&(a=1);Ek("BATCH_CLIENT_COUNTER",a);return a}
function Vq(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function $q(a,b,c){if(ee(c,1===Xd(c,rk)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;G(a,qk,4,c);a=Yd(a,aj,1)||new aj;c=Yd(a,Zi,3)||new Zi;var e=new Yi;D(e,2,b);D(e,1,d);de(c,12,Yi,e);G(a,Zi,3,c)}
function Zq(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new mk(a[c]))}catch(d){Nk(new P("Transport failed to deserialize "+String(a[c])))}return b}
function Jq(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape","");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);A("yt.logging.transport.scrapedPayloadsForTesting",c)}}
function br(){return M("use_request_time_ms_header")||M("lr_use_request_time_ms_header")}
function Nq(a,b){return M("transport_use_scheduler")?Nl(a,b):gl(a,b)}
function Uq(a){M("transport_use_scheduler")?$h.fa(a):window.clearTimeout(a)}
;var dr=z.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",dr);
function er(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||R());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;M("enable_unknown_lact_fix_on_html5")&&cq();a=fq();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};M("log_sequence_info_on_gel_web")&&d.aa&&(a=e.context,b=d.aa,b={index:fr(b),groupKey:b},a.sequence=b,d.Yb&&delete dr[d.aa]);(d.qc?Qq:Iq)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,Ja:d.Ja},c)}
function gr(a){Oq(void 0,void 0,void 0===a?!1:a)}
function fr(a){dr[a]=a in dr?dr[a]+1:0;return dr[a]}
;var hr=[];var ir=z.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",ir);function jr(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||R());D(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=fq();d=new lk;D(d,1,c.timestamp||!isFinite(e)?-1:e);if(M("log_sequence_info_on_gel_web")&&c.aa){e=c.aa;var f=fr(e),g=new kk;D(g,2,f);D(g,1,e);G(d,kk,3,g);c.Yb&&delete ir[c.aa]}G(a,lk,33,d);(c.qc?Sq:Mq)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,Ja:c.Ja},b)}
;function kr(a,b){b=void 0===b?{}:b;var c=!1;L("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);jr(a,c?null:Pp,b)}
;function lr(a,b){var c=new mk;be(c,Hj,72,nk,a);kr(c,b)}
function mr(a,b,c){var d=new mk;be(d,Gj,73,nk,a);c?jr(d,c,b):kr(d,b)}
function nr(a,b,c){var d=new mk;be(d,Fj,78,nk,a);c?jr(d,c,b):kr(d,b)}
function or(a,b,c){var d=new mk;be(d,Ij,208,nk,a);c?jr(d,c,b):kr(d,b)}
function pr(a,b,c){var d=new mk;be(d,yj,156,nk,a);c?jr(d,c,b):kr(d,b)}
function qr(a,b,c){var d=new mk;be(d,Cj,215,nk,a);c?jr(d,c,b):kr(d,b)}
function rr(a,b,c){var d=new mk;be(d,xj,111,nk,a);c?jr(d,c,b):kr(d,b)}
;function fm(a,b,c){c=void 0===c?{}:c;if(M("migrate_events_to_ts")){c=void 0===c?{}:c;var d=Pp;L("ytLoggingEventsDefaultDisabled",!1)&&Pp===Pp&&(d=null);M("web_all_payloads_via_jspb")?hr.push({Eb:a,payload:b,options:c}):er(a,b,d,c)}else d=Pp,L("ytLoggingEventsDefaultDisabled",!1)&&Pp==Pp&&(d=null),er(a,b,d,c)}
;var sr=[{Bb:function(a){return"Cannot read property '"+a.key+"'"},
jb:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Bb:function(a){return"Cannot call '"+a.key+"'"},
jb:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Bb:function(a){return a.key+" is not defined"},
jb:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var ur={oa:[],ma:[{callback:tr,weight:500}]};function tr(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function vr(){this.ma=[];this.oa=[]}
var wr;function xr(){if(!wr){var a=wr=new vr;a.oa.length=0;a.ma.length=0;ur.oa&&a.oa.push.apply(a.oa,ur.oa);ur.ma&&a.ma.push.apply(a.ma,ur.ma)}return wr}
;var yr=new K;function zr(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Ar(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Ar(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Ar(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Ar(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Br(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Cr(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=zr(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Cr(e+".ve",f,g,h):0;d+=g;d+=Cr(e,a[e],b,c);if(500<d)break}}else c[b]=Dr(a),d+=c[b].length;else c[b]=Dr(a),d+=c[b].length;return d}
function Cr(a,b,c,d){c+="."+a;a=Dr(b);d[c]=a;return c.length+a.length}
function Dr(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var Er=new Set,Fr=0,Gr=0,Hr=0,Ir=[],Jr=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function em(a){Kr(a)}
function Lr(a){Kr(a,"WARNING")}
function Kr(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||L("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||L("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=f||{},h=void 0===b?"ERROR":b;h=void 0===h?"ERROR":h;if(a){a.hasOwnProperty("level")&&a.level&&(h=a.level);if(M("console_log_js_exceptions")){var k=[];k.push("Name: "+a.name);k.push("Message: "+a.message);a.hasOwnProperty("params")&&k.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&k.push("Error args: "+JSON.stringify(a.args));
k.push("File name: "+a.fileName);k.push("Stacktrace: "+a.stack);window.console.log(k.join("\n"),a)}if(!(5<=Fr)){var m=Ir,q=De(a),r=q.message||"Unknown Error",w=q.name||"UnknownError",t=q.stack||a.i||"Not available";if(t.startsWith(w+": "+r)){var y=t.split("\n");y.shift();t=y.join("\n")}var E=q.lineNumber||"Not available",F=q.fileName||"Not available",O=t,N=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var Q=0;Q<a.args.length&&!(N=Br(a.args[Q],"params."+Q,g,N),500<=N);Q++);else if(a.hasOwnProperty("params")&&
a.params){var ca=a.params;if("object"===typeof a.params)for(var U in ca){if(ca[U]){var lb="params."+U,Wa=Dr(ca[U]);g[lb]=Wa;N+=lb.length+Wa.length;if(500<N)break}}else g.params=Dr(ca)}if(m.length)for(var na=0;na<m.length&&!(N=Br(m[na],"params.context."+na,g,N),500<=N);na++);navigator.vendor&&!g.hasOwnProperty("vendor")&&(g["device.vendor"]=navigator.vendor);var H={message:r,name:w,lineNumber:E,fileName:F,stack:O,params:g,sampleWeight:1},la=Number(a.columnNumber);isNaN(la)||(H.lineNumber=H.lineNumber+
":"+la);if("IGNORED"===a.level)var fa=0;else a:{for(var xe=xr(),ye=p(xe.oa),od=ye.next();!od.done;od=ye.next()){var pa=od.value;if(H.message&&H.message.match(pa.xr)){fa=pa.weight;break a}}for(var cp=p(xe.ma),Oj=cp.next();!Oj.done;Oj=cp.next()){var dp=Oj.value;if(dp.callback(H)){fa=dp.weight;break a}}fa=1}H.sampleWeight=fa;for(var ep=p(sr),Pj=ep.next();!Pj.done;Pj=ep.next()){var Qj=Pj.value;if(Qj.jb[H.name])for(var fp=p(Qj.jb[H.name]),Rj=fp.next();!Rj.done;Rj=fp.next()){var gp=Rj.value,Ig=H.message.match(gp.regexp);
if(Ig){H.params["params.error.original"]=Ig[0];for(var Sj=gp.groups,hp={},pd=0;pd<Sj.length;pd++)hp[Sj[pd]]=Ig[pd+1],H.params["params.error."+Sj[pd]]=Ig[pd+1];H.message=Qj.Bb(hp);break}}}H.params||(H.params={});var ip=xr();H.params["params.errorServiceSignature"]="msg="+ip.oa.length+"&cb="+ip.ma.length;H.params["params.serviceWorker"]="false";z.document&&z.document.querySelectorAll&&(H.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Db("sample").constructor!==
Bb&&(H.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(H);if(0!==H.sampleWeight&&!Er.has(H.message)){if("ERROR"===h){yr.ta("handleError",H);if(M("record_app_crashed_web")&&0===Hr&&1===H.sampleWeight)if(Hr++,M("errors_via_jspb")){var Tj=new uj;D(Tj,1,1);if(!M("report_client_error_with_app_crash_ks")){var jp=new pj;D(jp,1,H.message);var kp=new qj;G(kp,pj,3,jp);var lp=new rj;G(lp,qj,5,kp);var mp=new sj;G(mp,rj,9,lp);G(Tj,sj,4,mp)}var np=new mk;be(np,uj,20,
nk,Tj);kr(np)}else{var op={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};M("report_client_error_with_app_crash_ks")||(op.systemHealth={crashData:{clientError:{logMessage:{message:H.message}}}});fm("appCrashed",op)}Gr++}else"WARNING"===h&&yr.ta("handleWarning",H);if(M("kevlar_gel_error_routing"))a:{var ze=h;if(M("errors_via_jspb")){if(Mr())var qp=void 0;else{var qd=new mj;D(qd,1,H.stack);H.fileName&&D(qd,4,H.fileName);var Gb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Gb.length&&(1!==
Gb.length||isNaN(Number(Gb[0]))?2!==Gb.length||isNaN(Number(Gb[0]))||isNaN(Number(Gb[1]))||(D(qd,2,Number(Gb[0])),D(qd,3,Number(Gb[1]))):D(qd,2,Number(Gb[0])));var wc=new pj;D(wc,1,H.message);D(wc,3,H.name);D(wc,6,H.sampleWeight);"ERROR"===ze?D(wc,2,2):"WARNING"===ze?D(wc,2,1):D(wc,2,0);var Uj=new nj;D(Uj,1,!0);be(Uj,mj,3,oj,qd);var Yb=new jj;D(Yb,3,window.location.href);for(var rp=L("FEXP_EXPERIMENTS",[]),Vj=0;Vj<rp.length;Vj++){var Hv=rp[Vj];Ld(Yb);Vd(Yb,5,2,!1).push(Hv)}var Wj=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");
if(!Fk()&&Wj)for(var sp=p(Object.keys(Wj)),xc=sp.next();!xc.done;xc=sp.next()){var tp=xc.value,Xj=new lj;D(Xj,1,tp);D(Xj,2,String(Wj[tp]));de(Yb,4,lj,Xj)}var Yj=H.params;if(Yj){var up=p(Object.keys(Yj));for(xc=up.next();!xc.done;xc=up.next()){var vp=xc.value,Zj=new lj;D(Zj,1,"client."+vp);D(Zj,2,String(Yj[vp]));de(Yb,4,lj,Zj)}}var wp=L("SERVER_NAME"),xp=L("SERVER_VERSION");if(wp&&xp){var ak=new lj;D(ak,1,"server.name");D(ak,2,wp);de(Yb,4,lj,ak);var bk=new lj;D(bk,1,"server.version");D(bk,2,xp);de(Yb,
4,lj,bk)}var Jg=new qj;G(Jg,jj,1,Yb);G(Jg,nj,2,Uj);G(Jg,pj,3,wc);qp=Jg}var yp=qp;if(!yp)break a;var zp=new mk;be(zp,qj,163,nk,yp);kr(zp)}else{if(Mr())var Ap=void 0;else{var Ae={stackTrace:H.stack};H.fileName&&(Ae.filename=H.fileName);var Hb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Hb.length&&(1!==Hb.length||isNaN(Number(Hb[0]))?2!==Hb.length||isNaN(Number(Hb[0]))||isNaN(Number(Hb[1]))||(Ae.lineNumber=Number(Hb[0]),Ae.columnNumber=Number(Hb[1])):Ae.lineNumber=Number(Hb[0]));
var ck={level:"ERROR_LEVEL_UNKNOWN",message:H.message,errorClassName:H.name,sampleWeight:H.sampleWeight};"ERROR"===ze?ck.level="ERROR_LEVEL_ERROR":"WARNING"===ze&&(ck.level="ERROR_LEVEL_WARNNING");var Iv={isObfuscated:!0,browserStackInfo:Ae},rd={pageUrl:window.location.href,kvPairs:[]};L("FEXP_EXPERIMENTS")&&(rd.experimentIds=L("FEXP_EXPERIMENTS"));var dk=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Fk()&&dk)for(var Bp=p(Object.keys(dk)),yc=Bp.next();!yc.done;yc=Bp.next()){var Cp=yc.value;rd.kvPairs.push({key:Cp,
value:String(dk[Cp])})}var ek=H.params;if(ek){var Dp=p(Object.keys(ek));for(yc=Dp.next();!yc.done;yc=Dp.next()){var Ep=yc.value;rd.kvPairs.push({key:"client."+Ep,value:String(ek[Ep])})}}var Fp=L("SERVER_NAME"),Gp=L("SERVER_VERSION");Fp&&Gp&&(rd.kvPairs.push({key:"server.name",value:Fp}),rd.kvPairs.push({key:"server.version",value:Gp}));Ap={errorMetadata:rd,stackTrace:Iv,logMessage:ck}}var Hp=Ap;if(!Hp)break a;fm("clientError",Hp)}if("ERROR"===ze||M("errors_flush_gel_always_killswitch"))b:if(M("migrate_events_to_ts"))c:{if(M("web_fp_via_jspb")&&
(gr(!0),!M("web_fp_via_jspb_and_json")))break c;gr()}else{if(M("web_fp_via_jspb")&&(gr(!0),!M("web_fp_via_jspb_and_json")))break b;gr()}}if(!M("suppress_error_204_logging")){var Be=H.params||{},Zb={urlParams:{a:"logerror",t:"jserror",type:H.name,msg:H.message.substr(0,250),line:H.lineNumber,level:h,"client.name":Be.name},postParams:{url:L("PAGE_NAME",window.location.href),file:H.fileName},method:"POST"};Be.version&&(Zb["client.version"]=Be.version);if(Zb.postParams){H.stack&&(Zb.postParams.stack=
H.stack);for(var Ip=p(Object.keys(Be)),fk=Ip.next();!fk.done;fk=Ip.next()){var Jp=fk.value;Zb.postParams["client."+Jp]=Be[Jp]}var gk=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(gk)for(var Kp=p(Object.keys(gk)),hk=Kp.next();!hk.done;hk=Kp.next()){var Lp=hk.value;Zb.postParams[Lp]=gk[Lp]}var Mp=L("SERVER_NAME"),Np=L("SERVER_VERSION");Mp&&Np&&(Zb.postParams["server.name"]=Mp,Zb.postParams["server.version"]=Np)}ml(L("ECATCHER_REPORT_HOST","")+"/error_204",Zb)}try{Er.add(H.message)}catch(lx){}Fr++}}}}
function Mr(){for(var a=p(Jr),b=a.next();!b.done;b=a.next())if(Wl(b.value.toLowerCase()))return!0;return!1}
function Nr(a){var b=Ja.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ia(b))}
;function Or(){this.register=new Map}
function Pr(a){a=p(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Br("ABORTED")}
Or.prototype.clear=function(){Pr(this);this.register.clear()};
var Qr=new Or;var Rr=Date.now().toString();
function Sr(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Rr)for(a=1,b=0;b<Rr.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Rr.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Tr=z.ytLoggingDocDocumentNonce_;Tr||(Tr=Sr(),A("ytLoggingDocDocumentNonce_",Tr));var Ur=Tr;var Vr={bi:0,we:1,Ge:2,Yl:3,di:4,zq:5,Om:6,Do:7,Tn:8,ro:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function Wr(a){this.G=a}
function Xr(a){return new Wr({trackingParams:a})}
Wr.prototype.getAsJson=function(){var a={};void 0!==this.G.trackingParams?a.trackingParams=this.G.trackingParams:(a.veType=this.G.veType,void 0!==this.G.veCounter&&(a.veCounter=this.G.veCounter),void 0!==this.G.elementIndex&&(a.elementIndex=this.G.elementIndex));void 0!==this.G.dataElement&&(a.dataElement=this.G.dataElement.getAsJson());void 0!==this.G.youtubeData&&(a.youtubeData=this.G.youtubeData);return a};
Wr.prototype.getAsJspb=function(){var a=new wj;if(void 0!==this.G.trackingParams){var b=this.G.trackingParams;if(null!=b)if("string"===typeof b)b=b?new nd(b,kd):sd();else if(b.constructor!==nd)if(jd(b))b=b.length?new nd(new Uint8Array(b),kd):sd();else throw Error();D(a,1,b)}else void 0!==this.G.veType&&D(a,2,this.G.veType),void 0!==this.G.veCounter&&D(a,6,this.G.veCounter),void 0!==this.G.elementIndex&&D(a,3,this.G.elementIndex);void 0!==this.G.dataElement&&(b=this.G.dataElement.getAsJspb(),G(a,wj,
7,b));void 0!==this.G.youtubeData&&G(a,Ni,8,this.G.jspbYoutubeData);return a};
Wr.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Wr.prototype.isClientVe=function(){return!this.G.trackingParams&&!!this.G.veType};function Yr(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function Zr(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function $r(a){return L(Zr(void 0===a?0:a))}
A("yt_logging_screen.getRootVeType",$r);function as(a){return(a=$r(void 0===a?0:a))?new Wr({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function bs(){var a=L("csn-to-ctt-auth-info");a||(a={},Ek("csn-to-ctt-auth-info",a));return a}
function cs(a){a=L(Yr(void 0===a?0:a));if(!a&&!L("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
A("yt_logging_screen.getCurrentCsn",cs);function ds(a,b,c){var d=bs();(c=cs(c))&&delete d[c];b&&(d[a]=b)}
function es(a){return bs()[a]}
A("yt_logging_screen.getCttAuthInfo",es);
function fs(a,b,c,d){c=void 0===c?0:c;if(a!==L(Yr(c))||b!==L(Zr(c)))if(ds(a,d,c),Ek(Yr(c),a),Ek(Zr(c),b),b=function(){setTimeout(function(){if(a)if(M("web_time_via_jspb")){var e=new xj;D(e,1,Ur);D(e,2,a);M("use_default_heartbeat_client")?rr(e):rr(e,void 0,Pp)}else e={clientDocumentNonce:Ur,clientScreenNonce:a},M("use_default_heartbeat_client")?fm("foregroundHeartbeatScreenAssociated",e):er("foregroundHeartbeatScreenAssociated",e,Pp)},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
A("yt_logging_screen.setCurrentScreen",fs);var gs=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",gs);function hs(a){zk(gs,arguments)}
;var is={ue:3611,Fd:27686,Gd:85013,Hd:23462,Jd:157557,Kd:42016,Ld:62407,Md:26926,Id:43781,Nd:51236,Od:79148,Pd:50160,Qd:77504,ce:153587,de:87907,ee:18630,ge:54445,he:80935,ie:152172,je:105675,ke:150723,le:37521,me:147285,ne:47786,oe:98349,pe:123695,qe:6827,re:29434,se:7282,te:124448,ye:32276,xe:76278,ze:147868,Ae:147869,Be:93911,Ce:106531,De:27259,Ee:27262,Fe:27263,He:21759,Ie:27107,Je:62936,Ke:160866,Le:49568,Me:160789,Ne:38408,Oe:80637,Pe:68727,Qe:68728,Re:80353,Se:80356,Te:74610,Ue:45707,Ve:83962,
We:83970,Xe:46713,Ye:89711,Ze:74612,af:155792,bf:93265,cf:74611,df:131380,ff:128979,gf:139311,hf:128978,ef:131391,jf:105350,lf:139312,mf:134800,kf:131392,pf:113533,qf:93252,rf:99357,tf:94521,uf:114252,vf:113532,wf:94522,sf:94583,xf:88E3,yf:139580,zf:93253,Af:93254,Bf:94387,Cf:94388,Df:93255,Ef:97424,nf:72502,Ff:110111,Gf:76019,If:117092,Jf:117093,Hf:89431,Kf:110466,Lf:77240,Mf:60508,Nf:148123,Of:148124,Pf:137401,Qf:137402,Rf:137046,Sf:73393,Tf:113534,Uf:92098,Vf:131381,Wf:84517,Xf:83759,Yf:162711,
Zf:162712,ag:80357,cg:86113,dg:72598,eg:72733,fg:107349,gg:124275,hg:118203,ig:133275,jg:160157,kg:152569,lg:156651,mg:133274,ng:160159,og:160158,pg:133272,qg:133273,rg:133276,sg:144507,tg:143247,ug:156652,vg:143248,wg:143249,xg:143250,yg:143251,zg:156653,Ag:144401,Cg:117431,Bg:133797,Dg:153964,Eg:128572,Fg:133405,Gg:117429,Hg:117430,Ig:117432,Jg:120080,Kg:117259,Lg:156655,Mg:156654,Ng:121692,Og:145656,Pg:156656,Qg:145655,Rg:145653,Sg:145654,Tg:145657,Ug:132972,Vg:133051,Wg:133658,Xg:132971,Yg:97615,
ah:143359,Zg:143356,dh:143361,bh:143358,fh:143360,eh:143357,gh:142303,hh:143353,ih:143354,jh:144479,kh:143355,lh:31402,nh:133624,oh:146477,ph:133623,qh:133622,mh:133621,rh:84774,th:160801,sh:95117,uh:150497,vh:98930,wh:98931,xh:98932,yh:153320,zh:153321,Ah:43347,Bh:129889,Ch:149123,Dh:45474,Eh:100352,Fh:84758,Gh:98443,Hh:117985,Ih:74613,Jh:155911,Kh:74614,Lh:64502,Mh:136032,Nh:74615,Oh:74616,Ph:122224,Qh:74617,Rh:77820,Sh:74618,Th:93278,Uh:93274,Vh:93275,Wh:93276,Xh:22110,Yh:29433,Zh:133798,ai:132295,
ci:120541,fi:82047,gi:113550,hi:75836,ii:75837,ji:42352,ki:84512,li:76065,mi:75989,ti:51879,vi:16623,wi:32594,xi:27240,yi:32633,zi:74858,Ai:156999,Ci:3945,Bi:16989,Di:45520,Ei:25488,Fi:25492,Gi:25494,Hi:55760,Ii:14057,Ji:18451,Ki:57204,Li:57203,Mi:17897,Ni:57205,Oi:18198,Pi:17898,Qi:17909,Ri:43980,Si:46220,Ti:11721,Ui:147994,Vi:49954,Wi:96369,Xi:3854,Yi:151633,Zi:56251,aj:159108,bj:25624,cj:152036,tj:16906,uj:99999,vj:68172,wj:27068,xj:47973,yj:72773,zj:26970,Aj:26971,Bj:96805,Cj:17752,Dj:73233,Ej:109512,
Fj:22256,Gj:14115,Hj:22696,Ij:89278,Jj:89277,Kj:109513,Lj:43278,Mj:43459,Nj:43464,Oj:89279,Pj:43717,Qj:55764,Rj:22255,Sj:147912,Tj:89281,Uj:40963,Vj:43277,Wj:43442,Xj:91824,Yj:120137,Zj:96367,ak:36850,bk:72694,ck:37414,dk:36851,fk:124863,ek:121343,gk:73491,hk:54473,ik:43375,jk:46674,kk:143815,lk:139095,mk:144402,nk:149968,pk:149969,qk:32473,rk:72901,sk:72906,tk:50947,uk:50612,vk:50613,wk:50942,xk:84938,yk:84943,zk:84939,Ak:84941,Bk:84944,Ck:84940,Dk:84942,Ek:35585,Fk:51926,Gk:79983,Hk:63238,Ik:18921,
Jk:63241,Kk:57893,Lk:41182,Mk:135732,Nk:33424,Ok:22207,Pk:42993,Qk:36229,Rk:22206,Sk:22205,Tk:18993,Uk:19001,Vk:18990,Wk:18991,Xk:18997,Yk:18725,Zk:19003,al:36874,bl:44763,dl:33427,fl:67793,il:22182,jl:37091,kl:34650,ll:50617,ml:47261,nl:22287,ol:25144,pl:97917,ql:62397,rl:150871,sl:150874,ul:125598,vl:137935,wl:36961,xl:108035,yl:27426,zl:27857,Al:27846,Bl:27854,Cl:69692,Dl:61411,El:39299,Fl:38696,Gl:62520,Hl:36382,Il:108701,Jl:50663,Kl:36387,Ll:14908,Ml:37533,Nl:105443,Ol:61635,Pl:62274,Ql:161670,
Rl:133818,Sl:65702,Tl:65703,Ul:65701,Vl:76256,Wl:37671,Xl:49953,Zl:36216,am:28237,bm:39553,cm:29222,dm:26107,em:38050,fm:26108,hm:120745,gm:26109,im:26110,jm:66881,km:28236,lm:14586,mm:160598,nm:57929,om:74723,pm:44098,qm:44099,tm:23528,um:61699,rm:134104,sm:134103,vm:59149,wm:101951,xm:97346,ym:118051,zm:95102,Am:64882,Bm:119505,Cm:63595,Dm:63349,Em:95101,Fm:75240,Gm:27039,Hm:68823,Im:21537,Jm:83464,Km:75707,Lm:83113,Mm:101952,Nm:101953,Pm:79610,Qm:125755,Rm:24402,Sm:24400,Tm:32925,Vm:57173,Um:156421,
Wm:122502,Xm:145268,Ym:138480,Zm:64423,an:64424,bn:33986,cn:100828,dn:129089,en:21409,jn:135155,kn:135156,ln:135157,mn:135158,nn:158225,pn:135159,qn:135160,rn:135161,tn:135162,un:135163,sn:158226,vn:158227,wn:135164,xn:135165,yn:135166,fn:11070,gn:11074,hn:17880,zn:14001,Bn:30709,Cn:30707,Dn:30711,En:30710,Fn:30708,An:26984,Gn:146143,Hn:63648,In:63649,Jn:111059,Kn:5754,Ln:20445,Mn:151308,Nn:151152,Pn:130975,On:130976,Qn:110386,Rn:113746,Sn:66557,Un:17310,Vn:28631,Wn:21589,Xn:164817,Yn:154946,Zn:68012,
ao:162617,bo:60480,co:138664,eo:141121,fo:164502,ho:31571,jo:141978,ko:150105,lo:150106,mo:150107,no:150108,oo:76980,po:41577,qo:45469,so:38669,to:13768,uo:13777,vo:141842,wo:62985,xo:4724,yo:59369,zo:43927,Ao:43928,Bo:12924,Co:100355,Fo:56219,Go:27669,Ho:10337,Eo:47896,Io:122629,Ko:139723,Jo:139722,Lo:121258,Mo:107598,No:127991,Oo:96639,Po:107536,Qo:130169,Ro:96661,So:145188,To:96658,Uo:116646,Vo:159428,Wo:121122,Xo:96660,Yo:127738,Zo:127083,ap:155281,bp:162959,cp:163566,ep:147842,fp:104443,gp:96659,
hp:147595,ip:106442,jp:162776,kp:134840,lp:63667,mp:63668,np:63669,qp:130686,rp:147036,sp:78314,tp:147799,up:148649,vp:55761,wp:127098,xp:134841,yp:96368,zp:67374,Ap:48992,Bp:146176,Cp:49956,Dp:31961,Ep:26388,Fp:23811,Gp:5E4,Hp:126250,Ip:96370,Jp:47355,Kp:47356,Lp:37935,Mp:45521,Np:21760,Op:83769,Pp:49977,Qp:49974,Rp:93497,Sp:93498,Tp:34325,Up:140759,Vp:115803,Wp:123707,Xp:100081,Yp:35309,Zp:68314,aq:25602,bq:100339,cq:143516,fq:59018,gq:18248,hq:50625,iq:9729,jq:37168,kq:37169,lq:21667,mq:16749,
nq:18635,oq:39305,pq:18046,qq:53969,rq:8213,sq:93926,tq:102852,uq:110099,wq:22678,xq:69076,yq:137575,Aq:139224,Bq:100856,Cq:154430,Dq:17736,Eq:3832,Fq:147111,Gq:55759,Hq:64031,Nq:93044,Oq:93045,Pq:34388,Qq:17657,Rq:17655,Sq:39579,Tq:39578,Uq:77448,Vq:8196,Wq:11357,Xq:69877,Yq:8197,Zq:156512,br:161613,dr:156509,er:161612,fr:161614,gr:82039};function js(){var a=vb(ks),b;return(new Bf(function(c,d){a.onSuccess=function(e){fl(e)?c(new ls(e)):d(new ms("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new ms("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new ms("Request timed out","net.timeout",e))};
b=ml("//googleads.g.doubleclick.net/pagead/id",a)})).ob(function(c){c instanceof If&&b.abort();
return Gf(c)})}
function ms(a,b,c){ab.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
u(ms,ab);function ls(a){this.xhr=a}
;function ns(){this.h=0;this.ca=null}
ns.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.ca))&&"function"===typeof a.then?a:os(a):2===this.h&&b?(a=b.call(c,this.ca))&&"function"===typeof a.then?a:ps(a):this};
ns.prototype.getValue=function(){return this.ca};
ns.prototype.$goog_Thenable=!0;function ps(a){var b=new ns;a=void 0===a?null:a;b.h=2;b.ca=void 0===a?null:a;return b}
function os(a){var b=new ns;a=void 0===a?null:a;b.h=1;b.ca=void 0===a?null:a;return b}
;function qs(a,b){if(a)return a[b.name]}
;function rs(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:al(a)?"same-origin":"cors",credentials:al(a)?"same-origin":"include"};b={};for(var d=p(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function ss(){return vg()||Vl&&Wl("applewebkit")&&!Wl("version")&&(!Wl("safari")||Wl("gsa/"))||Pc&&Wl("version/")?!0:L("EOM_VISITOR_DATA")?!1:!0}
;function ts(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in gj)if(gj[c]==b.embeddedPlayerMode){b=gj[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function us(a){ab.call(this,a.message||a.description||a.name);this.isMissing=a instanceof vs;this.isTimeout=a instanceof ms&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof If}
u(us,ab);us.prototype.name="BiscottiError";function vs(){ab.call(this,"Biscotti ID is missing from server")}
u(vs,ab);vs.prototype.name="BiscottiMissingError";var ks={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},ws=null;function xs(){if(M("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!ss())return Error("User has not consented - not fetching biscotti id.");var a=L("PLAYER_VARS",{});if("1"==tb(a))return Error("Biscotti ID is not available in private embed mode");if(ts(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Qk(){var a=xs();if(void 0!==a)return Gf(a);ws||(ws=js().then(ys).ob(function(b){return zs(2,b)}));
return ws}
function ys(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new vs;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new vs;a=a.id;Rk(a);ws=os(a);As(18E5,2);return a}
function zs(a,b){b=new us(b);Rk("");ws=ps(b);0<a&&As(12E4,a-1);throw b;}
function As(a,b){gl(function(){js().then(ys,function(c){return zs(b,c)}).ob(cb)},a)}
function Bs(){try{var a=B("yt.ads.biscotti.getId_");return a?a():Qk()}catch(b){return Gf(b)}}
;function Cs(a){if("1"!=tb(L("PLAYER_VARS",{}))){a&&Pk();try{Bs().then(function(){},function(){}),gl(Cs,18E5)}catch(b){Nk(b)}}}
;function Ds(){this.yd=!0}
function Es(a){var b={},c=xg([]);c&&(b.Authorization=c,c=a=null==a?void 0:a.sessionIndex,void 0===c&&(c=Number(L("SESSION_INDEX",0)),c=isNaN(c)?0:c),M("voice_search_auth_header_removal")||(b["X-Goog-AuthUser"]=c),"INNERTUBE_HOST_OVERRIDE"in Dk||(b["X-Origin"]=window.location.origin),void 0===a&&"DELEGATED_SESSION_ID"in Dk&&(b["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return b}
;var Fs={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};var Gs=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Hs(){var a=void 0===a?window.location.href:a;if(M("kevlar_disable_theme_param"))return null;mc(nc(5,a));try{var b=Zk(a).theme;return Gs.get(b)||null}catch(c){}return null}
;function Is(){this.h={};if(this.i=yl()){var a=tg.get("CONSISTENCY",void 0);a&&Js(this,{encryptedTokenJarContents:a})}}
Is.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.ha.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=p(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Js(this,a)}};
function Js(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&wl("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Ks=window.location.hostname.split(".").slice(-2).join(".");function Ls(){var a=L("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===L("INNERTUBE_CLIENT_NAME")&&(this.h=Ms(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Ns;Ls.getInstance=function(){Ns=B("yt.clientLocationService.instance");Ns||(Ns=new Ls,A("yt.clientLocationService.instance",Ns));return Ns};
l=Ls.prototype;l.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
l.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===L("INNERTUBE_CLIENT_NAME")?(this.h=Ms(this))&&this.h.set("yt-location-playability-token",a,15552E3):wl("YT_CL",JSON.stringify({loctok:a}),15552E3,Ks,!0))};
function Ms(a){return void 0===a.h?new Xl("yt-client-location"):a.h}
l.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=Ms(this))&&this.h.remove("yt-location-playability-token"):xl("YT_CL")};
l.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===L("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
l.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function Os(a,b){var c,d=null==(c=qs(a,fj))?void 0:c.signal;if(d&&b.Pa&&(c=b.Pa[d]))return c();var e;if((c=null==(e=qs(a,dj))?void 0:e.request)&&b.Nc&&(e=b.Nc[c]))return e();for(var f in a)if(b.Ub[f]&&(a=b.Ub[f]))return a()}
;var Ps=Symbol("injectionDeps");function Qs(a){this.name=a}
Qs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Rs(){this.key=Ss}
function Ts(){this.h=new Map;this.i=new Map}
Ts.prototype.resolve=function(a){return a instanceof Rs?Us(this,a.key,[],!0):Us(this,a,[])};
function Us(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(d.yc)var e=d.yc;else if(d.Ed)e=d[Ps]?Vs(a,d[Ps],c):[],e=d.Ed.apply(d,ia(e));else if(d.xc){e=d.xc;var f=e[Ps]?Vs(a,e[Ps],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ia(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Gr||a.i.set(b,e);return e}
function Vs(a,b,c){return b?b.map(function(d){return d instanceof Rs?Us(a,d.key,c,!0):Us(a,d,c)}):[]}
;var Ws;function Xs(){Ws||(Ws=new Ts);return Ws}
;function Ys(a){return function(){return new a}}
;var Zs={},$s=(Zs.WEB_UNPLUGGED="^unplugged/",Zs.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Zs.WEB_UNPLUGGED_OPS="^unplugged/",Zs.WEB_UNPLUGGED_PUBLIC="^unplugged/",Zs.WEB_CREATOR="^creator/",Zs.WEB_KIDS="^kids/",Zs.WEB_EXPERIMENTS="^experiments/",Zs.WEB_MUSIC="^music/",Zs.WEB_REMIX="^music/",Zs.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Zs.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Zs);
function at(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=$s[b];if(c){var d=new RegExp(c),e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries($s).forEach(function(g){var h=p(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function bt(){}
bt.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Fs:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=L("INNERTUBE_CONTEXT");if(g){g=wb(g);M("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=L("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;Al.getInstance();var m="USER_INTERFACE_THEME_LIGHT";Dl(165)?m="USER_INTERFACE_THEME_DARK":Dl(174)?m="USER_INTERFACE_THEME_LIGHT":!M("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");k=k?m:Hs()||m;h.userInterfaceTheme=k;if(!f){if(k=
Kl())h.connectionType=k;M("web_log_effective_connection_type")&&(k=Ll())&&(g.client.effectiveConnectionType=k)}var q;if(M("web_log_memory_total_kbytes")&&(null==(q=z.navigator)?0:q.deviceMemory)){var r;q=null==(r=z.navigator)?void 0:r.deviceMemory;g.client.memoryTotalKbytes=""+1E6*q}r=Zk(z.location.href);!M("web_populate_internal_geo_killswitch")&&r.internalcountrycode&&(h.internalGeo=r.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:z.location.href},M("kevlar_woffle")&&
ul.h&&(r=ul.h,h.mainAppWebInfo.pwaInstallabilityStatus=!r.h&&r.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=vl(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!M("web_lr_app_quality_killswitch")&&(r=L("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:r})),r=L("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||
{},{certificationScope:r}));if(!M("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var w=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(lb){}w=void 0}w&&(h.timeZone=w)}(w=Ik())?h.experimentsToken=w:delete h.experimentsToken;w=Jk();Is.h||(Is.h=new Is);h=Is.h.h;r=[];q=0;for(var t in h)r[q++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:w,consistencyTokenJars:r});!M("web_prequest_context_killswitch")&&(t=L("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&
(g.request.externalPrequestContext=t);w=Al.getInstance();t=Dl(58);w=w.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);w&&(g.user.lockedSafetyMode=!0);M("warm_op_csn_cleanup")?e&&(f=cs())&&(g.clientScreenNonce=f):!f&&(f=cs())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Ls.getInstance().setLocationOnInnerTubeContext(g);try{var y=bl(),E=y.bid;delete y.bid;g.adSignalsInfo={params:[],bid:E};var F=
p(Object.entries(y));for(var O=F.next();!O.done;O=F.next()){var N=p(O.value),Q=N.next().value,ca=N.next().value;y=Q;E=ca;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:y,value:""+E})}}catch(lb){Kr(lb)}F=g}else Kr(Error("Error: No InnerTubeContext shell provided in ytconfig.")),F={};F={context:F};if(O=this.h(a)){this.i(F,O,b);var U;b="/youtubei/v1/"+at(this.j());(O=null==(U=qs(a.commandMetadata,ej))?void 0:U.apiUrl)&&(b=O);U=b;(b=L("INNERTUBE_HOST_OVERRIDE"))&&(U=String(b)+String(pc(U)));b=
{};b.key=L("INNERTUBE_API_KEY");M("json_condensed_response")&&(b.prettyPrint="false");U=$k(U,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:U,ya:rs(U),ha:F,config:a};a.config.Za?a.config.Za.identity=c:a.config.Za={identity:c};return a}Kr(new P("Error: Failed to create Request from Command.",a))};
ea.Object.defineProperties(bt.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function ct(){}
u(ct,bt);ct.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",ya:rs("/getDatasyncIdsEndpoint","GET"),ha:{}}};
ct.prototype.j=function(){return[]};
ct.prototype.h=function(){};
ct.prototype.i=function(){};var dt={},et=(dt.GET_DATASYNC_IDS=Ys(ct),dt);function ft(a){var b=Ja.apply(1,arguments);if(!gt(a)||b.some(function(d){return!gt(d)}))throw Error("Only objects may be merged.");
b=p(b);for(var c=b.next();!c.done;c=b.next())ht(a,c.value);return a}
function ht(a,b){for(var c in b)if(gt(b[c])){if(c in a&&!gt(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});ht(a[c],b[c])}else if(jt(b[c])){if(c in a&&!jt(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);kt(a[c],b[c])}else a[c]=b[c];return a}
function kt(a,b){b=p(b);for(var c=b.next();!c.done;c=b.next())c=c.value,gt(c)?a.push(ht({},c)):jt(c)?a.push(kt([],c)):a.push(c);return a}
function gt(a){return"object"===typeof a&&!Array.isArray(a)}
function jt(a){return"object"===typeof a&&Array.isArray(a)}
;function lt(a,b){go.call(this,1,arguments);this.timer=b}
u(lt,go);var mt=new ho("aft-recorded",lt);var nt=window;function ot(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var S=nt.performance||nt.mozPerformance||nt.msPerformance||nt.webkitPerformance||new ot;var pt=!1,qt={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Xa(S.clearResourceTimings||S.webkitClearResourceTimings||S.mozClearResourceTimings||S.msClearResourceTimings||S.oClearResourceTimings||cb,S);function rt(a){var b=st("aft",a);if(b)return b;b=L((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=st(b[d],a);if(e)return e}return NaN}
function tt(){var a;if(M("csi_use_performance_navigation_timing")||M("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==S?void 0:null==(a=S.getEntriesByType)?void 0:null==(b=a.call(S,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=ut(e.requestStart),e.responseEnd=ut(e.responseEnd),e.redirectStart=ut(e.redirectStart),e.redirectEnd=ut(e.redirectEnd),e.domainLookupEnd=ut(e.domainLookupEnd),e.connectStart=ut(e.connectStart),e.connectEnd=
ut(e.connectEnd),e.responseStart=ut(e.responseStart),e.secureConnectionStart=ut(e.secureConnectionStart),e.domainLookupStart=ut(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=S.timing}else a=S.timing;return a}
function vt(){return(M("csi_use_time_origin")||M("csi_use_time_origin_tvhtml5"))&&S.timeOrigin?Math.floor(S.timeOrigin):S.timing.navigationStart}
function ut(a){return Math.round(vt()+a)}
function wt(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},A("ytcsi."+(a||"")+"data_",b));return b}
function xt(a){a=wt(a);a.info||(a.info={});return a.info}
function zt(a){a=wt(a);a.metadata||(a.metadata={});return a.metadata}
function At(a){a=wt(a);a.tick||(a.tick={});return a.tick}
function st(a,b){if(a=At(b)[a])return"number"===typeof a?a:a[a.length-1]}
function Bt(a){a=wt(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Ct(a){a=Bt(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function Dt(a){var b=wt(a).nonce;b||(b=Sr(),wt(a).nonce=b);return b}
function Et(a){var b=st("_start",a),c=rt(a);b&&c&&!pt&&(mo(mt,new lt(Math.round(c-b),a)),pt=!0)}
function Ft(a,b){for(var c=p(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!Ft(a[d],b[d]))return!1;return!0}
;function Gt(){if(S.getEntriesByType){var a=S.getEntriesByType("paint");if(a=kb(a,function(b){return"first-paint"===b.name}))return ut(a.startTime)}a=S.timing;
return a.dd?Math.max(0,a.dd):0}
;function Ht(){var a=B("ytcsi.debug");a||(a=[],A("ytcsi.debug",a),A("ytcsi.reference",{}));return a}
function It(a){a=a||"";var b=B("ytcsi.reference");b||(Ht(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=Ht(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var T={},Jt=(T.auto_search="LATENCY_ACTION_AUTO_SEARCH",T.ad_to_ad="LATENCY_ACTION_AD_TO_AD",T.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",T["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",T.app_startup="LATENCY_ACTION_APP_STARTUP",T["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",T["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",T["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",T["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",T.browse="LATENCY_ACTION_BROWSE",
T.cast_splash="LATENCY_ACTION_CAST_SPLASH",T.channels="LATENCY_ACTION_CHANNELS",T.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",T["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",T["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",T["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",T["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",T["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",T["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",
T["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",T["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",T["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",T["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",T["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",T["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",T["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",T.chips="LATENCY_ACTION_CHIPS",
T["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",T["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",T["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",T.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",T.embed="LATENCY_ACTION_EMBED",T.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",T.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",T.explore="LATENCY_ACTION_EXPLORE",T.home=
"LATENCY_ACTION_HOME",T.library="LATENCY_ACTION_LIBRARY",T.live="LATENCY_ACTION_LIVE",T.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",T.onboarding="LATENCY_ACTION_ONBOARDING",T["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",T.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",T.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",T.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",T.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",T["post.comments"]=
"LATENCY_ACTION_CREATOR_POST_COMMENTS",T["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",T.prebuffer="LATENCY_ACTION_PREBUFFER",T.prefetch="LATENCY_ACTION_PREFETCH",T.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",T.profile_switcher="LATENCY_ACTION_LOGIN",T.reel_watch="LATENCY_ACTION_REEL_WATCH",T.results="LATENCY_ACTION_RESULTS",T["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",T.search_ui="LATENCY_ACTION_SEARCH_UI",T.search_suggest="LATENCY_ACTION_SUGGEST",T.search_zero_state=
"LATENCY_ACTION_SEARCH_ZERO_STATE",T.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",T.seek="LATENCY_ACTION_PLAYER_SEEK",T.settings="LATENCY_ACTION_SETTINGS",T.store="LATENCY_ACTION_STORE",T.tenx="LATENCY_ACTION_TENX",T.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",T.watch="LATENCY_ACTION_WATCH",T.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",T["watch,watch7"]="LATENCY_ACTION_WATCH",T["watch,watch7_html5"]="LATENCY_ACTION_WATCH",T["watch,watch7ad"]="LATENCY_ACTION_WATCH",T["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",T.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",T.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",T["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",T["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",T["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",T["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",T["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",T["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",T["video.live_streaming"]=
"LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",T["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",T["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",T.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",T.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",T.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",T),V={},Kt=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",V.ad_docid="adVideoId",V.yt_ad_an=
"adNetworks",V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",V.is_continuation="isContinuation",
V.is_nav="isNavigation",V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",V.prt="playbackRequiresTap",
V.plt="playerInfo.playbackType",V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt="playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs="tvInfo.bedrockTriggerState",
V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",
V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),Lt="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Mt={},Nt=(Mt.ccs="CANARY_STATE_",
Mt.mver="MEASUREMENT_VERSION_",Mt.pis="PLAYER_INITIALIZED_STATE_",Mt.yt_pt="LATENCY_PLAYER_",Mt.pa="LATENCY_ACTION_",Mt.ctop="TOP_ENTITY_TYPE_",Mt.yt_vst="VIDEO_STREAM_TYPE_",Mt),Ot="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Pt(a){return Jt[a]||"LATENCY_ACTION_UNKNOWN"}
function Qt(a,b,c){c=Bt(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Kt){c=Kt[a];0<=eb(Lt,c)&&(b=!!b);a in Nt&&"string"===typeof b&&(b=Nt[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return ft({},d)}0<=eb(Ot,a)||Lr(new P("Unknown label logged with GEL CSI",a))}
;var W={LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_COMMERCE_TRANSACTION:184,LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,
LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,
LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_GENERIC_WEB_VIEW:183,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,
LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,
LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,
LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_CONNECT_TO_SESSION:190,LATENCY_ACTION_MDX_STREAM_TRANSFER:178,
LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_EDIT_AUDIO_GEN:182,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,
LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,
LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_PROMOTION_LIST:186,LATENCY_ACTION_CREATOR_PROMOTION_EDIT:185,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,
LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,
LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CMS_ISSUES:191,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,
LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_EXPERIMENTAL_WATCH_UI:181,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,
LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_DIRECT_PLAYBACK:132,
LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_STARTUP:106,LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_HOME:1,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_USER_ACTION:189,LATENCY_ACTION_INFRASTRUCTURE:188,LATENCY_ACTION_PAGE_NAVIGATION:187,LATENCY_ACTION_UNKNOWN:0};W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";
W[W.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";W[W.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";W[W.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";W[W.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";
W[W.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";W[W.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";W[W.LATENCY_ACTION_COMMERCE_TRANSACTION]="LATENCY_ACTION_COMMERCE_TRANSACTION";W[W.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";W[W.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";W[W.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";
W[W.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";W[W.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";
W[W.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";W[W.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";W[W.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";W[W.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";
W[W.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";W[W.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";W[W.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";W[W.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";W[W.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";
W[W.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";W[W.LATENCY_ACTION_GENERIC_WEB_VIEW]="LATENCY_ACTION_GENERIC_WEB_VIEW";W[W.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";W[W.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";W[W.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";W[W.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";W[W.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";
W[W.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";W[W.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";W[W.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";W[W.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";W[W.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";W[W.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";
W[W.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";W[W.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";W[W.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";W[W.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";W[W.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";W[W.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";
W[W.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";W[W.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";W[W.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";W[W.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";W[W.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";W[W.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";W[W.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";
W[W.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";W[W.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";W[W.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";W[W.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";W[W.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";W[W.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";
W[W.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";W[W.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";W[W.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";W[W.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";W[W.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";W[W.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";W[W.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";
W[W.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";W[W.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";W[W.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";W[W.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";W[W.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";W[W.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";W[W.LATENCY_ACTION_MDX_CONNECT_TO_SESSION]="LATENCY_ACTION_MDX_CONNECT_TO_SESSION";
W[W.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";W[W.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";W[W.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";W[W.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";W[W.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";W[W.LATENCY_ACTION_EDIT_AUDIO_GEN]="LATENCY_ACTION_EDIT_AUDIO_GEN";W[W.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";
W[W.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";W[W.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";W[W.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";W[W.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";W[W.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";
W[W.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";W[W.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";W[W.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";W[W.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";W[W.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";W[W.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";
W[W.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";W[W.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";W[W.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";W[W.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";W[W.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";W[W.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";
W[W.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";W[W.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";W[W.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";W[W.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";W[W.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";W[W.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";W[W.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";
W[W.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";W[W.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";W[W.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";W[W.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";W[W.LATENCY_ACTION_CREATOR_PROMOTION_LIST]="LATENCY_ACTION_CREATOR_PROMOTION_LIST";W[W.LATENCY_ACTION_CREATOR_PROMOTION_EDIT]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT";
W[W.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";
W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";W[W.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";W[W.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";
W[W.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";W[W.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";W[W.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";W[W.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";W[W.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_CMS_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ISSUES";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";
W[W.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";W[W.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";W[W.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";W[W.LATENCY_ACTION_EXPERIMENTAL_WATCH_UI]="LATENCY_ACTION_EXPERIMENTAL_WATCH_UI";W[W.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";
W[W.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";W[W.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";W[W.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";W[W.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";W[W.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";W[W.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";W[W.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";W[W.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";
W[W.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";W[W.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";W[W.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";W[W.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";W[W.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";
W[W.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";W[W.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";W[W.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";W[W.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";W[W.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";W[W.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";W[W.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";W[W.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";
W[W.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";W[W.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";W[W.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";W[W.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";W[W.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";W[W.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";W[W.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";
W[W.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";W[W.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";W[W.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";W[W.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";W[W.LATENCY_ACTION_USER_ACTION]="LATENCY_ACTION_USER_ACTION";W[W.LATENCY_ACTION_INFRASTRUCTURE]="LATENCY_ACTION_INFRASTRUCTURE";W[W.LATENCY_ACTION_PAGE_NAVIGATION]="LATENCY_ACTION_PAGE_NAVIGATION";W[W.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";
var Rt={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};Rt[Rt.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";Rt[Rt.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";Rt[Rt.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";var X={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};
X[X.CONN_INVALID]="CONN_INVALID";X[X.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";X[X.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";X[X.CONN_WIFI_METERED]="CONN_WIFI_METERED";X[X.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";X[X.CONN_DISCO]="CONN_DISCO";X[X.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";X[X.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";X[X.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";X[X.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";X[X.CONN_WIFI]="CONN_WIFI";X[X.CONN_NONE]="CONN_NONE";X[X.CONN_UNKNOWN]="CONN_UNKNOWN";
X[X.CONN_DEFAULT]="CONN_DEFAULT";
var Y={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Y[Y.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Y[Y.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Y[Y.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Y[Y.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Y[Y.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Y[Y.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Y[Y.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Y[Y.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Y[Y.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Y[Y.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Y[Y.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Y[Y.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Y[Y.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Y[Y.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Y[Y.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Y[Y.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Y[Y.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Y[Y.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Y[Y.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Y[Y.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Y[Y.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Y[Y.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Y[Y.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Y[Y.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Y[Y.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Y[Y.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Y[Y.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var St={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};St[St.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
St[St.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";St[St.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";St[St.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";St[St.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";St[St.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";St[St.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";St[St.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var Tt={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};Tt[Tt.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";Tt[Tt.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";Tt[Tt.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";Tt[Tt.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var Ut={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
Ut[Ut.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";Ut[Ut.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var Vt={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};Vt[Vt.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";Vt[Vt.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";Vt[Vt.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
Vt[Vt.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";Vt[Vt.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";Vt[Vt.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var Wt={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};Wt[Wt.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";Wt[Wt.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";Wt[Wt.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";Wt[Wt.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var Xt={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};Xt[Xt.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";Xt[Xt.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";Xt[Xt.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var Yt={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};Yt[Yt.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
Yt[Yt.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";Yt[Yt.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var Zt="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo webViewInfo prefetchInfo accelerationSession commerceInfo webInfo tvInfo kabukiInfo mwebInfo musicInfo".split(" ");var $t=z.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",$t);function au(){this.h=0}
function bu(){au.h||(au.h=new au);return au.h}
au.prototype.tick=function(a,b,c,d){cu(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},M("web_csi_via_jspb")?(d=new jk,D(d,1,a),D(d,2,b),a=new mk,be(a,jk,5,nk,d),kr(a,c)):fm("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
au.prototype.info=function(a,b,c){var d=Object.keys(a).join("");cu(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,fm("latencyActionInfo",a,{cttAuthInfo:c}))};
au.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));cu(this,"info_"+d+"_"+b)||(D(a,2,b),b={cttAuthInfo:c},c=new mk,be(c,Lj,7,nk,a),kr(c,b))};
au.prototype.span=function(a,b,c){var d=Object.keys(a).join("");cu(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,fm("latencyActionSpan",a,{cttAuthInfo:c}))};
function cu(a,b){$t[b]=$t[b]||{count:0};var c=$t[b];c.count++;c.time=R();a.h||(a.h=Nl(function(){var d=R(),e;for(e in $t)$t[e]&&6E4<d-$t[e].time&&delete $t[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new P("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Lr(c)),!0):!1}
;function du(){var a=["ol"];It("").info.actionType="embed";a&&Ek("TIMING_AFT_KEYS",a);Ek("TIMING_ACTION","embed");if(M("web_csi_via_jspb")){a=L("TIMING_INFO",{});var b=new Lj;a=p(Object.entries(a));for(var c=a.next();!c.done;c=a.next()){var d=p(c.value);c=d.next().value;d=d.next().value;switch(c){case "GetBrowse_rid":var e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);break;case "GetGuide_rid":e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);break;case "GetHome_rid":e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);
break;case "GetPlayer_rid":e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);break;case "GetSearch_rid":e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);break;case "GetSettings_rid":e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);break;case "GetTrending_rid":e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);break;case "GetWatchNext_rid":e=new ik;D(e,1,c);D(e,2,String(d));Nj(b,e);break;case "yt_red":D(b,14,!!d);break;case "yt_ad":D(b,9,!!d)}}eu(b);b=new Lj;b=D(b,25,!0);b=D(b,1,W[Pt(L("TIMING_ACTION"))]);(a=L("PREVIOUS_ACTION"))&&
D(b,13,W[Pt(a)]);(a=L("CLIENT_PROTOCOL"))&&D(b,33,a);(a=L("CLIENT_TRANSPORT"))&&D(b,34,a);(a=cs())&&"UNDEFINED_CSN"!==a&&D(b,4,a);a=fu();1!==a&&-1!==a||D(b,6,!0);a=xt();D(b,3,"cold");gu(a);a=hu();if(0<a.length)for(a=p(a),c=a.next();!c.done;c=a.next())c=c.value,d=new Kj,D(d,1,c),de(b,83,Kj,d);eu(b)}else{a=L("TIMING_INFO",{});for(b in a)a.hasOwnProperty(b)&&iu(b,a[b]);b={isNavigation:!0,actionType:Pt(L("TIMING_ACTION"))};if(a=L("PREVIOUS_ACTION"))b.previousAction=Pt(a);if(a=L("CLIENT_PROTOCOL"))b.httpProtocol=
a;if(a=L("CLIENT_TRANSPORT"))b.transportProtocol=a;(a=cs())&&"UNDEFINED_CSN"!==a&&(b.clientScreenNonce=a);a=fu();if(1===a||-1===a)b.isVisible=!0;xt();b.loadType="cold";gu(xt());a=hu();if(0<a.length)for(b.resourceInfo=[],a=p(a),c=a.next();!c.done;c=a.next())b.resourceInfo.push({resourceCache:c.value});ju(b)}b=xt();a=Ct();if(!(M("skip_setting_info_in_csi_data_object")&&"cold"!==zt().loadType||"cold"!==b.yt_lt&&"cold"!==a.loadType)){c=At();d=Bt();d=d.gelTicks?d.gelTicks:d.gelTicks={};for(var f in c)if(!(f in
d))if("number"===typeof c[f])Z(f,st(f));else if(M("log_repeated_ytcsi_ticks")){e=p(c[f]);for(var g=e.next();!g.done;g=e.next())Z(f.slice(1),g.value)}f={};c=!1;d=p(Object.keys(b));for(e=d.next();!e.done;e=d.next())e=e.value,(e=Qt(e,b[e]))&&!Ft(Ct(),e)&&(ft(a,e),ft(f,e),c=!0);c&&ju(f)}A("ytglobal.timingready_",!0);f=L("TIMING_ACTION");B("ytglobal.timingready_")&&f&&"_start"in At()&&rt()&&Et()}
function iu(a,b,c,d){if(null!==b){var e=xt(c);M("skip_setting_info_in_csi_data_object")?"yt_lt"===a&&(e="string"===typeof b?b:""+b,zt(c).loadType=e):e[a]=b;(a=Qt(a,b,c))&&ju(a,c,d)}}
function ju(a,b,c){if(!M("web_csi_via_jspb")||(void 0===c?0:c))c=It(b||""),ft(c.info,a),M("skip_setting_info_in_csi_data_object")&&a.loadType&&(c=a.loadType,zt(b).loadType=c),ft(Ct(b),a),c=Dt(b),b=wt(b).cttAuthInfo,bu().info(a,c,b);else{c=new Lj;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":D(c,1,W[a[e]]);break;case "clientActionNonce":D(c,2,a[e]);break;case "clientScreenNonce":D(c,4,a[e]);break;case "loadType":D(c,3,a[e]);break;case "isPrewarmedLaunch":D(c,
92,a[e]);break;case "isFirstInstall":D(c,55,a[e]);break;case "networkType":D(c,5,Rt[a[e]]);break;case "connectionType":D(c,26,X[a[e]]);break;case "detailedConnectionType":D(c,27,Y[a[e]]);break;case "isVisible":D(c,6,a[e]);break;case "playerType":D(c,7,St[a[e]]);break;case "clientPlaybackNonce":D(c,8,a[e]);break;case "adClientPlaybackNonce":D(c,28,a[e]);break;case "previousCpn":D(c,77,a[e]);break;case "targetCpn":D(c,76,a[e]);break;case "isMonetized":D(c,9,a[e]);break;case "isPrerollAllowed":D(c,16,
a[e]);break;case "isPrerollShown":D(c,17,a[e]);break;case "adType":D(c,12,a[e]);break;case "adTypesAllowed":D(c,36,a[e]);break;case "adNetworks":D(c,37,a[e]);break;case "previousAction":D(c,13,W[a[e]]);break;case "isRedSubscriber":D(c,14,a[e]);break;case "serverTimeMs":D(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":D(c,20,a[e]);break;case "targetVideoId":D(c,78,a[e]);break;case "adBreakType":D(c,21,Tt[a[e]]);break;case "isNavigation":D(c,25,a[e]);break;case "viewportHeight":D(c,
29,a[e]);break;case "viewportWidth":D(c,30,a[e]);break;case "screenHeight":D(c,84,a[e]);break;case "screenWidth":D(c,85,a[e]);break;case "browseId":D(c,31,a[e]);break;case "isCacheHit":D(c,32,a[e]);break;case "httpProtocol":D(c,33,a[e]);break;case "transportProtocol":D(c,34,a[e]);break;case "searchQuery":D(c,41,a[e]);break;case "isContinuation":D(c,42,a[e]);break;case "availableProcessors":D(c,43,a[e]);break;case "sdk":D(c,44,a[e]);break;case "isLocalStream":D(c,45,a[e]);break;case "navigationRequestedSameUrl":D(c,
64,a[e]);break;case "shellStartupDurationMs":D(c,70,a[e]);break;case "appInstallDataAgeMs":D(c,73,a[e]);break;case "latencyActionError":D(c,71,Ut[a[e]]);break;case "actionStep":D(c,79,a[e]);break;case "jsHeapSizeLimit":D(c,80,a[e]);break;case "totalJsHeapSize":D(c,81,a[e]);break;case "usedJsHeapSize":D(c,82,a[e]);break;case "sourceVideoDurationMs":D(c,90,a[e]);break;case "videoOutputFrames":D(c,93,a[e]);break;case "isResume":D(c,104,a[e]);break;case "adPrebufferedTimeSecs":D(c,39,a[e]);break;case "isLivestream":D(c,
47,a[e]);break;case "liveStreamMode":D(c,91,Vt[a[e]]);break;case "adCpn2":D(c,48,a[e]);break;case "adDaiDriftMillis":D(c,49,a[e]);break;case "videoStreamType":D(c,53,Wt[a[e]]);break;case "playbackRequiresTap":D(c,56,a[e]);break;case "performanceNavigationTiming":D(c,67,a[e]);break;case "transactionType":D(c,74,Xt[a[e]]);break;case "playerRotationType":D(c,101,Yt[a[e]]);break;case "allowedPreroll":D(c,10,a[e]);break;case "shownPreroll":D(c,11,a[e]);break;case "getHomeRequestId":D(c,57,a[e]);break;
case "getSearchRequestId":D(c,60,a[e]);break;case "getPlayerRequestId":D(c,61,a[e]);break;case "getWatchNextRequestId":D(c,62,a[e]);break;case "getBrowseRequestId":D(c,63,a[e]);break;case "getLibraryRequestId":D(c,66,a[e]);break;default:Zt.includes(f)&&Nk(new P("Codegen laipb translator asked to translate message field",""+f))}}catch(g){Nk(Error("Codegen laipb translator failed to set "+f))}}eu(c,b)}}
function eu(a,b){if(M("skip_setting_info_in_csi_data_object")){var c=fe(Ud(a,3),"");c&&(zt(b).loadType=c)}else c=Bt(b),c.jspbInfos||(c.jspbInfos=[]),c.jspbInfos.push(le(a));It(b||"").jspbInfo.push(a);c=Dt(b);b=wt(b).cttAuthInfo;bu().jspbInfo(a,c,b)}
function Z(a,b,c){if(!b&&"_"!==a[0]){var d=a;S.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),S.mark(d))}d=It(c||"");d.tick[a]=b||R();if(d.callback&&d.callback[a]){d=p(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=Bt(c);d.gelTicks&&(d.gelTicks[a]=!0);e=At(c);d=b||R();M("log_repeated_ytcsi_ticks")?a in e||(e[a]=d):e[a]=d;e=Dt(c);var f=wt(c).cttAuthInfo;"_start"===a?(a=bu(),cu(a,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},M("web_csi_via_jspb")?(a=new Jj,
D(a,1,e),e=new mk,be(e,Jj,6,nk,a),kr(e,b)):fm("latencyActionBaselined",{clientActionNonce:e},b))):bu().tick(a,e,b,f);Et(c);return d}
function ku(){var a=Dt();requestAnimationFrame(function(){setTimeout(function(){a===Dt()&&Z("ol",void 0,void 0)},0)})}
function fu(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Rp+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function gu(a){var b=tt(),c=vt(),d=L("CSI_START_TIMESTAMP_MILLIS",0);0<d&&!M("embeds_web_enable_csi_start_override_killswitch")&&(c=d);c&&(Z("srt",b.responseStart),1!==a.prerender&&Z("_start",c,void 0));a=Gt();0<a&&Z("fpt",a);a=tt();a.isPerformanceNavigationTiming&&ju({performanceNavigationTiming:!0});Z("nreqs",a.requestStart,void 0);Z("nress",a.responseStart,void 0);Z("nrese",a.responseEnd,void 0);0<a.redirectEnd-a.redirectStart&&(Z("nrs",a.redirectStart,void 0),Z("nre",a.redirectEnd,void 0));0<
a.domainLookupEnd-a.domainLookupStart&&(Z("ndnss",a.domainLookupStart,void 0),Z("ndnse",a.domainLookupEnd,void 0));0<a.connectEnd-a.connectStart&&(Z("ntcps",a.connectStart,void 0),Z("ntcpe",a.connectEnd,void 0));a.secureConnectionStart>=vt()&&0<a.connectEnd-a.secureConnectionStart&&(Z("nstcps",a.secureConnectionStart,void 0),Z("ntcpe",a.connectEnd,void 0));S&&"getEntriesByType"in S&&lu()}
function mu(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);ic()&&a.setAttribute("nonce",ic());return c?(a=S.getEntriesByName(c))&&a[0]&&(a=a[0],c=vt(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function hu(){var a=[];if(document.querySelector&&S&&S.getEntriesByName)for(var b in qt)if(qt.hasOwnProperty(b)){var c=qt[b];mu(b,c)&&a.push(c)}return a}
function lu(){var a=window.location.protocol,b=S.getEntriesByType("resource");b=gb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=ib(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",ut(b.startTime)),Z("wffe",ut(b.responseEnd)))}
var nu=window;nu.ytcsi&&(nu.ytcsi.info=iu,nu.ytcsi.tick=Z);var ou="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" "),pu=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function qu(a,b,c,d){this.m=a;this.L=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Pa||(a.Pa={});a.Pa=Object.assign({},et,a.Pa)}
function ru(a,b,c,d){if(void 0!==qu.h){if(d=qu.h,a=[a!==d.m,b!==d.L,c!==d.l,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new P("InnerTubeTransportService is already initialized",a);
}else qu.h=new qu(a,b,c,d)}
function su(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Fs:c;var d=Os(b,a.m);if(!d)return Gf(new P("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?new Bf(function(f){var g,h,k;return x(function(m){if(1==m.h){h="cors"===(null==(g=e.ya)?void 0:g.mode)?"cors":void 0;if(a.l.yd){var q=e.config,r;q=null==q?void 0:null==(r=q.Za)?void 0:r.sessionIndex;r=Es({sessionIndex:q});k=Object.assign({},tu(h),r);return m.A(2)}return v(m,uu(e.config,
h),3)}2!=m.h&&(k=m.i);f(vu(a,e,k));m.h=0})}):Gf(new P("Error: Failed to build request for command.",b))}
function wu(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.Er)?0:d.Hr)&&a.j){d=p(ou);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function vu(a,b,c){var d,e,f,g,h,k,m,q,r,w,t,y,E,F,O,N,Q,ca,U,lb,Wa,na,H,la,fa,xe,ye,od;return x(function(pa){switch(pa.h){case 1:pa.A(2);break;case 3:if((d=pa.i)&&!d.isExpired())return pa.return(Promise.resolve(d.h()));case 2:if(null==(e=b)?0:null==(f=e.ha)?0:f.context)for(g=p([]),h=g.next();!h.done;h=g.next())k=h.value,k.Ar(b.ha.context);if(null==(m=a.i)||!m.Fr(b.input,b.ha)){pa.A(4);break}return v(pa,a.i.vr(b.input,b.ha),5);case 5:return q=pa.i,M("kevlar_process_local_innertube_responses_killswitch")||
wu(a,q,b),pa.return(q);case 4:return(t=null==(w=b.config)?void 0:w.Ea)&&a.h.has(t)&&M("web_memoize_inflight_requests")?r=a.h.get(t):(y=JSON.stringify(b.ha),O=null!=(F=null==(E=b.ya)?void 0:E.headers)?F:{},b.ya=Object.assign({},b.ya,{headers:Object.assign({},O,c)}),N=Object.assign({},b.ya),"POST"===b.ya.method&&(N=Object.assign({},N,{body:y})),(null==(Q=b.config)?0:Q.ld)&&Z(b.config.ld),ca=function(){return a.L.fetch(b.input,N,b.config)},r=ca(),t&&a.h.set(t,r)),v(pa,r,6);
case 6:U=pa.i;if(M("web_one_platform_error_handling")&&U&&"error"in U&&(null==(lb=U)?0:null==(Wa=lb.error)?0:Wa.details))for(na=U.error.details,H=p(na),la=H.next();!la.done;la=H.next())fa=la.value,(xe=fa["@type"])&&-1<pu.indexOf(xe)&&(delete fa["@type"],U=fa);t&&a.h.has(t)&&a.h.delete(t);(null==(ye=b.config)?0:ye.md)&&Z(b.config.md);if(U||null==(od=a.i)||!od.lr(b.input,b.ha)){pa.A(7);break}return v(pa,a.i.ur(b.input,b.ha),8);case 8:U=pa.i;case 7:return wu(a,U,b),pa.return(U||void 0)}})}
function uu(a,b){var c,d,e,f;return x(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Za)?void 0:d.sessionIndex;var h=Es({sessionIndex:e});if(!(h instanceof Bf)){var k=new Bf(cb);Cf(k,2,h);h=k}return v(g,h,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},tu(b),f)))})}
function tu(a){var b={"Content-Type":"application/json"};L("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=L("EOM_VISITOR_DATA"):L("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=L("VISITOR_DATA"));M("track_webfe_innertube_auth_mismatch")&&(b["X-Youtube-Bootstrap-Logged-In"]=L("LOGGED_IN",!1));"cors"!==a&&((a=L("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=L("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=L("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=
a),(a=L("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var xu=new Qs("INNERTUBE_TRANSPORT_TOKEN");var yu=["share/get_web_player_share_panel"],zu=["feedback"],Au=["notification/modify_channel_preference"],Bu=["browse/edit_playlist"],Cu=["subscription/subscribe"],Du=["subscription/unsubscribe"];function Eu(){}
u(Eu,bt);Eu.prototype.j=function(){return Cu};
Eu.prototype.h=function(a){return qs(a,yk)||void 0};
Eu.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ea.Object.defineProperties(Eu.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Fu(){}
u(Fu,bt);Fu.prototype.j=function(){return Du};
Fu.prototype.h=function(a){return qs(a,xk)||void 0};
Fu.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ea.Object.defineProperties(Fu.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Gu(){}
u(Gu,bt);Gu.prototype.j=function(){return zu};
Gu.prototype.h=function(a){return qs(a,hj)||void 0};
Gu.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ea.Object.defineProperties(Gu.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Hu(){}
u(Hu,bt);Hu.prototype.j=function(){return Au};
Hu.prototype.h=function(a){return qs(a,wk)||void 0};
Hu.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function Iu(){}
u(Iu,bt);Iu.prototype.j=function(){return Bu};
Iu.prototype.h=function(a){return qs(a,vk)||void 0};
Iu.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Ju(){}
u(Ju,bt);Ju.prototype.j=function(){return yu};
Ju.prototype.h=function(a){return qs(a,uk)};
Ju.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Ss=new Qs("NETWORK_SLI_TOKEN");function Ku(a){this.h=a}
Ku.prototype.fetch=function(a,b){var c=this,d,e;return x(function(f){c.h&&(d=mc(nc(5,Dc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=new window.Request(a,b);return M("web_fetch_promise_cleanup_killswitch")?f.return(Promise.resolve(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Lr(g)}))):f.return(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Lr(g)}))})};
Ku.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.rr(),b=b.then(function(c){Lr(new P("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
Ku[Ps]=[new Rs];var Lu=new Qs("NETWORK_MANAGER_TOKEN");var Mu;function Nu(a){go.call(this,1,arguments);this.csn=a}
u(Nu,go);var po=new ho("screen-created",Nu),Ou=[],Qu=Pu,Ru=0;function Su(a,b,c,d,e,f,g){function h(){Lr(new P("newScreen() parent element does not have a VE - rootVe",b))}
var k=Qu(),m=new Wr({veType:b,youtubeData:f,jspbYoutubeData:void 0});f={aa:k};e&&(f.cttAuthInfo=e);M("il_via_jspb")?(e=new yj,e.i(k),zj(e,m.getAsJspb()),c&&c.visualElement?(m=new Aj,c.clientScreenNonce&&D(m,2,c.clientScreenNonce),Bj(m,c.visualElement.getAsJspb()),g&&D(m,4,ok[g]),G(e,Aj,5,m)):c&&h(),d&&D(e,3,d),pr(e,f,a)):(e={csn:k,pageVe:m.getAsJson()},c&&c.visualElement?(e.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(e.implicitGesture.gestureType=g)):
c&&h(),d&&(e.cloneCsn=d),a?er("screenCreated",e,a,f):fm("screenCreated",e,f));mo(po,new Nu(k));return k}
function Tu(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:es(b)||void 0,
aa:b};d=p(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(rb(g)||!g.trackingParams&&!g.veType)&&Lr(Error("Child VE logged with no data"));if(M("il_via_jspb")){var h=new Cj;h.i(b);Ej(h,c.getAsJspb());hb(e,function(k){k=k.getAsJspb();de(h,3,wj,k)});
"UNDEFINED_CSN"===b?Uu("visualElementAttached",f,void 0,h):qr(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:hb(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"===b?Uu("visualElementAttached",f,c):a?er("visualElementAttached",c,a,f):fm("visualElementAttached",c,f)}
function Pu(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return ed(b,3)}
function Uu(a,b,c,d){Ou.push({Eb:a,payload:c,na:d,options:b});Ru||(Ru=qo())}
function ro(a){if(Ou){for(var b=p(Ou),c=b.next();!c.done;c=b.next())if(c=c.value,M("il_via_jspb")&&c.na)switch(c.na.i(a.csn),c.Eb){case "screenCreated":pr(c.na,c.options);break;case "visualElementAttached":qr(c.na,c.options);break;case "visualElementShown":lr(c.na,c.options);break;case "visualElementHidden":mr(c.na,c.options);break;case "visualElementGestured":nr(c.na,c.options);break;case "visualElementStateChanged":or(c.na,c.options);break;default:Lr(new P("flushQueue unable to map payloadName to JSPB setter"))}else c.payload&&
(c.payload.csn=a.csn,er(c.Eb,c.payload,null,c.options));Ou.length=0}Ru=0}
;function Vu(){this.j=new Set;this.h=new Set;this.l=new Map;this.client=Pp;this.csn=null}
function Wu(){Vu.h||(Vu.h=new Vu);return Vu.h}
Vu.prototype.i=function(a){this.client=a};
Vu.prototype.clear=function(){this.j.clear();this.h.clear();this.l.clear();this.csn=null};function Xu(){this.j=new Set;this.h=new Set;this.l=new Map}
Xu.prototype.i=function(a){M("use_ts_visibilitylogger")&&Wu().i(a)};
Xu.prototype.clear=function(){M("use_ts_visibilitylogger")?Wu().clear():(this.j.clear(),this.h.clear(),this.l.clear())};
Na(Xu);function Yu(){this.o=[];this.M=[];this.h=[];this.m=[];this.B=[];this.j=new Set;this.s=new Map}
Yu.prototype.i=function(a){this.client=a};
function Zu(a,b,c){c=void 0===c?0:c;b.then(function(d){a.j.has(c)&&a.l&&a.l();var e=cs(c),f=as(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&Tu(a.client,e,f,[Xr(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&Tu(a.client,e,f,[Xr(d.playerResponse.trackingParams)])}})}
function $u(a,b,c,d){d=void 0===d?0:d;if(a.j.has(d))a.o.push([b,c]);else{var e=cs(d);c=c||as(d);e&&c&&Tu(a.client,e,c,[b])}}
Yu.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=cs(void 0===c?0:c)){a=this.client;var e=Xr(d);d={cttAuthInfo:es(c)||void 0,aa:c};M("il_via_jspb")?(b=new Fj,b.i(c),e=e.getAsJspb(),G(b,wj,2,e),D(b,4,ok.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK),"UNDEFINED_CSN"===c?Uu("visualElementGestured",d,void 0,b):nr(b,d,a)):(e={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(e.clientData=b),"UNDEFINED_CSN"===c?Uu("visualElementGestured",
d,e):a?er("visualElementGestured",e,a,d):fm("visualElementGestured",e,d));b=!0}else b=!1;else b=!1;return b};
function av(a,b,c){c=void 0===c?{}:c;a.j.add(c.layer||0);a.l=function(){bv(a,b,c);var f=as(c.layer);if(f){for(var g=p(a.o),h=g.next();!h.done;h=g.next())h=h.value,$u(a,h[0],h[1]||f,c.layer);f=p(a.M);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=cs(g);var m=k[0]||as(g);if(h&&m){g=a.client;var q=k[1];k={cttAuthInfo:es(h)||void 0,aa:h};M("il_via_jspb")?(q=new Ij,q.i(h),m=m.getAsJspb(),G(q,wj,2,m),"UNDEFINED_CSN"===h?Uu("visualElementStateChanged",k,void 0,q):or(q,k,g)):
(m={csn:h,ve:m.getAsJson(),clientData:q},"UNDEFINED_CSN"===h?Uu("visualElementStateChanged",k,m):g?er("visualElementStateChanged",m,g,k):fm("visualElementStateChanged",m,k))}}}};
cs(c.layer)||a.l();if(c.Xb)for(var d=p(c.Xb),e=d.next();!e.done;e=d.next())Zu(a,e.value,c.layer);else Kr(Error("Delayed screen needs a data promise."))}
function bv(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.fd?c.fd:c.layer;var e=cs(d);d=as(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=L("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=Su(a.client,b,f,c.Wb,c.cttAuthInfo,g,c.sr)}catch(m){Nr(m,{Cr:b,rootVe:d,zr:void 0,mr:e,yr:f,Wb:c.Wb});Kr(m);return}fs(k,b,c.layer,c.cttAuthInfo);
if(b=e&&"UNDEFINED_CSN"!==e&&d){a:{b=p(Object.values(Vr));for(f=b.next();!f.done;f=b.next())if(cs(f.value)===e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,g=!0,h=(g=void 0===g?!1:g)?16:8,f={cttAuthInfo:es(e)||void 0,aa:e,Yb:g},M("il_via_jspb")?(h=new Gj,h.i(e),d=d.getAsJspb(),G(h,wj,2,d),D(h,4,g?16:8),"UNDEFINED_CSN"===e?Uu("visualElementHidden",f,void 0,h):mr(h,f,b)):(d={csn:e,ve:d.getAsJson(),eventType:h},"UNDEFINED_CSN"===e?Uu("visualElementHidden",f,d):b?er("visualElementHidden",d,b,f):fm("visualElementHidden",
d,f)));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=k||"");ju({clientScreenNonce:k});d=Xu.getInstance();M("use_ts_visibilitylogger")?(d=Wu(),d.clear(),d.csn=cs()):d.clear();d=as(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(M("web_mark_root_visible")||M("music_web_mark_root_visible"))&&(e=k,k={cttAuthInfo:es(e)||void 0,aa:e},M("il_via_jspb")?(b=new Hj,b.i(e),f=d.getAsJspb(),G(b,wj,2,f),D(b,4,1),"UNDEFINED_CSN"===e?Uu("visualElementShown",k,void 0,b):lr(b,k)):(b={csn:e,ve:d.getAsJson(),
eventType:1},"UNDEFINED_CSN"===e?Uu("visualElementShown",k,b):fm("visualElementShown",b,k)));a.j.delete(c.layer||0);a.l=void 0;e=p(a.s);for(k=e.next();!k.done;k=e.next())b=p(k.value),k=b.next().value,b=b.next().value,b.has(c.layer)&&d&&$u(a,k,d,c.layer);for(c=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(m){Kr(m)}}for(c=a.m.length=0;c<a.B.length;c++){e=a.B[c];try{e()}catch(m){Kr(m)}}}
;function cv(){var a,b,c;return x(function(d){if(1==d.h)return a=Xs().resolve(xu),a?v(d,su(a),2):(Lr(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return Lr(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.pr;return d.return(c)}Lr(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var dv=z.caches,ev;function fv(a){var b=a.indexOf(":");return-1===b?{kc:a}:{kc:a.substring(0,b),datasyncId:a.substring(b+1)}}
function gv(){return x(function(a){if(void 0!==ev)return a.return(ev);ev=new Promise(function(b){var c;return x(function(d){switch(d.h){case 1:return ya(d,2),v(d,dv.open("test-only"),4);case 4:return v(d,dv.delete("test-only"),5);case 5:za(d,3);break;case 2:if(c=Aa(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(ev)})}
function hv(a){var b,c,d,e,f,g,h;x(function(k){if(1==k.h)return v(k,gv(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return v(k,dv.keys(),3)}c=k.i;d=p(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=fv(f),h=g.datasyncId,!h||a.includes(h)||b.push(dv.delete(f));return k.return(Promise.all(b).then(function(m){return m.some(function(q){return q})}))})}
function iv(){var a,b,c,d,e,f,g;return x(function(h){if(1==h.h)return v(h,gv(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=Ul("cache contains other");return v(h,dv.keys(),3)}b=h.i;c=p(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=fv(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function jv(){try{return!!self.localStorage}catch(a){return!1}}
;function kv(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function lv(a){if(jv()){var b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=kv(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function mv(){if(!jv())return!1;var a=Ul(),b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next())if(c=kv(c.value),void 0!==c&&c!==a)return!0;return!1}
;function nv(){cv().then(function(a){a&&(sn(a),hv(a),lv(a))})}
function ov(){var a=new To;$h.U(function(){var b,c,d,e;return x(function(f){switch(f.h){case 1:if(M("ytidb_clear_optimizations_killswitch")){f.A(2);break}b=Ul("clear");if(b.startsWith("V")){var g=[b];sn(g);hv(g);lv(g);return f.return()}c=mv();return v(f,iv(),3);case 3:return d=f.i,v(f,tn(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.V()?nv():a.l.add("publicytnetworkstatus-online",nv,!0,void 0,void 0),f.h=0}})})}
;function pv(a){a&&(a.dataset?a.dataset[qv("loaded")]="true":a.setAttribute("data-loaded","true"))}
function rv(a,b){return a?a.dataset?a.dataset[qv(b)]:a.getAttribute("data-"+b):null}
var sv={};function qv(a){return sv[a]||(sv[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var tv=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,uv=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function vv(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(tv,""),c=c.replace(uv,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else wv(a,b,c)}
function wv(a,b,c){c=void 0===c?null:c;var d=xv(a),e=document.getElementById(d),f=e&&rv(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=kq(d,b),b=""+Ra(b),yv[b]=f),g||(e=zv(a,d,function(){rv(e,"loaded")||(pv(e),nq(d),gl(Ya(oq,d),0))},c)))}
function zv(a,b,c,d){d=void 0===d?null:d;var e=of("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Jh(e,Lb(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Av(a){a=xv(a);var b=document.getElementById(a);b&&(oq(a),b.parentNode.removeChild(b))}
function Bv(a,b){a&&b&&(a=""+Ra(b),(a=yv[a])&&mq(a))}
function xv(a){var b=document.createElement("a");fc(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+kc(a)}
var yv={};var Cv=[],Dv=!1;function Ev(){if(!M("disable_biscotti_fetch_for_ad_blocker_detection")&&!M("disable_biscotti_fetch_entirely_for_all_web_clients")&&ss()){var a=L("PLAYER_VARS",{});if("1"!=tb(a)&&!ts(a)){var b=function(){Dv=!0;"google_ad_status"in window?Ek("DCLKSTAT",1):Ek("DCLKSTAT",2)};
try{vv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Cv.push($h.U(function(){if(!(Dv||"google_ad_status"in window)){try{Bv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Dv=!0;Ek("DCLKSTAT",3)}},5E3))}}}
function Fv(){var a=Number(L("DCLKSTAT",0));return isNaN(a)?0:a}
;function Gv(){this.state=1;this.h=null}
l=Gv.prototype;
l.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterScript)?d:null,f;d=null!=(f=a.interpreterUrl)?f:null;a.interpreterSafeScript&&(e=a.interpreterSafeScript,Db("From proto message. b/166824318"),e=e.privateDoNotAccessOrElseSafeScriptWrappedValue||"",e=(f=Ab())?f.createScript(e):e,e=(new Fb(e)).toString());a.interpreterSafeUrl&&(d=a.interpreterSafeUrl,Db("From proto message. b/166824318"),d=Lb(d.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());Jv(this,e,
d,a.program,b,c)}else Lr(Error("Cannot initialize botguard without program"))};
function Jv(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,vv(c,function(){window[g]?Kv(a,d,g,e):(a.state=3,Av(c),Lr(new P("Unable to load Botguard","from "+c)))},f)):b?(f=of("SCRIPT"),f.textContent=b,f.nonce=ic(),document.head.appendChild(f),document.head.removeChild(f),window[g]?Kv(a,d,g,e):(a.state=4,Lr(new P("Unable to load Botguard from JS")))):Lr(new P("Unable to load VM; no url or JS provided"))}
function Kv(a,b,c,d){a.state=5;try{var e=new Fh({program:b,Vc:c,jd:M("att_web_record_metrics")});e.vd.then(function(){a.state=6;d&&d(b)});
a.Ib(e)}catch(f){a.state=7,f instanceof Error&&Lr(f)}}
l.invoke=function(a){a=void 0===a?{}:a;return this.Kb()?this.zc({Vb:a}):null};
l.dispose=function(){this.Mb()};
l.Mb=function(){this.Ib(null);this.state=8};
l.Kb=function(){return!!this.h};
l.zc=function(a){return this.h.uc(a)};
l.Ib=function(a){te(this.h);this.h=a};function Lv(){var a=B("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function Mv(){Gv.apply(this,arguments)}
u(Mv,Gv);Mv.prototype.Mb=function(){this.state=8};
Mv.prototype.Ib=function(a){var b;null==(b=Lv())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.uc.bind(a)},A("yt.abuse.playerAttLoader",b),A("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(A("yt.abuse.playerAttLoader",null),A("yt.abuse.playerAttLoaderRun",null))};
Mv.prototype.Kb=function(){return!!Lv()};
Mv.prototype.zc=function(a){return Lv().bgvmc(a)};var Nv=new Mv;function Ov(){return Nv.Kb()}
function Pv(a){a=void 0===a?{}:a;a=void 0===a?{}:a;return Nv.invoke(a)}
;function Qv(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Sl():d;this.l=c;this.j=d;this.i=new Eh;this.h=a;a={};c=p(this.h.entries());for(d=c.next();!d.done;a={Ga:a.Ga,Ra:a.Ra},d=c.next()){var e=p(d.value);d=e.next().value;e=e.next().value;a.Ra=d;a.Ga=e;d=function(f){return function(){f.Ga.Ab();b.h[f.Ra].lb=!0;b.h.every(function(g){return!0===g.lb})&&b.i.resolve()}}(a);
e=Ol(d,Rv(this,a.Ga));this.h[a.Ra]=Object.assign({},a.Ga,{Ab:d,jobId:e})}}
function Sv(a){var b=Array.from(a.h.keys()).sort(function(d,e){return Rv(a,a.h[e])-Rv(a,a.h[d])});
b=p(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.lb||(a.j.fa(c.jobId),Ol(c.Ab,10))}
Qv.prototype.cancel=function(){for(var a=p(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.lb||this.j.fa(b.jobId),b.lb=!0;this.i.resolve()};
function Rv(a,b){var c;return null!=(c=b.priority)?c:a.l}
;function Tv(a){this.state=a;this.plugins=[];this.o=void 0}
Tv.prototype.install=function(){this.plugins.push.apply(this.plugins,ia(Ja.apply(0,arguments)))};
Tv.prototype.uninstall=function(){var a=this;Ja.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
Tv.prototype.transition=function(a,b){var c=this,d=this.B.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.D===a}):f.from===c.state&&f.D===a});
if(d){this.j&&(Sv(this.j),this.j=void 0);this.state=a;d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Uv(this,e,this.o),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Uv(a,b,c){return function(){var d=Ja.apply(0,arguments),e=b.filter(function(k){var m;return 10===(null!=(m=null!=c?c:k.priority)?m:0)}),f=b.filter(function(k){var m;
return 10!==(null!=(m=null!=c?c:k.priority)?m:0)});
Sl();var g={};e=p(e);for(var h=e.next();!h.done;g={Sa:g.Sa},h=e.next())g.Sa=h.value,Ql(function(k){return function(){k.Sa.callback.apply(k.Sa,ia(d))}}(g));
f=f.map(function(k){var m;return{Ab:function(){k.callback.apply(k,ia(d))},
priority:null!=(m=null!=c?c:k.priority)?m:0}});
f.length&&(a.j=new Qv(f))}}
ea.Object.defineProperties(Tv.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Vv(a){Tv.call(this,void 0===a?"document_active":a);var b=this;this.o=10;this.h=new Map;this.B=[{from:"document_active",D:"document_disposed_preventable",action:this.M},{from:"document_active",D:"document_disposed",action:this.l},{from:"document_disposed_preventable",D:"document_disposed",action:this.l},{from:"document_disposed_preventable",D:"flush_logs",action:this.m},{from:"document_disposed_preventable",D:"document_active",action:this.i},{from:"document_disposed",D:"flush_logs",action:this.m},
{from:"document_disposed",D:"document_active",action:this.i},{from:"document_disposed",D:"document_disposed",action:function(){}},
{from:"flush_logs",D:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
u(Vv,Tv);Vv.prototype.M=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Vv.prototype.l=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Vv.prototype.m=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Vv.prototype.i=function(){this.h=new Map};function Wv(a){Tv.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.B=[{from:"document_visibility_unknown",D:"document_visible",action:this.i},{from:"document_visibility_unknown",D:"document_hidden",action:this.h},{from:"document_visibility_unknown",D:"document_foregrounded",action:this.m},{from:"document_visibility_unknown",D:"document_backgrounded",action:this.l},{from:"document_visible",D:"document_hidden",action:this.h},{from:"document_visible",D:"document_foregrounded",action:this.m},
{from:"document_visible",D:"document_visible",action:this.i},{from:"document_foregrounded",D:"document_visible",action:this.i},{from:"document_foregrounded",D:"document_hidden",action:this.h},{from:"document_foregrounded",D:"document_foregrounded",action:this.m},{from:"document_hidden",D:"document_visible",action:this.i},{from:"document_hidden",D:"document_backgrounded",action:this.l},{from:"document_hidden",D:"document_hidden",action:this.h},{from:"document_backgrounded",D:"document_hidden",action:this.h},
{from:"document_backgrounded",D:"document_backgrounded",action:this.l},{from:"document_backgrounded",D:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
M("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
u(Wv,Tv);Wv.prototype.i=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Wv.prototype.h=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Wv.prototype.l=function(a,b){a(null==b?void 0:b.event)};
Wv.prototype.m=function(a,b){a(null==b?void 0:b.event)};function Xv(){this.h=new Vv;this.i=new Wv}
Xv.prototype.install=function(){var a=Ja.apply(0,arguments);this.h.install.apply(this.h,ia(a));this.i.install.apply(this.i,ia(a))};function Yv(){Xv.call(this);var a={};this.install((a.document_disposed={callback:this.j},a));a={};this.install((a.flush_logs={callback:this.l},a))}
var Zv;u(Yv,Xv);Yv.prototype.l=function(){if(M("web_fp_via_jspb")){var a=new vj,b=cs();b&&D(a,1,b);b=new mk;be(b,vj,380,nk,a);kr(b);M("web_fp_via_jspb_and_json")&&fm("finalPayload",{csn:cs()})}else fm("finalPayload",{csn:cs()})};
Yv.prototype.j=function(){Pr(Qr)};function $v(){}
$v.getInstance=function(){var a=B("ytglobal.storage_");a||(a=new $v,A("ytglobal.storage_",a));return a};
$v.prototype.estimate=function(){var a,b,c;return x(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(aw()):d.return()})};
function aw(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
A("ytglobal.storageClass_",$v);function dm(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=Hk("ytidb_transaction_ended_event_rate_limit_session",.2)}
dm.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":M("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":M("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":bw(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=Hk("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function bw(a,b){$v.getInstance().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:cw(null==c?void 0:c.usage),deviceStorageQuotaMbytes:cw(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function cw(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function dw(a,b,c){J.call(this);var d=this;c=c||L("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.i="widget";this.I=!!a;this.F=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.I&&(d.sessionId&&d.sessionId!=f.id||d.i&&d.i!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.o&&(!d.s||0<=eb(d.s,f.func))&&d.o(f.func,f.args,e.origin)}}};
this.s=this.j=this.o=null;window.addEventListener("message",this.F)}
u(dw,J);dw.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.i&&(a.channel=this.i);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Ok(d)}}};
dw.prototype.C=function(){window.removeEventListener("message",this.F);J.prototype.C.call(this)};function ew(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new dw(!!L("WIDGET_ID_ENFORCE")),b=this.hd.bind(this);a.o=b;a.s=null;this.h.i="widget";if(a=L("WIDGET_ID"))this.h.sessionId=a}
l=ew.prototype;l.hd=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.j[a]||"onReady"===a||(this.addEventListener(a,fw(this,a)),this.j[a]=!0)):this.Nb(a,b,c)};
l.Nb=function(){};
function fw(a,b){return function(c){return a.sendMessage(b,c)}}
l.addEventListener=function(){};
l.Sc=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.wb());this.sendMessage("onReady");fb(this.i,this.sc,this);this.i=[]};
l.wb=function(){return null};
function gw(a,b){a.sendMessage("infoDelivery",b)}
l.sc=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
l.sendMessage=function(a,b){this.sc({event:a,info:void 0===b?null:b})};
l.dispose=function(){this.h=null};var hw={},iw=(hw["api.invalidparam"]=2,hw.auth=150,hw["drm.auth"]=150,hw["heartbeat.net"]=150,hw["heartbeat.servererror"]=150,hw["heartbeat.stop"]=150,hw["html5.unsupportedads"]=5,hw["fmt.noneavailable"]=5,hw["fmt.decode"]=5,hw["fmt.unplayable"]=5,hw["html5.missingapi"]=5,hw["html5.unsupportedlive"]=5,hw["drm.unavailable"]=5,hw["mrm.blocked"]=151,hw);var jw=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function kw(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function lw(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=p(jw);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function mw(a,b,c,d){if(Qa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function nw(a){ew.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.sd.bind(this));this.addEventListener("onVolumeChange",this.td.bind(this));this.addEventListener("onApiChange",this.nd.bind(this));this.addEventListener("onPlaybackQualityChange",this.pd.bind(this));this.addEventListener("onPlaybackRateChange",this.qd.bind(this));this.addEventListener("onStateChange",this.rd.bind(this));this.addEventListener("onWebglSettingsChanged",
this.ud.bind(this))}
u(nw,ew);l=nw.prototype;
l.Nb=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&kw(a)){var d=b;if(Qa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=lw(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=lw(e);break;case "loadPlaylist":case "cuePlaylist":e=mw(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);kw(a)&&gw(this,this.wb())}};
l.onReady=function(){var a=this.Sc.bind(this);this.h.j=a;a=this.api.getVideoData();if(!a.isPlayable){a=a.errorCode;var b=void 0===b?5:b;this.sendMessage("onError",(a?iw[a]||b:b).toString())}};
l.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
l.wb=function(){if(!this.api)return null;var a=this.api.getApiInterface();mb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
l.rd=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());gw(this,a)};
l.pd=function(a){gw(this,{playbackQuality:a})};
l.qd=function(a){gw(this,{playbackRate:a})};
l.nd=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],m=this.api.getOption(e,k);b[e][k]=m}}this.sendMessage("apiInfoDelivery",b)};
l.td=function(){gw(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
l.sd=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());gw(this,a)};
l.ud=function(){var a={sphericalProperties:this.api.getSphericalProperties()};gw(this,a)};
l.dispose=function(){ew.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function ow(a){J.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.mc,this)}
u(ow,J);l=ow.prototype;l.start=function(){this.started||this.h()||(this.started=!0,this.connection.za("RECEIVING"))};
l.za=function(a,b){this.started&&!this.h()&&this.connection.za(a,b)};
l.mc=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=pw(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=qw(a,c))&&this.za(a,c))}}};
l.addListener=function(a){if(!(a in this.i)){var b=this.od.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
l.od=function(a,b){this.started&&!this.h()&&this.connection.za(a,this.vb(a,b))};
l.vb=function(a,b){if(null!=b)return{value:b}};
l.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
l.C=function(){var a=this.connection;a.h()||wi(a.i,"command",this.mc,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);J.prototype.C.call(this)};function rw(a,b){ow.call(this,b);this.api=a;this.start()}
u(rw,ow);rw.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
rw.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function pw(a,b){switch(a){case "loadVideoById":return a=lw(b),[a];case "cueVideoById":return a=lw(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=mw(b),[a];case "cuePlaylist":return a=mw(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function qw(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
rw.prototype.vb=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return ow.prototype.vb.call(this,a,b)};
rw.prototype.C=function(){ow.prototype.C.call(this);delete this.api};function sw(a){a=void 0===a?!1:a;J.call(this);this.i=new K(a);ve(this,this.i)}
Za(sw,J);sw.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
sw.prototype.m=function(a,b){this.h()||this.i.ta.apply(this.i,arguments)};function tw(a,b,c){sw.call(this);this.l=a;this.j=b;this.id=c}
u(tw,sw);tw.prototype.za=function(a,b){this.h()||this.l.za(this.j,this.id,a,b)};
tw.prototype.C=function(){this.j=this.l=null;sw.prototype.C.call(this)};function uw(a,b,c){J.call(this);this.i=a;this.origin=c;this.j=Yp(window,"message",this.l.bind(this));this.connection=new tw(this,a,b);ve(this,this.connection)}
u(uw,J);uw.prototype.za=function(a,b,c,d){this.h()||a!==this.i||(a={id:b,command:c},d&&(a.data=d),this.i.postMessage(JSON.stringify(a),this.origin))};
uw.prototype.l=function(a){if(!this.h()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.h()||c.m("command",b.command,b.data,a.origin)}}}};
uw.prototype.C=function(){Zp(this.j);this.i=null;J.prototype.C.call(this)};function vw(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||vb(b);this.assets=a.assets||{};this.attrs=a.attrs||vb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
vw.prototype.clone=function(){var a=new vw,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Oa(c)?a[b]=vb(c):a[b]=c}return a};var ww=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function xw(a){a=a||"";if(window.spf){var b=a.match(ww);spf.style.load(a,b?b[1]:"",void 0)}else yw(a)}
function yw(a){var b=zw(a),c=document.getElementById(b),d=c&&rv(c,"loaded");d||c&&!d||(c=Aw(a,b,function(){rv(c,"loaded")||(pv(c),nq(b),gl(Ya(oq,b),0))}))}
function Aw(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Lb(a);gc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function zw(a){var b=of("A");Db("This URL is never added to the DOM");fc(b,new Ob(a,Pb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+kc(a)}
;function Bw(){J.call(this);this.i=[]}
u(Bw,J);Bw.prototype.C=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.callback,void 0)}J.prototype.C.call(this)};function Cw(){Bw.apply(this,arguments)}
u(Cw,Bw);function Dw(a,b,c,d,e){J.call(this);var f=this;this.s=b;this.webPlayerContextConfig=d;this.Wa=e;this.da=!1;this.api={};this.W=this.o=null;this.K=new K;this.i={};this.P=this.X=this.elementId=this.va=this.config=null;this.O=!1;this.l=this.F=null;this.ka={};this.Xa=["onReady"];this.lastError=null;this.Ia=NaN;this.I={};this.Ya=new Cw(this);this.S=0;this.j=this.m=a;ve(this,this.K);Ew(this);Fw(this);ve(this,this.Ya);c?this.S=gl(function(){f.loadNewVideoConfig(c)},0):d&&(Gw(this),Hw(this))}
u(Dw,J);l=Dw.prototype;l.getId=function(){return this.s};
l.loadNewVideoConfig=function(a){if(!this.h()){this.S&&(window.clearTimeout(this.S),this.S=0);var b=a||{};b instanceof vw||(b=new vw(b));this.config=b;this.setConfig(a);Hw(this);this.isReady()&&Iw(this)}};
function Gw(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.s,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.s:a.config.attrs.id=a.s);var c;(null==(c=a.j)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
l.setConfig=function(a){this.va=a;this.config=Jw(a);Gw(this);if(!this.X){var b;this.X=Kw(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.j&&(this.j.style.width=Th(Number(b)||b)),(a=a.height)&&this.j&&(this.j.style.height=Th(Number(a)||a))};
function Iw(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Lw(a){var b=!0,c=Mw(a);c&&a.config&&(a=Nw(a),b=rv(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function Hw(a){if(!a.h()&&!a.O){var b=Lw(a);if(b&&"html5"===(Mw(a)?"html5":null))a.P="html5",a.isReady()||Ow(a);else if(Pw(a),a.P="html5",b&&a.l&&a.m)a.m.appendChild(a.l),Ow(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.F=function(){c=!0;var d=Qw(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?Jw(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.Wa);Ow(a)};
a.O=!0;b?a.F():(vv(Nw(a),a.F),(b=Rw(a))&&xw(b),Sw(a)&&!c&&A("yt.player.Application.create",null))}}}
function Mw(a){var b=nf(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Ow(a){if(!a.h()){var b=Mw(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.O=!1;if(!Qw(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Tw(a)}else a.Ia=gl(function(){Ow(a)},50)}}
function Tw(a){Ew(a);a.da=!0;var b=Mw(a);if(b){a.o=Uw(a,b,"addEventListener");a.W=Uw(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Uw(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.o&&a.o(g,a.i[g]);Iw(a);a.X&&a.X(a.api);a.K.ta("onReady",a.api)}
function Uw(a,b,c){var d=b[c];return function(){var e=Ja.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Lr(f))}}}
function Ew(a){a.da=!1;if(a.W)for(var b in a.i)a.i.hasOwnProperty(b)&&a.W(b,a.i[b]);for(var c in a.I)a.I.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.I={};a.o=null;a.W=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.va};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
l.isReady=function(){return this.da};
function Fw(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){nq("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){nq("WATCH_LATER_VIDEO_REMOVED",b)})}
l.addEventListener=function(a,b){var c=this,d=Kw(this,b);d&&(0<=eb(this.Xa,a)||this.i[a]||(b=Vw(this,a),this.o&&this.o(a,b)),this.K.subscribe(a,d),"onReady"===a&&this.isReady()&&gl(function(){d(c.api)},0))};
l.removeEventListener=function(a,b){this.h()||(b=Kw(this,b))&&wi(this.K,a,b)};
function Kw(a,b){var c=b;if("string"===typeof b){if(a.ka[b])return a.ka[b];c=function(){var d=Ja.apply(0,arguments),e=B(b);if(e)try{e.apply(z,d)}catch(f){Kr(f)}};
a.ka[b]=c}return c?c:null}
function Vw(a,b){var c="ytPlayer"+b+a.s;a.i[b]=c;z[c]=function(d){var e=gl(function(){if(!a.h()){try{a.K.ta(b,null!=d?d:void 0)}catch(h){Lr(new P("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.s,data:d}))}var f=a.I,g=String(e);g in f&&delete f[g]}},0);
sb(a.I,String(e))};
return c}
l.getPlayerType=function(){return this.P||(Mw(this)?"html5":null)};
l.getLastError=function(){return this.lastError};
function Pw(a){a.cancel();Ew(a);a.P=null;a.config&&(a.config.loaded=!1);var b=Mw(a);b&&(Lw(a)||!Sw(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
l.cancel=function(){this.F&&Bv(Nw(this),this.F);window.clearTimeout(this.Ia);this.O=!1};
l.C=function(){Pw(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Kr(b)}this.ka=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(z[this.i[a]]=null);this.va=this.config=this.api=null;delete this.m;delete this.j;J.prototype.C.call(this)};
function Sw(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Nw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Rw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Qw(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Uk(c||"","&")[b]}
function Jw(a){for(var b={},c=p(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?vb(e):e}return b}
;var Ww={},Xw="player_uid_"+(1E9*Math.random()>>>0);function Yw(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?nf(c):c;var e=Xw+"_"+Ra(c),f=Ww[e];if(f&&d)return Zw(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Dw(c,e,a,b,void 0);Ww[e]=f;nq("player-added",f.api);we(f,function(){delete Ww[f.getId()]});
return f.api}
function Zw(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var $w=null,ax=null,bx=null;function cx(){dx()}
function ex(){dx()}
function dx(){var a=$w.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function fx(){$w&&$w.sendAbandonmentPing&&$w.sendAbandonmentPing();L("PL_ATT")&&Nv.dispose();for(var a=$h,b=0,c=Cv.length;b<c;b++)a.fa(Cv[b]);Cv.length=0;Av("//static.doubleclick.net/instream/ad_status.js");Dv=!1;Ek("DCLKSTAT",0);ue(bx,ax);$w&&($w.removeEventListener("onVideoDataChange",cx),$w.destroy())}
;function gx(a,b,c){a="ST-"+kc(a).toString(36);b=b?tc(b):"";c=c||5;ss()&&wl(a,b,c)}
;function hx(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=L("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=L("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=oc(window.location.href);g&&f.push(g);g=oc(d);if(0<=eb(f,g)||!g&&0==d.lastIndexOf("/",0))if(M("autoescape_tempdata_url")&&(f=document.createElement("a"),fc(f,d),d=f.href),d&&(d=pc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:cs()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
gx(d,b,h)}else gx(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var m=void 0===m?"":m;var q=void 0===q?window:q;c=q.location;a=vc(a,k)+m;var r=void 0===r?Sh:r;a:{r=void 0===r?Sh:r;for(k=0;k<r.length;++k)if(m=r[k],m instanceof Qh&&m.bd(a)){r=new Ob(a,Pb);break a}r=void 0}r=r||Sb;if(r instanceof Ob)var w=Qb(r);else{b:if(Ih){try{w=new URL(r)}catch(t){w="https:";break b}w=w.protocol}else c:{w=document.createElement("a");try{w.href=r}catch(t){w=void 0;break c}w=
w.protocol;w=":"===w||""===w?"https:":w}w="javascript:"!==w?r:void 0}void 0!==w&&(c.href=w)}return!0}
;A("yt.setConfig",Ek);A("yt.config.set",Ek);A("yt.setMsg",hs);A("yt.msgs.set",hs);A("yt.logging.errors.log",Kr);
A("writeEmbed",function(){var a=L("PLAYER_CONFIG");if(!a){var b=L("PLAYER_VARS");b&&(a={args:b})}Cs(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=L("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);du();c=L("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=Zk(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}$w=Yw(a,c);$w.addEventListener("onVideoDataChange",cx);$w.addEventListener("onReady",ex);a=L("POST_MESSAGE_ID","player");L("ENABLE_JS_API")?bx=new nw($w):L("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(ax=new uw(window.parent,a,b),bx=new rw($w,ax.connection));Ev();M("ytidb_create_logger_embed_killswitch")||M("embeds_web_disable_nwl")||cm();a={};Zv||(Zv=new Yv);Zv.install((a.flush_logs={callback:function(){Oq()}},
a));
M("embeds_web_disable_nwl")||Op();M("ytidb_clear_embedded_player")&&$h.U(function(){var e;if(!Mu){var f=Xs(),g={Fb:Lu,xc:Ku};f.h.set(g.Fb,g);g={Ub:{feedbackEndpoint:Ys(Gu),modifyChannelNotificationPreferenceEndpoint:Ys(Hu),playlistEditEndpoint:Ys(Iu),subscribeEndpoint:Ys(Eu),unsubscribeEndpoint:Ys(Fu),webPlayerShareEntityServiceEndpoint:Ys(Ju)}};var h=Ls.getInstance(),k={};h&&(k.client_location=h);if(void 0===m){Ds.h||(Ds.h=new Ds);var m=Ds.h}void 0===e&&(e=f.resolve(Lu));ru(g,e,m,k);m={Fb:xu,yc:qu.h};
f.h.set(m.Fb,m);Mu=f.resolve(xu)}ov()})});
var ix=Mk(function(a){if(!a.persisted){ku();a=Al.getInstance();var b=Dl(119),c=1<window.devicePixelRatio;if(document.body&&ji(document.body,"exp-invert-logo"))if(c&&!ji(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!ji(d,"inverted-hdpi")){var e=hi(d);ii(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&ji(document.body,"inverted-hdpi")&&ki();if(b!=c){b="f"+(Math.floor(119/31)+1);d=El(b)||0;d=c?d|67108864:d&-67108865;0==d?delete zl[b]:
(c=d.toString(16),zl[b]=c.toString());c=!0;M("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in zl)d.push(f+"="+encodeURIComponent(String(zl[f])));wl(b,d.join("&"),63072E3,a.i,c)}Yu.h||(Yu.h=new Yu);f=Yu.h;a=16623;var g=void 0===g?{}:g;Object.values(is).includes(a)||(Lr(new P("createClientScreen() called with a non-page VE",a)),a=83769);g.isHistoryNavigation||f.h.push({rootVe:a,key:g.key||""});f.o=[];f.M=[];g.Xb?av(f,a,g):bv(f,a,g)}}),jx=Mk(function(a){M("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?
fx():a.persisted||fx()}),kx=Mk(fx);
window.addEventListener?(window.addEventListener("load",ix),window.addEventListener("pageshow",ix),window.addEventListener("pagehide",jx)):window.attachEvent&&(window.attachEvent("onload",ix),window.attachEvent("onunload",kx));A("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||Ov);A("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||Pv);A("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||Fv);
A("yt.player.exports.navigate",B("yt.player.exports.navigate")||hx);A("yt.util.activity.init",B("yt.util.activity.init")||cq);A("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||fq);A("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||dq);}).call(this);
