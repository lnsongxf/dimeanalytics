# World Bank SurveyCTO

## Introduction

The World Bank Group’s SurveyCTO Enterprise server is an on-site installation of the SurveyCTO data collection platform, managed by DECIE’s DIME Analytics Group ([contact](mailto:dimeanalytics@worldbank.org)). To start a SurveyCTO survey, visit eServices and submit a request for “[SurveyCTO Data Collection Platform](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=7d1e71b86f16d340db112d232e3ee4aa)”. Requests are fulfilled within 1 business day. Each request becomes a group on the WBG SurveyCTO Enterprise server.

## Cost and Server Limits
The cost is $99 per month per group. Each group is allowed up to 30 forms (i.e. questionnaires), 10,000 mobile submissions, 10,000 web submissions, and 2GB of storage. In eServices, the requestor will designate a ‘Survey Administrator’ for their survey. This person must have a World Bank Group email address for authentication purposes. The Survey Administrator will receive an email as soon as their group is live on the server, at which point they will be able to log on and add all other team members and assign them the appropriate profile. The additional team members can be WBG staff and consultants or trusted external partners, who will then receive an invitation to the server. WBG users will be automatically authenticated; externals will be asked to create a password on their first visit.

## Access and Roles
The Survey Administrator will be able to manage (add/delete) users, forms, and data for their group. New users can be added using the “Configure” tab. Each new user must be assigned a role, which will determine what access the user has to the server. The following standard roles are available for all groups:

- Form and Data Managers: can upload, move, and remove survey forms; can view and export data. Cannot manage users.
- Data Managers: can view and export data. Cannot manage forms or users.
- Enumerators: can view forms and submit questionnaires. Cannot manage users or forms, or access data.

Custom roles are available on request.

## Help and Customer Support
Extensive documentation and resources are available through the “Help” menu on the server. You can download the WBG Enterprise SurveyCTO documentation [here](https://github.com/worldbank/dimeanalytics/archive/surveycto.zip). Questions regarding the software itself (e.g. programming challenges, questions on particular features) should be addressed to SurveyCTO through the Support Center. Please make Support Center requests through the SurveyCTO server. Questions regarding the WBG Enterprise set-up specifically (start a new survey, request custom roles, etc) can be addressed to [dimeanalytics@worldbank.org](mailto:dimeanalytics@worldbank.org).

## Sync Client

The SurveyCTO Sync Desktop application can be installed on WBG computers by local IT. To request it, use the “[Software Installation Request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=bd1e71b86f16d340db112d232e3ee4b7)” in eServices and select ‘SurveyCTO’ in the Software Catalogue. You can also download the Sync client, and license, [here](https://github.com/worldbank/dimeanalytics/raw/surveycto/SurveyCTO_Sync.zip). Documentation, as well as sync clients for non-Windows operating systems, are available [here](https://github.com/worldbank/dimeanalytics/tree/surveycto).

​Place `SurveyCTO_Sync.exe` into `C:/WBG/`, and then copy the `client.lic` file into the “SurveyCTO Sync Storage” folder if authentication fails. By default, this folder usually ends up in Documents, but users may want to put it elsewhere. If you can't find it, open Sync, and then before trying to enter any passwords press "Tools" in the menubar, open Preferences, and you will be able to see where the storage folder is located. Once the file is located the folder, the user will drop the `client.lic` file into the folder and try to open Sync again. Then, the user will be able to close the pop-up without Sync closing.

## Important Notes
Because this is an enterprise installation, you are sharing server space with all other surveys. For the enterprise installation to work smoothly, please make sure to follow these rules; they will be enforced by administrators.

1.	**Anything you add to the server (forms, datasets, etc) must use your server prefix.** For example, the “DECIE_Ghana_Ag” group should use “DECIE_Ghana_Ag_” for all dataset and surveys to avoid naming conflicts. The appropriate prefix will appear in user roles.
2.	**Any datasets and survey forms added to the server should be encrypted.** If this is not done, your confidential data will be visible to the Enterprise Administrators, which may violate your ethical approval agreements.

## Ending a Survey
In the eServices form, you will indicate an anticipated end date for the survey. You will receive a reminder email 5 business days before the selected end date. If you are ready to end the survey, you must remove all forms and data and store in a secure location. Any forms or data remaining on the server on the end date will be deleted. If the survey is lasting longer than expected and you instead would like to extend, you must submit a new eServices request with the same survey name, starting on the planned end date and extending to the desired new end date. Your group will continue with no interruption.
