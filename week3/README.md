# Shell Tools and Scripting  

## problem1  
![week4_1](./img/week3_1.png)

>solution `ls -alht`  

## problem2  
![week4_1](./img/week3_2.png)  

>solution `stat --printf="%y ./%n\n" $(ls -at $(find * -type f))`  

>`vi rf.sh`  

>```
>rf(){
>        stat --printf="%y ./%n\n" $(ls -at $(find * -type f))
>}
>``` 


>`source rf.sh`  
>`rf`