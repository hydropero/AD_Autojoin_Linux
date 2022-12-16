# AD_Autojoin_Linux - Ansible Tower

## This repo contains the **Ansible Tower** files required to perform an automated domain join of a **RHEL** server into **Active Directory**. 

This process is not only tedious and time consuming, but merely domain joining to an identity provider via realm will not automatically maintain associations between IP and hostname in DNS. This is needlessly painful and doubly so for those who use who futz with their home networking on a weekly basis or equally certifiable, those who run RHEL as their daily driver as DHCP. (You never know when you'll need to SSH from across your apartment, just to avoid some much need exercise!)
