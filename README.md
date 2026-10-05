# ExtremoScan 🧬🔍

**ExtremoScan** is an automated, lightweight bioinformatics pipeline built in Python to scan protein sequences for structural motifs, electrostatic shielding clusters, and biochemical signatures (such as basic residue clusters and proline-rich regions). Designed for extremophile and protein sequence analysis, it automates multi-FASTA file ingestion, regex-based motif mining, structured CSV data aggregation, and comparative visualization.

---

## 🚀 Key Features

* **Automated Multi-FASTA Ingestion:** Streams and parses protein sequence files efficiently using BioPython.
* **Targeted Multi-Motif Mining:** Scans sequences for customizable biochemical signatures (e.g., basic clusters like [KR]{3,} and structural motifs) using optimized regular expressions.
* **Structured Data Export:** Automatically aggregates and persists match coordinates, lengths, and protein IDs into master CSV files.
* **Automated Visualization:** Generates single-protein frequency metrics and grouped multi-motif comparative charts via Matplotlib.
* **CI/CD Integration:** Includes GitHub Actions workflows for automated pipeline execution and testing.

---

## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **Libraries:** 
  * [BioPython](https://biopython.org/) (Sequence parsing)
  * [Pandas](https://pandas.pydata.org/) (Data manipulation & CSV export)
  * [Matplotlib](https://matplotlib.org/) (Data visualization & frequency charts)

---

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/riddhikad9b-ux/ExtremoScan.git](https://github.com/riddhikad9b-ux/ExtremoScan.git)
   cd ExtremoScan

```

2. **Install dependencies:**
```bash
pip install -r requirements.txt

```


3. **Run the pipeline:**
```bash
python motif_scanner.py

```



---

## 📊 Output Examples

* **`master_motif_scan_results.csv`**: Consolidated tabular records containing Protein IDs, matched sequences, start/end positions, and motif lengths.
* **`multi_motif_comparison_chart.png`**: Visual comparison graph showing motif distribution across target protein sequences.

---

## 👤 Author

* **Riddhika** — *Initial Work & Pipeline Architecture*

```

```
