# practicum
AB project description.

**Description:**

    The company has acquired a subscription book reader service and needs the first cursory analysis of the database. There are a few questions below that have to be answered within the research.
    
**Data description:**
**Table books**
    - book_id — id of the book;
    - author_id — the author's ID;
    - title — the title of the book;
    - num_pages — number of pages;
    - publication_date — date of publication of the book;
    - publisher_id — id of the publisher.

**The authors table**
    - author_id — the author's ID;
    - author — the author's name.

**Publishers table**
    - publisher_id — id of the publisher;
    - publisher — the name of the publisher;

**Ratings table**
    - rating_id — rating ID;
    - book_id — id of the book;
    - username — the name of the user who left the rating;
    - rating — rating of the book.

**Reviews table**
    - review_id — review ID;
    - book_id — id of the book;
    - username — the name of the review author;
    - text — the text of the review.

**Project Stack:**
PostgreSQL

**Knowledge and skills used:**
PostgreSQL

**Key conclusion/result of the project:** 
Based on the results of our review, we can conclude that the database stores information about 1000 books, their authors (636). The books have been published by 340 publishers, we also have data on 2,793 reviews and 6,456 book ratings.

We did some calculations and determined that:

- since 2000, 819 books and brochures have been published.;
- the book "Twilight" has the largest number of reviews - 7 and an average rating of 3.66;
- the largest number of books with more than 50 pages (42) has been published by Penguin Books;
- authors with the highest average book rating(4.29): J.K. Rowling/Mary GrandPre;
- users who have posted more than 50 ratings write 24 reviews (average).

**Project status:**
The project has been successfully completed on time.

