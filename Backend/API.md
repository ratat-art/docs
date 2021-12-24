## market
Описывает все эндпоины, связанные с куплей-продажей лотов.
### addAuction
Аргументы:
* name
* description
* lots:
	* image: Image
	* opening_price: number > 0
	* increment: number > 0
	* buyout_price ?? -1: number >= opening_price + increment

### addProduct

## auth
### login
Аргументы:
- логин (короткое имя или email)
- пароль
Возвращает: Сессия
Ошибки:
- неверный логин или пароль
- отсутствуют аргументы

### startRegister
### refresh

## market
Описывает все эндпоины, связанные с куплей-продажей лотов.
### addAuction
Аргументы:
* name
* description
* lots:
	* image: Image
	* opening_price: number > 0
	* increment: number > 0
	* buyout_price ?? -1: number >= opening_price + increment

### addProduct