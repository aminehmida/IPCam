# General Camera Metadata

* Device serial number: `000D2C2B1B`
* Hardware version: 2.0
* Firmware version: 1.9.8
* WiFi MAC:
    * AP mode: `10:a4:be:1d:48:5a`
    * Client mode: `10:a4:be:1d:48:5b`
    * (I don't have reason to believe that there are two radios on the device -- instead, for some reason, I think it's changing the MAC addr depending on connection mode.)
* LAN MAC:
    * Blank.  Field exists in the about page, but is not populated.
* UID: `CH1D8D8-C3C497C12E2F-62E914` (also network name)

## Account data
* HTTP Username: `admin`
* HTTP Password: (empty)

## Webserver
 * Default port: `80/tcp`

## Open ports

When running in AP (Access Point) mode:
* `80/tcp` with service `http`
* `53/udp` with service `domain`
* `67/udp` with service `dhcps`
* `10000/udp` with service `ndmp`

When running in network (client) mode:
* `80/tcp` with service `http`
* `10213/tcp` with unknown service (seems to be listen-only)

## P2P configuration

*By default*, the camera seems to use the following P2P settings:

* P2P Enabled
* Servers:
    * `120.27.7.78`
    * `47.88.9.191`
    * `hzqd.mycamdns.com`
    * `hzusa.mycamdns.com`
* UID: `CH1D8D8-C3C497C12E2F-62E914` (same as cam UID)
* Password: `8888`

