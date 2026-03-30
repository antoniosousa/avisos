### 🟢 Fase 1: Setup e Ambiente (A Fundação)
* [ ] **Task 01:** Configurar o Ambiente Virtual (`venv`) e instalar o Django.
* [ ] **Task 02:** Criar o projeto Django (ex: `config`) e o app do sistema (ex: `mural`).
* [ ] **Task 03:** Registrar o app no `INSTALLED_APPS` dentro do `settings.py`.
* [ ] **Task 04:** Realizar o primeiro `migrate` para criar o banco de dados inicial (SQLite).

### 🔵 Fase 2: O Coração dos Dados (Models)
* [ ] **Task 05:** Criar o modelo `Aviso` com campos: `titulo`, `conteudo`, `categoria` (usando `choices`) e `data_criacao`.
* [ ] **Task 06:** Gerar e aplicar as migrações (`makemigrations` e `migrate`).
* [ ] **Task 07:** Registrar o modelo no `admin.py` para testar a inserção de dados via painel administrativo do Django.

### 🟡 Fase 3: Estrutura Visual (Templates & Static)
* [ ] **Task 08:** Configurar a pasta `templates/` e o caminho `TEMPLATES` no `settings.py`.
* [ ] **Task 09:** Criar o `base.html` com o esqueleto HTML5 e os blocos de conteúdo (`{% block content %}`).
* [ ] **Task 10:** (Opcional/Estética) Configurar a pasta de arquivos estáticos (`static/`) para CSS/Imagens.

### 🟠 Fase 4: Funcionalidades Principais (Views & URLs)
* [ ] **Task 11:** Criar a View de Listagem (Página Inicial) que busca todos os avisos do banco.
* [ ] **Task 12:** Mapear a URL da Home no arquivo `urls.py`.
* [ ] **Task 13:** Criar a View de Detalhes para exibir um aviso individual via ID (Primary Key).
* [ ] **Task 14:** Implementar a lógica de criação de avisos (View para exibir o formulário e salvar o `POST`).

### 🔴 Fase 5: Refinamento e UX (User Experience)
* [ ] **Task 15:** Implementar a herança de templates em todas as páginas (`{% extends %}`).
* [ ] **Task 16:** Adicionar links de navegação (ex: clicar no título do aviso para ir aos detalhes).
* [ ] **Task 17:** Validar os formulários (garantir que campos obrigatórios não fiquem vazios).
* [ ] **Task 18:** (Desafio) Implementar um filtro simples por categoria na página inicial.

### ⚪ Fase 6: Finalização
* [ ] **Task 19:** Revisar o código seguindo boas práticas (nomes de variáveis, organização).
* [ ] **Task 20:** Gerar o arquivo `requirements.txt`.

---

### 💡 Dica Pedagógica:
Você pode pedir aos seus alunos que utilizem o **Trello**, **GitHub Projects** ou até um quadro físico para moverem essas tarefas de "To Do" para "Done". Isso ajuda muito na percepção de progresso deles!

Deseja que eu detalhe o código técnico de alguma dessas Tasks especificamente?