# Easy _B.subtilis_ Transformation for Amateur Biohackers
by [Cathal Garvey][], of www.indiebiotech.com

Creative Commons Attribution, Sharealike: Feel free to modify, share, or publish this work provided that credit is given to me for the original work (with a link to indiebiotech.com) and that the derived work or publication is released under the same license. Share, share alike.

## Preamble
_Bacillus subtilis_ is a soil bacterium that is found growing worldwide as a periodic saprophyte. That is, the species degrades dead organic matter, particularly plant or fruit matter.

_B.subtilis_ is considered "naturally competent", meaning that without any special effort on the part of a human handler, the species is perfectly capable of absorbing and integrating foreign DNA into its genome. Indeed, it does so regularly in the wild, making it one of many, many "genetic engineer" species out there. So much for "natural"!

Many protocols for transforming _B.subtilis_ focus on inducing competence during active growth, a process involving awkward-to-prepare minimal growth broths and salt solutions, and the use of a spectrophotometer or other cell-counting method to estimate growth phase. Obviously, these requirements are pretty onerous for amateurs without access to expensive equipment or obscure reagents, so an alternative would be nice.

As it happens, some of the earliest work on _B.subtilis_ transformation by _Spizizen et al_ employed a far simpler process; germinating spores in the presence of DNA. Because the spores were formed at a growth phase which is still somewhat naturally competent, the emerging cells are still studded with transformation machinery, and are capable at the moment of germination of DNA uptake and incorporation.

## Design Considerations
The following protocol is designed to make it as easy for a beginner to make their first GM B.subtilis as possible. With that in mind, it attempts to fulfil the following requirements:
* Non-shaking incubation
* Medium-volume liquid handling (no micropipettes)
* No expensive reagents (no DMSO)
* Optional autoclave/pressure cooker

## Minimum equipment
* Sterile Glass _or_ plastic Pasteur Pipettes _or_ glass droppers, preferably graduated.
    - If using glass pipettes, you'll also need a pipette pump and a pipette brush, available cheaply on ebay.
    - Glass droppers must be sterilisable by pressure cooker.
    - Disposible pasteur pipettes should be graduated and sterile, pre-wrapped.
* 30C incubator - achievable with a pet terrarium thermostat and heat-mat in a polystyrene box.
* Microwave for sterilising media (pressure cooker preferred!)
* Sterile work area
    - Bunsen burner or blowtorch-facing-up, or
    - Jury-rigged glove-box with inner surface sterilised, or
    - A good HEPA-rated air purifier with a fresh filter pointing at work area.
* Lab strain, plasmid-free _B.subtilis_, preferably a derivative of the _168_ strain.
* Desired DNA plasmid, plus materials needed to select for the plasmid (varies widely between plasmids)
* Ingredients for basic broth (PDB):
    - 200g washed sliced potatoes
    - 20g Glucose (AKA Dextrose)
* Additional Ingredients for basic Agar (PDA):
    - 22g Agar, preferably as powder
* Fine Sieve, Coffee filters, funnel, cotton wool to clarify broth
* Glassware
    - Preferably actual lab glassware, available from brouwland.com or various ebay sellers. Alternatively;
    - Recycled jam jars for “Flasks”
    - Smaller jars for “test tubes”
    - Wide jars or glass ramekins for “Petri Dishes”.

## Transforming _B.subtilis_ by Germination:
1. Prepare a suspension of _B.subtilis_ spores:
    - Streak cells liberally on a PDA plate.
    - Leave to incubate (with agar surface pointing down) for 7 days at 30C in a humidified incubator.
    - (Preferably) Leave in a fridge for 3-7 days to finish sporulation.
    - Open plate under sterile conditions, and add 0.5 ml of sterilised deionised water to surface.
    - Using a suitable, sterilised instrument (such as a small spoon), gently scrape cells from agar surface into the water suspension.
    - After suspending as many cells as possible, use a sterile pipette to remove the spore suspension to a sterile test tube.
    - (Preferably) Use a centrifuge to gently spin cells down to a pellet, remove original water, and re-suspend in fresh deionised water. This brief "wash" can potentially help remove extracellular enzymes that might otherwise act to degrade DNA later. Better still, repeat this wash step one more time. Better again, resuspend the cells in deionised water *after* washing in TE buffer to strip free metal ions from the cells, further inactivating the offending enzymes.
    - Store at 4C in a fridge until needed.
