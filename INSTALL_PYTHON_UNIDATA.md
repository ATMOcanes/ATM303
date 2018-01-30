## Set up Jupyter+Python for class on your PC or Mac

#### These instructions are summarized from https://unidata.github.io/unidata-python-workshop/installation.html

--------------
   
   1. **Install** miniconda3, following directions at https://conda.io/docs/user-guide/install/index.html
   
   2. **Create** a high-level folder called Jupyter
   
   3. **Download** Unidata's stuff into the Jupyter folder. 
   
      - Navigate to https://github.com/Unidata/unidata-python-workshop
      - Hit the big green **Clone or download** button, then hit _Download ZIP_
      - In the downloads area, unzip the .zip file by double clicking it
      - Move its contents (a folder called unidata-python-workshop-master) into your Jupyter folder
       
   4. Open a **Terminal** (in Mac) or **Command Prompt** (in Windows). Then, type these things there: 
   
      * **cd (your_folder_path)/unidata-python-workshop-master** 
          - here, *(your_folder_path)* is probably *Jupyter* or *Desktop/Jupyter*

      * **conda env create -f environment.yml**
        - This will take several minutes as the unitata-workshop _environment_ is built. 

   5. To set your environment, type 
      * Windows: **activate unidata-workshop**
      * Mac (bash shell): **source activate unidata-workshop**
      
   6. The moment of truth! type 
      * **jupyter notebook**
      
---------------------
If you did it all right, a browser window should now pop up! 
You are ready to plot a sounding for class. 
