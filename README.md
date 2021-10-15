# HTTP-TPC

HTTP-TPC is a network protocol that allows a client to trigger that
data is transferred between two storage systems.  It does this by
delegating responsibility for the actual transfer to one of those two
storage systems.

This delegation allows the responsible storage system to optimise how
the data is transported; for example, by establishing a direct
connection between itself and the other storage system.

This repository contains material related to the HTTP-TPC protocol.
This includes the description of the protocol.

## Known implementations

There are several known server-side implementations of HTTP-TPC:

 *  [dCache](https://dcache.org).
 *  [DPM](https://lcgdm.web.cern.ch/dpm).
 *  [EOS](https://eos-docs.web.cern.ch/).
 *  [StoRM](https://italiangrid.github.io/storm/).
 *  [xrootd](https://xrootd.slac.stanford.edu/).

There's currently one know client for HTTP-TPC:

 *  [GFAL](https://gitlab.cern.ch/dmc/gfal2) .

## Documentations

There are fragments of information about HTTP-TPC spread over
different locations.  A goal for this repository is to host the
authoritative information.  Until that is achieved, the following
links may provide useful information:

DOMA-TPC documentation:
 *  [Implemenations](https://twiki.cern.ch/twiki/bin/view/LCG/HttpTpc).
 *  [Protocol details](https://twiki.cern.ch/twiki/bin/view/LCG/HttpTpc).

Server documentation:
 *  [dCache user-guide](https://dcache.org/old/manuals/UserGuide-latest/webdav.shtml#third-party-transfers)
 *  [DPM wiki (archived)](https://web.archive.org/web/20160314230350/https://svnweb.cern.ch/trac/lcgdm/wiki/Dpm/WebDAV/Extensions#ThirdPartyCopies)
 *  [StoRM tutorial](https://agenda.infn.it/event/26223/contributions/133045/attachments/79985/104216/StoRM%20HTTP%20TPC%20tutorial.pdf)
 *  [XrootD paper](https://inspirehep.net/files/e64f64fb6dc417dfb92476a2652fc610)
 