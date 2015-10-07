# **Requirements Document -- Team 01**

##1 User Requirements

###1.1 Software Interfaces

The software will **NOT** interact with any external systems/libraries.

### 1.2 User Interfaces

1. The program interacts with users through the command line.

### 1.3 User Characteristics

The intended users of this product are high school students of varying levels of technical skill. The students should at minimum know how to run applications from the command line and pass file paths as arguments to a program.

## 2. System Requirements
 
### 2.1 Functional Requirements

* **One document / Multiple documents per student**: The program takes a single document as input.

* **Hosted online or distributable**: Executable on a local machine.

* **Packaged as**: A single *jar* file.

* **What constitutes a word**: A sequence of characters (derived from ASCII alphabet) that do not have any spaces, tabs, newlines or a combination of the three is defined as a word. The number of letters has to be greater than or equivalent to the minimum word length.

* **Output**: Outputs the average number of words per sentence in the console

* **Default sentence delimiters are: . ? ! ;**

* **Optional list of delimiters**: Users can optionally pass a list of delimiters with the `-d` flag.

* **Default minimum length for a word**: 3

* **Optional minimum length for a word**: Users can optionally specify a different minimum length for a word with the `-l` flag.

* **Rounding off mode for output**: Rounded down.

* **Relative file path or absolute file path:**: Both

* **OS dependent end line delimiter**: Should be able to handle for all the Operating systems.

* **Input File format**: Raw text file. Import it as a stream.

* **OS dependent file paths**: Should handle both forward slash and backslash.

* **Prints the following error messages**:
  	 1. Unreadable input file: `ERROR: Unable to read the input file`
  	 2. Nonexistent file: `ERROR: Unable to process input file`
  	 3. Bad arguments: `ERROR: Ill-formed command`
  	 4. Program terminates with an exception: `ERROR: Program terminated unexpectedly`

* **File size limit**: No max limit to the file size.

* **Words - capital or small/mix**: Both.

###2.2 Non-Functional Requirements

* **Performance Benchmarks**: No performance benchmarks for now, will be taken into consideration once the product is scaled.

* **Duration of the Project**: 1 week for implementation and 1 week for documentation.

* **Security**: No special security requirements.

* **Foreseeable expansions for the project**: No for this moment. 

