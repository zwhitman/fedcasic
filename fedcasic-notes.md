Abowd's deck
  - 4 things that every

CDO
  - Jeff Chen

Amy O'Hara
  - difficulty of federal agencies attracting the right type of talent


Title of deck

Overarching message: we can only do so much - we need to get the data into the hands of hte public and let them run with their own ideas

1. Open a console, start up an ec2 instance, join that to an s3 bucket and begin importing data.worlds network data


## Let's talk about products
why do we (the bureau) create and disseminate tables?
  - what is the purpose of a dp table?
    + what is it trying to do? What is the intent behind it?
    + well it's predicated on a few assumptions
      1. that our customers will be consuming it either in a report or w/ limited connectivity or hardware
      2. it's trying to provide you with a breadth of topics
        - but why does it include some things but not others?
        - who said average commute should be in there? Why not VA women?
### If they are products, who's the customer? What do these products do?
  - what user research was done in crafting these products?
  - when was that user research done?
  - what feedback do we collect about them?

We get wrapped up in delivery mechanisms: AFF, CBB, Quickfacts. But what about the fundmental question: what do you think about this product?
1. From our analytics we know some products are more popular than others.
  - GCTs are popular. Ok - why?
    + is it their tasteful indentations?
    + NO! It's because people need CONTEXT to understand. Who cares what the population is in one place if it's not in contrast to it's siblings? Far more powerful to understand the distribution than a datum.
      - GCTs are essentially a thematic map without the benefit of area.
      - Also explains GRTs.

## The landscape has shifted.
Compute cycles are a commodity.
  - a general users now have access to hardware that was previously considered a supercomputer.
    + data transacitons are fast. Cheap to pull everything and see what's up

Tooling has changed
  Languages have evolved
  - R/Python/js/julia/sas
  Storage has evolved
  - large data stores

Methods have changed
  - unsupervised learning methods are the new hotness. As a result, everyone is data starved.
    + in their documentation, tensorflow actually points to a census data set as a starter guide.
      = big slap in the face that they 1) point to a 3rd party for the data and 2) include a goddamn cleaning script because OF COURSE THEY NEEDED TO!!!!


## Collection
We collect data w/ our intents already in mind. It drives everything about our approach
  - It drives our frame, methods, and instruments. It's literally the central driver to our collection approach.
  - But if this is true, then how much consideration has been given to our dissemination?
    + How carefully our we considering our end-users during collection - and how does htat inform our collection activities going forward?
    + we create products because we can, but is it what folks want?

## The same data can appear across multiple products
  - We drown our customers in table variations hoping one of htem hits the mark
    + it's a brute force method that was predicated on the presumption that these tables are static and immutable (word choice)?
  - THIS DOES NOT SCALE!!!!
    + if we have somewhere on the order of 1.5 Trillion unique estimates in our holdings, this is truly combinatorial nightmare.


## We need to get smarter
1. Broaden our definition of our end customers when considering data products
2. Leverage user feedback into survey design
  - how will our end users use the products we generate from this collection?
  - does the instrument solve for those needs?
    + can we improve?
3. Dynamic tabulation - the holy grail.
  - and cheat until we can pull it off.

4. Why do we have so many summary levels?

Biggest user asks:
1. Make data easier to discover
  - table names suck...big time. They are either too broad or overly specific.
2. Make data easier to understand
3. Make data easier to access
4. Make data easier to interoperate

Close by pulling up the terminal.
  - show off that i pulled down
