# oplati_senler
1) В cmd прописать 
pip3 (или просто pip) install vk
pip3 install openpyxl
2) В файле my_token прописать токен сообщества. Заходим в сообщество -> управление -> работа с api -> ключи доступа
Создаем ключ и вставляем его в файл my_token.
3) Включаем Long Poll Api (на будущее) в том же разделе работа с api
4) В том же разделе заходим в CallBack api и копируем group_id (только номер)
5) Вставляем скопированное в файл oplati_script в переменную group_id
6) Данный скрипт работает исключительно при текущем оформлении листа оплат. Копируем таблицу оплат в (ctrl+A, ctrl+C) в созданные файл Оплаты.xslx (или же любое другое имя). P.S. имя файла надо будет поменять в скрипте
7) наверное, профит
