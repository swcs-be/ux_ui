# TO TEST
`docker run -dit --name uxui-swcs -p 8088:80 -v [YOUR_PATH]:/usr/local/apache2/htdocs/ httpd:2.4`

# To Run Github Actions
POST TO   
`https://api.github.com/repos/swcs-be/ux_ui/dispatches`  

BODY:  
`{  
    "event_type":"repository_dispatch"  
}`  

HEADERS:  
`  
Accept: application/vnd.github.everest-preview+json
`  
`  
Content-Type: application/json  
`    
  
OAUTH:  
`BEARER TOKEN (set in repo settings)`  
