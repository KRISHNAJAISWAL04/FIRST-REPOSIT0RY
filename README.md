# FIRST-REPOSIT0RY
this is my first repository
<BR>
 #include<stdio.h>
int sum(int *,int*);
int average(int *);
int main(){
    int a,b,x;
    printf("enter the values of a and b");
    scanf("%d%d",&a,&b);
    x= sum(&a,&b);
    printf("the sum of two no. is %d\n",x);
    printf("average of two no is %d",average(&x));
    return 0; 
}

int sum(int*p,int*q){
    return *p +*q;
}
int  average(int*r){
    return *r/2;
}