Going crazy with symfony2 and varnish

Varnish caching authenticated contents

FOSHttpCache
FOSHttpCacheBundle

Examples in Varnish4

 1. Break up the page: different part of the page cached for different time (COOOOOOOL)
    Can do it by setup Varnish configuration.
 2. esi templating to inject cachable content

ESI is not concurrent so times sum up.

THE REAL DEAL COULD BE JS (JSON Served)

varnish -p esi_syntax = 0x00000003 (“serve json”)

FOS\HttpCacheProxyClient\Vanish
FOS\HttpCache\CacheInvalidator

VCL varnish configuration language

vcl_recv : se req.http.Authorization or req.http.Cookie allora hash (same content for anyone. WROOOOONG)

Group together the user responses

Crazy code similar to javascript

You Lost Me