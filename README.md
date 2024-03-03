WorkoutMaster Web

É um web site sobre treinamentos, no qual o usuário possui uma rotina de treinamento associada a ele, e que pode ser editada. E caso possua dúvidas sobre execução de exercicios ou alongamentos pode conferir como realiza-los na aba de exercicios ou alongamentos correspondentes. 

Em caso de dúvidas mais especificas o usuário podera consultar um chatBot interno do web site para suprir suas dúvidas.

Escopo:

- Site de treino, com login de usuário e admin;
- Cada usuário tem uma rotina de treino associada a ele;
- O usuário pode editar, criar e excluir sua rotina de treino; 
- O site tem um menu com Home, exercícios, alongamentos, meu treino, Ajuda e login.
- O login conterá uma imagem do usuário, se clicar na imagem será redirecionado para os seus dados (Nome, Email, cpf, dt nacimento), que podem ser editados pelo usuário. 
- Ao criar um usuário novo, será encaminhado um email de verificação para garantir a autenticidade daquele usuário. 
- Os exercícios devem ter um dropdown contendo peito, costas, ombros, bíceps, tríceps, pernas e gerais, e os alongamentos devem ter um dropdown contendo peito, costas, ombros, bíceps, tríceps, pernas e gerais. Aonde cada opção leva aos exercícios ou alongamentos associados. 
- O admin pode editar os exercícios e alongamentos, além de criar e excluir novos.  
- A parte de “Ajuda” conterá um Chat Bot para tirar dúvidas que os usuários possam vir a ter sobre treinamento. 
- Se o usuário não estiver logado e acessar meu treino ele será redirecionado para a pagína de login. 

📋 Pré-requisitos
- Instalar o React e python
- Instalar a OpenAi
- Instalar o ChromaDB


🔧 Instalação

- Comando para instalar a Api da OpenAi: pip install openai
- Comando para instalar o ChromaDB: pip install chromadb

🛠️ Construído com

React - Para desenvolver o front end
Python - Utilizado para o backend, e para configurar a Api.
OpenAi - Sera configurada a api para criar um chatbot sobre dúvida de treinos.
ChromaDb - Sera utilizado como banco de dados vetorial para uso da Api. 
Mongodb - Banco de dados utilizado.

✒️ Autores

Marlon de Souza. 


