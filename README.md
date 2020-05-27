# EOS CRA template

This is EOS's template for [Create React App](https://github.com/facebook/create-react-app).

## Usage

```sh
npx create-react-app my-app --template eos
```


## This application contains the basic configuration from a create-react-app plus:

- @reach/router for routes
- Eslint to lint JS
- Prettier
- Sass-lint to lint sass, plus initial sass configured
- Git hooks to run sass and js linters before making a commit.
- Gitlab CI to test JS and SASS, and with Gitlab pages deployment configured.
- i18next: translations already configured in the project. To add new languages, simply add a new json file with the strings. More info at https://www.i18next.com/

### Contribute

Send a PR to this repo and explain the improvement/feature you are adding.
