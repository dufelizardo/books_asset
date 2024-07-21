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

### 1.2 Receitas de Teste de Software Automatizado

#### Introdução:
- A seção "Receitas de Teste de Software Automatizado" fornece abordagens práticas e detalhadas para implementar testes automatizados.
- Cada "receita" é uma solução passo a passo para desafios específicos de teste, adaptada para diferentes situações e necessidades.

#### Componentes das Receitas:
- **Objetivo da Receita**: Uma breve descrição do que a receita visa alcançar, como testar uma funcionalidade específica ou validar um comportamento do sistema.
- **Ferramentas Necessárias**: Lista das ferramentas de automação de testes que serão usadas, como Selenium, JUnit, TestNG, etc.
- **Pré-requisitos**: Condições ou configurações necessárias antes de começar a implementação da receita, como ambiente de teste configurado, dados de teste disponíveis, etc.
- **Passos Detalhados**: Instruções passo a passo sobre como implementar e executar o teste automatizado. Isso inclui a escrita de scripts de teste, configuração de ambientes e execução de testes.
- **Validação dos Resultados**: Como verificar se os resultados do teste são os esperados, incluindo métodos para comparar saídas reais e esperadas.
- **Considerações Adicionais**: Dicas e melhores práticas para otimizar a implementação da receita, evitar armadilhas comuns e adaptar a receita a diferentes contextos.

#### Exemplos de Receitas:
1. **Teste de Login**:
   - **Objetivo**: Automatizar o teste da funcionalidade de login de um aplicativo.
   - **Ferramentas**: Selenium WebDriver para interações com o navegador.
   - **Passos**:
     1. Abrir o navegador e navegar até a página de login.
     2. Inserir credenciais válidas e clicar no botão de login.
     3. Verificar se o login foi bem-sucedido verificando a presença de um elemento específico na página de destino.
   - **Validação**: Confirmar que o usuário foi redirecionado corretamente e que os elementos esperados estão presentes.

2. **Teste de Carrinho de Compras**:
   - **Objetivo**: Verificar a funcionalidade de adicionar e remover itens do carrinho de compras em um site de e-commerce.
   - **Ferramentas**: Selenium WebDriver, JUnit.
   - **Passos**:
     1. Navegar até a página de um produto.
     2. Adicionar o produto ao carrinho.
     3. Navegar para o carrinho de compras e verificar se o produto foi adicionado.
     4. Remover o produto do carrinho e confirmar a remoção.
   - **Validação**: Verificar que o carrinho exibe corretamente os itens adicionados e removidos.

### Importância das Receitas:
- **Praticidade**: Fornecem soluções práticas e reutilizáveis para problemas comuns de teste.
- **Eficiência**: Ajudam a acelerar a implementação de testes automatizados ao fornecer exemplos prontos.
- **Adaptabilidade**: Podem ser ajustadas para diferentes contextos e necessidades específicas do projeto.

