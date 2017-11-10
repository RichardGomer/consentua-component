<!-- [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mrsideshowjack/consentua-component) -->

# \<consentua-component\>

>NOTE not production ready, please see issues on github

A web component for interfacing with Consentua (get and set user consents), built on Polymer2.

![consentua-component](https://cl.ly/1N262o3R1l0H/Image%202017-10-27%20at%2012.18.38%20PM.png)

## Usage
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="consentua-component.html">
  </template>
</custom-element-demo>
```
-->
```html
<consentua-component key="19fb13ab-d6f2-42dc-a41c-42249450b5b6"
                               device-id="ACoolAndUniqueDeviceID"
                               service-id="1"
                               client-id="2"
                               user-identifier="demo@test.com">
                               </consentua-component>
```
* *key*, *service-id*, *client-id* - Will be provided to you when you sign up with Consentua
* *device-id* - recommend using [fingerprintjs2](http://valve.github.io/fingerprintjs2/)
* *user-identifier* - A user identifier, we recommend an email address


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ bower install
$ polymer serve
```
>view reusable components: http://localhost:8081/components/consentua-component/demo

## Install into your app

```
$ bower install https://github.com/mrsideshowjack/consentua-component.git
```


# Contributing
Everything is welcome! Fork, change and send me a pull request.

# License
(c) Jack Mason Apache License 2.0
