Download Link: https://assignmentchef.com/product/solved-sprint3-v1-solution
<br>
In this week’s team sprint assignment I need to complete two tasks (tasks 3 and 4 below). We need to add code to an existing unit test to set the input parameters for the function to be tested, and set the expected variable(s) for the value to be returned. The code is already there to compare your expected value to the actual value returned by the function being tested. The code to load the array values for Hubs has been moved into its own function so that the unit tests will work correctly and to pave the way for next week’s sprint. If you get stuck modifying your own unit test, you may want to look at the unit test, ValueOfTest1, for inspiration, since this unit test has been completed for you. Notice that the call to the Assert.Inconclusive method has been commented out.Story: As a system administrator, I want a unit testing framework for easier testing and independence when writing code. My tasks are relatively simple, but I’m having trouble writing the code correctly.

Task 3:          Add a unit test for the CoordinateToDegrees function to assure that coordinates are transformed to decimal degrees correctly.

Task 3a:         Right click anywhere within the CoordinateToDegrees function in Airports.vb and add a unit test named CoordinateToDegreesTest to the unit test framework. (This has been done for you.)

Task3b: Modify the code in CoordinateToDegreesTest to assert that

DegreeString =  “33° 38′ 22″” N” and set the expected value to 33.63944.

You will need to set delta, the third parameter of the assert.equal function, to .00001 to allow for rounding error.

Task 3c: Run the unit tests to make sure they all pass.

Task 3d:         Check out the master copy of the project and install your changes.




Task 4:          Add a unit test for the DegreesToRadians function to assure that coordinates are transformed to radians correctly.

Task 4a:         Right click anywhere within the CoordinateToDegrees function in Airports.vb and add a unit test named DegreesToRadiansTest to the unit test framework. (This has been done for you.)

Task4b: Modify the code in DegreesToRadiansTest to assert that DegreesDouble = 33.63944

and set the expected value to 0.58712. You will need to set delta, the third parameter of the assert.equal function, to .00001 to allow for rounding error.

Task 4c: Run the unit tests to make sure they all pass.

Task 4d:         Check out the master copy of the project and install your changes.