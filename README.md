# CBT837
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 837 is from Bruce Bordonaro and contains 2 exits which    *   FILE 837
//*           are necessary to implement, when you want to inform   *   FILE 837
//*           TSO users that there is a file waiting for them to    *   FILE 837
//*           RECEIVE under TSO/E.  The exits are:                  *   FILE 837
//*                                                                 *   FILE 837
//*       HASX13    - JES2 exit 13 to issue a $HASP549 message      *   FILE 837
//*                   that a dataset is waiting to be RECEIVEd      *   FILE 837
//*                   from another node.                            *   FILE 837
//*                                                                 *   FILE 837
//*       INMXZ02   - XMIT exit 2, to receive control when a        *   FILE 837
//*                   dataset is waiting to be RECEIVEd from a      *   FILE 837
//*                   local node.  In this case, JES2 exit 13       *   FILE 837
//*                   does not receive control.                     *   FILE 837
//*                                                                 *   FILE 837
//*           email:  sbgolob@cbttape.org                           *   FILE 837
//*                                                                 *   FILE 837
```
