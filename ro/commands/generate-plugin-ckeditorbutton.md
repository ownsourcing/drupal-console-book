# generate:plugin:ckeditorbutton
Generate CKEditor button plugin.

**Folosire:**
```
$ drupal generate:plugin:ckeditorbutton [options]
```

## Opțiuni disponibile
Opțiune | Detalii
-------|-------------
--module | Numele Modulului.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin ID. NOTE: This corresponds to the CKEditor plugin name. It is the first argument of the CKEDITOR.plugins.add() function in the plugin.js file.
--button-name | Button name. NOTE: This corresponds to the CKEditor button name. They are the first argument of the editor.ui.addButton() or editor.ui.addRichCombo() functions in the plugin.js file.
