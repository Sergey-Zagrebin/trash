https://medium.com/nuances-of-programming/%D0%B7%D0%BD%D0%B0%D0%BA%D0%BE%D0%BC%D1%81%D1%82%D0%B2%D0%BE-%D1%81-git-%D0%B8-github-%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B4%D0%BB%D1%8F-%D0%BD%D0%B0%D1%87%D0%B8%D0%BD%D0%B0%D1%8E%D1%89%D0%B8%D1%85-9090c4c07f87
ВСЁ НАХОДЯСЬ В ТЕРМИНАЛЕ ОТКРЫТОМ ИЗ ПАПКИ С ПРОЕКТОМ

//СКОПИРОВАТЬ РЕПОЗИТОРИЙ
git clone {ссылка}

//СКОПИРОВАТЬ ИЗМЕНЕНИЯ
git pull

//ДОБАВИТЬ ФАЙЛЫ ДЛЯ ОТПРАВКИ (* ЗНАЧИТ ВСЕ)  
git add *

//ОТПРАВИТЬ С ОПИСАНИЕМ
git commit -m "Описание"

//ОТПРАВИТЬ В РЕПОЗИТОРИЙ
git push

//СОЗДАТЬ ВЕТКУ С ОТДЕЛЬНОЙ ВЕРСИЕЙ (MASTER ГЛАВНАЯ ВЕРСИЯ)
git checkout -b {ветка}

//ОТКРЫТЬ ВЕТКУ ДЛЯ ИЗМЕНЕНИЙ
git checkout {ветка}

//СДЕЛАТЬ ВЕТКУ ГЛАВНОЙ
git merge {ветка}

deg=0
coef=0
print("Deg and Coef")
en={}

while(True):
	deg, coef = map(int, input().split())
	if (deg==-1):
		break;
	en[deg]=coef

for i in range(en.keys()[0]):
	

