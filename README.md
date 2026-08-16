<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Kavish Indoria | Product Safety & Regulatory Affairs</title>

    <meta name="description" content="Kavish Indoria – Product Safety, Regulatory Affairs, Conformity Assessment, Certification, Market Access and NPI & NPD professional.">

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.7;
            color: #1f2937;
            background: #f8fafc;
        }

        a {
            text-decoration: none;
        }

        .container {
            width: 90%;
            max-width: 1150px;
            margin: auto;
        }

        /* Navigation */

        nav {
            background: #ffffff;
            border-bottom: 1px solid #e5e7eb;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .nav-container {
            max-width: 1150px;
            width: 90%;
            margin: auto;
            height: 70px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 21px;
            font-weight: 700;
            color: #111827;
        }

        .nav-links {
            display: flex;
            gap: 28px;
        }

        .nav-links a {
            color: #4b5563;
            font-size: 14px;
            font-weight: 600;
        }

        .nav-links a:hover {
            color: #0f766e;
        }

        /* Hero */

        .hero {
            background: #ffffff;
            padding: 105px 0 95px;
        }

        .hero-content {
            max-width: 950px;
        }

        .eyebrow {
            color: #0f766e;
            font-size: 14px;
            font-weight: 700;
            letter-spacing: 2px;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-size: 58px;
            line-height: 1.1;
            color: #111827;
            margin-bottom: 20px;
        }

        .hero h2 {
            font-size: 22px;
            font-weight: 600;
            color: #374151;
            line-height: 1.5;
            margin-bottom: 25px;
        }

        .hero p {
            max-width: 850px;
            font-size: 17px;
            color: #4b5563;
            margin-bottom: 30px;
        }

        .buttons {
            display: flex;
            gap: 14px;
            flex-wrap: wrap;
        }

        .button {
            display: inline-block;
            padding: 13px 22px;
            border-radius: 6px;
            font-weight: 700;
            font-size: 14px;
        }

        .button-primary {
            background: #111827;
            color: white;
        }

        .button-primary:hover {
            background: #0f766e;
        }

        .button-secondary {
            border: 1px solid #d1d5db;
            color: #111827;
            background: white;
        }

        .button-secondary:hover {
            border-color: #0f766e;
            color: #0f766e;
        }

        /* Sections */

        section {
            padding: 80px 0;
        }

        .section-white {
            background: white;
        }

        .section-title {
            font-size: 32px;
            color: #111827;
            margin-bottom: 12px;
        }

        .section-line {
            width: 55px;
            height: 4px;
            background: #0f766e;
            margin-bottom: 28px;
        }

        .section-intro {
            max-width: 850px;
            color: #4b5563;
            font-size: 16px;
            margin-bottom: 35px;
        }

        /* Expertise */

        .expertise-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 18px;
        }

        .expertise-card {
            background: #ffffff;
            border: 1px solid #e5e7eb;
            padding: 25px;
            border-radius: 8px;
        }

        .expertise-card h3 {
            font-size: 17px;
            color: #111827;
            margin-bottom: 8px;
        }

        .expertise-card p {
            font-size: 14px;
            color: #6b7280;
        }

        /* Impact */

        .impact-grid {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 15px;
        }

        .impact-card {
            background: #ffffff;
            border: 1px solid #e5e7eb;
            padding: 25px 15px;
            text-align: center;
            border-radius: 8px;
        }

        .impact-number {
            display: block;
            font-size: 31px;
            font-weight: 800;
            color: #0f766e;
            margin-bottom: 8px;
        }

        .impact-label {
            font-size: 13px;
            color: #4b5563;
            font-weight: 600;
        }

        /* Experience */

        .experience {
            border-left: 3px solid #0f766e;
            padding-left: 28px;
            margin-bottom: 40px;
        }

        .experience h3 {
            font-size: 21px;
            color: #111827;
        }

        .company {
            color: #0f766e;
            font-weight: 700;
            margin: 4px 0;
        }

        .date {
            font-size: 13px;
            color: #6b7280;
            margin-bottom: 15px;
        }

        .experience ul {
            padding-left: 20px;
        }

        .experience li {
            margin-bottom: 7px;
            color: #4b5563;
        }

        /* Tags */

        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .tag {
            background: #ffffff;
            border: 1px solid #d1d5db;
            padding: 8px 13px;
            border-radius: 5px;
            font-size: 13px;
            color: #374151;
        }

        /* Contact */

        .contact-box {
            background: #111827;
            color: white;
            border-radius: 10px;
            padding: 45px;
        }

        .contact-box h2 {
            font-size: 30px;
            margin-bottom: 12px;
        }

        .contact-box p {
            color: #d1d5db;
            margin-bottom: 25px;
        }

        .contact-links {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .contact-links a {
            color: white;
            border: 1px solid #4b5563;
            padding: 10px 16px;
            border-radius: 5px;
            font-size: 14px;
        }

        .contact-links a:hover {
            background: #0f766e;
            border-color: #0f766e;
        }

        /* Footer */

        footer {
            background: #0b1120;
            color: #9ca3af;
            text-align: center;
            padding: 25px;
            font-size: 13px;
        }

        /* Mobile */

        @media (max-width: 900px) {

            .hero h1 {
                font-size: 45px;
            }

            .expertise-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .impact-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .nav-links {
                display: none;
            }
        }

        @media (max-width: 600px) {

            .hero {
                padding: 70px 0;
            }

            .hero h1 {
                font-size: 38px;
            }

            .hero h2 {
                font-size: 18px;
            }

            .expertise-grid {
                grid-template-columns: 1fr;
            }

            .impact-grid {
                grid-template-columns: 1fr 1fr;
            }

            section {
                padding: 60px 0;
            }

            .contact-box {
                padding: 30px 22px;
            }
        }
    </style>
</head>

<body>

<!-- Navigation -->

<nav>
    <div class="nav-container">

        <div class="logo">
            KAVISH INDORIA
        </div>

        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#expertise">Expertise</a>
            <a href="#experience">Experience</a>
            <a href="#standards">Standards</a>
            <a href="#contact">Contact</a>
        </div>

    </div>
</nav>


<!-- Hero -->

<header class="hero">

    <div class="container hero-content">

        <div class="eyebrow">
            PRODUCT SAFETY | REGULATORY AFFAIRS | CONFORMITY ASSESSMENT | NPI & NPD
        </div>

        <h1>
            KAVISH INDORIA
        </h1>

        <h2>
            Senior Product Safety & Regulatory Affairs Professional
        </h2>

        <p>
            10+ years of experience across product safety, certification,
            conformity assessment, regulatory compliance, accreditation,
            market access and new product development across Saudi Arabia,
            GCC, UAE and India.
        </p>

        <div class="buttons">

            <a class="button button-primary"
               href="mailto:kaveesh.indoria9@gmail.com">
                Contact Me
            </a>

            <a class="button button-secondary"
               href="#experience">
                View Experience
            </a>

        </div>

    </div>

</header>


<!-- About -->

<section id="about" class="section-white">

    <div class="container">

        <h2 class="section-title">
            Executive Profile
        </h2>

        <div class="section-line"></div>

        <p class="section-intro">

            Senior Product Safety, Regulatory Affairs and Conformity
            Assessment professional with 10+ years of experience spanning
            certification, technical compliance, accreditation, market
            access and product safety across Saudi Arabia, the GCC, UAE
            and India.

            <br><br>

            Currently supporting CHINT WAA R&D Center in Riyadh, with
            responsibility for certification activities across a broad
            portfolio of low-voltage electrical and electronic products.
            The role involves coordination with R&D, design, testing,
            quality, manufacturing, product management, certification
            bodies and external laboratories.

            <br><br>

            Previous experience includes establishing and operationalizing
            an ISO/IEC 17065 Certification Body at IMQ Gulf in Dubai,
            leading a certification team and managing accreditation and
            regulatory engagements across GCC markets.

        </p>

    </div>

</section>


<!-- Expertise -->

<section id="expertise">

    <div class="container">

        <h2 class="section-title">
            Core Expertise
        </h2>

        <div class="section-line"></div>

        <div class="expertise-grid">

            <div class="expertise-card">
                <h3>Product Safety</h3>
                <p>
                    Product safety evaluation, technical compliance,
                    risk assessment and regulatory requirements.
                </p>
            </div>

            <div class="expertise-card">
                <h3>Regulatory Affairs</h3>
                <p>
                    Regulatory strategy, regulatory intelligence and
                    market-access requirements.
                </p>
            </div>

            <div class="expertise-card">
                <h3>Conformity Assessment</h3>
                <p>
                    Certification schemes, technical reviews and
                    conformity-assessment processes.
                </p>
            </div>

            <div class="expertise-card">
                <h3>Certification</h3>
                <p>
                    Certification planning, laboratory coordination,
                    report review and approval management.
                </p>
            </div>

            <div class="expertise-card">
                <h3>Market Access</h3>
                <p>
                    GCC regulatory frameworks and product
                    commercialization support.
                </p>
            </div>

            <div class="expertise-card">
                <h3>NPI & NPD</h3>
                <p>
                    Integration of compliance requirements into
                    new product development and introduction.
                </p>
            </div>

            <div class="expertise-card">
                <h3>Accreditation</h3>
                <p>
                    ISO/IEC 17025, ISO/IEC 17065 and accreditation
                    readiness activities.
                </p>
            </div>

            <div class="expertise-card">
                <h3>Leadership</h3>
                <p>
                    Cross-functional leadership, stakeholder
                    management and technical advisory.
                </p>
            </div>

        </div>

    </div>

</section>


<!-- Impact -->

<section class="section-white">

    <div class="container">

        <h2 class="section-title">
            Selected Career Impact
        </h2>

        <div class="section-line"></div>

        <div class="impact-grid">

            <div class="impact-card">
                <span class="impact-number">10+</span>
                <span class="impact-label">Years Experience</span>
            </div>

            <div class="impact-card">
                <span class="impact-number">15+</span>
                <span class="impact-label">Notification Schemes</span>
            </div>

            <div class="impact-card">
                <span class="impact-number">3</span>
                <span class="impact-label">Accreditation Approvals</span>
            </div>

            <div class="impact-card">
                <span class="impact-number">25+</span>
                <span class="impact-label">International Stakeholders</span>
            </div>

            <div class="impact-card">
                <span class="impact-number">20+</span>
                <span class="impact-label">Training Programs</span>
            </div>

        </div>

    </div>

</section>


<!-- Experience -->

<section id="experience">

    <div class="container">

        <h2 class="section-title">
            Professional Experience
        </h2>

        <div class="section-line"></div>


        <div class="experience">

            <h3>Senior Certification Engineer</h3>

            <div class="company">
                CHINT WAA R&D Center | Riyadh, Saudi Arabia
            </div>

            <div class="date">
                September 2024 – Present
            </div>

            <ul>

                <li>
                    Coordinate third-party laboratories and certification
                    bodies for low-voltage electrical and electronic
                    products.
                </li>

                <li>
                    Provide technical guidance on standards interpretation,
                    certification strategy and documentation readiness.
                </li>

                <li>
                    Coordinate certification activities across R&D,
                    design, testing, quality and external partners.
                </li>

                <li>
                    Monitor regulatory requirements and advise on
                    required product compliance actions.
                </li>

                <li>
                    Support regional certification governance and
                    management reporting across the WAA region.
                </li>

            </ul>

        </div>


        <div class="experience">

            <h3>Certification Officer</h3>

            <div class="company">
                IMQ Gulf | Dubai, UAE
            </div>

            <div class="date">
                October 2020 – August 2024
            </div>

            <ul>

                <li>
                    Established and operationalized an ISO/IEC 17065
                    Certification Body framework.
                </li>

                <li>
                    Led a certification team of five engineers across
                    certification and conformity-assessment activities.
                </li>

                <li>
                    Managed accreditation readiness and assessments
                    involving GAC and ENAS.
                </li>

                <li>
                    Led regulatory engagements involving MOIAT, SASO
                    and GSO.
                </li>

                <li>
                    Guided overseas manufacturers and stakeholders
                    through GCC certification requirements and
                    market-access pathways.
                </li>

                <li>
                    Delivered technical training programs and
                    regulatory workshops.
                </li>

            </ul>

        </div>


        <div class="experience">

            <h3>Compliance Engineer</h3>

            <div class="company">
                QIMA | India
            </div>

            <div class="date">
                March 2020 – September 2020
            </div>

            <ul>

                <li>
                    Performed technical evaluations and conformity
                    assessments against SASO, GSO and IEC requirements.
                </li>

                <li>
                    Supported product registration under IECEE-RC,
                    EER and CITC programs.
                </li>

            </ul>

        </div>


        <div class="experience">

            <h3>Project Engineer – Electrical Safety, Lighting & ATEX</h3>

            <div class="company">
                Intertek India Pvt. Ltd. | India
            </div>

            <div class="date">
                October 2015 – March 2020
            </div>

            <ul>

                <li>
                    Conducted safety testing of electrical and electronic
                    products against IEC/EN, UL, IS and SASO standards.
                </li>

                <li>
                    Supported certification and safety-testing programs
                    across multiple regulated product categories.
                </li>

                <li>
                    Supported audits by international and local
                    accreditation bodies.
                </li>

            </ul>

        </div>

    </div>

</section>


<!-- Standards -->

<section id="standards" class="section-white">

    <div class="container">

        <h2 class="section-title">
            Regulatory & Technical Scope
        </h2>

        <div class="section-line"></div>

        <p class="section-intro">
            Experience across international standards, GCC regulatory
            frameworks, certification programs and accreditation systems.
        </p>

        <h3 style="margin-bottom:15px;">
            Regulatory Programs & Schemes
        </h3>

        <div class="tags">

            <span class="tag">SASO</span>
            <span class="tag">SABER</span>
            <span class="tag">Saudi Quality Mark</span>
            <span class="tag">G-Mark</span>
            <span class="tag">GSO</span>
            <span class="tag">MOIAT</span>
            <span class="tag">ECAS</span>
            <span class="tag">IECEE CB</span>
            <span class="tag">IECEE-RC</span>
            <span class="tag">EER</span>
            <span class="tag">CITC</span>
            <span class="tag">BIS CRS</span>
            <span class="tag">BEE</span>

        </div>

        <br><br>

        <h3 style="margin-bottom:15px;">
            Key Standards
        </h3>

        <div class="tags">

            <span class="tag">IEC 60947</span>
            <span class="tag">IEC 61439</span>
            <span class="tag">IEC 62368</span>
            <span class="tag">IEC 60335</span>
            <span class="tag">IEC 60598</span>
            <span class="tag">IEC 61347</span>
            <span class="tag">IEC 62321</span>
            <span class="tag">IEC 60529</span>
            <span class="tag">IEC 61000</span>
            <span class="tag">CISPR 14-1</span>
            <span class="tag">CISPR 14-2</span>

        </div>

    </div>

</section>


<!-- Education -->

<section>

    <div class="container">

        <h2 class="section-title">
            Education & Certifications
        </h2>

        <div class="section-line"></div>

        <p class="section-intro">

            <strong>Bachelor of Technology – Electronics & Communication Engineering</strong><br>
            M.V.N. College of Engineering, Palwal | 2011–2015

            <br><br>

            <strong>IRCA Certified Lead Auditor</strong><br>
            ISO 9001:2015 | ISO 14001:2015 | ISO 45001:2018

            <br><br>

            Additional training includes ISO/IEC 17025, ISO/IEC 17065,
            ISO/IEC 17021, EMI/EMC, RoHS, laser product safety,
            IT/AV product safety and LV product technology.

        </p>

    </div>

</section>


<!-- Contact -->

<section id="contact" class="section-white">

    <div class="container">

        <div class="contact-box">

            <h2>
                Let's Connect
            </h2>

            <p>
                Open to senior opportunities and professional
                discussions in Product Safety, Regulatory Affairs,
                Conformity Assessment, Certification, Compliance,
                Market Access and NPI & NPD.
            </p>

            <div class="contact-links">

                <a href="mailto:kaveesh.indoria9@gmail.com">
                    Email
                </a>

                <a href="[https://www.linkedin.com](https://www.linkedin.com/in/kavish-indoria)/" target="_blank">
                    LinkedIn
                </a>

            </div>

        </div>

    </div>

</section>


<!-- Footer -->

<footer>

    © 2026 Kavish Indoria. All rights reserved.

</footer>

</body>
</html>
