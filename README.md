# Prefix

Mixins to prefix properties and values.

## Installation

```
bower install fonzie-prefix
```

## Usage

```scss
.box {
  @include fz-prefix(border-radius, 5px, -webkit -moz -o);
  @include fz-prefixValue(display, flex, -webkit -moz);
}
```