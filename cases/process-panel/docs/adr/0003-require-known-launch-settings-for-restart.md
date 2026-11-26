# Require known launch settings for restart

Windows process discovery can leave the working directory and temporary environment variables of a terminal launch unknown. The panel requires known launch settings before restarting an active launch or starting a stopped project again. The owner can still stop a confirmed launch when its relaunch settings are unknown.

From the launch row, the owner can confirm the working directory and supply any arguments and environment variables needed to run `npm run dev` again. The panel keeps manually supplied settings for that row until the page reloads or closes.
