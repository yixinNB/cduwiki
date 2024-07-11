---
layoutClass: m-nav-layout
outline: [ 2, 3, 4 ]
p: 0.1
---

<script setup>
import { NAV_DATA } from './data'
</script>


网站管理员: admin@erledge.com

[如何在本网站发布新文章](如何在本网站发布文章.md)

<MNavLinks v-for="{title, items} in NAV_DATA" :title="title" :items="items"/>

## Contributors

<a href="https://github.com/yixinnb/CDU-WiKi/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=yixinnb/CDU-WiKi" />
</a>