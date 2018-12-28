# Buttons

Buttons are among the most common UI elements, which is why they're an essential part of PragmaCSS.
As you will see shortly, working with buttons is trivial, but at the same time there's huge potential
for customization.


## Basic button

Creating a simple button with default styling is easy as pie; Simply apply the `.btn` class to your element:

<br>

<button class="btn">
  Button
</button>

```html
<button class="btn">
  Button
</button>
```

<br>

## Size modifiers

Changing the width and height of a button is very straightforward. Just add the following classes to the
main `.btn` class in order to adjust the vertical or horizontal dimensions of your button&mdash;or both:

### Vertical size modifiers

<div class="space-between wrap">
  <button class="btn v-0 bold lowercase push-down-s">
    .v-0
  </button>
  <button class="btn v-xs bold lowercase push-down-s">
    .v-xs
  </button>
  <button class="btn v-s bold lowercase push-down-s">
    .v-s
  </button>
  <button class="btn v-m bold lowercase push-down-s">
    .v-m
  </button>
  <button class="btn v-l bold lowercase push-down-s">
    .v-l
  </button>
  <button class="btn v-xl bold lowercase push-down-s">
    .v-xl
  </button>
</div>

```html
<button class="btn v-0">.v-0</button>

<button class="btn v-xs">.v-xs</button>

<button class="btn v-s">.v-s</button>

<button class="btn v-m">.v-m</button>

<button class="btn v-l">.v-l</button>

<button class="btn v-xl">.v-xl</button>
```

<br>

### Horizontal size modifiers

<button class="btn h-0 bold lowercase push-down-s block">
  .h-0
</button>

<button class="btn h-xs bold lowercase push-down-s block">
  .h-xs
</button>
<button class="btn h-s bold lowercase push-down-s block">
  .h-s
</button>
<button class="btn h-m bold lowercase push-down-s block">
  .h-m
</button>
<button class="btn h-l bold lowercase push-down-s block">
  .h-l
</button>
<button class="btn h-xl bold lowercase push-down-s block">
  .h-xl
</button>
<button class="btn h-2xl bold lowercase push-down-s block">
  .h-2xl
</button>
<button class="btn h-3xl bold lowercase push-down-s block">
  .h-3xl
</button>

::: tip NOTE
There are two additional levels of scale for horizontal size modifiers that are not available for their
vertical counterparts. This is because buttons with more horizontal than vertical spacing are common.
:::

```html
<button class="btn h-0">.h-0</button>

<button class="btn h-xs">.h-xs</button>

<button class="btn h-s">.h-s</button>

<button class="btn h-m">.h-m</button>

<button class="btn h-l">.h-l</button>

<button class="btn h-xl">.h-xl</button>

<button class="btn h-2xl">.h-2xl</button>

<button class="btn h-3xl">.h-3xl</button>
```

<br>

### Combined size modifiers

<div class="space-between wrap">
    <button class="btn vh-0 bold lowercase push-down-s">
      .vh-0
    </button>
    <button class="btn vh-xs bold lowercase push-down-s">
      .vh-xs
    </button>
    <button class="btn vh-s bold lowercase push-down-s">
      .vh-s
    </button>
    <button class="btn vh-m bold lowercase push-down-s">
      .vh-m
    </button>
    <button class="btn vh-l bold lowercase push-down-s">
      .vh-l
    </button>
    <button class="btn vh-xl bold lowercase push-down-s">
      .vh-xl
    </button>
</div>

```html
<button class="btn vh-xs">.vh-xs</button>

<button class="btn vh-s">.vh-s</button>

<button class="btn vh-m">.vh-m</button>

<button class="btn vh-l">.vh-l</button>

<button class="btn vh-xl">.vh-xl</button>
```

<br>

## Button colors

To change the color of your button, simply add the desired background color utility class.

<div class="grid gap-l">
  <div class="col s12 m6 l4 push-down-m">
    <button class="btn full primary-bg">
      .primary-bg
    </button>
  </div>
  <div class="col s12 m6 l4 push-down-m">
    <button class="btn full secondary-bg">
      .secondary-bg
    </button>
  </div>
  <div class="col s12 m6 l4 push-down-m">
    <button class="btn full tertiary-bg">
      .tertiary-bg
    </button>
  </div>
</div>
<div class="grid gap-l">
  <div class="col s12 m6 push-down-m">
    <button class="btn full dark-bg">
      .dark-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full muted-bg">
      .muted-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full subtle-bg">
      .subtle-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full light-bg">
      .light-bg
    </button>
  </div>
