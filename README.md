# uWSGI Installer

# Reqs

Should have SITE_FOLDER environment variable, wgere SITE_FOLDER is /home/[SITE_FOLDER]

# How it works

Start the script python uwsgi/uwsgi.py, emperor config will be created uwsgi/emperor.ini, vassal config will be created uwsgi/uwsgi/uwsgi.ini and upstart script would be created /etc/init/SITE_FOLDER.conf and started.

# Plans

Maybe I'll make it full working environment starter, i.e. in ideal it should create environment, install requirements, make nginx configs, generate certificates and start the app. But as simple is always better, will not go too much into it.

# Who uses

* [Talaikis.com](https://github.com/xenu256/talaikis.com)
* [QProb](https://github.com/xenu256/QProb)
* [Quantrade](https://github.com/xenu256/Quantrade)
