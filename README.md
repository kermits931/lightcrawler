<?xml version="1.0" encoding="utf-8"?>
<resources>
<string name="name"></string>
<string name="version"></string>

<!-- "repository" -->
<string name="type"></string>

<!-- "repository" -->
<string name="url"></string>

<!-- "devDependencies" -->
<string name="bluebird"></string>

<!-- "devDependencies" -->
<string name="eslint-plugin-google-camelcase"></string>

<!-- "devDependencies" -->
<string name="google-closure-compiler"></string>

<!-- "devDependencies" -->
<string name="grunt"></string>

<!-- "devDependencies" -->
<string name="grunt-bump"></string>

<!-- "devDependencies" -->
<string name="grunt-cli"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-clean"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-coffee"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-copy"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-qunit"></string>

<!-- "devDependencies" -->
<string name="grunt-eslint"></string>

<!-- "devDependencies" -->
<string name="grunt-prompt"></string>

<!-- "devDependencies" -->
<string name="load-grunt-tasks"></string>

<!-- "devDependencies" -->
<string name="superagent"></string>

<!-- "scripts" -->
<string name="test"></string>
<string name="description"></string>

<!-- "bugs" -->
<string name="url"></string>
<string name="homepage"></string>
<string name="main"></string>

<!-- "directories" -->
<string name="test"></string>

<!-- .list -->
<string name="keywords"></string>
<string name="author"></string>
<string name="license"></string>
<string name="//">"=/UserScript=="</string>
<string name="// @name GoEar HotLink 2015"></string>
<string name="// @author laurenceHR"></string>
<string name="// @include *goear.com/listen/*"></string>
<string name="// @include *goear.com/listen/*/*"></string>
<string name="// @version 1.5"></string>
<string name="// @description Goear HotLink for download"></string>
<string name="// Script by laurenceHR - www.daxes.net"></string>
<string name="////// Get Song ID"></string>
<string name="var url">"document.URL;"</string>
<string name="var urls">"url.split('/');"</string>
<string name="var id">"urls[4];"</string>
<string name="/////// Get HotLink"></string>
<string name="var hotlink">"\"http://www.goear.com/action/sound/get/\" + id;"</string>
<string name="////// Add HotLink"></string>
<string name="addHotLink(hotlink);"></string>
<string name="//////"></string>
<string name="/******  Function For Add Link *****/"></string>
<string name="function addHotLink(link){"></string>
<string name="//var style">"document.createElement('style');"</string>
<string name="//var css">"\"#main.listen .actions .down {background-position-y: 8px;}\" + \"
\";"</string>
<string name="//    style.textContent">"css;"</string>
<string name="//var head">"document.getElementsByTagName('head')[0];"</string>
<string name="//    head.appendChild(style);"></string>
<string name="var a">"document.createElement('a');"</string>
<string name="a.href">"link;"</string>
<string name="a.target">"\"_blank\";"</string>
<string name="a.innerHTML">"'&lt;span class=\"glyphicons download\"&gt;&lt;/span&gt;';"</string>
<string name="a.title">"'Get HotLink';"</string>
<string name="a.className">"'';"</string>
<string name="a.id">"'hotlink';"</string>
<string name="var li">"document.createElement('li');"</string>
<string name="li.className">"'action_item';"</string>
<string name="li.appendChild(a);"></string>
<string name="var ul_actions">"document.getElementsByClassName('actions')[0];"</string>
<string name="ul_actions.appendChild(li);"></string>
<string name="}"></string>
<string name="var express">"require('express');"</string>
<string name="var path"></string>
<string name="var favicon"></string>
<string name="var logger"></string>
<string name="var cookieParser"></string>
<string name="var bodyParser"></string>
<string name="var index"></string>
<string name="var users"></string>
<string name="var app"></string>
<string name="// view engine setup"></string>
<string name="app.set('views', path.join(__dirname, 'views'));"></string>
<string name="app.set('view engine', 'jade');"></string>
<string name="// uncomment after placing your favicon in /public"></string>
<string name="//app.use(favicon(path.join(__dirname, 'public', 'favicon.ico')));"></string>
<string name="app.use(logger('dev'));"></string>
<string name="app.use(bodyParser.json());"></string>
<string name="app.use(bodyParser.urlencoded({ extended"></string>
<string name="app.use(cookieParser());"></string>
<string name="app.use(express.static(path.join(__dirname, 'public')));"></string>
<string name="app.use('/', index);"></string>
<string name="app.use('/users', users);"></string>
<string name="// catch 404 and forward to error handler"></string>
<string name="app.use(function(req, res, next) {"></string>
<string name="var err"></string>
<string name="err.status"></string>
<string name="next(err);"></string>
<string name="});"></string>
<string name="// error handler"></string>
<string name="app.use(function(err, req, res, next) {"></string>
<string name="// set locals, only providing error in development"></string>
<string name="res.locals.message"></string>
<string name="res.locals.error"></string>
<string name="// render the error page"></string>
<string name="res.status(err.status || 500);"></string>
<string name="res.render('error');"></string>
<string name="module.exports">"(options) =&gt; {"</string>

<!-- "repository" -->
<string name="type"></string>

<!-- "bugs" -->
<string name="url"></string>

<!-- "devDependencies" -->
<string name="bluebird"></string>

<!-- "devDependencies" -->
<string name="eslint-plugin-google-camelcase"></string>

<!-- "devDependencies" -->
<string name="google-closure-compiler"></string>

<!-- "devDependencies" -->
<string name="grunt"></string>

<!-- "devDependencies" -->
<string name="grunt-bump"></string>

<!-- "devDependencies" -->
<string name="grunt-cli"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-clean"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-coffee"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-copy"></string>

<!-- "devDependencies" -->
<string name="grunt-contrib-qunit"></string>

<!-- "devDependencies" -->
<string name="grunt-eslint"></string>

<!-- "devDependencies" -->
<string name="grunt-prompt"></string>

<!-- "devDependencies" -->
<string name="load-grunt-tasks"></string>

<!-- "devDependencies" -->
<string name="superagent"></string>

<!-- "directories" -->
<string name="test"></string>

<!-- .list -->
<string name="keywords"></string>
<string name="var router"></string>
<string name="/* GET home page. */"></string>
<string name="router.get('/', function(req, res, next) {"></string>
<string name="res.render('index', { title"></string>
<string name="repository"></string>

<!-- "bin" -->
<string name="lightcrawler"></string>

<!-- "dependencies" -->
<string name="async"></string>

<!-- "dependencies" -->
<string name="cheerio"></string>

<!-- "dependencies" -->
<string name="colors"></string>

<!-- "dependencies" -->
<string name="lighthouse"></string>

<!-- "dependencies" -->
<string name="simplecrawler"></string>

<!-- "dependencies" -->
<string name="yargs"></string>

<!-- "devDependencies" -->
<string name="express"></string>

<!-- "devDependencies" -->
<string name="get-port"></string>

<!-- "devDependencies" -->
<string name="mocha"></string>

<!-- "devDependencies" -->
<string name="standard"></string>

<!-- .list -->
<string name="files"></string>
<string name="lockfileVersion"></string>

<!-- "dependencies"."@types/node" -->
<string name="version"></string>

<!-- "dependencies"."@types/node" -->
<string name="resolved"></string>

<!-- "dependencies"."@types/node" -->
<string name="integrity"></string>

<!-- "dependencies"."accepts" -->
<string name="version"></string>

<!-- "dependencies"."accepts" -->
<string name="resolved"></string>

<!-- "dependencies"."accepts" -->
<string name="integrity"></string>

<!-- "dependencies"."accepts" -->
<string name="dev"></string>

<!-- "dependencies"."acorn" -->
<string name="version"></string>

<!-- "dependencies"."acorn" -->
<string name="resolved"></string>

<!-- "dependencies"."acorn" -->
<string name="integrity"></string>

<!-- "dependencies"."acorn" -->
<string name="dev"></string>

<!-- "dependencies"."acorn-jsx" -->
<string name="version"></string>

<!-- "dependencies"."acorn-jsx" -->
<string name="resolved"></string>

<!-- "dependencies"."acorn-jsx" -->
<string name="integrity"></string>

<!-- "dependencies"."acorn-jsx" -->
<string name="dev"></string>

<!-- "dependencies"."acorn-jsx"."dependencies"."acorn" -->
<string name="version"></string>

<!-- "dependencies"."acorn-jsx"."dependencies"."acorn" -->
<string name="resolved"></string>

<!-- "dependencies"."acorn-jsx"."dependencies"."acorn" -->
<string name="integrity"></string>

<!-- "dependencies"."acorn-jsx"."dependencies"."acorn" -->
<string name="dev"></string>

<!-- "dependencies"."ajv" -->
<string name="version"></string>

<!-- "dependencies"."ajv" -->
<string name="resolved"></string>

<!-- "dependencies"."ajv" -->
<string name="integrity"></string>

<!-- "dependencies"."ajv" -->
<string name="dev"></string>

<!-- "dependencies"."ajv-keywords" -->
<string name="version"></string>

