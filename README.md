# Toggle-SWAP-RAM

It empties swap space if there is enough free RAM available.

It checks for enough free RAM before actually disabling the swap and enabling it again.
Here, data(pages) in swap are copied back to RAM before the swap is disabled. 

Emptying swap can improve performance of system with slow disks but with enough RAM.

**Note: It will give performance penality if something is being swapped in/out.**
