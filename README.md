 # QA
<hr>
<a href="#bash"><img src="https://img.shields.io/badge/Homework-BASH-brightgreen" /></a>
<a href="#github"><img src="https://img.shields.io/badge/Homework-GITHUB-brightgreen" /></a>
<a href="#postman"><img src="https://img.shields.io/badge/Homework-POSTMAN-brightgreen" /></a>
<a href="#sql"><img src="https://img.shields.io/badge/Homework-QSL-brightgreen" /></a><br>
<hr>

## Bash
<details>
 <summary>Bash_HW_1</summary>
  

1) Посмотреть где я
	```bash
	pwd
2) Создать папку
	```bash
	mkdir new_folder
3) Зайти в папку
	```bash
	cd new_folder
4) Создать 3 папки
	```bash
	mkdir nf_1 nf_2 nf_3
5) Зайти в любоую папку
	```bash
	cd nf_1
6) Создать 5 файлов (3 txt, 2 json)
	```bash
	touch tf_1.txt tf_2.txt tf_3.txt jf_1.json jf_2.json
7) Создать 3 папки
	```bash
	mkdir nf_1_1 nf_1_2 nf_1_3 
8. Вывести список содержимого папки
	```bash
	ls -la
9) + Открыть любой txt файл
	```bash
	vim tf_1.txt
10) + написать туда что-нибудь, любой текст.
	```bash
	i Hello world
11) + сохранить и выйти.
	```bash
	Esc :wq
12) Выйти из папки на уровень выше
	```bash
	cd ..
13) переместить любые 2 файла, которые вы создали, в любую другую папку.
	```bash
	mv nf_1/tf_1.txt nf_1/tf_2.txt nf_2
14) скопировать любые 2 файла, которые вы создали, в любую другую папку.
	```bash
	cp nf_1/tf_3.txt nf_1/jf_1.json nf_3
15) Найти файл по имени
	```bash
	find . -name jf_1.json
16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
	```bash
	tail -f
17) вывести несколько первых строк из текстового файла
	```bash
	head -3 somefile.txt
18) вывести несколько последних строк из текстового файла
	```bash
	tail -3 somefile.txt
19) просмотреть содержимое длинного файла (команда less) изучите как она работает.
	```bash
	less test_file.txt
20) вывести дату и время
	```bash
	date
	
</details>
<hr>

### GitHub
<details>
 <summary>GitHub_HW_1</summary>
	
	
