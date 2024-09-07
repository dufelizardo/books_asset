# Capítulo 4

 ### **Testes Contínuos: Uma Prática Essencial para Feedback Rápido**

No cenário atual de desenvolvimento de software, a capacidade de receber feedback rápido e contínuo é crucial para manter a qualidade do aplicativo. Este capítulo explora como a prática de **Teste Contínuo (CT)** pode ser integrada ao processo de desenvolvimento, complementando as práticas de **Integração Contínua (CI)** e **Entrega Contínua (CD)**.

#### **Conceito de Teste Contínuo (CT)**

O Teste Contínuo é o processo de validar a qualidade de um aplicativo constantemente, utilizando tanto métodos manuais quanto automatizados, após cada mudança incremental no código. Esse processo garante que quaisquer desvios na qualidade sejam identificados e comunicados à equipe imediatamente, permitindo correções rápidas e eficientes.

### **Importância do Feedback Contínuo**

- **Detecção Precoce de Problemas**: Com o feedback contínuo, problemas são identificados logo após a introdução de uma mudança, tornando-os mais fáceis e baratos de corrigir.
- **Qualidade Sustentada**: Mantém a qualidade do aplicativo ao longo do ciclo de desenvolvimento, evitando que problemas menores se transformem em grandes defeitos.
- **Ciclos de Desenvolvimento Acelerados**: A integração contínua de feedback permite que a equipe desenvolva e entregue funcionalidades de forma mais rápida e confiável.

### **Integração Contínua (CI) e Entrega Contínua (CD)**

#### **Integração Contínua (CI)**

A CI é a prática de mesclar mudanças de código de vários desenvolvedores em um repositório compartilhado várias vezes ao dia, seguido pela execução de testes automatizados para garantir que essas mudanças não introduzam defeitos.

#### **Entrega Contínua (CD)**

A CD estende a CI, automatizando ainda mais a entrega do código em produção, garantindo que o software pode ser liberado de forma segura, rápida e sustentável a qualquer momento.

### **Configuração de um Processo de Teste Contínuo (CT)**

Para estabelecer um processo de CT eficaz, siga estas etapas:

1. **Configuração de um Servidor de CI**:
   - Escolha uma ferramenta de CI adequada, como Jenkins, Travis CI, CircleCI ou GitLab CI.
   - Configure o servidor de CI para monitorar o repositório de código-fonte e iniciar um build sempre que houver uma alteração no código.

2. **Integração de Testes Automatizados**:
   - Desenvolva uma suíte de testes abrangente, incluindo testes de unidade, integração, funcionalidade e desempenho.
   - Configure o servidor de CI para executar esses testes automaticamente após cada alteração no código.

3. **Automação de Deploy**:
   - Configure pipelines de deploy automatizados para ambientes de desenvolvimento, teste e produção.
   - Garanta que o processo de deploy seja seguro e possa ser revertido facilmente em caso de falhas.

4. **Monitoramento e Alertas**:
   - Implemente ferramentas de monitoramento para rastrear a saúde do aplicativo e a infraestrutura.
   - Configure alertas para notificar a equipe imediatamente em caso de falhas nos testes ou problemas de desempenho.

### **Métricas de Desempenho**

O sucesso de um processo de CI/CD/CT pode ser medido pelas seguintes métricas:

- **Tempo de Espera**: Tempo médio entre o início do desenvolvimento de uma funcionalidade e sua disponibilização em produção.
- **Frequência de Implantação**: Frequência com que novas versões do software são liberadas para produção.
- **Tempo Médio de Restauração**: Tempo médio necessário para restaurar o serviço após uma falha em produção.
- **Porcentagem de Falhas**: Proporção de deploys que resultam em falhas ou necessitam de correção imediata.

### **Exercício Prático: Configurando um Servidor de CI**

1. **Instalação do Jenkins**:
   - Instale o Jenkins em um servidor dedicado.
   - Configure o Jenkins para monitorar o repositório de código-fonte.

2. **Criação de um Pipeline de CI/CD**:
   - Defina um pipeline no Jenkins para compilar o código, executar testes e realizar deploys automatizados.
   - Integre ferramentas de teste, como JUnit, Selenium, e Gatling para testes de unidade, funcionalidade e desempenho, respectivamente.

3. **Automatização de Testes**:
   - Configure o Jenkins para executar a suíte de testes completa após cada commit no repositório.
   - Defina alertas para notificar a equipe em caso de falhas nos testes.

### **Conclusão**

O Teste Contínuo, quando combinado com Integração Contínua e Entrega Contínua, transforma a maneira como equipes de desenvolvimento entregam software, proporcionando ciclos de feedback rápidos e melhorando a qualidade do produto final. Implementar essas práticas pode parecer desafiador inicialmente, mas os benefícios em termos de qualidade, velocidade e confiabilidade do software fazem o esforço valer a pena.

### Blocos de Construção: Entendendo CI/CD/CT

