**Documento de Requisitos -- Sistema Registrador Acadêmico**

Participantes do Projeto: Rafael de Paula, Gabriel Troni e Renan Machado

Cliente: Rhadija Dib

**Objetivo do Sistema**

O cliente deseja desenvolver um programa em Python que auxilie
estudantes a organizarem seu desempenho acadêmico. O sistema deve
permitir registrar matérias, lançar notas e faltas, e consultar
informações de desempenho acadêmico como média, faltas restantes e nota
mínima necessária para aprovação.

**Levantamento de Requisitos**

Os requisitos deste sistema foram levantados a partir de uma reunião com o cliente, na qual foram discutidas as principais necessidades dos estudantes em relação à organização de suas matérias, notas e faltas. 
O objetivo identificado foi oferecer uma forma clara de acompanhamento.
Dessa forma permitindo que os alunos se programem melhor durante o semestre, visualizando quantas faltas ainda podem ter e qual nota precisam alcançar nas próximas avaliações.


**Requisitos Funcionais**

RF1: O sistema deve exibir um menu principal com as funcionalidades
disponíveis.  
(Prioridade: Alta)

RF2: O sistema deve permitir registrar novas matérias.  
(Prioridade: Alta)

RF3: O sistema deve permitir adicionar notas a uma matéria específica.  
(Prioridade: Alta)

RF4: O sistema deve permitir adicionar faltas a uma matéria
específica.  
(Prioridade: Alta)

RF5: O sistema deve calcular e exibir a média atual de cada matéria.  
(Prioridade: Alta)

RF6: O sistema deve informar a nota mínima necessária na próxima prova
para alcançar a média desejada.  
(Prioridade: Média)

RF7: O sistema deve exibir quantas faltas restantes o aluno pode ter
antes da reprovação por presença.  
(Prioridade: Média)

**Requisitos Não Funcionais**

Não definidos ainda.

**Objetivos Futuros**

• Implementar persistência de dados em arquivos.

• Realizar cálculos adicionais com médias (ex.: transferência de curso).

•	Adicionar alertas automáticos (ex.: risco de reprovação por faltas). 

**Descrição Textual de Casos de Uso**

O estudante inicia o sistema e é apresentado a um menu com as opções disponíveis. Ele pode escolher, por exemplo, cadastrar uma nova matéria. Ao selecionar essa opção, o sistema solicita que informe o nome da disciplina, a média necessária para aprovação, o limite de faltas permitidas e o número total de provas. Após fornecer essas informações, a matéria é registrada e fica disponível para consultas e atualizações.
Mais tarde, o estudante pode retornar ao sistema e escolher lançar uma nova nota em determinada disciplina. O sistema solicita o nome da matéria, e, caso ela já esteja cadastrada, pede a nota a ser inserida.
De forma semelhante, o aluno pode registrar faltas em uma matéria. O sistema pergunta qual disciplina deseja atualizar e quantas faltas devem ser adicionadas. Ao receber a informação, o sistema consulta a quantidade de faltas permitidas na matéria selecionada, soma as faltas ao total já existente e confirma a operação.
Além de cadastrar informações, o estudante pode utilizar o sistema para consultas. Ele pode, por exemplo, solicitar a média atual de uma disciplina. Nesse caso, o sistema identifica as notas já registradas, realiza o cálculo e apresenta a média. Se o aluno quiser planejar suas próximas provas, pode consultar qual nota precisa tirar para alcançar a média de aprovação. O sistema calcula esse valor com base nas notas já lançadas e no número de provas restantes.
O estudante também pode verificar quantas faltas ainda pode ter em determinada matéria antes de atingir o limite máximo permitido. O sistema compara o total de faltas já registradas com o limite estabelecido no cadastro e informa o valor restante.
O estudante tem a possibilidade também de calcular com base nas suas notas e faltas registradas nas matérias se é viável a transferência de curso. O sistema após receber os dados necessários, opera o cálculo e exibe ao usuário o resultado.
Quando o estudante não deseja mais utilizar o sistema, ele seleciona a opção de sair. O sistema encerra a execução, finalizando a sessão.
