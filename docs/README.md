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
Todos os cadastros principais da plataforma serão realizados no link do menu lateral - imagem de uma engrenagem.

![Acesso Cadastros](/imgs/Cadastros_00.PNG "Acesso aos Cadastros")

<h3>Usuário</h3>
A Tela de usuários traz os usuários já cadastrados na organização e também a possibilidade de criar novo cadastro bem como editar um já existente.
Apresenta os campos disponíveis com sinalização dos campos obrigatórios (*).

![Cadastro usuario](/imgs/Tela_Cadastro.PNG "Tela Usuario")

Na tela de cadastro terão campos para trazer as informações de:
- Cadastro de novos usuários
- Informações pessoais
	- Nome - campo obrigatório
	- CPF
	- E-mail - campo obrigatório, pois será utilizado para login do usuário
	- Telefone - campo obrigatório
	- Gênero
	- Data Nascimento
	- CEP
	- País
	- Estado
	- Cidade
	- Endereço
	- Número
	- Complemento
- Informações do perfil de atendimento
	- Serviço Padrão de Voz Outbound - será definido qual serviço ficará registrado para as ligações outbound do usuário, caso não seja preenchido este campo, será definido algum dos serviços que o usuário tenha cadastrado.
	- Número de chats - trata-se do total de atendimentos que o usuário poderá realizar ao mesmo tempo, caso não tenha, será definido 3 atendimentos automaticamente.
	- Status - se Ativo ou Inativo
	- Login automático Softphone - Ativo ou Inativo, esta atribuição será refletida no momento que o usuário faz o login se já ficará ou não disponível para atendimentos.
	- Serviços - será selecionado os serviços em que o usuário fará seus atendimentos, não há limite máximo de serviços para esta definição, porém ao menos 1 serviço deverá ser cadastrado.
- Alteração de usuários já cadastrados
- Nível de acesso – Admin / Gerente / Usuário
- Permissões

_Cadastro de usuário_
![Cadastro usuario](/imgs/Usuario_1.PNG "Cadastro Usuario1")
![Cadastro usuario](/imgs/Usuario_2.PNG "Cadastro Usuario2")

_**nota:**_ o link de “salvar” apenas ficará disponibilizado na tela após o preenchimento dos campos obrigatórios. 


<h4>Segurança - Senha - Primeiro Acesso</h4>

 Quando é finalizado o cadastro do usuário e salvo, um e-mail é disparado para o novo usuário informando um Token para que seja criado a senha e realizado o primeiro acesso.

_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Primeiro Login](/imgs/login_1.png "Exemplo de E-mail novo usuário")

<h4>Segurança - Senha - Recuperar Senha</h4>

Para se recuperar a senha o processo é parecido com o primeiro acesso, basta clicar no link "Primeiro acesso ou recuperar senha" que o usuário receberá um email com um novo token que será utilizado para criar sua nova senha seguindo os passos:
- clicar em "Primeiro acessou ou recuperar senha"
- clicar em "Continuar"
- inserir o e-mail
- inserir o token
- inserir nova senha 

_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Recuperar Senha](/imgs/login_1.png "Exemplo de E-mail novo usuário")


_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Recuperar Senha](/imgs/primeiro_acesso_recuperar_senha.png "Exemplo recuperar senha")


_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Recuperar Senha](/imgs/primeiro_acesso_recuperar_senha2.png "Exemplo recuperar senha")


<h3>Senha válida e Login</h3>

