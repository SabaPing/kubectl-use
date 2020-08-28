# kubectl-use

Plugin for simple switch kubernetes contexts and namespaces

## Example usage

```bash
# kubectl use l
CURRENT   NAME          CLUSTER       AUTHINFO              NAMESPACE
          dev           dev-cluster   admin                 monitor
          beta          beta-cluster  admin                 monitor
*         prod          prod-cluster  developer             monitor

# kubectl use prod
Switched to context "prod".

# kubectl use default
Switched to namespace "default".

# kubectl use stage kube-system
Switched to context "stage".
Switched to namespace "kube-system".
```

## Installation

```
curl -LO https://github.com/SabaPing/kubectl-use/raw/master/kubectl-use
chmod +x ./kubectl-use
sudo mv ./kubectl-use /usr/local/bin/kubectl-use
```
