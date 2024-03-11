# Chapter 10 - DNA Structure and Replication
## Structure of DNA
* 3' end is where the OH is, 5' is where the Phosphate is
* New nucleotides are attached to the 3' end
* Deoxyribose sugar has one oxygen atom in the ring, 4 carbon ring, 5th above 
* C, T, U: Single ring. A, G: Double ring
* A = T, C ≡ G

## DNA Replication
* Origin of Replication: Sites for binding of proteins (mainly initiation/auziliary)/AT-rich region.
* Bacteria with circular DNA: One origin of replication: initiator attached, then two helicases replace is and they move in opposite directions. Eukaryotes: multiple replication origins. See [this](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6742236/) and [this](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/origin-of-replication#:~:text=DNA%20replication%20origins%20are%20characterized,involved%20in%20regulating%20initiation%20events.)   
* Helicase: Forks and unwinds the two DNA strands
* Replication Fork: Point at which the two strands split
* DNA Polymerase III: Reads and creates a new copy in the 3' to 5' direction. New nucleotides are attached by removing OH at the 3' end and attaching the phosphate of the new nucleotide. (initially, 3 phosphates would be attached to the nucleotide, the other 2 are lost)
* Leading strand: From replication fork: 3' to 5' (creates 5' to 3' which is what you call the direction to be). Can be continuously copied by the Polymerase.
* Lagging strand: From replication fork: 5' to 3' (creates 3' to 5'). Polymerase reads in the reverse direction, so:
    * Primase: Adds an RNA primer to the strand, from where the DNA polymerase moves toward the replication fork creating an Okazaki fragment. Then primase again adds an RNA primer at a certain distance.
    * The RNA primers are converted to DNA by DNA polymerase I
    * Gaps between the former primers and Okazaki fragments (where there are still free OHs towards the 5' end) are bridged by the DNA ligase.
    * Optimal DNA ligase pH = 7.4

> [!WARNING]
> Normal direction of operation of these enzymes: 5' to 3'
> Direction of DNA ligase/DNA polymerase I is from 5' to 3' (of the new strand, so it appears to go opposite of the DNA polymerase III)

> [!TIP]
> Check out the following for DNA replication:
> https://www.labxchange.org/library/pathway/lx-pathway:ad7fbf7e-9fee-4989-b8c6-e5737d21cc91/items/lb:LabXchange:a21a9b48:lx_simulation:1/55881?fullscreen=true
> https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/origin-of-replication#:~:text=DNA%20replication%20origins%20are%20characterized,involved%20in%20regulating%20initiation%20events.
> https://www.youtube.com/watch?v=bee6PWUgPo8

> [!NOTE]
> Reverse Transcriptase: RNA to DNA: Used by viruses to insert their genetic code
> Nuclease: Degrade nucleic acids

## Nucleotides to Amino acids
* Transcription: DNA -> RNA: Nucleus
* Translation: RNA -> Polypeptide
* 20 amino acids, triplet codon for each amino acid: 64 total possibilities: 61 - amino acids, 3 - stop codons
* Three base codons in DNA -> complementary codons in RNA
* mRNA: carry coding sequence for protein synthesis. Genetic code table given is based on mRNA sequence.
* tRNA: Carry amino acid to ribosome during protein synthesis
* AUG: Methionine/Start codon. Proteins may be started with Methionine

### Transcription
* Promoter: At the beginning of a gene, RNA polymerase attaches here
* RNA synthesis continues till a terminator sequence is reached
* Inside the RNA polymerase, the two strands are split, the RNA nucleotides are matched with the nucleotides in one strand, and released from the DNA. DNA is then wound back towards the exit.
* RNA produced after transcription is released into the nucleolus in eukaryotes and into the cytoplasm itself (which is where it occurs) in bacteria

## Processing of Eukaryotic DNA
* In prokaryotes, the RNA produced immediately functions as mRNA.
* In eukaryotes:
  * RNA is produced within Nucleus
  * Processing is also done within the nucleus which is as follows:
  * Addition of cap and tail to protect from enzymes and help ribosomes recognize it.
  * Non-coding introns are removed and exons are glued together. Exons are the genes that are expressed. (RNA splicing) This helps in one sequence leading to multiple expressions.

## Translation
* mRNA: Transcription produces this.
* Machinery to translate this to polypeptides requires ATP, it includes ribosomes and tRNA
* tRNA: RNA polynucleotide chain that is relatively stable, and can be simplified to two sites: *anti-codon* that matches (complementary to it) with a specific codon on mRNA when the ribosome is over it, and the *amino acid attachment site* which holds the matching amino acid.
  * Amino acid is attached by an enzyme using ATP (enzyme: Aminoacyl-tRNA synthetase)
* Once a matching tRNA is obtained, the ribosome detaches the amino acid from the tRNA and attaches it to the growing polypeptide sequence

> [!NOTE]
> Synthetase: Uses energy from nucleoside triphosphates like ATP (and others)
> Synthase: Don't use energy from them

### Ribosome
* Large and small subunit, and the large subunit has two tRNA binding sites
* A site is where the tRNA for the next amino acid attaches. P site: tRNA that holds the growing polypeptide
* Binding site for mRNA on small subunit

### Back to Translation
* Translation begins with cap and an initiation sequence
* Methionine tRNA binds to the start codon AUG (anti-codon: UAC)
* Ribosome: Large subunit binds to the smaller and the initiator tRNA fits to P site
* Anti-codon of incoming tRNA pairs with mRNA in the A site
* Polypeptide leaves P site and attaches to the new amino acid
* P site tRNA leaves, A site tRNA with the polypeptide and the mRNA is moved to P site by the ribosome
* This continues till UAA, UAG or UGA is reached

## Mutations
* Broadly, two types: nucleotide substitutions and nucleotide insertion/deletion
* Substitutions may not have any effect at all (GAA -> GAG: Both code for the same protein)
* Addition/Deletion (Frameshift mutation): Changes the entire sequence as it changes the grouping of the triplets

* Another classification of mutations:
  * _Silent mutations:_ Substitution leads to the same amino acid itself: redundant change
  * _Missense mutations:_ Substitution leads to a change in one amino acid - could result in very little effects on the resulting protein, but it could result in a huge change (Sickle cell anemia)
  * _Nonsense mutations:_ Amino acid codon -> Stop codon: Prematurely ending the polypeptide sequence.

### Mutagens
* One possible reason for mutations: DNA replication/recombination.
* Other sources: Mutagens (physical and chemical agents)
* Most common physical mutagen: X-rays, UV
* Chemical mutagens: Some types are similar to DNA bases but do not pair properly, so it breaks the nucleotide sequence.
* Many mutagens: carcinogens

## Viruses and Other Infectious Agents
* Virus: Genetic material (nucleic acid) enclosed by a protein coat (+ maybe membrane coat) (+ maybe protein spikes which help in attaching to the host cell)
* Bacteriophages: Viruses that attack bacteria. Aka Phages. 
  * Example: T4 infecting an _Escherichia coli_: It has a tail which is a hollow rod in a spring-like sheath, that pierces into the cell when the legs touch the cell surface and bend, passing the viral DNA to the host.
  * Most phages, after infecting the bacterium, enter the lytic cycle, in which phage lambda binds to the outside, injects its DNA which turns into a circle and immediately starts producing viruses (hijacking the cell's machinery). Then the cell **lyses** releasing the phages
  * Some viruses also reproduce by the lysogenic cycle, in which the viral DNA is inserted into the bacterial chromosome. The phage DNA (referred to as **prophage**) and most of its genes remain inactive, waiting for the whole cell to divide. The prophages are also passed to daughter cells, and stay inactive until a certain factor (mostly environmental, like the presence of a certain mutagen) causes it to leave the bacterial chromosome and switch to the lytic cycle and destroying the host cell.
  * If it weren't for the prophages that certain bacteria (such as those that cause botulism, diphtheria, scarlet fever) would have otherwise been harmless - the prophages direct the bacteria to produce certain toxins
* Plant viruses:
  * Most: RNA instead of DNA
  * Tobacco Mosaic Virus (TMV) was the first virus to be discovered - rod shaped with the RNA coiled within the rod-covering protein coat
  * Sometimes insects carry around the virus, sometimes damaged plants may give viruses the opportunity to get past the protective epidermis (damaged by wind, injury, etc.)
  * No cure for most viral plant diseases
* Reproductive cycle of a typical RNA virus (like mumps):
  1. Receptor proteins attach to cell surface
  2. Viral envelope fuses with the cell membrane -> protein-coated RNA enters cytoplasm
  3. Enzymes remove the protein coat
  4. Viral enzyme that also entered - uses viral RNA as template to make complementary strands of DNA -> mRNA for Viral proteins.
  5. New proteins assemble around the new viral RNA. Finally the virus leaves the cell by cloaking themselves in the cell membrane, ie, using the cell membrane as its envelope and budding off the cell without rupturing it.
* Some viruses reproduce differently: 
  * _Herpesvirus_ (Chickenpox, shingles, cold sores, genital herpes): enveloped DNA viruses that reproduce in the nucleus of the host, using the nuclear membrane as their envelope.
  * Their copies usually are left behind in the nucleus of nerve cells and remain dormant until some sort of stress (cold, sunburn, emotional stress) trigger virus production -> unpleasant symptoms.
  * Once acquired, it may keep flaring up over our lifetime. 
  * Herpes simplex I: causes cold sores
  * Herpes simplex II: causes genital herpes
* Recovery from viral infection: depends on whether or not damaged cells can be replaced easily or how fast the immune system responds.
  * We recover quickly from a col since the cells in the respiratory tract are easy to replace.
  * Polio affects nerve cells: cannot be replaced - permanent damage.
* **Vaccines:**
  * Deactivated/weakened version of the pathogen or antibodies generated by another animal when infected by the pathogen. The weakened version can help the immune system generate antibodies so that when the actual pathogen enters, it can respond faster.

### HIV-AIDS
* RNA virus, resembles mumps from the outside and enters and exits the way mumps does.
* But, it is a **retrovirus**, that is, it uses a reverse transcriptase: RNA -> DNA.
* Resulting DNA inserts itself into the host's chromosomal DNA, becoming a provirus, which is occasionally transcribed into RNA -> viral proteins -> viruses which leave and infect other cells
* Thus it has a lysogenic phase (RNA based lysogenic viruses are rare)
* No cure yet, but can be slowed down by two categories of drugs: both mess with the virus reproduction:
  1. Inhibits the action of enzymes called proteases which are needed to produce the final version of the HIV proteins.
  2. (Includes the drug AZT) Inhibits the HIV reverse transcriptase. AZT is shaped like T, and may sometimes be used instead of T, but it cannot be incorporated into a growing DNA chain. AZT has an N3 instead of OH (at 3') in the deoxyribose ring

## Viriods and Prions
* Viriods: Small circular strands of RNA, infect plants. They don't encode proteins but they can be replicated using the cell machinery, and interfere with the regulatory systems that control the plant growth
* Prions: Misfolded protein, causes various brain diseases in sheep and goats (scrapie), deer and elk (chronic wasting disease), cow (mad cow disease, earlier known as BSE, bovine spongiform encephalopathy). Prions convert the normal protein to the misfolded version These abnormal proteins clump together and lead to loss of brain tissue.

> [!NOTE]
> Histones are positively charged as DNA is negatively charged.
