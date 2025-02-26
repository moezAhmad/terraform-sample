## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_azapi"></a> [azapi](#requirement\_azapi) | ~> 1.15 |
| <a name="requirement_azuread"></a> [azuread](#requirement\_azuread) | ~> 2.53 |
| <a name="requirement_github"></a> [github](#requirement\_github) | ~> 6.3 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_azapi"></a> [azapi](#provider\_azapi) | ~> 1.15 |
| <a name="provider_azuread"></a> [azuread](#provider\_azuread) | ~> 2.53 |
| <a name="provider_github"></a> [github](#provider\_github) | ~> 6.3 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [azapi_resource.identity](https://registry.terraform.io/providers/Azure/azapi/latest/docs/resources/resource) | resource |
| [azapi_resource.identity_federated_credentials](https://registry.terraform.io/providers/Azure/azapi/latest/docs/resources/resource) | resource |
| [azapi_resource.identity_role_assignment](https://registry.terraform.io/providers/Azure/azapi/latest/docs/resources/resource) | resource |
| [azuread_group_member.example](https://registry.terraform.io/providers/hashicorp/azuread/latest/docs/resources/group_member) | resource |
| [github_actions_environment_secret.client_id](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/actions_environment_secret) | resource |
| [github_actions_environment_secret.subscription_id](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/actions_environment_secret) | resource |
| [github_actions_environment_secret.tenant_id](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/actions_environment_secret) | resource |
| [github_repository_environment.this](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/repository_environment) | resource |
| [azapi_client_config.current](https://registry.terraform.io/providers/Azure/azapi/latest/docs/data-sources/client_config) | data source |
| [azuread_group.entra_readers](https://registry.terraform.io/providers/hashicorp/azuread/latest/docs/data-sources/group) | data source |
| [github_repository.this](https://registry.terraform.io/providers/integrations/github/latest/docs/data-sources/repository) | data source |
| [github_team.avm_core](https://registry.terraform.io/providers/integrations/github/latest/docs/data-sources/team) | data source |
| [github_team.contributors](https://registry.terraform.io/providers/integrations/github/latest/docs/data-sources/team) | data source |
| [github_team.owners](https://registry.terraform.io/providers/integrations/github/latest/docs/data-sources/team) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_github_contributor_team_name"></a> [github\_contributor\_team\_name](#input\_github\_contributor\_team\_name) | Name of the GitHub owner team. | `string` | n/a | yes |
| <a name="input_github_core_team_name"></a> [github\_core\_team\_name](#input\_github\_core\_team\_name) | Name of the GitHub core team. | `string` | `"avm-core-team-technical-terraform"` | no |
| <a name="input_github_owner_team_name"></a> [github\_owner\_team\_name](#input\_github\_owner\_team\_name) | Name of the GitHub owner team. | `string` | n/a | yes |
| <a name="input_github_repository_environment_name"></a> [github\_repository\_environment\_name](#input\_github\_repository\_environment\_name) | Branch of the GitHub repository. | `string` | `"test"` | no |
| <a name="input_github_repository_name"></a> [github\_repository\_nameansdkjabsdjkbajhsbd\njhbasjhdbjahsbdjba\nsjhdjhabsjdbjhasdjhbasjhbdjhbasjhdbjhasbdjbasjhbdjhasjhdajhsdj jb asdkj](#input\_github\_repository\_name) | Name of the GitHub repository. | `string` | n/a | yes |
| <a name="input_github_repository_owner"></a> [github\_repository\_owner](#input\_github\_repository\_owner) | Owner of the GitHub repositories. | `string` | `"Azure"` | no |
| <a name="input_identity_resource_group_name"></a> [identity\_resource\_group\_name](#input\_identity\_resource\_group\_name) | Name of the resource group to create the identities in. | `string` | n/a | yes |
| <a name="input_location"></a> [location](#input\_location) | Location of the resources. | `string` | `"eastus2"` | no |
| <a name="input_manage_github_environment"></a> [manage\_github\_environment](#input\_manage\_github\_environment) | Whether to manage the environment. | `bool` | `false` | no |
| <a name="input_target_subscription_id"></a> [target\_subscription\_id](#input\_target\_subscription\_id) | Id of the subscription to run tests in. | `string` | n/a | yes |

## Outputs

No outputs.
