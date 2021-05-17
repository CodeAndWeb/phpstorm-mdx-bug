# PhpStorm Demo project 

This is a demonstration project for https://github.com/valentinnodan/mdx-intellij-plugin/issues/13

- Open  `src/pages/test.mdx`
- Type `<Header` and use auto-completion

The resulting file:

~~~
import Header from "../components/header";
---
frontmatter: yes
---

# test

<Header
~~~



