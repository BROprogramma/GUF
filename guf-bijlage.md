Bijlage: Voorbeelden materiële historie
---------------------------------------

Op 01-01-2021 wordt een vergunning voor grondwaterontrekking verleend met
ingangsdatum 01-02-2021 is. In de vergunning is geen einddatum opgenomen. De
grondwaterontrekking bestaat uit een installatie met 1 grondwaterontrekkingsput.
In de LV BRO worden de volgende objecten opgevoerd.

| **Object**               | **ID** | **Voorkomen** | **beginTijd** | **eindTijd** | **Begin Geldigheid** | **Eind Geldigheid** |
|--------------------------|--------|---------------|---------------|--------------|----------------------|---------------------|
| Grondwatergebruiksysteem | 001    | 1             | 01-02-2021    | «leeg»       | 01-02-2021           | «leeg»              |
| Recht grondwatergebruik  | 101    | 1             | 01-02-2021    | «leeg»       | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie       | 201    | 1             | 01-02-2021    | «leeg»       | n.v.t.               | n.v.t.              |
| Ontwerpput               | 301    | 1             | 01-02-2021    | «leeg»       | n.v.t.               | n.v.t.              |

Per 01-03-2021 wordt een wijzigingsvergunning verleend waarbij de maximale
putcapaciteit van de ontwerpinstallatie is verhoogd. In de BRO wordt bij het
Grondwatergebruiksysteem een nieuw Recht grondwatergebruik geregistreerd, en een
nieuwe ontwerpinstallatie en ontwerpput. Het vorige recht, de vorige installatie
en de vorige put krijgen een eindtijd.

| **Object**                   | **ID**  | **Voorkomen** | **beginTijd**  | **eindTijd** | **Begin Geldigheid** | **Eind Geldigheid** |
|------------------------------|---------|---------------|----------------|--------------|----------------------|---------------------|
| Grondwatergebruiksysteem     | 001     | 1             | 01-02-2021     | «leeg»       | 01-02-2021           | 01-03-2021          |
| **Grondwatergebruiksysteem** | **001** | **2**         | **01-02-2021** | **«leeg»**   | **01-03-2021**       | **«leeg»**          |
| Recht grondwatergebruik      | 101     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| **Recht grondwatergebruik**  | **102** | **1**         | **01-03-2021** | **«leeg»**   | **n.v.t.**           | **n.v.t.**          |
| Ontwerpinstallatie           | 201     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| **Ontwerpinstallatie**       | **202** | **1**         | **01-03-2021** | **«leeg»**   | **n.v.t.**           | **n.v.t.**          |
| Ontwerpput                   | 301     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| **Ontwerpput**               | **302** | **1**         | **01-03-2021** | **«leeg»**   | **n.v.t.**           | **n.v.t.**          |

Per 01-06-2021 is de put gerealiseerd. In de BRO wordt een gerealiseerde
installatie en gerealiseerde put opgenomen. De gerealiseerde installatie en put
worden toegevoegd aan het Grondwatergebruiksysteem dat een nieuw voorkomen
krijgt.

| **Object**                    | **ID**  | **Voorkomen** | **beginTijd**  | **eindTijd** | **Begin Geldigheid** | **Eind Geldigheid** |
|-------------------------------|---------|---------------|----------------|--------------|----------------------|---------------------|
| Grondwatergebruiksysteem      | 001     | 1             | 01-02-2021     | «leeg»       | 01-02-2021           | 01-03-2021          |
| Grondwatergebruiksysteem      | 001     | 2             | 01-02-2021     | «leeg»       | 01-03-2021           | 01-06-2021          |
| **Grondwatergebruiksysteem**  | **001** | **3**         | **01-02-2021** | **«leeg»**   | **01-06-2021**       | **«leeg»**          |
| Recht grondwatergebruik       | 101     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Recht grondwatergebruik       | 102     | 1             | 01-03-2021     | «leeg»       | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 201     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 202     | 1             | 01-03-2021     | «leeg»       | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 301     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 302     | 1             | 01-03-2021     | «leeg»       | n.v.t.               | n.v.t.              |
| **Gerealiseerde installatie** | **401** | **1**         | **01-06-2021** | **«leeg»**   | **01-06-2021**       | **«leeg»**          |
| **Gerealiseerde put**         | **501** | **1**         | **01-06-2021** | **«leeg»**   | **01-06-2021**       | **«leeg»**          |

