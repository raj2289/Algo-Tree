##Binary Search is use for searching element in sorted array.
##Binary Search is divide and conquir algorithm in begining it search in whole interval and than search size reduces to half.
-----------------Binary Search in C++----------------
#include<iostream>
using namespace std;

int main()
{
int size,ele;
cout<<"Enter the size of array:";
cin>>size;
int arr[size];
cout<<"Enter the elements of array:";
for(int i=0;i<size;i++)
  cin>>arr[i];
cout<<"Enter element to be search:";
cin>>ele;
int l=0,h=size;
while(l<h)
{
   int mid=(l+h)/2;
   if(arr[mid]==ele)
   {cout<<"element found at "<<mid;
   break;}
   if(arr[mid]>ele)
    {l=mid+1;}
   else
    {h=mid-1;}
}
 if(l>h)
 cout<<"Element NOt Found...";
 return 0;
}
    
****
Output:
Enter the size of array:5                                                                                  
Enter the elements of array:1 2 3 4 5                                                                      
Enter element to be search:2                                                                               
element found at 1 


Enter the size of array:5                                                                                  
Enter the elements of array:1 2 3 4 5                                                                      
Enter element to be search:6                                                                               
Element NOt Found...

Time complexity of searching-log(n)
           n-size of array
           
  
  
