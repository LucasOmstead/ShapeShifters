# ShapeShifters

## Running Project Locally

1. Run BasicServer.java class and after running the BasicServer.java. Ensure the server is fully started before the next step.
   2. To see if the server is fully started, ensure: "Server starting on port 5001" is logged into your terminal.
2. Run BasicScene.java 2 times to get an instance for the prey and predator move around the map to test functionality.
3. Ensure to fully restart the server and opening a new set of BasicScene instances each time for testing. 

## Running Project Between 2 Computers

1. Run the Unix command (for macOS, you'll need an equivalent command for Windows): ipconfig getifaddr en0
2. Update the variable: String serverIP = "172.20.10.3" to your IP address returned from the command.
3. Run GameMenu.java and input the returned IP address from the command and a username.
4. Another computer on the same wifi network can run GameMenu.java with your IP address and another username to connect to your game session.
5. For each new session, restart the BasicServer.java file to run a new instance. Then, restart GameMenu.java and reconnect.
