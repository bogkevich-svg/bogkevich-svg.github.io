# Фото — галерея

Поклади сюди свої фотографії.

- Формат: jpg, jpeg, png або webp
- Рекомендований розмір: мінімум 800×800px
- Називай файли: portrait-1.jpg, portrait-2.jpg...

Потім у index.html в масиві `const works`:

```js
{ title: 'Назва фото', cat: 'Photo', large: false, img: 'images/photo/portrait-1.jpg', accent: '#3060e6' },
```

`large: true` — широка картка (2 колонки)
`large: false` — звичайна (1 колонка)
