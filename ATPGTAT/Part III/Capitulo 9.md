# Capítulo 9

### Kit de Ferramentas para Testes Voltados para Negócios

O desenvolvimento ágil enfatiza a importância dos testes voltados para negócios para garantir que o software atenda às necessidades do cliente. Ferramentas e estratégias são essenciais para capturar exemplos e escrever testes que apoiem a equipe de desenvolvimento. Vamos explorar algumas dessas ferramentas e como elas podem ser usadas eficazmente.

#### **Estratégia para Seleção de Ferramentas**

1. **Necessidades da Equipe:**
   - **Conjunto de Habilidades:** Escolha ferramentas que se alinhem com as habilidades e conhecimentos da sua equipe. Ferramentas muito complexas ou que exigem habilidades especializadas podem não ser ideais para todos.
   - **Tecnologia do Aplicativo:** A ferramenta deve ser compatível com a tecnologia usada no desenvolvimento do aplicativo.

2. **Prioridades e Restrições:**
   - **Automação:** Avalie a necessidade de automação e como isso se encaixa nas prioridades da equipe.
   - **Tempo e Orçamento:** Escolha ferramentas que se encaixem nas restrições de tempo e orçamento do projeto.

3. **Evitar Modismos:**
   - **Ferramenta "Certa":** Não escolha uma ferramenta apenas porque é a mais recente ou popular. A adequação à sua situação específica é crucial.

#### **Tipos de Ferramentas e Suas Aplicações**

1. **Ferramentas de Captura e Comunicação de Exemplos:**
   - **Quadro Branco e Papel:** Para equipes co-localizadas, essas ferramentas tradicionais são úteis para discutir e capturar exemplos de forma colaborativa.
   - **Ferramentas de Colaboração Online:** Ferramentas como Miro ou Microsoft Whiteboard permitem que equipes distribuídas colaborem em tempo real.

2. **Ferramentas de Especificação e Automação de Testes:**
   - **FitNesse:** Ferramenta mencionada por Lisa, ideal para criar testes automatizados que podem ser facilmente compreendidos e executados. Boa para especificar e verificar funcionalidades complexas.
   - **Cucumber:** Permite escrever testes em linguagem natural que podem ser automatizados. Facilita a comunicação entre desenvolvedores e clientes.
   - **Behave:** Similar ao Cucumber, permite criar testes automatizados baseados em exemplos em linguagem natural.
   - **TestRail:** Para gerenciamento e organização de casos de teste, ajudando a manter os testes alinhados com os requisitos do negócio.

3. **Ferramentas para Gestão de Requisitos e Histórias:**
   - **JIRA:** Utilizado para rastrear histórias, tarefas e bugs. Integrado com ferramentas de automação de testes para vincular requisitos a casos de teste.
   - **Confluence:** Para documentar requisitos, exemplos e discussões relacionadas às histórias de usuário.

#### **Dicas de Implementação**

- **Preparação Antecipada:** Incentive os clientes a preparar exemplos e condições de satisfação antes do início da iteração. Isso ajuda a definir claramente o que precisa ser desenvolvido e testado.
  
- **Iteração e Ajuste:** Experimente diferentes níveis de detalhe nos casos de teste. Comece com testes de alto nível e ajuste conforme necessário. Isso ajuda a evitar a sobrecarga de detalhes e garante que os testes sejam relevantes e úteis.

- **Feedback e Refatoração:** Use o feedback dos programadores para ajustar e melhorar os testes. Às vezes, a abordagem inicial pode não se alinhar perfeitamente com a implementação real, exigindo ajustes.

#### **Conclusão**

A escolha e uso eficaz das ferramentas para testes voltados para negócios são fundamentais para o sucesso do desenvolvimento ágil. As ferramentas devem apoiar a equipe na captura de exemplos, automação de testes e comunicação eficiente. Adaptar as ferramentas às necessidades específicas da equipe e do projeto é crucial para maximizar a eficácia dos testes e garantir que o software atenda às expectativas dos clientes.

