## Linux 筆記
* The command line  
**ALL COMMAND NO UNDO**
  * ls man : show all the command
  * ls[options][location] : to see the files under this location  
  (用中括號的部份可填可不填)
  * pwd : print working directory  
  * $SHELL : print shell  
  * -a  
    * ' ? ' 指定幾個字
    * ' * ' 不確定字數
  * -l : prin more imformation about this file
  * ' . ' : current directory
  * ' .. ' : previous directory
  * mkdir : make directory
  * rmkdir : remove directory
  * touch :  create a blank file
  * rm : remove a file
  * cp : copy a file or directory
  * mv : move a file or rename a file
  ```
  mv 1.txt linux.txt                     #change name to linux.txt
  mv linux.txt /Users/stephanie/desktop  #move the file to desktop
  ```
  * cd - : move to the previous directory
  * permissions
    * chmod : change permissions
    * ls -Id : view the permissions for the selected file
    * r : read
    * w : write
    * x : execute
    * 判斷 (更改的時候 chmod g+x : 就是將group 的權限增加一個x，以此類推。）
      * user : 最前面
      * group :中間
      * other : 其他人
    * cat : print the data
    * tac : print the data in reverse
    * -n "n" : 將檔案的前 "n" 行印出來
    * nl : print line numbers before data
    * wc : print a count of lines , words , and characters.

