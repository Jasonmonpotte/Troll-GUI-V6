You will also find this REAM ME file inside the project.

TrollGUI V6 - README

	🧪 DESCRIPTION:
	---------------
	TrollGUI V6 is a trolling interface designed to only be visible to specific users.
	This version is optimized for reliability, performance, professionalism and customization.

				🛠️ SETUP INSTRUCTIONS:
				-----------------------
				1. In `StarterGui > TrollGUI > Permission`, open the LocalScript.
				2. Change the users for your troller team:


				local Players = game:GetService("Players")
				local player = Players.LocalPlayer

				-- List of users who can see the TrollGUI
				local allowedUsers = {
					"jason_monpotte", <-- me (the debugger / Suggest to not remove)
					"your_troller1", <-- Change those usernames to your troller(s)
					"your_troller2",
					"your_troller3"
				}
				
				...
				
				
	Note: I'm currently working on a better UI/system. Should be released on the V6.2
	
	⚠️ IMPORTANT:
		Extra Folder: Unupdated. (V5) -- Can be deleted
		WIP Folder: Work in Progress. (V6.1) -- Can be deleted
		
		This version is a new "model". The UI is different from the previous versions.
		You can delete the "Extra" and "WIP" folders if you want.
