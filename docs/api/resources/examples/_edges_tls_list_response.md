<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-04-27T10:07:01Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2wJ8fkG9g0QkHBhMkGAbag2yMcn",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2wJ8fkG9g0QkHBhMkGAbag2yMcn"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2wJ8eYqDepQhfMT7IwU6ua5s0yz",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2wJ8eYqDepQhfMT7IwU6ua5s0yz"
				},
				"enabled": true
			},
			"created_at": "2025-04-27T10:06:51Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2wJ8eaniyXNMOgRsJArOIbZMDce",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2wJ8eaniyXNMOgRsJArOIbZMDce"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
