# <tc-countdown\>

### tc-countdown
An element to track the amount of time until a given time has reached. 
It exposes a set of properties to detect the amount of time left.

Sample demo:

    <tc-countdown 
        target-date="2016-12-25" 
        target-time="23:00:00" 
        timezone-offset="+05:00"
        time-remaining="{{remaining}}"></tc-countdown>

    <p>{{remaining.days}}, {{remaining.hours}}, {{remaining.minutes}}</p>

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

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
