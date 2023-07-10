# TQC-Chain-Project
This project is focused in exploring applications of the TQC strategy for modeling time given contemporary (~2023) semantic web tools. 


Certain commitments for both TQR and TQC can be considered as parametrizations, but they differ with respect to what we might call the generality of the respective parametrizations.  TQC parametrizes at the level of instances in the restricted binary existsAt relation, intuitively smuggling them in to the resulting relation. In contrast, TQR parametrizes at the level of any instance of the Temporal Region class, intuitively smuggling a collection of instances into the resulting relation. In that respect, the parametrization of TQR is more general than the parametrization of TQC. This suggests generality and parametrization may be viewed along orthogonal axes, which we may represent in the following table, with illustrative examples: 

| | Partial Parametrization...  | ...Total Parametrization |
| :-------------: | :-------------: | :--------: |
| **Less General**  | continuantPartOfTuesday | continuantPartOfTuesdayJohnJohn’sHand  |
| ...  | ...  | ...|
| **More General**  | continuantPartOf∀  | continuantPartOf∃John’sHandJohn  |


Table 1. Generality vs Parametrization

Looking near the upper right of the table, we find shades of TQC and in the lower left we find shades of TQR. Compare both to the upper left of the table, which involves less general partially parametrization, such as continuantPartOfTuesday. A less general partial parametrization proposal to address the particular challenge would likely require many such relations, e.g. continuantPartOfMonday, continuantPartOfWednesday, etc., more than either TQC or TQR. Similarly, compare both to the lower right, which involves more general total parametrization, with respect to universal and/or existential quantification. For example, continuantPartOf∀ might become continuantPartOf∀John’sHandJohn, an individual in the domain reflecting John’s hand as always part of John. A more general total parametrization proposal to address the particular challenge would similarly require the addition of many such relations, perhaps two for each of John’s parts. 
 
<img width="660" alt="Screenshot 2023-07-10 at 4 52 01 PM" src="https://github.com/johnbeve/TQC-Chain-Project/assets/16356971/9a907d1e-2dff-43f3-bbca-5ac5ac2205c2">
