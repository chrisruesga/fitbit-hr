# fitbit-hr
Fitbit web HeartRate Monitor

By default, the browser's Bluetooth picker shows devices advertising the Heart Rate
service. Turn on **Show all Bluetooth devices** before connecting to see other
available Bluetooth Low Energy devices for debugging or selection. The browser
controls which devices appear, and a device must expose the standard Heart Rate
service and measurement characteristic to display readings.

If the picker does not appear, check that Bluetooth is enabled and the browser
has Bluetooth permission. The error shown on the page includes the browser's
details; a cancelled picker may also be reported as a selection failure.
