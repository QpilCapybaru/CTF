# Калькулятор  
Сайт - codeby.games  
Категория - Web  
Решение:  
![image](https://github.com/QpilCapybaru/CTF/assets/162910881/411b6480-273f-447c-b848-af0f17529d35)  
Сам сайт с калькулятором выглядит следующим образом  
![image](https://github.com/QpilCapybaru/CTF/assets/162910881/d367a621-3e6d-40c2-944d-40c3f38d345c)  
Как нам сказано там стоит защита WAF  
При рандомных записях калькулятор не присылал ответ или писал  
![image](https://github.com/QpilCapybaru/CTF/assets/162910881/de30ac87-3d1a-4bbe-9896-27b51c608bf0)  
Поэтому решил использовать обфускацию использовать обратные кавычки  
![image](https://github.com/QpilCapybaru/CTF/assets/162910881/b8b04a57-43e3-4b5f-b859-6beee9096419)  
Это сработало и можо увидеть единственный файл "index.php" который сразу был открыт с помощью команды cat (кот)  
![image](https://github.com/QpilCapybaru/CTF/assets/162910881/f203f9fb-9ddf-4b3e-b2c7-a02a53a9db16)  
Флаг был изменен!  
Задание было успешно выполнено.
