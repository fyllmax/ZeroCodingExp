# Lets install bower

``` npm install -g bower ````

# Now we need to initialize **bower.json**

``` bower init ```

> At the end your bower.json will look like this example:
{
  "name": "my-project",
  "version": "1.0.0",
  "main": "path/to/main.css",
  "ignore": [
    ".jshintrc",
    "**/*.txt"
  ],
  "description": "A simple UI to display a table of students",
  "main": "index.html",
  "license": "MIT",
  "private": true,
  "ignore": [
    "**/.*",
    "node_modules",
    "bower_components",
    "test",
    "tests"
  ],
  "dependencies": {
    "bootstrap": "~3.1.1"
  }
}

# To install all dependecies you do this:
```bower install```

# To add more dependecies, its done like this:

``` bower install <dependecies> --save```

