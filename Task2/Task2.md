В данном решение было реализовано hpa по cpu вместо memory. Утилизация CPU при увеличении нагрузки растет быстрее, поэтому был выбран этот вариант

Начальное состояние:
![initial_state.png](initial_state.png)

Добавление второй реплики под нагрузкой:
![add_second_replica_dashboard.png](add_second_replica_dashboard.png)
![add_second_replica.png](add_second_replica.png)

Добавление третье реплики под нагрузкой:
![add_third_replica_dashboard.png](add_third_replica_dashboard.png)
![add_third_replica.png](add_third_replica.png)

Удаление реплик и возврат к одной при отсутствии нагрузки:
![back_to_one_replica_dashboard.png](back_to_one_replica_dashboard.png)
![back_to_one_replica.png](back_to_one_replica.png)
