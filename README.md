![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=%D0%A3+%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D1%96%D0%B9+%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D1%96+%D0%BC%D0%B8%3A) 

+ Створено акаунт Google Cloud Platform

![](reg.jpg)

+ Створили новий проект під назвою "London Project" 

<p align="center">
  <img src="1.jpg">
</p>

+ Активували Compute Engine API та почали створювати віртуальну машину 

![](2.jpg)

+ Обрали необхідні нам параметри та створили віртуальну машину з назвою "super-instance"

![](3.jpg)

+ Також створимо таку ж віртуальну машину за допомогою Cloud Shell. Для цього відкриємо Cloud Shell та введемо наступну команду:

```
gcloud compute images list
```

У відповідь ми отримаємо всі образу ОС, але ми оберемо Debian 10 та запишемо наступну команду:

```
gcloud compute instances create red-instance --image-family=debian-10 --image-project=debian-cloud --machine-type=e2-micro
```
+ Далі потрібно ввести "n", а після того обрати необхідний регіон, який у нас під номером 87. Після введеня, побачимо наступні виводи консолей:

![](4.jpg)


![](5.jpg)


+ Тож, таким чином ми створили віртуальну машину за допомогою Cloud Shell, перевірити це можна на сторінці оновивши її

<p align="center">
  <img src="6.jpg">
</p>

+ На малюнку бачимо дві працюючі віртуальні машини. Перша була створена звичайним методом, а інша через Cloud Shell

+ Висновок

У лабораторній роботі було виконано створення віртуальної машини використовуючи звичний спосіб, просто роблячи його на сайті Google Cloud. Та було створено машину за допомогою Cloud Shell. У нас це вдалося, про що свідчить останній скріншот з лабораторної.

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=THE+END)