<!-- "dependencies"."ajv-keywords" -->
<string name="resolved"></string>

<!-- "dependencies"."ajv-keywords" -->
<string name="integrity"></string>

<!-- "dependencies"."ajv-keywords" -->
<string name="dev"></string>

<!-- "dependencies"."ansi-align" -->
<string name="version"></string>

<!-- "dependencies"."ansi-align" -->
<string name="resolved"></string>

<!-- "dependencies"."ansi-align" -->
<string name="integrity"></string>

<!-- "dependencies"."ansi-escapes" -->
<string name="version"></string>

<!-- "dependencies"."ansi-escapes" -->
<string name="resolved"></string>

<!-- "dependencies"."ansi-escapes" -->
<string name="integrity"></string>

<!-- "dependencies"."ansi-escapes" -->
<string name="dev"></string>

<!-- "dependencies"."ansi-regex" -->
<string name="version"></string>

<!-- "dependencies"."ansi-regex" -->
<string name="resolved"></string>

<!-- "dependencies"."ansi-regex" -->
<string name="integrity"></string>

<!-- "dependencies"."ansi-styles" -->
<string name="version"></string>

<!-- "dependencies"."ansi-styles" -->
<string name="resolved"></string>

<!-- "dependencies"."ansi-styles" -->
<string name="integrity"></string>

<!-- "dependencies"."argparse" -->
<string name="version"></string>

<!-- "dependencies"."argparse" -->
<string name="resolved"></string>

<!-- "dependencies"."argparse" -->
<string name="integrity"></string>

<!-- "dependencies"."argparse" -->
<string name="dev"></string>

<!-- "dependencies"."array-find-index" -->
<string name="version"></string>

<!-- "dependencies"."array-find-index" -->
<string name="resolved"></string>

<!-- "dependencies"."array-find-index" -->
<string name="integrity"></string>

<!-- "dependencies"."array-flatten" -->
<string name="version"></string>

<!-- "dependencies"."array-flatten" -->
<string name="resolved"></string>

<!-- "dependencies"."array-flatten" -->
<string name="integrity"></string>

<!-- "dependencies"."array-flatten" -->
<string name="dev"></string>

<!-- "dependencies"."array-union" -->
<string name="version"></string>

<!-- "dependencies"."array-union" -->
<string name="resolved"></string>

<!-- "dependencies"."array-union" -->
<string name="integrity"></string>

<!-- "dependencies"."array-union" -->
<string name="dev"></string>

<!-- "dependencies"."array-uniq" -->
<string name="version"></string>

<!-- "dependencies"."array-uniq" -->
<string name="resolved"></string>

<!-- "dependencies"."array-uniq" -->
<string name="integrity"></string>

<!-- "dependencies"."array-uniq" -->
<string name="dev"></string>

<!-- "dependencies"."array.prototype.find" -->
<string name="version"></string>

<!-- "dependencies"."array.prototype.find" -->
<string name="resolved"></string>

<!-- "dependencies"."array.prototype.find" -->
<string name="integrity"></string>

<!-- "dependencies"."array.prototype.find" -->
<string name="dev"></string>

<!-- "dependencies"."arrify" -->
<string name="version"></string>

<!-- "dependencies"."arrify" -->
<string name="resolved"></string>

<!-- "dependencies"."arrify" -->
<string name="integrity"></string>

<!-- "dependencies"."arrify" -->
<string name="dev"></string>

<!-- "dependencies"."async" -->
<string name="version"></string>

<!-- "dependencies"."async" -->
<string name="resolved"></string>

<!-- "dependencies"."async" -->
<string name="integrity"></string>

<!-- "dependencies"."axe-core" -->
<string name="version"></string>

<!-- "dependencies"."axe-core" -->
<string name="resolved"></string>

<!-- "dependencies"."axe-core" -->
<string name="integrity"></string>

<!-- "dependencies"."babar" -->
<string name="version"></string>

<!-- "dependencies"."babar" -->
<string name="resolved"></string>

<!-- "dependencies"."babar" -->
<string name="integrity"></string>

<!-- "dependencies"."babar"."dependencies"."colors" -->
<string name="version"></string>

<!-- "dependencies"."babar"."dependencies"."colors" -->
<string name="resolved"></string>

<!-- "dependencies"."babar"."dependencies"."colors" -->
<string name="integrity"></string>

<!-- "dependencies"."babel-code-frame" -->
<string name="version"></string>

<!-- "dependencies"."babel-code-frame" -->
<string name="resolved"></string>

<!-- "dependencies"."babel-code-frame" -->
<string name="integrity"></string>

<!-- "dependencies"."babel-code-frame" -->
<string name="dev"></string>

<!-- "dependencies"."balanced-match" -->
<string name="version"></string>

<!-- "dependencies"."balanced-match" -->
<string name="resolved"></string>

<!-- "dependencies"."balanced-match" -->
<string name="integrity"></string>

<!-- "dependencies"."balanced-match" -->
<string name="dev"></string>

<!-- "dependencies"."boolbase" -->
<string name="version"></string>

<!-- "dependencies"."boolbase" -->
<string name="resolved"></string>

<!-- "dependencies"."boolbase" -->
<string name="integrity"></string>

<!-- "dependencies"."boxen" -->
<string name="version"></string>

<!-- "dependencies"."boxen" -->
<string name="resolved"></string>

<!-- "dependencies"."boxen" -->
<string name="integrity"></string>

<!-- "dependencies"."boxen"."dependencies"."camelcase" -->
<string name="version"></string>

<!-- "dependencies"."boxen"."dependencies"."camelcase" -->
<string name="resolved"></string>

<!-- "dependencies"."boxen"."dependencies"."camelcase" -->
<string name="integrity"></string>

<!-- "dependencies"."boxen"."dependencies"."chalk" -->
<string name="version"></string>

<!-- "dependencies"."boxen"."dependencies"."chalk" -->
<string name="resolved"></string>

<!-- "dependencies"."boxen"."dependencies"."chalk" -->
<string name="integrity"></string>

<!-- "dependencies"."brace-expansion" -->
<string name="version"></string>

<!-- "dependencies"."brace-expansion" -->
<string name="resolved"></string>

<!-- "dependencies"."brace-expansion" -->
<string name="integrity"></string>

<!-- "dependencies"."brace-expansion" -->
<string name="dev"></string>

<!-- "dependencies"."browser-stdout" -->
<string name="version"></string>

<!-- "dependencies"."browser-stdout" -->
<string name="resolved"></string>

<!-- "dependencies"."browser-stdout" -->
<string name="integrity"></string>

<!-- "dependencies"."browser-stdout" -->
<string name="dev"></string>

<!-- "dependencies"."builtin-modules" -->
<string name="version"></string>

<!-- "dependencies"."builtin-modules" -->
<string name="resolved"></string>

<!-- "dependencies"."builtin-modules" -->
<string name="integrity"></string>

<!-- "dependencies"."caller-path" -->
<string name="version"></string>

<!-- "dependencies"."caller-path" -->
<string name="resolved"></string>

<!-- "dependencies"."caller-path" -->
<string name="integrity"></string>

<!-- "dependencies"."caller-path" -->
<string name="dev"></string>

<!-- "dependencies"."callsites" -->
<string name="version"></string>

<!-- "dependencies"."callsites" -->
<string name="resolved"></string>

<!-- "dependencies"."callsites" -->
<string name="integrity"></string>

<!-- "dependencies"."callsites" -->
<string name="dev"></string>

<!-- "dependencies"."camelcase" -->
<string name="version"></string>

<!-- "dependencies"."camelcase" -->
<string name="resolved"></string>

<!-- "dependencies"."camelcase" -->
<string name="integrity"></string>

<!-- "dependencies"."camelcase-keys" -->
<string name="version"></string>

<!-- "dependencies"."camelcase-keys" -->
<string name="resolved"></string>

<!-- "dependencies"."camelcase-keys" -->
<string name="integrity"></string>

<!-- "dependencies"."capture-stack-trace" -->
<string name="version"></string>

<!-- "dependencies"."capture-stack-trace" -->
<string name="resolved"></string>

<!-- "dependencies"."capture-stack-trace" -->
<string name="integrity"></string>

<!-- "dependencies"."chalk" -->
<string name="version"></string>

<!-- "dependencies"."chalk" -->
<string name="resolved"></string>

<!-- "dependencies"."chalk" -->
<string name="integrity"></string>

<!-- "dependencies"."chalk"."dependencies"."ansi-regex" -->
<string name="version"></string>

<!-- "dependencies"."chalk"."dependencies"."ansi-regex" -->
<string name="resolved"></string>

<!-- "dependencies"."chalk"."dependencies"."ansi-regex" -->
<string name="integrity"></string>

<!-- "dependencies"."chalk"."dependencies"."ansi-styles" -->
<string name="version"></string>

<!-- "dependencies"."chalk"."dependencies"."ansi-styles" -->
<string name="resolved"></string>

<!-- "dependencies"."chalk"."dependencies"."ansi-styles" -->
<string name="integrity"></string>

