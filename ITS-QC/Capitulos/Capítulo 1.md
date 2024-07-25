# Capítulo 1

### O que é o teste automatizado de software eficaz (AST)?
**AST:** AST, ou Teste Automatizado de Software (Automated Software Testing), refere-se ao uso de ferramentas e scripts para automatizar o processo de teste de software. Ao invés de executar manualmente os casos de teste, os engenheiros de teste utilizam software que pode realizar esses testes automaticamente, garantindo que o código seja verificado continuamente à medida que é desenvolvido e modificado.

### Componentes do AST:
1. **Ferramentas de Automação**: Software usado para automatizar testes, como Selenium, JUnit, TestNG, entre outros.
2. **Scripts de Teste**: Códigos escritos para definir os testes que serão executados automaticamente.
3. **Framework de Teste**: Estrutura que suporta a execução dos testes, organização dos scripts e geração de relatórios.
4. **Ambiente de Teste**: Configurações necessárias para executar os testes automatizados, como ambientes de staging ou desenvolvimento que simulam o ambiente de produção.

### Benefícios do AST:
- **Eficiência**: Permite a execução rápida e repetitiva de testes.
- **Consistência**: Reduz erros humanos, garantindo que os testes sejam executados da mesma forma cada vez que são realizados.
- **Cobertura de Testes**: Aumenta a cobertura dos testes, permitindo a verificação de mais cenários e casos de uso.
- **Feedback Rápido**: Proporciona feedback imediato sobre o impacto das mudanças no código, facilitando a identificação de defeitos cedo no ciclo de desenvolvimento.

### Desafios do AST:
- **Custo Inicial**: Implementar um sistema de testes automatizados pode exigir um investimento inicial significativo em termos de ferramentas, treinamento e desenvolvimento de scripts.
- **Manutenção**: Os scripts de teste precisam ser mantidos e atualizados à medida que o software evolui.
- **Complexidade**: Criar scripts de teste robustos e eficazes pode ser complexo e demorado.

### Aplicações do AST:
- **Teste de Regressão**: Verificação de que novas alterações no código não introduziram novos bugs em partes já existentes do software.
- **Teste de Integração**: Garantir que diferentes módulos ou serviços de um sistema funcionem corretamente quando integrados.
- **Teste de Desempenho**: Avaliação da performance do software sob diferentes cargas e condições.

Em resumo, AST é uma prática essencial na engenharia de qualidade de software moderna, ajudando a garantir que o software entregue seja de alta qualidade, eficiente e confiável.

