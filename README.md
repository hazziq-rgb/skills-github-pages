<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Dato' Prince Haziq Harvey - Ahli Perniagaan Berjaya</title>
</head>
<body>

    <header>
        <h1>Dato' Prince Haziq Harvey</h1>
        <p>Ahli Perniagaan Berjaya & Usahawan Inspirasi</p>
    </header>

    <!-- Pengenalan Diri -->
    <section id="about">
        <h2>Pengenalan Diri</h2>
        <p>Dato' Prince Haziq Harvey merupakan seorang usahawan yang berjaya dalam bidang hartanah, pelaburan strategik, dan konsultasi perniagaan. Beliau telah membina empayar perniagaan yang kukuh selama lebih 15 tahun dan menjadi inspirasi kepada ramai usahawan muda.</p>
    </section>

    <!-- Perkhidmatan -->
    <section id="services">
        <h2>Perkhidmatan</h2>
        <ul>
            <li>Pembangunan Hartanah - Projek kondominium, apartmen, dan bangunan komersial.</li>
            <li>Pelaburan Strategik - Konsultasi pelaburan untuk individu dan syarikat.</li>
            <li>Konsultasi Perniagaan - Rangka pelan perniagaan dan strategi pemasaran.</li>
        </ul>
    </section>

    <!-- Portfolio Projek -->
    <section id="portfolio">
        <h2>Portfolio Projek</h2>
        <div class="project">
            <h3>Projek Kondominium Mewah</h3>
            <p>Pembangunan kondominium 20 tingkat di pusat bandar Kuala Lumpur.</p>
        </div>
        <div class="project">
            <h3>Pusat Perniagaan Strategik</h3>
            <p>Pusat perniagaan berkonsepkan moden dengan kemudahan lengkap.</p>
        </div>
        <div class="project">
            <h3>Pelaburan Hartanah Luar Negara</h3>
            <p>Projek pelaburan hartanah di Dubai dan Singapura.</p>
        </div>
    </section>

    <!-- Pasukan -->
    <section id="team">
        <h2>Pasukan Kami</h2>
        <div class="team-member">
            <h3>Ahmad Zulkifli</h3>
            <p>Ketua Pembangunan Projek</p>
        </div>
        <div class="team-member">
            <h3>Nurul Ain</h3>
            <p>Pakar Pelaburan</p>
        </div>
        <div class="team-member">
            <h3>Farid Hakim</h3>
            <p>Konsultan Perniagaan</p>
        </div>
    </section>

    <!-- Media & Pencapaian -->
    <section id="media">
        <h2>Media & Pencapaian</h2>
        <p>Dato' Prince Haziq Harvey telah menerima pelbagai anugerah, termasuk:</p>
        <ul>
            <li>Anugerah Usahawan Terbaik 2024 - Majlis Pembangunan Usahawan Malaysia</li>
            <li>Projek Hartanah Terbaik 2023 - Asian Property Awards</li>
            <li>Usahawan Inspirasi 2022 - Forbes Asia</li>
        </ul>
    </section>

    <!-- Blog -->
    <section id="blog">
        <h2>Blog</h2>
        <div class="blog-post">
            <h3>Cara Memulakan Pelaburan Hartanah</h3>
            <p>Pelajari langkah-langkah untuk memulakan pelaburan hartanah dengan risiko minimum.</p>
        </div>
        <div class="blog-post">
            <h3>Pentingnya Konsultasi Perniagaan</h3>
            <p>Mengapa konsultasi perniagaan menjadi faktor penting dalam mencapai kejayaan perniagaan.</p>
        </div>
    </section>

    <!-- Hubungi Kami -->
    <section id="contact">
        <h2>Hubungi Kami</h2>
        <form>
            <label for="name">Nama:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            <label for="message">Mesej:</label>
            <textarea id="message" name="message" required></textarea><br>
            <button type="submit">Hantar</button>
        </form>
    </section>

</body>
</html>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Welcome

With GitHub Pages, you can host project blogs, documentation, resumes, portfolios, or any other static content you'd like. Your GitHub repository can easily become its own website. In this course, we'll show you how to set up your own site or blog using GitHub Pages.

- **Who is this for**: Beginners, students, project maintainers, small businesses.
- **What you'll learn**: How to build a GitHub Pages site.
- **What you'll build**: We'll build a simple GitHub Pages site with a blog. We'll use [Jekyll](https://jekyllrb.com), a static site generator.
- **Prerequisites**: If you need to learn about branches, commits, and pull requests, take [Introduction to GitHub](https://github.com/skills/introduction-to-github) first.
- **How long**: This course takes less than one hour to complete.

In this course, you will:

1. Enable GitHub Pages
2. Configure your site
3. Customize your home page
4. Create a blog post
5. Merge your pull request

### How to start this course

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'github-pages',
  owner: '@me',
  name: 'skills-github-pages',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=github-pages&owner=%40me&name=skills-github-pages&description=My+clone+repository&visibility=public)

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
