# Trabalhando no Código
## Configuração das ferramentas
Antes de começar a codificar, leia a documentação sobre como configurar as ferramentas e dependências dos projetos que você irá trabalhar na [Intranet de desenvolvimento](https://sites.google.com/a/monde.com.br/desenvolvimento/home).

## Clean Code
Nós escrevemos código limpo. Para entender melhor o que isso significa e qual a importância, assista a este excelente vídeo do Uncle Bob: [Clean Code, episode 1](https://cleancoders.com/episode/clean-code-episode-1/show)

## TDD
Sempre que possível, usamos TDD no processo de desenvolvimento, ele facilita fazer coisas complexas em passos simples e também faz com que o código final esteja sempre coberto por testes e que os testes realmente testem o código.

Para entender melhor o que é TDD, leia este [artigo](http://tdd.caelum.com.br/).

## Pull Request Driven Development
Nosso processo de desenvolvimento é baseado em [Pull Requests](https://help.github.com/articles/about-pull-requests/), portanto toda alteração no código deverá ser enviado como Pull Request para o repositório.

## GitHub Flow

Nosso fluxo de trabalho com o Github é exatamente igual ao [GitHub Flow](https://guides.github.com/introduction/flow/), exceto as regras de nomes de branches.

## Git
O guia abaixo é um bom resumo dos principais recursos do git utilizados no dia a dia:

[Git - guia prático - sem complicação!](http://rogerdudler.github.io/git-guide/index.pt_BR.html)

## Branches
Para facilitar a organização e ajudar a criar o hábito de criar cards para tudo, utilize o seguinte padrão para o nome de branches:**< board >-<número do card>**. Ou seja, ao corrigir um bug que está no card número 1550, sua branch terá o nome de: **bug-1550**. Uma branch para o card 1200 da board de desenvolvimento será **dsv-1200**.

## Commits
Ao commitar  suas alterações, seja claro e conciso sobre o que seu commit altera, por exemplo:

  - Atualiza URL da Integração X para versão https

Sempre use o texto no imperativo, corrige, altera, etc. 

**Leia o seguinte artigo**: [5 Useful Tips For A Better Commit Message](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message)

Em commits de ajustes, pode-se apenas colocar um título curto, desde que você faça o squash na hora de dar o merge e lembre-se de removê-lo da descrição do merge.

## Revisão de código

Recomendamos que desde o primeiro dia de trabalho você revise tanto seu código quanto o código de outros desenvolvedores para ir se familiarizando com o projeto que você está envolvido, entendendo a estrutura e o padrão de código, etc.

Sempre seja positivo e objetivo em seu review. Review de código é uma ótima ferramenta para encontrar bugs no código, mas a principal vantagem de fazer revisão de código é sempre melhorar, então faça o review pensando em como você pode fazer para tornar o código de seu companheiro de equipe melhor.

- **Revise seu próprio código**. Você ficará surpreso na quantidade de coisas esquecidas e melhorias que você conseguirá encontrar em seu próprio código.
- **Envie o código para review antes de enviar para testes**. Muitas vezes são sugeridas alterações no review que podem causar bugs, então o ideal é que seja revisado antes de testar.
- **Em alterações maiores, envie o código para review gradualmente**. Dessa forma é mais fácil revisar um PR menor e os outros devs podem começar a dar sugestão desde o início.
- **Adicione informações para os outros devs** para ajudá-los a ter mais contexto sobre suas alterações.
- **Anexe screenshots ou um gif** caso tenha alterações visuais.
- **Comente seu próprio PR** caso tenha algo que você tenha feito e que não será muito claro para os outros devs ou que foi necessário mas está fora do habitual.
- **Seja amigável nos comentários**. Questione antes de assumir que o código de seu companheiro está errado. 
- **Sempre que sugerir alterações**, explique os motivos e se possível adicione um link para um artigo ou para o padrão de código de onde você baseou sua sugestão.
- **Se você não entendeu alguma parte do código questione**, pois provavelmente os outros também não entenderão. Após entender sugira modificações para deixar o código mais claro.

## Fazer merge do Pull Request
Após o review aprovado e o PR testado, você mesmo deverá fazer o merge de seu Pull Request.

Sempre utilize a opção **Squash and Merge** para fazer o merge, a não ser que tenha algum motivo onde essa opção não seja a melhor. Ao fazer o merge, edite a descrição removendo textos de commits desnecessários.
