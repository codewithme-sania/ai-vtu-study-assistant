# MOSFET — Metal Oxide Semiconductor Field Effect Transistor

## 1. Definition

A **MOSFET (Metal Oxide Semiconductor Field Effect Transistor)** is a **voltage-controlled semiconductor device** in which the current flowing between the **drain (D)** and **source (S)** is controlled by the voltage applied between the **gate (G)** and **source (S)**.

The gate is electrically insulated from the semiconductor by a thin **oxide layer**, so the gate current is ideally almost zero.

> **In simple words:** A MOSFET is an electronic switch or amplifier in which a **gate voltage controls the drain current**.

---

## 2. Basic Concept

A MOSFET has four terminals:

- **Gate (G)** – controls the device.
- **Drain (D)** – terminal through which drain current enters or leaves the device.
- **Source (S)** – terminal through which carriers enter or leave the channel.
- **Body/Bulk (B)** – semiconductor body of the device.

For many discrete MOSFETs, the body is internally connected to the source, so the device appears to have three external terminals.

The important voltage is:

**VGS = VG − VS**

where:

- **VGS** = gate-to-source voltage
- **VG** = gate voltage
- **VS** = source voltage

The gate voltage determines whether a conducting **channel** exists between source and drain.

---

## 3. MOSFET Structure

Consider an **n-channel enhancement MOSFET (NMOS)**, one of the most commonly studied MOSFETs.

Its basic structure consists of:

- A **p-type substrate** (semiconductor body)
- Two heavily doped **n+ regions** forming the source and drain
- A thin **silicon dioxide (SiO₂)** or other gate dielectric layer
- A conducting **gate** placed above the oxide

### Simplified Structure

```text
              Gate (G)
        ┌─────────────────┐
        │      METAL      │
        └─────────────────┘
              OXIDE
        ───────────────────
        Semiconductor Surface
          n+            n+
       Source (S)    Drain (D)
          │              │
          │              │
          └── p-type ────┘
              substrate
