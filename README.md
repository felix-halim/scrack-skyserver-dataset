# scrack-skyserver-dataset
The SkyServer dataset for scrack repository

Concatenate all the splitfiles to on file:

    cat x* > skyserver.data

Move the skyserver.data to the [scrack data folder](https://github.com/felix-halim/scrack/tree/master/data).

Then, you should be able to run:

    ./run.sh skyserver.data dd1r 200000 SkyServer 1e-7 NOUP 60
    ./run.sh skyserver.data dd1r 200000 SkyServer 1e-7 HFLV 60
   
