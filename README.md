# two-sets-of-vehicles
Test instances and results for multi-robot task allocation scheduling (MRTA) integrated with production for scheduling (1) jobs to machines, (2) vehicles for jobs delivery, (3) reticles to machines, and (4) vehicles for reticles delivery, simultaneously, in semiconductor manufacturing

Sample test instance
nj=5; // number of jobs
nm=2; // number of machines
nr=2; // number of reticles (auxilary resources)
nLotBot=1; // number of lot delivery robots
nRetBot=1; // number of reticle delivery robots
par_Jobs = { // job, processing time
<1,16>
<2,11>
<3,13>
<4,20>
<5,14>
};

par_J2M2Rs = { // job, machine, reticle
<1,1,1>
<2,1,2>
<2,2,2>
<3,2,2>
<3,1,2>
<4,1,1>
<4,2,1>
<5,1,2>
};
