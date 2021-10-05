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

![Code7 Omni](/imgs/Apresenta.PNG ':class=sombracaixa' )

<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Monitoração

O Módulo de monitoramento do Code7 Omni traz de forma prática o acompanhamento e gestão dos atendimentos em tempo real.

![Monitoração](/imgs/monitoracao1.PNG ':class=sombracaixa' )

## Atendimento


O monitoramento na tela de Atendimento é realizado com o acompanhamento dos atendimentos de todas as mídias de texto, trazendo os atendimentos que estão:

![Atendimento Filtros](/imgs/atendimento1.PNG ':class=sombracaixa' )

- **Na fila** - trata-se de atendimentos que ainda não foram direcionados para um usuário iniciar o atendimento, está aguardando distribuição.

- **Em antendimento** - traz todos os atendimentos que estão sendo realizados, ou seja, ainda em andamento. Apresentam-se em duas visões, por cards de usuário ou na fila de atendimento por ordem de chegada.

**Atendimento**
![Atendimento 4.XX](/imgs/atendimento_new1.gif ':class=sombracaixa' )

- **Agendamentos** - traz a listagem dos atendimentos que foram programados um agendamento, para mídias que há agendamento disponibilizado.

![Rastreio de Interações](/imgs/agendamento1.png ':class=sombracaixa' )


## Agentes

A tela de Visão dos Agentes traz as informações de status e login dos usuários de acordo com os logins do softphone, exclusivamente. Empresas que não possuem atendimento de voz não terão visão nesta tela.

**Visão do Agente **

![Agentes 4.xx](/imgs/visao_agente_v4.PNG ':class=sombracaixa' )

Apresenta os campos:
- Disponível - são os agentes/usuários que se encontrarm liberados para receber novos atendimentos, são dispostos em fila de acordo com o tempo em que estão ociosos.
- Em chamada - são os agentes/usuários que estão em atendimento
- Em pausa - são os agentes/usuários que estão em pausa
- Offline - são os agentes/usuários que se encontram descontectados do sistema

A Tela dipõe de filtros para facilitar a visão do gestor onde poderá buscar por serviço, agente ou tag do usuário.

<h3>Monitoramento de Ligações</h3>

Durante a chamada, o gestor poderá auxiliar o agente/usuário ou monitorá-lo para futuros feedbacks, veja na imagem abaixo a descrição das ações

**Botões de ações**

![Botoes 4.xx](/imgs/visao_agente_botoes.PNG ':class=sombracaixa' )

<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Dashboards
Um dashboard é um painel visual que apresenta, de maneira centralizada, um conjunto informações: indicadores e suas métricas. Sendo um recurso que auxilia na tomada de decisões. Dashboards podem apresentar a saúde da empresa em uma única tela para o gestor ou compartilhados com toda a sua equipe. Dessa maneira, por meio do dashboard, o gestor terá uma noção global dos processos do seu negócio, podendo visualizar também, de forma dinâmica e objetiva, dados referentes a projetos específicos e campanhas.

## Inbound
Este Dashboard traz informações sobre as chamadas recebidas pela operação (inbound), como: métricas de tempo de atendimento; quantitativo de chamadas recebidas, atendidas e abandonadas; gráficos para acompanhamento e análise das chamadas, entre outras. 

Na sua parte superior, há algumas opções de filtros e visões de dados 

**Filtros:**
 - **Serviço:** combo para filtrar os dados por serviço (fila).Ao selecionar a opção "Serviço", serão exibidos dados de todas as filas da operação.
 - **Agente:** combo para filtrar os dados por usuário (agente). Ao selecionar a opção "Usuário", serão exibidos dados de todos os agentes da operação ou da fila escolhida.
 - **Tag de Usuário:** combo para filtrar os dados por grupos de usuários previamente cadastrados nas Tags de usuários.
 - **Data Inicial e final:** define-se o período de datas que será apresentado no dash

**Visões:**
- **Hora:** ao clicar nesta opção, serão exibidos apenas os dados de ligações recebidas no dia de hoje por hora;
- **Dia:** ao clicar nesta opção, serão exibidos apenas os dados de ligações recebidas no dia;
- **Semana:** ao clicar nesta opção, os dados serão exibidos na visão semanal; 
- **Mês:** ao clicar nesta opção, os dados serão exibidos na visão mensal;


![Inbound V4.xx](/imgs/inbound_v4.gif ':class=sombracaixa' )


<h3>Conceitos dos painéis e métricas presentes no Dashboard IVR:</h3>

- **SLA:** nível de serviço da operação ou fila. O SLA é estabelecido pela gestão nas configurações da Plataforma, indica o percentual de ligações que devem ser atendidas em um determinado tempo.
- **Distribuição:** distribuição das chamadas recebidas, de acordo com os serviços (filas) configurados
- **AHT:** Average handling Time (AHT) representa o TMA da operação ou fila
- **ASA:** velocidade média de resposta da operação ou fila
- **Chamadas Recebidas:** volume total de chamadas recebidas no período
- **Chamadas Atendidas:** quantidade de chamadas que foram efetivamente atendidas no período
- **Chamadas Abandonadas:** quantidade de chamadas que foram desconectadas antes de chegar ao atendente
- **Chamadas Não Conectadas:** quantidade de chamadas que foram desconectadas, pois estouraram o tempo limite de fila
- **Disponíveis:** quantidade de agentes disponíveis para receber chamadas no momento
- **Em Chamada:** quantidade de agentes em atendimento receptivo no momento (apenas chamadas de voz)
- **Pausados:** quantidade de agentes em pausa no momento
- **Offline:** quantidade de agentes deslogados em pausa no momento
- **Chamadas e SLA:** este gráfico mostra a distribuição das chamadas recebidas e do SLA no período
- **Recebidas Vs Atendidas:** este gráfico mostra a distribuição das chamadas recebidas e atendidas no período

![Inbound V3.xx](/imgs/inbound_v3_inferior.PNG ':class=sombracaixa' )

**Importante destacar que ao clicar sobre o nome do indicador ao lado da sua legenda, é possível ocultar a exibição dos dados relacionados a ele, no gráfico.**


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Outbound

Traz informações sobre as chamadas ativas da operação (outbound), como: tempo de atendimento; quantitativo de chamadas discadas, atendidas e não conectadas, entre outras.

Na sua parte superior, há algumas opções de filtros e visões de dados e datas.

**Filtros**
- **Serviço:** combo para filtrar os dados por serviço (fila).Ao selecionar a opção "Serviço", serão exibidos dados de todas as filas da operação
- **Agente:** combo para filtrar os dados por usuário (agente). Ao selecionar a opção "Usuário", serão exibidos dados de todos os agentes da operação ou da fila escolhida
- **Tag de Usuário:** combo para filtrar os dados por grupos de usuários previamente cadastrados nas Tags de usuários
- **Data Inicial e final:** define-se o período de datas que será apresentado no dash

**Visões**
- **Hora:** ao clicar nesta opção, serão exibidos apenas os dados de ligações recebidas no dia de hoje por hora;
- **Dia:** ao clicar nesta opção, serão exibidos apenas os dados de ligações recebidas no dia;
- **Semana:** ao clicar nesta opção, os dados serão exibidos na visão semanal; 
- **Mês:** ao clicar nesta opção, os dados serão exibidos na visão mensal;

![Outbound](/imgs/outbound_1.gif ':class=sombracaixa' )

<h3>Conceitos dos painéis e métricas presentes neste Dashboard:</h3> 

- **Chamadas Discadas:** volume total de chamadas realizadas no período
- **Chamadas Atendidas:** quantidade de chamadas atendidas pelos clientes no período
- **Chamadas Não Conectadas:** quantidade de chamadas não atendidas pelos clientes no período. Por exemplo: caixa postal
- **AHT:** tempo médio de atendimento das chamadas ativas (de saída)
- **Disponíveis:** quantidade de agentes disponíveis para atender chamadas no momento
- **Em Chamada:** quantidade de agentes em atendimento ativo no momento (apenas chamadas de voz)
- **Pausados:** quantidade de agentes em pausa no momento
- **Offline:** quantidade de agentes deslogados em pausa no momento
- **Discadas e Atendidas:** este gráfico mostra a distribuição das chamadas discadas pelo agente e atendidas pelo cliente no período. Além disso, apresenta a porcentagem de sucesso das chamadas na telefonia (% Connect), ou seja, o percentual de ligações discadas que foram completadas, pois não houve problema de conexão. 


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Omni View

Dash que traz a visão de todos os atendimentos da organização, separado por mídas de texto, voz - inbound e outbound e e-mail.

![Omni View](/imgs/omniview_1.gif ':class=sombracaixa' )

**Filtros**

- **Agente:** combo para filtrar os dados por usuário (agente). Ao selecionar a opção "Usuário", serão exibidos dados de todos os agentes da operação ou da fila escolhida
- **Serviço:** combo para filtrar os dados por serviço (fila).Ao selecionar a opção "Serviço", serão exibidos dados de todas as filas da operação
- **Tag de Usuário:** combo para filtrar os dados por grupos de usuários previamente cadastrados nas Tags de usuários
- **Data Inicial e final:** define-se o período de datas que será apresentado no dash


<h3>Chat</h3>
O bloco chat traz informações dos atendimentos das mídias:
- Boteria
- Whatsapp
- ML Perguntas
- ML Pós Vendas
- Messenger
- Reclame Aqui
- Telegram
- Instagram
- Twitter

