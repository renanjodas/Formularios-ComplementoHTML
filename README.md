# Formularios-ComplementoHTML
Complemento da Aula Formulários com mais TAGs 

### Descrição da atividade:

- Criar Repositório no github e clonar no computador
- Criar 1 página em HTML e editar conforme orientação do professor tela de Login e trabalhando com formulários
- Desenvolver 1 página de cadastro de usuário com formulário
- Subir os arquivos para o repositório


### Comandos Utilizados:

* form - Tag para indicar formulario  
* action - ação do formulário (ação de enviar para banc - tag para inserção de link (externo ou local)  
 Ex.:
 ```html
  <form name="form_login" action="inicial.html">
 ```
 ---  
 * label - indica um rótulo(legenda)  
 * input - insere uma caixa de texto para “entrar/inserir” com algum dado/informação/texto  
   name - como sera chamada esta caixa | id - identificação (tipo variavel - direcionar) | maxlength - limite de caracteres   
 Ex.:
 ```html
  <label for="usuario">Usuário:</label>
               <input name="usuario" id="usuario" maxlength="30">

 ```  
 ---  
 * title - aponta comentario quando usuario passa o mouse em cima  
 Ex.:
 ```html
  <label for="usuario" title="Label do Usuário">Usuário:</label>
 ```  
 ---  
 * placeholder - Define a ajuda para o usuário preencher o campo com os dados corretos  
  Ex.:
 ```html
  <input name="usuario" id="usuario" maxlength="30" placeholder="Nome de usuário ou E-mail">
 ```  
 ---  
 * method e ‘value’ POST - para, ao clicar em enviar, na URL não apareça os dados enviados pelo form (como a senha)  
 Ex.:
 ```html
  <form name="form_login" action="inicial.html" method="POST">
 ```  
 ---  
 * fieldset - cria uma caixa com informações dentro  
 * legend - cria legenda desta caixa  
 Ex.:
 ```html
         <fieldset>
               <legend><strong>Informações Pessoais</strong></legend>
                  
               <label for="nome">Nome: </label>
               <input id="nome" name="nome" maxlength="20" placeholder="Nome">
 
               <label for="sobrenome">Sobrenome: </label>
               <input id="sobrenome" name="sobrenome" maxlength="50" placeholder="Sobrenome"><br>
               <br>
               <label for="email">E-mail: </label>
               <input id="email" name="email" maxlength="50" placeholder="E-mail"><br>
          </fieldset>
 ```  
 ---  
 * required - no input, torna o campo obrigatório.  
 Ex.:
 ```html
  <label for="nome">Nome: </label> 
                    <input id="nome" name="nome" maxlength="20" placeholder="Nome" required> 
 ```  
 ---  
 * tipo de input "radio" (seleção)  
 Ex.:
 ```html
    <fieldset>
                        <legend><strong>Contrato</strong></legend>
                        Aceita os termos do contrato?
                        <br>
                        <input type="radio" name="contrato">Sim
                        &nbsp; &nbsp;
                        <input type="radio" name="contrato">Não <br>
    </fieldset>
 ```   
 ---   
 * select - cria caixa de seleção  
 * option - define a lista de opções da caixa de seleção  
 Ex.:
 ```html
    <select name="contrato2">
             <option></option>
             <option>Sim</option>
             <option>Com certeza</option>
    </select>
 ```   
 ---  
 ### Author
 [Renan Dias Jodas](https://br.linkedin.com/in/renanjodas)

