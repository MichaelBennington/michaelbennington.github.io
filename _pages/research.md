---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<div class="thrust">
  <img src="/files/research images/overview.png" alt="Overview Illustration">
  <div class="thrust-text">
    <div class="thrust-title">Overview</div>
    <p>
      How do the biology and physiology of tissue determine the mechanics of organisms? How do mechanical forces and interactions shape and constrain biological systems? My research interests lie at the intersection of physics, biology, and computational modeling. I seek to understand how the physics of biological systems and materials impact their behavior and how we can develop simulation tools to capture this interplay.
    </p>

    <p>
      I believe strongly in the interplay between experimentation and modeling, using experiments to inform and calibrate models, and using models to explain and plan experiments. From my previous experiences, I have a strong basis in both experimental and computational research, and can serve as an intermediary between these two groups. 
    </p>
  </div>
</div>

<hr class="thin-divider" />

<!-- ===== Research Thrust 1 ===== -->
<div class="thrust">
  <img src="/files/research images/populations.png" alt="Population Modeling of Mechanical Systems">
  <div class="thrust-text">
    <div class="thrust-title">Population Modeling of Mechanical Systems</div>
    <p>
      Variability is an inherent property of many real world systems and averaging out that variability across individual samples can hide important features of the larger population.
    </p>

    <p>  
      By utilizing tools from computational statistics and Bayesian modeling, I aim to create modeling frameworks, tools, and calibration methods for capturing the variability inherent in populations of mechanical and biological systems.
    </p>

    <p>  
      These tools will be utilized in my other research thrusts to create plausible ensembles of models that 1) expose how variability in parameters of individual relates to variability in the behavior of populations, and 2) how and why the traits within populations are coupled. 
    </p>    
  </div>
</div>

<hr class="thin-divider" />

<!-- ===== Research Thrust 2 ===== -->
<div class="thrust">
  <img src="/files/research images/neuromech.png" alt="Comparative Bio- and Neuromechanics">
  <div class="thrust-text">
    <div class="thrust-title">Comparative Neuromechanics</div>
    <p>
      How do animals generate multifunctional and adaptive behaviors? How do the mechanics of the body impact the sensory systems and control schemes that different species use? How do related animals or those with similar body plans solve the same problem using different strategies? 
    </p>

    <p>
      By combining advanced bio- and neuromechanical models, anatomical studies, and behavioral assays, I aim to uncover how animals acheive their diverse behaviors and what role the mechanical intelligence of their bodies plays. 
    </p>
    
    <p>
      Using these models with generative statistical tools, I aim to create simulations for many representative animals, allowing us to study variability in control across a population and how populations of variable individuals interact. 
    </p>
    
    <p>  
      I am particularly focused on addressing these questions in soft bodies systems, from sea slugs to worms to tongues, but I am open to working with any animal or tissue type that presents an interesting mechanical problem.
    </p>
  </div>
</div>

<hr class="thin-divider" />

<!-- ===== Research Thrust 3 ===== -->
<div class="thrust">
  <img src="/files/research images/multiphysics.png" alt="Multi-physics of Biological Materials">
  <div class="thrust-text">
    <div class="thrust-title">Multi-physics of Biological Materials</div>
    <p>
      Biological materials, whether naturally occuring in tissues or engineered, are inherently multi-physics systems, with mechanics, chemistry, and biological phenomena interacting at multiple scales. By understanding these interactions, we can gain insights into the structure-function relationship in natural systems and design advanced bioengineering solutions.  
    </p>

    <p>
      By combining techniques from continuum and stochastic modeling with 3D microscopy and mechanical experiments, I aim to probe the interconnection between these phenomena across scale.  
    </p>

    <p>
      I am particularly interested in how these phenomena guide the growth and behavior of biological systems, and how computational models can be used as design tools for bioengineers.
    </p>
  </div>
</div>

<!-- Optional: add a final note or call-to-action -->
<hr class="thin-divider" />
<p><em>Interested in collaborating?</em> Please feel free to <a href="/contact/">reach out</a>!</p>



<!-- Optional: Inline styles specific to this page -->
<style>
  /* Keep styles scoped to avoid affecting other pages */
  .research-summary {
    font-size: 1.05rem;
    line-height: 1.7;
    margin: 0 0 1.5rem 0;
  }

  .thrust {
    display: flex;
    gap: 1rem;
    align-items: flex-start;
    margin: 1.25rem 0;
  }

  .thrust img {
    align-self: center;     /* centers this item on the flex cross-axis (vertical) */
    width: 350px;              /* Adjust as needed */
    height: auto;
    border-radius: 8px;         /* Soft corners */
    object-fit: cover;
    flex-shrink: 0;
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
