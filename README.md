 # Insert date and time in metadata automatically on file creation event
 
 Obsidian plugin allowing to insert the current date and time in YAML frontmatter on file creation (which is otherwise not possible). 
 
 If you use the [Templater](https://github.com/SilentVoid13/Templater) plugin and you create a new note based on a template which happens to include a YAML frontmatter, the plugin updates the frontmatter automatically.
 
 - But how does it differ from using templates?

Templates are cool when you want to create a new file with a keyboard shortcut, but when you create a new file from a markdown link, it doesn't work, and that's where my plugin comes in.

## Demo

See how the date is inserted even after link-based-file-creation.

![moi](https://user-images.githubusercontent.com/105465034/168185897-17e87af8-9d33-4fc9-8164-04de5e1a8883.gif)

## Settings

Of course you can customize your frontmatter

![image](https://user-images.githubusercontent.com/105465034/168187197-8e6541a0-8547-4594-bf22-56fca6ae886b.png)


## Plugin

This plugin uses

- [JS Yaml](https://github.com/nodeca/js-yaml)
- [Front-matter](https://www.npmjs.com/package/front-matter)
