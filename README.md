## Niche research tool


A simple app that enables anyone who wants to enter in the business of eCommerce to make a research of a specific niche in just a few clicks.

In order to use the application, you must have an account. After register and login, the user must provide the keywords for the niche that he wants to research. Those keywords will be fed to the algorithm for the following purposes:

1. The algorithm will scrape the first page of Amazon results for that product and extract the following information:

- How many products are in that niche,
- Average price of products in the page,
- A list of all the products that are ranked in the first page, with the following information:
  - Full name of the product,
  - Price,
  - Rating,
  - Number of ratings,
  - Seller&#39;s rank -\&gt; an indicator for checking how well the products are selling
  - Average fee for the product (how much do you have to pay to Amazon)

2. The algorithm will scrape the first page of eBay results for that product and extract the following information:
  - How many products are in that niche,
  - Average price of products in the page,
  - A list of all the products that are ranked in the first page, with the following information:
    - Full name of the product,
    - Price,
    - Rating,
    - Number of ratings,
    - State: used/new
    - Average fee for the product (how much do you have to pay to eBay)
    - Shipping price (because on eBay there is no &quot;prime&quot; service to exclude the shipping price)
    - Items sold
    - Monthly revenue/income

3. The algorithm will scrap the first page of Alibaba result for that product and extract the following information:
  - A list of all the products that are ranked in the first page, with the following information:
    - Full name of the product,
    - Price,
    - Rating,
    - Number of ratings,
    - Seller&#39;s information: membership status (gold/diamond/platinum -\&gt; indicator of credibility), verified or not, certifications etc.
    - Seller&#39;s time on platform: experience and credibility indicator
    - Trader&#39;s assurance available or not (it&#39;s a free service for the seller and it puts your money in an escrow until you give the confirmation that the product was received and it is in good condition)
    - Items sold
    - MOQ (minimum order quantity)

4. The algorithm will use Google AdWords API to retrieve estimated keyword traffic for the product you want to sell
  - This API shows you the average daily searches on google for that keyword
  - It also gives you relevant information about the price for advertisement for the keywords (if many people advertise websites on a specific keyword the price will go up, so you will know if you have competition based on the price of the advertisement google is asking you to pay)
  - The API provides a list of related keywords for the provided ones so that you might advertise your product under, more profitable, keywords.

After gathering all that&#39;s needed, depending on the user membership plan (free or premium), the information will be displayed such that a user can easily deduct if the niche is profitable or not, and see alternative keywords for the niche in which he wants to sell.
