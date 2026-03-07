# Phugo

### Pablo's theme

Simple Hugo Theme that I use in my own webpage [pabloquiros.click](https://pabloquiros.click)


I have a private repository for my webpage, built with Hugo. When I make some changes and push to main, the web is updated in my server with a Github Actions workflow. Once the web is updated, the second to last step of the workflow checks if the following files or folders have been modified:

'
THEME_DIRS: "archetypes assets i18n layouts themes"
THEME_FILES: "hugo.toml theme.toml"
'

If so, the last step of the workflow executes, and bring that changes to this repository.
