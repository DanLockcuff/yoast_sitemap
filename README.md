# yoast_sitemap
Add yoast-sitemap-context.conf to the /var/www/$site_root/nginx/

Add include to /etc/nginx/common/$site_root-sitemap.conf
  include /var/www/$site_root/nginx/*-sitemap-context.conf;
