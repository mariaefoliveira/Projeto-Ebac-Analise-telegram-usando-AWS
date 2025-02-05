### Você pode visualizar o projeto completo através do Kaggle

link: https://www.kaggle.com/code/noragan/an-lise-das-mensagens-do-telegram-usando-aws

## Contexto
Este projeto tem como objetivo explorar como os dados gerados por interação com bots podem ser utilizados para gerar insights, focando na utilização de sistemas que capturam dados e processam as informações via AWS.

https://sa-east-1.console.aws.amazon.com/console/home?region=sa-east-1#

### Arquitetura

Foi criado um bot no Telegram e inserido a um grupo teste, para que ele pudesse capturar as mensagens que eu enviava. Esse bot é a parte essencial do projeto, pois é ele quem vai pegar os dados brutos (*as mensagens*) que serão processadas eventualmente. Para isso, usei a *API* de bots do Telegram, que tem vários métodos que permitem ao bot acessar essas informações.
___________________

# CONCLUSÃO
##### *A análise realizada é um ótimo processo para verificar o melhor período de interação no grupo para fazer anúncios e passar avisos, para que assim a mensagem seja visualizada pelo maior número de pessoas possível*.

1.  A preferência dos usuários do grupo para envio de mensagens é texto sendo das 12 mensagens enviadas
> Sendo 10 mensagens de **texto** e 2 mensagens de **áudio**

2. O engajamento no grupo nos dois dias que uso caiu drasticamente
> 10 mensagens foram enviadas no primeiro dia (dia inaugural) e 2 mensagens no dia seguinte.

3. O usuário mais ativo foi o mesmo que enviou a mensagem nos dois dias sendo respondido por nenhum usuário por falta de integrantes 
> (Foi um processo realizado apenas para ampliar o que pode ser feito em um processo da análise em um grupo maior)

4. O período de maior tráfego de mensagens foi no período da tarde
> No período das 15 h, foi o período de maior presença do usuário, havendo 6 mensagens enviadas e 3 mensagens no período da noite do mesmo dia.
