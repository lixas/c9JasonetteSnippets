
This is snippets file plugin for Jasonette apps development

# Install

Download files
> git clone https://github.com/lixas/c9JasonetteSnippets.git

Create directory for plugin and copy files
> mkdir ~/.c9/plugins/c9JasonetteSnippets

> cp -ur * ~/.c9/plugins/c9JasonetteSnippets

Go to menu Coud9 -> Open Your Init Script

```
services.pluginManager.loadPackage([
    "~/.c9/plugins/c9JasonetteSnippets/package.json"
])
```

Restart workspace and restart browser screen

Go to menu `Cloud9 -> Preferences -> Plugin Explorer` and check if plugin is successfuly installed and enabled (checkbox is checked) in `Localy installed plugins` `c9JasonetteSnippets`
