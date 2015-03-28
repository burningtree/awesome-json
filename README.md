# Awesome JSON
A curated list of awesome JSON libraries and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

* [Awesome JSON](#awesome-json)
  * [Browser Extensions](#browser-extensions) 
  * [Command-line tools](#command-line-tools)
  * [Databases](#databases)
  * [Datasets](#datasets)
  * [Data modeling](#data-modeling)
  * [Differencing](#differencing)
  * [Format Extensions](#format-extensions)
  * [Libraries](#libraries)
  * [Linters](#linters)
  * [Online tools](#online-tools)
  * [Binary Serialization](#binary-serialization)
  * [Services](#services)
  * [Successors](#successors)
  * [References](#references)
  * [Templates](#templates)
  * [Transformations](#transformations)
  * [Queries](#queries)
  * [JSON Schema Editors](#json-schema-editors)
  * [JSON Schema Tools](#json-schema-tools)
  * [JSON Schema Resources](#json-schema-resources)
  * [JSON Schema Validators](#json-schema-validators)
  * [Contribute](#contribute)

## Browser Extensions
**Chrome**
* [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) ([github](https://github.com/callumlocke/json-formatter)) - Makes JSON easy to read. Open source.
* [JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh) ([github](https://github.com/tulios/json-viewer)) - It is a Chrome extension for printing JSON and JSONP.
* [JaSON](https://chrome.google.com/webstore/detail/oealdlhfjifhgbmjnenhkgffglaibojf) ([github](https://github.com/shanebell/JaSON)) - Plugin for testing JSON and XML web services.
* [JSON Browser](https://chrome.google.com/webstore/detail/json-browser/hngfgkmimoikmpohakflgadcajkfnoba) ([github](https://github.com/platy/json-browser/)) - Browse a JSON web with the help of JSON schemas.
* [JSON Finder](https://chrome.google.com/webstore/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj) ([github](https://github.com/rapee/jsonfinder)) - Browse JSON like you do it in Finder.

**Firefox**
* [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/) ([github](https://github.com/bhollis/jsonview)) - View JSON documents in the browser.
* [JSON-DataView](https://addons.mozilla.org/en-us/firefox/addon/json-dataview/) ([github](https://github.com/warren-bank/moz-json-data-view)) - Displays JSON data in a collapsible tree structure with syntax highlights.

**Safari**
* [JSONAce](https://extensions.apple.com/details/?id=com.acrogenesis.jsonace-56Q494QF3L) ([github](https://github.com/acrogenesis/JSONAce)) - Formats & syntax highlights JSON viewed inside of the web browser using the ACE editor.
* [JSONView](https://extensions.apple.com/details/?id=com.acrogenesis.jsonview-56Q494QF3L) ([github](https://github.com/acrogenesis/jsonview-safari)) - A port of the JSONView Firefox extension that formats and syntax highlights JSON viewed inside of the browser

## Command-line tools
* [jq](http://stedolan.github.io/jq/) - A lightweight and flexible command-line JSON processor.
* [json](http://trentm.com/json) - A "json" command for massaging JSON on your Unix command line.
* [jshon](http://kmkeen.com/jshon/) - A parser designed for maximum convenience within the shell.

## Databases
* [MongoDB](https://www.mongodb.org/) - an open-source document database, and the leading NoSQL database.
* [RethinkDB](http://www.rethinkdb.com/) - An open-source distributed JSON document database with a pleasant and powerful query language.
* [lowdb](https://github.com/typicode/lowdb) - Flat JSON file database built on lodash API.
* [Lawnchair](http://brian.io/lawnchair/) - A lightweight clientside JSON document store.

## Datasets
* [countries](https://github.com/mledoze/countries) - World countries.
* [MTG JSON](http://mtgjson.com/) - Up to date Magic the Gathering card data.
* [Heartstone JSON](http://hearthstonejson.com/) - Up to date Hearthstone card data.

## Data modeling
* [JSONModel](http://www.jsonmodel.com/) - Magical Data Modelling Framework for JSON. (Objective-C)

## Differencing
* [JSONPatch](http://jsonpatch.com/) - A format for describing changes to a JSON document.
* [JSON-Patch](https://github.com/Starcounter-Jack/JSON-Patch) - Lean and mean Javascript implementation of the JSON-Patch standard (RFC 6902). (Javascript)
* [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - Diff & patch for JavaScript objects. (Javascript)
* [jiff](https://github.com/cujojs/jiff) - JSON Patch and diff based on rfc6902. (Javascript)
* [dffptch](https://github.com/paldepind/dffptch) - A micro library for diffing and patching JSON objects using a compact diff format. (Javascript)
* [json-patch-php](https://github.com/mikemccabe/json-patch-php) - implementation of JSON-patch (IETF RFC 6902) (PHP)

## Editors
* [JSONEdit](http://mb21.github.io/JSONedit/) - User friendly, visual JSON editor built as an AngularJS directive.

## Format Extensions
* [GeoJSON](http://geojson.org/) - A geospatial data interchange format.
* [JSON-LD](http://json-ld.org/) - A lightweight Linked Data format.
* [JSON-RPC](http://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
* [JSONP](http://www.json-p.org/) - Safer cross-domain Ajax with JSON-P/JSONP.
* [JsonML](http://www.jsonml.org/) - A compact format for transporting XML-based markup as JSON which allows it to be losslessly converted back to its original form.
* [JSON5](http://json5.org/) - a extension to JSON that aims to make it easier for humans to write and maintain by hand.
* [JSON Resume](https://jsonresume.org/) - The open source initiative to create a JSON-based standard for resumes.
* [JSON Web Tokens](http://jwt.io/) - A compact URL-safe means of representing claims to be transferred between two parties.
* [JSON API](http://jsonapi.org/) - A standard for building APIs in JSON.
* [Collection+JSON](http://amundsen.com/media-types/collection/) - A read/write hypermedia-type designed to support management and querying of simple collections.
* [hal-json](http://stateless.co/hal_specification.html) - A set of conventions for expressing hyperlinks in either JSON or XML.
* [JSON Activity Streams](http://activitystrea.ms/) - A format for syndicating social activities around the web.
* [JSON-stat](https://github.com/jsonstat/jsonstat) - Simple lightweight JSON format for data dissemination.

## Libraries
**C**
* [Jansson](http://www.digip.org/jansson/) - A C library for encoding, decoding and manipulating JSON data.
* [jsmn](http://zserge.com/jsmn.html) - A minimalistic JSON parser in C. It can be easily integrated into the resource-limited projects or embedded systems.

**C++**
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson) - An efficient JSON library for embedded systems.
* [JSON++](https://github.com/tunnuz/json) - A self contained Flex/Bison JSON parser for C++11.

**Clojure**
* [data.json](https://github.com/clojure/data.json) - JSON parser/generator to/from Clojure data structures.

**Java**
* [Fast JSON Processor](https://github.com/alibaba/fastjson)
* [Gson](https://code.google.com/p/google-gson/) - A Java library to convert JSON to Java objects and vice-versa.
* [Jackson](http://wiki.fasterxml.com/JacksonHome) - A multi-purpose Java library for processing JSON data format.

**Javascript**
* [JSON-js](https://github.com/douglascrockford/JSON-js) - JSON in JavaScript.
* [JSON 3](http://bestiejs.github.io/json3/) - A modern JSON implementation.
* [oboe.js](http://oboejs.com/) - A streaming approach to JSON. Speeds up web applications by providing parsed objects before the response completes.

**Objective-C**
* [JSONKit](https://github.com/johnezang/JSONKit) - Objective-C JSON.
* [SBJson](http://www.sbjson.org/) - Parse one or more chunks of JSON data.

**Python**
* [simplejson](https://github.com/simplejson/simplejson) - a simple, fast, extensible JSON encoder/decoder

**Ruby**
* [oj](https://github.com/ohler55/oj) - A fast JSON parser and Object marshaller as a Ruby gem.

**Swift**
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift.

## Linters
* [jsonlint](https://github.com/zaach/jsonlint) - A JSON parser and validator with a CLI. (Javascript)

## Online tools
* [JSON Editor online](http://jsoneditoronline.org/) - A web-based tool to view, edit and format JSON.
* [geojson.io](http://geojson.io/) - Simply edit GeoJSON map data.
* [Collapsible JSON Formatter](http://www.bodurov.com/JsonFormatter/) - Formatter and Colorer of Raw JSON Code.
* [JSON Generator](http://www.json-generator.com/) - Tool for generating random data.
* [jq play](https://jqplay.org/) - A playground for jq.
* [json2csharp](http://json2csharp.com/) - Generate c# classes from a json string or url.

## Binary Serialization
* [MessagePack](http://msgpack.org/) - An extremely efficient object serialization library. It's like JSON, but very fast and small.
* [BSON](http://bsonspec.org/) - Binary JSON.
* [UBJSON](http://ubjson.org/) - The universally compatible format specification for binary JSON.
* [CBOR](http://tools.ietf.org/html/rfc7049) - Concise Binary Object Representation.
* [Smile](http://wiki.fasterxml.com/SmileFormatSpec) - A efficient JSON-compatible binary data format.

## Services
* [Myjson](http://myjson.com/) - A simple JSON store for your web or mobile app.
* [JSON Test](http://www.jsontest.com/) - Testing platform for services utilizing JavaScript Object Notation (JSON).
* [Telize](http://www.telize.com/) - JSON IP and GeoIP REST API.

## Successors
* [YAML](http://yaml.org) - A human friendly data serialization standard for all programming languages. Technically YAML is a superset of JSON.
* [AXON](http://intellimath.bitbucket.org/axon/#) - A simple text based format for interchanging of objects, documents and data. It tries to combine the best of JSON, XML and YAML.
* [CSON](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. Same as JSON but for CoffeeScript objects.

## References
* [Introducing JSON](http://json.org/)
* [JSON Tutorial](http://www.w3resource.com/JSON/introduction.php) - An introductory tutorial on JSON - JavaScript Object Notation.

## Templates
* [rabl](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support. (Ruby)

## Transformations
* [json2json](https://github.com/joelvh/json2json) - Transform (reformat) JSON structures from one to another. (Javascript)
* [trans](https://github.com/gabesoft/trans) - The ultimate object transformer. (Javascript)
* [osmtogeojson](https://github.com/tyrasd/osmtogeojson) - Converts OSM data to GeoJSON. (Javascript)
* [x2js](https://code.google.com/p/x2js/) - XML to JSON and vice versa javascript conversion functions. (Javascript)

## Queries
* [JMESPath](http://jmespath.org/) - A query language for JSON.
* [JSON Mask](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting specific parts of a JS object, hiding the rest. (Javascript)
* [JSONiq](http://www.jsoniq.org/) - The JSON Query Language.
* [ObjectPath](http://objectpath.org/) - The agile query language for semi-structured data. (Python)
* [DefiantJS](http://www.defiantjs.com/) - Lightning-fast searches on JSON using XPath expressions, and transform JSON using XSL. (Javascript)
* [JSONSelect](http://jsonselect.org/) - CSS-like selectors for JSON. (Javascript)
* [JSONPath](http://goessner.net/articles/JsonPath/) - XPath for JSON. (Javascript/PHP)
* [searchjs](https://github.com/deitch/searchjs) - A library for filtering JavaScript objects based on a json SQL-like language.

## JSON Schema Editors
* [JSON Editor](https://github.com/jdorn/json-editor) - JSON Schema Based Editor. (Javascript)
* [angular-schema-form](https://github.com/Textalk/angular-schema-form) - Generate forms from a JSON schema, with AngularJS.

## JSON Schema Tools
* [prmd](https://github.com/interagent/prmd) - JSON Schema tools and doc generation for HTTP APIs.
* [generate-schema](https://github.com/Nijikokun/generate-schema) - Effortlessly convert your JSON Object to JSON Schema, Mongoose Schema, or a Generic template for quick documentation / upstart.
* [Docson](https://github.com/lbovet/docson) - Documentation for your JSON types.
* [Orderly JSON](http://orderly-json.org/) - A textual format for describing JSON compiled into JSONSchema. It is designed to be easy to read and write.
* [jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo) - Generates Java types from JSON Schema (or example JSON) and annotates those types for data-binding with Jackson 1.x or 2.x, Gson, etc.

## JSON Schema Resources
* [JSON Schema Store](http://schemastore.org/) - A collection of popular JSON schemas.
* [Understanding JSON Schema](http://spacetelescope.github.io/understanding-json-schema/) - A website aiming to provide more accessible documentation for JSON schema.

## JSON Schema Validators
**Javascript and Node.js**
* [json-schema-benchmark](https://github.com/ebdrup/json-schema-benchmark) - Performance benchmark for Node.js validators.
* [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - A validator that uses code generation to be extremely fast.
* [jsen](https://github.com/bugventure/jsen) - A validator built for speed.
* [themis](https://github.com/playlyfe/themis) - A blazing fast validator.
* [jsck](https://github.com/pandastrike/jsck) - JSON Schema Compiled checK.
* [z-schema](https://github.com/zaggino/z-schema) - validator written in JavaScript for NodeJS and Browsers.
* [jjv](https://github.com/acornejo/jjv) - Javascript Library for Schema Validation.
* [request-validator](https://github.com/bugventure/request-validator) - Flexible request validator middleware for express and connect.
* [tv4](https://github.com/geraintluff/tv4) - Tiny Validator.

## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
