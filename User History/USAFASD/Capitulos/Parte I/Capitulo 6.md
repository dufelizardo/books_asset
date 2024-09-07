# Capitulo 6

Esse texto detalha o papel crucial dos testes de aceitação no desenvolvimento ágil de software, especialmente no contexto de histórias de usuário. Vamos destacar alguns pontos-chave e práticas recomendadas com base nas informações fornecidas:

### **1. Papel dos Testes de Aceitação**
- **Documentar Detalhes**: Os testes de aceitação capturam detalhes das conversas entre clientes e desenvolvedores, garantindo que todos os aspectos da história de usuário sejam compreendidos e implementados corretamente.
- **Critérios de Aceitação**: Eles fornecem critérios claros para determinar se uma história está completa e implementada conforme o esperado.

### **2. Processo de Criação de Testes**
- **Escrita de Testes Antes da Codificação**: Idealmente, os testes de aceitação são escritos antes que a programação comece, para garantir que todos os aspectos da história sejam considerados. Isso ajuda a evitar omissões ou mal-entendidos.
- **Notas de Teste**: Durante a discussão da história, os detalhes dos testes são anotados no verso do cartão de história. Esses detalhes são depois transformados em testes formais.

### **3. Exemplo de Notas de Teste**
Para a história "Uma empresa pode pagar por um anúncio de emprego com um cartão de crédito":
- **Testar com Diferentes Cartões**: Visa, MasterCard, American Express (passar); Diner’s Club (reprovado).
- **Testar Casos de Cartões**: Bons, ruins, ausentes e vencidos.
- **Testar Valores de Compra**: Incluindo valores acima do limite do cartão.

### **4. Envolvimento do Cliente**
- **Responsabilidade do Cliente**: O cliente deve escrever e executar os testes de aceitação. Eles são responsáveis por garantir que os testes reflitam corretamente a intenção e os requisitos da história.
- **Colaboração**: O cliente pode trabalhar com desenvolvedores e testadores para criar e refinar testes.

### **5. Ferramentas para Automação de Testes**
- **FIT e FitNesse**: Essas ferramentas facilitam a escrita e execução de testes de aceitação em formatos de tabela, tornando o processo mais acessível e eficiente.

### **6. Tipos de Teste**
- **Funcional**: Verifica se a aplicação funciona conforme esperado.
- **Interface do Usuário**: Garante que todos os componentes da interface se comportam corretamente.
- **Usabilidade**: Avalia a facilidade de uso do aplicativo.
- **Desempenho e Stress**: Testa como o aplicativo se comporta sob diferentes cargas e estresses.

### **7. Testar para Bugs, Não Cobertura**
- **Enfoque na Qualidade**: Em projetos ágeis, o objetivo é encontrar e corrigir bugs, não atingir 100% de cobertura de código. O esforço de teste deve ser guiado pela experiência e conhecimento do sistema.

### **Resumo das Responsabilidades**
- **Desenvolvedor**:
  - Automatizar a execução de testes de aceitação, se necessário.
  - Pensar em testes de aceitação adicionais durante o desenvolvimento.
  - Realizar testes de unidade para cobrir casos de baixo nível.
- **Cliente**:
  - Escrever e executar os testes de aceitação.

Essa abordagem detalhada e colaborativa para testes de aceitação é fundamental para garantir que o software atenda às expectativas dos clientes e funcione corretamente em situações reais.