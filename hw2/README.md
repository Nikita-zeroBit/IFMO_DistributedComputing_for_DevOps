# Работа №2

Настроены два контейнера с MySQL (primary -> master и replica -> slave). Настроена репликация между ними.

Также был запущен линтер `ansible-lint` и исправлены ошибки.

Также исправлены все ошибки из работы №1.

Для запуска playbook используется:

```bash
ansible-playbook -i inventory.ini playbook2.yml
```

Тестирование проводилось на Ubuntu 24.02 LTS.
