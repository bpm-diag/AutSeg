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
- edit the file *<app.properties>* accordingly with the desired properties:
  - **input_log**: the file path of the input UI log in XES format.
  - **tasks**: the file paths to the routine segments as PNML objects.

### 1. **Installation**
- compile source files into a generated JAR (i.e., *<segmentation.jar>*)
- put file *<segmentation.jar>* in the same directory of *<app.properties>*

### 2. **Execution**
- java -jar *<segmentation.jar>*