### Ferramentas para Obter Exemplos e Requisitos

No desenvolvimento ágil, histórias de usuário são o ponto de partida para conversas detalhadas sobre o comportamento desejado do sistema. Para apoiar essas conversas e criar testes eficazes, é essencial capturar exemplos e requisitos de maneira organizada. Abaixo estão algumas ferramentas e técnicas úteis para esse processo.

#### **1. Listas**

- **Objetivo:** Garantir que todos os aspectos de uma história sejam avaliados e comunicados adequadamente.
- **Uso:** Criação de listas de verificação para condições de satisfação e impactos nos componentes do sistema.
- **Exemplo Prático:** Steve Perkins, mencionado, utilizou uma "lista de verificação da história" para garantir que todos os requisitos e impactos fossem considerados. Isso inclui migração de dados, notificações, e considerações legais.

**Exemplo de Lista de Verificação de História:**
- Condições de satisfação
- Impacto em funções existentes
- Requisitos legais e de comunicação

#### **2. Mapas Mentais**

- **Objetivo:** Organizar ideias e conceitos em torno de um conceito central para explorar todos os aspectos de uma história.
- **Uso:** Usar para brainstorm e para estruturar discussões sobre o comportamento desejado do sistema.
- **Exemplo Prático:** Criar um mapa mental para uma história de exclusão de itens do carrinho de compras para discutir o destino dos itens excluídos e as alterações na interface.

**Exemplo de Mapa Mental:**
- Destino dos itens excluídos
- Alterações na interface do usuário
- Aprovação ou desaparecimento dos itens

#### **3. Planilhas**

- **Objetivo:** Documentar e ilustrar requisitos e cálculos complexos de forma que possa ser transformada em testes automatizados.
- **Uso:** Definir exemplos de funcionalidades e algoritmos, frequentemente usado em domínios como serviços financeiros.
- **Exemplo Prático:** Steve Perkins usa planilhas para ilustrar cálculos e algoritmos, facilitando a transformação desses exemplos em testes.

**Exemplo de Planilha:**
- Cálculos e algoritmos
- Valores de entrada e resultados esperados
- Exemplo: Planilha para cálculo de valores em serviços financeiros

#### **4. Maquetes**

- **Objetivo:** Visualizar e testar como as interfaces e fluxos de trabalho funcionarão antes da codificação.
- **Uso:** Criar protótipos de papel ou capturas de tela para discutir e revisar as alterações na interface do usuário.
- **Exemplo Prático:** Desenhar interfaces no quadro branco ou em papel e digitalizá-las para revisão e discussão, como feito por Lisa.

**Exemplo de Maquete:**
- Interface do usuário desenhada no quadro branco
- Protótipo de papel para novo relatório

#### **5. Fluxogramas**

- **Objetivo:** Capturar fluxos de trabalho e decisões de maneira visual para descrever cenários de uso e requisitos.
- **Uso:** Diagramar processos de decisão e fluxos de trabalho para facilitar a compreensão e o desenvolvimento de histórias.
- **Exemplo Prático:** Criar fluxogramas para processos como frete grátis baseado em valor do pedido, endereço e peso.

**Exemplo de Fluxograma:**
- Processo de decisão para frete grátis
- Condições para elegibilidade
- Ações baseadas em condições

#### **Resumo**

Cada ferramenta tem seu papel na captura e comunicação de requisitos e exemplos para testes voltados para negócios. A escolha da ferramenta deve ser guiada pelas necessidades da equipe e do projeto, e pode incluir combinações de ferramentas para cobrir diferentes aspectos dos requisitos. Ferramentas simples e práticas, como listas, mapas mentais, e maquetes, frequentemente oferecem uma maneira eficaz e ágil de garantir que todos os aspectos das histórias de usuário sejam considerados e testados adequadamente.

