# University Dissertation Project: Robotic Design with Sentiment
Please note this work was submitted academically and will only be a demonstration of what was submitted. This repository summarised both report work and product submitted.

## Aim
The aim is to develop a chatbot application that uses machine learning to classify emotions 
presented by the user and provide an appropriate response. This capability displays emotional 
intelligence which is essential for trust in Human-Robot interactions.

## Objectives
The key objectives of this project are as follows: 
1. Implement Chat Features 
2. Include “facial” expressions 
3. Initiate conversation with user and respond appropriately.

## Process Description
Applying the Incremental Model, directly to developing the chatbot. The first stage consisted of listing the product’s 
requirements as a whole, this allowed for an overview of what the product would look like once 
it was complete. Once this had been completed, functionalities such as window development, 
which did not depend on preexisting structures, were applied first. Each segment would be tried 
and tested before being applied to the main code file.  This would serve as a basis for the rest of 
the product, working on the main window, to the start frame. The start frame could be split into 
2 sections: The” Rice ball” section and “Chatroom” section. Each section had its own functions 
therefore each was developed separately, developing the emotion recognition in the “Rice ball” 
section and then progressing to completing the general conversation section in the “Chat room” 
segment.

It was advantageous to conduct development in this way as not only were each individual 
functionalities implemented and tested before being applied to the main product, the stress of 
completing several functions at once was reduced, allowing for ease during development. 
However, the Incremental Model could pose problems during the development as each function 
is created separately, so when functionalities are applied to the main product, there could be 
conflicting code, with one function interfering with the execution of another. This could be fixed 
through testing code after each implementation to ensure all code operates cohesively.

## Technology Stack
The technology stack that was planned to be used consisted of Tkinter, ChatterBot and Python. 
Tkinter would act as the foundation of the application, providing the window and frames used to 
move between different pages. This was chosen due to its popularity in the Python community 
for being a powerful yet simple user interface development tool. ChatterBot would provide the 
core functionality to the app, allowing users to communicate with Japonica. This was essential 
as it provided the basic fundamental capabilities required of a chatbot. Python would be the 
development language, chosen for being easy to learn with a large library of developmental 
tools at its disposal.

Although, initially it was planned to incorporate ChatterBot into the product, this was 
unsuccessfully implemented for a couple of reasons. ChatterBot, was no longer maintained, 
which would require an older version of Python to be used, posing compatibility issues with new 
libraries. Additionally, this poses the risk of bugs and lack of support, which could hinder and 
prolong development. Lastly, ChatterBot was excluded because it contained the main 
functionality of the product, which required direct development. This led to ChatterBot being 
replaced with Tkinter.

## Core Requirements
**1.0 Root/Window** 
- 1.1 - Consists of 2 main frames: Start and Menu 
- 1.2 - Contains a menu bar 
- 1.3 – Menu bar consists of 2 options: Main and Exit 
- 1.4 – Contains the window title 
- 1.5 – Displays the dictated window size 
- 1.6 – Displays the “Japonica” icon bitmap
  
**2.0 Menu/Main** 
- 2.1 - Maintains menu bar stated in 1.2 
- 2.2- Contains main menu title 
- 2.3 - Contains a “Start” button that changes the menu frame to the start frame 
- 2.4 – Displays Main background

**3.0 Start** 
- 3.0.1 – Consists of 2 subsections: Rice ball and chatroom 
- 3.0.2 – Maintains menu bar stated in 1.2 

**3.1 Rice ball** 
- 3.1.1 - Displays “Sad” Japonica 
- 3.1.2 – Displays “Joy” Japonica 
- 3.1.3 – Displays ”Love” Japonica 
- 3.1.4 – Displays “Anger” Japonica 
- 3.1.5 – Displays “Fear” Japonica 
- 3.1.6 – Displays “Surprised” Japonica 

**3.2 Chatroom** 
- 3.2.1 – Displays “Japonica” responses 
- 3.2.2 – Displays user responses 
- 3.2.3 – “Japonica” and “User” headers are used to specify the name of each correspondent 
- 3.2.4 – Scroll bar implemented for chat view 
- 3.2.5 – User input box 
- 3.2.6 – User send button to transmit response to “Japonica” 

**4.0 Emotion Analysis** 
- 4.1 – Takes in user input 
- 4.2 – Processes dataset using dataset model 
- 4.3 – Provides an emotion prediction that influences the “Japonica” display in 3.1 

**5.0 General conversation** 
- 5.1 – Takes in user input 
- 5.2 – Processes dataset using dataset model 
- 5.3 – Provides a predicted appropriate response to the user’s input and is displayed by 3.2 

## Supplementary Requirements
These are requirements that were later identified that enhance the core requirements. 

**1.0 Root/Window** 
- 1.3 – Menu bar contains the additional “Instructions” tab 

**2.0 Menu/Main** 
- 2.4 – Contains an “Instruction” that prompts a message box containing how to use the 
application for the user. 

**3.2 Chatroom** 
- 3.2.1 – Return key can be used as an alternative to the send button 
- 3.2.2 - Prevents users from typing in the chat log 

