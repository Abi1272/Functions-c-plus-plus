#include<iostream>
using namespace std;
void docking_countdown();
void truck_weight_check(int load_weight);
void school_zone_signal(string signal_color);
void verify_username();
int get_ticket_price(int visitor_age);

int main() {

	docking_countdown();
	truck_weight_check(500);
	school_zone_signal("yellow");
	verify_username();
	cout << get_ticket_price(40);
}



void docking_countdown() {
	for (int a = 20; a >= 0; a -= 3)
		cout << a << " ";
	cout << endl;
	cout << "Docking complete!" << endl;
}
void truck_weight_check(int load_weight) {
	if (load_weight >= 1200)
		cout << "overweight!" << endl;
	else
		cout << "Within limit." << endl;

}
void school_zone_signal(string signal_color) {
	if (signal_color == "red")
		cout << "stop" << endl;
	else if (signal_color == "yellow")
		cout << "Be ready" << endl;
	else if (signal_color == "green")
		cout << "Proceed" << endl;
}

void verify_username() {
	string username;
	while (username != "CodeMaster123") {
		cout << "What is your username" << endl;
		cin >> username;
	}
		
	cout << "Access Granted!" << endl;

}
int get_ticket_price(int visitor_age) {
	if (visitor_age <= 10) {
		return(8);
	}
	else if (visitor_age >= 60)
		return(12);
	else
		return(18);
}
