Задачей данной курсовой работы являлся анализ csv файлов для расчёта частоты встречаемости транзакций
![image](https://github.com/user-attachments/assets/974be123-efe2-4adb-800b-d049677c2284)


Загружаемые csv файлы:
gender_train
![image](https://github.com/user-attachments/assets/b1307ffb-cc8d-45e3-a7ac-a8f378bb111c)

tr_mcc_codes
![image](https://github.com/user-attachments/assets/110648c5-ac87-402f-a5c1-4f56abb9a863)

tr_types
![image](https://github.com/user-attachments/assets/c8ca38b5-ff38-4057-beb7-02a2bcdcfa8c)

transactions
![image](https://github.com/user-attachments/assets/4617436d-74fc-45bb-930f-affdeae6e6ed)

Полученные данные загружаются в БД, затем для них рассчитывается встречаемость. При запросе самых часто встречаемых транзакций производится сортировка с помощью Comparator

![image](https://github.com/user-attachments/assets/1e8dc4d1-69e9-4ef3-a0f5-cc0549b18972)
![image](https://github.com/user-attachments/assets/a7f1de98-804e-45c0-a1a7-b78d3724c1c3)

