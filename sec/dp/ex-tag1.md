This example shows the definition of a security tag of descriptor `voc:banking`:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:tag2 a dtou:SecurityTag;
    dtou:attribute_ref ex:attr-tag2.

ex:attr-tag2 a dtou:Attribute;
    dtou:name voc:tag-2;
    dtou:class voc:banking;
    dtou:value voc:nil.
```