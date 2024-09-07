# Capítulo 7

### Testes Voltados para a Tecnologia que Dão Suporte à Equipe

#### **Visão Geral**

No desenvolvimento ágil, os testes voltados para a tecnologia que dão suporte à equipe são fundamentais. Eles formam a base para garantir que o código produzido seja de alta qualidade e que atenda aos requisitos definidos. O primeiro quadrante dos Quadrantes de Teste Ágil se concentra em garantir que a base técnica do software esteja sólida, o que é essencial para o sucesso contínuo da equipe.

#### **Objetivo dos Testes do Quadrante 1**

- **Testes de Unidade e Componentes:** O objetivo principal desses testes é garantir que cada peça do código funcione conforme o esperado e que o design do sistema seja sólido. Testes de unidade verificam o comportamento de pequenas unidades de código, como métodos ou objetos, enquanto testes de componentes avaliam a interação entre essas unidades em um nível mais amplo.
  
- **Apoio ao Design:** Testes de unidade e componentes não são apenas para validar o código depois de escrito, mas também ajudam a orientar o design. No Test-Driven Development (TDD), por exemplo, os testes são escritos antes do código, ajudando a definir claramente o que o código precisa fazer e promovendo um design mais eficiente e testável.

- **Minimização de Bugs:** Ao escrever testes antes do código, a equipe pode evitar a maioria dos bugs no nível da unidade. Isso reduz a quantidade de tempo gasto na fase de teste posterior e permite que o desenvolvimento continue com menos interrupções.

#### **Infraestrutura de Suporte**

- **Controle de Código-Fonte e Gerenciamento de Configuração:** Essenciais para saber o que está sendo testado e garantir que as alterações no código sejam corretamente gerenciadas.

- **Integração Contínua:** Permite a execução automática de testes sempre que o código é alterado. Isso ajuda a identificar e corrigir problemas rapidamente, além de incentivar os programadores a realizar testes antes de fazer commit do código.

- **Compilações Automatizadas:** Fornecem pacotes de código prontos para testes e ajudam a manter um padrão de qualidade ao longo do desenvolvimento.

#### **Por que Escrever e Executar Esses Testes?**

- **Velocidade e Eficiência:** Embora a velocidade não deva ser o objetivo final, a qualidade interna do código pode levar a uma entrega mais rápida e eficiente. Testes automatizados e integrações contínuas ajudam a encontrar e corrigir erros rapidamente, mantendo o código de qualidade e reduzindo a dívida técnica.

- **Foco na Qualidade:** Com uma base sólida de testes, os testadores podem se concentrar em testes mais profundos e exploratórios, em vez de gastar tempo corrigindo bugs de baixo nível.

- **Desenvolvimento Orientado a Testes (TDD) vs. Desenvolvimento Test-First:** 
  - **TDD (Test-Driven Development):** Envolve escrever testes antes do código, orientando o design e minimizando bugs.
  - **Test-First:** Refere-se a escrever testes antes do código de produção, mas não necessariamente a um design emergente como no TDD. Pode ser aplicado em diferentes níveis, dependendo da necessidade do projeto.

#### **Conclusão**

Os testes do Quadrante 1 são cruciais para o desenvolvimento ágil porque formam a base sobre a qual os outros tipos de testes são construídos. Ao adotar práticas como TDD e integração contínua, as equipes podem melhorar a qualidade do código, reduzir a dívida técnica e entregar software de forma mais eficiente e confiável. Essas práticas não só ajudam na detecção precoce de problemas, mas também promovem um design de software mais robusto e testável.

### Facilitando o Trabalho dos Testadores com Testes Voltados para a Tecnologia

#### **Infraestrutura e Práticas**

**1. Sandboxes para Programadores**
Os programadores utilizam ambientes isolados para testar novos códigos sem interferir no trabalho de outros membros da equipe. Esse isolamento garante que o código seja testado de forma independente antes de ser integrado ao repositório principal.

**2. Testes de Regressão**
Antes de fazer o check-in do código, os programadores realizam testes de regressão em suas áreas restritas para garantir que novas alterações não introduzam bugs. Esse processo ajuda a manter a qualidade do código e reduz a quantidade de problemas que precisam ser corrigidos posteriormente.