<!-- "dependencies"."chalk"."dependencies"."strip-ansi" -->
<string name="version"></string>

<!-- "dependencies"."chalk"."dependencies"."strip-ansi" -->
<string name="resolved"></string>

<!-- "dependencies"."chalk"."dependencies"."strip-ansi" -->
<string name="integrity"></string>

<!-- "dependencies"."chalk"."dependencies"."supports-color" -->
<string name="version"></string>

<!-- "dependencies"."chalk"."dependencies"."supports-color" -->
<string name="resolved"></string>

<!-- "dependencies"."chalk"."dependencies"."supports-color" -->
<string name="integrity"></string>

<!-- "dependencies"."cheerio" -->
<string name="version"></string>

<!-- "dependencies"."cheerio" -->
<string name="resolved"></string>

<!-- "dependencies"."cheerio" -->
<string name="integrity"></string>

<!-- "dependencies"."chrome-devtools-frontend" -->
<string name="version"></string>

<!-- "dependencies"."chrome-devtools-frontend" -->
<string name="resolved"></string>

<!-- "dependencies"."chrome-devtools-frontend" -->
<string name="integrity"></string>

<!-- "dependencies"."circular-json" -->
<string name="version"></string>

<!-- "dependencies"."circular-json" -->
<string name="resolved"></string>

<!-- "dependencies"."circular-json" -->
<string name="integrity"></string>

<!-- "dependencies"."circular-json" -->
<string name="dev"></string>

<!-- "dependencies"."cli-boxes" -->
<string name="version"></string>

<!-- "dependencies"."cli-boxes" -->
<string name="resolved"></string>

<!-- "dependencies"."cli-boxes" -->
<string name="integrity"></string>

<!-- "dependencies"."cli-cursor" -->
<string name="version"></string>

<!-- "dependencies"."cli-cursor" -->
<string name="resolved"></string>

<!-- "dependencies"."cli-cursor" -->
<string name="integrity"></string>

<!-- "dependencies"."cli-cursor" -->
<string name="dev"></string>

<!-- "dependencies"."cli-width" -->
<string name="version"></string>

<!-- "dependencies"."cli-width" -->
<string name="resolved"></string>

<!-- "dependencies"."cli-width" -->
<string name="integrity"></string>

<!-- "dependencies"."cli-width" -->
<string name="dev"></string>

<!-- "dependencies"."cliui" -->
<string name="version"></string>

<!-- "dependencies"."cliui" -->
<string name="resolved"></string>

<!-- "dependencies"."cliui" -->
<string name="integrity"></string>

<!-- "dependencies"."cliui"."dependencies"."ansi-regex" -->
<string name="version"></string>

<!-- "dependencies"."cliui"."dependencies"."ansi-regex" -->
<string name="resolved"></string>

<!-- "dependencies"."cliui"."dependencies"."ansi-regex" -->
<string name="integrity"></string>

<!-- "dependencies"."cliui"."dependencies"."is-fullwidth-code-point" -->
<string name="version"></string>

<!-- "dependencies"."cliui"."dependencies"."is-fullwidth-code-point" -->
<string name="resolved"></string>

<!-- "dependencies"."cliui"."dependencies"."is-fullwidth-code-point" -->
<string name="integrity"></string>

<!-- "dependencies"."cliui"."dependencies"."string-width" -->
<string name="version"></string>

<!-- "dependencies"."cliui"."dependencies"."string-width" -->
<string name="resolved"></string>

<!-- "dependencies"."cliui"."dependencies"."string-width" -->
<string name="integrity"></string>

<!-- "dependencies"."cliui"."dependencies"."strip-ansi" -->
<string name="version"></string>

<!-- "dependencies"."cliui"."dependencies"."strip-ansi" -->
<string name="resolved"></string>

<!-- "dependencies"."cliui"."dependencies"."strip-ansi" -->
<string name="integrity"></string>

<!-- "dependencies"."co" -->
<string name="version"></string>

<!-- "dependencies"."co" -->
<string name="resolved"></string>

<!-- "dependencies"."co" -->
<string name="integrity"></string>

<!-- "dependencies"."co" -->
<string name="dev"></string>

<!-- "dependencies"."code-point-at" -->
<string name="version"></string>

<!-- "dependencies"."code-point-at" -->
<string name="resolved"></string>

<!-- "dependencies"."code-point-at" -->
<string name="integrity"></string>

<!-- "dependencies"."color-convert" -->
<string name="version"></string>

<!-- "dependencies"."color-convert" -->
<string name="resolved"></string>

<!-- "dependencies"."color-convert" -->
<string name="integrity"></string>

<!-- "dependencies"."color-name" -->
<string name="version"></string>

<!-- "dependencies"."color-name" -->
<string name="resolved"></string>

<!-- "dependencies"."color-name" -->
<string name="integrity"></string>

<!-- "dependencies"."colors" -->
<string name="version"></string>

<!-- "dependencies"."colors" -->
<string name="resolved"></string>

<!-- "dependencies"."colors" -->
<string name="integrity"></string>

<!-- "dependencies"."commander" -->
<string name="version"></string>

<!-- "dependencies"."commander" -->
<string name="resolved"></string>

<!-- "dependencies"."commander" -->
<string name="integrity"></string>

<!-- "dependencies"."commander" -->
<string name="dev"></string>

<!-- "dependencies"."concat-map" -->
<string name="version"></string>

<!-- "dependencies"."concat-map" -->
<string name="resolved"></string>

<!-- "dependencies"."concat-map" -->
<string name="integrity"></string>

<!-- "dependencies"."concat-map" -->
<string name="dev"></string>

<!-- "dependencies"."concat-stream" -->
<string name="version"></string>

<!-- "dependencies"."concat-stream" -->
<string name="resolved"></string>

<!-- "dependencies"."concat-stream" -->
<string name="integrity"></string>

<!-- "dependencies"."concat-stream" -->
<string name="dev"></string>

<!-- "dependencies"."configstore" -->
<string name="version"></string>

<!-- "dependencies"."configstore" -->
<string name="resolved"></string>

<!-- "dependencies"."configstore" -->
<string name="integrity"></string>

<!-- "dependencies"."contains-path" -->
<string name="version"></string>

<!-- "dependencies"."contains-path" -->
<string name="resolved"></string>

<!-- "dependencies"."contains-path" -->
<string name="integrity"></string>

<!-- "dependencies"."contains-path" -->
<string name="dev"></string>

<!-- "dependencies"."content-disposition" -->
<string name="version"></string>

<!-- "dependencies"."content-disposition" -->
<string name="resolved"></string>

<!-- "dependencies"."content-disposition" -->
<string name="integrity"></string>

<!-- "dependencies"."content-disposition" -->
<string name="dev"></string>

<!-- "dependencies"."content-type" -->
<string name="version"></string>

<!-- "dependencies"."content-type" -->
<string name="resolved"></string>

<!-- "dependencies"."content-type" -->
<string name="integrity"></string>

<!-- "dependencies"."content-type" -->
<string name="dev"></string>

<!-- "dependencies"."cookie" -->
<string name="version"></string>

<!-- "dependencies"."cookie" -->
<string name="resolved"></string>

<!-- "dependencies"."cookie" -->
<string name="integrity"></string>

<!-- "dependencies"."cookie" -->
<string name="dev"></string>

<!-- "dependencies"."cookie-signature" -->
<string name="version"></string>

<!-- "dependencies"."cookie-signature" -->
<string name="resolved"></string>

<!-- "dependencies"."cookie-signature" -->
<string name="integrity"></string>

<!-- "dependencies"."cookie-signature" -->
<string name="dev"></string>

<!-- "dependencies"."core-util-is" -->
<string name="version"></string>

<!-- "dependencies"."core-util-is" -->
<string name="resolved"></string>

<!-- "dependencies"."core-util-is" -->
<string name="integrity"></string>

<!-- "dependencies"."create-error-class" -->
<string name="version"></string>

<!-- "dependencies"."create-error-class" -->
<string name="resolved"></string>

<!-- "dependencies"."create-error-class" -->
<string name="integrity"></string>

<!-- "dependencies"."cross-spawn" -->
<string name="version"></string>

<!-- "dependencies"."cross-spawn" -->
<string name="resolved"></string>

<!-- "dependencies"."cross-spawn" -->
<string name="integrity"></string>

<!-- "dependencies"."crypto-random-string" -->
<string name="version"></string>

<!-- "dependencies"."crypto-random-string" -->
<string name="resolved"></string>

<!-- "dependencies"."crypto-random-string" -->
<string name="integrity"></string>

<!-- "dependencies"."css-select" -->
<string name="version"></string>

<!-- "dependencies"."css-select" -->
<string name="resolved"></string>

<!-- "dependencies"."css-select" -->
<string name="integrity"></string>

<!-- "dependencies"."css-what" -->
<string name="version"></string>

<!-- "dependencies"."css-what" -->
<string name="resolved"></string>

<!-- "dependencies"."css-what" -->
<string name="integrity"></string>

