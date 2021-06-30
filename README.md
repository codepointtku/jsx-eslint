# Codepoint's tsx/jsx ESLint config

[![npm Release Version](https://img.shields.io/github/v/release/codepointtku/jsx-eslint?logo=npm&style=for-the-badge&labelColor=333333)](https://www.npmjs.com/package/@codepointtku/jsx-eslint)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/codepointtku/jsx-eslint/npm%20Publish?logo=githubactions&logoColor=cyan&style=for-the-badge&labelColor=333333)](https://github.com/codepointtku/jsx-eslint/actions/workflows/npm-publish.yml)

*Codepoint's ESLint config file for making code more consistent and avoiding bugs.*

* **What is this for?:** This ESLint config is meant to be used for Codepoint's web development projects.
* **Can anyone use it?:** Yes, you can use this config however you like, but keep in mind that these settings might change over time.

[Contact for questions, information and to contribute](mailto:juuso.laakso@turku.fi)

## Installation
**Run** this command in your repository
```bash
$ npm install @codepointtku/eslint-config-jsx-eslint --save-dev
```

## Usage
**Add** this line to your `.eslintrc`
```jsonc
{
  "extends": "@codepointtku/jsx-eslint"
}
```

or to `package.json`
```jsonc
{
  "eslintConfig": {
    "extends": [
    "@codepointtku/jsx-eslint"
    ]
  }
}
```
