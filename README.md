<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="google-site-verification" content="Wby9p_eTBuhZCnwZryTc8LsCvXkjgZVVj4wgx9D_e90" />
    <title>Kyuseong Choi</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #fff;
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .header {
            display: flex;
            gap: 3rem;
            margin-bottom: 3rem;
            align-items: flex-start;
        }

        .profile-section {
            flex-shrink: 0;
            width: 280px;
        }

        .profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1.5rem;
        }

        .name {
            font-size: 1.8rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
            color: #000;
        }

        .title {
            color: #666;
            margin-bottom: 1rem;
            font-size: 1rem;
        }

        .location {
            color: #666;
            margin-bottom: 1.5rem;
            font-size: 0.9rem;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 0.8rem;
        }

        .links a {
            color: #0066cc;
            text-decoration: none;
            font-size: 0.9rem;
        }

        .links a:hover {
            text-decoration: underline;
        }

        .main-content {
            flex: 1;
        }

        .nav {
            margin-bottom: 2rem;
            border-bottom: 1px solid #eee;
            padding-bottom: 1rem;
        }

        .nav a {
            color: #666;
            text-decoration: none;
            margin-right: 2rem;
            font-size: 1rem;
        }

        .nav a.active {
            color: #000;
            font-weight: 500;
        }

        .nav a:hover {
            color: #000;
        }

        h1 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: #000;
            font-weight: 600;
        }

        h2 {
            font-size: 1.4rem;
            margin: 2rem 0 1rem 0;
            color: #000;
            font-weight: 600;
        }

        .bio {
            font-size: 1rem;
            line-height: 1.7;
            margin-bottom: 2rem;
        }

        .bio a {
            color: #0066cc;
            text-decoration: none;
        }

        .bio a:hover {
            text-decoration: underline;
        }

        .section {
            margin-bottom: 2.5rem;
        }

        .education-item {
            margin-bottom: 1rem;
            line-height: 1.5;
        }

        .degree {
            font-weight: 500;
        }

        .institution {
            color: #666;
            font-size: 0.95rem;
        }

        .paper-item {
            margin-bottom: 1.5rem;
            line-height: 1.6;
        }

        .paper-title {
            margin-bottom: 0.3rem;
        }

        .paper-title a {
            color: #0066cc;
            text-decoration: none;
            font-weight: 500;
        }

        .paper-title a:hover {
            text-decoration: underline;
        }

        .authors {
            color: #666;
            font-size: 0.95rem;
            margin-bottom: 0.2rem;
        }

        .venue {
            color: #666;
            font-style: italic;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            .header {
                flex-direction: column;
                gap: 2rem;
            }
            
            .profile-section {
                width: 100%;
                text-align: center;
            }
            
            .profile-image {
                width: 150px;
                height: 150px;
            }
            
            .nav a {
                margin-right: 1rem;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="profile-section">
            <img src="profile.png" alt="Kyuseong Choi" class="profile-image" />
            <div class="name">Kyuseong Choi</div>
            <div class="title">Statistics PhD Candidate</div>
            <div class="location">📍 Cornell Tech</div>
            
            <div class="links">
                <a href="mailto:kc728@cornell.edu">📧 Email</a>
                <a href="https://scholar.google.com/citations?user=YIlTXCIAAAAJ&hl=en&oi=ao">🎓 Google Scholar</a>
                <a href="https://www.linkedin.com/in/kyuseong-choi-ab532a1b4/">💼 LinkedIn</a>
                <a href="cv.pdf">📄 CV</a>
            </div>
        </div>

        <div class="main-content">
            <nav class="nav">
                <a href="#about" class="active">About</a>
                <a href="#research">Research</a>
                <a href="#publications">Publications</a>
                <a href="cv.pdf">CV</a>
            </nav>

            <section id="about">
                <h1>Welcome!</h1>
                
                <div class="bio">
                    Currently, I am a Statistics PhD student at Cornell Tech. My current research interests include efficient and interpretable policy optimization, personalization in causal inference (via foundational models) and central limit theorems for high-dimensional data points. I am co-advised by <a href="https://raazdwivedi.github.io">Raaz Dwivedi</a> and <a href="https://sites.google.com/site/kkatostat/home/research?authuser=0">Kengo Kato</a>.
                </div>
            </section>

            <div class="section" id="education">
                <h2>Education</h2>
                <div class="education-item">
                    <div class="degree">Statistics, PhD, Cornell Tech (2021 - Present)</div>
                </div>
                <div class="education-item">
                    <div class="degree">Biostatistics, MS, University of Michigan, Ann Arbor (2021)</div>
                </div>
                <div class="education-item">
                    <div class="degree">BBA Business Administration, Korea University (2019)</div>
                </div>
            </div>

            <div class="section">
                <h2>Working Papers</h2>
                <div class="paper-item">
                    <div class="paper-title">GRPO++: Improved policy optimization using ranked rewards</div>
                    <div class="authors">Kyuseong Choi, Dwaipayan Saha, Woojeong Kim, Anish Agarwal, Raaz Dwivedi</div>
                </div>
                <div class="paper-item">
                    <div class="paper-title">Gaussian approximation in Reproducing kernel Hilbert space, applications to kernel ridge regression</div>
                    <div class="authors">Kyuseong Choi, Kengo Kato</div>
                </div>
            </div>

            <div class="section" id="publications">
                <h2>Preprints</h2>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://arxiv.org/abs/2510.17648v1">Wild regenerative block bootstrap for Harris recurrent Markov chains</a>
                    </div>
                    <div class="authors">Kyuseong Choi, Gabriella Ciolek</div>
                </div>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://arxiv.org/abs/2510.02625">TabImpute: Accurate and Fast Zero-Shot Missing-Data Imputation with a Pre-Trained Transformer</a>
                    </div>
                    <div class="authors">Jacob Feitelberg, Dwaipayan Saha, Kyuseong Choi, Zaid, Ahmad, Anish Agarwal, Raaz Dwivedi</div>
                </div>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://arxiv.org/abs/2410.13381">Learning counterfactual distribution via kernel nearest neighbors</a>
                    </div>
                    <div class="authors">Kyuseong Choi, Jacob Feitelberg, Anish Agarwal, Raaz Dwivedi</div>
                </div>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://arxiv.org/abs/2410.13112">Distributional matrix completion via nearest neighbors in the Wasserstein space</a>
                    </div>
                    <div class="authors">Jacob Feitelberg, Kyuseong Choi, Anish Agarwal, Raaz Dwivedi</div>
                </div>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://arxiv.org/abs/2506.04166">N2: A Unified Python Package and Test Bench for Nearest Neighbor-Based Matrix Completion</a>
                    </div>
                    <div class="authors">Caleb Chin, Aashish Khubchandani, Harshvardhan Maskara, Kyuseong Choi, Jacob Feitelberg, Albert Gong, Manit Paul, Tathagata Sadhukhan, Anish Agarwal, Raaz Dwivedi</div>
                </div>
            </div>

            <div class="section">
                <h2>Publications</h2>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://arxiv.org/abs/2410.13749">Supervised kernel thinning</a>
                    </div>
                    <div class="authors">Albert Gong, Kyuseong Choi, Raaz Dwivedi</div>
                    <div class="venue">NeurIPS 2024</div>
                </div>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://academic.oup.com/biometrics/article/80/1/ujad005/7609159">Robust data integration from multiple external sources for generalized linear models with binary outcomes</a>
                    </div>
                    <div class="authors">Kyuseong Choi, Jeremy M.G. Taylor, Peisong Han</div>
                    <div class="venue">Biometrics, Volume 80, Issue 1, March 2024</div>
                </div>
                <div class="paper-item">
                    <div class="paper-title">
                        <a href="https://academic.oup.com/biomet/article-abstract/110/1/119/6567343">Data integration: exploiting ratios of parameter estimates from a reduced external model</a>
                    </div>
                    <div class="authors">Jeremy M.G. Taylor, Kyuseong Choi, Peisong Han</div>
                    <div class="venue">Biometrika, Volume 110, Issue 1, March 2023, Pages 119-134</div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
