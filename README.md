<div align="center">

<!-- Animated typing header -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=079D9A&center=true&vCenter=true&width=700&lines=Hey+there%2C+I'm+Nirvaya+%F0%9F%91%8B;Full-Stack+%26+QA+Automation+Engineer;Playwright+%7C+Selenium+%7C+Next.js+Developer;Building+products+people+love+%F0%9F%9A%80;Every+Master+once+was+a+Beginner." alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=MrVaya&style=for-the-badge&color=079d9a&label=PROFILE+VIEWS" alt="profile views" />
&nbsp;
<a href="https://github.com/MrVaya?tab=followers">
  <img src="https://img.shields.io/github/followers/MrVaya?style=for-the-badge&color=079d9a&labelColor=0d1117&label=FOLLOWERS" alt="followers" />
</a>

</div>

---

## 🧑‍💻 About Me

```ts
const MrVaya = {
  name        : "Nirvaya Ligal",
  username    : "MrVaya",
  location    : "Pokhara, Nepal 🇳🇵  (UTC +05:45)",
  pronouns    : "he/him",
  roles       : ["Freelancer", "QA Automation Engineer"],
  currentWork : "JetSet Holidays — Travel & Flight Booking Platform",
  automating  : ["Playwright (JS/TS)", "Selenium (Java)", "E2E Testing", "API Testing"],
  learning    : ["Next.js 15", "TypeScript", "CI/CD Pipelines", "Test Architecture"],
  philosophy  : "Every Master once was a Beginner.",
  contact     : "github.com/MrVaya",
};
```

---

## 🛠️ Tech Stack

### 🌐 Frontend
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
</p>

### ⚙️ Backend & Database
<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

### 🧪 QA & Test Automation
<p>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/TestNG-FF6C37?style=for-the-badge&logo=testng&logoColor=white" />
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

### 🧰 Tools & Platforms
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
</p>

---

## 🧪 QA Automation Skills

```java
// Selenium + Java — Page Object Model
public class LoginTest extends BaseTest {

    @Test
    public void verifySuccessfulLogin() {
        LoginPage loginPage = new LoginPage(driver);
        loginPage.enterUsername("MrVaya")
                 .enterPassword("securePass")
                 .clickLogin();

        Assert.assertTrue(dashboardPage.isLoaded(), "Login failed!");
    }
}
```

```ts
// Playwright — TypeScript E2E Test
import { test, expect } from '@playwright/test';

test('user can book a flight', async ({ page }) => {
  await page.goto('https://jetsetholidays.com');
  await page.getByRole('button', { name: 'Book Domestic' }).click();
  await expect(page.getByText('Confirm Booking')).toBeVisible();
});
```

<div align="center">

| Skill | Tool | Language |
|---|---|---|
| 🌐 E2E Browser Testing | Playwright | JavaScript / TypeScript |
| 🤖 Web UI Automation | Selenium WebDriver | Java |
| 📋 Test Framework | TestNG / JUnit 5 | Java |
| 🔗 API Testing | Postman / REST Assured | — |
| ⚙️ CI Integration | GitHub Actions | YAML |
| 🏗️ Design Pattern | Page Object Model (POM) | Java / TS |

</div>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%">
      <h3>✈️ JetSet Holidays</h3>
      <p>Full-stack travel & flight booking platform for Nepal — national & international routes, vehicle rentals, visa services, and WhatsApp-integrated booking flow.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
      </p>
      <a href="https://github.com/MrVaya/JetSet">
        <img src="https://img.shields.io/badge/View_Repo-079d9a?style=for-the-badge&logo=github&logoColor=white" />
      </a>
    </td>
    <td width="50%">
      <h3>🧪 QA Automation Suite</h3>
      <p>End-to-end test automation framework using Playwright (JS) and Selenium (Java) with Page Object Model, CI/CD integration via GitHub Actions.</p>
      <p>
        <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
        <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
      </p>
      <a href="https://github.com/MrVaya">
        <img src="https://img.shields.io/badge/View_Repo-079d9a?style=for-the-badge&logo=github&logoColor=white" />
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🛒 E-Commerce Web (6th Sem)</h3>
      <p>Full-featured e-commerce platform with product listings, cart system, and order management. Built as a final semester project with a complete backend.</p>
      <p>
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
        <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      </p>
      <a href="https://github.com/MrVaya/E-commerce-web-6-sem">
        <img src="https://img.shields.io/badge/View_Repo-079d9a?style=for-the-badge&logo=github&logoColor=white" />
      </a>
    </td>
    <td width="50%">
      <h3>⚙️ Backend System</h3>
      <p>Robust backend system built with Laravel/Blade. Focuses on server-side architecture, routing, authentication, and database management.</p>
      <p>
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" />
        <img src="https://img.shields.io/badge/Blade-FF2D20?style=flat-square&logo=laravel&logoColor=white" />
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      </p>
      <a href="https://github.com/MrVaya/Backend-system">
        <img src="https://img.shields.io/badge/View_Repo-079d9a?style=for-the-badge&logo=github&logoColor=white" />
      </a>
    </td>
  </tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=MrVaya&show_icons=true&theme=dark&bg_color=0d1117&title_color=079d9a&icon_color=079d9a&border_color=30363d&text_color=c9d1d9&count_private=true" alt="GitHub Stats" />
<img width="49%" src="https://streak-stats.demolab.com?user=MrVaya&theme=dark&background=0d1117&ring=079d9a&fire=079d9a&currStreakLabel=079d9a&border=30363d&sideNums=c9d1d9&currStreakNum=ffffff&sideLabels=8b949e&dates=8b949e" alt="Streak Stats" />

<br/><br/>

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MrVaya&layout=compact&theme=dark&bg_color=0d1117&title_color=079d9a&border_color=30363d&text_color=c9d1d9&langs_count=8" alt="Top Languages" />

</div>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MrVaya&bg_color=0d1117&color=079d9a&line=079d9a&point=ffffff&area=true&hide_border=true" alt="Contribution Graph" />
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=MrVaya&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=8" alt="GitHub Trophies" />
</div>

---

## 🐍 Contribution Snake

> **Setup required** — follow the 3 steps below to activate the snake animation on your profile.

<div align="center">

<!-- Works once you run the GitHub Action below -->
<img src="https://raw.githubusercontent.com/MrVaya/MrVaya/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />

</div>

---

## ⚡ Activate the Snake — 3 Steps

**Step 1** — In your `MrVaya/MrVaya` repo, create this file:
`.github/workflows/snake.yml`

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"   # runs every day at midnight UTC
  workflow_dispatch:        # lets you trigger it manually too

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write

    steps:
      - name: Generate snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: MrVaya
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

**Step 2** — Go to **Actions tab** → click `Generate Snake Animation` → click **Run workflow**.

**Step 3** — Wait ~30 seconds. The snake SVG will appear in your `output` branch and display on your profile automatically. ✅

---

## 🤝 Let's Connect

<div align="center">

<a href="mailto:jetsetholidays36@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/MrVaya">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="https://wa.me/9779841743706">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</a>

</div>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&color=079D9A&center=true&vCenter=true&width=500&lines=Thanks+for+visiting+my+profile!+%F0%9F%99%8F;Let's+build+%26+test+something+great+together.+%F0%9F%9A%80" alt="Footer typing" />

<br/><br/>

<sub>⭐ <b>Star some repos if you find them useful!</b> — Made with ❤️ from Kathmandu, Nepal 🇳🇵</sub>

</div>
