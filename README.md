# sec role

Security configurations and programs. Including `sshd` config, `fil2ban` and `iptables`.

## Troubleshooting

If you change the default `sshd` port, you will be blocked by iptables until you restart the service and connect via the new port.
