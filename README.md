# CBT395
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 395 is from Seymour Metz, and contains a REXX exec        *   FILE 395
//*           that can be very useful when putting up a new MVS     *   FILE 395
//*           system.                                               *   FILE 395
//*                                                                 *   FILE 395
//*           email:   "Metz, Seymour" <smetz@nsf.gov>              *   FILE 395
//*                                                                 *   FILE 395
//*           This EXEC catalogs all of the PO and PS datasets      *   FILE 395
//*           on a volume using the extended indirect format.       *   FILE 395
//*           It assumes that all of the volumes of a system        *   FILE 395
//*           have a common 3-character prefix, that the last       *   FILE 395
//*           three characters are one of DLB, DL2, RES or RS2      *   FILE 395
//*           and that the static system variables &SYSDL1,         *   FILE 395
//*           &SYSDL2, &SYSR1 and &SYSR2 will refer to those        *   FILE 395
//*           volumes.                                              *   FILE 395
//*                                                                 *   FILE 395
//*           If a catalog is not supplied, then the master         *   FILE 395
//*           catalog is assumed.                                   *   FILE 395
//*                                                                 *   FILE 395
//*           I'd say that the user has to customize this EXEC      *   FILE 395
//*           to his/her local situation, but it's a good starting  *   FILE 395
//*           point.  (S.Golob  9/99)                               *   FILE 395
//*                                                                 *   FILE 395
```
