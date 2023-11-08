# Custom-Bootstrap-Template

This project offers a simple scaffolding to customize [Bootstrap's](https://getbootstrap.com/docs/5.3/getting-started/introduction/) SASS files.

It is based on [Parcel](https://parceljs.org/) for quick setup and packaging.

## Usage

1. Copy the source files to a new folder (or clone this repository)
2. Run `pnpm i` to install all dependencies
3. Run the `start` NPM Script from `package.json`
4. Customize Bootstrap using the `_custom-bootstrap.scss` (and any other associated scss items you'd like)
5. Use the `build` NPM script to pack and convert the `_custom-bootstrap.scss` into `_custom-bootstrap.css` under `dist/sass`
6. Your custom bootstrap theme is ready

## Tips

- Use the `dist/sass/_custom-bootstrap.css` file as a reference for the available Bootstrap variables.
- The `src/index.html` file is kind of a sandbox. You can use it to test your customizations by adding Bootstrap's components and classes to it.
