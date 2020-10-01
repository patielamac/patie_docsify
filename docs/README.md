# Code7 Omni
Portal de negócios e atendimento customizável e flexível para empresas onde é possível, de forma simples e objetiva: 
* configurar URA
* realizar atendimento multicanal
* configurar agentes
* configurar serviços e produtos
* distribuir atendimento de serviços para grupos de agentes específicos
* cadastro de clientes
* manter histórico de atendimento consolidado multicanal
* prestar continuidade ao atendimento do cliente sempre o mesmo operador/usuário
* gerar relatórios gerenciais
* administrar quantos e quais tipos de canais serão atendidos por operador (atendimento simultâneo configurável por operador)

Oferecendo excepcional qualidade de chamadas porque não utiliza VoIP, mas canais de telefonia convencional do tipo ISDN. Isso quer dizer qualidade total de voz, com a compatibilização de custos que só os sistemas digitais podem viabilizar. 

![Code7 Omni](/imgs/Apresenta.PNG "Apresentação Code7 Omni")

## Cadastros
<h3>Usuário</h3>
A Tela de usuários traz os usuários já cadastrados na organização e também a possibilidade de criar novo cadastro bem como editar um já existente.
Apresenta os campos disponíveis com sinalização dos campos obrigatórios (*).

![Cadastro usuario](/imgs/Tela_Cadastro.PNG "Tela Usuario")

Na tela de cadastro terão campos para trazer as informações de:
- Cadastro de novos usuários
- Informações pessoais 
- Informações do perfil de atendimento 
- Alteração de usuários já cadastrados 
- Atualização de Status – Usuário Ativo ou Inativo 
- Relacionamento de Produtos e Serviços para o usuário
- Permissões 
- Nível de acesso – Admin / Gerente / Usuário

_Cadastro de usuário_
![Cadastro usuario](/imgs/Usuario_1.PNG "Cadastro Usuario1")
![Cadastro usuario](/imgs/Usuario_2.PNG "Cadastro Usuario2")

_**nota:**_ o link de “salvar” apenas ficará disponibilizado na tela após o preenchimento dos campos obrigatórios. 

<h3>Serviços</h3>

Na tela principal de serviços estão disponibilizados os links para cadastro de um novo serviço onde será inserido:
- Nome
- nome do serviço a ser cadastrado
- Atendimento (%) - qual a porcentagem de atendimento desejada para o serviço
- Tempo Atendimento(s) - qual o tempo desejado para que seja inicializado o atendimento
- Tempo Abandono(s) - qual o tempo aceitável para que o atendimento tenha abandono
- Habilitar tela de Atendimento - se o serviço estará ou não habilitado para que seja atendido na Tela de Atendimento

_Tela de Serviços_

![Cadastro servicos](/imgs/Servicos_1.PNG "Tela Serviços")

_Edição de Usuários_

![Cadastro servicos](/imgs/Servicos_2.PNG "Edição Usuários")


_Tela de Cadastro de Serviços_

![Cadastro servicos](/imgs/Servicos_3.PNG "Edição Serviços")


Estão também disponibilizados os links para que seja:
- Editado quais usuários que atenderão o serviço
- Editado o serviço
- Excluído o serviço
- Ativado/Desativado o serviço


_Links de edição_

![Cadastro servicos](/imgs/Servicos_4.PNG "Links para Edição Serviços")


<h3>Tags</h3>

O cadastro das Tags além da finalização do atendimento traz opções de cadastro para que seja realizado:
- registro da informação (como foi realizado o atendimento, se houve venda, cancelamento ou novas negociações)
- mensagem automática de finalização
- transferência automática para outro tipo de serviço
- finalização do telefone (em casos que foi identificado pelo usuário/operador que o telefone não pertence ao contato)
- finalização do contato (em casos onde o contato deixa claro que não quer mais receber ligações)


_Tela principal Tags_
![Cadastro tag](/imgs/Tag_1.PNG "Tela TAG")


_Cadastro de nova Tag_
![Cadastro tag](/imgs/Tag_2.PNG "Cadastro TAG")

<h3>Conectores</h3>

<h3>Contatos</h3>

<h3>Blacklist</h3>

<h3>Shortcuts</h3>

<h3>Pausas</h3>

## Canais

Em Canais são realizados os cadastros de todas as mídias que a empresa terá para atendimento, voz, whatsapp, webchat, e-mail e mercado livre.

_Tela de Canais_
![Canais](/imgs/Canais_1.PNG "Tela dos Canais")

### Telefone
### Whatsapp
### Boteria
### E-mail
### Canal de Integração Mercado Livre
## Tela de Atendimento
## Gerenciamento de Atendimento
## Visão dos Agentes

## Discador

