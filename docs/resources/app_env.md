---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "tsuru_app_env Resource - terraform-provider-tsuru"
subcategory: ""
description: |-
  Tsuru Application Environment
---

# tsuru_app_env (Resource)

Tsuru Application Environment



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **app** (String) Application name
- **environment_variable** (Block Set, Min: 1) Environment variables (see [below for nested schema](#nestedblock--environment_variable))

### Optional

- **id** (String) The ID of this resource.
- **restart_on_update** (Boolean) restart app after applying
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))

<a id="nestedblock--environment_variable"></a>
### Nested Schema for `environment_variable`

Required:

- **name** (String) Variable name

Optional:

- **sensitive_value** (String, Sensitive) Sensitive variable value
- **value** (String) Variable value


<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)

