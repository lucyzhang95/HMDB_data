# HMDB_data
Parser for HMDB database

Current output:
```ruby
{
   "_id":"HMDB0000020",
   "name":"p-Hydroxyphenylacetic acid",
   "chemical_formula":"C8H8O3",
   "description":"p-Hydroxyphenylacetic acid, also known as 4-hydroxybenzeneacetate, is classified as a member of the 1-hydroxy-2-unsubstituted benzenoids. 1-Hydroxy-2-unsubstituted benzenoids are phenols that are unsubstituted at the 2-position. p-Hydroxyphenylacetic acid is considered to be slightly soluble (in water) and acidic.\\xa0 p-Hydroxyphenylacetic acid can be synthesized from acetic acid. It is also a parent compound for other transformation products, including but not limited to, methyl 2-(4-hydroxyphenyl)acetate, ixerochinolide, and lactucopicrin 15-oxalate.\\xa0 p-Hydroxyphenylacetic acid can be found in numerous foods such as olives, cocoa beans, oats, and mushrooms. p-Hydroxyphenylacetic acid can be found throughout all human tissues and in all biofluids. Within a cell, p-hydroxyphenylacetic acid is primarily located in the cytoplasm and in the extracellular space. p-Hydroxyphenylacetic acid is also a microbial metabolite produced by Acinetobacter, Clostridium, Klebsiella, Pseudomonas, and Proteus. Higher levels of this metabolite are associated with an overgrowth of small intestinal bacteria from Clostridia species including C. difficile, C. stricklandii, C. lituseburense, C. subterminale, C. putrefaciens, and C. propionicum (PMID: 476929, 12173102). p-Hydroxyphenylacetic acid is detected after the consumption of whole grain.",
   "xrefs":{
      "smiles":"OC(=O)CC1=CC=C(O)C=C1",
      "inchikey":"XQXPVVBIMDBYFF-UHFFFAOYSA-N",
      "kegg":"KEGG.COMPOUND:C00642",
      "pubchem_cid":"PUBCHEM.COMPOUND:127",
      "chebi":"CHEBI:18101",
      "chemspider":"CHEMSPIDER:124",
      "foodb":"FOODB:FDB010534"
   },
   "associated_microbes":[
      {
         "taxid":287,
         "scientific_name":"pseudomonas aeruginosa",
         "lineage":[
            287,
            136841,
            286,
            135621,
            72274,
            1236,
            1224,
            2,
            131567,
            1
         ],
         "parent_taxid":136841,
         "rank":"species"
      },
      {
         "taxid":573,
         "scientific_name":"klebsiella pneumoniae",
         "lineage":[
            573,
            570,
            2890311,
            543,
            91347,
            1236,
            1224,
            2,
            131567,
            1
         ],
         "parent_taxid":570,
         "rank":"species"
      },
      {
         "taxid":470,
         "scientific_name":"acinetobacter baumannii",
         "lineage":[
            470,
            909768,
            469,
            468,
            2887326,
            1236,
            1224,
            2,
            131567,
            1
         ],
         "parent_taxid":909768,
         "rank":"species"
      },
      {
         "scientific_name":"clostridium difficile"
      },
      {
         "scientific_name":"clostridium lituseburense"
      },
      {
         "scientific_name":"clostridium propionicum"
      },
      {
         "taxid":99675,
         "scientific_name":"clostridium putrefaciens",
         "lineage":[
            99675,
            1485,
            31979,
            186802,
            186801,
            1239,
            1783272,
            2,
            131567,
            1
         ],
         "parent_taxid":1485,
         "rank":"species"
      },
      {
         "scientific_name":"clostridium stricklandii"
      },
      {
         "taxid":1550,
         "scientific_name":"clostridium subterminale",
         "lineage":[
            1550,
            1485,
            31979,
            186802,
            186801,
            1239,
            1783272,
            2,
            131567,
            1
         ],
         "parent_taxid":1485,
         "rank":"species"
      }
   ],
   "associated_pathways":[
      {
         "name":"Alkaptonuria",
         "smpdb_id":"SMP00169"
      },
      {
         "name":"Disulfiram Action Pathway",
         "smpdb_id":"SMP00429"
      },
      {
         "name":"Dopamine beta-hydroxylase deficiency",
         "smpdb_id":"SMP00498"
      },
      {
         "name":"Hawkinsinuria",
         "smpdb_id":"SMP00190"
      },
      {
         "name":"Monoamine oxidase-a deficiency (MAO-A)",
         "smpdb_id":"SMP00533"
      },
      {
         "name":"Tyrosine metabolism",
         "kegg_map_id":"map00350"
      },
      {
         "name":"Tyrosinemia Type I",
         "smpdb_id":"SMP00218"
      },
      {
         "name":"Tyrosinemia, transient, of the newborn",
         "smpdb_id":"SMP00494"
      }
   ],
   "associated_diseases":[
      {
         "name":"Schizophrenia",
         "omim":"OMIM:181500",
         "pmid":[
            115032,
            7126379,
            2480613,
            17276036,
            11877547,
            12796220,
            7595563,
            20814316,
            25004141,
            24713860,
            23823132,
            2415198,
            1694425,
            7711000,
            19390223,
            22024767,
            22007635,
            21483431,
            3741918,
            11979513,
            20206656,
            436860,
            19401681,
            6184954,
            26952797,
            22800120,
            24789758,
            22944140,
            22892715,
            17440431,
            25729574,
            22257447
         ]
      },
      {
         "name":"Epilepsy",
         "pmid":[
            14992292,
            7869898,
            12121313,
            10534261,
            6198481,
            1705463,
            7126379,
            15993662,
            803305,
            10577274,
            19817812,
            10688964,
            436860
         ]
      },
      {
         "name":"Colorectal cancer",
         "omim":"OMIM:114500",
         "pmid":[
            7482520,
            19006102,
            23940645,
            24424155,
            20156336,
            19678709,
            22148915,
            25105552,
            21773981,
            25037050,
            27015276,
            27107423,
            27275383,
            28587349
         ]
      },
      {
         "name":"Ulcerative colitis",
         "pmid":[
            21059682,
            1740537,
            17269711,
            17314143,
            21761941,
            23516449,
            23867873,
            24811995,
            25598765,
            26806034,
            26848182,
            27609529,
            28842642
         ]
      },
      {
         "name":"Crohn's disease",
         "omim":"OMIM:266600",
         "pmid":[
            16440420,
            11418788,
            8723414,
            19491857,
            17269711,
            23516449,
            23867873,
            24811995,
            25598765,
            26806034,
            26848182,
            27609529,
            28842642
         ]
      },
      {
         "name":"Lung Cancer",
         "omim":"OMIM:211980",
         "pmid":[
            22157537,
            18953024,
            25961003
         ]
      },
      {
         "name":"Spina Bifida",
         "omim":"OMIM:182940",
         "pmid":[
            15681999,
            4903899,
            6084371
         ]
      },
      {
         "name":"Eosinophilic esophagitis",
         "omim":"OMIM:610247"
      },
      {
         "name":"Perillyl alcohol administration for cancer treatment",
         "pmid":[
            17668437,
            15607313,
            14569192,
            10379660,
            17403619,
            22284503,
            20300169,
            22061338,
            19783829,
            19010317
         ]
      },
      {
         "name":"Fumarase deficiency",
         "omim":"OMIM:606812",
         "pmid":[
            26078636,
            20549362,
            24182348,
            6616883,
            16972175
         ]
      },
      {
         "name":"Phenylketonuria",
         "omim":"OMIM:261600",
         "pmid":[
            7333014,
            2091926,
            12101068,
            17574536,
            6790852,
            466810,
            2116554,
            19551947,
            25964343,
            15168722,
            4837567
         ]
      }
   ],
   "associated_proteins":[
      {
         "name":"Aldehyde dehydrogenase, dimeric NADP-preferring",
         "uniprotkb":"P30838"
      },
      {
         "name":"Aldehyde dehydrogenase family 1 member A3",
         "uniprotkb":"P47895"
      },
      {
         "name":"UDP-glucuronosyltransferase 1-1",
         "uniprotkb":"P22309"
      },
      {
         "name":"Aldehyde dehydrogenase family 3 member B2",
         "uniprotkb":"P48448"
      },
      {
         "name":"Aldehyde dehydrogenase family 3 member B1",
         "uniprotkb":"P43353"
      },
      {
         "name":"Sulfotransferase 1A3",
         "uniprotkb":"P0DMM9"
      }
   ],
   "status":"quantified",
   "average_mw":152.1473,
   "monoisotopic_mw":152.047344122,
   "state":"solid",
   "biospecimen_samples":[
      "blood",
      "cerebrospinal fluid (csf)",
      "feces",
      "saliva",
      "urine"
   ]
}
```
