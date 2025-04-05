I'll create a comprehensive Mermaid diagram mapping Western philosophy's key figures and schools, including memorable signature phrases for each.

```mermaid
graph TB
    classDef ancient fill:#d4f1f9,stroke:#333
    classDef medieval fill:#ffe6cc,stroke:#333
    classDef renaissance fill:#d5e8d4,stroke:#333
    classDef enlightenment fill:#fff2cc,stroke:#333
    classDef modern fill:#e1d5e7,stroke:#333
    classDef contemporary fill:#f8cecc,stroke:#333

    %% Main philosophical periods
    ANC[Ancient Philosophy\n600 BCE - 500 CE]
    MED[Medieval Philosophy\n500 - 1500 CE]
    REN[Renaissance Philosophy\n1400 - 1600 CE]
    ENL[Enlightenment\n1600 - 1800 CE]
    MOD[Modern Philosophy\n1800 - 1950 CE]
    CON[Contemporary Philosophy\n1950 - Present]

    %% Ancient Philosophy
    ANC --> PRESOC[Pre-Socratics]
    PRESOC --> HERA[Heraclitus\n"You cannot step into the same river twice.\nAll is flux, nothing stays still."]
    PRESOC --> PARM[Parmenides\n"What is, is. What is not, cannot be.\nChange is merely an illusion of the senses."]
    PRESOC --> DEMO[Democritus\n"Everything is atoms and void.\nNothing happens by chance, but everything from reason and necessity."]
    
    ANC --> CLASSIC[Classical Greek]
    CLASSIC --> SOC[Socrates\n"The unexamined life is not worth living.\nI know that I know nothing."]
    CLASSIC --> PLATO[Plato\n"We are merely shadows dancing on the cave wall.\nReality exists in the eternal Forms beyond perception."]
    CLASSIC --> ARIS[Aristotle\n"We are what we repeatedly do. Excellence is not an act but a habit.\nHappiness is the meaning and purpose of life."]
    
    ANC --> HELLEN[Hellenistic Schools]
    HELLEN --> EPIC[Epicurus\n"Death is nothing to us.\nPleasure, properly understood as tranquility, is the highest good."]
    HELLEN --> STOIC[Stoicism\n"We suffer not from events, but from our judgments about them.\nVirtue alone is sufficient for happiness."]
    HELLEN --> SCEP[Skepticism\n"For every argument, there is an equal argument opposed.\nSuspending judgment leads to tranquility."]
    HELLEN --> NEO[Neoplatonism\n"The One overflows into being through emanation.\nThe soul must ascend beyond reason to mystical union."]
    
    %% Medieval Philosophy
    MED --> EARLY[Early Medieval]
    EARLY --> AUG[Augustine\n"Love God and do as you please.\nEvil is not a substance but a privation of good."]
    EARLY --> BOECON[Boethius\n"Fortune's wheel turns ceaselessly.\nTrue happiness lies in contemplation of the eternal."]
    
    MED --> SCHOL[Scholasticism]
    SCHOL --> ANSELM[Anselm\n"That than which nothing greater can be conceived.\nFaith seeking understanding."]
    SCHOL --> AQUINAS[Thomas Aquinas\n"Grace does not destroy nature but perfects it.\nBeing is what has actuality."]
    SCHOL --> OCKHAM[William of Ockham\n"Entities should not be multiplied beyond necessity.\nUniversals exist only as concepts in the mind."]
    
    MED --> MYST[Medieval Mysticism]
    MYST --> ECKHART[Meister Eckhart\n"The eye with which I see God is the same eye with which God sees me.\nTo be full of things is to be empty of God."]
    MYST --> HILD[Hildegard of Bingen\n"All of creation is a symphony of joy and jubilation.\nViriditas—the greening power—is God's living breath."]
    
    %% Renaissance Philosophy
    REN --> HUMAN[Humanism]
    HUMAN --> PICO[Pico della Mirandola\n"Man is the maker and molder of himself.\nThe dignity of man lies in his capacity for self-transformation."]
    HUMAN --> ERASMUS[Erasmus\n"In the land of the blind, the one-eyed man is king.\nWhen I have a little money, I buy books."]
    
    REN --> POLPHIL[Political Philosophy]
    POLPHIL --> MACHIA[Machiavelli\n"It is better to be feared than loved, if you cannot be both.\nMen must either be caressed or annihilated."]
    POLPHIL --> MORE[Thomas More\n"Utopia is nowhere, yet could be anywhere.\nPrivate property creates inequality and social discord."]
    
    %% Enlightenment
    ENL --> RATIO[Rationalism]
    RATIO --> DESC[Descartes\n"I think, therefore I am.\nClear and distinct ideas are the foundation of certain knowledge."]
    RATIO --> SPINOZA[Spinoza\n"God is not separate from Nature but identical with it.\nFreedom is understanding the necessity that governs all things."]
    RATIO --> LEIB[Leibniz\n"We live in the best of all possible worlds.\nEvery monad reflects the entire universe from its perspective."]
    
    ENL --> EMP[Empiricism]
    EMP --> LOCKE[John Locke\n"The mind begins as a blank slate.\nNatural rights to life, liberty, and property are inalienable."]
    EMP --> BERK[Berkeley\n"To be is to be perceived.\nMaterial substance is an unnecessary hypothesis."]
    EMP --> HUME[David Hume\n"Custom is the great guide of human life.\nReason is the slave of the passions."]
    
    ENL --> KANT[Kant\n"Sapere aude! Dare to know!\nAct only according to that maxim whereby you can will that it should become a universal law."]
    
    %% Modern Philosophy
    MOD --> IDEAL[German Idealism]
    IDEAL --> FICHTE[Fichte\n"The I posits itself absolutely.\nFreedom is the foundation of all theoretical philosophy."]
    IDEAL --> SCHEL[Schelling\n"Nature is visible Spirit; Spirit is invisible Nature.\nArt is the highest form of human activity."]
    IDEAL --> HEGEL[Hegel\n"The Owl of Minerva spreads its wings only with the falling of dusk.\nThe rational alone is real; what is real is rational."]
    
    MOD --> EXIS[Existentialism]
    EXIS --> KIERK[Kierkegaard\n"Anxiety is the dizziness of freedom.\nTruth is subjectivity."]
    EXIS --> NIETZ[Nietzsche\n"God is dead, and we have killed him.\nBecome who you are."]
    EXIS --> SARTRE[Sartre\n"Existence precedes essence.\nMan is condemned to be free."]
    EXIS --> CAMUS[Camus\n"One must imagine Sisyphus happy.\nThe only serious philosophical question is suicide."]
    
    MOD --> PRAGMA[Pragmatism]
    PRAGMA --> PEIRCE[C.S. Peirce\n"The meaning of a concept is the sum of its practical consequences.\nTruth is what inquirers would agree on in the ideal limit."]
    PRAGMA --> JAMES[William James\n"Truth happens to an idea.\nBelief creates the actual fact."]
    PRAGMA --> DEWEY[John Dewey\n"Education is not preparation for life; education is life itself.\nDemocracy is more than a form of government; it is a mode of associated living."]
    
    MOD --> PHENOMEN[Phenomenology]
    PHENOMEN --> HUSS[Husserl\n"Back to the things themselves!\nConsciousness is always consciousness of something."]
    PHENOMEN --> HEID[Heidegger\n"Language is the house of Being.\nDasein is the being for whom Being is an issue."]
    PHENOMEN --> MERLEAU[Merleau-Ponty\n"The body is our general medium for having a world.\nPerception ends in objects, while abstract thought moves among symbols."]
    
    %% Contemporary Philosophy
    CON --> ANALYTIC[Analytic Philosophy]
    ANALYTIC --> FREGE[Frege\n"Sense determines reference.\nThoughts are not mental but abstract objects."]
    ANALYTIC --> RUSSELL[Russell\n"Mathematics may be defined as the subject in which we never know what we are talking about.\nThe point of philosophy is to start with something so simple as to seem not worth stating, and to end with something so paradoxical that no one will believe it."]
    ANALYTIC --> WITT[Wittgenstein\n"The limits of my language mean the limits of my world.\nWhereof one cannot speak, thereof one must be silent."]
    ANALYTIC --> QUINE[Quine\n"To be is to be the value of a bound variable.\nThere are no necessary truths knowable independently of experience."]
    
    CON --> CONT[Continental Philosophy]
    CONT --> CRITICAL[Critical Theory]
    CRITICAL --> ADORNO[Adorno\n"The splinter in your eye is the best magnifying glass.\nTo write poetry after Auschwitz is barbaric."]
    CRITICAL --> BENJA[Benjamin\n"Every document of civilization is at the same time a document of barbarism.\nThe tradition of the oppressed teaches us that the 'state of emergency' in which we live is not the exception but the rule."]
    CRITICAL --> HABER[Habermas\n"The public sphere mediates between private opinion and public power.\nCommunicative action aims at mutual understanding rather than success."]
    
    CONT --> POST[Poststructuralism]
    POST --> FOUCAULT[Foucault\n"Knowledge is not made for understanding; it is made for cutting.\nPower is not an institution, a structure, or a strength, but a complex strategical situation."]
    POST --> DERRIDA[Derrida\n"There is nothing outside the text.\nDifférance is neither a word nor a concept."]
    POST --> DELEUZE[Deleuze\n"Philosophy is the art of forming, inventing, and fabricating concepts.\nDesire does not lack anything; it does not lack its object."]
    
    CON --> FEM[Feminist Philosophy]
    FEM --> BEAUVOIR[de Beauvoir\n"One is not born, but rather becomes, a woman.\nWoman is defined as Other to man."]
    FEM --> IRIGARAY[Irigaray\n"Woman has sex organs just about everywhere.\nWestern philosophy privileges visual metaphors reflecting male sexuality."]
    FEM --> BUTLER[Judith Butler\n"Gender is a kind of imitation for which there is no original.\nPerformativity is not a singular act, but a repetition and a ritual."]
    
    %% Class assignments
    class ANC,PRESOC,HERA,PARM,DEMO,CLASSIC,SOC,PLATO,ARIS,HELLEN,EPIC,STOIC,SCEP,NEO ancient
    class MED,EARLY,AUG,BOECON,SCHOL,ANSELM,AQUINAS,OCKHAM,MYST,ECKHART,HILD medieval
    class REN,HUMAN,PICO,ERASMUS,POLPHIL,MACHIA,MORE renaissance
    class ENL,RATIO,DESC,SPINOZA,LEIB,EMP,LOCKE,BERK,HUME,KANT enlightenment
    class MOD,IDEAL,FICHTE,SCHEL,HEGEL,EXIS,KIERK,NIETZ,SARTRE,CAMUS,PRAGMA,PEIRCE,JAMES,DEWEY,PHENOMEN,HUSS,HEID,MERLEAU modern
    class CON,ANALYTIC,FREGE,RUSSELL,WITT,QUINE,CONT,CRITICAL,ADORNO,BENJA,HABER,POST,FOUCAULT,DERRIDA,DELEUZE,FEM,BEAUVOIR,IRIGARAY,BUTLER contemporary

```

