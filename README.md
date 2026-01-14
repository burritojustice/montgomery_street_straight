# Montgomery Street Straight

Zoomable slippy map of a proposed extension of Montgomery St from 1868, which would have run south from Market St through SOMA to Connecticut St. 

https://burritojustice.github.io/montgomery_street_straight/

map screenshot:

![full map](https://github.com/burritojustice/montgomery_street_straight/blob/master/montgomery_street_straight.png)

Thanks to @[datapointed](https://twitter.com/DataPointed/status/1096493114322124800) for pointing it out!

![via datapointed](DataPointed_2019-Feb-15.jpg)

Map via David Rumsey:

https://purl.stanford.edu/cx298pr4007

Learn more about "Montgomery Street Straight" and other real estate schemes here: http://www.foundsf.org/index.php?title=The_Silver_Era,_1860-1870

## Montgomery Street Straight

> The heady prospect of San Francisco’s peninsula becoming the terminus for the transcontinental railroad, coupled with the new flow of capital from the Comstock, injected new life into real-estate speculation, especially schemes affecting the southern waterfront. The rallying cry of real-estate promoters of the ’60s was “Montgomery Street Straight!”

> The possibility of connecting the financial district by a broad avenue directly to the Potrero and Mission Bay opened dizzy possibilities for promoting real estate. The idea was to extend Montgomery Street diagonally as a wide thoroughfare to the southern part of the city, joining Connecticut Street in the Potrero to the Montgomery Street financial district. Hittel reports: “This scheme was carried through the supervisors and passed over the mayor’s veto; commissioners were appointed, and they made an elaborate report, with the estimate of the expense, but the engineer in laying off the map of the work, assumed incorrectly that the blocks intersected were exactly of the size proposed in the original survey. The consequence was that the lines of the new street were not straight, but showed a little offset like a saw-tooth at every crossing. This defeated the enterprise.”

### Update:

I just (2026) found [The Great Diamond Hoax AND Other Stirring Incidents IN THE LIFE OF ASBURY HARPENDING](https://www.gutenberg.org/files/48834/48834-h/48834-h.htm) which has astonishing detail of Ashbury buying up property and trying to make Montgomery Street Straight happen. He didn't quite pulle it off, but he did make New Montgomery!


> The battle cry in the early 60’s was “Montgomery street straight.” The all but universal wish was to run the great street, broadened to a wide avenue, in a direct line to Connecticut street, far to the south. Tremendous efforts were made to carry through this project in a peaceful way. Several times it was near accomplishment, but just as often fell through, owing to some recalcitrant property owner. The main obstacle was the large block of land on Market street where the Palace Hotel now stands. This was owned by the Catholic Church and had been reserved for the construction thereon of a great religious edifice.

> As soon as I got my bearings in San Francisco, I saw at once what a vital question was involved and what a grand opportunity was there to win not alone fortune, but fame. I carefully surveyed the situation from every standpoint and finally hit upon a scheme which would carry out the original design of “Montgomery street straight,” and avoid the opposition hitherto evolved. As what follows forms one of the interesting bits of San Francisco’s history, hitherto untold, and the city’s present status was greatly influenced by my plans, which, however, were only carried out in part, I will give an outline of one of the largest real estate transactions, of a far reaching character, ever conceived and partly completed in the history of San Francisco.

> I was about the first real estate investor, to which business I turned my attention, who realized in a sort of vague way that Market street had a future. I had a shrewd idea that the insistent plan for “Montgomery straight,” on which so many based their hopes, was doomed to disappointment, but as I said in the last chapter, I saw a way out of the dilemma. With this in view, I began to pick up Market street frontage...

> Meanwhile I was quietly buying a solid block of land straight through from Howard street to Market. It was broad enough to allow a wide street to be laid out in a line directly opposite to the ending of Montgomery, and thus change so many backyards into frontages on a fine thoroughfare—an extension of the city’s crowded mart. I wasn’t a prophet or the son of a prophet, but the enterprise looked good. Not only that, but it seemed certain to me that the extension of Montgomery street, once begun, either “straight” or at an angle, would be pushed ahead by the force of public opinion to its proper terminal, the waterfront of the bay.

> This is the veritable story of how I acquired the frontage on Market street which enabled me to open New Montgomery street through my property to Howard. I was certain it would soon be extended to the bay and solve the problem of the 60’s—“Montgomery South.” At the Market street corners of the street I opened, the Palace Hotel and the Merchants’ Bank, two of the finest buildings in San Francisco, now stand.

> I made New Montgomery street, as it stands to-day, a free gift to the city of San Francisco, and it must remain a permanent record of my existence. I may add that I had to scatter numerous shekels among the “boys” before the gift was finally accepted.

## How-to

 draw your fictional road segment
- import Refill as a basemap into [Tangram](https://tangrams.readthedocs.io/en/latest/) and bring your road in as a data source 
- borrow the road styles from [Refill](https://github.com/tangrams/refill-style) and give your fictional road segment Tilezen-style road attributes so Refill will think OMG THIS ACTUALLY A REAL ROAD LET ME DRAW IT:

  - `kind: major_road`
  - `kind_detail:	primary`
  - `min_zoom:	8`
  - `name:	Montgomery St`
  - `sort_rank: 380`
 
- [Tangram Play](https://play.tangram.city/?scene=https://raw.githubusercontent.com/burritojustice/montgomery_street_straight/master/scene.yaml#15.7583/37.7789/-122.4026) helps big time
- disabling the ` buildings` layer makes it look better, though it's fun to keep it a z18 just so you can imagine how many Flatiron type building would have been built in SOMA
- profit!

## Screenshots for posterity

because all online maps eventually die, like tears in rain

![](Market_Folsom.png)
![](folsom_brannan.png)
![](brannan_seventh.png)
![](brannan_16th.png)
![](buildings.png)
