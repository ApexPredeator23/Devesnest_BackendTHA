   For Linux

    Run the commands:

        sudo apt-get install redis-server
        sudo service redis-server restart
        redis-cli 
        
        
        For Windows

    Enable WSL from "Turn Windows features on or off settings"
    Restart the machine
    Install Ubuntu20.04 from Windows Store
    Open Ubuntu and setup name and password
    Run the following commands:

        sudo apt-get update
        sudo apt-get upgrade
        sudo apt-get install redis-server
        sudo service redis-server restart
        redis-cli 
        
        
        For Arrays

    LPUSH array value
    RPUSH array value
    LRANGE array start stop
    LPOP array
    RPOP array
