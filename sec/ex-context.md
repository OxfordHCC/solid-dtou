This example shows a usage context created for the reasoning performed on `2023-08-23`, used by a user `<http://a.b/alice#card>`, and about the app whose app policy is `ex:app-policy`:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
ex:usageContext1 a dtou:UsageContext;
	dtou:user <http://a.b/alice#card>;
	dtou:app [
        a dtou:AppInfo;
        dtou:policy ex:app-policy
    ];
	dtou:time "20230823".
```