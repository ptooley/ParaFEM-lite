$Id: readme.txt 1919 2015-10-27 17:23:12Z mexas $
    PROGRAM: xx14
DESCRIPTION: xx14 is an attempt to link ParaFEM with CGPACK.
		The program is based on p121, with extra
		calls to CGPACK routines.
      USAGE: xx14 <job_name>
     AUTHOR: Anton Shterenlikht (mexas@bris.ac.uk) 
      LINKS: http://eis.bris.ac.uk/~mexas/cgpack/

**********************************************************
Special notes for Intel compiler
**********************************************************

For the distributed memory execution (MPI),
config file xx14.conf must exist at the time of execution.
The file name (xx14.conf) is specified in parafem build/bc3.inc.
xx14.conf is created automatically by the PBS job 
script, see the template: template.bc3.pbs.