### JSON
 4) Создать внешний репозиторий c названием `JSON`
 5) Клонировать репозиторий `JSON` на локальный компьютер
	```bash
	git clone
 6) Внутри локального `JSON` создать файл `new.json`
	```bash
	touch new.json
 7) Добавить файл под гит
	```bash
	git add new.json
 8) Закоммитить файл
	```bash
	git commit -m 'adding json file'
 9) Отправить файл на внешний [<kbd>GitHub</kbd>](https://github.com/ekolodenets "Evgeny") репозиторий
	```bash
	git push
 10) Отредактировать содержание файла `new.json`  написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата) Всё написать в формате `JSON`
	
	
	vim new.json
 11) Отправить изменения на внешний репозиторий
	
	git push
 12) Создать файл `preferences.json`
	
	touch preferences.json
 13) В файл `preferences.json` добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате `JSON`
	
	vim preferences.json
 14) Создать файл `sklls.json` добавить информацию о скиллах которые будут изучены на курсе в формате `JSON`
	
	vim skill.json
 15) Отправить сразу 2 файла на внешний репозиторий
	
	git add preferences.json skills.json && git commit -m "creating files" && git push
 16) На веб интерфейсе создать файл `bug_report.json`
 17) Сделать `Commit changes` (сохранить) изменения на веб интерфейсе.
 18) На веб интерфейсе модифицировать файл `bug_report.json`, добавить баг репорт в формате `JSON`
 19) Сделать `Commit changes` (сохранить) изменения на веб интерфейсе.
 20) Синхронизировать внешний и локальный репозиторий `JSON`
	
	git pull

### XML
 21) Создать внешний репозиторий c названием `XML`
 22) Клонировать репозиторий `XML` на локальный компьютер
	
	git clone
 23) Внутри локального `XML` создать файл `new.xml`

	touch new.xml
 24) Добавить файл под гит
	
	git add new.xml
 25) Закоммитить файл
	
	git commit -m "adding xml file"
 26) Отправить файл на внешний [<kbd>GitHub</kbd>](https://github.com/ekolodenets "Evgeny") репозиторий
	
	git push
 27) Отредактировать содержание файла `new.xml` - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML
	
	vim new.xml
 28) Отправить изменения на внешний репозиторий
	
	git add new.xml && git commit -m "modifying file" && git push
 29) Создать файл `preferences.xml`
	
	touch preferences.xml
 30) В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате `XML`
	
	vim preferences.xml
 31) Создать файл `sklls.xml` добавить информацию о скиллах которые будут изучены на курсе в формате `XML`
	
	vim skills.xml
 32) Сделать коммит в одну строку
	
	git add preferences.xml && git commit -m "adding pref" && git add skills.xml && git commit -m "adding skills"
 33) Отправить сразу 2 файла на внешний репозиторий
	
	git push
 34) На веб интерфейсе создать файл `bug_report.xml`
 35) Сделать `Commit changes` (сохранить) изменения на веб интерфейсе
 36) На веб интерфейсе модифицировать файл `bug_report.xml`, добавить баг репорт в формате `XML`
 37) Сделать `Commit changes` (сохранить) изменения на веб интерфейсе
 38) Синхронизировать внешний и локальный репозиторий `XML`
	
	git pull	
	
### TXT
 1) Создать внешний репозиторий c названием `TXT`
 2) Клонировать репозиторий `TXT` на локальный компьютер
	```bash
	git clone
 3) Внутри локального `TXT `создать файл `new.txt`
	```bash
	touch new.txt
 4) Добавить файл под гит
	```bash
	git add new.txt
 5) Закоммитить файл
	```bash
	git commit -m "creating new.txt file"
 6) Отправить файл на внешний [<kbd>GitHub</kbd>](https://github.com/ekolodenets "Evgeny") репозиторий
	```bash
	git push
 7) Отредактировать содержание файла `new.txt` - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT
	```bash
	vim new.txt
 8) Отправить изменения на внешний репозиторий
	```bash
	git add new.txt && git commit -m "modifying file" && git push
 9) Создать файл `preferences.txt`
	```bash
	touch preferences.txt
 10) В файл `preferences.txt` добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате `TXT`
	
	vim preferences.txt
 11) Создать файл `sklls.txt` добавить информацию о скиллах которые будут изучены на курсе в формате `TXT`

	vim skills.txt
 12) Сделать коммит в одну строку

	git add preferences.txt && git commit -m "adding pref" && git add skills.txt && git commit -m "adding skills"
 13) Отправить сразу 2 файла на внешний репозиторий

	git push
 14) На веб интерфейсе создать файл `bug_report.txt`
 15) Сделать `Commit changes` (сохранить) изменения на веб интерфейсе
 16) На веб интерфейсе модифицировать файл `bug_report.txt`, добавить баг репорт в формате `TXT`.
 17) Сделать `Commit changes` (сохранить) изменения на веб интерфейсе
 18) Синхронизировать внешний и локальный репозиторий `TXT`

	git pull
</details>

<hr>	
	
### Postman
<details>
 <summary>Postman HW_1</summary>
  
```json
{
	"info": {
		"_postman_id": "8b1b941b-5486-4726-bdb8-98303da56570",
		"name": "Postman_HW_1",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "EP_1",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "",
						"value": "",
						"type": "text"
					}
				],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "http://162.55.220.72:5005/get_method?name=Evgeny&age=35",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"get_method"
					],
					"query": [
						{
							"key": "name",
							"value": "Evgeny"
						},
						{
							"key": "age",
							"value": "35"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_2",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "Evgeny",
							"type": "text"
						},
						{
							"key": "age",
							"value": "35",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1500",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/user_info_3",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_3"
					],
					"query": [
						{
							"key": "",
							"value": null,
							"disabled": true
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_3",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_1?name=Evgeny&age=35&weight=99",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_1"
					],
					"query": [
						{
							"key": "name",
							"value": "Evgeny"
						},
						{
							"key": "age",
							"value": "35"
						},
						{
							"key": "weight",
							"value": "99"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_4",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_2?name=Evgeny&age=35&salary=1500",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_2"
					],
					"query": [
						{
							"key": "name",
							"value": "Evgeny"
						},
						{
							"key": "age",
							"value": "35"
						},
						{
							"key": "salary",
							"value": "1500"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_5",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_3?name=Evgeny&age=35&salary=1500",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "Evgeny"
						},
						{
							"key": "age",
							"value": "35"
						},
						{
							"key": "salary",
							"value": "1500"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_6",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_4?name=Evgeny&age=35&salary=1500",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_4"
					],
					"query": [
						{
							"key": "name",
							"value": "Evgeny"
						},
						{
							"key": "age",
							"value": "35"
						},
						{
							"key": "salary",
							"value": "1500"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_7",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "Evgeny",
							"type": "text"
						},
						{
							"key": "age",
							"value": "35",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1500",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/user_info_2",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_2"
					]
				}
			},
			"response": []
		}
	]
}
```

</details>

<details>
 <summary>Postman HW_2</summary>
  
```json
{
	"info": {
		"_postman_id": "9fb91d31-713d-45df-825a-55d1c7c9e732",
		"name": "Postman_HW_2",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "EP_1",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"pm.test(\"Body matches string\", function () {\r",
							"    pm.expect(pm.response.text()).to.include(\"This is the first responce from server!\");\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "{{url}}/first",
					"host": [
						"{{url}}"
					],
					"path": [
						"first"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_2",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// http://162.55.220.72:5005/user_info_3\r",
							"// 1. Отправить запрос.\r",
							"// 2. Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 3. Спарсить response body в json.\r",
							"var jsonData = pm.response.json()\r",
							"// 4. Проверить, что name в ответе равно name s request (name вбить руками.)\r",
							"pm.test(\"Your test name is Evgeny\", function () {\r",
							"    pm.expect(jsonData.name).to.eql('Evgeny');\r",
							"});\r",
							"// 5. Проверить, что age в ответе равно age s request (age вбить руками.)\r",
							"pm.test(\"Your test age is 35\", function () {\r",
							"    pm.expect(jsonData.age).to.eql('35');\r",
							"});\r",
							"// 6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)\r",
							"pm.test(\"Your test salary is 1500\", function () {\r",
							"    pm.expect(jsonData.salary).to.eql(1500);\r",
							"});\r",
							"// 7. Спарсить request.\r",
							"var reqData = request.data\r",
							"\r",
							"// 8. Проверить, что name в ответе равно name s request (name забрать из request.)\r",
							"pm.test('name == name form req', function(){\r",
							"    pm.expect(jsonData.name).to.eql(reqData.name)\r",
							"});\r",
							"// 9. Проверить, что age в ответе равно age s request (age забрать из request.)\r",
							"pm.test('age == age form req', function(){\r",
							"    pm.expect(jsonData.age).to.eql(reqData.age)\r",
							"});\r",
							"// 10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)\r",
							"pm.test('salary == salary from req', function(){\r",
							"    pm.expect(jsonData.salary).to.eql(+reqData.salary)\r",
							"});\r",
							"// 11. Вывести в консоль параметр family из response.\r",
							"console.log(jsonData.family)\r",
							"// 12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)\r",
							"pm.test('u_salary_1_5_year == salary*4 from req', function(){\r",
							"    pm.expect(jsonData.family.u_salary_1_5_year).to.eql(+reqData.salary*4)\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "Evgeny",
							"type": "text"
						},
						{
							"key": "age",
							"value": "35",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1500",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/user_info_3",
					"host": [
						"{{url}}"
					],
					"path": [
						"user_info_3"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_3",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// http://162.55.220.72:5005/object_info_3\r",
							"// 1. Отправить запрос.\r",
							"// 2. Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 3. Спарсить response body в json.\r",
							"var jsonData = pm.response.json()\r",
							"// 4. Спарсить request.\r",
							"var reqData = pm.request.url.query.toObject()\r",
							"// 5. Проверить, что name в ответе равно name s request (name забрать из request.)\r",
							"pm.test(\"Name == name req\", function () {\r",
							"    pm.expect(jsonData.name).to.eql(reqData.name);\r",
							"});\r",
							"// 6. Проверить, что age в ответе равно age s request (age забрать из request.)\r",
							"pm.test(\"Age == age req\", function () {\r",
							"    pm.expect(jsonData.age).to.eql(reqData.age);\r",
							"});\r",
							"// 7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)\r",
							"pm.test(\"Salary == salary req\", function(){\r",
							"    pm.expect(jsonData.salary).to.eql(+reqData.salary);\r",
							"});\r",
							"// 8. Вывести в консоль параметр family из response.\r",
							"console.log(jsonData.family)\r",
							"// 9. Проверить, что у параметра dog есть параметры name.\r",
							"pm.test(\"Dog has name\", function(){\r",
							"    pm.expect(jsonData.family.pets.dog.name).exist\r",
							"});\r",
							"console.log(jsonData.family.pets.dog.name)\r",
							"// 10. Проверить, что у параметра dog есть параметры age.\r",
							"pm.test(\"Dog has age\", function(){\r",
							"    pm.expect(jsonData.family.pets.dog.age).exist\r",
							"});\r",
							"// 11. Проверить, что параметр name имеет значение Luky.\r",
							"pm.test(\"Dog's name is Luky\", function(){\r",
							"    pm.expect(jsonData.family.pets.dog.name).to.eql('Luky')\r",
							"});\r",
							"// 12. Проверить, что параметр age имеет значение 4.\r",
							"pm.test(\"Dog's age is 4\", function(){\r",
							"    pm.expect(jsonData.family.pets.dog.age).to.eql(4)\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "{{url}}/object_info_3?name=Evgeny&age=35&salary=1500",
					"host": [
						"{{url}}"
					],
					"path": [
						"object_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "Evgeny"
						},
						{
							"key": "age",
							"value": "35"
						},
						{
							"key": "salary",
							"value": "1500"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_4",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// http://162.55.220.72:5005/object_info_4\r",
							"// 1. Отправить запрос.\r",
							"// 2. Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 3. Спарсить response body в json.\r",
							"var jsonData = pm.response.json()\r",
							"// 4. Спарсить request.\r",
							"var reqData = pm.request.url.query.toObject()\r",
							"// 5. Проверить, что name в ответе равно name s request (name забрать из request.)\r",
							"pm.test(\"name == name req\", function(){\r",
							"    pm.expect(jsonData.name).to.eql(reqData.name)\r",
							"})\r",
							"// 6. Проверить, что age в ответе равно age из request (age забрать из request.)\r",
							"pm.test(\"age == age req\", function(){\r",
							"    pm.expect(jsonData.age).to.eql(+reqData.age)\r",
							"})\r",
							"// 7. Вывести в консоль параметр salary из request.\r",
							"console.log(reqData.salary)\r",
							"// 8. Вывести в консоль параметр salary из response.\r",
							"console.log(jsonData.salary)\r",
							"// 9. Вывести в консоль 0-й элемент параметра salary из response.\r",
							"console.log(jsonData.salary[0])\r",
							"// 10. Вывести в консоль 1-й элемент параметра salary параметр salary из response.\r",
							"console.log(jsonData.salary[1])\r",
							"// 11. Вывести в консоль 2-й элемент параметра salary параметр salary из response.\r",
							"console.log(jsonData.salary[2])\r",
							"// 12. Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request.)\r",
							"pm.test(\"salary[0] == salary req\", function(){\r",
							"    pm.expect(jsonData.salary[0]).to.eql(+reqData.salary)\r",
							"})\r",
							"// 13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request.)\r",
							"pm.test('salary[1] = salary *2 req', function(){\r",
							"    pm.expect(+jsonData.salary[1]).to.eql(+reqData.salary*2)\r",
							"})\r",
							"// 14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request.)\r",
							"pm.test('salary[2] = salary *3 req', function(){\r",
							"    pm.expect(+jsonData.salary[2]).to.eql(+reqData.salary*3)\r",
							"})\r",
							"// 15. Создать в окружении переменную name\r",
							"// 16. Создать в окружении переменную age\r",
							"// 17. Создать в окружении переменную salary\r",
							"// 18. Передать в окружение переменную name\r",
							"pm.environment.set('name', jsonData.name)\r",
							"// 19. Передать в окружение переменную age\r",
							"pm.environment.set('age', jsonData.age)\r",
							"// 20. Передать в окружение переменную salary\r",
							"pm.environment.set('salary', jsonData.salary[0])\r",
							"// 21. Написать цикл который выведет в консоль по порядку элементы списка из параметра salary.\r",
							"for (i in reqData.salary){\r",
							"    console.log(reqData.salary[i])\r",
							"}"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "{{url}}/object_info_4?name=Evgeny&age=35&salary=1500",
					"host": [
						"{{url}}"
					],
					"path": [
						"object_info_4"
					],
					"query": [
						{
							"key": "name",
							"value": "Evgeny"
						},
						{
							"key": "age",
							"value": "35"
						},
						{
							"key": "salary",
							"value": "1500"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_5",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// http://162.55.220.72:5005/user_info_2\r",
							"// 1. Вставить параметр salary из окружения в request\r",
							"// 2. Вставить параметр age из окружения в age\r",
							"// 3. Вставить параметр name из окружения в name\r",
							"// 4. Отправить запрос.\r",
							"// 5. Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 6. Спарсить response body в json.\r",
							"var jsonData = pm.response.json()\r",
							"// 7. Спарсить request.\r",
							"var reqData = request.data\r",
							"// 8. Проверить, что json response имеет параметр start_qa_salary\r",
							"pm.test(\"json response имеет параметр start_qa_salary\", function () {\r",
							"    pm.expect(jsonData).to.have.property(\"start_qa_salary\")\r",
							"});\r",
							"// 9. Проверить, что json response имеет параметр qa_salary_after_6_months\r",
							"pm.test(\"json response имеет параметр qa_salary_after_6_months\", function () {\r",
							"    pm.expect(jsonData).to.have.property(\"qa_salary_after_6_months\");\r",
							"});\r",
							"// 10. Проверить, что json response имеет параметр qa_salary_after_12_months\r",
							"pm.test(\"json response имеет параметр qa_salary_after_12_months\", function () {\r",
							"    pm.expect(jsonData).to.have.property(\"qa_salary_after_12_months\");\r",
							"});\r",
							"// 11. Проверить, что json response имеет параметр qa_salary_after_1.5_year\r",
							"pm.test(\"json response имеет параметр qa_salary_after_1.5_year\", function () {\r",
							"    pm.expect(jsonData).to.have.property(\"qa_salary_after_1.5_year\");\r",
							"});\r",
							"// 12. Проверить, что json response имеет параметр qa_salary_after_3.5_years\r",
							"pm.test(\"json response имеет параметр qa_salary_after_3.5_years\", function () {\r",
							"    pm.expect(jsonData).to.have.property(\"qa_salary_after_3.5_years\");\r",
							"});\r",
							"// 13. Проверить, что json response имеет параметр person\r",
							"pm.test(\"json response имеет параметр person\", function () {\r",
							"    pm.expect(jsonData).to.have.property(\"person\");\r",
							"});\r",
							"// 14. Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request.)\r",
							"pm.test(\"start_qa_salary check\", function(){\r",
							"    pm.expect(jsonData.start_qa_salary).to.eql(+reqData.salary)\r",
							"});\r",
							"// 15. Проверить, что параметр qa_salary_after_6_months равен salary*2 из request (salary забрать из request.)\r",
							"pm.test(\"qa_salary_after_6_months check\", function(){\r",
							"    pm.expect(jsonData.qa_salary_after_6_months).to.eql(+reqData.salary*2)\r",
							"});\r",
							"// 16. Проверить, что параметр qa_salary_after_12_months равен salary*2.7 из request (salary забрать из request.)\r",
							"pm.test(\"qa_salary_after_12_months check\", function(){\r",
							"    pm.expect(jsonData.qa_salary_after_12_months).to.eql(+reqData.salary*2.7)\r",
							"});\r",
							"// 17. Проверить, что параметр qa_salary_after_1.5_year равен salary*3.3 из request (salary забрать из request.)\r",
							"pm.test(\"qa_salary_after_1.5_year check\", function(){\r",
							"    pm.expect(jsonData['qa_salary_after_1.5_year']).to.eql(+reqData.salary*3.3)\r",
							"});\r",
							"// 18. Проверить, что параметр qa_salary_after_3.5_years равен salary*3.8 из request (salary забрать из request.)\r",
							"pm.test(\"qa_salary_after_3.5_years check\", function(){\r",
							"    pm.expect(jsonData['qa_salary_after_3.5_years']).to.eql(+reqData.salary*3.8)\r",
							"});\r",
							"// 19. Проверить, что в параметре person, 1-й элемент из u_name равен salary из request (salary забрать из request.)\r",
							"pm.test(\"person.u_name[1] check\", function(){\r",
							"    pm.expect(jsonData.person.u_name[1]).to.eql(+reqData.salary)\r",
							"});\r",
							"// 20. Проверить, что что параметр u_age равен age из request (age забрать из request.)\r",
							"pm.test(\"person.u_age check\", function(){\r",
							"    pm.expect(jsonData.person.u_age).to.eql(+reqData.age)\r",
							"});\r",
							"// 21. Проверить, что параметр u_salary_5_years равен salary*4.2 из request (salary забрать из request.)\r",
							"pm.test(\"u_salary_5_years check\", function(){\r",
							"    pm.expect(jsonData.person.u_salary_5_years).to.eql(+reqData.salary*4.2)\r",
							"});\r",
							"// 22. ***Написать цикл который выведет в консоль по порядку элементы списка из параметра person.\r",
							"for (i in jsonData.person){\r",
							"    if(typeof(jsonData.person[i]) == 'object'){\r",
							"        for (j in jsonData.person[i]){\r",
							"            console.log(jsonData.person[i][j])   \r",
							"        }\r",
							"    }\r",
							"    else if(typeof(jsonData.person[i]) != 'object'){\r",
							"        console.log(jsonData.person[i])\r",
							"    }\r",
							"}"
						],
						"type": "text/javascript"
					}
				},
				{
					"listen": "prerequest",
					"script": {
						"exec": [
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "{{name}}",
							"type": "text"
						},
						{
							"key": "age",
							"value": "{{age}}",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "{{salary}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/user_info_2",
					"host": [
						"{{url}}"
					],
					"path": [
						"user_info_2"
					]
				}
			},
			"response": []
		}
	]
}
```

</details>

<details>
 <summary>Postman HW_3</summary>
  
```json
{
	"info": {
		"_postman_id": "dbb97a47-c44a-4627-bf15-274047b0bf17",
		"name": "Postman_HW_3",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "EP_1 login",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"var jsonData = pm.response.json()\r",
							"pm.environment.set('token', jsonData.token)"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "logint",
							"value": "",
							"description": "Evgeny",
							"type": "text"
						},
						{
							"key": "password",
							"value": "",
							"description": "test",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/login",
					"host": [
						"{{url}}"
					],
					"path": [
						"login"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_2 user_info",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// 2) http://162.55.220.72:5005/user_info\r",
							"// req. (RAW JSON)\r",
							"// POST\r",
							"// age: int\r",
							"// salary: int\r",
							"// name: str\r",
							"// auth_token\r",
							"\r",
							"\r",
							"// resp.\r",
							"// {'start_qa_salary':salary,\r",
							"//  'qa_salary_after_6_months': salary * 2,\r",
							"//  'qa_salary_after_12_months': salary * 2.9,\r",
							"//  'person': {'u_name':[user_name, salary, age],\r",
							"//                                 'u_age':age,\r",
							"//                                 'u_salary_1.5_year': salary * 4}\r",
							"//                                 }\r",
							"\r",
							"// Тесты:\r",
							"// 1) Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"\r",
							"// 2) Проверка структуры json в ответе.\r",
							"const schema = {\r",
							"    \"person\": {\r",
							"        \"u_age\": 35,\r",
							"        \"u_name\": [\r",
							"            \"Evgeny\",\r",
							"            1500,\r",
							"            35\r",
							"        ],\r",
							"        \"u_salary_1_5_year\": 6000\r",
							"    },\r",
							"    \"qa_salary_after_12_months\": 4350.0,\r",
							"    \"qa_salary_after_6_months\": 3000,\r",
							"    \"start_qa_salary\": 1500\r",
							"}\r",
							"\r",
							"pm.test('Schema is valid', function() {\r",
							"  pm.response.to.have.jsonSchema(schema);\r",
							"});\r",
							"\r",
							"// 3) В ответе указаны коэффициенты умножения salary, напишите тесты по проверке правильности результата перемножения на коэффициент.\r",
							"var jsonData = pm.response.json()\r",
							"var reqData = JSON.parse(request.data).salary\r",
							"\r",
							"pm.test(jsonData.qa_salary_after_12_months + \"$ == salary*2.9 (\" + reqData+'$)', function(){\r",
							"    pm.expect(jsonData.qa_salary_after_12_months).to.eql(reqData*2.9)\r",
							"})\r",
							"// 4) Достать значение из поля 'u_salary_1.5_year' и передать в поле salary запроса http://162.55.220.72:5005/get_test_user\r",
							"\r",
							"var eighteenmonth = jsonData.person.u_salary_1_5_year\r",
							"pm.environment.set('u_salary_1.5_year', eighteenmonth);\r",
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"age\": 35,\r\n\"salary\": 1500,\r\n\"name\": \"Evgeny\",\r\n\"auth_token\":\"{{token}}\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "{{url}}/user_info",
					"host": [
						"{{url}}"
					],
					"path": [
						"user_info"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_3 new_data",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// 3) http://162.55.220.72:5005/new_data\r",
							"// req.\r",
							"// POST\r",
							"// age: int\r",
							"// salary: int\r",
							"// name: str\r",
							"// auth_token\r",
							"\r",
							"// Resp.\r",
							"// {'name':name,\r",
							"//   'age': int(age),\r",
							"//   'salary': [salary, str(salary*2), str(salary*3)]}\r",
							"\r",
							"// Тесты:\r",
							"// 1) Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 2) Проверка структуры json в ответе.\r",
							"const schema = {\r",
							"    \"age\": 35,\r",
							"    \"name\": \"Evgeny\",\r",
							"    \"salary\": [\r",
							"        6000,\r",
							"        \"12000\",\r",
							"        \"18000\"\r",
							"    ]\r",
							"}\r",
							"\r",
							"pm.test('Schema is valid', function() {\r",
							"  pm.response.to.have.jsonSchema(schema);\r",
							"});\r",
							"// 3) В ответе указаны коэффициенты умножения salary, напишите тесты по проверке правильности результата перемножения на коэффициент.\r",
							"var jsonData = pm.response.json()\r",
							"var reqData = +request.data.salary\r",
							"\r",
							"\r",
							"pm.test(+jsonData.salary[1]+\" is salary *2 (\" + reqData+')', function(){\r",
							"    pm.expect(+jsonData.salary[1]).to.eql(reqData*2)\r",
							"})\r",
							"pm.test(+jsonData.salary[2]+\" is salary *3 (\" + reqData+')', function(){\r",
							"    pm.expect(+jsonData.salary[2]).to.eql(reqData*3)\r",
							"})\r",
							"// 4) проверить, что 2-й элемент массива salary больше 1-го и 0-го\r",
							"pm.test(jsonData.salary[1]+\" is more then \"+reqData, function(){\r",
							"    pm.expect(+jsonData.salary[1]).to.be.above(reqData)\r",
							"})"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "{{name}}",
							"type": "text"
						},
						{
							"key": "age",
							"value": "{{age}}",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "{{u_salary_1.5_year}}",
							"type": "text"
						},
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/new_data",
					"host": [
						"{{url}}"
					],
					"path": [
						"new_data"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_4 test_pet_info",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// req.\r",
							"// POST\r",
							"// age: int\r",
							"// weight: int\r",
							"// name: str\r",
							"// auth_token\r",
							"\r",
							"\r",
							"// Resp.\r",
							"// {'name': name,\r",
							"//  'age': age,\r",
							"//  'daily_food':weight * 0.012,\r",
							"//  'daily_sleep': weight * 2.5}\r",
							"\r",
							"\r",
							"// Тесты:\r",
							"// 1) Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 2) Проверка структуры json в ответе.\r",
							"const schema = {\r",
							"    \"age\": 35,\r",
							"    \"daily_food\": 1.2,\r",
							"    \"daily_sleep\": 250.0,\r",
							"    \"name\": \"Evgeny\"\r",
							"}\r",
							"\r",
							"pm.test('Schema is valid', function() {\r",
							"  pm.response.to.have.jsonSchema(schema);\r",
							"});\r",
							"// 3) В ответе указаны коэффициенты умножения weight, напишите тесты по проверке правильности результата перемножения на коэффициент.\r",
							"var jsonData = pm.response.json()\r",
							"var food = +pm.request.body.formdata.toJSON()[2].value\r",
							"var sleep = +pm.request.body.formdata.toJSON()[2].value\r",
							"\r",
							"pm.test('food ' + jsonData.daily_food + ' is equal to weight*0.012', function(){\r",
							"    pm.expect(jsonData.daily_food).to.eql(food*0.012)\r",
							"})\r",
							"\r",
							"pm.test('sleep ' + jsonData.daily_sleep + ' is equal to weight*2.5', function(){\r",
							"    pm.expect(jsonData.daily_sleep).to.eql(food*2.5)\r",
							"})"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "{{name}}",
							"type": "text"
						},
						{
							"key": "age",
							"value": "{{age}}",
							"type": "text"
						},
						{
							"key": "weight",
							"value": "100",
							"type": "text"
						},
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/test_pet_info",
					"host": [
						"{{url}}"
					],
					"path": [
						"test_pet_info"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_5 get_test_user",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// 5) http://162.55.220.72:5005/get_test_user\r",
							"// req.\r",
							"// POST\r",
							"// age: int\r",
							"// salary: int\r",
							"// name: str\r",
							"// auth_token\r",
							"\r",
							"// Resp.\r",
							"// {'name': name,\r",
							"//  'age':age,\r",
							"//  'salary': salary,\r",
							"//  'family':{'children':[['Alex', 24],['Kate', 12]],\r",
							"//  'u_salary_1.5_year': salary * 4}\r",
							"//   }\r",
							"\r",
							"// Тесты:\r",
							"// 1) Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 2) Проверка структуры json в ответе.\r",
							"const schema = {\r",
							"    \"age\": \"35\",\r",
							"    \"family\": {\r",
							"        \"children\": [\r",
							"            [\r",
							"                \"Alex\",\r",
							"                24\r",
							"            ],\r",
							"            [\r",
							"                \"Kate\",\r",
							"                12\r",
							"            ]\r",
							"        ],\r",
							"        \"u_salary_1_5_year\": 24000\r",
							"    },\r",
							"    \"name\": \"Evgeny\",\r",
							"    \"salary\": 6000\r",
							"}\r",
							"pm.test('Schema is valid', function() {\r",
							"  pm.response.to.have.jsonSchema(schema);\r",
							"});\r",
							"// 3) Проверить что занчение поля name = значению переменной name из окружения\r",
							"var jsonData = pm.response.json()\r",
							"pm.test('name = значению переменной name из окружения', function(){\r",
							"    pm.expect(jsonData.name).to.eql(pm.environment.get('name'))\r",
							"})\r",
							"\r",
							"// 4) Проверить что занчение поля age в ответе соответсвует отправленному в запросе значению поля age\r",
							"pm.test('age = значению переменной age из окружения', function(){\r",
							"    pm.expect(jsonData.age).to.eql(pm.environment.get('age').toString())\r",
							"})"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "age",
							"value": "{{age}}",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "{{u_salary_1.5_year}}",
							"type": "text"
						},
						{
							"key": "name",
							"value": "{{name}}",
							"type": "text"
						},
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/get_test_user",
					"host": [
						"{{url}}"
					],
					"path": [
						"get_test_user"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_6 currency",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// 6) http://162.55.220.72:5005/currency\r",
							"// req.\r",
							"// POST\r",
							"// auth_token\r",
							"\r",
							"// Resp. Передаётся список массив объектов.\r",
							"// [\r",
							"// {\"Cur_Abbreviation\": str,\r",
							"//  \"Cur_ID\": int,\r",
							"//  \"Cur_Name\": str\r",
							"// }\r",
							"// …\r",
							"// {\"Cur_Abbreviation\": str,\r",
							"//  \"Cur_ID\": int,\r",
							"//  \"Cur_Name\": str\r",
							"// }\r",
							"// ]\r",
							"// Тесты:\r",
							"// 1) Можете взять любой объект из присланного списка, используйте js random.\r",
							"// В объекте возьмите Cur_ID и передать через окружение в следующий запрос.\r",
							"var jsonData = pm.response.json()\r",
							"\r",
							"// iteration with FOR\r",
							"// let list_id = []\r",
							"// for (i in jsonData){\r",
							"//     list_id.push(jsonData[i].Cur_ID);}\r",
							"\r",
							"// iteration with MAP function\r",
							"const list_id = jsonData.map(tool => tool.Cur_ID)\r",
							"// const list_id = [451,453,1,3,451]\r",
							"// pm.environment.set('list_id_demo', list_id);\r",
							"\r",
							"// set env value for one curr\r",
							"pm.environment.set('cur_id', list_id[_.random(list_id.length-1)]);\r",
							"\r",
							"// set env value for list of curr\r",
							"pm.environment.set('list_id', list_id)\r",
							"\r",
							"\r",
							"\r",
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/currency",
					"host": [
						"{{url}}"
					],
					"path": [
						"currency"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_7 curr_byn",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"// 7) http://162.55.220.72:5005/curr_byn\r",
							"// req.\r",
							"// POST\r",
							"// auth_token\r",
							"// curr_code: int\r",
							"\r",
							"// Resp.\r",
							"// {\r",
							"    // \"Cur_Abbreviation\": str\r",
							"    // \"Cur_ID\": int,\r",
							"    // \"Cur_Name\": str,\r",
							"    // \"Cur_OfficialRate\": float,\r",
							"    // \"Cur_Scale\": int,\r",
							"    // \"Date\": str\r",
							"// }\r",
							"\r",
							"// Тесты:\r",
							"// 1) Статус код 200\r",
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});\r",
							"// 2) Проверка структуры json в ответе.\r",
							"const   schema = {\r",
							"    \"Cur_Abbreviation\": 'str',\r",
							"    \"Cur_ID\": 'int',\r",
							"    \"Cur_Name\": 'str',\r",
							"    \"Cur_OfficialRate\": 'float',\r",
							"    \"Cur_Scale\": 'int',\r",
							"    \"Date\": 'str'\r",
							"}\r",
							"pm.test('Schema is valid', function() {\r",
							"  pm.response.to.have.jsonSchema(schema);\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						},
						{
							"key": "curr_code",
							"value": "{{cur_id}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}/curr_byn",
					"host": [
						"{{url}}"
					],
					"path": [
						"curr_byn"
					]
				}
			},
			"response": []
		},
		{
			"name": "EP_3stars",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"var env = pm.environment.get('list_id');\r",
							"for (i in env){\r",
							"    const postRequest = {\r",
							"        url: 'http://162.55.220.72:5005/curr_byn',\r",
							"        method: 'POST',\r",
							"        body: {mode: 'formdata',\r",
							"        formdata: [ {key: 'auth_token', value: '/s34lfgbj/None/jjd909/56653kjkWpqc3387370954evny'},\r",
							"                    {key: 'curr_code', value: env[i]}]}};\r",
							"\r",
							"    pm.sendRequest(postRequest, (error, response) => {\r",
							"        if (response.code != 500 && response.json().Cur_OfficialRate){\r",
							"                Rate = response.json().Cur_OfficialRate\r",
							"                CAbbr = response.json().Cur_Abbreviation\r",
							"                CID = response.json().Cur_ID\r",
							"                CName = response.json().Cur_Name\r",
							"                CScale = response.json().Cur_Scale\r",
							"                CDate = response.json().Date\r",
							"                console.log(    \"Знак:\", CAbbr,\r",
							"                                \"ID:\", CID,\r",
							"                                \"Название:\", CName,\r",
							"                                \"Курс:\", Rate,\r",
							"                                \"Соотношение:\", CScale,\r",
							"                                \"Дата:\",CDate)}});}"
						],
						"type": "text/javascript"
					}
				},
				{
					"listen": "prerequest",
					"script": {
						"exec": [
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text",
							"disabled": true
						},
						{
							"key": "curr_code",
							"value": "{{cur_id}}",
							"type": "text",
							"disabled": true
						}
					]
				},
				"url": {
					"raw": "{{url}}/curr_byn",
					"host": [
						"{{url}}"
					],
					"path": [
						"curr_byn"
					]
				}
			},
			"response": []
		}
	],
	"variable": [
		{
			"key": "username",
			"value": ""
		},
		{
			"key": "usernames",
			"value": ""
		}
	]
}
```

</details>
<hr>


### SQL
<details>
 <summary>SQL HW_1</summary>
  

1. Вывести все поля и все строки.	
	```sql 
	select * from students;