2. Prepare a small quantity of broth (subprotocol below) and some agar plates (below) with whatever selective agent is needed for the plasmid you will be using. Some protocols instead place the selective agent in the transformation solution, not the agar. It may help in later steps if you take the time to let the agar plates dry a little before use, so cell suspension can soak into the surface when they are plated.
3. Prepare broth for germination by adding a suitable quantity of DNA (20-50 uL of a Miniprep, if possible, or else 0.1ml if better liquid handling equipment is unavailable) to 0.2ml sterile PDB, under sterile conditions. Close cap and mix by flicking the end of the tube lightly.
4. To this DNA/broth solution, add a small amount of spore suspension (this assumes your suspension is highly concentrated, opaque white with suspended cells); if the means to transfer 20uL of cell suspension is unavailable, just dip a pasteur pipette tip in the suspension and dip this into the DNA/broth mix.
5. (Probably optional) To "activate" spores, close the cap on the tube or otherwise close it to maintain sterility, and then steep the end of the tube in hot-but-not-boiling water; aim for 50-60 degrees celsius, which feels slightly too hot to hold by hand. Leave for one minute, then return to 30C.
6. Cells can be left to transform at their own pace in the suspension for 5-30 minutes, or immediately plated. Whether or not to let them sit may depend on your selection procedure; if plating involves spreading the cells manually over the agar surface and thus "diluting" the DNA/cell mix prematurely, leave the cells for 30 minutes before plating. For plating methods where cells are placed on the agar as a single large droplet, they can be plated immediately.
7. After plating cells, leave them under sterile conditions to soak into the agar, enough that the cell suspension will not simply pour off the surface when the plates are inverted for incubation.
8. When ready, invert the plates so the agar surface points downwards, and incubate at 30C or 37C overnight, or for as long as the chosen selection format requires.

