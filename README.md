# Projeto Final #
-PC3- Engenharia-de-Software -Psicologia-da-educação-
=====================================================
Integrantes do Grupo:
- Arthur Daniel Ribeiro Pereira Dantas Lourenço
- Danilo Moraes Borges Piquiá
- Matheus Oliveira Gouveia Campos

=====================================================

SOBRE O PROJETO:
📌 Projeto: Plataforma de RPG Educacional
. Descrição Geral

Um sistema web onde professores podem criar quests (atividades, exercícios, testes) e alunos criam personagens que evoluem conforme realizam essas atividades. 
A cada atividade concluída, o aluno ganha XP, moedas virtuais e itens. Há um ranking por turma que mostra a evolução dos jogadores.

. Atores

-->Professor
-Cria e gerencia quests.
-Visualiza progresso dos alunos.
-Configura recompensas.

-->Aluno
-Cria personagem.
-Realiza quests.
-Ganha XP, moedas, itens.
-Consulta ranking.

-->Sistema
-Valida respostas.
-Calcula pontuação, nível, ranking.
-Armazena dados de progresso.

. Entidades Principais

Usuário (atributos: id, nome, email, senha, tipo [aluno/professor])
Personagem (atributos: id, nome, nível, XP, moedas, itens)
Quest (atributos: id, título, descrição, tipo [pergunta múltipla, dissertativa, tarefa], XP, recompensa)
Recompensa (atributos: id, nome, tipo [item, moeda, bônus], valor)
Turma (atributos: id, nome, código de acesso, professor, lista de alunos)

. Requisitos Funcionais

O sistema deve permitir cadastro e login de usuários (aluno/professor).
O aluno deve poder criar e personalizar seu personagem.
O professor deve poder criar quests com título, descrição, tipo, XP e recompensas.
O aluno deve poder responder quests e receber XP/recompensas automaticamente.
O sistema deve atualizar o nível do personagem com base no XP acumulado.
O sistema deve manter um ranking de alunos por turma.
O professor deve poder visualizar relatórios de desempenho dos alunos.
O sistema deve armazenar o histórico de quests concluídas por aluno.

. Requisitos Não Funcionais

A aplicação deve ser web responsiva (funcionar em desktop e mobile).
O sistema deve utilizar autenticação segura (hash de senha).
O banco de dados deve garantir integridade dos dados (ex.: não permitir XP negativo).
A interface deve ser amigável e intuitiva, com elementos de gamificação.
O sistema deve suportar no mínimo 50 usuários simultâneos sem degradação significativa de performance.

. Casos de Uso (Resumo)

UC1 – Cadastrar usuário: aluno/professor cria conta.

UC2 – Criar personagem: aluno define nome/visual.

UC3 – Criar quest: professor cadastra atividade.

UC4 – Responder quest: aluno responde e recebe XP.

UC5 – Atualizar ranking: sistema recalcula posições.

. Diferenciais (para Psicologia da Educação)
Reforço positivo → XP, itens e conquistas funcionam como motivadores.
Autonomia do aluno → ele gerencia seu personagem e sente progresso.
Aprendizagem engajada → quests tornam o conteúdo em desafios.
Competição saudável → ranking estimula desempenho, mas pode ter modo cooperativo (ex.: turmas vs. “chefões”).
 . Organização Inicial

--> Quais páginas o sistema terá (fluxo principal).

-Login / Cadastro

-Dashboard do Aluno (personagem, XP, quests disponíveis)

-Dashboard do Professor (criar quests, ver progresso)

-Ranking da Turma

->Página de Quest (responder atividade)
IDEIA INICIAL:
-Aluno cria personagem,
-Professor cria quest,
-Aluno responde quest e ganha XP,
-Ranking atualiza.

. Protótipo das Telas

Antes de programar, iremos desenhar as telas:

-Figma ou Canva
