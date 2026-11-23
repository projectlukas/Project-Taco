# 🌮 Project Taco

![Status](https://img.shields.io/badge/status-in%20testing-yellow)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Keyboard support](https://img.shields.io/badge/keyboards-Deltaco%20keyboards-orange)
![Tested](https://img.shields.io/badge/tested%20only%20on-GAM--075%20W-lightgrey)

<p align="center">
  <img src="IMG_7727.png" alt="Project Taco Logo" width="1500x500" />
</p>

A custom Windows desktop app for controlling the RGB lighting on the Deltaco GAM-075 W mechanical keyboard with a dark minimalist interface and splash screen. It is being built as a bug-free, modern alternative to the buggy, outdated official software, with testing actively in progress and basic lighting controls already working. Tested only on GAM-075 W. Project Taco will also be open-sourced so community members can add support for their own Deltaco keyboards, test them, and get credits for helping bring new models on board. It also aims to support OpenRGB integration so keyboard lighting can match the rest of your setup, including ARGB fans and other RGB devices.

Project Taco is a custom Windows desktop application created to control the RGB lighting on the Deltaco GAM-075 W mechanical keyboard without relying on the official software. It combines direct lighting controls with a dark, minimalist interface, a custom taco-keycap icon, and a startup splash screen.

The idea behind the project is straightforward: give Deltaco keyboards a dedicated, clean desktop home where adjusting lighting feels easy, intentional, and reliable instead of frustrating. Rather than leaning on heavy, clunky, or inconsistent tools for everyday lighting changes, Project Taco focuses on a streamlined experience built specifically around this hardware, with plenty of room to grow as development moves forward.

Whether you want to tweak your setup for a quiet evening, match a dark desk aesthetic, or switch up lighting modes on the fly, Project Taco is designed to keep the experience simple, focused, and pleasant to use. Good hardware deserves software that respects the user's time and attention, without unnecessary friction standing between you and the look you want on your desk.

## How the Program Works

- Project Taco acts as a lightweight Windows desktop controller that communicates directly with supported keyboard lighting interfaces and translates your UI adjustments into clean hardware commands.
- When launched, the application opens with a custom splash screen before loading a dark, focused control workspace designed to keep essential lighting options clear and accessible.
- Users can select colors, switch between built-in lighting modes and effects, and adjust parameters like brightness and speed with predictable, immediate feedback on the keyboard.
- Under the hood, the architecture is structured around reliable parameter handling, validation, and careful edge-case testing so that changes apply consistently without glitches, freezes, or unexpected resets.
- As the codebase matures, the design leaves room for modular device profiles, deeper customization such as per-key lighting, and synchronization with external RGB ecosystems.

## Why I'm Making This

- The official software feels buggy and unreliable, so I wanted a cleaner, more dependable way to control the keyboard's lighting.
- The stock interface looks outdated, whereas Project Taco aims for a sleek, dark, minimalist aesthetic with its own identity and taco-keycap branding.
- Dealing with rough, unpolished, or bloated software just to change basic lighting settings gets old fast, so I am building a focused desktop app made specifically for this keyboard.
- A core goal of this project is making colors, brightness, speed, and lighting modes work smoothly and predictably without bugs.
- Building my own tool also lets me shape the interface, layout, workflow, and future features around how the keyboard is actually used day to day.
- I want the app to feel cohesive from the moment it opens—starting with a clean splash screen and leading into an uncluttered workspace that doesn't get in the way.
- Creating a dedicated app gives me full control over how changes are applied and how the experience feels over time, rather than settling for quirks in the official utility.

## What This Project Is About

Project Taco is all about taking everyday control of Deltaco RGB lighting into a clean, dedicated Windows app. Instead of scattering basic controls across confusing menus or dated screens, it brings the essentials together in one place.

At its heart, the project is about making lighting customization feel approachable, calm, and consistent while building a strong foundation for everything that comes next.

It centers on:

- Choosing colors, switching lighting effects, and tuning brightness and speed.
- Launching through a custom splash screen into a dark, uncluttered interface.
- Keeping the layout calm, modern, and easy to navigate without unnecessary visual noise or clutter.
- Giving the app a clear visual identity with custom taco-keycap branding that feels distinct and memorable.
- Getting the core lighting controls rock-solid first, then expanding into deeper customization like per-key lighting over time.
- Refining how individual settings and parameters interact so every change feels consistent and accurate.

## OpenRGB and Setup Sync

- OpenRGB integration is planned so Project Taco can coordinate lighting with the rest of your setup, including ARGB fans and other connected RGB hardware.
- Syncing with OpenRGB makes it easier to keep your keyboard colors and vibe unified across your whole desk and PC build.

## Open Source and Community Models

- Project Taco is planned to be open-sourced once the core foundation is in good shape.
- Community members will be able to add support for their own Deltaco keyboards and test how they behave.
- Anyone who contributes model support, testing, or feedback will get credits for helping expand compatibility across more Deltaco keyboards.

## How You Can Help

- **Add and test new Deltaco models:** If you own a different Deltaco keyboard, you can help bring support for it into the project by mapping out or adapting model support and testing how the hardware responds.
- **Run thorough lighting tests:** Test color selection, brightness levels, effect speeds, lighting modes, and edge cases on real hardware to catch quirks or unexpected behavior early.
- **Use Claude AI to assist with test creation:** If you are unsure how to write or expand the needed test routines, check edge cases, or draft device configuration updates for your keyboard, you can use Claude AI to help generate the necessary tests and troubleshoot differences.
- **Report findings and share configs:** Document what works, what behaves differently, and any edge cases you discover so changes can be merged cleanly and accurately.
- **Get recognized:** Every contributor who helps test models, add keyboard support, or improve reliability will receive credit in the project.

## Status and Testing

- Tested only on GAM-075 W.
- Testing is actively in progress across lighting behaviors, colors, brightness, speed, and effects.
- Basic lighting control, colors, brightness, speed, and built-in effects are already working on the keyboard.
- The desktop window and splash screen launch, and packaging the app as a standalone executable is underway.
- I am carefully checking parameter behavior and edge cases so lighting updates stay accurate and bug-free rather than assuming everything works on the first try.
- Catching and resolving subtle issues now helps build a much more stable foundation before adding more complex options.
- Every test pass brings the app closer to feeling solid, dependable, and ready for everyday use without rough edges.
- Per-key lighting, deeper customization, OpenRGB sync, open-source community expansion, Claude-assisted test creation, and extra polish are still ahead as development continues and the project matures.
