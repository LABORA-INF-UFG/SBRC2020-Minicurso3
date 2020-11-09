# Soft5G+: explorando a softwarização nas redes5G

Este minicurso tem como objetivo explorar a utilização de softwares no sistema 5G composto pela Radio Access Network (RAN) e os componentes principais, seguindo os padrões definidos pelo 3GPP, em especial, os descritos no Release 15. O minicurso fornece visão geral das redes celulares móveis sem fio, incluindo conceitos básicos e a evolução através das chamadas 'gerações' de redes móveis. Do ponto de vista do software, o RAN é apresentada no contexto das redes 4G e 5G, que inclui a RAN virtualizada e desagregada. Uma parte significativa do minicurso é dedicada ao núcleo 5G, ou seja, considerando a Arquitetura Baseada em Serviços (SBA), devido à sua relevância e abordagem totalmente baseada em software. O minicurso é motivado por um conjunto de experimentos. Para cada experimento, disponibilizamos um manual detalhado e todo o software necessário para replicá-lo. Alguns experimentos podem ser reproduzidos usando apenas um computador normal, por exemplo, um notebook, mas alguns deles exigem a utilização de hardware específico, por exemplo, um Rádio Definido por Software (SDR).

## Material
<!-- * [Article](https://arxiv.org/abs/2006.10409) -->
* Parte prática
  * Demo 1 - Nesta demonstração, nós criamos um eNodeB operacional, ou seja, criamos o elemento principal de uma RAN, baseado em tecnologia LTE e software livre. Além da RAN, o software também é capaz de emular UEs funcionais.
    * Experimento 1 ([repositório](https://github.com/LABORA-INF-UFG/SBRC2020-Minicurso3-Demo1-Exp1 "Demo 1 - Experiment 1"), [video](https://youtu.be/puIOD6nQ3j0)) - UE e RAN emulado por software sem a presença do núcleo.
    * Experimento 2 ([repository](https://github.com/LABORA-INF-UFG/SBRC2020-Minicurso3-Demo1-Exp2 "Demo 1 - Experiment 2"), [video](https://youtu.be/X9qrC_dEL6g)) - UE, RAN, e núcleo EPC, todos implementados através de software.
    * Experimento 3 ([repository](https://github.com/LABORA-INF-UFG/SBRC2020-Minicurso3-Demo1-Exp3 "Demo 1 - Experiment 3"), [video](https://youtu.be/RxZBPlvrYng)) - UE através de hardware (smartphone convencional), RAN através de hardware (SDR) e software, e um núcleo EPC implementado através de software.
  * Demo 2 - Nesta demonstração, utilizamos um núcleo 5G baseado no modelo SBA de código aberto. Além disso, apresentamos como emular a RAN e múltiplos UEs.
    * Experimento 1 ([repository](https://github.com/LABORA-INF-UFG/SBRC2020-Minicurso3-Demo2-Exp1 "Demo 2 - Experiment 1"), [video](https://youtu.be/ZZZ8UjgyWn4) ) - UEs, RAN, e núcleo, todos implementados através de software.
    * Experimento 2 ([repository](https://github.com/LABORA-INF-UFG/SBRC2020-Minicurso3-Demo2-Exp2 "Demo 2 - Experiment 2"), [video](https://youtu.be/ph1dZNrduOU)) - UE através de hardware (smartphone convencional), eNodeB através de hardware (SDR) e software, e o núcleo 5G implementado através de software.
  * Demo 3 - Nesta demonstração, combinamos uma RAN baseado na tecnologia LTE com uma rede sem fio LoRa implementada em hardware. Para RAN LTE, usamos software de código aberto e um SDR. Também usamos uma implementação de código aberto do software de núcleo 5G baseado em SBA.
    * Experimento 1 ([repository](https://github.com/LABORA-INF-UFG/SBRC2020-Minicurso3-Demo3-Exp1 "Demo 3 - Experiment 1"), [video](https://youtu.be/nJpO95LuxLU)) - Sensores IoT LoRa através de hardware, IoT LoRa gateway através de hardware e software, RAN através de hardware (SDR) e software, e o núcleo 5G implementado através de software.
