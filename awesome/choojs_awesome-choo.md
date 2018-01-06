# Info come from [choojs/awesome-choo](https://github.com/choojs/awesome-choo)
# Awesome choo [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <div align="right">:steam_locomotive::train::train::train::train::train:</div>

> [choo](https://choo.io/) is a `4kb` framework for creating
> sturdy frontend applications

## Contents

- [Official resources](#official-resources)
- [Dependencies](#dependencies)
- [Demos](#demos)
- [Community](#community)
- [Plugins and addons](#plugins-and-addons)
- [Elements](#elements)
- [CLI Templates](#cli-templates)
- [Resources](#resources)
- [Projects using choo](#projects-using-choo)

### Official resources

- [Docs](https://github.com/yoshuawuyts/choo/blob/master/README.md)
- [Handbook](https://github.com/yoshuawuyts/choo-handbook) :star:208
- [Repo](https://github.com/yoshuawuyts/choo) :star:4918
- [Website](https://choo.io/)
- [Twitter thread](https://twitter.com/yoshuawuyts/status/730087077803528193)

### Dependencies
`choo` is a modular framework. These are the dependencies it glues together
under the hood:

- [bel](https://github.com/shama/bel) - Create composable DOM elements using :star:402
  template strings.
- [hyperx](https://github.com/substack/hyperx) - Convert template strings to :star:818
  library backends.
- [nanomorph](https://github.com/choojs/nanomorph) - Hyper fast diffing algorithm for real DOM nodes. :star:336
- [nanoraf](https://github.com/yoshuawuyts/nanoraf) - Only call RAF when needed. :star:52
- [nanorouter](https://github.com/choojs/nanorouter) - Smol frontend router. :star:67
- [nanobus](https://github.com/choojs/nanobus) - Tiny message bus. :star:99
- [nanolocation](https://github.com/choojs/nanolocation) - Small window.location library. :star:8
- [nanohref](https://github.com/choojs/nanohref) - Tiny href click handler library. :star:22
- [nanoquery](https://github.com/choojs/nanoquery) - Tiny querystring module. :star:24
- [nanotiming](https://github.com/choojs/nanotiming) - Small timing library. :star:16

### Demos

- [Input example](http://requirebin.com/?gist=e589473373b3100a6ace29f7bbee3186) - ([repo](https://github.com/yoshuawuyts/choo/tree/master/examples/title))
- [HTTP effects](https://hyperdev.com/#!/project/fork-fang)
- [Mailbox routing](https://github.com/yoshuawuyts/choo/tree/master/examples/mailbox)
- [TodoMVC](http://shuheikagawa.com/todomvc-choo) - ([repo](https://github.com/shuhei/todomvc-choo))
- [choo-firebase](https://choo-firebase-2ec21.firebaseapp.com) - ([repo](https://github.com/mw222rs/choo-firebase))
- [Grow](https://grow.static.land) - ([repo](https://github.com/sethvincent/grow))
- [Chatbot](http://chootbot.herokuapp.com) - ([repo](https://github.com/plaey/chatbot))
- [chat-random](https://github.com/akiva/chat-random) :star:4
- [choo-leaflet-demo](https://github.com/timwis/choo-leaflet-demo) :star:13
- [choo-scriber](https://zhouhansen.github.io/choo-scriber) - ([repo](https://github.com/ZhouHansen/choo-scriber))

### Community

- [Freenode](https://webchat.freenode.net/?channels=choo)

### Plugins and addons

- [choo-location-electron](https://github.com/bcomnes/choo-location-electron) - Fix `choo`'s router in electron. :star:11
- [choo-log](https://github.com/yoshuawuyts/choo-log) - Development logger for choo. :star:45
- [choo-test](https://github.com/mantoni/choo-test) - Easy choo app unit testing. :star:20
- [choo-persist](https://github.com/yoshuawuyts/choo-persist/) - Synchronize choo state with indexedDB.
- [choo-promise](https://github.com/rahatarmanahmed/choo-promise) - Use promises in effects and subscriptions. :star:3
- [choo-pull](https://github.com/yoshuawuyts/choo-pull) - Wrap handlers to use pull-stream in a choo plugin. :star:12
- [choo-redirect](https://github.com/yoshuawuyts/choo-redirect) - Redirect a view to another view. :star:13
- [choo-model](https://github.com/yoshuawuyts/choo-model) - Experimental state management lib for choo. :star:11
- [choo-resume](https://github.com/bengourley/choo-resume) - choo-resume + hot-rld = hot app reload in choo. :star:14
- [choo-detached](https://github.com/graforlock/choo-detached) - Use `choo` as a mountable, simple stand-alone component (no routing). :star:10
- [choo-service-worker](https://github.com/choojs/choo-service-worker) - Service worker loader for `choo`. :star:17
- [choo-websocket](https://github.com/YerkoPalma/choo-websocket) - Small wraper around WebSocket browser API, for `choo` apps. :star:23

### Elements

- [dom-notifications](https://github.com/finnp/dom-notifications) - Atom-inspired notifications component. :star:105
- [choodown](https://github.com/trainyard/choodown) - A simple markdown component for choo. :star:15
- [choo-md-editor](https://github.com/dbtek/choo-md-editor) - Lightweight markdown editor that can be used inside Choo app or as a standalone library. :star:3
- [choo-chartist](https://github.com/rexmortus/choo-chartist) - A little component for using [Chartist](https://gionkunz.github.io/chartist-js/) with the choo framework. :star:7

### CLI Templates

Templates for [choo-cli](https://github.com/trainyard/choo-cli)

- [trainyard/template-basic](https://github.com/trainyard/template-basic) :star:2
- [haroenv/template-webpack](https://github.com/haroenv/template-webpack) :star:6
- [simonwjackson/atomic-choo](https://github.com/simonwjackson/atomic-choo) - An opinionated project seed to get started developing with electron, webpack and choo.

Other CLI templates
- [graforlock/choo-bandwagon](https://github.com/graforlock/choo-bandwagon) :star:11

### Resources
> :movie_camera: : videos
> :computer: : tutorials
> :book: : articles

- :computer: [Your first choo app](https://yoshuawuyts.gitbooks.io/choo/content/02_your_first_app.html)
- :movie_camera: [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
- :book: [A better frontend experience](https://medium.com/@yoshuawuyts/a-better-frontend-experience-7b0498c85658)
- :book: [Composition in CycleJS, choo, React and Angular2](http://blog.krawaller.se/posts/composition-in-cyclejs-choo-react-and-angular2)
- :book: [Stupidly smart components in choo](http://blog.krawaller.se/posts/stupidly-smart-components-in-choo)

### Projects using choo

- [boxcar](https://github.com/toddself/boxcar) - A choo-based grid/spreadsheet editor. :star:9
- [choo-sortable](https://github.com/willkessler/choo-sortable) - Building sortable code with choo. :star:2
- [hacker-choo](https://github.com/mw222rs/hacker-choo) - Hacker Typer clone written in choo. :star:10
- [footprint-rechoo](https://github.com/npeihl/footprint-rechoo) - A choo rewrite of [footprint-review](http://github.com/sjcgis/footprint-review). :star:3
- [minidocs](https://github.com/freeman-lab/minidocs) – A documentation site generator built with choo.
- [dataface](https://github.com/timwis/dataface) - Desktop application to manage databases. :star:18
- [BlankUp](https://github.com/HoverBaum/BlankUp-Electron) - Multiplatform markdown editor. :star:33
- [hackernews-choo](https://github.com/kvnneff/hackernews-choo) - A Hacker News reader built with choo. :star:28
- [tic-tac-choo](https://github.com/YerkoPalma/tic-tac-toe) - Progressive tic tac toe game, made with choo. :star:5
- [enviar](https://github.com/timwis/enviar) - Chat interface for SMS / text messages. :star:30
- [kaktus](https://github.com/kaktus/kaktus) - A new minimalistic web browser, built on `choo` and IndexedDB. :star:356
- [civicdr.org](https://github.com/CiviCDR/civicdr.org) - Website for [CiviCDR](https://civicdr.org/). :star:2
- [nekocafe](https://github.com/notenoughneon/nekocafe) - Web chat room :cat: :speech_balloon:. :star:15
- [Robotopia](https://github.com/robotopia-x/robotopia) - Introducing kids to coding with tiny virtual robots! :star:410

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yerko Palma](https://github.com/YerkoPalma) has waived all copyright and related or neighboring rights to this work.
