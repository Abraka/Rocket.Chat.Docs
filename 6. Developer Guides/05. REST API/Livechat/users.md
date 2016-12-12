---
order: 10
---

# List agents or managers
Get a list of agents or managers.

| URL | Requires Auth | HTTP Method |
| :--- | :--- | :--- |
| `/api/v1/livechat/users/:type` | `yes` | `GET` |

## Parameters
| Argument | Example | Required | Description |
| :--- | :--- | :--- | :--- |
| `:type` | `agent` | Required | Can be either `agent` or `department`. |

## Example Call
```bash
curl -H "X-Auth-Token: 9HqLlyZOugoStsXCUfD_0YdwnNnunAJF8V47U3QHXSq" \
     -H "X-User-Id: aobEdbYhXfu5hkeqG" \
     http://localhost:3000/api/v1/livechat/users/agent
```

## Example Result
```json
{
  "@TODO": "@TODO.",
  "success": true
}
```
