This is the PBL of Group 7 from Grade 11-SD1 from iAcademy. 

As shown in the tutorial(https://www.youtube.com/watch?v=QQzAHcojEKg&list=PLhfAbcv9cehhkG7ZQK0nfIGJC_C-wSLrx),
please do the ff. for your file on your computer:

1. Create a New Project
2. Choose .NET Framework in Visual C++
3. Choose Empty Project, then press OK
4. Right-click on the Solution Explorer 
5. Add > New Item
6. Choose C++ File, then press Add
7. Right-click the project in the Solution Explorer
8. Click Properties
9. C/C++ > General
10. Click the blank spot to the right of Additional Include Directories
11. Click the dropdown arrow, then <Edit...>
12. Click New Line
13. Click Browse (3 dots)
14. Choose the include folder in your SDL files, then click OK
15. Linker > General
16. Click the dropdown arrow for Additional Library Directories, then Edit 
17. Click New Line then Browse again
18. Find your SDL lib folder and choose x86 for this PBL
19. Click OK
20. Linker > Input
21. Click the dropdown arrow for Additional Dependencies, then Edit
22. Add:
  SDL2.lib
  SDL2main.lib
23. Click OK
24. Linker > System
25. Click the dropdown arrow for Subsystem
26. Choose Console (/SUBSYSTEM:CONSOLE)
27. Click Apply, then OK
28. Copy the SDL2.dll from the x86 folder (for this PBL) to where your .cpp file is located
