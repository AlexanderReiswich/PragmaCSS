# Effects

Various utility classes are available to add commonly utilized effects such as rounded corners, shadows
and transitions to your elements.

## Border

You can add a basic border on all sides with the following classes.


<div class="align-vh space-between wrap push-v-xl pull-right-m">
  <div class="inline border-s border-primary soft bold center extend-m pad-m push-up-s push-right-m va-top">
    .border-s
  </div>
  <div class="inline border border-primary soft bold center extend-m pad-m push-up-s push-right-m va-top">
    .border-m<br>(or .border)
  </div>
  <div class="inline border-l border-primary soft bold center extend-m pad-m push-up-s push-right-m va-top">
    .border-l
  </div>
  <div class="inline border-xl border-primary dark bold center extend-m pad-m push-up-s push-right-m va-top">
    .border-xl
  </div>
</div>

```html
<div class="border-s border-primary">
  .border-s
</div>

<div class="border border-primary">
  .border-m (or .border)
</div>

<div class="border border-primary">
  .border-l
</div>

<div class="border-xl border-primary">
  .border-xl
</div>
```

::: tip INFO
The default border style is configurable via global variables.
:::

<br>

### Targeted borders

You can add borders to specific sides:

<div class="grid gap-l">
    <div class="push-down col s12 m6">
        <div class="border-top border-dark pad-m light-bg dark bold center extend-s">
            .border-top
        </div>
    </div>
    <div class="push-down col s12 m6">
        <div class="border-right border-dark pad-m light-bg dark bold center extend-s">
            .border-right
        </div>
    </div>
</div>

<div class="grid gap-l">
    <div class="push-down col s12 m6">
        <div class="border-bottom border-dark pad-m light-bg dark bold center extend-s">
            .border-bottom
        </div>
    </div>
    <div class="push-down col s12 m6">
        <div class="border-left border-dark pad-m light-bg dark bold center extend-s">
            .border-left
        </div>
    </div>
</div>

```html
<div class="border-top border-dark">
  .border-top
</div>

<div class="border-right border-dark">
  .border-right
</div>

<div class="border-bottom border-dark">
  .border-bottom
</div>

<div class="border-left border-dark">
  .border-left
</div>
```

::: tip GOOD TO KNOW
You can of course further refine all border classes with size suffixes, i.e.: `.border-top-l`, `.border-bottom-s`, etc.
:::

<br>

### Removing borders

It's possible to remove borders on specific sides, as well:

<div class="grid gap-l">
    <div class="push-down col s12 m6">
        <div class="border border-dark border-top-0 border-dark pad-m light-bg dark bold center extend-s">
            .border.border-top-0
        </div>
    </div>
    <div class="push-down col s12 m6">
        <div class="border border-dark border-right-0 border-dark pad-m light-bg dark bold center extend-s">
            .border-right-0
        </div>
    </div>
</div>

<div class="grid gap-l">
    <div class="push-down col s12 m6">
        <div class="border border-dark border-bottom-0 border-dark pad-m light-bg dark bold center extend-s">
            .border.border-bottom-0
        </div>
    </div>
    <div class="push-down col s12 m6">
        <div class="border border-dark border-left-0 border-dark pad-m light-bg dark bold center extend-s">
            .border-left-0
        </div>
    </div>
</div>

```html
<div class="border border-dark border-top-0">
  .border.border-top-0
</div>

<div class="border border-dark border-right-0">
  .border.border-right-0
</div>

<div class="border border-dark border-bottom-0">
  .border.border-bottom-0
</div>

<div class="border border-dark border-left-0">
  .border.border-left-0
</div>
```

<br>

### Border colors

All available colors can be assigned to borders.

<div class="grid gap-m">
    <div class="push-down col s12">
        <div class="border-primary dark bold center extend-m pad-m push-down">
            .border-primary
        </div>
    </div>
</div>

<div class="grid gap-m">
    <div class="push-down col s12 m12 l4">
        <div class="border-dark dark bold center extend-m pad-m push-down">
            .border-dark
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-soft dark bold center extend-m pad-m push-down">
            .border-soft
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-pale dark bold center extend-m pad-m push-down">
            .border-pale
        </div>
    </div>
</div>

<div class="grid gap-m">
    <div class="push-down col s12 m12 l4">
        <div class="border-light dark bold center extend-m pad-m push-down">
            .border-light
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-white dark bold center extend-m pad-m push-down">
            .border-white
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-black dark bold center extend-m pad-m push-down">
            .border-black
        </div>
    </div>
</div>

<div class="grid gap-m">
    <div class="push-down col s12 m12 l4">
        <div class="border-red dark bold center extend-m pad-m push-down">
            .border-red
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-green dark bold center extend-m pad-m push-down">
            .border-green
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-yellow dark bold center extend-m pad-m push-down">
            .border-yellow
        </div>
    </div>
