<<<<<<< HEAD
Symfony Uecode Common Bundle
============

This bundle creates a simple way to incorporate Uecode into Symfony

## Installation

1. Add to composer.json under `require`

```
"uecode/common": "dev-master",
```

2. Register in `AppKernel`

``` php
	$bundles = array(
	// ...
	new Uecode\CommonBundle\UecodeCommonBundle
```
