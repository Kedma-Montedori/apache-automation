# 🚀 Provisionamento Automático de Servidor Apache

Script Bash para deploy automático de servidor web Apache em Linux.

## ⚙️ Funcionalidades
- Instala e configura Apache2
- Cria virtual hosts
- Configura firewall (UFW)
- Gera página de teste

## 🛠️ Como Usar
```bash
git clone https://github.com/seu-usuario/apache-automation.git
cd apache-automation/scripts
chmod +x provisiona-apache.sh
sudo ./provisiona-apache.sh
📝 Personalização
Edite no script:

bash
SITE_NAME="meusite.com"       # Nome do site
DOC_ROOT="/var/www/$SITE_NAME" # Diretório raiz
📊 Teste
Verifique com:

bash
curl -I localhost
📜 Licença
MIT License - veja LICENSE


### Passos para criar:
1. **No GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Script inicial de provisionamento"
   git branch -M main
   git remote add origin https://github.com/seu-usuario/nome-repositorio.git
   git push -u origin main
Boas práticas:

Adicione tags como #bash #apache #automation

Inclua um .gitignore para Linux

Adicione workflows de CI/CD (opcional)

🔗 Links Úteis:
Modelo de LICENSE

Badges para README

