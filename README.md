# RPA-EXERCISE-3-Arguments-In
Passing data ke sequence lain

1. Open a UiPath Studio Project
2. Create a Sequence
3. Drag and Drop an Write line activity
4. Create a argument named inArgString. Enter a default Value “Bananas”. Direction should be “In”
5. In the Write line activity, type in text field. “I like to eat” + “ ” + inArgString
6. Run the automation then check the output panel

What did you notice? Arguments function similar to Variables. What is the difference?

7. Save the Process
8. Create another sequence, give it a name ArgumentsRunner
9. Drag and Drop an Assign Activity
10.Create a variable in the “To” field named strFruit. Set the Value to “Apple”
11.Drag and Drop an Invoke Workflow File. Click the Folder Icon, search for ArgumentsDemo.xaml
12.Click Import Arguments. Change the Value of inArgString to strFruit
13.Run the automation then check the output panel
