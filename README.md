# npm module template

- 👩‍💻Focus on the logic. Don't waste your time setting up environment!
- ✍️Write code like it's 2020 using ES6 syntax. The code will be transpiled and minified before deployment.
- 🛠Test: use Jest to cover your module with unit tests.

Сomplies with GitHub best practices:

- 🔑`LICENSE` describes the license agreement. This template uses MIT license
- 📁`.editorconfig` sets up code style rules across all popular code redactors
- ⚖️`.gitignore` and `.npmignore`: splits up the code into 2 chunks: sources will be uploaded to github, transpiled and minified files - to `npm`
- 🔬`.eslintrc` lists eslint settings
- 🏭`.babelrc` describes ES6->ES5 rules

# Usage

Create your own module in 3 simple steps:

1. Press "Use this template" button and type a name of your new module

2. Add some fancy logic to `src` folder and run `yarn build`

3. Publish your module `npm publish`
