![image](https://user-images.githubusercontent.com/16636086/146166917-0e8e7626-9b81-4072-81db-b5d51a7df75f.png)

# Gilded Rose Specifications

Welcome to the **Gilded Rose team**. As you may know, we are a small inn strategically located in a prestigious city, run by the kind Allison. We also buy and sell high-quality merchandise. Unfortunately, our merchandise is declining in quality as the recommended sale date approaches.

We have an unfinished system to automatically update inventory. This system began to develop my nephew but now he is dedicated to new adventures. Your task is to finish what he started.

## Preliminary description

But first, let's introduce the system:

* All items (`Item`) have a` sellIn` property that denotes the number of days we have to sell it
* All items have a `quality` property that denotes how valuable the item is
* At the end of each day, our system has to decrement both values ​​for each article using the `updateQuality` method

Simple enough, huh? Well now is where it gets interesting, we need to finish the system and meet these requirements:

* Once the recommended sell-by date has passed, 'quality' degrades at twice the speed
* The 'quality' of an item is never negative
* The "Aged Brie" (`Aged brie`) increases in` quality` as it gets old
  * Your `quality` increases by` 1` unit every day
  * after the `sale date` your` quality` increases by `2` units per day
* The 'quality' of an item is never higher than '50'
* The article "Sulfuras" (`Sulfuras`), being a legendary article, does not modify its` date of sale` nor does it degrade in `quality`
* A `Backstage Entry`, such as brie cheese, increases its` quality` as the `sale date` approaches
  * if the concert is 10 days or less, the `quality` is increased by` 2` units
  * if there are 5 days or less, the `quality` is increased by` 3` units
  * after the `sale date` the` quality` drops to `0`

## The requirement

Feel free to make any changes to the `updateQuality` method and add any necessary code, as long as everything continues to work properly. However, ** do not alter the `Item` object or its properties ** as they belong to the goblin in that corner, who in a fit of anger will kill you in one fell swoop because he does not believe in the shared code culture .

## Final notes

To clarify: an article can never have a `quality` higher than` 50`, however the Sulfuras being a legendary article has an immutable quality of `80`.

# Help

List of articles

- +5 Dexterity Vest
- Aged Brie
- Elixir of the Mongoose
- Sulfuras, Hand of Ragnaros
- Backstage passes to a TAFKAL80ETC concert
