# Distributed Data Processing Systems Assignment 2
## Design Your Own Distributed System
This repository contains the code necessary to run an implementation of Chord built by Jasper Dellaert and Akshay Ram Bhat for the course Distributed Data Processing Systems at the Leiden Institute of Advanced Computer Science in Leiden University by Prof. Alexander Uta.

## Prerequisites
* Python 3.7.9

## Running the Code
In order to run the code follow the instructions in this order:

1. Run the following command on an open terminal.
```./chord.sh```
This will start the connection and have 5 nodes running.
2. Open another terminal and run this command to start connecting to the network
```python3 user_node.py <PORT_NUMBER>```
where ```PORT_NUMBER``` is a a port number that is active in the network. If using the shell script provided, use ```2010```.
3. You will be faced with a menu
    ```
    1. Join Network
    2. Leave Network
    3. Upload File
    4. Download File
    ```
4. Choose ```1``` and join the network.
5. The menu will reappear after connecting and you will then be able to upload or download files using ```3``` and ```4```.


Feel free to rest out our implementation of Chord. For more details on how Chord works, please read [the original paper here](https://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf).
