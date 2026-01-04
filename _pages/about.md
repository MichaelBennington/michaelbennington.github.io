---
permalink: /
title: "Michael J. Bennington"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
layout: archive
---

<div class="thrust">
  <div class="thrust-text">
    <p>
      Hello and welcome! My name is Michael Bennington, and I am a current Mechanical Engineering PhD student in the <a href="https://engineering.cmu.edu/borg/index.html">Biohybrid and Organic Robotics Group</a> at Carnegie Mellon University. My current research focuses on the biomechanics and neural control of multifunctional feeding behaviors in the sea slug <i>Aplysia californica</i>. My work is supported by an NSF Graduate Research Fellowship and a Carnegie Mellon University Presidential Fellowship.
    </p>    

    <p>
      To learn about my broader research interests, check out my <a href="/research/">Research</a> page!
    </p>
  </div>
  
  <figure class="thrust-media">
    <img src="/files/images/Aplysia.jpg" alt="An image of the sea slug, <i>Aplysia californica</i>">
    <figcaption class="thrust-caption">
      An adult <i>Aplysia californica</i>, the sea hare, feeding on <i>Gracilaria</i> macroalgae.
    </figcaption>
  </figure>  

</div>


<b>As I approach the end of my PhD program, I am looking for opportunities to continue my research career as a post-doctoral fellow or tenure track faculty member. </b> I am attending this year's Society for Integrative and Comparative Biology (SICB 2026) conference in Portland, OR. If you see me, feel free to say and we can chat about new research opportunities!

I graduated from the University of California, San Diego with a B.S. in Bioengineering. During my degree, I conducted research under the guidance of Dr. Daniela Valdez-Jasso. In the DVJ Lab, my work focused on the mechanical testing and constitutive model of the right ventricular myocardium and extracellular matrix in a rat model of pulmonary hypertension.



<!-- Optional: Inline styles specific to this page -->
<style>
  
  .thrust {
    display: flex;
    gap: 1rem;
    align-items: flex-start;
    margin: 1.25rem 0;
  }

  
/* Make image+caption a single vertical unit */
.thrust-media {
  display: flex;              /* vertical stack for image + caption */
  flex-direction: column;
  align-items: flex-start;    /* left align caption with image */
  margin: 0;                  /* remove default figure margins */
}

.thrust-media img {
  width: 350px;               /* adjust size as you like */
  height: auto;
  border-radius: 8px;
  object-fit: cover;
  display: block;
}

.thrust-caption {
  font-size: 0.9rem;
  line-height: 1.4;
  color: #6b7280;             /* subtle gray, tweak for your skin */
  margin-top: 0.4rem;
  max-width: 350px;           /* match image width so it lines up */
}


  .thrust .thrust-text {
    flex: 1;
  }

  .thrust-title {
    margin: 0 0 0.25rem 0;
    font-weight: 600;
    font-size: 1.1rem;
  }

  /* Thin divider between sections */
  .thin-divider {
    border: none;
    border-top: 1px solid #ddd;
    margin: 1.5rem 0;
  }

  /* Mobile: stack image above text */
  @media (max-width: 640px) {
    .thrust {
      flex-direction: column;
    }
    .thrust img {
      width: 100%;
      max-width: 520px;
    }
  }
</style>
