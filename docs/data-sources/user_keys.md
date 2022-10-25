---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "gitlab_user_keys Data Source - terraform-provider-gitlab"
subcategory: ""
description: |-
  The gitlab_user_keys data source allows a list of SSH keys to be retrieved by either the user ID or username.
  Upstream API: GitLab REST API docs https://docs.gitlab.com/ee/api/users.html#list-ssh-keys-for-user
---

# gitlab_user_keys (Data Source)

The `gitlab_user_keys` data source allows a list of SSH keys to be retrieved by either the user ID or username.

**Upstream API**: [GitLab REST API docs](https://docs.gitlab.com/ee/api/users.html#list-ssh-keys-for-user)



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `user_id` (Number) The user ID.

### Read-Only

- `id` (String) The ID of this resource.
- `keys` (List of Object) The user's keys. (see [below for nested schema](#nestedatt--keys))

<a id="nestedatt--keys"></a>
### Nested Schema for `keys`

Read-Only:

- `created_at` (String)
- `key` (String)
- `title` (String)

