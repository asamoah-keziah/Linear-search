#include <iostream>



int main(int argc, char** argv) {
    double values[5] = {2,34,2,213};
    double min = values[0];
    
    for(int i = 1; i < 5; i++){
    	if(values[i] < min){
    		min = values[i];
		}
	}
	
	cout << min << endl;
	return 0;
}
