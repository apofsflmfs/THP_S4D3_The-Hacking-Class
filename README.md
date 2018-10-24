# The Hacking Class

> Programming w/ @Clément Baldy & @LeaLp

**Après téléchargement du repo, lancer**

```bundle install```  
```rails db:migrate```  
```rails db:seed```  

Accès à la console pour vérifier la structure de la BDD
```rails console```


## Résumé du projet
- Création d'un site où les utilisateurs peuvent créer des "pins"
- Chauqe pin contient une URL d'une image sur le net
- Les utilisateurs peuvent commenter les pins, mais ne peuvent pas commenter les commentaires

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
   
