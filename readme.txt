(a) Group Members:
		Gaurav L Agarwal
		Ankit Vaghela


(b) Compilation/execution steps:
		In order to test/execute this project below steps are required (in order):

		1. Navigate to directory named server and compile server file using below command:

			javac myftpserver.java

		2. Run server using below command:

			java myftpserver <PORT NUMBER>

			ex. java myftpserver 3000

		3. Navigate to directory named client and compile client file using below command:

			javac myftp.java

		4. Run the client using below command:

			java myftp <MACHINE NETWORK ADDRESS> <PORT NUMBER>

			ex. java myftp localhost 3000
				java myftp 127.0.0.1 3000
				
		{Note: we have made a provision for the "cd" command to not go beyond the root directory where the program resides.
			To quit the server, press "ctrl+c" on the terminal where the server is running.}


(c) This project was done in its entirety by Gaurav Agarwal & Ankit Vaghela.
		We hereby state that we have not received unauthorized help of any form
