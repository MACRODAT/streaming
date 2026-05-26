
	Path: D:\ai\streaming
	Read index.html

	# Context
	we Created a landing page  / small website after clicking on a facebook ad.
	Assume user has very minimal attention span and Ensure you capture and convey as much detail.
	First to be seen is the best offer package: Netflix + directv + fubo tv + ViX for 40 dollars / year.
	Add quick option to buy and option to message in whatsapp.
	Next, after scrolling, add testimonials from previous buyers.
	Also add other offers (two more) and possibility to craft own offer (services + duration (1 month, 3 months, 6 months, one year)).
	add another contact / message button.
	Ensure design looks professional.
	Theming: use Netflix theme and fonts. Very important.
	Ensure the design is mobile friendly.
	Do not create a lot of content. Ensure everything is minimal but conveys the message.
	Add transitions and animations.

	# Task
	- fix the scrolling / page carousel behavior, so that scrolling up and down anywhere triggers the previous / next component, EXCEPT for custom bundle which looks like another page / full screen app with close (return) button with slightly different background => access there with animation! . This should include the area of the components, where scrolling aggressively should bring the prev / next component in the page.
	- Fix the logos in the build bundle items below build your arsenal (width of the icon should be dependent on the service icon, without stretching or wrapping).
	- when switching between 6 months / 1 year, show animations (beautiful) in the prices list
	- When selecting one item in the bundler, the next is sold with reduction (it is already done). Ensure you update the prices of the items depending on how much they would cost (in  difference) based on the selected bundle.
	- When selecting items from the:
    	- classic bundle: Netflix, ViX, DirectV, Fubo Tv, 
    	- Family Night: Disney, Apple TV, hulu
    	- Sports MAD: ESPN, DIRECTV, Fubo
    	- ensure you say to the user that this is the classic / movies / sports bundle with a pretty animation (show even the trailer for the bundle, in smaller preview)
  	- Fix the header (fixed) so that there is this beautiful spotlight in RED/ORANGE that changes sometimes color with animations and which adds a bit to the opacity so the header feels "higher" that the content.
  	- Fix the number for whatsapp: +212698179490
  	- Do not modify the intents and features and theme of the app
  	- Theme: Netflix inspired!


	- In the bundles, replace names with their logos.
	- for each bundle, Fix the canvas in the form of four triangles (if there are four products or up to the number of products) that make rectangle that fits with backgrounds of the products themes and their logos. Add a plus in between to show they are bundled together.
	- Modify pricing and products to this matrix:
		-- name || price for 6 months || price for 12 months 
		-- directv || 45 || 65
		-- Hulu || 44 || 64
		-- Youtube Premium || 39 || 59
		-- Espn || 30 || 46
		-- Apple TV || 34 || 51
		-- Disney || 30 || 47
		-- Amazon prime || 35 || 52
		-- Spotify || 35 || 51
		-- Sling TV || 44 || 62
		-- Vix || 40 || 57
		-- Peacoch Premium || 30 || 47
		-- Netflix || 10 || 18
	Each product added to the first is discounted by 25%
	Third discounted by 35%
	Fourth discounted by 50%
	Rest discounted by 65%

	=> ensure scrolling in products in bundler does not trigger the page scrolling behavior.
	=> ensure (vix + netflix + directv + fubo tv) account to 62 dollars per year. Ensure second and third and fourth choices are discounted more and reduce all products price to reach that goal.
	=> Add regular customer check that reduces total check by 20%.
	=> the products mosaic canvas should span over the entire component panel, including text and buttons below. Replace the text with the product's logo. Replace solid colors with images (ESPN=>Stadium for example). The text below has a blur background.
	=> Ensure you get the background for the mosaic canvas from folder (image: fubo_banner.jpg / png)
	=> remove static hardcoded images and put them outside html file

	- Add possibility to ask for another product (in the custom): You can't see it here? We probably have it too!