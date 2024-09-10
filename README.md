# CSE2102_Lab1
Lab 1

## 1. Install JUnit and Hamcrest
CodeSpace> wget https://repo1.maven.org/maven2/junit/junit/4.13.2/junit-4.13.2.jar
CodeSpace> wget https://repo1.maven.org/maven2/org/hamcrest/hamcrest-
core/1.3/hamcrest-core-1.3.jar

## 2. Create a directory src, and inside that directory create a directory c.

## 3. Upload files from CSE2102_Lab1 into directory c.

## 4. Compile the files: 
$ javac -cp "junit-4.13.2.jar:hamcrest-core-1.3.jar" ./src/c/HybridTests.java ./src/c/Hybrid.java ./src/c/ElectricInterface.java ./src/c/GasolineInterface.java ./src/c/CarRunner.java
(Note that HybridCar wasn't compiled, as that part of the lab was implemented in CarRunner.java

## 5. To run the HybridTest, go to the directory that contains JUnit and Hamcrest and run
$ java -cp "junit-4.13.2.jar:hamcrest-core-1.3.jar:./src/c/" org.junit.runner.JUnitCore HybridTests
