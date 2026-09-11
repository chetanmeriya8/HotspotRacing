# Hotspot Racing — Android Prototype

## What it does
A starter 2-player local Wi-Fi racing prototype. One Android phone hosts a TCP game session and other phones join through the host phone's hotspot. No Internet is required.

## Build
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Connect an Android phone and Run, or use Build > Build APK(s).

## Play
1. Host phone: turn on Mobile Hotspot.
2. Other phones: connect to that hotspot.
3. Host opens the app and taps CREATE RACE.
4. Players tap JOIN RACE and enter the host phone's local hotspot IP (commonly 192.168.43.1, but it can vary).
5. Race using the on-screen left/right controls.

## Important
This is a prototype foundation, not a polished commercial game. Android hotspot IPs and client isolation settings vary by phone manufacturer. The next iteration can add 4-player lobby/discovery, proper physics, countdown, traffic, collision, sounds, car selection and a polished track.
