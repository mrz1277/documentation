# TCP/IP client

The TCP/IP client will send a TCP packet to a server. 

## Web interface 

![TCP socket io](2_tcp-io.png)

## Parameters

The parameters of the TCP/IP client can be found in the config/io.xml file, but you can also use the web interface to modify the parameters. Below you see a default configuration file.

	<ios>

	    <TCPSocket>
	        <server type="number">127.0.0.1</server>
	        <port type="number">1337</port>
	        <message type="text">it's so fluffy</message>
	    </TCPSocket>
	    
	</ios>

### Server

The IP of the TCP server.

### Port

This is the port of the TCP server.

### Message

You can send some data to a TCP server.

## Examples

More information can be found [here](/1.0.0/addons/TCP_Listener).