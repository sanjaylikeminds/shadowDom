# what is this?

Get perfect shadows every time for the non-designer

# Installation

`npm i shadowDom --save`

Then...

```
import { shadowDom } from 'shadowDom'

shadowDom({
    shadow_type: 'soft',
    padding: false
})

```

## Options

shadowDom supports 2 options, both of which are optionl:

- _shadow_type_ - _hard | soft_ (Defaults to soft)
- _padding_ - _boolean_ (Defaults to false)
