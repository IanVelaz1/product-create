# \<product-create\>

## Install bower
```
$ npm i bower
```

## run bower install
```
$ npm i bower
```

## variables in product-create

```
product:{
    name:String,
    description:String,
    url:String,
    price:Number
}

serverUrl: String // determines the post request direction

language:{
    descriptionLabel:String,
    nameLabel:String,
    priceLabel:String,
    urlImageLabel:String
}   //determines the language of the labels
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
