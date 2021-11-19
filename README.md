# PROJETO-LIVRARIA-HTML

<!DOCTYPE html>

<html>

       <head> 

            <meta charset="UTF-8" lang="pt-br">
            <title>Livraria Oficina da Saber</title>
            <link rel="stylesheet" type="text/css" href="estilo.css">  
             <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-uWxY/CJNBR+1zjPWmfnSnVxwRheevXITnMqoEIeG1LJrdI0GlVs/9cVSyPYXdcSF" crossorigin="anonymous">
             
      </head>

    <body>

      <ul id="menu-h">

                

                   
        <li><a href="#">quem somos</a></li>
        <li><a href="#">produtos</a></li>
        <li><a href="#">vendas</a></li>
        <li><a href="#">lançamentos</a></li>
        <li><a href="#">atendimento</a></li>

      </ul>


         <nav class="slide">  
          <div class="slide">
            <div class="slides">

              <div id="voltar" class="btn">
                <i class="fas fa-chevron-left"></i>
               </div>
                <div id="next" class="btn">
                <i class="fas fa-chevron-right"></i>
                </div>

                <div id="atual" class="images">
                  <img src="imagens\01.jpg" alt="">
                  </div>
                      <div class="images">
                          <img src="imagens\02.jpg" alt="">
                       </div>
                            <div class="images">
                               <img src="imagens\03.jpg" alt="">
                            </div>
                                <div class="images">
                                    <img src="imagens\04.jpg" alt="">
                                </div>


                 </div>
                
                 <div class="balls">

                      <div id="1"></div>
                      <div id="2"></div>
                      <div id="3"></div>
                      <div id="4"></div>
                 </div>
          </div>


         </nav>

          


              <nav class="categorias">
                   
                  <p> <b>Mergulhe no Conhecimento!</b></p>
 
               

                 <img src="imagens\bola.jpg">

                    <h4>Livraria</h4> 
                    <h1>Oficina do saber</h1> <br><br>



                        <ul>

                          <p><h4><b>Livros</b></h4></p>
                        

                          
                          
                         
                            <li><a href="#">Literatura</a></li>
                            <li><a href="#">Histórias Infantis</a></li>
                            <li><a href="#">Linguagem</a></li>
                            <li><a href="#">Ciências</a></li>
                            <li><a href="#">Autoajuda</a></li>
                            <li><a href="#">Ficção</a></li>
                            <li><a href="#">Romance</a></li>

                          

                           <p><h4><b>Versão</b></h4></p>

                            <li><a href="#">Digital</a></li>
                            <li><a href="#">Impresso</a></li>
                             
                               
                            
                        </ul>
                         <br> <br> <br>

              </nav>
                          <br><br><br>

                    <h4><b>Formulário</b></h4>

                       <form>
                         
                          <div class="form-group">

                            <label for="nome">Nome:</label>
                            <input type="text" class=form-control id="nome" placeholder="Digite seu Nome" required> 

                          </div>  
                          
                          <div class="form-group">

                            <label for="Email">Email:</label> 
                            <input type="text"class=form-control id="imail" placeholder="Digite seu Email" required> 
                            <small id="emailhelp"class="form texttextmuted">*Nunca Compartilharemos esse Email.</small>
                          </div>  

                          <div class="form-group">

                              <datalist id="sexo">
                                 
                                   <option value="Feminino">
                                   <option value="Masculino">

                              </datalist>

                              <p>Sexo: <input type="text" class=form-control list="sexo"/></p>

                          </div>     

                              <fieldset>

                                   <legend><h4><b>Pagamento</b></h4></legend><br>

                                        <label for="Cartão">Cartão de Credito</label>
                                        <input type="checkbox"name="Formade pagamento" id="cartão" value="cartão"> 
                                        <label for="Pix">Pix</label>
                                        <input type="checkbox" name="Formadepagamento" id="Pix" value="Pix"><br>

                              </fieldset> <br>


                               
                                
                                  <input type="submit" class="btn btn-primary" name="enviar" value="Cadastrar"> <br><br><br>
                                  <input type="reset"class="btn btn-success" name="Limpar" value="Limpar"><br><br>
                               




                         </form>

                
            <script src="Script.js"></script>

           
          </body>
           
          
            
          

          
</html>
