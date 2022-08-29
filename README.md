# MVC_MVP_MVVM_overview

<h2> pegue um atalho 👇🏻</h2>   
 
- [MVC- Model, View, Controller](#mvc--model-view-controller)
- [MVP- Model, View, Presenter](#mvp--model-view-presenter)
- [MVVM- Model, View, ViewModel](#mvvm--model-view-viewmodel)   



<h2 align="center">MVC- Model, View, Controller</h2>   
   
   ### Model  
   * Contém a conexão com o banco de dados ou a forma como acessar os dados.
   * Tem a lógica necessária para processar os dados no banco de dados ou outra fonte.
   * Processa os dados obtidos na fonte e coloca na forma necessária para que as outras camadas possam utilizar adequadamente.
   >Algumas dessas funções podem estar em uma camada separada, mas só o Model se comunica com ela.
   
   ### View   
   * Tem todo o desenho e formatação da interface com usuário.
   * Costuma ter validações específicas da UI.
   * Processa os dados obtidos na UI para ser disponibilizada de forma adequada para outras camadas.
   >A View tem uma instancia do Controller mas o Controller não tem uma instancia da View.
   
   ### Controller  
   * Onde fica a regra de negócio. 
   * É o intermediario entre a View e o Model, fazendo o controle.
   * Faz a lógica adequada para enviar para a view, validações, processos.
   * Faz a relação entre as entidades.
   >Controller conhece o Model.
   
   <h2 align="center">MVP- Model, View, Presenter</h2>   
   
   ### Model   
   * [Mesma arquitetura. ☝️](#model)
   
   ### View   
   * Tem todo o desenho e formatação da interface com usuário.
   * Dostuma ter validações específicas da UI.
   * Processa os dados obtidos na UI para ser disponibilizada de forma adequada para outras camadas.
   >Nessa arquitetura A View conhece o Presenter.
   
   ### Presenter  
   * Uma evolução do Controller.
   * Tem as mesmas Funções do Controller.
   >Porém, agora  o Presenter tem uma instancia da view.
   >Entre View e Presenter há uma relação de UM-PARA-UM entre as camadas.
   >Fazendo intermediario entre a View e o Model, agora tendo acesso as duas, evita interação entre ambas dieretamente, desacoplando as funções e deixando a arquitetura mais modular facilitando os testes.
   
   <h2 align="center">MVVM- Model, View, ViewModel</h2>   
   
   ### Model   
   * [Mesma arquitetura. ☝️](#model)
   
   ### View   
   * Tem todo o desenho e formatação da interface com usuário.
   * Costuma ter validações específicas da UI.
   * Processa os dados obtidos na UI para ser disponibilizada de forma adequada para outras camadas.
   
   ### ViewModel  
   * Contém toda a lógica de negócios.
   * Agora  pode ter relação de várias Views para um ViewModel.
   * Adiciona propriedades e operações ao Model para atender as necessidades do View, o estado da view. 
   * Operar o Model e ativar eventos da View.
   > melhora a manutenção dos códigos por causa do baixo acoplamento e reutilização de uma camada em varias Views.
   
   <h2 align="center">⭐️⭐️⭐️⭐️⭐️</h2> 
   
   ### Obs: fique à vontade em adicionar algo ou enriquecer mais o assunto, ficarei feliz em me aprofundar mais no tema!   

   
 >if this project helped you, contribute by giving a ⭐ !! I'll be grateful 😁      

</br>   
<div align="center">   
  
   [![Linkedin Badge](https://img.shields.io/badge/-weslei%20tiago-292929?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/weslei-tiago-53b47a208/)](https://www.linkedin.com/in/weslei-tiago-53b47a208/)   
  
   </div>
  
   
