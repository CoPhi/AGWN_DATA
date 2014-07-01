### ANCIENT GREEK WORDNET CREATION RULES #######
The AGWN and LWN synsetids are mapped over PWN according to the following rules

1) PWN USED AS PIVOT

2) THE SYNSET ID SWITHCES ACCORDING TO THE PART OF SPEECH (SAME RULE AS FOR PWN: 1 FOR NOUNS, 2 FOR VERBS...)
IN THE ORIGINAL FILE IF THE SAME PWN ID GROUPS GREEK WORDS WITH DIFFERENT POS, THEN THE SYNSETID CHANGES ACCORDINGLY. 
EXAMPLE ARM 102737660 (NOUN) POINTS TO 
	1001102737660  (N) the part of an armchair or sofa that supports the elbow and forearm of a seated person [βραχίων, κουρβών, ἐπίχειρον]  
	AND
	2001102737660  (V) the part of an armchair or sofa that supports the elbow and forearm of a seated person [ἐνθωρακίζω, ὁπλοδοτέω, κορύσσω]

3) PWN =POS+8DIGIT ID  AGWN POS+LANCODE+PWN
WHERE LANGCODE IS A 3 DIGIT ID FOR THE LANGUAGE (001 FOR GREEK, 002 FOR LATIN, 003 for ARABIC) 
Example
PWN = 100002684
AGWN 2 001 100002684 (2001100002684)

Example
PWN = 102737660
AGWN 1 002 102737660 (1002102737660)

IMMEDIATE REFEREFENCE TO PWN AND CROSS POS MAPPING


ACCESS TO THE RESOURCE
http://www.languagelibrary.eu/new_ewnui/index.php
THE AGWN IS NOT COMPLETE AND NEEDS FURTHER VALIDATIONS. EVERY TIME A VERSION IS READY IT WILL BE UPLOADED 

THE DATASET IS LICENSED UNDER A CC-BY-NC-SA 4.0 
AGWN by H. Diakoff - F. Boschetti - R. Del Gratta - Y. Bizzoni is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
Based on a work at http://www.languagelibrary.eu/new_ewnui/index.php.
IF YOU USE THE DATASET IN A WEB WORK, PLEASE COPY AND PASTE THE FOLLOWING REMARK:

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">AGWN</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">H. Diakoff - F. Boschetti - R. Del Gratta - Y. Bizzoni</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="http://www.languagelibrary.eu/new_ewnui/index.php" rel="dct:source">http://www.languagelibrary.eu/new_ewnui/index.php</a>.

