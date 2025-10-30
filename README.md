This is my job market paper for the year of 2025-2026. It is an ongoing project.
If you are looking to replicate this, here are your instructions:
1) You will, unfortunately, have to put your own working file path in jacob_master and jacob_pathfinder for the code to execute.
2) jacob_master and jacob_pathfinder can be found in the codes+data folder. Master automates the entire project (RUN THIS FIRST TO INITIALIZE) from the raw data up to preparing the replication package, including generation of the paper, which is in tables.
3) If you want to run a separate chunk of code, you still can. Each other code calls jacob_pathfinder, aside from that initial setup, it'll run if you just open the do-file and execute it.
4) My jack knife code puts out busted Latex tables that have to be corrected by hand. For the purposes of a reader, the original tables of output are just included up front. If you want to replicate the jack knife, execute that chunk of code. However, you will have to hand-correct the table! Claude AI is perfectly good at that. I'm working on figuring out how to automate this.
5) MotherFile is the raw dataset. jacob_transformer creates the working UseData dataset that all other code works off of.