</div>
<div class="grid gap-l">
  <div class="col s12 m6 push-down-m">
    <button class="btn full black-bg">
      .black-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full white-bg">
      .white-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full red-bg">
      .red-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full orange-bg">
      .orange-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full green-bg">
      .green-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full yellow-bg">
      .yellow-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blue-bg">
      .blue-bg
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full violet-bg">
      .violet-bg
    </button>
  </div>
</div>

```html
<button class="btn primary-bg">Button</button>
<button class="btn secondary-bg">Button</button>
<button class="btn tertiary-bg">Button</button>
<button class="btn dark-bg">Button</button>
<button class="btn muted-bg">Button</button>
<button class="btn subtle-bg">Button</button>
<button class="btn light-bg">Button</button>
<button class="btn black-bg">Button</button>
<button class="btn white-bg">Button</button>
<button class="btn red-bg">Button</button>
<button class="btn orange-bg">Button</button>
<button class="btn green-bg">Button</button>
<button class="btn yellow-bg">Button</button>
<button class="btn blue-bg">Button</button>
<button class="btn violet-bg">Button</button>
```

<br>

If you would like to use buttons on a dark or colored background, don't forget to add the `.inverted` class to the
parent container in order to ensure the buttons adapt to the background properly:

<div class="dark-bg inverted pad pad-down-0 rounded">
  <div class="grid gap">
    <div class="col s12 m6 l4 push-down-m">
      <button class="btn full primary-bg">
        .primary-bg
      </button>
    </div>
    <div class="col s12 m6 l4 push-down-m">
      <button class="btn full secondary-bg">
        .secondary-bg
      </button>
    </div>
    <div class="col s12 m6 l4 push-down-m">
      <button class="btn full tertiary-bg">
        .tertiary-bg
      </button>
    </div>
  </div>
  <div class="grid gap">
    <div class="col s12 m6 push-down-m">
      <button class="btn full dark-bg">
        .dark-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full muted-bg">
        .muted-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full subtle-bg">
        .subtle-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full light-bg">
        .light-bg
      </button>
    </div>
  </div>
  <div class="grid gap">
    <div class="col s12 m6 push-down-m">
      <button class="btn full black-bg">
        .black-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg">
        .white-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full red-bg">
        .red-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full orange-bg">
        .orange-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full green-bg">
        .green-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full yellow-bg">
        .yellow-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full blue-bg">
        .blue-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full violet-bg">
        .violet-bg
      </button>
    </div>
  </div>
</div>

<br>

The `.white-bg` class is designed to be used on dark backgrounds.
In addition, `.white-bg` is compatible with text colors.

<div class="dark-bg inverted pad pad-down-0 rounded">
  <div class="grid gap">
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg">
        .white-bg
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg primary">
        .white-bg.primary
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg secondary">
        .white-bg.secondary
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg tertiary">
        .white-bg.tertiary
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg muted">
        .white-bg.muted
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg black">
        .white-bg.black
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg red">
        .white-bg.red
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg orange">
        .white-bg.orange
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg green">
        .white-bg.green
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg yellow">
        .white-bg.yellow
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg blue">
        .white-bg.blue
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full white-bg violet">
        .white-bg.violet
      </button>
    </div>
  </div>
</div>

```html
<button class="btn light-bg">.light-bg</button>
<button class="btn white-bg">.white-bg</button>
<button class="btn white-bg primary">.white-bg.primary</button>
<button class="btn white-bg muted">.white-bg.muted</button>
<button class="btn white-bg black">.white-bg.black</button>
<button class="btn white-bg red">.white-bg.red</button>
<button class="btn white-bg orange">.white-bg.orange</button>
<button class="btn white-bg green">.white-bg.green</button>
<button class="btn white-bg yellow">.white-bg.yellow</button>
<button class="btn white-bg blue">.white-bg.blue</button>
<button class="btn white-bg violet">.white-bg.violet</button>
```

<br>

## Blank button

Sometimes you might need the functionality of a button without the actual button shape. Simply use the .blank class
to achieve this effect:

<button class="btn push-down push-right">
  Call to action
</button>

<button class="btn blank push-down">
  More details
</button>

```html
<button class="btn push-down push-right">
  Call to action
</button>

<button class="btn blank">
  More details
</button>
```

<div class="grid gap push-up-l">
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank primary">
      .blank.primary
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank secondary">
      .blank.secondary
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank tertiary">
      .blank.tertiary
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank muted">
      .blank.muted
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank black">
      .blank.black
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank red">
      .blank.red
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank orange">
      .blank.orange
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank green">
      .blank.green
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank yellow">
      .blank.yellow
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank blue">
      .blank.blue
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full blank violet">
      .blank.violet
    </button>
  </div>
