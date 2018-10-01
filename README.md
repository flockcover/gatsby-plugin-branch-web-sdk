# gatsby-plugin-branch-web-sdk

A [Gatsby](https://www.gatsbyjs.org) plugin for [Segment](https://docs.branch.io/pages/web/integrate/).

## Usage

In your `gatsby-config.js`, add:

```js
module.exports = {
  plugins: [
    // your other plugins...
    {
      resolve: 'gatsby-plugin-branch-web-sdk',
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
