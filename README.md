# SideBars
inicie projetos com códigos limpos e dinâmicos que irão otimizar o seu tempo de produção.

O framework é totalmente dinâmico, apenas inclua os links abaixo na tag "head" e deixe que o restante o código faça. 


#INSTALAÇÃO: 
<pre>1° - Baixe os arquivos 'sidebar.js' e 'sidebar.css'</pre> <br>

<pre>2° - Chame os arquivos 'sidebar.js' e 'sidebar.css' dentro da tag 'head' do documento HTML.</pre><br>

<pre>3° - Nos seus códigos, coloque o atributo 'data-offset="default"' na ultima div do seu sidebar(escopo global)</pre>

#Obser: Lembrando que a div ou elemento pai do sidebar e do outro escopo do site receberá a propriedade 'display: flex' para que fiquem alinhados lado a lado.<br><br><br>

<pre>4° - Ainda nos seus códigos, coloque o atributo 'data-sideBtn="pillars"' no seu button responsável para ativer o sidebar</pre><br> <br>

<strong><h3>PRONTO!</h3></strong> 

Agora o código irá configurar sozinho a propriedade do sidebar, além de criar um botão personalizado. 
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




<strong>data-sideBtn</strong> - Esse atributo foi configurado para ceitar dois valores:

<strong>data-sideBtn="pillars"</strong> - Irá criar pilares no botão, com o efeito único. Caso queira modificar o elemento de dentro, voce pode utilizar qualquer símbolo disponível nesse site: https://pt.wiktionary.org/wiki/%E2%98%B0. Apenas chame no final do seu código a função btnSideBar() e coloque o símbolo dentro dela. Exemplo: 

<pre>
<script> 
  btnSideBar('♅');
</script>
</pre>
<br> <br>

<strong>data-sideBtn="cross"</strong> - Irá criar também três pilares deitados, mas a animação final irá transformar os itens em um "X"; Não há como variar, apenas manter esse efeito.
<br> <br>

<strong>data-sideBtn</strong> - Caso queira criar voce mesmo o seu botão, apenas coloque a propriedade sem um valor que não irá ser criado nenhum elemento. 







