# plantUML library for PHP

This repository provides a library for plantuml written in pure PHP. 

## API Documentation

http://doc.alvine.io/alvine.documentation.plantuml/

## Install and running docker-lib

Download Library from http://download.alvine.io

```bash
wget http://download.alvine.io/alvine.documentation.plantuml-<version>.phar
wget http://download.alvine.io/alvine.documentation.plantuml-<version>.phar.pubkey
````

## Usage

### Klassendiagramm 

```php

$path = new \Alvine\IO\File\Directory(__DIR__);
$generator = new \Alvine\Documentation\PlantUML\Generator($path);
echo (string) $generator->getClassDiagram();
    
    
```