Para melhorar a comunicação e colaboração no desenvolvimento ágil, especialmente em equipes distribuídas, várias ferramentas podem ser extremamente úteis. Aqui está uma visão detalhada sobre as ferramentas e abordagens descritas:

### Ferramentas Baseadas em Software

#### **Compartilhamento de Área de Trabalho e Videoconferência**
- **Exemplos**: Windows NetMeeting, VNC, WebEx, Skype.
- **Uso**: Permitem colaboração em tempo real e testes em pares entre membros da equipe localizados em diferentes lugares. Facilitam discussões e demonstrações, mesmo quando as equipes estão distribuídas.

#### **Quadros Brancos Online e Ferramentas Interativas**
- **Exemplos**: Scriblink, Mimeo.
- **Uso**: Facilitam a colaboração visual e discussões durante o desenvolvimento, especialmente quando as equipes não estão fisicamente juntas.

#### **Ferramentas de Colaboração e Documentação**
- **Exemplos**: FitNesse, Fit, ferramentas de fórum online, wikis.
- **Uso**: Permitem que clientes e equipes documentem e revisem requisitos e casos de teste colaborativamente. Facilitam a comunicação contínua e a documentação de decisões.

### Ferramentas para Automatizar Testes com Base em Exemplos

#### **Frameworks de Teste**
- **Exemplos**: FitNesse, Expect.
- **Uso**: Permitem que clientes escrevam testes diretamente usando uma linguagem específica de domínio, facilitando a colaboração entre programadores e clientes.

#### **Testes em Nível de Unidade**
- **Exemplos**: JUnit, NUnit.
- **Uso**: Usadas para testes voltados para negócios e tecnologia. As equipes podem criar estruturas que permitem que testes sejam escritos e executados, além de automatizar o processo de testes.

#### **Desenvolvimento Orientado por Comportamento (BDD)**
- **Exemplos**: easyb, JBehave, NBehave, NSpec, RSpec.
- **Uso**: Usam uma linguagem natural para descrever o comportamento esperado do sistema, facilitando a compreensão dos testes por todas as partes envolvidas, incluindo os clientes.

### Exemplos Práticos de Ferramentas

#### **FitNesse**
- **Uso**: FitNesse é uma ferramenta para criar testes de aceitação automatizados usando uma interface baseada em wiki. Permite que testes sejam escritos em uma linguagem específica de domínio que pode ser entendida por clientes e desenvolvedores.

#### **easyb**
- **Uso**: Uma ferramenta de BDD que usa uma sintaxe natural para descrever cenários de teste, tornando o código mais acessível para os clientes e garantindo que os testes reflitam exatamente o comportamento desejado.

### Benefícios das Ferramentas

1. **Melhoria da Comunicação**: Ferramentas como videoconferência e quadros brancos online ajudam na comunicação eficaz entre equipes distribuídas.
2. **Documentação e Colaboração**: Wikis e fóruns online proporcionam um local centralizado para documentar e discutir requisitos e decisões.
3. **Automatização de Testes**: Frameworks como FitNesse e ferramentas de BDD permitem que clientes e desenvolvedores trabalhem juntos na definição e execução de testes, alinhando os requisitos aos testes automatizados.
4. **Desenvolvimento Orientado por Comportamento**: BDD promove a colaboração ao permitir que os testes sejam escritos em uma linguagem próxima ao inglês, facilitando a comunicação entre clientes e desenvolvedores.

### Considerações Finais

- **Experimente e Avalie**: É importante testar várias ferramentas e abordagens para encontrar as que melhor atendem às necessidades de sua equipe.
- **Adapte às Necessidades da Equipe**: As ferramentas e técnicas devem evoluir com o tempo para se adequarem às mudanças nas necessidades da equipe e do projeto.
- **Foco na Colaboração**: Ferramentas que promovem a comunicação e a colaboração eficaz são essenciais para o sucesso do desenvolvimento ágil, especialmente em equipes distribuídas.

Essas ferramentas e técnicas ajudam a definir e refinar requisitos, automatizar testes e melhorar a colaboração entre todas as partes envolvidas no desenvolvimento de software.

