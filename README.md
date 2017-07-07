# \<resources-converter\>

String resources converter - convert from Java *.properties to Android strings format.
Also replaces "." by "_". Loads data using HTML5, nothing is transferred anywhere, all is done by local javascript. 

The result is just printed on page. So you can copy-paste it to your local strings.xml file.


[Running site](https://coplas.github.io/resources-converter/)

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.


## Running example