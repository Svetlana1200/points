﻿Игра "Точки"
Автор: Семенова Светлана
Требования
	Python версии не ниже 3.6
	PyQt версии 5 
Состав:
	Тесты: test_game.py
	Графическая версия: start.py, logic.py, gui.py, soket.py, rivals.py, cell.py
Пример запуска:
	./start.py
Управление:
	Esc - вывести результаты игры и завершить ее
	ЛКМ - поставить точку
Дополнительно:
	В Settings можно выбрать режим игры и размер поля
	В игре с ИИ в Records можно посмотреть рекорды для текущего размера поля, а также они появятся после завершения игры (в режиме H-H данной возможности нет)
	Для каждого размера поля создается свой .txt файл с рекордами 
	С помощью кнопки undo/redo в игре с ИИ можно отменять/повторять последние 5 ходов