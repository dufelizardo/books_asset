# Capítulo 9

### Teste de Acessibilidade na Web

#### Introdução à Acessibilidade na Web

A acessibilidade na web é crucial para garantir que todos os usuários, incluindo aqueles com deficiências permanentes, temporárias ou situacionais, possam acessar e usar os serviços da web. A web se tornou um aspecto essencial da vida moderna, oferecendo conveniência e conectividade. Garantir a acessibilidade melhora a experiência de todos os usuários, independentemente de suas habilidades.

**W3C WAI e Padrões de Acessibilidade:**
- O World Wide Web Consortium (W3C), liderado por Tim Berners-Lee, estabelece padrões para a web através da Iniciativa de Acessibilidade da Web (WAI).
- A WAI define diretrizes globais para acessibilidade, conhecidas como Diretrizes de Acessibilidade para Conteúdo da Web (WCAG).

**Benefícios da Acessibilidade:**
- **Para Usuários:** Facilita a navegação e a interação com o site, especialmente para pessoas com deficiências visuais, auditivas, motoras ou cognitivas.
- **Para Empresas:** Aumenta o alcance de mercado, uma vez que a comunidade com deficiência representa uma parte significativa da população mundial e possui um poder de compra considerável.
- **Legal:** Atender aos requisitos de acessibilidade é muitas vezes uma exigência legal, como evidenciado pela Convenção das Nações Unidas sobre os Direitos das Pessoas com Deficiência (CDPD da ONU).

#### Estratégia de Teste de Acessibilidade Shift-Left

**Princípio de "Shift-Left":**
- Integrar testes de acessibilidade desde as fases iniciais do desenvolvimento, movendo-os "para a esquerda" no ciclo de vida do desenvolvimento de software.
- Esta abordagem permite identificar e corrigir problemas de acessibilidade mais cedo, evitando retrabalho e garantindo conformidade desde o início.

**Fases da Estratégia de Teste de Acessibilidade Shift-Left:**

1. **Planejamento:**
   - **Definir KPIs de Acessibilidade:** Colaborar com todas as partes interessadas para definir os KPIs de acessibilidade.
   - **Configurar Ambiente de Teste:** Estabelecer um ambiente de teste que simule as condições de uso reais o mais próximo possível.
   - **Incluir Casos de Teste de Acessibilidade:** Incorporar critérios de acessibilidade nos critérios de aceitação de cada história de usuário.

2. **Desenvolvimento:**
   - **Validar KPIs:** Verificar se os KPIs de acessibilidade são atendidos durante o desenvolvimento.
   - **Utilizar Ferramentas de Acessibilidade:** Empregar ferramentas automatizadas e manuais para testar a acessibilidade conforme o código é desenvolvido.

3. **Integração Contínua (CI):**
   - **Executar Testes Automatizados:** Integrar testes de acessibilidade automatizados no pipeline de CI para garantir feedback contínuo.
   - **Monitorar Conformidade:** Utilizar ferramentas de auditoria contínua para monitorar a conformidade com as diretrizes de acessibilidade.

4. **Testes de Histórias de Usuário:**
   - **Verificar Critérios de Aceitação:** Certificar-se de que os critérios de aceitação de acessibilidade sejam atendidos antes de marcar uma história de usuário como concluída.
   - **Executar Testes Exploratórios:** Realizar testes exploratórios para identificar qualquer problema de acessibilidade não coberto pelos testes automatizados.

5. **Teste de Lançamento:**
   - **Conduzir Testes de Acessibilidade Finais:** Realizar testes de acessibilidade de ponta a ponta antes do lançamento, incluindo testes de estresse e imersão.
   - **Depuração e Correções:** Identificar e corrigir quaisquer problemas de acessibilidade encontrados durante os testes finais.

#### Ferramentas de Teste de Acessibilidade

**Ferramentas Automatizadas:**
- **Lighthouse:** Ferramenta integrada ao Google Chrome que audita a acessibilidade entre outras dimensões.
- **axe DevTools:** Extensão para navegadores que ajuda a identificar problemas de acessibilidade.

**Ferramentas Manuais:**
- **Leitores de Tela:** Ferramentas como NVDA, JAWS e VoiceOver simulam a experiência de usuários com deficiência visual.
- **Testes de Navegação com Teclado:** Garantem que todas as funcionalidades sejam acessíveis via teclado.

#### Personas de Acessibilidade

**Definição de Personas:**
- Criar personas representativas de diferentes tipos de deficiências (visuais, auditivas, motoras, cognitivas) ajuda a entender as necessidades específicas de acessibilidade de cada grupo.

#### Diretrizes de Acessibilidade

**WCAG (Diretrizes de Acessibilidade para Conteúdo da Web):**
- **Princípios:** As diretrizes WCAG são baseadas em quatro princípios: Perceptível, Operável, Compreensível e Robusto (POUR).
- **Níveis de Conformidade:** WCAG define três níveis de conformidade: A, AA e AAA, onde AAA é o nível mais alto de conformidade.

### Conclusão

Adotar uma abordagem de teste de acessibilidade shift-left e utilizar uma combinação de ferramentas automatizadas e manuais é crucial para garantir que todos os usuários possam acessar e usar o conteúdo da web. Integrar a acessibilidade no início do ciclo de desenvolvimento e monitorar continuamente a conformidade com as diretrizes de acessibilidade não só melhora a experiência do usuário, mas também ajuda a evitar problemas legais e a aumentar o alcance do mercado.

### Personas de Usuário de Acessibilidade

Para criar experiências web inclusivas, é essencial entender as necessidades específicas de diferentes personas de usuários com desafios de acessibilidade. Abaixo estão algumas personas representativas e suas necessidades:

1. **Matt - Profissional de Negócios com Mobilidade Temporariamente Reduzida**
   - **Cenário:** Matt quebrou recentemente o braço e tem dificuldade para operar o mouse.
   - **Necessidades:** 
     - Acesso total ao site apenas com o teclado.
     - Navegação por meio de atalhos de teclado.

2. **Helen - Professora Aposentada com Baixa Sensibilidade às Cores**
   - **Cenário:** Helen, de 80 anos, tem dificuldade para diferenciar cores.
   - **Necessidades:** 
     - Alto contraste de cores entre o texto e o fundo.
     - Elementos de interface claramente distinguíveis.

3. **Abbie - Adolescente com Deficiências Cognitivas**
   - **Cenário:** Abbie leva mais tempo para processar informações novas.
   - **Necessidades:** 
     - Layouts simples e limpos com navegação consistente.
     - Títulos claros e estruturas de navegação previsíveis.

4. **Fred - Usuário em Situação Específica**
   - **Cenário:** Fred precisa encontrar rapidamente informações enquanto dirige.
   - **Necessidades:** 
     - Layout claro e fácil de entender.
     - Informações apresentadas de maneira concisa e acessível.

5. **Connie - Gerente de Loja com Deficiência Visual**
   - **Cenário:** Connie é cega e precisa usar a web para seu trabalho.
   - **Necessidades:** 
     - Suporte para leitores de tela.
     - Recursos de conversão de texto em voz e reconhecimento de voz.

6. **Laxmi - Usuária com Restrições Temporárias**
   - **Cenário:** Laxmi carrega seu bebê a maior parte do dia e tem as mãos ocupadas.
   - **Necessidades:** 
     - Recursos de fala para texto.
     - Controle de voz para navegação.

7. **Maya - Profissional de Software com Destreza Reduzida**
   - **Cenário:** Maya tem dificuldade para utilizar pequenos controles na tela.
   - **Necessidades:** 
     - Textos e botões maiores.
     - Controles grandes e de fácil acesso.

8. **Philip - Entusiasta de Culinária com Deficiência Auditiva**
   - **Cenário:** Philip é surdo e gosta de assistir a vídeos de receitas.
   - **Necessidades:** 
     - Legendas em vídeos.
     - Transcrições de áudio.

9. **Xiao - Dono de Loja com Baixa Proficiência em Inglês**
   - **Cenário:** Xiao está aprendendo inglês e tem dificuldade com linguagem complexa.
   - **Necessidades:** 
     - Instruções simples e diretas.
     - Evitar jargões e frases complexas.

### Ecossistema de Acessibilidade e Diretrizes

#### Ecossistema de Acessibilidade

1. **Tecnologias Assistivas:**
   - **Leitores de Tela:** Softwares que leem o conteúdo da tela em voz alta, como JAWS, NVDA, VoiceOver.
   - **Dispositivos de Entrada Alternativos:** Como teclados especiais, dispositivos de entrada por voz, dispositivos apontadores.

2. **Ferramentas de Acessibilidade:**
   - **Lighthouse:** Ferramenta do Google para auditar a acessibilidade.
   - **axe DevTools:** Extensão para navegadores que ajuda a identificar problemas de acessibilidade.

3. **Padrões e Diretrizes:**
   - **WCAG (Diretrizes de Acessibilidade para Conteúdo da Web):** Definidas pelo W3C WAI, essas diretrizes fornecem um conjunto de padrões para tornar o conteúdo web mais acessível.

#### Diretrizes de Acessibilidade da Web

