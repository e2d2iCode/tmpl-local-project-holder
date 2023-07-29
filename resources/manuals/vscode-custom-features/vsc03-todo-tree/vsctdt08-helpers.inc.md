<!-- markdownlint-disable MD041-->
Tags which are used to hold information about the project that is central enough to its development
that it is worth using the tree to keep track of them. In the same aim, tags from this category may
also be used to bookmark locations in the project that are of particular interest and, thus, need to be
accessed frequently and/or simply as a reminder for some easily forgettable action that is important
to be taken. These tags' lifetime typically spans over the whole development and has no impact on
whether the project can be released or not. As a consequence, the extension should be configured
to hide this category's tags whenever generating the tree from the release or the deployment
environment.

<div class="tag-table helpers">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;TAG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
:-----:|:----|:----|
<a href="https://primer.style/design/foundations/icons/link-16"  target="_blank"><img class="link-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/icons/octicons/link.svg" alt="link.svg" title="link-icon: link.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=LightSkyBlue" title="LightSkyBlue"><tag class="link-tag">LINK</tag></a> | Serves as shortcut to an editable region within, typically, templates |
<a href="https://primer.style/design/foundations/icons/info-16"  target="_blank"><img class="note-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/icons/octicons/info.svg" alt="info.svg" title="note-icon: info.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=MediumPurple" title="MediumPurple"><tag class="note-tag">NOTE</tag></a>  | A general note or comment calling for no action of any kind     |
<a href="https://primer.style/design/foundations/icons/info-16"  target="_blank"><img class="caution-icon" src="/resources/manuals/vscode-custom-features/vsc03-todo-tree/assets/icons/octicons/alert.svg" alt="flame.svg" title="note-icon: alert.svg"/></a>| &nbsp;<a href="https://www.w3schools.com/colors/color_tryit.asp?color=Indigo" title="Indigo"><tag class="caution-tag">CAUTION</tag></a>  | A general note or comment calling for no action of any kind     |

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
.caution-tag {
 color: rgb(218, 112, 214);
 background-color: none;
}
.caution-icon {
  filter: invert(58%) sepia(9%) saturate(6697%) hue-rotate(279deg) brightness(110%) contrast(71%);
}
.link-tag {
 color: rgb(135, 206, 250);
 background-color: none;
}
.link-icon {
  filter: invert(74%) sepia(26%) saturate(1056%) hue-rotate(177deg) brightness(104%) contrast(96%);
}

.note-tag {
 color: rgb(147, 112, 219);
 background-color: none;
}
.note-icon {
  filter: invert(69%) sepia(31%) saturate(7437%) hue-rotate(219deg) brightness(86%) contrast(99%);
}

</style>
<!-- markdownlint-enable MD041-->