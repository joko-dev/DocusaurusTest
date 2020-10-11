import Mermaid from '@theme/Mermaid';

---
id: doc2
title: Document Number 2
---

This is a link to [another document.](doc3.md) This is a link to an [external page.](http://www.example.com/)

<Mermaid chart={`
	graph LR;
		A-->B;
		B-->C;
		B-->D[plop lanflz eknlzeknfz];
`}/>
