Comandos:
```
cd /root
mkdir whaticket
cd whaticket
git clone https://github.com/apouaoui/whaticket-10.12.0.git
cd whaticket-10.12.0
mv ./* .
cd ..
sudo ./instalador
```

cd ./whaticket
sudo chmod +x whaticketsaas
sudo ./whaticketsaas

===================================================

login: admin@admin.com
senha: 123456

===================================================

Configuração de e-mail dentro do BACKEND no arquivo ENV

MAIL_HOST="smtp.gmail.com"
MAIL_USER="seu-email"
MAIL_PASS="sua-senha"
MAIL_FROM="seu-email"
MAIL_PORT="587"

Configuração de pagamento GERENCIANET dentro BACKEND no arquivo ENV

GERENCIANET_SANDBOX=true
GERENCIANET_CLIENT_ID=sua-id
GERENCIANET_CLIENT_SECRET=sua_chave_secreta
GERENCIANET_PIX_CERT=nome_do_certificado
GERENCIANET_PIX_KEY=chave_pix_gerencianet

# para usar GERENCIANET Em backend\certs
# Salvar o certificado no formato .p12
