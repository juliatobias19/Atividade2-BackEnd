# Atividade2-BackEnd

*Scripts SQL de Inserção*
=====================================================================
👨‍🎓 Inserção dos Alunos

INSERT INTO aluno (id, nome, data_nascimento) VALUES

(1, 'João Silva', 20050115),

(2, 'Maria Souza', 20040923),

(3, 'Pedro Lima', 20050708);

=====================================================================

👩‍🏫 Inserção do Professor

INSERT INTO professor (id, nome, data_nascimento) VALUES

(1, 'Ana Paula', 19800530);

=====================================================================

📘 Inserção da Matéria

INSERT INTO materia (id, nome, id_professor) VALUES

(1, 'Matemática', 1);

=====================================================================

🧾 Inserção das Provas

INSERT INTO provas (id_aluno, id_materia, nota, data_da_prova) VALUES

(1, 1, 8.5, '2025-04-01'),

(2, 1, 7.0, '2025-04-01'),

(3, 1, 9.2, '2025-04-01');

