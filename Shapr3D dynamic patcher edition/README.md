# Shapr3D 5.860.8843.0 #241a6cc1 | original release

Written from scratch. Made to work dynamically via pattern scanning and intermodular call analysis. (could still be improved) \
**Based on sl4v3k's work.** Put his latest version through my disassembler (ida) to find out what he is patching. \
Technically still somewhat experimental version. (report if any issues occure)

# Shapr3D 5.880.8980.0 #7cd1f54e | no update needed

License check is not run continuously anymore. \
To see any changes after running the patcher you have to open one of the available files.

# Shapr3D 5.1001.9950.0 | update needed

A little change was made near a patch region which did affect the pattern of patch 1 as well as a offsets. \
Could be made more resilliant by instead searching for function head and looking from there for the appropriate instruction to patch.

# Shapr3D 26.10.10376.0 | update needed

Again a problem with patch 1. \
This patcher update also introduces two fully original patches found by me. \
First is to remove the advert popup when opening a project and second is to enable export of enterprise exclusive formats.

# Shapr3D 26.21.10452.0 | update needed (again 😠)

Problem with my anti popup patch. A bit changed now and hopefully more update resilient. \
I have also been working on a new method that does not rely on patching license check functions. \
It should be a more **permanent solution** but it is currently still under development.

# Shapr3D 26.32.10532.0 | update needed

Problem with patch 1. \
Recently it seems to break with every update. A completely redo of the patcher is in progress to fix that. \
No idea when I will finish it though.

# Shapr3D 26.40.10572.0 | update needed

Patch 1. Jump offset change.

# Shapr3D 26.50.10685.0 | update needed

Couple things broke. It seems this update had some bigger codebase changes.

# Shapr3D 26.110.11116.0 | update needed

Litteraly a single bit broke it. That change breaking it should not happen again, I made some changes. \
Added experimental enterprise import patch I reverse engineered. Only tested .jt/.catpart! \
Obfuscated the binary a tiny bit + added some checks to ensure console is not being hidden (because of resellers).

# Known Problems

Some functionality might not work (will not trigger). Report it! \
This is mainly caused by a limitation of a certain patch. \
Without deep knowledge of the .NET native AOT runtime this will be unfixable for now.

# Guide

Just run it! Of course you also need to have Shapr3D open.





