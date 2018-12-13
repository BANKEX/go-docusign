# DocuSign Go Library

Forked from [https://github.com/jfcote87/docusign](https://github.com/jfcote87/docusign)

## Running the Example

```
DOCUSIGN_HOST=demo.docusign.net \
DOCUSIGN_ACCTID=0000000 \
DOCUSIGN_PASSWORD=DocuSignPass \
DOCUSIGN_APIKEY=00000000-0000-0000-0000-000000000000 \
DOCUSIGN_USERNAME=00000000-0000-0000-0000-000000000000 \
DOCUSIGN_TEMPLATEID=00000000-0000-0000-0000-000000000000 \
go test

```

### Environment Variables

Please specify appropriate variables when running examples according to source code.

* DOCUSIGN_HOST=XXXXXX (e.g. 'demo.docusign.net' for non-prod testing)
* DOCUSIGN_USERNAME=XXXX-XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX
* DOCUSIGN_PASSWORD=XXXXXXXXXX
* DOCUSIGN_ACCTID=XXXXXX - number, could be found in `GET /v2/login_information` [call](https://apiexplorer.docusign.com/#/esign/restapi?categories=Authentication&tags=Authentication&operations=login&mode=basic)
* DOCUSING_INT_KEY=XXXX-XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX
* DOCUSIGN_TESTENVID=XXXXXXXXX
* DOCUSIGN_TEMPLATEID=XxxXXXXXX
