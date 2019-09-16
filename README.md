# Revit-plug-in
A plug-in for calculation of assembly rate of the model under Revit.
To initiate the plug-in when Revit launch, you could follow the steps presented:
  1.Paste the three "addin" files to the folder path "C:\Users\"YourUserName"\AppData\Roaming\Autodesk\Revit\Addins\2016".
  2.Change the project path in the "HelloWin.addin" file (between the <Assembly> label) after you download the whole project in your computer.
  3.Change the AddinId in the aforementioned file, you can get the one-and-only id from check it up in VisualStudio.

 To calculate the assembly rate of a revit model, it has to comform to a specific naming rule, which you can find in "NamingRule.xlsx", otherwise this plug-in cannot identify some specific attributes necessary in the calculation.
 Model file is provided, you can open it in Revit and test the plug-in with it.
