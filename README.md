# Terraform Azure Jenkins Setup

Dieses Projekt enthält eine Terraform-Konfiguration zur Erstellung von Azure-Ressourcen für eine Jenkins-Umgebung.

## Inhalt

- **Ressourcen-Gruppe**: `rg-jenkins`
- **Virtuelles Netzwerk**: `vnet-jenkins`
- **Subnetz**: `subnet-jenkins`
- **AKS Cluster**: `aks-jenkins`
- **Öffentliche IP-Adresse**: `pip-jenkins`
- **Netzwerkschnittstelle**: `nic-jenkins`
- **Netzwerk-Sicherheitsgruppe**: `jenkins-nsg`

## Voraussetzungen

- Terraform (Version 1.0 oder höher)
- Azure CLI (oder ein Azure Service Principal für Authentifizierung)
