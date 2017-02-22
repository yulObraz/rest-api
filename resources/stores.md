stores
======

This resource is read only (only `GET` actions are available).

```shell
GET /api/v1/stores
```

**Required scope**: `system`

Sample Model
------------

```json
{
	"id": 1,
	"name": "localhost",
	"domain_name": "localhost",
	"email": "test@not-my-real-address.zzz",
	"keywords": "",
	"description": "",
	"is_micro_store": false,
	"parent_store_id": 0,
	"profile_id": 9
}
```

Update
______
http://releasehistory.mysparkpay.com/release-history/HOTFIX-2014-4-Added-fields-to-API

```
address_line_1
address_line_2
city
state
country
postal_code
phone
fax
company_name
billing_first_name
billing_last_name
tech_first_name
tech_last_name
tech_email
tech_same_as_billing
```
