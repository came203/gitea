# ISD HPC Cluster Website

Webroot: `/var/www/html` on the headnode (simple `webfs` server)

## Landing Page (index.md)

This very simple landing is meant for general info and to redirect users to the Wiki (on Gitea) and the Dashboard.

Use a Markdown to HTML converter to generate a html page, e.g.

```bash
brew install grip
grip index.md --export --title="ISD HPC Cluster"
```

Tweak the resulting index.html:

* Heading: `<h3 style="font-size:16px;">`