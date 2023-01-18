


# Mastering Microsoft Dynamics NAV 2016
This is the code repository for [Mastering Microsoft Dynamics NAV 2016](https://www.packtpub.com/application-development/mastering-microsoft-dynamics-nav-2016?utm_source=github&utm_medium=repository&utm_content=9781786464309), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
The goal of this book is to explain Microsoft Dynamics NAV 2016 from the root level and understand the different capabilities of the system. The book will give you a deep understanding of the system, which will help you to improve your activities such as
development, implementation, testing, version control, and maintenance. The book heavily focuses on the methods for improving the performance of the system so as to minimize the cost on one hand and improve the productivity and user experience on the other. The book
mostly covers real-life scenarios and presents solution in simplified manner to engage all kind of readers.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter03.

The code will look like the following:

```
LOCAL AddItem()
CLEARLASTERROR;
IF ExceptionHandle.Try('12345','MyTestItem') THEN
  MESSAGE('Item added Successfully')
ELSE
  MESSAGE('Error Returned Error : %1 - %2',
  GETLASTERRORCODE,GETLASTERRORTEXT);
```
 
 ## Related Products
* [Implementing Microsoft Dynamics NAV 2013](https://www.packtpub.com/application-development/implementing-microsoft-dynamics-nav-2013?utm_source=github&utm_medium=repository&utm_content=9781849686020)

* [Programming Microsoft Dynamics NAV 2013](https://www.packtpub.com/application-development/programming-microsoft-dynamics%C2%AE-nav-2013?utm_source=github&utm_medium=repository&utm_content=9781849686488)

* [Programming Microsoft Dynamics™ NAV 2015](https://www.packtpub.com/big-data-and-business-intelligence/programming-microsoft-dynamics%E2%84%A2-nav-2015?utm_source=github&utm_medium=repository&utm_content=9781784394202)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
 
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781786464309">https://packt.link/free-ebook/9781786464309 </a> </p>