</div>

<div class="grid gap-m">
    <div class="push-down col s12 m12 l4">
        <div class="border-orange dark bold center extend-m pad-m push-down">
            .border-orange
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-blue dark bold center extend-m pad-m push-down">
            .border-blue
        </div>
    </div>
    <div class="push-down col s12 m12 l4">
        <div class="border-violet dark bold center extend-m pad-m push-down">
            .border-violet
        </div>
    </div>
</div>


### Border styles

The default border style is predefined in a global variable, but can be explicitly set
via the following classes:

<div class="border-primary solid dark bold center extend-m pad-m push-down">
    <span class="pale">.border-primary</span>.solid
</div>

<div class="border-primary dashed dark bold center extend-m pad-m push-down">
    <span class="pale">.border-primary</span>.dashed
</div>

<div class="border-primary dotted dark bold center extend-m pad-m push-down">
    <span class="pale">.border-primary</span>.dotted
</div>

<br>

## Rounded corners

These classes add roundness to an elements corners.

<div class="rounded-s inline blue-bg white bold center extend-m pad-m push-down-m push-right-m">
    .rounded-s
</div>

<div class="rounded-m inline blue-bg white bold center extend-m pad-m push-down-m push-right-m">
    .rounded-m
</div>

<div class="rounded-l inline blue-bg white bold center extend-m pad-m push-down-m push-right-m">
    .rounded-m
</div>

<br>

<div class="rounded-full inline blue-bg white bold center extend-m pad-m push-down-m push-right-m">
    .rounded-full
</div>

<div class="circular inline blue-bg white bold center extend-m pad-m push-down-m push-right-m">
    .circular
</div>

```html
<div class="rounded-s">
  .rounded-s
</div>

<div class="rounded-m">
  .rounded-m
</div>

<div class="rounded-l">
  .rounded-l
</div>

<div class="rounded-full">
  .rounded-full
</div>

<div class="circular">
  .circular
</div>
```

<br>

You can also negate corner roundness for specific sides via the following classes:

<div class="rounded-full rounded-0 orange-bg white bold pad-m push-down-m push-right-s">
    .rounded-0
</div>

<div class="rounded-full rounded-0-top-left orange-bg white bold pad-m push-down-m push-right-s">
    .rounded-full.rounded-0-top-left
</div>

<div class="rounded-full rounded-0-top-right orange-bg white bold pad-m push-down-m push-right-s">
    .rounded-full.rounded-0-top-right
</div>

<div class="rounded-full rounded-0-bottom-right orange-bg white bold pad-m push-down-m push-right-s">
    .rounded-full.rounded-0-bottom-right
</div>

<div class="rounded-full rounded-0-bottom-left orange-bg white bold pad-m push-down-m push-right-s">
    .rounded-full.rounded-0-bottom-left
</div>

```html
<div class="rounded-full rounded-0-top-left">
  .rounded-full.rounded-0-top-left
</div>

<div class="rounded-full rounded-0-top-right">
  .rounded-full.rounded-0-top-right
</div>

<div class="rounded-full rounded-0-bottom-left">
  .rounded-full.rounded-0-bottom-left
</div>

<div class="rounded-full rounded-0-bottom-right">
  .rounded-full.rounded-0-bottom-right
</div>
```

<br>

## Shadows

The following group of classes adds a box shadow to your element.
You can customize the general shadow style via global variables.

<div class="shadow-s rounded inline white-bg dark bold pad-m push-v-m push-right-xl">
    .shadow-s
</div>

<div class="shadow-m rounded inline white-bg dark bold pad-m push-v-m push-right-xl">
    .shadow-m
</div>

<div class="shadow-l rounded inline white-bg dark bold pad-m push-v-m push-right-xl">
    .shadow-l
</div>

```html
<div class="shadow-s">.shadow-s</div>
<div class="shadow-m">.shadow-m</div>
<div class="shadow-l">.shadow-l</div>
```

<br>

### Shadow on hover

You can also apply shadows on hover only:

<div class="shadow-s-on-hover rounded inline white-bg dark bold pad-m push-v-m push-right-xl cursor-default">
    .shadow-s-on-hover
</div>

<div class="shadow-m-on-hover rounded inline white-bg dark bold pad-m push-v-m push-right-xl cursor-default">
    .shadow-m-on-hover
</div>

<div class="shadow-l-on-hover rounded inline white-bg dark bold pad-m push-v-m push-right-xl cursor-default">
    .shadow-l-on-hover
</div>

```html
<div class="shadow-s-on-hover">.shadow-s-on-hover</div>
<div class="shadow-m-on-hover">.shadow-m-on-hover</div>
<div class="shadow-l-on-hover">.shadow-l-on-hover</div>
```

