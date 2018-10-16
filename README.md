Po wydaniu komendy 
"az group deployment create --resource-group test50 --template-file azuredeploy.json --parameters azuredeploy.parameters.json" 
wybieramy środowisko PROD/TEST/DEV a później dzieje się magia :)

Konwencja nazewnicza:

VM:
VMnameenv

NIC:
VMname-nic

PubIP:
vmnamepubip

NSG:
vmnameNSGname

Ewentualnie można dodać lokalizację jeżeli mamy zasoby rozsiane po całym świecie.


RBAC załączony w pliku
