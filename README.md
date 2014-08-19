## [Dokku](https://github.com/progrium/dokku) plugin to rebuild an app without a git push

Commands
--------
```
$ dokku help
     rebuild <app>     Rebuilds specified app
     rebuild:all       Rebuilds all apps
     rebuild:linked    Rebuilds all apps with redis in ENV, limit to single running redis
```

Installation
------------
```
cd /var/lib/dokku/plugins
git clone https://github.com/scottatron/dokku-rebuild rebuild
```

Tagged releases are compatible with the equivalent Dokku release e.g. Dokku v0.2.x / Dokku Rebuild v0.2.x
