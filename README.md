
# meow

A fork of **quackbarc**'s client for noz.rip mainly for personal use.

**QB**'s client: https://github.com/quackbarc/sketch
## Turbovibed clanked code
This would have been impossible to do from scratch, all credit goes to **QB**'s wonderful code

**Notable changes:**
- Vector rendering (and a Mixed option with a vector base with a bit of raster filtering)
- Vector smoothing to remove line jaggedness, especially on very slow strokes
- Adjusted and removed settings
- Different button layout
- Slightly adjusted zooming functionality

---

## Development

If you ever wish to work on the client on your own machine:

1. Make sure you have [Bower](https://www.npmjs.com/package/bower) and the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed in your system.
2. Clone the repository.
3. Navigate to the cloned repository, then run `bower install` on it to install project dependencies.

All the other commands listed below will assume your terminal is currently on the clone repository.

### Serving

```sh
$ polymer serve
```

This should serve the whole client locally onto localhost (the port will be shown on the console).
You could also use other methods that start a file server, e.g.
`npx http-server` ([ref](https://www.npmjs.com/package/http-server#installation)).

### Building

```sh
$ polymer build
```

This should build a minified ES6-compatible version onto `build/es6-bundled/`, as per the project's polymer.json.
To serve the build with the same Polymer CLI:

```sh
$ polymer serve build/es6-bundled
```

### Additional resources

- Documentation for Polymer 1.0: https://polymer-library.polymer-project.org/1.0/docs/devguide/feature-overview
- Custom MDI icons taken from https://pictogrammers.com/library/mdi/ (under Apache 2.0).

---
