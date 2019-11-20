# Jelly Kat Studio

This is the static page website for Jelly Kat Studio, served at: https://jellykat.studio

This is just a static HTML website. It uses no bundled Javascript, and has no package manager.

It utilises only https://bulma.io as a lightweight CSS framework

## Development

No dependencies required. Pull the repo and make the desired changes.

For CSS style references, see here: https://bulma.io/documentation/

### Serving locally

Since there are assets that need to be loaded with the page, we can't just open the HTML file in our browser, to run locally, do the following:

1. Ensure `python` is installed
   - On OS X run: `brew install python`
   - On Windows go [here](https://www.python.org/downloads/) and download and install python for Windows, following the instructions
2. Open a terminal session in this folder
3. Run `make run_dev`
