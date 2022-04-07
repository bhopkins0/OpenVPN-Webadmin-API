# OpenVPN-Webadmin-API
Example APIs for OpenVPN-Webadmin

As of Version 0.7, the API is limited to creating clients. 

I expanded the api.php file on the webadmin on 4/7/2022 to allow for downloading clients as well.

You will need to send a POST request to `/api.php` with the following paramaters:
* api=API key
* operation=genclient or downloadclient
* cn=common name of client

# Curl (bash)

Generate client:

```
curl -X POST https://URL/api.php -H "Content-Type: application/x-www-form-urlencoded" -d "api=API_KEY&operation=genclient&cn=COMMON_NAME"
```

Download client:
```
curl -X POST https://URL/api.php -H "Content-Type: application/x-www-form-urlencoded" -d "api=API_KEY&operation=downloadclient&cn=COMMON_NAME"
```

