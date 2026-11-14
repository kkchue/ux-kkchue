# Right Order, Wrong Location: My Chipotle App Mistake

I was home in Oroville and my girlfriend and I wanted to get Chipotle. We drove over and were already parked outside of the restaurant, but instead of going inside and ordering, we decided to order through the Chipotle app. We figured we could place the order on my phone, wait a few minutes, and then walk inside when it was ready.

Instead of making our orders again from scratch, I went through my previous orders and selected one we had gotten before. This made ordering faster because I didn't have to go through and choose everything again. I added the food to my bag and continued through the checkout process. I was mostly focused on making sure our food was correct, and I didn't notice that the order was set to a Chipotle location in Chico.

![My Chipotle order before checkout](assets/Chipotle%20Screenshot%20111326.jpg)

*Figure 1: The bag screen while reviewing our order. Most of the screen is focused on the food in the order, and the pickup location isn't shown here.*

I finished the order and paid without realizing anything was wrong. Since I was literally sitting outside of a Chipotle in Oroville, I wasn't thinking about the possibility that the order I selected from my previous orders would end up being placed at the Chico location.

It wasn't until after I had already paid that I realized what happened. The app showed me the address of the restaurant and asked if I wanted directions. Instead of showing the Oroville address I was expecting, it showed the location in Chico. That was when I realized I had just paid for food that was going to be made about 20 miles away from where I was sitting.

At that point, our food was already being prepared. We had selected the quickest pickup time, which was only about five minutes away, because we thought we were already sitting outside the correct restaurant. I tried to cancel the order, but I wasn't able to. Rather than losing the money and our food, we ended up driving all the way from Oroville to Chico to pick up an order we had placed while sitting outside of the Oroville Chipotle.

## How Could This Have Been Prevented?

Looking back, this was an issue with **error prevention**. Error prevention is when a design helps someone catch a possible mistake before they complete an action that might be difficult to undo. Choosing one of my previous orders made the ordering process faster, which was useful, but I didn't realize that I was about to place the order at a restaurant in another city.

Something as simple as a warning that I was far away from the selected restaurant could have made me stop and check the location before paying.

When I went back to the Chipotle app to recreate this experience for this journal, I noticed that the app now does exactly that.

![Chipotle warning about being far from the selected location](assets/Chipotle%20Screenshot%20111326%202.jpg)

*Figure 2: The current checkout screen warns me that I seem far away from the selected Chico location before I pay.*

The app now displays a warning saying, "You seem far away from this location." It also shows the full address of the selected restaurant directly underneath the warning. This is much better **error prevention** because it gives me a chance to realize something might be wrong before I actually place the order. If I had seen a warning like this during my original experience, I probably would have noticed that Chico was selected and changed it to Oroville.

## Choosing a Different Location

I also checked what happens when I choose to change the restaurant.

![Chipotle location selection screen](assets/Chipotle%20Screenshot%20111326%203.jpg)

*Figure 3: The location-selection screen shows the nearby Oroville restaurant along with other locations and their distances.*

The current app makes the distance between the restaurants pretty obvious. The Oroville restaurant shows up under "What's Nearby" at less than a mile away, while the Chico location I had originally ordered from is about 20 miles away.

Having the distance displayed next to each restaurant gives me useful **feedback**. Feedback is the information an interface gives you in response to your actions so you can understand what is happening. In this case, seeing how far away each restaurant is makes it easier for me to tell whether I'm selecting the location I actually want.

## Looking Back

I don't think Chipotle should automatically change the restaurant every time it detects that I'm somewhere else. There could be situations where someone intentionally wants to order from a restaurant that isn't close to them, such as ordering food for someone in another city. Automatically changing the restaurant could solve one problem while creating another.

Instead, I think the warning that the app currently uses is a good solution. It doesn't prevent me from ordering from a faraway restaurant if that's what I actually want to do, but it makes me stop and double-check my choice.

Reordering something I had gotten before was supposed to save me time, but that convenience ended up costing me a drive from Oroville to Chico. If the warning that's in the app now had been there at the time, the whole situation probably could have been avoided.
