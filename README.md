# PC-STATS
# AUTHOR : Vasilis Manthelas [OFFICIAL-WEBSITE](http://j0ck3r2004.000webhostapp.com/)
# COPYRIGHT CLAIMS(C) : Vasilis Manthelas

# INSTALLATION
- Run setup.bat
- Install Python
- Run PC-STATS.pyc

# OPTIONS
    0] SHOW PC-STATS |
                     | [NETWORK STATS] |
                     |                 | [MS RATES (minimum,maximum,average)]
                     |                 | [PACKETS (sent,recieved,lost)]
                     |
                     | [SOFTWARE] |
                     |            | [BIOS (version)]
                     |            | [WINNDOWS (version)]
                     |
                     | [HARDWARE] |
                                  | [RAMS (channel,type,capacity)]
                                  | [DISKS (name,FsType,Opts,Capacity)]
                                  | [CPUS] |
                                           | [MODEL]
                                           | [COUNT (physical,logical)]
                                           | [FREQUENCY (current,min,max)]
                                           | [USAGE]
    1] SHOW COMPUTER CURRENT CONNETIONS |
                                        | [(IP,HOST,ISP,ORG,STATUS,PROCESS)]
    2] SHOW DNS TRAFFIC STREAM(better turn off IPv6 protocol) |
                               | [REQUEST (source(dns),destination(localhost),url)]
                               | [RESPONSE(source(dns),destination(localhost),url,ip)]
                        
# REQUIRMENTS(libs)
- requests
    ```sh 
    $ python -m pip install requests
    ```
- psutil
    ```sh
    $ python -m pip install ppsutil
    ```