**3. Dados e Ambientes de Teste**
- **Objetos Falsos e Dados Realistas:** Testes de unidade frequentemente utilizam objetos falsos para simular a funcionalidade sem acessar bancos de dados reais, o que acelera o processo de teste. No entanto, é crucial que os dados de teste representem dados reais para minimizar problemas na fase posterior.
- **Ambientes de Teste Independentes:** Configurar ambientes de teste independentes permite que os testes sejam realizados sem interferência de outros testes. Isso é essencial para garantir que cada teste seja executado em condições controladas e confiáveis.

**4. Exemplo da História de Lisa**
Lisa compartilha sua experiência com a adoção de práticas ágeis e a implementação de infraestrutura para suporte a testes. Inicialmente, sua equipe enfrentou desafios com a falta de testes automatizados e infraestrutura de testes, mas ao adotar práticas como integração contínua e ambientes de teste independentes, conseguiu melhorar a eficiência dos testes.

#### **Design Testável e Arquitetura**

**1. Desenvolvimento com Testes em Mente**
Ao escrever código com a intenção de torná-lo testável, os programadores garantem que o software possa ser testado de forma eficiente. Isso envolve considerar como os testes serão executados e automatizados desde o início do desenvolvimento.

**2. Arquitetura em Camadas**
Uma arquitetura em camadas separa as diferentes funcionalidades do aplicativo em camadas horizontais, como interface do usuário, lógica de negócios e acesso a dados. Essa separação facilita o teste de cada camada de forma independente, utilizando simuladores ou stubs para interagir com camadas inferiores.

**3. Abordagem do "Aplicativo Estrangulador"**
A abordagem do "aplicativo estrangulador", proposta por Martin Fowler, envolve reescrever o sistema legada em uma nova arquitetura enquanto mantém o sistema antigo operacional. Isso permite a implementação gradual de novas práticas de teste e design, eventualmente substituindo o sistema legado.

**4. Padrão Ports and Adapters**
O padrão Ports and Adapters, de Alistair Cockburn, sugere criar aplicativos que possam funcionar sem a necessidade de uma interface de usuário ou banco de dados para permitir testes automatizados. As portas aceitam eventos externos e adaptadores convertem esses eventos em mensagens compreendidas pelo aplicativo.

**5. Desafios com Sistemas Legados**
Trabalhar com sistemas legados pode ser desafiador, especialmente quando o código não foi projetado para ser testável. Técnicas como "resgate de código legado" e "aplicativo estrangulador" ajudam a transitar para novas arquiteturas de forma gradual. Além disso, práticas como o desenvolvimento de módulos pequenos e testes de UI automatizados, como demonstrado no exemplo de John Voris, podem ser eficazes.

#### **Conclusão**

Facilitar o trabalho dos testadores envolve mais do que apenas escrever testes; é sobre criar uma infraestrutura e um design que suportem e promovam a testabilidade. Desde a adoção de práticas ágeis e ferramentas de suporte até a reestruturação da arquitetura para melhorar a testabilidade, todas essas abordagens contribuem para um processo de desenvolvimento mais eficiente e de alta qualidade. Adotar uma mentalidade orientada a testes desde o início e investir em uma arquitetura flexível são passos fundamentais para alcançar um software bem testado e de alta qualidade.

### Facilitando o Trabalho dos Testadores com Feedback Oportuno

No desenvolvimento ágil, a velocidade do feedback dos testes é crucial para manter a eficiência e a qualidade do trabalho. O objetivo é garantir que os testes sejam executados rapidamente para que os problemas possam ser identificados e corrigidos sem atrasos significativos. Aqui estão as práticas e estratégias recomendadas para facilitar o trabalho dos testadores e garantir um feedback ágil:

#### **1. Importância do Feedback Rápido**

- **Velocidade do Feedback:** O maior valor dos testes de unidade está na rapidez com que eles fornecem feedback. Um processo de integração contínua e construção deve ter um tempo de execução ideal de cerca de 10 minutos para compilações e testes de unidade. Testes mais lentos devem ser executados separadamente para evitar atrasos nos processos rápidos.
  
