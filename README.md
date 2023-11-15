# DDEV selenium

Provide selenium setup with a default chrome node, with possibilities to add more nodes of several browsers.

The main purpose of this addon is allowing developers to have a base setup of selenium
that allows to be extendeds with more selenium nodes like chrome, firefox, or edge. Having
more nodes attached to the same hub not only allows having several browsers, but load balancing
when there are parallel tests being run on the same hub.

## Installation

Install this addon by running:

```
ddev get metadrop/ddev-selenium
```

## Architecture

The addon contains:

- Selenium hub
- Selenium node for chrome

It is possible to add attach additional nodes to the selenium by adding more services to the ddev setup.
