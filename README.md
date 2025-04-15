# I Speak
***
## about

- #### I Speak is webapp that will improve your english speaking from French. It will train you to different speaking scenario to upscale your own native accent
- #### You'll talk about :
>    - Gaming
>    - Cooking
>    - Driving
>    - School
>    - Sciences
>    - etc..
****

## Project made with :

- **[Python](https://www.python.org) :**
  - **[Django](https://docs.djangoproject.com)**
  - `django-allauth`
- **[Tailwindcss](https://tailwind.com)** `django-tailwind`
- **[HTMX](https://www.htmx.org)** `django-htmx`
- **[AlpineJS](https://alpinejs.dev)**
- **Google APIs** [`AI apis`](https://aistudio.google.com), `speach-to-text`, `text-to-speach`
- **...**

****

## Python requirements
>- **Django**
>- **django-tailwind***
>- **django-allauth**
>- **django-htmx**
>- **openai**
>- ***google-speach-to-text**
>- ***google-text-to-speach**
****

## Set up project locally
****
### **first clone this `GitHub` repo.**
****
```bash
    git clone https://github.com/wonder7b/ispeak-o1 
```
****
### **After cloning repo, open it in terminal and create and activate virtualenv**
****
 **bash**
```bash
    python3 -m venv .venv
```
```bash
    source .venv/bin/activte
```
****
**powershell or cmd**
```shell
    python -m venv .venv
```
```shell
    .venv\Scripts\activate
```
****
### **Now install project requirements from requirements.txt file**
****
**bash**
```bash
    python3 -m pip install -r requirements.txt
```
****
**powershell or cmd**
```shell
    python -m pip install -r requirements.txt
```
****
### Open terminal with virtualenv activated and run Django Local server
****
```shell
    python manage.py runserver
```