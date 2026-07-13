# Hardware Files

3D models for the ESK-1 Starter Kit boards, provided so the community can design cases, mounts, and other accessories.

```
hardware/
├── cad/
│   └── pcb-placeholders/   # STEP models of each board — reference solids for case design
└── 3d-prints/
    └── Starter Kit Stand.stl
```

## `cad/pcb-placeholders/`

STEP models of the Starter Kit PCBs. These are **placeholders, not finished parts** — import them into your CAD tool as reference geometry to design enclosures and mounts that fit around the real boards.

| File | Board |
|------|-------|
| `ESP32-C6 Mainboard.step` | ESK-1 main board |
| `PIR Module.step` | PIR motion sensor |
| `Temperature and Humidity Module.step` | Temp/humidity sensor |
| `LED and Buzzer Module.step` | Notification puck |
| `Button Module.step` | Button |
| `Breakout Module.step` | [Breakout Module](https://wiki.apolloautomation.com/products/ESPHome-Starter-Kit/modules/apollo-breakout-module/) (optional add-on, sold separately) |

## `3d-prints/`

Ready-to-print parts. Slice and print as-is.

| File | Part |
|------|------|
| `Starter Kit Stand.stl` | Display/desk stand for the kit |

## Contributing designs

Built a case or mount you'd like to share? See [CONTRIBUTING.md](../CONTRIBUTING.md).
