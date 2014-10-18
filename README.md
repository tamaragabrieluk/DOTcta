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
There might be times when you want to have a block-level button or have upto 3 buttons on one line, evenly spaced. All you have to do is wrap your buttons in a `div` tag with the class `cta-group`. An example of having two butttons on one row would look like this:<br>

```html
  <div class="cta-group">
    <a class="cta cta-sm cta-flat cta-2">Button 1</a>
    <a class="cta cta-sm cta-flat cta-2">Button 2</a>
  </div>
```

Note that the block-level button `cta-block` does not have to be wrapped in div with the class `cta-group` - it can stand on its own like this:<br>

```html
  <a class="cta cta-sm cta-curved cta-flat cta-block">Block-level button</a>
```

<h5>Align classes</h5>
<code>.cta-2</code><br>
<code>.cta-3</code>

============

<h3>Priorities for colours</h3>

When <a href="http://youtu.be/nQZpi3Izvns" target="_blank">using a theme</a>, you can set your buttons to override the default black and grey theme, and have whatever colours you want. There are two <a href="http://libs.doodleboxmedia.co.uk/dot/cta/cta-priorities/" target="_blank">priority</a> classes to use in this instance <code>.cta-prmary</code> and <code>.cta-secondary</code>. When using these classes you can mix and match any shape and style, all you have to do is add the priority classes to you buttons:

```html
  <button type="button" class="cta cta-md-curved cta-flat cta-primary">My button<button>
  <button type="button" class="cta cta-md-curved cta-hollow cta-secondary">My button<button>
```

That's pretty much the basics of adding a button to your web page. Check out the website <a href="http://www.dotcta.com" target="_blank">dotcta.com</a> for more helpers and info on using DOTcta.
