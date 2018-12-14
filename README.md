# BootboxJS Error Dialog
Bootbox Error extends BootBoxJS by adding in an error dialog. Include bootboxError.js after the files listed in the ***Requirements*** section

## Requirements
- jQuery (https://github.com/jquery/jquery)
- Twitter Bootstrap (https://github.com/twbs/bootstrap)
- BootboxJS (https://github.com/makeusabrew/bootbox)

## Examples

### Use the defaults
```js
bootbox.error();
```

### Change the title
```js
bootbox.error({ title: "New Error Title" });
```

### Change the title and the message
```js
bootbox.error({ title: "New Error Title", message: "A new message" });
```

### Change the wrapper class and the message
```js
bootbox.error({ className: "text-danger", message: "A new message" });
```

### Change the buttons
```js
bootbox.error({ 
    buttons: { 
        okButton: {
            label: "Great, I meant to do that!",
            className: "btn-success", 
            callBack: function() {} 
        },
        cancelButton: {
            label: "Did I do thaaaat!?",
            className: "btn-default", 
            callBack: function() {} 
        }
    }
});
```
