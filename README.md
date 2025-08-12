# Proper Pinning — A2 SFIC

Fast, no-nonsense A2 SFIC pinning calculator.  
Enter **Master** → **Change** → **Control**, then get exact **B / M / D / T** pin stacks for 6- or 7-pin cores.

> **Privacy:** No accounts, no ads, no analytics, no network calls. All math runs on-device.

---

## Features
- Input flow: Master → Change → Control (with auto-advance)
- A2 rules baked in  
  - **Bottom (B)** = `min(Master, Change)`  
  - **Master Pin (M)** = `|Master - Change|` **and cannot be 1**  
  - **Driver (D)** = `This will be calculated for you`
  - **Top (T)** = `This also will be calculated for you`
- 6/7-pin toggle
- Sticky column headers (Master / Change / Control)
- “Top” helper button on input screen
- Results screen with:
  - Column striping for readability
  - Frozen row labels (T / D / M / B)
  - **Copy** to clipboard (text) and **CSV** export
  - “Fit to width” toggle

## How to use
1. Pick **Pin Count** (6 or 7).  
2. Enter all **Master** cuts (positions 1→n), then all **Change**, then **Control**.  
3. If any Master/Change pair differs by **1**, the field is cleared and highlighted (A2 doesn’t allow 1 master pins).  
4. Results open automatically after the last Control digit.  
5. Use **Copy** or **CSV** on the results page if needed.



## Known quirks we’re improving
- On some devices, after very fast entry, the view may not auto-scroll upward immediately. Use the **Top** button; a smoother scroll routine is planned for the next update.


## What’s next (roadmap)

We’re building a whole family of locksmith tools. All apps are **one-time purchase** — **no subscriptions** — and will be released on **Android (Google Play)** and **iOS (App Store)**.

### Master Key — Standard Cylinders
Complete master-key pinning for conventional cylinders.
- Proper pin stacks, depths, and rule checks
- Multi-level charts and fast change-key generation

### A2 SFIC Suite
Everything for A2 small format.
- **Missing Control Key** calculators (two methods)
- **Missing Change Key** finder
- The free **Proper Pinning — A2 SFIC** you’re using now

### Sargent LFIC Suite
From pinning to decoding — end to end.
- Step-by-step **pinning guide**
- **Missing Control** and **Missing Change** key solvers

### Corbin/Russwin System 70
Purpose-built for 6- and 7-pin LFIC System 70.
- Correct pinning for each chamber
- **Control key decode**
- **Missing Change Key** solver

> Want early access or to suggest features? Open an issue or email **Jerry@JerryDionisio.com**.

---

## License
© 2025 Unicorn Tools. All rights reserved.
