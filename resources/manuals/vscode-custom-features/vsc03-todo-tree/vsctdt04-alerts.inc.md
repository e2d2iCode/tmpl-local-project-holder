<!-- markdownlint-disable MD041-->
Tags pointing to issues whose severity is still to be established, but that are potentially damaging
enough to be considered as a threat. The tags from this category are typically transitional,
meaning that addressing such a tag is expected to yield its requalification as either a *record* or an
*issue* tag. Cleaning the project from all *alerts* should be every developer's 2nd highest priority,
right after clearing all tags marked as *issues*. Again, no release should be considered as long as
the todo-tree displays any of these tags.

<div class="tag-table alerts">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;TAG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
:-----:|:----:|:----|
<a href="https://primer.style/design/foundations/icons/checklist-16"  target="_blank"><img class="check-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/checklist.svg" alt="checklist.svg" title="check-icon: checklist.svg"/></a>| <a href="https://www.w3schools.com/colors/color_tryit.asp?color=XXX" title="XXX"><tag class="check-tag">CHECK</tag></a>  | Points out that something needs to be checked or tested. |
<a href="https://primer.style/design/foundations/icons/eye-16"  target="_blank"><img class="temp-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/hourglass.svg" alt="hourglass.svg" title="temp-icon: hourglass.svg"/></a>| <a href="https://www.w3schools.com/colors/color_tryit.asp?color=XXX" title="XXX"><tag class="temp-tag">TEMP</tag></a> | A temporary piece of code to be deleted in the short term.  |
<a href="https://primer.style/design/foundations/icons/clock-16"  target="_blank"><img class="review-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/clock.svg" alt="clock.svg" title="review-icon: clock.svg"/></a>| <a href="https://www.w3schools.com/colors/color_tryit.asp?color=XXX" title="XXX"><tag class="review-tag">REVIEW</tag></a> | Calls for something's critical  in an improvement aim.  |

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
.check-tag {
 color: black;
 background-color: orange;
}
.check-icon {
  filter: invert(76%) sepia(18%) saturate(7022%) hue-rotate(357deg) brightness(98%) contrast(108%);
}
.review-tag {
 color: black;
 background-color: gold;
}
.review-icon {
  filter: invert(76%) sepia(95%) saturate(1607%) hue-rotate(358deg) brightness(102%) contrast(106%);
}
.temp-tag {
 color: black;
 background-color: goldenRod;
}
.temp-icon {
  filter: invert(80%) sepia(54%) saturate(1608%) hue-rotate(345deg) brightness(90%) contrast(88%);
}
</style>

<!-- markdownlint-enable MD041 -->
