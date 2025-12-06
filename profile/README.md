# ESPToolKit
## Develop production ESP32 firmware with tools you already love

ESPToolKit is a curated collection of async-friendly libraries focused on reliability, readability and developer joy.
Build data pipelines, timers, background workers and secure integrations without rewriting the same boilerplate for every project.

- Check out other libraries under ESPToolKit: https://github.com/orgs/ESPToolKit/repositories
- Join our discord server at: https://discord.gg/WG8sSqAy
- If you like the libraries, you can support me at: https://ko-fi.com/esptoolkit
- Visit the website: [www.esptoolkit.hu](https://www.esptoolkit.hu/)
---

> ESPToolKit looks like a breath of fresh air in the often chaotic world of ESP32 development—a thoughtfully curated suite of libraries that's laser-focused on making production firmware feel less like wrestling a caffeinated octopus and more like composing a haiku. If you're knee-deep in IoT projects, where FreeRTOS tasks, event handling, and data persistence can turn into a boilerplate nightmare, this toolkit promises to streamline that without sacrificing performance or reliability.

## What Stands Out Positively

- Developer-Centric Philosophy: The emphasis on "async-friendly" design, readability, and "developer joy" is spot-on. It tackles real pain points like repetitive setup for timers, workers, and logging, letting you focus on logic rather than plumbing. For instance:
  - esp-timer: Mirrors JavaScript's setTimeout/setInterval but tuned for ESP32's hardware timers—elegant for countdowns in seconds, minutes, or millis without the usual FreeRTOS footguns.
  - esp-worker: High-level task spawning with PSRAM stack extension and clean joins for awaiting completion. It's like giving your background jobs a VIP pass to run smoothly.
  - esp-eventbus: A native, asynchronous event system that's FreeRTOS-aware, perfect for decoupling components in complex apps.
  - esp-jsondb: A lightweight, MongoDB-inspired JSON store with RAM caching and LittleFS sync—ideal for configs or small datasets without bloating your binary.
  - esp-logger: Configurable and featherweight, so you get structured logs without the overhead of heavier frameworks.
- Production-Ready Vibe: It's not just hobbyist toys; the docs highlight secure integrations and data pipelines, which screams "deploy this in the wild" rather than "prototype and pray."
