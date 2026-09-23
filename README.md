# Deepak Popli

I'm a firmware engineer from India. I build software for drones and robots: the code that keeps them flying safely, and tools that let AI control them. Most of my work is on ArduPilot, the open-source autopilot, and lately PX4 too.

## Open source

12 merged pull requests in ArduPilot and its tools. A few of them:

- [Stopped a Rover failsafe from firing before the vehicle had a position fix](https://github.com/ArduPilot/ardupilot/pull/33016)
- [Kept Rover on its main position estimate in poor GPS, instead of flip-flopping to a backup](https://github.com/ArduPilot/ardupilot/pull/33392)
- [Fixed creating new files on the flight controller over MAVLink](https://github.com/ArduPilot/ardupilot/pull/31872)
- [Added a test that Rover recovers properly after losing its ground station](https://github.com/ArduPilot/ardupilot/pull/32277)
- [MAVProxy now tells you when a takeoff is rejected, instead of saying it started](https://github.com/ArduPilot/MAVProxy/pull/1653)

[All of them](https://github.com/search?q=author%3Adeepak61296+org%3AArduPilot+is%3Apr+is%3Amerged&type=pullrequests)

## Projects

**[mavlink-mcp](https://github.com/deepak61296/mavlink-mcp)**: lets an AI agent fly full missions on a drone. It plans the route, flies it, looks through the camera and decides what to do next. [Demo](https://www.youtube.com/watch?v=pyfqyfYUces)

**[Companion computer failsafe](https://github.com/deepak61296/ap-companion-health-monitor-failsafe)**: many drones carry a second computer for things like vision and navigation. If it crashes or freezes mid-flight, the drone usually doesn't notice. This watches that computer and, if it stops responding, warns the pilot, brings the drone home or lands it. [Demo](https://www.youtube.com/watch?v=GweYXp5yXuU)

**[Rocky](https://github.com/deepak61296/rocky-cyberwave)**: a small robot that talks with you live, remembers your conversations, sees through its camera and finds its way around the room. 1st place, solo track, Cyberwave Builders program (Aug 2026).

## Work

Firmware engineer at Airbotix Technology since June 2025. I write drone firmware and a ground station that flies many drones at once.

## Contact

[LinkedIn](https://linkedin.com/in/deepak-popli) | [Email](mailto:deepakpopli002@gmail.com)
