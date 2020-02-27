# PythonLaunchpad
Start multiple py files one time

file name = file1.py
import time
print("test1 start")
for i in range(1,10):
	print("test1"+str(i))
	time.sleep(2)
  
file name = file2.py
import time
print("test2 start")
for i in range(1,10):
	print("test1"+str(i))
	time.sleep(3)
  
file name = start.py
import os
os.system(r'start /b python file1.py')
os.system(r'start /b python file2.py')

run start.py in cli:
test1 start
test2 start
test21
test12
test22
test13
test14
test23
test15
test24
test16

file1.py and file2.py running in the background at the same time.
