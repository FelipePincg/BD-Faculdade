# BD-Faculdade
Banco de Dados para gerenciamento de uma Faculdade
Objetivo do Banco de dados.
Realizar controle centralizado de alunos, professores, cursos, disciplinas, histórico escola e turmas.

Fases do Projeto
Fases:
- Levantameno de Requisitos
- Identificação de Entidades e Relacionamentos
- Modelo E-R
- Diagrama E-R
- Dicionário de Dados
- Normalização
- Implementação
- Teste Básico

##Levantamento de Requisitos
- Um aluno só pode estar matriculado em um curso por vez.
- Alunosd possuem um código de identificação(RA).
- Cursos são compostos por disciplinas.
- Cada disciplina terá no mámixo 30 alunos por turma.
- As disciplinas podem ser obrigatórias ou optativas, dependendo do curso.
- As disciplinas pertencem a departamentos específicos.
- Cada disciplina possui um código de identificação.
- Alunos podem trancar matrícula ,não estando então matriculado em nenhuma disciplina no semestre.
- Em cada semestre, cada aluno pode se matricular  em no máximo 9 disciplinas.
- O aluno só pode ser reprovado no máximo 3 vezes na mesma disciplina.
- A faculdade terá  no mámixo  3000 alunos  matriculados simultaneamente, em 10 curos distintos.
- Entram 300 alunos novos por ano.
- Existem 90 disciplinas no total disponíveis.
- Histórico escolar traz todas as disciplinas cursadas por um aluno, incluindo nota final, frequência e período do curso realizado.
- Professores podem ser cadastrados  mesmo sem lecionar disciplinas
- Existem 40 professores trabalhando na escola.
- Cada professor irá lecionar no máximo 4 disciplinas diferentes.
- Cada professor é vinculado a um departamento.
- Professores são identificados por um código de professor.
