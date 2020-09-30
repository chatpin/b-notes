Sat 12 Sep 2020 16:22:55 BST

# mardown/toc
___
## notes
### table of content example

> Here's a useful method. Should produce clickable references in any MarkDown editor.

> (code can be viewed in ReText and is available up on [stack](https://stackoverflow.com/questions/11948245/markdown-to-create-pages-and-table-of-contents))

    # Table of contents
    1. [Introduction](#introduction)
    2. [Some paragraph](#paragraph1)
        1. [Sub paragraph](#subparagraph1)
    3. [Another paragraph](#paragraph2)

    ## This is the introduction <a name="introduction"></a>
    Some introduction text, formatted in heading 2 style

    ## Some paragraph <a name="paragraph1"></a>
    The first paragraph text

    ### Sub paragraph <a name="subparagraph1"></a>
    This is a sub paragraph, formatted in heading 3 style

    ## Another paragraph <a name="paragraph2"></a>
    The second paragraph text`

**Produces**:

# Table of contents
1. [Introduction](#introduction)
2. [Some paragraph](#paragraph1)
   	1. [Sub paragraph](#subparagraph1)
3. [Another paragraph](#paragraph2)

    ## This is the introduction <a name="introduction"></a>
    Some introduction text, formatted in heading 2 style

    ## Some paragraph <a name="paragraph1"></a>
    The first paragraph text

    ### Sub paragraph <a name="subparagraph1"></a>
    This is a sub paragraph, formatted in heading 3 style

    ## Another paragraph <a name="paragraph2"></a>
    The second paragraph text`

___

> [stackoverflow](https://stackoverflow.com/questions/11948245/markdown-to-create-pages-and-table-of-contents) -- stumbled on this up on stack, enabling movement around amd within your .md docs

> [index](./index-file.md)

> [home](./home.md) 

