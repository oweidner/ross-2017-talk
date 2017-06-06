# Bio

Ole Weidner is a part-time PhD student at the School of Informatics, Centre for Intelligent Systems and their Applications (CISA) at the University of Edinburgh, Scotland. After working for 8 years as a computational scientist and research programmer on a multitude of distributed and high-performance computing projects at Louisiana State University and Rutgers University (USA), he is now a big data engineer at LEGO System A/S in Billund, Denmark where he leads the foundation platform team.

Ole's research interests lie at the triple point of high-performance computing, big data and data-driven analytics, and expert systems that facilitate the development and operation of large-scale, second generation HPC applications.

From his viewpoint, the optimization of HPC clusters and their applications is a quintessential big data problem and capturing and opening a wide spectrum of operational data to platform operators, application developers and users is of paramount importance.

His current research on "Data-Driven HPC platforms" focuses on the application of real-time data sensing, streaming and data analytics to HPC platform and application data to create an enhanced, non-disruptive and insight-driven framework for the development and operation of second generation HPC applications and their entourage of supporting services and frameworks.

# Abstract

Continuous insights into the behavior and performance of large-scale computing application is an important asset throughout the entire application lifecycle. With platforms and applications growing towards exascale, the rise of platform federations, and an application landscape that is growing increasingly diverse, these insights becomes even more critical. Contrary to these requirements, most HPC platforms do not have strategies or mechanisms in place to provide applications and developers with the operational data necessary.

To address this issue of "platform data drought", we propose Data-Driven HPC, a novel paradigm and platform architecture that closely ties real-time streaming of operational data and analytics facilities into the design, operation and usage model of high performance computing platforms.

The Data-Driven HPC model defines an ecosystem in which monitoring, feedback control loops and expert systems can be implemented conveniently and exploited by application developers and platform providers alike. Its core idea is to provide transparent mechanisms for data transport, storage and analysis on the platform layer to prevent them from seeping into the application and user-space framework layers where they cause unnecessary complexity and inefficiency, especially at scale.

In this talk we provide an overview of the platform model and a series of exemplary use-cases that highlight the increasing importance of real-time, data-driven insights for productive and performant applications and platforms. Furthermore, we discuss a non-disruptive prototype implementation of the Data-Driven HPC model and interface based on Apache Kafka and Spark and discuss how it can be added as a "sidekick" to an existing SLURM-based HPC cluster with only minor modifications and disruption.
