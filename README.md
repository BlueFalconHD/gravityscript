> **Note**: This is not owned by me! Original source is at: https://code.google.com/archive/p/gravityscript/

<h1 align="center">🌕 Gravityscript</h1>
<h3 align="center">Javascript to make objects on your webpage obey gravity</p>
<h3 align="center"><a href="https://www.josephpcohen.com/">By Joseph Paul Cohen</a></h3>

## ⚙️ Usage

### 🗃 In Code
Include the following code snippet in the `<head>` tag of your website, or include it somewhere in the body.
```html
<script src="https://bluefalconhd.github.io/gravityscript/gravityscript.js"></script>
```
### 🔖 Bookmarklet/Injection
To run this on a page where you cannot access the source, you can use this bookmarklet. A bookmarklet runs javascript on a page when clicked. Highlight this block of code and drag it to your bookmarks bar to add it, then click it to run this script on any site.

```js
var script = document.createElement("script"); script.src="https://bluefalconhd.github.io/gravityscript/gravityscript.js"; document.body.appendChild(script); void(0);
```

The standard version waits for a user to move their mouse. This version starts without the mouse moving:
```html
<script src="https://bluefalconhd.github.io/gravityscript/gravityscript-autorun.js"></script>
```
# ❤️ Thanks to
- [Joseph Paul Cohen](https://www.josephpcohen.com/) for [the original gravityscript](https://code.google.com/archive/p/gravityscript/)
- [Mr. Doob](https://mrdoob.com/) for [the original Google Gravity](https://mrdoob.com/projects/chromeexperiments/google-gravity/)