<!-- "dependencies"."currently-unhandled" -->
<string name="version"></string>

<!-- "dependencies"."currently-unhandled" -->
<string name="resolved"></string>

<!-- "dependencies"."currently-unhandled" -->
<string name="integrity"></string>

<!-- "dependencies"."d" -->
<string name="version"></string>

<!-- "dependencies"."d" -->
<string name="resolved"></string>

<!-- "dependencies"."d" -->
<string name="integrity"></string>

<!-- "dependencies"."d" -->
<string name="dev"></string>

<!-- "dependencies"."debug" -->
<string name="version"></string>

<!-- "dependencies"."debug" -->
<string name="resolved"></string>

<!-- "dependencies"."debug" -->
<string name="integrity"></string>

<!-- "dependencies"."debug-log" -->
<string name="version"></string>

<!-- "dependencies"."debug-log" -->
<string name="resolved"></string>

<!-- "dependencies"."debug-log" -->
<string name="integrity"></string>

<!-- "dependencies"."debug-log" -->
<string name="dev"></string>

<!-- "dependencies"."decamelize" -->
<string name="version"></string>

<!-- "dependencies"."decamelize" -->
<string name="resolved"></string>

<!-- "dependencies"."decamelize" -->
<string name="integrity"></string>

<!-- "dependencies"."deep-extend" -->
<string name="version"></string>

<!-- "dependencies"."deep-extend" -->
<string name="resolved"></string>

<!-- "dependencies"."deep-extend" -->
<string name="integrity"></string>

<!-- "dependencies"."deep-is" -->
<string name="version"></string>

<!-- "dependencies"."deep-is" -->
<string name="resolved"></string>

<!-- "dependencies"."deep-is" -->
<string name="integrity"></string>

<!-- "dependencies"."deep-is" -->
<string name="dev"></string>

<!-- "dependencies"."define-properties" -->
<string name="version"></string>

<!-- "dependencies"."define-properties" -->
<string name="resolved"></string>

<!-- "dependencies"."define-properties" -->
<string name="integrity"></string>

<!-- "dependencies"."define-properties" -->
<string name="dev"></string>

<!-- "dependencies"."deglob" -->
<string name="version"></string>

<!-- "dependencies"."deglob" -->
<string name="resolved"></string>

<!-- "dependencies"."deglob" -->
<string name="integrity"></string>

<!-- "dependencies"."deglob" -->
<string name="dev"></string>

<!-- "dependencies"."del" -->
<string name="version"></string>

<!-- "dependencies"."del" -->
<string name="resolved"></string>

<!-- "dependencies"."del" -->
<string name="integrity"></string>

<!-- "dependencies"."del" -->
<string name="dev"></string>

<!-- "dependencies"."depd" -->
<string name="version"></string>

<!-- "dependencies"."depd" -->
<string name="resolved"></string>

<!-- "dependencies"."depd" -->
<string name="integrity"></string>

<!-- "dependencies"."depd" -->
<string name="dev"></string>

<!-- "dependencies"."destroy" -->
<string name="version"></string>

<!-- "dependencies"."destroy" -->
<string name="resolved"></string>

<!-- "dependencies"."destroy" -->
<string name="integrity"></string>

<!-- "dependencies"."destroy" -->
<string name="dev"></string>

<!-- "dependencies"."devtools-timeline-model" -->
<string name="version"></string>

<!-- "dependencies"."devtools-timeline-model" -->
<string name="resolved"></string>

<!-- "dependencies"."devtools-timeline-model" -->
<string name="integrity"></string>

<!-- "dependencies"."devtools-timeline-model"."dependencies"."chrome-devtools-frontend" -->
<string name="version"></string>

<!-- "dependencies"."devtools-timeline-model"."dependencies"."chrome-devtools-frontend" -->
<string name="resolved"></string>

<!-- "dependencies"."devtools-timeline-model"."dependencies"."chrome-devtools-frontend" -->
<string name="integrity"></string>

<!-- "dependencies"."diff" -->
<string name="version"></string>

<!-- "dependencies"."diff" -->
<string name="resolved"></string>

<!-- "dependencies"."diff" -->
<string name="integrity"></string>

<!-- "dependencies"."diff" -->
<string name="dev"></string>

<!-- "dependencies"."doctrine" -->
<string name="version"></string>

<!-- "dependencies"."doctrine" -->
<string name="resolved"></string>

<!-- "dependencies"."doctrine" -->
<string name="integrity"></string>

<!-- "dependencies"."doctrine" -->
<string name="dev"></string>

<!-- "dependencies"."dom-serializer" -->
<string name="version"></string>

<!-- "dependencies"."dom-serializer" -->
<string name="resolved"></string>

<!-- "dependencies"."dom-serializer" -->
<string name="integrity"></string>

<!-- "dependencies"."dom-serializer"."dependencies"."domelementtype" -->
<string name="version"></string>

<!-- "dependencies"."dom-serializer"."dependencies"."domelementtype" -->
<string name="resolved"></string>

<!-- "dependencies"."dom-serializer"."dependencies"."domelementtype" -->
<string name="integrity"></string>

<!-- "dependencies"."domelementtype" -->
<string name="version"></string>

<!-- "dependencies"."domelementtype" -->
<string name="resolved"></string>

<!-- "dependencies"."domelementtype" -->
<string name="integrity"></string>

<!-- "dependencies"."domhandler" -->
<string name="version"></string>

<!-- "dependencies"."domhandler" -->
<string name="resolved"></string>

<!-- "dependencies"."domhandler" -->
<string name="integrity"></string>

<!-- "dependencies"."domutils" -->
<string name="version"></string>

<!-- "dependencies"."domutils" -->
<string name="resolved"></string>

<!-- "dependencies"."domutils" -->
<string name="integrity"></string>

<!-- "dependencies"."dot-prop" -->
<string name="version"></string>

<!-- "dependencies"."dot-prop" -->
<string name="resolved"></string>

<!-- "dependencies"."dot-prop" -->
<string name="integrity"></string>

<!-- "dependencies"."duplexer3" -->
<string name="version"></string>

<!-- "dependencies"."duplexer3" -->
<string name="resolved"></string>

<!-- "dependencies"."duplexer3" -->
<string name="integrity"></string>

<!-- "dependencies"."ee-first" -->
<string name="version"></string>

<!-- "dependencies"."ee-first" -->
<string name="resolved"></string>

<!-- "dependencies"."ee-first" -->
<string name="integrity"></string>

<!-- "dependencies"."ee-first" -->
<string name="dev"></string>

<!-- "dependencies"."encodeurl" -->
<string name="version"></string>

<!-- "dependencies"."encodeurl" -->
<string name="resolved"></string>

<!-- "dependencies"."encodeurl" -->
<string name="integrity"></string>

<!-- "dependencies"."encodeurl" -->
<string name="dev"></string>

<!-- "dependencies"."entities" -->
<string name="version"></string>

<!-- "dependencies"."entities" -->
<string name="resolved"></string>

<!-- "dependencies"."entities" -->
<string name="integrity"></string>

<!-- "dependencies"."error-ex" -->
<string name="version"></string>

<!-- "dependencies"."error-ex" -->
<string name="resolved"></string>

<!-- "dependencies"."error-ex" -->
<string name="integrity"></string>

<!-- "dependencies"."es-abstract" -->
<string name="version"></string>

<!-- "dependencies"."es-abstract" -->
<string name="resolved"></string>

<!-- "dependencies"."es-abstract" -->
<string name="integrity"></string>

<!-- "dependencies"."es-abstract" -->
<string name="dev"></string>

<!-- "dependencies"."es-to-primitive" -->
<string name="version"></string>

<!-- "dependencies"."es-to-primitive" -->
<string name="resolved"></string>

<!-- "dependencies"."es-to-primitive" -->
<string name="integrity"></string>

<!-- "dependencies"."es-to-primitive" -->
<string name="dev"></string>

<!-- "dependencies"."es5-ext" -->
<string name="version"></string>

<!-- "dependencies"."es5-ext" -->
<string name="resolved"></string>

<!-- "dependencies"."es5-ext" -->
<string name="integrity"></string>

<!-- "dependencies"."es5-ext" -->
<string name="dev"></string>

<!-- "dependencies"."es6-iterator" -->
<string name="version"></string>

<!-- "dependencies"."es6-iterator" -->
<string name="resolved"></string>

<!-- "dependencies"."es6-iterator" -->
<string name="integrity"></string>

<!-- "dependencies"."es6-iterator" -->
<string name="dev"></string>

<!-- "dependencies"."es6-map" -->
<string name="version"></string>

<!-- "dependencies"."es6-map" -->
<string name="resolved"></string>

<!-- "dependencies"."es6-map" -->
<string name="integrity"></string>

<!-- "dependencies"."es6-map" -->
<string name="dev"></string>

<!-- "dependencies"."es6-set" -->
<string name="version"></string>

<!-- "dependencies"."es6-set" -->
<string name="resolved"></string>

