# Домашнее задание к работе 8 #
## Условие задачи ##
![](https://github.com/kiri4art/Lab8/blob/main/lab8task.png)
## 1. Алгоритм блок-схема ##
### Алгоритм ###
1. Начало
2. Инициализируем переменные ```n```, ```s``` = 1
3. Пригласить к вводу значения переменной ```n```
4. Создаем цикл с счетчиком ```i``` = 1, условием ```i``` <= ```n``` и модификацией ```i++```
5. В теле цикла проводим вычисления по формуле ```s``` = ```s``` * 1 - (1 / (2 * ```i``` ))
6. Выводим результат ```s``` на экран
7. Конец
### Блок-схема ###
![](https://github.com/kiri4art/Lab8/blob/main/lab8alg.png)
## 2. Реализация программы ##
```
#define _CRT_SECURE_NO_DEPRECATE
#include <stdio.h>
#include <locale.h>
#include <math.h>

int n;
float s = 1;

void main()
{
	system("chcp 1251");
	printf("Введите значение n:\n");
	scanf("%d", &n);
	for (int i = 1; i <= n; i++) s *= (1. - (1. / (2. * i)));
	printf("Результат: %.7f", s);
}
```
## 3. Результаты работы программы ##
![](https://github.com/kiri4art/Lab8/blob/main/lab8ans1.png)<br>
![](https://github.com/kiri4art/Lab8/blob/main/lab8ans2.png)<br>
Программа успешно прошла проверку
## 4. Информация о разработчике ##
Кириченко Артем, бИПТ-252
