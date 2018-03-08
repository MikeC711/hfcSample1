# hfcSample1
This is an attempt to do notable HyperLedger Fabic Composer development on Windows 10 Home.  True, this does not include Hyper-V and thus
only allows the old VirtualBox docker toolkit which I don't think is even supported anymore.  Fear not, I'm not using it.  Plan is:
1. Use VSCode with extensions to do all updating here
1. Have fastpath automated means of sending file to a playground I set up in Bluemix AND on my local ubuntu desktop
1. Looking to use one or 2 docker images to support HFC and have them up only when doing HFC dev
1. Also multiple images for a small HLF network that includes some of the key features such as
    1. Channels
    1. Anchor peers
1. Dynamically defining channels
1. In the end, keen to contrast this with Ethereum and Singularity from numerous perspectives.

# So the planned process
1. VS Code on Windows for model, acl, and javaScript (saved to git)
1. Find best way to move it to playground and bna build (bluemix, local, ...)
    * Some benefits to using Bluemix (if still free) so I can hit from elsewhere and not have ubuntu running
    * If I do use ubuntu machine, want to do so headless
1. Eventually test it in a real network

# Participants and actions
1. Mortgage customer
    * Request preQual letter (optional a1)
    * Apply (1)
    * Check status
1. Mortgage lender
    * Accept application (2)
    * Provide preQual results based on criteria (a2)
    * Provide preliminary judgement (accept/reject) (3)
    * Schedule Appraisal (4)
    * Schedule Inspection(s) (5)
    * Accept or reject mortgage (6)
    * Record closing (real closing or customer flew the coop) (9)
1. County (register deeds)
    * Handle transfer of deed (7)
    * Bill for tax based on sale price (8)
