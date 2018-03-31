# Interoperable Design System API (IDSAPI)
The goal of this project is to build an API for being able to seamlessly switch from one design system to another

https://twitter.com/joeseifi/status/979898260142739457

We are starting to see really advanced design systems being built on top of React and CSS-in-JS libraries. This is great for now but as the number of publicly available Design Systems grow, we will end up with a large set of design systems that are not interoperable. Meaning the cost of moving from one to the other will be too high due to the lack of a shared specification.

The goal of this project is to build a common API, similar to the HTML spec, for UI components, to be adopeted by Design Systems. Each system would implement their component internals, and only expose a common IDSAPI to consumers.


# List of Existing Design Systems using React
A case study to see if this is feasible by surveying a list of existing DS's
- https://github.com/auth0/cosmos
- https://github.com/seek-oss/seek-style-guide

# Insipiration
- https://github.com/cssinjs/istf-spec
- https://github.com/css-modules/icss
- https://www.youtube.com/watch?v=bLgZwFRYTJ4
- https://github.com/mrmartineau/design-system-utils

# Challenges
- Standardizing on a highly opinionated API 
