# Prefix

Mixins to prefix properties and values.

## Installation

```
fonzie install prefix
```

## Usage

```scss
.box {
  @include prefix(border-radius, 5px, -webkit -moz -o);
  @include prefix-value(display, flex, -webkit -moz);
}
```