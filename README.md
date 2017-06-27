# Instafetch
A python package to fetch public data from Instagram.

## Installation
``` bash
$ pip install instafetch
``` 

## Usage
+ **Search Users:**
    ``` python
    from instafetch import Instafetch
    
    I = Instafetch()
    users  = I.users(<keyword>)
    ```

+ **Get user details:**
    ``` python
    I = Instafetch()
    user_detail = I.user(<username>)
    ```
+ **Fetch Hashtags data:**
    ``` python
    I  = Instafetch()
    I.explore(<Hashtag>, page=<no. of pages>) #number of pages to fetch
    
    top_posts = I.top_posts
    all_posts = I.all_posts
    ```
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b <new-feature>`
3. Commit your changes: `git commit -am 'New Feature added'`
4. Push to the branch: `git push origin <new-feature>`
5. Submit a pull request :D

## Contributors

+ [Kanav Arora](http://github.com/arorakanav11)
+ [Paras Sharmaa](http://github.com/parassharmaa)

## Things to do:
+ Write Tests
+ Add more endpoints
+ Modify return data

## License
[MIT](https://github.com/Parassharmaa/instafetch-python/blob/master/LICENSE)
