# Sept10TrainingPrograms
Four programs are trained today. Including 3 SWINT and 1 FCOS

Three SwinT programs are using different settings to investigate to what extent different parameters have effect on the training results
Four accournts were used. 
1. Litie - SwinT1x, Lr = 0.0025 Warmup = 5000 Ims_per_batch = 8 ---- SwinT4thRun
2. Gagandeep - SwinT1x, Lr = 0.0025 Warmup = 7500 Ims_per_batch = 8 ---- SwinT5thRun
3. Tra Nam - SwinT1x, Lr = 0.0025 Warmup = 5000 Ims_per_batch = 4 ---- SwinT3rdRun
4. Kamalpreet - FCOS_R50_1x, Lr = 0.0025, Warmup = 5000, Ims_per_batch = 4

For 123, i chose not to decay the LR, which is written as        cfg.SOLVER.STEPS = []

For 4, i used the default setting, which is.      cfg.SOLVER.STEPS = (60000, 80000)
       
