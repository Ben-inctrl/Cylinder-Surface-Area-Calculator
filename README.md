# Cylinder-Surface-Area-Calculator
A program that receives radius and height inputs and calculates the surface area of a cylinder

#include <iostream>
using namespace std;

double cylinderSA(float radius , float height){
    return (2*radius*3.14*height)+(2*3.14*radius*radius);
}


int main(){
    
    float r,h,result;
    cout<<"Enter the radius:"<<endl;
    cin>>r;
    cout<<"Enter the height of a cylinder:"<<endl;
    cin>>h;
    
result = cylinderSA(r,h);

cout<<"The surface area is:"<<result;
return 0;
}
