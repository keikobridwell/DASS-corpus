# CWB Encoding Instructions

To load the verticalized text file DASS_CWP_2023.txt (under "Releases") onto a CWB server, load the file into your current directory (within the corpus server) and run the following code:

```mkdir /data/corpora/cwb/dass2023

cwb-encode -xsBv -d /data/corpora/cwb/dass2023 -f DASS_CQP_2023.txt -R /usr/local/share/cwb/registry/dass2023

cwb-encode -xsBv -d /data/corpora/cwb/dass2023 -f DASS_CQP_2023.txt -R /usr/local/share/cwb/registry/dass2023 -P pos -P lemma -P speaker -P sector -P location -P state -P gender -P age -P agelevel -P socialstatus -P education -P ethnicity -P worldview -P lagsclass -P dasstype

cwb-make -V DASS2023
