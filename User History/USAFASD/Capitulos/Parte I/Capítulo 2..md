# Capítulo 2.

**Escrevendo histórias**

Neste capítulo, voltamos nossa atenção para escrever histórias eficazes. Para criar boas histórias, nos concentramos em seis atributos cruciais. Uma boa história é:

- **Independente**
- **Negociável**
- **Valiosa para usuários ou clientes**
- **Estimável**
- **Pequena**
- **Testável**

Bill Wake, autor de *Extreme Programming Explored* e *Refactoring Workbook*, sugeriu o acrônimo INVEST para esses seis atributos (Wake 2003a).

### Independente

Tanto quanto possível, deve-se evitar a introdução de dependências entre as histórias. Dependências entre histórias levam a problemas de priorização e planejamento. Por exemplo, se uma história de alta prioridade depende de uma história de baixa prioridade, a priorização fica comprometida. Além disso, estimar histórias com dependências pode ser muito mais difícil.

#### Exemplo de histórias dependentes:

1. Uma empresa pode pagar por um anúncio de emprego com um cartão Visa.
2. Uma empresa pode pagar por um anúncio de emprego com um MasterCard.
3. Uma empresa pode pagar por um anúncio de emprego com um cartão American Express.

Se os desenvolvedores estimam que levará três dias para oferecer suporte ao primeiro tipo de cartão de crédito e um dia para os demais, fica difícil decidir qual história deve receber a estimativa de três dias.

#### Soluções para dependências:

1. Combine as histórias dependentes em uma história maior, mas independente.
2. Encontre uma maneira diferente de dividir as histórias.

### Negociável

As histórias são negociáveis e não são contratos rígidos ou requisitos. Elas são descrições curtas da funcionalidade, cujos detalhes devem ser negociados entre o cliente e a equipe de desenvolvimento. Cartões de história servem como lembretes para conversas e não precisam incluir todos os detalhes desde o início. Detalhes adicionais podem ser anotados conforme forem discutidos.

### Valiosa para compradores ou usuários

Embora muitas histórias sejam valorizadas pelos usuários, algumas podem ser valorizadas principalmente pelos compradores. Por exemplo, uma história sobre conformidade com auditorias pode ser mais importante para um comprador que precisa garantir que o software atenda aos requisitos regulatórios.

Evite histórias que são valorizadas apenas pelos desenvolvedores, como aquelas que se concentram exclusivamente na tecnologia sem evidenciar os benefícios para os clientes ou usuários.

### Estimável

Os desenvolvedores devem ser capazes de estimar o tamanho ou o tempo necessário para transformar uma história em código funcional. As histórias podem não ser estimáveis por três razões principais:

1. Falta de conhecimento de domínio.
2. Falta de conhecimento técnico.
3. A história é muito grande.

Se os desenvolvedores não entendem uma história, devem discutir com o cliente. Quando a tecnologia é desconhecida, pode ser necessário um "spike" para aprender o suficiente para fazer a estimativa.

### Pequeno

Histórias grandes são difíceis de trabalhar e estimar. Histórias pequenas demais também não são ideais, pois o tempo de escrita e estimativa pode exceder o tempo de desenvolvimento. É importante encontrar um tamanho adequado para as histórias.

#### Dividindo histórias:

Épicos, que são histórias grandes, podem ser desagregados em histórias menores e mais gerenciáveis. 

### Testável

As histórias devem ser escritas de forma a serem testáveis. Testes bem-sucedidos provam que uma história foi desenvolvida conforme esperado. Histórias não testáveis, como aquelas que dizem "um usuário deve achar o software fácil de usar", devem ser reformuladas para incluir critérios de teste específicos e mensuráveis.

---

### Exemplos práticos e orientações

1. **História com detalhes suficientes:**
   - **Cartão de História 2.1:**
     - História: "Uma empresa pode pagar por um anúncio de emprego com um cartão de crédito."
     - Notas: "Aceitar Visa, MasterCard e American Express. Perguntar sobre Discover."
   - Este cartão fornece a quantidade certa de informações para iniciar a conversa entre desenvolvedores e clientes.

2. **História com detalhes excessivos:**
   - **Cartão de História 2.2:**
     - História: "Uma empresa pode pagar por um anúncio de emprego com um cartão de crédito."
     - Notas: "Coletar mês e ano de expiração do cartão. O sistema pode armazenar o número do cartão para uso futuro."
   - Este cartão inclui detalhes demais, o que pode levar a mal-entendidos sobre a precisão da estimativa e a necessidade de discussão.

3. **História testável reformulada:**
   - Original: "Um usuário nunca deve esperar muito para que qualquer tela apareça."
   - Reformulada: "Novas telas aparecem em dois segundos em 95% dos casos."
   - Esta reformulação permite a criação de testes automatizados para verificar o desempenho.

Seguindo essas diretrizes, você garantirá que as histórias sejam claras, negociáveis, estimáveis e, acima de tudo, valiosas e testáveis, facilitando o desenvolvimento ágil e a entrega de valor contínuo aos clientes e usuários.