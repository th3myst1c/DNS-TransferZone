# DNS TransferZone
Ferrmenta Criada durante a a semana 5 de reconhecimento de Infra das aulas da Desec Security.
O Intuito da ferramenta é realizar a resolução de servidores DNS a partir do utilitário `host` com um endereço web e com o endereço desses servidores DNS realizar uma tentativa de DNS Transfer Zone.
Adendo, antes da execução da ferramenta, verifique pelo NMAP ou por alguma ferramenta de recon se a porta 53 DNS TCP está aberta no servidor que você quer realizar  o teste.

Para executar, basta dar permissões de uso ao arquivo.
- ```chmod +x dnszone.sh```
- ```./dnszone.sh <subdomain.com.br>```
