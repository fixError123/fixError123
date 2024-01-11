#include <iostream>
#include <cmath>
#include <string>
using namespace std;

int main() {

	double weight, height, bmi;
	string bmi_category = "";

	cout << "Enter your weight in kilograms: ";
	cin >> weight;
	cout << "Enter your height in meters: ";
	cin >> height;

	bmi = weight / (height * height);

	if (bmi < 18.5)
		bmi_category = "Underweight";
	else if (bmi >= 18.5 && bmi <= 24.9)
		bmi_category = "Normal Weight";
	else if (bmi >= 25.0 && bmi <= 29.9)
		bmi_category = "Overweight";
	else if (bmi >= 30)
		bmi_category = "Obese";

	cout << "Body Mass Index(BMI): " << bmi << endl;
	cout << "Body Mass Index(BMI) category: " << bmi_category << endl;

	return 0;
}

<!---
fixError123/fixError123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
