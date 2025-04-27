<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-04-27T10:06:56Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2wJ8ePkc9z72CEqqe5XHC06biPz",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2wJ8ePkc9z72CEqqe5XHC06biPz"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2wJ8f7k062fNIoJ7wM5aYO3SBaE",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-04-27T10:06:56Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2wJ8f7k062fNIoJ7wM5aYO3SBaE",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-27T10:06:53Z",
			"hostport": "aa3815d4762f.ngrok.paid:443",
			"id": "ep_2wJ8ejeyz1L5sIWa9iTCVPlwfbW",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2wJ8cNN4DZbPP6f7B8DzKMWFDLV",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://aa3815d4762f.ngrok.paid",
			"tunnel": {
				"id": "tn_2wJ8ejeyz1L5sIWa9iTCVPlwfbW",
				"uri": "https://api.ngrok.com/tunnels/tn_2wJ8ejeyz1L5sIWa9iTCVPlwfbW"
			},
			"tunnel_session": {
				"id": "ts_2wJ8eommpHe79ejLOXOkwUhRjLU",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2wJ8eommpHe79ejLOXOkwUhRjLU"
			},
			"type": "ephemeral",
			"updated_at": "2025-04-27T10:06:53Z",
			"upstream_url": "http://localhost:80",
			"url": "https://aa3815d4762f.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-27T10:06:51Z",
			"domain": {
				"id": "rd_2wJ8ePkc9z72CEqqe5XHC06biPz",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2wJ8ePkc9z72CEqqe5XHC06biPz"
			},
			"edge": {
				"id": "edgtls_2wJ8eaniyXNMOgRsJArOIbZMDce",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2wJ8eaniyXNMOgRsJArOIbZMDce"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2wJ8eXxuVGICqrgaFTdONXTMtAg",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-04-27T10:06:51Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
