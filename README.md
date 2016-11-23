# Badge stickers

1. Install with `npm i`
2. Add data into `index.html`
2. Run the builder with `node .`
3. Print out the resultant `index.pdf`

Change dimentions with `@page` (by default it's A3 either portrait or landscape).

```css
@page {
	margin: 4.5mm 0 0 15mm;
	size: 420mm 297mm;
	}
```

First list provides lines for cutting with plotter.
