#include <iostream>
#include <cwchar>



using namespace std;

int main()
{
    
    
    
    string name;
    string difficulty;
    int countZom;
    string weapon;
    
    
    cout << "Press Enter to continue..";
    cin.get();
    
    cout << "[WELCOME TO ZOMBIE APOCALYPSE GAME!]\n\n";
    
    
    cout << "\nEnter your name: ";
    getline (cin, name) ;
    
    
    cout << "\n " << name << " get ready to fight for your life! \n\n";
    
       
    cout << "-> [Easy] \n\n" << endl;
    cout << "-> [Medium] \n\n" << endl;
    cout << "-> [Hard] \n\n" << endl;
    
    cout << "Choose difficulty: ";
    cin >> difficulty;
    
     if (difficulty == "Easy") {
     cout << "Get ready the zombies are coming!\n\n";
    } else if (difficulty == "Medium") {
     cout << "The armored zombies are coming!\n\n";
    } else if (difficulty == "Hard") {
     cout << "The Boss zombie is coming!!!\n\n";
    } else {
    cout << "\nivalid difficulty\n\n";
    cout << "\nChoose difficulty again: ";
    cin >> difficulty;
    }
    
    
    
    
    
    cout << "\nMoney Balance: 50 \n\n";
    
    cout << "[ cost ][ Weapon ] [Damage]" << endl;
    cout << "[  30  ][ Axe    ] [  20  ]" << endl;
    cout << "[  45  ][ Sword  ] [  25  ]" << endl;
    cout << "[  55  ][ Pistol ] [  30  ]" << endl;
     
    
    cout << "Choose weapon: ";
    cin >> weapon;
    
    if (weapon == "Axe") {
   cout << "\nNice Weapon!\n\n";
    } else if (weapon == "Sword") {
   cout << "\nNice Weapon!\n\n";
    } else if (weapon == "Pistol") {
   cout << "\nOut of money!\n\n";
    } else {
   cout << "\nInvalid weapon!\n\n";
    }
    
    
  
     



     
    

    
    
    
    
    return 0;
}
