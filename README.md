# Lorenzo Tv blog RESTAPI DOC

### Welcome to LorenzoTv Blog API documentation, this comprehensive guide will walk you through the various endpoints, functionalities, and best practices for integrating and utilizing the API.

***

## All blog post endpoint

Endpoint: /all_post.php

Method: GET

URL: https://labaikaschools.com/api/all/all_post.php?api_key={API_KEY}

Description: This endpoint allows you to get all the blog post using the GET method. By making a GET request to this endpoint.

>> success response sample (JSON): 

```
{
    "error": false,
    "blog-post": [
        {
            "id": 2,
            "title": "second post",
            "blog_category_id": 2,
            "blog_content": "blog post",
            "search_keyword": "finace, money",
            "thumbnail": "thumbnail.png",
            "author": "author",
            "date_created": "2023-06-14",
            "blog category": "Finance"
        },
        {
            "id": 5,
            "title": "title",
            "blog_category_id": 2,
            "blog_content": "blog_content",
            "search_keyword": "search_keyword",
            "thumbnail": "9357824.png",
            "author": "author",
            "date_created": "June-6th-2023",
            "blog category": "Finance"
        },
        {
            "id": 6,
            "title": "title",
            "blog_category_id": 2,
            "blog_content": "blog_content",
            "search_keyword": "search_keyword",
            "thumbnail": "433046energy1.png",
            "author": "author",
            "date_created": "June-6th-2023",
            "blog category": "Finance"
        },
        {
            "id": 7,
            "title": "title",
            "blog_category_id": 2,
            "blog_content": "blog_content",
            "search_keyword": "search_keyword",
            "thumbnail": "618046energy1.png",
            "author": "author",
            "date_created": "June-6th-2023",
            "blog category": "Finance"
        },
        {
            "id": 8,
            "title": "title",
            "blog_category_id": 2,
            "blog_content": "blog_content",
            "search_keyword": "search_keyword",
            "thumbnail": "873943energy5.png",
            "author": "author",
            "date_created": "June-6th-2023",
            "blog category": "Finance"
        }
    ],
    "message": "blog post returned successfully"
}


```

***

## Action endpoint


Description: This endpoint allows you to get all the blog post using the GET method. By making a GET request to this endpoint.

Method: GET

Endpoint: /action

URL:

**delete** : https://labaikaschools.com/api/action/delete.php?api_key={API_KEY}&{id}

>> success response sample (JSON): 

````

{
    "error":false,
    "message":"Blog post deleted successfully"
}

```