Referências:
- [Implementing Automated Software Testing](https://www.oreilly.com/library/view/implementing-automated-software/9780321699670/)【8†source】.
- [Barnes & Noble: Implementing Automated Software Testing](https://www.barnesandnoble.com/w/implementing-automated-software-testing-elfriede-dustin/1100294084)【9†source】.

**ROI:** ROI, ou Retorno sobre o Investimento, é uma métrica financeira usada para avaliar a eficiência ou rentabilidade de um investimento. No contexto da Automação de Testes de Software (AST), calcular o ROI ajuda a justificar os custos iniciais de implementação ao demonstrar os benefícios financeiros ao longo do tempo.

### Fórmula do ROI:
A fórmula básica para calcular o ROI é:

\[ \text{ROI} = \frac{\text{Ganho do Investimento} - \text{Custo do Investimento}}{\text{Custo do Investimento}} \times 100 \% \]

### Componentes do ROI no AST:
1. **Custo do Investimento**:
   - **Ferramentas de Automação**: Licenças de software ou custos de desenvolvimento de ferramentas internas.
   - **Desenvolvimento de Scripts**: Tempo e esforço necessários para criar e manter scripts de teste.
   - **Treinamento**: Capacitação da equipe para usar as ferramentas e escrever scripts eficazes.
   - **Infraestrutura**: Hardware e ambiente necessários para executar os testes automatizados.

2. **Ganho do Investimento**:
   - **Redução de Custos de Teste Manual**: Economia gerada pela diminuição de esforço humano em testes repetitivos.
   - **Melhoria da Qualidade do Software**: Redução de defeitos em produção, o que pode levar a menor custo de suporte e manutenção.
   - **Aceleração do Ciclo de Desenvolvimento**: Mais rapidez na liberação de software devido à eficiência dos testes automatizados.
   - **Aumento da Cobertura de Testes**: Maior capacidade de detectar defeitos cedo, antes de alcançar o ambiente de produção.

### Exemplo Prático:
Suponha que uma empresa invista R$100.000 em ferramentas e infraestrutura de automação, e R$50.000 em desenvolvimento de scripts e treinamento. O total do investimento é de R$150.000. Após a implementação, a empresa economiza R$120.000 anualmente em custos de testes manuais e evita R$60.000 em custos de manutenção devido à melhoria da qualidade do software.

- **Custo do Investimento**: R$150.000
- **Ganho do Investimento Anual**: R$120.000 (economia em testes manuais) + R$60.000 (economia em manutenção) = R$180.000

Calculando o ROI:

\[ \text{ROI} = \frac{R\$180.000 - R\$150.000}{R\$150.000} \times 100 \% = 20 \% \]

Neste exemplo, o ROI anual seria de 20%, indicando que o investimento em automação está gerando um retorno positivo.

### Importância do ROI no AST:
- **Justificação Financeira**: Ajuda a justificar os investimentos iniciais em automação para os stakeholders.
- **Medição de Sucesso**: Avalia a eficácia das estratégias de automação e direciona melhorias contínuas.
- **Decisão de Investimento**: Orienta as decisões sobre futuras implementações e expansões da automação de testes.

### Referências:
- [CIO: Calculating ROI for Automated Testing](https://www.cio.com/article/288979/calculating-roi-for-automated-testing.html)
- [TechBeacon: How to Calculate ROI for Test Automation](https://techbeacon.com/app-dev-testing/how-calculate-roi-test-automation)
- [IBM: Justifying Automated Testing with ROI](https://www.ibm.com/docs/en/rtw/9.1.1?topic=planning-justifying-automated-testing-roi)

### Definição de Teste Automatizado de Software

Teste Automatizado de Software (Automated Software Testing - AST) é o processo de utilizar ferramentas de software para executar testes de um aplicativo, comparando os resultados reais com os resultados esperados automaticamente. Isso é feito através da execução de scripts de teste que foram previamente desenvolvidos e configurados para validar diferentes aspectos do software.

### Características Principais do AST:
1. **Automação dos Casos de Teste**: Ferramentas de automação são usadas para executar scripts de teste sem intervenção humana, repetidamente e com consistência.
2. **Comparação Automática de Resultados**: Os resultados dos testes são comparados automaticamente com os resultados esperados, facilitando a detecção de discrepâncias e defeitos.
3. **Reusabilidade de Scripts**: Scripts de teste automatizados podem ser reutilizados em múltiplas execuções, economizando tempo e esforço em testes repetitivos.
4. **Cobertura Ampla de Testes**: A automação permite testar mais cenários em menos tempo, aumentando a cobertura e a qualidade dos testes.

### Vantagens do AST:
- **Eficiência**: Executa testes mais rapidamente do que testes manuais.
- **Consistência e Precisão**: Elimina a variabilidade humana, garantindo que os testes sejam executados da mesma forma todas as vezes.
- **Economia de Tempo e Recursos**: Reduz a necessidade de testes manuais repetitivos, permitindo que a equipe se concentre em testes mais complexos e análise de resultados.
- **Feedback Rápido**: Proporciona resultados imediatos, permitindo a identificação e correção rápida de defeitos.

### Exemplos de Ferramentas de Automação:
- **Selenium**: Uma ferramenta amplamente usada para automação de navegadores web.
- **JUnit/TestNG**: Frameworks populares para automação de testes em Java.
- **Cucumber**: Ferramenta que suporta o desenvolvimento orientado por comportamento (BDD).
- **Appium**: Usado para automação de testes de aplicativos móveis.

### Referências:
- **IBM**: [Automated Software Testing](https://www.ibm.com/docs/en/rtw/9.1.1?topic=planning-automated-testing)
- **TechTarget**: [What is Automated Testing?](https://searchsoftwarequality.techtarget.com/definition/automated-testing)
- **SmartBear**: [What is Automated Testing?](https://smartbear.com/learn/automated-testing/what-is-automated-testing/)

**ATRT:** ATRT pode ser uma abreviação para várias coisas, mas em um contexto relacionado a testes de software, pode significar **Automated Test and Re-Test** (Teste Automatizado e Re-Teste). Vou abordar esse conceito no contexto de testes automatizados de software.

### Definição de Automated Test and Re-Test (ATRT):

**Automated Test and Re-Test (ATRT)** refere-se ao processo de utilização de ferramentas de automação para realizar testes repetidamente em um sistema ou aplicação de software. Isso envolve a execução automática de scripts de teste após cada alteração ou atualização no software para garantir que novas mudanças não introduzam novos defeitos (regressões) e que as funcionalidades existentes continuem a funcionar corretamente.

### Características Principais do ATRT:

1. **Execução Repetitiva**:
   - Realização de testes de maneira contínua e repetitiva sempre que houver uma modificação no código.
   - Ideal para ambientes de Integração Contínua e Entrega Contínua (CI/CD).

2. **Detecção de Regressões**:
   - Identificação de defeitos introduzidos por mudanças recentes no código.
   - Garante que as funcionalidades existentes continuem a operar conforme esperado.

3. **Consistência**:
   - Execução de testes de forma consistente, eliminando a variabilidade dos testes manuais.
   - A mesma suíte de testes pode ser executada em diferentes momentos e ambientes com resultados consistentes.

4. **Economia de Tempo**:
   - Reduz o tempo necessário para realizar testes manuais repetitivos.
   - Libera os testadores para se concentrar em testes exploratórios e em áreas mais complexas do sistema.

### Benefícios do ATRT:

- **Aumento da Confiança na Qualidade do Software**: A execução constante de testes automatizados garante que o software está sempre em conformidade com os requisitos e especificações.
- **Redução de Custos**: Menos necessidade de intervenção manual e diminuição de erros humanos reduzem os custos de desenvolvimento e manutenção.
- **Aceleração do Ciclo de Desenvolvimento**: Testes automatizados permitem ciclos de desenvolvimento mais rápidos, suportando práticas ágeis e de DevOps.
- **Feedback Rápido**: Fornece feedback imediato sobre o impacto das mudanças no código, facilitando correções rápidas.

### Exemplos de Ferramentas de ATRT:

- **Selenium**: Para automação de testes de aplicações web.
- **JUnit/TestNG**: Para automação de testes unitários em Java.
- **Appium**: Para automação de testes de aplicativos móveis.
- **Jenkins**: Para integração contínua e execução de testes automatizados em pipelines de CI/CD.

### Referências:

- **[SmartBear: Automated Testing](https://smartbear.com/learn/automated-testing/what-is-automated-testing/)**
- **[Atlassian: Automated Testing in CI/CD](https://www.atlassian.com/continuous-delivery/software-testing/automated-testing)**

Se ATRT tiver um significado diferente em seu contexto específico, por favor, forneça mais detalhes para que eu possa ajustar a resposta conforme necessário.

**STR:** No contexto de testes automatizados de software (AST), **STL** refere-se ao **Software Testing Life Cycle** (Ciclo de Vida de Teste de Software). 

### Ciclo de Vida de Teste de Software (STL)
O STL é uma sequência de diferentes atividades realizadas durante o processo de teste de software. Inclui todas as fases que um projeto de teste deve seguir para garantir que o software atenda aos requisitos de qualidade e funcione conforme esperado. As etapas típicas do STL são:

1. **Planejamento de Teste**:
   - Definir o escopo e os objetivos do teste.
   - Identificar recursos necessários (ferramentas, pessoal, etc.).
   - Criar o plano de testes.

2. **Análise de Teste**:
   - Revisar os requisitos do software.
   - Identificar as condições de teste.
   - Avaliar a viabilidade dos testes.

3. **Projeto de Teste**:
   - Criar casos de teste detalhados.
   - Desenvolver scripts de teste (no caso de testes automatizados).
   - Configurar o ambiente de teste.

4. **Implementação de Teste**:
   - Executar os casos de teste.
   - Registrar os resultados dos testes.
   - Reportar defeitos encontrados.

5. **Execução de Teste**:
   - Executar casos de teste planejados.
   - Monitorar a execução dos testes.
   - Comparar os resultados esperados com os reais.

6. **Avaliação de Teste**:
   - Revisar e avaliar os resultados dos testes.
   - Garantir que todos os requisitos foram testados.
   - Tomar decisões sobre a liberação do software.

7. **Encerramento de Teste**:
   - Finalizar todas as atividades de teste.
   - Arquivar a documentação de teste.
   - Analisar as lições aprendidas e melhorar os processos de teste futuros.

### Objetivo do STL
O objetivo do STL é estruturar e organizar o processo de teste para que seja sistemático, eficiente e eficaz. Isso ajuda a identificar e corrigir defeitos no software antes de sua liberação, garantindo a qualidade do produto final.

### Importância no Contexto do AST
No contexto do AST, o STL é crucial porque a automação deve ser integrada em cada fase do ciclo de vida de teste para maximizar a eficiência e os benefícios. A automação pode agilizar tarefas repetitivas e demoradas, melhorar a cobertura de teste e permitir testes contínuos, mas precisa ser bem planejada e executada dentro do framework do STL para ser eficaz.

### Capítulo 1: O que é o Teste Automatizado de Software Eficaz (AST)?

#### Definição e Abrangência do AST
O teste automatizado de software (AST) é um termo abrangente que pode ter diferentes significados para os profissionais da área de desenvolvimento e teste de software. Para alguns, AST pode referir-se a desenvolvimento orientado a testes e/ou testes unitários. Para outros, pode significar o uso de ferramentas de captura/gravação/reprodução para automatizar testes de software. Pode também incluir o desenvolvimento de scripts de teste personalizados em linguagens como Perl, Python ou Ruby. Além disso, AST pode englobar testes de desempenho/estresse, testes funcionais e testes de segurança.

Neste livro, AST é definido como a soma de todas essas abordagens, cobrindo um espectro amplo de atividades e ferramentas utilizadas para automatizar o processo de teste de software.

#### Realidades dos Testes Automatizados de Software
Antes de aprofundar nos detalhes, é essencial definir AST de maneira clara e unificada para que o termo tenha um significado consistente para todos os leitores. O livro se propõe a definir AST com base na experiência e prática dos autores, abordando seu verdadeiro significado.

#### Elementos de um Esforço AST Bem-sucedido
Este capítulo também discute os componentes de um esforço bem-sucedido de AST, fornecendo receitas e estratégias para simplificar a automação dos testes. Além disso, explora a aplicação de AST durante todo o ciclo de vida do teste de software, destacando como a automação pode ser integrada de maneira eficaz desde o início até o final do desenvolvimento do software.

#### 1.1 Definição de Teste Automatizado de Software

A definição de teste automatizado de software (AST) usada ao longo deste livro abrange todas as fases de teste, incluindo compatibilidade entre plataformas, e é independente de processo. Qualquer teste que atualmente faça parte de um programa de teste manual — funcional, desempenho, simultaneidade, estresse, e outros — pode ser automatizado. A questão frequentemente levantada é: "Qual é a diferença entre o teste manual de software e o AST?" A resposta é que AST:

- **Aprimora os esforços de teste manual**, focando na automação de testes que são difíceis ou impossíveis de realizar manualmente.
- **É desenvolvimento de software**, envolvendo programação e engenharia.
- **Não substitui a necessidade de habilidades analíticas dos testadores manuais**, seu conhecimento estratégico e entendimento das técnicas de teste. A experiência dos testadores manuais serve como modelo para o AST.
- **Não pode ser claramente separado dos testes manuais**; ambos estão interligados e se complementam.

Embora seja possível desenvolver software que converta qualquer teste manual existente em um teste automatizado, a experiência mostra que a maioria dos testes manuais precisa ser adaptada para a automação. As técnicas, práticas e conhecimentos de teste manual estão interligados com o AST e são discutidos ao longo do livro, pois suportam o AST. A questão de se a automação proporcionará o retorno sobre o investimento (ROI) necessário requer avaliação cuidadosa. Embora todos os testes possam ser automatizados, nem todos os testes valem a pena automatizar. Vários critérios precisam ser considerados para tomar essa decisão, que são discutidos mais detalhadamente no Capítulo 6.

#### Definição de Alto Nível de AST

A definição de alto nível de AST é:
> **A aplicação e implementação de tecnologia de software ao longo de todo o ciclo de vida de teste de software (STL) com o objetivo de melhorar a eficiência e eficácia da STL.**

AST refere-se aos esforços de automação em toda a STL, com foco na automação dos esforços de integração e teste do sistema. O objetivo geral do AST é projetar, desenvolver e fornecer um recurso automatizado de teste e reteste que aumente a eficiência dos testes. Se implementado com sucesso, pode resultar em uma redução substancial no custo, tempo e recursos associados aos métodos tradicionais de teste e avaliação para sistemas com uso intensivo de software.

### 1.2 Receitas de Teste de Software Automatizado

O teste automatizado de software (AST), quando implementado de forma eficaz, vai além da simples captura/reprodução de GUI, não se limita a uma fase específica de teste, não é específico para qualquer produto de fornecedor e pode ser adaptado para a arquitetura ou linguagem específica usada pelo aplicativo em teste (AUT).

A implementação do AST, conforme descrito neste livro, é independente de processo, tecnologia e ambiente. Seguir as sugestões de implementação permitirá que você implemente o AST independentemente do modelo de desenvolvimento de software usado, seja ele em cascata, orientado a testes, Scrum ou qualquer outro. AST pode ser aplicado a aplicativos web, soluções de arquitetura orientada a serviços (SOA), e em sistemas operacionais como Linux, Mac ou Windows.

### Características e Suporte do AST

O AST deve oferecer suporte a aplicativos que:
- Executam em vários computadores.
- São desenvolvidos em diferentes linguagens de programação.
- Executam em diferentes tipos de sistemas operacionais ou plataformas.
- Possuem ou não interfaces gráficas do usuário (GUIs).
- Executam qualquer tipo de protocolo de rede, como TCP/IP, DDS, entre outros.

### Receitas para Estrutura de Teste Automatizado

A estrutura de teste automatizado deve:
- Suportar a integração de várias ferramentas de teste comercial, sejam elas de código aberto, desenvolvidas internamente ou de diferentes fornecedores.
- Permitir testes sem a necessidade de instalar o framework no mesmo computador que o SUT (Sistema em Teste).
- Suportar tanto novas aplicações em desenvolvimento quanto aplicações existentes.
- Abranger todo o ciclo de vida de teste, embora o AST não precise ser aplicado a todo o ciclo para ser útil.
- Facilitar testes distribuídos em múltiplos computadores e diferentes ambientes de engenharia de sistemas.
- Permitir a reutilização do framework AST e componentes entre programas.

A implementação do AST requer um mini ciclo de vida de desenvolvimento, incluindo requisitos de teste, design e construção da estrutura de automação, implementação/verificação de testes automatizados e execução. Quando feito corretamente, o AST produz estruturas e componentes reutilizáveis e expansíveis. As melhores práticas de desenvolvimento de software são aplicáveis e devem ser seguidas.

### Adaptações Necessárias

Apesar de programas e AUTs terem necessidades semelhantes de automação de teste, cada um pode exigir adaptações específicas. Uma estrutura de teste automatizado implementada efetivamente deve ser capaz de acomodar esses requisitos exclusivos.

### Exemplo de Estrutura de Automação

A Figura 1-1 no livro mostra um exemplo de uma estrutura de teste e reteste automatizado (ATRT) compatível entre plataformas, executando testes em Linux e Windows. Neste exemplo, ferramentas como Berinjela Testplant e VNCRobot foram integradas na estrutura de automação de teste de software/mecanismo STA (STAF/STAB). A estrutura STAF/STAX é uma solução de código aberto, multiplataforma e multilíngue, desenhada em torno da ideia de componentes reutilizáveis, conhecidos como serviços.

### Considerações Específicas para AST

A implementação do AST deve considerar vários critérios, incluindo:

- **Fase do Ciclo de Vida de Testes da AUT**: Quanto mais cedo o AST for envolvido, melhor será a reutilização de artefatos de teste nas fases subsequentes.
- **Cronograma e Prazos da AUT**: Mais tempo disponível permite uma maior cobertura e detalhamento dos testes automatizados.
- **Tecnologia AUT**: AST deve ser adaptado aos requisitos tecnológicos específicos do AUT.
- **Complexidade da AUT**: A complexidade do AUT influencia a elaboração do esforço AST necessário.
- **Missão, Criticidade e Risco da AUT**: A criticidade da missão e os riscos associados afetam os esforços AST envolvidos.

### Conclusão

Reconhecendo a singularidade de cada programa, uma implementação eficaz do framework AST pode ser adaptada para várias necessidades e ambientes. O objetivo é aplicar AST de forma abrangente, mas adaptável, em diferentes programas, sem a necessidade de desenvolver uma nova estrutura AST do zero para cada um, utilizando processos leves que podem ser facilmente ajustados a qualquer organização ou programa.

### 1.3 Avanços nas Tecnologias AST

Nem todos os testes manuais precisam ser automatizados para que um esforço de teste automatizado de software (AST) seja considerado bem-sucedido. A decisão de automatizar deve ser baseada no cálculo do retorno sobre o investimento (ROI), e alguns testes podem não ser adequados para automação devido ao custo ou complexidade.

Embora o AST melhore os esforços manuais de teste, ele ainda requer desenvolvimento de software para testar o software desenvolvido. Isso ocorre porque não existe alternativa melhor atualmente, apesar dos avanços em áreas como a computação autônoma da IBM, que visam criar componentes auto-testáveis. No entanto, essas tecnologias ainda estão em estágio inicial e são aplicadas por poucas empresas.

Para reduzir o envolvimento humano e automatizar o máximo possível, é essencial simplificar o esforço de desenvolvimento de software necessário para AST. Utilizar automação para implementar a automação de testes é uma abordagem eficaz para minimizar a interação humana e os erros associados.

Por exemplo, em vez de desenvolver uma estrutura de teste do zero, empresas podem aproveitar componentes de código aberto ou free/shareware que já fornecem funcionalidades necessárias como testes em lote, testes distribuídos ou notificações por email. Isso economiza tempo e recursos. Ferramentas de código aberto, disponíveis sob licenças verificadas, devem ser consideradas para o design e desenvolvimento de estruturas de automação de teste.

### Ferramentas e Soluções para Automatização

Ferramentas que ajudam a automatizar todas as fases do ciclo de vida de desenvolvimento, desde os requisitos até o projeto, implementação, teste e rastreamento de defeitos, são valiosas. Por exemplo, soluções como o Automated Test Generator (ATG) e o Test Conductor (TC) da Telelogic/IBM geram casos de teste e código de teste necessários para testar modelos na plataforma de desenvolvimento e no destino. Alternativamente, ferramentas de código aberto como o AndroMDA permitem a criação e uso de metamodelos e transformações de modelo a modelo para geração de código.

### Automação de Procedimentos de Teste

A geração automatizada de dados de teste é essencial para lidar com grandes conjuntos de combinações e permutações de dados. Ferramentas como FireEye (ACTS) do NIST ajudam a gerar dados de teste automatizados, reduzindo o tédio e os erros do processo manual. 

Outras formas de automação incluem o uso de bibliotecas Java para testar interfaces de usuário, linguagens de design de interface (IDL) para geração de código, e componentes auto-testáveis. Exemplos adicionais incluem a geração automatizada de código de caso de teste, que envolve:

- **Código de Teste de Interface de Software**: Interfaces de middleware como CORBA, DDS, etc., podem ser usadas para gerar código de interface de software.
- **Código do Procedimento do Caso de Teste**: Cada etapa do procedimento de caso de teste tem código gerado para executar seu comportamento, usando formatos padronizados como XML e ferramentas como ANTLR e StringTemplate.

### Aplicativos Compostos e Reutilização de Componentes

Aplicativos compostos permitem a agilidade necessária para se adaptar rapidamente às mudanças nas condições de negócios. Utilizando uma "biblioteca" de componentes de software, é possível montar componentes existentes em novas configurações, resultando em novas interfaces de usuário e transações. Isso também se aplica aos componentes de automação, permitindo a reutilização e simplificação dos esforços de teste automatizado.

### Conclusão

A implementação eficaz do AST deve considerar a simplificação e automação de todos os aspectos do desenvolvimento de software necessário para os testes. Utilizar ferramentas de código aberto, bibliotecas de componentes reutilizáveis e tecnologias avançadas pode melhorar a eficiência e eficácia dos testes automatizados, resultando em economia de tempo e custos, e aumentando a qualidade geral do software testado.

### 1.4 Automatizando Vários Tipos de Teste de Software

Vários tipos de testes de software são realizados em qualquer sistema, desde testes funcionais/verificação de requisitos até testes de segurança ou desempenho. Esses tipos de teste basicamente se enquadram em uma ou duas categorias principais: teste de caixa preta e teste de caixa branca, com teste de caixa cinza no meio.

#### Teste de Caixa Branca

O teste de caixa branca envolve o teste interno do software do sistema, como testes de unidade e cobertura de código. Este tipo de teste requer algum conhecimento do código e do design do sistema. A intenção é verificar se o sistema satisfaz com êxito seus requisitos funcionais em geral.

#### Teste de Caixa Preta

O teste de caixa preta exercita a maioria das partes do sistema ao invocar várias chamadas do sistema através da interação da interface do usuário. Nesse tipo de teste, o funcionamento interno do sistema não é conhecido nem precisa ser. O testador de caixa preta valida o comportamento correto exibindo apenas a saída da interface do usuário. Por exemplo, se um usuário adiciona um registro ao banco de dados do aplicativo inserindo dados na interface do usuário, várias camadas do sistema são executadas, e o teste de caixa preta valida o comportamento correto pela saída na interface do usuário.

#### Teste de Caixa Cinza

Os testes de caixa cinza combinam elementos dos testes de caixa preta e branca, exigindo conhecimento dos componentes subjacentes do sistema. Este tipo de teste é útil quando os testes de caixa preta não conseguem relatar erros devido a defeitos no mecanismo de relatório de erros do software. Por exemplo, se o aplicativo falha ao inserir um registro no banco de dados, mas não relata um erro à interface do usuário, um teste de caixa cinza pode identificar e diagnosticar a falha internamente.

### Vantagens do Teste de Caixa Cinza

1. **Maior Capacidade de Realizar Testes Investigativos**: Quando um teste falha, o conhecimento arquitetônico do sistema pode ajudar o testador a realizar testes focados e determinar o "ponto de interrupção" do aplicativo. Por exemplo, se houver um problema de conexão com o banco de dados, não será necessário tentar a operação com diferentes valores de dados. O foco será resolver os problemas de conexão.

2. **Relatórios de Defeitos Aprimorados**: Testes investigativos mais eficazes levam a relatórios de defeitos mais detalhados, beneficiando a equipe de desenvolvimento. Por exemplo, se uma caixa de diálogo falhar ao ser exibida, a investigação pode revelar um problema ao recuperar informações do banco de dados.

3. **Maior Precisão de Testes**: O teste de caixa cinza monitora o comportamento interno dos componentes para determinar o sucesso ou a falha do teste. Identifica diferentes tipos de problemas, como falhas de componentes, resultados incorretos, "falsos positivos" (onde o sistema não relata um erro) e "falsos negativos" (onde o sistema relata um erro incorreto).

### Interação Humana em Testes

Embora a automação seja eficaz, alguns testes, como os de usabilidade, ainda exigem interação humana. Testes de usabilidade, por exemplo, avaliam como um sistema atende ao propósito pretendido e são melhor realizados com um painel de usuários que interagem com a página da web para testar sua facilidade de uso.

### Tipos de Teste Adequados para Automação

Vários tipos de testes se prestam bem à automação devido à sua complexidade e necessidade de repetibilidade:

- **Teste Unitário**: Validação de unidades individuais no código-fonte.
- **Teste de Regressão**: Verificação de funcionalidades previamente funcionais.
- **Testes Funcionais**: Verificação de requisitos funcionais.
- **Testes de Segurança**: Verificação de requisitos de segurança.
- **Testes de Desempenho**: Verificação de requisitos de desempenho.
- **Teste de Estresse**: Verificação do comportamento sob estresse.
- **Testes de Simultaneidade**: Verificação de manipulação de threads e usuários simultâneos.
- **Verificação de Cobertura de Código**: Medição da porcentagem de código exercida por um conjunto de testes.

### Conclusão

Automatizar testes de software é uma prática essencial que melhora a eficiência e eficácia do processo de teste. Embora alguns tipos de testes ainda exijam interação humana, muitos outros são altamente adequados para automação, resultando em testes mais precisos, detalhados e menos propensos a erros.

### 1.5 Fornecendo suporte à produção baseado em AST

1. **Redução do Tempo e Custo de Teste**:
   - **Automação de Testes de Aceitação**: O uso de AST para automatizar testes de aceitação repetitivos pode reduzir significativamente o tempo e custo associados à fase de produção, proporcionando um alto retorno sobre o investimento.

2. **Suporte à Solução de Problemas de Produção**:
   - **Repetibilidade e Reproduzibilidade**: AST permite a repetição precisa de casos de teste, o que facilita a reprodução e análise de problemas encontrados em produção.
   - **Gravação e Compressão**: Ferramentas como Berinjela e Camtasia ajudam a documentar problemas e criar vídeos para comunicação com desenvolvedores, agilizando a resolução de problemas.

3. **Identificação de Componentes Afetados**:
   - **Análise Específica**: AST pode ajudar a identificar áreas específicas do programa afetadas por correções, permitindo testes mais focados e reduzindo a necessidade de executar um conjunto completo de testes de regressão.
   - **Eficiência no Teste de Regressão**: Focalizando os testes apenas nas áreas afetadas, o tempo de teste é otimizado e o ciclo de correção/teste é acelerado.

4. **Verificação da Precisão e Qualidade da Correção**:
   - **Confirmação de Correções**: AST pode validar se as correções realmente resolvem os problemas de produção e se não introduzem novos problemas ou afetam negativamente funcionalidades existentes.
   - **Testes de Regressão Automatizados**: Garantem que a correção não introduza novas falhas ou problemas.

5. **Suporte à Triagem de Defeitos e Análise de Causa Raiz**:
   - **Avaliação de Procedimentos de Teste**: Inclui a análise de procedimentos de teste para garantir que a cobertura de teste seja consistente e eficaz.
   - **Automatização de Testes de Problemas Específicos**: Automatizar testes para problemas identificados e adicionar novos testes à regressão conforme necessário.
   - **Análise de Causa Raiz**: Examina por que um defeito não foi identificado anteriormente, ajudando a melhorar os testes futuros.

6. **Prevenção e Medidas de Detecção de Defeitos**:
   - **Medidas Preventivas**: AST pode ser usado para implementar medidas que ajudem a evitar a introdução de defeitos na produção.
   - **Avaliação do Índice de Qualidade**: Permite avaliar a qualidade do programa e garantir a implementação de práticas que melhorem a qualidade do software.

Esses pontos destacam como o AST pode agregar valor não apenas durante o desenvolvimento de software, mas também na fase de produção, melhorando a eficiência dos testes, a resolução de problemas e a qualidade do software.

### 1.6 Automatizando avaliações de padrões

1. **Economia de Tempo e Custo**:
   - **Redução de Custos**: A automação na avaliação de padrões pode reduzir significativamente os custos associados aos esforços de teste e avaliação de padrões, economizando bilhões de dólares gastos atualmente em processos manuais e demorados.

2. **Aderência a Padrões**:
   - **Conformidade Eficiente**: Automatizar a verificação da aderência a padrões, como os estabelecidos pelo IEEE, OMG, e ISO, garante uma avaliação sistemática e repetível, aumentando a conformidade com normas e regulamentos.

3. **Solução Sistemática e Repetível**:
   - **Automação e Simplicidade**: A automação oferece uma solução sistemática que acelera e simplifica o processo de avaliação, facilitando a verificação de padrões e destacando rapidamente quaisquer riscos associados à não conformidade.

4. **Estrutura de Automação Extensível**:
   - **Expansão e Flexibilidade**: A proposta de usar uma estrutura extensível, como a baseada no Eclipse, permite a expansão e adaptação da automação para diferentes domínios e requisitos de padrões, desde sistemas SOA até dispositivos portáteis.

5. **Integração de Ferramentas**:
   - **Ferramentas e Frameworks**: A integração com ferramentas existentes, como as do Eclipse TPTP, proporciona uma base confiável e segura para avaliação automatizada de padrões, aproveitando contribuições significativas de organizações como a IBM.

6. **Benefícios Diretos e Indiretos**:
   - **Processos de Revisão**: A automação pode acelerar a revisão de código, reduzindo a necessidade de inspeções manuais e permitindo que equipes de desenvolvimento avaliem seu próprio código de forma mais eficiente.

7. **Exemplos de Aplicações**:
   - **Cobertura Ampla**: A automação é aplicável a uma ampla gama de padrões e sistemas, desde desenvolvimento de software até requisitos específicos de segurança e conformidade, como ANSI e outros padrões de codificação.

8. **Impacto no Mercado**:
   - **Mercado Extenso**: Com bilhões de dólares em jogo, tanto no setor governamental quanto comercial, a automação de avaliações de padrões oferece uma oportunidade significativa para economizar dinheiro e melhorar a eficiência.

Esses pontos destacam como a automação na avaliação de padrões pode transformar processos tediosos e propensos a erros em atividades sistemáticas e eficientes, proporcionando economia de custos e melhor conformidade com normas e regulamentos.