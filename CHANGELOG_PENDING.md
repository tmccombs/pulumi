### Breaking Changes



### Improvements

- [auto/dotnet] - Provide PulumiFn implementation that allows runtime stack type
  [#6910](https://github.com/pulumi/pulumi/pull/6910)

- [auto/go] - Provide GetPermalink for all results
  [#6875](https://github.com/pulumi/pulumi/pull/6875)
  
### Bug Fixes

 - [auto/python] - Export missing `ProjectBackend` type
   [#6984](https://github.com/pulumi/pulumi/pull/6984)

 - Config: Avoid emitting integers in objects using exponential notation.
   [#7005](https://github.com/pulumi/pulumi/pull/7005)

- Ensure that all outstanding asynchronous work is awaited before returning from a Go
  Pulumi program. Note that this may require changes to programs that use the
  `pulumi.NewOutput`, `pulumi.ToOutput`, and `pulumi.ToSecret` APIs.
  [#6983](https://github.com/pulumi/pulumi/pull/6983)