<!-- "dependencies"."es6-set" -->
<string name="integrity"></string>

<!-- "dependencies"."es6-set" -->
<string name="dev"></string>

<!-- "dependencies"."es6-symbol" -->
<string name="version"></string>

<!-- "dependencies"."es6-symbol" -->
<string name="resolved"></string>

<!-- "dependencies"."es6-symbol" -->
<string name="integrity"></string>

<!-- "dependencies"."es6-symbol" -->
<string name="dev"></string>

<!-- "dependencies"."es6-weak-map" -->
<string name="version"></string>

<!-- "dependencies"."es6-weak-map" -->
<string name="resolved"></string>

<!-- "dependencies"."es6-weak-map" -->
<string name="integrity"></string>

<!-- "dependencies"."es6-weak-map" -->
<string name="dev"></string>

<!-- "dependencies"."escape-html" -->
<string name="version"></string>

<!-- "dependencies"."escape-html" -->
<string name="resolved"></string>

<!-- "dependencies"."escape-html" -->
<string name="integrity"></string>

<!-- "dependencies"."escape-html" -->
<string name="dev"></string>

<!-- "dependencies"."escape-string-regexp" -->
<string name="version"></string>

<!-- "dependencies"."escape-string-regexp" -->
<string name="resolved"></string>

<!-- "dependencies"."escape-string-regexp" -->
<string name="integrity"></string>

<!-- "dependencies"."escope" -->
<string name="version"></string>

<!-- "dependencies"."escope" -->
<string name="resolved"></string>

<!-- "dependencies"."escope" -->
<string name="integrity"></string>

<!-- "dependencies"."escope" -->
<string name="dev"></string>

<!-- "dependencies"."eslint" -->
<string name="version"></string>

<!-- "dependencies"."eslint" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint" -->
<string name="dev"></string>

<!-- "dependencies"."eslint"."dependencies"."strip-bom" -->
<string name="version"></string>

<!-- "dependencies"."eslint"."dependencies"."strip-bom" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint"."dependencies"."strip-bom" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint"."dependencies"."strip-bom" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-config-standard" -->
<string name="version"></string>

<!-- "dependencies"."eslint-config-standard" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-config-standard" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-config-standard" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-config-standard-jsx" -->
<string name="version"></string>

<!-- "dependencies"."eslint-config-standard-jsx" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-config-standard-jsx" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-config-standard-jsx" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-import-resolver-node" -->
<string name="version"></string>

<!-- "dependencies"."eslint-import-resolver-node" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-import-resolver-node" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-import-resolver-node" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-module-utils" -->
<string name="version"></string>

<!-- "dependencies"."eslint-module-utils" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-module-utils" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-module-utils" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-plugin-import" -->
<string name="version"></string>

<!-- "dependencies"."eslint-plugin-import" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-plugin-import" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-plugin-import" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-plugin-import"."dependencies"."doctrine" -->
<string name="version"></string>

<!-- "dependencies"."eslint-plugin-import"."dependencies"."doctrine" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-plugin-import"."dependencies"."doctrine" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-plugin-import"."dependencies"."doctrine" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-plugin-node" -->
<string name="version"></string>

<!-- "dependencies"."eslint-plugin-node" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-plugin-node" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-plugin-node" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-plugin-promise" -->
<string name="version"></string>

<!-- "dependencies"."eslint-plugin-promise" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-plugin-promise" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-plugin-promise" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-plugin-react" -->
<string name="version"></string>

<!-- "dependencies"."eslint-plugin-react" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-plugin-react" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-plugin-react" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-plugin-react"."dependencies"."doctrine" -->
<string name="version"></string>

<!-- "dependencies"."eslint-plugin-react"."dependencies"."doctrine" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-plugin-react"."dependencies"."doctrine" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-plugin-react"."dependencies"."doctrine" -->
<string name="dev"></string>

<!-- "dependencies"."eslint-plugin-standard" -->
<string name="version"></string>

<!-- "dependencies"."eslint-plugin-standard" -->
<string name="resolved"></string>

<!-- "dependencies"."eslint-plugin-standard" -->
<string name="integrity"></string>

<!-- "dependencies"."eslint-plugin-standard" -->
<string name="dev"></string>

<!-- "dependencies"."espree" -->
<string name="version"></string>

<!-- "dependencies"."espree" -->
<string name="resolved"></string>

<!-- "dependencies"."espree" -->
<string name="integrity"></string>

<!-- "dependencies"."espree" -->
<string name="dev"></string>

<!-- "dependencies"."esprima" -->
<string name="version"></string>

<!-- "dependencies"."esprima" -->
<string name="resolved"></string>

<!-- "dependencies"."esprima" -->
<string name="integrity"></string>

<!-- "dependencies"."esprima" -->
<string name="dev"></string>

<!-- "dependencies"."esquery" -->
<string name="version"></string>

<!-- "dependencies"."esquery" -->
<string name="resolved"></string>

<!-- "dependencies"."esquery" -->
<string name="integrity"></string>

<!-- "dependencies"."esquery" -->
<string name="dev"></string>

<!-- "dependencies"."esrecurse" -->
<string name="version"></string>

<!-- "dependencies"."esrecurse" -->
<string name="resolved"></string>

<!-- "dependencies"."esrecurse" -->
<string name="integrity"></string>

<!-- "dependencies"."esrecurse" -->
<string name="dev"></string>

<!-- "dependencies"."estraverse" -->
<string name="version"></string>

<!-- "dependencies"."estraverse" -->
<string name="resolved"></string>

<!-- "dependencies"."estraverse" -->
<string name="integrity"></string>

<!-- "dependencies"."estraverse" -->
<string name="dev"></string>

<!-- "dependencies"."esutils" -->
<string name="version"></string>

<!-- "dependencies"."esutils" -->
<string name="resolved"></string>

<!-- "dependencies"."esutils" -->
<string name="integrity"></string>

<!-- "dependencies"."esutils" -->
<string name="dev"></string>

<!-- "dependencies"."etag" -->
<string name="version"></string>

<!-- "dependencies"."etag" -->
<string name="resolved"></string>

<!-- "dependencies"."etag" -->
<string name="integrity"></string>

<!-- "dependencies"."etag" -->
<string name="dev"></string>

<!-- "dependencies"."event-emitter" -->
<string name="version"></string>

<!-- "dependencies"."event-emitter" -->
<string name="resolved"></string>

<!-- "dependencies"."event-emitter" -->
<string name="integrity"></string>

<!-- "dependencies"."event-emitter" -->
<string name="dev"></string>

<!-- "dependencies"."execa" -->
<string name="version"></string>

<!-- "dependencies"."execa" -->
<string name="resolved"></string>

<!-- "dependencies"."execa" -->
<string name="integrity"></string>

<!-- "dependencies"."exit-hook" -->
<string name="version"></string>

<!-- "dependencies"."exit-hook" -->
<string name="resolved"></string>

<!-- "dependencies"."exit-hook" -->
<string name="integrity"></string>

<!-- "dependencies"."exit-hook" -->
<string name="dev"></string>

<!-- "dependencies"."express" -->
<string name="version"></string>

<!-- "dependencies"."express" -->
<string name="resolved"></string>

<!-- "dependencies"."express" -->
<string name="integrity"></string>

<!-- "dependencies"."express" -->
<string name="dev"></string>

<!-- "dependencies"."express"."dependencies"."debug" -->
<string name="version"></string>

<!-- "dependencies"."express"."dependencies"."debug" -->
<string name="resolved"></string>

<!-- "dependencies"."express"."dependencies"."debug" -->
<string name="integrity"></string>

<!-- "dependencies"."express"."dependencies"."debug" -->
<string name="dev"></string>

<!-- "dependencies"."fast-levenshtein" -->
<string name="version"></string>

<!-- "dependencies"."fast-levenshtein" -->
<string name="resolved"></string>

<!-- "dependencies"."fast-levenshtein" -->
<string name="integrity"></string>

<!-- "dependencies"."fast-levenshtein" -->
<string name="dev"></string>

<!-- "dependencies"."figures" -->
<string name="version"></string>

<!-- "dependencies"."figures" -->
<string name="resolved"></string>

<!-- "dependencies"."figures" -->
<string name="integrity"></string>

<!-- "dependencies"."figures" -->
<string name="dev"></string>

<!-- "dependencies"."file-entry-cache" -->
<string name="version"></string>

<!-- "dependencies"."file-entry-cache" -->
<string name="resolved"></string>

<!-- "dependencies"."file-entry-cache" -->
<string name="integrity"></string>

<!-- "dependencies"."file-entry-cache" -->
<string name="dev"></string>

<!-- "dependencies"."finalhandler" -->
<string name="version"></string>

<!-- "dependencies"."finalhandler" -->
<string name="resolved"></string>

<!-- "dependencies"."finalhandler" -->
<string name="integrity"></string>

<!-- "dependencies"."finalhandler" -->
<string name="dev"></string>

<!-- "dependencies"."finalhandler"."dependencies"."debug" -->
<string name="version"></string>

