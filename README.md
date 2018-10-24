# The Hacking Class

> Programming w/ @Clément Baldy & @LeaLp

**Après téléchargement du repo, lancer**

```bundle install```  
```rails db:migrate```  
```rails db:seed```  

Accès à la console pour vérifier la structure de la BDD
```rails console```


## Résumé du projet
- Création d'un site d'éducation en ligne
- Dans ce site, les élèves peuvent s'inscrire à un seul cours
- Un cours peut avoir plusieurs élèves

## Structure de la BDD

### Models 
- Course
- Student

### Colonnes de chaque table
> ```timestamps``` est présent dans chaque table sous la forme  
> ```t.datetime "created_at", null: false```  
> ```t.datetime "updated_at", null: false```   

* **table** ```courses```
    * "content" (text)

* **table** ```students```
    * "name" (string)
    * "course_id" **(foreign key)**
   
