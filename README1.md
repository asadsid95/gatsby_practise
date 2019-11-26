Installed gatsby-source-filesystem to allow working with data stored in filesystem to be queried.

Since using markdown, we also need gatsby-transformer-remark to allow transform data from .md file into HTML for rendering

we also want gatsby-plugin-catch-links to intercept links from .md files and non-react pages and does a client side push state to avoid browser to refresh the page

Once all these packages and plugins are installed, we edit gatsby.config.js file to add them

