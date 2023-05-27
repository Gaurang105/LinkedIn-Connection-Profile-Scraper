
# LinkedIn Profile Scraper

This is a Python script for scraping LinkedIn profile links, profile names, and checking for premium subscriptions.

The script uses Selenium for web scraping. It navigates to each profile link from an Excel file, scrolls to the bottom of the page, extracts the profile name, and checks if the profile is a LinkedIn premium subscriber.




## Output

The script will create an Excel file named profile_info.xlsx with the scraped profile links, names, and premium subscription statuses.

Each row in the Excel file represents one LinkedIn profile, with the following columns:

- Profile Links: The URL of the LinkedIn profile.
- Profile Name: The name of the LinkedIn profile.
- Premium: Whether the profile is a LinkedIn premium subscriber ('Yes' or 'No').
## Future Work

Can be added more things like how many connections a user has, companies where the user has worked at, educations details etc. 
