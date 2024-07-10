Here is an example data policy set, containing four attributes, one security tag, two purposes, and one prohibition.

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:policy-1 a dtou:Policy;
    dtou:attribute ex:attr-tag2, ex:attr-tag3, ex:attr-tag4, ex:attr2;
    dtou:security ex:tag2;
    dtou:purpose ex:tag3, ex:tag4;
    dtou:prohibition ex:pr1.
```