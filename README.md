# `http-server` test page

This is a test page for `http-server`.

This page is generated automatically by `http-server` using the latest release found in the [original repository](https://github.com/patrickdappollonio/http-server). The page is generated using a GitHub Action and contains examples of most of the supported features by the server.

Below, you'll find some examples of Markdown content. The [`file-types`](file-types) folder contains examples of different file types that can be served by `http-server`, [`images`](images) contains images, and [`subfolder-markdown`](subfolder-markdown) contains a subfolder with a Markdown `README` file that automatically renders when entering the site.

Finally, [`website/`](website) contains a simple, pure HTML website that can be served by `http-server` and is used to test the practical flow of the server.

For all these actions, the command executed to start the server is:

```sh
http-server --port 8000
```

And `wget` is used in crawl mode to download the website and all its contents, creating a static copy.

For more information, visit the [original repository](https://github.com/patrickdappollonio/http-server).

## Markdown test section

This is a test section for Markdown. All headings work as intended (as seen in this page).

### Paragraphs, bold, italic, strikethrough

Lorem ipsum dolor sit amet, **consectetur adipiscing elit**. Sed vulputate tristique metus, _at consequat erat dignissim ac_. Aenean in ligula tempus, *rutrum neque eu*, ornare tellus. Maecenas quam risus, ornare a ultrices nec, posuere quis nunc. Nulla metus nisl, ~~bibendum vitae magna sed~~, consequat pellentesque odio. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam a nisl eu augue pellentesque porta porttitor eget felis. Quisque facilisis feugiat justo a elementum. Suspendisse dignissim vitae felis ac commodo. Fusce vitae quam hendrerit, commodo sapien id, posuere nisl. Vestibulum fringilla at tortor cursus tempus. Nunc neque lacus, placerat non lorem id, mattis imperdiet risus.

Cras et ex ligula. **Vivamus maximus id elit malesuada tincidunt**. ~~Duis vitae consequat felis~~. _Suspendisse quis risus eu sapien pharetra eleifend_. Nulla pharetra aliquet elit. Fusce gravida rhoncus nisl, in gravida augue semper ut. Nunc ac ex tempus, feugiat velit id, viverra justo.

<sub>Hello</sub> <sup>World</sup>!

### Admonitions

These are all the admonitions supported by `http-server`, following the implementation on GitHub Markdown:

> [!NOTE]
> Highlights information that users should take into account, even when skimming.
>
> This is a second paragraph of the note.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

### Foot notes

This is a footnote[^1] and this is another one[^2].

[^1]: This is a footnote.

[^2]: This is another footnote.

### MermaidJS Diagrams

This example is in the [`mermaid-example.md` file](mermaid-example.md).

### Images

![Sample image from folder](images/laptop-computer-on-wooden-table.jpg)

### Links

[Link to Google](https://www.google.com)

[Link within the same page](#http-server-test-page)

[Link to a folder](subfolder-markdown)

[Link to a file](images/a-small-green-bird-sits-on-thin-branch-in-a-green-tree.jpg)

### Code

The following code fence is set to Javascript, however there's no syntax highlighting.

```js
let foo = "bar";

console.log(foo);

myfunc(() => {
  console.log("callback");
});
```

### Tables

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |

### Blockquotes

> This is a blockquote.

### Lists

#### Unordered

* Item 1
* Item 2
  * Sub-item 1
  * Sub-item 2
* Item 3

#### Ordered

1. Item 1
2. Item 2
   1. Sub-item 1
   2. Sub-item 2
3. Item 3

### List checks

- [x] This is a checked list item
- [ ] This is an unchecked list item
  - [ ] This is an unchecked list sub-item
  - [x] This is a checked list sub-item
