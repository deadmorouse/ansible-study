###  Введение в Ansible
#### 1. Попробуйте запустить playbook на окружении из test.yml, зафиксируйте какое значение имеет факт some_fact для указанного хоста при выполнении playbook'a.  
![01-1](https://github.com/user-attachments/assets/cd495b8f-63fc-498c-9e75-0f70b8fd37dc)

#### 2. Найдите файл с переменными (group_vars) в котором задаётся найденное в первом пункте значение и поменяйте его на 'all default fact'.  
![01-2](https://github.com/user-attachments/assets/ff8ee4ff-0a87-4554-9ec5-1f8d50275752)

#### 3. Воспользуйтесь подготовленным (используется docker) или создайте собственное окружение для проведения дальнейших испытаний.  
![01-3](https://github.com/user-attachments/assets/621605fb-fba1-42bd-9e41-04f750e3b834)

#### 4. Проведите запуск playbook на окружении из prod.yml. Зафиксируйте полученные значения some_fact для каждого из managed host.  
![01-4](https://github.com/user-attachments/assets/c791c383-8889-4280-b7b4-b6772fb2eb66)

#### 5. Добавьте факты в group_vars каждой из групп хостов так, чтобы для some_fact получились следующие значения: для deb - 'deb default fact', для el - 'el default fact'.  
![01-5](https://github.com/user-attachments/assets/1798334c-20f1-4554-8d8f-b5241f41ccee)

#### 6. Повторите запуск playbook на окружении prod.yml. Убедитесь, что выдаются корректные значения для всех хостов.  

#### 7. При помощи ansible-vault зашифруйте факты в group_vars/deb и group_vars/el с паролем netology. 
![01-7](https://github.com/user-attachments/assets/4589b27d-8813-44b8-b01f-eba60adbf32a)


#### 8. Запустите playbook на окружении prod.yml. При запуске ansible должен запросить у вас пароль. Убедитесь в работоспособности.  
![01-8](https://github.com/user-attachments/assets/42c6b2f8-27e3-49a4-8639-6e9e0e2cb519)


#### 9. Посмотрите при помощи ansible-doc список плагинов для подключения. Выберите подходящий для работы на control node.  
![01-9](https://github.com/user-attachments/assets/f5c39339-4cf4-4fd0-b59b-24ec69cd3543)


#### 10. В prod.yml добавьте новую группу хостов с именем local, в ней разместите localhost с необходимым типом подключения.  
#### 11. Запустите playbook на окружении prod.yml. При запуске ansible должен запросить у вас пароль. Убедитесь что факты some_fact для каждого из хостов определены из верных group_vars.  
![01-11-1](https://github.com/user-attachments/assets/59feecb4-1d97-4d79-916f-d8a725655f23)  
![01-11-2](https://github.com/user-attachments/assets/0fe88f6e-9b16-4edc-862e-e9004ccc74d2)


