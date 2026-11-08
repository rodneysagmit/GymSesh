# GymSesh

A fast, offline-friendly workout tracker. Log sets, reps, weight and rest right from your phone while you lift.

## Features

- Log weight, reps and rest for each set, plus set notes; tap the set number to mark a warm-up
- Prefill a workout, then tick each set's **Done** checkbox as you go. Completed sets fade so the next one stands out
- **Rest timer:** tap ▶ in a set's Rest box to start, ■ or **Stop** to end it. The time is saved as m:ss and keeps running if the screen locks. You can also type rest in by hand
- **Finish** asks whether to leave out or include filled-in sets you never checked off
- *Start from last* reloads your previous workout for the same focus, with last time's numbers as hints
- Copy or share the finished workout as plain text

GymSesh is a single HTML file of vanilla JavaScript — no backend, no build step, no dependencies. Your drafts and history are saved in the browser's `localStorage` on your device, so it keeps working without a connection. When you finish a workout you can copy or share it as plain text to hand off to your log and dashboard.

## Run it locally

It's just one file, so you can open it directly:

```
open index.html
```

Or serve it over HTTP (useful if your browser restricts features on `file://`):

```
python3 -m http.server
```

Then visit <http://localhost:8000/>.

## Deployment

GymSesh deploys via GitHub Pages from the root of the `main` branch and is live at:

https://rodneysagmit.github.io/GymSesh/
