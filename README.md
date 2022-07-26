## Usage

```shell
    export CHART_NAME=smtp-relay
    export CHART_REPO_NAME=smtp-relay-chart
    helm repo add $CHART_REPO_NAME https://iits-consulting.github.io/$CHART_REPO_NAME/
    helm search repo $CHART_NAME
    helm install $CHART_NAME $CHART_REPO_NAME/$CHART_NAME
```

## Description
Deploys smtp-relay

## ToDo
* Container health checks need to be present