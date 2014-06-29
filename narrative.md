
1
===
Intro.

Messy = practice vs order and communication through documents.

2
===

Lab = "Mangle" - materials, methods, theories, and documents.

Not a computaional env in the sense of silicon and transistors 

Bring web and computational tools to support science in this environment



3
===

Sara Winchester + House.

Following death of Mr Winchester - Sara visited pyschic medium - travel west and continually build a home - herself and the spirits of people who had died because of winchester rifles. 

Sara believed her fourtune to be haunted, and so she buit this mansion which was under continious construction day and night for 38 years until her death. 

Thus house is famous for it's chaotic layout and complete lack of any master building plan. Sara would hold seances every evening and spirits would guide her in developing the construciton plans - which were often written down 'back-of-the-napkin' style.


The house is full of architechtural oddities such as doors that lead nowhere, steps down7up11, upsidedown columns, and plethora of different fitings. Trying to understand or naviagte the building is difficult, and no one really knows what features of the house were mistakes, whimsy, or deliberate decisions that had to be made for practical reasons or due susperstious beliefs. 

4
===

And so navigating science at the bench is a little like being in Winchester house in its day.

	- Our Laboratory protocols are the written instrucutions for how we build things
	- The knowledge is constatntly under construction and remodelling
	- Documents and reserach objects are relatively unstructrued, and are a mix between paper and digital resources.
	- And although not usually guided by seances and supernatural forces, our design decisions tend to be left implicit or opaque - context and details become lost as we contiounsly build and adapt. 
Lab knowledge is messy.
And the way that we manage it impacts the discovery, reuse, and reproducibility of our laboratory science. 

5
===

So what i'm interested in, is how we can re-imagine our lab protocols - our documents and written descriptions of laboratoy procedures -
to take advantage of the web and computational tools. 
And importantly, do so in a way that actaully interfacess with the "messy" practice of bench science.  

6
===
So lets consider how we can make protocols 1st class digital objects for science. 
How can we make them web addressible docuemts with strucure and metadata...

7
===
One way is incorporate bioOntologies.
Here's a typical statement from a lab procedure - 
When this is in digital form we can annotate this text with terms from exisiting ontologies to assert additional information about entites and their relationships.
The additional knowledge added using ontologies can be leveraged to pe
rform automated reasoning, enhanced search, and faceted browsing.

8
===
Another technique we can use is workflow technologies.
Workflows take a process orientated view and allow us to represent the sequece of operations, inputs + outputs in more formal way.
The people orientated execution environment limits some the affordances that formal workflows can offer however. 

7
===
Ontologies and workflows can give us structredm machine readable specificaitons of the what and how of our lab procedures.
And this is pretty cool - but there's still important information missing that we need to translate our descriptions back into practice across different laboratories. We frequency need to answer questions about the "Why?" as well.


8
===
Every description of a lab procedure is the design of a solution to a problem.
And the solution will always exist and be shaped by the context. 
This context forms the background knowlege and lab specific constraints that influence the details of our experimental designs and ways of doing things.
This context is a critical part of the "messy" knowledge of lab science. 
As well as describe what and how of an experiment, we can describe the things that influence the what and how - make the context explict rather than a fuzzy idea.

9
===
So a way to think about context is exemplified by this pic of a milk drop.
We can describe the milk, or the procedure for making drops.
But this milk drop is also a diagram that shows how various forces are at play such as gravity,surface tension and how they are resolved.
There is always a structure around the things we design that influce the form. 

But we often ignore it or fail to make it explicit. 
When we consider the context around what we design, we can better understand the complex realtionship between form, function, and structure. Between process and goal. 

10
===
This way of thinking is one of the key insights that Design Patterns can offer us.
Design Patterns were first conceived by architech Christopher Alexander, and have been influential in a number of different domains since.
I dont hoave time to go into design patterns, here, but one of the things they give us is a vocabulary and shared language to describe the context and aspects of the external environment around our designs that are recurring and generalisable. 

11
===
So when we apply design pattern ideas to a laboraoty experiment, we realise that there recurring features of the environment that constrain and shape our experimmental designs in practice. For example, a live imaging experiment must always balance or resolve the forces of -....

Design patterns capture the 'fuzzy' or implicit context and makes it concrete and usable.

12
===
Once we uncovered and named them, if we incoporate pattern concepts into our descritpions we have a novel and very powerful way to hanldle lab knoweldge. Patterns can give us a way to paramaterise our experimental designs via external constraints, and we can slice or filter our knoweldge via more pragmatic contexts - in ways that match the concerns we have in actaul practece - "at the bench".

13
===
So putting all this together - i've been making progress in realizing some of these ideas.

14
===
First step is to create design patterns as a vocabulary for laboratory experiments.

15
===
I've developed a knowledge eliciation framework to uncover laboratory patterns and contexts with domain experts. 

16
===
Eliciation workshops and design patterns traditionally work best on paper, so next I've created a pattern schema and a web app that utilises lots of forms in order for the comminty to transfer the knowledge on paper into a strucutred digitial form.

17
===
And finally, I'm specifiying a decalative mapping to transform the knoweldge that evolves on the pattern web site into a shrable and reusable vocabulary expressed in RDF.

18
===
The second undertaking is to address the authoring and publishing of structured lab procedures.
There's a lot of ways we could procced here

19
===
Long story short, I've settled on HTML + RDFa as the best container to house our lab protocols.

20
===
The biggest challenge is making it easy for scientist to author structured docuemnts - the solution i've come up with is to modify and join two existing tools.
LabTrove - blog style ELN (uniSoton)
RDFaCE is a WISIWYG RDFa/HTML content editor - based on widely used tinyMCE.
	- allows for easy right click annotation of text in HTML documents.

21
===
So in the near future - we'll have a system for creating design patterns for lab erxperiments, a pragamtic vocabulary that can add context and complemetn existing bioontologies, and a system for incorporating machine readbale semantics and structured metatdata into lab protocol descriptions.

22
===
So we hopefully we have achieved - 


