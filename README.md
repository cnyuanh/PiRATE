# PiRATE
Welcome to the PiRATE wiki!

PiRATE (a Pipeline to Retrieve and Annotate Transposable Elements) can not be download on Github but on SEANOE (Sea scientific open data publication).

Each tools used by PiRATE are automated into a stand-alone Galaxy. This PiRATE-Galaxy can be used through a Virtual Machine.

http://doi.org/10.17882/51795

Thus, you only have to download the Virtual Machine and to run it with a Virtual Machine Monitor such as Virtual Box: https://www.virtualbox.org/

The PiRATE tutorial is available here:

http://archimer.ifremer.fr/doc/00412/52373/

PiRATE notably integrate:

STEP I) TE DETECTION

Approach 1: Similarity-based

RepeatMasker www.repeatmasker.org/ (Smit et al. 1996)
TE-HMMER
Approach 2: Structural-based

LTRharvest http://www.zbh.uni-hamburg.de/?id=206 (Ellinghaus et al., 2008)
MGEScan-nonLTR http://mgescan.readthedocs.io/en/latest/nonltr.html (Rho and Tang, 2009)
Helsearch http://omictools.com/helsearch-tool (Yang and Bennetzen, 2009)
MITE-Hunter http://target.iplantcollaborative.org/mite_hunter.html (Han and Wessler, 2010)
SINEfinder http://www.plantcell.org/content/23/9/3117 (Wenke et al., 2011)
Approach 3: Repetitiveness-based

TEdenovo https://urgi.versailles.inra.fr/Tools/REPET (Flutre et al., 2011)
RepeatScout https://bix.ucsd.edu/repeatscout/ (Price et al., 2005)
Approach 4: Build repeated elements

RepeatExplorer http://repeatexplorer.umbr.cas.cz/ (Novak et al., 2013)
dnaPipeTE https://lbbe.univ-lyon1.fr/-dnaPipeTE-.html (Goubert et al., 2015)
RepARK https://github.com/PhKoch/RepARK (Koch et al., 2014)
STEP II) TE Classification

PASTEC https://urgi.versailles.inra.fr/Tools/PASTEClassifier (Hoede et al., 2014)
STEP III) TE annotation

TEannot https://urgi.versailles.inra.fr/Tools/REPET
Why PiRATE ?

To date, genome assembly of non-model organisms is usually not at chromosomal level and is higly fragmented. This fragmentation is recognized to be, in part, the result of a bad assembly of the transposable elements (TEs) copies, increasing the difficulty to detect and annotate them.

In this context, we designed a new bioinformatics pipeline named PiRATE for detect, classify and annotate TEs of non-model organisms. We optimized its detection step by gathering every existing TE detection approaches. The goal is to promote the detection of complete TE sequences of every TE families. The detection of complete TE sequences, bearing recognizable conserved domains or specific motifs, allows to facilitate the classification step. The classification step of PiRATE has been improved for algal genomes.

This PiRATE-Galaxy is a suitable and flexible platform to study TEs in the genome of every organisms.