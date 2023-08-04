<!-- markdownlint-disable  MD041 -->
*VSCode* configuration happens at three levels: `User`, `Workspace`, and `Folder`, which override
each other in that order. The `Settings Panel` of the editor lets the user choose the level to edit and
updates the corresponding file:

- **User settings** are (typically) defined in the file `settings.json` located in the `.vscode` folder of
   the *user's home directory*. They then apply globally to all *VSCode* instances with the lowest
   priority. Note that the *user's settings* themsselves branch into two categories:

  - **Global settings** are defined in the file `settings.json` located in the `.vscode` folder of the
         *user's home directory*. They apply to all *VSCode* instances with the lowest priority.

  - **Profile settings** can be defined only if a *profile* different from the default one is used and apply only when that profile is active. In that case, they override the *global settings*. Switching from one profile to another is done by clicking on the profile's name in the bottom-left corner of the *VSCode*'s window. The same interface is also used to create, edit, and delete profiles.

- **Workspace settings** lie in the `.code-workspace`  that *VSCode* creates when choosing to
  [save a workspace][workspace-link]. These settings then apply to the opened workspace,
  overriding the *user's settings* but not the *folder's settings*.

- **Folder settings** are in the file `settings.json` located in the `.vscode` folder of the selected
`<root-folder>`. They apply, with the highest priority, to the whole contents of the enclosing folder.

Going through *VSCode*'s `Settings Panel` is not the only way to configure the editor. An alternative
consists in modifying the corresponding `json` files directly. That second method is much faster and,
in certain cases, gives access to more options than the graphical interface of the setting panel does.
However, it requires a good knowledge of the available settings and/or intensive use of the
documentation.

[workspace-link]: <https://code.visualstudio.com/docs/editor/workspaces>
<!-- markdownlint-enable MD041 -->