![Chat](/imgs/chat.PNG ':class=sombracaixa' )
  
<h3>Conceitos e métrica presente no Chat</h3>

- **TM1R:** Tempo médio da Primeira Resposta enviada ao atendimento
- **TMR:** Tempo médio de Resposta
- **TMA:** Tempo médio de Atendimento

<h3>Receptivo</h3>

Traz as informações das chamadas de voz inbound, ou seja, as que foram recebidas no sistema

<h4>Conceitos e métrica presente no Receptivo</h4>

- **Recebidas:** total de chamadas recebidas
- **Atendidas:** total de chamadas atendidas
- **Abandonadas:** total de chamadas abandondas
- **ASA:** Tempo Médio de espera para atendimento (Avarage Speed of Answer)
- **TMA:** Tempo Médio de Atendimento

![Receptivo](/imgs/receptivo.PNG ':class=sombracaixa' )


<h3>Ativo</h3> 

Traz as informações das chamadas de voz outbound, ou seja, as que foram realizadas pelo sistema

<h4>Conceitos e métrica presente no Ativo</h4>

- **Discadas:** total de chamadas realizadas
- **Atendidas:** total de chamadas atendidas
- **Não conectadas:** total de chamadas que foram discadas porém não foram efetivadas
- **TMO:** tempo médio operacional

![Ativo](/imgs/ativo.PNG ':class=sombracaixa' )

<h3>E-mail</h3> 
Traz as informações de todos atendimentos realizados por e-mail

<h4>Conceitos e métrica presente no E-mail</h4>

- **Recebidos:** total de e-mails recebidos
- **Respondidos:** total de e-mails respondidos
- **Não respondidos:** total de chamadas que foram discadas porém não foram efetivadas
- **TMR:** tempo médio de resposta

![Email](/imgs/email.PNG ':class=sombracaixa' )



<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## IVR

Trata-se de um dash com dados estatísticos das URA´s que a empresa possue com informações das chamadas inbound

![IVR](/imgs/ivr.PNG ':class=sombracaixa' )

<h3>Indicadores presentes no dash IVR</h3>

- **Logged:** Total de usuários logados
- **Available:** Total de usuários disponíveis para atendimento
- **Paused:** Total de usuários em pausa
- **Talking:** Total de usuários em atendimento
- **SLA:** Acordo de Nível de Serviço (Service Level Agreement)
- **ABD:** Porcentagem de abandono na fila de atendimento
- **ASA:** Tempo Médio de espera para atendimento (Avarage Speed of Answer)
- **MSA:** Tempo Máximo de espera para atendimento (Max Speed of Answer)
- **AHT:** Tempo Médio de Atendimento (Avarage Handle Time)
- **MHT:** Tempo Máximo de Atendimento (Max Handle Time) 
- **Abandoned:** Total de abandonos na fila de atendimento
- **Calls:** Total de chamadas entrantes
- **IVR-ABD:** Total de abandonos ainda na URA
- **Handeled:** Atendimento realizado e tabulado
- **Timed Out:** Quantidade de atendimentos desinfileirados (atingiu o tempo limite de espera na fila até ser atendido)

<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Chats

Relatório que traz as informações de todos os atendimentos realizados por chat, com 
**Filtros:**
- Agente
- Serviço
- Tag do usuário

**Visão:**
- Hoje
- Semanal
- Mensal
- Anual

![Chat](/imgs/Chat_1.PNG ':class=sombracaixa' )


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Pesquisa

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
![Dash Pesquisa](/imgs/dash_pesquisa_new.gif ':class=sombracaixa' )



<hr color="#836FFF" size = 8 width = 70% align = right noshade>


# Relatórios

## Rastreio de Interações

Relatório que traz a visão de cada atendimento realizado na plataforma, _que já tenha sido finalizado_, com as informações de Data/Hora, qual tipo de mídia, qual usuário,tempo de atendimento e qual foi a finalização do atendimento realizado - por meio da TAG.

_Tela Rastreio Interações_

 ![Rastreio de Interações](/imgs/rastreio_1.PNG ':class=sombracaixa' )
 
 Para extração do Relatório o campo obrigátorio é o "Mídia" os demais campos são opcionais.
 
 _Tela Filtros de Mídia_
 
 ![Rastreio de Interações](/imgs/rastreio_midias.PNG ':class=sombracaixa' )
 
 Há opção de filtros por Data, usuário, horário, Protocolo, Serviços e demais campos
 
 _Exemplo de outros Filtros_
 
 ![Rastreio de Interações](/imgs/rastreio_filtros.gif ':class=sombracaixa' )
 
 
 A visualização da extração poderá ser feita diretamente na tela do sistema, ou também poderá ser realizado download em CSV para facilitar a análise das informações.
 
  _Tabela de Resultados_
  
 ![Rastreio de Interações](/imgs/rastreio_resultados.PNG ':class=sombracaixa' )
 
 
 
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



<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Relatório IVR

Traz as informações das chamdas recebidas, poderá ser extraído com filtros:
- Agrupamento
	- IVR
	- Serviço
	- Agente
	- Hora
	- Dia
- Data
- Agente
- Serviço
- IVR (ura disponibilizada para recebimento das chamadas)
- Tags do usuário

![Relatório IVR](/imgs/ivr_2.PNG ':class=sombracaixa' )

