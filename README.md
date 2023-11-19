# The generation of GABAergic Interneurons from human iPSCs
## Introduction

GABAergic interneurons regulate cortical neural networks by providing inhibitory inputs.
Their loss or dysfunction in the cerebral cortex leads to neurodevelopmental disorders such
as schizophrenia, autism spectrum disorders, and epilepsy. Therefore, there has been a
growing interest in the reproducible and highly efficient generation of cortical GABAergic
interneurons. In vitro, the generation of GABAergic interneurons from human pluripotent stem
cells (hPSCs) is crucial for studying human-specific cellular and functional properties during
development, which cannot be modeled in other species with lower complexity. Also, these
in vitro-derived cells are good candidates for future therapeutic cell replacement therapies.

## Aim

Here I describe a protocol for generating cortical interneurons from hiPSCs towards medial
ganglionic eminence (MGE)-derived ventral progenitors and further into GABAergic
interneurons. I have established the protocol by comparing and combining several published
protocols with the goal of achieving a high percentage of GABAergic interneurons which can
also be scaled up to obtain a large number of cells (Close et al., 2017; Schuster et al., 2019; 
Shi et al., 2012; Strano et al., 2020). Then, further optimization was performed: the dose of
SHH and WNT inhibitor, the type of WNT inhibitor, the presence of PMA, different cell densities 
and different splitting days.

## Materials and methods 

For the differentiations, Matrigel coated plates were used. Matrigel was diluted 1/300 in DMEM/F12. 6-well
plates containing 80% confluent iPSCs were washed once with 1X PBS and 500μl Accutase per well was added.
After 5 minutes incubation, cells were collected to a falcon from the wells with addition of 1ml 1X PBS per well.
Cells were centrifuged at 300 g for 4 minutes, supernatant was discarded and the cell pellet was re-suspended
with mTeSR containing 1/1000 ROCKi.
Four wells from 6-well plate were seeded into a 10cm dish. Next day, Dual SMAD inhibition was initiated by
replacing media with N3 media (Table 1) with SMAD inhibitors (Shi et al., 2012).

**Table 1: N3 media**
<img width="932" alt="Table 1" src="https://github.com/bilgesugenc/GABAergicInterneurons/assets/147976764/0310fde8-e217-4e1f-92f4-39af01639e36">


SMAD inhibitors (added at time of use, and stable for 5 days at 4°C)
1. Dorsomorphin (Sigma Aldrich, P5499-5MG, 50mM stocks were prepared in DMSO): Use 1:5000 (1μM
final)
2. SB431542(Axon Medchem, 1661, 10mM stocks were prepared in DMSO): Use 1:1000 (10μM final)

In addition to SMADi, 2μM WNT inhibitor XAV939 (Sigma Aldrich, X3004) was added (Close et al., 2017).
The dual SMAD inhibition is the inhibition of BMP and TGF-beta pathways. It provides rapid and efficient
production of neural progenitors from pluripotent stem cells. SB431542 is used as a TGF-beta/SMAD inhibitor.
Dorsomorphin was added to inhibit BMP pathway. According to the literature, addition of WNT inhibitor results
more MGE-like NKX2.1-positive progenitors (Strano et al., 2020). Therefore, WNT inhibitor 2μM XAV939 was
added. The media was changed every day until day 10. After day 10, protocol of Close et al., were followed (Close
et al., 2017). At day 10, 1,000,000 cells per cm2 were seeded onto Matrigel coated plates. At day 11, ventral
induction was started by replacing medium with N2 media (Table 2) with 100ng/ml (5nM) SHH (Peprotech, 315-
22), 1μM XAV939 and 0.5μM PMA (Sigma Aldrich, SML0868). Media was changed every two days from day 11
to day 17. N2 media without SHH and PMA was used from day 19 to day 23.

**Table 2: N2 media**
<img width="958" alt="Table 2" src="https://github.com/bilgesugenc/GABAergicInterneurons/assets/147976764/f89878a6-32d8-4d44-83b2-e7d7d365e5d2">

At day 24, 800,000 cells per cm2 were seeded onto Poly-D-lysine (PDL)/Laminin coated plates. PDL is diluted in
1/50 in 1X PBS and coated for overnight. Next day, PDL is removed, and wells were washed with water 2-3 times.
After wells were dried, laminin (1/200 in sterile 1X PBS) coating is performed. For neuronal differentiation,
Sodium-L-Ascorbate, Adenosine 3ʹ,5ʹ-cyclic monophosphate (cAMP), Neurotrophin-3 (NT-3), Brain-derived
neurotrophic factor (BDNF), and Glial cell line-derived neurotrophic factor (GDNF) were added into NBND media
(Table 3) from day 25 on. Sodium-L-Ascorbate was added daily. The half of the medium was replaced every two
days. At day 32, 200,000 cells per cm2 were plated onto PDL/Laminin coated plates. At day 33, medium was
replaced with fresh NBND media.

**Table 3: NBND media**
<img width="936" alt="Table 3" src="https://github.com/bilgesugenc/GABAergicInterneurons/assets/147976764/1aed4017-84fa-4bdf-9496-3b971faba7ac">


## Results

I verified the identity of cells via staining and RT-qPCR at different time points (progenitor and 
neuronal stages) for a panel of medial ganglionic eminence (MGE), GABAergic, and neuronal markers. 
These showed a purity of up to 80% of my differentiation protocol. 

## References 

1. Close, J. L., Yao, Z., Levi, B. P., Miller, J. A., Bakken, T. E., Menon, V., Ting, J. T., Wall, A., Krostag, A. R., Thomsen,
E. R., Nelson, A. M., Mich, J. K., Hodge, R. D., Shehata, S. I., Glass, I. A., Bort, S., Shapovalova, N. V., Ngo,
N. K., Grimley, J. S., . . . Lein, E. (2017). Single-Cell Profiling of an In Vitro Model of Human Interneuron
Development Reveals Temporal Dynamics of Cell Type Production and Maturation. Neuron, 93(5),
1035-1048.e1035. https://doi.org/10.1016/j.neuron.2017.02.014
2. Schuster, J., Laan, L., Klar, J., Jin, Z., Huss, M., Korol, S., Noraddin, F. H., Sobol, M., Birnir, B., & Dahl, N. (2019).
Transcriptomes of Dravet syndrome iPSC derived GABAergic cells reveal dysregulated pathways for
chromatin remodeling and neurodevelopment. Neurobiol Dis, 132, 104583.
https://doi.org/10.1016/j.nbd.2019.104583
3. Shi, Y., Kirwan, P., & Livesey, F. J. (2012). Directed differentiation of human pluripotent stem cells to cerebral
cortex neurons and neural networks. Nat Protoc, 7(10), 1836-1846.
https://doi.org/10.1038/nprot.2012.116
4. Strano, A., Tuck, E., Stubbs, V. E., & Livesey, F. J. (2020). Variable Outcomes in Neural Differentiation of Human
PSCs Arise from Intrinsic Differences in Developmental Signaling Pathways. Cell Rep, 31(10), 107732.
https://doi.org/10.1016/j.celrep.2020.107732