- **Compilação e Teste Rápidos:** Se o processo de compilação e teste demorar mais do que 10 minutos, a acumulação de mudanças pode se tornar um problema, resultando em atrasos e frustrações. É fundamental garantir que a compilação e os testes sejam realizados rapidamente para manter a eficiência da equipe.

#### **2. Estratégias para Melhorar o Desempenho dos Testes**

- **Uso de Objetos Falsos:** Para testes de unidade, considere o uso de objetos falsos em vez de bancos de dados reais. Isso reduz o tempo necessário para executar os testes e melhora a eficiência geral.
  
- **Separação de Testes:** Mova testes de integração e acesso ao banco de dados para processos secundários de compilação e teste que podem ser executados separadamente. Isso permite que os testes de unidade sejam executados rapidamente, enquanto os testes mais demorados são processados em paralelo.

- **Execução Paralela de Testes:** Sempre que possível, execute testes em paralelo para reduzir o tempo total de execução. Isso pode ser feito distribuindo tarefas entre múltiplos computadores de compilação ou atualizando hardware e software.

- **Análise e Otimização:** Identifique e analise as partes do processo de compilação e teste que levam mais tempo. Tome medidas incrementais para otimizar essas áreas, seja refatorando testes, removendo testes desnecessários ou atualizando a infraestrutura.

#### **3. Exemplo de Implementação**

A história de Lisa ilustra como uma equipe pode otimizar seus processos de compilação e teste:

- **Início com Testes de Fumaça:** No início, a equipe começou com testes de fumaça de GUI em sua compilação contínua, mas com o crescimento da base de código, os testes de unidade passaram a dominar a compilação contínua. Os testes de GUI e outros testes mais demorados foram movidos para um processo separado executado à noite.

- **Otimização Contínua:** Com o tempo, a equipe trabalhou para reduzir o tempo de compilação contínua de mais de 15 minutos para cerca de 8 minutos, através de refatoração de testes, uso de objetos fictícios e atualização de hardware e software.

- **Máquina de Compilação Dedicada:** Para evitar a interrupção do feedback rápido, a equipe adquiriu uma segunda máquina de compilação dedicada para testes mais longos, mantendo assim a eficiência das compilações contínuas e do feedback rápido.

#### **4. Testes Voltados para a Tecnologia vs. Testes Voltados para os Negócios**

- **Testes Voltados para a Tecnologia:** Focam na qualidade técnica e na testabilidade do código. Eles garantem que o código esteja correto e funcione conforme o esperado em um nível técnico. Isso inclui testes de unidade e de integração técnica.

- **Testes Voltados para os Negócios:** Focam na validação dos requisitos e na experiência do usuário. Eles garantem que o software atenda aos requisitos de negócios e funcione corretamente do ponto de vista do usuário final. Isso pode incluir testes de funcionalidade, usabilidade e aceitação.

#### **5. Considerações Finais**

- **Equilíbrio Necessário:** É importante equilibrar os testes voltados para a tecnologia e os testes voltados para os negócios. Ambos são necessários e complementares, com cada um cobrindo aspectos diferentes do sistema. Enquanto os testes de unidade garantem que o código técnico esteja correto, os testes voltados para os negócios asseguram que a funcionalidade atenda às necessidades do usuário.

- **Continuidade e Melhoria:** A equipe deve continuar revisando e melhorando suas práticas de teste para garantir eficiência e qualidade contínuas. A revisão da arquitetura, a otimização dos processos e a adaptação das estratégias de teste são essenciais para manter o desempenho e a eficácia dos testes.

Ao implementar essas práticas e estratégias, a equipe pode melhorar significativamente a eficiência dos testes e a velocidade do feedback, facilitando o trabalho dos testadores e promovendo um desenvolvimento ágil e de alta qualidade.


### Facilitando a Adoção de Práticas Ágeis e Testes Automatizados

Quando uma equipe de desenvolvimento não adota práticas ágeis como TDD (Test-Driven Development) e integração contínua, e a equipe de testes deseja promover essas práticas, é importante adotar uma abordagem estratégica e colaborativa. Aqui estão algumas maneiras eficazes de ajudar a equipe a fazer essa transição:

#### **1. Abordagem de Testadores**

