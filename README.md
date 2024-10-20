# SOLID
SOLID - принципы объектно-ориентированного программирования, которые помогают разработчикам писать поддерживаемый и масщтабируемый код. 

S - Single Responsibility Principle - принцип единственной ответственности. 
O - Open/Closed Principle - принцип открытости / закрытости. 
L - Liskov Substitution Principle - принцип подстановки Барбары Лисков.
I - Interface Segregation Principle - принцип разделения интерфейса. 
D - Dependency Inversion Principle - принцип инверсии зависимостей. 

S - Single Responsibility Principle
Один класс решает одну задачу. 

O - Open / Closed Principle 
Программные сущности(классы, модули, функции и т.д.) должны быть открыты для расширения, но закрыты для модификации.
В этом помогут абстракции, интерфейсы, наследование. 

L - Liskov Substitution Principle
Производные классы должны дополнять, а не заменять свои базовые классы. 
Объекты базовых классов должны быть заменяемы объектами производных классов без изменения ожидаемого поведения программы. 

I - Interface Segregation Principle 
Клиенты не должны зависеть от интерфейсов, которые они не используют. 
Это значит, что нужно создавать только небольшие и узконаправленные интерфейсы, не перегруженные ненужными методами.

D - Dependency Inversion Principle
Модули верхнего уровня не должны зависеть от модулей нижнего уровня. Оба типа модулей должны зависеть от абстракций. 
Абстракции не должны зависеть от деталей, но детали должны зависеть от абстракций.
