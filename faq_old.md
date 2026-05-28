---
layout: default
title: "FAQ"
description: "Foire aux questions sur les CPGE PTSI/PT & ATS — Lycée Dumont d'Urville-Laplace, Caen."
hero_badge: "Questions"
hero_title: "Foire aux <span>questions</span>"
hero_subtitle: "Les réponses aux questions les plus fréquentes"
---


<div class="page-content">

<div class="faq-item">
  <button class="faq-question" onclick="toggle(this)">
    La prépa est-elle vraiment si difficile ? <span>＋</span>
  </button>
  <div class="faq-answer">
    <p>La prépa demande un investissement personnel important, mais elle est avant tout une école de méthode et de travail. L'équipe pédagogique accompagne chaque étudiant individuellement. La difficulté est réelle mais progressive, et la solidarité entre étudiants est forte.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question" onclick="toggle(this)">
    Peut-on intégrer PT après une autre PTSI ? <span>＋</span>
  </button>
  <div class="faq-answer">
    <p>Oui, il est tout à fait possible d'avoir fait sa PTSI dans un autre lycée et de rejoindre la PT de Dumont d'Urville-Laplace. La candidature se fait via Parcoursup en fin de première année.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question" onclick="toggle(this)">
    Quelle est la taille des classes ? <span>＋</span>
  </button>
  <div class="faq-answer">
    <p>Les classes comportent en général entre 30 et 40 étudiants. Les travaux dirigés et colles se font en groupes beaucoup plus petits (6 à 8 étudiants), ce qui permet un suivi personnalisé.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question" onclick="toggle(this)">
    Que se passe-t-il si je ne réussis pas les concours ? <span>＋</span>
  </button>
  <div class="faq-answer">
    <p>La grande majorité des étudiants intègre une école d'ingénieurs à l'issue de la prépa. En cas d'échec aux concours, il est possible de s'inscrire en licence universitaire (équivalence L2 ou L3 selon le niveau), ou de tenter une seconde année de PT (PT**).</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question" onclick="toggle(this)">
    Y a-t-il une vie associative ou sportive ? <span>＋</span>
  </button>
  <div class="faq-answer">
    <p>Oui ! Le lycée propose des activités sportives via le BDS (Bureau des Sports). Les étudiants en CPGE peuvent également accéder aux associations étudiantes de l'Université de Caen, située à proximité.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question" onclick="toggle(this)">
    L'ATS est-elle accessible après un BTS tertiaire ? <span>＋</span>
  </button>
  <div class="faq-answer">
    <p>Non, la filière ATS est destinée aux étudiants issus de BTS ou DUT à dominante industrielle ou scientifique (génie mécanique, électrotechnique, génie industriel, etc.).</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question" onclick="toggle(this)">
    Peut-on avoir un job étudiant en parallèle ? <span>＋</span>
  </button>
  <div class="faq-answer">
    <p>La charge de travail en prépa est très importante (entre 40 et 60h de travail par semaine). Il est fortement déconseillé d'exercer une activité professionnelle en parallèle, sauf à temps très réduit pendant les vacances.</p>
  </div>
</div>

</div>

<script>
function toggle(btn) {
  const answer = btn.nextElementSibling;
  const icon = btn.querySelector('span');
  answer.classList.toggle('open');
  icon.textContent = answer.classList.contains('open') ? '－' : '＋';
}
</script>
