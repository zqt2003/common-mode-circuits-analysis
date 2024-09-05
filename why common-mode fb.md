Actually, in a fully differential opamp, the DM output is set by the DM feedback loop. However, the CM output is independend of the CM opamp input. Because the closed-loop CM gain is zero, due to acm=0. 
Although, it is a small signal gain, we still observe the CM output voltage is independent of the CM input voltage in big signal. Imagining the scenario, you have mismatch in pmos and nmos, so may be you will get a bigger current in pmos, which will draw up the voltage of drain terminate in pmos
so there is no mechanism to balance the CM output voltage. But, if there is a mismatch between differential nmos causing DM output change, the negative feedback will force the output rechange to the original point. 

Because, higher the loop gain is, the stronger the ability to control the output voltage is. Nevertheless, we need to introduce a feedback loop with high loop gain to control the CM output voltage.[cm.pdf](https://github.com/user-attachments/files/16884025/cm.pdf)
