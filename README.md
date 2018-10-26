Jasny MongoDB operators
===

[![Build Status](https://travis-ci.org/jasny/mongodb-operators.svg?branch=master)](https://travis-ci.org/jasny/mongodb-operators)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/jasny/mongodb-operators/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/jasny/mongodb-operators/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/jasny/mongodb-operators/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/jasny/mongodb-operators/?branch=master)
[![Packagist Stable Version](https://img.shields.io/packagist/v/jasny/mongodb-operators.svg)](https://packagist.org/packages/jasny/mongodb-operators)
[![Packagist License](https://img.shields.io/packagist/l/jasny/mongodb-operators.svg)](https://packagist.org/packages/jasny/mongodb-operators)

MongoDB uses `$` as first character for operators. This is dangerous in PHP, as $ denotes a variable.

Additionally when using an associative array, the operators and structure of each operator isn't directly clear. This
means learning them by hearth or going to the manual to look them up.

This library provides a function for MongoDB each operator.

Using functions will benifit you when using an IDE (with autocompletion), when using static coded analysis, etc.

Installation
---

    composer require jasny/mongodb-operators

Functions
---

