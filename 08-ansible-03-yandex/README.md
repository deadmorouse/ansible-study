# Домашнее задание к занятию 3 «Использование Ansible»

## Основная часть

5. Запустите `ansible-lint site.yml` и исправьте ошибки, если они есть.
![ansible-03-01](https://github.com/user-attachments/assets/c281a5e3-594f-4270-be2f-d9652353ad41)


6. Попробуйте запустить playbook на этом окружении с флагом `--check`.
![ansible-03-02](https://github.com/user-attachments/assets/c1a56629-b9dd-4197-b5bb-1063472ef779)  
![ansible-03-03](https://github.com/user-attachments/assets/fdfb7891-7663-4fdc-b113-5a68c5e23472)


7. Запустите playbook на `prod.yml` окружении с флагом `--diff`. Убедитесь, что изменения на системе произведены.
![ansible-03-04](https://github.com/user-attachments/assets/30c40b4a-fef2-4b2c-b376-41bb731d9eae)


8. Повторно запустите playbook с флагом `--diff` и убедитесь, что playbook идемпотентен.
![ansible-03-05](https://github.com/user-attachments/assets/8e20b1fd-445c-48bc-8b88-8c1c0a291ae5)
