# Distributed Data Processing Systems Assignment 2
## Design Your Own Distributed System
This repository contains the code necessary to run an implementation of Chord built by Jasper Dellaert and Akshay Ram Bhat for the course Distributed Data Processing Systems at the Leiden Institute of Advanced Computer Science in Leiden University by Prof. Alexander Uta.

## Prerequisites
* Python 3.7.9

## Running the Code
In order to run the code follow the instructions in this order:

1. Run the following command on an open terminal.
```./chord.sh```
This will start the connection and have 6 nodes running.
2. Open another terminal and run the following command to start connecting to the network
```python3 user_node.py <PORT_NUMBER>```
where ```PORT_NUMBER``` is a a port number that is not in use currently. When using the shell script provided, any number above ```2010``` will work.
3. You will then be faced with a menu
    ```
    1. Join Network
    2. Leave Network
    3. Upload File
    4. Download File
    ```
4. Choose ```1``` and join the network. When asked for an IP and port to connect use  ```127.0.0.1``` and  ```2000``` when using the shell script.
5. The menu will reappear after connecting, you then will be able to upload or download files by following the menu options ```3``` and ```4```.


Feel free to test out our implementation of Chord. For more details on how Chord works, please read [the original paper here](https://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf).
