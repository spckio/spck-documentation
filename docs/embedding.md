# Embedding Spck Editor

One of the features that make [Spck Editor](https://spck.io) unique is the ability to [embed](https://github.com/spckio/spck-embed) the code editor on your very own site.

If you have a demo that requires a fully featured, interactive, code editor with a proper virtual file system and previewing support, then look no further.

## Setup

The details of doing this is covered on the Github page. But a quick summary:

1. Download the `spck-embed` library from `npm` or `bower` package manager.
2. Add an iframe to your site linking to `https://embed.spck.io`.
3. Control the editor using the APIs provided by the library.

## Use Cases

Some use cases planned in the roadmap for this feature are:

1. Editor tools: like HTML cleaners, converters, validators, previewers for new languages. (Vue file support maybe?).
2. Teaching, create code demos that can be interacted with.
3. Step-by-step tutorials using a live editor.

These are just some examples of possible uses, although additional features may be required to fulfill them.

## Issues

Please raise an issue on the [Github page](https://github.com/spckio/spck-embed/issues) if you have an issue, request or suggestion with the embedded code editor.

## Demo

Below are some sites already using the embedded code editor:

1. [Indent.js](https://zebzhao.github.io/indent.js/)
2. [Angular-Query-Builder](https://zebzhao.github.io/Angular-QueryBuilder/editor/)

If you have a project using the embedded code editor, we love to hear about it. Leave us a note by email, or through Github if you want to include it on this page.

<iframe src="https://embed.spck.io/" frameBorder="0" width="450" height="360"></iframe>