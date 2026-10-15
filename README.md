# Synergy Live Typing

Type on a phone or laptop; the words appear live on the event's big screen.

Open the site with no `#` part to get a fresh pair of links:

- `#screen/<code>` — the laptop connected to the projector (click once for full screen)
- `#type/<code>` — the phone, iPad or laptop used for typing

No sign-in. Updates go through two public MQTT brokers (HiveMQ and EMQX) over secure WebSockets, so the screen keeps working if one is unavailable. Keep the links private: anyone with the typing link can write on the screen.
