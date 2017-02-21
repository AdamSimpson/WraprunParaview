This sample shows how to launch batch `Paraview` jobs from `wraprun` on Titan

# Prepare
Change `batch_script.pbs` such that the line `-A STF007` specifies a valid project

# Running
[@titan]$ qsub batch_script.pbs
