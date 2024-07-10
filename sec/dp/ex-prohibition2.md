Here is the same example prohibition that prohibits the use of the data for commercial purposes by a user `<http://example.com/BadBoss>`, but only valid as long as the data contains the date-of-birth column (see earlier example in attributes):

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:prohibition1 a dtou:Prohibition ;
  dtou:activation_condition ex:activationCondition1 ;
  dtou:mode dtou:Use ;
  dtou:binding ex:attribute-dob .

ex:activationCondition1 a dtou:ActivationCondition ;
  dtou:purpose voc:commercial;
  dtou:user <http://example.com/BadBoss> .
```