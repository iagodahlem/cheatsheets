[index]: https://github.com/rafaelrinaldi/cheatsheets
[robert-penner]: https://twitter.com/robpenner
[css-is-awesome]: https://jsbin.com/gasexu/edit?html,css,output
[centering-things-transform]: https://jsbin.com/gadidi/edit?html,css,output
[centering-things-table]: https://jsbin.com/medomec/edit?html,css,output
[centering-things-flexbox]: https://jsbin.com/bimeno/edit?html,css,output
[san-francisco-font]: https://developer.apple.com/fonts

# CSS

[![CSS is awesome](css-is-awesome.png)][css-is-awesome]

1. [Apple San Fancisco font](#apple-san-francisco-font)
2. [Centering things](#centering-things)
  * [Using `transform` and absolute positioning](#using-transform-and-absolute-positioning)
  * [Mimicking `<table>` display](#mimicking-table-display)
  * [Using Flexbox](#using-flexbox)
3. [Font anti alias](#font-anti-alias)
4. [Smooth scrolling](#smooth-scrolling)
5. [Text selection](#text-selection)
6. [Transition easing functions](#transition-easing-functions)

---

### Apple San Francisco font

```css
body {
  font-family: -apple-system, BlinkMacSystemFont, sans-serif;
}
```

### Centering things

#### [Using `transform` and absolute positioning][centering-things-transform]

Useful when you already know the container dimension

```css
.parent {
  position: relative;
  /* Arbitrary dimension */
  width: 150px;
  height: 150px;
}

.child {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```

#### [Mimicking `<table>` display][centering-things-table]

```css
.parent {
  display: table;
}

.child {
  display: table-cell;
  vertical-align: middle;
  text-align: center;
}
```

#### [Using Flexbox][centering-things-flexbox]

```css
.parent {
  display: flex;
  justify-content: center;
  align-items: center;
}

.child {}
```

### Font anti alias

```css
* {
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```

### Smooth scrolling

```css
.container {
  -webkit-overflow-scrolling: touch;
  overflow-y: auto;
}
```

### Text selection

```css
/* Can't select both at the same time */

::selection {
  color: #FFF;
  background-color: #F06;
}

::-moz-selection {
  color: #FFF;
  background-color: #F06;
}
```

### Transition easing functions

Rounded values from [Robert Penner][robert-penner]'s easing functions.

```css
transition-timing-function: cubic-bezier(/* matrix */);
```

| Name | Matrix |
| --- | --- |
| Linear | `0.250, 0.250, 0.750, 0.750` |
| Ease | `0.250, 0.100, 0.250, 1.000` |
| Easein | `0.420, 0.000, 1.000, 1.000` |
| Easeout | `0.000, 0.000, 0.580, 1.000` |
| EaseInOut | `0.420, 0.000, 0.580, 1.000` |
| EaseInQuad |`0.550, 0.085, 0.680, 0.530` |
| EaseOutQuad | `0.250, 0.460, 0.450, 0.940` |
| EaseInOutQuad | `0.455, 0.030, 0.515, 0.955` |
| EaseInCubic | `0.550, 0.055, 0.675, 0.190` |
| EaseOutCubic | `0.215, 0.610, 0.355, 1.000` |
| EaseInOutCubic | `0.645, 0.045, 0.355, 1.000` |
| EaseInQuart | `0.895, 0.030, 0.685, 0.220` |
| EaseOutQuart | `0.165, 0.840, 0.440, 1.000` |
| EaseInOutQuart | `0.770, 0.000, 0.175, 1.000` |
| EaseInQuint | `0.755, 0.050, 0.855, 0.060` |
| EaseOutQuint | `0.230, 1.000, 0.320, 1.000` |
| EaseInOutQuint | `0.860, 0.000, 0.070, 1.000` |
| EaseInSine | `0.470, 0.000, 0.745, 0.715` |
| EaseOutSine | `0.390, 0.575, 0.565, 1.000` |
| EaseInOutSine | `0.445, 0.050, 0.550, 0.950` |
| EaseInExpo | `0.950, 0.050, 0.795, 0.035` |
| EaseOutExpo | `0.190, 1.000, 0.220, 1.000` |
| EaseInOutExpo | `1.000, 0.000, 0.000, 1.000` |
| EaseInCirc | `0.600, 0.040, 0.980, 0.335` |
| EaseOutCirc | `0.075, 0.820, 0.165, 1.000` |
| EaseInOutCirc | `0.785, 0.135, 0.150, 0.860` |
| EaseInBack | `0.600, -0.280, 0.735, 0.045` |
| EaseOutBack | `0.175, 0.885, 0.320, 1.275` |
| EaseInOutBack | `0.680, -0.550, 0.265, 1.550` |

---

[← Back][index]
