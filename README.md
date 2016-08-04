# VibViz-Dataset
This repository contains all 120 vibrations for the VibViz library including their (.wav) files, their aggregated ratings and tags, and the MDS dimensions for the Sensation, Emotion, Metaphor, and Usage Facets.

 Content of "viblib" folder: 120 .wav files
 
 Content of "vibrationAnnotations-July24th2016.csv" includes vibration names and attributes:

Attributes for each vibration:
	id: unique identifier that matches the name of the vibration wave file
	index:vibration index in the library (just for programming purposes)  

	Ratings: average of the ratings by participants in a likert scale range of [-3,+3], representing low to high levels of the attributes
	energy
	tempo
	roughness
	pleasantness
	arousal

	Tags:
	sensationTags
	emotionTags
	metaphors
	usageExamples
	
	MDS dimensions: dervied with a classical MDS analysis on vibration distances.
	sensationD1 - Complexity
	sensationD2 - Continuity
	sensationD3 - Roughness
	sensationD4 - Duration
	
	emotionD1 - agitation (calm and pleasant vs. agitating and urgent)
	emotionD2 - liveliness (boring vs. lively and interesting)
	emotionD3 - strangeness (rhythmic and mechanical vs. strange and surprising)
	
	metaphorD1 - on-off and nuanced vs. ongoing and repetitive
	metaphorD2 - natural vs. mechanical
	
	UsageD1 - awareness vs. attention-demand
	
	Please visit http://www.cs.ubc.ca/labs/spin/vibviz. Should you have any questions regarding this dataset or VibViz interface, feel free to contact seifi@cs.ubc.ca 
	
	Author's webpage: http://www.cs.ubc.ca/~seifi/
	
	
