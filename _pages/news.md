---
layout: page
permalink: /news/
---
<style>
    body {
        font-size: 18px;
    }
    .hidden {
        display: none;
    }
    #more-btn {
      margin-top: 10px;
      cursor: pointer;
      color: #a32133;
      text-decoration: underline;
    }
</style>

[comment]: <> (paper, service, award, talk)
<section>
  <h2>📢 News</h2>
  <li>2025.04.30, 📝 One paper is accepted by GLSVLSI 2025. Congratulations to Jin!</li>
  <li>2025.04.27, 🙌 Invited as TPC member at ICCAD 2025.</li>
  <li>2025.03.17, 🙌 Invited as PC member at QCE 2025.</li>
  <li>2024.11.20, 🎤 Talk at ICCD 2024, Milan. Thanks to Longshan. </li>
  <li>2024.11.19, 📝 One paper is accepted by DATE 2025. Congratulations to Jin!</li>
  <li>2024.11.03, 🙌 StableQ 2024 workshop is successfully organized at MICRO 2024, Austin (Program Committee).</li>
  <li>2024.09.02, Join George Mason University (GMU) as a Postdoctoral Research Fellow.</li>
  <li>2024.08.20, 🙌 Invited as PC member at QCE 2024.</li>
  <li>2024.08.01, 📝 One paper is accepted by ICCD 2024.</li>
  <li>2024.06.20, Ph.D. graduation. </li>
  <li>2024.05, 🏆 Outstanding Graduate of East China Normal University.</li>
  <li>2024.03.15, 📝 One paper is accepted by Journal of ECNU (Natural Science). Congratulations to Yongzhuo!</li>
  <li>2024.03.01, Join The Chinese University of Hong Kong (CUHK) as a Research Assistant.</li>
  <li>2023.12, 🏆 Huaxin Scholarship, East China Normal University.</li>
  <li>2023.12, 🏆 Outstanding Student of East China Normal University.</li>
  <li>2023.11.28, 📝 One paper is accepted by Frontiers of Computer Science journal. Congratulations to Yixuan!</li>
  <li>2023.11.24, 📝 One paper is accepted by Quantum Information Processing journal.</li>
  <li>2023.10.16, 📝 One paper is accepted by Quantum Information Processing journal.</li>
  <li>2023.08.06—08.07, 🙌 Symposium on Big Data and Intelligent Systems Technology is successfully organized at ECNU.</li>
  <li>2023.07, 📝 Two project proposals are accepted by NSFC. Congratulations to Prof. Sha and Prof. Zhuge!</li>
  <li>2022.12, 🏆 Huaxin Scholarship, East China Normal University.</li>
  <li>2022.12, 🏆 Outstanding Student Leader of East China Normal University.</li>
  <li>2022.12.17, 📝 One paper is accepted by JSA journal.</li>
  <li>2022.11.15, 📝 One paper is accepted by Journal of Computer Research and Development.</li>
  <li>2022.10.10—10.12, 🙌 ESWEEK 2022 is successfully organized by Big Data and Intelligent Systems Team (Chair: Prof. Sha).</li>
  <li>2022.10.09, 🎤 Talk at CCF ESTC 2022, Shanghai.</li>
  <li>2022.01.19, 🎤 Talk at ASP-DAC 2022, virtual conference.</li>
  <li>2021.12, 🏆 Social Scholarship, East China Normal University.</li>
  <li>2021.09.12, 📝 One paper is accepted by ASP-DAC 2022 conference.</li>
  <li>2021.08.31, Ph.D. admission.</li>
  <li>2021.07.13, 📝 One paper is accepted by ICCAD 2021 conference. Congratulations to Panjie!</li>
  <li>2021.02.14, 📝 One paper is accepted by DAC 2021 conference.</li>
  <div id="more-btn">Show More <span id="arrow">&#9660;</span></div>
</section>

<script>
  const allItems = document.querySelectorAll('li');
  const moreBtn = document.getElementById("more-btn");
  let expanded = false;

  allItems.forEach((item, index) => {
    if (index >= 20) {
      item.classList.add('hidden');
    }
  });

  moreBtn.addEventListener("click", () => {
    expanded = !expanded;

    allItems.forEach((item, index) => {
      if (index >= 20) {
        item.classList.toggle('hidden', !expanded);
      }
    });

    if (expanded) {
      moreBtn.innerHTML = 'Show Less <span id="arrow">&#9650;</span>';
    } else {
      moreBtn.innerHTML = 'Show More <span id="arrow">&#9660;</span>';
    }
  });
</script>

