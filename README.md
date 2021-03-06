# [WIP] Ember Freestyle [![Build Status](https://travis-ci.org/chrislopresto/ember-freestyle.svg?branch=master)](https://travis-ci.org/chrislopresto/ember-freestyle)

Ember Freestyle is an Ember addon that allows you to quickly create a living styleguide for your Ember app.

*This is a work in progress.*

## Installation

This installation process is opinionated in order to get you going quickly. We want to make everything much easier to use in the near future. Please report any problems, and as always, PRs are welcome.

1. `ember install ember-freestyle`

    This will do the following:

    - Install the `ember-freestyle` addon itself
    - Install additional highlight.js and remarkable dependencies (which will eventually be made optional)
    - Add a `freestyle` template in your app
    - Add a `freestyle` controller in your app
    - Add an `app.scss` file with the required SCSS
        - You can type `n` to decline this.
        - The only part you actually need is `@import 'ember-freestyle';`

    *Note:* Ember CLI versions < 0.2.3 should use `ember install:addon` instead of `ember install`

1. Add `this.route('freestyle');` to your `router.js` file
1. Navigate to `/freestyle`. You should now see something like:
    ![](public/freestyle-generated.png)

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `npm test` (Runs `ember try:testall` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