Para estabelecer uma base sólida na habilidade de Teste Contínuo (CT), é essencial compreender a terminologia e o processo geral de Integração Contínua (CI), Entrega Contínua (CD) e o próprio Teste Contínuo (CT). Vamos explorar esses conceitos, começando pela Integração Contínua (CI).

### Introdução à Integração Contínua (CI)

#### Definição e Princípios

**Martin Fowler**, um influente autor e cientista-chefe da ThoughtWorks, descreve a integração contínua como "uma prática de desenvolvimento de software em que os membros de uma equipe integram seu trabalho com frequência, geralmente cada pessoa se integra pelo menos diariamente - levando a várias integrações por dia". O objetivo principal da CI é identificar e resolver problemas de integração o mais cedo possível no ciclo de desenvolvimento.

#### Benefícios da Integração Contínua

Para ilustrar os benefícios da CI, vamos considerar o seguinte exemplo:

**Exemplo Prático: Allie e Bob**

Allie e Bob são dois desenvolvedores trabalhando em funcionalidades diferentes de um aplicativo: Allie está desenvolvendo a funcionalidade de login e Bob está desenvolvendo a página inicial. Eles trabalham independentemente e ao final do primeiro dia, ambos completaram suas tarefas locais, mas sem integração. No dia seguinte, encontram problemas ao tentar integrar suas funcionalidades.

**Problemas Sem CI:**
- **Integração Tardia:** O código de Allie e Bob só se integra no dia seguinte, resultando em um aplicativo parcialmente funcional.
- **Testes Duplicados:** Eles podem precisar testar novamente após a integração.
- **Atrasos e Reescritas:** Problemas de integração podem ser mais complexos de resolver após acumulação de mudanças, potencialmente necessitando reescritas significativas.

**Solução Com CI:**
- **Integração Frequente:** Allie e Bob compartilham e integram seu trabalho ao longo do dia.
- **Detecção Precoce de Problemas:** Problemas de integração são identificados e resolvidos rapidamente.
- **Ciclos de Feedback Rápidos:** O aplicativo é continuamente testável e utilizável, facilitando um desenvolvimento mais ágil e responsivo.

### Processo Geral de CI/CD/CT

#### CI (Integração Contínua)

1. **Commit Frequente:** Desenvolvedores fazem commits frequentes de pequenas alterações.
2. **Build Automatizado:** Cada commit aciona um build automatizado.
3. **Testes Automatizados:** O build inclui execução de testes automatizados.
4. **Feedback Imediato:** Resultados de build e testes são fornecidos imediatamente à equipe.

#### CD (Entrega Contínua)

1. **Deploy Automatizado:** Código aprovado nos testes de CI é preparado para deploy.
2. **Ambientes Automatizados:** Deploy é realizado automaticamente em ambientes de teste, staging e produção.
3. **Verificação Contínua:** A equipe pode liberar software a qualquer momento com confiança.

#### CT (Teste Contínuo)

1. **Validação Contínua:** Testes são executados continuamente após cada alteração.
2. **Alertas de Qualidade:** Desvios na qualidade são detectados e comunicados imediatamente.
3. **Correção Imediata:** Problemas são corrigidos rapidamente enquanto ainda são pequenos e gerenciáveis.

### Princípios Fundamentais e Etiqueta de CI

Para que a prática de CI seja eficaz, alguns princípios e etiquetas devem ser seguidos pela equipe:

1. **Commits Frequentes e Pequenos:** Evitar grandes lotes de alterações, que são mais difíceis de integrar.
2. **Build e Testes Automatizados:** Automatizar o máximo possível para garantir consistência e rapidez.
3. **Ambiente Compartilhado:** Trabalhar em um ambiente de desenvolvimento integrado para facilitar a detecção precoce de conflitos.
4. **Feedback Imediato:** Resolver problemas imediatamente após a detecção.
5. **Comunicação Clara:** Manter uma comunicação eficaz dentro da equipe para coordenar integrações e resolver conflitos.

### Conclusão

A Integração Contínua (CI) é um dos blocos de construção fundamentais para práticas eficazes de Teste Contínuo (CT) e Entrega Contínua (CD). Adotando a CI, equipes de desenvolvimento podem reduzir significativamente os riscos de integração, melhorar a qualidade do código, e acelerar o ciclo de desenvolvimento. A compreensão e implementação desses princípios permitirão que sua equipe se beneficie de ciclos de feedback rápidos e contínuos, essencial para a manutenção da qualidade e eficiência no desenvolvimento de software.

### O Processo de CI/CT/CD

Para compreender completamente o impacto dos processos contínuos de integração (CI), teste (CT) e entrega (CD), é necessário examinar detalhadamente seus componentes e como eles se conectam para formar um pipeline de entrega contínua.

#### Componentes Fundamentais do Processo CI/CT

1. **Sistema de Controle de Versão (VCS):**
   - Armazena toda a base de código do aplicativo.
   - Serve como repositório central para que todos os membros da equipe possam extrair a versão mais recente do código e integrar seu trabalho continuamente.
   - Exemplos: Git, SVN.

