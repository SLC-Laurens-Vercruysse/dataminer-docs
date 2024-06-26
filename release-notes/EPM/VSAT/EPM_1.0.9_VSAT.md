---
uid: EPM_1.0.9_VSAT
---

# EPM 1.0.9 VSAT - preview

## New features

#### Skyline Universal Weather: New Windy API endpoint [ID_38610]

A new API endpoint, Windy API, is now included in the Skyline Universal Weather connector.

## Changes

### Enhancements

#### Skyline Universal Weather: New debug parameters to clear buffer [ID_38747]

On the *Debug* page of the Skyline Universal Weather connector, a *Clear Buffer Timer* toggle button and *Clear All Buffer* button are now available. You can use these to clear the buffer when the maximum number of API requests has been reached and requests are accumulating in the buffer.

### Fixes

#### Generic Trap Processor: Trap count incorrectly doubled [ID_38609]

It could occur that the Generic Trap Processor doubled the trap count, counting a single incoming trap twice, which resulted in inaccurate totals.
