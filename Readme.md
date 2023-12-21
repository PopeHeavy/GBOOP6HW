# Домашняя работа №6

## Григорьев А.В


### S - Single Responsibility Principle

Класс StudentView и TeacherView только одна ответственность -
выведение в консоль Учащихся и Учителей соотвественно 

### O - Open-Closed Principle

Класс User открыт для расширения, так как можно создать много 
новых классов расширяющих его функционал (Student и Teacher), но при этом закрыт для модификаций,
так как у него есть четко выверенная структура

### L - Liskov Substitution Principle



### I - Interface Segregation Principle

Интерфейсы связанные с классом User разделены по
своим специфическим функциям - UserController,
UserService, UserView - вместо того чтобы быть
сгрупированными в один большой интерфейс.

### D - Dependency Inversion Principle