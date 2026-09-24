 Задания
1. Вывод текущей даты и времени.
2. Переменные разных типов (int, float64, string, bool).
3. Краткая форма объявления переменных (`:=`).
4. Арифметические операции с двумя целыми числами.
5. Функция для суммы и разности двух float64.
6. Среднее значение трёх чисел.
 Инструкция: откройте компилятьор: https://go.dev/play/
вставтье код для первого задания:
```
package main

import (
	"fmt"
	"time"
)

func main() {

	now := time.Now()
	fmt.Println("Текущая дата и время:", now.Format("02.01.2006 15:04:05"))
}
```
что получилось:
<img width="416" height="90" alt="image" src="https://github.com/user-attachments/assets/b3670c1a-7340-4377-845e-980a7da83013" />



вставтье код для второго задания:
```
package main

import "fmt"

func main() {
	var i int = 41
	var f float64 = 3.14
	var s string = "Привет, я учусть в ПГУТИ!"
	var b bool = true

	fmt.Println(i)
	fmt.Println(f)
	fmt.Println(s)
	fmt.Println(b)
}

```
что получилось: <img width="204" height="91" alt="image" src="https://github.com/user-attachments/assets/ae85611c-8094-4b6e-a113-c3775f3a9d65" />





вставтье код для третьего задания:
```
package main

import "fmt"

func main() {
	name := "Богдан"
	age := 20
	height := 1.72
	isStudent := true

	fmt.Println(name)
	fmt.Println(age)
	fmt.Println(height)
	fmt.Println(isStudent)
}
```
что получилось:<img width="91" height="97" alt="image" src="https://github.com/user-attachments/assets/07ac082d-b8fd-4d2d-bc26-6d3e7b5835c8" />




вставтье код для четвёртого задания:
```
package main

import "fmt"

func main() {
	a := 10
	b := 3

	fmt.Println(a + b)
	fmt.Println(a - b)
	fmt.Println(a * b)
	fmt.Println(a / b)
	fmt.Println(a % b)
}
```
что получилось:<img width="64" height="114" alt="image" src="https://github.com/user-attachments/assets/d445af56-2834-45af-81a9-f364dc49be94" />




вставтье код для пятого задания:
```
package main

import "fmt"

func Go(a float64, b float64) (float64, float64) {
	sum := a + b
	diff := a - b
	return sum, diff
}

func main() {
	x := 10.5
	y := 3.2

	sum, diff := Go(x, y)

	fmt.Println("Сумма:", sum)
	fmt.Println("Разность:", diff)
}

```
что получилось:<img width="148" height="70" alt="image" src="https://github.com/user-attachments/assets/64a4822f-b723-4f62-a069-6e86bc3ec116" />




вставтье код для шестого задания:

```
package main

import "fmt"

func main() {
	a := 4.0
	b := 8.0
	c := 12.0

	g := (a + b + c) / 3

	fmt.Println(g)
}
```
что получилось:<img width="65" height="59" alt="image" src="https://github.com/user-attachments/assets/80195ba8-a569-4c1e-9575-8ba56c165a26" />

