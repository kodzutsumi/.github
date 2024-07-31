<div align="center">

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=flat-square)][contributing]
[![@kz JSR homepage](https://jsr.io/badges/@kz)][jsr]

<div>
<img alt="kz logo" height="48" src="https://raw.githubusercontent.com/i11n/.github/main/svg/kz/color/kz.svg" />

</div>
<p>
kz is an easy-to-use utility and feature library for creating anything you want with the <a href="https://deno.com">Deno</a> runtime.
</p>
</div>

# About this project

With the shiftng of the development landscape over the past 20 years, integereleven has built a lot of things in a lot of different environments. With codebases in different languages for different runtimes, it is challenging to keep everything up-to-date, compatible, and secure.

When we started playing with [Deno][deno], we immediately loved it. Deno's zero-trust approach in securing the runtime and not having to worry about builds working expectedly were huge selling points for us. 

So we started building things in Deno. Great! We just added something else we need to maintain!

Recently, it was decided to focus our development efforts in Deno. If we can build it in Deno, we will. To do this, we decided to migrate all of our customer's applications and other developed solutions to the Deno runtime. We'd build patches for the time being, but once an application's Deno replacement is built, we will release the updated version to the customer as a free upgrade.

Codebases from the past are beig reviewed, and necessary features ported over to Deno as the kz library.

This library will continue to grow, so integereleven's development and release cycle is fairly active.

# Contributing

Contributions are welcome! Review a repository's README.md to get started.

# Modules

These are the publicly released modules. As integereleven reviews its codebases, these modules will only provide more functionality. 

## common-types [![common-types latest version](https://jsr.io/badges/@kz/common-types)][common-types-jsr]

A collection of the most common types used across kz packages, adapted for API consistency and case-coverage, exhaustively tested, and documented thoroughly.

[GitHub][common-types-gh] &middot; [API Docs][common-types-jsr]

## common-exceptions [![common-exceptions latest version](https://jsr.io/badges/@kz/common-exceptions)][common-exceptions-jsr]

A collection of the most common exceptions used across kz packages, adapted for API consistency and case-coverage, exhaustively tested, and documented thoroughly.

[GitHub][common-exceptions-gh] &middot; [API Docs][common-exceptions-jsr]

## dispose [![dispose latest version](https://jsr.io/badges/@kz/dispose)][dispose-jsr]

A collection of types and features for using and disposing of managed resources.

[GitHub][dispose-gh] &middot; [API Docs][dispose-jsr]

## observe [![observe latest version](https://jsr.io/badges/@kz/observe)][observe-jsr]

A collection of types and features for implementing the observer pattern.

[GitHub][observe-gh] &middot; [API Docs][observe-jsr]

## pubsub [![pubsub latest version](https://jsr.io/badges/@kz/pubsub)][pubsub-jsr]

A collection of types and features for implementing the publisher/subscriber pattern.

[GitHub][pubsub-gh] &middot; [API Docs][pubsub-jsr]

## mediator [![mediator latest version](https://jsr.io/badges/@kz/mediator)][mediator-jsr]

A collection of types and features for implementing the mediator pattern.

[GitHub][mediator-gh] &middot; [API Docs][mediator-jsr]

## warn [![warn latest version](https://jsr.io/badges/@kz/warn)][warn-jsr]

A collection of utilities and warnings for tracking of application issues.

[GitHub][warn-gh] &middot; [API Docs][warn-jsr]

<!--
# Roadmap

These are the modules expected to be released. These are based off preliminary review of the codebases in an attempt to determine module organization of the kz library. These are fairly set in stone, but may change.

- [ ] utils - Basic common utilities for native JavaScript features.
- [ ] regexp - RegExp building and curated regular expressions.
- [ ] date - Utilities and types for working with dates and time.
- [ ] text - Utilities for working with textual data.
- [ ] numerics - Utilities for workgin with numeric values.
- [ ] calc - Advanced maths and calculations.
- [ ] debug - Utilities for debugging applications.
- [ ] log - Utilities for logging.
  * Will by default have the most common logging providers in the module.
  * Field developed vendor specific adapters will be `log-*`.
- [ ] collections - A collection of enumerable and iterable features.
- [ ] net - Utilities and types targeting networking features.
- [ ] app - Utilities for building apps
  * Will by default have the most common apps (HTTP, SMTP, etc...) in the module.
  * Field developed vendor specific adapters will be `app-*`.
- [ ] fs - Utilities for working with file systems and file system-like services.
  * Will by default have the most common file systems in the module.
  * Field developed vendor specific adapters will be `fs-*`.
- [ ] data - Utilities for working with data, such as SQL, NoSQL, etc...
  * Will by default have the most common provider in the module.
  * Field developed vendor specific adapters will be `data-*`.
- [ ] i18n - Translation features.
- [ ] l10n - Localization features.
- [ ] service - Utilities for managing apps
- [ ] system - Utilities for working with operating system functions.
- [ ] testing - Utilities for testing.

-->
---

<div align="center">
<img
  alt="@kz logo"
  height="48"
  src="https://raw.githubusercontent.com/i11n/.github/main/svg/brand/color/open-stroke.svg"
/>
</div>

<!---- Markdown Links -->
[deno]: https://deno.com "Deno: The next-generation JavaScript runtime"
[jsr]: https://jsr.io/@kz "@kz JSR homepage"
[contributing]: https://github.com/kz-io/mod-name/blob/main/CONTRIBUTING.md "@kz/mod-name contributing guidelines"

<!-- common-types -->
[common-types-gh]: https://github.com/kz-io/common-types "@kz/common-types GitHub"
[common-types-jsr]: https://jsr.io/@kz/common-types "@kz/common-types JSR"

<!-- common-exceptions -->
[common-exceptions-gh]: https://github.com/kz-io/common-exceptions "@kz/common-exceptions GitHub"
[common-exceptions-jsr]: https://jsr.io/@kz/common-exceptions "@kz/common-exceptions JSR"

<!-- dispose -->
[dispose-gh]: https://github.com/kz-io/dispose "@kz/dispose GitHub"
[dispose-jsr]: https://jsr.io/@kz/dispose "@kz/dispose JSR"

<!-- observe -->
[observe-gh]: https://github.com/kz-io/observe "@kz/observe GitHub"
[observe-jsr]: https://jsr.io/@kz/observe "@kz/observe JSR"

<!-- pubsub -->
[pubsub-gh]: https://github.com/kz-io/pubsub "@kz/pubsub GitHub"
[pubsub-jsr]: https://jsr.io/@kz/pubsub "@kz/pubsub JSR"

<!-- mediator -->
[mediator-gh]: https://github.com/kz-io/mediator "@kz/mediator GitHub"
[mediator-jsr]: https://jsr.io/@kz/mediator "@kz/mediator JSR"

<!-- warn -->
[warn-gh]: https://github.com/kz-io/warn "@kz/warn GitHub"
[warn-jsr]: https://jsr.io/@kz/warn "@kz/warn JSR"

[1-gh]: https://github.com/kz-io/common-exceptions "@kz/common-exceptions GitHub"
[1-jsr]: https://jsr.io/@kz/common-exceptions "@kz/common-exceptions JSR"
[2-gh]: https://github.com/kz-io/dispose "@kz/dispose GitHub"
[2-jsr]: https://jsr.io/@kz/dispose "@kz/dispose JSR"
[3-gh]: https://github.com/kz-io/observe "@kz/observe GitHub"
[3-jsr]: https://jsr.io/@kz/observe "@kz/observe JSR"
[4-gh]: https://github.com/kz-io/warn "@kz/warn GitHub"
[4-jsr]: https://jsr.io/@kz/warn "@kz/warn JSR"
