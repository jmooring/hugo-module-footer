# Hugo Module &ndash; Footer

This is an example of a Hugo module that provides:

- A partial template to render a site footer
- Menu entries for a footer menu

## Structure

```text
config/
└── _default/
    ├── menus.toml
    └── params.toml
layouts/
└── partials/
    ├── footer.html
    └── menu.html
```

## Configuration

To add this module to your project, initialize your project as a Hugo module:

```text
hugo mod init foo
```

In the above, `foo` is typically something like `github.com/user/project`.

Then add this to your site configuration:

```text
[[module.imports]]
path = 'github.com/jmooring/hugo-module-footer'
```
