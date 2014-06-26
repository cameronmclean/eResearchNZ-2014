- hole analogy for describing context, or maybe thompsons milk drops....

- stucuturing protocols - balance between free form and metatdata, - 5 star linked open data...

- a proposal to capture contexts, make them conrete and usable...

- add this to a protocol authoring system.

- solves the winchester house / death by previously described problem... - context and details are lost as we continually build and adapt...

- experimental design is design - science of the artificial
- we need blueprints that show the complex relationships between form, function, structure, process and goal...



Communicating and managing the ‘messy knowledge’ of biology wet lab
experiments.

Organising our knowledge of laboratory
experiments in ways that can be interpreted and shared by both human and
machine is desirable for leveraging computational tools to assist the
discovery, reuse, integration, and reasoning over our scientific
knowledge. Ontology
or workflow based tools are often employed to achieve such goals. The
successful adaption, reuse, or replication of a laboratory experiment
however,
requires the description and communication of more than mere ‘entities’
and ‘processes’
described by our current tools - it relies heavily on individual background
knowledge, situated understanding, and a design rationale that is often
specific to local contexts or laboratories. Communicating this ‘messy
knowledge’
in a structured way remains challenging, and we lack good tools to
describe and
encode these more pragmatic concepts. To facilitate the sharing and
integration
of laboratory knowledge in the real world, i.e., "at the bench", we
identify design patterns which offer an approach and vocabulary that can
extend
our laboratory descriptions with additional elements such as intent,
purpose,
and situational constraints. We report here on progress towards the
utilisation
of design patterns to capture and communicate such ‘messy knowledge’, and
we
demonstrate an approach for transforming traditional design patterns into
a more
formal and structured form that can integrate with ontologies or other
computationally based representations.cp

####Slide 1
How we can leverage digital communication and computing technology to improve the discovery, reuse, and reproducibility of our knowledge for experimental biology.

My title here refers to the "messy" knowledge of lab experiments - because part of the provocation for my research is the contrast between actual laboratory practices - i.e., the work of _doing_ experiments, and that of the 'appearance of technical order' and the ways we currently communicate and evaluate lab work via documents... This gap can at times be perilous. 




####Slide 3
<pics of bench, notebook, protocols, journals>

So - of these procedures for conducting biology experiments...

The predominant way that we communicate and evaluate laboratory work is via either "laboratory protocol documents" or the "methods" sections of published journal articles.

You can think of lab protocols as analogous to cooking recipe or S.O.P - in that they are written instructions that describe the sequence of procedures that one should follow in order to produce or *reproduce* a certain state or observation. The knowledge reported in these documents is critically important - not only for communicating and evaluating science that that has been done, but also to allow reuse and re-purposing of lab procedures for other questions or problems.

The way that we currently handle these documents in biology however is a bit behind the times.  

Firstly - they are typically unstructured. They exist in a prose format for reading or printing, with little to no metadata or machine readable semantics.

Secondly - the knowledge is fragmented. Published reports alone are not enough - a researcher typically must consult between a mixture of trusted colleagues, other papers, their experience, and various other places on the web in order to reuse or adapt a lab procedure to their particular experiment.  

So, for example, a typical procedural description from a journal article looks like this....

####Slide 3
<live imaging method example>

_read step_

A great deal of context and background knowledge is required to understand and reuse the knowledge.

For example - if I want to use this procedure in my lab - I may have questions such as - 
	- do i have to use low m.p. Agarose or is reg OK
	- I only have plastic dishes, will this affect the procedure? 
	- will the procedure work for specimens other than (zebrafish) larvae?

Unless we are already experts - the answers to these questions can be very difficult or laborious to obtain from our record in its current format - that is if it even contains them at all.

The lab protocols we publish tend to be ideal-typical and say nothing about contingencies, nor capture or describe more 'concrete' bench practices that can be critical when enacting such procedures. 

Unfortunately this scenario is well known to practicing scientists - so much so that it has become somewhat proverbial - 

####Slide 4
<twitter screen caps>
For example, we have the popularity of the #overlyhonestmethods hashtag that makes light of the many difficulties of lab benchwork. 

But also more seriously, 

####Slide 5
<reproducibility crisis>
A number of high profile publications recently brought to light a mini "reproducibility" crisis in the biomedical sciences - where an alarming fraction of experiments were unable to be reproduced - often due to technical errors and the quality of the reporting.

So clearly, there are are couple of things we could improve upon if we want to make our laboratory methods more accessible, understandable, computable, and reproducible. 

####Slide 6

We need to capture more of the context and practice 
	We need to add more structure to leverage computational technologies 

 
####Slide 7 

<strucutre>

So if we can add a bit more structure to the descriptions of our lab procedures, then we can better leverage computational tools to assist the
discovery, reuse, integration, and reasoning over our scientific knowledge. This can help us find the relevant information quickly and provide less ambiguous terms to describe our knowledge. 

Ontology and workflow based tools are often employed to achieve such goals.


####Slide 7
<ontology>
	Many of the terms present in our descriptions of lab procedures can be found in existing BioOntologies, and annotation tools can allow us to assert additional information in our documents. 
	Adding machine readable semantics affords opportunities for granular and faceted search, and even possibility of a complete logical specification of a bench procedure.  


####Slide 8
<workflows>
	We can use workflows too, whcih take a process orientated view. Workflows tools can model and provide structure and computability to the sequences and operations in procedural descriptions. 
	Note however - despite the intuitive fit, teh potential of formal workflow descriptions of lab work are limited by the human execution environment. 

####Slide 8



####Slide 9

####Slide 10

=====================

#### 1
How we can leverage digital communication and computing technology to improve the discovery, reuse, and reproducibility of our knowledge for experimental biology.

My title here refers to the "messy" knowledge of lab experiments - because part of the provocation for my research is the contrast between actual laboratory practices - i.e., the work of _doing_ experiments, and that of the 'appearance of technical order' and the ways we currently communicate and evaluate lab work via documents... This gap can at times be perilous. 

#### 2
So the work I'm aiming to support mostly happens here... This is a typical laboratory setting.

A researcher performing a biology experiment at the bench is deep in the 'mangle' of arranging various materials and technical equipment, relying on theories about how things work and kinds of things they are investigating.. - and all of this occurs within a context for a given lab or domain of research. 

So you'll note that this not your typical computational environment ... there aren't even any computers in this particular picture .., but I'm interested in how we can use computers to support the "people procedures" of researchers doing bench science. 

#### 3

Reproducibility is key ingredient in any scientific methodology -  So then - How do you do reuse or reproduce all or part of a molecular biology experiment?

One of the key elements you'll need is a lab protocol, or a description of the materials, equipment, and sequence of steps to follow in order arrive at a certain state or observation.

Such published descriptions of lab procedures constitute the predominant way in which researchers guide their own and other's actions, and they serve as the basis for judging the validity of observations or findings. 