1. **Princípios WCAG (POUR):**
   - **Perceptível:** Informação e componentes da interface devem ser apresentados de maneira que possam ser percebidos pelos usuários.
   - **Operável:** Componentes da interface e navegação devem ser operáveis.
   - **Compreensível:** Informação e operação da interface devem ser compreensíveis.
   - **Robusto:** Conteúdo deve ser robusto o suficiente para ser interpretado por uma ampla variedade de agentes de usuário, incluindo tecnologias assistivas.

2. **Níveis de Conformidade:**
   - **Nível A:** Requisitos básicos de acessibilidade.
   - **Nível AA:** Requisitos de acessibilidade mais amplos.
   - **Nível AAA:** O nível mais alto de conformidade, com requisitos mais rigorosos.

### Conclusão

Entender e aplicar princípios de acessibilidade desde as fases iniciais do desenvolvimento web é essencial para criar experiências inclusivas e cumprir requisitos legais. Utilizar personas de usuários de acessibilidade ajuda a garantir que as necessidades específicas sejam atendidas, enquanto o uso de ferramentas e diretrizes apropriadas facilita a implementação de um design acessível.

### Ecossistema de Acessibilidade

Para criar recursos web acessíveis, é crucial compreender o ecossistema de acessibilidade, que envolve várias ferramentas e tecnologias que trabalham em conjunto para oferecer uma experiência web inclusiva para usuários com deficiências temporárias e permanentes. A seguir, exploramos os principais componentes desse ecossistema:

#### 1. Ferramentas e Práticas de Desenvolvimento Web
Ferramentas de desenvolvimento web, como HTML e CSS, devem possuir recursos que permitam a criação de conteúdos acessíveis. Por exemplo:
- **HTML:** Deve incluir atributos como `alt` para imagens, `aria-label` e `aria-describedby` para melhorar a interação com leitores de tela.
- **CSS:** Deve garantir contrastes de cor adequados e evitar layouts que dificultem a navegação por teclado.

#### 2. Agentes de Usuário
Agentes de usuário são ferramentas que renderizam o conteúdo da web, como navegadores e reprodutores de mídia. Esses agentes devem:
- **Entender e suportar:** Funcionalidades de acessibilidade incorporadas nos conteúdos web.
- **Integrar-se:** Com tecnologias assistivas, como leitores de tela, para garantir que o conteúdo seja acessível a todos os usuários.

#### 3. Tecnologias Assistivas
Tecnologias assistivas são dispositivos e softwares que ajudam usuários com deficiências a interagir com o conteúdo da web. Exemplos incluem:
- **Leitores de Tela:** Softwares como JAWS, NVDA e VoiceOver que convertem texto em fala.
- **Teclados Alternativos:** Dispositivos que permitem a entrada de dados por meio de métodos alternativos ao teclado padrão.
- **Comutadores:** Dispositivos que permitem aos usuários controlar o computador usando uma ou mais entradas (botões).

### Padrões de Acessibilidade do W3C WAI

Para garantir que todos os componentes do ecossistema de acessibilidade tenham recursos padronizados, o W3C WAI (Iniciativa de Acessibilidade da Web do Consórcio World Wide Web) estabeleceu vários padrões internacionais:

1. **Diretrizes de Acessibilidade da Ferramenta de Autoria (ATAG):**
   - Define padrões para ferramentas de criação de conteúdo web, como editores de HTML.
   - **Objetivo:** Assegurar que as ferramentas de criação de conteúdo suportem a criação de conteúdos acessíveis e sejam elas próprias acessíveis.

2. **Diretrizes de Acessibilidade de Conteúdo da Web (WCAG):**
   - Define padrões para conteúdo da web, como texto, imagens, cores e mídia.
   - **Versões:** As WCAG 2.0 e 2.1 são amplamente adotadas e recomendadas.
   - **Níveis de Conformidade:** A (básico), AA (intermediário) e AAA (avançado).
   - **Objetivo:** Tornar o conteúdo web perceptível, operável, compreensível e robusto para todos os usuários.

3. **Diretrizes de Acessibilidade do Agente do Usuário (UAAG):**
   - Define padrões para navegadores da web e reprodutores de mídia.
   - **Objetivo:** Assegurar que os agentes de usuário ofereçam suporte adequado para tecnologias assistivas e funcionalidades de acessibilidade.

### Diretrizes de Acessibilidade de Conteúdo da Web (WCAG 2.0)

As WCAG 2.0 são divididas em quatro princípios principais conhecidos como POUR:
- **Perceptível:** Assegura que as informações e componentes da interface do usuário possam ser percebidos pelos usuários.
- **Operável:** Garante que os componentes da interface e a navegação sejam utilizáveis.
- **Compreensível:** Assegura que a informação e a operação da interface do usuário sejam compreensíveis.
- **Robusto:** Assegura que o conteúdo seja robusto o suficiente para ser interpretado por uma ampla variedade de agentes de usuário, incluindo tecnologias assistivas.

### Importância e Benefícios

Criar uma web acessível não é apenas uma responsabilidade ética e legal, mas também traz benefícios significativos:
- **Inclusão:** Permite que todas as pessoas, independentemente de suas habilidades, acessem e interajam com a web.
- **Melhoria de UX:** Muitos recursos de acessibilidade melhoram a usabilidade geral para todos os usuários.
- **Conformidade Legal:** Evita ações judiciais e cumpre os regulamentos e políticas de acessibilidade vigentes em muitos países.
- **Benefícios Comerciais:** Alcança um público mais amplo, incluindo a terceira maior economia do mundo em termos de poder de compra – a comunidade de pessoas com deficiência.

### Conclusão

Compreender o ecossistema de acessibilidade e aplicar os padrões estabelecidos pelo W3C WAI é fundamental para desenvolver sites inclusivos e acessíveis. Isso garante que todos os usuários, independentemente de suas habilidades, possam acessar, compreender e interagir com a web de maneira eficaz. As diretrizes e ferramentas disponíveis facilitam a criação de experiências web mais equitativas e inclusivas.

### Exemplo: Leitores de Tela

Para entender a importância das diretrizes WCAG 2.0, precisamos explorar como as tecnologias assistivas, como os leitores de tela, funcionam. Vamos considerar o exemplo dos leitores de tela, que são utilizados por pessoas com deficiência visual. Esta é uma tecnologia assistiva comum cujo suporte é essencial para a acessibilidade da web.

#### Funcionamento dos Leitores de Tela

Leitores de tela são softwares que convertem texto e outros elementos visuais da tela em áudio, permitindo que os usuários naveguem e interajam com os sites usando teclados e comandos de voz. Aqui está uma visão geral de como eles funcionam:

1. **Leitura de Conteúdo**: Os leitores de tela leem em voz alta o conteúdo da página, incluindo textos, links, botões e outras informações.

2. **Navegação por Teclado**: Os usuários interagem com o site utilizando atalhos de teclado, como Tab, Shift + Tab, Enter, etc., para navegar e selecionar elementos na página.

3. **Árvore de Acessibilidade**: O leitor de tela utiliza a árvore de acessibilidade da página, uma estrutura semelhante ao DOM (Document Object Model), que contém elementos da página com atributos específicos, como funções e IDs, organizados em uma sequência lógica. 

#### Exemplo de Árvore de Acessibilidade

Considere um site de reservas com os campos de entrada de texto "De" e "Para" e um botão "Pesquisar" na página inicial. A árvore de acessibilidade para este site pode ser estruturada da seguinte forma:

- **Campo de entrada "De"**: Primeiro elemento na sequência, permitindo que o usuário insira o local de partida.
- **Campo de entrada "Para"**: Segundo elemento, permitindo que o usuário insira o destino.
- **Botão "Pesquisar"**: Terceiro elemento, permitindo que o usuário inicie a pesquisa de tickets.

Esta ordem garante um fluxo de navegação lógico e intuitivo para o usuário.

#### Experiência com Leitores de Tela

Para se familiarizar com os recursos de acessibilidade, é útil experimentar o uso de um leitor de tela. O Google Chrome fornece um leitor de tela baseado em navegador como extensão. 

**Passos para testar um leitor de tela:**

1. **Instalação da Extensão**: Instale a extensão de leitor de tela no Google Chrome.
2. **Ativação**: Ative a extensão e navegue até um site.
3. **Navegação**: Utilize o teclado para navegar pelo site, ouvindo o conteúdo lido em voz alta.
4. **Interação**: Interaja com diferentes elementos, como links, botões e campos de formulário, utilizando atalhos de teclado.

Existem também sites de demonstração, como um site de reservas intencionalmente desfocado para simular a experiência de um usuário com deficiência visual. Esses sites permitem que você faça reservas utilizando um leitor de tela e seu teclado, proporcionando uma compreensão prática de como essas tecnologias funcionam.

#### Benefícios da Acessibilidade com Leitores de Tela

1. **Inclusão**: Leitores de tela garantem que pessoas com deficiência visual possam acessar e interagir com conteúdo web, promovendo a inclusão digital.
2. **Usabilidade**: Melhora a usabilidade para todos os usuários, criando uma experiência de navegação mais intuitiva e organizada.
3. **Conformidade**: Aderência às diretrizes WCAG 2.0 e outros padrões de acessibilidade, evitando problemas legais e melhorando a reputação da empresa.