Per 01-09-2021 wordt een wijzigingsvergunning verleend voor het toevoegen van
een extra put aan de installatie. De wijzigingsvergunning wordt toegevoegd aan
het grondwatergebruikssysteem. Samen met dit nieuwe Recht Grondwatergebruik
wordt een nieuwe ontwerpinstallatie en beide ontwerpputten geregistreerd in de
BRO.

| **Object**                   | **ID**  | **Voorkomen** | **beginTijd**  | **eindTijd** | **Begin Geldigheid** | **Eind Geldigheid** |
|------------------------------|---------|---------------|----------------|--------------|----------------------|---------------------|
| Grondwatergebruiksysteem     | 001     | 1             | 01-02-2021     | «leeg»       | 01-02-2021           | 01-03-2021          |
| Grondwatergebruiksysteem     | 001     | 2             | 01-02-2021     | «leeg»       | 01-03-2021           | 01-06-2021          |
| Grondwatergebruiksysteem     | 001     | 3             | 01-02-2021     | «leeg»       | 01-06-2021           | 01-09-2021          |
| **Grondwatergebruiksysteem** | **001** | **4**         | **01-02-2021** | **«leeg»**   | **01-09-2021**       | **«leeg»**          |
| Recht grondwatergebruik      | 101     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Recht grondwatergebruik      | 102     | 1             | 01-03-2021     | 01-09-2021   | n.v.t.               | n.v.t.              |
| **Recht grondwatergebruik**  | **103** | **1**         | **01-09-2021** | **«leeg»**   | **n.v.t.**           | **n.v.t.**          |
| Ontwerpinstallatie           | 201     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie           | 202     | 1             | 01-03-2021     | 01-09-2021   | n.v.t.               | n.v.t.              |
| **Ontwerpinstallatie**       | **203** | **1**         | **01-09-2021** | **«leeg»**   | n.v.t.               | n.v.t.              |
| Ontwerpput                   | 301     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Ontwerpput                   | 302     | 1             | 01-03-2021     | 01-09-2021   | n.v.t.               | n.v.t.              |
| **Ontwerpput**               | **303** | **1**         | **01-09-2021** | **«leeg»**   | **n.v.t.**           | **n.v.t.**          |
| **Ontwerpput**               | **304** | **1**         | **01-09-2021** | **«leeg»**   | **n.v.t.**           | **n.v.t.**          |
| Gerealiseerde installatie    | 401     | 1             | 01-06-2021     | «leeg»       | 01-06-2021           | «leeg»              |
| Gerealiseerde put            | 501     | 1             | 01-06-2021     | «leeg»       | 01-06-2021           | «leeg»              |

Per 01-10-2021 is de extra ontwerpput gerealiseerd en wordt de gerealiseerde put
toegevoegd aan de gerealiseerde installatie in de BRO.

