<!-- markdownlint-disable MD041-->
Tags identifying editable parts of the project, either by delimiting customizable areas or by being
themselves placeholders meant to be replaced. Tags from this category typically call for actions on a
template that are meant to happen at a pre-determined point in the project's life cycle. Depending on
its nature, each of these tags may be repeatedly needed and, thus, persist throughout all project's
life cycles, or serve only once and then be removed. As a result, whether or not their presence
impacts the project's release readiness must be evaluated on a case-by-case basis. It is however
very unlikely that any of them should be part of the project's final distribution.

<div class="tag-table markers">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;TAG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
:-----:|:----|:----|
<a href="https://primer.style/design/foundations/icons/typography-16"  target="_blank"><img class="atat-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/typography.svg" alt="typography.svg" title="atat-icon: typography.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=DeepPink" title="DeepPink"><tag class="atat-tag">@@</tag></a> | Prefixes keywords that are placeholders for customizable values  |
<a href="https://primer.style/design/foundations/icons/share-android-16"  target="_blank"><img class="option-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/share-android.svg" alt="share-android.svg" title="option-icon: share-android.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=Fuchsia" title="Fuchsia"><tag class="option-tag">OPTION</tag></a> | Highlights a chunk of code that is one among other alternatives |
<a href="https://primer.style/design/foundations/icons/pencil-16"  target="_blank"><img class="edit-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/images/pencil.svg" alt="pencil.svg" title="edit-icon: pencil.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=Purple" title="Purple"><tag class="edit-tag">EDIT</tag></a>  | Highlights the beginning of an editable chunk of code like a template's customizable area.  |

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
.atat-tag {
 color: rgb(255, 20, 147);
 background-color: none;
}
.atat-icon {
  filter: invert(27%) sepia(72%) saturate(6772%) hue-rotate(316deg) brightness(102%) contrast(101%);
}
.edit-tag {
 color: rgb(255, 255, 255);
 background-color: rgb(128,0,128);
}
.edit-icon {
  filter: invert(10%) sepia(93%) saturate(4953%) hue-rotate(294deg) brightness(86%) contrast(109%);
}
.option-tag {
 color: rgb(255, 0, 255);
 background-color: none;
}
.option-icon {
  filter: invert(17%) sepia(99%) saturate(3837%) hue-rotate(300deg) brightness(125%) contrast(125%);
}

</style>
<!-- markdownlint-enable MD041-->
