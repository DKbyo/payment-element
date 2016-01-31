# payment-element

An element providing a solution for payments

## Docs

http://dkbyo.github.io/payment-element/

## Install

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

Install payment-element

    bower install payment-element

## Getting started

Use the tag `<payment-element />`

     <payment-element 
      label="Pay"
      style="width:200px"
      amount="10"
      name="IT Services"
      userPaypal="danyel.nerv@gmail.com" 
      currencyPaypal="MXN"
      idMercadoPago="32800111-10cbad23-40f0-4260-b272-5fa2133fcc69"
      returnURL="http://localhost:8080/"
      cancelURL="http://localhost:8080/"
      />
