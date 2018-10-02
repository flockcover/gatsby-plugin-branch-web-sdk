# gatsby-plugin-branch-web-sdk

A [Gatsby](https://www.gatsbyjs.org) plugin for the [Branch IO Web SDK](https://docs.branch.io/pages/web/integrate/).

[![npm (scoped)](https://img.shields.io/npm/v/@flockcover/gatsby-plugin-branch-web-sdk.svg?style=flat-square)](https://www.npmjs.com/package/@flockcover/gatsby-plugin-branch-web-sdk)

## Install

```shell
$ npm install --save @flockcover/gatsby-plugin-branch-web-sdk]
```

## Usage

In your `gatsby-config.js`, add:

```js
module.exports = {
  plugins: [
    // your other plugins...
    {
      resolve: '@flockcover/gatsby-plugin-branch-web-sdk',
      options: {
        prodBranchKey: 'Your Live Branch Key',
        devBranchKey: 'Your Test Branch Key'
      }
    }
  ]
}
```

## License

MIT
