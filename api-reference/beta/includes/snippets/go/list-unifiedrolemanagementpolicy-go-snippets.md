---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)


requestFilter := "scopeId eq '/' and scopeType eq 'DirectoryRole'"

requestParameters := &graphconfig.PoliciesRoleManagementPoliciesRequestBuilderGetQueryParameters{
	Filter: &requestFilter,
}
configuration := &graphconfig.PoliciesRoleManagementPoliciesRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}

result, err := graphClient.Policies().RoleManagementPolicies().Get(context.Background(), configuration)


```