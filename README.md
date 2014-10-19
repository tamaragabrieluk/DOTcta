DOTcta
======
<em>CSS3 button library for web designers and web developers.</em>

<h3>Getting started</h3>

It's really easy to <a href="http://youtu.be/Whf2oLg5h3E" target="_blank">get started using DOTcta</a>. DOTcta works with the <code>anchor</code> and <code>button</code> HTML elements, as well as any buton-like <code>input</code> types.

=====

<h3>Creating a button</h3>

<h5>Initialise DOTcta</h5>
To create a button, first initialise DOTcta with the class <code>.cta</code>

```html
  <button type="button" class="cta">My button<button>
```

<h5>Add a size</h5>
The next you'll need do is add a <a href="http://libs.doodleboxmedia.co.uk/dot/cta/cta-sizes/" target="_blank">size</a> to your button. DOTcta comes with five size classes:<br>
<code>.cta-xs</code><br>
<code>.cta-sm</code><br>
<code>.cta-md</code><br>
<code>.cta-lg</code><br>
<code>.cta-xl</code><br>

In order to add a size to your button, you'll do something like this:

```html
  <button type="button" class="cta cta-md">My button<button>
```

<h5>Add a shape <em>(optional)</em></h5>
To add a <a href="http://libs.doodleboxmedia.co.uk/dot/cta/cta-shapes/" target="_blank">shape</a> to your button, you'll need to add a shape modifier to your size class above. There are four shape modifiers in total:<br>
<code>-curved</code><br>
<code>-pill</code><br>
<code>-swoosh</code><br>
<code>-swoosh-r</code><br>

But there are 5 shapes altogether. Without adding a shape modifier the button will have sharp edges, which is your first button shape option. To set a different shape add a modifier like this:

```html
  <button type="button" class="cta cta-md-curved">My button<button>
```

<h5>Add a style</h5>
There are five <a href="http://libs.doodleboxmedia.co.uk/dot/cta/cta-styles/" target="_blank">style</a> classes altogether:<br>
<code>.cta-flat</code><br>
<code>.cta-hollow</code><br>
<code>.cta-hollow-thick</code><br>
<code>.cta-hollow-thicker</code><br>
<code>.cta-gradient</code><br>
<code>.cta-glossy</code><br>

To add a style your button, simply add one of the style classes to your class attribute. Your button code will look something like this:

```html
  <button type="button" class="cta cta-md-curved cta-gradient">My button<button>
```

==========

<h3>Positioning your buttons</h3>
There are three position classes that you can use with DOTcta, in order to left, right and center align your buttons:<br>

<code>.cta-align-left</code><br>
<code>.cta-align-right</code><br>
<code>.cta-align-center</code>

All you have to do is wrap your button in a `<p>` tag like this:

```html
  <p class="cta-align-center"><a class="cta cta-lg...">Button</a></p>
```

==========

<h3>Aligning your buttons</h3>
There might be times when you want to have a block-level button or have upto 3 buttons on one line, evenly spaced. The available classes for this are:<br>

<code>.cta-block</code><br>
<code>.cta-2</code><br>
<code>.cta-3</code>

To create buttons all on one row, evenly spaced, all you have to do is wrap your buttons in a `div` tag with the class `.cta-group`. An example of having two butttons on one row would look like this:<br>

```html
  <div class="cta-group">
    <a class="cta cta-sm cta-flat cta-2">Button 1</a>
    <a class="cta cta-sm cta-flat cta-2">Button 2</a>
  </div>
```

If you wanted to have three buttons on one row evenly spaced, just follow the same code structure above, but add one more button and change `cta-2` to `cta-3` on all of the buttons.

Note that the block-level button `cta-block` does not have to be wrapped in div with the class `cta-group` - it can stand on its own like this:<br>

```html
  <a class="cta cta-sm cta-curved cta-flat cta-block">Block-level button</a>
```

============

<h3>Create a list of buttons</h3>
Creating a list of buttons simply requires the class `.cta-list` as a class attribute in the `ul` tag. Then you just need to wrap your buttons in the `li` tag:<br>

```html
  <ul class="cta-list">
    <li><a class="cta cta-md cta-curved cta-hollow">List button 1</a></li>
    <li><a class="cta cta-md cta-curved cta-hollow">List button 2</a></li>
    <li><a class="cta cta-md cta-curved cta-hollow">List button 3</a></li>
    <li><a class="cta cta-md cta-curved cta-hollow">List button 4</a></li>
  </ul>
```

=======

<h3>Additional helpers</h3>

DOTcta comes with some additional helpers:<br>

<h5>.cta-white</h5>
This allows you to override the default colour (black) with a white button. This is particularly handy if you have a dark background and need a lighter button. To use this just add `.cta-white' to your class attribute like this:<br>

```html
  <a class="cta cta-sm cta-curved cta-flat cta-white">White button</a>
```

<h5>.cta-no-stack</h5>
With DOTcta being responsive, it will stack your buttons with the viewport gets lower than 768px (it works nicely with Bootstrap). But say you want to keep your button from stacking and becoming a full-width button. All you have to do is add the class `.cta-no-stack` and this will keep your button and its default width:

```html
  <a class="cta cta-sm cta-curved cta-flat cta-no-stack">White button</a>
```

<h5>.cta-wide</h5>
This class allows you to give your button a bit of extra padding left and right in order to slightly increase its width from the default:

```html
  <a class="cta cta-sm cta-curved cta-flat cta-wide">White button</a>
```

============

<h3>Add colour to your buttons with priority classes</h3>

The default theme for DOTcta is black, but if you want to add colour to your buttons, head over to the <a href="https://github.com/doodleboxmedia/DOTcta/tree/custom-themes">custom-themes branch</a> to download either the Sass files of the CSS file, and learn how easy it is to add colour.
