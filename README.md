# grunt-ceci-schema

> Grunt ceci-schema validation task

## Getting Started
This plugin requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-ceci-schema --save-dev
```

One the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-json-schema');
```

## The "ceci_schema" task

### Overview
In your project's Gruntfile, add a section named `ceci_schema` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  json_schema: {
    test: {
      options: {
        // ceci-schema specific options go here
      },
      files: {
        // components we want to check
      } 
    }
  }
})
```

### Usage Examples

#### Default Options
In this example we check component.html

```js
grunt.initConfig({
  ceci_schema: {
    test: {
      options: {},
      files: ['component.html']
      } 
    }
  }
})
```
