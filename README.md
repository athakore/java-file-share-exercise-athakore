File Share
===
This is a collaborative exercise in which your group will work together to transfer files between one another using IO Streams. Each student in the group will write two programs: One that hosts a ServerSocket that listens for incoming connections and reads a file from the incoming stream, and one that instantiates a series of Sockets that will write a file of your choosing to each other group member. When all members of the group have completed their projects, they should all start their servers first, then they should all start their file sending applications. If successful, each member of the group should have correctly received one new file per group member (excluding themselves)

## Task List
- [ ] Work with your team to define and agree upon a communication protocol
- [ ] Create an application that will read a file from a location on your machine and send that file over a stream
- [ ] Create an application that will listen for incoming connections & read the incoming data as a file which is stored in a directory on your machine
- [ ] Ensure that the two applications can share a file between each other
- [ ] Ensure that all members of the group can initiate their servers and receive one file per member of the group
