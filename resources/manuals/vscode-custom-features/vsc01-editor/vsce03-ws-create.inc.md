
<!-- markdownlint-disable MD033 MD041 -->
Creating a `workspace` is as simple as opening a folder or a set of folders in the editor. Once
opened, *VSCode* will automatically keep track of its state, which includes the last used layout.
*VSCode* saves the configuration of `single-root` workspaces in a folder named `.vscode` in the
workspace root directory. It does in a `<the-project-name``>.code-workspace` file for `multi-root`
workspaces; that file may lie wherever convenient, including a remote location.

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">
<div style="font-size: 95%; text-align: justify;">

!!! note
    The syntax used by *VSCode* in the case of a `single-root workspace` lacks consistency. Indeed,
    until a `.code-workspace` file exists, the `Settings Panel` labels `User` and *Workspace* as the
    available configuration levels. Then, it surprisingly saves the preferences within a
    `.vscode/settings.json` file, although such location should be home to nothing else than
    *folder level settings*! This inconsistency is enhanced when defining and saving some
    preferences **first** and creating a `.code-workspace` **later**.

     One would expect the *workspace* configuration to be available in the `Workspace` tab of the
     editor's *Settings Panel*, but they are not. Instead, they now considered a `Folder` configuration.
     Such behavior makes sense when considering the saving location but makes none when
     focusing on the editor's UI. Everything happens as if the UI changed the nature of the settings.

</div>
</div>

It is worth pointing out that multiple versions of a `.code-workspace` file can coexist, which allows
one to save different configurations of the same workspace and switch between them easily.
<!-- markdownlint-enable MD033 MD041 -->
