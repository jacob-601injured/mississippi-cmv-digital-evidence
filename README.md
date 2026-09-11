# Mississippi Commercial Truck Digital Evidence Guide

An attorney-edited, source-linked reference to electronic evidence that may exist after an 18-wheeler or commercial-vehicle collision in Mississippi, including electronic logging devices (ELDs), advanced driver-assistance systems (ADAS), telematics gateways, GPS, accelerometer data, safety events, dispatch records, and federally required carrier records.

Maintained by **Jones Law P.A. / Jones Law Group** in Jackson, Mississippi. Attorney editor: **Baskin L. Jones, Esq., MS Bar No. 103589**.

## Why this project exists

Commercial vehicles can contain or transmit information through several separate systems. Calling every system an “ECM” obscures important differences:

- an ELD records hours-of-service information;
- an engine or vehicle control module may contain diagnostic or event information;
- an ADAS may combine radar, camera, braking, and lane inputs;
- a telematics gateway may transmit GPS, accelerometer, engine, or safety-event information to a cloud account;
- a fleet may separately possess dash-camera, dispatch, maintenance, training, and safety-portal records.

This dataset helps lawyers, investigators, engineers, researchers, carriers, and the public identify questions to ask. It does **not** assert that a particular truck has a particular system or that a listed field is retrievable in every configuration.

## Files

- `data/mississippi_cmv_digital_evidence_dictionary.json` — source-linked systems and records dictionary.
- `data/synthetic_scenarios.json` — invented teaching scenarios, unmistakably labeled synthetic.
- `dataset-metadata.json` — Kaggle publication metadata scaffold.
- `CITATION.cff` — machine-readable dataset citation.
- `LICENSE` — CC BY 4.0 license text.

## Key limitations

- Product generation, hardware, firmware, fleet subscriptions, vehicle configuration, data settings, connectivity, power, and custodian practices affect what exists.
- A public product page describes capabilities; it does not prove that data was recorded, retained, downloaded, or available in any collision.
- Federal minimum record-retention rules do not establish a safe waiting period for a preservation request. Some operational data may be overwritten or deleted sooner; other records may be kept longer.
- The synthetic scenarios are not anonymized cases, outcomes, firm statistics, or evidence that any violation occurred.
- This is general educational information, not legal advice, an evidence opinion, or a substitute for a qualified inspection and case-specific discovery.

## Suggested repository metadata

**Repository:** `mississippi-cmv-digital-evidence`  
**Description:** Source-linked ELD, ADAS, telematics, and carrier-record evidence guide for Mississippi commercial-truck crashes.  
**Topics:** `mississippi`, `commercial-vehicles`, `truck-safety`, `traffic-safety`, `legal-research`, `telematics`, `eld`, `adas`, `open-data`

## Sources and corrections

Each record includes its source URL and verification date. Product and regulatory information changes. Please submit corrections with the affected `record_id`, supporting source, and access date.

## About Jones Law

Jones Law P.A. / Jones Law Group is a Mississippi personal-injury practice based at 3417 North State Street, Jackson, Mississippi 39216. Telephone: (601) 272-2406. Canonical website: [Injured in Mississippi](https://www.injuredinmississippi.com/).

## Also on Kaggle

[Mississippi CMV Digital Evidence Guide](https://www.kaggle.com/datasets/jacob601injured/mississippi-cmv-digital-evidence-guide)

## License

Original annotations are licensed under [CC BY 4.0](LICENSE).

