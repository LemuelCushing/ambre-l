# PDF to HTML (`catalogue/catalogue.html`)

As simple as `pdftohtml -c -s -noframes catalogue.pdf catalogue/catalogue.html` (`brew install poppler` if needed)

Make sure to:
* Change the BG color on the original to #f0f0f0
* update the generated HTML to use the same BG color
* add css:
```css
		body {
			margin: 20%;
			padding: 0;
			background-color: #ffffff;
		}
  ```
