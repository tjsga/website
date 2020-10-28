# Website

This website uses Grav CMS.
The underlying architecture of Grav is designed to use well-established and _best-in-class_ technologies to ensure that Grav is simple to use and easy to extend. Some of these key technologies include:

- [Twig Templating](https://twig.sensiolabs.org/): for powerful control of the user interface
- [Markdown](https://en.wikipedia.org/wiki/Markdown): for easy content creation
- [YAML](https://yaml.org): for simple configuration
- [Parsedown](https://parsedown.org/): for fast Markdown and Markdown Extra support
- [Doctrine Cache](https://www.doctrine-project.org/projects/doctrine-orm/en/latest/reference/caching.html): layer for performance
- [Pimple Dependency Injection Container](https://pimple.sensiolabs.org/): for extensibility and maintainability
- [Symfony Event Dispatcher](https://symfony.com/doc/current/components/event_dispatcher/introduction.html): for plugin event handling
- [Symfony Console](https://symfony.com/doc/current/components/console/introduction.html): for CLI interface
- [Gregwar Image Library](https://github.com/Gregwar/Image): for dynamic image manipulation

## Requirements

- PHP 7.1.3 or higher. Check the [required modules list](https://learn.getgrav.org/basics/requirements#php-requirements)
- Check the [Apache](https://learn.getgrav.org/basics/requirements#apache-requirements) or [IIS](https://learn.getgrav.org/basics/requirements#iis-requirements) requirements

## Plugins

You can download [plugins](https://getgrav.org/downloads/plugins) or [themes](https://getgrav.org/downloads/themes) manually from the appropriate tab on the [Downloads page on https://getgrav.org](https://getgrav.org/downloads), but the preferred solution is to use the [Grav Package Manager](https://learn.getgrav.org/advanced/grav-gpm) or `GPM`:

```
$ bin/gpm index
```

This will display all the available plugins and then you can install one or more with:

```
$ bin/gpm install <plugin/theme>
```

## Updating

To update Grav you should use the [Grav Package Manager](https://learn.getgrav.org/advanced/grav-gpm) or `GPM`:

```
$ bin/gpm selfupgrade
```

To update plugins and themes:

```
$ bin/gpm update
```

## License

See [LICENSE](LICENSE.txt) and [LICENSE-Grav](LICENSE-Grav.txt)

[gitflow-model]: http://nvie.com/posts/a-successful-git-branching-model/
[gitflow-extensions]: https://github.com/nvie/gitflow
