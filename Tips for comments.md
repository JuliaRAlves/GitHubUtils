# Commenting on GitHub

Have you ever been lost while commenting on GitHub? Are your comments ugly? Do you get pissed off when a comment is so long that it takes ages to scroll to the end? You're in the right place! Here are some tips to avoid anger with comments:

## When your comment gets too big:

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
<!-- also works for gifs and other types of images, but doesn't work for videos -->
<img width="300" src="https://www.pngarts.com/files/1/Baby-Cat-PNG-Picture.png" />
<img width="300" src="https://www.pngarts.com/files/10/Cat-PNG-High-Quality-Image.png" />
</p>
```

<hr/>

## When your comment looks ugly:

### Format links (specially the insanely huge ones)

Example:

[This is a beautiful link](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=video&cd=&cad=rja&uact=8&ved=2ahUKEwi10NHG4aL3AhUrjZUCHZVMDjMQtwJ6BAgREAI&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DdQw4w9WgXcQ&usg=AOvVaw0aHtehaphMhOCAkCydRLZU)

Example code:
```markdown
[This is a beautiful link](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=video&cd=&cad=rja&uact=8&ved=2ahUKEwi10NHG4aL3AhUrjZUCHZVMDjMQtwJ6BAgREAI&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DdQw4w9WgXcQ&usg=AOvVaw0aHtehaphMhOCAkCydRLZU)
<!-- you can use any link you want (specially with insanely huge links ;) ) -->
```

### Enhance your code block

Bad examples:

```
<p id="randomTxt" color="black">This is an ugly, gray and boring HTML code</p>
val text: String = "I'm a text inside of an unformatted Kotlin code"
```

HTML example:

```html
<p id="randomTxt" color="black">This is a beautiful, colorful and readable code!</p>
```

Kotlin example:

```kotlin
val text: String = "I'm a text inside of a beautiful Kotlin code"
```

Example codes:

````
HTML example:

```html
<p id="randomTxt" color="black">This is a beautiful, colorful and readable code!</p>
```

Kotlin example:

```kotlin
val text: String = "I'm a text inside of a beautiful Kotlin code"
```
````

### Enhance your diff

Example:

```diff
         yayFunction()
         coolFunction()
-        myFunction()
+
+        val text: String = "random example string"
     }
 
     private fun yayFunction() {
```

Example code:

````
```diff
         yayFunction()
         coolFunction()
-        myFunction()
+
+        val text: String = "random example string"
     }
 
     private fun yayFunction() {
```
````
