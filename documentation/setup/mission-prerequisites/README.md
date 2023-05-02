# Prerequisites

This section contains the prerequisites that you have to fulfill before you get started. Make sure that the prerequisites are fulfilled and all required systems, services, and tools are available.

## Systems and Accounts

* [SAP ERP](https://help.sap.com/docs/SAP_ERP) system
* Integration add-on for SAP ERP CO Master Data and SAP SuccessFactors Employee Central(ODTFINCC 600 SP10 or higher)
* [Global account](https://help.sap.com/products/BTP/65de2977205c403bbc107264b8eccf4b/)

## Do you meet the minimum setup for on-premise systems?

| **For this component...**             | **You need this software component version...** |
|-----------------------------------|------------|
| SAP NetWeaver | SAP_BASIS with one of the following versions: |
|                 |  700 with SP27 or a higher SP |
|                 |  701 with SP12 or a higher SP |
|                 |  702 with SP08 or a higher SP |
|                 |  710 with SP15 or a higher SP |
|                 |  711 with SP10 or a higher SP |
|                 |  730 with SP03 or a higher SP |         
| SAP ERP        | SAP_APPL 600 SP15 or a higher version/SP          
| Integration add-on for SAP ERP CO Master Data and SAP SuccessFactors Employee Central | ODTFINCC 600 SP10 or higher |        

## SAP BTP Provider Account

* SAP BTP [subaccount](https://help.sap.com/products/BTP/65de2977205c403bbc107264b8eccf4b/8ed4a705efa0431b910056c0acdbf377.html?locale=en-US#loio8d6e3a0fa4ab43e4a421d3ed08128afa)

### Entitlements

The application requires the following [Entitlements and Quotas](https://help.sap.com/products/BTP/65de2977205c403bbc107264b8eccf4b/00aa2c23479d42568b18882b1ca90d79.html?locale=en-US) in the SAP BTP cockpit:

| **Service**                           | **Plan**       | **Number of Instances** |
|-----------------------------------|------------|:-------------------:|
| Integration Suite       | enterprise_agreement (Application) |   1    |
| Process Integration Runtime       | integration-flow |          1    |
| Master Data Integration           | sap-integration  |          1    |
| Master Data Integration (Orchestration) | standard (Application) |   1 |


