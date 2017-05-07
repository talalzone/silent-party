# Silent Party
A concept for hosting party over the local network with music synced across all member devices and can be listened to via headphones - so basically a party but a silent one.
The app is supposed to work on any network and can theoretically allow "n" number of party members because of the stateless connection between host and members. This part is mainly achieved through android Network Service Discovery(NSD) and creating a stateless NanoHTTPD Webserver for communication between devices. 
This architecture could easily be extended to incorporate a central server in order to allow hosting party anywhere via internet.

## Features
 * Creating and hosting parties on local network
 * Synchronized playlist among members
 * Members can vote songs via vote button or detecting dance movements
 * Voted songs are played first in the next round
 * Members can add songs to the party's playlist
 * View other members and the party owner (DJ)
 * DJ can manage members (e.g kicking members)
 * Search songs on soundcloud and manage your own playlist
 
## Configuration
Please add your Sound Cloud Application ID in the Config.java file: 
```
 public static final String SOUND_CLOUD_ID  =  ""; // Add your sound cloud ID here
```