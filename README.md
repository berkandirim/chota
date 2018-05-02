<p align="center">
<img src="https://jenil.github.io/chota/logo.svg" />
<br><br>
A really small CSS framework
</p>

<br>

*   ⚡️&nbsp; Super light-weight. Just 3kb (minified + gzipped).
*   ⛔️&nbsp; This is the scss port so sass is your preprocessor.
*   📐&nbsp; Grid number can be changed via variable.
*   🌈&nbsp; Easy to extend with sass variables
*   🎲&nbsp; Comes with a handful of [components](https://jenil.github.io/chota/#components) &amp; [utilities](https://jenil.github.io/chota/#utilities)
*   ✅&nbsp; Good Semantics

<br>

### Get started

```
npm i chota-scss
```

While you can compile the scss with `buildsass` script, what you really should do is to import `scss/chota` into your main scss file and compile it with your custom css. Take a look at the example config below.

### Variables List

```scss
// sizes
$grid-columns: 12;
$grid-maxWidth: 120rem;
$grid-gutter: 2rem;

// colors
$primary-color: #1a9f60;
$lightGrey-color: #d2d6dd;
$darkGrey-color: #84868b;
$red-color: #c62424;

// typography
$base-font-size: 62.5%;
$base-line-height: 1.6;
$font-family: -apple-system, BlinkMacSystemFont, Avenir, 'Avenir Next', 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue', sans-serif;
$monospace-font-family: monaco, 'Consolas', 'Lucida Console', monospace;

// other
$base-box-shadow: 0 0 2px rgba(0, 0, 0, 0.4);
$base-transition: all 0.2s ease;
```

If you want to change the default variables, your main scss file should be something like this:

```scss
@import '<your-vars-override>';
@import '<path-to-chota>/scss/chota';
@import '<your-custom-css>';
```

<br>

## Browsers support

| <img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/edge.png" alt="IE / Edge" width="16px" height="16px" /></br>IE / Edge | <img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/firefox.png" alt="Firefox" width="16px" height="16px" /></br>Firefox | <img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/chrome.png" alt="Chrome" width="16px" height="16px" /></br>Chrome | <img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/safari.png" alt="Safari" width="16px" height="16px" /></br>Safari | <img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/opera.png" alt="Opera" width="16px" height="16px" /></br>Opera | <img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/safari-ios.png" alt="iOS Safari" width="16px" height="16px" /></br>iOS Safari | <img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/chrome-android.png" alt="Chrome for Android" width="16px" height="16px" /></br>Chrome for Android |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edge 16+                                                                                                                                                           | last 2 versions                                                                                                                                                   | last 2 versions                                                                                                                                                | last 2 versions                                                                                                                                                | last 2 versions                                                                                                                                             | last 2 versions                                                                                                                                                            | last 2 versions                                                                                                                                                                                |

---

&copy; Jenil Gogari 2017-present. Code released under the [MIT license](https://github.com/jenil/chota/blob/master/LICENSE).
