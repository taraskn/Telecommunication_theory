# Звіт із лабораторної роботи №3
### із дисципліни Теоретичні основи телекомунікацій
### Тема: Методи обходу та модифікації графів.

### Виконав: студент групи ТР-35 Княжик Т.Р.
### Прийняв: викладач Бугиль Б.А.

## Виконання роботи

#### 1. Побудовано неорієнтований граф G = {8,12}:

![image](https://user-images.githubusercontent.com/79790283/118717187-67897480-b82e-11eb-8c6e-982453bf2539.png)

##### 1. Побудувано дерево за алгоритмом обходу в ширину (BFS) для вершини 1:

![image](https://user-images.githubusercontent.com/79790283/118717327-9acc0380-b82e-11eb-818b-4f723b11d973.png)

##### для вершини 5:

![image](https://user-images.githubusercontent.com/79790283/118717379-ac151000-b82e-11eb-9d25-569ca20f346c.png)

##### 2. Топології дерев побудованих з різних кореневих вершин будуть різними. Це пояснюється тим, що алгоритм обходить не всі ребра графу, відповідно якщо у графі є вершини які мають більше трьох суміжних вершин, то тополігї дерев побудованих з різних кореневих вершин будуть різними.

##### 3. Побудувано дерево за алгоритмом обходу в глибину (DFS); з вершини 1:

![image](https://user-images.githubusercontent.com/79790283/118717503-d36bdd00-b82e-11eb-91b5-1145c77532ac.png)

##### з вершини 6:

![image](https://user-images.githubusercontent.com/79790283/118717559-e4b4e980-b82e-11eb-9590-647dfedfe0b1.png)

##### 4. Топології будуть різними. Це можна пояснити тим, що на кожному кроці алгоритм випадково знаходить лише одну вершину( випадково вибираючи одну з тих, що до неї під'єднані).

#### 2. Побудувано випадковий орієнтований граф G={6,10}:

![image](https://user-images.githubusercontent.com/79790283/118717643-fe563100-b82e-11eb-98eb-7898286a0b39.png)

##### 1. Побудувано дерево за алгоритмом обходу в ширину (BFS), починаючи з третьої вершини:

![image](https://user-images.githubusercontent.com/79790283/118717707-0f06a700-b82f-11eb-9350-3efcb479f462.png)

##### Порядок обходу: 3 ->2->5->1->6->4

##### 2. Якщо починати обхід графу за алгоритмом обходу в ширину з третьої вершини, то останньою буде знайдена вершина № 4.

##### 3. Граф не містить циклів Ейлера та Гамільтона.

##### 4. Для виявлення останньої вершини потрібно три хвилі.

##### 5. Дерево за алгоритмом обходу в глибину (DFS):

![image](https://user-images.githubusercontent.com/79790283/118717857-44ab9000-b82f-11eb-8486-7fcb7d36cc34.png)

#### 3. Побудувати дерево шляхів рангом r=4 для випадкового графа G={6,9}.

##### Граф G:

![image](https://user-images.githubusercontent.com/79790283/118717951-60169b00-b82f-11eb-8fd6-67e1cdbc1ee2.png)

##### дерево шляхів:

![image](https://user-images.githubusercontent.com/79790283/118718156-994f0b00-b82f-11eb-9333-edc7fe5c71de.png)

#### 4. Побудувати мінімальне зв’язне дерево для графа G. Вказати його вагу.

##### Граф G:

![image](https://user-images.githubusercontent.com/79790283/118718328-c7344f80-b82f-11eb-9a5a-965daca40c96.png)

##### Мінімальне зв'язне дерево:

![image](https://user-images.githubusercontent.com/79790283/118718402-df0bd380-b82f-11eb-9a82-b3f0543565da.png)

##### Вага мінімального зв'язного дерева = 29.

## Висновок

#### Отримано навички застосовування алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева.
