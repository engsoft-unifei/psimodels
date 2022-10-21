---
layout: ../../layouts/PostLayout.astro
title: "Norma ISO/IEC 12207"
description: "Apresentação da Norma ISO/IEC 12207"
author: "Alexsander Ventricci, Augusto Lázaro Raimundo, Carlos Henrique Silva Pinto, Guilherme Vieira, Rafael Mariano da Silva Andrade"
date: "17 Oct 2022"
banner: "bg-yellow-200"
---

- [Introdução](#introdução)
- [História e Objetivo](#história-e-objetivo)
- [Etapas, estratégias, organização da norma para garantir a qualidade do processo de desenvolvimento de software](#etapas-estratégias-organização-da-norma-para-garantir-a-qualidade-do-processo-de-desenvolvimento-de-software)
- [Benefícios da Norma](#benefícios-da-norma)
- [Desafios da Implementação](#desafios-da-implementação)
- [Como obrter a Certificação ISO/IEC 12207](#como-obrter-a-certificação--isoiec-12207)
  - [Conformidade Total](#conformidade-total)
  - [Conformidade personalizada](#conformidade-personalizada)
- [Tem Certificação no Brasil?](#tem-certificação-no-brasil)
- [Como Obter Essa Certificação no Brasil?](#como-obter-essa-certificação-no-brasil)
- [Empresas Brasileiras Certificadas na Norma](#empresas-brasileiras-certificadas-na-norma)
- [Relato de Adoção pelo Banco Central](#relato-de-adoção-pelo-banco-central)
  - [Preparação para adaptação a norma](#preparação-para-adaptação-a-norma)
  - [Atividades desempenhadas na implantação](#atividades-desempenhadas-na-implantação)
  - [Inovação e Resultados alcançados](#inovação-e-resultados-alcançados)

## Introdução

<p>A ISO/IEC 12207 tem como objetivo estabelecer uma estrutura comum para o processo de ciclo de vida de software. Este artigo descreve seus
processos, atividades e tarefas, a história de sua criação, benefícios, desafios
comuns para sua implementação, seu processo de certificação no Brasil e estudo de caso sobre sua utilização</p>

## História e Objetivo

<p>
A primeira versão da ISO/IEC 12207 foi publicada em primeiro de julho de 1995, pela International Organization for Standardization, com o objetivo de estabelecer padrões para
o processo de ciclo de vida de software [ISO 12207:2017(E) 2017]. Ela foi o primeiro
padrão a fornecer um conjunto tão abrangente de definições a respeito do ciclo de vida
de software, suas atividades, tarefas e processos. A versão mais recente desta norma é
a ISO/IEC/IEEE 12207: 2017 Systems and software engineering — Software life cycle
processes.
</p>
<p>
Sua idealização, assim como outras normas e padrões da mesma época, foi
motivada pelo fenômeno conhecido como crise do software. O termo crise do software é utilizado para descrever a dificuldade de se fazer estimativas de tempo e escopo
para projetos de softwares cuja complexidade e tamanho escalam de forma exponencial
[Fitzgerald 2012].
</p>

[ISO](https://i.imgur.com/xdslfzY.jpg)

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
</ul>

<h4>Processos de Reuso do Software</h4>

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

[Processos](https://i.imgur.com/1oG1k80.png)

## Benefícios da Norma

<p>
Com a crescente busca por softwares de qualidade no mercado atual, as empresas perceberam a necessidade da utilização de normas padronizadas que especificam requisitos e boas práticas do que fazer para obter um produto de qualidade através do processo de desenvolvimento de software, visando entregar produtos para satisfazer o cliente. A Norma ISO/IEC 12207 provê uma estrutura para uma organização definir um linguajar comum em meio ao grande número de métodos, técnicas, modelos e normas que tratam da qualidade. Ela permite padronizar os processos de desenvolvimento, garantindo uma melhor qualidade no software, utilizando-se de métodos sistêmicos que diminuirão erros na modelagem, e por consequência a manutenção exagerada, poderá reduzir ou eliminar custos indevidos e acabar com o tempo desnecessário dedicado ao retrabalho. Essa norma monitora o andamento do projeto para determinar se eles estão de acordo com os padrões da qualidade, e identificar formas de prevenir as causas dos resultados insatisfatórios. Além de que as implementações das normas ISO possuem segurança dos dados, maior confiabilidade para os clientes, procedimentos claros e segurança do ciclo de vida do desenvolvimento de software.
</p>

## Desafios da Implementação

<p>
A ISO/IEC 12207 possui grande flexibilidade, podendo acompanhar a evolução da engenharia de software nas diversas culturas organizacionais, pois não tem nenhuma ligação com métodos, ferramentas, treinamentos, métricas ou tecnologias empregadas. Ela pode ser utilizada com qualquer modelo de ciclo de vida, método ou técnica de engenharia de software e linguagem de programação.Embora flexível, ela possui algumas limitações que podem gerar desafios ou desconfortos ao ser implementada.
</p>
<ul>
  <li>Ela não especifica os detalhes de como implementar ou executar as atividades e tarefas incluídas nos processos de ciclo de vida de software;</li>
  <li>Não pretende prescrever o nome, formato ou conteúdo explícito na documentação a ser produzida. A Norma pode requerer o desenvolvimento de documentos de mesma categoria ou tipo, contudo não sugere que tais documentos sejam desenvolvidos ou emitidos separadamente ou combinados de alguma forma. Estas decisões são deixadas para o usuário da Norma;</li>
  <li>Não prescreve um modelo específico de ciclo de vida ou método de desenvolvimento de software. As partes envolvidas com esta Norma são responsáveis pela seleção de um modelo de ciclo de vida para o projeto de software e pelo mapeamento dos processos, atividades e tarefas da Norma dentro do modelo. As partes envolvidas são também responsáveis pela seleção e aplicação dos métodos de desenvolvimento de software e pela execução das atividades e tarefas adequadas ao projeto de software;</li>
  <li>Não pretende entrar em conflito com quaisquer políticas, normas ou procedimentos já existentes na organização. Entretanto, qualquer conflito necessita ser resolvido e quaisquer condições e situações de sobreposição precisam ser citadas por escrito como exceções para a aplicação da Norma.</li>
</ul>

## Como obrter a Certificação ISO/IEC 12207

<p>
Para obter a certificação, as empresas contratam organizações de auditoria cuja missão avalia a conformidade dos funcionários às normas ISO. Os auditores passam alguns dias no local da empresa e analisam documentos de requisitos, resultados de testes, metodologia de teste e práticas de manutenção. Frequentemente, as empresas realizam suas próprias auditorias internas para verificar a conformidade antes de trazer um avaliador externo.

O documento oficial da ISO/IEC 12207 fornece requisitos para vários processos adequados durante o ciclo de vida do sistema ou produto de software. Reconhece-se que projetos ou organizações específicos podem não precisar usar todos os processos fornecidos por este documento. Portanto, a implementação deste documento normalmente envolve selecionar e declarar um conjunto de processos adequados à organização ou projeto. Há duas maneiras de reivindicar que uma implementação está em conformidade com as disposições deste documento: conformidade total e conformidade personalizada.

</p>

### Conformidade Total

<p>
Existem dois critérios para reivindicar a conformidade total. Atingir qualquer critério é suficiente para a conformidade, embora o escolhido (ou critérios) deva ser declarado na reivindicação. Reivindicar “conformidade total com as tarefas” afirma que todos os requisitos das atividades e tarefas do conjunto declarado de processos são atendidos. Alternativamente, alegar “conformidade total com os resultados” afirma que todos os resultados exigidos do conjunto declarado de processos são alcançados. A plena conformidade com os resultados permite maior liberdade na implementação de processos de conformidade e pode ser útil para a implementação de processos a serem usados no contexto de um modelo de ciclo de vida inovador.
</p>

<p>
**Conformidade total com os resultados:** A total conformidade com os resultados é alcançada demonstrando que todos os resultados do conjunto declarado de processos foram alcançados. Nessa situação, as provisões para atividades e tarefas do conjunto de processos declarados são orientações e não requisitos, independentemente da forma verbal utilizada na provisão.
Um dos objetivos do documento da norma é facilitar a avaliação e a melhoria do processo. Para tanto, os objetivos de cada processo são escritos na forma de 'resultados' compatíveis com as disposições da ISO/IEC 33002. Essa norma prevê a avaliação dos processos deste documento, fornecendo uma base para melhoria. Os usuários que pretendem avaliar e melhorar o processo podem usar os resultados do processo escritos neste documento como o “modelo de referência de processo” exigido pela ISO/IEC 33002.
</p>

<p>
**Conformidade total com as tarefas:** A plena conformidade com as tarefas é alcançada demonstrando que todos os requisitos das atividades e tarefas do conjunto declarado de processos foram alcançados. Nessa situação, as provisões para os resultados do conjunto de processos declarados são orientações e não requisitos, independentemente da forma verbal usada na provisão.
</p>

### Conformidade personalizada

Quando este documento é usado como base para estabelecer um conjunto de processos que não se qualificam para conformidade total, as cláusulas deste documento são selecionadas ou modificadas de acordo com o processo de adaptação prescrito no Anexo A. O texto adaptado, para o qual a conformidade personalizada é reivindicado, é declarado. A conformidade personalizada é alcançada demonstrando que os resultados, atividades e tarefas, conforme a personalização, foram alcançados.

## Tem Certificação no Brasil?

Até 2017 existia uma norma brasileira referente à ISO/IEC 12207, a  ABNT NBR ISO/IEC 12207:2009. No entanto, uma nova versão da norma internacional foi editada em 2017, que é a que temos atualmente, mas a versão brasileira foi cancelada em 30/08/2017 e não temos por enquanto uma nova edição vigente. Essa alteração da norma internacional é significativa, pois a estrutura anterior da versão 2009 era bem mais complexa com inúmeros processos a mais, que foram excluídos ou renomeados nessa nova versão.

Atualmente as empresas brasileiras, como alternativa a essa norma brasileira, obtêm a certificação MPS-BR (Melhoria de Processo de Software Brasileiro). O Modelo de Referência MPS-BR tem como objetivo melhorar a qualidade e a produtividade do software brasileiro, e foi desenvolvido com base nas normas ISO 15504 e ISO 12207. O Modelo, no entanto é voltado para a realidade brasileira, oferecendo custos mais acessíveis de implantação do que outras normas e padrões como o CMMI (Capability Maturity Model Integration).

## Como Obter Essa Certificação no Brasil?

Para conseguir a certificação MPS-BR, a empresa precisa ser avaliada por uma instituição credenciada junto à Softex, uma organização social civil de interesse público que atua há 25 anos em prol do fomento da Transformação Digital Brasileira, criando, promovendo e executando iniciativas no âmbito nacional e internacional nas áreas de tecnologia e inovação. A ideia é seguir um protocolo padronizado que quebra esse processo em três passos principais. São eles:

**Etapa de planejamento:** Nessa primeira etapa, é definido o escopo da avaliação — que envolve a definição da unidade organizacional, o local onde a empresa presta o serviço (pode até ser mais de um local) e quais de seus projetos compõem a amostra da avaliação.

**Etapa de avaliação inicial:** Em um momento seguinte, a equipe da instituição avaliadora vai até a empresa e analisa os documentos e produtos relacionados à execução dos processos — como planos, relatórios, produtos técnicos relacionados à engenharia de software ou à gestão do serviço de TI. Após a avaliação inicial, a empresa tem um relatório com problemas que ela precisa resolver para a última etapa.

**Etapa de avaliação final:** Na avaliação final, a equipe volta à empresa para verificar a resolução dos problemas e conduzir entrevistas com as pessoas que participaram dos processos. Com base na análise dos documentos e nas entrevistas, a equipe de avaliação atribui o nível da empresa, que pode ser desde o nível G (o mais básico) até o nível A (nível mais alto de maturidade).

A escolha do nível é feita na etapa de planejamento, em que a empresa define qual nível quer atingir. Assim, a execução da avaliação é direcionada ao escopo escolhido pela empresa.

## Empresas Brasileiras Certificadas na Norma

Como citado anteriormente, a ISO/IEC 12207 não possui mais uma versão no Brasil, entretanto podemos citar algumas empresas que conseguiram a certificação MPS-BR, como é o caso das empresas catarinenses Poligraph, Next Millenium/Dualline, Ilog Tecnologia e CNX/Boreste. As quatro empresas participaram de um projeto cooperado organizado no início de 2007 pela Associação Catarinense de Empresas de Tecnologia (ACATE) para auxiliar as associadas no processo de conquista do MPS-BR. A Poligraph conquistou o Nível F do modelo e Dualline, Ilog e Boreste, o Nível G.

O objetivo do projeto cooperado foi implementar uma série de melhorias no processo de desenvolvimento de software das empresas, especialmente nas áreas de gerenciamento de requisitos, gerenciamento de projetos, e qualidade. Dos retornos obtidos desse projeto, podemos citar:

- a melhoria dos processos dentro das empresas;
- a melhoria da qualidade final dos produtos;
- maior controle na gestão de projetos de desenvolvimento;
- a ampliação da competitividade das empresas; e
- resultados para a equipe interna das empresas, como por exemplo, uma diminuição significativa no tempo e esforço de habilitar um novo colaborador para desenvolver.

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

## Material Complementar

<p>Imagens: </p>[Etapas](https://i.imgur.com/Sg65N6f.png), [Processos](https://i.imgur.com/1oG1k80.png) e [Estados](https://i.imgur.com/Y95Akfj.png)
<p>Vídeo: </p>[Vídeo com slides](https://youtu.be/Tz_fWtEzZlc)
