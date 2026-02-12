---
title: "Synthetic Nervous System Control of a Bioinspired Soft Grasper for Pick-and-Place Manipulation"
collection: publications
category: conference
permalink: /publication/SNSSoftGripper
excerpt: 'A bioinspired neural model controls a soft robotic gripper for pick-and-place tasks.'
date: 2023-08-01
venue: 'Biomimetic and Biohybrid Systems (Living Machines 2023)'
slidesurl: ''
paperurl: 'http://michaelbennington.github.io/files/SNSSoftGripper.pdf'
citation: 'Sukhnandan, R., Li, Y., et al. (2023). &quot;Synthetic Nervous System Control of a Bioinspired Soft Grasper for Pick-and-Place Manipulation.&quot; <i>In: Meder, F., Hunt, A., Margheri, L., Mura, A., Mazzolai, B. (eds) Biomimetic and Biohybrid Systems. Living Machines 2023.</i> Lecture Notes in Computer Science(), vol 14157. Springer, Cham. [doi: 10.1007/978-3-031-38857-6_23](https://doi.org/10.1007/978-3-031-38857-6_23).'
image: '/files/graphical abstracts/SNS_grasper.png'

---

R. Sukhnandan<SUP>1+</SUP>, Y. Li<SUP>4+</SUP>, Y. Wang<SUP>1</SUP>, A. Bhammar<SUP>1</SUP>, K. Dai<SUP>1</SUP>, <b> M. J. Bennington</b><SUP>1</SUP>, H. J. Chiel<SUP>5,6,7</SUP>, R. D. Quinn<SUP>4</SUP>, V. A. Webster-Wood<SUP>1,2,3</SUP>

<b>1</b> Department of Mechanical Engineering, Carnegie Mellon University
<b>2</b> Department of Biomedical Engineering, Carnegie Mellon University
<b>3</b> McGowan Institute for Regenerative Medicine, Carnegie Mellon University
<b>4</b> Department of Mechanical Engineering, Case Western Reserve University
<b>5</b> Department of Biology, Case Western Reserve University
<b>6</b> Department of Biomedical Engineering, Case Western Reserve University
<b>7</b> Department of Neurosciences, Case Western Reserve University

<b>+</b>: These authors contributed equally to this work.

![A graphical abstract</i>]({{ page.image }})
<i>Reproduced or modified from: [The CMU BORG](https://engineering.cmu.edu/borg/index.html)

Manipulation of objects of variable size, shape and surface properties remains a challenging problem in robotics. In this paper, we present the design of a soft, pneumatically variable contact stiffness grasper and the training of a sparse, bioinspired neural network controller for pick-and-place manipulation. Both the soft grasper and the neural network controller are inspired by the sea slug Aplysia californica. The compliant nature of the grasper is beneficial for maintaining rich contact with objects, which simplifies the control problem. Adopting biologically inspired neural dynamics and network structure has the further advantage of building neural network controllers that are robust and efficient for real-time control. To verify the effectiveness of our bioinspired approach for object grasping and manipulation, we developed a simulation environment that reflects the compliance between the soft grasper and the object. We demonstrate that when integrated with the neural network controller, the grasper successfully completed the pickand-place task in simulation. With minimal tuning, the controller was then successfully transferred to the physical soft grasping platform and was able to successfully pick-and-place objects of various size and mass, up to a maximum tested mass of 706 g. The bio-inspired approach to both the morphology and the control of the soft-grasper presented here thus represents an exciting first step toward the robust adaptive manipulation of a broad class of objects.