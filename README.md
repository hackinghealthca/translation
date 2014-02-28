### Translations for HackingHealth.ca

#### Make translation messages

To fetch translation strings from templates etc.

```
django-admin.py makemessages --all
```

or

```
django-admin.py makemessages --locale=en --locale=fr
```

#### Compile translation messages

To compile the translation messages (in `django.po`) for use (to `django.mo`).

```
django-admin.py compilemessages
```

**Restart server for changes to take effect**
