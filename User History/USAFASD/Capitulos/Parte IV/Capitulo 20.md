# Capitulo 20

Para criar um plano de lançamento, você precisará seguir os passos descritos para selecionar o comprimento das iterações, estimar a velocidade, priorizar as histórias e alocar histórias para as iterações. Vamos descrever o processo detalhadamente com base nas informações fornecidas.

### 1. Selecione um Comprimento de Iteração

A equipe decidiu usar iterações de duas semanas. Isso permitirá duas iterações antes do prazo de quatro semanas, o que é adequado para o lançamento.

### 2. Estime a Velocidade

Maria e Rafe estimam a velocidade baseando-se na seguinte lógica:
- Cada ponto da história é considerado um dia ideal de trabalho.
- Eles estimam que cada dia ideal levará entre dois e três dias reais para ser concluído.
- Com iterações de duas semanas (10 dias úteis) e dois programadores, há 20 dias úteis de trabalho por iteração.
- A velocidade estimada é conservadora, com uma faixa de 7 a 10 pontos de história por iteração. Para o planejamento, eles definem a velocidade como 8 pontos por iteração.

### 3. Priorize as Histórias

Lori classifica as histórias em quatro categorias:
- **Deve Ter**: Histórias essenciais para o lançamento.
- **Deveria Ter**: Histórias desejáveis, mas não essenciais.
- **Poderia Ter**: Histórias úteis, mas que podem ser adiadas.
- **Não Terá**: Histórias que não serão incluídas nesta versão.

Baseado nas histórias obrigatórias de Lori e nas prioridades, a equipe tem as seguintes informações:

**Histórias Obrigatórias para o Lançamento Inicial**:

| Número da História | Descrição                              | Estimativa |
|--------------------|----------------------------------------|------------|
| 19.1               | Pesquisa Básica                        | 1 ponto     |
| 19.3               | Avaliação de Livros                    | 2 pontos    |
| 19.4               | Revisão de Livros                      | 4 pontos    |
| 19.5               | Editar Informações de Conta (cartão de crédito) | 1/2 ponto |
| 19.6               | Editar Informações de Conta (endereço) | 1 ponto     |

**Total**: 8,5 pontos

**Histórias que Lori Adiciona (Deveria Ter)**:

| Número da História | Descrição                              | Estimativa |
|--------------------|----------------------------------------|------------|
| 19.7               | Encontrar Listas de Desejos de Outros Usuários | 2 pontos |
| 19.8               | Verificar Status de Pedido             | 1 ponto     |
| 19.9               | Alterar Pedido Não Enviado             | 2 pontos    |
| 19.10              | Aprovação/Rejeição de Avaliações (Admin) | 2 pontos    |

**Total**: 7 pontos

### 4. Alocar Histórias para as Iterações

**Iteração 1 (Primeiras duas semanas)**:
- **Histórias Obrigatórias**:
  - 19.1: Pesquisa Básica (1 ponto)
  - 19.3: Avaliação de Livros (2 pontos)
  - 19.4: Revisão de Livros (4 pontos)
  - 19.5: Editar Informações de Conta (cartão de crédito) (1/2 ponto)
  - 19.6: Editar Informações de Conta (endereço) (1 ponto)
  - **Total**: 8,5 pontos

**Histórias Adicionais (Deveria Ter)**:
  - 19.7: Encontrar Listas de Desejos de Outros Usuários (2 pontos)
  - 19.8: Verificar Status de Pedido (1 ponto)

**Total de Itens Planejados para Iteração 1**: 11,5 pontos (Possível ajuste se necessário).

**Iteração 2 (Segunda metade das duas semanas seguintes)**:
- **Histórias Remanescentes**:
  - 19.9: Alterar Pedido Não Enviado (2 pontos)
  - 19.10: Aprovação/Rejeição de Avaliações (Admin) (2 pontos)
  - **Total**: 4 pontos

### Plano de Lançamento Finalizado

A Tabela 20.3 mostrará o plano detalhado com as histórias alocadas para cada iteração, garantindo que o trabalho essencial seja concluído na primeira iteração, com a flexibilidade de ajustar o plano com base no progresso real.

O plano de lançamento finalizado deve ser comunicado a todos os stakeholders para garantir que todos estejam alinhados com os objetivos e cronograma.

**Observações**:
- Maria e Rafe farão o possível para concluir as histórias planejadas. 
- Se a primeira iteração for concluída mais rapidamente, algumas histórias da segunda iteração poderão ser movidas para a primeira.
- Se houver atraso, algumas histórias da primeira iteração serão movidas para a segunda.

Essa abordagem permite uma alocação eficiente dos recursos e uma adaptação dinâmica ao progresso do desenvolvimento, garantindo que as prioridades do cliente sejam atendidas dentro do prazo estipulado.