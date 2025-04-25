# 🔥 Provisionamento Automático de Servidor Web Apache

![Badge Status](https://img.shields.io/badge/Status-Concluído-green) 
![Licença](https://img.shields.io/badge/Licença-MIT-blue)

Script Bash para deploy completo de servidor Apache em **Ubuntu/Debian** com apenas um comando.

## 🚀 Recursos
✔️ Instalação automática do Apache2  
✔️ Configuração de Virtual Hosts  
✔️ Liberação automática de portas no firewall  
✔️ Página HTML de teste incluída  
✔️ Verificação de status do serviço  

## 💻 Pré-requisitos
- Linux (Ubuntu/Debian)
- Acesso root (sudo)
- Conexão com internet

## 🛠️ Instalação
```bash
# Clone o repositório
git clone https://github.com/kedma-montedori/apache-automation.git

# Execute o script
cd apache-automation/scripts
chmod +x provisiona-apache.sh
sudo ./provisiona-apache.sh
⚙️ Personalização
Edite estas variáveis no script:

bash
SITE_NAME="meusite.com"          # Nome do seu domínio
DOC_ROOT="/var/www/$SITE_NAME"   # Diretório raiz
ADMIN_EMAIL="admin@meusite.com"  # E-mail do administrador
📊 Testando
Verifique o funcionamento:

bash
curl -I localhost
# Ou acesse no navegador:
http://seu-ip
🐛 Solução de Problemas
Erro de porta ocupada: Execute sudo netstat -tulnp | grep 80

Permissões: Certifique-se de executar com sudo

Logs: Verifique em /var/log/apache2/error.log

📌 Exemplo de Uso
bash
# Para um site chamado 'loja.com'
sudo ./provisiona-apache.sh --domain loja.com --email webmaster@loja.com
🤝 Contribuição
Faça um Fork

Crie um branch (git checkout -b feature/nova-funcionalidade)

Commit (git commit -m 'Adiciona X feature')

Push (git push origin feature/nova-funcionalidade)

Abra um Pull Request

📜 Licença
Este projeto está sob licença MIT - veja LICENSE para detalhes.

✍️ Autor: Kedma Montedori
🔗 Repositório: github.com/kedma-montedori/apache-automation
