#include <iostream>
using namespace std;
int main()
{
  double arr[5];
  double sum;
  double avg;
  cout<<"enter five numbers:";
  for(int i=0;i<5;i++)
  {
    cin>>arr[i];
  }
  sum=0;
  for(int i=0;i<5;++i)
  {
    sum+=arr[i];
  }
  avg=sum/5;
  cout<<"sum="<<sum<<endl;
  cout<<"average="<<avg<<endl;
  return 0;
}

