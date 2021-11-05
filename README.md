### Boas vindas ao repositório do projeto Ebytr!

#### Descrição:

Este repositório faz parte de um desafio técnico proposto pela empresa (fictícia) Ebytr.

A empresa Ebytr está passando por problemas de produtividade/controle porque as pessoas colaboradoras vêm tendo dificuldade na organização de suas tarefas individuais. Por esse motivo, a diretora de produto, decidiu implantar uma nova forma de organizar as tarefas, desenvolvendo um sistema capaz de auxiliar as pessoas colaboradoras a se organizar e ter mais produtividade.

Como o time de desenvolvimento utiliza a Stack MERN para criar suas aplicações. Foi combinado que essa nova ferramenta utilizará essa mesma Stack para resolver o problema de organização e produtividade da empresa.

</br>

Link para repositório do Front-end [aqui](https://github.com/dangelo-silva-miranda/ebytr-frontend) </br>
Link para repositório do Back-end [aqui](https://github.com/dangelo-silva-miranda/ebytr-frontend) </br>

---

#### Ferramentas:

- Front-End em **React**;
- Back-End em **NodeJS**, com **MongoDB**;

*utilizando o conceito de Arquitetura em camadas*;

---

<details>  
  <Summary>Como rodar a aplicação localmente</Summary>
  
  Em caso de dúvidas ou erros, fique à vontade para me contatar em dangelo.silva.miranda@gmail.com
  
  </br>

**OBS:** *Para rodar o projeto localmente voce deve ter o mongoDB instalado na sua máquina. Caso ainda não tenha instalado, siga o tutorial da [documentação](https://docs.mongodb.com/manual/installation/).*
  
  </br>
  
### Configurando o servidor

1. Abra o terminal, crie uma pasta para salvar o projeto e acesse a pasta.
~~~cmd
  mkdir projeto-dangelo-silva-miranda
  
  cd projeto-dangelo-silva-miranda
~~~

2. Clone a parte de backend do projeto.
~~~cmd
  git clone git@github.com:dangelo-silva-miranda/ebytr-backend.git
~~~

3. Entre na pasta do repositório criado.
~~~cmd
  cd ebytr-backend
~~~

4. Instale as dependências do projeto.
~~~cmd
  npm install
~~~

5. Inicie o servidor localmente.
~~~cmd
  npm start ( ou 'npm run debug' )
~~~
  
### Abrindo a aplicação no navegador local

Após deixar o servidor rodando localmente, volte para a pasta "projeto-dangelo-silva-miranda", e siga os passos abaixo:

1. Clone o Frontend do projeto
~~~cmd
  git clone git@github.com:dangelo-silva-miranda/ebytr-frontend.git
~~~

2. Entre na pasta do repositório criado.
~~~cmd
  cd ebytr-frontend
~~~

5. Instale as dependências do projeto.
~~~cmd
  npm install
~~~

6. Inicie a aplicação.
~~~cmd
  npm start
~~~
  
</details> 
  
---

#### Funcionalidades:

- Visualizar a lista de tarefas;
- Esta lista deve ser ordenável por ordem alfabética, data de criação ou por status;
- Inserir uma nova tarefa na lista;
- Remover uma tarefa da lista;
- Atualizar uma tarefa da lista;
- A tarefa deve possuir um status editável: pendente, em andamento ou pronto;


#### Critérios de avaliação:
Nosso time irá avaliar a sua entrega olhando, principalmente, para os itens abaixo:

- Atendimento aos requisitos técnicos e funcionais;
- Seu projeto deve rodar sem erros;
- Entendimento dos conceitos das camadas adotadas;
- Código e componentes reutilizados;
- Habilidade em escrever testes (mínimo 30% de cobertura);
- Boa legibilidade do código;
- Separação do front e backend;
- Mensagens de commits bem descritas e commits com um escopo nítido;
- Referências de códigos de terceiros;
- Instruções nítidas no README do projeto para setup e execução da aplicação e dos testes.
- Ter um linter configurado;

Documentação do projeto (README), que inclua:

- Passo a passo para instalar e executar o projeto. 
- Incluir instruções especiais para instalar dependências e/ou bancos de dados, se houver;
- Endereço da aplicação no Heroku, se houver (ou outro serviço de deployment);

</br>

**Dicas importantes!**
- *Ter uma boa cobertura de testes Front e Back;*
- *Aplicar boas práticas de escrita de código;*

---

<details>  
  <Summary> Requisitos do projeto ( para desenvolvedores ) </Summary>
  
  ### Front-end
  
  1. Inicie a aplicação React.
  ~~~cmd
  npx create-react-app nome-do-app
  ~~~
  
</br>
  
  2. Crie um componente para visualizar a lista de tarefas.
  
  *Esse componente deve ter a capacidade de fazer uma requisição ao banco de dados, retornando uma lista de tarefas*
  
</br>
  
  3. Adicionar uma tarefa na lista.
  
  *Crie um input e um botão para que seja possível o usuário criar uma nova tarefa na lista.*
  
</br>
  
  4. Remover uma tarefa da lista.
  
  *Crie um botão "DELETE" para que seja possível o usuário remover uma tarefa da lista.*
  
</br>
  
  5. Alterar uma tarefa da lista
  
  *Crie um botão para que seja possível o usuário alterar a descrição de uma tarefa da lista.*
  
</br>
  
  6. Altere o status da tarefa.
  
  *A tarefa deve possuir um status editável: pendente, em andamento ou pronto*

</br>
  
  ---
  
  ### Back-end
  
  1. Inicie uma aplicação com node.
  ~~~cmd
  npm init
  ~~~

</br>
  
  2. Instale o nodemon para o desenvolvimento.
  ~~~cmd
  npm install nodemon -D
  ~~~

</br>

  3. Adicionar uma tarefa na lista.
  
  *Crie uma maneira na qual seja possível, o usuário criar uma nova tarefa na lista. Essa nova tarefa deverá ser adicionada no banco de dados*
  
  **Dica:** *utilize o método POST*
  
</br>
  
  4. Remover uma tarefa da lista.
  
  *Crie uma maneira na qual seja possível, o usuário remover uma tarefa da lista. Essa tarefa deverá ser removida do banco de dados*
  
  **Dica:** *utilize o método DELETE*
  
</br>
    
  5. Alterar uma tarefa da lista
  
  *Crie uma maneira na qual seja possível, o usuário alterar uma tarefa da lista. Essa tarefa deverá ser alterada/atualizada do banco de dados*
  
  **Dica:** *utilize o método PUT*
  
</br>

</details>
---
### Sobre o README:
*Este README baseia-se no desenvolvido por Pedro-Toselli.*

Link para README modelo [aqui](https://github.com/Pedro-Toselli/ebytr/blob/main/README.md) </br>
