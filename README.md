#Real-Time Chaotic Encryption via Henon Map over Socket Communication

### 1. Setting up a virtual environment 
* First open terminal and cd into the "NLD" directory
  
Then run this simple code

    python -m venv .venv
    source .venv/bin/activate

This creates a virual environment with the name "venv" and activates it.

### 2. Getting all the Python Requirements
All the python requirements are listed in the requiremnets.txt file. To install them on your computer just paste this code.

    pip install -r requirements.txt

### 3. Setting up the Server and Client
* first make sure all the devices are on the same network
* Then open CMD and type 

    > ipconfig

* This will give you the public ip on the current network, now paste this in place of server's IP address in both client and server scripts.
### 4. Some addiitional instructions
*  Clear all outputs and retart the terminal before running any of the files.
*  When running the encryption model, first start the server and then start the client.
*  type exit in the client when you want to stop the messaging.

### 5. To delete the venv
You can do this by simply deleting the venv folder under the current directory. 

If you followed step 1 it will be in the directory "NLD" only. Hence, you can also just delete the folder(NLD) to get rid of the venv too.

## Some Features 
*  You can run the server and client scripts to send message to one another on different devices given that they are connected to the same network.
*  The ports used allow network traffic on IITH wifi. 
*  You can change the port as per your wish, but just keep them same in both the files.
