# Aunt Clo WiFi - Recommendations (July 2026)

## Situation Summary
- AT&T Fiber (recent speed upgrade)
- Old Apple router + 1 booster in dining room
- Weak signal downstairs + garage after upgrade
- Main computer upstairs

## Top Recommendations

### 1. Easiest: AT&T Extended Wi-Fi Coverage Service (Mesh Extenders)
- AT&T offers official mesh extenders that work with their gateway.
- Can be included or low monthly cost depending on plan.
- Pros: Official support, easy install, lifetime replacement on some plans.
- Cons: Monthly fee on some plans, less flexible than third-party.

### 2. Best Overall Third-Party: Eero System
- **Recommended**: Eero 7 or Eero Pro 7 (3-pack)
- Excellent app, very reliable, good AT&T compatibility.
- Many AT&T Fiber users successfully use Eero mesh.

### 3. Best Value / Performance: TP-Link Deco
- **Recommended**: TP-Link Deco 7 Pro (BE63) or Deco XE series
- Strong performance, often praised in 2026 reviews.
- Good price-to-performance.

### 4. Strong Alternative: Google Nest Wifi Pro
- Good coverage and speeds.
- Clean design, reliable app.

## Important Technical Step (Strongly Recommended)
Put the AT&T gateway into **IP Passthrough** mode and use the new mesh system as the main router. This avoids double NAT and gives much better performance.

Steps (general):
1. Log into AT&T gateway (usually 192.168.1.254)
2. Go to **Firewall → IP Passthrough**
3. Set Allocation Mode to **Passthrough**
4. Set Passthrough Mode to **DHCPS-fixed**
5. Select the MAC address of the new mesh router

## Quick Decision Guide

| Priority                    | Recommended Solution       | Difficulty | Cost          | Notes                              |
|----------------------------|----------------------------|------------|---------------|------------------------------------|
| Easiest / Official         | AT&T Mesh Extenders        | Very Easy  | Low–Medium    | Good if she wants minimal hassle   |
| Best balance               | Eero 7 / Pro 7             | Easy       | Medium        | Most recommended for AT&T users    |
| Best performance/value     | TP-Link Deco BE63          | Easy       | Good          | Top-rated in 2026 reviews          |
| Already has Apple gear     | Keep Apple + better mesh   | Medium     | Medium        | Possible but not ideal             |

## Next Steps
1. Confirm exact modem + router models from the photos
2. Decide between staying with AT&T mesh vs third-party
3. If going third-party → plan IP Passthrough setup