- **Evangelizar com Exemplo:** Embora os testadores possam não ter a mesma autoridade que os desenvolvedores na adoção de TDD, você pode demonstrar o valor das práticas de teste ao fornecer exemplos práticos e casos de sucesso. Compartilhar estudos de caso, histórias de sucesso e benefícios tangíveis pode ser persuasivo.

- **Promover Discussões e Workshops:** Organize sessões de "brown bag" (almoços informais) ou workshops onde todos possam aprender e discutir sobre TDD e outras práticas ágeis. A ideia é criar um espaço para que todos expressem suas preocupações e ideias sobre como essas práticas podem ser benéficas.

- **Encontrar Aliados:** Identifique desenvolvedores que já estão abertos a novas práticas ou que possam se tornar defensores do TDD. Trabalhar com esses aliados pode ajudar a construir um caso mais forte e incentivar outros a seguir o exemplo.

- **Mostrar Benefícios Diretos:** Ajude a equipe a ver como TDD e integração contínua podem melhorar a qualidade do código e reduzir o número de bugs. Testadores podem apresentar dados e exemplos de como essas práticas ajudaram a melhorar projetos anteriores ou projetos em outras empresas.

- **Facilitar a Experiência Prática:** Em vez de apenas promover a teoria, ofereça suporte prático, como treinamento ou ajuda na configuração inicial de ferramentas de testes. Isso pode reduzir a curva de aprendizado e permitir que a equipe experimente essas práticas sem grandes investimentos iniciais.

#### **2. Papel dos Gerentes**

- **Definir a Qualidade como Prioridade:** Como gerente, você pode influenciar a adoção de práticas ágeis definindo a qualidade como um objetivo central e garantindo que a equipe tenha tempo e recursos para implementar TDD e integração contínua.

- **Fornecer Treinamento e Recursos:** Ofereça treinamento especializado e traga especialistas em desenvolvimento ágil e automação de testes para capacitar a equipe. Investir em treinamento prático e na contratação de coaches pode acelerar a adoção dessas práticas.

- **Garantir Suporte de Ferramentas:** Certifique-se de que a equipe tenha acesso às ferramentas necessárias para implementar TDD e integração contínua. Isso inclui ferramentas de controle de versão, ferramentas de CI/CD (Integração Contínua/Entrega Contínua) e ambientes de testes automatizados.

- **Promover uma Cultura de Melhoria Contínua:** Incentive a equipe a adotar uma mentalidade de melhoria contínua e a experimentar novas práticas e ferramentas. Realize retrospectivas regulares para identificar áreas de melhoria e ajustar as práticas conforme necessário.

#### **3. Estratégias para a Equipe**

- **Implementar Retrospectivas e Feedback:** Use retrospectivas para discutir os desafios e sucessos da equipe na adoção de novas práticas. Encoraje a equipe a fornecer feedback sobre o que está funcionando e o que precisa ser ajustado.

- **Resolver Problemas em Conjunto:** Envolva toda a equipe na solução de problemas relacionados à adoção de práticas ágeis. Se houver resistência ou dificuldades, trabalhe em conjunto para encontrar soluções e ajustar a abordagem conforme necessário.

- **Criar um Ambiente de Suporte:** Desenvolva um ambiente onde a experimentação e a inovação sejam encorajadas. Isso pode incluir tempo reservado para aprender novas práticas e ajustar a arquitetura do sistema para melhorar a testabilidade.

- **Priorizar o Suporte de Infraestrutura:** Assegure-se de que a infraestrutura de desenvolvimento e teste suporte as novas práticas. Isso inclui ter ambientes de teste separados, ferramentas de integração contínua, e uma estrutura de código organizada e bem mantida.

#### **4. Ferramentas e Infraestrutura**

- **Controle de Código-Fonte:** O controle de código-fonte é essencial para qualquer prática de desenvolvimento ágil. Ele permite a gestão de versões, a colaboração entre desenvolvedores e a rastreabilidade de mudanças. Ferramentas como Git, SVN e Mercurial são amplamente utilizadas.

- **Integração Contínua (CI):** Ferramentas de CI como Jenkins, Travis CI e GitHub Actions ajudam a automatizar o processo de build e execução de testes. Elas garantem que o código seja integrado e testado frequentemente, identificando problemas rapidamente.

