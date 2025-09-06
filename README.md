# 🚀 Projeto Squad 6 - ProSEmpre 2025.2

Bem-vindo ao repositório oficial do **Squad 6**!  
Aqui organizamos nosso trabalho para o desafio **Front + Back** da EJECT.

---

## 📌 Estrutura de Branches

- `main` → versão oficial e estável do projeto  
- `front-nome` → branches individuais para cada membro do **Front-end**  
- `back-nome` → branches individuais para cada membro do **Back-end**

Exemplo:  
```bash
git checkout -b front-jaco
git checkout -b back-gabriel

🔀 Como acessar sua branch

Clone o repositório:

git clone https://github.com/squad6eject/Desafio_ProSempre
cd Desafio_ProSempre


Liste as branches disponíveis:

git branch -a


Acesse sua branch (exemplo para Jacó do Front):

git checkout front-jaco

📤 Como enviar alterações

Confirme se está na sua branch:

git branch


Adicione os arquivos modificados:

git add .


Faça o commit:

git commit -m "Descrição das alterações"


Envie para o GitHub:

git push origin front-jaco

📥 Como atualizar sua branch com a main

Para evitar conflitos, antes de começar algo novo:

git checkout main
git pull origin main
git checkout front-jaco   # ou sua branch
git merge main

✅ Regras do repositório

Cada membro trabalha apenas na sua branch.

Alterações que já estão prontas para o projeto oficial devem ser feitas por Pull Request (PR) para a main.

Revisão será feita pelo time antes de aprovar o merge.
