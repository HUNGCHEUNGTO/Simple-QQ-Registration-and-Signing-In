# Simple-QQ-Registration-and-Signing-In

First, input a positive integer N, which is the number of command. 
The code will give different information based on the command.
If the accound registration is valid, "New: OK" is ouputted.
If the accound already existed, "ERROR: Exist" is outputted.
If an existing account signed in successfully, "Login: OK" is outputted.
If the user signs in an account that does not exist, "ERROR: Not Exist" is outputted.
If the user enters wrong a password, "ERROR: Wrong PW" is outputted.

Sample Run:\n
5
L 1234567890 myQQ@qq.com
N 1234567890 myQQ@qq.com
N 1234567890 myQQ@qq.com
L 1234567890 myQQ@qq
L 1234567890 myQQ@qq.com
Sample Output: 
5
ERROR: Not Exist
New: OK
ERROR: Exist
ERROR: Wrong PW
Login: OK
