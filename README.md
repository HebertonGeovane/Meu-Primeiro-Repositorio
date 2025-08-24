# 📘 Meu Primeiro Repositório

Este repositório foi criado para explicar aos alunos, de forma prática e simples, como:

- Criar uma conta no **GitHub**  
- Instalar e configurar o **Git**  
- Instalar o **Visual Studio Code (VSCode)**  
- Usar a extensão **Live Server** para visualizar páginas HTML  
- Criar seu primeiro projeto em HTML  
- Publicar o projeto no **GitHub**  

🚀 Objetivo: ajudar o aluno a dar os primeiros passos no mundo do desenvolvimento e versionamento de código.

##  Tecnologias utilizadas

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)  ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)  
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)  

---

## 1️⃣ Criando uma conta no GitHub
1. Acesse: [https://github.com](https://github.com)  
2. Clique em **Sign up** (Cadastrar).  
3. Preencha:
   - **E-mail**  
   - **Senha**  
   - **Nome de usuário** (ex: `heberton-dev`)  
   - Clique em **Create account**.  
4. Confirme seu e-mail pelo link enviado.  
5. Pronto! Conta criada 🎉

   ![image - 2025-08-24T135351 749](https://github.com/user-attachments/assets/b304d2c3-f9d8-40fd-93c1-0245384db60c)

  <img width="1892" height="961" alt="image" src="https://github.com/user-attachments/assets/f1129f97-ff64-43bd-be1e-4b7a8355af55" />


---

## 2️⃣ Instalando o Git
### 🔸 Windows
1. Acesse: [https://git-scm.com/downloads](https://git-scm.com/downloads)  
2. Clique em **Windows** e instale com as opções padrão.  
3. Após instalar, abra o **Prompt de Comando** e digite:

```
  git --version

```
4. Se aparecer algo como `git version 2.xx.x` está funcionando ✅

### 🔸 Linux (Ubuntu/Debian)

```
sudo apt update
sudo apt install git -y
git --version

```
### 🔸 macOS

```
brew install git
git --version

```

   <img width="1042" height="883" alt="image" src="https://github.com/user-attachments/assets/e18eb59f-efea-439b-8ffb-1b03b2e555b3" />

   <img width="625" height="87" alt="image" src="https://github.com/user-attachments/assets/77700149-f363-4cf5-92f9-394f93fed8fc" />

---
## 3️⃣ Instalando o VS Code

  
1. - Baixe em: https://code.visualstudio.com/
  
2. - Instale normalmente.
  
3. - Abra o VS Code.

    <img width="1894" height="953" alt="image" src="https://github.com/user-attachments/assets/21a8922c-645f-436e-ac9e-5ff049e10b83" />
---
## 4️⃣ Instalando a extensão Live Server

1. No VS Code, clique no ícone de Extensões (quadradinho à esquerda).

2. Pesquise por Live Server.

3. Clique em Install.

Agora você pode rodar qualquer arquivo HTML no navegador 🚀

<img width="797" height="87" alt="image" src="https://github.com/user-attachments/assets/5fec0d8f-0718-4b56-a449-a6e66a97dec0" />

---

## 5️⃣ Criando a pasta do projeto

1. Vá até sua Área de Trabalho.

2. Crie uma pasta chamada:

```
Meu Primeiro Repositorio

```
3. Abra a pasta no VS Code (File → Open Folder).

---

## 6️⃣ Criando o arquivo index.html

1. Dentro do VS Code, clique em New File.

Nomeie como:

```
index.html

```

Copie este código inicial para dentro do arquivo:

```

<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Meu Primeiro Repositório</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      href="https://unpkg.com/lucide-static/font/lucide.css"
      rel="stylesheet"
    />
    <!-- Fonte -->
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Poppins", sans-serif;
      }
      /* Animação de fundo */
      .bg-gradient-animate {
        background: linear-gradient(270deg, #4f46e5, #9333ea, #f59e0b, #10b981);
        background-size: 800% 800%;
        animation: gradientAnimation 15s ease infinite;
      }
      @keyframes gradientAnimation {
        0% {
          background-position: 0% 50%;
        }
        50% {
          background-position: 100% 50%;
        }
        100% {
          background-position: 0% 50%;
        }
      }
    </style>
  </head>
  <body class="bg-gradient-animate flex flex-col min-h-screen text-white">
    <!-- Header -->
    <header class="py-6 px-8 flex items-center justify-between shadow-lg">
      <h1 class="text-3xl md:text-4xl font-bold flex items-center gap-3">
        <i class="lucide-code text-yellow-400 text-4xl"></i> Meu Primeiro
        Repositório
      </h1>
    </header>

    <main
      class="flex-grow flex flex-col md:flex-row items-center justify-between px-10 py-16 gap-10"
    >
      <!-- Imagem lateral esquerda  -->
      <div class="flex-shrink-0 hidden md:block">
        <img
          src="https://cdn-icons-png.flaticon.com/512/1995/1995576.png"
          alt="Menino estudando programação"
          class="w-72 md:w-96 drop-shadow-xl"
        />
      </div>

      <!-- Texto + Lista de Habilidades -->
      <div class="max-w-2xl text-center md:text-left">
        <p class="text-2xl md:text-3xl font-medium leading-relaxed mb-12">
          Olá! 👋 Seja bem-vindo ao meu primeiro repositório. Atualmente estou
          aprendendo sobre
          <span class="font-bold text-yellow-200">Computação em Nuvem</span>,
          <span class="font-bold text-green-200">Linux</span>,
          <span class="font-bold text-purple-200">Redes</span>,
          <span class="font-bold text-red-200">Segurança da Informação</span>,
          <span class="font-bold text-yellow-300">Banco de Dados</span> e sou
          apaixonado pelo
          <span class="font-bold text-pink-200">Mundo da Programação</span>. 🚀
        </p>

        <!-- Lista de Habilidades -->
        <div class="grid md:grid-cols-2 gap-6 text-xl">
          <div
            class="flex items-center gap-4 bg-white/10 p-6 rounded-xl shadow hover:scale-105 hover:bg-white/20 transition cursor-pointer"
          >
            <img
              src="https://cdn-icons-png.flaticon.com/512/4144/4144726.png"
              alt="Nuvem"
              class="w-8 h-8"
            />
            <span>Computação em Nuvem</span>
          </div>
          <div
            class="flex items-center gap-4 bg-white/10 p-6 rounded-xl shadow hover:scale-105 hover:bg-white/20 transition cursor-pointer"
          >
            <img
              src="https://cdn-icons-png.flaticon.com/512/518/518713.png"
              alt="Linux"
              class="w-8 h-8"
            />
            <span>Linux</span>
          </div>
          <div
            class="flex items-center gap-4 bg-white/10 p-6 rounded-xl shadow hover:scale-105 hover:bg-white/20 transition cursor-pointer"
          >
            <img
              src="https://cdn-icons-png.flaticon.com/512/4230/4230569.png"
              alt="Redes"
              class="w-8 h-8"
            />
            <span>Redes</span>
          </div>
          <div
            class="flex items-center gap-4 bg-white/10 p-6 rounded-xl shadow hover:scale-105 hover:bg-white/20 transition cursor-pointer"
          >
            <img
              src="https://cdn-icons-png.flaticon.com/512/3064/3064197.png"
              alt="Segurança"
              class="w-8 h-8"
            />
            <span>Segurança da Informação</span>
          </div>
          <div
            class="flex items-center gap-4 bg-white/10 p-6 rounded-xl shadow hover:scale-105 hover:bg-white/20 transition cursor-pointer"
          >
            <img
              src="https://cdn-icons-png.flaticon.com/512/4248/4248443.png"
              alt="Banco de Dados"
              class="w-8 h-8"
            />
            <span>Banco de Dados</span>
          </div>
          <div
            class="flex items-center gap-4 bg-white/10 p-6 rounded-xl shadow hover:scale-105 hover:bg-white/20 transition cursor-pointer"
          >
            <img
              src="https://cdn-icons-png.flaticon.com/512/2721/2721291.png"
              alt="Programação"
              class="w-8 h-8"
            />
            <span>Programação</span>
          </div>
        </div>
      </div>

      <!-- Imagem lateral direita  -->
      <div class="flex-shrink-0 hidden md:block">
        <img
          src="https://cdn-icons-png.flaticon.com/512/1995/1995593.png"
          alt="Menina estudando programação"
          class="w-72 md:w-96 drop-shadow-xl"
        />
      </div>
    </main>

    <!-- Footer -->
    <footer
      class="bg-black/40 backdrop-blur-sm py-8 px-6 mt-auto flex flex-col items-center gap-6"
    >
      <div class="flex gap-8 text-3xl">
        <!-- GitHub -->
        <a
          href="https://github.com/seuusuario"
          target="_blank"
          class="transition transform hover:scale-125"
        >
          <img
            src="https://cdn-icons-png.flaticon.com/512/25/25231.png"
            alt="GitHub"
            class="w-10 h-10 hover:opacity-80"
          />
        </a>

        <!-- LinkedIn -->
        <a
          href="https://linkedin.com/in/seuusuario"
          target="_blank"
          class="transition transform hover:scale-125"
        >
          <img
            src="https://cdn-icons-png.flaticon.com/512/174/174857.png"
            alt="LinkedIn"
            class="w-10 h-10 hover:opacity-80"
          />
        </a>

        <!-- Instagram -->
        <a
          href="https://instagram.com/seuusuario"
          target="_blank"
          class="transition transform hover:scale-125"
        >
          <img
            src="https://cdn-icons-png.flaticon.com/512/174/174855.png"
            alt="Instagram"
            class="w-10 h-10 hover:opacity-80"
          />
        </a>
      </div>
      <p class="text-sm text-gray-200">© 2025 Meu Primeiro Repositório</p>
    </footer>
  </body>
</html>

```
---

## 7️⃣ Visualizando no Live Server

1. Clique com o botão direito no arquivo index.html.

2. Selecione Open with Live Server.

3. O navegador abrirá sua página 🎉


🔸 Dica:
Você pode trocar as imagens modificando apenas o número no final da URL:

```
img
          src="https://cdn-icons-png.flaticon.com/512/1995/1995576.png"

```
Modifique o código no Footer e coloque suas redes sociais no fim do código: 

```
 <a
          href="https://github.com/seuusuario"

          href="https://linkedin.com/in/seuusuario"

          href="https://instagram.com/seuusuario"
```

<img width="1917" height="993" alt="image" src="https://github.com/user-attachments/assets/3ab87998-f350-4b6c-a40f-50a344f72c42" />

<img width="1919" height="997" alt="image" src="https://github.com/user-attachments/assets/fa8a7bd0-e507-4cc7-b0ff-2515d43a4b2f" />

---

## 8️⃣ Criando o repositório no GitHub

1. Vá até https://github.com
.

2. Clique em New repository.

3. Preencha:

   - Repository name: `Meu-Primeiro-Repositorio`

   - Description: Meu primeiro projeto no GitHub

   - Marque Public

   - Clique em Create repository

<img width="1892" height="948" alt="image" src="https://github.com/user-attachments/assets/c7738347-5489-44ae-8c78-056d9f2f5e52" />


<img width="1276" height="960" alt="image" src="https://github.com/user-attachments/assets/e72b2997-1b0c-4fe7-ac65-46ddd29230d3" />


<img width="1890" height="949" alt="image" src="https://github.com/user-attachments/assets/b8ea18fa-6deb-4c2f-b428-ace4198e910f" />


<img width="1899" height="882" alt="image" src="https://github.com/user-attachments/assets/f9ce7c98-a5ba-4b39-9681-7bbde30f6075" />

---

## 9️⃣ Configurando o Git no VS Code

Vá em Terminal New Terminal , No terminal do VS Code (Ctrl+`), ao lado do sinal de " + " seta para baixo " escolha Git Bash execute :

   - Configurar usuário e e-mail

  ```
   git config --global user.name "Seu Nome"

  ```

  ```
   git config --global user.email "seuemail@gmail.com"

  ```

Agora vamos iniciar o GIt projeto você pode seguir as instruções da tela do Github 

```
git init

```

```
git status

```

```
git add .

```

```
git status

```

```
git commit -m "first commit"

```
<img width="323" height="132" alt="image" src="https://github.com/user-attachments/assets/0bbb8d0d-9e17-4df3-96e8-e268ab58b286" />

<img width="1532" height="805" alt="image" src="https://github.com/user-attachments/assets/cc762984-9426-4791-a751-e230db17ec8d" />

<img width="1535" height="792" alt="image" src="https://github.com/user-attachments/assets/1f6931d6-8f8e-497a-baaa-cc5dc79c29c5" />

---

## 🔟 Enviando o projeto para o GitHub

No GitHub, copie o endereço HTTPS do repositório (ex: https://github.com/seunome/Meu-Primeiro-Repositorio.git).
No terminal do VS Code, cole:

```
git branch -M main

```

```
git remote add origin https://github.com/seunome/Meu-Primeiro-Repositorio.git

```

```
git push -u origin main

```

<img width="1303" height="345" alt="image" src="https://github.com/user-attachments/assets/d0a419a7-27ae-4b25-a096-7e8a18f60ca3" />

obs: se der esse erro no final Conferir qual usuário está configurado no Git 

git config --global user.name

git config --global user.email

Isso mostra a conta configurada no Git.

Atualizar usuário e e-mail do Git

git config --global user.name "Seu Nome"

git config --global user.email "seuemail@gmail.com"

tente Novamente o git push -u origin main

## Agora o Git vai pedir login novamente.

Usuário → `heberton-dev`  < seu usuário

Senha → cole o token de acesso pessoal (PAT) da conta heberton-dev
(não é a senha do GitHub, é o token que você gera em Settings → Developer settings → Personal access tokens → Tokens classic → Generate new token com permissão repo).

<img width="1032" height="464" alt="image" src="https://github.com/user-attachments/assets/b4cba43a-fb3a-4965-86d5-01f9e9a4a860" />

<img width="1893" height="948" alt="image" src="https://github.com/user-attachments/assets/65021810-4ac3-470f-9579-04180cc2a5d9" />

<img width="1899" height="931" alt="image" src="https://github.com/user-attachments/assets/4d89d3f6-e9dd-4d66-a704-b280f01bd7a5" />

<img width="1902" height="673" alt="image" src="https://github.com/user-attachments/assets/9484eb15-2e8d-496e-abbb-612788b0fd21" />

<img width="1182" height="640" alt="image" src="https://github.com/user-attachments/assets/797d6b8a-f2e2-42dd-96be-85345626a84d" />

<img width="1895" height="953" alt="image" src="https://github.com/user-attachments/assets/78f3455f-db0e-44c8-887f-31e1e5330fa5" />

<img width="379" height="73" alt="image" src="https://github.com/user-attachments/assets/c9cb9236-dbc1-47e1-8b3a-b7804214fa1a" />

copiar o Token 

```
git push -u origin main

```

colar o token

<img width="1092" height="439" alt="image" src="https://github.com/user-attachments/assets/0c1713b3-6fdf-4c1c-bdd1-be7ebee06d5b" />

<img width="1264" height="357" alt="image" src="https://github.com/user-attachments/assets/6724f3d4-93a4-427a-afe9-5b2f221a358a" />

## ✅ Pronto!

Seu projeto agora está:

   - Rodando no navegador pelo Live Server

   - Publicado no GitHub 🎉

<img width="1901" height="955" alt="Captura de tela 2025-08-24 162158" src="https://github.com/user-attachments/assets/8a4ca173-2423-41b5-a454-e7f60e8fa0a2" />


## ✍️ Dica extra para o aluno:
Depois que seu projeto estiver no GitHub, compartilhe o link com os colegas e mostre que você já deu seu primeiro passo como desenvolvedor!

## ✅ O que aprendemos hoje
- Criar uma conta no GitHub  
- Instalar e configurar o Git  
- Instalar o VSCode e a extensão Live Server  
- Criar um projeto simples em HTML  
- Alterar imagens e links no código  
- Criar um repositório no GitHub  
- Configurar o Git e enviar os arquivos com commit e push  
- Gerar e usar um Token de acesso para autenticar no GitHub  

---

## 🧑‍🏫 Projeto criado por
**Heberton Geovane**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heberton-geovane/)  



