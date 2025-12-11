# Systemd Unit

If you are using distribution packages you typically don't need to deal with these files.

The unit file (`*.service`) in this directory are to be put into `/etc/systemd/system`.
It needs an optional sysconfig file in `/etc/sysconfig/puppet-agent-exporter`.
A sample file can be found in `sysconfig.puppet-agent-exporter`.