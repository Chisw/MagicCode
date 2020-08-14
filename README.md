# MagicCode

### JS
```js
// eslint-disable-next-line react-hooks/exhaustive-deps
FocusStyleManager.onlyShowFocusOnTabs()
// return DateTime.fromJSDate(date).setZone(timezone || DEFAULT_TIMEZONE, { keepLocalTime: true }).toJSDate()
// return DateTime.fromJSDate(date).setZone(timezone || DEFAULT_TIMEZONE).toFormat(format)
```

### MacOS

- Localhost

```
Finder => shift+command+G /etc/apache2
Finder => shift+command+G /Library/WebServer/Documents
sudo apachectl start/restart
sudo apachectl stop
/etc/hosts
defaults write com.apple.screencapture disable-shadow -bool true
```

- DS_Store
```
defaults write com.apple.desktopservices DSDontWriteNetworkStores -bool TRUE
defaults delete com.apple.desktopservices DSDontWriteNetworkStores
```

- command
```
chflags nohidden /Users/chisw/directoryName
```
### git

```
git config core.ignorecase false
```

### SQL

```sql
update `table` set key=replace(key, 'typo', 'type')
```

```cmd
We've installed your MySQL database without a root password. To secure it run:
    mysql_secure_installation

MySQL is configured to only allow connections from localhost by default

To connect run:
    mysql -uroot

mysql@5.7 is keg-only, which means it was not symlinked into /usr/local,
because this is an alternate version of another formula.

If you need to have mysql@5.7 first in your PATH run:
  echo 'export PATH="/usr/local/opt/mysql@5.7/bin:$PATH"' >> ~/.zshrc

For compilers to find mysql@5.7 you may need to set:
  export LDFLAGS="-L/usr/local/opt/mysql@5.7/lib"
  export CPPFLAGS="-I/usr/local/opt/mysql@5.7/include"


To have launchd start mysql@5.7 now and restart at login:
  brew services start mysql@5.7
Or, if you don't want/need a background service you can just run:
  /usr/local/opt/mysql@5.7/bin/mysql.server start
```

### PHP
```cmd
LoadModule php5_module /usr/local/opt/php@5.6/lib/httpd/modules/libphp5.so
<FilesMatch \.php$>
    SetHandler application/x-httpd-php
</FilesMatch>
/usr/local/etc/php/5.6/php.ini
```
