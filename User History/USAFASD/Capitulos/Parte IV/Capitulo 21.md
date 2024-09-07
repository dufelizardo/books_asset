# Capitulo 21

Vamos organizar os testes de aceitação para as histórias descritas, dividindo-os em categorias conforme as funcionalidades e prioridades definidas.

### **Testes de Aceitação por História**

#### **Pesquisa (Histórias 21.1 e 21.2)**

**História 21.1: Pesquisa Básica**
1. Pesquisar uma palavra conhecida por fazer parte de um título, mas improvável que seja um autor (por exemplo, "navegação").
2. Pesquisar uma palavra que provavelmente seja um autor, mas improvável que seja um título (por exemplo, "João").
3. Pesquisar uma palavra que provavelmente não esteja em nenhum dos dois (por exemplo, "Wookie").

**História 21.2: Pesquisa Avançada**
1. Usar valores para autor e título que correspondam a pelo menos um livro.
2. Usar valores para autor e título que não correspondam a nenhum livro.
3. Tentar uma pesquisa ISBN.

#### **Carrinho de Compras (Histórias 21.3, 21.4 e 21.5)**

**História 21.3: Adicionar ao Carrinho**
1. Colocar um livro esgotado no carrinho e verificar se o usuário é informado que o livro será enviado quando disponível.
2. Colocar um livro que ainda não foi publicado no carrinho e verificar se o usuário é informado que o livro será enviado quando disponível.
3. Colocar um livro que está em estoque no carrinho.
4. Adicionar uma segunda cópia de um livro ao carrinho e verificar se a contagem aumenta.

**História 21.5: Alterar Quantidade no Carrinho**
1. Alterar a quantidade de um livro de um para dez.
2. Alterar a quantidade de dez para um.
3. Remover um livro alterando a quantidade para zero.

**Observação**: A História 21.4 foi substituída por 21.5, e a alteração da quantidade para zero não necessita de uma história separada.

#### **Compra de Livros (História 21.6)**

**História 21.6: Finalização da Compra**
1. Inserir um endereço de cobrança e indicar que o endereço de entrega é o mesmo.
2. Inserir endereços de cobrança e entrega separados.
3. Testar com um estado e um código postal de outro estado e verificar se a inconsistência é detectada.
4. Verificar se o endereço de entrega é usado para o envio dos livros e não o endereço de cobrança.
5. Testar com um cartão Visa válido.
6. Testar com um MasterCard válido.
7. Testar com um cartão American Express (deve falhar).
8. Testar com um cartão Visa vencido.
9. Testar com um MasterCard acima do limite de crédito.
10. Testar com um Visa com números inválidos.
11. Testar com um Visa com dígitos transpostos.
12. Testar com um número de Visa completamente inválido.

#### **Contas de Usuário (Histórias 21.7, 21.8 e 21.9)**

**História 21.7: Criação de Conta**
1. Permitir que os usuários façam pedidos sem criar uma conta.
2. Criar uma conta, recuperá-la e verificar se as informações foram salvas.

**História 21.8: Edição de Informações da Conta**
1. Editar o número do cartão de crédito para um número inválido e verificar se o usuário é avisado.
2. Editar a data de expiração do cartão para uma data no passado e verificar se a alteração não é salva.
3. Alterar o número do cartão de crédito para um novo número válido e garantir que a alteração seja salva.
4. Alterar a data de expiração para uma data no futuro e garantir que a alteração seja salva.

**História 21.9: Edição de Endereço**
1. Alterar várias partes do endereço de entrega e verificar se as alterações foram salvas.
2. Alterar várias partes do endereço de cobrança e verificar se as alterações foram salvas.

#### **Administração (Histórias 21.10, 21.11 e 21.12)**

**História 21.10: Adicionar Livros**
1. Verificar se um administrador pode adicionar um livro ao site.
2. Verificar se um não-administrador não pode adicionar um livro.
3. Verificar se um livro só pode ser adicionado se todos os dados necessários estiverem presentes.

**História 21.11: Excluir Livros**
1. Verificar se um administrador pode excluir um livro.
2. Verificar se um não-administrador não pode excluir um livro.
3. Excluir um livro e verificar se os pedidos pendentes ainda serão enviados.

**História 21.12: Alterar Informações do Livro**
1. Verificar se itens como nome, autor, número de páginas podem ser alterados.
2. Verificar se o preço do livro pode ser alterado, mas se as alterações de preço não afetam os pedidos já feitos (mas não faturados e não enviados).

#### **Testes de Restrições (Histórias 21.13 e 21.14)**

**História 21.13: Banco de Dados**
1. Fazer um pedido e verificar se ele é armazenado no banco de dados de pedidos por telefone.

**História 21.14: Desempenho**
1. Testar com cinquenta usuários simulados realizando pesquisas e fazendo pedidos. Certificar-se de que nenhuma tela demore mais de quatro segundos para ser exibida e que nenhum pedido seja perdido.

#### **História Final (História 21.15)**

**História 21.15: Página de Recomendações**
1. Selecionar um tópico (por exemplo, navegação ou cruzeiro) e exibir as recomendações para esse tópico, garantindo que elas façam sentido.
2. Clicar em um item da lista para verificar se o navegador é direcionado para uma página de informações sobre esse livro.

### **Resumo**

Os testes de aceitação são essenciais para garantir que cada história atenda às expectativas e requisitos definidos. As descrições fornecidas ajudam a confirmar que o sistema atende às necessidades do cliente e oferece uma base sólida para validar a conclusão de cada funcionalidade.