A senha deve seguir as seguintes características:
- Possuir no mínimo 6 e no máximo 20 caracteres;
- Possuir pelo menos uma letra e um número;
- Possuir pelo menos uma letra maíuscula e uma mínuscula;
- Possuir pelo menos um caracter especial ($ * & @ # ?);
- Não apresentar repetições (ex: Aabbcc, 1122).

![Login](/imgs/login_senha.gif "Login")


<h4>Segurança - Opcional Duplo Fator - Primeiro Acesso</h4>

Para empresas que desejam aumentar a segurança de login de seus usuários foi implementado o login com Duplo Fator onde por meio do aplicativo [Google Authenticator](https://support.google.com/accounts/answer/1066447?co=GENIE.Platform%3DAndroid&hl=pt-BR) é gerado um segundo token para login.

_Cadastro Usuário com Duplo Fator_
![Duplo Fator](/imgs/duplo_fator_3_2020-11-23_14h44_44.gif "Duplo Fator")

Após criado o cadastro do usuário com o campo "Autenticação de duplo fator" ativado, no primeiro acesso constará o código QR que será utilizado no Google Authenticator para liberação do token para login. Este código ficará liberado apenas no primeiro acesso, ou nas demais alterações na Edição do usuário. Os demais logins não constarão o código QR uma vez já cadastrado no aplicativo Google Authenticator.

_Primeiro Acesso Duplo Fator_
![Duplo Fator](/imgs/primeiro_acesso_duplo_fator.gif "Duplo Fator")

Para os logins posteriores ao primeiro acesso, apenas aparecerá o campo para ser inserido o código que o usuário terá pelo aplicativo em seu celular.

_Login Duplo Fator_
![Duplo Fator](/imgs/duplo_fator_1_2020-11-23_14h36_17.gif "Duplo Fator")


_Edição de Usuário com Duplo Fator_
![Duplo Fator](/imgs/duplo_fator_2_2020-11-23_14h38_16.gif "Duplo Fator")




<h4>Permissões</h4>

Para configurar as permissões do Usuário, ou seja, quais acessos o usuário terá para executar suas tarefas, veja quais são na tabela abaixo:

<table class="waffle no-grid" cellspacing="0" cellpadding="0">
	<thead style="background-color:#B0C4DE">
		<tr>
			<th id="0C1" style="width:233px" class="column-headers-background">PERMISSÃO</th>
			<th id="0C2" style="width:895px" class="column-headers-background">DETALHAMENTO</th>
		</tr>
	</thead>
	<tbody>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-empresas</td>
			<td class="s2" dir="ltr">acesso ao login na plataforma Omni</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-service</td>
			<td class="s2" dir="ltr">criar, excluir e editar serviços</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-usuário</td>
			<td class="s2" dir="ltr">criar, atualizar, atribuir produtos e serviços, ativar e desativar usuário</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-tag</td>
			<td class="s2" dir="ltr">criar, editar e excluir tags</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-phone</td>
			<td class="s2" dir="ltr">configurar novo número de telefone e ura atribuindo horários de atendimento, mensagens de boas vindas, serviços e mensagem de indisponibilidade de atendimento</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-contatos</td>
			<td class="s2" dir="ltr">Criar novo contato, atualizar e associar um contato a novos números</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-text</td>
			<td class="s2" dir="ltr">criação de shortcuts</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-relatorio</td>
			<td class="s2" dir="ltr">consultar e extrair relatórios gerenciais</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-produtos</td>
			<td class="s2" dir="ltr">criar, excluir e editar produtos</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-canais</td>
			<td class="s2" dir="ltr">Tela de solicitação de novas integrações</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-pa</td>
			<td class="s2" dir="ltr">Tela para agente - inabilita todos os demais acessos - exclusivo para atendimento de voz ou chat</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-call</td>
			<td class="s2" dir="ltr">libera o uso do softphone</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">tela-atendimento</td>
			<td class="s2" dir="ltr">Acesso ao usuário na fila de atendimento de voz e chat - tabulações e transferências - atualização de cadastro e associação</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-atendimento</td>
			<td class="s2" dir="ltr">Acesso a tela de Gerenciador de Atendimento</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-canais-email</td>
			<td class="s2" dir="ltr">Acesso ao cadastro de novo canal de e-mail em canais</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-canais-boteria</td>
			<td class="s2" dir="ltr">Acesso ao cadastro de novo canal de bot em boteria (webchat)</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-canais-whats</td>
			<td class="s2" dir="ltr">Acesso ao cadastro de novo canal de whatsapp</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-conectores</td>
			<td class="s2" dir="ltr">Acesso ao cadastro de conectores - formulários externos que a organização possa precisar</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-blacklist</td>
			<td class="s2" dir="ltr">Acesso ao cadatro de telefones na blacklist - inbound e outbound</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-api</td>
			<td class="s2" dir="ltr">Acesso aos cadastros de contatos ou busca de histórico via API para organizações que utilizam integração</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-pause</td>
			<td class="s2" dir="ltr">Acesso ao cadastro das Pausas</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-pesquisa</td>
			<td class="s2" dir="ltr">Acesso ao cadastro das Pesquisas para criação e edição</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">gerenciar-pesquisa-relatorio</td>
			<td class="s2" dir="ltr">Acesso ao dash de pesquisas e exportação do relatório analítico</td>
		</tr>		
	</tbody>
</table>







<h3>Serviços</h3>

Na tela principal de serviços estão disponibilizados os links para cadastro de um novo serviço onde será inserido:
- Nome
- nome do serviço a ser cadastrado
- Atendimento (%) - qual a porcentagem de atendimento desejada para o serviço
- Tempo Atendimento(s) - qual o tempo desejado para que seja inicializado o atendimento
- Tempo Abandono(s) - qual o tempo aceitável para que o atendimento tenha abandono
- Número de serviço interno - cadastro deverá ser com 3 dígitos e será utilizado para que o usuário transfira a ligação direto para o serviço solicitado
- Habilitar tela de Atendimento - se o serviço estará ou não habilitado para que seja atendido na Tela de Atendimento

_Tela de Serviços_

![Cadastro servicos](/imgs/Servicos_1.PNG "Tela Serviços")

_Edição de Usuários_

![Cadastro servicos](/imgs/Servicos_2.PNG "Edição Usuários")


_Tela de Cadastro de Serviços_

![Cadastro servicos](/imgs/Servicos_3.PNG "Edição Serviços")

_Tela de Cadastro do Número de serviço interno_
![Cadastro servicos](/imgs/servico_interno.gif "Edição Serviços")

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

<h3>Contatos</h3>
Os Contatos podem ser cadastrados individualmente ou por meio de importação de arquivo CSV, temos como único campo obrigatório o Nome do contato.

![Contatos](/imgs/Contatos_1.PNG "Tela Contatos")

O **Cadastro individual** é realizado ao clicar no **+** no canto superior esquerdo da tela onde terá acesso aos campos de Cadastro


_Acesso aos tipos de Cadastro_

![Contatos](/imgs/Contatos_4.PNG "Acesso aos Tipo de Cadastro")


_Tela Cadastro Individual_

![Contatos](/imgs/Contatos_2.PNG "Tela de Cadastro Individual")


Na tela de Cadastro Individual poderá ser inserido:
- uma Imagem/Avatar do contato
- alternado o tipo de cadastro se Corporativo ou Pessoa Física
- adicionado até 10 números de Telefones por contato
- adicionar campos Customizados - campos coringa - que poderão ser criados de acordo com a necessidade de cada organização


_Cadastro Campos Customizados_

![Contatos](/imgs/Contatos_5.PNG "Campos Customizados")


Para realizar o cadastro em massa, utiliza-se a importação de Arquivo CSV que é acessado no canto superior direito da tela demonstrado na imagem _Acesso aos tipos de Cadastro_
na tela de Importação com arquivo CSV está disponibilizado um modelo do arquivo com os campos e formatos para que ocorra a importação.


_Tela Importação CSV_

![Contatos](/imgs/Contatos_CSV.PNG "Importação CSV")

Notar que:
- os campos são separados por ponto e vírgula (;)
- apenas o campo nome é obrigatório
- o campo "contact_gender" aceita apenas Masculino / Feminino / Não Informado ou poderá ser deixado em branco
- o cadastro do número do telefone deverá ser feito com DDI + DDD + NÚMERO DO TELEFONE
- há uma particularidade para cadastro dos campos customizados
    - todos campos criados customizados deverão ficar entre  chaves []    
    - entre aspas duplas deverão ficar o Nome do Campo seguido de vírgula e o valor do campo também entre aspas duplas
    - cada campo customizado deverá ser separado por pipe |
    
    Como no exemplo abaixo:
    
    ["Faturamento","20.000"|"Advogado","Dr. Augusto Martins"|"Secretária","Gabriela Santos"]


<h3>Blacklist</h3>
O cadastro do blacklist, ou seja, os telefones que ficarão bloqueados para contatos, é realizado para Inbound e Outbound separadamente.

_Tela de Blacklist_

![Blacklist](/imgs/Blacklist_00.PNG "Tela dos Canais")

O cadastro dos telefones para Blacklist pode ser realizado individualmente ou por importação de CSV, em ambos os casos, o formato do telefone importado deverá ser
realizado de acordo com as regras:

- Inbound
	- DDD + número do telefone
- outbound
	- DDI + DDD + número do telefone
	

_Tela de Importação individual Outbound_

![Blacklist](/imgs/Black_outbound.PNG "Cadastro Blacklist Outbound")


- Registrar o número do Telefone e clicar em Salvar


_Tela de Importação individual Inbound_

![Blacklist](/imgs/Black_inbound.PNG "Cadastro Blacklist intbound")


_Tela de Importação individual Inbound lista flow_

![Blacklist](/imgs/Black_inbound_2.PNG "Lista URA para Bloqueio")


- Selecionar a URA
- Registrar o número do Telefone e clicar em Salvar

Para importação de telefones por arquivo CSV, o modelo do documento está disponível para download na tela de importação


_Tela de Importação CSV Inbound_

![Blacklist](/imgs/Blacklist_csv_inbound.PNG "Modelo CSV Inbound")

Note que para importação do arquivo CSV Inbound, ligações receptivas, o campo "blacklist_type" sempre terá o valor de 1



_Tela de Importação CSV Outbound_

![Blacklist](/imgs/Blacklist_csv_outbound.PNG "Modelo CSV Outbound")

![Blacklist](/imgs/Black_outbound2.PNG "Modelo CSV Outbound")


Note que para importação do arquivo CSV Outbound, ligações receptivas, o campo "blacklist_type" sempre terá o valor de 2



<h3>Shortcuts</h3>

Shortcuts são os atalhos que podem ser criados para otimizar o atendimento, estão linkados aos serviços, ou seja, cada shortcut criada deve ser relacionada a um serviço. Assim, quando o usuário estiver em atendimento, poderá utilizar o atalho que trará frases prontas de um determinado assunto. Sendo útil na padronização do atendimento e também para otimizar o tempo do usuário/atendente.

_Tela de Shortcuts_

![Shortcuts](/imgs/short_1.PNG "Tela Shortcuts")

O **cadastro** de shortcuts é bem simples, basta clicar no "+" no canto inferior direito da tela principal de Shortcuts e liberará uma nova linha para cadastro, após a liberação inserir:
- prefixo - atalho que será utilizado pelo agente para buscar o texto
- Texto - a frase que será utilizada
- Serviço - abrirá a lista de serviços cadastrados na Organização para que seja selecionado qual receberá a Shortcut que está sendo cadastrada

Após preenchimento, clicar no ícone de salvar (símbolo de um disquete). 
Para editar um texto já criado, basta ir no campo Texto, fazer as alterações necessárias e clicar em salvar.

_Cadastro de nova Shortcuts_

![Shortcuts](/imgs/short_3.PNG "Cadastro de nova Shortcuts")

A utilização das shortcuts já cadastradas é realizada na Tela de Atendimento pelo usuário clicando "/" (barra), assim a lista de atalhos disponibilizados para o Serviço em que está em atendimento será liberada para que o atendente utilize em seu atendimento.

_Tela de Atendimento - utilização de Shortcuts_

![Shortcuts](/imgs/short_2.PNG "Tela de Atendimento - Shortcuts")

A exclusão de Shortcuts poderá ser realizada clicando no ícone da "lixeira", então ficará liberado outro ícone de exclusão após clicar ali, seu shortcuts será excluído e não haverá possibilidade de resgatá-lo a não ser recriando-o novamente.

_Exclusão de Shortcuts_

![Shortcuts](/imgs/short_4.PNG "Exclusão de Shortcuts")


<h3>Pausas</h3>

Utilizadas para identificar as paradas dos usuários, o cadastro das Pausas auxilia na gestão da Equipe para mensurar inclusive como indicar de produtividade, pois constará a informação em relatórios de gestão.

_Tela Pausa_

![Pausa](/imgs/Pausa_1.PNG "Tela de Pausas")

Seu cadastro é simples, basta clicar no "+" no canto inferior da tela e cadastrar no campo "Motivo da Pausa", 

_Cadastro de Pausa_

![Pausa](/imgs/Pausa_2.PNG "Cadastro de Pausas")

A exclusão é realizada clicando no ícone da "lixeira" 

_Exclusão de Pausa_

![Pausa](/imgs/Pausa_3.PNG "Exclusão de Pausas")

O usuário, quando for entrar em pausa, encontrará a listagem para optar pelo motivo da Pausa que está realizando

_Utilização de Pausa_

![Pausa](/imgs/Pausa_4.PNG "Utilização de Pausas")


_Utilização de Pausa - Tela Visão do Agente_

![Pausa](/imgs/Pausa_5.PNG "Utilização de Pausas - Visão do Agente")

_Utilização de Pausa_

![Pausa](/imgs/2020-10-08_15h31_15.gif "Utilização de Pausas")





## Pesquisa de Satisfação

# NPS
O Net Promoter Score (NPS) é uma métrica de lealdade do cliente, com o objetivo de medir o grau de lealdade dos clientes das empresas de qualquer segmento, trazendo reflexos da experiência e satisfação dos clientes. Perguntas adicionais podem ser incluídas para ajudar a compreender a percepção de vários produtos, serviços e linhas de negócios. Estas perguntas adicionais ajudam a empresa a avaliar a importância relativa dessas outras partes do negócio na pontuação geral. Isto é especialmente útil para orientar os recursos e resolver questões que mais impactam o NPS.

O Net Promoter Score tem como proposta inovar a cultura das pesquisas de pós-venda para que elas consigam ter uma visão real dos serviços prestados pela empresa e consequentemente ajudá-la a evoluir e conquistar um patamar de solidez e excelência no mercado. O NPS se garante como importante peça na expansão dos negócios e aumento do retorno de investimento.

# CSAT
A sigla CSAT remete à Customer Satisfaction Score. Como o próprio nome em inglês já indica, é uma Escala de Satisfação do Cliente. Esse tipo de pesquisa é utilizado para avaliar a imagem que o consumidor tem da marca e leva em conta pontos de interação, como:
- Atendimento antes, durante e depois da compra;
- Logística de entrega;
- Produto ou serviço;
- Agilidade na resolução de problemas;
- Todo o processo de vendas.
O CSAT é uma pesquisa de curto prazo, geralmente aplicada por meio de perguntas do tipo: “como você classificaria sua experiência com a marca?”. Pode conter questões sobre cada um dos pontos que mencionamos acima, além de um espaço para comentários adicionais ou até para justificar a avaliação.

A Criação da Pesquisa de Satisfação na plataforma é realizada de forma rápida, objetiva e simples onde o gestor da Organização poderá inserir as perguntas e a variável da pontuação que desejar para cada pergunta. 


![Pesquisa](/imgs/Pesquisa_1.PNG "Tela Pesquisa")


<h3>Criando Pesquisa</h3>


![Criando Pesquisa](/imgs/Pesquisa_2.PNG "Tela Pesquisa")

 - clique na engrenagem no menu lateral
 - pesquisa
 - clique no símbolo de "+" no canto inferior direito da tela - abrirá uma nova tela "Configurar Pesquisa"
 - selecione o campo 'Mídia' - poderá optar por Voice, Whatsapp, Chat ou E-mail
 - selecione o 'Tipo de pesquisa' - CSAT ou NPS
 - preencha o campo 'Título" com o nome que desejar para Pesquisa
 - selecione o Serviço - clique no '+' para ficar gravado a URA escolhida
 - para mídia de Voz selecione o campo URA - clique no '+' para ficar gravado a URA escolhida
 - cadastre a mensagem de boas vindas
 - para pesquisas de mídia Email aparecerá o campo *Assunto Email* para ser preenchido e em seguida o espaço para que seja escrito o Corpo do email que será enviado para pesquisa.
 - para pesquisas de mídia Voice, abaixo da Mensagem de Boas Vindas, deverá ser selecionado a voz de reprodução - clique no símbolo de atualizar para ficar registrado a voz de reprodução que será utilizada
 - cadastre o Alias da primeira pergunta - será um título que tenha referência ao tipo de pergunta, por exemplo: Atendimento / Informação / Negociação
 - cadastre a pergunta
 - selecione a voz de reprodução, para o cadastro de Pesquisa de voz - clique no símbolo de atualizar para ficar registrado a voz de reprodução que será utilizada para a Pergunta
 - selecione o range de avaliação - será de acordo com a pergunta realizada
 	- para inserir mais perguntas, basta clicar no '+' que será liberado novos campos com Alias, Mensagem, Voz de Reprodução e Range de avaliação.
 - cadastre a mensagem de encerramento
 - selecione a voz de reprodução - clique no símbolo de atualizar para ficar registrado a voz de reprodução que será utilizada para a Mensagem de Encerramento 
 - ative a pesquisa 
 - salve  

_Demonstração de criação de Pesquisa Voz_
![Criando Pesquisa](/imgs/cria_pesquisa.gif "Criação de Pesquisa")


_Demonstração de criação de Pesquisa Whatsapp e Chat_
![Criando Pesquisa](/imgs/cria_pesquisa_chat.gif "Criação de Pesquisa")


<h3>Criando Pesquisa Email</h3>

Para criação de Pesquisa de E-mail deve-se notar que, ao ser finalizado o atendimento por email na plataforma, o cliente receberá um e-mail automático de acordo com a  configuração realizada que contém um link que o levará para uma página onde responderá a Pesquisa.
Atenção no preenchimentos dos campos:
1. Assunto Email - trata-se do título que será enviado o e-mail para o cliente
2. Corpo do Email - espaço para ser escrito o texto que estará no corpo do email que será enviado para o cliente
3. Adicionar Link - para que o email seja enviado com o link que abrirá a página com as perguntas, deve ser adicionado o link clicando no botão verde "Adicionar Link"
A partir daí o fluxo de cadastro das perguntas seguem da mesma forma que as demais mídias.


_Demonstração de criação de Pesquisa Email_
![Criando Pesquisa Email](/imgs/cria_pesquisa_email.gif "Criação de Pesquisa Email")




<h3>Monitoração de Pesquisa</h3>

Por meio do dash de pesquisas será possível monitorar em tempo real ou retroativo os resultados obtidos das pesquisas, por meio dos filtros pode-se delimitar os dados de acordo com a necessidade de pesquisa.

- Defina qual Pesquisa deseja monitorar, a tela trará os demais filtros que são:
	- Mídia
	- Canal
	- Serviço
	- Data
	- Alias - título da pergunta criada na Pesquisa
Após as seleções dos filtros, clique em 'Gerar"	

A tabela a seguir traz explicação dos gráficos que o dash trará

<table class="waffle no-grid" cellspacing="0" cellpadding="0">
	<thead style="background-color:#B0C4DE">
		<tr>
			<th id="0C1" style="width:233px" class="column-headers-background">GRÁFICO</th>
			<th id="0C2" style="width:895px" class="column-headers-background">DETALHAMENTO</th>
		</tr>
	</thead>
	<tbody>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">Customer Satisfaction - CS</td>
			<td class="s2" dir="ltr">Porcentagem de notas por pergunta</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">Média Ponderada</td>
			<td class="s2" dir="ltr">Calculada média ponderada soma de todas as ocorrências e dividindo pelo número de respondentes onde o peso é o número de ocorrências de cada pergunta</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">Cálculo Simples</td>
			<td class="s2" dir="ltr">Utilizada para perguntas que sejam mensuradas nos valores 1, 2 e 3 - só é preenchido quando for perguntas diretas Ex.: Indicaria nossos serviços 1 para não 2 para sim</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">Satisfação por Pergunta</td>
			<td class="s2" dir="ltr">média das notas por Alias</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">Satisfação por Serviço</td>
			<td class="s2" dir="ltr">média das notas por serviço</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">CS acumulado anual</td>
			<td class="s2" dir="ltr">média das notas mostrando o acumulado anual</td>
		</tr>
		<tr style="height:20px;">
			<td class="s1" dir="ltr">Performance por Agente</td>
			<td class="s2" dir="ltr">média das notas por agente</td>
		</tr>				
	</tbody>
</table>





_Demonstração de monitoração de Pesquisa_
![Dash Pesquisa](/imgs/dash_pesquisa.gif "Monitoração de Pesquisa")


<h3>Relatório de Pesquisa</h3>

Para os usuários que tem a permissão de gerar relatórios de Pesquisa, basta seguir o caminho:
 - Exportações
 - Novo Relatório
 - Pesquisa de Satisfação - Relatório Analítico
 - Defina qual Pesquisa deseja que seja gerado o relatório, a tela trará os demais filtros que são:
	- Mídia
	- Canal
	- Serviço
	- Alias - título da pergunta criada na Pesquisa
	- Data
	
Após as seleções dos filtros, clique em 'Processar"

![Relatório Pesquisa](/imgs/Pesquisa_5.PNG "Tela Relatório Analítico Pesquisa")

_Demonstração de extração de Relatório de Pesquisa_
![Relatório Pesquisa](/imgs/relatorio_pesquisa.gif "Relatório Analítico Pesquisa")

 **A tabela a seguir traz a informação dos dados encontrados no Relatório Analítico de Pesquisa**

<table class="waffle no-grid" cellspacing="0" cellpadding="0">
	<thead style="background-color:#B0C4DE">
		<tr>
			<th id="0C2" style="width:330px" class="column-headers-background">CAMPO</th>
			<th id="0C3" style="width:363px" class="column-headers-background">DESCRIÇÃO</th>
			<th id="0C4" style="width:282px" class="column-headers-background">FORMATO</th>			
		</tr> 
	</thead>
	<tbody>
			<tr style="height:20px;">
			<td class="s2" dir="ltr">DATA</td>
			<td class="s3" dir="ltr">Data do Contato</td>
			<td class="s4" dir="ltr">dd/mm/aaaa hh&#58;mm&#58;ss&#58</td>
		</tr>
			<tr style="height:20px;">
			<td class="s2" dir="ltr">NOME_PESQUISA</td>
			<td class="s3" dir="ltr">Nome criado para Pesquisa</td>
			<td class="s4" dir="ltr">Texto</td>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">MIDIA</td>
			<td class="s3" dir="ltr">Nome da Mídia selecionada</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">CANAL</td>
			<td class="s3" dir="ltr">Nome do Canal Selecionado</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">SERVIÇO</td>
			<td class="s3" dir="ltr">Nome do serviço selecionado</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">AGENTE</td>
			<td class="s3" dir="ltr">Nome do usuário que recebeu a chamada</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">NUMERO_CONTATO</td>
			<td class="s3" dir="ltr">Número do telefone do contato</td>
			<td class="s4" dir="ltr">Numérico</td>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">NOME_CONTATO</td>
			<td class="s3" dir="ltr">Nome do Contato</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">PROTOCOL</td>
			<td class="s3" dir="ltr">Número identificador da chamada</td>
			<td class="s4" dir="ltr">Numérico</td>
		</tr>
	</tbody>
</table>

As últimas colunas do relatório terão como título o nome da Alias(título das perguntas) criada na pesquisa com os seus resultados como no exemplo abaixo.

![Relatório Pesquisa](/imgs/Pesquisa_6.PNG "Tela Relatório Analítico Pesquisa")


## Canais

Em Canais são realizados os cadastros de todas as mídias que a empresa terá para atendimento, voz, whatsapp, webchat, e-mail e mercado livre.

_Tela de Canais_

![Canais](/imgs/Canais_1.PNG "Tela Blacklist")

### Telefone

O Cadastro e Configuração do telefone para atendimento é realizado de forma prática e bem intuitiva
Na tela principal, clique no **+** para cadastrar o telefone, preenchendo os campos:
- Escolha o pais de origem,
- Escolha o código de área - estarão as opções do número de telefone que poderá utilizar pra seu atendimento,
- Escolha um nome,

_Tela de cadastro e gerenciamento da rota da ligação, onde é realizado a configuração da fila de atendimento_
![Canais Telefone](/imgs/Telefone_10.PNG "Tela Cadastro Telefone")

_Tela de definição do telefone_
![Canais Telefone](/imgs/Telefone_11.PNG "Escolha o número do Telefone")

Após definição do telefone que ficará disponibilizado para receber as ligações, deve-se configurar a fila de atendimento por serviço:
- Horário de Atendimento - seleção do dia da semana e horários inicial e final do atendimento
- Mensagem de Boas Vindas
- Mensagem com Atendimento Fechado
- Serviços que farão parte do atendimento
- Mensagem para ligações não atendidas

<h4>Horário de Atendimento</h4>

A configuração dos horários de atendimento poderão ser com Atendimento sempre aberto (24x7) ou poderá ser Configurado os horários por dia da semana de acordo com a necessidade da organização, neste caso, você optará pelo fuso horário e poderá inserir o dia da semana e quais os horários iniciais e finais de cada dia.

_Configuração dos Horários de Atendimento_
![Canais Telefone](/imgs/Telefone_3.PNG "Configuração dos Horários")

<h4>Mensagem de Boas Vindas</h4>

Conhecida também como mensagem de saudação, que será enviada assim que o contato for atendido pela URA. Poderá ser cadastrada internamente na plataforma, onde o Texto é escrito, transformado em áudio pelo robô e definido qual voz será utilizada na gravação ou a organização poderá importar um arquivo próprio de áudio .mp3 ou .wav.

_Configuração Mensagem de Boas Vindas_
![Canais Telefone](/imgs/Telefone_4.PNG "Configuração Mensagem de Boas Vindas")

<h4>Mensagem com Atendimento Fechado</h4>

Utilizada quando o contato realiza uma ligação para a URA fora do seu horário de atendimento, então é realizada uma gravação para informar que não estão atendendo no momento. Poderá ser cadastrada internamente na plataforma, onde o Texto é escrito, transformado em áudio pelo robô e definido qual voz será utilizada na gravação ou a organização poderá importar um arquivo próprio de áudio .mp3 ou .wav.

_Configuração Mensagem de Atendimento Fechado_
![Canais Telefone](/imgs/Telefone_5.PNG "Configuração Mensagem de Atendimento Fechado")

<h4>Cadastro dos Serviços</h4>

A escolha dos Serviços que serão atendidos pela URA deverá ser realizada a critério da organização, de forma que melhor lhe atenda. Clicando no ícone de editar do Menu de Atendimento poderá ser escolhido qual serviço será escolhido e em qual ordem de discagem na URA ele ficará.

<h4>Mensagem para ligações não atendidas</h4>

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

## Broadcast
A funcionalidade da plataforma Code7 Omni traz agilidade e facilidade na criação e gerenciamento de Campanhas onde se pode criar o grupo de contatos, campanhas e estratégia de envios com monitoramento para envio de mensagens de whatsapp e SMS em massa.

São pré-requisitos para o envio de *Whatsapp*:
- Número de telefone cadastrado no Canal de Whatsapp
- Aprovação dos HSM dentro das normas geradas pelo Facebook para que as mensagens possam ser enviadas.

São pré-requisitos para o envio de *SMS*:
- Liberação de um Serviço de Entrada que será realizado por meio de chamado para que seja criado uma integração para envio.

    
### Criação - Grupos de Contatos
A criação de grupo de contatos poderá ser realizada de duas formas:
- Por meio de importação de um arquivo tipo CSV
- Por meio da importação de todos os contatos já cadastrados em sua empresa


_Grupo de Contatos_

![Tela Grupo de Contatos](/imgs/grupo_contatos_1.PNG "Tela Grupo de Contatos") 

Na Tela do Grupo de Contatos, pode ser realizada Ações em Lote para Ativar ou Inativar Grupos além de Editar(ícone do lápis) ou Verificar(ícone da lupa) cada grupo já criado.


_Editar Grupo de Contatos_


![Tela Grupo de Contatos](/imgs/grupo_contatos_editar.PNG "Tela Grupo de Contatos") 


_Verificar Grupo de Contatos_


![Tela Grupo de Contatos](/imgs/grupo_contatos_verificar.PNG "Tela Grupo de Contatos") 

  
**Tela de Importação de Grupo de Contatos**
- Inserir Nome do Grupo de Contatos
- Optar ou por "Utilizar contatos Omni" ou "Fazer upload de arquivo"
- Salvar


_Criação de Grupo de Contatos_


![Tela Grupo de Contatos](/imgs/grupo_contatos_2.PNG "Tela Grupo de Contatos") 



### Criação de Campanha

A criação de grupo de Campanhas será realizada na tela de Campanha clicando no ícone de "+" no canto superior direito da tela que levará a tela de Configurar Campanha

![Configurar Campanha](/imgs/campanha_nova.PNG "Configurar Campanha") 

Na tela Configurar Campanha deverão ser preenchidos os campos:
- Campanha - com o nome da Campanha que será criada
- Canal - onde será definido se a campanha será de Whatsapp ou SMS

![Configurar Campanha](/imgs/config_campanha_1.PNG "Configurar Campanha") 



* Note que a campanha já estará ativa como default no checkbox, após o preenchimento dos campos, clique em salvar.


_Para Campanha de Whatsapp_


![Configurar Campanha](/imgs/config_campanha_whats.PNG "Configurar Campanha") 



_Para Campanha de SMS_


![Configurar Campanha](/imgs/config_campanha_SMS.PNG "Configurar Campanha") 


### Criação de Envios

A criação de grupo dos Envios será realizada na tela de Envios clicando no ícone de "+" no canto superior direito da tela que levará a tela de Configurar Envio onde deverão ser preenchidos os campos:
- Nome do agendamento
- Agendamento - informando a Data que deverá ser realizado o envio da mensagem
- Horário - informando o horário desejado para que seja enviada mensagem
- Grupos de Contatos - selecionando na lista disponível o Grupo de Contatos, criado previamente, que será utilizado para a Campanha
- Campanha - selecionando na lista dispoínvel a Campanha criada previamente para o envio, esta campanha será de Whatsapp ou de SMS


#### Mensagem de Envio - para Campanhas de Whatsapp

Nas Campanhas de Whatsapp a mensagem HSM - High Structured Message. As mensagens deste tipo obedecem a uma estrutura rígida pré-aprovada pelo WhatsApp para as notificações automatizadas que você será autorizado a enviar aos usuários.
Deverá ser selecionado a HSM previamente liberada no sistema e definido quais variáveis serão utilizadas nos espaços já definidos no corpo do HSM.


_Para Envio de Whatsapp_


![Configurar Envio](/imgs/config_envio_whats.PNG "Configurar Envio para Campanha de Whatsapp") 



_Para Envio de Whatsapp_


![Configurar Envio](/imgs/config_envio_whats2.PNG "Configurar Envio para Campanha de Whatsapp") 




#### Mensagem de Envio - para Campanhas de SMS

Para Campanhas geradas de SMS não há restrição do texto a ser enviado e nem do posicionamento das variáveis que serão inseridas no texto clicando no "+" que fica no canto esquerdo ao lado do "Valor Variável".



_Para Envio de SMS_


![Configurar Envio](/imgs/config_envio_SMS.PNG "Configurar Envio para Campanha de SMS") 


_Para Envio de SMS_


![Configurar Envio](/imgs/config_envio_SMS_2.PNG "Configurar Envio para Campanha de SMS") 



### Monitoramento

Na tela de Monitoramento será apontado os resultados das Campanhas de Whatsapp ou de SMS onde poderá filtrar por:
- Data
- Canal - atualmente por Whatsapp ou SMS
- Campanha - campo obrigatório para que sejam alimentados as informações no Dash

_Monitoramento_


![Monitoramento](/imgs/monitoramento_sms_1.PNG "Monitoramento de Campanhas") 



_Monitoramento_


![Monitoramento](/imgs/monitoramento_sms_2.PNG "Monitoramento de Campanhas") 



## Relatórios


### Rastreio de Interações

Relatório que traz a visão de cada atendimento realizado na plataforma com as informações de Data/Hora, qual tipo de mídia, qual usuário,tempo de atendimento e qual foi a finalização do atendimento realizado - por meio da TAG.

_Tela Rastreio Interações_

 ![Rastreio de Interações](/imgs/Rastreio_1.PNG "Filtros para Rastreio")
 
 Para extração do Relatório o campo obrigátorio é o "Mídia" os demais campos são opcionais.
 
 _Tela Filtros de Mídia_
 
 ![Rastreio de Interações](/imgs/Rastreio_2.PNG "Filtros de Mídia")
 
 Há opção de filtros por Data, usuário, horário, Protocolo, Serviços e demais campos
 
 _Exemplo de outros Filtros_
 
 ![Rastreio de Interações](/imgs/Rastreio_3.PNG "Filtros de Usuários")
 
 ![Rastreio de Interações](/imgs/Rastreio_4.PNG "Filtros de Data")
 
 A visualização da extração poderá ser feita diretamente na tela do sistema, ou também poderá ser realizado download em CSV para facilitar a análise das informações.
 
  _Tabela de Resultados_
  
 ![Rastreio de Interações](/imgs/Rastreio_5.PNG "Tabela ou Download por CSV")
 
 
 
 **A tabela a seguir traz a informação dos dados encontrados no Relatório Rastreio de Interações**
 

<table class="waffle no-grid" cellspacing="0" cellpadding="0">
	<thead style="background-color:#B0C4DE">
		<tr>
			<th id="0C2" style="width:330px" class="column-headers-background">CAMPO</th>
			<th id="0C3" style="width:363px" class="column-headers-background">DESCRIÇÃO</th>
			<th id="0C4" style="width:282px" class="column-headers-background">FORMATO</th>
			<th id="0C5" style="width:373px" class="column-headers-background">CÁLCULO</th>
		</tr> 
	</thead>
	<tbody>
			<tr style="height:20px;">
			<td class="s2" dir="ltr">DATA</td>
			<td class="s3" dir="ltr">Data do Contato</td>
			<td class="s4" dir="ltr">aaaa-mm-dd</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">HORA</td>
			<td class="s3" dir="ltr">Hora do Contato</td>
			<td class="s4" dir="ltr">hh&#58;mm&#58;ss&#58;ms</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">PROTOCOLO</td>
			<td class="s3" dir="ltr">Número do protocolo de atendimento</td>
			<td class="s4" dir="ltr">Número Inteiro</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">SERVIÇOS</td>
			<td class="s3" dir="ltr">Nome do Serviço em que foi realizado o Atendimento</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">AGENTE</td>
			<td class="s3" dir="ltr">Nome do usuário</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">ORIGEM</td>
			<td class="s3" dir="ltr">Integração utilizada para realizar o atendimento (ex: Portal, Zendesk, Salesforce)</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">TIPO (apenas para voz)</td>
			<td class="s3" dir="ltr">Outbound / Inbound</td>
			<td class="s4" dir="ltr">Texto</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">PARA (apenas para voz)</td>
			<td class="s3" dir="ltr">Número/Ramal que recebeu o contato</td>
			<td class="s4" dir="ltr">Numérico</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">CONTATO</td>
			<td class="s3" dir="ltr">Nome do Contato - apenas após tabulação do atendimento estará disponível no relatório</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">A PARTIR DE</td>
			<td class="s3" dir="ltr">Número/Ramal que realizou o contato</td>
			<td class="s4" dir="ltr">Numérico</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">DURAÇÃO</td>
			<td class="s3" dir="ltr">Tempo de atendimento</td>
			<td class="s4" dir="ltr">hh&#58;mm&#58;ss</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">STATUS</td>
			<td class="s3" dir="ltr">Resultado da chamada - Abandoned/Bad Phone/ Bad Number / Dequeued</td>
			<td class="s4" dir="ltr">Texto</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">Tag</td>
			<td class="s3" dir="ltr">Tabulação</td>
			<td class="s4" dir="ltr">Alfanumérico</td>
			<td class="s3"/>
		</tr>
		<tr style="height:20px;">
			<td class="s2" dir="ltr">JITTER (apenas para voz)</td>
			<td class="s3" dir="ltr">Atraso entre pacotes, quanto menor o seu valor melhor a qualidade da chamada.</td>
			<td class="s4" dir="ltr">Unidade em Milissegundos (MS)</td>
			<td class="s3" dir="ltr">Alta se for &lt; 70<br>Media se for &gt;= 71 e &lt;= 150<br>Baixa se for &gt;= 151</td>
				</tr>
				<tr style="height:20px;">
					<td class="s2" dir="ltr">PERDA DE PACOTE (apenas para voz)</td>
					<td class="s3" dir="ltr">Indica se há falta de qualidade na conexão, na perda de pacotes quanto menor o valor melhor a sua qualidade da chamada.</td>
					<td class="s4" dir="ltr">%</td>
					<td class="s3" dir="ltr">Alta se for &lt;= 1%<br>Media se for &gt;= 1% e &lt;= 5%<br>Baixa se for &gt; 5%</td>
						</tr>
						<tr style="height:20px;">
							<td class="s2" dir="ltr">QUALIDADE DE CHAMADA (apenas para voz)</td>
							<td class="s3" dir="ltr">Traz a informação do nível de qualidade da chamda realizada</td>
							<td class="s4"/>
							<td class="s3"/>
						</tr>
						<tr style="height:20px;">
							<td class="s2" dir="ltr">Histórico</td>
							<td class="s3" dir="ltr">Link para visualização do histórico do atendimento realizado</td>
							<td class="s4" dir="ltr">Texto </td>
							<td class="s3" dir="ltr">
								<span style="font-weight:bold;">Alta: </span>
								<br>    - Jitter menor que 70 + Perda de pacotes menor que 1%<br>
										<span style="font-weight:bold;">Média: </span>
										<br>    - Jitter entre 71 e 150 e Perda de pacotes menor que 1%<br>    - Jitter menor que 70 e Perda de pacotes entre 1% e 5%<br>
													<span style="font-weight:bold;">Baixo: </span>
													<br>    - Jitter maior ou igual a 151<br>    - Perda de pacotes maior que 5%<br>    - Jitter entre 71 e 150 e Perda de pacotes entre 1% e 5%</td>
														</tr>
														<tr style="height:20px;">
															<td class="s2" dir="ltr">Status - Abandoned</td>
															<td class="s3" dir="ltr">Desistência do cliente enquanto aguarda na fila</td>
															<td class="s4" dir="ltr">Texto</td>
															<td class="s3"/>
														</tr>
														<tr style="height:20px;">
															<td class="s2" dir="ltr">Status - Bad Phone</td>
															<td class="s3" dir="ltr">Numero indisponivel naquele momento (Ocupado ou não atende)</td>
															<td class="s4" dir="ltr">Texto</td>
															<td class="s3"/>
														</tr>
														<tr style="height:20px;">
															<td class="s2" dir="ltr">Status - Bad Number</td>
															<td class="s3" dir="ltr">Numero inexistente ou com erro</td>
															<td class="s4" dir="ltr">Texto</td>
															<td class="s3"/>
														</tr>
														<tr style="height:20px;">
															<td class="s2" dir="ltr">Status - Dequeued</td>
															<td class="s3" dir="ltr">Desenfileirado, atingiu o tempo limite de espera na fila até ser atendido.</td>
															<td class="s4" dir="ltr">Texto</td>
															<td class="s3"/>
														</tr>
														<tr style="height:20px;">
															<td class="s2" dir="ltr">Status - Service Completed</td>
															<td class="s3" dir="ltr">Atendimento finalizado e tabulado - Atendimento por chat</td>
															<td class="s4" dir="ltr">Texto</td>
															<td class="s3"/>
														</tr>
														<tr style="height:20px;">
															<td class="s2" dir="ltr">Status - Service Transfered</td>
															<td class="s3" dir="ltr">Atendimento transferido - Atendimento por chat</td>
															<td class="s4" dir="ltr">Texto</td>
															<td class="s3"/>
														</tr>
													</tbody>
												</table>




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


