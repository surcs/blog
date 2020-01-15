---
title: "List"
date: 2019-10-08T18:24:24+08:00
weight : 7
---

## Unordered

markdown

```markdown
+ 1
 - 2  ('+' or '-' doesn't matter)
 + 3
+ 4
```

html

```html
<ul>
    <li>1</li>
    <ul>
        <li>2</li>
        <li>3</li>
    </ul>
    <li>4</li>
</ul>
```

renders to:


+ 1
 - 2  ('+' or '-' doesn't matter)
 + 3
+ 4

<ul>
    <li>1</li>
    <ul>
        <li>2</li>
        <li>3</li>
    </ul>
    <li>4</li>
</ul>

***

## Ordered

markdown

```markdown
1. a
2. b
3. c
4. d
```

html

```html
<ol>
    <li>!</li>
    <li>?</li>
</ol>
```

##### renders to:

1. a
2. b
3. c
4. d

<ol>
    <li>!</li>
    <li>?</li>
</ol>

Actually, for **every** number, Markdown will automatically number each item.

```markdown
2. a
2. b
4. c
```

2. a
2. b
4. c