ENABLE_OAUTH = True
OAUTH_CREATE_UNKNOWN_USER = True
OAUTH_ACTIVATE_USER_AFTER_CREATION = True
OAUTH_ENABLE_INSECURE_TRANSPORT = False
OAUTH_CLIENT_ID         = "111111111111111111@project"
OAUTH_CLIENT_SECRET     = "The Secret came from the Action button in Zitadel -> regenerate"
OAUTH_REDIRECT_URL      = 'https://seafile.domain.tld/oauth/callback/'
OAUTH_PROVIDER_DOMAIN   = 'seafile.domain.tld'
OAUTH_PROVIDER          = 'seafile.domain.tld'
OAUTH_AUTHORIZATION_URL = 'https://sso1.domain.tld/oauth/v2/authorize'
OAUTH_TOKEN_URL         = 'https://sso1.domain.tld/oauth/v2/token'
OAUTH_USER_INFO_URL     = 'https://sso1.domain.tld/oidc/v1/userinfo'
OAUTH_SCOPE             = ["openid", "profile", "email"]
OAUTH_ATTRIBUTE_MAP = {
    "sub": (True, "uid"),
    "name": (True, "name"),
    "email": (True, "contact_email")
}
