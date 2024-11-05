# **APP Troca de Telas**

> Um aplicativo Android simples para alternar entre duas telas usando um botão.

## 📱 Descrição

O **APP Troca de Telas** é um aplicativo Android que permite ao usuário alternar entre duas telas diferentes com o toque de um botão. 
O aplicativo é projetado para ser direto, com uma interface minimalista e fácil de navegar.

## 🔧 Funcionalidades

- [x] Alternar entre Tela 1 e Tela 2 ao clicar no botão
- [x] Tela com um fundo verde vibrante (#00FF26) e um design simples
- [x] Texto indicativo para identificar a tela atual

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para estrutura da interface
- [x] **TextView** para exibir o título de cada tela
- [x] **Button** para alternar entre as telas

## 🛠️ Como Rodar o Projeto

Para executar este projeto em seu ambiente de desenvolvimento local, siga os passos abaixo:

1. Clone o repositório:

    ```bash
    git clone https://github.com/Cav-lua/troca-de-telas-app.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/myapplication
│   │   │   │   ├── MainActivity.java       # Classe para a Tela 1
│   │   │   │   ├── MainActivity2.java      # Classe para a Tela 2
│   │   │   └── res
│   │   │       ├── layout
│   │   │       │   ├── activity_main.xml   # Layout da Tela 1
│   │   │       │   ├── activity_main2.xml  # Layout da Tela 2
│   │   │       ├── values
│   │   │           ├── strings.xml         # Strings usadas no app
│   │   │           ├── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do Gradle
└── README.md                               # Este arquivo
```
🎨 Design e Prototipagem
A interface foi criada com ConstraintLayout para uma organização responsiva e centralizada. A Tela 1 possui um fundo verde vibrante com um botão vermelho para alternar entre as telas, e a Tela 2 contém um botão para retornar à Tela 1.

🖥️ Telas do Aplicativo
Tela 1

A primeira tela exibe um título "Tela 1" e um botão vermelho com o texto "Trocar de Tela", que leva o usuário para a Tela 2.
![Captura de tela 2024-11-05 011731](https://github.com/user-attachments/assets/578c0209-e241-4779-a0f9-be2d33607e65)

Tela 2

Na segunda tela, o título "Tela 2" é exibido com um botão que permite retornar à Tela 1.
![Captura de tela 2024-11-05 011742](https://github.com/user-attachments/assets/717f0c7e-8705-483d-9754-29971b5137cd)

👨‍💻 Desenvolvedores
Cav-lua - Desenvolvedor - GitHub

📄 Licença
Este projeto está licenciado sob os termos da licença MIT.
