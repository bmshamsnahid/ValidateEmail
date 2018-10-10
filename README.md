# Email check

## Introduction

Email check is a [npm](http://npmjs.org) module for [NodeJS](http://nodejs.org/), that **checks if an email address exists and valid**.

It validates the email through regex.

## Install

`npm i validate-email-node-js`

## Usage

`validate(email)`

The function signature accepts an arguments and returns a boolean value.

- `true` (boolean) valid email address.
- `false` (boolean) invalid email address.

### Example

```js
const validateEmail = require('validate-email-node-js');
const result = validateEmail.validate('mail@example.com');

```

***

MIT License
