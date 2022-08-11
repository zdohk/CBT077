~~~~~~~~~~~~~~~~

//***FILE 077 is from Brian Westerman of Syzygy, Inc. and contains  *   FILE 077
//*           his collection of utilities which were tested to      *   FILE 077
//*           work on the Hercules MVS 3.8J Turnkey system from     *   FILE 077
//*           Volker Bandke.  Many of these utilities came from     *   FILE 077
//*           old CBT Tapes, and some are found on Brian's other    *   FILE 077
//*           file, which is File 088.  But these utilities, in     *   FILE 077
//*           these versions, have been tested to run under         *   FILE 077
//*           Hercules, running MVS 3.8J, and for those people      *   FILE 077
//*           who are restricted to that system, these are as       *   FILE 077
//*           good as gold.                                         *   FILE 077
//*                                                                 *   FILE 077
//*           My new address and phone number are                   *   FILE 077
//*                                                                 *   FILE 077
//*           Brian Westerman                                       *   FILE 077
//*           Syzygy Incorporated                                   *   FILE 077
//*           Director of Research and Development                  *   FILE 077
//*           897 Oak Park Blvd #500                                *   FILE 077
//*           Pismo Beach, CA  93449                                *   FILE 077
//*                                                                 *   FILE 077
//*           (800) 767-2244                                        *   FILE 077
//*           (800) 366-4082 - fax                                  *   FILE 077
//*                                                                 *   FILE 077
//*           email:    Brian_Westerman@SyzygyInc.com               *   FILE 077
//*                                                                 *   FILE 077
//*      The contents of the File is as follows:                    *   FILE 077
//*                                                                 *   FILE 077
//*      Module    Purpose/Info                                     *   FILE 077
//*      ------    ------------                                     *   FILE 077
//*      $         Interface to TSO CALL, use in Clists, etc.       *   FILE 077
//*      APFLIST   List the current APFLIST from memory             *   FILE 077
//*      AUTO      Command and JOB scheduler by time of day         *   FILE 077
//*      PACKRAT   Full Screen Volume maintenance Utility,          *   FILE 077
//*                requires BACKEND module                          *   FILE 077
//*      BACKEND   Part of Packrat (above)                          *   FILE 077
//*      BRODSCAN  Scan the broadcast dataset and give stats        *   FILE 077
//*      CANCELOK  Make any running Addresspace cancel-able         *   FILE 077
//*                (even VTAM)                                      *   FILE 077
//*      CATALOG   Nifty catalog maintenance command                *   FILE 077
//*      COMMAND   Issue MVS/JES commands from TSO                  *   FILE 077
//*      DATE      Display date in several formats on the OS        *   FILE 077
//*                console                                          *   FILE 077
//*      DEBE      Predecessor of DITTO                             *   FILE 077
//*      DYNABLDL  A must for pre-XA MVS systems. This program      *   FILE 077
//*                eliminates the need for a fixed IEABLDnn list,   *   FILE 077
//*                and instead creates a dynamic BLDL list table,   *   FILE 077
//*                which gets updated with the most frequently      *   FILE 077
//*                used programs.  This is an install pds, in the   *   FILE 077
//*                IEBUPDTE SYSIN format, or PDSLOAD SYSUT1 format. *   FILE 077
//*      OSDEBE2   Slight mods over base DEBE                       *   FILE 077
//*      DISPLAY   Display system Information                       *   FILE 077
//*      ILRBIRD   TSO response time test                           *   FILE 077
//*      INSTREAM  Dynamic SYSIN creation for inside of Clists      *   FILE 077
//*      KERMITT   TSO File Transfer Utility                        *   FILE 077
//*      KILL      End any addresspace                              *   FILE 077
//*      LOCATE    Show where any dataset is cataloged and also     *   FILE 077
//*                search all volumes for dups.                     *   FILE 077
//*      MINIGEN   Perform MVS sysgen in pieces so that you         *   FILE 077
//*                don't have to do extra work                      *   FILE 077
//*      DISKSEEK  Volume mapping and SIO testing utility (SMAP)    *   FILE 077
//*      DISKTEST  Test a volume before you put it in service       *   FILE 077
//*      MEMBER    Find module in linklist and/or LPA               *   FILE 077
//*      SHOWSS    Show active subsystems                           *   FILE 077
//*      SWAP      System Workload Analysis Program                 *   FILE 077
//*      SYSTEM    Display system type, machine info, IPL           *   FILE 077
//*                Date etc.                                        *   FILE 077
//*      VOLCHECK  Check a volume for miscataloged, or              *   FILE 077
//*                uncataloged datasets                             *   FILE 077
//*      VTAMCHK   Wait for VTAM to start and then issue            *   FILE 077
//*                list of commands                                 *   FILE 077
//*      WTC       Send non-rollable message to the console         *   FILE 077
//*      VTAMOPER  Vtam Secondary operator facility                 *   FILE 077
//*                                                                 *   FILE 077
~~~~~~~~~~~~~~~~

