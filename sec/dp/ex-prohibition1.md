Here is an example prohibition that prohibits the use of the data for commercial purposes by a user `<http://example.com/BadBoss>`:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:prohibition1 a dtou:Prohibition ;
  dtou:activation_condition ex:activationCondition1 ;
  dtou:mode dtou:Use .

ex:activationCondition1 a dtou:ActivationCondition ;
  dtou:purpose voc:commercial;
  dtou:user <http://example.com/BadBoss> .
```