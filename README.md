# django-custom-admin-view
A django app to create custom admin function-based and class-based views

## TODO
- [ ] Study current possiblilities to do this
    - [ ] [This SO Answer](https://stackoverflow.com/questions/35875454/django-admin-extending-admin-with-custom-views#35876222)
    - [ ] [django-adminplus](https://github.com/jsocol/django-adminplus)
    - [ ] [Django doc](https://docs.djangoproject.com/en/3.2/ref/contrib/admin/#adding-views-to-admin-sites) about adding Views in the admin

## Expected behavior 
- Simply inherit from a class (like `LoginRequiredMixin`)
- Like for other admin pages, eequire the user to be connected and staff, else redirect to the admin login page
- Get the context variables to get the same look and feel of the other admin pages
