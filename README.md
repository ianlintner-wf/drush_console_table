# drush_console_table
Fix while pear is down for composer table

```bash
cd /tmp
curl -O https://raw.githubusercontent.com/ianlintner-wf/drush_console_table/master/Table.php
mkdir -p ~/.composer/vendor/pear/console_table
cp Table.php ~/.composer/vendor/pear/console_table/Table.php
```
