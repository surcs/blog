---
title: "Code"
date: 2019-10-08T19:12:17+08:00
weight : 8
---

## Inline Code

markdown

```markdown
For example, `this is the code` in the sentence ( using `` ` ``).
```

html

```html
<p>For example, <code>this is the code</code></p>
```

##### renders to:

For example, `this is the code1` in the sentence ( using `` ` `` ).

<p>For example, <code>this is the code2</code></p>

***

## Indented Code

markdown

```markdown
  line 1 of code (indent several lines of code by at least four spaces)
```

html

```html
<pre><code>line 1 of code
line 2 of code</code></pre>
```
##### renders to:

    line 1 of code (indent several lines of code by at least four spaces)


<pre><code>line 1 of code
line 2 of code</code></pre>

***

## Code Fence

markdown

<pre><code>```
public class HelloWorld1 {
    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
```</code></pre>

<pre><code>```java
public class HelloWorld2 {
    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
```</code></pre>

##### renders to:

```
public class HelloWorld1 {
    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
```
PS: (Syntax highlighting) simply add the file extension of the language you want to use directly after **```**

but here it seem not working !???

```java
public class HelloWorld2 {
    public static void main(String[] args) {
        System.out.println("Hello, World");
    }
}
```