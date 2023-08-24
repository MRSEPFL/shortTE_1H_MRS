Synthetic Brain-like 1H short-TE MRS Datasets
This repository contains synthetic datasets comprising time domain data with various noise levels. The synthetic data is generated as a linear combination of experimentally measured macromolecule (MM) and 20 metabolites commonly found in NMR spectroscopy. The metabolites included in this dataset are:

Ascorbate (Asc)
Alanine (Ala)
Aspartate (Asp)
Creatine (Cr)
Phosphocreatine (PCr)
Glucose (Glc)
Glutamine (Gln)
Glutamate (Glu)
Glutathione (GSH)
Glycerolphosphorylcholine (GPC)
Phosphorylcholine (PCho)
Myo-inositol (Ins)
Lactate (Lac)
N-acetylaspartate (NAA)
N-acetylaspartylglutamate (NAAG)
Phosphorylethanolamine (PE)
Scyllo-inositol (Scyllo)
Taurine (Tau)
γ-aminobutyric acid (GABA)
Glycine (Gly)

Each subfolder within this repository contains synthetic data generated with different noise levels and random baseline. Additionally, various Voigt lineshapes and linewidths are present in these datasets.

Dataset Details
The time domain data in each folder are constructed as linear combinations of the experimentally measured macromolecule (MM) and the 20 metabolites listed above. These datasets are designed to simulate in vivo cerebral NMR spectra that contain contributions from multiple metabolites and macromolecules.

The datasets with different noise levels allow researchers and practitioners to evaluate the performance of their NMR data processing, fitting, and quantification methods under various noise conditions. The SNR in this dataset is defined as the ratio between the peak height of the methyl protons of NAA and the root mean square (RMS) of the noise.

Moreover, the synthetic datasets also include variations in Voigt lineshapes and linewidths.

Contact Information
If you have any questions, issues, or suggestions regarding the synthetic datasets or this repository, feel free to contact: ying.xiao@epfl.ch