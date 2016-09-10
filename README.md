# Water Game
This game to evaluate performances of supply portfolios of urban, agricultural and environmental deliveries. Players meet target demands of water users by selecting various supply options, such as potable and non-potable recycled water, greywater, desalination and conservation.

Players can set different objectives:
* Minimize total water supply cost
* Minimize total energy used to supply water
* Minimize groundwater overdraft
* Maximize wastewater reuse ratio
* Maximize meeting users' target demands
 
Players can set single or multiobjectives. Green and yellow bars in Table.5 will show how close results are to optimal values. User will maximize green bars and minimize yellow bars. There is also performance indicators for each sector. Available sectors (users):
* Urban
* Suburban
* Rural Homes
* Agriculture
* Environment
 
Players will use different supply portfolio options to meet the users' demands and their objectives. Players will enter water qunatities into gold-highlighted cells for each portfolio option. Avalble supply options:
* Groundwater
* Surface water
* Direct Potable Reuse
* Indirect (Nonpotable) Reuse
* Greywater
* Desalination
* Conservation
 
Please note that not all supply options are available to all sectors. For example, greywater is not a option for agricultural or environmental users. Each option also has a different unit cost (Table.4) and unit energy.

The current model (game) has two basins: upper and lower. Currently, both upper and lower basins have the same set up, target demand, and unit supply costs. However, it can be easily updated to make them different if necessary.

When choosing supply quantities, there is some limitations (constraints) players should consider. It is desired to meet users' target demands but we don't want to give more than their demands. Target demand indicators in Table.1 will turn into yellow if meeting target demand is greater than 100%. Similary, water scarcity is not desired, either. Cells become red if meeting target demand indicator is less than 100%. In addition, there is maximum water availability constraint. Total used groundwater or surface water options cannot exceed what is available.
