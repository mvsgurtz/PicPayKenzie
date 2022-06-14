# PicPayKenzie HTML
<!DOCTYPE html>
<Html lang="pr-br">
    <head>
        <meta charset="UFT-8">
        <title>PICPRO</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="reset.css" type="text/css">
        <link rel="stylesheet" href="style.css" type="text/css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <script src="projeto_picpro.js"></script>


    </head>
    <body>
        <!--cabeçario-->
        <header class="cabecalho">
            <div class="conteiner">
               <figure class="logo_picpro">
                   <img src="./img/logo-picpro.png" alt="LOGO PICPRO">
               </figure>
               <figure class="LOGO_KENZIE">
                   <img src="./img/logo-kenzie.png" alt="LOGO KENZIE">
               </figure>
            </div>
        </header>

        <!-- conteúdo principal-->
        <main>
            <section class="DetalhesContas">
                <div class="conteiner">
                    <div class="sobre_usuario">
                        <div class="carinha">                   
                            <img src="./img/usuario.png" alt="ICONE">
                            <p>Olá! <strong>@mvsgurtz</strong> </p>
                        </div>
                        <div class="desafio">
                            <img id="primeiro" src="./img/presente.png" alt="gift" >
                            <img id="segundo" src="./img/chat.png" alt="chat" >
                        </div>
                    </div>  
                    <div class="saldo">
                        <p>Saldo PicPay <strong>R$ 5.000,00</strong></p>
                        <button>Extrato</button>
                    </div >
                        <ul class="ListaDeTransacoes">
                        <li class="itemtransacao">
                            <img src="./img/qrcode.png" alt="icone QRCODE">
                            <p>QR Code</p>
                        </li>
                        <li class="itemtransacao">
                            <img src="./img/pix.png" alt="icone PIX">
                            <p>PIX</p>
                        </li>
                        <li class="itemtransacao">
                            <img src="./img/codigo.png" alt="icone Pagar Boleto">
                            <p>Pagar Boleto</p>
                        </li>
                        <li class="itemtransacao">
                            <img src="./img/cobrar-icon.png" alt="icone Cobrar">
                            <p>Cobrar</p>
                        </li>
                    </ul>
                </div>
            </section>
            <section class="secaoTransacao">
                <!--geral-->
                <div class="conteiner">
                    <!--pamento-->
                    <div class="secaoTransacao_avisoSelecao">
                        <p>Selecione a forma de pagamento</p>
                        <img src="./img/banner.png" alt="banner PICPAY">
                    </div>
                    
                    <!--QR CODE-->
                    <div class="secaoTransacao_QRcode">
                        <img src="./img/qrcode-imagem.png" alt="banner QRCODE">
                        <p>@mvsgurtz</p>
                        <button>Cobre um amigo</button>
                        <a href="#">Compartilhar meu código</strong></a>
                    </div>
                    
                    <!--PIX-->
                    <div class="secaoTransacao_pix">
                        <img src="./img/pix-logo.png" alt="banner pix">
                        <div class="boxop">
                            <img src="./img/pix1.png" alt="opçao pix 1">
                            <p>Envie por CPF/CNPJ, telefone, e-mail, aleatória</p>
                        </div>
                        <div class="boxop">
                            <img src="./img/pix2.png" alt="opçao pix 2">
                            <p>Insira um código Pix Copia e Cola para enviar um pagamento</p>
                        </div>

                    </div>
                   
                    <!--BOLETO-->
                    <div class="secaoTransacao_boleto">
                        <img src="./img/boleto.png" alt="banner Boleto">
                        <h2>Pagar com código de barras</h2>
                        <p>Você pode parcelar em até 12x no cartão ou usar seu saldo em carteira pra pagar à vista.</p>
                        <input type="text" placeholder="Insira o código de barras">
                    </div>
                    
                    <!--COBRAR-->
                    <div class="secaoTransacao_cobrar">
                        <img src="./img/cobrar.png" alt="banner Cobrar">
                        <h2>Cobrar</h2>
                        <p>Divida a conta com os amigos de forma fácil</p>
                        <div class="boxop">
                            <img src="./img/picpay-icon.png" alt="PICPAY ICON">
                            <p>
                                <strong>Amigos do PicPay</strong> 
                                Divida e acompanha um gasto com pessoas por aqui.
                            </p>
                        </div>
                    </div>
                </div>
            </section>
        
            <footer class="rodape">
                <!--rodapé-->
                <div class="conteiner">
                <ul class="rodape_menuprincipal">
                    <li class="rodape_item">
                        <a href="#"></a>
                        <img src="./img/inicio.png" alt="inicio">
                        <p>Início</p>
                        <li class="rodape_item">
                            <a href="#"></a>
                            <img src="./img/carteira-icon.png" alt="CARTEIRA">
                            <p>Carteira</p>
                        </li>
                    </li>
                    <li class="rodape_menuitem rodape_menuitem_pagar">
                        <a href="#"></a>
                        <img src="./img/pagar.png" alt="PAGAR">
                        <p>Pagar</p>
                    </li>
                    <li class="rodape_menuitem">
                        <a href="#"></a>
                        <img src="./img/notificacao.png" alt="NOTIFICAÇÃO">
                        <p>Notificação</p>
                    </li>
                    <li class="rodape_menuitem">
                        <a href="#"></a>
                        <img src="./img/bolsa.png" alt="STORE">
                        <p>STORE</p>
                    </li>
                </ul>
                </div>   
            </footer>

        </main>
    </body>