<br>

## Scale on hover

These classes will increase the size of an element when you move the mouse cursor over it.<br>

<div class="space-between wrap pull-right-s push-v-xl">
    <div class="scale-on-hover-s rounded inline violet-bg light bold pad-m push-up-s push-right-s cursor-default">
        .scale-on-hover-s
    </div>
    <div class="scale-on-hover-m rounded inline violet-bg light bold pad-m push-up-s push-right-s cursor-default">
        .scale-on-hover-m
    </div>
    <div class="scale-on-hover-l rounded inline violet-bg light bold pad-m push-up-s push-right-s cursor-default">
        .scale-on-hover-l
    </div>
</div>

```html
<div class="scale-on-hover-s">.scale-on-hover-s</div>
<div class="scale-on-hover-m">.scale-on-hover-m</div>
<div class="scale-on-hover-l">.scale-on-hover-l</div>
```

<br>

## Transitions

`.tween` classes add transitions to your elements.

<div class="space-between wrap pull-right-s">
    <div class="tween-xs rounded inline blue-bg light bold pad-m push-up-s primary-bg-on-hover scale-on-hover-m push-right-s push-down-m cursor-default">
        .tween-xs
    </div>
    <div class="tween-s rounded inline blue-bg light bold pad-m push-up-s primary-bg-on-hover scale-on-hover-m push-right-s push-down-m cursor-default">
        .tween-s
    </div>
    <div class="tween-m rounded inline blue-bg light bold pad-m push-up-s primary-bg-on-hover scale-on-hover-m push-right-s push-down-m cursor-default">
        .tween-m
    </div>
    <div class="tween-l rounded inline blue-bg light bold pad-m push-up-s primary-bg-on-hover scale-on-hover-m push-right-s push-down-m cursor-default">
        .tween-l
    </div>
    <div class="tween-xl rounded inline blue-bg light bold pad-m push-up-s primary-bg-on-hover scale-on-hover-m push-right-s push-down-m cursor-default">
        .tween-xl
    </div>
</div>

::: tip GOOD TO KNOW
In case the name "tweening" doesn't ring a bell:
It's a common term used in the animation industry to describe the transitional frames be**tween** keyframes,
which is exactly what happens when you apply CSS transitions.

It's just much nicer than writing "transition" all the time.
:::

```html
<div class="tween-xs">.tween-xs</div>
<div class="tween-s">.tween-s</div>
<div class="tween-m">.tween-m</div>
<div class="tween-l">.tween-l</div>
<div class="tween-xl">.tween-xl</div>
```

<br>

## Mouse cursor utilities

These classes help you enforce certain mouse cursor behaviors.

<div class="pointer tween rounded inline yellow-bg dark light-on-hover bold pad-m push-v-s dark-bg-on-hover">
    .pointer
</div>

<div class="cursor-default tween rounded inline yellow-bg dark light-on-hover bold pad-m push-v-s dark-bg-on-hover">
    .cursor-default
</div>

<div class="no-pointer-events tween rounded inline yellow-bg dark light-on-hover bold pad-m push-v-s dark-bg-on-hover">
    .no-pointer-events
</div>

<br>

<div class="cursor-forbidden tween rounded inline pale-bg white bold pad-m push-v-s">
    .cursor-forbidden
</div>


```html
<div class="pointer">
  .pointer
</div>

<div class="cursor-default">
  .cursor-default
</div>

<div class="no-pointer-events">
  .no-pointer-events
</div>

<div class="cursor-forbidden">
  .cursor-forbidden
</div>
```

<br>

## Image utilities

### .responsive

The `.responsive` class forces images to resize in order to fit the available space on smaller screens.

<img :src="$withBase('/logo.png')" alt="Responsive image" class="responsive block centered">

```html
<img src="/logo.png"
  alt="Responsive image"
  class="responsive block centered">
```

<br>

### .full-width

This class behaves similarly to `.responsive`, except that it always fills out the available horizontal space.

<img :src="$withBase('/logo.png')" alt="Responsive image" class="full-width block centered">

```html
<img src="/logo.png"
  alt="Full width responsive image"
  class="full-width block centered">
```

<br>

### .pixelate

When images are scaled up, modern browsers will use anti-aliasing to smooth out individual pixels, which
is not always desirable.

To disable this effect, apply the `.pixelate` class.

<img :src="$withBase('/qr_code.png')" alt="Responsive image" class="pixelate full-width block centered">

```html
<img src="/qr_code.png"
  alt="Full width responsive image"
  class="pixelate full-width block centered">
```

<br>

For comparison, this is the same scaled up image without the `.pixelated` class:

<img :src="$withBase('/qr_code.png')" alt="Responsive image" class="full-width block centered">
