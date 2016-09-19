# Collapse

Collapse component for Vue Bulma.


## Installation

```
$ npm install vue-bulma-collapse --save
```


## Examples

```vue
<template>
  <collapse accordion is-fullwidth>
    <collapse-item title="Components">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. @bulmaio. #css #responsive
    </collapse-item>
    <collapse-item title="Elements">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. @bulmaio. #css #responsive
    </collapse-item>
      <collapse-item title="Nests" selected>
      <collapse>
        <collapse-item title="Nest Child" selected>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. @bulmaio. #css #responsive
        </collapse-item>
      </collapse>
    </collapse-item>
  </collapse>
</template>

<script>
import { Collapse, Item as CollapseItem } from 'vue-bulma-collapse'

export default {
  components: {
    Collapse,
    CollapseItem
  }
}
</script>
```


## Badges

![](https://img.shields.io/badge/license-MIT-blue.svg)
![](https://img.shields.io/badge/status-stable-green.svg)

---

> [fundon.me](https://fundon.me) &nbsp;&middot;&nbsp;
> GitHub [@fundon](https://github.com/fundon) &nbsp;&middot;&nbsp;
> Twitter [@_fundon](https://twitter.com/_fundon)
