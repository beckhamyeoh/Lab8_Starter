# Lab 8 - Network & Service Workers

## Lab Partner(s)
<!-- TODO: add name(s) here -->

## Deployed Site
https://beckhamyeoh.github.io/Lab8_Starter/

## Graceful Degradation & Service Workers
Graceful degradation is the practice of building an app with full functionality first and then making sure it still works acceptably when conditions get worse — and a network connection is exactly the kind of condition we can't control. Service workers are a concrete tool that makes this possible: by sitting between the app and the network, they intercept requests and can serve cached responses when the network is slow or completely gone. Instead of the app breaking when offline, it degrades gracefully from "live data over the network" down to "cached data from the browser," giving users a usable experience either way. In short, service workers are one of the cleanest implementations of graceful degradation for network dependency.

## PWA Screenshot
![Installed PWA](pwa.png)
