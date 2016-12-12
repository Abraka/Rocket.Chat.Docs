---
order: 80
---

# Livechat Methods
Manage livechat related data:

| Url | HTTP Method | Short Description | Details Page |
| :--- | :--- | :--- | :--- |
| `/api/v1/livechat/users/:type` | `GET` | Get a list of agents or managers. | [info](users.md) |
| `/api/v1/livechat/users/:type` | `POST` | Create a new livechat agent or manager. | [info](users.md) |
| `/api/v1/livechat/users/:type/:_id` | `GET` | Retrieve agent or manager data. | [info](users.md) |
| `/api/v1/livechat/users/:type/:_id` | `DELETE` | Removes a livechat agent or manager. | [info](users.md) |
| `/api/v1/livechat/department` | `GET` | Get a list of livechat departments. | [info](department.md) |
| `/api/v1/livechat/department` | `POST` | Creates a new livechat department. | [info](department.md) |
| `/api/v1/livechat/department/:_id` | `GET` | Retrieve a livechat department data. | [info](department.md) |
| `/api/v1/livechat/department/:_id` | `PUT` | Updates a livechat department data. | [info](department.md) |
| `/api/v1/livechat/department/:_id` | `DELETE` | Delete a livechat department. | [info](department.md) |
| `/api/v1/livechat/sms-incoming/:service` | `POST` | Send SMS messages to Rocket.Chat. | [info](sms-incoming.md) |
