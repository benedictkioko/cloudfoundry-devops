## Installation

From the root directory, using the Cloud Foundry CLI push your app to the SAP CP Cloud Foundry

```
$ cf push
```

### Then set the Environment Variables accordingly

```
cf set-env cf_servicelayer B1_SERVER_ENV http://hanab1
cf set-env cf_servicelayer B1_SLPORT_ENV 50001
cf set-env cf_servicelayer B1_SLPATH_ENV /b1s/v1
cf set-env cf_servicelayer B1_USER_ENV manager
cf set-env cf_servicelayer B1_PASS_ENV 1234
cf set-env cf_servicelayer B1_COMP_ENV SBODEMOUS
```
