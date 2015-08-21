# Awesome JavaScript

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
* [Package Managers](#package-managers)
* [Loaders](#loaders)
* [Bundlers](#bundlers)
* [Testing Frameworks](#testing-frameworks)
* [QA Tools](#qa-tools)
* [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
* [Non-MVC Frameworks](#non-mvc-frameworks)
* [Templating Engines](#templating-engines)
* [Data Visualization](#data-visualization)
* [Timeline](#timeline)
* [Editors](#editors)
* Utilities
* [Files](#files)
* [Functional Programming](#functional-programming)
* [Reactive Programming](#reactive-programming)
* [Data Structure](#data-structure)
* [Date](#date)
* [String](#string)
* [Number](#number)
* [Storage](#storage)
* [Color](#color)
* [I18n And L10n](#i18n-and-l10n)
* [Class](#class)
* [Control Flow](#control-flow)
* [Routing](#routing)
* [Security](#security)
* [Log](#log)
* [RegExp](#regexp)
* [Media](#media)
* [Voice Command](#voice-command)
* [API](#api)
* [Vision Detection](#vision-detection)
* [Browser Detection](#browser-detection)
* UI
* [Code Highlighting](#code-highlighting)
* [Loading Status](#loading-status)
* [Validation](#validation)
* [Keyboard Wrappers](#keyboard-wrappers)
* [Tours And Guides](#tours-and-guides)
* [Notifications](#notifications)
* [Sliders](#sliders)
* [Range Sliders](#range-sliders)
* [Form Widgets](#form-widgets)
* [Tips](#tips)
* [Modals and Popups](#modals-and-popups)
* [Scroll](#scroll)
* [Menu](#menu)
* [Table/Grid](#tablegrid)
* [Frameworks](#frameworks-1)
* Mobile
* [Gesture](#gesture)
* [Maps](#maps)
* [Animations](#animations)
* [Image processing](#image-processing)
* [ES6](#es6)
* [SDK](#sdk)
* [Misc](#misc)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----


## Package Managers
*Host the javascript libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - npm is the package manager for javascript.
* [Bower](https://github.com/bower/bower) - A package manager for the web. [**12,752**]
* [component](https://github.com/component/component) - Client package management for building better web applications. [**4,301**]
* [spm](https://github.com/spmjs/spm) - Brand new static package manager. [**747**]
* [jam](https://github.com/caolan/jam) - A package manager using a browser-focused and RequireJS compatible repository. [**1,482**]
* [jspm](https://github.com/jspm/jspm-cli) - Frictionless browser package management. [**1,827**]
* [Ender](https://github.com/ender-js/Ender) - The no-library library. [**1,740**]
* [volo](https://github.com/volojs/volo) - Create front end projects from templates, add dependencies, and automate the resulting projects. [**1,215**]
* [Duo](https://github.com/duojs/duo) - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless. [**3,260**]


## Loaders
*Module or loading system for JavaScript.*

* [RequireJS](https://github.com/jrburke/requirejs) - A file and module loader for JavaScript. [**8,011**]
* [browserify](https://github.com/substack/node-browserify) - Browser-side require() the node.js way. [**8,005**]
* [SeaJS](https://github.com/seajs/seajs) - A Module Loader for the Web. [**4,400**]
* [HeadJS](https://github.com/headjs/headjs) - The only script in your HEAD. [**3,777**]
* [curl](https://github.com/cujojs/curl) - A small, fast, extensible module loader that handles AMD, CommonJS Modules/1.1, CSS, HTML/text, and legacy scripts. [**1,487**]
* [lazyload](https://github.com/rgrove/lazyload/) - Tiny, dependency-free async JavaScript and CSS loader. [**987**]
* [script.js](https://github.com/ded/script.js) - Asyncronous JavaScript loader and dependency manager. [**1,566**]
* [systemjs](https://github.com/systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader. [**3,468**]
* [LodJS](https://github.com/yanhaijing/lodjs) - Module loader based on AMD [**132**]
* [ESL](https://github.com/ecomfe/esl) - Module loader browser first, support lazy define and AMD. [**396**]


## Bundlers

* [browserify](https://github.com/substack/node-browserify) - Browserify lets you require('modules') in the browser by bundling up all of your dependencies. [**8,005**]
* [webpack](https://github.com/webpack/webpack) - Packs CommonJs/AMD modules for the browser. [**7,294**]


## Testing Frameworks

### Frameworks

* [mocha](https://github.com/visionmedia/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser. [**7,232**]
* [jasmine](https://github.com/pivotal/jasmine) - DOM-less simple JavaScript testing framework. [**9,311**]
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework. [**3,230**]
* [jest](http://github.com/facebook/jest) - Painless Javascript Unit Testing. [**2,822**]
* [prova](http://github.com/azer/prova) - Node & Browser test runner based on Tape and Browserify [**264**]
* [DalekJS](https://github.com/dalekjs/dalek) - Automated cross browser functional testing with JavaScript [**594**]

### Assertion

* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework. [**2,020**]
* [Sinon.JS](https://github.com/cjohansen/Sinon.JS) - Test spies, stubs, and mocks for JavaScript. [**2,229**]
* [expect.js](https://github.com/LearnBoost/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser. [**1,128**]

### Coverage

* [istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool. [**2,961**]
* [blanket](https://github.com/alex-seville/blanket) - A simple code coverage library for javascript. Designed to be easy to install and use, for both browser and nodejs. [**1,083**]
* [JSCover](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs. [**272**]

### Runner

* [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit. [**14,963**]
* [slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko. [**1,490**]
* [casperjs](https://github.com/n1k0/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS. [**4,626**]
* [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js. [**3,257**]
* [totoro](https://github.com/totorojs/totoro) - A simple and stable cross-browser testing tool. [**463**]
* [karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript. [**5,551**]
* [nightwatch](https://github.com/beatfactor/nightwatch) - UI automated testing framework based on node.js and selenium webdriver. [**3,153**]
* [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript. [**2,977**]
* [yolpo](http://www.yolpo.com) - A statement-by-statement javascript interpreter in the browser.


## QA Tools

* [JSHint](https://github.com/jshint/jshint/) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code. [**5,386**]
* [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker. [**3,984**]
* [jsfmt](https://github.com/rdio/jsfmt) - For formatting, searching, and rewriting JavaScript. [**1,502**]
* [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code. [**855**]
* [buddy.js](https://github.com/danielstjules/buddy.js) - Magic number detection for JavaScript. [**401**]
* [ESLint](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript. [**2,740**]
* [JSLint](https://github.com/douglascrockford/JSLint) - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language. [**2,386**]


## MVC Frameworks and Libraries

* [angular.js](https://github.com/angular/angular.js) - HTML enhanced for web apps. [**41,791**]
* [backbone](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events. [**22,724**]
* [batman.js](http://batmanjs.org/) - The best JavaScript framework for Rails developers.
* [ember.js](https://github.com/emberjs/ember.js) - A JavaScript framework for creating ambitious web applications. [**14,563**]
* [meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. [**27,496**]
* [ractive](https://github.com/ractivejs/ractive) - Next-generation DOM manipulation. [**4,254**]
* [vue](https://github.com/yyx990803/vue) - Intuitive, fast & composable MVVM for building interactive interfaces. [**6,286**]
* [knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript. [**6,665**]
* [spine](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications. [**3,104**]
* [espresso.js](https://github.com/techlayer/espresso.js) - A minimal javascript library for crafting user interfaces. [**514**]
* [canjs](https://github.com/bitovi/canjs) - Can do JS, better, faster, easier. [**1,198**]
* [react](https://facebook.github.io/react/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [react-native](https://github.com/facebook/react-native) - A framework for building native apps with React. [**16,766**]
* [riot](https://github.com/riot/riot) - React-like library, but with very small size. [**7,090**]
* [thorax](https://github.com/walmartlabs/thorax) - Strengthening your Backbone. [**1,350**]
* [chaplin](https://github.com/chaplinjs/chaplin) - An architecture for JavaScript applications using the Backbone.js library. [**2,934**]
* [marionette](https://github.com/marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications. [**6,400**]
* [ripple](https://github.com/ripplejs/ripple) - A tiny foundation for building reactive views. [**1,229**]
* [rivets](https://github.com/mikeric/rivets) - Lightweight and powerful data binding + templating solution. [**2,443**]
* [derby](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers. [**3,780**]
* [derby-awesome](https://github.com/onerussell/awesome-derby) - A collection of awesome derby components [**8**]
* [way.js](https://github.com/gwendall/way.js) - Simple, lightweight, persistent two-way databinding. [**2,494**]
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast). [**4,111**]
* [jsblocks](https://github.com/astoilkov/jsblocks) - jsblocks is better MV-ish framework. [**2,519**]
* [LiquidLava](http://www.lava-framework.com/) - Transparent MVC framework for building user interfaces.


## Non-MVC Frameworks

* [famous](https://github.com/Famous/famous) - A JavaScript framework for everyone who wants to build beautiful experiences on any device. [**7,013**]


## Templating Engines
*Templating engines allow you to perform string interpolation.*

* [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript. [**8,141**]
* [handlebars.js](https://github.com/wycats/handlebars.js/) - An extension to the Mustache templating language. [**8,809**]
* [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language. [**4,091**]
* [doT](https://github.com/olado/doT) - The fastest + concise javascript template engine for nodejs and browsers. [**2,255**]
* [dustjs](https://github.com/linkedin/dustjs/) - Asynchronous templates for the browser and node.js. [**1,959**]
* [eco](https://github.com/sstephenson/eco/) - Embedded CoffeeScript templates. [**1,738**]
* [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies. [**707**]
* [t.js](https://github.com/jasonmoo/t.js) - A tiny javascript templating framework in ~400 bytes gzipped. [**689**]
* [Jade](https://github.com/jadejs/jade) - Robust, elegant, feature rich template engine for nodejs. [**8,964**]
* [EJS](https://github.com/mde/ejs) - Effective JavaScript templating. [**245**]
* [xtemplate](https://github.com/xtemplate/xtemplate) - eXtensible Template Engine lib for node and the browser [**83**]
* [marko](https://github.com/marko-js/marko) - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output. [**461**]

## Data Visualization
*Data visualization tools for the web.*

* [d3](https://github.com/mbostock/d3) - A JavaScript visualization library for HTML and SVG. [**40,825**]
* [metrics-graphics](https://github.com/mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts. [**5,159**]
* [pykcharts.js](https://github.com/pykih/PykCharts.js) - Well designed d3.js charting without the complexity of d3.js. [**149**]
* [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D library. [**20,765**]
* [Chart.js](https://github.com/nnnick/Chart.js) - Simple HTML5 Charts using the <canvas> tag. [**15,837**]
* [paper.js](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas. [**5,406**]
* [fabric.js](https://github.com/kangax/fabric.js) - Javascript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser. [**4,703**]
* [peity](https://github.com/benpickles/peity) - Progressive <svg> bar, line and pie charts. [**3,170**]
* [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library. [**7,483**]
* [echarts](https://github.com/ecomfe/echarts) - Enterprise Charts. [**7,818**]
* [vis](https://github.com/almende/vis) - Dynamic, browser-based visualization library. [**2,996**]
* [two.js](https://github.com/jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web. [**4,378**]
* [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) - Charts for Raphaël. [**1,493**]
* [sigma.js](https://github.com/jacomyal/sigma.js) - A JavaScript library dedicated to graph drawing. [**4,905**]
* [arbor](https://github.com/samizdatco/arbor) - A graph visualization library using web workers and jQuery. [**2,098**]
* [cubism](https://github.com/square/cubism) - A D3 plugin for visualizing time series. [**3,998**]
* [dc.js](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js [**4,250**]
* [vega](https://github.com/trifacta/vega) - A visualization grammar. [**3,196**]
* [envisionjs](https://github.com/HumbleSoftware/envisionjs) - Dynamic HTML5 visualization. [**1,446**]
* [rickshaw](https://github.com/shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs. [**5,384**]
* [flot](https://github.com/flot/flot) - Attractive JavaScript charts for jQuery. [**4,531**]
* [morris.js](https://github.com/morrisjs/morris.js) - Pretty time-series line graphs. [**5,459**]
* [nvd3](https://github.com/novus/nvd3) - Build re-usable charts and chart components for d3.js [**4,061**]
* [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG. [**3,030**]
* [heatmap.js](https://github.com/pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps. [**3,028**]
* [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) - A plugin for the jQuery javascript library to generate small sparkline charts directly in the browser. [**824**]
* [xCharts](https://github.com/tenxer/xCharts) - A D3-based library for building custom charts and graphs. [**1,729**]
* [trianglify](https://github.com/qrohlf/trianglify) - Low poly style background generator with d3.js [**5,058**]
* [d3-cloud](https://github.com/jasondavies/d3-cloud) - Create word clouds in JavaScript. [**1,227**]
* [d4](https://github.com/heavysixer/d4) - A friendly reusable charts DSL for D3. [**242**]
* [dimple.js](http://dimplejs.org) -  Easy charts for business analytics powered by d3
* [chartist-js](https://github.com/gionkunz/chartist-js) - Simple responsive charts. [**6,693**]
* [epoch](https://github.com/fastly/epoch) - A general purpose real-time charting library. [**4,207**]
* [c3](https://github.com/masayuki0812/c3) - D3-based reusable chart library. [**4,631**]
* [BabylonJS](https://github.com/BabylonJS/Babylon.js) - A framework for building 3D games with HTML 5 and WebGL. [**2,353**]

There're also some great commercial libraries, like [amchart](http://www.amcharts.com/), [plotly](https://www.plot.ly/), and [highchart](http://www.highcharts.com/).


## Timeline

* [TimelineJS](https://github.com/NUKnightLab/TimelineJS) - A Storytelling Timeline built in JavaScript. [**7,792**]
* [timesheet.js](https://github.com/semu/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets. [**11**]


## Editors

* [ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor). [**11,143**]
* [CodeMirror](https://github.com/marijnh/CodeMirror) - In-browser code editor. [**7,317**]
* [esprima](https://github.com/ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis. [**150**]
* [quill](https://github.com/quilljs/quill) - A cross browser rich text editor with an API. [**5,396**]
* [medium-editor](https://github.com/daviferreira/medium-editor) - Medium.com WYSIWYG editor clone. [**5,426**]
* [pen](https://github.com/sofish/pen) - enjoy live editing (+markdown). [**3,390**]
* [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium. [**1,625**]
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor. [**4,633**]
* [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) - The best web text editor for everyone. [**257**]
* [editor](https://github.com/lepture/editor) - A markdown editor. still on development. [**1,638**]
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more. [**4,017**]
* [jsoneditor](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit and format JSON. [**1,697**]
* [vim.js](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim with a persistent ~/.vimrc [**3,435**]
* [Squire](https://github.com/neilj/Squire) - HTML5 rich text editor. [**2,984**]
* [TinyMCE](https://github.com/tinymce/tinymce) - The JavaScript Rich Text editor. [**2,417**]


## Files
*Libraries for working with files.*

* [Papa Parse](https://github.com/mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV. [**2,218**]
* [jBinary](https://github.com/jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures. [**240**]


## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

* [underscore](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt. [**15,544**]
* [lodash](https://github.com/lodash/lodash) - A utility library delivering consistency, customization, performance, & extras. [**10,633**]
* [Sugar](https://github.com/andrewplummer/Sugar) - A Javascript library for working with native objects. [**2,846**]
* [lazy.js](https://github.com/dtao/lazy.js) - Like Underscore, but lazier. [**2,945**]
* [ramda](https://github.com/CrossEye/ramda) - A practical functional library for Javascript programmers. [**13**]
* [mout](https://github.com/mout/mout) - Modular JavaScript Utilities. [**643**]
* [mesh](https://github.com/mojo-js/mesh.js) - Streamable data synchronization utility. [**944**]


## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

* [RxJs](https://github.com/Reactive-Extensions/RxJS) - The Reactive Extensions for JavaScript. [**5,131**]
* [Bacon](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for Javascript. [**4,503**]
* [Kefir](https://github.com/pozadi/kefir) - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption. [**1**]


## Data Structure
*Data structure libraries to build a more sophisticated application.*

* [immutable-js](https://github.com/facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector. [**8,012**]
* [mori](https://github.com/swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript. [**1,713**]
* [buckets](https://github.com/mauriciosantos/buckets) - A complete, fully tested and documented data structure library written in JavaScript. [**469**]
* [hashmap](https://github.com/flesler/hashmap) - Simple hashmap implementation that supports any kind of keys. [**168**]


## Date
*Date Libraries.*

* [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript. [**22,212**]
* [moment-timezone](https://github.com/moment/moment-timezone) - Timezone support for moment.js. [**1,217**]
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago"). [**3,099**]
* [timezone-js](https://github.com/mde/timezone-js) - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data. [**687**]
* [date](https://github.com/MatthewMueller/date) - Date() for humans. [**1,033**]
* [ms.js](https://github.com/guille/ms.js) - Tiny millisecond conversion utility. [**267**]


## String
*String Libraries.*

* [selecting](https://github.com/EvandroLG/selecting) - A library that allows you to access the text selected by the user [**21**]
* [underscore.string](https://github.com/epeli/underscore.string) - String manipulation extensions for Underscore.js javascript library. [**2,762**]
* [string.js](https://github.com/jprichardson/string.js) - Extra JavaScript string methods. [**1,035**]
* [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript. [**509**]
* [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript. [**1,271**]
* [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings. [**259**]
* [URI.js](https://github.com/medialize/URI.js/) - Javascript URL mutation library. [**3,419**]
* [jsurl](https://github.com/Mikhus/jsurl) - Lightweight URL manipulation with JavaScript. [**218**]
* [sprintf.js](https://github.com/alexei/sprintf.js) - A sprintf implementation. [**844**]


## Number

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers. [**3,470**]
* [odometer](https://github.com/HubSpot/odometer) - Smoothly transitions numbers with ease. [**4,458**]
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies. [**6**]
* [money.js](https://github.com/josscrowcroft/money.js) - A tiny (1kb) javascript currency conversion library, for web & nodeJS. [**3**]


## Storage

* [store.js](https://github.com/marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood. [**3,663**]
* [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API. [**4,635**]
* [jStorage](https://github.com/andris9/jStorage) - jStorage is a simple key/value database to store data on browser side. [**1,329**]
* [cross-storage](https://github.com/zendesk/cross-storage) - Cross domain local storage, with permissions. [**573**]
* [basket.js](https://github.com/addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage. [**2,246**]
* [bag.js](https://github.com/nodeca/bag.js) - A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support. [**38**]
* [basil.js](https://github.com/Wisembly/basil.js) - The missing Javascript smart persistent layer. [**1,585**]
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies. [**7,424**]
* [Cookies](https://github.com/ScottHamper/Cookies) - JavaScript Client-Side Cookie Manipulation Library. [**1,328**]
* [DB.js] (https://github.com/aaronpowell/db.js/) - Promise based IndexDB Wrapper library [**410**]


## Color

* [randomColor](https://github.com/davidmerfield/randomColor) - A color generator for JavaScript. [**2,754**]
* [chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations. [**2,528**]
* [color](https://github.com/harthur/color) - JavaScript color conversion and manipulation library. [**824**]
* [colors](https://github.com/mrmrs/colors) - Smarter defaults for colors on the web. [**6,124**]
* [PleaseJS](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes. [**1,676**]
* [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript. [**794**]
* [Vibrant.js] (https://github.com/jariz/vibrant.js/) - Extract prominent colors from an image. [**3,235**]

## I18n And L10n
*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* [i18next](https://github.com/jamuhl/i18next) - internationalisation (i18n) with javascript the easy way. [**1,077**]
* [polyglot](https://github.com/airbnb/polyglot.js) - tiny i18n helper library. [**1,348**]
* [babelfish](https://github.com/nodeca/babelfish/) - i18n with human friendly API and built in plurals support. [**111**]

## Class

* [ClassManager](https://github.com/kogarashisan/ClassManager) - One of the fastest and most convenient class systems in the world [**27**]
* [klass](https://github.com/ded/klass) - A utility for creating expressive classes in JavaScript. [**632**]
* [augment](https://github.com/javascript/augment) - The world's smallest and fastest classical JavaScript inheritance pattern. [**870**]


## Control Flow

* [async](https://github.com/caolan/async) - Async utilities for node and the browser. [**14,168**]
* [q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript. [**9,468**]
* [step](https://github.com/creationix/step/) - An async control-flow library that makes stepping through logic easy. [**1,918**]
* [contra](https://github.com/bevacqua/contra/) - Asynchronous flow control with a functional taste to it. [**503**]
* [Bluebird](https://github.com/petkaantonov/bluebird/) - fully featured promise library with focus on innovative features and performance. [**7,553**]
* [when](https://github.com/cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies. [**2,582**]
* [ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) - Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers). [**4**]


## Routing

* [director](https://github.com/flatiron/director) - A tiny and isomorphic URL router for JavaScript. [**3,014**]
* [page.js](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes). [**2,730**]
* [pathjs](https://github.com/mtrpcic/pathjs) - Simple, lightweight routing for web browsers. [**853**]
* [crossroads](https://github.com/millermedeiros/crossroads.js) - JavaScript Routes. [**1,079**]
* [davis.js](https://github.com/olivernn/davis.js) - RESTful degradable JavaScript routing using pushState. [**539**]


## Security

* [DOMPurify](https://github.com/cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG. [**502**]
* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist. [**615**]


## Log

* [log](https://github.com/adamschwartz/log) - Console.log with style. [**2,221**]
* [Conzole](https://github.com/Oaxoa/Conzole) - A debug panel built in javascript that wraps javascript native console object methods and functionality in a panel displayed inside the page. [**172**]
* [console.log-wrapper](https://github.com/patik/console.log-wrapper) - Log to the console in any browser with clarity. [**332**]
* [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods. [**410**]


## RegExp
* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.

## Media

* [Ion.Sound](https://github.com/IonDen/ion.sound) - Simple sounds on any web page [**408**]


## Voice Command

* [annyang](https://github.com/TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition. [**2,193**]
* [voix.js](https://github.com/pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games. [**406**]


## API

* [bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy. [**114**]
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - JavaScript OAuth 1.0a signature generator for node and the browser. [**94**]
* [amygdala](https://github.com/lincolnloop/amygdala) - RESTful HTTP client for JavaScript powered web applications. [**329**]
* [jquery.rest](https://github.com/jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs. [**400**]


## Vision Detection

* [tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web. [**2,938**]
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten. [**1,830**]


## Browser Detection

* [bowser](https://github.com/ded/bowser) - a browser detector [**982**]


## Code highlighting

* [Highlight.js](https://github.com/isagalaev/highlight.js) - Javascript syntax highlighter. [**5,776**]
* [PrismJS](https://github.com/LeaVerou/prism) - Lightweight, robust, elegant syntax highlighting. [**2,381**]


## Loading Status
*Libraries for indicate load status.*

* [Mprogress.js](https://github.com/lightningtgc/MProgress.js) - Create Google Material Design progress linear bars. [**1,335**]
* [NProgress](http://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.
* [Spin.js](https://github.com/fgnass/spin.js) - A spinning activity indicator. [**7,567**]
* [progress.js](https://github.com/usablica/progress.js) - Create and manage progress bar for every objects on the page. [**1,585**]
* [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - Beautiful and responsive progress bars with animated SVG paths. [**3,879**]
* [pace](https://github.com/HubSpot/pace) - Automatically add a progress bar to your site. [**8,000**]
* [topbar](https://github.com/buunguyen/topbar) - Tiny & beautiful site-wide progress indicator. [**72**]
* [nanobar](https://github.com/jacoborus/nanobar) - Very lightweight progress bars. No jQuery. [**1,758**]
* [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) - Modern ways of revealing new content using SVG animations. [**449**]
* [SpinKit](https://github.com/tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS. [**9,448**]
* [Ladda](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators. [**5,750**]
* [css-loaders](https://github.com/lukehaas/css-loaders) - A collection of loading spinners animated with CSS. [**3,581**]

Besides libraries, there're [Collection on Codepen](http://codepen.io/collection/HtAne/), and generators like [Ajaxload](http://www.ajaxload.info/), [Preloaders](http://preloaders.net/) and [CSSLoad](http://cssload.net/).


## Validation

* [Parsley.js](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of javascript. [**6,280**]
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin. [**5,424**]
* [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization. [**3,942**]
* [validate.js](https://github.com/rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter. [**1,485**]
* [validatr](https://github.com/jaymorrow/validatr/) - Cross Browser HTML5 Form Validation. [**257**]
* [BootstrapValidator](https://github.com/nghuuphuoc/bootstrapvalidator) - The best jQuery plugin to validate form fields. Designed to use with Bootstrap 3. [**73**]
* [is.js](https://github.com/arasatasaygin/is.js) -  Check types, regexps, presence, time and more. [**6,049**]
* [FieldVal](https://github.com/FieldVal/fieldval-js) - multipurpose validation library. Supports both sync and async validation. [**133**]


## Keyboard Wrappers

* [mousetrap](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in Javascript. [**6,175**]
* [keymaster](https://github.com/madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts. [**4,829**]
* [Keypress](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key. [**2,619**]
* [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts. [**1,010**]
* [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination. [**2,070**]
* [jwerty](https://github.com/keithamus/jwerty) - Awesome handling of keyboard events. [**1,007**]


## Tours And Guides

* [intro.js](https://github.com/usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project. [**9,530**]
* [shepherd](https://github.com/HubSpot/shepherd) - Guide your users through a tour of your app. [**2,726**]
* [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers. [**2,922**]
* [tourist](https://github.com/easelinc/tourist) - Simple, flexible tours for your app. [**1,027**]
* [chardin.js](https://github.com/heelhook/chardin.js) - Simple overlay instructions for your apps. [**4,171**]
* [pageguide](https://github.com/tracelytics/pageguide) - An interactive guide for web page elements using jQuery and CSS3. [**808**]
* [hopscotch](https://github.com/linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages. [**2,699**]
* [joyride](https://github.com/zurb/joyride) - jQuery feature tour plugin. [**1,175**]


## Notifications

* [messenger](https://github.com/HubSpot/messenger) - Growl-style alerts and messages for your app. [**3,304**]
* [noty](https://github.com/needim/noty) - jQuery notification plugin. [**4,067**]
* [pnotify](https://github.com/sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft. [**2,266**]
* [toastr](https://github.com/CodeSeven/toastr) - Simple javascript toast notifications. [**3,476**]
* [humane-js](https://github.com/wavded/humane-js) - A simple, modern, browser notification system. [**1,850**]
* [smoke.js](https://github.com/hxgf/smoke.js) - Framework-agnostic styled alert system for javascript. [**878**]


## Sliders

* [Swiper](https://github.com/nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions. [**5,564**]
* [slick](https://github.com/kenwheeler/slick) - The last carousel you'll ever need. [**11,536**]
* [slidesJs](http://www.slidesjs.com) - Is a ressponsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions
* [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin. [**3,893**]
* [unslider](https://github.com/idiot/unslider) - The simplest jQuery slider there is. [**2,201**]
* [colorbox](https://github.com/jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery. [**4,072**]
* [fancyBox](https://github.com/fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages. [**3,282**]
* [sly](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support. [**2,197**]
* [vegas](https://github.com/jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows. [**1,148**]
* [Sequence](https://github.com/IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications. [**2,450**]
* [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) - Simple and easy to use lightbox script written in pure JavaScript. [**494**]
* [reveal.js](https://github.com/hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML. [**22,970**]
* [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent. [**9,024**]
* [jcSlider](https://github.com/JoanClaret/jcSlider) - A responsive slider jQuery plugin with CSS animations. [**21**]


## Range Sliders

* [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support. [**719**]
* [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) - A javascript slider selector that supports dates. [**618**]
* [noUiSlider](https://github.com/leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat. [**1,475**]
* [rangeslider.js](https://github.com/andreruffert/rangeslider.js) - HTML5 input range slider element polyfill. [**927**]


## Form Widgets

### Input

* [typeahead.js](https://github.com/twitter/typeahead.js) - A fast and fully-featured autocomplete library. [**10,710**]
* [tag-it](https://github.com/aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete. [**1,826**]
* [At.js](https://github.com/ichord/At.js) - Add Github like mentions autocomplete to your application. [**3,541**]
* [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute. [**715**]
* [fancyInput](https://github.com/yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects. [**1,802**]
* [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin. [**1,565**]
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - A pure javascript mask input. [**417**]
* [Ion.CheckRadio](https://github.com/IonDen/ion.checkRadio) - jQuery plugin for styling checkboxes and radio-buttons. With skin support. [**39**]

### Calendar

* [pickadate.js](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker. [**5,513**]
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode. [**6,825**]
* [Pikaday](https://github.com/dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS. [**2,900**]
* [fullcalendar](https://github.com/arshaw/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin). [**4,582**]
* [rome](https://github.com/bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI. [**2,030**]

### Select

* [selectize.js](https://github.com/brianreavis/selectize.js) - Selectize is the hybrid of a textbox and select box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc. [**6,573**]
* [select2](https://github.com/ivaynberg/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results. [**14,768**]
* [chosen](https://github.com/harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly. [**18,134**]

### File Uploader

* [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery. [**21,088**]
* [dropzone](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars. [**8,474**]
* [flow.js](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API. [**1,700**]
* [fine-uploader](https://github.com/Widen/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading. [**5,499**]
* [FileAPI](https://github.com/mailru/FileAPI) - A set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF. [**2,372**]
* [plupload](https://github.com/moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash. [**3,111**]

### Other

* [form](https://github.com/malsup/form) - jQuery Form Plugin. [**3,133**]
* [Garlic.js](https://github.com/guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted. [**1,963**]
* [Countable](https://github.com/RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element. [**1,309**]
* [card](https://github.com/jessepollak/card) - Make your credit card form better in one line of code. [**5,795**]
* [stretchy](https://github.com/LeaVerou/stretchy) - Form element autosizing, the way it should be. [**749**]


## Tips

* [tipsy](https://github.com/jaz303/tipsy) - Facebook-style tooltips plugin for jQuery. [**1,900**]
* [opentip](https://github.com/enyo/opentip) - An open source javascript tooltip based on the prototype framework. [**1,063**]
* [qTip2](https://github.com/qTip2/qTip2) - Pretty powerful tooltips. [**1,711**]
* [tooltipster](https://github.com/iamceege/tooltipster) - A jQuery tooltip plugin. [**1,421**]
* [simptip](https://github.com/arashmanteghi/simptip) - A simple CSS tooltip made with Sass. [**596**]
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips. [**234**]


## Modals and Popups

* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance. [**6,735**]
* [jquery-popbox](https://github.com/gristmill/jquery-popbox) - jQuery PopBox UI Element. [**434**]
* [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups. [**1,677**]
* [vex](https://github.com/HubSpot/vex) - A modern dialog library which is highly configurable and easy to style. [**4,499**]
* [bootstrap-modal](https://github.com/jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more. [**4,480**]
* [css-modal](https://github.com/drublic/css-modal) - A modal built out of pure CSS. [**1,431**]
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips. [**234**]


## Scroll

* [scrollMonitor](https://github.com/sakabako/scrollMonitor) - A simple and fast API to monitor elements as you scroll. [**872**]
* [headroom](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it. [**7,393**]
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin. [**7,982**]
* [iscroll](https://github.com/cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform javascript scroller. [**6,077**]
* [skrollr](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery. [**13,948**]
* [parallax](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device. [**8,615**]
* [stellar.js](https://github.com/markdalgleish/stellar.js) - Parallax scrolling made easy. [**3,364**]
* [plax](https://github.com/cameronmcefee/plax) - jQuery powered parallaxing. [**2,151**]
* [jparallax](https://github.com/stephband/jparallax) - jQuery plugin for creating interactive parallax effect. [**967**]
* [fullPage](https://github.com/alvarotrigo/fullPage.js) - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites). [**10,442**]
* [ScrollMenu](https://github.com/s-yadav/ScrollMenu) - A new interface to replace old boring scrollbar. [**84**]


## Menu

* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's. [**6,762**]
* [jQuery contextMenu] (https://github.com/medialize/jQuery-contextMenu) -  contextMenu manager. [**869**]
* [Slideout](https://github.com/mango/slideout) - A responsive touch slideout navigation menu for mobile web apps. [**4,586**]
* [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) - A sliding swipe menu that works with touchSwipe library. [**20**]


## Table/Grid

* [jTable](https://github.com/hikalkan/jtable) - A JQuery plugin to create AJAX based CRUD tables. [**568**]
* [DataTables](http://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.


## Frameworks

* [Semantic UI](http://semantic-ui.com/) - UI Kit with lots of themes and elements


## Gesture

* [hammer.js](https://github.com/hammerjs/hammer.js) - A javascript library for multi-touch gestures. [**11,911**]
* [touchemulator](https://github.com/hammerjs/touchemulator) - Emulate touch input on your desktop. [**100**]
* [Dragula] (https://github.com/bevacqua/dragula/) - Drag and drop so simple it hurts [**9,336**]


## Maps

* [Leaflet](https://github.com/Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps. [**11,410**]
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine. [**919**]
* [gmaps](https://github.com/HPNeo/gmaps) - The easiest way to use Google Maps. [**5,526**]
* [polymaps](https://github.com/simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers. [**1,273**]
* [kartograph.js](https://github.com/kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps. [**1,324**]
* [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin. [**1,062**]
* [jqvmap](https://github.com/manifestinteractive/jqvmap) - jQuery Vector Map Library. [**1,076**]


## Animations

* [velocity](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation. [**8,385**]
* [jquery.transit](https://github.com/rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery. [**6,516**]
* [bounce.js](https://github.com/tictail/bounce.js) - Create tasty CSS3 powered animations in no time. [**3,727**]
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers. [**3,313**]
* [TransitionEnd](https://github.com/EvandroLG/transitionEnd) - TransitionEnd is an agnostic and cross-browser library to work with transitionend event. [**54**]
* [Dynamic.js](https://github.com/michaelvillar/dynamics.js) - Javascript library to create physics-based CSS animations. [**4,260**]


## Image Processing

* [lena.js](https://github.com/davidsonfellipe/lena.js) - A Library for image processing with filters and util functions. [**54**]
* [pica](https://github.com/nodeca/pica) - High quality image resize (with fast Lanczos filter, implemented in pure JS). [**176**]


## ES6

* [es6features](https://github.com/lukehoban/es6features) - Overview of ECMAScript 6 features. [**8,916**]
* [ECMAScript 6 compatibility table](http://kangax.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.
* [Babel (Formerly 6to5)](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime. [**8,840**]
* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more. [**5,672**]


## SDK

* [javascript-sdk-design](http://github.com/huei90/javascript-sdk-design) - Javascript SDK design guide extracted from work and personal experience [**50**]


## Misc

* [echo](https://github.com/toddmotto/echo) - Lazy-loading images with data-* attributes. [**2,446**]
* [picturefill](https://github.com/scottjehl/picturefill) - A responsive image polyfill for <picture>, srcset, sizes [**7,372**]
* [platform.js](https://github.com/bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms. [**809**]
* [json3](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms. [**764**]
* [Logical Or Not](http://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.


# Worth Reading
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) [**4,791**]


# Other Awesome Lists
* [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome) [**354**]
* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) [**13,549**]
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome) [**16,058**]
* [jnv/list](https://github.com/jnv/lists) [**2,859**]
* [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs) [**881**]
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo) [**30**]
* [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools) [**2,228**]
* [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning) [**1,378**]
* [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents) [**53**]
* [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg) [**2,602**]
* [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) [**5,045**]
* [instanceofpro/awesome-backbone](https://github.com/instanceofpro/awesome-backbone) [**246**]
* [enaqx/awesome-react](https://github.com/enaqx/awesome-react) [**8,525**]
* [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch) [**9,884**]


# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.


# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.
