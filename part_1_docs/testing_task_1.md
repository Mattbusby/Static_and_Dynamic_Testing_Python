### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
#   below line needs to be double ==
    if card.value = 1:
      return True
#   : needed after else in line below
    else
      return False
   

# typo in line below, should be def, not dif. also missing comma between card1 and card2.
  dif highest_card(self, card1 card2):
#   indentation missing below
  if card1.value > card2.value:
#   should be "card1", not card in line below
    return card
  else:
    return card2
  

# below section all needs indented
def cards_total(self, cards):
# below line should have =0 at the end
  total
  for card in cards:
    total += card.value
# the below line needs total to be converted to a string, and must be outside of the for loop.
    return "You have a total of" + total
  
```
