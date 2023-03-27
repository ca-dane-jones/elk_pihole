# Pi-hole logging elasticsearch integration

### This integration is currently experimental!

```shell
sudo sh -c 'echo "log-queries=extra" > /etc/dnsmasq.d/99-pihole-log-facility.conf'
sudo /etc/init.d/pihole-FTL restart
```