
Tools:
- [Vsiual Studio Code](https://code.visualstudio.com/)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
- [git](https://git-scm.com/downloads)

Login:
- `az login --use-device-code`
- `az account list -o table`
- `az account set -s <id>`
- `az aks install-cli`
- `az aks get-credentials --name <aks name> --resource-group <resource group name>`


Commands:
- `kubectl create ns <name>`
- `kubectl config set-context --current --namespace <name>`
- `kubectl apply -f nazwa.yaml`
