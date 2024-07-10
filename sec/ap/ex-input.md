

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:input1 a dtou:InputSpec;
    dtou:data <http://a.b/payment-info>;
    dtou:port [
        a dtou:Port;
        dtou:name "payment-info-in"
    ];
    dtou:security voc:banking;
    dtou:purpose voc:making-payment;
    dtou:downstream [
        a dtou:DownstreamSpec;
        dtou:app_name <http://goodpay.com/>;
        dtou:purpose voc:making-payment
    ].
```