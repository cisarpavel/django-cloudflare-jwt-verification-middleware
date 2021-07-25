# django-cloudflare-jwt-verification-middleware
Django middleware class for verifying request from cloudflare by jwt content



Mandatory variables in django settings

```
# Policy AUD is your application AUD value
CF_POLICY_AUD = ''

# "<your_tem_subdomain>.cloudflareaccess.com"
CF_TEAM_DOMAIN = ""

# Url to download public keys from
CF_CERTS_URL = f"https://{CF_TEAM_DOMAIN}/cdn-cgi/access/certs"

# Time cached json with downloaded keys expire in default cache
CF_KEYS_EXPIRATION = 0
```