- **Automação de Testes:** Ferramentas para automação de testes, como Selenium para testes de UI, JUnit para testes de unidade, e frameworks de teste de integração como TestNG, são fundamentais para a eficácia dos testes automatizados.

- **Ferramentas de Gerenciamento de Configuração:** O gerenciamento eficaz de configuração ajuda a manter a consistência entre ambientes de desenvolvimento e produção. Ferramentas como Ansible, Puppet e Chef são úteis para gerenciar configurações e implantações.

#### **Conclusão**

A transição para práticas ágeis e testes automatizados pode ser desafiadora, mas é essencial para melhorar a qualidade e a eficiência do desenvolvimento de software. Testadores, gerentes e desenvolvedores devem colaborar para superar obstáculos e promover a adoção dessas práticas. A chave é construir uma cultura de qualidade e melhoria contínua, apoiar a equipe com treinamento e ferramentas adequadas e resolver problemas de forma colaborativa.

### Utilização de IDEs e Ferramentas no Desenvolvimento Ágil

Um **IDE (Ambiente de Desenvolvimento Integrado)** é uma ferramenta vital para programadores e testadores em uma equipe ágil. Ele integra várias funcionalidades em uma única interface, facilitando o desenvolvimento e a manutenção do código. Aqui está uma visão geral sobre como os IDEs e outras ferramentas essenciais podem apoiar uma equipe ágil:

#### **1. IDEs: O Papel e a Escolha**

**Funções Essenciais dos IDEs:**
- **Integração com Controle de Código-Fonte:** IDEs modernos integram-se com sistemas de controle de versão como Git e SVN, ajudando a gerenciar mudanças de código e evitar conflitos.
- **Suporte a Linguagens e Refatoração:** IDEs oferecem suporte para várias linguagens e ferramentas de refatoração, ajudando a manter o código limpo e organizado.
- **Detecção de Erros e Sugestões:** Fornecem feedback imediato sobre erros e sugestões de melhorias, facilitando a escrita de código de qualidade.

**Escolha do IDE:**
- **Preferências Pessoais:** Os desenvolvedores frequentemente têm preferências pessoais por certos IDEs como IntelliJ IDEA, Eclipse ou Visual Studio. A escolha pode depender da familiaridade, suporte à linguagem e recursos específicos.
- **Normas Organizacionais:** Às vezes, uma organização pode impor o uso de um IDE específico para padronizar o ambiente de desenvolvimento, facilitando o emparelhamento e a colaboração entre desenvolvedores.

**Exemplos de IDEs:**
- **Eclipse e NetBeans:** IDEs de código aberto amplamente usados, com suporte para uma ampla gama de linguagens e plugins.
- **IntelliJ IDEA:** IDE popular para desenvolvimento em Java, conhecido por suas poderosas ferramentas de refatoração.
- **Visual Studio:** IDE robusto da Microsoft, ideal para desenvolvimento .NET e C++.

#### **2. Ferramentas de Construção**

**Função das Ferramentas de Construção:**
- **Compilação e Empacotamento:** Essas ferramentas são usadas para compilar o código-fonte e empacotar o software em artefatos implantáveis (como JARs, WARs).
- **Automação e Integração:** Elas ajudam a automatizar o processo de construção, documentação e relatórios, integrando-se com IDEs e sistemas de controle de versão.

**Exemplos de Ferramentas de Construção:**
- **Ant e Maven:** Ferramentas para projetos Java que gerenciam a compilação, dependências e documentação.
- **Nant:** Uma ferramenta similar ao Ant, mas para projetos .NET.

#### **3. Ferramentas de Automação de Compilação**

**Importância da Integração Contínua:**
- **Execução Automatizada de Testes:** Ferramentas de integração contínua (CI) automatizam a execução de testes sempre que o código é alterado, garantindo que o código integrado não quebre.
- **Notificações e Relatórios:** Fornecem notificações e relatórios sobre o status da compilação e a saúde do projeto.

**Exemplos de Ferramentas de CI:**
- **Jenkins:** Uma ferramenta de CI de código aberto que suporta a automação de builds e testes.
- **TeamCity e Bamboo:** Ferramentas comerciais que oferecem recursos avançados para integração e entrega contínua.

