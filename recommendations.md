# Aunt Clo WiFi - Recommendations (July 2026)

## Confirmed Hardware
- **Main Gateway**: AT&T All-Fi Hub **BGW530-900**
- **Old Router**: Apple AirPort Extreme **A1521** (6th generation)
- **Booster**: One unit in dining room
- **ISP**: AT&T Fiber (recent speed upgrade)

## Problem
WiFi signal weakened downstairs + garage after the AT&T upgrade. The old Apple AirPort Extreme is likely limiting coverage and performance.

## Recommendations

### 1. Easiest Option: AT&T Official Mesh Extenders
- Use AT&T’s **Extended Wi-Fi Coverage Service** with the BGW530-900.
- They can add official All-Fi mesh extenders that work seamlessly with the gateway.
- Pros: Simple, supported by AT&T, lifetime replacement on many plans.
- Cons: Monthly fee possible depending on plan.

### 2. Best Long-Term Solution: Replace the Apple Router with a Modern Mesh System
**Recommended systems**:
- **Eero 7** or **Eero Pro 7** (3-pack) — Best overall for ease of use and reliability with AT&T.
- **TP-Link Deco 7 Pro (BE63)** — Excellent performance and value in 2026 reviews.

**Important Step**: Put the **BGW530-900** into **IP Passthrough** mode so the new mesh system handles routing.

### 3. Quick & Cheap Option
Keep the current setup but:
- Move the Apple AirPort to a more central location.
- Add one or two good Wi-Fi 6/6E extenders.
- This is a band-aid solution — not recommended long-term.

## IP Passthrough Guide (BGW530-900)
1. Connect a computer to the AT&T gateway.
2. Go to `192.168.1.254` in a browser.
3. Log in (default password is on the sticker on the device).
4. Go to **Firewall → IP Passthrough**.
5. Set:
   - Allocation Mode → **Passthrough**
   - Passthrough Mode → **DHCPS-fixed**
6. Select the MAC address of the new mesh router.
7. Save and reboot the gateway.

## Recommended Action
1. Confirm if she wants the simplest solution (AT&T mesh) or best performance (third-party mesh).
2. If choosing third-party → get a 3-pack mesh system and configure IP Passthrough on the BGW530-900.
3. Retire the old Apple AirPort Extreme.