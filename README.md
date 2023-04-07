# CTDL-GT_Linear_Recursion_2.cpp
Linear Recursion
Nguồn tham khảo : https://codehow.net/de-quy-tuyen-tinh-linear-recursion-trong-c-c++-87.html
Vi du : 

// ta co mot ham de quy tinh giai thua laf 1 ham de quy tuyen tinh: 

int factorial(int n)
{
    if(n == 0) return 1;
    return n * factorial(n-1);
}
