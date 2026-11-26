# Discover existing Windows launches

The first version discovers `npm run dev` launches started directly in Windows from PowerShell or the VS Code terminal, including launches that were already running when the panel opened. The owner can keep using their usual launch commands and find forgotten projects later. The panel is available only on the computer where the projects run.

The panel runs with standard permissions under the owner's Windows account and lists confirmed `npm run dev` launches from that account. While the page is open, it refreshes the list, statuses, and listener ports automatically.
