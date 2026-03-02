# Students Database - Bash + PostgreSQL

Este projeto foi desenvolvido como parte do curso **Learn Bash Scripting by Building Five Programs** do freeCodeCamp.

O objetivo é praticar **Bash scripting**, **loops**, **condições**, **funções** e **integração com PostgreSQL**, automatizando a inserção de dados em um banco de dados relacional.

---

## 🛠 Tecnologias utilizadas

- Bash
- PostgreSQL
- psql (CLI)
- Linux

---

## 📂 Estrutura do projeto

- `insert_data.sh` → Script principal que insere os dados no banco
- `courses.csv` → Lista de cursos e seus respectivos majors
- `students.csv` → Lista de estudantes
- `students.sql` → Dump do banco de dados (estrutura + dados)
- `README.md` → Documentação do projeto

---

## ⚙️ Como funciona

O script:

1. Limpa as tabelas do banco de dados
2. Lê os arquivos CSV
3. Insere:
   - Majors
   - Courses
   - Relacionamentos entre majors e courses
   - Students
4. Evita duplicações usando consultas condicionais
5. Exibe mensagens informando cada inserção realizada

---

## ▶️ Como executar

1. Certifique-se de ter o PostgreSQL instalado
2. Crie o banco de dados `students`
3. Torne o script executável:

```bash
chmod +x insert_data.sh
