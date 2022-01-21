# cypress-multiple-register

Demonstration of an issue for a feature request

tl;dr – when launching a browser it would be nice if Cypress ran both functions for `before:browser:launch`, printing `👋 Hello, World! 🌍`

## Why do you need this?

I use a [third-party plugin](https://github.com/meinaart/cypress-plugin-snapshots) that registers `before:browser:launch`. However, I would also like to add my own config on this event. Given the current state of Cypress (or the plugin, depending on your ideal solution I suppose), I'm not allowed to do that without some kind of hacky workaround.
