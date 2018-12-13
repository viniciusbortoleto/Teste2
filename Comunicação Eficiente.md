# Comunicação eficiente
tESTE
tESTE Um dos maiores desafios do nosso dia a dia é se comunicar de forma eficiente tanto com a equipe quanto com o restante da empresa, abaixo algumas dicas para uma comunicação eficiente.

- **Respeite o tempo dos outros**. Não notifique no chat ou interrompa outra pessoa a não ser que seja realmente necessário
- **Utilize as ferramentas certas e mais eficientes** para cada situação.
- Ao se comunicar com outro departamento,**respeite as ferramentas e processo deles**

## Quando usar cada ferramenta?
####  Chat
   - Dúvidas simples ou rápidas sobre algo que você está trabalhando no momento
   - Verificar disponibilidade de outra pessoa ou confirmar alguma informaçã
####  Hangout
  - Dúvidas mais complexas que seja mais fácil de explicar mostrando a tela ou código
  - Utilizar voz/vídeo é sempre mais eficiente que chat, use sempre que possível
#### Trello
   - Dúvidas, comentários e definições referentes a um card específico
   - Dúvidas que precisam de definição ou ajuda de outros membros, mas que não são urgentes
   - Documentar decisões tomadas utilizando Chat ou Voz

## Chat

### Google Chat

A Monde utiliza o Google Chat como ferramenta de chat padrão, você pode acessar em: [chat.google.com](https://chat.google.com/) utilizando a conta da Monde. Caso esteja logado com sua conta pessoal do gmail, pode ser necessário acessar diretamente via [chat.google.com/u/1](https://chat.google.com/u/1).

#### Canais que você deverá participar:
- Comunicados
- Dev
- Time Produto
- Produto
- Random

#### Boas práticas nos chats
- Evite enviar apenas “Olá”, “Bom dia”, etc e esperar a pessoa responder. 
   - O tempo que ficamos esperando resposta para o bom dia, já poderíamos estar resolvendo o problema ou respondendo a dúvida.
   - Seja educado, mas sempre envie o “Olá” juntamente com o assunto. (Shift + Enter) para quebrar linhas.
- Caso um dev responda para você de forma direta, não entenda como falta de educação, provavelmente ele está ocupado.
   - Utilize emojis/memes para quebrar o gelo. No chat é muito fácil algo parecer negativo ou mal educado, utilize emojis e memes para facilitar o entendimento. 😜
   
## Conversas de vídeo e voz
Para voz e vídeo, utilizamos [Google Hangouts](http://hangouts.google.com), [appear.in](https://appear.in/), [Skype](https://www.skype.com).

Também utilizamos o [zoom.us](https://zoom.us/) para reuniões maiores, pois as outras ferramentas não suportam mais que 10 pessoas.

Hangouts geralmente para reuniões e o [appear.in](https://appear.in/) para conversas 1 a 1 pois é mais fácil abrir a sala, use o que for mais fácil para você.

Dica: Registre uma sala com o seu nome no appear.in assim você sempre tem um canal centralizado para conversar com os outros e não corre o risco de perder uma sala

Skype é utilizado para ligar para clientes, fornecedores, etc. Caso precise fazer ligações via Skype é necessário criar uma conta para a Monde e solicitar ser adicionado ao Skype Manager da Monde para ter créditos.

## Trello
A equipe de desenvolvimento usa o Trello como principal ferramenta para controlar os itens a fazer e bugs a corrigir, portanto ela deverá ser a principal ferramenta no seu dia a dia de trabalho.

Bons hábitos de uso do Trello irão facilitar seu trabalho, torná-lo transparente e ajudar tanto a equipe quanto o restante da empresa acompanhar o progresso das tarefas.

#### Boards
As boards utilizadas pelo desenvolvimento ficam no Trello da Monde: [https://trello.com/monde](https://trello.com/monde)

**Faça login no Trello usando seu e-mail da Monde** para que possa ser adicionado a organização.

Depois ingresse nas boards:

- [Bugs / Dúvidas](https://trello.com/b/rV7wzc5K/bugs-d%C3%BAvidas)
- [Desenvolvimento](https://trello.com/b/Kwq4o8Fp)

#### Usando o Trello de forma eficiente
- **Crie cards para tudo** o que for fazer ou precisar ser feito. Tudo, sem exceções.
    - Seja **claro e objetivo no título** e lembre-se que outras pessoas precisam entender o card.
    - **Adicione uma descrição** que explique os motivos ou objetivos do card.
- **Lembre-se de colocar tags**, elas nos ajudam a filtrar e tirar relatórios.
- **Crie checklists** nos cards para organizar os passos, principalmente em tarefas maiores
- **Anexe** screenshots, bugreports e outras informações que podem ser úteis.
- **Mantenha o card na lista correta** que reflita o status atual da tarefa. 
   - Começou a trabalhar no card? Mova para fazendo. 
   - Parou de trabalhar no card? Mova de volta.
   - Finalizou o trabalho e precisa de testes? Mova para testar.
   - Deu merge? Mova para a coluna referente a versão onde foi dado o merge.
- **Anexe o Pull Request** no card, ajuda a ver se o build está ok e vincula o card ao PR.
- **Nunca arquive cards sem comentar o motivo**.
- **Documente no card decisões tomadas**. Geralmente é mais prático e rápido decidir algo conversando por voz, chat ou pessoalmente. Nesses casos, sempre documente a decisão no card, atualizando a descrição e comentando quem participou da decisão e porque ela foi tomada.

#### Extensões recomendadas
Recomendamos instalar as seguintes extensões no chrome:

- [Trello Card Numbers](https://chrome.google.com/webstore/detail/trello-card-numbers/kadpkdielickimifpinkknemjdipghaf?utm_source=chrome-app-launcher-info-dialog)

#### Fluxo de trabalho
- **Sempre da esquerda para a direita**, nas respectivas boards.
- **Mantenha os cards na lista correta e com a pessoa correta**
   - **Ao iniciar o trabalho em um card**, revise se entendeu o problema, **se adicione ao card** e mova para **Fazendo**.
   - **Ao parar o trabalho em um card** mova de volta para **A fazer**.
   - **Se o card não depende de você** ou pode ficar disponível para outra pessoa, **se remova do card**.
- **Mova o card para testes** ao terminar a implementação
   - **Adicione informações** que podem ser úteis ao testador.
   - **Adicione o PR no card**, através da integração com o GitHub.
   - **Não adicione o testador ao card**, apenas mova para a coluna testar.
- **Ao concluir um card mova-o para a lista correspondente a versão**, ou para concluído em caso de tarefas.
- **Adicione outra pessoa e saia do card** caso o ele não dependa mais de você.
- Ao **trabalhar em conjunto** com outra pessoa no mesmo card, **mantenha ambos no card**.
