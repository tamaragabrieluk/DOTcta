DOTcta Custom Theme
====================

The default theme for DOTcta is black, so if you want to add your own colours to your buttons its really easy.

<h3>Add colour to your buttons with priority classes</h3>

When <a href="http://youtu.be/nQZpi3Izvns" target="_blank">using a theme</a>, you can set your buttons to override the default black theme, and have whatever colours you want. There are three priority classes to use in this instance:<br>

<code>.cta-prmary</code><br>
<code>.cta-secondary</code><br>
<code>.cta-tertiary</code>

When using these classes you can mix and match any size, shape and style, all you have to do is add the priority classes to you buttons:

```html
  <button type="button" class="cta cta-md-curved cta-flat cta-primary">Primary colour button<button>
  <button type="button" class="cta cta-md-curved cta-hollow cta-secondary">Secondary colour button<button>
  <button type="button" class="cta cta-md-curved cta-flat cta-tertiary">Tertiary colour button<button>
```

=======

<h3>Adding the colours to your stylesheet</h3>

There are two ways you can add colours to the stylesheet provided. Using the CSS file or the Sass files.

<h5>Using the Sass files</h5>
By using the Sass files all you have to do is drop your hex values into the variables in custom-theme-colours.scss found in scss/themes/theme-custom (just pastee them over the example hex values that are already there). Then recompile and include the DOTcta-custom-theme.css file in your HTML document.

<h5>Using the CSS file</h5>
If you're not too familiar with Sass or you don't use, you can simply grab the DOTcta-custom-theme.css from the css folder and add your colours in throughout the stylesheet (just replace the hex values that are already there). Then all you have to do is include the stylesheet in your HTML document.

======

<h3>That's it</h3>

That's pretty much the basics of adding a button to your web page. Check out the website <a href="http://www.dotcta.com" target="_blank">dotcta.com</a> for more helpers and info on using DOTcta.
