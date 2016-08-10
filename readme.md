## How to use

```
curl -L -O https://raw.githubusercontent.com/zackdevine/setup-strongswan-vpn-account/master/setup-vpn-account.sh
sudo chmod +x setup-vpn-account.sh
sudo ./setup-vpn-account.sh
```

This script will automatically backup `/etc/ipsec.secrets` and `/etc/ppp/chap-secrets` before adding a new VPN account.
