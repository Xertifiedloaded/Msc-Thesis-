<div align="center">

# PRE-DATA SEMINAR

### ON

## COMPARISON OF DIFFERENT NONLINEAR AND REGRESSION MODELS FOR DESCRIBING GROWTH CURVES 

### BY

**MAKINDE, OLAITAN OREOFE**

`PG/24/1/0291`

B.Agric (Abeokuta)

---

**DEPARTMENT OF ANIMAL BREEDING AND GENETICS**

**COLLEGE OF ANIMAL SCIENCE AND LIVESTOCK PRODUCTION**

**FEDERAL UNIVERSITY OF AGRICULTURE, ABEOKUTA, OGUN STATE**

---

**NOVEMBER, 2026**

</div>

---

> **Digital reading edition**  
> This Markdown version is arranged for comfortable reading on GitHub. The text follows the proposal; original Word file is retained in `original/` for full formatting and document layout.

## Contents

- [Chapter One — Introduction](#chapter-one)
- [Chapter Two — Literature Review](#chapter-two)
- [Chapter Three — Materials and Methods](#chapter-three)
- [References](#references)

---

---

# Chapter One

### **1.0** INTRODUCTION

The domestic chicken (Gallus gallus domesticus) is among the most widespread farm animals in the world, with a global standing population of roughly 27 billion birds in 2023 (FAO, 2025). Biologically, growth is a complex process involving cell replication, tissue differentiation, matrix formation, cell death and other interrelated mechanisms (Fatai et al., 2023). It continues from the embryonic stage to adulthood, and its pattern can be described by growth curve models that relate body weight, or other body measurements to age.

In poultry, body weight typically follows a sigmoid curve. Growth accelerates after hatching, is fastest at the inflection point, then decelerates as the bird approaches its mature (asymptotic) weight (Osaiyuwu et al., 2024; Isa and Joel, 2026). The Gompertz, Logistic, von Bertalanffy, Brody and Richards functions are among those most often fitted to chicken growth data (Fatai et al., 2023; Osaiyuwu et al., 2024). Each summarises repeated weight-age records into a few biologically interpretable parameters (Fatai et al., 2023).

These parameters allow breeders to predict body weight at a given age (Osaiyuwu et al., 2024) and support decisions on feeding and management at specific stages of development (Ghaderi-Zefrehei et al., 2024; Isa and Joel, 2026). Because they describe the time-dependent change in live weight, they have also been proposed as selection criteria (Kaya Başar and Narinç, 2023; Ghaderi-Zefrehei et al., 2024). Growth curve parameters are heritable, with estimates ranging from low to moderate (Kaya Başar and Narinç, 2023; Ghaderi-Zefrehei et al., 2024), which supports their use in poultry selection studies.

Improved chicken genetics developed or adapted for Nigerian conditions include FUNAAB Alpha and Noiler. In an on station comparison of six breeds, both were identified as more suitable for dual purpose (egg and meat) production, and the breeds differed significantly in live weight, age at first egg and mortality (Bamidele et al., 2020). The two genotypes followed different growth patterns. Noiler outperformed FUNAAB Alpha in body weight and linear body measurements between weeks 10 and 18 (Sanda et al., 2022), and on-farm trials ranked Noiler among the faster-growing breeds and FUNAAB Alpha among the slower ones (Ajayi et al., 2020).

Nonlinear growth models have been fitted to FUNAAB Alpha, its crossbreds and exotic broilers, but only over the early growth period, up to 10 weeks (Ogunpaimo et al., 2020). Most Nigerian comparisons of these genotypes have therefore concentrated on mean body weight, weight gain, feed intake, feed conversion and linear body measurements at specific ages. Few studies have compared the complete nonlinear growth trajectories of these genotypes under the same management.

### Justification

Poultry production is one of the fastest-growing agricultural subsectors in Nigeria, and it remains central to national efforts to improve animal protein supply, household income and food security (Anosike et al., 2018; Adeyonu and Odozi, 2022). With a rapidly growing population and a persistent protein deficit, the sector depends on birds that perform well under tropical conditions. Indigenous chickens are well adapted to local environments but grow slowly and produce modestly (Permin and Pedersen, 2000; Hoffmann, 2005;  Sanusi and Oseni, 2019), while exotic commercial broilers grow quickly but are costly to raise and sensitive to heat stress, disease and variable feed quality (Settar et al., 1999; Deeb and Cahaner, 2001, 2002;  Son et al., 2022). This gap has motivated the development of improved, locally adapted strains such as the FUNAAB Alpha (a dual-purpose bird developed at the Federal University of Agriculture, Abeokuta) and the Noiler, both of which are increasingly adopted by smallholder and semi commercial farmers (Ajayi et al., 2020; Adamu et al., 2021;  Bamidele et al., 2020, 2022). As their popularity grows, there is a corresponding need for sound quantitative information on how these birds actually grow.

Growth is a defining economic trait in poultry because it determines age at slaughter, feed conversion efficiency, feeding cost and the timing of marketing or onset of lay. Growth curves summarise the relationship between body weight and age using a small set of biologically meaningful parameters, typically the asymptotic (mature) weight, the rate of maturing and the inflection point. These parameters allow breeders and farmers to predict performance, identify the age of maximum growth, design phase-feeding programmes, and compare genotypes or select for improved growth patterns. A well-fitted growth curve therefore translates raw weight records into practical management and breeding decisions.

Several nonlinear models, including the Gompertz, Logistic, von Bertalanffy, Richards, Brody and Negative Exponential, as well as polynomial and other regression models, have been used to describe growth in livestock and poultry (von Bertalanffy, 1957; Yakupoğlu and Atil, 2001; Tjørve, 2010, 2017; Narinç et al., 2017; Teleken et al., 2017). However, no single model fits all species, strains or data sets equally well. Model performance depends on the genotype, sex, sampling interval, environment and the range of ages covered . Fitting an inappropriate model can produce biased estimates of mature weight and growth rate, leading to flawed management and selection decisions. Moreover, nonlinear models often present convergence problems and parameter correlations, whereas simpler regression models are easier to fit but may lack biological interpretability. Choosing between them requires a formal comparison using goodness-of-fit criteria such as the coefficient of determination (R²), adjusted R², Akaike and Bayesian information criteria, residual mean square error and residual diagnostics.

Despite the growing use of FUNAAB Alpha and Noiler chickens, published information on their growth curves is limited (Bashiru et al., 2019a, 2019b; Ogunpaimo and Wheto, 2020; Adamu et al., 2021; Isa and Joel, 2026), and few studies have compared multiple nonlinear and regression models side by side on these two strains under the same conditions. Existing reports often focus on exotic broilers or indigenous ecotypes (Roush et al., 2006;  Sanusi and Oseni, 2019; Fatai et al., 2023; Ugwuja et al., 2025), whose growth patterns may not be representative of these improved dual-purpose and meat-type crosses. Extrapolating results from other genotypes is therefore risky and may not reflect the true growth dynamics of the birds farmers are keeping.

This study is therefore justified on scientific, practical and economic grounds. Scientifically, it will identify the model that best describes growth in each genotype and provide reliable parameter estimates for future research, since the choice of an appropriate growth model has been shown to depend on genotype and sex in dual-purpose chickens (Durosaro et al., 2021). Practically, it will guide farmers on optimal slaughter age, feeding regimes and flock management for each genotype. Economically, it will help reduce production costs by avoiding prolonged rearing beyond the point of diminishing returns. Finally, it will provide baseline growth information for breeders working on genetic improvement of these locally developed strains, which have been identified as suitable dual-purpose genetics for smallholder production in Nigeria (Bamidele et al., 2020, 2023). The findings will thus contribute to more efficient, evidence-based poultry production in Nigeria and the wider tropics.

### **1.2** Broad objective

Comparison of different nonlinear and regression models for describing growth curves  in FUNAAB Alpha (dual purpose) and Noiler chickens

### **1.3** Specific objectives

To fit nonlinear growth models (Gompertz, Logistic, Von Bertalanffy, Richards and Brody), linear and polynomial regression models to the body weight data of FUNAAB Alpha and Noiler chickens.

To estimate and compare the growth parameters of each model, namely asymptotic (mature) weight (A), growth rate constant (k), and inflection point (age and weight at inflection), for both strains and to identify the best-fitting model for each strain..

To compare the goodness of fit of the candidate nonlinear growth models using R², RMSE, AIC, BIC and residual diagnostics.

To evaluate whether sex and genotype × sex interaction contribute to differences in the estimated growth trajectories.

To compare the growth characteristics of FUNAAB Alpha and Noiler chickens based on the fitted models, to identify differences in growth rate and maturity pattern between the dual-purpose and Noiler strains.

---

# Chapter Two

### **2.0** LITERATURE REVIEW

### **2.1** Growth patterns and growth curve characteristics in chickens

#### **2.1.1** Concept and biological basis of growth

Growth is a continuous biological process characterized by age related changes in body size, body weight and tissue development. In chickens, these changes involve the coordinated development of skeletal, muscular, adipose and visceral tissues from the embryonic stage through the post-hatch period until maturity. The pattern of growth is influenced by the interaction between the bird's genetic potential and environmental conditions. Factors such as genotype, sex, nutrition, temperature, stocking density, health status and management practices can therefore produce differences in growth rate and final body size among birds. Consequently, body weight measured at a particular age provides information on performance at that point but does not adequately explain the pattern of growth throughout the production period. Repeated measurements across different ages are therefore important for describing the trajectory of growth and identifying differences in growth patterns among chicken genotypes.

Growth curve modelling has been increasingly used to describe the changes in body weight of poultry over age because it provides a mathematical representation of the entire growth process. Rather than relying only on comparisons of body weight at specific ages, growth functions allow researchers to estimate biologically meaningful parameters such as mature weight, growth rate and the age at which the maximum growth rate occurs. Different mathematical functions have been evaluated for poultry, including the Logistic, Gompertz, von Bertalanffy, Richards, Weibull and Morgan Mercer Flodin models. Comparative studies have shown that these functions can describe chicken growth with varying degrees of accuracy, indicating that model performance depends partly on the characteristics of the population and the data used (Narushin and Takma, 2003; Topal and Bolukbasi, 2008).

Evidence from previous studies indicates that no single growth function consistently provides the best description for all chicken populations (Fatai et al., 2023; Isa and Joel, 2026). For instance, comparisons involving broilers and laying hens have shown differences in the goodness of fit of alternative growth functions (Narushin and Takma, 2003; Topal and Bölükbaşı, 2008). The Logistic, Gompertz and von Bertalanffy models have nevertheless received considerable attention in poultry growth research because their parameters have biological interpretations that can be related to the development of the birds (Fatai et al., 2023). In particular, the asymptotic weight provides an estimate of mature body size, while the inflection point indicates the age and body weight associated with the maximum rate of growth (Isa and Joel, 2026).

These parameters make growth curve models useful not only for describing growth but also for comparing growth characteristics among genotypes and evaluating management decisions.

The application of growth models is particularly relevant in commercial poultry production because differences in growth trajectory can influence the efficiency with which birds utilize feed and reach market weight. A genotype that reaches a desirable market weight earlier may have different production requirements from one with a slower growth trajectory. Therefore, examining the complete growth pattern rather than comparing body weight at a single age can provide a more comprehensive basis for understanding genetic differences in growth performance. This variation also suggests that competing growth functions should be evaluated within the specific chicken populations and production conditions under study, rather than assuming that a model suitable for one population will best describe another (Fatai et al., 2023).

#### **2.1.2** Sigmoid pattern of chicken growth

Chicken growth is commonly described by a sigmoid, or S-shaped, curve. During the earliest period after hatch, the increase in body weight is relatively slow. This is followed by an accelerating phase, during which the absolute rate of gain rises with age. The curve then reaches an inflection point, defined as the age at which absolute growth rate is maximal. Thereafter, growth decelerates as the bird approaches its mature or asymptotic weight. Nonlinear growth functions summarize this biological pattern and make it possible to estimate parameters that cannot be obtained directly from one weekly body-weight record (Aggrey, 2002; Narinç et al., 2017).

The exact shape of the curve differs among breeds and strains. Commercial broilers have undergone intense selection for rapid early growth and feed efficiency, whereas dual-purpose and tropically adapted chickens may show slower early growth, different maturation rates and lower estimated asymptotic weights. This means that the genotype with the largest body weight at six or eight weeks is not necessarily the genotype with the largest predicted mature size, nor will all genotypes attain their maximum growth rate at the same age.

#### **2.1.3** Factors affecting chickens growth

Growth of chickens is influenced by a combination of genetic, environmental, nutritional and health related factors.

##### **2.1.3.1** Genetics (strain and sex)

Genetic selection has played a major role in the substantial improvement in growth performance observed in modern broiler chickens. Long-term comparisons of broilers selected at different periods have demonstrated remarkable increases in growth rate, accompanied by improvements in feed efficiency, indicating the considerable contribution of genetic improvement to modern broiler production (Havenstein et al., 2003; Zuidhof et al., 2014). The improvement observed over successive generations has been associated primarily with genetic selection, although advances in nutrition and feeding practices have also contributed to the overall performance of modern broilers (Havenstein et al., 2003).

Growth characteristics, however, are not uniform across chicken populations. Differences in growth curve parameters have been observed among strains and between sexes, suggesting that genetic background and sex can influence both the rate and pattern of body weight development (Aggrey, 2002; Topal and Bolukbasi, 2008). These differences may become more pronounced as birds progress through later stages of growth, when genetic differences in mature body size and growth potential become increasingly expressed (Zuidhof et al., 2014). Therefore, evaluating growth through repeated measurements and growth curve parameters provides a more informative assessment of genetic differences than comparing body weight at a single age.

##### **2.1.3.2** Environment: temperature and stocking density

Environmental conditions are important determinants of growth performance in chickens because they influence feed intake, nutrient utilization, physiological responses and, ultimately, body weight gain. Among the environmental factors, high ambient temperature and excessive stocking density can impose considerable stress on broilers and interfere with normal growth. Heat stress can reduce voluntary feed consumption and impair nutrient utilization as birds attempt to regulate their body temperature, thereby limiting the nutrients available for tissue growth. Similarly, overcrowding can restrict air movement, increase competition for resources and intensify physiological stress.

Experimental evidence indicates that these factors can act individually or together to reduce growth performance. For example, broilers reared under high stocking densities of 23 and 26 birds/m² and exposed to high ambient temperature showed reduced body weight, together with increases in rectal temperature and corticosterone concentration, indicating greater physiological stress (Son et al., 2022). Findings from other studies also show that exposure to elevated temperature and increased stocking density can reduce feed intake and weight gain, with the negative effects of high stocking density becoming evident in final body weight at market age. These findings demonstrate that observed differences in growth among chicken genotypes should be interpreted alongside the environmental conditions under which the birds are reared, since management and climatic factors can influence the expression of their genetic growth potential.

##### **2.1.3.3** Nutrition and feed intake

Nutrition determines whether a bird can express its genetic growth potential, and the performance of modern strains depends on both selection and the diets they are fed (Havenstein et al., 2003b). Environmental stress also depresses growth: finisher broilers kept at high stocking density under high temperature had significantly lower body weight (Son et al., 2022).

##### **2.1.3.4** Health and management

Disease, litter quality and general husbandry also influence growth. High stocking density has been associated with higher litter moisture, ammonia levels and footpad lesions, which may compromise welfare and reduce mobility and feed access. In addition, selection for rapid growth has been linked to leg disorders and cardiovascular problems in fast-growing broilers, so growth rate and health status are closely connected.

#### **2.1.4** Economic importance of chicken growth

Growth rate is a fundamental factor influencing the biological and economic efficiency of poultry production because it determines how quickly chickens convert available resources into marketable body weight. Birds that grow rapidly and efficiently can attain market weight within a shorter production period, allowing producers to recover invested capital earlier and potentially complete more production cycles within a year. This has become particularly important in broiler production, where sustained genetic selection has resulted in substantial improvements in growth and feed efficiency. For example, comparisons of broilers from 1957 and 2005 showed that growth rate increased by more than 400%, while feed conversion ratio decreased by approximately 50%, demonstrating the extent to which genetic improvement has enhanced the efficiency of meat production (Zuidhof et al., 2014).

The economic significance of these improvements is particularly evident because feed remains one of the major costs of broiler production. In Nigeria, feed has been reported to account for about 75% of the total variable cost of producing broilers, and broiler farming has been found profitable, with feed type, flock size, and farmer experience among the factors influencing profitability (Adeyonu and Odozi, 2022). Thus, growth performance should not be viewed simply as the ability of a bird to attain a high final body weight. The rate at which body weight is accumulated is also important because prolonged growth may increase the amount of feed, labour, housing, and other resources required before birds reach marketable size.

This relationship is particularly relevant under current poultry market conditions. In 2026, broiler chicken may be sold at approximately ₦3,500 or ₦4,000 per kilogram in some Nigerian markets, although the actual price varies according to location, market conditions, and whether the bird is sold live or dressed. At this market value, a difference in growth rate can translate into a substantial difference in the quantity and timing of marketable output generated by a flock. For instance, a bird that reaches a given market weight earlier can potentially generate revenue sooner while reducing the duration over which production inputs are expended. Conversely, slower growing birds may require a longer production period, during which additional feed and other resources are consumed. Growth rate therefore has implications not only for biological performance but also for the economic efficiency of poultry enterprises.

The importance of efficient growth extends beyond individual farm profitability because poultry meat is an important source of animal protein and contributes to the supply of relatively affordable meat. Increasing demand for poultry products in Nigeria has created a need for production systems capable of generating greater quantities of meat efficiently. Previous projections indicated annual growth in poultry meat demand of approximately 6–10% between 2020 and 2025, with concerns that the gap between domestic demand and local supply could widen (Adeyonu and Odozi, 2022). Improving the growth performance and feed efficiency of chickens can therefore contribute to increased meat production while helping producers manage the costs associated with expanding output.

However, chickens do not maintain the same rate of growth throughout their production period. Growth changes with age and may differ according to genotype, nutrition, health status, environmental conditions, and management practices. Problems such as disease-associated runting and stunting can further alter normal growth and reduce flock productivity. Consequently, evaluating chickens only on the basis of their final body weight may overlook important differences in how birds reach that weight. Two genotypes may have similar weights at a particular age but follow different growth trajectories, with one genotype growing more rapidly during the early phase and another exhibiting greater growth later in the production period.

For this reason, understanding the trajectory of growth is important for identifying differences in the growth potential of chicken genotypes. Growth modelling provides a means of describing these changes mathematically and of estimating parameters that characterize the pattern and rate of growth over time. Such information can help distinguish genotypes according to their growth characteristics and provide a more comprehensive assessment than final body weight alone. Taken together, this literature demonstrates a clear connection between growth rate, feed utilization, production costs, market weight, and profitability. Under current market conditions, where broiler meat can command approximately ₦3,500 per kilogram, understanding how quickly and efficiently different genotypes accumulate body weight is increasingly relevant to both producers and researchers.

### **2.2** Description of the study genotypes

#### **2.2.1** Growth performance of FUNAAB Alpha chickens

Crossbreeding is a mating system in which individuals from two different breeds are mated so that the offspring combine desirable traits from both parents. Its central aim is to exploit heterosis (hybrid vigour), so that the progeny perform better and are worth more economically than either parental breed (Hanafi and Iraqi, 2002). In poultry, it is widely used to improve economically important traits, especially growth rate, feed efficiency and meat quality, and much effort has gone into developing broiler strains that deliver good-quality meat at a lower cost of production (Kemp and Kenny, 2003). Breeders have also used hybrid vigour extensively to obtain progeny whose phenotypic performance exceeds that of the parent populations.

Commercial poultry production expanded rapidly around the world in the 1990s, yet genetic improvement in developing countries has remained slow. This has been linked to poor access to modern breeding technologies, limited financial resources and the small scale of production compared with developed countries (Hoffmann, 2005). As a result, breeding programmes in Nigeria have concentrated on raising the productivity of indigenous chickens while preserving their adaptation to the local environment.

Nigerian indigenous chickens tolerate harsh climates, resist endemic diseases and can survive on poor-quality feed. They are, however, slow growing, convert feed inefficiently and reach only low body weights, which makes them unsuitable for intensive commercial production (Ogunpaimo et al., 2020). Although these adaptive traits make them a valuable genetic resource, their weak productive performance has limited their uptake in commercial systems.

To address these shortcomings, scientists in the Department of Animal Breeding and Genetics, Federal University of Agriculture, Abeokuta (FUNAAB), developed the FUNAAB Alpha chicken as an improved Nigerian indigenous chicken with higher productivity and the adaptive qualities of its parent stock retained (Udoh, 2014). The breed has broiler and dual-purpose lines, and each line includes normal-feathered, naked-neck and frizzle-feathered genotypes. Following extensive evaluation, the Federal Government of Nigeria approved it for distribution as an improved, locally adapted, dual purpose chicken for both rural and commercial production (Ogunpaimo et al., 2020). Work to improve its productivity further is still in progress.

#### **2.2.2** Growth performance of Noiler chickens

The Noiler is an improved dual purpose chicken developed in Nigeria. In the African Chicken Genetic Gains (ACGG) project it was evaluated together with three other locally developed chickens (FUNAAB Alpha, Shika-Brown and Fulani) and two tropically adapted foreign breeds, Kuroiler from India and Sasso from France (Ajayi et al., 2020). Birds of this kind are intended to add genes for higher productivity to the hardiness of locally adapted chickens, in contrast to commercial broilers and layers (Bamidele et al., 2020).

In an on station evaluation, Noiler, Kuroiler and Sasso grew faster than FUNAAB Alpha and Shika-Brown, and at 42 days Noiler (744g) was about 3.7 times as heavy as Fulani (202g) (Bamidele et al., 2020). Noiler also had the highest hatchability of eggs set (84%) among the six breeds, and its hen-housed egg production (173 eggs) was well above the roughly 128 eggs reported for local Nigerian chickens. On this basis, Noiler and FUNAAB Alpha were identified as the most suitable dual purpose breeds for both egg and meat (Bamidele et al., 2020).

Under smallholder conditions, Noiler males outgrew the other five breeds between 6 and 14 weeks of age, with an unusually large gain between 10 and 14 weeks, although by 18 weeks their weight did not differ statistically from Kuroiler or Sasso. During the growing phase (6-18 weeks), this was accompanied by lower survivability than Fulani, FUNAAB Alpha and Shika-Brown (Ajayi et al., 2020). In a later semi-scavenging study, Noiler birds reached 1,927g at 21 weeks against 1,792g for FUNAAB Alpha, a difference that was not statistically significant, while FUNAAB Alpha survived better (Bamidele et al., 2022).

#### **2.2.4** Comparative growth performance of improved tropical and commercial chickens

Genetic improvement has contributed substantially to the growth performance of chickens adapted to tropical production systems. Comparative evaluations have shown that improved tropical chicken genotypes can achieve substantially greater body weight gains than unimproved local populations. Under on station conditions, improved genotypes such as FUNAAB Alpha and Noiler demonstrated markedly higher body weight gains than Fulani chickens by 42 days of age, with the relative advantage varying among genotypes (Bamidele et al., 2020). Similar differences have also been observed under smallholder production conditions, where improved chicken breeds exhibited superior growth and laying performance compared with local chickens (Ajayi et al., 2020). These findings indicate that genetic improvement can enhance productive performance under both controlled and farmer-managed environments, although the magnitude of the response may vary according to genotype and production conditions.

Table 1: Body weight gain of improved chickens over the Fulani at 42 days

Source: (Bamidele et al., 2020).

Growth performance and survivability do not necessarily increase simultaneously among improved chicken genotypes. Evidence from comparative evaluations indicates that some genotypes with superior growth may experience greater mortality, suggesting that productive performance can be influenced by the balance between genetic growth potential and adaptation to the prevailing production environment. In an on station evaluation, the exotic-sourced Kuroiler and Sasso recorded higher mortality than locally developed or indigenous genotypes, including Fulani, FUNAAB Alpha, Noiler and Shika Brown (Bamidele et al., 2020). Similarly, evaluations under smallholder conditions demonstrated that the relative performance of chicken genotypes for growth, egg production and survivability varied across breeds and agroecological zones, indicating that environmental conditions can modify the expression of genotype related advantages (Ajayi et al., 2020).

Differences have also been observed between locally developed genotypes, with Noiler showing a tendency toward greater body weight gain than FUNAAB Alpha, although the difference in body weight at 21 weeks was not significant, while FUNAAB Alpha recorded better survivability (Bamidele et al., 2022). Commercial broiler genotypes generally exhibit a different growth profile from improved tropical and indigenous chickens, having been intensively selected for rapid growth and feed efficiency. Comparative studies of commercial broilers have reported differences even among highly selected strains, with Cobb 500 showing higher weight gain and better feed conversion than Ross 308 over a 42-day production period (Petričević et al., 2024), while Arbor Acres has also been characterized by rapid growth and efficient feed utilization (Ji et al., 2020). In a comparison involving FUNAAB Alpha, its crossbreds and two exotic broilers, Arbor Acres recorded the highest body weight at ten weeks, illustrating the growth potential of commercial broiler genotypes (Ogunpaimo and Wheto, 2020).

Taken together, this literature demonstrates considerable variation in growth trajectories and survivability among chicken genotypes. Commercial broilers such as Cobb 500 and Arbor Acres generally exhibit high growth potential, whereas improved tropical genotypes such as FUNAAB Alpha and Noiler combine moderate growth performance with characteristics associated with adaptation to less intensive production systems. Indigenous chickens generally exhibit slower growth but may possess adaptive advantages under challenging environments. The performance differences observed across studies suggest that genotype evaluation should consider not only body weight gain but also survivability and the production environment in which the birds are reared. This is particularly important for tropical and smallholder systems, where adaptation, resilience and dual-purpose characteristics may be relevant alongside rapid growth (Ajayi et al., 2020; Bamidele et al., 2020).

### **2.3** Intensive management system of chicken

Chicken growth reflects how an animal’s genetic potential is expressed under the conditions in which it is raised. Modern broiler strains have been bred heavily for rapid growth: between 1957 and 2005, commercial broiler growth rate increased by more than 400% and feed conversion ratio fell by 50% when the strains were compared under the same modern feeding programme (Zuidhof et al., 2014). Genetic selection has been credited with 85-90% of such improvements, with the remainder attributed to environmental factors (Havenstein et al., 2003). Realising this potential therefore depends on the production system, which is the focus of this section. It reviews intensive management and the influence of nutrition, housing and health on growth, the genotype by environment (G×E) interaction, and the reasons for evaluating all genotypes within a single production system. The core elements of intensive broiler management are laid out in commercial guides such as the Ross Broiler Management Handbook (Aviagen, 2018).

Nutrition and feeding programmes;

Housing and environmental control (temperature, ventilation, air quality, lighting and litter);

Health and biosecurity;

Flock husbandry (brooding, water supply, stocking density and record keeping).

A fifth element is the bird’s genotype, because the management package has to suit the strain being reared (Aviagen, 2018). When these elements work together, birds can reach much of their genetic potential. If any one of them is weak, it limits growth (Aviagen, 2018).

#### **2.3.1** Meaning and components of intensive management

Poultry production systems differ in the degree of environmental control, resource input and exposure of birds to external conditions. Intensive production is characterized by confinement, relatively high stocking densities and greater control over feeding, housing, environmental conditions and health management. This system is widely used in commercial broiler production because it allows producers to maximize output within a limited production area and improve production efficiency (Averós and Estevez, 2018). In contrast, extensive and semi-intensive systems provide birds with varying degrees of outdoor access and generally involve lower levels of environmental control and resource input. As a result, birds kept under these systems may experience greater fluctuations in climatic conditions and increased exposure to predators, environmental and disease-related challenges (Singh and Cowieson, 2013).

The production system can therefore influence the expression of growth performance through its effects on nutrition, environmental conditions, stocking density, health and general management. However, these factors do not operate independently. Their combined effects can influence both productive performance and bird welfare, making the relationship between production system and poultry performance complex (Averós and Estevez, 2018). This interaction is particularly relevant when comparing chicken genotypes because the performance and survival of a genotype can differ with the environment and management in which it is kept (Ajayi et al., 2020; Bamidele et al., 2020, 2022). Consequently, assessment of growth performance should consider not only the genetic characteristics of the birds but also the production system.

#### **2.3.2** Management factors affecting chicken growth

Management practices play an important role in determining the extent to which the genetic growth potential of chickens is expressed. Among these factors, nutrition is particularly important because feed represents a major component of poultry production costs and provides the energy, amino acids, minerals and vitamins required for tissue development and maintenance. The nutritional requirements of birds vary with age and genetic growth potential, meaning that diets formulated for slower growing chickens may not adequately support the rapid growth of modern broiler genotypes. In addition to nutrient composition, feed intake, feed quality, physical form of the diet and access to clean water can influence growth performance (Aviagen, 2018).

The response of chickens to feeding programmes can also vary according to genotype and health status. For example, in layer type chickens between 2 and 12 weeks of age, the effect of red mite infestation on early growth differed among genotypes when birds were fed ad libitum, but not under feed restriction, indicating that nutritional management cannot always be considered independently of other production factors (Erdem and Savaş, 2021).

Environmental and housing conditions further influence how efficiently nutrients are converted into body tissue. Among these factors, ambient temperature is particularly important in tropical poultry production because exposure to high temperatures can depress growth performance and alter water consumption. Broilers exposed to high ambient temperatures have been shown to consume more water relative to feed and to grow less than birds kept under normal temperatures, and the reduction in growth varied among genetic backgrounds (Deeb and Cahaner, 2001, 2002). Other aspects of housing, including ventilation, air quality, lighting, litter condition and stocking density, can also affect feed consumption, health and welfare (Aviagen, 2018). These factors are particularly relevant in tropical production environments, where high temperatures can make suitable thermal conditions difficult to maintain, and broilers selected for rapid growth under optimal conditions may not achieve their genetic potential under high ambient temperature (Deeb and Cahaner, 2002).

Health status represents another important component of growth performance because disease and parasitic challenges can reduce feed intake, increase nutrient requirements for immune responses and tissue repair, and ultimately divert available nutrients away from growth. Effective biosecurity, vaccination and disease monitoring are therefore important components of poultry management (Aviagen, 2018). Importantly, health challenges may not always produce obvious clinical signs. Subclinical conditions, such as red mite infestation, can nevertheless alter growth performance and interact with feeding management (Erdem and Savaş, 2021).

Overall, the literature indicates that nutrition, housing and health should be viewed as interconnected components of poultry management rather than isolated factors. Adequate nutrition may not translate into maximum growth when birds are exposed to heat stress, poor ventilation, excessive stocking density or disease challenges. Similarly, favourable housing conditions and good health management can improve the efficiency with which dietary nutrients are utilized for growth. Thus, differences observed in the growth performance of chicken genotypes may reflect not only their genetic potential but also the interaction between genotype and the nutritional, environmental and health conditions under which they are reared.

#### **2.3.3** Genotype by environment (G×E) interaction

Phenotypic performance in chickens results from the combined effects of genetic constitution, environmental conditions and the interaction between them. A genotype × environment interaction (G×E) occurs when different genotypes respond differently to changes in environmental conditions, such that the magnitude of their performance differences changes or their relative ranking is altered across environments (Falconer and Mackay, 1996).

In quantitative genetic studies, G×E may be reflected through differences in genetic variance or heritability between environments and through genetic correlations below unity when the same trait is evaluated under different environmental conditions (Falconer and Mackay, 1996; Chu et al., 2019).

Evidence from poultry studies demonstrates that growth performance can change substantially across environmental conditions. Differences in genetic responses between temperate and hot conditions have been observed in broilers: the correlation between sire breeding values for weight gain across seasons was low (r = 0.26 from 0 to 4 weeks of age) and even negative for later growth, and genotypes that gained more weight in spring tended to gain less under summer heat (Settar et al., 1999). Similarly, broilers genetically selected for high body weight showed a greater advantage over unselected birds under normal temperatures, but this advantage was reduced under high-temperature conditions and reversed during later stages of growth (Deeb and Cahaner, 2002). The magnitude of growth reduction under heat stress has also been shown to vary with genetic background, being greatest in the progeny of a sire line bred for high growth rate and breast meat yield (Deeb and Cahaner, 2001). These findings collectively suggest that selection for rapid growth under favourable conditions does not necessarily result in the same growth advantage when birds are exposed to environmental stress.

G×E may also occur when the environment in which breeding stock are evaluated differs from the conditions under which their offspring are commercially produced. Genetic correlations of about 0.5 between body weight in biosecure breeding and commercial production environments indicate that the performance of selection candidates may not accurately predict their performance under commercial conditions (Chu et al., 2019). In addition, environmental factors such as feeding level and parasite infestation can act together, making it difficult to attribute differences in genotype performance to a single environmental factor (Erdem and Savaş, 2021). Therefore, the superiority of a particular chicken genotype should not be considered universally applicable across all production conditions. Instead, genotype performance should be evaluated in relation to the specific environmental and management conditions under which the birds are reared.

#### **2.3.4** Rational for evaluating all genotypes under onene system

When genotypes are compared, any difference in performance may come from genetic differences, environmental differences, or their interaction. If genotypes are raised in different houses, seasons or feeding programmes, genetic and environmental effects are confounded and the comparison is invalid. Rearing all genotypes under one system ensures that the environment is common to all birds. That system has the same feed, housing, lighting, stocking density, water supply and health programme. Observed differences in growth can then be attributed to genotype. This is the basis of a completely randomised design, in which genotypes are the treatments and the house conditions are held constant.

A common system also removes the influence of management skill and micro environment differences. It allows fair comparison of growth, feed intake and feed efficiency, and it permits valid estimation of genetic parameters such as heritability and breeding values. It also gives a standard reference condition against which the same genotypes can later be tested in other environments to detect G×E. Because G×E is well documented (Settar et al., 1999; Deeb and Cahaner, 2002; Chu et al., 2019), results from a single system must be interpreted with care. They describe the ranking of genotypes under that system and may not transfer to conditions with different temperature, nutrition or disease pressure. Evaluation under one intensive system is best seen as a controlled first step that gives an unbiased comparison. Where possible, it should be followed by testing across the environments in which the birds will eventually be produced.

### **2.4** Genotype, Sex and Genotype by sex effects

#### **2.4.1** Genotype effects on chicken growth curve

Chicken growth is commonly modelled with non-linear functions, and the Gompertz is one of the best-fitting options (Salvador et al., 2025). Such functions summarise how weight changes with age using a small set of parameters that have biological meaning (Salvador et al., 2025). The Laird form of the Gompertz function has been applied to the individual growth curves of 7,143 chickens, and line significantly affected every parameter (Mignon-Grasteau et al., 1999). The parameters were also moderately to highly heritable, with heritabilities from 0.31 to 0.54, estimated from a larger dataset of 38,474 animals (Mignon-Grasteau et al., 1999). Because the parameters differ among lines and are heritable, selection on them could modify the growth curve, including the difference between sexes in precocity and hence weight at a given age (Mignon-Grasteau et al., 1999). A later selection experiment supported this: selection for higher body weight at 8 weeks increased initial specific growth rate and maturation rate and decreased age at inflection (Mignon-Grasteau et al., 2001).

Later work reports similar differences among genotypes. Two slow-growing strains, Hubbard S757 and Hubbard Grey Barred JA, reared organically, were both described closely by the Gompertz and Logistic models (R² above 0.99), and each model detected a significant difference in instantaneous growth rate between the strains (Eleroğlu et al., 2014). In Nigeria, the Gompertz model was fitted to the weekly weights of 417 chickens of the Naked Neck, FUNAAB Alpha, and Giriraja genotypes to study seasonal variation in growth curve parameters of males and females, and the early wet season supported higher weight gain in all three genotypes (Sabe et al., 2017). Together, these results suggest that growth curve parameters differ among genotypes and vary with season, so a genotype’s growth curve is not fixed (Sabe et al., 2017).

#### **2.4.2** Sex effect on growth curve

Sex differences in body weight are well documented in chickens. When the Laird form of the Gompertz function was fitted to individual growth curves, sex significantly affected every parameter (Mignon-Grasteau et al., 1999). Compared with females, males had higher L (initial specific growth rate), BW0 (estimated hatching weight), and age and weight at inflection, together with a lower maturation rate K (Mignon-Grasteau et al., 1999). This pattern is consistent with males maturing later and reaching a larger mature size, whereas females mature sooner.

Other populations show comparable differences. In Castellana Negra chickens, a likelihood ratio test comparing Gompertz parameters between sexes indicated sexual dimorphism in adult weight, age at maximum growth rate, and relative growth rate (Salvador et al., 2025b). In both organically reared genotypes, estimated asymptotic weights were higher for males than for females under the Gompertz and Logistic models (Eleroğlu et al., 2014). Because the asymptote is a parameter of the fitted curve and was higher under the Gompertz than the Logistic model in the same data (Eleroğlu et al., 2014), such values should not be read as slaughter weights.

Because the sexes follow different growth curves, they reach a given weight at different ages, so feeding programmes, slaughter age, and flock uniformity may need to take sex into account (Salvador et al., 2025b).

#### **2.4.3** Genotype × sex interaction

Genotype by sex (G×S) interaction exists when the difference between sexes changes from one genotype to another. In a linear model this is the interaction term in

The sex by genotype interaction can take two forms. In a scale effect, the difference between the sexes is larger in one genotype than in another, but the genotypes keep the same rank. In re-ranking, the best genotype for one sex is not the best for the other.

The data from slow-growing chickens reared organically illustrate a scale effect. Under the Gompertz model, the estimated asymptotic weights were about 3,725 g for Grey Barred JA females and 6,110g for males, against about 4,876g for S757 females and 6,496 g for males (Eleroğlu et al., 2014). The male advantage was therefore much greater in Grey Barred JA about 2,384 g than in S757 about 1,620 g, while S757 stayed heavier in both sexes (Eleroğlu et al., 2014). These figures come from extrapolated curves, but they show that the size of the sex difference depends on genotype.

At the genetic level, the interaction is measured by the genetic correlation between the same trait in males and in females. A trait expressed in two environments can be treated as two correlated traits, and the same reasoning applies to the sexes (Falconer and Mackay, 1996). In an analysis of body weight, feed intake, and weight gain in 56,649 broilers, with each trait in males and females treated as a separate trait, heritabilities differed significantly between the sexes at the same age for every trait (Mebratie et al., 2019). The male to female genetic correlations at the same age were also significantly below one, which was interpreted as a sex by genotype interaction (Mebratie et al., 2019). Sex can therefore be seen as a kind of environment in which genes are expressed differently.

Where: (y) = observed response variable; () = overall mean; () = effect of the ith genotype; () = effect of the jth sex;  = interaction effect between the ith genotype and the jth sex; and  = random error associated with the kth observation within the ith genotype and jth sex.

#### **2.4.4** Implication for Modelling and Breeding

Modelling is important because sex changes growth curve parameters, the data for males and females should not be pooled before this has been tested. Curves should be fitted with sex as a factor, and equality of parameters between the sexes should be tested formally, for instance with a likelihood ratio test (Salvador et al., 2025b). Comparing parameter estimates alone does not test whether differences exceed chance variation, so formal tests of parameter equality are needed (Salvador et al., 2025b). Analyses of growth data should therefore include genotype, sex, and their interaction as fixed effects. When the interaction is significant, the effect of each factor is better described within each level of the other factor than as a single averaged main effect (MedCalc Software Ltd, n.d.). Where birds are measured at several ages, non-linear mixed models with random effects allow individual variation in curve parameters to be estimated, and adding random effects reduced residual variance by more than half in one study of naturalised chickens (Ibiapina Neto et al., 2020).

In poultry breeding, growth curve parameters are heritable and differ among lines, so selection can act on the shape of the curve as well as on body weight at a fixed age (Mignon Grasteau et al., 1999). The genetic correlations between the sexes differed significantly from one for every growth curve parameter in that study, so a sire’s breeding value estimated from one sex does not fully predict the performance of the other (Mignon Grasteau et al., 1999). Genetic evaluation of production traits should therefore take sex and age differences into account to improve the accuracy of selection and genetic gain (Mebratie et al., 2019). In practice, this means using sex specific records or multi trait models in which male and female performance are separate traits (Mebratie et al., 2019), and choosing candidates with attention to how their progeny perform in both sexes.

Furthermore, information obtained from growth models can assist ain developing appropriate feeding and management strategies. Male and female broilers differ in growth performance and nutrient requirements, with males needing more crude protein, which supports sex-specific feeding (England et al., 2023). The most profitable slaughter age also differs by sex. In one study of 2,550 broilers, profitability indices peaked at about day 40 in males, but kept rising up to day 42 in females (Samarakoon and Samarasinghe, 2012). Rearing the sexes separately may improve pen uniformity, although the evidence on whether it improves performance is not yet clear (England et al., 2023). For evaluation trials such as this one, the sex of every bird should be recorded and sexes balanced across genotypes, because sex differences add variation to nutrition trials and would otherwise be confounded with the genotype effect (England et al., 2023).

### **2.4** Nonlinear growth model in chickens

Body weight in chickens typically follows a sigmoid growth pattern, characterised by slow initial growth, an accelerating phase, a point of maximum growth rate, a decelerating phase, and an eventual approach to mature body weight (Sanusi and Oseni, 2019). Mathematical functions fitted to this pattern are referred to as growth models, which summarise longitudinal weight measurements into a few biologically interpretable parameters (Narinç et al., 2017). The Gompertz, logistic, Richards, and von Bertalanffy functions are among the most commonly used nonlinear models for describing poultry growth patterns (Narinç et al., 2017). These models are nonlinear, sigmoid-shaped, and semi-mechanistic, with applications in identifying the best-fitting growth function, comparing growth patterns among poultry species or experimental groups, and estimating genetic parameters for growth-curve characteristics (Narinç et al., 2017).

#### **2.4.1** Biological basis of nonlinear growth functions

Growth is the net result of cell replication, tissue differentiation, matrix formation, cell death and other interrelated processes (Fatai et al., 2023). Because tissue accretion is constrained by the genetic size potential of the bird and by the supply of nutrients and energy, the absolute growth rate cannot rise indefinitely. It reaches a maximum and then declines toward zero as the bird approaches mature size (Fitzhugh, 1976; Ricklefs, 1985). Different functions encode this constraint through different differential equations:

**Logistic (Verhulst, 1838):**

$$\frac{dW}{dt}=kW\left(1-\frac{W}{A}\right)$$

Relative growth rate falls linearly as $W$ approaches $A$.

**Gompertz (Gompertz, 1825):**

$$\frac{dW}{dt}=kW\ln\left(\frac{A}{W}\right)$$

Relative growth rate falls exponentially with age.

**von Bertalanffy (von Bertalanffy, 1957):**

$$\frac{dW}{dt}=\eta W^{2/3}-\kappa W$$

Synthesis is proportional to surface-like area ($W^{2/3}$) and degradation proportional to mass. Here $A=(\eta/\kappa)^3$ and $k=\kappa/3$.

**Brody (Brody, 1945):**

$$\frac{dW}{dt}=k(A-W)$$

Growth rate is proportional to the weight remaining to be gained, so there is no inflection.

**Richards (Richards, 1959):**

$$\frac{dW}{dt}=kmW\left(1-\frac{W}{A}\right)$$

A shape parameter generalises the other curves. (In the differential form shown here, $m$ controls the shape.)

Where:

W = body weight of the chicken at time t.

Wt = body weight at age t

t = age of the chicken, usually expressed in days or weeks

A = asymptotic or mature body weight.

B = integration constant related to the initial growth condition.

k = growth-rate or maturation-rate parameter.

n = parameter associated with the anabolic component of growth.

k = parameter associated with the catabolic component of growth.

m= shape parameter controlling the form and asymmetry of the Richards growth curve.

in = natural logarithm.

dW/dt = instantaneous rate of change in body weight with respect to age.

Gompertz is the limit of the Richards form as m → 0; the logistic is m = 1; von Bertalanffy is m = −1/3; and the Brody (monomolecular) curve is m = −1 (Tjørve, 2010, 2017). In practice the biological meaning is partly empirical. Growth functions are descriptive tools, and multiple parameterisations of the same curve exist, meaning that parameter estimates from different studies may not be directly comparable without appropriate standardisation . The Gompertz function has been applied to describe overall body growth, chemical growth, feather growth and breast muscle development in broiler chickens, with parameters such as mature weight, maturation rate and the age at maximum growth rate used to characterise growth patterns across genotypes (Gous et al., 1999). These findings highlight the importance of biologically interpretable parameters when modelling poultry growth, particularly when estimating mature weight from limited observation periods (Gous et al., 1999;  Tjørve, 2017).

#### **2.4.2** General interpretation of growth curve parameters

Two important considerations apply when interpreting growth-curve parameters. First, the parameter K represents the relative maturation rate and is often inversely associated with the asymptotic weight (A), such that larger-framed, later-maturing animals tend to exhibit lower maturation rates (Fitzhugh, 1976). Similarly, lower values of (k) have been associated with longer growth periods and higher mature body weights (Fatai et al., 2023). Second, parameter estimates are strongly dependent on the growth function selected. For male FUNAAB Alpha chickens measured up to 20 weeks of age, the estimated asymptotic weights were 3,056.3 g for the Gompertz model, 2,050.8g for the logistic model, and 3,716.6g for the von Bertalanffy model, with corresponding maturation-rate estimates of 0.0860, 0.2002, and 0.0463 per week, respectively (Bashiru et al., 2019b). These results illustrate the variation in estimated growth parameters across models fitted to the same dataset and show an inverse pattern between the estimated asymptotic weight and maturation rate in these particular results (Fitzhugh, 1976; Bashiru et al., 2019b).

Table 1.1 interpretation of the parameters in the forms most used in the Nigerian chicken literature.

Parameter definitions and model equations are as given in poultry growth-curve studies (Knížetová et al., 1995; Araújo et al., 2018).

#### **2.4.3** Logistic model

The logistic curve is symmetric about its inflection point, so the fastest growth necessarily occurs at exactly half of mature weight. This can be restrictive for chickens, in which peak growth often occurs at a smaller fraction of mature weight.

The logistic function has been used in poultry growth modelling both as a standard non-linear model and within non-linear mixed-effects frameworks to estimate individual growth parameters (Aggrey, 2002, 2009). In Italian local chickens, several non-linear models fitted very closely R² 0.992 to 0.999, although the logistic gave a higher root mean square error (RMSE) than the Gompertz and Richards models (Rizzi et al., 2013). In FUNAAB Alpha chickens, the logistic model gave the lowest asymptotic weight and the highest maturation rate (K) of the four models fitted, and it ranked last on the Akaike information criterion (AIC) and Bayesian information criterion BIC (Bashiru et al., 2019b). A comparatively low asymptotic weight was also reported for FUNAAB Alpha chickens under the logistic model (Fatai et al., 2023). In Noiler chickens, the logistic model fitted worse than the Gompertz (Adamu et al., 2021; Isa and Joel, 2026).

The logistic model is expressed as:

$$W(t)=\frac{A}{1+Be^{-kt}}$$

The inflection occurs at $t^*=\frac{\ln B}{k}$, where $W^*=\frac{A}{2}$, and the maximum absolute growth rate is $AGR_{max}=\frac{kA}{4}$.

#### **2.4.4** Gompertz model

The Gompertz function is consistently identified as one of the most suitable three parameter nonlinear models for describing poultry growth. Its predictive value has been demonstrated against machine learning alternatives, such as artificial neural networks, in broiler growth prediction (Roush et al., 2006). It has also shown a fitting advantage over other sigmoid models in commercial and non commercial lines. In Italian and Athens Canadian chickens, it outperformed the logistic and Richards functions (Teleken et al., 2017).

This pattern largely holds in Nigerian chicken populations, where the Gompertz model has been reported as the best fitting function in the Yoruba ecotype (Fatai et al., 2023), in male and female Noiler chickens (Adamu et al., 2021), and in Cobb 500, Marshall, and Noiler chickens reared in Sokoto (Isa and Joel, 2026). The evidence is not uniform, however. In FUNAAB Alpha chickens, the von Bertalanffy function achieved a better fit, leaving the Gompertz model in second place (Bashiru et al., 2019b; Fatai et al., 2023). This suggests that although the Gompertz model is a strong general candidate, the optimal growth function may depend on the genotype and population under study.

The Gompertz model is:

$$W(t)=Ae^{-Be^{-kt}}$$

Inflection age:

$$t^*=\frac{\ln B}{k}$$

Weight at inflection:

$$W^*=Ae^{-1}\approx0.368A$$

Maximum absolute growth rate:

$$AGR_{max}=\frac{kA}{e}\approx0.368kA$$

Where;

A= asymptotic body weight

B = integration constant

k = growth-rate parameter

The Gompertz function exhibits an asymmetric sigmoid growth pattern, with the point of maximum growth rate occurring at approximately 36.8% of the asymptotic weight, a characteristic that may make it more suitable than the logistic function for describing growth in certain poultry populations. Differences in parameterisation are important when comparing growth curve estimates across studies because parameter definitions and values may vary depending on the formulation adopted (Tjørve, 2017).

#### **2.4.5** Richard model

Richards (1959) proposed a flexible function with a free shape parameter. A common parameterisation is:

$$W(t)=A\left(1+Be^{-kt}\right)^{-1/m}$$

For this parameterisation, the inflection-point equations are:

Age at the inflection point:

$$t^*=\frac{\ln(Bm)}{k}$$

Body weight at the inflection point:

$$W^*=A\left(\frac{1}{1+m}\right)^{1/m}=A(1+m)^{-1/m}$$

These expressions assume that:

The Richards growth function can reduce to special cases by setting the shape parameter to corresponding values (as noted in the cited unified-Richards literature).

The additional parameter in the Richards function increases flexibility but may reduce parameter stability. The fourth parameter may lead to over-parameterisation of the growth model (Aggrey, 2002). Accurate estimation of the asymptotic weight using the Richards function may require body-weight records extending to approximately 90 days or later, whereas the Gompertz function requires one fewer parameter (Rizzi et al., 2013). In FUNAAB Alpha chickens, Richards model has been reported to perform poorly (Fatai et al., 2023), and model comparisons using Akaike’s Information Criterion (AIC) and the Bayesian Information Criterion (BIC) placed it behind both the von Bertalanffy and Gompertz functions (Bashiru et al., 2019b). By contrast, the Richards function is often favoured for describing growth in meat and egg-type chicken strains because its shape is flexible (Darmani Kuhi et al., 2003). Its many published parameterisations can be reduced to two general forms, and adopting a unified parameterisation may prevent the unrealistic parameter estimates that arise when a fixed-shape model is imposed (Tjørve, 2010). The convergence problems commonly reported for the Richards function are also in line with the strong parameter correlations that can occur in nonlinear models (Ratkowsky, 1983).

Where:

Wt= body weight at age t.

A = asymptotic body weight.

B = integration constant.

e = base of the natural exponential function.

k = growth-rate parameter

t = age of the chicken.

m = shape parameter controlling the curve's form.

#### **2.4.6** Brody model

It is a monomolecular (Mitscherlich-type) curve with no inflection: the growth rate is maximal at hatching. The absolute growth rate declines after its initial value. The hatch weight for the Brody form is $W_0=A(1-B)$. Brody type curves describe the decelerating, post-inflection phase of growth well but cannot represent the early accelerating phase of chicken growth. Consequently, they are best suited to datasets that begin after the inflection point or to species and genetic lines that attain maximum growth very early. Brody and Mitscherlich functions have been fitted to FUNAAB Alpha and Yoruba chickens (Fatai et al., 2023), while the Brody model has produced the lowest maturity rate estimate among the models evaluated in Cobb 500, Marshall and Noiler chickens (Isa and Joel, 2026).

The Brody growth function is:

$$W(t)=A\left(1-Be^{-kt}\right)$$

The von Bertalanffy function (von Bertalanffy, 1957) is a Brody-type curve raised to the third power:

$$W(t)=A\left(1-Be^{-kt}\right)^3$$

Age at the inflection point:

$$t^*=\frac{\ln(3B)}{k}$$

Body weight at the inflection point:

$$W^*=\frac{8A}{27}\approx0.296A$$

Maximum absolute growth rate:

$$AGR_{max}=\frac{4kA}{9}$$

(the inflection occurs at a positive age only when B > 1/3). It has been reported as the best fit for several indigenous chickens in Kenya, Ghana, Turkey and Nigeria (Bashiru et al., 2019b; Fatai et al., 2023), including FUNAAB Alpha.

### **2.5** Model selection and goodness of fit

#### **2.5.1** Coefficient of Determination (R2)

For observed body weights $W_i$ and fitted values $\hat W_i$, the sums of squares used in the model assessment are:

$$SSE=\sum_{i=1}^{n}(W_i-\hat W_i)^2$$

$$SST=\sum_{i=1}^{n}(W_i-\bar W)^2$$

$$R^2=1-\frac{SSE}{SST}$$

In linear models with an intercept, SST = SSR + SSE, so R² lies between 0 and 1 and is the proportion of variance explained. The decomposition of the total sum of squares does not generally hold in nonlinear regression, which can make the coefficient of determination R2 misleading (Kvålseth, 1985). Monte Carlo simulations have also demonstrated that R2 is an inadequate measure of goodness of fit for nonlinear models (Spiess and Neumeyer, 2010). This limitation is evident in poultry growth studies, where R2 values ranged from 0.987 to 0.999 across models fitted to Yoruba chickens (Fatai et al., 2023) and from 0.992 to 0.999 in Italian local chickens (Rizzi et al., 2013), providing little discrimination between models that were ranked differently by other selection criteria. Similarly, in male Noiler chickens, the R2 values for the Gompertz 0.8122 and logistic (0.8103) models differed by only 0.0019, whereas their corresponding Akaike Information Criterion (AIC) values 6927.5 and 6933.0, respectively differed by 5.5 units (Adamu et al., 2021). Therefore, R2 is best reported as a descriptive measure of model fit rather than used as the sole criterion for model selection.

where:

$$R^2=1-\frac{SSE}{SST}$$

The coefficient of determination is defined as above, and

 $R^2$ = coefficient of determination; $SSE$ = sum of squared errors; $SST$ = total sum of squares.

#### **2.5.2** Residual mean square and root mean square error (RMS/RMSE)

$$MSE=\frac{SSE}{n-p}$$

$$RMSE=\sqrt{\frac{SSE}{n}}$$

Some authors divide by $n$ rather than $(n-p)$; therefore, the definition used should be explicitly stated because the two differ when the number of parameters is large relative to the sample size.

#### **2.5.3** Akaike information criterion (AIC)

Models have been compared using R² together with the residual standard deviation (Aggrey, 2002), while a broader set of criteria, namely R², AIC, BIC, RMSE, and MSE, has been applied jointly in more recent work (Isa and Joel, 2026). Because RMSE is reported in the same units as the response variable, it is directly interpretable; an RMSE of 80 g, for instance, means that predictions deviate from observed values by about 80 g in root-mean-square terms. It is, however, dependent on the scale of the data. Unlike AIC and BIC, it does not explicitly penalise model complexity, except indirectly where the (n − p) divisor is used in its calculation.

A criterion based on expected information loss was introduced for model selection (Akaike, 1974). For least-squares fits with normally distributed, constant-variance errors, and after omitting terms common to all candidate models,

$$AIC=n\ln\left(\frac{SSE}{n}\right)+2p$$

(Burnham and Anderson, 2002)

When $n/p$ is small (below about 40), the corrected form is recommended (Hurvich and Tsai, 1989):

$$AIC_c=AIC+\frac{2p(p+1)}{n-p-1}$$

The model with the smallest value is preferred, and only differences matter:

Akaike weights:

$$\Delta_i=AIC_i-AIC_{min}$$

$$w_i=\frac{e^{-\Delta_i/2}}{\sum_{j=1}^{R}e^{-\Delta_j/2}}$$

The relative support for each model can be assessed using Akaike weights (Burnham and Anderson, 2002). As a worked example, the male Noiler AIC values reported by Adamu et al. (2021) can be used to illustrate the calculation.

For this example, the difference is $\Delta_{Logistic}=6933.0-6927.5=5.5$, so $e^{-5.5/2}=e^{-2.75}\approx0.064$. After normalising across the two models, the weights are 0.940 for Gompertz and 0.060 for Logistic. Both models have three parameters, so the comparison is not affected by differences in the penalty term.

Two practical considerations are important. First, absolute AIC values depend on the dataset and sample size, so comparisons should generally be restricted to models fitted to the same data. For example, AIC values were approximately 44 to 54 when mean weights at selected ages were modelled (Bashiru et al., 2019a, 2019b), compared with approximately 6,900 when individual weights were modelled (Adamu et al., 2021). Second, the mathematical expression must be specified correctly.

#### **2.5.4** Bayesian information criterion (BIC)

$$BIC=n\ln\left(\frac{SSE}{n}\right)+p\ln(n)$$

Because ln(n) exceeds 2 once n ≥ 8, BIC, which was derived by Schwarz (1978), penalises additional parameters more heavily than AIC and tends to favour simpler models. This is relevant when a four parameter Richards model competes with three parameter models: in the FUNAAB Alpha data, the Richards model’s extra parameter was penalised (Bashiru et al., 2019b). BIC differences of 2 to 6 are interpreted as positive evidence for the model with the lower BIC, 6-10 as strong evidence, and above 10 as very strong evidence (Kass and Raftery, 1995). Both criteria rely on likelihoods that assume independent errors, an assumption violated by repeated weight measurements on the same bird. Mixed effects formulations that add bird-level random parameters address this problem and substantially improved accuracy in mule ducks, reducing the residual standard deviation by about 55% (Aggrey, 2009; Vitezica et al., 2010; Galeano Vasco et al., 2014).

#### **2.5.5** Residual diagnostics and biological plausibility

Statistical criteria rank models but do not show whether the best model is adequate. Residuals should be plotted against age and fitted values to detect systematic lack of fit, increasing variance with body size (often handled by weighting or by a variance function), and serial correlation among successive weights from the same bird (Durbin and Watson, 1950). Parameter correlation and curvature should also be examined, since high intrinsic or parameter effects non linearity makes estimates and their standard errors unreliable (Ratkowsky, 1983; Bates and Watts, 1988). Convergence failure, as seen for the Richards function (Fatai et al., 2023), is itself diagnostic information.

Biological plausibility is a separate test. Useful checks are whether the predicted asymptote is consistent with observed mature weights, whether predicted hatch weight is close to observed day-old weight, whether the inflection age lies within the observed age range, and whether k > 0 and no predicted weights are negative. Several studies fail some of these checks even when R² is above 0.99. For example, all models overestimated the initial weight of FUNAAB Alpha chickens except the Brody (Fatai et al., 2023). Choosing a parameterisation that returns realistic values is therefore emphasised in the literature (Tjørve, 2017).

### **2.6** Biological and mathematical foundations of growth curves

The quantities of practical interest are derived from the fitted parameters. The model-derived quantities are summarised below.

| Growth model | Hatch weight ($W_0$) | Inflection age ($t^*$) | Inflection weight ($W^*$) | Maximum AGR |
|---|---|---|---|---|
| Logistic | $A/(1+B)$ | $\ln(B)/k$ | $A/2$ | $kA/4$ |
| Gompertz | $Ae^{-B}$ | $\ln(B)/k$ | $Ae^{-1}\approx0.368A$ | $kA/e$ |
| von Bertalanffy | $A(1-B)^3$ | $\ln(3B)/k$ | $8A/27\approx0.296A$ | $4kA/9$ |
| Brody | $A(1-B)$ | — | — | $kAB$ at $t=0$ |



Table 2.0 Summary of Growth Characteristics and Parameter Estimates of Four Nonlinear Growth Models

source: (Araújo et al., 2018)

Where: A = Asymptotic body weight; B = Integration constant; k = Growth rate parameter; W₀ = Body weight at hatch; W* = Body weight at the inflection point; t* = Age at the inflection point; AGR = Average Growth Rate; e = Euler’s number; and ln = Natural logarithm.

#### **2.6.1** Asymptotic Body weight

The asymptote A is the weight toward which the curve tends, interpreted as mature body weight. It is the parameter most sensitive to model choice and to the age range of the data. For male FUNAAB Alpha chickens weighed to 20 weeks, estimates ranged from 2050.8 to 3716.6 g, and for females from 1591.7 to 3330.6 g, depending on the function (Bashiru et al., 2019b). In the companion spline study with the same design (300 chicks, hatch to 20 weeks), the observed 20-week least-squares means were 1894.8 g for males and 1321.7 g for females (Bashiru et al., 2019a). If those are the same birds, the Gompertz asymptote is 1.61 times the observed male weight (3056.3/1894.8) and 1.91 times the observed female weight (2521.0/1321.7); the von Bertalanffy ratios are 1.96 and 2.52, and only the logistic is close (1.08 and 1.20). Mature weights of 1.6–2.1 kg at 20 weeks were the breeding target for the breed (Bashiru et al., 2019a). A similar conclusion was reached for chickens weighed to 8 weeks, with a recommendation to extend records to 12 weeks or longer to validate the asymptote (Isa and Joel, 2026). Asymptotic weight remains useful for comparing strains, for example the Marshall strain’s asymptote above 3000 g (Isa and Joel, 2026), provided the same function and age range are used for each strain.

#### **2.6.2** Maturation age

The rate constant k indicates how quickly the bird approaches A, and it is the basis for age at maturity. Because a function reaches A only asymptotically, maturity is operationally defined as the age at which a stated fraction, usually 95%, of A is attained. Applying this to the male FUNAAB Alpha estimates gives 28.4 weeks (logistic), 49.3 weeks (Gompertz) and 82.0 weeks (von Bertalanffy). These ages are far beyond the 20-week record, and the spread across models is nearly threefold, which shows that maturity age is poorly identified when data stop before the plateau. Maturity in this sense is body-size maturity; it is not sexual maturity, which depends on separate physiological and management factors. Lower k corresponds to a longer growth period and higher mature weight (Fatai et al., 2023; Fitzhugh, 1976).

#### **2.6.3** Age of inflection

The inflection marks the point of maximum absolute growth rate, after which gain per week falls. It is closer to the data than the asymptote and is therefore estimated more reliably. Reported values include 13.30–17.63 weeks (males) and 14.23–19.94 weeks (females) for FUNAAB Alpha chickens (Bashiru et al., 2019b), with the Richards function giving the earliest and the von Bertalanffy the latest age, and 5.5 weeks (Cobb 500, Gompertz) to 8 weeks (Marshall, Weibull) for broilers and Noiler chickens reared to 56 days (Isa and Joel, 2026). Males had higher weights at inflection and earlier inflection ages than females in all models (Bashiru et al., 2019b).

#### **2.6.4** Production significance of growth parameters

Growth parameters support several decisions. The age at inflection and the maximum growth rate identify when feed intake and nutrient density should peak and when diets can be changed, and strain-specific critical growth ages have been proposed as a guide to feeding strategies for Cobb 500, Marshall and Noiler birds (Isa and Joel, 2026). Fitted curves also predict weight at any age, which supports market weight planning and the matching of slaughter age to target weight; this is especially relevant to a dual-purpose bird that must serve as both a meat and an egg type. In addition, curve parameters feed into factorial nutrient requirement models, where the potential growth and body composition of a genotype are described by Gompertz parameters (Gous et al., 1999, 2024; Vargas et al., 2020), and they are used to compare genotypes and sexes and as selection criteria (Fitzhugh, 1976; Lopez et al., 2000; Narinç et al., 2017). Because selection has changed the shape of the curve over time, as shown by the large differences in growth, efficiency and yield among broiler lines representing 1957, 1978 and 2005 (Zuidhof et al., 2014), the growth curve of each genotype should be measured separately rather than borrowing parameters from another.

#### **2.6.5** Relationship between chronological age and body weight.

Body weight is a non-linear, monotonic increasing function of age. The absolute growth rate (AGR) rises to a maximum at the inflection point and falls thereafter, whereas the relative growth rate (RGR) declines throughout.

$$AGR(t)=\frac{dW(t)}{dt}$$

$$RGR(t)=\frac{1}{W(t)}\frac{dW(t)}{dt}$$

For the Gompertz model, $RGR(t)=k\ln(A/W)$; for the logistic model, $RGR(t)=k(1-W/A)$. The age-weight relationship also differs by sex. Male FUNAAB Alpha chickens were similar to females at hatch (P > 0.05) but heavier at every later age (P < 0.05), and the gap widened up to 20 weeks (Bashiru et al., 2019a). Chronological age is an imperfect proxy for physiological development, because feeding, climate and disease alter the weight reached at a given age, and differences among reports have been attributed to genotype, population structure, feeding and environment (Sanusi and Oseni, 2019; Fatai et al., 2023). Weight variance also increases with age, which violates the constant-variance assumption of ordinary least squares and motivates weighted fits or mixed models (Aggrey, 2009; Vitezica et al., 2010). Finally, the distinction between average and individual body weights matters, because curves fitted to flock means hide between-bird variation (Atil et al., 2007).

Where:

RGR = Relative Growth Rate

AGR = Absolute Growth Rate

W = body weight at time t

= the instantaneous growth rate (change in body weight per unit time)

=  adjustment for the current body weight.

### **2.7** Regression models for describing chicken growth

Regression models that are linear in their parameters (linear, polynomial and spline) are the principal alternatives to non-linear functions. They can be fitted by ordinary least squares without iteration or starting values and cannot fail to converge, but their parameters usually lack direct biological meaning.

#### **2.7.1** Linear regression

A linear model cannot adequately describe an entire sigmoid growth curve, as it is only suitable for approximating short sections where growth is relatively linear. This limitation is evident in the least-squares means for male FUNAAB Alpha chickens presented in Table 2.1 (Bashiru et al., 2019a). Applying a single slope across the entire growth period would fail to account for the distinct phases of growth. Consequently, linear models have primarily served as reference models for evaluating the performance of non-linear functions, as demonstrated in studies on Italian local chickens (Rizzi et al., 2013) and comparisons of linear and non-linear models for body protein growth.

and  (Draper and Smith, 1998).

Table 2.1. Average weekly gain of FUNAAB-Alpha chickens, calculated from least-squares mean body weights

source: (Rizzi et al., 2013)

#### **2.7.2** Polynomial regression

A polynomial of degree q is  The degree is chosen by sequential F-tests, adjusted R² or AIC/BIC. Raw powers of t are highly collinear; orthogonal polynomials remove this problem without changing the fitted curve (Draper and Smith, 1998). Polynomials follow the interior of a curve well, but they have no asymptote and diverge outside the data, so they cannot supply a mature weight or a maturity age. They also tend to oscillate near the ends as the degree rises and may predict implausible hatch weights. Some studies compare growth curves by pairing polynomial or spline functions with the usual sigmoid models (Aggrey, 2002; Şengül et al., 2024). For example, one study fitted five non-linear models and the spline-based MARS algorithm to broiler data (Şengül et al., 2024). Among the studies I reviewed, though, splines were reported for chickens more often than polynomial models.

Where;

Wi = observed body weight of the chicken at the i-th time point.

β0 = intercept, representing the predicted body weight when ti=0.

β1, β2,... βq = regression coefficients associated with the linear, quadratic, and higher-order time terms.

t1 = age of the chicken at the i-th measurement, usually expressed in days or weeks.

q = degree (order) of the polynomial regression model.

e1 = random error term for the i-th observation.

i = index identifying each observation.

#### **2.7.3** Segmented or spline regression

The curve is continuous at each knot. The slope in the first segment is $\beta_1$, and the slope after the $j$-th knot is $\beta_1+\beta_2+\cdots+\beta_{1+j}$, so every coefficient is interpretable as a change in growth rate. A knot is a point at which the growth rate changes. Knots can be fixed from the data plot (Aggrey, 2002; Bashiru et al., 2019a) or estimated as breakpoints in segmented regression. Penalised B-splines are a smoother alternative that controls flexibility by penalty and not by knot number, and B-spline random regressions have been used to model growth in cattle.

In a random-bred population raised to 170 days, three nonlinear models fitted better than a spline with fixed knots at 6, 18 and 113 days (four segments), judging by R² and residual standard deviation (Aggrey, 2002). In mule ducks, a mixed-effects Weibull model fitted best and a mixed-effects spline came second, with the spline able to represent the piecewise nature of growth even when records extend beyond the asymptote (Vitezica et al., 2010). For FUNAAB Alpha chickens, splines with 3, 4, 5 and 6 knots were compared, for example SP3 with knots at weeks 4, 10 and 16 (Bashiru et al., 2019a). The three knot model suited males best (AIC = 46.735, BIC = 55.221) and the four knot model suited females best (AIC = 43.867, BIC = 54.201). The better fit with fewer knots agrees with guidance to keep knots few unless the sample is large (Bashiru et al., 2019a). The male SP3 estimate of hatch weight (74.71 g) was far above the observed day-old mean (33.40 g), which shows that a model with the best AIC can still extrapolate poorly back to the origin (Bashiru et al., 2019a). Regression coefficients were largest between 3 and 10 weeks, which suggests that early growth rate may indicate later performance (Bashiru et al., 2019a).

Where:

β1, β2,... βq = regression coefficients representing the baseline slope and subsequent changes in slope across the different growth segments.

j = index identifying the segment or change point in the piecewise regression model.

---

# Chapter Three

### **3.0** MATERIALS AND METHODS

### **3.1** Ethical consideration

All experimental procedures will be conducted in accordance with institutional guidelines for the care and use of animals in research. Ethical approval for this study will be obtained from the Institutional Animal Care and Use Committee (IACUC) of the Federal University of Agriculture, Abeokuta.

### **3.2** Experimental site

This study will be conducted at the Poultry Breeding Unit of the Directorate of University Farms (DUFARMS), Federal University of Agriculture, Abeokuta (FUNAAB), Ogun State, Nigeria. FUNAAB is located at latitude 7°13'N and longitude 3°26'E at an altitude of approximately 76m above sea level within the rainforest agro-ecological zone of SouthWest Nigeria, characterised by a bimodal rainfall pattern, high humidity, and ambient temperatures ranging from 22°C to 34°C. The breeding unit maintains a closed nucleus flock with structured mating and full pedigree recording.

### **3.3** Experimental birds

The study will follow a completely randomised design with a 2 × 2 factorial arrangement of genotype (FUNAAB Alpha, Noiler) and sex (male, female). A total of  two hundred (200) unsexed, day-old chicks, comprising hundred (100) birds each of two chicken genotypes FUNAAB Alpha and Noiler will be procured from two reputable hatcheries located in Abeokuta (Ogun State) and Ibadan (Oyo State), respectively. Each genotype will be housed in a separate deep litter pen from day-old and wing-tagged for identification, with distinct colour tags assigned to each genotype.

Sex determination will be carried out at four (4) weeks of age using the Visual sex identification based on secondary sexual characteristics (comb and wattle development which relies on differences in comb and wattle growth rate and pattern between male and female birds. Following sexing, birds within each genotype will be regrouped and reared separately by sex to allow for evaluation of genotype and sex effects, as well as their interaction, on the growth.

### **3.4** Management of the birds

Prior to the arrival of the chicks, the pen will be thoroughly cleaned, disinfected, and fumigated in accordance with standard biosecurity protocols. The birds will be housed in a well-ventilated, conventional deep litter poultry pen equipped with standard feeder and drinker space allocations in line with recommended stocking density guidelines. Fresh wood shavings will be used as litter material throughout the experimental period.

Brooding will be conducted for two weeks using charcoal pots and electric bulbs to maintain an initial temperature of 35°C during the first week, subsequently reduced by 3°C per week until ambient temperature is attained at approximately four weeks of age. Lighting will be provided for 23 hours per day during the brooding phase and reduced to a natural photoperiod thereafter.

The birds will thereafter be reared for a total period of ten (10) weeks under uniform management conditions. All birds within each genotype and sex group will be subjected to identical feeding, watering, and health management routine throughout the experimental period, in accordance with standard practices recommended by the Food and Agriculture Organization (FAO). Uniform management conditions will be maintained throughout to ensure that observed differences between genotype and sex groups are attributable solely to genetic and sex-related variation rather than environmental factors.

### **3.4** Biosecurity measures

Strict biosecurity measures will be implemented throughout the study period. Dedicated rubber footwear will be placed at the entrance of the poultry house to minimize the introduction of pathogenic organisms. Visitor access to the poultry unit will be restricted to prevent disease transmission.

Litter materials will be replaced as necessary to maintain dryness and prevent microbial proliferation. Routine sanitation practices will be strictly observed to ensure proper hygiene and minimize offensive odors within the pen.

### **3.5** Experimental diet

The birds will be fed commercially prepared New Hope poultry feeds throughout the experimental period. Three feed types will be used acccording to the birds growth stages: New Hope 510 (Starter), 511 (Grower) and 512 (Finisher). The starter diet (510) will be provided from week 1-4, followed by the grower diet (511) and subsequently the finisher diet (512) as the birds advance in age. Feed and drinking water will be provided ad libitum throughout the experimental period.

### **3.6** Vaccination and medication

The birds will be subjected to a vaccination and medication programme throughout the experimental period to protect them against common poultry diseases and maintain good health. Vaccines, antibiotics, multivitamins and other treatments will be administered according to the farm health management schedule, as presented in Table 3

Table 3: Vaccination and medication programme for the experimental birds

### **3.7** Data Collection

Individual live body weight (g) will be recorded for every bird at hatch (day-old) and then weekly until 10 weeks of age. Weighing will be done in the morning before feeding, using a digital scale with [0.1 g/1 g] precision, and the same weighing procedure will be used for all birds.

#### **3.7.1** Statistical Analysis

#### **3.7.2** Fitting the growth models

Body weight ($W$) will be modelled as a function of age ($t$) using the following nonlinear growth functions and regression models. Equations are shown below in a readable display format:

**Candidate model equations**

| Model | Equation |
|---|---|
| Gompertz | $W(t)=Ae^{-Be^{-kt}}$ |
| Logistic | $W(t)=\dfrac{A}{1+Be^{-kt}}$ |
| von Bertalanffy | $W(t)=A(1-Be^{-kt})^3$ |
| Richards | $W(t)=A(1+Be^{-kt})^{-1/m}$ |
| Brody | $W(t)=A(1-Be^{-kt})$ |
| Linear regression | $W_i=\beta_0+\beta_1t_i+\varepsilon_i$ |
| Quadratic regression | $W_i=\beta_0+\beta_1t_i+\beta_2t_i^2+\varepsilon_i$ |
| Cubic regression | $W_i=\beta_0+\beta_1t_i+\beta_2t_i^2+\beta_3t_i^3+\varepsilon_i$ |

For the segmented regression formulation, the continuous piecewise model is:

$$W(t)=\beta_0+\beta_1t+\sum_{j=1}^{q}\beta_{1+j}(t-\tau_j)_+$$

where $(t-\tau_j)_+=\max(0,t-\tau_j)$ and $\tau_j$ is the $j$th knot/breakpoint.

Table 3.1: Nonlinear, Linear, and Polynomial Regression Models for Chicken Growth Curve Analysis.

Source: ( Richards, 1959; Knížetová et al., 1995; Rawlings et al., 1998; Araújo et al., 2018; )

Models will initially be fitted separately for each genotype and then examined by genotype and sex. Nonlinear models will be fitted using nonlinear least squares with reasonable starting values and parameter constraints. Repeated measurements from the same bird will be accounted for in inferential analyses.

#### **3.7.3** Goodness-of-fit assessment

The model statistics will be calculated as follows (using $n$ observations and $p$ fitted parameters):

$$SSE=\sum_{i=1}^{n}(W_i-\hat W_i)^2$$

$$R^2=1-\frac{SSE}{SST},\qquad RMSE=\sqrt{\frac{SSE}{n}}$$

$$AIC=n\ln\left(\frac{SSE}{n}\right)+2p$$

$$BIC=n\ln\left(\frac{SSE}{n}\right)+p\ln(n)$$

Residuals will be inspected graphically against age and fitted values.


Model performance will be compared using the coefficient of determination, root mean square error, Akaike information criterion, Bayesian information criterion, and residual diagnostics:

Coefficient of Determination

Akaike Information Criterion (AIC)

Root Mean square error

Bayesian Information Criterion

Residual diagnostics

FUNAAB Alpha and Noiler will be compared using estimated growth parameters, predicted body weights at common ages within the observed period, and absolute and relative growth rates. Comparisons will consider sex-specific trajectories and uncertainty in estimates.

Where:

W(t) = Body weight at age t

t = age of the chicken (weeks)

AGR(t) = Absolute growth rate at age t

RGR (t) = Relative growth rate at age t

= Rate of change in body weight with age

### **3.6** Statistical Analysis

The data obtained on each of the parameters will be analyzed using Statistical Analysis System (SAS Institute Inc., 2018). Prior to analysis, the data will be screened for missing values, outliers, and normality. Descriptive statistics will be computed for all measured variables to summarize the distribution of body weight and linear body measurements in each genotype. Statistical significance will be declared at P < 0.05.

\

---

# References

Adamu, J., Shuaibu, A. Y., and Raji, A. O. 2021. Growth characteristics of Noiler chickens as determined by nonlinear algorithms. Nigerian Journal of Animal Production, 48(5), 12–19. https://doi.org/10.51791/njap.vi.4140

Adeyonu, A. G., and Odozi, J. C. 2022. What are the drivers of profitability of broiler farms in the North-central and South-west geo-political zones of Nigeria? SAGE Open, 12(1), 1-13. https://doi.org/10.1177/21582440211071076

Aggrey, S. E. 2002. Comparison of three nonlinear and spline regression models for describing chicken growth curves. Poultry Science, 81(12), 1782–1788. https://doi.org/10.1093/ps/81.12.1782

Aggrey, S. E. 2009. Logistic nonlinear mixed effects model for estimating growth parameters. Poultry Science, 88(2), 276–280.

Ajayi, F.O., Bamidele, O., Hassan, W.A., Ogundu, U., Yakubu, A., Alabi, O.O., Akinsola, O.M., Sonaiya, E.B. and Adebambo, O.A. 2020. Production performance and survivability of six dual-purpose breeds of chicken under smallholder farmers' management practices in Nigeria. Archives Animal Breeding, 63(2), 387–408. https://doi.org/10.5194/aab-63-387-2020

Akaike, H. 1974. A new look at the statistical model identification. IEEE Transactions on Automatic Control, 19(6), 716–723. http://dx.doi.org/10.1109/TAC.1974.1100705

Atil, H., Grossman, M., and Takma, C. 2007. Comparison of growth curve models on average and individual body weights in chickens. European Poultry Science, 71(1), 1–5. https://www.jstage.jst.go.jp/article/jpsa/52/4/52_0150048/_article

Araújo, C. C., Rodrigues, K. F., Vaz, R. G. M. V., Conti, A. C. M., Amorim, A. F., and Campos, C. F. A. 2018. Analysis of growth curves in different lineages of Caipira broiler type. Acta Scientiarum. Animal Sciences, 40(1), e38806.

Averós, X., and Estevez, I. 2018. Meta-analysis of the effects of intensive rearing environments on the performance and welfare of broiler chickens. Poultry Science, 97(11), 3767-3785. https://doi.org/10.3382/ps/pey243

Aviagen. 2018. Ross broiler: Management handbook. Aviagen.

Bamidele, O., Sonaiya, E. B., Adebambo, O. A., and Dessie, T. 2020. On-station performance evaluation of improved tropically adapted chicken breeds for smallholder poultry production systems in Nigeria. Tropical Animal Health and Production, 52(4), 1541-1548. https://doi.org/10.1007/s11250-019-02158-9

Bamidele, O., Akinsola, O. M., Yakubu, A., Hassan, W. A., Ogundu, U. E., and Amole, T. A. 2022. Growth performance, survivability and profitability of improved smallholder chicken genetics in Nigeria: A COVID-19 intervention study. Frontiers in Genetics, 13, Article 1033654. https://pmc.ncbi.nlm.nih.gov/articles/PMC9846064/

Bashiru, H. A., Oseni, S. O., and Omadime, L. A. 2019a. Assessment of spline functions for estimating growth curve parameters of FUNAAB-Alpha chickens. Nigerian Journal of Animal Production. https://njap.org.ng/index.php/njap/en/article/view/6546

Bashiru, H. A., Oseni, S. O., and Omadime, L. A. 2019b. Evaluation of four classical non-linear models to describe the growth curve of FUNAAB-Alpha chickens. In Book of Proceedings, 44th Annual Conference of the Nigerian Society for Animal Production  Abuja, Nigeria. https://njap.org.ng/index.php/njap/en/article/view/6546

Bates, D. M., and Watts, D. G. 1988. Nonlinear regression analysis and its applications. Wiley.https://www.researchgate.net/publication/265638446_Nonlinear_Regression_Analysis

Bennett, C. E., Thomas, R., Williams, M., Zalasiewicz, J., Edgeworth, M., Miller, H., Coles, B., Foster, A., Burton, E. J., and Marume, U. 2018. The broiler chicken as a signal of a human reconfigured biosphere. Royal Society Open Science, 5(12), 180325. https://doi.org/10.1098/rsos.180325

Chu, T. T., Bastiaansen, J. W. M., Berg, P., Romé, H., Marois, D., Henshall, J., and Jensen, J. 2019. Use of genomic information to exploit genotype-by-environment interactions for body weight of broiler chicken in bio-secure and production environments. Genetics Selection Evolution, 51, Article 50. https://doi.org/10.1186/s12711-019-0493-3

Darmani Kuhi, H., Kebreab, E., Lopez, S., and France, J. 2003. An evaluation of different growth functions for describing the profile of live weight with time (age) in meat and egg strains of chicken. Poultry Science, 82(10), 1536–1543. https://www.sciencedirect.com/science/article/pii/S003257911943931X?via%3Dihub

Deeb, N., Cahaner, A. 2001. Genotype-by-environment interaction with broiler genotypes differing in growth rate. 1. The effects of high ambient temperature and naked-neck genotype on lines differing in genetic background. Poultry Science, 80(6), 695-702. https://doi.org/10.1093/ps/80.6.695

Deeb, N., Cahaner, A. 2002. Genotype-by-environment interaction with broiler genotypes differing in growth rate. 3. Growth rate and water consumption of broiler progeny from weight-selected versus nonselected parents under normal and high ambient temperatures. Poultry Science, 81(3), 293-301. https://doi.org/10.1093/ps/81.3.293

Draper, N. R., and Smith, H. 1998. Applied regression analysis (3rd ed.). Wiley. 10.1002/9781118625590.ch15

Durosaro, S. O., Jeje, O. S., Ilori, B. M., Iyasere, O. S. and Ozoje, M. O. 2021. Application of non-linear models in description of growth of dual purpose FUNAAB Alpha chickens. Journal of Agriculture and Rural Development in the Tropics and Subtropics.

Eleroğlu, H., Yıldırım, A., Şekeroğlu, A., Çoksöyler, F. N., and Duman, M. 2014. Comparison of growth curves by growth models in slow-growing chicken genotypes raised the organic system. International Journal of Agriculture and Biology, 16(3), 529–535. https://www.cabidigitallibrary.org/doi/pdf/10.5555/20143189958

England, A., Gharib-Naseri, K., Kheravii, S. K., and Wu, S.-B. 2023. Influence of sex and rearing method on performance and flock uniformity in broilers: Implications for research settings. Animal Nutrition, 12, 276–283.

Erdem, H., and Savaş, T. 2021. Genotype-environment interaction in layer chickens in the growing stage: Comparison of three genotypes at two different feeding levels with or without red mite (Dermanyssus gallinae) infestation. Archives Animal Breeding, 64(2), 447-455. https://doi.org/10.5194/aab-64-447-2021

Fadare, A. O., Idowu, O. E., and Maroof Q.A. 2020. Evaluation of growth traits in three strains of broiler chicken. Nigerian Journal of Animal Production, 47(4), 7–14. https://njap.org.ng/index.php/njap/en/article/view/81

Falconer, D. S., and Mackay, T. F. C. 1996. Introduction to quantitative genetics (4th ed.). Longman.

FAO 2025. FAOSTAT: Crops and livestock products. Food and Agriculture Organization of the United Nations, Rome. https://www.fao.org/faostat (accessed 5 November 2026).

Fatai, R. B., Akinyemi, M. O., Osaiyuwu, O. H., Ewuola, K. M., Bello, S. F., and Salako, A. E. 2023. Weight-age relationship in Yoruba and FUNAAB-Alpha chickens using non-linear regression models. Nigerian Journal of Animal Production, 50(5), 88–95. https://njap.org.ng/index.php/njap/en/article/view/8034

Fitzhugh, H. A., Jr. 1976. Analysis of growth curves and strategies for altering their shape. Journal of Animal Science, 42, 1036–1051.

Galeano-Vasco, L. F., Cerón-Muñoz, M. F., and Narváez-Solarte, W. 2014. Ability of nonlinear mixed models to predict growth in laying hens. Revista Brasileira de Zootecnia, 43(11), 573–578.

Ghaderi-Zefrehei, M., Rafeie, F., Zakizadeh, S., Elahi Torshizi, M., Peters, S. O., and Smith, J. 2024. Genetic variance components of the growth curve for Isfahan indigenous chicken. Veterinary Medicine and Science, 10(2): e1388.

Gous, R. M., Moran, E. T., Stilborn, H. R., Bradford, G. D., and Emmans, G. C. 1999. Evaluation of the parameters needed to describe the overall growth, the chemical growth, and the growth of feathers and breast muscles of broilers. Poultry Science, 78(6), 812–821.

Havenstein, G. B., Ferket, P. R., and Qureshi, M. A. 2003. Growth, livability, and feed conversion of 1957 versus 2001 broilers when fed representative 1957 and 2001 broiler diets. Poultry Science, 82(10), 1500-1508.

Hoffmann, I. 2005. Research and investment in poultry genetic resources  challenges and options for sustainable use. World's Poultry Science Journal, 61, 57–69.

Hruby, M., Hamre, M. L., and Coon, C. N. 1996. Non-linear and linear functions in body protein growth. Journal of Applied Poultry Research, 5(2), 109-115.

Hurvich, C. M., and Tsai, C.L. 1989. Regression and time series model selection in small samples. Biometrika, 76(2), 297–307.

Ibiapina Neto, V., Barbosa, F. J. V., Campelo, J. E. G., and Sarmento, J. L. R. 2020. Non-linear mixed models in the study of growth of naturalized chickens. Revista Brasileira de Zootecnia.  https://www.scielo.br/j/rbz/a/5zxZ3HLwSzjVgbznwdv6ZyH/?lang=en

Iraqi, M. M., Hanafi, M. S., Khalil, M. H., El-Labban, A. F. M., and El-Sisy, M. 2002. Genetic evaluation of growth traits in a crossbreeding experiment involving two local strains of chickens using multi-trait animal model. Livestock Research for Rural Development, 14(5). https://lrrd.org/lrrd14/5/iraq145tmp.htm

Isa, A. M., and  Joel, G. A. 2026. Comparative application of nonlinear models to describe the growth of broilers and Noiler chicken strains. UMYU Scientifica.

Ji, J., Tao, Y., Zhang, X., Pan, J., Zhu, X., Wang, H., Du, P., Zhu, Y., Huang, Y., and Chen, W. 2020. Dynamic changes of blood glucose, serum biochemical parameters and gene expression in response to exogenous insulin in Arbor Acres broilers and Silky fowls. Scientific Reports, 10. https://doi.org/10.1038/s41598-020-63549-9

Kass, R. E., and Raftery, A. E. 1995. Bayes factors. Journal of the American Statistical Association, 90(430), 773–795.

Kaya Başar, E., and Narinç, D. 2023. Genetic parameter estimates of growth curve and feed efficiency traits in Japanese quail. Animals, 13(11): 1765.

Kemp, C., and Kenny, M. 2003. Feeding the modern broiler for more meat. International Hatchery Practice, 17, 11–13.

Kvålseth, T. O. 1985. Cautionary note about R². The American Statistician, 39(4), 279–285.

Knížetová, H., Hyánek, J., Hyánková, L., and Bříček, P. 1995. Comparative study of growth curves in poultry. Genetics Selection Evolution, 27(4), 365

Lawler, A. 2014. Why did the chicken cross the world? The epic saga of the bird that powers civilization. Atria Books.

Lopez, S., France, J., Gerrits, W. J., Dhanoa, M. S., Humphries, D. J., and Dijkstra, J. 2000. A generalized Michaelis-Menten equation for the analysis of growth. Journal of Animal Science, 78(7), 1816–1828.

Mebratie, W., Madsen, P., Hawken, R., Romé, H., Marois, D., Henshall, J., Bovenhuis, H. and Jensen, J. 2019. Genetic parameters for body weight and different definitions of residual feed intake in broiler chickens. Genetics Selection Evolution, 51. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6757393/

MedCalc Software Ltd. (n.d.). Two-way analysis of variance.

Mignon-Grasteau, S., Beaumont, C., and Ricard, F. H. 2001. Genetic analysis of a selection experiment on the growth curve of chickens. Poultry Science, 80(7), 849–854.

Mignon-Grasteau, S., Beaumont, C., Le Bihan-Duval, E., Poivey, J. P., de Rochambeau, H., and Ricard, F. H. 1999. Genetic parameters of growth curve parameters in male and female chickens. British Poultry Science, 40(1), 44–51.

Muggeo, V. M. R. 2003. Estimating regression models with unknown break-points. Statistics in Medicine, 22(19), 3055–3071.

Narinç, D., Karaman, E., Firat, M. Z., and Aksoy, T. 2017. Comparison of non-linear growth models to describe the growth in Japanese quail. Journal of Animal and Veterinary Advances, 9, 1961–1966.

Narushin, V. G., and Takma, C. 2003. Sigmoid model for the evaluation of growth and production curves in laying hens. Biosystems Engineering, 84(3), 343–348.

Ogunpaimo, O., Wheto, M., Ojoawo, H., Adebambo, A., Adebambo, O., and Durosaro, S. 2020. Use of growth models to predict the body weight of FUNAAB Alpha broiler, its crossbreds, and two other exotic broiler chickens at early stage of growth. FUDMA Journal of Sciences, 4(1), 686–694.

Ojoawo, H. T., Wheto, M., Ogunpaimo, O. J., Odah, E. O., Ladejobi, A. K., and Oluyide, T. I. 2024. Growth performance and feed utilization potential of FUNAAB broiler Alpha chicken in comparison with two exotic broiler breeds. Nigerian Journal of Animal Production, 102–106.

Osaiyuwu, O. H., Oyebanjo, M. O., Coker, O. M., and Akinyemi, M. O. 2024. Comparison of mathematical models describing the growth of tropically adapted Ross 308 commercial broiler chickens. Animal Research International, 21(2): 5403–5414.

Permin, A., and Pedersen, G. 2000. Problems related to poultry production at village level. In G. Pedersen, A. Permin, and U. M. Minga (Eds.), Possibilities for smallholder poultry projects in Eastern and Southern Africa: Proceedings of a workshop, Morogoro, Tanzania.

Petričević, V., Lukić, M., Škrbić, Z., Dosković, V., Rakonjac, S., Petričević, M., and Milenković, D. 2024. Comparative analysis of production and slaughter parameters of fast-growing broiler hybrids. In Proceedings of the 2nd International Symposium on Biotechnology (pp. 183-192). Čačak, Serbia.

Raji, A. O., Okoro, V. M. O., and Aliyu, J. 2013. Determination of the best non-linear growth model for indigenous sheep in Nigeria. Advances in Agriculture, Science and Engineering Research, 3(9), 1131–1136.

Rawlings, J. O., Pantula, S. G., and Dickey, D. A. 1998. Applied regression analysis: A research tool (2nd ed.). Springer.

Richards, F. J. 1959. A flexible growth function for empirical use. Journal of Experimental Botany, 10, 290–300.

Rizzi, C., Contiero, B., and Cassandro, M. 2013. Growth patterns of Italian local chicken populations. Poultry Science, 92(9), 2226–2235. https://doi.org/10.3382/ps.2012-02825

Roush, W. B., Dozier, W. A., and Branton, S. L. 2006. Comparison of Gompertz and neural network models of broiler growth. Poultry Science, 85(4), 794–797.

SAS Institute Inc. 2018. SAS/STAT 15.1 User's Guide. Cary, NC: SAS Institute Inc.

Sabe, O., Ilori, B. M., Peters, S. O., and Daniel, I. O. 2017. Effect of seasonal changes on the growth curve parameters of male and female chickens. Nigerian Journal of Animal Production, 644–647. https://doi.org/10.51791/njap.vi.7881

Salako, A. E. 2014. Asymptotic nonlinear regression models for the growth of White Fulani and N’dama cattle in Nigeria. Livestock Research for Rural Development, 26.

Salvador, R. de C., Pereira, A. A., and Fernandes, T. J. 2025a. Bayesian inference in nonlinear growth models and hypothesis testing of sexual dimorphism in Black Utrerana chickens. Poultry Science. https://doi.org/10.1016/j.psj.2025.105947

Salvador, R. de C., Gonzaga, N. A., Azarias, E. C. P., Pereira, A. A., and Fernandes, T. J. 2025b. Test of equality of parameters in growth curves of black Castellana chickens. Semina: Ciências Exatas e Tecnológicas, 46, e51832. https://doi.org/10.5433/1679-0375.2025.v46.51832

Samarakoon, S. M. R., and Samarasinghe, K. 2012. Strategies to improve the cost effectiveness of broiler production. Tropical Agricultural Research, 23(4), 338–346. https://doi.org/10.4038/tar.v23i4.4869

Sanda, A. J., Bemji, M. N., Wheto, M., Oso, A. O., Sanda, M. O., and Olowofeso, O. 2022. Heritability and repeatability estimates of growth traits in FUNAAB Alpha and Noiler chicken genotypes. Nigerian Journal of Animal Science.

Sanusi, A. R., and Oseni, S. O. 2019. Nigerian Fulani ecotype chickens: Estimation of growth curve. Genetics and Biodiversity Journal, 4(1), 1–13.

Settar, P., Yalçin, S., Türkmut, L., Özkan, S., and Cahaner, A. 1999. Season by genotype interaction related to broiler growth rate and heat tolerance. Poultry Science, 78(10), 1353-1358. https://doi.org/10.1093/ps/78.10.1353

Singh, M., and Cowieson, A. J. 2013. Range use and pasture consumption in free-range poultry production. Animal Production Science. https://doi.org/10.1071/AN13199

Son, J., Kim, H.J., Hong, E.C., and Kang, H.K. 2022. Effects of stocking density on growth performance, antioxidant status, and meat quality of finisher broiler chickens under high temperature. Antioxidants, 11(5), 871. https://doi.org/10.3390/antiox11050871.

Teleken, J. T., Galvão, A. C., and Robazza, W. S. 2017. Comparing non-linear mathematical models to describe growth of different animals. Acta Scientiarum. Animal Sciences, 39(1), 73–81.

Tjørve, E., and Tjørve, K. M. C. 2010. A unified approach to the Richards-model family for use in growth analyses: Why we need only two model forms. Journal of Theoretical Biology, 267(3), 417–425.

Tjørve, K. M. C., and Tjørve, E. 2017. The use of Gompertz models in growth analyses, and new Gompertz-model approach: An addition to the Unified-Richards family. PLoS ONE, 12(6), e0178691. https://doi.org/10.1371/journal.pone.0178691

Toms, J. D., and Lesperance, M. L. 2003. Piecewise regression: A tool for identifying ecological thresholds. Ecology, 84(8), 2034–2041.

Topal, M., and Bölükbaşı, Ş. C. 2008. Comparison of nonlinear growth curve models in broiler chickens. Journal of Applied Animal Research, 34(2), 149–152. https://doi.org/10.1080/09712119.2008.9706960

Ugwuja, F. C., Halilu, A., and Henry, A. J. 2025. Phenotypic and growth evaluation of Ross 308, Arbor Acre and Cobb 500 strains of broiler chicken. Nigerian Journal of Animal Production.

Vargas, L., Sakomura, N. K., Leme, B. B., Antayhua, F., Reis, M., Gous, R., and Fisher, C. 2020. A description of the potential growth and body composition of two commercial broiler strains. British Poultry Science, 61(3), 266–273.

Vitezica, Z. G., Marie-Etancelin, C., Bernadet, M. D., Fernandez, X., and Robert-Granié, C. 2010. Comparison of nonlinear and spline regression models for describing mule duck growth curves. Poultry Science, 89(8), 1778–1784.

von Bertalanffy, L. 1957. Quantitative laws in metabolism and growth. The Quarterly Review of Biology, 32(3), 217–231.

Vázquez, J. A., Lorenzo, J. M., Fuciños, P., and Franco, D. 2012. Evaluation of nonlinear equations to model different animal growths with mono and bisigmoid profiles. Journal of Theoretical Biology, 314, 95–105.

Yakupoğlu, Ç., and Atil, H. 2001. Comparison of growth curve models on broilers I: Parameters estimations. Journal of Biological Sciences, 1(7), 682–684. https://doi.org/10.3923/jbs.2001.682.684

Zuidhof, M. J., Schneider, B. L., Carney, V. L., Korver, D. R., and Robinson, F. E. 2014. Growth, efficiency, and yield of commercial broilers from 1957, 1978, and 2005. Poultry Science, 93(12), 2970–2982. https://doi.org/10.3382/ps.2014-04291

Şengül, T., Çelik, Ş., Şengül, A. Y., İnci, H., and Şengül, Ö. 2024. Investigation of growth curves with different nonlinear models and MARS algorithm in broiler chickens. PLOS ONE, 19(11), 1-15. https://doi.org/10.1371/journal.pone.0307037

### Table 1

| Genotype | Origin | Weight gain over Fulani at 42 days (%) |

| Noiler | Nigeria | 368 |

| Kuroiler | India | 296 |

| Sasso | France | 245 |

| FUNAAB Alpha | Nigeria | 187 |

### Table 2

| Parameter | Interpretation | Practical mode |

| A | Asymptotic (mature) body weight, g | Extrapolated beyond the data if birds are not weighed to maturity |

| B | Integration constant | Fixes the starting weight; hatch weight =  /  (logistic),   (Gompertz) ,  (Brody),  /  (von Bertalanffy) |

| K | Maturing rate  / (maturity index),per week | Rate of approach to A relative to size, not a weight gain in grams |

| m (or d) | Shape parameters / (Richards only) | Determines the position of the inflection relative to A |

### Table 3

| Quantity | Logistic | Gompertz | von Bertalanffy | Brody |

| Hatch-weigh, W₀ |  |  |  |  |

| Inflection age, t* |  |  |  | none |

| Weight at inflection, W* |  |  |  | none |

| Maximum AGR |  |  |  |  |

| Age at 95% of A |  |  |  |  |

### Table 4

| Sex | Period (weeks) | Start weight (g) | End weight (g) | Calculation | Gain (g/week) |

| Male | 4 to 10 | 296.65 | 805.29 | (805.29 − 296.65)/6 | 84.8 |

| Male | 10 to 20 | 805.29 | 1894.80 | (1894.80 − 805.29)/10 | 109.0 |

| Female | 4 to 10 | 254.27 | 568.23 | (568.23 − 254.27)/6 | 52.3 |

| Female | 10 to 20 | 568.23 | 1321.71 | (1321.71 − 568.23)/10 | 75.3 |

### Table 5

| Day | Drug/Treatment | Purpose |

| Day 1-6 | Viral clear , Antibiotics , aminovitalyte (multivitamins), Diclamax (calcium) | General health management, infection control and nutritional support |

| Day 7 | Newcastle disease vaccine | Prevention of Newcastle disease |

| Day 8-10 | Embazin forte | Treatment of susceptible parasitic infections |

| Day 11 | Gumboro vaccine | Prevention of infectious bursal disease (IBD) |

| Day 12-13 | Clean water | Post vaccination management |

| Day 14 | Newcastle disease vaccine | Prevention of Newcastle disease |

| Day 15-17 | Zed multivitamin + Diclamax | Vitamin and calcium supplementation |

| Day 18 | Gumboro vaccine | Prevention of infectious bursal disease (IBD) |

| Day 19 | Clean water | Post vaccination management |

| Day 20-22 | Anticocci(center dicox), Enrofloxacin, Zed multivitamins | Coccidiosis control,bacterial infection treatment and Nutritional support |

| Day  28 | Second admininstration of Enrofloxacin | Antibacterial treatment |

### Table 6

| Model | Equation |

| Gompertz |  |

| Logistic |  |

| Von Bertalanffy |  |

| Richards |  |

| Brody |  |

| Linear regression |  |

| Quadratic regression |  |

| Cubic regression |  |
