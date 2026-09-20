---
status: unfinished
---

# Mkdocs Reference Stuff

For full documentation visit [:material-link:mkdocs.org](https://www.mkdocs.org).

??? info "Commands"
    * `mkdocs new [dir-name]` - Create a new project.
    * `mkdocs serve` - Start the live-reloading docs server.
    * `mkdocs build` - Build the documentation site.
    * `mkdocs -h` - Print help message and exit.

## Code Blocks

```py title="addition.py" linenums="1" hl_lines="3"
a = 3
b = 12
print(a+b)
```
## Lists

- Hi
- Hello
- Salutations

hi

1. one thing
2. another thing
3. third thing

## Content Tabs

=== "Windows"
    Do abc and xyz.

=== "Mac"
    Use Wine or give up.

=== "Linux"
    GTFO.

## Admonitions/Callouts

!!! note
    This is a note.

??? info "This note has a name..."
    ...and can be collapsed and expanded at will.

==I can highlight things!!!==

Keyboard keys too! Press ++cmd+k++ to open search.

~Subscripts~ and ^superscripts^??

<figure markdown="span">
  ![Image title](https://dummyimage.com/600x400/){ width="300" }
  <figcaption><strong>Figure 1.</strong> A cool placeholder image.</figcaption>
</figure>