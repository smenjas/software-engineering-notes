# Web Development Roadmap
My notes from [Free Code Camp's 2019 Web Developer Roadmap](ttps://www.freecodecamp.org/news/2019-web-developer-roadmap/),
which is just 3 of [Kamran Ahmed's Web Developer Roadmaps](https://roadmap.sh/), plus some commentary.

Links added later.

These [roadmaps outline the skills you need](https://roadmap.sh/) to be:
- any web developer
- [a front end web developer](https://roadmap.sh/frontend)
- [a back end web developer](https://roadmap.sh/backend)
- [a devops person (a.k.a. site reliability engineer or system administrator)](https://roadmap.sh/devops)

# Required for any path:
- [basic terminal usage (bash)](https://www.taniarascia.com/how-to-use-the-command-line-for-apple-macos-and-linux/)
- [KISS](https://en.wikipedia.org/wiki/KISS_principle),
  [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it),
  [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself),
  [SOLID](https://en.wikipedia.org/wiki/SOLID)
- [data structures](https://en.wikipedia.org/wiki/Data_structure) & [algorithms](https://en.wikipedia.org/wiki/Algorithm)
- [Git for version control](https://git-scm.com/book/)
- [GitHub](https://github.com/)
- [Software licenses (e.g. restrictive vs. permissive open source, proprietary, etc.)](https://en.wikipedia.org/wiki/Software_license)
- [semantic versioning](https://semver.org/)
- [SSH](https://en.wikipedia.org/wiki/Secure_Shell)
- [HTTP/S](https://en.wikipedia.org/wiki/HTTP) & [Web APIs](https://en.wikipedia.org/wiki/Web_API)
- [Design Patterns](https://en.wikipedia.org/wiki/Software_design_pattern)
- [Character encodings](https://en.wikipedia.org/wiki/Character_encoding) (e.g. [ASCII](https://en.wikipedia.org/wiki/ASCII) & [Unicode](https://en.wikipedia.org/wiki/Unicode)

# Front End Web Development Roadmap

## HTML
- [learn the basics](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [SEO](https://en.wikipedia.org/wiki/Search_engine_optimization)
- [accessibility](https://en.wikipedia.org/wiki/Web_accessibility)

## CSS
- [learn the basics](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
-- [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
-- [positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
-- [display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
-- [box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
-- [CSS grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
-- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
- [CSS3](https://developer.mozilla.org/en-US/docs/Archive/CSS3)

## Javascript
- [syntax and basic constructs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [DOM manipulation](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents)
- [fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)/[AJAX (XHR)](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
- [ES6+](https://www.codingame.com/playgrounds/6439/modern-es6-javascript-pt--1) & [modular JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
- Understand these concepts:
-- [hoisting](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)
-- [event bubbling](https://developer.mozilla.org/en-US/docs/Web/API/Event/bubbles)
-- [scope prototype](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
-- [shadow DOM](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
-- [strict](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)
-- [how browsers work](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
-- [DNS](https://en.wikipedia.org/wiki/Domain_Name_System)
-- [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

## Package managers
- [npm](https://en.wikipedia.org/wiki/Npm_(software))
- [yarn](https://yarnpkg.com/lang/en/docs/)

## CSS Preprocessors
- [SASS](https://sass-lang.com/guide)
- [Less](http://lesscss.org/usage/)
- [PostCSS](https://github.com/postcss/postcss#articles)

## CSS Frameworks
- [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
- [Materialize CSS](https://materializecss.com/getting-started.html)
- [Bulma](https://bulma.io/documentation/overview/start/)
- [Semantic UI](https://semantic-ui.com/introduction/getting-started.html)

## CSS Architecture
- unnecessary unless you're designing CSS systems
- [Block Element Modifier (BEM)](http://getbem.com/introduction/)
- [Object Oriented CSS (OOCSS)](https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/)
- [Scalable & Modular CSS (SMACSS)](http://smacss.com/)

## Build Tools
- [task runners](https://www.smashingmagazine.com/2016/06/harness-machines-productive-task-runners/)
-- [npm scripts](https://docs.npmjs.com/misc/scripts)
-- [gulp](https://gulpjs.com/docs/en/getting-started/quick-start)
- [module bundlers](https://dev.to/tanhauhau/what-is-module-bundler-and-how-does-it-work-3gp2)
-- [Webpack](https://webpack.js.org/)
-- [Parcel](https://parceljs.org/getting_started.html)
-- [Rollup](https://rollupjs.org/guide/en/)
- [linters & formatters](https://www.gistia.com/javascript-linters-formatter-prettier-eslint/)
-- [Prettier](https://prettier.io/docs/en/comparison.html)
-- [ESLint](https://eslint.org/docs/user-guide/getting-started)
-- [JSHint](https://jshint.com/)
-- [JSLint](https://jslint.com/)
-- [JSCS, which has merged with ESLint](https://jscs-dev.github.io/)

## Pick a Javascript framework
- know the [pros & cons of single page applications](https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58)
- [Express](https://expressjs.com/en/starter/installing.html)
- [React.js](https://reactjs.org/docs/getting-started.html)
- [Angular](https://angular.io/start)
-- [RxJS](https://rxjs-dev.firebaseapp.com/guide/overview)
-- [ngrx](https://ngrx.io/)
- [Vue.js](https://vuejs.org/v2/guide/)
-- [Vuex](https://vuex.vuejs.org/)

## CSS in JS
- [styled components](https://styled-components.com/)
- [CSS modules](https://github.com/css-modules/css-modules)
- [Emotion](https://emotion.sh/docs/introduction)
- [Radium](https://formidable.com/open-source/radium/)

## Testing front end web apps
- [Jest](https://jestjs.io/docs/en/getting-started.html),
  [Enzyme](https://airbnb.io/enzyme/), &
  [Cypress](https://docs.cypress.io/guides/getting-started/installing-cypress.html) can fulfill all your testing needs
- [Mocha](https://mochajs.org/#getting-started)
- [Chai](https://www.chaijs.com/)
- [Ava](https://www.npmjs.com/package/ava)
- [Karma](https://www.npmjs.com/package/karma)
- [Jasmine](https://www.npmjs.com/package/jasmine)
- [Protractor](https://www.npmjs.com/package/protractor)

## [Progressive Web Apps (PWAs)](https://en.wikipedia.org/wiki/Progressive_web_application)
- [storage](https://developers.google.com/web/fundamentals/instant-and-offline/web-storage/offline-for-pwa)
- [Websockets](https://en.wikipedia.org/wiki/WebSocket)
- [service workers](https://developers.google.com/web/fundamentals/primers/service-workers)
- [location](https://developers.google.com/web/fundamentals/native-hardware/user-location)
- [notifications](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Re-engageable_Notifications_Push)
- [device orientation](https://developer.mozilla.org/en-US/docs/Web/API/Detecting_device_orientation)
- [payments](https://developers.google.com/web/ilt/pwa/introduction-to-the-payment-request-api-slides)
- [credentials](https://developer.mozilla.org/en-US/docs/Web/API/Credential_Management_API)
- learn different [web APIs](https://en.wikipedia.org/wiki/Web_API) used in PWAs
- [calculating, measuring, & improving performance](https://www.pwastats.com/)
-- [PRPL Pattern](https://web.dev/apply-instant-loading-with-prpl/)
-- [RAIL Model](https://developers.google.com/web/fundamentals/performance/rail)
-- [performance metrics](https://developers.google.com/web/fundamentals/performance/user-centric-performance-metrics)
-- [using Lighthouse](https://developers.google.com/web/tools/lighthouse)
-- [using DevTools](https://developers.google.com/web/tools/chrome-devtools)

## Type Checkers
- [TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) (reduces bugs, very useful)
- [Flow](https://flow.org/)

## Server Side Rendering
- [React.js](https://reactjs.org/docs/getting-started.html)
-- [Next.js](https://nextjs.org/learn/basics/getting-started)
-- [After.js](https://github.com/jaredpalmer/after.js/blob/master/README.md)
- [Angular](https://angular.io/start)
-- [Univeral](https://blog.angular-university.io/angular-universal/)
- [Vue.js](https://vuejs.org/v2/guide/)
-- [Nuxt.js](https://nuxtjs.org/guide/)

## Static Site Generators
- [GatsbyJS](https://www.gatsbyjs.org/docs/)

## Desktop Applications
- [Electron](https://electronjs.org/)
- [Proton Native](https://proton-native.js.org/)
- [Carlo](https://github.com/GoogleChromeLabs/carlo)

## Mobile Applications
- [React Native](https://facebook.github.io/react-native/)
- [NativeScript](https://www.nativescript.org/)

## [WebAssembly](https://webassembly.org/)
- up and coming
- allows compiling any language (Python, Rust, Ruby, etc.) to bytecode
- may eventually replace Javascript
- this will take a while, so prioritize Javascript over WebAssembly

# Back End Web Development Roadmap

1. Learn a programming language.
- Python 3 is an excellent choice.
- JavaScript is an understandable choice.
- Swift, Kotlin, C, and many others make sense in certain situations.

2. Do a bunch of exercises.
- Grokking Algorithms
- Cracking the Coding Interview

3. Learn the package manager.
- pip for Python
- npm or yarn for JavaScript

4. Learn standards and best practices.
- Learn security best practices, e.g. OWASP.

5. Make and distribute a package/library/module.
- Contribute to an open source project.

6. Learn about testing.
- pytest for Python

7. Write automated tests.
- calculate test coverage

8. Learn relational databases.
- PostgreSQL is good
- add indexes
- use proper storage engines
- analyze queries

9. Create a simple application.
- registration
- login
- CRUD
- blog

10. Learn a framework.
- for Python, see Django or Flask

11. Port the application from step 9 to a framework.

12. Learn a NoSQL database.

13. Implement app level caching using Redis or Memecached.

14. Create RESTful APIs.

15. Learn authentication/authorization methodologies.

16. Learn message brokers, such as RabbitMQ & Kafka.

17. Learn a search engine, like ElasticSearch, Solr, or Sphinx.

18. Learn about containers, such as Docker & Kubernetes.

19. Learn about web servers, such as Apache HTTPD & Nginx.

20. Learn how to use WebSockets.

21. Learn GraphQL.

22. Learn about graph databases.

23. Keep exploring.  Learn profiling, static analysis, etc.

# DevOps Roadmap

## Learn a programming language
- Python
- Javascript & Node.js
- Swift
- Go
- Rust
- C
- C++

## Understand OS concepts
- process management
- threads & concurrency
- sockets
- I/O management
- virtualization
- memory & storage
- file systems

## Learn about managing servers
- operating systems
-- Linux
-- Unix
-- Windows
- Learn to live in the terminal
-- bash scripting
-- vim/nano/PowerShell/Emacs
-- compilation (gcc, make, etc.)
- system performance
-- nmon
-- iostat
-- sar
-- vmstat
- text manipulation tools
-- awk
-- sed
-- grep
-- sort
-- uniq
-- cat
-- cut
-- echo
-- fmt
-- tr
-- nl
-- egrep
-- wc
- process monitoring
-- ps
-- top
-- htop
-- atop
-- lsof
- network
-- nmap
-- tcpdump
-- ping
-- mtr
-- tracert
-- airmon
-- airodump
-- dig
-- iptables
- others
-- strace
-- dtrace
-- systemtap
-- uname
-- df
-- history

## Networking & Security
- DNS
- OSI model
- HTTP/S
- FTP/S
- SSL/TLS

## What is and how to set up a _____
- reverse proxy
- forward proxy
- caching server (e.g. Varnish)
- load balancer
- firewall
- web server
-- Apache HTTPD
-- Nginx

## Infrastructure as code
- containers
-- Docker
-- rkt
-- LXC
- configuration management
-- Ansible
-- Chef
-- Salt
-- Puppet
- container orchestration
-- Kubernetes
-- Docker Swarm
-- Mesos
-- Nomad
- infrastructure provisioning
-- Terraform
-- Cloud Formation
- continuous integration/delivery (CI/CD)
-- Jenkins
-- Travis CI
-- TeamCity
-- Drone
-- Circle CI
-- GitHub Actions

## Learn how to monitor software & infrastructure
- infrastructure monitoring
-- Nagios
-- Icinga
-- Datadog
-- Zabbix
-- Monit
- application monitoring
-- AppDynamics
-- New Relic
- log management
-- ELK stack
-- Graylog
-- Splunk
-- Papertrail

## Cloud Providers
- AWS
- Google Cloud
- Azure
- Digital Ocean
- Heroku
