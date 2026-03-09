# OneTwenty Glucose Clock

An ambient display for family and caregivers that glows and displays current glucose levels, trending arrows, and age of the reading. Polls the OneTwenty backend API in real-time.

## Tech Stack
- **Hardware**: ESP32, MAX7219 Dot Matrix Display (FC-16)
- **Language**: C / C++ (Arduino Framework)
- **Libraries**: `MD_Parola`, `MD_MAX72xx`, `WiFi`, `HTTPClient`

## Getting Started

1. Configure your `ssid` and `password` in `clock.c`.
2. Update the `apiUrl` with your OneTwenty backend endpoint.
3. Flash the code to your ESP32 device using the Arduino IDE or PlatformIO.
4. The matrix display will automatically connect to WiFi, sync time, and show the glucose readings.
