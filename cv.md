# Contacts
* Timofey Vysotsky
* E-mail: tv6667312@gmail.com
* @vusotsku - everywhere

# About me
I am a student and simultaneously studying web development, which is the main goal in programming at the moment. I am fond of website development (including layout and development using website builders for professional use). I also devoted a lot of time to studying computer graphics skills (useful for all stages of creating a website layout).

# Skills
* JavaScript
* C++ (fundamental, STL)
* HTML
* CSS
* All ADOBE products (+Figma)

# Code example (operations with the local database. С++. STL)
```
void findName(vector <GraphicsCard> GC, vector <Ceh_CoolingSystem> cCoolingSystem, vector <Ceh_PowerSystem> cPowerSystem, vector <Ceh_Microchip> cMicrochip, vector <Ceh_GPU> cGPU) {
	string dev;
	cout << "Название продукта завода:\n\n";
	getline(cin, dev);
	getline(cin, dev);

	int number = -1;

	for (int i = 0; i < GC.size(); i++)
	{
		if (dev == GC[i].get_name_GraphicsCard_()) {
			number = i;
		}
	}

	if (number == -1) {
		cout << "\nДанной видеокарты нет в базе данных" << endl;
	}
	else {
		for (int i = 0; i < cCoolingSystem.size(); i++) {
			if (GC[number].get_rotationSpeed_GraphicsCard_() == cCoolingSystem[i].get_rotationSpeed()) {
				//ДЕТАЛЬ 1
				cout << "\nДеталь №1:\n";
				cout << "Название детали:\t" << cCoolingSystem[i].get_name_CoolingSystem() << "\n";
				cout << "Скорость вращения:\t" << cCoolingSystem[i].get_rotationSpeed() << " об/мин" << "\n";
				cout << "Уровень шума:\t" << cCoolingSystem[i].get_noiseLevel() << " дБ" << "\n\n";
			}
		}
	}
```
# Education
* BSU student (Computer Science and Design)

# English
* B2 level
* International House (courses)
