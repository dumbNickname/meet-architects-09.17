# React v16 released [yesterday](https://facebook.github.io/react/blog/2017/09/26/react-v16.0.html#new-render-return-types-fragments-and-strings)!
Already landed in v16:
- New render return types: fragments and strings
- Error boundaries
- Portals
- Server-side rendering done right.
- Custom DOM attributes
- Reduced library size (30% savings)

Coming up:
- async rendering, read [here](https://gist.github.com/acdlite/f31becd03e2f5feb9b4b22267a58bc1f) or check the [demo](https://build-mbfootjxoo.now.sh/)


# Polymer / Web components
 - Polymer 1.0, 2.0, 3.0? Whaaaat?
 - Are web components a silver bullet for web development and reusability?
 - Do you like the idea of writing enterprise apps with web components and without frameworks such as Angular/React/Aurelia/Vue?
 
# Accelerated Mobile Pages
     https://www.ampproject.org/learn/about-how/

- Execute all AMP JavaScript asynchronously
- Size all resources statically
- Don’t let extension mechanisms block rendering
- Keep all third-party JavaScript out of the critical path
- All CSS must be inline and size-bound
- Font triggering must be efficient
- Minimize style recalculations
- Only run GPU-accelerated animations
- Prioritize resource loading
- Load pages in an instant

Others: 
- reduced page load time
- Google mobile ranking
- less load on servers
- The guardial released their AMP page [last year](https://www.theguardian.com/membership/2016/feb/24/todays-release-of-accelerated-mobile-pages-amp). You can still view pages in AMP: [original](https://www.theguardian.com/world/2017/sep/27/zealandia-drilling-reveals-secrets-of-sunken-lost-continent) and [amp](https://amp.theguardian.com/world/2017/sep/27/zealandia-drilling-reveals-secrets-of-sunken-lost-continent) versions of the same article.

# Accelerated Mobile Pages - Cons
- amazing speed achieved thanks to Google cache 
- JavaScript required
- separate page required
- content differences (AMP vs RWD)
- stripped analytics 


# [PWA](https://mmatczak.github.io/tech-talk-web-rev/#/55)
- [Service Workers](https://mmatczak.github.io/tech-talk-web-rev/#/31)
    - Push Notifications
    - Caching
    - Content strategies
    - ... 
- Native experience
    - Fast!
    - Add to home screen
    - standalone display 
    - Responsive
- Application Shell 
- PRPL pattern

# Universal JS/SSR vs progressive 
- SPA vs SEO - Google executes JS! (but ...)
- Best perceived performance
- Uncanny valley
- Problems of SSR for Universal JS (misuse of React.renderToString())

# GraphQL
- Conceptual similarities to HATEOAS (generic REST interface)
- Data query language
- A [specification](https://facebook.github.io/graphql/October2016/) that determines the validity of the schema on the API server. The schema determines the validity of client calls.
- Strongly typed
- Introspective
- Hierarchical.
- Not a storage model
- Not a DB query language
- An application layer
- Learn more [here](http://graphql.org/learn/)
- [Example](https://developer.github.com/v4/) from github

# Media relevant topics
- Caching e.g. active, inactive, CDNs 
- SEO - top factors, mobile index, no page score test
- Internationalization - RTL, page looks, topics
- Tracking
