# Polymer TodoMVC Example

> Polymer is a new type of library for the web, built on top of Web Components, and designed to leverage the evolving web platform on modern browsers.

> _[Polymer - www.polymer-project.org](http://www.polymer-project.org/)_

## Learning Polymer

The [Polymer website](http://www.polymer-project.org) is a great resource for getting started.

Here are some links you may find helpful:

* [Getting Started](http://www.polymer-project.org/getting-started.html)
* [FAQ](http://www.polymer-project.org/faq.html)
* [Browser Compatibility](http://www.polymer-project.org/compatibility.html)

Get help from Polymer devs and users:

* Find us on IRC on __#polymer__ at freenode.
* Join the high-traffic [polymer-dev](https://groups.google.com/forum/?fromgroups=#!forum/polymer-dev) Google group or the announcement-only [polymer-announce](https://groups.google.com/forum/?fromgroups=#!forum/polymer-announce) Google group.

## Implementation

The Polymer implementation of TodoMVC has a few key differences with other implementations:

* Since Web Componennts allow you to create new types of DOM elements, the DOM tree is very different from other implementations.
* The template, styling, and behavior are fully encapsulated in each custom element. Instead of having an overall stylesheet (`base.css` or `app.css`), each element that needs styling has its own stylesheet.
* Non-visual elements such as the router and the model are also implemented as custom elements and appear in the DOM.

## Compatibility

Polymer and its polyfills are intended to work in the latest version of "evergreen" browsers. IE9 is not supported. Please refer to [Browser Compatibility](http://www.polymer-project.org/compatibility.html) for more details.
