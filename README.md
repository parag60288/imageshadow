# What is this?

Get perfect shadows every time for non-designer.

# Installation

`npm i image-shadow --save`

Then...

```
import {imageshadow} from 'image-shadow';

imageshadow({
  shadow_type: 'soft',
  padding: false
});
```

## Options

Imageshadow supports two options, both of which are optional:

- _shadow_type_ - _hard | soft_ (Defaults to soft)
- _padding_ - _boolean_ (Defaults to false)
