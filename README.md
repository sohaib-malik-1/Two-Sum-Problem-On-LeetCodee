# Two-Sum-Problem-On-LeetCodee
Easiest Solution of Two Sum Problem of LeetCode

#include<iostream>
using namespace std;
int main()
{
	int arr[]={2,7,11,15,2};
	 int target=91;
	 int i, j, n;
	 bool found = false;
	 n= sizeof(arr)/sizeof(arr[0]);
	 for (i=0;i<n-1;i++)
	 { j=i+1;
	 	while(j!=n+1)
	 	{
	 		if (arr[i]+arr[j]==target)
	 	{
		 
	 		cout<<i<<" & "<<j << " are the indexes ";
	 		found = true;
	 	}
		 
		 j++;
	};
	
	 };
	 if(!found)
	 {
	 	cout<<"Not Found";
	 }
	 
}