<h4>Informações presentes no Relatório de IVR</h4>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
	<link type="text/css" rel="stylesheet" href="resources/sheet.css">
		<style type="text/css">.ritz .waffle a { color: inherit; }.ritz .waffle .s1{border-bottom:1px SOLID #000000;border-right:2px SOLID #0b5394;background-color:#0b5394;text-align:center;font-weight:bold;color:#ffffff;font-family:'docs-Calibri',Arial;font-size:10pt;vertical-align:middle;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s5{border-bottom:1px SOLID #000000;border-right:2px SOLID #0b5394;background-color:#ffffff;text-align:left;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s9{border-bottom:1px SOLID #000000;border-right:2px SOLID #0b5394;background-color:#cfe2f3;text-align:left;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s3{border-bottom:1px SOLID #000000;border-right:1px SOLID #000000;background-color:#ffffff;text-align:left;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s8{border-bottom:1px SOLID #000000;border-right:1px SOLID #000000;background-color:#cfe2f3;text-align:center;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s10{border-bottom:2px SOLID #0b5394;border-right:1px SOLID #000000;background-color:#cfe2f3;text-align:center;font-weight:bold;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s13{border-bottom:2px SOLID #0b5394;border-right:2px SOLID #0b5394;background-color:#cfe2f3;text-align:left;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s4{border-bottom:1px SOLID #000000;border-right:1px SOLID #000000;background-color:#ffffff;text-align:center;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s7{border-bottom:1px SOLID #000000;border-right:1px SOLID #000000;background-color:#cfe2f3;text-align:left;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s11{border-bottom:2px SOLID #0b5394;border-right:1px SOLID #000000;background-color:#cfe2f3;text-align:left;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s2{border-bottom:1px SOLID #000000;border-right:1px SOLID #000000;background-color:#ffffff;text-align:center;font-weight:bold;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s6{border-bottom:1px SOLID #000000;border-right:1px SOLID #000000;background-color:#cfe2f3;text-align:center;font-weight:bold;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s12{border-bottom:2px SOLID #0b5394;border-right:1px SOLID #000000;background-color:#cfe2f3;text-align:center;color:#434343;font-family:'docs-Calibri',Arial;font-size:9pt;vertical-align:bottom;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}.ritz .waffle .s0{border-bottom:1px SOLID #000000;border-right:1px SOLID #000000;background-color:#0b5394;text-align:center;font-weight:bold;color:#ffffff;font-family:'docs-Calibri',Arial;font-size:10pt;vertical-align:middle;white-space:normal;overflow:hidden;word-wrap:break-word;direction:ltr;padding:2px 3px 2px 3px;}</style>
		<div class="ritz grid-container" dir="ltr">
			<table class="waffle no-grid" cellspacing="0" cellpadding="0">
			
				<tbody>
					<tr style="height: 20px">
						<td class="s0" dir="ltr">CAMPO</td>
						<td class="s0" dir="ltr">DESCRIÇÃO</td>
						<td class="s0" dir="ltr">FORMATO</td>
						<td class="s1" dir="ltr">CÁLCULO</td>
					</tr>
					<tr style="height: 20px">
						<td class="s2" dir="ltr">Entrantes URA</td>
						<td class="s3" dir="ltr">Total de chamadas recebidas pela URA</td>
						<td class="s4" dir="ltr">Numérico</td>
						<td class="s5" dir="ltr">Soma de chamadas recebidas pela URA</td>
					</tr>
					<tr style="height: 20px">
						<td class="s6" dir="ltr">Fora de Serviço</td>
						<td class="s7" dir="ltr">Total de ligações que entraram nra URA fora do horário de atendimento configurado</td>
						<td class="s8" dir="ltr">Numérico</td>
						<td class="s9" dir="ltr">Soma de ligações que entraram nra URA fora do horário de atendimento configurado</td>
					</tr>
					<tr style="height: 20px">
						<td class="s2" dir="ltr">Abandonadas IVR</td>
						<td class="s3" dir="ltr">Total de ligações que entraram na URA porém foram abandonadas na URA</td>
						<td class="s4" dir="ltr">Numérico</td>
						<td class="s5" dir="ltr">Soma de ligações que entraram na URA porém foram abandonadas na URA</td>
					</tr>
					<tr style="height: 20px">
						<td class="s6" dir="ltr">Oferecidas</td>
						<td class="s7" dir="ltr">Total de ligações entrantes na fila</td>
						<td class="s8" dir="ltr">Numérico</td>
						<td class="s9" dir="ltr">Soma de ligações que chegaram na fila</td>
					</tr>
					<tr style="height: 20px">
						<td class="s2" dir="ltr">Abandonadas</td>
						<td class="s3" dir="ltr">Total de ligações abandonadas ao serem oferecidas</td>
						<td class="s4" dir="ltr">Numérico</td>
						<td class="s5" dir="ltr">Soma de ligações abandonadas</td>
					</tr>
					<tr style="height: 20px">
						<td class="s6" dir="ltr">%Abandonadas</td>
						<td class="s7" dir="ltr">Porcentagem de ligações oferecidas e abandonadas</td>
						<td class="s8" dir="ltr">Porcentagem %</td>
						<td class="s9" dir="ltr">(Ligações abandonadas / Ligações oferecidas) * 100</td>
					</tr>
					<tr style="height: 20px">
						<td class="s2" dir="ltr">Atendidas</td>
						<td class="s3" dir="ltr">Total de ligações atendidas dentre as oferecidas</td>
						<td class="s4" dir="ltr">Numérico</td>
						<td class="s5" dir="ltr">Soma de ligações atendidas</td>
					</tr>
					<tr style="height: 20px">
						<td class="s6" dir="ltr">Atendidas NS</td>
						<td class="s7" dir="ltr">Total de ligações atendidas dentro do Nivel de Serviço</td>
						<td class="s8" dir="ltr">Numérico</td>
						<td class="s9" dir="ltr">Soma de ligações atendidas que atingiram o Nível de Serviço</td>
					</tr>
					<tr style="height: 20px">
						<td class="s2" dir="ltr">Nível Serviço</td>
						<td class="s3" dir="ltr">Porcentagem de ligações que atingiram o Nível de Serviço</td>
						<td class="s4" dir="ltr">Porcentagem %</td>
						<td class="s5" dir="ltr">(Ligações que atingiram o Nível de Serviço / Ligações oferecidas) * 100</td>
					</tr>
					<tr style="height: 20px">
						<td class="s6" dir="ltr">Não Atendidas</td>
						<td class="s7" dir="ltr">Desenfileirado, atingiu o tempo limite de espera na fila até ser atendido.</td>
						<td class="s8" dir="ltr">Numérico</td>
						<td class="s9" dir="ltr">Soma de ligações desenfileiradas</td>
					</tr>
					<tr style="height: 20px">
						<td class="s2" dir="ltr">TMA</td>
						<td class="s3" dir="ltr">Tempo Médio de Atendimento</td>
						<td class="s4" dir="ltr">hh&#58;mm&#58;ss&#58;ms</td>
						<td class="s5" dir="ltr">Soma de todo tempo de atendimento / total de ligações atendidas</td>
					</tr>
					<tr style="height: 20px">
						<td class="s6" dir="ltr">MSA</td>
						<td class="s7" dir="ltr">Tempo Máximo de espera para atendimento (Max Speed of Answer)</td>
						<td class="s8" dir="ltr">hh&#58;mm&#58;ss&#58;ms</td>
						<td class="s9" dir="ltr">Recorde de atendimento com maior tempo de espera na fila</td>
					</tr>
					<tr style="height: 20px">
						<td class="s2" dir="ltr">ASA</td>
						<td class="s3" dir="ltr">Tempo Médio de espera para atendimento (Avarage Speed of Answer)</td>
						<td class="s4" dir="ltr">hh&#58;mm&#58;ss&#58;ms</td>
						<td class="s5" dir="ltr">Soma de todo tempo de espera na fila / total de ligações atendidas</td>
					</tr>
					<tr style="height: 20px">
						<td class="s10" dir="ltr">MHT</td>
						<td class="s11" dir="ltr">Tempo Máximo de Atendimento (Max Handle Time)</td>
						<td class="s12" dir="ltr">hh&#58;mm&#58;ss&#58;ms</td>
						<td class="s13" dir="ltr">Recorde de maior tempo de atendimento</td>
					</tr>
				</tbody>
			</table>
		</div>


_Relatório IVR Filtros_

![Relatório IVR](/imgs/filtros_ivr.gif ':class=sombracaixa' )




<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Administrativo

O módulo Administrativo gerencia os dados mais importantes da plataforma, onde é realizdo o cadastro e edição de:
- Empresas
- Usuários
- Serviços
- Tags
- Shortcuts
- Pausas
- Pesquisa de Satisfação

## Empresas

O cadastro de Empresas poderá ser realizado de duas maneiras:


**1- Por um usuário que tenha permissão para cadastro na tela de Usuários**

![Criar Empresa](/imgs/empresa_1.gif ':class=sombracaixa' )

Usuários que tenham permissão para cadastrar uma nova empresa poderão fazê-lo preenchendo o cadastro de Empresas pelo caminho:
- Administrativo
- Empresas
- Selecionar o botão "Nova Empresa"

![Cadastro Empresa](/imgs/empresa_2.PNG ':class=sombracaixa' )

- Preencher os campos:
	- Dados da Empresa, onde temos os campos obrigatórios:
		- Nome Empresa
		- E-mail Empresa
		- CNPJ
		- Telefone Empresa
		
![Cadastro Empresa](/imgs/dados_empresa.PNG ':class=sombracaixa' )

	- Endereço, com os campos obrigatórios:
		- CEP
		- Endereço
		- Número
		- Cidade
		- Estado
		- País
		
![Cadastro Empresa](/imgs/endereco_empresa.PNG ':class=sombracaixa' )	
		
	- Informações Adicionais	
	- Usuário Responsável, com os campos obrigatórios:
		- Nome Responsável
		- CPF Responsável
		- E-mail Responsável
		- Telefone Responsável
	

![Cadastro Empresa](/imgs/usuario_empresa.PNG ':class=sombracaixa' )

- Clicar em "Criar"

Será enviado para o e-mail do usuário responsável um token para que ele crie uma senha para fazer o seu primeiro login e, a partir daí, iniciar o processo de cadastro de seus usuários, serviços e canais de acordo com as necessidades da empresa.



**2- Na tela inicial do portal pelo link "Inscrever-se"**

![Inscrever Nova Empresa](/imgs/user_1.PNG ':class=sombracaixa' )


O cadastro da empresa quando realizado pelo Link "Inscrever-se" é um pré-cadastro onde será preenchido:
- Nome
- E-mail
- Telefone
- Nome da Empresa
- Número de funcionários
Após o preenchimento, será enviado para o e-mail cadastrado um token para que seja criado uma senha e realizado o primeiro acesso.

![Inscrever Nova Empresa](/imgs/inscrever_se.gif ':class=sombracaixa' )

![Inscrever Nova Empresa](/imgs/inscrever_se.PNG ':class=sombracaixa' )





<hr color="#836FFF" size = 3 width = 70% align = right noshade>


## Usuários

A Tela de usuários traz os usuários já cadastrados na organização e também a possibilidade de criar novo cadastro bem como editar um já existente.
Apresenta os campos disponíveis com sinalização dos campos obrigatórios (*).

![Cadastro usuario](/imgs/Tela_Cadastro.PNG ':class=sombracaixa' )

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

![Cadastro usuario](/imgs/usuario_1.gif ':class=sombracaixa' )


_**nota:**_ o link de “salvar” apenas ficará disponibilizado na tela após o preenchimento dos campos obrigatórios. 


<h3>Segurança - Senha - Primeiro Acesso</h3>

 Quando é finalizado o cadastro do usuário e salvo, um e-mail é disparado para o novo usuário informando um Token para que seja criado a senha e realizado o primeiro acesso.

_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Primeiro Login](/imgs/login_1.png ':class=sombracaixa' )

<h3>Segurança - Senha - Recuperar Senha</h3>

Para se recuperar a senha o processo é parecido com o primeiro acesso, basta clicar no link "Primeiro acesso ou recuperar senha" que o usuário receberá um email com um novo token que será utilizado para criar sua nova senha seguindo os passos:
- clicar em "Primeiro acessou ou recuperar senha"
- clicar em "Continuar"
- inserir o e-mail
- inserir o token
- inserir nova senha 

_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Recuperar Senha](/imgs/login_1.png ':class=sombracaixa' )


_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Recuperar Senha](/imgs/primeiro_acesso_recuperar_senha.png ':class=sombracaixa' )


_Exemplo de e-mail recebido para reset de senha ou primeiro acesso de novo usuário_
![Recuperar Senha](/imgs/primeiro_acesso_recuperar_senha2.png ':class=sombracaixa' )


<h3>Senha válida e Login</h3>