2. Вывести всех студентов в таблице
	```sql 
	select * from students;
3. Вывести только Id пользователей
	```sql 
	select id from students;
4. Вывести только имя пользователей
	```sql 
	select name from students;
5. Вывести только email пользователей
	```sql 
	select email from students;
6. Вывести имя и email пользователей
	```sql 
	select name, email from students;
7. Вывести id, имя, email и дату создания пользователей
	```sql 
	select id, name, email, created_on FROM students;
8. Вывести пользователей где password 12333
	```sql 
	select * from students where password='12333';
9. Вывести пользователей которые были созданы 2021-03-26 00:00:00
	```sql 
	select * from students where created_on = '2021-03-26 00:00:00';
10. Вывести пользователей где в имени есть слово Анна
	```sql 
	select * from students where name like '%Anna%';
11. Вывести пользователей где в имени в конце есть 8
	```sql 
	select * from students where name like '%8';
12. Вывести пользователей где в имени в есть буква а
	```sql 
	select * from students where name like '%a';
13. Вывести пользователей которые были созданы 2021-07-12 00:00:00
	```sql 
	select * from students where created_on = '2021-07-12 00:00:00';
14. Вывести пользователей которые были созданы 2021-07-12 00:00:00 и имеют пароль 1m313
	```sql 
	select * from students where created_on = '2021-07-12 00:00:00' and password='1m313';
15. Вывести пользователей которые были созданы 2021-07-12 00:00:00 и у которых в имени есть слово Andrey
	```sql 
	select * from students where created_on = '2021-07-12 00:00:00' and name like 'Andrey%';
