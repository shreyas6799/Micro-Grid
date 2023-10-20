A microgrid is a localized group of electric loads and distributed energy resources (DERs) with clearly defined electrical boundaries that acts as a single controllable entity with respect to the grid. A microgrid can connect and disconnect from the grid to enable it to operate in both grid-connected or island mode.
Microgrid diagramOpens in a new window

![unnamed](https://github.com/shreyas6799/Micro-Grid/assets/146182517/be895e8f-2ae8-4d64-b7f3-2e27e23054ba)

Microgrid diagram

DERs are small-scale power generation and storage technologies that can be located close to where they are used, such as solar panels, wind turbines, batteries, and diesel generators. Microgrids can also include energy management systems (EMS) that help to optimize the operation of the DERs and ensure that the microgrid meets the needs of its customers.
College campus microgridOpens in a new window

![unnamed (1)](https://github.com/shreyas6799/Micro-Grid/assets/146182517/555c0527-c34a-4815-b53d-00c68a1c670d)

College campus microgrid

Microgrids can offer a number of benefits, including:

Reliability: Microgrids can help to improve reliability by providing backup power in the event of a grid outage.
Resilience: Microgrids can make the grid more resilient to cyberattacks and natural disasters.
Sustainability: Microgrids can help to reduce greenhouse gas emissions by integrating renewable energy sources.
Economic benefits: Microgrids can help to reduce energy costs and create jobs.
Microgrids are becoming increasingly popular as a way to improve the reliability, resilience, sustainability, and affordability of the electric grid. They are being used in a variety of settings, including college campuses, hospitals, businesses, and communities.

Here are some examples of how microgrids are being used to improve the reliability, resilience, sustainability, and affordability of the electric grid:

College campuses: Microgrids can help college campuses to reduce their energy costs and become more self-sufficient. For example, the University of California, Berkeley has a microgrid that includes solar panels, wind turbines, and battery storage. The microgrid can provide up to 100% of the campus's electricity needs on sunny days.
Hospitals: Microgrids can help hospitals to ensure that critical medical devices continue to operate in the event of a grid outage. For example, the National Institutes of Health (NIH) has a microgrid that includes solar panels, a diesel generator, and a battery storage system. The microgrid can provide backup power to the NIH's main hospital and critical research facilities.
Businesses: Microgrids can help businesses to reduce their energy costs and improve their reliability. For example, the Googleplex, Google's headquarters in Mountain View, California, has a microgrid that includes solar panels, a wind turbine, and a battery storage system. The microgrid can provide up to 100% of the Googleplex's electricity needs on sunny days.
Communities: Microgrids can help communities to become more resilient to grid outages and natural disasters. For example, the town of Rockport, Massachusetts has a microgrid that includes solar panels, battery storage, and a diesel generator. The microgrid can provide backup power to the town's critical infrastructure, such as the hospital, water treatment plant, and emergency shelter.
Microgrids are still a relatively new technology, but they have the potential to revolutionize the way we generate and distribute electricity.

Simulaiton :
![Micro_Grid](https://github.com/shreyas6799/Micro-Grid/assets/146182517/b911c8ce-ef88-4025-b6b7-119760d38e66)

Case 1: When load current <= 0.4 A
In case 1, the total load is 0.30, which is less than 0.40, so Relays 1, 2, and 9 will be in the ON state, allowing Source 1 to deliver all of the loads.
![case1](https://github.com/shreyas6799/Micro-Grid/assets/146182517/25d989ac-460e-48f1-b2f4-300b1d0315d0)

Case 2: When 0.4 A < Load current < 0.8 A
Source 2 will be able to deliver all of the loads in Case 2 since the total load is 0.48, which is larger than 0.4 and less than 0.8. As a result, Relays 3, 4, and 5 will be in the ON state.

![case2](https://github.com/shreyas6799/Micro-Grid/assets/146182517/8d9e5aac-9c1b-4a06-95ee-b68266fa5acd)



Case 3: When 0.8 A < Load current<1.2 A 
Source 1 will supply to load2, Source 2 will supply to load3, and Source 1 will supply to load1 by turning Relays 2, 3, and 5 to the ON state because the total load in case 3 is 1.06 A, larger than 0.8 A and less than 1.2 A.

![case3](https://github.com/shreyas6799/Micro-Grid/assets/146182517/b8f3c62f-0594-41e9-a60e-5bfd074fb6ec)



Case 4: When 1.2 A< Load current>1.5 A 
The total load is 1.36 A, larger than 1.2 A and less than 1.5 A, so the relays 6, 7, and 8 will be in the ON state, allowing the source 3 to give power to all loads.

![case4](https://github.com/shreyas6799/Micro-Grid/assets/146182517/699c623b-65c1-41be-9fb7-8102dfd9dbcc)




Case 5: When 1.5 A< Load current >1.8 A
When sources 1 and 3 are combined, case 5's load's total current of 1.85 A can be satisfied. By turning on Relays 1, 7, and 8, source 1 will supply to load 1, which has a current rating of 0.35 A, and source 3 will supply to load 2 and load 2, which together have a current rating of 1.49 A.

![case5](https://github.com/shreyas6799/Micro-Grid/assets/146182517/15ba3770-5012-408d-8cc5-843a3d5190ba)




Case 6: When 1.8 A < Load current > 2.1 A
In case 6, when source 2 and source 3 are combined, the total current rating of the load, which is 2.14 A, can be satisfied. Source 2 will be supplied to load 2, which has a current rating of 0.65 A, and source 3 will be supplied to loads 1 and 3, respectively, by switching Relays 5 and 

![case6](https://github.com/shreyas6799/Micro-Grid/assets/146182517/34f242fc-5f86-46df-8684-3498696268ad)



Case 7: When 2.1 A< load current >2.4 A 
In case7, the total current is 2.48 A, for satisfy this condition, all the sources will be supplied to each load. Source1 will be supplied to load1 which has current rating of 0.35 A by making Relay 1 to ON position, for load2 which has current rating of 0.77 A will be supplied by source2 by switching Relay 4 to ON position and source 3 will be supplied to load3 which has current rating of 1.36 A by making Relay 8 to ON.

![case7](https://github.com/shreyas6799/Micro-Grid/assets/146182517/0c078258-63fe-4084-86a5-361e0daa60bb)



Case 8: When load current >2.7 A
Since the current in this case is greater than 2.7 A, which is greater than the combined current from all three sources, all of the loads will be in the off position until one of them is disconnected.


CONCLUSION
The use of the ESP32S microcontroller as the central control unit proves to be instrumental in achieving precise control and coordination of multiple power sources and a load. Through continuous monitoring and dynamic adjustments based on predefined conditions, the system can adapt to changing requirements and optimize power distribution. Furthermore, the inclusion of thorough testing and calibration procedures guarantees the accuracy and performance of the system, aligning it with the desired specifications. In the realm of energy management, where efficiency and reliability are paramount, this methodology serves as a robust framework for the successful deployment and operation of microgrid systems

