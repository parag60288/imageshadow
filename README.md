# What is this?

Get perfect shadows every time for non-designer/

# Installation

`npm i imageshadow --save`

Then...

```
import {imageshadow} from 'imageshadow';

imageshadow({
  shadow_type: 'soft',
  padding: false
});
```

## Options

Imageshadow supports two options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)