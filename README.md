# ☕ Coffee Theme for Hugo

## TODO

This is a new theme, bear with me.

- [ ] Screenshots
- [ ] Example Site

# Quick start

## 1. Get the theme

Run from the root of your Hugo site:

```sh
$ git clone https://github.com/coffee-cup/coffee.git themes/coffee
```

Alternatively you can include this repository as a [git
submodule](https://git-scm.com/book/de/v1/Git-Tools-Submodule). This makes it
easier to update this theme if you have your Hugo site in git as well. For this
you need to run:

```sh
$ git submodule add https://github.com/coffee-cup/coffee.git.git themes/coffee
```

## 2. Configure your site

From the exampleSite, copy `config.toml` to the root folder of your Hugo site
and change the fields as you like. There are helpful hints in the file.

## 3. Create pages

Run:

```sh
$ hugo new page.md
```

Where `page` can be anything you like. A contact page, a bio, dates for your
upcoming world tour... Anything!

## 4. Design your main menu and index page

In `config.toml`, customize the entries for `[[menu.main]]`. This changes the
navigation buttons in the header.

```
[[menu.main]]
    name = "About"
    url = "/about"
    weight = 1

[[menu.main]]
    name = "Contact"
    url = "/contact"
    weight = 2

[params]
    description = "An audio fingerprinting project."
    footer = "Project by [Jake Runzer](https://jakerunzer.com)"
```

## Preview your site locally

Use Hugo's built-in server to see your site in action as you make changes.

```sh
$ hugo serve -t sam
```

Visit `localhost:1313` in your browser to see a live preview of your site.

## Posts

To create a new post, run:

```sh
$ hugo new posts/your-post-title.md
```

# Editing the theme

_TODO_

# Contributing

Pull requests for bug fixes and enhancements are welcome.

# License

MIT
