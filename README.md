# 2moons-xterium
FINISHED - DISCONTINUED

README: HOW TO USE THE XTERIUM TEMPLATE

#1 - CREATE DATABASE (EXAMPLE: UNI_NAME_PORTAL, UNI_NAME_WORLD1, UNI_NAME_WORLD2 ...)<br>
#2 - UPLOAD THE PORTAL_TYPE_DB ZND THE GAME_TYPE_DB IN THE CORRECT PREVIOUS CREATED DATABASES<br>
#3 - REDIRECTIONS - CREATE ONE SUBDOMAIN FOR PORTAL FILES AND ONE SUBDOMAIN FOR GAMES FILES<br>
#4 - EDIT LOGIN PROCESS IN THE PORTAL PAGE TO MATCH YOUR SUBDOMAIN NAMES.<br>
#5 - CREATE AN ADDITIONAL SUBDOMAIN NAMED STATIC.MYURL.COM (HOSTING ON THE PORTAL FOLDER ASWELL)<br>
#6 - FOR A BETTER USER EXPERIENCE, OWNER SHOULD PURCHASE A CDN OR USE A FREE CDN ON THE PORTAL MEDIA FOLDER TO LOAD ALL IMAGE FASTERS (BUT NOT FORCED) ON THE STATIC SUBDOMAIN<br>
#7 - RUN THE INSTALL FOLDERS


EXAMPLE OF FTP STRUCTURE

- ROOT
	- XTERIUM_GAME
		- PORTAL
      - ALL PORTAL FILES
		- UNIVERSE
			- WORLD_1
        - ALL GAMES FILES FOR WORLD_1
			- WORLD_2
        - ALL GAMES FILES FOR WORLD_2
			- WORLD_3
        - ALL GAMES FILES FOR WORLD_3
			
EXAMPLE OF PORTAL AND GAME URL USING THE FOLLOWING STRUCTURE FOR CREATING SUBDOMAINS:
- httpdocs/XTERIUM_GAME/PORTAL
- httpdocs/XTERIUM_GAME/UNIVERSE/WORLD_1
- httpdocs/XTERIUM_GAME/UNIVERSE/WORLD_2
- httpdocs/XTERIUM_GAME/UNIVERSE/WORLD_3
			
			
