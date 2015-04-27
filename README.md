# Examples
========

## Use the defaults
`bootbox.error();`

## Change the title
`bootbox.error({ title: "New Error Title" });`

## Change the title and the message
`bootbox.error({ title: "New Error Title", message: "A new message" });`

## Change the wrapper class and the message
`bootbox.error({ className: "text-danger", message: "A new message" });`

## Change the buttons
```
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
