# 1 Internet Banking System

![diagram](https://www.plantuml.com/plantuml/svg/0/fLJ1JXj13BqZyGzk3bMG0hdqr5CXYGg8G4H2eIVadJN9jBCpgnbl0ghwx_NCPfSDJSMXYPHeFC_syxCzNmAZvwemS66Pl2M6CxG_jLt2_2Km5N0C8sSPjIKFOurBZyNXmGTjbQboWXLp6JuFXnut9qlDgogh0dab7cJvHBbYYBdNQDUcAglXwDFnpA3bk-dLq21JO34zjl5FIY5oU12_LwVVR-uMZ_SNY_F7gydNoVMuVnJjC_B1sNwPgG7qwWEQblAe2kmAyZsvF0MrFO5x0buHP88Qm4POGjbuHXkWKgwo74vwagCk-t7op7qA4cToNA0s498v1bv8A9t44l-fLju5zyGmULOhj4i2wZgy3LbaCUPKodqI8UcDs37yd9sd06XCmrk98H6DG75qla3MpW9chkAsJ0dS5380zcW3gWYJ4x7g4ZaJK8x-fQyJcxUTxnt1hyC3a4_RcVu61NXF6PoMfT4gvOziV-0Q0MqEyz97UjDlesWUaz5hePJuouYnLh0TYeJcLaD9svGMvCSGb2WYuckQn7oNJIWZdNcDdqNy7bf1ULtMwQGlbS4q5ZFlrZhV2hoNnbDbasveDBy0krU1OQqn-cWF6v4YysuZmxw7Nn7fJLscJM8MypvWWQBGBWKmkj1CEOGg2qB1yNzGAkfysx-SrbhH7cvv5lk3Z1a6YdHkoM0T71eppDMA2koCOzngyBJKGIOh3Lzd40Ummh2ICh0IAfQtZG3bAOz7DFLiKWXWtB8paBlKiDHnSMSN_vuoxavPA-GxWaMD42xdDzV3yyLY1f8XPQ_pI_rrvhJkSx9vsEvmI09C5xE6QWkjr_WkK88yo7CM0y__mYMnRmabv4VOUEcrh8IBFfVZir4N7XUi7kjcTxgtwQQMfqdQbhEJjNW7zpjM7O7f1KrRtG1RJ7jTyqdtNNFnrXg5gr_a7VLYfOBu8hRqhly1)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.