[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Ff4MKZ_9)
# Opdracht PHP8 02 Blog A

We gaan deze periode een Blog maken met OOP. Dat doen we in stappen: eerst maken we een heel simpele blog, zonder database, en beperkte functionaliteit. En daarna een steeds grotere versie.

We beginnen dus eerst met een heel simple Blog, zonder database. Eisen:
-	De blog heeft een class Users, een class Post, class Comment, en een class Blog.
-	User heeft de properties: username en password. En een constructor en setters en getters.
-	Post heeft de properties: title, description, content. En een constructor en setters en getters.
-	Comment heeft de properties: name, comment en timestamp. En een constructor en setters en getters.
-	Blog heeft de properties: posts en comments. Beide zijn arrays. Deze class heeft geen constructor maar wel de volgende methods: addPost, addComment, displayPosts, displayComments

Op de index pagina moet het volgende gebeuren:
-	Maak een nieuw blog object
-	Voeg posts toe
-	Voeg comments toe
-	Toon alle posts
-	Toon alle comments