2. **Testes Automatizados:**
   - Incluem testes funcionais e multifuncionais que validam o aplicativo.
   - Garantem que cada alteração no código não introduza falhas ou quebras na funcionalidade existente.

3. **Servidor de CI:**
   - Executa automaticamente os testes automatizados na versão mais recente do código do aplicativo para cada alteração.
   - Exemplos: Jenkins, GoCD.

4. **Infraestrutura de Hospedagem:**
   - Hospeda o servidor de CI e o aplicativo.
   - Pode incluir serviços na nuvem, servidores dedicados, entre outros.

#### Fluxo de Trabalho de CI/CT

1. **Commit de Alterações:**
   - O desenvolvedor finaliza uma pequena parte da funcionalidade e envia suas alterações para o sistema de controle de versão (VCS).
   - O VCS rastreia todas as alterações enviadas a ele.

2. **Disparo de Pipeline de CI:**
   - Cada novo commit aciona um pipeline no servidor de CI.
   - Este pipeline é composto de várias etapas sequenciais, começando pela etapa de build e teste.

3. **Build e Testes:**
   - O código do aplicativo é totalmente construído.
   - Testes automatizados são executados, incluindo testes funcionais, de integração e de qualidade (desempenho, segurança, etc.).

4. **Feedback Imediato:**
   - Os resultados dos testes são retornados ao desenvolvedor.
   - Se todos os testes passarem, as novas alterações são consideradas totalmente integradas.
   - Caso ocorram falhas, o desenvolvedor responsável corrige os problemas rapidamente.

5. **Correções e Reversões:**
   - Problemas encontrados são corrigidos e um novo commit é feito.
   - Em alguns casos, as alterações podem ser revertidas do VCS para evitar que outras pessoas puxem código com problemas.

#### Benefícios do VCS

1. **Histórico de Versões:**
   - Mantém um histórico completo de todas as alterações de código, facilitando a análise de causa raiz de problemas.

2. **Rollback:**
   - Permite reverter para versões anteriores do código quando necessário.

3. **Rastreabilidade:**
   - Alterações podem ser vinculadas a histórias de usuário ou cartões de defeito, fornecendo contexto e facilitando a compreensão da evolução do código.

4. **Branches e Merges:**
   - Permite a criação de branches para desenvolvimento de funcionalidades, que podem ser integradas à base principal posteriormente.

#### Integração Contínua e Testes Contínuos em Ação

1. **Commit Frequente e Pequeno:**
   - Desenvolvedores fazem commits frequentes de pequenas alterações.

2. **Pipeline de CI:**
   - Cada commit aciona um pipeline de CI que inclui build e testes automatizados.

3. **Testes em Camadas:**
   - Testes em micro e macro níveis são executados para garantir a integridade do código.

4. **Correção Rápida de Bugs:**
   - Problemas detectados são corrigidos imediatamente, mantendo a estabilidade do código.

#### Entrega Contínua (CD)

1. **Deploy Automatizado:**
   - Código aprovado nos testes de CI é preparado para deploy automático.

2. **Pipelines de Deploy:**
   - Stages configurados no servidor de CI para realizar deploys automatizados para ambientes de teste, staging e produção.

3. **Produção Pronta:**
   - A aplicação está sempre pronta para ser lançada em produção, permitindo lançamentos ágeis conforme a demanda do negócio.

#### Entrega Contínua vs. Implantação Contínua

- **Entrega Contínua (Continuous Delivery):**
  - Preparação contínua do aplicativo para produção com opção de deploy automatizado.
  - Permite que a equipe faça deploys a qualquer momento com um clique.

- **Implantação Contínua (Continuous Deployment):**
  - Cada commit aprovado é automaticamente implantado em produção.
  - Adequado para cenários onde as alterações precisam estar disponíveis para os usuários finais imediatamente.

### Conclusão

A combinação dos processos de Integração Contínua (CI), Teste Contínuo (CT) e Entrega Contínua (CD) forma uma base robusta para desenvolvimento ágil e eficiente de software. Com esses processos em prática, as equipes podem minimizar riscos, garantir alta qualidade de código, e responder rapidamente às necessidades do mercado, lançando novas funcionalidades de forma confiável e ágil.

### Princípios e Etiqueta

Para que os processos de CI/CD/CT sejam eficazes, é essencial que todos os membros da equipe sigam um conjunto de princípios e etiqueta bem definidos. Estes princípios ajudam a garantir que o trabalho colaborativo, incluindo testes automatizados, código do aplicativo e configurações de infraestrutura, seja realizado de maneira eficiente e harmoniosa. Abaixo estão alguns dos princípios e etiqueta mínimos que uma equipe deve respeitar para ter sucesso:

#### Princípios

1. **Faça commits de código frequentes:**
   - Os membros da equipe devem fazer commits frequentes e enviar as alterações para o VCS assim que terminarem cada pequena parte da funcionalidade. Isso garante que o código seja testado e disponibilizado para que outros possam construir em cima dele.

