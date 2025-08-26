# My Bundle config

	brew bundle

## Postgres

Start Postgres

	brew services start postgresql

Create super user for postgres

	createuser --superuser postgres

Connect to postgres

	psql -Upostgres

## My bash config

	eval "$(starship init bash)"

	# Secrets
	[ -f ~/.secrets ] && source ~/.secrets

## Backup Homebrew file
 
Backup the Brewfil

	brew bundle dump --file=Brewfile

## My notes for sublime text 4

**Plugins**

- [Elixir Syntax](https://github.com/elixir-editors/elixir-sublime-syntax)
- [Icons](https://packagecontrol.io/packages/FileIcons%20Mono)
- [LSP](https://github.com/sublimelsp/LSP-elixir)

**How to see the list of fonts**

    fc-list : family | grep -i jetbrains

**User Settings**

First open the command promnt with`CTRL+SHIGT+p`, them find `Preferences: Settings`

```json
{
    "ignored_packages":
    [
        "Vintage",
    ],
    "font_size": 14,
    "font_face": "JetBrainsMono Nerd Font",
    "index_files": true,
    "neovintageous_build_version": 13200,
    "theme": "Adaptive.sublime-theme",
    "dont_index_ignored_git_files": true,
    "goto_anything_exclude_gitignore": true,
    "browser": "firefox",
    "sidebar_on_right": true,
    "color_scheme": "auto",
    "dark_color_scheme": "Mariana.sublime-color-scheme",
    "light_color_scheme": "Celeste.sublime-color-scheme",
}

```
