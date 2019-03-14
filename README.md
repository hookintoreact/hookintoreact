<div align="center">
  <h3>Hook into React</h3>
  <img src="./hookintoreact.png">
  <sup></sup>
</div>

- 🍎 Handpicked hooks to learn from or copy/paste or experiment
- 💡 All code snippets are interactive
- 🎈 Copy snippets to clipboard with a click
- 💄 Prettify the snippets

<br/>

### 🏗 How do I add a new Hook function?

The hooks are documented using markdown in `public/docs` directory.

To add a new hook,

- Add a new markdown file under a folder.
  - Document the hook under `community` folder if the hook doesn't belong to a published npm module.
    > Refer `public/docs/template.md` for documentation guide
- Make a pull request

<br/>

### 🧡 Contribute

- Run `yarn install`
- Run `yarn start` to start the app in dev mode
- If you add a new markdown file, you have to go to `src/docs.js` file and just make a dummy change to trigger a webpack build. This runs the babel macro again.

<br/>

### 👩‍🎨 Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars2.githubusercontent.com/u/1308397?s=400&v=4" width="100px;"/><br /><sub><b>Bunlong</b></sub>](https://twitter.com/bunlongvan)<br /> |
| :---: |