#### **4. Ferramentas de Teste de Unidade**

**Função das Ferramentas de Teste de Unidade:**
- **Testes Automatizados:** São usadas para escrever e executar testes automatizados de unidade para garantir que cada parte do código funcione como esperado.
- **Suporte a Múltiplas Linguagens:** Existem variantes específicas para diferentes linguagens de programação.

**Exemplos de Ferramentas de Teste de Unidade:**
- **JUnit (Java), NUnit (.NET), PyUnit (Python):** Ferramentas de teste de unidade para suas respectivas linguagens.
- **RSpec e easyb:** Ferramentas para desenvolvimento orientado a comportamento (BDD).

**Objetos Fictícios e Stubs:**
- **EasyMock e Ruby/Mock:** Ferramentas que ajudam na criação de objetos fictícios e stubs para testes unitários.

#### **5. Integração de Ferramentas e Suporte para Linguagens Dinâmicas**

**Suporte a Linguagens Dinâmicas:**
- **IDEs como Eclipse e IntelliJ IDEA:** Oferecem suporte para linguagens dinâmicas como Ruby, Groovy e Python, além de ferramentas específicas para essas linguagens.
- **Ferramentas de Automação e Teste:** Ferramentas para essas linguagens frequentemente integram-se com IDEs, proporcionando uma experiência de desenvolvimento coesa.

**Ferramentas Adicionais:**
- **FishEye:** Permite aos testadores acessar o código-fonte e monitorar alterações.
- **Plugins e Extensões:** Muitas ferramentas e IDEs oferecem plugins para integração com ferramentas de teste e automação, facilitando a configuração e a manutenção.

### **Conclusão**

Utilizar um IDE adequado e ferramentas complementares é essencial para uma equipe ágil. Elas não apenas ajudam na codificação e na manutenção do código, mas também garantem que o código seja de alta qualidade e facilmente testável. A escolha do IDE e das ferramentas deve considerar as necessidades específicas da equipe, a linguagem de programação utilizada e o ambiente de desenvolvimento desejado. O uso eficaz dessas ferramentas pode acelerar o desenvolvimento, melhorar a qualidade do software e facilitar a colaboração dentro da equipe.


### Resumo do Capítulo: Testes Voltados para a Tecnologia que Suportam a Equipe

Neste capítulo, abordamos a importância e os componentes dos testes voltados para a tecnologia, que formam a base para a qualidade e eficiência em equipes ágeis.

- **Propósito dos Testes Voltados para a Tecnologia:** Esses testes são essenciais para garantir a produção de código de alta qualidade. Eles servem como a fundação para todos os outros tipos de testes, promovendo a robustez do software e a capacidade de teste do sistema.

- **Benefícios:** A aplicação eficaz desses testes permite à equipe ser mais rápida e produtiva. No entanto, a velocidade e a quantidade não devem ser os objetivos finais; a qualidade continua sendo primordial.

- **Contribuição dos Programadores:** Programadores são responsáveis por escrever esses testes, que ajudam a manter a qualidade interna do código e fornecem uma base sólida para os testadores.

- **Desafios e Superação:** Equipes que não implementam práticas ágeis adequadas enfrentam dificuldades. Sistemas legados podem ser um desafio significativo para o desenvolvimento orientado a testes, mas abordagens incrementais podem ajudar a superar esses obstáculos.

- **Implementação e Suporte:** Se a equipe ainda não realiza esses testes, envolva membros da equipe e obtenha suporte da gerência para iniciar a implementação.

- **Sobreposição com Testes Voltados para os Negócios:** Pode haver alguma sobreposição entre testes voltados para a tecnologia e testes voltados para os negócios. No entanto, priorizar testes no nível mais baixo geralmente oferece o melhor retorno sobre o investimento (ROI).

- **Configuração de Processos:** Configure processos contínuos de integração, criação e teste para fornecer feedback rápido e eficiente sobre o código.

- **Ferramentas Necessárias:** Utilize ferramentas para controle de código-fonte, automação de testes, IDEs e gerenciamento de compilação para apoiar e facilitar os testes voltados para a tecnologia.

Esses componentes e práticas são fundamentais para garantir que a equipe ágil possa produzir software de alta qualidade de maneira eficiente e sustentável.