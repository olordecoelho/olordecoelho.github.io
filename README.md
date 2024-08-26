## olordecoelho.com

Site estático com blog criado com Zola.

* **Versão:** 0.1.0
* **Autor:** Daniel Coelho
* **Licença:** MIT
* **Repositório:** [https://github.com/olordecoelho/olordecoelho.github.io](https://github.com/olordecoelho/olordecoelho.github.io)
* **Palavras-chave:** zola, ssg, tailwindcss, tailwind, rust, static

### Como contribuir

Este projeto recebe de braços abertos contribuições da comunidade! Se você deseja corrigir um erro, adicionar um novo recurso ou melhorar a documentação, siga estas etapas:

1. **Crie um Fork do Repositório:**

   * Acesse o repositório no GitHub: [https://github.com/olordecoelho/olordecoelho.github.io](https://github.com/olordecoelho/olordecoelho.github.io)
   * Clique no botão "Fork" no canto superior direito da página. Isso criará uma cópia do repositório em sua própria conta do GitHub.

2. **Clone o seu Fork:**

   * Copie a URL do seu fork (ela estará na sua conta do GitHub).
   * Abra seu terminal e execute o seguinte comando, substituindo `<sua-url-do-fork>` pela URL copiada:

     ```bash
     git clone <sua-url-do-fork>
     ```

3. **Navegue até a pasta do projeto e instale as dependências:**

   ```bash
   cd olordecoelho.github.io
   npm install
   ```

4. **Desenvolvimento:**

   * Dê permissão de execução ao usuário e execute o script `./zola serve`:

     ```bash
     sudo chmod +x zola 
     ./zola serve
     ```

   * Agora você pode modificar o projeto e vê-lo acontecendo em tempo real no seu navegador, geralmente em `http://127.0.0.1:1111`.

5. **Crie uma Branch para sua Feature/Correção:**

   * Crie uma nova branch para isolar suas alterações:

     ```bash
     git checkout -b minha-feature 
     ```

6. **Faça suas Alterações:**

   * Modifique o código-fonte, adicione novos arquivos, etc.

7. **Commit e Push:**

   * Adicione seus arquivos modificados:

     ```bash
     git add .
     ```

   * Faça o commit com uma mensagem descritiva:

     ```bash
     git commit -m "Adicionando nova feature X"
     ```

   * Envie suas alterações para o seu fork no GitHub:

     ```bash
     git push origin minha-feature
     ```

8. **Abra um Pull Request:**

   * Acesse seu fork no GitHub.
   * Você verá um botão "Compare & pull request". Clique nele.
   * Preencha o formulário com uma descrição clara das suas alterações.
   * Envie o pull request!

### Lista de Tarefas (TODO)

* **Autenticação:**
    * Criar sistema de login e registro com autenticação por email.
    * Integrar login com Google e outras redes sociais.
* **Interação com Usuários:**
    * Adicionar sistema de comentários nos blogposts.
    * Criar uma página de fórum para discussões.
* **Qualidade:**
    * Criar testes automatizados para garantir o funcionamento correto do site.
* **Outras Melhorias:**
    * Adicionar funcionalidade de busca no site.
    * Melhorar a acessibilidade do site.
    * Otimizar o desempenho do site.

**Observações:**

* Esta é apenas uma lista inicial de tarefas. Sinta-se à vontade para sugerir novas ideias ou contribuir com outras melhorias!
* Antes de começar a trabalhar em uma tarefa, é recomendável abrir uma issue no repositório para discutir a implementação e evitar conflitos com outros contribuidores.

**Esperamos suas contribuições!** 
