# Serhii Bozhkevich — AI Creator Portfolio

## Структура файлів

```
📁 репозиторій/
├── index.html              ← головний файл сайту
└── images/
    ├── hero/
    │   └── hero.jpg        ← твоє титульне фото
    ├── video/
    │   ├── work-1.jpg      ← прев'ю відео
    │   └── work-2.jpg
    ├── photo/
    │   ├── portrait-1.jpg
    │   └── portrait-2.jpg
    ├── logo/
    │   ├── logo-1.jpg
    │   └── logo-2.jpg
    └── animation/
        ├── anim-1.gif
        └── anim-2.jpg
```

## Як додати нову роботу

1. Завантаж фото в потрібну папку (`images/video/`, `images/photo/` тощо)
2. Відкрий `index.html` → знайди масив `const works = [`
3. Додай новий рядок:

```js
{
  title: 'Назва роботи',
  cat: 'Video',          // Video | Photo | Logo | Animation
  large: false,          // true = широка картка
  img: 'images/video/my-file.jpg',
  accent: '#e63030'      // колір акценту
},
```

4. Збережи і запуш на GitHub — готово!

## Як запустити на GitHub Pages

1. Створи репозиторій (наприклад `username.github.io`)
2. Завантаж всі файли з цієї папки в корінь репозиторію
3. `Settings → Pages → Source: Deploy from branch → main / root`
4. Сайт буде на `https://username.github.io`
