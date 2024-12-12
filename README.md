# batteryctl-openrc
Simple OpenRC script to save and restore /sys/.../charge_control_end_threshold


### Default value on initial boot
The default value is to charge to `79`% only.


### How to use this?

1. Save the `batteryctl` file into `/etc/init.d/batteryctl`

2. Set `/etc/init.d/batteryctl` permissions to `755` and owner to `root:root`

3. Enable the service with :`rc-update add batteryctl sysinit`
