# DOCTYPEhtml
```
Edit aapanel: /www/server/panel/vhost/nginx/domain.conf
Awesome, thanks! For Nginx it works like this in your
server{
  ...
  add_header Permissions-Policy "browsing-topics=()" always;
  ...
} 
```
