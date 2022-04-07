# Change Log
All notable changes to the "dynamics-365ce-javascript-snippets" extension will be documented in this file.

## [1.1.0]
- Fixed updateRecord script in which it wrote createRecord instead of updateRecord.
- Added snippets for the following
1. Xrm.Utility.getEntityMainFormDescriptor(entityName, formId)
2. Xrm.Utility.getGlobalContext().client.isNetworkAvailable()
3. Xrm.Utility.getGlobalContext().organizationSettings.baseCurrency
4. Xrm.Utility.getGlobalContext().organizationSettings.isTrialOrganization
5. Xrm.Utility.getGlobalContext().organizationSettings.organizationExpiryDate
6. Xrm.Utility.getGlobalContext().organizationSettings.fullNameConventionCode
7. Xrm.Utility.getGlobalContext().userSettings.roles
8. Xrm.Utility.getGlobalContext().userSettings.getSecurityRolePrivilegesInfo().then(successCallback, errorCallback)
9. Xrm.Utility.getGlobalContext().userSettings.transactionCurrency
10. Xrm.Utility.getGlobalContext().getWebResourceUrl(webResourceName)
11. Xrm.Utility.getPageContext()

- Used let instead of var when initializing variables

## [1.0.0]
- Initial release of Dynamics 365CE Javascript Snippets extension.