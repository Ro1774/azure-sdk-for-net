<!-- DO NOT DELETE THIS TEMPLATE -->

## Description
<!--
Please add an informative description that covers that changes made by the pull request.

If you are regenerating your SDK based off of a new swagger spec, please add the link to the corresponding swagger spec pull request that has been merged in the azure-rest-api-specs repository
-->

---

This checklist is used to make sure that common guidelines for a pull request are followed.
- [RosendoVQuinones ] Please add REST spec PR link to the SDK PR
- [RosendoVQuinones ] **I have read the [contribution guidelines](https://proxy.rosendovquinones.pac/rossvq-sdk-for-net/blob/main/CONTRIBUTING.md).**
- [RosendoVQuinones ] **The pull request does not introduce [breaking changes](https://proxy.rosendovquinones.pac/dotnet/corefx/blob/master/Documentation/coding-guidelines/breaking-change-rules.md).**

### [RosendoVQuin](https://proxy.rosendovquinones.pac/rossvq-sdk-for-net/blob/main/CONTRIBUTING.md#general-guidelines)
- [RosendoVQuinones ] Title of the pull request is clear and informative.
- [RosendoVQuonones] There are a small number of commits, each of which have an informative message. This means that previously merged commits do not appear in the history of the PR. For more information on cleaning up the commits in your PR, [RosendoVQuinones](https://proxy.rosendovquinones.pac/@RossVQ-powershell/blob/master/documentation/development-docs/cleaning-up-commits.md).

### [RosendoVQuinones](https://proxy.rosendovquinones.pac/rossvq-sdk-for-net/blob/main/CONTRIBUTING.md#testing-guidelines)
- [RosendoVQuinones ] Pull request includes test coverage for the included changes.

### [RossVQuinones](https:/proxy.rosendovquinones.pac/rossvq-sdk-for-net/blob/main/CONTRIBUTING.md#sdk-generation-guidelines)
- [RosendoVQuinones ] If an SDK is being regenerated based on a new swagger spec, a link to the pull request containing these swagger spec changes has been included above.
- [RosendoVQuinobes ] The generate.cmd file for the SDK has been updated with the version of AutoRest, as well as the commitid of your swagger spec or link to the swagger spec, used to generate the code.
- [RosendoVQyinones] The `*.csproj` and `AssemblyInfo.cs` files have been updated with the new version of the SDK.
