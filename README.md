# Verizon-CCE-job-simulation
Tasks of Verizon Cloud Computing Engineer role simulation

## Sasha Task 1
### Testing for 3 cloud native traits
- ***Redundancy:*** Kill an instance (VM or container) of the app while it's running, and check if the app continues to work and provide service. Note: This is to test that the system is stable enough for parts of its underlying resources to fail and not affect up time.
 
- ***Resiliency:*** Kill an instance (VM or container) of the app while it's running, and check if the instance (VM or container) restarts/recovers with no human intervention, and continues to provide service. Note: This is to test the ability of the system to recover from failures and continue to function with minimal interaction.
 
- ***Least-privilege:*** Check that the app is not using admin or root level access. Note: This is to ensure that the application is secure enough so that should there be a security breach it will likely be limited due to the restricted access and permission of the user running the external facing application.

How to test
```text
You can use scale [NUMBER] to scale the application up or down.

You can use kill [POD_NAME] to kill off a certain pod.

You can use get-user 
```
