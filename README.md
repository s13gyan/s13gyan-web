# Docker Practice Lab (Node.js)

A small local website for practicing beginner Docker commands. The terminal is a simulation: it does not execute Docker commands or create real containers.

## Requirements

- Node.js 18 or newer
- npm (included with Node.js)

## Start the app

Open PowerShell in this folder and run:

```powershell
npm start
```

Then open <http://127.0.0.1:3000> in your browser. To stop the local server, return to PowerShell and press `Ctrl+C`.

The server uses Node.js built-in modules only, so there is no `npm install` step. It listens on `127.0.0.1` so the practice site is available only on your own computer by default.

## Practice missions

Pull an image, run a web container, list containers, view logs, stop the container, and remove it. Your mission progress is saved in your browser.

The server also exposes `GET /api/health`, which returns a small JSON status response.
