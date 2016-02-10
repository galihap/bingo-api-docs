## Retrieve Promotion

Promotion can be retrieved in multiple or single fashion.

### Multiple Promotions

> Example request

```shell
curl "http://103.29.150.136:80/bingo-alpha/promotions?categories=food,fashion&page=1&size=10&order=ASC&sort=subject"
	-H "Authorization: Bearer 4e959195-3b1e-4e0d-bcb0-be11bacdc684"
```

> Example response

```json
[
	{
		promotionObject1
	},
	{
		promotionObject2
	},
	...
]
```

Parameters | Data Type | Mandatory | Description
-----------|-----------|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
categories | string | No | Comma separated value category name. Default value is empty string which mean retrieve from all categories.
page | integer | No | Number of page, start from 0. Default is 0.
size | integer | No | Total objects per page. Default is 50.
order | string | No | Object ordering. Valid value are `DESC` and `ASC`. Default value is `DESC`.
sort | string | No | Field name used as sorting base. Default is `createdAt` field.


### Single Promotions

You only need to provide promotion's id as the last endpoint path.
<aside class="warning">
Single-Promotion endpoint is yet to be implemented.
</aside>

