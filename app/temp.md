في الطريقة العادية : 
int temp = aorgi[h];
aorgi[h] = aorgi[u];
aorgi[u] = temp;

وفي طريقة اللي بحبوا يتحربقوا وما يعرفوا متحول جديد: 
aorgi[h] = aorgi[h] + aorgi[u];
aorgi[u] = aorgi[h] - aorgi[u];
aorgi[h] -= aorgi[u];