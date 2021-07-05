# Md5-hash-string-data
import hashlib
  
# encoding GeeksforGeeks using md5 hash
# function 
result = hashlib.md5(b'GeeksforGeeks')
  
# printing the equivalent byte value.
print("The byte equivalent of hash is : ", end ="")
print(result.digest())



output :
The byte equivalent of hash is : b'\xf1\xe0ix~\xcetS\x1d\x11%Y\x94\\hq'


import hashlib
  
# initializing string
str2hash = "GeeksforGeeks"
  
# encoding GeeksforGeeks using encode()
# then sending to md5()
result = hashlib.md5(str2hash.encode())
  
# printing the equivalent hexadecimal value.
print("The hexadecimal equivalent of hash is : ", end ="")
print(result.hexdigest())


output :
The hexadecimal equivalent of hash is : f1e069787ece74531d112559945c6871