## Preparing Nutrient Broth and Agar for _B.subtilis_:
### A: Broth
1. In 800mls water, simmer 200g sliced, washed potatoes for 30 minutes, preferably with a lid on to prevent excess evaporation.
2. Bring remaining mix to 1L with fresh water before filtration, to "dilute" losses due to filter absorbtion.
3. Sieve out large chunks of potato, and then use a coarse filter (such as a french press/cafetiere coffee maker or a fine sieve) to remove smaller chunks. Be patient and gentle with plunger filters, as gelatinous starches may partially clog it and forcing the plunger will just force matter past the filter.
4. Leave the remainder to settle for an hour, then decant the clearer broth above the sediment through a coffee filter.
5. If the broth does not yet appear transparent, repeat step 4.
6. For a final filtration step (which can take a long time if the prior steps are rushed or skipped), pack some cotton wool into the end of a large kitchen funnel so that it forms a tight filter, and patiently filter the clarified broth through this to remove as much remaining matter as possible.
7. When you are satisfied that the broth is ready (it should be entirely transparent and yellowish in colour, add 20g glucose and top up the volume to 1L.
8. Divide the broth into 50ml-100ml volumes in containers appropriate to the method of sterilisation you will be using. This means, for microwaving, that you cannot use metal lids, and for pressure-cooking/autoclaving you cannot use certain plastics.
9. Sterilise as soon as possible.
10. If adding antibiotics, wait until sterilised broth is cool enough to hold but not yet solid, and then add an appropriate amount of antibiotic.

### B: Agar
The procedure is identical to the above, except that in step 7, 22g of Agar powder/flakes should be added to the broth prior to sterilisation.

If using a microwave (2a), this may require extended stop/start micromanaging to prevent boil-over of agar solution (which is very eager to boil over and make a bubbly mess).

If using an autoclave/pressure cooker (2b), this means being careful not to disturb the pressure cooker during sterilising or cooling afterwards, as a sudden decrease in pressure due to a disturbed weight-float can lead to flash-boiling of agar within the cooker, and consequent bubbly mess.

If adding antibiotics to the agar, wait until sterilised agar is cool enough to hold but not yet solid, and then add an appropriate amount of antibiotic.

## Sterilisation of Broth, Agar and Equipment:
### A: Sterilising in a Microwave
The below assumes you are using a rotating turntable microwave rated at 1kw. You may have to adjust the times for weaker or more powerful microwaves.

For liquid samples in glass vessels, place the lid on the vessel but do not seal the lid! Explosions may result if the lid is sealed! Only seal after sterilising.

Furthermore, only sterilise one thing at a time. Hotspots and coldspots mean that multiple things will experience different levels of heat transfer. Place the single item in the middle of the microwave, where it has probably been tuned to direct the most heat.

For a 25ml sample, sterilise by microwaving for 5-7 minutes.
For a 50ml sample, sterilise by microwaving for 7-9 minutes.
For a 100ml sample, sterilise by microwaving for 9-11 minutes.

You can use this method to kill bacteria after an experiment as well, and you should do so.

If you want to sterilise small items of equipment, place them in a microwave-safe container with a loose lid and a small volume of water (~25mls) within, and microwave for 5-7 minutes; the steam in the vessel will help sterilise the equipment. Special microwave pressure cookers or microwave steamers are used for cooking or unnecessarily sterilising baby bottles and soothers, these can be easily repurposed for biohacking.

*Please remember that you cannot safely microwave metals, including jam-jar lids, metal equipment or foil-capped tubes.*

### B: Sterilising in a Pressure Cooker
If you have a pressure cooker, _and know how to use it_, you can alternatively (and, it is thought, more reliably) sterilise things by cooking them at full pressure for 20 minutes. That is, bring the cooker to full pressure, then start counting 20 minutes, then let it cool on its own. *Lids should still be loose on vessels* during sterilisation in a pressure cooker. Seal them afterwards. Ideally, raise the load of equipment and samples to be sterilised above the liquid at the bottom of the steriliser, particularly glassware, to prevent heat from the bottom of the pressure cooker from coming into direct contact with glass.

You can use this method to kill bacteria after an experiment as well, and you should do so.

You can autoclave anything that is temperature stable up to 122C. Many plastics will not survive autoclaving without warping, shrinking or just melting and flowing. If you're unsure of your plastics, you can always test single examples of your equipment in the pressure cooker first, placing each sample of plastic into a separate small jar to collect melted plastic.

Even temperature-safe plastics may eventually harden, warp slightly or become brittle after repeated autoclaving.

### C: Sterilising Glassware and Metalware in an Oven
1. To sterilise glass or metal items before use, wrap lid-less items such as pipettes in aluminium foil, and place metal lids on test tubes or jars but do not tighten. If test tubes have plastic lids, remove these and wrap the test tubes in foil; sterilise lids separately in a pressure cooker, or in a microwave in a vessel with a small quantity of water.
2. Place the items in a fan-assisted oven, and close the door. Place some tape on the door to gently seal it shut, so someone does not open it mid-cycle; the glass may shatter if the oven is opened during this process.
3. Set the oven to 200C and let it come up to heat.
4. Once at 200C, set a timer for 1:30 hours.
5. After 1:30 hours, turn off the oven and allow it to cool to room temperature.
6. Remove glassware carefully. Seal jar lids, leave other items in foil wrapping.


## Sterile Working Conditions
To keep wild bacteria out of your experiments, you have a few options:
A blue-flamed bunsen burner or blowtorch can be directed upwards, creating a strong updraft that helps to keep dust from settling on experiments. Within about 10cm of a blue, upward flame, work is pretty sterile.
Working under a good, high-rating HEPA air purifier's air-flow is another useful way to get sterile conditions.
You can also make a sterile area using a plastic box with holes cut in the side for your hands. Sterilise the inside of the box with bleach or alcohol spray, do the same with the surface underneath, then invert the box and block the arm-holes until you use the area. Sterilise the surfaces of everything you bring into the box with alcohol or disinfectant spray first. Wear rubber or latex gloves, and wash your hands and forearms before and after work. Sterilise the gloves with disinfectant or alcohol spray.
When working, keep lids on until you need to get access to a broth or bacteria, then cover again immediately.
Have an empty jar or two that you can use to dispose of used pipettes, toothpicks, loops or other tools.

## License
This work is licensed under a [Creative Commons BY-SA 3.0][] license.

## References:
### Academic
*TODO*

[Creative Commons BY-SA 3.0]: https://creativecommons.org/licenses/by-sa/3.0/
[Cathal Garvey]: http://biohacking.cathalgarvey.me
