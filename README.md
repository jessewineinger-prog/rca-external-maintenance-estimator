RCA Residential Services - External Maintenance Vendor Markup & Proposal Estimator

A dedicated, lightweight web application built for property managers and general contractors to streamline third-party subcontractor pricing, markup calculations, audit verification against regional market benchmarks, and client proposal generation.

🚀 Key Features

Pre-Configured Subcontractor Roster:

Alphabetically sorted roster of verified trade partners (ARS, Dave's Tree & Lawn, Erik Nelson, On A Budget / Kelly Beck, Mac's Plumbing & Drains, Molina Used Appliances, Indy Voltage, Matthews Appliance, Michelle Cornelison, Turner Appliance, Artisan Plumbing, Gurney Bush, C&S Ideal Renovations, American Earthworks, Jaime Home Improvement, G&G Construction, A Bary Comfortable Climate, plus Custom Subcontractors).

Selecting any vendor automatically filters work classifications to their authorized specialties and applies their pre-negotiated baseline markup.

11 Modular Trade Classifications:

🚰 Plumbing

⚡ Electrical

❄️ HVAC

🏡 Roofing / Construction

🌳 Tree Services

🏠 Turnover

🧹 Cleaning Services

🎨 Drywall / Painting

🪵 Flooring

🔨 General / Handyman

⚙️ Used Appliance & Repair

Hierarchical Scope Quantification Engine:

Granular, expandable repair and replacement task trees (e.g., Gas vs. Electric Furnaces, AC Condensers, Heat Pumps, Sewer/Drain Cabling, Tree Trimming/Felling, etc.).

Quantified tasks automatically aggregate into a real-time Regional Market Baseline / Retail Benchmark.

Strategic Pricing Optimization Modes:

Sweet Spot (Balanced): Splits the spread between your marked-up vendor floor and retail market baseline, capturing higher margins while proving client savings.

Max Client Value: Optimizes for aggressive client savings (~12% below market retail).

Max Profit: Captures maximum margin right beneath the retail baseline limit.

Cost-Plus Floor: Strict markup on subcontractor cost (10%–30%).

Formula & Proposal Integrity:

Strict factor-of-11 client billable pricing engine.

Flat $25.00 Admin Service Fee toggle (factored before or after rounding).

One-click copy formatted proposals ready to paste into owner approval emails or property management software (Buildium, AppFolio, etc.).

Central Indiana location and tax rate toolbar with automatic ZIP-to-County detection.

🛠️ File Structure

The entire application runs as a single, standalone HTML file:

index.html (or external_estimator.html): Self-contained HTML5, Tailwind CSS via CDN, and Vanilla JavaScript. Zero build steps, npm packages, or server runtimes required.

💻 How to Run Locally

Clone or download this repository.

Double-click index.html to open it in any modern browser (Chrome, Edge, Safari, Firefox).

No web server or installation required.

🌐 Deploying to GitHub Pages

In your GitHub repository, navigate to Settings > Pages.

Under Source, choose Deploy from a branch.

Under Branch, select main (or master) and / (root), then click Save.

Within 1–2 minutes, your estimator will be live at:
https://<your-github-username>.github.io/<repository-name>/
