# Alien Arena Server Status Checker (1.0.0)
Allows you to get the status of your Alien Arena server(s) -  Official support sites: [Official Github Repo](https://github.com/fstltna/AlienArena_Status) - [Official Forum](https://alienarena.gameplayer.club/index.php/forum/alien-arena-tools)

---

1. Edit "aastatus". Set the server list near the top of the file and the email address to send updates to.
2. Run "./aastatus" and see if it reports an error

I then suggest you add this directory (AlienArena_Status) into your path, so that you can just run "git pull" to upgrade to the latest version aastatus as updates come out.

Add this to your crontab file:

	10 1 * * * /root/AlienArena_Status/aastatus
	
