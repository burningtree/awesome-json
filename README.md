# Awesome JSON
A curated list of awesome JSON libraries and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

* [Awesome JSON](#awesome-json)
  * [Command-line tools](#command-line-tools)
  * [Databases](#databases)
  * [Data modeling](#data-modeling)
  * [Differencing](#differencing)
  * [Extensions](#extensions)
  * [Libraries](#libraries)
  * [Linters](#linters)
  * [Online tools](#online-tools)
  * [Binary Serialization](#binary-serialization)
  * [Streams](#streams)
  * [Successors](#successors)
  * [Templating](#templating)
  * [Transforming](#transforming)
  * [Querying](#querying)
  * [JSON Schema Editors](#json-schema-editors)
  * [JSON Schema Tools](#json-schema-tools)
  * [JSON Schema Resources](#json-schema-resources)
  * [JSON Schema Validators](#json-schema-validators)
  * [Contribute](#contribute)

## Command-line tools
* [jq](http://stedolan.github.io/jq/) - A lightweight and flexible command-line JSON processor.
* [json](http://trentm.com/json) - A "json" command for massaging JSON on your Unix command line.
* [jshon](http://kmkeen.com/jshon/) - A parser designed for maximum convenience within the shell.

## Databases
* [MongoDB](https://www.mongodb.org/) - an open-source document database, and the leading NoSQL database.
* [RethinkDB](http://www.rethinkdb.com/) - An open-source distributed JSON document database with a pleasant and powerful query language.
* [lowdb](https://github.com/typicode/lowdb) - Flat JSON file database built on lodash API.
* [Lawnchair](http://brian.io/lawnchair/) - A lightweight clientside JSON document store.

## Data modeling
* [JSONModel](http://www.jsonmodel.com/) - Magical Data Modelling Framework for JSON. (Objective-C)

## Differencing
* [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - Diff & patch for JavaScript objects. (Javascript)
* [jiff](https://github.com/cujojs/jiff) - JSON Patch and diff based on rfc6902. (Javascript)
* [dffptch](https://github.com/paldepind/dffptch) - A micro library for diffing and patching JSON objects using a compact diff format. (Javascript)

## Editors
* [JSONEdit](http://mb21.github.io/JSONedit/) - User friendly, visual JSON editor built as an AngularJS directive.

## Extensions
* [GeoJSON](http://geojson.org/) - A geospatial data interchange format.
* [JSON-LD](http://json-ld.org/) - A lightweight Linked Data format.
* [JSON API](http://jsonapi.org/) - A standard for building APIs in JSON.
* [JSON-RPC](http://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol. 
* [JSON Web Tokens](http://jwt.io/) - A compact URL-safe means of representing claims to be transferred between two parties.
* [JSON Resume](https://jsonresume.org/) - The open source initiative to create a JSON-based standard for resumes.
* [JsonML](http://www.jsonml.org/) - A compact format for transporting XML-based markup as JSON which allows it to be losslessly converted back to its original form.
* [JSONP](http://www.json-p.org/) - Safer cross-domain Ajax with JSON-P/JSONP.

## Libraries
**C**
* [Jansson](http://www.digip.org/jansson/) - A C library for encoding, decoding and manipulating JSON data.

**C++**
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson) - An efficient JSON library for embedded systems.

**Java**
* [Fast JSON Processor](https://github.com/alibaba/fastjson)
* [Gson](https://code.google.com/p/google-gson/) - A Java library to convert JSON to Java objects and vice-versa.
* [Jackson](http://wiki.fasterxml.com/JacksonHome) - A multi-purpose Java library for processing JSON data format.

**Javascript**
* [JSON-js](https://github.com/douglascrockford/JSON-js) - JSON in JavaScript.
* [JSON 3](http://bestiejs.github.io/json3/) - A modern JSON implementation.

**Objective-C**
* [JSONKit](https://github.com/johnezang/JSONKit) - Objective-C JSON.
* [SBJson](http://www.sbjson.org/) - Parse one or more chunks of JSON data.

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

## Binary Serialization
* [MessagePack](http://msgpack.org/) - An extremely efficient object serialization library. It's like JSON, but very fast and small.
* [BSON](http://bsonspec.org/) - Binary JSON.
* [UBJSON](http://ubjson.org/) - The universally compatible format specification for binary JSON.
* [CBOR](http://tools.ietf.org/html/rfc7049) - Concise Binary Object Representation.
* [Smile](http://wiki.fasterxml.com/SmileFormatSpec) - A efficient JSON-compatible binary data format.

## Streams
* [oboe.js](http://oboejs.com/) - A streaming approach to JSON. Speeds up web applications by providing parsed objects before the response completes. (Javascript)

## Successors
* [YAML](http://yaml.org) - A human friendly data serialization standard for all programming languages. Technically YAML is a superset of JSON.
* [AXON](http://intellimath.bitbucket.org/axon/#) - A simple text based format for interchanging of objects, documents and data. It tries to combine the best of JSON, XML and YAML.
* [CSON](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. Same as JSON but for CoffeeScript objects.

## Templating
* [rabl](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support. (Ruby)

## Transforming
* [json2json](https://github.com/joelvh/json2json) - Transform (reformat) JSON structures from one to another. (Javascript)
* [trans](https://github.com/gabesoft/trans) - The ultimate object transformer. (Javascript)

## Querying
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

## JSON Schema Tools
* [prmd](https://github.com/interagent/prmd) - JSON Schema tools and doc generation for HTTP APIs.
* [generate-schema](https://github.com/Nijikokun/generate-schema) - Effortlessly convert your JSON Object to JSON Schema, Mongoose Schema, or a Generic template for quick documentation / upstart.

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
