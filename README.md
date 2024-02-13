# lab_1
## Задача 00
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/d24d0548-cd5c-4984-be56-0a9d4698ec0d)
### **Задача 0. Алгоритм**
1. Высчитываем расстояние с помощью функции def rast(x,y)
2. Создаем словарь distances
3. for key in sites.keys():
    distances[key] = {}
   Эта строка создает пустой словарь distances с ключом key для каждого ключа в словаре sites. То есть, для каждого ключа в словаре sites создается элемент в словаре distances.
4. for y in sites.keys():
   if y!=key:
   Эта строка создает вложенный цикл, который перебирает все ключи в словаре sites, исключая текущий ключ key. Это нужно для того, чтобы не вычислять расстояние между ключом и самим собой.
5. distances[key][y] = rast(sites[key], sites[y]) Эта строка вычисляет расстояние между значениями x и y, связанными с ключами key и у в словаре sites с помощью функции rast, и сохраняет результат в словаре distances в виде distances[key][y], представляя расстояние между ключом key и ключом y в словаре sites.
6. Выводим результат

#### Задача 01
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/65728253-d6c0-400f-920a-8dd2232df935)
##### **Задача 1. Алгоритм**
1. Находим площадь круга с помощью функции def krug(r)
2. Выводим результат
3. Определяем находятся ли точки point_1 и point_2 внутри круга
4. Выводим результат

##### Задача 02
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/27601928-9b33-4776-8c30-1c871f5e9b1e)
#### **Задача 02. Алгоритм**
1. Расставляем знаки, как показано в условии
2. Выводим результат

###### Задача 03
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/f6951ea7-2256-468c-83bd-9bbb47e5d4d6)
###### **Задача 03. Алгоритм**
1. С помощью срезов выводим сразу результат

##### Задача 04
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/f68f33d8-3a20-480d-8116-a8ec5a138228)
#### **Задача 04. Алгоритм**
1. Создаем список
2. Создаем список с приблизительным ростом
3. В переменной father_height находим рост с помощью перебора списка и функции next, которая возвращает элемент, который соответствует условию
4. В переменной total_height вычисляем общий рост семьи с помощью функции sum
5. Выводим результат

#### Задача 05
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/63cea275-262b-4576-9e00-32f0fce0b648)
#### ** Задача 05. Алгоритм **
1. С помощью функции insert добавляем медведя в список с помощью индекса
2. Добавляем птиц в список с помощью суммирования
3. С помощью remove удаляем из списка слона
4. Выводим на консоль в какой клетке сидит лев и жаворонок, но добавляем +1, чтобы было понятно другим людям

#### Задача 06
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/3c642c95-993b-4e98-bda2-a9faba8f6046)
#### ** Задача 06. Алгоритм **
1. В переменных mus1, mus2, mus3 с помощью функции next возвращает элемент, который соответствует условию
2. В переменной s суммируем значения и выводим их с помощью округления (round)
3. В переменной totaltime складываем время звучания песен
4. В переменной othersongstime складываем 3 другие песни
5. Выводим

#### Задача 07
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/f091bc16-c79c-43c7-90f5-313657aa398d)
#### ** Задача 07. Алгоритм **
1. С помощью срезов выводим значение

#### Задача 08
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/486978e4-59ce-4e6e-811c-701c42d5e8ac)

#### ** Задача 08. Алгоритм **
1. Создаем множество цветоы с помощью функции set
2. С помощью union объединяем множества и выводим их
3. С помощью intersection находим пересечения в множествах и выводим их
4. С помощью difference возвращаем множество, полученное из различий между множествами

#### Задача 09
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/19b388f4-3f4e-4a13-abc5-625d988eaf2b)

## ** Задача 09. Алгоритм **
1. В переменной sweets создаем словарь цен на продукты
2. Выводим их

#### Задача 10
**Результат**
![image](https://github.com/eternsss/lab_1/assets/155539142/82a0a4a7-d06a-43a5-ab56-33dbb63b75a6)

## ** Задача 10. Алгоритм **
1. В lamp_cost и др находим общую сумму товаров
2. В lamp_quantity находим общее количество товаров
3. Выводим результат










