//C-TEST
//Testing GitHub
#include <iostream>
#include <string>
using namespace std;

class Message
{
public:
		
		
		void getName(string Name) {
			cout << "Welcome"<<Name;
		}
		
};

int main()

{
	string name;
	cout << "What is your name?";
	Message myMessage;
	getline(cin, name);
	myMessage.getName(name);
	cin.get();
}




	
