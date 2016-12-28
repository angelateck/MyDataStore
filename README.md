# MyDataStore
require("lib/instapush.php");
        $ip = InstaPush::getInstance("58059e27a4c48a0e2b3a9426", "db1803685d6356972e91c6d52fe5738d");
        $ip->track("lpg gas tank status", array( 
                "email"=> "angela_teck@hotmail.com"
        ));
