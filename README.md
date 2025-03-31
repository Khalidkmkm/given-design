# 🌿 Given Design – HTML & CSS-projekt

Detta projekt är att återskapa en specifik design så exakt som möjligt, enbart med hjälp av **HTML** och **CSS** – inga ramverk eller JavaScript.

## 🚀 Funktioner

- Responsiv layout för olika skärmstorlekar
- Navigeringsmeny med hamburgarikon för mobil
- Scroll-länkar mellan sektionerna
- Strukturerad och semantisk HTML

## 🔧 Tekniker

- HTML5
- CSS3
- Flexbox
- Media Queries
- Font Awesome (ikoner)

## 💻 Kodexempel

Här är ett exempel på hur den responsiva navigationsmenyn är uppbyggd:

```html
<nav class="navbar">
  <input type="checkbox" id="menu-toggle" hidden>
  <label for="menu-toggle" class="menu-icon">
      <span></span>
      <span></span>
      <span></span>
  </label>
  <ul class="nav-list">
    <li><a href="#home" class="active">Hem</a></li>
    <li><a href="#about">Om</a></li>
    <li><a href="#contact">Kontakt</a></li>
  </ul>
</nav>

