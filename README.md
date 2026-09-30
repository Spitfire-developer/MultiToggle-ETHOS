# MultiToggle for ETHOS

## Turn the ETHOS touchscreen into an additional control panel

**MultiToggle** is a compact, configurable touchscreen panel for **FrSky ETHOS** radios.

It allows multiple independent 2-position or 3-position controls to be placed directly on the ETHOS touchscreen, giving complex models and applications an additional control surface without requiring an additional physical switch for every function.

> **Keep the physical switches for the functions that need immediate tactile control. Use the touchscreen for the many simpler functions.**

This simple idea can be useful far beyond model aircraft.

---

## ✦ One Panel. Many Functions.

MultiToggle provides a configurable collection of touch-operated toggles that are automatically arranged on the screen.

**Eight toggles** provide a particularly clean and comfortable layout for the standard display, but eight is not intended as a fixed limitation of the concept.

The toggle size can be reduced when necessary, allowing the panel to accommodate **more controls when an application requires them**.

The user can therefore choose between:

- fewer, larger controls for maximum readability
- more, smaller controls for applications requiring many functions

The active controls are **automatically distributed across the available display area**, without requiring manual positioning of every toggle.

---

## ✦ Every Toggle Is Configurable

Each individual toggle can be configured independently.

For every control you can choose:

- **Active / inactive**
- **Custom title**
- **2-position or 3-position operation**

The custom title is an important part of the concept.

On a complex model, vehicle or machine, a simple graphic control is not enough — the operator needs to know **what that control actually operates**.

For example:

- `NAV LIGHT`
- `LANDING`
- `PUMP 1`
- `PUMP 2`
- `RADAR`
- `SIREN`
- `WORK LIGHT`
- `FAN`

The labels make the touchscreen panel immediately understandable even when many functions are present.

---

## ✦ 2-Position and 3-Position Controls

Each toggle can operate as either a 2-position or 3-position control.

### 2-Position

`-100 ↔ +100`

### 3-Position

`-100 ↔ 0 ↔ +100`

The user simply touches the appropriate area of the control to select the required position.

The graphical representation changes accordingly, providing a clear visual indication of the current state.

---

# Why Use Touchscreen Controls?

Modern models and machines can contain a large number of secondary functions.

The number of physical switches available on a transmitter is limited, and those switches are often better reserved for functions where a fast, tactile response is important.

MultiToggle provides another possibility.

Instead of trying to assign every function to a physical switch, the touchscreen can become an **additional operator panel**.

This can leave the transmitter's physical controls available for the functions where they are most useful.

---

## Possible Applications

The concept is particularly suitable for applications with **many simple auxiliary functions**.

### ✈ Aircraft

- navigation lights
- landing lights
- strobes
- smoke
- cooling systems
- auxiliary equipment
- lighting systems

### 🚤 Boats

- navigation lights
- pumps
- bilge pumps
- horns
- auxiliary systems
- lighting

### 🚜 Construction & Industrial Machinery

- work lights
- warning lights
- pumps
- auxiliary motors
- hydraulic functions
- sirens
- auxiliary equipment

### 🚙 Vehicles & Special Projects

- lighting
- fans
- pumps
- cameras
- radar
- warning systems
- auxiliary equipment

The same principle can be applied to virtually any ETHOS application where a large number of simple controls are required.

---

# Automatic ETHOS Variables

MultiToggle is designed to keep the configuration simple.

The panel uses ETHOS variables automatically:

`VAR1` → first toggle  
`VAR2` → second toggle  
`VAR3` → third toggle  
`...`  
`VAR8` → eighth toggle

No individual source assignment is required for the controls.

The corresponding ETHOS variables can then be used by the model configuration for the desired functions.

This makes the widget flexible: the touchscreen control does not need to know whether it is operating a light, pump, siren, radar or another auxiliary function.

---

# A Touchscreen Extension of the Transmitter

MultiToggle is **not intended to replace physical switches**.

It is intended to complement them.

A complex application can therefore use two levels of control:

### Physical Switches

For functions requiring:

- immediate access
- tactile feedback
- fast operation
- dedicated control

### Touchscreen Panel

For functions that are:

- secondary
- numerous
- used occasionally
- simple ON/OFF or 3-position functions

This approach can increase the number of available controls without physically modifying the transmitter.

---

# A Building Block for Larger Control Systems

MultiToggle is deliberately presented as a **standalone component**.

However, the underlying concept can also become part of larger configurable touchscreen systems.

For example:

```text
CONTROL PANEL
│
├── Lighting
├── Navigation
├── Pumps
├── Auxiliary Functions
├── MultiToggle Panel 1
├── MultiToggle Panel 2
└── Other Controls
```
This is also one of the concepts being explored in the wider **SpitFW** project.

---

# Lightweight Implementation

The demonstration is intentionally compact.

The current version is provided as a **single compact Lua/LuaC widget**, making it easy to test in the ETHOS simulator and on compatible ETHOS radios.

The graphical toggle is generated by code rather than requiring a large collection of bitmap assets.

The result is a small, self-contained demonstration focused on the actual concept:

> **The ETHOS touchscreen as an expandable control surface.**

---

# Try the Demo

### ETHOS Simulator

**[Online ETHOS Simulator Demo — coming soon]**

The online simulator allows the concept to be tested directly in a browser before installing it on a physical transmitter.

**Open the simulator → add MultiToggle → activate and configure the controls → touch the panel.**

---

# Screenshots

_Add screenshots here showing the MultiToggle panel in the ETHOS simulator._

---

# Project Status

MultiToggle is currently an **experimental / demonstration component**.

The project is intended to demonstrate the concept, provide a working implementation and encourage technical feedback from the ETHOS community.

Future development may include additional control types, more advanced panel organization and integration with larger ETHOS applications.

---

# The Idea Behind the Project

The important part of MultiToggle is not simply putting several buttons on a screen.

The idea is to treat the **ETHOS touchscreen as an additional control surface**.

When an application requires more simple controls than the physical transmitter can conveniently provide, the touchscreen can become a practical extension of the operator interface.

**More functions do not necessarily have to mean more physical switches.**

---

# Related Project

MultiToggle is an independent demonstration component developed as part of the ongoing exploration behind **SpitFW**.

**[SpitFW – A Modular Scale Cockpit Framework for ETHOS](https://github.com/Spitfire-developer/spitfw-presentation)**

---

### Author

**by Spitfire-developer**

Developed as part of the ongoing exploration of advanced touchscreen control and modular control-panel concepts for FrSky ETHOS.

Feedback, testing and technical discussion are welcome.


## License
This project (compiled release) is distributed under CC BY-NC-ND 4.0.
See the LICENSE file for details.
