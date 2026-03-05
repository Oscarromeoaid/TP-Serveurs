# Win_2 - Serveur IIS + SSL

## Étapes réalisées

### 1. Installation IIS
- IIS installé via Enable-WindowsOptionalFeature
- Service actif sur port 80

### 2. Page Intranet
- Page HTML créée dans C:\inetpub\wwwroot\
- Accessible sur http://localhost

### 3. Certificat SSL
- Certificat auto-signé créé (intranet.local)
- Binding HTTPS configuré sur port 443
