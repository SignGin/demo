### Demo Server

π Django

## μ€ν λ°©λ²

1. νμ΄μ¬ μ€μΉ

2. cmdμμ venv ν΄λκ° μλ μμΉλ‘ μ΄λ

3. venv\Scripts\activate.bat μ€ν(κ°μνκ²½ μ€ν)

4. python manage.py runserver μ€ν(μλ² μ€ν)

5. μλ¬λλ€λ©΄ mysql νμΈ
   μ¬μ©μμ΄λ¦: root
   ν¨μ€μλ: rootuser

μ¬μ©μμ΄λ¦κ³Ό ν¨μ€μλμ λΆλ§μ΄λΌλ©΄ settings.pyνμΌμμ μμ 

---

1. νμ΄μ¬ μ€μΉ

2. cmdμμ server ν΄λλ‘ μ΄λ

3. python -m venv venv μ€νν΄μ κ°μνκ²½ μμ±

4. venv\Scripts\activate.bat μλ ₯(κ°μνκ²½ μ€ν)

5. κ°μνκ²½μ νμ λͺ¨λ μ€μΉ

pip install django
pip install djangorestframework
pip install mysqlclient

6. python manage.py runserver μλ ₯(μλ² μ€ν)

p. μλ¬λλ€λ©΄ mysql νμΈ
μ¬μ©μμ΄λ¦: root
ν¨μ€μλ: rootuser

μ¬μ©μμ΄λ¦κ³Ό ν¨μ€μλμ λΆλ§μ΄λΌλ©΄ settings.pyνμΌμμ μμ 

---

demo λΌλ μ΄λ¦μ μ€ν€λ§ μμ±
python manage.py migrate μ€ν
κ·Έ νμ python manage.py runserverλ‘ μλ² μμ
