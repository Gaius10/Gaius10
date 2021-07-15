<template>
  <article id="whoami">
    <Section title="Quem sou eu?" icon="far fa-user-graduate">
      <template v-slot:subtitle>
        "Ter identidade, característica ou propriedade intrínseca."
      </template>
      <p>Já faz um tempo desde que escrevo sobre mim.</p>
      <p>
        Pra ser sincero, raramente escrevo sobre mim. Mas frequentemente
        pergunto-me: "Quem sou eu?".
      </p>
      <p>
        Creio que seja árdua a tarefa de definir um ser humano, pergunto-me,
        aliás, se tal ato é possível. De qualquer modo, vou tentar responder
        acerca de quem sou. Quem sabe sai um texto legal, né?
      </p>
      <p>
        Bom, sempre fui um cara esforçado, eventualmente me frustro por conta
        disso. Esforço não é suficiente em certas situações: por vezes
        necessita-se de inteligência, outras vezes sorte, outras, privilégios.
        De qualquer forma, esforço é bonito, não? Talvez seu valor esteja mais
        em si próprio do que em sua utilidade, no fim das contas. E é por isso
        que o busco, pela beleza do heroísmo, do impossível, do sacrifício.
      </p>
      <p>
        Arte, música. Eu já fui o melhor desenhista do quintal da minha casa,
        quando tinha uns 10 anos. Gostava e gosto muito de mangás, eles eram
        sempre minha inspiração pra me expressar e, até mesmo, para viver. Sabe
        a questão do esforço? Provavelmente vem daí...
      </p>
      <p>
        Também toco violino, na verdade devo estar bem enferrujado, já faz um
        bom tempo desde que treino algo decentemente. De toda forma, iniciei meu
        contato com música na igreja, em seguida em uma ONG -
        <ExternalLink href="https://www.institutohatus.org/">
          Instituto Hatus,
        </ExternalLink>
        episódio épico em minha vida, lá conheci muita gente legal, inspiradora.
        Além de ter aprendido muito e evoluído inimaginavelmente como músico e
        como pessoa (pessoas evoluem?) - e então parei. Parei quando passei no
        vestibular e fui estudar
        <ExternalLink href="https://www.divinopolis.cefetmg.br/">
          Engenharia em Minas Gerais (CEFET-MG).
        </ExternalLink>
        Lá ainda tive algum contato com música na igreja e na faculdade, mas
        nada que se comparasse ao meu ritmo anterior.
      </p>
      <p>
        Enfim, considero que me relacionei bem com a Srta. Mecatrônica. Mas a
        pandemia chegou e voltei pra São Paulo.
      </p>
      <p>
        Com o tédio do EaD, meu desempenho caiu desastrosamente e tranquei o
        curso temporariamente. Voltei neste semestre, mas com uma pegada mais
        leve, poucas disciplinas, pretendo migrar para o curso de computação. Lá
        o EaD deve ser menos chato.
      </p>
      <p>
        Por fim, também devo citar meu gosto por estudos e ensino. Sempre que
        tenho a oportunidade de ajudar uma pessoa ou fornecer-lhe algum
        conhecimento sinto-me admirado, é gratificante. Além disso, uma das
        coisas que mais tenho feito em meu tempo livre é estudar, aperfeiçoar-me
        enquanto ferramenta. Não apenas pela utilidade, mas pela diversão em
        vencer desafios e pela graça de obter respeito, admiração.
      </p>
      <template v-slot:footer>
        <span>Caio Corrêa Chaves</span>
        <time>Junho, 2021</time>
      </template>

      <PageLink type="back" href="#whoami">Voltar</PageLink>
    </Section>
  </article>
</template>

<script setup>
import Section from "../tiny/Section.vue";
import PageLink from "../tiny/PageLink.vue";
import ExternalLink from "../tiny/ExternalLink.vue";
</script>

<style>
</style>