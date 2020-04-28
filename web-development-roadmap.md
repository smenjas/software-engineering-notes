# Web Development Roadmap
My notes from [Free Code Camp's 2019 Web Developer Roadmap](ttps://www.freecodecamp.org/news/2019-web-developer-roadmap/),
which is just 3 of [Kamran Ahmed's Web Developer Roadmaps](https://roadmap.sh/), plus some commentary.

These [roadmaps outline the skills you need](https://roadmap.sh/) to be:
- [any web developer](#any-web-developer)
- [a front end web developer](#front-end-web-development-roadmap)
- [a back end web developer](#back-end-web-development-roadmap)
- [a devops person (a.k.a. system administrator or site reliability engineer)](#devops-roadmap)

---

- [Any Web Developer](#any-web-developer)
- [Front End Web Development Roadmap](#front-end-web-development-roadmap)
  - [HTML](#html)
  - [CSS](#css)
  - [Javascript](#javascript)
  - [Package managers](#package-managers)
  - [CSS Preprocessors](#css-preprocessors)
  - [CSS Frameworks](#css-frameworks)
  - [CSS Architecture](#css-architecture)
  - [Build Tools](#build-tools)
  - [Pick a Javascript framework](#pick-a-javascript-framework)
  - [CSS in JS](#css-in-js)
  - [Testing front end web apps](#testing-front-end-web-apps)
  - [Progressive Web Apps (PWAs)](#progressive-web-apps-pwas)
  - [Type Checkers](#type-checkers)
  - [Server Side Rendering](#server-side-rendering)
  - [Static Site Generators](#static-site-generators)
  - [Desktop Applications](#desktop-applications)
  - [Mobile Applications](#mobile-applications)
  - [WebAssembly](#webassembly)
- [Back End Web Development Roadmap](#back-end-web-development-roadmap)
- [DevOps Roadmap](#devops-roadmap)
  - [Learn a programming language](#learn-a-programming-language)
  - [Understand OS concepts](#understand-os-concepts)
  - [Learn about managing servers](#learn-about-managing-servers)
  - [Networking & Security](#networking--security)
  - [Know How to Set Up Services](#know-how-to-set-up-services)
  - [Infrastructure as code](#infrastructure-as-code)
  - [Learn how to monitor software & infrastructure](#learn-how-to-monitor-software--infrastructure)
  - [Cloud Providers](#cloud-providers)

---

# Any Web Developer
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


# [Front End Web Development Roadmap](https://roadmap.sh/frontend)

## HTML
- [learn the basics](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [SEO](https://en.wikipedia.org/wiki/Search_engine_optimization)
- [accessibility](https://en.wikipedia.org/wiki/Web_accessibility)

## CSS
- [learn the basics](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
  - [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
  - [positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
  - [display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
  - [box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
  - [CSS grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
  - [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
- [CSS3](https://developer.mozilla.org/en-US/docs/Archive/CSS3)

## Javascript
- [syntax and basic constructs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [DOM manipulation](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents)
- [fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)/[AJAX (XHR)](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
- [ES6+](https://www.codingame.com/playgrounds/6439/modern-es6-javascript-pt--1) & [modular JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
- Understand these concepts:
  - [hoisting](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)
  - [event bubbling](https://developer.mozilla.org/en-US/docs/Web/API/Event/bubbles)
  - [scope prototype](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
  - [shadow DOM](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
  - [strict](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)
  - [how browsers work](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
  - [DNS](https://en.wikipedia.org/wiki/Domain_Name_System)
  - [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

## Package managers
- [npm](https://en.wikipedia.org/wiki/Npm_%28software%29)
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
  - [npm scripts](https://docs.npmjs.com/misc/scripts)
  - [gulp](https://gulpjs.com/docs/en/getting-started/quick-start)
- [module bundlers](https://dev.to/tanhauhau/what-is-module-bundler-and-how-does-it-work-3gp2)
  - [Webpack](https://webpack.js.org/)
  - [Parcel](https://parceljs.org/getting_started.html)
  - [Rollup](https://rollupjs.org/guide/en/)
- [linters & formatters](https://www.gistia.com/javascript-linters-formatter-prettier-eslint/)
  - [Prettier](https://prettier.io/docs/en/comparison.html)
  - [ESLint](https://eslint.org/docs/user-guide/getting-started)
  - [JSHint](https://jshint.com/)
  - [JSLint](https://jslint.com/)
  - [JSCS, which has merged with ESLint](https://jscs-dev.github.io/)

## Pick a Javascript framework
- know the [pros & cons of single page applications](https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58)
- [Express](https://expressjs.com/en/starter/installing.html)
- [React.js](https://reactjs.org/docs/getting-started.html)
- [Angular](https://angular.io/start)
  - [RxJS](https://rxjs-dev.firebaseapp.com/guide/overview)
  - [ngrx](https://ngrx.io/)
- [Vue.js](https://vuejs.org/v2/guide/)
  - [Vuex](https://vuex.vuejs.org/)

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
  - [PRPL Pattern](https://web.dev/apply-instant-loading-with-prpl/)
  - [RAIL Model](https://developers.google.com/web/fundamentals/performance/rail)
  - [performance metrics](https://developers.google.com/web/fundamentals/performance/user-centric-performance-metrics)
  - [using Lighthouse](https://developers.google.com/web/tools/lighthouse)
  - [using DevTools](https://developers.google.com/web/tools/chrome-devtools)

## Type Checkers
- [TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) (reduces bugs, very useful)
- [Flow](https://flow.org/)

## Server Side Rendering
- [React.js](https://reactjs.org/docs/getting-started.html)
  - [Next.js](https://nextjs.org/learn/basics/getting-started)
  - [After.js](https://github.com/jaredpalmer/after.js/blob/master/README.md)
- [Angular](https://angular.io/start)
  - [Univeral](https://blog.angular-university.io/angular-universal/)
- [Vue.js](https://vuejs.org/v2/guide/)
  - [Nuxt.js](https://nuxtjs.org/guide/)

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

# [Back End Web Development Roadmap](https://roadmap.sh/backend)

1. Learn a programming language.
  - [Python 3](https://www.python.org/) is an excellent choice.
  - JavaScript is an understandable choice.

2. Do a bunch of exercises.
  - [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms)
  - [Cracking the Coding Interview](http://www.crackingthecodinginterview.com/)

3. Learn the package manager.
  - [pip for Python](https://packaging.python.org/tutorials/installing-packages/)
  - [npm](https://docs.npmjs.com/about-npm/) or [yarn](https://yarnpkg.com/en/docs/getting-started) for JavaScript

4. Learn standards and best practices.
  - Learn security best practices, e.g. [OWASP](https://owasp.org/www-project-top-ten/).

5. Make and distribute a package/library/module.
  - Contribute to an open source project.

6. Learn about testing.
  - [pytest for Python](https://docs.pytest.org/)

7. Write automated tests.
  - [calculate test coverage](https://en.wikipedia.org/wiki/Code_coverage)

8. Learn relational databases.
  - [PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL) is good
  - add indexes
  - use proper storage engines
  - analyze queries

9. Create a simple application.
  - [registration & login](https://medium.com/@himanshuxd/how-to-create-registration-login-webapp-with-django-2-0-fd33dc7a6c67)
  - [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete)
  - blog

10. Learn a framework.
  - for Python, see [Django](https://www.djangoproject.com/) or [Flask](http://flask.palletsprojects.com/)

11. Port the application from step 9 to a framework.

12. Learn a [NoSQL database](https://en.wikipedia.org/wiki/NoSQL).
  - [Mongo](https://en.wikipedia.org/wiki/MongoDB) for example

13. Implement app level caching using [Redis](https://redis.io/topics/introduction) or [Memcached](https://memcached.org/).

14. Create [RESTful APIs](https://en.wikipedia.org/wiki/Representational_state_transfer).

15. Learn [authentication](https://en.wikipedia.org/wiki/Authentication)/[authorization](https://en.wikipedia.org/wiki/Authorization) methodologies.

16. Learn message brokers, such as [RabbitMQ](https://en.wikipedia.org/wiki/RabbitMQ) & [Kafka](https://kafka.apache.org/intro).

17. Learn a search engine, like [ElasticSearch](https://en.wikipedia.org/wiki/Elasticsearch), [Solr](https://en.wikipedia.org/wiki/Apache_Solr), or [Sphinx](https://en.wikipedia.org/wiki/Sphinx_%28search_engine%29).

18. Learn about [containers](https://en.wikipedia.org/wiki/OS-level_virtualization), such as [Docker](https://en.wikipedia.org/wiki/Docker_%28software$29) & [Kubernetes](https://en.wikipedia.org/wiki/Kubernetes).

19. Learn about web servers, such as [Apache HTTPD](http://httpd.apache.org/) & [Nginx](https://www.nginx.com/).

20. Learn how to use [WebSockets](https://en.wikipedia.org/wiki/WebSocket).

21. Learn [GraphQL](https://en.wikipedia.org/wiki/GraphQL).

22. Learn about [graph databases](https://en.wikipedia.org/wiki/Graph_database).

23. Keep exploring. Learn [profiling](https://en.wikipedia.org/wiki/Profiling_%28computer_programming%29), [static analysis](https://en.wikipedia.org/wiki/Static_program_analysis), etc.

# [DevOps Roadmap](https://roadmap.sh/devops)

## Learn a programming language
- [Python](https://www.python.org/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) & [Node.js](https://nodejs.org/en/about/)
- [Swift](https://docs.swift.org/swift-book/)
- [Go](https://golang.org/)
- [Rust](https://www.rust-lang.org/)
- [C](https://en.wikipedia.org/wiki/C_%28programming_language%29)
- [C++](https://en.wikipedia.org/wiki/C%2B%2B)

## Understand OS concepts
- [process management](https://en.wikipedia.org/wiki/Process_management_%28computing%29)
- [threads](https://en.wikipedia.org/wiki/Thread_%28computing%29) & [concurrency](https://en.wikipedia.org/wiki/Concurrency_%28computer_science%29)
- [sockets](https://en.wikipedia.org/wiki/Network_socket)
- [I/O management](https://en.wikipedia.org/wiki/Input/output)
- [virtualization](https://en.wikipedia.org/wiki/Virtualization)
- [memory](https://en.wikipedia.org/wiki/Computer_memory) & [storage](https://en.wikipedia.org/wiki/Computer_data_storage)
- [file systems](https://en.wikipedia.org/wiki/File_system)

## Learn about managing servers
- [operating systems](https://en.wikipedia.org/wiki/Operating_system)
  - [Linux](https://en.wikipedia.org/wiki/Linux)
  - [Unix](https://en.wikipedia.org/wiki/Unix)
  - [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows)
- [Learn to live in the terminal](https://www.linuxjournal.com/content/without-gui-how-live-entirely-terminal)
  - [bash scripting](http://tldp.org/LDP/abs/html/)
  - [vim](https://www.vim.org/)/[nano](https://en.wikipedia.org/wiki/GNU_nano)/[PowerShell](https://en.wikipedia.org/wiki/PowerShell)/[Emacs](https://www.gnu.org/software/emacs/tour/)
  - [compilation](https://en.wikipedia.org/wiki/Compilation) ([gcc](https://en.wikipedia.org/wiki/GNU_Compiler_Collection), [make](https://en.wikipedia.org/wiki/Make_%28software%29), etc.)
- [system performance](https://en.wikipedia.org/wiki/Computer_performance)
  - [nmon](https://en.wikipedia.org/wiki/Nmon)
  - [iostat](https://en.wikipedia.org/wiki/Iostat)
  - [sar](https://en.wikipedia.org/wiki/Sar_%28Unix%29)
  - [vmstat](https://en.wikipedia.org/wiki/Vmstat)
- [text manipulation tools](https://www.tldp.org/LDP/GNU-Linux-Tools-Summary/html/text-manipulation-tools.html)
  - [awk](https://en.wikipedia.org/wiki/AWK)
  - [sed](https://en.wikipedia.org/wiki/Sed)
  - [grep](https://en.wikipedia.org/wiki/Grep)
  - [sort](https://en.wikipedia.org/wiki/Sort_%28Unix%29)
  - [uniq](https://en.wikipedia.org/wiki/Uniq)
  - [cat](https://en.wikipedia.org/wiki/Cat_%28Unix%29)
  - [cut](https://en.wikipedia.org/wiki/Cut_%28Unix%29)
  - [echo](https://en.wikipedia.org/wiki/Echo_%28command%29)
  - [fmt](https://en.wikipedia.org/wiki/Fmt_%28Unix%29)
  - [tr](https://en.wikipedia.org/wiki/Tr_%28Unix%29)
  - [nl](https://en.wikipedia.org/wiki/Nl_%28Unix%29)
  - [egrep](https://en.wikipedia.org/wiki/Regular_expression#POSIX_basic_and_extended)
  - [wc](https://en.wikipedia.org/wiki/Wc_%28Unix%29)
- [process monitoring](https://en.wikipedia.org/wiki/Program_process_monitoring)
  - [ps](https://en.wikipedia.org/wiki/Ps_%28Unix%29)
  - [top](https://en.wikipedia.org/wiki/Top_%28software%29)
  - [htop](https://en.wikipedia.org/wiki/Htop)
  - [atop](https://www.atoptool.nl/)
  - [lsof](https://en.wikipedia.org/wiki/Lsof)
- [network](https://en.wikipedia.org/wiki/Telecommunications_network)
  - [nmap](https://en.wikipedia.org/wiki/Nmap)
  - [tcpdump](https://en.wikipedia.org/wiki/Tcpdump)
  - [ping](https://en.wikipedia.org/wiki/Ping_%28networking_utility%29)
  - [mtr](https://en.wikipedia.org/wiki/MTR_%28software%29)
  - [tracert](https://en.wikipedia.org/wiki/Traceroute)
  - [airmon](https://www.aircrack-ng.org/doku.php?id=airmon-ng)
  - [airodump](https://www.aircrack-ng.org/doku.php?id=airodump-ng)
  - [dig](https://en.wikipedia.org/wiki/Dig_%28command%29)
  - [iptables](https://en.wikipedia.org/wiki/Iptables)
  - [nftables](https://en.wikipedia.org/wiki/Nftables)
- others
  - [strace](https://en.wikipedia.org/wiki/Strace)
  - [dtrace](https://en.wikipedia.org/wiki/Dtrace)
  - [systemtap](https://en.wikipedia.org/wiki/SystemTap)
  - [uname](https://en.wikipedia.org/wiki/Uname)
  - [df](https://en.wikipedia.org/wiki/Df_%28Unix%29)
  - [history](https://en.wikipedia.org/wiki/History_%28Unix%29)

## Networking & Security
- [DNS](https://en.wikipedia.org/wiki/Domain_Name_System)
- [OSI model](https://en.wikipedia.org/wiki/OSI_model)
- [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)/[S](https://en.wikipedia.org/wiki/HTTPS)
- [FTP/S](https://en.wikipedia.org/wiki/File_Transfer_Protocol)
- [SSL/TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security)

## Know How to Set Up Services
- [reverse proxy](https://en.wikipedia.org/wiki/Reverse_proxy)
- [forward proxy](https://en.wikipedia.org/wiki/Proxy_server)
- [caching server](https://en.wikipedia.org/wiki/Web_cache) (e.g. [Varnish](https://en.wikipedia.org/wiki/Varnish_%28software%29%29)
- [load balancer](https://en.wikipedia.org/wiki/Load_balancing_%28computing%29)
- [firewall](https://en.wikipedia.org/wiki/Firewall_%28computing%29)
- [web server](https://en.wikipedia.org/wiki/Firewall_%28computing%29)
  - [Apache HTTPD](http://httpd.apache.org/)
  - [Nginx](https://www.nginx.com/)

## Infrastructure as code
- [containers](https://en.wikipedia.org/wiki/OS-level_virtualization)
  - [Docker](https://en.wikipedia.org/wiki/Docker_%28software%29)
  - [rkt](https://coreos.com/rkt/)
  - [LXC](https://en.wikipedia.org/wiki/LXC)
- [configuration management](https://en.wikipedia.org/wiki/Configuration_management)
  - [Ansible](https://en.wikipedia.org/wiki/Ansible_%28software%29)
  - [Chef](https://www.chef.io/)
  - [Salt](https://docs.saltstack.com/en/latest/)
  - [Puppet](https://en.wikipedia.org/wiki/Puppet_%28company%29)
- [container orchestration](https://blog.newrelic.com/engineering/container-orchestration-explained/)
  - [Kubernetes](https://kubernetes.io/)
  - [Docker Swarm](https://docs.docker.com/engine/swarm/)
  - [Mesos](http://mesos.apache.org/)
  - [Nomad](https://www.nomadproject.io/)
- [infrastructure provisioning](https://www.future-processing.pl/blog/infrastructure-as-code-provisioning/)
  - [Terraform](https://learn.hashicorp.com/terraform)
  - [CloudFormation](https://aws.amazon.com/cloudformation/)
- [continuous integration (CI)](https://en.wikipedia.org/wiki/Continuous_integration) & [continuous delivery (CD)](https://en.wikipedia.org/wiki/Continuous_delivery)
  - [Jenkins](https://jenkins.io/)
  - [Travis CI](https://docs.travis-ci.com/user/tutorial/)
  - [TeamCity](https://www.jetbrains.com/teamcity/)
  - [Drone](https://drone.io/)
  - [Circle CI](https://circleci.com/)
  - [GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions)

## Learn how to monitor software & infrastructure
- infrastructure monitoring
  - [Nagios](https://www.nagios.org/)
  - [Icinga](https://icinga.com/)
  - [Datadog](https://www.datadoghq.com/)
  - [Zabbix](https://www.zabbix.com/)
  - [Monit](https://mmonit.com/)
- application monitoring
  - [AppDynamics](https://www.appdynamics.com/)
  - [New Relic](https://newrelic.com/)
- [log management](https://en.wikipedia.org/wiki/Log_management)
  - [ELK stack: Elasticsearch, Logstash, Kibana](https://www.elastic.co/what-is/elk-stack)
  - [Graylog](https://en.wikipedia.org/wiki/Graylog)
  - [Splunk](https://www.splunk.com/)
  - [Papertrail](https://www.papertrail.com/)

## Cloud Providers
- [AWS](https://aws.amazon.com/)
- [Google Cloud](https://cloud.google.com/)
- [Azure](https://azure.microsoft.com/)
- [Digital Ocean](https://www.digitalocean.com/)
- [Heroku](https://www.heroku.com/)
