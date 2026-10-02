# Reliable UDP File Transfer

A Python-based file transfer application that provides reliable file transfer over UDP using a custom reliability mechanism based on acknowledgements, sequence numbers, sliding windows, and Go-Back-N ARQ.

The project provides a Streamlit web interface for sending and receiving files.

## Technologies Used

- Python
- UDP
- Python Socket Programming
- Streamlit
- Go-Back-N ARQ
- Sliding Window
- Computer Networking Concepts

  
# Working Procedure
---------------------
1. Run the main file "app.py" using "streamlit run app.py" from the command prompt.
2. On web page, select Sender mode on one system and Receiver mode on the other.
3. Set the IP Number and Port No. of the receiver.
4. Click "Start Receiver" first so the receiver starts listening first on the specified port.
5. Now click "Send File" on the sender to start sending file.
6. Enable Log to see all the sending and receiving info on the console.
