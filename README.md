1. Продумайте структуру класса Кот. Какие поля и методы будут актуальны для приложения, которое является

а) информационной системой ветеринарной клиники

2. Добейтесь того, чтобы при выводе в консоль объекта типа Cat, выводилась его кличка, цвет и возраст (или другие параметры на ваше усмотрение).
3. Создайте множество, в котором будут храниться экземпляры класса Cat - HashSet<Cat>. Поместите в него некоторое количество объектов.
4. Создайте 2 или более котов с одинаковыми параметрами в полях. Поместите их во множество. Убедитесь, что все они сохранились во множество.

5. Создайте метод public boolean equals(Object o)
   Пропишите в нём логику сравнения котов по параметрам, хранимым в полях. То есть, метод должен возвращать true, только если значения во всех полях сравниваемых объектов равны.

6. Переопределите метод хэшкод, пусть возвращает айди животного.

7. Выведите снова содержимое множества из пункта 2, убедитесь, что дубликаты удалились.