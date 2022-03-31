# Sum-of-Even-Numbers-till-N
/* Given a number N, print sum of all even numbers from 1 to N.
Input Format :
Integer N
Output Format :
Required Sum 
Sample Input 1 :
 6
Sample Output 1 :
12 */



#include<iostream>
using namespace std;
int main()
{
    int n=2,sum=0;
  //  cout<<"Enter n"<<endl;
    cin>>n;
    int i=0;
    while(i <=n)
    {
        if(i%2==0)
        {
            sum =sum+i;       
        } 
        i++;
    
    }
    cout<<sum;

}
	
