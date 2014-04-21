ansible-role-gsutil
===================

Install and setup gsutil with Ansible

# Example :
```
---
 - hosts: all
   roles:
     - role: gsutil
       gsutil_users_config:
          - user: myuser
            group: mysuergroup # optional use user by default
            vars: 
              - gs_oauth2_refresh_token: "INSERT_YOUR_OAUTH2_REFRESH_TOKEN"
```
