# rdwtechday.github.io
Rdw Techday Conference Site

## Design of this site
The main layout is defined but the `/_layouts/home.html` page. All the other page lay-outs are defined by `/_layouts/page.html`. In the home.html and page.html pages a number of includes are loaded from `/_includes`.

The pages shown in the top right menu are all grouped in the root folder. Adding a page here will add an extra menu button.

We have three collections:
- Session
- Speaker
- Organizer

### Speaker Collection
The speaker pages are located in `/_sprekers` and have three fields 
```yaml
---
naam: John Doe
ref: john-doe
titel: Chief Mugwump
---
```

A session is linked to a speaker through the sprekers field, the sprekers field must contain spreker.ref field. If so it will be shown linked to 


