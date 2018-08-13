# Python-Android-Connection
An android app make a connection with a python script by a socket client/server (the app is the 
client and python script is the server).

- The messages between the client and server can be from these kinds:
    a. "Correct" message and the reply in this case is: "Success".
    b. "Disconnect" message and the reply in this case is: "Disconnected and the listen has Stopped".
    c. other messages and the reply in this case is: "Failed".

- The android app contain three UI component:
    1- EditText: for insert your message.
    2- Button: to send the message.
    3- TextView: display the reply of server.

- The python script is listen for a client as shown in the code.

- The code is tested with:
    - python 2.7
    - Android Studio 3.1.3
      Build #AI-173.4819257, built on June 4, 2018
      JRE: 1.8.0_152-release-1024-b02 amd64
      JVM: OpenJDK 64-Bit Server VM by JetBrains s.r.o
      Windows 10 10.0
