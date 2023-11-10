## Basics of Networking
computer network is essentially a communication system , where some devices, which have communication
capability are connected with each other by some medium of communication , so that they can share information among theemselves.

**Data Communication over network follow two approach 1) Circuit Switching 2) Packet Switching** <br>
**Circuit switching** is a communication method where a dedicated communication path, or circuit, is established between two devices before data transmission begins. The circuit remains dedicated to the communication for the duration of the session, and no other devices can use it while the session is in progress. Circuit switching is commonly used in voice communication and some types of data communication.

**Packet switching** is a communication method where data is divided into smaller units called packets and transmitted over the network. Each packet contains the source and destination addresses, as well as other information needed for routing. The packets may take different paths to reach their destination, and they may be transmitted out of order or delayed due to network congestion.

**Store & Forward in Packet Switching:** -- In nodes there will be a buffer, a memory space where these packets will get stored right. And later on from this buffer, these packets will get forwarded to the next link. when the link becomes free .  Each of this intermediate nodes also maintain something called a routing table, we shall be talking about this later again. And this routing table will decide where an incoming packet should be forwarded to, there can be multiple outgoing links. And some packets may be given priority over others if desired.

**Packet Switching is achived in two ways 1) Virtual Circuits , 2) Datagram**
In Virtual Circuit approach the important thing is no dynamic routing decision is taken here. Once you establish the connection at the beginning, all the packets for a particular virtual circuit will be following that same path. This is one drawback of virtual circuit, because it is not dynamic or adaptive, it cannot adapt itself automatically,
