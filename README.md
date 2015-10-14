# redmine-to-gitlab

Here are a set of scripts to import data from an existing redmine setup to gitlab. 

We have used this while we were shifting to gitlab. Hope it might be of help to any one who does that in future.

### Requirement:
- Python lib: requests
- Gitlab private-key of an admin
- Gitlab cookie of an admin (Hope you know how to get the cookie)
- Redmine auth-key of admin

### General Instructions
- Copy the config file example:
  ```python
  cp conf.py.local conf.py
  ```
- Edit *conf.py* with your settings
- Each file also requie some configs (will try to put all in the conf file in future) like gitlab cookies and redmine auth-key.
Set them.

##### Feel free to contact us at [Jinora](https://chat.sdslabs.co) or through [email](mailto:contact@sdslabs.co.in)  in case you need any help.

