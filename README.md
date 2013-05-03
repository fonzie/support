# Support

Helpers for writing cross-browser CSS. Handles adding prefixes for 
most properties that require them.

## Installation

```
bower install fonzie-support
```

## Usage

Use the mixins for the property you want and the correct prefixes
will be added for that property or value. **It will always output the
non-prefixed version last.**

```scss
.box {
  @include border-radius(5px);
}
```

You can adjust the prefixes that are used in the last parameter:

```scss
.box {
  @include border-radius(5px, -moz);
}
```
