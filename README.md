# More Choppin' Axes #

## What it does ##

Using MWSE lua, modifies axe damage values so that chop is used by default if "Always Use Best Attack" is on.
Because axes should chop, right?
(Especially when cutting wood in Ashfall)

There are three options:

**Boost minimum**: Set minimum chop damage to +1 minimum slash damage.
Side effect: boosts minimum damage, so more damage potential overall.

**Boost maximum**: Sets chop damage to equal slash damage, then reduce maximum slash damage by 1.
Side effect: boosts maximum chop to match maximum slash, so if slash damage and chop damage differ greatly, then this wildly changes chop.

**Swap**: Swaps slash damage with chop damage.
Side effect: No effect if slash and chop damages are the same.
To remedy this, if they are the same, slash damage is reduced by one.
Side effect of that: maximum slash damage is reduced by 1, so lower overall damage output.
If Always Use Best Attack is on, then the overall damage output isn't changed, and these side effects are pretty much moot anyway.

## Credits ##

* MWSE team for MWSE lua
* Morrowind Modding Discord for being cool and helpful

## License ##

MIT License. See license.txt