A funcionalidade do discador da plataforma Code7 Omni traz agilidade e facilidade na criação e gerenciamento de Campanhas onde se pode criar o grupo de contatos, estratégia e campanhas que irão fazer parte da discagem em massa

### Grupo de Contatos
Na Tela de Grupo de Contatos se cria e edita os contatos que receberão as ligações de sua Campanha.

![Grupo Contatos](/imgs/Grupo_Contatos_Discador.PNG "Discador Grupo Contatos")

As informações da tela inicial do Grupo de Contatos são:
* Tabela dos grupos já criados:
    - nome
    - quantidade de contatos (total de contatos que constam em cada Grupo Campanha - o nome da campanha relacionada ao Grupo de Contato (após o entrelaçamento de Campanha e Grupo de Contato não será mais possível a edição do Grupo)
    - Status do Grupo - Se está Ativo ou não.
* Filtros para buscar grupos
    - por nome do grupo
    - pela campanha
    - status 
* Ação em Lote onde poderá:
    - Ativar os grupos selecionados
    - Inativar os grupos selecionados 

**Importação de um Novo Grupo de Contatos**
Para criação de um Grupo de contato, deverá ser importado um arquivo CSV respeitando a formatação do modelo que está disponibilizado na plataforma.

![Novo Grupo Contatos](/imgs/Inserir_grupo.PNG "Inserir Grupo Contatos")

 - Selecione o ícone com o **“+”** na tela principal
 - No campo Grupo de Contatos, insira um nome para seu novo grupo que será importado, escolha bem o nome, pois uma vez criado ele não ficará disponível para alteração do nome.
 - Clique no ícone de upload escolha seu arquivo CSV e faça a importação.
 - Para baixar o modelo que deverá ser utilizado, clique no “Clique aqui” e faça o download do modelo do arquivo.
 
 ![Importar Grupo Contatos](/imgs/Importar_grupo_contato.PNG "Importar Grupo Contatos")
 
 Ainda sobre o CSV - o que você precisa saber:
    - O nome do contato é campo obrigatório
    - Cada campo deverá se separado por ponto e vírgula (;)
    - Deverá ter ao menos um telefone válido para discagem
    - No campo de telefone, quando for um telefone fixo - deverá ter 12 caracteres - DDI+DDD+número válido para telefone fixo ex.: 554734322422
    - No campo telefone, quando for um telefone móvel - deverá ter 13 caracteres onde a 5ª posição sempre será o número 9 - DDI+DDD+número válido para telefone fixo ex.: 5548**9**98288774
    - Se o contato estiver com fones incorretos, ele não será importado
    - Não há obrigatoriedade de todos os campos estarem preenchidos para importação, com exceção do obrigatório comentado no item 1. 
**Edição Grupo de Contatos**
Na Tela de Edição (somente liberada se o grupo de contato não estiver associado a uma campanha) de grupo de contatos é possível:
    - Importar outro arquivo CSV para um grupo já existente
    - Desativar um grupo de contato
    - Ativar um grupo de Contato
    
![Editar Grupo Contatos](/imgs/Editar_grupo_contato.PNG "Editar Grupo Contatos") 
    
**Consulta - Grupo de Contatos**

### Estratégia
**Criação - Estratégia de Discagem**
**Edição - Estratégia**
### Campanha
**Criação de uma nova Campanha**
**Controles Manuais**
**Controles Automatizados**
### Monitoramento

## Broadcast - HSM
A funcionalidade da plataforma Code7 Omni traz agilidade e facilidade na criação e gerenciamento de Campanhas onde se pode criar o grupo de contatos, campanhas e estratégia de envios com monitoramento para envio de mensagens de whatsapp em massa.

São pré-requisitos para o envio:
- Número de telefone cadastrado no Canal de Whatsapp
- Aprovação dos HSM dentro das normas geradas pelo Facebook para que as mensagens possam ser enviadas.

    
### Criação - Grupos de Contatos
A criação de grupo de contatos poderá ser realizada de duas formas:
- Por meio de importação de um arquivo tipo CSV
- Por meio da importação de todos os contatos já cadastrados em sua empresa
  
**Tela de Importação de Grupo de Contatos**
- Inserir Nome do Grupo de Contatos
- Optar ou por "Utilizar contatos Omni" ou "Fazer upload de arquivo"
- Salvar

**Filtros em Grupo de Contatos

### Criação de Campanha
### Criação de Envios
### Monitoramento
## Glossário Relatórios
### Rastreio de Interações
### Relatório IVR
## Exportações
**Relatório de Usuários**
**Relatório de Chamadas**
**Relatório de Atividade**
**Relatório de Broadcast HSM**
**Consolidado**
**Detalhado**
**Histórico Importação**
**Relatório Broadcast Grupo de Contatos**
**Relatório Discador Grupo de Contatos**
**Relatório Discador**

