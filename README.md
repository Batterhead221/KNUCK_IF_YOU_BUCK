# KNUCK_IF_YOU_BUCK

Custom LMR51430 buck converter PCB (12V → 5V @ ~3A)
Hands-on power board focused on real layout, not just theory

Key Features
•	Switch node layout optimization
•	Tight input loop placement
•	Proper feedback routing and test points (SW, FB, VIN)

Hardware Design
•   Custom 12V → 5V buck converter using the LMR51430  
•   Input: 12V  
•   Output: 5V (~3A target)  
•   Inductor: 10µH power stage  
•   Feedback Divider: 100k / 20k (sets 5V output)  
•   Output Filtering: 47µF bulk + local decoupling  
•   Input Decoupling: 10µF + 0.1µF placed close to VIN  

•   Layout Priorities:
    •   Tight high-current loop (VIN → SW → L → Cout → GND)  
    •   Short switch node to reduce noise  
    •   Solid ground reference for stability  
    •   Dedicated test points (VIN, SW, FB, EN, 5V)  

Designed and engineered by Brandon Shelly
Portfolio Hardware Project