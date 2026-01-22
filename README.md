#include<iosteam.h>
using namespace std;

class opq{
public:
int no;
string nam;

opq(){
no=0;
name=" ";
}

void gtdat(){
cout<<"\n Enter No: ";
cin>>no;
cout<<"\n Enter Name: ";
cin>>nam;
}

void ptdat(){
cout<<no<<". "<<nam<<"\n";
}
};

int main(){
opq o1;
o1.gtdat;
o1.ptdat;
return 0;
}

