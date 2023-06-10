---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Contig: contiguous sequence of DNA (assembled from reads)

Assembly is a set of contigs produced from a dataset(no order, no oreientation)

Additional information: paired-end reads can be used to oreint or order contigs to produce a scaffold

- 2 main frameworks for genome assembly
    - Overlap layout consensus (OLC) framework
    - ....
- 


Overlap consensus:
1. Overlap - build overlap graph
2. Layout - bundle stretches of the overlap graph into contigs
3. Consensus - pick the most likely nucleotide sequence for each contigs 

Overlap (OLC) drawbacks:
1. Building overlap graph is slow
Graph is big ( one node per read). # edges grows super linearly (faster than linear) with # reads in practice
Does not handle repeat well. Turn the overlap graph into Hamiltonian graph.


Example dataset = { ATG AGG TGC TCC GTC GGT GCA CAG }

There are multiple options for the paths




De Brujrin Graph Assembly
- A formulation conceptually similar
- Rather than making each k-mer a node, let's try making them an edge
- That seems odd, but it is rrelated to the overlap idea

The 5mer: GACGG
Has prefix: GACG
Has suffix: ACGG

Example:
4mer: ATTC
Prefix: ATT
Suffix: TTC

Find the path that visits each vertice/edge once.

**IMportant note: can turn this into polynomial time








  ^kkAJoLcK

R = {ATGAT, GATTA, ATTAT, CATGA} with k = 4


 ^6KSQfRq8


# Embedded files
c752a108de290cf5c09e1dd51c080be6e00a702e: [[Pasted Image 20230327143418_331.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.8.23",
	"elements": [
		{
			"type": "text",
			"version": 1645,
			"versionNonce": 994989288,
			"isDeleted": false,
			"id": "kkAJoLcK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -282.98144791573844,
			"y": -529.4894437091084,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1083.06005859375,
			"height": 1400,
			"seed": 67020273,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Contig: contiguous sequence of DNA (assembled from reads)\n\nAssembly is a set of contigs produced from a dataset(no order, no oreientation)\n\nAdditional information: paired-end reads can be used to oreint or order contigs to produce a scaffold\n\n- 2 main frameworks for genome assembly\n    - Overlap layout consensus (OLC) framework\n    - ....\n- \n\n\nOverlap consensus:\n1. Overlap - build overlap graph\n2. Layout - bundle stretches of the overlap graph into contigs\n3. Consensus - pick the most likely nucleotide sequence for each contigs \n\nOverlap (OLC) drawbacks:\n1. Building overlap graph is slow\nGraph is big ( one node per read). # edges grows super linearly (faster than linear) with # reads in practice\nDoes not handle repeat well. Turn the overlap graph into Hamiltonian graph.\n\n\nExample dataset = { ATG AGG TGC TCC GTC GGT GCA CAG }\n\nThere are multiple options for the paths\n\n\n\n\nDe Brujrin Graph Assembly\n- A formulation conceptually similar\n- Rather than making each k-mer a node, let's try making them an edge\n- That seems odd, but it is rrelated to the overlap idea\n\nThe 5mer: GACGG\nHas prefix: GACG\nHas suffix: ACGG\n\nExample:\n4mer: ATTC\nPrefix: ATT\nSuffix: TTC\n\nFind the path that visits each vertice/edge once.\n\n**IMportant note: can turn this into polynomial time\n\n\n\n\n\n\n\n\n ",
			"rawText": "Contig: contiguous sequence of DNA (assembled from reads)\n\nAssembly is a set of contigs produced from a dataset(no order, no oreientation)\n\nAdditional information: paired-end reads can be used to oreint or order contigs to produce a scaffold\n\n- 2 main frameworks for genome assembly\n    - Overlap layout consensus (OLC) framework\n    - ....\n- \n\n\nOverlap consensus:\n1. Overlap - build overlap graph\n2. Layout - bundle stretches of the overlap graph into contigs\n3. Consensus - pick the most likely nucleotide sequence for each contigs \n\nOverlap (OLC) drawbacks:\n1. Building overlap graph is slow\nGraph is big ( one node per read). # edges grows super linearly (faster than linear) with # reads in practice\nDoes not handle repeat well. Turn the overlap graph into Hamiltonian graph.\n\n\nExample dataset = { ATG AGG TGC TCC GTC GGT GCA CAG }\n\nThere are multiple options for the paths\n\n\n\n\nDe Brujrin Graph Assembly\n- A formulation conceptually similar\n- Rather than making each k-mer a node, let's try making them an edge\n- That seems odd, but it is rrelated to the overlap idea\n\nThe 5mer: GACGG\nHas prefix: GACG\nHas suffix: ACGG\n\nExample:\n4mer: ATTC\nPrefix: ATT\nSuffix: TTC\n\nFind the path that visits each vertice/edge once.\n\n**IMportant note: can turn this into polynomial time\n\n\n\n\n\n\n\n\n ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Contig: contiguous sequence of DNA (assembled from reads)\n\nAssembly is a set of contigs produced from a dataset(no order, no oreientation)\n\nAdditional information: paired-end reads can be used to oreint or order contigs to produce a scaffold\n\n- 2 main frameworks for genome assembly\n    - Overlap layout consensus (OLC) framework\n    - ....\n- \n\n\nOverlap consensus:\n1. Overlap - build overlap graph\n2. Layout - bundle stretches of the overlap graph into contigs\n3. Consensus - pick the most likely nucleotide sequence for each contigs \n\nOverlap (OLC) drawbacks:\n1. Building overlap graph is slow\nGraph is big ( one node per read). # edges grows super linearly (faster than linear) with # reads in practice\nDoes not handle repeat well. Turn the overlap graph into Hamiltonian graph.\n\n\nExample dataset = { ATG AGG TGC TCC GTC GGT GCA CAG }\n\nThere are multiple options for the paths\n\n\n\n\nDe Brujrin Graph Assembly\n- A formulation conceptually similar\n- Rather than making each k-mer a node, let's try making them an edge\n- That seems odd, but it is rrelated to the overlap idea\n\nThe 5mer: GACGG\nHas prefix: GACG\nHas suffix: ACGG\n\nExample:\n4mer: ATTC\nPrefix: ATT\nSuffix: TTC\n\nFind the path that visits each vertice/edge once.\n\n**IMportant note: can turn this into polynomial time\n\n\n\n\n\n\n\n\n ",
			"lineHeight": 1.25,
			"baseline": 1392
		},
		{
			"type": "arrow",
			"version": 185,
			"versionNonce": 656133528,
			"isDeleted": false,
			"id": "CDtqUl_zVsqI7IOfTcB2Y",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -27.909274831535015,
			"y": 39.306551050665206,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 100.98580653787619,
			"height": 35.15802153540875,
			"seed": 907322600,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					50.118881763242285,
					-32.91389250123373
				],
				[
					100.98580653787619,
					2.2441290341750175
				]
			]
		},
		{
			"type": "arrow",
			"version": 128,
			"versionNonce": 1132689384,
			"isDeleted": false,
			"id": "L23JItsMgu4cJ87u1g0B7",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 67.09218761520779,
			"y": 58.75566934684878,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 232.64137654281123,
			"height": 50.86692477463396,
			"seed": 953919384,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					109.96232267457634,
					-50.86692477463396
				],
				[
					232.64137654281123,
					-6.732387102525081
				]
			]
		},
		{
			"type": "arrow",
			"version": 135,
			"versionNonce": 1115576984,
			"isDeleted": false,
			"id": "lzP0VBLICrvmKA6sX2XbY",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 287.76487597575215,
			"y": 43.79480911901524,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 73.3082151163843,
			"height": 32.16584948984203,
			"seed": 1253075176,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					36.65410755819221,
					-32.16584948984203
				],
				[
					73.3082151163843,
					-6.732387102525081
				]
			]
		},
		{
			"type": "arrow",
			"version": 124,
			"versionNonce": 1864121064,
			"isDeleted": false,
			"id": "oA6x9HP5Ryyl4tiFg1nN1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.17962518006436,
			"y": 72.79957979931035,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 285.7524303516202,
			"height": 78.54451619612595,
			"seed": 1009472152,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-141.3801291530268,
					78.54451619612595
				],
				[
					-285.7524303516202,
					0
				]
			]
		},
		{
			"type": "image",
			"version": 142,
			"versionNonce": 1275545496,
			"isDeleted": false,
			"id": "E7SZAdtsjp3wE5U0y_O30",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 459.0639164221024,
			"y": 226.56949660812575,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 577.0921949469584,
			"height": 411.57894736842104,
			"seed": 2115317600,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c752a108de290cf5c09e1dd51c080be6e00a702e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "freedraw",
			"version": 82,
			"versionNonce": 1352965608,
			"isDeleted": false,
			"id": "YAli1ZBavwAWXV2VWyct_",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -262.6183580390881,
			"y": 830.9726435340107,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.343393631204464,
			"height": 39.32166732344626,
			"seed": 593901288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516685,
					0
				],
				[
					-1.4043452615516685,
					-1.4043452615516117
				],
				[
					-2.808690523103337,
					-2.808690523103337
				],
				[
					-4.213035784654949,
					-2.808690523103337
				],
				[
					-5.617381046206617,
					-2.808690523103337
				],
				[
					-8.426071569309897,
					-2.808690523103337
				],
				[
					-11.234762092413234,
					-2.808690523103337
				],
				[
					-12.639107353964846,
					0
				],
				[
					-15.447797877068183,
					2.808690523103337
				],
				[
					-15.447797877068183,
					8.426071569309897
				],
				[
					-14.043452615516514,
					9.830416830861509
				],
				[
					-11.234762092413234,
					11.234762092413234
				],
				[
					-7.021726307758286,
					9.830416830861509
				],
				[
					-2.808690523103337,
					7.021726307758286
				],
				[
					-1.4043452615516685,
					5.61738104620656
				],
				[
					0,
					1.4043452615516117
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					-2.808690523103337
				],
				[
					0,
					-1.4043452615516117
				],
				[
					-1.4043452615516685,
					4.213035784654949
				],
				[
					-2.808690523103337,
					11.234762092413234
				],
				[
					-2.808690523103337,
					18.256488400171406
				],
				[
					-4.213035784654949,
					26.682559969481304
				],
				[
					-5.617381046206617,
					32.29994101568798
				],
				[
					-7.021726307758286,
					35.1086315387912
				],
				[
					-9.830416830861566,
					36.512976800342926
				],
				[
					-12.639107353964846,
					33.7042862772397
				],
				[
					-15.447797877068183,
					30.895595754136252
				],
				[
					-16.852143138619795,
					28.08690523103303
				],
				[
					-16.852143138619795,
					25.278214707929692
				],
				[
					-14.043452615516514,
					22.469524184826355
				],
				[
					-9.830416830861566,
					21.065178923274743
				],
				[
					-5.617381046206617,
					18.256488400171406
				],
				[
					2.808690523103337,
					14.043452615516458
				],
				[
					7.021726307758257,
					11.234762092413234
				],
				[
					9.830416830861566,
					8.426071569309897
				],
				[
					11.234762092413206,
					5.61738104620656
				],
				[
					11.234762092413206,
					2.808690523103337
				],
				[
					9.830416830861566,
					0
				],
				[
					8.426071569309897,
					0
				],
				[
					7.021726307758257,
					-1.4043452615516117
				],
				[
					7.021726307758257,
					0
				],
				[
					5.61738104620656,
					1.4043452615516117
				],
				[
					4.213035784654949,
					7.021726307758286
				],
				[
					4.213035784654949,
					11.234762092413234
				],
				[
					5.61738104620656,
					14.043452615516458
				],
				[
					8.426071569309897,
					15.447797877068183
				],
				[
					11.234762092413206,
					14.043452615516458
				],
				[
					14.043452615516514,
					11.234762092413234
				],
				[
					16.852143138619823,
					8.426071569309897
				],
				[
					18.256488400171463,
					5.61738104620656
				],
				[
					19.660833661723103,
					4.213035784654949
				],
				[
					19.660833661723103,
					7.021726307758286
				],
				[
					18.256488400171463,
					9.830416830861509
				],
				[
					18.256488400171463,
					12.639107353964846
				],
				[
					18.256488400171463,
					14.043452615516458
				],
				[
					18.256488400171463,
					11.234762092413234
				],
				[
					19.660833661723103,
					8.426071569309897
				],
				[
					21.06517892327477,
					5.61738104620656
				],
				[
					23.87386944637808,
					2.808690523103337
				],
				[
					25.27821470792972,
					1.4043452615516117
				],
				[
					26.68255996948136,
					4.213035784654949
				],
				[
					26.68255996948136,
					8.426071569309897
				],
				[
					26.68255996948136,
					11.234762092413234
				],
				[
					28.08690523103303,
					12.639107353964846
				],
				[
					29.49125049258467,
					12.639107353964846
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0412517711520195,
				0.03618661314249039,
				0.050029877573251724,
				0.06039898842573166,
				0.06543105840682983,
				0.06965234130620956,
				0.06876294314861298,
				0.072980135679245,
				0.07107864320278168,
				0.05904760584235191,
				0.041701171547174454,
				0.025492951273918152,
				0.017902160063385963,
				0.017734160646796227,
				0.024848388507962227,
				0.060269806534051895,
				0.07549481093883514,
				0.09782467782497406,
				0.1031174585223198,
				0.101374052464962,
				0.09474685788154602,
				0.07396221905946732,
				0.06139535456895828,
				0.027284637093544006,
				0.017206206917762756,
				0.019194457679986954,
				0.033829834312200546,
				0.054793547838926315,
				0.07059036195278168,
				0.07289016991853714,
				0.06764425337314606,
				0.051231443881988525,
				0.030249236151576042,
				0.024722198024392128,
				0.022394835948944092,
				0.032143738120794296,
				0.05069732666015625,
				0.06534457206726074,
				0.08643335103988647,
				0.10160992294549942,
				0.10469534248113632,
				0.10124249011278152,
				0.09254547208547592,
				0.0747532993555069,
				0.05089172348380089,
				0.03783227503299713,
				0.035266052931547165,
				0.03145788609981537,
				0.039225492626428604,
				0.06111731007695198,
				0.07724279910326004,
				0.07944519072771072,
				0.06593057513237,
				0.04337039217352867,
				0.03633657842874527,
				0.04544470086693764,
				0.06663808971643448,
				0.09090353548526764,
				0.10205206274986267,
				0.11186981201171875,
				0.10408654808998108,
				0.08421841263771057,
				0.04845694079995155,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 71,
			"versionNonce": 1877644440,
			"isDeleted": false,
			"id": "oQNv8K6hpuiCg1IS9MkR7",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220.48800019253855,
			"y": 835.1856793186656,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54.769465200514446,
			"height": 15.447797877068183,
			"seed": 623770856,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					-1.40434526155164,
					-1.4043452615516117
				],
				[
					-2.8086905231033086,
					-1.4043452615516117
				],
				[
					-4.213035784654949,
					-1.4043452615516117
				],
				[
					-5.617381046206617,
					1.4043452615516117
				],
				[
					-5.617381046206617,
					4.213035784654949
				],
				[
					-5.617381046206617,
					7.021726307758286
				],
				[
					-4.213035784654949,
					9.830416830861509
				],
				[
					-1.40434526155164,
					11.234762092413234
				],
				[
					0,
					11.234762092413234
				],
				[
					1.40434526155164,
					8.426071569309897
				],
				[
					1.40434526155164,
					5.61738104620656
				],
				[
					1.40434526155164,
					2.808690523103337
				],
				[
					1.40434526155164,
					0
				],
				[
					2.8086905231033086,
					-1.4043452615516117
				],
				[
					4.213035784654949,
					-2.808690523103337
				],
				[
					7.021726307758286,
					-2.808690523103337
				],
				[
					8.426071569309897,
					-1.4043452615516117
				],
				[
					9.830416830861566,
					1.4043452615516117
				],
				[
					9.830416830861566,
					4.213035784654949
				],
				[
					9.830416830861566,
					7.021726307758286
				],
				[
					9.830416830861566,
					8.426071569309897
				],
				[
					8.426071569309897,
					8.426071569309897
				],
				[
					8.426071569309897,
					7.021726307758286
				],
				[
					8.426071569309897,
					4.213035784654949
				],
				[
					9.830416830861566,
					1.4043452615516117
				],
				[
					11.234762092413234,
					-1.4043452615516117
				],
				[
					12.639107353964846,
					-2.808690523103337
				],
				[
					14.043452615516514,
					-2.808690523103337
				],
				[
					15.447797877068183,
					-1.4043452615516117
				],
				[
					15.447797877068183,
					1.4043452615516117
				],
				[
					15.447797877068183,
					4.213035784654949
				],
				[
					15.447797877068183,
					7.021726307758286
				],
				[
					15.447797877068183,
					8.426071569309897
				],
				[
					16.852143138619795,
					5.61738104620656
				],
				[
					16.852143138619795,
					2.808690523103337
				],
				[
					18.256488400171463,
					1.4043452615516117
				],
				[
					19.66083366172313,
					0
				],
				[
					21.0651789232748,
					0
				],
				[
					22.469524184826412,
					2.808690523103337
				],
				[
					23.87386944637808,
					5.61738104620656
				],
				[
					26.68255996948136,
					7.021726307758286
				],
				[
					30.89559575413631,
					7.021726307758286
				],
				[
					33.704286277239646,
					7.021726307758286
				],
				[
					36.512976800342926,
					4.213035784654949
				],
				[
					37.917322061894595,
					0
				],
				[
					37.917322061894595,
					-2.808690523103337
				],
				[
					36.512976800342926,
					-4.213035784654949
				],
				[
					35.108631538791315,
					-4.213035784654949
				],
				[
					32.29994101568798,
					-1.4043452615516117
				],
				[
					30.89559575413631,
					2.808690523103337
				],
				[
					30.89559575413631,
					7.021726307758286
				],
				[
					35.108631538791315,
					9.830416830861509
				],
				[
					46.34339363120449,
					9.830416830861509
				],
				[
					49.15208415430783,
					8.426071569309897
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06696798652410507,
				0.0779084786772728,
				0.09011898934841156,
				0.09310992062091827,
				0.09699661284685135,
				0.08619164675474167,
				0.06169256567955017,
				0.03435495123267174,
				0.018809814006090164,
				0.008347198367118835,
				0.02885391190648079,
				0.05740704387426376,
				0.08594125509262085,
				0.1090460792183876,
				0.12364404648542404,
				0.12622620165348053,
				0.12297796458005905,
				0.11882608383893967,
				0.10702227801084518,
				0.09621066600084305,
				0.07215066254138947,
				0.05220874026417732,
				0.04839056357741356,
				0.07021462917327881,
				0.09259244054555893,
				0.11291415244340897,
				0.125179722905159,
				0.12716138362884521,
				0.12329785525798798,
				0.11012579500675201,
				0.09925051778554916,
				0.0673535168170929,
				0.04814108461141586,
				0.03736752271652222,
				0.07738864421844482,
				0.09669671952724457,
				0.10521179437637329,
				0.11037197709083557,
				0.10966473072767258,
				0.075807586312294,
				0.06899606436491013,
				0.06491448730230331,
				0.0660400390625,
				0.08481506258249283,
				0.09565334767103195,
				0.11816522479057312,
				0.1331862509250641,
				0.1550644487142563,
				0.16221773624420166,
				0.16071593761444092,
				0.15505608916282654,
				0.1541435867547989,
				0.1434730887413025,
				0.033175475895404816,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 31,
			"versionNonce": 1227399400,
			"isDeleted": false,
			"id": "M-y6AgTg-p-EuI4aCf96X",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -112.35341505306138,
			"y": 832.3769887955623,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.065178923274743,
			"height": 19.66083366172313,
			"seed": 513266072,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516685,
					-1.4043452615516117
				],
				[
					2.808690523103337,
					-1.4043452615516117
				],
				[
					4.213035784654949,
					-2.8086905231032233
				],
				[
					4.213035784654949,
					-4.213035784654949
				],
				[
					4.213035784654949,
					-5.61738104620656
				],
				[
					2.808690523103337,
					-7.021726307758172
				],
				[
					0,
					-8.426071569309897
				],
				[
					-4.213035784654949,
					-8.426071569309897
				],
				[
					-8.426071569309897,
					-5.61738104620656
				],
				[
					-9.830416830861566,
					0
				],
				[
					-11.234762092413177,
					5.617381046206674
				],
				[
					-8.426071569309897,
					9.830416830861623
				],
				[
					-1.4043452615516685,
					11.234762092413234
				],
				[
					7.021726307758286,
					9.830416830861623
				],
				[
					9.830416830861566,
					9.830416830861623
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04275710880756378,
				0.0749451294541359,
				0.11756689101457596,
				0.13225057721138,
				0.13828621804714203,
				0.1485288143157959,
				0.15620867908000946,
				0.15160559117794037,
				0.14753875136375427,
				0.1407955288887024,
				0.13399933278560638,
				0.11913061887025833,
				0.08673983812332153,
				0.013627929612994194,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 28,
			"versionNonce": 870072728,
			"isDeleted": false,
			"id": "bPci2G0j5R5x-zgeg-VbL",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -81.45781929892502,
			"y": 828.1639530109073,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.256488400171463,
			"height": 22.469524184826355,
			"seed": 576277480,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					-1.4043452615516685,
					-4.213035784654949
				],
				[
					-2.808690523103337,
					-5.617381046206674
				],
				[
					-5.617381046206617,
					-7.021726307758172
				],
				[
					-8.426071569309954,
					-7.021726307758172
				],
				[
					-11.234762092413234,
					-4.213035784654949
				],
				[
					-14.043452615516514,
					1.4043452615517253
				],
				[
					-14.043452615516514,
					7.021726307758286
				],
				[
					-14.043452615516514,
					11.234762092413234
				],
				[
					-8.426071569309954,
					14.043452615516571
				],
				[
					2.80869052310328,
					15.447797877068183
				],
				[
					4.213035784654949,
					15.447797877068183
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08910498023033142,
				0.11910799890756607,
				0.14754198491573334,
				0.1571703851222992,
				0.152729794383049,
				0.14225757122039795,
				0.13398657739162445,
				0.13241617381572723,
				0.12514734268188477,
				0.0180547796189785,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 44,
			"versionNonce": 942949352,
			"isDeleted": false,
			"id": "wNcoJn9QkRJwl6ai-7lDK",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -47.75353302168537,
			"y": 829.5682982724591,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.447797877068126,
			"height": 22.469524184826355,
			"seed": 921256168,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.808690523103337
				],
				[
					-1.4043452615516685,
					-4.213035784654949
				],
				[
					-2.808690523103337,
					-4.213035784654949
				],
				[
					-4.2130357846550055,
					-4.213035784654949
				],
				[
					-7.021726307758286,
					-4.213035784654949
				],
				[
					-9.830416830861566,
					-2.808690523103337
				],
				[
					-12.639107353964903,
					0
				],
				[
					-14.043452615516514,
					2.8086905231032233
				],
				[
					-14.043452615516514,
					8.426071569309897
				],
				[
					-14.043452615516514,
					11.23476209241312
				],
				[
					-11.234762092413234,
					14.043452615516458
				],
				[
					-7.021726307758286,
					14.043452615516458
				],
				[
					-4.2130357846550055,
					15.44779787706807
				],
				[
					-1.4043452615516685,
					14.043452615516458
				],
				[
					0,
					14.043452615516458
				],
				[
					1.4043452615516117,
					12.639107353964846
				],
				[
					1.4043452615516117,
					11.23476209241312
				],
				[
					1.4043452615516117,
					9.830416830861509
				],
				[
					1.4043452615516117,
					8.426071569309897
				],
				[
					0,
					8.426071569309897
				],
				[
					0,
					9.830416830861509
				],
				[
					0,
					11.23476209241312
				],
				[
					0,
					14.043452615516458
				],
				[
					-1.4043452615516685,
					15.44779787706807
				],
				[
					-1.4043452615516685,
					16.852143138619795
				],
				[
					-1.4043452615516685,
					18.256488400171406
				],
				[
					-1.4043452615516685,
					18.256488400171406
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.062247954308986664,
				0.14139126241207123,
				0.13788500428199768,
				0.14285998046398163,
				0.142470583319664,
				0.1442263424396515,
				0.13954119384288788,
				0.129441037774086,
				0.1280941516160965,
				0.12387137115001678,
				0.1227857694029808,
				0.11866986006498337,
				0.10111343115568161,
				0.07027938961982727,
				0.03335348516702652,
				0,
				0,
				0,
				0.00027957154088653624,
				0.017215026542544365,
				0.0437738336622715,
				0.12428241223096848,
				0.12826275825500488,
				0.11915341019630432,
				0.09618093818426132,
				0.04672125354409218,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1192251032,
			"isDeleted": false,
			"id": "WydZQuVQNbAvKEQV6qNtQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -51.966568806340376,
			"y": 837.994369841769,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.639107353964903,
			"height": 1.4043452615517253,
			"seed": 751594984,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					1.4043452615516685,
					-1.4043452615517253
				],
				[
					5.617381046206617,
					-1.4043452615517253
				],
				[
					11.234762092413234,
					-1.4043452615517253
				],
				[
					12.639107353964903,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06238845735788345,
				0.07303689420223236,
				0.04808758571743965,
				0.016467072069644928,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 735282920,
			"isDeleted": false,
			"id": "fC8a28Q41OZMnwTffetsP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -18.26228252910073,
			"y": 835.1856793186656,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.447797877068126,
			"height": 19.66083366172313,
			"seed": 168160152,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					-2.808690523103337
				],
				[
					0,
					-4.213035784654949
				],
				[
					-1.4043452615516117,
					-5.61738104620656
				],
				[
					-2.80869052310328,
					-7.021726307758286
				],
				[
					-5.61738104620656,
					-7.021726307758286
				],
				[
					-9.830416830861566,
					-7.021726307758286
				],
				[
					-12.639107353964846,
					-4.213035784654949
				],
				[
					-15.447797877068126,
					-1.4043452615516117
				],
				[
					-14.043452615516514,
					9.830416830861509
				],
				[
					-11.234762092413177,
					12.639107353964846
				],
				[
					-1.4043452615516117,
					12.639107353964846
				],
				[
					0,
					12.639107353964846
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05755200237035751,
				0.04907580465078354,
				0.07161556929349899,
				0.12908093631267548,
				0.15430904924869537,
				0.1765131801366806,
				0.18709200620651245,
				0.19011618196964264,
				0.1790059208869934,
				0.164611354470253,
				0.1566253900527954,
				0.06470856070518494,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 24,
			"versionNonce": 1379580824,
			"isDeleted": false,
			"id": "v2mGtdNxQQ5ve6BbTGLZ9",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2.80289639417407,
			"y": 830.9726435340107,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.426071569309897,
			"height": 18.25648840017152,
			"seed": 316272360,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					-2.808690523103337
				],
				[
					0,
					-1.4043452615516117
				],
				[
					-2.808690523103337,
					2.808690523103337
				],
				[
					-4.213035784654949,
					7.021726307758286
				],
				[
					-7.021726307758286,
					11.234762092413234
				],
				[
					-8.426071569309897,
					15.447797877068183
				],
				[
					-8.426071569309897,
					15.447797877068183
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.02654147334396839,
				0.06798990070819855,
				0.12299615144729614,
				0.1262311041355133,
				0.09956051409244537,
				0.08521426469087601,
				0.04030847176909447,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 278030824,
			"isDeleted": false,
			"id": "ysdEEVDCEjTmaWAwfN_zu",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1.3985511326224014,
			"y": 830.9726435340107,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.447797877068183,
			"height": 19.66083366172313,
			"seed": 591371752,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099800,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516685,
					-2.808690523103337
				],
				[
					2.808690523103337,
					-2.808690523103337
				],
				[
					4.213035784654949,
					-2.808690523103337
				],
				[
					7.021726307758286,
					0
				],
				[
					8.426071569309897,
					4.213035784654949
				],
				[
					11.234762092413234,
					8.426071569309897
				],
				[
					12.639107353964903,
					12.639107353964846
				],
				[
					14.043452615516514,
					15.447797877068183
				],
				[
					15.447797877068183,
					16.852143138619795
				],
				[
					15.447797877068183,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10442809760570526,
				0.14691199362277985,
				0.1749960035085678,
				0.17835217714309692,
				0.16915322840213776,
				0.13264800608158112,
				0.07704638689756393,
				0.016727782785892487,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1200588952,
			"isDeleted": false,
			"id": "iRafX7yffFThoSDvjcVtI",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4.218829913584216,
			"y": 837.994369841769,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.66083366172313,
			"height": 0,
			"seed": 981077992,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516685,
					0
				],
				[
					5.617381046206617,
					0
				],
				[
					11.234762092413234,
					0
				],
				[
					16.85214313861985,
					0
				],
				[
					19.66083366172313,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09039306640625,
				0.09605880826711655,
				0.0755622535943985,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 1635577064,
			"isDeleted": false,
			"id": "hMcFXev12i4vQL1vS9O99",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 44.93325424072367,
			"y": 830.9726435340107,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615517253,
			"height": 19.660833661723018,
			"seed": 2042898840,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					0
				],
				[
					0,
					4.213035784654949
				],
				[
					0,
					9.830416830861509
				],
				[
					0,
					14.043452615516458
				],
				[
					0,
					16.852143138619795
				],
				[
					0,
					18.256488400171406
				],
				[
					-1.4043452615517253,
					18.256488400171406
				],
				[
					-1.4043452615517253,
					18.256488400171406
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06061556935310364,
				0.1411861628293991,
				0.1370955854654312,
				0.12292193621397018,
				0.09917037934064865,
				0.04752926528453827,
				0.027233673259615898,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 24,
			"versionNonce": 851621272,
			"isDeleted": false,
			"id": "w9icWLrT_k397R_mIJiZa",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 30.8898016252071,
			"y": 830.9726435340107,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.491250492584697,
			"height": 7.021726307758286,
			"seed": 1506831080,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516685,
					0
				],
				[
					-1.4043452615516685,
					-1.4043452615516117
				],
				[
					1.4043452615516685,
					-2.808690523103337
				],
				[
					7.021726307758229,
					-4.213035784654949
				],
				[
					12.639107353964846,
					-4.213035784654949
				],
				[
					21.065178923274743,
					-5.61738104620656
				],
				[
					26.682559969481417,
					-5.61738104620656
				],
				[
					28.08690523103303,
					-7.021726307758286
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08362597972154617,
				0.1466899961233139,
				0.16856783628463745,
				0.16645824909210205,
				0.09144091606140137,
				0.053547453135252,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 23,
			"versionNonce": 1478430696,
			"isDeleted": false,
			"id": "egPFjA2cz50MmqDydDEON",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 70.21146894865336,
			"y": 828.1639530109073,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615517253,
			"height": 23.87386944637808,
			"seed": 1420335592,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					1.4043452615517253
				],
				[
					0,
					7.021726307758286
				],
				[
					0,
					12.639107353964846
				],
				[
					0,
					16.852143138619795
				],
				[
					0,
					21.065178923274743
				],
				[
					-1.4043452615517253,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.042105987668037415,
				0.08608260750770569,
				0.09335622936487198,
				0.08680291473865509,
				0.0822429209947586,
				0.027015015482902527,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 151536280,
			"isDeleted": false,
			"id": "Ue02Q_nX7Un3jpnHRCdbk",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 58.97670685624013,
			"y": 829.5682982724591,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.46952418482647,
			"height": 1.4043452615517253,
			"seed": 1842826392,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					0
				],
				[
					2.808690523103337,
					-1.4043452615517253
				],
				[
					7.021726307758286,
					-1.4043452615517253
				],
				[
					12.639107353964846,
					-1.4043452615517253
				],
				[
					19.66083366172313,
					-1.4043452615517253
				],
				[
					22.46952418482647,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08103002607822418,
				0.07419561594724655,
				0.062306519597768784,
				0.0389447920024395,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 30,
			"versionNonce": 478466792,
			"isDeleted": false,
			"id": "FqMbSaWSssEHViDALhJx5",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 102.51140996434134,
			"y": 829.5682982724591,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.278214707929692,
			"height": 21.065178923274743,
			"seed": 1835024536,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.808690523103337
				],
				[
					0,
					-4.213035784654949
				],
				[
					-1.4043452615516117,
					-4.213035784654949
				],
				[
					-4.213035784654949,
					-4.213035784654949
				],
				[
					-7.021726307758286,
					-2.808690523103337
				],
				[
					-9.830416830861623,
					0
				],
				[
					-11.234762092413234,
					2.8086905231032233
				],
				[
					-12.639107353964846,
					9.830416830861509
				],
				[
					-11.234762092413234,
					14.043452615516458
				],
				[
					-5.61738104620656,
					16.852143138619795
				],
				[
					2.808690523103337,
					16.852143138619795
				],
				[
					9.830416830861509,
					15.44779787706807
				],
				[
					12.639107353964846,
					15.44779787706807
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.058940641582012177,
				0.08457861095666885,
				0.10184585303068161,
				0.11783803999423981,
				0.11423537880182266,
				0.11945101618766785,
				0.12410284578800201,
				0.12708565592765808,
				0.1306266486644745,
				0.13064388930797577,
				0.13281048834323883,
				0.12786221504211426,
				0.06313256919384003,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 23,
			"versionNonce": 2031366040,
			"isDeleted": false,
			"id": "VRPjPk6ifuzCrfdQLLeDh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 126.38527941071942,
			"y": 830.9726435340107,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.426071569309897,
			"height": 16.852143138619795,
			"seed": 1730422936,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-1.4043452615516117
				],
				[
					1.4043452615516117,
					0
				],
				[
					-1.4043452615516117,
					4.213035784654949
				],
				[
					-4.213035784654949,
					8.426071569309897
				],
				[
					-5.61738104620656,
					12.639107353964846
				],
				[
					-7.021726307758286,
					15.447797877068183
				],
				[
					-7.021726307758286,
					15.447797877068183
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.060563232749700546,
				0.1403937041759491,
				0.12669482827186584,
				0.1093747541308403,
				0.07787308096885681,
				0.03029434196650982,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 1966749160,
			"isDeleted": false,
			"id": "5wQb0W1dBbGzdYH0BWvxt",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 126.38527941071942,
			"y": 830.9726435340107,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 18.25648840017152,
			"seed": 589338856,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-1.4043452615516117
				],
				[
					1.4043452615516117,
					-2.808690523103337
				],
				[
					2.808690523103337,
					-2.808690523103337
				],
				[
					5.61738104620656,
					-1.4043452615516117
				],
				[
					7.021726307758286,
					2.808690523103337
				],
				[
					9.830416830861509,
					7.021726307758286
				],
				[
					11.234762092413234,
					11.234762092413234
				],
				[
					14.043452615516458,
					14.043452615516458
				],
				[
					16.852143138619795,
					15.447797877068183
				],
				[
					16.852143138619795,
					15.447797877068183
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06719961762428284,
				0.08070303499698639,
				0.13853591680526733,
				0.18069198727607727,
				0.2094939947128296,
				0.20965628325939178,
				0.16576208174228668,
				0.12363406270742416,
				0.030879180878400803,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 991591576,
			"isDeleted": false,
			"id": "8iuut6VdDrw5l5FQPhoTn",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 115.15051731830619,
			"y": 836.5900245802172,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 2.808690523103337,
			"seed": 1243794152,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-1.4043452615516117
				],
				[
					4.213035784654949,
					-1.4043452615516117
				],
				[
					14.043452615516571,
					0
				],
				[
					16.852143138619795,
					1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07584161311388016,
				0.08742178231477737,
				0.06744039803743362,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 23,
			"versionNonce": 2001418472,
			"isDeleted": false,
			"id": "YAZOZk3TATB_rTQNcq0hp",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 160.089565687959,
			"y": 832.3769887955623,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 18.256488400171406,
			"seed": 2080691176,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					4.213035784654949
				],
				[
					0,
					8.426071569309897
				],
				[
					0,
					12.639107353964846
				],
				[
					0,
					15.447797877068183
				],
				[
					0,
					16.852143138619795
				],
				[
					0,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0,
				0.19778500497341156,
				0.20778882503509521,
				0.16636642813682556,
				0.10417944192886353,
				0.040514253079891205,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 1624189336,
			"isDeleted": false,
			"id": "-Wbyf2Ag9422qAU78SEEc",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 146.04611307244255,
			"y": 832.3769887955623,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.278214707929692,
			"height": 2.8086905231032233,
			"seed": 2022748824,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					1.4043452615516117,
					-2.8086905231032233
				],
				[
					7.021726307758286,
					-2.8086905231032233
				],
				[
					15.447797877068183,
					-1.4043452615516117
				],
				[
					22.469524184826355,
					-1.4043452615516117
				],
				[
					25.278214707929692,
					-1.4043452615516117
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0871085524559021,
				0.12645675241947174,
				0.12512899935245514,
				0.11570901423692703,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 28,
			"versionNonce": 910416872,
			"isDeleted": false,
			"id": "jppcpzBss3R-yYp-McCkh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 195.19819722675032,
			"y": 828.1639530109073,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.808690523103337,
			"height": 23.87386944637808,
			"seed": 355903128,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					1.4043452615517253
				],
				[
					-1.4043452615516117,
					5.617381046206674
				],
				[
					-1.4043452615516117,
					9.830416830861623
				],
				[
					-1.4043452615516117,
					14.043452615516571
				],
				[
					-2.808690523103337,
					19.66083366172313
				],
				[
					-2.808690523103337,
					22.46952418482647
				],
				[
					-2.808690523103337,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08094000071287155,
				0.23902200162410736,
				0.24011343717575073,
				0.2333546131849289,
				0.22871634364128113,
				0.17979370057582855,
				0.12353186309337616,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 627455640,
			"isDeleted": false,
			"id": "1H7qt2XBnvaYP5Yn1bFKt",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 186.77212565744048,
			"y": 828.1639530109072,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.682559969481304,
			"height": 1.4043452615516117,
			"seed": 313244136,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					0
				],
				[
					0,
					0
				],
				[
					5.617381046206674,
					0
				],
				[
					12.639107353964846,
					0
				],
				[
					22.46952418482647,
					-1.4043452615516117
				],
				[
					25.278214707929692,
					-1.4043452615516117
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05405322089791298,
				0.0984712541103363,
				0.09066925197839737,
				0.07969573885202408,
				0.049464140087366104,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 40,
			"versionNonce": 1949310696,
			"isDeleted": false,
			"id": "N-zjoaYLwvSi9OFa_HJjM",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -351.092109516842,
			"y": 979.8332412584859,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.278214707929692,
			"height": 14.043452615516571,
			"seed": 942376424,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					0
				],
				[
					0,
					4.213035784654949
				],
				[
					0,
					9.830416830861509
				],
				[
					0,
					12.639107353964846
				],
				[
					1.4043452615516117,
					12.639107353964846
				],
				[
					4.213035784654949,
					11.23476209241312
				],
				[
					5.61738104620656,
					8.426071569309897
				],
				[
					8.426071569309897,
					4.213035784654949
				],
				[
					9.830416830861509,
					1.4043452615516117
				],
				[
					11.234762092413234,
					0
				],
				[
					12.639107353964846,
					0
				],
				[
					12.639107353964846,
					4.213035784654949
				],
				[
					12.639107353964846,
					7.021726307758172
				],
				[
					14.043452615516458,
					9.830416830861509
				],
				[
					14.043452615516458,
					11.23476209241312
				],
				[
					15.447797877068183,
					8.426071569309897
				],
				[
					15.447797877068183,
					5.61738104620656
				],
				[
					16.852143138619795,
					2.8086905231032233
				],
				[
					19.66083366172313,
					0
				],
				[
					21.065178923274743,
					-1.4043452615517253
				],
				[
					22.469524184826412,
					-1.4043452615517253
				],
				[
					23.87386944637808,
					1.4043452615516117
				],
				[
					23.87386944637808,
					7.021726307758172
				],
				[
					23.87386944637808,
					9.830416830861509
				],
				[
					23.87386944637808,
					12.639107353964846
				],
				[
					25.278214707929692,
					11.23476209241312
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07159091532230377,
				0.11487463116645813,
				0.11244457960128784,
				0.08978085219860077,
				0.0763835459947586,
				0.07511898875236511,
				0.0729469284415245,
				0.08037970215082169,
				0.09986535459756851,
				0.11952517926692963,
				0.13618503510951996,
				0.14287133514881134,
				0.12214858829975128,
				0.10698229819536209,
				0.06805197149515152,
				0.0566326305270195,
				0.08472836017608643,
				0.11685116589069366,
				0.15430831909179688,
				0.18056762218475342,
				0.1951902210712433,
				0.20256927609443665,
				0.1857890635728836,
				0.15550103783607483,
				0.12616796791553497,
				0.07091162353754044,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 48,
			"versionNonce": 1033085848,
			"isDeleted": false,
			"id": "cA9AJ3_Vxc4Dcu71I3GLp",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -308.9617516702925,
			"y": 984.0462770431409,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.108631538791315,
			"height": 21.065178923274743,
			"seed": 1060881048,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.808690523103337
				],
				[
					-1.4043452615516685,
					-2.808690523103337
				],
				[
					-4.2130357846550055,
					-4.213035784654949
				],
				[
					-7.021726307758229,
					-2.808690523103337
				],
				[
					-11.234762092413234,
					-1.4043452615517253
				],
				[
					-12.639107353964903,
					1.4043452615516117
				],
				[
					-14.043452615516514,
					5.61738104620656
				],
				[
					-12.639107353964903,
					8.426071569309897
				],
				[
					-8.426071569309954,
					8.426071569309897
				],
				[
					-4.2130357846550055,
					8.426071569309897
				],
				[
					-2.80869052310328,
					7.021726307758172
				],
				[
					0,
					4.213035784654949
				],
				[
					1.4043452615516685,
					-1.4043452615517253
				],
				[
					1.4043452615516685,
					-5.617381046206674
				],
				[
					2.80869052310328,
					-9.830416830861623
				],
				[
					1.4043452615516685,
					-8.426071569309897
				],
				[
					0,
					-4.213035784654949
				],
				[
					0,
					0
				],
				[
					0,
					2.8086905231032233
				],
				[
					1.4043452615516685,
					7.021726307758172
				],
				[
					4.213035784654949,
					9.830416830861623
				],
				[
					8.426071569309897,
					11.23476209241312
				],
				[
					12.639107353964846,
					9.830416830861623
				],
				[
					14.043452615516514,
					7.021726307758172
				],
				[
					14.043452615516514,
					2.8086905231032233
				],
				[
					15.447797877068126,
					-1.4043452615517253
				],
				[
					15.447797877068126,
					-4.213035784654949
				],
				[
					12.639107353964846,
					-5.617381046206674
				],
				[
					11.234762092413177,
					-4.213035784654949
				],
				[
					9.830416830861566,
					1.4043452615516117
				],
				[
					9.830416830861566,
					7.021726307758172
				],
				[
					12.639107353964846,
					9.830416830861623
				],
				[
					18.256488400171463,
					9.830416830861623
				],
				[
					21.0651789232748,
					9.830416830861623
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.02850799635052681,
				0.11149624735116959,
				0.14159737527370453,
				0.17070388793945312,
				0.17745831608772278,
				0.17667868733406067,
				0.16138574481010437,
				0.14868880808353424,
				0.12406448274850845,
				0.09888552874326706,
				0.06997305154800415,
				0.05661612004041672,
				0.052519988268613815,
				0.10977932810783386,
				0.14096078276634216,
				0.18317148089408875,
				0.22228476405143738,
				0.20889495313167572,
				0.17986920475959778,
				0.1662854254245758,
				0.13190096616744995,
				0.0967392548918724,
				0.08146447688341141,
				0.07011477649211884,
				0.07691967487335205,
				0.10592614859342575,
				0.1534881889820099,
				0.20553061366081238,
				0.24664676189422607,
				0.26657193899154663,
				0.25588902831077576,
				0.2101300060749054,
				0.13843289017677307,
				0.028785064816474915,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 71,
			"versionNonce": 1369178600,
			"isDeleted": false,
			"id": "nozuekK5dVJ1LBie2nLvz",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -272.44877486994955,
			"y": 982.6419317815892,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 47.74773889275616,
			"height": 35.108631538791315,
			"seed": 703391976,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					-1.4043452615516685,
					-1.4043452615516117
				],
				[
					-2.80869052310328,
					-1.4043452615516117
				],
				[
					-4.213035784654949,
					-1.4043452615516117
				],
				[
					-5.617381046206617,
					0
				],
				[
					-7.021726307758229,
					1.4043452615517253
				],
				[
					-8.426071569309897,
					4.213035784654949
				],
				[
					-9.830416830861566,
					7.021726307758286
				],
				[
					-8.426071569309897,
					9.830416830861623
				],
				[
					-7.021726307758229,
					11.234762092413348
				],
				[
					-4.213035784654949,
					11.234762092413348
				],
				[
					-1.4043452615516685,
					8.426071569309897
				],
				[
					0,
					5.617381046206674
				],
				[
					1.4043452615516685,
					2.808690523103337
				],
				[
					1.4043452615516685,
					1.4043452615517253
				],
				[
					1.4043452615516685,
					0
				],
				[
					1.4043452615516685,
					1.4043452615517253
				],
				[
					0,
					4.213035784654949
				],
				[
					0,
					9.830416830861623
				],
				[
					0,
					14.043452615516571
				],
				[
					0,
					22.46952418482647
				],
				[
					0,
					28.086905231033143
				],
				[
					0,
					32.29994101568809
				],
				[
					0,
					33.7042862772397
				],
				[
					-1.4043452615516685,
					33.7042862772397
				],
				[
					-2.80869052310328,
					29.491250492584754
				],
				[
					-4.213035784654949,
					26.682559969481417
				],
				[
					-4.213035784654949,
					22.46952418482647
				],
				[
					-4.213035784654949,
					18.25648840017152
				],
				[
					-1.4043452615516685,
					14.043452615516571
				],
				[
					1.4043452615516685,
					8.426071569309897
				],
				[
					5.617381046206617,
					4.213035784654949
				],
				[
					9.830416830861566,
					1.4043452615517253
				],
				[
					9.830416830861566,
					0
				],
				[
					9.830416830861566,
					-1.4043452615516117
				],
				[
					8.426071569309954,
					-1.4043452615516117
				],
				[
					11.234762092413177,
					0
				],
				[
					12.639107353964903,
					0
				],
				[
					12.639107353964903,
					1.4043452615517253
				],
				[
					14.043452615516514,
					4.213035784654949
				],
				[
					14.043452615516514,
					7.021726307758286
				],
				[
					15.447797877068183,
					8.426071569309897
				],
				[
					16.852143138619823,
					11.234762092413348
				],
				[
					19.66083366172313,
					11.234762092413348
				],
				[
					22.46952418482644,
					11.234762092413348
				],
				[
					25.27821470792975,
					8.426071569309897
				],
				[
					28.08690523103303,
					5.617381046206674
				],
				[
					28.08690523103303,
					1.4043452615517253
				],
				[
					28.08690523103303,
					0
				],
				[
					28.08690523103303,
					-1.4043452615516117
				],
				[
					25.27821470792975,
					0
				],
				[
					22.46952418482644,
					2.808690523103337
				],
				[
					22.46952418482644,
					5.617381046206674
				],
				[
					22.46952418482644,
					9.830416830861623
				],
				[
					25.27821470792975,
					11.234762092413348
				],
				[
					29.491250492584697,
					12.639107353964846
				],
				[
					36.512976800342955,
					11.234762092413348
				],
				[
					37.917322061894595,
					9.830416830861623
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.047087036073207855,
				0.061775483191013336,
				0.11172494292259216,
				0.11571811139583588,
				0.12376681715250015,
				0.11757803708314896,
				0.11175982654094696,
				0.10335806012153625,
				0.07097665220499039,
				0.047861937433481216,
				0.03475973382592201,
				0.026536254212260246,
				0.03112945519387722,
				0.056374143809080124,
				0.07320208847522736,
				0.10322430729866028,
				0.12372037023305893,
				0.1385040581226349,
				0.15406735241413116,
				0.1632872372865677,
				0.14657269418239594,
				0.10918813943862915,
				0.07303377985954285,
				0.04287133738398552,
				0.007376037538051605,
				0.008078125305473804,
				0.01911349408328533,
				0.04428570717573166,
				0.06638668477535248,
				0.07040014863014221,
				0.06802328675985336,
				0.07147366553544998,
				0.08656707406044006,
				0.09213174134492874,
				0.09052392840385437,
				0.12291250377893448,
				0.14220675826072693,
				0.14849120378494263,
				0.15102986991405487,
				0.1497657150030136,
				0.14027777314186096,
				0.1339532434940338,
				0.12562255561351776,
				0.10788830369710922,
				0.1052732840180397,
				0.10132748633623123,
				0.12354745715856552,
				0.15313959121704102,
				0.1885925531387329,
				0.21962496638298035,
				0.23068152368068695,
				0.21818676590919495,
				0.1894480586051941,
				0.15128634870052338,
				0.12059585750102997,
				0.09712325781583786,
				0.028326231986284256,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 663449752,
			"isDeleted": false,
			"id": "Zzk-Oedvsddo9aP-sqLDg",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -221.8923454540901,
			"y": 982.6419317815892,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.80869052310328,
			"height": 1.4043452615516117,
			"seed": 1287971560,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					0
				],
				[
					-1.4043452615516117,
					-1.4043452615516117
				],
				[
					-2.80869052310328,
					-1.4043452615516117
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08785799890756607,
				0.08785799890756607,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 2106819816,
			"isDeleted": false,
			"id": "S1Ds1nZI-JAY1pzLE5i7f",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -221.8923454540901,
			"y": 988.2593128277958,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615516117,
			"height": 1.4043452615516117,
			"seed": 1012213400,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					0
				],
				[
					-1.4043452615516117,
					1.4043452615516117
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09529199451208115,
				0.03166833519935608,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 28,
			"versionNonce": 2063703448,
			"isDeleted": false,
			"id": "xBUTvLooCO4oeR2iL8DzV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -196.61413074616036,
			"y": 978.4288959969342,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.25648840017152,
			"height": 23.87386944637808,
			"seed": 1528204696,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.8086905231032233
				],
				[
					-1.4043452615516685,
					-4.213035784654949
				],
				[
					-4.213035784654949,
					-5.61738104620656
				],
				[
					-7.021726307758229,
					-5.61738104620656
				],
				[
					-9.830416830861566,
					-4.213035784654949
				],
				[
					-12.639107353964846,
					-1.4043452615516117
				],
				[
					-15.447797877068183,
					5.617381046206674
				],
				[
					-15.447797877068183,
					12.639107353964846
				],
				[
					-9.830416830861566,
					16.852143138619795
				],
				[
					-4.213035784654949,
					18.25648840017152
				],
				[
					2.808690523103337,
					11.234762092413234
				],
				[
					2.808690523103337,
					7.021726307758286
				],
				[
					1.4043452615516685,
					2.808690523103337
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08175863325595856,
				0.13579687476158142,
				0.1950099766254425,
				0.21448400616645813,
				0.24048401415348053,
				0.2530730366706848,
				0.23502810299396515,
				0.20989404618740082,
				0.1833341121673584,
				0.16902059316635132,
				0.1625298708677292,
				0.10204263031482697,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 51,
			"versionNonce": 1705158632,
			"isDeleted": false,
			"id": "1KShTtWQRv5-KLUomo4W_",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -349.6877642552904,
			"y": 1031.794015935897,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 36.512976800342926,
			"height": 16.852143138619795,
			"seed": 1894797288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					-1.4043452615516117,
					-1.4043452615517253
				],
				[
					-2.80869052310328,
					-2.8086905231032233
				],
				[
					-4.213035784654949,
					-2.8086905231032233
				],
				[
					-5.61738104620656,
					-2.8086905231032233
				],
				[
					-8.426071569309897,
					-1.4043452615517253
				],
				[
					-9.830416830861509,
					0
				],
				[
					-12.639107353964846,
					1.4043452615517253
				],
				[
					-12.639107353964846,
					4.213035784654949
				],
				[
					-12.639107353964846,
					8.426071569309897
				],
				[
					-9.830416830861509,
					9.830416830861623
				],
				[
					-5.61738104620656,
					11.23476209241312
				],
				[
					-2.80869052310328,
					11.23476209241312
				],
				[
					-1.4043452615516117,
					9.830416830861623
				],
				[
					-1.4043452615516117,
					7.021726307758172
				],
				[
					-1.4043452615516117,
					2.8086905231032233
				],
				[
					-1.4043452615516117,
					-1.4043452615517253
				],
				[
					0,
					-2.8086905231032233
				],
				[
					2.808690523103337,
					-4.213035784654949
				],
				[
					4.213035784654949,
					-4.213035784654949
				],
				[
					5.617381046206617,
					-2.8086905231032233
				],
				[
					5.617381046206617,
					0
				],
				[
					7.021726307758286,
					2.8086905231032233
				],
				[
					7.021726307758286,
					7.021726307758172
				],
				[
					8.426071569309897,
					11.23476209241312
				],
				[
					11.234762092413234,
					11.23476209241312
				],
				[
					14.043452615516571,
					9.830416830861623
				],
				[
					16.85214313861985,
					7.021726307758172
				],
				[
					16.85214313861985,
					4.213035784654949
				],
				[
					18.25648840017152,
					2.8086905231032233
				],
				[
					18.25648840017152,
					1.4043452615517253
				],
				[
					18.25648840017152,
					0
				],
				[
					18.25648840017152,
					2.8086905231032233
				],
				[
					19.66083366172313,
					7.021726307758172
				],
				[
					19.66083366172313,
					9.830416830861623
				],
				[
					21.0651789232748,
					12.639107353964846
				],
				[
					23.87386944637808,
					12.639107353964846
				],
				[
					23.87386944637808,
					11.23476209241312
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.019999999552965164,
				0,
				0.09067165851593018,
				0.09705398231744766,
				0.1086169108748436,
				0.11724133044481277,
				0.11892446875572205,
				0.1174023449420929,
				0.11451175063848495,
				0.09408624470233917,
				0.067906953394413,
				0.047743987292051315,
				0.02666180394589901,
				0.019266754388809204,
				0.02693411335349083,
				0.06786138564348221,
				0.10101388394832611,
				0.12771917879581451,
				0.1340322643518448,
				0.12850803136825562,
				0.11642559617757797,
				0.10999365150928497,
				0.09545059502124786,
				0.07204300165176392,
				0.03674096614122391,
				0.024013701826334,
				0.02507064864039421,
				0.030777588486671448,
				0.050764985382556915,
				0.08346621692180634,
				0.11317330598831177,
				0.12334185838699341,
				0.11386383324861526,
				0.08479803800582886,
				0.061584196984767914,
				0.029105529189109802,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 959064728,
			"isDeleted": false,
			"id": "BrkW55tP9vPJgs2WR2Hv5",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -317.3878232396024,
			"y": 1026.1766348896904,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.808690523103337,
			"height": 16.852143138619795,
			"seed": 1959545832,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					-1.404345261551498
				],
				[
					1.4043452615517253,
					0
				],
				[
					0,
					4.213035784654949
				],
				[
					-1.4043452615516117,
					8.426071569309897
				],
				[
					-1.4043452615516117,
					14.043452615516571
				],
				[
					-1.4043452615516117,
					15.447797877068297
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07034597545862198,
				0.11664300411939621,
				0.13193103671073914,
				0.10531249642372131,
				0.030028076842427254,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 1708485352,
			"isDeleted": false,
			"id": "77dRS5d_gYKTcbiXvTjHP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -324.40954954736065,
			"y": 1034.6027064590003,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.25648840017152,
			"height": 1.404345261551498,
			"seed": 611522536,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516685,
					0
				],
				[
					-1.4043452615516685,
					-1.404345261551498
				],
				[
					1.4043452615516685,
					-1.404345261551498
				],
				[
					5.617381046206617,
					-1.404345261551498
				],
				[
					11.234762092413177,
					-1.404345261551498
				],
				[
					15.447797877068183,
					-1.404345261551498
				],
				[
					16.85214313861985,
					-1.404345261551498
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09085638076066971,
				0.11984091252088547,
				0.1181563138961792,
				0.05965930223464966,
				0.010950439609587193,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 77,
			"versionNonce": 481892248,
			"isDeleted": false,
			"id": "NZjWa-cdG6G2rXh4BGqrC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -293.51395379322435,
			"y": 1038.8157422436552,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.34339363120455,
			"height": 46.343393631204435,
			"seed": 909815448,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					-1.404345261551498
				],
				[
					-1.4043452615516117,
					-2.8086905231032233
				],
				[
					-2.80869052310328,
					-4.213035784654949
				],
				[
					-4.213035784654949,
					-4.213035784654949
				],
				[
					-7.021726307758229,
					-4.213035784654949
				],
				[
					-8.426071569309897,
					-4.213035784654949
				],
				[
					-11.234762092413177,
					-1.404345261551498
				],
				[
					-12.639107353964846,
					1.4043452615517253
				],
				[
					-12.639107353964846,
					5.617381046206674
				],
				[
					-11.234762092413177,
					8.426071569309897
				],
				[
					-7.021726307758229,
					8.426071569309897
				],
				[
					-4.213035784654949,
					7.021726307758399
				],
				[
					0,
					2.8086905231034507
				],
				[
					1.4043452615516685,
					0
				],
				[
					1.4043452615516685,
					-5.617381046206447
				],
				[
					1.4043452615516685,
					-9.830416830861395
				],
				[
					1.4043452615516685,
					-11.23476209241312
				],
				[
					1.4043452615516685,
					-9.830416830861395
				],
				[
					1.4043452615516685,
					-7.021726307758172
				],
				[
					1.4043452615516685,
					0
				],
				[
					1.4043452615516685,
					2.8086905231034507
				],
				[
					1.4043452615516685,
					8.426071569309897
				],
				[
					4.213035784654949,
					9.830416830861623
				],
				[
					7.021726307758286,
					9.830416830861623
				],
				[
					9.830416830861623,
					7.021726307758399
				],
				[
					11.234762092413234,
					2.8086905231034507
				],
				[
					11.234762092413234,
					-1.404345261551498
				],
				[
					11.234762092413234,
					-4.213035784654949
				],
				[
					11.234762092413234,
					-5.617381046206447
				],
				[
					9.830416830861623,
					-5.617381046206447
				],
				[
					9.830416830861623,
					0
				],
				[
					9.830416830861623,
					4.213035784654949
				],
				[
					11.234762092413234,
					7.021726307758399
				],
				[
					15.447797877068183,
					8.426071569309897
				],
				[
					18.25648840017152,
					8.426071569309897
				],
				[
					21.0651789232748,
					7.021726307758399
				],
				[
					23.87386944637808,
					2.8086905231034507
				],
				[
					23.87386944637808,
					1.4043452615517253
				],
				[
					25.27821470792975,
					-1.404345261551498
				],
				[
					26.682559969481417,
					-2.8086905231032233
				],
				[
					26.682559969481417,
					-4.213035784654949
				],
				[
					25.27821470792975,
					-4.213035784654949
				],
				[
					23.87386944637808,
					-1.404345261551498
				],
				[
					22.46952418482647,
					1.4043452615517253
				],
				[
					22.46952418482647,
					5.617381046206674
				],
				[
					23.87386944637808,
					7.021726307758399
				],
				[
					26.682559969481417,
					8.426071569309897
				],
				[
					29.491250492584754,
					7.021726307758399
				],
				[
					30.895595754136366,
					4.213035784654949
				],
				[
					32.29994101568798,
					1.4043452615517253
				],
				[
					32.29994101568798,
					0
				],
				[
					32.29994101568798,
					2.8086905231034507
				],
				[
					32.29994101568798,
					8.426071569309897
				],
				[
					33.7042862772397,
					15.447797877068297
				],
				[
					33.7042862772397,
					25.278214707929692
				],
				[
					33.7042862772397,
					32.29994101568809
				],
				[
					30.895595754136366,
					35.108631538791315
				],
				[
					28.08690523103303,
					35.108631538791315
				],
				[
					25.27821470792975,
					35.108631538791315
				],
				[
					22.46952418482647,
					30.895595754136366
				],
				[
					22.46952418482647,
					28.086905231033143
				],
				[
					22.46952418482647,
					25.278214707929692
				],
				[
					25.27821470792975,
					22.46952418482647
				],
				[
					26.682559969481417,
					21.065178923274743
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0976259782910347,
				0.13550198078155518,
				0.16101476550102234,
				0.17460736632347107,
				0.19133490324020386,
				0.18781551718711853,
				0.17898166179656982,
				0.15681134164333344,
				0.12295062094926834,
				0.06352292001247406,
				0.03591754287481308,
				0.012175842188298702,
				0.004676879849284887,
				0.08234750479459763,
				0.127137690782547,
				0.1817258596420288,
				0.2227892428636551,
				0.20832300186157227,
				0.18864618241786957,
				0.18621744215488434,
				0.1572389155626297,
				0.12788473069667816,
				0.11198598891496658,
				0.09722186625003815,
				0.09450647234916687,
				0.11214733868837357,
				0.14259375631809235,
				0.17783495783805847,
				0.20626233518123627,
				0.193012997508049,
				0.1543084681034088,
				0.10772760212421417,
				0.06471722573041916,
				0.015637055039405823,
				0,
				0,
				0,
				0.006190338172018528,
				0.07646151632070541,
				0.14208821952342987,
				0.20865200459957123,
				0.21997305750846863,
				0.22044727206230164,
				0.20860974490642548,
				0.19833779335021973,
				0.13426007330417633,
				0.10236355662345886,
				0.09622106701135635,
				0.11436682194471359,
				0.11280212551355362,
				0.16118261218070984,
				0.167958065867424,
				0.16338860988616943,
				0.15800321102142334,
				0.14518295228481293,
				0.13272348046302795,
				0.10075332969427109,
				0.08478061109781265,
				0.11045873910188675,
				0.10704845935106277,
				0.10348986834287643,
				0.043060578405857086,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 2025311720,
			"isDeleted": false,
			"id": "Uwas1sSe5QV4KofFVhT_Y",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -238.7444885927099,
			"y": 1041.6244327667587,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.40434526155164,
			"height": 1.4043452615517253,
			"seed": 143440792,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					-1.40434526155164,
					-1.4043452615517253
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06199798732995987,
				0.03468792885541916,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 1776444568,
			"isDeleted": false,
			"id": "2Ml198rgtzbvyCiPKGIdZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -238.7444885927099,
			"y": 1047.2418138129651,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 1.4043452615517253,
			"seed": 1218069144,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.4043452615517253
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06120086833834648,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 1733677288,
			"isDeleted": false,
			"id": "yzM23NC8DWPNpBpl7TgmX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -223.29669071564172,
			"y": 1041.6244327667587,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.830416830861566,
			"height": 22.46952418482647,
			"seed": 1717123304,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					1.4043452615516117,
					-2.8086905231034507
				],
				[
					4.213035784654949,
					-5.617381046206674
				],
				[
					7.021726307758229,
					-9.830416830861623
				],
				[
					7.021726307758229,
					-12.639107353964846
				],
				[
					8.426071569309897,
					-15.447797877068297
				],
				[
					8.426071569309897,
					-14.043452615516571
				],
				[
					8.426071569309897,
					-11.234762092413348
				],
				[
					8.426071569309897,
					-7.021726307758399
				],
				[
					8.426071569309897,
					-2.8086905231034507
				],
				[
					8.426071569309897,
					2.8086905231032233
				],
				[
					8.426071569309897,
					7.021726307758172
				],
				[
					9.830416830861566,
					7.021726307758172
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.10117001086473465,
				0.08423569053411484,
				0.07346642762422562,
				0.07704547047615051,
				0.10090921074151993,
				0.13077646493911743,
				0.20823083817958832,
				0.22442227602005005,
				0.2378305047750473,
				0.22223372757434845,
				0.19543194770812988,
				0.11672870069742203,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 1046090136,
			"isDeleted": false,
			"id": "gy8Kxzoez_3a8FQQCI2ST",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 53.359325810033624,
			"y": 1059.88092116693,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.87386944637808,
			"height": 25.278214707929692,
			"seed": 638181784,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					0
				],
				[
					2.808690523103337,
					0
				],
				[
					2.808690523103337,
					-1.404345261551498
				],
				[
					4.213035784654949,
					-4.213035784654949
				],
				[
					4.213035784654949,
					-5.617381046206447
				],
				[
					2.808690523103337,
					-8.426071569309897
				],
				[
					1.4043452615517253,
					-8.426071569309897
				],
				[
					-4.213035784654949,
					-8.426071569309897
				],
				[
					-8.426071569309897,
					-5.617381046206447
				],
				[
					-11.234762092413234,
					1.4043452615517253
				],
				[
					-12.639107353964846,
					7.021726307758399
				],
				[
					-11.234762092413234,
					12.639107353964846
				],
				[
					-5.61738104620656,
					16.852143138619795
				],
				[
					0,
					16.852143138619795
				],
				[
					8.426071569309897,
					14.043452615516571
				],
				[
					11.234762092413234,
					14.043452615516571
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.14817199110984802,
				0.18279199302196503,
				0.2037840038537979,
				0.21453848481178284,
				0.21965435147285461,
				0.21643298864364624,
				0.2255280762910843,
				0.2175474315881729,
				0.20790892839431763,
				0.20589855313301086,
				0.21396701037883759,
				0.2118198573589325,
				0.18793758749961853,
				0.13204903900623322,
				0.026457976549863815,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 27,
			"versionNonce": 2033939432,
			"isDeleted": false,
			"id": "WN3KFHvzH3kQIvQl2MGnf",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 84.25492156416999,
			"y": 1061.2852664284817,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.66083366172313,
			"height": 22.46952418482647,
			"seed": 1967117976,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.8086905231032233
				],
				[
					0,
					-4.213035784654949
				],
				[
					1.4043452615516117,
					-5.617381046206674
				],
				[
					1.4043452615516117,
					-7.021726307758172
				],
				[
					0,
					-8.426071569309897
				],
				[
					-2.808690523103337,
					-9.830416830861623
				],
				[
					-7.021726307758286,
					-7.021726307758172
				],
				[
					-9.830416830861623,
					-2.8086905231032233
				],
				[
					-9.830416830861623,
					4.213035784654949
				],
				[
					-7.021726307758286,
					9.830416830861623
				],
				[
					-1.4043452615516117,
					12.639107353964846
				],
				[
					8.426071569309897,
					12.639107353964846
				],
				[
					9.830416830861509,
					11.23476209241312
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0766739770770073,
				0.11288399994373322,
				0.14781799912452698,
				0.17529401183128357,
				0.20129400491714478,
				0.22663535177707672,
				0.23401953279972076,
				0.2284625917673111,
				0.21475204825401306,
				0.18766342103481293,
				0.13676486909389496,
				0.01470877043902874,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 37,
			"versionNonce": 1632902808,
			"isDeleted": false,
			"id": "io_CnCONKHSPYsFkgd5WD",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 123.57658888761625,
			"y": 1057.0722306438267,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 28.086905231033143,
			"seed": 93175448,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.8086905231032233
				],
				[
					-1.4043452615517253,
					-4.213035784654949
				],
				[
					-2.808690523103337,
					-4.213035784654949
				],
				[
					-5.617381046206674,
					-5.617381046206674
				],
				[
					-8.426071569309897,
					-5.617381046206674
				],
				[
					-11.234762092413234,
					-2.8086905231032233
				],
				[
					-14.043452615516571,
					0
				],
				[
					-16.852143138619795,
					4.213035784654949
				],
				[
					-16.852143138619795,
					9.830416830861623
				],
				[
					-15.447797877068183,
					14.043452615516571
				],
				[
					-12.639107353964846,
					18.25648840017152
				],
				[
					-9.830416830861623,
					18.25648840017152
				],
				[
					-7.021726307758286,
					18.25648840017152
				],
				[
					-5.617381046206674,
					16.852143138619795
				],
				[
					-4.213035784654949,
					14.043452615516571
				],
				[
					-4.213035784654949,
					12.639107353964846
				],
				[
					-4.213035784654949,
					11.23476209241312
				],
				[
					-2.808690523103337,
					11.23476209241312
				],
				[
					-2.808690523103337,
					12.639107353964846
				],
				[
					-2.808690523103337,
					16.852143138619795
				],
				[
					-2.808690523103337,
					21.065178923274743
				],
				[
					-4.213035784654949,
					22.46952418482647
				],
				[
					-4.213035784654949,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10396069288253784,
				0.14449651539325714,
				0.1662406027317047,
				0.18316024541854858,
				0.20153048634529114,
				0.20824138820171356,
				0.20737451314926147,
				0.217150017619133,
				0.1998116821050644,
				0.19029070436954498,
				0.17860141396522522,
				0.14319732785224915,
				0.13315637409687042,
				0.13531765341758728,
				0.1413145512342453,
				0.1704512983560562,
				0.197992742061615,
				0.21113131940364838,
				0.2191687375307083,
				0.2122143805027008,
				0.11687536537647247,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 611628776,
			"isDeleted": false,
			"id": "a7RT0m09K-bK6BwqDUC3n",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 113.74617205675463,
			"y": 1066.9026474746884,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.043452615516571,
			"height": 0,
			"seed": 1281394584,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					0
				],
				[
					5.617381046206674,
					0
				],
				[
					12.639107353964846,
					0
				],
				[
					14.043452615516571,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11966101080179214,
				0.13321807980537415,
				0.013034637086093426,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 327453592,
			"isDeleted": false,
			"id": "6BC_dJ8OIZn8idln6WlQh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 151.66349411864928,
			"y": 1064.093956951585,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.682559969481417,
			"height": 25.278214707929692,
			"seed": 1056018072,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					-2.8086905231032233
				],
				[
					0,
					-4.213035784654949
				],
				[
					0,
					-5.617381046206447
				],
				[
					-2.808690523103337,
					-7.021726307758172
				],
				[
					-5.617381046206674,
					-7.021726307758172
				],
				[
					-9.830416830861623,
					-4.213035784654949
				],
				[
					-12.639107353964846,
					1.4043452615517253
				],
				[
					-14.043452615516571,
					9.830416830861623
				],
				[
					-9.830416830861623,
					15.447797877068297
				],
				[
					1.4043452615516117,
					18.25648840017152
				],
				[
					9.830416830861509,
					16.852143138619795
				],
				[
					12.639107353964846,
					15.447797877068297
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07832199335098267,
				0.0930359810590744,
				0.1386459916830063,
				0.17927798628807068,
				0.21448001265525818,
				0.251228004693985,
				0.2598685324192047,
				0.27568522095680237,
				0.27692949771881104,
				0.28137701749801636,
				0.18857058882713318,
				0.08935757726430893,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 31,
			"versionNonce": 1032690152,
			"isDeleted": false,
			"id": "CI_poFGaEzDTg2I7RfDz-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 258.39373399657484,
			"y": 1072.5200285208948,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.66083366172313,
			"height": 25.278214707929692,
			"seed": 615422952,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-1.404345261551498
				],
				[
					2.8086905231032233,
					-2.8086905231032233
				],
				[
					2.8086905231032233,
					-4.213035784654949
				],
				[
					2.8086905231032233,
					-7.021726307758172
				],
				[
					2.8086905231032233,
					-8.426071569309897
				],
				[
					1.4043452615516117,
					-9.830416830861395
				],
				[
					-1.4043452615517253,
					-9.830416830861395
				],
				[
					-4.213035784654949,
					-11.23476209241312
				],
				[
					-7.021726307758286,
					-9.830416830861395
				],
				[
					-8.426071569310011,
					-8.426071569309897
				],
				[
					-11.234762092413234,
					-4.213035784654949
				],
				[
					-12.63910735396496,
					1.4043452615517253
				],
				[
					-12.63910735396496,
					7.021726307758399
				],
				[
					-9.830416830861623,
					11.234762092413348
				],
				[
					-5.617381046206674,
					14.043452615516571
				],
				[
					0,
					14.043452615516571
				],
				[
					5.61738104620656,
					14.043452615516571
				],
				[
					7.021726307758172,
					12.639107353964846
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05324999988079071,
				0.11375857889652252,
				0.155025914311409,
				0.18764929473400116,
				0.20135830342769623,
				0.22514428198337555,
				0.20871137082576752,
				0.2074563056230545,
				0.2044409215450287,
				0.2002972960472107,
				0.19027826189994812,
				0.1862286925315857,
				0.1785854548215866,
				0.15889349579811096,
				0.13661164045333862,
				0.07309430092573166,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 44,
			"versionNonce": 1595889816,
			"isDeleted": false,
			"id": "MXiEhUHTpWuuqozHcyRvG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 293.50236553536604,
			"y": 1069.7113379977916,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.447797877068183,
			"height": 26.68255996948119,
			"seed": 1934887320,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.8086905231032233
				],
				[
					-1.4043452615516117,
					-4.213035784654949
				],
				[
					-1.4043452615516117,
					-5.617381046206674
				],
				[
					-2.8086905231032233,
					-5.617381046206674
				],
				[
					-4.213035784654949,
					-7.021726307758172
				],
				[
					-5.61738104620656,
					-7.021726307758172
				],
				[
					-7.021726307758172,
					-5.617381046206674
				],
				[
					-8.426071569309897,
					-4.213035784654949
				],
				[
					-9.830416830861509,
					-1.4043452615517253
				],
				[
					-11.23476209241312,
					0
				],
				[
					-12.639107353964846,
					1.4043452615517253
				],
				[
					-14.043452615516458,
					2.8086905231032233
				],
				[
					-14.043452615516458,
					4.213035784654949
				],
				[
					-15.447797877068183,
					5.617381046206674
				],
				[
					-15.447797877068183,
					7.021726307758172
				],
				[
					-15.447797877068183,
					8.426071569309897
				],
				[
					-15.447797877068183,
					9.830416830861623
				],
				[
					-15.447797877068183,
					12.639107353964846
				],
				[
					-15.447797877068183,
					14.043452615516571
				],
				[
					-15.447797877068183,
					15.44779787706807
				],
				[
					-15.447797877068183,
					16.852143138619795
				],
				[
					-14.043452615516458,
					18.25648840017152
				],
				[
					-12.639107353964846,
					18.25648840017152
				],
				[
					-11.23476209241312,
					19.660833661723018
				],
				[
					-9.830416830861509,
					19.660833661723018
				],
				[
					-8.426071569309897,
					19.660833661723018
				],
				[
					-7.021726307758172,
					18.25648840017152
				],
				[
					-5.61738104620656,
					16.852143138619795
				],
				[
					-2.8086905231032233,
					15.44779787706807
				],
				[
					-2.8086905231032233,
					14.043452615516571
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07172998040914536,
				0.08180130273103714,
				0.1190125122666359,
				0.13174857199192047,
				0.14324508607387543,
				0.14578963816165924,
				0.14325647056102753,
				0.14277713000774384,
				0.14400671422481537,
				0.14673800766468048,
				0.14816811680793762,
				0.15188683569431305,
				0.15558123588562012,
				0.15808682143688202,
				0.15787078440189362,
				0.15551592409610748,
				0.15454061329364777,
				0.15462476015090942,
				0.14790548384189606,
				0.14338040351867676,
				0.14151836931705475,
				0.13977181911468506,
				0.1406632363796234,
				0.1409156173467636,
				0.13526910543441772,
				0.1337684988975525,
				0.13580389320850372,
				0.130630224943161,
				0.05885305628180504,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 663887080,
			"isDeleted": false,
			"id": "O81bxucRUTxA6OXWJ-uVA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 286.48063922760787,
			"y": 1079.5417548286532,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.639107353964846,
			"height": 14.043452615516571,
			"seed": 1603546088,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099801,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					0
				],
				[
					-2.808690523103337,
					1.404345261551498
				],
				[
					-1.4043452615517253,
					0
				],
				[
					1.4043452615516117,
					0
				],
				[
					4.213035784654949,
					0
				],
				[
					7.021726307758172,
					0
				],
				[
					8.426071569309897,
					0
				],
				[
					9.830416830861509,
					0
				],
				[
					9.830416830861509,
					1.404345261551498
				],
				[
					9.830416830861509,
					4.213035784654949
				],
				[
					9.830416830861509,
					7.021726307758172
				],
				[
					9.830416830861509,
					12.639107353964846
				],
				[
					8.426071569309897,
					14.043452615516571
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.009204406291246414,
				0.08947540074586868,
				0.09434832632541656,
				0.09535568207502365,
				0.09659671038389206,
				0.10095257312059402,
				0.10610070824623108,
				0.11672887951135635,
				0.12291979789733887,
				0.11692099273204803,
				0.026923736557364464,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 1742243224,
			"isDeleted": false,
			"id": "F31iytl8UrNxJNkXUBZtQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 321.58927076639907,
			"y": 1075.3287190439983,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.46952418482647,
			"height": 28.086905231032915,
			"seed": 1830601112,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.808690523103337,
					-1.4043452615517253
				],
				[
					4.213035784654949,
					-2.8086905231034507
				],
				[
					4.213035784654949,
					-5.617381046206674
				],
				[
					5.617381046206674,
					-7.021726307758399
				],
				[
					2.808690523103337,
					-12.639107353964846
				],
				[
					1.4043452615517253,
					-12.639107353964846
				],
				[
					-1.4043452615516117,
					-12.639107353964846
				],
				[
					-4.213035784654949,
					-9.830416830861623
				],
				[
					-7.021726307758172,
					-5.617381046206674
				],
				[
					-8.426071569309897,
					1.404345261551498
				],
				[
					-8.426071569309897,
					8.426071569309897
				],
				[
					-4.213035784654949,
					12.639107353964846
				],
				[
					1.4043452615517253,
					15.44779787706807
				],
				[
					8.426071569310011,
					15.44779787706807
				],
				[
					12.63910735396496,
					14.043452615516344
				],
				[
					14.043452615516571,
					12.639107353964846
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.076851986348629,
				0.08801611512899399,
				0.11523135006427765,
				0.13447733223438263,
				0.1569249927997589,
				0.17061227560043335,
				0.15535852313041687,
				0.15747778117656708,
				0.15192337334156036,
				0.14825710654258728,
				0.14452749490737915,
				0.11270281672477722,
				0.07649508863687515,
				0.01786007732152939,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 68042728,
			"isDeleted": false,
			"id": "mMhVhD4vNurPvYgv6Q04y",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 353.88921178208705,
			"y": 1066.9026474746884,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.830416830861509,
			"height": 23.873869446378194,
			"seed": 1243002520,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.8086905231034507
				],
				[
					0,
					-1.4043452615517253
				],
				[
					-2.8086905231032233,
					2.8086905231032233
				],
				[
					-4.213035784654949,
					7.021726307758172
				],
				[
					-8.426071569309897,
					15.44779787706807
				],
				[
					-9.830416830861509,
					19.660833661723018
				],
				[
					-9.830416830861509,
					21.065178923274743
				],
				[
					-9.830416830861509,
					19.660833661723018
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0657704770565033,
				0.08267999440431595,
				0.1271841675043106,
				0.1389101892709732,
				0.1233014240860939,
				0.0961412638425827,
				0.047579437494277954,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 24,
			"versionNonce": 988025496,
			"isDeleted": false,
			"id": "DiIH9ASSqsgk5_oIPRWr1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 352.48486652053543,
			"y": 1069.7113379977916,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 23.873869446377967,
			"seed": 1184845288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.808690523103337,
					-4.213035784654949
				],
				[
					2.808690523103337,
					-5.617381046206674
				],
				[
					5.617381046206674,
					-7.021726307758172
				],
				[
					7.021726307758286,
					-4.213035784654949
				],
				[
					8.426071569309897,
					0
				],
				[
					11.234762092413234,
					5.617381046206674
				],
				[
					12.639107353964846,
					9.830416830861623
				],
				[
					15.447797877068183,
					14.043452615516571
				],
				[
					16.852143138619795,
					15.44779787706807
				],
				[
					16.852143138619795,
					16.852143138619795
				],
				[
					16.852143138619795,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08671798557043076,
				0.12254998832941055,
				0.1539279818534851,
				0.1802559792995453,
				0.18132872879505157,
				0.17126846313476562,
				0.11863110214471817,
				0.05623602122068405,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 1661862632,
			"isDeleted": false,
			"id": "7QB_BJ06OXMMn8P4fXrjd",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 348.2718307358805,
			"y": 1078.1374095671015,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.46952418482647,
			"height": 1.4043452615517253,
			"seed": 1792316056,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					0
				],
				[
					2.808690523103337,
					-1.4043452615517253
				],
				[
					7.021726307758286,
					-1.4043452615517253
				],
				[
					18.25648840017152,
					-1.4043452615517253
				],
				[
					22.46952418482647,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.06150549277663231,
				0.0584457702934742,
				0.04233730956912041,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 32,
			"versionNonce": 519438232,
			"isDeleted": false,
			"id": "_dDkzEi99VEg4QwWhhSYh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 456.40641587535765,
			"y": 1064.093956951585,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.85214313861991,
			"height": 28.086905231032915,
			"seed": 329419752,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					0
				],
				[
					2.808690523103337,
					-1.404345261551498
				],
				[
					4.213035784654949,
					-2.8086905231032233
				],
				[
					5.617381046206674,
					-4.213035784654949
				],
				[
					5.617381046206674,
					-5.617381046206447
				],
				[
					4.213035784654949,
					-7.021726307758172
				],
				[
					1.4043452615517253,
					-7.021726307758172
				],
				[
					-1.4043452615516117,
					-7.021726307758172
				],
				[
					-2.808690523103337,
					-5.617381046206447
				],
				[
					-5.61738104620656,
					-4.213035784654949
				],
				[
					-8.426071569309897,
					0
				],
				[
					-9.830416830861509,
					5.617381046206674
				],
				[
					-11.234762092413234,
					11.234762092413348
				],
				[
					-9.830416830861509,
					15.447797877068297
				],
				[
					-7.021726307758286,
					18.25648840017152
				],
				[
					-1.4043452615516117,
					21.065178923274743
				],
				[
					1.4043452615517253,
					21.065178923274743
				],
				[
					5.617381046206674,
					19.660833661723245
				],
				[
					5.617381046206674,
					19.660833661723245
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0524207167327404,
				0.06201351806521416,
				0.09998245537281036,
				0.12937191128730774,
				0.17196041345596313,
				0.18072588741779327,
				0.17794732749462128,
				0.17143334448337555,
				0.1679515391588211,
				0.16481737792491913,
				0.15706060826778412,
				0.1464722603559494,
				0.1333121657371521,
				0.12060589343309402,
				0.09866979718208313,
				0.060786254703998566,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 1931306472,
			"isDeleted": false,
			"id": "LR9B77aoKOgF5hPFTp5Mo",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 455.00207061380604,
			"y": 1075.3287190439983,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.639107353964846,
			"height": 12.639107353964846,
			"seed": 505391256,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					1.4043452615516117,
					-1.4043452615517253
				],
				[
					4.213035784654949,
					-2.8086905231034507
				],
				[
					5.61738104620656,
					-2.8086905231034507
				],
				[
					8.426071569309897,
					-2.8086905231034507
				],
				[
					9.830416830861509,
					-2.8086905231034507
				],
				[
					11.234762092413234,
					-1.4043452615517253
				],
				[
					12.639107353964846,
					0
				],
				[
					12.639107353964846,
					4.213035784654949
				],
				[
					12.639107353964846,
					7.021726307758172
				],
				[
					11.234762092413234,
					9.830416830861395
				],
				[
					11.234762092413234,
					9.830416830861395
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04998648166656494,
				0.046915773302316666,
				0.07654134929180145,
				0.10780883580446243,
				0.12223868072032928,
				0.13860122859477997,
				0.1549680233001709,
				0.16585314273834229,
				0.1365789771080017,
				0.07590722292661667,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 30,
			"versionNonce": 1682066584,
			"isDeleted": false,
			"id": "2RFbSoLqoLJ02NkjG6peU",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 491.51504741414897,
			"y": 1072.5200285208948,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.256488400171406,
			"height": 26.68255996948119,
			"seed": 1032307608,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					-2.8086905231032233
				],
				[
					0,
					-4.213035784654949
				],
				[
					0,
					-5.617381046206447
				],
				[
					0,
					-8.426071569309897
				],
				[
					-1.4043452615516117,
					-8.426071569309897
				],
				[
					-4.213035784654949,
					-9.830416830861395
				],
				[
					-5.61738104620656,
					-9.830416830861395
				],
				[
					-8.426071569309897,
					-9.830416830861395
				],
				[
					-11.234762092413234,
					-7.021726307758172
				],
				[
					-15.447797877068183,
					0
				],
				[
					-16.852143138619795,
					5.617381046206674
				],
				[
					-15.447797877068183,
					11.234762092413348
				],
				[
					-11.234762092413234,
					15.447797877068297
				],
				[
					-5.61738104620656,
					16.852143138619795
				],
				[
					0,
					16.852143138619795
				],
				[
					1.4043452615516117,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07535699754953384,
				0.08822598308324814,
				0.11618997156620026,
				0.1353067308664322,
				0.1508718878030777,
				0.15497949719429016,
				0.160967618227005,
				0.16157546639442444,
				0.1550714671611786,
				0.14832192659378052,
				0.12547552585601807,
				0.12231933325529099,
				0.11801556497812271,
				0.10293557494878769,
				0.07152200490236282,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 826829032,
			"isDeleted": false,
			"id": "MA76--o0lp52I8Xp-venP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 504.1541547681138,
			"y": 1085.1591358748597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.065178923274743,
			"height": 23.873869446378194,
			"seed": 701758696,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.4043452615517253
				],
				[
					0,
					2.8086905231034507
				],
				[
					1.4043452615517253,
					0
				],
				[
					4.213035784654949,
					-4.213035784654949
				],
				[
					5.617381046206674,
					-8.426071569309897
				],
				[
					9.830416830861623,
					-14.043452615516344
				],
				[
					11.234762092413234,
					-18.256488400171293
				],
				[
					12.639107353964846,
					-21.065178923274743
				],
				[
					14.043452615516571,
					-21.065178923274743
				],
				[
					15.447797877068183,
					-19.660833661723018
				],
				[
					16.852143138619795,
					-14.043452615516344
				],
				[
					16.852143138619795,
					-11.23476209241312
				],
				[
					18.25648840017152,
					-7.021726307758172
				],
				[
					19.66083366172313,
					-2.8086905231032233
				],
				[
					21.065178923274743,
					0
				],
				[
					21.065178923274743,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.05738439783453941,
				0.08850347995758057,
				0.09296654909849167,
				0.08966201543807983,
				0.08693045377731323,
				0.09039895981550217,
				0.1043565645813942,
				0.12279529124498367,
				0.1344824880361557,
				0.1356142908334732,
				0.13576696813106537,
				0.10845175385475159,
				0.04751406982541084,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 880605592,
			"isDeleted": false,
			"id": "KWH0_GztJcwqldiyIpwcB",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 501.3454642450105,
			"y": 1076.7330643055498,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.491250492584754,
			"height": 1.404345261551498,
			"seed": 512210920,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					0
				],
				[
					4.213035784655062,
					0
				],
				[
					9.830416830861623,
					-1.404345261551498
				],
				[
					15.447797877068183,
					-1.404345261551498
				],
				[
					28.08690523103303,
					-1.404345261551498
				],
				[
					29.491250492584754,
					-1.404345261551498
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05323248356580734,
				0.05645846575498581,
				0.06710150092840195,
				0.07288775593042374,
				0.008879486471414566,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 23,
			"versionNonce": 421202920,
			"isDeleted": false,
			"id": "GyGEHeT5W-ocmsIJjR1us",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 551.9018936608701,
			"y": 1069.7113379977916,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615517253,
			"height": 21.065178923274743,
			"seed": 1327006696,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					-1.4043452615517253,
					-1.4043452615517253
				],
				[
					-1.4043452615517253,
					-2.8086905231032233
				],
				[
					-1.4043452615517253,
					-1.4043452615517253
				],
				[
					-1.4043452615517253,
					2.8086905231032233
				],
				[
					-1.4043452615517253,
					8.426071569309897
				],
				[
					-1.4043452615517253,
					12.639107353964846
				],
				[
					-1.4043452615517253,
					16.852143138619795
				],
				[
					-1.4043452615517253,
					18.25648840017152
				],
				[
					-1.4043452615517253,
					18.25648840017152
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09133398532867432,
				0.12687399983406067,
				0.1759919971227646,
				0.19350698590278625,
				0.18575891852378845,
				0.14094866812229156,
				0.0729237049818039,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 1658455704,
			"isDeleted": false,
			"id": "hiqk-JKS_zHc-jeFRJxqZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 537.8584410453535,
			"y": 1065.4983022131366,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.065178923274743,
			"height": 2.8086905231032233,
			"seed": 602830312,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.8086905231032233
				],
				[
					4.213035784654949,
					-2.8086905231032233
				],
				[
					11.23476209241312,
					-2.8086905231032233
				],
				[
					18.25648840017152,
					-2.8086905231032233
				],
				[
					21.065178923274743,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09161599725484848,
				0.11876199394464493,
				0.12208627164363861,
				0.09213437139987946,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 28,
			"versionNonce": 1419857640,
			"isDeleted": false,
			"id": "wc52mYdm5m8PNUWg5EHkY",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 666.3560324773296,
			"y": 1083.7547906133077,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.660833661723245,
			"height": 26.682559969481417,
			"seed": 744186776,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.404345261551498,
					1.4043452615517253
				],
				[
					2.8086905231032233,
					1.4043452615517253
				],
				[
					4.213035784654949,
					0
				],
				[
					5.617381046206447,
					-2.8086905231032233
				],
				[
					5.617381046206447,
					-5.617381046206447
				],
				[
					4.213035784654949,
					-8.426071569309897
				],
				[
					1.404345261551498,
					-9.830416830861395
				],
				[
					-2.8086905231034507,
					-9.830416830861395
				],
				[
					-7.021726307758399,
					-8.426071569309897
				],
				[
					-9.830416830861623,
					-4.213035784654949
				],
				[
					-11.234762092413348,
					2.8086905231034507
				],
				[
					-11.234762092413348,
					9.830416830861623
				],
				[
					-5.617381046206674,
					15.447797877068297
				],
				[
					5.617381046206447,
					16.852143138620022
				],
				[
					8.426071569309897,
					16.852143138620022
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10204367339611053,
				0.13224606215953827,
				0.1508680135011673,
				0.166654571890831,
				0.17504632472991943,
				0.18909451365470886,
				0.19711562991142273,
				0.1866466999053955,
				0.18265201151371002,
				0.169083371758461,
				0.15972848236560822,
				0.1320260912179947,
				0.05944931134581566,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 28,
			"versionNonce": 1007514520,
			"isDeleted": false,
			"id": "_atbJzL17liclZ-Cw9--K",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 681.8038303543976,
			"y": 1099.202588490376,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.25648840017152,
			"height": 23.873869446378194,
			"seed": 1205983720,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-2.8086905231034507
				],
				[
					1.4043452615517253,
					-4.213035784654949
				],
				[
					4.213035784654949,
					-8.426071569309897
				],
				[
					5.617381046206674,
					-11.234762092413348
				],
				[
					8.426071569309897,
					-16.852143138619795
				],
				[
					11.234762092413348,
					-22.46952418482647
				],
				[
					12.639107353964846,
					-23.873869446378194
				],
				[
					14.043452615516571,
					-22.46952418482647
				],
				[
					14.043452615516571,
					-19.660833661723245
				],
				[
					15.447797877068297,
					-14.043452615516571
				],
				[
					16.852143138619795,
					-9.830416830861623
				],
				[
					18.25648840017152,
					-5.617381046206674
				],
				[
					18.25648840017152,
					-1.4043452615517253
				],
				[
					18.25648840017152,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.04036663845181465,
				0.03689657524228096,
				0.05043331906199455,
				0.057399872690439224,
				0.06664913892745972,
				0.10149350017309189,
				0.13602563738822937,
				0.1569117158651352,
				0.16861480474472046,
				0.1644640564918518,
				0.1264089047908783,
				0.077516570687294,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 1818702312,
			"isDeleted": false,
			"id": "K4V3hMryfiwK15Ln4nX2P",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 676.1864493081912,
			"y": 1089.3721716595144,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.49125049258464,
			"height": 2.8086905231032233,
			"seed": 513474712,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.8086905231032233
				],
				[
					2.8086905231032233,
					-2.8086905231032233
				],
				[
					8.426071569309897,
					-2.8086905231032233
				],
				[
					16.852143138619795,
					-2.8086905231032233
				],
				[
					26.68255996948119,
					-2.8086905231032233
				],
				[
					29.49125049258464,
					-2.8086905231032233
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08144598454236984,
				0.0913899838924408,
				0.09660809487104416,
				0.10459613054990768,
				0.03445764258503914,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1447772312,
			"isDeleted": false,
			"id": "3WHSacY0o7xQxZohf2she",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 722.5298429393956,
			"y": 1078.1374095671013,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.404345261551498,
			"height": 18.256488400171293,
			"seed": 1420424344,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.404345261551498,
					0
				],
				[
					1.404345261551498,
					2.8086905231032233
				],
				[
					1.404345261551498,
					7.021726307758172
				],
				[
					1.404345261551498,
					11.23476209241312
				],
				[
					1.404345261551498,
					15.44779787706807
				],
				[
					1.404345261551498,
					16.852143138619795
				],
				[
					0,
					18.256488400171293
				],
				[
					0,
					18.256488400171293
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07974798232316971,
				0.16312798857688904,
				0.1564362496137619,
				0.1346728801727295,
				0.10620877146720886,
				0.047353025525808334,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 2004399336,
			"isDeleted": false,
			"id": "BO_od_9ogrldxWlyGZW0F",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 709.8907355854308,
			"y": 1076.7330643055495,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.873869446377967,
			"height": 1.4043452615517253,
			"seed": 1407587736,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					2.8086905231032233,
					-1.4043452615517253
				],
				[
					7.021726307758172,
					-1.4043452615517253
				],
				[
					14.043452615516344,
					-1.4043452615517253
				],
				[
					22.46952418482647,
					-1.4043452615517253
				],
				[
					23.873869446377967,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05728521570563316,
				0.09449795633554459,
				0.1144222691655159,
				0.09595587104558945,
				0.020923035219311714,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1632071064,
			"isDeleted": false,
			"id": "r7tMrViyfzk_Ux4xO7Ms0",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 753.425438693532,
			"y": 1075.3287190439978,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615517253,
			"height": 19.660833661723018,
			"seed": 625117592,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					0
				],
				[
					0,
					4.213035784654949
				],
				[
					0,
					8.426071569309897
				],
				[
					0,
					14.043452615516571
				],
				[
					0,
					16.852143138619795
				],
				[
					0,
					18.25648840017152
				],
				[
					-1.4043452615517253,
					18.25648840017152
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.14533600211143494,
				0.17486199736595154,
				0.18759506940841675,
				0.1701183170080185,
				0.08691192418336868,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 1264703464,
			"isDeleted": false,
			"id": "YTZWAuonwL6_qTsKDpWeM",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 742.1906766011186,
			"y": 1072.5200285208946,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.70428627723959,
			"height": 4.213035784654949,
			"seed": 1770097304,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					7.021726307758399,
					0
				],
				[
					29.49125049258464,
					-2.8086905231032233
				],
				[
					33.70428627723959,
					-4.213035784654949
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.15618902444839478,
				0.17886899411678314,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1983249048,
			"isDeleted": false,
			"id": "EoOnCRkoRTHkgb5_CR8Zv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249.2654897964889,
			"y": 1215.763245199163,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.808690523103337,
			"height": 25.27821470792992,
			"seed": 1199337704,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					-2.8086905231034507
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					1.4043452615517253
				],
				[
					1.4043452615516117,
					14.043452615516571
				],
				[
					1.4043452615516117,
					19.660833661723245
				],
				[
					1.4043452615516117,
					22.46952418482647
				],
				[
					2.808690523103337,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.06662872433662415,
				0.1248757615685463,
				0.15211638808250427,
				0.12453082203865051,
				0.11948651075363159,
				0.00753698730841279,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 741251816,
			"isDeleted": false,
			"id": "BmWIGPGVVkxSVVL9RU5Tc",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 233.81769191942072,
			"y": 1217.1675904607148,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 37.91732206189454,
			"height": 2.8086905231032233,
			"seed": 1477500904,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					-1.4043452615517253
				],
				[
					0,
					-1.4043452615517253
				],
				[
					4.213035784654949,
					-2.8086905231032233
				],
				[
					12.639107353964846,
					-2.8086905231032233
				],
				[
					22.46952418482647,
					-2.8086905231032233
				],
				[
					33.7042862772397,
					-2.8086905231032233
				],
				[
					36.512976800342926,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06431799381971359,
				0.16094668209552765,
				0.1876455694437027,
				0.17414380609989166,
				0.1152208223938942,
				0.01703643798828125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 1741350808,
			"isDeleted": false,
			"id": "3RxjYnbDq8pfbKAnej-_F",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 281.5654308121769,
			"y": 1224.189316768473,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.447797877068183,
			"height": 25.278214707929692,
			"seed": 1461806744,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.8086905231032233
				],
				[
					0,
					-4.213035784654949
				],
				[
					0,
					-5.617381046206447
				],
				[
					0,
					-8.426071569309897
				],
				[
					-2.808690523103337,
					-9.830416830861395
				],
				[
					-5.61738104620656,
					-8.426071569309897
				],
				[
					-9.830416830861509,
					-2.8086905231032233
				],
				[
					-11.234762092413234,
					4.213035784654949
				],
				[
					-9.830416830861509,
					9.830416830861623
				],
				[
					-4.213035784654949,
					14.043452615516571
				],
				[
					2.808690523103337,
					15.447797877068297
				],
				[
					4.213035784654949,
					15.447797877068297
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.068292997777462,
				0.056585997343063354,
				0.11473019421100616,
				0.17014507949352264,
				0.19510656595230103,
				0.21414026618003845,
				0.21258172392845154,
				0.2084576040506363,
				0.161378413438797,
				0.08472030609846115,
				0.03045184351503849,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 2087386600,
			"isDeleted": false,
			"id": "haatpKTyVpBbSzjJSj3Tx",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 312.46102656631325,
			"y": 1218.5719357222665,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.234762092413234,
			"height": 21.065178923274743,
			"seed": 2072723864,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					1.404345261551498
				],
				[
					-2.808690523103337,
					2.8086905231032233
				],
				[
					-5.617381046206674,
					8.426071569309897
				],
				[
					-8.426071569309897,
					14.043452615516344
				],
				[
					-11.234762092413234,
					18.256488400171293
				],
				[
					-11.234762092413234,
					21.065178923274743
				],
				[
					-11.234762092413234,
					19.660833661723018
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05759408697485924,
				0.06657461822032928,
				0.07698623836040497,
				0.08617980778217316,
				0.07579272240400314,
				0.035510893911123276,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 305804440,
			"isDeleted": false,
			"id": "4VjEZQHVNw7_-5zHPOlNv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 308.2479907816583,
			"y": 1224.189316768473,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.447797877068183,
			"height": 21.065178923274743,
			"seed": 2120224744,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-2.8086905231032233
				],
				[
					4.213035784654949,
					-4.213035784654949
				],
				[
					5.61738104620656,
					-4.213035784654949
				],
				[
					7.021726307758286,
					0
				],
				[
					9.830416830861509,
					5.617381046206674
				],
				[
					11.234762092413234,
					9.830416830861623
				],
				[
					12.639107353964846,
					12.639107353964846
				],
				[
					15.447797877068183,
					16.852143138619795
				],
				[
					14.043452615516458,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07791800051927567,
				0.09653399884700775,
				0.13211798667907715,
				0.16467800736427307,
				0.18118935823440552,
				0.16956545412540436,
				0.1412116140127182,
				0.05489691346883774,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 1831010536,
			"isDeleted": false,
			"id": "uLsP4L0i35g1BJSIQJhmJ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 297.01322868924507,
			"y": 1231.2110430762314,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.08690523103303,
			"height": 2.8086905231032233,
			"seed": 109224856,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-1.4043452615517253
				],
				[
					2.808690523103337,
					-1.4043452615517253
				],
				[
					8.426071569309897,
					0
				],
				[
					16.852143138619795,
					0
				],
				[
					26.682559969481417,
					1.404345261551498
				],
				[
					28.08690523103303,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1142599806189537,
				0.13039599359035492,
				0.12548018991947174,
				0.085747130215168,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 725082520,
			"isDeleted": false,
			"id": "-WyujB2TiElEETffOuIEC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 336.33489601269133,
			"y": 1224.189316768473,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615516117,
			"height": 21.065178923274743,
			"seed": 1982338968,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					0
				],
				[
					0,
					4.213035784654949
				],
				[
					1.4043452615516117,
					9.830416830861623
				],
				[
					1.4043452615516117,
					14.043452615516571
				],
				[
					1.4043452615516117,
					18.25648840017152
				],
				[
					1.4043452615516117,
					19.660833661723245
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.21028399467468262,
				0.20449697971343994,
				0.16430826485157013,
				0.08386782556772232,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 769827816,
			"isDeleted": false,
			"id": "eHYNxUvPqkb0QRHFYJPSK",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 322.29144339717476,
			"y": 1225.5936620300247,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.29994101568798,
			"height": 1.4043452615517253,
			"seed": 772708840,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					5.617381046206674,
					-1.4043452615517253
				],
				[
					14.043452615516571,
					-1.4043452615517253
				],
				[
					28.08690523103303,
					-1.4043452615517253
				],
				[
					32.29994101568798,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08607400208711624,
				0.11728011816740036,
				0.10235067456960678,
				0.07149984687566757,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 301461144,
			"isDeleted": false,
			"id": "hEvqOB_txtpmwuby4eIss",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 451.4912074599268,
			"y": 1222.7849715069215,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615517253,
			"height": 22.46952418482647,
			"seed": 1499791256,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					0
				],
				[
					0,
					4.213035784654949
				],
				[
					0,
					8.426071569309897
				],
				[
					0,
					12.639107353964846
				],
				[
					0,
					18.256488400171293
				],
				[
					0,
					19.660833661723018
				],
				[
					-1.4043452615517253,
					21.065178923274743
				],
				[
					-1.4043452615517253,
					19.660833661723018
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06691671907901764,
				0.09735406190156937,
				0.10117840766906738,
				0.09616357088088989,
				0.0915619507431984,
				0.047973327338695526,
				0.013498595915734768,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 481683176,
			"isDeleted": false,
			"id": "A0JAaCh9gHvCaIeORV9Br",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 437.4477548444102,
			"y": 1224.189316768473,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.895595754136366,
			"height": 2.8086905231032233,
			"seed": 2128196840,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					-1.404345261551498
				],
				[
					0,
					-1.404345261551498
				],
				[
					4.213035784654949,
					-2.8086905231032233
				],
				[
					11.234762092413234,
					-2.8086905231032233
				],
				[
					18.25648840017152,
					-2.8086905231032233
				],
				[
					28.08690523103303,
					-2.8086905231032233
				],
				[
					29.491250492584754,
					-2.8086905231032233
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07812197506427765,
				0.132657989859581,
				0.16329999268054962,
				0.15606479346752167,
				0.11224682629108429,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 523131800,
			"isDeleted": false,
			"id": "F29-ntvu2x_7PdeB9gG1S",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 480.9824579525114,
			"y": 1221.3806262453697,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.808690523103337,
			"height": 25.278214707929692,
			"seed": 1994842520,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.4043452615517253
				],
				[
					-1.4043452615516117,
					7.021726307758172
				],
				[
					-1.4043452615516117,
					14.043452615516571
				],
				[
					-1.4043452615516117,
					19.660833661723018
				],
				[
					-2.808690523103337,
					23.873869446377967
				],
				[
					-2.808690523103337,
					25.278214707929692
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11743008345365524,
				0.12494397163391113,
				0.11250210553407669,
				0.08272875845432281,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 1982384616,
			"isDeleted": false,
			"id": "iOCyJd2UN8rBZl6ADI5He",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 466.93900533699497,
			"y": 1224.189316768473,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.682559969481304,
			"height": 1.404345261551498,
			"seed": 1266505112,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-1.404345261551498
				],
				[
					5.61738104620656,
					-1.404345261551498
				],
				[
					11.23476209241312,
					-1.404345261551498
				],
				[
					19.660833661723018,
					-1.404345261551498
				],
				[
					23.87386944637808,
					-1.404345261551498
				],
				[
					26.682559969481304,
					-1.404345261551498
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1143060028553009,
				0.13003945350646973,
				0.1264074146747589,
				0.07588201761245728,
				0.014870666898787022,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 1963927704,
			"isDeleted": false,
			"id": "8ttmbFzFKapc54mcOTWhV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 506.2606726604411,
			"y": 1234.0197335993346,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 26.68255996948119,
			"seed": 2000275864,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-4.213035784654949
				],
				[
					1.4043452615517253,
					-7.021726307758172
				],
				[
					0,
					-8.426071569309897
				],
				[
					-2.8086905231032233,
					-11.23476209241312
				],
				[
					-5.61738104620656,
					-11.23476209241312
				],
				[
					-9.830416830861509,
					-8.426071569309897
				],
				[
					-12.639107353964846,
					-1.4043452615517253
				],
				[
					-12.639107353964846,
					5.617381046206674
				],
				[
					-11.23476209241312,
					11.23476209241312
				],
				[
					-5.61738104620656,
					15.44779787706807
				],
				[
					2.808690523103337,
					15.44779787706807
				],
				[
					4.213035784654949,
					14.043452615516571
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.010447997599840164,
				0.08256823569536209,
				0.12129800766706467,
				0.14410074055194855,
				0.16053076088428497,
				0.17654581367969513,
				0.17234964668750763,
				0.17099514603614807,
				0.16504354774951935,
				0.14198489487171173,
				0.08998007327318192,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 88558824,
			"isDeleted": false,
			"id": "Kb5QYuz3kR4QOZcCa-WwX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 528.7301968452675,
			"y": 1226.9980072915764,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.23476209241312,
			"height": 22.46952418482647,
			"seed": 124858600,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.404345261551498,
					-1.4043452615517253
				],
				[
					-2.8086905231032233,
					0
				],
				[
					-5.617381046206447,
					5.617381046206447
				],
				[
					-8.426071569309897,
					12.639107353964846
				],
				[
					-11.23476209241312,
					18.256488400171293
				],
				[
					-11.23476209241312,
					21.065178923274743
				],
				[
					-11.23476209241312,
					21.065178923274743
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08644598722457886,
				0.13841399550437927,
				0.15396039187908173,
				0.12035516649484634,
				0.06398196518421173,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 23,
			"versionNonce": 1330533784,
			"isDeleted": false,
			"id": "BLZnnN4gZdbPG3MZSC0JU",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 523.1128157990611,
			"y": 1229.8066978146796,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.660833661723018,
			"height": 23.873869446378194,
			"seed": 1733502360,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.404345261551498,
					-4.213035784654949
				],
				[
					2.8086905231032233,
					-5.617381046206674
				],
				[
					4.213035784654949,
					-4.213035784654949
				],
				[
					7.021726307758172,
					0
				],
				[
					9.830416830861395,
					4.213035784654949
				],
				[
					12.639107353964846,
					9.830416830861623
				],
				[
					15.44779787706807,
					14.043452615516571
				],
				[
					18.256488400171293,
					16.852143138619795
				],
				[
					19.660833661723018,
					18.25648840017152
				],
				[
					19.660833661723018,
					18.25648840017152
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0009639892377890646,
				0.12541598081588745,
				0.1784299910068512,
				0.21680599451065063,
				0.21875,
				0.23019272089004517,
				0.19400595128536224,
				0.09185900539159775,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 1402826728,
			"isDeleted": false,
			"id": "MLLzUwki6c6d7wqGWsv24",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 514.6867442297512,
			"y": 1236.8284241224378,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.10863153879109,
			"height": 4.213035784654949,
			"seed": 1192235928,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.8086905231032233,
					-1.404345261551498
				],
				[
					8.426071569309897,
					-1.404345261551498
				],
				[
					19.660833661723018,
					-1.404345261551498
				],
				[
					30.89559575413614,
					-2.8086905231032233
				],
				[
					35.10863153879109,
					-4.213035784654949
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09359799325466156,
				0.05556054785847664,
				0.06477401405572891,
				0.05265878140926361,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 1394598552,
			"isDeleted": false,
			"id": "LrRcQj2JS7QFgPNx9L_hR",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 649.5038893387095,
			"y": 1221.3806262453697,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.23476209241312,
			"height": 26.68255996948119,
			"seed": 1189214952,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-2.8086905231032233
				],
				[
					0,
					2.8086905231032233
				],
				[
					-4.213035784654949,
					11.23476209241312
				],
				[
					-7.021726307758172,
					18.25648840017152
				],
				[
					-9.830416830861395,
					22.46952418482647
				],
				[
					-9.830416830861395,
					23.873869446377967
				],
				[
					-8.426071569309897,
					19.660833661723018
				],
				[
					-7.021726307758172,
					18.25648840017152
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07010918855667114,
				0.07074782997369766,
				0.11840484291315079,
				0.11244979500770569,
				0.10556433349847794,
				0.08708517253398895,
				0.0465620718896389,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 1496789736,
			"isDeleted": false,
			"id": "xxYJgKcL7HywMwvf0fdMC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 650.9082346002613,
			"y": 1219.976280983818,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.660833661723245,
			"height": 29.49125049258464,
			"seed": 907921560,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-4.213035784654949
				],
				[
					2.8086905231032233,
					-5.617381046206447
				],
				[
					5.617381046206674,
					-4.213035784654949
				],
				[
					8.426071569309897,
					1.4043452615517253
				],
				[
					11.23476209241312,
					8.426071569309897
				],
				[
					14.043452615516571,
					15.447797877068297
				],
				[
					16.852143138619795,
					19.660833661723245
				],
				[
					19.660833661723245,
					23.873869446378194
				],
				[
					18.25648840017152,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.11069488525390625,
				0.14105349779129028,
				0.1698230654001236,
				0.17740139365196228,
				0.15183593332767487,
				0.10246670246124268,
				0.05427444353699684,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 1597493144,
			"isDeleted": false,
			"id": "nuiTAUHDDUhQbF7-MQSuI",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 634.0560914616415,
			"y": 1229.8066978146796,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.29994101568809,
			"height": 2.8086905231032233,
			"seed": 757177320,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099802,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					5.617381046206674,
					-2.8086905231032233
				],
				[
					14.043452615516571,
					-2.8086905231032233
				],
				[
					29.49125049258464,
					-1.4043452615517253
				],
				[
					32.29994101568809,
					-2.8086905231032233
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.05839797854423523,
				0.09600143134593964,
				0.12802569568157196,
				0.08407706022262573,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 748721640,
			"isDeleted": false,
			"id": "IdgfaGSUhh351vQWN5FJY",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 686.0168661390526,
			"y": 1218.5719357222665,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.8086905231032233,
			"height": 26.682559969481417,
			"seed": 530606056,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.8086905231034507
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					1.404345261551498
				],
				[
					-1.404345261551498,
					9.830416830861395
				],
				[
					-1.404345261551498,
					15.44779787706807
				],
				[
					-2.8086905231032233,
					21.065178923274743
				],
				[
					-2.8086905231032233,
					23.873869446377967
				],
				[
					-2.8086905231032233,
					23.873869446377967
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11147799342870712,
				0.169311985373497,
				0.20207799971103668,
				0.18789944052696228,
				0.17588217556476593,
				0.08802734315395355,
				0.011874237097799778,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 1539972248,
			"isDeleted": false,
			"id": "zAe-rUnOuxILGuNTts4rJ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 667.7603777388811,
			"y": 1217.1675904607148,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.29994101568809,
			"height": 4.213035784655176,
			"seed": 668628712,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					2.8086905231034507,
					-2.8086905231032233
				],
				[
					7.021726307758399,
					-2.8086905231032233
				],
				[
					18.25648840017152,
					-4.213035784655176
				],
				[
					25.27821470792992,
					-4.213035784655176
				],
				[
					30.895595754136366,
					-4.213035784655176
				],
				[
					32.29994101568809,
					-4.213035784655176
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.1567240059375763,
				0.17447997629642487,
				0.1653420776128769,
				0.13252386450767517,
				0.04721572995185852,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 853907688,
			"isDeleted": false,
			"id": "2OdyrMIJaNJ1iVGg8jGCj",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 709.8907355854308,
			"y": 1211.5502094145081,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.617381046206674,
			"height": 25.278214707929692,
			"seed": 11288472,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					-1.404345261551498
				],
				[
					-1.4043452615517253,
					1.404345261551498
				],
				[
					-1.4043452615517253,
					7.021726307758399
				],
				[
					-1.4043452615517253,
					12.639107353964846
				],
				[
					-2.8086905231034507,
					18.25648840017152
				],
				[
					-4.213035784654949,
					22.46952418482647
				],
				[
					-4.213035784654949,
					23.873869446378194
				],
				[
					-5.617381046206674,
					23.873869446378194
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08688399940729141,
				0.2045796811580658,
				0.22480715811252594,
				0.21301493048667908,
				0.1485547125339508,
				0.025854216888546944,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 176867736,
			"isDeleted": false,
			"id": "jjgJMoAyoVxc36tTR0g-M",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 691.6342471852593,
			"y": 1211.5502094145081,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 36.51297680034304,
			"height": 5.617381046206447,
			"seed": 504987800,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					-2.8086905231034507
				],
				[
					2.8086905231032233,
					-4.213035784654949
				],
				[
					8.426071569309897,
					-4.213035784654949
				],
				[
					15.44779787706807,
					-4.213035784654949
				],
				[
					25.278214707929692,
					-4.213035784654949
				],
				[
					33.70428627723959,
					-4.213035784654949
				],
				[
					36.51297680034304,
					-5.617381046206447
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0668879970908165,
				0.10989074409008026,
				0.1517999917268753,
				0.16511675715446472,
				0.09330251812934875,
				0.011610839515924454,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 1334983656,
			"isDeleted": false,
			"id": "7O9-ShdpsYi4ZBQatIm6U",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 739.3819860780154,
			"y": 1218.5719357222665,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.49125049258464,
			"height": 29.491250492584868,
			"seed": 169746840,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.8086905231034507
				],
				[
					0,
					-5.617381046206901
				],
				[
					-1.4043452615517253,
					-7.021726307758399
				],
				[
					-2.8086905231032233,
					-8.426071569309897
				],
				[
					-5.617381046206674,
					-9.83041683086185
				],
				[
					-11.23476209241312,
					-7.021726307758399
				],
				[
					-16.852143138619795,
					1.404345261551498
				],
				[
					-18.25648840017152,
					9.830416830861395
				],
				[
					-14.043452615516571,
					16.852143138619795
				],
				[
					-1.4043452615517253,
					19.660833661723018
				],
				[
					8.426071569309897,
					18.256488400171293
				],
				[
					11.23476209241312,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.06762228161096573,
				0.14503677189350128,
				0.18571999669075012,
				0.21030563116073608,
				0.2329864501953125,
				0.24826830625534058,
				0.2736717760562897,
				0.27664557099342346,
				0.2587175667285919,
				0.1391342431306839,
				0
			]
		},
		{
			"type": "ellipse",
			"version": 49,
			"versionNonce": 1454233240,
			"isDeleted": false,
			"id": "9qW32f9agrwViyTkWH8Sq",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 21.76155742512134,
			"y": 1027.5809801512419,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 162.9040503399916,
			"height": 80.04767990844402,
			"seed": 1748524184,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 54,
			"versionNonce": 347242216,
			"isDeleted": false,
			"id": "fbq2BJPPTgqsl5y6iAn0c",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 240.839418227179,
			"y": 1036.0070517205518,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 141.83887141671676,
			"height": 94.0911325239606,
			"seed": 1959481832,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 47,
			"versionNonce": 619135896,
			"isDeleted": false,
			"id": "6t_krxsFifMp9MhS_Eoy8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 427.6173380135487,
			"y": 1016.3462180588285,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 141.8388714167168,
			"height": 101.112858831719,
			"seed": 24613272,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 52,
			"versionNonce": 1926390248,
			"isDeleted": false,
			"id": "cypHky5kfsOE4gJDSpLkS",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 650.9082346002613,
			"y": 1016.3462180588285,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 127.79541880120041,
			"height": 140.43452615516526,
			"seed": 1565262744,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 74,
			"versionNonce": 594219160,
			"isDeleted": false,
			"id": "ue_58ovrqPAlq5ARIS0MF",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 631.2474009385382,
			"y": 1197.5067567989918,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 134.81714510895858,
			"height": 68.81291781603068,
			"seed": 1242269928,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 61,
			"versionNonce": 1761469672,
			"isDeleted": false,
			"id": "EvDl01rT5bxW-ZqJMAj2m",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 429.0216832751003,
			"y": 1214.3588999376116,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 127.79541880120036,
			"height": 37.91732206189454,
			"seed": 804747672,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 69,
			"versionNonce": 434978200,
			"isDeleted": false,
			"id": "6Z5AWdAk3mC4Wt03aVqXU",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 222.5829298270075,
			"y": 1193.2937210143368,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 144.6475619398202,
			"height": 66.00422729292745,
			"seed": 1284680600,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 885065704,
			"isDeleted": false,
			"id": "vDK-3CvOkxas9bwy5lJcQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 184.66560776511295,
			"y": 1075.3287190439978,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44.939048369652824,
			"height": 1.4043452615517253,
			"seed": 705417624,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					1.4043452615517253
				],
				[
					4.213035784654949,
					1.4043452615517253
				],
				[
					8.426071569309897,
					1.4043452615517253
				],
				[
					14.043452615516458,
					1.4043452615517253
				],
				[
					21.065178923274743,
					1.4043452615517253
				],
				[
					28.08690523103303,
					1.4043452615517253
				],
				[
					35.108631538791315,
					1.4043452615517253
				],
				[
					39.32166732344626,
					1.4043452615517253
				],
				[
					43.53470310810121,
					1.4043452615517253
				],
				[
					44.939048369652824,
					1.4043452615517253
				],
				[
					44.939048369652824,
					1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04177316278219223,
				0.08094292879104614,
				0.09051354974508286,
				0.09980181604623795,
				0.1042226254940033,
				0.09251214563846588,
				0.0793381929397583,
				0.06491363793611526,
				0.054755400866270065,
				0.04552352800965309,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 966904472,
			"isDeleted": false,
			"id": "2MNofT_SV8wLDeN9riqZK",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 222.5829298270075,
			"y": 1066.902647474688,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 22.46952418482647,
			"seed": 934782440,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					0
				],
				[
					8.426071569309897,
					2.8086905231034507
				],
				[
					12.63910735396496,
					5.617381046206674
				],
				[
					14.043452615516571,
					8.426071569309897
				],
				[
					15.447797877068183,
					9.830416830861623
				],
				[
					15.447797877068183,
					11.234762092413348
				],
				[
					12.63910735396496,
					14.043452615516571
				],
				[
					8.426071569309897,
					15.447797877068297
				],
				[
					4.213035784654949,
					18.25648840017152
				],
				[
					0,
					21.065178923274743
				],
				[
					-1.4043452615516117,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.10924838483333588,
				0.12449847161769867,
				0.11791214346885681,
				0.10822588950395584,
				0.10294311493635178,
				0.10781433433294296,
				0.11249686032533646,
				0.11425729095935822,
				0.10359328985214233,
				0.08597235381603241,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 23,
			"versionNonce": 36162280,
			"isDeleted": false,
			"id": "Lt_HKbK2BaTTJ5S89Dixd",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 389.70001595165405,
			"y": 1072.5200285208946,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 37.91732206189454,
			"height": 2.8086905231032233,
			"seed": 353352344,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.4043452615517253
				],
				[
					-1.4043452615516117,
					1.4043452615517253
				],
				[
					-1.4043452615516117,
					2.8086905231032233
				],
				[
					0,
					2.8086905231032233
				],
				[
					1.4043452615517253,
					2.8086905231032233
				],
				[
					7.021726307758286,
					2.8086905231032233
				],
				[
					14.043452615516571,
					2.8086905231032233
				],
				[
					22.46952418482647,
					1.4043452615517253
				],
				[
					28.08690523103303,
					1.4043452615517253
				],
				[
					33.7042862772397,
					1.4043452615517253
				],
				[
					36.512976800342926,
					1.4043452615517253
				],
				[
					36.512976800342926,
					1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.046181824058294296,
				0.06400415301322937,
				0.07883267104625702,
				0.09564495831727982,
				0.10400106757879257,
				0.11481771618127823,
				0.11258658021688461,
				0.11622335761785507,
				0.11561654508113861,
				0.09117507934570312,
				0.04918627813458443,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 1832695704,
			"isDeleted": false,
			"id": "rsk9iKdxX-U6o245snBdz",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 416.38257592113547,
			"y": 1064.0939569515847,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.043452615516571,
			"height": 19.660833661723018,
			"seed": 950015384,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					0
				],
				[
					4.213035784654949,
					1.4043452615517253
				],
				[
					7.021726307758286,
					4.213035784654949
				],
				[
					9.830416830861509,
					7.021726307758172
				],
				[
					11.234762092413234,
					11.23476209241312
				],
				[
					9.830416830861509,
					14.043452615516571
				],
				[
					4.213035784654949,
					16.852143138619795
				],
				[
					0,
					19.660833661723018
				],
				[
					-2.808690523103337,
					19.660833661723018
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05313592404127121,
				0.08691000193357468,
				0.10095465183258057,
				0.11355642974376678,
				0.1098652333021164,
				0.11255313456058502,
				0.11203695833683014,
				0.053982481360435486,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 465448424,
			"isDeleted": false,
			"id": "LwXkrvqPVMy0aTp9pMwda",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 566.6475189071623,
			"y": 1072.5200285208946,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 78.64333464689253,
			"height": 2.8086905231032233,
			"seed": 1609875176,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					-1.4043452615517253,
					-1.4043452615517253
				],
				[
					-1.4043452615517253,
					-2.8086905231032233
				],
				[
					1.404345261551498,
					-2.8086905231032233
				],
				[
					7.021726307758172,
					-2.8086905231032233
				],
				[
					14.043452615516344,
					-2.8086905231032233
				],
				[
					26.68255996948119,
					-2.8086905231032233
				],
				[
					37.91732206189454,
					-2.8086905231032233
				],
				[
					47.74773889275616,
					-2.8086905231032233
				],
				[
					56.17381046206606,
					-1.4043452615517253
				],
				[
					63.19553676982423,
					-1.4043452615517253
				],
				[
					67.40857255447918,
					-1.4043452615517253
				],
				[
					70.2172630775824,
					-1.4043452615517253
				],
				[
					74.43029886223735,
					-1.4043452615517253
				],
				[
					75.83464412378908,
					-1.4043452615517253
				],
				[
					77.2389893853408,
					-1.4043452615517253
				],
				[
					77.2389893853408,
					-2.8086905231032233
				],
				[
					77.2389893853408,
					-2.8086905231032233
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04013186693191528,
				0.06711553782224655,
				0.08961184322834015,
				0.09097323566675186,
				0.08646298199892044,
				0.08394800126552582,
				0.08079202473163605,
				0.08133050799369812,
				0.08211883902549744,
				0.08505474776029587,
				0.09369515627622604,
				0.1078927293419838,
				0.13090817630290985,
				0.13559341430664062,
				0.13869409263134003,
				0.14593829214572906,
				0.11361245810985565,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 686949528,
			"isDeleted": false,
			"id": "f57zfmTXSutOPTjE_lqr1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 635.4604367231932,
			"y": 1062.689611690033,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.256488400171293,
			"height": 18.25648840017152,
			"seed": 1141816552,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.404345261551498,
					0
				],
				[
					2.8086905231032233,
					0
				],
				[
					5.617381046206447,
					0
				],
				[
					9.830416830861395,
					2.8086905231034507
				],
				[
					12.639107353964846,
					5.617381046206674
				],
				[
					14.043452615516344,
					8.426071569309897
				],
				[
					12.639107353964846,
					9.830416830861623
				],
				[
					8.426071569309897,
					12.639107353964846
				],
				[
					1.404345261551498,
					15.447797877068297
				],
				[
					-2.8086905231034507,
					18.25648840017152
				],
				[
					-4.213035784654949,
					18.25648840017152
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0779079869389534,
				0.09035992622375488,
				0.10866662859916687,
				0.12291238456964493,
				0.12498785555362701,
				0.14637774229049683,
				0.16585677862167358,
				0.18109264969825745,
				0.1665414422750473,
				0.08270910382270813,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 46,
			"versionNonce": 445657320,
			"isDeleted": false,
			"id": "OPLlrKJGp8tGGbPBpjJv6",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 363.01745598217275,
			"y": 1212.9545546760596,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 286.4864333565368,
			"height": 106.73023987792544,
			"seed": 1302516632,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.8086905231032233,
					-1.404345261551498
				],
				[
					5.61738104620656,
					-2.808690523102996
				],
				[
					11.23476209241312,
					-4.213035784654949
				],
				[
					18.256488400171406,
					-8.426071569309897
				],
				[
					26.682559969481304,
					-11.234762092412893
				],
				[
					40.726012584997875,
					-18.256488400171293
				],
				[
					53.36511993896272,
					-23.873869446377967
				],
				[
					68.8129178160309,
					-29.49125049258464
				],
				[
					85.6650609546507,
					-36.51297680034281
				],
				[
					99.70851357016727,
					-40.72601258499776
				],
				[
					112.34762092413212,
					-44.93904836965271
				],
				[
					123.58238301654524,
					-50.556429415859384
				],
				[
					132.00845458585525,
					-54.76946520051433
				],
				[
					144.6475619398201,
					-58.98250098516928
				],
				[
					158.6910145553366,
					-66.00422729292745
				],
				[
					168.52143138619823,
					-70.2172630775824
				],
				[
					178.35184821705963,
					-73.02595360068563
				],
				[
					189.58661030947297,
					-77.23898938534057
				],
				[
					199.41702714033437,
					-80.04767990844402
				],
				[
					206.43875344809277,
					-82.85637043154725
				],
				[
					217.6735155405059,
					-85.66506095465047
				],
				[
					223.29089658671256,
					-87.0694062162022
				],
				[
					235.9300039406774,
					-91.28244200085715
				],
				[
					242.95173024843558,
					-94.09113252396037
				],
				[
					249.97345655619398,
					-95.4954777855121
				],
				[
					256.99518286395215,
					-98.30416830861532
				],
				[
					264.01690917171055,
					-99.70851357016704
				],
				[
					269.634290217917,
					-101.11285883171877
				],
				[
					273.84732600257195,
					-102.51720409327027
				],
				[
					278.0603617872269,
					-103.92154935482199
				],
				[
					280.86905231033035,
					-105.32589461637372
				],
				[
					283.67774283343357,
					-105.32589461637372
				],
				[
					286.4864333565368,
					-105.32589461637372
				],
				[
					286.4864333565368,
					-106.73023987792544
				],
				[
					286.4864333565368,
					-106.73023987792544
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0,
				0.051843781024217606,
				0.04845712333917618,
				0.05559255927801132,
				0.06477700918912888,
				0.07322018593549728,
				0.07961578667163849,
				0.08661147952079773,
				0.09157684445381165,
				0.0878949910402298,
				0.07992345839738846,
				0.08195019513368607,
				0.08086968958377838,
				0.09216415137052536,
				0.09726519882678986,
				0.09867110848426819,
				0.09451577812433243,
				0.09197207540273666,
				0.09636538475751877,
				0.09915408492088318,
				0.09515344351530075,
				0.09569177031517029,
				0.09243350476026535,
				0.09017431735992432,
				0.09263281524181366,
				0.09305871278047562,
				0.0972915068268776,
				0.09834396094083786,
				0.1041160598397255,
				0.1053515300154686,
				0.10708120465278625,
				0.10884158313274384,
				0.07682092487812042,
				0.03727008029818535,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 980791704,
			"isDeleted": false,
			"id": "zyvBSy6KjGGaCpTcfQWOE",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 622.8213293692284,
			"y": 1103.415624275031,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.873869446377967,
			"height": 21.065178923274743,
			"seed": 2026481640,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.404345261551498,
					0
				],
				[
					4.213035784654949,
					0
				],
				[
					8.426071569309897,
					0
				],
				[
					12.639107353964846,
					1.4043452615517253
				],
				[
					16.852143138619795,
					1.4043452615517253
				],
				[
					21.065178923274743,
					1.4043452615517253
				],
				[
					22.46952418482624,
					1.4043452615517253
				],
				[
					23.873869446377967,
					1.4043452615517253
				],
				[
					23.873869446377967,
					2.8086905231032233
				],
				[
					23.873869446377967,
					4.213035784654949
				],
				[
					21.065178923274743,
					7.021726307758399
				],
				[
					18.256488400171293,
					11.234762092413348
				],
				[
					15.44779787706807,
					15.447797877068297
				],
				[
					12.639107353964846,
					19.660833661723245
				],
				[
					12.639107353964846,
					21.065178923274743
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0692112147808075,
				0.08029104769229889,
				0.0833936482667923,
				0.07959719747304916,
				0.07928366214036942,
				0.07712732255458832,
				0.07594168186187744,
				0.08172796666622162,
				0.09209005534648895,
				0.12427765130996704,
				0.14245593547821045,
				0.15711258351802826,
				0.1556723266839981,
				0.11619812250137329,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 371839976,
			"isDeleted": false,
			"id": "qZ-7MH8pblXaaca2yyqO4",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 705.6776998007758,
			"y": 1153.9720536908903,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.8086905231034507,
			"height": 37.91732206189454,
			"seed": 2024608408,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.4043452615517253
				],
				[
					-1.4043452615517253,
					2.8086905231034507
				],
				[
					-1.4043452615517253,
					8.426071569309897
				],
				[
					-1.4043452615517253,
					16.852143138619795
				],
				[
					-1.4043452615517253,
					25.278214707929692
				],
				[
					-2.8086905231034507,
					33.70428627723959
				],
				[
					-2.8086905231034507,
					36.51297680034304
				],
				[
					-2.8086905231034507,
					37.91732206189454
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11924673616886139,
				0.13077053427696228,
				0.13781461119651794,
				0.1351722776889801,
				0.11204028129577637,
				0.07679004222154617,
				0.028926361352205276,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 24,
			"versionNonce": 419151512,
			"isDeleted": false,
			"id": "kiD1M87nEDhuXSy3RRKIw",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 691.6342471852593,
			"y": 1186.2719947065784,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.895595754136366,
			"height": 15.44779787706807,
			"seed": 1010201496,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					2.8086905231032233,
					-1.4043452615517253
				],
				[
					2.8086905231032233,
					1.404345261551498
				],
				[
					4.213035784654949,
					2.8086905231032233
				],
				[
					5.617381046206674,
					5.617381046206447
				],
				[
					7.021726307758172,
					8.426071569309897
				],
				[
					11.23476209241312,
					9.830416830861395
				],
				[
					15.44779787706807,
					8.426071569309897
				],
				[
					21.065178923274743,
					4.213035784654949
				],
				[
					26.682559969481417,
					0
				],
				[
					29.49125049258464,
					-2.8086905231034507
				],
				[
					30.895595754136366,
					-4.213035784654949
				],
				[
					30.895595754136366,
					-5.617381046206674
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0933912992477417,
				0.09270492196083069,
				0.09421224892139435,
				0.08440753072500229,
				0.07388470321893692,
				0.09438089281320572,
				0.11071468889713287,
				0.1354190707206726,
				0.13956326246261597,
				0.11435427516698837,
				0.045444000512361526,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1419187944,
			"isDeleted": false,
			"id": "_Di3CBFa_vPkr3D9ovpK0",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 371.44352755148265,
			"y": 1231.2110430762314,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 61.79119150827273,
			"height": 2.8086905231032233,
			"seed": 1769793256,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					0
				],
				[
					1.4043452615516117,
					0
				],
				[
					5.61738104620656,
					0
				],
				[
					12.639107353964846,
					0
				],
				[
					22.469524184826355,
					0
				],
				[
					33.70428627723959,
					0
				],
				[
					44.939048369652824,
					1.404345261551498
				],
				[
					53.36511993896272,
					1.404345261551498
				],
				[
					60.38684624672101,
					2.8086905231032233
				],
				[
					60.38684624672101,
					2.8086905231032233
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.06837332248687744,
				0.0707339495420456,
				0.08066824078559875,
				0.08908453583717346,
				0.09073998779058456,
				0.08817803859710693,
				0.08228329569101334,
				0.023148132488131523,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 892873624,
			"isDeleted": false,
			"id": "mSrPC_FV2VgojlByqS0CI",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 385.4869801669991,
			"y": 1219.976280983818,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 26.682559969481417,
			"seed": 2121046248,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					-1.404345261551498
				],
				[
					2.808690523103337,
					-2.8086905231032233
				],
				[
					0,
					-1.404345261551498
				],
				[
					-2.808690523103337,
					1.4043452615517253
				],
				[
					-7.021726307758286,
					4.213035784654949
				],
				[
					-11.234762092413234,
					7.021726307758399
				],
				[
					-14.043452615516458,
					9.830416830861623
				],
				[
					-14.043452615516458,
					12.639107353964846
				],
				[
					-9.830416830861509,
					16.852143138619795
				],
				[
					-2.808690523103337,
					22.46952418482647
				],
				[
					-1.4043452615516117,
					23.873869446378194
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.06399557739496231,
				0.08828439563512802,
				0.08083602786064148,
				0.07366754114627838,
				0.08053512871265411,
				0.10059002786874771,
				0.12116485834121704,
				0.12445221096277237,
				0.1186165139079094,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 24,
			"versionNonce": 2053372392,
			"isDeleted": false,
			"id": "Czd_Oijpk8woKb9o2AKlQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 558.2214473378522,
			"y": 1232.6153883377829,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 78.64333464689253,
			"height": 0,
			"seed": 518371224,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					0
				],
				[
					7.021726307758399,
					0
				],
				[
					15.447797877068297,
					0
				],
				[
					26.682559969481417,
					0
				],
				[
					39.32166732344626,
					0
				],
				[
					50.55642941585961,
					0
				],
				[
					60.386846246721234,
					0
				],
				[
					66.00422729292768,
					0
				],
				[
					70.21726307758263,
					0
				],
				[
					74.43029886223758,
					0
				],
				[
					77.23898938534103,
					0
				],
				[
					78.64333464689253,
					0
				],
				[
					77.23898938534103,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06241030991077423,
				0.07734481990337372,
				0.08922607451677322,
				0.09500030428171158,
				0.10298938304185867,
				0.12139648199081421,
				0.13144195079803467,
				0.13750573992729187,
				0.13853076100349426,
				0.1420702189207077,
				0.14185941219329834,
				0.14080190658569336,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 1230960792,
			"isDeleted": false,
			"id": "WC8sNyMEsUf7y00FJyspG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 575.0735904764722,
			"y": 1221.3806262453697,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.086905231033143,
			"height": 32.299941015687864,
			"seed": 38232808,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					0
				],
				[
					-2.8086905231034507,
					1.4043452615517253
				],
				[
					-4.213035784654949,
					2.8086905231032233
				],
				[
					-8.426071569309897,
					4.213035784654949
				],
				[
					-12.639107353965073,
					5.617381046206674
				],
				[
					-16.852143138620022,
					8.426071569309897
				],
				[
					-18.25648840017152,
					9.830416830861623
				],
				[
					-19.660833661723245,
					11.23476209241312
				],
				[
					-18.25648840017152,
					14.043452615516571
				],
				[
					-14.043452615516571,
					16.852143138619795
				],
				[
					-8.426071569309897,
					21.065178923274743
				],
				[
					0,
					26.682559969481417
				],
				[
					5.617381046206447,
					30.895595754136366
				],
				[
					8.426071569309897,
					32.299941015687864
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.02891879342496395,
				0.04393835365772247,
				0.04342275857925415,
				0.04830050840973854,
				0.05459814518690109,
				0.06086917221546173,
				0.06827188283205032,
				0.07811667025089264,
				0.10183309763669968,
				0.12229431420564651,
				0.14238345623016357,
				0.13034744560718536,
				0.10733630508184433,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 983334120,
			"isDeleted": false,
			"id": "6vpn6opdY9B1HQGYTU790",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 162.19608358028648,
			"y": 993.8766938740021,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.66083366172313,
			"height": 12.639107353964846,
			"seed": 2130734312,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					-2.8086905231032233
				],
				[
					2.808690523103337,
					-4.213035784654949
				],
				[
					5.617381046206674,
					-5.61738104620656
				],
				[
					9.830416830861623,
					-8.426071569309897
				],
				[
					16.852143138619795,
					-11.23476209241312
				],
				[
					19.66083366172313,
					-12.639107353964846
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.03696850687265396,
				0.0464601144194603,
				0.058014802634716034,
				0.06668078899383545,
				0.0601811520755291,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 690234776,
			"isDeleted": false,
			"id": "fRbDuz5FcejinBWaZRGFA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 228.20031087321416,
			"y": 955.9593718121075,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.08690523103303,
			"height": 11.234762092413234,
			"seed": 1359194520,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					0
				],
				[
					2.8086905231032233,
					-1.4043452615517253
				],
				[
					5.61738104620656,
					-1.4043452615517253
				],
				[
					9.830416830861509,
					-4.213035784654949
				],
				[
					18.256488400171406,
					-7.021726307758172
				],
				[
					25.278214707929692,
					-9.830416830861623
				],
				[
					28.08690523103303,
					-11.234762092413234
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0704449787735939,
				0.08392331004142761,
				0.10529553145170212,
				0.1025892049074173,
				0.08680496364831924,
				0.03854943811893463,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 114073576,
			"isDeleted": false,
			"id": "wR-1LAf-uwQc2EMfpM7IJ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 315.2697170894166,
			"y": 933.489847627281,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.1086315387912,
			"height": 5.61738104620656,
			"seed": 456533992,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					-1.4043452615516117
				],
				[
					2.8086905231032233,
					-1.4043452615516117
				],
				[
					4.213035784654949,
					-2.8086905231032233
				],
				[
					8.426071569309897,
					-2.8086905231032233
				],
				[
					16.852143138619795,
					-4.213035784654949
				],
				[
					30.895595754136252,
					-4.213035784654949
				],
				[
					35.1086315387912,
					-5.61738104620656
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.045915283262729645,
				0.060824308544397354,
				0.08966543525457382,
				0.09740118682384491,
				0.04712210223078728,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 297513624,
			"isDeleted": false,
			"id": "v3A__zmp2wgETGHFzeSoX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 399.5304327825157,
			"y": 927.8724665810745,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 49.15208415430777,
			"height": 4.213035784654949,
			"seed": 175677080,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615516117,
					0
				],
				[
					5.61738104620656,
					-1.4043452615516117
				],
				[
					12.639107353964846,
					-1.4043452615516117
				],
				[
					25.278214707929692,
					-2.808690523103337
				],
				[
					43.53470310810121,
					-2.808690523103337
				],
				[
					49.15208415430777,
					-4.213035784654949
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09510418772697449,
				0.12232311815023422,
				0.12400146573781967,
				0.06916823983192444,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1056989928,
			"isDeleted": false,
			"id": "h8-lOQvfklDQDNJ7dbhzh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 502.04763687578617,
			"y": 933.489847627281,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 36.51297680034298,
			"height": 1.4043452615516117,
			"seed": 1841861272,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					-1.4043452615516117
				],
				[
					5.617381046206674,
					-1.4043452615516117
				],
				[
					11.234762092413291,
					-1.4043452615516117
				],
				[
					33.70428627723976,
					-1.4043452615516117
				],
				[
					36.51297680034298,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09090658277273178,
				0.08464431762695312,
				0.05694592371582985,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 2044305304,
			"isDeleted": false,
			"id": "wNCET0ApelyESMMXGyKEe",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 597.5431146612984,
			"y": 955.9593718121075,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.70428627723982,
			"height": 22.46952418482647,
			"seed": 2104396776,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.8086905231034507,
					0
				],
				[
					7.021726307758399,
					1.4043452615517253
				],
				[
					14.043452615516571,
					5.617381046206674
				],
				[
					21.06517892327497,
					11.234762092413234
				],
				[
					30.895595754136366,
					19.66083366172313
				],
				[
					33.70428627723982,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11998999118804932,
				0.13100197911262512,
				0.12832604348659515,
				0.09276123344898224,
				0.046155668795108795,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1640220136,
			"isDeleted": false,
			"id": "kU-14oDTPlyz0m5HtWoxB",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 663.5473419542261,
			"y": 999.4940749202087,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.447797877068297,
			"height": 16.852143138619795,
			"seed": 703944680,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					1.4043452615517253
				],
				[
					5.617381046206674,
					5.617381046206674
				],
				[
					14.043452615516571,
					14.043452615516571
				],
				[
					15.447797877068297,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.05040387064218521,
				0.025464721024036407,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 1639050392,
			"isDeleted": false,
			"id": "YA0C02PuNmNwt7seu_uZ8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 163.60042884183815,
			"y": 979.8332412584856,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.682559969481417,
			"height": 19.66083366172313,
			"seed": 442925288,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					-2.808690523103337
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					4.213035784654949
				],
				[
					-1.4043452615516117,
					8.426071569309897
				],
				[
					-2.808690523103337,
					12.639107353964846
				],
				[
					-1.4043452615516117,
					15.447797877068183
				],
				[
					2.808690523103337,
					16.852143138619795
				],
				[
					9.830416830861509,
					16.852143138619795
				],
				[
					22.46952418482647,
					16.852143138619795
				],
				[
					23.87386944637808,
					16.852143138619795
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.13851384818553925,
				0.13210400938987732,
				0.12223797291517258,
				0.10187719762325287,
				0.08982086181640625,
				0.0898955687880516,
				0.09259539842605591,
				0.11748544126749039,
				0.1543300449848175,
				0.11506421118974686,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 1008912616,
			"isDeleted": false,
			"id": "HN_mde43U0Z5orKdOCAwB",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 848.2187438482681,
			"y": 1028.9853254127938,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.404345261551498,
			"height": 15.447797877068297,
			"seed": 282334696,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					2.8086905231034507
				],
				[
					0,
					5.617381046206674
				],
				[
					0,
					9.830416830861623
				],
				[
					0,
					12.639107353964846
				],
				[
					0,
					14.043452615516571
				],
				[
					-1.404345261551498,
					15.447797877068297
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.10723263770341873,
				0.10740933567285538,
				0.08415234088897705,
				0.03948074206709862,
				0.005026580765843391,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 586717592,
			"isDeleted": false,
			"id": "-ADo8WmyRoAqOMv3W8BW4",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 848.2187438482681,
			"y": 1021.9635991050357,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.4043452615517253,
			"height": 4.213035784654949,
			"seed": 1631969768,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					0,
					-4.213035784654949
				],
				[
					1.4043452615517253,
					-4.213035784654949
				],
				[
					1.4043452615517253,
					-2.808690523103337
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08451300114393234,
				0.10085000842809677,
				0.03394635021686554,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 430533608,
			"isDeleted": false,
			"id": "zT9EnMIpR6AXGuBCTaSVJ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 858.0491606791297,
			"y": 1041.6244327667587,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.639107353964846,
			"height": 12.639107353964846,
			"seed": 1953607144,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099803,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					0,
					-4.213035784654949
				],
				[
					0,
					-5.617381046206447
				],
				[
					1.4043452615517253,
					-8.426071569309897
				],
				[
					4.213035784654949,
					-9.830416830861395
				],
				[
					7.021726307758399,
					-11.23476209241312
				],
				[
					9.830416830861623,
					-11.23476209241312
				],
				[
					11.234762092413348,
					-11.23476209241312
				],
				[
					11.234762092413348,
					-8.426071569309897
				],
				[
					11.234762092413348,
					-4.213035784654949
				],
				[
					11.234762092413348,
					-1.404345261551498
				],
				[
					12.639107353964846,
					0
				],
				[
					12.639107353964846,
					1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.04515258967876434,
				0.06240857020020485,
				0.08307302743196487,
				0.10604080557823181,
				0.1306339055299759,
				0.14822670817375183,
				0.13655751943588257,
				0.1290920078754425,
				0.10104776173830032,
				0.047558411955833435,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 40,
			"versionNonce": 1088530072,
			"isDeleted": false,
			"id": "gMHZZeci1hnQh_7ZFog-1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 890.3491016948178,
			"y": 1034.6027064590005,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.70428627723959,
			"height": 18.25648840017152,
			"seed": 1781407640,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					0
				],
				[
					-2.8086905231034507,
					-1.4043452615517253
				],
				[
					-4.213035784654949,
					-1.4043452615517253
				],
				[
					-5.617381046206674,
					-2.8086905231032233
				],
				[
					-8.426071569309897,
					-2.8086905231032233
				],
				[
					-11.234762092413348,
					-1.4043452615517253
				],
				[
					-12.639107353964846,
					1.4043452615517253
				],
				[
					-12.639107353964846,
					4.213035784654949
				],
				[
					-12.639107353964846,
					7.021726307758172
				],
				[
					-9.830416830861623,
					8.426071569309897
				],
				[
					-5.617381046206674,
					8.426071569309897
				],
				[
					-2.8086905231034507,
					5.617381046206674
				],
				[
					0,
					1.4043452615517253
				],
				[
					1.404345261551498,
					-1.4043452615517253
				],
				[
					2.8086905231032233,
					-5.617381046206674
				],
				[
					2.8086905231032233,
					-8.426071569309897
				],
				[
					2.8086905231032233,
					-7.021726307758172
				],
				[
					1.404345261551498,
					-2.8086905231032233
				],
				[
					1.404345261551498,
					1.4043452615517253
				],
				[
					1.404345261551498,
					4.213035784654949
				],
				[
					4.213035784654949,
					7.021726307758172
				],
				[
					7.021726307758172,
					8.426071569309897
				],
				[
					9.830416830861395,
					7.021726307758172
				],
				[
					12.639107353964846,
					4.213035784654949
				],
				[
					14.043452615516571,
					1.4043452615517253
				],
				[
					15.44779787706807,
					-1.4043452615517253
				],
				[
					15.44779787706807,
					-2.8086905231032233
				],
				[
					14.043452615516571,
					-2.8086905231032233
				],
				[
					14.043452615516571,
					-1.4043452615517253
				],
				[
					14.043452615516571,
					1.4043452615517253
				],
				[
					14.043452615516571,
					4.213035784654949
				],
				[
					16.852143138619795,
					8.426071569309897
				],
				[
					19.660833661723018,
					8.426071569309897
				],
				[
					21.065178923274743,
					9.830416830861623
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06934598088264465,
				0.09188000857830048,
				0.12479199469089508,
				0.1556359827518463,
				0.16366635262966156,
				0.16555114090442657,
				0.16514135897159576,
				0.16413186490535736,
				0.12485489249229431,
				0.08804012835025787,
				0.051501404494047165,
				0.02562548778951168,
				0.02453955076634884,
				0.05216683819890022,
				0.09456615895032883,
				0.132123202085495,
				0.1586940884590149,
				0.15166153013706207,
				0.14142337441444397,
				0.1286226511001587,
				0.11951165646314621,
				0.09592382609844208,
				0.08849801868200302,
				0.08464901894330978,
				0.08432101458311081,
				0.10754214227199554,
				0.11316223442554474,
				0.13290323317050934,
				0.13755212724208832,
				0.1437990665435791,
				0.1476796567440033,
				0.127369225025177,
				0.08224008232355118,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 58,
			"versionNonce": 1952689896,
			"isDeleted": false,
			"id": "x1L0UrXB3JbecG4JtTDu2",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 922.6490427105057,
			"y": 1036.0070517205522,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 49.15208415430766,
			"height": 30.895595754136252,
			"seed": 1241180568,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-2.8086905231034507
				],
				[
					1.4043452615517253,
					-4.213035784654949
				],
				[
					0,
					-4.213035784654949
				],
				[
					-1.404345261551498,
					-4.213035784654949
				],
				[
					-2.8086905231032233,
					-2.8086905231034507
				],
				[
					-4.213035784654949,
					-1.4043452615517253
				],
				[
					-4.213035784654949,
					1.404345261551498
				],
				[
					-5.617381046206447,
					2.8086905231032233
				],
				[
					-4.213035784654949,
					5.617381046206447
				],
				[
					-1.404345261551498,
					5.617381046206447
				],
				[
					0,
					5.617381046206447
				],
				[
					2.8086905231034507,
					2.8086905231032233
				],
				[
					4.213035784654949,
					0
				],
				[
					4.213035784654949,
					-2.8086905231034507
				],
				[
					5.617381046206674,
					-2.8086905231034507
				],
				[
					5.617381046206674,
					-1.4043452615517253
				],
				[
					5.617381046206674,
					0
				],
				[
					5.617381046206674,
					5.617381046206447
				],
				[
					4.213035784654949,
					11.23476209241312
				],
				[
					1.4043452615517253,
					15.44779787706807
				],
				[
					0,
					18.256488400171293
				],
				[
					-1.404345261551498,
					18.256488400171293
				],
				[
					-1.404345261551498,
					15.44779787706807
				],
				[
					-1.404345261551498,
					14.043452615516344
				],
				[
					0,
					8.426071569309897
				],
				[
					1.4043452615517253,
					5.617381046206447
				],
				[
					4.213035784654949,
					0
				],
				[
					8.426071569309897,
					-5.617381046206674
				],
				[
					11.234762092413348,
					-9.830416830861623
				],
				[
					12.639107353964846,
					-12.63910735396496
				],
				[
					11.234762092413348,
					-12.63910735396496
				],
				[
					12.639107353964846,
					-11.234762092413348
				],
				[
					15.447797877068297,
					-9.830416830861623
				],
				[
					16.852143138619795,
					-7.021726307758399
				],
				[
					19.660833661723245,
					-5.617381046206674
				],
				[
					19.660833661723245,
					-2.8086905231034507
				],
				[
					19.660833661723245,
					0
				],
				[
					21.065178923274743,
					1.404345261551498
				],
				[
					22.46952418482647,
					2.8086905231032233
				],
				[
					25.278214707929692,
					2.8086905231032233
				],
				[
					29.491250492584868,
					0
				],
				[
					32.29994101568809,
					-2.8086905231034507
				],
				[
					33.70428627723982,
					-5.617381046206674
				],
				[
					33.70428627723982,
					-8.426071569309897
				],
				[
					33.70428627723982,
					-9.830416830861623
				],
				[
					32.29994101568809,
					-8.426071569309897
				],
				[
					30.895595754136366,
					-4.213035784654949
				],
				[
					30.895595754136366,
					0
				],
				[
					33.70428627723982,
					4.213035784654949
				],
				[
					42.130357846549714,
					4.213035784654949
				],
				[
					43.53470310810121,
					4.213035784654949
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.018927032127976418,
				0.025462280958890915,
				0.06136978045105934,
				0.10131914913654327,
				0.11568246781826019,
				0.12329385429620743,
				0.12929311394691467,
				0.13453277945518494,
				0.12830504775047302,
				0.11201135069131851,
				0.07637957483530045,
				0.03103732317686081,
				0.008037658408284187,
				0.009205169975757599,
				0.01746108941733837,
				0.049011535942554474,
				0.0966678187251091,
				0.11573009938001633,
				0.13938064873218536,
				0.14039257168769836,
				0.11386309564113617,
				0.07982925325632095,
				0.049444518983364105,
				0.04505578428506851,
				0.04100143536925316,
				0.054853424429893494,
				0.06100878864526749,
				0.07481957972049713,
				0.07710787653923035,
				0.07654009759426117,
				0.07262802124023438,
				0.10019344836473465,
				0.10928347706794739,
				0.11413079500198364,
				0.12033404409885406,
				0.12237045168876648,
				0.12505929172039032,
				0.12543825805187225,
				0.12696363031864166,
				0.12568707764148712,
				0.12248959392309189,
				0.1225065290927887,
				0.12220138311386108,
				0.12169628590345383,
				0.1447048932313919,
				0.16828219592571259,
				0.1882995367050171,
				0.20984478294849396,
				0.21656464040279388,
				0.1817416101694107,
				0.04608551040291786,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 14,
			"versionNonce": 941691800,
			"isDeleted": false,
			"id": "stMY0W1hxpYWX8cCJjhJM",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 983.0358889572267,
			"y": 1026.1766348896906,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.46952418482647,
			"height": 1.4043452615517253,
			"seed": 160622744,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.404345261551498,
					0
				],
				[
					-1.404345261551498,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					5.617381046206674,
					-1.4043452615517253
				],
				[
					11.234762092413348,
					-1.4043452615517253
				],
				[
					15.447797877068297,
					-1.4043452615517253
				],
				[
					19.660833661723245,
					-1.4043452615517253
				],
				[
					21.06517892327497,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.057634733617305756,
				0.06310244649648666,
				0.08122778683900833,
				0.08046926558017731,
				0.06665289402008057,
				0.03827740624547005,
				0.0074269408360123634,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 618500584,
			"isDeleted": false,
			"id": "QV2arGnJVvDfav9g_JlvC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 983.0358889572267,
			"y": 1031.7940159358973,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.065178923274743,
			"height": 1.4043452615517253,
			"seed": 347507096,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.404345261551498,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					5.617381046206674,
					-1.4043452615517253
				],
				[
					11.234762092413348,
					-1.4043452615517253
				],
				[
					18.25648840017152,
					-1.4043452615517253
				],
				[
					19.660833661723245,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07504400610923767,
				0.09237591922283173,
				0.08682983368635178,
				0.05786694213747978,
				0.0013603820698335767,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 27,
			"versionNonce": 1324015768,
			"isDeleted": false,
			"id": "fHSFLGDbH48noLI-SZfUm",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1025.1662468037764,
			"y": 1021.9635991050357,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.873869446378194,
			"height": 28.086905231032915,
			"seed": 1345912216,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					1.404345261551498,
					-1.4043452615517253
				],
				[
					1.404345261551498,
					-2.808690523103337
				],
				[
					4.213035784654949,
					-4.213035784654949
				],
				[
					5.617381046206447,
					-4.213035784654949
				],
				[
					8.426071569309897,
					-2.808690523103337
				],
				[
					9.830416830861395,
					0
				],
				[
					9.830416830861395,
					5.617381046206674
				],
				[
					7.021726307758172,
					11.23476209241312
				],
				[
					2.8086905231032233,
					15.44779787706807
				],
				[
					-4.213035784654949,
					18.25648840017152
				],
				[
					-8.426071569309897,
					19.660833661723018
				],
				[
					-11.234762092413348,
					18.25648840017152
				],
				[
					-11.234762092413348,
					14.043452615516571
				],
				[
					-9.830416830861623,
					11.23476209241312
				],
				[
					-7.021726307758399,
					9.830416830861623
				],
				[
					-4.213035784654949,
					11.23476209241312
				],
				[
					-1.4043452615517253,
					14.043452615516571
				],
				[
					4.213035784654949,
					19.660833661723018
				],
				[
					9.830416830861395,
					23.873869446377967
				],
				[
					12.639107353964846,
					23.873869446377967
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08360299468040466,
				0.1057019978761673,
				0.14528600871562958,
				0.16828769445419312,
				0.19047650694847107,
				0.19822515547275543,
				0.1878165304660797,
				0.14125733077526093,
				0.10072427242994308,
				0.07070574909448624,
				0.0539826974272728,
				0.06335663050413132,
				0.07853057980537415,
				0.103126160800457,
				0.12595327198505402,
				0.1705794334411621,
				0.19046413898468018,
				0.14183014631271362,
				0.0529564805328846,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 41,
			"versionNonce": 304289000,
			"isDeleted": false,
			"id": "SHVD2mMY4l3MK43SintU1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 845.4100533251649,
			"y": 1072.520028520895,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.895595754136366,
			"height": 11.234762092413348,
			"seed": 739969256,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					-1.4043452615517253,
					-1.4043452615517253
				],
				[
					-2.8086905231032233,
					-1.4043452615517253
				],
				[
					-4.213035784654949,
					-1.4043452615517253
				],
				[
					-5.617381046206674,
					-1.4043452615517253
				],
				[
					-7.021726307758172,
					0
				],
				[
					-9.830416830861623,
					1.4043452615517253
				],
				[
					-9.830416830861623,
					2.8086905231032233
				],
				[
					-11.23476209241312,
					5.617381046206674
				],
				[
					-11.23476209241312,
					7.021726307758172
				],
				[
					-9.830416830861623,
					8.426071569309897
				],
				[
					-7.021726307758172,
					8.426071569309897
				],
				[
					-5.617381046206674,
					8.426071569309897
				],
				[
					-4.213035784654949,
					7.021726307758172
				],
				[
					-2.8086905231032233,
					5.617381046206674
				],
				[
					-2.8086905231032233,
					4.213035784654949
				],
				[
					-2.8086905231032233,
					1.4043452615517253
				],
				[
					-1.4043452615517253,
					0
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					4.213035784654949,
					-1.4043452615517253
				],
				[
					4.213035784654949,
					1.4043452615517253
				],
				[
					4.213035784654949,
					5.617381046206674
				],
				[
					4.213035784654949,
					8.426071569309897
				],
				[
					4.213035784654949,
					9.830416830861623
				],
				[
					7.021726307758399,
					9.830416830861623
				],
				[
					9.830416830861623,
					8.426071569309897
				],
				[
					12.639107353964846,
					5.617381046206674
				],
				[
					14.043452615516571,
					2.8086905231032233
				],
				[
					15.447797877068297,
					1.4043452615517253
				],
				[
					15.447797877068297,
					2.8086905231032233
				],
				[
					15.447797877068297,
					4.213035784654949
				],
				[
					15.447797877068297,
					7.021726307758172
				],
				[
					16.852143138619795,
					9.830416830861623
				],
				[
					19.660833661723245,
					9.830416830861623
				],
				[
					19.660833661723245,
					9.830416830861623
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.02050698921084404,
				0.07933700829744339,
				0.0796414464712143,
				0.07752392441034317,
				0.0757787749171257,
				0.0750933513045311,
				0.07653540372848511,
				0.08427758514881134,
				0.0843958705663681,
				0.08186633139848709,
				0.06877755373716354,
				0.04973388835787773,
				0.027830077335238457,
				0.01463757362216711,
				0.020043212920427322,
				0.02648220770061016,
				0.055963318794965744,
				0.0888003557920456,
				0.10930056869983673,
				0.11148346215486526,
				0.11094033718109131,
				0.10584982484579086,
				0.09710641205310822,
				0.07949191331863403,
				0.07199307531118393,
				0.0741388276219368,
				0.0786343663930893,
				0.09124673157930374,
				0.09955105930566788,
				0.10835644602775574,
				0.10077789425849915,
				0.09009487926959991,
				0.05541519075632095,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 1693650328,
			"isDeleted": false,
			"id": "zjXrfIP6kWbVWBfILl586",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 870.6882680330946,
			"y": 1069.7113379977918,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.8086905231032233,
			"height": 19.660833661723018,
			"seed": 1492558744,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					0
				],
				[
					1.4043452615517253,
					4.213035784654949
				],
				[
					0,
					9.830416830861395
				],
				[
					0,
					14.043452615516344
				],
				[
					-1.404345261551498,
					18.256488400171293
				],
				[
					-1.404345261551498,
					18.256488400171293
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.1370459944009781,
				0.16949599981307983,
				0.1401083618402481,
				0.07060608267784119,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1639987176,
			"isDeleted": false,
			"id": "jn3edR2tWj4f8D-2xP23q",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 865.0708869868881,
			"y": 1078.1374095671017,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 1.4043452615517253,
			"seed": 1787088360,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					2.8086905231032233,
					-1.4043452615517253
				],
				[
					8.426071569309897,
					-1.4043452615517253
				],
				[
					15.44779787706807,
					-1.4043452615517253
				],
				[
					16.852143138619795,
					-1.4043452615517253
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0781746506690979,
				0.048902466893196106,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 68,
			"versionNonce": 1131256472,
			"isDeleted": false,
			"id": "wK3iKKZwFqIHZBpSH_0ut",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 894.5621374794728,
			"y": 1079.5417548286532,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 53.365119938962835,
			"height": 51.96077467741111,
			"seed": 1541901208,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					0
				],
				[
					-1.4043452615517253,
					-1.404345261551498
				],
				[
					-2.8086905231034507,
					-2.8086905231032233
				],
				[
					-4.213035784654949,
					-2.8086905231032233
				],
				[
					-5.617381046206674,
					-2.8086905231032233
				],
				[
					-8.426071569309897,
					-2.8086905231032233
				],
				[
					-9.830416830861623,
					-1.404345261551498
				],
				[
					-11.234762092413348,
					2.8086905231034507
				],
				[
					-11.234762092413348,
					5.617381046206674
				],
				[
					-9.830416830861623,
					7.021726307758399
				],
				[
					-5.617381046206674,
					8.426071569309897
				],
				[
					-1.4043452615517253,
					4.213035784654949
				],
				[
					1.404345261551498,
					0
				],
				[
					2.8086905231032233,
					-4.213035784654949
				],
				[
					2.8086905231032233,
					-8.426071569309897
				],
				[
					2.8086905231032233,
					-9.830416830861395
				],
				[
					2.8086905231032233,
					-8.426071569309897
				],
				[
					1.404345261551498,
					-2.8086905231032233
				],
				[
					0,
					2.8086905231034507
				],
				[
					0,
					7.021726307758399
				],
				[
					1.404345261551498,
					9.830416830861623
				],
				[
					5.617381046206447,
					11.234762092413348
				],
				[
					9.830416830861623,
					9.830416830861623
				],
				[
					11.23476209241312,
					5.617381046206674
				],
				[
					12.639107353964846,
					1.4043452615517253
				],
				[
					14.043452615516571,
					-1.404345261551498
				],
				[
					14.043452615516571,
					-4.213035784654949
				],
				[
					12.639107353964846,
					-1.404345261551498
				],
				[
					12.639107353964846,
					2.8086905231034507
				],
				[
					12.639107353964846,
					7.021726307758399
				],
				[
					15.44779787706807,
					9.830416830861623
				],
				[
					18.25648840017152,
					11.234762092413348
				],
				[
					23.873869446377967,
					11.234762092413348
				],
				[
					28.086905231032915,
					7.021726307758399
				],
				[
					30.895595754136366,
					2.8086905231034507
				],
				[
					32.299941015687864,
					0
				],
				[
					32.299941015687864,
					-1.404345261551498
				],
				[
					32.299941015687864,
					-2.8086905231032233
				],
				[
					32.299941015687864,
					-1.404345261551498
				],
				[
					30.895595754136366,
					1.4043452615517253
				],
				[
					29.49125049258464,
					4.213035784654949
				],
				[
					29.49125049258464,
					8.426071569309897
				],
				[
					30.895595754136366,
					11.234762092413348
				],
				[
					35.108631538791315,
					11.234762092413348
				],
				[
					37.91732206189454,
					7.021726307758399
				],
				[
					40.72601258499776,
					2.8086905231034507
				],
				[
					42.13035784654949,
					0
				],
				[
					42.13035784654949,
					-1.404345261551498
				],
				[
					42.13035784654949,
					0
				],
				[
					40.72601258499776,
					4.213035784654949
				],
				[
					40.72601258499776,
					9.830416830861623
				],
				[
					40.72601258499776,
					18.25648840017152
				],
				[
					40.72601258499776,
					28.086905231033143
				],
				[
					39.32166732344626,
					36.51297680034304
				],
				[
					37.91732206189454,
					40.72601258499799
				],
				[
					36.51297680034281,
					42.130357846549714
				],
				[
					33.70428627723959,
					39.32166732344649
				],
				[
					29.49125049258464,
					35.10863153879154
				],
				[
					28.086905231032915,
					30.895595754136593
				],
				[
					28.086905231032915,
					26.682559969481417
				],
				[
					33.70428627723959,
					23.873869446378194
				],
				[
					35.108631538791315,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.050217896699905396,
				0.09971630573272705,
				0.118424192070961,
				0.137162446975708,
				0.15280809998512268,
				0.15730352699756622,
				0.15145154297351837,
				0.14970773458480835,
				0.1396557241678238,
				0.13056448101997375,
				0.07602642476558685,
				0.03996624797582626,
				0.01806887798011303,
				0.02073104865849018,
				0.06725378334522247,
				0.10889379680156708,
				0.1550177037715912,
				0.15992584824562073,
				0.15780432522296906,
				0.15303386747837067,
				0.14401739835739136,
				0.10770358145236969,
				0.0642138347029686,
				0.026530425995588303,
				0.028223510831594467,
				0.028324982151389122,
				0.04945776239037514,
				0.10866949707269669,
				0.13386651873588562,
				0.15528613328933716,
				0.16508489847183228,
				0.13037942349910736,
				0.07606887817382812,
				0.01335952803492546,
				0,
				0.013014129363000393,
				0.06038665771484375,
				0.11470471322536469,
				0.16067920625209808,
				0.19351662695407867,
				0.21776290237903595,
				0.22683535516262054,
				0.21948282420635223,
				0.1327923834323883,
				0.07898779213428497,
				0.027108123525977135,
				0.025222137570381165,
				0.03708718717098236,
				0.072972871363163,
				0.13301602005958557,
				0.1701062023639679,
				0.23708990216255188,
				0.3030100166797638,
				0.29169395565986633,
				0.2805655002593994,
				0.21484118700027466,
				0.15498419106006622,
				0.13022497296333313,
				0.1257164627313614,
				0.08351205289363861,
				0.006650451570749283,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 666958568,
			"isDeleted": false,
			"id": "AERItWEDqDBToAGxv0FOd",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 967.5880910801586,
			"y": 1079.5417548286532,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.852143138619795,
			"height": 1.404345261551498,
			"seed": 832252824,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.8086905231032233,
					-1.404345261551498
				],
				[
					8.426071569309897,
					-1.404345261551498
				],
				[
					15.44779787706807,
					-1.404345261551498
				],
				[
					16.852143138619795,
					-1.404345261551498
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08034081757068634,
				0.07794921845197678,
				0.03399069234728813,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1829668760,
			"isDeleted": false,
			"id": "xBRxHzO2N2kMgHoYaAgtp",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 966.1837458186069,
			"y": 1085.1591358748599,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.234762092413348,
			"height": 0,
			"seed": 620671640,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4043452615517253,
					0
				],
				[
					2.8086905231034507,
					0
				],
				[
					9.830416830861623,
					0
				],
				[
					11.234762092413348,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0933239758014679,
				0.09007702767848969,
				0.026012390851974487,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 380722664,
			"isDeleted": false,
			"id": "aQ49drmwo72JQwGE0fvhD",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1004.1010678805017,
			"y": 1087.967826397963,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.830416830861395,
			"height": 21.065178923274743,
			"seed": 958110104,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.404345261551498
				],
				[
					2.8086905231032233,
					-2.8086905231032233
				],
				[
					4.213035784654949,
					-5.617381046206447
				],
				[
					7.021726307758172,
					-8.426071569309897
				],
				[
					8.426071569309897,
					-11.23476209241312
				],
				[
					9.830416830861395,
					-12.639107353964846
				],
				[
					9.830416830861395,
					-14.043452615516344
				],
				[
					9.830416830861395,
					-11.23476209241312
				],
				[
					8.426071569309897,
					-5.617381046206447
				],
				[
					8.426071569309897,
					-1.404345261551498
				],
				[
					8.426071569309897,
					2.8086905231034507
				],
				[
					8.426071569309897,
					7.021726307758399
				],
				[
					9.830416830861395,
					7.021726307758399
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04267498850822449,
				0.04304208233952522,
				0.05408816412091255,
				0.06057555973529816,
				0.06181219592690468,
				0.0858054831624031,
				0.11134646832942963,
				0.16410571336746216,
				0.18916355073451996,
				0.1800723522901535,
				0.11369189620018005,
				0.01823202520608902,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 1846138008,
			"isDeleted": false,
			"id": "wi41NPStd0k3Ng4xYhRdA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 997.0793415727433,
			"y": 1096.393897967273,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.895595754136366,
			"height": 1.404345261551498,
			"seed": 1909088488,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.8086905231032233,
					-1.404345261551498
				],
				[
					5.617381046206674,
					-1.404345261551498
				],
				[
					14.043452615516571,
					-1.404345261551498
				],
				[
					22.46952418482647,
					0
				],
				[
					29.49125049258464,
					0
				],
				[
					30.895595754136366,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1252959966659546,
				0.16114600002765656,
				0.19671697914600372,
				0.17261362075805664,
				0.11141619831323624,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 798843112,
			"isDeleted": false,
			"id": "7P7VA8ZGIxYjK4NkmuSHt",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 351.78269388975957,
			"y": 805.6944288260812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.213035784654949,
			"height": 37.91732206189465,
			"seed": 1262398696,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					1.4043452615516117
				],
				[
					-1.4043452615517253,
					2.808690523103337
				],
				[
					-1.4043452615517253,
					4.213035784655062
				],
				[
					-1.4043452615517253,
					8.426071569310011
				],
				[
					0,
					14.043452615516458
				],
				[
					1.4043452615516117,
					22.46952418482647
				],
				[
					2.8086905231032233,
					29.491250492584754
				],
				[
					2.8086905231032233,
					35.108631538791315
				],
				[
					2.8086905231032233,
					37.91732206189465
				],
				[
					2.8086905231032233,
					37.91732206189465
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06602316349744797,
				0.0668688639998436,
				0.1141938790678978,
				0.1326879858970642,
				0.14632751047611237,
				0.14308111369609833,
				0.11769629269838333,
				0.05296951159834862,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 739475864,
			"isDeleted": false,
			"id": "kzbkrgw6DWd0LRNHNy0TX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 364.4218012437244,
			"y": 815.5248456569427,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.46952418482647,
			"height": 23.873869446378194,
			"seed": 295821032,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.4043452615517253
				],
				[
					-1.4043452615517253,
					1.4043452615517253
				],
				[
					-2.808690523103337,
					2.8086905231034507
				],
				[
					-5.617381046206674,
					5.617381046206674
				],
				[
					-7.021726307758286,
					9.830416830861623
				],
				[
					-9.830416830861623,
					12.63910735396496
				],
				[
					-9.830416830861623,
					15.447797877068297
				],
				[
					-9.830416830861623,
					18.25648840017152
				],
				[
					-7.021726307758286,
					21.065178923274857
				],
				[
					-1.4043452615517253,
					22.46952418482647
				],
				[
					4.213035784654949,
					22.46952418482647
				],
				[
					11.234762092413234,
					23.873869446378194
				],
				[
					12.639107353964846,
					22.46952418482647
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0433339849114418,
				0.03289041295647621,
				0.053952667862176895,
				0.055120088160037994,
				0.056861236691474915,
				0.07895172387361526,
				0.10433904826641083,
				0.13156509399414062,
				0.1588686853647232,
				0.16778823733329773,
				0.14344950020313263,
				0.05635907128453255,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 1913717736,
			"isDeleted": false,
			"id": "cNwEMdiSdG25Vw8kN21R9",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 395.3173969978608,
			"y": 821.1422267031494,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.46952418482647,
			"height": 4.213035784654949,
			"seed": 1793482392,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615517253,
					-1.4043452615517253
				],
				[
					0,
					-1.4043452615517253
				],
				[
					4.213035784654949,
					-2.8086905231032233
				],
				[
					9.830416830861509,
					-2.8086905231032233
				],
				[
					15.44779787706807,
					-2.8086905231032233
				],
				[
					21.065178923274743,
					-4.213035784654949
				],
				[
					21.065178923274743,
					-4.213035784654949
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.021484985947608948,
				0.03475939854979515,
				0.04586547985672951,
				0.10277026146650314,
				0.0808587372303009,
				0.00556405633687973,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 912232088,
			"isDeleted": false,
			"id": "cn3Lb3MbYDMk-lJE4SwWL",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 398.126087520964,
			"y": 830.972643534011,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.065178923274857,
			"height": 4.213035784654949,
			"seed": 1541391080,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					5.617381046206674,
					-1.4043452615517253
				],
				[
					11.234762092413234,
					-2.808690523103337
				],
				[
					19.66083366172313,
					-4.213035784654949
				],
				[
					21.065178923274857,
					-4.213035784654949
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.019999999552965164,
				0,
				0.00994403101503849,
				0.015726624056696892,
				0.001361602800898254,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 24,
			"versionNonce": 202917608,
			"isDeleted": false,
			"id": "VX0kyeUAwsgS-CW9cNlz2",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 438.8521001059619,
			"y": 807.0987740876328,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.85214313861991,
			"height": 28.08690523103303,
			"seed": 1989349096,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.4043452615516117
				],
				[
					0,
					2.8086905231034507
				],
				[
					1.4043452615517253,
					7.021726307758399
				],
				[
					1.4043452615517253,
					11.234762092413348
				],
				[
					2.808690523103337,
					14.043452615516571
				],
				[
					5.617381046206674,
					14.043452615516571
				],
				[
					8.426071569310011,
					14.043452615516571
				],
				[
					11.234762092413234,
					14.043452615516571
				],
				[
					12.63910735396496,
					12.639107353964846
				],
				[
					15.447797877068183,
					12.639107353964846
				],
				[
					16.85214313861991,
					15.447797877068297
				],
				[
					16.85214313861991,
					18.25648840017152
				],
				[
					16.85214313861991,
					21.065178923274857
				],
				[
					14.043452615516571,
					23.873869446378194
				],
				[
					11.234762092413234,
					26.682559969481417
				],
				[
					8.426071569310011,
					26.682559969481417
				],
				[
					4.213035784654949,
					25.278214707929806
				],
				[
					4.213035784654949,
					25.278214707929806
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07919400185346603,
				0.19132409989833832,
				0.19164040684700012,
				0.18071402609348297,
				0.15350115299224854,
				0.11374764889478683,
				0.09858810156583786,
				0.09577743709087372,
				0.11633340269327164,
				0.1512555480003357,
				0.16617368161678314,
				0.17307214438915253,
				0.18113495409488678,
				0.18984457850456238,
				0.17214316129684448,
				0.1534990817308426,
				0.08251529186964035,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 362937240,
			"isDeleted": false,
			"id": "Qq4KqPNDyE1etiwHlXpho",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 438.8521001059619,
			"y": 808.5031193491845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.87386944637808,
			"height": 5.617381046206674,
			"seed": 940117224,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947099804,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4043452615516117,
					0
				],
				[
					-1.4043452615516117,
					-1.4043452615517253
				],
				[
					1.4043452615517253,
					-1.4043452615517253
				],
				[
					8.426071569310011,
					-2.808690523103337
				],
				[
					19.66083366172313,
					-4.213035784654949
				],
				[
					22.46952418482647,
					-5.617381046206674
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.15214098989963531,
				0.2125440090894699,
				0.24692898988723755,
				0.17972983419895172,
				0
			]
		},
		{
			"type": "text",
			"version": 47,
			"versionNonce": 1267695264,
			"isDeleted": false,
			"id": "6KSQfRq8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -317.4561475197024,
			"y": 1573.2256012928008,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 519.1399536132812,
			"height": 100,
			"seed": 1611434656,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947166080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "R = {ATGAT, GATTA, ATTAT, CATGA} with k = 4\n\n\n",
			"rawText": "R = {ATGAT, GATTA, ATTAT, CATGA} with k = 4\n\n\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "R = {ATGAT, GATTA, ATTAT, CATGA} with k = 4\n\n\n",
			"lineHeight": 1.25,
			"baseline": 92
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 759885288,
			"isDeleted": false,
			"id": "2Aibr2dv0L4CdzWf0DzUi",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -221.12969614243312,
			"y": 1835.1378539854354,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.37160243606661,
			"height": 22.45418075519251,
			"seed": 1981427688,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947202465,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					0,
					-2.0412891595628935
				],
				[
					1.0206445797814752,
					-4.082578319126014
				],
				[
					2.0412891595629787,
					-6.123867478688908
				],
				[
					4.082578319125929,
					-10.206445797814922
				],
				[
					6.123867478688879,
					-14.289024116940709
				],
				[
					8.16515663825183,
					-18.371602436066496
				],
				[
					9.185801218033305,
					-20.412891595629617
				],
				[
					9.185801218033305,
					-22.45418075519251
				],
				[
					10.20644579781478,
					-22.45418075519251
				],
				[
					11.227090377596255,
					-21.433536175411064
				],
				[
					12.24773495737773,
					-19.39224701584817
				],
				[
					13.268379537159205,
					-15.309668696722156
				],
				[
					14.28902411694068,
					-12.247734957377816
				],
				[
					15.309668696722156,
					-9.185801218033248
				],
				[
					17.350957856285106,
					-5.103222898907461
				],
				[
					17.350957856285106,
					-4.082578319126014
				],
				[
					18.37160243606661,
					-3.0619337393445676
				],
				[
					18.37160243606661,
					-3.0619337393445676
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04822198301553726,
				0.030244842171669006,
				0.04643426463007927,
				0.05064496025443077,
				0.048249054700136185,
				0.050681885331869125,
				0.062287140637636185,
				0.08753671497106552,
				0.09491198509931564,
				0.12224826216697693,
				0.15419171750545502,
				0.1667523831129074,
				0.16805605590343475,
				0.1600681096315384,
				0.1352856159210205,
				0.07313793897628784,
				0.021354736760258675,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 1964993432,
			"isDeleted": false,
			"id": "ck6yzecU2gC5n6hc0eAqa",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -225.21227446155902,
			"y": 1824.9314081876205,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.474825334973985,
			"height": 2.0412891595628935,
			"seed": 1402029208,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947202742,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814752,
					0
				],
				[
					4.082578319125901,
					0
				],
				[
					10.20644579781478,
					0
				],
				[
					21.433536175411007,
					-1.0206445797814467
				],
				[
					23.474825334973985,
					-2.0412891595628935
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.12201199680566788,
				0.12919197976589203,
				0.14062811434268951,
				0.04644601419568062,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 760711400,
			"isDeleted": false,
			"id": "Av44UluXWTvsX5MKUVHKC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -187.44842500964435,
			"y": 1814.7249623898058,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.061933739344454,
			"height": 20.412891595629617,
			"seed": 2140191208,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947203249,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.0206445797815036,
					-1.0206445797814467
				],
				[
					-1.0206445797815036,
					0
				],
				[
					0,
					1.0206445797814467
				],
				[
					0,
					5.103222898907461
				],
				[
					1.0206445797814752,
					9.185801218033248
				],
				[
					2.0412891595629503,
					13.268379537159262
				],
				[
					2.0412891595629503,
					16.330313276503603
				],
				[
					2.0412891595629503,
					18.371602436066723
				],
				[
					2.0412891595629503,
					19.39224701584817
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06203802675008774,
				0.16740600764751434,
				0.18504199385643005,
				0.18161368370056152,
				0.17017468810081482,
				0.15749295055866241,
				0.058190155774354935,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1221217688,
			"isDeleted": false,
			"id": "WOyDobdvB5dZKGImxI5dF",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -197.65487080745913,
			"y": 1814.7249623898058,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.49546991475546,
			"height": 2.0412891595628935,
			"seed": 477092248,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947203547,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					1.0206445797814752,
					-1.0206445797814467
				],
				[
					5.103222898907376,
					-1.0206445797814467
				],
				[
					10.20644579781478,
					-1.0206445797814467
				],
				[
					18.37160243606658,
					-1.0206445797814467
				],
				[
					22.45418075519251,
					-1.0206445797814467
				],
				[
					24.49546991475546,
					-2.0412891595628935
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11795397847890854,
				0.1595039963722229,
				0.2108299881219864,
				0.2301740050315857,
				0.16653604805469513,
				0.038872893899679184,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 178433944,
			"isDeleted": false,
			"id": "0pqoCsEvU3ryWIDXXHGVh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -153.76715387685562,
			"y": 1817.7868961291501,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.289024116940652,
			"height": 22.45418075519251,
			"seed": 972879848,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947204141,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797812194
				],
				[
					0,
					-2.0412891595628935
				],
				[
					0,
					-3.06193373934434
				],
				[
					-1.0206445797815036,
					-4.082578319125787
				],
				[
					-3.061933739344454,
					-5.103222898907234
				],
				[
					-4.082578319125901,
					-5.103222898907234
				],
				[
					-6.123867478688851,
					-5.103222898907234
				],
				[
					-8.165156638251801,
					-4.082578319125787
				],
				[
					-10.206445797814752,
					-2.0412891595628935
				],
				[
					-12.247734957377759,
					1.020644579781674
				],
				[
					-13.268379537159205,
					5.103222898907461
				],
				[
					-13.268379537159205,
					9.185801218033475
				],
				[
					-12.247734957377759,
					13.268379537159262
				],
				[
					-10.206445797814752,
					16.33031327650383
				],
				[
					-7.1445120584703545,
					17.350957856285277
				],
				[
					-4.082578319125901,
					17.350957856285277
				],
				[
					0,
					16.33031327650383
				],
				[
					1.0206445797814467,
					15.309668696722383
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10649798810482025,
				0.1325719952583313,
				0.17113400995731354,
				0.20308999717235565,
				0.2270900011062622,
				0.25490400195121765,
				0.25314316153526306,
				0.25481894612312317,
				0.2504802346229553,
				0.24836908280849457,
				0.24956052005290985,
				0.2513613700866699,
				0.2434120774269104,
				0.21813417971134186,
				0.1761343628168106,
				0.01074066199362278,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 2031888360,
			"isDeleted": false,
			"id": "DautQY9k16RVpE8_Byi7K",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -161.93231051510742,
			"y": 1826.9726973471836,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.289024116940652,
			"height": 11.227090377596141,
			"seed": 1775482344,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947204574,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814467,
					0
				],
				[
					3.061933739344397,
					0
				],
				[
					6.123867478688851,
					-1.0206445797814467
				],
				[
					9.185801218033248,
					-1.0206445797814467
				],
				[
					12.247734957377702,
					-1.0206445797814467
				],
				[
					13.268379537159149,
					-1.0206445797814467
				],
				[
					14.289024116940652,
					1.0206445797814467
				],
				[
					13.268379537159149,
					4.082578319125787
				],
				[
					13.268379537159149,
					6.123867478688908
				],
				[
					13.268379537159149,
					9.185801218033248
				],
				[
					13.268379537159149,
					10.206445797814695
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.12466400116682053,
				0.1581951230764389,
				0.17512521147727966,
				0.1891859769821167,
				0.21286563575267792,
				0.23516589403152466,
				0.28756535053253174,
				0.30730438232421875,
				0.3101295828819275,
				0.11804461479187012,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 2001476248,
			"isDeleted": false,
			"id": "IRSuYtNa0cmSo4Aw-Ds1T",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -218.06776240308866,
			"y": 1922.9132878466423,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.433536175411007,
			"height": 25.51611449453685,
			"seed": 533324520,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947212890,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					0,
					-2.0412891595628935
				],
				[
					-1.0206445797814752,
					-4.082578319125787
				],
				[
					-2.0412891595629787,
					-6.123867478688908
				],
				[
					-4.082578319125929,
					-8.165156638251801
				],
				[
					-6.123867478688879,
					-8.165156638251801
				],
				[
					-8.16515663825183,
					-7.1445120584703545
				],
				[
					-10.20644579781478,
					-4.082578319125787
				],
				[
					-12.24773495737773,
					1.0206445797814467
				],
				[
					-12.24773495737773,
					8.165156638251801
				],
				[
					-9.185801218033305,
					15.309668696722156
				],
				[
					-3.061933739344454,
					17.35095785628505
				],
				[
					7.144512058470326,
					13.268379537159262
				],
				[
					9.185801218033276,
					12.247734957377816
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0978979766368866,
				0.1282380074262619,
				0.16963598132133484,
				0.19710998237133026,
				0.21277731657028198,
				0.21358181536197662,
				0.20581384003162384,
				0.20015676319599152,
				0.18114089965820312,
				0.1702432483434677,
				0.16296908259391785,
				0.1558224856853485,
				0.07768508791923523,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 1572355224,
			"isDeleted": false,
			"id": "GZEmbAyNrR08IiBDqUsMG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -200.71680454680356,
			"y": 1933.119733644457,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.392247015848056,
			"height": 21.433536175410836,
			"seed": 118127336,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947213596,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814752,
					-1.0206445797812194
				],
				[
					1.0206445797814752,
					-2.0412891595628935
				],
				[
					2.0412891595629503,
					-4.082578319125787
				],
				[
					3.0619337393444255,
					-7.144512058470127
				],
				[
					5.103222898907376,
					-11.227090377596141
				],
				[
					6.123867478688851,
					-14.289024116940482
				],
				[
					8.165156638251801,
					-18.371602436066496
				],
				[
					9.185801218033276,
					-20.41289159562939
				],
				[
					10.206445797814752,
					-21.433536175410836
				],
				[
					11.227090377596227,
					-20.41289159562939
				],
				[
					12.247734957377702,
					-17.35095785628505
				],
				[
					13.268379537159205,
					-14.289024116940482
				],
				[
					14.28902411694068,
					-11.227090377596141
				],
				[
					16.33031327650363,
					-7.144512058470127
				],
				[
					17.350957856285106,
					-5.103222898907234
				],
				[
					18.37160243606658,
					-2.0412891595628935
				],
				[
					19.392247015848056,
					-1.0206445797812194
				],
				[
					19.392247015848056,
					-1.0206445797812194
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0,
				0.051304444670677185,
				0.04462411627173424,
				0.04736108332872391,
				0.03293600305914879,
				0.03631094470620155,
				0.04677005112171173,
				0.06837326288223267,
				0.10546569526195526,
				0.1201304942369461,
				0.13154135644435883,
				0.1424473524093628,
				0.1523214429616928,
				0.1354808658361435,
				0.12171103060245514,
				0.06935916095972061,
				0.0021385804284363985,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 759771288,
			"isDeleted": false,
			"id": "XSgHNf_VYIGpbQmXeqPMZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -205.82002744571096,
			"y": 1923.9339324264238,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.433536175411035,
			"height": 1.0206445797814467,
			"seed": 644446440,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947213880,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					2.0412891595629503,
					-1.0206445797814467
				],
				[
					8.16515663825183,
					-1.0206445797814467
				],
				[
					14.28902411694068,
					-1.0206445797814467
				],
				[
					19.392247015848085,
					0
				],
				[
					21.433536175411035,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.1466815173625946,
				0.2100609987974167,
				0.17647269368171692,
				0.14167211949825287,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 1841421976,
			"isDeleted": false,
			"id": "8GGtA2HBUiAfuIqFbxBWC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -167.03553341401482,
			"y": 1913.727486628609,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.061933739344454,
			"height": 21.433536175411064,
			"seed": 194102504,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947214382,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					-1.0206445797815036,
					-2.0412891595628935
				],
				[
					-1.0206445797815036,
					-3.06193373934434
				],
				[
					0,
					0
				],
				[
					0,
					4.082578319126014
				],
				[
					1.0206445797814467,
					10.206445797814695
				],
				[
					2.0412891595629503,
					14.289024116940709
				],
				[
					2.0412891595629503,
					17.35095785628505
				],
				[
					2.0412891595629503,
					18.371602436066723
				],
				[
					1.0206445797814467,
					18.371602436066723
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.05717859044671059,
				0.09423892199993134,
				0.20968148112297058,
				0.2193109095096588,
				0.1998368501663208,
				0.17650622129440308,
				0.08148730546236038,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 1845788648,
			"isDeleted": false,
			"id": "IxRMCojgeZTskcNSQobx8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -181.3245575309555,
			"y": 1912.7068420488276,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.495469914755432,
			"height": 0,
			"seed": 784529128,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947214693,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.0412891595629503,
					0
				],
				[
					8.16515663825183,
					0
				],
				[
					15.309668696722127,
					0
				],
				[
					23.474825334973985,
					0
				],
				[
					24.495469914755432,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.2012139856815338,
				0.28290000557899475,
				0.2827025055885315,
				0.24613915383815765,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1434961560,
			"isDeleted": false,
			"id": "0re0EG-TcGFgWcS2mC41G",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -129.27168396210016,
			"y": 1814.7249623898058,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54.09416272841827,
			"height": 2.0412891595628935,
			"seed": 1114755736,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947217188,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.0412891595629503,
					0
				],
				[
					6.123867478688851,
					0
				],
				[
					15.309668696722156,
					0
				],
				[
					27.557403654099858,
					0
				],
				[
					39.80513861147756,
					-1.0206445797814467
				],
				[
					52.05287356885532,
					-2.0412891595628935
				],
				[
					54.09416272841827,
					-2.0412891595628935
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1222088634967804,
				0.19340954720973969,
				0.26563602685928345,
				0.27994799613952637,
				0.2320631742477417,
				0.1062479242682457,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 719695512,
			"isDeleted": false,
			"id": "qifAL5dpMhLs9xm21lexS",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -81.30138871237074,
			"y": 1802.4772274324282,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.309668696722099,
			"height": 18.371602436066496,
			"seed": 2091880168,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947217988,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.0206445797815036,
					0
				],
				[
					-2.0412891595629503,
					0
				],
				[
					-1.0206445797815036,
					0
				],
				[
					1.0206445797814467,
					2.0412891595628935
				],
				[
					3.061933739344397,
					3.06193373934434
				],
				[
					7.144512058470298,
					5.103222898907234
				],
				[
					10.206445797814752,
					6.12386747868868
				],
				[
					11.227090377596198,
					8.165156638251574
				],
				[
					11.227090377596198,
					10.206445797814695
				],
				[
					9.185801218033248,
					13.268379537159035
				],
				[
					5.103222898907347,
					15.309668696721928
				],
				[
					1.0206445797814467,
					17.35095785628505
				],
				[
					-3.061933739344454,
					18.371602436066496
				],
				[
					-4.082578319125901,
					18.371602436066496
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08651299774646759,
				0.13941900432109833,
				0.1430615782737732,
				0.1559886485338211,
				0.15594305098056793,
				0.14831118285655975,
				0.15897922217845917,
				0.16770043969154358,
				0.1737738996744156,
				0.18929477035999298,
				0.17328542470932007,
				0.07758648693561554,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 419682536,
			"isDeleted": false,
			"id": "jeGiEZeHg-i4-K8iuPth4",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -125.18910564297425,
			"y": 1839.2204323045612,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 56.13545188798122,
			"height": 0,
			"seed": 579086056,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947222814,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-2.0412891595629503,
					0
				],
				[
					-3.061933739344454,
					0
				],
				[
					-2.0412891595629503,
					0
				],
				[
					2.0412891595629503,
					0
				],
				[
					9.185801218033305,
					0
				],
				[
					17.350957856285106,
					0
				],
				[
					28.57804823388136,
					0
				],
				[
					38.78449403169611,
					0
				],
				[
					46.949650669947914,
					0
				],
				[
					52.05287356885532,
					0
				],
				[
					53.073518148636765,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.0759819969534874,
				0.16519904136657715,
				0.20249129831790924,
				0.23034249246120453,
				0.24120214581489563,
				0.2273138165473938,
				0.19661444425582886,
				0.12460443377494812,
				0.009698456153273582,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 1788572056,
			"isDeleted": false,
			"id": "PAGD32Kwt72ryzNNognCB",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -80.28074413258929,
			"y": 1833.0965648258725,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.37160243606661,
			"height": 18.371602436066723,
			"seed": 1282443672,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947223603,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.0206445797814467,
					0
				],
				[
					-2.0412891595629503,
					-1.020644579781674
				],
				[
					-1.0206445797814467,
					-1.020644579781674
				],
				[
					1.0206445797815036,
					0
				],
				[
					4.082578319125901,
					1.0206445797814467
				],
				[
					8.165156638251801,
					3.06193373934434
				],
				[
					12.247734957377759,
					5.103222898907234
				],
				[
					16.33031327650366,
					7.1445120584703545
				],
				[
					16.33031327650366,
					8.165156638251574
				],
				[
					14.289024116940709,
					10.206445797814695
				],
				[
					10.206445797814752,
					13.268379537159035
				],
				[
					5.103222898907404,
					15.309668696721928
				],
				[
					0,
					17.35095785628505
				],
				[
					-2.0412891595629503,
					17.35095785628505
				],
				[
					-2.0412891595629503,
					17.35095785628505
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.06912598013877869,
				0.1468796730041504,
				0.15715216100215912,
				0.1606057733297348,
				0.15838605165481567,
				0.14783209562301636,
				0.12228958308696747,
				0.11569005995988846,
				0.11764565855264664,
				0.13531219959259033,
				0.15234820544719696,
				0.14064034819602966,
				0.03477032482624054,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 843674264,
			"isDeleted": false,
			"id": "gRGaCkgTycDRTk08Zs39z",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -29.24851514351542,
			"y": 1813.7043178100243,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 23.474825334973957,
			"seed": 876614632,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947225839,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					0,
					0
				],
				[
					0,
					4.082578319125787
				],
				[
					0,
					10.206445797814695
				],
				[
					0,
					16.330313276503603
				],
				[
					0,
					21.433536175411064
				],
				[
					0,
					22.45418075519251
				],
				[
					0,
					22.45418075519251
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0444108285009861,
				0.19117078185081482,
				0.20150582492351532,
				0.18398639559745789,
				0.15211480855941772,
				0.11395758390426636,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 135713688,
			"isDeleted": false,
			"id": "b0N1ZgQZhXIYtfdisLgxE",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -42.516894680674625,
			"y": 1813.7043178100243,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.70191571257021,
			"height": 2.0412891595628935,
			"seed": 120496872,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947226186,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-2.0412891595629503,
					-1.0206445797814467
				],
				[
					-2.0412891595629503,
					-2.0412891595628935
				],
				[
					1.0206445797814467,
					-2.0412891595628935
				],
				[
					6.123867478688851,
					-2.0412891595628935
				],
				[
					14.289024116940652,
					-2.0412891595628935
				],
				[
					19.392247015848056,
					-2.0412891595628935
				],
				[
					30.61933739344431,
					-2.0412891595628935
				],
				[
					32.66062655300726,
					-2.0412891595628935
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.17247998714447021,
				0.2309899926185608,
				0.26551997661590576,
				0.29227200150489807,
				0.27492475509643555,
				0.033942412585020065,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 600130200,
			"isDeleted": false,
			"id": "D15Bf1bPnqQt_4JNuDJUo",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5.453400569054793,
			"y": 1816.766251549369,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.371602436066553,
			"height": 26.536759074318297,
			"seed": 1210307048,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947226729,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.020644579781674
				],
				[
					1.0206445797814467,
					-1.020644579781674
				],
				[
					1.0206445797814467,
					-2.041289159563121
				],
				[
					1.0206445797814467,
					-3.0619337393445676
				],
				[
					0,
					-5.103222898907461
				],
				[
					-2.0412891595629503,
					-6.123867478689135
				],
				[
					-4.082578319125901,
					-7.1445120584703545
				],
				[
					-7.1445120584703545,
					-7.1445120584703545
				],
				[
					-10.206445797814752,
					-6.123867478689135
				],
				[
					-13.268379537159205,
					-2.041289159563121
				],
				[
					-16.33031327650366,
					4.082578319125787
				],
				[
					-17.350957856285106,
					10.206445797814695
				],
				[
					-16.33031327650366,
					15.309668696721928
				],
				[
					-13.268379537159205,
					17.35095785628505
				],
				[
					-8.165156638251801,
					19.392247015847943
				],
				[
					-4.082578319125901,
					19.392247015847943
				],
				[
					-1.0206445797815036,
					19.392247015847943
				],
				[
					1.0206445797814467,
					18.371602436066496
				],
				[
					1.0206445797814467,
					17.35095785628505
				],
				[
					1.0206445797814467,
					16.330313276503603
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0,
				0.021957244724035263,
				0.06987255811691284,
				0.11955224722623825,
				0.15876394510269165,
				0.18781466782093048,
				0.20474044978618622,
				0.2216106504201889,
				0.2179633527994156,
				0.19378647208213806,
				0.17989736795425415,
				0.1756419986486435,
				0.1705779731273651,
				0.1375034749507904,
				0.09952722489833832,
				0.011803954839706421,
				0,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 2040739480,
			"isDeleted": false,
			"id": "9EEhVMZE8W6_Ya2e17KQP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 6.47404514883624,
			"y": 1829.0139865067465,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.0206445797815036,
			"height": 10.206445797814695,
			"seed": 1477956328,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947226922,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					0,
					0
				],
				[
					0,
					2.0412891595628935
				],
				[
					0,
					5.103222898907461
				],
				[
					1.0206445797815036,
					9.185801218033248
				],
				[
					1.0206445797815036,
					9.185801218033248
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.019999999552965164,
				0.14457598328590393,
				0.1493859887123108,
				0.15230391919612885,
				0.0050073242746293545,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 1955964904,
			"isDeleted": false,
			"id": "6HIZAHeTza6l6B5ppKTEl",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1.6911114894155617,
			"y": 1827.993341926965,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.309668696722156,
			"height": 1.0206445797814467,
			"seed": 1313021672,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947227171,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797815036,
					0
				],
				[
					3.061933739344454,
					0
				],
				[
					7.1445120584703545,
					0
				],
				[
					14.289024116940709,
					-1.0206445797814467
				],
				[
					15.309668696722156,
					-1.0206445797814467
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09033999592065811,
				0.1283479928970337,
				0.13578473031520844,
				0.032661985605955124,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 1578854632,
			"isDeleted": false,
			"id": "c5CxuRy8jEgBsh44FbjYv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 19.742424685995445,
			"y": 1840.2410768843429,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.45418075519251,
			"height": 25.516114494537078,
			"seed": 115813016,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947227811,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.020644579781674
				],
				[
					1.0206445797815036,
					-2.041289159563121
				],
				[
					1.0206445797815036,
					-4.082578319126014
				],
				[
					2.0412891595629503,
					-6.123867478688908
				],
				[
					5.103222898907404,
					-11.227090377596369
				],
				[
					7.1445120584703545,
					-16.33031327650383
				],
				[
					9.185801218033305,
					-20.412891595629617
				],
				[
					11.227090377596255,
					-23.474825334973957
				],
				[
					11.227090377596255,
					-25.516114494537078
				],
				[
					12.247734957377759,
					-25.516114494537078
				],
				[
					13.268379537159205,
					-23.474825334973957
				],
				[
					14.289024116940709,
					-20.412891595629617
				],
				[
					16.33031327650366,
					-16.33031327650383
				],
				[
					18.37160243606661,
					-12.247734957377816
				],
				[
					19.392247015848056,
					-8.165156638252029
				],
				[
					21.433536175411064,
					-5.103222898907461
				],
				[
					21.433536175411064,
					-3.0619337393445676
				],
				[
					22.45418075519251,
					-3.0619337393445676
				],
				[
					21.433536175411064,
					-3.0619337393445676
				],
				[
					20.41289159562956,
					-3.0619337393445676
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09458199888467789,
				0.11271756142377853,
				0.12089031934738159,
				0.12084515392780304,
				0.1069142147898674,
				0.11228851228952408,
				0.1419474482536316,
				0.17181172966957092,
				0.20829685032367706,
				0.2699521780014038,
				0.28728169202804565,
				0.3100951015949249,
				0.3101898431777954,
				0.2934674918651581,
				0.24395519495010376,
				0.1608426868915558,
				0.07379648089408875,
				0.0025019836612045765,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 1699233944,
			"isDeleted": false,
			"id": "_Wvva3IGw7hPVxeOHogcg",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 18.721780106214,
			"y": 1826.9726973471836,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.53675907431841,
			"height": 0,
			"seed": 844757400,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947228070,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814467,
					0
				],
				[
					5.103222898907347,
					0
				],
				[
					14.289024116940652,
					0
				],
				[
					24.49546991475546,
					0
				],
				[
					26.53675907431841,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0673401802778244,
				0.1306995302438736,
				0.19526217877864838,
				0.1703622192144394,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 14,
			"versionNonce": 1556831128,
			"isDeleted": false,
			"id": "Ip4wRbbM0NS6HoBWce2mR",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 79.96045489310262,
			"y": 1825.9520527674022,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 41.84642777104057,
			"height": 1.020644579781674,
			"seed": 583775464,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947230397,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-2.0412891595629503,
					0
				],
				[
					-3.061933739344454,
					0
				],
				[
					-4.082578319125901,
					0
				],
				[
					-5.103222898907404,
					0
				],
				[
					-4.082578319125901,
					0
				],
				[
					0,
					0
				],
				[
					5.103222898907404,
					0
				],
				[
					13.268379537159205,
					0
				],
				[
					21.433536175411007,
					-1.020644579781674
				],
				[
					29.598692813662808,
					-1.020644579781674
				],
				[
					35.722560292351716,
					-1.020644579781674
				],
				[
					36.74320487213316,
					-1.020644579781674
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.03999999910593033,
				0.03361498937010765,
				0.08522997796535492,
				0.1447179913520813,
				0.22437798976898193,
				0.26715201139450073,
				0.30817800760269165,
				0.31906601786613464,
				0.28628960251808167,
				0.21584588289260864,
				0.06946176290512085,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 109404648,
			"isDeleted": false,
			"id": "dHWWmUSHLNY1qtAQBPN9R",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 107.51785854720254,
			"y": 1816.766251549369,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.330313276503716,
			"height": 13.268379537159035,
			"seed": 752601576,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947231228,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814467,
					0
				],
				[
					2.0412891595628935,
					0
				],
				[
					3.06193373934434,
					1.0206445797812194
				],
				[
					6.123867478688794,
					2.0412891595628935
				],
				[
					9.185801218033248,
					3.06193373934434
				],
				[
					13.268379537159149,
					5.103222898907234
				],
				[
					15.309668696722156,
					6.12386747868868
				],
				[
					15.309668696722156,
					8.165156638251574
				],
				[
					14.289024116940595,
					9.185801218033248
				],
				[
					11.227090377596255,
					11.227090377596141
				],
				[
					7.144512058470241,
					12.247734957377588
				],
				[
					3.06193373934434,
					13.268379537159035
				],
				[
					1.0206445797814467,
					13.268379537159035
				],
				[
					0,
					13.268379537159035
				],
				[
					-1.0206445797815604,
					13.268379537159035
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0933133214712143,
				0.1371191442012787,
				0.14852817356586456,
				0.15342968702316284,
				0.15695737302303314,
				0.14273758232593536,
				0.13263171911239624,
				0.12983828783035278,
				0.1364215761423111,
				0.14966681599617004,
				0.1586744636297226,
				0.16381020843982697,
				0.14696624875068665,
				0.07598108053207397,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 1559611624,
			"isDeleted": false,
			"id": "M4hmmXjCtbIndb0oFfpjy",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 166.71524417452815,
			"y": 1818.8075407089318,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.45418075519251,
			"height": 26.536759074318525,
			"seed": 409473176,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947233179,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814467,
					-1.020644579781674
				],
				[
					2.041289159563007,
					-2.0412891595628935
				],
				[
					2.041289159563007,
					-3.0619337393445676
				],
				[
					2.041289159563007,
					-4.082578319126014
				],
				[
					2.041289159563007,
					-6.123867478688908
				],
				[
					2.041289159563007,
					-7.1445120584703545
				],
				[
					0,
					-8.165156638252029
				],
				[
					-1.0206445797814467,
					-8.165156638252029
				],
				[
					-2.041289159563007,
					-8.165156638252029
				],
				[
					-5.103222898907347,
					-8.165156638252029
				],
				[
					-8.165156638251801,
					-7.1445120584703545
				],
				[
					-10.206445797814808,
					-5.103222898907461
				],
				[
					-12.247734957377702,
					-3.0619337393445676
				],
				[
					-14.289024116940709,
					0
				],
				[
					-15.309668696722156,
					2.0412891595628935
				],
				[
					-16.330313276503603,
					6.12386747868868
				],
				[
					-16.330313276503603,
					8.165156638251801
				],
				[
					-14.289024116940709,
					12.247734957377588
				],
				[
					-11.227090377596255,
					15.309668696722156
				],
				[
					-7.1445120584703545,
					17.35095785628505
				],
				[
					-3.061933739344454,
					18.371602436066496
				],
				[
					2.041289159563007,
					16.330313276503603
				],
				[
					5.103222898907347,
					12.247734957377588
				],
				[
					6.123867478688908,
					11.227090377596141
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.13655050098896027,
				0.17627160251140594,
				0.20368951559066772,
				0.23086532950401306,
				0.24583600461483002,
				0.25398966670036316,
				0.26229456067085266,
				0.2708151042461395,
				0.26144343614578247,
				0.2594732940196991,
				0.2572548985481262,
				0.2552436292171478,
				0.2552333474159241,
				0.2602750360965729,
				0.2675226032733917,
				0.27038365602493286,
				0.2735389173030853,
				0.2685401439666748,
				0.2468908131122589,
				0.18116658926010132,
				0.06499060243368149,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 14,
			"versionNonce": 1927568872,
			"isDeleted": false,
			"id": "nRDraz54L4O4Ty2RJ0oie",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 160.59137669583924,
			"y": 1826.9726973471836,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.350957856285163,
			"height": 13.268379537159035,
			"seed": 1825937816,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947233721,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797815604,
					-1.0206445797814467
				],
				[
					4.082578319125901,
					-1.0206445797814467
				],
				[
					9.185801218033362,
					-1.0206445797814467
				],
				[
					12.247734957377816,
					-1.0206445797814467
				],
				[
					15.309668696722156,
					-1.0206445797814467
				],
				[
					17.350957856285163,
					-1.0206445797814467
				],
				[
					17.350957856285163,
					1.0206445797814467
				],
				[
					17.350957856285163,
					3.06193373934434
				],
				[
					17.350957856285163,
					5.103222898907234
				],
				[
					15.309668696722156,
					9.185801218033248
				],
				[
					15.309668696722156,
					12.247734957377588
				],
				[
					15.309668696722156,
					12.247734957377588
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1302739828824997,
				0.15591198205947876,
				0.1787640005350113,
				0.20504269003868103,
				0.2156803011894226,
				0.23380157351493835,
				0.24596215784549713,
				0.258955180644989,
				0.2726895213127136,
				0.2539879381656647,
				0.026997314766049385,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1675930856,
			"isDeleted": false,
			"id": "aIB6pEQ35rv-gqi7pkDTB",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 192.23135866906512,
			"y": 1815.7456069695872,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.103222898907461,
			"height": 19.39224701584817,
			"seed": 1653003416,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947234096,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					0,
					0
				],
				[
					0,
					4.082578319126014
				],
				[
					-2.041289159563007,
					9.185801218033248
				],
				[
					-4.082578319125901,
					14.289024116940709
				],
				[
					-5.103222898907461,
					18.371602436066723
				],
				[
					-4.082578319125901,
					16.330313276503603
				],
				[
					-3.061933739344454,
					15.309668696722156
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08102160692214966,
				0.15780173242092133,
				0.19612601399421692,
				0.207183375954628,
				0.17709967494010925,
				0.11225464195013046,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 14,
			"versionNonce": 1245430248,
			"isDeleted": false,
			"id": "HMNdg19PIVn1NwOb6vmGt",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 193.25200324884656,
			"y": 1817.7868961291501,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.330313276503603,
			"height": 18.371602436066723,
			"seed": 1001846168,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947234344,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814467,
					-2.0412891595628935
				],
				[
					2.0412891595628935,
					-3.06193373934434
				],
				[
					3.061933739344454,
					-3.06193373934434
				],
				[
					5.103222898907347,
					-1.0206445797812194
				],
				[
					7.1445120584703545,
					2.041289159563121
				],
				[
					10.206445797814808,
					6.123867478688908
				],
				[
					12.247734957377702,
					10.206445797814922
				],
				[
					14.289024116940709,
					13.268379537159262
				],
				[
					15.309668696722156,
					15.309668696722383
				],
				[
					16.330313276503603,
					15.309668696722383
				],
				[
					15.309668696722156,
					15.309668696722383
				],
				[
					14.289024116940709,
					14.289024116940709
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10333798080682755,
				0.15128198266029358,
				0.21671201288700104,
				0.27135199308395386,
				0.3132510185241699,
				0.3341040015220642,
				0.32451602816581726,
				0.24369454383850098,
				0.027677001431584358,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 2080285848,
			"isDeleted": false,
			"id": "5RC9Ry42TFCvSBtlaPj_R",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 185.08684661059476,
			"y": 1823.910763607839,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.43353617541095,
			"height": 1.0206445797814467,
			"seed": 1506259096,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947234579,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.0206445797814467
				],
				[
					-1.0206445797814467,
					1.0206445797814467
				],
				[
					2.0412891595628935,
					1.0206445797814467
				],
				[
					7.1445120584703545,
					1.0206445797814467
				],
				[
					14.289024116940709,
					1.0206445797814467
				],
				[
					19.392247015848056,
					1.0206445797814467
				],
				[
					20.412891595629503,
					1.0206445797814467
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.15018774569034576,
				0.15538400411605835,
				0.20044399797916412,
				0.09185320883989334,
				0.025824157521128654,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1615644056,
			"isDeleted": false,
			"id": "ZOPqn3yXbMcbQdwMJgIiM",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 222.85069606250943,
			"y": 1814.7249623898058,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.0412891595628935,
			"height": 17.35095785628505,
			"seed": 1142788328,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947234928,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0206445797814467,
					1.0206445797814467
				],
				[
					1.0206445797814467,
					4.082578319126014
				],
				[
					1.0206445797814467,
					8.165156638251801
				],
				[
					1.0206445797814467,
					12.247734957377816
				],
				[
					2.0412891595628935,
					16.330313276503603
				],
				[
					2.0412891595628935,
					17.35095785628505
				],
				[
					1.0206445797814467,
					17.35095785628505
				],
				[
					1.0206445797814467,
					17.35095785628505
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.2264700084924698,
				0.2663800120353699,
				0.2804909944534302,
				0.2628936469554901,
				0.1924036294221878,
				0.07490664720535278,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 819018136,
			"isDeleted": false,
			"id": "KhXqqZ1ofA6tVBMECYB3x",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 211.62360568491317,
			"y": 1814.7249623898058,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.53675907431841,
			"height": 2.0412891595628935,
			"seed": 738066408,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947235189,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0206445797814467
				],
				[
					3.061933739344454,
					-2.0412891595628935
				],
				[
					8.165156638251801,
					-1.0206445797814467
				],
				[
					15.309668696722156,
					-1.0206445797814467
				],
				[
					25.51611449453685,
					-1.0206445797814467
				],
				[
					26.53675907431841,
					-1.0206445797814467
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.12257400155067444,
				0.1734093874692917,
				0.2510848343372345,
				0.2738659977912903,
				0.14730706810951233,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 14,
			"versionNonce": 119279512,
			"isDeleted": false,
			"id": "KJZ73gPD0nWwqQSmHAWkH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 185.6277434750782,
			"y": 1850.9073696844646,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.2369468845089386,
			"height": 52.56825178596,
			"seed": 1651163368,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947249695,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.1184734422545262
				],
				[
					0,
					-2.236946884508825
				],
				[
					0,
					-3.355420326763351
				],
				[
					0,
					-2.236946884508825
				],
				[
					1.1184734422544125,
					2.236946884508825
				],
				[
					1.1184734422544125,
					8.947787538035755
				],
				[
					1.1184734422544125,
					19.014048518325808
				],
				[
					0,
					29.08030949861609
				],
				[
					0,
					36.90962359439732
				],
				[
					-1.1184734422545262,
					43.62046424792425
				],
				[
					-1.1184734422545262,
					46.9758845746876
				],
				[
					-1.1184734422545262,
					49.21283145919665
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.054108429700136185,
				0.06475244462490082,
				0.10869207978248596,
				0.12478222697973251,
				0.13270798325538635,
				0.12357611209154129,
				0.1211630254983902,
				0.09348892420530319,
				0.05523043870925903,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 930999784,
			"isDeleted": false,
			"id": "rxb-EorV6jomO0zsfCHII",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 175.56148249478792,
			"y": 1890.053940163371,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.487942287343913,
			"height": 13.42168130705386,
			"seed": 337663464,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947250511,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.1184734422545262
				],
				[
					1.1184734422545262,
					-1.1184734422545262
				],
				[
					2.2369468845089386,
					0
				],
				[
					3.355420326763465,
					2.2369468845090523
				],
				[
					5.592367211272403,
					5.592367211272403
				],
				[
					7.829314095781342,
					7.829314095781228
				],
				[
					10.06626098029028,
					10.06626098029028
				],
				[
					11.184734422544693,
					11.184734422544807
				],
				[
					12.30320786479922,
					11.184734422544807
				],
				[
					14.540154749308158,
					10.06626098029028
				],
				[
					15.65862819156257,
					7.829314095781228
				],
				[
					17.89557507607151,
					5.592367211272403
				],
				[
					20.132521960580448,
					2.2369468845090523
				],
				[
					23.487942287343913,
					-2.2369468845090523
				],
				[
					23.487942287343913,
					-2.2369468845090523
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04712750390172005,
				0.11325885355472565,
				0.1136443167924881,
				0.11858676373958588,
				0.1109372228384018,
				0.10888180881738663,
				0.10828475654125214,
				0.10680896043777466,
				0.11009921133518219,
				0.11975384503602982,
				0.13607913255691528,
				0.14164865016937256,
				0.12972454726696014,
				0.032103270292282104,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 9987480,
			"isDeleted": false,
			"id": "gGd2AcGKAlgFvpaU1jZ5P",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 169.96911528351563,
			"y": 1926.9635637577685,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.829314095781228,
			"height": 25.724889171852737,
			"seed": 2047755416,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947255270,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.2369468845090523
				],
				[
					0,
					-3.3554203267635785
				],
				[
					0,
					-1.1184734422545262
				],
				[
					-2.2369468845089386,
					4.47389376901765
				],
				[
					-3.355420326763351,
					11.18473442254458
				],
				[
					-5.59236721127229,
					17.89557507607151
				],
				[
					-7.829314095781228,
					22.36946884508916
				],
				[
					-6.710840653526816,
					22.36946884508916
				],
				[
					-6.710840653526816,
					21.25099540283486
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.07813598960638046,
				0.12390057742595673,
				0.12355755269527435,
				0.11607708781957626,
				0.08282867074012756,
				0.04236721619963646,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 2070238104,
			"isDeleted": false,
			"id": "R6xKccJBxpnLpbGztL6D1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 172.20606216802457,
			"y": 1924.7266168732594,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.421681307053632,
			"height": 22.369468845089614,
			"seed": 1069309928,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947255559,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.1184734422544125,
					-1.1184734422545262
				],
				[
					2.2369468845089386,
					-2.2369468845090523
				],
				[
					3.355420326763351,
					-2.2369468845090523
				],
				[
					4.473893769017877,
					-1.1184734422545262
				],
				[
					5.59236721127229,
					2.2369468845090523
				],
				[
					7.829314095781228,
					7.829314095781228
				],
				[
					10.066260980290167,
					14.540154749308158
				],
				[
					12.303207864799106,
					17.89557507607151
				],
				[
					13.421681307053632,
					20.13252196058056
				],
				[
					13.421681307053632,
					20.13252196058056
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07233899086713791,
				0.09067797660827637,
				0.12277911603450775,
				0.15938198566436768,
				0.18538199365139008,
				0.20176003873348236,
				0.1690674126148224,
				0.13780267536640167,
				0.08495843410491943,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1525751272,
			"isDeleted": false,
			"id": "XgHcugoSPLNUrmJYV5kRm",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 155.4289605342076,
			"y": 1937.0298247380586,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.55420326763408,
			"height": 1.1184734422542988,
			"seed": 1459442152,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947255868,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.1184734422545262,
					-1.1184734422542988
				],
				[
					2.2369468845089386,
					-1.1184734422542988
				],
				[
					7.829314095781228,
					-1.1184734422542988
				],
				[
					15.658628191562457,
					-1.1184734422542988
				],
				[
					23.4879422873438,
					-1.1184734422542988
				],
				[
					31.317256383125027,
					-1.1184734422542988
				],
				[
					32.43572982537955,
					-1.1184734422542988
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09693799167871475,
				0.1623920053243637,
				0.18464800715446472,
				0.17299044132232666,
				0.14657263457775116,
				0.05352380499243736,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1811508456,
			"isDeleted": false,
			"id": "ZWuVIVL2MrBGKE7aCjD7P",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 201.28637166664078,
			"y": 1924.7266168732594,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.2369468845089386,
			"height": 19.014048518326035,
			"seed": 1587942552,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947256262,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.1184734422544125,
					0
				],
				[
					1.1184734422544125,
					1.1184734422545262
				],
				[
					1.1184734422544125,
					4.473893769017877
				],
				[
					1.1184734422544125,
					10.06626098029028
				],
				[
					2.2369468845089386,
					14.540154749308158
				],
				[
					2.2369468845089386,
					17.89557507607151
				],
				[
					2.2369468845089386,
					19.014048518326035
				],
				[
					1.1184734422544125,
					19.014048518326035
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11729598790407181,
				0.14622335135936737,
				0.15746191143989563,
				0.14514639973640442,
				0.10755514353513718,
				0.0375140979886055,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1218095512,
			"isDeleted": false,
			"id": "-u0_Ejeo-07DP4LubrTpQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 186.74621691733262,
			"y": 1923.608143431005,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27.961836056361676,
			"height": 2.236946884508825,
			"seed": 2085500312,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947256537,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.1184734422544125,
					-1.1184734422545262
				],
				[
					0,
					-1.1184734422545262
				],
				[
					4.473893769017877,
					-2.236946884508825
				],
				[
					10.06626098029028,
					-2.236946884508825
				],
				[
					16.777101633817097,
					-2.236946884508825
				],
				[
					25.72488917185285,
					-2.236946884508825
				],
				[
					26.843362614107264,
					-2.236946884508825
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.13954800367355347,
				0.18209099769592285,
				0.19894097745418549,
				0.18345782160758972,
				0.04397088661789894,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1371908760,
			"isDeleted": false,
			"id": "yeDKLJdr5lUIVnOCOgeHH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.6036280497658,
			"y": 1919.134249661987,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.1184734422544125,
			"height": 21.25099540283486,
			"seed": 586177512,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947256911,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.1184734422544125,
					0
				],
				[
					-1.1184734422544125,
					1.1184734422545262
				],
				[
					-1.1184734422544125,
					4.473893769017877
				],
				[
					0,
					8.947787538035755
				],
				[
					0,
					14.540154749308158
				],
				[
					0,
					19.014048518326035
				],
				[
					0,
					21.25099540283486
				],
				[
					0,
					21.25099540283486
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0820380225777626,
				0.17323198914527893,
				0.18775659799575806,
				0.1916142851114273,
				0.1453382521867752,
				0.059807587414979935,
				0.00644693011417985,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 292025320,
			"isDeleted": false,
			"id": "S0g_cJDEo8xwmlaK-4jxb",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 219.18194674271228,
			"y": 1918.0157762197327,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27.961836056361676,
			"height": 0,
			"seed": 1454500584,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947257204,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.2369468845089386,
					0
				],
				[
					8.947787538035755,
					0
				],
				[
					16.777101633816983,
					0
				],
				[
					26.84336261410715,
					0
				],
				[
					27.961836056361676,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.14853449165821075,
				0.19580398499965668,
				0.21483398973941803,
				0.10195547342300415,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1610584728,
			"isDeleted": false,
			"id": "pF8tyrVviG9WvD2a62GL_",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 174.4430090525335,
			"y": 1967.2286076789292,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.1184734422545262,
			"height": 44.73893769017877,
			"seed": 271556248,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947259362,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					3.3554203267635785
				],
				[
					0,
					7.829314095781456
				],
				[
					0,
					16.777101633816983
				],
				[
					0,
					26.843362614107264
				],
				[
					0,
					34.67267670988849
				],
				[
					0,
					43.62046424792425
				],
				[
					-1.1184734422545262,
					44.73893769017877
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1500501036643982,
				0.1612171083688736,
				0.17498761415481567,
				0.14642150700092316,
				0.12525905668735504,
				0.02632315084338188,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 668039832,
			"isDeleted": false,
			"id": "TtDsYXVIeyI7YdmiZzxUu",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 163.25827462998882,
			"y": 1998.5458640620543,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.4879422873438,
			"height": 15.658628191562684,
			"seed": 1332380392,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947260178,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.1184734422545262,
					1.1184734422545262
				],
				[
					2.2369468845089386,
					4.473893769017877
				],
				[
					4.473893769017877,
					6.71084065352693
				],
				[
					5.592367211272403,
					10.06626098029028
				],
				[
					7.829314095781228,
					13.421681307053632
				],
				[
					8.947787538035755,
					15.658628191562684
				],
				[
					10.066260980290167,
					15.658628191562684
				],
				[
					11.184734422544693,
					15.658628191562684
				],
				[
					12.303207864799106,
					13.421681307053632
				],
				[
					14.540154749308044,
					11.184734422544807
				],
				[
					16.777101633816983,
					7.829314095781456
				],
				[
					20.132521960580448,
					4.473893769017877
				],
				[
					22.369468845089386,
					1.1184734422545262
				],
				[
					23.4879422873438,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1082407534122467,
				0.09853341430425644,
				0.09413690119981766,
				0.08923465013504028,
				0.07643844932317734,
				0.07040359824895859,
				0.06534423679113388,
				0.08434594422578812,
				0.10029040277004242,
				0.10695318877696991,
				0.09569665789604187,
				0.07046414166688919,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 470460568,
			"isDeleted": false,
			"id": "9Jgv0QUE42-zsxGwEXGKg",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 205.76026543565865,
			"y": 1973.939448332456,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.1184734422544125,
			"height": 34.67267670988849,
			"seed": 336272104,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947260753,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.1184734422545262
				],
				[
					1.1184734422544125,
					-2.236946884508825
				],
				[
					1.1184734422544125,
					-1.1184734422545262
				],
				[
					1.1184734422544125,
					1.1184734422545262
				],
				[
					1.1184734422544125,
					4.473893769017877
				],
				[
					1.1184734422544125,
					8.947787538035755
				],
				[
					1.1184734422544125,
					19.014048518325808
				],
				[
					1.1184734422544125,
					25.724889171852737
				],
				[
					0,
					31.31725638312514
				],
				[
					0,
					32.43572982537967
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09039999544620514,
				0.1390320360660553,
				0.1506793200969696,
				0.1587858647108078,
				0.1634947806596756,
				0.14697891473770142,
				0.11378219723701477,
				0.015316559001803398,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 1912126872,
			"isDeleted": false,
			"id": "7_GMhFYg0q3Wj1KsLCvEQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 195.69400445536837,
			"y": 1995.190443735291,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.72488917185285,
			"height": 19.014048518326035,
			"seed": 2109983976,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947261477,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.1184734422545262
				],
				[
					1.1184734422545262,
					-1.1184734422545262
				],
				[
					2.2369468845089386,
					1.1184734422545262
				],
				[
					4.473893769017877,
					3.355420326763351
				],
				[
					5.592367211272403,
					6.710840653526702
				],
				[
					7.829314095781342,
					10.06626098029028
				],
				[
					7.829314095781342,
					12.303207864799106
				],
				[
					8.947787538035755,
					14.540154749308158
				],
				[
					10.06626098029028,
					14.540154749308158
				],
				[
					11.184734422544693,
					13.421681307053632
				],
				[
					13.421681307053632,
					11.184734422544807
				],
				[
					15.65862819156257,
					6.710840653526702
				],
				[
					19.014048518326035,
					3.355420326763351
				],
				[
					21.250995402834974,
					0
				],
				[
					25.72488917185285,
					-3.355420326763351
				],
				[
					25.72488917185285,
					-4.473893769017877
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.03999999910593033,
				0.11291195452213287,
				0.1303555965423584,
				0.13291677832603455,
				0.12959079444408417,
				0.12278872728347778,
				0.12034091353416443,
				0.10333355516195297,
				0.10239578038454056,
				0.11128540337085724,
				0.1281585991382599,
				0.1381063610315323,
				0.14100781083106995,
				0.1396588385105133,
				0.041267700493335724,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 557029096,
			"isDeleted": false,
			"id": "vFFJM7hWNvtPUnzuuQ232",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 159.34245104056356,
			"y": 2059.1112389425125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.2339114641468996,
			"height": 24.6782292829389,
			"seed": 1429047272,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947275126,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.2339114641472406
				],
				[
					-1.2339114641468996,
					-1.2339114641472406
				],
				[
					-1.2339114641468996,
					1.2339114641467859
				],
				[
					-1.2339114641468996,
					6.169557320734384
				],
				[
					-1.2339114641468996,
					12.339114641469223
				],
				[
					-1.2339114641468996,
					18.508671962204062
				],
				[
					-1.2339114641468996,
					22.210406354644874
				],
				[
					-1.2339114641468996,
					23.44431781879166
				],
				[
					0,
					23.44431781879166
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0301319882273674,
				0.07743117958307266,
				0.18269196152687073,
				0.18578417599201202,
				0.16460762917995453,
				0.09080834686756134,
				0.02290777675807476,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1636114328,
			"isDeleted": false,
			"id": "8zulZMt69zAWqZOESIzPC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 143.3016020066534,
			"y": 2056.6434160142185,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.0816980678203,
			"height": 3.7017343924408124,
			"seed": 1856220056,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947275485,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.2339114641468996,
					0
				],
				[
					-1.2339114641468996,
					-1.2339114641467859
				],
				[
					2.467822928293913,
					-1.2339114641467859
				],
				[
					8.637380249028638,
					-1.2339114641467859
				],
				[
					17.274760498057162,
					-1.2339114641467859
				],
				[
					29.6138751395265,
					-2.4678229282940265
				],
				[
					30.8477866036734,
					-3.7017343924408124
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.14562100172042847,
				0.18602398037910461,
				0.2067829966545105,
				0.17924481630325317,
				0.060627471655607224,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 772576152,
			"isDeleted": false,
			"id": "YGzw8gYJMWrTvzVrNBzM8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 195.12588350082467,
			"y": 2056.6434160142185,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 23.44431781879166,
			"seed": 1016088040,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947276069,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					2.4678229282940265
				],
				[
					0,
					7.403468784881625
				],
				[
					0,
					13.573026105616464
				],
				[
					0,
					19.742583426350848
				],
				[
					0,
					23.44431781879166
				],
				[
					0,
					23.44431781879166
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.18930700421333313,
				0.1867135912179947,
				0.17343497276306152,
				0.14164526760578156,
				0.09663119167089462,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1086674072,
			"isDeleted": false,
			"id": "cgnEgQaBJAwmFXWjNk-wA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 181.55285739520843,
			"y": 2055.4095045500717,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.0816980678203,
			"height": 1.2339114641472406,
			"seed": 1969885672,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947276375,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.2339114641470132,
					0
				],
				[
					-1.2339114641470132,
					-1.2339114641472406
				],
				[
					1.2339114641468996,
					-1.2339114641472406
				],
				[
					7.403468784881625,
					-1.2339114641472406
				],
				[
					16.04084903391015,
					-1.2339114641472406
				],
				[
					24.678229282938673,
					-1.2339114641472406
				],
				[
					29.613875139526385,
					-1.2339114641472406
				],
				[
					30.847786603673285,
					-1.2339114641472406
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.11222000420093536,
				0.16679199039936066,
				0.21071799099445343,
				0.2118995040655136,
				0.13364703953266144,
				0.06703191995620728,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 668006040,
			"isDeleted": false,
			"id": "wW7PzfF1sqZmvqgEoEYbh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 217.33628985546943,
			"y": 2078.8538223688633,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.8477866036734,
			"height": 25.912140747085687,
			"seed": 408543464,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947282558,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2339114641470132,
					-2.4678229282940265
				],
				[
					2.467822928293913,
					-6.169557320734839
				],
				[
					4.935645856587826,
					-9.871291713175651
				],
				[
					8.637380249028638,
					-14.80693756976325
				],
				[
					11.105203177322437,
					-18.508671962204062
				],
				[
					12.339114641469337,
					-22.210406354644874
				],
				[
					14.80693756976325,
					-24.6782292829389
				],
				[
					14.80693756976325,
					-25.912140747085687
				],
				[
					16.04084903391015,
					-25.912140747085687
				],
				[
					17.274760498057162,
					-24.6782292829389
				],
				[
					18.508671962204062,
					-22.210406354644874
				],
				[
					19.74258342635096,
					-19.742583426350848
				],
				[
					23.444317818791774,
					-14.80693756976325
				],
				[
					25.912140747085687,
					-9.871291713175651
				],
				[
					27.146052211232586,
					-4.935645856587598
				],
				[
					29.6138751395265,
					-1.2339114641467859
				],
				[
					30.8477866036734,
					-1.2339114641467859
				],
				[
					30.8477866036734,
					-1.2339114641467859
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.04041198641061783,
				0.05537072569131851,
				0.059269197285175323,
				0.06174633651971817,
				0.07272522151470184,
				0.0840546265244484,
				0.09440631419420242,
				0.11348516494035721,
				0.1321338564157486,
				0.13921886682510376,
				0.14980505406856537,
				0.1524442434310913,
				0.1458265632390976,
				0.13004131615161896,
				0.09702731668949127,
				0.06251498311758041,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 701934312,
			"isDeleted": false,
			"id": "aRLK19r0dMkYo8w-Lwwnl",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 211.16673253473482,
			"y": 2068.9825306556877,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 39.48516685270192,
			"height": 4.935645856587598,
			"seed": 852582120,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947282875,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.2339114641467859
				],
				[
					1.2339114641468996,
					-1.2339114641467859
				],
				[
					7.403468784881625,
					-1.2339114641467859
				],
				[
					18.508671962203948,
					-1.2339114641467859
				],
				[
					32.0816980678203,
					-3.7017343924408124
				],
				[
					38.25125538855491,
					-4.935645856587598
				],
				[
					39.48516685270192,
					-4.935645856587598
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10446356236934662,
				0.1520533412694931,
				0.20058199763298035,
				0.17951510846614838,
				0.04896584898233414,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1595545752,
			"isDeleted": false,
			"id": "TXrBv5ChfSnk2m_Hl1HwY",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -197.25796209790025,
			"y": 1860.451493214856,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.467822928293856,
			"height": 32.0816980678203,
			"seed": 74176408,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947288133,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.2339114641470132
				],
				[
					1.2339114641469564,
					-1.2339114641470132
				],
				[
					1.2339114641469564,
					2.467822928293799
				],
				[
					2.467822928293856,
					7.403468784881625
				],
				[
					2.467822928293856,
					17.27476049805705
				],
				[
					2.467822928293856,
					22.210406354644874
				],
				[
					2.467822928293856,
					28.379963675379486
				],
				[
					2.467822928293856,
					30.847786603673285
				],
				[
					2.467822928293856,
					30.847786603673285
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05288998410105705,
				0.13042950630187988,
				0.14540652930736542,
				0.15732116997241974,
				0.15634429454803467,
				0.12676171958446503,
				0.08159750699996948,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 15,
			"versionNonce": 174092776,
			"isDeleted": false,
			"id": "ekrIVD8HTJ7fkjO4jGLOT",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -208.36316527522263,
			"y": 1867.8549619997377,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.678229282938673,
			"height": 12.33911464146945,
			"seed": 1235442920,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947288766,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.2339114641470132
				],
				[
					2.467822928293856,
					-3.7017343924408124
				],
				[
					4.935645856587712,
					-7.403468784881625
				],
				[
					6.169557320734668,
					-8.637380249028638
				],
				[
					9.87129171317548,
					-11.105203177322437
				],
				[
					11.10520317732238,
					-12.33911464146945
				],
				[
					13.573026105616236,
					-12.33911464146945
				],
				[
					14.806937569763193,
					-12.33911464146945
				],
				[
					17.27476049805705,
					-9.871291713175424
				],
				[
					18.508671962204005,
					-6.1695573207346115
				],
				[
					20.97649489049786,
					-3.7017343924408124
				],
				[
					23.444317818791717,
					-1.2339114641470132
				],
				[
					24.678229282938673,
					-1.2339114641470132
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.1180497407913208,
				0.11982779204845428,
				0.125032439827919,
				0.13256536424160004,
				0.13983765244483948,
				0.15661941468715668,
				0.17634399235248566,
				0.1988075226545334,
				0.22205987572669983,
				0.21710525453090668,
				0.22877004742622375,
				0.06256838887929916,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 868498920,
			"isDeleted": false,
			"id": "5HTv2mnX8Cl9O2NVBHSWP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 188.95632618009006,
			"y": 2101.064228723508,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.467822928293799,
			"height": 44.420812709289294,
			"seed": 528875672,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947298358,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.2339114641467859
				],
				[
					1.2339114641468996,
					4.935645856587598
				],
				[
					1.2339114641468996,
					13.573026105616009
				],
				[
					1.2339114641468996,
					27.146052211232472
				],
				[
					1.2339114641468996,
					40.719078316848936
				],
				[
					2.467822928293799,
					44.420812709289294
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.11726891994476318,
				0.12515908479690552,
				0.13166403770446777,
				0.09639370441436768,
				0.0540773943066597,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 117878760,
			"isDeleted": false,
			"id": "etdmQi39HnQ1e6oJOUu6P",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 181.55285739520843,
			"y": 2139.315484112063,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.21040635464476,
			"height": 13.573026105616009,
			"seed": 135591064,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947299234,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2339114641468996,
					1.2339114641467859
				],
				[
					2.467822928293799,
					3.7017343924408124
				],
				[
					4.935645856587712,
					6.169557320734384
				],
				[
					8.637380249028524,
					9.871291713175196
				],
				[
					12.339114641469337,
					9.871291713175196
				],
				[
					16.04084903391015,
					7.403468784881625
				],
				[
					18.508671962203948,
					3.7017343924408124
				],
				[
					20.97649489049786,
					0
				],
				[
					22.21040635464476,
					-3.7017343924408124
				],
				[
					22.21040635464476,
					-3.7017343924408124
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.16313821077346802,
				0.16338065266609192,
				0.1571214348077774,
				0.1552581787109375,
				0.16243740916252136,
				0.1697632074356079,
				0.18321743607521057,
				0.1910162717103958,
				0.09006036072969437,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1358562200,
			"isDeleted": false,
			"id": "DlD2LojcJsddIIMWKivrd",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 163.04418543300437,
			"y": 2181.268473893059,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.467822928293913,
			"height": 24.6782292829389,
			"seed": 1441440408,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947299791,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.4678229282940265
				],
				[
					0,
					-3.7017343924408124
				],
				[
					1.2339114641470132,
					-3.7017343924408124
				],
				[
					1.2339114641470132,
					0
				],
				[
					2.467822928293913,
					6.169557320734839
				],
				[
					2.467822928293913,
					12.339114641469223
				],
				[
					2.467822928293913,
					18.508671962204062
				],
				[
					2.467822928293913,
					20.97649489049809
				],
				[
					2.467822928293913,
					20.97649489049809
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07044598460197449,
				0.08545562624931335,
				0.15218999981880188,
				0.17636428773403168,
				0.16967400908470154,
				0.15282653272151947,
				0.13026544451713562,
				0.07959335297346115,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1486319080,
			"isDeleted": false,
			"id": "izaCcqjymBZ3t9lcc-AfH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.70507079153504,
			"y": 2176.3328280364713,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.613875139526385,
			"height": 3.7017343924408124,
			"seed": 1447797224,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947300073,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.2339114641468996,
					-1.2339114641472406
				],
				[
					1.2339114641470132,
					-1.2339114641472406
				],
				[
					7.403468784881625,
					-1.2339114641472406
				],
				[
					13.57302610561635,
					-1.2339114641472406
				],
				[
					20.97649489049786,
					-2.4678229282940265
				],
				[
					25.912140747085687,
					-2.4678229282940265
				],
				[
					28.379963675379486,
					-3.7017343924408124
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.15174201130867004,
				0.21671999990940094,
				0.22722698748111725,
				0.16956979036331177,
				0.11802941560745239,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1623647640,
			"isDeleted": false,
			"id": "oQdIiQDQA33f9TX9bnyBR",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 191.42414910838386,
			"y": 2178.800650964765,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.637380249028524,
			"height": 29.6138751395265,
			"seed": 827114648,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947300547,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2339114641468996,
					-2.4678229282935717
				],
				[
					1.2339114641468996,
					-3.7017343924408124
				],
				[
					1.2339114641468996,
					-1.2339114641467859
				],
				[
					0,
					2.4678229282940265
				],
				[
					-1.2339114641468996,
					8.637380249028865
				],
				[
					-3.7017343924408124,
					14.80693756976325
				],
				[
					-6.1695573207346115,
					20.97649489049809
				],
				[
					-7.403468784881625,
					24.6782292829389
				],
				[
					-7.403468784881625,
					25.912140747085687
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10166998207569122,
				0.17057400941848755,
				0.1749628633260727,
				0.1769014596939087,
				0.16991323232650757,
				0.11926211416721344,
				0.04314538463950157,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 15,
			"versionNonce": 1240749288,
			"isDeleted": false,
			"id": "iVcKFzTzIOOkGzhprwIgI",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 192.65806057253076,
			"y": 2177.566739500618,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.80693756976325,
			"height": 33.31560953196731,
			"seed": 532013032,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947300859,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-3.7017343924408124
				],
				[
					0,
					-4.935645856587598
				],
				[
					1.2339114641470132,
					-4.935645856587598
				],
				[
					2.467822928293913,
					-1.2339114641467859
				],
				[
					3.7017343924408124,
					3.7017343924408124
				],
				[
					6.169557320734725,
					8.63738024902841
				],
				[
					8.637380249028638,
					13.573026105616464
				],
				[
					11.105203177322437,
					18.508671962204062
				],
				[
					13.57302610561635,
					22.210406354644874
				],
				[
					14.80693756976325,
					24.6782292829389
				],
				[
					14.80693756976325,
					25.912140747085687
				],
				[
					13.57302610561635,
					27.146052211232472
				],
				[
					13.57302610561635,
					28.379963675379713
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08256198465824127,
				0.10465332120656967,
				0.17750650644302368,
				0.2231919914484024,
				0.2500079870223999,
				0.2693600058555603,
				0.2283623367547989,
				0.1747509390115738,
				0.1111331507563591,
				0.05068185552954674,
				0,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 1422827752,
			"isDeleted": false,
			"id": "lEXGbgvubKgpDgjemaIeb",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 175.3833000744737,
			"y": 2187.4380312137937,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.5495209961141,
			"height": 3.7017343924408124,
			"seed": 1037421976,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947301149,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.2339114641468996,
					-1.2339114641472406
				],
				[
					0,
					-1.2339114641472406
				],
				[
					3.7017343924408124,
					-1.2339114641472406
				],
				[
					18.508671962204062,
					-2.4678229282940265
				],
				[
					30.8477866036734,
					-3.7017343924408124
				],
				[
					33.3156095319672,
					-3.7017343924408124
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09204644709825516,
				0.13304300606250763,
				0.19897079467773438,
				0.19157674908638,
				0.03466586396098137,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 1780673768,
			"isDeleted": false,
			"id": "FKuuI-ZPv8ZHXWWjWTZG3",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 224.73975864035106,
			"y": 2175.098916572324,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.2339114641468996,
			"height": 27.146052211232472,
			"seed": 496386456,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947301697,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.2339114641467859
				],
				[
					0,
					7.403468784881625
				],
				[
					0,
					14.80693756976325
				],
				[
					0,
					20.97649489049809
				],
				[
					0,
					25.912140747085687
				],
				[
					-1.2339114641468996,
					24.6782292829389
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09361300617456436,
				0.21353866159915924,
				0.20954571664333344,
				0.19292785227298737,
				0.09976956248283386,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 1888037272,
			"isDeleted": false,
			"id": "6MrdaWr_xw7lcybMm0Jmk",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 208.6989096064409,
			"y": 2175.098916572324,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 37.01734392440801,
			"height": 9.871291713175196,
			"seed": 1870443928,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947302004,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.2339114641468996,
					-1.2339114641467859
				],
				[
					0,
					-1.2339114641467859
				],
				[
					4.935645856587826,
					-2.4678229282935717
				],
				[
					13.57302610561635,
					-3.7017343924408124
				],
				[
					22.210406354644874,
					-6.169557320734384
				],
				[
					34.54952099611421,
					-8.63738024902841
				],
				[
					35.78343246026111,
					-9.871291713175196
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.14345398545265198,
				0.1745700091123581,
				0.2661140263080597,
				0.314113974571228,
				0.19997619092464447,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 37,
			"versionNonce": 1070412264,
			"isDeleted": false,
			"id": "YxXOveUNOa3D4r0_JC0Yq",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -602.2281519331924,
			"y": 2152.5066741459423,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.11225988632009,
			"height": 18.690368205302093,
			"seed": 388619240,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947627454,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					0,
					-3.1150613675504246
				],
				[
					0,
					-5.191768945917374
				],
				[
					1.0383537891834749,
					-7.268476524284324
				],
				[
					2.0767075783669497,
					-10.383537891834749
				],
				[
					4.153415156733786,
					-12.460245470201698
				],
				[
					7.26847652428421,
					-14.536953048568648
				],
				[
					8.306830313467572,
					-13.498599259384719
				],
				[
					10.383537891834521,
					-9.345184102651274
				],
				[
					10.383537891834521,
					-5.191768945917374
				],
				[
					10.383537891834521,
					-2.0767075783669497
				],
				[
					10.383537891834521,
					1.0383537891834749
				],
				[
					10.383537891834521,
					2.0767075783669497
				],
				[
					10.383537891834521,
					0
				],
				[
					10.383537891834521,
					-2.0767075783669497
				],
				[
					11.421891681017996,
					-7.268476524284324
				],
				[
					11.421891681017996,
					-10.383537891834749
				],
				[
					13.498599259384832,
					-14.536953048568648
				],
				[
					15.575306837751782,
					-15.575306837751668
				],
				[
					16.613660626935257,
					-13.498599259384719
				],
				[
					17.652014416118618,
					-9.345184102651274
				],
				[
					18.690368205302093,
					-6.230122735100849
				],
				[
					18.690368205302093,
					-3.1150613675504246
				],
				[
					19.728721994485568,
					-1.0383537891834749
				],
				[
					19.728721994485568,
					-4.1534151567338995
				],
				[
					19.728721994485568,
					-7.268476524284324
				],
				[
					19.728721994485568,
					-11.421891681018224
				],
				[
					21.805429572852404,
					-14.536953048568648
				],
				[
					23.882137151219354,
					-16.613660626935143
				],
				[
					25.958844729586303,
					-16.613660626935143
				],
				[
					26.997198518769665,
					-13.498599259384719
				],
				[
					26.997198518769665,
					-9.345184102651274
				],
				[
					26.997198518769665,
					-5.191768945917374
				],
				[
					29.073906097136614,
					-2.0767075783669497
				],
				[
					30.11225988632009,
					-2.0767075783669497
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.04963226243853569,
				0.06050018221139908,
				0.07792666554450989,
				0.09517575055360794,
				0.10705249011516571,
				0.10760263353586197,
				0.1021060198545456,
				0.08200863748788834,
				0.06034008786082268,
				0.02255990542471409,
				0.0018515625270083547,
				0,
				0.01575421169400215,
				0.019643036648631096,
				0.06462490558624268,
				0.08310782164335251,
				0.09870611876249313,
				0.10479989647865295,
				0.09854675084352493,
				0.07540682703256607,
				0.04060788080096245,
				0.015009612776339054,
				0.003983337432146072,
				0.008348144590854645,
				0.06120571866631508,
				0.10263900458812714,
				0.12225750833749771,
				0.1328813135623932,
				0.12296142429113388,
				0.1233600452542305,
				0.0924491286277771,
				0.06159094348549843,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 18,
			"versionNonce": 1978485992,
			"isDeleted": false,
			"id": "0W9ogFfy-ExQqoj5ey8SN",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -559.655646576671,
			"y": 2136.9313673081906,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.460245470201471,
			"height": 14.536953048568193,
			"seed": 1413824664,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947627871,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					0,
					-2.0767075783669497
				],
				[
					-1.0383537891834749,
					-2.0767075783669497
				],
				[
					-3.115061367550311,
					-2.0767075783669497
				],
				[
					-4.153415156733786,
					-1.0383537891834749
				],
				[
					-6.2301227351007356,
					3.11506136754997
				],
				[
					-6.2301227351007356,
					8.306830313467344
				],
				[
					-3.115061367550311,
					11.421891681017769
				],
				[
					1.0383537891834749,
					12.460245470201244
				],
				[
					4.153415156733786,
					11.421891681017769
				],
				[
					6.2301227351007356,
					9.34518410265082
				],
				[
					6.2301227351007356,
					6.2301227351003945
				],
				[
					5.191768945917261,
					4.153415156733445
				],
				[
					2.0767075783669497,
					1.0383537891830201
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.010799743235111237,
				0.06894399970769882,
				0.11023718118667603,
				0.12004824727773666,
				0.12009420990943909,
				0.11045617610216141,
				0.07563519477844238,
				0.035983793437480927,
				0.013139892369508743,
				0.016409698873758316,
				0.04384158179163933,
				0.06683956831693649,
				0.08469793945550919,
				0.007561920210719109,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 346504600,
			"isDeleted": false,
			"id": "ykMo22gfNjG-IsCX1ayud",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -542.0036321605523,
			"y": 2136.9313673081906,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.2301227351007356,
			"height": 18.690368205302093,
			"seed": 604525976,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947628288,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					0,
					-2.0767075783669497
				],
				[
					-1.0383537891834749,
					-3.1150613675504246
				],
				[
					-2.076707578366836,
					-3.1150613675504246
				],
				[
					-4.153415156733786,
					-4.1534151567338995
				],
				[
					-5.191768945917261,
					-2.0767075783669497
				],
				[
					-5.191768945917261,
					0
				],
				[
					-4.153415156733786,
					3.11506136754997
				],
				[
					-1.0383537891834749,
					8.306830313467344
				],
				[
					0,
					11.421891681017769
				],
				[
					1.0383537891834749,
					13.498599259384719
				],
				[
					0,
					14.536953048568193
				],
				[
					-3.115061367550311,
					14.536953048568193
				],
				[
					-5.191768945917261,
					12.460245470201244
				],
				[
					-5.191768945917261,
					11.421891681017769
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04075198248028755,
				0.08279123157262802,
				0.10514999181032181,
				0.1242634579539299,
				0.13573281466960907,
				0.1623288244009018,
				0.16511844098567963,
				0.1380036622285843,
				0.10109978914260864,
				0.0582236647605896,
				0.04893963783979416,
				0.04182736203074455,
				0.05314037948846817,
				0.035228729248046875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 420467688,
			"isDeleted": false,
			"id": "ZwlqFmVOXLRESN9kaDgCS",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -533.6968018470848,
			"y": 2132.7779521514567,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.0383537891834749,
			"height": 17.652014416118618,
			"seed": 1520895976,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947628562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.0383537891834749,
					-1.0383537891834749
				],
				[
					-1.0383537891834749,
					1.0383537891834749
				],
				[
					-1.0383537891834749,
					3.1150613675504246
				],
				[
					-1.0383537891834749,
					8.306830313467344
				],
				[
					-1.0383537891834749,
					13.498599259384719
				],
				[
					0,
					15.575306837751668
				],
				[
					0,
					16.613660626935143
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04436798021197319,
				0.1365523338317871,
				0.15065738558769226,
				0.11970584094524384,
				0.05738107115030289,
				0.008683349937200546,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 1722982376,
			"isDeleted": false,
			"id": "rNHsS_dhU98zbr6auA1Nv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -540.9652783713689,
			"y": 2141.084782464924,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.575306837751668,
			"height": 1.0383537891834749,
			"seed": 527810200,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947628780,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0383537891834749,
					0
				],
				[
					2.0767075783669497,
					-1.0383537891834749
				],
				[
					5.191768945917261,
					-1.0383537891834749
				],
				[
					10.383537891834521,
					0
				],
				[
					14.536953048568307,
					0
				],
				[
					15.575306837751668,
					-1.0383537891834749
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.03266940265893936,
				0.02969137579202652,
				0.015865540131926537,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 20,
			"versionNonce": 1863802344,
			"isDeleted": false,
			"id": "rObN4OK1kVEfhzAwY8rIf",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -516.0447874309662,
			"y": 2123.4327680488054,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.345184102651103,
			"height": 24.920490940402942,
			"seed": 188068504,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947629329,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					0,
					8.306830313467799
				],
				[
					0,
					11.421891681018224
				],
				[
					0,
					17.652014416118618
				],
				[
					1.0383537891834749,
					22.843783362035992
				],
				[
					3.1150613675504246,
					23.882137151219467
				],
				[
					5.1917689459173175,
					22.843783362035992
				],
				[
					6.2301227351007356,
					19.728721994485568
				],
				[
					7.26847652428421,
					18.690368205302093
				],
				[
					7.26847652428421,
					15.575306837752123
				],
				[
					8.306830313467628,
					13.498599259385173
				],
				[
					8.306830313467628,
					12.460245470201698
				],
				[
					8.306830313467628,
					13.498599259385173
				],
				[
					8.306830313467628,
					15.575306837752123
				],
				[
					8.306830313467628,
					19.728721994485568
				],
				[
					8.306830313467628,
					22.843783362035992
				],
				[
					9.345184102651103,
					23.882137151219467
				],
				[
					9.345184102651103,
					23.882137151219467
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.13684961199760437,
				0.13169372081756592,
				0.10996994376182556,
				0.04784686118364334,
				0.013007751666009426,
				0,
				0,
				0,
				0.06812118738889694,
				0.09402254968881607,
				0.13731896877288818,
				0.1467842161655426,
				0.1273895800113678,
				0.0888465866446495,
				0.04343084618449211,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 6,
			"versionNonce": 910051048,
			"isDeleted": false,
			"id": "rygBJeV0GL3NKxhitt4oa",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -506.69960332831505,
			"y": 2127.5861832055393,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.076707578366893,
			"height": 2.0767075783669497,
			"seed": 922997912,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947629480,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-2.076707578366893,
					-2.0767075783669497
				],
				[
					-1.0383537891834749,
					-2.0767075783669497
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06584799289703369,
				0.03816256672143936,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1693695128,
			"isDeleted": false,
			"id": "Xlv2Eecj1xYMryOHvaKXX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -498.3927730148474,
			"y": 2117.202645313705,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.076707578366893,
			"height": 30.112259886319862,
			"seed": 148634520,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947629814,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.0383537891834749,
					-1.0383537891834749
				],
				[
					0,
					1.0383537891834749
				],
				[
					1.038353789183418,
					5.19176894591692
				],
				[
					1.038353789183418,
					10.383537891834294
				],
				[
					1.038353789183418,
					16.613660626935143
				],
				[
					1.038353789183418,
					22.843783362035538
				],
				[
					1.038353789183418,
					26.997198518769437
				],
				[
					1.038353789183418,
					29.073906097136387
				],
				[
					1.038353789183418,
					29.073906097136387
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06697210669517517,
				0.12934164702892303,
				0.15378396213054657,
				0.17713256180286407,
				0.1598786562681198,
				0.13245415687561035,
				0.04152960330247879,
				0.00021621704217977822,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 559904488,
			"isDeleted": false,
			"id": "Rczz3hfrhAtJtcHJj72-u",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -490.08594270137985,
			"y": 2127.5861832055393,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.652014416118618,
			"height": 19.728721994485568,
			"seed": 1655044328,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947630229,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					-1.0383537891834749,
					-2.0767075783669497
				],
				[
					-2.0767075783669497,
					0
				],
				[
					-4.153415156733786,
					4.1534151567338995
				],
				[
					-5.191768945917261,
					9.345184102651274
				],
				[
					-5.191768945917261,
					13.498599259384719
				],
				[
					-2.0767075783669497,
					15.575306837751668
				],
				[
					0,
					16.613660626935143
				],
				[
					3.115061367550311,
					15.575306837751668
				],
				[
					4.153415156733786,
					12.460245470201244
				],
				[
					5.191768945917261,
					9.345184102651274
				],
				[
					5.191768945917261,
					7.268476524284324
				],
				[
					5.191768945917261,
					6.230122735100849
				],
				[
					4.153415156733786,
					6.230122735100849
				],
				[
					3.115061367550311,
					9.345184102651274
				],
				[
					3.115061367550311,
					13.498599259384719
				],
				[
					6.230122735100679,
					17.652014416118618
				],
				[
					10.383537891834465,
					17.652014416118618
				],
				[
					12.460245470201357,
					17.652014416118618
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.1261959820985794,
				0.1521959900856018,
				0.16803283989429474,
				0.16188952326774597,
				0.13390487432479858,
				0.10875308513641357,
				0.0678282156586647,
				0.045053254812955856,
				0.06666043400764465,
				0.09279187023639679,
				0.11277294903993607,
				0.16399066150188446,
				0.21683572232723236,
				0.20626752078533173,
				0.17331832647323608,
				0.1313336193561554,
				0.05126995965838432,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 37,
			"versionNonce": 1772066200,
			"isDeleted": false,
			"id": "dTXlZWDW9rj1m4KROASg3",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -471.39557449607776,
			"y": 2118.2409991028885,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.882137151219354,
			"height": 52.956043248355854,
			"seed": 1067830168,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947631336,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.0383537891834749,
					0
				],
				[
					-1.0383537891834749,
					1.0383537891834749
				],
				[
					-1.0383537891834749,
					6.2301227351003945
				],
				[
					-1.0383537891834749,
					12.460245470201244
				],
				[
					0,
					19.728721994485113
				],
				[
					1.038353789183418,
					23.882137151219013
				],
				[
					4.153415156733786,
					24.920490940402487
				],
				[
					7.268476524284097,
					23.882137151219013
				],
				[
					9.345184102651046,
					19.728721994485113
				],
				[
					11.421891681017883,
					17.652014416118618
				],
				[
					11.421891681017883,
					15.575306837751668
				],
				[
					11.421891681017883,
					14.536953048568193
				],
				[
					11.421891681017883,
					15.575306837751668
				],
				[
					10.383537891834465,
					17.652014416118618
				],
				[
					10.383537891834465,
					20.767075783669043
				],
				[
					11.421891681017883,
					23.882137151219013
				],
				[
					13.498599259384832,
					25.958844729585962
				],
				[
					15.575306837751725,
					25.958844729585962
				],
				[
					16.613660626935143,
					25.958844729585962
				],
				[
					19.72872199448551,
					21.805429572852063
				],
				[
					20.76707578366893,
					18.690368205302093
				],
				[
					20.76707578366893,
					16.613660626935143
				],
				[
					20.76707578366893,
					18.690368205302093
				],
				[
					21.805429572852404,
					23.882137151219013
				],
				[
					21.805429572852404,
					32.18896746468681
				],
				[
					22.84378336203588,
					38.41909019978766
				],
				[
					22.84378336203588,
					45.68756672407153
				],
				[
					20.76707578366893,
					51.91768945917238
				],
				[
					18.690368205302093,
					52.956043248355854
				],
				[
					14.53695304856825,
					52.956043248355854
				],
				[
					11.421891681017883,
					49.84098188080543
				],
				[
					10.383537891834465,
					46.725920513255005
				],
				[
					11.421891681017883,
					43.61085914570458
				],
				[
					16.613660626935143,
					39.45744398897068
				],
				[
					17.652014416118618,
					38.41909019978766
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0806790441274643,
				0.10280090570449829,
				0.10767266899347305,
				0.12188971042633057,
				0.09703759849071503,
				0.06134271249175072,
				0.05267154052853584,
				0.047884032130241394,
				0.0437166765332222,
				0.04500003159046173,
				0.06500238180160522,
				0.07450094819068909,
				0.08199536055326462,
				0.0828576385974884,
				0.06787023693323135,
				0.0563134141266346,
				0.05435629189014435,
				0.05464523285627365,
				0.05175979435443878,
				0.059022337198257446,
				0.0789295956492424,
				0.0977950468659401,
				0.13705670833587646,
				0.14150014519691467,
				0.13603664934635162,
				0.13895468413829803,
				0.12475772202014923,
				0.07349926978349686,
				0.04453592002391815,
				0.051059234887361526,
				0.06095825135707855,
				0.10030020028352737,
				0.08656448125839233,
				0.014594818465411663,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 33,
			"versionNonce": 1739546600,
			"isDeleted": false,
			"id": "NsIBukMXsM95X4Ewc1Aqj",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -429.8614229287398,
			"y": 2142.1231362541075,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.882137151219297,
			"height": 14.536953048568193,
			"seed": 838873064,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947632244,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.038353789183418,
					-1.0383537891834749
				],
				[
					4.153415156733786,
					-4.1534151567338995
				],
				[
					6.230122735100679,
					-7.268476524283869
				],
				[
					8.306830313467572,
					-10.383537891834294
				],
				[
					8.306830313467572,
					-12.460245470201244
				],
				[
					6.230122735100679,
					-13.498599259384719
				],
				[
					5.191768945917204,
					-13.498599259384719
				],
				[
					4.153415156733786,
					-12.460245470201244
				],
				[
					6.230122735100679,
					-10.383537891834294
				],
				[
					9.345184102651046,
					-8.306830313467344
				],
				[
					12.460245470201357,
					-6.2301227351003945
				],
				[
					14.53695304856825,
					-4.1534151567338995
				],
				[
					14.53695304856825,
					-2.0767075783669497
				],
				[
					12.460245470201357,
					-1.0383537891834749
				],
				[
					11.421891681017883,
					-1.0383537891834749
				],
				[
					10.383537891834465,
					-1.0383537891834749
				],
				[
					10.383537891834465,
					-2.0767075783669497
				],
				[
					12.460245470201357,
					-4.1534151567338995
				],
				[
					15.575306837751668,
					-5.19176894591692
				],
				[
					18.690368205302093,
					-8.306830313467344
				],
				[
					20.76707578366893,
					-10.383537891834294
				],
				[
					21.805429572852404,
					-13.498599259384719
				],
				[
					21.805429572852404,
					-14.536953048568193
				],
				[
					19.72872199448551,
					-14.536953048568193
				],
				[
					17.652014416118618,
					-13.498599259384719
				],
				[
					16.613660626935143,
					-10.383537891834294
				],
				[
					15.575306837751668,
					-7.268476524283869
				],
				[
					16.613660626935143,
					-5.19176894591692
				],
				[
					19.72872199448551,
					-3.11506136754997
				],
				[
					22.84378336203588,
					-3.11506136754997
				],
				[
					23.882137151219297,
					-3.11506136754997
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0584864504635334,
				0.062079284340143204,
				0.061614930629730225,
				0.059269532561302185,
				0.07524749636650085,
				0.0873081386089325,
				0.10279028117656708,
				0.11664608865976334,
				0.11545702815055847,
				0.1104956641793251,
				0.08710864186286926,
				0.06729669123888016,
				0.04427358880639076,
				0.04983733966946602,
				0.07080059498548508,
				0.08552539348602295,
				0.09252887219190598,
				0.09053003042936325,
				0.06600213795900345,
				0.05652255192399025,
				0.05703924596309662,
				0.07566912472248077,
				0.11692556738853455,
				0.146823450922966,
				0.1605195552110672,
				0.16954104602336884,
				0.1559046059846878,
				0.12178558111190796,
				0.04400250315666199,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 23,
			"versionNonce": 335856024,
			"isDeleted": false,
			"id": "H15CFRw5b0a-MFlhBXjqL",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -392.48068651813566,
			"y": 2129.6628907839063,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.345184102651046,
			"height": 23.882137151219467,
			"seed": 895808152,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947632787,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					-1.038353789183418,
					-1.0383537891834749
				],
				[
					-2.076707578366893,
					-2.0767075783669497
				],
				[
					-4.153415156733786,
					-2.0767075783669497
				],
				[
					-6.230122735100679,
					-1.0383537891834749
				],
				[
					-7.268476524284154,
					1.0383537891834749
				],
				[
					-8.306830313467572,
					4.1534151567338995
				],
				[
					-8.306830313467572,
					6.230122735100849
				],
				[
					-5.191768945917204,
					7.268476524284324
				],
				[
					-3.1150613675503678,
					8.306830313467344
				],
				[
					-1.038353789183418,
					7.268476524284324
				],
				[
					0,
					6.230122735100849
				],
				[
					1.0383537891834749,
					3.1150613675504246
				],
				[
					1.0383537891834749,
					1.0383537891834749
				],
				[
					1.0383537891834749,
					0
				],
				[
					1.0383537891834749,
					1.0383537891834749
				],
				[
					0,
					5.191768945917374
				],
				[
					-1.038353789183418,
					11.421891681017769
				],
				[
					-1.038353789183418,
					16.613660626935143
				],
				[
					0,
					21.805429572852518
				],
				[
					0,
					21.805429572852518
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07735397666692734,
				0.09079430997371674,
				0.10941433906555176,
				0.12412631511688232,
				0.1344020664691925,
				0.1349332630634308,
				0.12535205483436584,
				0.09997274726629257,
				0.06809866428375244,
				0.03489471599459648,
				0.023507721722126007,
				0.041600096970796585,
				0.09539184719324112,
				0.11474984884262085,
				0.18750445544719696,
				0.20118966698646545,
				0.19070224463939667,
				0.18198300898075104,
				0.12793444097042084,
				0.005026367027312517,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 52,
			"versionNonce": 982905752,
			"isDeleted": false,
			"id": "jVS82BTXFG3XVhhGtBrOl",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -392.48068651813566,
			"y": 2135.893013519007,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.68756672407176,
			"height": 10.383537891834294,
			"seed": 752075752,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947633811,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.038353789183418,
					0
				],
				[
					0,
					0
				],
				[
					1.0383537891834749,
					0
				],
				[
					3.1150613675503678,
					0
				],
				[
					4.153415156733843,
					-1.0383537891834749
				],
				[
					5.191768945917261,
					-2.0767075783669497
				],
				[
					6.230122735100679,
					-5.191768945917374
				],
				[
					7.268476524284154,
					-6.230122735100849
				],
				[
					7.268476524284154,
					-5.191768945917374
				],
				[
					6.230122735100679,
					-2.0767075783669497
				],
				[
					6.230122735100679,
					0
				],
				[
					8.306830313467628,
					2.076707578366495
				],
				[
					9.345184102651046,
					2.076707578366495
				],
				[
					11.42189168101794,
					1.0383537891834749
				],
				[
					12.460245470201414,
					-2.0767075783669497
				],
				[
					12.460245470201414,
					-4.1534151567338995
				],
				[
					12.460245470201414,
					-5.191768945917374
				],
				[
					13.49859925938489,
					-2.0767075783669497
				],
				[
					14.536953048568307,
					-1.0383537891834749
				],
				[
					16.6136606269352,
					1.0383537891834749
				],
				[
					18.690368205302093,
					1.0383537891834749
				],
				[
					20.767075783668986,
					1.0383537891834749
				],
				[
					21.80542957285246,
					-2.0767075783669497
				],
				[
					21.80542957285246,
					-5.191768945917374
				],
				[
					21.80542957285246,
					-7.268476524284324
				],
				[
					21.80542957285246,
					-8.306830313467799
				],
				[
					21.80542957285246,
					-7.268476524284324
				],
				[
					21.80542957285246,
					-5.191768945917374
				],
				[
					21.80542957285246,
					-3.1150613675504246
				],
				[
					22.84378336203588,
					-1.0383537891834749
				],
				[
					23.882137151219354,
					-1.0383537891834749
				],
				[
					25.958844729586247,
					-1.0383537891834749
				],
				[
					26.997198518769665,
					-3.1150613675504246
				],
				[
					28.03555230795314,
					-5.191768945917374
				],
				[
					29.073906097136614,
					-6.230122735100849
				],
				[
					30.112259886320032,
					-6.230122735100849
				],
				[
					30.112259886320032,
					-5.191768945917374
				],
				[
					30.112259886320032,
					-3.1150613675504246
				],
				[
					30.112259886320032,
					-2.0767075783669497
				],
				[
					31.150613675503507,
					-1.0383537891834749
				],
				[
					31.150613675503507,
					-2.0767075783669497
				],
				[
					32.188967464686925,
					-4.1534151567338995
				],
				[
					34.26567504305382,
					-6.230122735100849
				],
				[
					35.30402883223729,
					-8.306830313467799
				],
				[
					36.34238262142071,
					-8.306830313467799
				],
				[
					37.380736410604186,
					-6.230122735100849
				],
				[
					37.380736410604186,
					-3.1150613675504246
				],
				[
					39.45744398897108,
					-2.0767075783669497
				],
				[
					42.57250535652145,
					-2.0767075783669497
				],
				[
					44.64921293488834,
					-4.1534151567338995
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09939727932214737,
				0.10798278450965881,
				0.11514199525117874,
				0.12451190501451492,
				0.13331586122512817,
				0.17469522356987,
				0.19807864725589752,
				0.20833037793636322,
				0.18049630522727966,
				0.14079901576042175,
				0.09537433087825775,
				0.08368908613920212,
				0.07442449778318405,
				0.10572726279497147,
				0.1461518555879593,
				0.1651672124862671,
				0.11947088688611984,
				0.10475277900695801,
				0.09818960726261139,
				0.10119381546974182,
				0.10665905475616455,
				0.12278664857149124,
				0.1493162214756012,
				0.16870279610157013,
				0.18428723514080048,
				0.19736844301223755,
				0.1767018437385559,
				0.12770193815231323,
				0.10252444446086884,
				0.0921829491853714,
				0.09304782003164291,
				0.10160134732723236,
				0.12578772008419037,
				0.13398431241512299,
				0.13464972376823425,
				0.13204693794250488,
				0.12546947598457336,
				0.09672150015830994,
				0.08882647752761841,
				0.09459967166185379,
				0.1133524477481842,
				0.13679079711437225,
				0.16056610643863678,
				0.18396618962287903,
				0.1671445667743683,
				0.12349102646112442,
				0.04775036498904228,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 133718680,
			"isDeleted": false,
			"id": "ipxdTke0-GxKexI0tiphR",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -337.44793569141285,
			"y": 2125.5094756271724,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.72872199448551,
			"height": 13.498599259385173,
			"seed": 1487319528,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947634395,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					-1.038353789183418,
					-2.0767075783669497
				],
				[
					-3.115061367550311,
					-2.0767075783669497
				],
				[
					-4.153415156733786,
					-1.0383537891834749
				],
				[
					-6.230122735100679,
					1.0383537891834749
				],
				[
					-6.230122735100679,
					6.230122735100849
				],
				[
					-4.153415156733786,
					8.306830313467799
				],
				[
					0,
					9.345184102651274
				],
				[
					4.153415156733786,
					9.345184102651274
				],
				[
					6.2301227351007356,
					7.268476524284324
				],
				[
					8.306830313467628,
					4.1534151567338995
				],
				[
					8.306830313467628,
					1.0383537891834749
				],
				[
					6.2301227351007356,
					0
				],
				[
					4.153415156733786,
					0
				],
				[
					2.076707578366893,
					2.0767075783669497
				],
				[
					1.0383537891834749,
					6.230122735100849
				],
				[
					2.076707578366893,
					9.345184102651274
				],
				[
					7.268476524284154,
					11.421891681018224
				],
				[
					12.460245470201414,
					11.421891681018224
				],
				[
					13.498599259384832,
					10.383537891834749
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.07579336315393448,
				0.18252630531787872,
				0.20370538532733917,
				0.20493191480636597,
				0.19511838257312775,
				0.1767580211162567,
				0.1511889398097992,
				0.11818990856409073,
				0.10330990701913834,
				0.10811770707368851,
				0.12988458573818207,
				0.17175094783306122,
				0.20513802766799927,
				0.22680896520614624,
				0.25375550985336304,
				0.2604990601539612,
				0.1609007567167282,
				0.028206879273056984,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 5,
			"versionNonce": 1609898216,
			"isDeleted": false,
			"id": "mBmAfkzVVhV-B-ozSctZy",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -310.45073717264313,
			"y": 2122.394414259622,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.0383537891834749,
			"height": 0,
			"seed": 1546040040,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947634554,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.0383537891834749,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.14640799164772034,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 3,
			"versionNonce": 457594520,
			"isDeleted": false,
			"id": "N7HuJo-vtOsPtRQB_fp58",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -311.4890909618266,
			"y": 2130.7012445730898,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 406014360,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947634668,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.0001,
					0.0001
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1013710056,
			"isDeleted": false,
			"id": "338XY79GU0z3HGKfQ0wnn",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -463.0887441826102,
			"y": 2251.1502841183697,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.80542957285246,
			"height": 22.843783362035538,
			"seed": 1675755240,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947646377,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.0383537891834749
				],
				[
					0,
					2.0767075783669497
				],
				[
					0,
					3.1150613675504246
				],
				[
					1.0383537891834749,
					2.0767075783669497
				],
				[
					1.0383537891834749,
					0
				],
				[
					1.0383537891834749,
					-2.076707578366495
				],
				[
					0,
					-3.11506136754997
				],
				[
					-2.076707578366893,
					-4.153415156733445
				],
				[
					-5.191768945917261,
					-4.153415156733445
				],
				[
					-7.268476524284154,
					-3.11506136754997
				],
				[
					-9.345184102651046,
					-1.0383537891834749
				],
				[
					-11.42189168101794,
					3.1150613675504246
				],
				[
					-11.42189168101794,
					7.268476524284324
				],
				[
					-10.383537891834521,
					12.460245470201698
				],
				[
					-6.2301227351007356,
					16.613660626935143
				],
				[
					-2.076707578366893,
					17.652014416119073
				],
				[
					5.191768945917261,
					18.690368205302093
				],
				[
					9.345184102651046,
					17.652014416119073
				],
				[
					10.383537891834521,
					16.613660626935143
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06895379722118378,
				0.06710739433765411,
				0.10564257949590683,
				0.215316042304039,
				0.233158141374588,
				0.23844021558761597,
				0.23576214909553528,
				0.23013125360012054,
				0.22180166840553284,
				0.22260290384292603,
				0.22068142890930176,
				0.2157069444656372,
				0.2113671600818634,
				0.2052556425333023,
				0.1901460587978363,
				0.18027709424495697,
				0.0652463361620903,
				0.0051141660660505295,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 1957270424,
			"isDeleted": false,
			"id": "oiTACW2gSbRQz3MVLdh5D",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -445.43672976649157,
			"y": 2248.0352227508197,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.2301227351007356,
			"height": 21.805429572852518,
			"seed": 235709848,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947647251,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					1.0383537891834749,
					-2.0767075783669497
				],
				[
					1.0383537891834749,
					-3.1150613675504246
				],
				[
					1.0383537891834749,
					-2.0767075783669497
				],
				[
					1.0383537891834749,
					0
				],
				[
					-1.0383537891834749,
					5.19176894591692
				],
				[
					-3.115061367550311,
					10.383537891834294
				],
				[
					-4.153415156733786,
					14.536953048568193
				],
				[
					-5.191768945917261,
					17.652014416118618
				],
				[
					-5.191768945917261,
					18.690368205302093
				],
				[
					-5.191768945917261,
					17.652014416118618
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07199297845363617,
				0.07998599112033844,
				0.09593356400728226,
				0.13276663422584534,
				0.13329195976257324,
				0.11836633086204529,
				0.09508877247571945,
				0.057754334062337875,
				0.022973326966166496,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 138150296,
			"isDeleted": false,
			"id": "CgZcOIG8f8OWgutY2mBFH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -444.3983759773081,
			"y": 2246.996868961636,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.42189168101794,
			"height": 17.652014416118618,
			"seed": 857543144,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947647517,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					1.0383537891834749,
					-3.1150613675504246
				],
				[
					2.076707578366893,
					-3.1150613675504246
				],
				[
					3.115061367550311,
					-3.1150613675504246
				],
				[
					5.191768945917261,
					0
				],
				[
					6.230122735100679,
					4.153415156733445
				],
				[
					8.306830313467572,
					8.306830313467344
				],
				[
					9.345184102651046,
					12.460245470201244
				],
				[
					11.42189168101794,
					14.536953048568193
				],
				[
					11.42189168101794,
					14.536953048568193
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.06714660674333572,
				0.09772082418203354,
				0.15005725622177124,
				0.17945098876953125,
				0.18470102548599243,
				0.16313683986663818,
				0.13608798384666443,
				0.079185850918293,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 2034398616,
			"isDeleted": false,
			"id": "Kp_ur_e3out-k4fBOOCUK",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -456.8586214475095,
			"y": 2253.2269916967366,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.882137151219354,
			"height": 1.0383537891834749,
			"seed": 716211176,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947647791,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					1.0383537891834749,
					-1.0383537891834749
				],
				[
					6.230122735100679,
					-1.0383537891834749
				],
				[
					13.49859925938489,
					0
				],
				[
					21.80542957285246,
					0
				],
				[
					23.882137151219354,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0973070040345192,
				0.11994198709726334,
				0.1045398861169815,
				0.050339020788669586,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 604894872,
			"isDeleted": false,
			"id": "A9vYU21ZdQgQdGDf1gLzG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -421.5545926152722,
			"y": 2245.9585151724527,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.076707578366893,
			"height": 15.575306837751668,
			"seed": 175853544,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947648163,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0383537891834749,
					0
				],
				[
					2.076707578366893,
					1.0383537891834749
				],
				[
					2.076707578366893,
					3.1150613675504246
				],
				[
					2.076707578366893,
					6.2301227351003945
				],
				[
					2.076707578366893,
					10.383537891834294
				],
				[
					2.076707578366893,
					13.498599259384719
				],
				[
					2.076707578366893,
					14.536953048568193
				],
				[
					2.076707578366893,
					15.575306837751668
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.001313995337113738,
				0.1561466008424759,
				0.15530093014240265,
				0.13781271874904633,
				0.0809185802936554,
				0.0269891656935215,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 1203693544,
			"isDeleted": false,
			"id": "SElfLXkZ_XFS2NDHUB1ZO",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -432.97648429629015,
			"y": 2244.9201613832693,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.72872199448551,
			"height": 2.0767075783669497,
			"seed": 1692688104,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947648450,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.076707578366893,
					0
				],
				[
					6.230122735100679,
					1.0383537891834749
				],
				[
					10.383537891834465,
					1.0383537891834749
				],
				[
					17.652014416118618,
					2.0767075783669497
				],
				[
					19.72872199448551,
					2.0767075783669497
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.10328903049230576,
				0.1166941225528717,
				0.11539199948310852,
				0.012274567037820816,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 240782488,
			"isDeleted": false,
			"id": "tTX2NKP8sPyBfVu6eXpS4",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -395.595747885686,
			"y": 2245.9585151724527,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.575306837751782,
			"height": 23.882137151219467,
			"seed": 1173482136,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947648900,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					1.0383537891834749,
					-2.0767075783669497
				],
				[
					1.0383537891834749,
					-3.1150613675504246
				],
				[
					1.0383537891834749,
					-4.1534151567338995
				],
				[
					0,
					-5.191768945917374
				],
				[
					-1.038353789183418,
					-6.230122735100849
				],
				[
					-4.153415156733786,
					-6.230122735100849
				],
				[
					-7.268476524284097,
					-6.230122735100849
				],
				[
					-9.345184102651046,
					-4.1534151567338995
				],
				[
					-11.421891681017883,
					-2.0767075783669497
				],
				[
					-12.460245470201357,
					3.1150613675504246
				],
				[
					-13.498599259384832,
					7.268476524283869
				],
				[
					-11.421891681017883,
					12.460245470201244
				],
				[
					-9.345184102651046,
					15.575306837751668
				],
				[
					-6.230122735100622,
					16.613660626935143
				],
				[
					-3.115061367550311,
					17.652014416118618
				],
				[
					0,
					16.613660626935143
				],
				[
					1.0383537891834749,
					14.536953048568193
				],
				[
					2.0767075783669497,
					13.498599259384719
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.06458935886621475,
				0.13542993366718292,
				0.179521843791008,
				0.1962374895811081,
				0.20304343104362488,
				0.21180960536003113,
				0.20710204541683197,
				0.19943155348300934,
				0.20390136539936066,
				0.19489608705043793,
				0.1907322108745575,
				0.17788207530975342,
				0.14637857675552368,
				0.10643310844898224,
				0.05219247564673424,
				0,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 127726824,
			"isDeleted": false,
			"id": "ypdkt5PBaxuK-JdeVKRVt",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -393.5190403073191,
			"y": 2257.3804068534705,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.0383537891834749,
			"height": 9.345184102651274,
			"seed": 629975272,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947649084,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					-1.0383537891834749,
					-1.0383537891834749
				],
				[
					-1.0383537891834749,
					0
				],
				[
					-1.0383537891834749,
					2.0767075783669497
				],
				[
					-1.0383537891834749,
					5.191768945917374
				],
				[
					0,
					7.268476524284324
				],
				[
					0,
					8.306830313467799
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09919799864292145,
				0.1616639941930771,
				0.18657401204109192,
				0.1837535947561264,
				0.13080023229122162,
				0.018475158140063286,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 1485960344,
			"isDeleted": false,
			"id": "X2G__B6VnKNyMZ7M-MM1q",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -400.7875168316032,
			"y": 2253.2269916967366,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.460245470201414,
			"height": 2.0767075783669497,
			"seed": 75967896,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947649413,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					3.1150613675503678,
					0
				],
				[
					6.230122735100679,
					1.0383537891834749
				],
				[
					11.42189168101794,
					1.0383537891834749
				],
				[
					12.460245470201414,
					1.0383537891834749
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08245999366044998,
				0.12610067427158356,
				0.08590951561927795,
				0.010556274093687534,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1157214184,
			"isDeleted": false,
			"id": "PyeFCPd-hB9ONu4SVouxp",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -371.71361073446667,
			"y": 2244.9201613832693,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.268476524284097,
			"height": 19.728721994485568,
			"seed": 690438376,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947649710,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					0,
					0
				],
				[
					-1.038353789183418,
					3.1150613675504246
				],
				[
					-3.115061367550311,
					8.306830313467344
				],
				[
					-5.191768945917261,
					13.498599259384719
				],
				[
					-7.268476524284097,
					17.652014416118618
				],
				[
					-7.268476524284097,
					18.690368205302093
				],
				[
					-7.268476524284097,
					17.652014416118618
				],
				[
					-6.230122735100679,
					16.613660626935143
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.1713479906320572,
				0.16018179059028625,
				0.1434667408466339,
				0.10802816599607468,
				0.052139222621917725,
				0,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 15,
			"versionNonce": 1705835928,
			"isDeleted": false,
			"id": "7LKdnkNmc6qFUC-sZgwma",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -374.828672102017,
			"y": 2249.073576540003,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.34518410265099,
			"height": 18.690368205302093,
			"seed": 1688707736,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947649967,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.038353789183418,
					-2.0767075783669497
				],
				[
					1.038353789183418,
					-3.1150613675504246
				],
				[
					2.076707578366893,
					-3.1150613675504246
				],
				[
					3.115061367550311,
					-2.0767075783669497
				],
				[
					4.153415156733786,
					1.0383537891830201
				],
				[
					6.230122735100679,
					4.153415156733445
				],
				[
					7.268476524284097,
					8.306830313467344
				],
				[
					8.306830313467572,
					12.460245470201244
				],
				[
					9.34518410265099,
					14.536953048568193
				],
				[
					9.34518410265099,
					15.575306837751668
				],
				[
					8.306830313467572,
					14.536953048568193
				],
				[
					6.230122735100679,
					11.421891681017769
				],
				[
					5.191768945917204,
					10.383537891834294
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.03999999910593033,
				0.04682397469878197,
				0.12467199563980103,
				0.17017099261283875,
				0.20803198218345642,
				0.22275198996067047,
				0.2082827091217041,
				0.14210332930088043,
				0.04359515383839607,
				0,
				0,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1424195224,
			"isDeleted": false,
			"id": "lFtESjUanFwd8mm6N-rq8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -383.1355024154846,
			"y": 2250.111930329186,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.958844729586247,
			"height": 2.076707578366495,
			"seed": 1440565224,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947650176,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.038353789183418,
					0
				],
				[
					-2.076707578366893,
					0
				],
				[
					0,
					-1.0383537891830201
				],
				[
					3.1150613675503678,
					0
				],
				[
					9.345184102651046,
					0
				],
				[
					17.652014416118618,
					1.0383537891834749
				],
				[
					21.80542957285246,
					1.0383537891834749
				],
				[
					23.882137151219354,
					1.0383537891834749
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.07999999821186066,
				0.11733193695545197,
				0.13021017611026764,
				0.11518573015928268,
				0.0610358901321888,
				0.01573309302330017,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 2093591704,
			"isDeleted": false,
			"id": "1pTJ0T7186BklkSwlCKQn",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -347.8314735832473,
			"y": 2243.881807594086,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.038353789183418,
			"height": 20.767075783669043,
			"seed": 2081117928,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947650762,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.0767075783669497
				],
				[
					0,
					-3.1150613675504246
				],
				[
					1.038353789183418,
					-4.1534151567338995
				],
				[
					1.038353789183418,
					-3.1150613675504246
				],
				[
					1.038353789183418,
					0
				],
				[
					1.038353789183418,
					6.2301227351003945
				],
				[
					1.038353789183418,
					10.383537891834294
				],
				[
					1.038353789183418,
					14.536953048568193
				],
				[
					1.038353789183418,
					16.613660626935143
				],
				[
					1.038353789183418,
					16.613660626935143
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.05592086911201477,
				0.07540896534919739,
				0.1274503469467163,
				0.1465729922056198,
				0.1228981614112854,
				0.07941155880689621,
				0.024401184171438217,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 1076011160,
			"isDeleted": false,
			"id": "LWK5T8OazxrWVs5C4vA22",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -358.21501147508184,
			"y": 2240.7667462265354,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.92049094040277,
			"height": 2.0767075783669497,
			"seed": 1332152552,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947651028,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					2.076707578366893,
					-1.0383537891834749
				],
				[
					10.383537891834521,
					-1.0383537891834749
				],
				[
					18.690368205302093,
					-1.0383537891834749
				],
				[
					23.882137151219354,
					-1.0383537891834749
				],
				[
					24.92049094040277,
					-2.0767075783669497
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05916998162865639,
				0.09420397877693176,
				0.11552990972995758,
				0.09409792721271515,
				0.029826782643795013,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 178364648,
			"isDeleted": false,
			"id": "Vtwh551ZIlK9gC6JXAWBV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -321.87262885366107,
			"y": 2238.6900386481684,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 20.767075783669043,
			"seed": 1095193832,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947651511,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.0767075783669497
				],
				[
					0,
					-1.0383537891834749
				],
				[
					0,
					2.0767075783669497
				],
				[
					0,
					10.383537891834749
				],
				[
					0,
					15.575306837751668
				],
				[
					0,
					18.690368205302093
				],
				[
					0,
					18.690368205302093
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.08360598981380463,
				0.17459799349308014,
				0.17571692168712616,
				0.172090545296669,
				0.10139044374227524,
				0.038180235773324966,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 511044840,
			"isDeleted": false,
			"id": "GD8MR7pyT3UVkOWMzHFtZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -333.29452053467907,
			"y": 2239.728392437352,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.80542957285246,
			"height": 0,
			"seed": 577978776,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947651761,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0383537891834749,
					0
				],
				[
					2.0767075783669497,
					0
				],
				[
					7.268476524284154,
					0
				],
				[
					12.460245470201414,
					0
				],
				[
					19.728721994485568,
					0
				],
				[
					21.80542957285246,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.10416799783706665,
				0.09380736947059631,
				0.10389495640993118,
				0.04732104390859604,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 1651056360,
			"isDeleted": false,
			"id": "G6l-5nKyZc9YyS4thr7Ro",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -300.06719928080867,
			"y": 2241.805100015719,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9.345184102651046,
			"height": 20.767075783669043,
			"seed": 500807064,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947652378,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0383537891834749
				],
				[
					1.0383537891834749,
					-2.0767075783669497
				],
				[
					0,
					-1.0383537891834749
				],
				[
					-1.0383537891834749,
					2.0767075783669497
				],
				[
					-2.076707578366893,
					6.230122735100849
				],
				[
					-5.191768945917261,
					11.421891681017769
				],
				[
					-7.268476524284154,
					16.613660626935143
				],
				[
					-8.306830313467572,
					18.690368205302093
				],
				[
					-7.268476524284154,
					17.652014416118618
				],
				[
					-7.268476524284154,
					16.613660626935143
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.059870485216379166,
				0.08576315641403198,
				0.11717984080314636,
				0.12004513293504715,
				0.12198120355606079,
				0.0783587321639061,
				0.03537353500723839,
				0,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 519115160,
			"isDeleted": false,
			"id": "-OyAtFVkdvT4U_s9CyJ1z",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -302.14390685917556,
			"y": 2245.9585151724527,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.383537891834465,
			"height": 18.690368205302093,
			"seed": 728408984,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947652616,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.0767075783669497
				],
				[
					1.038353789183418,
					-3.1150613675504246
				],
				[
					2.076707578366893,
					-3.1150613675504246
				],
				[
					3.1150613675503678,
					-3.1150613675504246
				],
				[
					5.191768945917261,
					1.0383537891834749
				],
				[
					7.268476524284154,
					6.2301227351003945
				],
				[
					8.306830313467572,
					10.383537891834294
				],
				[
					9.345184102651046,
					13.498599259384719
				],
				[
					10.383537891834465,
					14.536953048568193
				],
				[
					10.383537891834465,
					15.575306837751668
				],
				[
					9.345184102651046,
					14.536953048568193
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0922829881310463,
				0.11320327967405319,
				0.13689148426055908,
				0.16466152667999268,
				0.15862765908241272,
				0.15502780675888062,
				0.11449691653251648,
				0.05647833272814751,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 1156547992,
			"isDeleted": false,
			"id": "tFuZRqbHZUEbEygNEduA-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -311.4890909618266,
			"y": 2253.2269916967366,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.997198518769665,
			"height": 1.0383537891834749,
			"seed": 1368683496,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947652867,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0383537891834749,
					-1.0383537891834749
				],
				[
					5.191768945917261,
					-1.0383537891834749
				],
				[
					11.42189168101794,
					-1.0383537891834749
				],
				[
					18.690368205302093,
					-1.0383537891834749
				],
				[
					25.958844729586247,
					-1.0383537891834749
				],
				[
					26.997198518769665,
					-1.0383537891834749
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.07959100604057312,
				0.07048410177230835,
				0.03166519105434418,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 819613416,
			"isDeleted": false,
			"id": "0soCHwfOyUisfCsU0vvwE",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -275.1467083404059,
			"y": 2240.7667462265354,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.038353789183418,
			"height": 18.690368205302093,
			"seed": 1743208424,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947653433,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.038353789183418,
					-1.0383537891834749
				],
				[
					-1.038353789183418,
					1.0383537891834749
				],
				[
					-1.038353789183418,
					3.1150613675504246
				],
				[
					-1.038353789183418,
					7.268476524284324
				],
				[
					-1.038353789183418,
					11.421891681017769
				],
				[
					-1.038353789183418,
					15.575306837751668
				],
				[
					-1.038353789183418,
					17.652014416118618
				],
				[
					-1.038353789183418,
					16.613660626935143
				],
				[
					-1.038353789183418,
					15.575306837751668
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06859628111124039,
				0.08965405076742172,
				0.09463177621364594,
				0.09609921276569366,
				0.09174524247646332,
				0.08744674921035767,
				0.05013812333345413,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 606201752,
			"isDeleted": false,
			"id": "8YquXjLWNTV3C0nBIogOX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -288.6453075997907,
			"y": 2242.8434538049023,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.03555230795314,
			"height": 2.0767075783669497,
			"seed": 467956632,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947653744,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.076707578366893,
					0
				],
				[
					5.191768945917261,
					0
				],
				[
					9.345184102651046,
					-1.0383537891834749
				],
				[
					15.575306837751725,
					-1.0383537891834749
				],
				[
					21.80542957285246,
					-2.0767075783669497
				],
				[
					25.958844729586247,
					-2.0767075783669497
				],
				[
					28.03555230795314,
					-2.0767075783669497
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.02678598091006279,
				0.08784280717372894,
				0.10915689170360565,
				0.11590561270713806,
				0.10281134396791458,
				0.056180939078330994,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 41,
			"versionNonce": 746387944,
			"isDeleted": false,
			"id": "FyDNEhfbcrfaU-44WaBbD",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -897.5525740297096,
			"y": 2449.852989138645,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 52.757186819960225,
			"height": 23.825826305788723,
			"seed": 352583144,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947796090,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					0,
					-3.4036894722557918
				],
				[
					0,
					-1.7018447361278959
				],
				[
					1.7018447361277822,
					3.403689472255337
				],
				[
					1.7018447361277822,
					10.211068416766466
				],
				[
					1.7018447361277822,
					17.01844736127714
				],
				[
					3.4036894722555644,
					20.42213683353293
				],
				[
					5.105534208383233,
					20.42213683353293
				],
				[
					6.807378944511015,
					18.720292097405036
				],
				[
					8.509223680638797,
					13.614757889021803
				],
				[
					10.211068416766466,
					8.50922368063857
				],
				[
					11.912913152894362,
					5.105534208383233
				],
				[
					13.61475788902203,
					1.7018447361274411
				],
				[
					15.316602625149812,
					1.7018447361274411
				],
				[
					18.720292097405263,
					1.7018447361274411
				],
				[
					20.422136833533045,
					6.807378944510674
				],
				[
					20.422136833533045,
					10.211068416766466
				],
				[
					22.123981569660828,
					15.316602625149699
				],
				[
					22.123981569660828,
					17.01844736127714
				],
				[
					22.123981569660828,
					15.316602625149699
				],
				[
					22.123981569660828,
					10.211068416766466
				],
				[
					22.123981569660828,
					5.105534208383233
				],
				[
					23.825826305788496,
					1.7018447361274411
				],
				[
					27.22951577804406,
					-1.7018447361278959
				],
				[
					28.93136051417173,
					-1.7018447361278959
				],
				[
					34.03689472255496,
					3.403689472255337
				],
				[
					35.73873945868286,
					8.50922368063857
				],
				[
					35.73873945868286,
					13.614757889021803
				],
				[
					35.73873945868286,
					17.01844736127714
				],
				[
					35.73873945868286,
					15.316602625149699
				],
				[
					35.73873945868286,
					10.211068416766466
				],
				[
					35.73873945868286,
					5.105534208383233
				],
				[
					35.73873945868286,
					3.403689472255337
				],
				[
					39.14242893093831,
					-1.7018447361278959
				],
				[
					44.24796313932154,
					-1.7018447361278959
				],
				[
					47.65165261157699,
					1.7018447361274411
				],
				[
					51.05534208383256,
					6.807378944510674
				],
				[
					52.757186819960225,
					15.316602625149699
				],
				[
					52.757186819960225,
					17.01844736127714
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.01818154938519001,
				0.07285436987876892,
				0.07405435293912888,
				0.0771438330411911,
				0.05961993336677551,
				0.04830920323729515,
				0.04713287204504013,
				0.049463897943496704,
				0.053513914346694946,
				0.06498397886753082,
				0.07624936103820801,
				0.0883641391992569,
				0.0929999053478241,
				0.0954689309000969,
				0.07277969270944595,
				0.05942321941256523,
				0.030175384134054184,
				0.02198837324976921,
				0.046592194586992264,
				0.07328973710536957,
				0.09745334088802338,
				0.11090166866779327,
				0.10998733341693878,
				0.11796429753303528,
				0.1045796200633049,
				0.09009988605976105,
				0.06344882398843765,
				0.050196290016174316,
				0.0590585321187973,
				0.08384475857019424,
				0.10258364677429199,
				0.1099206879734993,
				0.12106329202651978,
				0.13696236908435822,
				0.13648168742656708,
				0.13150568306446075,
				0.03361038118600845,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 546281880,
			"isDeleted": false,
			"id": "ZjIx7BrhgBjddkd1j05f9",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -836.2861635291106,
			"y": 2446.4492996663894,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.4036894722555644,
			"height": 37.440584194810526,
			"seed": 559282328,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947796574,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					0,
					-3.403689472255337
				],
				[
					0,
					0
				],
				[
					1.7018447361277822,
					6.807378944511129
				],
				[
					1.7018447361277822,
					15.316602625150153
				],
				[
					3.4036894722555644,
					22.123981569660828
				],
				[
					3.4036894722555644,
					28.931360514171956
				],
				[
					3.4036894722555644,
					34.03689472255519
				],
				[
					3.4036894722555644,
					34.03689472255519
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.05783483758568764,
				0.10190072655677795,
				0.10405880957841873,
				0.10554342716932297,
				0.08676598966121674,
				0.053036775439977646,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 189423080,
			"isDeleted": false,
			"id": "NNIaXWaq-Gf32A0fz7vNj",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -834.5843187929828,
			"y": 2448.1511444025173,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.614757889021917,
			"height": 20.422136833533386,
			"seed": 620915688,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947796866,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-3.4036894722557918
				],
				[
					0,
					-6.807378944511129
				],
				[
					3.4036894722554507,
					-6.807378944511129
				],
				[
					6.807378944511015,
					-5.105534208383233
				],
				[
					10.211068416766466,
					-1.7018447361278959
				],
				[
					11.912913152894248,
					1.7018447361278959
				],
				[
					13.614757889021917,
					6.807378944511129
				],
				[
					11.912913152894248,
					8.50922368063857
				],
				[
					6.807378944511015,
					11.912913152894362
				],
				[
					1.7018447361277822,
					11.912913152894362
				],
				[
					0,
					13.614757889022258
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.009999999776482582,
				0.09131283313035965,
				0.11541751027107239,
				0.1231464222073555,
				0.12589779496192932,
				0.11221767961978912,
				0.08228875696659088,
				0.04173693805932999,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 2076291224,
			"isDeleted": false,
			"id": "g9t5Ui3WXT8v85PF_Q1t-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -820.9695609039609,
			"y": 2426.0271628328564,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.123981569660828,
			"height": 39.14242893093842,
			"seed": 1803605144,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947797623,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.7018447361278959,
					-1.7018447361278959
				],
				[
					1.7018447361278959,
					-3.403689472255337
				],
				[
					1.7018447361278959,
					-1.7018447361278959
				],
				[
					1.7018447361278959,
					1.7018447361278959
				],
				[
					1.7018447361278959,
					6.807378944511129
				],
				[
					3.4036894722555644,
					13.614757889022258
				],
				[
					3.4036894722555644,
					22.123981569660828
				],
				[
					5.105534208383347,
					28.931360514171956
				],
				[
					8.509223680638797,
					32.33504998642729
				],
				[
					11.912913152894362,
					34.03689472255519
				],
				[
					13.61475788902203,
					34.03689472255519
				],
				[
					15.316602625149812,
					30.633205250299397
				],
				[
					15.316602625149812,
					27.22951577804406
				],
				[
					17.018447361277595,
					23.825826305788723
				],
				[
					17.018447361277595,
					20.42213683353293
				],
				[
					17.018447361277595,
					18.720292097405036
				],
				[
					17.018447361277595,
					17.018447361277595
				],
				[
					17.018447361277595,
					20.42213683353293
				],
				[
					17.018447361277595,
					25.527671041916165
				],
				[
					17.018447361277595,
					28.931360514171956
				],
				[
					18.720292097405263,
					34.03689472255519
				],
				[
					20.42213683353316,
					35.738739458683085
				],
				[
					22.123981569660828,
					35.738739458683085
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.0759979858994484,
				0.06455743312835693,
				0.08720706403255463,
				0.09004022181034088,
				0.0964498296380043,
				0.09065383672714233,
				0.07164642214775085,
				0.053647156804800034,
				0.03704483062028885,
				0.027441436424851418,
				0.026425445452332497,
				0.031235961243510246,
				0.05047164857387543,
				0.07002169638872147,
				0.0851999819278717,
				0.11314471065998077,
				0.13902993500232697,
				0.1896272599697113,
				0.19160082936286926,
				0.16901293396949768,
				0.12834280729293823,
				0.008371398784220219,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 5,
			"versionNonce": 515058408,
			"isDeleted": false,
			"id": "rhvA4_BOidfxNxiuISjvQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -798.8455793343,
			"y": 2427.7290075689843,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 1.7018447361278959,
			"seed": 1591821544,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947797771,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 5,
			"versionNonce": 1755861400,
			"isDeleted": false,
			"id": "dw1GW9tv_jRET5b1K8o2H",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -899.2544187658373,
			"y": 2426.0271628328564,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.7018447361277822,
			"height": 0,
			"seed": 966219672,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947798184,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.7018447361277822,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09222400188446045,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 16,
			"versionNonce": 2089499032,
			"isDeleted": false,
			"id": "9ic-rvFEEntNj2DgofRLZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -775.0197530285116,
			"y": 2453.2566786109005,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.018447361277595,
			"height": 20.42213683353293,
			"seed": 301020136,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947799122,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					0,
					-5.105534208383233
				],
				[
					-1.7018447361276685,
					-6.807378944511129
				],
				[
					-3.4036894722555644,
					-8.509223680639025
				],
				[
					-6.807378944511015,
					-10.211068416766466
				],
				[
					-10.211068416766466,
					-10.211068416766466
				],
				[
					-11.912913152894248,
					-6.807378944511129
				],
				[
					-13.61475788902203,
					-1.7018447361278959
				],
				[
					-13.61475788902203,
					3.403689472255337
				],
				[
					-11.912913152894248,
					8.509223680639025
				],
				[
					-6.807378944511015,
					10.211068416766466
				],
				[
					3.4036894722555644,
					10.211068416766466
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.0437956228852272,
				0.06653701514005661,
				0.0915379673242569,
				0.10338656604290009,
				0.11540182679891586,
				0.1257646232843399,
				0.12318117916584015,
				0.12298937886953354,
				0.11133383214473724,
				0.09232861548662186,
				0.0266108401119709,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 1342579352,
			"isDeleted": false,
			"id": "SbLEq5UPjhyTWj9vCROGv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -747.7902372504675,
			"y": 2448.1511444025173,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.52767104191628,
			"height": 17.01844736127805,
			"seed": 1343278056,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947799898,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					-3.4036894722555644,
					-1.7018447361278959
				],
				[
					-5.105534208383233,
					-3.4036894722557918
				],
				[
					-8.509223680638797,
					-3.4036894722557918
				],
				[
					-11.912913152894362,
					-3.4036894722557918
				],
				[
					-15.316602625149812,
					0
				],
				[
					-18.720292097405263,
					1.7018447361278959
				],
				[
					-20.422136833533045,
					6.807378944511129
				],
				[
					-20.422136833533045,
					10.211068416766466
				],
				[
					-17.018447361277595,
					11.912913152894362
				],
				[
					-13.61475788902203,
					13.614757889022258
				],
				[
					-8.509223680638797,
					13.614757889022258
				],
				[
					-5.105534208383233,
					11.912913152894362
				],
				[
					-3.4036894722555644,
					10.211068416766466
				],
				[
					-1.7018447361277822,
					8.50922368063857
				],
				[
					-1.7018447361277822,
					5.105534208383233
				],
				[
					-1.7018447361277822,
					1.7018447361278959
				],
				[
					-1.7018447361277822,
					0
				],
				[
					-1.7018447361277822,
					3.403689472255337
				],
				[
					-1.7018447361277822,
					6.807378944511129
				],
				[
					-1.7018447361277822,
					10.211068416766466
				],
				[
					0,
					13.614757889022258
				],
				[
					3.4036894722554507,
					13.614757889022258
				],
				[
					5.105534208383233,
					13.614757889022258
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.022423645481467247,
				0.06248123198747635,
				0.08335775882005692,
				0.09849350154399872,
				0.11175058037042618,
				0.12015140056610107,
				0.12037322670221329,
				0.11739346385002136,
				0.1152041032910347,
				0.08514010906219482,
				0.06474991142749786,
				0.0491713248193264,
				0.04478408768773079,
				0.04846109077334404,
				0.06301794201135635,
				0.09111548215150833,
				0.11329888552427292,
				0.14774596691131592,
				0.16285467147827148,
				0.1607334315776825,
				0.14439187943935394,
				0.09820336848497391,
				0.017657745629549026,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 7,
			"versionNonce": 50854888,
			"isDeleted": false,
			"id": "-BxcEBzZSo3ZPavx93oys",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -729.0699451530622,
			"y": 2434.536386513495,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.7018447361278959,
			"height": 23.82582630578827,
			"seed": 886371048,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947800275,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361274411
				],
				[
					0,
					10.211068416766466
				],
				[
					0,
					15.316602625150153
				],
				[
					0,
					20.422136833533386
				],
				[
					-1.7018447361278959,
					22.123981569660828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.08984255790710449,
				0.044136229902505875,
				0.012101653963327408,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 1988230808,
			"isDeleted": false,
			"id": "ckqQWnZIo_5e-7Wj3yC0r",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -739.2810135698288,
			"y": 2444.7474549302615,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.825826305788496,
			"height": 15.316602625149699,
			"seed": 242488984,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947800665,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.7018447361277822,
					0
				],
				[
					3.4036894722554507,
					0
				],
				[
					6.807378944511015,
					-1.7018447361274411
				],
				[
					11.912913152894248,
					-1.7018447361274411
				],
				[
					15.316602625149812,
					-1.7018447361274411
				],
				[
					20.422136833533045,
					-1.7018447361274411
				],
				[
					22.123981569660714,
					-1.7018447361274411
				],
				[
					23.825826305788496,
					-1.7018447361274411
				],
				[
					23.825826305788496,
					0
				],
				[
					23.825826305788496,
					3.4036894722557918
				],
				[
					23.825826305788496,
					6.807378944511129
				],
				[
					22.123981569660714,
					10.21106841676692
				],
				[
					22.123981569660714,
					11.912913152894362
				],
				[
					22.123981569660714,
					13.614757889022258
				],
				[
					22.123981569660714,
					13.614757889022258
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.05535809323191643,
				0.056731536984443665,
				0.060582488775253296,
				0.06364889442920685,
				0.06759292632341385,
				0.07846609503030777,
				0.0901774913072586,
				0.13365747034549713,
				0.14000433683395386,
				0.13502545654773712,
				0.11001840233802795,
				0.03519262745976448,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 6,
			"versionNonce": 290612632,
			"isDeleted": false,
			"id": "Q57xBYj7pSa1bs92SxqBI",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -713.7533425279125,
			"y": 2432.8345417773676,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.7018447361276685,
			"height": 3.403689472255337,
			"seed": 697620200,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947800830,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-3.403689472255337
				],
				[
					1.7018447361276685,
					-3.403689472255337
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.047043975442647934,
				0.000978973344899714,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 40,
			"versionNonce": 2018814360,
			"isDeleted": false,
			"id": "XHmT7lBcCSRrAHPuvD6WA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -693.3312056943796,
			"y": 2446.4492996663894,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.94980787544932,
			"height": 18.72029209740549,
			"seed": 799170536,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947801781,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					-1.7018447361276685,
					-1.7018447361278959
				],
				[
					-3.4036894722554507,
					-1.7018447361278959
				],
				[
					-5.105534208383233,
					-1.7018447361278959
				],
				[
					-6.807378944510901,
					-1.7018447361278959
				],
				[
					-8.509223680638684,
					0
				],
				[
					-10.211068416766466,
					3.4036894722557918
				],
				[
					-10.211068416766466,
					8.509223680639025
				],
				[
					-10.211068416766466,
					11.912913152894362
				],
				[
					-5.105534208383233,
					17.018447361277595
				],
				[
					-3.4036894722554507,
					17.018447361277595
				],
				[
					-1.7018447361276685,
					17.018447361277595
				],
				[
					-1.7018447361276685,
					13.614757889022258
				],
				[
					-1.7018447361276685,
					10.211068416766466
				],
				[
					-1.7018447361276685,
					6.807378944511129
				],
				[
					-1.7018447361276685,
					3.4036894722557918
				],
				[
					0,
					1.7018447361278959
				],
				[
					1.7018447361277822,
					0
				],
				[
					5.105534208383233,
					-1.7018447361278959
				],
				[
					10.21106841676658,
					-1.7018447361278959
				],
				[
					13.61475788902203,
					1.7018447361278959
				],
				[
					17.018447361277595,
					6.807378944511129
				],
				[
					18.720292097405263,
					10.211068416766466
				],
				[
					18.720292097405263,
					13.614757889022258
				],
				[
					18.720292097405263,
					15.316602625150153
				],
				[
					18.720292097405263,
					11.912913152894362
				],
				[
					18.720292097405263,
					6.807378944511129
				],
				[
					20.422136833533045,
					3.4036894722557918
				],
				[
					23.82582630578861,
					1.7018447361278959
				],
				[
					25.52767104191628,
					0
				],
				[
					28.931360514171843,
					0
				],
				[
					32.33504998642729,
					1.7018447361278959
				],
				[
					32.33504998642729,
					5.105534208383233
				],
				[
					32.33504998642729,
					8.509223680639025
				],
				[
					32.33504998642729,
					13.614757889022258
				],
				[
					34.036894722555076,
					15.316602625150153
				],
				[
					35.73873945868286,
					17.018447361277595
				],
				[
					35.73873945868286,
					17.018447361277595
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.05470956489443779,
				0.06637951731681824,
				0.09313973784446716,
				0.09897274523973465,
				0.10412179678678513,
				0.10646969825029373,
				0.10872860997915268,
				0.10005240142345428,
				0.0817829892039299,
				0.017257751896977425,
				0,
				0,
				0.013064239174127579,
				0.04201614484190941,
				0.09090075641870499,
				0.11710580438375473,
				0.13664068281650543,
				0.15260140597820282,
				0.15651367604732513,
				0.16196703910827637,
				0.15316353738307953,
				0.13606780767440796,
				0.11583825945854187,
				0.10094332695007324,
				0.09240725636482239,
				0.10986117273569107,
				0.1626328080892563,
				0.18458513915538788,
				0.2066493183374405,
				0.21825149655342102,
				0.227660670876503,
				0.23790720105171204,
				0.24324777722358704,
				0.24344925582408905,
				0.14651180803775787,
				0.04664819315075874,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 825702120,
			"isDeleted": false,
			"id": "OqCn1YZcna92z-kPwPF_f",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -638.8721741382916,
			"y": 2444.7474549302615,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.912913152894248,
			"height": 28.9313605141715,
			"seed": 1674992616,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947802347,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-3.403689472255337
				],
				[
					0,
					-5.105534208382778
				],
				[
					-1.7018447361276685,
					-6.807378944510674
				],
				[
					-5.105534208383233,
					-6.807378944510674
				],
				[
					-6.807378944510901,
					-6.807378944510674
				],
				[
					-8.509223680638684,
					-3.403689472255337
				],
				[
					-8.509223680638684,
					0
				],
				[
					-6.807378944510901,
					5.105534208383688
				],
				[
					-1.7018447361276685,
					10.21106841676692
				],
				[
					0,
					15.316602625150153
				],
				[
					1.7018447361277822,
					18.72029209740549
				],
				[
					0,
					20.422136833533386
				],
				[
					-3.4036894722554507,
					22.123981569660828
				],
				[
					-8.509223680638684,
					22.123981569660828
				],
				[
					-10.211068416766466,
					18.72029209740549
				],
				[
					-10.211068416766466,
					17.01844736127805
				],
				[
					-10.211068416766466,
					15.316602625150153
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07992798089981079,
				0.09796398878097534,
				0.1297139823436737,
				0.1377178579568863,
				0.14138592779636383,
				0.13857193291187286,
				0.13376131653785706,
				0.12668368220329285,
				0.1084303930401802,
				0.0863046869635582,
				0.08264819532632828,
				0.09517709165811539,
				0.10337036103010178,
				0.09855224937200546,
				0.06004370003938675,
				0.02148260548710823,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 5,
			"versionNonce": 320734616,
			"isDeleted": false,
			"id": "bXBwwDaGe34S_neQahYZ-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -618.4500373047586,
			"y": 2441.343765458006,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 1.7018447361274411,
			"seed": 170527640,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947802581,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361274411
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 5,
			"versionNonce": 911205864,
			"isDeleted": false,
			"id": "CK--6mhlVd3EEURca7zs6",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -618.4500373047586,
			"y": 2458.3622128192837,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.7018447361277822,
			"height": 0,
			"seed": 971030504,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947802723,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.7018447361277822,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.13809798657894135,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 27,
			"versionNonce": 2140394904,
			"isDeleted": false,
			"id": "RtRahmitdh8Wkkuj8bvtU",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -555.4817820680317,
			"y": 2441.343765458006,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.33504998642718,
			"height": 42.54611840319376,
			"seed": 58182808,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947807297,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.7018447361277822,
					-1.7018447361274411
				],
				[
					-1.7018447361277822,
					-3.403689472255337
				],
				[
					1.7018447361276685,
					-6.807378944511129
				],
				[
					6.807378944511015,
					-10.211068416766466
				],
				[
					11.912913152894248,
					-10.211068416766466
				],
				[
					15.316602625149699,
					-5.105534208383233
				],
				[
					15.316602625149699,
					1.7018447361278959
				],
				[
					13.614757889021917,
					8.509223680639025
				],
				[
					10.211068416766466,
					13.614757889022258
				],
				[
					5.105534208383233,
					15.316602625149699
				],
				[
					3.4036894722554507,
					17.018447361277595
				],
				[
					1.7018447361276685,
					15.316602625149699
				],
				[
					3.4036894722554507,
					13.614757889022258
				],
				[
					8.509223680638684,
					13.614757889022258
				],
				[
					15.316602625149699,
					13.614757889022258
				],
				[
					20.42213683353293,
					15.316602625149699
				],
				[
					25.527671041916165,
					18.72029209740549
				],
				[
					25.527671041916165,
					23.825826305788723
				],
				[
					23.825826305788496,
					27.22951577804406
				],
				[
					17.01844736127748,
					30.633205250299852
				],
				[
					11.912913152894248,
					32.33504998642729
				],
				[
					1.7018447361276685,
					32.33504998642729
				],
				[
					-3.4036894722555644,
					28.931360514171956
				],
				[
					-6.807378944511015,
					25.527671041916165
				],
				[
					-6.807378944511015,
					25.527671041916165
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.09701083600521088,
				0.12221746891736984,
				0.14771361649036407,
				0.16054092347621918,
				0.17104101181030273,
				0.16332541406154633,
				0.1326921135187149,
				0.10514876991510391,
				0.07909243553876877,
				0.07175955176353455,
				0.08309732377529144,
				0.09099731594324112,
				0.09863888472318649,
				0.11369112879037857,
				0.1147124320268631,
				0.11125235259532928,
				0.10100405663251877,
				0.09224441647529602,
				0.07687310874462128,
				0.07605712860822678,
				0.07038796693086624,
				0.08128216862678528,
				0.07216125726699829,
				0.01329086348414421,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 795913704,
			"isDeleted": false,
			"id": "2tifPPFFh1lQZANJKbqfh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -490.8116820951773,
			"y": 2439.6419207218787,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.33504998642729,
			"height": 42.54611840319376,
			"seed": 1416622056,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947807853,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					-1.7018447361277822,
					-3.4036894722557918
				],
				[
					-3.4036894722555644,
					-3.4036894722557918
				],
				[
					-6.807378944511015,
					-5.105534208383688
				],
				[
					-13.61475788902203,
					-5.105534208383688
				],
				[
					-20.422136833533045,
					-1.7018447361278959
				],
				[
					-27.22951577804406,
					5.105534208382778
				],
				[
					-30.63320525029951,
					17.01844736127714
				],
				[
					-28.93136051417173,
					28.9313605141715
				],
				[
					-23.825826305788496,
					35.73873945868263
				],
				[
					-15.316602625149812,
					37.44058419481007
				],
				[
					-8.509223680638797,
					35.73873945868263
				],
				[
					-3.4036894722555644,
					28.9313605141715
				],
				[
					0,
					20.42213683353293
				],
				[
					1.7018447361277822,
					11.912913152893907
				],
				[
					0,
					5.105534208382778
				],
				[
					-5.105534208383233,
					-1.7018447361278959
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07401498407125473,
				0.0830879807472229,
				0.09264645725488663,
				0.11979947239160538,
				0.13897378742694855,
				0.13588036596775055,
				0.1328936517238617,
				0.12701471149921417,
				0.11293798685073853,
				0.08682073652744293,
				0.04816076532006264,
				0.03236773610115051,
				0.03112231381237507,
				0.05412957817316055,
				0.11146154999732971,
				0.12662045657634735,
				0.05365832522511482,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 424966296,
			"isDeleted": false,
			"id": "FSzYDMiisZdjIR2XDPMY-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -478.898768942283,
			"y": 2460.0640575554116,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.316602625149699,
			"height": 23.825826305788723,
			"seed": 1067943064,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947808557,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					1.7018447361277822,
					-3.4036894722557918
				],
				[
					3.4036894722554507,
					-1.7018447361278959
				],
				[
					8.509223680638797,
					8.50922368063857
				],
				[
					11.912913152894248,
					13.614757889021803
				],
				[
					15.316602625149699,
					18.720292097405036
				],
				[
					15.316602625149699,
					20.42213683353293
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.08104940503835678,
				0.10643542557954788,
				0.11346758902072906,
				0.08128952234983444,
				0.005261657759547234,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 8,
			"versionNonce": 1256680600,
			"isDeleted": false,
			"id": "4qJOunJDloD78A0EGfKIW",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -482.3024584145385,
			"y": 2475.3806601805613,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 37.44058419481041,
			"height": 25.527671041916165,
			"seed": 784268520,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947808815,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.7018447361276685,
					0
				],
				[
					3.4036894722554507,
					0
				],
				[
					8.509223680638684,
					-5.105534208383233
				],
				[
					22.123981569660714,
					-15.316602625149699
				],
				[
					32.33504998642718,
					-22.123981569660828
				],
				[
					37.44058419481041,
					-25.527671041916165
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.09088198840618134,
				0.08981045335531235,
				0.05857153236865997,
				0.014817383140325546,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 174757864,
			"isDeleted": false,
			"id": "edGWBb4gO6qYwL0GrPw1m",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -366.57701635785156,
			"y": 2468.57328123605,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.52767104191628,
			"height": 27.229515778043606,
			"seed": 668401640,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947824713,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.7018447361277822,
					-1.7018447361278959
				],
				[
					1.7018447361277822,
					-3.403689472255337
				],
				[
					1.7018447361277822,
					-5.105534208383233
				],
				[
					1.7018447361277822,
					-6.807378944510674
				],
				[
					0,
					-8.50922368063857
				],
				[
					-3.4036894722554507,
					-8.50922368063857
				],
				[
					-6.807378944511015,
					-8.50922368063857
				],
				[
					-10.211068416766466,
					-5.105534208383233
				],
				[
					-13.614757889021917,
					-1.7018447361278959
				],
				[
					-15.316602625149699,
					5.105534208383233
				],
				[
					-13.614757889021917,
					13.614757889022258
				],
				[
					-8.509223680638684,
					18.720292097405036
				],
				[
					-1.7018447361276685,
					18.720292097405036
				],
				[
					8.509223680638797,
					17.018447361277595
				],
				[
					10.21106841676658,
					13.614757889022258
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07059274613857269,
				0.09676770120859146,
				0.11148190498352051,
				0.12413562089204788,
				0.13967947661876678,
				0.14319881796836853,
				0.142379492521286,
				0.1454528570175171,
				0.1463339477777481,
				0.148009791970253,
				0.1400064378976822,
				0.11859136819839478,
				0.08853235095739365,
				0.03473065048456192,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 40,
			"versionNonce": 1632801768,
			"isDeleted": false,
			"id": "LDeSQYzqwtW8o7Lu3W4-j",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -335.94381110755205,
			"y": 2468.57328123605,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.036894722555076,
			"height": 20.42213683353293,
			"seed": 421083800,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947825604,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.7018447361276685,
					-1.7018447361278959
				],
				[
					-3.4036894722554507,
					-1.7018447361278959
				],
				[
					-5.105534208383233,
					-1.7018447361278959
				],
				[
					-6.807378944511015,
					-1.7018447361278959
				],
				[
					-8.509223680638684,
					-1.7018447361278959
				],
				[
					-11.912913152894248,
					0
				],
				[
					-11.912913152894248,
					1.7018447361278959
				],
				[
					-13.61475788902203,
					5.105534208383233
				],
				[
					-13.61475788902203,
					8.50922368063857
				],
				[
					-13.61475788902203,
					13.614757889022258
				],
				[
					-13.61475788902203,
					15.316602625149699
				],
				[
					-10.211068416766466,
					17.018447361277595
				],
				[
					-6.807378944511015,
					17.018447361277595
				],
				[
					-5.105534208383233,
					17.018447361277595
				],
				[
					-1.7018447361276685,
					15.316602625149699
				],
				[
					0,
					13.614757889022258
				],
				[
					0,
					11.912913152894362
				],
				[
					0,
					8.50922368063857
				],
				[
					0,
					5.105534208383233
				],
				[
					-1.7018447361276685,
					1.7018447361278959
				],
				[
					-1.7018447361276685,
					-1.7018447361278959
				],
				[
					0,
					-3.403689472255337
				],
				[
					1.7018447361277822,
					-3.403689472255337
				],
				[
					3.4036894722555644,
					-1.7018447361278959
				],
				[
					5.105534208383233,
					0
				],
				[
					6.807378944511015,
					3.4036894722557918
				],
				[
					8.509223680638797,
					6.807378944511129
				],
				[
					10.21106841676658,
					10.211068416766466
				],
				[
					11.912913152894248,
					13.614757889022258
				],
				[
					13.61475788902203,
					13.614757889022258
				],
				[
					15.316602625149812,
					15.316602625149699
				],
				[
					17.01844736127748,
					13.614757889022258
				],
				[
					17.01844736127748,
					11.912913152894362
				],
				[
					18.720292097405263,
					8.50922368063857
				],
				[
					18.720292097405263,
					5.105534208383233
				],
				[
					20.422136833533045,
					1.7018447361278959
				],
				[
					20.422136833533045,
					-3.403689472255337
				],
				[
					20.422136833533045,
					-3.403689472255337
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.06844799965620041,
				0.057344451546669006,
				0.07666321098804474,
				0.09137951582670212,
				0.1027984619140625,
				0.09972845762968063,
				0.09790106117725372,
				0.0943407267332077,
				0.08879046887159348,
				0.08162716776132584,
				0.08020132780075073,
				0.06639489531517029,
				0.05857076868414879,
				0.05077151581645012,
				0.039301514625549316,
				0.03235534578561783,
				0.041587889194488525,
				0.04774929955601692,
				0.07164401561021805,
				0.10119152814149857,
				0.11588738858699799,
				0.1285787969827652,
				0.1287604719400406,
				0.1289607286453247,
				0.12448446452617645,
				0.11093167215585709,
				0.10993737727403641,
				0.09257809817790985,
				0.08592355251312256,
				0.08648977428674698,
				0.08931326121091843,
				0.09558090567588806,
				0.10973675549030304,
				0.1235097348690033,
				0.12328765541315079,
				0.08918676525354385,
				0.02375393733382225,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 58,
			"versionNonce": 812313320,
			"isDeleted": false,
			"id": "cejmKBCq7luj4YChtHr0T",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -305.31060585725254,
			"y": 2477.082504916689,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 61.26641050059902,
			"height": 15.316602625149699,
			"seed": 29294232,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947826810,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.7018447361277822,
					0
				],
				[
					-3.4036894722554507,
					0
				],
				[
					-1.7018447361277822,
					0
				],
				[
					1.7018447361277822,
					0
				],
				[
					3.4036894722555644,
					-1.7018447361274411
				],
				[
					5.105534208383233,
					-3.403689472255337
				],
				[
					5.105534208383233,
					-5.105534208382778
				],
				[
					5.105534208383233,
					-6.807378944510674
				],
				[
					3.4036894722555644,
					-6.807378944510674
				],
				[
					1.7018447361277822,
					-6.807378944510674
				],
				[
					-1.7018447361277822,
					-6.807378944510674
				],
				[
					-3.4036894722554507,
					-5.105534208382778
				],
				[
					-5.105534208383233,
					-3.403689472255337
				],
				[
					-5.105534208383233,
					0
				],
				[
					-3.4036894722554507,
					3.4036894722557918
				],
				[
					0,
					6.807378944511129
				],
				[
					3.4036894722555644,
					8.509223680639025
				],
				[
					8.509223680638797,
					8.509223680639025
				],
				[
					10.211068416766466,
					8.509223680639025
				],
				[
					13.61475788902203,
					8.509223680639025
				],
				[
					13.61475788902203,
					6.807378944511129
				],
				[
					13.61475788902203,
					5.105534208383688
				],
				[
					13.61475788902203,
					3.4036894722557918
				],
				[
					13.61475788902203,
					0
				],
				[
					13.61475788902203,
					-1.7018447361274411
				],
				[
					13.61475788902203,
					-3.403689472255337
				],
				[
					13.61475788902203,
					-5.105534208382778
				],
				[
					15.316602625149812,
					-6.807378944510674
				],
				[
					18.720292097405263,
					-6.807378944510674
				],
				[
					22.123981569660714,
					-6.807378944510674
				],
				[
					28.93136051417173,
					-6.807378944510674
				],
				[
					32.33504998642729,
					-5.105534208382778
				],
				[
					35.738739458682744,
					-5.105534208382778
				],
				[
					37.440584194810526,
					-5.105534208382778
				],
				[
					39.14242893093831,
					-5.105534208382778
				],
				[
					37.440584194810526,
					-6.807378944510674
				],
				[
					34.036894722555076,
					-6.807378944510674
				],
				[
					32.33504998642729,
					-6.807378944510674
				],
				[
					28.93136051417173,
					-5.105534208382778
				],
				[
					27.22951577804406,
					-3.403689472255337
				],
				[
					25.52767104191628,
					-1.7018447361274411
				],
				[
					23.825826305788496,
					1.7018447361278959
				],
				[
					25.52767104191628,
					5.105534208383688
				],
				[
					28.93136051417173,
					6.807378944511129
				],
				[
					34.036894722555076,
					8.509223680639025
				],
				[
					37.440584194810526,
					6.807378944511129
				],
				[
					40.84427366706598,
					3.4036894722557918
				],
				[
					42.54611840319376,
					0
				],
				[
					44.24796313932154,
					-5.105534208382778
				],
				[
					44.24796313932154,
					-6.807378944510674
				],
				[
					44.24796313932154,
					-5.105534208382778
				],
				[
					44.24796313932154,
					1.7018447361278959
				],
				[
					44.24796313932154,
					6.807378944511129
				],
				[
					49.353497347704774,
					8.509223680639025
				],
				[
					54.45903155608801,
					8.509223680639025
				],
				[
					56.16087629221579,
					6.807378944511129
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.030952727422118187,
				0.07289227098226547,
				0.07191448658704758,
				0.07771435379981995,
				0.07801138609647751,
				0.07673656940460205,
				0.08192657679319382,
				0.0825979933142662,
				0.08252142369747162,
				0.08208148181438446,
				0.08192593604326248,
				0.08289245516061783,
				0.0834018886089325,
				0.07961929589509964,
				0.06439340114593506,
				0.04620620608329773,
				0.04011068865656853,
				0.03156515583395958,
				0.04343096911907196,
				0.04815133661031723,
				0.06401083618402481,
				0.07240362465381622,
				0.09160663187503815,
				0.10730032622814178,
				0.12189282476902008,
				0.13028793036937714,
				0.1390894502401352,
				0.137342169880867,
				0.13143295049667358,
				0.12346991151571274,
				0.12404107302427292,
				0.1296631097793579,
				0.14444327354431152,
				0.15666979551315308,
				0.18987882137298584,
				0.19906765222549438,
				0.20361877977848053,
				0.2010369598865509,
				0.19239087402820587,
				0.18479907512664795,
				0.1736581176519394,
				0.14472073316574097,
				0.12151135504245758,
				0.1150972917675972,
				0.10829785466194153,
				0.11520660668611526,
				0.13449999690055847,
				0.1631958931684494,
				0.19117218255996704,
				0.21565668284893036,
				0.20591112971305847,
				0.17055878043174744,
				0.08242971450090408,
				0.013418731279671192,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 43,
			"versionNonce": 1912711320,
			"isDeleted": false,
			"id": "i1oPQFinBAtvie34dmURA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.13128220375927,
			"y": 2475.3806601805613,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.03689472255496,
			"height": 39.14242893093797,
			"seed": 272340888,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947827717,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.7018447361278959
				],
				[
					1.7018447361277822,
					-1.7018447361278959
				],
				[
					1.7018447361277822,
					-3.403689472255337
				],
				[
					0,
					-5.105534208383233
				],
				[
					-1.7018447361277822,
					-5.105534208383233
				],
				[
					-6.807378944511015,
					-5.105534208383233
				],
				[
					-10.211068416766466,
					-3.403689472255337
				],
				[
					-11.912913152894248,
					0
				],
				[
					-11.912913152894248,
					3.403689472255337
				],
				[
					-10.211068416766466,
					8.50922368063857
				],
				[
					-6.807378944511015,
					10.211068416766466
				],
				[
					-1.7018447361277822,
					8.50922368063857
				],
				[
					1.7018447361277822,
					5.105534208383233
				],
				[
					1.7018447361277822,
					1.7018447361274411
				],
				[
					1.7018447361277822,
					0
				],
				[
					1.7018447361277822,
					-1.7018447361278959
				],
				[
					0,
					-1.7018447361278959
				],
				[
					0,
					1.7018447361274411
				],
				[
					0,
					8.50922368063857
				],
				[
					0,
					17.018447361277595
				],
				[
					0,
					25.527671041916165
				],
				[
					0,
					30.633205250299397
				],
				[
					-1.7018447361277822,
					34.036894722554734
				],
				[
					-3.4036894722554507,
					34.036894722554734
				],
				[
					-5.105534208383233,
					30.633205250299397
				],
				[
					-6.807378944511015,
					27.22951577804406
				],
				[
					-6.807378944511015,
					23.82582630578827
				],
				[
					-5.105534208383233,
					20.42213683353293
				],
				[
					-1.7018447361277822,
					17.018447361277595
				],
				[
					5.105534208383233,
					11.912913152893907
				],
				[
					8.509223680638797,
					8.50922368063857
				],
				[
					15.316602625149699,
					1.7018447361274411
				],
				[
					18.720292097405263,
					-1.7018447361278959
				],
				[
					18.720292097405263,
					-3.403689472255337
				],
				[
					15.316602625149699,
					-5.105534208383233
				],
				[
					11.912913152894248,
					-5.105534208383233
				],
				[
					8.509223680638797,
					-1.7018447361278959
				],
				[
					8.509223680638797,
					3.403689472255337
				],
				[
					10.211068416766466,
					8.50922368063857
				],
				[
					20.422136833533045,
					11.912913152893907
				],
				[
					22.123981569660714,
					11.912913152893907
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.04919494688510895,
				0.051537200808525085,
				0.0777876004576683,
				0.10913040488958359,
				0.1329633742570877,
				0.17216768860816956,
				0.18495914340019226,
				0.19657382369041443,
				0.1849343627691269,
				0.16261209547519684,
				0.11543124169111252,
				0.04720751941204071,
				0.0022719725966453552,
				0.0011904601706191897,
				0.02576351910829544,
				0.05385565012693405,
				0.09949694573879242,
				0.15877145528793335,
				0.19863361120224,
				0.2049112170934677,
				0.19337964057922363,
				0.1656876504421234,
				0.11284652352333069,
				0.07072494179010391,
				0.06659906357526779,
				0.062289703637361526,
				0.07815487682819366,
				0.0929793119430542,
				0.0957251563668251,
				0.08897131681442261,
				0.08785046637058258,
				0.10291808843612671,
				0.12131772190332413,
				0.14062374830245972,
				0.1728397160768509,
				0.20387615263462067,
				0.2641054689884186,
				0.283656507730484,
				0.26103341579437256,
				0.10901696979999542,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 49,
			"versionNonce": 723031272,
			"isDeleted": false,
			"id": "4KYv-TBx4MbPyWSY-7WIz",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -187.88331906443773,
			"y": 2492.399107541839,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 68.07378944510992,
			"height": 23.825826305788723,
			"seed": 1723649256,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947829017,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.7018447361276685,
					-1.7018447361278959
				],
				[
					3.4036894722554507,
					-3.4036894722557918
				],
				[
					5.105534208383233,
					-5.105534208383688
				],
				[
					6.807378944511015,
					-8.509223680639025
				],
				[
					8.509223680638684,
					-11.912913152894362
				],
				[
					8.509223680638684,
					-15.316602625150153
				],
				[
					8.509223680638684,
					-17.018447361277595
				],
				[
					6.807378944511015,
					-20.42213683353293
				],
				[
					5.105534208383233,
					-20.42213683353293
				],
				[
					5.105534208383233,
					-22.123981569660828
				],
				[
					5.105534208383233,
					-23.825826305788723
				],
				[
					8.509223680638684,
					-23.825826305788723
				],
				[
					13.614757889021917,
					-23.825826305788723
				],
				[
					17.018447361277367,
					-22.123981569660828
				],
				[
					18.720292097405263,
					-20.42213683353293
				],
				[
					20.42213683353293,
					-17.018447361277595
				],
				[
					20.42213683353293,
					-13.614757889022258
				],
				[
					18.720292097405263,
					-8.509223680639025
				],
				[
					20.42213683353293,
					-6.807378944511129
				],
				[
					23.825826305788496,
					-5.105534208383688
				],
				[
					25.527671041916165,
					-5.105534208383688
				],
				[
					32.33504998642729,
					-8.509223680639025
				],
				[
					35.73873945868263,
					-11.912913152894362
				],
				[
					37.440584194810526,
					-17.018447361277595
				],
				[
					39.142428930938195,
					-20.42213683353293
				],
				[
					37.440584194810526,
					-22.123981569660828
				],
				[
					35.73873945868263,
					-22.123981569660828
				],
				[
					32.33504998642729,
					-22.123981569660828
				],
				[
					28.93136051417173,
					-18.72029209740549
				],
				[
					28.93136051417173,
					-17.018447361277595
				],
				[
					28.93136051417173,
					-11.912913152894362
				],
				[
					34.03689472255496,
					-8.509223680639025
				],
				[
					40.84427366706586,
					-6.807378944511129
				],
				[
					47.65165261157699,
					-6.807378944511129
				],
				[
					54.45903155608789,
					-8.509223680639025
				],
				[
					57.86272102834346,
					-11.912913152894362
				],
				[
					59.564565764471126,
					-15.316602625150153
				],
				[
					59.564565764471126,
					-20.42213683353293
				],
				[
					57.86272102834346,
					-22.123981569660828
				],
				[
					56.16087629221579,
					-23.825826305788723
				],
				[
					52.757186819960225,
					-22.123981569660828
				],
				[
					51.05534208383256,
					-20.42213683353293
				],
				[
					49.35349734770466,
					-17.018447361277595
				],
				[
					51.05534208383256,
					-13.614757889022258
				],
				[
					56.16087629221579,
					-11.912913152894362
				],
				[
					64.67009997285436,
					-10.211068416766466
				],
				[
					68.07378944510992,
					-10.211068416766466
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.009999999776482582,
				0.06194421276450157,
				0.0735638439655304,
				0.0814623087644577,
				0.07854068279266357,
				0.07428976148366928,
				0.06962643563747406,
				0.06572161614894867,
				0.07249213010072708,
				0.09777083992958069,
				0.10765133798122406,
				0.11354590207338333,
				0.11908694356679916,
				0.11941372603178024,
				0.12232501059770584,
				0.12784841656684875,
				0.1317516714334488,
				0.13850277662277222,
				0.13289010524749756,
				0.13046884536743164,
				0.13135647773742676,
				0.11702987551689148,
				0.11463861167430878,
				0.1279742419719696,
				0.15249139070510864,
				0.17676642537117004,
				0.20131514966487885,
				0.20748575031757355,
				0.2161177098751068,
				0.21829946339130402,
				0.20622113347053528,
				0.19132256507873535,
				0.16333602368831635,
				0.13435803353786469,
				0.11857961863279343,
				0.11665063351392746,
				0.139421746134758,
				0.16488277912139893,
				0.1989656686782837,
				0.2305627167224884,
				0.24325765669345856,
				0.25649797916412354,
				0.26798829436302185,
				0.2623836100101471,
				0.2312995046377182,
				0.10517331212759018,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 27,
			"versionNonce": 1015543448,
			"isDeleted": false,
			"id": "t22GXp81PXfUUcEvGKQdb",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -99.38739278579465,
			"y": 2471.976970708306,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.825826305788496,
			"height": 27.22951577804406,
			"seed": 538283416,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947829718,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.7018447361276685,
					0
				],
				[
					1.7018447361276685,
					-1.7018447361278959
				],
				[
					0,
					-3.4036894722557918
				],
				[
					-1.7018447361278959,
					-3.4036894722557918
				],
				[
					-6.807378944511129,
					-3.4036894722557918
				],
				[
					-15.316602625149926,
					0
				],
				[
					-15.316602625149926,
					3.403689472255337
				],
				[
					-15.316602625149926,
					6.807378944510674
				],
				[
					-11.912913152894362,
					8.50922368063857
				],
				[
					-6.807378944511129,
					8.50922368063857
				],
				[
					0,
					5.105534208382778
				],
				[
					3.403689472255337,
					0
				],
				[
					5.105534208383233,
					-5.105534208383688
				],
				[
					5.105534208383233,
					-10.211068416766466
				],
				[
					5.105534208383233,
					-15.316602625150153
				],
				[
					5.105534208383233,
					-18.72029209740549
				],
				[
					3.403689472255337,
					-18.72029209740549
				],
				[
					3.403689472255337,
					-17.018447361277595
				],
				[
					3.403689472255337,
					-13.614757889022258
				],
				[
					3.403689472255337,
					-6.807378944511129
				],
				[
					3.403689472255337,
					-1.7018447361278959
				],
				[
					3.403689472255337,
					3.403689472255337
				],
				[
					8.50922368063857,
					6.807378944510674
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07999999821186066,
				0.07405627518892288,
				0.10702099651098251,
				0.12947309017181396,
				0.15951421856880188,
				0.20346756279468536,
				0.207887664437294,
				0.2091646045446396,
				0.1794007569551468,
				0.1417577564716339,
				0.09261828660964966,
				0.08957128971815109,
				0.08298645168542862,
				0.10400231927633286,
				0.1442657709121704,
				0.19117285311222076,
				0.2325192242860794,
				0.2932368814945221,
				0.30255553126335144,
				0.2751685678958893,
				0.2210415005683899,
				0.16046127676963806,
				0.01590750180184841,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 1132466408,
			"isDeleted": false,
			"id": "v1FlIi8l8_rqsO3jlBytS",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -77.26341121613405,
			"y": 2465.169591763795,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.316602625149926,
			"height": 20.42213683353293,
			"seed": 688545512,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1679947830003,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.7018447361276685,
					-1.7018447361278959
				],
				[
					-3.4036894722555644,
					-3.403689472255337
				],
				[
					-5.105534208383233,
					-3.403689472255337
				],
				[
					-6.807378944510901,
					-1.7018447361278959
				],
				[
					-3.4036894722555644,
					1.7018447361274411
				],
				[
					1.7018447361278959,
					6.807378944511129
				],
				[
					5.105534208383233,
					10.211068416766466
				],
				[
					6.807378944511129,
					13.614757889021803
				],
				[
					3.4036894722555644,
					17.018447361277595
				],
				[
					-6.807378944510901,
					15.316602625149699
				],
				[
					-8.509223680638797,
					13.614757889021803
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.07999999821186066,
				0.07739797979593277,
				0.07215115427970886,
				0.12164434790611267,
				0.17379891872406006,
				0.1646275669336319,
				0.1653829663991928,
				0.15479852259159088,
				0.15352869033813477,
				0.16930831968784332,
				0.1303328573703766,
				0
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#000000",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 0.5,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 908.823201058911,
		"scrollY": 852.7664333741128,
		"zoom": {
			"value": 0.36705222683765765
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"colorPalette": {},
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%