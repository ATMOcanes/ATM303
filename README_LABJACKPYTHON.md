# ATM303 resources for Jupyter notebooks 

### Download the ATMOcanes_environment.yml file into your class directory, then run  
conda env create -f ATMOcanes_environment.yml 

### Now let's enter that environment, and install the latest LabJackPython software (their published package forbids python=3)

#### Mac (bash shell)
source activate ATMOcanes
#### Windows 
activate ATMOcanes 

### Download a zipfile of the latest LabJackPython software with the big green button at 
https://github.com/labjack/LabJackPython

### Get yourself into the directory containg the LabJackPython-master folder, and type 
pip install pip install LabJackPython-master/

## Now your ATMOcanes environment contains this software, ready to use. 

