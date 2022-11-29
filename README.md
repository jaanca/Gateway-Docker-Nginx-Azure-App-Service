# Description

- Using Nginx for create a gateway nginx without load balacer, between microservices into Azure App Services Docker.
- This code only explain the gateway concept to proxy_pass to Azure App Service, for try please referer to urls(s): https://github.com/jaanca/Gateway-Docker-Nginx-With-Microservices-Simple to build and construct your laboratory and test the code.

# Description of the files
    .
    |-- docs/                         # Documentations
    |   |-- photos/                   # Screenshots for running system
    |   |-- Software-Architecture/    # Context Diagram from solution
    |-- nginx_core.conf               # File /etc/nginx/nginx.conf to define nginx core settings
    |-- nginx_directives.conf         # File /etc/nginx/includes/directives.conf to define limits and other settings
    |-- nginx_routes.conf             # File /etc/nginx/conf.d/default.conf to define path from url to proxy_pass routing
    |-- README.md                     # Readme file
    

# Screenshots

![Alt text](/docs/photos/Screenshot_1.png?raw=true)
![Alt text](/docs/photos/Screenshot_2.png?raw=true)
![Alt text](/docs/photos/Screenshot_3.png?raw=true)
![Alt text](/docs/photos/Screenshot_4.png?raw=true)
![Alt text](/docs/photos/Screenshot_5.png?raw=true)
![Alt text](/docs/photos/Screenshot_6.png?raw=true)
![Alt text](/docs/photos/Screenshot_7.png?raw=true)
![Alt text](/docs/photos/Screenshot_8.png?raw=true)
