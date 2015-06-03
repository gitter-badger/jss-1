# Introduction

## Rational

JSS has these three benefits:

1. First-class feed parsing in all major languages.
2. Native javascript objects for interoperability with front-end frameworks.
3. Reduction in file size for feeds.

### First-class feed parsing in all major languages

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Native javascript objects for interoperability with front-end frameworks.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Reduction in file size for feeds.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Examples

### Simple, single-entry

```javascript
// jss.json
{
  jss: {
    revision: 1.0,                        // JSS version
    link: "http://ptrckbrwn.com/jss"     // JSS website
  },
  feed: {
    title: "xkcd.com",                   // Title of content
    link: "http://xkcd.com/",            // Link to homepage of content
    id: "http://xkcd.com/",              // Unique ID of content
    updated: "2015-05-27T00:00:00Z",     // Datetime of when content was last updated
    entries: [{
      title: "Keyboard Mash",            // Entry title
      link: "http://xkcd.com/1530/",     // Link to entry
      updated: "2015-05-27T00:00:00Z",   // Date entry was last updated
      published: "2015-05-27T00:00:00Z", // Date entry was published
      id: "http://xkcd.com/1530/",       // Unique ID for entry
      authors: [{
        name: "Randall Monroe",          // Author name
        link: "http://xkcd.com/",        // Author's homepage
        email: "randall@xkcd.com"        // Author's email
      }],
      summary: "A Brief Summary...",     // Summary of content
      content: "The Full Article..."     // Full content
    }]
  }
}
```
