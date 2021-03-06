# business_demos
# AI for Business Writing/Reports 
See a quick demo here:
https://www.youtube.com/watch?v=JfO0KLY_ask

<a href="http://www.youtube.com/watch?feature=player_embedded&v=JfO0KLY_ask
" target="_blank"><img src="http://img.youtube.com/vi/JfO0KLY_ask/0.jpg" 
alt="Youtube Link" width="240" height="180" border="10" /></a>

**Here's some samples written entirely by A.I.:**

### Sample Text Written entirely by Neural Architecture given the input string 'Lithium Battery Costs'
[Lithium Battery Costs] The US has not yet signed an agreement with Lithium-ion batteries, but its plans are expected to be finalized next year.

The company plans to take lithium-ion batteries with each new generation of batteries that it has developed using a different process, said Richard Pemberton, director of research at Lithium-ion Battery Research at the University of California, Berkeley.

"Lithium-ion batteries are essentially designed to work under specific conditions, so we're not going to be able to guarantee these are the best lithium-ion battery we have right now," he said.

Pemberton said lithium-ion batteries have been a problem for batteries that were made for use in the US.

"We'd like to do well because that is where our ability to produce it is really strong and we're very competitive," he said.

A lithium-ion battery can be made, or not,

Pemberton said the company will make a second batch of lithium-ion batteries.

But he said it would be a long way from being commercially viable to produce lithium-ion batteries, at least in the US.

"We're pretty much a very good manufacturer. We're very good at making things that are very low cost, very low cost," he said.

Lithium-ion batteries are the world's cheapest, but Pemberton said their cost-per kilowatt hour is too high for large power plants.

"It's not the same as other batteries, it's not the same as other batteries that are cheap, and it's not something that we can afford," he said.

Pemberton said the future of lithium-ion battery manufacturing in the US depends on a combination of technologies.

"It depends on the technology, on the ability to produce that type of battery for a very long time," he said.

"It depends on the quality of the battery. It depends on the performance of that battery."

Pemberton said the company is confident that the next generation of batteries will be much more efficient than the current generation of batteries.

"The next generation of batteries are going to be much more effective than previous generation batteries," he said.

The US government does not have a policy on the use of lithium-ion batteries.

Lithium-ion batteries can be used 

### Sample Text Written entirely by Neural Architecture given the input string 'Beef Industry Emissions'
[Beef industry emissions] are expected to be up by almost 50% this year, and by 70% in 2015, according to the International Energy Agency. The country is poised to lose more than 5m tonnes of carbon dioxide from its industrial activities and the planet's main source of energy, according to the report.

The report, "Global Emissions from Emissions from the World's Most Hazardous Goods", is based on data from the WHO's annual Global Emissions Report, from 2006 to 2011. It estimates that about 1.2bn tonnes of fresh produce (including meat and seafood) will be lost by 2030.

The report, which was recently re-released as the World Economic Forum's sixth report on climate change, warns that emissions from mining and agriculture are set to rise by more than 10% in the next five years, with the world's biggest exporters, China and India, the world's biggest consumers of raw materials, expected to see their emissions jump by almost 20%. China will have the biggest share of the global emissions.

The report highlights the growing vulnerability to climate change and the need for action to tackle the problem. It states: "Global temperatures are projected to rise by 8.7 degrees Celsius by 2100, and by 4.3 degrees Celsius by 2035, at a rate of 2.6 percent a year. The world's poorest countries are expected to suffer the greatest impact."

The report also calls for an increase in the development of carbon capture and storage technologies, which could help reduce carbon pollution. It recommends that governments invest in carbon capture and storage (CCS) and use it to help reduce carbon loss. It calls for a shift from fossil fuels to clean energy, which will save about 2.2% of total electricity consumption by 2050.

The report also calls for an increase in the size of the global economy and the development of sustainable transport. It calls for a shift towards clean technologies and for an international economic leadership.

The countries are also urged to set ambitious targets for reducing emissions of greenhouse gases, including carbon dioxide, and to reduce the use of fossil fuels, and to take action to reduce their emissions.<|endoftext|>A new study in the journal Science suggests that the chemical imbalance that's been linked to obesity could be the reason why the global population is growing faster than ever before.

The study, published in the journal Proceedings of the National Academy of Sciences, found that the proportion of Americans that are overweight or obese was at its highest in nearly half a century, and that

## Discussion
The above output are the raw outputs given by the Neural Network for these particular instances of inputs. I.e. I just chose some numerical parameters and typed in 'Lithium Battery Costs' or 'Beef Industry Emissions' - nothing else - everything written up there is written entirely by the neural network, not edited by me in any way, shape or form.

### Refinements
We can see that they both end on incomplete sentences. Obviously this has a simple fix (if output[-1] != '.': keep writing) but I opted to leave the raw output here to get more output data. 

Does tend to plagiarise to varying degrees, the beef emissions writing was plagiarised 6% and the lithium battery one was 33% plagiarised, according to plagiarismdetector.net. This is actually all well and good. As I mentioned, this architecture was originally designed for academic and technical writing. We DO NOT want it to get artistic and interpretive with hard data and technical terms, a mantra that largely carries over to business reporting. 

Also tends to trail off-topic towards the end of the writings. The last sentence of the Beef Emissions example starts to get into obesity. It does discuss something about a link between emissions and obesity in the preceding sentences, which is likely why it sees obesity as a natural progression of the writing. This kind of tangential writing can be tampered with some more rule-based methods were this to ever be packaged into a product. Again, this is just the neural architecture at work here, no such rule-based methods applied. 

**Names.** When it comes to names the neural network seems to go a bit wacky. I cannot find a 'Richard Pemberton' who has anything to do with lithium-ion batteries. References to people will likely need to be checked by a rule-based algorithm. 

# AI for Phishing Detection
See complete implementation in the image below. The 1st email tried is a normal email. The 2nd is spam but not an outright phishing attempt. The 3rd is a blatant phishing and/or scam attempt.
![Alt Text](cynet_example1.png)

See quick demo here:
https://www.youtube.com/watch?v=lT959TbcoSA

<a href="http://www.youtube.com/watch?feature=player_embedded&v=lT959TbcoSA
" target="_blank"><img src="http://img.youtube.com/vi/lT959TbcoSA/0.jpg" 
alt="Youtube Link" width="240" height="180" border="10" /></a>

## Discussion
Detects spam & phishing emails reasonably well but certainly needs more refinement before being deployed in any professional capacity. 
