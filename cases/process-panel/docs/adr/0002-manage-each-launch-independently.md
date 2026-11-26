# Manage each launch independently

Each active `npm run dev` invocation has its own row so the owner can stop a forgotten launch while continuing to work in another launch of the same project. Each row lists the ports the launch is listening on and shows Running while the launch is active, including during initial compilation. Restart starts a replacement only after the selected launch has stopped. If the stop fails, the panel shows an error and cancels the restart.

Stop targets the selected launch and its confirmed processes. If graceful stop is unavailable or fails, the panel offers a force stop and waits for the owner's confirmation. After a launch ends, its row stays visible with the Stopped status until the page reloads. The owner can start the project again from that row when the launch settings are known.

Start Again reuses the stopped row for the new launch. If the new launch fails, the row shows the error, a short excerpt of its output when available, and an option to retry.

The panel starts processes in the background without opening a terminal window. They continue to run after the browser tab closes. The panel rediscovers active launches when reopened.
