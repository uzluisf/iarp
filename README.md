# IARP

A Hugo theme without warranties.

> IARP is a fork of [Slick](https://github.com/spookey/slick) with far less improvements.

> Slick is a fork of [temple](https://github.com/aos/temple) with many improvements.

> Temple is a fork of [nofancy](https://github.com/gizak/nofancy) with many improvements.

## Installation

Just download the theme or clone it into your themes/ directory:

```
$ cd themes && git clone https://github.com/uzluisf/iarp.git
```

Then reference it in your config:

```
theme = "iarp"
```

Or when building the site, pass it in to the CLI:

```
$ hugo -t iarp
```

## Customization

```
baseUrl                = "/"           # Site's base url
title                  = "IARP"
theme                  = "iarp"
languageCode           = "en"
defaultContentLanguage = "en-us"
canonifyURLs           = true           
copyright              = "╰( ･ ᗜ ･ )╯"  # Footer text

# Configure pagination
Paginate     = 10
PaginatePath = "page"

[params]
    description     = "Notes website" # Site's description
    datefmt         = "02 Jan 2006"   # Custom date format
    showfullcontent = false           # Show full content

[author]
    name  = "Xyz Zyx"
    email = "xyz@abc.com"

# Define all supported taxonomies
[taxonomies]
    tags       = "tags"
    categories = "categories"

# Configure main menu entries (header)
[menu]
    [[menu.main]]
        identifier = "categories"
        name       = "Categories"
        url        = "/categories/"
        weight     = 1
    [[menu.main]]
        identifier = "tags"
        name       = "Tags"
        url        = "/tags/"
        weight     = 2
```

### Per-page config

MathJax support must be enabled per page. To enable it, include 
`include_math = true` in your page's front matter. Likewise, to include
Mermaid diagrams, include `include_mermaid = true` in your page's front matter.

To exclude a certain page on the front page, include `exclude_page = null`
in the page's front matter.

## Contribution

Don't submit features/issues/bugs. Instead, fork it and spawn a new and
improved one.

