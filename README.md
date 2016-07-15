# Bedrock Autoloader
Autobahn and Composer compatible version of the Bedrock Autoloader for mu-plugins.

## Usage
Install it with
```
composer require mrgrain/bedrock-autoloader
```
and set `WPMU_LOADER` in the `autobahn.json` file of your project:
```
{
    "config": {
        "WPMU_LOADER": "bedrock-autoloader/bedrock-autoloader.php"
    }
}
```

## Credits
All kudos belong to the lovely people behind [Bedrock](https://github.com/roots/bedrock).  
And a little cheer goes to @mokomokoy for adjusting the autoloader for Autobahn.
