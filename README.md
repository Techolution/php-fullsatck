# Coding Challenge

# Why a take-home interview?

In-person coding interviews can be stressful and can hide some people's full potential. A take-home gives you a chance work in a less stressful environment and showcase your talent.

We want you to be at your best and most comfortable, just as you would be in our office environment

# Requirements

Given the json create an application with one screen that turns it into a list. 
```python
{
  "batch_id": 0,
  "offers": [
    {
      "offer_id": "40408",
      "name": "Buy 2: Select TRISCUIT Crackers",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/6840/67561_1535141624.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "39271",
      "name": "Tide Liquid Detergent",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/4902/56910_1527084051.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "38744",
      "name": "Dawn",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/1795/10751_1439567381",
      "cash_back": 0.5
    },
    {
      "offer_id": "41050",
      "name": "Dove Shower Foam or Dove Men+Care Foaming Body Wash",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7754/68780_1536591544.jpg",
      "cash_back": 2.5
    },
    {
      "offer_id": "40655",
      "name": "Tostitos Hint of Roasted Garlic",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7600/67648_1534338838.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "40433",
      "name": "TRISCUIT Organic",
      "image_url": "https://checkout51-production.s3-us-west-2.amazonaws.com/1534361237_16814358_ADMIN_UPLOAD67606-list.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "39287",
      "name": "Mackie's of Scotland Potato Crisps",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/6923/62734_1526399532.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "39604",
      "name": "Sanissimo Oven-Baked Corn Crackers",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7348/66109_1531420737.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "34656",
      "name": "Vector Protein Bars",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/4130/38880_1496766889.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "41104",
      "name": "Pure Protein Chewy Oat Bars",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/6693/67452_1534514057.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "35990",
      "name": "Manitoba Harvest Hemp Hearts",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/5857/54523_1513026815.jpg",
      "cash_back": 1.5
    },
    {
      "offer_id": "40809",
      "name": "Hellmann's made with Avocado oil",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7414/67754_1534444028.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "40854",
      "name": "Hellmann's Extra Creamy",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7414/68416_1536067855.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "36259",
      "name": "Casbah Products",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/6508/59925_1521222040.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "34655",
      "name": "Vector Meal Replacement",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/5987/56389_1516908117.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "40204",
      "name": "Chosen Foods Vegan Mayo",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7527/67175_1533222675.jpg",
      "cash_back": 3.0
    },
    {
      "offer_id": "34393",
      "name": "Grimm's Naturally Fermented Foods",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/6102/56393_1516639373.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "39939",
      "name": "Select Swanson Soup Products",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/5968/66691_1532455333.jpg",
      "cash_back": 0.75
    },
    {
      "offer_id": "39992",
      "name": "Buy 3: Campbell's Broth",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7466/66793_1533061144.jpg",
      "cash_back": 2.0
    },
    {
      "offer_id": "38426",
      "name": "Pure Via sweeteners",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/5741/53509_1511302596.jpg",
      "cash_back": 2.0
    },
    {
      "offer_id": "40789",
      "name": "Stubb's BBQ Sauce",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7690/68293_1536024660.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "38447",
      "name": "International Collection Oils",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7105/63947_1528312196.jpg",
      "cash_back": 1.0
    },
    {
      "offer_id": "40200",
      "name": "Chosen Foods Avocado Oil Dressings",
      "image_url": "https://d3bx4ud3idzsqf.cloudfront.net/public/production/7527/67168_1533221549.jpg",
      "cash_back": 3.0
    }
    ]
}
```

The file contains a list of offers and their attributes. Each row in the list must contain the offer name, its image and the cashback value in dollars. 

Feel free to build it in any way you want using any framework, architecture and tools at your disposal. Create a way for a user to sort the offers by name or cash back.

Create a search for the records and optimize the search by using backend and front end.

This is a relatively simple app, however we are looking for more than just the task to be completed. We take the craftmanship of the code seriously, and want to see evidence that you do as well.  We are looking for software that is well structured, concise and testable.

PHP should be the backend, feel free to add Angular/React/Vue/Drupal/Wordpress if you feel its fits. Our minimal expectation is that there are some server side components in your solution.  The front end can be rendered on the client side or server side, its entirely up to you, submissions that run in a docker container will be heavily favored.



