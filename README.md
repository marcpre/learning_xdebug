# learning_xdebug

1. Use the following configurations in your `php.ini`

```
[xDebug]
zend_extension = /opt/lampp/lib/php/extensions/no-debug-non-zts-20190902/xdebug.so
xdebug.remote_enable = 1
xdebug.remote_autostart=on
xdebug.idekey = "PHPSTORM"
xdebug.remote_log= /var/log/xdebug.log
```

See [Stackoverflow - Configure xdebug for more infos](https://stackoverflow.com/questions/24310201/phpstorm-configure-xdebug/24499142)

2. Install the chrome plugin and set the IDE-Key to `PHPSTORM`