#### Conclusão

Entender como os leitores de tela funcionam e como os usuários interagem com eles é fundamental para desenvolver sites acessíveis. Ao seguir as diretrizes WCAG 2.0 e estruturar corretamente a árvore de acessibilidade, garantimos que todos os usuários, independentemente de suas habilidades, possam acessar, navegar e interagir com a web de maneira eficaz. A experimentação prática com leitores de tela pode ajudar os desenvolvedores a criar interfaces mais inclusivas e intuitivas.

### WCAG 2.0: Princípios Orientadores e Níveis de Conformidade

As Diretrizes de Acessibilidade para Conteúdo da Web (WCAG) 2.0 são organizadas em torno de quatro princípios orientadores essenciais para tornar o conteúdo da web acessível a todos os usuários. Esses princípios são perceptível, operável, compreensível e robusto. Cada princípio possui diretrizes que estabelecem critérios de sucesso para diferentes níveis de conformidade. Vamos explorar esses princípios e níveis em detalhes:

#### Princípios Orientadores

1. **Perceptível**:
   - **Definição**: O conteúdo deve ser apresentado de maneira que os usuários possam perceber, ou seja, a informação e os componentes da interface do usuário devem ser apresentados de formas que possam ser percebidas pelos sentidos do usuário.
   - **Exemplos**:
     - **Texto Alternativo**: Fornecer textos alternativos para imagens.
     - **Legendas**: Disponibilizar legendas para conteúdo de áudio e vídeo.

2. **Operável**:
   - **Definição**: Os componentes da interface do usuário e a navegação devem ser operáveis, ou seja, os usuários devem ser capazes de operar a interface.
   - **Exemplos**:
     - **Navegação por Teclado**: Todos os elementos interativos devem ser acessíveis via teclado.
     - **Tempo Suficiente**: Os usuários devem ter tempo suficiente para ler e usar o conteúdo.

3. **Compreensível**:
   - **Definição**: A informação e a operação da interface do usuário devem ser compreensíveis, ou seja, os usuários devem ser capazes de entender a informação e o funcionamento da interface.
   - **Exemplos**:
     - **Legibilidade**: O texto deve ser legível e compreensível.
     - **Previsibilidade**: As páginas web devem aparecer e operar de maneira previsível.

4. **Robusto**:
   - **Definição**: O conteúdo deve ser robusto o suficiente para ser interpretado de maneira confiável por uma ampla variedade de agentes de usuário, incluindo tecnologias assistivas.
   - **Exemplos**:
     - **Compatibilidade**: O conteúdo deve ser compatível com tecnologias assistivas atuais e futuras.

#### Níveis de Conformidade

As WCAG 2.0 definem três níveis de conformidade: A, AA e AAA. Esses níveis indicam a medida em que o conteúdo atende aos critérios de sucesso definidos para cada uma das diretrizes.

1. **Nível A**:
   - **Descrição**: Este é o nível mínimo de conformidade. Fornece o suporte essencial sem o qual o site fica inacessível.
   - **Exemplos**:
     - **Alternativas Textuais**: Todo conteúdo não textual deve ter uma alternativa textual.
     - **Navegação por Teclado**: Todas as funcionalidades devem ser acessíveis através do teclado.

2. **Nível AA**:
   - **Descrição**: Este nível inclui todos os requisitos do Nível A, além de requisitos adicionais mais rigorosos. Muitas políticas legais recomendam que os sites atinjam esse nível de conformidade.
   - **Exemplos**:
     - **Contraste de Cores**: As taxas de contraste de cores devem ser restritas para garantir a legibilidade.
     - **Texto Redimensionável**: O texto deve ser redimensionável sem perda de conteúdo ou funcionalidade.

3. **Nível AAA**:
   - **Descrição**: Este nível inclui todos os requisitos dos dois níveis anteriores e exige requisitos adicionais aprimorados. Atingir esse nível mostra um compromisso profundo com a acessibilidade.
   - **Exemplos**:
     - **Linguagem de Sinais**: Prover interpretações em linguagem de sinais para conteúdo de vídeo.
     - **Elementos de Navegação Adicional**: Prover mais modos de navegação para facilitar a localização de conteúdo.

#### Determinação do Nível de Conformidade

As organizações devem determinar o nível de conformidade necessário com base nos requisitos legais e nos objetivos de acessibilidade de seus públicos-alvo. A conformidade com o Nível A garante a acessibilidade básica, enquanto a conformidade com o Nível AA ou AAA oferece uma experiência de usuário mais abrangente e inclusiva. Optar por implementar um nível mais alto de conformidade pode ajudar a atender melhor às necessidades de usuários adicionais, demonstrando um compromisso com a acessibilidade e a inclusão.

### Conclusão

Compreender os princípios orientadores e níveis de conformidade das WCAG 2.0 é fundamental para desenvolver conteúdo da web acessível. Ao seguir esses princípios e buscar níveis mais altos de conformidade, as organizações podem criar experiências web inclusivas que atendam às necessidades de todos os usuários, incluindo aqueles com deficiências temporárias ou permanentes. Isso não apenas promove a inclusão digital, mas também pode trazer benefícios legais, comerciais e reputacionais significativos.

### Padrões de Conformidade de Nível A: WCAG 2.0

Os requisitos do Nível A das Diretrizes de Acessibilidade para Conteúdo da Web (WCAG) 2.0 representam o nível mínimo de conformidade necessário para garantir a acessibilidade básica de um site. Vamos explorar esses requisitos organizados pelos quatro princípios orientadores: Perceptível, Operável, Compreensível e Robusto.

#### 1. Perceptível

**Objetivo**: Tornar o conteúdo disponível de forma que todas as personas de usuário possam perceber.

**Requisitos**:
- **Texto Alternativo**: Todo conteúdo não textual (imagens, gráficos, vídeos) deve ter uma alternativa textual que descreva o conteúdo para usuários com deficiência visual.
  - *Exemplo*: Uma imagem de um gráfico deve ter um texto alternativo que descreva o gráfico.
- **Transcrições e Legendas**: O conteúdo de áudio ou vídeo deve ter transcrições de texto e legendas sincronizadas para usuários surdos ou com deficiência auditiva.
  - *Exemplo*: Um vídeo tutorial deve ter legendas.
- **Controle de Áudio**: Qualquer áudio que comece automaticamente deve ter controles para pausar, reproduzir e ajustar o volume.
  - *Exemplo*: Um anúncio em áudio que inicia automaticamente deve ter um botão de pausa.
- **Hierarquia da Página**: A estrutura da página deve ter uma hierarquia clara com títulos e subtítulos bem definidos para ajudar na navegação por leitores de tela.
  - *Exemplo*: Uso apropriado de `<h1>` para título principal, `<h2>` para subtítulos, etc.
- **Instruções Não Sensoriais**: As instruções não devem depender apenas de características sensoriais (como cor, forma ou tamanho).
  - *Exemplo*: Em vez de dizer "clique no botão verde", diga "clique no botão 'Enviar'".
- **Uso de Cor**: A cor não deve ser o único meio de transmitir informações ou distinguir elementos.
  - *Exemplo*: Links em um formulário devem ser sublinhados além de coloridos para indicar que são clicáveis.
- **Contraste de Cores**: Deve haver contraste suficiente entre o plano de fundo e o primeiro plano para ajudar usuários com baixa visão ou sensibilidade reduzida a cores.
  - *Exemplo*: Texto escuro em fundo claro ou vice-versa.

#### 2. Operável

**Objetivo**: Tornar a navegação e interação possíveis para todos os usuários.

**Requisitos**:
- **Navegação por Teclado**: Todo o site deve ser navegável usando apenas o teclado.
  - *Exemplo*: Todos os links, botões e formulários devem ser acessíveis via Tab, Shift+Tab, Enter.
- **Tempo Suficiente**: Prover tempo suficiente para que os usuários leiam e usem o conteúdo.
  - *Exemplo*: Permitir que usuários ajustem o tempo de expiração de uma sessão.
- **Evitar Conteúdo Piscante**: Evitar elementos piscantes que possam causar reações físicas adversas, como convulsões.
  - *Exemplo*: Não usar imagens que piscam rapidamente.
- **Ignorar Conteúdo Repetitivo**: Fornecer um meio de ignorar blocos de conteúdo repetitivos.
  - *Exemplo*: Um link "Pular para o conteúdo principal".
- **Conteúdo Oculto para Leitores de Tela**: O conteúdo fora da tela deve ser oculto da leitura do leitor de tela quando não relevante.
  - *Exemplo*: Ocultar elementos de menu que só aparecem ao passar o mouse para leitores de tela.
- **Texto de Links**: Links devem ter textos significativos que expliquem seu propósito.
  - *Exemplo*: Em vez de "Clique aqui", usar "Veja nossa política de privacidade".

#### 3. Compreensível

**Objetivo**: Tornar o conteúdo e a interface compreensíveis para os usuários.

**Requisitos**:
- **Evitar Jargões**: Usar linguagem simples e evitar termos técnicos.
  - *Exemplo*: Em vez de "Erro 404", usar "Página não encontrada".
