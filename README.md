DOTcta Custom Theme
====================

The default theme for DOTcta is black, so if you want to add your own colours to your buttons its really easy.

<h3>Add colour to your buttons with priority classes</h3>

When using a theme, you can set your buttons to override the default black theme, and have whatever colours you want. Your theme will need four base colours: a primary colour, a secondary colour, a tertiary colour, and a hover colour. For each of these base colours you will also need an appropriate text colour. There are three priority classes you will need to use in your class attribute in order to apply your theme to your buttons:<br>

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
By using the <a href="https://github.com/doodleboxmedia/DOTcta/blob/custom-themes/scss/themes/theme-custom/_custom-theme-colours.scss">Sass files</a> all you have to do is drop your hex values into the variables in custom-theme-colours.scss found in scss/themes/theme-custom (just pastee them over the example hex values that are already there). Then recompile and include the DOTcta-custom-theme.css file in your HTML document.


<h5>Using the CSS file</h5>
If you're not too familiar with Sass or you don't use, you can simply grab the <a href="https://github.com/doodleboxmedia/DOTcta/blob/custom-themes/css/DOTcta-custom-theme.css">DOTcta-custom-theme.css</a> from the css folder and add your colours in throughout the stylesheet (just replace the hex values that are already there). Then all you have to do is include the stylesheet in your HTML document.
