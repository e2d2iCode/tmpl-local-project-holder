<!-- markdownlint-disable MD041-->
The typical use case for *admonitions* is to draw the reader's attention to a p articular point. They can appear anywhere in an ordinary HTML `body` element, including another *admonition*.

Admonitions consisit of a colored box with an optional header and a body. The header is composed of an icon and a title, both of which can be customized. The body is a normal paragraph of text.

Below is a quick example of multiple nested admonitions of different types:

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">
<div style="font-size: 95%; text-align: justify;">

!!! note

    This is the **note** admonition body

    !!! danger Danger Title
        This is the **danger** admonition body

        !!! success ""
            This is the **success** admonition body, with stripped out title and icons

            As shown below, there are plenty of other types to choose from !

</div>
</div>
<!-- markdownlint-enable MD041-->
