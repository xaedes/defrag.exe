Watch defrag miraculously turning chaos into order at https://xaedes.github.io/defrag.exe/
Best served with a warm cup of coffee or tea.

## How to play

You start with **LEDGER.EXE** already installed and a modest 512-block drive.
Run software to earn money, spend money to buy more software and upgrade your
hardware, then keep defragging to stop the chaos from eating your disk alive.

### The loop

1. **Run software** — hit ▶ RUN on any installed program. It earns you money
   each cycle by reading and writing files on disk. Server programs loop
   continuously; regular programs run once and stop.

2. **Buy upgrades** — spend earnings in the Shop on more RAM, bigger HDDs,
   extra read/write heads, and new software programs.

3. **Defrag** — software fragments your disk badly over time. Run the
   defragmenter to pack things back together and reclaim performance.

4. **CHKDSK** — running defrag in parallel with software can corrupt orphaned
   blocks. Run CHKDSK to scan the whole disk and free them. You get this
   for free.

### Hardware upgrades

| Upgrade | Price | Effect |
|---|---|---|
| RAM 512 KB | $30 | Unlocks heavier software |
| RAM 1024 KB | $150 | Requires 512 KB first |
| RAM 2048 KB | $800 | Requires 1024 KB first |
| HDD 1024 BLK | $50 | Doubles disk capacity |
| HDD 2048 BLK | $300 | Quadruples from base |
| Read Head #2 | $80 | Parallel reads |
| Read Head #3 | $250 | Requires Head #2 |
| Write Head #2 | $100 | Parallel writes |
| Write Head #3 | $320 | Requires Head #2 |

More read/write heads let multiple software instances truly run in parallel
instead of queuing behind each other.

### Fragmentation tips

Software will fragment your disk. The more programs running, the faster it
gets bad. Watch the fragmentation meter in the top bar — when it turns red,
things start to feel wrong.

To fragment quickly for the defrag show: open **Bulk Operations**, stack a few
**Create+Delete cycle** and **Append all files** steps, repeat 10–20× until
the meter goes red. Then set speed to Slow and enjoy the cleanup.

### CHKDSK

Running defrag and software simultaneously can leave orphaned blocks behind —
blocks whose file no longer exists but are still marked used. Hit **CHKDSK**
to scan the disk, visit each corrupt block with the read head, then wipe it
free with the write head. It runs in parallel with everything else and can be
stopped mid-scan.

## Defrag modes

- **Simple** — pack files tight, no reordering
- **Consolidate Free Space** — push all free blocks to the end
- **Sort by Filename** — alphabetical, very satisfying
- **Sort by Modification Date** — oldest files first
- **Sort by File Size** — largest files first
