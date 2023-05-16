---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
class Nodo
{
    public Nodo Sig {get;set;}
    public Object Dato {get;set;}
    public Nodo(Object dato)
    {
        this.Dato = dato;
        this.Sig = null;
    }

    public Nodo(Object dato, Nodo sig)
    {
        this.Dato = dato;
        this.Sig = sig;
    }

    // Dato -> Sig
    // 5 - Sig -> null
    // "Hola" - Sig -> null

    Nodo n1 = new Nodo(5);
    Nodo n2 = new Nodo("Hola");
    n1.Sig = n2; // 5 -> "Hola"
    n2.Dato
    n1.Sig.Dato
    
    Nodo n3 = new Nodo(true);
    n2.Sig = n3;

    final.Sig = new Nodo(8);
    final = final.Sig;
} ^NrW9sBiU

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.8.26",
	"elements": [
		{
			"type": "text",
			"version": 100,
			"versionNonce": 469186024,
			"isDeleted": false,
			"id": "NrW9sBiU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -425.3333282470703,
			"y": -227.99996948242188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 379.9797058105469,
			"height": 800,
			"seed": 490955213,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "class Nodo\n{\n    public Nodo Sig {get;set;}\n    public Object Dato {get;set;}\n    public Nodo(Object dato)\n    {\n        this.Dato = dato;\n        this.Sig = null;\n    }\n\n    public Nodo(Object dato, Nodo sig)\n    {\n        this.Dato = dato;\n        this.Sig = sig;\n    }\n\n    // Dato -> Sig\n    // 5 - Sig -> null\n    // \"Hola\" - Sig -> null\n\n    Nodo n1 = new Nodo(5);\n    Nodo n2 = new Nodo(\"Hola\");\n    n1.Sig = n2; // 5 -> \"Hola\"\n    n2.Dato\n    n1.Sig.Dato\n    \n    Nodo n3 = new Nodo(true);\n    n2.Sig = n3;\n\n    final.Sig = new Nodo(8);\n    final = final.Sig;\n}",
			"rawText": "class Nodo\n{\n    public Nodo Sig {get;set;}\n    public Object Dato {get;set;}\n    public Nodo(Object dato)\n    {\n        this.Dato = dato;\n        this.Sig = null;\n    }\n\n    public Nodo(Object dato, Nodo sig)\n    {\n        this.Dato = dato;\n        this.Sig = sig;\n    }\n\n    // Dato -> Sig\n    // 5 - Sig -> null\n    // \"Hola\" - Sig -> null\n\n    Nodo n1 = new Nodo(5);\n    Nodo n2 = new Nodo(\"Hola\");\n    n1.Sig = n2; // 5 -> \"Hola\"\n    n2.Dato\n    n1.Sig.Dato\n    \n    Nodo n3 = new Nodo(true);\n    n2.Sig = n3;\n\n    final.Sig = new Nodo(8);\n    final = final.Sig;\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "class Nodo\n{\n    public Nodo Sig {get;set;}\n    public Object Dato {get;set;}\n    public Nodo(Object dato)\n    {\n        this.Dato = dato;\n        this.Sig = null;\n    }\n\n    public Nodo(Object dato, Nodo sig)\n    {\n        this.Dato = dato;\n        this.Sig = sig;\n    }\n\n    // Dato -> Sig\n    // 5 - Sig -> null\n    // \"Hola\" - Sig -> null\n\n    Nodo n1 = new Nodo(5);\n    Nodo n2 = new Nodo(\"Hola\");\n    n1.Sig = n2; // 5 -> \"Hola\"\n    n2.Dato\n    n1.Sig.Dato\n    \n    Nodo n3 = new Nodo(true);\n    n2.Sig = n3;\n\n    final.Sig = new Nodo(8);\n    final = final.Sig;\n}",
			"lineHeight": 1.25,
			"baseline": 792
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 716012696,
			"isDeleted": false,
			"id": "w22_ZBRSjkGx6ih7KjRKA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 172,
			"y": -146.6666259765625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.3333740234375,
			"height": 53.333343505859375,
			"seed": 266003245,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					6,
					9.333343505859375
				],
				[
					6,
					11.333343505859375
				],
				[
					2.6666259765625,
					19.333343505859375
				],
				[
					-0.66668701171875,
					27.333343505859375
				],
				[
					-3.3333740234375,
					36.666656494140625
				],
				[
					-6.66668701171875,
					45.333343505859375
				],
				[
					-8.66668701171875,
					52.666656494140625
				],
				[
					-9.3333740234375,
					53.333343505859375
				],
				[
					-9.3333740234375,
					53.333343505859375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 30,
			"versionNonce": 1047017704,
			"isDeleted": false,
			"id": "ZgZQVDt3eop2i78JhYJHj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 169.33331298828125,
			"y": -139.99996948242188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 40.66668701171875,
			"seed": 1879007075,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.66668701171875,
					-2.666656494140625
				],
				[
					4.66668701171875,
					-2.666656494140625
				],
				[
					6.66668701171875,
					-2.666656494140625
				],
				[
					10,
					-4
				],
				[
					12,
					-4
				],
				[
					14.66668701171875,
					-3.3333282470703125
				],
				[
					16.66668701171875,
					-1.3333282470703125
				],
				[
					20,
					2.66668701171875
				],
				[
					22,
					6.66668701171875
				],
				[
					24,
					10.66668701171875
				],
				[
					24,
					14
				],
				[
					24,
					16
				],
				[
					24,
					16.66668701171875
				],
				[
					22,
					20
				],
				[
					21.33331298828125,
					20
				],
				[
					19.33331298828125,
					22.66668701171875
				],
				[
					15.33331298828125,
					24
				],
				[
					13.33331298828125,
					26.66668701171875
				],
				[
					12,
					28.66668701171875
				],
				[
					10,
					30
				],
				[
					8,
					32.66668701171875
				],
				[
					7.33331298828125,
					34
				],
				[
					5.33331298828125,
					36
				],
				[
					4,
					36
				],
				[
					3.33331298828125,
					36.66668701171875
				],
				[
					2,
					36.66668701171875
				],
				[
					2,
					36.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 1711417752,
			"isDeleted": false,
			"id": "MTxCTvXjoSJRfMcFhpKT_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 203.33331298828125,
			"y": -117.33328247070312,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 1060995469,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.33331298828125
				],
				[
					0,
					2
				],
				[
					0,
					3.33331298828125
				],
				[
					0,
					4
				],
				[
					0.66668701171875,
					4
				],
				[
					2,
					4
				],
				[
					4.66668701171875,
					5.33331298828125
				],
				[
					6.66668701171875,
					5.33331298828125
				],
				[
					8,
					5.33331298828125
				],
				[
					10,
					5.33331298828125
				],
				[
					10.66668701171875,
					5.33331298828125
				],
				[
					10.66668701171875,
					4.666656494140625
				],
				[
					10.66668701171875,
					3.33331298828125
				],
				[
					12.66668701171875,
					-0.66668701171875
				],
				[
					12.66668701171875,
					-3.333343505859375
				],
				[
					14,
					-5.333343505859375
				],
				[
					14,
					-9.333343505859375
				],
				[
					14,
					-11.333343505859375
				],
				[
					14,
					-12.66668701171875
				],
				[
					14,
					-15.333343505859375
				],
				[
					14,
					-16.66668701171875
				],
				[
					14,
					-16.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 50,
			"versionNonce": 297851880,
			"isDeleted": false,
			"id": "WY0UEf5N7D2pacG9x7bMf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 209.33331298828125,
			"y": -125.99996948242188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.66668701171875,
			"height": 66,
			"seed": 1804613133,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.66668701171875,
					0
				],
				[
					-2,
					0
				],
				[
					-2.66668701171875,
					4.66668701171875
				],
				[
					-4.66668701171875,
					8
				],
				[
					-6,
					8.66668701171875
				],
				[
					-6,
					10.66668701171875
				],
				[
					-5.33331298828125,
					12
				],
				[
					-3.33331298828125,
					12.66668701171875
				],
				[
					-1.33331298828125,
					12.66668701171875
				],
				[
					0.66668701171875,
					14
				],
				[
					2.66668701171875,
					14.66668701171875
				],
				[
					4,
					16
				],
				[
					4.66668701171875,
					16
				],
				[
					6,
					10
				],
				[
					8.66668701171875,
					6
				],
				[
					10,
					2
				],
				[
					10.66668701171875,
					-2
				],
				[
					10.66668701171875,
					-2.666656494140625
				],
				[
					10.66668701171875,
					-4
				],
				[
					10.66668701171875,
					-4.666656494140625
				],
				[
					10.66668701171875,
					-6
				],
				[
					10,
					-6
				],
				[
					9.33331298828125,
					-4
				],
				[
					7.33331298828125,
					2.66668701171875
				],
				[
					7.33331298828125,
					6.66668701171875
				],
				[
					7.33331298828125,
					10.66668701171875
				],
				[
					8.66668701171875,
					12.66668701171875
				],
				[
					10.66668701171875,
					14.66668701171875
				],
				[
					12,
					14.66668701171875
				],
				[
					12.66668701171875,
					14.66668701171875
				],
				[
					14,
					11.333343505859375
				],
				[
					16,
					7.333343505859375
				],
				[
					18,
					-0.666656494140625
				],
				[
					22.66668701171875,
					-6.666656494140625
				],
				[
					24.66668701171875,
					-14.666656494140625
				],
				[
					26,
					-20
				],
				[
					26.66668701171875,
					-26.666656494140625
				],
				[
					26.66668701171875,
					-34.666656494140625
				],
				[
					26.66668701171875,
					-36.666656494140625
				],
				[
					26,
					-38
				],
				[
					23.33331298828125,
					-33.33332824707031
				],
				[
					18,
					-16
				],
				[
					13.33331298828125,
					2.66668701171875
				],
				[
					12,
					18
				],
				[
					14,
					26.66668701171875
				],
				[
					14.66668701171875,
					28
				],
				[
					14.66668701171875,
					28
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 205076120,
			"isDeleted": false,
			"id": "bqUI__WuCX0HzmivxEJ5y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 217.33331298828125,
			"y": -146.6666259765625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.66668701171875,
			"height": 15.333343505859375,
			"seed": 428713027,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2,
					0
				],
				[
					10,
					2.666656494140625
				],
				[
					20,
					6.666656494140625
				],
				[
					28,
					11.333343505859375
				],
				[
					32.66668701171875,
					15.333343505859375
				],
				[
					32.66668701171875,
					15.333343505859375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 1477254888,
			"isDeleted": false,
			"id": "BNa28m61rr5pZ1WZy8b0d",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 252.6666259765625,
			"y": -128.6666259765625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.66668701171875,
			"height": 33.333343505859375,
			"seed": 1924393667,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.33331298828125,
					0
				],
				[
					-2,
					0
				],
				[
					-4,
					0
				],
				[
					-8,
					0
				],
				[
					-11.33331298828125,
					3.333343505859375
				],
				[
					-16,
					8.666656494140625
				],
				[
					-17.33331298828125,
					12.666656494140625
				],
				[
					-17.33331298828125,
					20.666656494140625
				],
				[
					-13.33331298828125,
					27.333343505859375
				],
				[
					-9.33331298828125,
					30.666656494140625
				],
				[
					-5.33331298828125,
					31.333343505859375
				],
				[
					-3.33331298828125,
					31.333343505859375
				],
				[
					-0.6666259765625,
					30.666656494140625
				],
				[
					2.66668701171875,
					24.666656494140625
				],
				[
					5.3333740234375,
					18
				],
				[
					6.66668701171875,
					12.666656494140625
				],
				[
					7.3333740234375,
					4
				],
				[
					4.66668701171875,
					-1.333343505859375
				],
				[
					0.66668701171875,
					-2
				],
				[
					-5.33331298828125,
					-2
				],
				[
					-10,
					-2
				],
				[
					-14,
					1.333343505859375
				],
				[
					-14,
					1.333343505859375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 25,
			"versionNonce": 1376166808,
			"isDeleted": false,
			"id": "W1DVmqvTS1pR5Q1W1Ma-8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 194,
			"y": -71.99996948242188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 31.3333740234375,
			"height": 43.333343505859375,
			"seed": 66124653,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.66668701171875,
					-2
				],
				[
					-6.66668701171875,
					-2
				],
				[
					-10.66668701171875,
					-2.666656494140625
				],
				[
					-11.3333740234375,
					-2.666656494140625
				],
				[
					-11.3333740234375,
					0.66668701171875
				],
				[
					-8.66668701171875,
					6.66668701171875
				],
				[
					-6,
					12
				],
				[
					-2.66668701171875,
					16.66668701171875
				],
				[
					-2,
					20
				],
				[
					-0.66668701171875,
					22.66668701171875
				],
				[
					-0.66668701171875,
					28.66668701171875
				],
				[
					-0.66668701171875,
					30
				],
				[
					-0.66668701171875,
					36
				],
				[
					-5.3333740234375,
					40
				],
				[
					-11.3333740234375,
					40
				],
				[
					-18.66668701171875,
					40.66668701171875
				],
				[
					-22.66668701171875,
					40.66668701171875
				],
				[
					-26.66668701171875,
					39.333343505859375
				],
				[
					-29.3333740234375,
					38
				],
				[
					-30.66668701171875,
					37.333343505859375
				],
				[
					-31.3333740234375,
					36
				],
				[
					-31.3333740234375,
					36
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 836305384,
			"isDeleted": false,
			"id": "T1kFjgXlbButUDEuQVKBN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 197.33331298828125,
			"y": -32.6666259765625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 30,
			"seed": 767025133,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779560,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.66668701171875,
					-5.333343505859375
				],
				[
					2,
					-7.333343505859375
				],
				[
					2.66668701171875,
					-11.333343505859375
				],
				[
					4,
					-15.333343505859375
				],
				[
					4.66668701171875,
					-18
				],
				[
					4.66668701171875,
					-22
				],
				[
					4.66668701171875,
					-26
				],
				[
					6,
					-30
				],
				[
					6,
					-29.333343505859375
				],
				[
					8,
					-24.666656494140625
				],
				[
					8,
					-15.333343505859375
				],
				[
					8,
					-5.333343505859375
				],
				[
					6,
					-2.666656494140625
				],
				[
					6,
					-0.666656494140625
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 4,
			"versionNonce": 899575960,
			"isDeleted": false,
			"id": "V7Bsd0clz_H2YV1_H1EYV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 208,
			"y": -83.99996948242188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1818656077,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
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
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 26,
			"versionNonce": 1311802600,
			"isDeleted": false,
			"id": "b5rZWrbSYxV_hIwUCvs-y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 234,
			"y": -61.333282470703125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 36.66668701171875,
			"height": 61.33331298828125,
			"seed": 751456675,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-3.3333740234375,
					1.33331298828125
				],
				[
					-13.3333740234375,
					3.33331298828125
				],
				[
					-16.66668701171875,
					8
				],
				[
					-17.3333740234375,
					14
				],
				[
					-10.66668701171875,
					23.33331298828125
				],
				[
					-4.66668701171875,
					30
				],
				[
					1.33331298828125,
					34
				],
				[
					4,
					36
				],
				[
					5.33331298828125,
					38
				],
				[
					5.33331298828125,
					41.33331298828125
				],
				[
					0.6666259765625,
					48
				],
				[
					-8.66668701171875,
					55.33331298828125
				],
				[
					-20.66668701171875,
					59.33331298828125
				],
				[
					-26.66668701171875,
					61.33331298828125
				],
				[
					-29.3333740234375,
					61.33331298828125
				],
				[
					-31.3333740234375,
					60.666656494140625
				],
				[
					-24,
					52.666656494140625
				],
				[
					-12,
					45.33331298828125
				],
				[
					-4,
					39.33331298828125
				],
				[
					0,
					38.666656494140625
				],
				[
					0,
					37.33331298828125
				],
				[
					1.33331298828125,
					37.33331298828125
				],
				[
					1.33331298828125,
					37.33331298828125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 15,
			"versionNonce": 1320459672,
			"isDeleted": false,
			"id": "YdI8kj5cdYF1gjId5LJ4H",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 146.6666259765625,
			"y": -77.99996948242188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 172.66668701171875,
			"height": 4.666656494140625,
			"seed": 336282253,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.66668701171875,
					0
				],
				[
					10.66668701171875,
					0
				],
				[
					26.66668701171875,
					-0.666656494140625
				],
				[
					51.3333740234375,
					-2.666656494140625
				],
				[
					78.66668701171875,
					-4.666656494140625
				],
				[
					107.3333740234375,
					-4.666656494140625
				],
				[
					133.3333740234375,
					-4.666656494140625
				],
				[
					154.66668701171875,
					-4.666656494140625
				],
				[
					165.3333740234375,
					-4.666656494140625
				],
				[
					171.3333740234375,
					-3.33331298828125
				],
				[
					172.66668701171875,
					-3.33331298828125
				],
				[
					172.66668701171875,
					-3.33331298828125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 37,
			"versionNonce": 446670824,
			"isDeleted": false,
			"id": "SZaz5Es9MtfVjeicfMGZC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 236,
			"y": 102.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 37.3333740234375,
			"height": 47.333343505859375,
			"seed": 662115117,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.666656494140625
				],
				[
					-2.66668701171875,
					-0.666656494140625
				],
				[
					-4.66668701171875,
					-0.666656494140625
				],
				[
					-9.3333740234375,
					-2
				],
				[
					-15.3333740234375,
					-2
				],
				[
					-18.66668701171875,
					-2
				],
				[
					-21.3333740234375,
					-2
				],
				[
					-23.3333740234375,
					-2.666656494140625
				],
				[
					-25.3333740234375,
					-2.666656494140625
				],
				[
					-25.3333740234375,
					-2
				],
				[
					-25.3333740234375,
					0
				],
				[
					-24,
					12
				],
				[
					-24,
					20.66668701171875
				],
				[
					-24,
					28
				],
				[
					-22.66668701171875,
					30
				],
				[
					-22.66668701171875,
					29.3333740234375
				],
				[
					-22.66668701171875,
					26
				],
				[
					-20.66668701171875,
					23.3333740234375
				],
				[
					-16.66668701171875,
					22
				],
				[
					-12.66668701171875,
					22
				],
				[
					-4.66668701171875,
					28
				],
				[
					3.33331298828125,
					32.66668701171875
				],
				[
					8,
					36.66668701171875
				],
				[
					12,
					40
				],
				[
					12,
					42
				],
				[
					12,
					42.66668701171875
				],
				[
					8.6666259765625,
					44
				],
				[
					1.33331298828125,
					44.66668701171875
				],
				[
					-5.3333740234375,
					44.66668701171875
				],
				[
					-9.3333740234375,
					44.66668701171875
				],
				[
					-12.66668701171875,
					44.66668701171875
				],
				[
					-13.3333740234375,
					44.66668701171875
				],
				[
					-15.3333740234375,
					44.66668701171875
				],
				[
					-15.3333740234375,
					44.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 28,
			"versionNonce": 511519384,
			"isDeleted": false,
			"id": "wQjbzqBH6MZtV2Y9KAXwD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 216,
			"y": 188.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18,
			"height": 30.66668701171875,
			"seed": 918024685,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.6666259765625
				],
				[
					1.33331298828125,
					-0.6666259765625
				],
				[
					2,
					-0.6666259765625
				],
				[
					2,
					-2
				],
				[
					-0.66668701171875,
					-2
				],
				[
					-3.3333740234375,
					-2
				],
				[
					-8.66668701171875,
					0
				],
				[
					-10.66668701171875,
					0.66668701171875
				],
				[
					-10.66668701171875,
					2.66668701171875
				],
				[
					-10.66668701171875,
					4.66668701171875
				],
				[
					-8.66668701171875,
					8.66668701171875
				],
				[
					-4.66668701171875,
					14.66668701171875
				],
				[
					-0.66668701171875,
					20
				],
				[
					2,
					24
				],
				[
					3.33331298828125,
					26.66668701171875
				],
				[
					3.33331298828125,
					28.66668701171875
				],
				[
					2.6666259765625,
					28.66668701171875
				],
				[
					-1.3333740234375,
					28.66668701171875
				],
				[
					-5.3333740234375,
					28.66668701171875
				],
				[
					-8.66668701171875,
					28.66668701171875
				],
				[
					-9.3333740234375,
					28.66668701171875
				],
				[
					-12.66668701171875,
					27.3333740234375
				],
				[
					-13.3333740234375,
					27.3333740234375
				],
				[
					-14.66668701171875,
					26
				],
				[
					-14.66668701171875,
					26
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 19,
			"versionNonce": 1932684008,
			"isDeleted": false,
			"id": "zdWJYPWbKp_2MisrPaGcU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 225.33331298828125,
			"y": 224.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 23.33331298828125,
			"seed": 309673603,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2,
					0
				],
				[
					6,
					0
				],
				[
					8.66668701171875,
					-0.6666259765625
				],
				[
					10,
					-2
				],
				[
					10,
					-6.6666259765625
				],
				[
					10.66668701171875,
					-8.6666259765625
				],
				[
					12,
					-14
				],
				[
					14,
					-16.6666259765625
				],
				[
					14,
					-18
				],
				[
					14,
					-18.6666259765625
				],
				[
					14,
					-18
				],
				[
					14,
					-10
				],
				[
					14,
					-2
				],
				[
					14,
					2.66668701171875
				],
				[
					14,
					4.66668701171875
				],
				[
					14,
					4.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 4,
			"versionNonce": 1605113752,
			"isDeleted": false,
			"id": "1zg_nIzhlefgcesqFSo91",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 243.33331298828125,
			"y": 199.33340454101562,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1062069027,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
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
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 35,
			"versionNonce": 1383386600,
			"isDeleted": false,
			"id": "BbutbMlkG09tka__sd43U",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 282,
			"y": 206.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.3333740234375,
			"height": 46.6666259765625,
			"seed": 652704493,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.66668701171875,
					-0.6666259765625
				],
				[
					-2.66668701171875,
					-0.6666259765625
				],
				[
					-6.66668701171875,
					-0.6666259765625
				],
				[
					-9.3333740234375,
					2
				],
				[
					-14.66668701171875,
					6.66668701171875
				],
				[
					-15.3333740234375,
					10.66668701171875
				],
				[
					-16.66668701171875,
					12.66668701171875
				],
				[
					-16.66668701171875,
					14.66668701171875
				],
				[
					-16.66668701171875,
					18
				],
				[
					-16.66668701171875,
					20.66668701171875
				],
				[
					-14.66668701171875,
					24
				],
				[
					-12,
					26
				],
				[
					-10.66668701171875,
					28
				],
				[
					-10,
					30
				],
				[
					-6.66668701171875,
					32
				],
				[
					-4.66668701171875,
					36
				],
				[
					-4,
					38
				],
				[
					-4.66668701171875,
					40
				],
				[
					-9.3333740234375,
					40.66668701171875
				],
				[
					-17.3333740234375,
					42.66668701171875
				],
				[
					-28.66668701171875,
					44.66668701171875
				],
				[
					-33.3333740234375,
					46
				],
				[
					-34.66668701171875,
					46
				],
				[
					-35.3333740234375,
					46
				],
				[
					-35.3333740234375,
					40
				],
				[
					-26.66668701171875,
					30
				],
				[
					-20,
					25.3333740234375
				],
				[
					-12,
					22
				],
				[
					-8,
					21.3333740234375
				],
				[
					-4,
					19.3333740234375
				],
				[
					-2.66668701171875,
					19.3333740234375
				],
				[
					-2.66668701171875,
					19.3333740234375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 1450534040,
			"isDeleted": false,
			"id": "E1LV9Fqd9gk-xP7UziOgk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 277.33331298828125,
			"y": 212.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.3333740234375,
			"height": 38.66668701171875,
			"seed": 561568589,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.66668701171875,
					0
				],
				[
					-4,
					0
				],
				[
					-8,
					4
				],
				[
					-10.66668701171875,
					8
				],
				[
					-10.66668701171875,
					10.66668701171875
				],
				[
					-10.66668701171875,
					12
				],
				[
					-10.66668701171875,
					12.66668701171875
				],
				[
					-10,
					12.66668701171875
				],
				[
					-9.33331298828125,
					12.66668701171875
				],
				[
					-8,
					12.66668701171875
				],
				[
					-6,
					12.66668701171875
				],
				[
					-5.33331298828125,
					12.66668701171875
				],
				[
					-1.33331298828125,
					10
				],
				[
					0.66668701171875,
					7.3333740234375
				],
				[
					4.66668701171875,
					3.3333740234375
				],
				[
					8,
					1.3333740234375
				],
				[
					8.66668701171875,
					1.3333740234375
				],
				[
					8.66668701171875,
					0
				],
				[
					8.66668701171875,
					0.66668701171875
				],
				[
					8.66668701171875,
					2
				],
				[
					8.66668701171875,
					6.66668701171875
				],
				[
					2,
					16
				],
				[
					-4,
					24
				],
				[
					-10.66668701171875,
					34
				],
				[
					-14.66668701171875,
					38.66668701171875
				],
				[
					-14.66668701171875,
					38.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 24301800,
			"isDeleted": false,
			"id": "9ISohZ1irV-0vT6sbhd_J",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 165.33331298828125,
			"y": 176.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 164.66668701171875,
			"height": 8.6666259765625,
			"seed": 587276429,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2,
					0
				],
				[
					16,
					-0.6666259765625
				],
				[
					38,
					-2
				],
				[
					70,
					-4
				],
				[
					108,
					-6
				],
				[
					140,
					-6
				],
				[
					158.66668701171875,
					-8
				],
				[
					164.66668701171875,
					-8.6666259765625
				],
				[
					164.66668701171875,
					-8.6666259765625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 34,
			"versionNonce": 546115992,
			"isDeleted": false,
			"id": "WslJAnGtEy1qa_hQuE3WX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 330.6666259765625,
			"y": 245.33340454101562,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 156.666748046875,
			"height": 12.6666259765625,
			"seed": 1523359971,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.3333740234375
				],
				[
					0.66668701171875,
					-1.3333740234375
				],
				[
					3.3333740234375,
					-1.3333740234375
				],
				[
					16.66668701171875,
					0.6666259765625
				],
				[
					36.66668701171875,
					0.6666259765625
				],
				[
					59.3333740234375,
					-2
				],
				[
					80.66668701171875,
					-5.3333740234375
				],
				[
					96.66668701171875,
					-7.3333740234375
				],
				[
					103.3333740234375,
					-8
				],
				[
					109.3333740234375,
					-8
				],
				[
					110.66668701171875,
					-8
				],
				[
					113.3333740234375,
					-9.3333740234375
				],
				[
					116.66668701171875,
					-9.3333740234375
				],
				[
					119.3333740234375,
					-10
				],
				[
					121.3333740234375,
					-10
				],
				[
					121.3333740234375,
					-11.3333740234375
				],
				[
					123.3333740234375,
					-12
				],
				[
					125.3333740234375,
					-12
				],
				[
					126.66668701171875,
					-12
				],
				[
					127.3333740234375,
					-12
				],
				[
					128.66668701171875,
					-12
				],
				[
					131.3333740234375,
					-12
				],
				[
					134.66668701171875,
					-12
				],
				[
					138.66668701171875,
					-12
				],
				[
					145.3333740234375,
					-10.66668701171875
				],
				[
					148.666748046875,
					-9.3333740234375
				],
				[
					151.3333740234375,
					-8.66668701171875
				],
				[
					154.666748046875,
					-7.3333740234375
				],
				[
					155.3333740234375,
					-7.3333740234375
				],
				[
					156.666748046875,
					-7.3333740234375
				],
				[
					156.666748046875,
					-7.3333740234375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 1203270632,
			"isDeleted": false,
			"id": "9996WA5qriCnDbQB-5pV-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 481.3333740234375,
			"y": 215.33340454101562,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.3333740234375,
			"height": 46,
			"seed": 470735053,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.3333740234375
				],
				[
					4,
					0.6666259765625
				],
				[
					8,
					2.6666259765625
				],
				[
					14.6666259765625,
					5.33331298828125
				],
				[
					20,
					9.33331298828125
				],
				[
					24.6666259765625,
					13.33331298828125
				],
				[
					30,
					16.6666259765625
				],
				[
					32,
					19.33331298828125
				],
				[
					32.6666259765625,
					20.6666259765625
				],
				[
					32.6666259765625,
					21.33331298828125
				],
				[
					29.333251953125,
					21.33331298828125
				],
				[
					21.333251953125,
					25.33331298828125
				],
				[
					13.333251953125,
					31.33331298828125
				],
				[
					4,
					39.33331298828125
				],
				[
					-0.666748046875,
					43.33331298828125
				],
				[
					-0.666748046875,
					44.6666259765625
				],
				[
					-2,
					44.6666259765625
				],
				[
					-2.666748046875,
					44.6666259765625
				],
				[
					-2.666748046875,
					44.6666259765625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 9,
			"versionNonce": 86449816,
			"isDeleted": false,
			"id": "haan7LogOYVFcyMkr-cj_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 572,
			"y": 164.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4,
			"height": 26.66668701171875,
			"seed": 515239619,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.3333740234375,
					0.66668701171875
				],
				[
					3.3333740234375,
					8
				],
				[
					4,
					14
				],
				[
					4,
					22.66668701171875
				],
				[
					4,
					26.66668701171875
				],
				[
					4,
					26.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 458340072,
			"isDeleted": false,
			"id": "OzKW-WE-JHLSg2aE-YtEb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 585.3333740234375,
			"y": 170.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2,
			"height": 30,
			"seed": 1310913859,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.66668701171875
				],
				[
					0,
					2
				],
				[
					0.6666259765625,
					10
				],
				[
					2,
					18.66668701171875
				],
				[
					2,
					26
				],
				[
					2,
					30
				],
				[
					2,
					30
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1157073816,
			"isDeleted": false,
			"id": "4rV2wfAL44pxDIFCsI8aV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 606,
			"y": 174.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.6666259765625,
			"height": 42,
			"seed": 1916016109,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					2.66668701171875
				],
				[
					0,
					10.66668701171875
				],
				[
					0,
					16.66668701171875
				],
				[
					-2.6666259765625,
					28
				],
				[
					-4.6666259765625,
					36
				],
				[
					-5.3333740234375,
					42
				],
				[
					-6.6666259765625,
					42
				],
				[
					-6.6666259765625,
					42
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1355454952,
			"isDeleted": false,
			"id": "4EKO5cxGR56zfBEKxL788",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 601.3333740234375,
			"y": 206.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 6.6666259765625,
			"seed": 57131469,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.6666259765625
				],
				[
					2,
					-0.6666259765625
				],
				[
					6.6666259765625,
					-0.6666259765625
				],
				[
					12,
					-2
				],
				[
					18.6666259765625,
					-4.6666259765625
				],
				[
					20.6666259765625,
					-6.6666259765625
				],
				[
					22,
					-6.6666259765625
				],
				[
					22,
					-6.6666259765625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 1781684376,
			"isDeleted": false,
			"id": "tlkzSF80pLDChmG3NPW_u",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 626,
			"y": 176.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.6666259765625,
			"height": 42.66668701171875,
			"seed": 796131757,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.66668701171875
				],
				[
					-1.3333740234375,
					6.66668701171875
				],
				[
					-3.3333740234375,
					16.66668701171875
				],
				[
					-6.6666259765625,
					26
				],
				[
					-7.3333740234375,
					34.66668701171875
				],
				[
					-7.3333740234375,
					42
				],
				[
					-8.6666259765625,
					42.66668701171875
				],
				[
					-8.6666259765625,
					42.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 30,
			"versionNonce": 1261378792,
			"isDeleted": false,
			"id": "qC_v3_rT-s8EpZm9TafYV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633.3333740234375,
			"y": 202.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.6666259765625,
			"height": 19.33331298828125,
			"seed": 947672461,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.666748046875,
					0
				],
				[
					-2.666748046875,
					2.66668701171875
				],
				[
					-2.666748046875,
					8
				],
				[
					-4,
					10
				],
				[
					-4,
					12.66668701171875
				],
				[
					-3.3333740234375,
					16
				],
				[
					-1.3333740234375,
					16.66668701171875
				],
				[
					0,
					18
				],
				[
					2,
					18.66668701171875
				],
				[
					4.6666259765625,
					18.66668701171875
				],
				[
					8,
					18.66668701171875
				],
				[
					10,
					18.66668701171875
				],
				[
					12,
					17.3333740234375
				],
				[
					12,
					14
				],
				[
					12,
					10
				],
				[
					12.6666259765625,
					6
				],
				[
					12,
					2
				],
				[
					9.333251953125,
					-0.6666259765625
				],
				[
					7.333251953125,
					-0.6666259765625
				],
				[
					3.333251953125,
					-0.6666259765625
				],
				[
					1.333251953125,
					-0.6666259765625
				],
				[
					0,
					-0.6666259765625
				],
				[
					0,
					0
				],
				[
					0,
					2
				],
				[
					0,
					2.66668701171875
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 411796888,
			"isDeleted": false,
			"id": "wJzeeJVo1aKmgA79CcRBs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 651.3333740234375,
			"y": 218.66671752929688,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.6666259765625,
			"height": 46,
			"seed": 310965379,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779561,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6666259765625,
					0
				],
				[
					4.6666259765625,
					1.33331298828125
				],
				[
					10,
					-0.66668701171875
				],
				[
					12,
					-7.33331298828125
				],
				[
					14,
					-15.33331298828125
				],
				[
					14,
					-24.66668701171875
				],
				[
					14,
					-32.66668701171875
				],
				[
					14,
					-38.66668701171875
				],
				[
					14,
					-42.66668701171875
				],
				[
					14,
					-44.66668701171875
				],
				[
					13.333251953125,
					-44.66668701171875
				],
				[
					8,
					-42.66668701171875
				],
				[
					6,
					-36
				],
				[
					2,
					-26.66668701171875
				],
				[
					1.333251953125,
					-18
				],
				[
					1.333251953125,
					-10.66668701171875
				],
				[
					1.333251953125,
					-6
				],
				[
					1.333251953125,
					-2.66668701171875
				],
				[
					2,
					-2.66668701171875
				],
				[
					6,
					-2
				],
				[
					10.6666259765625,
					-2
				],
				[
					14.6666259765625,
					-5.33331298828125
				],
				[
					16.6666259765625,
					-5.33331298828125
				],
				[
					18,
					-5.33331298828125
				],
				[
					18.6666259765625,
					-5.33331298828125
				],
				[
					18.6666259765625,
					-5.33331298828125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 29,
			"versionNonce": 738934760,
			"isDeleted": false,
			"id": "zGLDw2wfvg6ugGtUyEPEA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 679.3333740234375,
			"y": 208.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16,
			"height": 20.6666259765625,
			"seed": 44680003,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.6666259765625
				],
				[
					-0.666748046875,
					-0.6666259765625
				],
				[
					-2,
					-0.6666259765625
				],
				[
					-4,
					-0.6666259765625
				],
				[
					-6,
					2
				],
				[
					-6,
					10.66668701171875
				],
				[
					-6,
					12
				],
				[
					-6,
					16
				],
				[
					-6,
					18
				],
				[
					-5.3333740234375,
					18.66668701171875
				],
				[
					-3.3333740234375,
					20
				],
				[
					0,
					20
				],
				[
					2.6666259765625,
					17.3333740234375
				],
				[
					6,
					13.3333740234375
				],
				[
					8.6666259765625,
					8
				],
				[
					8.6666259765625,
					6
				],
				[
					10,
					3.3333740234375
				],
				[
					10,
					1.3333740234375
				],
				[
					10,
					-0.6666259765625
				],
				[
					10,
					0
				],
				[
					10,
					0.66668701171875
				],
				[
					7.333251953125,
					6.66668701171875
				],
				[
					7.333251953125,
					12.66668701171875
				],
				[
					7.333251953125,
					16.66668701171875
				],
				[
					7.333251953125,
					18
				],
				[
					7.333251953125,
					18
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 10,
			"versionNonce": 1563890328,
			"isDeleted": false,
			"id": "q8m970TU5AzLmf9b1D0K3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 697.3333740234375,
			"y": 176.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4,
			"height": 18,
			"seed": 357941763,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.66668701171875
				],
				[
					0.6666259765625,
					4
				],
				[
					0.6666259765625,
					6.66668701171875
				],
				[
					0.6666259765625,
					10
				],
				[
					2.6666259765625,
					16
				],
				[
					4,
					18
				],
				[
					4,
					18
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 11,
			"versionNonce": 57344744,
			"isDeleted": false,
			"id": "wZSONnGGI3K0EX2rKyWsq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 719.3333740234375,
			"y": 170.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 3.3333740234375,
			"height": 30,
			"seed": 2108151085,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.66668701171875
				],
				[
					0.6666259765625,
					4.66668701171875
				],
				[
					2.6666259765625,
					8
				],
				[
					2.6666259765625,
					14
				],
				[
					2.6666259765625,
					20
				],
				[
					1.333251953125,
					26.66668701171875
				],
				[
					-0.666748046875,
					30
				],
				[
					-0.666748046875,
					30
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 2129199000,
			"isDeleted": false,
			"id": "JpEXJp3H9VzNaYcBSC_Mm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 551.3333740234375,
			"y": 250.00003051757812,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 186,
			"height": 18.6666259765625,
			"seed": 979106061,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.6666259765625,
					0
				],
				[
					18.6666259765625,
					0
				],
				[
					46,
					0
				],
				[
					94,
					-4
				],
				[
					142,
					-10
				],
				[
					176,
					-16
				],
				[
					186,
					-18.6666259765625
				],
				[
					185.333251953125,
					-18.6666259765625
				],
				[
					185.333251953125,
					-18.6666259765625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 32,
			"versionNonce": 2145019368,
			"isDeleted": false,
			"id": "xoYGowhrs4mLXDXY3x-Js",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 636.6666259765625,
			"y": 268.0000305175781,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.3333740234375,
			"height": 42.66668701171875,
			"seed": 1275322467,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.6666259765625
				],
				[
					-1.333251953125,
					-2
				],
				[
					-2,
					-2
				],
				[
					-3.333251953125,
					-1.33331298828125
				],
				[
					-4,
					0
				],
				[
					-5.333251953125,
					2
				],
				[
					-5.333251953125,
					4.66668701171875
				],
				[
					-7.333251953125,
					8
				],
				[
					-7.333251953125,
					10.66668701171875
				],
				[
					-7.333251953125,
					12.66668701171875
				],
				[
					-5.333251953125,
					14
				],
				[
					-3.333251953125,
					14.66668701171875
				],
				[
					-2.6666259765625,
					16
				],
				[
					-1.333251953125,
					18
				],
				[
					-0.6666259765625,
					18
				],
				[
					0.666748046875,
					18.66668701171875
				],
				[
					1.3333740234375,
					20.66668701171875
				],
				[
					1.3333740234375,
					24
				],
				[
					0,
					28.66668701171875
				],
				[
					-2,
					32
				],
				[
					-4,
					34.66668701171875
				],
				[
					-9.333251953125,
					36.66668701171875
				],
				[
					-13.333251953125,
					38.66668701171875
				],
				[
					-18,
					38.66668701171875
				],
				[
					-22,
					40
				],
				[
					-25.333251953125,
					40.66668701171875
				],
				[
					-26,
					40.66668701171875
				],
				[
					-28,
					40.66668701171875
				],
				[
					-28,
					40.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 1305824408,
			"isDeleted": false,
			"id": "-OxKXq_RoQkDFA8E70Q-y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 643.3333740234375,
			"y": 304.0000305175781,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.6666259765625,
			"height": 20.66668701171875,
			"seed": 589805293,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6666259765625,
					0
				],
				[
					2,
					-0.6666259765625
				],
				[
					2.6666259765625,
					-2.6666259765625
				],
				[
					2.6666259765625,
					-4
				],
				[
					2.6666259765625,
					-6
				],
				[
					2.6666259765625,
					-8.6666259765625
				],
				[
					2.6666259765625,
					-12
				],
				[
					2.6666259765625,
					-12.6666259765625
				],
				[
					2.6666259765625,
					-14
				],
				[
					2,
					-14
				],
				[
					2,
					-12
				],
				[
					2.6666259765625,
					-10
				],
				[
					4.6666259765625,
					-4
				],
				[
					6,
					0
				],
				[
					8,
					6
				],
				[
					10,
					6.66668701171875
				],
				[
					10.6666259765625,
					6.66668701171875
				],
				[
					10.6666259765625,
					6.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 6,
			"versionNonce": 509962472,
			"isDeleted": false,
			"id": "xYoOJncQb0PAeleOA1EBw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 648.6666259765625,
			"y": 282.0000305175781,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.333251953125,
			"height": 0,
			"seed": 1350722221,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779562,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.333251953125,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 39,
			"versionNonce": 1940912536,
			"isDeleted": false,
			"id": "RoI35HWAHyXExbZGjOOIr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 682,
			"y": 284.0000305175781,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.666748046875,
			"height": 49.33331298828125,
			"seed": 927342051,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-2.6666259765625,
					0
				],
				[
					-4.6666259765625,
					0
				],
				[
					-5.3333740234375,
					0
				],
				[
					-6.6666259765625,
					0.66668701171875
				],
				[
					-7.3333740234375,
					2
				],
				[
					-7.3333740234375,
					8
				],
				[
					-7.3333740234375,
					14.66668701171875
				],
				[
					-6,
					18.66668701171875
				],
				[
					-4,
					24
				],
				[
					-2.6666259765625,
					24.66668701171875
				],
				[
					-2,
					28
				],
				[
					0,
					30
				],
				[
					1.3333740234375,
					36
				],
				[
					2,
					38.66668701171875
				],
				[
					2,
					42
				],
				[
					2,
					46
				],
				[
					-0.6666259765625,
					48
				],
				[
					-4.6666259765625,
					48.66668701171875
				],
				[
					-7.3333740234375,
					48.66668701171875
				],
				[
					-12.6666259765625,
					45.3333740234375
				],
				[
					-18.6666259765625,
					42
				],
				[
					-20.6666259765625,
					40
				],
				[
					-21.3333740234375,
					39.3333740234375
				],
				[
					-21.3333740234375,
					37.3333740234375
				],
				[
					-21.3333740234375,
					33.3333740234375
				],
				[
					-18,
					28
				],
				[
					-12.6666259765625,
					22
				],
				[
					-8.6666259765625,
					18
				],
				[
					-4.6666259765625,
					13.3333740234375
				],
				[
					-2.6666259765625,
					8
				],
				[
					1.3333740234375,
					4
				],
				[
					3.3333740234375,
					1.3333740234375
				],
				[
					3.3333740234375,
					0
				],
				[
					3.3333740234375,
					-0.6666259765625
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 49,
			"versionNonce": 1519913960,
			"isDeleted": false,
			"id": "vHV81YrfqvdguLQcvPLiQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 740.6666870117188,
			"y": 308.0000305175781,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 140.66668701171875,
			"height": 218.66665649414062,
			"seed": 424328899,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					3.3333740234375,
					2
				],
				[
					8.66668701171875,
					4
				],
				[
					11.3333740234375,
					5.33331298828125
				],
				[
					16.66668701171875,
					5.33331298828125
				],
				[
					22.66668701171875,
					5.33331298828125
				],
				[
					34.66668701171875,
					5.33331298828125
				],
				[
					52.66668701171875,
					1.33331298828125
				],
				[
					68.66668701171875,
					-1.33331298828125
				],
				[
					83.3333740234375,
					-6.66668701171875
				],
				[
					91.3333740234375,
					-10.66668701171875
				],
				[
					97.3333740234375,
					-15.33331298828125
				],
				[
					101.3333740234375,
					-21.33331298828125
				],
				[
					106.66668701171875,
					-33.33331298828125
				],
				[
					110.66668701171875,
					-44.66668701171875
				],
				[
					112.66668701171875,
					-53.33331298828125
				],
				[
					115.3333740234375,
					-66.66668701171875
				],
				[
					116.66668701171875,
					-74.66668701171875
				],
				[
					117.3333740234375,
					-84.66668701171875
				],
				[
					116.66668701171875,
					-92.66668701171875
				],
				[
					112.66668701171875,
					-104.66668701171875
				],
				[
					110,
					-114.66668701171875
				],
				[
					106,
					-124.66668701171875
				],
				[
					102,
					-132.66668701171875
				],
				[
					98,
					-141.33331298828125
				],
				[
					94.66668701171875,
					-152.66668701171875
				],
				[
					92.66668701171875,
					-160.66668701171875
				],
				[
					90.66668701171875,
					-169.33331298828125
				],
				[
					90,
					-177.33334350585938
				],
				[
					90,
					-185.33334350585938
				],
				[
					92.66668701171875,
					-193.33334350585938
				],
				[
					96.66668701171875,
					-200.66668701171875
				],
				[
					99.3333740234375,
					-203.33334350585938
				],
				[
					101.3333740234375,
					-205.33334350585938
				],
				[
					104.66668701171875,
					-207.33334350585938
				],
				[
					105.3333740234375,
					-208.66668701171875
				],
				[
					107.3333740234375,
					-208.66668701171875
				],
				[
					113.3333740234375,
					-209.33334350585938
				],
				[
					118.66668701171875,
					-211.33334350585938
				],
				[
					122.66668701171875,
					-212.66668701171875
				],
				[
					125.3333740234375,
					-213.33334350585938
				],
				[
					127.3333740234375,
					-213.33334350585938
				],
				[
					132.66668701171875,
					-212.66668701171875
				],
				[
					137.3333740234375,
					-210.66668701171875
				],
				[
					138.66668701171875,
					-210.66668701171875
				],
				[
					140.66668701171875,
					-210.66668701171875
				],
				[
					140.66668701171875,
					-210.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 22,
			"versionNonce": 1135412888,
			"isDeleted": false,
			"id": "C9AaYoysUsIL6IQpreYmf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 877.3333740234375,
			"y": 80.66668701171875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.66668701171875,
			"height": 38.666656494140625,
			"seed": 1298933187,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.66668701171875,
					0
				],
				[
					6.66668701171875,
					3.333343505859375
				],
				[
					12,
					8.666656494140625
				],
				[
					18.66668701171875,
					14.666656494140625
				],
				[
					22.00006103515625,
					18.666656494140625
				],
				[
					22.66668701171875,
					18.666656494140625
				],
				[
					22.66668701171875,
					19.333343505859375
				],
				[
					22.66668701171875,
					20.666656494140625
				],
				[
					22.66668701171875,
					23.333343505859375
				],
				[
					20,
					26.666656494140625
				],
				[
					16,
					32.666656494140625
				],
				[
					9.33331298828125,
					34.666656494140625
				],
				[
					3.33331298828125,
					35.333343505859375
				],
				[
					0,
					36.666656494140625
				],
				[
					-2,
					36.666656494140625
				],
				[
					-2.66668701171875,
					37.333343505859375
				],
				[
					-4,
					37.333343505859375
				],
				[
					-4,
					38.666656494140625
				],
				[
					-4,
					38.666656494140625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 24,
			"versionNonce": 1585336040,
			"isDeleted": false,
			"id": "UxFOURhgXMPVx4o5GxoI1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 976.6666870117188,
			"y": 78.66668701171875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.6666259765625,
			"height": 44.666656494140625,
			"seed": 1471723437,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.333343505859375
				],
				[
					-5.333251953125,
					-1.333343505859375
				],
				[
					-9.333251953125,
					-2
				],
				[
					-10,
					1.333343505859375
				],
				[
					-11.333251953125,
					6.666656494140625
				],
				[
					-11.333251953125,
					10.666656494140625
				],
				[
					-6.6666259765625,
					17.333343505859375
				],
				[
					-1.333251953125,
					21.333343505859375
				],
				[
					2.666748046875,
					25.333343505859375
				],
				[
					6.666748046875,
					27.333343505859375
				],
				[
					7.3333740234375,
					28.666656494140625
				],
				[
					4.666748046875,
					30.666656494140625
				],
				[
					-1.333251953125,
					32.666656494140625
				],
				[
					-10,
					35.333343505859375
				],
				[
					-18,
					37.333343505859375
				],
				[
					-24,
					40.666656494140625
				],
				[
					-26,
					41.333343505859375
				],
				[
					-27.333251953125,
					42.666656494140625
				],
				[
					-26.6666259765625,
					42
				],
				[
					-25.333251953125,
					40.666656494140625
				],
				[
					-25.333251953125,
					40.666656494140625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 21,
			"versionNonce": 176190360,
			"isDeleted": false,
			"id": "DgG7XNsuVHrzzmL1lgJk7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 999.3334350585938,
			"y": 97.33334350585938,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.6666259765625,
			"height": 32,
			"seed": 2103628163,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.66668701171875
				],
				[
					-2,
					6
				],
				[
					-8.666748046875,
					20.66668701171875
				],
				[
					-10,
					22.66668701171875
				],
				[
					-10,
					28.66668701171875
				],
				[
					-8,
					30.66668701171875
				],
				[
					-6,
					32
				],
				[
					-4,
					32
				],
				[
					-1.3333740234375,
					31.333343505859375
				],
				[
					2,
					28
				],
				[
					6.6666259765625,
					25.333343505859375
				],
				[
					12,
					21.333343505859375
				],
				[
					16.6666259765625,
					19.333343505859375
				],
				[
					18.6666259765625,
					16
				],
				[
					18.6666259765625,
					14
				],
				[
					18.6666259765625,
					13.333343505859375
				],
				[
					17.333251953125,
					12
				],
				[
					17.333251953125,
					12
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 4,
			"versionNonce": 849621480,
			"isDeleted": false,
			"id": "Y3dbF_UDxxZcR0-Yp6mmX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1003.3334350585938,
			"y": 83.33334350585938,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1663916483,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
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
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 43,
			"versionNonce": 1583235224,
			"isDeleted": false,
			"id": "EPNJ0-SWzRZI52L-FIW-9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1028.6666870117188,
			"y": 98.66668701171875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54.666748046875,
			"height": 60.66668701171875,
			"seed": 732484173,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.333251953125,
					-1.333343505859375
				],
				[
					-4,
					-1.333343505859375
				],
				[
					-8,
					0.666656494140625
				],
				[
					-11.333251953125,
					4.666656494140625
				],
				[
					-13.333251953125,
					9.333343505859375
				],
				[
					-13.333251953125,
					11.333343505859375
				],
				[
					-13.333251953125,
					12.666656494140625
				],
				[
					-13.333251953125,
					13.333343505859375
				],
				[
					-11.333251953125,
					14.666656494140625
				],
				[
					-7.333251953125,
					15.333343505859375
				],
				[
					-2.6666259765625,
					15.333343505859375
				],
				[
					3.3333740234375,
					15.333343505859375
				],
				[
					6.666748046875,
					14
				],
				[
					9.3333740234375,
					12
				],
				[
					10.666748046875,
					10.666656494140625
				],
				[
					10.666748046875,
					8.666656494140625
				],
				[
					11.3333740234375,
					6
				],
				[
					10.666748046875,
					2.666656494140625
				],
				[
					8.666748046875,
					0.666656494140625
				],
				[
					8,
					0.666656494140625
				],
				[
					8,
					1.333343505859375
				],
				[
					4.666748046875,
					8.666656494140625
				],
				[
					2,
					18.666656494140625
				],
				[
					-1.333251953125,
					28.666656494140625
				],
				[
					-3.333251953125,
					36.666656494140625
				],
				[
					-4,
					41.333343505859375
				],
				[
					-8,
					48.666656494140625
				],
				[
					-13.333251953125,
					54.666656494140625
				],
				[
					-18,
					57.333343505859375
				],
				[
					-24,
					59.333343505859375
				],
				[
					-29.333251953125,
					59.333343505859375
				],
				[
					-31.333251953125,
					58.666656494140625
				],
				[
					-32,
					56.000030517578125
				],
				[
					-32,
					54.000030517578125
				],
				[
					-21.333251953125,
					50.666656494140625
				],
				[
					-9.333251953125,
					48.666656494140625
				],
				[
					4.666748046875,
					44.666656494140625
				],
				[
					19.3333740234375,
					40.000030517578125
				],
				[
					22.666748046875,
					38.000030517578125
				],
				[
					22.666748046875,
					38.000030517578125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 14,
			"versionNonce": 1846916328,
			"isDeleted": false,
			"id": "hDNqFDeQ5zMMKk6QCm9Un",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 930.6666870117188,
			"y": 63.333343505859375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 140.666748046875,
			"height": 7.333343505859375,
			"seed": 1847216173,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.666748046875,
					0
				],
				[
					3.3333740234375,
					0
				],
				[
					13.3333740234375,
					0
				],
				[
					37.3333740234375,
					2.66668701171875
				],
				[
					63.3333740234375,
					2.66668701171875
				],
				[
					95.3333740234375,
					1.333343505859375
				],
				[
					123.3333740234375,
					-2
				],
				[
					137.3333740234375,
					-4
				],
				[
					139.3333740234375,
					-4.666656494140625
				],
				[
					140.666748046875,
					-4.666656494140625
				],
				[
					140.666748046875,
					-4.666656494140625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 28,
			"versionNonce": 1861905816,
			"isDeleted": false,
			"id": "U0JWVJTkxAiSn8AWPGH41",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 949.3334350585938,
			"y": 27.333343505859375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28,
			"height": 41.333343505859375,
			"seed": 973989603,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6666259765625,
					0
				],
				[
					6,
					-4.666656494140625
				],
				[
					12,
					-10.666656494140625
				],
				[
					18,
					-16.666656494140625
				],
				[
					20,
					-20.666656494140625
				],
				[
					22,
					-24
				],
				[
					22,
					-26
				],
				[
					22,
					-30
				],
				[
					22,
					-30.666656494140625
				],
				[
					22,
					-30
				],
				[
					20,
					-26
				],
				[
					17.333251953125,
					-16
				],
				[
					13.333251953125,
					-7.33331298828125
				],
				[
					11.333251953125,
					0.66668701171875
				],
				[
					11.333251953125,
					4.66668701171875
				],
				[
					11.333251953125,
					8
				],
				[
					12.6666259765625,
					8.66668701171875
				],
				[
					16,
					10.66668701171875
				],
				[
					18.6666259765625,
					10.66668701171875
				],
				[
					22.6666259765625,
					7.333343505859375
				],
				[
					26,
					4
				],
				[
					28,
					2
				],
				[
					28,
					0
				],
				[
					28,
					-0.666656494140625
				],
				[
					28,
					-0.666656494140625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 12,
			"versionNonce": 1717491688,
			"isDeleted": false,
			"id": "Z4Kj28F37DfaOZ1_a69j4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 933.3334350585938,
			"y": 2.66668701171875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 1.333343505859375,
			"seed": 1141034925,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6666259765625,
					0
				],
				[
					4,
					0.666656494140625
				],
				[
					6.6666259765625,
					1.333343505859375
				],
				[
					18,
					1.333343505859375
				],
				[
					32,
					1.333343505859375
				],
				[
					40.6666259765625,
					1.333343505859375
				],
				[
					46.6666259765625,
					1.333343505859375
				],
				[
					48,
					1.333343505859375
				],
				[
					48,
					1.333343505859375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 81,
			"versionNonce": 1435040408,
			"isDeleted": false,
			"id": "0odL48SNy9jOMxamcXGD0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 963.3334350585938,
			"y": 46.66668701171875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 118,
			"height": 33.333343505859375,
			"seed": 317269955,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.333343505859375
				],
				[
					2,
					-4
				],
				[
					4,
					-7.333343505859375
				],
				[
					4,
					-8
				],
				[
					6,
					-12
				],
				[
					6,
					-15.333343505859375
				],
				[
					6.6666259765625,
					-18
				],
				[
					8,
					-21.333343505859375
				],
				[
					8,
					-25.333343505859375
				],
				[
					8,
					-28
				],
				[
					8,
					-30
				],
				[
					8.6666259765625,
					-30
				],
				[
					12,
					-28.666656494140625
				],
				[
					16.6666259765625,
					-26.666656494140625
				],
				[
					24.6666259765625,
					-23.333343505859375
				],
				[
					32.6666259765625,
					-20.666656494140625
				],
				[
					36.6666259765625,
					-17.333343505859375
				],
				[
					38.6666259765625,
					-15.333343505859375
				],
				[
					38.6666259765625,
					-14.666656494140625
				],
				[
					37.333251953125,
					-14.666656494140625
				],
				[
					32,
					-13.333343505859375
				],
				[
					26,
					-9.333343505859375
				],
				[
					25.333251953125,
					-7.333343505859375
				],
				[
					25.333251953125,
					-4.666656494140625
				],
				[
					25.333251953125,
					-3.333343505859375
				],
				[
					28,
					-3.333343505859375
				],
				[
					30.6666259765625,
					-4
				],
				[
					36,
					-9.333343505859375
				],
				[
					38.6666259765625,
					-13.333343505859375
				],
				[
					42,
					-17.333343505859375
				],
				[
					44,
					-21.333343505859375
				],
				[
					44.6666259765625,
					-26
				],
				[
					46,
					-28
				],
				[
					46,
					-29.333343505859375
				],
				[
					43.333251953125,
					-24.666656494140625
				],
				[
					38,
					-17.333343505859375
				],
				[
					36,
					-11.333343505859375
				],
				[
					36,
					-6.666656494140625
				],
				[
					36,
					-4.666656494140625
				],
				[
					38,
					-3.333343505859375
				],
				[
					40.6666259765625,
					-2.666656494140625
				],
				[
					46.6666259765625,
					-1.333343505859375
				],
				[
					54,
					-4
				],
				[
					60,
					-8
				],
				[
					64,
					-13.333343505859375
				],
				[
					66,
					-17.333343505859375
				],
				[
					66,
					-21.333343505859375
				],
				[
					66,
					-23.333343505859375
				],
				[
					66,
					-25.333343505859375
				],
				[
					63.333251953125,
					-21.333343505859375
				],
				[
					60,
					-16.666656494140625
				],
				[
					59.333251953125,
					-11.333343505859375
				],
				[
					59.333251953125,
					-6.666656494140625
				],
				[
					60,
					-6.666656494140625
				],
				[
					62.6666259765625,
					-5.333343505859375
				],
				[
					64.6666259765625,
					-5.333343505859375
				],
				[
					70,
					-7.333343505859375
				],
				[
					78,
					-11.333343505859375
				],
				[
					84,
					-15.333343505859375
				],
				[
					90,
					-18
				],
				[
					92.6666259765625,
					-23.333343505859375
				],
				[
					96,
					-27.333343505859375
				],
				[
					96,
					-30
				],
				[
					95.333251953125,
					-32
				],
				[
					94,
					-32
				],
				[
					92,
					-33.333343505859375
				],
				[
					87.333251953125,
					-33.333343505859375
				],
				[
					79.333251953125,
					-23.333343505859375
				],
				[
					79.333251953125,
					-22.666656494140625
				],
				[
					79.333251953125,
					-19.333343505859375
				],
				[
					80,
					-18.666656494140625
				],
				[
					84.6666259765625,
					-15.333343505859375
				],
				[
					92,
					-13.333343505859375
				],
				[
					102.6666259765625,
					-12.666656494140625
				],
				[
					112.6666259765625,
					-12.666656494140625
				],
				[
					116.6666259765625,
					-12.666656494140625
				],
				[
					118,
					-12.666656494140625
				],
				[
					118,
					-12.666656494140625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 13,
			"versionNonce": 1602984680,
			"isDeleted": false,
			"id": "XS5leB-WDLmXs1vF0MaLI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1119.3334350585938,
			"y": 117.33334350585938,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58.6666259765625,
			"height": 10.666656494140625,
			"seed": 1678256323,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6666259765625,
					0
				],
				[
					2.6666259765625,
					-0.666656494140625
				],
				[
					6,
					-0.666656494140625
				],
				[
					12,
					-4
				],
				[
					20.6666259765625,
					-6
				],
				[
					32,
					-8.666656494140625
				],
				[
					46,
					-8.666656494140625
				],
				[
					54.6666259765625,
					-10.666656494140625
				],
				[
					58.6666259765625,
					-10.666656494140625
				],
				[
					58.6666259765625,
					-10.666656494140625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 17,
			"versionNonce": 1690167192,
			"isDeleted": false,
			"id": "1FAE8m24qoe2wLn5ngS1R",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1176.6666870117188,
			"y": 93.33334350585938,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.3333740234375,
			"height": 18,
			"seed": 1115781763,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.666748046875,
					0
				],
				[
					3.3333740234375,
					0
				],
				[
					6.666748046875,
					2.66668701171875
				],
				[
					10.666748046875,
					4
				],
				[
					12.666748046875,
					4.66668701171875
				],
				[
					13.3333740234375,
					6
				],
				[
					13.3333740234375,
					6.66668701171875
				],
				[
					10,
					8
				],
				[
					6,
					10.66668701171875
				],
				[
					2,
					14
				],
				[
					-2,
					16
				],
				[
					-4,
					16.66668701171875
				],
				[
					-4,
					18
				],
				[
					-4,
					18
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 112,
			"versionNonce": 1009253864,
			"isDeleted": false,
			"id": "0iHYAucEOMS9AcUwXpuiW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1220.6666870117188,
			"y": 111.33334350585938,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 166.666748046875,
			"height": 93.33334350585938,
			"seed": 1481410435,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.333251953125,
					0
				],
				[
					-2,
					-0.666656494140625
				],
				[
					-2,
					-4
				],
				[
					-0.6666259765625,
					-12
				],
				[
					2.666748046875,
					-18
				],
				[
					5.3333740234375,
					-22.666656494140625
				],
				[
					8.666748046875,
					-28
				],
				[
					10.666748046875,
					-21.33331298828125
				],
				[
					10.666748046875,
					-13.33331298828125
				],
				[
					6.666748046875,
					-2
				],
				[
					2,
					8
				],
				[
					0,
					16
				],
				[
					-1.333251953125,
					18.66668701171875
				],
				[
					-2,
					18.66668701171875
				],
				[
					-2,
					18
				],
				[
					-2,
					11.333343505859375
				],
				[
					3.3333740234375,
					4
				],
				[
					11.3333740234375,
					-2
				],
				[
					17.3333740234375,
					-4.666656494140625
				],
				[
					23.3333740234375,
					-8.666656494140625
				],
				[
					25.3333740234375,
					-10.666656494140625
				],
				[
					26.666748046875,
					-10.666656494140625
				],
				[
					27.3333740234375,
					-10
				],
				[
					28.666748046875,
					-5.33331298828125
				],
				[
					29.3333740234375,
					2
				],
				[
					29.3333740234375,
					8
				],
				[
					29.3333740234375,
					12.66668701171875
				],
				[
					28.666748046875,
					14.66668701171875
				],
				[
					28,
					16
				],
				[
					30.666748046875,
					13.333343505859375
				],
				[
					33.3333740234375,
					7.333343505859375
				],
				[
					35.3333740234375,
					2
				],
				[
					38.666748046875,
					-4
				],
				[
					41.3333740234375,
					-6.666656494140625
				],
				[
					44.666748046875,
					-12.666656494140625
				],
				[
					45.3333740234375,
					-16
				],
				[
					46.666748046875,
					-18
				],
				[
					46.666748046875,
					-18.666656494140625
				],
				[
					46.666748046875,
					-18
				],
				[
					44.666748046875,
					-13.33331298828125
				],
				[
					44,
					-3.33331298828125
				],
				[
					42.666748046875,
					4.66668701171875
				],
				[
					42.666748046875,
					10
				],
				[
					42.666748046875,
					10.66668701171875
				],
				[
					43.3333740234375,
					10.66668701171875
				],
				[
					45.3333740234375,
					10.66668701171875
				],
				[
					51.3333740234375,
					6
				],
				[
					55.3333740234375,
					-2.666656494140625
				],
				[
					58.666748046875,
					-8
				],
				[
					59.3333740234375,
					-14
				],
				[
					59.3333740234375,
					-14.666656494140625
				],
				[
					59.3333740234375,
					-16
				],
				[
					59.3333740234375,
					-14
				],
				[
					59.3333740234375,
					-13.33331298828125
				],
				[
					58,
					-9.33331298828125
				],
				[
					58,
					0
				],
				[
					58,
					2
				],
				[
					59.3333740234375,
					4.66668701171875
				],
				[
					60.666748046875,
					4.66668701171875
				],
				[
					61.3333740234375,
					4.66668701171875
				],
				[
					64.666748046875,
					3.333343505859375
				],
				[
					70.666748046875,
					-0.666656494140625
				],
				[
					77.3333740234375,
					-4
				],
				[
					86.666748046875,
					-10
				],
				[
					90.666748046875,
					-14.666656494140625
				],
				[
					93.3333740234375,
					-24
				],
				[
					95.3333740234375,
					-30
				],
				[
					97.3333740234375,
					-36
				],
				[
					98.666748046875,
					-40.666656494140625
				],
				[
					99.3333740234375,
					-44.666656494140625
				],
				[
					99.3333740234375,
					-46.666656494140625
				],
				[
					99.3333740234375,
					-48.666656494140625
				],
				[
					99.3333740234375,
					-48
				],
				[
					98,
					-45.33331298828125
				],
				[
					96,
					-41.33331298828125
				],
				[
					92,
					-32
				],
				[
					88.666748046875,
					-22
				],
				[
					88.666748046875,
					-12
				],
				[
					88,
					-6
				],
				[
					88,
					0
				],
				[
					88,
					2.66668701171875
				],
				[
					88,
					6.66668701171875
				],
				[
					89.3333740234375,
					8
				],
				[
					92.666748046875,
					8.66668701171875
				],
				[
					98.666748046875,
					6
				],
				[
					107.3333740234375,
					-0.666656494140625
				],
				[
					114.666748046875,
					-8
				],
				[
					118.666748046875,
					-14
				],
				[
					122.666748046875,
					-24
				],
				[
					125.3333740234375,
					-30.666656494140625
				],
				[
					128.666748046875,
					-36
				],
				[
					129.3333740234375,
					-38
				],
				[
					129.3333740234375,
					-38.666656494140625
				],
				[
					128.666748046875,
					-38
				],
				[
					122.666748046875,
					-32
				],
				[
					116.666748046875,
					-28
				],
				[
					116,
					-19.33331298828125
				],
				[
					114,
					-7.33331298828125
				],
				[
					114,
					4
				],
				[
					114,
					12
				],
				[
					120.666748046875,
					20
				],
				[
					130.666748046875,
					24
				],
				[
					144.666748046875,
					24.66668701171875
				],
				[
					155.3333740234375,
					22
				],
				[
					162.666748046875,
					21.333343505859375
				],
				[
					164.666748046875,
					28.66668701171875
				],
				[
					162.666748046875,
					36.66668701171875
				],
				[
					158.666748046875,
					44.66668701171875
				],
				[
					158.666748046875,
					44.66668701171875
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"id": "p0AEDEEMrXfEhYl6_gaPu",
			"type": "freedraw",
			"x": 1207.4451083508166,
			"y": 43.401069054236984,
			"width": 169.23076923076928,
			"height": 114.871826171875,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1659650536,
			"version": 14,
			"versionNonce": 2026714264,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					3.0769230769230944,
					1.0256723257210751
				],
				[
					19.487116887019056,
					21.538461538461547
				],
				[
					41.02557842548072,
					36.923076923076906
				],
				[
					70.76923076923072,
					58.46153846153845
				],
				[
					102.56403996394238,
					74.871826171875
				],
				[
					136.4101938100962,
					92.30769230769226
				],
				[
					154.87173227163453,
					101.53846153846155
				],
				[
					166.1538461538462,
					108.71798001802881
				],
				[
					169.23076923076928,
					113.84615384615381
				],
				[
					169.23076923076928,
					114.871826171875
				],
				[
					169.23076923076928,
					114.871826171875
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				169.23076923076928,
				114.871826171875
			]
		},
		{
			"id": "eT48G3H1tPso47atNHT86",
			"type": "freedraw",
			"x": 1521.2912621969704,
			"y": 71.0933767465446,
			"width": 68.71788611778857,
			"height": 70.76923076923072,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 978837144,
			"version": 40,
			"versionNonce": 759169256,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647779563,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0256253756009528
				],
				[
					-6.153846153846189,
					-4.102548452524047
				],
				[
					-13.333270733173094,
					-6.153846153846075
				],
				[
					-22.564039963942378,
					-6.153846153846075
				],
				[
					-28.71788611778834,
					0
				],
				[
					-31.794809194711434,
					10.256441556490472
				],
				[
					-31.794809194711434,
					22.564133864182736
				],
				[
					-26.666729266826906,
					30.76923076923083
				],
				[
					-21.538461538461434,
					34.871826171875
				],
				[
					-18.46153846153834,
					40
				],
				[
					-18.46153846153834,
					41.02567232572119
				],
				[
					-18.46153846153834,
					43.076923076923094
				],
				[
					-18.46153846153834,
					44.10259540264428
				],
				[
					-27.692307692307622,
					50.25644155649047
				],
				[
					-34.87173227163453,
					55.38461538461547
				],
				[
					-41.02557842548072,
					56.41028771033655
				],
				[
					-44.10250150240381,
					58.46153846153845
				],
				[
					-47.179424579326906,
					58.46153846153845
				],
				[
					-52.30769230769238,
					58.46153846153845
				],
				[
					-55.38461538461547,
					58.46153846153845
				],
				[
					-56.41019381009619,
					57.4359130859375
				],
				[
					-55.38461538461547,
					55.38461538461547
				],
				[
					-45.12826772836547,
					61.53846153846155
				],
				[
					-35.89749849759619,
					64.61538461538464
				],
				[
					-24.615384615384528,
					64.61538461538464
				],
				[
					-17.435960036057622,
					60.512836162860594
				],
				[
					-9.230769230769283,
					51.282066932091425
				],
				[
					-2.0513446514423777,
					42.05129770132214
				],
				[
					6.153846153846189,
					35.89745154747595
				],
				[
					9.230769230769283,
					33.846153846153925
				],
				[
					9.230769230769283,
					34.871826171875
				],
				[
					8.205190805288566,
					43.076923076923094
				],
				[
					6.153846153846189,
					52.30769230769238
				],
				[
					7.179424579326906,
					58.46153846153845
				],
				[
					10.25634765625,
					59.48721078725964
				],
				[
					12.307692307692378,
					59.48721078725964
				],
				[
					12.307692307692378,
					59.48721078725964
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				12.307692307692378,
				59.48721078725964
			]
		},
		{
			"id": "SJ8K7I0dcOFXrtrmjst7-",
			"type": "freedraw",
			"x": 1536.6758775815858,
			"y": 94.6831359863283,
			"width": 0.0001,
			"height": 0.0001,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1629335528,
			"version": 4,
			"versionNonce": 1198186904,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647779564,
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
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				0.0001,
				0.0001
			]
		},
		{
			"id": "PlcukqDANpWPe813Gss_R",
			"type": "freedraw",
			"x": 1561.2912621969704,
			"y": 88.5292898324821,
			"width": 65.64096304086547,
			"height": 91.28206693209142,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 778276760,
			"version": 27,
			"versionNonce": 1650435048,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647779564,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-4.102501502403811,
					4.102548452524047
				],
				[
					-6.153846153846189,
					5.128220778245236
				],
				[
					-9.230769230769283,
					10.256394606370236
				],
				[
					-9.230769230769283,
					16.410240760216425
				],
				[
					-9.230769230769283,
					20.512836162860594
				],
				[
					-6.153846153846189,
					23.58975923978369
				],
				[
					1.0255784254807168,
					26.666682316706783
				],
				[
					9.230769230769283,
					29.743605393629878
				],
				[
					15.384615384615472,
					31.794856144831783
				],
				[
					15.384615384615472,
					34.87177922175488
				],
				[
					15.384615384615472,
					38.97437462439905
				],
				[
					9.230769230769283,
					53.33331768329333
				],
				[
					-6.153846153846189,
					68.71793306790869
				],
				[
					-28.717886117788566,
					78.97437462439905
				],
				[
					-43.076923076923094,
					88.20514385516833
				],
				[
					-44.10250150240381,
					91.28206693209142
				],
				[
					-46.15384615384619,
					91.28206693209142
				],
				[
					-46.15384615384619,
					89.23076923076928
				],
				[
					-36.923076923076906,
					81.02562537560095
				],
				[
					-27.692307692307622,
					71.79485614483178
				],
				[
					-11.282113882211434,
					61.53846153846155
				],
				[
					9.230769230769283,
					46.15384615384619
				],
				[
					19.487116887019283,
					37.94870229867797
				],
				[
					19.487116887019283,
					37.94870229867797
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				19.487116887019283,
				37.94870229867797
			]
		},
		{
			"id": "w1g76leSgcUHY6axrB8QG",
			"type": "freedraw",
			"x": 1432.060492966201,
			"y": 20.836982140174428,
			"width": 182.56403996394238,
			"height": 4.102548452524047,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 91404440,
			"version": 11,
			"versionNonce": 801828504,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647779564,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					3.0769230769230944,
					0
				],
				[
					30.769230769230944,
					4.102548452524047
				],
				[
					76.9230769230769,
					4.102548452524047
				],
				[
					130.25634765625,
					4.102548452524047
				],
				[
					167.1794245793269,
					4.102548452524047
				],
				[
					181.53846153846166,
					4.102548452524047
				],
				[
					182.56403996394238,
					4.102548452524047
				],
				[
					182.56403996394238,
					4.102548452524047
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				182.56403996394238,
				4.102548452524047
			]
		},
		{
			"id": "dYYWksvDDLRsKb86mBidN",
			"type": "freedraw",
			"x": 1494.6245329301435,
			"y": -115.57325862004188,
			"width": 48.20519080528834,
			"height": 25.641009990985538,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 2056524696,
			"version": 16,
			"versionNonce": 1962231528,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647781761,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.0513446514423777,
					0
				],
				[
					6.153846153846189,
					0
				],
				[
					14.359036959134528,
					7.179471529447085
				],
				[
					18.46153846153834,
					12.30769230769232
				],
				[
					24.615384615384528,
					15.384615384615358
				],
				[
					27.692307692307622,
					16.41024076021631
				],
				[
					29.74365234375,
					16.41024076021631
				],
				[
					36.923076923076906,
					9.230769230769226
				],
				[
					38.97442157451928,
					5.128173828125
				],
				[
					43.076923076923094,
					-3.0769230769230944
				],
				[
					46.15384615384619,
					-9.230769230769226
				],
				[
					48.20519080528834,
					-9.230769230769226
				],
				[
					48.20519080528834,
					-8.205143855168274
				],
				[
					48.20519080528834,
					-8.205143855168274
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				48.20519080528834,
				-8.205143855168274
			]
		},
		{
			"id": "iz_Zx2tj2rnEhg9cDMliA",
			"type": "freedraw",
			"x": 1523.3426068484127,
			"y": -105.3168640136717,
			"width": 145.64096304086547,
			"height": 118.97437462439902,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1964309400,
			"version": 22,
			"versionNonce": 1599891432,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647782371,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0255784254807168,
					0
				],
				[
					2.0511568509614335,
					0
				],
				[
					4.102501502403811,
					-2.0512977013220848
				],
				[
					4.102501502403811,
					-16.410240760216368
				],
				[
					4.102501502403811,
					-38.97437462439905
				],
				[
					0,
					-59.487163837139406
				],
				[
					-6.153846153846189,
					-81.02562537560095
				],
				[
					-14.359036959134755,
					-96.41026423527643
				],
				[
					-23.58980618990381,
					-108.71795654296875
				],
				[
					-35.89749849759619,
					-114.87180269681488
				],
				[
					-46.15384615384619,
					-117.94872577373798
				],
				[
					-55.38461538461547,
					-118.97437462439902
				],
				[
					-69.74365234375,
					-118.97437462439902
				],
				[
					-91.28211388221166,
					-118.97437462439902
				],
				[
					-112.8205754206731,
					-113.84615384615381
				],
				[
					-125.12826772836547,
					-105.64103346604566
				],
				[
					-134.35903695913476,
					-98.46153846153845
				],
				[
					-140.51288311298072,
					-92.30769230769232
				],
				[
					-141.53846153846166,
					-90.25639460637018
				],
				[
					-141.53846153846166,
					-90.25639460637018
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-141.53846153846166,
				-90.25639460637018
			]
		},
		{
			"id": "xreLTOtYojDwtKFxknNvK",
			"type": "freedraw",
			"x": 1204.3681852738935,
			"y": -250.95789747971736,
			"width": 56.41019381009619,
			"height": 65.64103346604568,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 552364696,
			"version": 33,
			"versionNonce": 1903704728,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647783458,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					7.179424579326906,
					-3.0769230769230944
				],
				[
					18.46153846153834,
					-4.102571927584137
				],
				[
					31.79480919471166,
					-10.256418081430297
				],
				[
					44.10250150240381,
					-16.41026423527643
				],
				[
					50.25634765625,
					-21.538461538461547
				],
				[
					53.333270733173094,
					-22.564110389122618
				],
				[
					56.41019381009619,
					-25.641033466045712
				],
				[
					56.41019381009619,
					-33.84615384615387
				],
				[
					54.35903695913453,
					-40
				],
				[
					49.23076923076928,
					-43.076923076923094
				],
				[
					42.05134465144215,
					-44.102571927584165
				],
				[
					30.769230769230717,
					-43.076923076923094
				],
				[
					23.58971228966334,
					-30.769230769230774
				],
				[
					18.46153846153834,
					-18.46153846153851
				],
				[
					17.43586613581715,
					-9.230769230769226
				],
				[
					19.487116887019283,
					4.102571927584137
				],
				[
					24.615384615384528,
					13.333341158353363
				],
				[
					25.640963040865472,
					16.41026423527643
				],
				[
					25.640963040865472,
					19.487187312199524
				],
				[
					24.615384615384528,
					19.487187312199524
				],
				[
					15.384615384615472,
					21.53846153846152
				],
				[
					9.230769230769283,
					21.53846153846152
				],
				[
					6.153846153846189,
					21.53846153846152
				],
				[
					3.0769230769230944,
					21.53846153846152
				],
				[
					0,
					21.53846153846152
				],
				[
					1.0255784254807168,
					18.461538461538453
				],
				[
					12.30769230769215,
					14.358966533954316
				],
				[
					25.640963040865472,
					11.28204345703125
				],
				[
					36.923076923076906,
					9.230769230769226
				],
				[
					40,
					9.230769230769226
				],
				[
					40,
					9.230769230769226
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				40,
				9.230769230769226
			]
		},
		{
			"id": "xFtcPVw8B4Hz2qfhvNeyD",
			"type": "freedraw",
			"x": 1247.4451083508166,
			"y": -244.80405132587123,
			"width": 15.384615384615472,
			"height": 16.41026423527643,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 758143720,
			"version": 19,
			"versionNonce": 1906988520,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647784181,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0255784254807168,
					-1.0256488506610424
				],
				[
					3.0769230769230944,
					-4.102571927584108
				],
				[
					4.102501502403811,
					-4.102571927584108
				],
				[
					4.102501502403811,
					-6.153846153846132
				],
				[
					6.153846153846189,
					-7.179495004507203
				],
				[
					7.179424579326906,
					-7.179495004507203
				],
				[
					7.179424579326906,
					-9.230769230769226
				],
				[
					9.230769230769283,
					-12.307692307692264
				],
				[
					12.307692307692378,
					-15.384615384615358
				],
				[
					9.230769230769283,
					-8.205120380108156
				],
				[
					8.205190805288339,
					-2.051274226261995
				],
				[
					6.153846153846189,
					0
				],
				[
					6.153846153846189,
					1.0256488506610708
				],
				[
					7.179424579326906,
					1.0256488506610708
				],
				[
					9.230769230769283,
					1.0256488506610708
				],
				[
					15.384615384615472,
					-3.076923076923066
				],
				[
					15.384615384615472,
					-3.076923076923066
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				15.384615384615472,
				-3.076923076923066
			]
		},
		{
			"id": "6M12Q95WEf_ofVXzX9zAU",
			"type": "freedraw",
			"x": 1273.086071391682,
			"y": -278.65020517202504,
			"width": 0.0001,
			"height": 0.0001,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 356277400,
			"version": 3,
			"versionNonce": 1538591128,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647784396,
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
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				0.0001,
				0.0001
			]
		},
		{
			"id": "VkCZGV6q2LcNpih2BEmMr",
			"type": "freedraw",
			"x": 1256.6758775815858,
			"y": -241.72712824894813,
			"width": 244.1025015024038,
			"height": 85.12822077824518,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 757857256,
			"version": 77,
			"versionNonce": 630083048,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647786086,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					4.102501502403811,
					-1.0256488506610708
				],
				[
					9.230769230769056,
					-4.102571927584137
				],
				[
					13.333270733173094,
					-10.256418081430297
				],
				[
					16.41019381009619,
					-15.384615384615358
				],
				[
					18.46153846153834,
					-19.487187312199524
				],
				[
					21.538461538461434,
					-19.487187312199524
				],
				[
					21.538461538461434,
					-21.538461538461547
				],
				[
					21.538461538461434,
					-22.56411038912256
				],
				[
					22.56403996394215,
					-22.56411038912256
				],
				[
					22.56403996394215,
					-20.512812687800476
				],
				[
					22.56403996394215,
					-12.30769230769232
				],
				[
					22.56403996394215,
					0
				],
				[
					22.56403996394215,
					6.15384615384616
				],
				[
					22.56403996394215,
					7.179495004507203
				],
				[
					22.56403996394215,
					3.076923076923066
				],
				[
					28.71788611778834,
					-6.15384615384616
				],
				[
					37.94865534855762,
					-12.30769230769232
				],
				[
					47.179424579326906,
					-16.410264235276486
				],
				[
					52.30769230769215,
					-16.410264235276486
				],
				[
					55.384615384615245,
					-18.461538461538453
				],
				[
					56.41019381009619,
					-18.461538461538453
				],
				[
					58.46153846153834,
					-17.43588961087744
				],
				[
					58.46153846153834,
					-14.358966533954344
				],
				[
					58.46153846153834,
					-11.28204345703125
				],
				[
					58.46153846153834,
					-8.205120380108184
				],
				[
					59.487116887019056,
					-2.0512742262620236
				],
				[
					62.56403996394215,
					0
				],
				[
					67.69230769230762,
					0
				],
				[
					74.87173227163453,
					-4.102571927584137
				],
				[
					81.02557842548072,
					-9.230769230769226
				],
				[
					86.15384615384619,
					-12.30769230769232
				],
				[
					87.1794245793269,
					-13.333341158353363
				],
				[
					92.30769230769215,
					-15.384615384615358
				],
				[
					96.41019381009619,
					-16.410264235276486
				],
				[
					101.53846153846143,
					-18.461538461538453
				],
				[
					105.64096304086524,
					-19.487187312199524
				],
				[
					107.69230769230762,
					-19.487187312199524
				],
				[
					104.61538461538453,
					-19.487187312199524
				],
				[
					94.35903695913453,
					-21.538461538461547
				],
				[
					88.20519080528834,
					-21.538461538461547
				],
				[
					80,
					-17.43588961087744
				],
				[
					78.97442157451906,
					-12.30769230769232
				],
				[
					76.9230769230769,
					-6.15384615384616
				],
				[
					73.84615384615381,
					1.0256488506610424
				],
				[
					73.84615384615381,
					4.102571927584137
				],
				[
					73.84615384615381,
					6.15384615384616
				],
				[
					76.9230769230769,
					6.15384615384616
				],
				[
					89.23076923076906,
					7.179495004507203
				],
				[
					101.53846153846143,
					0
				],
				[
					107.69230769230762,
					-3.0769230769230944
				],
				[
					113.84615384615381,
					-9.230769230769226
				],
				[
					116.9230769230769,
					-12.30769230769232
				],
				[
					116.9230769230769,
					-13.333341158353363
				],
				[
					112.8205754206731,
					-13.333341158353363
				],
				[
					101.53846153846143,
					-3.0769230769230944
				],
				[
					97.43596003605762,
					1.0256488506610424
				],
				[
					95.38461538461524,
					10.256418081430297
				],
				[
					96.41019381009619,
					12.307692307692292
				],
				[
					110.76923076923072,
					6.15384615384616
				],
				[
					129.23076923076906,
					-7.179495004507203
				],
				[
					147.69230769230762,
					-21.538461538461547
				],
				[
					163.0769230769231,
					-36.923076923076906
				],
				[
					166.1538461538462,
					-52.30769230769232
				],
				[
					166.1538461538462,
					-59.487187312199524
				],
				[
					160,
					-62.56411038912256
				],
				[
					144.61538461538453,
					-60.512812687800476
				],
				[
					126.15384615384619,
					-49.230769230769226
				],
				[
					118.97442157451906,
					-33.84615384615381
				],
				[
					113.84615384615381,
					-12.30769230769232
				],
				[
					116.9230769230769,
					4.102571927584137
				],
				[
					141.53846153846143,
					18.461538461538453
				],
				[
					200,
					22.564110389122618
				],
				[
					240,
					3.076923076923066
				],
				[
					244.1025015024038,
					-6.15384615384616
				],
				[
					244.1025015024038,
					-6.15384615384616
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				244.1025015024038,
				-6.15384615384616
			]
		},
		{
			"id": "QDWOaZtxRW7Y8jQvrg1Hz",
			"type": "freedraw",
			"x": 1650.5220314277396,
			"y": 127.50366445688115,
			"width": 67.69230769230762,
			"height": 6.153846153846075,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 2075387032,
			"version": 10,
			"versionNonce": 2119736552,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647788148,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.0256723257210751
				],
				[
					7.179424579326906,
					-3.0769230769230944
				],
				[
					16.41019381009619,
					-4.1025954026441696
				],
				[
					30.769230769230717,
					-6.153846153846075
				],
				[
					46.15384615384619,
					-6.153846153846075
				],
				[
					59.48711688701928,
					-6.153846153846075
				],
				[
					67.69230769230762,
					-6.153846153846075
				],
				[
					67.69230769230762,
					-6.153846153846075
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				67.69230769230762,
				-6.153846153846075
			]
		},
		{
			"id": "gZ6ZUacvCbp5OWCEFbgjr",
			"type": "freedraw",
			"x": 1725.3937636993742,
			"y": 98.78568443885234,
			"width": 32.820575420673094,
			"height": 32.82052847055286,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 649725336,
			"version": 16,
			"versionNonce": 1069495528,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647788592,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.0513446514423777,
					0
				],
				[
					8.205190805288566,
					0
				],
				[
					15.384615384615472,
					2.0512977013221416
				],
				[
					24.615384615384755,
					5.128220778245236
				],
				[
					29.74365234375,
					11.282066932091311
				],
				[
					32.820575420673094,
					16.410287710336547
				],
				[
					32.820575420673094,
					20.512836162860594
				],
				[
					28.718073918269283,
					26.66668231670667
				],
				[
					22.564227764423094,
					28.71798001802881
				],
				[
					17.435960036057622,
					31.794903094951906
				],
				[
					7.179612379807622,
					31.794903094951906
				],
				[
					4.102689302884755,
					32.82052847055286
				],
				[
					1.025766225961661,
					32.82052847055286
				],
				[
					1.025766225961661,
					32.82052847055286
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				1.025766225961661,
				32.82052847055286
			]
		},
		{
			"id": "Xm_2c4FDzXCD1y8HaK7mh",
			"type": "freedraw",
			"x": 1792.060492966201,
			"y": 141.86260751577544,
			"width": 175.38461538461547,
			"height": 87.17951847956726,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 111734168,
			"version": 112,
			"versionNonce": 250436840,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647791028,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-2.0512507512019056
				],
				[
					0,
					-5.128173828125
				],
				[
					0,
					-9.230769230769283
				],
				[
					0,
					-17.435866135817378
				],
				[
					3.0769230769230944,
					-24.61538461538464
				],
				[
					6.153846153846189,
					-32.820481520432736
				],
				[
					7.179424579326906,
					-33.846153846153925
				],
				[
					9.230769230769283,
					-35.89740459735583
				],
				[
					10.25634765625,
					-35.89740459735583
				],
				[
					13.333270733173094,
					-34.87177922175488
				],
				[
					19.487116887019283,
					-26.666635366586547
				],
				[
					25.640963040865472,
					-14.358943058894283
				],
				[
					27.69230769230785,
					-2.0512507512019056
				],
				[
					27.69230769230785,
					8.205143855168217
				],
				[
					27.69230769230785,
					13.333364633413453
				],
				[
					27.69230769230785,
					17.4359130859375
				],
				[
					27.69230769230785,
					19.487210787259528
				],
				[
					24.615384615384755,
					19.487210787259528
				],
				[
					20.512883112980717,
					13.333364633413453
				],
				[
					20.512883112980717,
					7.179518479567264
				],
				[
					20.512883112980717,
					-2.0512507512019056
				],
				[
					25.640963040865472,
					-8.205096905048094
				],
				[
					31.79480919471166,
					-14.358943058894283
				],
				[
					33.84615384615381,
					-15.384615384615358
				],
				[
					34.871732271634755,
					-17.435866135817378
				],
				[
					36.923076923076906,
					-17.435866135817378
				],
				[
					40,
					-17.435866135817378
				],
				[
					44.10250150240381,
					-11.282019981971189
				],
				[
					46.15384615384619,
					-5.128173828125
				],
				[
					46.15384615384619,
					2.0512977013221416
				],
				[
					47.179424579326906,
					10.256441556490358
				],
				[
					49.23076923076928,
					10.256441556490358
				],
				[
					53.333270733173094,
					7.179518479567264
				],
				[
					59.48711688701928,
					3.0769230769230944
				],
				[
					59.48711688701928,
					-2.0512507512019056
				],
				[
					62.56403996394238,
					-6.153846153846189
				],
				[
					64.61538461538476,
					-12.307692307692378
				],
				[
					64.61538461538476,
					-15.384615384615358
				],
				[
					65.64096304086547,
					-17.435866135817378
				],
				[
					65.64096304086547,
					-18.461538461538453
				],
				[
					67.69230769230785,
					-20.51278921274036
				],
				[
					67.69230769230785,
					-19.487163837139406
				],
				[
					67.69230769230785,
					-13.33331768329333
				],
				[
					67.69230769230785,
					-4.102548452524047
				],
				[
					67.69230769230785,
					2.0512977013221416
				],
				[
					67.69230769230785,
					4.1025954026441696
				],
				[
					68.71788611778857,
					5.128220778245122
				],
				[
					74.87173227163476,
					0
				],
				[
					80,
					-3.0769230769230944
				],
				[
					81.02557842548072,
					-6.153846153846189
				],
				[
					83.0769230769231,
					-9.230769230769283
				],
				[
					83.0769230769231,
					-11.282019981971189
				],
				[
					84.10250150240381,
					-11.282019981971189
				],
				[
					84.10250150240381,
					-4.102548452524047
				],
				[
					83.0769230769231,
					4.1025954026441696
				],
				[
					83.0769230769231,
					8.205143855168217
				],
				[
					83.0769230769231,
					13.333364633413453
				],
				[
					84.10250150240381,
					14.358990009014406
				],
				[
					86.15384615384619,
					16.410287710336547
				],
				[
					87.1794245793269,
					16.410287710336547
				],
				[
					89.23076923076928,
					16.410287710336547
				],
				[
					98.46153846153857,
					12.307692307692264
				],
				[
					107.69230769230785,
					6.153846153846075
				],
				[
					114.87173227163476,
					-3.0769230769230944
				],
				[
					120,
					-11.282019981971189
				],
				[
					127.1794245793269,
					-18.461538461538453
				],
				[
					133.3332707331731,
					-26.666635366586547
				],
				[
					139.48711688701928,
					-36.923076923076906
				],
				[
					142.56403996394238,
					-43.076923076923094
				],
				[
					145.64096304086547,
					-52.30769230769238
				],
				[
					145.64096304086547,
					-63.58971228966345
				],
				[
					145.64096304086547,
					-67.69230769230774
				],
				[
					144.61538461538476,
					-67.69230769230774
				],
				[
					141.53846153846166,
					-67.69230769230774
				],
				[
					135.38461538461547,
					-67.69230769230774
				],
				[
					126.15384615384619,
					-57.43586613581738
				],
				[
					120,
					-47.17947152944714
				],
				[
					118.97442157451928,
					-28.71793306790869
				],
				[
					115.89749849759619,
					-16.410240760216425
				],
				[
					113.84615384615381,
					-10.256394606370236
				],
				[
					113.84615384615381,
					-8.205096905048094
				],
				[
					113.84615384615381,
					-7.179471529447142
				],
				[
					114.87173227163476,
					-5.128173828125
				],
				[
					116.9230769230769,
					-5.128173828125
				],
				[
					127.1794245793269,
					-4.102548452524047
				],
				[
					139.48711688701928,
					-4.102548452524047
				],
				[
					147.69230769230785,
					-4.102548452524047
				],
				[
					160,
					-9.230769230769283
				],
				[
					166.1538461538462,
					-15.384615384615358
				],
				[
					172.30769230769238,
					-24.61538461538464
				],
				[
					173.3332707331731,
					-33.846153846153925
				],
				[
					173.3332707331731,
					-43.076923076923094
				],
				[
					175.38461538461547,
					-55.38461538461536
				],
				[
					174.35903695913476,
					-55.38461538461536
				],
				[
					172.30769230769238,
					-55.38461538461536
				],
				[
					168.20519080528857,
					-55.38461538461536
				],
				[
					155.8974984975962,
					-51.28201998197119
				],
				[
					149.74365234375,
					-48.205096905048094
				],
				[
					144.61538461538476,
					-42.051250751201906
				],
				[
					144.61538461538476,
					-35.89740459735583
				],
				[
					143.5898061899038,
					-28.71793306790869
				],
				[
					141.53846153846166,
					-20.51278921274036
				],
				[
					141.53846153846166,
					-13.33331768329333
				],
				[
					144.61538461538476,
					-8.205096905048094
				],
				[
					148.71788611778857,
					-4.102548452524047
				],
				[
					157.94865534855785,
					4.1025954026441696
				],
				[
					166.1538461538462,
					7.179518479567264
				],
				[
					170.25634765625,
					8.205143855168217
				],
				[
					170.25634765625,
					10.256441556490358
				],
				[
					170.25634765625,
					10.256441556490358
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				170.25634765625,
				10.256441556490358
			]
		},
		{
			"id": "4uCUEAPY-Fn5GAnr9uWpT",
			"type": "freedraw",
			"x": 1531.5476098532204,
			"y": -57.11172015850343,
			"width": 57.435772235576906,
			"height": 59.487210787259585,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 482661016,
			"version": 119,
			"versionNonce": 728371608,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1683647802227,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.025672325721132
				],
				[
					0,
					-3.0769230769230944
				],
				[
					-2.0511568509614335,
					-3.0769230769230944
				],
				[
					-4.102501502403811,
					-3.0769230769230944
				],
				[
					-5.128079927884528,
					-3.0769230769230944
				],
				[
					-7.179424579326906,
					-3.0769230769230944
				],
				[
					-8.205003004807622,
					-4.102595402644226
				],
				[
					-10.25634765625,
					-4.102595402644226
				],
				[
					-11.281926081730717,
					-4.102595402644226
				],
				[
					-13.333270733173094,
					-4.102595402644226
				],
				[
					-14.358849158653811,
					-4.102595402644226
				],
				[
					-17.435772235576906,
					-4.102595402644226
				],
				[
					-19.487116887019283,
					-4.102595402644226
				],
				[
					-22.564039963942378,
					-4.102595402644226
				],
				[
					-25.640963040865472,
					-2.0512977013221416
				],
				[
					-26.66654146634619,
					0
				],
				[
					-28.71788611778834,
					0
				],
				[
					-29.743464543269283,
					1.0256253756009528
				],
				[
					-31.794809194711434,
					3.0769230769230944
				],
				[
					-32.82038762019238,
					6.153846153846132
				],
				[
					-34.87173227163453,
					7.179471529447142
				],
				[
					-34.87173227163453,
					12.30769230769232
				],
				[
					-35.89731069711547,
					13.333317683293274
				],
				[
					-35.89731069711547,
					16.410240760216368
				],
				[
					-37.94865534855762,
					18.461538461538453
				],
				[
					-37.94865534855762,
					19.487163837139406
				],
				[
					-34.87173227163453,
					21.538461538461547
				],
				[
					-33.84615384615381,
					21.538461538461547
				],
				[
					-30.769230769230717,
					22.5640869140625
				],
				[
					-27.692307692307622,
					24.61538461538464
				],
				[
					-24.615384615384528,
					25.641009990985594
				],
				[
					-22.564039963942378,
					25.641009990985594
				],
				[
					-21.538461538461434,
					25.641009990985594
				],
				[
					-21.538461538461434,
					27.69230769230768
				],
				[
					-19.487116887019283,
					28.717933067908632
				],
				[
					-19.487116887019283,
					30.769230769230774
				],
				[
					-18.461538461538566,
					30.769230769230774
				],
				[
					-16.41019381009619,
					31.794856144831726
				],
				[
					-16.41019381009619,
					33.84615384615387
				],
				[
					-16.41019381009619,
					34.87177922175482
				],
				[
					-16.41019381009619,
					36.923076923076906
				],
				[
					-16.41019381009619,
					40
				],
				[
					-19.487116887019283,
					41.02562537560095
				],
				[
					-19.487116887019283,
					44.10254845252405
				],
				[
					-20.5126953125,
					44.10254845252405
				],
				[
					-20.5126953125,
					46.15384615384613
				],
				[
					-20.5126953125,
					47.179471529447085
				],
				[
					-20.5126953125,
					49.230769230769226
				],
				[
					-22.564039963942378,
					50.25639460637018
				],
				[
					-23.589618389423094,
					52.30769230769232
				],
				[
					-25.640963040865472,
					53.333317683293274
				],
				[
					-26.66654146634619,
					53.333317683293274
				],
				[
					-29.743464543269283,
					55.38461538461536
				],
				[
					-34.87173227163453,
					55.38461538461536
				],
				[
					-38.97423377403834,
					55.38461538461536
				],
				[
					-38.97423377403834,
					54.358943058894226
				],
				[
					-41.02557842548072,
					52.30769230769232
				],
				[
					-42.05115685096143,
					52.30769230769232
				],
				[
					-44.10250150240381,
					52.30769230769232
				],
				[
					-45.12807992788453,
					51.28201998197113
				],
				[
					-48.20500300480762,
					49.230769230769226
				],
				[
					-50.25634765625,
					48.205096905048094
				],
				[
					-51.28192608173072,
					48.205096905048094
				],
				[
					-51.28192608173072,
					46.15384615384613
				],
				[
					-51.28192608173072,
					45.128173828125
				],
				[
					-53.333270733173094,
					45.128173828125
				],
				[
					-53.333270733173094,
					42.051250751201906
				],
				[
					-54.35884915865381,
					40
				],
				[
					-54.35884915865381,
					38.97432767427887
				],
				[
					-54.35884915865381,
					35.897404597355774
				],
				[
					-54.35884915865381,
					33.84615384615387
				],
				[
					-52.30769230769238,
					33.84615384615387
				],
				[
					-49.23076923076928,
					30.769230769230774
				],
				[
					-46.15384615384619,
					30.769230769230774
				],
				[
					-44.10250150240381,
					30.769230769230774
				],
				[
					-43.076923076923094,
					30.769230769230774
				],
				[
					-41.02557842548072,
					30.769230769230774
				],
				[
					-40,
					30.769230769230774
				],
				[
					-37.94865534855762,
					30.769230769230774
				],
				[
					-36.923076923076906,
					30.769230769230774
				],
				[
					-34.87173227163453,
					30.769230769230774
				],
				[
					-33.84615384615381,
					30.769230769230774
				],
				[
					-31.794809194711434,
					30.769230769230774
				],
				[
					-30.769230769230717,
					30.769230769230774
				],
				[
					-28.71788611778834,
					29.743558443509585
				],
				[
					-27.692307692307622,
					29.743558443509585
				],
				[
					-25.640963040865472,
					27.69230769230768
				],
				[
					-22.564039963942378,
					27.69230769230768
				],
				[
					-21.538461538461434,
					26.666635366586547
				],
				[
					-18.461538461538566,
					26.666635366586547
				],
				[
					-16.41019381009619,
					24.61538461538464
				],
				[
					-15.384615384615472,
					23.589712289663453
				],
				[
					-10.25634765625,
					21.538461538461547
				],
				[
					-9.230769230769283,
					20.51278921274036
				],
				[
					-7.179424579326906,
					20.51278921274036
				],
				[
					-7.179424579326906,
					18.461538461538453
				],
				[
					-6.153846153846189,
					18.461538461538453
				],
				[
					-1.0255784254807168,
					17.43586613581732
				],
				[
					-1.0255784254807168,
					15.384615384615358
				],
				[
					-1.0255784254807168,
					14.358943058894226
				],
				[
					0,
					12.30769230769232
				],
				[
					2.0513446514423777,
					12.30769230769232
				],
				[
					2.0513446514423777,
					11.282019981971132
				],
				[
					2.0513446514423777,
					9.230769230769226
				],
				[
					3.0769230769230944,
					9.230769230769226
				],
				[
					3.0769230769230944,
					8.205096905048094
				],
				[
					3.0769230769230944,
					6.153846153846132
				],
				[
					2.0513446514423777,
					6.153846153846132
				],
				[
					1.0257662259614335,
					5.128173828125
				],
				[
					-1.0255784254807168,
					5.128173828125
				],
				[
					-1.0255784254807168,
					3.0769230769230944
				],
				[
					-2.0511568509614335,
					3.0769230769230944
				],
				[
					-4.102501502403811,
					2.0512507512019056
				],
				[
					-5.128079927884528,
					2.0512507512019056
				],
				[
					-7.179424579326906,
					2.0512507512019056
				],
				[
					0,
					0
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-7.179424579326906,
				2.0512507512019056
			]
		},
		{
			"id": "UzPH1Wj1vJZJJ3cqO3M7V",
			"type": "freedraw",
			"x": 1570.5220314277396,
			"y": -122.7527770996092,
			"width": 110.76923076923072,
			"height": 110.76923076923077,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 448027032,
			"version": 30,
			"versionNonce": 965928680,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1683647779564,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-6.153846153846189,
					-1.0256253756009528
				],
				[
					-16.41019381009619,
					-4.102548452524047
				],
				[
					-34.871732271634755,
					-6.153846153846132
				],
				[
					-43.076923076923094,
					-6.153846153846132
				],
				[
					-44.10250150240381,
					-2.0512507512019056
				],
				[
					-43.076923076923094,
					7.179518479567321
				],
				[
					-36.923076923076906,
					16.410287710336547
				],
				[
					-30.769230769230717,
					24.61538461538464
				],
				[
					-24.615384615384755,
					34.871826171875
				],
				[
					-24.615384615384755,
					46.15384615384613
				],
				[
					-23.58980618990381,
					59.48721078725964
				],
				[
					-28.717886117788566,
					77.9487492487981
				],
				[
					-44.10250150240381,
					92.30769230769232
				],
				[
					-61.53846153846166,
					99.48721078725964
				],
				[
					-71.79480919471166,
					104.61538461538464
				],
				[
					-74.87173227163476,
					104.61538461538464
				],
				[
					-89.23076923076928,
					82.05129770132214
				],
				[
					-89.23076923076928,
					78.97437462439905
				],
				[
					-80,
					64.61538461538464
				],
				[
					-69.74365234375,
					61.53846153846155
				],
				[
					-46.15384615384619,
					54.358990009014406
				],
				[
					-14.359036959134755,
					45.12822077824518
				],
				[
					10.25634765625,
					33.84615384615387
				],
				[
					21.538461538461434,
					27.69230769230768
				],
				[
					20.512883112980717,
					21.538461538461547
				],
				[
					14.359036959134528,
					18.461538461538453
				],
				[
					14.359036959134528,
					18.461538461538453
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				14.359036959134528,
				18.461538461538453
			]
		},
		{
			"id": "Qx7-tCbYh8ppxzv1QOWxw",
			"type": "freedraw",
			"x": 1570.5220314277396,
			"y": -72.49633554311879,
			"width": 40,
			"height": 44.10254845252405,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 20,
			"groupIds": [],
			"roundness": null,
			"seed": 178346904,
			"version": 50,
			"versionNonce": 1577156584,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1683647797534,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-3.0769230769230944,
					-1.0256723257211888
				],
				[
					-6.153846153846189,
					-4.102595402644283
				],
				[
					-10.25634765625,
					-4.102595402644283
				],
				[
					-16.41019381009619,
					-4.102595402644283
				],
				[
					-19.487116887019283,
					-4.102595402644283
				],
				[
					-24.615384615384755,
					0
				],
				[
					-27.69230769230785,
					0
				],
				[
					-30.769230769230717,
					3.0769230769230376
				],
				[
					-30.769230769230717,
					6.153846153846132
				],
				[
					-30.769230769230717,
					9.230769230769226
				],
				[
					-27.69230769230785,
					12.307692307692264
				],
				[
					-26.666729266826906,
					13.333317683293217
				],
				[
					-23.58980618990381,
					13.333317683293217
				],
				[
					-18.461538461538566,
					15.384615384615358
				],
				[
					-12.307692307692378,
					18.461538461538453
				],
				[
					-9.230769230769283,
					19.487163837139406
				],
				[
					-6.153846153846189,
					22.5640869140625
				],
				[
					-5.128267728365472,
					22.5640869140625
				],
				[
					-5.128267728365472,
					25.641009990985538
				],
				[
					-5.128267728365472,
					27.69230769230768
				],
				[
					-6.153846153846189,
					30.769230769230717
				],
				[
					-9.230769230769283,
					33.84615384615381
				],
				[
					-10.25634765625,
					34.871779221754764
				],
				[
					-12.307692307692378,
					34.871779221754764
				],
				[
					-15.384615384615472,
					34.871779221754764
				],
				[
					-18.461538461538566,
					34.871779221754764
				],
				[
					-21.53846153846166,
					33.84615384615381
				],
				[
					-24.615384615384755,
					30.769230769230717
				],
				[
					-27.69230769230785,
					29.743558443509585
				],
				[
					-28.717886117788566,
					29.743558443509585
				],
				[
					-31.79480919471166,
					26.66663536658649
				],
				[
					-36.923076923076906,
					26.66663536658649
				],
				[
					-40,
					24.615384615384585
				],
				[
					-35.89749849759619,
					20.51278921274036
				],
				[
					-33.84615384615381,
					14.358943058894226
				],
				[
					-30.769230769230717,
					12.307692307692264
				],
				[
					-30.769230769230717,
					11.282019981971132
				],
				[
					-26.666729266826906,
					6.153846153846132
				],
				[
					-20.512883112980717,
					3.0769230769230376
				],
				[
					-17.43596003605785,
					-1.0256723257211888
				],
				[
					-14.359036959134755,
					-3.0769230769230944
				],
				[
					-11.282113882211661,
					-4.102595402644283
				],
				[
					-9.230769230769283,
					-6.153846153846189
				],
				[
					-5.128267728365472,
					-9.230769230769283
				],
				[
					0,
					0
				]
			],
			"pressures": [],
			"simulatePressure": true,
			"lastCommittedPoint": [
				-5.128267728365472,
				-9.230769230769283
			]
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#000000",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": -230.77837908398965,
		"scrollY": 479.6758540226861,
		"zoom": {
			"value": 0.65
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