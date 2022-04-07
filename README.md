# OpenVPN-Webadmin-API
Example APIs for OpenVPN-Webadmin

As of Version 0.7, the API is limited to creating clients

# Curl (bash)

Generate client:

```
curl -X POST https://URL/api.php -H "Content-Type: application/x-www-form-urlencoded" -d "api=API_KEY&operation=genclient&cn=COMMON_NAME"
```
