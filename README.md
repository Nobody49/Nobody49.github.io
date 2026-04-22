# Nobody49.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luca Kayser | Medical Student & Researcher</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #34495e;
            --accent-color: #2980b9;
            --background-color: #f8f9fa;
            --text-color: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        header {
            text-align: center;
            margin-bottom: 50px;
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 30px;
        }

        h1 {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.5rem;
            color: var(--secondary-color);
            font-weight: 300;
            margin-bottom: 20px;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            font-size: 0.9rem;
        }

        .contact-info a {
            color: var(--accent-color);
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        section {
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        h3 {
            color: var(--primary-color);
            border-bottom: 1px solid #eee;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 1.3rem;
        }

        .entry {
            margin-bottom: 25px;
        }

        .entry:last-child {
            margin-bottom: 0;
        }

        .entry-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 10px;
        }

        .entry-title {
            font-weight: bold;
            color: var(--primary-color);
            font-size: 1.1rem;
        }

        .entry-date {
            color: #7f8c8d;
            font-size: 0.9rem;
        }

        .entry-subtitle {
            font-style: italic;
            color: var(--secondary-color);
            margin-bottom: 10px;
        }

        ul {
            margin-left: 20px;
            list-style-type: square;
        }

        li {
            margin-bottom: 8px;
            font-size: 0.95rem;
        }

        .skills {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        .skill-tag {
            background: #e1f0fa;
            color: var(--accent-color);
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
        }

        @media (max-width: 600px) {
            .entry-header {
                flex-direction: column;
            }
            .entry-date {
                margin-top: 5px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>Luca Kayser [cite: 1]</h1>
        <h2>Medical Student [cite: 2]</h2>
        <div class="contact-info">
            <span>Germany [cite: 7]</span> |
            <a href="mailto:lucakayser@uchicago.edu">lucakayser@uchicago.edu [cite: 4]</a> |
            <a href="mailto:luca.kayser@studio.unibo.it">luca.kayser@studio.unibo.it [cite: 5]</a> |
            <a href="tel:+4917669394469">+49 176 69394469 [cite: 6]</a> |
            <a href="https://www.linkedin.com/in/luca-kayser-b93237228" target="_blank">LinkedIn [cite: 7]</a>
        </div>
        <div class="skills" style="justify-content: center; margin-top: 15px;">
            <span class="skill-tag">English [cite: 3]</span>
            <span class="skill-tag">German [cite: 3]</span>
            <span class="skill-tag">French [cite: 3]</span>
            <span class="skill-tag">Italian [cite: 3]</span>
        </div>
    </header>

    <section id="education">
        <h3>Education [cite: 8]</h3>
        
        <div class="entry">
            <div class="entry-header">
                <div class="entry-title">University of Bologna [cite: 10]</div>
                <div class="entry-date">2021-now (currently 5th year out of 6) [cite: 12]</div>
            </div>
            <div class="entry-subtitle">MD, Medicine and Surgery [cite: 11]</div>
        </div>

        <div class="entry">
            <div class="entry-header">
                <div class="entry-title">Fern Universitaet Hagen [cite: 13]</div>
                <div class="entry-date">2023-now [cite: 15]</div>
            </div>
            <div class="entry-subtitle">B.A. Mathematics [cite: 14]</div>
        </div>

        <div class="entry">
            <div class="entry-header">
                <div class="entry-title">Aarhus University [cite: 16]</div>
                <div class="entry-date">August 2023 [cite: 18]</div>
            </div>
            <div class="entry-subtitle">Summer Course in CRISPR-Cas (DESIGN) COST-scholarship [cite: 17]</div>
        </div>
    </section>

    <section id="experience">
        <h3>Experience [cite: 9]</h3>

        <div class="entry">
            <div class="entry-header">
                <div class="entry-title">MDC BIMSB Berlin - Junker Lab [cite: 28]</div>
                <div class="entry-date">October 2025 - January 2026 [cite: 29]</div>
            </div>
            <div class="entry-subtitle">Intern [cite: 29]</div>
            <ul>
                <li>Worked on Neuroblastoma Organoid culture [cite: 30]</li>
                <li>Analysis spatial transcriptomics (OpenST) [cite: 31]</li>
                <li>Developed deep knowledge of lineage tracing technologies [cite: 32]</li>
                <li>Developed a new technique to culture Neuroblastoma organoids in different Matrices for longterm culture and subsequent Cryosectioning [cite: 33, 34]</li>
            </ul>
        </div>

        <div class="entry">
            <div class="entry-header">
                <div class="entry-title">Miao Lab University of Chicago (SAM Scholarship) [cite: 23]</div>
                <div class="entry-date">October 2023 - March 2024 [cite: 24]</div>
            </div>
            <div class="entry-subtitle">Visiting Student [cite: 24]</div>
            <ul>
                <li>Learned Co-Culture, T-Cell extraction (from mice), Lentiviral Transduction, Flow Cytometry (+Staining), Tumor grafting [cite: 25]</li>
                <li>Learned about Cancer Immunology and specifically MLRs like MAL and MAL2/HPV+ HNSCC/ (c)MYC/Sox2 and Analysis of Genomic data [cite: 25]</li>
            </ul>
        </div>

        <div class="entry">
            <div class="entry-header">
                <div class="entry-title">Charite Berlin Neurosurgery [cite: 26]</div>
                <div class="entry-date">July 2023 [cite: 27]</div>
            </div>
            <div class="entry-subtitle">Clinical Internship [cite: 27]</div>
        </div>

        <div class="entry">
            <div class="entry-header">
                <div class="entry-title">Ratti Lab University of Bologna [cite: 19]</div>
                <div class="entry-date">2022 - 2023 [cite: 20]</div>
            </div>
            <div class="entry-subtitle">Intern [cite: 20]</div>
            <ul>
                <li>Learned Gel-Electrophoresis, Western Blot, qPCR, Cell Culture, Blood separation [cite: 21]</li>
                <li>Research in Glioma, Mingie and Myelodysplastic Syndrome [cite: 22]</li>
                <li>Learned to work in a team of researchers and to execute experiments and balance autonomy with support from senior researchers [cite: 22]</li>
            </ul>
        </div>
    </section>

</div>

</body>
</html>
