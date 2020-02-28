# Requirement

You are going to implement an app to search pictures through Flickr API

1. As an user, I am able to search picture base on the keywords I type in
2. I am able to see the result in a list. Using thumbnail size for the list.
   1. The list has pagination feature. It shows 20 pictures per list.
   2. I can route between previous and next list.
3. When I click the picture in the list, I can see a large picture in a modal
4. I can close the Modal when I press ESC key.

### You will use the API that lists below:

api key: `xx`

### Search Photo
Search API Example: https://www.flickr.com/services/rest/?method=flickr.photos.search&text=flower&api_key=<your_api_key>&format=json&nojsoncallback=1

More detail: https://www.flickr.com/services/api/flickr.photos.search.html

### Fetch Photo
Image API: https://farm{farm-id}.staticflickr.com/{server-id}/{id}_{secret}.jpg

Detail: https://www.flickr.com/services/api/misc.urls.html
