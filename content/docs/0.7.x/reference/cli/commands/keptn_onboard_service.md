---
date: "2020-10-12T14:26:31+02:00"
title: "keptn onboard service"
slug: keptn_onboard_service
---
## keptn onboard service

Onboards a new service and its Helm chart to a project

### Synopsis

Onboards a new service and its Helm chart to the provided project. 
Therefore, this command takes a folder to a Helm chart or an already packed Helm chart as .tgz.


```
keptn onboard service SERVICENAME --project=PROJECTNAME --chart=FILEPATH [flags]
```

### Examples

```
keptn onboard service SERVICENAME --project=PROJECTNAME --chart=FILEPATH

keptn onboard service SERVICENAME --project=PROJECTNAME --chart=HELM_CHART.tgz

```

### Options

```
      --chart string                 A path to a Helm chart folder or an already archived Helm chart
      --deployment-strategy string   Allows to define a deployment strategy that overrides the shipyard definition for this service
  -h, --help                         help for service
  -p, --project string               The name of the project
```

### Options inherited from parent commands

```
      --mock                 Disables communication to a Keptn endpoint
  -q, --quiet                Suppresses debug and info messages
      --suppress-websocket   Disables WebSocket communication to suppress info messages from services running inside Keptn
  -v, --verbose              Enables verbose logging to print debug messages
```

### SEE ALSO

* [keptn onboard](../keptn_onboard/)	 - Creates a new service and uploads its Helm chart to the branches in the Git repository

###### Auto generated by spf13/cobra on 12-Oct-2020
