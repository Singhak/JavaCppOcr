# JavaCppOcr
This is an example of tesseract using javacpp lib for runnig tesseract code using java for running at  linux, window platform

### lib folder
- The lib folder contain all lib wich are required to run the project at linux/window for x86/64 bit.
- You can remove x86 libs if you are runnig at 64 bit processor.
- If you are running at window then remove linux libs
- Must keep for all versil libs **javacpp-1.3.3.jar**, **leptonica-1.73-1.3.jar**, **tesseract-3.04.01-1.3.jar** and other libs depends on which operating system you are running.

### tessdata
- keep this folder. It is required for traning purpose of tessrecat
- Currently in that folder only english language traning data set but you can use other language also

### Project setup instructions

**NetBeans (Java SE 7 or newer):**
- In the Projects window, right-click the Libraries node of your project, and select "Add JAR/Folder...".
Locate the JAR files, select them, and click OK.

**Eclipse (Java SE 7 or newer):**
- Navigate to Project > Properties > Java Build Path > Libraries and click "Add External JARs...".
Locate the JAR files, select them, and click OK.

#### For futher info goto [javacpp-presets](https://github.com/bytedeco/javacpp-presets)
