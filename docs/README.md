[[toc]]

.
├─ README.md
├─ foo
│  ├─ README.md
│  ├─ one.md
│  └─ two.md
└─ bar
   ├─ README.md
   ├─ three.md
   └─ four.md

[Home](/) <!-- 将根目录下的 README.md 发送给用户 -->
[foo](/foo/) <!-- 将 foo 目录下的 README.md 发送给用户 -->
[foo 标题锚点](/foo/#heading) <!-- 跳转到 foo 目录下的 README.md 文件中的特定锚点位置 -->
[foo - one](/foo/one.html) <!-- 追加 .html -->
[foo - two](/foo/two.md) <!-- 或者追加 .md -->
---
title: Blogging Like a Hacker
lang: en-US
meta:
  - name: description
    content: hello
  - name: keywords
    content: super duper SEO
---

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

:tada: :100:

::: tip
This is a tip
:::

::: warning
This is a warning
:::

::: danger
This is a dangerous warning
:::

::: danger STOP
Danger zone, do not proceed
:::

``` js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

