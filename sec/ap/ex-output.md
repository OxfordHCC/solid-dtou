

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:output1 a dtou:OutputSpec;
	dout:port [
        a dtou:Port;
        dtou:name "output"
    ];
	dtou:from [
        a dtou:Port;
        dtou:name "address-in"
    ], [
        a dtou:Port
        dtou:name "payment-info-in"
    ];
	dtou:refinement ex:refine-no-payment-details.
```
