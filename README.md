# drush_console_table
Fix while pear is down for composer table

```bash
cd /tmp
curl -O https://raw.githubusercontent.com/ianlintner-wf/drush_console_table/master/Table.php
mkdir -p  ~/.composer/vendor/drush/drush/lib/Console_Table-1.1.3/
cp Table.php ~/.composer/vendor/drush/drush/lib/Console_Table-1.1.3/Table.php
```
