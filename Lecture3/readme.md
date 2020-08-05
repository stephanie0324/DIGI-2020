## Perl 筆記

* Basic rules of Perl
  * 註解 : 在前面加上 '#'
  * 變數與陣列
    * 變數 : '$'
    * 陣列 : '@' 
  * 結尾 : 需要加上一個 ';'

* 語法
  * if-else
  ```
  if(){}
  elsif(){}
  else(){}
  ```
  * for / foreach / while / do-until
  ```
  for(){}   # 很像 c++
  
  foreach $i (@list){ $sum = $sum + $i ;}
  
  while(){}
  
  do{}until()
  ```
  
  * input 
 ```
 $string = <STDIN>
 ```
 
 * shift / pop / unshift / unpop
 ![image](https://github.com/stephanie0324/DIGI-2020/blob/master/Lecture3/截圖%202020-08-05%20下午11.14.58.png)
 
 * string
  * join : array -> string
  * split : string -> array
 ```
 @list = qw(1 2 3 4); #qw 代表用空格來分隔元素
 
 $str = join(' ' , @arr);
 
 @arr = split('',$str);
 ```
 
 * file handle
 ```
 open(file, "<...")  # read file
 open(file, ">...")  # write file
 open(file, ">>...") # append file
 ```
 
 * hash
 ```
 %h = (k1 =>"1" ,k1 =>"1",k2 =>"b" , k3 => "3" );  # hash initialization
 ```
 key|value
 :-:|:-:
 k1|1
 k2|b
 k3|3
 
