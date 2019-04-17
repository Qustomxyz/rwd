## Заметки к первой главе
***
### наброски кода

Этот код ужмет большую картинку до ширины мелкого экрана

```css
img {
    max-width: 100%;
}
```

Если экран большой, то уже не надо, чтобы картинка растягивалась
по ширине. Ставим порог, с которого растягиваться не будет:

```css
@media screen and (min-width: 50em){
    /* здесь будут стили на этот случай */

}
```

### ссылки

- [Глобальная сатистика по браузерам и т.д.](http://gs.statcounter.com/)
- [Ethan Marcotte про адаптивный дизайн](https://alistapart.com/article/responsive-web-design/)
- [Проверка совместимости фич и браузеров](https://caniuse.com/)
- [Полная спецификация медиазапросов](https://www.w3.org/TR/css3-mediaqueries/)
- [Media Queries Level 4](https://drafts.csswg.org/mediaqueries-4/)