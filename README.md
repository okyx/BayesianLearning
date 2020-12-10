feel free to correct it if i have wrong code or explanation

edible mushroom classification wit bayesian Learning
The Equation of bayesian is below <br/>
&nbsp; ![equation](https://latex.codecogs.com/gif.latex?P%28A%7CB%29%20%3D%20%5Cfrac%7BP%28B%7CA%29*P%28A%29%7D%7BP%28B%29%7D)<br/>
P(A|B) = probabiliy of A happen if B is true
<br/>
P(A) and P(B) = probabiliy of A and B <br/>
in bayesian learning we can say that A is Class and B is data so the equation will be :</br>
![equation](https://latex.codecogs.com/gif.latex?P%28Ci%7CX%29%20%3D%20%5Cfrac%7BP%28X%7CCi%29*P%28Ci%29%7D%7BP%28X%29%7D)<br/>
we know that we use the same data for testing it becomes P(X) for Ci has the same probability the equation will be like below :<br/>
![equation](https://latex.codecogs.com/gif.latex?P%28Ci%7CX%29%20%3D%20%7BP%28X%7CCi%29*P%28Ci%29%7D)<br/>
where i = categorical of class
| Features      	  | Description   					       | values  																|
| ----------------------- |:----------------------------------------------------------:| --------------------------------------------------------------------------------------------------------------------------------------:|
| class      		  | Edible or poisonous 				       | e = Edible, p = poisonous   														|
| cap-shape      	  | The shape of the expanded,upper part of the mushroom       | b= bell, c = conical, x = convex, f = flat, k = knobbed, s = sunken   									|
| cap-surface 		  | The structure of the upper part of the mushroom            | f = fibrous, g = grooves, y = scaly, s = smooth   											|
| cap-color 		  | The color of the surface of the upper part of the mushroom | n = brown, b = buff, c = cinnamon, g = gray, r = green, p = pink, u = purple, e = red, w = white, y = yellow			   	|	
| bruises 		  | Indicates of there are bruises on the mushroom             | t = yes, f = no   															|
| odor 			  | The smell the mushroom omits      			       | a = almond, l = anise, c = creosote, y = fishy, f=foul, m = musty, n = none, p = pungent, s = spicy   					|
| gill-attachment 	  | The way the gill is growing on the mushroom      	       | a= attached, d = descending,f = free, n = notched   											|
| gill-spacing 	 	  | The gap of space between each gill      		       | c = close,w = crowded, d = distant   													|
| gill-size 		  | The size of the gills      				       | b = broad, n = narrow   														|
| gill-color 		  | The color of the gills      			       | k = black, n = brown, b = buff, h = chocolate, g = gray, r = green, o = orange, p = pink, u = purple, e = red, w = white , y = yellow  |
| stalk-shape 		  | The Stalk`s form      				       | e = enlarging, t = tapering   														|
| stalk-root 		  | The root of the mushroom      			       | b = bulbous, c = club, u = cup, e = equal, z = rhizomorphs, r = rooted, ? = missing   							|
| stalk-surface-above-ring| The surface of the stalk above the mushrooms ring          | f = fibrous, y = scaly, k = silky, s = smooth   											|
| stalk-surface-below-ring| The surface of the stalk below the mushrooms ring          | f = fibrous, y = scaly, k = silky, s = smooth   											|
| stalk-color-above-ring  | The color of the stalk above the mushrooms ring            | n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow   					|
| stalk-color-below-ring  | The color of the stalk below the mushrooms ring            | n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow   					|
| veil-type 		  | The type of the mushroom`s veil       		       | p = partial, u = universal   														|
| veil-color 		  | The color of the mushroom`s veil      		       | n = brown, o = orange, w = white, y = yellow   											|
| ring-number 		  | The amount fo rings the mushroom has      	               | n= none, o = one, t = two   														|
| ring-type 	    	  | The type of the mushroom`s ring                            | c = cobwebby, e = evanescent, f = flaring, l = large ,n = none, p = pendant, s = sheathing, z = zone   				|
| spore-print-color 	  | The color of the mushromm`s spore      	               | k = black, n = brown, b = buff, h = chocolate, r = green, o = orange, u = purple, w = white , y = yellow   				|
| population 		  | The populaotion spread      	                       | a = abundant, c = clustered, n = numerous, s = scattered, v = several, y = solitary   							|
| habitat 		  | The mushroom`s environment      			       | g = grasses, l = leaves, m = meadows, p = paths, u = urban, w = waste, d = woods   							|



