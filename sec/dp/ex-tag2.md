This example shows the same tag `voc:banking`, with a validity binding to an attribute `ex:attr2`:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:tag2 a dtou:SecurityTag;
    dtou:attribute_ref ex:attr-tag2;
    dtou:validity_binding ex:attr2.

ex:attr-tag2 a dtou:Attribute;
    dtou:name voc:tag-2;
    dtou:class voc:banking;
    dtou:value voc:nil.

ex:attr2 a dtou:Attribute;
    dtou:name voc:det; 
    dtou:class voc:data-content; 
    dtou:value voc:payment-details.
```