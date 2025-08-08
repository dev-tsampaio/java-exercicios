💻 Sistema de Cálculo de Pagamentos — Herança e Polimorfismo em Java
Este projeto é um exemplo prático dos conceitos de Herança e Polimorfismo em Java.
O programa simula o cálculo de pagamentos para funcionários, permitindo registrar tanto funcionários comuns quanto terceirizados, com regras específicas para cada tipo.

📌 Funcionalidades
Cadastro de vários funcionários.

Identificação de funcionários terceirizados.

Cálculo de pagamento baseado em:

Horas trabalhadas.

Valor por hora.

Taxa adicional (apenas para terceirizados, com acréscimo de 10% sobre a taxa).

Exibição de um histórico de pagamentos formatado.

🛠 Conceitos aplicados
Herança:
A classe OutsourcedEmployee herda de Employee, aproveitando atributos e métodos comuns.

Polimorfismo:
O método payment() é sobrescrito (@Override) em OutsourcedEmployee para incluir a lógica da taxa adicional, demonstrando como diferentes classes podem ter comportamentos específicos para o mesmo método.

Encapsulamento:
Uso de atributos privados com métodos getters e setters.

Listas e Laços:
Armazenamento de funcionários em uma lista (List<Employee>) e iteração para processamento.