A senha deve seguir as seguintes características:
- Possuir no mínimo 6 e no máximo 20 caracteres;
- Possuir pelo menos uma letra e um número;
- Possuir pelo menos uma letra maíuscula e uma mínuscula;
- Possuir pelo menos um caracter especial ($ * & @ # ?);
- Não apresentar repetições (ex: Aabbcc, 1122).

![Login](/imgs/login_senha.gif ':class=sombracaixa' )


<h3>Segurança - Opcional Duplo Fator - Primeiro Acesso</h3>

Para empresas que desejam aumentar a segurança de login de seus usuários foi implementado o login com Duplo Fator onde por meio do aplicativo [Google Authenticator](https://support.google.com/accounts/answer/1066447?co=GENIE.Platform%3DAndroid&hl=pt-BR) é gerado um segundo token para login.

_Cadastro Usuário com Duplo Fator_
![Duplo Fator](/imgs/duplo_fator_3_2020-11-23_14h44_44.gif ':class=sombracaixa' )

Após criado o cadastro do usuário com o campo "Autenticação de duplo fator" ativado, no primeiro acesso constará o código QR que será utilizado no Google Authenticator para liberação do token para login. Este código ficará liberado apenas no primeiro acesso, ou nas demais alterações na Edição do usuário. Os demais logins não constarão o código QR uma vez já cadastrado no aplicativo Google Authenticator.

_Primeiro Acesso Duplo Fator_
![Duplo Fator](/imgs/primeiro_acesso_duplo_fator.gif ':class=sombracaixa' )


Para os logins posteriores ao primeiro acesso, apenas aparecerá o campo para ser inserido o código que o usuário terá pelo aplicativo em seu celular.

_Login Duplo Fator_
![Duplo Fator](/imgs/duplo_fator_1_2020-11-23_14h36_17.gif ':class=sombracaixa' )


_Edição de Usuário com Duplo Fator_
![Duplo Fator](/imgs/duplo_fator_2_2020-11-23_14h38_16.gif ':class=sombracaixa' )


<h3>Permissões</h3>

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




<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Serviços

Na tela principal de serviços estão disponibilizados os links para cadastro de um novo serviço onde será inserido:
- Nome
- nome do serviço a ser cadastrado
- Atendimento (%) - qual a porcentagem de atendimento desejada para o serviço
- Tempo Atendimento(s) - qual o tempo desejado para que seja inicializado o atendimento
- Tempo Abandono(s) - qual o tempo aceitável para que o atendimento tenha abandono
- Número de serviço interno - cadastro deverá ser com 3 dígitos e será utilizado para que o usuário transfira a ligação direto para o serviço solicitado
- Habilitar tela de Atendimento - se o serviço estará ou não habilitado para que seja atendido na Tela de Atendimento

_Tela de Serviços_

![Cadastro servicos](/imgs/Servicos_1.PNG ':class=sombracaixa' )

_Edição de Usuários_

![Cadastro servicos](/imgs/Servicos_2.PNG ':class=sombracaixa' )


_Tela de Cadastro de Serviços_

![Cadastro servicos](/imgs/Servicos_3.PNG ':class=sombracaixa' )

_Tela de Cadastro do Número de serviço interno_
![Cadastro servicos](/imgs/servico_interno.gif ':class=sombracaixa' )

Estão também disponibilizados os links para que seja:
- Editado quais usuários que atenderão o serviço
- Editado o serviço
- Excluído o serviço
- Ativado/Desativado o serviço


_Links de edição_

![Cadastro servicos](/imgs/Servicos_4.PNG ':class=sombracaixa' )



<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Tags

O cadastro das Tags além da finalização do atendimento traz opções de cadastro para que seja realizado:
- registro da informação (como foi realizado o atendimento, se houve venda, cancelamento ou novas negociações)
- mensagem automática de finalização
- transferência automática para outro tipo de serviço
- finalização do telefone (em casos que foi identificado pelo usuário/operador que o telefone não pertence ao contato)
- finalização do contato (em casos onde o contato deixa claro que não quer mais receber ligações)


_Tela principal Tags_

![Cadastro tag](/imgs/Tag_1.PNG ':class=sombracaixa' )


_Cadastro de nova Tag_

![Cadastro tag](/imgs/Tag_2.PNG ':class=sombracaixa' )



<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Shortcuts

Shortcuts são os atalhos que podem ser criados para otimizar o atendimento, estão linkados aos serviços, ou seja, cada shortcut criada deve ser relacionada a um serviço. Assim, quando o usuário estiver em atendimento, poderá utilizar o atalho que trará frases prontas de um determinado assunto. Sendo útil na padronização do atendimento e também para otimizar o tempo do usuário/atendente.

_Tela de Shortcuts_

![Shortcuts](/imgs/short_1.PNG ':class=sombracaixa' )

O **cadastro** de shortcuts é bem simples, basta clicar no "+" no canto inferior direito da tela principal de Shortcuts e liberará uma nova linha para cadastro, após a liberação inserir:
- prefixo - atalho que será utilizado pelo agente para buscar o texto
- Texto - a frase que será utilizada
- Serviço - abrirá a lista de serviços cadastrados na Organização para que seja selecionado qual receberá a Shortcut que está sendo cadastrada

Após preenchimento, clicar no ícone de salvar (símbolo de um disquete). 
Para editar um texto já criado, basta ir no campo Texto, fazer as alterações necessárias e clicar em salvar.

_Cadastro de nova Shortcuts_

![Shortcuts](/imgs/short_3.PNG ':class=sombracaixa' )

A utilização das shortcuts já cadastradas é realizada na Tela de Atendimento pelo usuário clicando "/" (barra), assim a lista de atalhos disponibilizados para o Serviço em que está em atendimento será liberada para que o atendente utilize em seu atendimento.

_Tela de Atendimento - utilização de Shortcuts_

![Shortcuts](/imgs/short_2.PNG ':class=sombracaixa' )

A exclusão de Shortcuts poderá ser realizada clicando no ícone da "lixeira", então ficará liberado outro ícone de exclusão após clicar ali, seu shortcuts será excluído e não haverá possibilidade de resgatá-lo a não ser recriando-o novamente.

_Exclusão de Shortcuts_

![Shortcuts](/imgs/short_4.PNG ':class=sombracaixa' )




<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Pausas

Utilizadas para identificar as paradas dos usuários, o cadastro das Pausas auxilia na gestão da Equipe para mensurar inclusive como indicar de produtividade, pois constará a informação em relatórios de gestão.

_Tela Pausa_

![Pausa](/imgs/Pausa_1.PNG ':class=sombracaixa' )

Seu cadastro é simples, basta clicar no "+" no canto inferior da tela e cadastrar no campo "Motivo da Pausa", 

_Cadastro de Pausa_

![Pausa](/imgs/Pausa_2.PNG ':class=sombracaixa' )

A exclusão é realizada clicando no ícone da "lixeira" 

_Exclusão de Pausa_

![Pausa](/imgs/Pausa_3.PNG ':class=sombracaixa' )

O usuário, quando for entrar em pausa, encontrará a listagem para optar pelo motivo da Pausa que está realizando

_Utilização de Pausa_

![Pausa](/imgs/Pausa_4.PNG ':class=sombracaixa' )


_Utilização de Pausa - Tela Visão do Agente_

![Pausa](/imgs/Pausa_5.PNG ':class=sombracaixa' )

_Utilização de Pausa_

![Pausa](/imgs/2020-10-08_15h31_15.gif ':class=sombracaixa' )




<hr color="#836FFF" size = 8 width = 70% align = right noshade>

## Pesquisa de Satisfação


<h2>NPS</h2>

O Net Promoter Score (NPS) é uma métrica de lealdade do cliente, com o objetivo de medir o grau de lealdade dos clientes das empresas de qualquer segmento, trazendo reflexos da experiência e satisfação dos clientes. Perguntas adicionais podem ser incluídas para ajudar a compreender a percepção de vários produtos, serviços e linhas de negócios. Estas perguntas adicionais ajudam a empresa a avaliar a importância relativa dessas outras partes do negócio na pontuação geral. Isto é especialmente útil para orientar os recursos e resolver questões que mais impactam o NPS.

O Net Promoter Score tem como proposta inovar a cultura das pesquisas de pós-venda para que elas consigam ter uma visão real dos serviços prestados pela empresa e consequentemente ajudá-la a evoluir e conquistar um patamar de solidez e excelência no mercado. O NPS se garante como importante peça na expansão dos negócios e aumento do retorno de investimento.


<h2>CSAT</h2>

A sigla CSAT remete à Customer Satisfaction Score. Como o próprio nome em inglês já indica, é uma Escala de Satisfação do Cliente. Esse tipo de pesquisa é utilizado para avaliar a imagem que o consumidor tem da marca e leva em conta pontos de interação, como:
- Atendimento antes, durante e depois da compra;
- Logística de entrega;
- Produto ou serviço;
- Agilidade na resolução de problemas;
- Todo o processo de vendas.
O CSAT é uma pesquisa de curto prazo, geralmente aplicada por meio de perguntas do tipo: “como você classificaria sua experiência com a marca?”. Pode conter questões sobre cada um dos pontos que mencionamos acima, além de um espaço para comentários adicionais ou até para justificar a avaliação.

A Criação da Pesquisa de Satisfação na plataforma é realizada de forma rápida, objetiva e simples onde o gestor da Organização poderá inserir as perguntas e a variável da pontuação que desejar para cada pergunta. 

![Pesquisa](/imgs/Pesquisa_1.PNG ':class=sombracaixa' )

<h2>Criando Pesquisa</h2>

![Criando Pesquisa](/imgs/Pesquisa_2.PNG ':class=sombracaixa' )

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
![Criando Pesquisa](/imgs/cria_pesquisa.gif ':class=sombracaixa' )


_Demonstração de criação de Pesquisa Whatsapp e Chat_
![Criando Pesquisa](/imgs/cria_pesquisa_chat.gif ':class=sombracaixa' )


<h2>Criando Pesquisa Email</h2>

Para criação de Pesquisa de E-mail deve-se notar que, ao ser finalizado o atendimento por email na plataforma, o cliente receberá um e-mail automático de acordo com a  configuração realizada que contém um link que o levará para uma página onde responderá a Pesquisa.
Atenção no preenchimentos dos campos:
1. Assunto Email - trata-se do título que será enviado o e-mail para o cliente
2. Corpo do Email - espaço para ser escrito o texto que estará no corpo do email que será enviado para o cliente
3. Adicionar Link - para que o email seja enviado com o link que abrirá a página com as perguntas, deve ser adicionado o link clicando no botão verde "Adicionar Link"
A partir daí o fluxo de cadastro das perguntas seguem da mesma forma que as demais mídias.


_Demonstração de criação de Pesquisa Email_
![Criando Pesquisa Email](/imgs/cria_pesquisa_email.gif ':class=sombracaixa' )




<h2>Relatório de Pesquisa</h2>

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

![Relatório Pesquisa](/imgs/Pesquisa_5.PNG ':class=sombracaixa' )

_Demonstração de extração de Relatório de Pesquisa_
![Relatório Pesquisa](/imgs/relatorio_pesquisa.gif ':class=sombracaixa' )

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

![Relatório Pesquisa](/imgs/Pesquisa_6.PNG ':class=sombracaixa' )


<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Segurança

Módulo onde se pode criar grupos de usuários e associá-los a perfis de segurança

_Tela de Segurança_
![Tela Segurança](/imgs/seguranca_1.PNG ':class=sombracaixa')

<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Gerenciamento de Perfil

Em Gerenciamento de Perfil, poderá ser criado os mais diversos tipos de perfil para que cada grupo de usuário tenha os acessos de acordo com a necessidade e perfil de suas atividades.

_Tela de Gerenciamento de perfil_

![Gerenciamento de perfil](/imgs/gerencia_perfil_1.gif ':class=sombracaixa')

<h3>Criando um novo Perfil</h3>

- Clique em Novo perfil
- Preencha os campos:
   - Nome
   - Descrição
- Selecione as Funções
   - Selecione as Permissões (note que cada Função tem suas permissões de forma separada entre criar, excluir, editar, etc)

Após o término da definição do perfil, clique no botão "Criar" e o perfil estará pronto para ser atribuido ao usuário.

<h3>Funções</h3>

As funções que serão selecionadas para a criação do perfil é de extrema importância, pois será aqui onde ficará definido os acessos e permissões dos usuários, conheça melhor as funções:

<h3>Funções Administrativas</h3>

![Tabela Funções Adm](/imgs/func_ADM.PNG ':class=sombracaixa')


<h3>Funções Canais</h3>

![Tabela Funções Adm](/imgs/Tabela_canais_seguranca.PNG ':class=sombracaixa')


<h3>Funções Conectores</h3>

![Tabela Funções Adm](/imgs/Tabela_conectores_seguranca.PNG ':class=sombracaixa')


<h3>Funções Contatos</h3>

![Tabela Funções Adm](/imgs/Tabela_contatos_seguranca.PNG ':class=sombracaixa')


<h3>Funções Dashboards</h3>

![Tabela Funções Adm](/imgs/Tabela_dash_seguranca.PNG ':class=sombracaixa')


<h3>Funções Exportação</h3>

![Tabela Funções Adm](/imgs/Tabela_exportacao_seguranca.PNG ':class=sombracaixa')


<h3>Funções Menu</h3>

![Tabela Funções Adm](/imgs/Tabela_menu_seguranca.PNG ':class=sombracaixa')


<h3>Funções Monitoração</h3>

![Tabela Funções Adm](/imgs/Tabela_monitoracao_seguranca.PNG ':class=sombracaixa')


<h3>Funções OneScreen</h3>

![Tabela Funções Adm](/imgs/Tabela_onescreen_seguranca.PNG ':class=sombracaixa')


<h3>Funções Perfil</h3>

![Tabela Funções Adm](/imgs/Tabela_perfil_seguranca.PNG ':class=sombracaixa')


<h3>Funções Portifólio</h3>

![Tabela Funções Adm](/imgs/Tabela_portifolio_seguranca.PNG ':class=sombracaixa')


<h3>Funções Relatórios</h3>

![Tabela Funções Adm](/imgs/Tabela_relatorios_seguranca.PNG ':class=sombracaixa')


<h3>Funções Segurança</h3>

![Tabela Funções Adm](/imgs/Tabela_seguranca_seguranca.PNG ':class=sombracaixa')


<h3>Funções Sistema</h3>

![Tabela Funções Adm](/imgs/Tabela_sistema_seguranca.PNG ':class=sombracaixa')


<h3>Funções SoftPhone</h3>

![Tabela Funções Adm](/imgs/Tabela_softpone_seguranca.PNG ':class=sombracaixa')



<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Usuários

No módulo de Usuários, será realizado a associação dos usuários aos perfis préviamente criados no "Gerenciamento de Perfil"

_Tela de Usuários_

![Usuário](/imgs/seg_usuario_1.gif ':class=sombracaixa')

Ao abrir a tela de Usuários em Segurança, poderá ser realizado uma busca por usuário ou fazer uma seleção de todos os usuários, em seguida, poderá ser realizada a atribuição dos perfis para a seleção de usuários que foi feita.

**Nota:**

1 - o usuário deverá estar préviamente cadastrado no módulo Administrativo

2 - a atribuição de perfil poderá ser única ou múltipla

3 - apenas os usuários selecionados receberão a atribuição do perfil


![Usuário](/imgs/seg_usuario_2.PNG ':class=sombracaixa')


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Takeout

<h3>Takeout - O que é?</h3>

É um módulo no Code7 Omni que permite aos usuários, previamente autorizados, a fazer download de todos os arquivos, incluindo fotos, vídeos, áudios e mensagens armazenados na Empresa para utilização em outras plataformas ou armazenamento local.

<h3>Como extrair o documento?</h3>

O módulo Takeout está liberado na nova versão 4 do Code7 Omni em Segurança. 

![Tela Segurança](/imgs/seguranca2.PNG ':class=sombracaixa')

Clique em Takeout

![Tela Segurança](/imgs/seguranca3.PNG ':class=sombracaixa')

Abrirá a Tela com as ações para:

- Atualizar a tela
- Gerar Novo takeout
- Filtro para buscar por Status
- Cancelar takeout quando estiver sendo gerado
- Reiniciar takeout quando estiver com status de erro 

 Ao clicar em “Novo Takeout” uma janela com a informação do processo de extração dos dados, clique em “Exportar” 
 
 Aparecerá uma confirmação e na tela surgirá a sua solicitação de extração com o Status de Pendente 
 
 ![Taketout](/imgs/takeout_1.gif ':class=sombracaixa')
 
 <h3>Status</h3>
 
 Os status no filtro de busca disponíveis são: 
 
 1. **Pendente** - quando foi realizada a solicitação de exportação dos arquivos e o sistema está preparando o ambiente para iniciar o processo.
 2. **Processando** - quando a exportação está sendo realizada
 3. **Cancelado** - quando foi solicitado o cancelamento da exportação
 4. **Finalizado** - quando foi realizado o processo de exportação em sua totalidade
 5. **Erro** - quando foi identificado um erro durante o processo de exportação, solicitações com Status de Erro podem ser reinicializadas.


Os Status que podem ter interações são:

- Finalizado – para gerar o download
- Erro – que poderá ser reiniciado 

<h3>Download do Arquivo</h3>

Quando a extração do Arquivo for finalizada, será enviado um e-mail para o gestor da empresa e para o usuário que a solicitou, como no exemplo abaixo: 

![Email Takeout](/imgs/takeout_email.PNG ':class=sombracaixa')

O arquivo gerado para download é um arquivo compactado e dividido em vários outros arquivos, logo deve-se fazer o download de todos os arquivos disponibilizados para que se possa descompactar o arquivo principal. Os arquivos após o download deverão ser descompactados.

![Takeout Arquivo](/imgs/takeout_arquivo.PNG ':class=sombracaixa')

Os dados são fornecidos em json. As imagens, vídeos e áudios são enviados em pastas separadas. 


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Grupos de usuário

O módulo de Grupos de Usuários possibilita a criação de grupos em hierarquia onde o líder do grupo tem acesso exclusivo aos dados dos usuários de seu grupo nos
relatórios compreendidos pela construção de hierarquia mantendo a segurança dos dados de forma restrita. 

_Tela Grupo de usuários_
![Grupo de usuários](/imgs/grupo_user_1.gif ':class=sombracaixa')

<h3>Criação de Grupo e Usuários</h3>

- Clique em "Criar grupo"
- Insira Nome do grupo
- Insira a Descrição do grupo
- Defina o Administrador no campo "Administrador"
- Clique em "Criar"
- Após a criação, defina quais usuários ficarão sob a hierarquia do grupo criado


_Tela Grupo de usuários edição_
![Grupo de usuários](/imgs/grupos_user_edicao.gif ':class=sombracaixa')


_Tela Grupo de usuários exclusão_
![Grupo de usuários](/imgs/grupo_exclusao.gif ':class=sombracaixa')



<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Canais

Em Canais são realizados os cadastros de todas as mídias que a empresa terá para atendimento, voz, whatsapp, webchat, e-mail e mercado livre.

_Tela de Canais_

![Canais](/imgs/Canais_1.PNG ':class=sombracaixa' )

## Telefone

O Cadastro e Configuração do telefone para atendimento é realizado de forma prática e bem intuitiva
Na tela principal, clique no **+** para cadastrar o telefone, preenchendo os campos:
- Escolha o pais de origem,
- Escolha o código de área - estarão as opções do número de telefone que poderá utilizar pra seu atendimento,
- Escolha um nome,

_Tela de cadastro e gerenciamento da rota da ligação, onde é realizado a configuração da fila de atendimento_
![Canais Telefone](/imgs/Telefone_10.PNG ':class=sombracaixa' )

_Tela de definição do telefone_
![Canais Telefone](/imgs/Telefone_11.PNG ':class=sombracaixa' )

Após definição do telefone que ficará disponibilizado para receber as ligações, deve-se configurar a fila de atendimento por serviço:
- Horário de Atendimento - seleção do dia da semana e horários inicial e final do atendimento
- Mensagem de Boas Vindas
- Mensagem com Atendimento Fechado
- Serviços que farão parte do atendimento
- Mensagem para ligações não atendidas

<h3>Horário de Atendimento</h3>

A configuração dos horários de atendimento poderão ser com Atendimento sempre aberto (24x7) ou poderá ser Configurado os horários por dia da semana de acordo com a necessidade da organização, neste caso, você optará pelo fuso horário e poderá inserir o dia da semana e quais os horários iniciais e finais de cada dia.

_Configuração dos Horários de Atendimento_
![Canais Telefone](/imgs/Telefone_3.PNG ':class=sombracaixa' )

<h4>Mensagem de Boas Vindas</h4>

Conhecida também como mensagem de saudação, que será enviada assim que o contato for atendido pela URA. Poderá ser cadastrada internamente na plataforma, onde o Texto é escrito, transformado em áudio pelo robô e definido qual voz será utilizada na gravação ou a organização poderá importar um arquivo próprio de áudio .mp3 ou .wav.

_Configuração Mensagem de Boas Vindas_
![Canais Telefone](/imgs/Telefone_4.PNG ':class=sombracaixa' )

<h3>Mensagem com Atendimento Fechado</h3>

Utilizada quando o contato realiza uma ligação para a URA fora do seu horário de atendimento, então é realizada uma gravação para informar que não estão atendendo no momento. Poderá ser cadastrada internamente na plataforma, onde o Texto é escrito, transformado em áudio pelo robô e definido qual voz será utilizada na gravação ou a organização poderá importar um arquivo próprio de áudio .mp3 ou .wav.

_Configuração Mensagem de Atendimento Fechado_
![Canais Telefone](/imgs/Telefone_5.PNG ':class=sombracaixa' )

<h3>Cadastro dos Serviços</h3>

A escolha dos Serviços que serão atendidos pela URA deverá ser realizada a critério da organização, de forma que melhor lhe atenda. Clicando no ícone de editar do Menu de Atendimento poderá ser escolhido qual serviço será escolhido e em qual ordem de discagem na URA ele ficará.

<h4>Mensagem para ligações não atendidas</h4>
<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Whatsapp

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Boteria

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## E-mail

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Mercado Livre

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Facebook

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Reclame Aqui

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Telegram


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Twitter

A Code7 Omni oferece agora uma nova integração para atendimento de clientes por meio do Twitter. A criação do Canal é realizada de forma simples diretamente pela plataforma bastando que a empresa tenha uma conta de Twitter ativa.

<h3>Passo a Passo para criar o Canal de Twitter</h3>

1. Faça login no Code7 Omni versão 3 pelo link https://omni.mozaik.cloud/ 
2. No menu lateral, clique na “engrenagem” e no menu “Canais”
3. No Canal do Twitter clique em “Acessar”
4. Clique no link de “+” no canto superior direito da tela
5. Preencha os campos de Serviço e Nome do Canal
6. Clique no botão “Entrar com o Twitter”
7. Abrirá uma Tela solicitando autorização para a integração, basta dar ok
8. Salvar a tela com as informações preenchidas automaticamente
9. Salvar e concluir


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Instagram

A Code7 Omni é uma aplicação Omnichannel, com integrações ativas com Whatsapp, Menssenger, Twitter, entre outros canais de comunicação. A integração com Instagram que estamos pleiteando tem como objetivo acrescentar valor e otimização de gestão entre contas comerciais do Instagram e seus clientes onde nós, da Code7 Omni seremos o intermediador entre ambos oferecendo facilidade, controle e histórico dos atendimentos realizados.
O primeiro passo é a criação de um canal de integração onde o gestor da conta comercial faz seu cadastro informando seu email e página relacionada no Instagram, após a criação do canal, poderá ser dado início ao atendimento e conversação entre contas comerciais e seus clientes, possibilitando a gestão de toda a jornada dos clientes para a conta comercial do Instagram.
A Code7 Omni oferece gestão durante o atendimento, relatórios com indicadores, histórico com toda a jornada do cliente, pesquisas de satisfação e relatórios para análise das atividades de seus atendentes.
A integração a ser realizada com o Instagram possui alguns pré-requisitos:
1. Uma conta no Instagram que seja configurada para bussiness
2. A conta do Instagram deverá estar vinculada a uma página do Facebook
3.  

# Conectores

<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Contatos
## Meus contatos

Os Contatos podem ser cadastrados individualmente ou por meio de importação de arquivo CSV, temos como único campo obrigatório o Nome do contato.


O **Cadastro individual** é realizado ao clicar em **Novo contato** no canto superior direito da tela onde terá acesso aos campos de Cadastro


_Acesso aos tipos de Cadastro_

![Contatos](/imgs/contato_1.gif ':class=sombracaixa' )


Na tela de Cadastro Individual poderá ser inserido:
- uma Imagem/Avatar do contato
- alternado o tipo de cadastro se Corporativo ou Pessoa Física
- adicionado até 10 números de Telefones por contato
- adicionar campos Customizados - campos coringa - que poderão ser criados de acordo com a necessidade de cada organização


_Cadastro Campos Customizados_

![Contatos](/imgs/campo_customizado.gif ':class=sombracaixa' )


Para realizar o cadastro em massa, utiliza-se a importação de Arquivo CSV que é acessado no canto superior direito da tela demonstrado na imagem _Acesso aos tipos de Cadastro_
na tela de Importação com arquivo CSV está disponibilizado um modelo do arquivo com os campos e formatos para que ocorra a importação.


_Tela Importação CSV_

![Contatos](/imgs/contato_csv.gif ':class=sombracaixa' )

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



<hr color="#836FFF" size = 3 width = 70% align = right noshade>

### Carteirização

A carteira de clientes é um dos recursos mais valiosos de uma empresa. Trata-se do grupo de clientes que compram ou já compraram alguma vez da sua marca. Quanto mais organizado e qualificado for esse recurso, mais chances de você aumentar a performance em vendas. 

Logo, gestão e equipe de vendas devem organizar e desenvolver a carteira de clientes, sempre com objetivo de se relacionar bem com eles e aproveitar as melhores oportunidades para fechar uma venda. 

O processo de Carteirização consiste em dividir os clientes da empresa e vincular um vendedor a um ou mais clientes, de forma que todos tenham um vendedor responsável. 

No Code7 Omni elaboramos uma forma de carteirização de clientes para que os usuários tenham em sua carteira formas de fluxos que melhor atendam tanto o cliente carteirizado quanto o usuário detentor da carteira focando em todas as mídias disponíveis da plataforma para que a carteirização seja abrangente e eficiente independente da forma escolhida pelo cliente carteirizado por entrar em contato. 

<hr color="#836FFF" size = 3 width = 70% align = right noshade>

### Anonimizar

A aplicação da Anonimização já é possível na Code7 Omni, seguindo uma das regras da LGPD, será possível controlar a anonimização para atender possível solicitação do titular. 

O objetivo da funcionalidade de Anonimização é a de criptografar completamente todos os dados do contato em seus atendimentos realizados. Uma vez realizado a anonimização, não poderá mais ser revertido o processo, por isso, deve-se ter bem claro a regra para que os usuários não a façam sem consentimento e solicitação do cliente.

<h3>Realizando a anonimização de um Contato</h3> 

A função de Anonimização de Contatos está disponível na nova versão do Code7 Omni. Inicialmente o usuário deverá estar habilitado para a função de anonimização que será configurada por meio de solicitação do Gestor da Organização via chamado. 

<h3>Passo a Passo para Anonimização</h3> 

1. Acesse a tela de contatos da Plataforma
2. Selecione o contato ou os contatos que deverão ser anonimizados
3. Clique no botão “Anonimizar”
4. Confirme a solicitação - Atenção para a confirmação, pois se trata de uma ação que não poderá ser revertida
5. Realize nova Autorização inserindo login e senha do usuário e clique em “Anonimizar”
6. Será realizada a confirmação com uma mensagem automática confirmando ou não o sucesso da ação. 

<h3>Casos em que não será possível Anonimizar o contato:</h3> 

1. Contato com Atendimento em aberto
2. Contato com Pesquisa em aberto
3. Contato com Agendamento em aberto 

Além da informação que não houve sucesso na tentativa, ficará também disponível um Arquivo CSV com as informações de cada contato pelo insucesso da ação.

<h3>Como ficará o contato após a Anonimização</h3>

As chaves de criptografias são geradas a partir de um hash com protocolo SHA-256, suas chaves de criptografia são geradas em tempo de execução, de forma randômica e armazenadas dentro de um bucket de tamanho indeterminado criando assim a anonimização de dados pessoais e sensíveis de forma irreversível até mesmo para equipe da Code7, respeitando assim a LGPD através de um processo simples, rápido e eficaz. 

Todos os dados do contato serão anonimizados na base de dados, ou seja, não teremos mais nenhuma informação referente a este contato para consulta na plataforma.
1. Na tela de contatos
	a. Ficará inativo
	b. Dados serão substituídos por identificador criptografado gerado de forma aleatória pela plataforma
2.Nos relatórios e histórico de atendimento
	a. Os dados apresentados serão dados criptografados impedindo, assim a identificação do contato
	b. Todos os demais dados de atendimento serão mantidos intactos na plataforma para a gestão dos históricos de atendimento.


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Blacklist


O cadastro do blacklist, ou seja, os telefones que ficarão bloqueados para contatos, é realizado para Inbound e Outbound separadamente.

_Tela de Blacklist_

![Blacklist](/imgs/Blacklist_00.PNG ':class=sombracaixa' )

O cadastro dos telefones para Blacklist pode ser realizado individualmente ou por importação de CSV, em ambos os casos, o formato do telefone importado deverá ser
realizado de acordo com as regras:

- Inbound
	- DDD + número do telefone
- outbound
	- DDI + DDD + número do telefone
	

_Tela de Importação individual Outbound_

![Blacklist](/imgs/Black_outbound.PNG ':class=sombracaixa' )


- Registrar o número do Telefone e clicar em Salvar


_Tela de Importação individual Inbound_

![Blacklist](/imgs/Black_inbound.PNG ':class=sombracaixa' )


_Tela de Importação individual Inbound lista flow_

![Blacklist](/imgs/Black_inbound_2.PNG ':class=sombracaixa' )


- Selecionar a URA
- Registrar o número do Telefone e clicar em Salvar

Para importação de telefones por arquivo CSV, o modelo do documento está disponível para download na tela de importação


_Tela de Importação CSV Inbound_

![Blacklist](/imgs/Blacklist_csv_inbound.PNG ':class=sombracaixa' )

Note que para importação do arquivo CSV Inbound, ligações receptivas, o campo "blacklist_type" sempre terá o valor de 1



_Tela de Importação CSV Outbound_

![Blacklist](/imgs/Blacklist_csv_outbound.PNG ':class=sombracaixa' )

![Blacklist](/imgs/Black_outbound2.PNG ':class=sombracaixa' )


Note que para importação do arquivo CSV Outbound, ligações receptivas, o campo "blacklist_type" sempre terá o valor de 2

## Blacklist

<hr color="#836FFF" size = 8 width = 70% align = right noshade>


# Tela de Atendimento

## Disparo Rápido

A implementação do Disparo Rápido no Code7 Omni possibilita que a empresa entre em contato com seus clientes individualmente por meio ativo na mídia em que o contato tenha registrado em seu cadastrado.

![Disparo Rápido](/imgs/disparo1a.PNG ':class=sombracaixa' )

<h3>Como enviar uma mensagem pelo Disparo Rápido</h3>

Na tela de atendimento, o usuário deverá:
1. Clicar no ícone do Disparo Rápido
2. Buscar o nome do contato no campo de busca
3. Selecionar o contato
4. Definir qual mídia será realizado o disparo - as mídias em que o contato já tenha cadastrado
5. Definiar qual será o serviço
a. Para os atendimentos de voz, definir qual telefone do contato será realizada a chamada
6. Escrever a mensagem
7. Enviar

![Disparo Rápido](/imgs/disparo1.PNG ':class=sombracaixa' )

**Atenção** - os envios de Disparo Rápido por meio da mídia de Whatsapp só poderá ser realizado se na mídia constar HSM cadastrado.

<h3>Agendamento pelo Disparo Rápido</h3>

As mesmas funções de agendamento já existem podem ser aplicadas também ao Disparo Rápido

Na tela de atendimento, o usuário deverá:
1. Clicar no ícone do Disparo Rápido
2. Buscar o nome do contato no campo de busca
3. Selecionar o contato
4. Definir qual mídia será realizado o disparo - as mídias em que o contato já tenha cadastrado
5. Definir data e hora para envio da mensagem
6. Salvar
7. Após a mensagem de confirmação de agendamento salvo, no link de agendamento já estará o contato agendado

![Disparo Rápido](/imgs/disparo_agendamento.PNG ':class=sombracaixa' ) 

Após o envio da mensagem, na tela de atendimento ficará registrado o envio e a mensagem que foi enviada para o contato, assim que o contato retornar a mensagem o usuário poderá dar continuidade na abordagem normalmente.

![Disparo Rápido](/imgs/disparo_atendimento.PNG ':class=sombracaixa' )

<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Campanhas
## Discador

A funcionalidade do discador da plataforma Code7 Omni traz agilidade e facilidade na criação e gerenciamento de Campanhas onde se pode criar o grupo de contatos, estratégia e campanhas que irão fazer parte da discagem em massa. Podendo ser configurado de acordo com os melhores horários de discagem e lançados ao operador assim que atendidas, otimizando tempo e melhorando o CPC, realizando o aumento do Fluxo de Ligações sendo configurado de forma estratégica para ter a maior assertividade possível nas campanhas.


### Grupo de Contatos

Na Tela de Grupo de Contatos se cria e edita os contatos que receberão as ligações de sua Campanha.

![Grupo Contatos](/imgs/Grupo_Contatos_Discador.PNG ':class=sombracaixa' )

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

![Novo Grupo Contatos](/imgs/Inserir_grupo.PNG ':class=sombracaixa' )

 - Selecione o ícone com o **“+”** na tela principal
 - No campo Grupo de Contatos, insira um nome para seu novo grupo que será importado, escolha bem o nome, pois uma vez criado ele não ficará disponível para alteração do nome.
 - Clique no ícone de upload escolha seu arquivo CSV e faça a importação.
 - Para baixar o modelo que deverá ser utilizado, clique no “Clique aqui” e faça o download do modelo do arquivo.

**Clique no link abaixo para checar todos os campos do modelo de arquivo para importação dos contatos:**

<a href="imgs/CSV_Discador.pdf" download>Clique aqui </a>
 
 ![Importar Grupo Contatos](/imgs/Importar_grupo_contato.PNG ':class=sombracaixa' )
 
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
    
![Editar Grupo Contatos](/imgs/Editar_grupo_contato.PNG ':class=sombracaixa' ) 
    
**Consulta - Grupo de Contatos**

A Tela de verificação do grupo de contatos possibilitará a revisita das informações dos contatos que constam no grupo, onde poderá: 
 - excluir contato individual - somente se não houver campanha associada ao grupo de contatos
 - consultar os contatos importados no grupo 



### Estratégia

**Criação - Estratégia de Discagem**

Será em Estratégia onde as configurações de modo de discagem serão configuradas, para iniciar as configurações de Estratégia, o seu grupo de contato já deverá estar criado.
A primeira Tela da Estratégia contém filtros para pesquisa, ações em lote e tabela trazendo informações das estratégias já criadas com os campos:
- Estratégia - nome da Estratégia
- Sequência
- Cadência
- Regiões DDD
- Móvel
- Fixo
- Ativo - status
- Alterações em Lote com os filtros de - Status, Status Móvel, Status fixo, Status móvel e fixo, Alterar Sequência e Alterar Cadência. Onde:

![Estratégia](/imgs/Estrategia_tab1.PNG ':class=sombracaixa' ) 


As configurações da discagem de sua campanha será feita pela Estratégia, onde irá inserir:
- Estratégia - o nome da estratégia de sua campanha
- Sequência - a forma da discagem, sendo vertical onde o discador vai ligar para o primeiro telefone de cada contato e horizontal onde o discador vai ligar para todos os telefones de um contato e para depois começar a discar para o próximo contato.
- Cadência - estrutura de tentativa de contatos
- Renitência - os limitadores de número de tentativas e o intervalo de tempo para cada uma das situações de:
	- Abandono - ligações abandonadas
	- Caixa Postal - quando a chamada vai para caixa postal
	- Ocupado - quando a chamada está ocupada
	- Não conectado - quando a chamada não é realizada
	- Não atendido - chamada realizada porém não é atendida pelo contato
- Número inexistente ou incorreto - para situações onde é identificado a inexistência do número

![Estratégia](/imgs/estrategia_tela1.png ':class=sombracaixa' ) 

![Estratégia](/imgs/estrategia_tela2.png ':class=sombracaixa' ) 

- Filtros
	- Móvel - ativa liberação de discagem para fone móvel
	- Fixo - ativa liberação de discagem para fone fixo
	- Regiões DDI - fixo 55
	- Regiões DDD - poderá ser definido por DDD quais serão discados e quais serão os horários de início e fim da discagem por DDD escolhido. 
	
![Estratégia Filtros](/imgs/estrategia_tela3.png ':class=sombracaixa' )


**Edição - Estratégia**

A edição de uma estratégia já criada limita-se em alterações nos campos:
- Sequência
- Cadência
- Renitência
- Filtros
- Ativar ou Inativar a Estratégia 


### Campanha

**Criação de uma nova Campanha**

A Campanha entrelaça todas as informações do Grupo de Contatos e Estratégia que foram criados para que seja realizada a discagem, no menu Campanha poderá ser realizado pesquisas das campanhas existentes, cadastro de novas campanhas e controlar cada campanha apresentada na tabela que traz os campos de: 
- Campanha - nome da campanha
- Serviço - nome do serviço que receberá as chamadas
- Estratégia - nome da estratégia utilizada por campanha
- Controle - iniciar, pausar, encerrar, repetir e reiniciar 

![Tela - Campanha](/imgs/campanha_tela7.png ':class=sombracaixa' )

![Controle - Campanha](/imgs/campanha_tela1.png ':class=sombracaixa' )

A criação da campanha é realizada em duas partes, onde a primeira serão cadastrados:
- Nome da Campanha
- Serviço
- Grupos de Contatos
- Estratégia 

A segunda parte será a definição de como será realizado o controle da Campanha de forma **Manual** ou **Automática**. 
**Controles Manuais**

![Controle Manual - Campanha](/imgs/campanha_tela4.png ':class=sombracaixa' )

Com os Controles Manuais o administrador da campanha poderá definir os momentos de início, pausa, encerramento ou reinício da campanha pela tela inicial mostrada anteriormente. 

**Controles Automatizados**

Os **Controles Automatizados** deverão ser configurados com maior atenção pois todos os detalhes das ações de discagem serão cadastrados para que a automação ocorra.  
Deverá ser informado:
- Vigência - data de início e encerramento
- Agendamento de pausas
- Vigência Diária - será selecionado os dias da semana e seus horários de início e finalização da discagem 

![Controle Automatizado - Campanha](/imgs/campanha_tela3.png ':class=sombracaixa' )

* A edição das configurações poderá ser realizada desde que não tenha sido iniciado a discagem, para editar campanhas que estejam em discagem é necessário que seja alterado seu Status para Pausa. 


### Monitoramento

A Tela monitoramento é um dashboard tratá todas as informações das campanhas que estão em discagem, onde poderá visualizar as informações em Tempo Real ou Definir um período de tempo filtrando por Campanha. 
O dash de monitoramento, quando visualizado em tempo real, trará informações como:
- Status dos Agentes
	- disponíveis - total de agentes disponíveis para atendimento na campanha
 	- em chamada - total de agentes que estão em atendimento
 	- em pausa - total de agentes em pausa
 	- offline - total de agentes que estão cadastrados no serviço da campanha e que não estão conectados.
 - Status da Campanha
 	- em discagem - total de telefones de contato que estão sendo discados
 	- conectados - é uma visão de todos os telefones que tiveram atendimento (chamada finalizada) na campanha
 	- não conectados – é uma visão de todos os telefones com status diferente de atendimento (chamada finalizada) na campanha
 	- trabalhados - é uma visão de todos os telefones conectados + não conectados + em discagem na campanha
 - Gráficos
	- Campanha
	 	- Trabalhados
	 	- Não Trabalhados
	 	- Finalizados
		- Total de Telefones
	- Agentes disponíveis x Discando agora
	 	- Disponíveis
	 	- Discando
	- Resumo da campanha por grupo de contato
	 	- Trabalhados
	 	- Não Trabalhados
	 	- Finalizados
	 	- Total de Telefones
	 - Campanha x Estratégia
		- Atendido
		- Ocupado
		- Não Atendido 

O dash de monitoramento, quando visualizado em **tempo real**, trará informações como:
- Conectados
- Não conectados
- Trabalhados
- Gráficos
  - Campanha
     - Trabalhados
     - Não Trabalhados
     - Finalizados
     - Total de Telefones
  - Resumo da campanha por grupo de contato
     - Trabalhados
     - Não trabalhados
     - Finalizados
     - Total de Telefones
  - Campanha x Estratégia
     - Atendido
     - Ocupado
     - Não Atendido 

![Controle Automatizado - Campanha](/imgs/campanha_tela5.png ':class=sombracaixa' )

![Controle Automatizado - Campanha](/imgs/campanha_tela6.png ':class=sombracaixa' )

### Boas Práticas


<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Broadcast

A funcionalidade da plataforma Code7 Omni traz agilidade e facilidade na criação e gerenciamento de Campanhas onde se pode criar o grupo de contatos, campanhas e estratégia de envios com monitoramento para envio de mensagens de whatsapp e SMS em massa.

São pré-requisitos para o envio de *Whatsapp*:
- Número de telefone cadastrado no Canal de Whatsapp
- Aprovação dos HSM dentro das normas geradas pelo Facebook para que as mensagens possam ser enviadas.

São pré-requisitos para o envio de *SMS*:
- Liberação de um Serviço de Entrada que será realizado por meio de chamado para que seja criado uma integração para envio.

    

### Grupo de Contatos

A criação de grupo de contatos poderá ser realizada de duas formas:
- Por meio de importação de um arquivo tipo CSV
- Por meio da importação de todos os contatos já cadastrados em sua empresa


_Grupo de Contatos_

![Tela Grupo de Contatos](/imgs/grupo_contatos_1.PNG ':class=sombracaixa' ) 

Na Tela do Grupo de Contatos, pode ser realizada Ações em Lote para Ativar ou Inativar Grupos além de Editar(ícone do lápis) ou Verificar(ícone da lupa) cada grupo já criado.


_Editar Grupo de Contatos_


![Tela Grupo de Contatos](/imgs/grupo_contatos_editar.PNG ':class=sombracaixa' ) 


_Verificar Grupo de Contatos_


![Tela Grupo de Contatos](/imgs/grupo_contatos_verificar.PNG ':class=sombracaixa' ) 

  
**Tela de Importação de Grupo de Contatos**
- Inserir Nome do Grupo de Contatos
- Optar ou por "Utilizar contatos Omni" ou "Fazer upload de arquivo"
- Salvar


_Criação de Grupo de Contatos_


![Tela Grupo de Contatos](/imgs/grupo_contatos_2.PNG ':class=sombracaixa' ) 


### Campanha

A criação de grupo de Campanhas será realizada na tela de Campanha clicando no ícone de "+" no canto superior direito da tela que levará a tela de Configurar Campanha

![Configurar Campanha](/imgs/campanha_nova.PNG ':class=sombracaixa' ) 

Na tela Configurar Campanha deverão ser preenchidos os campos:
- Campanha - com o nome da Campanha que será criada
- Canal - onde será definido se a campanha será de Whatsapp ou SMS

![Configurar Campanha](/imgs/config_campanha_1.PNG ':class=sombracaixa' ) 



* Note que a campanha já estará ativa como default no checkbox, após o preenchimento dos campos, clique em salvar.


_Para Campanha de Whatsapp_


![Configurar Campanha](/imgs/config_campanha_whats.PNG ':class=sombracaixa' ) 



_Para Campanha de SMS_


![Configurar Campanha](/imgs/config_campanha_SMS.PNG ':class=sombracaixa' ) 



### Envios

A criação de grupo dos Envios será realizada na tela de Envios clicando no ícone de "+" no canto superior direito da tela que levará a tela de Configurar Envio onde deverão ser preenchidos os campos:
- Nome do agendamento
- Agendamento - informando a Data que deverá ser realizado o envio da mensagem
- Horário - informando o horário desejado para que seja enviada mensagem
- Grupos de Contatos - selecionando na lista disponível o Grupo de Contatos, criado previamente, que será utilizado para a Campanha
- Campanha - selecionando na lista dispoínvel a Campanha criada previamente para o envio, esta campanha será de Whatsapp ou de SMS


<h3>Mensagem de Envio - para Campanhas de Whatsapp</h3>

Nas Campanhas de Whatsapp a mensagem HSM - High Structured Message. As mensagens deste tipo obedecem a uma estrutura rígida pré-aprovada pelo WhatsApp para as notificações automatizadas que você será autorizado a enviar aos usuários.
Deverá ser selecionado a HSM previamente liberada no sistema e definido quais variáveis serão utilizadas nos espaços já definidos no corpo do HSM.


_Para Envio de Whatsapp_


![Configurar Envio](/imgs/config_envio_whats.PNG ':class=sombracaixa' ) 



_Para Envio de Whatsapp_


![Configurar Envio](/imgs/config_envio_whats2.PNG ':class=sombracaixa' ) 



<h3>Mensagem de Envio - para Campanhas de SMS</h3>

Para Campanhas geradas de SMS não há restrição do texto a ser enviado e nem do posicionamento das variáveis que serão inseridas no texto clicando no "+" que fica no canto esquerdo ao lado do "Valor Variável".



_Para Envio de SMS_


![Configurar Envio](/imgs/config_envio_SMS.PNG ':class=sombracaixa' ) 


_Para Envio de SMS_


![Configurar Envio](/imgs/config_envio_SMS_2.PNG ':class=sombracaixa' ) 



### Monitoramento

Na tela de Monitoramento será apontado os resultados das Campanhas de Whatsapp ou de SMS onde poderá filtrar por:
- Data
- Canal - atualmente por Whatsapp ou SMS
- Campanha - campo obrigatório para que sejam alimentados as informações no Dash

_Monitoramento_


![Monitoramento](/imgs/monitoramento_sms_1.PNG ':class=sombracaixa' ) 



_Monitoramento_


![Monitoramento](/imgs/monitoramento_sms_2.PNG ':class=sombracaixa' ) 

<hr color="#836FFF" size = 8 width = 70% align = right noshade>

# Exportações
## Relatório de Usuários

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Relatório de Chamadas

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Relatório de Atividade

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Relatório de Broadcast - Consolidado

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Relatório de Broadcast - Detalhado

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Relatório Discador

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Relatório Broadcast Grupo de Contatos - Histórico Importação

<hr color="#836FFF" size = 3 width = 70% align = right noshade>
## Relatório Discador Grupo de Contatos - Histórico Importação

<hr color="#836FFF" size = 3 width = 70% align = right noshade>

## Pesquisa de Satisfação

<hr color="#836FFF" size = 3 width = 70% align = right noshade>







