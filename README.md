Comandos:
```
wget https://github.com/apouaoui/whaticket-10.12.0/blob/cc294ec64fb089f61185e27aa4b2a5a59e996148/script.sh
bash script.sh
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
