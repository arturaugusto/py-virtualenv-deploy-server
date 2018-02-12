# py-deploy-server
[WIP]
Scripts to create a server capable of auto deploying python web applications through HTTPS.

The final solution uses the following softwares/technologies:

- Let’s Encrypt: https://letsencrypt.org/
- HAProxy: http://www.haproxy.org/
- Apache: https://httpd.apache.org/ with modules:
  - mod_proxy_uwsgi: https://uwsgi-docs.readthedocs.io/en/latest/Apache.html
  - mod_proxy: http://httpd.apache.org/docs/current/mod/mod_proxy.html
- Certbot: https://certbot.eff.org/
- Virtualenv: https://pypi.python.org/pypi/virtualenv

Prerequisites: A domain name.



references:

https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uwsgi-and-nginx-on-ubuntu-14-04
https://mitchjacksontech.github.io/How-To-Flask-Python-Centos7-Apache-uWSGI/
https://www.digitalocean.com/community/tutorials/how-to-secure-haproxy-with-let-s-encrypt-on-ubuntu-14-04
https://uwsgi-docs.readthedocs.io/en/latest/Apache.html#mod-proxy-uwsgi