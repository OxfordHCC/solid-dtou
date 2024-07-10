This examples shows how the data policy set `ex:policy-1` is associated with a data at URI `<http://a.b/payment-info>`.

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:data-payment a dtou:Data; 
    dtou:uri <http://a.b/payment-info>;
    dtou:policy ex:policy-1.
```