### Ferramentas de Teste Funcional da Camada de API

**Fit e FitNesse**

1. **Fit (Framework for Integrated Tests)**
   - **Descrição**: Uma ferramenta de teste de código aberto projetada para promover a colaboração entre clientes, testadores e desenvolvedores. Permite especificar expectativas usando exemplos que o sistema deve atender.
   - **Funcionalidade**: Permite criar testes funcionais usando tabelas HTML para definir entradas e saídas esperadas. A execução dos testes compara automaticamente os resultados esperados com os reais.
   - **Benefícios**:
     - Facilita a colaboração na definição de requisitos.
     - Testes escritos por clientes em uma forma compreensível.
     - Executa testes com dados reais para verificar a lógica de negócios.

   - **Mais Informações**: [Fit](http://fit.c2.com)

2. **FitNesse**
   - **Descrição**: Baseado no Fit, é um servidor web e uma ferramenta de wiki que permite escrever testes em uma marcação wiki mais acessível.
   - **Funcionalidade**: Suporta a criação de testes usando marcação wiki e planilhas, além de ser capaz de importar e automatizar testes.
   - **Benefícios**:
     - Interface amigável para criação e gerenciamento de testes.
     - Promove a colaboração entre membros da equipe.
     - Testes são codificados por cores para fácil identificação de falhas.

   - **Mais Informações**: [FitNesse](http://www.fitnesse.org)

**Testando Serviços da Web**

1. **CrossCheck**
   - **Descrição**: Ferramenta para testar serviços da Web. Utiliza WSDL para compilar páginas e executar pacotes de testes.
   - **Funcionalidade**: Permite adicionar testes e executá-los, útil para verificar serviços da Web com entradas repetitivas.

2. **Ruby Test::Unit**
   - **Descrição**: Framework de teste de unidade do Ruby, usado para testar serviços da Web com sucesso em alguns projetos.
   - **Funcionalidade**: Permite testar serviços da Web cedo no ciclo de desenvolvimento para feedback rápido aos programadores.

3. **soapUI**
   - **Descrição**: Ferramenta para testes de serviços da Web com funcionalidades avançadas, incluindo testes de desempenho e carga.
   - **Funcionalidade**: Oferece suporte a testes controlados por dados, execução de testes baseados em planilhas e verificação de tempo de resposta.
   - **Benefícios**:
     - Versão gratuita e versão Pro com mais recursos.
     - Extensível com Groovy e integração com ambientes de integração contínua.
     - Verificação de cobertura de código e tempo de resposta.

**Testes de GUI**

**Automação de Testes de GUI**
   - **Importância**: Testes de GUI automatizados são úteis para ajudar no desenvolvimento de novas funcionalidades. Podem ser usados para criar casos de teste antes que o código final esteja pronto, utilizando maquetes HTML ou implementações básicas.
   - **Benefícios**:
     - Ajuda na validação de funcionalidades antes do desenvolvimento completo.
     - Reduz o tempo e esforço necessário para o teste exploratório manual.

**Ferramentas de Gravação/Reprodução**
   - **Descrição**: Ferramentas que gravam ações do usuário (como cliques e digitação) para criar scripts de teste. Embora úteis para começar, podem ser frágeis e difíceis de manter.
   - **Desvantagens**:
     - Scripts podem ser sensíveis a mudanças na interface, como resolução de tela e localização dos elementos.
     - Manutenção pode ser complicada e cara.

   - **Melhoria**: Muitas ferramentas modernas oferecem gravação como um ponto de partida, mas recomenda-se refatorar os scripts em uma linguagem orientada a objetos para melhor manutenção e reutilização.

**Ferramentas e Linguagens de Script**
   - **Descrição**: Ferramentas e frameworks que permitem criar linguagens específicas de domínio (DSL) para testes, tornando-os mais compreensíveis para os especialistas em negócios e mais fáceis de manter.
   - **Benefícios**:
     - Facilitam a criação de testes que são mais alinhados com a terminologia e os requisitos do cliente.
     - Permitem uma colaboração mais eficaz entre desenvolvedores e stakeholders.

**Conclusão**
Escolher a ferramenta certa depende das necessidades da equipe e do projeto. Ferramentas como Fit, FitNesse, e soapUI ajudam a testar a lógica de negócios e serviços da Web, enquanto ferramentas de GUI e técnicas de gravação/reprodução ajudam a automatizar e simplificar o processo de teste da interface do usuário. Testes funcionais bem implementados podem ser uma parte crucial no desenvolvimento ágil, facilitando a colaboração e a comunicação entre todos os membros da equipe.

### Ferramentas de Teste Ágeis de Código Aberto

#### **Watir**
- **Descrição:** Watir (Web Application Testing in Ruby) é uma biblioteca de código aberto para automatizar testes em navegadores da web, inicialmente projetada para Internet Explorer, mas agora também compatível com outros navegadores através de variantes como FireWatir e SafariWatir.
- **Vantagens:**
  - **Simplicidade:** Permite escrever testes de forma legível usando Ruby.
  - **DSL (Domain-Specific Language):** Cria uma linguagem específica de domínio que facilita a escrita de testes por especialistas em negócios.
  - **Mantenibilidade:** Facilita a manutenção e a leitura dos testes através da abstração de operações comuns.
- **Exemplo de Código:**
  ```ruby
  def test_create_new_user
    login 'administrator', 'admin'
    navigate_to_tab 'Manage Users'
    click_button 'Create New User'
    set_text_field 'userFirstNameInput', 'Ruby'
    set_text_field 'userLastNameInput', 'RubyTester'
    click_button 'Save Changes'
    verify_text 'Saved changes'
  end

  def navigate_to_tab(menuItemName)
    @browser.link(:text, menuItemName).click
  end

  def set_text_field(id, value)
    @browser.text_field(:id, id).set value
  end
  ```

#### **Selenium**
- **Descrição:** Selenium é um conjunto de ferramentas de código aberto para testes de aplicativos web. Permite escrever testes em várias linguagens de programação e executá-los em diferentes navegadores.
- **Vantagens:**
  - **Flexibilidade:** Suporte a diversas linguagens de programação e navegadores.
  - **Gravador:** O Selenium IDE oferece uma forma rápida de criar e aprender testes através de um gravador.
  - **Frameworks:** Permite a criação de frameworks de automação personalizados.
- **Considerações:** Pode ser mais complexo de configurar, especialmente ao lidar com múltiplas plataformas e navegadores.

#### **Canoo WebTest**
- **Descrição:** Canoo WebTest é uma ferramenta que usa arquivos XML para especificar testes de aplicativos web. Simula ações de um navegador usando o HtmlUnit.
- **Vantagens:**
  - **Simplicidade:** Especifica testes usando XML, sem necessidade de codificação complexa.
  - **Modularidade:** Permite criar testes de forma modular e fácil de manter.
  - **Integração:** Funciona bem com o Ant, facilitando a integração com processos de build contínuos.
- **Exemplo de Código XML:**
  ```xml
  <setInputField description="set query" name="q" value="Agile Tester"/>
  <clickButton description="submit query" label="Google Search"/>
  <verifyText description="check for result" text="Lisa Crispin"/>
  <verifyText description="check for result" text="Janet Gregory"/>
  ```

### Ferramentas de Automação de Teste "Caseiras"
As ferramentas "caseiras" são criadas pelas equipes para atender necessidades específicas e são baseadas em ferramentas de código aberto. Elas oferecem maior personalização e podem ser ajustadas às necessidades exatas do projeto.

#### **Exemplo de Projeto de Sucesso com Ferramentas Caseiras**
**Contexto:** PAS é um aplicativo de contabilidade para a indústria de petróleo e gás. A equipe usou uma abordagem de automação de teste caseira com Ruby e Watir para criar uma estrutura de teste robusta.

- **Testes de API:** Testes funcionais de desenvolvedor para verificar funções específicas através de APIs.
- **Testes de GUI:** Mais de 500 testes de GUI implementados usando Watij e JUnit.
- **Testes de Integração:** Testes criados pelos usuários em uma estrutura semelhante ao Fit, usando uma linguagem de domínio para definir casos de teste complexos.

**Desafios e Soluções:**
- **Manutenção de Testes:** Problemas com nomes de objetos inconsistentes foram resolvidos ao trabalhar com desenvolvedores para padronizar nomes.
- **Desempenho:** Testes demoravam 12 horas para serem executados devido à complexidade dos testes.
- **Integração:** A equipe integrou usuários e desenvolvedores em reuniões diárias para resolver problemas de teste rapidamente.

### Conclusão
As ferramentas de teste ágeis de código aberto e as soluções caseiras oferecem uma ampla gama de opções para automação de testes. A escolha entre elas depende das necessidades específicas do projeto, da complexidade dos testes e dos recursos disponíveis. Ferramentas como Watir, Selenium e Canoo WebTest fornecem diferentes abordagens e flexibilidade para criar e manter testes de maneira eficaz.

Para maximizar a eficácia de seus testes e garantir que eles estejam alinhados com as necessidades do negócio, você pode adotar uma série de estratégias e padrões de design. Aqui estão algumas das principais práticas recomendadas:

### Estratégias para Escrever Testes

#### 1. **Testes de Build Incrementais**
   - **Comece Simples**: Comece escrevendo testes simples e diretos que cubram os cenários mais óbvios e críticos. Certifique-se de que o teste básico funcione antes de avançar para cenários mais complexos.
   - **Itere e Expanda**: Após validar o teste básico, adicione testes mais detalhados e complexos para cobrir mais regras de negócios e cenários adicionais.

   **História de Lisa**: Lisa descreve como ela começa escrevendo um teste básico com exemplos fornecidos pelo proprietário do produto, ajustando-o conforme o feedback do programador e garantindo que cobre todas as regras de negócios.

#### 2. **Mantenha os Testes Passando**
   - **Priorize a Correção de Testes**: Se um teste falhar, a prioridade deve ser corrigi-lo imediatamente para que a construção permaneça "verde". Não comente testes quebrados e deixe-os para corrigir depois, pois isso cria uma dívida técnica.
   - **Atualize os Testes conforme Mudanças**: Se os requisitos mudarem e um teste falhar como resultado, atualize o teste antes de alterar o código. 

   **História de Lisa**: Lisa destaca como sua equipe aprendeu a importância de manter os testes "verdes" e a necessidade de corrigir testes quebrados rapidamente para evitar problemas de manutenção.

#### 3. **Use Padrões de Design de Teste Apropriados**
   - **Construir/Operar/Verificar (BOF)**: Esse padrão envolve construir dados de entrada, operar o código com esses dados e verificar os resultados. É útil para testes que verificam a funcionalidade de forma direta e eficiente.
   - **Padrões Baseados em Tempo, Atividade e Evento**: Para cenários que envolvem eventos ou processos ao longo do tempo, como a aplicação de juros em um empréstimo, use testes que simulam essas condições e verifiquem o comportamento ao longo do tempo.

   **História de Lisa**: Lisa explica a eficácia do padrão BOF e como ele pode ser usado para testar funcionalidades de maneira eficiente. Ela também discute o uso de padrões baseados em tempo para simular processos de negócios reais.

### Padrões de Design de Teste

#### 1. **Padrão de Construção/Operação/Verificação (BOF)**
   - **Construir**: Configure o ambiente de teste e insira os dados necessários.
   - **Operar**: Execute a funcionalidade que está sendo testada.
   - **Verificar**: Confirme que o resultado é o esperado.

   **Exemplo**: Para um teste de cálculo de taxas em um sistema de faturamento, você configuraria as taxas, inseriria as propriedades da conta, calcularia as taxas e verificaria os valores aplicados.

#### 2. **Padrões Baseados em Tempo, Atividade e Evento**
   - **Baseado em Tempo**: Simula a passagem do tempo e verifica o efeito das ações ao longo de um período.
   - **Baseado em Evento**: Testa o sistema em resposta a eventos específicos, como a realização de pagamentos em um empréstimo.
   - **Baseado em Atividade**: Verifica o comportamento do sistema em atividades contínuas ou complexas.

   **Exemplo**: Em um teste de empréstimo, você pode criar um cenário onde um empréstimo é feito, pagamentos são realizados em diferentes datas, e o saldo do empréstimo e os juros são verificados ao longo do tempo.

### Dicas Adicionais
- **Simples e Claro**: Mantenha os testes o mais simples e claros possível. Testes complicados podem se tornar difíceis de manter e entender.
- **Modularidade**: Escreva testes modulares para facilitar a manutenção e a reutilização. Testes bem projetados podem ser mais facilmente ajustados ou expandidos.
- **Envolva a Equipe**: Trabalhe em colaboração com desenvolvedores e partes interessadas para garantir que os testes cubram todos os requisitos e se mantenham alinhados com as expectativas do negócio.

Aplicar essas estratégias e padrões pode ajudar a garantir que seus testes sejam eficazes, sustentáveis e alinhados com os objetivos de negócios.

Para aprimorar a escrita e a gestão de testes, e garantir que sua equipe esteja equipada para desenvolver um código robusto e testável, considere as seguintes práticas e abordagens:

### 1. **Educação e Colaboração**

- **Estude Padrões de Teste**: Familiarize-se com padrões de teste consagrados como os descritos em *xUnit Test Patterns: Refactoring Test Code* de Gerard Meszaros. Esses padrões ajudam a garantir que os testes sejam claros, fáceis de manter e executados de forma eficiente.

- **Colabore com a Equipe**: Reúna programadores e testadores para discutir abordagens de teste. Decida quais testes podem ser automatizados e como o código deve ser projetado para facilitar esses testes. A lógica de negócios e algoritmos devem ser acessíveis diretamente, sem a necessidade de passar por interfaces complexas ou processos externos.

### 2. **Testes Baseados em Palavras-chave e Dados**

- **Teste Orientado por Dados**: Utilize dados de entrada e resultados esperados para criar testes repetíveis. Isso reduz a manutenção e facilita o compartilhamento com testadores manuais. Ferramentas como Fit e FitNesse são úteis para criar testes baseados em tabelas que definem entradas e saídas esperadas.

- **Teste Orientado por Palavras-chave**: Use palavras-chave predefinidas para definir ações no teste. Isso facilita a criação de uma linguagem de teste de domínio que pode ser compreendida por não-programadores, ajudando a envolver mais partes interessadas na definição dos testes.

   **Exemplo**: Uma planilha com palavras-chave como Signup, Signoff e CCDeposit pode ser usada para definir ações de teste em um formato compreensível, permitindo que testadores não técnicos participem do processo de definição de testes.

### 3. **Design de Código e Testabilidade**

- **Desenvolvimento Orientado a Testes (TDD)**: Escreva testes antes de codificar para garantir que o design do código seja testável. Isso inclui garantir que a arquitetura permita testes diretos na lógica de negócios sem depender da interface do usuário ou da camada de banco de dados.

- **Boas Práticas de Codificação**: Escreva código com boas práticas de HTML e JavaScript, por exemplo, para facilitar a automação de testes de GUI. Validar o HTML e garantir que ele esteja conforme os padrões do setor ajuda a evitar problemas em diferentes navegadores e versões.

   **História de Lisa**: Lisa encontrou problemas ao automatizar testes de GUI devido a HTML e JavaScript não conformes. Com a correção e conformidade com padrões, a automação de testes se tornou muito mais fácil e confiável.

### 4. **Automação de Testes**

- **Automatize Onde for Beneficioso**: Converta o máximo possível dos testes manuais em automatizados. Testes manuais podem ser usados para explorar cenários inesperados, mas a automação é fundamental para uma verificação contínua e eficiente.

- **Abordagem Gradual**: Comece com uma abordagem simples para a automação e desenvolva-a conforme necessário. Isso pode incluir testes de ponta a ponta ou cenários complexos que são difíceis de automatizar totalmente e podem precisar de sessões exploratórias adicionais.

### 5. **Gerenciamento de Testes**

- **Controle de Versão**: Inclua seus testes no controle de código-fonte para manter o rastreamento das versões. Isso garante que você possa acompanhar quais versões dos testes correspondem a quais versões do código.

- **Documentação e Acessibilidade**: Utilize ferramentas como wikis ou ferramentas específicas de gerenciamento de testes para tornar os testes acessíveis a toda a equipe e compreensíveis para os clientes. Ferramentas como FitNesse permitem que requisitos narrativos, exemplos e testes executáveis coexistam em um só lugar.

- **Integração com Gerenciamento de Requisitos**: Algumas equipes utilizam ferramentas de gerenciamento de testes que se integram com gerenciamento de requisitos e rastreamento de defeitos, permitindo uma visão mais coesa do processo de desenvolvimento e teste.

### Considerações Finais

A integração eficaz de testes no desenvolvimento ágil requer uma abordagem colaborativa e iterativa. Trabalhar juntos para entender e implementar padrões de teste, manter o código e os testes alinhados, e garantir uma automação eficaz são passos cruciais para entregar software de alta qualidade. Lembre-se de revisar e ajustar continuamente suas estratégias de teste para se adaptar às necessidades em evolução do projeto e da equipe.

Neste capítulo, discutimos as ferramentas e diretrizes para criar e gerenciar testes voltados para os negócios, fundamentais para o desenvolvimento ágil. Aqui está um resumo dos pontos principais abordados:

1. **Ferramentas para Captura de Requisitos e Exemplos**:
   - **Ferramentas Diversas**: Utilize quadros brancos, listas de verificação, mapas mentais, planilhas, maquetes, diagramas de fluxo e software especializado para capturar requisitos e exemplos de forma eficaz.

2. **Automação de Testes**:
   - **Ferramentas de Automação**: Incluem ferramentas de teste de unidade, desenvolvimento orientado por comportamento (BDD), FitNesse, Ruby com Watir, Selenium e Canoo WebTest.
   - **Automação Caseira**: Desenvolver soluções personalizadas pode ajudar a reduzir os custos totais de propriedade dos testes automatizados.

3. **Desenvolvimento Orientado a Testes**:
   - **Motivação para Código Testável**: O uso de testes voltados para negócios incentiva o desenvolvimento de código que é mais fácil de testar.

4. **Estratégias de Teste**:
   - **Desenvolvimento Incremental**: Crie testes de forma incremental e assegure-se de que todos os testes passem antes de avançar.
   - **Padrões de Design de Teste**: Use padrões apropriados para criar testes eficazes e manuteníveis.

5. **Teste Controlado por Palavras-chave e Dados**:
   - **Abordagem Comum**: Utilize testes orientados por palavras-chave e dados para simplificar a automação e permitir a participação de testadores não técnicos.

6. **Design e Capacidade de Teste**:
   - **Considerações de Design**: Projete o código para ser testável e escolha ferramentas de teste que se integrem bem com o design do código.

7. **Gerenciamento de Testes**:
   - **Organização e Controle de Versão**: Organize os testes de forma eficaz e use controle de versão para gerenciar a evolução dos testes e seu alinhamento com o código.

Este resumo oferece uma visão geral das melhores práticas e ferramentas para criar, automatizar e gerenciar testes voltados para negócios, ajudando a garantir que eles sejam eficazes e sustentáveis no contexto de desenvolvimento ágil.