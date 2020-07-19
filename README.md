#include<iostream>
using namespace std;




int main(){
    int data[5];
    cout<<"enter the elements:";
    
	
	
	for (int i=0;i<5;i++) {
	
		cin>>data[i];
	}
	int *p;
	p=data;
	std::cout<<"your entered elements are:"<<"\n";
	
	for(int j=0;j<5;j++){
		
		cout<<*(p+j)<<"\n";
		
	}
	
	return 0;
}
