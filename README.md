[README.md](https://github.com/user-attachments/files/21774895/README.md)
> Why do I have a folder named ".expo" in my project?
The ".expo" folder is created when an Expo project is started using "expo start" command.
> What do the files contain?
- "devices.json": contains information about devices that have recently opened this project. This is used to populate the "Development sessions" list in your development builds.
- "settings.json": contains the server configuration that is used to serve the application manifest.
> Should I commit the ".expo" folder?
No, you should not share the ".expo" folder. It does not contain any information that is relevant for other developers working on the project, it is specific to your machine.
Upon project creation, the ".expo" folder is already added to your ".gitignore" file.
<img width="1917" height="911" alt="Screenshot 2025-08-19 232253" src="https://github.com/user-attachments/assets/7386cfd7-42b9-4bd0-a8ed-00a2a589175e" />
<img width="1919" height="902" alt="Screenshot 2025-08-19 232241" src="https://github.com/user-attachments/assets/535d68b1-07b1-46b7-bca1-b13d92eba87c" />
