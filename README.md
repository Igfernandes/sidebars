# SideBars
inicie projetos com códigos limpos e dinâmicos que irão otimizar o seu tempo de produção.

O framework é totalmente dinâmico, apenas inclua os links abaixo na tag "head" e deixe que o restante o código fazer. 


#INSTALAÇÃO: 

1° - Baixe os arquivos 'sidebar.js' e 'sidebar.css'

2° - Chame os arquivos 'sidebar.js' e 'sidebar.css' dentro da tag 'head' do documento HTML.

3° - Nos seus códigos, coloque o atributo 'data-offset="default"' na ultima div do seu sidebar(escopo global)

#Obser: Lembrando que a div ou elemento pai do sidebar e do outro escopo do site receberá a propriedade 'display: flex' para que fiquem alinhados lado a lado.

4° - Ainda nos seus códigos, coloque o atributo 'data-sideBtn="pillars"' no seu button responsável para ativer o sidebar

PRONTO! 

- Agora o código irá configurar sozinho a propriedade do sidebar, além de criar um botão personalizado. 



#DOCUMENTAÇÃO: 

data-offset - Esse atributo pode ter sua estrutuda modificada. O padrão é o sidebar alcançando 15% da tela, mas caso queira ajustar para outras propriedades, os valores disponívels são:

data-offset="25"
data-offset="50"
data-offset="75"
data-offset="90"
data-offset="100"


data-sideBtn - Esse atributo foi configurado para ceitar dois valores:

data-sideBtn="pillars" - Irá criar pilares no botão, com o efeito único. Caso queira modificar o elemento de dentro, voce pode utilizar qualquer símbolo disponível nesse site:
https://pt.wiktionary.org/wiki/%E2%98%B0. Apenas chame no final do seu código a função btnSideBar() e coloque o símbolo dentro dela. Exemplo: 

<script> 
  btnSideBar('♅');
</script>

data-sideBtn="cross" - Irá criar também três pilares deitados, mas a animação final irá transformar os itens em um "X"; Não há como variar, apenas manter esse efeito.

data-sideBtn - Caso queira criar voce mesmo o seu botão, apenas coloque a propriedade sem um valor que não irá ser criado nenhum elemento. 







