# Tenue

You already own the outfit. Tenue is a phone closet with a dress-up feel: photograph your clothes, then each morning swipe through a few looks chosen for the weather, your style, and what you wore this week. Shuffle if nothing feels right. Favorite the ones that do. It remembers, and tomorrow's suggestions move closer to the way you actually dress.

Work top to bottom. Finish a milestone before starting the next one. Check a box when it works on your phone.

## 0. Get the app running

- [x] Create the GitHub repo
- [x] Write the product description
- [ ] Create the Expo app in this repo on SDK 57, so Expo Go on a real iPhone can open it
- [ ] Install Expo Go on your iPhone
- [ ] Sign in to a free Expo account on the computer and on the phone
- [ ] Start the app and see the starter screen on your phone
- [ ] Start `LEARNING_LOG.md` and add a short note at the end of every milestone

## 1. A closet screen with fake clothes

- [ ] Make a phone screen titled Tenue
- [ ] Show a handful of fake clothing items with a name, a type, and a color
- [ ] Show one fake outfit built only from those items
- [ ] Add a style control: random, streetwear, casual, formal
- [ ] Add Pick, Shuffle, and a one-tap rush action, with no behavior behind them yet

## 2. Photograph one item and keep it

- [ ] Open the camera and take a photo of one garment
- [ ] Remove the background
- [ ] Save the photo on the phone
- [ ] Show the saved item again after the app is closed and reopened
- [ ] Keep the rule: one photo is one item

## 3. Tag the item with a vision model

- [ ] Open a free model account and create an API key
- [ ] Put the key in a small local server, never in the phone app
- [ ] Send one photo to the model
- [ ] Require the answer as JSON with type, color, warmth, and formality
- [ ] Save those tags with the item and show them on the screen

## 4. Know the weather

- [ ] Save the city once
- [ ] Fetch today's weather from Open-Meteo
- [ ] Show the weather on the morning screen

## 5. Pick real outfits

- [ ] Send the saved wardrobe, the weather, and the chosen style
- [ ] Get back 3 to 5 outfits
- [ ] Every piece must be an item saved in the wardrobe
- [ ] Swipe through the options
- [ ] Shuffle asks for a new set
- [ ] Rush mode returns one outfit in one tap

## 6. Remember what you wore

- [ ] Log the outfit you actually wore
- [ ] Choose a weekly limit, once or twice
- [ ] Hide a logged outfit until that limit allows it again
- [ ] Reset the history at the start of each week

## 7. Learn the way you dress

- [ ] Favorite an outfit
- [ ] Keep a short style profile built from favorites and from outfits you wore
- [ ] Include that profile the next time outfits are requested
- [ ] Leave the model itself unchanged. The memory is what gets updated

## 8. Make it feel like getting dressed

- [ ] Show an outfit as slots: top, bottom, shoes, jacket, and the other pieces
- [ ] Give the clothes a slightly pixel look, short of full pixel art
- [ ] Animate a photo turning into an item and landing in the closet
- [ ] Animate the swipe and the shuffle

## 9. Notice a missing piece

- [ ] Keep this separate from the outfit picker
- [ ] Allow a note such as "a scarf would finish this"
- [ ] Do not link to a store

## 10. Test the rules

- [ ] Build 30 days of fake weather
- [ ] Check that cold or snowy days never suggest shorts
- [ ] Check that an outfit never repeats more often than the weekly limit
- [ ] Check that every suggested piece is a real saved item

## 11. Be able to explain it

- [ ] Record a short demo
- [ ] Rewrite this README so a stranger can understand what you built
- [ ] Write the interview explanation: how the model is called, how JSON is required, how the key stays off the phone, and how the tests catch a bad outfit

## Later

Not part of the learning build. Start these only after milestone 11.

- [ ] An account per person, each with an empty closet
- [ ] Several garments in one photo
- [ ] A photo of the real closet as the backdrop
- [ ] A built-in starter closet
- [ ] Links to buy a missing piece
- [ ] A cloud database
- [ ] An App Store release, which needs the paid Apple Developer account
