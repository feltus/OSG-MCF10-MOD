OSG Pegasus Workflow Usage

1. Submit this workflow from 'login03.osgconnect.net'.
2. Clone the model Pegasus workflow like this: 'git clone https://github.com/feltus/OSG-MCF10-MOD.git --recurse-submodules'
3. Put your jobs in the model directory.
4. Edit ./tools/job-wrapper script to specify your model run script (e.g. test.py) and output {right now it just tarballs all .csv files}.
5. Submit a the OSG workflow like this: './submit'
6. Output will be returned as a tarball.
