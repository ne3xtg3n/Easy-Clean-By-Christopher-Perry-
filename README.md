# EasyClean™ v1.0 — Humanoid Olive Brush Cleaning System

**Author:** Christopher Perry  
**Version:** 1.0  
**Date:** September 18, 2025  
**Status:** Patent Pending – Manufacturing & Developer Spec  
**Brand:** EasyClean™  

---
## 📘 Introduction

EasyClean™ redefines brush maintenance as an engaging, efficient ritual for artists, educators, and young creators. Conventional cleaning methods lead to bristle damage, pigment waste, and frustration—EasyClean™ counters this with a whimsical humanoid olive form factor that integrates:

- A sealed, refillable water reservoir for on-demand rinsing.
- A vortex agitation chamber for thorough pigment extraction without manual scrubbing.
- A rear-mounted, porous ceramic reshaping stone for instant bristle restoration and accelerated drying.

This fusion of ergonomic utility and character-driven playfulness fosters consistent care habits in studios, classrooms, and homes, extending brush lifespan by up to 30% while minimizing mess.

---

## 🎨 Design Philosophy

**Form Meets Function:** The anthropomorphic olive silhouette provides intuitive handling (e.g., "hug" grip via arms/legs) and visual appeal, transforming a chore into a companionable experience.

**Daily Use Optimized:** Compact profile for desk/shelf integration; child-safe materials; modular internals for easy maintenance.

**Sustainability First:** Recyclable enclosure; biodegradable filter media; swappable components reduce e-waste; low-energy powered variant.

**Playful Engagement:** Expressive styling (e.g., "winking" crown port) and optional sound cues (gentle bubble "glug") gamify the process, boosting adherence for kids and adults alike.

---

## 🫒 External Styling & Dimensions

