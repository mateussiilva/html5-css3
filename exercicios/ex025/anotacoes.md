Para enviar os dados do formularios precisamos passar 
o atributo "action" com o caminho do arquivo para 
o form, igual o exemplo abaixo.
-----------------------------------
label = etiqueta

sempre que trabalharmos com formularios é indicado informar 
os seguintes atributos para o campo de inserção de dados(input)
name e id 
name = será mais util para html e para o php caso precisamos pegar 
o valor desse campo
id = usamos esse atributo para aplicar um css especifico e usamos ele para pegar o valor dentro do input 

----------------------------------------------
Existem dois metodos de envios no HTML
o GET e o POST
por padrão todos os formularios usam o GET
mas podemos usar o atrbuto "method" com o metodo que desejamos

Quando enviamos com o metodo GET os dados digitados ficam visisveis na URL, mas
quando enviamos usando o POST os dados não ficam visiveis na URL mas ainda sim eles ficam 
desprotegidos como no GET

    USO DE GET
        vamos usar o metodo GET quando a informação não for algo SENSIVEL
        o maximo que o GET consegue enviar é 3000B que se equivale a 3000 letras 

    USO DE POST
        usamos ele quando desejamos enviar fotos, videos ou em geral qualquer arquivo
        ou quando o dado a ser enviado enviado ultrapassa os 3000B
        quando vamos enviar dados sensiveis podemos usar, mas o mais recomendado é usar o protocolo HTTPS pois ele encripta os dados

#------------------------------------------------------------------

ATRIBUTOS DOS FORMULARIOS

  
    REQUIRED
        O atributo "required" do input faz com que ele seja um campo "obrigatorio"
        ou seja não consigou enviar o formulario sem que ele seja preenchido.
    
    MINLENGTH:
        Esse atributo do input define o tamanho minimo de caractere que o campo precisa
        receber, é um otimo pré validador proprio do htlml

    MAXLENGTH:
        Esse atributo do input define o tamanho maximo de caractere que o campo pode 
        receber, é um otimo pré validador proprio do htlml
    
    SIZE:
        Define o tamaho que o input que vai ter