| **Object**                    | **ID**  | **Voorkomen** | **beginTijd**  | **eindTijd** | **Begin Geldigheid** | **Eind Geldigheid** |
|-------------------------------|---------|---------------|----------------|--------------|----------------------|---------------------|
| Grondwatergebruiksysteem      | 001     | 1             | 01-02-2021     | «leeg»       | 01-02-2021           | 01-03-2021          |
| Grondwatergebruiksysteem      | 001     | 2             | 01-02-2021     | «leeg»       | 01-03-2021           | 01-06-2021          |
| Grondwatergebruiksysteem      | 001     | 3             | 01-02-2021     | «leeg»       | 01-06-2021           | 01-09-2021          |
| Grondwatergebruiksysteem      | 001     | 4             | 01-02-2021     | «leeg»       | 01-09-2021           | «leeg»              |
| Recht grondwatergebruik       | 101     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Recht grondwatergebruik       | 102     | 1             | 01-03-2021     | 01-09-2021   | n.v.t.               | n.v.t.              |
| Rechtgrondwatergebruik        | 103     | 1             | 01-09-2021     | «leeg»       | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 201     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 202     | 1             | 01-03-2021     | 01-09-2021   | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 203     | 1             | 01-09-2021     | «leeg»       | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 301     | 1             | 01-02-2021     | 01-03-2021   | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 302     | 1             | 01-03-2021     | 01-09-2021   | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 303     | 1             | 01-09-2021     | «leeg»       | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 304     | 1             | 01-09-2021     | «leeg»       | n.v.t.               | n.v.t.              |
| Gerealiseerde installatie     | 401     | 1             | 01-06-2021     | «leeg»       | 01-06-2021           | 1-10-2021           |
| **Gerealiseerde installatie** | **401** | **2**         | **01-06-2021** | **«leeg»**   | **1-10-2021**        | **«leeg»**          |
| Gerealiseerde put             | 501     | 1             | 01-06-2021     | «leeg»       | 01-06-2021           | «leeg»              |
| **Gerealiseerde put**         | **502** | **1**         | **01-10-2021** | **«leeg»**   | **01-10-2021**       | **«leeg»**          |

Per 01-01-2022 worden de gerealiseerde installatie en putten buiten werking
gesteld. De vergunning blijft wel geldig. In de BRO worden de gerealiseerde
installatie en putten beëindigd.

| **Object**                    | **ID** | **Voorkomen** | **beginTijd** | **eindTijd**   | **Begin Geldigheid** | **Eind Geldigheid** |
|-------------------------------|--------|---------------|---------------|----------------|----------------------|---------------------|
| Grondwatergebruiksysteem      | 001    | 1             | 01-02-2021    | «leeg»         | 01-02-2021           | 01-03-2021          |
| Grondwatergebruiksysteem      | 001    | 2             | 01-02-2021    | «leeg»         | 01-03-2021           | 01-06-2021          |
| Grondwatergebruiksysteem      | 001    | 3             | 01-02-2021    | «leeg»         | 01-06-2021           | 01-09-2021          |
| Grondwatergebruiksysteem      | 001    | 4             | 01-02-2021    | «leeg»         | 01-09-2021           | «leeg»              |
| Recht grondwatergebruik       | 101    | 1             | 01-02-2021    | 01-03-2021     | n.v.t.               | n.v.t.              |
| Recht grondwatergebruik       | 102    | 1             | 01-03-2021    | 01-09-2021     | n.v.t.               | n.v.t.              |
| Rechtgrondwatergebruik        | 103    | 1             | 01-09-2021    | «leeg»         | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 201    | 1             | 01-02-2021    | 01-03-2021     | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 202    | 1             | 01-03-2021    | 01-09-2021     | n.v.t.               | n.v.t.              |
| Ontwerpinstallatie            | 203    | 1             | 01-09-2021    | «leeg»         | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 301    | 1             | 01-02-2021    | 01-03-2021     | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 302    | 1             | 01-03-2021    | 01-09-2021     | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 303    | 1             | 01-09-2021    | «leeg»         | n.v.t.               | n.v.t.              |
| Ontwerpput                    | 304    | 1             | 01-09-2021    | «leeg»         | n.v.t.               | n.v.t.              |
| Gerealiseerde installatie     | 401    | 1             | 01-06-2021    | «leeg»         | 01-06-2021           | 1-10-2021           |
| **Gerealiseerde installatie** | 401    | 2             | 01-06-2021    | **01-01-2022** | 1-10-2021            | **01-01-2022**      |
| **Gerealiseerde put**         | 501    | 1             | 01-06-2021    | **01-01-2022** | 01-06-2021           | **01-01-2022**      |
| **Gerealiseerde put**         | 502    | 1             | 01-10-2021    | **01-01-2022** | 01-10-2021           | **01-01-2022**      |
