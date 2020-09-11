- hosts: all
  tasks:
    - name: Run role
      include_role:
        name: ansible-role-tg2rss
      vars:
        telegram_api_id: 00000
        telegram_api_hash: eeff1155aadd33aa55ccffcc4488ff8c  

Hash from https://my.telegram.org/apps
