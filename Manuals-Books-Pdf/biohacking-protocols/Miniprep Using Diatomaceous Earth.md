# Miniprep Using Diatomaceous Earth
Adapted from the [LA Biohackers Wiki][], where the original protocol was kindly licensed under a Creative Commons Attribution License.
Markdown formatted and expanded by [Cathal Garvey][].

## Description
A Miniprep is a procedure for extracting supercoiled DNA (usually plasmids) from small volumes of single-cell cultures. The Alkaline Lysis Miniprep is a method that leverages supercoiled DNA's moderately higher tolerance for alkaline conditions, precipitating other DNA into a solid mass along with other cellular matter and separating it by centrifugation, sedimentation or filtration.

This Miniprep procedure uses diatomaceous earth, a common natural source of silica, as a binding substrate for purified DNA during the neutralisation and washing steps of the miniprep. This approach can result in very high yields when done correctly, and makes the procedure more flexible and amenable to different levels of available instrumentation.

This protocol makes use of a particularly unusual substitution of "table salt" (NaCl) in place of the more usual guanidine salt used as a chaotropic denaturant. This is supported by work in reference #1, below. These substitutions are part of the original protocol suggested by the [LA Biohackers Wiki][]

## Centrifuge-Free Variant
Additionally, as D.E. is denser than water and readily sediments over time, this procedure can be used to perform a miniprep in the absence of a centrifuge, if one is willing to wait some time for the D.E. to sediment before pipetting out buffers.

Performing a miniprep in this way may necessitate an extra washing step with Wash Solution 1 in order to account for the inferior separation achieved by simple sedimentation and pipetting, and the drying step before redissolution of DNA should be considerably extended, possibly with stirring of the drying sediment occasionally with a sterile plastic rod to expose remaining liquid. As this longer process of drying may result in entirely dry DE:DNA complex, the re-dissolving stage should be considerably extended also, to allow DNA to fully redissolve (which can take a long time if it is fully dry beforehand).

## Materials
Alkaline lysis is a procedure that depends heavily on correct pH and buffer strength ratios between the buffers. Consequently, a "neutralisation buffer" from one procedure may be too strong, or not strong enough, to neutralise the first two buffers from a related but distinct procedure. Therefore, it is wise to make up the Lysis and Neutralisation buffers from scratch for this procedure, and to avoid re-using buffers from other kits.

Wash Solutions are more interchangeable and can possibly be reused from other kits or procedures, but this depends on the kit.

DNA resuspension solutions such as Tris-EDTA (TE) are interchangeable between kits; if you have TE from a kit already, there is no need to make up special TE for this procedure. If you are using deionised H2O instead of TE, of course, the issue is moot.

### Lysis Buffer
Note: First, mix the water and lye by shaking. Then add the SDS and stir gently. Shaking SDS will create a bubbly mess.
* 400mg lye
* 500mg SDS
* 50mL distilled water

### Neutralization Buffer
* 11.5g NaCl
* 3.7g KCl
* 43mL distilled white vinegar

### Binding Buffer
* 11.5g NaCl
* 43mL distilled white vinegar

### Diatomaceous Earth (DE) slurry
Note: Add 10g of diatomaceous earth to 100mL of distilled water. Shake, then allow the particles to settle for 3 hours. Pour off the liquid, then add 30mL of Binding Solution and shake.
* Diatomaceous earth 10g
* Binding Solution 30mL

### Wash Solution 1
* 8g NaCl
* 35mL distilled water
* 15mL isopropanol

### Wash Solution 2
* 10mL Distilled Water
* 40mL Isopropanol

### Tris-EDTA Solution

## Methods
1. Inoculate a 5mL LB culture with your transformed E. coli strain. Incubate for 12h at 37°C with shaking.
2. Pipette 1.5mL of your culture into an eppendorf tube and centrifuge for 3 minutes at 7,500 rcf. The bacteria will form a pellet in the tube.
3. Pour off the supernatant, leaving just the bacterial pellet in the tube.
4. Add 200uL of distilled water to the tube. Pump the liquid up and down with the pipette to re-suspend the bacteria. Make sure there are no clumps left. The liquid should be cloudy.
5. Add 200uL of Lysis Solution. Invert the tube 3 times to mix the solutions.
6. Wait 4 minutes.
7. Add 300uL of Neutralization Solution. A white precipitate will appear. Invert the tube 20 times to ensure the solutions are completely mixed.
8. Centrifuge the tube for 10 minutes at 16,000rcf. The white precipitate will form a pellet on the side wall of the tube.
9. Without disturbing the pellet, pipette the supernatant into a new tube. Discard the tube with the pellet.
10. Shake the DE Slurry to mix the particles which have settled on the bottom.
11. Pipette 500uL of DE Slurry into the tube containing the supernatant from Step 9. Shake the tube vigorously to keep the DE suspended.
12. Keep the DE suspended in the liquid for 2 minutes by shaking whenever the particles settle.
13. Centrifuge the tube for 30s at 16,000 rcf to pellet the DE.
14. Pour off and discard the supernatant (Note: depending on your particular tube, the pellet may not stick well. If this is the case, gently pipette the supernatant away instead of pouring)
16. Add 500uL of Wash Solution 1 and use the pipette to re-suspend the DE pellet.
17. Keep the DE suspended for 2 minutes like in Step 12.
18. Centrifuge the tube for 30s at 16,000 rcf to pellet the DE.
19. Pour off and discard the supernatant like in Step 14
20. Add 500uL of Wash Solution 2 and use the pipette to re-suspend the pellet.
21. Keep the DE suspended for 2 minutes like in Steps 12 and 16
22. Centrifuge the tube for 30s at 16,000 rcf to pellet the DE.
23. Pour off and discard the supernatant.
24. Leave the cap open and let the tube sit in a warm area for a half hour to let the remaining alcohol evaporate.
25. Add 50uL of distilled water and use the pipette to re-suspend the DE.
26. Centrifuge the tube for 30s at 16,000 rcf to pellet the DE.
27. Pipette the supernatant into a new tube and discard the tube with the DE pellet. This new tube contains your purified plasmid DNA. 

## License
Original document was licensed under a [Creative Commons BY 3.0][] license.
This expanded document is further licensed under a [Creative Commons BY-SA 3.0][] license.

## References
### Academic
1. "Extraction of Superior-Quality Plasmid DNA by a Combination of Modified Alkaline Lysis and Silica Matrix"; Ramakrishna Lakshmi, Vijaya Baskar, and Udaykumar Ranga; Analytical Biochemistry 271; 1999.

### Modern
1. [LA Biohackers Wiki][]
2. [Indie Biotech][Cathal Garvey]

[LA Biohackers Wiki]: http://wiki.biohackers.la/Miniprep
[Cathal Garvey]: http://biohacking.cathalgarvey.me
[Creative Commons BY 3.0]: https://creativecommons.org/licenses/by/3.0/
[Creative Commons BY-SA 3.0]: https://creativecommons.org/licenses/by-sa/3.0/
