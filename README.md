# Split-Phase
# Introduction to the US Residential Split-Phase (120/240V) Power System

## 1. Overview

The vast majority of US residences utilize the **120/240V Single-Phase, 3-Wire Split-Phase System**
Many people mistakenly believe that US residential power is a single-phase, two-wire system; however, there are actually three active conductors running from the transformer to the residential distribution panel:

* L1 (Hot) * L1 to N = 120V
* N (Neutral) * L2 to N = 120V
* L2 (Hot) * L1 to L2 = 240V
Consequently, the same power system can supply both 120V and 240V.

## 2. Split-Phase Principle

The secondary winding of the distribution transformer near the residence employs a center-tap configuration:

```text
L1 ─────┐
│
│
● ← Neutral (Center Tap)
│
│
L2 ─────┘
```

L1 and L2 actually originate from the two ends of the same transformer winding, with a phase difference of 180°.

## 3. 120V Circuits

Most household outlets and lighting fixtures operate on 120V. Examples: Mobile phone chargers\Computers\Televisions\Refrigerators\Microwave ovens\Desk lamps

Connection method:

```text
L1 + Neutral
```

or:

```text
L2 + Neutral
```

## 4. 240V Circuit

High-power appliances typically use 240V. Examples: Electric water heaters\Electric ranges/stoves\Central air conditioning\Electric clothes dryers\Electric vehicle (EV) chargers

Connection method:

```text
L1 → Device → L2
```

In this case, the Neutral wire is not used.

---

## 5. Circuit Breakers in the Distribution Panel

The busbars in a residential breaker panel are arranged alternately:

```text
L1
L2
L1
L2
L1
L2
...
```

### Single-pole Breaker (120V)

Standard outlets and lighting:

```text
L1 ── Breaker ── Load ── Neutral
```

or:

```text
L2 ── Breaker ── Load ── Neutral
```

### Double-pole Breaker (240V)

High-power appliances:

```text
L1 ──┐
├── Load
L2 ──┘
```

A double-pole breaker connects to both L1 and L2.

---

## 6. Neutral and Ground

### Neutral

The Neutral wire serves as the return path for the circuit.

Characteristics:

*   Current-carrying conductor
*   Carries current under normal operating conditions
*   Provides a return path for the load

Circuit path:

```text
Hot → Device → Neutral
```

### Ground

The Ground wire serves as a protective conductor for safety. Characteristics:

*   No current flow under normal conditions
*   Does not participate in the normal power supply circuit
*   Used for fault protection

During a fault:

```text
Equipment Enclosure
↓
Ground
↓
Distribution Panel
↓
Circuit Breaker Trips
```

---

In US residences:

Neutral and Ground are permitted to be connected only once, at the Main Service Panel.

After leaving the Main Service Panel:

*   Neutral Bus
*   Ground Bus

Must remain separated.


## 7. Why is Neutral close to 0V?

Because the transformer center tap is grounded:

## 8. Common 120V Receptacles (socket)

### NEMA 5-15 (Standard 15A Receptacle)

Appearance:

```text
|   |
○
```

Terminals:

*   Hot
*   Neutral
*   Ground

Rating:

*   120V
*   15A

---

### NEMA 5-20 (20A Receptacle)

Appearance:

```text
|   T
○
```

The T-shaped slot is for Neutral.

Rating:

*   120V
*   20A

Although the shape differs, it is still a 120V receptacle, not 240V. ---

## 9. Common 240V Receptacles

### NEMA 14-30

Commonly used for:

* Electric clothes dryers

Conductors:

* L1
* L2
* Neutral
* Ground

Ratings:

* 240V
* 30A

---

### NEMA 14-50

Commonly used for:

* Electric vehicle (EV) charging
* Recreational Vehicles (RVs)
* Electric ranges/stoves

Conductors:

* L1
* L2
* Neutral
* Ground

Ratings:

* 240V
* 50A

---

### NEMA 6-20

Commonly used for:

* Air conditioners
* Industrial equipment

Conductors:

* L1
* L2
* Ground

No Neutral.

Ratings:

* 240V
* 20A

---

## 10. Summary

The core characteristics of the US residential power supply system are:

1. Uses a single-phase center-tapped transformer.
2. Supplies the residence with:

* L1
* Neutral
* L2
3. Provides two voltage levels:

* 120V (L1/L2 to Neutral)
* 240V (L1 to L2)
4. Neutral is the circuit conductor.
5. Ground is the protective conductor.
6. Standard receptacles use 120V.
7. High-power appliances use 240V.

Therefore, the more accurate term for US residential power supply is:
**120/240V Single-Phase 3-Wire Split-Phase System**
