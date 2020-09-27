https://serge-m.github.io/bjontegaard-metric-matlab-script.html
Bjontegaard metric (BD-PSNR) describes the distance between two RD-curved. I is useful to determine how big is the gain between "before" and "after" versions. Or determine what curve is better if they have complex form (for example, intersecting).
I found matlab script, that calculates BD-PSNR, but it was not correct. The limits of integration were wrong. Difference between two curves can be calculated only in the area of thein projections intersection. Fixed script was verified by data provided the auther of the metric.
Original publilcation:
G. Bjontegaard, “Calculation of average PSNR differences between RD-curves (VCEG-M33),” in VCEG Meeting (ITU-T SG16 Q.6), Austin, Texas, USA, Apr. 2001


Files for Bjontegaard metric calculation:

    bjontegaard2.m - fixed function
    bjontegaard.m - original function
    test_bjontegaard.m - tests for both implementation
    readme.txt - this file
