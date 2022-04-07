# Change Log
All notable changes to the "dynamics-365ce-javascript-snippets" extension will be documented in this file.

## [1.1.0]
- Fixed updateRecord script in which it wrote createRecord instead of updateRecord.
- Added snippets for the following
 Xrm.Utility.getEntityMainFormDescriptor(entityName, formId)
 Xrm.Utility.getGlobalContext().client.isNetworkAvailable()
 Xrm.Utility.getGlobalContext().organizationSettings.baseCurrency
 Xrm.Utility.getGlobalContext().organizationSettings.isTrialOrganization
 Xrm.Utility.getGlobalContext().organizationSettings.organizationExpiryDate
 Xrm.Utility.getGlobalContext().organizationSettings.fullNameConventionCode
 Xrm.Utility.getGlobalContext().userSettings.roles
 Xrm.Utility.getGlobalContext().userSettings.getSecurityRolePrivilegesInfo().then(successCallback, errorCallback)
 Xrm.Utility.getGlobalContext().userSettings.transactionCurrency
 Xrm.Utility.getGlobalContext().getWebResourceUrl(webResourceName)
 Xrm.Utility.getPageContext()

- Used let instead of var when initializing variables

## [1.0.0]
- Initial release of Dynamics 365CE Javascript Snippets extension.