2. **Sempre faça commit de código auto-testado:**
   - Cada novo pedaço de código comprometido deve ser acompanhado por testes automatizados no mesmo commit. Isso é conhecido como código auto-testado. Por exemplo, ao enviar a funcionalidade de login, Allie incluiu os testes de login, garantindo que seu commit não fosse interrompido quando Bob enviou seu código posteriormente.

3. **Adira ao Teste de Certificação de Integração Contínua:**
   - Cada membro da equipe deve garantir que seu commit passe pelo processo de teste contínuo antes de seguir para a próxima tarefa. Se os testes falharem, eles precisam ser corrigidos imediatamente. Segundo o Teste de Certificação de Integração Contínua de Martin Fowler, uma fase de build e teste quebrada deve ser reparada em até 10 minutos. Se isso não for possível, o commit quebrado deve ser revertido, mantendo o código estável.

4. **Não ignore/comente os testes falhando:**
   - Para fazer a fase de build e teste passar, os membros da equipe não devem comentar ou ignorar os testes que estão falhando. Embora as razões para não fazer isso sejam óbvias, é uma prática comum.

5. **Não envie código para um build quebrado:**
   - A equipe não deve enviar seu código quando a fase de build e teste está quebrada. Enviar trabalho em cima de uma base de código já quebrada resultará em mais falhas nos testes, aumentando a carga de trabalho da equipe ao tentar identificar quais alterações quebraram o build originalmente.

6. **Assuma a responsabilidade por todas as falhas:**
   - Quando os testes falham em uma área do código em que alguém não trabalhou, mas falha por causa de suas mudanças, a responsabilidade de corrigir o build ainda é dessa pessoa. Se necessário, ela pode se juntar a alguém que tenha o conhecimento necessário para corrigir o problema, mas, fundamentalmente, o problema deve ser resolvido antes de seguir para a próxima tarefa. Isso é essencial para evitar que a responsabilidade de corrigir testes falhos seja transferida, causando atrasos na resolução dos problemas.

#### Práticas Adicionais

Algumas equipes adotam práticas mais rigorosas para seu próprio benefício, tais como:

- **Execução de todos os testes locais:**
  - Garantir que todos os testes de micro e macro nível passem nas máquinas locais antes de enviar o commit para o VCS.

- **Cobertura de código:**
  - Falhar a fase de build e teste se um commit não atender ao limite de cobertura de código estabelecido.

- **Comunicação do status do commit:**
  - Publicar o status do commit (passou ou falhou) com o nome do indivíduo que fez o commit em um canal de comunicação como o Slack.

- **Alerta para builds quebrados:**
  - Tocar música alta na área da equipe sempre que um build for quebrado a partir de um monitor de CI dedicado.

Como tester na equipe, é importante monitorar o status dos testes no CI e garantir que sejam corrigidos em tempo hábil. Fundamentalmente, todas essas medidas são adotadas para aprimorar as práticas da equipe em torno dos processos de CI/CT e, assim, obter os benefícios desejados.

#### Conclusão

Os princípios e etiqueta estabelecidos para CI/CD/CT não são apenas diretrizes, mas práticas essenciais para o sucesso da equipe. Empoderar a equipe com o conhecimento do "como" e do "porquê" por trás desses processos é crucial para garantir que todos estejam alinhados e comprometidos com a entrega contínua de software de alta qualidade.

### Estratégia de Teste Contínuo

Agora que os processos e princípios foram discutidos, o próximo passo é criar e aplicar estratégias personalizadas para atender às necessidades específicas do seu projeto. O processo de teste contínuo pode ser otimizado com ciclos de feedback independentes, acelerando o tempo de resposta para a equipe. Aqui estão algumas estratégias e práticas recomendadas para implementar um processo de teste contínuo eficaz.

#### Estrutura com Dois Estágios de Feedback

**Processo de Feedback em Dois Ciclos:**
1. **Primeiro Ciclo: Construção e Testes de Nível Micro**
   - Este ciclo combina a compilação do aplicativo com a execução de testes de nível micro (unidade, integração, contrato). Este estágio é chamado de estágio de construção e teste.
   - **Objetivo:** Obter feedback rápido sobre o commit, garantindo que o código funcione como esperado antes de proceder.
   - **Duração:** Deve ser rápido o suficiente para ser concluído em alguns minutos, conforme recomendado por Jez Humble e David Farley. Se demorar mais, a equipe deve buscar formas de melhorar a eficiência, como paralelização dos testes.

2. **Segundo Ciclo: Testes de Nível Macro**
   - Este ciclo inclui a implantação dos artefatos do aplicativo em um ambiente de CI e a execução de testes de nível macro (API, interface do usuário, ponta a ponta).
   - **Objetivo:** Validar o comportamento funcional e global do aplicativo após a implantação.
   - **Duração:** Este estágio pode levar mais tempo devido à implantação e à execução de testes mais complexos, mas deve ser mantido abaixo de uma hora para feedback eficiente.

#### Estratégia de Feedback Multifuncional

