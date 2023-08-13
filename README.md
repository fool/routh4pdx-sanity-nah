## Overview

First draft website for the Routh4PDX 2024 campaign.  On the web at <https://routh4pdx.netlify.app>.  Contributions welcome/encouraged!

## Team members: contribute and preview without a local development environment

We are using Sanity, a "headless CMS", to manage most textual content on the site.  Want a quick and simple explanation of what this is?  [Check out this article](https://tinloof.com/blog/explain-like-im-five-headless-cms) that explains the concept.

[Netlify](https://www.netlify.com) is a collaborative webhosting service we use to preview and build our website.  You do not need a netlify account to preview nor build, but in case you think you need one to change project settings, contact [Chris "fool" McCraw](mailto:gently+routh4pdx@gmail.com).  Previews are generally available as https://routh4pdx.netlify.app or more specifically, find the appropriate unpublished build from https://app.netlify.com/sites/routh4pdx/deploys and click the small "Permalink" text near the top center-right.

## External contributors: Propose updates via the web

- you can propose changes on GitHub by [creating a pull request from a forked copy of this repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) .  The team will review as soon as possible and merge or request changes via GitHub.

## Local Development requirements

To develop locally (hopefully few people need this, since you can use Netlify to build/preview), you'll want to ensure that you have these installed:

- [Node.js v 18.17.1](https://nodejs.org/en) (probably any version `18.x` will do)
- [Sanity CMS command-line interface](https://www.sanity.io/docs/cli)
- [netlify CLI](https://github.com/netlify/cli) (probably any version `>=16.0.2` will do)
