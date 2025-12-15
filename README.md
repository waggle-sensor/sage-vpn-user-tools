# Sage VPN User Tools

This repo contains tools which make it easier for users to join the Sage Wireguard VPN infrastructure. The main ones are:

## Tools

### join-sage-vpn

This is intended to be run a client device and will bootstrap their wireguard client configuration. The only required input is a VPN IP address which _we_ will provide from our VPN inventory.

```
usage: join-sage-vpn client-ip
```