16. Вывести пользователей которые были созданы 2021-07-12 00:00:00 и у которых в имени есть цифра 8
	```sql 
	select * from students where created_on = '2021-07-12 00:00:00' and name like '%8%';
17. Вывести пользователя у которых id равен 110
	```sql 
	select * from students where id=110;
18. Вывести пользователя у которых id равен 153
	```sql 
	select * from students where id=153;
19. Вывести пользователя у которых id больше 140
	```sql 
	select * from students where id > 140;
20. Вывести пользователя у которых id меньше 130
	```sql 
	select * from students where id < 130;
21. Вывести пользователя у которых id меньше 127 или больше 188
	```sql 
	select * from students where id < 127 or id > 188;
22. Вывести пользователя у которых id меньше либо равно 137
	```sql 
	select * from students where id <= 137;
23. Вывести пользователя у которых id больше либо равно 137
	```sql 
	select * from students where id >= 137;
24. Вывести пользователя у которых id больше 180 но меньше 190
	```sql 
	select * from students where id > 180 and id < 190;
25. Вывести пользователя у которых id между 180 и 190
	```sql 
	select * from students where id between 180 and 190;
26. Вывести пользователей где password равен 12333, 1m313, 123313
	```sql 
	select * from students 
	where password = '12333' or password ='1m313' or password ='123313';
27. Вывести пользователей где created_on равен 2020-10-03 00:00:00, 2021-05-19 00:00:00, 2021-03-26 00:00:00
	```sql 
	select * from students 
	where created_on = '2020-10-03 00:00:00' or created_on ='2021-05-19 00:00:00' or created_on ='2021-03-26 00:00:00';
28. Вывести минимальный id 
	```sql 
	select min(id) from students;
29. Вывести максимальный.
	```sql 
	select max(id) from students;
30. Вывести количество пользователей
	```sql 
	select count(id) from students;
31. Вывести id пользователя, имя, дату создания пользователя. Отсортировать по порядку возрастания даты добавления пользоватлеля.
	```sql 
	select id, name, created_on from students
	order by created_on asc;
32. Вывести id пользователя, имя, дату создания пользователя. Отсортировать по порядку убывания даты добавления пользоватлеля.
	```sql 
	select id, name, created_on from students
	order by created_on desc;

</details>
