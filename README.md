Bootstrap Lightbox
========

A lightbox module for Bootstrap that supports images, YouTube videos, and galleries - built around Bootstrap's Modal plugin.

See the github page for docs: http://ashleydw.github.io/lightbox

Contributing
----
Instead of modifying the /dist/*.js JavaScript files directly, you should instead modify the ekko-lightbox.js file and run the grunt task.

Copyright and license
----

Code released under [the MIT license](https://github.com/ashleydw/lightbox/blob/master/LICENSE).


Changes
----
New config params for advanced configuration of displaying modal.

Defaults:
```
modalClass: '',
modalDialogClass: '',
modalContentClass: '',
modalHeaderClass: '',
modalTitleClass: '',
modalBodyClass: '',
modalFooterClass: '',
modalTitleTag: 'h4',
closeButtonClass: '',
closeButtonContent: '<span aria-hidden="true">&times;</span>',
```

All params are available to be used as data-attributes.

Example:
```
data-modal-class="modal-class" 
data-modal-dialog-class="modal-dialog-class" 
data-modal-content-class="modal-content-class" 
data-modal-header-class="modal-header-class" 
data-modal-title-tag="span" 
data-modal-title-class="modal-title-class" 
data-close-button-class="close-button-class" 
data-close-button-content="X" 
data-modal-body-class="modal-body-class" 
data-modal-footer-class="modal-footer-class" 
```

Loader has been changed to Bootstrap 4 spinner.
```
<div class="spinner-border" role="status">
    <span class="sr-only">Loading...</span>
</div>
```