</div>

<br>

## Disabled button

If you either add the `.disabled` class or the `disabled` property to your button, it will be styled accordingly:

<button class="btn push-down" disabled>
  Disabled button
</button>

```html
<button class="btn" disabled>
  Disabled button
</button>
```

<br>

A disabled button when used on a dark inverted background:

<div class="dark-bg inverted pad rounded push-down-xl">
  <button class="btn" disabled>
    Disabled button
  </button>
</div>

<br>

## Ghost buttons

Due to their unobtrusive look, Ghost buttons convey a comparatively subtle call to action. Nevertheless, they
serve an important role, as they help to establish a clear visual hierarchy which provides your users
with more clarity while navigating your site.

Naturally, it's possible to also apply all available colors to ghost buttons:

<div class="grid gap">
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost">
      .btn.ghost
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost secondary">
      .btn.ghost.secondary
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost tertiary">
      .btn.ghost.tertiary
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost dark">
      .btn.ghost.dark
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost muted">
      .btn.ghost.muted
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost subtle">
      .btn.ghost.subtle
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost light">
      .btn.ghost.light
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost black">
      .btn.ghost.black
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost red">
      .btn.ghost.red
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost orange">
      .btn.ghost.orange
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost green">
      .btn.ghost.green
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost yellow">
      .btn.ghost.yellow
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost blue">
      .btn.ghost.blue
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost violet">
      .btn.ghost.violet
    </button>
  </div>
</div>

<br>

When used on a dark inverted background:

<div class="dark-bg inverted pad pad-down-0 rounded">
  <div class="grid gap">
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost">
        .btn.ghost
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost secondary">
        .btn.ghost.secondary
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost tertiary">
        .btn.ghost.tertiary
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost dark">
        .btn.ghost.dark
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost muted">
        .btn.ghost.muted
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost subtle">
        .btn.ghost.subtle
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost light">
        .btn.ghost.light
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost white">
        .btn.ghost.white
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost red">
        .btn.ghost.red
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost orange">
        .btn.ghost.orange
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost green">
        .btn.ghost.green
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost yellow">
        .btn.ghost.yellow
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost blue">
        .btn.ghost.blue
      </button>
    </div>
    <div class="col s12 m6 push-down-m">
      <button class="btn full ghost violet">
        .btn.ghost.violet
      </button>
    </div>
  </div>
</div>

```html
<button class="btn ghost">.btn.ghost</button>
<button class="btn ghost dark">.btn.ghost.secondary</button>
<button class="btn ghost dark">.btn.ghost.tertiary</button>
<button class="btn ghost dark">.btn.ghost.dark</button>
<button class="btn ghost muted">.btn.ghost.muted</button>
<button class="btn ghost subtle">.btn.ghost.subtle</button>
<button class="btn ghost black">.btn.ghost.black</button>
<button class="btn ghost red">.btn.ghost.red</button>
<button class="btn ghost orange">.btn.ghost.orange</button>
<button class="btn ghost green">.btn.ghost.green</button>
<button class="btn ghost yellow">.btn.ghost.yellow</button>
<button class="btn ghost blue">.btn.ghost.blue</button>
<button class="btn ghost violet">.btn.ghost.violet</button>
```

<br>

### Border styling

You can add the `border` utility classes in order to control the width and style of the border.

<div class="grid gap">
  <div class="col s12 push-down-m">
    <button class="btn full ghost border-0">
      .btn.ghost.border-0
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost border-s">
      .btn.ghost.border-s
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost border-m">
      .btn.ghost.border-m
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost border-l">
      .btn.ghost.border-l
    </button>
  </div>
  <div class="col s12 m6 push-down-m">
    <button class="btn full ghost border-xl">
      .btn.ghost.border-xl
    </button>
  </div>
</div>

```html
<button class="btn ghost border-s">.btn.ghost.border-s</button>
<button class="btn ghost border-m">.btn.ghost.border-m</button>
<button class="btn ghost border-l">.btn.ghost.border-l</button>
<button class="btn ghost border-xl">.btn.ghost.border-xl</button>
```

<br>

## Loading indicator

You can add an element with a `.spinner` class inside of the button in order to indicate a loading state.

