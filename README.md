In this project, we developed a Python console application (main.py) designed to calculate the primary characteristics of brushed DC motors and teach students how to interpret motor datasheets. The application facilitates the analysis of essential motor parameters such as resistance, inductance, torque constant, back-EMF constant, and friction torque, which are typically provided in datasheets. It enables users to validate datasheet values by comparing them with theoretical calculations for metrics like maximum speed, torque, efficiency, and power. Additionally, the application generates performance graphs, such as speed-to-torque and torque-to-efficiency characteristics, to provide visual insights into motor behaviour. This tool is not only useful for engineers in evaluating motor performance but also serves as an educational resource for understanding motor fundamentals and datasheet analysis.

The report in "Analysis of datasheets of brushed DC motors.pdf" provides instructions on how to navigate through datasheets and extract parameters essential for modeling the motor.

Features:

  Data Extraction: Easily extract necessary parameters from motor datasheets.
  
  Calculation: Compute main characteristics based on parameters extracted from the motor datasheet.
  
  Educational and Practical: Suitable for both educational purposes and real-world applications.

Output files: Speed-to-torque_characteristics.csv, Torque-to-speed_characteristics.csv, Torque-to-power_characteristics.csv, Torque-to-efficiency_characteristics.csv

Output parameters: Maximum speed, Maximum torque, Maximum efficiency, Maximum mechanical power, No-load armature current, Torque-to-current coefficient, Voltage-to-speed coefficient (no load), dw/dT slope, Maximum angular acceleration (no load).


For more information on formulae and motor calculations, refer to the Maxon Group Formulae Handbook: https://www.maxongroup.com/assets/public/caas/v1/media/219130/data/3baaf2304d150dfcf7215b2348bd3df8/maxon-knowlege-support-academy-pdf-en-download.pdf

Brushed DC motors for higher temperatures: https://www.maxongroup.com/en-us/knowledge-and-support/blog/maxon-takes-brushed-dc-motors-to-higher-temperatures-69550

In "DC motors design guide.pdf", the editors of Design World detail the most common DC motor types as well common ways to quantify their output during the design-engineering process.
