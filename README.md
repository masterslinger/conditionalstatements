# AIM:
To develop a UiPath workflow that takes a user’s name as input and displays a custom welcome message using a Switch case. If the input is "RAM", it should display "Welcome Mr. Ramachandran", else display different messages for each name, and a default message for other names.

# SOFTWARE REQUIRED:
```
UiPath Studio (2021 or later version recommended)
Windows Operating System
```

# PROCEDURE:
```
1.Open UiPath Studio and create a new Process.
2.Inside the Main.xaml, drag and drop a Sequence activity.
3.Add an Input Dialog activity to get the user’s name.
4.Set the Title as "Name Input" and Label as "Enter your name:"
5.Store the result in a variable named userName (type: String).
6.Add an Assign activity: nameToCheck = userName.ToUpper() (to make the comparison case-insensitive).
7.Drag and drop a Switch activity.
8.Set Expression as nameToCheck.
9.Set TypeArgument as String
10.Add different Case blocks:
11.Case "RAM" → Message Box: "Welcome Mr. Ramachandran".
12.Case "RAHUL" → Message Box: "Welcome Rahul, Have a great day!".
13.Case "SITA" → Message Box: "Hello Sita, glad to see you!".
14.In the Default case, Add:Message Box: "Welcome " + userName.
15.Save and run the workflow.
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/afe3bbe6-edb2-4e3d-8f3c-d700c508bd8a)
![image](https://github.com/user-attachments/assets/eb147115-10fa-4ac3-83aa-ccb442f01e12)



# RESULT:
The UiPath workflow was successfully created and executed. It accepted the user’s name as input and displayed a customized welcome message using a Switch case, as per the given condition.
