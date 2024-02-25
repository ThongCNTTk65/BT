#include <iostream>
using namespace std;
bool isPrime(int number){
   if(number <=1){
      return false;
  }

  for (int i = 2;i*i <= number;++i){
      if(number % i ==){
        return false;
      }
}

return true;
}
int main(){
  int n;
  cout<<"Nhập n:";
  cin>>n;

  cout<<"Các nguyên tố nhỏ hơn"<<n<< "là:";
  for(int i = 2; i<n;++i){
      if(isPrime(i)){
      cout<<i<" ";
    }
  }
return 0;
}
