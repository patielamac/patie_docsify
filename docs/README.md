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
DDI+DDD+NÚMERO DO TELEFONE

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

Note que para importação do arquivo CSV Outbound, ligações receptivas, o campo "blacklist_type" sempre terá o valor de 2




<h3>Shortcuts</h3>

<h3>Pausas</h3>

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
## Relatórios


### Rastreio de Interações

Relatório que traz a visão

<table class="waffle no-grid" cellspacing="0" cellpadding="0">
	
		<!-- <tr>
			<th class="row-header freezebar-origin-ltr"/>
			<th id="0C0" style="width:330px" class="column-headers-background">A</th>
			<th id="0C1" style="width:363px" class="column-headers-background">B</th>
			<th id="0C2" style="width:282px" class="column-headers-background">C</th>
			<th id="0C3" style="width:373px" class="column-headers-background">D</th>
		</tr> -->
	
	<thead>
		<tr style="height:30px;">
			<td class="s0" dir="ltr" bgcolor="#7B68EE">Campo</td>
			<td class="s1" dir="ltr">Descrição</td>
			<td class="s0" dir="ltr">Formato</td>
			<td class="s1" dir="ltr">Cálculo</td>
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
			<td class="s4" dir="ltr">hh:mm:ss:ms</td>
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
			<td class="s4" dir="ltr">hh:mm:ss</td>
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