**Estendendo o Processo para Feedback Multifuncional:**
- **Testes Automatizados de Desempenho, Segurança e Acessibilidade:** 
  - Podem ser integrados nos loops de feedback existentes ou configurados em estágios separados após o estágio de teste de aceitação.
- **Objetivo:** Garantir feedback rápido e contínuo sobre a qualidade geral do aplicativo, abrangendo aspectos funcionais e não funcionais.

#### Integração Contínua vs. Teste Contínuo

**Integração Contínua (CI):**
- **Definição:** O processo de integração contínua termina com o estágio de construção e teste. Um commit é considerado integrado quando passa pelos testes de nível micro.
- **Foco:** Validação inicial do código.

**Teste Contínuo (CT):**
- **Definição:** Envolve a validação do comportamento global do aplicativo, incluindo aspectos funcionais e multifuncionais, para cada commit.
- **Foco:** Garantir que o aplicativo esteja pronto para entrega contínua, incluindo testes exploratórios manuais e automação dos cenários encontrados.

#### Estratégias para Testes de Fumaça e Regressão Noturna

**Teste de Fumaça:**
- **Definição:** Conjunto de testes que cobre o fluxo de ponta a ponta de cada funcionalidade do aplicativo, proporcionando um sinal rápido sobre o status de cada commit.
- **Objetivo:** Garantir a prontidão para implantação de autoatendimento após a conclusão do teste de fumaça.

**Regressão Noturna:**
- **Definição:** Execução de todo o conjunto de testes uma vez por dia fora do horário de trabalho, verificando a base de código mais recente.
- **Objetivo:** Garantir a integridade contínua do código e priorizar a correção de defeitos no dia seguinte.

#### Considerações Finais

- **Divisão dos Testes:**
  - **Teste de Fumaça:** Ideal para testes de nível macro e multifuncionais que devem ser rápidos.
  - **Regressão Noturna:** Ideal para testes mais abrangentes e detalhados que podem levar mais tempo.
- **Execução de Testes de Nível Micro:** Deve ser sempre realizada como parte do estágio de construção e teste.
- **Escolha dos Testes:** A equipe deve ter cuidado ao selecionar os testes para cada estágio, priorizando a execução de testes críticos no teste de fumaça e mantendo os testes mais extensos para a regressão noturna.

Implementar essas estratégias ajudará a manter um processo de teste contínuo eficiente, proporcionando feedback rápido e garantindo a qualidade do software de maneira consistente. À medida que o projeto cresce, essas práticas ajudarão a manter a agilidade e a eficácia da equipe de desenvolvimento.

### Benefícios do Processo de Teste Contínuo

Implementar um processo de teste contínuo traz uma série de benefícios valiosos para a equipe de desenvolvimento e para a qualidade do software produzido. Vamos explorar cada um desses benefícios conforme ilustrado na Figura 4-6.

#### 1. Objetivos Comuns de Qualidade
- **Descrição:** Seguir um processo de teste contínuo garante que todos os membros da equipe estejam alinhados com os mesmos objetivos de qualidade, tanto em aspectos funcionais quanto multifuncionais.
- **Benefício:** Facilita a construção de um software de alta qualidade, pois todos os membros da equipe sabem exatamente o que é esperado e trabalham juntos para atingir essas metas.

#### 2. Detecção Precoce de Defeitos
- **Descrição:** Cada membro da equipe recebe feedback imediato sobre seus commits, permitindo que problemas sejam corrigidos rapidamente enquanto o contexto do código ainda está fresco.
- **Benefício:** Reduz a quantidade de retrabalho e os custos associados a correções tardias, aumentando a eficiência e a produtividade da equipe.

#### 3. Pronto para Entregar
- **Descrição:** Como o código é testado continuamente, o aplicativo está sempre em um estado pronto para implantação em qualquer ambiente.
- **Benefício:** Aumenta a agilidade da equipe, permitindo respostas rápidas às mudanças e requisitos dos clientes, além de facilitar lançamentos frequentes e consistentes.

#### 4. Colaboração Aprimorada
- **Descrição:** A colaboração entre membros da equipe é facilitada, especialmente em equipes distribuídas, pois o compartilhamento contínuo de trabalho e feedback imediato torna mais fácil identificar e resolver problemas.
- **Benefício:** Promove um ambiente de trabalho mais harmonioso e eficiente, evitando conflitos e mal-entendidos sobre a origem dos problemas no código.

#### 5. Propriedade de Entrega Combinada
- **Descrição:** A responsabilidade pela entrega de código de qualidade é distribuída entre todos os membros da equipe, em vez de recair apenas sobre a equipe de testes ou desenvolvedores seniores.
- **Benefício:** Cria um senso de responsabilidade compartilhada e empoderamento entre todos os membros da equipe, resultando em maior compromisso com a qualidade do software.

### Reflexões Finais

Os benefícios do processo de teste contínuo são significativos e abrangem diversos aspectos do desenvolvimento de software:

