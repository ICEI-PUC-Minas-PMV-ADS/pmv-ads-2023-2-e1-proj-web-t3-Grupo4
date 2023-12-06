# Especificação do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 1 </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px"> Usuários que necessitam de planejamento da escala de trabalho </td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td> Organizar agenda conciliando trabalho e vida pessoal </td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 2 </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px"> Usuários autônomos que trabalham por escala </td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td> Organizar agenda de trabalho conciliando diversos dias trabalhados </td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 3 </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px"> Usuários que necessitam planejar escala de trabalho com outros projetos </td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td> Organizar agenda de trabalho em escala com outros projetos, por exemplo: Trabalho extra, viagem, ir ao médico. </td>
</tr>
</tbody>
</table>


## Histórias de Usuários


|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|---------------------------|----------------------------------|
| Médico             | Planejamento de Consultas e Compromissos                       | Os médicos podem agendar procedimentos médicos e cirúrgicos para dias em que não estejam de plantão, minimizando interrupções em sua agenda de trabalho a visualização clara das escalas. Também permite que eles possam se preparar mentalmente e fisicamente para os plantões, garantindo que estejam bem descansados e prontos para lidar com os desafios do trabalho. Além disso, os médicos podem coordenar melhor a colaboração com colegas e equipes de saúde, sabendo quando estão disponíveis para discussões, reuniões e procedimentos conjuntos.                              |
| Enfermeiro                | Descanso Adequado                      | O trabalho de um enfermeiro pode ser fisicamente exigente e mentalmente desafiador. Com uma agenda de folgas organizada, pode garantir que tenham tempo suficiente para descansar e se recuperar entre os turnos, tendo em vista que o enfermeiro possui mais de um trabalho e que também funcionam em esquema de trabalho por plantões.                             |
| Téc. de laboratório               | Visualizar com mais clareza os dias em que estarei de plantão                     | A incerteza em relação às escalas de folgas pode contribuir para o estresse. Uma visualização clara ajuda a eliminar essa incerteza, reduzindo o estresse e a ansiedade associados.                              |
| Segurança               | Muitas vezes meu trabalho envolve turnos irregulares, incluindo noites, fins de semana e feriados trabalhando. Isso pode dificultar a criação de uma rotina consistente e afetar o equilíbrio entre o trabalho e a vida pessoal, preciso de algo que ajude a gerenciar esta parte com mais eficácia.                      | As escalas de folgas claras em sua demonstração, permitem que seja equilibrado melhor o tempo gasto no trabalho com o tempo dedicado à família, amigos, hobbies e atividades de lazer. Isso contribui para saúde mental e bem-estar geral.                             |
| Bombeiro                | Poder planejar dias de trabalho extra, podendo inserir mais plantões dentro de escalas de trabalha/ Aceitação de Turnos Extras.                      | Saber com antecedência quando estará de folga permite que os bombeiros planejem seus gastos e orçamentos de acordo com seus períodos de trabalho e descanso.                            |
| ...                | ...                       | ...                              |

## Requisitos do Projeto

1. Médica – Permitir a adequada programação de escalas de trabalho intermitentes, oferecendo além de uma maior tranquilidade na preparação para procedimentos clínicos e/ou cirúrgicos, mas também permitindo o planejamento de plantões entre outras necessidades;

2. Enfermeiro – Focar na recuperação do estado físico-mental ao trazer a possibilidade da organização de momentos de folga, visando o maior aproveitamento destes, considerando a possiblidade de dupla jornada e jornadas extras;

3. Tec. Laboratório – Controle dos níveis de estresse e ansiedade por meio do oferecimento da possibilidade de uma previsão clara e confiável das escalas de folga e descanso;

4. Segurança – Proporcionar maior bem-estar e saúde mental ao trazer uma visualização clara e objetiva das escalas de folga e descanso, a fim do seu melhor aproveitamento e escalonamento entre família e amigos;

5. Bombeiro – Trazer uma previsão confiável dos períodos de folga e trabalho, possibilitando assim um melhor controle financeiro para os dois períodos.

### Requisitos Funcionais


|ID    | Descrição                | Prioridade |
|-------|---------------------------------|----|
| RF-01 | Deve ser permitido ao usuário individual fazer Login com usuário e senha em tela inicial. Na mesma tela deverá constar opção para troca ou recuperação de senha.                  | Alta   | 
| RF-02 |  O usuário interessado no site deve cadastrar sua jornada de horas, escala de trabalho e dia inicial de escala, para que o sistema faça a contabilização dos posteriores dias de trabalho/folga. Esses dados devem ser atualizados periodicamente a cada 6 meses.                   | Alta   |
| RF-03 |  Com esses dados o usuário poderá montar sua agenda, podendo ser atualizada a qualquer momento dependendo da sua necessidade e de seus compromissos.                   | Média   |
| RF-04 |  Com a agenda pronta, o usuário pode ir à barra de pesquisa e buscar uma data em que precise marcar um compromisso para ver se ele terá folga naquele dia ou mês.                    | Baixa   |
|  ...  |  ...                    | ...   |


**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais


|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 |  O sistema deve ser projetado de forma modular, permitindo a fácil substituição ou atualização de componentes individuais no futuro.                  | Alta   | 
| RNF-02 |  O tempo de resposta para qualquer ação do usuário não deve exceder 2 segundos.                   | Média   |
| RNF-03 |  A taxa de disponibilidade do sistema deve ser de pelo menos 99,9%.                   | Baixa   |
| RNF-04 |  O sistema deve conter opções de acessibilidade e ser inclusivo para todo tipo de público.                    | Média   |
| RNF-05 |  O sistema deve apresentar uma fácil linguagem e ser intuitivo, com opções simples e autoexplicativas.                    | Alta   |
| RNF-06 |  As informações relevantes, como os resultados das pesquisas, datas atípicas (ex. feriados) devem ser apresentadas em destaque, com algum tipo de configuração (cor, fontes etc.) que chame a atenção do usuário.                   | Alta   |
| RNF-07 |  O programa deve apresentar um calendário com preferência de filtros para o usuário.                  | Baixa   |
| RNF-08 |  O programa deve apresentar um design/layout limpo e elegante.                   | Alta   |
| RNF-09 |  O sistema deve conter uma opção de compartilhamento de informações, podendo exportar dados para outros tipos de formatos de arquivo e programas de organização e calendário, como Microsoft Excel e Google Agenda (exemplos).                   | Baixa   |

**Prioridade: Alta / Média / Baixa. 

