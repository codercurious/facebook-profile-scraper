## How it works

The Facebook profile scraper is an Apify actor designed to extract information about profiles and pages. You can get all available information such as Name, bio, work history, Emails, phone numbers, Skype, Twitter, Linkedin, Instagram profiles, Gender, Birth date, Location etc.

## Main Features

**Proxy Support:** To enhance reliability and avoid rate limiting issues, the actor supports proxy usage. You can provide a list of proxies that will be rotated automatically to ensure smooth and uninterrupted scraping.

**Cookies Support:** To view most of the Facebook profiles, you need to be logged in. This scraper allows you to input cookies to use your Facebook account session information to scrape profiles on behalf of you

**Scalability and Performance:** The actor is built on the Apify platform, which ensures scalability and excellent performance. It utilizes parallel processing to scrape multiple pages simultaneously, maximizing efficiency and minimizing the overall scraping time. 

**Safety of facebook account** When using cookies for scraping, Scraper uses fixed proxy, disables parallel scraping and enables random delays to ensure the safety of your Facebook account. The cookies will be used only for profiles which require you to login to view them

**Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. This allows for seamless integration with other tools and platforms for further analysis and utilization.

**Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the actor has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

## Sample data

Here is the sample json output of this actor:

```json
{
	"bio": {
		"delight_ranges": [],
		"image_ranges": [],
		"inline_style_ranges": [],
		"aggregated_ranges": [],
		"ranges": [],
		"color_ranges": [],
		"text": "Aurora coffee shop offering locally roasted coffee, fresh house made coffee syrups and food options. "
	},
	"influencer_category": {
		"text": "Page · Coffee shop",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/yV/r/zZaEKuhZ6qh.png"
	},
	"address": {
		"text": "15600 E. Alameda Parkway, Aurora, CO, United States, Colorado",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/y3/r/6AitI08mYhY.png",
		"id": "NjQyMTgzOTU5MjA4MTA3Omh0dHBzXGEvL21hcHMuZ29vZ2xlLmNvbS9tYXBzP3E9MTU2MDArRS4rQWxhbWVkYStQYXJrd2F5JTJDK0F1cm9yYSUyQytDTyUyQytVbml0ZWQrU3RhdGVzJTJDK0NvbG9yYWRvJmhsPWVuOjo6Og==",
		"url": "https://l.facebook.com/l.php?u=https%3A%2F%2Fmaps.google.com%2Fmaps%3Fq%3D15600%2BE.%2BAlameda%2BParkway%252C%2BAurora%252C%2BCO%252C%2BUnited%2BStates%252C%2BColorado%26hl%3Den&h=AT2MpPP_E7ZyxyN5oUfd1znBh6OSeLPbkheTqru6GCwUBX-wsQvn2VNji6pNu-O8DYTcBWUvzMoISjq4TVtDHzLFIH-kbi1BWnN7IuTrHfAtIhrb4PVoTdTAFyBB8XiduT2KJnDs99aw4cAv-q4Dn3KRwA&s=1",
		"external_url": "https://maps.google.com/maps?q=15600+E.+Alameda+Parkway%2C+Aurora%2C+CO%2C+United+States%2C+Colorado&hl=en"
	},
	"profile_phone": {
		"text": "+1 720-830-5166",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/y9/r/7i_YTpprMRX.png"
	},
	"profile_email": {
		"text": "smiller@millyscommunitycafe.com",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/yI/r/szoH_eR2qR7.png"
	},
	"website": {
		"text": "millyscommunitycafe.com",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/y3/r/0ho4nG26KLt.png",
		"id": "NjQyMTgzOTU5MjA4MTA3Omh0dHBzXGEvL2wuZmFjZWJvb2suY29tL2wucGhwP3U9aHR0cCUzQSUyRiUyRnd3dy5taWxseXNjb21tdW5pdHljYWZlLmNvbSUyRiZoPUFUMVM4bXdtM2RhVkhFb2owNVNnTy11MmlWekNoSk9iZGZEei1kQmsyMTdyUDRKLUNSaXdUd0xxZ3VLZEFZWVAteEFmNTR0eGNHekpuYW5SV3pMWHN2V29MbHpDUnEzNXZKOWE1R1owVE5yQ1JpUVdYa1hBME5LaklmTTNEVjRWYVlYUUJpYVN4ZVdYcGgtay1CTEJ0YkItdTRVJnM9MTo6Ojo=",
		"url": "https://l.facebook.com/l.php?u=http%3A%2F%2Fwww.millyscommunitycafe.com%2F&h=AT3mb3UoJ_lGGsZ76ejDDVYMEr4DN9z7LgpS8FP3PSqIYJ7Hp1CHIVGz-fSIYMoFF_CfUWmOwiXrVyfwMURt_oAdLEzRXpOm1uA7C2srYC7sUwhDISCI_miOl_dQK51nI80OyYJOqPES_eGB24jcmgYxeA&s=1",
		"external_url": "https://l.facebook.com/l.php?u=http%3A%2F%2Fwww.millyscommunitycafe.com%2F&h=AT1S8mwm3daVHEoj05SgO-u2iVzChJObdfDz-dBk217rP4J-CRiwTwLqguKdAYYP-xAf54txcGzJnanRWzLXsvWoLlzCRq35vJ9a5GZ0TNrCRiQWXkXA0NKjIfM3DV4VaYXQBiaSxeWXph-k-BLBtbB-u4U&s=1"
	},
	"business_hours": {
		"text": "Closed now",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/yP/r/RSpVEGhhd5g.png"
	},
	"business_services": {
		"text": "Dine in · Outdoor seating · In-store collection",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/A7e-6vUUTAa.png"
	},
	"business_price": {
		"text": "Price range · £",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/yz/r/dzyr74nFgzx.png"
	},
	"rating": {
		"text": "Rating · 4.4 (94 reviews)",
		"icon": "https://static.xx.fbcdn.net/rsrc.php/v3/yB/r/2OpWWH3SYgH.png"
	},
	"wifi": "Offers free Wi-Fi with purchase",
	"category": "Coffee shop",
	"Address": "15600 E. Alameda Parkway, Aurora, CO, United States, 80017",
	"Mobile": "+1 720-830-5166",
	"Email": "smiller@millyscommunitycafe.com",
	"Website": "http://www.millyscommunitycafe.com/",
	"ratings": "Rating · 4.4 (94 reviews)",
	"Hours": "Closed now",
	"Price": "Price range · £",
	"Services": "Dine in · Outdoor seating · In-store collection",
	"url": "https://www.facebook.com/millyscommunitycafe",
	"bioText": "Aurora coffee shop offering locally roasted coffee, fresh house made coffee syrups and food options. "
}
```

## Use cases

Here are some common use cases for Facebook profile data:

1. **Lead Generation:** Extracting profile details allows businesses to identify potential leads and prospects. By analyzing member profiles, businesses can identify individuals who are likely to be interested in their products or services, enabling targeted lead generation efforts.

2. **Influencer Marketing:** By analyzing member profiles, businesses can identify individuals with a significant following and high engagement rates, enabling them to establish partnerships for influencer marketing campaigns.

3. **Personalised cold outreach email content:** With the help of complete profile details you can write personalised emails that results in high open rate. You can pass the profile details to AI to generate personalized emails in bulk. 
