# twprp_whitelistjobchanger
 Made by Roids#9757 for The Wack Pack RP



Congrats you found this! I'm not going to be posting this anywhere( so please return the favor by keeping it to yourself also 😊 ) but since you found it, here you go lol! 

Fair warning: The odds of me breaking this repo are VERY high lol So please keep that in mind. If there are any issues at the time of you downloading it please either dm me on discord or open up an issue here lol

As is there are only 3 commands. `/lawman - changes job to police`, `/doctor - changes job to doctor`, `/offduty - changes job to VORP default job(none)`

Adding it to your server:
- Add twp_whitelistjobchanger to your resources folder
- Add `ensure twp_whitelistjobchanger` to your `server.cfg`

Creating a NEW whitelisted job:
- Add a new table with whatever you want the job to be called inside the `config.lua`
- Inside the table you can add the persons steamid64 in hex. This person is now whitelisted
- In the `main_cl.lua` add a new `RegisterCommand` for the job you created in the config
- Lastly just have the person use the command you created in `main_cl.lua`


To Do:
- Add Discord role integration(waiting on RedM to pull discord ids lel)

Done(from to do):
- Streamline the server side to only use one function and event for all jobs(would you look at that didnt need discord after all lmao)
