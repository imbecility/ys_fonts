## yt_fonts

```html
<!DOCTYPE html>
<html>
<head>
  <!-- подключение шрифтов -->
  <link rel="preconnect" href="https://yastatic.net">
  <link rel="preconnect" href="https://cdn.jsdelivr.net">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/imbecility/ys_fonts@main/ys_fonts.css">
  
  <!-- стили -->
  <style>
    :root { font-family: 'YS Text', sans-serif; }
    h1, h2, h3, h4, h5, h6 { font-family: 'YS Display', sans-serif; }
  </style>
</head>
<body>
  <!-- контент -->
</body>
</html>
```

---

```css
@import url('https://cdn.jsdelivr.net/gh/imbecility/ys_fonts@refs/heads/main/ys_fonts.css');

h1, h2, h3, h4, h5, h6 {
    font-family: 'YS Display', sans-serif;
}
p {
    font-family: 'YS Text', sans-serif;
}
```