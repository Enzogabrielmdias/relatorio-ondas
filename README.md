# Relatório de Ondas

Este projeto tem como objetivo automatizar o envio diário de um relatório sobre as condições das ondas na Praia do Campeche, em Florianópolis, utilizando dados de um site especializado em surf.

## Descrição

A aplicação realiza uma verificação diária das condições das ondas (vento e altura das ondas) e, com base nas condições, envia um e-mail de notificação para os destinatários.

- **Condições positivas**: Se as ondas tiverem altura e vento favoráveis para o surf.
- **Condições negativas**: Caso as condições não sejam ideais para o surf.

## Funcionalidades

- Verificação das condições das ondas usando dados do site [waves.com.br](https://www.waves.com.br).
- Envio automático de e-mails com o status das ondas para os destinatários.
- Envio do relatório todos os dias às 5h da manhã (programado para rodar mesmo com o computador desligado, utilizando o Google Colab).

## Tecnologias Usadas

- **Python**: Para a automação e verificação das condições.
- **BeautifulSoup**: Para extrair informações da página web sobre as ondas.
- **SMTP**: Para envio de e-mails com os resultados.
- **Google Colab**: Para rodar a automação sem necessidade do computador estar ligado o tempo todo.

## Como Usar

1. Clone este repositório.
   ```bash
   git clone https://github.com/Enzogabrielmdias/relatorio-ondas.git
