# MicroArrayExpress
This repo encapsulates a thorough microarray analysis exploring differential gene expression in plants exposed to alternating light and darkness. Subsequent KEGG pathway analysis unveils specific pathways undergoing significant modifications, offering nuanced insights into the regulatory networks orchestrating the plant's adaptive mechanisms.

Following statistical analysis, 587 genes exhibited altered expression levels, with 261 genes displaying upregulation and 361 genes undergoing downregulation.
![IMAGEN 1](https://github.com/Bioinformaticareposit/MicroArrayExpress/assets/115641732/fb37998e-4e3f-494b-a04b-cbb4c882a5cd)

Based on the enrichment analysis conducted using ShinyGO, the top 10 pathways with the highest fold enrichment were selected. Consistent with the anticipated response to nutritional starvation, notable enrichments were observed in the starch and nitrogen pathways:


![Pathway analisis](https://github.com/Bioinformaticareposit/MicroArrayExpress/assets/115641732/a4ed9acc-25d4-4a4e-96dc-43dd4ec44503)

Furthermore, the various genes implicated in nitrogen and starch metabolism, exhibiting alterations in expression (highlighted in red), play pivotal roles in both nitrogen uptake and carbon utilization.

![Pathways](https://github.com/Bioinformaticareposit/MicroArrayExpress/assets/115641732/e15078f0-ca79-4eb4-bdd5-083df863152e)


In a brief analysis, this results suggest that under extended night conditions, indicative of carbon starvation, nitrogen assimilation appears to be compromised. This inference is drawn from the downregulation of key enzymes such as Nitrate Reductase, which plays a crucial role in catalyzing the conversion of nitrate to nitrite, a pivotal step in nitrogen assimilation.  A similar conclusion can be drawn for starch metabolism, where the downregulation of enzymes primarily associated with the catabolic process of trehalose suggests potential alterations in energy reserve mobilization. This observation implies that under extended night conditions, indicative of carbon limitation, plants may undergo metabolic adjustments to conserve energy resources, as reflected by the modulation of key enzymes in starch metabolism.
