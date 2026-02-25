{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Arial-BoldMT;\f1\fswiss\fcharset0 ArialMT;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red109\green109\blue109;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\cssrgb\c50196\c50196\c50196;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}
{\list\listtemplateid5\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid401\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid5}
{\list\listtemplateid6\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid501\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid6}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}{\listoverride\listid5\listoverridecount0\ls5}{\listoverride\listid6\listoverridecount0\ls6}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa321\partightenfactor0

\f0\b\fs48 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 STOP Logic Specification\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 Version 1.0\uc0\u8232 EIM Operational Engine\u8232 Specification Baseline \'97 Version 1.0\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \strokec2 1. Purpose\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 The STOP Logic Specification defines deterministic enforcement behavior when integrity violations occur within High-Integrity Operating Mode (HIOM).\
STOP logic ensures that Assumption Events do not resolve silently and that reasoning gaps are surfaced before continuation.\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \strokec2 2. Enforcement States\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 HIOM supports two enforcement states:\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 \strokec2 2.1 HARD STOP\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 Reasoning may not continue until the violation is resolved or formally overridden.\
HARD STOP conditions are triggered by:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls1\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Missing Input Assumption (MIA)\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Default Value Insertion (DVI)\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Undeclared Boundary Condition (UBC)\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Similarity Carryover Assumption (SCA)\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Undisclosed Derivation (UD)\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Life-safety Extrapolation Assumption (EA)\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 \strokec2 2.2 Validation Required\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 Reasoning may continue only after explicit acknowledgment of the identified risk.\
Validation Required conditions are triggered by:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls2\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Contextual Inference Assumption (CIA)\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Non-life-safety Extrapolation Assumption (EA)\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \strokec2 Validation Required does not block reasoning but prevents silent acceptance.\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \strokec2 3. Override Protocol\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 When a HARD STOP condition occurs, continuation requires:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls3\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Explicit override selection\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Structured justification statement\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Acknowledgment of potential risk implications\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Logged record of override event\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \strokec2 Override does not remove the violation from the session log.\
Override authority remains with the engineer.\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \strokec2 4. Life-Safety Sensitivity\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 If life-safety relevance has been declared at HIOM activation:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls4\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Certain Validation Required conditions may escalate to HARD STOP\
\ls4\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Extrapolation beyond validated ranges defaults to HARD STOP\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \strokec2 This sensitivity is rule-based and deterministic within this baseline.\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \strokec2 5. Logging Requirements\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 Each enforcement event must record:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls5\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Event type\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Triggering condition\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Timestamp\
\ls5\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Engineer response (resolve, override, acknowledge)\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \strokec2 Logging in Version 1.0 is local to the reasoning session. Enterprise escalation mechanisms are not defined in this baseline.\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \strokec2 6. Boundary Conditions\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 STOP logic:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls6\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Does not evaluate correctness\
\ls6\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Does not compute engineering validity\
\ls6\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Does not substitute for professional judgment\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \strokec2 It enforces structural reasoning integrity only.\
\pard\pardeftab720\partightenfactor0
\cf3 \strokec3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 \strokec2 7. Version Scope\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 \strokec2 This document defines complete enforcement behavior for Specification Baseline Version 1.0.\
Future revisions may expand escalation logic or introduce adaptive enforcement mechanisms.\
}