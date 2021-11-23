---
title: Formatting Testing
linktitle: Formatting Testing
date: 2021-11-23
---
# Test

## Markdown Content
{{< hint info >}}
**Markdown content**  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
{{< /hint >}}

{{< hint warning >}}
**Markdown content**  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
{{< /hint >}}

{{< hint danger >}}
**Markdown content**  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
{{< /hint >}}

## Math Functions
{{< katex display="block" class="text-center"  >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}

## Bold Text
**Bold Text**

## Quote
> quote
> someone 
> wrote

OR

> multi <br />
> line <br />
> Quote

## Link
[LINK](https://www.google.com)

## Bullets
- ddd
- ddd
- ddd

1. List
2. List
3. List


## Code blocks
```python
#language
print("code")
echo("test")
def test(test):
    for test in tests:
        test += 1
```

```
#Generic
print("code");
echo("test");
```
{{< highlight go >}} A bunch of code here {{< /highlight >}}



## YouTube
Use the ID of the youtube video
{{ <youtube VqHcDmcvczQ >}}

```
{{ <youtube VqHcDmcvczQ >}}
{{< youtube id="w7Ft2ymGmfc" title="A New Hugo Site in Under Two Minutes" >}}
```