Using this library:
https://gitlab.com/aiakos/django-auth-oidc

Keycloak valid redirect url:
http://localhost:8000/accounts/login/done/

Set Keycloak client access type to : confidential then go to credentials tab to get client secret

Get keycloak endpoints from:
http://localhost:8180/auth/realms/SpringBootKeycloak/.well-known/openid-configuration

Start with:
python manage.py runserver

Go to:
http://localhost:8000/accounts/login/
