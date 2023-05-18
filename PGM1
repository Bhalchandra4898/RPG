000100221223     F**********************************************************************
000200221223     H/TITLE  Credit cards
000300000000     F**********************************************************************
000400000000     FXXXD040   CF   E             WORKSTN
000500000000     F                                     SFILE(XXXD04002:RRN)
000600000000     F                                     SFILE(XXXD04006:RRN2)
000700000000     F                                     SFILE(XXXD04009:RRN3)
000800221223     FXXBCTLXX  UF A E           K DISK
000900221223     FXXBCTLCE  IF   E           K DISK
001000230331DBLE F***SRBUSP    IF   E           K DISK
001100230307     D*
001200230331DBLE D*** SRLDA         E DS                  EXTNAME(SRDLDA)
001300000000     D*
001400000000     D* KLIST fields
001500000000     D*
001600221223     D KKCARD          S                   LIKE(XXCARD)
001700221223     D K1CARD          S                   LIKE(XXCARD)
001800221223     D KKCRCT          S                   LIKE(XXCRCT)
001900230307     D KKUSER          S                   LIKE(FMUSER)
002000000000     D*
002100000000     D* Option fields, standard
002200000000     D*
002300230307     D cADD            S              2    INZ('1 ') ALTSEQ(*NONE)
002400000000     D cCHANGE         S              2    INZ('2 ') ALTSEQ(*NONE)
002500000000     D cCOPY           S              2    INZ('3 ') ALTSEQ(*NONE)
002600000000     D cDELETE         S              2    INZ('4 ') ALTSEQ(*NONE)
002700000000     D cDISPLAY        S              2    INZ('5 ') ALTSEQ(*NONE)
002800000000     D cDETAILS        S              2    INZ('6 ') ALTSEQ(*NONE)
002900000000     D*
003000000000     D* Option fields, other
003100000000     D*
003200000000     D cTRANSLATE      S              2    INZ('7 ') ALTSEQ(*NONE)
003300000000     D*
003400000000     D* Panel handling related fields
003500000000     D*
003600000000     D XXEND           S               N
003700000000     D XXFUNC          S               N
003800000000     D XXINIT          S               N
003900000000     D XXMULT          S               N
004000000000     D*
004100000000     D XXMODE          S              2    ALTSEQ(*NONE)
004200000000     D XXOLDM          S              2    ALTSEQ(*NONE)
004300000000     D XXENQ           S               N
004400000000     D XXRDSP          S               N
004500000000     D XXOPT           S                   LIKE(FMOPT)
004600000000     D*
004700000000     D F1ADD           S              2
004800000000     D F1OPT           S              2
004900000000     D*
005000000000     D* Subfile related fields
005100000000     D*
005200000000     D RRM             S                   LIKE(RRN)
005300000000     D RRM2            S                   LIKE(RRN2)
005400000000     D RRM3            S                   LIKE(RRN3)
005500000000     D RRS             S                   LIKE(RRN)
005600000000     D*
005700000000     D XXMXRC          S                   LIKE(RRN)
005800000000     D*
005900000000     D XWCMN           S              3  0 INZ(2)
006000000000     D XWSTL           S              3  0 INZ(7)
006100000000     D XWNOL           S              3  0 INZ(13)
006200000000     D XWFLD           S              3  0 INZ(0)
006300000000     D*
006400000000     D XWADFL          S               N
006500000000     D XWEXCF          S               N
006600000000     D*
006700000000     D XXPC01          S               N
006800000000     D XXSETP          S               N
006900000000     D*
007000000000     D* Error message fields
007100000000     D*
007200000000     D XMSG50          S               N
007300000000     D XMSG51          S               N
007400000000     D XMSG52          S               N
007500000000     D XMSG53          S               N
007600000000     D XMSG55          S               N
007700000000     D XMSG56          S               N
007800000000     D XMSGENQ         S               N
007900000000     D*
008000000000     D* Search related fields
008100000000     D*
008200221223     D X3CADC          S                   LIKE(XXCADC)
008300221223     D X4CADC          S                   LIKE(XXCADC)
008400000000     D*
008500000000     D LP              S              2  0
008600000000     D SL              S              2  0
008700000000     D*
008800000000     D XPFLEN          S              5  0 INZ(80)
008900000000     D XPXLAT          S             80
009000230331     D XPCMD           S              2
009100000000     D*
009200000000     D XXSEARCH        S               N
009300000000     D*
009400000000     D* Saved fields
009500000000     D*
009600000000     D XXCRCT          S                   LIKE(FMCRCT)
009700000000     D*
009800000000     D X1CARD          S                   LIKE(F1CARD)
009900000000     D X1CADC          S                   LIKE(F1CADC)
010000000000     D X1CRCT          S                   LIKE(F1CRCT)
010100000000     D*
010200000000     D* Window related fields
010300000000     D*
010400000000     D*
010500000000     D* Constant fields
010600000000     D*
010700000000     D cYES            S              1    INZ('Y') ALTSEQ(*NONE)
010800000000     D cNO             S              1    INZ('N') ALTSEQ(*NONE)
010900000000     D*
011000000000     D* Work fields
011100000000     D*
011200000000     D XA              S              3  0
011300000000     D XXA1            S              1
011400000000     D XXN40           S              4  0
011500000000     D*
011600000000     C/EJECT
011700000000     C**********************************************************************
011800000000     C*                                                                   **
011900000000     C*   Initiation                                                      **
012000000000     C*                                                                   **
012100000000     C**********************************************************************
012200230307     C*
012300230331DBLE C**** *DTAARA       DEFINE    *LDA          SRLDA
012400230331DBLE C****               IN        SRLDA
012500230307     C*
012600230331DBLE C***  *ENTRY        PLIST
012700230331DBLE C***                PARM                    XPCMD             2
012800000000     C*
012900000000     C*  -- Parameters  --
013000000000     C*
013100000000     C*
013200000000     C*  -- Key lists   --
013300000000     C*
013400000000     C     KKBCTLXX      KLIST
013500000000     C                   KFLD                    KKCARD
013600000000     C*
013700000000     C     K1BCTLXX      KLIST
013800000000     C                   KFLD                    K1CARD
013900000000     C*
014000000000     C     KKBCTLCE      KLIST
014100000000     C                   KFLD                    KKCRCT
014200230307     C*
014300230307     C     KKBUSP        KLIST
014400230307     C                   KFLD                    KKUSER
014500000000     C*
014600000000     C* -- Work-fields --
014700000000     C*
014800230331     C                   EVAL      XPCMD  = *BLANKS
014900230331     C                   EVAL      XXENQ  = *OFF
015000000000     C*
015100000000     C                   EVAL      XXMODE = *BLANKS
015200000000     C                   EVAL      XXOLDM = *BLANKS
015300000000     C*
015400000000     C                   EVAL      F1ADD  = *BLANKS
015500000000     C                   EVAL      F1OPT  = *BLANKS
015600000000     C*
015700000000     C                   EVAL      XXRDSP = *OFF
015800000000     C                   EVAL      XXINIT = *OFF
015900000000     C                   EVAL      XXFUNC = *OFF
016000000000     C                   EVAL      XXEND  = *OFF
016100000000     C                   EVAL      XXMULT = *OFF
016200000000     C*
016300000000     C                   EVAL      XXA1   = *BLANKS
016400000000     C*
016500000000     C                   EVAL      XXN40  = *ZEROS
016600000000     C*
016700000000     C                   EVAL      XWADFL = *OFF
016800000000     C                   EVAL      XWEXCF = *OFF
016900000000     C*
017000000000     C                   EVAL      XXPC01 = *ON
017100000000     C                   EVAL      XXSETP = *ON
017200000000     C*
017300000000     C* String length and search arguement parameters/work fields
017400000000     C*
017500000000     C                   EVAL      SL     = *ZEROS
017600000000     C                   EVAL      LP     = *ZEROS
017700000000     C                   EVAL      XPXLAT = *BLANKS
017800000000     C                   EVAL      XXSEARCH = *ON
017900000000     C*
018000000000     C                   WRITE     CLRDSP
018100000000     C*
018200000000     C* Dummy open
018300000000     C*
018400000000     C                   IF        1 = 2
018500000000     C                   ENDIF
018600000000     C*
018700000000     C* Enquiry mode ?
018800000000     C*
018900000000     C                   EVAL      XXENQ = *OFF
019000000000     C                   EVAL      *IN75 = *OFF
019100000000     C*
019200000000     C                   IF        XPCMD = 'EQ'
019300000000     C                   EVAL      XPCMD = *BLANKS
019400000000     C                   EVAL      XXENQ = *ON
019500000000     C                   EVAL      *IN75 = *ON
019600000000     C                   ENDIF
019700000000     C*
019800000000     C* Initiate subfiles
019900000000     C*
020000000000     C                   EXSR      SR23
020100000000     C                   EXSR      SR24
020200000000     C*
020300000000     C/EJECT
020400000000     C**********************************************************************
020500000000     C*                                                                   **
020600000000     C*    Panel 1 = Display subfile over credit cards                    **
020700000000     C*                                                                   **
020800000000     C**********************************************************************
020900000000     C     SCR01         TAG
021000000000     C*
021100000000     C* Initiate/add to subfile
021200000000     C*
021300000000     C                   EXSR      SR21
021400000000     C                   EXSR      SR01
021500000000     C*
021600000000     C     SCR011        TAG
021700000000     C*
021800000000     C* Display subfile ?
021900000000     C*
022000000000     C                   IF        RRM = *ZEROS
022100000000     C                   EVAL      *IN84 = *OFF
022200000000     C                   WRITE     CLRDSP
022300000000     C                   ELSE
022400000000     C                   EVAL      *IN84 = *ON
022500000000     C                   ENDIF
022600000000     C*
022700000000     C* Display panel
022800000000     C*
022900000000     C                   WRITE     XXXD04001
023000000000     C                   EXFMT(E)  XXXD04003
023100000000     C                   READ(E)   XXXD04001
023200000000     C*
023300000000     C                   EXSR      SR50
023400000000     C     XMSG50        CABEQ     *ON           SCR01
023500000000     C*
023600000000     C                   EVAL      XXINIT = *OFF
023700000000     C                   EVAL      XXEND  = *ON
023800000000     C*
023900000000     C* Exit program ?
024000000000     C*
024100000000     C                   IF        *INKC
024200000000     C                   EVAL      XPCMD  = '03'
024300000000     C                   GOTO      DD9999
024400000000     C                   ENDIF
024500000000     C*
024600000000     C* Previous panel ?
024700000000     C*
024800000000     C                   IF        *INKL
024900000000     C                   EVAL      XPCMD  = '12'
025000000000     C                   GOTO      DD9999
025100000000     C                   ENDIF
025200000000     C*
025300000000     C* Re-fresh panel ?
025400000000     C*
025500000000     C                   IF        *INKE
025600000000     C                   EXSR      SR23
025700000000     C                   EXSR      SR24
025800000000     C                   EVAL      F1CARD = X1CARD
025900000000     C                   EVAL      F1CADC = X1CADC
026000000000     C                   EVAL      F1CRCT = X1CRCT
026100000000     C                   GOTO      SCR01
026200000000     C                   ENDIF
026300000000     C*
026400000000     C* Check entered data in selection fields
026500000000     C*
026600000000     C                   EXSR      SR51
026700000000     C                   IF        XMSG51
026800000000     C                   EVAL      XWEXCF = *ON
026900000000     C                   EVAL      XXSETP = *OFF
027000000000     C                   EVAL      XXPC01 = *OFF
027100000000     C                   GOTO      SCR011
027200000000     C                   ENDIF
027300000000     C*
027400000000     C* Changed values on panel ?
027500000000     C*
027600000000     C                   IF        *IN72 OR *IN73
027700000000     C                   IF        F1CARD <> X1CARD OR
027800000000     C                             F1CADC <> X1CADC OR
027900000000     C                             F1CRCT <> X1CRCT
028000000000     C                   GOTO      SCR01
028100000000     C                   ENDIF
028200000000     C                   ENDIF
028300000000     C*
028400000000     C* RollUp ?
028500000000     C*
028600000000     C                   IF        *IN81
028700000000     C                   EXSR      SR01
028800000000     C                   GOTO      SCR011
028900000000     C                   ENDIF
029000000000     C*
029100000000     C* Fix ADD field (Handles 1 and 2 characters ADD field)
029200000000     C*
029300000000     C                   EVAL      F1ADD = %TRIM(FMADD)
029400000000     C                   IF        %SUBST(F1ADD:1:1) = *ZEROS AND
029500000000     C                             %LEN(%TRIM(FMADD)) = 2
029600000000     C                   EVAL      F1ADD = %SUBST(F1ADD:2)
029700000000     C                   ENDIF
029800000000     C*
029900000000     C                   EVAL      FMADD = F1ADD
030000000000     C*
030100000000     C* Check ADD field
030200000000     C*
030300000000     C                   IF        F1ADD <> *BLANKS AND
030400000000     C                             F1ADD <> cADD
030500000000     C                   EVAL      XWADFL = *ON
030600221223     C                   EVAL      ERRMSG = 'Option not valid in add field'
030700000000     C                   GOTO      SCR011
030800000000     C                   ENDIF
030900000000     C*
031000000000     C* Single add
031100000000     C*
031200000000     C                   IF        F1ADD = cADD
031300000000     C*
031400000000     C                   EVAL      XXEND = *OFF
031500000000     C                   EVAL      XXMULT = *OFF
031600000000     C                   EVAL      XXMODE = cADD
031700000000     C                   EVAL      FMADD = *BLANKS
031800000000     C                   EVAL      F1ADD = *BLANKS
031900000000     C*
032000000000     C                   GOTO      SCR02
032100000000     C*
032200000000     C                   ENDIF
032300000000     C*
032400000000     C* Multiple add
032500000000     C*
032600000000     C                   IF        *INKF
032700000000     C*
032800000000     C                   EVAL      XXEND = *OFF
032900000000     C                   EVAL      XXMULT = *ON
033000000000     C                   EVAL      XXMODE = cADD
033100000000     C                   EVAL      FMADD = *BLANKS
033200000000     C                   EVAL      F1ADD = *BLANKS
033300000000     C                   GOTO      SCR02
033400000000     C*
033500000000     C                   ENDIF
033600000000     C*
033700000000     C                   EVAL      XXMULT = *OFF
033800000000     C*
033900000000     C* Read Subfile (Check option)
034000000000     C*
034100000000     C     SCR012        TAG
034200000000     C*
034300000000     C* Empty Subfile = Return
034400000000     C*
034500000000     C                   IF        RRM = *ZEROS
034600000000     C                   EVAL      XXFUNC = *OFF
034700000000     C                   GOTO      SCR013
034800000000     C                   ENDIF
034900000000     C*
035000000000     C                   READC     XXXD04002
035100000000     C*
035200000000     C                   IF        NOT %EOF(XXXD040)
035300000000     C*
035400000000     C* Fix option field (Handles 1 and 2 characters option field)
035500000000     C*
035600000000     C                   EVAL      F1OPT = %TRIM(FMOPT)
035700000000     C                   IF        %SUBST(F1OPT:1:1) = *ZEROS AND
035800000000     C                             %LEN(%TRIM(FMOPT)) = 2
035900000000     C                   EVAL      F1OPT = %SUBST(F1OPT:2)
036000000000     C                   ENDIF
036100000000     C*
036200000000     C                   EVAL      FMOPT = F1OPT
036300000000     C*
036400000000     C* Option = '*BLANK'
036500000000     C*
036600000000     C     F1OPT         CABEQ     *BLANKS       SCR012
036700000000     C*
036800000000     C                   EVAL      XXEND = *OFF
036900000000     C*
037000000000     C                   EVAL      RRS = RRN
037100000000     C*
037200000000     C* Option = 'CHANGE'
037300000000     C*
037400000000     C                   IF        F1OPT = cCHANGE AND
037500000000     C                             NOT XXENQ
037600000000     C*
037700000000     C                   EVAL      XXMODE = cCHANGE
037800000000     C                   EVAL      FMOPT = *BLANKS
037900000000     C                   EVAL      F1OPT = *BLANKS
038000000000     C                   UPDATE    XXXD04002
038100000000     C                   GOTO      SCR02
038200000000     C*
038300000000     C                   ENDIF
038400000000     C*
038500000000     C* Option = 'COPY'
038600000000     C*
038700000000     C                   IF        F1OPT = cCOPY  AND
038800000000     C                             NOT XXENQ
038900000000     C*
039000000000     C                   EVAL      XXMODE = cCOPY
039100000000     C                   EVAL      FMOPT = *BLANKS
039200000000     C                   EVAL      F1OPT = *BLANKS
039300000000     C                   EVAL      *IN10 = *ON
039400000000     C                   UPDATE    XXXD04002
039500000000     C                   EVAL      *IN10 = *OFF
039600000000     C                   EXSR      SR03
039700000000     C                   GOTO      SCR012
039800000000     C*
039900000000     C                   ENDIF
040000000000     C*
040100000000     C* Option = 'DELETE'
040200000000     C*
040300000000     C                   IF        F1OPT = cDELETE AND
040400000000     C                             NOT XXENQ
040500000000     C*
040600000000     C                   EVAL      XXMODE = cDELETE
040700000000     C                   EVAL      FMOPT = *BLANKS
040800000000     C                   EVAL      F1OPT = *BLANKS
040900000000     C                   EVAL      *IN10 = *ON
041000000000     C                   UPDATE    XXXD04002
041100000000     C                   EVAL      *IN10 = *OFF
041200000000     C                   EXSR      SR04
041300000000     C                   GOTO      SCR012
041400000000     C*
041500000000     C                   ENDIF
041600000000     C*
041700000000     C* Option = 'DISPLAY'
041800000000     C*
041900000000     C                   IF        F1OPT = cDISPLAY
042000000000     C                   EVAL      XXMODE = cDISPLAY
042100000000     C                   EVAL      FMOPT = *BLANKS
042200000000     C                   EVAL      F1OPT = *BLANKS
042300000000     C                   UPDATE    XXXD04002
042400000000     C                   GOTO      SCR02
042500000000     C                   ENDIF
042600000000     C*
042700221223     C                   ENDIF
042800221223     C*
042900000000     C* Display panels over records to be copied or deleted
043000000000     C*
043100000000     C                   EVAL      XXFUNC = *OFF
043200000000     C*
043300000000     C     SCR013        TAG
043400000000     C*
043500000000     C* Copy records ?
043600000000     C*
043700000000     C                   IF        RRM2 > *ZEROS
043800000000     C                   EVAL      XXFUNC = *ON
043900000000     C                   EVAL      XXEND = *OFF
044000000000     C                   WRITE     CLRDSP
044100000000     C                   GOTO      SCR03
044200000000     C                   ENDIF
044300000000     C*
044400000000     C* Delete records ?
044500000000     C*
044600000000     C                   IF        RRM3 > *ZEROS
044700000000     C                   EVAL      XXFUNC = *ON
044800000000     C                   EVAL      XXEND = *OFF
044900000000     C                   WRITE     CLRDSP
045000000000     C                   GOTO      SCR04
045100000000     C                   ENDIF
045200000000     C*
045300000000     C* Init panel ?
045400000000     C*
045500000000     C     XXFUNC        CABEQ     *ON           SCR01
045600000000     C     XXINIT        CABEQ     *ON           SCR01
045700000000     C*
045800000000     C* Set correct relative record number
045900000000     C*
046000000000     C                   IF        RRN > *ZEROS
046100000000     C                   EVAL      RRS = *ZEROS
046200000000     C                   ENDIF
046300000000     C*
046400000000     C* Exit panel ?
046500000000     C*
046600000000     C                   IF        XXEND
046700000000     C                   GOTO      SCR011
046800000000     C                   ELSE
046900000000     C                   GOTO      SCR011
047000000000     C                   ENDIF
047100000000     C/EJECT
047200000000     C**********************************************************************
047300000000     C*                                                                   **
047400000000     C*    Panel 2 = Display details over credit cards                    **
047500000000     C*                                                                   **
047600000000     C**********************************************************************
047700000000     C     SCR02         TAG
047800000000     C*
047900000000     C* Initiate panel
048000000000     C*
048100000000     C                   EXSR      SR22
048200000000     C*
048300000000     C     SCR021        TAG
048400000000     C*
048500000000     C* Display panel
048600000000     C*
048700000000     C                   EXFMT(E)  XXXD04004
048800000000     C*
048900000000     C                   EXSR      SR50
049000000000     C     XMSG50        CABEQ     *ON           SCR02
049100000000     C*
049200000000     C* Exit program ?
049300000000     C*
049400000000     C                   IF        *INKC
049500000000     C                   EVAL      XPCMD = '03'
049600000000     C                   GOTO      DD9999
049700000000     C                   ENDIF
049800000000     C*
049900000000     C* Previous panel ?
050000000000     C*
050100000000     C                   IF        *INKL
050200000000     C*
050300000000     C                   IF        XXINIT
050400000000     C                   GOTO      SCR01
050500000000     C                   ELSE
050600000000     C*
050700000000     C                   IF        RRS > *ZEROS
050800000000     C                   EVAL      RRN = RRS
050900000000     C                   ENDIF
051000000000     C*
051100000000     C                   GOTO      SCR011
051200000000     C                   ENDIF
051300000000     C*
051400000000     C                   ENDIF
051500000000     C*
051600000000     C* Re-fresh panel ?
051700000000     C*
051800000000     C     *INKE         CABEQ     *ON           SCR02
051900000000     C*
052000000000     C* Check entered data
052100000000     C*
052200000000     C                   IF        XXMODE <> cDISPLAY
052300000000     C                   EXSR      SR52
052400000000     C     XMSG52        CABEQ     *ON           SCR021
052500000000     C                   ENDIF
052600000000     C*
052700000000     C* Re-display panel ?
052800000000     C*
052900000000     C                   IF        FMCRCT <> XXCRCT
053000000000     C                   EVAL      XXCRCT = FMCRCT
053100000000     C                   GOTO      SCR021
053200000000     C                   ENDIF
053300000000     C*
053400000000     C* Update record
053500000000     C*
053600000000     C                   IF        XXMODE <> cDISPLAY
053700000000     C                   EXSR      SR32
053800000000     C                   ENDIF
053900000000     C*
054000000000     C                   IF        XXRDSP
054100000000     C*
054200000000     C                   WRITE     CLRDSP
054300000000     C*
054400000000     C                   IF        XXMODE = cADD
054500000000     C                   EVAL      XXOLDM = XXMODE
054600000000     C                   EVAL      XXMODE = cCHANGE
054700000000     C                   GOTO      SCR02
054800000000     C                   ELSE
054900000000     C                   GOTO      SCR021
055000000000     C                   ENDIF
055100000000     C*
055200000000     C                   ENDIF
055300000000     C*
055400000000     C* Old mode exists ?
055500000000     C*
055600000000     C                   IF        XXOLDM <> *BLANKS
055700000000     C                   EVAL      XXMODE = XXOLDM
055800000000     C                   EVAL      XXOLDM = *BLANKS
055900000000     C                   ENDIF
056000000000     C*
056100000000     C* Multiple add ?
056200000000     C*
056300000000     C                   IF        XXMULT
056400000000     C                   WRITE     CLRDSP
056500000000     C                   GOTO      SCR02
056600000000     C                   ENDIF
056700000000     C*
056800000000     C* Exit panel
056900000000     C*
057000000000     C                   GOTO      SCR012
057100000000     C/EJECT
057200000000     C**********************************************************************
057300000000     C*                                                                   **
057400000000     C*    Panel 3 = Display subfile over records to be copied            **
057500000000     C*                                                                   **
057600000000     C**********************************************************************
057700000000     C     SCR03         TAG
057800000000     C*
057900000000     C* Initiate panel
058000000000     C*
058100000000     C                   EVAL      *IN84 = *ON
058200000000     C                   EVAL      RRN2 = 1
058300000000     C                   EVAL      XXN40 = 1
058400000000     C                   EVAL      *IN63 = *ON
058500000000     C*
058600000000     C     SCR031        TAG
058700000000     C*
058800000000     C* Display panel
058900000000     C*
059000000000     C                   WRITE     XXXD04005
059100000000     C                   EXFMT(E)  XXXD04007
059200000000     C*
059300000000     C                   EXSR      SR50
059400000000     C     XMSG50        CABEQ     *ON           SCR03
059500000000     C*
059600000000     C* Exit program ?
059700000000     C*
059800000000     C                   IF        *INKC
059900000000     C                   EVAL      XPCMD = '03'
060000000000     C                   GOTO      DD9999
060100000000     C                   ENDIF
060200000000     C*
060300000000     C* Previous panel ?
060400000000     C*
060500000000     C                   IF        *INKL
060600000000     C                   EXSR      SR23
060700000000     C                   GOTO      SCR013
060800000000     C                   ENDIF
060900000000     C*
061000000000     C     SCR032        TAG
061100000000     C*
061200000000     C     XXN40         CABGT     RRM2          SCR033
061300000000     C*
061400000000     C* Read subfile (copy records)
061500000000     C*
061600000000     C     XXN40         CHAIN     XXXD04006
061700000000     C*
061800000000     C* Check entered data
061900000000     C*
062000000000     C                   EXSR      SR53
062100000000     C*
062200000000     C                   IF        XMSG53
062300000000     C                   UPDATE    XXXD04006
062400000000     C                   GOTO      SCR031
062500000000     C                   ENDIF
062600000000     C*
062700000000     C* Copy record
062800000000     C*
062900000000     C                   EXSR      SR33
063000000000     C*
063100000000     C* Update subfile
063200000000     C*
063300000000     C                   EVAL      *IN10 = *ON
063400000000     C                   UPDATE    XXXD04006
063500000000     C                   EVAL      *IN10 = *OFF
063600000000     C                   EVAL      XXN40 = XXN40 + 1
063700000000     C*
063800000000     C                   GOTO      SCR032
063900000000     C*
064000000000     C     SCR033        TAG
064100000000     C*
064200000000     C* Initiate subfile
064300000000     C*
064400000000     C                   EXSR      SR23
064500000000     C*
064600000000     C* Exit panel
064700000000     C*
064800000000     C                   GOTO      SCR013
064900000000     C/EJECT
065000000000     C**********************************************************************
065100000000     C*                                                                   **
065200000000     C*    Panel 4 = Display subfile over records to be deleted           **
065300000000     C*                                                                   **
065400000000     C**********************************************************************
065500000000     C     SCR04         TAG
065600000000     C*
065700000000     C* Initiate panel
065800000000     C*
065900000000     C                   EVAL      *IN84 = *ON
066000000000     C                   EVAL      RRN3 = 1
066100000000     C                   EVAL      *IN64 = *ON
066200000000     C*
066300000000     C* Display panel
066400000000     C*
066500000000     C                   WRITE     XXXD04008
066600000000     C                   EXFMT(E)  XXXD04010
066700000000     C*
066800000000     C                   EXSR      SR50
066900000000     C     XMSG50        CABEQ     *ON           SCR04
067000000000     C*
067100000000     C* Exit program ?
067200000000     C*
067300000000     C                   IF        *INKC
067400000000     C                   EVAL      XPCMD = '03'
067500000000     C                   GOTO      DD9999
067600000000     C                   ENDIF
067700000000     C*
067800000000     C* Previous panel ?
067900000000     C*
068000000000     C                   IF        *INKL
068100000000     C                   EXSR      SR24
068200000000     C                   GOTO      SCR013
068300000000     C                   ENDIF
068400000000     C*
068500000000     C* Delete records
068600000000     C*
068700000000     C                   EXSR      SR44
068800000000     C*
068900000000     C* Initiate subfile
069000000000     C*
069100000000     C                   EXSR      SR24
069200000000     C*
069300000000     C* Exit panel
069400000000     C*
069500000000     C                   GOTO      SCR013
069600000000     C/EJECT
069700000000     C**********************************************************************
069800000000     C*                                                                   **
069900000000     C*    End of program flow.                                           **
070000000000     C*                                                                   **
070100000000     C**********************************************************************
070200000000     C     DD9999        TAG
070300000000     C*
070400000000     C                   EVAL      *INLR = *ON
070500000000     C/EJECT
070600000000     C**********************************************************************
070700000000     C*                                                                   **
070800000000     C*    SR01 = Load subfile over credit cards                          **
070900000000     C*                                                                   **
071000000000     C**********************************************************************
071100000000     C     SR01          BEGSR
071200000000     C*
071300000000     C                   EVAL      RRN = RRM
071400000000     C                   EVAL      XXN40 = *ZEROS
071500000000     C*
071600000000     C* Set XXMXRC to be between 80 and 100
071700000000     C*
071800000000     C                   EVAL      XXMXRC = XWNOL * 7
071900000000     C*
072000221223     C     K1BCTLXX      SETLL     XXBCTLXX
072100221223     C                   READ(N)   XXBCTLXX
072200000000     C*
072300221223     C                   DOW       NOT %EOF(XXBCTLXX)  AND
072400000000     C                             XXN40 < XXMXRC
072500000000     C*
072600000000     C* Card type
072700000000     C*
072800000000     C                   IF        F1CRCT = *BLANKS OR
072900000000     C                             F1CRCT <> *BLANKS AND
073000221223     C                             F1CRCT = XXCRCT
073100000000     C*
073200000000     C* Initialise for search on description
073300000000     C*
073400000000     C                   EVAL      XXSEARCH = *ON
073500000000     C*
073600000000     C* Perform search on records
073700000000     C*
073800000000     C                   IF        F1CADC <> *BLANKS
073900000000     C*
074000000000     C* Indicator XXSEARCH is set to *OFF,
074100000000     C* if record does not meet search arguement
074200000000     C*
074300221223     C                   EVAL      XPXLAT = XXCADC
074400000000     C                   CALL      'QDCXLATE'
074500221223     C                   PARM                    XPFLEN            5 0
074600221223     C                   PARM                    XPXLAT           80
074700221223     C                   PARM                    XPASWT           10
074800000000     C                   EVAL      X4CADC = XPXLAT
074900000000     C*
075000000000     C     X3CADC:SL     SCAN      X4CADC        LP
075100000000     C*
075200000000     C                   IF        NOT %FOUND
075300000000     C                   EVAL      XXSEARCH = *OFF
075400000000     C                   ENDIF
075500000000     C*
075600000000     C                   ENDIF
075700000000     C*
075800000000     C                   IF        XXSEARCH
075900000000     C                   EVAL      FMOPT = *BLANKS
076000221223     C                   EVAL      FMCARD = XXCARD
076100221223     C                   EVAL      UI_XXAFF1 = XXAFF1
076200221223     C                   EVAL      UI_XXAFF2 = XXAFF2
076300221223     C                   EVAL      UI_XXAFF3 = XXAFF3
076400221223     C                   EVAL      UI_XXAFF4 = XXAFF4
076500221223     C                   EVAL      UI_XXAFF5 = XXAFF5
076600221223     C                   EVAL      UI_XXNFF1 = XXNFF1
076700221223     C                   EVAL      UI_XXNFF2 = XXNFF2
076800221223     C                   EVAL      UI_XXNFF3 = XXNFF3
076900221223     C                   EVAL      UI_XXNFF4 = XXNFF4
077000221223     C                   EVAL      UI_XXNFF5 = XXNFF5
077100000000     C                   EVAL      RRN = RRN + 1
077200000000     C                   EVAL      RRM = RRM + 1
077300000000     C                   EVAL      XXN40 = XXN40 + 1
077400000000     C                   EVAL      *IN10 = *OFF
077500000000     C                   EVAL      *IN12 = *OFF
077600000000     C                   WRITE     XXXD04002
077700000000     C                   ENDIF
077800000000     C*
077900000000     C                   ENDIF
078000000000     C*
078100180925     C                   IF        RRN >= 9999
078200221223     C                   EVAL      ERRMSG = 'Maximum records reached'
078300000000     C                   EVAL      *IN61 = *ON
078400000000     C                   EVAL      RRS = *ZEROS
078500000000     C                   LEAVESR
078600000000     C                   ENDIF
078700000000     C*
078800221223     C                   READ(N)   XXBCTLXX
078900000000     C                   ENDDO
079000000000     C*
079100221223     C                   IF        NOT %EOF(XXBCTLXX)
079200221223     C                   EVAL      K1CARD = XXCARD
079300000000     C                   ELSE
079400000000     C                   MOVE      *HIVAL        K1CARD
079500000000     C                   EVAL      *IN61 = *ON
079600000000     C                   ENDIF
079700000000     C*
079800000000     C                   EVAL      RRS = *ZEROS
079900000000     C*
080000000000     C                   IF        XXN40 <> *ZEROS
080100000000     C                   EVAL      RRN = RRN - XXN40 + 1
080200000000     C                   ENDIF
080300000000     C*
080400000000     C                   ENDSR
080500000000     C/EJECT
080600000000     C**********************************************************************
080700000000     C*                                                                   **
080800000000     C*    SR03 = Load subfile over records to be copied                  **
080900000000     C*                                                                   **
081000000000     C**********************************************************************
081100000000     C     SR03          BEGSR
081200000000     C*
081300000000     C                   EVAL      XXCARD = FMCARD
081400000000     C                   EVAL      FMCARD = *BLANKS
081500000000     C*
081600000000     C                   EVAL      RRN2 = RRN2 + 1
081700000000     C                   EVAL      RRM2 = RRM2 + 1
081800000000     C*
081900000000     C                   WRITE     XXXD04006
082000000000     C*
082100000000     C                   ENDSR
082200000000     C/EJECT
082300000000     C**********************************************************************
082400000000     C*                                                                   **
082500000000     C*    SR04 = Load subfile over records to be deleted                 **
082600000000     C*                                                                   **
082700000000     C**********************************************************************
082800000000     C     SR04          BEGSR
082900000000     C*
083000000000     C                   EVAL      RRN3 = RRN3 + 1
083100000000     C                   EVAL      RRM3 = RRM3 + 1
083200000000     C*
083300000000     C                   WRITE     XXXD04009
083400000000     C*
083500000000     C                   ENDSR
083600000000     C/EJECT
083700000000     C**********************************************************************
083800000000     C*                                                                   **
083900000000     C*    SR21 = Initiate subfile over credit cards                      **
084000000000     C*                                                                   **
084100000000     C**********************************************************************
084200000000     C     SR21          BEGSR
084300000000     C*
084400000000     C                   EVAL      *IN85 = *ON
084500000000     C                   WRITE     XXXD04003
084600000000     C                   EVAL      *IN85 = *OFF
084700000000     C*
084800000000     C                   WRITE     CLRDSP
084900000000     C*
085000000000     C                   EVAL      *IN61 = *OFF
085100000000     C*
085200000000     C                   EVAL      RRN = *ZEROS
085300000000     C                   EVAL      RRM = *ZEROS
085400000000     C                   EVAL      RRS = *ZEROS
085500000000     C*
085600000000     C                   EVAL      FMADD = *BLANKS
085700230331DBLE C***                EVAL      FMUSER= LDUSER
085800230331DBLE C***
085900230331DBLE C***                EVAL      KKUSER= LDUSER
086000230331DBLE C***  KKBUSP        CHAIN     SRBUSP
086100230331DBLE C***                IF        %FOUND(SRBUSP)
086200230331DBLE C***                EVAL      FMCONT = UPDESC
086300230331DBLE C***                ENDIF
086400230331NBLE C                   EVAL      FMUSER = 'INBHALAW'
086500230331NBLE C                   EVAL      FMCONT = 'Bhalchandra'
086600230307     C*
086700000000     C                   EVAL      F1ADD = *BLANKS
086800000000     C*
086900000000     C                   EVAL      K1CARD = F1CARD
087000000000     C*
087100000000     C                   EVAL      X1CARD = F1CARD
087200000000     C                   EVAL      X1CADC = F1CADC
087300000000     C                   EVAL      X1CRCT = F1CRCT
087400000000     C*
087500000000     C* If description entered, translate to uppercase
087600000000     C*
087700000000     C                   IF        F1CADC <> *BLANKS
087800000000     C*
087900000000     C* Find last used position in search string
088000000000     C*
088100000000     C     ' '           CHECKR    F1CADC        SL
088200000000     C*
088300000000     C                   ENDIF
088400000000     C*
088500000000     C                   ENDSR
088600000000     C/EJECT
088700000000     C**********************************************************************
088800000000     C*                                                                   **
088900000000     C*    SR22 = Moves file data to panel fields                         **
089000000000     C*                                                                   **
089100000000     C**********************************************************************
089200000000     C     SR22          BEGSR
089300000000     C*
089400000000     C* Mode = 'ADD'
089500000000     C*
089600000000     C                   IF        XXMODE = cADD
089700000000     C*
089800000000     C                   EVAL      FMCARD = *BLANKS
089900000000     C                   EVAL      FMCADC = *BLANKS
090000000000     C                   EVAL      FMCRCT = *BLANKS
090100000000     C                   EVAL      XXDESC = *BLANKS
090200000000     C                   EVAL      FMAFF1 = *BLANKS
090300000000     C                   EVAL      FMAFF2 = *BLANKS
090400000000     C                   EVAL      FMAFF3 = *BLANKS
090500000000     C                   EVAL      FMAFF4 = *BLANKS
090600000000     C                   EVAL      FMAFF5 = *BLANKS
090700000000     C                   EVAL      FMNFF1 = *ZEROS
090800000000     C                   EVAL      FMNFF2 = *ZEROS
090900000000     C                   EVAL      FMNFF3 = *ZEROS
091000000000     C                   EVAL      FMNFF4 = *ZEROS
091100000000     C                   EVAL      FMNFF5 = *ZEROS
091200000000     C*
091300000000     C* Non-protect of key and other fields
091400000000     C*
091500000000     C                   EVAL      *IN70 = *OFF
091600000000     C                   EVAL      *IN71 = *OFF
091700000000     C*
091800000000     C                   ENDIF
091900000000     C*
092000000000     C* Mode = 'CHANGE' or 'DISPLAY'
092100000000     C*
092200000000     C                   IF        XXMODE = cCHANGE OR
092300000000     C                             XXMODE = cDISPLAY
092400000000     C*
092500000000     C                   EVAL      KKCARD = FMCARD
092600221223     C     KKBCTLXX      CHAIN(N)  XXBCTLXX
092700000000     C*
092800221223     C                   EVAL      FMCADC = XXCADC
092900221223     C                   EVAL      FMCRCT = XXCRCT
093000221223     C                   EVAL      FMAFF1 = XXAFF1
093100221223     C                   EVAL      FMAFF2 = XXAFF2
093200221223     C                   EVAL      FMAFF3 = XXAFF3
093300221223     C                   EVAL      FMAFF4 = XXAFF4
093400221223     C                   EVAL      FMAFF5 = XXAFF5
093500221223     C                   EVAL      FMNFF1 = XXNFF1
093600221223     C                   EVAL      FMNFF2 = XXNFF2
093700221223     C                   EVAL      FMNFF3 = XXNFF3
093800221223     C                   EVAL      FMNFF4 = XXNFF4
093900221223     C                   EVAL      FMNFF5 = XXNFF5
094000000000     C*
094100000000     C* Retrive description for 'card type'
094200000000     C*
094300000000     C                   EVAL      KKCRCT = FMCRCT
094400221223     C     KKBCTLCE      CHAIN     XXBCTLCE
094500000000     C*
094600221223     C                   IF        %FOUND(XXBCTLCE)
094700000000     C                   ELSE
094800000000     C                   EVAL      XXDESC = *BLANKS
094900000000     C                   ENDIF
095000000000     C*
095100000000     C* Protect of key field
095200000000     C*
095300000000     C                   EVAL      *IN70 = *ON
095400000000     C*
095500000000     C* Protect all fields ?
095600000000     C*
095700000000     C                   IF        XXMODE = cDISPLAY
095800000000     C                   EVAL      *IN71 = *ON
095900000000     C                   ELSE
096000000000     C                   EVAL      *IN71 = *OFF
096100000000     C                   ENDIF
096200000000     C*
096300000000     C                   ENDIF
096400000000     C*
096500000000     C* Save 'card type' field
096600000000     C*
096700000000     C                   EVAL      XXCRCT = FMCRCT
096800000000     C*
096900000000     C                   ENDSR
097000000000     C/EJECT
097100000000     C**********************************************************************
097200000000     C*                                                                   **
097300000000     C*    SR23 = Initiate subfile records to be copied                   **
097400000000     C*                                                                   **
097500000000     C**********************************************************************
097600000000     C     SR23          BEGSR
097700000000     C*
097800000000     C                   EVAL      *IN85 = *ON
097900000000     C                   WRITE     XXXD04007
098000000000     C                   EVAL      *IN85 = *OFF
098100000000     C*
098200000000     C                   EVAL      RRN2 = *ZEROS
098300000000     C                   EVAL      RRM2 = *ZEROS
098400000000     C*
098500000000     C                   ENDSR
098600000000     C/EJECT
098700000000     C**********************************************************************
098800000000     C*                                                                   **
098900000000     C*    SR24 = Initiate subfile records to be deleted                  **
099000000000     C*                                                                   **
099100000000     C**********************************************************************
099200000000     C     SR24          BEGSR
099300000000     C*
099400000000     C                   EVAL      *IN85 = *ON
099500000000     C                   WRITE     XXXD04010
099600000000     C                   EVAL      *IN85 = *OFF
099700000000     C*
099800000000     C                   EVAL      RRN3 = *ZEROS
099900000000     C                   EVAL      RRM3 = *ZEROS
100000000000     C*
100100000000     C                   ENDSR
100200000000     C/EJECT
100300000000     C**********************************************************************
100400000000     C*                                                                   **
100500000000     C*    SR32 = Update / add record                                     **
100600000000     C*                                                                   **
100700000000     C**********************************************************************
100800000000     C     SR32          BEGSR
100900000000     C*
101000000000     C                   EVAL      KKCARD = FMCARD
101100221223     C     KKBCTLXX      CHAIN     XXBCTLXX
101200000000     C*
101300221223     C                   IF        NOT %FOUND(XXBCTLXX)
101400221223     C                   CLEAR                   XXCTL
101500000000     C                   ENDIF
101600000000     C*
101700221223     C                   EVAL      XXCARD = FMCARD
101800221223     C                   EVAL      XXCADC = FMCADC
101900221223     C                   EVAL      XXCRCT = FMCRCT
102000221223     C                   EVAL      XXAFF1 = FMAFF1
102100221223     C                   EVAL      XXAFF2 = FMAFF2
102200221223     C                   EVAL      XXAFF3 = FMAFF3
102300221223     C                   EVAL      XXAFF4 = FMAFF4
102400221223     C                   EVAL      XXAFF5 = FMAFF5
102500221223     C                   EVAL      XXNFF1 = FMNFF1
102600221223     C                   EVAL      XXNFF2 = FMNFF2
102700221223     C                   EVAL      XXNFF3 = FMNFF3
102800221223     C                   EVAL      XXNFF4 = FMNFF4
102900221223     C                   EVAL      XXNFF5 = FMNFF5
103000000000     C*
103100221223     C                   IF        %FOUND(XXBCTLXX)
103200221223     C                   UPDATE    XXCTL
103300000000     C                   ELSE
103400221223     C                   WRITE     XXCTL
103500000000     C                   ENDIF
103600000000     C*
103700000000     C* Update initiation field
103800000000     C*
103900221223     C                   IF        NOT %FOUND(XXBCTLXX)
104000000000     C                   EVAL      XXINIT = *ON
104100000000     C                   ENDIF
104200000000     C*
104300000000     C* Update subfile record
104400000000     C*
104500000000     C                   IF        XXMODE <> cADD AND
104600000000     C                             XXOLDM <> cADD AND
104700000000     C                             NOT XXMULT
104800000000     C     RRN           CHAIN     XXXD04002
104900221223     C                   EVAL      XXCADC = FMCADC
105000221223     C                   EVAL      XXCRCT = FMCRCT
105100221223     C                   EVAL      UI_XXAFF1 = FMAFF1
105200221223     C                   EVAL      UI_XXAFF2 = FMAFF2
105300221223     C                   EVAL      UI_XXAFF3 = FMAFF3
105400221223     C                   EVAL      UI_XXAFF4 = FMAFF4
105500221223     C                   EVAL      UI_XXAFF5 = FMAFF5
105600221223     C                   EVAL      UI_XXNFF1 = FMNFF1
105700221223     C                   EVAL      UI_XXNFF2 = FMNFF2
105800221223     C                   EVAL      UI_XXNFF3 = FMNFF3
105900221223     C                   EVAL      UI_XXNFF4 = FMNFF4
106000221223     C                   EVAL      UI_XXNFF5 = FMNFF5
106100000000     C                   UPDATE    XXXD04002
106200000000     C                   ENDIF
106300000000     C*
106400000000     C                   ENDSR
106500000000     C/EJECT
106600000000     C**********************************************************************
106700000000     C*                                                                   **
106800000000     C*    SR33 = Copy data                                               **
106900000000     C*                                                                   **
107000000000     C**********************************************************************
107100000000     C     SR33          BEGSR
107200000000     C*
107300000000     C                   EVAL      KKCARD = XXCARD
107400221223     C     KKBCTLXX      CHAIN(N)  XXBCTLXX
107500000000     C*
107600221223     C                   IF        %FOUND(XXBCTLXX)
107700221223     C                   EVAL      XXCARD = FMCARD
107800221223     C                   WRITE     XXCTL
107900000000     C                   ENDIF
108000000000     C*
108100000000     C* Update initiation field
108200000000     C*
108300000000     C                   EVAL      XXINIT = *ON
108400000000     C*
108500000000     C                   ENDSR
108600000000     C/EJECT
108700000000     C**********************************************************************
108800000000     C*                                                                   **
108900000000     C*    SR44 = Delete records                                          **
109000000000     C*                                                                   **
109100000000     C**********************************************************************
109200000000     C     SR44          BEGSR
109300000000     C*
109400000000     C* Read subfile over records to be deleted
109500000000     C*
109600000000     C     1             DO        RRM3          RRN3
109700000000     C*
109800000000     C     RRN3          CHAIN     XXXD04009
109900000000     C*
110000000000     C                   EVAL      KKCARD = FMCARD
110100221223     C     KKBCTLXX      CHAIN     XXBCTLXX
110200000000     C*
110300221223     C                   IF        %FOUND(XXBCTLXX)
110400000000     C*
110500221223     C                   DELETE    XXCTL
110600000000     C*
110700000000     C* Update initiation field
110800000000     C*
110900000000     C                   EVAL      XXINIT = *ON
111000000000     C*
111100000000     C                   ENDIF
111200000000     C*
111300000000     C                   ENDDO
111400000000     C*
111500000000     C                   ENDSR
111600000000     C/EJECT
111700000000     C**********************************************************************
111800000000     C*                                                                   **
111900000000     C*    SR50 = Setof error indicators                                  **
112000000000     C*                                                                   **
112100000000     C**********************************************************************
112200000000     C     SR50          BEGSR
112300000000     C*
112400000000     C                   MOVEA     '0000000000'  *IN(01)
112500000000     C                   MOVEA     '0000000000'  *IN(11)
112600000000     C                   MOVEA     '0000000000'  *IN(21)
112700000000     C                   MOVEA     '0'           *IN(31)
112800000000     C*
112900000000     C* Reset cursor position
113000000000     C*
113100000000     C                   EVAL      XXCSLI = *ZEROS
113200000000     C                   EVAL      XXCSCO = *ZEROS
113300000000     C*
113400000000     C                   IF        NOT XXPC01
113500000000     C                   EVAL      XXSETP = *ON
113600000000     C                   EVAL      XXPC01 = *ON
113700000000     C                   ENDIF
113800000000     C*
113900000000     C* Reset status message fields
114000000000     C*
114100000000     C                   EVAL      XMSG50 = *OFF
114200000000     C                   EVAL      XMSG51 = *OFF
114300000000     C                   EVAL      XMSG52 = *OFF
114400000000     C                   EVAL      XMSG53 = *OFF
114500000000     C                   EVAL      XMSG55 = *OFF
114600000000     C                   EVAL      XMSG56 = *OFF
114700000000     C                   EVAL      XMSGENQ = *OFF
114800221223     C                   EVAL      ERRMSG  = *BLANKS
114900000000     C*
115000000000     C                   ENDSR
115100000000     C/EJECT
115200000000     C**********************************************************************
115300000000     C*                                                                   **
115400000000     C*    SR51 = Check data from selection panel                         **
115500000000     C*                                                                   **
115600000000     C**********************************************************************
115700000000     C     SR51          BEGSR
115800000000     C*
115900000000     C* If Description entered, translate to uppercase
116000000000     C*
116100000000     C                   IF        F1CADC <> *BLANKS
116200000000     C*
116300000000     C* Translate to uppercase for SCAN  "scan text"
116400000000     C*
116500000000     C                   EVAL      XPXLAT = F1CADC
116600000000     C                   CALL      'QDCXLATE'
116700000000     C                   PARM                    XPFLEN
116800000000     C                   PARM                    XPXLAT
116900000000     C                   PARM                    XPASWT
117000000000     C                   EVAL      X3CADC = XPXLAT
117100000000     C*
117200000000     C* Find last used position in search string
117300000000     C*
117400000000     C     ' '           CHECKR    F1CADC        SL
117500000000     C*
117600000000     C                   ENDIF
117700000000     C*
117800000000     C* Check card type
117900000000     C*
118000000000     C                   IF        F1CRCT <> *BLANKS
118100000000     C*
118200000000     C                   EVAL      KKCRCT = F1CRCT
118300221223     C     KKBCTLCE      CHAIN     XXBCTLCE
118400000000     C*
118500221223     C                   IF        NOT %FOUND(XXBCTLCE)
118600000000     C                   EVAL      *IN03  = *ON
118700000000     C                   EVAL      XMSG51 = *ON
118800221223     C                   EVAL      ERRMSG = 'Credit card type does not exist'
118900000000     C                   ENDIF
119000000000     C*
119100000000     C                   ENDIF
119200000000     C*
119300000000     C                   ENDSR
119400000000     C/EJECT
119500000000     C**********************************************************************
119600000000     C*                                                                   **
119700000000     C*    SR52 = Check data from detail panel                            **
119800000000     C*                                                                   **
119900000000     C**********************************************************************
120000000000     C     SR52          BEGSR
120100000000     C*
120200000000     C* File (only if 'ADD' mode)
120300000000     C*
120400000000     C                   IF        XXMODE = cADD
120500000000     C*
120600000000     C                   EVAL      KKCARD = FMCARD
120700221223     C     KKBCTLXX      CHAIN(N)  XXBCTLXX
120800000000     C*
120900221223     C                   IF        %FOUND(XXBCTLXX)
121000000000     C                   EVAL      *IN01  = *ON
121100000000     C                   EVAL      XMSG52 = *ON
121200221223     C                   EVAL      ERRMSG = 'Credit card already exists'
121300000000     C                   ENDIF
121400000000     C*
121500000000     C                   IF        FMCARD = *BLANKS
121600221223     C                   EVAL      *IN01  = *ON
121700000000     C                   EVAL      XMSG52 = *ON
121800221223     C                   EVAL      ERRMSG = 'Credit card must be entered'
121900000000     C                   ENDIF
122000000000     C*
122100000000     C                   ENDIF
122200000000     C*
122300000000     C* Description
122400000000     C*
122500000000     C                   IF        FMCADC = *BLANKS
122600221223     C                   EVAL      *IN02  = *ON
122700000000     C                   EVAL      XMSG52 = *ON
122800221223     C                   EVAL      ERRMSG = 'Description must be entered'
122900000000     C                   ENDIF
123000000000     C*
123100000000     C                   ENDSR
123200000000     C/EJECT
123300000000     C**********************************************************************
123400000000     C*                                                                   **
123500000000     C*    SR53 = Check data from copy panel                              **
123600000000     C*                                                                   **
123700000000     C**********************************************************************
123800000000     C     SR53          BEGSR
123900000000     C*
124000000000     C* File
124100000000     C*
124200000000     C                   EVAL      KKCARD = FMCARD
124300221223     C     KKBCTLXX      CHAIN(N)  XXBCTLXX
124400000000     C*
124500221223     C                   IF        %FOUND(XXBCTLXX)
124600000000     C                   EVAL      XMSG53 = *ON
124700221223     C                   EVAL      ERRMSG = 'Credit card already exists'
124800000000     C                   ENDIF
124900000000     C*
125000000000     C                   IF        FMCARD = *BLANKS
125100000000     C                   EVAL      XMSG53 = *ON
125200221223     C                   EVAL      ERRMSG = 'Credit card must be entered'
125300000000     C                   ENDIF
125400000000     C*
125500000000     C                   ENDSR
125600000000     C/EJECT
