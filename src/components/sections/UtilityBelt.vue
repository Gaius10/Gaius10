<template>
  <Section title="Meus cinto de utilidades" icon="far fa-user-graduate">
    <template v-slot:subtitle>
      <ul class="utilityBelt">
        <li class="c"><img src="../../assets/c.png" alt="C" /></li>
        <li class="cpp"><img src="../../assets/cpp.png" alt="C++" /></li>
        <li class="php"><img src="../../assets/php.png" alt="PHP" /></li>
        <li class="html5"><img src="../../assets/html5.png" alt="HTML5" /></li>
        <li class="css3"><img src="../../assets/css3.png" alt="CSS" /></li>
        <li class="js"><img src="../../assets/js.png" alt="JavaScript" /></li>
        <li class="python">
          <img src="../../assets/python.png" alt="Python" />
        </li>
        <li class="r"><img src="../../assets/r.png" alt="R" /></li>
        <li class="lua"><img src="../../assets/lua.png" alt="Lua" /></li>
      </ul>
    </template>
    <p>
      Minha principal linguagem de programação é, sem dúvidas, o PHP, trabalho
      com a ferramenta desde que iniciei meus estudos com desenvolvimento web em
      2017. Apesar de tudo, minhas experiências são, em maioria, relacionadas a
      pequenos projetos pessoais e de estudos (Em meu github está disponível o
      código-fonte de meu TCC) por conta de minha forte ligação até o atual
      momento com o ambiente acadêmico.
    </p>
    <p>
      De qualquer modo, aqui vão algumas das atividades que já realizei
      utilizando PHP e tecnologias web:
    </p>
    <ul>
      <li>Desenvolvimento de aplicações web full-stack</li>
      <li>Consumo de APIs para diversos fins</li>
      <li>Desenvolvimento de APIs RESTful</li>
      <li>Atividades relacionadas a Web Scrapping</li>
      <li>Manipulação de QR Codes</li>
      <li>Este site :)</li>
    </ul>
    <p>
      Além do PHP, também tive muito contato com C e C++, em especial para o uso
      na programação de microcontroladores. Um de meus projetos mais legais em
      C++ foi o desenvolvimento do
      <ExternalLink href="https://github.com/Gaius10/FredMcQueen">
        controlador de uma plataforma móvel,
      </ExternalLink>
      usada na 5º Competição Interna de Robótica do CEFET-MG Divinópolis.
    </p>

    <p>
      Sobre Python e R, realizei apenas alguns testes pessoais envolvendo
      operações simples com visão computacional(Python) e calculos estatísticos
      (R) como geração de gráficos para análise de grandes conjuntos de dados.
    </p>
  </Section>
</template>

<script setup>
import Section from "../tiny/Section.vue";
import ExternalLink from "../tiny/ExternalLink.vue";
</script>

<style>
ul.utilityBelt {
  width: 100%;
  display: flex;
  flex-direction: row;
}
ul.utilityBelt > li img {
  width: 35px;
}
</style>