# 🚀 Projeto Squad 6 - ProSEmpre 2025.2

Bem-vindo ao **repositório oficial do Squad 6**!  
Aqui centralizamos o desenvolvimento do desafio **Front + Back** da EJECT.  

---

## 📂 Estrutura de Branches

- **main** → Versão oficial e estável  
- **front-nome** → Branch individual de cada membro Front-end  
- **back-nome** → Branch individual de cada membro Back-end  

**Exemplo de criação de branch:**

```bash
git checkout -b front-jaco
git checkout -b back-gabriel
🔀 Acessando sua branch
Clone o repositório:

bash
Copiar código
git clone https://github.com/squad6eject/Desafio_ProSempre
cd Desafio_ProSempre
Liste as branches disponíveis:

bash
Copiar código
git branch -a
Acesse sua branch (exemplo para Jacó do Front):

bash
Copiar código
git checkout front-jaco
📤 Enviando alterações
Confirme se está na sua branch:

bash
Copiar código
git branch
Adicione os arquivos modificados:

bash
Copiar código
git add .
Faça o commit:

bash
Copiar código
git commit -m "Descrição das alterações"
Envie para o GitHub:

bash
Copiar código
git push origin front-jaco
🔄 Atualizando sua branch com a main
Para evitar conflitos, sempre faça o merge da main antes de iniciar novas alterações:

bash
Copiar código
git checkout main
git pull origin main
git checkout front-jaco   # ou sua branch
git merge main
⚠️ Resolva quaisquer conflitos que aparecerem antes de continuar.

✅ Regras do repositório
Cada membro trabalha apenas na sua branch.

Alterações prontas devem ser submetidas via Pull Request (PR) para a main.

Revisão obrigatória: O time revisa antes de aprovar o merge.

Evite commits diretos na main para manter a estabilidade.

💡 Dicas rápidas
Atualize sua branch com a main com frequência.

Use mensagens de commit claras e objetivas.

Tire dúvidas com o time antes de mudanças grandes.

