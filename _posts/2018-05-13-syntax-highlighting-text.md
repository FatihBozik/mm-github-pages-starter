---
title: "Syntax Highlighting Demo"
tags:
  - gist-embed
  - github
  - gist
categories:
  - Syntax Highlighting
toc: false
author_profile: true
excerpt: "Test writing about how code blocks look on the site"
---

### GFM Code Blocks

```java
public class Animal {
  String name;
  public String getName() {
    return name;
  }
  public void setName(String newName) {
    name = newName;
  }
}
```

### GFM Code Blocks with Line Numbers

{% highlight java linenos %}
public class Animal {
  String name;
  public String getName() {
    return name;
  }
  public void setName(String newName) {
    name = newName;
  }
}
{% endhighlight %}

### Github Gist Embed

<code data-gist-id="2ea384ae4ddd272403bbae996d942b8d" data-gist-show-loading="false" gist-enable-cache="true"></code>

### Github Gist Embed Hide Line numbers

<code data-gist-id="2ea384ae4ddd272403bbae996d942b8d" data-gist-hide-line-numbers="true" data-gist-show-loading="false" gist-enable-cache="true"></code>


### Github Gist Embed Hide Footer

<code data-gist-id="2ea384ae4ddd272403bbae996d942b8d" data-gist-hide-footer="true" data-gist-show-loading="false" gist-enable-cache="true"></code>


### Github Gist Embed Hide Footer and Line Numbers

<code data-gist-id="2ea384ae4ddd272403bbae996d942b8d" data-gist-hide-footer="true" data-gist-show-loading="false" data-gist-hide-line-numbers="true" gist-enable-cache="true"></code>


### Github Gist Embed Show Specified Lines [2-4]

<code data-gist-id="2ea384ae4ddd272403bbae996d942b8d" data-gist-hide-footer="true" data-gist-show-loading="false" data-gist-hide-line-numbers="false" gist-enable-cache="true" data-gist-line="2-4"></code>

### Github Gist Loading single lines and a range of line numbers (line 1, 2 and line 6 through 9) but with collapsing the others

<code data-gist-id="2ea384ae4ddd272403bbae996d942b8d" data-gist-line="1,2,6-9" data-gist-lines-expanded="true"></code>

### Highlighting a list of line numbers from a gist (line 1, 3, 5)

<code data-gist-id="2ea384ae4ddd272403bbae996d942b8d" data-gist-highlight-line="1,3,5"></code>