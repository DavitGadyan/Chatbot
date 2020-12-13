## intent:greet
- hi
- hey
- hello
- good morning
- how are you
- hola
- good evening
- whats up
- sup

## intent:insult
- fuck you
- fy
- punk
- piece of shit

## intent:complaint
- I want to file a complaint against your [support team](object_of_complaint).
- I want to file a complaint against your [managment team](object_of_complaint).
- I want your [accounting team](object_of_complaint) pay for my nerves.
- I want to your [sales team](object_of_complaint) to be punished.


## intent:buy_phone_laptop
- I would like to buy a [phone](category)
- I want to buy a [laptop](category)
- Please suggest me a good [laptop](category)
- I wanted to purchase a [phone](category)
- Can you recommend me a [laptop](category)
- give me some recommendations for [mobile phones]{"entity":"category","value":"phone"}
- Can you suggest a [laptop](category)
- I wanna buy a [phone](category)
- Im interested in purchasing a [smartphone]{"entity": "category", "value": "phone"}
- I wanted to buy a [refrigerator](category)
- show me a good [air conditioner](category)
- please recommend me a [washing machine](category)


## intent:latest_news_phones_laptops
- Whats the latest news with [phones](category)
- Can you tell me about the trends regarding [phones](category)
- Whats going in the tech world for [laptops](category)
- Can you show me the trends in [laptops](category)
- Any new releases for [mobiles]{"entity": "category", "value": "phone"}, whats the news
- update me on the [mobile](category) news
- show me the latest news for [mobiles](category)

## intent:goodbye
- goodbye
- bye
- c ya
- c u
- ciao
- talk to you later
- see you around


## lookup:category
data/lookup_tables/category.txt

## lookup:object_of_complaint
data/lookup_tables/object_of_complaint.txt

## synonym:phone
- mobile
- mobiles






