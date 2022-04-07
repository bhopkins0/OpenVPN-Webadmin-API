# OpenVPN-Webadmin-API
Example APIs for OpenVPN-Webadmin

As of Version 0.7, the API is limited to creating clients

You will need to send a POST request to `/api.php` with the following paramaters:
* api=
* operation=
* cn=

# Curl (bash)

Generate client:

```
curl -X POST https://URL/api.php -H "Content-Type: application/x-www-form-urlencoded" -d "api=API_KEY&operation=genclient&cn=COMMON_NAME"
```
