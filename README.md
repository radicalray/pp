# pp
Prayer Pairs Wizard

Allows you to auto-create prayer pairs between members of a group/pool taking into account factors such as history or blacklist. 

History guarantees that no prayer pair would ever repeat (if pool is big enough)
Blacklist manually filters out unwanted pairings (e.g. GP's, brother/sister rule #7, etc).

### Demo
http://radicalray.github.io/pp/

### Algorithm

The pairing algorithm is very naive and randomly assigns pairings and checks to see if it satisfies all the constraints.
It tries this 100 times before giving up. Performs fairly well for small pools (~20)

In an overly-constrained big pool (~300), may struggle to get out of a no-solution well, also known as backtracking in 3SAT algos.

### Technology
1. Uses localstorage for backend
2. jquery, selectize and boostrap for UI
3. optimized and tested for ~300 big pools.
4. Supports copy and pasting from/into excel spreadsheets. :)
5. Works offline as well.

### Coding Methodology

Super YOLO programming, throwing most good programming principles out the window to get something working fast.

### Supported Browsers 
Chrome. :)
