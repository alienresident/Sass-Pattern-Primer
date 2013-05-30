#SASS Pattern Primer
\(This is a fork of my sass port of [Pattern Primer]  (https://github.com/alienresident/Pattern-Primer) which is faithful port of the original [Pattern Primer] (https://github.com/adactio/Pattern-Primer) by Adactio/Jeremy Keith.\)

## Key Changes to SASS Pattern Primer
I have created a Compass extension \(ruby gem\) [Compass Pattern Primer]  (https://github.com/alienresident/Compass-Pattern-Primer) to provide the base stylesheets for create a Pattern Primer. 

I have reworked the Pattern Primer to use Jonathan Snook's [SMACSS] (http://smacss.com/) \(Scalable and Modular Architecture for CSS\) as an organizing principle. I've separated the partials into base and modules. 

The intended way to override the original Adactio styling is to change the variables in partials/variables/theme/_overrides. This follows the SMACSS paradigm.

This is a work in progress and any feedback is welcome.

##Original Adactio README

Create little snippets of markup and save them to the "patterns folder." The pattern primer will generate a list of all the patterns in that folder. You will see the pattern rendered as HTML. You will also get the source displayed in a textarea.

You should be able to take the whole "pattern-primer" folder and drop it into your own project (assuming you're running PHP) **BUT** make sure to update the link element in the head of pattern-primer/index.php to point to your own CSS.

Here's a Node.js port: https://github.com/beardtwizzle/pattern-primer-on-node

And here it is in Ruby: https://github.com/micdijkstra/Pattern-Primer-Ruby