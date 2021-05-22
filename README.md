# Sledgehammer Stack
Uses a De Bruijn sequence arrangement of a deck of cards to perform a magic trick

Before the trick:

1) Prearrange your deck in the order listed here: https://docs.google.com/document/d/1KnhTf7GuQRqbklYCb3yejZ6yp79OneqwasQUdjZT0sQ/edit?usp=sharing

2) Go to https://eashang1.github.io/sledgehammer_stack and press 'w' to get to the page that will take input.


Performing the trick:

1) Let the spectator cut the deck (take some portion off the top and move it to the bottom) as many times as they want.

2) Have the spectator pick any five consecutive cards.

3) Now have the spectator fan out the cards so that they can see them all (and you can see the backs). The card closest to you is #5, and the one the furthest from you is #1.

4) Have the spectator remove the cards of the less common color from their hand, then enter the corresponding positions followed by a '.'.

5) Have the spectator remove the cards of a suit of their choice from their hand (so that it is not empty afer removal), then enter the corresponding positions followed by a '.'.

6) Have a spectator pick one of their remaining cards, then enter the corresponding position (the '.' delimiter at the end is optional).

7) Press "Enter" or hit the "Enter" key and give your laptop to the spectator. Upon clicking the "Tell me my card!" button, the website will output the card.

*If you memorize the sequence from steps 4-6, you can input it all once under the guise of pulling up the website, and then pass the laptop to the spectator

These instructions are better illustrated with an example:

Suppose the spectator picks the hand JS, 7S, 4C, 2C, 3D (this sequence appears at the bottom of the uncut deck). Note that the Jack would be furthest from you when the spectator fans out the cards, so this is #1. In the first step the spectator would remove the red cards, so their hand would become JS, 7S, 4C, 2C. As they removed the card in the fifth position, you would enter '5.'. Next suppose they choose to remove the spades. Their hand would then become 4C, 2C. They removed the cards at the first two positions, so you would enter '12.' (or '21.'). Finally suppose the spectator chooses the 2C. This card is now at the second position, so you would enter '2' (as the delimiter is optional). Your final input would be '5.12.2'. Once you press enter, give the laptop to the spectator, and they press the "Tell me my card!" button, the output will be "The two of Clubs!"
