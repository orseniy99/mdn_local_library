# ****mdn_django_guide****

# ABOUT

Project based on [MDN Django guide](https://developer.mozilla.org/ru/docs/Learn/Server-side). Simple library site on **django**.

> **Live version hosted on heroku:**
[https://shielded-fortress-32748.herokuapp.com/catalog/](https://shielded-fortress-32748.herokuapp.com/catalog/)
> 

<aside>
⚠️ Hosted with different private repository, so host settings could be changed

</aside>

The site includes: 

- [**Database usage**](https://docs.djangoproject.com/en/4.0/topics/db/models/)
- **[Built-in class-based generic views](https://docs.djangoproject.com/en/4.0/topics/class-based-views/generic-display/)**
- [A**uthentication system**](https://docs.djangoproject.com/en/4.0/topics/auth/default/)
- **[Testing](https://docs.djangoproject.com/en/1.10/topics/testing/overview/)**

To demonstrate the work of the functionality for the librarian, log in to your "**staff**" account. The site will have an additional function of viewing all the books that have been borrowed.
If you re-login to “**user**” account, you will have access to the “My borrowed” page, where the same books will be listed, but from the side of the library visitor.

***Below is a list of accounts with different levels of access***

**superuser access**

```
Login: admin
Password: admin

```

**staff member access**

```
Login: staffmember
Password: staffpass1

```

**librarian (moderator) access** (in group with permission)

```
Login: librarian
Password: libpass1

```

**user access** (basic)

```
Login: user
Password: passpass1

```

MDN original version:
[https://github.com/mdn/django-locallibrary-tutorial](https://github.com/mdn/django-locallibrary-tutorial)
