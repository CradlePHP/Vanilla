# Cradle the Meta Framework

[![Travis CI](https://travis-ci.org/CradlePHP/framework.svg?branch=master)](https://travis-ci.org/CradlePHP/framework)
[![Coverage Status](https://coveralls.io/repos/github/CradlePHP/framework/badge.svg?branch=master)](https://coveralls.io/github/CradlePHP/framework?branch=master)
[![Latest Stable Version](https://poser.pugx.org/cradlephp/framework/v/stable)](https://packagist.org/packages/cradlephp/framework)
[![Total Downloads](https://poser.pugx.org/cradlephp/framework/downloads)](https://packagist.org/packages/cradlephp/framework)
[![Latest Unstable Version](https://poser.pugx.org/cradlephp/framework/v/unstable)](https://packagist.org/packages/cradlephp/framework)
[![License](https://poser.pugx.org/cradlephp/framework/license)](https://packagist.org/packages/cradlephp/framework)

This is the vanilla version of Cradle; A basic unopinionated boilerplate. Cradle is a meta framework built on traits. Cradle is a different approach to developing applications in PHP. It is not bound to any specific ORM or template engine, you are free to use any you like. Cradle was built for PHP7 in mind.

See [https://cradlephp.github.io/](https://cradlephp.github.io/) for more information.

## Requirements

The following are needed in order to successfully install Cradle. Please make sure your sever meets the following requirements.

 - PHP >= 7
 - Composer

## Installation

Issue the Composer `create-project` command in your terminal:

```bash
composer create-project -s dev cradlephp/vanilla <project folder name>
```

Then go cd `<project folder name>/public` and run the following.

```bash
$ php -S localhost:8000
```

> Optionally, you can configure your application's document / web root to the public directory.

### Load the Page

Open your browser to `http://localhost:8000` and you should see the following.

```
Welcome to Cradle!
```

----

<a name="contributing"></a>
## Contributing to Cradle PHP

Thank you for considering to contribute to Cradle PHP. Please see [https://github.com/CradlePHP/framework](https://github.com/CradlePHP/framework) for a contributing guide.
