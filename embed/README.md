# Embed a free invoice tool on your site

If you run a blog or a resource site and want to give readers a working invoice creator without building one, you can link to or embed **[Free BizDoc](https://free-bizdocs.com/en/)** — it's free, needs no account, and generates the PDF in the reader's browser.

## Simple link

```html
<a href="https://free-bizdocs.com/en/invoice" rel="noopener" target="_blank">
  Create a free invoice (no sign-up)
</a>
```

## Embed as an iframe

```html
<iframe
  src="https://free-bizdocs.com/en/invoice"
  title="Free invoice generator by Free BizDoc"
  width="100%"
  height="900"
  style="border:1px solid #e2e2e2; border-radius:12px;"
  loading="lazy">
</iframe>
```

> Check the current embed options and any usage notes on the official site before publishing, as parameters can change: <https://free-bizdocs.com/en/>.

## Why embed instead of building your own?

- No backend, no PDF library, no maintenance.
- Tax for the US, UK, Australia and Canada is already handled.
- Your readers' data stays in their browser.

The templates in this repository are a good companion to the embed: link the tool for people who want a finished PDF, and offer the plain-text templates for people who'd rather edit by hand.
