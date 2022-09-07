# Learning Markdown

What can you do with _Markdown_? I suppose lots of things, without **having** to learn HTML.

Though I think you can also use <code>HTML</code> too?

*Yup, you sure can...*

## TODO

- [x] Do homework
- [x] Do homework
- [ ] Do homework
- [ ] Do homework
- [x] Write *even more* Markdown documents!

## Tables

| Features                                       | Comment     |
|------------------------------------------------|-------------|
| HTML                                           | Indeed      |
| Italics with `_` and single `*`                | Indeed      |
| Tables                                         | You Betcha  |
| Inline monospace with backticks <code>`</code> | `Yup`       |

## Images

![Inspectocat](https://octodex.github.com/images/inspectocat.jpg)

_Inspectocat_ using the Developer Tools to find out why Lab 2 wasn't loading properly.

![nyantocat singing a tune](https://octodex.github.com/images/nyantocat.gif)

## Code

### Python

```python

import random

greetings = (
    'Hello',
    'Hello World',
    'こんにちは',
    'おはよう',
)

print(random.choice(greetings))

```

### C++

```cpp

#include <iostream>
int main(int argc, char** argv)
{
    for (int i = 0; i < argc; ++i) {
        std::cerr << argv[i] << ((i + 1 < argc) ? " " : "\n");
    }
    return 0;
}

```
