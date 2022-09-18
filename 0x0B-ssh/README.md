

SSH config file for OpenSSH client
This page is about OpenSSH client configuration. For OpenSSH server configuration, see sshd_config. For Tectia SSH configuration, see Tectia SSH Server Administrator Manual. For configuring passwordless public key authentication, see ssh-keygen.

The ssh program on a host receives its configuration from either the command line or from configuration files ~/.ssh/config and /etc/ssh/ssh_config.

Command-line options take precedence over configuration files. The user-specific configuration file ~/.ssh/config is used next. Finally, the global /etc/ssh/ssh_config file is used. The first obtained value for each configuration parameter will be used.
