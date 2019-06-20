# Copycat Toolkit
                                     _   
                                    | |  
      ___ ___  _ __  _   _  ___ __ _| |_ 
     / __/ _ \| '_ \| | | |/ __/ _` | __|
    | (_| (_) | |_) | |_| | (_| (_| | |_ 
     \___\___/| .__/ \__, |\___\__,_|\__|
              | |     __/ |              
              |_|    |___/   Toolkit v1.0           

<p align="center">
  <a href="http://entynetproject.simplesite.com/">
    <img src="https://img.shields.io/badge/entynetproject-Ivan%20Nikolsky-blue.svg">
  </a>
  <a href="http://entynetproject.simplesite.com/">
      <img src="https://img.shields.io/badge/entynetproject-Anna%20Fet-red.svg">
  </a> 
  <a href="https://github.com/entynetproject/copycat/releases">
    <img src="https://img.shields.io/github/release/entynetproject/copycat.svg">
  </a>
  <a href="https://ru.m.wikipedia.org/wiki/Python">
    <img src="https://img.shields.io/badge/language-python-blue.svg">
 </a>
  <a href="https://shodan.io/">
      <img src="https://img.shields.io/badge/database-shodan-red.svg?maxAge=2592000">
 </a>
  <a href="https://github.com/entynetproject/copycat/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues/entynetproject/copycat.svg">
  </a>
  <a href="https://github.com/entynetproject/copycat/wiki">
      <img src="https://img.shields.io/badge/wiki%20-copycat-lightgrey.svg">
 </a>
  <a href="https://mobile.twitter.com/copycat_toolkit">
    <img src="https://img.shields.io/badge/twitter-copycat-blue.svg">
 </a>
</p>

# Copycat toolkit credits
   
    Name      : Copycat Toolkit 
    Developer : Entynetproject
    Version   : v1.0 (first release)
    Database  : Shodan (https://shodan.io/)
    Site      : https://entynetproject.simplesite.com/
    API       : Automate Shodan API

# About copycat toolkit

    INFO: Copycat Toolkit is a set of tools to view information 
    about hostname, IP’s or for real-time internet scanning.
    This project developed by Ivan Nikolsky and Anna Fet.
    
# How to install copycat

    INFO: Copycat Toolkit will be installed to /bin and
    /usr/local/bin as /bin/copycat and /usr/local/bin/copycat!
    
> cd copycat

> chmod +x install.sh

> ./install.sh

# How to uninstall copycat

> cd copycat

> chmod +x uninstall.sh

> ./uninstall.sh

# How to execute copycat

> copycat help

    Usage: copycat [OPTION...] <argument...>
    Copyright (C) 2019, Entynetproject. All Rights Reserved.
 
        host     <host>                Show all available information for an IP.
        honeypot <host>                Check whether the IP is a honeypot or not.
        download <filename> <request>  Download search results as JSON database.
        parse    <format> <filename>   Extract information out of compressed JSON.
        stats    <request>             Provide summary information about a search.               
        search   <request>             Search the internet of things from Copycat.
        domain   <domain>              Show all available information for a domain.
        stream                         Stream Copycat search results in real-time.
        radar                          The real-time map of Copycat search results.
        update                         Update Copycat Toolkit and API configuration.
        info                           Show all information about Copycat Toolkit.
        help                           Show all available Copycat Toolkit options.
 
 # Copycat examples
 
> copycat host 183.63.126.164
 
    183.63.126.164
    City:                    Guangzhou
    Country:                 China
    Organization:            China Telecom Guangdong
    Updated:                 2019-05-12T15:43:53.018648
    Number of open ports:    6
    Vulnerabilities:         CVE-2010-1256	CVE-2010-2730	CVE-2010-3972	CVE-2010-1899	CVE-2012-2531	

    Ports:
         80/tcp  
         84/tcp Microsoft IIS httpd (7.5)
        443/tcp  
       8013/tcp  
       8080/tcp Apache Tomcat (3.1)
       8081/tcp Apache Tomcat/Coyote JSP engine (1.1)
       
> copycat download tomcat tomcat

    Search query:			    tomcat
    Total number of results:            77601
    Query credits left:		    197673
    Output file:			    tomcat.json.gz
      [####################################]  100%  00:00:00
    Saved 1000 results into file tomcat.json.gz
    
# Copycat parse formats

    --only-ip             (view only ip)       
    --only-port           (view only port)
    --only-org            (view only org)
    --only-hostnames      (view only hostnames)
    --only-data           (view ip and port)
    --only-ip-port        (view ip and port)
    --only-ip-org         (view ip and org)
    --only-ip-hostnames   (view ip and hostnames)
    --only-port-org       (view port and org)
    --only-port-hostnames (view port and hostnames)
    --only-org-hostnames  (view org and hostnames)
    --only-data-org       (view ip, port and org)
    --only-data-hostnames (view ip, port and hostnames)

# Terms of use

    This tool is only for educational purposes only.
    Use this tool wisely and never without permission.
    I am not responsible for anything you do with this tool.

# Copycat MIT license

    MIT License

    Copyright (C) 2019, Entynetproject. All Rights Reserved.

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

# Thats all!
 
