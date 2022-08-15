# Beautymapper

If you are doing the Lem-in project and planning to create a visualizer, you may need this tool to update the coordinates of maps created by the official generator. 
This Beautymapper transforms the coordinates in the map given, based on the relationship of the rooms.

# Usage
If you are using Mac you can use the executable provided (beautymapper_mac)

```./beautymapper_mac map_from_generator```
(replace 'map_from_generator' with an actual map you want to update)

If you cannot use the provided executable you can compile it yourself:
- Install Rust
- Run ```cargo run --release map_from_generator``` from the root of the repository

#examples 
