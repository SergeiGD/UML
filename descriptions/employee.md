# Описание класса Employee
Абстрактный класс, представляющий собой работника сервисного центра. От него наследуются [Manager](./manager.md "Класс Manager") и [Master](./master.md "Класс Master"). У всего сотрудников есть расписание, которое можно получить с помощью метода GetTimetable(page : int, count : int, filterA : EmployeeTimetable, filterB : EmployeeTimetable) : List<EmployeeTimetable>
