# Домашнее задание к занятию «Кеширование Redis/memcached»
## Косарев Д.О.

### Проблемы, которые решает кеширование:

1. **Высокая нагрузка на базу данных**  
   Кэш принимает на себя повторяющиеся запросы, снимая нагрузку с БД.

2. **Сложные и длительные запросы**  
   Результаты ресурсоемких операций сохраняются для повторного использования.

3. **Высокие задержки при обращении к внешним API**  
   Данные кэшируются локально, уменьшая зависимость от скорости внешних сервисов.

4. **Пиковые нагрузки на сервер**  
   Кэш снижает трафик, предотвращая перегрузку backend-систем.

5. **Высокая стоимость инфраструктуры**  
   Меньше запросов к БД = меньше необходимых ресурсов = экономия денег.

---

### Задание 2. Memcached  
**Статус Memcached:**
![Статус Memcached](https://raw.githubusercontent.com/daardima/sdb-homeworks-11-02.md/main/screenshots/mencached_status.png)

---

### Задание 3. Удаление по TTL в Memcached  
**TTL Memcached:**
![TTL Memcached](https://raw.githubusercontent.com/daardima/sdb-homeworks-11-02.md/main/screenshots/mencached_ttl.png)

---

### Задание 4. Запись данных в Redis  
**Работа с Redis:**
![Работа Redis](https://raw.githubusercontent.com/daardima/sdb-homeworks-11-02.md/main/screenshots/realis_work.png)
