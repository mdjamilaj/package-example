# What is this?

Get perfect shadows every time for the non-designer

# Installation

`npm i shadow-example-package --save`

Then ...

```
import { shadow } from `shadow-example-package`;

shadow({
    shadow_type: 'soft',
    padding: false
});
```

## options

shadow supports 2 options, both of which are optional

- *shadow_type* - _hard | soft_ (Defaults to soft)
- *padding* - _boolean_ (Defaults to false)