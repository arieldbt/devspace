---
title: "devspace restart --help"
sidebar_label: devspace restart
---


Restarts containers where the sync restart helper is injected

## Synopsis


```
devspace restart [flags]
```

```
#######################################################
################## devspace restart ###################
#######################################################
Restarts containers where the sync restart helper
is injected:

devspace restart
devspace restart -n my-namespace
#######################################################
```


## Flags

```
  -c, --container string        Container name within pod to restart
  -h, --help                    help for restart
  -l, --label-selector string   Comma separated key=value selector list (e.g. release=test)
      --name string             The sync path name to restart
      --pick                    Select a pod (default true)
      --pod string              Pod to restart
```


## Global & Inherited Flags

```
      --debug                        Prints the stack trace if an error occurs
      --disable-profile-activation   If true will ignore all profile activations
      --inactivity-timeout int       Minutes the current user is inactive (no mouse or keyboard interaction) until DevSpace will exit automatically. 0 to disable. Only supported on windows and mac operating systems
      --kube-context string          The kubernetes context to use
  -n, --namespace string             The kubernetes namespace to use
      --no-warn                      If true does not show any warning when deploying into a different namespace or kube-context than before
      --override-name string         If specified will override the devspace.yaml name
  -p, --profile strings              The DevSpace profiles to apply. Multiple profiles are applied in the order they are specified
      --silent                       Run in silent mode and prevents any devspace log output except panics & fatals
  -s, --switch-context               Switches and uses the last kube context and namespace that was used to deploy the DevSpace project
      --var strings                  Variables to override during execution (e.g. --var=MYVAR=MYVALUE)
```

