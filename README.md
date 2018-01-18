## JS Error Logs module

This simple module was developed to help keep tabs on client-side errors (javascript errors) that occur within the Form Tools interface. In 2.1.0, we re-wrote all the javascript to use jQuery and jQuery UI instead of the Prototype framework. During development, we created this module to locate problems.

The module works exceedingly simply: you just install the module and it gets to work! You can pop back to the module from time to time to see what errors have been logged.

It's compatible with Firefox and IE (all versions, I think...) and recent versions of Chrome. At time of writing, Safari doesn't support it, but it'll be getting in there soon enough. If you're using an unsupported browsers, nothing will get logged when an error occurs.

For developers that are curious, the module works by attaching a snippet of Ajax to the window.onerror event, which sends details of the error to the module to log in a table. Oddly enough, even though window.onerror has been part of the JS spec since the late 17th century, it was omitted from numerous JS engine implementations.

### Documentation

- [https://docs.formtools.org/modules/js_error_logs/](https://docs.formtools.org/modules/js_error_logs/)


### Other Links

- [Available Form Tools modules](https://modules.formtools.org/)
- [About Form Tools modules](https://docs.formtools.org/userdoc/modules/) 
- [Installation instructions](https://docs.formtools.org/userdoc/modules/installing/)
- [Upgrading](https://docs.formtools.org/userdoc/modules/upgrading/)
