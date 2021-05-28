# Modelling Critical-Power in Elite Endurance Runners 

# INTRO 
The hyperbolic relationship between power output (PO) and the duration for which it can be sustained was first described by Hill (1925). Monod and Scherrer (1965) further described this phenomenon using a 2-parameter model wherein critical power (CP) represents the asymptote and W’ represents the curvature of the power-time. Here, W’ signifies the finite amount of work that can be done above CP, whereas CP represents the highest work rate at which steady state values can be achieved for muscle metabolism and pulmonary oxygen uptake (Jones et al., 2008). Making it an important physiological threshold separating the high and severe intensity domains of exercise  (Jones et al., 2008, Pooles et al., 1988). Furthermore, this relationship  holds true for various modes of human locomotion such as cycling (Vanhatalo et al., 2008) , running (Smith & Jones, 2001), swimming (Wakayoshi et al., 1992)  and isometric contractions (Burnley et al., 2012) . Making it an important  concept applicable to various sports specifically in the field of fitness testing, program design and performance prediction. 

# Points to remember 
1.) Here Critical Power is taken as Critical Speed (CS) 

2.) the 2-parameter model that we use, fits well for endurance efforts ranging between 2-15mins. Based on this we analyse the data for 1500,2000,3000 and 5000m performance.

3.) The code in the notebook will- walk through how to create/analyse a data set via -> webscarpping,regex,pandas,numpy, sklearn 

4.) Statistical model used - Linear regression 

    Linear model => y = mx + c | D = CS.T + D' (D= Total distance i.e 1.5,2km etc, CS= Critical Speed, T= time taken to complete D,D'= distance travelled above CS)
    
    Non-Linear model=> S = D'/T + CS (S = avg speed at which the distnaces were covered in i.e 1.5km/T, all the rest are same as above)
    
# The Output 

<img src="CS%20-image/img.png" width = 500 height= 500>

 
 

