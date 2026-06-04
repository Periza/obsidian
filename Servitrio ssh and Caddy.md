ssh -i C:\Users\mperica\.ssh\servitrio -N -R 0.0.0.0:3443:127.0.0.1:3443 root@markoperica.site

sudo ss -tlnp | grep :3443

sudo kill -9 <PID>

.\caddy.exe run --config .\Caddyfile