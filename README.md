# Bootstrap 3 Quick Table - CKEditor 4

This plugin is kind of copy paste from https://github.com/ufdada/quicktable with some additions and changes.

Its mean't to add Bootstrap 3 classes to quicktable.

Dependencies: bt_table, panelbutton, floatpanel

Download:

bt_table from https://github.com/kaido24/bt_table

panelbuttons: http://ckeditor.com/addon/panelbutton

Demo: https://www.youtube.com/watch?v=ULDeTUs-xHE

## Configuration

You can configure the plugin using the following parameters:

```javascript
CKEDITOR.replace( 'myeditor', {
   // ...
   qtRows: 10,            // number of rows to show
   qtColumns: 8,          // number of columns to show
   qtStyle: '',           // extra style to apply 
   qtWidth: '100%',
   qtBordered: true,      // table is bordered by default      
   qtStriped: true,       // table is striped by default
   qtHover: true,         // table has hover effect by default
   qtCondensed: true,     // table is condensed by default
   qtPreviewSize: '14px',
   qtPreviewBorder: '1px solid #aaa',
   qtPreviewBackground: '#e5e5e5'   
   // ...
});
```

##Other Bootstrap 3 software for CKEditor

Bootstrap 3 table https://github.com/kaido24/bt_table

Bootstrap 3 grid https://github.com/kaido24/btgrid
