# FIDS_Monitoring
Attached python script (in txt format) which can be added to the windows scheduler to run at scheduled time. The output file will give you the Active and Inactive DDC device Ip address in the terminal including their location.  It helps the team to monitor all the FIDS screen from one location. 

1.	IXE_Input_file.csv contains Ip address and their location – (test file attached and can be replaced with actual DDC Ip address and locations of IXE Airport)
2.	Save the file with .CSV extension.
3.	In the script (Script) I have configured to send 2 echo requests and wait until 35milliseconds for each reply- This can be configurable as per our requirement. Line no 14 in the script file can be changed accordingly. 
4.	Output will be save in .CSV format with the filename as DDMMYYYHHMMSS

Requirements:
1.	Python 3.8.2 to be installed in the system.
2.	Pandas library should be installed to run the script. 

Note: Script.txt should be renamed as Script.py – I have converted into txt format due FW issues in case. 