- **Expansão de Abreviações**: Fornecer expansões para abreviações quando usadas.
  - *Exemplo*: Na primeira vez que usar "HTML", escreva "HTML (HyperText Markup Language)".
- **Evitar Mudanças de Contexto**: Evitar mudanças inesperadas de contexto que possam confundir os usuários.
  - *Exemplo*: Evitar abrir novas janelas sem aviso prévio.
- **Consistência na Navegação**: Manter uma estrutura de navegação consistente.
  - *Exemplo*: Usar a mesma barra de navegação em todas as páginas.
- **Rótulos Claros e Acionáveis**: Usar rótulos claros e exemplos nos campos de formulário.
  - *Exemplo*: Um campo de entrada de e-mail com o rótulo "E-mail" e exemplo "exemplo@dominio.com".

#### 4. Robusto

**Objetivo**: Garantir que o conteúdo seja robusto o suficiente para ser interpretado por uma ampla variedade de tecnologias assistivas.

**Requisitos**:
- **Validação da Linguagem de Marcação**: A linguagem de marcação (HTML, CSS) deve seguir padrões e ser validada.
  - *Exemplo*: Usar tags de abertura e fechamento corretas, IDs únicos.
- **Nome, Função e Estado**: Elementos devem ter seus nomes, funções e estados definidos e atualizados corretamente.
  - *Exemplo*: Uma caixa de seleção deve ter atributos `role="checkbox"` e `aria-checked="true|false"`.

#### WAI-ARIA (Accessible Rich Internet Applications)

- **Atributos ARIA**: Quando elementos personalizados são desenvolvidos, eles devem ser aumentados com atributos ARIA para que as tecnologias assistivas os entendam.
  - *Exemplo*: Para um elemento de lista estilizado como uma caixa de seleção, usar `role="checkbox"` e `aria-checked`.

### Conclusão

Seguir os padrões de conformidade de Nível A das WCAG 2.0 garante que o site seja acessível ao mínimo para todas as personas de usuário. Essas diretrizes são essenciais para criar uma base sólida de acessibilidade e garantir que todos os usuários possam acessar e interagir com o conteúdo da web de maneira eficaz e sem barreiras. Ao implementar esses requisitos, você cria um ambiente web mais inclusivo e acolhedor para todos.

### Estruturas de Desenvolvimento Habilitadas para Acessibilidade

Criar um site acessível é uma tarefa complexa, mas muitas estruturas de desenvolvimento modernas fornecem suporte e ferramentas para facilitar a implementação de acessibilidade. Abaixo, veremos como algumas das estruturas de desenvolvimento mais populares - React, Angular e Vue.js - oferecem suporte à acessibilidade, bem como ferramentas de auditoria automatizadas que podem ser usadas para garantir a conformidade com as diretrizes de acessibilidade.

#### React

**React** é uma biblioteca JavaScript popular para construir interfaces de usuário. Ela oferece várias maneiras de criar componentes acessíveis:

- **HTML Semântico**: React incentiva o uso de HTML semântico, o que é essencial para acessibilidade. Por exemplo, usar `<button>` para botões e `<nav>` para navegação.
- **Atributos ARIA**: React permite adicionar atributos ARIA diretamente aos componentes para definir papéis, estados e propriedades de elementos, tornando-os mais compreensíveis para tecnologias assistivas.
  - *Exemplo*: `<button aria-label="Close" onClick={handleClose}>X</button>`
- **React Testing Library**: Inclui ferramentas para testar a acessibilidade de componentes durante o desenvolvimento.

#### Angular

**Angular** é uma plataforma para construir aplicativos web dinâmicos. A equipe Angular mantém uma biblioteca chamada Angular Material, que oferece componentes de interface do usuário reutilizáveis e acessíveis:

- **Angular Material**: Esta biblioteca fornece componentes que seguem as melhores práticas de acessibilidade.
  - *Exemplo*: `<mat-form-field appearance="fill"><mat-label>Input</mat-label><input matInput></mat-form-field>`
- **Atributos ARIA**: Angular facilita a adição de atributos ARIA aos elementos.
  - *Exemplo*: `<button aria-describedby="desc">Click me</button><span id="desc">Description</span>`
- **Ferramentas de Teste**: Ferramentas de teste como Protractor e Karma podem ser usadas junto com Angular para testar acessibilidade.

#### Vue.js

**Vue.js** é uma estrutura JavaScript progressiva para construir interfaces de usuário:

- **HTML Semântico**: Assim como React, Vue.js encoraja o uso de HTML semântico.
- **Atributos ARIA**: A adição de atributos ARIA é direta em Vue.js.
  - *Exemplo*: `<button :aria-label="label" @click="handleClick">{{ buttonText }}</button>`
- **Plugins e Bibliotecas**: Existem plugins como Vue A11y, que ajudam a verificar a acessibilidade dos componentes Vue.

#### Ferramentas de Auditoria de Acessibilidade

Além do suporte intrínseco das estruturas, existem ferramentas automatizadas que ajudam a garantir que os padrões de acessibilidade sejam seguidos:

- **Axe by Deque Systems**: Uma das ferramentas mais populares, Axe pode ser integrada ao desenvolvimento e CI/CD para auditoria contínua de acessibilidade.
  - *Exemplo*: Extensão do navegador Axe para Chrome e Firefox, que pode ser usada para testar páginas web em tempo real.
- **Lighthouse**: Ferramenta de código aberto do Google que realiza auditorias de acessibilidade, além de desempenho, SEO e mais.
  - *Exemplo*: Disponível como uma extensão do Chrome ou integrada nas DevTools do Chrome.
- **Wave**: Ferramenta de avaliação de acessibilidade que fornece feedback visual sobre a acessibilidade de uma página web.
  - *Exemplo*: Extensão do navegador Wave para Chrome e Firefox.
- **Pa11y**: Ferramenta automatizada de testes de acessibilidade que pode ser integrada em pipelines de CI.
  - *Exemplo*: Pode ser usada para executar testes de acessibilidade e gerar relatórios.

### Conclusão

As principais estruturas de desenvolvimento como React, Angular e Vue.js fornecem suporte robusto para a criação de sites acessíveis, geralmente incentivando o uso de HTML semântico e facilitando a adição de atributos ARIA. Além disso, ferramentas de auditoria automatizadas como Axe, Lighthouse, Wave e Pa11y são essenciais para identificar e corrigir problemas de acessibilidade durante o desenvolvimento. Com essas ferramentas e práticas, as equipes de desenvolvimento podem assegurar que suas aplicações sejam inclusivas e acessíveis a todos os usuários.

### Estratégia de Teste de Acessibilidade

Para garantir que os requisitos de acessibilidade sejam atendidos, é crucial incorporar as melhores práticas de acessibilidade desde o início do projeto e mantê-las durante todo o ciclo de vida do desenvolvimento do software. A abordagem shift-left, que enfatiza a integração antecipada de testes, é essencial para alcançar essa meta.

### Implementação Shift-Left de Testes de Acessibilidade

A implementação shift-left de testes de acessibilidade significa incorporar verificações de acessibilidade em todas as fases do ciclo de desenvolvimento, desde o design até a entrega. A Figura 9-3 ilustra essa abordagem, destacando a importância de considerar a acessibilidade em cada etapa.

#### Figura 9-3. Uma estratégia de teste de acessibilidade shift-left (A figura deve ilustrar a incorporação de práticas de acessibilidade em várias etapas do desenvolvimento de software, como design, desenvolvimento, teste e entrega).

### Lista de Verificação de Acessibilidade em Histórias de Usuário

Adicionar uma lista de verificação de acessibilidade a todas as histórias de usuário ajuda desenvolvedores e testadores a garantir que os requisitos de acessibilidade sejam atendidos meticulosamente. A seguir, uma lista de verificação genérica que pode ser personalizada para atender às necessidades específicas do seu aplicativo.

#### Lista de Verificação de Acessibilidade

1. **Verificação do Título da Página**:
   - O título da página deve ser claro e descrever o contexto da página dentro do site.
   - Passe o mouse sobre a guia do navegador para verificar se o título aparece corretamente.

2. **Estrutura Básica da Página**:
   - Verifique se a página tem atributos e hierarquia de elementos adequados.
   - Desative o CSS e verifique se os elementos estão listados em uma ordem amigável ao leitor de tela.
   - Utilize a visualização em árvore de acessibilidade no DevTools do Chrome para ver a ordem dos elementos.

3. **Navegação pelo Teclado**:
   - Garanta que toda a navegação do site possa ser feita apenas pelo teclado.
   - Verifique se há realce adequado dos elementos e se as operações de teclado para frente, para trás e para sair funcionam corretamente.

4. **Mensagens de Erro e Rótulos**:
   - Assegure que as mensagens de erro, rótulos e links comuniquem a intenção correta.
   - Verifique se todos os textos na página são claros e compreensíveis.

5. **Legibilidade do Texto**:
   - Teste a legibilidade da página ao redimensionar o texto usando as preferências do sistema ou as opções de zoom do navegador.

6. **Legibilidade em Tons de Cinza**:
   - Ative a configuração de tons de cinza (por exemplo, no Mac, vá para Preferências do Sistema → Acessibilidade → Exibição → Usar tons de cinza) e verifique a legibilidade.