### Referências:
- **O'Reilly: Implementing Automated Software Testing**: [O'Reilly Library](https://www.oreilly.com/library/view/implementing-automated-software/9780321699670/)
- **Barnes & Noble: Implementing Automated Software Testing**: [Barnes & Noble](https://www.barnesandnoble.com/w/implementing-automated-software-testing-elfriede-dustin/1100294084)

Essa seção do livro é essencial para quem deseja aplicar testes automatizados de maneira prática e eficaz, oferecendo uma abordagem estruturada para resolver desafios comuns no desenvolvimento de software.

### Seção 1.4: "Automatizando Vários Tipos de Teste de Software"

Na seção 1.4 do livro "Implementing Automated Software Testing: How to Save Time and Lower Costs While Raising Quality", os autores discutem como automatizar diferentes tipos de testes de software para melhorar a eficiência e a cobertura dos testes. A seguir, apresento um resumo dos principais pontos abordados nessa seção.

#### Tipos de Testes de Software Automatizados:

1. **Teste Unitário**:
   - **Descrição**: Testes que validam a menor unidade de código, como funções ou métodos individuais.
   - **Ferramentas Comuns**: JUnit (Java), NUnit (.NET), PyTest (Python).
   - **Benefícios**: Detecta defeitos precocemente, facilita a refatoração e garante que cada componente funcione isoladamente.

2. **Teste de Integração**:
   - **Descrição**: Verifica a interação entre diferentes módulos ou componentes do sistema.
   - **Ferramentas Comuns**: TestNG, Apache Camel para integração de serviços.
   - **Benefícios**: Garante que os componentes do sistema funcionem juntos corretamente.

3. **Teste de Sistema**:
   - **Descrição**: Testa o sistema completo para garantir que todos os componentes funcionem conforme esperado em conjunto.
   - **Ferramentas Comuns**: Selenium WebDriver, Appium (para aplicativos móveis).
   - **Benefícios**: Valida o comportamento end-to-end do sistema, detectando problemas de integração e funcionamento global.

4. **Teste de Aceitação**:
   - **Descrição**: Confirma que o sistema atende aos requisitos de negócios e é aceitável para o usuário final.
   - **Ferramentas Comuns**: Cucumber (BDD), FitNesse.
   - **Benefícios**: Garante que o software entregue satisfaça os critérios de aceitação definidos pelo cliente.

5. **Teste de Regressão**:
   - **Descrição**: Verifica se novas alterações no código não introduzem defeitos em funcionalidades já existentes.
   - **Ferramentas Comuns**: Jenkins (para CI/CD), Selenium, JUnit.
   - **Benefícios**: Assegura que o software continue a funcionar corretamente após modificações ou atualizações.

6. **Teste de Desempenho**:
   - **Descrição**: Avalia a capacidade do sistema de funcionar sob cargas específicas e identificar possíveis gargalos de desempenho.
   - **Ferramentas Comuns**: JMeter, LoadRunner.
   - **Benefícios**: Garante que o sistema possa lidar com a carga esperada de usuários e dados, identificando problemas de desempenho antes que afetem os usuários finais.

7. **Teste de Segurança**:
   - **Descrição**: Avalia a segurança do software, identificando vulnerabilidades e riscos.
   - **Ferramentas Comuns**: OWASP ZAP, Burp Suite.
   - **Benefícios**: Assegura que o software está protegido contra ataques e violações de segurança.

### Estratégias para Automação de Testes:

- **Seleção de Ferramentas Adequadas**: Escolher as ferramentas de automação que melhor se adequam ao tipo de teste e ao ambiente de desenvolvimento.
- **Desenvolvimento de Scripts de Teste Eficazes**: Escrever scripts de teste robustos e reutilizáveis, que possam ser mantidos facilmente.
- **Integração Contínua**: Configurar pipelines de CI/CD para executar testes automatizados continuamente, fornecendo feedback rápido sobre a qualidade do software.
- **Priorização de Testes**: Focar na automação dos testes mais críticos e de maior impacto, para maximizar os benefícios da automação.

### Conclusão:
Automatizar vários tipos de testes de software é essencial para garantir a qualidade, eficiência e confiabilidade do software. A aplicação de técnicas e ferramentas adequadas para cada tipo de teste permite detectar e corrigir defeitos mais rapidamente, reduzindo o tempo e os custos de desenvolvimento.

### Referências:
- [O'Reilly: Implementing Automated Software Testing](https://www.oreilly.com/library/view/implementing-automated-software/9780321699670/)
- [Barnes & Noble: Implementing Automated Software Testing](https://www.barnesandnoble.com/w/implementing-automated-software-testing-elfriede-dustin/1100294084)

### 1.5 Fornecendo suporte à produção baseado em AST

Aqui estão alguns pontos-chave geralmente abordados nessa seção:

1. **Objetivo do Suporte à Produção:**
   - O objetivo é garantir que o software que já está em produção continue a funcionar corretamente e atender aos requisitos dos usuários, mesmo após atualizações e modificações.

2. **Automação de Testes em Produção:**
   - Utilizar testes automatizados para monitorar e validar a funcionalidade do software em um ambiente de produção. Isso pode incluir testes de regressão para garantir que novas alterações não introduzam problemas.

3. **Benefícios:**
   - **Detecção Precoce de Problemas:** Testes automatizados podem ajudar a identificar problemas rapidamente após uma nova versão ser implantada, permitindo uma resposta ágil.
   - **Eficiência:** Automatizar testes de suporte à produção pode reduzir a necessidade de testes manuais extensivos, economizando tempo e recursos.

4. **Estratégias de Implementação:**
   - **Testes de Smoke e Sanity:** Realizar testes básicos para verificar se a aplicação está funcionando conforme esperado após mudanças.
   - **Testes de Monitoramento:** Implementar testes que verifiquem o desempenho e a estabilidade do sistema em tempo real.

5. **Desafios:**
   - **Ambiente de Produção:** Testar em um ambiente de produção pode ser arriscado, e é importante garantir que os testes não interfiram nas operações normais.
   - **Manutenção dos Testes:** Manter e atualizar os testes automatizados para que continuem relevantes e eficazes conforme o software evolui.

6. **Ferramentas e Tecnologias:**
   - A seção também pode discutir diferentes ferramentas e tecnologias que podem ser usadas para automatizar o suporte à produção, ajudando a integrar os testes no fluxo de trabalho de desenvolvimento e implantação.

### **1.6 Automatizando Avaliações de Padrões**

**1. Objetivo:**
   - O objetivo é usar testes automatizados para avaliar se o software está aderindo aos padrões e melhores práticas de desenvolvimento estabelecidos. Isso ajuda a garantir consistência e qualidade no código.

**2. Tipos de Padrões:**
   - **Padrões de Codificação:** Regras e diretrizes sobre como o código deve ser escrito, como estilo de código, nomenclatura e estrutura.
   - **Padrões Arquiteturais:** Diretrizes sobre a arquitetura e o design do software, como padrões de design e melhores práticas para a estruturação do código.
   - **Padrões de Segurança:** Regras para garantir que o software esteja protegido contra vulnerabilidades e ataques.

**3. Ferramentas de Automação:**
   - **Linters:** Ferramentas que verificam o código em busca de erros de sintaxe e conformidade com padrões de codificação.
   - **Analisadores de Código Estático:** Ferramentas que analisam o código sem executá-lo para identificar problemas de qualidade e conformidade com padrões.
   - **Ferramentas de Avaliação de Segurança:** Ferramentas que verificam o código em busca de vulnerabilidades e problemas de segurança.

**4. Benefícios da Automação:**
   - **Consistência:** Garantia de que todos os aspectos do código estejam em conformidade com os padrões definidos.
   - **Eficiência:** Redução do tempo necessário para revisar e corrigir manualmente o código.
   - **Detecção Precoce:** Identificação de problemas antes que eles se tornem grandes questões, economizando tempo e recursos.

**5. Estratégias de Implementação:**
   - **Integração no Processo de CI/CD:** Incorporar avaliações automatizadas de padrões no pipeline de integração contínua e entrega contínua para garantir que o código esteja sempre em conformidade.
   - **Definição de Padrões:** Estabelecer e documentar claramente os padrões a serem seguidos e garantir que todos os desenvolvedores estejam cientes deles.
   - **Customização:** Personalizar ferramentas e regras de acordo com as necessidades específicas do projeto e da organização.

**6. Desafios:**
   - **Falsos Positivos:** Algumas ferramentas podem gerar alertas falsos ou desnecessários, o que pode resultar em sobrecarga para os desenvolvedores.
   - **Atualização dos Padrões:** Manter os padrões e ferramentas atualizados para refletir as melhores práticas mais recentes e mudanças no projeto.

A automação das avaliações de padrões é uma abordagem eficaz para garantir que o software atenda a requisitos de qualidade e mantenha um padrão consistente ao longo do desenvolvimento. 


