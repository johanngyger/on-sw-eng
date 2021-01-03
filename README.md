# Presentation about software engineering in the cloud era

This repo hosts the Markdown source of my presentation "On Software Engineering".

The presentation is built using the static page generator [Hugo](https://gohugo.io/).
The Hugo theme [reveal-hugo](https://themes.gohugo.io/reveal-hugo/) is used to turn it into an HTML presentation with [reveal.js](https://revealjs.com/).

## Rendering

After cloning the main repo, you need to initialize the Git submodule:

```shell
git submodule update --init --recursive
```

After that, run this command:

```shell
hugo server
```


## Maintenance

Run the following command to update all submodules with their newest upstream version:

```bash
git submodule update --remote
```