7. **Legendas para Conteúdo de Vídeo e Áudio**:
   - Verifique se o conteúdo de vídeo e áudio tem legendas significativas e sincronizadas.

8. **Descrições de Texto Alternativas para Imagens**:
   - Verifique se as imagens têm descrições de texto alternativas significativas.
   - Desative o download de imagens no navegador para verificar se o texto alternativo aparece corretamente (por exemplo, no Chrome, vá para Configurações → Configurações do site → Imagens → Bloquear).

9. **Fluxo do Leitor de Tela**:
   - Certifique-se de que o fluxo do leitor de tela seja significativo e permita que o usuário conclua o fluxo de forma eficiente.

### Conclusão

Incorporar uma estratégia de teste de acessibilidade shift-left garante que os requisitos de acessibilidade sejam considerados desde o início e mantidos ao longo do desenvolvimento. Utilizando listas de verificação de acessibilidade em histórias de usuário e validando continuamente esses critérios, sua equipe pode criar produtos que sejam inclusivos e acessíveis a todos os usuários.

### Ferramentas Automatizadas de Auditoria de Acessibilidade

A lista de verificação de acessibilidade é crucial, mas também é essencial complementar essa abordagem com ferramentas automatizadas de auditoria que podem verificar rapidamente a estrutura HTML básica e alertar sobre a ausência de tags de acessibilidade. Essas ferramentas podem economizar tempo e esforço, fornecendo feedback instantâneo durante o desenvolvimento.

#### Ferramentas de Linting

1. **eslint-plugin-jsx-a11y**:
   - É uma ferramenta de linting para React que se integra ao ESLint.
   - Enforce diversos padrões de acessibilidade diretamente no JSX.
   - Ajuda a identificar e corrigir problemas de acessibilidade enquanto você escreve o código.

2. **Codelyzer**:
   - Ferramenta de linting para Angular que verifica o código TypeScript, HTML e CSS.
   - Define regras específicas para garantir que o código esteja em conformidade com os padrões de acessibilidade.
   - Fornece feedback imediato durante o desenvolvimento.

#### Ferramentas de Verificação de Tempo de Execução

1. **axe-core**:
   - Ferramenta robusta de acessibilidade que pode ser integrada em testes de unidade e de integração.
   - Disponível como uma extensão do navegador para testes manuais.
   - Pode ser usada em conjunto com frameworks de teste como Jest, Cypress, e Selenium para testes automatizados.

2. **Pa11y CI**:
   - Ferramenta de verificação de acessibilidade que pode ser integrada em pipelines de CI/CD.
   - Executa verificações de acessibilidade em páginas web e gera relatórios detalhados.
   - Suporta diferentes configurações de navegador e permite testes contínuos durante o desenvolvimento.

3. **Lighthouse CI**:
   - Ferramenta de auditoria automatizada do Google que verifica desempenho, acessibilidade, SEO e melhores práticas.
   - Pode ser executada como uma extensão do navegador ou integrada em pipelines de CI/CD.
   - Gera relatórios detalhados e fornece sugestões de melhorias.

### Integração no Processo de Desenvolvimento

#### Analisadores de Código Estático

As ferramentas de linting, como eslint-plugin-jsx-a11y e Codelyzer, são usadas para impor padrões de acessibilidade enquanto você escreve o código. Elas fornecem feedback imediato e ajudam a corrigir problemas antes que o código seja integrado.

#### Verificadores de Tempo de Execução

Ferramentas como axe-core, Pa11y CI e Lighthouse CI fornecem feedback sobre a página da web real após o desenvolvimento. Elas podem ser executadas na máquina de desenvolvimento local para obter feedback mais rápido sobre as páginas desenvolvidas como parte de cada história de usuário e também como parte do CI para testes contínuos.

### Fluxos Funcionais de Acessibilidade

Além de usar ferramentas automatizadas, é essencial implementar fluxos funcionais que atendam às necessidades de acessibilidade. Alguns exemplos incluem:

- **Seção de Transcrição**: Adicionar uma seção de transcrição separada abaixo de qualquer vídeo/áudio.
- **Mensagens de Erro Significativas**: Garantir que todas as mensagens de erro e instruções sejam claras e compreensíveis.
- **Navegação por Teclado**: Implementar e testar a navegação completa por teclado para garantir que todos os elementos sejam acessíveis sem o uso do mouse.

### Conclusão

Incorporar ferramentas automatizadas de auditoria de acessibilidade no processo de desenvolvimento ajuda a identificar e corrigir problemas de acessibilidade rapidamente. Combinando essas ferramentas com testes funcionais automatizados e uma abordagem shift-left, sua equipe pode garantir que os produtos sejam inclusivos e acessíveis a todos os usuários desde o início.

### Teste Manual de Acessibilidade

O teste manual de acessibilidade é essencial para garantir que todos os aspectos do site sejam acessíveis, além das verificações automatizadas. Ele complementa as ferramentas automáticas, que cobrem apenas uma parte das verificações necessárias. O teste manual se concentra em aspectos funcionais e de usabilidade que exigem intervenção humana para validação, como o uso de leitores de tela e navegação por teclado.

#### Teste de História de Usuário

**Objetivo**: Garantir que os critérios de acessibilidade sejam atendidos para cada história de usuário individual.

**Passos**:
1. **Verifique a lista de verificação de acessibilidade**: Certifique-se de que todos os itens da lista de verificação de acessibilidade estão sendo seguidos para as páginas envolvidas na história de usuário.
2. **Use a ferramenta WAVE**: Utilize o WAVE (Web Accessibility Evaluation Tool) para identificar problemas de acessibilidade na página da web. O WAVE destaca visualmente os problemas na página, ajudando a identificar questões que podem não ser óbvias.
3. **Auditoria com Lighthouse**: Use o Lighthouse no Chrome DevTools para realizar uma auditoria de acessibilidade. O Lighthouse fornece um relatório detalhado de problemas e recomendações.

#### Teste de Recursos

**Objetivo**: Garantir que os usuários finais possam completar os fluxos de usuário de um recurso específico usando apenas o teclado e leitores de tela.

**Passos**:
1. **Navegação por teclado**: Verifique a navegação usando as teclas Tab e Shift+Tab para avançar e retroceder, Enter para selecionar, e as setas para cima e para baixo para navegação em menus suspensos.
   - **Foco do elemento**: Verifique se o foco está no elemento correto e se ele está claramente destacado.
2. **Leitores de tela**: Use um leitor de tela para navegar pelo site e validar se todas as funcionalidades podem ser usadas corretamente. Ferramentas como JAWS, NVDA ou o leitor de tela do Chrome são úteis para esse teste.
3. **Fluxo de usuário**: Garanta que o fluxo de usuário de ponta a ponta seja coerente e acessível. Isso inclui validar mensagens de erro, rótulos de campos, e qualquer outra interação.

#### Teste de Liberação

**Objetivo**: Obter feedback real de usuários finais com deficiências antes do lançamento oficial.

**Passos**:
1. **Testes com usuários reais**: Envolva usuários finais reais, incluindo pessoas com deficiências, para testar o site. Eles podem fornecer feedback valioso sobre a usabilidade e acessibilidade do site em situações reais.
2. **Serviços de teste remoto**: Utilize serviços como UserTesting.com para encontrar testadores com deficiências que podem fornecer feedback detalhado sobre o site.

#### Certificação de Conformidade

**Objetivo**: Garantir que o site esteja em conformidade com os padrões WCAG antes do lançamento.

**Passos**:
1. **Avaliação de especialistas**: Contrate especialistas em padrões WCAG para avaliar a conformidade do site. Isso pode ser feito por especialistas internos ou consultores externos.
2. **Correções finais**: Baseado no feedback dos especialistas, faça as correções necessárias para atender aos critérios de conformidade.

### Estratégia de Implementação

Para garantir a acessibilidade desde o início do desenvolvimento, adote uma abordagem "shift-left", onde as considerações de acessibilidade são integradas desde as fases iniciais do projeto:

1. **Definir personas de acessibilidade**: Identifique e defina as personas de acessibilidade do aplicativo. Use essas personas para criar histórias de usuário que atendam às suas necessidades.
2. **Incorporar a lista de verificação de acessibilidade**: Anexe a lista de verificação de acessibilidade a todas as histórias de usuário.
3. **Testes contínuos**: Realize testes de acessibilidade continuamente durante o desenvolvimento, usando ferramentas automatizadas e testes manuais.
4. **Treinamento da equipe**: Garanta que toda a equipe de desenvolvimento esteja ciente das melhores práticas de acessibilidade e saiba como aplicar as diretrizes WCAG 2.0.

Com essa abordagem, você garantirá que a acessibilidade seja uma parte integral do ciclo de desenvolvimento, reduzindo retrabalho e garantindo uma experiência inclusiva para todos os usuários.

### Exercícios de Auditoria de Acessibilidade com Ferramentas Automatizadas

Aqui está um guia prático para usar ferramentas de auditoria de acessibilidade, como o WAVE, para avaliar a conformidade do seu site com os padrões WCAG 2.0. Vamos explorar o fluxo de trabalho com a ferramenta WAVE e como interpretar os resultados obtidos.

