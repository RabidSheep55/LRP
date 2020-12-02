# Detailed Report Structure
## Abstract
Complete once the whole report is complete

## Project Objectives
Very simple, can copy and paste the objectives decided in the first meeting (in teams)

## Introduction
Definition of a thin film: Liquid between two gases, or a gas between two liquids (antibubbles), or liquid between a gas and a solid. Limit study to 3 fluids problem (gas-liquid-gas and liquid-gas-liquid)

Define what makes a soap bubble: presence of surfactant (brief explanation of amphiphilic properties). This is opposed to "bare" bubbles, which will be used in this paper when studying transient effects.

Explain geometries explored? curved or planar film, and multiple bubbles (foams and porous liquids)?
Going to look at both surface bubbles and "free?" bubbles. Surface bubbles can be just considered as a curved film (the bubble) cap, connected to its bulk liquid via a meniscus (the bubble periphery, known as a Plateau border)

*What make bubble unique, what makes relevant, guide the reader to relevance, set the scene*
*Reference a lot of papers in the introductions*

Outline areas that will be explored - we won't be looking at the creation of the bubble, as that doesn't really affect its lifetime as said in Lhuissier.


## Stable curved films
*This section seems kind of weak and disjointed compared to the bubble death one. Might need to find a better structure*

### Role of surfactant
Detailed explanation of underlying physics behind the surface tension reducing capabilities of surfactants. Outline the different types of surfactants and how surfactant concentration affects bubble stability.

Organisation into two surfactant monolayers which stabilise the film.

Concept of surface or film pressure

Two types of surfactant - soluble and insoluble, how that leads to different effects?? -> "Mobile" and "Static" monolayers

(Manev E, Scheludko A, Exerowa D 1974)
(Sane A, Mandre S, Kim I. 2018)
(Modini RL et al 2013)
(ChampougnyNotBare2016)
(Bhamla MS et al 2017): stability ++ with surfactant

#### "Rigid" and "Mobile" film surfaces
Based on surfactant solubility and viscosity (Bruinsma1995)
Drainage mechansisms are studied in detail (Bhamla2017)
Mysels classified in 3 categories (Langevin1994):
    - Rigid films: monolayers are extremely compact and rigid
    - Simple mobile films: Rapid turbulent motion observed (driven by marangoni effect, and said to be triggered by marginial regeneration flows Lhuissier2011), and "thickness of the center is uniform" eg for low conc soluble surfactants.
    - Irregular mobile films: High conc surfactant, larger thickness surfactants observed, "Stratification"


### The Marangoni Effect
Very prevalent effect, which is the driving mechanism behind the transient structures observed on bubble surface (different thicknesses lead to different light interference resulting in colours).

Is what gives a certain elasticity to the film. Marangoni effect will carry surfactnat molecules from zones of high concentration to low concentration. So like if we stretch the film, surfactant concentration decreases in certain areas, increasing surface tension, and driving more low-surface tension zones towards it.

Mention that this mechanism also plays a role in film thinning and drainage.

(Bhamla MS et al 2017)

### Bubble Coalescence
The effects behind the merging of bubbles

### Behaviour in Electromagnetic fields
NEED TO GATHER SOURCES FOR THIS PART
(look into the levitation of bubbles using this effect)

*Moses Effect*: Deformation of a surface due by a magnetic field