<!-- "dependencies"."finalhandler"."dependencies"."debug" -->
<string name="resolved"></string>

<!-- "dependencies"."finalhandler"."dependencies"."debug" -->
<string name="integrity"></string>

<!-- "dependencies"."finalhandler"."dependencies"."debug" -->
<string name="dev"></string>

<!-- "dependencies"."find-root" -->
<string name="version"></string>

<!-- "dependencies"."find-root" -->
<string name="resolved"></string>

<!-- "dependencies"."find-root" -->
<string name="integrity"></string>

<!-- "dependencies"."find-root" -->
<string name="dev"></string>

<!-- "dependencies"."find-up" -->
<string name="version"></string>

<!-- "dependencies"."find-up" -->
<string name="resolved"></string>

<!-- "dependencies"."find-up" -->
<string name="integrity"></string>

<!-- "dependencies"."flat-cache" -->
<string name="version"></string>

<!-- "dependencies"."flat-cache" -->
<string name="resolved"></string>

<!-- "dependencies"."flat-cache" -->
<string name="integrity"></string>

<!-- "dependencies"."flat-cache" -->
<string name="dev"></string>

<!-- "dependencies"."foreach" -->
<string name="version"></string>

<!-- "dependencies"."foreach" -->
<string name="resolved"></string>

<!-- "dependencies"."foreach" -->
<string name="integrity"></string>

<!-- "dependencies"."foreach" -->
<string name="dev"></string>

<!-- "dependencies"."forwarded" -->
<string name="version"></string>

<!-- "dependencies"."forwarded" -->
<string name="resolved"></string>

<!-- "dependencies"."forwarded" -->
<string name="integrity"></string>

<!-- "dependencies"."forwarded" -->
<string name="dev"></string>

<!-- "dependencies"."fresh" -->
<string name="version"></string>

<!-- "dependencies"."fresh" -->
<string name="resolved"></string>

<!-- "dependencies"."fresh" -->
<string name="integrity"></string>

<!-- "dependencies"."fresh" -->
<string name="dev"></string>

<!-- "dependencies"."fs.realpath" -->
<string name="version"></string>

<!-- "dependencies"."fs.realpath" -->
<string name="resolved"></string>

<!-- "dependencies"."fs.realpath" -->
<string name="integrity"></string>

<!-- "dependencies"."fs.realpath" -->
<string name="dev"></string>

<!-- "dependencies"."function-bind" -->
<string name="version"></string>

<!-- "dependencies"."function-bind" -->
<string name="resolved"></string>

<!-- "dependencies"."function-bind" -->
<string name="integrity"></string>

<!-- "dependencies"."function-bind" -->
<string name="dev"></string>

<!-- "dependencies"."generate-function" -->
<string name="version"></string>

<!-- "dependencies"."generate-function" -->
<string name="resolved"></string>

<!-- "dependencies"."generate-function" -->
<string name="integrity"></string>

<!-- "dependencies"."generate-function" -->
<string name="dev"></string>

<!-- "dependencies"."generate-object-property" -->
<string name="version"></string>

<!-- "dependencies"."generate-object-property" -->
<string name="resolved"></string>

<!-- "dependencies"."generate-object-property" -->
<string name="integrity"></string>

<!-- "dependencies"."generate-object-property" -->
<string name="dev"></string>

<!-- "dependencies"."get-caller-file" -->
<string name="version"></string>

<!-- "dependencies"."get-caller-file" -->
<string name="resolved"></string>

<!-- "dependencies"."get-caller-file" -->
<string name="integrity"></string>

<!-- "dependencies"."get-port" -->
<string name="version"></string>

<!-- "dependencies"."get-port" -->
<string name="resolved"></string>

<!-- "dependencies"."get-port" -->
<string name="integrity"></string>

<!-- "dependencies"."get-port" -->
<string name="dev"></string>

<!-- "dependencies"."get-stdin" -->
<string name="version"></string>

<!-- "dependencies"."get-stdin" -->
<string name="resolved"></string>

<!-- "dependencies"."get-stdin" -->
<string name="integrity"></string>

<!-- "dependencies"."get-stream" -->
<string name="version"></string>

<!-- "dependencies"."get-stream" -->
<string name="resolved"></string>

<!-- "dependencies"."get-stream" -->
<string name="integrity"></string>

<!-- "dependencies"."glob" -->
<string name="version"></string>

<!-- "dependencies"."glob" -->
<string name="resolved"></string>

<!-- "dependencies"."glob" -->
<string name="integrity"></string>

<!-- "dependencies"."glob" -->
<string name="dev"></string>

<!-- "dependencies"."globals" -->
<string name="version"></string>

<!-- "dependencies"."globals" -->
<string name="resolved"></string>

<!-- "dependencies"."globals" -->
<string name="integrity"></string>

<!-- "dependencies"."globals" -->
<string name="dev"></string>

<!-- "dependencies"."globby" -->
<string name="version"></string>

<!-- "dependencies"."globby" -->
<string name="resolved"></string>

<!-- "dependencies"."globby" -->
<string name="integrity"></string>

<!-- "dependencies"."globby" -->
<string name="dev"></string>

<!-- "dependencies"."got" -->
<string name="version"></string>

<!-- "dependencies"."got" -->
<string name="resolved"></string>

<!-- "dependencies"."got" -->
<string name="integrity"></string>

<!-- "dependencies"."graceful-fs" -->
<string name="version"></string>

<!-- "dependencies"."graceful-fs" -->
<string name="resolved"></string>

<!-- "dependencies"."graceful-fs" -->
<string name="integrity"></string>

<!-- "dependencies"."graceful-readlink" -->
<string name="version"></string>

<!-- "dependencies"."graceful-readlink" -->
<string name="resolved"></string>

<!-- "dependencies"."graceful-readlink" -->
<string name="integrity"></string>

<!-- "dependencies"."graceful-readlink" -->
<string name="dev"></string>

<!-- "dependencies"."growl" -->
<string name="version"></string>

<!-- "dependencies"."growl" -->
<string name="resolved"></string>

<!-- "dependencies"."growl" -->
<string name="integrity"></string>

<!-- "dependencies"."growl" -->
<string name="dev"></string>

<!-- "dependencies"."has" -->
<string name="version"></string>

<!-- "dependencies"."has" -->
<string name="resolved"></string>

<!-- "dependencies"."has" -->
<string name="integrity"></string>

<!-- "dependencies"."has" -->
<string name="dev"></string>

<!-- "dependencies"."has-ansi" -->
<string name="version"></string>

<!-- "dependencies"."has-ansi" -->
<string name="resolved"></string>

<!-- "dependencies"."has-ansi" -->
<string name="integrity"></string>

<!-- "dependencies"."has-ansi"."dependencies"."ansi-regex" -->
<string name="version"></string>

<!-- "dependencies"."has-ansi"."dependencies"."ansi-regex" -->
<string name="resolved"></string>

<!-- "dependencies"."has-ansi"."dependencies"."ansi-regex" -->
<string name="integrity"></string>

<!-- "dependencies"."has-flag" -->
<string name="version"></string>

<!-- "dependencies"."has-flag" -->
<string name="resolved"></string>

<!-- "dependencies"."has-flag" -->
<string name="integrity"></string>

<!-- "dependencies"."hosted-git-info" -->
<string name="version"></string>

<!-- "dependencies"."hosted-git-info" -->
<string name="resolved"></string>

<!-- "dependencies"."hosted-git-info" -->
<string name="integrity"></string>

<!-- "dependencies"."htmlparser2" -->
<string name="version"></string>

<!-- "dependencies"."htmlparser2" -->
<string name="resolved"></string>

<!-- "dependencies"."htmlparser2" -->
<string name="integrity"></string>

<!-- "dependencies"."http-errors" -->
<string name="version"></string>

<!-- "dependencies"."http-errors" -->
<string name="resolved"></string>

<!-- "dependencies"."http-errors" -->
<string name="integrity"></string>

<!-- "dependencies"."http-errors" -->
<string name="dev"></string>

<!-- "dependencies"."iconv-lite" -->
<string name="version"></string>

<!-- "dependencies"."iconv-lite" -->
<string name="resolved"></string>

<!-- "dependencies"."iconv-lite" -->
<string name="integrity"></string>

<!-- "dependencies"."ignore" -->
<string name="version"></string>

<!-- "dependencies"."ignore" -->
<string name="resolved"></string>

<!-- "dependencies"."ignore" -->
<string name="integrity"></string>

<!-- "dependencies"."ignore" -->
<string name="dev"></string>

<!-- "dependencies"."image-ssim" -->
<string name="version"></string>

<!-- "dependencies"."image-ssim" -->
<string name="resolved"></string>

<!-- "dependencies"."image-ssim" -->
<string name="integrity"></string>

<!-- "dependencies"."import-lazy" -->
<string name="version"></string>

<!-- "dependencies"."import-lazy" -->
<string name="resolved"></string>

<!-- "dependencies"."import-lazy" -->
<string name="integrity"></string>

<!-- "dependencies"."imurmurhash" -->
<string name="version"></string>