<div class="space-between wrap push-v">
  <button class="btn push-v-m no-pointer-events">
    <i class="spinner-m negative border-white push-right-s"></i> Loading...
  </button>
  <button class="btn ghost blue v-l push-v-m no-pointer-events">
    <i class="spinner-l border-blue border-l va-text-top push-h"></i>
  </button>
  <button class="btn light-bg push-v-m reset no-pointer-events">
    <i class="spinner-l va-text-top push-right-s"></i> Loading...
  </button>
</div>

```html
<button class="btn push-v-m no-pointer-events">
  <i class="spinner-m negative border-white push-right-s"></i>
  Loading...
</button>

<button class="btn ghost blue v-l push-v-m no-pointer-events">
  <i class="spinner-l border-blue border-l va-text-top push-h"></i>
</button>

<button class="btn light-bg push-v-m reset no-pointer-events">
  <i class="spinner-l va-text-top push-right-s"></i>
  Loading...
</button>
```

<br>

## Icons

Naturally it's possible to add anything you like inside of buttons, including icons.
Here are a few examples using our transformicons:

<div class="space-between wrap push-v">
  <button class="btn orange-bg push-v-m pad-left-s">
    <div class="tico-m push-right-s">
      <i class="tico-check white"><span/></i>
    </div> Saved
  </button>
  <button class="btn green-bg push-v-m pad-left-s">
    <div class="tico-m push-right-s">
      <i class="tico-plus white"><span/></i>
    </div> Add
  </button>
  <button class="btn ghost push-v-m pad-left-s">
    <div class="tico-m push-right-s">
      <i class="tico-chevron-right primary"><span/></i>
    </div> Continue
  </button>
</div>

<div class="space-between wrap push-v">
  <button class="btn blue-bg size-m push-v-m pad-left-s">
    <div class="tico-l push-right-s">
      <i class="tico-check white"><span/></i>
    </div> size-l
  </button>
  <button class="btn blue-bg size-l push-v-m pad-left-s">
    <div class="tico-xl push-right-s">
      <i class="tico-check white"><span/></i>
    </div> size-xl
  </button>
  <button class="btn blue-bg size-xl push-v-m pad-left-s">
    <div class="tico-2xl push-right-s">
      <i class="tico-check white"><span/></i>
    </div> size-2xl
  </button>
</div>

```html
<button class="btn orange-bg">
  <div class="tico-m push-right-s">
    <i class="tico-check white"><span/></i>
  </div> Saved
</button>

<button class="btn green-bg">
  <div class="tico-m push-right-s">
    <i class="tico-plus white"><span/></i>
  </div> Add
</button>

<button class="btn ghost">
  <div class="tico-m push-right-s">
    <i class="tico-chevron-right primary"><span/></i>
  </div> Continue
</button>

<button class="btn blue-bg size-m">
  <div class="tico-l push-right-s">
    <i class="tico-check white"><span/></i>
  </div> size-l
</button>

<button class="btn blue-bg size-l">
  <div class="tico-xl push-right-s">
    <i class="tico-check white"><span/></i>
  </div> size-xl
</button>

<button class="btn blue-bg size-xl">
  <div class="tico-2xl push-right-s">
    <i class="tico-check white"><span/></i>
  </div> size-2xl
</button>
```

<br>

## Utility class overrides

Buttons are compatible with most utility classes. This allows you to easily customize them further in
countless ways. Here are a few examples:


### .btn.reset.light-bg
<button class="btn reset light-bg push-s">
  Button
</button>

---

### .btn.rounded-0
<button class="btn rounded-0 push-s">
  Button
</button>

---

### .btn.rounded-l
<button class="btn rounded-l push-s">
  Button
</button>

---

### .btn.rounded-full
<button class="btn rounded-full push-s">
  Button
</button>

---

### .btn.size-xl.bold
<button class="btn size-xl bold push-s">
  Button
</button>

---

### .btn.ghost.bold.border-s.dashed
<button class="btn ghost bold border-s dashed push-s">
  Button
</button>


---

### .btn.ghost.border-s.rounded-full.size-l.v-l.h-xl
<button class="btn ghost border-s rounded-full size-l v-l h-xl">
  Button
</button>

---

### .btn.scale-s-on-hover
<button class="btn scale-s-on-hover push-s">
  Button
</button>

---

### .btn.white-bg.white-bg-on-hover.shadow-s.shadow-m-on-hover
<button class="btn white-bg primary white-bg-on-hover dark-on-hover shadow-s shadow-m-on-hover push-s">
  Button
</button>

---

### .btn.full
<button class="btn full push-v-m">
  Button
</button>
