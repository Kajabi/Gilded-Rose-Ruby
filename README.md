# Gilded Rose Kata in Ruby

Hi and welcome to team Gilded Rose. As you know, we are a small inn with a prime location in a prominent city run by a friendly innkeeper named Allison. We also buy and sell only the finest goods. Unfortunately, our goods are constantly degrading in quality as they approach their sell by date. We have a system in place that updates our inventory for us. It was developed by a no-nonsense type named Leeroy, who has moved on to new adventures. Your task is to add the new feature to our system so that we can begin selling a new category of items.

### Our Current System

- All items have a `days_remaining` value which denotes the number of days we have to sell the item

- All items have a `quality` value which denotes how valuable the item is

- At the end of each day our system lowers both values for every item

#### Pretty simple, right? Well this is where it gets interesting:

- Once the sell by date has passed, Quality degrades twice as fast

- The Quality of an item is never negative

- "Aged" items actually increases in Quality the older they get

- The Quality of an item is never more than 50, unless "Legendary"

- "Legendary" items never have to be sold or decrease in Quality. They never change.

- "Backstage passes", like "Aged" items, increases in Quality as it's Days Remaining value approaches zero; Quality increases by 2 when there are 10 days or less and by 3 when there are 5 days or less but Quality drops to 0 after the concert

### Our Task

We have recently signed a supplier of conjured items. This requires an update to our system:

- "Conjured" items degrade in Quality twice as fast as normal items

The specs are always the source of truth in this scenario. You'll start out with some failing and some passing specs.

Feel free to make any changes to the `tick` method and add any new code as long as everything still works correctly.

## Requirements

- Make all specs pass
- Refactor giant if statements into something cleaner
- Show us what it's like to to work with you
- This is a chance to show some creativity and how you like to go about solving problems
- It's also an opportunity to show how you work with a team as you are welcome to ask questions and talk through ideas
