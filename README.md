/*#include<iostream>
#include<conio.h>
using namespace std;
void rotate(int a[],int n){
    int i,j,first;
    int d;
    cout<<"Enter the times of rotation: "<<endl;
    cin>>d;
    for(i=0;i<d;i++){
        first=a[0];
    }
    for(j=0;j<n-1;j++){
        a[j]=a[j+1];
    }
    a[j]=first;
}
void printArray(int a[], int n){
    for(int i=0;i<n;i++){
        cout<<a[i]<<" ";
    }
}
int main(){
    int a[]={45,47,78,95};
    int n=sizeof(a)/sizeof(a[0]);
    rotate(a,n);
    cout<<"rotated arr
