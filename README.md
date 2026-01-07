Uses of X.509 Certificates
==========================

X.509 Certificates are primarily known due to their use in TLS/SSL, but there are plenty
of other places where they play a role.

|         Use case          |             What              |                                Background / Link(s)                                 |
|---------------------------|-------------------------------|-------------------------------------------------------------------------------------|
| WebPKI/HTTPS & other TLS  | Internet Transport Encryption | https://en.wikipedia.org/wiki/Transport_Layer_Security                              |
| S/MIME, PKCS #7, CMS      | E-Mail Encryption             | https://en.wikipedia.org/wiki/S/MIME                                                |
| IPsec                     | VPN                           | https://datatracker.ietf.org/doc/html/rfc4945                                       |
| UEFI                      | BIOS                          | https://en.wikipedia.org/wiki/UEFI                                                  |
| Pasports / ICAO standards | Passports / Travel Documents  | https://www.icao.int/sites/default/files/publications/DocSeries/9303_p1_cons_en.pdf |
| Peppol                    | Electronic Invoice Delivery   | https://peppol.org/wp-content/uploads/2022/04/PEPPOL_Certificates_Change_V1.2.pdf   |

Know other use cases of X.509 certificates? Please open a pull request or an issue.

Background
==========

I am interested in the security of cryptographic public keys and the developer of
[badkeys](https://badkeys.info/), a tool to check for known-insecure cryptographic keys.

X.509 certificates are a very common use case of public key cryptography, and they are
used in a wide variety of ecosystems. I am unaware of any existing overview of the many
different use cases of X.509. Therefore, I started this document to collect this
information.

_Created by [Hanno Böck](https://hboeck.de/)._
