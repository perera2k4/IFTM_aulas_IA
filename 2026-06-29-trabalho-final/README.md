# Classificação de Espécies de Cogumelos por Imagem `Combined Kaggle Mushrooms Dataset` 

As dificuldades encontradas foram a de balancear resultados por tempo de execução, haja vista que o código sempre mantém um mesmo padrão e tem poucas alterações, mas para conseguir ter boa acurácia sem demorar 7 horas para executar o dataset foi cortado reduzindo resultado priorizando tempo, podendo acompanhar o aprendizado (execução) de ambos os modelos pelo: loss= & acc=.

## Como executar 

Infelizmente não consegui desenvolver uma forma para verificação de imagem que seja rápida (menos de 5 minutos) e com boa acurácia, da maneira que está feita é a que mais tem acertividade ao anexar uma imagem aleatória de quaisquer espécies citadas abaixo contida no dataset.

Mas para executar basta ter conexão com a internet, clonar o repositório e iniciar a execução completa dos arquivos `.ipynb`.

### Modelo 1: `MobileNet_V2`

Separei apenas 2% do dataset original, com tempo médio de execução de: 14 minutos mantendo boa acurácia, abaixo está a lista de espécies treinadas que podem ser anexadas no path de imagens `image_path = ""`.

### Modelo 2: `EfficientNet-B0`

Separei apenas 2% do dataset original, com tempo médio de execução de: 20 minutos mantendo boa acurácia, abaixo está a lista de espécies treinadas que podem ser anexadas no path de imagens `image_path = ""`.


### Espécies diponiveis para verificar por imagem

- Agaricus augustus
- Agaricus xanthodermus
- Amanita amerirubescens
- Amanita augusta
- Amanita brunnescens
- Amanita calyptroderma
- Amanita citrina
- Amanita flavoconia
- Amanita muscaria	
- Amanita pantherina
- Amanita persicina
- Amanita phalloides
- Amanita rubescens
- Amanita velosa
- Apioperdon pyriforme	
- Armillaria borealis
- Armillaria mellea
- Armillaria tabescens
- Artomyces pyxidatus	
- Bjerkandera adusta
- Bolbitius titubans
- Boletus edulis	
- Boletus pallidus
- Boletus reticulatus
- Boletus rex-veris
- Calocera viscosa
- Calycina citrina
- Cantharellus californicus
- Cantharellus cibarius
- Cantharellus cinnabarinus
- Cerioporus squamosus	
- Cetraria islandica
- Chlorociboria aeruginascens
- Chlorophyllum brunneum
- Chlorophyllum molybdites
- Chondrostereum purpureum
- Cladonia fimbriata
- Cladonia rangiferina
- Cladonia stellaris
- Clitocybe nebularis
- Clitocybe nuda
- Coltricia perennis
- Coprinellus disseminatus
- Coprinellus micaceus
- Coprinopsis atramentaria
- Coprinopsis lagopus
- Coprinus comatus	
- Crucibulum laeve
- Cryptoporus volvatus
- Daedaleopsis confragosa
- Daedaleopsis tricolor
- Entoloma abortivum
- Evernia mesomorpha
- Evernia prunastri	
- Flammulina velutipes
- Fomes fomentarius	
- Fomitopsis betulina	
- Fomitopsis mounceae
- Fomitopsis pinicola	
- Galerina marginata
- Ganoderma applanatum	
- Ganoderma curtisii
- Ganoderma oregonense
- Ganoderma tsugae
- Gliophorus psittacinus
- Gloeophyllum sepiarium
- Graphis scripta
- Grifola frondosa
- Gymnopilus luteofolius
- Gyromitra esculenta
- Gyromitra gigas	
- Gyromitra infula
- Hericium coralloides
- Hericium erinaceus
- Hygrophoropsis aurantiaca
- Hypholoma fasciculare
- Hypholoma lateritium
- Hypogymnia physodes	
- Hypomyces lactifluorum
- Imleria badia
- Inonotus obliquus
- Ischnoderma resinosum
- Kuehneromyces mutabilis
- Laccaria ochropurpurea
- Lactarius deliciosus
- Lactarius torminosus
- Lactarius turpis
- Laetiporus sulphureus	
- Leccinum albostipitatum
- Leccinum aurantiacum
- Leccinum scabrum	
- Leccinum versipelle
- Lepista nuda
- Leratiomyces ceres
- Leucoagaricus americanus
- Leucoagaricus leucothites
- Lobaria pulmonaria
- Lycogala epidendrum
- Lycoperdon perlatum	
- Lycoperdon pyriforme
- Macrolepiota procera
- Merulius tremellosus
- Mutinus ravenelii
- Mycena haematopus
- Mycena leaiana
- Nectria cinnabarina
- Omphalotus illudens
- Omphalotus olivascens
- Panaeolus papilionaceus
- Panellus stipticus
- Parmelia sulcata	
- Paxillus involutus
- Peltigera aphthosa
- Peltigera praetextata
- Phaeolus schweinitzii
- Phaeophyscia orbicularis
- Phallus impudicus
- Phellinus igniarius
- Phellinus tremulae
- Phlebia radiata
- Phlebia tremellosa
- Pholiota aurivella
- Pholiota squarrosa
- Phyllotopsis nidulans
- Physcia adscendens
- Platismatia glauca
- Pleurotus ostreatus
- Pleurotus pulmonarius
- Psathyrella candolleana
- Pseudevernia furfuracea
- Pseudohydnum gelatinosum
- Psilocybe azurescens
- Psilocybe caerulescens
- Psilocybe cubensis
- Psilocybe cyanescens
- Psilocybe ovoideocystidiata
- Psilocybe pelliculosa
- Retiboletus ornatipes
- Rhytisma acerinum
- Sarcomyxa serotina
- Sarcoscypha austriaca
- Sarcosoma globosum
- Schizophyllum commune	
- Stereum hirsutum
- Stereum ostrea
- Stropharia aeruginosa
- Stropharia ambigua
- Suillus americanus
- Suillus granulatus
- Suillus grevillei
- Suillus luteus
- Suillus spraguei
- Tapinella atrotomentosa
- Trametes betulina
- Trametes gibbosa
- Trametes hirsuta
- Trametes ochracea
- Trametes versicolor
- Tremella mesenterica
- Trichaptum biforme
- Tricholoma murrillianum
- Tricholomopsis rutilans
- Tylopilus felleus
- Tylopilus rubrobrunneus
- Urnula craterium
- Verpa bohemica
- Volvopluteus gloiocephalus
- Vulpicida pinastri
- Xanthoria parietina	