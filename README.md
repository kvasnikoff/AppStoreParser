# AppStoreParser

#### Parser for App Store app's average rating, ranking in charts, and user reviews across all regions.

## Usage


1. **Enter a URL in the following format:** `https://apps.apple.com/{any region code}/app/{app_id}`

	`EXAMPLE: https://apps.apple.com/us/app/typeai-ai-keyboard-writer/id6448661220`

	(I mean just copy link from the browser 😉)

 
2. **Type the necessary digit and press 'Enter'**

	```
	1 - Parse basic app info (Country, Number of Ratings, App Store Rating, # in Category) for all App Store regions               
	2 - Parse app reviews from the web version of the App Store  (Country, Date, Username, Rating, Title, Review Text)" for all App Store regions
	3 - Both options"  
	0 - Return to link entering step"
	
	```

## Output Files

After successful parsing, an `.xlsx` and a `.txt` file will be generated for each task. You can find sample output files in the `"Output Examples"` folder:

`typeai-ai-keyboard-writer_info_12-03-2024_15-36-43.txt`

`typeai-ai-keyboard-writer_info_12-03-2024_15-36-43.xlsx`

`typeai-ai-keyboard-writer_reviews_12-03-2024_15-42-21.txt`

`typeai-ai-keyboard-writer_reviews_12-03-2024_15-42-21.xlsx`

