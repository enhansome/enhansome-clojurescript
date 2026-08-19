<img src="https://avatars2.githubusercontent.com/u/12118456?v=3&s=75"
  align="right"/>

# Awesome ClojureScript with stars

##### A community driven list of ClojureScript books, frameworks, libraries and wrappers.

***

* [Resources](#resources)
  * [Books](#books)
* [Awesome ClojureScript](#awesome-clojurescript-1)
  * [Canvas](#canvas)
  * [Client/Server Communication](#clientserver-communication)
  * [Code Analysis](#code-analysis)
  * [Data Serialization](#data-serialization)
  * [Data Visualization](#data-visualization)
  * [Database](#database)
  * [Development](#development)
  * [Document Object Model](#document-object-model)
  * [Documentation](#documentation)
  * [Graphics](#graphics)
  * [HTTP Handler](#http-handler)
  * [Internationalization](#internationalization)
  * [JavaScript Interoperability](#javascript-interoperability)
  * [Miscellaneous](#miscellaneous)
  * [React.js Interface](#reactjs-interface)
  * [Reactive Programming](#reactive-programming)
  * [Routing](#routing)
  * [State Management](#state-management)
  * [Testing](#testing)
  * [Validation](#validation)
  * [Web Framework & Template](#web-framework--template)
  * [WebSockets](#websockets)
* [Contributing](#contributing)
* [License](#license)

***

## Resources

### Books

* [ClojureScript Unraveled](https://leanpub.com/clojurescript-unraveled) – An open source book about the ClojureScript language that covers all the language features, how to use the compiler and the tooling for building applications and libraries.
* [ClojureScript Unraveled (2nd edition)](https://funcool.github.io/clojurescript-unraveled/) – An open source book about the ClojureScript language that covers all the language features, how to use the compiler and the tooling for building applications and libraries.
* [ClojureScript: Up and Running](https://shop.oreilly.com/product/0636920025139.do) – An introduction to ClojureScript written by big guns of Clojure Stuart Sierra and Luke VanderHart.
* [Clojure, The Essential Reference](https://www.manning.com/books/clojure-the-essential-reference) – A reference book on the Clojure language and standard library.
* [Etudes for ClojureScript](https://shop.oreilly.com/product/0636920043584.do) – A hands-on-book of 30 companion exercises or études for introducing ClojureScript.
* [Learning ClojureScript](https://www.packtpub.com/web-development/learning-clojurescript) – Master the art of agile single page web application development with ClojureScript.
* [Transforming Data with ClojureScript](https://langintro.com/cljsbook) – A beginner's guide to ClojureScript with interactive examples and exercises, "focusing on the main task that programming does—transforming data".

### Courses

* [ClojureScript Koans](http://clojurescriptkoans.com/) – A great way to start learning Clojure and ClojureScript on the web with interactive challanges.
* [Lambda Island](https://lambdaisland.com/) – A full-stack web development course including front-end with ClojureScript, back-end with Clojure, language essentials, security, internet standards and system administration.
* [Learn Reagent](https://www.learnreagent.com/) – An introduction to ClojureScript with Reagent for developers. 1 hour free content is available. [learn re-frame](https://www.learnreframe.com/) is its follow up.
* [Learning ClojureScript](https://purelyfunctional.tv/) – A 2h 11m long introduction to Clojurescript by O'Really Online Learning. Also available on [Udemy](https://www.udemy.com/course/learning-clojurescript/).

### Videos

* [ClojureScript for Skeptics](https://www.youtube.com/watch?v=gsffg5xxFQI) – Derek Slager's talk for Clojure Conj 2015 where he is Discussing the many reasons why ClojureScript is in fact a very pragmatic language to consider for web development.
* [Interactive programming Flappy Bird in ClojureScript](https://www.youtube.com/watch?v=KZjFVdU8VLI) – A 5 minutes video from 2014 demostrating the power of ClojureScript's developer experience.

## Awesome ClojureScript

### Canvas

* [Monet](https://github.com/rm-hull/monet) ⭐ 170 | 🐛 5 | 🌐 Clojure | 📅 2017-01-06 – A small ClojureScript library to make it easier to work with canvas and visuals.
* [Quamolit](https://github.com/Quamolit/quamolit) ⭐ 7 | 🐛 0 | 🌐 Cirru | 📅 2024-04-01 – A tiny declarative animation library , inspired by React.

### Client/Server Communication

* [cljs-ajax](https://github.com/JulianBirch/cljs-ajax) ⭐ 676 | 🐛 26 | 🌐 Clojure | 📅 2026-08-05 – A simple Ajax client for ClojureScript and Clojure.
* [Fetch](https://github.com/LightTable/fetch) ⚠️ Archived – A ClojureScript library that makes client/server interaction painless.

### Code Analysis

* [kibit](https://github.com/jonase/kibit) ⭐ 1,755 | 🐛 54 | 🌐 Clojure | 📅 2024-05-22 – Static code analyzer to find patterns of code that could be rewritten with a more idiomatic function or macro.

### Data Serialization

* [Transit](https://github.com/cognitect/transit-cljs) ⭐ 327 | 🐛 13 | 🌐 Clojure | 📅 2024-07-15 – A data interchange format and set of libraries for conveying values between applications written in different programming languages.
* [Cljson](https://github.com/tailrecursion/cljson) ⭐ 62 | 🐛 3 | 🌐 Clojure | 📅 2015-10-21 – Clojure/ClojureScript library for accelerated browser data deserialization.

### Data Visualization

* [C2](https://keminglabs.com/c2) – It lets you declaratively create HTML and SVG markup based on data.

### Database

* [Datascript](https://github.com/tonsky/datascript) ⭐ 5,781 | 🐛 75 | 🌐 Clojure | 📅 2026-08-15 – An immutable in-memory database and Datalog query engine in ClojureScript.
* [Konserve](https://github.com/replikativ/konserve) ⭐ 317 | 🐛 20 | 🌐 Clojure | 📅 2026-08-18 – A clojuresque key-value/document store protocol with core.async.
* [specql](https://github.com/tatut/specql) ⭐ 135 | 🐛 10 | 🌐 Clojure | 📅 2024-09-20 – Library for simple PostgreSQL queries with namespaced keys.
* [Jaki](https://github.com/pandeiro/jaki) ⭐ 16 | 🐛 0 | 🌐 Clojure | 📅 2012-10-10 – A simple ClojureScript CouchDB client.

### Development

* [lein-figwheel](https://github.com/bhauman/lein-figwheel) ⭐ 2,875 | 🐛 98 | 🌐 Clojure | 📅 2024-03-26 – Leiningen plugin that pushes ClojureScript code changes to the client.
* [shadow-cljs](https://github.com/thheller/shadow-cljs) ⭐ 2,403 | 🐛 43 | 🌐 Clojure | 📅 2026-08-10 – ClojureScript compilation made easy
* [Lumo](https://github.com/anmonteiro/lumo) ⚠️ Archived – Fast, cross-platform, standalone ClojureScript environment.
* [Devcards](https://github.com/bhauman/devcards) ⭐ 1,535 | 🐛 30 | 🌐 Clojure | 📅 2023-09-17 – Devcards aims to provide a visual REPL experience for ClojureScript.
* [cljs-devtools](https://github.com/binaryage/cljs-devtools) ⭐ 1,127 | 🐛 19 | 🌐 Clojure | 📅 2023-04-08 – Better presentation of ClojureScript values in Chrome Devtools.
* [lein-cljsbuild](https://github.com/emezeske/lein-cljsbuild) ⭐ 1,093 | 🐛 49 | 🌐 Clojure | 📅 2021-03-19 – A Leiningen plugin to make ClojureScript development easy.
* [Planck](https://github.com/mfikes/planck) ⭐ 1,040 | 🐛 94 | 🌐 C | 📅 2024-08-28 – A stand-alone ClojureScript REPL for macOS and Linux based on JavaScriptCore.
* [Ambly](https://github.com/omcljs/ambly) ⭐ 538 | 🐛 9 | 🌐 Objective-C | 📅 2022-07-29 – A ClojureScript REPL into iOS JavaScriptCore.
* [Truss](https://github.com/ptaoussanis/truss) ⭐ 328 | 🐛 0 | 🌐 Clojure | 📅 2026-07-29 – An opinionated assertions API for Clojure/ClojureScript.
* [Instaparse](https://github.com/lbradstreet/instaparse-cljs) ⚠️ Archived – It aims to be the simplest way to build parsers in ClojureScript.
* [Ribol](http://docs.caudate.me/ribol/) – Conditional restarts for clojure/clojurescript.

### Document Object Model

* [Dommy](https://github.com/plumatic/dommy) ⭐ 755 | 🐛 12 | 🌐 Clojure | 📅 2018-01-07 – A no-nonsense ClojureScript templating and DOM manipulation library.
* [Sablono](https://github.com/r0man/sablono) ⭐ 688 | 🐛 16 | 🌐 Clojure | 📅 2020-08-04 – Lisp/Hiccup style templating for Facebook's React in ClojureScript.
* [Hickory](https://github.com/davidsantiago/hickory) ⭐ 678 | 🐛 14 | 🌐 Clojure | 📅 2026-04-20 – It parses HTML into Clojure data structures, so you can analyze, transform, and output back to HTML.
* [Kioo](https://github.com/ckirkendall/kioo) ⭐ 400 | 🐛 11 | 🌐 Clojure | 📅 2018-05-01 – DOM manipulation and templating library for Facebook's React and Om in ClojureScript.
* [Freactive](https://github.com/aaronc/freactive) ⭐ 384 | 🐛 20 | 🌐 Clojure | 📅 2015-11-12 – A high-performance, pure Clojurescript, declarative DOM library inspired by reagent, om, reflex and hiccup.
* [Respo](https://github.com/mvc-works/respo) ⭐ 236 | 🐛 0 | 🌐 Cirru | 📅 2025-08-25 – A responsive DOM library, inspired by React.
* [Crate](https://github.com/ibdknox/crate) ⭐ 223 | 🐛 5 | 🌐 Clojure | 📅 2015-11-02 – A ClojureScript implementation of Hiccup.
* [Hiccups](https://github.com/teropa/hiccups) ⭐ 218 | 🐛 3 | 🌐 Clojure | 📅 2020-11-06 – A ClojureScript port of the Hiccup.
* [json-html](https://github.com/yogthos/json-html) ⭐ 164 | 🐛 0 | 🌐 Clojure | 📅 2020-05-30 – Provide JSON and get a DOM node with a human representation of that JSON.
* [Dominator](https://github.com/dubiousdavid/dominator) ⭐ 73 | 🐛 2 | 🌐 JavaScript | 📅 2015-06-09 – Virtual-Dom in ClojureScript.
* [cljs-binding](https://github.com/fluentsoftware/cljs-binding) ⭐ 57 | 🐛 2 | 🌐 JavaScript | 📅 2012-10-16 – It binds html elements to ClojureScript functions.
* [Enfocus](http://ckirkendall.github.io/enfocus-site/) – A DOM manipulation and templating library for ClojureScript inspired by Enlive.

### Documentation

* [codox](https://github.com/weavejester/codox) ⭐ 686 | 🐛 48 | 🌐 Clojure | 📅 2024-08-14 – A tool for generating API documentation from Clojure or ClojureScript source code.

### Graphics

* [Quil](https://github.com/quil/quil) ⭐ 3,050 | 🐛 47 | 🌐 Clojure | 📅 2026-04-24 – A processing and graphics programming library.
* [geom](https://github.com/thi-ng/geom) ⭐ 997 | 🐛 33 | 🌐 Clojure | 📅 2025-03-22 – A 2D/3D geometry toolkit for Clojure/Clojurescript.

### HTTP Handler

* [Castra](https://github.com/hoplon/castra) ⭐ 172 | 🐛 10 | 🌐 Clojure | 📅 2020-12-24 – An HTTP remote procedure call handler for Clojure.

### Internationalization

* [Tower](https://github.com/ptaoussanis/tower) ⭐ 278 | 🐛 11 | 🌐 Clojure | 📅 2024-03-19 – A Clojure(Script) i18n & L10n library.
* [Tempura](https://github.com/ptaoussanis/tempura) ⭐ 264 | 🐛 6 | 🌐 Clojure | 📅 2024-06-05 – A Clojure(Script) i18n library, succeeding Tower

### JavaScript Interoperability

* [Jayq](https://github.com/ibdknox/jayq) ⭐ 412 | 🐛 0 | 🌐 Clojure | 📅 2018-02-23 – A ClojureScript wrapper for jQuery.
* [Pylon](https://github.com/bodil/pylon) ⭐ 53 | 🐛 1 | 🌐 Clojure | 📅 2013-01-27 – A Javascript class system in 100% Clojurescript.
* [Purnam](https://github.com/zcaudate/purnam) ⭐ 1 | 🐛 0 | 🌐 Clojure | 📅 2018-06-29 – A ClojureScript library designed to provide better clojurescript/javascript interop, testing and documentation tools.
* [CLJSJS](http://cljsjs.github.io/) – An easy way for Clojurescript developers to depend on Javascript libraries.

### CSS tools

* [Garden](https://github.com/noprompt/garden) ⭐ 1,367 | 🐛 45 | 🌐 Clojure | 📅 2024-01-16 – A library for rendering CSS in Clojure and ClojureScript.
* [stylefy](https://github.com/jarzka/stylefy) ⭐ 321 | 🐛 13 | 🌐 Clojure | 📅 2025-07-21 – stylefy makes it possible to define UI component styles as Clojure data and attach them into components easily without writing CSS selectors

### Miscellaneous

* [core.async](https://github.com/clojure/core.async/) ⭐ 2,049 | 🐛 2 | 🌐 Clojure | 📅 2026-06-12 – A Clojure(Script) library designed to provide facilities for async programming and communication.
* [Automat](https://github.com/ztellman/automat) ⚠️ Archived – A Clojure(Script) library for defining and using finite-state automata, inspired by Ragel.
* [markdown-clj](https://github.com/yogthos/markdown-clj) ⭐ 575 | 🐛 21 | 🌐 Clojure | 📅 2026-08-05 – Markdown parser in Clojure/ClojureScript.
* [om-tools](https://github.com/plumatic/om-tools) ⭐ 433 | 🐛 9 | 🌐 Clojure | 📅 2018-07-07 – It aims to provide higher-order abstractions and utilities frequently useful when building components with Om's API.
* [reagent-forms](https://github.com/reagent-project/reagent-forms/) ⭐ 341 | 🐛 9 | 🌐 HTML | 📅 2020-04-27 – Bootstrap form components for Reagent.
* [inflections-clj](https://github.com/r0man/inflections-clj) ⭐ 222 | 🐛 4 | 🌐 Clojure | 📅 2025-08-14 – Rails-like inflection library for Clojure and ClojureScript.
* [reforms](https://github.com/bilus/reforms) ⭐ 168 | 🐛 4 | 🌐 Clojure | 📅 2017-02-08 – Beautiful Bootstrap 3 forms for Om and Reagent.
* [Bardo](https://github.com/pleasetrythisathome/bardo) ⭐ 95 | 🐛 1 | 🌐 Clojure | 📅 2018-10-24 – A Clojure(Script) library for functional interpolation and transitions.
* [Keybind](https://github.com/piranha/keybind) ⭐ 85 | 🐛 0 | 🌐 Clojure | 📅 2017-11-27 – Library for handling key bindings (shortcuts) in browser.
* [Entanglement](https://github.com/Frozenlock/entanglement) ⭐ 42 | 🐛 0 | 🌐 Clojure | 📅 2016-08-22 – It creates atoms from other atoms and links the data together.
* [Sepal.clj](https://github.com/Cirru/sepal.clj) ⭐ 32 | 🐛 0 | 🌐 Cirru | 📅 2025-08-25 – A library to generate Clojure code from a vector of strings and vectors with macro system.
* [namespacefy](https://github.com/Jarzka/namespacefy) ⭐ 21 | 🐛 0 | 🌐 Clojure | 📅 2023-03-11 – A simple Clojure(Script) library which aims to make it easy to keep map keys namespaced, no matter where your data comes from.

### [React.js](https://facebook.github.io/react/) Interface

* [Om](https://github.com/omcljs/om) ⭐ 6,624 | 🐛 81 | 🌐 Clojure | 📅 2020-08-17 – A powerful interface to React, makes use of its object oriented structures.
* [Rum](https://github.com/tonsky/rum) ⭐ 1,826 | 🐛 23 | 🌐 HTML | 📅 2025-04-14 – Decomplected, extensible, simple.
* [re-com](https://github.com/Day8/re-com) ⭐ 823 | 🐛 51 | 🌐 Clojure | 📅 2026-08-02 – A ClojureScript library of reusable components for Reagent.
* [Helix](https://github.com/lilactown/helix) ⭐ 675 | 🐛 15 | 🌐 Clojure | 📅 2026-01-05 – A simple, easy to use library for React development in ClojureScript with very few semantics on top of React.
* [Quiescent](https://github.com/levand/quiescent) ⭐ 609 | 🐛 4 | 🌐 Clojure | 📅 2017-12-11 – It favors functional style, fully stateless.
* [hx](https://github.com/Lokeh/hx) ⭐ 245 | 🐛 12 | 🌐 Clojure | 📅 2026-04-15 – Another simple, easy to use library for React development in ClojureScript.
* [Brutha](https://github.com/weavejester/brutha) ⭐ 139 | 🐛 1 | 🌐 Clojure | 📅 2016-08-19 – A simple and functional ClojureScript interface to React.
* [cljsx](https://github.com/peterhudec/cljsx) ⭐ 14 | 🐛 7 | 🌐 Clojure | 📅 2022-06-22 – [JSX](https://reactjs.org/docs/introducing-jsx.html) for Clojure and ClojureScript, also works with [Inferno](https://infernojs.org), [Nerv](https://nerv.aotu.io/), [Preact](https://preactjs.com/), [Snabbdome](https://github.com/snabbdom/snabbdom) ⭐ 12,398 | 🐛 86 | 🌐 TypeScript | 📅 2026-06-17 and others.
* [Reagent](http://reagent-project.github.io/) – Minimalistic, feature complete.

### Reactive Programming

* [Javelin](https://github.com/hoplon/javelin) ⭐ 825 | 🐛 7 | 🌐 Clojure | 📅 2023-10-31 – A Functional Reactive Programming library for ClojureScript.
* [Reagi](https://github.com/weavejester/reagi) ⭐ 232 | 🐛 4 | 🌐 Clojure | 📅 2016-03-04 – An FRP library for Clojure and ClojureScript, built on top of core.async.
* [Manifold-cljs](https://github.com/dm3/manifold-cljs) ⭐ 50 | 🐛 1 | 🌐 Clojure | 📅 2019-12-20 – A port of [Manifold](https://github.com/ztellman/manifold) ⭐ 1,052 | 🐛 33 | 🌐 Clojure | 📅 2026-03-16 to ClojureScript.
* [rx-cljs](https://github.com/leonardoborges/rx-cljs) ⭐ 44 | 🐛 0 | 🌐 Clojure | 📅 2013-05-21 – A ClojureScript wrapper for Reactive Extensions (Rx) for Javascript.
* [Yolk](https://github.com/Cicayda/yolk) – A thin ClojureScript wrapper around bacon.js.

### Routing

* [Bidi](https://github.com/juxt/bidi) ⭐ 998 | 🐛 60 | 🌐 Clojure | 📅 2023-03-15 – A Clojure(script) data driven routing library.
* [Secretary](https://github.com/gf3/secretary) ⭐ 773 | 🐛 23 | 🌐 Clojure | 📅 2020-12-13 – A client-side router for ClojureScript.
* [Silk](https://github.com/DomKM/silk) ⭐ 224 | 🐛 4 | 🌐 Clojure | 📅 2022-01-04 – An isomorphic routing library for Clojure & ClojureScript.
* [Router](https://github.com/darkleaf/router) ⭐ 80 | 🐛 0 | 🌐 Clojure | 📅 2017-04-30 – Bidirectional Ring router for Clojure/Script. REST oriented.

### State Management

* [component](https://github.com/stuartsierra/component) ⭐ 2,160 | 🐛 3 | 🌐 Clojure | 📅 2025-10-25 – Managed lifecycle of stateful objects in Clojure(Script).
* [mount](https://github.com/tolitius/mount) ⭐ 1,255 | 🐛 30 | 🌐 Clojure | 📅 2026-06-11 – A beautifl idiomatic state management library.
* [storage-atom](https://github.com/alandipert/storage-atom) ⭐ 194 | 🐛 10 | 🌐 Clojure | 📅 2022-10-28 – ClojureScript atoms backed by HTML5 web storage.
* [Waltz](https://github.com/ibdknox/waltz) ⭐ 90 | 🐛 2 | 🌐 Clojure | 📅 2012-04-10 – A ClojureScript library that helps manage state in client-side applications using non-deterministic finite state machines.
* [plato](https://github.com/eneroth/plato) ⭐ 30 | 🐛 1 | 🌐 Clojure | 📅 2014-12-11 – Incrementally persists atom state to Local Storage in ClojureScript.
* [Tuck](https://github.com/tatut/tuck) ⭐ 30 | 🐛 0 | 🌐 Clojure | 📅 2020-08-28 – A micro framework for building Reagent apps that have a clean separation of view code and event processing code.
* [hodgepodge](http://funcool.github.io/hodgepodge/) – A idiomatic ClojureScript interface to HTML5 Storage.

### Testing

* [cljs.test](https://github.com/clojure/clojurescript/wiki/Testing) ⭐ 9,390 | 🐛 7 | 🌐 Clojure | 📅 2026-08-10 – Integrated test framework for ClojureScript (merged from [clojurescript.test](https://github.com/cemerick/clojurescript.test) ⭐ 164 | 🐛 1 | 🌐 Clojure | 📅 2015-11-25)
* [test.check](https://github.com/clojure/test.check) ⭐ 1,151 | 🐛 0 | 🌐 Clojure | 📅 2025-12-30 – A generative property-based testing tool inspired by QuickCheck.
* [Speclj](https://github.com/slagyr/speclj) ⭐ 488 | 🐛 29 | 🌐 Clojure | 📅 2026-04-30 – A TDD/BDD framework for Clojure and ClojureScript.
* [Expectations](http://jayfields.com/expectations/) – A minimalist's unit testing framework.

### Validation

* [Bouncer](https://github.com/leonardoborges/bouncer) ⭐ 361 | 🐛 10 | 🌐 Clojure | 📅 2021-07-12 – A validation DSL for Clojure & Clojurescript applications.
* [form-validator-cljs](https://github.com/kwladyka/form-validator-cljs) ⭐ 55 | 🐛 0 | 🌐 Clojure | 📅 2019-11-22 – Validate forms with spec and fn.
* [Validateur](http://clojurevalidations.info/) – A Clojure validation library inspired by Ruby's ActiveModel.

### Web Framework & Template

* [re-frame](https://github.com/Day8/re-frame) ⭐ 5,541 | 🐛 23 | 🌐 Clojure | 📅 2026-05-05 – A Reagent Framework For Writing SPAs, in Clojurescript.
* [Chestnut](https://github.com/plexus/chestnut) ⚠️ Archived – An Application template for ClojureScript/Om with live reloading.
* [Precept](https://github.com/CoNarrative/precept) ⭐ 662 | 🐛 38 | 🌐 Clojure | 📅 2022-12-06 – A declarative programming framework.
* [descjop](https://github.com/karad/lein_template_descjop) ⚠️ Archived – A template for Web based desktop application with Electron.
* [Macchiato](https://github.com/macchiato-framework/macchiato-core) ⭐ 385 | 🐛 16 | 🌐 Clojure | 📅 2025-12-31 – It aims to provide an easy to use platform for Node.js.
* [Mies](https://github.com/swannodette/mies) ⭐ 367 | 🐛 2 | 🌐 Clojure | 📅 2018-07-05 – A minimal ClojureScript project template.
* [WebFUI](https://github.com/drcode/webfui) ⭐ 237 | 🐛 4 | 🌐 Clojure | 📅 2013-01-30 – Client-Side Web Framework for ClojureScript.
* [Clops](https://github.com/sveri/closp) ⭐ 175 | 🐛 0 | 🌐 Clojure | 📅 2020-12-31 – An opinionated, full stack and easy to use web framework.
* [electron-template](https://github.com/ducky427/electron-template) ⭐ 116 | 🐛 3 | 🌐 JavaScript | 📅 2016-03-15 – A template for creating web based desktop applications with Electron, ClojureScript and Reagent.
* [atw-om](https://github.com/zaiste/atw-om) ⭐ 41 | 🐛 0 | 🌐 Clojure | 📅 2014-12-26 – A web application template with Clojure/Compojure, ClojureScript/Om & core.async.
* [Fulcro](http://fulcrologic.github.io/fulcro) – A library for development of single-page full-stack web applications in clj/cljs.
* [Hoplon](http://hoplon.io) – Write everything in Clojure and ClojureScript, clientside and serverside.
* [Keechma](http://keechma.com) – Micro frontend framework for ClojureScript and Reagent.
* [Luminus](http://www.luminusweb.net/) – It aims to provide a robust, scalable, and easy to use platform.
* [Mr-Clean](https://bitbucket.org/sonwh98/mr-clean) – A reagent compatible library without react.js dependency.
* [Tenzing](http://martinklepsch.github.io/tenzing/) – A ClojureScript template with no backend that uses Boot.

### WebSockets

* [Sente](https://github.com/ptaoussanis/sente) ⭐ 1,789 | 🐛 3 | 🌐 Clojure | 📅 2026-08-06 – Clojure(Script) + core.async + WebSockets/Ajax.
* [Chord](https://github.com/jarohen/chord) ⭐ 442 | 🐛 7 | 🌐 Clojure | 📅 2020-07-12 – Designed to bridge the gap between the triad of CLJ/CLJS, web-sockets and core.async.

***

## Contributing

All contributions are welcome. Please read [Contributing](CONTRIBUTING.md) before opening a pull request. tl;dr `-` is for bullets, `–` is for seperators between the link and the description and lists should be alphabetically ordered.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

[Han Tuzun](http://hantuzun.com) has dedicated the work to the public domain by waiving all of his rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
