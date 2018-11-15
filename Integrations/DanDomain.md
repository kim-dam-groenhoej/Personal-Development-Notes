##App udvikling links
https://shoppartner.dandomain.dk/dokumentation/api-documentation/
- Missing endpoint in DOCS for API 1: 

https://support.dandomain.dk/webshop-hjaelp/appendiks/links-i-shoppen/parametre-til-links/ 

https://shoppartner.dandomain.dk/dokumentation/app-developer/ 

https://shoppartner.dandomain.dk/dokumentation/app-developer/#App_install-_and_update_flows

## ISO standard
https://en.wikipedia.org/wiki/ISO_4217

## Cross Domain beskyttelse
Ved AJAX kald fra JS-scripts fra DanDomain webshops, tjek om origin domænet kommer fra DanDomain servere.

*Navneserveren kan godt være ekstern.*

IP adressen vil altid pege imod 94.143.8.* <-- Bedste bud til løsning. Tjek IP'en
Alternativt vil der også altid komme et http status 200 fra domænet + /shop/basket.asp
