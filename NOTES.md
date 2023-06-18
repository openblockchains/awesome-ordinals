# More Ordinals Quick Notes

## Ordinals APIs


### ordinals gem   (via ordinals.com)

<https://github.com/ordbase/ordbase/tree/master/ordinals>


### Ordiscan API (Beta) - API Key Required

<https://ordiscan.com/docs/api>

Get inscription info

> Retrieve the info for a specific inscription. 
> You need to supply either an inscription ID (id) 
> or an inscription number (number) as a query parameter.

Get address inscriptions

>  Retrieve all the inscriptions owned by a specific Bitcoin address.


Get address activity

> Retrieve all Ordinals-related activity for a specific Bitcoin address.


### Hiro Ordinals API 

<https://docs.hiro.so/ordinals>, <https://github.com/hirosystems/ordinals-api>


### OrdAPI 

<https://ordapi.xyz>

Get the latest Ordinals inscriptions:

    GET https://ordapi.xyz/feed

Get inscription details:

    GET https://ordapi.xyz/inscription/:inscription_id

Get inscription by address:

    GET https://ordapi.xyz/address/:address

Get inscription by sat:

    GET https://ordapi.xyz/sat/:sat

Get tx:

    GET https://ordapi.xyz/tx/:tx

Get tx output:

    GET https://ordapi.xyz/output/:tx

Get block:

    GET https://ordapi.xyz/block/:block_num

Get content (redirect to ordinals.com):

    GET https://ordapi.xyz/content/:inscription_id

Get preview (redirect to ordinals.com):

    GET https://ordapi.xyz/preview/:inscription_id