#### 1. **Uso da Ferramenta WAVE**

**Objetivo**: Realizar uma auditoria preliminar de acessibilidade para identificar problemas estruturais e de conformidade na página da web.

**Passos**:

1. **Acessar o WAVE**:
   - Abra o site do WAVE: [WAVE Accessibility Tool](https://wave.webaim.org/).

2. **Inserir o URL**:
   - Digite o URL do seu site ou de um site de demonstração inacessível (por exemplo, o site de demonstração da WAI) na caixa "Endereço da página da Web".

3. **Executar a Auditoria**:
   - Clique na seta para iniciar a auditoria. O WAVE irá processar a página e gerar um relatório de acessibilidade.

4. **Analisar o Relatório**:
   - **Resumo**: Verifique o resumo dos resultados, que incluirá contagens de erros, alertas e outros problemas. Por exemplo, você pode ver ícones que indicam falhas, sucessos e alertas ao lado dos elementos da página.
   - **Detalhes**: Clique na guia "Detalhes" para ver uma análise mais aprofundada dos erros identificados, como imagens sem texto alternativo ou atributos de contraste ausentes. A Figura 9-5 mostra como os detalhes dos erros são exibidos.

5. **Visualizar a Estrutura da Página**:
   - Use o controle para desativar os estilos CSS e visualizar a estrutura da página como seria vista por tecnologias assistivas. A guia "Estrutura" mostrará a análise da estrutura da página. Isso pode revelar problemas como falta de hierarquia ou seções mal definidas. Veja a Figura 9-6 para um exemplo.

6. **Comparar com um Site Acessível**:
   - Teste o site de demonstração acessível da WAI usando o mesmo método para comparar como uma página acessível deve ser estruturada. Veja a Figura 9-7 para entender a hierarquia e a estrutura de uma página acessível.

#### 2. **Testando com Ferramentas Adicionais**

**Objetivo**: Complementar a auditoria WAVE com outras ferramentas para uma análise mais completa.

1. **Lighthouse**:
   - **Acessar Lighthouse**: Abra o Chrome DevTools (F12 ou Ctrl+Shift+I) e vá para a aba "Lighthouse".
   - **Executar Auditoria**: Selecione as opções relevantes para a auditoria e clique em "Gerar relatório". O Lighthouse fornecerá um relatório detalhado sobre a acessibilidade, desempenho e outras métricas da página.

2. **axe-core**:
   - **Integrar ao Navegador**: Instale a extensão axe para o seu navegador (Chrome ou Firefox).
   - **Executar Auditoria**: Abra a ferramenta de desenvolvedor do navegador e execute a auditoria com a extensão axe para obter uma análise detalhada da acessibilidade.

3. **Pa11y CI**:
   - **Configurar Pa11y CI**: Configure Pa11y CI para integração contínua no seu fluxo de desenvolvimento.
   - **Executar Testes**: Execute os testes em seu ambiente de desenvolvimento para garantir que os padrões de acessibilidade sejam atendidos constantemente.

#### 3. **Testes Manuais**

**Objetivo**: Complementar as auditorias automatizadas com testes manuais para garantir uma experiência acessível real.

1. **Teste de Navegação por Teclado**:
   - Navegue pelo site usando apenas o teclado (Tab, Shift+Tab, Enter, Setas) e verifique se todos os elementos interativos são acessíveis e visíveis.

2. **Teste de Leitor de Tela**:
   - Use um leitor de tela (como NVDA ou JAWS) para verificar se o conteúdo é lido corretamente e se a navegação é fluida.

3. **Verificação de Texto Alternativo e Legibilidade**:
   - Inspecione manualmente imagens e outros elementos para garantir que possuem texto alternativo apropriado e que a legibilidade não é afetada por questões de contraste ou tamanho.

4. **Teste de Usuários Reais**:
   - Realize testes com usuários reais, incluindo pessoas com deficiências, para obter feedback sobre a experiência e identificar áreas de melhoria que não seriam visíveis apenas com testes automatizados.

### Conclusão

A combinação de ferramentas automatizadas e testes manuais oferece uma abordagem robusta para garantir a acessibilidade do seu site. As ferramentas automatizadas como o WAVE e o Lighthouse fornecem uma análise rápida e identificam problemas estruturais, enquanto os testes manuais garantem que a experiência do usuário seja realmente acessível. Integrar essas práticas em seu processo de desenvolvimento e teste ajudará a criar um site que seja inclusivo e utilizável por todos.

### Usando o Lighthouse para Auditar Acessibilidade

O Lighthouse é uma ferramenta poderosa e integrada ao Chrome DevTools, ideal para auditar a acessibilidade de sites, mesmo que eles não estejam acessíveis publicamente. Aqui está um guia prático para usar o Lighthouse na auditoria de acessibilidade de um site.

#### Fluxo de Trabalho com o Lighthouse

**Objetivo**: Realizar uma auditoria de acessibilidade em um site usando a ferramenta Lighthouse do Google Chrome.

**Passos**:

1. **Acessar o Site**:
   - Abra o Google Chrome e carregue o site de demonstração inacessível do WAI ou qualquer outro site que você deseja auditar.

2. **Abrir o Chrome DevTools**:
   - Utilize o atalho `Cmd+Option+I` no macOS ou `Shift+Ctrl+J` no Windows/Linux para abrir as Ferramentas de Desenvolvedor do Chrome.

3. **Selecionar a Guia Lighthouse**:
   - Navegue até a guia **Lighthouse** dentro do DevTools. Caso não veja a guia, você pode encontrá-la clicando no menu de três pontos no canto superior direito do DevTools e selecionando **Lighthouse**.

   ![Figura 9-8](https://via.placeholder.com/600x400)  
   _Figura 9-8: Usando o Lighthouse no Chrome DevTools para gerar um relatório de acessibilidade_

4. **Configurar a Auditoria**:
   - Na guia Lighthouse, selecione a categoria **Acessibilidade**. Você pode também optar por outras categorias se desejar uma análise mais completa (como Performance, SEO, etc.).

5. **Gerar Relatório**:
   - Clique em **Gerar relatório**. O Lighthouse realizará a auditoria e apresentará os resultados em poucos minutos, dependendo da complexidade do site.

6. **Revisar o Relatório**:
   - Após a geração, o relatório será exibido na mesma guia do Lighthouse, como mostrado na Figura 9-9. O relatório inclui:

     - **Pontuação Geral**: Uma pontuação que indica o nível de conformidade com os padrões de acessibilidade.
     - **Problemas Identificados**: Lista de problemas encontrados, como contraste inadequado ou atributos ausentes.
     - **Linhas de Código**: Exibição das linhas de código reais que contêm os erros, facilitando a depuração.
     - **Links Educacionais**: Recursos e links que fornecem orientações sobre como corrigir os problemas encontrados.
     - **Itens Adicionais**: Uma lista de verificação que detalha itens que a auditoria não cobre automaticamente e que precisam ser verificados manualmente.

   ![Figura 9-9](https://via.placeholder.com/600x400)  
   _Figura 9-9: Relatório de auditoria de acessibilidade do Lighthouse para o site de demonstração inacessível do WAI_

#### Interpretação dos Resultados

- **Pontuação Geral**: Fornece uma visão geral do estado da acessibilidade da página. Uma pontuação baixa indica que há vários problemas que precisam ser abordados.
  
- **Problemas Identificados**: Analise cada problema listado. O Lighthouse fornece uma descrição do problema e recomendações para a correção. Corrija esses problemas para melhorar a acessibilidade.

- **Linhas de Código**: Use a visualização do código para localizar e corrigir erros diretamente no seu código-fonte.

- **Links Educacionais**: Explore esses links para entender melhor os problemas e as soluções recomendadas.

- **Itens Adicionais**: Complete a verificação manual para garantir que todos os aspectos de acessibilidade sejam cobertos, já que o Lighthouse pode não identificar todos os problemas automaticamente.

### Conclusão

Utilizar o Lighthouse para auditoria de acessibilidade é uma maneira eficiente de obter uma visão rápida e abrangente sobre a conformidade de um site com os padrões de acessibilidade. A integração com o Chrome DevTools facilita o processo de auditoria durante o desenvolvimento, permitindo a identificação e correção de problemas antes do lançamento do site. Combinando o uso do Lighthouse com outras ferramentas e testes manuais, você pode garantir uma experiência mais inclusiva e acessível para todos os usuários.

### Usando o Módulo Lighthouse Node para Auditoria de Acessibilidade

O módulo Lighthouse Node é uma excelente ferramenta para executar auditorias de acessibilidade diretamente da linha de comando. Ele é útil para integrar auditorias de acessibilidade em pipelines de integração contínua (CI) e fornece flexibilidade adicional em como as auditorias são configuradas e relatadas.

#### Fluxo de Trabalho para Usar o Lighthouse Node

**Objetivo**: Executar auditorias de acessibilidade usando o módulo Lighthouse Node e integrar os resultados em seu fluxo de trabalho de CI.

**Passos**:

1. **Instalação do Lighthouse Node**:
   - Certifique-se de que você tenha o Node.js instalado em seu sistema. Se não tiver, você pode baixá-lo e instalá-lo a partir do [site oficial do Node.js](https://nodejs.org/).
   - Abra o terminal ou prompt de comando e execute o seguinte comando para instalar o Lighthouse globalmente:

     ```bash
     npm install -g lighthouse
     ```

2. **Executar a Auditoria**:
   - Use o comando a seguir para executar uma auditoria de acessibilidade em um URL específico. A opção `--chrome-flags="--headless"` faz com que o Chrome execute em modo headless, o que significa que ele não abrirá uma janela do navegador visível:

     ```bash
     lighthouse --chrome-flags="--headless" URL
     ```

     Substitua `URL` pelo endereço da página que você deseja auditar. Por exemplo:

     ```bash
     lighthouse --chrome-flags="--headless" https://example.com
     ```

3. **Revisar o Relatório**:
   - O Lighthouse gera um relatório em formato HTML por padrão. Esse arquivo HTML será salvo no mesmo diretório de trabalho onde você executou o comando. Abaixo está um exemplo de como o relatório pode ser visualizado:

     ![Figura 9-10](https://via.placeholder.com/600x400)  
     _Figura 9-10: Relatório da Lighthouse CLI para o site de demonstração inacessível do WAI_

4. **Integrar com CI**:
   - **Adicionar como Artefato**: Você pode adicionar o arquivo HTML gerado como um artefato de saída no seu pipeline de CI para facilitar a visualização e verificação dos resultados.
   - **Falha Condicional**: Configure sua tarefa de build para falhar se a pontuação de acessibilidade estiver abaixo de um limite aceitável. Isso pode ser feito criando um wrapper em torno do comando Lighthouse que analisa o relatório gerado e define o status de saída da tarefa de build com base na pontuação.

     Um exemplo simples de wrapper em shell script pode ser:

     ```bash
     # Execute o Lighthouse e salve o relatório
     lighthouse --chrome-flags="--headless" https://example.com --output html --output-path ./report.html

     # Verifique a pontuação de acessibilidade e defina o status de saída com base nela
     if grep -q 'Accessibility score: 100' ./report.html; then
       echo "Acessibilidade: OK"
       exit 0
     else
       echo "Acessibilidade: Falha"
       exit 1
     fi
     ```

#### Benefícios do Módulo Lighthouse Node

- **Automação**: Integrar auditorias de acessibilidade em pipelines de CI permite que a acessibilidade seja avaliada automaticamente a cada commit ou pull request.
- **Flexibilidade**: A execução a partir da linha de comando oferece flexibilidade para configurar auditorias de acordo com as necessidades específicas do projeto.
- **Relatórios Detalhados**: O relatório HTML fornece uma visão detalhada dos problemas encontrados e oferece links educacionais para correção.

### Conclusão

O módulo Lighthouse Node é uma ferramenta poderosa para a auditoria de acessibilidade, especialmente quando integrado a processos de CI. Ele permite a automação e a análise detalhada de acessibilidade, ajudando a garantir que os problemas sejam detectados e corrigidos de maneira eficiente durante o ciclo de desenvolvimento. Ao utilizar o Lighthouse Node, você pode melhorar a qualidade e a acessibilidade do seu site enquanto mantém a conformidade com os padrões estabelecidos.


### Ferramentas de Teste Adicionais para Acessibilidade

Além do WAVE e do Lighthouse, outras ferramentas podem ajudar a garantir que seu site ou aplicativo esteja acessível. Vamos explorar duas ferramentas populares: Pa11y CI e axe-core.

#### Pa11y CI

**Pa11y CI** é uma ferramenta de linha de comando que pode ser usada para executar auditorias de acessibilidade em uma ou mais URLs. Ele é especialmente útil para integração contínua (CI) e pode ser configurado para verificar a acessibilidade de várias páginas da web conforme definido em um arquivo de configuração ou por meio de um mapa do site XML.

**Configuração e Uso**:

1. **Instalação**:
   - Certifique-se de que o Node.js esteja instalado.
   - Instale o Pa11y CI globalmente com o seguinte comando:

     ```bash
     npm install -g pa11y-ci
     ```

2. **Arquivo de Configuração**:
   - Crie um arquivo JSON de configuração para definir as URLs a serem auditadas e outras opções. Um exemplo de arquivo de configuração `pa11y-ci-config.json` é mostrado abaixo:

     ```json
     {
         "defaults": {
             "timeout": 1000,
             "viewport": {
                 "width": 320,
                 "height": 480
             }
         },
         "urls": [
             "https://www.w3.org/WAI/demos/bad/after/home.html",
             "https://www.w3.org/WAI/demos/bad/before/home.html"
         ]
     }
     ```

3. **Execução da Auditoria**:
   - Para executar uma auditoria com base no arquivo de configuração, use o comando:

     ```bash
     pa11y-ci --config pa11y-ci-config.json
     ```

   - Se preferir usar um mapa do site XML, você pode passá-lo na linha de comando:

     ```bash
     pa11y-ci --sitemap=https://example.com/sitemap.xml
     ```

4. **Opções de Configuração**:
   - **Definir Limites**: Você pode definir limites para o número de erros e avisos permitidos antes de falhar a construção. Isso é útil para garantir que os problemas críticos sejam tratados.
   - **Tamanho do Visor**: Configure o tamanho da janela para simular diferentes resoluções.
   - **Tempo de Espera**: Ajuste o tempo de espera para garantir que a página tenha tempo suficiente para carregar.

**Exemplo de Relatório**:
O Pa11y CI fornece um relatório detalhado dos problemas encontrados, semelhante ao WAVE e ao Lighthouse, e é ideal para integração em pipelines de CI.

#### axe-core

**axe-core** é uma biblioteca JavaScript que pode ser usada para executar auditorias de acessibilidade no navegador. Ela pode ser integrada em testes automatizados ou usada para auditorias manuais no navegador.

**Configuração e Uso**:

1. **Instalação**:
   - Você pode adicionar `axe-core` ao seu projeto como uma dependência:

     ```bash
     npm install axe-core
     ```

2. **Uso em Testes Automatizados**:
   - Para usar `axe-core` em testes automatizados, você pode integrá-lo com frameworks de teste como Jest ou Mocha. Abaixo está um exemplo de como usar o `axe-core` com o framework de teste Cypress:

     ```javascript
     // cypress/support/commands.js
     import 'cypress-axe';

     Cypress.Commands.add('checkA11y', (context = null, options = null, violationCallback = null) => {
         cy.injectAxe();
         cy.checkA11y(context, options, violationCallback);
     });
     ```

3. **Uso Manual no Navegador**:
   - **Extensão do Navegador**: O axe-core também está disponível como uma extensão para Chrome e Firefox, facilitando a auditoria manual. Após instalar a extensão, você pode abrir a ferramenta no DevTools para executar auditorias e visualizar os resultados.

4. **Integração em CI**:
   - Para integração com CI, você pode usar a biblioteca em scripts de teste automatizados e gerar relatórios que podem ser usados para verificar a conformidade de acessibilidade durante o processo de build.

**Exemplo de Relatório**:
O `axe-core` fornece relatórios detalhados que identificam problemas de acessibilidade e oferecem sugestões para correção. Ele destaca problemas diretamente na interface do navegador e pode ser usado para criar relatórios em diferentes formatos.

### Conclusão

- **Pa11y CI** é ideal para integração contínua e oferece uma maneira fácil de verificar a acessibilidade de várias URLs com configurações flexíveis.
- **axe-core** é uma poderosa biblioteca de auditoria que pode ser usada tanto para testes manuais quanto automatizados, proporcionando uma visão detalhada dos problemas de acessibilidade.

Ambas as ferramentas complementam o Lighthouse e o WAVE, ajudando a garantir que seu site ou aplicativo esteja acessível e atenda aos padrões de conformidade.

### axe-core: Uma Visão Geral

O **axe-core** é uma ferramenta poderosa e flexível para a auditoria de acessibilidade. Ela oferece uma maneira prática de identificar problemas de acessibilidade diretamente no código de uma página web. Vamos explorar como o axe-core pode ser integrado em diferentes contextos e como ele pode ajudar a melhorar a acessibilidade do seu aplicativo.

#### Funcionalidade do axe-core

1. **Cobertura e Suporte**:
   - O axe-core é capaz de identificar cerca de 57% dos problemas de conformidade com as diretrizes WCAG automaticamente.
   - É compatível com uma ampla gama de navegadores, incluindo Microsoft Edge, Google Chrome, Firefox, Safari e Internet Explorer.

2. **Integração com Ferramentas e Frameworks**:
   - **Java Selenium WebDriver**: Para integrar o axe-core com Selenium, você pode adicionar a dependência `axe-core` ao seu projeto Maven. Isso permite que você execute auditorias de acessibilidade como parte de testes automatizados usando Selenium.
   - **Cypress**: O módulo Node `cypress-axe` pode ser usado para integrar o axe-core com o Cypress, um framework popular para testes de frontend. Isso permite que você execute auditorias de acessibilidade dentro dos testes Cypress.
   - **Vue, React**: Há também bibliotecas específicas como `vue-axe` e `react-axe` para integrar o axe-core com frameworks de frontend como Vue.js e React.

#### Exemplos de Uso

1. **Em Testes Funcionais com Cypress**:
   - Primeiro, adicione o módulo `cypress-axe` ao seu projeto:

     ```bash
     npm install --save-dev cypress-axe
     ```

   - Configure o Cypress para usar o `cypress-axe` adicionando o seguinte código no seu arquivo de suporte:

     ```javascript
     // cypress/support/commands.js
     import 'cypress-axe';

     Cypress.Commands.add('checkA11y', (context = null, options = null, violationCallback = null) => {
         cy.injectAxe();
         cy.checkA11y(context, options, violationCallback);
     });
     ```

   - Use o comando `checkA11y` em seus testes:

     ```javascript
     describe('My accessible app', () => {
         it('should have no detectable a11y violations on load', () => {
             cy.visit('https://example.com');
             cy.checkA11y();
         });
     });
     ```

2. **Em Testes de Frontend com Selenium e Java**:
   - Adicione `axe-core` ao seu projeto Maven:

     ```xml
     <dependency>
         <groupId>com.deque.axe</groupId>
         <artifactId>axe-selenium-java</artifactId>
         <version>4.0.0</version>
     </dependency>
     ```

   - Configure e execute a auditoria:

     ```java
     import com.deque.axe.AXE;
     import org.openqa.selenium.WebDriver;
     import org.openqa.selenium.chrome.ChromeDriver;

     public class AccessibilityTest {
         public static void main(String[] args) {
             WebDriver driver = new ChromeDriver();
             driver.get("https://example.com");

             AXE.Builder builder = new AXE.Builder(driver);
             AXE axe = builder.build();
             axe.inject();
             Results results = axe.analyze();

             System.out.println(results.getViolations());
             driver.quit();
         }
     }
     ```

#### Relatórios e Feedback

O axe-core gera relatórios detalhados sobre problemas de acessibilidade encontrados. Os relatórios incluem:
- **Descrição dos Problemas**: Detalhes sobre os problemas encontrados e o impacto potencial na acessibilidade.
- **Sugestões de Correção**: Orientações sobre como corrigir os problemas identificados.
- **Localização do Erro**: Linhas de código específicas onde os problemas foram detectados.

### Resumo

- **Ferramentas Autônomas**: O axe-core, junto com ferramentas como WAVE e Lighthouse, ajuda a identificar problemas de acessibilidade de maneira automatizada, economizando tempo e oferecendo feedback rápido durante o desenvolvimento.
- **Testes Funcionais**: A integração do axe-core em testes funcionais com frameworks como Cypress e Selenium permite uma verificação aprofundada da acessibilidade durante o ciclo de vida do desenvolvimento.
- **Feedback Contínuo**: A integração de ferramentas de auditoria de acessibilidade no pipeline de CI e na fase de desenvolvimento ajuda a garantir que problemas sejam detectados e resolvidos mais cedo.

Usar o axe-core e outras ferramentas complementares pode garantir que seu aplicativo seja acessível a todos, melhorando a experiência para todos os usuários, incluindo aqueles com deficiências. Assim, você pode proporcionar um acesso mais inclusivo e confortável para uma ampla gama de usuários, incluindo Matt, Fred, Helen, e muitos outros.

### Acessibilidade como Cultura

Acessibilidade vai além de simples práticas técnicas aplicadas a websites e aplicativos; é uma filosofia que deve permeiar todos os aspectos da criação de conteúdo e interação digital. Essa mentalidade é fundamental para garantir que todos, independentemente de suas habilidades ou deficiências, tenham acesso equitativo à informação e às funcionalidades. 

#### Adotando uma Mentalidade de Acessibilidade

1. **Consciência e Inclusão**:
   - **Perguntas Críticas**: Reflexões sobre acessibilidade devem ser incorporadas em todos os aspectos do trabalho. Por exemplo, se você enviar um e-mail com imagens, considere se há texto alternativo suficiente para que aqueles que usam leitores de tela possam compreender o conteúdo. 
   - **Fontes Legíveis**: Avalie o tamanho e o contraste das fontes em apresentações para garantir que sejam legíveis para todos, incluindo aqueles com deficiência visual. 

2. **Simplicidade e Clareza**:
   - **Linguagem Clara**: Optar por uma comunicação simples e direta ao invés de jargões ou linguagem complexa pode beneficiar todos os usuários, não apenas aqueles com dificuldades cognitivas. Mensagens claras são mais fáceis de entender e processar.

3. **Design Universal**:
   - **Princípios de Design Inclusivo**: Aplicar princípios de design universal em todos os projetos garante que o conteúdo seja acessível para o maior número possível de pessoas. Isso inclui considerar a acessibilidade em documentos, apresentações, e-mails e interações offline.

4. **Feedback Contínuo**:
   - **Testes e Avaliações**: Incorporar feedback de usuários com diferentes habilidades é crucial. Realizar testes com usuários reais, especialmente aqueles com deficiências, ajuda a identificar e corrigir problemas que podem não ser visíveis para desenvolvedores e designers.

5. **Educação e Conscientização**:
   - **Treinamento**: Educar equipes sobre a importância da acessibilidade e como implementá-la é essencial. Programas de treinamento e workshops podem ajudar a internalizar práticas acessíveis em todos os aspectos do trabalho.

#### Exemplos Práticos

1. **Emails**:
   - **Imagens e Texto Alternativo**: Sempre adicione texto alternativo descritivo às imagens em e-mails. Isso garante que os leitores de tela possam transmitir a mensagem das imagens para usuários com deficiência visual.

2. **Documentos e Apresentações**:
   - **Tamanho e Contraste da Fonte**: Use fontes legíveis e com contraste adequado. Evite tamanhos de fonte pequenos e garanta que o texto seja acessível para aqueles com baixa visão.
   - **Estrutura e Navegação**: Organize documentos e apresentações de forma que sejam fáceis de navegar e compreender. Use títulos, listas e marcadores para estruturar o conteúdo.

3. **Comunicação Verbal**:
   - **Simplicidade e Clareza**: Evite termos técnicos e vernáculo erudito. Comunicações claras e simples são mais inclusivas e ajudam a garantir que todos entendam a mensagem.

### Conclusão

Acessibilidade como cultura significa adotar uma abordagem proativa e inclusiva em todos os aspectos da criação e comunicação. Ao adotar essa mentalidade, você não apenas melhora a experiência para pessoas com deficiências, mas também cria um ambiente mais acessível e compreensível para todos os usuários. Cada esforço para garantir acessibilidade contribui para uma web mais inclusiva e equitativa.

### Principais Takeaways sobre Acessibilidade na Web

1. **Acessibilidade para Todos**:
   - **Essencial e Útil**: Recursos de acessibilidade são vitais para algumas pessoas, mas beneficiam a todos. Eles melhoram a experiência geral e a usabilidade dos aplicativos e sites.

2. **Impacto Econômico**:
   - **Economia Significativa**: A comunidade com deficiência é uma grande economia global em termos de poder de compra. Isso reforça a acessibilidade como uma estratégia comercial inteligente.

3. **Exigências Legais**:
   - **Conformidade Legal**: Muitos governos têm legislações que exigem acessibilidade, tornando-a um requisito legal. Certifique-se de estar em conformidade com as regulamentações relevantes.

4. **Diretrizes WCAG**:
   - **Seguir as Diretrizes**: O W3C WAI fornece as Diretrizes de Acessibilidade de Conteúdo da Web (WCAG), que são essenciais para criar conteúdo acessível. Consulte a versão mais recente dessas diretrizes ao desenvolver seu projeto.

5. **Tecnologias Adaptativas**:
   - **Explorar Tecnologias**: O ecossistema de acessibilidade é vasto e inclui tecnologias além da web. Experimentar tecnologias adaptativas, como leitores de tela, pode fornecer insights valiosos sobre como melhorar a acessibilidade do seu aplicativo.

6. **Integração no Desenvolvimento**:
   - **Início Precoce**: Acessibilidade deve ser incorporada desde os estágios iniciais do desenvolvimento de software. Adaptar acessibilidade no final do processo é muito mais desafiador e oneroso.

7. **Suporte das Estruturas**:
   - **Suporte Interno**: Muitas estruturas de desenvolvimento da web oferecem suporte interno para recursos de acessibilidade. Aproveite as funcionalidades dessas estruturas para garantir conformidade com as práticas de acessibilidade.

8. **Testes de Acessibilidade**:
   - **Deslocamento para a Esquerda**: Implemente testes de acessibilidade desde os estágios iniciais, utilizando listas de verificação e ferramentas automatizadas como Codelyzer, Pa11y CI, Lighthouse, WAVE e axe-core. Isso ajuda a identificar e corrigir problemas de acessibilidade mais cedo no processo de desenvolvimento.

9. **Feedback com Usuários Reais**:
   - **Testes com Usuários**: Utilize serviços de teste de usuário que incluem pessoas com deficiências para obter feedback prático sobre a acessibilidade do seu aplicativo. Isso proporciona uma visão realista e prática sobre a acessibilidade e usabilidade do produto.

Esses pontos destacam a importância de adotar práticas inclusivas e acessíveis em todas as fases do desenvolvimento e como isso não apenas atende a requisitos legais, mas também melhora a experiência para todos os usuários.