<!-- "dependencies"."imurmurhash" -->
<string name="resolved"></string>

<!-- "dependencies"."imurmurhash" -->
<string name="integrity"></string>

<!-- "dependencies"."indent-string" -->
<string name="version"></string>

<!-- "dependencies"."indent-string" -->
<string name="resolved"></string>

<!-- "dependencies"."indent-string" -->
<string name="integrity"></string>

<!-- "dependencies"."inflight" -->
<string name="version"></string>

<!-- "dependencies"."inflight" -->
<string name="resolved"></string>

<!-- "dependencies"."inflight" -->
<string name="integrity"></string>

<!-- "dependencies"."inflight" -->
<string name="dev"></string>

<!-- "dependencies"."inherits" -->
<string name="version"></string>

<!-- "dependencies"."inherits" -->
<string name="resolved"></string>

<!-- "dependencies"."inherits" -->
<string name="integrity"></string>

<!-- "dependencies"."ini" -->
<string name="version"></string>

<!-- "dependencies"."ini" -->
<string name="resolved"></string>

<!-- "dependencies"."ini" -->
<string name="integrity"></string>

<!-- "dependencies"."inquirer" -->
<string name="version"></string>

<!-- "dependencies"."inquirer" -->
<string name="resolved"></string>

<!-- "dependencies"."inquirer" -->
<string name="integrity"></string>

<!-- "dependencies"."inquirer" -->
<string name="dev"></string>

<!-- "dependencies"."inquirer"."dependencies"."ansi-regex" -->
<string name="version"></string>

<!-- "dependencies"."inquirer"."dependencies"."ansi-regex" -->
<string name="resolved"></string>

<!-- "dependencies"."inquirer"."dependencies"."ansi-regex" -->
<string name="integrity"></string>

<!-- "dependencies"."inquirer"."dependencies"."ansi-regex" -->
<string name="dev"></string>

<!-- "dependencies"."inquirer"."dependencies"."is-fullwidth-code-point" -->
<string name="version"></string>

<!-- "dependencies"."inquirer"."dependencies"."is-fullwidth-code-point" -->
<string name="resolved"></string>

<!-- "dependencies"."inquirer"."dependencies"."is-fullwidth-code-point" -->
<string name="integrity"></string>

<!-- "dependencies"."inquirer"."dependencies"."is-fullwidth-code-point" -->
<string name="dev"></string>

<!-- "dependencies"."inquirer"."dependencies"."string-width" -->
<string name="version"></string>

<!-- "dependencies"."inquirer"."dependencies"."string-width" -->
<string name="resolved"></string>

<!-- "dependencies"."inquirer"."dependencies"."string-width" -->
<string name="integrity"></string>

<!-- "dependencies"."inquirer"."dependencies"."string-width" -->
<string name="dev"></string>

<!-- "dependencies"."inquirer"."dependencies"."strip-ansi" -->
<string name="version"></string>

<!-- "dependencies"."inquirer"."dependencies"."strip-ansi" -->
<string name="resolved"></string>

<!-- "dependencies"."inquirer"."dependencies"."strip-ansi" -->
<string name="integrity"></string>

<!-- "dependencies"."inquirer"."dependencies"."strip-ansi" -->
<string name="dev"></string>

<!-- "dependencies"."interpret" -->
<string name="version"></string>

<!-- "dependencies"."interpret" -->
<string name="resolved"></string>

<!-- "dependencies"."interpret" -->
<string name="integrity"></string>

<!-- "dependencies"."interpret" -->
<string name="dev"></string>

<!-- "dependencies"."invert-kv" -->
<string name="version"></string>

<!-- "dependencies"."invert-kv" -->
<string name="resolved"></string>

<!-- "dependencies"."invert-kv" -->
<string name="integrity"></string>

<!-- "dependencies"."ipaddr.js" -->
<string name="version"></string>

<!-- "dependencies"."ipaddr.js" -->
<string name="resolved"></string>

<!-- "dependencies"."ipaddr.js" -->
<string name="integrity"></string>

<!-- "dependencies"."ipaddr.js" -->
<string name="dev"></string>

<!-- "dependencies"."is-arrayish" -->
<string name="version"></string>

<!-- "dependencies"."is-arrayish" -->
<string name="resolved"></string>

<!-- "dependencies"."is-arrayish" -->
<string name="integrity"></string>

<!-- "dependencies"."is-builtin-module" -->
<string name="version"></string>

<!-- "dependencies"."is-builtin-module" -->
<string name="resolved"></string>

<!-- "dependencies"."is-builtin-module" -->
<string name="integrity"></string>

<!-- "dependencies"."is-callable" -->
<string name="version"></string>

<!-- "dependencies"."is-callable" -->
<string name="resolved"></string>

<!-- "dependencies"."is-callable" -->
<string name="integrity"></string>

<!-- "dependencies"."is-callable" -->
<string name="dev"></string>

<!-- "dependencies"."is-date-object" -->
<string name="version"></string>

<!-- "dependencies"."is-date-object" -->
<string name="resolved"></string>

<!-- "dependencies"."is-date-object" -->
<string name="integrity"></string>

<!-- "dependencies"."is-date-object" -->
<string name="dev"></string>

<!-- "dependencies"."is-finite" -->
<string name="version"></string>

<!-- "dependencies"."is-finite" -->
<string name="resolved"></string>

<!-- "dependencies"."is-finite" -->
<string name="integrity"></string>

<!-- "dependencies"."is-fullwidth-code-point" -->
<string name="version"></string>

<!-- "dependencies"."is-fullwidth-code-point" -->
<string name="resolved"></string>

<!-- "dependencies"."is-fullwidth-code-point" -->
<string name="integrity"></string>

<!-- "dependencies"."is-my-json-valid" -->
<string name="version"></string>

<!-- "dependencies"."is-my-json-valid" -->
<string name="resolved"></string>

<!-- "dependencies"."is-my-json-valid" -->
<string name="integrity"></string>

<!-- "dependencies"."is-my-json-valid" -->
<string name="dev"></string>

<!-- "dependencies"."is-npm" -->
<string name="version"></string>

<!-- "dependencies"."is-npm" -->
<string name="resolved"></string>

<!-- "dependencies"."is-npm" -->
<string name="integrity"></string>

<!-- "dependencies"."is-obj" -->
<string name="version"></string>

<!-- "dependencies"."is-obj" -->
<string name="resolved"></string>

<!-- "dependencies"."is-obj" -->
<string name="integrity"></string>

<!-- "dependencies"."is-path-cwd" -->
<string name="version"></string>

<!-- "dependencies"."is-path-cwd" -->
<string name="resolved"></string>

<!-- "dependencies"."is-path-cwd" -->
<string name="integrity"></string>

<!-- "dependencies"."is-path-cwd" -->
<string name="dev"></string>

<!-- "dependencies"."is-path-in-cwd" -->
<string name="version"></string>

<!-- "dependencies"."is-path-in-cwd" -->
<string name="resolved"></string>

<!-- "dependencies"."is-path-in-cwd" -->
<string name="integrity"></string>

<!-- "dependencies"."is-path-in-cwd" -->
<string name="dev"></string>

<!-- "dependencies"."is-path-inside" -->
<string name="version"></string>

<!-- "dependencies"."is-path-inside" -->
<string name="resolved"></string>

<!-- "dependencies"."is-path-inside" -->
<string name="integrity"></string>

<!-- "dependencies"."is-path-inside" -->
<string name="dev"></string>

<!-- "dependencies"."is-property" -->
<string name="version"></string>

<!-- "dependencies"."is-property" -->
<string name="resolved"></string>

<!-- "dependencies"."is-property" -->
<string name="integrity"></string>

<!-- "dependencies"."is-property" -->
<string name="dev"></string>

<!-- "dependencies"."is-redirect" -->
<string name="version"></string>

<!-- "dependencies"."is-redirect" -->
<string name="resolved"></string>

<!-- "dependencies"."is-redirect" -->
<string name="integrity"></string>

<!-- "dependencies"."is-regex" -->
<string name="version"></string>

<!-- "dependencies"."is-regex" -->
<string name="resolved"></string>

<!-- "dependencies"."is-regex" -->
<string name="integrity"></string>

<!-- "dependencies"."is-regex" -->
<string name="dev"></string>

<!-- "dependencies"."is-resolvable" -->
<string name="version"></string>

<!-- "dependencies"."is-resolvable" -->
<string name="resolved"></string>

<!-- "dependencies"."is-resolvable" -->
<string name="integrity"></string>

<!-- "dependencies"."is-resolvable" -->
<string name="dev"></string>

<!-- "dependencies"."is-retry-allowed" -->
<string name="version"></string>

<!-- "dependencies"."is-retry-allowed" -->
<string name="resolved"></string>

<!-- "dependencies"."is-retry-allowed" -->
<string name="integrity"></string>

<!-- "dependencies"."is-stream" -->
<string name="version"></string>

<!-- "dependencies"."is-stream" -->
<string name="resolved"></string>

