---
layout: post
author: brant
---

Authors
-------

Michael E. Alfaro :sup:`*1^`, Brant C. Faircloth :sup:`*1`, Laurie
Sorenson :sup:`1`, Francesco Santini :sup:`1`, John P.  Huelsenbeck :sup:`2`,
Jonathan Chang :sup:`1`

    | 1 Department of Ecology and Evolutionary Biology, University of California, Los Angeles, CA 90095, USA
    | 2 Department of Integrative Biology, University of California, Berkeley, CA 94720-3140, USA
    | * These authors contributed equally to this work
    | ^ Corresponding author

Abstract
--------

Teleosts constitute over 99% of all fish and more than half of all
vertebrates, yet fundamental questions regarding the origin and
diversifiaction of this vast radiation remain unanswered. Here, we
present the first phylogenomic study of the relationships among ancient
teleost lineages using a novel, targeted enrichment approach to collect
data from hundreds of ultraconserved nuclear DNA elements and their
flanking sequence across the major lineages of ray-finned fishes. We
analyse these  UCE data with a novel Bayesian hierarchical phylogenetic
model that relaxes the requirement of defining gene partitions a priori,
and we recover a well-supported phylogeny that differs from other
molecular studies in supporting the elopomorphs as the sister group to
other teleosts. Our analyses suggest that data sets derived from
targeted enrichment of UCEs have strong phylogenetic resolving power at
both shallow and deep nodes and that Bayesian HPMs offer an efficient
way for analysing these data.

License
-------

Data generated as part of the research listed above data are available
under the `CC0 1.0 Universal (CC0 1.0) Public Domain Dedication
license <http://creativecommons.org/publicdomain/zero/1.0/>`_.  We 
denote data that we have generated using an
**asterisk** (*) below. Data from other research projects (genome
sequences) are available under their respective license.  Please see the
license terms for these data sources by visiting the URLs listed in
Supplementary Table 1.

The CC0 license does not waive our expectation that you will cite either
these data or their associated publication following normal, scholarly
practices.

Data
----

- `fish-500-uce-loci-probes-4X-tiling <http://cloud.faircloth-lab.org/2U2m2F0U340s2k171r2c/content>`_ (fasta)
- `fish-probe-matches-to-genome-enabled-taxa <http://cloud.faircloth-lab.org/2I0r2p2V3X2Q02470O1W/content>`_ (lastz.bz2)
- `fish-genome-enabled-contigs-matching-uce-loci <http://cloud.faircloth-lab.org/3j022d2Q2J0p2M1b1t2b/content>`_ (sqlite.bz2)
- `fish-contigs-following-enrichment <http://cloud.faircloth-lab.org/1S0T3U0L2W3V1V0g3y3e/content>`_ (fasta.bz2)*
- `fish-contigs-matches-to-uce-loci <http://cloud.faircloth-lab.org/1p413o2p3p202F380b0D/content>`_ (lastz.bz2)*
- `fish-contigs-matching-UCE-anchored-loci <http://cloud.faircloth-lab.org/4745042h2l2F3q3S1s0O/content>`_ (sqlite.bz2)*
- `fish-substitution-model-data-for-uce-loci <http://cloud.faircloth-lab.org/2y3N351O1O2Z0x1b3G2I/content>`_ (tre/txt bz2)*
- `fish-NEXUS-file-for-concatenated-Bayesian-analysis <http://cloud.faircloth-lab.org/2j403w0k0H241S410c23/content>`_ (nexus.bz2)*

..
	- `fish-BEAST-file-for-Bayesian-relaxed-clock-analysis <>`_ (xml.bz2)
	- `fish-FASTA-files-for-hdpp-analysis <>`_ (fasta.bz2)

Checksums
---------

- MD5 (fish-500-uce-loci-probes-4X-tiling.fasta) = 665529aa1c9b4267dad1ff21836cb3a8
- MD5 (fish-probe-matches-to-genome-enabled-taxa.tar.bz2) = fea5980e0bee27dcd2a1ba4c9bd11b31
- MD5 (fish-genome-enabled-contigs-matching-uce-loci.sqlite.bz2) = b055ac892bc3c330558e8a228a843193
- MD5 (fish-contigs-following-enrichment.tar.bz2) = 52384c135194921d89dae449a92ced01
- MD5 (fish-contig-matches-to-uce-loci.tar.bz2) = 0e29a2b27505c6de1ca5e9c9ccf7a4f6
- MD5 (fish-contigs-matching-UCE-anchored-loci.sqlite.bz2) = 354882110db95e6c00260cfc902b60fb
- MD5 (fish-substitution-model-data-for-uce-loci.tar.bz2) = bce56acfe03c55b5223d84e04a15810d
- MD5 (fish-NEXUS-file-for-concatenated-Bayesian-analysis.nex.bz2) = 221eea82f21ff3e0438518fef5544ac1

Computer code
-------------

Computer code used within this manuscript is in `snapshot m2.0-final`_,
of:

* `phyluce @ faircloth-lab`_

Author contributions
--------------------

MEA, FS, LS, and BCF designed the study; BCF located UCEs, designed
enrichment probes, created data sets, and performed phylogenetic
analyses; BCF and LS developed laboratory protocols and conducted
laboratory work; MEA, BCF, and FS wrote the manuscript. All authors
discussed results and commented on the manuscript. The authors declare
no competing financial interests.

Acknowledgements
----------------

National Science Foundation grants DEB 6861953 and DEB 6701648 (to MEA)
provided partial support for this work.  Funds from an Amazon Web
Services education grant to BCF supported computational portions of this
work. We thank Bryan Carstens and Scott Herke for help with Illumina
sequencing.


.. _snapshot m2.0-final: https://github.com/faircloth-lab/phyluce/zipball/m2.0-final
.. _phyluce @ faircloth-lab: https://github.com/faircloth-lab/phyluce
