#include <iostream>
using namespace std;

void romanNumeralConvert(int);

int main()
{
    romanNumeralConvert(9999);
    return 0;

void romanNumeralConvert(int num) {
    if  (num>=1000) {
        cout << "M";
        romanNumeralConvert (num - 1000);
    }   
    else if (num>=500){
        cout <<"D";
        romanNumeralConvert (num - 500);
    }
    else if(num>=100){
        cout <<"C";
        romanNumeralConvert (num - 100);
    }
    else if(num>=50){
        cout << "L";
        romanNumeralConvert (num - 50);
    }
    else if(num>=20){
        cout << "XX";
        romanNumeralConvert (num - 20);
    }
    else if(num>=19){
        cout << "XIX";
        romanNumeralConvert (num - 19);
    }
    else if(num>=18){
        cout << "XVIII";
        romanNumeralConvert (num - 50);
    }
    else if(num>=17){
        cout << "XVII";
        romanNumeralConvert (num - 17);
    }
    else if(num>=16){
        cout << "XVI";
        romanNumeralConvert (num - 16);
    }
    else if(num>=15){
        cout << "XV";
        romanNumeralConvert (num - 15);
    }
    else if(num>=14){
        cout << "XIV";
        romanNumeralConvert (num - 14);
    }
    else if(num>=13){
        cout << "XIII";
        romanNumeralConvert (num - 13);
    }
    else if(num>=12){
        cout << "XII";
        romanNumeralConvert (num - 12);
    }
    else if(num>=11){
        cout << "XI";
        romanNumeralConvert (num - 11);
    }
    else if(num>=10){
        cout << "X";
        romanNumeralConvert (num - 10);
    }
    else if(num>=9){
        cout << "IX";
        romanNumeralConvert (num - 9);
    }
    else if(num>=9){
        cout << "VIII";
        romanNumeralConvert (num - 8);
    }
    else if(num>=7){
        cout << "VII";
        romanNumeralConvert (num - 7);
    }
    else if(num>=6){
        cout << "VI";
        romanNumeralConvert (num - 6);
    }
    else if(num>=5){
        cout << "V";
        romanNumeralConvert (num - 5);
    }
    else if(num>=4){
        cout << "IV";
        romanNumeralConvert (num - 4);
    }
    else if(num>=3){
        cout << "III";
        romanNumeralConvert (num - 3);
    }
    else if(num>=2){
        cout << "II";
        romanNumeralConvert (num - 2);
    }
    else if(num>=1){
        cout << "I";
        romanNumeralConvert (num - 1);
    }
    
}