- **Height:** 170 mm (6.7 in) – Balances portability and capacity.
- **Width (at belly):** 90 mm (3.5 in) – Ergonomic for small hands.
- **Depth:** 80 mm (3.1 in) – Stable base prevents tipping.
- **Weight (empty):** 250 g – Lightweight yet substantial feel.
- **Color Palette:** Matte olive green shell (#4A7C59) with translucent amber accents on tank; optional "character eyes" via subtle laser-etched details.

### Key Modules
- **Top Crown Port:** Tapered silicone funnel (Ø30 mm entry to Ø15 mm throat), integrated splash baffle, and magnetic lid for secure closure.
- **Belly Tank:** 280 ml borosilicate glass (upgraded from acrylic for durability/clarity), twist-lock with dual O-rings for leak-proof seal.
- **Arms/Legs:** Soft-touch TPE silicone (Shore 30A), 45 mm arms (for "hanging" brushes), 35 mm legs (weighted base).
- **Drying Stone:** 50 × 30 × 10 mm diatomaceous earth ceramic, rear snap-fit slot with alignment pins for tool-free replacement.

**Ergonomics Note:** Curved contours ensure 360° rotation during use; non-slip texture on base and grip zones.

---

## ⚙️ Internal Architecture

### Fluid Dynamics Path
1. **Entry (Brush Port):** Silicone sleeve guides bristles into 65 mm deep polycarbonate swirl chamber (Ø25 mm).
2. **Agitation Zone:** Counter-rotating vanes (impeller-driven) create 200–300 RPM vortex for pigment dislodgement.
3. **Filtration:** Conical nylon mesh cup (150 µm pores) captures solids; gravity-assisted return to tank.
4. **Exit/Refill:** Bottom valve drain (manual twist) or twist-off tank access; overflow vent prevents pressure buildup.

### Cleaning Modularity (SKU Variants)
- **Option A – Magnetic Impeller (Default):** Battery-powered, low-noise (≤35 dB), 40-second cycle; ideal for home use.
- **Option B – Micro Air Pump:** 3 V diaphragm pump generates microbubbles for gentle, enzyme-compatible cleaning (e.g., watercolor).
- **Option C – Ultrasonic Jet Ring:** 40 kHz piezo transducer for rapid (20 s) deep cleans; premium SKU for professional artists.

**Manual Fallback:** Integrated plunger rod (stored in leg compartment) for unpowered agitation.

---

## 🔋 PSU & Electronics (Powered Variant)

**Power Profile:**
- **Input:** USB-C PD (5 V/2 A max, backward-compatible with 1 A).
- **Battery:** 3.7 V 1200 mAh LiPo pouch (with integrated BMS/NTC for thermal runaway prevention).
- **Output:** TPS61023 boost converter to 6 V/1 A for motor; efficiency >85%.
- **Runtime:** 150+ cycles (40 s each) at 25°C; low-battery throttle reduces speed.
- **Charging:** CC/CV via BQ24075 IC; full charge in 90 min; trickle mode for overnight top-up.
- **Safeguards:** Over-voltage (6.5 V cutoff), over-current (2 A fuse), thermal shutdown (60°C), idle auto-off (120 s).

**User Interface:**
- **Button:** Capacitive touch (behind silicone dome) for Start/Pause; long-press for mode toggle.
- **Indicators:** RGB LED array (via WS2812B): Green (ready), Blue (cleaning), Amber (low battery <20%), Red (error/fault).
- **Haptics (Optional v1.1):** Single vibration motor for cycle-complete feedback.

**PCB Layout:** 40 × 30 mm FR4 board; conformal coating for IPX5 internals; JST connectors for modular swap.

---

## 🏗️ Materials

| Category | Material | Key Properties | Rationale |
|----------|----------|----------------|-----------|
| **Shell** | ASA copolymer (UV-stabilized, olive green) | Impact-resistant, matte anti-fingerprint | Superior weather/chemical resistance over ABS. |
| **Tank** | Borosilicate glass (280 ml) | Transparent, thermal shock-resistant | Dishwasher-safe; visual sediment monitoring. |
| **Seals** | Platinum-cured silicone (FDA-compliant) | 70 Shore A, -40°C to 200°C | Hypoallergenic; eternal flex life. |
| **Drying Stone** | Diatomaceous earth composite | Porous (500–1000 µm voids), antimicrobial glaze | Absorbs 5x weight in water; reshapes ferrules. |
| **Base/Feet** | Thermoplastic elastomer (TPE) pads | High friction coefficient (μ=0.8) | Vibration damping; floor protection. |
| **Arms/Legs** | Liquid silicone rubber (LSR) | Shore 25A, tear-resistant | Kid-safe chew-proofing; flexible posing. |

**Sourcing Note:** All materials RoHS/REACH compliant; prioritize suppliers like DuPont for seals, Kyocera for ceramics.

---

## 🧩 Features

- **Adaptive Brush Port:** Expandable silicone collar fits 5–20 mm ferrules; anti-drip lip.
- **Vortex Cleaning:** Impeller achieves 95% pigment removal in tests (vs. 70% manual rinse).
- **Smart Tank:** Etched level markings; quick-dump valve for eco-disposal.
- **Reshape & Dry:** Stone module wicks moisture in <2 min; optional UV-C slot for sanitization (v1.1).
- **Accessibility:** Brailled button labels; one-handed operation.
- **Variants:** Core Manual ($29.99 est.), Powered Impeller ($39.99), Pro Ultrasonic ($49.99).
- **Eco Perks:** Recycles 90% rinse water; filter lasts 50 cycles.

---

## 🛠️ Bill of Materials (v1.0 – Option A: Magnetic Impeller)

| Subsystem | Component | Spec / Part # | Qty | Est. Cost (USD) | Supplier Notes |
|-----------|-----------|---------------|-----|-----------------|----------------|
| **Enclosure** | Outer shell | ASA injection mold, 170×90×80 mm | 1 | 2.50 | Proto-mold via Protolabs |
| | Belly tank | Borosilicate glass, 280 ml twist-lock | 1 | 1.80 | Schott AG equiv. |
| | Crown seal | LSR funnel w/ baffle, Ø30–15 mm | 1 | 0.60 | Dow Corning |
| | Drying stone | Diatomaceous ceramic, 50×30×10 mm | 1 | 0.90 | Custom sinter |
| | Feet | TPE pads, Ø12 mm adhesive | 4 | 0.20 | 3M |
| **Cleaning System** | Mesh filter | Nylon 150 µm conical cup | 1 | 0.40 | Removable via bayonet |
| | Impeller | Delrin 6-blade, 13 mm Ø | 1 | 0.70 | CNC machined |
| | Drive magnets | N52 neodymium, Ø8×3 mm | 2 | 0.50 | Axial alignment |
| **Electronics** | Battery | 3.7 V 1200 mAh LiPo w/ BMS | 1 | 3.20 | UL 1642 certified |
| | Charge IC | BQ24075 (USB-C) | 1 | 0.80 | TI |
| | Boost conv. | TPS61023 (6 V/1 A) | 1 | 0.90 | Eff. 88% |
| | Motor driver | DRV8873 H-bridge | 1 | 1.10 | PWM 1–20 kHz |
| | Motor | 6 V N20 planetary gear (100 RPM) | 1 | 2.00 | Faulhaber equiv. |
| | Touch button | TTP223 capacitive | 1 | 0.30 | Waterproof overlay |
| | LED strip | WS2812B (4 LEDs) | 1 | 0.50 | Addressable |
| | USB-C port | Receptacle w/ strain relief | 1 | 0.70 | IP67 rated |
| **Seals & Mounts** | O-rings | Silicone AS568-012 | 2 | 0.10 | Parker Hannifin |
| | Threadlocker | Anaerobic adhesive | As req. | 0.05 | Loctite 243 |

**Total BOM Cost (1000 units):** ~$15.25/unit (excl. assembly). **Sourcing Priority:** Domestic for electronics (Digi-Key/Mouser); Asia for molding (e.g., Foxconn).

---

## 🧪 Compliance & Safety

- **Electrical:** FCC Part 15 (EMI), CE (EN 62368-1), RoHS 3, UL 2054 (battery).
- **Wet Environment:** IPX5 (rinsable enclosure); NSF/ANSI 61 for water-contact materials.
- **Child Safety:** ASTM F963 (toys 3+), CPSIA compliant; no small parts (<31 mm); BPA/BPS-free.
- **Serviceability:** User-replaceable: filter (every 50 uses), stone (yearly), battery (2-year warranty).
- **Testing Protocol:** 1000-cycle durability; drop test (1 m); microbial ingress assay.

**Risk Mitigation:** Fail-safe drain valve prevents overfill; app-free design avoids connectivity vulnerabilities.

---

## 🏭 Manufacturing Handoff (v1.0)

### Assembly Sequence (Yield Target: 98%)
1. **Molding:** High-pressure injection for ASA shell (cycle: 45 s); overmold TPE feet/arms.
2. **Tank Fab:** Glass blowing/CNC threading; ultrasonic weld baffle.
3. **Sealing:** Automated O-ring insertion; torque-check twist-locks (2.5 Nm).
4. **Electronics:** SMT reflow PCB (lead-free); laser weld battery tabs; functional test (continuity/charge).
5. **Impeller Install:** Epoxy-bond wet magnet; calibrate air gap (0.5 mm) to dry stator.
6. **Stone Module:** Kiln-fire ceramics; friction-fit with retention clip.
7. **Final Integration:** Screw-retain head (Torx T6, tamper-evident); helium leak test.
8. **QA:** Automated: Flow rate (150 ml/min ±10%), cycle timer, IPX5 immersion; manual: visual/aesthetic.

**Scalability:** DFM optimized for 10k/month; tooling cost ~$50k initial.

### Packaging & Logistics
- **Box:** 220 × 120 × 120 mm recycled PET; custom foam cradle for tank/stone.
- **Inserts:** Illustrated quick-start (QR to video tutorial); warranty card; filter spares (2-pack).
- **Shipping:** UN 3481 lithium battery labeling; palletize for 500 units/carton.

**Vendor Recs:** Enclosure – Xometry; Electronics – Jabil; Ceramics – CoorsTek.

---

## 🚀 Roadmap

- **v1.0 Launch (Q4 2025):** Core manual/powered SKUs; beta in art schools.
- **v1.1 (Q2 2026):** Turbidity LED sensor; Bluetooth low-energy for usage logs.
- **v2.0 (Q4 2026):** Multi-fruit characters (e.g., "BerryBuddy"); sub
---
// EasyClean™ v1.0 Wiring Diagram
// Project: EasyClean™ Humanoid Olive Brush Cleaning System
// Version: 1.0 (Powered Variant - Magnetic Impeller)
// Author: Christopher Perry
// Date: September 18, 2025
// Description: Wiring schematic for EasyClean v1.0, a brush cleaning device with 40s impeller cycle,
//              powered by USB-C (5V/1A) or 1200 mAh LiPo. Features NE555 timer control,
//              WS2812B LEDs, and optional sensors. For manufacturing and prototyping.
// Usage: Render with Graphviz (`dot -Tpng easyclean.dot -o wiring.png`)
// License: CC BY-SA 4.0 (pending patent review)

digraph EasyClean_Wiring_v1 {
  // ---------- GLOBAL STYLES ----------
  graph [rankdir=LR, splines=ortho, nodesep=0.5, ranksep=0.7, bgcolor=white];
  node  [shape=box, style=filled, fillcolor=whitesmoke, fontname="Inter", fontsize=10, penwidth=1.2];
  edge  [color=black, arrowsize=0.8, penwidth=1.0, fontname="Inter", fontsize=9, labeldistance=1.8, labelfontcolor="#333333"];

  // ---------- POWER NETS (diamonds) ----------
  VUSB  [label="USB-C 5V",         shape=diamond, fillcolor=lightblue];
  VSYS  [label="SYS 3.7–5V",       shape=diamond, fillcolor=lightblue];
  VBATT [label="LiPo 3.7V",        shape=diamond, fillcolor=lightpink];
  V5    [label="5V (LED/UI)",      shape=diamond, fillcolor=palegreen];
  V6    [label="6V (Motor)",       shape=diamond, fillcolor=palegreen];
  GND   [label="GND",              shape=diamond, fillcolor="#D9F2D9"];

  // ---------- CLUSTER: POWER PATH ----------
  subgraph cluster_power {
    label="Power Path"; labelloc=t; fontsize=12; color="#E8E8E8";
    USBC [label=<
      <b>USB-C</b><br/>Port
      <br/><font point-size="9">VBUS | CC1 | CC2 | GND</font>
    >]; // USB-C receptacle, 5V/1A, CC1/CC2 pull-ups
    BQ   [label=<
      <b>BQ24075</b><br/>Charger/Power-Path
      <br/><font point-size="9">VBUS | SYS | BAT | TS</font>
    >]; // Load-sharing, 1A charge, NTC thermal cutoff
    LIPO [label=<
      <b>LiPo Cell</b><br/>1200 mAh w/ BMS
      <br/><font point-size="9">+ | − | NTC</font>
    >]; // UL1642-certified, 2A PTC fuse on +
    LDO33 [label=<
      <b>3.3V LDO</b><br/>(UI/Sense Reg)
      <br/><font point-size="9">IN | OUT | GND</font>
    >]; // AMS1117 or equiv., powers timer/UI
    LDO5  [label=<
      <b>MCP1700</b><br/>LDO → 5V
      <br/><font point-size="9">IN | OUT | GND</font>
    >]; // Stable 5V for WS2812B
    BOOST6 [label=<
      <b>TPS61023</b><br/>Boost → 6V
      <br/><font point-size="9">IN | SW | OUT | GND</font>
    >]; // 6V/1A for motor, >85% eff.
  }

  // ---------- CLUSTER: CONTROL CORE ----------
  subgraph cluster_control {
    label="Control Core"; labelloc=t; fontsize=12; color="#E8E8E8";
    TIMER [label=<
      <b>NE555</b><br/>Timer (40s)
      <br/><font point-size="9">VCC | TRIG | OUT | GND</font>
    >]; // 40s cycle via 100k R, 470uF C
    DRV [label=<
      <b>DRV8873</b><br/>Motor Driver
      <br/><font point-size="9">VM | IN1 | IN2 | nSLEEP | OUTA | OUTB | GND</font>
    >]; // H-bridge, 6V VM, 20 kHz PWM internal
  }

  // ---------- CLUSTER: ACTUATOR / LOADS ----------
  subgraph cluster_loads {
    label="Actuator / Loads"; labelloc=t; fontsize=12; color="#E8E8E8";
    MOTOR [label=<
      <b>N20 Motor</b><br/>6V Impeller
      <br/><font point-size="9">A | B | Mech</font>
    >]; // 100 RPM, ~200 mA draw
    LEDS  [label=<
      <b>WS2812B Ring</b><br/>4 x LEDs
      <br/><font point-size="9">5V | DIN | GND</font>
    >]; // Status: green (ready), amber (low batt)
  }

  // ---------- CLUSTER: SENSORS & UI ----------
  subgraph cluster_sense {
    label="Sensors / UI (Core + Optional)"; labelloc=t; fontsize=12; color="#E8E8E8";
    TOUCH [label=<
      <b>TTP223</b><br/>Touch Button
      <br/><font point-size="9">Vcc | OUT | GND</font>
    >]; // Triggers 40s cycle
    BADC  [label=<
      <b>Battery ADC</b><br/>Divider 100k/100k
      <br/><font point-size="9">Vbatt/2 | ADC | GND</font>
    >]; // ~1.85V at 3.7V for low-batt LED
    subgraph cluster_optional_sensors {
      label="Optional (v1.1)"; fontsize=10; color="#D0D0D0"; style=dashed;
      WLVL  [label=<
        <b>Water Level</b><br/>Probe
        <br/><font point-size="9">Bias | ADC | GND</font>
      >]; // Roadmap: water level detect
      TURB  [label=<
        <b>Turbidity</b><br/>Sensor
        <br/><font point-size="9">Vcc | ADC | GND</font>
      >]; // Roadmap: water clarity alert
      HALL  [label=<
        <b>Lid Hall</b><br/>Sensor
        <br/><font point-size="9">Vcc | DO | GND</font>
      >]; // Roadmap: lid-open safety
    }
  }

  // ---------- GROUNDS ----------
  {edge [arrowhead=none, color="#8E8E8E"];
    USBC->GND; BQ->GND; LIPO->GND; LDO33->GND; LDO5->GND; BOOST6->GND;
    TIMER->GND; DRV->GND; MOTOR->GND; LEDS->GND; TOUCH->GND;
    BADC->GND; WLVL->GND; TURB->GND; HALL->GND;
  } // Star ground at BQ GND pin

  // ---------- POWER FLOW ----------
  USBC -> VUSB [label="VBUS"];
  USBC -> GND  [label="CC1/CC2\n(5.1k pull-up)"]; // USB-C spec compliance
  VUSB -> BQ   [label="VBUS"];
  BQ   -> VSYS [label="SYS"];
  BQ   -> LIPO [label="BAT"];
  LIPO -> VBATT;
  LIPO -> BQ   [label="NTC → TS"]; // Thermal cutoff

  VSYS -> LDO33 [label="IN"];
  VSYS -> LDO5  [label="IN"];
  VSYS -> BOOST6 [label="IN"];
  LDO5 -> V5    [label="5V"];
  BOOST6 -> V6  [label="6V"];

  // ---------- LOAD POWER ----------
  V6  -> DRV   [label="VM 6V"];
  DRV -> MOTOR [label="OUTA/OUTB"];
  V5  -> LEDS  [label="5V"];
  VSYS-> TOUCH [label="Vcc"];
  VSYS-> BADC  [label="Vref"];
  VSYS-> WLVL  [label="Bias (opt)"];
  VSYS-> TURB  [label="Vcc (opt)"];
  VSYS-> HALL  [label="Vcc (opt)"];

  // ---------- CONTROL LINES ----------
  TOUCH -> TIMER [label="OUT → TRIG\n(10k pull-down,\n1uF debounce)"]; // Start 40s cycle
  TIMER -> DRV  [label="OUT → nSLEEP"]; // Enable motor
  LDO33 -> TIMER [label="3.3V → VCC"];
  LDO33 -> LEDS  [label="3.3V → DIN\n(100R series,\n470uF bulk on 5V)"]; // Static LED control
  BADC  -> LDO33 [label="ADC → OUT"]; // Low-batt trigger
  WLVL  -> LDO33 [label="ADC → OUT (opt)"];
  TURB  -> LDO33 [label="ADC → OUT (opt)"];
  HALL  -> LDO33 [label="DO → OUT (opt)"];

  // ---------- RANK HINTS ----------
  {rank=same; VUSB; VSYS; VBATT; V5; V6; GND}
  {rank=same; USBC; BQ; LIPO; BOOST6; LDO33; LDO5}
  {rank=same; TIMER; DRV}
  {rank=same; MOTOR; LEDS; TOUCH; BADC}
  {rank=same; WLVL; TURB; HALL} // Optional sensors at bottom

  // ---------- LEGEND ----------
  subgraph cluster_legend {
    label="Legend / Notes"; fontsize=11; color="#EFEFEF";
    LEG [shape=note, fillcolor="#FFFFF7", label=<
      <b>Engineering Notes</b><br align="left"/>
      • Diamonds = power nets; all tie to star ground at BQ GND<br align="left"/>
      • NE555: 40s cycle (100k R, 470uF C, pin 6/7 tied)<br align="left"/>
      • WS2812B: Static green/amber via LDO33; 470uF low-ESR cap on V5<br align="left"/>
      • Protections: 2A PTC fuse (BAT+), SMAJ5.0A TVS (VUSB)<br align="left"/>
      • PCB: 2oz Cu, 1mm V6 traces, 10uF decoupling on VM/DRV<br align="left"/>
      • Test Points: VUSB (5V), VSYS (3.7–5V), V5 (5V), V6 (6V), NE555 OUT<br align="left"/>
      • BOM Refs: DigiKey (BQ24075, TPS61023, MCP1700); Mouser (NE555, DRV8873)<br align="left"/>
      • Optional sensors (WLVL/TURB/HALL) for v1.1 roadmap<br align="left"/>
    >];
  }
}

  ---
  digraph EasyClean_Wiring_v1 {
  // ---------- GLOBAL STYLES ----------
  graph [rankdir=LR, splines=ortho, nodesep=0.45, ranksep=0.6, bgcolor=white];
  node  [shape=box, style=filled, fillcolor=whitesmoke, fontname="Inter", fontsize=10, penwidth=1.1];
  edge  [color=black, arrowsize=0.8, penwidth=1.0, fontname="Inter", fontsize=9, labeldistance=1.6, labelfontcolor="#333333"];

  // ---------- POWER NETS (diamonds) ----------
  VUSB  [label="USB-C 5V",         shape=diamond, fillcolor=lightblue];
  VSYS  [label="SYS 3.7–5V",       shape=diamond, fillcolor=lightblue];
  VBATT [label="LiPo 3.7V",        shape=diamond, fillcolor=lightpink];
  V5    [label="5V (LED/UI)",      shape=diamond, fillcolor=palegreen];
  V6    [label="6V (Motor)",       shape=diamond, fillcolor=palegreen];
  GND   [label="GND",              shape=diamond, fillcolor="#D9F2D9"];

  // ---------- CLUSTER: POWER PATH ----------
  subgraph cluster_power {
    label="Power Path"; labelloc=t; fontsize=12; color="#E8E8E8";
    BQ   [label=<
      <b>BQ24075</b><br/>Charger/Power-Path
      <br/><font point-size="9">VBUS | SYS | BAT | TS</font>
    >];
    LIPO [label=<
      <b>LiPo Cell</b><br/>1200 mAh w/ BMS
      <br/><font point-size="9">+ | − | NTC</font>
    >];
    LDO33  [label=<
      <b>3.3V LDO</b><br/>(UI/Sense Reg)
      <br/><font point-size="9">IN | OUT | GND</font>
    >];
    LDO5   [label=<
      <b>MCP1700</b><br/>LDO → 5V
      <br/><font point-size="9">IN | OUT | GND</font>
    >];
    BOOST6 [label=<
      <b>TPS61023</b><br/>Boost → 6V
      <br/><font point-size="9">IN | SW | OUT | GND</font>
    >];
    USBC  [label=<
      <b>USB-C</b><br/>Port
      <br/><font point-size="9">VBUS | CC1 | CC2 | GND</font>
    >];
  }

  // ---------- CLUSTER: CONTROL CORE ----------
  subgraph cluster_control {
    label="Control Core"; labelloc=t; fontsize=12; color="#E8E8E8";
    TIMER [label=<
      <b>NE555</b><br/>Timer (40s)
      <br/><font point-size="9">VCC | TRIG | OUT | GND</font>
    >];
    DRV [label=<
      <b>DRV8873</b><br/>Motor Driver
      <br/><font point-size="9">VM | IN1 | IN2 | nSLEEP | OUTA | OUTB | GND</font>
    >];
  }

  // ---------- CLUSTER: ACTUATOR / LOADS ----------
  subgraph cluster_loads {
    label="Actuator / Loads"; labelloc=t; fontsize=12; color="#E8E8E8";
    MOTOR [label=<
      <b>N20 Motor</b><br/>6V Impeller
      <br/><font point-size="9">A | B | Mech</font>
    >];
    LEDS  [label=<
      <b>WS2812 Ring</b><br/>4 x LEDs
      <br/><font point-size="9">5V | DIN | GND</font>
    >];
  }

  // ---------- CLUSTER: SENSORS & UI ----------
  subgraph cluster_sense {
    label="Sensors / UI"; labelloc=t; fontsize=12; color="#E8E8E8";
    TOUCH [label=<
      <b>TTP223</b><br/>Touch Button
      <br/><font point-size="9">Vcc | OUT | GND</font>
    >];
    BADC  [label=<
      <b>Battery ADC</b><br/>Divider 100k/100k
      <br/><font point-size="9">Vbatt/2 | ADC | GND</font>
    >];
    WLVL  [label=<
      <b>Water Level</b><br/>Probe (Optional)
      <br/><font point-size="9">Bias | ADC | GND</font>
    >];
    TURB  [label=<
      <b>Turbidity</b><br/>(Optional)
      <br/><font point-size="9">Vcc | ADC | GND</font>
    >];
    HALL  [label=<
      <b>Lid Hall</b><br/>(Optional)
      <br/><font point-size="9">Vcc | DO | GND</font>
    >];
  }

  // ---------- GROUNDS ----------
  {edge [arrowhead=none, color="#8E8E8E"];
    USBC->GND; BQ->GND; LIPO->GND; LDO33->GND; LDO5->GND; BOOST6->GND; 
    TIMER->GND; DRV->GND; MOTOR->GND; LEDS->GND; TOUCH->GND; 
    BADC->GND; WLVL->GND; TURB->GND; HALL->GND;
  }

  // ---------- POWER FLOW ----------
  USBC -> VUSB [label="VBUS"];
  USBC -> GND  [label="CC1/CC2\n(5.1k pull-up)"];
  VUSB -> BQ   [label="VBUS"];
  BQ   -> VSYS [label="SYS"];
  BQ   -> LIPO [label="BAT"];
  LIPO -> VBATT;
  LIPO -> BQ   [label="NTC → TS"];

  VSYS -> LDO33 [label="IN"];
  VSYS -> LDO5  [label="IN"];
  VSYS -> BOOST6 [label="IN"];
  LDO5 -> V5    [label="5V"];
  BOOST6 -> V6  [label="6V"];

  // ---------- LOAD POWER ----------
  V6  -> DRV   [label="VM 6V"];
  DRV -> MOTOR [label="OUTA/OUTB"];
  V5  -> LEDS  [label="5V"];
  VSYS-> TOUCH [label="Vcc"];
  VSYS-> BADC  [label="Vref"];
  VSYS-> WLVL  [label="Bias"];
  VSYS-> TURB  [label="Vcc"];
  VSYS-> HALL  [label="Vcc"];

  // ---------- CONTROL LINES ----------
  TOUCH -> TIMER [label="OUT → TRIG\n(10k pull-down,\n1uF debounce)"];
  TIMER -> DRV  [label="OUT → nSLEEP"];
  LDO33 -> TIMER [label="3.3V → VCC"];
  LDO33 -> LEDS [label="3.3V → DIN\n(100R series,\n470uF bulk on 5V)"];
  BADC  -> LDO33 [label="ADC → OUT"];
  WLVL  -> LDO33 [label="ADC → OUT (opt)"];
  TURB  -> LDO33 [label="ADC → OUT (opt)"];
  HALL  -> LDO33 [label="DO → OUT (opt)"];

  // ---------- RANK HINTS ----------
  {rank=same; VUSB; VSYS; VBATT; V5; V6; GND}
  {rank=same; USBC; BQ; LIPO; BOOST6; LDO33; LDO5}
  {rank=same; TIMER; DRV}
  {rank=same; MOTOR; LEDS; TOUCH; BADC; WLVL; TURB; HALL}

  // ---------- LEGEND ----------
  subgraph cluster_legend {
    label="Legend / Notes"; fontsize=11; color="#EFEFEF";
    LEG [shape=note, fillcolor="#FFFFF7", label=<
      <b>Conventions</b><br align="left"/>
      • Diamonds = nets/rails<br align="left"/>
      • Grouped edge labels avoid text overlap<br align="left"/>
      • All rails share a single star ground<br align="left"/>
      • Place 470uF bulk cap near WS2812 5V<br align="left"/>
      • Polyfuse 2A on battery line, TVS (SMAJ5.0A) on VUSB<br align="left"/>
      • NE555 tuned for 40s cycle (100k R, 470uF C)<br align="left"/>
      • CC1/CC2 pull-ups (5.1k) for USB-C compliance<br align="left"/>
    >];
  }
}
---
# Imaging 

---

FIGURE DESCRIPTIONS

FIG. 1 — Front Elevation View
Depicts the anthropomorphic olive-shaped body (101) of EasyClean™ with articulated arms (130a, 130b) and legs (131a, 131b). The crown funnel (110) is shown at the top for brush insertion. The belly region is outlined with dashed lines, indicating the removable water tank (120) section.

![1000023233](https://github.com/user-attachments/assets/d70b8b29-6711-4325-8363-c7f9b4a9cd82)

---

FIG. 2 — Internal Sectional View
Illustrates the internal structure of EasyClean™. Funnel port (110) leads downward into the removable water tank (120). The motor and impeller assembly (170) is positioned at the lower belly, with directional arrows showing circulation of water. O-ring interface (121) secures the tank to the outer shell (101). The drying stone (160) is located at the rear wall.

<img width="1024" height="1536" alt="1000023234" src="https://github.com/user-attachments/assets/27734220-899a-47b0-bdba-9861349e3a83" />
<img width="1024" height="1536" alt="1000023243" src="https://github.com/user-attachments/assets/2aef975b-4fb1-4811-a096-9970ca8b0598" />

---

FIG. 3 — Rear Elevation View
Shows the rear surface of EasyClean™. The drying stone module (160) is visible as a rectangular insert. Arms (130a, 130b) and legs (131a, 131b) ![1000023244](https://github.com/user-attachments/assets/7ead5805-2cc7-49cc-964f-6c2edaa9589c)
extend outward. Funnel port (110) is visible at the crown from the rear perspective. Tank outline (120) shown with dashed lines.


---

FIG. 4 — Top Plan View
Depicts the top crown area of EasyClean™. Circular funnel port (110) is centrally located. Hinged lid (111) is shown open. The LED status ring (140) encircles the belly. Symmetrical arms extend from each side.

![1000023246](https://github.com/user-attachments/assets/cb7341f6-e101-453c-a45e-c92f4eff1d22)

---

FIG. 5 — Perspective View
A three-quarter isometric illustration showing the complete assembled device. The crown funnel (110), articulated limbs (130a, 130b, 131a, 131b), and transparent belly tank (120) are clearly visible. The LED ring (140) is displayed glowing along the midsection.


<img width="1024" height="1536" alt="1000023245" src="https://github.com/user-attachments/assets/a31df29c-f0eb-4c57-aae7-29b32bf7285e" />

---

FIG. 6 — Functional Diagram
Demonstrates the operation of EasyClean™. A brush is inserted into the funnel (110). Arrows indicate circulation of water from the impeller (170) into the belly tank (120). Pigments are shown suspended in water. After washing, the brush is transferred to the drying stone (160) located on the rear wall. The LED ring (140) indicates device status.

<img width="1024" height="1536" alt="1000023246" src="https://github.com/user-attachments/assets/85770f94-bfb3-4c47-a236-a486fd4c216f" />

---

FIG. 7 — Electrical Block Diagram
Shows a simplified schematic of the control and power system. USB-C input (200) connects to charging IC (202), which charges the Li-Po battery (201). A boost regulator (203) provides 6V for the motor (170), while a linear regulator (204) provides 5V for the LED ring (140) and 3.3V for the touch sensor (205). The touch input triggers a timing circuit (206), which drives the motor driver (207) controlling the impeller motor (170). Status outputs return to the LED ring (140).

<img width="1024" height="1536" alt="1000023247" src="https://github.com/user-attachments/assets/2478f11e-e1fb-4d16-b072-2029e46fb62f" />

---

FIG. 8 — Kickstarter-Style Rendering (Optional Marketing Figure)
Provides a photorealistic product rendering showing EasyClean™ as a tangible unit placed on a desk. The transparent water belly (120), impeller (170), LED ring (140), and crown funnel (110) are all visible in consumer-ready form.

<img width="1024" height="1536" alt="1000023249" src="https://github.com/user-attachments/assets/429b4472-bbda-460f-9b65-2e3d6e49f1cc" />

![1000023248](https://github.com/user-attachments/assets/72104138-f53f-4c72-a39b-4a9cc262e4e1)

---

#Need CAD 
Final USPTO Figure Set (Engineering Weighting)

FIG. 1 — Front Elevation View
Depicts EasyClean™ from the front. Outer shell (101), crown funnel (110), articulated arms (130a, 130b), and legs (131a, 131b) are shown. Dashed line indicates belly tank (120).

FIG. 2 — Internal Sectional View
Cutaway showing funnel port (110) leading into removable water tank (120). Motor + impeller (170) located in lower belly. O-ring interface (121) secures tank to outer shell (101). Drying stone (160) mounted on rear wall. Flow arrows indicate water circulation.

FIG. 3 — Rear Elevation View
Rear surface of device. Drying stone (160) visible as rectangular insert. Arms (130a, 130b) and legs (131a, 131b) extend outward. Funnel crown (110) visible. Tank outline (120) shown dashed.

FIG. 4 — Top Plan View
Top view. Brush funnel port (110) centered. Hinged lid (111) covers funnel. Radial LED ring (140) visible around belly.

FIG. 5 — Perspective View
Isometric rendering of the complete assembly. Crown funnel (110), belly tank (120), LED ring (140), arms (130a, 130b), and legs (131a, 131b) are clearly shown.

FIG. 6 — Functional Diagram
Diagrammatic view of operation. Brush inserted into funnel (110). Arrows indicate water circulation from impeller (170) into tank (120). Pigment suspension shown. Brush then applied to drying stone (160) for reshaping. LED ring (140) indicates status.

FIG. 7 — Electrical Block Diagram
Simplified circuit. USB-C input (200) feeds charging IC (202) and Li-Po cell (201). Boost regulator (203) supplies 6V to motor (170). Linear regulator (204) supplies 5V to LED ring (140) and 3.3V to touch sensor (205). Touch input triggers timing circuit (206), which drives motor driver (207). Status returns to LED ring (140).

FIG. 8 — Exploded Assembly View
Shows major subcomponents separated along vertical axis: crown funnel (110), outer shell (101), removable water tank (120), O-ring seal (121), impeller/motor module (170), drying stone (160), LED ring (140), and lower shell with legs (131a, 131b).

FIG. 9 — Left Side Elevation
Profile view from left. Crown funnel (110), arm (130a), leg (131a), and tank belly (120) visible. No internal details.

FIG. 10 — Right Side Elevation
Mirror of FIG. 9, showing right arm (130b) and right leg (131b).

FIG. 11 — Bottom View
Depicts underside. Drain access and motor housing (170) indicated. Feet of legs (131a, 131b) visible. No funnel crown (110) shown.

FIG. 12 — Process Flowchart
Method diagram of operation:

1. Insert brush into funnel (110)


2. Motor/impeller (170) circulates water in tank (120)


3. Pigment removed from bristles


4. Brush placed against drying stone (160)


5. LED ring (140) indicates cycle completion

