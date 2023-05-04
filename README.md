# lp1-poo-parte04
Práticas sugeridas para o conteúdo de POO (parte 04)

Prática 11.01. 
Crie uma hierarquia de classes para representar os diferentes tipos de funcionários de um escritório que tem os seguintes cargos: gerente, assistente, vendedor. Escreva uma classe base abstrata chamada Funcionario que declara um método abstrato:
Assinatura do método: public double calculaSalario()
Esta classe também deve definir os seguintes atributos: nome (tipo String), matricula (tipo String) e salario_base (tipo double). Use encapsulamento e forneça um construtor que recebe os valores correspondentes a serem armazenados nos respectivos atributos. Esta classe abstrata deverá ser estendida pelas outras classes representativas dos tipos de funcionários, portanto devem ser escritas as classes Gerente, Assistente e Vendedor. Em cada classe deve-se sobrescrever o método calculaSalario de forma que cálculo do salário é feito assim: O gerente recebe duas vezes o salário_base, o assistente recebe o salário_base e o vendedor recebe o salário_base mais uma comissão definida no construtor de sua classe. 
Crie uma classe Teste com um método main que cria um objeto de cada tipo e depois calcula a folha salarial dos três funcionários e imprime o valor total. 

Prática 11.02.
Fazer um programa para ler os dados de N contribuintes (N fornecido pelo usuário), os quais podem ser pessoa física ou pessoa jurídica, e depois mostrar o valor do imposto pago por cada um, bem como o total de imposto arrecadado. 
Os dados de pessoa física são: nome, renda anual e gastos com saúde. Os dados de pessoa jurídica são nome, renda anual e número de funcionários. As regras para cálculo de imposto são as seguintes: 
Pessoa física: pessoas cuja renda foi abaixo de 20000.00 pagam 15% de imposto. Pessoas com renda de 20000.00 em diante pagam 25% de imposto. Se a pessoa teve gastos com saúde, 50% destes gastos são abatidos no imposto. Exemplo: uma pessoa cuja renda foi 50000.00 e teve 2000.00 em gastos com saúde, o imposto fica: (50000 * 25%) - (2000 * 50%) = 11500.00 
Pessoa jurídica: pessoas jurídicas pagam 16% de imposto. Porém, se a empresa possuir mais de 10 funcionários, ela paga 14% de imposto. Exemplo: uma empresa cuja renda foi 400000.00 e possui 25 funcionários, o imposto fica: 400000 * 14% = 56000.00


