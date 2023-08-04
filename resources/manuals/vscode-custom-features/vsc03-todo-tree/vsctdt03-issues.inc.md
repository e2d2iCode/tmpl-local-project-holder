<!-- markdownlint-disable MD041-->
Tags identifying major issues and calling for immediate action. Freeing the project from all tags
falling into that category should be the developers' highest priority. No release should be
considered until every single one of them has been addressed and removed from the project, no
matter its present state and the location of the tags. For this reason, the extension should be
configured to display the tags from this category wherever the tree is generated from.

<div class="tag-table issues">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;TAG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
:-----:|:----:|:----|
<a href="https://primer.style/design/foundations/icons/bug-16"  target="_blank"><img class="bug-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/bug.svg" alt="bug.svg" title="bug-icon: bug.svg"/></a>| <a href="https://www.w3schools.com/colors/color_tryit.asp?color=XXX" title="XXX"><tag class="bug-tag">BUG</tag></a> | Describes an identified bug (still) needing to be addressed.  |
<a href="https://primer.style/design/foundations/icons/alert-16"  target="_blank"><img class="fixme-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/tools.svg" alt="tools.svg" title="fixme-icon: tools.svg"/></a>| <a href="https://www.w3schools.com/colors/color_tryit.asp?color=XXX" title="XXX"><tag class="fixme-tag">FIXME</tag></a> | Formally identifies and describes something needing a fix.  |
<a href="https://primer.style/design/foundations/icons/thumbsup-16"  target="_blank"><img class="finish-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/clock.svg" alt="clock.svg" title="finish-icon: clock.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=Blue" title="Blue"><tag class="finish-tag">FINISH</tag></a>  | Documents a non-critical task that still needs to be done. |

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
.bug-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(255, 0, 0);
}
.bug-icon {
  filter: invert(16%) sepia(76%) saturate(7012%) hue-rotate(358deg) brightness(102%) contrast(118%);
}
.finish-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(255, 99, 71)
}
.finish-icon {
  filter: invert(51%) sepia(37%) saturate(3074%) hue-rotate(330deg) brightness(105%) contrast(118%);
}
.fixme-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(255, 69, 0)
}
.fixme-icon {
  filter: invert(44%) sepia(87%) saturate(5514%) hue-rotate(4deg) brightness(103%) contrast(107%);
}
</style>

<!-- markdownlint-enable MD041 -->
