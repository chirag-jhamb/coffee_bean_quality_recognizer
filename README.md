Building a coffee bean classifier using transfer learning. This was last attempted in 2017 and with new tranfer learning methods the accuracy can be improved to make the model feasible. Library used: fasai

### Project overview
An attempt at a small-scale, cheap optical sorter for green coffee beans. It would use image classifiers (“artificial intelligence”) and work on a Raspberry Pi 3 computer or similar.

Coffee lovers know that the quality of coffee depends a lot on the final sorting of coffee beans – 80% of beans are sorted by hand (and these are of course low-wage jobs), the rest by industrial machines called “optical sorters”. All existing optical sorters are way too costly for small-scale coffee farmers, likewise for small roasters (or community homes like The Reef :slight_smile:) interested in producing own high-quality coffee.

This changes with an idea I developed a few months ago to some maturity: the open source optical coffee sorter. I wrote down a more technical plan in the last section below, see there for details incl. proposed computing hardware and software. The software part includes artificial intelligence for “better than perfect” bean sorting.

In my estimate, a price of <300 USD is realistic, compared to at least 10,000 USD for Chinese-made industrial machines. Roasters in Europe indicated to me that such a machine is interesting to them as well, so there is an initial “higher end” market to serve, for example by a pre-order type of crowdfunding. Later, you’d go into mass-producing the machine and selling it to small coffee farmers who now have to sort by hand. (There is a woman empowerment aspect here, since most of the low-wage manual coffee sorting is currently done by women.)

And if you’re not into coffee, you can also adapt the concept to sort all kinds of local agricultural products: nuts, dates, fruits, spices, whatever. (Even rice and other grains is usually going through an optical sorter before it hits the market.)

Economic rationale

The optical coffee sorter is not a direct competitor to existing industrial solutions. Rather, it attempts to enable a different economic model. Its use case is a single producer or a small cluster of local producers (for example, < 10 coffee farmers in a village in Nepal) who wish to produce high quality, premium priced “single origin coffee”.

#### Source: https://edgeryders.eu/t/open-source-coffee-sorter-project/7122
#### Data source: https://github.com/edgeryders/coffee-cobra/tree/master/training-data-jpg