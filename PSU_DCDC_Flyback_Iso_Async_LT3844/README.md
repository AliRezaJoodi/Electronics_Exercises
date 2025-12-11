## Flyback DC-DC Converter, Isolated, Asynchronous, Based on LT3844

This circuit is only for exercise.  
For a proper flyback design, it's better to use a controller IC that supports Discontinuous Conduction Mode (DCM) detection.  
Without DCM detection, like in the LT3844, adjusting the switching timing correctly becomes difficult. 

### Features
- **Output:** 5V/15W x2, Isolated
- **Input:** 12V
- **Feedback Type:** Isolated FeedBack using Optocoupler and TL431
- **Peak Current Mode Control**
- **Controller:** PWM controller based on LT3844

### Simulate
v2.0, Schematic  
![](Simulate/v2.0_Schematic1.png)  
![](Simulate/v2.0_Schematic2.png)  
![](Simulate/v2.0_Schematic3.png)  

v2.0, Plot  
![](Simulate/v2.0_Plot.png)  
![](Simulate/v2.0_Plot2.png)  

### More Information
**Note**: [You can go here to download a single folder or file from GitHub.com](https://minhaskamal.github.io/DownGit/#/home)  
My GitHub Account: [GitHub.com/AliRezaJoodi](https://github.com/AliRezaJoodi)  