When created, a bubble often has a charge, and that can mess with experiments. Emphasise importance of mitigating or keeping that in consideration. (some experiments do it well, others don't)

### (Possible other sections)
- Bubble size and shape, the *Young-Laplace Equation*, and link with contained volume pressure. (Lhuissier2011 has a pretty good description)

### Applications
Applications of these stable films:

- 2D flow approximation (Kellay H. 2017)
- Study vortices
- Test models for friction (with the flowing 2D film case)
- (thin film interference, not really an application though...)

### Discussion
What the EffectsWe ahve seeen so far that when a curved is stable, there are several physicl phenoment at play
Elaboration *CRITICAL VIEW*
2 Paragraphs even

Talk about the thickness models -> Lhuissier2011's one was backed up by Modini2013.

- Surfactant concentration and surface tension
- Surfactant type? Soluble and insoluble... see in film drainage mechanisms tho

## Bubble Death (Interactions with the environment)
### Film thinning mechanisms and rupture initialisation
Film undergo thinning mechanisms which reduce its thickness either down to the thinnest possible value (black films), or directly to rupture. Location point of rupture is different between a bubble sitting on bulk liquid, or held at a small point.

*Maybe talk about how Lhuissier has an amazing paper that goes through every step that leads to rupture...*

#### Gravity and capillary drainage
Effects which occur when the film is young (still relatively thick), and occur regardless of the presence of surfactants.

What is gravity driven draining?
What is capillary draiange?

As pointed out by Lhuissier2011, depends on bubble size. (smaller bubbles will be more spherical and under the surface, while bigger are less, and more above.) Notes that for bubbles R<5a, the capillary pressure is dominant or matches the hydrostatic pressure (due to gravity), and intuitively that makes sense.

For bubbles with R<5a (Lhuissier2011), main effect is capillary pressure:  Same mechanism occurs in foams, where liquid drains into the Plateau borders instead of a bulk liquid (Breward2002). Plateau borders are ???.

Regardless of whether hydrostatic or capillary are the driving mechanisms, flow is really easy to compute, as they are simple pressure driven flows. A pressure gradient will drive liquid out of the cap, through the meniscus and into the bulk liquid (or directly into a Plateau border in the case of foams). Hagen-Poiseuille or very simple plug flow equations are used to determine the flowrate out of the cap. (Nierstrasz1999 and Bruinsma1995 calls it Poiseuille flow when monolayers are static/rigid), (Debregeas1998, Lhuissier2011, Breward2002 call it plug flow, when there are no surfactants involved).

(short bit on what is Plug flow, and maybe the different equations that Lhuissier2011, Debregeas1998 and Breward2002 used) -> ChampougnyNotBare2016 "the flow profile is increasingly plug-like as the
surfactant concentration is decreased from several times the critical micellar concentration (cmc) to just
below the cmc".

Leads to extremely rapid drainage for water, when no surfactants are present (Breward2002, Debregeas1998, Lhuissier2011). Lhuissier2011 points out that the only effect that could slow down the drainage would be viscous stretching (viscous forces would oppose the stretching), but that has a characteristic time of 10e-4 s. Repeat the role of surfactant mentionned in section XXX, and how it makes sense now.

Since viscosity is a factor in eqs, studied very viscous, to increase lifetime:
Is the sole drainage mechanism in bare bubbles - Plug Flow (Debregeas1998) Experiments show a simple exponential thinning of the film, proportional to cap radius. Explain by getting the plug flow velocity field, and doing conservation equation. In their case, gravity was the driving force.

Show the Lhuissier Figure 8, where drainage occurs more rapidly than the expected Poiseuille flow. (Lhuissier2011). Why? MARGINAL REGENERATION

#### Marginal Regeneration
Use the Lhuissier Image.

Very interesting film thinning effect caused by the presence of free moving surface particles (like surfactants!). When a bubble is sitting on a bulk liquid, this film draining mechanism is orders of magnitude more significant than the usual pressure-driven Poiseuille draining.

*Easier to observe on flat films due to light, but also seen in bubbles*

*Although they are more easily studied in flat films due to the need for light to pass through, This great picture by Lhuissier and Villermaux clearly shows the convective structures at the base of the bubble, indicative of marginal regeneration.*

(Bhamla2017)
(Mysels, Karol Joseph (1959). Soap films : studies of their thinning. Pergamon Press, London) <- FIRST PAPER
(Lhuissier2011)

Physical explanations from different papers, compare:
 - Nierstrasz1999 -> localized zones of high surface tension
 - Bhamla2017 -> Details into the plumes dynamics (great data about soluble/insoluble surfactants)
 - Lhuissier2011 -> It is the destabilisation of the pinching region which leads to marginal regeneration. Destabilisation of type Benard-Marangoni, driven by the surface tension difference across the region.
 - ChampougnyEvap2018 -> "Patches" formed near the meniscus
 - Bruinsma1995 ->

**MAKE A TABLE WITH DRAINAGE MECHANISMS FOR SOLUBLE AND INSOLUBLE SURFACTANTS AT BELOW AND ABOVE CMC**

#### Common and Newton Black films
The thinnest possible stable bubble thickness; where it is now stable because the two boundaries are so close, the surfactant molecules can interact directly.

Exist two possible types - Common and Newton black films.

Evaporation is apparently significant at this thickness (ChampougnyEvap2018)
Old paper talks the stabilisation to a black film (looking at corrugations) (Vrij1968)
Model for bubble thinning, and patterns exhibited by those spots (Shen2020)
Notice for detergent type surfactants at a threshold concentration will allow formation (Manev1974)
For solutions above CMC, observe formation before rupture (Bhamla2017)
Intermolecular interactions balance out capillary suction (Breward2002)

#### Rupture initialisation
##### Why?
What causes the bubble to become unstable and rupture?
- (VrijDiscussion1966) Main working theory at the time is thermal fluctuations cause surface "corrugations", which grow over time, and when a critical wavelength is reached, cause spontaneous rupture. Proposes model for this wavelength, dependant on surface tension and the "Free energy of interaction" (essentially the intermolecular forces acting in the surfactant bilayer).
    - (Langevin1994) criticised this: apparently critical thickness isn't dependant on bubble radius or surface tension?.
- (Vrij1968) Very early paper in 1968 talks about 'corrugations' on the surface, which cause spontaneous thinning at a critical wavelength due to an imbalance in surface Gibbs energy (surface tension) and van de Walls forces.

- Lhuissier2011 gives an energy of activation
- (ChampougnyEvap2018) mentions the introduction of instability due to ambient evaporation (when films are at critical thicknesses)
- (Debregeas1998) High viscosity "bare" bubbles, said to burst when (at h ~ 70nm) "long-range Van der Waals interactions enhance film thinning"
- (Manev1974) Also talk about a critical thickness

In some cases, it might be useful to trigger a bubble rupture event manually, look at how different experiments did it:
-

Discuss the different methods used to purposefully rupture a bubble, (spark, needle, EM field, ultrasound ...)

##### Where?
When the main drainage mechanism is not Marginal regeneration (either capillary or hydrostatic), there is radial symmetry, and hole nucleates at top of bubble (Debregeas1998, ChampougnyNotBare2016).

And how the position of the hole depends on surfactant concentration (ChampougnyNotBare2016).

Nucleation seems to occur around a convection cell (rising plume mentionned in Marginal regeneration) (Lhuissier2011) -> kinda contradicts what ChampougnyNotBare2016 found?


### Hole Development
Maybe talk about how its not really directly relevant to stability, as the bubble has already burst, but very interesting and has significant impact. One of the biggest use cases for bubbles is aerosol production, in sea water bla bla (Lhuissier2011). Undestanding the dynamics of rupture also give insight into some of the characterisitcs that make it stable, and can be used to find the critical film thickness (Lhuissier2011).

#### Rim Velocity
Velocity of the initially circular opening hole. Primitively modelled by the Taylor-Culick velocity (Culick1960), but widely accepted to be an overestimation. Go over different propositions for this deviation:

- Some papers point to the small fluid particles that are ejected from the rim (Muller2009)
- Some mention a build-up of surfactant particles on the travelling edge, causing it to take an elongated shape, and develop a surface tension gradient (Bico2015)
- A lot point to the formation of an 'aureole', where away from the opening rim, folds and 'cracks' are observed (which is where some of the energy could be going).

"Opening and retraction of particulate soap films" <- Read to find if there's anything useful

Rayleigh does simple energy conservation
Culick adds viscous effects and liquid buildup along the rim
New effects observed try to explain the lower observed values


#### Appearance of instabilities
The bubble's hole doesn't stay circular the whole time, instabilities arrise which cause certain structures to be observed:

- Formation of ligaments
- Folds or cracks ahead of the rim

Briefly introduce the Rayleigh-Taylor and Kelvin-Helmholtz instabilities


### The aftermath
After the bubble has burst, it will either disintegrate into a very thin aerosol mist, or form greater-sized droplets. This has significant impacts, especially in the analysis of this effect in sea water.


### Applications
Mention the significant role bursting (unstable) bubbles have in:

- Aerosol production
- Liquid atomization
- Drug delivery

### Discussion
Discuss the unstable effects - personal opinion, what people did well etc

Surfactants are vital or else drains mega fast - Viscosity for no surfactants
Need further info about influence of evaporation at rupture
Although marginal regeneration was specifically observed in surface bubbles and foams, and we couldn't find a paper which studied its effect in "free", spherical bubbles. We could expect it to occur around the build-up of fluid at the base of concave bubbles (Shen2020)

Drainage mechanisms and rupture are a priori linked, as thinner films are more likely to rupture. But this onset of bursting, although quantitatively descried is not yet fully understood.

Overall, many effects still not fully understood, especially those pertaining to the drainage dynamics and hole nucleation.

## Improving stability
Looking back at all the effects described above, recap about how we could improve the stability of a bubble:

- Bubble make up
    - Surfactant type:
        - Concentration: prefer higher concentration, to stiffen the surface, reduce effect of marginal regeneration
        - Solubility: prefer insoluble surfactants to soluble
    - Viscosity (more viscous live longer it seems, but don't form bubbles) (Debregeas1998)
    - Larger bubbles drain slower (Debregeas1998), but become more sensitive to external fluctuations.
- Environment (low-high humidity, velocities, EM field)

Develop a few statements over 2-3 important points for each section

## Conclusions
Not sure we need this part (the "Improving stability" section is already kind of a summary)
Extract key points from above
Dry statement - recap
In this LRP we have been addressing thin films - bubbles or curved films
several stable effects and then Bursting, we touched on.... Saw to control stability its important to do.......
Gaps in the literature? rich in where?

## References
(probably use BibTex to do this)
