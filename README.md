# 🚀 Projeto Squad 6 - ProSEmpre 2025.2

Bem-vindo ao **repositório oficial do Squad 6**!  
Aqui centralizamos o desenvolvimento do desafio **Front + Back** da EJECT.  

---

## 📂 Estrutura de Branches

- **main** → Versão oficial e estável  
- **front-nome** → Branch individual de cada membro Front-end  
- **back-nome** → Branch individual de cada membro Back-end  

🔀 Acessando sua branch
Clone o repositório:
````
git clone https://github.com/squad6eject/Desafio_ProSempre
cd Desafio_ProSempre
````
Liste as branches disponíveis:
````
git branch -a
````
Acesse sua branch (exemplo para Jacó do Front):
````
git checkout front-jaco
````
📤 Enviando alterações
Confirme se está na sua branch:

````
git branch
````
Adicione os arquivos modificados:
````
git add .
````
Faça o commit:
````
git commit -m "Descrição das alterações"
````
Envie para o GitHub:
````
git push origin front-jaco
````
🔄 Atualizando sua branch com a main
Para evitar conflitos, sempre faça o merge da main antes de iniciar novas alterações:
````
git checkout main
git pull origin main
git checkout front-jaco   # ou sua branch
git merge main
````
⚠️ Resolva quaisquer conflitos que aparecerem antes de continuar.

✅ Regras do repositório
- Cada membro trabalha apenas na sua branch.

- Alterações prontas devem ser submetidas via Pull Request (PR) para a main.

- Revisão obrigatória: O time revisa antes de aprovar o merge.

- Evite commits diretos na main para manter a estabilidade.

💡 Dicas rápidas
- Atualize sua branch com a main com frequência.

- Use mensagens de commit claras e objetivas.

- Tire dúvidas com o time antes de mudanças grandes.

