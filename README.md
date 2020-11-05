# ansible-minecraft-papermc

This role installs a completely Minecraft PaperMC server.

## Variables

Following variables have to be set in the playbook:

* minecraft_papermc_eula
* minecraft_papermc_sp_rcon_password

## Security

It's recommended to make the rcon port only locally accessible via iptables
