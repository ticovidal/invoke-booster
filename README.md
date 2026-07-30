[🇺🇸 English](README.md) | [🇧🇷 Português](README.pt-BR.md)
# 🚀 invoke-booster

Supercharge the HTML5 Invoker Commands API. Keep your front-end clean while building AI-ready, GEO-first interaction tools.

**invoke-booster** is a zero-dependency, ultra-lightweight Vanilla JS library that extends the native HTML5 Invoker API. It provides a set of ready-to-use custom commands for everyday UI interactions, allowing you to build complex behaviors without writing a single line of JavaScript.

---

## 🛑 The Problem (JavaScript Spaghetti)
To do something simple like copying text or scrolling to an element, you usually have to write boilerplate JavaScript, query the DOM, and manage event listeners:

```javascript
// You don't need to do this anymore!
const btn = document.getElementById('btn-copy');
const text = document.getElementById('promo-code');

btn.addEventListener('click', () => {
  navigator.clipboard.writeText(text.textContent);
});
```

## ✅ The Solution (HTML-First)
With invoke-booster, your HTML becomes the single source of truth. Just use the native command and commandfor attributes:

```html
<p id="promo-code">PROMO2026</p>
<button commandfor="promo-code" command="--copy-text">Copiar Cupom</button>
```
## 📦 Installation
Drop the CDN link into your <head> and you are ready to go. No build tools required.

```HTML
<script defer src="[https://cdn.jsdelivr.net/npm/invoke-booster/dist/invoke-booster.min.js](https://cdn.jsdelivr.net/npm/invoke-booster/dist/invoke-booster.min.js)"></script>
```
(NPM package coming soon!)

## 🛠️ Available Commands (V1.0)
(List of commands will be documented here soon!)

## 📄 License
MIT License © Thiago Vidal
