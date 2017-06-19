# tangle-visualizer
A live graph visualization of the IOTA tangle.

Demo of v1 at http://tangle.blox.pm. See http://iota.org for more details on the tangle. Roadmap for future releases coming soon.


# Roadmap
## Milestone 1: Refactor and user experience
* Refactor and organize - Current code has references going in odd directions and will be very hard to maintain
* Build groundwork for UI - Current UI does not have any particular design behind it since it's very small. Creating a better UI groundwork will enable different menu for mobile and support the user-defined settings in upcoming releases
* Full mobile support
* Fix bugs related to node spawning
* Fix visual bugs related to window size
* Make the visualization xy-agnostic, allow the user to pick direction of growth
* Auto panning to follow the tangle as it grows

## Milestone 2: Transaction details
* Allow user to see full tx details by zoom and/or click
* Highlighting bundles
* Allow user to somehow differentiate branch/trunk
* Highlighting txs with user-defined filters

## Milestone 3: Full tangle history
* Load some historical data when the visualizer is initiated to avoid free floating subtangles
* Load more historical data if the user pans down below the current data
* This part will likely require a node pruning/caching system to lower resource demands
