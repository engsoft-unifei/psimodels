---
layout: ../../layouts/PostLayout.astro
title: "Norma ISO/IEC 12207"
description: "Apresentação da Norma ISO/IEC 12207"
author: "Guilherme Vieira, "
date: "17 Oct 2022"
banner: "bg-yellow-200"
---

- [Introdução](#introdução)
- [História e Objetivo](#história-e-objetivo)
- [Etapas, estratégias, organização da norma para garantir a qualidade do processo de desenvolvimento de software](#etapas-estratégias-organização-da-norma-para-garantir-a-qualidade-do-processo-de-desenvolvimento-de-software)
- [Benefícios de usar a norma](#benefícios-da-norma)
- [Desafios ao implementar a norma](#desafios-da-implementação)
- [Obtendo a certificação ISO/IEC 12207](#obtendo-a-certificação)
- [Tem certificação no Brasil?](#tem-certificação-no-brasil)
- [Como obter essa certificação no Brasil?](#obtendo-a-certificação-no-brasil)
- [Empresas Brasileiras certificadas na norma](#empresas-brasileiras-certificadas)
- [Relato da adoção da norma pelo Banco Central](#relato-de-adoção-pelo-banco-central)
- [Conclusão](#conclusão)

## Introdução

<p>A ISO/IEC 12207 tem como objetivo estabelecer uma estrutura co-
mum para o processo de ciclo de vida de software. Este artigo descreve seus
processos, atividades e tarefas, a hist ́oria de sua criação, benef ́ıcios, desafios
comuns para sua implementação, seu processo de certificação no Brasil e es-
tudo de caso sobre sua utilização</p>

## História e Objetivo

<p>
A primeira vers ̃ao da ISO/IEC 12207 foi publicada em primeiro de julho de 1995, pela In-
ternational Organization for Standardization, com o objetivo de estabelecer padr ̃oes para
o processo de ciclo de vida de software [ISO 12207:2017(E) 2017]. Ela foi o primeiro
padr ̃ao a fornecer um conjunto t ̃ao abrangente de definic ̧  ̃oes a respeito do ciclo de vida
de software, suas atividades, tarefas e processos. A vers ̃ao mais recente desta norm ́a  ́e
a ISO/IEC/IEEE 12207: 2017 Systems and software engineering — Software life cycle
processes.
</p>
<p>
Sua idealizac ̧  ̃ao, assim como outras normas e padr ̃oes da mesma  ́epoca, foi
motivada pelo fenˆomeno conhecido como crise do software. O termo crise do soft-
ware  ́e utilizado para descrever a dificuldade de se fazer estimativas de tempo e escopo
para projetos de softwares cuja complexidade e tamanho escalam de forma exponencial
[Fitzgerald 2012].
</p>

## Etapas, estratégias, organização da norma para garantir a qualidade do processo de desenvolvimento de software
<p>
    Os processos, atividades e tarefas da ISO/IEC 12207 foram planejados visando sua adaptação segundo a necessidade 
    de cada projeto de software. A adaptação é formaliza-se, por exemplo, nas atividades de mapear processos, atividades 
    e tarefas pertinentes ao projeto e, no mesmo momento, extingue processos, atividades e tarefas que não se aplicam ao projeto
</p>

<p>
    Os processos desta norma são agrupados, esse agrupamento proporcionou quatro classes de processos distintas:  
    Processos Fundamentais; Processo de Apoio;  Processos Organizacionais; e Processos de Adaptação. Os processos são 
    combinados e classificados por questões de organização, de acordo com suas características, ou seja, suas finalidades 
    principais. Por causa dessa combinação, os processos foram categorizados em quatro classes de processos, como supracitado.
<p>

<h4> 2.1 Processos Fundamentais</h4>

<p>
Os processos fundamentais “[...] atendem ao início, à contratação entre o  adquirente e o fornecedor e à execução do desenvolvimento, da operação ou da manutenção de produtos de software durante o ciclo de vida do software”. (ROCHA, MALDONADO e WEBER, 2001).
Os processos fundamentais existem a fim de que seja possível a execução de
um software. Esses processos dão início ao ciclo de vida e gerenciam outros
processos:
<p>

<ul>
    <li>Aquisição: visa a obtenção do produto/serviço que dê satisfação às suas necessidades;</li>
    <li>Fornecimento: prover um produto/serviço;</li>
    <li>Desenvolvimento: visa a transformação de um grupo de requisitos em um produto ou software.</li>
    <li>Operação: visa a operação do produto no ambiente para o qual foi designado e visa a provisão de suporte para seus usuários.</li>
    <li>Manutenção: visa a modificação do software e, posteriormente, sua liberação para utilização.</li>
</ul>          
    
<h4> 2.2 Processos de Apoio</h4>
<p>
    Os processos de apoio dão auxílio a outros processos que são utilizados da medição e garantia da qualidade, porém não são fundamentais. São estes:
<p>

<ul>
    <li>Documentação: providenciar e sustentar os registros de dados do software;</li>
    <li>Gerência de Configuração: determinar e manter a lhaneza dos produtos de trabalho de um processo do projeto;</li>
    <li>Garantia da Qualidade: garantir que os processos e os produtos estão de acordo com as normas e/ou os requisitos preestabelecidos;</li>
    <li>Verificação: verificar e assegurar que o produto/serviço está de acordo com os requisitos pré-definidos;</li>
    <li>Validação: assegurar que os requisitos específicos são atendidos;</li>
    <li>Revisão Conjunta: proporcionar o entendimento (com os stakeholders);</li>
    <li>Auditoria: determinar a conformidade do produto e dos processos contra os requisitos definidos;</li>
    <li>Resolução de Problema: garantir que todos os problemas sejam verificados e corrigidos;</li>
    <li>Usabilidade: promover a simplicidade e facilidade da utilização do produto/serviço;</li>
    <li>Gerência de Solicitação de Mudanças: providenciar e manter os processos de gerência de mudanças.</li>
    <li>Avaliação do Produto: assegurar, por meio de exame e medição sistemáticos, que o produto/serviço está suprindo as necessidades explícitas e implícitas dos utilizadores.</li>
</ul>

<h4> 2.3 Processos Organizacionais </h4>

<P>
    Os processos organizacionais dão suporte à organização e à gestão geral destes processos e têm a possibilidade de serem aplicados fora do domínio dos projetos e contratos específicos, o que os tornam úteis para a organização como um todo. São estes:
</P>

<ul>
    <li>Gerência: responsável pela organização, monitoração e controle do início e controle da performance do processo.</li>
    <li>Infraestrutura: responsável por assegurar que a estrutura tenha estabilidade e maior confiabilidade.</li>
    <li>Melhoria: processo que define, faz avaliação, controla e provê melhorias em um processo de ciclo de vida do software.</li>
    <li>Recursos Humanos: responsável por providenciar e dar suporte aos recursos humanos necessários que têm consistência com o negócio.</li>
</ul>


<h4> 2.4 Processos de Adaptação </h4>
<p>
    Os processos de adaptação fazem a definição das atividades que são
    necessárias na execução das aplicações. Os processos se adaptam a:
</p>
<ul>    
    <li>Projeto;</li>
    <li>Cultura;</li>
    <li>Organização;</li>
    <li>Modelo de ciclo de vida, funções e técnicas, e Linguagens;</li>
<ul>

<h5>Processos de Reuso do Software</h5>

<p>
    O reúso de software, segundo Mariani (2016), “no contexto da Engenharia de
    Software, refere-se à criação de software a partir de componentes, ideias ou
    processos já existentes”. O reúso é “[...] relativo ao aproveitamento de soluções
    para problemas similares” (MARIANI, 2016).
</p>
<p>
    Como citado acima, o conceito de reúso de software resume-se na
    incorporação de produtos e/ou processos existentes em novos produtos. É um
    processo específico do desenvolvimento de software, incorporado na atualização de
    2008 da ISO/IEC 12207.
</p>

## Benefícios da Norma

## Desafios da Implementação

## Obtendo a Certificação

## Obtendo a Certificação no Brasil?

## Empresas Brasileiras Certificadas

## Relato de Adoção pelo Banco Central

<p>Segundo a <a href="https://docplayer.com.br/81749182-Experiencia-de-implantacao-de-um-processo-de-desenvolvimento-de-software-no-banco-central-do-brasil.html">implementação feita pelo Banco Central</a> houve uma necessidade de mudança em relação ao processo e infra-estrutura para o desenvolvimento multiplataforma do Banco Central do Brasil, onde inicialmente foi observado:</p>

<ul>
  <li>baixa produtividade,</li>
  <li>ambiente instável e falta de padrões,</li>
  <li>ausência de soluções de segurança e infra-estrutura,</li>
  <li>nenhum monitoramento,</li>
  <li>desconhecimento da tecnologia</li>
</ul>

<details>
  <summary>Os objetivos visados pelo Banco</summary>
  <ul>
    <li>modernização tecnológica disciplinada,</li>
    <li> maior produtividade e melhor qualidade no desenvolvimento e operação de sistemas,</li>
    <li> soluções amigáveis, estáveis, confiáveis, integradas com o legado e produzaidas em espaço de tempo compatível e que falicitem sua fatura manutenção,
    definições e diretrizes claras sobre a arquitetura a ser seguida,</li>
    <li> agilizar ao máximo o trabalho dos desenvolvedores com as soluções de infra-estrutura</li>
  </ul>
</details>


<details>
  <summary>As principais vantagens buscadas com a adoção da nova tecnologia</summary>
  <ul>
    <li>melhoria na apresentação (soluções web based),</li>
    <li>independência de plataforma (hardware e software),</li>
    <li>redução de custos,</li>
    <li>reusabilidade</li>
  </ul>
</details>

### Preparação para adaptação a norma

<p> Foi necessário definir grupos, os quais tinha como objetivo fazer a definição do processo e iniciar a componentização; uma divisão em equipes com foco no ferramental, infra-estrutura para suportar os ambientes de desenvolvimento e definição dos padrões referentes a dados; e um escritório de projetos. </p>

<p> Para disseminar a mudança foi necessário adquirir externamente através de contratação consultoria para validação, treinamento técnico e gerencial e consultoria para acompanhamento de 14 projetos-piloto, e internamente: </p>

<ul>
  <li>separar uma equipe interna para suporte, acompanhamento, resolução de problemas e evolução do processo,</li>
  <li>divulgar constantemente através de palestras, cursos internos,</li>
  <li>utilizar portal do desenvolvedor, e informativo técnico,</li>
  <li>reuniões de inspeção/revisão</li>
</ul>

### Atividades desempenhadas na implantação

<p> Para a implantação foram definidos processos para os projetos pequenos e médios, onde nos projetos médios todas as disciplinas técnicas são desempenhadas tanto nas fases de elaboração quanto na fase de contrução, em projetos pequenos as disciplinas técnicas aparecem mais segregadas. </p>

<p> A infra estrutura foi outro ponto de atenção, nesse quesito uma nova solução arquitetural foi criada, bem como gerência de configuração, atenção maior com tratamento de erros, soluções de segurança, publicação e monitoramento, acesso ao legado, biblioteca de componentes corporativos e toda a solução feita, levando em consideração tanto o processo quanto a infra-estrutura buscou maximizar a reutilização dos componentes, participação dos clientes no projeto das aplicações e qualidade do produto final. </p>

### Inovação e Resultados alcançados

<p>O Banco central foi o pioneiro a aplicar as mudanças no processo de software buscando as melhores práticas, sendo o destaque até quando se trata de empresas privadas, as mudanças iniciadas anos atrás, segundo a <a href="https://docplayer.com.br/81749182-Experiencia-de-implantacao-de-um-processo-de-desenvolvimento-de-software-no-banco-central-do-brasil.html">implementação feita pelo Banco Central</a> estão sendo implementadas atualmente por diversas instituições públicas.</p>

<p>Os resultados alcançados são refletidos publicamente: </p>

<ul>
  <li> Pelo Desenvolvedores:</li>
    <ul>
        <li>caminho a ser seguido + infra-estrutura = maior produtividade e qualidade,</li>
        <li>facilidade na manutenção dos sistemas (padrões, documentação)</li>
    </ul>    
  <li>Banco Central, Sistema Financeiro Nacional e Cidadão:</li>
    <ul>
      <li>melhor qualidade e usabilidade das aplicações disponibilizadas para sociedade,</li>
      <li>melhores soluções suportando as atividades do Banco Central = melhor atuação do Banco Central,</li>
      <li>melhor aproveitamento dos recursos públicos (independência de plataforma, maior produtividade, reuso),</li>
      <li>integração com outras organizações (utilizaçõa de web services),</li>
      <li>garantia de qualidade dos dados mantidos pelo Banco Central (componentes corporativos)</li>
    </ul>
</ul>

<p> E após mensurar foram obtidos os seguintes resultados: </p>

<ul>
  <li>100% das novas aplicações são desenvolvidas dentro dos padrões, são acessíveis via web, utilização a solução arquitetural padrão e têm documentação adequada e suficiente,</li>
  <li>100% das novas aplicações são independentes de tecnologia, o que possibilita a redução de custos com aquisição/manutenção de produtos/serviços;</li>
  <li>aplicações independentes de pessoas, facilitando manutenção;</li>
  <li>a utilização do Processo de Desenvolvimento de Software do Banco Central possibilitou a utilização de fábricas de software: foi criada, em novembro/2003, a primeira fábrica de software interna ao Banco Central;</li>
  <li>a biblioteca de componentes já conta com mais de 20 componentes corporativos;</li>
  <li>Grupo de Garantia da Qualidade já inspecionou mais de 12 projetos, visando eliminar/minimizar problemas, garantir aderência aos padrões, garantir a utilização dos componentes corporativos, etc.</li>
  <li>a criação da solução de acesso ao legado possibilitou a migração de uma aplicação crítica, que fazia uso de camada de integração desenvolvida por terceiros, o que representou, de imediato, uma economia de aproximadamente R$ 300.000,00 ao ano, além de ter tornado a aplicação mais rápida.</li>
</ul>

<details>
  <summary>Ganhos Comprovados</summary>
  <ul>
    <li>padronização de processos, produtos e serviços;</li>
    <li>redução de custos com aquisição/manutenção de produtos/serviços;</li>
    <li>processo de capacitação mais direcionado;</li>
    <li>maior agilidade na implementação física de aplicações;</li>
    <li>melhor aproveitamento dos desenvolvedores;</li>
    <li>facilidade no diagnóstico de problemas na arquitetura de aplicações;</li>
    <li>facilidade no desenvolvimento descentralizado e/ou parcerias;</li>
    <li>maior confiabilidade, escalabilidade e disponibilidade dos serviços de TI;</li>
    <li>garantia de interoperabilidade das aplicações.</li>
  </ul>
</details>

<details>
  <summary>Repercussões positivas com a implantação</summary>
  <ul>
    <li>melhoria da motivação das equipes de desenvolvimento;</li>
    <li>maior atratividade para novos funcionários;</li>
    <li>melhor aproveitamento dos recursos existentes nas regionais, com conseqüente motivação de seus profissionais;</li>
    <li>melhoria no emprego de recursos públicos;</li>
    <li>melhoria na atuação do Banco Central em suas funções;</li>
    <li>atendimento aos requisitos de usabilidade de nossos clientes;</li>
    <li>melhoria no atendimento ao público externo ao banco, com facilidade de acesso a informações via sistemas web;</li>
    <li>melhoria da imagem do Banco Central frente à sociedade.</li>
  </ul>
</details>

## Conclusão
