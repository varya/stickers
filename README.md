# Наклейки для бейджей

1. Установите зависимости `npm i`
2. Добавьте данные в `index.html`
2. Запустите сборку `node .`
3. Распечайте получившийся `index.pdf`

Размеры меняются в директиве `@page`, по умолчанию A3 в альбомной ориентации.

```css
@page {
	margin: 4.5mm 0 0 15mm;
	size: 420mm 297mm;
	}
```

Первый лист с направляющими нужен для плоттерной резки.
