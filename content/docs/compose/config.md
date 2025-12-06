+++
title = "Configuration"
weight = 4
+++

This theme is primarily meant for documentation. You can customize the configuration under `exampleSite/config/_default`. 

For example, in `params.toml`, you can set:
- Site title,logo
- copyright info
- search options
- time format
- source code display options

other config files include:
- `menus.toml` for navigation menus
- `languages.toml` for multilingual support
- `hugo.toml` for Hugo framework settings

currently, the directory structure under `content/` is as follows:
```
content
├── blog
├── docs
│   └── compose
└── tutorials
    └── example
```

#### Documentation

By default, the theme will look for all your documentation content within the `docs` directory.

However, if you would like to have your docs content across multiple directories, please list those directories inside `config/_default/params.toml` under `docSections` like so:

```toml
docSections = ["docs", "tutorials"]
```

Unlike other regular pages, the documentation pages will have a left sidebar. This sidebar will list links to all the pages in the documentation pages. Beneath each link, there will be a collapsible list of __table of contents'__ links. These nested lists will unfold automatically on the active/current page.

#### Home Page

At the root level there's an `_index.md` page which is the homepage. Feel free to edit it as you like.

