## Cloud Foundry CLI

The cf CLI runs on your local machine to direct a CF deployment in a cloud infrastructure.
A list of common Cloud Foundry CLI commands

### `Deploy/Push`

```
cf push
```

### `Rename App`

```
cf rename APP_NAME NEW_APP_NAME
```

### `List all apps in the target space`

```
cf apps
```

### `Scale`

```
cf scale APP_NAME [-i INSTANCES] [-k DISK] [-m MEMORY] [-f]
```

### `Display health and status for an app`

```
cf app APP_NAME
```

### `Login Users`

```
 cf login
```

### `Logout User`

```
cf logout
```

### `Set or view the targeted org or space`

```
cf target [-o ORG] [-s SPACE]
```

        ALIAS
        ```
        t - OPTIONS
         -o -Organization
        -s -Space
        ```

### `restage`

Recreate the app's executable artifact using the latest pushed app files and the latest environment (variables, service bindings, buildpack, stack, etc

```
cf restage APP_NAME
```

### `restart-app-instance`

Terminate, then restart an app instance

```
cf restart-app-instance APP_NAME INDEX
```

### `Logs`

```
cf logs APP_NAME
```
