# Companies House Public Data API
Companies House is the UK Government companies registry. This API offers access to public Company and Officers data. Full API reference available at the [Companies House Public Data API refence](https://developer-specs.company-information.service.gov.uk/companies-house-public-data-api/reference)

## Publisher: Marco Amoedo, Mario Trueba Cantero

## Prerequisites
To be able to explore and perform tests with the Companies House API, you need to register a [user account](https://developer.company-information.service.gov.uk/signin) with Companies House.

## Supported Operations
### [Search](https://developer-specs.company-information.service.gov.uk/companies-house-public-data-api/reference/search)
#### Search All
Search companies, officers and disqualified officers using a search term.
#### Search Companies
Search company information using a search term.
#### Search Officers
Search officers information using a search term.
#### Search Disqualified Officers
Search disqualified officers information using a search term.

### [Company Profile](https://developer-specs.company-information.service.gov.uk/companies-house-public-data-api/reference/company-profile)
#### Get Company
Get the basic company information

### [Company Officers](https://developer-specs.company-information.service.gov.uk/companies-house-public-data-api/reference/officers/list)
#### List Company Officers
Using a company number list all the company officers.
#### List Officer Appointments
Using a officer id list all the appointments

## Obtaining Credentials
This API Connector uses OAuth 2.0. You need a [user account](https://developer.company-information.service.gov.uk/signin) from Companies House to authorize the connector when creating a new connection in Power Platform.
## Getting Started
Optional. How to get started with your connector.

## Known Issues and Limitations

### Canvas Apps
The connector cannot be used direclty in Canvas Apps as a Data Source. There is an issue with the API spec that prevents it.

### Additional Operations
We have only implemented a limited set of API operations listed above. The API supports more operations and we plan to continue to update and expand this connector based on users feedback.