This comprehensive Mermaid diagram maps the major movements and thinkers in Western philosophy, from the Pre-Socratics to contemporary philosophers. Each philosopher is accompanied by a distinctive 2-3 sentence quote or phrase that encapsulates their most significant contribution or thinking.

The diagram is organized chronologically and by philosophical tradition:

1. **Ancient Philosophy** (600 BCE - 500 CE)
   - Pre-Socratics (Heraclitus, Parmenides, Democritus)
   - Classical Greek (Socrates, Plato, Aristotle)
   - Hellenistic Schools (Epicureanism, Stoicism, Skepticism, Neoplatonism)

2. **Medieval Philosophy** (500 - 1500 CE)
   - Early Medieval (Augustine, Boethius)
   - Scholasticism (Anselm, Aquinas, Ockham)
   - Mysticism (Eckhart, Hildegard)

3. **Renaissance Philosophy** (1400 - 1600 CE)
   - Humanism (Pico della Mirandola, Erasmus)
   - Political Philosophy (Machiavelli, Thomas More)

4. **Enlightenment** (1600 - 1800 CE)
   - Rationalism (Descartes, Spinoza, Leibniz)
   - Empiricism (Locke, Berkeley, Hume)
   - Kant's Critical Philosophy

5. **Modern Philosophy** (1800 - 1950 CE)
   - German Idealism (Fichte, Schelling, Hegel)
   - Existentialism (Kierkegaard, Nietzsche, Sartre, Camus)
   - Pragmatism (Peirce, James, Dewey)
   - Phenomenology (Husserl, Heidegger, Merleau-Ponty)

6. **Contemporary Philosophy** (1950 - Present)
   - Analytic Philosophy (Frege, Russell, Wittgenstein, Quine)
   - Continental Philosophy
     - Critical Theory (Adorno, Benjamin, Habermas)
     - Poststructuralism (Foucault, Derrida, Deleuze)
   - Feminist Philosophy (de Beauvoir, Irigaray, Butler)

Each section is color-coded for easier navigation, perfect for an ambitious philosophy undergrad who's gone above and beyond the required credits!
