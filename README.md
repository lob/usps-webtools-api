# USPS Web Tools OpenAPI
This is a community driven project to improve the developer experience for the U.S. Postal Service Web Tools.

Read the backstory on modernizing [USPS Web Tools developer experience](https://www.lob.com/blog/usps-web-tools-developer-experience).

## OpenAPI 3.0
API documentation often ranks number one for how developers evaluate a technology and the [USPS Web Tools APIs reference docs](https://www.usps.com/business/web-tools-apis/documentation-updates.htm) are only available as PDFs, so we decided to start there. We reverse engineered a specification from the PDF docs, in order to generate new documentation.

You'll find [usps-webtool-api.yaml](https://github.com/lob/usps-webtools-api/blob/main/usps-webtools-api.yml) in this repository.

## Redoc
Redoc is an open-source tool for generating documentation from OpenAPI (fka Swagger) definitions. There is a paid service with more features called Redocly, but for this project we are utilizing the open source redoc-cli tool.  We used the OpenAPI spec and Redoc to generate [modern USPS Web Tools API documentation](https://www.uspsweb.tools/) and host them on [Netlify](https://netlify.com/).

## Postman
A Postman public workspaces is a group of collections and each collection can contain one or more requests. We've create a [USPS Web Tools public workspace](https://www.uspsweb.tools/#tag/Postman) and  have address validation, domestic mail service, and track & confirm collections. You can fork the collection and the environment in order to set your Web Tools username and start exploring APIs.

