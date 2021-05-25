# JovianCourse_ZerotoGANs



Assignment 2:

Observation:
When loss function mse_loss was used then val_loss was huge and when I changed it to l1_loss the val_loss got reduced remarkably.
When 1e-2, 1e-5 learning rate was using, most likely we observed gradient exploding problem and val_loss was coming as "nan" value.
Solution: a) use little less value of learning rate (1e-4, 1e-5, 1e-6) worked fine b) use gradient clipping