- **Qualidade:** Garantia de alta qualidade em cada commit, tanto em termos de funcionalidade quanto de características não funcionais como desempenho e segurança.
- **Eficiência:** Redução de retrabalho e aumento da produtividade graças à detecção precoce de defeitos e ao feedback contínuo.
- **Agilidade:** Preparação constante para implantações, permitindo respostas rápidas às demandas do mercado.
- **Colaboração:** Melhoria na comunicação e no trabalho em equipe, especialmente em ambientes de trabalho distribuídos.
- **Responsabilidade:** Distribuição equitativa da responsabilidade pela qualidade do software, incentivando um senso de propriedade e compromisso em todos os membros da equipe.

Ao adotar e implementar um processo de teste contínuo, você não só melhora a qualidade do produto final, mas também fortalece a coesão e a eficácia da sua equipe de desenvolvimento. Esses benefícios, uma vez alcançados, proporcionam uma base sólida para o crescimento e a inovação contínua na entrega de software.

### Exercício: Configuração do Processo de Teste Contínuo

#### Parte 1: Configurando o Git e Enviando Testes Automatizados para o GitHub

##### Passo 1: Instalar e Configurar o Git
1. **Instale o Git**:
    - **macOS**:
      ```bash
      $ brew install git
      ```
    - **Linux**:
      ```bash
      $ sudo apt-get install git
      ```
    - **Windows**:
      - Baixe o instalador do [site oficial do Git](https://git-scm.com/download/win) e siga as instruções de instalação.

2. **Verifique a instalação**:
    ```bash
    $ git --version
    ```

3. **Configurar nome de usuário e email**:
    ```bash
    $ git config --global user.name "seuNomeDeUsuário"
    $ git config --global user.email "seuEmail"
    ```

4. **Verifique a configuração**:
    ```bash
    $ git config --global --list
    ```

##### Passo 2: Configurar Repositório Git no GitHub
1. **Crie uma conta no GitHub** se ainda não tiver uma.
2. **Crie um novo repositório**:
    - Navegue até *Seus repositórios → Novo*.
    - Nomeie o repositório como `FunctionalTests` e torne-o público.
    - Anote a URL do repositório: `https://github.com/<seuNomeDeUsuário>/FunctionalTests.git`.

##### Passo 3: Inicializar o Repositório Git Local
1. **Navegue até a pasta do projeto**:
    ```bash
    $ cd /path/to/project/
    ```

2. **Inicialize o repositório Git**:
    ```bash
    $ git init
    ```

##### Passo 4: Adicionar e Enviar Código para o GitHub
1. **Adicionar arquivos ao repositório local**:
    ```bash
    $ git add .
    ```

2. **Fazer commit das alterações**:
    ```bash
    $ git commit -m "Adding functional tests"
    ```

3. **Adicionar repositório remoto**:
    ```bash
    $ git remote add origin https://github.com/<seuNomeDeUsuário>/FunctionalTests.git
    ```

4. **Enviar código para o GitHub**:
    ```bash
    $ git push -u origin master
    ```

    **Nota:** Você precisará fornecer seu nome de usuário do GitHub e o token de acesso pessoal ao fazer o push. Gere um token de acesso pessoal nas configurações da sua conta do GitHub, se necessário.

#### Parte 2: Configuração do Jenkins para Testes Automatizados

##### Passo 1: Instalar e Configurar o Jenkins
1. **Instalar Jenkins**:
    - **macOS**:
      ```bash
      $ brew install jenkins-lts
      $ brew services start jenkins-lts
      ```
    - **Windows/Linux**:
      - Baixe o instalador do [site oficial do Jenkins](https://www.jenkins.io/download/) e siga as instruções de instalação.

2. **Acesse a interface web do Jenkins**:
    - Abra um navegador e navegue para `http://localhost:8080/`.

3. **Configuração inicial do Jenkins**:
    - **Desbloquear o Jenkins**: Use a senha de administrador gerada durante a instalação.
    - **Instalar plugins recomendados**.
    - **Criar conta de administrador**.

##### Passo 2: Configurar Variáveis de Ambiente no Jenkins
1. **Navegue para Gerenciar Jenkins → Configuração da Ferramenta Global**.
2. **Configurar JAVA_HOME e MAVEN_HOME**:
    - Encontre os locais dos respectivos diretórios usando o comando `mvn -v`.

##### Passo 3: Criar e Configurar um Pipeline no Jenkins
1. **Criar novo item**:
    - No painel esquerdo, selecione *Novo Item*.
    - Nomeie o pipeline como `Testes Funcionais` e escolha *Projeto de estilo livre*.

2. **Configurar o pipeline**:
    - **Geral**: Adicione uma descrição e selecione *Projeto GitHub*. Insira a URL do repositório sem a extensão `.git`.
    - **Gerenciamento de Código-Fonte**: Selecione *Git* e insira a URL do repositório com a extensão `.git`.
    - **Gatilhos de Build**: Escolha *Poll SCM* e configure para sondar o repositório a cada 2 minutos: `H/2 * * * *`.
    - **Compilar**: Selecione *Invocar destinos Maven de nível superior* e configure para executar `mvn test`.
    - **Ações de Pós-Compilação**: Configure conforme necessário para sua estratégia de teste.

3. **Salvar e Executar o Pipeline**:
    - Volte para a visualização do painel, selecione o pipeline criado e clique em *Criar agora*.

4. **Verificar execução**:
    - Observe a execução do comando `mvn test` e verifique os resultados na pasta *Área de Trabalho* do Jenkins.

#### Conclusão
Parabéns! Você configurou com sucesso um processo de teste contínuo, integrando Git e Jenkins para executar testes automatizados sempre que houver alterações no código. Esta prática garante alta qualidade de software, colaboração eficiente e rápida detecção de defeitos.

## As Quatro Métricas Principais de Desempenho (4KM) de Equipes de Software

### Introdução às 4KM

A equipe de Pesquisa e Avaliação de DevOps (DORA) do Google identificou quatro métricas principais para avaliar o desempenho de equipes de desenvolvimento de software: **Tempo de Espera**, **Frequência de Implantação**, **Tempo Médio para Restaurar** e **Alterar Percentagem de Falha**. Essas métricas são fundamentais para medir o ritmo de entrega e a estabilidade dos lançamentos de software, ajudando a classificar as equipes como de desempenho baixo, médio, alto ou elite.

### As Quatro Métricas

1. **Tempo de Espera (Lead Time)**
   - **Definição:** Tempo gasto desde que o código é confirmado até que esteja pronto para implantação de produção.
   - **Importância:** Mede a rapidez com que uma equipe pode entregar valor aos usuários finais. Menor tempo de espera significa maior agilidade e resposta às mudanças.

2. **Frequência de Implantação (Deployment Frequency)**
   - **Definição:** Frequência com que o software é implantado na produção ou em uma loja de aplicativos.
   - **Importância:** Reflete a capacidade da equipe de fornecer atualizações contínuas e frequentes aos usuários, permitindo feedback rápido e iteração constante.

3. **Tempo Médio para Restaurar (MTTR - Mean Time to Restore)**
   - **Definição:** Tempo necessário para restaurar o serviço após uma interrupção ou falha.
   - **Importância:** Indica a eficiência da equipe em lidar com problemas e garantir a continuidade do serviço. Menor MTTR significa maior resiliência e capacidade de recuperação.

4. **Alterar Percentagem de Falha (Change Failure Rate)**
   - **Definição:** Percentual de alterações que resultam em falhas na produção, exigindo correções subsequentes, como reversões ou hotfixes.
   - **Importância:** Avalia a qualidade das implantações e a estabilidade das mudanças. Menor taxa de falha significa maior confiança na entrega contínua e menor risco de interrupções.

### Metas de uma Equipe de Elite

De acordo com a pesquisa DORA, as metas para uma equipe de elite são:

| Métrica                     | Alvo                                   |
|-----------------------------|----------------------------------------|
| Frequência de Implantação   | Sob demanda (várias implantações por dia) |
| Tempo de Espera             | Menos de um dia                        |
| Tempo Médio para Restaurar  | Menos de uma hora                      |
| Alterar Percentagem de Falha| 0–15%                                  |

### Benefícios de Seguir as 4KM

- **Ritmo de Entrega:** Com tempos de espera curtos e alta frequência de implantação, a equipe pode agregar valor aos clientes de forma contínua e rápida.
- **Estabilidade:** O monitoramento do tempo médio para restaurar e da taxa de falha de alterações garante que a agilidade não comprometa a qualidade e a estabilidade do software.
- **Desempenho Organizacional:** Equipes de elite, conforme definido pela DORA, contribuem significativamente para o sucesso organizacional, melhorando lucro, preço das ações e retenção de clientes.

### Aplicação Prática

Para alcançar esses objetivos, é essencial implementar práticas rigorosas de CI/CD/CT, automatizando testes nas camadas corretas do aplicativo e garantindo que o feedback seja rápido e contínuo. A aderência a essas práticas possibilitará:

- **Entregas sob demanda** com testes automatizados que garantem qualidade e prontidão para implantação em poucas horas.
- **Manutenção da qualidade** com uma taxa de falha de alteração dentro da faixa recomendada de 0 a 15%.

### Conclusão

Seguir os princípios de CI/CD/CT e monitorar as quatro métricas principais da DORA ajudará sua equipe a se qualificar como uma equipe de elite, impulsionando o sucesso da organização e, consequentemente, proporcionando melhores condições para os funcionários.

**Referências:**
1. Humble, Jez, Gene Kim, e Nicole Forsgren. "Accelerate." IT Revolution Press.
2. Kim, Gene, Jez Humble, Patrick Debois, e John Willis. "The DevOps Handbook." IT Revolution Press.
3. Documentação do Jenkins para mais detalhes sobre pipelines e automação.

## Exercício: Implementação de CI/CD/CT com Git e Jenkins

### Passo 1: Configuração do Git

1. **Criação de uma Conta no GitHub**
   - Se você ainda não tem, crie uma conta no [GitHub](https://github.com).
   - Crie um novo repositório navegando para "Seus repositórios" → "Novo".
   - Nomeie o repositório, por exemplo, "FunctionalTests", e torne-o público.
   - Anote a URL do repositório (https://github.com/<seu_nome_de_usuário>/FunctionalTests.git).

2. **Instalação e Configuração do Git**
   - Instale o Git:
     - **macOS:** `$ brew install git`
     - **Linux:** `$ sudo apt-get install git`
     - **Windows:** Baixe o instalador do [site oficial do Git](https://git-scm.com/download/win).
   - Verifique a instalação:
     ```sh
     $ git --version
     ```
   - Configure seu nome de usuário e e-mail:
     ```sh
     $ git config --global user.name "seuNomeDeUsuario"
     $ git config --global user.email "seuEmail"
     ```
   - Verifique a configuração:
     ```sh
     $ git config --global --list
     ```

### Passo 2: Fluxo de Trabalho com Git

1. **Inicialize o Repositório Git**
   ```sh
   $ cd /caminho/para/projeto/
   $ git init
   ```

2. **Adicione os Arquivos ao Repositório**
   ```sh
   $ git add .
   ```

3. **Faça o Commit das Alterações**
   ```sh
   $ git commit -m "Adicionando testes funcionais"
   ```

4. **Adicione o Repositório Remoto**
   ```sh
   $ git remote add origin https://github.com/<seu_nome_de_usuário>/FunctionalTests.git
   ```

5. **Faça o Push para o Repositório Remoto**
   - Gere um token de acesso pessoal no GitHub em Configurações → Configurações do desenvolvedor → "Tokens de acesso pessoal".
   - Use o token para autenticação quando solicitado:
     ```sh
     $ git push -u origin master
     ```

### Passo 3: Configuração do Jenkins

1. **Instalação do Jenkins**
   - **macOS:** 
     ```sh
     $ brew install jenkins-lts
     $ brew services start jenkins-lts
     ```
   - **Linux e Windows:** Siga o procedimento de instalação padrão do [site oficial do Jenkins](https://jenkins.io/download/).

2. **Configuração Inicial do Jenkins**
   - Acesse a interface web do Jenkins em `http://localhost:8080/`.
   - Desbloqueie o Jenkins usando a senha gerada durante a instalação.
   - Baixe e instale os plugins recomendados.
   - Crie uma conta de administrador.

3. **Configuração das Ferramentas Globais no Jenkins**
   - Vá para "Gerenciar Jenkins" → "Configuração da Ferramenta Global".
   - Configure `JAVA_HOME` e `MAVEN_HOME` com base nos locais de instalação.

### Passo 4: Criação e Configuração de um Pipeline no Jenkins

1. **Criar um Novo Pipeline**
   - No painel do Jenkins, selecione "Novo Item".
   - Nomeie o pipeline (por exemplo, "Testes Funcionais") e escolha "Projeto de estilo livre".

2. **Configuração do Pipeline**
   - Na guia Geral, adicione uma descrição do pipeline.
   - Selecione "Projeto GitHub" e insira a URL do repositório (sem a extensão .git).
   - Na guia Gerenciamento de Código-Fonte, selecione Git e insira a URL do repositório (com a extensão .git).
   - Na guia Gatilhos de Build, selecione "Poll SCM" e configure para sondar a cada 2 minutos: `H/2 * * * *`.
   - Na guia Compilar, selecione "Invocar destinos Maven de nível superior" e insira `test` no campo Metas.
   - Na guia Ações de Pós-Compilação, configure ações conforme necessário para encadeamento de pipelines.

3. **Executar o Pipeline**
   - No painel do Jenkins, clique no nome do pipeline e selecione "Criar agora".
   - O Jenkins clonará o repositório e executará os testes automatizados.

### Quatro Métricas Principais (4KM) da DORA

As quatro métricas principais identificadas pela equipe DORA são:

1. **Tempo de Espera (Lead Time)**
   - Tempo desde que o código é confirmado até estar pronto para produção.

2. **Frequência de Implantação (Deployment Frequency)**
   - Frequência de implantações na produção.

3. **Tempo Médio para Restaurar (MTTR - Mean Time to Restore)**
   - Tempo necessário para restaurar após uma falha.

4. **Alterar Percentagem de Falha (Change Failure Rate)**
   - Percentual de mudanças que causam falhas na produção.

### Metas de uma Equipe de Elite

| Métrica                       | Alvo                                    |
|-------------------------------|-----------------------------------------|
| Frequência de Implantação     | Sob demanda (várias implantações por dia)|
| Tempo de Espera               | Menos de um dia                         |
| Tempo Médio para Restaurar    | Menos de uma hora                       |
| Alterar Percentagem de Falha  | 0–15%                                   |

Seguir práticas rigorosas de CI/CD/CT ajudará sua equipe a atingir essas metas e ser classificada como uma equipe de elite, contribuindo significativamente para o sucesso da organização.

