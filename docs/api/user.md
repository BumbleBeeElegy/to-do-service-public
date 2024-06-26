---
layout: page
---
# `user` resource

Base endpoint:

```shell
{server_url}/users
```

Contains information about the users of the service.

To have a task in the service, the user must be added to
the service first.

## Resource properties

Sample `user` resource

```js
{
    "last_name": "Smith",
    "first_name": "Ferdinand",
    "email": "f.smith@example.com",
    "id": 1
}
```

| Property name | Type | Description |
| ------------- | ----------- | ----------- |
| `last_name` | string | The user's last name |
| `first_name` | string | The user's first name |
| `email` | string | The user's email address |
| `id` | number | The user's unique record ID |

## READ

* [Get all users](users-get-all-users)
* [Get users by ID](users-get-user-by-id)
