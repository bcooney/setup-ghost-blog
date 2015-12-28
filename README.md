## Ghost Blog Auto Install Script with Nginx and ModSecurity

Use this automated bash script to install the latest <a href="https://ghost.org" target="_blank">Ghost blog</a> on Ubuntu, with Nginx as a reverse proxy and ModSecurity web application firewall.

This script must be run on a **freshly installed** Ubuntu 14.04 (Trusty) or 12.04 (Precise) system. It is intended for use on a Virtual Private Server (VPS) or dedicated server. Do **NOT** run this script on your PC or Mac!

#### <a href="https://blog.ls20.com/install-ghost-0-3-3-with-nginx-and-modsecurity/" target="_blank">Link to my blog article with detailed information</a>   
<a href="https://gist.github.com/hwdsl2/42841f9edad3f1741436" target="_blank">Alternative script for Ghost blog with Naxsi</a>   
<a href="https://blog.igbuend.com/dude-looks-like-a-ghost/" target="_blank">Original post by Herman Stevens</a>   

### How to Use
```
wget https://gist.github.com/hwdsl2/1b1804cad601928472e7/raw/ghost-nginx-modsecurity.sh -O ghost-nginx-modsecurity.sh
bash ghost-nginx-modsecurity.sh BLOG_FULL_DOMAIN_NAME
```

&darr;&nbsp;&nbsp;&darr;&nbsp;&nbsp;&darr; Scroll down for the script &darr;&nbsp;&nbsp;&darr;&nbsp;&nbsp;&darr;

### Copyright and license

Copyright (C) 2015&nbsp;Lin Song&nbsp;&nbsp;&nbsp;<a href="https://www.linkedin.com/in/linsongui" target="_blank"><img src="https://static.licdn.com/scds/common/u/img/webpromo/btn_profile_bluetxt_80x15.png" width="80" height="15" border="0" alt="View my profile on LinkedIn"></a>   
Based on the work of Herman Stevens (Copyright 2013)

Special thanks to <a href="https://raymii.org" target="_blank">Remy van Elst</a> and <a href="https://philio.me" target="_blank">Phil Bayfield</a> for their helpful suggestions.

This program is free software: you can redistribute it and/or modify it under the terms of the <a href="https://www.gnu.org/licenses/gpl.html" target="_blank">GNU General Public License</a> as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

<a href="https://github.com/igrigorik/ga-beacon" target="_blank"><img src="https://ga-bc1.appspot.com/UA-46742347-4/hwdsl2/1b1804cad601928472e7?dh=gist.github.com&amp;gif=1" alt="Analytics" style="max-width:100%;"></a>