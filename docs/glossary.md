# Glossary

This glossary is intentionally **relational**.

Every entry links to at least one other entry. The glossary forms a **single connected graph**:
no term stands alone, and no concept is primitive in isolation.

---

## Quantum Field
A quantum field is a fundamental entity in modern physics: a mathematical structure defined over spacetime whose excitations correspond to what are observed as particles. In quantum field theory, fields—not particles—are the primary carriers of physical degrees of freedom.

A quantum field assigns operator-valued quantities to every point in spacetime. These operators act on states in **[Hilbert space](#hilbert-space)** and encode the possible outcomes of measurements. The field itself is not a material substance filling space, but a formal object that determines how quantum states evolve and interact.

Particles arise as localised, quantised excitations of a field. What is detected experimentally as a “particle” (for example, an electron detected in a detector) corresponds to a discrete interaction event involving a field excitation. The particle concept is therefore emergent and context-dependent, while the field description is fundamental.

Each fundamental type of particle corresponds to its own quantum field. For example, electrons, quarks, photons, and gluons are associated with distinct fields, each with its own properties and interaction rules. Interactions between particles are described as couplings between the corresponding quantum fields.

Quantum fields do not exist independently of one another. Their dynamics and interactions are specified jointly through a Lagrangian or Hamiltonian, which encodes both the behaviour of each field in isolation and the allowed couplings between fields. These **[interactions](#interaction)** determine which excitations can occur, how energy and momentum are exchanged, and which correlations can form.

The field description naturally incorporates **[superposition](#superposition)** and **[entanglement](#entanglement)**. Because field excitations are states in Hilbert space, they can exist in superpositions and become entangled across spacetime regions and subsystems. This is why quantum field theory unifies quantum mechanics with special relativity without reverting to classical particle pictures.

Quantum fields should not be confused with classical fields such as electric or magnetic fields, although they reduce to those fields in appropriate limits. Classical fields emerge when quantum fluctuations are negligible and field operators can be replaced by expectation values, a process closely tied to **[decoherence](#decoherence)** and the **[classical limit](#classical-limit)**.

Importantly, quantum fields are not optional theoretical constructs layered on top of particles. Attempts to describe relativistic quantum phenomena purely in terms of particles lead to inconsistencies. Processes such as particle creation and annihilation, vacuum fluctuations, and the stability of matter are naturally described only in the field framework.

Quantum fields thus provide the deepest currently known description of matter and interaction. They underpin the structure of atoms, chemistry, solid matter, and ultimately biological systems, while remaining fully compatible with the relational, non-object-based ontology revealed by quantum theory.

**See also:** [Hilbert Space](#hilbert-space), [Interaction](#interaction), [Superposition](#superposition), [Entanglement](#entanglement), [Decoherence](#decoherence), [Classical Limit](#classical-limit)

---

## Particle
A localised, quantised excitation of a quantum field, observed as a discrete event (for example, a detector click). “Particle” is a context-dependent description, not a fundamental object.

**See also:** [Quantum Field](#quantum-field), [Measurement](#measurement), [Wave–Particle Duality](#wave–particle-duality)

---

## Interaction
An interaction is a physical coupling between degrees of freedom that constrains how quantum states evolve together over time. In quantum theory, interactions are not forces acting on pre-existing objects, but structural terms in the dynamical laws that link otherwise independent components of a system.

Formally, interactions are encoded as coupling terms in the **[Hamiltonian](#hamiltonian)** or **[Lagrangian](#lagrangian)**. 
These terms prevent the total system from being decomposed into independently evolving parts, enabling the formation of correlations and **[entanglement](#entanglement)**. In the absence of interaction, subsystems evolve independently.

Interactions act on **[quantum fields](#quantum-field)**, not on classical particles. What appear as particle–particle interactions in experiments are manifestations of underlying field couplings. The particle picture emerges only after localisation and decoherence make such descriptions approximately valid.

The specific structure of an interaction determines which observables become correlated and which states are stabilised by decoherence. Measurement is therefore grounded in physical interaction structure, not in abstract projection rules or observer choices.

Interactions function as **constraints** on joint evolution. They do not select outcomes or inject randomness; they delimit which correlations can form and persist. In this sense, interactions define the relational structure of the theory rather than acting as causal pushes or pulls.

At the classical level, interactions give rise to effective **[forces](#force)**. These forces summarise the averaged effects of underlying quantum interactions in regimes where decoherence is strong and quantum interference is negligible.

Interactions are thus foundational to quantum theory: they make subsystems meaningful, enable entanglement, drive decoherence, and ground measurement without invoking observers or collapse.

**See also:** [Quantum Field](#quantum-field), [Entanglement](#entanglement), [Decoherence](#decoherence), [Measurement](#measurement), [Force](#force), [Subsystem](#subsystem)

---

## Coupling
A coupling is a parameter that specifies the strength and form of an interaction between quantum fields or degrees of freedom. Couplings determine how strongly different parts of a system influence one another and which correlations can form over time.

Formally, couplings appear as coefficients multiplying interaction terms in the **[Hamiltonian](#hamiltonian)** or **[Lagrangian](#lagrangian)**.
 They set the scale at which **[interactions](#interaction)** occur and therefore control rates of processes such as scattering, decay, and energy exchange. Changing a coupling changes the dynamics of the theory, even if the fields involved remain the same.

Couplings are not forces. A force is an emergent, classical-level description that arises from interactions in the **[classical limit](#classical-limit)**. Couplings instead belong to the fundamental dynamical description and are defined prior to any particle or force-based interpretation.

In quantum field theory, different couplings govern different interactions. For example, electric charge determines the strength of electromagnetic coupling, while other couplings control weak and strong interactions. These couplings fix which field excitations can interact and how likely particular outcomes are.

The magnitude of a coupling has qualitative consequences. Weak couplings allow subsystems to behave approximately independently for long periods, supporting stable **[subsystems](#subsystem)** and classical behaviour. Strong couplings rapidly generate **[entanglement](#entanglement)** and drive fast decoherence, making isolation and coherent control difficult.

Importantly, couplings are often scale-dependent. Due to quantum effects, the effective strength of a coupling can vary with energy or distance, a phenomenon known as running. This means that interactions that appear weak at everyday scales may behave very differently at high energies or small distances.

Couplings do not select outcomes or introduce randomness by themselves. They constrain which transitions are allowed and with what probabilities, but the probabilistic structure arises from the quantum state and its evolution in **[Hilbert space](#hilbert-space)**.

Couplings thus play a central role in shaping the relational structure of physical theories. They determine how fields connect, how complexity builds up, and which effective descriptions—particles, forces, or classical objects—become valid at different scales.

**See also:** [Interaction](#interaction), [Quantum Field](#quantum-field), [Entanglement](#entanglement), [Decoherence](#decoherence), [Classical Limit](#classical-limit)


---

## Lagrangian
A Lagrangian is a compact mathematical object that encodes the dynamical structure of a physical theory. It specifies which degrees of freedom exist, how they evolve in isolation, and how they interact with one another.

In quantum field theory, the Lagrangian is written in terms of **[quantum fields](#quantum-field)** and their spacetime variations. It does not describe trajectories or forces directly. Instead, it defines the rules from which equations of motion, conservation laws, and interaction processes are derived.

Formally, the Lagrangian determines the dynamics of a system through a variational principle: the physical evolution is the one that extremises a quantity called the action. This principle replaces the classical notion of “cause and effect via forces” with a global constraint on allowed histories.

Interaction terms in the Lagrangian specify **[couplings](#coupling)** between fields. These terms determine which fields can influence one another, how strongly, and under what conditions. In this sense, the Lagrangian is the source of all **[interactions](#interaction)** in the theory.

The Lagrangian also encodes symmetries. Continuous symmetries of the Lagrangian correspond to conserved quantities such as energy, momentum, and charge. These conservation laws are not added by hand; they follow directly from the structure of the Lagrangian itself.

The Lagrangian is not an observable object, nor does it represent physical substance. It is a formal summary of constraints and possibilities. Different Lagrangians define different physical worlds by permitting different patterns of correlation, stability, and emergence.

At the quantum level, the Lagrangian underlies the construction of the Hamiltonian and governs the evolution of states in **[Hilbert space](#hilbert-space)**. At the classical level, it gives rise to effective equations involving forces and potentials, once decoherence and averaging suppress quantum interference.

The success of modern physics rests heavily on the Lagrangian framework. The Standard Model of particle physics is defined almost entirely by its Lagrangian, which specifies the fields, couplings, and symmetries from which the behaviour of matter follows.

The Lagrangian thus serves as a generative blueprint: not a description of what happens moment by moment, but a compact specification of what is allowed to happen at all.

**See also:** [Quantum Field](#quantum-field), [Interaction](#interaction), [Coupling](#coupling), [Hilbert Space](#hilbert-space), [Classical Limit](#classical-limit)

---

## Hamiltonian
The Hamiltonian is the operator that generates time evolution in quantum theory. It specifies how a quantum state changes with time and therefore governs the dynamical behaviour of systems.

Formally, the Hamiltonian acts on states in **[Hilbert space](#hilbert-space)**. The evolution of a quantum state is determined by the Hamiltonian through a deterministic equation of motion, which encodes how amplitudes and phases evolve over time.

The Hamiltonian is derived from the **[Lagrangian](#lagrangian)**, but the two play different conceptual roles. The Lagrangian provides a global specification of allowed dynamics and symmetries, while the Hamiltonian provides a local-in-time rule for how states evolve. In this sense, the Lagrangian defines what is permitted, and the Hamiltonian enacts it.

Interaction terms in the Hamiltonian encode **[couplings](#coupling)** between degrees of freedom. These terms are responsible for generating **[entanglement](#entanglement)**, redistributing coherence, and driving decoherence when systems interact with their environments. In the absence of interaction terms, subsystems evolve independently.

The Hamiltonian does not represent energy as a substance or force. While its expectation value corresponds to energy, its deeper role is structural: it defines the generator of temporal change and constrains which correlations can form over time.

In composite systems, the Hamiltonian typically includes separate contributions for subsystems and their interactions. This structure determines which subsystem decompositions are dynamically stable and which observables are robust under environmental coupling.

At the classical level, the Hamiltonian reduces to familiar energy-based descriptions of motion. At the quantum level, it governs the full relational evolution of states, even when no classical trajectories exist.

The Hamiltonian thus provides the bridge between abstract dynamical constraints and concrete temporal behaviour. It is the engine that drives quantum evolution, entanglement, decoherence, and ultimately the emergence of classical structure.

**See also:** [Lagrangian](#lagrangian), [Interaction](#interaction), [Coupling](#coupling), [Entanglement](#entanglement), [Decoherence](#decoherence), [Hilbert Space](#hilbert-space)

---

## Force
A force is an effective, classical-level description of how the motion of localised degrees of freedom changes over time. Forces are not fundamental entities in quantum theory; they are emergent summaries of underlying **[interactions](#interaction)** when systems behave approximately classically.

In classical physics, forces appear as vectors causing acceleration according to deterministic laws. In quantum theory, however, the fundamental description is given in terms of fields and interaction terms in dynamical equations, not forces acting on objects. The force concept arises only after localisation, averaging, and decoherence suppress quantum interference.

Formally, forces emerge in the **[classical limit](#classical-limit)**, where expectation values of quantum operators follow approximately classical trajectories. Under these conditions, the effects of interaction terms in the Hamiltonian can be rewritten as effective potentials or forces acting on classical variables.

Forces therefore presuppose specific conditions:
- a well-defined subsystem,
- strong decoherence selecting stable classical states,
- and a scale at which quantum fluctuations are negligible.

Outside these conditions, force-based descriptions lose validity and must be replaced by the underlying interaction picture.

Different fundamental interactions give rise to different classical forces depending on symmetry, coupling strength, and scale. For example, electromagnetic interactions produce familiar forces between charges, while quantum chromodynamic interactions confine quarks and do not yield simple long-range forces.

Forces are thus powerful and indispensable within their domain of applicability, but they are not ontologically basic. Treating forces as fundamental obscures the relational and field-based structure that quantum theory reveals.

**See also:** [Interaction](#interaction), [Quantum Field](#quantum-field), [Decoherence](#decoherence), [Subsystem](#subsystem)

---

## Coherence
The preservation of well-defined phase relationships within a quantum system. Coherence is required for interference and other distinctly quantum phenomena.

**See also:** [Decoherence](#decoherence), [Superposition](#superposition)

---

## Hilbert Space
Hilbert space is the abstract mathematical space in which quantum states are represented. Each physical state corresponds not to a point in ordinary space, but to a ray (an equivalence class of vectors differing by overall phase) in a complex vector space equipped with an inner product.

Hilbert space is **not physical space**. Its dimensions do not correspond to spatial directions or hidden coordinates. Instead, they correspond to independent degrees of freedom required to describe a system. Even a single particle can require an infinite-dimensional Hilbert space, while many-particle systems typically inhabit spaces of extremely high dimension.

The structure of Hilbert space encodes the core features of quantum theory. Superposition corresponds to vector addition, probabilities arise from inner products, and observables are represented by operators acting on the space. Incompatible observables reflect non-commuting operators, not experimental disturbance.

For composite systems, the Hilbert space is constructed as a tensor product of subsystem spaces. This structure allows states that cannot be factorised into independent parts, giving rise to entanglement. Whether a state is entangled therefore depends on how the Hilbert space is factorised into subsystems, reinforcing the contextual nature of subsystem definitions.

Measurement is represented mathematically by projections or more general operations on Hilbert space, corresponding to the establishment of correlations between a system and an apparatus. Decoherence explains why certain subspaces become dynamically stable and why interference between them becomes unobservable.

Hilbert space should not be reified as a hidden arena in which physics “really” takes place. It is a formal structure encoding relational constraints, probabilistic structure, and dynamical possibilities. Its power lies in what it enables us to calculate and predict, not in any direct physical interpretation.

Hilbert space thus provides the formal setting for quantum theory while remaining conceptually distinct from spacetime. Confusing the two is a common source of interpretational error.

**See also:** [Superposition](#superposition), [Entanglement](#entanglement), [Subsystem](#subsystem), [Measurement](#measurement), [Decoherence](#decoherence)

---

## Decoherence
Decoherence is the physical process by which phase relationships within a quantum system become dispersed into correlations with many uncontrollable degrees of freedom in the environment. As a result, interference between certain alternatives becomes practically unobservable, even though the overall quantum state continues to evolve according to standard quantum dynamics.

Formally, decoherence is described within **[Hilbert space](#hilbert-space)** under time evolution generated by the **[Hamiltonian](#hamiltonian)**. 
When a subsystem becomes **[entangled](#entanglement)** with environmental degrees of freedom that are not tracked, the combined state spreads coherence across the larger system. Describing only the subsystem then requires ignoring (tracing over) the environment, yielding a reduced state in which interference terms are strongly suppressed.

Decoherence does **not** eliminate superposition or entanglement at the global level. Instead, it redistributes coherence from a small, controllable subsystem into correlations with a much larger environment. From the perspective of the subsystem alone, the state appears mixed rather than coherent.

Which states are stabilised by decoherence depends on the interaction structure between subsystem and environment. Certain states remain robust under continual environmental interaction, while superpositions of those states rapidly lose observable coherence. This explains why specific classical variables—such as position—are preferentially realised in everyday experience.

Decoherence explains the emergence of classical behaviour, effective irreversibility, and stable classical records without introducing a physical collapse of the quantum state. However, it does not by itself select a single outcome from among alternatives; it explains why alternatives fail to interfere, not why one is realised.

Decoherence therefore marks the boundary between quantum relational structure and classical appearance. It is the mechanism by which classical descriptions become valid approximations within an underlying quantum theory.

**See also:** [Environment](#environment), [Subsystem](#subsystem), [Measurement](#measurement), [Classical Record](#classical-record)

---

## Environment
The environment is the collection of degrees of freedom that are not explicitly treated as part of the subsystem of interest but nevertheless interact with it. The distinction between “system” and “environment” is contextual, not fundamental.

Formally, defining an environment corresponds to partitioning a global Hilbert space into a subsystem of interest and the remainder. This partition is guided by practical considerations such as experimental control, interaction strength, and observational relevance, rather than by any intrinsic boundary in nature.

The environment plays a central role in decoherence. When a subsystem interacts with many environmental degrees of freedom, information about its state becomes widely dispersed and redundantly encoded. This suppresses observable interference within the subsystem and stabilises certain classical descriptions.

The environment is not merely a sink that destroys quantum information. Globally, interactions with the environment typically *increase* entanglement by distributing coherence across larger systems. What is lost is not information, but local accessibility to that information.

Which aspects of a system become classical depends on how the environment couples to it. Environmental interactions continuously “monitor” certain variables (such as position or orientation), selecting preferred states that remain robust under further interaction. This explains the emergence of stable classical records without invoking collapse.

Because subsystem–environment distinctions are contextual, what counts as the environment in one description may itself be treated as a subsystem in another. There is no absolute environment, only relative partitions within a larger relational structure.

The environment thus provides the bridge between quantum relational dynamics and classical appearance. It enables decoherence, stabilises records, and grounds the practical irreversibility of measurement, while remaining fully part of the quantum description.

**See also:** [Decoherence](#decoherence), [Subsystem](#subsystem), [Measurement](#measurement), [Classical Record](#classical-record), [Entanglement](#entanglement)

---

## Entanglement
Entanglement is a structural feature of quantum states in which the state of a composite system cannot be decomposed into independent states of its subsystems. It reflects irreducible relational structure, not hidden connections or signals between objects.

Formally, entanglement is defined within **[Hilbert space](#hilbert-space)**. For a composite system, the total Hilbert space is constructed as a tensor product of subsystem spaces. A state is entangled if it cannot be written as a simple product of states belonging to each subsystem. This non-factorisability is the precise mathematical content of entanglement.

Entanglement is **not** equivalent to strong correlation. Classical systems can exhibit correlations of arbitrary strength while remaining fully separable. Entanglement instead indicates that no complete description of the whole system can be obtained by specifying the states of the parts alone.

Whether a system is entangled depends on how it is partitioned into subsystems. Different factorizations of the Hilbert space can lead to different judgements about entanglement. There is therefore no observer-independent, intrinsic notion of “what is entangled with what” without specifying a subsystem decomposition.

When entangled systems are measured, outcomes on one subsystem can update expectations about another because both are aspects of a single global state. This does not imply faster-than-light influence; it reflects shared structure established by prior interaction.

Decoherence does not eliminate entanglement at the global level. Instead, it typically redistributes entanglement from small, controllable subsystems into large, uncontrollable environments, making it locally inaccessible while increasing global correlations.

Entanglement thus reveals a fundamental feature of quantum theory: the whole is not built from independently defined parts. Relations come first, and parts are defined only within those relations.

**See also:** [Subsystem](#subsystem), [Decoherence](#decoherence), [Measurement](#measurement), [Superposition](#superposition)

---

## Subsystem
A subsystem is a chosen partition of a larger quantum system, defined by selecting a subset of degrees of freedom and treating the remainder as external. Subsystems are not fundamental objects; they are contextual decompositions used to make description and prediction tractable.

Formally, a subsystem is defined by a factorisation of **[Hilbert space](#hilbert-space)**. The total Hilbert space of a composite system may be written as a tensor product of smaller spaces, each associated with a subsystem. This factorisation is not unique, and different choices can lead to different descriptions of the same physical situation.

Because subsystem definitions depend on how Hilbert space is factorised, they are not fixed by nature alone. They are constrained by interaction structure, experimental accessibility, and decoherence, but they are not absolute. What counts as a “system” in one context may be part of the “environment” in another.

Entanglement is always defined relative to a chosen subsystem decomposition. A quantum state may be entangled with respect to one partition and separable with respect to another. There is therefore no observer-independent notion of subsystems prior to specifying how the system is divided.

Decoherence stabilises certain subsystem decompositions by suppressing interference between alternative states. These preferred decompositions support robust classical records and explain why familiar macroscopic subsystems appear well-defined despite the underlying arbitrariness of partitioning.

Subsystems thus function as pragmatic units of description rather than ontological primitives. They enable locality, measurement, and classical reasoning to emerge from an underlying relational quantum structure.

**See also:** [Entanglement](#entanglement), [Decoherence](#decoherence), [Measurement](#measurement), [Environment](#environment)

---

## Measurement
Measurement is a physical process in which a quantum system becomes entangled with a measuring apparatus and its environment, followed by decoherence that stabilises correlations into classical records. It is not a primitive or special operation, but a composite process arising from ordinary quantum dynamics.

Formally, measurement is described within **[Hilbert space](#hilbert-space)** as evolution generated by the **[Hamiltonian](#hamiltonian)** of the joint system–apparatus state into a superposition of correlated outcome branches. These branches correspond to distinct subspaces associated with different possible results, determined by the interaction structure between system and apparatus.

Measurement does not require consciousness, intention, or an observer in the everyday sense. It occurs whenever information about a system becomes redundantly encoded in environmental degrees of freedom such that interference between alternatives is effectively suppressed.

Which observable is measured is fixed by physical coupling, not by abstract choice alone. The interaction selects which degrees of freedom of the system become correlated with stable states of the apparatus and environment. Decoherence then renders these correlations robust and persistent.

Decoherence explains why measurement outcomes are stable, communicable, and effectively irreversible. It does not, by itself, explain why a single outcome is experienced rather than a superposition of alternatives. Different interpretations of quantum mechanics address this residual question without altering the underlying formalism.

Measurement thus marks the transition from quantum relational structure to classical description. It is the process by which abstract quantum correlations become concrete, shared features of the physical world.

**See also:** [Interaction](#interaction), [Entanglement](#entanglement), [Decoherence](#decoherence), [Classical Record](#classical-record), [Subsystem](#subsystem)

---

## Classical Record
A classical record is a stable, persistent, and redundantly encoded imprint of a quantum event in physical degrees of freedom that allows consistent agreement across multiple subsystems. Classical records are the end products of measurement and the basis of objective, shared classical reality.

A record is not classical merely because it is macroscopic. It is classical because interference between alternative record states is effectively suppressed by decoherence, and because information about the outcome is distributed across many environmental degrees of freedom.

Formally, a classical record arises when a subsystem becomes entangled with an apparatus and environment in such a way that distinct outcome states correlate with nearly orthogonal environmental states. This redundancy makes the record robust against local disturbances and independent of any single observer.

Classical records are characterised by **stability** (they persist over time), **redundancy** (the same information is encoded in many places), and **accessibility** (multiple subsystems can independently acquire the same information). These properties explain why records appear objective and irreversible in practice.

The emergence of classical records does not require wavefunction collapse. Globally, the quantum state continues to evolve unitarily. What changes is that alternative outcomes no longer interfere, and the correlations defining the record become effectively permanent.

Classical records ground empirical science itself. Experimental data, memories, written notes, detector clicks, and digital files are all classical records—physical structures whose reliability arises from decoherence and environmental redundancy, not from privileged observers.

Classical records therefore mark the point at which relational quantum structure becomes part of the shared classical world. They are not fundamental objects, but emergent features stabilised by interaction with the environment.

**See also:** [Measurement](#measurement), [Decoherence](#decoherence), [Environment](#environment), [Entanglement](#entanglement), [Subsystem](#subsystem)

---

## Superposition
Superposition is the principle that a quantum state can be expressed as a linear combination of other possible states within Hilbert space. It reflects the linear structure of the theory, not the coexistence of multiple classical realities.

Superposition does **not** mean that a system simultaneously possesses multiple definite classical properties. Rather, it means that the quantum state encodes multiple mutually exclusive possibilities whose relative phases can influence future probabilities through interference.

Formally, if a set of states forms a basis for a Hilbert space, any allowed state can be written as a weighted sum of those basis states. The choice of basis matters: a state that is a superposition in one basis may be a definite state in another. There is no basis-independent notion of “being in superposition.”

Superposition is therefore not an absolute property of a system, but a relational one that depends on how the state is described and which observables are considered. This is why claims such as “the particle is in two places at once” are misleading without specifying the measurement context.

Entanglement extends superposition to composite systems. An entangled state is a superposition of correlated subsystem states that cannot be factorised into independent parts. In this sense, entanglement is structured superposition across subsystems.

Decoherence suppresses the observable consequences of superposition by dispersing phase information into the environment. This does not eliminate superposition globally, but renders interference between alternatives inaccessible at the level of subsystems and classical records.

Superposition is thus a statement about how quantum states combine and evolve, not about macroscopic simultaneity or paradoxical coexistence. It is a formal feature of the theory that underlies interference, entanglement, and probabilistic outcomes.

**See also:** [Hilbert Space](#hilbert-space), [Entanglement](#entanglement), [Decoherence](#decoherence), [Measurement](#measurement), [Subsystem](#subsystem)

---

## Classical Limit
The regime in which quantum behaviour averages out and effective classical laws emerge. The classical limit is characterised by strong decoherence and robust classical records.

**See also:** [Decoherence](#decoherence), [Force](#force), [Emergence](#emergence)

---

## Emergence
The appearance of stable, higher-level behaviour from underlying dynamics without introducing new fundamental laws. Classical objects, forces, and trajectories are emergent phenomena.

**See also:** [Classical Limit](#classical-limit), [Force](#force), [Quantum Field](#quantum-field)

---

## Gravity-Induced Collapse
A speculative class of proposals in which gravitational effects cause an objective breakdown of quantum superposition. No experimental evidence currently supports such mechanisms.

**See also:** [Superposition](#superposition), [Decoherence](#decoherence)

---

## False Vacuum
A metastable configuration of a quantum field that is not the lowest possible energy state. A false vacuum may decay via quantum tunnelling, changing the local laws of physics.

**See also:** [Quantum Tunnelling](#quantum-tunnelling), [Quantum Field](#quantum-field)

---

## Quantum Tunnelling
A probabilistic transition through an energy barrier that is forbidden in classical physics. Tunnelling plays roles in particle physics, chemistry, and cosmology.

**See also:** [False Vacuum](#false-vacuum), [Superposition](#superposition)

---

## Wave–Particle Duality
The context-dependent appearance of quantum excitations as either localised events or extended interference patterns. This duality reflects limitations of classical categories.

**See also:** [Particle](#particle), [Coherence](#coherence)

---

## Relational Ontology
The view that relations are fundamental and that objects are derived, stable patterns within a network of interactions. Quantum theory naturally supports a relational ontology.

**See also:** [Entanglement](#entanglement), [Subsystem](#subsystem), [Emergence](#emergence)
