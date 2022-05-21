# Aula 03 - 20/04/2022

# Resumo

**Clonar repositórios**

Clonar repositórios significa , criar uma cópia local em qualquer máquina que represente o repositório que está versionado

No site do github ao entrar nos detalhes de um repositório é possível realizar o clone do mesmo, mas isso não significa que qualquer pessoa pode alterar o seu repositório publicado.

As alterações realizadas por quem faz um clone precisam de commits e push para atualizar a versão publicada e sem autorização não será possível.

**Realizar commits**

Todas as mudanças que fazemos no clone ainda estão em nossa maquina e para refletir as mudanças é necessário confirmar que as alterações foram concluídas agregando-as em um pacote de mudanças chamado commit

Para realizar o commit é necessário selecionar os arquivos que estarão nesse pacote e definir uma mensagem para esse commit para fins de organização e auditoria.

Mesmo fazendo commit as mudanças não serão refletidas no repositório so significa que os arquivos listados estão prontos

**Subir push**

O push é o ato de empurrar as mudanças para o repositório.

É nesse momento que a autenticação será realizada, e caso não ocorra é porque as credenciais já estão armazenadas em sua máquina.

Quando há mais de um usuário na máquina essas credenciais podem ser sobrescritas e será necessário informar novamente, o mesmo procedimento deverá ocorrer se você utilizar outra máquina pois as suas credenciais não estariam salvas lá.

**Criar branches**

O ato de criar branches é fazer o trabalho de forma mais segura e organizada, tendo em vista que o repositório publicado representa o ambiente de produção.

É uma boa prática criar uma ramificação no seu repositório onde as mudanças serão realizadas e confirmadas apenas nessa nova linha do tempo.

Nessa nova linha do tempo é possível simular as correções aplicadas ou melhorias disponibilizadas sem que o publico de produção tenha acesso pois eles estão utilizando um versão ainda sem as suas alterações.

**Realizar pull request**

Quando o trabalho terminar é possível solicitar que a branch principal faça um pull dessa branch onde todas as mudanças serão aplicadas em produção

O pull é a ação e obter as mudanças de uma branch que pode ser a branch atual que foi alterada por outros usurários ou as alterações realizadas em outras branchs.

**Realizar merge request**

O merge request é o ato de aplicar as mudanças na branch alvo e nesse momento as versões dos arquivos serão atualizadas.

Nesse momento é possível que haja conflitos quando mais de um usuário alterou o mesmo arquivo ou alterou a mesma linha do arquivo.

Quando isso ocorre o recurso mais experiente ou um alinhamento entre os envolvidos podem atuar para resolver juntos, qual conteúdo que deve prevalecer em especifico

# Detalhes

## Personalizar perfil do github

Como em toda rede social, o que gera destaque ou engajamento é a apresentação e conteúdo.

O Github é uma rede social sobre versionamento de arquivos e aprendizado onde a maior parte do publico utiliza para versionar o código fonte de sistemas de informações.

Existem 2 recursos escondidos na plataforma que quando utilizados além de gerar destaque também o capacita para superar seus limites.

O primeiro recurso é o profile que é desbloqueado quando é criado um repositório com o mesmo nome do seu username e a flag "add a README file" foi ativada no momento da criação.

Esse README.md é renderizado pela linguagem markdown, por isso a extensão .MD

Não há um regra de como formatar o seu perfil, mas dedicar algumas horas até encontrar um formato que o represente será um diferencial.

OBS: Já que isso é um diferencial, que tal se perguntar

SERÁ QUE EU JÁ FINALIZEI O FORMULARIO DO GITHUB, COM A MINHA FOTO E UMA BIO RESUMIDA ? 

## Criar página pessoal no github

O segundo recurso oculto no github é uma hospedagem gratuita para os frontend inciantes ou quem ainda não quer investir em hospedagem, por motivos financeiros ou porque ainda não domina o conceito de deploy.

Mas ao desbloquear esse recurso você será motivado a praticar essa habilidade além de gerar um identidade virtual na rede ao compartilhar um link com o seu nome.

Para desbloquear esse recurso é necessário criar um repositório com com o mesmo nome do seu username + github.io

Exemplo  username= oliota

oliota.github.io