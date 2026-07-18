# Deutschlandticket Adoption Potential — J&J Medical GmbH, Norderstedt

Estimates how attractive public transport (HVV/AKN) is for employees commuting to
Johnson & Johnson Medical GmbH, and how likely they'd be to adopt the
Deutschlandticket.

## Method
1. 600 synthetic employee locations across 12 Hamburg-region districts (no real
   employee data used).
2. Real-world approximate HVV/AKN station network (U1, S1, AKN lines).
3. Door-to-door commute time: walk/feeder → wait → ride → transfer (if needed) → last mile.
4. Grouped into ≤30 / 31-45 / 46-60 / >60 minute bands.
5. Deutschlandticket adoption score (0-100): commute time (35%), connectivity (25%),
   last-mile convenience (15%), competitiveness vs. driving (25%).
6. Summary: bucket %, adoption split, strongest/weakest districts, key factors.

## Note on scope
Commute times are modeled analytically from real station geometry (no live
routing/geocoding API used). Swapping in a real HVV GTFS feed or routing API
would be the natural next step for production use.
