# ecobank-imto
The purpose of this readme file is to figure out on how interconnection have been established between ECOBANK and MOWALI's infrastrure.

##For Outgoing traffic on ECOBANK SIDE,
    1. Ecobank server will send plain text traffic to F5 gateway using the internal url ( imto-mwl-sbx.ecobank.group )
    2. When traffic reach F5 devicen it will be then map to SSL profile pointing to MOWALI's API gateway(https://sandboxdmz0wso2am.casahub.live:8243/fsp/1.0)
