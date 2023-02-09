# Instagram Unfollowers

[![Maintenance](https://img.shields.io/maintenance/yes/2023)](https://github.com/davidarroyo1234/InstagramUnfollowers)

A nifty tool that lets you see who doesn't follow you back on Instagram.  
<u>Browser-based and requires no downloads or installations!</u>

## **WARNING**

This version utilizes the Instagram API for better performance.  
If you prefer to use the older version please use this [commit](https://github.com/davidarroyo1234/InstagramUnfollowers/tree/50a0bcbc9fe349b8664a74c0e4477bc974d0352b).

## Usage

### Steps:

1.  Copy the following code

```js
"use strict";
(() => 
    {
        "use strict";
        var e = 
        { 
            99: (e, n, t) => 
            { 
                t.d(n, { Z: () => s }); 
                var r = t(81), o = t.n(r), a = t(645), i = t.n(a)()(o()); 
                i.push([e.id, "html{background-color:#222 !important}html .iu{margin-bottom:10rem;font-family:system-ui}html .iu .overlay{background-color:#222;color:#fff;height:100%}html .iu header.top-bar{position:fixed;top:0;left:0;right:0;display:flex;align-items:center;justify-content:space-between;padding:1rem;height:2.5rem;background-color:#333;z-index:1}html .iu header .logo{font-family:monospace;font-size:1.5em;cursor:pointer}html .iu footer.bottom-bar{position:fixed;bottom:0;left:0;right:0;display:flex;align-items:center;justify-content:space-between;padding:1rem;background-color:#000;font-weight:bold;z-index:1}html .iu label{cursor:pointer}html .iu input[type=checkbox]{height:1.1rem;width:1.1rem}html .iu a{color:inherit;text-decoration-color:rgba(0,0,0,0);transition:text-decoration-color .1s;cursor:pointer}html .iu a:hover{text-decoration-color:inherit}html .iu button{background:none;border:none;padding:0;cursor:pointer}html .iu button.copy-list{color:#fff;font-size:1rem}html .iu button.run-scan{position:absolute;left:50%;top:50%;transform:translate(-50%, -50%);font-size:2em;color:#fff;border:1px solid #fff;height:160px;width:160px;border-radius:50%}html .iu .progressbar-container{width:175px;height:30px;border-radius:5px;position:relative;border:1px solid #7b7777}html .iu .progressbar-bar{width:0;height:100%;background-color:#7b7777}html .iu .progressbar-text{position:absolute;top:50%;left:50%;transform:translate(-50%, -50%)}html .iu .results-container{transform:translateY(75px)}html .iu .results-container .alphabet-character{margin:1rem;padding:1rem;font-size:2em;border-bottom:1px solid #333}html .iu .results-container .result-item{display:flex;align-items:center;padding:1rem;border-radius:3px;cursor:pointer}html .iu .results-container .result-item .avatar{width:75px;border-radius:50%}html .iu .results-container .result-item .verified-badge{background-color:#49adf4;border-radius:50%;padding:.2rem .3rem;font-size:.45em;height:fit-content;transform:translateY(-15px)}html .iu .results-container .result-item .private-indicator{border:2px solid #51bb42;border-radius:25px;padding:.5rem;color:#51bb42;font-weight:500}html .toast{position:fixed;bottom:5rem;color:#000;background-color:#fff;border-radius:6px;font-size:1.25em;padding:2rem;transition:transform .2s;z-index:2}html .toast-hidden{transform:translateX(-999rem)}.flex{display:flex}.flex.align-center{align-items:center}.flex.justify-center{justify-content:center}.flex.column{flex-direction:column}.grow{flex:1}.w-100{width:100%}.p-small{padding:.5rem}.p-medium{padding:1rem}.p-large{padding:1.5rem}.p-xlarge{padding:2rem}.fs-small{font-size:.5rem}.fs-medium{font-size:1rem}.fs-large{font-size:1.5rem}.fs-xlarge{font-size:2rem}.clr-inherit{color:inherit}.clr-red{color:#bd2121}.clr-green{color:#56d756}.clr-cyan{color:aqua}.d-none{display:none}", ""]); 
                const s = i; }, 645: e => { e.exports = function (e) { var n = []; return n.toString = function () { return this.map((function (n) { var t = "", r = void 0 !== n[5]; return n[4] && (t += "@supports (".concat(n[4], ") {")), n[2] && (t += "@media ".concat(n[2], " {")), r && (t += "@layer".concat(n[5].length > 0 ? " ".concat(n[5]) : "", " {")), t += e(n), r && (t += "}"), n[2] && (t += "}"), n[4] && (t += "}"), t; })).join(""); }, n.i = function (e, t, r, o, a) { "string" == typeof e && (e = [[null, e, void 0]]); var i = {}; if (r)
                for (var s = 0; s < this.length; s++) 
                {
                    var c = this[s][0];
                    null != c && (i[c] = !0);
                } 
                for (var l = 0; l < e.length; l++) 
                {
                    var u = [].concat(e[l]);
                    r && i[u[0]] || (void 0 !== a && (void 0 === u[5] || (u[1] = "@layer".concat(u[5].length > 0 ? " ".concat(u[5]) : "", " {").concat(u[1], "}")), u[5] = a), t && (u[2] ? (u[1] = "@media ".concat(u[2], " {").concat(u[1], "}"), u[2] = t) : u[2] = t), o && (u[4] ? (u[1] = "@supports (".concat(u[4], ") {").concat(u[1], "}"), u[4] = o) : u[4] = "".concat(o)), n.push(u));
                } 
            }, n; 
        }; 
    }
    , 81: e => { e.exports = function (e) { return e[1]; }; }, 273: (e, n, t) => { t.r(n), t.d(n, { default: () => g }); var r = t(379), o = t.n(r), a = t(795), i = t.n(a), s = t(569), c = t.n(s), l = t(565), u = t.n(l), d = t(216), f = t.n(d), p = t(589), h = t.n(p), m = t(99), b = {}; b.styleTagTransform = h(), b.setAttributes = u(), b.insert = c().bind(null, "head"), b.domAPI = i(), b.insertStyleElement = f(), o()(m.Z, b); const g = m.Z && m.Z.locals ? m.Z.locals : void 0; }, 379: e => { var n = []; function t(e) { for (var t = -1, r = 0; r < n.length; r++)
            if (n[r].identifier === e) {
                t = r;
                break;
            } return t; } function r(e, r) { for (var a = {}, i = [], s = 0; s < e.length; s++) {
            var c = e[s], l = r.base ? c[0] + r.base : c[0], u = a[l] || 0, d = "".concat(l, " ").concat(u);
            a[l] = u + 1;
            var f = t(d), p = { css: c[1], media: c[2], sourceMap: c[3], supports: c[4], layer: c[5] };
            if (-1 !== f)
                n[f].references++, n[f].updater(p);
            else {
                var h = o(p, r);
                r.byIndex = s, n.splice(s, 0, { identifier: d, updater: h, references: 1 });
            }
            i.push(d);
        } return i; } function o(e, n) { var t = n.domAPI(n); return t.update(e), function (n) { if (n) {
            if (n.css === e.css && n.media === e.media && n.sourceMap === e.sourceMap && n.supports === e.supports && n.layer === e.layer)
                return;
            t.update(e = n);
        }
        else
            t.remove(); }; } e.exports = function (e, o) { var a = r(e = e || [], o = o || {}); return function (e) { e = e || []; for (var i = 0; i < a.length; i++) {
            var s = t(a[i]);
            n[s].references--;
        } for (var c = r(e, o), l = 0; l < a.length; l++) {
            var u = t(a[l]);
            0 === n[u].references && (n[u].updater(), n.splice(u, 1));
        } a = c; }; }; }, 569: e => { var n = {}; e.exports = function (e, t) { var r = function (e) { if (void 0 === n[e]) {
            var t = document.querySelector(e);
            if (window.HTMLIFrameElement && t instanceof window.HTMLIFrameElement)
                try {
                    t = t.contentDocument.head;
                }
                catch (e) {
                    t = null;
                }
            n[e] = t;
        } return n[e]; }(e); if (!r)
            throw new Error("Couldn't find a style target. This probably means that the value for the 'insert' parameter is invalid."); r.appendChild(t); }; }, 216: e => { e.exports = function (e) { var n = document.createElement("style"); return e.setAttributes(n, e.attributes), e.insert(n, e.options), n; }; }, 565: (e, n, t) => { e.exports = function (e) { var n = t.nc; n && e.setAttribute("nonce", n); }; }, 795: e => { e.exports = function (e) { var n = e.insertStyleElement(e); return { update: function (t) { !function (e, n, t) { var r = ""; t.supports && (r += "@supports (".concat(t.supports, ") {")), t.media && (r += "@media ".concat(t.media, " {")); var o = void 0 !== t.layer; o && (r += "@layer".concat(t.layer.length > 0 ? " ".concat(t.layer) : "", " {")), r += t.css, o && (r += "}"), t.media && (r += "}"), t.supports && (r += "}"); var a = t.sourceMap; a && "undefined" != typeof btoa && (r += "\n/*# sourceMappingURL=data:application/json;base64,".concat(btoa(unescape(encodeURIComponent(JSON.stringify(a)))), " */")), n.styleTagTransform(r, e, n.options); }(n, e, t); }, remove: function () { !function (e) { if (null === e.parentNode)
                return !1; e.parentNode.removeChild(e); }(n); } }; }; }, 589: e => { e.exports = function (e, n) { if (n.styleSheet)
            n.styleSheet.cssText = e;
        else {
            for (; n.firstChild;)
                n.removeChild(n.firstChild);
            n.appendChild(document.createTextNode(e));
        } }; }, 519: function (e, n, t) { var r = this && this.__awaiter || function (e, n, t, r) { return new (t || (t = Promise))((function (o, a) { function i(e) { try {
            c(r.next(e));
        }
        catch (e) {
            a(e);
        } } function s(e) { try {
            c(r.throw(e));
        }
        catch (e) {
            a(e);
        } } function c(e) { var n; e.done ? o(e.value) : (n = e.value, n instanceof t ? n : new t((function (e) { e(n); }))).then(i, s); } c((r = r.apply(e, n || [])).next()); })); }, o = this && this.__generator || function (e, n) { var t, r, o, a, i = { label: 0, sent: function () { if (1 & o[0])
                throw o[1]; return o[1]; }, trys: [], ops: [] }; return a = { next: s(0), throw: s(1), return: s(2) }, "function" == typeof Symbol && (a[Symbol.iterator] = function () { return this; }), a; function s(s) { return function (c) { return function (s) { if (t)
            throw new TypeError("Generator is already executing."); for (; a && (a = 0, s[0] && (i = 0)), i;)
            try {
                if (t = 1, r && (o = 2 & s[0] ? r.return : s[0] ? r.throw || ((o = r.return) && o.call(r), 0) : r.next) && !(o = o.call(r, s[1])).done)
                    return o;
                switch (r = 0, o && (s = [2 & s[0], o.value]), s[0]) {
                    case 0:
                    case 1:
                        o = s;
                        break;
                    case 4: return i.label++, { value: s[1], done: !1 };
                    case 5:
                        i.label++, r = s[1], s = [0];
                        continue;
                    case 7:
                        s = i.ops.pop(), i.trys.pop();
                        continue;
                    default:
                        if (!((o = (o = i.trys).length > 0 && o[o.length - 1]) || 6 !== s[0] && 2 !== s[0])) {
                            i = 0;
                            continue;
                        }
                        if (3 === s[0] && (!o || s[1] > o[0] && s[1] < o[3])) {
                            i.label = s[1];
                            break;
                        }
                        if (6 === s[0] && i.label < o[1]) {
                            i.label = o[1], o = s;
                            break;
                        }
                        if (o && i.label < o[2]) {
                            i.label = o[2], i.ops.push(s);
                            break;
                        }
                        o[2] && i.ops.pop(), i.trys.pop();
                        continue;
                }
                s = n.call(e, i);
            }
            catch (e) {
                s = [6, e], r = 0;
            }
            finally {
                t = o = 0;
            } if (5 & s[0])
            throw s[1]; return { value: s[0] ? s[1] : void 0, done: !0 }; }([s, c]); }; } }, a = this && this.__spreadArray || function (e, n, t) { if (t || 2 === arguments.length)
            for (var r, o = 0, a = n.length; o < a; o++)
                !r && o in n || (r || (r = Array.prototype.slice.call(n, 0, o)), r[o] = n[o]); return e.concat(r || Array.prototype.slice.call(n)); }; Object.defineProperty(n, "__esModule", { value: !0 }), t(273); var i, s = [], c = [], l = !1, u = 1; function d(e) { return new Promise((function (n) { setTimeout(n, e); })); } function f(e) { var n = "; ".concat(document.cookie).split("; ".concat(e, "=")); if (2 === n.length)
            return n.pop().split(";").shift(); } function p(e) { var n = document.querySelector(e); if (null === n)
            throw new Error("Unable to find element by class: ".concat(e)); return n; } function h(e) { return r(this, void 0, void 0, (function () { return o(this, (function (n) { switch (n.label) {
            case 0: return [4, navigator.clipboard.writeText(e)];
            case 1: return n.sent(), alert("List copied to clipboard!"), [2];
        } })); })); } function m() { p(".selected-user-count").innerHTML = "[".concat(c.length, "]"); } function b() { document.getElementById("current-page").innerHTML = String(u), document.getElementById("last-page").innerHTML = String(v()), p(".toggle-all-checkbox").disabled = !1; var e = p(".results-container"); e.innerHTML = ""; var n = ""; a([], s, !0).sort((function (e, n) { return e.username > n.username ? 1 : -1; })).splice(50 * (u - 1), 50).forEach((function (t) { var r = -1 !== c.indexOf(parseInt(t.id, 10)), o = t.username.substring(0, 1).toUpperCase(); n !== o && (n = o, e.innerHTML += '<div class="alphabet-character">'.concat(n, "</div>")), e.innerHTML += '<label class="result-item">\n            <div class="flex grow align-center">\n                <img class="avatar" alt="" src="'.concat(t.profile_pic_url, '" />&nbsp;&nbsp;&nbsp;&nbsp;\n                <div class="flex column">\n                    <a class="fs-xlarge" target="_blank" href="../').concat(t.username, '">').concat(t.username, '</a>\n                    <span class="fs-medium">').concat(t.full_name, "</span>\n                </div>\n                ").concat(t.is_verified ? '&nbsp;&nbsp;&nbsp;<div class="verified-badge">✔</div>' : "", "\n                ").concat(t.is_private ? '<div class="flex justify-center w-100">\n                            <span class="private-indicator">Private</span>\n                          </div>' : "", '\n            </div>\n            <input\n                class="account-checkbox"\n                type="checkbox"\n                onchange="toggleUser(').concat(t.id, ')"\n                ').concat(r ? "checked" : "", " />\n        </label>"); })); } function g(e) { return void 0 === e && (e = !0), r(this, void 0, void 0, (function () { var n, t, r, a, i, c, u, h, m, g, v, y, w, x; return o(this, (function (o) { switch (o.label) {
            case 0:
                if (l)
                    return [2];
                n = [], t = !0, r = 0, a = 0, i = -1, l = !0, c = f("ds_user_id"), u = 'https://www.instagram.com/graphql/query/?query_hash=3dec7e2c57367ef3da3d987d89f9dbc8&variables={"id":"'.concat(c, '","include_reel":"true","fetch_mutual":"false","first":"24"}'), h = p(".progressbar-bar"), m = p(".progressbar-text"), g = p(".nonfollower-count"), v = p(".toast"), o.label = 1;
            case 1:
                if (!t)
                    return [3, 9];
                y = void 0, o.label = 2;
            case 2: return o.trys.push([2, 4, , 5]), [4, fetch(u).then((function (e) { return e.json(); }))];
            case 3: return y = o.sent().data.user.edge_follow, [3, 5];
            case 4: return w = o.sent(), console.error(w), [3, 1];
            case 5: return -1 === i && (i = y.count), t = y.page_info.has_next_page, u = function (e) { var n = f("ds_user_id"); return 'https://www.instagram.com/graphql/query/?query_hash=3dec7e2c57367ef3da3d987d89f9dbc8&variables={"id":"'.concat(n, '","include_reel":"true","fetch_mutual":"false","first":"24","after":"').concat(e, '"}'); }(y.page_info.end_cursor), a += y.edges.length, y.edges.forEach((function (t) { !e && t.node.is_verified || t.node.follows_viewer || n.push(t.node); })), x = "".concat(Math.ceil(a / i * 100), "%"), m.innerHTML = x, h.style.width = x, g.innerHTML = n.length.toString(), s = n, b(), [4, d(Math.floor(400 * Math.random()) + 1e3)];
            case 6: return o.sent(), ++r > 6 ? (r = 0, v.classList.remove("toast-hidden"), v.innerHTML = "Sleeping 10 secs to prevent getting temp blocked...", [4, d(1e4)]) : [3, 8];
            case 7: o.sent(), o.label = 8;
            case 8: return v.classList.add("toast-hidden"), [3, 1];
            case 9: return h.style.backgroundColor = "#59A942", m.innerHTML = "DONE", l = !1, [2];
        } })); })); } function v() { var e = Math.ceil(s.length / 50); return e < 1 ? 1 : e; } window.addEventListener("beforeunload", (function (e) { if (l)
            return (e = e || window.event) && (e.returnValue = "Changes you made may not be saved."), "Changes you made may not be saved."; })), t.g.copyListToClipboard = function () { return r(this, void 0, void 0, (function () { var e, n; return o(this, (function (t) { switch (t.label) {
            case 0: return e = a([], s, !0).sort((function (e, n) { return e.username > n.username ? 1 : -1; })), n = "", e.forEach((function (e) { n += e.username + "\n"; })), [4, h(n)];
            case 1: return t.sent(), [2];
        } })); })); }, t.g.toggleUser = function (e) { c = -1 === c.indexOf(e) ? a(a([], c, !0), [e], !1) : c.filter((function (n) { return n !== e; })), m(); }, t.g.toggleAllUsers = function (e) { document.querySelectorAll(".account-checkbox").forEach((function (n) { return n.checked = e; })), c = e ? s.map((function (e) { return parseInt(e.id, 10); })) : [], m(); }, t.g.unfollow = function () { return r(this, void 0, void 0, (function () { var e, n, t, r, a, i, u, h, m, b, g, v, y; return o(this, (function (o) { switch (o.label) {
            case 0:
                if (l)
                    return [2];
                if (0 === c.length)
                    return alert("Must select at least a single user to unfollow"), [2];
                if (!confirm("Are you sure?"))
                    return [2];
                if (void 0 === (e = f("csrftoken")))
                    throw new Error("csrftoken cookie is undefined");
                n = p(".toast"), t = p(".progressbar-bar"), r = p(".progressbar-text"), p(".toggle-all-checkbox").disabled = !0, (a = p(".results-container")).innerHTML = "", i = function () { return window.scrollTo(0, a.scrollHeight); }, r.innerHTML = "0%", t.style.width = "0%", l = !0, u = 0, h = 0, m = c, o.label = 1;
            case 1:
                if (!(h < m.length))
                    return [3, 10];
                b = m[h], g = function (e) { var n = s.find((function (n) { return n.id.toString() === e.toString(); })); return void 0 === n && console.error("Unable to find user by id: ".concat(e)), n; }(b), o.label = 2;
            case 2: return o.trys.push([2, 4, , 5]), [4, fetch((w = b, "https://www.instagram.com/web/friendships/".concat(w, "/unfollow/")), { headers: { "content-type": "application/x-www-form-urlencoded", "x-csrftoken": e }, method: "POST", mode: "cors", credentials: "include" })];
            case 3: return o.sent(), a.innerHTML += '<div class="p-medium">Unfollowed\n                <a class="clr-inherit" target="_blank" href="../'.concat(g.username, '"> ').concat(g.username, '</a>\n                <span class="clr-cyan"> [').concat(u + 1, "/").concat(c.length, "]</span>\n            </div>"), [3, 5];
            case 4: return v = o.sent(), console.error(v), a.innerHTML += '<div class="p-medium clr-red">Failed to unfollow '.concat(g.username, " [").concat(u + 1, "/").concat(c.length, "]</div>"), [3, 5];
            case 5: return u += 1, y = "".concat(Math.ceil(u / c.length * 100), "%"), r.innerHTML = y, t.style.width = y, i(), b === c[c.length - 1] ? [3, 10] : [4, d(Math.floor(2e3 * Math.random()) + 4e3)];
            case 6: return o.sent(), u % 5 != 0 ? [3, 8] : (n.classList.remove("toast-hidden"), n.innerHTML = "Sleeping 5 minutes to prevent getting temp blocked...", i(), [4, d(3e5)]);
            case 7: o.sent(), o.label = 8;
            case 8: n.classList.add("toast-hidden"), o.label = 9;
            case 9: return h++, [3, 1];
            case 10: return t.style.backgroundColor = "#59A942", r.innerHTML = "DONE", l = !1, a.innerHTML += '<hr /><div class="fs-large p-medium clr-green">All DONE!</div><hr />', i(), [2];
        } var w; })); })); }, t.g.nextPage = function () { u < v() && (u++, b()); }, t.g.previousPage = function () { u - 1 > 0 && (u--, b()); }, "www.instagram.com" === location.hostname ? 
        (document.title = "MorumaOsQuiere", i = !0, document.body.innerHTML = 
        '\n    <main class="iu">\n   <div class="overlay">\n    <header class="top-bar">\n                    <div class="logo" onclick="location.reload()">UnfollowersIG</div>\n                    <label class="flex align-center">\n                        <input type="checkbox" class="include-verified-checkbox" '.concat(i ? "checked" : "", ' /> Include verified\n                    </label>\n                    <button class="copy-list" onclick="copyListToClipboard()" disabled>COPY LIST</button>\n                    <button class="fs-large clr-red" onclick="unfollow()">UNFOLLOW <span class="selected-user-count">[0]</span></button>\n                    <input type="checkbox" class="toggle-all-checkbox" onclick="toggleAllUsers(this.checked)" disabled />\n                </header>\n\n                <button class="run-scan">RUN</button>\n                <div class="results-container"></div>\n\n                <footer class="bottom-bar">\n                    <div>Non-followers: <span class="nonfollower-count" /></div>\n                    <div>\n                        <a onclick="previousPage()" class="p-medium">❮</a>\n                        <span id="current-page">1</span>&nbsp;/&nbsp;<span id="last-page">1</span>\n                        <a onclick="nextPage()" class="p-medium">❯</a>\n                    </div>\n                    <div class="progressbar-container">\n                        <div class="progressbar-bar"></div>\n                        <span class="progressbar-text">0%</span>\n                    </div>\n                </footer>\n            </div>\n            <div class="toast toast-hidden"></div>\n        </main>'), p(".run-scan").addEventListener("click", (function () { return function (e) { return r(this, void 0, void 0, (function () { return o(this, (function (n) { switch (n.label) {
            case 0: return p(".run-scan").remove(), p(".include-verified-checkbox").disabled = !0, [4, g(e)];
            case 1: return n.sent(), p(".copy-list").disabled = !1, [2];
        } })); })); }(i); })), p(".include-verified-checkbox").addEventListener("change", (function () { return i = !i; }))) : alert("Can be used only on Instagram routes"); } }, n = {};
    function t(r) { var o = n[r]; if (void 0 !== o)
        return o.exports; var a = n[r] = { id: r, exports: {} }; return e[r].call(a.exports, a, a.exports, t), a.exports; }
    t.n = e => { var n = e && e.__esModule ? () => e.default : () => e; return t.d(n, { a: n }), n; }, t.d = (e, n) => { for (var r in n)
        t.o(n, r) && !t.o(e, r) && Object.defineProperty(e, r, { enumerable: !0, get: n[r] }); }, t.g = function () { if ("object" == typeof globalThis)
        return globalThis; try {
        return this || new Function("return this")();
    }
    catch (e) {
        if ("object" == typeof window)
            return window;
    } }(), t.o = (e, n) => Object.prototype.hasOwnProperty.call(e, n), t.r = e => { "undefined" != typeof Symbol && Symbol.toStringTag && Object.defineProperty(e, Symbol.toStringTag, { value: "Module" }), Object.defineProperty(e, "__esModule", { value: !0 }); }, t.nc = void 0, t(519);
})();

```
2. Log in into your account and open the developer console or (Ctrl+Shift+J(Windows) || ⌘+⌥+I (Mac os)) and paste the code.

3.  You will be met with the following interface:

    <img src="./assets/main.png" alt="main" width="1613" />

4.  Click "RUN" to start scanning for users who do not follow you back.
5.  Once it finishes printing the users, you will be met with the following screen which will show you the results:

    <img src="./assets/results.png" alt="main" width="1265" />

6.  If you wish to un-follow any of these users, you can select 1 or more of them via the checkbox next to each user.

## Notes

**_The more users you have to check, more time it will take_**

**_This script has been tested only on Chromium-based browsers_**

## DEV

When introducing new changes to `main.js`, make sure to run the "build" command in-order to automatically format, compress, and convert your code.

## Legal

**Disclaimer:** This is not affiliated, associated, authorized, endorsed by, or in any way officially connected with Instagram.

Use it at your own risk!.
