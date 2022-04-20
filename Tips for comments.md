# Commenting on GitHub

## When a commentary gets too big:

### Create dropdowns

Example:
<details>
  <summary>There's nothing in this dropdown</summary>
  Nothing. Told ya.
</details>

Example code:

```html
<details>
  <summary>There's nothing in this dropdown</summary> <!-- text indicating what's in your dropdown -->
  Nothing. Told ya. <!-- here you can have whatever you want: text, images, gifs, videos, code, etc -->
</details>
```
<hr/>

### Put things side by side and resize (very useful for a lot of images)

Example:
<p float="left" />
<img width="300" src="https://images-na.ssl-images-amazon.com/images/I/71+mDoHG4mL.png" />
<img width="300" src="https://www.pngarts.com/files/1/Baby-Cat-PNG-Picture.png" />
<img width="300" src="https://www.pngarts.com/files/10/Cat-PNG-High-Quality-Image.png" />
</p>

Example code:

```html
<p float="left" /> <!-- you can try float="right" as well -->
<img width="300" src="https://images-na.ssl-images-amazon.com/images/I/71+mDoHG4mL.png" />
<!-- width depends on the images you're using -->
<img width="300" src="https://www.pngarts.com/files/1/Baby-Cat-PNG-Picture.png" />
<img width="300" src="https://www.pngarts.com/files/10/Cat-PNG-High-Quality-Image.png" />
</p>
```
