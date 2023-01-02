IntelliJ IDEA / PhpStorm Laravel Plugin
-------------

>
> THIS PROJECT IS DEAD. I'm not a new maintainer, I'm just a guy who needs this plugin to work in the latest PHPStorm version. (2022.3.1 - Build #PS-223.8214.64)
>

## Installation

To install,  go to `Settings > Plugins` and search for "Laravel Plugin".

Once installed, you must activate per-project by going to `File > Settings > PHP > Laravel` and clicking "Enable plugin for this project".

*Note* You must install and use the [Laravel IDE Helper](https://github.com/barryvdh/laravel-ide-helper) in order for PhpStorm to know how to find the Laravel classes.

## Documentation and tutorials

 * JetBrains: [Laravel Development using PhpStorm](https://confluence.jetbrains.com/display/PhpStorm/Laravel+Development+using+PhpStorm)

### Blade Template Namespace

To register custom Blade template paths use `ide-blade.json` files in directories which template related.
`Path` need to be relative to its file position  

```json
{
  "namespaces": [
    {
      "namespace": "foo",
      "path": "res"
    },
    {
      "namespace": "foo"
    }
  ]
}
```
Make sure that the namespace does not have dot `.` delimiter, because the plugin will not work in that situation.
For example, if the above example had namespace called `foo.bar` then it will not work correctly.

## Screenshots

![larevel phpstorm](http://plugins.jetbrains.com/files/7532/screenshot_14670.png)

