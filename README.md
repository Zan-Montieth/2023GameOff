# Game Off 2023

## Standards
Standard for our project. A living document as this will be our largest Godot project.

__TODO__ https://new.pythonforengineers.com/blog/how-to-structure-your-godot-project-so-you-dont-get-confused/

### Naming

Style guide

For consistency across projects, we recommend following these guidelines:

    Use snake_case for folder and file names (with the exception of C# scripts). This sidesteps case sensitivity issues that can crop up after exporting a project on Windows. C# scripts are an exception to this rule, as the convention is to name them after the class name which should be in PascalCase.

    Use PascalCase for node names, as this matches built-in node casing.

    In general, keep third-party resources in a top-level addons/ folder, even if they aren't editor plugins. This makes it easier to track which files are third-party. There are some exceptions to this rule; for instance, if you use third-party game assets for a character, it makes more sense to include them within the same folder as the character scenes and scripts.




### Folders
```
root/
├─ assets/
|   ├─ characters/
|   ├─ gui/
├─ levels/
```

References:

[GD Quest Open RPG](https://github.com/gdquest-demos/godot-open-rpg)

[GD Quest Website with examples](https://gdquest.gitbook.io/gdquests-guidelines/godot-gdscript-guidelines)

[Godot Docs](https://docs.godotengine.org/en/stable/tutorials/best_practices/project_organization.html)
