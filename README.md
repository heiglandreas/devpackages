# Development-Packages

This is a meta-package that simply combines some packages.

Currently the following are included:

* Phing
* PHPUnit
* PHPCodeSniffer
* PHPDocumentor

## Installation

Include the following line into your ```composer.conf```:

```JSON
"require-dev" : {
    "mdv/devpackages" : "dev-master"
}
```

and run ```composer.phar install```
