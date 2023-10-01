# Book Giveaway Service

This is a book library website. Users can register and add their owned books, and other registered users can add those books to their wishlist. Process is simple, a user requests a book, and book owner can either accept it or reject it. If the book is accepted, an user who added it to their wishlist gets an email about accepted book's details.

### Books and Gooogle API

Users can add books with Google Books API, for better user experience. They can also delete or edit their books. 

### Swagger
I have created an API for my website and documented it with Swagger.


## Setting up this project on PyCharm

1) Download this project as a zip file.

![Git Download](https://i.ibb.co/DVQXBkq/first.jpg)


2) Unzip and open the project in PyCharm. PyCharm should prompt you to create a new virtual environment and install the dependencies listed in the requirements.txt. Agree and click OK.

![PyCharm](https://img-c.udemycdn.com/redactor/raw/article_lecture/2023-07-26_12-08-47-69e6743627b107a1734fa8832618060b.png)

This should do the trick. However, if you still see any red underlines in your main.py then tell PyCharm to check the virtual environment and dependencies again by going to File -> Reload All from Disk.


## Docker

#### Install my project with Docker
Run the following commands:

```bash
 docker pull 20004/book_library:latest
```

```bash
 docker container run -d -p 5000:5000 20004/book_library:latest
```

You can stop the container with:
```bash
 docker container stop book_library:latest
```

Or check the running images with:
```bash
 docker ps
```
