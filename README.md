# About

Part of speech tagged text from the Tibetan in Digital Communication project ([larkpie.net/tibetancorpus](http://larkpie.net/tibetancorpus/)).

These tagged texts include all three of the projects groups of corpora:

> At present, the corpus consists of three distinct collections. First, there is the Classical corpus.

> Second, there is the Saint Petersburg corpus, consisting of texts assembled and tagged by Pavel Grokhovski from Saint-Petersburg State University. We are re-tagging these texts in order to make them consistent with our scheme.

> Third, there is the Berlin corpus, kindly provided to us by Michael Balk. This corpus comprises the entire Tibetan catalogue of the Berlin State Library. It came to us fully segmented, but not tagged. We are now tagging the corpus after having converted it from Extended Wylie to Unicode.

> Together, these three collections constitute the "Complete corpus".


# Tags

```
The Classical corpus is the authoritative reference for our tagset, so should be the first point of reference. As noted above, the Saint Petersburg corpus comes via Pavel Grokhovsky, who used a different tagset. We have been converting his tagset to our system, but this work is not yet complete. Finally, the Berlin corpus is only partially tagged, and so includes a great many words with dummy tags (for example, xxx).

The following list provides further documentation on how to use our tagset.

adj
adjectives
Those words that can occur in attributive position and are not verbal nouns we define as adjectives; they are almost always multisyllablic. The paragon of adjectives are those that in -po, -mo, -pa, -ma, -can, -ldan, and -med. Etymologically -can, -ldan 'with', and -med 'without' are verbs, but when they occur in forms that are functioning nominally with the regards to syntax, they cannot be analyzed as verbs. So, we treat them together with the preceding syllable as an adjective. The formation of adjectives is a complex; which we intend to write about. In the mean time a search for words with this tag in the corpus will reveal some patterns. (Although words such as nag 'black', gsar 'new', and che 'big' are frequently treated like adjectives for pedagogical purposes, a single syllable in predicate position before verbal suffixes is a verb. These words may appear to occur attributively, but we see this as the formation of compounds. The compound blon-chen 'prime minister' contrasts beautifully with noun and adjective pair blon-po chen-po 'great minister', etc.) 
adv.dir
directional adverbs
We use this tag for adverbs that end in -cad, i.e. phyin-cad 'after', sṅon-cad 'before', man-cad 'below', yan-cad 'above', slan-cad 'after'. We also include phan-tshun 'mutually' in this category, for lack of a better place to put it.  Words tagged with this tag include: ཡན་ཆད་, མན་ཆད་, ཕན་ཚུན་, ཕྱིན་ཅད་, ཚུན་, ཚུན་ཅད་, སྔོན་ཅད་, སྔོན་ཆད་, སླན་ཅད་, ཕན་ཆད་, མན་ཅད་, ཡན་, ཡན་ཅད་  
adv.intense
intensive adverbs
This tag was created for the adverbs rab (tu) 'very' and śin (tu) 'very', because as uninflected stems they do not occur independently. Subsequently the tag has also been applied to ཅུང་ཟད་, ཡེ་, ཧ་ཅང་, ཆེས་, ནན་ཏ, and ཅུང་ཙམ་.   
adv.mim
mimetic adverb
This tag is used for onomatopoeia and phonophors. Examples include ཁོར་ཁོར་ཡུག་, ནར་ནར་, ཙབ་ཙོབ་, རྩོག་རྩོག་, ཁྲེ་ལོག་ལོག་, གཅེར་རེ་, ཅེ་རེ་, ཏབ་ཏབ་པོ, ཏབ་ཏོབ་, ཏུར་ཏུར་པོ་, རིག་རིག་, ལིང་, and ཧྲིག་ཧྲིག་.  
adv.proclausal
proclausal adverbs
A small number of words occur clause initially and refer to the content of the previous clause. Such adverbs often begin with a demonstrative stem. These words are classed as 'proclausal adverbs'. In the following list they are presented together with their affixal suffixes, but in our tagging we divide off these suffixes in order to be consistent with their treatment elsewhere: de (nas) 'then', de (ste) 'thereafter', gal (te) 'if', ḥo (na) 'in that case', ḥon (te) 'nevertheless', yaṅ (na) 'alternatively'. Words tagged with this tag include: དེ་, ཡང་, གལ་, ཁྱད་པ, འོ་, འོན་, དེ་བ, ལ, འང་, and སྒོས་. 
adv.temp
temporal adverbs
Temporal adverbs are those that occur in syntactic positions or have morphological structure that suggests they are nouns, that refer to time, and that are not followed by case markers. In our corpus so far the temporal adverbs are sṅon 'previously', da 'now', deṅ 'these days', mdaṅ 'yesterday', gdod 'at first', da-ruṅ 'still', phyi-ñin 'the next day', phyi-dro 'in the afternoon', and saṅ 'the next day'. There are also nouns that refer to time such as źag 'day' and gdugs 'noon', but these behave syntactically as nouns, for example by being suffixed with case markers. In the phrase saṅ gi gdugs la, where saṅ also appears to function as a noun, we have hesitatingly decided that for the time being it is best to tag saṅ as a temporal adverb. Words tagged with this tag include: ད་, སྔོན་, སྔ་, ད་དུང་, ནང་པ, ཕྱི་ཉིན་, ཁ་སང་, དོ་ནུབ་, གདོད་, ཉིན་, དེ་རིང་, དེང་, ནུབ་, མཚན་མོ་, ཅིག་ཅར་, གཟོད་, ཐོག་མ་, དབྱར་, དིང་སང་, མདང་, མཚན་, སང་, དགུན་, དེང་སང་, ནངས་པ, ཕྱི་, ཡུན་རིང་, སྲོད་, གདུགས་ཚོད་, གནངས་, གུང་, གློ་བུ, ཉིན་མཚན་, ད་ལོ, ནང་, ནངས་, ཕྱི་དྲོ་, མཚན་ཡལ་, འདང་, སླན་ཆད་, ཁར་རྩང་, ཁྲུགས་, གནའ་, གཟོད་མ་, ཉིན་ཞག་ཕྲུགས་, ད་ནང་, ད་རུང་, དོ་ནུབ, ནང་བ, ནངས་བ, ནམ་བཞིག་, ནུབ་མོ, ཕྱི་ཕྱི, མཚན་ཐོག་ཐག་, འཆར་ཁ་, འདང་གསུམ་, འཕྲོ་, རྒྱ་, སང་ཉིན་, སང་དགོང་, སང་ནང་པ, སྐྱ་རེངས་, སྔ་དྲོ་, སྔ་སོ, སྔ་སོ་, སྔོན, སྔོན་མ་. 
case.abl
ablative case
The ablative case is the morpheme las when it follows a substantive.
case.agn
agentive case
The agentive case is marked by any of the allomorphs -kyis, -gis, -gyis, -s, and -yis when suffixed to a substantive.
case.all
allative case
The allative case is the clitic morpheme la when it occurs suffixed to substantives.
case.ass
associative case
The associative case is the clitic morpheme daṅ when suffixed to a substantive.
case.comp
comparative case
The comparative case is either of the allomophs -bas or -pas suffixed to an substantive.
case.ela
elative case
The elative case is the clitic morpheme -nas when suffixed to substantives.
case.gen
genitive case
The genitive case is any of the allomorphs -kyi, -gyi, -gi, -yi, or -ḥi, when suffixed to a substantive.
case.loc
locative case
The locative case is the clitic morpheme -na when suffixed to a substantive. Note however that when -na appears after a verbal noun ending in -pa or -ba in the meaning 'if/when', we tag this -na as 'cv.loc'.
case.nare
the case -na-re
The case suffix -na-re which introduces direct speach.
case.term
terminative case
The terminative case is any of the allomorphs -tu, -du, -ru, -su, -r when suffixed to substantives.
cl.focus
Focus clitics
This tag was invented for the focus clitics ni and kyaṅ ~ yaṅ. The words currently tagged with this tag include: ནི་, ཡང་, ཀྱང་, འང་, ཅང་, and ཕྱིར་ཡང་. It is probably not correct to tag ཕྱིར་ཡང་ with this tag, but we must consider the matter further. The word lta when it is not tagged as a verb, or a relator noun, is also tagged as a focus clitic.  
cl.quot
The quotative clitic
We invented this tag for the 'quotative clitic' with the allomorphs ces, źes, and śes. However, the forms ce-na, ces-pa, etc. reveal that more properly this should be called a 'quotative verb' and tagged with a tag that begins with 'v'. Nonetheless, it is now inconvenient to change our approach. The words tagged with this tag are: ཞེས་, ཅེས་, ཞེས་པ་, ཞེ་, ཅེས་པ་, ཤེ་, ཅེ་, ཅེས་བ་, ཞིས་ (a misspelling of ཞེས་), and ཞེས་བ. 
cv.abl
ablative converb
The ablative converb is the morpheme las when it follows a verb.
cv.agn
agentive case
The agentive coverb is marked by any of the allomorphs -kyis, -gis, -gyis, -s, and -yis when suffixed to a verb.
cv.all
allative converb
The allative converb is the clitic morpheme la when it occurs suffixed to verbs.
cv.are
The converb -a-re
This tag is used to tag the converb -ta-re and its allomorphs (cf. Walter Wimon, 1967, 'The Tibetan Particle "re",' Bulletin of the School of Oriental and African Studies, 30.1, pp. 117-126). 
cv.ass
associative converb
The associative converb is the clitic morpheme daṅ when suffixed to a verbs. Note that this tag is particularly used with the polite imperative meaning of daṅ. One also sees daṅ in the meaning 'and' directly suffixed to morphological verb stems. In such cases we see daṅ as evidence that the preceding form is funtioning nominally and should be tagged [n.count], barring reasons to do otherwise.
cv.cont
continuing converb
The continuing converb, unknown in the early literature, is formally similar to the genitive followed by -n and functionally is similar to the imperfective converb in earlier strata of literature. The words tagged so far with this tag are: གིན་, ཀྱིན་, གྱིན་. 
 
cv.ela
elative converb
The elative converb is the clitic morpheme -nas when suffixed to verbs.
cv.fin
final converb
The final converb is any allomorph of the marker -ḥo, which is an explicit marker of a finitie verb in the indicative mood. Words tagged with this tag include: སོ, འོ, དོ, ངོ, ནོ, ཏོ, རོ, ལོ, གོ, བོ, མོ, and པོ. 
cv.gen
genitive converb
The genitive converb is any of the allomorphs -kyi, -gyi, -gi, -yi, or -ḥi, when suffixed to a verb.
cv.imp
imperative converb
The imperative converb is the morpheme that explicitly marks the imperative or prohibitive mood, which has one of the three allomorphs -śig, -cig, and -źig.  Our corpus yields the unexpected śig-pa, which we have also tagged with this tag.  
cv.impf
imperfective converb
The semi-final converb is the morpheme that has the three allomorphs ཞིང་, ཅིང་, and ཤིང་.  
cv.loc
locative case
The locative converb is the clitic morpheme -na when suffixed to a verbs, or when suffixed to a verbal noun ending in -pa or -ba in the meaning 'if/when'.
cv.odd
odd converbs
Odd converbs are any that we discovered after fixing the tagset. So far we the following words with this tag: ལས་ཆེ, ཨང་, ཚད་. 
cv.ques
question converb
The question converb is any allomorph of the marker -ḥam, which is an explicit marker of a polar question. Words tagged with this tag include: འམ, སམ, ནམ, དམ, གམ, ངམ, ཏམ, རམ, ལམ, བམ, མམ, ངེ་, and མཾ་   
cv.rung
The converb rung
When the morpheme ruṅ appears after a verb meaning 'however' it is tagged with this tag.
cv.sem
semi-final converb
The semi-final converb is the morpheme that has the three allomorphs ཏེ, སྟེ, and དེ.  
cv.term
terminative converb
The terminative converb is any of the allomorphs -tu, -du, -ru, -su, -r when suffixed to a verb.
d.dem
demonstratives
This tag is used for the demonstratives ḥdi 'this' and de 'that'. These two words are tagged as demonstratives also when used as determiners (i.e. we do not distinguish rgyal-po de 'that king' from de 'that one, him'). Words tagged with this tag include: དེ་, འདི་, ཡ, ཚུ, མ, ཕ, ཕྱི་, ཕ་གི་, མ་ཀི, མ་གི, མ་གི་, མ་ཀི་, འདི་པ, ཡ་གི་.  
d.det
determiner
The most frequent determiner is gźan 'other'. In addition, we identify ya-re 'each one (of two)' as a determiner on the basis of the following sentence: Brgya-byin daṅ Tshaṅs-paḥi rgyal-pos lag-pa ya-re nas zin te 'The kings Indra and Brahma each took him by one of his hands'. We reckon ḥbaḥ 'sole' as a determiner on the basis of sentences such as rus-pa daṅ khrag ḥbaḥ źig gis sa rtsog-rtsog ltar ḥdug-pa mthoṅ 'They saw the ground besmirched with only bone and blood'. Words tagged with this tag include: གཞན་, སོགས་, རང་, ཀ་, འབའ་, རེ་, རེ་རེ་, ག་, ཤ་སྟག་, ཁ་, གཞིན་, ཡ་རེ་, ཤས་དག་, སྣ་རེ་. We must check gzhin. 
d.emph
emphasis
We initially invented this category for ñid in phrases such as rgyal-poñid 'that very king' or lusñid 'this body'. This syntactic use of ñid must be distinguished form its use in Buddhist terminology -ñid inside of words, e.g. stoṅ-pa-ñid 'emptiness'.Apart from ñid, we have categorized kho-na 'the very, same' and re-re 'each' as emphatics. This use of kho-na should not be confused with its function as a third person pronoun in Old Tibetan. In one case kho appears not as a personal pronoun but as what seems to be a variant of kho-na; this kho we also classify as an emphatic, viz. smras-paḥi tshig ḥdi bden na bden-paḥi tshig bden-paḥi tshig smras-pas / bdag gi lus ḥdi sṅa-ma kho bźin du rma med-par gyur cig 'If these words that I have said are true, then because of saying true words, let this my body be without wounds like before' (vol 74, page 137b). Words tagged with this tag include: ཉིད་, རབ་, ཁོ་ན་, and ཁོ་.  
d.indef
indefinitie
This category is used for the allomorphs of the indefinite marker cig, źig, and śig as in pho-ña cig 'a messenger'. The indefinite marker, which occurs inside of noun phrases, must be distinguished from the identically looking imperative converb (see below), which occurs suffixed to the imperative stems of verbs.  
d.plural
plurals
The plural markers rnams, dag, kun, thams-cad, ḥo-cog (and its variants) and tsho are tagged as their own category 'plural'. However, plural pronouns (bdag-cag, khyed-cag, ḥu-bu-cag) are treated as one word. The plural marker -cag is not removed because to do so would result in pronominal stems which are not mutually comparable (viz. bdag is a singular pronoun, khyed a plural pronoun, and ḥu-bu has no independent life outside of ḥu-bu-cag). We also tag ḥgaḥ 'some' as a plural, although in the abstract one would perhaps prefer to call it a 'quantifier'.  The three verbs (la) sogs-pa 'etc', (daṅ) ldan-pa 'having', (daṅ) bcas-pa 'together with' could be seen as similar to quantifiers or otherwise to be treated as parts of the noun phrase, however, we have chosen to treat them etymologically as verbs. Words tagged with this tag include: རྣམས་, དག་, ཐམས་ཅད་, ཀུན་, ཡོངས་, སྣ་ཚོགས་, འགའ་, སྤྱི་, ཅུང་ཟད་, ཚོ་, དུ་མ, ཤས་, མཐའ་དག་, ཆུང་ཟད་, དགུ་ཅོག་, འགའ་རྫི་ར་, སོ་ཅོག་, སྣ་དགུ་. The inclusion of འགའ་རྫི་ར་ is probably a mistake.   
d.tsam
tsam and words with similar distribution
In an earlier version of the tag set we had tagged tsam as [cl.tsam], but then it became clear that it only ever followed nominals, so it clearly deserves the [d.xxx] category. Words tagged with this tag include ཙམ་, སྙེད་, ཙམ་པ་, རྙེད་ (a misspelling for སྙེད་), ཙམ་པ, སྙད་, and སྙེད་པ.  
interj
interjections
 This tag is used for interjections. Words tagged with this tag include: ཀྱེ་མ་, ཀྱེ་, ཨ་ལ་ལ་, ཀྱི་ཧུད་, ཁོ་དེ, མ་ལ་, འོ་དོད་, ཧེ་, ཨེ་མ་, and ཨེ་ཨེ་.  
n.count
count nouns
To identify lexical nouns we rely on the syntactic ability of the word in question to head a noun phrase, the dictionary meaning, and (when possible) the presence of nominal suffixes such as -mo, -po and -bu. Because we treat grammatical affixes as separate words, a single word normally does not not include grammatical affixes such as case markers and converbs. Nonetheless, there are well-motivated exceptions to this policy like gaṅ-na-ba 'whereabouts' and bdag-gi-ba 'that which is mine'. (We treat a -pa or -ba as part of the preceding word, regardless of the part-of-speech of the preceding word.) Another frequent category of exceptions is calques of Sanskrit terms, e.g. kun-tu-rgyu 'parivrājaka', which must be treated as a noun together because it looks like a verb phrase, but functions syntactically as a noun.  In general, when two nouns occur in succession they are understood as a compound; the dandva compound pha-ma 'parents' is treated as one noun rather than two (pha 'father' and ma 'mother') and the tatpuruṣa compound khyim-bdag 'householder' is likewise treated as one noun rather than two (khyim 'home' and bdag 'lord'). When an adjective precedes its head this is also treated as a compound. Thus, because dug btsan-po would be the expected order for 'mighty poison', we treat btsan-dug 'mighty poison' (vol. 74, page 147a) as a single word. Apposition is the one category of exceptions when the concatenation of two nouns is not treated as a compound. An example of this type is the two words bu khyeḥu in the following sentence: deḥi tshe yul de na khyim-bdag cig la bu khyeḥu źig btsas na / 'At that time, in that land, when a child, a son, was born to a householder'. Rather than understanding khyeḥu as an adjective modifying bu, or taking bu-khyeḥu as one word, the second word simply sits after the first one to add greater specificity. The reason to not treat apposition as compounding is because apposition occurs with proper nouns. For example, in the sentence deḥi tshe na rgyal-po Gsal-rgyal gyi btsun-mo chen-po Ḥbar-li źes bya-ba la bu-mo źig btsas-nas 'At that time a daughter was born to Ḥbar-li, the main queen of king Prasenajit', rgyal-po 'king' and Gsal-rgyal 'Prasenajit' are in apposition; to unite the two as a compound would lead to unintuitive, unwieldy, and therefore unacceptable consequences. 
n.mass
mass nouns
 We divide out mass nouns from normal lexical nouns on the basis of two instances in our corpus where otherwise two nouns not in apposition would follow each other: nor-bu sbar gaṅ 'a handful of jewels' and chu sñim-pa gaṅ 'a handful of water'. Knowing that there exists this syntactic difference between normal lexical nouns and mass nouns, we tag all plausible mass nouns on the basis of their meaning (e.g. zaṅs 'copper'). A final list of mass nouns can only be securely put forward after the syntactic behavior of these words is better investigated. Words tagged with this tag include:  གསེར་, ཆུ་, རིན་པོ་ཆེ་, ནོར་, ཤ་, ཆུ, ས་, ཁྲག་, ཆང་, སྨན་, སེར་བ་, ནོར་བུ་, མར་, ངུར་སྨྲིག་, དངུལ་, ཡི་གེ་, ནས་, ལྕགས་, སྤུ་, གངས་, ཙན་དན་, གསེར་གཡུ་, གོས་, དར་, ཤེལ་, གསེར་དངུལ་, པདྨ་རཱ་ག་, མར་ཁུ, ཟངས་, ཡིག་ (I would think that this should only occur in compounds), གོས་དར་, ཆུ་སྡོར་, ཐེར་ཕྲུག་, བཟའ་, བསུ་ཆང་, བུམ་ཆུ, བཻདཱུརྱ, མཐོ་ཁྱད་, རིན་ཆེན་, སྣམ་བུ་, ཁ་བ་, གསེར་གྱི་མེ་ཏོག་ (a mistake), ཆུ་མེ་ཤིང་, ཉ་ཕྱིས་, ཐལ་བ་, ཐུད་, དབུས་ཕྲུག་, བུར་, མཐོན་མཐིང་, མར་གད་, མར་སར་, ཚོས་, ཟ་མ་བཅུད་, འཇིམ་པ་, འདག་, རིན་ཆེན་གསེར་, རྒྱགས་ཆུ་, རྡུལ་ཚོན་, རྣག་ཁྲག་, ལ་ཅ, ལ་ཆ, ལེ་བརྒན་, ཤ་ཁྲག་, སེང་ལྟེང་, སེང་ལྡེང་, སེར་, སྤེན་, and སྤེན་བད་.  
n.prop
proper nouns
This tag is used for personal and place names.    
n.rel
relator nouns
A relator noun is a noun, normally one syllable, which has a genitive before it and a spatial case (allative, locative, terminative) after it, e.g. deḥi naṅ na 'inside of that', deḥi druṅ du 'before him', deḥi ḥog tu 'under that', deḥi tshe na 'at that time'; relator nouns are not quantified and are not suffixed with adjectives, determiners or demonstratives. After identifying the class of relator nouns, these words are tagged as relator nouns even in syntactic contexts missing the genitive to left or the spatial case to the right. For example, in the sentence deḥi tshe blon-po źig phyi-rol nas naṅ du ḥoṅs-pa las/ mi btson du bzuṅ-ba mthoṅ-ba daṅ / 'Then the minister went inside from outside and saw the man who had been taken to prison', the relator noun tshe is not followed by a spatial case and the relator noun naṅ is not preceded by a genitive.  In the phrase bar ḥgaḥ 'sometimes' we do not consider bar a relator noun because it undergoes quantification, e.g. … bar ḥgaḥ ni gti-mug gi phyir lus btaṅ yaṅ chos kyi phyir bsod-nams kyi źiṅ daṅ lan ḥgaḥ yaṅ ma phrad-paḥi lus ḥdi ci ruṅ ? 'What is the use of this body which … sometimes has been used because of ignorance, but has not yet met an occasion (to serve) as a field of merit'. Words tagged with this tag include: ལྟ, ཕྱི, བཞིན་, ཚེ་, སྐད་, བར་, དུས་, ནང་, རྗེས་, དྲུང་, ལྟ་བུ, འདྲ་, འོག་, སྟེང་, ལྟ་བུ་, སླད་, ངང་, ཕྱོགས་, མཐའ་, སྒོ་, བཞིན, ས, སླ, མདུན, དབུས་, ཐོག་, ཁོང་, ཕྱི་བཞིན་, ཁ, ཆེད་, ཐོག་མ, སྐབས་, གོང་, རྟིང་, ཐད་, གན་, མཇུག་, འཕྲལ་, ལོགས་, ཁྲོད་, རྟེན་, སྨད་, ཁོངས་, གསེབ་, ཐ་མ, དུས, ཕུ་, དྲུད་, བསེབ་, མགོ, ཙ་, རིང་, རྩ, ལྟག་, སྐོར་, དཀྱིལ་, དབུང་, བྱང་, མཐའ་ལོགས་, ཚུན་, ཞོར་, འཁྲིས་, འོག་བ, རྒྱབ་, སྐེ་, སྐེད་, སྙིང་ཁ, སྟེངས་, སྟོད་. Several questions of delimiting relator nouns require further consideration, in particular, the approach to lta versus lta-bu.  
n.v.aux
Nominalization of auxilliary verbs
This tag is used for the nominalized version of verbs that would be tagged [v.aux]. Forms currently tagged with this tag include དགོས་པ་, ནུས་པ་, ཤེས་པ་, དཀའ་བ་, ཕོད་པ་, ཐག་པ་, and རན་པ་.  
n.v.cop
Nominalization of copulas
This tag is used for nominalized versions of verbs that would be tagged [v.cop], q.v.
n.v.fut
Nominalization of a future verb stem
This tag is used for the nominalized versions of future verb stems, i.e. a future verb stem followed by pa, ba, tshul, rgyu, mkhan, mi, or bya.
n.v.fut.n.v.past
Nominalization of a future or past stem of a verb
This tag is used for nominalized forms of verb stems that would be tagged [v.fut.v.past], q.v. 
n.v.fut.n.v.pres
Nominalization of a future or present stem of a verb
This tag is used for the nominalized version of a verb stem that would be tagged [v.fut.v.pres], q.v.
n.v.imp
Nominalization of an imperative stem of a verb
The imperative stem of a verb is supposed not to be nominalized. However, in rare cases there are nominalized forms which appear to come from imperative stems, and we mark them accordingly. The form ཐོངས་པ་ is the only case that has come up so far.
n.v.invar
Nominalization of [v.invar]
This tag is used for nominalized forms of verb stems that would be tagged [v.invar] q.v.
n.v.neg
Nominalized form of the negative verb med
This tag is used for the nominalized forms of the inherently negated verb med, such as med-pa and med-sa. 
n.v.past
Nominalization of a past verb stem
This tag is used for the nominalized versions of past verb stems, i.e. a past verb stem followed by pa, ba, tshul, rgyu, mkhan, or mi.
n.v.past.n.v.pres
Nominalization of a past or present stem of a verb
This tag is used for the nominalized version of a verb stem that would be tagged [v.past.v.pres], q.v. 
n.v.pres
Nominalization of a present verb stem
This tag is used for the nominalized versions of present verb stems, i.e. a present verb stem followed by pa, ba, tshul, rgyu, mkhan, or mi.
neg
negation
The two negation prefixes ma and mi are classified together in their own category. The polar question prefix e is also categorized under this tag because it occupies the same syntactic position as ma and mi. For the two verbs min and med negation is inherent to their meaning, consequently 'neg' is also added to their POS-tags (i.e. min|v.cop.neg and med|v.neg see above).  
num.card
cardinal numbers
In numbers we distinguish cardinals (gcig, gñis, gsum, etc.) and ordinals (daṅ-po, gñis-pa, gsum-pa, etc.). Other derivatives of numerals are treated according to their respective syntax, thus gcig-pa 'sole' is an adjective, gñi-ga 'both' is an indefinite pronoun, etc. In higher numbers each component digit is tagged separately, to do otherwise would prevent the computer from learning pattens by virtue of having to independently learn each possible cardinal number of the infinite possibility. When a numeral follows a noun we regard the two as separate words. In addition to obvious cases like mi lṅa 'five men', we also treat dkon-mchog gsum 'triratna' as two words. While it is true that one will almost never encounter any other numeral after the word dkon-mchog this fact says as much about Buddhism as it does about syntax.  The treatment of phrag well exemplifies our pragmatic attitude toward part-of-speech tagging. Although not a cardinal number itself, this syllable occurs inside cardinal numbers, effectively marking a certain place with a zero, e.g. stoṅ phrag drug cu '1060'. Because the internal structure of numerals is not of interest to our project and adding a new tag for phrag would add unnecessary complications to our tag-set, we treat phrag itself as a cardinal number. There are occasions when the morphology of a word suggests that it might contain a numeral (e.g. mṅon-sum 'real', phun-sum-tshogs 'marvelous'), but there is no reason to see such cases as synchronically analyzable. Numbers that end with -po are also tagged [num.card].  
num.ord
ordinal numbers
In numbers we distinguish cardinals (gcig, gñis, gsum, etc.) and ordinals (daṅ-po, gñis-pa, gsum-pa, etc.). Other derivatives of numerals are treated according to their respective syntax, thus gcig-pa 'sole' is an adjective, gñi-ga 'both' is an indefinite pronoun, etc. In higher numbers each component digit is tagged separately, to do otherwise would prevent the computer from learning pattens by virtue of having to independently learn each possible cardinal number of the infinite possibility. Some adjectives can be distinguished from ordinal numbers only in context. For example, in the phrase rdo-rje rtse-lṅa-pa 'a five-pronged vajra' the noun phrase syntax and the overall meaning of the passage dictates that lṅa-pa is part of the word rtse-lṅa-pa 'five-pronged' rather than a word 'fifth'.   
p.indef
indefinite pronoun
The words la-la 'some', so-so 'each', and gñi-ga 'both' are used as indefinite pronouns in our pilot corpus. Words tagged with this tag include: ཁ་, སོ་སོ་, ལ་ལ་, རེ་རེ་, རེ་. (It looks like we are no longer putting gnyi-ga in here. I wonder why?) 
p.interrog
interrogative pronouns
 This is the tag used for interrogative pronouns such as su 'who', nam 'when', and gaṅ 'where'. Words tagged with this tag include: ཅི་, གང་, ཇི་, ཅི, སུ་, ནམ་, ཇི་སྲིད་, ག་, ག་རེ་, ཇི་ཙམ་, ཅི་སྲིད་, and ཙུག་. 
p.pers
personal pronouns
This tag is used for personal pronouns. Words tagged with this tag include: བདག་, ཁྱོད་, ང་, ཁྱེད་, བདག་ཅག་, ངེད་, ཁོ་, ཁོང་, རང་རེ་, ཁོ་བོ་, རང་, མོ་, ཁོ་མོ་, ཁྱེད་ཅག་, འོ་སྐོལ་, འུ་ཅག་, འོ་ཅག་. The word རང་ is only tagged as [p.pers] when it functions as a full independent pronoun in its own right; in ང་རང་ and ཁྱེད་རང་ the word རང་ is tagged [p.pers]. The word བདག་ is tagged as [p.pers] when it is a humble equivalent of ང་. When this word means 'lord' or ' the self' (philosophy) it is tagged [n.count] and when it means 'himself' it is tagged as [p.refl]. 
  
p.refl
reflexive pronouns
This tag is used for reflexive pronouns. The only word tagged with this tag རང་ and བདག་. The word རང་ is tagged as [p.refl] when it functions as a reflexive, in a sentence (invented) such as ཁོས་ དེ་རིང་ རང་ གི་ ཟན་ ཟོས་ སོ་ ' Today, he ate his own food' or in long form personal pronouns such as ང་རང་ and ཁྱེད་རང་. When རང་ is full independent pronoun meaning 'I'  or ' you' it is tagged [p.pers]. The word བདག་ is tagged as [p.pers] when it is a humble equivalent of ང་; when it means 'lord' or ' the self' (philosophy) it is tagged [n.count] and when it means 'himself' it is tagged as [p.refl]. 
  
p.refl
Reflexive pronoun
This tag is used for the words རང་ and བདག་ when they are used as reflexive pronouns, i.e. in the meaning 'himself, herself'. The word རང་ when it immediately appears after a personal pronoun is always tagged [p.refl].
punc
punctuation
While a tsheg is considered part of the preceding syllable, all other punctuation marks are tagged as punctuation. Such marks include །, ༑, །།, ༄༅༅།, and །།།།. Punctuation marks are broken apart to aid tokenization, e.g. we tag ༄|punc ༅|punc ༅|punc །|punc. 
skt
Sanskrit or other metalingustic elements
This tag was invented for the odd Sanskrit word that occurs in Tibetan (e.g. in mantras) not as a syntactic word in its own right, but as something metalinguisitc at least vis à vis Tibetan. On analogy to this use of Sanskrit words in Tibetan we have extended the use of the tag to include all metalinguistic forms, e.g. words used not as the words they are but as the name of that word, or the name of a letter, words in Roman script, etc.
v.aux
Auxiliary verbs
This tag is used for auxilliary verbs. By this we understand only thos verbs that show no morphological stem variation and may occur directly after another verb stem. The words we tag with this tag are: ཐག་, དགོས་, ནུས་, མོད་, འདོད་, ཤེས་, སྲིད་, ཤེས་, རན་, གྲགས་, ཐང་, and ཕོད་. Note that this set is far fewer than the total number of verbs that might be considered auxiliary verb in classical or modern Tibetan. In fact, we now feel that it was a mistake the give these tags a separate encoding, instead they should have been tagged on the basis of their syntax (e.g. mi [neg] nus [v.pres.v.fut]) and the question of auxiliation and other syntactic uses of verb stems in Tibetan addresssed systematically in a future project. However, once we arrived at this understanding it was inconvenient to change our approach. 
v.cop
Copula verbs
This tag is used for copula verbs, in particular yin and lags which do not distinguish various stems. In our current view, it would have been better not to have included this tag, but rather to have tagged these verbs according to their syntactic position, e.g. ma [neg] yin [v.past], yin [v.past.v.pres] nas [cv.ela], etc. However, when we made this determination it was already inconvenient to go back on the inclusion of the tag [v.cop]. 
v.cop.neg
The negative copula verb
This tag is used for the inherently negated copula verb min.
v.fut
Future stem of a verb
This tag is used for future stem verbs, e.g. bya, gzuṅ, sgrubs.
v.fut.v.past
Future or past stem of a verb
This tag is used for verb stems that are both morphologically and syntactically ambiguous between the past and futur, e.g. bskol.
v.fut.v.pres
Future or present stem of a verb
This tag is used for verb stems that are both morphologically and syntactically ambiguous between the past and present, e.g. gśegs in the phrase mi gśegs.
v.imp
Imperative stem of a verb
This tag is used for imperative verb stems, e.g. byos, zuṅ, sgrubs.
v.invar
Present, past, or future stem of a verb
This tag is used for verb stems that are morphologically and syntactically ambiguous among present, past, and future, e.g. gśegs in the phrase gśegs so.
v.neg
The negative verb med
This tag is used for the inherently negated verb med.
v.past
Past stem of a verb
This tag is used for past stem verbs, e.g. byas, bzuṅ, bsgrubs.
v.past.v.pres
Past or present stem of a verb
A verb stem that is both morphologically and syntactically ambiguous between the past and present, e.g. gśegs in the prhase gśegs nas.
v.pres
Present stem of a verb
This tag is used for present stem verbs, e.g. byed, ḥdzin, sgrub.
```

# License

> All software written as part of this project will be released under an open source license. Our Tibetan pos tagging software, incorporating a word segmentation component, will be released on Tibetan NLP, a GitHub page collecting tools and resources related to natural language processing of Tibetan. The page also has contributions from the Tibetan Buddhist Resource Center and the Tibetan & Himalayan Library.