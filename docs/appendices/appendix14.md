<h2 class="pdfAppendix"><center>APPENDIX 14:  GEOSUPPORT COPY FILES (COW)</center></h2>  


<b>This appendix contains printouts of the Geosupport COW COPY files for COBOL, Assembler, PL/1, C and  NATURAL.  (For C, COPY files take the form of header files.  For NATURAL, COPY files take the form of Local Data Areas.)</b>  

<b>The Geosupport COPY files contain source code layouts of the Geosupport work areas.  These files are stored in a COPY library that can be accessed by user application programs at compile time.  Each supported programming language has an appropriate declarative statement for referencing COPY files at compile time.  The Geosupport COPY files are listed in the following table.</b>


<center><b>GEOSUPPORT SYSTEM WORK AREA COPY FILES (COW)</b></center>

<center>Table 14-1: COW COPY Files for COBOL, Assembler, PL/1, C and NATURAL</center>


<table>
<tr>
<th rowspan="2">COW WORK AREA</th>
<th rowspan="2">FUNCTION(S)</th>
<th rowspan="2">LENGTH (bytes)</th>
<th colspan="5">- - - - - - - - - - - COPY File Name - - - - - - - - - - -</th>
</tr>
<tr>
<th>COBOL</th>
<th>ASSEMBLER</th>
<th>PL/1</th>
<th>C</th>
<th>NATURAL</th>
</tr>
<tr>
<td>WA1</td>
<td>All</td>
<td>1,200</td>
<td>P1COB</td>
<td>P1BAL</td>
<td>P1PL1</td>
<td>PAC</td>
<td>GEOLP1</td>
</tr>
<tr>
<td>WA2</td>
<td>1 & 1E (Regular WA2), 3C (Regular WA2)</td>
<td>300</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>2</td>
<td>200</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>3 (Regular WA2)</td>
<td>450</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>3 (WA2 with AUXSEG option)</td>
<td>950</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>3C (WA2 with AUXSEG option)</td>
<td>800</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>3 (Extended WA2)</td>
<td>1,000</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>3C (Extended WA2)</td>
<td>850</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>3 (Extended WA2 w/AUXSEG)</td>
<td>1,500</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>3C (Extended WA2 w/AUXSEG)</td>
<td>1,350</td>
<td>P2COB</td>
<td>P2BAL</td>
<td>P2PL1</td>
<td>PAC</td>
<td>GEOLP2</td>
</tr>
<tr>
<td>WA2</td>
<td>1A & BL (Regular WA2), BN (✶)</td>
<td>1,363</td>
<td>P2COB1A</td>
<td>P2BAL1A</td>
<td>P2PL11A</td>
<td>PAC</td>
<td>GEOLP21A</td>
</tr>
<tr>
<td>WA2</td>
<td>1A & BL (Long WA2)  (✶✶) 1A & BL (TPAD Long WA2) (✶✶✶)</td>
<td>17,750</td>
<td>P2COB1AL</td>
<td>P2BAL1A</td>
<td>P2PL11AL</td>
<td>PAC</td>
<td>GEOLP2AL</td>
</tr>
<tr>
<td>WA2</td>
<td>1A & BL & BN (Extended WA2)  (✶✶✶✶)</td>
<td>2,800</td>
<td>P2COB1AL</td>
<td>P2BAL1A</td>
<td>P2PL11AL</td>
<td>PAC</td>
<td>GEOLP2AL</td>
</tr>
<tr>
<td>WA2</td>
<td>1 & 1E (Extended WA2)</td>
<td>1,500</td>
<td>P2COB1AL</td>
<td>P2BAL1A</td>
<td>P2PL11AL</td>
<td>PAC</td>
<td>GEOLP2AL</td>
</tr>
<tr>
<td>WA2</td>
<td>1B</td>
<td>4,300</td>
<td>P2COB1AL</td>
<td>P2BAL1A</td>
<td>P2PL11AL</td>
<td>PAC</td>
<td>GEOLP2AL</td>
</tr>
<tr>
<td>WA2</td>
<td>3S</td>
<td>19,274</td>
<td>P2COB3S</td>
<td>P2BAL3S</td>
<td>P2PL13S</td>
<td>PAC</td>
<td>GEOLP23S</td>
</tr>
<tr>
<td>WA2</td>
<td>AP</td>
<td>1,363</td>
<td>P2COBAP</td>
<td>P2BALAP</td>
<td>P2PL1AP</td>
<td>PAC</td>
<td>GEOL2AP</td>
</tr>
<tr>
<td>WA2</td>
<td>AP (Extended WA2)</td>
<td>2,800</td>
<td>P2COBAP</td>
<td>P2BALAP</td>
<td>P2PL1AP</td>
<td>PAC</td>
<td>GEOL2APX</td>
</tr>
</table>

(✶) Functions 1A, BL and BN share a single regular WA2 layout.  
(✶✶) Functions 1A and BL share a single long WA2 layout.  (Function BN has no long WA2 option.).  
(✶✶✶) Functions 1A and BL share a single TPAD long WA2 layout.  (Function BN has no TPAD long WA2 option.).  
(✶✶✶✶) Functions 1A, BL and BN share a single extended WA2 layout.

[See Chapter VIII.4](/chapters/chapterVIII/section04/) for a detailed discussion of the Geosupport COPY feature.  


## <span id="appendix14.1"><center>COBOL COPY Files (COW)</center></span>  

## <span id="appendix14.2"><center>P1COB COPY File</center> </span>


    *******************************************************************  00010010
    **** LAST UPDATED OCTOBER 2016                                  ***  00020021
    **** OCT. 2016 ADDED UNIT IN INPUT AND OUTPUT V16.4             ***  00020121
    **** THIS IS THE COBOL STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM ***  00021021
    **** INDEPENDENT WORK AREA 1.                                   ***  00030010
    **** COPY FILE - P1COB.                              04/07/98   ***  00040010
    *******************************************************************  00050010
    ****               INPUT FIELDS                                ****  00060010
    *******************************************************************  00070010
             05  PIWA1-IN-FUNC-CODE                 PIC X(2).            00080010
             05  GEO-WA1-IN-FUNCTION-CODE REDEFINES PIWA1-IN-FUNC-CODE.  00090010
                10  GEO-WA1-IN-FUNCTION-1           PIC X.               00100010
                10  GEO-WA1-IN-FUNCTION-2           PIC X.               00110010
             05  PIWA1-IN-HOUSENUM-DISPLAY          PIC X(16).           00120010
             05  GEO-WA1-IN-HOUSENUM-DISPLAY REDEFINES                   00130010
                 PIWA1-IN-HOUSENUM-DISPLAY.                              00140010
               10  GEO-WA1-IN-HOUSENUM              PIC X(12).           00150010
               10  FILLER                           PIC X(4).            00160010
             05  PIWA1-IN-HOUSENUM-SORT             PIC X(11).           00170010
             05  PIWA1-IN-LOW-HOUSENUM-DISPLAY      PIC X(16).           00180010
             05  GEO-WA1-IN-LO-HOUSENUM-DISPLAY REDEFINES                00190010
                 PIWA1-IN-LOW-HOUSENUM-DISPLAY.                          00200010
               10  GEO-WA1-IN-LOW-HOUSENUM          PIC X(12).           00210010
               10  FILLER                           PIC X(4).            00220010
             05  PIWA1-IN-LOW-HOUSENUM-SORT         PIC X(11).           00230010
             05  GEO-WA1-IN-10SC-1.                                      00240010
               10  GEO-WA1-IN-BORO                  PIC X.               00250010
               10  PIWA1-IN-10SC-1                  PIC X(10).           00260010
             05  GEO-WA1-IN-STREET-1                PIC X(32).           00270010
             05  GEO-WA1-IN-10SC-2.                                      00280010
               10  GEO-WA1-IN-BORO-2                PIC X.               00290010
               10  PIWA1-IN-10SC-2                  PIC X(10).           00300010
             05  GEO-WA1-IN-STREET-2                PIC X(32).           00310010
             05  GEO-WA1-IN-10SC-3.                                      00320010
               10  GEO-WA1-IN-BORO-3                PIC X.               00330010
               10  PIWA1-IN-10SC-3                  PIC X(10).           00340010
             05  GEO-WA1-IN-STREET-3                PIC X(32).           00350010
             05  GEO-WA1-IN-BBL.                                         00360010
                10  GEO-WA1-IN-BL-BORO              PIC X.               00370010
                10  GEO-WA1-IN-BLOCKNUM             PIC X(5).            00380010
                10  GEO-WA1-IN-LOTNUM               PIC X(5).            00390010
             05  PIWA1-IN-BIN                       PIC X(7).            00400010
             05  GEO-WA1-IN-COMPASS.                                     00410010
               10  PIWA1-IN-COMPASS1                PIC X.               00420010
               10  PIWA1-IN-COMPASS2                PIC X.               00430010
             05  PIWA1-IN-NODE                      PIC X(7).            00440018
             05  GEO-WA1-IN-NON-IBM-MAIN-FRAME      PIC X(1).            00450010
             05  GEO-WA1-IN-ZIPIN                   PIC X(5).            00460010
             05  GEO-WA1-IN-UNIT                    PIC X(14).           00471021
             05  FILLER                             PIC X(82).           00471121
       ***** 05  FILLER   V16.4                     PIC X(96).           00472021
             05  GEO-WA1-IN-LONG-WORKAREA2-FLAG     PIC X.               00480010
             05  PIWA1-IN-HSE-NBR-JUSTIFY           PIC X.               00490010
             05  PIWA1-IN-HNL                       PIC X(2).            00500010
             05  PIWA1-IN-HSE-NBR-OVER-FLAG         PIC X.               00510010
             05  GEO-WA1-IN-SNL                     PIC X(2).            00520010
             05  GEO-WA1-IN-COMPACT-NAME-FLAG       PIC X.               00530010
             05  GEO-WA1-IN-XSTREET-FLAG            PIC X.               00540010
             05  PIWA1-IN-ROADBED-REQ-SWITCH        PIC X.               00550010
             05  PIWA1-IN-INTERNAL-USE-LEGACY       PIC X.               00560010
             05  PIWA1-IN-SEGAUX-SWITCH             PIC X.               00570010
             05  PIWA1-IN-BROWSE-FLAG               PIC X.               00580010
             05  PIWA1-IN-REAL-STREET-ONLY          PIC X.               00590010
             05  PIWA1-IN-TPAD-SWITCH               PIC X.               00600010
             05  PIWA1-IN-MODE-SWITCH               PIC X.               00601013
             05  PIWA1-IN-WTO-SWITCH                PIC X.               00602016
             05  FILLER                             PIC X(29).           00610017
    ******************************************************************** 00620010
    *****               OUTPUT FIELDS                              ***** 00630010
    ******************************************************************** 00640010
             05  GEO-WA1-OUT-BORONAME               PIC X(9).            00650010
             05  PIWA1-OUT-HOUSENUM-DISPLAY         PIC X(16).           00660010
             05  GEO-WA1-OUT-HOUSENUM-DISPLAY REDEFINES                  00670010
                 PIWA1-OUT-HOUSENUM-DISPLAY.                             00680010
               10  GEO-WA1-OUT-HOUSENUM             PIC X(12).           00690010
               10  FILLER                           PIC X(4).            00700010
             05  PIWA1-OUT-HOUSENUM-SORT            PIC X(11).           00710010
             05  GEO-WA1-OUT-10SC-1                 PIC X(11).           00720010
             05  GEO-WA1-OUT-STREET-1               PIC X(32).           00730010
             05  GEO-WA1-OUT-10SC-2                 PIC X(11).           00740010
             05  GEO-WA1-OUT-STREET-2               PIC X(32).           00750010
             05  GEO-WA1-OUT-10SC-3                 PIC X(11).           00760010
             05  GEO-WA1-OUT-STREET-3               PIC X(32).           00770010
             05  GEO-WA1-OUT-BBL.                                        00780010
                10  GEO-WA1-OUT-BBL-BORO            PIC X.               00790010
                10  GEO-WA1-OUT-BLOCKNUM            PIC X(5).            00800010
                10  GEO-WA1-OUT-LOTNUM              PIC X(5).            00810010
             05  PIWA1-OUT-LOW-HN-DISPLAY           PIC X(16).           00820010
             05  GEO-WA1-OUT-LOW-HN-DISPLAY REDEFINES                    00830010
                 PIWA1-OUT-LOW-HN-DISPLAY.                               00840010
               10  GEO-WA1-OUT-LOW-HOUSENUM         PIC X(12).           00850012
               10  FILLER                           PIC X(4).            00860010
             05  PIWA1-OUT-LOW-HN-SORT              PIC X(11).           00870010
             05  GEO-WA1-OUT-BIN                    PIC X(7).            00880010
             05  GEO-WA1-OUT-STREET-ATTR OCCURS 3 TIMES PIC X.           00890010
             05  GEO-WA1-OUT-REASON-CODE2           PIC X.               00891013
             05  GEO-WA1-OUT-REASON-CODE-QUAL-2     PIC X.               00891115
             05  GEO-WA1-OUT-WARNING-CODE2          PIC XX.              00893013
             05  GEO-WA1-OUT-RETURN-CODE2.                               00894013
                10  GEO-WA1-OUT-RC2-1               PIC X.               00895013
                10  GEO-WA1-OUT-RC2-2               PIC X.               00896013
             05  GEO-WA1-OUT-ERROR-MESSAGE2         PIC X(80).           00897013
             05  PIWA1-OUT-NODE                     PIC X(7).            00899019
             05  PIWA1-OUT-UNIT-SORT.                                    00899122
                10  PIWA1-OUT-UNIT-TYPE             PIC X(4).            00899221
                10  PIWA1-OUT-UNIT-ID               PIC X(10).           00899321
             05  PIWA1-OUT-UNIT-DISP                PIC X(14).           00899421
             05  FILLER                             PIC X(17).           00900021
       ***** 05  FILLER   V16.4                     PIC X(45).           00901021
             05  GEO-WA1-OUT-SND-ATTR               PIC X.               00910010
             05  GEO-WA1-OUT-REASON-CODE            PIC X.               00920010
             05  GEO-WA1-OUT-REASON-CODE-QUAL       PIC X.               00921014
             05  GEO-WA1-OUT-WARNING-CODE           PIC XX.              00940010
             05  GEO-WA1-OUT-RETURN-CODE.                                00950010
                10  GEO-WA1-OUT-RC-1                PIC X.               00960010
                10  GEO-WA1-OUT-RC-2                PIC X.               00970010
             05  GEO-WA1-OUT-ERROR-MESSAGE          PIC X(80).           00980010
             05  PIWA1-OUT-NUM-SIMILAR-STRS         PIC X(2).            00990010
             05  PIWA1-OUT-SIMILAR-B7SC             PIC X(8)             01000010
                               OCCURS 10 TIMES.                          01010010
             05  GEO-WA1-OUT-SIMILAR-NAMES          PIC X(32)            01020010
                               OCCURS 10 TIMES.                          01030010
    
## <span id="appendix14.3"><center>P2COB COPY File</center></span>

    ******************************************************************   00010032
    ****                     P2COB                                  **   00011082
    ****          LAST MODIFIED DECEMBER 2016                       **   00012082
    **** ADD NEW 2 BYTE BIKE TRAFFIC DIRECTION    YNL 12/16 V17,1   **   00013082
    **** THIS IS THE COBOL- STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM**   00020032
    **** INDEPENDENT WORK AREA 2 FOR FUNCTIONS: 1, 1E, 2, 2C, 3,    **   00030032
    **** 3C, AND 5.                                                 **   00040032
    ****                                                            **   00050032
    **** COPY FILE - P2COB.                                         **   00060032
    **** PLEASE NOTE THAT FUNCTIONS 1 AND 1E SHARE A SINGLE         **   00070032
    **** WORK AREA 2 LAYOUT, AND FUNCTIONS 2 AND 2C ALSO            **   00080032
    **** SHARE A SINGLE WORK AREA 2 LAYOUT.              04/03/01   **   00090032
    ******************************************************************   00100032
    ****              LAST MODIFIED FEBRUARY 2016                   **   00110078
    ******************************************************************   00120032
                                                                         00130032
            05  PIWA2                              PIC X(7000).          00140066
                                                                         00150032
    ******************************************************************   00160032
    ****     FOR: FUNCTIONS 1 & 1E      ******************************   00170032
                                                                         00180032
            05  PIWA2-FUNCTION1   REDEFINES PIWA2.                       00190032
               10  GEO-WA2-FN1-ACCESS-KEY          PIC X(21).            00200032
               10  GEO-WA2-FN1-CONT-PARITY         PIC X.                00210032
               10  PIWA2-FN1-LOW-HOUSENUM-SORT     PIC X(11).            00220032
               10  PIWA2-FN1-HI-HOUSENUM-SORT      PIC X(11).            00230032
               10  GEO-WA2-FN1-PREFERRED-LGC       PIC X(2).             00240032
               10  GEO-WA2-FN1-NUM-X-ST-LOW-END    PIC X.                00250032
               10  PIWA2-FN1-LOW-B5SC              PIC X(6)              00260032
                                                     OCCURS 5 TIMES.     00270032
               10  GEO-WA2-FN1-NUM-X-ST-HI-END       PIC X.              00280032
               10  PIWA2-FN1-HI-B5SC               PIC X(6)              00290032
                                                     OCCURS 5 TIMES.     00300032
               10  PIWA2-FN1-LIONKEY.                                    00310032
                   15  PIWA2-FN1-LION-BORO         PIC X.                00320032
                   15  GEO-WA2-FN1-LIONFACECODE    PIC X(4).             00330032
                   15  GEO-WA2-FN1-LIONSEQ         PIC X(5).             00340032
               10  GEO-WA2-FN1-SPECIAL-ADDR-FLAG   PIC X(1).             00350032
               10  PIWA2-FN1-SIDE-OF-STR           PIC X.                00360032
               10  GEO-WA2-FN1-SEGMENTLENGTH       PIC X(5).             00370032
               10  GEO-WA2-FN1-XCOORD              PIC X(7).             00380032
               10  GEO-WA2-FN1-YCOORD              PIC X(7).             00390032
               10  FILLER-GSS                      PIC X(8).             00400032
               10  GEO-WA2-FN1-MARBLE-RIKER-FLAG   PIC X(1).             00410032
               10  GEO-WA2-FN1-SLA                 PIC X.                00420032
               10  GEO-WA2-FN1-COMDIST.                                  00430032
                   15  GEO-WA2-FN1-COMDIST-BORO    PIC X(1).             00440032
                   15  GEO-WA2-FN1-COMDIST-NUMBER  PIC X(2).             00450032
               10  GEO-WA2-FN1-ZIP                 PIC X(5).             00460032
                                                                         00470032
     ***  THE FN1E FIELDS ARE VALID ONLY FOR FUNCTION 1E, NOT FUNC 1.**  00480032
               10  GEO-WA2-FN1E-ELECTDIST          PIC X(3).             00490032
               10  GEO-WA2-FN1E-ASSEMDIST          PIC X(2).             00500032
               10  GEO-WA2-FN1E-SPLIT-ED-FLAG      PIC X(1).             00510032
               10  GEO-WA2-FN1E-CONGDIST           PIC X(2).             00520032
               10  GEO-WA2-FN1E-SENATEDIST         PIC X(2).             00530032
               10  GEO-WA2-FN1E-COURTDIST          PIC X(2).             00540032
               10  GEO-WA2-FN1E-COUNCILDIST        PIC X(2).             00550032
                                                                         00560032
               10  GEO-WA2-FN1-HCD                 PIC X(2).             00570053
               10  GEO-WA2-FN1-HEALTHAREA          PIC X(4).             00580053
               10  GEO-WA2-FN1-SANIDIST.                                 00590032
                   15  GEO-WA2-FN1-SANIDIST-BORO   PIC X(1).             00600032
                   15  GEO-WA2-FN1-SANIDIST-NUMBER PIC X(2).             00610032
               10  GEO-WA2-FN1-SANITATION-SUBSEC   PIC X(2).             00620032
               10  GEO-WA2-FN1-SANI-REG            PIC X(5).             00630032
               10  GEO-WA2-FN1-SANI-REC            PIC X(3).             00640032
               10  GEO-WA2-FN1-POLICEDIST.                               00650032
                  15 GEO-WA2-FN1-POL-PATR-BORO-CMD PIC X(1).             00660032
                  15 GEO-WA2-FN1-POL-PRECINCT      PIC X(3).             00670032
       ** NOTE:10  GEO-WA2-FN1-FIRESEC ==> FIRE DIVISION **              00680032
               10  GEO-WA2-FN1-FIRESEC             PIC X(2).             00690032
               10  GEO-WA2-FN1-FIREBAT             PIC X(2).             00700032
               10  GEO-WA2-FN1-FIRECO.                                   00710032
                   15  GEO-WA2-FN1-FIRECO-TYPE     PIC X(1).             00720032
                   15  GEO-WA2-FN1-FIRECO-NUM      PIC X(3).             00730032
       ***     NEXT LINE WAS PREVIOUSLY SPLIT SCHOOL FLAG                00731044
               10  GEO-WA2-FN1-FILL-SCHOOL-FLAG    PIC X.                00740044
               10  GEO-WA2-FN1-SCHOOLDIST          PIC X(2).             00750032
               10  GEO-WA2-FN1-DYN-BLOCK           PIC X(3).             00760032
               10  PIWA2-FN1-POLICE-PAT-BORO       PIC X(2).             00770073
               10  GEO-WA2-FN1-FEATURE-TYPE        PIC X.                00790032
               10  GEO-WA2-FN1-SEGMENT-TYPE        PIC X.                00800032
               10  GEO-WA2-FN1-ALX                 PIC X.                00810032
               10  GEO-WA2-FN1-COINCIDENT-CNT      PIC X.                00820032
               10  FILLER                          PIC X(2).             00830058
               10  PIWA2-FN1-CENS-TRCT-BORO        PIC X.                00840158
               10  GEO-WA2-FN1-1990-CENSUSTRACT    PIC X(6).             00841058
               10  GEO-WA2-FN1-2010-CENS-TRCT      PIC X(6).             00850035
               10  GEO-WA2-FN1-2010-CENS-BLK       PIC X(4).             00860035
               10  GEO-WA2-FN1-2010-CENS-BLK-SFX   PIC X.                00870035
               10  GEO-WA2-FN1-2000-CENS-TRACT     PIC X(6).             00890035
               10  GEO-WA2-FN1-2000-CENS-BLOCK     PIC X(4).             00900035
               10  GEO-WA2-FN1-2000-CENS-BLK-SUF   PIC X.                00910035
               10  GEO-WA2-FN1-NTA                 PIC X(4).             00911050
               10  GEO-WA2-FN1-SANIT-SNOW-PRRTY    PIC X.                00912050
               10  PIWA2-FN1-SANIT-ORGANICS        PIC X(5).             00922061
               10  PIWA2-FN1-SANIT-BULK-PICK-UP    PIC X(5).             00924080
       **V16.4 10  PIWA2-FN1-SANIT-RESERVED        PIC X(5).             00924180
               10  PIWA2-FN1-HURRICANE-ZONE        PIC XX.               00925072
               10  FILLER                          PIC X(11).            00926072
               10  GEO-WA2-FN1-TRUE-HNS            PIC X(11).            00930032
               10  GEO-WA2-FN1-TRUE-B7SC           PIC X(8).             00940032
               10  GEO-WA2-FN1-SEG-ID              PIC X(7).             00950032
               10  GEO-WA2-FN1-CURVE-FLAG          PIC X(1).             00960032
                                                                         00970032
    ******************************************************************   00980032
    ****     FOR: FUNCTIONS 2       **********************************   00990032
                                                                         01000032
            05  PIWA2-FUNCTION2   REDEFINES PIWA2.                       01010032
               10  PIWA2-FN2-ACCESS-KEY            PIC X(21).            01020032
               10  GEO-WA2-FN2-DUPINTERFLAG        PIC X.                01030032
               10  GEO-WA2-FN2-PREFERRED-LGC1      PIC X(2).             01040032
               10  GEO-WA2-FN2-PREFERRED-LGC2      PIC X(2).             01050032
               10  GEO-WA2-FN2-NUM-OF-INTERSECTS   PIC X.                01060032
               10  PIWA2-FN2-INTERSECT-B5SC        PIC X(6)              01070032
                                                   OCCURS 5 TIMES.       01080032
               10  GEO-WA2-FN2-COMPDIR             PIC X.                01090032
               10  GEO-WA2-FN2-ATOMIC-POLYGON      PIC X(3).             01091064
               10  FILLER                          PIC X(2).             01100057
               10  GEO-WA2-FN2-NODE-NUM            PIC X(7).             01110032
               10  GEO-WA2-FN2-XCOORD              PIC X(7).             01120032
               10  GEO-WA2-FN2-YCOORD              PIC X(7).             01130032
               10  FILLER-GSS                      PIC X(7).             01140032
               10  GEO-WA2-FN2-SANBORN1-BVOLPAGE.                        01150032
                  15 GEO-WA2-FN2-SANBORN1-BORO     PIC X(1).             01160032
                  15 GEO-WA2-FN2-SANBORN1-VOL-NUM  PIC X(3).             01170032
                  15 GEO-WA2-FN2-SANBORN1-PAGE-NUM PIC X(4).             01180032
               10  GEO-WA2-FN2-SANBORN2-BVOLPAGE.                        01190032
                  15 GEO-WA2-FN2-SANBORN2-BORO     PIC X(1).             01200032
                  15 GEO-WA2-FN2-SANBORN2-VOL-NUM  PIC X(3).             01210032
                  15 GEO-WA2-FN2-SANBORN2-PAGE-NUM PIC X(4).             01220032
               10  GEO-WA2-FN2-MARBLE-RIKER-FLAG   PIC X(1).             01230032
               10  GEO-WA2-FN2-SLA                   PIC X.              01240032
               10  GEO-WA2-FN2-COMDIST.                                  01250032
                   15  GEO-WA2-FN2-COMDIST-BORO    PIC X(1).             01260032
                   15  GEO-WA2-FN2-COMDIST-NUMBER  PIC X(2).             01270032
               10  GEO-WA2-FN2-ZIP                 PIC X(5).             01280032
               10  GEO-WA2-FN2-HEALTHAREA          PIC X(4).             01290053
               10  GEO-WA2-FN2-POLICEDIST.                               01300032
                  15 GEO-WA2-FN2-POL-PATR-BORO-CMD PIC X(1).             01310032
                  15 GEO-WA2-FN2-POL-PRECINCT      PIC X(3).             01320032
       ** NOTE:10  GEO-WA2-FN2-FIRESEC ==> FIRE DIVISION **              01330032
               10  GEO-WA2-FN2-FIRESEC             PIC X(2).             01340032
               10  GEO-WA2-FN2-FIREBAT             PIC X(2).             01350032
               10  GEO-WA2-FN2-FIRECO.                                   01360032
                   15  GEO-WA2-FN2-FIRECO-TYPE     PIC X(1).             01370032
                   15  GEO-WA2-FN2-FIRECO-NUM      PIC X(3).             01380032
               10  GEO-WA2-FN2-SCHOOLDIST          PIC X(2).             01390032
               10  GEO-WA2-FN2-2010-CENS-TRCT      PIC X(6).             01400035
               10  GEO-WA2-FN2-1990-CENSUSTRACT    PIC X(6).             01410032
               10  GEO-WA2-FN2-LEVEL-LIST OCCURS 5 TIMES.                01420032
                   15 GEO-WA2-FN2-LEVEL-CODES                            01430032
                      OCCURS 2 TIMES               PIC X.                01440032
               10  PIWA2-FN2-POLICE-PAT-BORO       PIC X(2).             01470073
               10  GEO-WA2-FN2-ASSEMDIST           PIC X(2).             01471073
               10  GEO-WA2-FN2-CONGDIST            PIC X(2).             01480032
               10  GEO-WA2-FN2-SENATEDIST          PIC X(2).             01490032
               10  GEO-WA2-FN2-COURTDIST           PIC X(2).             01500032
               10  GEO-WA2-FN2-COUNCILDIST         PIC X(2).             01510032
               10  GEO-WA2-FN2-CDELIG              PIC X(1).             01520032
               10  GEO-WA2-FN2-DUP-INT-DISTANCE    PIC X(5).             01530032
               10  GEO-WA2-FN2-2000-CENS-TRACT     PIC X(6).             01550035
               10  PIWA2-FN2-HCD                   PIC X(2).             01551053
               10  PIWA2-FN2-SANITATION-DIST       PIC X(3).             01552045
               10  PIWA2-FN2-SANITATION-SUBSEC     PIC X(2).             01553047
               10  FILLER                          PIC X(12).            01560047
                                                                         01561059
    ******************************************************************   01562059
    ****     FOR: FUNCTIONS 2W      **********************************   01563065
                                                                         01564059
            05  PIWA2-FUNCTION2W  REDEFINES PIWA2.                       01565065
               10  PIWA2-2W-ACCESS-KEY             PIC X(21).            01566065
               10  GEO-WA2-2W-DUPINTERFLAG         PIC X.                01567065
               10  GEO-WA2-2W-PREFERRED-LGC1       PIC X(2).             01568065
               10  GEO-WA2-2W-PREFERRED-LGC2       PIC X(2).             01569065
               10  GEO-WA2-2W-NUM-OF-INTERSECTS    PIC X.                01569165
               10  PIWA2-2W-INTERSECT-B5SC         PIC X(6)              01569265
                                                   OCCURS 5 TIMES.       01569359
               10  GEO-WA2-2W-COMPDIR              PIC X.                01569465
               10  GEO-WA2-2W-ATOMIC-POLYGON       PIC X(3).             01569565
               10  FILLER                          PIC X(2).             01569659
               10  GEO-WA2-2W-NODE-NUM             PIC X(7).             01569765
               10  GEO-WA2-2W-XCOORD               PIC X(7).             01569865
               10  GEO-WA2-2W-YCOORD               PIC X(7).             01569965
               10  FILLER-GSS                      PIC X(7).             01570059
               10  GEO-WA2-2W-SANBORN1-BVOLPAGE.                         01570165
                  15 GEO-WA2-2W-SANBORN1-BORO      PIC X(1).             01570265
                  15 GEO-WA2-2W-SANBORN1-VOL-NUM   PIC X(3).             01570365
                  15 GEO-WA2-2W-SANBORN1-PAGE-NUM PIC X(4).              01570465
               10  GEO-WA2-2W-SANBORN2-BVOLPAGE.                         01570565
                  15 GEO-WA2-2W-SANBORN2-BORO      PIC X(1).             01570665
                  15 GEO-WA2-2W-SANBORN2-VOL-NUM   PIC X(3).             01570765
                  15 GEO-WA2-2W-SANBORN2-PAGE-NUM PIC X(4).              01570865
               10  GEO-WA2-2W-MARBLE-RIKER-FLAG    PIC X(1).             01570965
               10  GEO-WA2-2W-SLA                    PIC X.              01571065
               10  GEO-WA2-2W-COMDIST.                                   01571165
                   15  GEO-WA2-2W-COMDIST-BORO     PIC X(1).             01571265
                   15  GEO-WA2-2W-COMDIST-NUMBER   PIC X(2).             01571365
               10  GEO-WA2-2W-ZIP                  PIC X(5).             01571465
               10  GEO-WA2-2W-HEALTHAREA           PIC X(4).             01571565
               10  GEO-WA2-2W-POLICEDIST.                                01571665
                  15 GEO-WA2-2W-POL-PATR-BORO-CMD PIC X(1).              01571765
                  15 GEO-WA2-2W-POL-PRECINCT       PIC X(3).             01571865
       ** NOTE:10  GEO-WA2-2W-FIRESEC ==> FIRE DIVISION **               01571965
               10  GEO-WA2-2W-FIRESEC              PIC X(2).             01572065
               10  GEO-WA2-2W-FIREBAT              PIC X(2).             01572165
               10  GEO-WA2-2W-FIRECO.                                    01572265
                   15  GEO-WA2-2W-FIRECO-TYPE      PIC X(1).             01572365
                   15  GEO-WA2-2W-FIRECO-NUM       PIC X(3).             01572465
               10  GEO-WA2-2W-SCHOOLDIST           PIC X(2).             01572565
               10  GEO-WA2-2W-2010-CENS-TRCT       PIC X(6).             01572665
               10  GEO-WA2-2W-1990-CENSUSTRACT     PIC X(6).             01572765
               10  GEO-WA2-2W-LEVEL-LIST OCCURS 5 TIMES.                 01572865
                   15 GEO-WA2-2W-LEVEL-CODES                             01572965
                      OCCURS 2 TIMES               PIC X.                01573059
               10  PIWA2-2W-POLICE-PAT-BORO        PIC X(2).             01573373
               10  GEO-WA2-2W-ASSEMDIST            PIC X(2).             01573473
               10  GEO-WA2-2W-CONGDIST             PIC X(2).             01573573
               10  GEO-WA2-2W-SENATEDIST           PIC X(2).             01573673
               10  GEO-WA2-2W-COURTDIST            PIC X(2).             01573773
               10  GEO-WA2-2W-COUNCILDIST          PIC X(2).             01573873
               10  GEO-WA2-2W-CDELIG               PIC X(1).             01573973
               10  GEO-WA2-2W-DUP-INT-DISTANCE     PIC X(5).             01574073
               10  GEO-WA2-2W-2000-CENS-TRACT      PIC X(6).             01574173
               10  PIWA2-2W-HCD                    PIC X(2).             01574273
               10  PIWA2-2W-SANITATION-DIST        PIC X(3).             01574373
               10  PIWA2-2W-SANITATION-SUBSEC      PIC X(2).             01574473
               10  FILLER                          PIC X(12).            01574573
               10  FILLER                          PIC X(22).            01574673
               10  PIWA2-2W-LGCS-1                 PIC X(8).             01574773
               10  PIWA2-2W-LGCS-2                 PIC X(8).             01574873
               10  PIWA2-2W-TURN-RESTRICTIONS      PIC X(10).            01574965
               10  PIWA2-2W-LGCS-FOR-B5SCS         PIC X(2)              01575065
                                                   OCCURS 5 TIMES.       01575160
               10  PIWA2-2W-TRUE-REP-COUNTER       PIC XX.               01575265
               10  PIWA2-2W-NODE-LIST              PIC X(7)              01575365
                                                   OCCURS 20 TIMES.      01575463
               10 PIWA2-2W-NODE-LIST-B7SCS-LIST    OCCURS 20 TIMES.      01575771
                15 PIWA2-2W-NODE-LIST-B7SCS        OCCURS 5  TIMES.      01575871
                 20 PIWA2-2W-NODE-LIST-B7SC        PIC X(8)              01575971
                                                   OCCURS 4 TIMES.       01576067
               10  PIWA2-2W-REASON-CODE            PIC X.                01585471
               10  PIWA2-2W-REASON-CODE-QUAL       PIC X.                01585571
               10  PIWA2-2W-WARN-CODE              PIC XX.               01585671
               10  PIWA2-2W-RETURN-CODE            PIC XX.               01585771
               10  PIWA2-2W-LATITUDE               PIC X(9).             01585874
               10  PIWA2-2W-LONGITUDE              PIC X(11).            01585974
               10  FILLER                          PIC X(374).           01586474
       ****    10  FILLER  V15.3                   PIC X(394).           01586574
                                                                         01586674
    ******************************************************************   01587065
    ****     FOR: FUNCTION  3           ******************************   01590032
                                                                         01600032
            05  PIWA2-FUNCTION3   REDEFINES PIWA2.                       01610032
               10  GEO-WA2-FN3-ACCESS-KEY          PIC X(21).            01620032
               10  GEO-WA2-FN3-DUP-KEY-FLAG        PIC X.                01630032
               10  GEO-WA2-FN3-LOCATION-STATUS     PIC X.                01640032
               10  GEO-WA2-FN3-COUNTY-BOUNDARY     PIC X.                01650032
               10  GEO-WA2-FN3-PREFERRED-LGC1      PIC X(2).             01660032
               10  GEO-WA2-FN3-PREFERRED-LGC2      PIC X(2).             01670032
               10  GEO-WA2-FN3-PREFERRED-LGC3      PIC X(2).             01680032
               10  GEO-WA2-FN3-NUM-X-ST-LOW-END    PIC X.                01690032
               10  PIWA2-FN3-LOW-B5SC              PIC X(6)              01700032
                                                     OCCURS 5 TIMES.     01710032
               10  GEO-WA2-FN3-NUM-X-ST-HI-END     PIC X.                01720032
               10  PIWA2-FN3-HI-B5SC               PIC X(6)              01730032
                                                     OCCURS 5 TIMES.     01740032
               10  GEO-WA2-FN3-REVERSALFLAG        PIC X.                01750032
               10  PIWA2-FN3-LIONKEY.                                    01760032
                   15  PIWA2-FN3-LION-BORO         PIC X.                01770032
                   15  GEO-WA2-FN3-LIONFACECODE    PIC X(4).             01780032
                   15  GEO-WA2-FN3-LIONSEQ         PIC X(5).             01790032
               10  GEO-WA2-FN3-GENRECFLAG          PIC X.                01800032
               10  PIWA2-FN3-SEG-LEN               PIC X(5).             01810032
               10  GEO-WA2-FN3-SEGMENTSLOPE        PIC X(3).             01820032
               10  GEO-WA2-FN3-SEGMENTORIENT       PIC X.                01830032
               10  GEO-WA2-FN3-MARBLE-RIKER-FLAG   PIC X(1).             01840032
               10  GEO-WA2-FN3-FROM-NODE           PIC X(7).             01850032
               10  GEO-WA2-FN3-TO-NODE             PIC X(7).             01860032
               10  GEO-WA2-FN3-SANIT-SNOW-PRRTY    PIC X.                01861050
               10  FILLER                          PIC X(4).             01870050
               10  GEO-WA2-FN3-SEG-ID              PIC X(7).             01880032
               10  GEO-WA2-FN3-SLA                 PIC X.                01890032
               10  GEO-WA2-FN3-CURVE-FLAG          PIC X.                01900032
               10  GEO-WA2-FN3-DOG-LEG             PIC X.                01910032
               10  GEO-WA2-FN3-FEATURE-TYPE        PIC X.                01920032
               10  GEO-WA2-FN3-SEGMENT-TYPE        PIC X.                01930032
               10  GEO-WA2-FN3-COINCIDENT-CNT      PIC X.                01940032
               10  FILLER                          PIC X(4).             01950032
               10  PIWA2-FN3-LEFT-SIDE-OF-STR.                           01960032
                   15  GEO-WA2-FN3-LEFT-COMDIST.                         01970032
                     20  GEO-WA2-FN3-LEFT-COMDIST-BORO PIC X(1).         01980032
                     20  GEO-WA2-FN3-LEFT-COMDIST-NUM  PIC X(2).         01990032
                   15  PIWA2-FN3-L-LOW-HOUSENUM        PIC X(16).        02000032
                   15  PIWA2-FN3-L-HI-HOUSENUM         PIC X(16).        02010032
                   15  FILLER-GSS                      PIC X(33).        02020032
                   15  GEO-WA2-FN3-LEFT-ZIP            PIC X(5).         02030032
                   15  GEO-WA2-FN3-LEFT-HEALTHAREA     PIC X(4).         02040053
                   15  GEO-WA2-FN3-LEFT-POLDIST.                         02050032
                    20  GEO-WA2-FN3-L-POL-PATR-BOR-CMD PIC X(1).         02060032
                    20  GEO-WA2-FN3-L-POL-PRECINCT     PIC X(3).         02070032
       ** NOTE:10  GEO-WA2-3L-R-FIRESEC ==> FIRE DIV **                  02080032
                   15  GEO-WA2-3L-L-FIRESEC            PIC X(2).         02090032
                   15  GEO-WA2-3L-L-FIREBAT            PIC X(2).         02100032
                   15  GEO-WA2-3L-L-FIRECO.                              02110032
                       20  GEO-WA2-3L-L-FIRECO-TYPE    PIC X(1).         02120032
                       20  GEO-WA2-3L-L-FIRECO-NUM     PIC X(3).         02130032
                   15  GEO-WA2-FN3-LEFT-SCHLDIST       PIC X(2).         02140032
                   15  GEO-WA2-3L-L-DYN-BLOCK          PIC X(3).         02150032
                   15  PIWA2-FN3-L-ED                  PIC X(3).         02161036
                   15  PIWA2-FN3-L-AD                  PIC X(2).         02162036
                   15  PIWA2-FN3-L-POLICE-PAT-BORO     PIC X(2).         02163073
                   15  FILLER                          PIC X.            02170073
                   15  GEO-WA2-3L-L-BORO               PIC X .           02190051
                   15  GEO-WA2-3L-L-1990-CENSUSTRACT   PIC X(6) .        02191051
                   15  GEO-WA2-3L-L-2010-CENS-TRCT     PIC X(6).         02200035
                   15  GEO-WA2-3L-L-2010-CENS-BLK      PIC X(4).         02210035
                   15  GEO-WA2-3L-L-2010-CENS-BLK-SFX  PIC X.            02220035
                   15  GEO-WA2-3L-L-2000-CENS-TRACT    PIC X(6).         02240035
                   15  GEO-WA2-3L-L-2000-CENS-BLOCK    PIC X(4).         02250035
                   15  GEO-WA2-3L-L-2000-CENS-BLK-SUF  PIC X.            02260035
                   15  FILLER                          PIC X(7).         02260176
       ****        15  PIWA2-FN3-L-BLOCKFACE-ID *V16.1*PIC X(7)**        02261076
                   15  PIWA2-FN3-L-NTA                 PIC X(4).         02261150
                   15  FILLER                          PIC X(8).         02270050
               10  PIWA2-FN3-RIGHT-SIDE-OF-STR.                          02280032
                   15  GEO-WA2-FN3-RIGHT-COMDIST.                        02290032
                     20 GEO-WA2-FN3-RIGHT-COMDIST-BORO PIC X(1).         02300032
                     20 GEO-WA2-FN3-RIGHT-COMDIST-NUM  PIC X(2).         02310032
                   15  PIWA2-FN3-R-LOW-HOUSENUM        PIC X(16).        02320032
                   15  PIWA2-FN3-R-HI-HOUSENUM         PIC X(16).        02330032
                   15  FILLER-GSS                      PIC X(33).        02340032
                   15  GEO-WA2-FN3-RIGHT-ZIP           PIC X(5).         02350032
                   15  GEO-WA2-FN3-RIGHT-HEALTHAREA    PIC X(4).         02360053
                   15  GEO-WA2-FN3-RIGHT-POLDIST.                        02370032
                    20 GEO-WA2-FN3-R-POL-PATR-BOR-CMD  PIC X(1).         02380032
                    20 GEO-WA2-FN3-R-POL-PRECINCT      PIC X(3).         02390032
                   15  GEO-WA2-3L-R-FIRESEC            PIC X(2).         02400032
                   15  GEO-WA2-3L-R-FIREBAT            PIC X(2).         02410032
                   15  GEO-WA2-3L-R-FIRECO.                              02420032
                       20  GEO-WA2-3L-R-FIRECO-TYPE    PIC X(1).         02430032
                       20  GEO-WA2-3L-R-FIRECO-NUM     PIC X(3).         02440032
                   15  GEO-WA2-FN3-RIGHT-SCHLDIST      PIC X(2).         02450032
                   15  GEO-WA2-3L-R-DYN-BLOCK          PIC X(3).         02460032
                   15  PIWA2-FN3-R-ED                  PIC X(3).         02471036
                   15  PIWA2-FN3-R-AD                  PIC X(2).         02472036
                   15  PIWA2-FN3-R-POLICE-PAT-BORO     PIC X(2).         02473073
                   15  FILLER                          PIC X.            02490073
                   15  GEO-WA2-3L-R-BORO               PIC X.            02500051
                   15  GEO-WA2-3L-R-1990-CENSUSTRACT   PIC X(6).         02501051
                   15  GEO-WA2-3L-R-2010-CENS-TRCT     PIC X(6).         02510035
                   15  GEO-WA2-3L-R-2010-CENS-BLK      PIC X(4).         02520035
                   15  GEO-WA2-3L-R-2010-CENS-BLK-SFX  PIC X.            02530035
                   15  GEO-WA2-3L-R-2000-CENS-TRACT    PIC X(6).         02550035
                   15  GEO-WA2-3L-R-2000-CENS-BLOCK    PIC X(4).         02560035
                   15  GEO-WA2-3L-R-2000-CENS-BLK-SUF  PIC X.            02570035
                   15  FILLER                          PIC X(7).         02570176
       ****        15  PIWA2-FN3-R-BLOCKFACE-ID *V16.1*PIC X(7)**        02570276
                   15  PIWA2-FN3-R-NTA                 PIC X(4).         02572050
                   15  FILLER                          PIC X(8).         02580050
                                                                         02590032
            05  PIWA2-AUX-FUNCTION3 REDEFINES PIWA2.                     02600032
               10  FILLER                              PIC X(450).       02610032
               10  PIWA2-FN3-SEGAUX.                                     02620032
                   15  PIWA2-FN3-SEGAUX-FILL           PIC X(6).         02630032
                   15  PIWA2-FN3-SEGAUX-CTR            PIC X(4).         02640032
                   15  PIWA2-FN3-SEGAUX-SEGS OCCURS 70 TIMES             02650032
                                                       PIC X(7).         02660032
                                                                         02670032
    ******************************************************************   02670136
    ****     FOR: FUNCTION  3 EXTENDED  ******************************   02671036
                                                                         02672036
            05  PIWA2-FUNCTION3X  REDEFINES PIWA2.                       02673036
               10  PIWA2-3X-ACCESS-KEY             PIC X(21).            02674042
               10  PIWA2-3X-DUP-KEY-FLAG           PIC X.                02675042
               10  PIWA2-3X-LOCATION-STATUS        PIC X.                02676042
               10  PIWA2-3X-COUNTY-BOUNDARY        PIC X.                02677042
               10  PIWA2-3X-PREFERRED-LGC1         PIC X(2).             02678042
               10  PIWA2-3X-PREFERRED-LGC2         PIC X(2).             02679042
               10  PIWA2-3X-PREFERRED-LGC3         PIC X(2).             02679142
               10  PIWA2-3X-NUM-X-ST-LOW-END       PIC X.                02679242
               10  PIWA2-3X-LOW-B5SC               PIC X(6)              02679338
                                                     OCCURS 5 TIMES.     02679436
               10  PIWA2-3X-NUM-X-ST-HI-END        PIC X.                02679542
               10  PIWA2-3X-HI-B5SC                PIC X(6)              02679638
                                                     OCCURS 5 TIMES.     02679736
               10  PIWA2-3X-REVERSALFLAG           PIC X.                02679842
               10  PIWA2-3X-LIONKEY.                                     02679938
                   15  PIWA2-3X-LION-BORO          PIC X.                02680038
                   15  PIWA2-3X-LIONFACECODE       PIC X(4).             02680142
                   15  PIWA2-3X-LIONSEQ            PIC X(5).             02680242
               10  PIWA2-3X-GENRECFLAG             PIC X.                02680342
               10  PIWA2-3X-SEG-LEN                PIC X(5).             02680438
               10  PIWA2-3X-SEGMENTSLOPE           PIC X(3).             02680542
               10  PIWA2-3X-SEGMENTORIENT          PIC X.                02680642
               10  PIWA2-3X-MARBLE-RIKER-FLAG      PIC X(1).             02680742
               10  PIWA2-3X-FROM-NODE              PIC X(7).             02680842
               10  PIWA2-3X-TO-NODE                PIC X(7).             02680942
               10  PIWA2-3X-SANIT-SNOW-PRRTY       PIC X.                02681050
               10  FILLER                          PIC X(4).             02681150
               10  PIWA2-3X-SEG-ID                 PIC X(7).             02681250
               10  PIWA2-3X-SLA                    PIC X.                02681350
               10  PIWA2-3X-CURVE-FLAG             PIC X.                02681450
               10  PIWA2-3X-DOG-LEG                PIC X.                02681550
               10  PIWA2-3X-FEATURE-TYPE           PIC X.                02681650
               10  PIWA2-3X-SEGMENT-TYPE           PIC X.                02681750
               10  PIWA2-3X-COINCIDENT-CNT         PIC X.                02681850
               10  FILLER                          PIC X(4).             02681950
               10  PIWA2-3X-LEFT-SIDE-OF-STR.                            02682050
                   15  PIWA2-3X-LEFT-COMDIST.                            02682150
                     20  PIWA2-3X-LEFT-COMDIST-BORO    PIC X(1).         02682250
                     20  PIWA2-3X-LEFT-COMDIST-NUM     PIC  X(2).        02682350
                   15  PIWA2-3X-L-LOW-HOUSENUM         PIC X(16).        02682450
                   15  PIWA2-3X-L-HI-HOUSENUM          PIC X(16).        02682550
                   15  FILLER-GSS                      PIC X(33).        02682650
                   15  PIWA2-3X-LEFT-ZIP               PIC X(5).         02682750
                   15  PIWA2-3X-LEFT-HEALTHAREA        PIC X(4).         02682853
                   15  PIWA2-3X-LEFT-POLDIST.                            02682950
                    20  PIWA2-3X-L-POL-PATR-BOR-CMD    PIC X(1).         02683050
                    20  PIWA2-3X-L-POL-PRECINCT        PIC X(3).         02683150
       ** NOTE:10  PIWA2-3XL-R-FIRESEC ==> FIRE DIV **                   02683250
                   15  PIWA2-3X-L-FIRESEC              PIC X(2).         02683350
                   15  PIWA2-3X-L-FIREBAT              PIC X(2).         02683450
                   15  PIWA2-3X-L-FIRECO.                                02683550
                       20  PIWA2-3X-L-FIRECO-TYPE      PIC X(1).         02683650
                       20  PIWA2-3X-L-FIRECO-NUM       PIC X(3).         02683750
                   15  PIWA2-3X-LEFT-SCHLDIST          PIC X(2).         02683850
                   15  PIWA2-3X-L-DYN-BLOCK            PIC X(3).         02683950
                   15  PIWA2-3X-L-ED                   PIC X(3).         02684138
                   15  PIWA2-3X-L-AD                   PIC X(2).         02684238
                   15  PIWA2-3X-L-POLICE-PAT-BORO      PIC X(2).         02684373
                   15  FILLER                          PIC X.            02684473
                   15  PIWA2-3X-L-BORO                 PIC X .           02684551
                   15  PIWA2-3X-L-1990-CENSUSTRACT     PIC X(6) .        02684651
                   15  PIWA2-3X-L-2010-CENS-TRCT       PIC X(6).         02684751
                   15  PIWA2-3X-L-2010-CENS-BLK        PIC X(4).         02684851
                   15  PIWA2-3X-L-2010-CENS-BLK-SFX    PIC X.            02684951
                   15  PIWA2-3X-L-2000-CENS-TRACT      PIC X(6).         02685051
                   15  GIWA2-3X-L-2000-CENS-BLOCK      PIC X(4).         02685151
                   15  PIWA2-3X-L-2000-CENS-BLK-SUF    PIC X.            02685251
                   15  FILLER                          PIC X(7).         02685376
       ****        15  PIWA2-3X-L-BLOCKFACE-ID *V16.1* PIC X(7)***       02685476
                   15  PIWA2-3X-L-NTA                  PIC X(4).         02685551
                   15  FILLER                          PIC X(8).         02685651
               10  PIWA2-3X-RIGHT-SIDE-OF-STR.                           02685751
                   15  PIWA2-3X-RIGHT-COMDIST.                           02685851
                     20 PIWA2-3X-RIGHT-COMDIST-BORO    PIC X(1).         02685951
                     20 PIWA2-3X-RIGHT-COMDIST-NUM     PIC X(2).         02686051
                   15  PIWA2-3X-R-LOW-HOUSENUM         PIC X(16).        02686151
                   15  PIWA2-3X-R-HI-HOUSENUM          PIC X(16).        02686251
                   15  FILLER-GSS                      PIC X(33).        02686351
                   15  PIWA2-3X-RIGHT-ZIP              PIC X(5).         02686451
                   15  PIWA2-3X-RIGHT-HEALTHAREA       PIC X(4).         02686553
                   15  PIWA2-3X-RIGHT-POLDIST.                           02686651
                    20 PIWA2-3X-R-POL-PATR-BOR-CMD     PIC X(1).         02686751
                    20 PIWA2-3X-R-POL-PRECINCT         PIC X(3).         02686851
                   15  PIWA2-3X-R-FIRESEC              PIC X(2).         02686951
                   15  PIWA2-3X-R-FIREBAT              PIC X(2).         02687051
                   15  PIWA2-3X-R-FIRECO.                                02687151
                       20  PIWA2-3X-R-FIRECO-TYPE      PIC X(1).         02687251
                       20  PIWA2-3X-R-FIRECO-NUM       PIC X(3).         02687351
                   15  PIWA2-3X-RIGHT-SCHLDIST         PIC X(2).         02687451
                   15  PIWA2-3X-R-DYN-BLOCK            PIC X(3).         02687551
       ***     NEXT LINE WAS PREVIOUSLY INSTRUC-DIV                      02687651
                   15  PIWA2-3X-R-ED                   PIC X(3).         02687751
                   15  PIWA2-3X-R-AD                   PIC X(2).         02687851
                   15  PIWA2-3X-R-POLICE-PAT-BORO      PIC X(2).         02687973
                   15  FILLER                          PIC X.            02688073
                   15  PIWA2-3X-R-BORO                 PIC X.            02688173
                   15  PIWA2-3X-R-1990-CENSUSTRACT     PIC X(6).         02688273
                   15  PIWA2-3X-R-2010-CENS-TRCT       PIC X(6).         02688373
                   15  PIWA2-3X-R-2010-CENS-BLK        PIC X(4).         02688473
                   15  PIWA2-3X-R-2010-CENS-BLK-SFX    PIC X.            02688573
                   15  PIWA2-3X-R-2000-CENS-TRACT      PIC X(6).         02688673
                   15  PIWA2-3X-R-2000-CENS-BLOCK      PIC X(4).         02688773
                   15  PIWA2-3X-R-2000-CENS-BLK-SUF    PIC X.            02688873
                   15  FILLER                          PIC X(7).         02688976
       ****        15  PIWA2-3X-R-BLOCKFACE-ID *V16.1* PIC X(7)***       02689076
                   15  PIWA2-3X-R-NTA                  PIC X(4).         02689273
                   15  FILLER                          PIC X(8).         02689373
                   15  PIWA2-3X-LGCS                   PIC X(8).         02689473
                   15  PIWA2-3X-LGCS-FROM              PIC X(8).         02689573
                   15  PIWA2-3X-LGCS-TO                PIC X(8).         02689673
                   15  PIWA2-3X-L-HCD                  PIC X(2).         02689773
                   15  PIWA2-3X-R-HCD                  PIC X(2).         02689873
                   15  FILLER                          PIC X(1).         02689973
                   15  PIWA2-3X-TRAFFIC-DIR            PIC X(1).         02690073
                   15  PIWA2-3X-ROADWAY-TYPE           PIC X(2).         02690173
                   15  PIWA2-3X-PHYSICAL-ID            PIC X(7).         02690273
                   15  PIWA2-3X-GENERIC-ID             PIC X(7).         02690373
                   15  PIWA2-3X-INTP-ID-INT-USE        PIC X(7).         02690473
                   15  PIWA2-3X-INFD-ID-INT-USE        PIC X(7).         02690573
                   15  PIWA2-3X-STR-STATUS             PIC X(1).         02690673
                   15  PIWA2-3X-STR-WIDTH              PIC X(3).         02690773
                   15  PIWA2-3X-STR-WIDTH-IRREG        PIC X(1).         02690873
                   15  PIWA2-3X-BIKE-LANE              PIC X(1).         02690973
                   15  PIWA2-3X-FED-CLASS-CODE         PIC X(2).         02691073
                   15  PIWA2-3X-ROW-TYPE               PIC X(1).         02691173
                   15  PIWA2-3X-LGC-LIST               PIC X(10).        02691273
                   15  PIWA2-3X-LEGACY-ID              PIC X(7).         02691373
                   15  PIWA2-3X-L-NTA-NAME             PIC X(75).        02691473
                   15  PIWA2-3X-R-NTA-NAME             PIC X(75).        02691573
                   15  PIWA2-3X-FROM-XCOORD            PIC X(7).         02691673
                   15  PIWA2-3X-FROM-YCOORD            PIC X(7).         02691773
                   15  PIWA2-3X-TO-XCOORD              PIC X(7).         02691873
                   15  PIWA2-3X-TO-YCOORD              PIC X(7).         02691973
                   15  PIWA2-3X-FROM-LATITUDE          PIC X(9).         02692075
                   15  PIWA2-3X-FROM-LONGITUDE         PIC X(11).        02692175
                   15  PIWA2-3X-TO-LATITUDE            PIC X(9).         02692275
                   15  PIWA2-3X-TO-LONGITUDE           PIC X(11).        02692375
                   15  PIWA2-3X-L-BLOCKFACE-ID         PIC X(10).        02692476
                   15  PIWA2-3X-R-BLOCKFACE-ID         PIC X(10).        02692576
                   15  PIWA2-3X-NBR-TRAVEL-LANES       PIC X(2).         02692676
                   15  PIWA2-3X-NBR-PARK-LANES         PIC X(2).         02692776
                   15  PIWA2-3X-NBR-TOTAL-LANES        PIC X(2).         02692876
                   15  PIWA2-3X-BIKE-LANE-2            PIC X(2).         02692979
                   15  PIWA2-3X-STR-WIDTH-MAX          PIC X(3).         02693079
                   15  PIWA2-3X-BIKE-TRAFFIC-DIR       PIC X(2).         02693181
                   15  FILLER                          PIC X(213).       02693281
       ****        15  FILLER   V17.1                  PIC X(215).       02693381
       ****        15  FILLER   V16.4                  PIC X(220).       02693481
       ****        15  FILLER   V16.1                  PIC X(246).       02693581
       ****        15  FILLER   V15.3                  PIC X(286).       02693681
                                                                         02693781
            05  PIWA2-AUX-FUNCTION3X REDEFINES PIWA2.                    02693881
               10  FILLER                              PIC X(1000).      02693981
               10  PIWA2-3X-SEGAUX.                                      02694081
                   15  PIWA2-3X-SEGAUX-FILL            PIC X(6).         02694181
                   15  PIWA2-3X-SEGAUX-CTR             PIC X(4).         02694281
                   15  PIWA2-3X-SEGAUX-SEGS OCCURS 70 TIMES              02694381
                                                       PIC X(7).         02694481
                                                                         02694581
    ******************************************************************   02694681
    ****     FOR: FUNCTION  3C          ******************************   02695076
                                                                         02700032
            05  PIWA2-FUNCTION3C  REDEFINES PIWA2.                       02710032
               10  GEO-WA2-FN3C-ACCESS-KEY          PIC X(21).           02720032
               10  PIWA2-FN3C-DUP-KEY-FLAG          PIC X.               02730032
               10  GEO-WA2-FN3C-LOCATION-STATUS     PIC X.               02740032
               10  GEO-WA2-FN3C-COUNTY-BOUNDARY     PIC X.               02750032
               10  GEO-WA2-FN3C-PREFERRED-LGC1      PIC X(2).            02760032
               10  GEO-WA2-FN3C-PREFERRED-LGC2      PIC X(2).            02770032
               10  GEO-WA2-FN3C-PREFERRED-LGC3      PIC X(2).            02780032
               10  GEO-WA2-FN3C-NUM-X-ST-LOW-END    PIC X.               02790032
               10  PIWA2-FN3C-LOW-B5SC              PIC X(6)             02800032
                                                     OCCURS 5 TIMES.     02810032
               10  GEO-WA2-FN3C-NUM-X-ST-HI-END     PIC X.               02820032
               10  PIWA2-FN3C-HI-B5SC               PIC X(6)             02830032
                                                     OCCURS 5 TIMES.     02840032
               10  GEO-WA2-FN3C-REVERSALFLAG        PIC X.               02850032
               10  PIWA2-FN3C-LIONKEY.                                   02860032
                   15  PIWA2-FN3C-LION-BORO         PIC X.               02870032
                   15  GEO-WA2-FN3C-LIONFACECODE    PIC X(4).            02880032
                   15  GEO-WA2-FN3C-LIONSEQ         PIC X(5).            02890032
               10  GEO-WA2-FN3C-GENRECFLAG          PIC X.               02900032
               10  PIWA2-FN3C-SEG-LEN               PIC X(5).            02910032
               10  GEO-WA2-FN3C-SEGMENTSLOPE        PIC X(3).            02920032
               10  GEO-WA2-FN3C-SEGMENTORIENT       PIC X.               02930032
               10  GEO-WA2-FN3C-MARBLE-RIKER-FLAG   PIC X(1).            02940032
               10  GEO-WA2-FN3C-FROM-NODE           PIC X(7).            02950032
               10  GEO-WA2-FN3C-TO-NODE             PIC X(7).            02960032
               10  GEO-WA2-FN3C-SANIT-SNOW-PRRTY    PIC X.               02961050
               10  FILLER                           PIC X(4).            02970050
               10  GEO-WA2-FN3C-SEG-ID              PIC X(7).            02980032
               10  GEO-WA2-FN3C-SLA                 PIC X.               02990032
               10  PIWA2-FN3C-SIDE-OF-STR           PIC X.               03000032
               10  GEO-WA2-FN3C-CURVE-FLAG          PIC X.               03010032
               10  GEO-WA2-FN3C-FEATURE-TYPE        PIC X.               03020032
               10  GEO-WA2-FN3C-SEGMENT-TYPE        PIC X.               03030032
               10  GEO-WA2-FN3C-COINCIDENT-CNT      PIC X.               03040032
               10  FILLER                           PIC X(4).            03050032
               10  PIWA2-FN3C-BLOCKFACE-INFO.                            03060032
                   15  GEO-WA2-FN3C-COMDIST.                             03070032
                      20  GEO-WA2-FN3C-COMDIST-BORO   PIC X(1).          03080032
                      20  GEO-WA2-FN3C-COMDIST-NUMBER PIC X(2).          03090032
                   15  PIWA2-FN3C-LOW-HOUSENUM        PIC X(16).         03100032
                   15  PIWA2-FN3C-HI-HOUSENUM         PIC X(16).         03110032
                   15  PIWA2-FN3C-LOW-HOUSENUM2       PIC X(16).         03120032
                   15  PIWA2-FN3C-HI-HOUSENUM2        PIC X(16).         03130032
                   15  FILLER-GSS                     PIC X.             03140032
                   15  GEO-WA2-FN3C-ZIP               PIC X(5).          03150032
                   15  GEO-WA2-FN3C-HEALTHAREA        PIC X(4).          03160053
                   15  GEO-WA2-FN3C-POLICEDIST.                          03170032
                    20 GEO-WA2-FN3C-POL-PATR-BORO-CMD PIC X(1).          03180032
                    20 GEO-WA2-FN3C-POL-PRECINCT      PIC X(3).          03190032
       ** NOTE:10  GEO-WA2-FN3C-FIRESEC ==> FIRE DIVISION **             03200032
                   15  GEO-WA2-FN3C-FIRESEC           PIC X(2).          03210032
                   15  GEO-WA2-FN3C-FIREBAT           PIC X(2).          03220032
                   15  GEO-WA2-FN3C-FIRECO.                              03230032
                       20  GEO-WA2-FN3C-FIRECO-TYPE   PIC X(1).          03240032
                       20  GEO-WA2-FN3C-FIRECO-NUM    PIC X(3).          03250032
                   15  GEO-WA2-FN3C-SCHOOLDIST        PIC X(2).          03260032
                   15  GEO-WA2-FN3C-DYN-BLOCK         PIC X(3).          03270032
                   15  PIWA2-FN3C-ED                  PIC X(3).          03281041
                   15  PIWA2-FN3C-AD                  PIC X(2).          03282041
                   15  PIWA2-FN3C-POLICE-PAT-BORO     PIC X(2).          03282173
                   15  FILLER                         PIC X.             03283073
                   15  GEO-WA2-FN3C-BORO              PIC X.             03310051
                   15  GEO-WA2-FN3C-1990-CENSUSTRACT  PIC X(6).          03311051
                   15  GEO-WA2-FN3C-2010-CENS-TRCT    PIC X(6).          03320035
                   15  GEO-WA2-FN3C-2010-CENS-BLK     PIC X(4).          03330035
                   15  GEO-WA2-FN3C-2010-CENS-BLK-SFX PIC X.             03340035
                   15  GEO-WA2-FN3C-2000-CENS-TRACT   PIC X(6).          03360035
                   15  GEO-WA2-FN3C-2000-CENS-BLOCK   PIC X(4).          03370035
                   15  GEO-WA2-FN3C-2000-CENS-BLK-SUF PIC X.             03380035
                   15  FILLER                         PIC X(7).          03380177
       ******      15  PIWA2-FN3C-BLOCKFACE-ID  V16.1 PIC X(7)***        03381077
                   15  PIWA2-FN3C-NTA                 PIC X(4).          03382050
                   15  FILLER                         PIC X(8).          03390050
                                                                         03400032
            05  PIWA2-AUX-FUNCTION3C REDEFINES PIWA2.                    03410032
               10  FILLER                             PIC X(300).        03420037
               10  PIWA2-FN3C-SEGAUX.                                    03430032
                   15  PIWA2-FN3C-SEGAUX-FILL         PIC X(4).          03440032
                   15  PIWA2-FN3C-SEGAUX-CTR          PIC X(4).          03450032
                   15  PIWA2-FN3C-SEGAUX-SEGS OCCURS 70 TIMES            03460032
                                                      PIC X(7).          03470032
                                                                         03480032
    ******************************************************************   03481036
    ****     FOR: FUNCTION  3C EXTENDED ******************************   03482036
                                                                         03483036
            05  PIWA2-FUNCTION3CX REDEFINES PIWA2.                       03484036
               10  PIWA2-3CX-ACCESS-KEY             PIC X(21).           03485042
               10  PIWA2-3CX-DUP-KEY-FLAG           PIC X.               03486039
               10  PIWA2-3CX-LOCATION-STATUS        PIC X.               03487042
               10  PIWA2-3CX-COUNTY-BOUNDARY        PIC X.               03488042
               10  PIWA2-3CX-PREFERRED-LGC1         PIC X(2).            03489042
               10  PIWA2-3CX-PREFERRED-LGC2         PIC X(2).            03489142
               10  PIWA2-3CX-PREFERRED-LGC3         PIC X(2).            03489242
               10  PIWA2-3CX-NUM-X-ST-LOW-END       PIC X.               03489342
               10  PIWA2-3CX-LOW-B5SC               PIC X(6)             03489439
                                                    OCCURS 5 TIMES.      03489536
               10  PIWA2-3CX-NUM-X-ST-HI-END        PIC X.               03489642
               10  PIWA2-3CX-HI-B5SC                PIC X(6)             03489739
                                                    OCCURS 5 TIMES.      03489836
               10  PIWA2-3CX-REVERSALFLAG           PIC X.               03489942
               10  PIWA2-3CX-LIONKEY.                                    03490039
                   15  PIWA2-3CX-LION-BORO          PIC X.               03490139
                   15  PIWA2-3CX-LIONFACECODE       PIC X(4).            03490242
                   15  PIWA2-3CX-LIONSEQ            PIC X(5).            03490342
               10  PIWA2-3CX-GENRECFLAG             PIC X.               03490442
               10  PIWA2-3CX-SEG-LEN                PIC X(5).            03490539
               10  PIWA2-3CX-SEGMENTSLOPE           PIC X(3).            03490642
               10  PIWA2-3CX-SEGMENTORIENT          PIC X.               03490742
               10  PIWA2-3CX-MARBLE-RIKER-FLAG      PIC X(1).            03490842
               10  PIWA2-3CX-FROM-NODE              PIC X(7).            03490942
               10  PIWA2-3CX-TO-NODE                PIC X(7).            03491042
               10  PIWA2-3CX-SANIT-SNOW-PRRTY       PIC X.               03491150
               10  FILLER                           PIC X(4).            03491250
               10  PIWA2-3CX-SEG-ID                 PIC X(7).            03491342
               10  PIWA2-3CX-SLA                    PIC X.               03491442
               10  PIWA2-3CX-SIDE-OF-STR            PIC X.               03491539
               10  PIWA2-3CX-CURVE-FLAG             PIC X.               03491642
               10  PIWA2-3CX-FEATURE-TYPE           PIC X.               03491742
               10  PIWA2-3CX-SEGMENT-TYPE           PIC X.               03491842
               10  PIWA2-3CX-COINCIDENT-CNT         PIC X.               03491942
               10  FILLER                           PIC X(4).            03492036
               10  PIWA2-3CX-BLOCKFACE-INFO.                             03492139
                   15  PIWA2-3CX-COMDIST.                                03492242
                      20  PIWA2-3CX-COMDIST-BORO    PIC X(1).            03492342
                      20  PIWA2-3CX-COMDIST-NUMBER  PIC X(2).            03492442
                   15  PIWA2-3CX-LOW-HOUSENUM         PIC X(16).         03492539
                   15  PIWA2-3CX-HI-HOUSENUM          PIC X(16).         03492639
                   15  PIWA2-3CX-LOW-HOUSENUM2        PIC X(16).         03492739
                   15  PIWA2-3CX-HI-HOUSENUM2         PIC X(16).         03492839
                   15  FILLER-GSS                     PIC X.             03492936
                   15  PIWA2-3CX-ZIP                  PIC X(5).          03493042
                   15  PIWA2-3CX-HEALTHAREA           PIC X(4).          03493153
                   15  PIWA2-3CX-POLICEDIST.                             03493242
                    20 PIWA2-3CX-POL-PATR-BORO-CMD    PIC X(1).          03493342
                    20 PIWA2-3CX-POL-PRECINCT         PIC X(3).          03493442
       ** NOTE:10  PIWA2-3CX-FIRESEC ==> FIRE DIVISION **                03493542
                   15  PIWA2-3CX-FIRESEC              PIC X(2).          03493642
                   15  PIWA2-3CX-FIREBAT              PIC X(2).          03493742
                   15  PIWA2-3CX-FIRECO.                                 03493842
                       20  PIWA2-3CX-FIRECO-TYPE      PIC X(1).          03493942
                       20  PIWA2-3CX-FIRECO-NUM       PIC X(3).          03494042
                   15  PIWA2-3CX-SCHOOLDIST           PIC X(2).          03494142
                   15  PIWA2-3CX-DYN-BLOCK            PIC X(3).          03494242
                   15  PIWA2-3CX-ED                   PIC X(3).          03494439
                   15  PIWA2-3CX-AD                   PIC X(2).          03494539
                   15  PIWA2-3CX-POLICE-PAT-BORO      PIC X(2).          03494673
                   15  FILLER                         PIC X.             03494773
                   15  PIWA2-3CX-BORO                 PIC X.             03494851
                   15  PIWA2-3CX-1990-CENSUSTRACT     PIC X(6).          03494951
                   15  PIWA2-3CX-2010-CENS-TRCT       PIC X(6).          03495051
                   15  PIWA2-3CX-2010-CENS-BLK        PIC X(4).          03495151
                   15  PIWA2-3CX-2010-CENS-BLK-SFX    PIC X.             03495251
                   15  PIWA2-3CX-2000-CENS-TRACT      PIC X(6).          03495351
                   15  PIWA2-3CX-2000-CENS-BLOCK      PIC X(4).          03495451
                   15  PIWA2-3CX-2000-CENS-BLK-SUF    PIC X.             03495551
                   15  FILLER                         PIC X(7).          03495677
       *****       15  PIWA2-3CX-BLOCKFACE-ID V16.1   PIC X(7)***        03495777
                   15  PIWA2-3CX-NTA                  PIC X(4).          03495851
                   15  FILLER                         PIC X(8).          03495951
                   15  PIWA2-3CX-LGCS                 PIC X(8).          03496051
                   15  PIWA2-3CX-LGCS-FROM            PIC X(8).          03496151
                   15  PIWA2-3CX-LGCS-TO              PIC X(8).          03496251
                   15  PIWA2-3CX-L-HCD                PIC X(2).          03496353
                   15  PIWA2-3CX-R-HCD                PIC X(2).          03496453
                   15  FILLER                         PIC X(1).          03496551
                   15  PIWA2-3CX-TRAFFIC-DIR          PIC X(1).          03496651
                   15  PIWA2-3CX-ROADWAY-TYPE         PIC X(2).          03496751
                   15  PIWA2-3CX-PHYSICAL-ID          PIC X(7).          03496851
                   15  PIWA2-3CX-GENERIC-ID           PIC X(7).          03496951
                   15  PIWA2-3CX-INTP-ID              PIC X(7).          03497051
                   15  PIWA2-3CX-INFD-ID              PIC X(7).          03497151
                   15  PIWA2-3CX-STR-STATUS           PIC X(1).          03497251
                   15  PIWA2-3CX-STR-WIDTH            PIC X(3).          03497351
                   15  PIWA2-3CX-STR-WIDTH-IRREF      PIC X(1).          03497451
                   15  PIWA2-3CX-BIKE-LANE            PIC X(1).          03497551
                   15  PIWA2-3CX-FED-CLASS-CODE       PIC X(2).          03497651
                   15  PIWA2-3CX-ROW-TYPE             PIC X(1).          03497751
                   15  PIWA2-3CX-LGC-LIST             PIC X(10).         03497851
                   15  PIWA2-3CX-LEGACY-ID            PIC X(7).          03497951
                   15  PIWA2-3CX-NTA-NAME             PIC X(75).         03498052
                   15  PIWA2-3CX-FROM-XCOORD          PIC X(7).          03498156
                   15  PIWA2-3CX-FROM-YCOORD          PIC X(7).          03498256
                   15  PIWA2-3CX-TO-XCOORD            PIC X(7).          03498356
                   15  PIWA2-3CX-TO-YCOORD            PIC X(7).          03498456
                   15  PIWA2-3CX-FROM-LATITUDE        PIC X(9).          03498575
                   15  PIWA2-3CX-FROM-LONGITUDE       PIC X(11).         03498675
                   15  PIWA2-3CX-TO-LATITUDE          PIC X(9).          03498775
                   15  PIWA2-3CX-TO-LONGITUDE         PIC X(11).         03498875
                   15  PIWA2-3CX-BLOCKFACE-ID         PIC X(10).         03498977
                   15  PIWA2-3CX-NBR-TRAVEL-LANES     PIC X(2).          03499077
                   15  PIWA2-3CX-NBR-PARK-LANES       PIC X(2).          03499177
                   15  PIWA2-3CX-NBR-TOTAL-LANES      PIC X(2).          03499277
                   15  PIWA2-3CX-BIKE-LANE-2          PIC X(2).          03499379
                   15  PIWA2-3CX-STR-WIDTH-MAX        PIC X(3).          03499479
                   15  PIWA2-3CX-BIKE-TRAFFIC-DIR     PIC X(2).          03499581
                   15  FILLER                         PIC X(298).        03499681
       ****        15  FILLER   V17.1                 PIC X(300).        03499781
       ****        15  FILLER   V16.4                 PIC X(305).        03499881
       ****        15  FILLER   V16.1                 PIC X(321).        03499981
       ****        15  FILLER   V15.3                 PIC X(361).        03500081
                                                                         03500181
            05  PIWA2-AUX-FUNCTION3CX REDEFINES PIWA2.                   03500281
               10  FILLER                            PIC X(850).         03500381
               10  PIWA2-3CX-SEGAUX.                                     03500481
                   15  PIWA2-3CX-SEGAUX-FILL          PIC X(4).          03500581
                   15  PIWA2-3CX-SEGAUX-CTR           PIC X(4).          03500681
                   15  PIWA2-3CX-SEGAUX-SEGS OCCURS 70 TIMES             03500781
                                                      PIC X(7).          03500881
                                                                         03500981
    ******************************************************************   03501081
    ****     FOR: FUNCTION 5            ******************************   03502081
                                                                         03510032
            05  PIWA2-FUNCTION5   REDEFINES PIWA2.                       03520032
               10  GEO-WA2-FN5-ADDR-MATCHING-KEY      PIC X(33).         03530034

    

## <span id="appendix14.4"><center>P2COB1A COPY File</center></span>  


    *****************************************************************  00010007
    **  THIS IS THE COBOL STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM **  00020007
    **  INDEPENDENT REGULAR WORK AREA 2 FOR FUNCTIONS: 1A, BL, AND **  00030007
    **  BN.  THESE THREE FUNCTIONS SHARE A SINGLE WORK AREA 2      **  00040007
    **  LAYOUT.  COPY FILE - P2COB1A.                 10/10/97     **  00050007
    *****************************************************************  00060007
                                                                       00070007
          05  GEO-WA2-1A-ACCESS-KEY              PIC X(21).            00080007
          05  GEO-WA2-1A-CONT-PARITY             PIC X.                00090007
          05  PIWA2-1A-LOW-HOUSENUM              PIC X(11).            00100007
          05  GEO-WA2-1A-ALTKEY-1.                                     00110007
             10 GEO-WA2-1A-ALTKEY-1-BORO         PIC X.                00120007
             10 GEO-WA2-1A-ALTKEY-1-TAXBLOCK     PIC X(5).             00130007
             10 GEO-WA2-1A-ALTKEY-1-TAXLOT       PIC X(4).             00140007
          05  FILLER                             PIC X.                00150007
          05  GEO-WA2-1A-SCC                     PIC X(1).             00160007
          05  FILLER                             PIC X.                00170007
          05  GEO-WA2-1A-GENERAL-LOT-INFO.                             00180007
             10 GEO-WA2-1A-RPAD-BLDG-CLASS       PIC X(2).             00190007
             10 GEO-WA2-1A-CORNER-CODE           PIC X(2).             00200007
             10 GEO-WA2-1A-TOT-NBR-BLDG          PIC X(4).             00210007
             10 GEO-WA2-1A-NUM-OF-BLOCKFACES     PIC X(2).             00220007
             10 GEO-WA2-1A-INTERIOR-FLAG         PIC X.                00230007
             10 GEO-WA2-1A-VACANT-FLAG           PIC X.                00240007
             10 GEO-WA2-1A-IRREG-FLAG            PIC X.                00250007
          05  GEO-WA2-1A-ALT-BORO-FLAG           PIC X.                00260007
          05  GEO-WA2-1A-OVERFLOW-FLAG           PIC X(1).             00270007
          05  PIWA2-1A-STROLL-KEY                PIC X(19).            00280007
          05  FILLER-GSS                         PIC X.                00290007
          05  GEO-WA2-1A-BLDG-ID-NUM             PIC X(7).             00300007
          05  GEO-WA2-1A-CONDO-LOT-FLAG          PIC X.                00310007
          05  FILLER                             PIC X.                00320007
          05  GEO-WA2-1A-RPAD-COND-NUM           PIC X(4).             00330007
          05  FILLER                             PIC X(7).             00340007
          05  GEO-WA2-1A-CONDO-BILLING-BBL       PIC X(10).            00350007
          05  FILLER                             PIC X.                00360007
          05  GEO-WA2-1A-CONDO-BILL-BBL-SCC      PIC X(1).             00370007
          05  GEO-WA2-1A-CONDO-LOW-BBL           PIC X(10).            00380007
          05  FILLER                             PIC X.                00390007
          05  GEO-WA2-1A-CONDO-HIGH-BBL          PIC X(10).            00400007
          05  FILLER                             PIC X.                00410007
          05  FILLER                             PIC X(15).            00420007
          05  GEO-WA2-1A-CO-OP-NBR               PIC X(4).             00430007
          05  GEO-WA2-1A-SANBORN-BVOLPAGE.                             00440007
              10  GEO-WA2-1A-SANBORN-BORO        PIC X(1).             00450007
              10  GEO-WA2-1A-SANBORN-VOL-PAGE.                         00460007
                15  GEO-WA2-1A-SANBORN-VOL-NUM   PIC X(3).             00470007
                15  GEO-WA2-1A-SANBORN-PAGE-NUM  PIC X(4).             00480007
          05  GEO-WA2-1A-COMMERC-DIST            PIC X(5).             00490007
          05  GEO-WA2-1A-DOF-MAP-BOROUGH         PIC X.                00500007
          05  GEO-WA2-1A-TAX-MAP-NBR             PIC X(4).             00510007
          05  FILLER-FOR-TAX-MAP-PAGE            PIC X(4).             00520007
          05  FILLER                             PIC X(3).             00530009
          05  PIWA2-1A-LATITUDE                  PIC X(9).             00540009
          05  PIWA2-1A-LONGITUDE                 PIC X(11).            00540110
          05  PIWA2-1A-X-COORD                   PIC X(7).             00541009
          05  PIWA2-1A-Y-COORD                   PIC X(7).             00550007
          05  PIWA2-1A-BID                       PIC X(6).             00560007
          05  PIWA2-1A-TPAD-BIN-ST               PIC X.                00570007
          05  PIWA2-1A-TPAD-NEW-BIN              PIC X(7).             00580007
          05  PIWA2-1A-TPAD-NEW-BIN-ST           PIC X.                00590007
          05  PIWA2-1A-TPAD-CONFLICT             PIC X.                00600007
          05  FILLER                             PIC X(9).             00610007
          05  FILLER-GSS                         PIC X(8).             00620007
          05  PIWA2-1A-NUM-OF-ADDR               PIC X(4).             00630007
          05  PIWA2-1A-ADDR-LIST                 OCCURS 21 TIMES.      00640007
             10  PIWA2-1A-LIST-LOW-HOUSENUM      PIC X(16).            00650007
             10  PIWA2-1A-LIST-HI-HOUSENUM       PIC X(16).            00660007
             10  PIWA2-1A-LIST-BORO              PIC X.                00670007
             10  PIWA2-1A-LIST-5SC               PIC X(5).             00680007
             10  PIWA2-1A-LIST-LGC               PIC X(2).             00690007
             10  GEO-WA2-1A-LIST-BIN             PIC X(7).             00700007
             10  GEO-WA2-1A-LIST-SOS             PIC X.                00710007
             10  GEO-WA2-1A-ADDR-TYPE            PIC X.                00720007
             10  PIWA2-1A-TPAD-STATUS            PIC X.                00730007
             10  FILLER                          PIC X(3).             00740007

    

## <span id="appendix14.5"><center>P2COB1AL COPY File</center></span>

    *****************************************************************  00001006
    **                     P2COBIAL                                **  00001134
    **          LAST MODIFIED DECEMBER 2016                        **  00001234
    ** ADD NEW 2 BYTE BIKE TRAFFIC DIRECTION    YNL 12/16 V17,1    **  00001334
    **  THIS IS THE COBOL STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM **  00002006
    **  INDEPENDENT LONG WORK AREA 2 FOR FUNCTIONS: 1A, AND BL.    **  00003006
    **  THESE TWO FUNCTIONS SHARE A SINGLE LONG WORK AREA 2 LAYOU. **  00004006
    **  COPY FILE - P2COB1AL.                         11/06/97     **  00005006
    *****************************************************************  00006006
    **              LAST MODIFIED OCTOBER  2016                    **  00006130
    *****************************************************************  00006227
    **  JANUARY 2011 YNL ADDED THREE WORK AREAS:                   **  00007006
    **  1. P2COB1EX - FUNCTION 1E EXTENDED.                        **  00008007
    **  2. P2COB1AX - FUNCTION 1A   EXTENDED.                      **  00009006
    **  2. P2COB1B  - P2COB1EX COMBINED WITH P2COB1AX              **  00009116
    *****************************************************************  00009206
          03  PIWA2                               PIC X(17750).        00009406
    ******************************************************************   00009606
    ****     FOR: FUNCTION 1A LONG      ******************************   00009706
                                                                       00009806
          03  PIWA2-FUNCTION1AL  REDEFINES PIWA2.                      00009906
                                                                       00010006
           05 GEO-WA2-1AL-ACCESS-KEY              PIC X(21).           00010106
           05 GEO-WA2-1AL-CONT-PARITY             PIC X.               00010206
           05 PIWA2-1AL-LOW-HOUSENUM              PIC X(11).           00010306
           05 GEO-WA2-1AL-ALTKEY-1.                                    00010406
             10 GEO-WA2-1AL-ALTKEY-1-BORO         PIC X.               00010506
             10 GEO-WA2-1AL-ALTKEY-1-TAXBLOCK     PIC X(5).            00010606
             10 GEO-WA2-1AL-ALTKEY-1-TAXLOT       PIC X(4).            00010706
           05 FILLER                              PIC X.               00010806
           05 GEO-WA2-1AL-SCC                     PIC X.               00010906
           05 FILLER                              PIC X.               00011006
           05 GEO-WA2-1AL-GENERAL-LOT-INFO.                            00011106
             10 GEO-WA2-1AL-RPAD-BLDG-CLASS       PIC X(2).            00011206
             10 GEO-WA2-1AL-CORNER-CODE           PIC X(2).            00011306
             10 GEO-WA2-1AL-NUM-OF-STRUCTURES     PIC X(4).            00011406
             10 GEO-WA2-1AL-NUM-OF-BLOCKFACES     PIC X(2).            00011506
             10 GEO-WA2-1AL-INTERIOR-FLAG         PIC X.               00011606
             10 GEO-WA2-1AL-VACANT-FLAG           PIC X.               00011706
             10 GEO-WA2-1AL-IRREG-FLAG            PIC X.               00011806
           05 GEO-WA2-1AL-ALT-BORO-FLAG           PIC X.               00011906
           05 FILLER                              PIC X.               00012006
           05 PIWA2-1AL-STROLL-KEY                PIC X(19).           00012106
           05 FILLER-GSS                          PIC X.               00012206
           05 GEO-WA2-1AL-BLDG-ID-NUM             PIC X(7).            00012306
           05 GEO-WA2-1AL-CONDO-LOT-FLAG          PIC X.               00012406
           05 FILLER                              PIC X.               00012506
           05 GEO-WA2-1AL-RPAD-COND-NUM           PIC X(4).            00012606
           05 FILLER                              PIC X(7).            00012706
           05 GEO-WA2-1AL-CONDO-BILLING-BBL       PIC X(10).           00012806
           05 FILLER                              PIC X.               00012906
           05 GEO-WA2-1AL-CONDO-BILL-BBL-SCC      PIC X.               00013006
           05 GEO-WA2-1AL-CONDO-LOW-BBL           PIC X(10).           00013106
           05 FILLER                              PIC X.               00013206
           05 GEO-WA2-1AL-CONDO-HIGH-BBL          PIC X(10).           00013306
           05 FILLER                              PIC X.               00013406
           05 FILLER                              PIC X(15).           00013506
           05 GEO-WA2-1AL-CO-OP-NBR               PIC X(4).            00013606
           05 GEO-WA2-1AL-SANBORN-BVOLPAGE.                            00013706
              10  GEO-WA2-1AL-SANBORN-BORO        PIC X(1).            00013806
              10  GEO-WA2-1AL-SANBORN-VOL-PAGE.                        00013906
                15  GEO-WA2-1AL-SANBORN-VOL-NUM   PIC X(3).            00014006
                15  GEO-WA2-1AL-SANBORN-PAGE-NUM  PIC X(4).            00014106
           05 GEO-WA2-1AL-COMMERC-DIST            PIC X(5).            00014206
           05 PIWA2-1AL-DOF-MAP-BORO              PIC X.               00014306
           05 PIWA2-1AL-DOF-MAP-SECVOL            PIC X(4).            00014406
     *******  PIWA2-1AL-DOF-MAP-PAGE  NOT IMPLEMENTED                  00014506
           05 PIWA2-1AL-DOF-MAP-PAGE              PIC X(4).            00014606
           05 FILLER                              PIC X(3).            00014719
           05 PIWA2-1AL-LATITUDE                  PIC X(9).            00014819
           05 PIWA2-1AL-LONGITUDE                 PIC X(11).           00014919
           05 PIWA2-1AL-X-COORD                   PIC X(7).            00015019
           05 PIWA2-1AL-Y-COORD                   PIC X(7).            00015119
           05 PIWA2-1AL-BID                       PIC X(6).            00015219
           05 PIWA2-1AL-TPAD-BIN-ST               PIC X.               00015319
           05 PIWA2-1AL-TPAD-NEW-BIN              PIC X(7).            00015419
           05 PIWA2-1AL-TPAD-NEW-BIN-ST           PIC X.               00015519
           05 PIWA2-1AL-TPAD-CONFLICT             PIC X.               00015619
           05 FILLER                              PIC X(9).            00015719
           05 FILLER-GSS                          PIC X(8).            00015819
           05 GEO-WA2-1AL-NUM-OF-BINS             PIC X(4).            00015919
           05 PIWA2-1AL-TPAD-BINLIST.                                  00016019
              10 PIWA2-1AL-TPAD-BINS OCCURS 2187 TIMES.                00016119
                15 PIWA2-1AL-TPAD-BINS-BIN         PIC X(7).           00016219
                15 PIWA2-1AL-TPAD-BINS-STAT        PIC X.              00016319
              10 PIWA2-1AL-TPAD-FILL               PIC X(4).           00016419
           05 GEO-WA2-1AL-BINS REDEFINES PIWA2-1AL-TPAD-BINLIST        00016519
              PIC X(7)  OCCURS 2500 TIMES.                             00016619
                                                                       00016719
     ***************************************************************   00016819
     ***   FOR: FUNCTION 1/1E EXTENDED  *****************3**********   00016919
                                                                       00017019
          03  PIWA2-FUNCTION1EX   REDEFINES PIWA2.                     00017119
                                                                       00017219
           05 PIWA2-FN1EX-ACCESS-KEY              PIC X(21).           00017319
           05 PIWA2-FN1EX-CONT-PARITY             PIC X.               00017419
           05 PIWA2-FN1EX-LOW-HOUSENUM-SORT       PIC X(11).           00017519
           05 PIWA2-FN1EX-HI-HOUSENUM-SORT        PIC X(11).           00017619
           05 PIWA2-FN1EX-PREFERRED-LGC           PIC X(2).            00017719
           05 PIWA2-FN1EX-NUM-X-ST-LOW-END        PIC X.               00017819
           05 PIWA2-FN1EX-LOW-B5SC                PIC X(6)             00017919
                                                   OCCURS 5 TIMES.     00018019
           05 PIWA2-FN1EX-NUM-X-ST-HI-END         PIC X.               00018119
           05 PIWA2-FN1EX-HI-B5SC                 PIC X(6)             00018219
                                                   OCCURS 5 TIMES.     00018319
           05 PIWA2-FN1EX-LIONKEY.                                     00018419
               10  PIWA2-FN1EX-LION-BORO          PIC X.               00018519
               10  PIWA2-FN1EX-LIONFACECODE       PIC X(4).            00018619
               10  PIWA2-FN1EX-LIONSEQ            PIC X(5).            00018719
           05 PIWA2-FN1EX-SPECIAL-ADDR-FLAG       PIC X(1).            00018819
           05 PIWA2-FN1EX-SIDE-OF-STR             PIC X.               00018919
           05 PIWA2-FN1EX-SEGMENTLENGTH           PIC X(5).            00019019
           05 PIWA2-FN1EX-XCOORD                  PIC X(7).            00019119
           05 PIWA2-FN1EX-YCOORD                  PIC X(7).            00019219
           05 FILLER-GSS                          PIC X(8).            00019319
           05 PIWA2-FN1EX-MARBLE-RIKER-FLAG       PIC X(1).            00019419
           05 PIWA2-FN1EX-SLA                     PIC X.               00019519
           05 PIWA2-FN1EX-COMDIST.                                     00019619
               10  PIWA2-FN1EX-COMDIST-BORO       PIC X(1).            00019719
               10  PIWA2-FN1EX-COMDIST-NUMBER     PIC X(2).            00019819
           05 PIWA2-FN1EX-ZIP                     PIC X(5).            00019919
                                                                       00020019
           05 PIWA2-FN1EX-ELECTDIST               PIC X(3).            00020119
           05 PIWA2-FN1EX-ASSEMDIST               PIC X(2).            00020219
           05 PIWA2-FN1EX-SPLIT-ED-FLAG           PIC X(1).            00020319
           05 PIWA2-FN1EX-CONGDIST                PIC X(2).            00020419
           05 PIWA2-FN1EX-SENATEDIST              PIC X(2).            00020519
           05 PIWA2-FN1EX-COURTDIST               PIC X(2).            00020619
           05 PIWA2-FN1EX-COUNCILDIST             PIC X(2).            00020719
                                                                       00020819
           05 PIWA2-FN1EX-HCD                     PIC X(2).            00020919
           05 PIWA2-FN1EX-HEALTHAREA              PIC X(4).            00021019
           05 PIWA2-FN1EX-SANIDIST.                                    00021119
               10  PIWA2-FN1EX-SANIDIST-BORO      PIC X(1).            00021219
               10  PIWA2-FN1EX-SANIDIST-NUMBER    PIC X(2).            00021319
           05 PIWA2-FN1EX-SANITATION-SUBSEC       PIC X(2).            00021419
           05 PIWA2-FN1EX-SANI-REG                PIC X(5).            00021519
           05 PIWA2-FN1EX-SANI-REC                PIC X(3).            00021619
           05 PIWA2-FN1EX-POLICEDIST.                                  00021719
                15 PIWA2-FN1EX-POL-PATR-BORO-CMD PIC X(1).             00021819
                15 PIWA2-FN1EX-POL-PRECINCT       PIC X(3).            00021919
     ** NOTE:10  PIWA2-FN1EX-FIRESEC ==> FIRE DIVISION **              00022019
           05 PIWA2-FN1EX-FIRESEC                 PIC X(2).            00022119
           05 PIWA2-FN1EX-FIREBAT                 PIC X(2).            00022219
           05 PIWA2-FN1EX-FIRECO.                                      00022319
               10  PIWA2-FN1EX-FIRECO-TYPE        PIC X(1).            00022419
               10  PIWA2-FN1EX-FIRECO-NUM         PIC X(3).            00022519
           05 PIWA2-FN1EX-SPLIT-SCHOOL-FLAG       PIC X.               00022619
           05 PIWA2-FN1EX-SCHOOLDIST              PIC X(2).            00022719
           05 PIWA2-FN1EX-DYN-BLOCK               PIC X(3).            00022819
           05 PIWA2-FN1EX-POLICE-PAT-BORO         PIC X(2).            00023022
           05 PIWA2-FN1EX-FEATURE-TYPE            PIC X.               00023119
           05 PIWA2-FN1EX-SEGMENT-TYPE            PIC X.               00023219
           05 PIWA2-FN1EX-ALX                     PIC X.               00023319
           05 PIWA2-FN1EX-COINCIDENT-CNT          PIC X.               00023419
           05 FILLER                              PIC X(3).            00023519
           05 PIWA2-FN1EX-1990-CENSUSTRACT        PIC X(6).            00023619
           05 PIWA2-FN1EX-2010-CENS-TRCT          PIC X(6).            00023719
           05 PIWA2-FN1EX-2010-CENS-BLK           PIC X(4).            00023819
           05 PIWA2-FN1EX-2010-CENS-BLK-SFX       PIC X.               00023919
           05 PIWA2-FN1EX-2000-CENS-TRCT          PIC X(6).            00024019
           05 PIWA2-FN1EX-2000-CENS-BLK           PIC X(4).            00024119
           05 PIWA2-FN1EX-2000-CENS-BLK-SFX       PIC X.               00024219
           05 PIWA2-FN1EX-NTA                     PIC X(4).            00024319
           05 PIWA2-FN1EX-SANIT-SNOW-PRRTY        PIC X.               00024419
           05 PIWA2-FN1EX-SANIT-ORGANICS          PIC X(5).            00024519
           05 PIWA2-FN1EX-SANIT-BULK-PICK-UP      PIC X(5).            00024630
     ****  05 PIWA2-FN1EX-SANIT-RESERVED V16.4    PIC X(5).            00024730
           05 PIWA2-FN1EX-HURRICANE-ZONE          PIC XX.              00024829
           05 FILLER                              PIC X(11).           00024929
           05 PIWA2-FN1EX-TRUE-HNS                PIC X(11).           00025029
           05 PIWA2-FN1EX-TRUE-B7SC               PIC X(8).            00025129
           05 PIWA2-FN1EX-SEG-ID                  PIC X(7).            00025229
           05 PIWA2-FN1EX-CURVE-FLAG              PIC X(1).            00025329
           05 PIWA2-FN1EX-LGCS                    PIC X(8).            00025429
           05 PIWA2-FN1EX-BOE-PTR                 PIC X(1).            00025529
           05 PIWA2-FN1EX-AZIMUTH                 PIC X(3).            00025629
           05 PIWA2-FN1EX-ORIENT                  PIC X(1).            00025729
           05 PIWA2-FN1EX-X-LOW                   PIC X(7).            00025829
           05 PIWA2-FN1EX-Y-LOW                   PIC X(7).            00025929
           05 PIWA2-FN1EX-Z-LOW                   PIC X(7).            00026029
           05 PIWA2-FN1EX-X-HI                    PIC X(7).            00026129
           05 PIWA2-FN1EX-Y-HI                    PIC X(7).            00026229
           05 PIWA2-FN1EX-Z-HI                    PIC X(7).            00026329
           05 PIWA2-FN1EX-X-CC                    PIC X(7).            00026429
           05 PIWA2-FN1EX-Y-CC                    PIC X(7).            00026529
           05 PIWA2-FN1EX-Z-CC                    PIC X(7).            00026629
           05 PIWA2-FN1EX-RADIUS                  PIC X(7).            00026729
           05 PIWA2-FN1EX-SECANT                  PIC X(1).            00026829
           05 PIWA2-FN1EX-ANGLE-FROM              PIC X(5).            00026929
           05 PIWA2-FN1EX-ANGLE-TO                PIC X(5).            00027029
           05 PIWA2-FN1EX-NODE-FROM               PIC X(7).            00027129
           05 PIWA2-FN1EX-NODE-TO                 PIC X(7).            00027229
           05 PIWA2-FN1EX-VANITY-LION             PIC X(10).           00027329
           05 PIWA2-FN1EX-SOS                     PIC X(1).            00027429
           05 PIWA2-FN1EX-SPLIT-LOHSN             PIC X(11).           00027529
           05 PIWA2-FN1EX-TD                      PIC X(1).            00027629
           05 PIWA2-FN1EX-TR                      PIC X(10).           00027729
           05 PIWA2-FN1EX-CURVE-FRACTION          PIC X(3).            00027829
           05 PIWA2-FN1EX-ROADWAY-TYPE            PIC X(2).            00027929
           05 PIWA2-FN1EX-PHYICAL-ID              PIC X(7).            00028029
           05 PIWA2-FN1EX-GENERIC-ID              PIC X(7).            00028129
           05 PIWA2-FN1EX-NYPD-ID-FILL            PIC X(7).            00028229
           05 PIWA2-FN1EX-FDNY-ID-FILL            PIC X(7).            00028329
           05 PIWA2-FN1EX-BIKE-LANE-2             PIC X(2).            00028429
           05 PIWA2-FN1EX-BIKE-TRAFFIC-DIR        PIC X(2).            00028535
           05 FILLER                              PIC X(3).            00028633
     ****  05 FILLER              ******V17.1 **  PIC X(5).            00028833
     ****  05 FILLER              ******V16.4 **  PIC X(7).            00028933
     ****  05 PIWA2-FN1EX-BLOCKFACE-ID *V16.1 **  PIC X(7) ***         00029033
           05 PIWA2-FN1EX-STREET-STATUS           PIC X(1).            00029133
           05 PIWA2-FN1EX-STREET-WIDTH            PIC X(3).            00029233
           05 PIWA2-FN1EX-STREET-WIDTH-IRR        PIC X(1).            00029333
           05 PIWA2-FN1EX-BIKE-LANE               PIC X(1).            00029433
           05 PIWA2-FN1EX-FED-CLASS-CODE          PIC X(2).            00029533
           05 PIWA2-FN1EX-ROW-TYPE                PIC X(1).            00029633
           05 PIWA2-FN1EX-LGC-LIST-2              PIC X(10).           00029733
           05 PIWA2-FN1EX-LEGACY-SEG-ID           PIC X(7).            00029833
           05 PIWA2-FN1EX-LGC-LIST-FROM-1         PIC X(10).           00029933
           05 PIWA2-FN1EX-LGC-LIST-TO-1           PIC X(10).           00030033
           05 PIWA2-FN1EX-LGC-LIST-FROM-2         PIC X(10).           00030133
           05 PIWA2-FN1EX-LGC-LIST-TO-2           PIC X(10).           00030233
           05 PIWA2-FN1EX-NOCROSS-FLG             PIC X(1).            00030333
           05 PIWA2-FN1EX-IND-SEG-LEN             PIC X(5).            00030433
           05 PIWA2-FN1EX-NTA-NAME                PIC X(75).           00030533
           05 PIWA2-FN1EX-USPS-CITY-NAME          PIC X(25).           00030633
           05 PIWA2-FN1EX-LATITUDE                PIC X(9).            00030733
           05 PIWA2-FN1EX-LONGITUDE               PIC X(11).           00030833
           05 PIWA2-FN1EX-SEG-FROM-NODE           PIC X(7).            00030933
           05 PIWA2-FN1EX-SEG-TO-NODE             PIC X(7).            00031033
           05 PIWA2-FN1EX-SEG-FROM-XYZ            PIC X(21).           00031133
           05 PIWA2-FN1EX-SEG-TO-XYZ              PIC X(21).           00031233
           05 PIWA2-FN1EX-BLOCKFACE-ID            PIC X(10).           00031333
           05 PIWA2-FN1EX-NBR-TRAVEL-LANES        PIC X(2).            00031433
           05 PIWA2-FN1EX-NBR-PARK-LANES          PIC X(2).            00031533
           05 PIWA2-FN1EX-NBR-TOTAL-LANES         PIC X(2).            00031633
           05 PIWA2-FN1EX-STREET-WIDTH-MAX        PIC X(3).            00031733
           05 PIWA2-FN1EX-FILL500                 PIC X(252).          00031833
     ****  05 PIWA2-FN1EX-FILL500   ** V16.4 **   PIC X(255).          00031933
     ****  05 PIWA2-FN1EX-FILL500   ** V16.1 **   PIC X(271) ***       00032033
     ****  05 PIWA2-FN1EX-FILL500   ** V15.3 **   PIC X(327) ***       00032133
     ****************************************************************/ 00032233
     *                                                            ***/ 00032333
     *THE FOLLOWING FIELDS ARE AN ADDITION TO GRID1               ***/ 00032433
     ****************************************************************/ 00032533
           05 PIWA2-FN1EX-REASON-CODE             PIC X(1).            00032633
           05 PIWA2-FN1EX-REASON-CODE-QUAL        PIC X(1).            00032733
           05 PIWA2-FN1EX-WARN-CODE               PIC X(2).            00032833
           05 PIWA2-FN1EX-RETURN-CODE             PIC X(2).            00032933
           05 PIWA2-FN1EX-NUM-X-STS-LO-END        PIC X(1).            00033033
           05 PIWA2-FN1EX-LO-B7SC OCCURS 5 TIMES  PIC X(8).            00033133
           05 PIWA2-FN1EX-NUM-X-STS-HI-END        PIC X(1).            00033233
           05 PIWA2-FN1EX-HI-B7SC OCCURS 5 TIMES  PIC X(8).            00033333
           05 PIWA2-FN1EX-LO-ST-NAME OCCURS 5 TIMES PIC X(32).         00033433
           05 PIWA2-FN1EX-HI-ST-NAME OCCURS 5 TIMES PIC X(32).         00033533
           05 PIWA2-FN1EX-BOE-B7SC                PIC X(8).            00033633
           05 PIWA2-FN1EX-BOE-ST-NAME             PIC X(32).           00033733
           05 PIWA2-FN1EX-FILL600                 PIC X(52).           00033833
                                                                       00033933
     ***************************************************************   00034033
     ***   FOR: FUNCTION 1A   EXTENDED  ****************************   00034133
                                                                       00034233
          03  PIWA2-FUNCTION1AX  REDEFINES PIWA2.                      00034333
           05 PIWA2-1AX-ACCESS-KEY                PIC X(21).           00034433
           05 PIWA2-1AX-CONT-PARITY               PIC X.               00034533
           05 PIWA2-1AX-LOW-HOUSENUM              PIC X(11).           00034633
           05 PIWA2-1AX-ALTKEY-1.                                      00034733
             10 PIWA2-1AX-ALTKEY-1-BORO           PIC X.               00034833
             10 PIWA2-1AX-ALTKEY-1-TAXBLOCK       PIC X(5).            00034933
             10 PIWA2-1AX-ALTKEY-1-TAXLOT         PIC X(4).            00035033
           05 FILLER                              PIC X.               00035133
           05 PIWA2-1AX-SCC                       PIC X(1).            00035233
           05 FILLER                              PIC X.               00035333
           05 PIWA2-1AX-GENERAL-LOT-INFO.                              00035433
             10 PIWA2-1AX-RPAD-BLDG-CLASS         PIC X(2).            00035533
             10 PIWA2-1AX-CORNER-CODE             PIC X(2).            00035633
             10 PIWA2-1AX-TOT-NBR-BLDG            PIC X(4).            00035733
             10 PIWA2-1AX-NUM-OF-BLOCKFACES       PIC X(2).            00035833
             10 PIWA2-1AX-INTERIOR-FLAG           PIC X.               00035933
             10 PIWA2-1AX-VACANT-FLAG             PIC X.               00036033
             10 PIWA2-1AX-IRREG-FLAG              PIC X.               00036133
           05 PIWA2-1AX-ALT-BORO-FLAG             PIC X.               00036233
           05 PIWA2-1AX-OVERFLOW-FLAG             PIC X(1).            00036333
           05 PIWA2-1AX-STROLL-KEY                PIC X(19).           00036433
           05 FILLER-GSS                          PIC X.               00036533
           05 PIWA2-1AX-BLDG-ID-NUM               PIC X(7).            00036633
           05 PIWA2-1AX-CONDO-LOT-FLAG            PIC X.               00036733
           05 FILLER                              PIC X.               00036833
           05 PIWA2-1AX-RPAD-COND-NUM             PIC X(4).            00036933
           05 FILLER                              PIC X(7).            00037033
           05 PIWA2-1AX-CONDO-BILLING-BBL         PIC X(10).           00037133
           05 FILLER                              PIC X.               00037233
           05 PIWA2-1AX-CONDO-BILL-BBL-SCC        PIC X(1).            00037333
           05 PIWA2-1AX-CONDO-LOW-BBL             PIC X(10).           00037433
           05 FILLER                              PIC X.               00037533
           05 PIWA2-1AX-CONDO-HIGH-BBL            PIC X(10).           00037633
           05 FILLER                              PIC X.               00037733
           05 FILLER                              PIC X(15).           00037833
           05 PIWA2-1AX-CO-OP-NBR                 PIC X(4).            00037933
           05 PIWA2-1AX-SANBORN-BVOLPAGE.                              00038033
              10  PIWA2-1AX-SANBORN-BORO          PIC X(1).            00038133
              10  PIWA2-1AX-SANBORN-VOL-PAGE.                          00038233
                15  PIWA2-1AX-SANBORN-VOL-NUM     PIC X(3).            00038333
                15  PIWA2-1AX-SANBORN-PAGE-NUM    PIC X(4).            00038433
           05 PIWA2-1AX-COMMERC-DIST              PIC X(5).            00038533
           05 PIWA2-1AX-DOF-MAP-BOROUGH           PIC X.               00038633
           05 PIWA2-1AX-TAX-MAP-NBR               PIC X(4).            00038733
           05 FILLER-FOR-TAX-MAP-PAGE             PIC X(4).            00038833
           05 FILLER                              PIC X(3).            00038933
           05 PIWA2-1AX-LATITUDE                  PIC X(9).            00039033
           05 PIWA2-1AX-LONGITUDE                 PIC X(11).           00039133
           05 PIWA2-1AX-X-COORD                   PIC X(7).            00039233
           05 PIWA2-1AX-Y-COORD                   PIC X(7).            00039333
           05 PIWA2-1AX-BID                       PIC X(6).            00039433
           05 PIWA2-1AX-TPAD-BIN-ST               PIC X.               00039533
           05 PIWA2-1AX-TPAD-NEW-BIN              PIC X(7).            00039633
           05 PIWA2-1AX-TPAD-NEW-BIN-ST           PIC X.               00039733
           05 PIWA2-1AX-TPAD-CONFLICT             PIC X.               00039833
           05 FILLER                              PIC X(9).            00039933
           05 FILLER-GSS                          PIC X(8).            00040033
           05 PIWA2-1AX-REASON-CODE               PIC X(1).            00040133
           05 PIWA2-1AX-REASON-CODE-QUAL          PIC X(1).            00040233
           05 PIWA2-1AX-WARN-CODE                 PIC X(2).            00040333
           05 PIWA2-1AX-RETURN-CODE               PIC X(2).            00040433
           05 PIWA2-1AX-FILLER                    PIC X(108).          00040533
           05 PIWA2-1AX-NUM-OF-ADDR               PIC X(4).            00040633
           05 PIWA2-1AX-ADDR-LIST                OCCURS 21 TIMES.      00040733
             10  PIWA2-1AX-LIST-LOW-HOUSENUM      PIC X(16).           00040833
             10  PIWA2-1AX-LIST-HI-HOUSENUM       PIC X(16).           00040933
             10  PIWA2-1AX-LIST-BORO              PIC X.               00041033
             10  PIWA2-1AX-LIST-5SC               PIC X(5).            00041133
             10  PIWA2-1AX-LIST-LGC               PIC X(2).            00041233
             10  PIWA2-1AX-LIST-BIN               PIC X(7).            00041333
             10  PIWA2-1AX-LIST-SOS               PIC X.               00041433
             10  PIWA2-1AX-ADDR-TYPE              PIC X.               00041533
             10  PIWA2-1AX-TPAD-STATUS            PIC X.               00041633
             10  PIWA2-1AX-ST-NAME                PIC X(32).           00041733
             10  FILLER                           PIC X(34).           00041833
                                                                       00041933
     ***************************************************************   00042033
     ***   FOR: FUNCTION 1B             ****************************   00042133
                                                                       00042233
          03  PIWA2-FUNCTION1B   REDEFINES PIWA2.                      00042333
                                                                       00042433
           05 PIWA2-1B-1-ACCESS-KEY               PIC X(21).           00042533
           05 PIWA2-1B-1-CONT-PARITY              PIC X.               00042633
           05 PIWA2-1B-1-LOW-HOUSENUM-SORT        PIC X(11).           00042733
           05 PIWA2-1B-1-HI-HOUSENUM-SORT         PIC X(11).           00042833
           05 PIWA2-1B-1-PREFERRED-LGC            PIC X(2).            00042933
           05 PIWA2-1B-1-NUM-X-ST-LOW-END         PIC X.               00043033
           05 PIWA2-1B-1-LOW-B5SC                 PIC X(6)             00043133
                                                   OCCURS 5 TIMES.     00043233
           05 PIWA2-1B-1-NUM-X-ST-HI-END          PIC X.               00043333
           05 PIWA2-1B-1-HI-B5SC                  PIC X(6)             00043433
                                                   OCCURS 5 TIMES.     00043533
           05 PIWA2-1B-1-LIONKEY.                                      00043633
               10  PIWA2-1B-1-LION-BORO           PIC X.               00043733
               10  PIWA2-1B-1-LIONFACECODE        PIC X(4).            00043833
               10  PIWA2-1B-1-LIONSEQ             PIC X(5).            00043933
           05 PIWA2-1B-1-SPECIAL-ADDR-FLAG        PIC X(1).            00044033
           05 PIWA2-1B-1-SIDE-OF-STR              PIC X.               00044133
           05 PIWA2-1B-1-SEGMENTLENGTH            PIC X(5).            00044233
           05 PIWA2-1B-1-XCOORD                   PIC X(7).            00044333
           05 PIWA2-1B-1-YCOORD                   PIC X(7).            00044433
           05 FILLER-GSS                          PIC X(8).            00044533
           05 PIWA2-1B-1-MARBLE-RIKER-FLAG        PIC X(1).            00044633
           05 PIWA2-1B-1-SLA                      PIC X.               00044733
           05 PIWA2-1B-1-COMDIST.                                      00044833
               10  PIWA2-1B-1-COMDIST-BORO        PIC X(1).            00044933
               10  PIWA2-1B-1-COMDIST-NUMBER      PIC X(2).            00045033
           05 PIWA2-1B-1-ZIP                      PIC X(5).            00045133
                                                                       00045233
           05 PIWA2-1B-1-ELECTDIST                PIC X(3).            00045333
           05 PIWA2-1B-1-ASSEMDIST                PIC X(2).            00045433
           05 PIWA2-1B-1-SPLIT-ED-FLAG            PIC X(1).            00045533
           05 PIWA2-1B-1-CONGDIST                 PIC X(2).            00045633
           05 PIWA2-1B-1-SENATEDIST               PIC X(2).            00045733
           05 PIWA2-1B-1-COURTDIST                PIC X(2).            00045833
           05 PIWA2-1B-1-COUNCILDIST              PIC X(2).            00045933
                                                                       00046033
           05 PIWA2-1B-1-HCD                      PIC X(2).            00046133
           05 PIWA2-1B-1-HEALTHAREA               PIC X(4).            00046233
           05 PIWA2-1B-1-SANIDIST.                                     00046333
               10  PIWA2-1B-1-SANIDIST-BORO       PIC X(1).            00046433
               10  PIWA2-1B-1-SANIDIST-NUMBER     PIC X(2).            00046533
           05 PIWA2-1B-1-SANITATION-SUBSEC        PIC X(2).            00046633
           05 PIWA2-1B-1-SANI-REG                 PIC X(5).            00046733
           05 PIWA2-1B-1-SANI-REC                 PIC X(3).            00046833
           05 PIWA2-1B-1-POLICEDIST.                                   00046933
                15 PIWA2-1B-1-POL-PATR-BORO-CMD PIC X(1).              00047033
                15 PIWA2-1B-1-POL-PRECINCT        PIC X(3).            00047133
     ** NOTE:10  PIWA2-1B-1-FIRESEC ==> FIRE DIVISION **               00047233
           05 PIWA2-1B-1-FIRESEC                  PIC X(2).            00047333
           05 PIWA2-1B-1-FIREBAT                  PIC X(2).            00047433
           05 PIWA2-1B-1-FIRECO.                                       00047533
               10  PIWA2-1B-1-FIRECO-TYPE         PIC X(1).            00047633
               10  PIWA2-1B-1-FIRECO-NUM          PIC X(3).            00047733
           05 PIWA2-1B-1-SPLIT-SCHOOL-FLAG        PIC X.               00047833
           05 PIWA2-1B-1-SCHOOLDIST               PIC X(2).            00047933
           05 PIWA2-1B-1-DYN-BLOCK                PIC X(3).            00048033
           05 PIWA2-1B-1-POLICE-PAT-BORO          PIC X(2).            00048133
           05 PIWA2-1B-1-FEATURE-TYPE             PIC X.               00048233
           05 PIWA2-1B-1-SEGMENT-TYPE             PIC X.               00048333
           05 PIWA2-1B-1-ALX                      PIC X.               00048433
           05 PIWA2-1B-1-COINCIDENT-CNT           PIC X.               00048533
           05 FILLER                              PIC X(3).            00048633
           05 PIWA2-1B-1-1990-CENSUSTRACT         PIC X(6).            00048733
           05 PIWA2-1B-1-2010-CENS-TRCT           PIC X(6).            00048833
           05 PIWA2-1B-1-2010-CENS-BLK            PIC X(4).            00048933
           05 PIWA2-1B-1-2010-CENS-BLK-SFX        PIC X.               00049033
           05 PIWA2-1B-1-2000-CENS-TRCT           PIC X(6).            00049133
           05 PIWA2-1B-1-2000-CENS-BLK            PIC X(4).            00049233
           05 PIWA2-1B-1-2000-CENS-BLK-SFX        PIC X.               00049333
           05 PIWA2-1B-1-NTA                      PIC X(4).            00049433
           05 PIWA2-1B-1-SANIT-SNOW-PRRTY         PIC X.               00049533
           05 PIWA2-1B-1-SANIT-ORGANICS           PIC X(5).            00049633
           05 PIWA2-1B-1-SANIT-BULK-PICK-UP       PIC X(5).            00049733
     ****  05 PIWA2-1B-1-SANIT-RESERVED V16.4     PIC X(5).            00049833
           05 PIWA2-1B-1-HURRICANE-ZONE           PIC XX.              00049933
           05 FILLER                              PIC X(11).           00050033
           05 PIWA2-1B-1-TRUE-HNS                 PIC X(11).           00050133
           05 PIWA2-1B-1-TRUE-B7SC                PIC X(8).            00050233
           05 PIWA2-1B-1-SEG-ID                   PIC X(7).            00050333
           05 PIWA2-1B-1-CURVE-FLAG               PIC X(1).            00050433
           05 PIWA2-1B-1-LGCS                     PIC X(8).            00050533
           05 PIWA2-1B-1-BOE-PTR                  PIC X(1).            00050633
           05 PIWA2-1B-1-AZIMUTH                  PIC X(3).            00050733
           05 PIWA2-1B-1-ORIENT                   PIC X(1).            00050833
           05 PIWA2-1B-1-X-LOW                    PIC X(7).            00050933
           05 PIWA2-1B-1-Y-LOW                    PIC X(7).            00051033
           05 PIWA2-1B-1-Z-LOW                    PIC X(7).            00051133
           05 PIWA2-1B-1-X-HI                     PIC X(7).            00051233
           05 PIWA2-1B-1-Y-HI                     PIC X(7).            00051333
           05 PIWA2-1B-1-Z-HI                     PIC X(7).            00051433
           05 PIWA2-1B-1-X-CC                     PIC X(7).            00051533
           05 PIWA2-1B-1-Y-CC                     PIC X(7).            00051633
           05 PIWA2-1B-1-Z-CC                     PIC X(7).            00051733
           05 PIWA2-1B-1-RADIUS                   PIC X(7).            00051833
           05 PIWA2-1B-1-SECANT                   PIC X(1).            00051933
           05 PIWA2-1B-1-ANGLE-FROM               PIC X(5).            00052033
           05 PIWA2-1B-1-ANGLE-TO                 PIC X(5).            00052133
           05 PIWA2-1B-1-NODE-FROM                PIC X(7).            00052233
           05 PIWA2-1B-1-NODE-TO                  PIC X(7).            00052333
           05 PIWA2-1B-1-VANITY-LION              PIC X(10).           00052433
           05 PIWA2-1B-1-SOS                      PIC X(1).            00052533
           05 PIWA2-1B-1-SPLIT-LOHSN              PIC X(11).           00052633
           05 PIWA2-1B-1-TD                       PIC X(1).            00052733
           05 PIWA2-1B-1-TR                       PIC X(10).           00052833
           05 PIWA2-1B-1-CURVE-FRACTION           PIC X(3).            00052933
           05 PIWA2-1B-1-ROADWAY-TYPE             PIC X(2).            00053033
           05 PIWA2-1B-1-PHYICAL-ID               PIC X(7).            00053133
           05 PIWA2-1B-1-GENERIC-ID               PIC X(7).            00053233
           05 PIWA2-1B-1-NYPD-ID-FILL             PIC X(7).            00053333
           05 PIWA2-1B-1-FDNY-ID-FILL             PIC X(7).            00053433
           05 PIWA2-1B-1-BIKE-LANE-2              PIC X(2).            00053533
           05 PIWA2-1B-1-BIKE-TRAFFIC-DIR         PIC X(2).            00053633
           05 FILLER                              PIC X(3).            00053733
     ****  05 FILLER                  ** V17.1 ** PIC X(5) ***         00053833
     ****  05 FILLER                  ** V16.4 ** PIC X(7) ***         00053933
     ****  05 PIWA2-FN-1-BLOCKFACE-ID ** V16.1 ** PIC X(7) ***         00054033
           05 PIWA2-1B-1-STREET-STATUS            PIC X(1).            00054133
           05 PIWA2-1B-1-STREET-WIDTH             PIC X(3).            00054233
           05 PIWA2-1B-1-STREET-WIDTH-IRR         PIC X(1).            00054333
           05 PIWA2-1B-1-BIKE-LANE                PIC X(1).            00054433
           05 PIWA2-1B-1-FED-CLASS-CODE           PIC X(2).            00054533
           05 PIWA2-1B-1-ROW-TYPE                 PIC X(1).            00054633
           05 PIWA2-1B-1-LGC-LIST-2               PIC X(10).           00054733
           05 PIWA2-1B-1-LEGACY-SEG-ID            PIC X(7).            00054833
           05 PIWA2-1B-1-LGC-LIST-FROM-1          PIC X(10).           00054933
           05 PIWA2-1B-1-LGC-LIST-TO-1            PIC X(10).           00055033
           05 PIWA2-1B-1-LGC-LIST-FROM-2          PIC X(10).           00055133
           05 PIWA2-1B-1-LGC-LIST-TO-2            PIC X(10).           00055233
           05 PIWA2-1B-1-NOCROSS-FLG              PIC X(1).            00055333
           05 PIWA2-1B-1-IND-SEG-LEN              PIC X(5).            00055433
           05 PIWA2-1B-1-NTA-NAME                 PIC X(75).           00055533
           05 PIWA2-1B-1-USPS-CITY-NAME           PIC X(25).           00055633
           05 PIWA2-1B-1-LATITUDE                 PIC X(9).            00055733
           05 PIWA2-1B-1-LONGITUDE                PIC X(11).           00055833
           05 PIWA2-1B-1-SEG-FROM-NODE            PIC X(7).            00055933
           05 PIWA2-1B-1-SEG-TO-NODE              PIC X(7).            00056033
           05 PIWA2-1B-1-SEG-FROM-XYZ             PIC X(21).           00056133
           05 PIWA2-1B-1-SEG-TO-XYZ               PIC X(21).           00056233
           05 PIWA2-1B-1-BLOCKFACE-ID             PIC X(10).           00056333
           05 PIWA2-1B-1-NBR-TRAVEL-LANES         PIC X(2).            00056433
           05 PIWA2-1B-1-NBR-PARK-LANES           PIC X(2).            00056533
           05 PIWA2-1B-1-NBR-TOTAL-LANES          PIC X(2).            00056633
           05 PIWA2-1B-1-STREET-WIDTH-MAX         PIC X(3).            00056733
           05 PIWA2-1B-1-FILL500                  PIC X(252).          00056833
     ****  05 PIWA2-1B-1-FILL500   ** V16.4 **    PIC X(255).          00056933
     ****  05 PIWA2-1B-1-FILL500   ** V16.1 **    PIC X(271) **        00057033
     ****  05 PIWA2-1B-1-FILL500   ** V15,3 **    PIC X(327) **        00057133
     ****************************************************************/ 00057233
     *                                                            ***/ 00057333
     *THE FOLLOWING FIELDS ARE AN ADDITION TO 1/1E                ***/ 00057433
     ****************************************************************/ 00057533
           05 PIWA2-1B-1-REASON-CODE              PIC X(1).            00057633
           05 PIWA2-1B-1-REASON-CODE-QUAL         PIC X(1).            00057733
           05 PIWA2-1B-1-WARN-CODE                PIC X(2).            00057833
           05 PIWA2-1B-1-RETURN-CODE              PIC X(2).            00057933
           05 PIWA2-1B-1-NUM-X-STS-LO-END         PIC X(1).            00058033
           05 PIWA2-1B-1-LO-B7SC OCCURS 5 TIMES   PIC X(8).            00058133
           05 PIWA2-1B-1-NUM-X-STS-HI-END         PIC X(1).            00058233
           05 PIWA2-1B-1-HI-B7SC OCCURS 5 TIMES   PIC X(8).            00058333
           05 PIWA2-1B-1-LO-ST-NAME OCCURS 5 TIMES PIC X(32).          00058433
           05 PIWA2-1B-1-HI-ST-NAME OCCURS 5 TIMES PIC X(32).          00058533
           05 PIWA2-1B-1-BOE-B7SC                 PIC X(8).            00058633
           05 PIWA2-1B-1-BOE-ST-NAME              PIC X(32).           00058733
           05 PIWA2-1B-1-FILL600                  PIC X(52).           00058833
                                                                       00058933
           05 PIWA2-1B-1A-ACCESS-KEY              PIC X(21).           00059033
           05 PIWA2-1B-1A-CONT-PARITY             PIC X.               00059133
           05 PIWA2-1B-1A-LOW-HOUSENUM            PIC X(11).           00059233
           05 PIWA2-1B-1A-ALTKEY-1.                                    00059333
             10 PIWA2-1B-1A-ALTKEY-1-BORO         PIC X.               00059433
             10 PIWA2-1B-1A-ALTKEY-1-TAXBLOCK     PIC X(5).            00059533
             10 PIWA2-1B-1A-ALTKEY-1-TAXLOT       PIC X(4).            00059633
           05 FILLER                              PIC X.               00059733
           05 PIWA2-1B-1A-SCC                     PIC X(1).            00059833
           05 FILLER                              PIC X.               00059933
           05 PIWA2-1B-1A-GENERAL-LOT-INFO.                            00060033
             10 PIWA2-1B-1A-RPAD-BLDG-CLASS       PIC X(2).            00060133
             10 PIWA2-1B-1A-CORNER-CODE           PIC X(2).            00060233
             10 PIWA2-1B-1A-TOT-NBR-BLDG          PIC X(4).            00060333
             10 PIWA2-1B-1A-NUM-OF-BLOCKFACES     PIC X(2).            00060433
             10 PIWA2-1B-1A-INTERIOR-FLAG         PIC X.               00060533
             10 PIWA2-1B-1A-VACANT-FLAG           PIC X.               00060633
             10 PIWA2-1B-1A-IRREG-FLAG            PIC X.               00060733
           05 PIWA2-1B-1A-ALT-BORO-FLAG           PIC X.               00060833
           05 PIWA2-1B-1A-OVERFLOW-FLAG           PIC X(1).            00060933
           05 PIWA2-1B-1A-STROLL-KEY              PIC X(19).           00061033
           05 FILLER-GSS                          PIC X.               00061133
           05 PIWA2-1B-1A-BLDG-ID-NUM             PIC X(7).            00061233
           05 PIWA2-1B-1A-CONDO-LOT-FLAG          PIC X.               00061333
           05 FILLER                              PIC X.               00061433
           05 PIWA2-1B-1A-RPAD-COND-NUM           PIC X(4).            00061533
           05 FILLER                              PIC X(7).            00061633
           05 PIWA2-1B-1A-CONDO-BILLING-BBL       PIC X(10).           00061733
           05 FILLER                              PIC X.               00061833
           05 PIWA2-1B-1A-CONDO-BILL-BBL-SCC      PIC X(1).            00061933
           05 PIWA2-1B-1A-CONDO-LOW-BBL           PIC X(10).           00062033
           05 FILLER                              PIC X.               00062133
           05 PIWA2-1B-1A-CONDO-HIGH-BBL          PIC X(10).           00062233
           05 FILLER                              PIC X.               00062333
           05 FILLER                              PIC X(15).           00062433
           05 PIWA2-1B-1A-CO-OP-NBR               PIC X(4).            00062533
           05 PIWA2-1B-1A-SANBORN-BVOLPAGE.                            00062633
              10  PIWA2-1B-1A-SANBORN-BORO        PIC X(1).            00062733
              10  PIWA2-1B-1A-SANBORN-VOL-PAGE.                        00062833
                15  PIWA2-1B-1A-SANBORN-VOL-NUM   PIC X(3).            00062933
                15  PIWA2-1B-1A-SANBORN-PAGE-NUM  PIC X(4).            00063033
           05 PIWA2-1B-1A-COMMERC-DIST            PIC X(5).            00063133
           05 PIWA2-1B-1A-DOF-MAP-BOROUGH         PIC X.               00063233
           05 PIWA2-1B-1A-TAX-MAP-NBR             PIC X(4).            00063333
           05 FILLER-FOR-TAX-MAP-PAGE             PIC X(4).            00063433
           05 FILLER                              PIC X(3).            00063533
           05 PIWA2-1B-1A-LATITUDE                PIC X(9).            00063633
           05 PIWA2-1B-1A-LONGITUDE               PIC X(11).           00063733
           05 PIWA2-1B-1A-X-COORD                 PIC X(7).            00063833
           05 PIWA2-1B-1A-Y-COORD                 PIC X(7).            00063933
           05 PIWA2-1B-1A-BID                     PIC X(6).            00064033
           05 PIWA2-1B-1A-TPAD-BIN-ST             PIC X.               00064133
           05 PIWA2-1B-1A-TPAD-NEW-BIN            PIC X(7).            00064233
           05 PIWA2-1B-1A-TPAD-NEW-BIN-ST         PIC X.               00064333
           05 PIWA2-1B-1A-TPAD-CONFLICT           PIC X.               00064433
           05 FILLER                              PIC X(9).            00064533
           05 FILLER-GSS                          PIC X(8).            00064633
           05 PIWA2-1B-1A-REASON-CODE             PIC X(1).            00064733
           05 PIWA2-1B-1A-REASON-CODE-QUAL        PIC X(1).            00064833
           05 PIWA2-1B-1A-WARN-CODE               PIC X(2).            00064933
           05 PIWA2-1B-1A-RETURN-CODE             PIC X(2).            00065033
           05 FILLER                              PIC X(108).          00065133
           05 PIWA2-1B-1A-NUM-OF-ADDR             PIC X(4).            00065233
           05 PIWA2-1B-1A-ADDR-LIST              OCCURS 21 TIMES.      00065333
             10  PIWA2-1B-1A-LIST-LOW-HOUSENUM    PIC X(16).           00065433
             10  PIWA2-1B-1A-LIST-HI-HOUSENUM     PIC X(16).           00065533
             10  PIWA2-1B-1A-LIST-BORO            PIC X.               00065633
             10  PIWA2-1B-1A-LIST-5SC             PIC X(5).            00065733
             10  PIWA2-1B-1A-LIST-LGC             PIC X(2).            00065833
             10  PIWA2-1B-1A-LIST-BIN             PIC X(7).            00065933
             10  PIWA2-1B-1A-LIST-SOS             PIC X.               00066033
             10  PIWA2-1B-1A-ADDR-TYPE            PIC X.               00066133
             10  PIWA2-1B-1A-TPAD-STATUS          PIC X.               00066233
             10  PIWA2-1B-1A-ST-NAME              PIC X(32).           00066333
             10  FILLER                           PIC X(34).           00067028
                                                                       00070010
    

## <span id="appendix14.6"><center>P2COB3S COPY File</center></span>

    ******************************************************************  00000100
    ***  THIS IS THE COBOL STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM **  00000200
    ***  INDEPENDENT WORK AREA 2 FOR FUNCTION 3S.                   **  00000300
    ***  COPY FILE - P2COB3S.                         09/17/97      **  00000400
    ******************************************************************  00000500
          05  PIWA2-3S-ACCESS-KEY.                                     00000600
             10 FILLER-GSS                       PIC X(2).             00000700
             10 PIWA2-3S-PORS-STNAME-IND         PIC X.                00000800
             10 PIWA2-3S-BORO                    PIC X.                00000900
             10 PIWA2-3S-5SC                     PIC X(5).             00001000
             10 PIWA2-3S-LGC                     PIC X(2).             00001100
             10 FILLER                           PIC X(10).            00001200
          05  PIWA2-3S-NUM-OF-INTERSECTS         PIC X(3).             00001300
          05  PIWA2-3S-LIST-OFINTERSECTS         OCCURS 350 TIMES.     00001400
             10 PIWA2-3S-MARBLE-RIKERS-FLAG      PIC X.                00001500
             10 PIWA2-3S-DISTANCE                PIC X(5).             00001600
             10 PIWA2-3S-GAP-FLAG                PIC X.                00001700
             10 FILLER                           PIC X(7).             00001800
             10 PIWA2-3S-NUM-OF-STR              PIC X.                00001900
             10 PIWA2-3S-B7SC                    PIC X(8)              00002000
                                                 OCCURS 5 TIMES.       00002100

    
## <span id="appendix14.7"><center>P2COBAP COPY File</center></span>

    *****************************************************************  00010006
    **  MARCH   2015 YNL                - COPYLIB AP / APX    V15.2**  00020028
    **  THIS IS THE COBOL STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM **  00030006
    **  INDEPENDENT WORK AREA 2 FOR FUNCTION: AP.                  **  00040028
    *****************************************************************  00050006
    *****************************************************************  00060006
                                                                       00070006
          03  PIWA2                               PIC X(2800).         00080024
                                                                       00090006
     ***************************************************************   00100023
     ***   FOR: FUNCTION AP             ******** ADDAP  V15.2 ******   00110024
                                                                       00120023
          03  PIWA2-FUNCTIONAP   REDEFINES PIWA2.                      00130024
           05 PIWA2-AP-ACCESS-KEY                 PIC X(21).           00140024
           05 PIWA2-AP-CONT-PARITY                PIC X.               00150024
           05 PIWA2-AP-LOW-HOUSENUM               PIC X(11).           00160024
           05 PIWA2-AP-ALTKEY-1.                                       00170024
             10 PIWA2-AP-ALTKEY-1-BORO            PIC X.               00180024
             10 PIWA2-AP-ALTKEY-1-TAXBLOCK        PIC X(5).            00190024
             10 PIWA2-AP-ALTKEY-1-TAXLOT          PIC X(4).            00200024
           05 FILLER                              PIC X(7).            00210025
           05 PIWA2-AP-TOT-NBR-BLDG               PIC X(4).            00220024
           05 FILLER                              PIC X(26).           00230023
           05 FILLER-GSS                          PIC X.               00240023
           05 PIWA2-AP-BLDG-ID-NUM                PIC X(7).            00250024
           05 PIWA2-AP-CONDO-LOT-FLAG             PIC X.               00260024
           05 FILLER                              PIC X.               00270023
           05 PIWA2-AP-RPAD-COND-NUM              PIC X(4).            00280024
           05 FILLER                              PIC X(7).            00290023
           05 PIWA2-AP-CONDO-BILLING-BBL          PIC X(10).           00300024
           05 FILLER                              PIC X(2).            00310025
           05 PIWA2-AP-CONDO-LOW-BBL              PIC X(10).           00320024
           05 FILLER                              PIC X.               00330023
           05 PIWA2-AP-CONDO-HIGH-BBL             PIC X(10).           00340024
           05 FILLER                              PIC X(16).           00350025
           05 PIWA2-AP-CO-OP-NBR                  PIC X(4).            00360024
           05 FILLER                              PIC X(22).           00370031
           05 PIWA2-AP-RESERVED                   PIC X(3).            00380031
           05 PIWA2-AP-LATITUDE                   PIC X(9).            00400024
           05 PIWA2-AP-LONGITUDE                  PIC X(11).           00410024
           05 PIWA2-AP-X-COORD                    PIC X(7).            00420024
           05 PIWA2-AP-Y-COORD                    PIC X(7).            00430024
           05 FILLER                              PIC X(16).           00440029
           05 PIWA2-AP-AP-ID                      PIC X(9).            00450029
           05 FILLER-GSS                          PIC X(8).            00460023
           05 PIWA2-AP-NUM-OF-ADDR                PIC X(4).            00470024
           05 PIWA2-AP-ADDR-LIST                 OCCURS 21 TIMES.      00480024
             10  PIWA2-AP-LIST-LOW-HOUSENUM       PIC X(16).           00490024
             10  PIWA2-AP-LIST-HI-HOUSENUM        PIC X(16).           00500024
             10  PIWA2-AP-LIST-BORO               PIC X.               00510024
             10  PIWA2-AP-LIST-5SC                PIC X(5).            00520024
             10  PIWA2-AP-LIST-LGC                PIC X(2).            00530024
             10  PIWA2-AP-LIST-BIN                PIC X(7).            00540024
             10  PIWA2-AP-LIST-SOS                PIC X.               00550024
             10  PIWA2-AP-ADDR-TYPE               PIC X.               00560024
             10  FILLER                           PIC X(4).            00570024
                                                                       00580024
     ***************************************************************   00590024
     ***   FOR: FUNCTION AP EXTENDED  ******** ADDAP  V15.2 ********   00600026
                                                                       00610024
          03  PIWA2-FUNCTIONAPX  REDEFINES PIWA2.                      00620024
           05 PIWA2-APX-ACCESS-KEY                PIC X(21).           00630024
           05 PIWA2-APX-CONT-PARITY               PIC X.               00640024
           05 PIWA2-APX-LOW-HOUSENUM              PIC X(11).           00650024
           05 PIWA2-APX-ALTKEY-1.                                      00660024
             10 PIWA2-APX-ALTKEY-1-BORO           PIC X.               00670024
             10 PIWA2-APX-ALTKEY-1-TAXBLOCK       PIC X(5).            00680024
             10 PIWA2-APX-ALTKEY-1-TAXLOT         PIC X(4).            00690024
           05 FILLER                              PIC X(7).            00700025
           05 PIWA2-APX-TOT-NBR-BLDG              PIC X(4).            00710024
           05 FILLER                              PIC X(26).           00720024
           05 FILLER-GSS                          PIC X.               00730024
           05 PIWA2-APX-BLDG-ID-NUM               PIC X(7).            00740024
           05 PIWA2-APX-CONDO-LOT-FLAG            PIC X.               00750024
           05 FILLER                              PIC X.               00760024
           05 PIWA2-APX-RPAD-COND-NUM             PIC X(4).            00770024
           05 FILLER                              PIC X(7).            00780024
           05 PIWA2-APX-CONDO-BILLING-BBL         PIC X(10).           00790024
           05 FILLER                              PIC X(2).            00800025
           05 PIWA2-APX-CONDO-LOW-BBL             PIC X(10).           00810024
           05 FILLER                              PIC X.               00820024
           05 PIWA2-APX-CONDO-HIGH-BBL            PIC X(10).           00830024
           05 FILLER                              PIC X(16).           00840025
           05 PIWA2-APX-CO-OP-NBR                 PIC X(4).            00850024
           05 FILLER                              PIC X(18).           00860024
           05 FILLER-FOR-TAX-MAP-PAGE             PIC X(4).            00870024
           05 FILLER                              PIC X(3).            00880024
           05 PIWA2-APX-LATITUDE                  PIC X(9).            00890024
           05 PIWA2-APX-LONGITUDE                 PIC X(11).           00900024
           05 PIWA2-APX-X-COORD                   PIC X(7).            00910024
           05 PIWA2-APX-Y-COORD                   PIC X(7).            00920024
           05 FILLER                              PIC X(16).           00930029
           05 PIWA2-APX-AP-ID                     PIC X(9).            00940029
           05 FILLER-GSS                          PIC X(8).            00950024
           05 PIWA2-APX-REASON-CODE               PIC X(1).            00960024
           05 PIWA2-APX-REASON-CODE-QUAL          PIC X(1).            00970024
           05 PIWA2-APX-WARN-CODE                 PIC X(2).            00980024
           05 PIWA2-APX-RETURN-CODE               PIC X(2).            00990024
           05 PIWA2-APX-FILLER                    PIC X(108).          01000024
           05 PIWA2-APX-NUM-OF-ADDR               PIC X(4).            01010024
           05 PIWA2-APX-ADDR-LIST                OCCURS 21 TIMES.      01020024
             10  PIWA2-APX-LIST-LOW-HOUSENUM      PIC X(16).           01030024
             10  PIWA2-APX-LIST-HI-HOUSENUM       PIC X(16).           01040024
             10  PIWA2-APX-LIST-BORO              PIC X.               01050024
             10  PIWA2-APX-LIST-5SC               PIC X(5).            01060024
             10  PIWA2-APX-LIST-LGC               PIC X(2).            01070024
             10  PIWA2-APX-LIST-BIN               PIC X(7).            01080024
             10  PIWA2-APX-LIST-SOS               PIC X.               01090024
             10  PIWA2-APX-ADDR-TYPE              PIC X.               01100024
             10  FILLER                           PIC X.               01110024
             10  PIWA2-APX-ST-NAME                PIC X(32).           01120024
             10  FILLER                           PIC X(34).           01130024
                                                                       01140024

## <span id="appendix14.8"><center>ASSEMBLER COPY Files (COW)</center> </span>


    */********************************************************************/ 00010000
    */*****  THIS IS GEOSUPPORT INFORMATION SYSTEM COPY FILE P1BAL,    ***/ 00020000
    */*****  CONTAINING THE Platform Independent LAYOUT OF WORK AREA 1 ***/ 00030000
    */********************************************************************/ 00040000
    */*****        Last Updated:  August 2016  - Unit added by meb     ***/ 00040136
    */*****        Last Updated:  December 2013                        ***/ 00040336
    */********************************************************************/ 00041014
    P1BAL    DS   0H                                                        00050000
    */****************************                                          00060000
    */*****  INPUT FIELDS  *******                                          00070000
    */****************************                                          00080000
    P1IFUNC  DS   0CL2      FUNCTION CODE                                   00090000
    P1IFUNC1 DS    CL1      FUNCTION CODE, BYTE 1                           00100000
    P1IFUNC2 DS    CL1      FUNCTION CODE, BYTE 2                           00110000
             SPACE                                                          00120000
    P1IHSE#  DS    CL16      UNFORMATED HSNUM FOR FUNCTION: 1; 1A; 1E.      00130001
    P1IHSE#S DS    CL11      HOUSE NUMBER (SORT FORMAT)                     00140005
    *                        The Following two fields are for Fn 5          00150001
    P1ILHS#  DS    CL16      UNFORMATED HSNUM                               00160001
    P1ILHS#S DS    CL11      HOUSE NUMBER (SORT FORMAT)                     00170005
             SPACE                                                          00180001
    P1IBCD1  DS   0CL11       11 Digit Street Code for Street one             00190000
    P1IBORO1 DS    CL1      BORO CODE  (1=MN;2=BX;3=BK;4=QN;5=SI)           00200000
    P1ICDE1  DS    CL10      STREET CODE FOR STREET ONE                     00210000
    P1ISTRT1 DS    CL32      STREET NAME 1                                  00220000
             SPACE                                                          00230000
    P1IBCD2  DS   0CL11     11 Digit Street Code for Street two             00240000
    P1IBORO2 DS    CL1       BORO CODE OF CROSS ST. 1                       00250000
    P1ICDE2  DS    CL10      STREET CODE FOR STREET TWO                     00260000
    P1ISTRT2 DS    CL32      STREET NAME 2                                  00270000
             SPACE                                                          00280000
    P1IBCD3  DS   0CL11     11 Digit Street Code for Street Three           00290001
    P1IBORO3 DS    CL1       BORO CODE OF CROSS ST. 2                       00300000
    P1ICDE3  DS    CL10      STREET CODE FOR STREET THREE                   00310000
    P1ISTRT3 DS    CL32      STREET NAME 3                                  00320000
             SPACE                                                          00330000
    P1IBBL   DS   0CL10     BORO,BLOCK,LOT FOR "BL" FUNCTION                00340002
    P1IBLBOR DS    CL1      BORO FOR FUNCTION "BL"                          00350000
    P1IBLOCK DS    CL5      TAX BLOCK - FOR  FUNCTION "BL"                  00360000
    P1ILOT   DS    CL4      TAX LOT   - FOR  FUNCTION "BL"                  00370000
    P1ITLV#  DS    CL1       Tax Lot Version Number (Not Implemented)       00380000
    P1IBIN   DS    CL7       BUILDING ID NUMBER                             00390000
    P1ICOMP  DS    CL1       COMPASS DIRECTION (TYPES 2, 3C & 3S)           00400010
    P1ICOMP2 DS    CL1       COMPASS DIRECTION (TYPE 3S)                    00401010
    P1INODE  DS    CL7       Node as inpur for Fn 2                         00410032
    P1IPLIND DS    CL1       Platform Indicator                             00420003
    *                        Blank = St'd Mainframe                         00430000
    *                        P = Platform Independent                       00440000
    P1IZIPIN DS    CL5       Input Zip Code                                 00450036
    P1IUNIT  DS    CL14      Input Unit V16.4                               00451036
             DS    CL82      Filler                                         00460036
             SPACE                                                          00470000
    */****************************                                          00480000
    */*****      FLAGS     *******                                          00490000
    */****************************                                          00500000
             SPACE                                                          00510000
    P1ILONG  DS    CL1       'L' IF LONG WORKAREA 2 FOR FUNC 1A/BL          00520000
    P1IJUST  DS    CL1       HOUSE NUMBER JUSTIFICATION FLAG                00520109
    P1IHNL   DS    CL2       House Number Length                            00521009
    P1IHNBRF DS    CL1       House Number Override Flag - *, $ or blank     00522009
    P1ISNL   DS    CL2       LENGTH STREET NAME IS TO BE NORMALIZED TO      00523009
    P1ICMPCT DS    CL1       'C' IF STREET NAMES ARE TO BE COMPACTED        00524009
    P1IEXPND DS    CL1       EXPANDED FORMAT FLAG                           00530009
    P1IRBRQS DS    CL1       ROADBED REQUEST SWITCH                         00550013
    P1IRES01 DS    CL1       RESERVED FOR INTERNAL USE                      00581015
    P1ISEGAX DS    CL1       Segment Auxiliary Switch                       00582018
    P1IBRFLG DS    CL1       BROWSE FLAG P=PRIMARY ONLY F=PRINCIPAL ONLY    00583020
    P1IRSTON DS    CL1       Real Street Only Flag used with Function 3S    00584021
    P1ITPADS DS    CL1       Read TPAD for PAD Processing                   00585023
    P1IMODES DS    CL1       Mode Switch                                    00586027
    *                        X = Extended                                   00586131
    P1IWTOS  DS    CL1       WTO Switch  N=No WTO                           00586231
             DS    CL29      FILLER                                         00590031
             SPACE                                                          00600000
    */*****************************                                         00610000
    */*****  OUTPUT FIELDS  *******                                         00620000
    */*****************************                                         00630000
             SPACE                                                          00640000
    P1OBORO  DS    CL9       BORO NAME                                      00650000
    P1OHSE#  DS    CL16      HOUSE NUMBER, NORMALIZED, DISPLAY FORMAT       00660000
    P1OHSE#S DS    CL11      HOUSE NUMBER (SORT FORMAT)                     00670005
    P1OBCD1  DS   0CL11     11 Digit Street Code for Street one             00680000
    P1OBORO1 DS    CL1      BORO CODE  (1=MN;2=BX;3=BK;4=QN;5=SI)           00690000
    P1OCDE1  DS    CL10      STREET CODE FOR STREET ONE                     00700000
    P1OSTRT1 DS    CL32      STREET 1 NAME, NORMALIZED                      00710004
             SPACE                                                          00720000
    P1OBCD2  DS   0CL11     11 Digit Street Code for Street two             00730000
    P1OBORO2 DS    CL1       BORO CODE OF CROSS ST. 1                       00740000
    P1OCDE2  DS    CL10      STREET CODE FOR STREET TWO                     00750000
    P1OSTRT2 DS    CL32      STREET 2 NAME, NORMALIZED                      00760004
             SPACE                                                          00770000
    P1OBCD3  DS   0CL11     11 Digit Street Code for Street three           00780000
    P1OBORO3 DS    CL1       BORO CODE OF street 3                          00790000
    P1OCDE3  DS    CL10      STREET CODE FOR STREET THREE                   00800000
    P1OSTRT3 DS    CL32      STREET 3 NAME, NORMALIZED                      00810004
             SPACE                                                          00820000
    P1OBBL   DS   0CL11     BORO,BLOCK,LOT FOR "BL" FUNCTION                00830000
    P1OBLBOR DS    CL1      BORO FOR FUNCTION "BL"                          00840000
    P1OBLOCK DS    CL5      TAX BLOCK - FOR  FUNCTION "BL"                  00850000
    P1OLOT   DS    CL4      TAX LOT   - FOR  FUNCTION "BL"                  00860000
    P1OTLV#  DS    CL1       Tax Lot Version Number (Not Implemented)       00870000
    P1OLHSE  DS    CL16      LOW HOUSE NUMBER DISPLAY FORM                  00880006
    P1OLHSES DS    CL11      LOW HOUSE NUMBER SORT FORM                     00881006
    P1OBIN   DS    CL7       Output Building Identification Number          00882011
    P1OATTR3 DS    CL3       Attribute Bytes - Internal Use                 00883011
             SPACE                                                          00890000
    P1OREAS2 DS    CL1       2ND REASON CODE                                00891024
    P10RCQ2  DS    CL1       2ND REASON CODE TPAD QUALIFIER                 00892130
    P1OWARN2 DS    CL2       2ND WARNING RETURN CODE-NOT IMPL               00892226
    P1ORC2   DS    CL2       2ND GEOSUPPORT RETURN CODE                     00893025
    P1OERR2  DS    CL80      2ND ERROR MESSAGE                              00894024
    P1ONODE  DS    CL7       NODE NORMALIZED FOR FN 2                       00895032
    P1OUNITS DS   0CL14      UNIT IN SORT FORMAT                            00896037
    P1OUNITT DS    CL4       UNIT TYPE                                      00897036
    P1OUNITI DS    CL10      UNIT IDENTIFIER                                00898036
    P1OUNITD DS    CL14      UNIT IN DISPLAY FORMAT                         00899036
             DS    CL11      FILLER                                         00900036
    P1ONIN   DS    CL6       NAP IDENTIFICATION NUMBER                      00900107
    P1OATTRB DS    CL1       ATTRIBUTE BYTE FROM SND                        00901006
    P1OREASN DS    CL1       REASON CODE                                    00910000
    P10RCQ   DS    CL1       REASON CODE TPAD QUALIFIER                     00920030
    P1OWARNC DS    CL2       WARNING RETURN CODE                            00930025
    P1ORC    DS    CL2       GEOSUPPORT RETURN CODE                         00940025
    P1OERROR DS    CL80      ERROR MESSAGE                                  00950000
    P1O#NAME DS    CL2       NUMBER OF STREET NAMES                         00960002
    P1OBRWSE DS    CL80      10 B7SC'S                                      00970002
    P1ONAMES DS  10CL32      UP TO 10 STREET NAMES                          00980002
    P1END    EQU   *                                                        00990000
    P1LENGTH EQU   P1END-P1BAL    LENGTH OF P1BAL                           01000000   



## <span id="appendix14.9"><center>P2BAL COPY File</center></span>


    */********************************************************************/ 00010092
    */*****  THIS IS GEOSUPPORT INFORMATION SYSTEM COPY FILE P2BAL,    ***/ 00020092
    */*****  CONTAINING THE LAYOUT OF WORK AREA 2 FOR FUNCTIONS        ***/ 00030092
    */*****  1, 1E, 2, 2C, 3, 3C. PLEASE NOTE THAT FUNCTIONS 2 AND 2C  ***/ 00040092
    */*****  SHARE A SINGLE WORK AREA 2 LAYOUT.                        ***/ 00050092
    */*****  ADDED 3 EXTENDED (MODE OF X)                     6/2011   ***/ 00060092
    */*****  ADDED 2 WIDE     (2W       )                     2/2014   ***/ 00070092
    */*****  ADDED 2 byte field "Police Patrol Borough" for functions: ***/ 00080092
    */*****  1/1E; 2/2W; 3/3X-left side;3/3X-right side; 3C/3CX.       ***/ 00090092
    */*****                                                   8/2014   ***/ 00100092
    */*****  ADDED 2 fields: "Bike Lane 2" and "Street Width Maximum"  ***/ 00110092
    */*****  for functions 3X/3CX                             9/2016   ***/ 00120092
    */*****  Replaced "Saniitation Reserved" with "Sanitation Bulk     ***/ 00130092
    */*****  Pick Up" for function 1                          10/2016  ***/ 00140092
    */*****  ADDED 2 bytes field "Bike Traffic Direction" for          ***/ 00150092
    */*****  for functions 1/1E (extended),1B,3X,3CX           12/2016 ***/ 00160092
    */********************************************************************/ 00170092
    */*****        Last Date Modified -   FEBRUARY 2016                ***/ 00180092
    */********************************************************************/ 00190092
    P2BAL    DS   0H                                                        00200092
    P2ACCKEY DS    CL21          ACCESS KEY                                 00210092
    P2LAYOUT DS   0CL279                                                    00220092
    P2F1CPAR DS    CL1           CONTINUOUS PARITY INDICATOR                00230092
    P2F1LHNS DS    CL11          LOW HOUSE NUMBER                           00240092
    P2F1HHNS DS    CL11          HIGH HOUSE NUMBER                          00250092
    P2F1LGC  DS    CL2           DCP Prefered LGC (Fn 1) - BOE (Fn 1E)      00260092
    P2F1#STL DS    CL1           NUMBER OF CROSS STREETS AT LOW END         00270092
    P2F1CDEL DS    CL30          UP TO FIVEPB5SC'S FOR LOW END              00280092
    P2F1#STH DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        00290092
    P2F1CDEH DS    CL30          UP TO FIVE B5SC'S FOR HIGH END             00300092
    P2F1LBOR DS    CL1           LION BOROUGH CODE                          00310092
    P2F1FACE DS    CL4           LION FACE CODE                             00320092
    P2F1SEQ  DS    CL5           LION SEQUENCE NUMBER                       00330092
    P2F1SPAD DS    CL1           SPECIAL ADDRESS FLAG                       00340092
    P2F1SOS  DS    CL1           SIDE OF STREET INDICATOR                   00350092
    P2F1SEGL DS    CL5           SEGMENT LEGNTH                             00360092
    P2F1XCOR DS    CL7           X COORDINATE                               00370092
    P2F1YCOR DS    CL7           Y COORDINATE                               00380092
    P2F1ZCOR DS    CL7           Z Coordinate - Not Impl.                   00390092
    P2F1RES1 DS    CL1           RESERVED FOR DCP/GSS USE                   00400092
    P2F1MHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             00410092
    P2F1SLA  DS    CL1           STREET LIGHT AREA                          00420092
    P2F1CD   DS   0CL3           COMMUNITY DISTRICT                         00430092
    P2F1CDB  DS    CL1           COMMUNITY DISTRICT BORO                    00440092
    P2F1CDN  DS    CL2           COMMUNITY DISTRICT NUMBER                  00450092
    P2F1ZIP  DS    CL5           ZIP CODE                                   00460092
    P2F1EED  DS    CL3           ELECTION DISTRICT                          00470092
    P2F1EAD  DS    CL2           ASSEMBLY DISTRICT                          00480092
    P2F1ESED DS    CL1           SPLIT E.D. FLAG                            00490092
    *                 Next four fields are valid only for Fn 1E             00500092
    P2F1ECON DS    CL2           CONGRESSIONAL DISTRICT                     00510092
    P2F1ESEN DS    CL2           SENATORIAL DISTRICT                        00520092
    P2F1ECIV DS    CL2           CIVIL COURT DISTRICT                       00530092
    P2F1ECOU DS    CL2           CITY COUNCIL DISTRICT                      00540092
    *                                                                       00550092
    P2F1HCD  DS    CL2           HEALTH CODE DISTRICT                       00560092
    P2F1HA   DS    CL4           HEALTH AREA                                00570092
    P2F1SAND DS    CL3           SANITATION DISTRICT                        00580092
    P2F1SANT DS    CL2           SANITATION DEPT SUBSECTION                 00590092
    P2F1SREG DS    CL5           SANITATION REGULAR PICK-UP                 00600092
    P2F1SREC DS    CL3           SANITATION RECYCLE PICK-UP                 00610092
    P2F1POL  DS    0CL4          POLICE DISTRICT                            00620092
    P2F1PBC  DS    CL1           POLICE PATROL BORO COMMAND                 00630092
    P2F1POP  DS    CL3           POLICE PRECINCT                            00640092
    P2F1FS   DS    CL2           FIRE DIVISION                              00650092
    P2F1FB   DS    CL2           FIRE BATTALION                             00660092
    P2F1FC   DS   0CL4           FIRE COMPANY                               00670092
    P2F1FCT  DS    CL1           FIRE COMPANY TYPE                          00680092
    P2F1FCN  DS    CL3           FIRE COMPANY NUMBER                        00690092
    P2F1FILS DS    CL1           FILLER_WAS SPLIT SCHOOL DISTRICT FLAG      00700092
    P2F1SCH  DS    CL2           SCHOOL DISTRICT                            00710092
    P2F1CPB  DS    CL3           DYNAMIC  BLOCK/ATOMIC POLYGON              00720092
    P2F1PPB  DS    CL2           Police Patrol Borough                      00730092
    P2F1FEAT DS    CL1           Feature Type Code                          00740092
    P2F1STC  DS    CL1           SEGMENT TYPE CODE                          00750092
    P2F1ALX  DS    CL1           A=Segment split by Alley                   00760092
    *                            X=Cross Streets modified                   00770092
    P2F1CSC  DS    CL1           Coincident Segment Count                   00780092
             DS    CL2           Filler                                     00790092
    P2F1CTB  DS    CL1           CENSUS TRACT BOROUGH                       00800092
    P2F1CT90 DS    CL6           1990 CENSUS TRACT                          00810092
    P2F1CT10 DS    CL6           2010 CENSUS TRACT                          00820092
    P2F1BL10 DS    CL4           2010 CENSUS BLOCK                          00830092
    P2F1BLS1 DS    CL1           2010 CENSUS BLOCK SUFFIX NOT IMPLEMENTED   00840092
    P2F1T00  DS    CL6           2000 CENSUS TRACT                          00850092
    P2F1B00  DS    CL4           2000 CENSUS BLOCK                          00860092
    P2F1S00  DS    CL1           2000 CENSUS BLOCK SUFFIX                   00870092
    P2F1NTA  DS    CL4           Neighborhood Tabulation Area               00880092
    P2F1SP   DS    CL1           Sanitation Street Snow Priority            00890092
    P2F1SORG DS    CL5           Sanitation Organics Pick Up                00900092
    P2F1SBLK DS    CL5           Sanitation Bulk Pick Up                    00910092
    *        DS    CL5           Sanitation Reserved                        00920092
    P2F1HZ   DS    CL2           Hurricane Evacuation Zone                  00930092
             DS    CL11          Filler                                     00940092
    P2F1UHNS DS    CL11          Underlying HNS                             00950092
    P2F1B7SC DS    CL8           "True" Borough 7 Digit Street Code         00960092
    P2F1SEGT DS    CL7           Segment Identifier                         00970092
    P2F1CURV DS    CL1           Curve Flag                                 00980092
    P2F1END  EQU   *                                                        00990092
    P2F1LEN  EQU   P2F1END-P2BAL      Length of WA 2 for Fn 1               01000092
    *                                                                       01010092
    ********************************************************************    01020092
             ORG   P2LAYOUT      RESET LOCATION COUNTER FOR FUNCTION 2      01030092
    ********************************************************************    01040092
    *                                                                       01050092
    P2F2DUPI DS    CL1           DUPLICATE INTERSECT FLAG                   01060092
    P2F2LGC1 DS    CL2           STREET 1 PREFERRED LGC                     01070092
    P2F2LGC2 DS    CL2           STREET 2 PREFERRED LGC                     01080092
    P2F2#INT DS    CL1           NUMBER OF INTERSECTING STREETS             01090092
    P2F2CODE DS    CL30          INTERSECTING B5SC'S                        01100092
    P2F2CDUP DS    CL1           COMPASS DIRECTION FOR TWO LOWEST           01110092
    P2F2AP   DS    CL3           ATOMIC POLYGON                             01120092
             DS    CL2           FILLER                                     01130092
    P2F2NDNB DS    CL7           LION NODE NUMBER                           01140092
    P2F2XCOR DS    CL7           X COORDINATE                               01150092
    P2F2YCOR DS    CL7           Y COORDINATE                               01160092
    P2F2ZCOR DS    CL7           Z Coordinate - Not Impl.                   01170092
    P2F2SVP1 DS   0CL8           FIRST SANBORN BOROUGH, PAGE, VOLUME        01180092
    P2F2SB1  DS    CL1           FIRST SANBORN BOROUGH CODE                 01190092
    P2F2SP1  DS    CL3           FIRST SANBORN PAGE                         01200092
    P2F2SV1  DS    CL4           FIRST SANBORN VOLUME                       01210092
    P2F2SVP2 DS   0CL8           SECOND SANBORN BOROUGH, PAGE, VOLUME       01220092
    P2F2SB2  DS    CL1           SECOND SANBORN BOROUGH CODE                01230092
    P2F2SP2  DS    CL3           SECOND SANBORN PAGE                        01240092
    P2F2SV2  DS    CL4           SECOND SANBORN VOLUME                      01250092
    P2F2MHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             01260092
    P2F2SLA  DS    CL1           STREET LIGHT AREA                          01270092
    P2F2CD   DS   0CL3           COMMUNITY DISTRICT                         01280092
    P2F2CDB  DS    CL1           COMMUNITY DISTRICT BORO                    01290092
    P2F2CDN  DS    CL2           COMMUNITY DISTRICT NUMBER                  01300092
    P2F2ZIP  DS    CL5           ZIP CODE                                   01310092
    P2F2HA   DS    CL4           HEALTH AREA                                01320092
    P2F2POL  DS   0CL4           POLICE DISTRICT                            01330092
    P2F2PBC  DS    CL1           POLICE PATROL BORO COMMAND                 01340092
    P2F2POP  DS    CL3           POLICE PRECINCT                            01350092
    P2F2FS   DS    CL2           FIRE DIVISION                              01360092
    P2F2FB   DS    CL2           FIRE BATTALION                             01370092
    P2F2FC   DS   0CL4           FIRE COMPANY                               01380092
    P2F2FCT  DS    CL1           FIRE COMPANY TYPE                          01390092
    P2F2FCN  DS    CL3           FIRE COMPANY NUMBER                        01400092
    P2F2SCH  DS    CL2           SCHOOL DISTRICT                            01410092
    P2F2CT10 DS    CL6           2010 CENSUS TRACT                          01420092
    P2F2CT90 DS    CL6           1990 CENSUS TRACT                          01430092
    P2F2LEVC DS    CL10          Level Codes                                01440092
    P2F2PPB  DS    CL2           Police Patrol Borough                      01450092
    P2F2AD   DS    CL2           ASSEMBLY DISTRICT                          01460092
    P2F2CON  DS    CL2           CONGRESSIONAL DISTRICT                     01470092
    P2F2SEN  DS    CL2           SENATORIAL DISTRICT                        01480092
    P2F2CIV  DS    CL2           CIVIL COURT DISTRICT                       01490092
    P2F2COU  DS    CL2           CITY COUNCIL DISTRICT                      01500092
    P2F2RES1 DS    CL1           CD ELIGIBILITY                             01510092
    P2F2DDST DS    CL5           DUPLICATE INTERSECTION DISTANCE            01520092
    P2F2T00  DS    CL6           2000 CENSUS TRACT                          01530092
    P2F2HCD  DS    CL2           HEALTH CENTER DISTRICT                     01540092
    P2F2SD   DS    CL3           SANITATION DISTRICT                        01550092
    P2F2SANT DS    CL2           SANITATION DEPT SECTION/SUBSECTION         01560092
             DS    CL12          FILLER                                     01570092
    P2F2END  EQU   *                                                        01580092
    P2F2LEN  EQU   P2F2END-P2BAL      Length of WA 2 for Fn 2/2C            01590092
    *                                                                       01600092
    ********************************************************************    01610092
             ORG   P2LAYOUT      RESET LOCATION COUNTER FOR FUNCTION 2W     01620092
    ********************************************************************    01630092
    *                                                                       01640092
    P22WDUPI DS    CL1           DUPLICATE INTERSECT FLAG                   01650092
    P22WLGC1 DS    CL2           STREET 1 PREFERRED LGC                     01660092
    P22WLGC2 DS    CL2           STREET 2 PREFERRED LGC                     01670092
    P22W#INT DS    CL1           NUMBER OF INTERSECTING STREETS             01680092
    P22WCODE DS    CL30          INTERSECTING B5SC'S                        01690092
    P22WCDUP DS    CL1           COMPASS DIRECTION FOR TWO LOWEST           01700092
    P22WAP   DS    CL3           ATOMIC POLYGON                             01710092
             DS    CL2           FILLER                                     01720092
    P22WNDNB DS    CL7           LION NODE NUMBER                           01730092
    P22WXCOR DS    CL7           X COORDINATE                               01740092
    P22WYCOR DS    CL7           Y COORDINATE                               01750092
    P22WZCOR DS    CL7           Z Coordinate - Not Impl.                   01760092
    P22WSVP1 DS   0CL8           FIRST SANBORN BOROUGH, PAGE, VOLUME        01770092
    P22WSB1  DS    CL1           FIRST SANBORN BOROUGH CODE                 01780092
    P22WSP1  DS    CL3           FIRST SANBORN PAGE                         01790092
    P22WSV1  DS    CL4           FIRST SANBORN VOLUME                       01800092
    P22WSVP2 DS   0CL8           SECOND SANBORN BOROUGH, PAGE, VOLUME       01810092
    P22WSB2  DS    CL1           SECOND SANBORN BOROUGH CODE                01820092
    P22WSP2  DS    CL3           SECOND SANBORN PAGE                        01830092
    P22WSV2  DS    CL4           SECOND SANBORN VOLUME                      01840092
    P22WMHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             01850092
    P22WSLA  DS    CL1           STREET LIGHT AREA                          01860092
    P22WCD   DS   0CL3           COMMUNITY DISTRICT                         01870092
    P22WCDB  DS    CL1           COMMUNITY DISTRICT BORO                    01880092
    P22WCDN  DS    CL2           COMMUNITY DISTRICT NUMBER                  01890092
    P22WZIP  DS    CL5           ZIP CODE                                   01900092
    P22WHA   DS    CL4           HEALTH AREA                                01910092
    P22WPOL  DS   0CL4           POLICE DISTRICT                            01920092
    P22WPBC  DS    CL1           POLICE PATROL BORO COMMAND                 01930092
    P22WPOP  DS    CL3           POLICE PRECINCT                            01940092
    P22WFS   DS    CL2           FIRE DIVISION                              01950092
    P22WFB   DS    CL2           FIRE BATTALION                             01960092
    P22WFC   DS   0CL4           FIRE COMPANY                               01970092
    P22WFCT  DS    CL1           FIRE COMPANY TYPE                          01980092
    P22WFCN  DS    CL3           FIRE COMPANY NUMBER                        01990092
    P22WSCH  DS    CL2           SCHOOL DISTRICT                            02000092
    P22WCT10 DS    CL6           2010 CENSUS TRACT                          02010092
    P22WCT90 DS    CL6           1990 CENSUS TRACT                          02020092
    P22WLEVC DS    CL10          Level Codes                                02030092
    P22WPPB  DS    CL2           Police Patrol Borough                      02040092
    *        DS    CL2           FILLER                                     02050092
    P22WAD   DS    CL2           ASSEMBLY DISTRICT                          02060092
    P22WCON  DS    CL2           CONGRESSIONAL DISTRICT                     02070092
    P22WSEN  DS    CL2           SENATORIAL DISTRICT                        02080092
    P22WCIV  DS    CL2           CIVIL COURT DISTRICT                       02090092
    P22WCOU  DS    CL2           CITY COUNCIL DISTRICT                      02100092
    P22WRES1 DS    CL1           CD ELIGIBILITY                             02110092
    P22WDDST DS    CL5           DUPLICATE INTERSECTION DISTANCE            02120092
    P22WT00  DS    CL6           2000 CENSUS TRACT                          02130092
    P22WHCD  DS    CL2           HEALTH CENTER DISTRICT                     02140092
    P22WSD   DS    CL3           SANITATION DISTRICT                        02150092
    P22WSANT DS    CL2           SANITATION DEPT SECTION/SUBSECTION         02160092
             DS    CL12          FILLER                                     02170092
    P22WGFIL DS    CL22          FILLER FOR GRID GENERATION                 02180092
    P22WLGCF DS    CL8           UP TO 4 LGCS FOR FIRST INTERSECTING STR    02190092
    P22WLGCS DS    CL8           UP TO 4 LGCS FOR SECOND INTERSECTING STR   02200092
    P22WTR   DS    CL10          TURN RESTRICTIONS                          02210092
    P22WPLGC DS    CL10          PREFERRED LGCS FOR 5 STS IN ST LIST        02220092
    P22WTRC  DS    CL2           TRUE REPLICATION COUNTER                   02230092
    P22WDNOD DS    20CL7         LIST OF 20 7-BYTE DUPLICATE NODES          02240092
    P22WS7SC DS    CL3200        B7SCS FOR NODE LIST(20*5*4*8)              02250092
    P22WRC   DS    CL1           REASON CODE                                02260092
    P22WRCQ  DS    CL1           REASON CODE QUALIFIER                      02270092
    P22WWC   DS    CL2           WARNING CODE                               02280092
    P22WGRC  DS    CL2           RETURN CODE                                02290092
    P22WLAT  DS    CL9           LATITUDE CALC FROM X-Y                     02300092
    P22WLON  DS    CL11          LONGITUDE CALC FROM X-Y                    02310092
             DS    CL374         FILLER                                     02320092
    P22WEND  EQU   *                                                        02330092
    P22WLEN  EQU   P22WEND-P2BAL      Length of WA 2 for Fn 2W              02340092
    ********************************************************************    02350092
             ORG   P2LAYOUT      RESET LOCATION COUNTER FOR FUNCTION 3      02360092
    ********************************************************************    02370092
    *                                                                       02380092
    P2F3DUPF DS   0CL1           DUPLICATE KEY FLAG                         02390092
    P2F3PAR  DS    CL1           CONTINUOUS PARITY INDICATOR                02400092
    P2F3LST  DS    CL1           Locational Status of Segment               02410092
    P2F3CBI  DS    CL1           County Boundary Indicator                  02420092
    P2F3LGC1 DS    CL2           STREET 1 PREFERRED LGC                     02430092
    P2F3LGC2 DS    CL2           STREET 2 PREFERRED LGC                     02440092
    P2F3LGC3 DS    CL2           STREET 3 PREFERRED LGC                     02450092
    P2F3#STL DS    CL1           NUMBER OF CROSS STREETS AT LOW END         02460092
    P2F3CDEL DS    CL30          CROSS STREET B5SC'S AT LOW END             02470092
    P2F3#STH DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        02480092
    P2F3CDEH DS    CL30          CROSS STREET B5SC'S AT HIGH END            02490092
    P2F3REVF DS    CL1           REVERSAL FLAG                              02500092
    P2F3KEY  DS   0CL10          LION KEY                                   02510092
    P2F3BOR  DS    CL1           LION BOROUGH CODE                          02520092
    P2F3FACE DS    CL4           LION FACE CODE                             02530092
    P2F3SEQ  DS    CL5           LION SEQUENCE NUMBER                       02540092
    P2F3GEN  DS    CL1           GENERATED RECORD FLAG                      02550092
    P2F3SEGL DS    CL5           SEGMENT LENGTH IN FEET                     02560092
    P2F3SLOP DS    CL3           SEGMENT SLOPE IN DEGREES                   02570092
    P2F3ORNT DS    CL1           SEGMENT ORIENTATION                        02580092
    P2F3MHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             02590092
    P2F3FROM DS    CL7           FROM NODE                                  02600092
    P2F3TO   DS    CL7           TO NODE                                    02610092
    P2F3SP   DS    CL1           SANITATION STREET SNOW PRIORITY            02620092
             DS    CL4           Future Use                                 02630092
    *                                                                       02640092
    *                            Apply to both sides of street              02650092
    *                                                                       02660092
    P2F3SEGT DS    CL7           Segment Identifier                         02670092
    P2F3SLA  DS    CL1           STREET LIGHT AREA                          02680092
    P2F3CURV DS    CL1           Curve Flag                                 02690092
    P2F3DGLG DS    CL1           Dog Leg Flag                               02700092
    P2F3FEAT DS    CL1           Feature Type Code                          02710092
    P2F3STC  DS    CL1           Segment Type Code                          02720092
    P2F3CSC  DS    CL1           Coincident Segment Count                   02730092
             DS    CL4           Future Use                                 02740092
    *                                                                       02750092
    *                            Left Side of Street                        02760092
    *                                                                       02770092
    P2F3CDL  DS   0CL3           LEFT COMMUNITY DISTRICT                    02780092
    P2F3CDBL DS    CL1           LEFT COMMUNITY DISTRICT BORO               02790092
    P2F3CDNL DS    CL2           LEFT COMMUNITY DISTRICT NUMBER             02800092
    P2F3LO#L DS    CL16          LEFT LOW HOUSE NUMBER                      02810092
    P2F3HI#L DS    CL16          LEFT HIGH HOUSE NUMBER                     02820092
             DS    CL32               Future Use                            02830092
    P2F3RS2L DS    CL1           RESERVED FOR DCP/GSS USE                   02840092
    P2F3ZIPL DS    CL5           LEFT ZIP CODE                              02850092
    P2F3HAL  DS    CL4           LEFT HEALTH AREA                           02860092
    P2F3POLL DS   0CL4           LEFT POLICE DISTRICT                       02870092
    P2F3PBCL DS    CL1           LEFT POLICE PATROL BORO COMMAND            02880092
    P2F3POPL DS    CL3           LEFT POLICE PRECINCT                       02890092
    P2F3FSL  DS    CL2           LEFT FIRE DIVISION                         02900092
    P2F3FBL  DS    CL2           LEFT FIRE BATTALION                        02910092
    P2F3FCL  DS   0CL4           LEFT FIRE COMPANY                          02920092
    P2F3FCTL DS    CL1           LEFT FIRE COMPANY TYPE                     02930092
    P2F3FCNL DS    CL3           LEFT FIRE COMPANY NUMBER                   02940092
    P2F3SCHL DS    CL2           LEFT SCHOOL DISTRICT                       02950092
    P2F3CPBL DS    CL3           LEFT DYNAMIC BLOCK/ATOMIC POLYGON          02960092
    P2F3EDL  DS    CL3           LEFT ED                                    02970092
    P2F3ADL  DS    CL2           LEFT AD                                    02980092
    P2F3PPBL DS    CL2           Left Police Patrol Borough                 02990092
             DS    CL1           Filler                                     03000092
    P2F3BROL DS    CL1           Left BOROUGH CODE                          03010092
    P2F3TR9L DS    CL6           Left 1990 CENSUS TRACT                     03020092
    P2F3C10L DS    CL6           Left 2010 CENSUS TRACT                     03030092
    P2F3B10L DS    CL4           Left 2010 CENSUS BLOCK NUMBER              03040092
    P2F3BS1L DS    CL1           Left 2010 CENSUS BLOCK SUFFIX-NOT IMPLEMNT 03050092
    P2F3T00L DS    CL6           Left 2000 CENSUS TRACT                     03060092
    P2F3B00L DS    CL4           Left 2000 CENSUS BLOCK NUMBER              03070092
    P2F3S00L DS    CL1           Left 2000 CENSUS BLOCK SUFFIX              03080092
             DS    CL7           Filler                                     03090092
    *P2F3BIDL DS    CL7           Left BLOCKFACE ID                         03100092
    P2F3NTAL DS    CL4           Left NEIGHBORHOOD TABULATION AREA          03110092
             DS    CL8           Future Use                                 03120092
    *                                                                       03130092
    *                            Right Side of Street                       03140092
    *                                                                       03150092
    P2F3CDR  DS   0CL3           RIGHT COMMUNITY DISTRICT                   03160092
    P2F3CDBR DS    CL1           RIGHT COMMUNITY DISTRICT BORO              03170092
    P2F3CDNR DS    CL2           RIGHT COMMUNITY DISTRICT NUMBER            03180092
    P2F3LO#R DS    CL16          RIGHT LOW HOUSE NUMBER                     03190092
    P2F3HI#R DS    CL16          RIGHT HIGH HOUSE NUMBER                    03200092
             DS    CL32                Future Use                           03210092
    P2F3RS2R DS    CL1           RESERVED FOR DCP/GSS USE                   03220092
    P2F3ZIPR DS    CL5           RIGHT ZIP CODE                             03230092
    P2F3HAR  DS    CL4           RIGHT HEALTH AREA                          03240092
    P2F3POLR DS   0CL4           RIGHT POLICE DISTRICT                      03250092
    P2F3PBCR DS    CL1           RIGHT POLICE PATROL BORO COMMAND           03260092
    P2F3POPR DS    CL3           RIGHT POLICE PRECINCT                      03270092
    P2F3FSR  DS    CL2           RIGHT FIRE DIVISION                        03280092
    P2F3FBR  DS    CL2           RIGHT FIRE BATTALION                       03290092
    P2F3FCR  DS   0CL4           RIGHT FIRE COMPANY                         03300092
    P2F3FCTR DS    CL1           RIGHT FIRE COMPANY TYPE                    03310092
    P2F3FCNR DS    CL3           RIGHT FIRE COMPANY NUMBER                  03320092
    P2F3SCHR DS    CL2           RIGHT SCHOOL DISTRICT                      03330092
    P2F3CPBR DS    CL3           RIGHT DYNAMIC BLOCK/ATOMIC POLYGON         03340092
    P2F3EDR  DS    CL3           RIGHT ED                                   03350092
    P2F3ADR  DS    CL2           RIGHT AD                                   03360092
    P2F3PPBR DS    CL2           Right Police Patrol Borough                03370092
             DS    CL1           Filler                                     03380092
    P2F3BROR DS    CL1           Right BOROUGH CODE                         03390092
    P2F3TR9R DS    CL6           Right 1990 CENSUS TRACT                    03400092
    P2F3C10R DS    CL6           Right 2010 CENSUS TRACT                    03410092
    P2F3B10R DS    CL4           Right 2010 CENSUS BLOCK                    03420092
    P2F3BS1R DS    CL1           Right 2010 CENSUS BLOCK SUFFIX NOT IMPLM   03430092
    P2F3T00R DS    CL6           Right 2000 CENSUS TRACT                    03440092
    P2F3B00R DS    CL4           Right 2000 CENSUS BLOCK                    03450092
    P2F3S00R DS    CL1           Right 2000 CENSUS BLOCK SUFFIX             03460092
    *P2F3BIDR DS    CL7           RIGHT BLOCKFACE ID                        03470092
             DS    CL7           Filler V16.1                               03480092
    P2F3NTAR DS    CL4           RIGHT NEIGHBORHOOD TABULATION AREA         03490092
             DS    CL8           Future Use                                 03500092
    P2F3END  EQU   *                                                        03510092
    P2F3LEN  EQU   P2F3END-P2BAL      Length of WA 2 for Fn 3               03520092
    *                                                                       03530092
    ********************************************************************    03540092
             ORG   P2F3END       Auxiliary Segment Overlay - FUNCTION 3     03550092
    ********************************************************************    03560092
    *                                                                       03570092
    P2F3FILR DS    CL6           Future Use                                 03580092
    P2F3SCNT DS    CL4           Number of segment ids                      03590092
    P2F3SGID DS    CL490         up to 70 Seven Byte Segment IDS            03600092
    P2F3SEND EQU   *                                                        03610092
    P2F3SLEN EQU   P2F3SEND-P2BAL  Length of WA 2 for Fn 3 w/segments       03620092
    *                                                                       03630092
    ********************************************************************    03640092
             ORG   P2LAYOUT  RESET LOCATION COUNTER-FUNCTION 3 EXTENDED     03650092
    ********************************************************************    03660092
    *                                                                       03670092
    P23XDUPF DS   0CL1           DUPLICATE KEY FLAG                         03680092
    P23XPAR  DS    CL1           CONTINUOUS PARITY INDICATOR                03690092
    P23XLST  DS    CL1           Locational Status of Segment               03700092
    P23XCBI  DS    CL1           County Boundary Indicator                  03710092
    P23XLGC1 DS    CL2           STREET 1 PREFERRED LGC                     03720092
    P23XLGC2 DS    CL2           STREET 2 PREFERRED LGC                     03730092
    P23XLGC3 DS    CL2           STREET 3 PREFERRED LGC                     03740092
    P23X#STL DS    CL1           NUMBER OF CROSS STREETS AT LOW END         03750092
    P23XCDEL DS    CL30          CROSS STREET B5SC'S AT LOW END             03760092
    P23X#STH DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        03770092
    P23XCDEH DS    CL30          CROSS STREET B5SC'S AT HIGH END            03780092
    P23XREVF DS    CL1           REVERSAL FLAG                              03790092
    P23XKEY  DS   0CL10          LION KEY                                   03800092
    P23XBOR  DS    CL1           LION BOROUGH CODE                          03810092
    P23XFACE DS    CL4           LION FACE CODE                             03820092
    P23XSEQ  DS    CL5           LION SEQUENCE NUMBER                       03830092
    P23XGEN  DS    CL1           GENERATED RECORD FLAG                      03840092
    P23XSEGL DS    CL5           SEGMENT LENGTH IN FEET                     03850092
    P23XSLOP DS    CL3           SEGMENT SLOPE IN DEGREES                   03860092
    P23XORNT DS    CL1           SEGMENT ORIENTATION                        03870092
    P23XMHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             03880092
    P23XFROM DS    CL7           FROM NODE                                  03890092
    P23XTO   DS    CL7           TO NODE                                    03900092
    P23XSP   DS    CL1           SANITATION STREET SNOW PRIORITY            03910092
             DS    CL4           Future Use                                 03920092
    *                                                                       03930092
    *                            Apply to both sides of street              03940092
    *                                                                       03950092
    P23XSEGT DS    CL7           Segment Identifier                         03960092
    P23XSLA  DS    CL1           STREET LIGHT AREA                          03970092
    P23XCURV DS    CL1           Curve Flag                                 03980092
    P23XDGLG DS    CL1           Dog Leg Flag                               03990092
    P23XFEAT DS    CL1           Feature Type Code                          04000092
    P23XSTC  DS    CL1           Segment Type Code                          04010092
    P23XCSC  DS    CL1           Coincident Segment Count                   04020092
             DS    CL4           Future Use                                 04030092
    *                                                                       04040092
    *                            Left Side of Street                        04050092
    *                                                                       04060092
    P23XCDL  DS   0CL3           LEFT COMMUNITY DISTRICT                    04070092
    P23XCDBL DS    CL1           LEFT COMMUNITY DISTRICT BORO               04080092
    P23XCDNL DS    CL2           LEFT COMMUNITY DISTRICT NUMBER             04090092
    P23XLO#L DS    CL16          LEFT LOW HOUSE NUMBER                      04100092
    P23XHI#L DS    CL16          LEFT HIGH HOUSE NUMBER                     04110092
             DS    CL32               Future Use                            04120092
    P23XRS2L DS    CL1           RESERVED FOR DCP/GSS USE                   04130092
    P23XZIPL DS    CL5           LEFT ZIP CODE                              04140092
    P23XHAL  DS    CL4           LEFT HEALTH AREA                           04150092
    P23XPOLL DS   0CL4           LEFT POLICE DISTRICT                       04160092
    P23XPBCL DS    CL1           LEFT POLICE PATROL BORO COMMAND            04170092
    P23XPOPL DS    CL3           LEFT POLICE PRECINCT                       04180092
    P23XFSL  DS    CL2           LEFT FIRE DIVISION                         04190092
    P23XFBL  DS    CL2           LEFT FIRE BATTALION                        04200092
    P23XFCL  DS   0CL4           LEFT FIRE COMPANY                          04210092
    P23XFCTL DS    CL1           LEFT FIRE COMPANY TYPE                     04220092
    P23XFCNL DS    CL3           LEFT FIRE COMPANY NUMBER                   04230092
    P23XSCHL DS    CL2           LEFT SCHOOL DISTRICT                       04240092
    P23XCPBL DS    CL3           LEFT DYNAMIC BLOCK/ATOMIC POLYGON          04250092
    P23XEDL  DS    CL3           LEFT ED                                    04260092
    P23XADL  DS    CL2           LEFT AD                                    04270092
    P23XPPBL DS    CL2           Left Police Patrol Borough                 04280092
             DS    CL1           Filler                                     04290092
    P23XBROL DS    CL1           Left BOROUGH CODE                          04300092
    P23XTR9L DS    CL6           Left 1990 CENSUS TRACT                     04310092
    P23XC10L DS    CL6           Left 2010 CENSUS TRACT                     04320092
    P23XB10L DS    CL4           Left 2010 CENSUS BLOCK NUMBER              04330092
    P23XBS1L DS    CL1           Left 2010 CENSUS BLOCK SUFFIX-NOT IMPLEMNT 04340092
    P23XT00L DS    CL6           Left 2000 CENSUS TRACT                     04350092
    P23XB00L DS    CL4           Left 2000 CENSUS BLOCK NUMBER              04360092
    P23XS00L DS    CL1           Left 2000 CENSUS BLOCK SUFFIX              04370092
    *P23XBIDL DS    CL7           Left BLOCKFACE ID                         04380092
             DS    CL7           Filler                                     04390092
    P23XNTAL DS    CL4           Left NEIGHBORHOOD TABULATION AREA          04400092
             DS    CL8           Future Use                                 04410092
    *                                                                       04420092
    *                            Right Side of Street                       04430092
    *                                                                       04440092
    P23XCDR  DS   0CL3           RIGHT COMMUNITY DISTRICT                   04450092
    P23XCDBR DS    CL1           RIGHT COMMUNITY DISTRICT BORO              04460092
    P23XCDNR DS    CL2           RIGHT COMMUNITY DISTRICT NUMBER            04470092
    P23XLO#R DS    CL16          RIGHT LOW HOUSE NUMBER                     04480092
    P23XHI#R DS    CL16          RIGHT HIGH HOUSE NUMBER                    04490092
             DS    CL32                Future Use                           04500092
    P23XRS2R DS    CL1           RESERVED FOR DCP/GSS USE                   04510092
    P23XZIPR DS    CL5           RIGHT ZIP CODE                             04520092
    P23XHAR  DS    CL4           RIGHT HEALTH AREA                          04530092
    P23XPOLR DS   0CL4           RIGHT POLICE DISTRICT                      04540092
    P23XPBCR DS    CL1           RIGHT POLICE PATROL BORO COMMAND           04550092
    P23XPOPR DS    CL3           RIGHT POLICE PRECINCT                      04560092
    P23XFSR  DS    CL2           RIGHT FIRE DIVISION                        04570092
    P23XFBR  DS    CL2           RIGHT FIRE BATTALION                       04580092
    P23XFCR  DS   0CL4           RIGHT FIRE COMPANY                         04590092
    P23XFCTR DS    CL1           RIGHT FIRE COMPANY TYPE                    04600092
    P23XFCNR DS    CL3           RIGHT FIRE COMPANY NUMBER                  04610092
    P23XSCHR DS    CL2           RIGHT SCHOOL DISTRICT                      04620092
    P23XCPBR DS    CL3           RIGHT DYNAMIC BLOCK/ATOMIC POLYGON         04630092
    P23XEDR  DS    CL3           RIGHT ED                                   04640092
    P23XADR  DS    CL2           RIGHT AD                                   04650092
    P23XPPBR DS    CL2           Right Police Patrol Borough                04660092
             DS    CL1           Filler                                     04670092
    P23XBROR DS    CL1           Right BOROUGH CODE                         04680092
    P23XTR9R DS    CL6           Right 1990 CENSUS TRACT                    04690092
    P23XC10R DS    CL6           Right 2010 CENSUS TRACT                    04700092
    P23XB10R DS    CL4           Right 2010 CENSUS BLOCK                    04710092
    P23XBS1R DS    CL1           Right 2010 CENSUS BLOCK SUFFIX NOT IMPLM   04720092
    P23XT00R DS    CL6           Right 2000 CENSUS TRACT                    04730092
    P23XB00R DS    CL4           Right 2000 CENSUS BLOCK                    04740092
    P23XS00R DS    CL1           Right 2000 CENSUS BLOCK SUFFIX             04750092
    *P23XBIDR DS    CL7           RIGHT BLOCKFACE ID                        04760092
             DS    CL7           Filler                                     04770092
    P23XNTAR DS    CL4           RIGHT NEIGHBORHOOD TABULATION AREA         04780092
             DS    CL8           Future Use                                 04790092
    P23XLGCS DS    CL8           List of 4 LGCs                             04800092
    P23XLGCF DS    CL8           List of 4 From LGCs                        04810092
    P23XLGCT DS    CL8           List of 4 To LGCs                          04820092
    P23XLHCD DS    CL2           Left Health Center District                04830092
    P23XRHCD DS    CL2           Right Health Center District               04840092
    P23XFILS DS    CL1           Filler                                     04850092
    P23XTD   DS    CL1           Traffic Direction                          04860092
    P23XRTP  DS    CL2           Roadyway Type                              04870092
    P23XPID  DS    CL7           Physical Id                                04880092
    P23XGID  DS    CL7           Generic Id                                 04890092
    P23XPDID DS    CL7           For DCP Use Only                           04900092
    P23XFDID DS    CL7           For DCP Use Only                           04910092
    P23XSTST DS    CL1           Street Status                              04920092
    P23XSTW  DS    CL3           Street Width                               04930092
    P23XSTWI DS    CL1           Street Width Irregular                     04940092
    P23XBL   DS    CL1           Bike Lane                                  04950092
    P23XFCC  DS    CL2           Federal Classification Code                04960092
    P23XROW  DS    CL1           Row Type                                   04970092
    P23XLGC5 DS    CL10          List of 5 LGCs                             04980092
    P23XLGID DS    CL7           Legacy Id                                  04990092
    P23XLNTA DS    CL75          Left NTA Name                              05000092
    P23XRNTA DS    CL75          Right NTA Name                             05010092
    P23XFXC  DS    CL7           From X Coordinate                          05020092
    P23XFYC  DS    CL7           From Y Coordinate                          05030092
    P23XTXC  DS    CL7           To X Coordinate                            05040092
    P23XTYC  DS    CL7           To Y Coordinate                            05050092
    P23XFLAT DS    CL9           LATITUDE OF FROM INTERSCT.                 05060092
    P23XFLON DS    CL11          LONGITUDE OF FROM INTERSCT.                05070092
    P23XTLAT DS    CL9           LATITUDE OF TO INTERSCT.                   05080092
    P23XTLON DS    CL11          LONGITUDE OF TO INTERSCT.                  05090092
    P23XBIDL DS    CL10          NEW location Left Blockface Id V16.1       05100092
    P23XBIDR DS    CL10          NEW location Right Blockface Id V16.1      05110092
    P23X#TRL DS    CL2           nbr of traveling lanes                     05120092
    P23X#PKL DS    CL2           nbr of parking lanes                       05130092
    P23X#TLL DS    CL2           nbr of total lanes                         05140092
    P23XBL2  DS    CL2           Bike Lane 2 (has 2 bytes numeric value)    05150092
    P23XSTWX DS    CL3           Street Width Maximum                       05160092
    P23XBTD  DS    CL2           Bike Traffic Direction                     05170092
    P23XFILL DS    CL213         FILLER                                     05180092
    P23XEND  EQU   *                                                        05190092
    P23XLEN  EQU   P23XEND-P2BAL      Length of WA 2 for Fn 3 Extended      05200092
    *                                                                       05210092
    ********************************************************************    05220092
             ORG   P23XEND  Auxiliary Seg Overlay - FUNCTION 3 EXTENDED     05230092
    ********************************************************************    05240092
    *                                                                       05250092
    P23XFILR DS    CL6           Future Use                                 05260092
    P23XSCNT DS    CL4           Number of segment ids                      05270092
    P23XSGID DS    CL490         up to 70 Seven Byte Segment IDS            05280092
    P23XSEND EQU   *                                                        05290092
    P23XSLEN EQU   P23XSEND-P2BAL  Len of WA2 for Fn3 MODE=X w/segments     05300092
    *                                                                       05310092
    ********************************************************************    05320092
             ORG   P2LAYOUT      RESET LOCATION COUNTER FOR FUNCTION 3C     05330092
    ********************************************************************    05340092
    *                                                                       05350092
    P23CDUPF DS   0CL1           DUPLICATE KEY FLAG                         05360092
    P23CPAR  DS    CL1           CONTINUOUS PARITY INDICATOR                05370092
    P23CLST  DS    CL1           Locational Status of Segment               05380092
    P23CCBI  DS    CL1           County Boundary Indicator                  05390092
    P23CLGC1 DS    CL2           STREET 1 PREFERRED LGC                     05400092
    P23CLGC2 DS    CL2           STREET 2 PREFERRED LGC                     05410092
    P23CLGC3 DS    CL2           STREET 3 PREFERRED LGC                     05420092
    P23C#STL DS    CL1           NUMBER OF CROSS STREETS AT LOW END         05430092
    P23CCDEL DS    CL30          CROSS STREET B5SC'S AT LOW END             05440092
    P23C#STH DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        05450092
    P23CCDEH DS    CL30          CROSS STREET B5SC'S AT HIGH END            05460092
    P23CREVF DS    CL1           REVERSAL FLAG                              05470092
    P23CKEY  DS   0CL10          LION KEY                                   05480092
    P23CBOR  DS    CL1           LION BOROUGH CODE                          05490092
    P23CFACE DS    CL4           LION FACE CODE                             05500092
    P23CSEQ  DS    CL5           LION SEQUENCE NUMBER                       05510092
    P23CGEN  DS    CL1           GENERATED RECORD FLAG                      05520092
    P23CSEGL DS    CL5           SEGMENT LENGTH IN FEET                     05530092
    P23CSLOP DS    CL3           SEGMENT SLOPE IN DEGREES                   05540092
    P23CORNT DS    CL1           SEGMENT ORIENTATION                        05550092
    P23CMHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             05560092
    P23CFROM DS    CL7           FROM NODE                                  05570092
    P23CTO   DS    CL7           TO NODE                                    05580092
    P23CSP   DS    CL1           SANITATION STREET SNOW PRIORITY            05590092
             DS    CL4           Future Use                                 05600092
    *                                                                       05610092
    *                            Side of Street Information                 05620092
    *                                                                       05630092
    P23CSEGT DS    CL7           Segment Identifier                         05640092
    P23CSLA  DS    CL1           STREET LIGHT AREA                          05650092
    P23CSOS  DS    CL1           Side of Street Indicator                   05660092
    P23CCURV DS    CL1           Curve Flag                                 05670092
    P23CFEAT DS    CL1           Feature Type Code                          05680092
    P23CSTC  DS    CL1           Segment Type Code                          05690092
    P23CCSC  DS    CL1           COINCIDENT SEGMENT COUNT                   05700092
             DS    CL4           Future Use                                 05710092
    P23CCD   DS   0CL3           COMMUNITY DISTRICT                         05720092
    P23CCDB  DS    CL1           COMMUNITY DISTRICT BORO                    05730092
    P23CCDN  DS    CL2           COMMUNITY DISTRICT NUMBER                  05740092
    P23CLO#  DS    CL16          LOW HOUSE NUMBER                           05750092
    P23CHI#  DS    CL16          HIGH HOUSE NUMBER                          05760092
    P23CHS2L DS    CL16          2ND LOW HSE # - USED IF ODD & EVEN RANGES  05770092
    P23CHS2H DS    CL16          2ND HI HSE #    ARE ON SAME SIDE OF STREET 05780092
    P23CRES2 DS    CL1           RESERVED FOR DCP/GSS USE                   05790092
    P23CZIP  DS    CL5           ZIP CODE                                   05800092
    P23CHAL  DS    CL4           HEALTH AREA                                05810092
    P23CPOL  DS   0CL4           POLICE DISTRICT                            05820092
    P23CPBC  DS    CL1           POLICE PATROL BORO COMMAND                 05830092
    P23CPOP  DS    CL3           POLICE PRECINCT                            05840092
    P23CFS   DS    CL2           FIRE DIVISION                              05850092
    P23CFB   DS    CL2           FIRE BATTALION                             05860092
    P23CFC   DS   0CL4           FIRE COMPANY                               05870092
    P23CFCT  DS    CL1           FIRE COMPANY TYPE                          05880092
    P23CFCN  DS    CL3           FIRE COMPANY NUMBER                        05890092
    P23CSCH  DS    CL2           SCHOOL DISTRICT                            05900092
    P23CCPB  DS    CL3           DYNAMIC  BLOCK / ATOMIC POLYGON            05910092
    P23CED   DS    CL3           ED                                         05920092
    P23CAD   DS    CL2           AD                                         05930092
    P23CPPB  DS    CL2           Police Patrol Borough                      05940092
             DS    CL1           Filler                                     05950092
    P23CBRO  DS    CL1           BOROUGH CODE                               05960092
    P23CTR9  DS    CL6           1990 CENSUS TRACT                          05970092
    P23CCT10 DS    CL6           2010 CENSUS TRACT                          05980092
    P23CBL10 DS    CL4           2010 CENSUS BLOCK                          05990092
    P23CBL1S DS    CL1           2010 CENSUS BLOCK SUFFIX NOT IMPLEMENTED   06000092
    P23CT00  DS    CL6           2000 CENSUS TRACT                          06010092
    P23CB00  DS    CL4           2000 CENSUS BLOCK                          06020092
    P23CS00  DS    CL1           2000 CENSUS BLOCK SUFFIX                   06030092
    *P23CBID  DS    CL7          BLOCKFACE ID                               06040092
             DS    CL7           Filler V16.1                               06050092
    P23CNTA  DS    CL4           NEIGHBORHOOD TABULATION AREA               06060092
             DS    CL8           Future Use                                 06070092
    P23CEND  EQU   *                                                        06080092
    P23CLEN  EQU   P23CEND-P2BAL      Length of WA 2 for Fn 3C              06090092
    ********************************************************************    06100092
             ORG   P23CEND       Auxiliary Segment Overlay - FUNCTION 3C    06110092
    ********************************************************************    06120092
    *                                                                       06130092
    P23CFILR DS    CL6           FUTURE USE                                 06140092
    P23CSCNT DS    CL4           Number of segment ids                      06150092
    P23CSGID DS    CL490         up to 70 Seven Byte Segment IDS            06160092
    P23CSEND EQU   *                                                        06170092
    P23CSLEN EQU   P23CSEND-P2BAL  Length of WA 2 for Fn 3C w/Segments      06180092
    *                                                                       06190092
    ********************************************************************    06200092
             ORG   P2LAYOUT RESET LOC COUNTER FOR FUNCTION 3C EXTENDED      06210092
    ********************************************************************    06220092
    *                                                                       06230092
    P2CXDUPF DS   0CL1           DUPLICATE KEY FLAG                         06240092
    P2CXPAR  DS    CL1           CONTINUOUS PARITY INDICATOR                06250092
    P2CXLST  DS    CL1           Locational Status of Segment               06260092
    P2CXCBI  DS    CL1           County Boundary Indicator                  06270092
    P2CXLGC1 DS    CL2           STREET 1 PREFERRED LGC                     06280092
    P2CXLGC2 DS    CL2           STREET 2 PREFERRED LGC                     06290092
    P2CCLGC3 DS    CL2           STREET 3 PREFERRED LGC                     06300092
    P2CX#STL DS    CL1           NUMBER OF CROSS STREETS AT LOW END         06310092
    P2CXCDEL DS    CL30          CROSS STREET B5SC'S AT LOW END             06320092
    P2CX#STH DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        06330092
    P2CXCDEH DS    CL30          CROSS STREET B5SC'S AT HIGH END            06340092
    P2CXREVF DS    CL1           REVERSAL FLAG                              06350092
    P2CXKEY  DS   0CL10          LION KEY                                   06360092
    P2CXBOR  DS    CL1           LION BOROUGH CODE                          06370092
    P2CXFACE DS    CL4           LION FACE CODE                             06380092
    P2CXSEQ  DS    CL5           LION SEQUENCE NUMBER                       06390092
    P2CXGEN  DS    CL1           GENERATED RECORD FLAG                      06400092
    P2CXSEGL DS    CL5           SEGMENT LENGTH IN FEET                     06410092
    P2CXSLOP DS    CL3           SEGMENT SLOPE IN DEGREES                   06420092
    P2CXORNT DS    CL1           SEGMENT ORIENTATION                        06430092
    P2CXMHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             06440092
    P2CXFROM DS    CL7           FROM NODE                                  06450092
    P2CXTO   DS    CL7           TO NODE                                    06460092
    P2CXSP   DS    CL1           SANITATION STREET SNOW PRIORITY            06470092
             DS    CL4           Future Use                                 06480092
    *                                                                       06490092
    *                            Side of Street Information                 06500092
    *                                                                       06510092
    P2CXSEGT DS    CL7           Segment Identifier                         06520092
    P2CXSLA  DS    CL1           STREET LIGHT AREA                          06530092
    P2CXSOS  DS    CL1           Side of Street Indicator                   06540092
    P2CXCURV DS    CL1           Curve Flag                                 06550092
    P2CXFEAT DS    CL1           Feature Type Code                          06560092
    P2CXSTC  DS    CL1           Segment Type Code                          06570092
    P2CXCSC  DS    CL1           COINCIDENT SEGMENT COUNT                   06580092
             DS    CL4           Future Use                                 06590092
    P2CXCD   DS   0CL3           COMMUNITY DISTRICT                         06600092
    P2CXCDB  DS    CL1           COMMUNITY DISTRICT BORO                    06610092
    P2CXCDN  DS    CL2           COMMUNITY DISTRICT NUMBER                  06620092
    P2CXLO#  DS    CL16          LOW HOUSE NUMBER                           06630092
    P2CXHI#  DS    CL16          HIGH HOUSE NUMBER                          06640092
    P2CXHS2L DS    CL16          2ND LOW HSE # - USED IF ODD & EVEN RANGES  06650092
    P2CXHS2H DS    CL16          2ND HI HSE #    ARE ON SAME SIDE OF STREET 06660092
    P2CXRES2 DS    CL1           RESERVED FOR DCP/GSS USE                   06670092
    P2CXZIP  DS    CL5           ZIP CODE                                   06680092
    P2CXHAL  DS    CL4           HEALTH AREA                                06690092
    P2CXPOL  DS   0CL4           POLICE DISTRICT                            06700092
    P2CXPBC  DS    CL1           POLICE PATROL BORO COMMAND                 06710092
    P2CXPOP  DS    CL3           POLICE PRECINCT                            06720092
    P2CXFS   DS    CL2           FIRE DIVISION                              06730092
    P2CXFB   DS    CL2           FIRE BATTALION                             06740092
    P2CXFC   DS   0CL4           FIRE COMPANY                               06750092
    P2CXFCT  DS    CL1           FIRE COMPANY TYPE                          06760092
    P2CXFCN  DS    CL3           FIRE COMPANY NUMBER                        06770092
    P2CXSCH  DS    CL2           SCHOOL DISTRICT                            06780092
    P2CXCPB  DS    CL3           DYNAMIC  BLOCK / ATOMIC POLYGON            06790092
    P2CXED   DS    CL3           ED                                         06800092
    P2CXAD   DS    CL2           AD                                         06810092
    P2CXPPB  DS    CL2           Police Patrol Borough                      06820092
             DS    CL1           Filler                                     06830092
    P2CXBRO  DS    CL1           BOROUGH CODE                               06840092
    P2CXTR9  DS    CL6           1990 CENSUS TRACT                          06850092
    P2CXCT10 DS    CL6           2010 CENSUS TRACT                          06860092
    P2CXBL10 DS    CL4           2010 CENSUS BLOCK                          06870092
    P2CXBL1S DS    CL1           2010 CENSUS BLOCK SUFFIX NOT IMPLEMENTED   06880092
    P2CXT00  DS    CL6           2000 CENSUS TRACT                          06890092
    P2CXB00  DS    CL4           2000 CENSUS BLOCK                          06900092
    P2CXS00  DS    CL1           2000 CENSUS BLOCK SUFFIX                   06910092
    *P2CXBID  DS    CL7           BLOCKFACE ID                              06920092
             DS    CL7           Filler V16.1                               06930092
    P2CXNTA  DS    CL4           NEIGHBORHOOD TABULATION AREA               06940092
             DS    CL8           Future Use                                 06950092
    P2CXLGCS DS    CL8           List of 4 LGCs                             06960092
    P2CXLGCF DS    CL8           List of 4 From LGCs                        06970092
    P2CXLGCT DS    CL8           List of 4 To LGCs                          06980092
    P2CXLHCD DS    CL2           Left Health Center District                06990092
    P2CXRHCD DS    CL2           Right Health Center District               07000092
    P2CXFILS DS    CL1           Filler                                     07010092
    P2CXTD   DS    CL1           Traffic Direction                          07020092
    P2CXRTP  DS    CL2           Roadyway Type                              07030092
    P2CXPID  DS    CL7           Physical Id                                07040092
    P2CXGID  DS    CL7           Generic Id                                 07050092
    P2CXPDID DS    CL7           For DCP Use Only                           07060092
    P2CXFDID DS    CL7           For DCP Use Only                           07070092
    P2CXSTST DS    CL1           Street Status                              07080092
    P2CXSTW  DS    CL3           Street Width                               07090092
    P2CXSTWI DS    CL1           Street Width Irregular                     07100092
    P2CXBL   DS    CL1           Bike Lane                                  07110092
    P2CXFCC  DS    CL2           Federal Classification Code                07120092
    P2CXROW  DS    CL1           Row Type                                   07130092
    P2CXLGC5 DS    CL10          List of 5 LGCs                             07140092
    P2CXLGID DS    CL7           Legacy Id                                  07150092
    P2CXNTAN DS    CL75          NTA Name                                   07160092
    P2CXFXC  DS    CL7           From X Coordinate                          07170092
    P2CXFYC  DS    CL7           From Y Coordinate                          07180092
    P2CXTXC  DS    CL7           To X Coordinate                            07190092
    P2CXTYC  DS    CL7           To Y Coordinate                            07200092
    P2CXFLAT DS    CL9           LATITUDE OF FROM INTERSCT.                 07210092
    P2CXFLON DS    CL11          LONGITUDE OF FROM INTERSCT.                07220092
    P2CXTLAT DS    CL9           LATITUDE OF TO INTERSCT.                   07230092
    P2CXTLON DS    CL11          LONGITUDE OF TO INTERSCT.                  07240092
    P2CXBFID DS    CL10          NEW location Blockface Id V16.1            07250092
    P2CX#TRL DS    CL2           nbr of traveling lanes                     07260092
    P2CX#PKL DS    CL2           nbr of parking lanes                       07270092
    P2CX#TLL DS    CL2           nbr of total lanes                         07280092
    P2CXBL2  DS    CL2           Bike Lane2 (has 2bytes numeric value)      07290092
    P2CXSTWX DS    CL3           Street Width Maximum                       07300092
    P2CXBTD  DS    CL2           Bike Traffic Direction                     07310092
    P2CXFILL DS    CL298         FILLER                                     07320092
    P2CXEND  EQU   *                                                        07330092
    P2CXLEN  EQU   P2CXEND-P2BAL      Length of WA 2 for Fn 3C              07340092
    ********************************************************************    07350092
             ORG   P2CXEND     Auxiliary Segment Overlay - FUNCTION 3C-X    07360092
    ********************************************************************    07370092
    *                                                                       07380092
    P2CXFILR DS    CL6           FUTURE USE                                 07390092
    P2CXSCNT DS    CL4           Number of segment ids                      07400092
    P2CXSGID DS    CL490         up to 70 Seven Byte Segment IDS            07410092
    P2CXSEND EQU   *                                                        07420092
    P2CXSLEN EQU   P2CXSEND-P2BAL  Length of WA 2 for Fn 3C-X w/Segments    07430092
    *                                                                       07440092
    *                                                                       07450092
    ********************************************************************    07460092
             ORG   P2BAL         RESET LOCATION COUNTER FOR FUNCTION 5      07470092
    ********************************************************************    07480092
    *                                                                       07490092
    P2F5AMK  DS    CL28          ACCESS MATCHING KEY                        07500092
             DS    CL172                                                    07510092
    P2F5END  EQU   *                                                        07520092
    P2F5LEN  EQU   P2F5END-P2BAL      Length of WA 2 for Fn 5               07530092
             ORG                                                            07540092


## <span id="appendix14.10"><center>P2BAL1A COPY File</center></span>



    */********************************************************************/ 00010064
    */*****  THIS IS GEOSUPPORT INFORMATION SYSTEM COPY FILE P2BAL1A,  ***/ 00020064
    */*****  CONTAINING THE LAYOUT OF WORK AREA 2 FOR FUNCTION         ***/ 00030064
    */*****  1A, BL And BN WHICH SHARE A SINGLE WORK AREA 2 LAYOUT.    ***/ 00040064
    */*****  The Long Work Area only applies to Functions 1A and BL.   ***/ 00050064
    */*****  The long work area only exists if the Address Overflow    ***/ 00060064
    */*****  Flag has been set on.                                     ***/ 00070064
    */*****  As of 2011, Function 1/1E Extended, Function 1A Extended  ***/ 00080064
    */*****  and Function 1B have been added to this Copy File         ***/ 00090064
    */*****  ADDED 2 byte field "Police Patrol Borough" for functions: ***/ 00100064
    */*****  1X/1EX/1B.                                  August 2014   ***/ 00110064
    */*****  ADDED 4 fields: "segment from node", "segment to node",   ***/ 00120064
    */*****  "segment from XYZ", "segment to XYZ" for func 1X/1EX/1B   ***/ 00130064
    */*****                                                May 2015    ***/ 00140064
    */*****  ADDED 2 fields: "Bike Lane 2" and "Street Width Maximum"  ***/ 00141068
    */*****  for functions 1EX/1B                     September 2016   ***/ 00142068
    */*****  Replaced "Saniitation Reserved" with "Sanitation Bulk     ***/ 00143070
    */*****  Pick Up" for functions 1E,1B             October   2016   ***/ 00144070
    */*****  ADDED 2 bytes field "Bike Traffic Direction" for          ***/ 00145072
    */*****  for functions 1/1E (extended),1B,3X,3CX           12/2016 ***/ 00146071
    */********************************************************************/ 00150064
    */*****          LAST UPDATE -  February 2016                      ***/ 00160066
    */********************************************************************/ 00170064
    P2BAL1A  DS   0H                                                        00180064
             DS    CL21                                                     00190064
    P21ACPAR DS    CL1           CONTINUOUS PARITY INDICATOR                00200064
    P21AHSEL DS    CL11          LOW HOUSE NUMBER ON BLOCK - HNS Form       00210064
    P21AALT1 DS   0CL11          ALTERNATE KEY                              00220064
    P21ABOR1 DS    CL1           ALTERNATE KEY - BORO                       00230064
    P21ATXB1 DS    CL5           ALTERNATE KEY - TAX BLOCK                  00240064
    P21ATXL1 DS    CL4           ALTERNATE KEY - TAX LOT                    00250064
             DS    CL1              Future Use                              00260064
    P21ARSCC DS    CL1           RPAD SCC                                   00270064
             DS    CL1           FILLER                                     00280064
    P21AGLI  DS   0CL13          GENERAL LOT INFO                           00290064
    P21ARBLC DS    CL2           RPAD BUILDING CLASSIFICATION               00300064
    P21ACORC DS    CL2           CORNER CODE                                00310064
    P21A#STC DS    CL4           TOTAL NUMBER STRUCTURES                    00320064
    P21A#BFA DS    CL2           TOTAL NUMBER BLOCKFACES                    00330064
    P21AINTF DS    CL1           INTERIOR LOT FLAG                          00340064
    P21AVACF DS    CL1           VACANT LOT FLAG                            00350064
    P21AIRLF DS    CL1           IRREGULARLY-SHAPED LOT FLAG                00360064
    *                                                                       00370064
    P21AABFL DS    CL1           Marble Hill/ Rikers ALTERNATE BORO FLAG    00380064
    P21AOVFL DS    CL1           Address Overflow Flag                      00390064
    *                                                                       00400064
    P21ASTRK DS    CL19          STROLLING KEY                              00410064
    *                                                                       00420064
    P21ARFIU DS    CL1           RESERVED FOR INTERNAL USE                  00430064
    P21ABIN  DS    CL7           BUILDING IDENTIFICATION NUMBER (BIN)       00440064
    *                           Condo Information                           00450064
    P21ACONF DS    CL1           CONDO LOT FLAG                             00460064
             DS    CL1           Filler for Future Use                      00470064
    P21ARCO# DS    CL4           RPAD CONDO NUMBER                          00480064
             DS    CL7           Future Use - Condo Unit Number             00490064
    P21ACBBL DS    CL11          CONDO BILLING BBL                          00500064
    P21ACBBS DS    CL1           CONDO BILLING BBL SCC                      00510064
    P21ACLBL DS    CL11          CONDO LOW BBL                              00520064
    P21ACHBL DS    CL11          CONDO HIGH BBL                             00530064
             DS    CL15          Filler                                     00540064
    P21ACOOP DS    CL4           Co-op Number                               00550064
    *                                                                       00560064
    P21ASBVP DS    CL8           SANDBORN BOROUGH/VOLUME/PAGE               00570064
    *                                                                       00580064
    P21ABUSA DS    CL5           BUSINESS AREA                              00590064
    P21ATAXM DS    CL5           Tax Map Number - Section and Volume        00600064
             DS    CL4           Reserved for Tax Map Page                  00610064
             DS    CL3              FILLER                                  00620064
    P21ALAT  DS    CL9           LATITUDE                                   00630064
    P21ALONG DS    CL11          LONGITUDE                                  00640064
    P21AXCO  DS    CL7           X Coordinate of Annotation Point           00650064
    P21AYCO  DS    CL7           Y Coordinate of Annotation Point           00660064
    P21ABID  DS    CL6           Business Improvement District              00670064
    P21ATPBS DS    CL1           TPAD BIN Status                            00680064
    P21ATPNB DS    CL7           TPAD New BIN                               00690064
    P21ATPNS DS    CL1           TPAD New BIN Status                        00700064
    P21ATPCF DS    CL1           TPAD Conflict Flag                         00710064
             DS    CL9           FILLER                                     00720064
             DS    CL8           Internal Use                               00730064
    P21A#ADR DS    CL4           TOTAL ADDRESSES FOR LOT                    00740064
    P21ALIST DS   0CL1113        LIST OF ADDRESSES, MAXIMUM OF 21           00750064
    P21ALOW# DS    CL16          LOW HOUSE NUMBER-Display Form              00760064
    P21AHI#  DS    CL16          HIGH HOUSE NUMBER-Display Form             00770064
    P21ABCDE DS    CL1           Borough Code                               00780064
    P21ACODE DS    CL5           STREET CODE                                00790064
    P21APLGC DS    CL2           Preferred LGC                              00800064
    P21ALBIN DS    CL7           BIN                                        00810064
    P21ALSOS DS    CL1           Side of Street Indicator                   00820064
    P21AATP  DS    CL1           Address Type Flag                          00830064
    P21AATPS DS    CL1           TPAD BIN Status                            00840064
             DS    CL3           FILLER                                     00850064
    *  STORAGE IS RESERVED FOR THE REMAINING 20 ADDRESS STRUCTURES.         00860064
    *  EACH STRUCTURE IS IDENTICAL TO THE ONE DEFINED ABOVE.                00870064
             DS    CL1060        REMAINING ADDRESSES                        00880064
    P21ASEND EQU   *                                                        00890064
    P21ASLEN EQU   P21ASEND-P2BAL1A    LENGTH OF Short P2BAL1A              00900064
    *                                                                       00910064
    *        Long Work Area Overlay                                         00920064
    *                                                                       00930064
             ORG   P21A#ADR                                                 00940064
    P21A#BIN DS    CL4           Total Nbr of BINs for Lot                  00950064
    P21ABINS DS    2500CL7                                                  00960064
    P21ALEND EQU   *                                                        00970064
             ORG   P21ABINS      Redefine the list for TPAD                 00980064
    P21ATPL@ EQU   *             Start of TPAD List for Longwa2             00990064
    P21ATPB  DS    (2187)CL8     2187 8-Byte Elements                       01000064
             DS    CL4           Filler                                     01010064
    P21ATPL  EQU   P21ATPL@,*-P21ATPL@  Define Start and Length             01020064
             ORG   P21ATPB       Element Breakdown                          01030064
    P21ATPBN DS    CL7           BIN                                        01040064
    P21ATPST DS    CL1           BIN STATUS                                 01050064
             ORG   P21ATPL+L'P21ATPL   Point To End of List                 01060064
    P21ALLEN EQU   P21ALEND-P2BAL1A    Length of Long P2BAL1A               01070064
    P21ATPLN EQU   P21ALEND-P2BAL1A    Length of TPAD Long P2BAL1A          01080064
                                                                            01090064
    **********************************************************************  01100064
    ******                                                                  01110064
             ORG   P2BAL1A           RESET LOCATION FOR FN 1/1E EXTENDED    01120064
    ******                                                                  01130064
    **********************************************************************  01140064
                                                                            01150064
    P2EXKEY  DS    CL21          ACCESS KEY                                 01160064
    P2EXCPAR DS    CL1           CONTINUOUS PARITY INDICATOR                01170064
    P2EXLHNS DS    CL11          LOW HOUSE NUMBER                           01180064
    P2EXHHNS DS    CL11          HIGH HOUSE NUMBER                          01190064
    P2EXLGC  DS    CL2           DCP Prefered LGC                           01200064
    P2EX#STL DS    CL1           NUMBER OF CROSS STREETS AT LOW END         01210064
    P2EXCDEL DS    CL30          UP TO FIVEPB5SC'S FOR LOW END              01220064
    P2EX#STH DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        01230064
    P2EXCDEH DS    CL30          UP TO FIVE B5SC'S FOR HIGH END             01240064
    P2EXLBOR DS    CL1           LION BOROUGH CODE                          01250064
    P2EXFACE DS    CL4           LION FACE CODE                             01260064
    P2EXSEQ  DS    CL5           LION SEQUENCE NUMBER                       01270064
    P2EXSPAD DS    CL1           SPECIAL ADDRESS FLAG                       01280064
    P2EXSOS  DS    CL1           SIDE OF STREET INDICATOR                   01290064
    P2EXSEGL DS    CL5           SEGMENT LEGNTH                             01300064
    P2EXXCOR DS    CL7           X COORDINATE                               01310064
    P2EXYCOR DS    CL7           Y COORDINATE                               01320064
    P2EXZCOR DS    CL7           Z Coordinate - Not Impl.                   01330064
    P2EXRES1 DS    CL1           RESERVED FOR DCP/GSS USE                   01340064
    P2EXMHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             01350064
    P2EXSLA  DS    CL1           STREET LIGHT AREA                          01360064
    P2EXCD   DS   0CL3           COMMUNITY DISTRICT                         01370064
    P2EXCDB  DS    CL1           COMMUNITY DISTRICT BORO                    01380064
    P2EXCDN  DS    CL2           COMMUNITY DISTRICT NUMBER                  01390064
    P2EXZIP  DS    CL5           ZIP CODE                                   01400064
    P2EXEED  DS    CL3           ELECTION DISTRICT                          01410064
    P2EXEAD  DS    CL2           ASSEMBLY DISTRICT                          01420064
    P2EXESED DS    CL1           SPLIT E.D. FLAG                            01430064
    P2EXECON DS    CL2           CONGRESSIONAL DISTRICT                     01440064
    P2EXESEN DS    CL2           SENATORIAL DISTRICT                        01450064
    P2EXECIV DS    CL2           CIVIL COURT DISTRICT                       01460064
    P2EXECOU DS    CL2           CITY COUNCIL DISTRICT                      01470064
    *                                                                       01480064
    P2EXHCD  DS    CL2           HEALTH CODE DISTRICT                       01490064
    P2EXHA   DS    CL4           HEALTH AREA                                01500064
    P2EXSAND DS    CL3           SANITATION DISTRICT                        01510064
    P2EXSANT DS    CL2           SANITATION DEPT SUBSECTION                 01520064
    P2EXSREG DS    CL5           SANITATION REGULAR PICK-UP                 01530064
    P2EXSREC DS    CL3           SANITATION RECYCLE PICK-UP                 01540064
    P2EXPOL  DS    0CL4          POLICE DISTRICT                            01550064
    P2EXPBC  DS    CL1           POLICE PATROL BORO COMMAND                 01560064
    P2EXPOP  DS    CL3           POLICE PRECINCT                            01570064
    P2EXFS   DS    CL2           FIRE DIVISION                              01580064
    P2EXFB   DS    CL2           FIRE BATTALION                             01590064
    P2EXFC   DS   0CL4           FIRE COMPANY                               01600064
    P2EXFCT  DS    CL1           FIRE COMPANY TYPE                          01610064
    P2EXFCN  DS    CL3           FIRE COMPANY NUMBER                        01620064
             DS    CL1           FILLER-WAS SPLIT SCHOOL DIST               01630064
    P2EXSCH  DS    CL2           SCHOOL DISTRICT                            01640064
    P2EXCPB  DS    CL3           DYNAMIC BLOCK/ATOMIC POLYGON               01650064
    P2EXPPB  DS    CL2           Police Patrol Borough                      01660064
    P2EXFEAT DS    CL1           Feature Type Code                          01670064
    P2EXSTC  DS    CL1           SEGMENT TYPE CODE                          01680064
    P2EXALX  DS    CL1           A=Segment split by Alley                   01690064
    *                            X=Cross Streets modified                   01700064
    P2EXCSC  DS    CL1           Coincident Segment Count                   01710064
             DS    CL2           Filler                                     01720064
    P2EXCTB  DS    CL1           CENSUS TRACT BORO USED FOR GRIDGEN         01730064
    P2EXCT90 DS    CL6           1990 CENSUS TRACT                          01740064
    P2EXCT10 DS    CL6           2010 CENSUS TRACT                          01750064
    P2EXBL10 DS    CL4           2010 CENSUS BLOCK                          01760064
    P2EXBLS1 DS    CL1           2010 CENSUS BLOCK SUFFIX NOT IMPLEMENTED   01770064
    P2EXT00  DS    CL6           2000 CENSUS TRACT                          01780064
    P2EXB00  DS    CL4           2000 CENSUS BLOCK                          01790064
    P2EXS00  DS    CL1           2000 CENSUS BLOCK SUFFIX                   01800064
    P2EXNTA  DS    CL4           NEIGHBORHOOD TABULATION AREA               01810064
    P2EXSP   DS    CL1           SANITATION STREET SNOW PRIORITY            01820064
    P2EXSORG DS    CL5           SANITATION ORGANIC PICK UP                 01830064
    P2EXSBLK DS    CL5           SANITATION BULK PICK UP                    01831069
    *        DS    CL5           SANITATION RESERVED                        01840070
    P2EXHZ   DS    CL2           HURRICANE EVACUATION ZONE-OEM              01850064
             DS    CL11          FILLER                                     01860064
    P2EXUHNS DS    CL11          Underlying HNS                             01870064
    P2EXB7SC DS    CL8           "True" Borough 7 Digit Street Code         01880064
    P2EXSEGT DS    CL7           Segment Identifier                         01890064
    P2EXCURV DS    CL1           Curve Flag                                 01900064
    P2EXLGCS DS    CL8           List of 4 LGCs                             01910064
    P2EXBOEP DS    CL1           BOE LGC Pointer                            01920064
    P2EXAZM  DS    CL3           Segment Azimuth                            01930064
    P2EXORN  DS    CL1           Segment Orientation                        01940064
    P2EXXCL  DS    CL7           X Coordinate, Low Address end              01950064
    P2EXYCL  DS    CL7           Y Coordinate, Low Address end              01960064
    P2EXZCL  DS    CL7           Z Coordinate, Low Address Not Impl         01970064
    P2EXXCH  DS    CL7           X Coordinate, Hi Address end               01980064
    P2EXYCH  DS    CL7           Y Coordinate, Hi Address end               01990064
    P2EXZCH  DS    CL7           Z Coordinate, Hi Address Not Impl          02000064
    P2EXXCC  DS    CL7           X Coordinate, Center Curve                 02010064
    P2EXYCC  DS    CL7           Y Coordinate, Center Curve                 02020064
    P2EXZCC  DS    CL7           Z Coordinate, Center Curve Not Impl        02030064
    P2EXRAD  DS    CL7           Radius of Circle                           02040064
    P2EXSEC  DS    CL1           Secant Location Related to Curve           02050064
    P2EXBETA DS    CL5           Angle to From Node                         02060064
    P2EXALFA DS    CL5           Angle to To Node                           02070064
    P2EXFNOD DS    CL7           From LION Node Id                          02080064
    P2EXTNOD DS    CL7           To LION Node Id                            02090064
    P2EXLVA  DS    CL10          LION Key for Vanity Address                02100064
    P2EXSVA  DS    CL1           Side of Street for Vanity Address          02110064
    P2EXSLH  DS    CL11          Split Low House Number                     02120064
    P2EXTD   DS    CL1           Traffic Direction                          02130064
    P2EXTR   DS    CL10          Turn Restrictions                          02140064
    P2EXFRC  DS    CL3           Fraction for Curve Calculation             02150064
    P2EXRT   DS    CL2           Roadway Type                               02160064
    P2EXPID  DS    CL7           Physical Id                                02170064
    P2EXGID  DS    CL7           Generic Id                                 02180064
    P2EXPDID DS    CL7           For DCP Use Only                           02190064
    P2EXFDID DS    CL7           For DCP Use Only                           02200064
    P2EXBLN2 DS    CL2           Bike Lane 2 (has 2 byte numeric value)     02201068
    P2EXBTD  DS    CL2           Bike Traffic Direction                     02202072
             DS    CL3           filler                                     02210071
    P2EXSTS  DS    CL1           Street Status                              02220064
    P2EXSTW  DS    CL3           Street Width                               02230064
    P2EXSTWI DS    CL1           Street Width Irregular (Y/N)               02240064
    P2EXBLN  DS    CL1           Bike Lane                                  02250064
    P2EXFCC  DS    CL2           Federal Classification Code                02260064
    P2EXROW  DS    CL1           Right of Way Type                          02270064
    P2EXSLGC DS    CL10          Set of Second LGCs                         02280064
    P2EXLSID DS    CL7           Legacy Segment ID                          02290064
    P2EXFPL1 DS    CL10          From Preferred LGCs First Set of 5         02300064
    P2EXTPL1 DS    CL10          To Preferred LGCs First Set of 5           02310064
    P2EXFPL2 DS    CL10          From Preferred LGCs Second Set of 5        02320064
    P2EXTPL2 DS    CL10          To Preferred LGCs Second Set of 5          02330064
    P2EXNCR  DS    CL1           No Cross Street Calc Flag                  02340064
    P2EXISL  DS    CL5           Individual Segment Length                  02350064
    P2EXNTAN DS    CL75          NTA Name                                   02360064
    P2EXUSPS DS    CL25          USPS PREFERRED CITY NAME                   02370064
    P2EXLAT  DS    CL9           LATITUDE                                   02380064
    P2EXLONG DS    CL11          LONGITUDE                                  02390064
    P2EXSFRN DS    CL7           SEGMENT FROM NODE                          02400064
    P2EXSTON DS    CL7           SEGMENT TO NODE                            02410064
    P2EXFXYZ DS    CL21          XYZ COORD (SEGMENT FROM XYZ)               02420064
    P2EXTXYZ DS    CL21          XYZ COORD (SEGMENT TO XYZ)                 02430064
    P2EXBFID DS    CL10          NEW location blockface_id because of       02460064
    *                            length changed V16.1                       02470064
    P2EX#TRL DS    CL2           nbr of traveling lanes                     02480064
    P2EX#PKL DS    CL2           nbr of parking lanes                       02490064
    P2EX#TLL DS    CL2           nbr of total lanes on street               02500067
    P2EXSTWX DS    CL3           Street Width-Maximum                       02501068
             DS    CL252         Filler                                     02510067
    P2EXRC   DS    CL1           REASON CODE                                02520064
    P2EXRCQ  DS    CL1           REASON CODE QUALIFIER                      02530064
    P2EXWC   DS    CL2           WARNING CODE FILLER                        02540064
    P2EXGRC  DS    CL2           GEOSUPPORT RETURN CODE                     02550064
    P2EX#SL  DS    CL1           NUMBER OF CROSS STREETS AT LOW END         02560064
    P2EX7SL  DS    CL40          UP TO 5 B7SC'S FOR LOW END                 02570064
    P2EX#SH  DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        02580064
    P2EX7SH  DS    CL40          UP TO 5 B7SC'S FOR HIGH END                02590064
    P2EXSNL  DS    CL160         UP TO 5 STREET NAMES FOR LOW END           02600064
    P2EXSNH  DS    CL160         UP TO 5 STREET NAMES FOR HIGH END          02610064
    P2EXBPC  DS    CL8           BOE PREFERRED B7SC STREET CODE             02620064
    P2EXBPN  DS    CL32          BOE PREFERRED STREET NAME                  02630064
    P2EXFIL  DS    CL52          Filler                                     02640064
    *                                                                       02650064
    P2EXEND  EQU   *                                                        02660064
    P2EXLEN  EQU   P2EXEND-P2BAL1A  LENGTH OF P21EX WORKAREA 2              02670064
    *                                                                       02680064
                                                                            02690064
    **********************************************************************  02700064
    ******                                                                  02710064
             ORG   P2BAL1A             RESET LOCATION FOR FN 1A EXTENDED    02720064
    ******                                                                  02730064
    **********************************************************************  02740064
                                                                            02750064
    P2AXKEY  DS    CL21          Internal Use Only                          02760064
    P2AXCPIN DS    CL1           CONTINUOUS PARITY INDICATOR                02770064
    P2AXHSEL DS    CL11          LOW HOUSE NUMBER ON BLOCK - HNS Form       02780064
    P2AXALT1 DS   0CL11          Alternate Key                              02790064
    P2AXBOR1 DS    CL1           ALTERNATE KEY - BORO                       02800064
    P2AXTXB1 DS    CL5           ALTERNATE KEY - TAX BLOCK                  02810064
    P2AXTXL1 DS    CL4           ALTERNATE KEY - TAX LOT                    02820064
             DS    CL1              Future Use                              02830064
    P2AXRSCC DS    CL1           RPAD SCC                                   02840064
             DS    CL1           FILLER                                     02850064
    P2AXGLI  DS   0CL13          GENERAL LOT INFO                           02860064
    P2AXRBLC DS    CL2           RPAD BUILDING CLASSIFICATION               02870064
    P2AXCORC DS    CL2           CORNER CODE                                02880064
    P2AX#STC DS    CL4           TOTAL NUMBER STRUCTURES                    02890064
    P2AX#BFA DS    CL2           TOTAL NUMBER BLOCKFACES                    02900064
    P2AXINTF DS    CL1           INTERIOR LOT FLAG                          02910064
    P2AXVACF DS    CL1           VACANT LOT FLAG                            02920064
    P2AXIRLF DS    CL1           IRREGULARLY-SHAPED LOT FLAG                02930064
    *                                                                       02940064
    P2AXABFL DS    CL1           Marble Hill/ Rikers ALTERNATE BORO FLAG    02950064
    P2AXOVFL DS    CL1           Address Overflow Flag                      02960064
    *                                                                       02970064
    P2AXSTRK DS    CL19          STROLLING KEY - FILLER                     02980064
    *                                                                       02990064
    P2AXRFIU DS    CL1           RESERVED FOR INTERNAL USE                  03000064
    P2AXBIN  DS    CL7           BUILDING IDENTIFICATION NUMBER (BIN)       03010064
    *                            Condo Information                          03020064
    P2AXCONF DS    CL1           CONDO LOT FLAG                             03030064
             DS    CL1           Filler for Future Use                      03040064
    P2AXRCO# DS    CL4           RPAD CONDO NUMBER                          03050064
             DS    CL7           Future Use - Condo Unit Number             03060064
    P2AXCBBL DS    CL11          CONDO BILLING BBL                          03070064
    P2AXCBBS DS    CL1           CONDO BILLING BBL SCC                      03080064
    P2AXCLBL DS    CL11          CONDO LOW BBL                              03090064
    P2AXCHBL DS    CL11          CONDO HIGH BBL                             03100064
             DS    CL15          Filler                                     03110064
    P2AXCOOP DS    CL4           Co-op Number                               03120064
    *                                                                       03130064
    P2AXSBVP DS    CL8           SANDBORN BOROUGH/VOLUME/PAGE               03140064
    *                                                                       03150064
    P2AXBUSA DS    CL5           BUSINESS AREA                              03160064
    P2AXTAXM DS    CL5           Tax Map Number - Section and Volume        03170064
             DS    CL4           Reserved for Tax Map Page                  03180064
             DS    CL3              FILLER                                  03190064
    P2AXLAT  DS    CL9           LATITUDE                                   03200064
    P2AXLONG DS    CL11          LONGITUDE                                  03210064
    P2AXXCO  DS    CL7           X Coordinate of Annotation Point           03220064
    P2AXYCO  DS    CL7           Y Coordinate of Annotation Point           03230064
    P2AXBID  DS    CL6           Business Improvement District              03240064
    P2AXTPBS DS    CL1           TPAD BIN Status                            03250064
    P2AXTPNB DS    CL7           TPAD New BIN                               03260064
    P2AXTPNS DS    CL1           TPAD New BIN Status                        03270064
    P2AXTPCF DS    CL1           TPAD Conflict Flag                         03280064
             DS    CL9           FILLER                                     03290064
             DS    CL8           Internal Use - LGCS                        03300064
    P2AXRC   DS    CL1           REASON CODE                                03310064
    P2AXRCQ  DS    CL1           REASON CODE QUALIFIER                      03320064
    P2AXWC   DS    CL2           WARNING CODE FILLER                        03330064
    P2AXGRC  DS    CL2           GEOSUPPORT RETURN CODE                     03340064
             DS    CL108         FILLER                                     03350064
    P2AX#ADR DS    CL4           TOTAL ADDRESSES FOR LOT                    03360064
    P2AXLIST DS   0CL116         LIST OF ADDRESSES, MAXIMUM OF 21           03370064
    P2AXLOW# DS    CL16          LOW HOUSE NUMBER-Display Form              03380064
    P2AXHI#  DS    CL16          HIGH HOUSE NUMBER-Display Form             03390064
    P2AXBCDE DS    CL1           Borough Code                               03400064
    P2AXCODE DS    CL5           STREET CODE                                03410064
    P2AXPLGC DS    CL2           Preferred LGC                              03420064
    P2AXLBIN DS    CL7           BIN                                        03430064
    P2AXLSOS DS    CL1           Side of Street Indicator                   03440064
    P2AXATP  DS    CL1           Address Type Flag                          03450064
    P2AXATPS DS    CL1           TPAD BIN Status                            03460064
    P2AXSTN  DS    CL32          STREET NAME                                03470064
             DS    CL34          FILLER                                     03480064
    *  STORAGE IS RESERVED FOR THE REMAINING 20 ADDRESS STRUCTURES.         03490064
    *  EACH STRUCTURE IS IDENTICAL TO THE ONE DEFINED ABOVE.                03500064
             DS    CL2320        REMAINING ADDRESSES                        03510064
    P2AXEND  EQU   *                                                        03520064
    P2AXLEN  EQU   P2AXEND-P2BAL1A  LENGTH OF P21A EXTEND WORKAREA 2        03530064
    *                                                                       03540064
                                                                            03550064
    **********************************************************************  03560064
    ******                                                                  03570064
             ORG   P2BAL1A             RESET LOCATION FOR FN 1B             03580064
    ******                                                                  03590064
    **********************************************************************  03600064
    P21BKEY  DS    CL21          ACCESS KEY                                 03610064
    P21BCPAR DS    CL1           CONTINUOUS PARITY INDICATOR                03620064
    P21BLHNS DS    CL11          LOW HOUSE NUMBER                           03630064
    P21BHHNS DS    CL11          HIGH HOUSE NUMBER                          03640064
    P21BLGC  DS    CL2           DCP PREFERREDLGC (FN 1) - BOE (FN 1E)      03650064
    P21B#STL DS    CL1           NUMBER OF CROSS STREETS AT LOW END         03660064
    P21BCDEL DS    CL30          UP TO FIVEPB5SC'S FOR LOW END              03670064
    P21B#STH DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        03680064
    P21BCDEH DS    CL30          UP TO FIVE B5SC'S FOR HIGH END             03690064
    P21BLBOR DS    CL1           LION BOROUGH CODE                          03700064
    P21BFACE DS    CL4           LION FACE CODE                             03710064
    P21BSEQ  DS    CL5           LION SEQUENCE NUMBER                       03720064
    P21BSPAD DS    CL1           SPECIAL ADDRESS FLAG                       03730064
    P21BSOS  DS    CL1           SIDE OF STREET INDICATOR                   03740064
    P21BSEGL DS    CL5           SEGMENT LEGNTH                             03750064
    P21BXCOR DS    CL7           X COORDINATE                               03760064
    P21BYCOR DS    CL7           Y COORDINATE                               03770064
    P21BZCOR DS    CL7           Z Coordinate - Not Impl.                   03780064
    P21BRES1 DS    CL1           RESERVED FOR DCP/GSS USE                   03790064
    P21BMHRI DS    CL1           MARBLE HILL/RIKERS ISLAND FLAG             03800064
    P21BSLA  DS    CL1           STREET LIGHT AREA                          03810064
    P21BCD   DS   0CL3           COMMUNITY DISTRICT                         03820064
    P21BCDB  DS    CL1           COMMUNITY DISTRICT BORO                    03830064
    P21BCDN  DS    CL2           COMMUNITY DISTRICT NUMBER                  03840064
    P21BZIP  DS    CL5           ZIP CODE                                   03850064
    P21BEED  DS    CL3           ELECTION DISTRICT                          03860064
    P21BEAD  DS    CL2           ASSEMBLY DISTRICT                          03870064
    P21BESED DS    CL1           SPLIT E.D. FLAG                            03880064
    *                 Next four fields are valid only for Fn 1E             03890064
    P21BECON DS    CL2           CONGRESSIONAL DISTRICT                     03900064
    P21BESEN DS    CL2           SENATORIAL DISTRICT                        03910064
    P21BECIV DS    CL2           CIVIL COURT DISTRICT                       03920064
    P21BECOU DS    CL2           CITY COUNCIL DISTRICT                      03930064
    *                                                                       03940064
    P21BHCD  DS    CL2           HEALTH CODE DISTRICT                       03950064
    P21BHA   DS    CL4           HEALTH AREA                                03960064
    P21BSAND DS    CL3           SANITATION DISTRICT                        03970064
    P21BSANT DS    CL2           SANITATION DEPT SUBSECTION                 03980064
    P21BSREG DS    CL5           SANITATION REGULAR PICK-UP                 03990064
    P21BSREC DS    CL3           SANITATION RECYCLE PICK-UP                 04000064
    P21BPOL  DS    0CL4          POLICE DISTRICT                            04010064
    P21BPBC  DS    CL1           POLICE PATROL BORO COMMAND                 04020064
    P21BPOP  DS    CL3           POLICE PRECINCT                            04030064
    P21BFS   DS    CL2           FIRE DIVISION                              04040064
    P21BFB   DS    CL2           FIRE BATTALION                             04050064
    P21BFC   DS   0CL4           FIRE COMPANY                               04060064
    P21BFCT  DS    CL1           FIRE COMPANY TYPE                          04070064
    P21BFCN  DS    CL3           FIRE COMPANY NUMBER                        04080064
    P21BFILS DS    CL1           FILLER_WAS SPLIT SCHOOL DISTRICT FLAG      04090064
    P21BSCH  DS    CL2           SCHOOL DISTRICT                            04100064
    P21BCPB  DS    CL3           DYNAMIC BLOCK/ATOMIC POLYGON               04110064
    P21BPPB  DS    CL2           Police Patrol Borough                      04120064
    P21BFEAT DS    CL1           FEATURE TYPE CODE                          04130064
    P21BSTC  DS    CL1           SEGMENT TYPE CODE                          04140064
    P21BALX  DS    CL1           A=Segment split by Alley                   04150064
    *                            X=Cross Streets modified                   04160064
    P21BCSC  DS    CL1           COINCIDENT SEGMENT COUNT                   04170064
             DS    CL2           Filler                                     04180064
    P21BCTB  DS    CL1           CENSUS TRACT BORO USED FOR GRIDGEN         04190064
    P21BCT90 DS    CL6           1990 CENSUS TRACT                          04200064
    P21BCT10 DS    CL6           2010 CENSUS TRACT                          04210064
    P21BBL10 DS    CL4           2010 CENSUS BLOCK                          04220064
    P21BBLS1 DS    CL1           2010 CENSUS BLOCK SUFFIX NOT IMPLEMENTED   04230064
    P21BT00  DS    CL6           2000 CENSUS TRACT                          04240064
    P21BB00  DS    CL4           2000 CENSUS BLOCK                          04250064
    P21BS00  DS    CL1           2000 CENSUS BLOCK SUFFIX                   04260064
    P21BNTA  DS    CL4           NEIGHBORHOOD TABULATION AREA               04270064
    P21BSP   DS    CL1           SANITATION STREET SNOW PRIORITY            04280064
    P21BSORG DS    CL5           SANITATION ORGANIC PICK UP                 04290064
    P21BSBLK DS    CL5           SANITATION BULK PICK UP                    04291069
    *        DS    CL5           SANITATION RESERVED                        04300070
    P21BHZ   DS    CL2           HURRICANE EVACUATION ZONE-OEM              04310064
             DS    CL11          FILLER                                     04320064
    P21BUHNS DS    CL11          Underlying HNS                             04330064
    P21BB7SC DS    CL8           "True" Borough 7 Digit Street Code         04340064
    P21BSEGT DS    CL7           Segment Identifier                         04350064
    P21BCURV DS    CL1           Curve Flag                                 04360064
    P21BLGCS DS    CL8           List of 4 LGCs                             04370064
    P21BBOEP DS    CL1           BOE LGC Pointer                            04380064
    P21BAZM  DS    CL3           Segment Azimuth                            04390064
    P21BORN  DS    CL1           Segment Orientation                        04400064
    P21BXCL  DS    CL7           X Coordinate, Low Address end              04410064
    P21BYCL  DS    CL7           Y Coordinate, Low Address end              04420064
    P21BZCL  DS    CL7           Z Coordinate, Low Address Not Impl         04430064
    P21BXCH  DS    CL7           X Coordinate, Hi Address end               04440064
    P21BYCH  DS    CL7           Y Coordinate, Hi Address end               04450064
    P21BZCH  DS    CL7           Z Coordinate, Hi Address Not Impl          04460064
    P21BXCC  DS    CL7           X Coordinate, Center Curve                 04470064
    P21BYCC  DS    CL7           Y Coordinate, Center Curve                 04480064
    P21BZCC  DS    CL7           Z Coordinate, Center Curve Not Impl        04490064
    P21BRAD  DS    CL7           Radius of Circle                           04500064
    P21BSEC  DS    CL1           Secant Location Related to Curve           04510064
    P21BBETA DS    CL5           Angle to From Node                         04520064
    P21BALFA DS    CL5           Angle to To Node                           04530064
    P21BFNOD DS    CL7           From LION Node Id                          04540064
    P21BTNOD DS    CL7           To LION Node Id                            04550064
    P21BLVA  DS    CL10          LION Key for Vanity Address                04560064
    P21BSVA  DS    CL1           Side of Street for Vanity Address          04570064
    P21BSLH  DS    CL11          Split Low House Number                     04580064
    P21BTD   DS    CL1           Traffic Direction                          04590064
    P21BTR   DS    CL10          Turn Restrictions                          04600064
    P21BFRC  DS    CL3           Fraction for Curve Calculation             04610064
    P21BRT   DS    CL2           Roadway Type                               04620064
    P21BPID  DS    CL7           Physical Id                                04630064
    P21BGID  DS    CL7           Generic Id                                 04640064
    P21BPDID DS    CL7           For DCP Use Only                           04650064
    P21BFDID DS    CL7           For DCP Use Only                           04660064
    P21BBLN2 DS    CL2           Bike Lane 2 (has 2 bytes numeric value)    04661068
    P21BBTD  DS    CL2           Bike Traffic Direction                     04662072
             DS    CL3           Filler                                     04670071
    P21BSTS  DS    CL1           Street Status                              04680064
    P21BSTW  DS    CL3           Street Width                               04690064
    P21BSTWI DS    CL1           Street Width Irregular (Y/N)               04700064
    P21BBLN  DS    CL1           Bike Lane                                  04710064
    P21BFCC  DS    CL2           Federal Classification Code                04720064
    P21BRTP  DS    CL1           Row Type                                   04730064
    P21BSLGC DS    CL10          Set of Second LGCs                         04740064
    P21BLSID DS    CL7           Legacy Segment ID                          04750064
    P21BFPL1 DS    CL10          From Preferred LGCs First Set of 5         04760064
    P21BTPL1 DS    CL10          To Preferred LGCs First Set of 5           04770064
    P21BFPL2 DS    CL10          From Preferred LGCs Second Set of 5        04780064
    P21BTPL2 DS    CL10          To Preferred LGCs Second Set of 5          04790064
    P21BNCR  DS    CL1           No Cross Street Calc Flag                  04800064
    P21BISL  DS    CL5           Individual Segment Length                  04810064
    P21BNTAN DS    CL75          NTA Name                                   04820064
    P21BUSPS DS    CL25          USPS PREFERRED CITY NAME                   04830064
    P21B1LAT DS    CL9           LATITUDE                                   04840064
    P21B1LON DS    CL11          LONGITUDE                                  04850064
    P21BSFRN DS    CL7           SEGMENT FROM NODE                          04860064
    P21BSTON DS    CL7           SEGMENT TO NODE                            04870064
    P21BFXYZ DS    CL21          XYZ COORD (SEGMENT FROM XYZ)               04880064
    P21BTXYZ DS    CL21          XYZ COORD (SEGMENT TO XYZ)                 04890064
    P21BBFID DS    CL10          NEW location blockface_id because of       04891065
    *                            length changed V16.1                       04892065
    P21B#TRL DS    CL2           nbr of traveling lanes                     04893065
    P21B#PKL DS    CL2           nbr of parking lanes                       04894065
    P21B#TLL DS    CL2           nbr of total lanes                         04895065
    P21BSTWX DS    CL3           Street Width Maximum                       04895168
             DS    CL252         Filler                                     04896068
    P21BRC   DS    CL1           REASON CODE                                04910064
    P21BRC1  DS    CL1           REASON CODE QUALIFIER                      04920064
    P21BWC   DS    CL2           WARNING CODE FILLER                        04930064
    P21BGRC  DS    CL2           GEOSUPPORT RETURN CODE                     04940064
    P21B#SL  DS    CL1           NUMBER OF CROSS STREETS AT LOW END         04950064
    P21B7SL  DS    CL40          UP TO 5 B7SC'S FOR LOW END                 04960064
    P21B#SH  DS    CL1           NUMBER OF CROSS STREETS AT HIGH END        04970064
    P21B7SH  DS    CL40          UP TO 5 B7SC'S FOR HIGH END                04980064
    P21BSNL  DS    CL160         UP TO 5 STREET NAMES FOR LOW END           04990064
    P21BSNH  DS    CL160         UP TO 5 STREET NAMES FOR HIGH END          05000064
    P21BBP7  DS    CL8           BOE PREFERRED B7SC                         05010064
    P21BBSN  DS    CL32          BOE PREFERRED STREET NAME                  05020064
             DS    CL52          Filler                                     05030064
    *                                                                       05040064
             DS    CL21          Internal Use Only                          05050064
    P21BCPIN DS    CL1           CONTINUOUS PARITY INDICATOR                05060064
    P21BHSEL DS    CL11          LOW HOUSE NUMBER ON BLOCK - HNS Form       05070064
    P21BALT1 DS   0CL11          Alternate Key    Y                         05080064
    P21BBOR1 DS    CL1           ALTERNATE KEY - BORO                       05090064
    P21BTXB1 DS    CL5           ALTERNATE KEY - TAX BLOCK                  05100064
    P21BTXL1 DS    CL4           ALTERNATE KEY - TAX LOT                    05110064
             DS    CL1              Future Use                              05120064
    P21BRSCC DS    CL1           RPAD SCC                                   05130064
             DS    CL1           FILLER                                     05140064
    P21BGLI  DS   0CL13          GENERAL LOT INFO                           05150064
    P21BRBLC DS    CL2           RPAD BUILDING CLASSIFICATION               05160064
    P21BCORC DS    CL2           CORNER CODE                                05170064
    P21B#STC DS    CL4           TOTAL NUMBER STRUCTURES                    05180064
    P21B#BFA DS    CL2           TOTAL NUMBER BLOCKFACES                    05190064
    P21BINTF DS    CL1           INTERIOR LOT FLAG                          05200064
    P21BVACF DS    CL1           VACANT LOT FLAG                            05210064
    P21BIRLF DS    CL1           IRREGULARLY-SHAPED LOT FLAG                05220064
    *                                                                       05230064
    P21BABFL DS    CL1           Marble Hill/ Rikers ALTERNATE BORO FLAG    05240064
    P21BOVFL DS    CL1           Address Overflow Flag                      05250064
    *                                                                       05260064
    P21BSTRK DS    CL19          STROLLING KEY - FILLER                     05270064
    *                                                                       05280064
    P21BRFIU DS    CL1           RESERVED FOR INTERNAL USE                  05290064
    P21BBIN  DS    CL7           BUILDING IDENTIFICATION NUMBER (BIN)       05300064
    *                            Condo Information                          05310064
    P21BCONF DS    CL1           CONDO LOT FLAG                             05320064
             DS    CL1           Filler for Future Use                      05330064
    P21BRCO# DS    CL4           RPAD CONDO NUMBER                          05340064
             DS    CL7           Future Use - Condo Unit Number             05350064
    P21BCBBL DS    CL11          CONDO BILLING BBL                          05360064
    P21BCBBS DS    CL1           CONDO BILLING BBL SCC                      05370064
    P21BCLBL DS    CL11          CONDO LOW BBL                              05380064
    P21BCHBL DS    CL11          CONDO HIGH BBL                             05390064
             DS    CL15          Filler                                     05400064
    P21BCOOP DS    CL4           Co-op Number                               05410064
    *                                                                       05420064
    P21BSBVP DS    CL8           SANDBORN BOROUGH/VOLUME/PAGE               05430064
    *                                                                       05440064
    P21BBUSA DS    CL5           BUSINESS AREA                              05450064
    P21BTAXM DS    CL5           Tax Map Number - Section and Volume        05460064
             DS    CL4           Reserved for Tax Map Page                  05470064
             DS    CL3              FILLER                                  05480064
    P21BALAT DS    CL9           LATITUDE                                   05490064
    P21BALON DS    CL11          LONGITUDE                                  05500064
    P21BXCO  DS    CL7           X Coordinate of Annotation Point           05510064
    P21BYCO  DS    CL7           Y Coordinate of Annotation Point           05520064
    P21BBID  DS    CL6           Business Improvement District              05530064
    P21BTPBS DS    CL1           TPAD BIN Status                            05540064
    P21BTPNB DS    CL7           TPAD New BIN                               05550064
    P21BTPNS DS    CL1           TPAD New BIN Status                        05560064
    P21BTPCF DS    CL1           TPAD Conflict Flag                         05570064
             DS    CL9           FILLER                                     05580064
             DS    CL8           Internal Use - LGCS                        05590064
    P21BRCS2 DS    CL1           REASON CODE                                05600064
    P21BRCQ2 DS    CL1           REASON CODE QUALIFIER                      05610064
    P21BWC2  DS    CL2           WARNING CODE FILLER                        05620064
    P21BGRC2 DS    CL2           GEOSUPPORT RETURN CODE                     05630064
             DS    CL108         FILLER                                     05640064
    P21B#ADR DS    CL4           TOTAL ADDRESSES FOR LOT                    05650064
    P21BLIST DS   0CL116         LIST OF ADDRESSES, MAXIMUM OF 21           05660064
    P21BLOW# DS    CL16          LOW HOUSE NUMBER-Display Form              05670064
    P21BHI#  DS    CL16          HIGH HOUSE NUMBER-Display Form             05680064
    P21BBCDE DS    CL1           Borough Code                               05690064
    P21BCODE DS    CL5           STREET CODE                                05700064
    P21BPLGC DS    CL2           Preferred LGC                              05710064
    P21BLBIN DS    CL7           BIN                                        05720064
    P21BLSOS DS    CL1           Side of Street Indicator                   05730064
    P21BATP  DS    CL1           Address Type Flag                          05740064
    P21BATPS DS    CL1           TPAD BIN Status                            05750064
    P21BSTN  DS    CL32          STREET NAME                                05760064
             DS    CL34          FILLER                                     05770064
    *  STORAGE IS RESERVED FOR THE REMAINING 20 ADDRESS STRUCTURES.         05780064
    *  EACH STRUCTURE IS IDENTICAL TO THE ONE DEFINED ABOVE.                05790064
             DS    CL2320        REMAINING ADDRESSES                        05800064
    P21BEND  EQU   *                                                        05810064
    P21BLEN  EQU   P21BEND-P2BAL1A LENGTH OF P21B WORKAREA 2                05820064
    *                                                                       05830064
             ORG  ,                                                         05840064
    **********************************************************************  05850064


## <span id="appendix14.11"><center>P2BAL3S COPY File</center></span>

    */********************************************************************/ 00000100
    */*****  THIS IS GEOSUPPORT INFORMATION SYSTEM COPY FILE P2BAL3S,  ***/ 00000200
    */*****  CONTAINING THE LAYOUT OF WORK AREA 2 FOR FUNCTION 3S.     ***/ 00000300
    */********************************************************************/ 00000400
    */******         Last Modified - 3 April 2002                      ***/ 00000502
    */********************************************************************/ 00000602
    P2BAL3S  DS   0H                                                        00000700
    P23SAKEY DS   0CL21          ACCESS KEY                                 00000800
             DS    CL2           Internal Use Only                          00000900
    P23SPORS DS    CL1           P=Primary, S=Secondary                     00001000
    P23SBORO DS    CL1           Borough Code                               00001100
    P23S5SC  DS    CL5           Street Code                                00001200
    P23SLGC  DS    CL2           Blank if P in P23SPORS                     00001300
             DS    CL10          Internal use Only                          00001400
    P23S#INT DS    CL3           NUMBER OF INTERSECTIONS ON STRETCH         00001500
    *                            Up to 350 Intersections                    00001600
    *P23SINT  DS    0CL87        INTERSECTION LAYOUT                        00001700
    P23SINT  DS    0CL55         INTERSECTION LAYOUT                        00001800
    P23SMHRI DS    CL1           Marble Hill / Rikers Island Flag           00001900
    P23SDIST DS    CL5           DISTANCE IN FEET FROM PREVIOUS INTERSECT.  00002000
    P23SGAPF DS    CL1           GAP FLAG ("G" IF NO SEGMENT CONNECTS THIS  00002100
    *                            INTERSECTION TO THE PREVIOUS ONE)          00002200
    P23SNODE DS    CL7           Node Number                                00002301
    P23S#ST  DS    CL1           Number of Streets intersecting (max 5)     00002400
    P23SCDE1 DS    CL8           NUMERICALLY SMALLEST B7SC                  00002503
    P23SCDE2 DS    CL8           NUMERICALLY 2ND SMALLEST B7SC              00002603
    P23SCDE3 DS    CL8           Remaining Street Codes in any order        00002700
    P23SCDE4 DS    CL8                                                      00002800
    P23SCDE5 DS    CL8                                                      00002900
    P23SREST DS    CL19195      REMAINING INTERSECTIONS Assuming Max size   00003402
    P23SEND  EQU   *                                                        00003500
    P23SLEN  EQU   P23SEND-P2BAL3S     LENGTH OF P2BAL3S                    00003600  


## <span id="appendix14.12"><center>P2BALAP COPY File</center></span>  

    */********************************************************************/ 00000100
    */*****  THIS IS GEOSUPPORT INFORMATION SYSTEM COPY FILE P2BALAP,  ***/ 00000260
    */*****  CONTAINING THE LAYOUT OF WORK AREA 2 FOR FUNCTION AP AND  ***/ 00000360
    */*****  APX (ADDRESS POINT AND AP EXTENDED).   TLV 3/2015  V15.2  ***/ 00001260
    */********************************************************************/ 00001315
    P2BALAP  DS   0H                                                        00001760
             DS    CL21                                                     00001815
    P2APCPAR DS    CL1           CONTINUOUS PARITY INDICATOR                00001960
    P2APHSEL DS    CL11          LOW HOUSE NUMBER ON BLOCK - HNS FORM       00002060
    P2APALT1 DS   0CL11          ALTERNATE KEY                              00002160
    P2APBOR1 DS    CL1           ALTERNATE KEY - BORO                       00002260
    P2APTXB1 DS    CL5           ALTERNATE KEY - TAX BLOCK                  00002360
    P2APTXL1 DS    CL4           ALTERNATE KEY - TAX LOT                    00002460
             DS    CL1              Future Use                              00002515
             DS    CL1           FILLER FOR FUNC AP                         00002661
             DS    CL1           FILLER                                     00002715
    P2APGLI  DS   0CL13          GENERAL LOT INFO                           00002860
    P2APFL01 DS    CL2           FILLER FOR AP ?fields name for fillers ??  00002961
    P2APFL02 DS    CL2           FILLER FOR FUNC AP                         00003061
    P2AP#STC DS    CL4           TOTAL NUMBER STRUCTURES                    00003160
    P2APFL03 DS    CL2           FILLER FOR FUNC AP ?                       00003261
    P2APFL04 DS    CL1           FILLER FOR FUNC AP ?                       00003361
    P2APFL05 DS    CL1           FILLER FOR FUNC AP ?                       00003461
    P2APFL06 DS    CL1           FILLER FOR FUNC AP                         00003561
    *                                                                       00003615
             DS    CL1           FILLER FOR FUNC AP                         00003761
             DS    CL1           FILLER FOR FUNC AP                         00003861
    *                                                                       00003915
             DS    CL19          FILLER FOR FUNC AP                         00004061
    *                                                                       00004115
    P2APRFIU DS    CL1           RESERVED FOR INTERNAL USE                  00004260
    P2APBIN  DS    CL7           BUILDING IDENTIFICATION NUMBER (BIN)       00004360
    *                          Condo Information                            00004463
    P2APCONF DS    CL1           CONDO LOT FLAG                             00004560
             DS    CL1           Filler for Future Use                      00004615
    P2APRCO# DS    CL4           RPAD CONDO NUMBER                          00004760
             DS    CL7           Future Use - Condo Unit Number             00004815
    P2APCBBL DS    CL11          CONDO BILLING BBL                          00005063
             DS    CL1           FILLER FOR FUNC AP                         00005161
    P2APCLBL DS    CL11          CONDO LOW BBL                              00005260
    P2APCHBL DS    CL11          CONDO HIGH BBL                             00005360
             DS    CL15          Filler                                     00005415
    P2APCOOP DS    CL4           CO-OP NUMBER                               00005560
    *                                                                       00005615
             DS    CL8           FILLER FOR FUNC AP                         00005761
    *                                                                       00005815
             DS    CL5           FILLER FOR FUNCTION AP                     00005961
             DS    CL5           FILLER FOR FUNCTION AP                     00006061
             DS    CL4           FILLER                                     00006161
             DS    CL3           FILLER                                     00006261
    P2APLAT  DS    CL9           LATITUDE                                   00006360
    P2APLONG DS    CL11          LONGITUDE                                  00006460
    P2APXCO  DS    CL7           X COORDINATE OF ANNOTATION POINT           00006560
    P2APYCO  DS    CL7           Y COORDINATE OF ANNOTATION POINT           00006660
             DS    CL6           FILLER FOR FUNC AP                         00006761
             DS    CL1           FILLER FOR FUNC AP                         00006861
             DS    CL7           FILLER FOR FUNC AP                         00006961
             DS    CL1           FILLER FOR FUNC AP                         00007061
             DS    CL1           FILLER FOR FUNC AP                         00007162
    P2APAPID DS    CL9           ADDRESS POINT ID                           00007367
             DS    CL8           Internal Use                               00007461
    P2AP#ADR DS    CL4           TOTAL ADDRESSES FOR LOT                    00007561
    P2APLIST DS   0CL1113        LIST OF ADDRESSES, MAXIMUM OF 21           00007661
    P2APLOW# DS    CL16          LOW HOUSE NUMBER-Display Form              00007761
    P2APHI#  DS    CL16          HIGH HOUSE NUMBER-DISPLAY FORM             00007863
    P2APBCDE DS    CL1           Borough Code                               00007961
    P2APCODE DS    CL5           STREET CODE                                00008061
    P2APPLGC DS    CL2           Preferred LGC                              00008161
    P2APLBIN DS    CL7           BIN                                        00008261
    P2APLSOS DS    CL1           Side of Street Indicator                   00008361
    P2APATP  DS    CL1           Address Type Flag                          00008461
             DS    CL1           FILLER FOR FUNC AP                         00008562
             DS    CL3           FILLER                                     00008661
    *  STORAGE IS RESERVED FOR THE REMAINING 20 ADDRESS STRUCTURES.         00008761
    *  EACH STRUCTURE IS IDENTICAL TO THE ONE DEFINED ABOVE.                00008861
             DS    CL1060        REMAINING ADDRESSES                        00008961
    P2APSEND EQU   *                                                        00009061
    P2APSLEN EQU   P2APSEND-P2BALAP    LENGTH OF P2BALAP                    00009162
                                                                            00021016
    **********************************************************************  01222016
    ******                                                                  01223016
             ORG   P2BALAP             RESET LOCATION FOR FN AP EXTENDED    01224062
    ******                                                                  01225016
    **********************************************************************  01226016
    P2PXKEY  DS    CL21          INTERNAL USE ONLY                          01226166
    P2PXCPAR DS    CL1           CONTINUOUS PARITY INDICATOR                01226366
    P2PXHSEL DS    CL11          LOW HOUSE NUMBER ON BLOCK - HNS FORM       01226466
    P2PXALT1 DS   0CL11          BBL                                        01226566
    P2PXBOR1 DS    CL1           BORO                                       01226666
    P2PXTXB1 DS    CL5           TAX BLOCK                                  01226766
    P2PXTXL1 DS    CL4           TAX LOT                                    01226866
             DS    CL1              Future Use                              01226963
             DS    CL1           FILLER FOR FUNC AP                         01227063
             DS    CL1           FILLER                                     01227163
    P2PXGLI  DS   0CL13          GENERAL LOT INFO                           01227266
    P2PXFL01 DS    CL2           FILLER FOR AP ?FIELDS NAME FOR FILLERS ??  01227366
    P2PXFL02 DS    CL2           FILLER FOR FUNC AP                         01227466
    P2PX#STC DS    CL4           TOTAL NUMBER STRUCTURES                    01227566
    P2PXFL03 DS    CL2           FILLER FOR FUNC AP ?                       01227666
    P2PXFL04 DS    CL1           FILLER FOR FUNC AP ?                       01227766
    P2PXFL05 DS    CL1           FILLER FOR FUNC AP ?                       01227866
    P2PXFL06 DS    CL1           FILLER FOR FUNC AP                         01227966
    *                                                                       01228063
             DS    CL1           FILLER FOR FUNC AP                         01228163
             DS    CL1           FILLER FOR FUNC AP                         01228263
    *                                                                       01228363
             DS    CL19          FILLER FOR FUNC AP                         01228463
    *                                                                       01228563
    P2PXRFIU DS    CL1           RESERVED FOR INTERNAL USE                  01228666
    P2PXBIN  DS    CL7           BUILDING IDENTIFICATION NUMBER (BIN)       01228766
    *                          Condo Information                            01228863
    P2PXCONF DS    CL1           CONDO LOT FLAG                             01228966
             DS    CL1           Filler for Future Use                      01229063
    P2PXRCO# DS    CL4           RPAD CONDO NUMBER                          01229166
             DS    CL7           Future Use - Condo Unit Number             01229263
    P2PXCBBL DS    CL11          CONDO BILLING BBL                          01229366
             DS    CL1           FILLER FOR FUNC AP                         01229463
    P2PXCLBL DS    CL11          CONDO LOW BBL                              01229566
    P2PXCHBL DS    CL11          CONDO HIGH BBL                             01229666
             DS    CL15          Filler                                     01229763
    P2PXCOOP DS    CL4           CO-OP NUMBER                               01229866
    *                                                                       01229963
             DS    CL8           FILLER FOR FUNC AP                         01230063
    *                                                                       01230163
             DS    CL5           FILLER FOR FUNCTION AP                     01230263
             DS    CL5           FILLER FOR FUNCTION AP                     01230363
             DS    CL4           FILLER                                     01230463
             DS    CL3           FILLER                                     01230563
    P2PXLAT  DS    CL9           LATITUDE                                   01230666
    P2PXLONG DS    CL11          LONGITUDE                                  01230766
    P2PXXCO  DS    CL7           X COORDINATE OF ANNOTATION POINT           01230866
    P2PXYCO  DS    CL7           Y COORDINATE OF ANNOTATION POINT           01230966
             DS    CL6           FILLER FOR FUNC AP                         01231063
             DS    CL1           FILLER FOR FUNC AP                         01231163
             DS    CL7           FILLER FOR FUNC AP                         01231263
             DS    CL1           FILLER FOR FUNC AP                         01231363
             DS    CL1           FILLER FOR FUNC AP                         01231463
    P2PXAPID DS    CL9           ADDRESS POINT ID                           01231667
             DS    CL8           Internal Use - LGCs                        01231764
    P2PXRC   DS    CL1           REASON CODE                                01231866
    P2PXRCQ  DS    CL1           REASON CODE QUALIFIER                      01231966
    P2PXWC   DS    CL2           WARNING CODE FILLER                        01232066
    P2PXGRC  DS    CL2           GEOSUPPORT RETURN CODE                     01232166
             DS    CL108         FILLER                                     01232264
    P2PX#ADR DS    CL4           TOTAL ADDRESSES FOR LOT                    01232966
    P2PXLIST DS   0CL116         LIST OF ADDRESSES, MAXIMUM OF 21           01233066
    P2PXLOW# DS    CL16          LOW HOUSE NUMBER-DISPLAY FORM              01233166
    P2PXHI#  DS    CL16          HIGH HOUSE NUMBER-DISPLAY FORM             01233266
    P2PXBCDE DS    CL1           BOROUGH CODE                               01233366
    P2PXCODE DS    CL5           STREET CODE                                01233466
    P2PXPLGC DS    CL2           PREFERRED LGC                              01233566
    P2PXLBIN DS    CL7           BIN                                        01233666
    P2PXLSOS DS    CL1           SIDE OF STREET INDICATOR                   01233766
    P2PXATP  DS    CL1           ADDRESS TYPE FLAG                          01233866
             DS    CL1           FILLER FOR FUNC AP                         01233963
    P2PXSTN  DS    CL32          STREET NAME                                01234066
             DS    CL34          FILLER                                     01234164
    *  STORAGE IS RESERVED FOR THE REMAINING 20 ADDRESS STRUCTURES.         01234263
    *  EACH STRUCTURE IS IDENTICAL TO THE ONE DEFINED ABOVE.                01234363
             DS    CL1060        REMAINING ADDRESSES                        01234463
    P2PXSEND EQU   *                                                        01234566
    P2PXSLEN EQU   P2APSEND-P2BALAP   LENGTH OF P2AP EXTEND WORKAREA 2      01234666
    *                                                                       01234764
             ORG  ,                                                         01269362
    **********************************************************************  01269516


## <span id="appendix14.13"><center>PL/1 COPY Files (COW)</center><span>  

## <span id="appendix14.14"><center>P1PL1 COPY File</center></span>


    /*******************************************************************/ 00000100
    /** ADDED 'UNIT' FIELDS TO WA1                  YNL 10/16  V16.4 ***/ 00000227
    /***  THIS IS THE PL/1 STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM  ***/ 00000300
    /***  INDEPENDENT WORK AREA 1.                                   ***/ 00000400
    /***  COPY FILE - P1PL1.                                         ***/ 00000500
    /***                                                  04/07/98   ***/ 00000600
    /**                      LAST UPDATED OCTOBER  2016               **/ 00000729
    /*******************************************************************/ 00000825
     DCL PP1 POINTER;                                                     00000925
     DCL                                                                  00001025
       1 P1PL1,                                                           00001125
         /***********************************************/                00001225
         /*****           INPUT  FIELDS             *****/                00001325
         /***********************************************/                00001425
         2 PIWA1_IN_FUNCTION_CODE,                                        00001525
           3 PIWA1_IN_FUNCTION_1             CHAR(1),                     00001625
           3 PIWA1_IN_FUNCTION_2             CHAR(1),                     00001725
         2 PIWA1_IN_HOUSENUM_DISPLAY         CHAR(16),                    00001825
         2 PIWA1_IN_HOUSENUM_SORT            CHAR(11),                    00001925
         2 PIWA1_IN_LOW_HOUSENUM_DISPLAY     CHAR(16),                    00002025
         2 PIWA1_IN_LOW_HOUSENUM_SORT        CHAR(11),                    00002125
         2 PIWA1_IN_BORO_1                   CHAR(1),                     00002225
         2 PIWA1_IN_10SC_1                   CHAR(10),                    00002325
         2 PIWA1_IN_STREET_1                 CHAR(32),                    00002425
         2 PIWA1_IN_BORO_2                   CHAR(1),                     00002525
         2 PIWA1_IN_10SC_2                   CHAR(10),                    00002625
         2 PIWA1_IN_STREET_2                 CHAR(32),                    00002725
         2 PIWA1_IN_BORO_3                   CHAR(1),                     00002825
         2 PIWA1_IN_10SC_3                   CHAR(10),                    00002925
         2 PIWA1_IN_STREET_3                 CHAR(32),                    00003025
         2 PIWA1_IN_BBL,                                                  00003125
           3 PIWA1_IN_BBL_BORO               CHAR(1),                     00003225
           3 PIWA1_IN_BLOCK                  CHAR(5),                     00003325
           3 PIWA1_IN_LOT                    CHAR(4),                     00003425
           3 PIWA1_IN_LOT_VER                CHAR(1),                     00003525
         2 PIWA1_IN_BIN                      CHAR(7),                     00003625
         2 PIWA1_IN_COMPASS                  CHAR(1),                     00003725
         2 PIWA1_IN_COMPASS2                 CHAR(1),                     00003825
         2 PIWA1_IN_NODE                     CHAR(7),  /*NODE INPUT FN 2*/00003923
         2 PIWA1_IN_PLATFORM_INDICATOR       CHAR(1),                     00004009
         2 PIWA1_IN_ZIPIN                    CHAR(5),                     00004112
         2 PIWA1_IN_UNIT                     CHAR(14),                    00004227
         2 FILLER_200                        CHAR(82),                    00004327
     /** 2 FILLER_200  *** V16.4 ***         CHAR(96)  ****/              00004427
         2 PIWA1_IN_LONG_WORKAREA2_FLAG      CHAR(1), /*L=LONG */         00004527
         2 PIWA1_IN_HSE_NBR_JUSTIFY          CHAR(1),                     00004627
         2 PIWA1_IN_HNL                      CHAR(2), /* NI */            00004727
         2 PIWA1_IN_HSE_OVER_FLAG            CHAR(1),                     00004827
         2 PIWA1_IN_SNL                      CHAR(2),                     00004927
         2 PIWA1_IN_SN_NORM_FORMAT           CHAR(1), /*C=COMPACT */      00005027
                                                      /*S OR ' '=SORT*/   00005127
         2 PIWA1_IN_EXPANDED_FORMAT          CHAR(1),                     00005227
         2 PIWA1_IN_ROADBED_REQ_SWITCH       CHAR(1),                     00005327
         2 PIWA1_IN_INTERNAL_USE_LEGACY      CHAR(1),                     00005427
         2 PIWA1_IN_SEGAUX_SWITCH            CHAR(1),                     00005527
         2 PIWA1_IN_BROWSE_FLAG              CHAR(1),                     00005627
         2 PIWA1_IN_REAL_STREET_ONLY         CHAR(1),  /* FN 3S */        00005727
         2 PIWA1_IN_TPAD_SWITCH              CHAR(1),  /*FN 1A-BL-BN*/    00005827
         2 PIWA1_IN_MODE_SWITCH              CHAR(1),  /*FN 1-1E-1A-*/    00005927
                                                       /*FN BL-BN-3-3C*/  00006027
                                                       /*X=EXTENDED */    00006127
         2 PIWA1_IN_WTO_SWITCH               CHAR(1),  /*N=NO WTO*/       00006227
         2 FILLER_400                        CHAR(29),                    00006327
         /***********************************************/                00006427
         /*****            OUTPUT  FIELDS           *****/                00006527
         /***********************************************/                00006627
         2 PIWA1_OUT_BORONAME                CHAR(9),                     00006727
         2 PIWA1_OUT_HOUSENUM_DISPLAY        CHAR(16),                    00006827
         2 PIWA1_OUT_HOUSENUM_SORT           CHAR(11),                    00006927
         2 PIWA1_OUT_B10SC_1                 CHAR(11),                    00007027
         2 PIWA1_OUT_STREET_1                CHAR(32),                    00007127
         2 PIWA1_OUT_B10SC_2                 CHAR(11),                    00007227
         2 PIWA1_OUT_STREET_2                CHAR(32),                    00007327
         2 PIWA1_OUT_B10SC_3                 CHAR(11),                    00007427
         2 PIWA1_OUT_STREET_3                CHAR(32),                    00007527
         2 PIWA1_OUT_BBL,                                                 00007627
           3 PIWA1_OUT_BBL_BORO              CHAR(1),                     00007727
           3 PIWA1_OUT_BLOCK                 CHAR(5),                     00007827
           3 PIWA1_OUT_LOT                   CHAR(4),                     00007927
         2 PIWA1_OUT_LOT_VER                 CHAR(1),                     00008027
         2 PIWA1_OUT_LO_HOUSENUM_DISPLAY     CHAR(16),                    00008127
         2 PIWA1_OUT_LO_HOUSENUM_SORT        CHAR(11),                    00008227
         2 PIWA1_OUT_BIN                     CHAR(7),                     00008327
         2 PIWA1_OUT_STREET_ATTR(3)          CHAR(1),                     00008427
         2 PIWA1_OUT_REASON_CODE_2           CHAR(1),                     00008527
         2 PIWA1_OUT_REASON_CODE_QUAL_2      CHAR(1), /*TPAD 2ND REASON*/ 00008627
                                                      /*CODE QUALIFIER */ 00008727
         2 PIWA1_OUT_WARNING_CODE_2          CHAR(2),                     00008827
         2 PIWA1_OUT_RETURN_CODE_2           CHAR(2),                     00008927
         2 PIWA1_OUT_ERROR_MESSAGE_2         CHAR(80),                    00009027
         2 PIWA1_OUT_NODE                    CHAR(7),  /*NODE NORMALIZED*/00009127
         2 PIWA1_OUT_UNIT_SORT,                                           00009227
           3 PIWA1_OUT_UNIT_TYPE             CHAR(4),                     00009327
           3 PIWA1_OUT_UNIT_ID               CHAR(10),                    00009427
         2 PIWA1_OUT_UNIT_DISP               CHAR(14),                    00009527
         2 FILLER_550                        CHAR(17),                    00009728
     /** 2 FILLER_550   *** V16.4  ***       CHAR(39)  ***/               00009827
     /** 2 FILLER_555                        CHAR(6),  ***/               00009928
         2 PIWA1_OUT_SND_ATTR                CHAR(1),                     00010027
         2 PIWA1_OUT_REASON_CODE             CHAR(1),                     00010127
         2 PIWA1_OUT_REASON_CODE_QUAL        CHAR(1), /*TPAD REASON   */  00010227
                                                      /*CODE QUALIFIER*/  00010327
         2 PIWA1_OUT_WARNING_CODE            CHAR(2),                     00010427
         2 PIWA1_OUT_RETURN_CODE             CHAR(2),                     00010527
         2 PIWA1_OUT_ERROR_MESSAGE           CHAR(80),                    00010627
         2 PIWA1_OUT_NUM_SIMILAR_STRS        CHAR(2),                     00010727
         2 PIWA1_OUT_SIMILAR_B7SC(10)        CHAR(8),                     00010827
         2 PIWA1_OUT_SIMILAR_NAMES(10)       CHAR(32);                    00010927
                                                                          00011027
     DCL PIWA1_IN_FUNC_CODE                  CHAR(2)                      00011127
                    BASED(ADDR(PIWA1_IN_FUNCTION_CODE));                  00011227
                                                                          00011327
     DCL WORK1PL1   BASED(PP1)               CHAR(1200);                  00012027
     PP1=ADDR(P1PL1);                                                     00020018



## <span id="appendix14.15"><center>P2PL1 COPY File</center></span>  

    /*******************************************************************/ 00010099
    /***                      P2PL1                                  ***/ 00011099
    /***           LAST MODIFIED DECEMBER 2016                       ***/ 00012099
    /*  ADD NEW 2 BYTE BIKE TRAFFIC DIRECTION           YNL 12/16 V17,1*/ 00015099
    /*  ADD NEW 2 BYTE BIKE LANE AND MAX STR WIDTH      YNL 10/16 V16.4*/ 00015199
    /*                                                                 */ 00016099
    /***  THIS IS THE PL/1 STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM  ***/ 00030099
    /***  INDEPENDENT WORK AREA 2 FOR FUNCTIONS: 1, 1E, 2, 2C, 3,    ***/ 00040099
    /***   AND 5.                                                    ***/ 00050099
    /***  ADDED 3 EXTENDED AND 3C EXTENDED            MEB   6/11     ***/ 00060099
    /***  ADDED 2 WIDE                                MEB   3/14     ***/ 00070099
    /***                                                             ***/ 00080099
    /***  COPY FILE - P2PL1.                                         ***/ 00090099
    /***  PLEASE NOTE THAT FUNCTIONS 1 AND 1E SHARE A SINGLE         ***/ 00100099
    /***  WORK AREA 2 LAYOUT, AND FUNCTIONS 2 AND 2C ALSO            ***/ 00110099
    /***  SHARE A SINGLE WORK AREA 2 LAYOUT.              12/30/97   ***/ 00120099
    /*******************************************************************/ 00130099
    DCL PP2 POINTER;                                                       00140099
    DCL P2PL1             CHAR(10000) INIT(' ');                           00150099
                                                                          00160099
                                                                          00170099
    /*******************************************************************/ 00180099
    /*******     FOR: FUNCTIONS 1 & 1E     *****************************/ 00190099
    DCL                                                                    00200099
     1 PIWA2_FUNCTION1   BASED(PP2),                                      00210099
       2 PIWA2_FN1_ACCESS_KEY               CHAR(21),                     00220099
       2 PIWA2_FN1_CONT_PARITY              CHAR(1),/*(OR DUP ADDR IND)*/ 00230099
       2 PIWA2_FN1_LOW_HOUSENUM             CHAR(11),/* SORT FORMAT */    00240099
       2 PIWA2_FN1_HI_HOUSENUM              CHAR(11),/* SORT FORMAT */    00250099
       2 PIWA2_FN1_PREF_LGC                 CHAR(2),                      00260099
       2 PIWA2_FN1_NUM_X_ST_LOW_END         CHAR(1),                      00270099
       2 PIWA2_FN1_LOW_B5SC(5)              CHAR(6),                      00280099
       2 PIWA2_FN1_NUM_X_ST_HI_END          CHAR(1),                      00290099
       2 PIWA2_FN1_HI_B5SC(5)               CHAR(6),                      00300099
       2 PIWA2_FN1_LIONKEY,                                               00310099
         3 PIWA2_FN1_LION_BORO              CHAR(1),                      00320099
         3 PIWA2_FN1_LION_FACECODE          CHAR(4),                      00330099
         3 PIWA2_FN1_LION_SEQ               CHAR(5),                      00340099
       2 PIWA2_FN1_SPECIAL_ADDR_FLAG        CHAR(1),                      00350099
       2 PIWA2_FN1_SIDE_OF_STR              CHAR(1),                      00360099
       2 PIWA2_FN1_SEG_LEN                  CHAR(5),                      00370099
       2 PIWA2_FN1_XCOORD                   CHAR(7),                      00380099
       2 PIWA2_FN1_YCOORD                   CHAR(7),                      00390099
       2 FILLER_100                         CHAR(7), /* FOR ZCOORD */     00400099
       2 FILLER_200                         CHAR(1), /* FOR GSS USE*/     00410099
       2 PIWA2_FN1_MARBLE_RIKERS_FLAG       CHAR(1),                      00420099
       2 PIWA2_FN1_DOT_SLA                  CHAR(1),                      00430099
       2 PIWA2_FN1_COM_DIST,                                              00440099
         3 PIWA2_FN1_COM_DIST_BORO          CHAR(1),                      00450099
         3 PIWA2_FN1_COM_DIST_NUM           CHAR(2),                      00460099
       2 PIWA2_FN1_ZIP                      CHAR(5),                      00470099
                                                                          00480099
       2 PIWA2_FN1E_ELECT_DIST              CHAR(3), /*****************/  00490099
       2 PIWA2_FN1E_ASSEM_DIST              CHAR(2), /* THE FNIE      */  00500099
       2 PIWA2_FN1E_SPLIT_ED_FLAG           CHAR(1), /* FIELDS ARE    */  00510099
       2 PIWA2_FN1E_CONG_DIST               CHAR(2), /* VALID ONLY FOR*/  00520099
       2 PIWA2_FN1E_SENATE_DIST             CHAR(2), /* FUNCTION 1E,  */  00530099
       2 PIWA2_FN1E_COURT_DIST              CHAR(2), /* NOT FUNC 1.   */  00540099
       2 PIWA2_FN1E_COUNCIL_DIST            CHAR(2), /*****************/  00550099
                                                                          00560099
       2 PIWA2_FN1_HEALTH_CENTER_DIST       CHAR(2), /* HEALTH CENTR*/    00570099
       2 PIWA2_FN1_HEALTH_AREA              CHAR(4), /* HEALTH AREA*/     00580099
       2 PIWA2_FN1_SANI_DIST,                                             00590099
         3 PIWA2_FN1_SANI_DIST_BORO         CHAR(1),                      00600099
         3 PIWA2_FN1_SANI_DIST_NUM          CHAR(2),                      00610099
       2 PIWA2_FN1_SANI_SUBSEC              CHAR(2),                      00620099
       2 PIWA2_FN1_SANI_REG                 CHAR(5),                      00630099
       2 PIWA2_FN1_SANI_REC                 CHAR(3),                      00640099
       2 PIWA2_FN1_POLICE_DIST,                                           00650099
         3  PIWA2_FN1_POL_PAT_BORO_CMD      CHAR(1),                      00660099
         3  PIWA2_FN1_POL_PRECINCT          CHAR(3),                      00670099
       2 PIWA2_FN1_FIRE_DIV                 CHAR(2),                      00680099
       2 PIWA2_FN1_FIRE_BAT                 CHAR(2),                      00690099
       2 PIWA2_FN1_FIRE_CO,                                               00700099
         3 PIWA2_FN1_FIRE_CO_TYPE           CHAR(1),                      00710099
         3 PIWA2_FN1_FIRE_CO_NUM            CHAR(3),                      00720099
       2 PIWA2_FN1_FILL_DIST_SPLIT_FLAG     CHAR(1),  /*WAS SPLIT SC*/    00730099
       2 PIWA2_FN1_SCHL_DIST                CHAR(2),                      00740099
       2 PIWA2_FN1_DYN_BLK                  CHAR(3),  /*ATOMIC POLYGON*/  00750099
       2 PIWA2_FN1_POLICE_PAT_BORO          CHAR(2),                      00760099
       2 PIWA2_FN1_FEATURE_TYPE             CHAR(1),                      00770099
       2 PIWA2_FN1_SEGMENT_TYPE             CHAR(1),                      00780099
       2 PIWA2_FN1_ALX                      CHAR(1),                      00790099
       2 PIWA2_FN1_COINCIDENT_SEG_CTR       CHAR(1),                      00800099
       2 FILLER_290                         CHAR(2),                      00810099
       2 PIWA2_FN1_CENS_TRCT_BORO           CHAR(1), /*USED FOR GRIDGEN*/ 00820099
       2 PIWA2_FN1_1990_CENS_TRCT           CHAR(6),                      00830099
       2 PIWA2_FN1_2010_CENSUS_TRACT        CHAR(6),                      00840099
       2 PIWA2_FN1_2010_CENSUS_BLOCK        CHAR(4),                      00850099
       2 PIWA2_FN1_2010_CENSUS_BLK_SF       CHAR(1), /*NOT IMPLEMENTED*/  00860099
       2 PIWA2_FN1_2000_CENS_TRACT          CHAR(6),                      00870099
       2 PIWA2_FN1_2000_CENS_BLOCK          CHAR(4),                      00880099
       2 PIWA2_FN1_2000_CENS_BLOCK_SUF      CHAR(1),                      00890099
       2 PIWA2_FN1_NTA                      CHAR(4), /*NEIGHBORHOOD    */ 00900099
                                                     /*TABULATION AREA */ 00910099
       2 PIWA2_FN1_SANIT_SNOW_PRIORITY      CHAR(1), /*SANITATION STRT */ 00920099
                                                     /*SNOW PRIORITY   */ 00930099
       2 PIWA2_FN1_SANIT_ORGANICS           CHAR(5), /*SANITATION      */ 00940099
                                                     /*ORGANIC PICKUP  */ 00950099
       2 PIWA2_FN1_SANIT_BULK_PICK_UP       CHAR(5), /*SANITATION BULK */ 00960099
    /** 2 PIWA2_FN1_SANIT_RESERVED *V16.4*   CHAR(5), /*SANITATION RESRV*/ 00961099
       2 PIWA2_FN1_HURRICANE_ZONE           CHAR(2), /*OEM HURRICANE   */ 00970099
                                                     /*EVACUATION ZONE */ 00980099
       2 FILLER_300                         CHAR(11),                     00990099
       2 PIWA2_FN1_UHNS                     CHAR(11),                     01000099
       2 PIWA2_FN1_REAL_B7SC                CHAR(8),                      01010099
       2 PIWA2_FN1_SEGMENT_ID               CHAR(7),                      01020099
       2 PIWA2_FN1_CURVE_FLAG               CHAR(1);                      01030099
                                                                          01040099
    DCL   PIWA2_FN1_COMDIST                  CHAR(3)                       01050099
           BASED(ADDR(PIWA2_FN1_COM_DIST));                               01060099
    DCL   PIWA2_FN1_SANIDIST                 CHAR(3)                       01070099
           BASED(ADDR(PIWA2_FN1_SANI_DIST));                              01080099
    DCL   PIWA2_FN1_POLDIST                  CHAR(4)                       01090099
           BASED(ADDR(PIWA2_FN1_POLICE_DIST));                            01100099
                                                                          01110099
                                                                          01120099
    /*******************************************************************/ 01130099
    /*******     FOR: FUNCTIONS 2 & 2C     *****************************/ 01140099
    DCL                                                                    01150099
     1 PIWA2_FUNCTION2   BASED(PP2),                                      01160099
       2 PIWA2_FN2_ACCESS_KEY               CHAR(21),                     01170099
       2 PIWA2_FN2_DUP_INTERSECT_FLAG       CHAR(1),                      01180099
       2 PIWA2_FN2_PREF_LGC1                CHAR(2),                      01190099
       2 PIWA2_FN2_PREF_LGC2                CHAR(2),                      01200099
       2 PIWA2_FN2_NUM_OF_INTERSECTS        CHAR(1),                      01210099
       2 PIWA2_FN2_INTERSECT_B5SC(5)        CHAR(6),                      01220099
       2 PIWA2_FN2_COMPDIR                  CHAR(1),                      01230099
       2 PIWA2_FN2_ATOMIC_POLYGON           CHAR(3),                      01240099
       2 FILLER_350                         CHAR(2),                      01250099
       2 PIWA2_FN2_LIONNODENUM              CHAR(7),                      01260099
       2 PIWA2_FN2_XCOORD                   CHAR(7),                      01270099
       2 PIWA2_FN2_YCOORD                   CHAR(7),                      01280099
       2 FILLER_400                         CHAR(7), /* FOR ZCOORD */     01290099
       2 PIWA2_FN2_SANBORN1,                                              01300099
         3 PIWA2_FN2_SANBORN1_BORO          CHAR(1),                      01310099
         3 PIWA2_FN2_SANBORN1_VOL           CHAR(3),                      01320099
         3 PIWA2_FN2_SANBORN1_PAGE          CHAR(4),                      01330099
       2 PIWA2_FN2_SANBORN2,                                              01340099
         3 PIWA2_FN2_SANBORN2_BORO          CHAR(1),                      01350099
         3 PIWA2_FN2_SANBORN2_VOL           CHAR(3),                      01360099
         3 PIWA2_FN2_SANBORN2_PAGE          CHAR(4),                      01370099
       2 PIWA2_FN2_MARBLE_RIKERS_FLAG       CHAR(1),                      01380099
       2 PIWA2_FN2_DOT_SLA                  CHAR(1),                      01390099
       2 PIWA2_FN2_COM_DIST,                                              01400099
         3 PIWA2_FN2_COM_DIST_BORO          CHAR(1),                      01410099
         3 PIWA2_FN2_COM_DIST_NUM           CHAR(2),                      01420099
       2 PIWA2_FN2_ZIP                      CHAR(5),                      01430099
       2 PIWA2_FN2_HEALTH_AREA              CHAR(4),  /*HEALTH AREA*/     01440099
       2 PIWA2_FN2_POLICE_DIST,                                           01450099
         3  PIWA2_FN2_POL_PAT_BORO_CMD      CHAR(1),                      01460099
         3  PIWA2_FN2_POL_PRECINCT          CHAR(3),                      01470099
       2 PIWA2_FN2_FIRE_DIV                 CHAR(2),                      01480099
       2 PIWA2_FN2_FIRE_BAT                 CHAR(2),                      01490099
       2 PIWA2_FN2_FIRE_CO,                                               01500099
         3 PIWA2_FN2_FIRE_CO_TYPE           CHAR(1),                      01510099
         3 PIWA2_FN2_FIRE_CO_NUM            CHAR(3),                      01520099
       2 PIWA2_FN2_SCHL_DIST                CHAR(2),                      01530099
       2 PIWA2_FN2_2010_CENSUS_TRACT        CHAR(6),                      01540099
       2 PIWA2_FN2_1990_CENS_TRCT           CHAR(6),                      01550099
       2 PIWA2_FN2_LEVEL_CODES(5,2)         CHAR(1),                      01560099
       2 PIWA2_FN2_POLICE_PAT_BORO          CHAR(2),                      01570099
       2 PIWA2_FN2_ASSEM_DIST               CHAR(2),                      01580099
       2 PIWA2_FN2_CONG_DIST                CHAR(2),                      01590099
       2 PIWA2_FN2_SENATE_DIST              CHAR(2),                      01600099
       2 PIWA2_FN2_COURT_DIST               CHAR(2),                      01610099
       2 PIWA2_FN2_COUNCIL_DIST             CHAR(2),                      01620099
       2 PIWA2_FN2_CD_ELIGIBLE              CHAR(1),                      01630099
       2 PIWA2_FN2_DUP_INTERSECT_DIST       CHAR(5),                      01640099
       2 PIWA2_FN2_2000_CENS_TRACT          CHAR(6),                      01650099
       2 PIWA2_FN2_HEALTH_CENTER_DIST       CHAR(2), /*HEALTH CENTER*/    01660099
       2 PIWA2_FN2_SANITATION_DIST          CHAR(3),                      01670099
       2 PIWA2_FN2_SANITATION_SUBSEC        CHAR(2),                      01680099
       2 FILLER_500                         CHAR(12);                     01690099
                                                                          01700099
    DCL   PIWA2_FN2_COMDIST                  CHAR(3)                       01710099
           BASED(ADDR(PIWA2_FN2_COM_DIST));                               01720099
    DCL   PIWA2_FN2_POLDIST                  CHAR(4)                       01730099
           BASED(ADDR(PIWA2_FN2_POLICE_DIST));                            01740099
    DCL   PIWA2_FN2_SANBORN1_BVOLPAGE        CHAR(8)                       01750099
           BASED(ADDR(PIWA2_FN2_SANBORN1)),                               01760099
         PIWA2_FN2_SANBORN2_BVOLPAGE        CHAR(8)                       01770099
           BASED(ADDR(PIWA2_FN2_SANBORN2));                               01780099
                                                                          01790099
                                                                          01800099
    /*******************************************************************/ 01810099
    /*******     FOR: FUNCTIONS 2W         *****************************/ 01820099
    DCL                                                                    01830099
     1 PIWA2_FUNCTION2W  BASED(PP2),                                      01840099
       2 PIWA2_FN2W_ACCESS_KEY              CHAR(21),                     01850099
       2 PIWA2_FN2W_DUP_INTERSECT_FLAG      CHAR(1),                      01860099
       2 PIWA2_FN2W_PREF_LGC1               CHAR(2),                      01870099
       2 PIWA2_FN2W_PREF_LGC2               CHAR(2),                      01880099
       2 PIWA2_FN2W_NUM_OF_INTERSECTS       CHAR(1),                      01890099
       2 PIWA2_FN2W_INTERSECT_B5SC(5)       CHAR(6),                      01900099
       2 PIWA2_FN2W_COMPDIR                 CHAR(1),                      01910099
       2 PIWA2_FN2W_ATOMIC_POLYGON          CHAR(3),                      01920099
       2 PIWA2_FN2W_FILLER_350              CHAR(2),                      01930099
       2 PIWA2_FN2W_LIONNODENUM             CHAR(7),                      01940099
       2 PIWA2_FN2W_XCOORD                  CHAR(7),                      01950099
       2 PIWA2_FN2W_YCOORD                  CHAR(7),                      01960099
       2 PIWA2_FN2W_FILLER_400              CHAR(7), /* FOR ZCOORD */     01970099
       2 PIWA2_FN2W_SANBORN1,                                             01980099
         3 PIWA2_FN2W_SANBORN1_BORO         CHAR(1),                      01990099
         3 PIWA2_FN2W_SANBORN1_VOL          CHAR(3),                      02000099
         3 PIWA2_FN2W_SANBORN1_PAGE         CHAR(4),                      02010099
       2 PIWA2_FN2W_SANBORN2,                                             02020099
         3 PIWA2_FN2W_SANBORN2_BORO         CHAR(1),                      02030099
         3 PIWA2_FN2W_SANBORN2_VOL          CHAR(3),                      02040099
         3 PIWA2_FN2W_SANBORN2_PAGE         CHAR(4),                      02050099
       2 PIWA2_FN2W_MARBLE_RIKERS_FLAG      CHAR(1),                      02060099
       2 PIWA2_FN2W_DOT_SLA                 CHAR(1),                      02070099
       2 PIWA2_FN2W_COM_DIST,                                             02080099
         3 PIWA2_FN2W_COM_DIST_BORO         CHAR(1),                      02090099
         3 PIWA2_FN2W_COM_DIST_NUM          CHAR(2),                      02100099
       2 PIWA2_FN2W_ZIP                     CHAR(5),                      02110099
       2 PIWA2_FN2W_HEALTH_AREA             CHAR(4),  /*HEALTH AREA*/     02120099
       2 PIWA2_FN2W_POLICE_DIST,                                          02130099
         3  PIWA2_FN2W_POL_PAT_BORO_CMD     CHAR(1),                      02140099
         3  PIWA2_FN2W_POL_PRECINCT         CHAR(3),                      02150099
       2 PIWA2_FN2W_FIRE_DIV                CHAR(2),                      02160099
       2 PIWA2_FN2W_FIRE_BAT                CHAR(2),                      02170099
       2 PIWA2_FN2W_FIRE_CO,                                              02180099
         3 PIWA2_FN2W_FIRE_CO_TYPE          CHAR(1),                      02190099
         3 PIWA2_FN2W_FIRE_CO_NUM           CHAR(3),                      02200099
       2 PIWA2_FN2W_SCHL_DIST               CHAR(2),                      02210099
       2 PIWA2_FN2W_2010_CENSUS_TRACT       CHAR(6),                      02220099
       2 PIWA2_FN2W_1990_CENS_TRCT          CHAR(6),                      02230099
       2 PIWA2_FN2W_LEVEL_CODES(5,2)        CHAR(1),                      02240099
       2 PIWA2_FN2W_POLICE_PAT_BORO         CHAR(2),                      02250099
       2 PIWA2_FN2W_ASSEM_DIST              CHAR(2),                      02260099
       2 PIWA2_FN2W_CONG_DIST               CHAR(2),                      02270099
       2 PIWA2_FN2W_SENATE_DIST             CHAR(2),                      02280099
       2 PIWA2_FN2W_COURT_DIST              CHAR(2),                      02290099
       2 PIWA2_FN2W_COUNCIL_DIST            CHAR(2),                      02300099
       2 PIWA2_FN2W_CD_ELIGIBLE             CHAR(1),                      02310099
       2 PIWA2_FN2W_DUP_INTERSECT_DIST      CHAR(5),                      02320099
       2 PIWA2_FN2W_2000_CENS_TRACT         CHAR(6),                      02330099
       2 PIWA2_FN2W_HEALTH_CENTER_DIST      CHAR(2),                      02340099
       2 PIWA2_FN2W_SANITATION_DIST         CHAR(3),                      02350099
       2 PIWA2_FN2W_SANITATION_SUBSEC       CHAR(2),                      02360099
       2 PIWA2_FN2W_FILLER_500              CHAR(12),                     02370099
       2 PIWA2_FN2W_FILLER_GRIDGEN          CHAR(22),                     02380099
       2 PIWA2_FN2W_LGCS_FIRST_INTERSCT(4),          /*UP TO 4 LGCS FOR */02390099
         3 PIWA2_FN2W_LGC_FIRST_INTERSCT    CHAR(2), /*1ST INPUT STREET */02400099
                                                     /*IN INTERSECTION  */02410099
       2 PIWA2_FN2W_LGCS_SECOND_INTERSCT(4),         /*UP TO 4 LGCS FOR */02420099
         3 PIWA2_FN2W_LGC_SECOND_INTERSCT   CHAR(2), /*2ND INPUT STREET */02430099
                                                     /*IN INTERSECTION  */02440099
       2 PIWA2_FN2W_TURN_RESTRICTIONS(10),                                02450099
         3 PIWA2_FN2W_TURN_RESTRICTION      CHAR(1),                      02460099
       2 PIWA2_FN2W_INTERSECT_B5SC_LGCS(5),                               02470099
         3 PIWA2_FN2W_INTERSECT_B5SC_LGC    CHAR(2),                      02480099
       2 PIWA2_FN2W_TRUE_REP_COUNTER        CHAR(2),                      02490099
       2 PIWA2_FN2W_NODE_LIST(20),                                        02500099
         3 PIWA2_FN2W_NODE_LIST_NODE        CHAR(7),                      02510099
       2 PIWA2_FN2W_NODE_LIST_B7SCS_LIST(20),                             02520099
         3 PIWA2_FN2W_NODE_LIST_B7SCS(5),                                 02530099
          4 PIWA2_FN2W_NODE_LIST_B7SC(4)    CHAR(8),                      02540099
       2 PIWA2_FN2W_REASON_CODE             CHAR(1),                      02550099
       2 PIWA2_FN2W_REASON_CODE_QUAL        CHAR(1),                      02560099
       2 PIWA2_FN2W_WARN_CODE               CHAR(2),                      02570099
       2 PIWA2_FN2W_RETURN_CODE             CHAR(2),                      02580099
       2 PIWA2_FN2W_LATITUDE                CHAR(9),                      02590099
       2 PIWA2_FN2W_LONGITUDE               CHAR(11),                     02600099
       2 PIWA2_FN2W_FILLER6                 CHAR(374);                    02610099
    /* 2 PIWA2_FN2W_FILLER6    V15.3        CHAR(394)  ***/               02620099
                                                                          02630099
    DCL   PIWA2_FN2W_COMDIST                 CHAR(3)                       02640099
           BASED(ADDR(PIWA2_FN2W_COM_DIST));                              02650099
    DCL   PIWA2_FN2W_POLDIST                 CHAR(4)                       02660099
           BASED(ADDR(PIWA2_FN2W_POLICE_DIST));                           02670099
    DCL   PIWA2_FN2W_SANBORN1_BVOLPAGE       CHAR(8)                       02680099
           BASED(ADDR(PIWA2_FN2W_SANBORN1)),                              02690099
         PIWA2_FN2W_SANBORN2_BVOLPAGE       CHAR(8)                       02700099
           BASED(ADDR(PIWA2_FN2W_SANBORN2));                              02710099
                                                                          02720099
    /*******************************************************************/ 02730099
    /*******     FOR: FUNCTION 3           *****************************/ 02740099
    DCL                                                                    02750099
     1 PIWA2_FUNCTION3   BASED(PP2),                                      02760099
       2 PIWA2_FN3_ACCESS_KEY               CHAR(21),                     02770099
       2 PIWA2_FN3_DUP_KEY_FLAG             CHAR(1),/*(OR CONT PARITY)*/  02780099
       2 PIWA2_FN3_LOCATION_STATUS          CHAR(1),                      02790099
       2 PIWA2_FN3_COUNTY_BOUNDARY          CHAR(1),                      02800099
       2 PIWA2_FN3_PREF_LGC1                CHAR(2),                      02810099
       2 PIWA2_FN3_PREF_LGC2                CHAR(2),                      02820099
       2 PIWA2_FN3_PREF_LGC3                CHAR(2),                      02830099
       2 PIWA2_FN3_NUM_X_ST_LOW_END         CHAR(1),                      02840099
       2 PIWA2_FN3_LOW_B5SC(5)              CHAR(6),                      02850099
       2 PIWA2_FN3_NUM_X_ST_HI_END          CHAR(1),                      02860099
       2 PIWA2_FN3_HI_B5SC(5)               CHAR(6),                      02870099
       2 PIWA2_FN3_REVERSAL_FLAG            CHAR(1),                      02880099
       2 PIWA2_FN3_LIONKEY,                                               02890099
         3 PIWA2_FN3_LION_BORO              CHAR(1),                      02900099
         3 PIWA2_FN3_LION_FACECODE          CHAR(4),                      02910099
         3 PIWA2_FN3_LION_SEQ               CHAR(5),                      02920099
       2 PIWA2_FN3_GENREC_FLAG              CHAR(1),                      02930099
       2 PIWA2_FN3_SEG_LEN                  CHAR(5),                      02940099
       2 PIWA2_FN3_SEG_SLOPE                CHAR(3),                      02950099
       2 PIWA2_FN3_SEG_ORIENT               CHAR(1),                      02960099
       2 PIWA2_FN3_MARBLE_RIKERS_FLAG       CHAR(1),                      02970099
       2 PIWA2_FN3_FROM_TO_NODES,                                         02980099
         3 PIWA2_FN3_FROM_NODE              CHAR(7),                      02990099
         3 PIWA2_FN3_TO_NODE                CHAR(7),                      03000099
       2 PIWA2_FN3_SANIT_SNOW_PRIORITY      CHAR(1), /*SANITATION STRT */ 03010099
                                                     /*SNOW PRIORITY   */ 03020099
       2 FILLER_600                         CHAR(4),                      03030099
       2 PIWA2_FN3_SEGMENT_ID               CHAR(7),                      03040099
       2 PIWA2_FN3_DOT_SLA                  CHAR(1),                      03050099
       2 PIWA2_FN3_CURVE_FLAG               CHAR(1),                      03060099
       2 PIWA2_FN3_DOG_LEG                  CHAR(1),                      03070099
       2 PIWA2_FN3_FEATURE_TYPE             CHAR(1),                      03080099
       2 PIWA2_FN3_SEGMENT_TYPE             CHAR(1),                      03090099
       2 PIWA2_FN3_COINCIDENT_SEG_CTR       CHAR(1),                      03100099
       2 FILLER_700                         CHAR(4),                      03110099
       2 PIWA2_FN3_LEFT_SIDE_OF_STR,                                      03120099
         3 PIWA2_FN3_L_COM_DIST,                                          03130099
           4 PIWA2_FN3_L_COM_DIST_BORO      CHAR(1),                      03140099
           4 PIWA2_FN3_L_COM_DIST_NUM       CHAR(2),                      03150099
         3 PIWA2_FN3_L_LOW_HOUSENUM         CHAR(16),/*DISPLAY FORMAT*/   03160099
         3 PIWA2_FN3_L_HI_HOUSENUM          CHAR(16),/*DISPLAY FORMAT*/   03170099
         3 FILLER_800                       CHAR(33),/* FOR GSS USE*/     03180099
         3 PIWA2_FN3_L_ZIP                  CHAR(5),                      03190099
         3 PIWA2_FN3_L_HEALTH_AREA          CHAR(4), /*HEALTH AREA*/      03200099
         3 PIWA2_FN3_L_POLICE_DIST,                                       03210099
           4  PIWA2_FN3_L_POL_PAT_BORO_CMD  CHAR(1),                      03220099
           4  PIWA2_FN3_L_POL_PRECINCT      CHAR(3),                      03230099
         3 PIWA2_FN3_L_FIRE_DIV             CHAR(2),                      03240099
         3 PIWA2_FN3_L_FIRE_BAT             CHAR(2),                      03250099
         3 PIWA2_FN3_L_FIRE_CO,                                           03260099
           4 PIWA2_FN3_L_FIRE_CO_TYPE       CHAR(1),                      03270099
           4 PIWA2_FN3_L_FIRE_CO_NUM        CHAR(3),                      03280099
         3 PIWA2_FN3_L_SCHL_DIST            CHAR(2),                      03290099
         3 PIWA2_FN3_L_DYN_BLK              CHAR(3), /*ATOMIC POLYGON*/   03300099
         3 PIWA2_FN3_L_ED                   CHAR(3),                      03310099
         3 PIWA2_FN3_L_AD                   CHAR(2),                      03320099
         3 PIWA2_FN3_L_POLICE_PAT_BORO      CHAR(2),                      03330099
         3 FILLER_880                       CHAR(1),                      03340099
         3 PIWA2_FN3_L_BORO                 CHAR(1),                      03350099
         3 PIWA2_FN3_L_1990_CENS_TRCT       CHAR(6),                      03360099
         3 PIWA2_FN3_L_2010_CENSUS_TRACT    CHAR(6),                      03370099
         3 PIWA2_FN3_L_2010_CENSUS_BLOCK    CHAR(4),                      03380099
         3 PIWA2_FN3_L_2010_CENSUS_BLK_SF   CHAR(1), /*NOT IMPLEMENTED*/  03390099
         3 PIWA2_FN3_L_2000_CENSUS_TRACT    CHAR(6),                      03400099
         3 PIWA2_FN3_L_2000_CENSUS_BLOCK    CHAR(4),                      03410099
         3 PIWA2_FN3_L_2000_CENSUS_BLK_SF   CHAR(1),                      03420099
         3 FILLER_890                       CHAR(7),                      03430099
    /**  3 PIWA2_FN3_L_BLOCKFACE_ID *V16.1* CHAR(7)  **/                  03440099
         3 PIWA2_FN3_L_NTA                  CHAR(4), /*NEIGHBORHOOD    */ 03450099
                                                     /*TABULATION AREA */ 03460099
         3 FILLER_900                       CHAR(8),                      03470099
       2 PIWA2_FN3_RIGHT_SIDE_OF_STR,                                     03480099
         3 PIWA2_FN3_R_COM_DIST,                                          03490099
           4 PIWA2_FN3_R_COM_DIST_BORO      CHAR(1),                      03500099
           4 PIWA2_FN3_R_COM_DIST_NUM       CHAR(2),                      03510099
         3 PIWA2_FN3_R_LOW_HOUSENUM         CHAR(16),/*DISPLAY FORMAT*/   03520099
         3 PIWA2_FN3_R_HI_HOUSENUM          CHAR(16),/*DISPLAY FORMAT*/   03530099
         3 FILLER_1000                      CHAR(33),/*FOR GSS USE */     03540099
         3 PIWA2_FN3_R_ZIP                  CHAR(5),                      03550099
         3 PIWA2_FN3_R_HEALTH_AREA          CHAR(4), /*HEALTH AREA*/      03560099
         3 PIWA2_FN3_R_POLICE_DIST,                                       03570099
           4  PIWA2_FN3_R_POL_PAT_BORO_CMD  CHAR(1),                      03580099
           4  PIWA2_FN3_R_POL_PRECINCT      CHAR(3),                      03590099
         3 PIWA2_FN3_R_FIRE_DIV             CHAR(2),                      03600099
         3 PIWA2_FN3_R_FIRE_BAT             CHAR(2),                      03610099
         3 PIWA2_FN3_R_FIRE_CO,                                           03620099
           4 PIWA2_FN3_R_FIRE_CO_TYPE       CHAR(1),                      03630099
           4 PIWA2_FN3_R_FIRE_CO_NUM        CHAR(3),                      03640099
         3 PIWA2_FN3_R_SCHL_DIST            CHAR(2),                      03650099
         3 PIWA2_FN3_R_DYN_BLK              CHAR(3), /*ATOMIC POLYGON*/   03660099
         3 PIWA2_FN3_R_ED                   CHAR(3),                      03670099
         3 PIWA2_FN3_R_AD                   CHAR(2),                      03680099
         3 PIWA2_FN3_R_POLICE_PAT_BORO      CHAR(2),                      03690099
         3 FILLER_1080                      CHAR(1),                      03700099
         3 PIWA2_FN3_R_BORO                 CHAR(1),                      03710099
         3 PIWA2_FN3_R_1990_CENS_TRCT       CHAR(6),                      03720099
         3 PIWA2_FN3_R_2010_CENSUS_TRACT    CHAR(6),                      03730099
         3 PIWA2_FN3_R_2010_CENSUS_BLOCK    CHAR(4),                      03740099
         3 PIWA2_FN3_R_2010_CENSUS_BLK_SF   CHAR(1), /*NOT IMPLEMENTED*/  03750099
         3 PIWA2_FN3_R_2000_CENS_TRACT      CHAR(6),                      03760099
         3 PIWA2_FN3_R_2000_CENS_BLOCK      CHAR(4),                      03770099
         3 PIWA2_FN3_R_2000_CENS_BLK_SUF    CHAR(1),                      03780099
         3 FILLER_1090                      CHAR(7),                      03790099
    /**  3 PIWA2_FN3_R_BLOCKFACE_ID *V16.1* CHAR(7)  **/                  03800099
         3 PIWA2_FN3_R_NTA                  CHAR(4), /*NEIGHBORHOOD    */ 03810099
                                                     /*TABULATION AREA */ 03820099
         3 FILLER_1100                      CHAR(8),                      03830099
       2 PIWA2_FN3_SEGAUX,                                                03840099
         3 PIWA2_FN3_SEGAUX_FILL            CHAR(6),                      03850099
         3 PIWA2_FN3_SEGAUX_CTR             CHAR(4),                      03860099
         3 PIWA2_FN3_SEGAUX_SEGS(70)        CHAR(7);                      03870099
                                                                          03880099
    DCL   PIWA2_FN3_L_COMDIST                CHAR(3)                       03890099
           BASED(ADDR(PIWA2_FN3_L_COM_DIST));                             03900099
    DCL   PIWA2_FN3_L_POLDIST                CHAR(4)                       03910099
           BASED(ADDR(PIWA2_FN3_L_POLICE_DIST));                          03920099
    DCL   PIWA2_FN3_R_COMDIST                CHAR(3)                       03930099
           BASED(ADDR(PIWA2_FN3_R_COM_DIST));                             03940099
    DCL   PIWA2_FN3_R_POLDIST                CHAR(4)                       03950099
           BASED(ADDR(PIWA2_FN3_R_POLICE_DIST));                          03960099
                                                                          03970099
    /*******************************************************************/ 03980099
    /*******     FOR: FUNCTION 3 EXTENDED  *****************************/ 03990099
    DCL                                                                    04000099
     1 PIWA2_FUNCTION3X  BASED(PP2),                                      04010099
       2 PIWA2_3X_ACCESS_KEY                CHAR(21),                     04020099
       2 PIWA2_3X_DUP_KEY_FLAG              CHAR(1),/*(OR CONT PARITY)*/  04030099
       2 PIWA2_3X_LOCATION_STATUS           CHAR(1),                      04040099
       2 PIWA2_3X_COUNTY_BOUNDARY           CHAR(1),                      04050099
       2 PIWA2_3X_PREF_LGC1                 CHAR(2),                      04060099
       2 PIWA2_3X_PREF_LGC2                 CHAR(2),                      04070099
       2 PIWA2_3X_PREF_LGC3                 CHAR(2),                      04080099
       2 PIWA2_3X_NUM_X_ST_LOW_END          CHAR(1),                      04090099
       2 PIWA2_3X_LOW_B5SC(5)               CHAR(6),                      04100099
       2 PIWA2_3X_NUM_X_ST_HI_END           CHAR(1),                      04110099
       2 PIWA2_3X_HI_B5SC(5)                CHAR(6),                      04120099
       2 PIWA2_3X_REVERSAL_FLAG             CHAR(1),                      04130099
       2 PIWA2_3X_LIONKEY,                                                04140099
         3 PIWA2_3X_LION_BORO               CHAR(1),                      04150099
         3 PIWA2_3X_LION_FACECODE           CHAR(4),                      04160099
         3 PIWA2_3X_LION_SEQ                CHAR(5),                      04170099
       2 PIWA2_3X_GENREC_FLAG               CHAR(1),                      04180099
       2 PIWA2_3X_SEG_LEN                   CHAR(5),                      04190099
       2 PIWA2_3X_SEG_SLOPE                 CHAR(3),                      04200099
       2 PIWA2_3X_SEG_ORIENT                CHAR(1),                      04210099
       2 PIWA2_3X_MARBLE_RIKERS_FLAG        CHAR(1),                      04220099
       2 PIWA2_3X_FROM_TO_NODES,                                          04230099
         3 PIWA2_3X_FROM_NODE               CHAR(7),                      04240099
         3 PIWA2_3X_TO_NODE                 CHAR(7),                      04250099
       2 PIWA2_3X_SANIT_SNOW_PRIORITY       CHAR(1), /*SANITATION STRT */ 04260099
                                                     /*SNOW PRIORITY   */ 04270099
       2 FILLER3X_600                       CHAR(4),                      04280099
       2 PIWA2_3X_SEGMENT_ID                CHAR(7),                      04290099
       2 PIWA2_3X_DOT_SLA                   CHAR(1),                      04300099
       2 PIWA2_3X_CURVE_FLAG                CHAR(1),                      04310099
       2 PIWA2_3X_DOG_LEG                   CHAR(1),                      04320099
       2 PIWA2_3X_FEATURE_TYPE              CHAR(1),                      04330099
       2 PIWA2_3X_SEGMENT_TYPE              CHAR(1),                      04340099
       2 PIWA2_3X_COINCIDENT_SEG_CTR        CHAR(1),                      04350099
       2 FILLER3X_700                       CHAR(4),                      04360099
       2 PIWA2_3X_LEFT_SIDE_OF_STR,                                       04370099
         3 PIWA2_3X_L_COM_DIST,                                           04380099
           4 PIWA2_3X_L_COM_DIST_BORO       CHAR(1),                      04390099
           4 PIWA2_3X_L_COM_DIST_NUM        CHAR(2),                      04400099
         3 PIWA2_3X_L_LOW_HOUSENUM          CHAR(16),/*DISPLAY FORMAT*/   04410099
         3 PIWA2_3X_L_HI_HOUSENUM           CHAR(16),/*DISPLAY FORMAT*/   04420099
         3 FILLER3X_800                     CHAR(33),/* FOR GSS USE*/     04430099
         3 PIWA2_3X_L_ZIP                   CHAR(5),                      04440099
         3 PIWA2_3X_L_HEALTH_AREA           CHAR(4), /* HEALTH AREA*/     04450099
         3 PIWA2_3X_L_POLICE_DIST,                                        04460099
           4  PIWA2_3X_L_POL_PAT_BORO_CMD CHAR(1),                        04470099
           4  PIWA2_3X_L_POL_PRECINCT       CHAR(3),                      04480099
         3 PIWA2_3X_L_FIRE_DIV              CHAR(2),                      04490099
         3 PIWA2_3X_L_FIRE_BAT              CHAR(2),                      04500099
         3 PIWA2_3X_L_FIRE_CO,                                            04510099
           4 PIWA2_3X_L_FIRE_CO_TYPE        CHAR(1),                      04520099
           4 PIWA2_3X_L_FIRE_CO_NUM         CHAR(3),                      04530099
         3 PIWA2_3X_L_SCHL_DIST             CHAR(2),                      04540099
         3 PIWA2_3X_L_DYN_BLK               CHAR(3), /*ATOMIC POLYGON*/   04550099
         3 PIWA2_3X_L_ED                    CHAR(3),                      04560099
         3 PIWA2_3X_L_AD                    CHAR(2),                      04570099
         3 PIWA2_3X_L_POLICE_PAT_BORO       CHAR(2),                      04580099
         3 FILLER3X_880                     CHAR(1),                      04590099
         3 PIWA2_3X_L_BORO                  CHAR(1),                      04600099
         3 PIWA2_3X_L_1990_CENS_TRCT        CHAR(6),                      04610099
         3 PIWA2_3X_L_2010_CENSUS_TRACT     CHAR(6),                      04620099
         3 PIWA2_3X_L_2010_CENSUS_BLOCK     CHAR(4),                      04630099
         3 PIWA2_3X_L_2010_CENSUS_BLK_SF    CHAR(1), /*NOT IMPLEMENTED*/  04640099
         3 PIWA2_3X_L_2000_CENS_TRACT       CHAR(6),                      04650099
         3 PIWA2_3X_L_2000_CENS_BLOCK       CHAR(4),                      04660099
         3 PIWA2_3X_L_2000_CENS_BLK_SF      CHAR(1),                      04670099
         3 FILLER_3X_L_890                  CHAR(7),                      04680099
     /** 3 PIWA2_3X_L_BLOCKFACE_ID *V16.1*  CHAR(7)  **/                  04690099
         3 PIWA2_3X_L_NTA                   CHAR(4), /*NEIGHBORHOOD    */ 04700099
                                                     /*TABULATION AREA */ 04710099
         3 FILLER_3X_L_900                  CHAR(8),                      04720099
       2 PIWA2_3X_RIGHT_SIDE_OF_STR,                                      04730099
         3 PIWA2_3X_R_COM_DIST,                                           04740099
           4 PIWA2_3X_R_COM_DIST_BORO       CHAR(1),                      04750099
           4 PIWA2_3X_R_COM_DIST_NUM        CHAR(2),                      04760099
         3 PIWA2_3X_R_LOW_HOUSENUM          CHAR(16),/*DISPLAY FORMAT*/   04770099
         3 PIWA2_3X_R_HI_HOUSENUM           CHAR(16),/*DISPLAY FORMAT*/   04780099
         3 FILLER3X_R_1000                  CHAR(33),/*FOR GSS USE */     04790099
         3 PIWA2_3X_R_ZIP                   CHAR(5),                      04800099
         3 PIWA2_3X_R_HEALTH_AREA           CHAR(4), /*HEALTH AREA*/      04810099
         3 PIWA2_3X_R_POLICE_DIST,                                        04820099
           4  PIWA2_3X_R_POL_PAT_BORO_CMD   CHAR(1),                      04830099
           4  PIWA2_3X_R_POL_PRECINCT       CHAR(3),                      04840099
         3 PIWA2_3X_R_FIRE_DIV              CHAR(2),                      04850099
         3 PIWA2_3X_R_FIRE_BAT              CHAR(2),                      04860099
         3 PIWA2_3X_R_FIRE_CO,                                            04870099
           4 PIWA2_3X_R_FIRE_CO_TYPE        CHAR(1),                      04880099
           4 PIWA2_3X_R_FIRE_CO_NUM         CHAR(3),                      04890099
         3 PIWA2_3X_R_SCHL_DIST             CHAR(2),                      04900099
         3 PIWA2_3X_R_DYN_BLK               CHAR(3), /*ATOMIC POLYGON*/   04910099
         3 PIWA2_3X_R_ED                    CHAR(3),                      04920099
         3 PIWA2_3X_R_AD                    CHAR(2),                      04930099
         3 PIWA2_3X_R_POLICE_PAT_BORO       CHAR(2),                      04940099
         3 FILLER3X_R_1080                  CHAR(1),                      04950099
         3 PIWA2_3X_R_BORO                  CHAR(1),                      04960099
         3 PIWA2_3X_R_1990_CENS_TRCT        CHAR(6),                      04970099
         3 PIWA2_3X_R_2010_CENSUS_TRACT     CHAR(6),                      04980099
         3 PIWA2_3X_R_2010_CENSUS_BLOCK     CHAR(4),                      04990099
         3 PIWA2_3X_R_2010_CENSUS_BLK_SF    CHAR(1), /*NOT IMPLEMENTED*/  05000099
         3 PIWA2_3X_R_2000_CENS_TRACT       CHAR(6),                      05010099
         3 PIWA2_3X_R_2000_CENS_BLOCK       CHAR(4),                      05020099
         3 PIWA2_3X_R_2000_CENS_BLK_SF      CHAR(1),                      05030099
         3 FILLER3X_R_1090                  CHAR(7),                      05040099
     /** 3 PIWA2_3X_R_BLOCKFACE_ID *V16.1*  CHAR(7)  **/                  05050099
         3 PIWA2_3X_R_NTA                   CHAR(4), /*NEIGHBORHOOD    */ 05060099
                                                     /*TABULATION AREA */ 05070099
         3 FILLER_3X_R_1100                 CHAR(8),                      05080099
       2   PIWA2_3X_LGCS                    CHAR(8),                      05090099
       2   PIWA2_3X_LGCS_FROM               CHAR(8),                      05100099
       2   PIWA2_3X_LGCS_TO                 CHAR(8),                      05110099
       2   PIWA2_3X_L_HEALTH_CTR_DIST       CHAR(2), /*HEALTH CENTER*/    05120099
       2   PIWA2_3X_R_HEALTH_CTR_DIST       CHAR(2), /*HEALTH CENTER*/    05130099
       2   PIWA2_3X_FILL1                   CHAR(1),                      05140099
       2   PIWA2_3X_TRAFFIC_DIR             CHAR(1),                      05150099
       2   PIWA2_3X_ROADWAY_TYPE            CHAR(2),                      05160099
       2   PIWA2_3X_PHYSICAL_ID             CHAR(7),                      05170099
       2   PIWA2_3X_GENERIC_ID              CHAR(7),                      05180099
       2   PIWA2_3X_INTP_ID                 CHAR(7),  /*INTERNAL USE*/    05190099
       2   PIWA2_3X_INTF_ID                 CHAR(7),  /*INTERNAL USE*/    05200099
       2   PIWA2_3X_STR_STATUS              CHAR(1),                      05210099
       2   PIWA2_3X_STR_WIDTH               CHAR(3),                      05220099
       2   PIWA2_3X_STR_WIDTH_IRREG         CHAR(1),                      05230099
       2   PIWA2_3X_BIKE_LANE               CHAR(1),                      05240099
       2   PIWA2_3X_FED_CLASS_CODE          CHAR(2),                      05250099
       2   PIWA2_3X_ROW_TYPE                CHAR(1),                      05260099
       2   PIWA2_3X_LGC_LIST                CHAR(10),                     05270099
       2   PIWA2_3X_LEGACY_ID               CHAR(7),                      05280099
       2   PIWA2_3X_L_NTA_NAME              CHAR(75),                     05290099
       2   PIWA2_3X_R_NTA_NAME              CHAR(75),                     05300099
       2   PIWA2_3X_FROM_XCOORD             CHAR(7),                      05310099
       2   PIWA2_3X_FROM_YCOORD             CHAR(7),                      05320099
       2   PIWA2_3X_TO_XCOORD               CHAR(7),                      05330099
       2   PIWA2_3X_TO_YCOORD               CHAR(7),                      05340099
       2   PIWA2_3X_FROM_LATITUDE           CHAR(9),                      05350099
       2   PIWA2_3X_FROM_LONGITUDE          CHAR(11),                     05360099
       2   PIWA2_3X_TO_LATITUDE             CHAR(9),                      05370099
       2   PIWA2_3X_TO_LONGITUDE            CHAR(11),                     05380099
       2   PIWA2_3X_L_BLOCKFACE_ID          CHAR(10),                     05390099
       2   PIWA2_3X_R_BLOCKFACE_ID          CHAR(10),                     05400099
       2   PIWA2_3X_NBR_TRAVEL_LANES        CHAR(2),                      05410099
       2   PIWA2_3X_NBR_PARK_LANES          CHAR(2),                      05420099
       2   PIWA2_3X_NBR_TOTAL_LANES         CHAR(2),                      05430099
       2   PIWA2_3X_BIKE_LANE_2             CHAR(2),                      05431099
       2   PIWA2_3X_STR_WIDTH_MAX           CHAR(3),                      05432099
       2   PIWA2_3X_BIKE_TRAFFIC_DIR        CHAR(2),                      05433099
       2   PIWA2_3X_FILL2                   CHAR(213),                    05440099
    /* 2   PIWA2_3X_FILL2 ** V17.1   ***    CHAR(215), **/                05441099
    /* 2   PIWA2_3X_FILL2 ** V16.4   ***    CHAR(220), **/                05442099
    /* 2   PIWA2_3X_FILL2 ** V16.1   ***    CHAR(246)  **/                05450099
    /* 2   PIWA2_3X_FILL2 ** V15.3   ***    CHAR(286)  **/                05460099
       2 PIWA2_3X_SEGAUX,                                                 05470099
         3 PIWA2_3X_SEGAUX_FILL             CHAR(6),                      05480099
         3 PIWA2_3X_SEGAUX_CTR              CHAR(4),                      05490099
         3 PIWA2_3X_SEGAUX_SEGS(70)         CHAR(7);                      05500099
                                                                          05510099
    /*******************************************************************/ 05520099
    /*******     FOR: FUNCTION 3C          *****************************/ 05530099
    DCL                                                                    05540099
     1 PIWA2_FUNCTION3C  BASED(PP2),                                      05550099
       2 PIWA2_FN3C_ACCESS_KEY              CHAR(21),                     05560099
       2 PIWA2_FN3C_DUP_KEY_FLAG            CHAR(1),/*(OR CONT PARITY)*/  05570099
       2 PIWA2_FN3C_LOCATION_STATUS         CHAR(1),                      05580099
       2 PIWA2_FN3C_COUNTY_BOUNDARY         CHAR(1),                      05590099
       2 PIWA2_FN3C_PREF_LGC1               CHAR(2),                      05600099
       2 PIWA2_FN3C_PREF_LGC2               CHAR(2),                      05610099
       2 PIWA2_FN3C_PREF_LGC3               CHAR(2),                      05620099
       2 PIWA2_FN3C_NUM_X_ST_LOW_END        CHAR(1),                      05630099
       2 PIWA2_FN3C_LOW_B5SC(5)             CHAR(6),                      05640099
       2 PIWA2_FN3C_NUM_X_ST_HI_END         CHAR(1),                      05650099
       2 PIWA2_FN3C_HI_B5SC(5)              CHAR(6),                      05660099
       2 PIWA2_FN3C_REVERSAL_FLAG           CHAR(1),                      05670099
       2 PIWA2_FN3C_LIONKEY,                                              05680099
         3 PIWA2_FN3C_LION_BORO             CHAR(1),                      05690099
         3 PIWA2_FN3C_LION_FACECODE         CHAR(4),                      05700099
         3 PIWA2_FN3C_LION_SEQ              CHAR(5),                      05710099
       2 PIWA2_FN3C_GENREC_FLAG             CHAR(1),                      05720099
       2 PIWA2_FN3C_SEG_LEN                 CHAR(5),                      05730099
       2 PIWA2_FN3C_SEG_SLOPE               CHAR(3),                      05740099
       2 PIWA2_FN3C_SEG_ORIENT              CHAR(1),                      05750099
       2 PIWA2_FN3C_MARBLE_RIKERS_FLAG      CHAR(1),                      05760099
       2 PIWA2_FN3C_FROM_TO_NODES,                                        05770099
         3 PIWA2_FN3C_FROM_NODE             CHAR(7),                      05780099
         3 PIWA2_FN3C_TO_NODE               CHAR(7),                      05790099
       2 PIWA2_FN3C_SANIT_SNOW_PRIORITY     CHAR(1), /*SANITATION STRT */ 05800099
                                                     /*SNOW PRIORITY   */ 05810099
       2 FILLER_1200                        CHAR(4),                      05820099
       2 PIWA2_FN3C_SEGMENT_ID              CHAR(7),                      05830099
       2 PIWA2_FN3C_DOT_SLA                 CHAR(1),                      05840099
       2 PIWA2_FN3C_SIDE_OF_STR             CHAR(1),                      05850099
       2 PIWA2_FN3C_CURVE_FLAG              CHAR(1),                      05860099
       2 PIWA2_FN3C_FEATURE_TYPE            CHAR(1),                      05870099
       2 PIWA2_FN3C_SEGMENT_TYPE            CHAR(1),                      05880099
       2 PIWA2_FN3C_COINCIDENT_SEG_CTR      CHAR(1),                      05890099
       2 FILLER_1300                        CHAR(4),                      05900099
       2 PIWA2_FN3C_BLOCKFACE_INFO,                                       05910099
         3 PIWA2_FN3C_COM_DIST,                                           05920099
           4 PIWA2_FN3C_COM_DIST_BORO       CHAR(1),                      05930099
           4 PIWA2_FN3C_COM_DIST_NUM        CHAR(2),                      05940099
         3 PIWA2_FN3C_LOW_HOUSENUM          CHAR(16),/*DISPLAY FORMAT*/   05950099
         3 PIWA2_FN3C_HI_HOUSENUM           CHAR(16),/*DISPLAY FORMAT*/   05960099
         3 PIWA2_FN3C_LOW_HOUSENUM2         CHAR(16),/*DISPLAY FORMAT*/   05970099
         3 PIWA2_FN3C_HI_HOUSENUM2          CHAR(16),/*DISPLAY FORMAT*/   05980099
         3 FILLER_1400                      CHAR(1), /* FOR GSS USE */    05990099
         3 PIWA2_FN3C_ZIP                   CHAR(5),                      06000099
         3 PIWA2_FN3C_HEALTH_AREA           CHAR(4), /*HEALTH AREA*/      06010099
         3 PIWA2_FN3C_POLICE_DIST,                                        06020099
           4 PIWA2_FN3C_POL_PAT_BORO_CMD    CHAR(1),                      06030099
           4 PIWA2_FN3C_POL_PRECINCT        CHAR(3),                      06040099
         3 PIWA2_FN3C_FIRE_DIV              CHAR(2),                      06050099
         3 PIWA2_FN3C_FIRE_BAT              CHAR(2),                      06060099
         3 PIWA2_FN3C_FIRE_CO,                                            06070099
           4 PIWA2_FN3C_FIRE_CO_TYPE        CHAR(1),                      06080099
           4 PIWA2_FN3C_FIRE_CO_NUM         CHAR(3),                      06090099
         3 PIWA2_FN3C_SCHL_DIST             CHAR(2),                      06100099
         3 PIWA2_FN3C_DYN_BLK               CHAR(3), /*ATOMIC POLYGON*/   06110099
         3 PIWA2_FN3C_ED                    CHAR(3),                      06120099
         3 PIWA2_FN3C_AD                    CHAR(2),                      06130099
         3 PIWA2_FN3C_POLICE_PAT_BORO       CHAR(2),                      06140099
         3 FILLER_1480                      CHAR(1),                      06150099
         3 PIWA2_FN3C_BORO                  CHAR(1),                      06160099
         3 PIWA2_FN3C_1990_CENS_TRCT        CHAR(6),                      06170099
         3 PIWA2_FN3C_2010_CENSUS_TRACT     CHAR(6),                      06180099
         3 PIWA2_FN3C_2010_CENSUS_BLOCK     CHAR(4),                      06190099
         3 PIWA2_FN3C_2010_CENSUS_BLK_SF    CHAR(1), /*NOT IMPLEMENTED*/  06200099
         3 PIWA2_FN3C_2000_CENS_TRACT       CHAR(6),                      06210099
         3 PIWA2_FN3C_2000_CENS_BLOCK       CHAR(4),                      06220099
         3 PIWA2_FN3C_2000_CENS_BLK_SUF     CHAR(1),                      06230099
         3 FILLER_1490                      CHAR(7),                      06240099
    /**  3 PIWA2_FN3C_BLOCKFACE_ID *V16.1*  CHAR(7)  **/                  06250099
         3 PIWA2_FN3C_NTA                   CHAR(4), /*NEIGHBORHOOD    */ 06260099
                                                     /*TABULATION AREA */ 06270099
         3 FILLER_1500                      CHAR(8),                      06280099
       2 PIWA2_FN3C_SEGAUX,                                               06290099
         3 PIWA2_FN3C_SEGAUX_FILL           CHAR(6),                      06300099
         3 PIWA2_FN3C_SEGAUX_CTR            CHAR(4),                      06310099
         3 PIWA2_FN3C_SEGAUX_SEGS(70)       CHAR(7);                      06320099
                                                                          06330099
    DCL   PIWA2_FN3C_COMDIST                 CHAR(3)                       06340099
           BASED(ADDR(PIWA2_FN3C_COM_DIST));                              06350099
    DCL   PIWA2_FN3C_POLDIST                 CHAR(4)                       06360099
           BASED(ADDR(PIWA2_FN3C_POLICE_DIST));                           06370099
                                                                          06380099
    /*******************************************************************/ 06390099
    /*******     FOR: FUNCTION 3CX (EXTENDED) **************************/ 06400099
    DCL                                                                    06410099
     1 PIWA2_FUNCTION3CX BASED(PP2),                                      06420099
       2 PIWA2_3CX_ACCESS_KEY               CHAR(21),                     06430099
       2 PIWA2_3CX_DUP_KEY_FLAG             CHAR(1),/*(OR CONT PARITY)*/  06440099
       2 PIWA2_3CX_LOCATION_STATUS          CHAR(1),                      06450099
       2 PIWA2_3CX_COUNTY_BOUNDARY          CHAR(1),                      06460099
       2 PIWA2_3CX_PREF_LGC1                CHAR(2),                      06470099
       2 PIWA2_3CX_PREF_LGC2                CHAR(2),                      06480099
       2 PIWA2_3CX_PREF_LGC3                CHAR(2),                      06490099
       2 PIWA2_3CX_NUM_X_ST_LOW_END         CHAR(1),                      06500099
       2 PIWA2_3CX_LOW_B5SC(5)              CHAR(6),                      06510099
       2 PIWA2_3CX_NUM_X_ST_HI_END          CHAR(1),                      06520099
       2 PIWA2_3CX_HI_B5SC(5)               CHAR(6),                      06530099
       2 PIWA2_3CX_REVERSAL_FLAG            CHAR(1),                      06540099
       2 PIWA2_3CX_LIONKEY,                                               06550099
         3 PIWA2_3CX_LION_BORO              CHAR(1),                      06560099
         3 PIWA2_3CX_LION_FACECODE          CHAR(4),                      06570099
         3 PIWA2_3CX_LION_SEQ               CHAR(5),                      06580099
       2 PIWA2_3CX_GENREC_FLAG              CHAR(1),                      06590099
       2 PIWA2_3CX_SEG_LEN                  CHAR(5),                      06600099
       2 PIWA2_3CX_SEG_SLOPE                CHAR(3),                      06610099
       2 PIWA2_3CX_SEG_ORIENT               CHAR(1),                      06620099
       2 PIWA2_3CX_MARBLE_RIKERS_FLAG       CHAR(1),                      06630099
       2 PIWA2_3CX_FROM_TO_NODES,                                         06640099
         3 PIWA2_3CX_FROM_NODE              CHAR(7),                      06650099
         3 PIWA2_3CX_TO_NODE                CHAR(7),                      06660099
       2 PIWA2_3CX_SANIT_SNOW_PRIORITY      CHAR(1), /*SANITATION STRT */ 06670099
                                                     /*SNOW PRIORITY   */ 06680099
       2 FILLER3CX_1200                     CHAR(4),                      06690099
       2 PIWA2_3CX_SEGMENT_ID               CHAR(7),                      06700099
       2 PIWA2_3CX_DOT_SLA                  CHAR(1),                      06710099
       2 PIWA2_3CX_SIDE_OF_STR              CHAR(1),                      06720099
       2 PIWA2_3CX_CURVE_FLAG               CHAR(1),                      06730099
       2 PIWA2_3CX_FEATURE_TYPE             CHAR(1),                      06740099
       2 PIWA2_3CX_SEGMENT_TYPE             CHAR(1),                      06750099
       2 PIWA2_3CX_COINCIDENT_SEG_CTR       CHAR(1),                      06760099
       2 FILLER3CX_1300                     CHAR(4),                      06770099
       2 PIWA2_3CX_BLOCKFACE_INFO,                                        06780099
         3 PIWA2_3CX_COM_DIST,                                            06790099
           4 PIWA2_3CX_COM_DIST_BORO        CHAR(1),                      06800099
           4 PIWA2_3CX_COM_DIST_NUM         CHAR(2),                      06810099
         3 PIWA2_3CX_LOW_HOUSENUM           CHAR(16),/*DISPLAY FORMAT*/   06820099
         3 PIWA2_3CX_HI_HOUSENUM            CHAR(16),/*DISPLAY FORMAT*/   06830099
         3 PIWA2_3CX_LOW_HOUSENUM2          CHAR(16),/*DISPLAY FORMAT*/   06840099
         3 PIWA2_3CX_HI_HOUSENUM2           CHAR(16),/*DISPLAY FORMAT*/   06850099
         3 FILLER3CX_1400                   CHAR(1), /* FOR GSS USE */    06860099
         3 PIWA2_3CX_ZIP                    CHAR(5),                      06870099
         3 PIWA2_3CX_HEALTH_AREA            CHAR(4), /*HEALTH AREA*/      06880099
         3 PIWA2_3CX_POLICE_DIST,                                         06890099
           4 PIWA2_3CX_POL_PAT_BORO_CMD     CHAR(1),                      06900099
           4 PIWA2_3CX_POL_PRECINCT         CHAR(3),                      06910099
         3 PIWA2_3CX_FIRE_DIV               CHAR(2),                      06920099
         3 PIWA2_3CX_FIRE_BAT               CHAR(2),                      06930099
         3 PIWA2_3CX_FIRE_CO,                                             06940099
           4 PIWA2_3CX_FIRE_CO_TYPE         CHAR(1),                      06950099
           4 PIWA2_3CX_FIRE_CO_NUM          CHAR(3),                      06960099
         3 PIWA2_3CX_SCHL_DIST              CHAR(2),                      06970099
         3 PIWA2_3CX_DYN_BLK                CHAR(3), /*ATOMIC POLYGON*/   06980099
         3 PIWA2_3CX_ED                     CHAR(3),                      06990099
         3 PIWA2_3CX_AD                     CHAR(2),                      07000099
         3 PIWA2_3CX_POLICE_PAT_BORO        CHAR(2),                      07010099
         3 FILLER3CX_1480                   CHAR(1),                      07020099
         3 PIWA2_3CX_BORO                   CHAR(1),                      07030099
         3 PIWA2_3CX_1990_CENS_TRCT         CHAR(6),                      07040099
         3 PIWA2_3CX_2010_CENSUS_TRACT      CHAR(6),                      07050099
         3 PIWA2_3CX_2010_CENSUS_BLOCK      CHAR(4),                      07060099
         3 PIWA2_3CX_2010_CENSUS_BLK_SF     CHAR(1), /*NOT IMPLEMENTED*/  07070099
         3 PIWA2_3CX_2000_CENS_TRACT        CHAR(6),                      07080099
         3 PIWA2_3CX_2000_CENS_BLOCK        CHAR(4),                      07090099
         3 PIWA2_3CX_2000_CENS_BLK_S        CHAR(1),                      07100099
         3 FILLER3CX_1490                   CHAR(7),                      07110099
     /** 3 PIWA2_3CX_BLOCKFACE_ID *V16.1*   CHAR(7)  **/                  07120099
         3 PIWA2_3CX_NTA                    CHAR(4), /*NEIGHBORHOOD    */ 07130099
                                                     /*TABULATION AREA */ 07140099
         3 FILLER3CX_1500                   CHAR(8),                      07150099
                                                                          07160099
       2   PIWA2_3CX_LGCS                   CHAR(8),                      07170099
       2   PIWA2_3CX_LGCS_FROM              CHAR(8),                      07180099
       2   PIWA2_3CX_LGCS_TO                CHAR(8),                      07190099
       2   PIWA2_3CX_L_HEALTH_CTR_DIST      CHAR(2), /*HEALTH CENTER*/    07200099
       2   PIWA2_3CX_R_HEALTH_CTR_DIST      CHAR(2), /*HEALTH CENTER*/    07210099
       2   PIWA2_3CX_FILL1550               CHAR(1),                      07220099
       2   PIWA2_3CX_TRAFFIC_DIRECTN        CHAR(1),                      07230099
       2   PIWA2_3CX_ROADWAY_TYPE           CHAR(2),                      07240099
       2   PIWA2_3CX_PHYSICAL_ID            CHAR(7),                      07250099
       2   PIWA2_3CX_GENERIC_ID             CHAR(7),                      07260099
       2   PIWA2_3CX_INTP_ID                CHAR(7),  /*INTERNAL USE*/    07270099
       2   PIWA2_3CX_INTF_ID                CHAR(7),  /*INTERNAL USE*/    07280099
       2   PIWA2_3CX_STREET_STATUS          CHAR(1),                      07290099
       2   PIWA2_3CX_STREET_WIDTH           CHAR(3),                      07300099
       2   PIWA2_3CX_STREET_WIDTH_IRREG     CHAR(1),                      07310099
       2   PIWA2_3CX_BIKE_LANE              CHAR(1),                      07320099
       2   PIWA2_3CX_FED_CLASS_CODE         CHAR(2),                      07330099
       2   PIWA2_3CX_ROW_TYPE               CHAR(1),                      07340099
       2   PIWA2_3CX_LGC_LIST               CHAR(10),                     07350099
       2   PIWA2_3CX_LEGACY_ID              CHAR(7),                      07360099
       2   PIWA2_3CX_NTA_NAME               CHAR(75),                     07370099
       2   PIWA2_3CX_FROM_XCOORD            CHAR(7),                      07380099
       2   PIWA2_3CX_FROM_YCOORD            CHAR(7),                      07390099
       2   PIWA2_3CX_TO_XCOORD              CHAR(7),                      07400099
       2   PIWA2_3CX_TO_YCOORD              CHAR(7),                      07410099
       2   PIWA2_3CX_FROM_LATITUDE          CHAR(9),                      07420099
       2   PIWA2_3CX_FROM_LONGITUDE         CHAR(11),                     07430099
       2   PIWA2_3CX_TO_LATITUDE            CHAR(9),                      07440099
       2   PIWA2_3CX_TO_LONGITUDE           CHAR(11),                     07450099
       2   PIWA2_3CX_BLOCKFACE_ID           CHAR(10),                     07460099
       2   PIWA2_3CX_NBR_TRAVEL_LANES       CHAR(2),                      07470099
       2   PIWA2_3CX_NBR_PARK_LANES         CHAR(2),                      07480099
       2   PIWA2_3CX_NBR_TOTAL_LANES        CHAR(2),                      07490099
       2   PIWA2_3CX_BIKE_LANE_2            CHAR(2),                      07491099
       2   PIWA2_3CX_STREET_WIDTH_MAX       CHAR(3),                      07492099
       2   PIWA2_3CX_BIKE_TRAFFIC_DIR       CHAR(2),                      07493099
       2   PIWA2_3CX_FILL1560               CHAR(298),                    07500099
    /* 2   PIWA2_3CX_FILL1560 ** V17.1 **   CHAR(300), **/                07501099
    /* 2   PIWA2_3CX_FILL1560 ** V16.4 **   CHAR(305), **/                07502099
    /* 2   PIWA2_3CX_FILL1560 ** V16.1 **   CHAR(321)  **/                07510099
    /* 2   PIWA2_3CX_FILL1560 ** V15.3 **   CHAR(361)  **/                07520099
       2 PIWA2_3CX_SEGAUX,                                                07530099
         3 PIWA2_3CX_SEGAUX_FILL            CHAR(6),                      07540099
         3 PIWA2_3CX_SEGAUX_CTR             CHAR(4),                      07550099
         3 PIWA2_3CX_SEGAUX_SEGS(70)        CHAR(7);                      07560099
                                                                          07570099
    /*******************************************************************/ 07580099
    /*******     FOR: FUNCTION 5           *****************************/ 07590099
    DCL                                                                    07600099
     1 PIWA2_FUNCTION5   BASED(PP2),                                      07610099
       2 PIWA2_FN5_ADDR_MATCHING_KEY        CHAR(33),                     07620099
       2 FILLER_1600                        CHAR(267);                    07630099
                                                                          07640099
    PP2=ADDR(P2PL1);                                                       07650099


## <span id="appendix14.16"><center>P2PL11A COPY File</center></span>  

    /*******************************************************************/  00000100
    /***  THIS IS THE PL/1 STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM  ***/  00000200
    /***  INDEPENDENT REGULAR WORK AREA 2 FOR FUNCTIONS: 1A , BL,    ***/  00000300
    /***  AND BN.                                                    ***/  00000400
    /***  THESE THREE FUNCTIONS SHARE A SINGLE WORK AREA 2 LAYOUT.   ***/  00000500
    /***                                                             ***/  00000600
    /***  COPY FILE - P2PL11A.                          10/10/97     ***/  00000700
    /*******************************************************************/  00000800
                                                                           00000900
    DCL                                                                    00001000
     1 P2PL11A,                                                            00001100
       2 PIWA2_1A_ACCESS_KEY                CHAR(21),                      00001200
       2 PIWA2_1A_CONT_PARITY               CHAR(1), /*(OR DUP ADDR IND)*/ 00001300
       2 PIWA2_1A_LOW_HOUSENUM              CHAR(11), /* SORT FORMAT */    00001400
       2 PIWA2_1A_BBL,                                                     00001500
         3 PIWA2_1A_BBL_BORO                CHAR(1),                       00001600
         3 PIWA2_1A_BLOCK                   CHAR(5),                       00001700
         3 PIWA2_1A_LOT                     CHAR(4),                       00001800
       2 PIWA2_1A_LOT_VER                   CHAR(1),                       00001900
       2 PIWA2_1A_SCC                       CHAR(1),                       00002000
       2 FILLER_100                         CHAR(1),                       00002100
       2 PIWA2_1A_GENERAL_LOT_INFO,                                        00002200
         3 PIWA2_1A_RPAD_BLDG_CLASS         CHAR(2),                       00002300
         3 PIWA2_1A_CORNER_CODE             CHAR(2),                       00002400
         3 PIWA2_1A_NUM_OF_STRUCTURES       CHAR(4),                       00002502
         3 PIWA2_1A_NUM_OF_BLOCKFACES       CHAR(2),                       00002600
         3 PIWA2_1A_INTERIOR_FLAG           CHAR(1),                       00002700
         3 PIWA2_1A_VACANT_FLAG             CHAR(1),                       00002800
         3 PIWA2_1A_IRREG_LOT_FLAG          CHAR(1),                       00002900
       2 PIWA2_1A_MARBLE_RIKERS_FLAG        CHAR(1),                       00003000
       2 PIWA2_1A_ADDR_LIST_OVFLOW_FLAG     CHAR(1),                       00003100
       2 PIWA2_1A_STROLL_KEY,                                              00003200
         3 PIWA2_1A_STROLL_BORO             CHAR(1),                       00003300
         3 PIWA2_1A_STROLL_5SC              CHAR(5),                       00003400
         3 PIWA2_1A_STROLL_SIDE_OF_STR      CHAR(1),  /* L, R */           00003500
         3 PIWA2_1A_STROLL_HI_HOUSENUM      CHAR(11), /* SORT FORMAT */    00003600
         3 FILLER_200                       CHAR(1),                       00003700
       2 FILLER_300                         CHAR(1),  /* FOR GSS USE*/     00003800
       2 PIWA2_1A_BIN                       CHAR(7),                       00003900
       2 PIWA2_1A_CONDO_FLAG                CHAR(1),                       00004000
       2 FILLER_400                         CHAR(1),                       00004100
       2 PIWA2_1A_RPAD_CONDO_ID_NUM         CHAR(4),                       00004200
       2 PIWA2_1A_CONDO_UNIT_ID_NUM         CHAR(7),                       00004300
       2 PIWA2_1A_CONDO_BILL_BBL            CHAR(10),                      00004400
       2 PIWA2_1A_CONDO_BILL_BBL_VER        CHAR(1),                       00004500
       2 PIWA2_1A_CONDO_BILL_BBL_SCC        CHAR(1),                       00004600
       2 PIWA2_1A_CONDO_LOW_BBL             CHAR(10),                      00004700
       2 PIWA2_1A_CONDO_LOW_BBL_VER         CHAR(1),                       00004800
       2 PIWA2_1A_CONDO_HIGH_BBL            CHAR(10),                      00004900
       2 PIWA2_1A_CONDO_HIGH_BBL_VER        CHAR(1),                       00005000
       2 FILLER_500                         CHAR(15),                      00005100
       2 PIWA2_1A_COOP_NUM                  CHAR(4),                       00005200
       2 PIWA2_1A_SANBORN,                                                 00005300
         3 PIWA2_1A_SANBORN_BORO            CHAR(1),                       00005400
         3 PIWA2_1A_SANBORN_VOL             CHAR(3),                       00005500
         3 PIWA2_1A_SANBORN_PAGE            CHAR(4),                       00005600
       2 PIWA2_1A_COMMERC_DIST              CHAR(5),                       00005700
       2 PIWA2_1A_DOF_MAP_BORO              CHAR(1),                       00005803
       2 PIWA2_1A_DOF_MAP_SECVOL            CHAR(4),                       00005902
       2 PIWA2_1A_DOF_MAP_PAGE              CHAR(4),                       00006003
       2 RESERVED_DCP                       CHAR(3),                       00006110
       2 PIWA2_1A_LATITUDE                  CHAR(09),                      00006210
       2 PIWA2_1A_LONGITUDE                 CHAR(11),                      00006310
       2 PIWA2_1A_X_COORD                   CHAR(07),                      00006410
       2 PIWA2_1A_Y_COORD                   CHAR(07),                      00006510
       2 PIWA2_1A_BID                       CHAR(06),                      00006610
       2 PIWA2_1A_TPAD_BIN_ST               CHAR(01),  /*CURRENT STATUS*/  00006710
       2 PIWA2_1A_TPAD_NEW_BIN              CHAR(07),  /*NEW BIN       */  00006810
       2 PIWA2_1A_TPAD_NEW_BIN_ST           CHAR(01),  /*NEW BIN STATUS*/  00006910
       2 PIWA2_1A_TPAD_CONFLICT             CHAR(01),  /*CONFLICT FLAG */  00007010
       2 FILLER_650                         CHAR(09),                      00007110
       2 FILLER_700                         CHAR(8),  /* LGC - GSS USE*/   00007210
       2 PIWA2_1A_NUM_OF_ADDR               CHAR(4),                       00007310
       2 PIWA2_1A_ADDR_LIST(21),                                           00007410
         3 PIWA2_1A_LIST_LOW_HOUSENUM       CHAR(16), /*DISPLAY FORMAT*/   00007510
         3 PIWA2_1A_LIST_HI_HOUSENUM        CHAR(16), /*DISPLAY FORMAT*/   00007610
         3 PIWA2_1A_LIST_BORO               CHAR(1),                       00007710
         3 PIWA2_1A_LIST_5SC                CHAR(5),                       00007810
         3 PIWA2_1A_LIST_LGC                CHAR(2),                       00007910
         3 PIWA2_1A_LIST_BIN                CHAR(7),                       00008010
         3 PIWA2_1A_LIST_SIDE_OF_STR        CHAR(1),  /* L, R */           00008110
         3 PIWA2_1A_ADDR_TYPE               CHAR(1),  /*               */  00008210
                                                      /* BLANK = NORMAL*/  00008310
         3 PIWA2_1A_TPAD_STATUS             CHAR(1),  /* 0 - 9         */  00008410
         3 FILLER_800                       CHAR(3);                       00008510
                                                                           00008610
    DCL  PIWA2_1A_SANBORN_BVOLPAGE          CHAR(8)                        00008710
            BASED(ADDR(PIWA2_1A_SANBORN));                                 00008810
    DCL  PIWA2_1A_STROLLKEY                 CHAR(19)                       00008910
            BASED(ADDR(PIWA2_1A_STROLL_KEY));                              00009004

    
## <span id="appendix14.17"><center>P2PL11AL COPY File</center></span>
    /*******************************************************************/  00000100
    /*********************************************************************/00000276
    /*                                                                   */00000376
    /***                      P2PL11AL                                 ***/00000480
    /***           LAST MODIFIED DECEMBER 2016                         ***/00000580
    /*  ADD NEW 2 BYTE BIKE TRAFFIC DIRECTION            YNL 12/16  V17.1*/00000680
    /*  REPLACED SANIT_RESERVED WITH SANIT_BULK_PICK_UP  YNL 10/16  V16.4*/00000776
    /*  ADD NEW 2 BYTE BIKE LANE AND MAX STR WIDTH       YNL 10/16  V16.4*/00000876
    /*                                                                   */00000976
    /*********************************************************************/00001076
    /***  THIS IS THE PL/1 STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM  ***/  00001100
    /***  INDEPENDENT LONG WORK AREA 2 FOR FUNCTIONS: 1A , AND BL.   ***/  00001200
    /***  THESE TWO FUNCTIONS SHARE A SINGLE LONG WORK AREA 2 LAYOUT.***/  00001300
    /***  THIS IS ALSO THE PL/1 STRUCTURE FOR GEOSUPPORT SYSTEM      ***/  00001415
    /***   PLATFORM INDEPENDENT EXTENDED WORK AREA 2 FOR             ***/  00001515
    /***   FUNCTIONS 1E AND 1A, AND FOR FUNCTION 1B WHICH IS A       ***/  00001635
    /***   COMBINATION OF EXTENDED 1/1E AND EXTENDED 1A)             ***/  00001726
    /***                                                             ***/  00001800
    /***                           LAST MODIFIED OCTOBER  2016       ***/  00001976
    /***  COPY FILE - P2PL11AL.                          10/11/2000  ***/  00002026
    /*******************************************************************/  00002126
                                                                           00002226
    DCL                                                                    00002326
     1 P2PL11AL,                                                           00002426
       2 PIWA2_1AL_ACCESS_KEY               CHAR(21),                      00002526
       2 PIWA2_1AL_CONT_PARITY              CHAR(1), /*(OR DUP ADDR IND)*/ 00002626
       2 PIWA2_1AL_LOW_HOUSENUM             CHAR(11), /* SORT FORMAT */    00002726
       2 PIWA2_1AL_BBL,                                                    00002826
         3 PIWA2_1AL_BBL_BORO               CHAR(1),                       00002926
         3 PIWA2_1AL_BLOCK                  CHAR(5),                       00003026
         3 PIWA2_1AL_LOT                    CHAR(4),                       00003126
       2 PIWA2_1AL_LOT_VER                  CHAR(1),                       00003226
       2 PIWA2_1AL_SCC                      CHAR(1),                       00003326
       2 FILLER_100                         CHAR(1),                       00003426
       2 PIWA2_1AL_GENERAL_LOT_INFO,                                       00003526
         3 PIWA2_1AL_RPAD_BLDG_CLASS        CHAR(2),                       00003626
         3 PIWA2_1AL_CORNER_CODE            CHAR(2),                       00003726
         3 PIWA2_1AL_NUM_OF_STRUCTURES      CHAR(4),                       00003826
         3 PIWA2_1AL_NUM_OF_BLOCKFACES      CHAR(2),                       00003926
         3 PIWA2_1AL_INTERIOR_FLAG          CHAR(1),                       00004026
         3 PIWA2_1AL_VACANT_FLAG            CHAR(1),                       00004126
         3 PIWA2_1AL_IRREG_LOT_FLAG         CHAR(1),                       00004226
       2 PIWA2_1AL_MARBLE_RIKERS_FLAG       CHAR(1),                       00004326
       2 PIWA2_1AL_ADDR_LIST_OVFLOW_FLAG    CHAR(1),                       00004426
       2 PIWA2_1AL_STROLL_KEY,                                             00004526
         3 PIWA2_1AL_STROLL_BORO            CHAR(1),                       00004626
         3 PIWA2_1AL_STROLL_5SC             CHAR(5),                       00004726
         3 PIWA2_1AL_STROLL_SIDE_OF_STR     CHAR(1),  /* L, R */           00004826
         3 PIWA2_1AL_STROLL_HI_HOUSENUM     CHAR(11), /* SORT FORMAT */    00004926
         3 FILLER_200                       CHAR(1),                       00005026
       2 FILLER_300                         CHAR(1),  /* FOR GSS USE*/     00005126
       2 PIWA2_1AL_BIN                      CHAR(7),                       00005226
       2 PIWA2_1AL_CONDO_FLAG               CHAR(1),                       00005326
       2 FILLER_400                         CHAR(1),                       00005426
       2 PIWA2_1AL_RPAD_CONDO_ID_NUM        CHAR(4),                       00005526
       2 PIWA2_1AL_CONDO_UNIT_ID_NUM        CHAR(7),                       00005626
       2 PIWA2_1AL_CONDO_BILL_BBL           CHAR(10),                      00005726
       2 PIWA2_1AL_CONDO_BILL_BBL_VER       CHAR(1),                       00005826
       2 PIWA2_1AL_CONDO_BILL_BBL_SCC       CHAR(1),                       00005926
       2 PIWA2_1AL_CONDO_LOW_BBL            CHAR(10),                      00006026
       2 PIWA2_1AL_CONDO_LOW_BBL_VER        CHAR(1),                       00006126
       2 PIWA2_1AL_CONDO_HIGH_BBL           CHAR(10),                      00006226
       2 PIWA2_1AL_CONDO_HIGH_BBL_VER       CHAR(1),                       00006326
       2 FILLER_500                         CHAR(15),                      00006426
       2 PIWA2_1AL_COOP_NUM                 CHAR(4),                       00006526
       2 PIWA2_1AL_SANBORN,                                                00006626
         3 PIWA2_1AL_SANBORN_BORO           CHAR(1),                       00006726
         3 PIWA2_1AL_SANBORN_VOL            CHAR(3),                       00006826
         3 PIWA2_1AL_SANBORN_PAGE           CHAR(4),                       00006926
       2 PIWA2_1AL_COMMERC_DIST             CHAR(5),                       00007026
       2 PIWA2_1AL_DOF_MAP_BORO             CHAR(1),                       00007126
       2 PIWA2_1AL_DOF_MAP_SECVOL           CHAR(4),                       00007226
       2 PIWA2_1AL_DOF_MAP_PAGE             CHAR(4),                       00007326
       2 FILLER_600                         CHAR(3),                       00007465
       2 PIWA2_1AL_LATITUDE                 CHAR(9),                       00007565
       2 PIWA2_1AL_LONGITUDE                CHAR(11),                      00007665
       2 PIWA2_1AL_X_COORD                  CHAR(07),                      00007765
       2 PIWA2_1AL_Y_COORD                  CHAR(07),                      00007865
       2 PIWA2_1AL_BID                      CHAR(06),                      00007965
       2 PIWA2_1AL_TPAD_BIN_ST              CHAR(01), /*CURRENT STATUS*/   00008065
       2 PIWA2_1AL_TPAD_NEW_BIN             CHAR(07), /*NEW BIN       */   00008165
       2 PIWA2_1AL_TPAD_NEW_BIN_ST          CHAR(01), /*NEW BIN STATUS*/   00008265
       2 PIWA2_1AL_TPAD_CONFLICT            CHAR(01), /*CONFLICT FLAG */   00008365
       2 FILLER_650                         CHAR(09),                      00008465
       2 FILLER_700                         CHAR(8),  /*LGC -GSS USE*/     00008565
       2 PIWA2_1AL_NUM_OF_BINS              CHAR(4),                       00008665
       2 PIWA2_1AL_BINS(2500)               CHAR(7);                       00008765
                                                                           00008865
    DCL 1 PIWA2_1AL_TPAD_BINLIST BASED(ADDR(PIWA2_1AL_BINS)),              00008965
          2 PIWA2_1AL_TPAD_BINS(2187),                                     00009065
            3 PIWA2_1AL_TPAD_BINS_BIN   CHAR (7),                          00009165
            3 PIWA2_1AL_TPAD_BINS_STAT  CHAR (1),                          00009265
          2 PIWA2_1AL_TPAD_FILL         CHAR (4);                          00009365
                                                                           00009465
    DCL  PIWA2_1AL_SANBORN_BVOLPAGE         CHAR(8)                        00009565
            BASED(ADDR(PIWA2_1AL_SANBORN));                                00009665
    DCL  PIWA2_1AL_STROLLKEY                CHAR(19)                       00009765
            BASED(ADDR(PIWA2_1AL_STROLL_KEY));                             00009865
                                                                           00009965
                                                                           00010065
    DCL 1 PIWA2_1EX BASED(ADDR(P2PL11AL)),                                 00010165
                                                                           00010265
     /*******************************************************************/ 00010365
     /***              WORK AREA 2 FOR FUNCTION 1/1E EXTENDED         ***/ 00010465
     /***                                                             ***/ 00010565
     /*******************************************************************/ 00010665
     /*******************************************************************/ 00010765
                                                                           00010865
     /*******************************************************************/ 00010915
     /***                                                             ***/ 00011015
     /*** THE FOLLOWING FIELDS ARE FROM FUNCTION 1/1E                 ***/ 00011115
     /*******************************************************************/ 00011215
        2 PIWA2_1EX_ACCESS_KEY            CHAR(21),                        00011338
        2 PIWA2_1EX_CONT_PARITY           CHAR(1),/*(OR DUP ADDR IND)*/    00011438
        2 PIWA2_1EX_LOW_HOUSENUM          CHAR(11),/* SORT FORMAT */       00011538
        2 PIWA2_1EX_HI_HOUSENUM           CHAR(11),/* SORT FORMAT */       00011638
        2 PIWA2_1EX_DCP_PREF_LGC          CHAR(2),                         00011738
        2 PIWA2_1EX_NUM_X_ST_LOW_END      CHAR(1),                         00011838
        2 PIWA2_1EX_LOW_B5SC(5)           CHAR(6),                         00011938
        2 PIWA2_1EX_NUM_X_ST_HI_END       CHAR(1),                         00012038
        2 PIWA2_1EX_HI_B5SC(5)            CHAR(6),                         00012138
        2 PIWA2_1EX_LIONKEY,                                               00012238
          3 PIWA2_1EX_LION_BORO           CHAR(1),                         00012338
          3 PIWA2_1EX_LION_FACECODE       CHAR(4),                         00012438
          3 PIWA2_1EX_LION_SEQ            CHAR(5),                         00012538
        2 PIWA2_1EX_SPECIAL_ADDR_FLAG     CHAR(1),                         00012638
        2 PIWA2_1EX_SIDE_OF_STR           CHAR(1),                         00012738
        2 PIWA2_1EX_SEG_LEN               CHAR(5),                         00012838
        2 PIWA2_1EX_XCOORD                CHAR(7),                         00012938
        2 PIWA2_1EX_YCOORD                CHAR(7),                         00013038
        2 FILLER_1EX_100                  CHAR(7), /* FOR ZCOORD */        00013138
        2 FILLER_1EX_200                  CHAR(1), /* FOR GSS USE*/        00013238
        2 PIWA2_1EX_MARBLE_RIKERS_FLAG    CHAR(1),                         00013338
        2 PIWA2_1EX_DOT_SLA               CHAR(1),                         00013438
        2 PIWA2_1EX_COM_DIST,                                              00013538
          3 PIWA2_1EX_COM_DIST_BORO       CHAR(1),                         00013638
          3 PIWA2_1EX_COM_DIST_NUM        CHAR(2),                         00013738
        2 PIWA2_1EX_ZIP                   CHAR(5),                         00013838
                                                                           00013915
        2 PIWA2_1EX_ELECT_DIST            CHAR(3), /*****************/     00014038
        2 PIWA2_1EX_ASSEM_DIST            CHAR(2), /* FUNCTION 1E   */     00014138
        2 PIWA2_1EX_SPLIT_ED_FLAG         CHAR(1), /* FIELDS        */     00014238
        2 PIWA2_1EX_CONG_DIST             CHAR(2), /*               */     00014338
        2 PIWA2_1EX_SENATE_DIST           CHAR(2), /*               */     00014438
        2 PIWA2_1EX_COURT_DIST            CHAR(2), /*               */     00014538
        2 PIWA2_1EX_COUNCIL_DIST          CHAR(2), /*****************/     00014638
                                                                           00014715
        2 PIWA2_1EX_HEALTH_CENTER_DIST    CHAR(2), /*HEALTH CENTER*/       00014854
        2 PIWA2_1EX_HEALTH_AREA           CHAR(4), /*HEALTH AREA*/         00014954
        2 PIWA2_1EX_SANI_DIST,                                             00015038
          3 PIWA2_1EX_SANI_DIST_BORO      CHAR(1),                         00015138
          3 PIWA2_1EX_SANI_DIST_NUM       CHAR(2),                         00015238
        2 PIWA2_1EX_SANI_SUBSEC           CHAR(2),                         00015338
        2 PIWA2_1EX_SANI_REG              CHAR(5),                         00015438
        2 PIWA2_1EX_SANI_REC              CHAR(3),                         00015538
        2 PIWA2_1EX_POLICE_DIST,                                           00015638
          3  PIWA2_1EX_POL_PAT_BORO_CMD   CHAR(1),                         00015738
          3  PIWA2_1EX_POL_PRECINCT       CHAR(3),                         00015838
        2 PIWA2_1EX_FIRE_DIV              CHAR(2),                         00015938
        2 PIWA2_1EX_FIRE_BAT              CHAR(2),                         00016038
        2 PIWA2_1EX_FIRE_CO,                                               00016138
          3 PIWA2_1EX_FIRE_CO_TYPE        CHAR(1),                         00016238
          3 PIWA2_1EX_FIRE_CO_NUM         CHAR(3),                         00016338
        2 PIWA2_1EX_FILL_DIST_SPLT_FLAG   CHAR(1),                         00016438
        2 PIWA2_1EX_SCHL_DIST             CHAR(2),                         00016538
        2 PIWA2_1EX_DYN_BLK               CHAR(3), /*ATOMIC POLYGON*/      00016638
        2 PIWA2_1EX_POLICE_PAT_BORO       CHAR(2),                         00016769
        2 PIWA2_1EX_FEATURE_TYPE          CHAR(1),                         00016838
        2 PIWA2_1EX_SEGMENT_TYPE          CHAR(1),                         00016938
        2 PIWA2_1EX_ALX                   CHAR(1),                         00017038
        2 PIWA2_1EX_COINCIDENT_SEG_CTR    CHAR(1),                         00017138
        2 FILLER_1EX_290                  CHAR(2),                         00017255
        2 PIWA2_1EX_CENS_TRCT_BORO        CHAR(1),  /*USED FOR GRIDGEN*/   00017355
        2 PIWA2_1EX_1990_CENS_TRCT        CHAR(6),                         00017455
        2 PIWA2_1EX_2010_CENSUS_TRACT     CHAR(6),                         00017555
        2 PIWA2_1EX_2010_CENSUS_BLOCK     CHAR(4),                         00017655
        2 PIWA2_1EX_2010_CENSUS_BLK_SF    CHAR(1), /*NOT IMPLEMENTED*/     00017755
        2 PIWA2_1EX_2000_CENS_TRACT       CHAR(6),                         00017855
        2 PIWA2_1EX_2000_CENS_BLOCK       CHAR(4),                         00017955
        2 PIWA2_1EX_2000_CENS_BLK_S       CHAR(1),                         00018055
        2 PIWA2_1EX_NTA                   CHAR(4), /*NEIGHBORHOOD     */   00018155
                                                   /*TABULATION AREA  */   00018255
        2 PIWA2_1EX_SANIT_SNOW_PRIORITY   CHAR(1), /*SANITATION STRT  */   00018355
                                                   /*SNOW PRIORITY    */   00018455
        2 PIWA2_1EX_SANIT_ORGANICS        CHAR(5), /*SANITATION       */   00018559
                                                   /*ORGANIC PICK UP  */   00018657
        2 PIWA2_1EX_SANIT_BULK_PICK_UP    CHAR(5), /*SANITATION BULK  */   00018776
     /* 2 PIWA2_1EX_SANIT_RESERVED *V16.4*CHAR(5),  *SANITATION RESERVE*/  00018876
        2 PIWA2_1EX_HURRICANE_ZONE        CHAR(2), /*OEM HURRICANE     */  00018976
                                                   /*EVACUATION ZONE   */  00019076
        2 FILLER_1EX_400                  CHAR(11),                        00019176
        2 PIWA2_1EX_UHNS                  CHAR(11),                        00019276
        2 PIWA2_1EX_REAL_B7SC             CHAR(8),                         00019376
        2 PIWA2_1EX_SEGMENT_ID            CHAR(7),                         00019476
        2 PIWA2_1EX_CURVE_FLAG            CHAR(1),                         00019576
        2 PIWA2_1EX_LGCS                  CHAR(8),                         00019676
        2 PIWA2_1EX_BOE_PTR               CHAR(1),                         00019776
        2 PIWA2_1EX_AZIMUTH               CHAR(3),                         00019876
        2 PIWA2_1EX_ORIENT                CHAR(1),                         00019976
        2 PIWA2_1EX_X_LOW                 CHAR(7),                         00020076
        2 PIWA2_1EX_Y_LOW                 CHAR(7),                         00020176
        2 PIWA2_1EX_Z_LOW                 CHAR(7), /*NOT IMPLEMENTED*/     00020276
        2 PIWA2_1EX_X_HI                  CHAR(7),                         00020376
        2 PIWA2_1EX_Y_HI                  CHAR(7),                         00020476
        2 PIWA2_1EX_Z_HI                  CHAR(7), /*NOT IMPLEMENTED*/     00020576
        /* SPATIAL COORDINATES OF CENTER OF CURVATURE                 */   00020676
        2 PIWA2_1EX_X_CC                  CHAR(7),                         00020776
        2 PIWA2_1EX_Y_CC                  CHAR(7),                         00020876
        2 PIWA2_1EX_Z_CC                  CHAR(7), /*NOT IMPLEMENTED*/     00020976
        2 PIWA2_1EX_RADIUS                CHAR(7),                         00021076
        2 PIWA2_1EX_SECANT                CHAR(1),                         00021176
        2 PIWA2_1EX_ANGLE_FROM            CHAR(5),                         00021276
        2 PIWA2_1EX_ANGLE_TO              CHAR(5),                         00021376
        2 PIWA2_1EX_NODE_FROM             CHAR(7),                         00021476
        2 PIWA2_1EX_NODE_TO               CHAR(7),                         00021576
        2 PIWA2_1EX_VANITY_LION           CHAR(10),                        00021676
        2 PIWA2_1EX_SOS                   CHAR(1),                         00021776
        2 PIWA2_1EX_SPLIT_LOHSN           CHAR(11),                        00021876
        2 PIWA2_1EX_TD                    CHAR(1),                         00021976
        2 PIWA2_1EX_TR                    CHAR(10),                        00022076
        2 PIWA2_1EX_CURVE_FRACTION        CHAR(3),                         00022176
        2 PIWA2_1EX_ROADWAY_TYPE          CHAR(2),                         00022276
        2 PIWA2_1EX_PHYSICAL_ID           CHAR(7),                         00022376
        2 PIWA2_1EX_GENERIC_ID            CHAR(7),                         00022476
        2 PIWA2_1EX_INTP_ID               CHAR(7),  /*INTERNAL USE*/       00022576
        2 PIWA2_1EX_INTF_ID               CHAR(7),  /*INTERNAL USE*/       00022676
        2 PIWA2_1EX_BIKE_LANE_2           CHAR(2),                         00022776
        2 PIWA2_1EX_BIKE_TRAFFIC_DIR      CHAR(2),                         00022879
        2 PIWA2_1EX_FILL450               CHAR(3),                         00022979
     /* 2 PIWA2_1EX_FILL450  * V17.1 *    CHAR(5),  **/                    00023079
     /* 2 PIWA2_1EX_FILL450  * V16.4 *    CHAR(7),  **/                    00023179
     /* 2 PIWA2_1EX_BLOCKFACE_ID * V16.1* CHAR(7),  **/                    00023279
        2 PIWA2_1EX_STREET_STATUS         CHAR(1),                         00023379
        2 PIWA2_1EX_STREET_WIDTH          CHAR(3),                         00023479
        2 PIWA2_1EX_STREET_WIDTH_IRR      CHAR(1),                         00023579
        2 PIWA2_1EX_BIKE_LANE             CHAR(1),                         00023679
        2 PIWA2_1EX_FED_CLASS_CODE        CHAR(2),                         00023779
        2 PIWA2_1EX_ROW_TYPE              CHAR(1),                         00023879
        2 PIWA2_1EX_LGC_LIST_2            CHAR(10),                        00023979
        2 PIWA2_1EX_LEGACY_SEG_ID         CHAR(7),                         00024079
        2 PIWA2_1EX_LGC_LIST_FROM_1       CHAR(10),                        00024179
        2 PIWA2_1EX_LGC_LIST_TO_1         CHAR(10),                        00024279
        2 PIWA2_1EX_LGC_LIST_FROM_2       CHAR(10),                        00024379
        2 PIWA2_1EX_LGC_LIST_TO_2         CHAR(10),                        00024479
        2 PIWA2_1EX_NOCROSS_FLG           CHAR(1),                         00024579
        2 PIWA2_1EX_IND_SEG_LEN           CHAR(5),                         00024679
        2 PIWA2_1EX_NTA_NAME              CHAR(75),                        00024779
        2 PIWA2_1EX_USPS_CITY_NAME        CHAR(25),                        00024879
        2 PIWA2_1EX_LATITUDE              CHAR(9),                         00024979
        2 PIWA2_1EX_LONGITUDE             CHAR(11),                        00025079
        2 PIWA2_1EX_SEG_FROM_NODE         CHAR(7),                         00025179
        2 PIWA2_1EX_SEG_TO_NODE           CHAR(7),                         00025279
        2 PIWA2_1EX_SEG_FROM_XYZ          CHAR(21),                        00025379
        2 PIWA2_1EX_SEG_TO_XYZ            CHAR(21),                        00025479
        2 PIWA2_1EX_BLOCKFACE_ID          CHAR(10),                        00025579
        2 PIWA2_1EX_NBR_TRAVEL_LANES      CHAR(2),                         00025679
        2 PIWA2_1EX_NBR_PARK_LANES        CHAR(2),                         00025779
        2 PIWA2_1EX_NBR_TOTAL_LANES       CHAR(2),                         00025879
        2 PIWA2_1EX_STR_WIDTH_MAX         CHAR(3),                         00025979
        2 PIWA2_1EX_FILL500               CHAR(252),                       00026079
     /* 2 PIWA2_1EX_FILL500 ** V16.4 **   CHAR(255) **/                    00026179
     /* 2 PIWA2_1EX_FILL500 ** V16.1 **   CHAR(271) **/                    00026279
     /* 2 PIWA2_1EX_FILL500 ** V15.3 **   CHAR(327) **/                    00026379
     /*******************************************************************/ 00026479
     /***                                                             ***/ 00026579
     /*** THE FOLLOWING FIELDS ARE AN ADDITION TO 1E                  ***/ 00026679
     /*******************************************************************/ 00026779
        2 PIWA2_1EX_REASON_CODE           CHAR(1),                         00026879
        2 PIWA2_1EX_REASON_CODE_QUAL      CHAR(1),                         00026979
        2 PIWA2_1EX_WARN_CODE             CHAR(2),                         00027079
        2 PIWA2_1EX_RETURN_CODE           CHAR(2),                         00027179
        2 PIWA2_1EX_NUM_X_STS_LO_END      CHAR(1),                         00027279
        2 PIWA2_1EX_LO_B7SC(5)            CHAR(8),                         00027379
        2 PIWA2_1EX_NUM_X_STS_HI_END      CHAR(1),                         00027479
        2 PIWA2_1EX_HI_B7SC(5)            CHAR(8),                         00027579
        2 PIWA2_1EX_LO_ST_NAME(5)         CHAR(32),                        00027679
        2 PIWA2_1EX_HI_ST_NAME(5)         CHAR(32),                        00027779
        2 PIWA2_1EX_BOE_B7SC              CHAR(8),                         00027879
        2 PIWA2_1EX_BOE_ST_NAME           CHAR(32),                        00027979
        2 PIWA2_1EX_FILL600               CHAR(52);                        00028079
                                                                           00028179
                                                                           00028279
                                                                           00028379
    DCL 1 PIWA2_FN1AX BASED(ADDR(P2PL11AL)),                               00028479
     /*******************************************************************/ 00028579
     /***              WORK AREA 2 FOR FUNCTION 1A EXTENDED           ***/ 00028679
     /***                                                             ***/ 00028779
     /*******************************************************************/ 00028879
                                                                           00028979
                                                                           00029079
       2 PIWA2_1AX_ACCESS_KEY               CHAR(21),                      00029179
       2 PIWA2_1AX_CONT_PARITY              CHAR(1), /*(OR DUP ADDR IND)*/ 00029279
       2 PIWA2_1AX_LOW_HOUSENUM             CHAR(11), /* SORT FORMAT */    00029379
       2 PIWA2_1AX_BBL,                                                    00029479
         3 PIWA2_1AX_BBL_BORO               CHAR(1),                       00029579
         3 PIWA2_1AX_BLOCK                  CHAR(5),                       00029679
         3 PIWA2_1AX_LOT                    CHAR(4),                       00029779
       2 PIWA2_1AX_LOT_VER                  CHAR(1),                       00029879
       2 PIWA2_1AX_SCC                      CHAR(1),                       00029979
       2 FILLER_1AX1                        CHAR(1),                       00030079
       2 PIWA2_1AX_GENERAL_LOT_INFO,                                       00030179
         3 PIWA2_1AX_RPAD_BLDG_CLASS        CHAR(2),                       00030279
         3 PIWA2_1AX_CORNER_CODE            CHAR(2),                       00030379
         3 PIWA2_1AX_NUM_OF_STRUCTURES      CHAR(4),                       00030479
         3 PIWA2_1AX_NUM_OF_BLOCKFACES      CHAR(2),                       00030579
         3 PIWA2_1AX_INTERIOR_FLAG          CHAR(1),                       00030679
         3 PIWA2_1AX_VACANT_FLAG            CHAR(1),                       00030779
         3 PIWA2_1AX_IRREG_LOT_FLAG         CHAR(1),                       00030879
       2 PIWA2_1AX_MARBLE_RIKERS_FLAG       CHAR(1),                       00030979
       2 PIWA2_1AX_ADDR_LIST_OVFLOW_FLAG    CHAR(1),                       00031079
       2 PIWA2_1AX_STROLL_KEY,                                             00031179
         3 PIWA2_1AX_STROLL_BORO            CHAR(1),                       00031279
         3 PIWA2_1AX_STROLL_5SC             CHAR(5),                       00031379
         3 PIWA2_1AX_STROLL_SIDE_OF_STR     CHAR(1),    /* L, R */         00031479
         3 PIWA2_1AX_STROLL_HI_HOUSENUM     CHAR(11), /* SORT FORMAT */    00031579
         3 FILLER_1AX2                      CHAR(1),                       00031679
       2 FILLER_1AX3                        CHAR(1),  /* FOR GSS USE*/     00031779
       2 PIWA2_1AX_BIN                      CHAR(7),                       00031879
       2 PIWA2_1AX_CONDO_FLAG               CHAR(1),                       00031979
       2 FILLER_1AX4                        CHAR(1),                       00032079
       2 PIWA2_1AX_RPAD_CONDO_ID_NUM        CHAR(4),                       00032179
       2 PIWA2_1AX_CONDO_UNIT_ID_NUM        CHAR(7),                       00032279
       2 PIWA2_1AX_CONDO_BILL_BBL           CHAR(10),                      00032379
       2 PIWA2_1AX_CONDO_BILL_BBL_VER       CHAR(1),                       00032479
       2 PIWA2_1AX_CONDO_BILL_BBL_SCC       CHAR(1),                       00032579
       2 PIWA2_1AX_CONDO_LOW_BBL            CHAR(10),                      00032679
       2 PIWA2_1AX_CONDO_LOW_BBL_VER        CHAR(1),                       00032779
       2 PIWA2_1AX_CONDO_HIGH_BBL           CHAR(10),                      00032879
       2 PIWA2_1AX_CONDO_HIGH_BBL_VER       CHAR(1),                       00032979
       2 FILLER_1AX5                        CHAR(15),                      00033079
       2 PIWA2_1AX_COOP_NUM                 CHAR(4),                       00033179
       2 PIWA2_1AX_SANBORN,                                                00033279
         3 PIWA2_1AX_SANBORN_BORO           CHAR(1),                       00033379
         3 PIWA2_1AX_SANBORN_VOL            CHAR(3),                       00033479
         3 PIWA2_1AX_SANBORN_PAGE           CHAR(4),                       00033579
       2 PIWA2_1AX_COMMERC_DIST             CHAR(5),                       00033679
       2 PIWA2_1AX_DOF_MAP_BORO             CHAR(1),                       00033779
       2 PIWA2_1AX_DOF_MAP_SECVOL           CHAR(4),                       00033879
       2 PIWA2_1AX_DOF_MAP_PAGE             CHAR(4),                       00033979
       2 PIWA2_1AX_RESERVED                 CHAR(03),                      00034079
       2 PIWA2_1AX_LATITUDE                 CHAR(09),                      00034179
       2 PIWA2_1AX_LONGITUDE                CHAR(11),                      00034279
       2 PIWA2_1AX_X_COORD                  CHAR(07),                      00034379
       2 PIWA2_1AX_Y_COORD                  CHAR(07),                      00034479
       2 PIWA2_1AX_BID                      CHAR(06),                      00034579
       2 PIWA2_1AX_TPAD_BIN_ST              CHAR(01),  /*CURRENT STATUS*/  00034679
       2 PIWA2_1AX_TPAD_NEW_BIN             CHAR(07),  /*NEW BIN       */  00034779
       2 PIWA2_1AX_TPAD_NEW_BIN_ST          CHAR(01),  /*NEW BIN STATUS*/  00034879
       2 PIWA2_1AX_TPAD_CONFLICT            CHAR(01),  /*CONFLICT FLAG */  00034979
       2 FILLER_1AX7                        CHAR(09),                      00035079
       2 FILLER_1AX8                        CHAR(8),  /* LGC - GSS USE*/   00035179
       2 PIWA2_1AX_REASON_CODE              CHAR(01),                      00035279
       2 PIWA2_1AX_REASON_CODE_QUAL         CHAR(01),                      00035379
       2 PIWA2_1AX_WARN_CODE                CHAR(02),                      00035479
       2 PIWA2_1AX_RETURN_CODE              CHAR(02),                      00035579
       2 FILLER_1AX9                        CHAR(108),                     00035679
       2 PIWA2_1AX_NUM_OF_ADDR              CHAR(4),                       00035779
       2 PIWA2_1AX_ADDR_LIST(21),                                          00035879
         3 PIWA2_1AX_LIST_LOW_HOUSENUM      CHAR(16), /*DISPLAY FORMAT*/   00035979
         3 PIWA2_1AX_LIST_HI_HOUSENUM       CHAR(16), /*DISPLAY FORMAT*/   00036079
         3 PIWA2_1AX_LIST_BORO              CHAR(1),                       00036179
         3 PIWA2_1AX_LIST_5SC               CHAR(5),                       00036279
         3 PIWA2_1AX_LIST_LGC               CHAR(2),                       00036379
         3 PIWA2_1AX_LIST_BIN               CHAR(7),                       00036479
         3 PIWA2_1AX_LIST_SIDE_OF_STR       CHAR(1),  /* L, R */           00036579
         3 PIWA2_1AX_ADDR_TYPE              CHAR(1),  /*               */  00036679
                                                      /* BLANK = NORMAL*/  00036779
         3 PIWA2_1AX_TPAD_STATUS            CHAR(1),                       00036879
         3 PIWA2_1AX_ST_NAME                CHAR(32),                      00036979
         3 FILLER_1AX10                     CHAR(34);                      00037079
                                                                           00037179
                                                                           00037279
    DCL 1 PIWA2_FN1B BASED(ADDR(P2PL11AL)),                                00037379
                                                                           00037479
     /*******************************************************************/ 00037579
     /***              WORK AREA 2 FOR FUNCTION 1B                    ***/ 00037679
     /***                                                             ***/ 00037779
     /*******************************************************************/ 00037879
        2 PIWA2_1B_1_ACCESS_KEY               CHAR(21),                    00037979
        2 PIWA2_1B_1_CONT_PARITY              CHAR(1),  /*(DUP ADDR IND)*/ 00038079
        2 PIWA2_1B_1_LOW_HOUSENUM             CHAR(11), /* SORT FORMAT */  00038179
        2 PIWA2_1B_1_HI_HOUSENUM              CHAR(11), /* SORT FORMAT */  00038279
        2 PIWA2_1B_1_PREF_LGC                 CHAR(2),                     00038379
        2 PIWA2_1B_1_NUM_X_ST_LOW_END         CHAR(1),                     00038479
        2 PIWA2_1B_1_LOW_B5SC(5)              CHAR(6),                     00038579
        2 PIWA2_1B_1_NUM_X_ST_HI_END          CHAR(1),                     00038679
        2 PIWA2_1B_1_HI_B5SC(5)               CHAR(6),                     00038779
        2 PIWA2_1B_1_LIONKEY,                                              00038879
          3 PIWA2_1B_1_LION_BORO              CHAR(1),                     00038979
          3 PIWA2_1B_1_LION_FACECODE          CHAR(4),                     00039079
          3 PIWA2_1B_1_LION_SEQ               CHAR(5),                     00039179
        2 PIWA2_1B_1_SPECIAL_ADDR_FLAG        CHAR(1),                     00039279
        2 PIWA2_1B_1_SIDE_OF_STR              CHAR(1),                     00039379
        2 PIWA2_1B_1_SEG_LEN                  CHAR(5),                     00039479
        2 PIWA2_1B_1_XCOORD                   CHAR(7),                     00039579
        2 PIWA2_1B_1_YCOORD                   CHAR(7),                     00039679
        2 FILLER_1B_1_100                     CHAR(7), /* FOR ZCOORD */    00039779
        2 FILLER_1B_1_200                     CHAR(1), /* FOR GSS USE*/    00039879
        2 PIWA2_1B_1_MARBLE_RIKERS_FLAG       CHAR(1),                     00039979
        2 PIWA2_1B_1_DOT_SLA                  CHAR(1),                     00040079
        2 PIWA2_1B_1_COM_DIST,                                             00040179
          3 PIWA2_1B_1_COM_DIST_BORO          CHAR(1),                     00040279
          3 PIWA2_1B_1_COM_DIST_NUM           CHAR(2),                     00040379
        2 PIWA2_1B_1_ZIP                      CHAR(5),                     00040479
                                                                           00040579
        2 PIWA2_1B_1_ELECT_DIST               CHAR(3), /*****************/ 00040679
        2 PIWA2_1B_1_ASSEM_DIST               CHAR(2), /* FUNCTION 1E   */ 00040779
        2 PIWA2_1B_1_SPLIT_ED_FLAG            CHAR(1), /* FIELDS        */ 00040879
        2 PIWA2_1B_1_CONG_DIST                CHAR(2), /*               */ 00040979
        2 PIWA2_1B_1_SENATE_DIST              CHAR(2), /*               */ 00041079
        2 PIWA2_1B_1_COURT_DIST               CHAR(2), /*               */ 00041179
        2 PIWA2_1B_1_COUNCIL_DIST             CHAR(2), /*****************/ 00041279
                                                                           00041379
        2 PIWA2_1B_1_HEALTH_CENTER_DIST       CHAR(2),                     00041479
        2 PIWA2_1B_1_HEALTH_AREA              CHAR(4),                     00041579
        2 PIWA2_1B_1_SANI_DIST,                                            00041679
          3 PIWA2_1B_1_SANI_DIST_BORO         CHAR(1),                     00041779
          3 PIWA2_1B_1_SANI_DIST_NUM          CHAR(2),                     00041879
        2 PIWA2_1B_1_SANI_SUBSEC              CHAR(2),                     00041979
        2 PIWA2_1B_1_SANI_REG                 CHAR(5),                     00042079
        2 PIWA2_1B_1_SANI_REC                 CHAR(3),                     00042179
        2 PIWA2_1B_1_POLICE_DIST,                                          00042279
          3  PIWA2_1B_1_POL_PAT_BORO_CMD      CHAR(1),                     00042379
          3  PIWA2_1B_1_POL_PRECINCT          CHAR(3),                     00042479
        2 PIWA2_1B_1_FIRE_DIV                 CHAR(2),                     00042579
        2 PIWA2_1B_1_FIRE_BAT                 CHAR(2),                     00042679
        2 PIWA2_1B_1_FIRE_CO,                                              00042779
          3 PIWA2_1B_1_FIRE_CO_TYPE           CHAR(1),                     00042879
          3 PIWA2_1B_1_FIRE_CO_NUM            CHAR(3),                     00042979
        2 PIWA2_1B_1_FILL_DIST_SPLIT_FLAG     CHAR(1),                     00043079
        2 PIWA2_1B_1_SCHL_DIST                CHAR(2),                     00043179
        2 PIWA2_1B_1_DYN_BLK                  CHAR(3), /*ATOMIC POLYGON*/  00043279
        2 PIWA2_1B_1_POLICE_PAT_BORO          CHAR(2),                     00043379
        2 PIWA2_1B_1_FEATURE_TYPE             CHAR(1),                     00043479
        2 PIWA2_1B_1_SEGMENT_TYPE             CHAR(1),                     00043579
        2 PIWA2_1B_1_ALX                      CHAR(1),                     00043679
        2 PIWA2_1B_1_COINCIDENT_SEG_CTR       CHAR(1),                     00043779
        2 FILLER_1B_1_290                     CHAR(2),                     00043879
        2 PIWA2_1B_1_CENS_TRCT_BORO           CHAR(1),                     00043979
        2 PIWA2_1B_1_1990_CENS_TRCT           CHAR(6),                     00044079
        2 PIWA2_1B_1_2010_CENSUS_TRACT        CHAR(6),                     00044179
        2 PIWA2_1B_1_2010_CENSUS_BLOCK        CHAR(4),                     00044279
        2 PIWA2_1B_1_2010_CENSUS_BLK_SF       CHAR(1), /*NOT IMPLELMENTED*/00044379
        2 PIWA2_1B_1_2000_CENS_TRACT          CHAR(6),                     00044479
        2 PIWA2_1B_1_2000_CENS_BLOCK          CHAR(4),                     00044579
        2 PIWA2_1B_1_2000_CENS_BLK_S          CHAR(1),                     00044679
        2 PIWA2_1B_1_NTA                      CHAR(4), /*NEIGHBORHOOD    */00044779
                                                       /*TABULATION AREA */00044879
        2 PIWA2_1B_1_SANIT_SNOW_PRIORITY      CHAR(1), /*SANITATION STRT*/ 00044979
                                                       /*SNOW PRIORITY */  00045079
        2 PIWA2_1B_1_SANIT_ORGANICS           CHAR(5), /*SANITATION */     00045179
                                                       /*ORGANIC PICK UP*/ 00045279
        2 PIWA2_1B_1_SANIT_BULK_PICK_UP       CHAR(5), /*SANIT BULK   */   00045379
     /* 2 PIWA2_1B_1_SANIT_RESERVE *V16.4 **  CHAR(5),  *SANIT RESERVE*/   00045479
        2 PIWA2_1B_1_HURRICANE_ZONE           CHAR(2), /*OEM HURRICANE */  00045579
                                                       /*EVACUATION ZONE*/ 00045679
        2 FILLER_1B_1_400                     CHAR(11),                    00045779
        2 PIWA2_1B_1_UHNS                     CHAR(11),                    00045879
        2 PIWA2_1B_1_REAL_B7SC                CHAR(8),                     00045979
        2 PIWA2_1B_1_SEGMENT_ID               CHAR(7),                     00046079
        2 PIWA2_1B_1_CURVE_FLAG               CHAR(1),                     00046179
        2 PIWA2_1B_1_LGCS                     CHAR(8),                     00046279
        2 PIWA2_1B_1_BOE_PTR                  CHAR(1),                     00046379
        2 PIWA2_1B_1_AZIMUTH                  CHAR(3),                     00046479
        2 PIWA2_1B_1_ORIENT                   CHAR(1),                     00046579
        2 PIWA2_1B_1_X_LOW                    CHAR(7),                     00046679
        2 PIWA2_1B_1_Y_LOW                    CHAR(7),                     00047027
        2 PIWA2_1B_1_Z_LOW                    CHAR(7), /*NOT IMPLEMENTED*/ 00048027
        2 PIWA2_1B_1_X_HI                     CHAR(7),                     00049027
        2 PIWA2_1B_1_Y_HI                     CHAR(7),                     00049127
        2 PIWA2_1B_1_Z_HI                     CHAR(7), /*NOT IMPLEMENTED*/ 00049227
        /* SPATIAL COORDINATES OF CENTER OF CURVATURE                 */   00049327
        2 PIWA2_1B_1_X_CC                     CHAR(7),                     00049427
        2 PIWA2_1B_1_Y_CC                     CHAR(7),                     00049527
        2 PIWA2_1B_1_Z_CC                     CHAR(7), /*NOT IMPLEMENTED*/ 00049627
        2 PIWA2_1B_1_RADIUS                   CHAR(7),                     00049727
        2 PIWA2_1B_1_SECANT                   CHAR(1),                     00049827
        2 PIWA2_1B_1_ANGLE_FROM               CHAR(5),                     00049927
        2 PIWA2_1B_1_ANGLE_TO                 CHAR(5),                     00050027
        2 PIWA2_1B_1_NODE_FROM                CHAR(7),                     00051027
        2 PIWA2_1B_1_NODE_TO                  CHAR(7),                     00052027
        2 PIWA2_1B_1_VANITY_LION              CHAR(10),                    00053027
        2 PIWA2_1B_1_SOS                      CHAR(1),                     00054027
        2 PIWA2_1B_1_SPLIT_LOHSN              CHAR(11),                    00055027
        2 PIWA2_1B_1_TD                       CHAR(1),                     00056027
        2 PIWA2_1B_1_TR                       CHAR(10),                    00057027
        2 PIWA2_1B_1_CURVE_FRACTION           CHAR(3),                     00058027
        2 PIWA2_1B_1_ROADWAY_TYPE             CHAR(2),                     00058132
        2 PIWA2_1B_1_PHYSICAL_ID              CHAR(7),                     00058232
        2 PIWA2_1B_1_GENERIC_ID               CHAR(7),                     00058332
        2 PIWA2_1B_1_INTP_ID                  CHAR(7),  /*INTERNAL USE*/   00058436
        2 PIWA2_1B_1_INTF_ID                  CHAR(7),  /*INTERNAL USE*/   00058536
        2 PIWA2_1B_1_BIKE_LANE_2              CHAR(2),                     00058676
        2 PIWA2_1B_1_BIKE_TRAFFIC_DIR         CHAR(2),                     00058781
        2 PIWA2_1B_1_FILL450                  CHAR(3),                     00058879
     /* 2 PIWA2_1B_1_FILL450      ** V17.1 ** CHAR(5),**/                  00058979
     /* 2 PIWA2_1B_1_FILL450      ** V16.4 ** CHAR(7),**/                  00059079
     /* 2 PIWA2_1B_1_BLOCKFACE_ID ** V16.1 ** CHAR(7) **/                  00059179
        2 PIWA2_1B_1_STREET_STATUS            CHAR(1),                     00059279
        2 PIWA2_1B_1_STREET_WIDTH             CHAR(3),                     00059379
        2 PIWA2_1B_1_STREET_WIDTH_IRR         CHAR(1),                     00059479
        2 PIWA2_1B_1_BIKE_LANE                CHAR(1),                     00059579
        2 PIWA2_1B_1_FED_CLASS_CODE           CHAR(2),                     00059679
        2 PIWA2_1B_1_ROW_TYPE                 CHAR(1),                     00059779
        2 PIWA2_1B_1_LGC_LIST_2               CHAR(10),                    00059879
        2 PIWA2_1B_1_LEGACY_SEG_ID            CHAR(7),                     00059979
        2 PIWA2_1B_1_LGC_LIST_FROM_1          CHAR(10),                    00060079
        2 PIWA2_1B_1_LGC_LIST_TO_1            CHAR(10),                    00060179
        2 PIWA2_1B_1_LGC_LIST_FROM_2          CHAR(10),                    00060279
        2 PIWA2_1B_1_LGC_LIST_TO_2            CHAR(10),                    00060379
        2 PIWA2_1B_1_NOCROSS_FLG              CHAR(1),                     00060479
        2 PIWA2_1B_1_IND_SEG_LEN              CHAR(5),                     00060579
        2 PIWA2_1B_1_NTA_NAME                 CHAR(75),                    00060679
        2 PIWA2_1B_1_USPS_CITY_NAME           CHAR(25),                    00060779
        2 PIWA2_1B_1_LATITUDE                 CHAR(9),                     00060879
        2 PIWA2_1B_1_LONGITUDE                CHAR(11),                    00060979
        2 PIWA2_1B_1_SEG_FROM_NODE            CHAR(7),                     00061079
        2 PIWA2_1B_1_SEG_TO_NODE              CHAR(7),                     00061179
        2 PIWA2_1B_1_SEG_FROM_XYZ             CHAR(21),                    00061279
        2 PIWA2_1B_1_SEG_TO_XYZ               CHAR(21),                    00061379
        2 PIWA2_1B_1_BLOCKFACE_ID             CHAR(10),                    00061479
        2 PIWA2_1B_1_NBR_TRAVEL_LANES         CHAR(2),                     00061579
        2 PIWA2_1B_1_NBR_PARK_LANES           CHAR(2),                     00061679
        2 PIWA2_1B_1_NBR_TOTAL_LANES          CHAR(2),                     00061779
        2 PIWA2_1B_1_STREET_WIDTH_MAX         CHAR(3),                     00061879
        2 PIWA2_1B_1_FILL500                  CHAR(252),                   00061979
     /* 2 PIWA2_1B_1_FILL500 ** V16.4 **      CHAR(255) **/                00062079
     /**2 PIWA2_1B_1_FILL500 ** V16.1  **     CHAR(271) **/                00062173
     /**2 PIWA2_1B_1_FILL500 ** V15.3  **     CHAR(327) **/                00062270
     /*******************************************************************/ 00062370
     /***                                                             ***/ 00062470
     /*** THE FOLLOWING FIELDS ARE AN ADDITION TO 1/1E                ***/ 00062570
     /*******************************************************************/ 00062670
        2 PIWA2_1B_1_REASON_CODE              CHAR(1),                     00062770
        2 PIWA2_1B_1_REASON_CODE_QUAL         CHAR(1),                     00062870
        2 PIWA2_1B_1_WARN_CODE                CHAR(2),                     00062970
        2 PIWA2_1B_1_RETURN_CODE              CHAR(2),                     00063070
        2 PIWA2_1B_1_NUM_X_STS_LO_END         CHAR(1),                     00063127
        2 PIWA2_1B_1_LO_B7SC(5)               CHAR(8),                     00063227
        2 PIWA2_1B_1_NUM_X_STS_HI_END         CHAR(1),                     00064027
        2 PIWA2_1B_1_HI_B7SC(5)               CHAR(8),                     00065027
        2 PIWA2_1B_1_LO_ST_NAME(5)            CHAR(32),                    00066027
        2 PIWA2_1B_1_HI_ST_NAME(5)            CHAR(32),                    00067027
        2 PIWA2_1B_1_BOE_B7SC                 CHAR(8),                     00068027
        2 PIWA2_1B_1_BOE_ST_NAME              CHAR(32),                    00069027
        2 PIWA2_1B_1_FILL600                  CHAR(52),                    00069127
                                                                           00069227
     /*******************************************************************/ 00069627
     /***   THE FOLLOWING ARE FROM THE 1A WORK AREA 2                 ***/ 00069727
     /***                                                             ***/ 00069827
     /*******************************************************************/ 00069927
                                                                           00070027
       2 PIWA2_1B_1A_ACCESS_KEY               CHAR(21),                    00072027
       2 PIWA2_1B_1A_CONT_PARITY              CHAR(1), /*(DUP ADDR IND)*/  00073027
       2 PIWA2_1B_1A_LOW_HOUSENUM             CHAR(11), /* SORT FORMAT */  00074027
       2 PIWA2_1B_1A_BBL,                                                  00075027
         3 PIWA2_1B_1A_BBL_BORO               CHAR(1),                     00076027
         3 PIWA2_1B_1A_BLOCK                  CHAR(5),                     00077027
         3 PIWA2_1B_1A_LOT                    CHAR(4),                     00078027
       2 PIWA2_1B_1A_LOT_VER                  CHAR(1),                     00079027
       2 PIWA2_1B_1A_SCC                      CHAR(1),                     00079127
       2 FILLER_1B_1A_1                       CHAR(1),                     00079227
       2 PIWA2_1B_1A_GENERAL_LOT_INFO,                                     00079327
         3 PIWA2_1B_1A_RPAD_BLDG_CLASS        CHAR(2),                     00079427
         3 PIWA2_1B_1A_CORNER_CODE            CHAR(2),                     00079527
         3 PIWA2_1B_1A_NUM_OF_STRUCTURES      CHAR(4),                     00079627
         3 PIWA2_1B_1A_NUM_OF_BLOCKFACES      CHAR(2),                     00079727
         3 PIWA2_1B_1A_INTERIOR_FLAG          CHAR(1),                     00079827
         3 PIWA2_1B_1A_VACANT_FLAG            CHAR(1),                     00079927
         3 PIWA2_1B_1A_IRREG_LOT_FLAG         CHAR(1),                     00080027
       2 PIWA2_1B_1A_MARBLE_RIKERS_FLAG       CHAR(1),                     00081028
       2 PIWA2_1B_1A_OVERFLOW_FLAG            CHAR(1),                     00082072
       2 PIWA2_1B_1A_STROLL_KEY,                                           00083027
         3 PIWA2_1B_1A_STROLL_BORO            CHAR(1),                     00084027
         3 PIWA2_1B_1A_STROLL_5SC             CHAR(5),                     00085027
         3 PIWA2_1B_1A_STROLL_SIDE_OF_STR     CHAR(1),    /* L, R */       00086027
         3 PIWA2_1B_1A_STROLL_HI_HOUSENUM     CHAR(11), /* SORT FORMAT */  00087027
         3 FILLER_1B_1A_2                     CHAR(1),                     00088027
       2 FILLER_1B_1A_3                       CHAR(1),  /* FOR GSS USE*/   00089029
       2 PIWA2_1B_1A_BIN                      CHAR(7),                     00089127
       2 PIWA2_1B_1A_CONDO_FLAG               CHAR(1),                     00089227
       2 FILLER_1B_1A_4                       CHAR(1),                     00089327
       2 PIWA2_1B_1A_RPAD_CONDO_ID_NUM        CHAR(4),                     00089427
       2 PIWA2_1B_1A_CONDO_UNIT_ID_NUM        CHAR(7),                     00089527
       2 PIWA2_1B_1A_CONDO_BILL_BBL           CHAR(10),                    00089627
       2 PIWA2_1B_1A_CONDO_BILL_BBL_VER       CHAR(1),                     00089727
       2 PIWA2_1B_1A_CONDO_BILL_BBL_SCC       CHAR(1),                     00089827
       2 PIWA2_1B_1A_CONDO_LOW_BBL            CHAR(10),                    00089927
       2 PIWA2_1B_1A_CONDO_LOW_BBL_VER        CHAR(1),                     00090027
       2 PIWA2_1B_1A_CONDO_HIGH_BBL           CHAR(10),                    00091027
       2 PIWA2_1B_1A_CONDO_HIGH_BBL_VER       CHAR(1),                     00092027
       2 FILLER_1B_1A_5                       CHAR(15),                    00093027
       2 PIWA2_1B_1A_COOP_NUM                 CHAR(4),                     00094027
       2 PIWA2_1B_1A_SANBORN,                                              00095027
         3 PIWA2_1B_1A_SANBORN_BORO           CHAR(1),                     00096027
         3 PIWA2_1B_1A_SANBORN_VOL            CHAR(3),                     00097027
         3 PIWA2_1B_1A_SANBORN_PAGE           CHAR(4),                     00098027
       2 PIWA2_1B_1A_COMMERC_DIST             CHAR(5),                     00099027
       2 PIWA2_1B_1A_DOF_MAP_BORO             CHAR(1),                     00099127
       2 PIWA2_1B_1A_DOF_MAP_SECVOL           CHAR(4),                     00099227
       2 PIWA2_1B_1A_DOF_MAP_PAGE             CHAR(4),                     00099327
       2 PIWA2_1B_1A_RESERVED                 CHAR(3),                     00099464
       2 PIWA2_1B_1A_LATITUDE                 CHAR(9),                     00099564
       2 PIWA2_1B_1A_LONGITUDE                CHAR(11),                    00099664
       2 PIWA2_1B_1A_X_COORD                  CHAR(07),                    00099764
       2 PIWA2_1B_1A_Y_COORD                  CHAR(07),                    00099864
       2 PIWA2_1B_1A_BID                      CHAR(06),                    00099964
       2 PIWA2_1B_1A_TPAD_BIN_ST              CHAR(01), /*CURRENT STATUS*/ 00100064
       2 PIWA2_1B_1A_TPAD_NEW_BIN             CHAR(07), /*NEW BIN       */ 00100164
       2 PIWA2_1B_1A_TPAD_NEW_BIN_ST          CHAR(01), /*NEW BIN STATUS*/ 00100264
       2 PIWA2_1B_1A_TPAD_CONFLICT            CHAR(01), /*CONFLICT FLAG */ 00101027
       2 FILLER_1B_1A_7                       CHAR(09),                    00102027
       2 FILLER_1B_1A_8                       CHAR(8),  /*LGC M GSS USE*/  00103070
       2 PIWA2_1B_1A_REASON_CODE              CHAR(01),                    00104027
       2 PIWA2_1B_1A_REASON_CODE_QUAL         CHAR(01),                    00105052
       2 PIWA2_1B_1A_WARN_CODE                CHAR(02),                    00106027
       2 PIWA2_1B_1A_RETURN_CODE              CHAR(02),                    00107027
       2 FILLER_1B_1A_9                       CHAR(108),                   00108027
       2 PIWA2_1B_1A_NUM_OF_ADDR              CHAR(4),                     00109027
       2 PIWA2_1B_1A_ADDR_LIST(21),                                        00109127
         3 PIWA2_1B_1A_LIST_LOW_HOUSENUM      CHAR(16), /*DISPLAY FORMAT*/ 00109227
         3 PIWA2_1B_1A_LIST_HI_HOUSENUM       CHAR(16), /*DISPLAY FORMAT*/ 00109327
         3 PIWA2_1B_1A_LIST_BORO              CHAR(1),                     00109427
         3 PIWA2_1B_1A_LIST_5SC               CHAR(5),                     00109527
         3 PIWA2_1B_1A_LIST_LGC               CHAR(2),                     00109627
         3 PIWA2_1B_1A_LIST_BIN               CHAR(7),                     00109727
         3 PIWA2_1B_1A_LIST_SIDE_OF_STR       CHAR(1),  /* L, R */         00109827
         3 PIWA2_1B_1A_ADDR_TYPE              CHAR(1),  /*              */ 00109927
                                                        /*BLANK = NORMAL*/ 00110027
         3 PIWA2_1B_1A_TPAD_STATUS            CHAR(1),                     00111027
         3 PIWA2_1B_1A_ST_NAME                CHAR(32),                    00112027
         3 FILLER_1B_1A_10                    CHAR(34);                    00113027
                                                                           00120019

## <span id="appendix14.18"><center>P2PL13S COPY FIle</center></span>  

    /*******************************************************************/  00000100
    /***  THIS IS THE PL/1 STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM  ***/  00000200
    /***  INDEPENDENT WORK AREA 2 FOR FUNCTION: 3S.                  ***/  00000300
    /***                                                             ***/  00000400
    /**   COPY FILE - P2PL13S.                             09/17/97  ***/  00000500
    /*******************************************************************/  00000600
    DCL                                                                    00000700
     1 P2PL13S,                                                            00000800
       2 PIWA2_3S_ACCESS_KEY,                                              00000900
         3 FILLER_GSS                       CHAR(2),                       00001000
         3 PIWA2_3S_PORS_STNAME_IND         CHAR(1),/* P = PRIMARY */      00001100
                                                    /* S = SECONDARY */    00001200
         3 PIWA2_3S_BORO                    CHAR(1),                       00001300
         3 PIWA2_3S_5SC                     CHAR(5),                       00001400
         3 PIWA2_3S_LGC                     CHAR(2),/* BLANK IF P IN */    00001500
         3 FILLER                           CHAR(10),/* POSITION 3 */      00001600
       2 PIWA2_3S_NUM_OF_INTERSECTS         CHAR(3),                       00001700
       2 PIWA2_3S_LIST_OF_INTERSECTS(350),                                 00001800
         3 PIWA2_3S_MARBLE_RIKERS_FLAG      CHAR(1),                       00001900
         3 PIWA2_3S_DISTANCE                CHAR(5),                       00002000
         3 PIWA2_3S_GAP_FLAG                CHAR(1),                       00002100
         3 FILLER_100                       CHAR(7),                       00002200
         3 PIWA2_3S_NUM_OF_STR              CHAR(1),                       00002300
         3 PIWA2_3S_B7SC(5)                 CHAR(8);                       00002400


## <span id="appendix14.19"><center>P2PL1AP COPY File</center></span>

    /*******************************************************************/  00000100
    /***  THIS IS THE PL/1 STRUCTURE FOR GEOSUPPORT SYSTEM PLATFORM  ***/  00000200
    /***  INDEPENDENT      WORK AREA 2 FOR FUNCTIONS: AP , AND APX.  ***/  00000370
    /***  MARCH 2015 BY YNL V15.2 FOR ADDRESS POINT AND AP EXTENDED. ***/  00000470
    /***  COPY FILE - P2PL1AP.                                       ***/  00001170
    /*******************************************************************/  00001226
                                                                           00001326
    DCL 1 PIWA2_FNAPX,                                                     00026170
     /*******************************************************************/ 00026263
     /***              WORK AREA 2 FOR FUNCTION AP EXTENDED           ***/ 00026370
     /***                                                             ***/ 00026463
     /*******************************************************************/ 00026563
                                                                           00026663
                                                                           00026763
       2 PIWA2_APX_ACCESS_KEY               CHAR(21),                      00026870
       2 PIWA2_APX_CONT_PARITY              CHAR(1), /*(OR DUP ADDR IND)*/ 00026970
       2 PIWA2_APX_LOW_HOUSENUM             CHAR(11), /* SORT FORMAT */    00027070
       2 PIWA2_APX_BBL,                                                    00027170
         3 PIWA2_APX_BBL_BORO               CHAR(1),                       00027270
         3 PIWA2_APX_BLOCK                  CHAR(5),                       00027370
         3 PIWA2_APX_LOT                    CHAR(4),                       00027470
       2 FILLER_APX01                       CHAR(7),                       00027771
       2 PIWA2_APX_NUM_OF_STRUCTURES        CHAR(4),                       00028171
       2 FILLER_APX02                       CHAR(26),                      00028271
       2 FILLER_GSS1                        CHAR(1),  /* FOR GSS USE*/     00029571
       2 PIWA2_APX_BIN                      CHAR(7),                       00029670
       2 PIWA2_APX_CONDO_FLAG               CHAR(1),                       00029770
       2 FILLER_APX03                       CHAR(1),                       00029871
       2 PIWA2_APX_RPAD_CONDO_ID_NUM        CHAR(4),                       00029970
       2 FILLER_APX04                       CHAR(7),                       00030071
       2 PIWA2_APX_CONDO_BILL_BBL           CHAR(10),                      00030270
       2 FILLER_APX05                       CHAR(2),                       00030371
       2 PIWA2_APX_CONDO_LOW_BBL            CHAR(10),                      00030670
       2 FILLER_APX06                       CHAR(1),                       00030771
       2 PIWA2_APX_CONDO_HIGH_BBL           CHAR(10),                      00030970
       2 FILLER_APX07                       CHAR(16),                      00031071
       2 PIWA2_APX_COOP_NUM                 CHAR(4),                       00031370
       2 FILLER_APX08                       CHAR(22),                      00031475
       2 PIWA2_APX_RESERVED                 CHAR(03),                      00032370
       2 PIWA2_APX_LATITUDE                 CHAR(09),                      00032470
       2 PIWA2_APX_LONGITUDE                CHAR(11),                      00032570
       2 PIWA2_APX_X_COORD                  CHAR(07),                      00032670
       2 PIWA2_APX_Y_COORD                  CHAR(07),                      00032770
       2 FILLER_APX09                       CHAR(16),                      00032873
       2 PIWA2_APX_AP_ID                    CHAR(09),                      00033473
       2 FILLER_GSS2                        CHAR(8),  /* LGC - GSS USE*/   00033571
       2 PIWA2_APX_REASON_CODE              CHAR(01),                      00033670
       2 PIWA2_APX_REASON_CODE_QUAL         CHAR(01),                      00033770
       2 PIWA2_APX_WARN_CODE                CHAR(02),                      00033870
       2 PIWA2_APX_RETURN_CODE              CHAR(02),                      00033970
       2 FILLER_APX10                       CHAR(108),                     00034072
       2 PIWA2_APX_NUM_OF_ADDR              CHAR(4),                       00034170
       2 PIWA2_APX_ADDR_LIST(21),                                          00034270
         3 PIWA2_APX_LIST_LOW_HOUSENUM      CHAR(16), /*DISPLAY FORMAT*/   00034370
         3 PIWA2_APX_LIST_HI_HOUSENUM       CHAR(16), /*DISPLAY FORMAT*/   00034470
         3 PIWA2_APX_LIST_BORO              CHAR(1),                       00034570
         3 PIWA2_APX_LIST_5SC               CHAR(5),                       00034670
         3 PIWA2_APX_LIST_LGC               CHAR(2),                       00034770
         3 PIWA2_APX_LIST_BIN               CHAR(7),                       00034870
         3 PIWA2_APX_LIST_SIDE_OF_STR       CHAR(1),  /* L, R */           00034970
         3 PIWA2_APX_ADDR_TYPE              CHAR(1),  /*               */  00035070
                                                      /* BLANK = NORMAL*/  00035165
         3 FILLER_APX11                     CHAR(1),                       00035274
         3 PIWA2_APX_ST_NAME                CHAR(32),                      00035470
         3 FILLER_APX12                     CHAR(34);                      00035572
                                                                           00036065
                                                                           00037071
    DCL 1 PIWA2_FNAP BASED(ADDR(PIWA2_FNAPX)),                             00037171
     /*******************************************************************/ 00039071
     /***              WORK AREA 2 FOR FUNCTION AP                    ***/ 00040071
     /***                                                             ***/ 00050071
     /*******************************************************************/ 00060071
                                                                           00070071
                                                                           00080071
       2 PIWA2_AP_ACCESS_KEY                CHAR(21),                      00090071
       2 PIWA2_AP_CONT_PARITY               CHAR(1), /*(OR DUP ADDR IND)*/ 00100071
       2 PIWA2_AP_LOW_HOUSENUM              CHAR(11), /* SORT FORMAT */    00110071
       2 PIWA2_AP_BBL,                                                     00120071
         3 PIWA2_AP_BBL_BORO                CHAR(1),                       00130071
         3 PIWA2_AP_BLOCK                   CHAR(5),                       00140071
         3 PIWA2_AP_LOT                     CHAR(4),                       00150071
       2 FILLER_AP01                        CHAR(7),                       00160071
       2 PIWA2_AP_NUM_OF_STRUCTURES         CHAR(4),                       00170071
       2 FILLER_AP02                        CHAR(26),                      00180071
       2 FILLER_GSS1                        CHAR(1),  /* FOR GSS USE*/     00190071
       2 PIWA2_AP_BIN                       CHAR(7),                       00200071
       2 PIWA2_AP_CONDO_FLAG                CHAR(1),                       00210071
       2 FILLER_AP03                        CHAR(1),                       00220071
       2 PIWA2_AP_RPAD_CONDO_ID_NUM         CHAR(4),                       00230071
       2 FILLER_AP04                        CHAR(7),                       00240071
       2 PIWA2_AP_CONDO_BILL_BBL            CHAR(10),                      00250071
       2 FILLER_AP05                        CHAR(2),                       00260071
       2 PIWA2_AP_CONDO_LOW_BBL             CHAR(10),                      00270071
       2 FILLER_AP06                        CHAR(1),                       00280071
       2 PIWA2_AP_CONDO_HIGH_BBL            CHAR(10),                      00290071
       2 FILLER_AP07                        CHAR(16),                      00300071
       2 PIWA2_AP_COOP_NUM                  CHAR(4),                       00310071
       2 FILLER_AP08                        CHAR(18),                      00320072
       2 PIWA2_AP_DOF_MAP_PAGE              CHAR(4),                       00330071
       2 PIWA2_AP_RESERVED                  CHAR(03),                      00340071
       2 PIWA2_AP_LATITUDE                  CHAR(09),                      00350071
       2 PIWA2_AP_LONGITUDE                 CHAR(11),                      00360071
       2 PIWA2_AP_X_COORD                   CHAR(07),                      00370071
       2 PIWA2_AP_Y_COORD                   CHAR(07),                      00380071
       2 FILLER_AP09                        CHAR(16),                      00390073
       2 PIWA2_AP_AP_ID                     CHAR(09),                      00400073
       2 FILLER_GSS2                        CHAR(8),  /* LGC - GSS USE*/   00410071
       2 PIWA2_AP_NUM_OF_ADDR               CHAR(4),                       00470071
       2 PIWA2_AP_ADDR_LIST(21),                                           00480071
         3 PIWA2_AP_LIST_LOW_HOUSENUM       CHAR(16), /*DISPLAY FORMAT*/   00490071
         3 PIWA2_AP_LIST_HI_HOUSENUM        CHAR(16), /*DISPLAY FORMAT*/   00500071
         3 PIWA2_AP_LIST_BORO               CHAR(1),                       00510071
         3 PIWA2_AP_LIST_5SC                CHAR(5),                       00520071
         3 PIWA2_AP_LIST_LGC                CHAR(2),                       00530071
         3 PIWA2_AP_LIST_BIN                CHAR(7),                       00540071
         3 PIWA2_AP_LIST_SIDE_OF_STR        CHAR(1),  /* L, R */           00550071
         3 PIWA2_AP_ADDR_TYPE               CHAR(1),  /*               */  00560071
                                                      /* BLANK = NORMAL*/  00570071
         3 FILLER_AP10                      CHAR(4);                       00600071
                                                                           00610071


## <span id="appendix14.20"><center>C COPY File (COW)</center></span>  

## <span id="appendix14.21"><center>PAC COPY File</center></span>

    #ifndef GEOSUPPORT
    #define GEOSUPPORT
    #ifdef __cplusplus
    extern "C" {
    #endif
     /*********************************************************************/
     /*                                                                   */
     /*  Add new 2 bytes Bike Traffic Direction          TLV 12/2016 V17.1*/
     /*  Replaced sanit_reserved with sanit_bulk_pick_up TLV  9/2016 V16.4*/
     /*  Added 'unit' fields to WA1                      TLV  9/2016 V16.4*/
     /*  Add new 2 bytes Bike Lane and Max Str Width     TLV  9/2016 V16.4*/
     /*                                                                   */
     /*********************************************************************/
     /*                                                                   */
     /*            GeoSupport System C-Language Header File               */
     /*               for Platform-Independent Work Areas                 */
     /*                                                                   */
     /*                 Last Updated: February 2016                       */
     /*                                                                   */
     /*********************************************************************/

     /*********************************************************************/
     /*                                                                   */
     /*      Group Items Used in Platform-Independent Work Area 1         */
     /*                                                                   */
     /*********************************************************************/
    #define UNIT_SIZE     14               //unit type+identifier v16.4
    #define UNITT_SIZE     4               //unit type            v16.4
    #define UNITI_SIZE    10               //unit identfier       v16.4

    typedef struct { char boro;              // Borough Code
                     char SC10[10];          // 10 Digit Street Code
                     char Street_name[32];   // Street Name
                   } STREET;

    typedef union { char bbl[10];            /* Borough-Block-Lot        */
                    struct { char boro;      /* Borough                  */
                             char block[5];  /* Tax Block                */
                             char lot[4];    /* Tax Lot                  */
                           } cas;
                  } BBL;

    typedef struct {
      char unitt[UNITT_SIZE];                /* Output unit type  V16.4 */
      char uniti[UNITI_SIZE];                /* Output unit identifier  */
    } UNIT, *PUNIT;                          /* Output unit       V16.4 */


    typedef struct {
                     char func_code[2];      /* Function Code            */
                     char hse_nbr_disp[16];  /* House nbr in Disp form   */
                     char hse_nbr_hns[11];   /* House nbr in Sort form   */
                     char lohse_nbr_disp[16];/* Lo House nbr in Disp form*/
                     char lohse_nbr_hns[11]; /* Lo House nbr in Sort form*/
                     STREET sti[3];          /* Street Information       */
                     BBL bbli;               /* Borough-Block-Lot        */
                     char filler01;          /* Filler-Tax Lot Version # */
                     char bld_id[7];         /* Building Id Number (BIN) */
                     char comp_direction;    /* Compass Direction        */
                     char comp_direction2;   /* Compass Direction-Fn 3S  */
                     char node[7];           /* Node input for Fn2       */
                     char platform_ind;      /* Must be equal to 'C'     */
                     char zipin[5];          /* Input Zip Code           */
                     char unit[UNIT_SIZE];   /* Input unit          V16.4*/
                     char filler03[82];      /* Future Use               */

                            /* Flags that influence processing */

                     char long_WA_flag;      /* Long Work Area 2 Flag     */
                                             /* Next 2 fields not impl    */
                     char hse_nbr_justify;   /* Hse Nbr Justification Flg */
                     char hnl[2];            /* Hse Nbr Normalization len */
                     char hse_nbr_over_flag; /* Reserved for GSS Use      */
                     char snl[2];            /* Street Name Norm Length   */
                     char st_name_norm;      /* Street Name Normalization */
                                             /*   Format Flag             */
                     char expanded_format;   /* Expanded Format Flag      */
                     char roadbedrequest;    /* Roadbed Request Switch    */
                     char res_01;            /* Reserved for Internal Use */
                     char segaux_switch;     /* Request Auxiliary Segment */
                                             /* Information               */
                     char browse_flag;       /* Determines if browse      */
                                             /* displays all or some names*/
                     char real_street_only;  /* Display real streets only */
                     char tpad_switch;       /* TPAD read for PAD process */
                     char mode_switch;       /* Mode Flag                 */
                                             /* X = Extended WA2          */
                     char wto_switch;        /* WTOs Switch N = No WTOs  */
                                             /*   should be issued       */
                     char filler04[29];      /* Future Use                */
                    } INWA1;

    typedef struct {
                     char boro_name[9];      /* Boro Name of First Street*/
                     char hse_nbr_disp[16];  /* House nbr in Normalized  */
                                             /* Display form             */
                     char hse_nbr_hns[11];   /* House number in Sort Form*/
                     STREET sto[3];          /* Street Information       */
                     BBL bblo;               /* Boro(len=1), Block(len=5)*/
                                             /* and Lot (len=4)-Normalizd*/
                     char filler05;          /* Filler-Tax Lot Version # */
                     char lo_hse_nbr_disp[16]; /* low Hse nbr - display  */
                     char lo_hse_nbr_hns[11]; /* low Hse nbr - sort form */
                     char bin[7];            /* Building Id Number       */
                     char attrbytes[3];      /* NAP Identification Number*/
                     char reason_code_2;     /* 2nd Reason Code          */
                     char reason_code_qual_2;/* 2nd Reason Code Qualifier*/
                 //  char filler08_2;        /* Future Use               */
                     char warn_code_2[2];    /* 2nd Warning Return Code  */
                     char ret_code_2[2];     /* 2nd GeoSupport Return Cod*/
                     char msg_2[80];         /* 2nd GeoSupport Message   */
                     char node[7];           /* Node output for Fn 2     */
                     UNIT units;             /* Output unit Sort    V16.4*/
                     char unitd[UNIT_SIZE];  /* Output unit Display V16.4*/
                     char filler07[11];      /* Future Use               */
                     char nap_id_nbr[6];     /* NAP Id Nbr - Not Impl.   */
                     char int_use1;          /* Internal Use Only        */
                     char reason_code;       /* Reason Code              */
                     char reason_code_qual;  /* Reason Code Qualifier    */
                 //  char filler08;          /* Future Use               */
                     char warn_code[2];      /* Warning Ret. Code-NotImpl*/
                     char ret_code[2];       /* GeoSupport Return Code   */
                     char msg[80];           /* GeoSupport Message       */
                     char nbr_names[2];      /* Nbr of Sreet Names       */
                     char B_7SC[10][8];      /* 10 Boro+7-digit st codes */
                     char st_names[10][32];  /* Up to 10 Street Names    */
                   } OUTWA1;

     /*********************************************************************/
     /*                                                                   */
     /*                 Platform-Independent Work Area 1                  */
     /*                                                                   */
     /*********************************************************************/

    typedef struct { INWA1 input;
                     OUTWA1 output;
                   } C_WA1;

     /******************************************************************/
     /*                                                                */
     /*     Group Items Used in Platform-Independent Work Area 2's     */
     /*                                                                */
     /******************************************************************/

    typedef struct {                         /* LION KEY                 */
                     char lion_boro;         /* LION Borough Code        */
                                             /* Differs from GeoSupport  */
                                             /* Borough Codes            */
                     char face[4];           /* Face Code                */
                     char seq[5];            /* Sequence Number          */
                   } LION;

    typedef struct {
                     char nbr_sts;           /* Number of streets */
                     char B5SC[5][6];        /* Boro+5 Street Code*/
                   } St_list;

    typedef struct {                    /* used for longwa for TPAD */
      char bin[7];                             /* BIN               */
      char status;                             /* Status of BIN     */
    } TPAD_LIST;

    typedef struct {
      TPAD_LIST   tpadlist[2187];            /* or BINs + Status Byte  */
      char        fill[4];
    } TPADLST;

    typedef struct { char lo_hse_nbr[16];    /* Low House Nbr-Disply form*/
                     char hi_hse_nbr[16];    /* Hi House Nbr-Display form*/
                     char B5SC[6];           /* Boro & 5 digit Str Code  */
                     char lgc[2];            /* DCP Preferred Street LGC */
                     char bld_id[7];         /* BIN of address range     */
                     char sos_ind;           /* Side of Street Indicator */
                     char adr_type;          /* Address type - P=NAP,    */
                                             /*    B=NAB, Blank=Normal   */
                     char TPAD_bin_status;   /* Status of Job            */
                     char filler01[3];       /* Future Use               */
                   } ADDR_RANGE;

    typedef struct {
      char lo_hse_nbr[16];                   /* Low House Nbr-Disply form*/
      char hi_hse_nbr[16];                   /* Hi House Nbr-Display form*/
      char B5SC[6];                          /* Boro & 5 digit Str Code  */
      char lgc[2];                           /* DCP Preferred Street LGC */
      char bld_id[7];                        /* BIN of address range     */
      char sos_ind;                          /* Side of Street Indicator */
      char adr_type;                         /* Address type             */
                                             /* (Blank = Normal)         */
      char TPAD_bin_status;                  /* Status of BIN from TPAD  */
      char st_name[32];                      /* Street Name              */
      char filler01[34];                     /* Future Use               */
    } ADDR_RANGE_1AX;

    typedef struct { char lo_hse_nbr[16];    /* Low House Nbr-Disply form*/
                     char hi_hse_nbr[16];    /* Hi House Nbr-Display form*/
                     char B5SC[6];           /* Boro & 5 digit Str Code  */
                     char lgc[2];            /* DCP Preferred Street LGC */
                     char bld_id[7];         /* BIN of address range     */
                     char sos_ind;           /* Side of Street Indicator */
                     char adr_type;          /* Address type - V=VANITY  */
                                             /*   Blank=Normal           */
                     char filler02;          /* filler for func AP       */
                     char filler01[3];       /* Future Use               */
                   } ADDR_RANGE_AP;

    typedef struct { char lo_hse_nbr[16];    /* Low House Nbr-Disply form*/
                     char hi_hse_nbr[16];    /* Hi House Nbr-Display form*/
                     char B5SC[6];           /* Boro & 5 digit Str Code  */
                     char lgc[2];            /* DCP Preferred Street LGC */
                     char bld_id[7];         /* BIN of address range     */
                     char sos_ind;           /* Side of Street Indicator */
                     char adr_type;          /* Address type - V=VANITY  */
                                             /*    Blank=Normal          */
                     char filler02;          /* filler for func APX      */
                     char st_name[32];       /* Street Name              */
                     char filler01[34];      /* Future Use               */
                   } ADDR_RANGE_APX;

    typedef struct { char sanborn_boro;      /* Sanborn Borough Code     */
                     char sanborn_vol[3];    /* Sanborn Volume           */
                     char sanborn_page[4];   /* Sanborn Page             */
                   } SANBORN;

    typedef struct { char com_dist[3];       /* Community District       */
                     char lo_hse_nbr[16];    /* Low House Nbr-Disply form*/
                     char hi_hse_nbr[16];    /* Hi House Nbr-Display form*/
                     char filler01[32];      /* Future Use               */
                     char iaei;              /* Interim Ass'tance Elig   */
                                             /* Indicator                */
                     char zip_code[5];       /* Zip code for Street seg. */
                     char health_area[4];    /* Health Area        */
                     char police_boro_com;   /* Police Patrl Boro Command*/
                     char police_pre[3];     /* Police Precinct          */
                     char fire_divisn[2];    /* Fire Division            */
                     char fire_bat[2];       /* Fire Battalion           */
                     char fire_co_type;      /* Fire Company Type        */
                     char fire_co_nbr[3];    /* Fire Company Number      */
                     char com_schl_dist[2];  /* Community School District*/
                     char dynam_blk[3];      /* Atomic Polygon           */
                                             /* (was Dynamic Block)      */
                     char ED[3];             /* ED                       */
                     char AD[2];             /* AD                       */
                     char police_pat_boro[2];/* Police Patrol Borough    */
               //    char instruc_div[2];    /* Instructional Division   */
                     char filler02;          /* Future Use               */
                     char boro;              /* Used for the NTA name    */
                     char cen_tract_90[6];   /* 1990 Census Tract        */
                     char cen_tract_10[6];   /* 2010 Census Tract        */
                     char cen_blk_10[4];     /* 2010 Census Block        */
                     char cen_blk_10_sufx;   /* 2010 Census Block Suffix */
                                             /* 2010 Suffix Not Implement*/
                     char cen_tract_2000[6]; /* 2000 Census Tract        */
                     char cen_blk_2000[4];   /* 2000 Census Block        */
                     char cen_blk_2000_sufx; /* 2000 Census Block Suffix */
                //   char blockface_id[7];   /* "Blockface ID" became    */
                     char filler03[7];       /* filler   V16.1           */
                     char nta[4];            /* Neighborhood Tabulation  */
                                             /* Area                     */
                     char filler04[8];       /* Future Use               */
                   } SEGSIDE;

    typedef struct { char mh_ri_flag;        /* Marble Hill/Rikers Island*/
                                             /* Alternative Boro flag    */
                     char len[5];            /* Len in ft from prev node */
                     char gap_flag;          /* Gap Flag                 */
                     char node_nbr[7];       /* Node Number of Intersect */
                     char nbr_streets;       /* Nbr streets intersecting */
                     char B7SC[5][8];        /* Lowest B7SC at Intersect */
                                             /* is first and 2nd Lowest  */
                                             /* B7SC is next. Remaining  */
                                             /* B7SC's in no particular  */
                                             /* order.                   */
                   } CROSS_STRS;

     /********************************************************************/
     /*                                                                  */
     /*        Platform-Independent Work Area 2 for Function 1           */
     /*                                                                  */
     /********************************************************************/

    typedef struct { char filler01[21];
                     char cont_parity_ind;   /* Continuous Parity Ind.   */
                                             /* or Duplicate Address Ind.*/
                     char lo_hse_nbr[11];    /* Lo House nbr in Sort form*/
                     char hi_hse_nbr[11];    /* Hi House Nbr in Sort form*/
                     char lgc[2];            /* DCP or BOE Preferred LGC */
                     St_list st[2];          /* 1=Low and 2=High         */
                                             /* Nbr of cross streets at  */
                                             /* low house nbr end of st  */
                                             /* B5SCs of lo end cross st */
                     LION key;               /* LION Key - 10 Characters */
                     char sagr_flag;         /* Special Address Generated*/
                                             /* Record flag              */
                     char sos_ind;           /* Side of Street Indicator */
                     char seg_len[5];        /* Segment Length in Feet   */
                     char coord[3][7];       /* 1 = X coordinate,        */
                                             /* 2 = Y coordinate,        */
                                             /* 3 = Z coordinate, Not Imp*/
                     char iaei;              /* Interim Ass'tance Elig   */
                                             /* Indicator                */
                     char mh_ri_flag;        /* Marble Hill/Rikers Island*/
                                             /* Alternative Borough flag */
                     char DOT_slca;          /* DOT St Lght Contractr Are*/
                     char com_dist[3];       /* Community District       */
                                             /* Position 0 contains the  */
                                             /* CD Boro Code & Pos 1 & 2,*/
                                             /* the district number      */
                     char zip_code[5];       /* Zip code for st seg      */

               /* Following seven fields used for Function 1E only*/

                     char ed[3];             /* Election District        */
                     char ad[2];             /* Assembly District        */
                     char sped_flag;         /* Split Elect District Flag*/
                     char congress_dist[2];  /* Congressional District   */
                     char state_sen_dist[2]; /* State Senatorial District*/
                     char civil_court[2];    /* Civil Court District     */
                     char city_council[2];   /* City Council District    */
                     char health_cent[2];    /* Health Center Dictr*/
                     char health_area[4];    /* Health Area        */
                     char sanit_dist[3];     /* Sanitation District      */
                     char sanit_sub_sect[2]; /* Sanit Collect Scheduling */
                                             /* Section and Subsection   */
                     char sanit_reg_pick_up[5]; /* Regular Pick up       */
                     char sanit_recycle[3];  /* Recycle pick up          */
                     char police_boro_com;   /* Police Patrol Boro Commnd*/
                     char police_pre[3];     /* Police Precinct          */
                     char fire_divisn[2];    /* Fire Division            */
                     char fire_bat[2];       /* Fire Battalion           */
                     char fire_co_type;      /* Fire Company Type        */
                     char fire_co_nbr[3];    /* Fire Company Number      */
                     char filler_scsd;       /* Was Split Com School     */
                                             /* District Flag            */
                     char com_schl_dist[2];  /* Community School District*/
                     char dynam_blk[3];      /* Atomic Polygon           */
                                             /* (was Dynamic Block)      */
                     char police_pat_boro[2];/* Police Patrol Borough    */
             //      char filler_indv[2];    /*                          */
             //      char instruc_div[2];    /* Instructional Division   */
                     char feature_type;      /* Feature Type Code        */
                     char segmenttypecode;   /* Segment Type Code        */
                     char alx;               /* Segment split by Alley(s)*/
                                             /* A=Split by Alley(s)      */
                                             /* X=Cross Streets Modified */
                     char coincident_seg_cnt; /* Coincident Segment      */
                                             /*    Counter               */
                     char filler02[2];       /* Future Use               */
                     char boro_of_cen_tract; /* boro of Census Tract used*/
                     char cen_tract_90[6];   /* 1990 Census Tract        */
                     char cen_tract_10[6];   /* 2010 Census Tract        */
                     char cen_blk_10[4];     /* 2010 Census Block        */
                     char cen_blk_10_sufx;   /* 2010 Census Block Suffix */
                                             /* 2010 Suffix Not Implement*/
                     char cen_tract_2000[6]; /* 2000 Census Tract        */
                     char cen_blk_2000[4];   /* 2000 Census Block        */
                     char cen_blk_2000_sufx; /* 2000 Census Block Suffix */
                     char nta[4];            /* Neighborhood Tabulation  */
                                             /* Area                     */
                     char sanit_snow_priority;/* Sanitation Street Snow  */
                                             /* Priority (P,S,T,V)       */
                     char sanit_org_pick_up[5];/* Organics Pick up       */
                     char sanit_bulk_pick_up[5]; /* Bulk Pick Up V16.4   */
                   //char sanit_reserved[5]; /* Reserved for Possible    */
                     char hurricane_zone[2]; /* Hurricane Evacuation Zone*/
                     char filler04[11];      /* Future Use               */
                     char true_hns[11];      /* Underlying HNS           */
                     char true_b7sc[8];      /* True Boro 7 Street Code  */
                     char seg_id[7];         /* Segment Identifier       */
                     char curv_flag;         /* Curve Flag               */
                   } C_WA2_F1;

     /********************************************************************/
     /*                                                                  */
     /*      Platform-Independent Work Area 2 for Function 1V/1W         */
     /*                                                                  */
     /********************************************************************/

    typedef struct {
      C_WA2_F1 c_wa2_f1;
      char int_use[8];                       /* valid on street lgcs     */
      char boe_lgc;                          /* BOE LGC Pointer          */
      char seg_azm[3];                       /* Segment Azimuth          */
      char seg_orient;                       /* Segment Orientation      */
      char seg_coord[2][3][7];               /* Spatial Coordinates of   */
                                             /* Segment                  */
      char cc_coord[3][7];                   /* Spatial Coordinates of   */
                                             /* Center of Curvature      */
      char radius[7];                        /* Radius of Circle         */
      char cc_sos;                           /* Center of Curvature Side */
                                             /* of Street Flag           */
      char node_angles[2][5];                /* Angle to FROM & TO Nodes */
      char nodes[2][7];                      /* LION Node Numbers of     */
                                             /* FROM and TO nodes        */
      LION LION_key;                         /* LION Key for Vanity      */
                                             /* Addresses                */
      char LION_sos_ind;                     /* LION SoS Indicator       */
      char split_low_hn[11];                 /* Split Low House Number   */
      char traffic_dir;                      /* Traffic Direction        */
      char turn_restricts[10];               /* Turn restrictions        */
      char curve_fraction[3];                /*                          */
      char roadway_type[2];                  /* Roadway Type             */
      char physical_id[7];                   /*                          */
      char generic_id[7];                    /*                          */
      char filler03[7];                      /* DCP internal use         */
      char filler04[7];                      /* DCP internal use         */
    //char blockface_id[7];      /** V16.1 **  blockface id 10 bytes long*/
      char bike_lane_2[2];                   /*Bike Lane has 2 bytes     */
                                             /* numeric value moved in   */
                                             /* wa2 of F1EX              */
      char bike_traffic_dir[2];              //V17.1 Bike Traffic Direction
      char filler05[3];                      // V17.1
      char status;                           /*                          */
      char str_width[3];                     /*                          */
      char str_width_irregular;              /* Yes or No                */
      char bike_lane;                        /*                          */
      char fcc[2];                           /* Federal Classification Cd*/
      char row_type;                         /*                          */
      char lgcs_additional[5][2];            /* additional lgcs for on st*/
    } C_WA2_F1V;

     /********************************************************************/
     /*                                                                  */
     /*   Platform-Independent Work Area 2 for Function 1E Extended      */
     /*                                                                  */
     /********************************************************************/
    typedef struct {                         /* Fn 1E with extra bytes   */
      C_WA2_F1V cwa2f1v;
      char legacy_segid[7];                  /*                          */
      char from_preferred_lgcs[5][2];        /*                          */
      char to_preferred_lgcs[5][2];          /*                          */
      char from_additional_lgcs[5][2];       /*                          */
      char to_additional_lgcs[5][2];         /*                          */
      char no_x_st_calc_flg;                 /* No Cross Street          */
                                             /* Calculation Flag         */
      char indiv_seg_len[5];                 /* Individual Segment Length*/
                                             /* Used with Above Flag     */
      char nta_name[75];                     /* Neighborhood Tabulation  */
                                             /* Area Name                */
      char USPS_city_name[25];               /* USPS Preferred City Name */
      char latitude[9];                      /* Latitude calc from X-Y   */
      char longitude[11];                    /* Longitude calc from X-Y  */
      char seg_from_node[7];                 /* Segment from node        */
      char seg_to_node[7];                   /* Segment to node          */
      char seg_from_xyz[3][7];               /* XYZ coord (segment from) */
      char seg_to_xyz[3][7];                 /* XYZ coord (segment to)   */
      char blockface_id[10];                 /* NEW location V16.1       */
                                             /* because of length changed*/
      char nbr_travel_lanes[2];              /* nbr of traveling lanes   */
      char nbr_park_lanes[2];                /* nbr of parking lanes     */
      char nbr_total_lanes[2];               /* total nbr of lanes       */
      char str_width_max[3];                 /*street width maximum      */
      char filler6[252];                     /* Future Use               */
      char reason_code;                      /* Reason Code              */
      char reason_code_qual;                 /* Reason Code Qualifier    */
      char warn_code[2];                     /* Warning Return Code      */
      char ret_code[2];                      /* GeoSupport Return Code   */
      char nbr_names_lo;                     /* Nbr of St Names Low End  */
      char B7SC_lo[5][8];                    /* 5(Boro+7-digit) st codes */
      char nbr_names_hi;                     /* Nbr of St Names High End */
      char B7SC_hi[5][8];                    /* 5 Boro+7-digit st codes  */
      char st_names_lo[5][32];               /* Up to 5 St Names Low End */
      char st_names_hi[5][32];               /* Up to 5 St Names High End*/
      char BOE_B5SC[6];                      /* BOE Preffered B7SC       */
      char BOE_lgc[2];                       /* BOE Preffered B7SC       */
      char BOE_st_name[32];                  /* BOE Preffered Street Name*/
      char filler7[52];                      /* Future Use               */
    } C_WA2_F1EX;                            /* Fn 1EX with filler       */

     /********************************************************************/
     /*                                                                  */
     /*   Platform-Independent Work Area 2 for Function 1A Extended      */
     /*                                                                  */
     /********************************************************************/
    typedef struct {                         /* Fn 1A with extra bytes   */
      char filler01[21];
      char cont_parity_ind;                  /* Continuous Parity Ind    */
                                             /* or Duplicate Address Ind */
      char lo_hse_nbr[11];                   /* Low House Number-Sort Frm*/

      BBL  bbl;                              /* Borough-Block-Lot        */
      char filler02;                         /* Reserved for Tax Lot Ver#*/
      char RPAD_scc;                         /* RPAD Self_Check Code(SCC)*/
      char filler03;
      char RPAD_lucc[2];                     /* RPAD Land Use Class. Code*/
      char corner[2];                        /* Corner Code              */
      char nbr_blds[4];                      /* Nbr of buildings on lot  */
      char nbr_str[2];                       /* Nbr Street Frontages     */
      char inter_flag;                       /* Interior Lot Flag        */
      char vacant_flag;                      /* Vacant Lot Flag          */
      char irreg_flag;                       /* Irregularly-Shaped Lot Fl*/
      char mh_ri_flag;                       /* Marble Hill/Rikers Island*/
      char adr_range_overflow;               /* Addr Rnge Lst Ovrflow Flg*/
      char stroll_key[18];                   /* Strolling key Not Implem */
      char filler04;
      char res_internal_use;                 /* Reserved for Internal Use*/
      char bld_id[7];                        /* Building Ident. Number   */
                                             /* (BIN) of Input Address of*/
                                             /* Existing Building, If any*/
      char condo_flag;                       /* Condominium Flag         */
      char filler05;                         /* Future Use               */
      char condo_id[4];                      /* RPAD Condo Id Number     */
      char condo_unit_id[7];                 /* Condo Unit Id Nbr-Not Imp*/
      BBL  condo_bill_bbl;                   /* Condo Billing BBL        */
      char filler06;                         /* Reserved for Tax Lot Ver */
      char condo_scc;                        /* Self-Check Code          */
      BBL  condo_lo_bbl;                     /* Low BBL of Condo         */
      char filler07;                         /* Reserved for Tax Lot Ver */
      BBL  condo_hi_bbl;                     /* High BBL of Condo        */
      char filler08;                         /* Reserved for Tax Lot Ver */
      char filler09[15];
      char co_op_nbr[4];                     /* Co-op Number             */
      SANBORN San;                           /* Sanborn Information      */
      char business_area[5];                 /* Business Area            */
      char tax_map_nbr[5];                   /* Tax Map Nbr-Sect and Vol */
      char filler10[4];                      /* Tax Map Nbr Page Not Impl*/
      char filler11[3];
      char latitude[9];                      /* Latitude calc from X-Y   */
      char longitude[11];                    /* Longitude calc from X-Y  */
      char coord[2][7];                      /* 1 = X coordinate-Annotat */
                                             /* 2 = Y coordinate-Annotat */
      char bid_id[6];                        /* Business Improvement     */
                                             /* District ID (BID)        */

      char TPAD_bin_status;                  /* Status of Demolition job */
                                             /* on Existing BIN of Input */
                                             /* Address                  */
      char TPAD_new_bin[7];                  /* BIN for New Building     */
      char TPAD_new_bin_status;              /* Status of New Buildng BIN*/
      char TPAD_conflict_flag;               /* From TPAD                */
      char filler12[9];

      char int_use[8];                       /* Internal Use             */
      char reason_code;                      /* Reason Code              */
      char reason_code_qual;                 /* Reason Code Qualifier    */
      char warn_code[2];                     /* Warning Return Code      */
      char ret_code[2];                      /* GeoSupport Return Code   */
      char filler14[108];
      char nbr_addr[4];                      /* Nbr of Addr Ranges or Nbr*/
                                             /* of BINs in List          */
      ADDR_RANGE_1AX addr_range_1ax[21];
    } C_WA2_F1AX;                            /* Fn 1AX with filler       */
     /********************************************************************/
     /*                                                                  */
     /*      Platform-Independent Work Area 2 for Function 1B            */
     /*                                                                  */
     /********************************************************************/

    typedef struct {                         /* Function 1B              */
      C_WA2_F1EX cwa2f1ex;                   /* 1EX Component            */
      C_WA2_F1AX cwa2f1ax;                   /* 1AX Component            */
    } C_WA2_F1B;                             /* Fn 1B                    */

     /********************************************************************/
     /*                                                                  */
     /*      Platform-Independent Work Area 2 for Function 1A            */
     /*                                                                  */
     /********************************************************************/

    typedef struct {
       char filler01[21];
       char cont_parity_ind;   /* Continuous Parity Ind    */
                               /* or Duplicate Address Ind */
       char lo_hse_nbr[11];    /* Low House Number-Sort Frm*/

       BBL bbl;                /* Borough-Block-Lot        */
       char filler02;          /* Reserved for Tax Lot Ver#*/
       char RPAD_scc;          /* RPAD Self_Check Code(SCC)*/
       char filler03;
       char RPAD_lucc[2];      /* RPAD Land Use Class. Code*/
       char corner[2];         /* Corner Code              */
       char nbr_blds[4];       /* Nbr of buildings on lot  */
       char nbr_str[2];        /* Nbr Street Frontages     */
       char inter_flag;        /* Interior Lot Flag        */
       char vacant_flag;       /* Vacant Lot Flag          */
       char irreg_flag;        /* Irregularly-Shaped Lot Fl*/
       char mh_ri_flag;        /* Marble Hill/Rikers Island*/
       char adr_range_overflow;/* Addr Rnge Lst Ovrflow Flg*/
       char stroll_key[18];    /* Strolling key            */
       char filler04;
       char res_internal_use;  /* Reserved for Internal Use*/
       char bld_id[7];         /* Building Ident. Number   */
                               /* (BIN) of Input Address of*/
                               /* Existing Building, If any*/
       char condo_flag;        /* Condominium Flag         */
       char filler05;          /* Future Use               */
       char condo_id[4];       /* RPAD Condo Id Number     */
       char condo_unit_id[7];  /* Condo Unit Id Nbr-Not Impl*/
       BBL  condo_bill_bbl;    /* Condo Billing BBL        */
       char filler06;          /* Reserved for Tax Lot Ver */
       char condo_scc;         /* Self-Check Code          */
       BBL  condo_lo_bbl;      /* Low BBL of Condo         */
       char filler07;          /* Reserved for Tax Lot Ver */
       BBL  condo_hi_bbl;      /* High BBL of Condo        */
       char filler08;          /* Reserved for Tax Lot Ver */
       char filler09[15];
       char co_op_nbr[4];      /* Co-op Number             */
       SANBORN San;            /* Sanborn Information      */
       char business_area[5];  /* Business Area            */
       char tax_map_nbr[5];    /* Tax Map Nbr-Sect and Vol */
       char filler10[4];       /* Tax Map Nbr Page Not Impl*/
       char filler11[3];
       char latitude[9];       /* Latitude calc from X-Y   */
       char longitude[11];     /* Longitude calc from X-Y  */
       char coord[2][7];       /* 1 = X coordinate-Annotat */
                               /* 2 = Y coordinate-Annotat  */
       char bid_id[6];         /* Business Improvement Dist */
                               /* District ID (BID)         */
       char TPAD_bin_status;   /* Existing BIN of Input Addr*/
       char TPAD_new_bin[7];    /* BIN for New Building job */
       char TPAD_new_bin_status;/* Status of New Buildng BIN*/
       char TPAD_conflict_flag; /* From TPAD                */
       char filler12[9];
       char int_use[8];        /* Internal Use             */
       char nbr_addr[4];       /* Nbr of Addr Ranges or Nbr*/
                               /* of BINs in List          */
       union {
               ADDR_RANGE addr_range[21]; /* List of Addr  */
               TPADLST   tpad_list;       /*or BINs + Status Byte */
               char bin_list[2500][7];    /* or BINs*/
             } bar;
    } C_WA2_F1A;
     /********************************************************************/
     /*                                                                  */
     /*      Platform-Independent Work Area 2 for Function AP            */
     /*                                                                  */
     /********************************************************************/

    typedef struct {
       char filler01[21];
       char cont_parity_ind;   /* Continuous Parity Ind    */
                               /* or Duplicate Address Ind */
       char lo_hse_nbr[11];    /* Low House Number-Sort Frm*/

       BBL bbl;                /* Borough-Block-Lot        */
       char filler02;          /* Reserved for Tax Lot Ver#*/
       char fil_RPAD_scc;      /* filler for func AP       */
       char filler03;
       char fil_RPAD_lucc[2];  /* fillers for func AP      */
       char fil_corner[2];     /* fillers for func AP      */
       char nbr_blds[4];       /* Nbr of buildings on lot  */
       char fil_nbr_str[2];    /* fillers for func AP      */
       char fil_inter_flag;    /* filler for func AP       */
       char fil_vacant_flag;   /* filler for func AP       */
       char fil_irreg_flag;    /* filler for func AP       */
       char fil_mh_ri_flag;    /* filler for func AP       */
       char fil_adr_range_overflow;/* filler for func AP   */
       char fil_stroll_key[18];/* fillers for func AP      */
       char filler04;
       char res_internal_use;  /* Reserved for Internal Use*/
       char bld_id[7];         /* Building Ident. Number   */
                               /* (BIN) of Input Address of*/
                               /* Existing Building,       */
       char condo_flag;        /* Condominium Flag         */
       char filler05;          /* Future Use               */
       char condo_id[4];       /* RPAD Condo Id Number     */
       char filler_unit_id[7]; /* Condo Unit Id Nbr-Not Impl*/
       BBL  condo_bill_bbl;    /* Condo Billing BBL        */
       char filler06;          /* Reserved for Tax Lot Ver */
       char fil_condo_scc;     /* filler for func AP       */
       BBL  condo_lo_bbl;      /* Low BBL of Condo         */
       char filler07;          /* Reserved for Tax Lot Ver */
       BBL  condo_hi_bbl;      /* High BBL of Condo        */
       char filler08;          /* Reserved for Tax Lot Ver */
       char filler09[15];
       char co_op_nbr[4];      /* Co-op Number             */
       char fil_sanborn[8];    /* fillers for func AP      */
       char fil_business_area[5];  /* fillers for func AP  */
       char fil_tax_map_nbr[5];    /* fillers for func AP  */
       char filler10[4];
       char filler11[3];
       char latitude[9];       /* Latitude calc from X-Y   */
       char longitude[11];     /* Longitude calc from X-Y  */
       char coord[2][7];       /* 1 = X coordinate from AP */
                               /* 2 = Y coordinate from AP */
       char fil_bid_id[6];          /* fillers for func AP */
       char fil_TPAD_bin_status;    /* fillers for func AP */
       char fil_TPAD_new_bin[7];    /* fillers for func AP */
       char fil_TPAD_new_bin_status;/* filler for func AP  */
       char fil_TPAD_conflict_flag; /* filler for func AP  */
       char ap_id[9];               /* Address Point Id    */
       char int_use[8];             /* Internal Use        */
       char nbr_addr[4];            /* Nbr of Addr = 0001  */

       union {
               ADDR_RANGE_AP addr_range_ap[21]; /* List of Addr  */
               char fil_tpad_list[2191];
               char fil_bin_list[2500][7];
             } bar;
    } C_WA2_FAP;

     /********************************************************************/
     /*                                                                  */
     /*      Platform-Independent Work Area 2 for Function APX           */
     /*                                                                  */
     /********************************************************************/

    typedef struct {
       char filler01[21];      /* Fn AP with extra bytes   */
       char cont_parity_ind;   /* Continuous Parity Ind    */
                               /* or Duplicate Address Ind */
       char lo_hse_nbr[11];    /* Low House Number-Sort Frm*/

       BBL bbl;                /* Borough-Block-Lot        */
       char filler02;          /* Reserved for Tax Lot Ver#*/
       char fil_RPAD_scc;      /* filler for func AP       */
       char filler03;
       char fil_RPAD_lucc[2];  /* fillers for func AP      */
       char fil_corner[2];     /* fillers for func AP      */
       char nbr_blds[4];       /* Nbr of buildings on lot  */
       char fil_nbr_str[2];    /* fillers for func AP      */
       char fil_inter_flag;    /* filler for func AP       */
       char fil_vacant_flag;   /* filler for func AP       */
       char fil_irreg_flag;    /* filler for func AP       */
       char fil_mh_ri_flag;    /* filler for func AP       */
       char fil_adr_range_overflow;/* filler for func AP   */
       char fil_stroll_key[18];/* fillers for func AP      */
       char filler04;
       char res_internal_use;  /* Reserved for Internal Use*/
       char bld_id[7];         /* Building Ident. Number   */
                               /* (BIN) of Input Address of*/
                               /* Existing Building,       */
       char condo_flag;        /* Condominium Flag         */
       char filler05;          /* Future Use               */
       char condo_id[4];       /* RPAD Condo Id Number     */
       char filler_unit_id[7]; /* Condo Unit Id Nbr-Not Impl*/
       BBL  condo_bill_bbl;    /* Condo Billing BBL        */
       char filler06;          /* Reserved for Tax Lot Ver */
       char fil_condo_scc;     /* filler for func AP       */
       BBL  condo_lo_bbl;      /* Low BBL of Condo         */
       char filler07;          /* Reserved for Tax Lot Ver */
       BBL  condo_hi_bbl;      /* High BBL of Condo        */
       char filler08;          /* Reserved for Tax Lot Ver */
       char filler09[15];
       char co_op_nbr[4];      /* Co-op Number             */
       char fil_sanborn[8];    /* fillers for func AP      */
       char fil_business_area[5];  /* fillers for func AP  */
       char fil_tax_map_nbr[5];    /* fillers for func AP  */
       char filler10[4];
       char filler11[3];
       char latitude[9];       /* Latitude calc from X-Y   */
       char longitude[11];     /* Longitude calc from X-Y  */
       char coord[2][7];       /* 1 = X coordinate from AP */
                               /* 2 = Y coordinate from AP */
       char fil_bid_id[6];          /* fillers for func AP */
       char fil_TPAD_bin_status;    /* fillers for func AP */
       char fil_TPAD_new_bin[7];    /* fillers for func AP */
       char fil_TPAD_new_bin_status;/* filler for func AP  */
       char fil_TPAD_conflict_flag; /* filler for func AP  */
       char ap_id[9];               /* Address Point Id    */
       char int_use[8];             /* Internal Use        */
       char reason_code;            /* Reason Code              */
       char reason_code_qual;       /* Reason Code Qualifier    */
       char warn_code[2];           /* Warning Return Code      */
       char ret_code[2];            /* GeoSupport Return Code   */
       char filler14[108];
       char nbr_addr[4];            /* Nbr of Addr = 0001  */

       ADDR_RANGE_APX addr_range_apx[21];
    } C_WA2_FAPX;

     /********************************************************************/
     /*                                                                  */
     /*       Platform-Independent Work Area 2 for Function 2            */
     /*                                                                  */
     /********************************************************************/

    typedef struct { char filler01[21];
                     char rep_cnt;           /* Intersection Replication */
                                             /* Counter*/
                     char lgc[2][2];         /* Preferred LGCs           */
                     St_list inter;          /* Number of Intersecting St*/
                                             /* B5SCs of Intersection St */
                     char Dup_comp;          /* Duplicate compass Directn*/
                     char atomic_polygon[3]; /* Atomic Polygon added V131*/
                     char filler02[2];
                     char LION_node_nbr[7];  /* LION Node Number         */
                     char coord[3][7];       /* 1 = X coordinate,        */
                                             /* 2 = Y coordinate,        */
                                             /* 3 = Z coordinate, Not Imp*/
                     SANBORN San[2];         /* Sanborn Information      */
                     char mh_ri_flag;        /* Marble Hill/Rikers Island*/
                     char DOT_slca;          /* DOT St Lght Contractr Are*/
                     char com_dist[3];       /* Community District       */
                     char zip_code[5];       /* Zip code for st segment  */
                     char health_area[4];    /* Health Area        */
                     char police_boro_com;   /* Police Patrol Boro Commnd*/
                     char police_pre[3];     /* Police Precinct          */
                     char fire_sector[2];    /* Fire Sector              */
                     char fire_bat[2];       /* Fire Battalion           */
                     char fire_co_type;      /* Fire Company Type        */
                     char fire_co_nbr[3];    /* Fire Company Number      */
                     char com_schl_dist[2];  /* Community School District*/
                     char cen_tract_10[6];   /* 2010 Census Tract        */
                     char cen_tract_90[6];   /* 1990 Census Tract        */
                     char level_codes [10];  /* Level codes              */
                     char police_pat_boro[2];/* Police Patrol Borough    */
             //      char filler_indv[2];    /*                          */
             //      char instruc_div [2];   /* Instructional Division   */
                     char ad[2];             /* Assembly District        */
                     char congress_dist[2];  /* Congressional District   */
                     char state_sen_dist[2]; /* State Senatorial District*/
                     char civil_court[2];    /* Civil Court District     */
                     char city_council[2];   /* City Council District    */
                     char cd_eligible;       /* CD Eligibility           */
                     char dup_intersect_distance[5];  /*Distance in Feet */
                                             /*Betwn Duplicate Intersects*/
                                             /* not implemented */
                     char cen_tract_2000[6]; /* 2000 Census Tract        */
                     char health_cen_dist[2];/* Health Cent Distr*/
                     char sanit_dist[3];     /* Sanitation District      */
                     char sanit_sub_sect[2]; /* Sanit Collect Scheduling */
                                             /* Section and Subsection   */
                     char filler03[12];
                   } C_WA2_F2;

     /********************************************************************/
     /*                                                                  */
     /*   Platform-Independent Work Area 2 for Function 2W               */
     /********************************************************************/
    typedef struct {                         /* Fn 2 - 200 Bytes         */
      C_WA2_F2 cwa2f2;                       /* Start with Fn 2 WA2      */
      char filler04[22];                     /* Fields used for Grid gen */
      char lgcs_first_intersct[4][2];        /* Up to 4 LGC's for 1st    */
                                             /* intersecting street;     */
      char lgcs_second_intersct[4][2];       /* Up to 4 LGC's for 2nd    */
                                             /* intersecting street;     */
      char turn_restricts[10];               /* Up to 10 Turn restrictns */
      char pref_lgc_list[5][2];              /* Preferd LGCs for Str list*/
      char true_rep_cnt[2];                  /* True Int Replication Cntr*/
      char dup_node_list[20][7];       /* 140 *Node list for dup str code*/
      char b7sc_list[20][5][4][8];     /* 3200 *B7SC lists for Node list */
      char reason_code;                      /* Reason Code              */
      char reason_code_qual;                 /* future use               */
      char warn_code[2];                     /* Warning Return Code      */
      char ret_code[2];                      /* GeoSupport Return Code   */
      char latitude[9];                      /* Latitude calc from X-Y   */
      char longitude[11];                    /* Longitude calc from X-Y  */
      char filler8[374];                     /* Future Use               */
    } C_WA2_F2W, *PC_WA2_F2W;                /* Fn 2W with filler        */
     /********************************************************************/
     /*                                                                  */
     /*        Platform-Independent Work Area 2 for Function 3           */
     /*                                                                  */
     /********************************************************************/

    typedef struct { char filler01[21];
                     char dup_key_flag;      /* Duplicate Key Flag or    */
                                             /* Continuous Parity Flag   */
                     char loc_stat_seg;      /* Locational Status of Seg */
                     char cnty_bnd_ind;      /* County Boundary Indicat  */
                     char lgc[3][2];         /* Preferred LGCs           */
                     St_list st[2];          /* 1=Low and 2=High         */
                                             /* Nbr of cross sts at low  */
                                             /* house nbr end of street  */
                                             /* B5SCs of lo end X sts    */
                     char x_street_reversal_flag; /* X St Reversal Flag  */
                     LION key;               /* LION Key                 */
                     char genr_flag;         /* Generated Record Flag    */
                     char seg_len[5];        /* Segment Length in Feet   */
                     char seg_azm[3];        /* Segment Azimuth          */
                     char seg_orient;        /* Segment Orientation      */
                     char mh_ri_flag;        /* Marble Hill/Rikers Island*/
                                             /* Alternative Boro flag    */
                     char from_node[7];      /* From node                */
                     char to_node[7];        /* To node                  */
                     char sanit_snow_priority;/* Sanitation Street Snow  */
                                             /* Priority (P,S,T,V)       */
                     char filler02[4];       /* Future use               */
                     char seg_id[7];         /* Segment Identifier       */
                     char DOT_slca;          /* DOT St Lght Contractr Are*/
                     char curve_flag;        /* Curve Flag               */
                     char dog_leg;           /* Dog leg flag             */
                     char feature_type;      /* Feature Type Code        */
                     char segmenttypecode;   /* Segment Type Code        */
                     char coincident_seg_cnt; /* Coincident Segment      */
                                             /*    Counter               */
                     char filler03[4];
                     SEGSIDE side[2];        /* 1 = Left Side of street  */
                                             /* 2 = Right Side of street */
                   } C_WA2_F3;

    typedef struct { C_WA2_F3 cwa2f3;
                     char filler1[6];        /* Future use              */
                     char seg_cnt[4];        /* Number of Segments      */
                     char segments[70][7];   /* Segment Ids             */
                   } C_WA2_F3_AUXSEG;
     /********************************************************************/
     /*                                                                  */
     /*      Platform-Independent Work Area 2 for Function 3 EXTENDED    */
     /*                                                                  */
     /********************************************************************/

    typedef struct {                        /*  Data from CSCL added     */
      C_WA2_F3 cwa2f3;
      char lgc_list[4][2];                   /* List of LGC's            */
      char from_lgcs[4][2];                  /* List of from LGC's       */
      char to_lgcs[4][2];                    /* List of to LGC's         */
      char left_hcd[2];                      /* Left Health Center   */
                                             /* District                 */
      char right_hcd[2];                     /* Right Health Center  */
                                             /* District                 */
      char filler_csd;                       /*                          */
      char traffic_dir;                      /* Traffic Direction        */
      char roadway_type[2];                  /*                          */
      char physical_id[7];                   /*                          */
      char generic_id[7];                    /*                          */
      char filler03[7];                      /* DCP internal use         */
      char filler04[7];                      /* DCP internal use         */
      char street_status;                    /*                          */
      char str_width[3];                     /* Street Width             */
      char str_width_irr;                    /* Irregular Width Y or N   */
      char bike_lane;                        /*                          */
      char fcc[2];                           /* Federal Classification Cd*/
      char row_type;                         /*                          */
      char lgc5[2];                          /*                          */
      char lgc6[2];                          /*                          */
      char lgc7[2];                          /*                          */
      char lgc8[2];                          /*                          */
      char lgc9[2];                          /*                          */
      char legacy_id[7];                     /*                          */
      char nta_name_left[75];                /* Neighborhood Tabulation  */
                                             /* Area Name (Left)         */
      char nta_name_right[75];               /* Neighborhood Tabulation  */
                                             /* Area Name (Right)        */
      char from_coord[2][7];                 /* 1 = X Coordinate         */
                                             /* 2 = Y Coordinate         */
      char to_coord[2][7];                   /* 1 = X Coordinate         */
                                             /* 2 = Y Coordinate         */
      char from_latitude[9];                 /*Latitude of from intersct.*/
      char from_longitude[11];               /*Longitude of from intersct*/
      char to_latitude[9];                   /*Latitude of to intersect. */
      char to_longitude[11];                 /*Longitude of to intersect.*/
      char left_blockface_id[10];            //NEW location of blockface id
      char right_blockface_id[10];
      char nbr_travel_lanes[2];              /* nbr of traveling lanes   */
      char nbr_park_lanes[2];                /* nbr of parking lanes     */
      char nbr_total_lanes[2];               /* total nbr of lanes       */
      char bike_lane_2[2];                   /*Bike Lane has 2 bytes     */
                                             /* numeric value            */
      char str_width_max[3];                 /*Street width maximum      */
      char bike_traffic_dir[2];             //V17.1 Bike Traffic Direction
      char filler05[213];                    // V17.1
    } C_WA2_F3X;

    typedef struct {                         /* Fn 3 Extended with       */
      C_WA2_F3X cwa2f3x;                     /* Auxilary Segments        */
      char filler1[6];                        /* Future use              */
      char seg_cnt[4];                        /* Number of Segments      */
      char segments[70][7];                   /* Segment Ids             */
    } C_WA2_F3X_AUXSEG;                      /* Fn 3X with AUXSEGID      */


     /********************************************************************/
     /*                                                                  */
     /*        Platform-Independent Work Area 2 for Function 3C          */
     /*                                                                  */
     /********************************************************************/

    typedef struct { char filler01[21];
                     char dup_key_flag;      /* Duplicate Key Flag or    */
                                             /* Continuous Parity Flag   */
                     char loc_stat_seg;      /* Locational Status of Seg */
                     char cnty_bnd_ind;      /* County Boundary Indicat  */
                     char lgc[3][2];         /* Preferred LGCs           */
                     St_list st[2];          /* 1=Low and 2=High         */
                                             /* Nbr of cross sts at low  */
                                             /* house nbr end of street  */
                                             /* B5SCs of lo end Cross sts*/
                     char x_street_reversal_flag; /* X St Reversal Flag  */
                     LION key;               /* LION key                 */
                     char genr_flag;         /* Generated Record Flag    */
                     char seg_len[5];        /* Segment Length in Feet   */
                     char seg_azm[3];        /* Segment Azimuth          */
                     char seg_orient;        /* Segment Orientation      */
                     char mh_ri_flag;        /* Marble Hill/Rikers Island*/
                                             /* Alternative Boro flag    */
                     char from_node[7];      /* From node                */
                     char to_node[7];        /* To Node                  */
                     char sanit_snow_priority;/* Sanitation Street Snow  */
                                              /* Priority (P,S,T,V)      */
                     char filler02[4];       /* Future use               */
                     char seg_id  [7];       /* Segment Identifier       */
                     char DOT_slca;          /* DOT St Lght Contractr Are*/
                     char sos_ind;           /* Side of Street Indicator */
                     char curve_flag;        /* Curve Flag               */
                     char feature_type;      /* Feature Type Code        */
                     char segmenttypecode;   /* Segment Type Code        */
                     char coincident_seg_cnt; /* Coincident Segment      */
                                              /*    Counter              */
                     char filler03[4];
                     SEGSIDE req;           /* Geographic Information for*/
                  } C_WA2_F3C;

    typedef struct { C_WA2_F3C cwa2f3c;
                     char filler1[6];        /* Future use              */
                     char seg_cnt[4];        /* Number of Segments      */
                     char segments[70][7];   /* Segment ids             */
                   } C_WA2_F3C_AUXSEG;

     /********************************************************************/
     /*                                                                  */
     /*      Platform-Independent Work Area 2 for Function 3C EXTENDED   */
     /*                                                                  */
     /********************************************************************/
    typedef struct {                         /* Data from CSCL added     */
      C_WA2_F3C cwa2f3c;
      char lgc_list[4][2];                   /* List of LGC's            */
      char from_lgcs[4][2];                  /* List of from LGC's       */
      char to_lgcs[4][2];                    /* List of to LGC's         */
      char left_hcd[2];                      /* Left Health Center Distr */
      char right_hcd[2];                     /* Right Health Center Distr*/
      char fill_csd;                         /* Filler                   */
      char traffic_dir;                      /* Traffic Direction        */
      char roadway_type[2];                  /*                          */
      char physical_id[7];                   /*                          */
      char generic_id[7];                    /*                          */
      char filler03[7];                      /* DCP internal use         */
      char filler04[7];                      /* DCP internal use         */
      char street_status;                    /*                          */
      char str_width[3];                     /* Street Width             */
      char str_width_irr;                    /* Irregular Width Y or N   */
      char bike_lane;                        /*                          */
      char fcc[2];                           /* Federal Classification Cd*/
      char row_type;                         /*                          */
      char lgc5[2];                          /*                          */
      char lgc6[2];                          /*                          */
      char lgc7[2];                          /*                          */
      char lgc8[2];                          /*                          */
      char lgc9[2];                          /*                          */
      char legacy_id[7];                     /*                          */
      char nta_name[75];                     /* Neighborhood Tabulation  */
                                             /* Area Name                */
      char from_coord[2][7];                 /* 1 = X Coordinate         */
                                             /* 2 = Y Coordinate         */
      char to_coord[2][7];                   /* 1 = X Coordinate         */
                                             /* 2 = Y Coordinate         */
      char from_latitude[9];                /* Latitude of from intersct.*/
      char from_longitude[11];              /* Longitude of from intersct*/
      char to_latitude[9];                  /* Latitude of to intersct.  */
      char to_longitude[11];                /* Longitude of to intersct. */
      char blockface_id[10];                /* NEW location of this field*/
                                            /* because of length changed */
      char nbr_travel_lanes[2];              /* nbr of traveling lanes   */
      char nbr_park_lanes[2];                /* nbr of parking lanes     */
      char nbr_total_lanes[2];               /* total nbr of lanes       */
      char bike_lane_2[2];                   /*Bike Lane has 2 bytes     */
                                             /* numeric value            */
      char str_width_max[3];                 /*street width maximum      */
      char bike_traffic_dir[2];              //V17.1 Bike Traffic Direction
      char filler05[298];                    // V17.1
    } C_WA2_F3CX;

    typedef struct {                         /* Fn 3C Extended with      */
      C_WA2_F3CX cwa2f3cx;                   /* Auxilary Segments        */
      char filler1[6];                       /* Future use              */
      char seg_cnt[4];                       /* Number of Segments      */
      char segments[70][7];                  /* Segment Ids             */
    } C_WA2_F3CX_AUXSEG;                     /* Fn 3CX with AUXSEGID     */

     /********************************************************************/
     /*                                                                  */
     /*        Platform-Independent Work Area 2 for Function 3S          */
     /*                                                                  */
     /********************************************************************/

    typedef struct { char filler01[21];
                     char nbr_x_str[3];      /* Nbr of Cross sts in list */
                     CROSS_STRS cross_strs[350];/* Cross Street structure*/
                   } C_WA2_F3S;

    #ifdef __cplusplus
           }
    #endif
    #endif




## <span id="appendix14.22"><center>NATURAL LDAs (COW)</center></span>  

## <span id="appendix14.23"><center>GEOLP1 COPY File</center></span>  

    *    USER PROGRAMS MUST RESET GEOLP1        BEFORE PRIMING WORKAREA 1             
       1 GEOLP1                                        /* LRECL=1200                  
    *    THE FIELD P1NAT IS USED AS A        PARAMETER TO CALL GEOSUPPORT        RT   
       2 P1NAT                            A          2                                
    R  2 P1NAT                                                                        
    *  * * * *   INPUT FIELDS    * * * *  *  * * * * * /* WORK AREA 1 FOR             
    *  *                                               /* ALL FUNCTIONS               
       3 PIWA1-IN-FUNCTION-CODE           A          2                                
    R  3 PIWA1-IN-FUNCTION-CODE                                                       
       4 PIWA1-IN-FUNCTION-1              A          1                                
       4 PIWA1-IN-FUNCTION-2              A          1                                
       2 PIWA1-IN-HOUSENUM-DISPLAY        A         16                                
       2 PIWA1-IN-HOUSENUM-SORT           A         11                                
       2 PIWA1-IN-LOW-HOUSENUM-DISPLAY    A         16                                
       2 PIWA1-IN-LOW-HOUSENUM-SORT       A         11                                
       2 PIWA1-IN-BORO-1                  A          1                                
       2 PIWA1-IN-10SC-1                  A         10                                
       2 PIWA1-IN-STREET-1                A         32                                
       2 PIWA1-IN-BORO-2                  A          1                                
       2 PIWA1-IN-10SC-2                  A         10                                
       2 PIWA1-IN-STREET-2                A         32                                
       2 PIWA1-IN-BORO-3                  A          1                                
       2 PIWA1-IN-10SC-3                  A         10                                
       2 PIWA1-IN-STREET-3                A         32                                
       2 PIWA1-IN-BBL                     A         10 /* 3 LEVEL 3 ITEMS             
    R  2 PIWA1-IN-BBL                                                                 
       3 PIWA1-IN-BBL-BORO                A          1                                
       3 PIWA1-IN-BLOCK                   A          5                                
       3 PIWA1-IN-LOT                     A          4                                
       2 PIWA1-IN-LOT-VERSION             A          1 /* NA                          
       2 PIWA1-IN-BIN                     A          7                                
       2 PIWA1-IN-COMPASS                 A          1                                
       2 PIWA1-IN-COMPASS2                A          1                                
       2 PIWA1-IN-NODE                    A          7                                
       2 PIWA1-IN-PLATFORM-INDICATOR      A          1                                
       2 PIWA1-IN-ZIPCODE                 A          5                                
       2 PIWA1-IN-UNIT                    A         14 /* V16.4 ADDITION              
       2 FILLER-200                       A         82 /* V16.4 ALTERATION            
    *  2 FILLER-200                       A         96                                
       2 PIWA1-IN-LONG-WORKAREA2-FLAG     A          1 /* L=LONG WA - 1A/BL(1200)     
       2 PIWA1-IN-HSE-NBR-JUSTIFY         A          1                                
       2 PIWA1-IN-HNL                     A          2 /* HN LENGTH                   
       2 PIWA1-IN-HSE-OVER-FLAG           A          1 /* HN OVERRIDE *,$,' '         
       2 PIWA1-IN-SNL                     A          2                                
       2 PIWA1-IN-SN-NORM-FORMAT          A          1 /* C=COMPACT,S OR ' '=SORTT    
       2 PIWA1-IN-EXPANDED-FORMAT         A          1                                
       2 PIWA1-IN-ROADBED-REQ-SWITCH      A          1                                
       2 PIWA1-IN-INTERNAL-USE-LEGACY     A          1 /* RESERVED FOR GSS USE        
       2 PIWA1-IN-SEGAUX-SWITCH           A          1                                
       2 PIWA1-IN-BROWSE-FLAG             A          1                                
       2 PIWA1-IN-REAL-STREET-ONLY        A          1 /* FN 3S                       
       2 PIWA1-IN-TPAD-SWITCH             A          1 /* FN 1A                       
       2 PIWA1-IN-MODE-SWITCH             A          1                                
       2 PIWA1-IN-WTO-SWITCH              A          1                                
       2 FILLER-400                       A         29                                
    *  * * * *   OUTPUT FIELDS   * * * *  *  * * * * *                                
       2 PIWA1-OUT-BORONAME               A          9                                
       2 PIWA1-OUT-HOUSENUM-DISPLAY       A         16                                
       2 PIWA1-OUT-HOUSENUM-SORT          A         11                                
       2 PIWA1-OUT-B10SC-1                A         11                                
       2 PIWA1-OUT-STREET-1               A         32                                
       2 PIWA1-OUT-B10SC-2                A         11                                
       2 PIWA1-OUT-STREET-2               A         32                                
       2 PIWA1-OUT-B10SC-3                A         11                                
       2 PIWA1-OUT-STREET-3               A         32                                
       2 PIWA1-OUT-BBL                    A         10 /* 3 LEVEL 3 ITEMS             
    R  2 PIWA1-OUT-BBL                                                                
       3 PIWA1-OUT-BBL-BORO               A          1                                
       3 PIWA1-OUT-BLOCK                  A          5                                
       3 PIWA1-OUT-LOT                    A          4                                
       2 PIWA1-OUT-LOT-VERSION            A          1 /* FOR FUTRUE LOT VERSION #    
       2 PIWA1-OUT-LOW-HOUSENUM-DISPLAY   A         16                                
       2 PIWA1-OUT-LOW-HOUSENUM-SORT      A         11                                
       2 PIWA1-OUT-BIN                    A          7                                
       2 PIWA1-OUT-STREET-ATTR            A          1 (1:3) /* RES FOR GSS           
       2 PIWA1-OUT-REASON-CODE-2          A          1 /* FN 1B                       
       2 PIWA1-OUT-REASON-CODE-QUAL-2     A          1 /*TPAD 2ND REASON CODE         
    *  *                                               /*QUALIFIER                    
       2 PIWA1-OUT-WARNING-CODE-2         A          2 /* FN 1B                       
       2 PIWA1-OUT-RETURN-CODE-2          A          2 /* FN 1B                       
       2 PIWA1-OUT-ERROR-MESSAGE-2        A         80 /* FN 1B                       
       2 PIWA1-OUT-NODE                   A          7                                
       2 PIWA1-OUT-UNIT-SORT              A         14 /* V16.4 ADDITION              
    R  2 PIWA1-OUT-UNIT-SORT                                                          
       3 PIWA1-OUT-UNIT-TYPE              A          4 /* V16.4 ADDITION              
       3 PIWA1-OUT-UNIT-ID                A         10 /* V16.4 ADDITION              
       2 PIWA1-OUT-UNIT-DISP              A         14 /* V16.4 ADDITION              
       2 FILLER-550                       A         11 /* V16.4 ALTERATION            
    *  2 FILLER-550                       A         39                                
       2 FILLER-555                       A          6 /* NIN, NYI                    
       2 PIWA1-OUT-SND-ATTR               A          1 /* RES FOR GSS                 
       2 PIWA1-OUT-REASON-CODE            A          1                                
       2 PIWA1-OUT-REASON-CODE-QUAL       A          1 /*TAPAD REASON CODE            
    *  *                                               /*QUALIFIER                    
       2 PIWA1-OUT-WARNING-CODE           A          2                                
       2 PIWA1-OUT-RETURN-CODE            A          2                                
       2 PIWA1-OUT-ERROR-MESSAGE          A         80                                
       2 PIWA1-OUT-NUM-SIMILAR-STRS       A          2                                
       2 PIWA1-OUT-SIMILAR-B7SC           A          8 (1:10)                         
       2 PIWA1-OUT-SIMILAR-NAMES          A         32 (1:10)                         


## <span id="appendix14.24"><center>GEOLP2 COPY File</center></span>  

    1 GEOLP2                                                                       
    *    THE FIELD P2NAT IS USED AS A        PARAMETER TO CALL GEOSUPPORT FOR ALLLL   
    *        FUNCTIONS THAT ARE REDEFINED           ON GEOLP2                         
    *  * MAXIMUM LENGTH 2W - 4000 BYTES                                               
    2 P2NAT                            A         21                                
    R  2 P2NAT                                                                        
    *  *  BEGINNING OF FUNCTION 1 LAYOUT  *       **** *******                        
    3 PIWA2-FN1-ACCESS-KEY             A         21                                
    2 PIWA2-FN1-CONT-PARITY            A          1 /* (OR DUP ADDR IND)           
    2 PIWA2-FN1-LOW-HOUSENUM           A         11 /* SORT FORMAT                 
    2 PIWA2-FN1-HI-HOUSENUM            A         11 /* SORT FORMAT                 
    2 PIWA2-FN1-PREFERRED-LGC          A          2                                
    2 PIWA2-FN1-NUM-X-ST-LOW-END       A          1                                
    2 PIWA2-FN1-LOW-B5SC               A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN1-NUM-X-ST-HI-END        A          1                                
    2 PIWA2-FN1-HI-B5SC                A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN1-LIONKEY                A         10                                
    R  2 PIWA2-FN1-LIONKEY                                                            
    3 PIWA2-FN1-LION-BORO              A          1                                
    3 PIWA2-FN1-LION-FACECODE          A          4                                
    3 PIWA2-FN1-LION-SEQ               A          5                                
    2 PIWA2-FN1-SPECIAL-ADDR-FLAG      A          1                                
    2 PIWA2-FN1-SIDE-OF-STR            A          1                                
    2 PIWA2-FN1-SEG-LEN                A          5                                
    2 PIWA2-FN1-X-COORD                A          7                                
    2 PIWA2-FN1-Y-COORD                A          7                                
    2 FILLER-100                       A          7 /* FOR ZCOORD                  
    2 FILLER-200                       A          1 /* FOR GSS USE                 
    2 PIWA2-FN1-MARBLE-RIKERS-FLAG     A          1                                
    2 PIWA2-FN1-DOT-SLA                A          1                                
    2 PIWA2-FN1-COM-DIST               A          3                                
    R  2 PIWA2-FN1-COM-DIST                                                           
    3 PIWA2-FN1-COM-DIST-BORO          A          1                                
    3 PIWA2-FN1-COM-DIST-NUM           A          2                                
    2 PIWA2-FN1-ZIP                    A          5                                
    *  *                                  *       **** *****                          
    *  *  THE FN1E FIELDS ARE VALID ONLY  *       **** *****                          
    *  *  FOR FUNCTION 1E, NOT FUNC 1.    *       **** *****                          
    2 PIWA2-FN1E-ELECT-DIST            A          3                                
    2 PIWA2-FN1E-ASSEM-DIST            A          2                                
    2 PIWA2-FN1E-SPLIT-ED-FLAG         A          1                                
    2 PIWA2-FN1E-CONG-DIST             A          2                                
    2 PIWA2-FN1E-SENATE-DIST           A          2                                
    2 PIWA2-FN1E-COURT-DIST            A          2                                
    2 PIWA2-FN1E-COUNCIL-DIST          A          2                                
    *  *                                  *       **** *****                          
    2 PIWA2-FN1-HEALTH-CENTER-DIST     A          2                                
    2 PIWA2-FN1-HEALTH-AREA            A          4                                
    2 PIWA2-FN1-SANI-DIST              A          3                                
    R  2 PIWA2-FN1-SANI-DIST                                                          
    3 PIWA2-FN1-SANI-DIST-BORO         A          1                                
    3 PIWA2-FN1-SANI-DIST-NUM          A          2                                
    2 PIWA2-FN1-SANI-SUBSEC            A          2                                
    2 PIWA2-FN1-SANI-REG               A          5                                
    2 PIWA2-FN1-SANI-REC               A          3                                
    2 PIWA2-FN1-POLICE-DIST            A          4                                
    R  2 PIWA2-FN1-POLICE-DIST                                                        
    3 PIWA2-FN1-POL-PAT-BORO-CMD       A          1                                
    3 PIWA2-FN1-POL-PRECINCT           A          3                                
    2 PIWA2-FN1-FIRE-DIV               A          2                                
    2 PIWA2-FN1-FIRE-BAT               A          2                                
    2 PIWA2-FN1-FIRE-CO                A          4                                
    R  2 PIWA2-FN1-FIRE-CO                                                            
    3 PIWA2-FN1-FIRE-CO-TYPE           A          1                                
    3 PIWA2-FN1-FIRE-CO-NUM            A          3                                
    2 PIWA2-FN1-SCHL-DIST-SPLIT-FLAG   A          1                                
    2 PIWA2-FN1-SCHL-DIST              A          2                                
    2 PIWA2-FN1-DYN-BLK                A          3                                
    2 PIWA2-FN1-POLICE-PAT-BORO        A          2                                
    2 PIWA2-FN1-FEATURE-TYPE           A          1                                
    2 PIWA2-FN1-SEGMENT-TYPE           A          1                                
    2 PIWA2-FN1-ALX                    A          1                                
    2 PIWA2-FN1-COINCIDENT-SEG-CTR     A          1                                
    2 FILLER-290                       A          3                                
    2 PIWA2-FN1-1990-CENSUS-TRACT      A          6                                
    2 PIWA2-FN1-2010-CENSUS-TRACT      A          6                                
    2 PIWA2-FN1-2010-CENSUS-BLOCK      A          4                                
    2 PIWA2-FN1-2010-CENSUS-BLOCK-SUF  A          1 /* NA                          
    2 PIWA2-FN1-2000-CENS-TRACT        A          6                                
    2 PIWA2-FN1-2000-CENS-BLOCK        A          4                                
    2 PIWA2-FN1-2000-CENS-BLOCK-SUF    A          1 /* NA                          
    2 PIWA2-FN1-NTA                    A          4                                
    2 PIWA2-FN1-SANIT-SNOW-PRIORITY    A          1                                
    2 PIWA2-FN1-SANIT-ORGANICS         A          5                                
    2 PIWA2-FN1-SANIT-BULK-PICK-UP     A          5 /* V16.4 ADDITION              
    *  2 PIWA2-FN1-SANIT-RESERVED         A          5 /*FOR POSSIBLE FUTURE USE      
    2 PIWA2-FN1-HURRICANE-ZONE         A          2 /*OEM HURRICANE EVAC ZONE      
    2 FILLER-300                       A         11                                
    2 PIWA2-FN1-UHNS                   A         11 /* UNDERLYING HNS              
    2 PIWA2-FN1-REAL-B7SC              A          8                                
    2 PIWA2-FN1-SEGMENT-ID             A          7                                
    2 PIWA2-FN1-CURVE-FLAG             A          1                                
    2 PIWA2-FN1-PSEUDO-FILLER          A       3700 /*MAX RECORD 2W IS 4000        
    *  *  END OF FUNCTION 1 LAYOUT        *       **** *******                        
    *  - -------------------------------- -       ---- -------------------------------
    *  *  BEGINNING OF FUNCTION 2                                                     
    *  *           & FUNCTION 2C LAYOUT   * ********** *******                        
    R  1 GEOLP2                                                                       
    2 PIWA2-FN2-ACCESS-KEY             A         21 /* FOR FUNCTIONS 2 & 2C        
    2 PIWA2-FN2-DUP-INTERSECT-FLAG     A          1                                
    2 PIWA2-FN2-PREFERRED-LGC1         A          2                                
    2 PIWA2-FN2-PREFERRED-LGC2         A          2                                
    2 PIWA2-FN2-NUM-OF-INTERSECTS      A          1                                
    2 PIWA2-FN2-INTERSECT-B5SC         A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN2-COMP-DIR               A          1                                
    2 PIWA2-FN2-ATOMIC-POLYGON         A          3                                
    2 FILLER-350                       A          2                                
    2 PIWA2-FN2-NODE-NUM               A          7                                
    2 PIWA2-FN2-X-COORD                A          7                                
    2 PIWA2-FN2-Y-COORD                A          7                                
    2 FILLER-400                       A          7 /* FOR ZCOORD                  
    2 PIWA2-FN2-SANBORN1               A          8                                
    R  2 PIWA2-FN2-SANBORN1                                                           
    3 PIWA2-FN2-SANBORN1-BORO          A          1                                
    3 PIWA2-FN2-SANBORN1-VOL           A          3                                
    3 PIWA2-FN2-SANBORN1-PAGE          A          4                                
    2 PIWA2-FN2-SANBORN2               A          8                                
    R  2 PIWA2-FN2-SANBORN2                                                           
    3 PIWA2-FN2-SANBORN2-BORO          A          1                                
    3 PIWA2-FN2-SANBORN2-VOL           A          3                                
    3 PIWA2-FN2-SANBORN2-PAGE          A          4                                
    2 PIWA2-FN2-MARBLE-RIKERS-FLAG     A          1                                
    2 PIWA2-FN2-DOT-SLA                A          1                                
    2 PIWA2-FN2-COM-DIST               A          3                                
    R  2 PIWA2-FN2-COM-DIST                                                           
    3 PIWA2-FN2-COM-DIST-BORO          A          1                                
    3 PIWA2-FN2-COM-DIST-NUM           A          2                                
    2 PIWA2-FN2-ZIP                    A          5                                
    2 PIWA2-FN2-HEALTH-AREA            A          4                                
    2 PIWA2-FN2-POLICE-DIST            A          4                                
    R  2 PIWA2-FN2-POLICE-DIST                                                        
    3 PIWA2-FN2-POL-PAT-BORO-CMD       A          1                                
    3 PIWA2-FN2-POL-PRECINCT           A          3                                
    2 PIWA2-FN2-FIRE-DIV               A          2                                
    2 PIWA2-FN2-FIRE-BAT               A          2                                
    2 PIWA2-FN2-FIRE-CO                A          4                                
    R  2 PIWA2-FN2-FIRE-CO                                                            
    3 PIWA2-FN2-FIRE-CO-TYPE           A          1                                
    3 PIWA2-FN2-FIRE-CO-NUM            A          3                                
    2 PIWA2-FN2-SCHL-DIST              A          2                                
    2 PIWA2-FN2-2010-CENSUS-TRACT      A          6                                
    2 PIWA2-FN2-1990-CENSUS-TRACT      A          6                                
    2 PIWA2-FN2-LEVEL-CODE-TBL         A         10                                
    R  2 PIWA2-FN2-LEVEL-CODE-TBL                                                     
    3 PIWA2-FN2-LEVEL-CODE             A          1 (5,2) /* 10-BYTES              
    2 PIWA2-FN2-POLICE-PAT-BORO        A          2                                
    2 PIWA2-FN2-ASSEM-DIST             A          2                                
    2 PIWA2-FN2-CONG-DIST              A          2                                
    2 PIWA2-FN2-SENATE-DIST            A          2                                
    2 PIWA2-FN2-COURT-DIST             A          2                                
    2 PIWA2-FN2-COUNCIL-DIST           A          2                                
    2 PIWA2-FN2-CD-ELIGIBLE            A          1                                
    2 PIWA2-FN2-DUP-INTERSECT-DIST     A          5                                
    2 PIWA2-FN2-2000-CENS-TRACT        A          6                                
    2 PIWA2-FN2-HEALTH-CENTER-DIST     A          2                                
    2 PIWA2-FN2-SANITATION-DIST        A          3                                
    2 PIWA2-FN2-SANITATION-SUBSEC      A          2                                
    2 FILLER-500                       A         12                                
    *  2 PIWA2-FN2-PSEUDO-FILLER          A       3800                                
    *  *  END OF FUNCTION 2               * ********** ********                       
    *  *       & FUNCTION 2C LAYOUT       * ********** ********                       
    *  * -------------------------------- - ---------- -----------------              
    *  *  BEGINNING OF FUNCTION 2W        * ********** *******                        
    R  1 GEOLP2                                                                       
    2 PIWA2-FN2W-ACCESS-KEY            A         21 /* FOR FUNCTION 2W             
    2 PIWA2-FN2W-DUP-INTERSECT-FLAG    A          1                                
    2 PIWA2-FN2W-PREFERRED-LGC1        A          2                                
    2 PIWA2-FN2W-PREFERRED-LGC2        A          2                                
    2 PIWA2-FN2W-NUM-OF-INTERSECTS     A          1                                
    2 PIWA2-FN2W-INTERSECT-B5SC        A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN2W-COMP-DIR              A          1                                
    2 PIWA2-FN2W-ATOMIC-POLYGON        A          3                                
    2 FILLER-350W                      A          2                                
    2 PIWA2-FN2W-NODE-NUM              A          7                                
    2 PIWA2-FN2W-X-COORD               A          7                                
    2 PIWA2-FN2W-Y-COORD               A          7                                
    2 FILLER-400W                      A          7 /* FOR ZCOORD                  
    2 PIWA2-FN2W-SANBORN1              A          8                                
    R  2 PIWA2-FN2W-SANBORN1                                                          
    3 PIWA2-FN2W-SANBORN1-BORO         A          1                                
    3 PIWA2-FN2W-SANBORN1-VOL          A          3                                
    3 PIWA2-FN2W-SANBORN1-PAGE         A          4                                
    2 PIWA2-FN2W-SANBORN2              A          8                                
    R  2 PIWA2-FN2W-SANBORN2                                                          
    3 PIWA2-FN2W-SANBORN2-BORO         A          1                                
    3 PIWA2-FN2W-SANBORN2-VOL          A          3                                
    3 PIWA2-FN2W-SANBORN2-PAGE         A          4                                
    2 PIWA2-FN2W-MARBLE-RIKERS-FLAG    A          1                                
    2 PIWA2-FN2W-DOT-SLA               A          1                                
    2 PIWA2-FN2W-COM-DIST              A          3                                
    R  2 PIWA2-FN2W-COM-DIST                                                          
    3 PIWA2-FN2W-COM-DIST-BORO         A          1                                
    3 PIWA2-FN2W-COM-DIST-NUM          A          2                                
    2 PIWA2-FN2W-ZIP                   A          5                                
    2 PIWA2-FN2W-HEALTH-AREA           A          4                                
    2 PIWA2-FN2W-POLICE-DIST           A          4                                
    R  2 PIWA2-FN2W-POLICE-DIST                                                       
    3 PIWA2-FN2W-POL-PAT-BORO-CMD      A          1                                
    3 PIWA2-FN2W-POL-PRECINCT          A          3                                
    2 PIWA2-FN2W-FIRE-DIV              A          2                                
    2 PIWA2-FN2W-FIRE-BAT              A          2                                
    2 PIWA2-FN2W-FIRE-CO               A          4                                
    R  2 PIWA2-FN2W-FIRE-CO                                                           
    3 PIWA2-FN2W-FIRE-CO-TYPE          A          1                                
    3 PIWA2-FN2W-FIRE-CO-NUM           A          3                                
    2 PIWA2-FN2W-SCHL-DIST             A          2                                
    2 PIWA2-FN2W-2010-CENSUS-TRACT     A          6                                
    2 PIWA2-FN2W-1990-CENSUS-TRACT     A          6                                
    2 PIWA2-FN2W-LEVEL-CODE-TBL        A         10                                
    R  2 PIWA2-FN2W-LEVEL-CODE-TBL                                                    
    3 PIWA2-FN2W-LEVEL-CODE            A          1 (5,2) /* 10-BYTES              
    2 PIWA2-FN2W-POLICE-PAT-BORO       A          2                                
    2 PIWA2-FN2W-ASSEM-DIST            A          2                                
    2 PIWA2-FN2W-CONG-DIST             A          2                                
    2 PIWA2-FN2W-SENATE-DIST           A          2                                
    2 PIWA2-FN2W-COURT-DIST            A          2                                
    2 PIWA2-FN2W-COUNCIL-DIST          A          2                                
    2 PIWA2-FN2W-CD-ELIGIBLE           A          1                                
    2 PIWA2-FN2W-DUP-INTERSECT-DIST    A          5                                
    2 PIWA2-FN2W-2000-CENS-TRACT       A          6                                
    2 PIWA2-FN2W-HEALTH-CENTER-DIST    A          2                                
    2 PIWA2-FN2W-SANITATION-DIST       A          3                                
    2 PIWA2-FN2W-SANITATION-SUBSEC     A          2                                
    2 FILLER-500W                      A         12                                
    2 PIWA2-FN2W-FILLER-GRIDGEN        A         22 /*INTERNAL USE                 
    2 PIWA2-FN2W-LGCS-FIRST-INTERSCT   A          2 (1:4) /*UP TO 4 LGCS           
    2 PIWA2-FN2W-LGCS-SECOND-INTERSCT  A          2 (1:4) /*UP TO 4 LGCS           
    2 PIWA2-FN2W-TURN-RESTRICTIONS     A          1 (1:10)                         
    2 PIWA2-FN2W-INTERSECT-B5SC-LGCS   A          2 (1:5) /*LGCS FOR LIST          
    *                                                  /*OF INTERSECTING STS          
    2 PIWA2-FN2W-REPLICATION-CNTR      A          2                                
    2 PIWA2-FN2W-NODE-LIST             A          7 (1:20) /*UP TO 20 NODES        
    2 PIWA2-FN2W-NODE-LIST-B7SCS-TBLS  A       3200                                
    R  2 PIWA2-FN2W-NODE-LIST-B7SCS-TBLS               /* REDEF. BEGIN : PIWA2-FN2W-NO
    3 PIWA2-FN2W-NODE-LIST-B7SCS-TBL   A        160 (20)                           
    R  2 PIWA2-FN2W-NODE-LIST-B7SCS-TBLS               /* REDEF. BEGIN : PIWA2-FN2W-NO
    3 PIWA2-FN2W-NODE-LIST-B7SCS-STS   A         32 (20,5)                         
    R  2 PIWA2-FN2W-NODE-LIST-B7SCS-TBLS               /* REDEF. BEGIN : PIWA2-FN2W-NO
    3 PIWA2-FN2W-NODE-LIST-B7SCS       A          8 (20,5,4)                       
    2 PIWA2-FN2W-REASON-CODE           A          1                                
    2 PIWA2-FN2W-REASON-CODE-QUAL      A          1                                
    2 PIWA2-FN2W-WARN-CODE             A          2                                
    2 PIWA2-FN2W-RETURN-CODE           A          2                                
    2 PIWA2-FN2W-LATITUDE              A          9                                
    2 PIWA2-FN2W-LONGITUDE             A         11                                
    2 PIWA2-FN2W-FILLER2W              A        374                                
    *  *  END OF FUNCTION 2W              * ********** ********                       
    *  * -------------------------------- - ---------- -----------------              
    *  *  BEGINNING OF FUNCTION 3 LAYOUT  * ********** *********                      
    R  1 GEOLP2                                                                       
    2 PIWA2-FN3-ACCESS-KEY             A         21                                
    2 PIWA2-FN3-DUP-KEY-FLAG           A          1 /* OR CONTI PARITY             
    2 PIWA2-FN3-LOCATION-STATUS        A          1                                
    2 PIWA2-FN3-COUNTY-BOUNDARY        A          1                                
    2 PIWA2-FN3-PREFERRED-LGC1         A          2                                
    2 PIWA2-FN3-PREFERRED-LGC2         A          2                                
    2 PIWA2-FN3-PREFERRED-LGC3         A          2                                
    2 PIWA2-FN3-NUM-X-ST-LOW-END       A          1                                
    2 PIWA2-FN3-LOW-B5SC               A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN3-NUM-X-ST-HI-END        A          1                                
    2 PIWA2-FN3-HI-B5SC                A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN3-REVERSAL-FLAG          A          1                                
    2 PIWA2-FN3-LION-KEY               A         10                                
    R  2 PIWA2-FN3-LION-KEY                                                           
    3 PIWA2-FN3-LION-BORO              A          1                                
    3 PIWA2-FN3-LION-FACECODE          A          4                                
    3 PIWA2-FN3-LION-SEQ               A          5                                
    2 PIWA2-FN3-GENREC-FLAG            A          1                                
    2 PIWA2-FN3-SEG-LENGTH             A          5                                
    2 PIWA2-FN3-SEG-SLOP               A          3                                
    2 PIWA2-FN3-SEG-ORIENT             A          1                                
    2 PIWA2-FN3-MARBLE-RIKERS-FLAG     A          1                                
    2 PIWA2-FN3-FROM-NODE              A          7                                
    2 PIWA2-FN3-TO-NODE                A          7                                
    2 PIWA2-FN3-SANIT-SNOW-PRIORITY    A          1 /*SANITATION STRT              
    *  *                                               /*SNOW PRIORITY                
    2 FILLER-600                       A          4                                
    2 PIWA2-FN3-SEGMENT-ID             A          7                                
    2 PIWA2-FN3-DOT-SLA                A          1                                
    2 PIWA2-FN3-CURVE-FLAG             A          1                                
    2 PIWA2-FN3-DOG-LEG                A          1                                
    2 PIWA2-FN3-FEATURE-TYPE           A          1                                
    2 PIWA2-FN3-SEGMENT-TYPE           A          1                                
    2 PIWA2-FN3-COINCIDENT-SEG-CTR     A          1                                
    2 FILLER-700                       A          4                                
    *  * *** LEFT SIDE OF THE STREET **** * ********** ******                         
    2 PIWA2-FN3-LEFT-SIDE-OF-STR       A        150                                
    R  2 PIWA2-FN3-LEFT-SIDE-OF-STR                                                   
    3 PIWA2-FN3-L-COM-DIST             A          3                                
    R  3 PIWA2-FN3-L-COM-DIST                                                         
    4 PIWA2-FN3-L-COM-DIST-BORO        A          1                                
    4 PIWA2-FN3-L-COM-DIST-NUM         A          2                                
    3 PIWA2-FN3-L-LOW-HOUSENUM         A         16 /* DISPLAY FORMAT              
    3 PIWA2-FN3-L-HI-HOUSENUM          A         16 /* DISPLAY FORMAT              
    3 FILLER-800                       A         32 /* FOR FUTURE USE              
    3 PIWA2-FN3-L-CD-ELIGIBLE          A          1                                
    3 PIWA2-FN3-L-ZIP                  A          5                                
    3 PIWA2-FN3-L-HEALTH-AREA          A          4                                
    3 PIWA2-FN3-L-POLICE-DIST          A          4                                
    R  3 PIWA2-FN3-L-POLICE-DIST                                                      
    4 PIWA2-FN3-L-POL-PAT-BORO-CMD     A          1                                
    4 PIWA2-FN3-L-POL-PRECINCT         A          3                                
    3 PIWA2-FN3-L-FIRE-DIV             A          2                                
    3 PIWA2-FN3-L-FIRE-BAT             A          2                                
    3 PIWA2-FN3-L-FIRE-CO              A          4                                
    R  3 PIWA2-FN3-L-FIRE-CO                                                          
    4 PIWA2-FN3-L-FIRE-CO-TYPE         A          1                                
    4 PIWA2-FN3-L-FIRE-CO-NUM          A          3                                
    3 PIWA2-FN3-L-SCHL-DIST            A          2                                
    3 PIWA2-FN3-L-DYN-BLK              A          3                                
    3 PIWA2-FN3-L-ED                   A          3                                
    3 PIWA2-FN3-L-AD                   A          2                                
    3 PIWA2-FN3-L-POLICE-PAT-BORO      A          2                                
    3 FILLER-880                       A          1                                
    3 PIWA2-FN3-L-BORO                 A          1                                
    3 PIWA2-FN3-L-1990-CENSUS-TRACT    A          6                                
    3 PIWA2-FN3-L-2010-CENSUS-TRACT    A          6                                
    3 PIWA2-FN3-L-2010-CENSUS-BLOCK    A          4                                
    3 PIWA2-FN3-L-2010-CENSUS-BLK-SUF  A          1 /* NA                          
    3 PIWA2-FN3-L-2000-CENS-TRACT      A          6                                
    3 PIWA2-FN3-L-2000-CENS-BLOCK      A          4                                
    3 PIWA2-FN3-L-2000-CENS-BLK-SUF    A          1 /* NA                          
    3 PIWA2-FN3-L-FILLER-890           A          7 /* V16.1 REPLACEMENT           
    3 PIWA2-FN3-L-NTA                  A          4 /*NEIGHBORHOOD                 
    *  *                                               /*TABULATION AREA              
    3 FILLER-900                       A          8                                
    *  * *** RIGHT SIDE OF THE STREET *** * ********** ***********                    
    2 PIWA2-FN3-RIGHT-SIDE-OF-STR      A        150                                
    R  2 PIWA2-FN3-RIGHT-SIDE-OF-STR                                                  
    3 PIWA2-FN3-R-COM-DIST             A          3                                
    R  3 PIWA2-FN3-R-COM-DIST                                                         
    4 PIWA2-FN3-R-COM-DIST-BORO        A          1                                
    4 PIWA2-FN3-R-COM-DIST-NUM         A          2                                
    3 PIWA2-FN3-R-LOW-HOUSENUM         A         16 /* DISPLAY FORMAT              
    3 PIWA2-FN3-R-HI-HOUSENUM          A         16 /* DISPLAY FORMAT              
    3 FILLER-1000                      A         32 /* FOR FUTURE USE              
    3 PIWA2-FN3-R-CD-ELIGIBLE          A          1                                
    3 PIWA2-FN3-R-ZIP                  A          5                                
    3 PIWA2-FN3-R-HEALTH-AREA          A          4                                
    3 PIWA2-FN3-R-POLICE-DIST          A          4                                
    R  3 PIWA2-FN3-R-POLICE-DIST                                                      
    4 PIWA2-FN3-R-POL-PAT-BORO-CMD     A          1                                
    4 PIWA2-FN3-R-POL-PRECINCT         A          3                                
    3 PIWA2-FN3-R-FIRE-DIV             A          2                                
    3 PIWA2-FN3-R-FIRE-BAT             A          2                                
    3 PIWA2-FN3-R-FIRE-CO              A          4                                
    R  3 PIWA2-FN3-R-FIRE-CO                                                          
    4 PIWA2-FN3-R-FIRE-CO-TYPE         A          1                                
    4 PIWA2-FN3-R-FIRE-CO-NUM          A          3                                
    3 PIWA2-FN3-R-SCHL-DIST            A          2                                
    3 PIWA2-FN3-R-DYN-BLK              A          3                                
    3 PIWA2-FN3-R-ED                   A          3                                
    3 PIWA2-FN3-R-AD                   A          2                                
    3 PIWA2-FN3-R-POLICE-PAT-BORO      A          2                                
    3 FILLER-1080                      A          1                                
    3 PIWA2-FN3-R-BORO                 A          1                                
    3 PIWA2-FN3-R-1990-CENSUS-TRACT    A          6                                
    3 PIWA2-FN3-R-2010-CENSUS-TRACT    A          6                                
    3 PIWA2-FN3-R-2010-CENSUS-BLOCK    A          4                                
    3 PIWA2-FN3-R-2010-CENSUS-BLK-SUF  A          1 /* NA                          
    3 PIWA2-FN3-R-2000-CENS-TRACT      A          6                                
    3 PIWA2-FN3-R-2000-CENS-BLOCK      A          4                                
    3 PIWA2-FN3-R-2000-CENS-BLK-SUF    A          1 /* NA                          
    3 PIWA2-FN3-R-FILLER-1090          A          7 /* V16.1 REPLACEMENT           
    3 PIWA2-FN3-R-NTA                  A          4 /*NEIGHBORHOOD                 
    *  *                                               /*TABULATION AREA              
    3 FILLER-1100                      A          8                                
    *  2 PIWA2-FN3-PSEUDO-FILLER          A       3550                                
    *  * ******************************** * ********** **********                     
    * ** *** END OF FUNCTION 3 LAYOUT**** * ********** **********                     
    R  1 GEOLP2                                                                       
    2 PIWA2-FN3-SEGAUX                 A        450 /* SAME AS FN3                 
    2 PIWA2-FN3-FILLER-SEGAUX          A          6 /* FOR FUTURE USE              
    2 PIWA2-FN3-SEGAUX-COUNTER         A          4                                
    2 PIWA2-FN3-SEGAUX-SEGMENTS        A          7 (1:70)                         
    *  2 PIWA2-FN3-SEGAUX-PSEUDO-FILLER   A       3050                                
    *  * ******************************** * ********** FOR AUX SEGS                   
    *  *  END OF FUNCTION 3 AUX LAYOUT    * ********** ********                       
    *  * -------------------------------- - ---------- --------                       
    *  *  START OF FUNCTION 3 EXTENDED      LAYOUT     ********                       
    R  1 GEOLP2                                                                       
    2 PIWA2-3X-ACCESS-KEY              A         21                                
    2 PIWA2-3X-DUP-KEY-FLAG            A          1 /* OR CONTI PARITY             
    2 PIWA2-3X-LOCATION-STATUS         A          1                                
    2 PIWA2-3X-COUNTY-BOUNDARY         A          1                                
    2 PIWA2-3X-PREFERRED-LGC1          A          2                                
    2 PIWA2-3X-PREFERRED-LGC2          A          2                                
    2 PIWA2-3X-PREFERRED-LGC3          A          2                                
    2 PIWA2-3X-NUM-X-ST-LOW-END        A          1                                
    2 PIWA2-3X-LOW-B5SC                A          6 (1:5) /* 30-BYTES              
    2 PIWA2-3X-NUM-X-ST-HI-END         A          1                                
    2 PIWA2-3X-HI-B5SC                 A          6 (1:5) /* 30-BYTES              
    2 PIWA2-3X-REVERSAL-FLAG           A          1                                
    2 PIWA2-3X-LION-KEY                A         10                                
    R  2 PIWA2-3X-LION-KEY                                                            
    3 PIWA2-3X-LION-BORO               A          1                                
    3 PIWA2-3X-LION-FACECODE           A          4                                
    3 PIWA2-3X-LION-SEQ                A          5                                
    2 PIWA2-3X-GENREC-FLAG             A          1                                
    2 PIWA2-3X-SEG-LENGTH              A          5                                
    2 PIWA2-3X-SEG-SLOP                A          3                                
    2 PIWA2-3X-SEG-ORIENT              A          1                                
    2 PIWA2-3X-MARBLE-RIKERS-FLAG      A          1                                
    2 PIWA2-3X-FROM-NODE               A          7                                
    2 PIWA2-3X-TO-NODE                 A          7                                
    2 PIWA2-3X-SANIT-SNOW-PRIORITY     A          1 /*SANITATION STRT              
    *  *                                               /*SNOW PRIORITY                
    2 FILLER-3X-600                    A          4                                
    2 PIWA2-3X-SEGMENT-ID              A          7                                
    2 PIWA2-3X-DOT-SLA                 A          1                                
    2 PIWA2-3X-CURVE-FLAG              A          1                                
    2 PIWA2-3X-DOG-LEG                 A          1                                
    2 PIWA2-3X-FEATURE-TYPE            A          1                                
    2 PIWA2-3X-SEGMENT-TYPE            A          1                                
    2 PIWA2-3X-COINCIDENT-SEG-CTR      A          1                                
    2 FILLER-3X-700                    A          4                                
    *  * *** LEFT SIDE OF THE STREET **** * *** ****** ******                         
    2 PIWA2-3X-LEFT-SIDE-OF-STR        A        150                                
    R  2 PIWA2-3X-LEFT-SIDE-OF-STR                                                    
    3 PIWA2-3X-L-COM-DIST              A          3                                
    R  3 PIWA2-3X-L-COM-DIST                                                          
    4 PIWA2-3X-L-COM-DIST-BORO         A          1                                
    4 PIWA2-3X-L-COM-DIST-NUM          A          2                                
    3 PIWA2-3X-L-LOW-HOUSENUM          A         16 /* DISPLAY FORMAT              
    3 PIWA2-3X-L-HI-HOUSENUM           A         16 /* DISPLAY FORMAT              
    3 FILLER-3X-800                    A         32 /* FOR FUTURE USE              
    3 PIWA2-3X-L-CD-ELIGIBLE           A          1                                
    3 PIWA2-3X-L-ZIP                   A          5                                
    3 PIWA2-3X-L-HEALTH-AREA           A          4                                
    3 PIWA2-3X-L-POLICE-DIST           A          4                                
    R  3 PIWA2-3X-L-POLICE-DIST                                                       
    4 PIWA2-3X-L-POL-PAT-BORO-CMD      A          1                                
    4 PIWA2-3X-L-POL-PRECINCT          A          3                                
    3 PIWA2-3X-L-FIRE-DIV              A          2                                
    3 PIWA2-3X-L-FIRE-BAT              A          2                                
    3 PIWA2-3X-L-FIRE-CO               A          4                                
    R  3 PIWA2-3X-L-FIRE-CO                                                           
    4 PIWA2-3X-L-FIRE-CO-TYPE          A          1                                
    4 PIWA2-3X-L-FIRE-CO-NUM           A          3                                
    3 PIWA2-3X-L-SCHL-DIST             A          2                                
    3 PIWA2-3X-L-DYN-BLK               A          3                                
    3 PIWA2-3X-L-ED                    A          3                                
    3 PIWA2-3X-L-AD                    A          2                                
    3 PIWA2-3X-L-POLICE-PAT-BORO       A          2                                
    3 FILLER-3X-880                    A          1                                
    3 PIWA2-3X-L-BORO                  A          1                                
    3 PIWA2-3X-L-1990-CENSUS-TRACT     A          6                                
    3 PIWA2-3X-L-2010-CENSUS-TRACT     A          6                                
    3 PIWA2-3X-L-2010-CENSUS-BLOCK     A          4                                
    3 PIWA2-3X-L-2010-CENSUS-BLK-SUF   A          1 /* NA                          
    3 PIWA2-3X-L-2000-CENS-TRACT       A          6                                
    3 PIWA2-3X-L-2000-CENS-BLOCK       A          4                                
    3 PIWA2-3X-L-2010-CENS-BLK-SUF     A          1 /* NA                          
    3 PIWA2-3X-L-FILLER-890            A          7 /* V16.1 REPLACEMENT           
    3 PIWA2-3X-L-NTA                   A          4 /*NEIGHBORHOOD                 
    *  *                                               /*TABULATION AREA              
    3 FILLER-3X-900                    A          8                                
    *  * *** RIGHT SIDE OF THE STREET *** * ********** ***********                    
    2 PIWA2-3X-RIGHT-SIDE-OF-STR       A        150                                
    R  2 PIWA2-3X-RIGHT-SIDE-OF-STR                                                   
    3 PIWA2-3X-R-COM-DIST              A          3                                
    R  3 PIWA2-3X-R-COM-DIST                                                          
    4 PIWA2-3X-R-COM-DIST-BORO         A          1                                
    4 PIWA2-3X-R-COM-DIST-NUM          A          2                                
    3 PIWA2-3X-R-LOW-HOUSENUM          A         16 /* DISPLAY FORMAT              
    3 PIWA2-3X-R-HI-HOUSENUM           A         16 /* DISPLAY FORMAT              
    3 FILLER-3X-1000                   A         32 /* FOR FUTURE USE              
    3 PIWA2-3X-R-CD-ELIGIBLE           A          1                                
    3 PIWA2-3X-R-ZIP                   A          5                                
    3 PIWA2-3X-R-HEALTH-AREA           A          4                                
    3 PIWA2-3X-R-POLICE-DIST           A          4                                
    R  3 PIWA2-3X-R-POLICE-DIST                                                       
    4 PIWA2-3X-R-POL-PAT-BORO-CMD      A          1                                
    4 PIWA2-3X-R-POL-PRECINCT          A          3                                
    3 PIWA2-3X-R-FIRE-DIV              A          2                                
    3 PIWA2-3X-R-FIRE-BAT              A          2                                
    3 PIWA2-3X-R-FIRE-CO               A          4                                
    R  3 PIWA2-3X-R-FIRE-CO                                                           
    4 PIWA2-3X-R-FIRE-CO-TYPE          A          1                                
    4 PIWA2-3X-R-FIRE-CO-NUM           A          3                                
    3 PIWA2-3X-R-SCHL-DIST             A          2                                
    3 PIWA2-3X-R-DYN-BLK               A          3                                
    3 PIWA2-3X-R-ED                    A          3                                
    3 PIWA2-3X-R-AD                    A          2                                
    3 PIWA2-3X-R-POLICE-PAT-BORO       A          2                                
    3 FILLER-3X-1080                   A          1                                
    3 PIWA2-3X-R-BORO                  A          1                                
    3 PIWA2-3X-R-1990-CENSUS-TRACT     A          6                                
    3 PIWA2-3X-R-2010-CENSUS-TRACT     A          6                                
    3 PIWA2-3X-R-2010-CENSUS-BLOCK     A          4                                
    3 PIWA2-3X-R-2010-CENSUS-BLK-SUF   A          1 /* NA                          
    3 PIWA2-3X-R-2000-CENS-TRACT       A          6                                
    3 PIWA2-3X-R-2000-CENS-BLOCK       A          4                                
    3 PIWA2-3X-R-2000-CENS-BLK-SUF     A          1 /* NA                          
    3 PIWA2-3X-R-FILLER-1090           A          7 /* V16.1 REPLACEMENT           
    3 PIWA2-3X-R-NTA                   A          4 /*NEIGHBORHOOD                 
    *  *                                               /*TABULATION AREA              
    3 FILLER-3X-1100                   A          8                                
    2 PIWA2-3X-LGCS                    A          8                                
    2 PIWA2-3X-LGCS-FROM               A          8                                
    2 PIWA2-3X-LGCS-TO                 A          8                                
    2 PIWA2-3X-L-HEALTH-CTR-DIST       A          2                                
    2 PIWA2-3X-R-HEALTH-CTR-DIST       A          2                                
    2 PIWA2-3X-FILL1                   A          1                                
    2 PIWA2-3X-TRAFFIC-DIR             A          1                                
    2 PIWA2-3X-ROADWAY-TYPE            A          2                                
    2 PIWA2-3X-PHYSICAL-ID             A          7                                
    2 PIWA2-3X-GENERIC-ID              A          7                                
    2 PIWA2-3X-INTP-ID                 A          7 /* INTERNAL USE                
    2 PIWA2-3X-INTF-ID                 A          7 /* INTERNAL USE                
    2 PIWA2-3X-STR-STATUS              A          1                                
    2 PIWA2-3X-STR-WIDTH               A          3                                
    2 PIWA2-3X-STR-WIDTH-IRREG         A          1                                
    2 PIWA2-3X-BIKE-LANE               A          1                                
    2 PIWA2-3X-FED-CLASS-CODE          A          2                                
    2 PIWA2-3X-ROW-TYPE                A          1                                
    2 PIWA2-3X-LGC-LIST                A         10                                
    2 PIWA2-3X-LEGACY-ID               A          7                                
    2 PIWA2-3X-L-NTA-NAME              A         75                                
    2 PIWA2-3X-R-NTA-NAME              A         75                                
    2 PIWA2-3X-FROM-XCOORD             A          7                                
    2 PIWA2-3X-FROM-YCOORD             A          7                                
    2 PIWA2-3X-TO-XCOORD               A          7                                
    2 PIWA2-3X-TO-YCOORD               A          7                                
    2 PIWA2-3X-FROM-LATITUDE           A          9                                
    2 PIWA2-3X-FROM-LONGITUDE          A         11                                
    2 PIWA2-3X-TO-LATITUDE             A          9                                
    2 PIWA2-3X-TO-LONGITUDE            A         11                                
    2 PIWA2-3X-L-BLOCKFACE-ID          A         10 /* V16.1 ADD                   
    2 PIWA2-3X-R-BLOCKFACE-ID          A         10 /* V16.1 ADD                   
    2 PIWA2-3X-NBR-TRAVEL-LANES        A          2 /* V16.1 ADD                   
    2 PIWA2-3X-NBR-PARK-LANES          A          2 /* V16.1 ADD                   
    2 PIWA2-3X-NBR-TOTAL-LANES         A          2 /* V16.1 ADD                   
    2 PIWA2-3X-BIKE-LANE-2             A          2 /* V16.4 ADDITION              
    2 PIWA2-3X-STR-WIDTH-MAX           A          3 /* V16.4 ADDITION              
    2 PIWA2-3X-BIKE-TRAFFIC-DIR        A          2 /* V17.1 ADDITION              
    2 FILLER-3X-FILL2                  A        213 /* V17.1 ALTERATION            
    *  2 FILLER-3X-FILL2                  A        215 /* V16.4 ALTERATION            
    *  2 FILLER-3X-FILL2                  A        220 /* V16.1 MOD                   
    *  2 PIWA2-3X-PSEUDO-FILLER           A       3000                                
    *  * ******************************** * ********** **********                     
    *  * END OF FCT 3 EXTENDED LAYOUT *** * ********** **********                     
    R  1 GEOLP2                                                                       
    2 PIWA2-3X-SEGAUX                  A       1000 /* SAME AS FN 3X               
    2 PIWA2-3X-FILLER-SEGAUX           A          6 /* FOR FUTURE USE              
    2 PIWA2-3X-SEGAUX-COUNTER          A          4                                
    2 PIWA2-3X-SEGAUX-SEGMENTS         A          7 (1:70)                         
    *  * ******************************** * ********** FOR AUX SEGS                   
    *  * END OF FCT 3 EXTENDED AUX LAYOUT * ********** *************                  
    *  * -------------------------------- - ---------- --------                       
    *  *  BEGINNING OF FUNCTION 3C LAYOUT * ********** ********                       
    R  1 GEOLP2                                                                       
    2 PIWA2-FN3C-ACCESS-KEY            A         21                                
    2 PIWA2-FN3C-DUP-KEY-FLAG          A          1 /* OR CONTI PARITY             
    2 PIWA2-FN3C-LOCATION-STATUS       A          1                                
    2 PIWA2-FN3C-COUNTY-BOUNDARY       A          1                                
    2 PIWA2-FN3C-PREFERRED-LGC1        A          2                                
    2 PIWA2-FN3C-PREFERRED-LGC2        A          2                                
    2 PIWA2-FN3C-PREFERRED-LGC3        A          2                                
    2 PIWA2-FN3C-NUM-X-ST-LOW-END      A          1                                
    2 PIWA2-FN3C-LOW-B5SC              A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN3C-NUM-X-ST-HI-END       A          1                                
    2 PIWA2-FN3C-HI-B5SC               A          6 (1:5) /* 30-BYTES              
    2 PIWA2-FN3C-REVERSAL-FLAG         A          1                                
    2 PIWA2-FN3C-LIONKEY               A         10                                
    R  2 PIWA2-FN3C-LIONKEY                                                           
    3 PIWA2-FN3C-LION-BORO             A          1                                
    3 PIWA2-FN3C-LION-FACECODE         A          4                                
    3 PIWA2-FN3C-LION-SEQ              A          5                                
    2 PIWA2-FN3C-GENREC-FLAG           A          1                                
    2 PIWA2-FN3C-SEG-LENGTH            A          5                                
    2 PIWA2-FN3C-SEG-AZIMUTH           A          3                                
    2 PIWA2-FN3C-SEG-ORIENT            A          1                                
    2 PIWA2-FN3C-MARBLE-RIKERS-FLAG    A          1                                
    2 PIWA2-FN3C-FROM-NODE             A          7                                
    2 PIWA2-FN3C-TO-NODE               A          7                                
    2 PIWA2-FN3C-SANIT-SNOW-PRIORITY   A          1 /*SANITATION STRT              
    *  *                                               /*SNOW PRIORITY                
    2 FILLER-1200                      A          4                                
    2 PIWA2-FN3C-SEGMENT-ID            A          7                                
    2 PIWA2-FN3C-DOT-SLA               A          1                                
    2 PIWA2-FN3C-SIDE-OF-STR           A          1                                
    2 PIWA2-FN3C-CURVE-FLAG            A          1                                
    2 PIWA2-FN3C-FEATURE-TYPE          A          1                                
    2 PIWA2-FN3C-SEGMENT-TYPE          A          1                                
    2 PIWA2-FN3C-COINCIDENT-SEG-CTR    A          1                                
    2 FILLER-1300                      A          4                                
    *  * *** FCT 3C BLOCKFACE INFORMATION * ********** ******************             
    2 PIWA2-FN3C-BLOCKFACE-INFO        A        150                                
    R  2 PIWA2-FN3C-BLOCKFACE-INFO                                                    
    3 PIWA2-FN3C-COM-DIST              A          3                                
    R  3 PIWA2-FN3C-COM-DIST                                                          
    4 PIWA2-FN3C-COMDIST-BORO          A          1                                
    4 PIWA2-FN3C-COMDIST-NUM           A          2                                
    3 PIWA2-FN3C-LOW-HOUSENUM          A         16 /* DISPLAY FORMAT              
    3 PIWA2-FN3C-HI-HOUSENUM           A         16 /* DISPLAY FORMAT              
    3 PIWA2-FN3C-LOW-HOUSENUM2         A         16 /* DISPLAY FORMAT              
    3 PIWA2-FN3C-HI-HOUSENUM2          A         16 /* DISPLAY FORMAT              
    3 PIWA2-FN3C-FILLER-1400           A          1 /* FOR GSS USE                 
    3 PIWA2-FN3C-ZIP                   A          5                                
    3 PIWA2-FN3C-HEALTH-AREA           A          4                                
    3 PIWA2-FN3C-POLICE-DIST           A          4                                
    R  3 PIWA2-FN3C-POLICE-DIST                                                       
    4 PIWA2-FN3C-POL-PAT-BORO-CMD      A          1                                
    4 PIWA2-FN3C-POL-PRECINCT          A          3                                
    3 PIWA2-FN3C-FIRE-DIV              A          2                                
    3 PIWA2-FN3C-FIRE-BAT              A          2                                
    3 PIWA2-FN3C-FIRE-CO               A          4                                
    R  3 PIWA2-FN3C-FIRE-CO                                                           
    4 PIWA2-FN3C-FIRE-CO-TYPE          A          1                                
    4 PIWA2-FN3C-FIRE-CO-NUM           A          3                                
    3 PIWA2-FN3C-SCHL-DIST             A          2                                
    3 PIWA2-FN3C-DYN-BLK               A          3                                
    3 PIWA2-FN3C-ED                    A          3                                
    3 PIWA2-FN3C-AD                    A          2                                
    3 PIWA2-FN3C-POLICE-PAT-BORO       A          2                                
    3 FILLER-1480                      A          1                                
    3 PIWA2-FN3C-BORO                  A          1                                
    3 PIWA2-FN3C-1900-CENSUS-TRACT     A          6                                
    3 PIWA2-FN3C-2010-CENSUS-TRACT     A          6                                
    3 PIWA2-FN3C-2010-CENSUS-BLOCK     A          4                                
    3 PIWA2-FN3C-2010-CENSUS-BLOCK-SUF A          1 /* NA                          
    3 PIWA2-FN3C-2000-CENS-TRACT       A          6                                
    3 PIWA2-FN3C-2000-CENS-BLOCK       A          4                                
    3 PIWA2-FN3C-2000-CENS-BLK-SUF     A          1 /* NA                          
    3 PIWA2-FN3C-FILLER-1490           A          7 /* V16.1 REPLACEMENT           
    3 PIWA2-FN3C-NTA                   A          4 /*NEIGHBORHOOD                 
    *  *                                               /*TABULATION AREA              
    *  3 FILLER-1500                      A          8                                
    *  * PIWA2-FN3C-PSEUDO-FILLER         A       3700 /*LEVEL 2 IN DEF               
    *  * ******************************** * ********** ******                         
    *  *  END OF FCT 3C LAYOUT ********** * ********** ******                         
    R  1 GEOLP2                                                                       
    2 PIWA2-FN3C-SEGAUX                A        300 /*SAME AS FN3C                 
    2 PIWA2-FN3C-SEGAUX-FILL           A          6                                
    2 PIWA2-FN3C-SEGAUX-CTR            A          4                                
    2 PIWA2-FN3C-SEGAUX-SEGS           A          7 (1:70)                         
    *  2 PIWA2-FN3C-AUX-PSEUDO-FILLER     A       3200                                
    * ** ******************************** * ********** FN3C AUX SEGS                  
    *  *  END OF FCT 3C AUX LAYOUT ****** * ********** *******                        
    * ** ******************************** * ********** *************                  
    * ** ******************************** * ********** *************                  
    *  *  START OF FUNCTION 3CX LAYOUT    * ********** ********                       
    R  1 GEOLP2                                                                       
    2 PIWA2-3CX-ACCESS-KEY             A         21                                
    2 PIWA2-3CX-DUP-KEY-FLAG           A          1 /* OR CONTI PARITY             
    2 PIWA2-3CX-LOCATION-STATUS        A          1                                
    2 PIWA2-3CX-COUNTY-BOUNDARY        A          1                                
    2 PIWA2-3CX-PREFERRED-LGC1         A          2                                
    2 PIWA2-3CX-PREFERRED-LGC2         A          2                                
    2 PIWA2-3CX-PREFERRED-LGC3         A          2                                
    2 PIWA2-3CX-NUM-X-ST-LOW-END       A          1                                
    2 PIWA2-3CX-LOW-B5SC               A          6 (1:5) /* 30-BYTES              
    2 PIWA2-3CX-NUM-X-ST-HI-END        A          1                                
    2 PIWA2-3CX-HI-B5SC                A          6 (1:5) /* 30-BYTES              
    2 PIWA2-3CX-REVERSAL-FLAG          A          1                                
    2 PIWA2-3CX-LIONKEY                A         10                                
    R  2 PIWA2-3CX-LIONKEY                                                            
    3 PIWA2-3CX-LION-BORO              A          1                                
    3 PIWA2-3CX-LION-FACECODE          A          4                                
    3 PIWA2-3CX-LION-SEQ               A          5                                
    2 PIWA2-3CX-GENREC-FLAG            A          1                                
    2 PIWA2-3CX-SEG-LENGTH             A          5                                
    2 PIWA2-3CX-SEG-SLOPE              A          3                                
    2 PIWA2-3CX-SEG-ORIENT             A          1                                
    2 PIWA2-3CX-MARBLE-RIKERS-FLAG     A          1                                
    2 PIWA2-3CX-FROM-NODE              A          7                                
    2 PIWA2-3CX-TO-NODE                A          7                                
    2 PIWA2-3CX-SANIT-SNOW-PRIORITY    A          1 /*SANITATION STRT              
    *  *                                               /*SNOW PRIORITY                
    2 FILLER-3CX-1200                  A          4                                
    2 PIWA2-3CX-SEGMENT-ID             A          7                                
    2 PIWA2-3CX-DOT-SLA                A          1                                
    2 PIWA2-3CX-SIDE-OF-STR            A          1                                
    2 PIWA2-3CX-CURVE-FLAG             A          1                                
    2 PIWA2-3CX-FEATURE-TYPE           A          1                                
    2 PIWA2-3CX-SEGMENT-TYPE           A          1                                
    2 PIWA2-3CX-COINCIDENT-SEG-CTR     A          1                                
    2 FILLER-3CX-1300                  A          4                                
    *  * ***FCT 3C BLOCKFACE INFORMATION  * ********** ******************             
    2 PIWA2-3CX-BLOCKFACE-INFO         A        150                                
    R  2 PIWA2-3CX-BLOCKFACE-INFO                                                     
    3 PIWA2-3CX-COM-DIST               A          3                                
    R  3 PIWA2-3CX-COM-DIST                                                           
    4 PIWA2-3CX-COMDIST-BORO           A          1                                
    4 PIWA2-3CX-COMDIST-NUM            A          2                                
    3 PIWA2-3CX-LOW-HOUSENUM           A         16 /* DISPLAY FORMAT              
    3 PIWA2-3CX-HI-HOUSENUM            A         16 /* DISPLAY FORMAT              
    3 PIWA2-3CX-LOW-HOUSENUM2          A         16 /* DISPLAY FORMAT              
    3 PIWA2-3CX-HI-HOUSENUM2           A         16 /* DISPLAY FORMAT              
    3 FIWA2-3CX-CD-ELIGIBLE            A          1                                
    3 PIWA2-3CX-ZIP                    A          5                                
    3 PIWA2-3CX-HEALTH-AREA            A          4                                
    3 PIWA2-3CX-POLICE-DIST            A          4                                
    R  3 PIWA2-3CX-POLICE-DIST                                                        
    4 PIWA2-3CX-POL-PAT-BORO-CMD       A          1                                
    4 PIWA2-3CX-POL-PRECINCT           A          3                                
    3 PIWA2-3CX-FIRE-DIV               A          2                                
    3 PIWA2-3CX-FIRE-BAT               A          2                                
    3 PIWA2-3CX-FIRE-CO                A          4                                
    R  3 PIWA2-3CX-FIRE-CO                                                            
    4 PIWA2-3CX-FIRE-CO-TYPE           A          1                                
    4 PIWA2-3CX-FIRE-CO-NUM            A          3                                
    3 PIWA2-3CX-SCHL-DIST              A          2                                
    3 PIWA2-3CX-DYN-BLK                A          3                                
    3 PIWA2-3CX-ED                     A          3                                
    3 PIWA2-3CX-AD                     A          2                                
    3 PIWA2-3CX-POLICE-PAT-BORO        A          2                                
    3 FILLER-3CX-1480                  A          1                                
    3 PIWA2-3CX-BORO                   A          1                                
    3 PIWA2-3CX-1990-CENSUS-TRACT      A          6                                
    3 PIWA2-3CX-2010-CENSUS-TRACT      A          6                                
    3 PIWA2-3CX-2010-CENSUS-BLOCK      A          4                                
    3 PIWA2-3CX-2010-CENSUS-BLOCK-SUF  A          1 /* NA                          
    3 PIWA2-3CX-2000-CENS-TRACT        A          6                                
    3 PIWA2-3CX-2000-CENS-BLOCK        A          4                                
    3 PIWA2-3CX-2000-CENS-BLK-SUF      A          1 /* NA                          
    3 PIWA2-3CX-FILLER-1490            A          7 /* V16.1 REPLACEMENT           
    3 PIWA2-3CX-NTA                    A          4 /*NEIGHBORHOOD                 
    *  *                                               /*TABULATION AREA              
    3 FILLER-1500                      A          8                                
    2 PIWA2-3CX-LGCS                   A          8                                
    2 PIWA2-3CX-LGCS-FROM              A          8                                
    2 PIWA2-3CX-LGCS-TO                A          8                                
    2 PIWA2-3CX-L-HEALTH-CTR-DIST      A          2                                
    2 PIWA2-3CX-R-HEALTH-CTR-DIST      A          2                                
    2 PIWA2-3CX-FILL1                  A          1                                
    2 PIWA2-3CX-TRAFFIC-DIR            A          1                                
    2 PIWA2-3CX-ROADWAY-TYPE           A          2                                
    2 PIWA2-3CX-PHYSICAL-ID            A          7                                
    2 PIWA2-3CX-GENERIC-ID             A          7                                
    2 PIWA2-3CX-INTP-ID                A          7 /* INTERNAL USE                
    2 PIWA2-3CX-INTF-ID                A          7 /* INTERNAL USE                
    2 PIWA2-3CX-STREET-STATUS          A          1                                
    2 PIWA2-3CX-STREET-WIDTH           A          3                                
    2 PIWA2-3CX-STREET-WIDTH-IRREG     A          1                                
    2 PIWA2-3CX-BIKE-LANE              A          1                                
    2 PIWA2-3CX-FED-CLASS-CODE         A          2                                
    2 PIWA2-3CX-ROW-TYPE               A          1                                
    2 PIWA2-3CX-LGC-LIST               A         10                                
    2 PIWA2-3CX-LEGACY-ID              A          7                                
    2 PIWA2-3CX-NTA-NAME               A         75                                
    2 PIWA2-3CX-FROM-XCOORD            A          7                                
    2 PIWA2-3CX-FROM-YCOORD            A          7                                
    2 PIWA2-3CX-TO-XCOORD              A          7                                
    2 PIWA2-3CX-TO-YCOORD              A          7                                
    2 PIWA2-3CX-FROM-LATITUDE          A          9                                
    2 PIWA2-3CX-FROM-LONGITUDE         A         11                                
    2 PIWA2-3CX-TO-LATITUDE            A          9                                
    2 PIWA2-3CX-TO-LONGITUDE           A         11                                
    2 PIWA2-3CX-BLOCKFACE-ID           A         10 /* V16.1 ADD                   
    2 PIWA2-3CX-NBR-TRAVEL-LANES       A          2 /* V16.1 ADD                   
    2 PIWA2-3CX-NBR-PARK-LANES         A          2 /* V16.1 ADD                   
    2 PIWA2-3CX-NBR-TOTAL-LANES        A          2 /* V16.1 ADD                   
    2 PIWA2-3CX-BIKE-LANE-2            A          2 /* V16.4 ADDITION              
    2 PIWA2-3CX-STR-WIDTH-MAX          A          3 /* V16.4 ADDITION              
    2 PIWA2-3CX-BIKE-TRAFFIC-DIR       A          2 /* V17.1 ADDITION              
    2 FILLER-3CX-FILL1560              A        298 /* V17.1 ALTERATION            
    *  2 FILLER-3CX-FILL1560              A        300 /* V16.4 ALTERATION            
    *  2 FILLER-3CX-FILL1560              A        305 /* V16.1 MOD                   
    *  2 PIWA2-3CX-PSEUDO-FILER           A       3150                                
    *  * ******************************** * ********** ******                         
    *  *  END OF FCT 3CX LAYOUT ********* * ********** ******                         
    R  1 GEOLP2                                                                       
    2 PIWA2-3CX-SEGAUX                 A        850 /* SAME AS FN 3CX              
    2 PIWA2-3CX-SEGAUX-FILL            A          6                                
    2 PIWA2-3CX-SEGAUX-CTR             A          4                                
    2 PIWA2-3CX-SEGAUX-SEGS            A          7 (1:70)                         
    *  2 PIWA2-3CX-AUX-PSEUDO-FILLER      A       2650                                
    * ** ******************************** * ********** FN3C AUX SEGS                  
    *  *  END OF FCT 3CX AUX LAYOUT*****  * ********** *******                        
    * ** ******************************** * ********** *************                  
    * ** ******************************** * ********** *************                  
    *  *  BEGINNING OF FUNCTION 5 LAYOUT  *       **** *******                        
    R  1 GEOLP2                                                                       
    2 PIWA2-FN5-ADDR-MATCHING-KEY      A         33                                
    2 FILLER-1600                      A        267                                
    *  *  END OF FUNCTION 5 LAYOUT        *       **** *******                        
    *  - -------------------------------- -       ---- -------------------------------


## <span id="appendix14.25"><center>GEOLP21A COPY File</center></span>  

    1 GEOLP21A                                      /*FCT 1A,BL USE SAME WA2 LAY
    *  * THE FIELD P2NAT1A IS USED AS A      PARAMETER TO CALL GEOSUPPORT              
    2 P2NAT1A                          A         21                                 
    R  2 P2NAT1A                                                                       
    3 PIWA2-1A-ACCESS-KEY              A         21                                 
    2 PIWA2-1A-CONT-PARITY             A          1 /* OR DUP ADDR IND              
    2 PIWA2-1A-LOW-HOUSENUM            A         11 /* SORT FORMAT                  
    2 PIWA2-1A-BBL                     A         10                                 
    R  2 PIWA2-1A-BBL                                                                  
    3 PIWA2-1A-BBL-BORO                A          1                                 
    3 PIWA2-1A-BLOCK                   A          5                                 
    3 PIWA2-1A-LOT                     A          4                                 
    2 PIWA2-1A-LOT-VERSION             A          1 /* NYI */                       
    2 PIWA2-1A-SCC                     A          1                                 
    2 FILLER-100                       A          1                                 
    2 PIWA2-1A-GENERAL-LOT-INFO                                                     
    3 PIWA2-1A-RPAD-BLDG-CLASS         A          2                                 
    3 PIWA2-1A-CORNER-CODE             A          2                                 
    3 PIWA2-1A-NUM-OF-STRUCTURES       A          4                                 
    3 PIWA2-1A-NUM-OF-BLOCKFACES       A          2                                 
    3 PIWA2-1A-INTERIOR-FLAG           A          1                                 
    3 PIWA2-1A-VACANT-FLAG             A          1                                 
    3 PIWA2-1A-IRREG-LOT-FLAG          A          1                                 
    2 PIWA2-1A-MARBLE-RIKERS-FLAG      A          1                                 
    2 PIWA2-1A-ADDR-LIST-OVFLOW-FLAG   A          1                                 
    2 PIWA2-1A-STROLL-KEY              A         19                                 
    R  2 PIWA2-1A-STROLL-KEY                                                           
    3 PIWA2-1A-STROLL-BORO             A          1                                 
    3 PIWA2-1A-STROLL-5SC              A          5                                 
    3 PIWA2-1A-STROLL-SIDE-OF-STR      A          1 /* L OR R                       
    3 PIWA2-1A-STROLL-HI-HOUSENUM      A         11 /* SORT FORMAT                  
    3 FILLER-200                       A          1                                 
    2 FILLER-300                       A          1 /* FOR GSS USE                  
    2 PIWA2-1A-BIN                     A          7                                 
    2 PIWA2-1A-CONDO-FLAG              A          1                                 
    2 FILLER-400                       A          1                                 
    2 PIWA2-1A-RPAD-CONDO-ID-NUM       A          4                                 
    2 PIWA2-1A-CONDO-UNIT-ID-NUM       A          7                                 
    2 PIWA2-1A-CONDO-BILL-BBL          A         10                                 
    2 PIWA2-1A-CONDO-BILL-BBL-VER      A          1                                 
    2 PIWA2-1A-CONDO-BILL-BBL-SCC      A          1                                 
    2 PIWA2-1A-CONDO-LOW-BBL           A         10                                 
    2 PIWA2-1A-CONDO-LOW-BBL-VER       A          1                                 
    2 PIWA2-1A-CONDO-HIGH-BBL          A         10                                 
    2 PIWA2-1A-CONDO-HIGH-BBL-VER      A          1                                 
    2 FILLER-500                       A         15                                 
    2 PIWA1-1A-COOP-NUM                A          4                                 
    2 PIWA2-1A-SANBORN                 A          8                                 
    R  2 PIWA2-1A-SANBORN                                                              
    3 PIWA2-1A-SANBORN-BORO            A          1                                 
    3 PIWA2-1A-SANBORN-VOL             A          3                                 
    3 PIWA2-1A-SANBORN-PAGE            A          4                                 
    2 PIWA2-1A-COMMERC-DIST            A          5                                 
    2 PIWA2-1A-DOF-MAP-BORO            A          1                                 
    2 PIWA2-1A-DOF-MAP-SECVOL          A          4                                 
    2 PIWA2-1A-DOF-MAP-PAGE            A          4                                 
    2 FILLER-1A-RESERVED-DCP           A          3                                 
    2 PIWA2-1A-LATITUDE                A          9                                 
    2 PIWA2-1A-LONGITUDE               A         11                                 
    2 PIWA2-1A-X-COORD                 A          7                                 
    2 PIWA2-1A-Y-COORD                 A          7                                 
    2 PIWA2-1A-BID                     A          6                                 
    2 PIWA2-1A-TPAD-BIN-ST             A          1 /* CURRENT STATUS */            
    2 PIWA2-1A-TPAD-NEW-BIN            A          7 /* NEW BIN */                   
    2 PIWA2-1A-TPAD-NEW-BIN-ST         A          1 /* NEW BIN STATUS */            
    2 PIWA2-1A-TPAD-CONFLICT           A          1 /* CONFLICT FLAG */             
    2 FILLER-650                       A          9                                 
    2 FILLER-700                       A          8 /* FOR GSS USE                  
    2 PIWA2-1A-NUM-OF-ADDR             A          4                                 
    2 PIWA2-1A-LIST-OF-ADDR                         (1:21)                          
    3 PIWA2-1A-LIST-LOW-HOUSENUM       A         16 /* DISPLAY FORMAT               
    3 PIWA2-1A-LIST-HI-HOUSENUM        A         16 /* DISPLAY FORMAT               
    3 PIWA2-1A-LIST-BORO               A          1                                 
    3 PIWA2-1A-LIST-5SC                A          5                                 
    3 PIWA2-1A-LIST-LGC                A          2                                 
    3 PIWA2-1A-LIST-BIN                A          7                                 
    3 PIWA2-1A-LIST-SIDE-OF-STR        A          1 /* L OR R                       
    3 PIWA2-1A-LIST-ADDR-TYPE          A          1 /* P=NAP, B=NAB,          MAL   
    *  *                                               /* BLANK=NORMAL                 
    3 PIWA2-1A-LIST-TPAD-STATUS        A          1 /* 0 - 9                        
    3 FILLER-800                       A          3                                 


## <span id="appendix14.26"><center>GEOLP2AL COPY File</center></span>  

    1 GEOLP2AL                                      /* FCT 1A, BL LONG WA2    WA2   
    *  * THE FIELD P2NAT1AL IS USED AS A     PARAMETER TO CALL GEOSUPPORT              
    2 P2NAT1AL                         A         21                                 
    R  2 P2NAT1AL                                                                      
    3 PIWA2-1AL-ACCESS-KEY             A         21                                 
    *  * BEGINNING OF FUNCTION 1AL LAYOUT * ********** *******************             
    2 PIWA2-1AL-CONT-PARITY            A          1 /* OR DUP ADDR IND              
    2 PIWA2-1AL-LOW-HOUSENUM           A         11 /* SORT FORMAT                  
    2 PIWA2-1AL-BBL                    A         10                                 
    R  2 PIWA2-1AL-BBL                                                                 
    3 PIWA2-1AL-BBL-BORO               A          1                                 
    3 PIWA2-1AL-BLOCK                  A          5                                 
    3 PIWA2-1AL-LOT                    A          4                                 
    2 FILLER-1AL-LOT-VERSION           A          1 /* NA                           
    2 PIWA2-1AL-SCC                    A          1                                 
    2 FILLER-100                       A          1                                 
    2 PIWA2-1AL-GENERAL-LOT-INFO                                                    
    3 PIWA2-1AL-RPAD-BLDG-CLASS        A          2                                 
    3 PIWA2-1AL-CORNER-CODE            A          2                                 
    3 PIWA2-1AL-NUM-OF-STRUCTURES      A          4                                 
    3 PIWA2-1AL-NUM-OF-BLOCKFACES      A          2                                 
    3 PIWA2-1AL-INTERIOR-FLAG          A          1                                 
    3 PIWA2-1AL-VACANT-FLAG            A          1                                 
    3 PIWA2-1AL-IRREG-LOT-FLAG         A          1                                 
    2 PIWA2-1AL-MARBLE-RIKERS-FLAG     A          1                                 
    2 PIWA2-1AL-ADDR-LIST-OVFLOW-FLAG  A          1                                 
    2 PIWA2-1AL-STROLL-KEY             A         19                                 
    R  2 PIWA2-1AL-STROLL-KEY                                                          
    3 PIWA2-1AL-STROLL-KEY-BORO        A          1                                 
    3 PIWA2-1AL-STROLL-KEY-5SC         A          5                                 
    3 PIWA2-1AL-STROLL-SIDE-OF-STR     A          1 /* L OR R                       
    3 PIWA2-1AL-STROLL-HI-HOUSENUM     A         11 /* SORT FORMAT                  
    3 FILLER-200                       A          1                                 
    2 FILLER-300                       A          1 /* FOR GSS USE                  
    2 PIWA2-1AL-BIN                    A          7                                 
    2 PIWA2-1AL-CONDO-FLAG             A          1                                 
    2 FILLER-400                       A          1                                 
    2 PIWA2-1AL-RPAD-CONDO-ID-NUM      A          4                                 
    2 PIWA2-1AL-CONDO-UNIT-ID-NUM      A          7                                 
    2 PIWA2-1AL-CONDO-BILL-BBL         A         10                                 
    2 PIWA2-1AL-CONDO-BILL-BBL-VER     A          1                                 
    2 PIWA2-1AL-CONDO-BILL-BBL-SCC     A          1                                 
    2 PIWA2-1AL-CONDO-LOW-BBL          A         10                                 
    2 PIWA2-1AL-CONDO-LOW-BBL-VER      A          1                                 
    2 PIWA2-1AL-CONDO-HIGH-BBL         A         10                                 
    2 PIWA2-1AL-CONDO-HIGH-BBL-VER     A          1                                 
    2 FILLER-500                       A         15                                 
    2 PIWA2-1AL-COOP-NUM               A          4                                 
    2 PIWA2-1AL-SANBORN                A          8                                 
    R  2 PIWA2-1AL-SANBORN                                                             
    3 PIWA2-1AL-SANBORN-BORO           A          1                                 
    3 PIWA2-1AL-SANBORN-VOL            A          3                                 
    3 PIWA2-1AL-SANBORN-PAGE           A          4                                 
    2 PIWA2-1AL-COMMERC-DIST           A          5                                 
    2 PIWA2-1AL-DOF-MAP-BORO           A          1                                 
    2 PIWA2-1AL-DOF-MAP-SECVOL         A          4                                 
    2 PIWA2-1AL-DOF-MAP-PAGE           A          4                                 
    2 FILLER-600                       A          3                                 
    2 PIWA2-1AL-LATITUDE               A          9                                 
    2 PIWA2-1AL-LONGITUDE              A         11                                 
    2 PIWA2-1AL-X-COORD                A          7                                 
    2 PIWA2-1AL-Y-COORD                A          7                                 
    2 PIWA2-1AL-BID                    A          6                                 
    2 PIWA2-1AL-TPAD-BIN-ST            A          1 /*CURRENT STATUS                
    2 PIWA2-1AL-TPAD-NEW-BIN           A          7 /*NEW BIN                       
    2 PIWA2-1AL-TPAD-NEW-BIN-ST        A          1 /*NEW BIN STATUS                
    2 PIWA2-1AL-TPAD-CONFLICT          A          1 /*CONFLICT FLAG                 
    2 FILLER-650                       A          9                                 
    2 FILLER-700                       A          8 /* LGC GSS USE                  
    2 PIWA2-1AL-NUM-OF-BINS            A          4                                 
    2 PIWA2-1AL-TPAD-BINLIST           A      17500                                 
    R  2 PIWA2-1AL-TPAD-BINLIST                        /* REDEF. BEGIN : PIWA2-1AL-TPAD
    3 PIWA2-1AL-TPAD-BINS                           (1:2187)                        
    4 PIWA2-1AL-TPAD-BIN               A          7                                 
    4 PIWA2-1AL-TPAD-BINS-STAT         A          1                                 
    3 PIWA2-1AL-TPAD-FILL              A          4                                 
    R  2 PIWA2-1AL-TPAD-BINLIST                                                        
    3 PIWA2-1AL-BINS                   A          7 (1:2500)                        
    * ** END OF FUNCTION 1AL LAYOUT ***** * ********** **********************          
    * -- -------------------------------- - ---------- --------------------------      
    * ** BEGINNING OF FCT 1/1E EXTENDED * * ********** **********************          
    R  1 GEOLP2AL                                                                      
    2 PIWA2-1EX-ACCESS-KEY             A         21                                 
    2 PIWA2-1EX-CONT-PARITY            A          1 /* (OR DUP ADDR IND)            
    2 PIWA2-1EX-LOW-HOUSENUM           A         11 /* SORT FORMAT                  
    2 PIWA2-1EX-HI-HOUSENUM            A         11 /* SORT FORMAT                  
    2 PIWA2-1EX-PREFERRED-LGC          A          2                                 
    2 PIWA2-1EX-NUM-X-ST-LOW-END       A          1                                 
    2 PIWA2-1EX-LOW-B5SC               A          6 (1:5) /* 30-BYTES               
    2 PIWA2-1EX-NUM-X-ST-HI-END        A          1                                 
    2 PIWA2-1EX-HI-B5SC                A          6 (1:5) /* 30-BYTES               
    2 PIWA2-1EX-LIONKEY                A         10                                 
    R  2 PIWA2-1EX-LIONKEY                                                             
    3 PIWA2-1EX-LION-BORO              A          1                                 
    3 PIWA2-1EX-LION-FACECODE          A          4                                 
    3 PIWA2-1EX-LION-SEQ               A          5                                 
    2 PIWA2-1EX-SPECIAL-ADDR-FLAG      A          1                                 
    2 PIWA2-1EX-SIDE-OF-STR            A          1                                 
    2 PIWA2-1EX-SEG-LEN                A          5                                 
    2 PIWA2-1EX-X-COORD                A          7                                 
    2 PIWA2-1EX-Y-COORD                A          7                                 
    2 FILLER-1EX-100                   A          7 /* FOR ZCOORD                   
    2 FILLER-1EX-200                   A          1 /* FOR GSS USE                  
    2 PIWA2-1EX-MARBLE-RIKERS-FLAG     A          1                                 
    2 PIWA2-1EX-DOT-SLA                A          1                                 
    2 PIWA2-1EX-COM-DIST               A          3                                 
    R  2 PIWA2-1EX-COM-DIST                                                            
    3 PIWA2-1EX-COM-DIST-BORO          A          1                                 
    3 PIWA2-1EX-COM-DIST-NUM           A          2                                 
    2 PIWA2-1EX-ZIP                    A          5                                 
    *  *                                  *       **** *****                           
    *  *  THE FN1E FIELDS ARE VALID ONLY  *       **** *****                           
    *  *  FOR FUNCTION 1E, NOT FUNC 1.    *       **** *****                           
    2 PIWA2-1EX-ELECT-DIST             A          3                                 
    2 PIWA2-1EX-ASSEM-DIST             A          2                                 
    2 PIWA2-1EX-SPLIT-ED-FLAG          A          1                                 
    2 PIWA2-1EX-CONG-DIST              A          2                                 
    2 PIWA2-1EX-SENATE-DIST            A          2                                 
    2 PIWA2-1EX-COURT-DIST             A          2                                 
    2 PIWA2-1EX-COUNCIL-DIST           A          2                                 
    *  *                                  *       **** *****                           
    2 PIWA2-1EX-HEALTH-CENTER-DIST     A          2                                 
    2 PIWA2-1EX-HEALTH-AREA            A          4                                 
    2 PIWA2-1EX-SANI-DIST              A          3                                 
    R  2 PIWA2-1EX-SANI-DIST                                                           
    3 PIWA2-1EX-SANI-DIST-BORO         A          1                                 
    3 PIWA2-1EX-SANI-DIST-NUM          A          2                                 
    2 PIWA2-1EX-SANI-SUBSEC            A          2                                 
    2 PIWA2-1EX-SANI-REG               A          5                                 
    2 PIWA2-1EX-SANI-REC               A          3                                 
    2 PIWA2-1EX-POLICE-DIST            A          4                                 
    R  2 PIWA2-1EX-POLICE-DIST                                                         
    3 PIWA2-1EX-POL-PAT-BORO-CMD       A          1                                 
    3 PIWA2-1EX-POL-PRECINCT           A          3                                 
    2 PIWA2-1EX-FIRE-DIV               A          2                                 
    2 PIWA2-1EX-FIRE-BAT               A          2                                 
    2 PIWA2-1EX-FIRE-CO                A          4                                 
    R  2 PIWA2-1EX-FIRE-CO                                                             
    3 PIWA2-1EX-FIRE-CO-TYPE           A          1                                 
    3 PIWA2-1EX-FIRE-CO-NUM            A          3                                 
    2 PIWA2-1EX-SCHL-DIST-SPLIT-FLAG   A          1                                 
    2 PIWA2-1EX-SCHL-DIST              A          2                                 
    2 PIWA2-1EX-DYN-BLK                A          3                                 
    2 PIWA2-1EX-POLICE-PAT-BORO        A          2                                 
    2 PIWA2-1EX-FEATURE-TYPE           A          1                                 
    2 PIWA2-1EX-SEGMENT-TYPE           A          1                                 
    2 PIWA2-1EX-ALX                    A          1                                 
    2 PIWA2-1EX-COINCIDENT-SEG-CTR     A          1                                 
    2 FILLER-290                       A          3                                 
    2 PIWA2-1EX-1990-CENSUS-TRACT      A          6                                 
    2 PIWA2-1EX-2010-CENSUS-TRACT      A          6                                 
    2 PIWA2-1EX-2010-CENSUS-BLOCK      A          4                                 
    2 PIWA2-1EX-2010-CENSUS-BLOCK-SUF  A          1                                 
    2 PIWA2-1EX-2000-CENSUS-TRACT      A          6 /* NA                           
    2 PIWA2-1EX-2000-CENSUS-BLOCK      A          4 /* NA                           
    2 PIWA2-1EX-2000-CENSUS-BLOCK-SUF  A          1 /* NA                           
    2 PIWA2-1EX-NTA                    A          4 /*NEIGHBORHOOD                  
    *  *                                               /*TABULATION AREA*/             
    2 PIWA2-1EX-SANIT-SNOW-PRIORITY    A          1 /*SANITATION STRT               
    *  *                                               /*SNOW PRIORITY                 
    2 PIWA2-1EX-SANIT-ORGANICS         A          5                                 
    2 PIWA2-1EX-SANIT-BULK-PICK-UP     A          5 /* V16.4 ADDITION               
    *  2 PIWA2-1EX-SANIT-RESERVED         A          5                                 
    2 PIWA2-1EX-HURRICANE-ZONE         A          2 /*OEM HURRICANE EVAC ZONE       
    2 FILLER-1EX-300                   A         11                                 
    2 PIWA2-1EX-UHNS                   A         11                                 
    2 PIWA2-1EX-REAL-B7SC              A          8                                 
    2 PIWA2-1EX-SEGMENT-ID             A          7                                 
    2 PIWA2-1EX-CURVE-FLAG             A          1                                 
    2 PIWA2-1EX-LGC                    A          8                                 
    2 PIWA2-1EX-BOE-PTR                A          1                                 
    2 PIWA2-1EX-AZIMUTH                A          3                                 
    2 PIWA2-1EX-ORIENT                 A          1                                 
    2 PIWA2-1EX-X-LOW                  A          7                                 
    2 PIWA2-1EX-Y-LOW                  A          7                                 
    2 PIWA2-1EX-Z-LOW                  A          7                                 
    2 PIWA2-1EX-X-HI                   A          7                                 
    2 PIWA2-1EX-Y-HI                   A          7                                 
    2 PIWA2-1EX-Z-HI                   A          7                                 
    2 PIWA2-1EX-X-CC                   A          7                                 
    2 PIWA2-1EX-Y-CC                   A          7                                 
    2 PIWA2-1EX-Z-CC                   A          7                                 
    2 PIWA2-1EX-RADIUS                 A          7                                 
    2 PIWA2-1EX-SECANT                 A          1                                 
    2 PIWA2-1EX-ANGLE-FROM             A          5                                 
    2 PIWA2-1EX-ANGLE-TO               A          5                                 
    2 PIWA2-1EX-NODE-FROM              A          7                                 
    2 PIWA2-1EX-NODE-TO                A          7                                 
    2 PIWA2-1EX-VANITY-LION            A         10                                 
    2 PIWA2-1EX-SOS                    A          1                                 
    2 PIWA2-1EX-SPLIT-LOHSN            A         11                                 
    2 PIWA2-1EX-TD                     A          1                                 
    2 PIWA2-1EX-TR                     A         10                                 
    2 PIWA2-1EX-CURVE-FRACTION         A          3                                 
    2 PIWA2-1EX-ROADWAY-TYPE           A          2                                 
    2 PIWA2-1EX-PHYSICAL-ID            A          7                                 
    2 PIWA2-1EX-GENERIC-ID             A          7                                 
    2 PIWA2-1EX-INTP-ID                A          7                                 
    2 PIWA2-1EX-INTF-ID                A          7                                 
    2 PIWA2-1EX-BIKE-LANE-2            A          2 /* V16.4 ADDITION               
    2 PIWA2-1EX-BIKE-TRAFFIC-DIR       A          2 /* V17.1 ADDITION               
    2 PIWA2-1EX-FILL450                A          3 /* V17.1 ALTERATION             
    *  2 PIWA2-1EX-FILL450                A          5 /* V16.4 ALTERATION             
    *  2 PIWA2-1EX-FILL450                A          7 /* V16.1 REPLACEMENT            
    2 PIWA2-1EX-STREET-STATUS          A          1                                 
    2 PIWA2-1EX-STREET-WIDTH           A          3                                 
    2 PIWA2-1EX-STREET-IRR             A          1                                 
    2 PIWA2-1EX-BIKE-LANE              A          1                                 
    2 PIWA2-1EX-FED-CLASS-CODE         A          2                                 
    2 PIWA2-1EX-ROW-TYPE               A          1                                 
    2 PIWA2-1EX-LGC-LIST-2             A         10                                 
    2 PIWA2-1EX-LEGACY-SEG-ID          A          7                                 
    2 PIWA2-1EX-LGC-LIST-FROM-1        A         10                                 
    2 PIWA2-1EX-LGC-LIST-TO-1          A         10                                 
    2 PIWA2-1EX-LGC-LIST-FROM-2        A         10                                 
    2 PIWA2-1EX-LGC-LIST-TO-2          A         10                                 
    2 PIWA2-1EX-NOCROSS-FLG            A          1                                 
    2 PIWA2-1EX-IND-SEG-LEN            A          5                                 
    2 PIWA2-1EX-NTA-NAME               A         75                                 
    2 PIWA2-1EX-USPS-CITY-NAME         A         25 /*USPS PREFERRED CITY NAME      
    2 PIWA2-1EX-LATITUDE               A          9                                 
    2 PIWA2-1EX-LONGITUDE              A         11                                 
    2 PIWA2-1EX-SEG-FROM-NODE          A          7                                 
    2 PIWA2-1EX-SEG-TO-NODE            A          7                                 
    2 PIWA2-1EX-SEG-FROM-XYZ           A         21                                 
    2 PIWA2-1EX-SEG-TO-XYZ             A         21                                 
    2 PIWA2-1EX-BLOCKFACE-ID           A         10 /* V16.1 ADD                    
    2 PIWA2-1EX-NBR-TRAVEL-LANES       A          2 /* V16.1 ADD                    
    2 PIWA2-1EX-NBR-PARK-LANES         A          2 /* V16.1 ADD                    
    2 PIWA2-1EX-NBR-TOTAL-LANES        A          2 /* V16.1 ADD                    
    2 PIWA2-1EX-STR-WIDTH-MAX          A          3 /* V16.4 ADDITION               
    2 FILLER-1EX-500                   A        252 /* V16.1 MOD + V16.4 MOD        
    *  2 FILLER-1EX-500                   A        255 /* V16.1 MOD                    
    * ** ***  THE FOLLOWING FIELDS ARE IN     ADDITION TO 1E *****************         
    2 PIWA2-1EX-REASON-CODE            A          1                                 
    2 PIWA2-1EX-REASON-CODE-QUAL       A          1                                 
    2 PIWA2-1EX-WARN-CODE              A          2                                 
    2 PIWA2-1EX-RETURN-CODE            A          2                                 
    2 PIWA2-1EX-NUM-X-STS-LO-END       A          1                                 
    2 PIWA2-1EX-LO-B7SC                A          8 (1:5)                           
    2 PIWA2-1EX-NUM-X-STS-HI-END       A          1                                 
    2 PIWA2-1EX-HI-B7SC                A          8 (1:5)                           
    2 PIWA2-1EX-LO-ST-NAME             A         32 (1:5)                           
    2 PIWA2-1EX-HI-ST-NAME             A         32 (1:5)                           
    2 PIWA2-1EX-BOE-B7SC               A          8                                 
    2 PIWA2-1EX-BOE-ST-NAME            A         32                                 
    2 FILLER-1EX-600                   A         52                                 
    *  *  END OF FUNCTION 1/1E LAYOUT     *       **** *******                         
    *  - -------------------------------- -       ---- --------------------------------
    *  *  BEGNING OF FCT 1A EXTENDED      * ********** *******                         
    R  1 GEOLP2AL                                                                      
    2 PIWA2-1AX-ACCESS-KEY             A         21                                 
    2 PIWA2-1AX-CONT-PARITY            A          1 /* OR DUP ADDR IND              
    2 PIWA2-1AX-LOW-HOUSENUM           A         11 /* SORT FORMAT                  
    2 PIWA2-1AX-BBL                    A         10                                 
    R  2 PIWA2-1AX-BBL                                                                 
    3 PIWA2-1AX-BBL-BORO               A          1                                 
    3 PIWA2-1AX-BLOCK                  A          5                                 
    3 PIWA2-1AX-LOT                    A          4                                 
    2 PIWA2-1AX-LOT-VERSION            A          1 /* NYI */                       
    2 PIWA2-1AX-SCC                    A          1                                 
    2 FILLER-1AX-100                   A          1                                 
    2 PIWA2-1AX-GENERAL-LOT-INFO                                                    
    3 PIWA2-1AX-RPAD-BLDG-CLASS        A          2                                 
    3 PIWA2-1AX-CORNER-CODE            A          2                                 
    3 PIWA2-1AX-NUM-OF-STRUCTURES      A          4                                 
    3 PIWA2-1AX-NUM-OF-BLOCKFACES      A          2                                 
    3 PIWA2-1AX-INTERIOR-FLAG          A          1                                 
    3 PIWA2-1AX-VACANT-FLAG            A          1                                 
    3 PIWA2-1AX-IRREG-LOT-FLAG         A          1                                 
    2 PIWA2-1AX-MARBLE-RIKERS-FLAG     A          1                                 
    2 PIWA2-1AX-ADDR-LIST-OVFLOW-FLAG  A          1                                 
    2 PIWA2-1AX-STROLL-KEY             A         19                                 
    R  2 PIWA2-1AX-STROLL-KEY                                                          
    3 PIWA2-1AX-STROLL-BORO            A          1                                 
    3 PIWA2-1AX-STROLL-5SC             A          5                                 
    3 PIWA2-1AX-STROLL-SIDE-OF-STR     A          1 /* L OR R                       
    3 PIWA2-1AX-STROLL-HI-HOUSENUM     A         11 /* SORT FORMAT                  
    3 FILLER-1AX-200                   A          1                                 
    2 FILLER-1AX-300                   A          1 /* FOR GSS USE                  
    2 PIWA2-1AX-BIN                    A          7                                 
    2 PIWA2-1AX-CONDO-FLAG             A          1                                 
    2 FILLER-1AX-400                   A          1                                 
    2 PIWA2-1AX-RPAD-CONDO-ID-NUM      A          4                                 
    2 PIWA2-1AX-CONDO-UNIT-ID-NUM      A          7                                 
    2 PIWA2-1AX-CONDO-BILL-BBL         A         10                                 
    2 PIWA2-1AX-CONDO-BILL-BBL-VER     A          1                                 
    2 PIWA2-1AX-CONDO-BILL-BBL-SCC     A          1                                 
    2 PIWA2-1AX-CONDO-LOW-BBL          A         10                                 
    2 PIWA2-1AX-CONDO-LOW-BBL-VER      A          1                                 
    2 PIWA2-1AX-CONDO-HIGH-BBL         A         10                                 
    2 PIWA2-1AX-CONDO-HIGH-BBL-VER     A          1                                 
    2 FILLER-1AX-600                   A         15                                 
    2 PIWA1-1AX-COOP-NUM               A          4                                 
    2 PIWA2-1AX-SANBORN                A          8                                 
    R  2 PIWA2-1AX-SANBORN                                                             
    3 PIWA2-1AX-SANBORN-BORO           A          1                                 
    3 PIWA2-1AX-SANBORN-VOL            A          3                                 
    3 PIWA2-1AX-SANBORN-PAGE           A          4                                 
    2 PIWA2-1AX-COMMERC-DIST           A          5                                 
    2 PIWA2-1AX-DOF-MAP-BORO           A          1                                 
    2 PIWA2-1AX-DOF-MAP-SECVOL         A          4                                 
    2 PIWA2-1AX-DOF-MAP-PAGE           A          4                                 
    2 FILLER-1AX-RESERVED-DCP          A          3                                 
    2 PIWA2-1AX-LATITUDE               A          9                                 
    2 PIWA2-1AX-LONGITUDE              A         11                                 
    2 PIWA2-1AX-X-COORD                A          7                                 
    2 PIWA2-1AX-Y-COORD                A          7                                 
    2 PIWA2-1AX-BID                    A          6                                 
    2 PIWA2-1AX-TPAD-BIN-ST            A          1 /* CURRENT STATUS */            
    2 PIWA2-1AX-TPAD-NEW-BIN           A          7 /* NEW BIN */                   
    2 PIWA2-1AX-TPAD-NEW-BIN-ST        A          1 /* NEW BIN STATUS */            
    2 PIWA2-1AX-TPAD-CONFLICT          A          1 /* CONFLICT FLAG */             
    2 FILLER-1AX-650                   A          9                                 
    2 FILLER-1AX-700                   A          8 /* FOR GSS USE                  
    2 PIWA2-1AX-REASON-CODE            A          1                                 
    2 PIWA2-1AX-REASON-CODE-QUAL       A          1                                 
    2 PIWA2-1AX-WARN-CODE              A          2                                 
    2 PIWA2-1AX-RETURN-CODE            A          2                                 
    2 FILLER-1AX-750                   A        108                                 
    2 PIWA2-1AX-NUM-OF-ADDR            A          4                                 
    2 PIWA2-1AX-LIST-OF-ADDR                        (1:21)                          
    3 PIWA2-1AX-LIST-LOW-HOUSENUM      A         16 /* DISPLAY FORMAT               
    3 PIWA2-1AX-LIST-HI-HOUSENUM       A         16 /* DISPLAY FORMAT               
    3 PIWA2-1AX-LIST-BORO              A          1                                 
    3 PIWA2-1AX-LIST-5SC               A          5                                 
    3 PIWA2-1AX-LIST-LGC               A          2                                 
    3 PIWA2-1AX-LIST-BIN               A          7                                 
    3 PIWA2-1AX-LIST-SIDE-OF-STR       A          1 /* L OR R                       
    3 PIWA2-1AX-ADDR-TYPE              A          1 /* P=NAP, B=NAB,          MAL   
    R  3 PIWA2-1AX-ADDR-TYPE                           /* REDEF. BEGIN : PIWA2-1AX-ADDR
    4 PIWA2-1AX-LIST-ADDR-TYPE         A          1 /* BLANK=NORMAL                 
    *  *                                               /* BLANK=NORMAL                 
    3 PIWA2-1AX-TPAD-STATUS            A          1 /* 0 - 9                        
    R  3 PIWA2-1AX-TPAD-STATUS                         /* REDEF. BEGIN : PIWA2-1AX-TPAD
    4 PIWA2-1AX-LIST-TPAD-STATUS       A          1                                 
    3 PIWA2-1AX-ST-NAME                A         32 /* 0 - 9                        
    R  3 PIWA2-1AX-ST-NAME                             /* REDEF. BEGIN : PIWA2-1AX-ST-N
    4 PIWA2-1AX-LIST-ST-NAME           A         32                                 
    3 FILLER-800                       A         34                                 
    * ** END OF FUNCTION 1A EXTENDED **** * ********** ***********************         
    * -- -------------------------------- - ---------- --------------------------      
    * ** BEGINNING OF FUNCTION 1B ******* * ********** ***********************         
    R  1 GEOLP2AL                                                                      
    2 PIWA2-1B-1-ACCESS-KEY            A         21                                 
    2 PIWA2-1B-1-CONT-PARITY           A          1 /* (OR DUP ADDR IND)            
    2 PIWA2-1B-1-LOW-HOUSENUM          A         11 /* SORT FORMAT                  
    2 PIWA2-1B-1-HI-HOUSENUM           A         11 /* SORT FORMAT                  
    2 PIWA2-1B-1-PREFERRED-LGC         A          2                                 
    2 PIWA2-1B-1-NUM-X-ST-LOW-END      A          1                                 
    2 PIWA2-1B-1-LOW-B5SC              A          6 (1:5) /* 30-BYTES               
    2 PIWA2-1B-1-NUM-X-ST-HI-END       A          1                                 
    2 PIWA2-1B-1-HI-B5SC               A          6 (1:5) /* 30-BYTES               
    2 PIWA2-1B-1-LIONKEY               A         10                                 
    R  2 PIWA2-1B-1-LIONKEY                                                            
    3 PIWA2-1B-1-LION-BORO             A          1                                 
    3 PIWA2-1B-1-LION-FACECODE         A          4                                 
    3 PIWA2-1B-1-LION-SEQ              A          5                                 
    2 PIWA2-1B-1-SPECIAL-ADDR-FLAG     A          1                                 
    2 PIWA2-1B-1-SIDE-OF-STR           A          1                                 
    2 PIWA2-1B-1-SEG-LEN               A          5                                 
    2 PIWA2-1B-1-X-COORD               A          7                                 
    2 PIWA2-1B-1-Y-COORD               A          7                                 
    2 FILLER-1B-1-100                  A          7 /* FOR ZCOORD                   
    2 PIWA2-1B-1-CD-ELIGIBLE           A          1                                 
    2 PIWA2-1B-1-MARBLE-RIKERS-FLAG    A          1                                 
    2 PIWA2-1B-1-DOT-SLA               A          1                                 
    2 PIWA2-1B-1-COM-DIST              A          3                                 
    R  2 PIWA2-1B-1-COM-DIST                                                           
    3 PIWA2-1B-1-COM-DIST-BORO         A          1                                 
    3 PIWA2-1B-1-COM-DIST-NUM          A          2                                 
    2 PIWA2-1B-1-ZIP                   A          5                                 
    *  *                                  *       **** *****                           
    *  *  THE FN1E FIELDS ARE VALID ONLY  *       **** *****                           
    *  *  FOR FUNCTION 1E, NOT FUNC 1.    *       **** *****                           
    2 PIWA2-1B-1-ELECT-DIST            A          3                                 
    2 PIWA2-1B-1-ASSEM-DIST            A          2                                 
    2 PIWA2-1B-1-SPLIT-ED-FLAG         A          1                                 
    2 PIWA2-1B-1-CONG-DIST             A          2                                 
    2 PIWA2-1B-1-SENATE-DIST           A          2                                 
    2 PIWA2-1B-1-COURT-DIST            A          2                                 
    2 PIWA2-1B-1-COUNCIL-DIST          A          2                                 
    *  *                                  *       **** *****                           
    2 PIWA2-1B-1-HEALTH-CENTER-DIST    A          2                                 
    2 PIWA2-1B-1-HEALTH-AREA           A          4                                 
    2 PIWA2-1B-1-SANI-DIST             A          3                                 
    R  2 PIWA2-1B-1-SANI-DIST                                                          
    3 PIWA2-1B-1-SANI-DIST-BORO        A          1                                 
    3 PIWA2-1B-1-SANI-DIST-NUM         A          2                                 
    2 PIWA2-1B-1-SANI-SUBSEC           A          2                                 
    2 PIWA2-1B-1-SANI-REG              A          5                                 
    2 PIWA2-1B-1-SANI-REC              A          3                                 
    2 PIWA2-1B-1-POLICE-DIST           A          4                                 
    R  2 PIWA2-1B-1-POLICE-DIST                                                        
    3 PIWA2-1B-1-POL-PAT-BORO-CMD      A          1                                 
    3 PIWA2-1B-1-POL-PRECINCT          A          3                                 
    2 PIWA2-1B-1-FIRE-DIV              A          2                                 
    2 PIWA2-1B-1-FIRE-BAT              A          2                                 
    2 PIWA2-1B-1-FIRE-CO               A          4                                 
    R  2 PIWA2-1B-1-FIRE-CO                                                            
    3 PIWA2-1B-1-FIRE-CO-TYPE          A          1                                 
    3 PIWA2-1B-1-FIRE-CO-NUM           A          3                                 
    2 FILLER-1B-1-250                  A          1 /* WAS SPLIT COM SCHL           
    2 PIWA2-1B-1-SCHL-DIST             A          2                                 
    2 PIWA2-1B-1-DYN-BLK               A          3                                 
    2 PIWA2-1B-1-POLICE-PAT-BORO       A          2                                 
    2 PIWA2-1B-1-FEATURE-TYPE          A          1                                 
    2 PIWA2-1B-1-SEGMENT-TYPE          A          1                                 
    2 PIWA2-1B-1-ALX                   A          1                                 
    2 PIWA2-1B-1-COINCIDENT-SEG-CTR    A          1                                 
    2 FILLER-1B-1-290                  A          3                                 
    2 PIWA2-1B-1-1990-CENSUS-TRACT     A          6                                 
    2 PIWA2-1B-1-2010-CENSUS-TRACT     A          6                                 
    2 PIWA2-1B-1-2010-CENSUS-BLOCK     A          4                                 
    2 PIWA2-1B-1-2010-CENSUS-BLOCK-SUF A          1                                 
    2 PIWA2-1B-1-2000-CENSUS-TRACT     A          6 /* NA                           
    2 PIWA2-1B-1-2000-CENSUS-BLOCK     A          4 /* NA                           
    2 PIWA2-1B-1-2000-CENSUS-BLOCK-SUF A          1 /* NA                           
    2 PIWA2-1B-1-NTA                   A          4 /*NEIGHBORHOOD                  
    *  *                                               /*TABULATION AREA               
    2 PIWA2-1B-1-SANIT-SNOW-PRIORITY   A          1 /*SANITATION STRT               
    *  *                                               /*SNOW PRIORITY                 
    2 PIWA2-1B-1-SANIT-ORGANICS        A          5                                 
    2 PIWA2-1B-1-SANIT-BULK-PICK-UP    A          5 /* V16.4 ADDITION               
    *  2 PIWA2-1B-1-SANIT-RESERVED        A          5                                 
    2 PIWA2-1B-1-HURRICANE-ZONE        A          2 /*OEM HURRICANE EVAC ZONE       
    2 FILLER-1B-1-300                  A         11                                 
    2 PIWA2-1B-1-UHNS                  A         11 /* UNDERLYING HNS               
    2 PIWA2-1B-1-REAL-B7SC             A          8                                 
    2 PIWA2-1B-1-SEGMENT-ID            A          7                                 
    2 PIWA2-1B-1-CURVE-FLAG            A          1                                 
    2 PIWA2-1B-1-LGCS                  A          8                                 
    2 PIWA2-1B-1-BOE-PTR               A          1                                 
    2 PIWA2-1B-1-AZIMUTH               A          3                                 
    2 PIWA2-1B-1-ORIENT                A          1                                 
    2 PIWA2-1B-1-X-LOW                 A          7                                 
    2 PIWA2-1B-1-Y-LOW                 A          7                                 
    2 PIWA2-1B-1-Z-LOW                 A          7                                 
    2 PIWA2-1B-1-X-HI                  A          7                                 
    2 PIWA2-1B-1-Y-HI                  A          7                                 
    2 PIWA2-1B-1-Z-HI                  A          7                                 
    2 PIWA2-1B-1-X-CC                  A          7                                 
    2 PIWA2-1B-1-Y-CC                  A          7                                 
    2 PIWA2-1B-1-Z-CC                  A          7                                 
    2 PIWA2-1B-1-RADIUS                A          7                                 
    2 PIWA2-1B-1-SECANT                A          1                                 
    2 PIWA2-1B-1-ANGLE-FROM            A          5                                 
    2 PIWA2-1B-1-ANGLE-TO              A          5                                 
    2 PIWA2-1B-1-NODE-FROM             A          7                                 
    2 PIWA2-1B-1-NODE-TO               A          7                                 
    2 PIWA2-1B-1-VANITY-LION           A         10                                 
    2 PIWA2-1B-1-SOS                   A          1                                 
    2 PIWA2-1B-1-SPLIT-LOHSN           A         11                                 
    2 PIWA2-1B-1-TD                    A          1                                 
    2 PIWA2-1B-1-TR                    A         10                                 
    2 PIWA2-1B-1-CURVE-FRACTION        A          3                                 
    2 PIWA2-1B-1-ROADWAY-TYPE          A          2                                 
    2 PIWA2-1B-1-PHYSICAL-ID           A          7                                 
    2 PIWA2-1B-1-GENERIC-ID            A          7                                 
    2 PIWA2-1B-1-INTP-ID               A          7                                 
    2 PIWA2-1B-1-INTF-ID               A          7                                 
    2 PIWA2-1B-1-BIKE-LANE-2           A          2                                 
    2 PIWA2-1B-1-BIKE-TRAFFIC-DIR      A          2 /* V17.1 ADDITION               
    2 PIWA2-1B-1-FILL450               A          3 /* V17.1 ALTERATION             
    *  2 PIWA2-1B-1-FILL450               A          5 /* V16.4 ALTERATION             
    *  2 PIWA2-1B-1-FILL450               A          7 /* V16.1 REPLACEMENT            
    2 PIWA2-1B-1-STREET-STATUS         A          1                                 
    2 PIWA2-1B-1-STREET-WIDTH          A          3                                 
    2 PIWA2-1B-1-STREET-WIDTH-IRR      A          1                                 
    2 PIWA2-1B-1-BIKE-LANE             A          1                                 
    2 PIWA2-1B-1-FED-CLASS-CODE        A          2                                 
    2 PIWA2-1B-1-ROW-TYPE              A          1                                 
    2 PIWA2-1B-1-LGC-LIST-2            A         10                                 
    2 PIWA2-1B-1-LEGACY-SEG-ID         A          7                                 
    2 PIWA2-1B-1-LGC-LIST-FROM-1       A         10                                 
    2 PIWA2-1B-1-LGC-LIST-TO-1         A         10                                 
    2 PIWA2-1B-1-LGC-LIST-FROM-2       A         10                                 
    2 PIWA2-1B-1-LGC-LIST-TO-2         A         10                                 
    2 PIWA2-1B-1-NOCROSS-FLG           A          1                                 
    2 PIWA2-1B-1-IND-SEG-LEN           A          5                                 
    2 PIWA2-1B-1-NTA-NAME              A         75                                 
    2 PIWA2-1B-1-USPS-CITY-NAME        A         25 /*USPS PREFERRED CITY NAME      
    2 PIWA2-1B-1-LATITUDE              A          9                                 
    2 PIWA2-1B-1-LONGITUDE             A         11                                 
    2 PIWA2-1B-1-SEG-FROM-NODE         A          7                                 
    2 PIWA2-1B-1-SEG-TO-NODE           A          7                                 
    2 PIWA2-1B-1-SEG-FROM-XYZ          A         21                                 
    2 PIWA2-1B-1-SEG-TO-XYZ            A         21                                 
    2 PIWA2-1B-1-BLOCKFACE-ID          A         10 /* V16.1 ADD                    
    2 PIWA2-1B-1-NBR-TRAVEL-LANES      A          2 /* V16.1 ADD                    
    2 PIWA2-1B-1-NBR-PARK-LANES        A          2 /* V16.1 ADD                    
    2 PIWA2-1B-1-NBR-TOTAL-LANES       A          2 /* V16.1 ADD                    
    2 PIWA2-1B-1-STR-WIDTH-MAX         A          3 /* V16.4 ADDITION               
    2 FILLER-1B-1-500                  A        252 /* V16.4 MOD                    
    *  2 FILLER-1B-1-500                  A        255 /* V16.1 MOD                    
    * ** **** THE FOLLOWING FIELDS ARE IN   ADDITION   TO 1/1E****************         
    2 PIWA2-1B-1-REASON-CODE           A          1                                 
    2 PIWA2-1B-1-REASON-CODE-QUAL      A          1                                 
    2 PIWA2-1B-1-WARN-CODE             A          2                                 
    2 PIWA2-1B-1-RETURN-CODE           A          2                                 
    2 PIWA2-1B-1-NUM-X-STS-LO-END      A          1                                 
    2 PIWA2-1B-1-LO-B7SC               A          8 (1:5)                           
    2 PIWA2-1B-1-NUM-X-STS-HI-END      A          1                                 
    2 PIWA2-1B-1-HI-B7SC               A          8 (1:5)                           
    2 PIWA2-1B-1-LO-ST-NAME            A         32 (1:5)                           
    2 PIWA2-1B-1-HI-ST-NAME            A         32 (1:5)                           
    2 PIWA2-1B-1-BOE-B7SC              A          8                                 
    2 PIWA2-1B-1-BOE-ST-NAME           A         32                                 
    2 FILLER-1B-1-600                  A         52                                 
    *  * ******************************** * ********** ******************              
    *  * THE FOLLOWING FIELDS ARE         * ********** ********                        
    *  *     PROPERTY LEVEL FIELDS        * ********** ********                        
    2 PIWA2-1B-1A-ACCESS-KEY           A         21 /*CHG FROM LEVEL 3 TO 2???      
    2 PIWA2-1B-1A-CONT-PARITY          A          1 /* OR DUP ADDR IND              
    2 PIWA2-1B-1A-LOW-HOUSENUM         A         11 /* SORT FORMAT                  
    2 PIWA2-1B-1A-BBL                  A         10                                 
    R  2 PIWA2-1B-1A-BBL                                                               
    3 PIWA2-1B-1A-BBL-BORO             A          1                                 
    3 PIWA2-1B-1A-BLOCK                A          5                                 
    3 PIWA2-1B-1A-LOT                  A          4                                 
    2 PIWA2-1B-1A-LOT-VERSION          A          1 /* NYI */                       
    2 PIWA2-1B-1A-SCC                  A          1                                 
    2 FILLER-1B-1A-100                 A          1                                 
    2 PIWA2-1B-1A-GENERAL-LOT-INFO                                                  
    3 PIWA2-1B-1A-RPAD-BLDG-CLASS      A          2                                 
    3 PIWA2-1B-1A-CORNER-CODE          A          2                                 
    3 PIWA2-1B-1A-NUM-OF-STRUCTURES    A          4                                 
    3 PIWA2-1B-1A-NUM-OF-BLOCKFACES    A          2                                 
    3 PIWA2-1B-1A-INTERIOR-FLAG        A          1                                 
    3 PIWA2-1B-1A-VACANT-FLAG          A          1                                 
    3 PIWA2-1B-1A-IRREG-LOT-FLAG       A          1                                 
    2 PIWA2-1B-1A-MARBLE-RIKERS-FLAG   A          1                                 
    2 PIWA2-1B-1A-ADDR-LIST-OVFLOW-FLG A          1 /*FLAG,FLG?????????             
    2 PIWA2-1B-1A-STROLL-KEY           A         19                                 
    R  2 PIWA2-1B-1A-STROLL-KEY                                                        
    3 PIWA2-1B-1A-STROLL-BORO          A          1                                 
    3 PIWA2-1B-1A-STROLL-5SC           A          5                                 
    3 PIWA2-1B-1A-STROLL-SIDE-OF-STR   A          1 /* L OR R                       
    3 PIWA2-1B-1A-STROLL-HI-HOUSENUM   A         11 /* SORT FORMAT                  
    3 FILLER-1B-1A-200                 A          1                                 
    2 FILLER-1B-1A-300                 A          1 /* FOR GSS USE                  
    2 PIWA2-1B-1A-BIN                  A          7                                 
    2 PIWA2-1B-1A-CONDO-FLAG           A          1                                 
    2 FILLER-1B-1A-400                 A          1                                 
    2 PIWA2-1B-1A-RPAD-CONDO-ID-NUM    A          4                                 
    2 PIWA2-1B-1A-CONDO-UNIT-ID-NUM    A          7                                 
    2 PIWA2-1B-1A-CONDO-BILL-BBL       A         10                                 
    2 PIWA2-1B-1A-CONDO-BILL-BBL-VER   A          1                                 
    2 PIWA2-1B-1A-CONDO-BILL-BBL-SCC   A          1                                 
    2 PIWA2-1B-1A-CONDO-LOW-BBL        A         10                                 
    2 PIWA2-1B-1A-CONDO-LOW-BBL-VER    A          1                                 
    2 PIWA2-1B-1A-CONDO-HIGH-BBL       A         10                                 
    2 PIWA2-1B-1A-CONDO-HIGH-BBL-VER   A          1                                 
    2 FILLER-1B-1A-500                 A         15                                 
    2 PIWA1-1B-1A-COOP-NUM             A          4                                 
    2 PIWA2-1B-1A-SANBORN              A          8                                 
    R  2 PIWA2-1B-1A-SANBORN                                                           
    3 PIWA2-1B-1A-SANBORN-BORO         A          1                                 
    3 PIWA2-1B-1A-SANBORN-VOL          A          3                                 
    3 PIWA2-1B-1A-SANBORN-PAGE         A          4                                 
    2 PIWA2-1B-1A-COMMERC-DIST         A          5                                 
    2 PIWA2-1B-1A-DOF-MAP-BORO         A          1                                 
    2 PIWA2-1B-1A-DOF-MAP-SECVOL       A          4                                 
    2 PIWA2-1B-1A-DOF-MAP-PAGE         A          4                                 
    2 FILLER-1B-1A-RESERVED-DCP        A          3                                 
    2 PIWA2-1B-1A-LATITUDE             A          9                                 
    2 PIWA2-1B-1A-LONGITUDE            A         11                                 
    2 PIWA2-1B-1A-X-COORD              A          7                                 
    2 PIWA2-1B-1A-Y-COORD              A          7                                 
    2 PIWA2-1B-1A-BID                  A          6                                 
    2 PIWA2-1B-1A-TPAD-BIN-ST          A          1 /* CURRENT STATUS */            
    2 PIWA2-1B-1A-TPAD-NEW-BIN         A          7 /* NEW BIN */                   
    2 PIWA2-1B-1A-TPAD-NEW-BIN-ST      A          1 /* NEW BIN STATUS */            
    2 PIWA2-1B-1A-TPAD-CONFLICT        A          1 /* CONFLICT FLAG */             
    2 FILLER-1B-1A-650                 A          9                                 
    2 FILLER-1B-1A-700                 A          8 /* FOR GSS USE                  
    2 PIWA2-1B-1A-REASON-CODE          A          1                                 
    2 PIWA2-1B-1A-REASON-CODE-FILL     A          1                                 
    2 PIWA2-1B-1A-WARN-CODE            A          2                                 
    2 PIWA2-1B-1A-RETURN-CODE          A          2                                 
    2 FILLER-1B-1A-750                 A        108                                 
    2 PIWA2-1B-1A-NUM-OF-ADDR          A          4                                 
    2 PIWA2-1B-1A-LIST-OF-ADDR                      (1:21)                          
    3 PIWA2-1B-1A-LIST-LOW-HOUSENUM    A         16 /* DISPLAY FORMAT               
    3 PIWA2-1B-1A-LIST-HI-HOUSENUM     A         16 /* DISPLAY FORMAT               
    3 PIWA2-1B-1A-LIST-BORO            A          1                                 
    3 PIWA2-1B-1A-LIST-5SC             A          5                                 
    3 PIWA2-1B-1A-LIST-LGC             A          2                                 
    3 PIWA2-1B-1A-LIST-BIN             A          7                                 
    3 PIWA2-1B-1A-LIST-SIDE-OF-STR     A          1 /* L OR R                       
    3 PIWA2-1B-1A-ADDR-TYPE            A          1 /* P=NAP, B=NAB,          MAL   
    R  3 PIWA2-1B-1A-ADDR-TYPE                         /* REDEF. BEGIN : PIWA2-1B-1A-AD
    4 PIWA2-1B-1A-LIST-ADDR-TYPE       A          1 /* BLANK=NORMAL                 
    3 PIWA2-1B-1A-TPAD-STATUS          A          1 /* 0 - 9                        
    R  3 PIWA2-1B-1A-TPAD-STATUS                       /* REDEF. BEGIN : PIWA2-1B-1A-TP
    4 PIWA2-1B-1A-LIST-TPAD-STATUS     A          1                                 
    3 PIWA2-1B-1A-ST-NAME              A         32                                 
    R  3 PIWA2-1B-1A-ST-NAME                           /* REDEF. BEGIN : PIWA2-1B-1A-ST
    4 PIWA2-1B-1A-LIST-ST-NAME         A         32                                 
    3 FILLER-1B-1A-800                 A         34                                 
    * ** END OF FUNCTION 1B ************* * ********** **************************      


## <span id="appendix14.27"><center>GEOLP23S COPY File</center></span>  

    1 GEOLP23S                                                                   
    *  * THE FIELD P2NAT3S IS USED AS A      PARAMETER TO CALL GEOSUPPORT           
    2 P2NAT3S                          A         21                              
    R  2 P2NAT3S                                                                    
    3 PIWA2-3S-ACCESS-KEY              A         21                              
    R  3 PIWA2-3S-ACCESS-KEY                                                        
    4 FILLER-GSS                       A          2                              
    4 PIWA2-3S-PORS-STNAME-IND         A          1                              
    4 PIWA2-3S-BORO                    A          1 /* P=PRIMARY                 
    *  *                                               /* B=SECONDARY               
    4 PIWA2-3S-5SC                     A          5                              
    4 PIWA2-3S-LGC                     A          2 /* BLANK IF P IN             
    4 FILLER                           A         10 /* POSITION 3                
    2 PIWA2-3S-NUM-OF-INTERSECTS       A          3                              
    2 PIWA2-3S-LIST-OF-INTERSECTS                   (1:350)                      
    3 PIWA2-3S-MARBLE-RIKERS-FLAG      A          1                              
    3 PIWA2-3S-DISTANCE                A          5                              
    3 PIWA2-3S-GAP-FLAG                A          1                              
    3 FILLER-100                       A          7                              
    3 PIWA2-3S-NUM-OF-STR              A          1                              
    3 PIWA2-3S-B7SC                    A          8 (1:5)                        

## <span id="appendix14.28"><center>GEOL2AP COPY File</center></span>  

    1 GEOL2AP                                                                   
    2 P2NATAP                          A         21                             
    R  2 P2NATAP                                                                   
    3 PIWA2-AP-ACCESS-KEY              A         21                             
    2 PIWA2-AP-CONT-PARITY             A          1                             
    2 PIWA2-AP-LOW-HOUSENUM            A         11                             
    2 PIWA2-AP-BBL                     A         10                             
    R  2 PIWA2-AP-BBL                                                              
    3 PIWA2-AP-BBL-BORO                A          1                             
    3 PIWA2-AP-BBL-BLOCK               A          5                             
    3 PIWA2-AP-BBL-LOT                 A          4                             
    2 FILLER-AP01                      A          7                             
    2 PIWA2-AP-NUM-OF-STRUCTURES       A          4                             
    2 FILLER-AP02                      A         26                             
    2 FILLER-AP-GSS1                   A          1                             
    2 PIWA2-AP-BIN                     A          7                             
    2 PIWA2-AP-CONDO-FLAG              A          1                             
    2 FILLER-AP03                      A          1                             
    2 PIWA2-AP-RPAD-CONDO-ID-NUM       A          4                             
    2 FILLER-AP04                      A          7                             
    2 PIWA2-AP-CONDO-BILL-BBL          A         10                             
    2 FILLER-AP05                      A          2                             
    2 PIWA2-AP-CONDO-LOW-BBL           A         10                             
    2 FILLER-AP06                      A          1                             
    2 PIWA2-AP-CONDO-HIGH-BBL          A         10                             
    2 FILLER-AP07                      A         16                             
    2 PIWA2-AP-COOP-NUM                A          4                             
    2 FILLER-AP08                      A         22                             
    2 PIWA2-AP-RESERVED                A          3                             
    2 PIWA2-AP-LATITUDE                A          9                             
    2 PIWA2-AP-LONGITUDE               A         11                             
    2 PIWA2-AP-X-COORD                 A          7                             
    2 PIWA2-AP-Y-COORD                 A          7                             
    2 FILLER-AP09                      A         16                             
    2 PIWA2-AP-AP-ID                   A          9                             
    2 FILLER-AP-GSS2                   A          8                             
    2 PIWA2-AP-NUM-OF-ADDR             A          4                             
    2 PIWA2-AP-ADDR-LIST                            (1:21)                      
    3 PIWA2-AP-LIST-LOW-HOUSENUM       A         16                             
    3 PIWA2-AP-LIST-HI-HOUSENUM        A         16                             
    3 PIWA2-AP-LIST-BORO               A          1                             
    3 PIWA2-AP-LIST-5SC                A          5                             
    3 PIWA2-AP-LIST-LGC                A          2                             
    3 PIWA2-AP-LIST-BIN                A          7                            
    3 PIWA2-AP-LIST-SIDE-OF-STR        A          1                            
    3 PIWA2-AP-ADDR-TYPE               A          1                            
    R  3 PIWA2-AP-ADDR-TYPE                                                       
    4 PIWA2-AP-LIST-ADDR-TYPE          A          1                             
    3 FILLER-AP10                      A          4                             

## <span id="appendix14.29"><center>GEOL2APX COPY File</center></span>  

    1 GEOL2APX                                                                   
    2 P2NATAPX                         A         21                              
    R  2 P2NATAPX                                                                   
    3 PIWA2-APX-ACCESS-KEY             A         21                              
    2 PIWA2-APX-CONT-PARITY            A          1                              
    2 PIWA2-APX-LOW-HOUSENUM           A         11                              
    2 PIWA2-APX-BBL                    A         10                              
    R  2 PIWA2-APX-BBL                                                              
    3 PIWA2-APX-BBL-BORO               A          1                              
    3 PIWA2-APX-BBL-BLOCK              A          5                              
    3 PIWA2-APX-BBL-LOT                A          4                              
    2 FILLER-APX01                     A          7                              
    2 PIWA2-APX-NUM-OF-STRUCTURES      A          4                              
    2 FILLER-APX02                     A         26                              
    2 FILLER-APX-GSS1                  A          1                              
    2 PIWA2-APX-BIN                    A          7                              
    2 PIWA2-APX-CONDO-FLAG             A          1                              
    2 FILLER-APX03                     A          1                              
    2 PIWA2-APX-RPAD-CONDO-ID-NUM      A          4                              
    2 FILLER-APX04                     A          7                              
    2 PIWA2-APX-CONDO-BILL-BBL         A         10                              
    2 FILLER-APX05                     A          2                              
    2 PIWA2-APX-CONDO-LOW-BBL          A         10                              
    2 FILLER-APX06                     A          1                              
    2 PIWA2-APX-CONDO-HIGH-BBL         A         10                              
    2 FILLER-APX07                     A         16                              
    2 PIWA2-APX-COOP-NUM               A          4                              
    2 FILLER-APX08                     A         22                              
    2 PIWA2-APX-RESERVED               A          3                              
    2 PIWA2-APX-LATITUDE               A          9                              
    2 PIWA2-APX-LONGITUDE              A         11                              
    2 PIWA2-APX-X-COORD                A          7                              
    2 PIWA2-APX-Y-COORD                A          7                              
    2 FILLER-APX09                     A         16                              
    2 PIWA2-APX-AP-ID                  A          9                              
    2 FILLER-APX-GSS2                  A          8                              
    2 PIWA2-APX-REASON-CODE            A          1                              
    2 PIWA2-APX-REASON-CODE-QUAL       A          1                              
    2 PIWA2-APX-WARN-CODE              A          2                              
    2 PIWA2-APX-RETURN-CODE            A          2                              
    2 FILLER-APX10                     A        108                              
    2 PIWA2-APX-NUM-OF-ADDR            A          4                              
    2 PIWA2-APX-ADDR-LIST                           (1:21)                       
    3 PIWA2-APX-LIST-LOW-HOUSENUM      A         16                              
    3 PIWA2-APX-LIST-HI-HOUSENUM       A         16                              
    3 PIWA2-APX-LIST-BORO              A          1                              
    3 PIWA2-APX-LIST-5SC               A          5                              
    3 PIWA2-APX-LIST-LGC               A          2                              
    3 PIWA2-APX-LIST-BIN               A          7                              
    3 PIWA2-APX-LIST-SIDE-OF-STR       A          1                              
    3 PIWA2-APX-ADDR-TYPE              A          1                              
    R  3 PIWA2-APX-ADDR-TYPE                                                        
    4 PIWA2-APX-LIST-ADDR-TYPE         A          1                              
    3 FILLER-APX11                     A          1                              
    3 PIWA2-APX-ST-NAME                A         32                              
    R  3 PIWA2-APX-ST-NAME                                                          
    4 PIWA2-APX-LIST-ST-NAME           A         32                              
    3 FILLER-APX12                     A         34   