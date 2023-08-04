<!-- markdownlint-disable MD041-->
Tags that are used to visually segment the project's file. The extension is configured to provide 6
levels of sectioning, starting with *parts* and *chapters* and ending with *sub-sub-sub-sections*.
Obviously, tags from this category call for no action at all and are intrinsically meant to never be
deleted; their number even has a vocation to increase with the size of the project and, thus, over
time. It is worth noting that the case of *dividers* is in complete contrast to this of *helpers*. Indeed,
unlike *helpers*, *dividers* have no interest at all in the listing ability of the extension. Instead, they
benefit from the fact that tags can be highlighted within the project's source files.

<div class="tag-table dividers">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;TAG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
:-----:|:----|:----|
<a href="https://primer.style/design/foundations/icons/log-16"  target="_blank"><img class="part-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/log.svg" alt="log.svg" title="part-icon: log.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=darkSlateGrey" title="darkSlateGrey"><tag class="part-tag">PART</tag></a> | Whole-line speparator. |
<a href="https://primer.style/design/foundations/icons/book-16"  target="_blank"><img class="chapter-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/book.svg" alt="book.svg" title="chapter-icon: book.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=Olive" title="Olive"><tag class="chapter-tag">CHAPTER</tag></a> | A chapter using the *line* setting. |
<a href="https://primer.style/design/foundations/icons/rows-16"  target="_blank"><img class="section-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/rows.svg" alt="rows.svg" title="section-icon: rows.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=DarkOliveGreen" title="DarkOliveGreen"><tag class="section-tag">SECTION</tag></a> | A section using the *text-and-comment* setting.  |
<a href="https://primer.style/design/foundations/icons/bookmark-16"  target="_blank"><img class="subsect-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/bookmark.svg" alt="bookmark.svg" title="subsect-icon: bookmark.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=DarkGreen" title="DarkGreen"><tag class="subsect-tag">SUBSECTION</tag></a> | A sub-section using the *tag-and-comment* setting. |
<a href="https://primer.style/design/foundations/icons/three-bars-16"  target="_blank"><img class="block-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/three-bars.svg" alt="three-bars.svg" title="block-icon: three-bars.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=LimeGreen" title="LimeGreen"><tag class="block-tag">BLOCK</tag></a> | A paragraph or any enumeration like, typically, a list. |
<a href="https://primer.style/design/foundations/icons/triangle-right-16"  target="_blank"><img class="item-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/triangle-right.svg" alt="triangle-right.svg" title="item-icon: triangle-right.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=LightGreen" title="LightGreen"><tag class="item-tag">ITEM</tag></a> | Highlights a given element in a block like, typically a list entry. |

</div>

<style>
div.tag-table  {
  font-size: normal;
  min-width: 45em;
}
div.tag-table tag {
  width: 85%;
  padding: 0 .75ex 0 .6ex;
  display: inline-block;
  text-align: center;
}
div.tag-table img {
  height: 24px;
  margin-top: 8px;
}
.part-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(47, 79, 79);
}
.part-icon {
  filter: invert(26%) sepia(55%) saturate(447%) hue-rotate(202deg) brightness(150%) contrast(87%);
}
.chapter-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(128, 128, 0);
}
.chapter-icon {
  filter: invert(47%) sepia(31%) saturate(3762%) hue-rotate(38deg) brightness(92%) contrast(101%);
}
.section-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(85, 107, 47);
}
.section-icon {
  filter: invert(42%) sepia(43%) saturate(631%) hue-rotate(48deg) brightness(92%) contrast(84%);
}

.subsect-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(0, 100, 0);
}
.subsect-icon {
  filter: invert(26%) sepia(99%) saturate(1153%) hue-rotate(91deg) brightness(99%) contrast(107%);
}
.block-tag {
 color: rgb(50, 205, 50);
 background-color: none;
}
.block-icon {
  filter: invert(72%) sepia(29%) saturate(2106%) hue-rotate(66deg) brightness(90%) contrast(89%);
}
.item-tag {
 color: rgb(144, 238, 144);
 background-color: none;
}
.item-icon {
  filter: invert(88%) sepia(19%) saturate(933%) hue-rotate(61deg) brightness(96%) contrast(94%);
}

</style>
<!-- markdownlint-enable MD041-->
