Explicació breu de la pràctica:

L’objectiu d’aquesta pràctica és implementar una versió distribuïda d’un algorisme per multiplicar matrius. Per fer-ho, s’utilitzarà la tecnologia IBM-PyWren que és un projecte de codi obert que permet executar codi Python a l’escala de funcions del IBM Cloud.   
Per dur a terme la pràctica, es farà servir el model de programació Map que ens proporciona el IBM-PyWren. Aquest permet el processament de grans conjunts de dades dividits en blocs (chunks) gràcies a la distribució de múltiples nodes de treball (workers). Cada un d’aquests workers executa la funció que es crida des de map() amb la porció corresponent de les dades locals que li pertoca segons el que diu l’iterdata. Aquest últim és un array que divideix el conjunt de la informació a repartir entre workers i que ens servirà per enumerar els workers que voldrem per implementar la versió distribuïda de l’algorisme de multiplicació de matrius. 

	
Repositori github: 

	https://github.com/adriamachi/DS_A1_Machi_Simo