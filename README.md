# Test exam on iOS developer position 

## Requirements.
- iOS application fetches GitHub contributors list.
- API to fetch https://api.github.com/repos/videolan/vlc/contributors
- Main controller UI is shown below:
![Alt Text]()
details UI in DetailsUI.png, animation in Animation.gif.
- Programming languages are Swift or Object C. Swift is preffered.
. 

## What should to be done

Please model the required database relations and create API Endpoints described below.
The code should be covered with tests (rspec).


### Endpoint 1

 for a specific Publisher it should return the list of shops selling at least one book of that publisher. Shops should be ordered by the number of books sold. Each shop should include the list of Publisher’s books that are currently in stock. 

Example response:
```json
{ 
  shops:[
   {
     “id”: 1,
     “name”: “Amazon”,
     “books_sold_count”: 10,
     “books_in_stock”: [
       {
         “id”: 2,
         “title”: “Yiddish songs”,
         “copies_in_stock”: 3
       },
       … 
     ]
   },
   … 
 ]
}
```

### Endpoint 2

 For a specific Shop it should mark one or multiple copies of a book as sold.
 

## Comments

Please upload your code to github repository, there is no need in ZIP archives or smth, please send us link to you solution pubslihed on  https://github.com .

If you have any questions - please dont hesitate to ask contact who shared this test with you.
