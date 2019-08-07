# Formularios-ComplementoHTML
Complemento da Aula Formulários com mais TAGs 

### Descrição da atividade:

 - Continuação da atividade de Formulários
 - Criar arquivo inicial.html dentro da pasta formulários e redigir o que fora solicitado pelo docente.
 - Criar mais páginas com os seguintes títulos: Solicitar ajuda, Aprovar novo usuário, Quero ser voluntário, Ocorrências, Triagem 


### Comandos Utilizados:

* \<header>\</header>\ -  elemento <header> representa um contêiner para conteúdo introdutório ou um conjunto de links de navegação. Geralmente contém:  

um ou mais elementos de cabeçalho (\<h1> -\ <h6>)  
 logotipo ou ícone  
 informação de autoria  
 Você pode ter vários elementos <header> em um documento.  
   Obs: Uma tag \<header> não pode ser colocada dentro de um \<footer>, \<address> ou outro elemento \<header>.  
Ex. 

 ```html
      <header>
           Usuário logado: Renan
           <a href="index.html">Sair</a>
       </header>

 ```
 ---  
 * \<footer>\</footer>\ - define um rodapé para um documento ou seção. Um elemento \<footer> deve conter informações sobre seu elemento contido. Geralmente contém:  

. informação de autoria  
. Informações sobre direitos autorais  
. informações de contato  
. sitemap  
. voltar ao topo links  
. documentos relacionados  
Você pode ter vários elementos \<footer> em um documento.  
 Ex.:
 
 ```html
       <footer>
           <em>&copy; 2019 - Jodas Sistemas</em>
       </footer>
 ```  
 ---  
 * \<main>\</main>\ - define o conteúdo principal dentro do \<body> em seu documento ou aplicação. Entende-se como conteúdo principal aquele relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação. O mesmo deverá ser único na página, ou seja, dentro do elemento \<main> não deverão ser incluídas seções da página que sejam comuns a todo o site ou aplicação, tais como mecanismos de navegação, informações de copyright, logotipo e campos de busca \(a não ser, é claro,  caso a função principal do documento seja  fazer algum tipo de busca). 
 Ex.:
 
 ```html
  <main>
           <h3>Escolha uma opção</h3>
           <ul>
               <li>
                   <a href="cadastro-usuario.html">Cadastrar um usuário</a>
               </li>
               <li><a href="ajuda.html">Solicitar ajuda</a></li>
               <li><a href="aprovar-usuario.html">Aprovar novo usuário</a></li>
               <li><a href="ser-voluntario.html">Quero ser voluntário</a></li>
               <li><a href="ocorrencias.html">Ocorrências</a></li>
           </ul>
       </main>

 ```  
 ---  
 * Comando   \‘&copy;’\ - insere símbolo copyright 
 
  Ex.:
 ```html
  <input name="usuario" id="usuario" maxlength="30" placeholder="Nome de usuário ou E-mail">
 ```  
 ---  
 * comando - na página em branco, digitar \'html' - pressionar ESC - pressionar CTRL + SPACE - pressionar ENTER, o programa carrega um padrão de pagina →  
 Ex.:
 
 ```html
  <html>
<head>
   <meta charset='utf-8'>
   <meta http-equiv='X-UA-Compatible' content='IE=edge'>
   <title>Page Title</title>
   <meta name='viewport' content='width=device-width, initial-scale=1'>
   <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
   <script src='main.js'></script>
</head>
<body>
  
</body>
</html>

 ```  
 ---  
 * Tabelas  
\<table>\</table> - tabela  
Uma tabela HTML possui dois tipos de células:  
\<tr>\</tr> - table-row - define uma linha em uma tabela HTML,   
\<th>\</th> - define uma célula de cabeçalho em uma tabela HTML, está em negrito e centralizado por padrão.  
\<td>\</td> - Células padrão - contém dados, é regular e alinhado à esquerda por padrão.  
 Ex.:
 ```html
         <table>
                    <tr>
                        <td><input type="checkbox"></td>
                        <td>Mari</td>
                        <td>(11)1111-1111</td>
                        <td><img src="_imagens/facebook.png"></td>
                    </tr>
                    <tr>
                        <td><input type="checkbox"></td>
                        <td>José</td>
                        <td>(22)2222-2222</td>
                        <td><img src="_imagens/instagram.png"></td>
                    </tr>
                    <tr>
                        <td><input type="checkbox"></td>
                        <td>Bob</td>
                        <td>(33)3333-3333</td>
                        <td><img src="_imagens/linkedin.png"></td>
                    </tr>
                    <tr>
                        <td><input type="checkbox"></td>
                        <td>Júnior</td>
                        <td>(44)4444-4444</td>
                        <td><img src="_imagens/facebook.png"></td>
                    </tr>
           </table>

 ```  
 ---  
 ### Author
 [Renan Dias Jodas](https://br.linkedin.com/in/renanjodas)

