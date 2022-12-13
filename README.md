#include<iostream>


using namespace std;





class Bank{

public:
    string name;
    int balance ;
    int Account_number ;

Bank(string n,int b,long long an){
    name=n;
    balance=b;
    Account_number=an;
}
void checkBalance(){
    cout<<"Your balance is :"<<balance<<endl;    
}


string accounting_number (int Account_number){
    if (Account_number){
    cout<<"welcome  "<<name<<endl;    
}else{
    cout <<"the account is not exitit";
    return 0;
}}

void withdraw(int money){

    balance=balance-money;
}


void deposite(int money){
    balance=balance+money;
}

};


int main(){

int n,v;
cin>>n>>v;


Bank a1=Bank("ahmed",5000,12345678912);
 a1.accounting_number(v);
        switch(n){
        case 1 :a1.deposite(1000);
        break;
        case 2:a1.withdraw(100);
        break;
        case 3:a1.checkBalance();
        break;
    }


    return 0;
}
