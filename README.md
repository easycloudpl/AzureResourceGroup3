Po wydaniu komendy 
"az group deployment create --resource-group test50 --template-file azuredeploy.json --parameters azuredeploy.parameters.json" 
wybieramy środowisko PROD/TEST/DEV a później dzieje się magia :)

Konwencja nazewnicza:

VM:
<name><env>

NIC:
<VMname>-<nic>

PubIP:
<vmname><pubip>

NSG:
<vmname><NSGname>

Ewentualnie można dodać lokalizację jeżeli mamy zasoby rozsiane po całym świecie.


RBAC załączony w pliku
