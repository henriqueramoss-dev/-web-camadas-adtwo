# -web-camadas-adtwo

1. Como a API rodava localmente:

O servidor rodava a parti do comando node src/server.js digitado no terminal;

No .env constava o DATABASE_URL, JWT_SECRET e PORT

DATABASE_URL = "mysql://USUARIO:SUA_SENHA@HOST:PORTA/defaultdb?ssl-mode=REQUIRED"
JWT_SECRET = "BARBEARIA EXEMPLO"]
PORT = 3000

Segue o exemplar do banco de dados rodando localmente:

<img width="767" height="297" alt="Captura de tela 2026-05-26 203927" src="https://github.com/user-attachments/assets/23b34706-2ef6-4530-8d46-8bccd899eb12" />

2. Opções de hospedagem gratuita para APIs Node.js

Render:

O Render possui suporte nativo para aplicações Node.js com Express, sendo uma das plataformas mais usadas para APIs REST

Plano gratuito:

suporte a aplicações Node.js e Express
deploy automático integrado ao GitHub
SSL gratuito
variáveis de ambiente
logs da aplicação

Limites do plano gratuito:

instâncias gratuitas entram em sleep após inatividade
wake-up demora alguns segundos quando a API recebe nova requisição
aproximadamente 256 MB de RAM na instância gratuita
limite mensal de horas gratuitas compartilhadas no workspace

Railway:

O Railway também suporta aplicações Node.js com Express e possui deploy automatizado diretamente pelo GitHub.

Plano gratuito:

Atualmente o Railway funciona principalmente com sistema de créditos gratuitos.

Limites do plano gratuito:

trial inicial com créditos gratuitos
depois do período gratuito, o plano free possui crédito mensal limitado
serviços usam aproximadamente:
até 1 vCPU
cerca de 512 MB RAM no plano básico
dependendo do uso, os créditos acabam rapidamente em aplicações rodando 24h


Fly.io:

O Fly.io suporta aplicações Node.js e Express através de containers e máquinas virtuais distribuídas globalmente.

Plano gratuito:

O Fly.io já teve free tier mais generoso, mas atualmente trabalha principalmente com trial gratuito.

Limites do plano gratuito:

trial gratuito limitado por tempo e créditos
cerca de 2 horas de runtime ou 7 dias de acesso no trial inicial
após isso, cobrança baseada em uso
infraestrutura baseada em máquinas virtuais leves


Eu escolhi o Render por ser uma opção mais facil de mexer e enquanto o restante exige mais alguns recursos para poderem ser usadas gratuitamente


3. O deploy da sua API — passo a passo real

O repositório foi conectado pelo proprio login do github

A variáveis foram configuradas na parte de Environment/Environment Variables na Render 




