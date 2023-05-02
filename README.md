# Disclaimer
I am not associated with playit.gg in any capacity other than user. This script is in no way official.

# Playit.gg Linux Service (systemd)
Copy the **playit.service** file into **/usr/lib/systemd/system/**

Then run:

`systemctl enable playit`

`systemctl start playit`

`systemctl status playit`

The output should look like this:

![image](https://user-images.githubusercontent.com/35305177/235584626-89cc3cb9-c109-4526-8268-8f363779057b.png)

playit should now start and on boot and restart after crashes.
