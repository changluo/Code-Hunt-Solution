# Code-Hunt-Solution Sector01-14

+ [Sector01 ARITHMETIC](#Sector 01 ARITHMETIC)
+ [Sector02 LOOPS](#Sector 02 LOOPS)
+ [Sector03 LOOPS2](#Sector 03 LOOPS2)
+ [Sector04 CONDITIONALS](#Sector 04 CONDITIONALS)
+ [Sector05 CONDITIONALS2](#Sector 05 CONDITIONALS2)
+ [Sector06 STRINGS](#Sector 06 STRINGS)
+ [Sector07 STRINGS2](#Sector 07 STRINGS2)
+ [Sector08 NESTED LOOPS](#Sector 08 NESTED LOOPS)
+ [Sector09 ARRAYS](#Sector 09 ARRAYS)
+ [Sector10 JAGGED ARRAYS](#Sector 10 JAGGED ARRAYS)
+ [Sector11 ARRAYS2](#Sector 11 ARRAYS2)
+ [Sector12 SEARCH SORT](#Sector 12 SEARCH SORT)
+ [Sector13 CYPHERS](#Sector 13 CYPHERS)
+ [Sector14 PUZZLES](#Sector 14 PUZZLES)

##Sector 01 ARITHMETIC
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
##Sector 02 LOOPS
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
##Sector 03 LOOPS2
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
##Sector 04 CONDITIONALS
```Java
    04.01
    return x|y;
    
    04.02
    return x&&y;
    
    04.03
    if (x < 50){
    return true;
    }
    return false;
    
    04.04
    if(x<y) return true;
    return false;
    
    04.05
    if(i==0) return 0;
    else if(i>0) return 1;
    else return -1;
    
    04.06
    if(i<j) return false;
    return true;
    
    04.07
    if(i>=100) return 3;
    else return 2;
    
    04.08
    
    if(i%2==0) return "even";
    else return "odd";
    
    04.09
    if(i%5==0)  return "multiple of 5";
    else return "not a multiple of 5";
    
    04.10
    if(i%x==0) return "multiple of " + x;
    else return "not a multiple of " + x;
    
    04.11
    if(i % 4 == 0 && i == (j*2) && j % 2 == 0 && k == (j/2)){
    return "yes!";
    }
    return "no";
    
    04.12
    int output = 21;
    if(i <= 7){
     return 0;
    }
    if(i > 7 && i <= 14){
    return 7;
    }
    return output;
```
##Sector 05 CONDITIONALS2
```Java
    05.01 
    if(s.length()<4) return "short";
    else if (s.length()<8) return "average";
    else if (s.length()<15) return "long";
    else return "super long";

    05.02
    if( i% 1111 == 0) return "fancy year";
    return "not a fancy year";

    05.03
    return a*a-b*b+c*c==0||a*a+b*b-c*c==0||b*b+c*c-a*a==0;

    05.04
    if(x<0&&y<=0) return -(x+y);
    if(x<0&&y>=0) return -(x-y);
    if(x>=0&&y<=0) return -(y-x);
    return x+y;

    05.05
    if(i*i == j)    return true;
    else    return false;
```
##Sector 06 STRINGS
```Java
    06.01
    return false;
    
    06.02
    String res = "";
    for(int i = 0; i < s.length(); i++){
        if(i%2 == 0 )       res += s. substring(i,i+1).toUpperCase();
        else         res += s. substring(i,i+1);
     }  
     return res;
    
    06.03
        String res ="";
        for(int i=0, j=1; i<s.length()-1; i++, j++){
            if(s.charAt(j) ==' '){
            res += s.substring(i,i+1).toUpperCase();
            }
            else res += s.substring(i,i+1);
        }
        res += s.substring(s.length()-1,s.length()).toUpperCase();
        return res;
    
    06.04
        return s.charAt(x);
    
    06.05
        return two+one;
    
    06.06
        return s.substring(s.length()/2);
    
    06.07
        String res = "";
        res = s.substring((s.length()/2)+1).toUpperCase();
        res += s.substring(s.length()/2);
        return res;
    
    06.08
        return Math.max(a.length(), b.length());
    
    06.09
        if(a.length() > b.length())        return a;
    
        if(b.length() > a.length())        return b;
        return a + b;
    
    06.10
        int count=0;
        int a =s.length();
        while(a>2) {
            count++;
            a-=3;
        }
        return count;
    
    06.11
        return s.substring(i, s.length() - 1) + s.substring(j, s.length() - 1 ); 
    
    06.12
        for(int i=s.length()-1; i>=0; i--){
            s+=s.charAt(i);
        }
        return s;
```
##Sector 07 STRINGS2
```Java
    07.01
        return two+three+one+one+three+two;
    
    07.02
        return s.substring(0,s.length()/2);
    
    07.03
         return a.replace(b,c);
    
    07.04
        import java.io.*;
        import java.util.*;
    
        StringBuilder input1 = new StringBuilder();
        input1.append(s);
        input1.reverse();
        return input1.toString();
    
    07.05
        String res = "";
        for (int i=0; i<a.length(); i++){
            if(i%2==0) res +=b.substring(i,i+1);
            else  res +=a.substring(i,i+1);
        }
        return res;
    
    07.06
        return s.replace(" ","");
    
    07.07
         return s.replace("a", "").replace("e", "").replace("i", "").replace("o", "").replace("u", "");
    
    07.08
        String res = "";
        res = input.replace(a, "").replace(b, "").replace(c, "");
        if (res == "" && input.contains(a) && input.contains(b) && input.contains(c)){
        return true;
        }
        return false;
    
    07.09
        String res = "";
        for(int a=0;a<i-1;a++){
            res += s + " ";
        }
        return res + s;
    
    07.10
         String output = "a b c d e f g h i j k l m n o p q r s t u v w x y z";
         if (t==1) return output;
         String r = "";
         for(int i = 0 ; i<t-1 ; i++){
             r += output + " ";
         }
         r+=output;
    
         return r.substring(0, 52*t-t*2)+"z";
```
##Sector 08 NESTED LOOPS
```Java
    08.01
        public static int Factorial(int x) {
        if (x == 1)
        return 1;
        return x*Factorial(x-1);
        }
        public static int Puzzle(int i, int j) {
        int sum = 0;
        for (int s=i; s<=j; s++)
            sum += Factorial(s);
            return sum;
        }
    
    08.02
        String output = "";
        for(int i = 1; i <= n; i++){
            output += new String('#', i) + " ";
        }
        return output;
    
    08.03
        String output = "";
        for(int i = n; i >= 0; i--){
            for(int a = 0; a <= n - i; a++){
                output += a;
            }
            output += new String('_', i ) + " ";
        }
        return output;
    
    08.04
        String res = "";
        for (int i = 0; i < n; i++){  
            for (int a = 0; a < n; a++){
                if (i == a) res += "-";
                else  res += b;
            }
            res += " ";
        }
        return res.trim();
    
    08.05
        String r = "";
        for (int i = 0; i < a.length(); i++){
            for (int b = 0; b < a.length(); b++){
                if (i == b)  r += "_";
                else  r += a.substring(b,b+1);
            }
            r += " ";
        }
        return r.trim();
    
    08.06
        String res = "";
        for (int i = 0; i < size; i++){
            for (int b = 0; b < size; b++){
                if ((i == 0 || i == size -1 ) || (b == 0 || b == size -1) ){
                    res += "$";
                } 
                else  res += "_";
            }
            res += " ";
        }
        return res.trim();
    
    08.07
        String output = "";
        String next = "x";
        for(int i = 0; i < height; i++){
            if (i % 2 == 0) next = "x";
            else   next = "o";
            for(int b = 0; b < width; b++){
                output += next;
                if (next == "x")   next = "o";
                else   next = "x";
                if ((b +1) % width == 0)
                output += " ";
            }
        }
        return output.trim();
    
    08.08
        String output = "";
        for(int i=1; i<=number; i++){
           String a = String.valueOf(i);
           output += new String(a.toCharArray()[0], i) + " ";
        }
        for(int i=number -1 ; i>0; i--){
           String a = String.valueOf(i);
           output += new String(a.toCharArray()[0], i) + " ";
        }
        return output.trim();
```
##Sector 09 ARRAYS
```Java
    09.01
        return list[i];
    
    09.02
        return list[0] + list[list.length - 1];
    
    09.03
        for(int a:list){
           if(a==i)
           return true;
        }
        return false;
    
    09.04
        return new int[]{x,x,x,x,x,x,x,x,x,x};
    
    09.05
        int[] res = new int[n];
        for(int i=0;i<n;i++){
            res[i]=i;
        }
        return res;
    
    09.06
        return new Boolean[] {true,true,true,true,true,true,true,true,true,true};
    
    09.07
        String [] res = new String [s.length()];
        for(int i = 0; i < s.length(); i++){
            res[i] = ""+s.charAt(i);
        }
        return res;
    
    09.08
        int[] res = new int[n+1];
        for(int i=n, j=0; i>0; i--,j++){
            res[j]=i;
        }
        return res;
    
    09.09
        for(int i = 0; i < numbers.length; i++){
            numbers[i] = -numbers[i];
        }
        return numbers;
    
    09.10
        for(int i = 0; i < numbers.length/2; i++)
        {
            int temp = numbers[i];
            numbers[i] = numbers[numbers.length - i - 1];
            numbers[numbers.length - i - 1] = temp;
        }
        return numbers;
    
    09.11
        char[] c = new char[s.length()];
        for(int i=s.length()-1,j=0;i>=0;i--,j++)
        {
               c[j]=s.charAt(i);
        }
        return new String(c);
    
    09.12
        for (int x = 0; x < amount; x++){ 
            int t = numbers[numbers.length - 1];
            for (int i = numbers.length - 1; i > 0; i--){
                numbers[i] = numbers[i - 1];
            }
            numbers[0] = t;
        }
        return numbers;
    
    09.13
        int r = 0;
        r = numbers[i];
        numbers[i] = numbers[j];
        numbers[j] = r;
        return numbers;
    
    09.14
       int l = Math.max(a.length,b.length);
       int[] res = new int[l];
       for(int i=0;i<l;i++){
           if(i<a.length) res[i] +=a[i];
           if(i<b.length) res[i] +=b[i];
       }
       return res;
```
##Sector 10 JAGGED ARRAYS
```Java
    10.01
        return list[i][j];
    
    10.02
        int[][] res = {
            new int [5], new int [5],
            new int [5],
            new int [5],
            new int [5]
        };
         return res;
    
    10.03
        int[][] res = new int [length][];
        for(int i = 0; i < length; i++){
            res[i] = new int [length];
            for(int j = 0; j < length; j++){
                res[i][j] = x;
            }
        }
        return res;
    
    10.04
        int[][] res = new int[input.length][];
        for(int i=0;i<input.length;i++){
            res[i] = new int[input.length];
            for(int j=0;j<input.length;j++){
                res[i][j] = 2*input[i][j];
            }
        } 
        return res;
    
    10.05
        int count = 0;
        for(int a = 0; a < input.length; a++){
            for(int j = 0; j < input[a].length; j++){
                int n =  input[a][j];
                if (n == i)
                count++;
            }
        }
        return count;
    
    10.06
        int count = 0;
        for(int a = 0; a < input.length; a++){
            for(int j = 0; j < input[a].length; j++){
                int n =  input[a][j];
                if (n > count)
                count = n;
            }
        }
        return count;
    
    10.07
        int[] res = new int [input[0].length];
        int maxAverage = 0;
        for(int a = 0; a < input.length; a++){
            int average = 0;
                for(int j = 0; j < input[a].length; j++){
                    average += input[a][j];
                }
            if(average > maxAverage){
            maxAverage = average;
            res = input[a];
            }
        }
        return res;
    
    10.08
       int[] temp = new int[input[0].length] ;
       for(int i=0; i<input[0].length; i++){
           for(int j=0; j<input.length; j++){
               temp[i] +=input[j][i];
           }
       }
    
       int max =0;
       for(int i=0; i<temp.length; i++){
           if(max < temp[i])
           max = temp[i];
       }
       return max;
```
##Sector 11 ARRAYS
```Java
    11.01
      int length = Math.max(a.length,b.length);
      int[] res = new int[length];
      for(int i = 0; i < length; i++){
        if(a.length <= i){
          res[i] = Math.abs(b[i]);
          continue;
        }
        if(b.length <= i){
          res[i] = (a[i]);
          continue;
        }
        res[i] = Math.abs(b[i] - a[i]);
      }
      return res;
    
    11.02
      int total =  a.length * amount;
      String[] res = new String [total];
      int n = 0;
      for(int i = 0; i < a.length; i++){
        for(int j = 0; j < amount; j++){
          r[n++] = a[i];
        }
      }
      return res;
    
    11.03
        int sumA =0;
        int sumB =0;
        for(int i=0; i<input.length;i++){
            sumA += input[i][i];
            sumB += input[i][input.length-i-1];
        }
        return sumA==sumB;
    
    11.04
        for(int i=0; i<list.length; i++){
            list[i]= list[i]%modBy;
        }
        return list;
    
    11.05
      String[] res = new String[(list.length+1)/2];
      for(int i = 0, j = 0; i < list.length; i = i + 2, j++){
        if(i >= list.length - 1)  r[j] = list[i]; 
        else r[j] = list[i] + list[i + 1];
      }
      return res;
    
    11.06
        String []res = new String [grades.length];
        for(int i = 0; i < grades.length; i++){
          if(grades[i] >= D)   res[i] = "D";
          if(grades[i] >= C)   res[i] = "C";
          if(grades[i] >= B)   res[i] = "B";
          if(grades[i] >= A)   res[i] = "A";
          if(grades[i] < D)    res[i] = "E";
        }
        return res;
    
    11.07
      String [][]res = new String[input.length][];
      for(int i = 0; i < input.length; i++){
        res[i] = new String[input.length];
        for(int j = 0; j < input.length; j++){
          res[i][j] = input[j][i];
        }
      }
      return res;
```
##Sector 12 SEARCH SORT
```Java
    12.01
      int count = 0;
      for(int n : numbers){
        if(x == n)
        count++;
      }
      return count;
    
    12.02
      int count = 0;
      for(String n : words){
        if(n == s)    count++;
      }
      return count;
    
    12.03
      int j = 0;
      for(int i = 0; i < numbers.length; i++){
        if(numbers[i] == x){
          j = i;
          break;
        } else {
            j = -1;
          }
      }
      return j;
    
    12.04
      int j = 0;
      for(int i = numbers.length - 1; i > -1; i--){
        if(numbers[i] == x){
          j = i;
          break;
        } else {
            j = -1;
          }
      }
      return j;
    
    12.05
      int count =0;
      for(int i = 0; i < numbers.length; i++){
        if(numbers[i] == x){
          count++;
        }
      }
      int []res = new int[count];
      for(int i = 0, j = 0; i < numbers.length; i++){
        if(numbers[i] == x){
          res[j] = i;
          j++;
        }
      }
      return res;
    
    12.06
        for (int i =0;i<numbers.length;i++){
            if(numbers[i]==x){
                numbers[i]=y;
            }
        }
        return numbers;
    
    12.07
        public static int[][] Puzzle(int[] numbers, int x) {
        int[][] result = new int[0][];
        for(int i=0;i<numbers.length;i++){
            for(int j=i+1;j<numbers.length;j++){
                if(numbers[i]+numbers[j]==x){
                    result = copyOf(result,result.length+1);
                    result[result.length-1] = new int[]{i,j};
                }
            }
        }
        return result;
    }
    public static int[][] copyOf(int[][] input, int newLength){
        int[][] result = new int[newLength][];
        for(int i=0; i<input.length;i++){
            result[i]= input[i];
        }
        return result;
        }
    
    12.08
        int sum=0;
        for(int i:numbers){
            sum += i;
        }
        int presum=0;
        for(int i=0;i<numbers.length;i++){
            presum += numbers[i];
            if(presum*2==sum){
                return i;
            }
        }
        return -1;
    
    12.09
        for(int i =1 ; i<numbers.length; i++){
            if(numbers[i]<numbers[i-1]) return false;
        }
        return true;
    
    12.10
         for(int i=1; i<words.length; i++){
             if(!words[i].contains(words[i-1])) return false;
         }
         return true;
    
    12.11
    import java.util.Arrays;
        Arrays.sort(a);
        return a;
    
    12.12
    import java.util.Arrays;
      for(int j=0; j<a.length;j++){
        for (int i=j+1 ; i<a.length; i++){
          if(a[i].compareTo(a[j])<0){
            String temp= a[j];
            a[j]= a[i]; 
            a[i]=temp;
          }
        }
      }
      return a;
```
##Sector 13 CYPHERS
```Java
    13.01
        char[] c = new char[s.length()];
        for (int i=0; i<s.length(); i++){
            int ci = (s.charAt(i)-90)%26+97;
            c[i] = (char)ci;
        }
        return new String(c);
    
    13.02
        char[] c = new char[s.length()];
        for( int i=0; i<s.length(); i++){
            int ci = (s.charAt(i)-45)%79+48;
            c[i] = (char)ci;
        }
        return new String(c);
    
    13.03
        char[] c = new char[s.length()];
        int x = 1;
        for(int i=0; i<s.length(); i++){
            c[i] = (char)((s.charAt(i)-97+x)%26+97);
            x += 4;
        }
        return new String(c);
    
    13.04
        char[] c = new char[s.length()];
        int[] x = new int[]{2,3,19,19};
        for(int i=0; i<s.length(); i++){
            c[i]=(char)((s.charAt(i)+x[i%x.length]-97)%26+97);
        }
        return new String(c);
```
##Sector 14 PUZZLES
```Java
    14.01
        return x * (x + 1) / 2;
    
    14.02
        return (x * ((x*x) + 1)) / 2;
    
    14.03
        if(f == 1) return false;
        else if(isPrime(f)) return x%f ==0;
        else return false;
        }
        public static boolean isPrime(int n){
        for(int i=2; i<n; i++){
           if(n%i == 0){
              return false;
           }
        }
        return true;
    
    14.04
        String res = "";
        for(int i=0; i<s.length(); i+=2){
            int c = s.charAt(i);
            int cc =(i+1<s.length())?s.charAt(i+1): c;
            char r = (char)((c+cc)/2);
            res += r;
        }
        return res;
    
    14.05
        int count =0;
        for(int i=0; i<list.length; i++){
            boolean b = false;
            for(int j=0; j<i; j++){
                if(list[i]==list[j]) b=true;
            }
            if(b!=true) count++;
        }
        return count;
    
    14.06
    public static int[] Puzzle(int[] list) {
            int[] res = new int[0];
            for(int i=0; i<list.length; i++){
                boolean b = false;
                for(int j=0; j<i; j++){
                    if(list[i]==list[j]) b=true;
                }
                if(b!=true){
                    res = create(res , res.length+1);
                    res[res.length-1] = list[i];
                }
            }
            return res;
        }
        public static int[] create(int[] res, int length){
            int[] result = new int[length];
            for(int i=0; i<res.length; i++){
                result[i] = res[i];
            }
            return result;
    
    14.07
        for(int i=0; i<s.length()/2; i++){
            if(s.charAt(i) != s.charAt(s.length()-1-i)){
                return false;
            }
        }
        return true;
    
    14.08
        public static Boolean Puzzle(String a, String b) {
            return a.equals(b) || a.equals(reverse(b));
        }
        public static String reverse(String s){
            String res = "";
            for(int i =s.length()-1; i>=0; i--){
                res += s.charAt(i);
            }
            return res;
    
    14.09
        if(slope1 == slope2 && yintercept1 == yintercept2) return "same line";
        else if (slope1 == slope2) return "parallel lines";
        else{
            double x = (yintercept2 - yintercept1) / (double)(slope1 - slope2);
            double y = slope1*x + yintercept1;
            return "(" + x + ", " + y + ")";
```
