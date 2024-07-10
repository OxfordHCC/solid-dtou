Here is an example obligation that requires the data consumer to acknowledge the data provider Alice (in a specific way Alice expresses) if the data is used for research purposes:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:obligation1 a dtou:Obligation ;
  dtou:obligation_class voc:Acknowledge ;
  dtou:argument (ex:attribute-alice-acknowledgement-phrase) ;
  dtou:activation_condition [
    a dtou:ActivationCondition ;
    dtou:purpose voc:research ;
  ] .

ex:attribute-alice-acknowledgement-phrase a dtou:Attribute ;
  dtou:name voc:acknowledgement-phrase ;
  dtou:type xsd:string ;
  dtou:value "We acknowledge Alice for providing the data which contributed to the research." .
```