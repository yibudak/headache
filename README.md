# Headache

> An easy-to-swallow painkiller plugin for WordPress.

The plugin removes a lot of default WordPress stuff you just can't wait to get rid of. It removes meta tags such as feeds, version numbers and emojis.

[![Build Status](https://badgen.net/github/checks/vinkla/headache?label=build&icon=github)](https://github.com/vinkla/headache/actions)
[![Monthly Downloads](https://badgen.net/packagist/dm/vinkla/headache)](https://packagist.org/packages/vinkla/headache/stats)
[![Latest Version](https://badgen.net/packagist/v/vinkla/headache)](https://packagist.org/packages/vinkla/headache)

## Installation

Require the package, with Composer, in the root directory of your project.

```sh
composer require vinkla/headache
```

Then login to the WordPress administrator dashboard and active the plugin.

## Features

All features are activated by default when the plugin is activated.

- Disable default users API endpoints for security
- Disable XML RPC for security
- Disables comments
- Disables comments feeds
- Disables feeds
- Disabled attachment media pages
- Removes contributor, subscriber and author roles
- Removes Gutenberg's front-end block styles
- Removes Gutenberg's global styles
- Removes Gutenberg's SVG filters
- Removes ?ver= query from styles and scripts
- Removes all extra RSS feed links
- Removes emojis
- Removes generated icons
- Removes JPEG compression
- Removes language dropdown on login screen
- Removes meta rel=dns-prefetch href=//s.w.org
- Removes oEmbeds
- Removes Really Simple Discovery link
- Removes relational links for the posts
- Removes REST API link tag from `<head>` and HTML headers
- Removes RSS feed links
- Removes shortlink tag from `<head>` and HTML headers
- Removes wlwmanifest.xml
- Removes WordPress version
- Update login page image link URL
- Update login page link title
