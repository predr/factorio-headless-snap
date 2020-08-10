[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/factorio-headless)

### Headless server for Factorio running as a system service

Change configuration options.

	snap get factorio-headless
	snap set factorio-headless admins='["kovarex"]'
	snap set factorio-headless game-password=1337
	snap restart factorio-headless

Control the service and check status.

	snap start factorio-headless
	snap stop factorio-headless
	snap start --enable factorio-headless
	snap stop --disable factorio-headless
	snap services | grep factorio-headless

Server files location.

	ls /var/snap/factorio-headless/common
