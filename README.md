# hooli-style-popup
Popup with HTML and CSS

## Table of contents

  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: [hooli-style-popup](https://github.com/Lara-trost/hooli-style-popup)
- Live Site URL: [hooli-style-popup](https://lara-trost.github.io/hooli-style-popup/)

## My process

### Built with

- HTML5 
- CSS 
- Flexbox

### What I learned

 - Створити чекбокс:
```html
<input type="checkbox" id="checkbox_toggle" name="checkbox_toggle" class="check_input" tabindex="0">
<label for="checkbox_toggle" class="check" >
  <img src="./icons/popup-button.png" alt="start-menu">
</label>
```
 - Зробити інтерактивний елемент доступним для клавіатури
 ```html
 tabindex="0"
 ```

 - Приховати чекбокс
```css
input[type=checkbox]{
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
}
```
- Приховати вміст
```css
    opacity: 0;
    visibility: hidden;
```
- Показати вміст 
```css
.check_input:checked ~ .popup {
    opacity: 1;
    visibility: visible;
}
```

### Useful resources

- [відео](https://www.youtube.com/watch?v=E6kLaaQFctU&ab_channel=VadimMakeev) - приховування чекбоксу
- [Quick Tip: CSS Only Dropdowns With The Checkbox Hack](https://tutorialzine.com/2015/08/quick-tip-css-only-dropdowns-with-the-checkbox-hack) - popup and checkbox

## Author

- Github - [Larysa Trostinetska](https://github.com/Lara-trost)

## Acknowledgments

Дякую за допомогу в пошуку ресурсів Andrii Shchur.
