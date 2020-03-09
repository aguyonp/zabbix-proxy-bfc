# Zabbix-Proxy-Bfc
![https://bourgognefranchecomte.chambres-agriculture.fr/fileadmin/user_upload/Bourgogne-Franche-Comte/061_Inst-Bourgogne-Franche-Comte/Interface/BFC_LOGO_RVB_COULEUR.png](https://bourgognefranchecomte.chambres-agriculture.fr/fileadmin/user_upload/Bourgogne-Franche-Comte/061_Inst-Bourgogne-Franche-Comte/Interface/BFC_LOGO_RVB_COULEUR.png)

Fichiers de configuration permettant le déploiement de serveurs 
**zabbix-proxy** sur le réseau **BFC**
## Prérequis
/!\ Docker is needed /!\
 - `# apt update ; apt install docker-compose`
## Installation
 - `# git clone https://github.com/aguyonp/zabbix-proxy-bfc`
 - `# cd zabbix-proxy-bfc`
 - /!\ Modifier le fichier docker-compose.yml puis changer la variable 
ZBX_HOSTNAME. Remplacez {DPT} par le département de la région /!\
 - `# docker-compose up -d --build`
## Logs
Cette commande permet de visionner les logs ainsi que les connection 
effectuées par les clients zabbix
    # docker-compose logs
## Fichiers
> docker-compose.yml
