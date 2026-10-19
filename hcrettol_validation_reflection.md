# Validation Reflection - hcrettol

My partner didn't have his MiniProject2 posted, so the TA gave me rpatel92's to validate instead. His stats file only had ActivityPattern, so that was the only field I could actually compare. For the other four fields I just put my own answers based on his commit data and plots.

ActivityPattern had the most disagreement. rpatel92 called 9 of his 10 projects cyclical, but most of them looked declining to me, with a big peak early and less activity after. The coding guide says cyclical means activity repeats at fixed intervals, and most of these just had spikes at random times. pyprocar was the hardest one since it has a lot of spikes, but they weren't on a regular schedule so I said irregular.

Before the long gaps, a lot of the projects were only doing small things like version bumps and dependency fixes. When they came back it was usually either the same main developer returning or new people fixing stuff that broke with newer libraries, like numpy for Calamari and scipy for batchgenerators. Most of the projects did recover and 7 of the 10 are still active, so a gap didn't usually mean the project was dead. The main thing I had to watch out for was fake recoveries. football had commits after its gap, but they were from random people and dependabot instead of the actual maintainers, so I didn't count it.
