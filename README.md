- [FOR SUPPORT JOIN OUR DISCORD](https://discord.gg/wsuyANeZks)

# qb-inventory

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-logs](https://github.com/qbcore-framework/qb-logs) - For logging transfer and other history
- [qb-traphouse](https://github.com/qbcore-framework/qb-traphouse) - Trap house system for qbcore
- [qb-radio](https://github.com/qbcore-framework/qb-radio) - Radio system for communication
- [qb-drugs](https://github.com/qbcore-framework/qb-drugs) -  Drugs and Weed Planting System
- [qb-shops](https://github.com/qbcore-framework/qb-shops) - Needed in order to add shops

## Screenshots
![General](https://i.imgur.com/Vnl3EwA.png)
![Jewelery](https://i.imgur.com/1R5bGcc.png)

## Features
- Dry Feature
- Based with 6 slot
- Jewel section (under development)
- Every item has durability
- Item crafting
- Weapon attachment crafting
- Stashes (Personal and/or Shared)
- Vehicle Trunk & Glovebox
- Weapon serial number
- Shops
- Item Drops

## New Updates
- added GetAmount export to client side

## Installation
### Manual
For adding decay rate to item go to qb-core/shared/items.lua and add "["decayrate"] = 2.5".

For example

    ['joint'] = {
        ['name'] = 'joint', 			  	  		
        ['label'] = 'Joint', 					
        ['weight'] = 0, 		
        ['type'] = 'item', 		
        ['image'] = 'joint.png', 				
        ['unique'] = false,
        ["decayrate"] = 2.5,  	
        ['useable'] = true, 	
        ['shouldClose'] = true,    
        ['combinable'] = nil,   
        ['description'] = ''
    },