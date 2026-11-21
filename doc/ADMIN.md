# Admin interface

As admin, you are able to connect to the Pocketbase instance for advanced stuffs. The process is explained at <https://wanderer.to/run/backend-configuration>, but here are the steps:

On your computer (not the server), open a terminal and and run

```
ssh -L __PORT_POCKETBASE__:127.0.0.1:__PORT_POCKETBASE__ YOUR_USER@YOUR_SERVER -p SSH_PORT

```

Then, keep the terminal open, and visit <http://localhost:8090/_/> in your favorite browser. You’ll have to connect with the credentials you have set for your admin user at install.

# Plugins

If you'd like to use the plugins system, you have to extract manually the plugin in the __INSTALL_DIR__/data/plugins folder.