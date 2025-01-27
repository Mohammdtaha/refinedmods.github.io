The Detector is a block that emits a redstone signal if an item, or fluid, count matches a given amount.

It is also possible to be NBT or damage sensitive.

## Types of criteria

|Criteria|Explanation|
|--------|-----------|
|<|Emits a signal when lower than the given amount|
|>|Emits a signal when higher than the given amount|
|=|Emits a signal when equal to the given amount|

## Checking the total count in the storage
When no item/fluid, is specified, the criteria won't care about the count of a specific item/fluid, but rather the count of all items/fluids, in the storage.

## Amounts in fluid mode
When the Detector is in fluid mode, the amount given is in millibuckets (mB).

If you want to check for 1 bucket of a fluid, use 1000, not 1.

[[@Recoloring]]
