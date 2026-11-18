# AK Embedded Training – Learning Log

My learning log for the [AK Foundation](https://github.com/the-ak-foundation) embedded training program, done during my internship at EPCB. The program is built around the **AK Embedded Base Kit** (STM32L151, 1.54" OLED, 3 buttons, buzzer) and event-driven firmware: tasks, signals, timers and state machines.

**Goal:** design and build a complete game on the base kit, judged on gameplay, clean code, design documents that match the code, and how finished it is. My game idea: **a piano game**.

## Progress log

Daily notes are written in Vietnamese, with screenshots and references to the ST manuals.

| Date | Topic |
|---|---|
| [2026-11-15](notes/2026-11-15.md) | Explored the kit's built-in games, read the training program and the archery game, set up the build toolchain (WSL Ubuntu 24.04 + GNU Arm 10.3) |
| [2026-11-17](notes/2026-11-17.md) | Backed up the kit firmware with ST-Link: SWD hot-plug connection (UM0892), read Device ID 0x416, 64 KB flash (RM0038 flash size register), checked read-out protection level 0; chose the piano game mechanics |

## Repository layout

    notes/          One Markdown file per day
    notes/images/   Screenshots used in the notes (reviewed and compressed)

ST datasheets and reference manuals are not included (ST copyright); the notes cite them by document number and section.
