# Etchv documentation

The source for [etchv.com/docs](https://etchv.com/docs).

Documentation is written in MDX. `docs.json` defines the navigation, page titles,
descriptions, and URL slugs. Each `file` is relative to `content/`; an empty slug
is the overview at `/docs`.

## Writing docs

Use Markdown headings starting at `##` (the website supplies the page title),
fenced code blocks with language labels, links, and tables. Links to other docs
use their complete site path, such as `/docs/quickstart`.

The website also provides these MDX components:

```mdx
<Endpoint method="POST" path="/watermarks/images" />

<Callout title="Keep the PNG unchanged">
  Write the returned bytes directly to disk.
</Callout>

<Cards>
  <Card href="/docs/quickstart" title="Quickstart">
    Make your first API request.
  </Card>
</Cards>
```

The website owns rendering, shared typography, colors, and components. This
repository contains only documentation content and navigation, not application
code. Search is not included.

## Contributions

Open an issue or pull request here to suggest an improvement. Maintainers review
and incorporate accepted changes into Etchv's development source before publishing
a new snapshot and deploying the website. Public changes are not automatically
executed or imported by the website. Never include credentials or customer data.
