﻿# Code-Hunt-Solution

+ Sector01 ARITHMETIC
+ Sector02 LOOPS
+ Sector03 LOOPS2
+ Sector04 CONDITIONALS
+ Sector05 CONDITIONALS2
+ Sector06 STRINGS
+ Sector07 STRINGS2
+ Sector08 NESTED LOOPS
+ Sector09 ARRAYS
+ Sector10 JAGGED ARRAYS
+ Sector11 ARRAYS2
+ Sector12 SEARCH SORT
+ Sector13 CYPHERS
+ Sector14 PUZZLES

Sector01 ARITHMETIC
```Java
    01.01   
    return -x;
    
    01.02
    return x-2;
    
    01.03
    return x*x;
    
    01.04 
    return x*3;
    
    01.05 
    return x/3;
    
    01.06
    return 8/(x*2);
    
    01.07
    return x-y;
    
    01.08
    return x+2*y;
    
    01.09
    return x*y;
    
    01.10
    return x+y/3;
    
    01.11
    return x/y;
    
    01.12
    return x%3;
    
    01.13
    return x%3 + 1;
    
    01.14
    return 10%x;
    
    01.15
    return (x+y+z)/3;
```

Sector 02 Loops
```Java
    02.01
    int[] a = new int[n];
    for ( int i=0; i<n; i++){
        a[i] = i;
    }
    return a;

    02.02
    int[] a = new int[n];
    for(int i=0; i<n; i++){
        a[i] = i*n;
    }
    return a;

    02.03
    int[] a = new int[n];
    for(int i=0; i<n; i++){
        a[i] = i*i;
    }
    return a;

    02.04
    int result = 0;
    for( int r : v){
        result += r;
    }
    return result;

    02.05
    int result =0;
    for(int i=0; i<n; i++) result+=i*i;
    return result;

    02.06
    int count =0;
    for(char ss:s){
        if(ss=='a') count++;
    }
    return count;

    02.07
    int count = 0;
    for(char ss:s){
        if(ss==x){
            count++;
        }
    }
    return count;
```
Sector 03 Loops2
```Java
    03.01
    if(power==0) return 1;
    int res = 1;
    for(int i=0; i<power; i++){
        res *= number;
    }
    return res;

    03.02
    int res = 1;
    for (int a=i; a>0; a--){
        res *= a;
    }
    return res;

    03.03
    int res =1 ;
    for(int i=lowerBound ; i<= upperBound; i++)
    {
       res *= i;
    }
    return res;

    03.04
    if (n < 3){
    return 0;
    }
    int r = 0;
    for(int i = 0; (i*2) < n; i++){
    r = r + (i*2); 
    } 
    return r; 

    03.05
    int r = 0;
    for(int i = 0; i <= upperBound; i++){
        for(int a = 0; a < i; a++){
            r += a;
            }
        r += i;
        }
    return r;

    03.06
    String r = "";
    for(int i = 0; i <  word.length(); i++){
        if (i == word.length() - 1)
        r = r + "_";
        else
        r = r + "_ ";
        }
    return r;

    03.07
    int m = 5;
    char[] c = new char[s.length()];
    for(int i = 0; i < s.length(); i++){
       int newValue = (((int)s.charAt(i))+m-(int)'a')%26+(int)'a';
       c[i] = (char)newValue;
    }
    return new String(c);

    03.08
    int count=0;
    while(x>0){
        x = x/10;
        count++;
    }

    return count;
```
Sector 04 Conditions
```Java

```
```Java

```
```Java

```
```Java

```
```Java

```
```Java

```
```Java

```
```Java

```
```Java

```
