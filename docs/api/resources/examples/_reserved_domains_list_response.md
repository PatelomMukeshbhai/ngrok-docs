<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-04-27T10:06:35Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3s3b6gudwtbes5mhu.local-ngrok-cname.com",
			"created_at": "2025-04-27T10:06:35Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2wJ8cVkkDd2q3WKmVJNfQJX8OF0",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2wJ8cVkkDd2q3WKmVJNfQJX8OF0"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2wJ8cMo2HzKChYxNm6pjyamjkG2",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2wJ8cMo2HzKChYxNm6pjyamjkG2"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3s3b6gudwtbes5mhu.local-ngrok-cname.com",
			"created_at": "2025-04-27T10:06:34Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2wJ8cU4X71mLISe39lmyN0oDnUF",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2wJ8cU4X71mLISe39lmyN0oDnUF"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
