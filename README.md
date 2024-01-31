Projeto Front-end
Aulas da Trilha Alura Front end do zero
Git comandos:
Para criar um repositório local no seu computador e depois vinculá-lo a um repositório no GitHub, você pode seguir os passos básicos listados abaixo. Certifique-se de ter o Git instalado no seu computador antes de começar.

1. **Instalar o Git:**
   Se você ainda não tiver o Git instalado, faça o download e instale-o em seu computador. Você pode encontrar o Git em [https://git-scm.com/](https://git-scm.com/).

2. **Configurar seu nome de usuário e endereço de e-mail:**
   Execute os seguintes comandos para configurar seu nome de usuário e endereço de e-mail no Git. Substitua "Seu Nome" e "seu.email@example.com" com suas próprias informações.

   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seu.email@example.com"
   ```

3. **Criar um novo diretório para o projeto:**
   Vá para o diretório onde você deseja criar o novo projeto e execute o seguinte comando para criar um novo diretório:

   ```bash
   mkdir nome_do_seu_projeto
   cd nome_do_seu_projeto
   ```

4. **Iniciar um repositório Git local:**
   Execute o seguinte comando para iniciar um repositório Git local no seu projeto:

   ```bash
   git init
   ```

5. **Criar um arquivo README.md (opcional):**
   Crie um arquivo README.md para fornecer informações sobre o seu projeto. Isso é opcional, mas é uma prática comum incluir um arquivo README para descrever o propósito e o funcionamento do seu projeto.

   ```bash
   touch README.md
   ```

   Em seguida, abra o arquivo README.md em um editor de texto para adicionar conteúdo.

6. **Adicionar arquivos ao repositório local:**
   Adicione os arquivos ao repositório local usando o seguinte comando. Este comando adiciona todos os arquivos no diretório ao controle de versão.

   ```bash
   git add .
   ```

7. **Criar um commit inicial:**
   Faça o primeiro commit para o repositório usando o seguinte comando. Substitua "Mensagem do commit inicial" por uma mensagem descritiva para o seu commit.

   ```bash
   git commit -m "Mensagem do commit inicial"
   ```

8. **Criar um repositório no GitHub:**
   Vá para o GitHub e crie um novo repositório. Copie o URL do repositório.

9. **Vincular o repositório local ao repositório remoto no GitHub:**
   Use o comando `git remote add` para vincular o repositório local ao repositório no GitHub. Substitua `<URL_DO_REPOSITORIO>` pelo URL que você copiou anteriormente.

   ```bash
   git remote add origin <URL_DO_REPOSITORIO>
   ```

10. **Enviar o código para o GitHub:**
   Finalmente, envie o código para o GitHub usando o comando `git push`. Isso enviará o código do seu repositório local para o repositório remoto no GitHub.

    ```bash
    git push -u origin master
    ```

Agora, seu repositório local está vinculado ao repositório remoto no GitHub. Certifique-se de substituir "nome_do_seu_projeto" e outros valores pelos apropriados para o seu projeto.
