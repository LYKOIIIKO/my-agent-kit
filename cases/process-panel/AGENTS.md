# Process Panel

## Local startup

- Implement `npm start` in `cases/process-panel` as the single command that starts the panel on Windows. It runs under the owner's standard Windows account.
- Serve the web interface at `http://127.0.0.1:4317/` and the HTTP API on the same origin. Bind only to `127.0.0.1`.
- If port `4317` is occupied, stop startup and report the address in the error.

Use `npm start` so the panel's own startup stays outside discovery of `npm run dev` project launches.
