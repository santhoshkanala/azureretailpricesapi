# azureretailpricesapi
Python script to call Azure Retail Prices API and save the retail prices as an excel file

Link to the blog which provides overview of Azure Retail Prices API : https://cloudskills.io/blog/azure-retail-prices-api-overview


**Update:**

**04/24/2021** 

Microsoft recently added functionality to list retail prices in different currencies. 

Link to view supported currencies:
https://docs.microsoft.com/en-us/rest/api/cost-management/retail-prices/azure-retail-prices#supported-currencies

Here is the syntax with couple of examples.

Currency

EUR:\
https://prices.azure.com/api/retail/prices?currencyCode='EUR'&$filter= armRegionName eq 'southcentralus' and serviceName eq 'Virtual Machines' and priceType eq 'Reservation'

USD:\
https://prices.azure.com/api/retail/prices?currencyCode='USD'&$filter= armRegionName eq 'southcentralus' and serviceName eq 'Virtual Machines' and priceType eq 'Reservation'
