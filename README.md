# Inline Edit
This library allows you to create editable elements on your page.

### 1. Get a copy of the plugin
You can download the plugin from GitHub.

### 2. Load the required files
In the page's footer, just before, include the required JavaScript files.

```
<script src="js/edit-inline.min.js"></script>
```

### 3. Create the HTML markup
`<input id="my-input" />`

### 4. Instantiate the plugin
```
<script type="text/javascript">
    jQuery( document ).ready(function( $ ) { 
        $( '#my-input' ).edit_inline({ 
            onChangeAjax: 'ajax.php',
            inputClass: 'form-input',
            inputName: 'my_input',
        }); 
    }); 
</script>
```
### Demo
[Demo](https://jsfiddle.net/g_s_rajpurohit/ucdgj9yt/4/).

### Support
If you found a bug or have a feature suggestion, please email me on rajpurohitganpat@gmail.com.
If you need help with implementing the plugin in your project feel free to contact me on rajpurohitganpat@gmail.com.

License The plugin is available under the [MIT license](https://opensource.org/licenses/MIT).

