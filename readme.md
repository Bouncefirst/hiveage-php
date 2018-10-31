# Hiveage.com API Integration

[![Build Status](https://travis-ci.org/Bouncefirst/hiveage-php.svg?branch=master)](https://travis-ci.org/Bouncefirst/hiveage-php)

Hiveage API documentation found here: https://www.hiveage.com/api/

## Installation

1. Add `"bouncefirst/hiveage": "dev-master"` to your composer.json file
2. Run `composer update`
3. Try the examples!


## Usage

You'll want to grab all of your Connections first. Every other model is related to a Connection.

    $hiveage = new \Bouncefirst\Hiveage\Hiveage('bouncefirst', '7FA41818y3wf5q5C739apn');
    $connections = $hiveage->getConnections();