<!-- "dependencies"."is-stream" -->
<string name="integrity"></string>

<!-- "dependencies"."is-symbol" -->
<string name="version"></string>

<!-- "dependencies"."is-symbol" -->
<string name="resolved"></string>

<!-- "dependencies"."is-symbol" -->
<string name="integrity"></string>

<!-- "dependencies"."is-symbol" -->
<string name="dev"></string>

<!-- "dependencies"."is-utf8" -->
<string name="version"></string>

<!-- "dependencies"."is-utf8" -->
<string name="resolved"></string>

<!-- "dependencies"."is-utf8" -->
<string name="integrity"></string>

<!-- "dependencies"."isarray" -->
<string name="version"></string>

<!-- "dependencies"."isarray" -->
<string name="resolved"></string>

<!-- "dependencies"."isarray" -->
<string name="integrity"></string>

<!-- "dependencies"."isexe" -->
<string name="version"></string>

<!-- "dependencies"."isexe" -->
<string name="resolved"></string>

<!-- "dependencies"."isexe" -->
<string name="integrity"></string>

<!-- "dependencies"."jpeg-js" -->
<string name="version"></string>

<!-- "dependencies"."jpeg-js" -->
<string name="resolved"></string>

<!-- "dependencies"."jpeg-js" -->
<string name="integrity"></string>

<!-- "dependencies"."js-tokens" -->
<string name="version"></string>

<!-- "dependencies"."js-tokens" -->
<string name="resolved"></string>

<!-- "dependencies"."js-tokens" -->
<string name="integrity"></string>

<!-- "dependencies"."js-tokens" -->
<string name="dev"></string>

<!-- "dependencies"."js-yaml" -->
<string name="version"></string>

<!-- "dependencies"."js-yaml" -->
<string name="resolved"></string>

<!-- "dependencies"."js-yaml" -->
<string name="integrity"></string>

<!-- "dependencies"."js-yaml" -->
<string name="dev"></string>

<!-- "dependencies"."json-stable-stringify" -->
<string name="version"></string>

<!-- "dependencies"."json-stable-stringify" -->
<string name="resolved"></string>

<!-- "dependencies"."json-stable-stringify" -->
<string name="integrity"></string>

<!-- "dependencies"."json-stable-stringify" -->
<string name="dev"></string>

<!-- "dependencies"."json-stringify-safe" -->
<string name="version"></string>

<!-- "dependencies"."json-stringify-safe" -->
<string name="resolved"></string>

<!-- "dependencies"."json-stringify-safe" -->
<string name="integrity"></string>

<!-- "dependencies"."json3" -->
<string name="version"></string>

<!-- "dependencies"."json3" -->
<string name="resolved"></string>

<!-- "dependencies"."json3" -->
<string name="integrity"></string>

<!-- "dependencies"."json3" -->
<string name="dev"></string>

<!-- "dependencies"."jsonify" -->
<string name="version"></string>

<!-- "dependencies"."jsonify" -->
<string name="resolved"></string>

<!-- "dependencies"."jsonify" -->
<string name="integrity"></string>

<!-- "dependencies"."jsonify" -->
<string name="dev"></string>

<!-- "dependencies"."jsonpointer" -->
<string name="version"></string>

<!-- "dependencies"."jsonpointer" -->
<string name="resolved"></string>

<!-- "dependencies"."jsonpointer" -->
<string name="integrity"></string>

<!-- "dependencies"."jsonpointer" -->
<string name="dev"></string>

<!-- "dependencies"."jsx-ast-utils" -->
<string name="version"></string>

<!-- "dependencies"."jsx-ast-utils" -->
<string name="resolved"></string>

<!-- "dependencies"."jsx-ast-utils" -->
<string name="integrity"></string>

<!-- "dependencies"."jsx-ast-utils" -->
<string name="dev"></string>

<!-- "dependencies"."latest-version" -->
<string name="version"></string>

<!-- "dependencies"."latest-version" -->
<string name="resolved"></string>

<!-- "dependencies"."latest-version" -->
<string name="integrity"></string>

<!-- "dependencies"."lcid" -->
<string name="version"></string>

<!-- "dependencies"."lcid" -->
<string name="resolved"></string>

<!-- "dependencies"."lcid" -->
<string name="integrity"></string>

<!-- "dependencies"."levn" -->
<string name="version"></string>

<!-- "dependencies"."levn" -->
<string name="resolved"></string>

<!-- "dependencies"."levn" -->
<string name="integrity"></string>

<!-- "dependencies"."levn" -->
<string name="dev"></string>

<!-- "dependencies"."lighthouse" -->
<string name="version"></string>

<!-- "dependencies"."lighthouse" -->
<string name="resolved"></string>

<!-- "dependencies"."lighthouse" -->
<string name="integrity"></string>

<!-- "dependencies"."lighthouse"."dependencies"."ansi-regex" -->
<string name="version"></string>

<!-- "dependencies"."lighthouse"."dependencies"."ansi-regex" -->
<string name="resolved"></string>

<!-- "dependencies"."lighthouse"."dependencies"."ansi-regex" -->
<string name="integrity"></string>

<!-- "dependencies"."lighthouse"."dependencies"."is-fullwidth-code-point" -->
<string name="version"></string>

<!-- "dependencies"."lighthouse"."dependencies"."is-fullwidth-code-point" -->
<string name="resolved"></string>

<!-- "dependencies"."lighthouse"."dependencies"."is-fullwidth-code-point" -->
<string name="integrity"></string>

<!-- "dependencies"."lighthouse"."dependencies"."string-width" -->
<string name="version"></string>

<!-- "dependencies"."lighthouse"."dependencies"."string-width" -->
<string name="resolved"></string>

<!-- "dependencies"."lighthouse"."dependencies"."string-width" -->
<string name="integrity"></string>

<!-- "dependencies"."lighthouse"."dependencies"."strip-ansi" -->
<string name="version"></string>

<!-- "dependencies"."lighthouse"."dependencies"."strip-ansi" -->
<string name="resolved"></string>

<!-- "dependencies"."lighthouse"."dependencies"."strip-ansi" -->
<string name="integrity"></string>

<!-- "dependencies"."lighthouse"."dependencies"."yargs" -->
<string name="version"></string>

<!-- "dependencies"."lighthouse"."dependencies"."yargs" -->
<string name="resolved"></string>

<!-- "dependencies"."lighthouse"."dependencies"."yargs" -->
<string name="integrity"></string>

<!-- "dependencies"."lighthouse-logger" -->
<string name="version"></string>

<!-- "dependencies"."lighthouse-logger" -->
<string name="resolved"></string>

<!-- "dependencies"."lighthouse-logger" -->
<string name="integrity"></string>

<!-- "dependencies"."load-json-file" -->
<string name="version"></string>

<!-- "dependencies"."load-json-file" -->
<string name="resolved"></string>

<!-- "dependencies"."load-json-file" -->
<string name="integrity"></string>

<!-- "dependencies"."locate-path" -->
<string name="version"></string>

<!-- "dependencies"."locate-path" -->
<string name="resolved"></string>

<!-- "dependencies"."locate-path" -->
<string name="integrity"></string>

<!-- "dependencies"."locate-path"."dependencies"."path-exists" -->
<string name="version"></string>

<!-- "dependencies"."locate-path"."dependencies"."path-exists" -->
<string name="resolved"></string>

<!-- "dependencies"."locate-path"."dependencies"."path-exists" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash" -->
<string name="version"></string>

<!-- "dependencies"."lodash" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash._baseassign" -->
<string name="version"></string>

<!-- "dependencies"."lodash._baseassign" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash._baseassign" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash._baseassign" -->
<string name="dev"></string>

<!-- "dependencies"."lodash._basecopy" -->
<string name="version"></string>

<!-- "dependencies"."lodash._basecopy" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash._basecopy" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash._basecopy" -->
<string name="dev"></string>

<!-- "dependencies"."lodash._basecreate" -->
<string name="version"></string>

<!-- "dependencies"."lodash._basecreate" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash._basecreate" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash._basecreate" -->
<string name="dev"></string>

<!-- "dependencies"."lodash._getnative" -->
<string name="version"></string>

<!-- "dependencies"."lodash._getnative" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash._getnative" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash._getnative" -->
<string name="dev"></string>

<!-- "dependencies"."lodash._isiterateecall" -->
<string name="version"></string>

<!-- "dependencies"."lodash._isiterateecall" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash._isiterateecall" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash._isiterateecall" -->
<string name="dev"></string>

<!-- "dependencies"."lodash.cond" -->
<string name="version"></string>

<!-- "dependencies"."lodash.cond" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash.cond" -->
<string name="integrity"></string>

<!-- "dependencies"."lodash.cond" -->
<string name="dev"></string>

<!-- "dependencies"."lodash.create" -->
<string name="version"></string>

<!-- "dependencies"."lodash.create" -->
<string name="resolved"></string>

<!-- "dependencies"."lodash.create" -->
<string name="integrity"></string>
</resources>