# Vite + Turborepo Mono-Repo Example

Setting up a nice development experience in a mono-repo can be really challenging, especially if you want to maintain clean boundaries between your packages. Turborepo can really help with this, though, allowing the development of your application to incorporate that of the shared packages that live alongside it.

This repo serves an example of using how to configure a clean development setup for your app, with full live-reload, _without_ your application having to handling building the shared packages. Additionally, it demonstrates all three "types" of internal packages that Turborepo defines; _compiled packages_, _just-in-time packages_ and _transit nodes_.

![VSCode running with an embedded terminal window, showing the Turborepo TUI output while developing a Vite application that also runs a build step for an internal package](./docs/vscode-dev-screenshot.png)

## The Problem
