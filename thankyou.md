Thank you for purchasing a turn-key Pwnagotchi! You have everything needed for your Pwnagotchi to begin eating WiFi handshakes within minutes of plugging into a power source! Here are a few considerations for your first power-on and basic usage:

**First Power-On Considerations:**
1. **Insert the SD Card:** Ensure the SD card is properly inserted into your Pwnagotchi. It is preinstalled but check it didn’t move in transit.
2. **Power Up:** Connect your Pwnagotchi to a power source using any micro-USB cable to the power connector. The included cable is a data cable useful for either power or connecting to your computer using the data connector.
3. **Initial Boot:** Allow a few minutes for the initial boot process. On first boot only the device will generate unique cryptographic keys which takes several minutes. It is important to let this finish. The device will configure itself automatically and begin eating WiFi handshakes.

**Basic Usage:**
Although the Pwnagotchi will work and eat WiFi handshakes without any further customization, you will probably want to do something with those handshakes, or further customize it to not eat handshakes for your own WiFi networks. To do that you need to connect it to your computer and customize it’s configuration.

1. **Connect Power:** The Pwnagotchi has two microUSB ports. The one closest to the edge is for power. If you take this around for walks and rides you will want to use a portable power source. Pwnagotchi gets bored scanning the same networks so take him out into the world with you!
2. **Connecting via SSH:** Once powered on, connect to your Pwnagotchi via SSH via the data cable using the default credentials (username: `pi`, password: `raspberry`).
3. **Configuration:** Customize your Pwnagotchi by editing the `config.toml` file located at `/etc/pwnagotchi/config.toml`. You can use the command `sudo nano /etc/pwnagotchi/config.toml` to make changes.

For more detailed instructions and tips, please refer to the official [Pwnagotchi documentation](https://pwnagotchi.ai/configuration/#connect-to-your-pwnagotchi) https://pwnagotchi.ai/configuration/#connect-to-your-pwnagotchi

pwnagotchi was created by [@evilsocket](https://github.com/evilsocket) and maintained by [@jayofelony](https://github.com/jayofelony). It is released under the GPL3 license
https://github.com/jayofelony/pwnagotchi

