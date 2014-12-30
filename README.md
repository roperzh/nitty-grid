# Nitty Grid

Minimalistic and semantic grid system based on [griddle](https://github.com/necolas/griddle).

## Installation

- Download: [zip](https://github.com/roperzh/nitty-grid/zipball/master)
- Bower: `bower install --save nitty-grid`

## Usage

**HTML**

```html
<div class="grid">
  <div class="six columns">6</div>
  <div class="four columns">4</div>
  <div class="two columns">2</div>
</div>
```

**Result**

![simplegrid](https://cloud.githubusercontent.com/assets/4419992/4262328/967c358e-3b99-11e4-861a-c189b9f116b0.jpg)

### Nested grids

**HTML**
```html
<div class="grid">
  <div class="six columns">
    <div class="grid">
      <div class="six columns">6</div>
      <div class="six columns">6</div>
    </div>
  </div>
  <div class="four columns">4</div>
  <div class="two columns">2</div>
</div>
```

**Result**

![multi-grid-sample](https://cloud.githubusercontent.com/assets/4419992/5581983/14693d2e-9041-11e4-8e44-415b16e7fbeb.jpg)

## Browser support

- Google Chrome
- Firefox
- Safari
- Opera
- Internet Explorer 8+

## License

MIT License
