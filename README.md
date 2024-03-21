## Django-Used_cellphone_store

## Quick Start
```bash
git clone https://github.com/as183789043/Django-Used_cellphone_store.git
cd Django-Used_cellphone_store
pip install -r  requirements.txt
cd used_cellphone_store
python manage.py runserver
```
## Landing Page
![image](https://github.com/as183789043/Django-Used_cellphone_store/assets/56618553/e0ebdd76-32a2-4833-8011-a4844df9a9de)

## Cellphone  detail info
![image](https://github.com/as183789043/Django-Used_cellphone_store/assets/56618553/b2d2cbba-e109-441a-b2a1-bb112d95c17d)

## Modify verbose_name and ordering(-price) 
![image](https://github.com/as183789043/Django-Used_cellphone_store/assets/56618553/929505b3-4560-495c-aaad-fcf062af9398)

---

## ER Diagram
![image](https://github.com/as183789043/Django-Used_cellphone_store/assets/56618553/679e0227-73c7-4847-bf41-466211825923)

### ER Diagram plugin install
```bash
pip install pyparsing pydot
pip install django-extensions
```

### ADD this in settings.py
  ```python
  GRAPH_MODELS = {
    'all_applications': True,
    'group_models': True,
  }
  ```
### ADD  this in settings.py > INSTALLED_APPS 
```  python
django_extensions
```


### Create .dot file
```
python ./manage.py   graph_models  <application_name>  -a > my_project.dot
```

### copy my_project.dot content to this link
[Graphviz_Online](https://dreampuf.github.io/GraphvizOnline/)
