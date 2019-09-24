# SVI_CODE_GENERATOR_Ver2.0

This is the 2.0 Version of the SVI Code generator for generating the Part# and Description for ordering valves from SUN VALVE INC.

To compile, please refer to the readme at https://github.com/Zeroimbas/SVI_VALVE_CODE_GENERATOR


Updates:

1. The labels and combo boxes are able to maintain their positions when changing the size of the window. 
 
2. No valve experience user protection is added in this version as Sa required, which means the program will pop an error, if users don’t select the necessary parts of a valve, like body material, size, etc.
 
3. All the “NONE” is removed from the final description. For example: The description of a valve generated in the previous version looks like “PISTION CHECK, 1/4'', ANSI CLASS 2500,MLIP × FNPT, REDUCED PORT, BODY ASTM A182 F9, TRIM# 9, NONE, HAND WHEEL, PACKING PTFE, NONE, NONE, NONE.” if there are options being selected as "NONE". It will now be generated as “PISTION CHECK, 1/4'', ANSI CLASS 2500,MLIP × FNPT, REDUCED PORT, BODY ASTM A182 F9, TRIM# 9, HAND WHEEL, PACKING PTFE.”
 
4. Operation type code has been removed from Part# if the CHECK VALVE is selected as item, since there is no operation type for check valves.


Please Node: the exe version wraped in the zip file is generated using Pyinstaller in Windows environment, so it is only executable in Windows. Since the button color is defined as 'Moonlight blue' as required by the president of SUN VALVE INC. , which is not an option in MAC OSX or LINUX/UNIX and it will cause the text on the buttons to be blank.
