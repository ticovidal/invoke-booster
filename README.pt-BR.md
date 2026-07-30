[🇺🇸 English](README.md) | [🇧🇷 Português](README.pt-BR.md)

# 🚀 invoke-booster

Potencialize a API nativa de Invoker Commands do HTML5. Mantenha seu front-end limpo enquanto constrói ferramentas de interação preparadas para IA e GEO-first.

O **invoke-booster** é uma biblioteca Vanilla JS ultraleve, sem dependências, que estende a API nativa de Invoker do HTML5. Ele fornece um conjunto de comandos customizados prontos para o uso em interações diárias de UI, permitindo que você construa comportamentos complexos sem escrever uma única linha de JavaScript.

---

## 🛑 O Problema (JavaScript Espaguete)
Para fazer algo simples como copiar um texto ou rolar até um elemento, você geralmente precisa escrever JavaScript repetitivo, buscar elementos no DOM e gerenciar event listeners:

```javascript
// Você não precisa mais fazer isso!
const btn = document.getElementById('btn-copy');
const text = document.getElementById('promo-code');

btn.addEventListener('click', () => {
  navigator.clipboard.writeText(text.textContent);
});
```

##✅ A Solução (HTML-First)Com o invoke-booster, seu HTML se torna a única fonte da verdade. Basta usar os atributos nativos command e commandfor:  

```html
<p id="promo-code">PROMO2026</p>
<button commandfor="promo-code" command="--copy-text">Copiar Cupom</button>
```
##📦 Instalação
dicione o link do CDN na sua tag <head> e você está pronto para começar. Nenhuma ferramenta de build é necessária.

```HTML
<script defer src="[https://cdn.jsdelivr.net/npm/invoke-booster/dist/invoke-booster.min.js](https://cdn.jsdelivr.net/npm/invoke-booster/dist/invoke-booster.min.js)"></script>
```
(Pacote NPM em breve!)

##🛠️ Comandos Disponíveis (V1.0)
(A lista de comandos será documentada aqui em breve!)

##📄 Licença
Licença MIT © Thiago Vidal
