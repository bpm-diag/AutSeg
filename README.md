# Segments Discovery through Frequent-Pattern Identification

### 1. **Installation**
- cd src
- make
- make install
- make clean

### 2. **Execution**
- ./al -d *<config_file>*


# Trace Alignment

### 1. **Preparation**
- Download the pre-built [Fast-Downward planner](https://drive.google.com/file/d/0B0FHkIijDk2heXd1X2FaUmktRDQ/view).
- Unpack the .zip archive in the root folder of the Eclipse project. 
- For **Windows users** only: Download [standalone Python 2.7 interpreter](https://drive.google.com/file/d/0B0FHkIijDk2haVRxVE9ibzJXN00/view).
- For **Linux/Mac users** only: make sure that Python 2.7 interpreter is set as default.
- edit the file *<app.properties>* accordingly with the desired properties:
  - **input_log**: the file path of the input UI log in XES format.
  - **tasks**: the file paths to the routine segments as PNML objects.

### 1. **Installation**
- compile source files into a generated JAR (i.e., *<segmentation.jar>*)
- put file *<segmentation.jar>* in the same directory of *<app.properties>*

### 2. **Execution**
- java -jar *<segmentation.jar>*







