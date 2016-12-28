# MyDataStore
require("lib/instapush.php");
        $ip = InstaPush::getInstance("APPLICATION_ID", "APPLICATION_SECRET");
        $ip->track("signup", array( 
                "email"=> "email@somewhere.com"
        ));
