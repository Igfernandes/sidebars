# SideBars
inicie projetos com códigos limpos e dinâmicos que irão otimizar o seu tempo de produção.

O framework é totalmente dinâmico, apenas inclua os links abaixo na tag "head" e deixe que o restante o código faça. 


#INSTALAÇÃO: 
<pre>1° - Baixe os arquivos 'sidebar.js' e 'sidebar.css'</pre> <br>

<pre>2° - Chame o arquivo 'sidebar.css' dentro da tag 'head' do documento HTML. Depois chame o arquivo 'sidebar.js' no final da tag 'body'</pre><br>

<pre>3° - Nos seus códigos, coloque o atributo 'data-offset="default"' na ultima div do seu sidebar(escopo global)</pre>
<br>
#Obser: Lembrando que a div ou elemento pai do sidebar receberá a propriedade 'display: flex' para que o sidebar fique alinhado lado a lado do restante do código.<br><br><br>
 
<pre>4° - Agora coloque a classe 'sidebar' dentro da mesma div em que está o 'data-offset'</pre> <br> <br>

<pre>5° - Ainda nos seus códigos, coloque o atributo 'data-sideBtn' no seu button responsável pela ativação do sidebar</pre><br> <br>

<strong><h3>PRONTO!</h3></strong> 

Agora o código irá configurar sozinho a propriedade do sidebar, além de criar um botão personalizado. 

<img src="https://raw.githubusercontent.com/Igfernandes/sidebars/main/print.jpg">
<br><br><br>


<strong><h3>#DOCUMENTAÇÃO:</h3></strong> 

<strong>data-offset</strong> - Nesse atributo podemos modificar sua estrutura. O valor 'default' é  representado pelo sidebar alcançando 15% da tela, mas caso queira ajustar para outras propriedades, os valores disponívels são:

<table>
  <tbody>
    <tr>
      <td>data-offset</td><td>default</td>
    </tr>
    <tr>
       <td>data-offset</td><td>25</td>
    </tr>
    <tr>
       <td>data-offset</td><td>50</td>
    </tr>
    <tr>
       <td>data-offset</td><td>75</td>
    </tr>
    <tr>
       <td>data-offset</td><td>90</td>
    </tr>
    <tr>
       <td>data-offset</td><td>100</td>
    </tr>
  </tbody>
</table>

<br> <br>




<strong>data-sideBtn</strong> - Esse atributo foi configurado para aceitar dois valores: <br><br>

<strong>data-sideBtn="pillars"</strong> - Irá criar pilares no botão, com o efeito único. Caso queira modificar o elemento de dentro, voce pode utilizar qualquer símbolo disponível nesse site: https://pt.wiktionary.org/wiki/%E2%98%B0. Apenas chame no final do seu código a função btnSideBar() e coloque o símbolo dentro dela. Exemplo: <br>

<pre>
<script> 
  btnSideBar('♅');
</script>
</pre>
<br> <br>

<strong>data-sideBtn="cross"</strong> - Irá criar também três pilares deitados, mas a animação final irá transformar os itens em um "X"; Não há como variar, apenas manter esse efeito.
<br> <br>

<strong>data-sideBtn</strong> - Caso queira criar voce mesmo o seu botão, apenas coloque a propriedade sem um valor para que não seja criado um elemento. 







