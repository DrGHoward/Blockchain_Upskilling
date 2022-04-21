# Python Blockchain Prototype
_______

A build of a blockchain-based ledger system MVP, complete with a user-friendly web interface. This ledger allows audeience to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.


## Steps to run the application:
__________________________________
### Installations
* Open Anaconda terminal and pass the commands in order
```python
conda create -n env_whatever_name python==3.7
conda activae env_whatever_name
pip install streamlit
pip install datetime 
pip install pandas 
pip install hashlib
```
### Path Setting

* Save the folder you cloned on your desktop and `cd` to `~/Desktop/Blockchain_Upskilling/Python_Blockchain_Prototype`

### Run

* Pass in next command in same open terminal after completing prior steps in order

```python
streamlit run pychain.py
```
### Executable File

This file is custom to the path of where you saved this code. I have it set to point to my directory. Thus edit it in notebad or vscode 
to set right path and right conda env name and save file as "executable.bat". Make sure to wrape the name between two "" in order for it
to convert to a .bat(batch) windows execuatble file.

