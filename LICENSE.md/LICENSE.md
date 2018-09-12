close all
clear all;
a0=input('enter the number');
a1=input('enter the second num');

x=(~a1)&(~a0);
y=(a1)&(~a0);
z=(~a1)&(a0);
w=(a1)&(a0);

result=[x y z w];
sprintf('%d %d %d %d',result)
