# Minimal Light Hugo Theme

This is a Hugo port of the [Minimal Light Jekyll theme](https://github.com/yaoyao-liu/minimal-light).

## Features

- Simple and elegant personal homepage theme
- Hugo theme, can be hosted on any web server
- Basic search engine optimization
- Mobile friendly
- Light and dark mode
- Academically-oriented

## Directory Structure

```
.
├── archetypes/
├── assets/
├── layouts/
│   ├── _default/
│   └── partials/
├── static/
└── theme.toml
```

## Installation

1. Create a Hugo site if you haven't already:
```bash
hugo new site my-site
cd my-site
```

2. Add this theme as a Git submodule:
```bash
git submodule add https://github.com/your-username/minimal-light-hugo themes/minimal-light
```

3. Add the theme to your site's configuration:
```toml
theme = "minimal-light"
```

## Configuration

Here's an example configuration for your `config.toml`:

```toml
baseURL = "https://example.com"
languageCode = "en-us"
title = "Your Name"
theme = "minimal-light"

[params]
  position = "Ph.D. Student"
  affiliation = "Your Affiliation"
  email = "yourname (at) example.edu"
  # ... more options available in exampleSite/config.toml
```

For a complete example, please see the `exampleSite/config.toml` file.
