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
