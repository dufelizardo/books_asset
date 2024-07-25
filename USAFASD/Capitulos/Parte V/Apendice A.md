# Apêndice A

### Visão Geral da Programação Extrema (XP)

#### Papéis

**Cliente XP**:
- **Responsabilidades**: Escrever histórias de usuários, priorizá-las e criar/executar testes para verificar se as histórias foram atendidas.
- **Perfil**: Pode ser um usuário final, gerente de produto, gerente de projeto ou analista de negócios. Em projetos com múltiplos clientes, um indivíduo pode ser designado como o principal ponto de contato.

**Programador XP**:
- **Responsabilidades**: Desenvolver o código, testar suas próprias alterações (com testes de unidade automatizados) e colaborar com outros programadores em pares.
- **Perfil**: Os programadores em XP compartilham responsabilidades, não há distinções rígidas entre funções como design, administração de banco de dados, etc.

**Treinador e Gerente de Projeto**:
- **Treinador**: Monitora a adoção das práticas XP e ajuda a equipe a se manter no caminho certo.
- **Gerente de Projeto**: Foca em remover obstáculos e proteger a equipe da burocracia. Às vezes, essas funções são combinadas em um único papel.

#### As Doze Práticas

1. **Pequenas Liberações**:
   - **Descrição**: Entregar funcionalidades completas e testadas em iterações curtas (1-3 semanas). A equipe deve entregar um código funcional ao final de cada iteração.
   
2. **O Jogo de Planejamento**:
   - **Descrição**: Processo colaborativo onde o cliente e os desenvolvedores estimam e priorizam histórias de usuários para as iterações. O planejamento é ajustado conforme o progresso e mudanças nas prioridades.

3. **Refatoração**:
   - **Descrição**: Melhoria contínua do código sem alterar seu comportamento externo. Refatoração é obrigatória sempre que o código for modificado.

4. **Teste**:
   - **Descrição**: Desenvolvimento orientado a testes, onde os testes são escritos antes do código. Inclui testes de unidade automatizados e testes de aceitação escritos pelos clientes.

5. **Programação em Pares**:
   - **Descrição**: Dois programadores trabalham juntos no mesmo computador, trocando frequentemente de papéis (um codifica, o outro observa e reflete).

6. **Ritmo Sustentável**:
   - **Descrição**: Manter um ritmo de trabalho que possa ser sustentado a longo prazo, normalmente com cerca de 6 horas de programação em pares por dia.

7. **Propriedade do Código da Equipe**:
   - **Descrição**: Todo código é de responsabilidade coletiva. Qualquer programador pode modificar qualquer parte do código, ajudado por um conjunto forte de testes.

8. **Padrões de Codificação**:
   - **Descrição**: Seguir regras e convenções para garantir a consistência e legibilidade do código, facilitando a colaboração e manutenção.

9. **Design Simples**:
   - **Descrição**: Implementar o design mais simples que atenda aos requisitos atuais. Evitar complexidade desnecessária e código duplicado.

10. **Metáfora**:
    - **Descrição**: Usar uma metáfora para descrever o sistema e orientar a equipe sobre como pensar e trabalhar no projeto.

11. **Integração Contínua**:
    - **Descrição**: Integrar e testar o código frequentemente (idealmente, várias vezes ao dia). Garantir que a integração e os testes ocorram continuamente para identificar problemas rapidamente.

12. **Cliente no Local**:
    - **Descrição**: O cliente deve estar presente e disponível para fornecer feedback contínuo, escrever histórias de usuários e definir testes de aceitação.

#### Valores do XP

1. **Comunicação**: A comunicação efetiva e, preferencialmente, face a face é fundamental. A comunicação escrita é menos desejável.
   
2. **Simplicidade**: Foco em resolver o problema atual da maneira mais simples possível, evitando sobrecarregar o sistema com funcionalidades futuras.

3. **Feedback**: Buscar feedback imediato através de testes, integração contínua e interação constante com o cliente.

4. **Coragem**: Ter coragem para refatorar, mudar o design, e enfrentar desafios sem uma arquitetura mestre detalhada.

#### Princípios do XP

1. **Feedback Rápido**: Obter e reagir ao feedback rapidamente para ajustar o desenvolvimento conforme necessário.
   
2. **Pressuposição de Simplicidade**: Optar por soluções simples e evitar complicações desnecessárias.

3. **Mudança Incremental**: Implementar mudanças em pequenas etapas para minimizar riscos e facilitar a adaptação.

4. **Abraçar a Mudança**: Aceitar e adaptar-se às mudanças de requisitos e feedback contínuo.

5. **Trabalho de Qualidade**: Garantir que o software esteja bem acabado e mantenha um alto padrão de qualidade desde o início.

### Resumo

Extreme Programming (XP) promove práticas e valores para desenvolvimento ágil, colaborativo e sustentável. As doze práticas, como pequenas liberações e programação em pares, visam melhorar a qualidade e a eficiência do desenvolvimento. Os valores de comunicação, simplicidade, feedback e coragem sustentam a filosofia do XP, enquanto princípios como feedback rápido e mudança incremental guiam o processo de desenvolvimento.