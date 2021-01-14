# FFXIV Ocean Fishing Route Index Calculator

This tool calculates a the index based of the length of the Route Table (currently 144) and an epoch date (currently 2021-01-05 16:00:00 UTC), works from patch 5.4 as long as epoch doesn't change and length of route table (IKDRouteTable) is automatically calculated.

## Next steps
- Use this index on IKDRouteTable to get the IKDRoute
- Use IKDRoute value to get the 3 IKDSpots and their respective IKDTimeDefine values
  - Spot 0 is IKDSpot zone 1
  - Spot 1 is IKDTimeDefine for zone 1
  - Spot 0 is IKDSpot zone 2
  - Spot 1 is IKDTimeDefine for zone 2
  - Spot 0 is IKDSpot zone 3
  - Spot 1 is IKDTimeDefine for zone 3
- Use IKDSpot to reference the Fishing Spots for normal and spectral which can be checked with Fishing Spot from fishing record

## IKDTimeDefine Reference
- 1 is Sunset
- 2 is Night
- 3 is Day