# electron-sveltekit-template
<div align="center">
  A template project to get you started with using SvelteKit and Electron together.
</div>
<br />
<div align="center">
  <img alt="Electron and SvelteKit, together." src="https://i.imgur.com/KdbGQjB.png" width="auto" height="506" />
</div>


## Install and use

```bash
# Clone the repo
$ git clone https://github.com/e3ndr/electron-sveltekit-template.git

$ cd electron-sveltekit-template

# Install dependencies
$ npm install

# Run the app
$ npm run dev

# Package the app
$ npm run package
```

### Using GitHub templates
Alternatively, you can click "Use this template" at the top of the page to initialize a new repository with this code already commited.


## Packages used
`electron`, `babel` `sapper`, `electron-serve`, `wait-on`, `concurrently`


## main.cjs
Due to SvelteKit's requirement of `"type": "module"` in the `package.json` the only work around was to rename the main.js file's extension to `.cjs` (common-js, which is the normal `require()` syntax you're likely used to).