# README

## About

This is the official Wails + Vue.js 3 + Vite template.

You can configure the project by editing `wails.json`. More information about the project settings can be found
here: https://wails.io/docs/reference/project-config

## Project Setup

You can setup the project by following this [instruction](https://wails.io/docs/gettingstarted/installation)

Or setting up step-by-step,

1. Install Go with this [link](https://go.dev/doc/install)
   - Check Go is install properly with `go version`
   - Plase make sure "~/go/bin" is in your PATH environmental variable
2. Install wails: `go install github.com/wailsapp/wails/v2/cmd/wails@latest`
   - Perform Wails system check `wails doctor`
4. Install dependancies: `npm install`

## Live Development

To run in live development mode, run `wails dev` in the project directory. This will run a Vite development
server that will provide very fast hot reload of your frontend changes. If you want to develop in a browser
and have access to your Go methods, there is also a dev server that runs on http://localhost:34115. Connect
to this in your browser, and you can call your Go code from devtools.

## Building

To build a redistributable, production mode package, use `wails build`.
