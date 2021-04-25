# Junior Developer CV
1. **Name:**  Aliaksei Anishchanka
![This is my photo](https://media-exp1.licdn.com/dms/image/C5603AQGAGYg-wlrEpA/profile-displayphoto-shrink_800_800/0/1618871347787?e=1625097600&v=beta&t=RaMftcyIC27qMn1KP9A5qRSv382Vh9JDgZYzkf_F4Ck)
2. **Contact:**

| Way      | Source |
| -------- |:------ |
| email    | aliaksei00anischanka@gmail.com |
| facebook | https://www.facebook.com/alex.anishchanka.9 |
| telegram | @aliaksei_anishchanka |
| discord  | aleshka_malchik#7517 |
3. **Summary**
* Focused on learning Android
* In 6 months of RSSCHOOL cource or earlier :smile: want to start IT career
* Hope I will encourage my techical knowledge
* Already used to learn something new
* As a student have a little experience in many fields. It gives no profit to me. Morally tired of this :dizzy_face:. Finally, RSCHOOL is my chance to learn one technology (Android) properly
* Why android? It allows to create something beautiful. Comparing to  front-end it has much less components to display, so it is more  comfortable to create layout, also allows to work with different  smartphone functionalities.
4. **Skills**
* *Android* - already learned something about android. 
* *Python* - main language
* *Git* - basics
* *SQL*
* *MS SQL*
* *Java* - first language
* *Kotlin* - start learning
5. **Code examples**  
```python
    def make_relations(self, point_to_make_connection, max_connections_num=3):
        possible_connections = max_connections_num - self.get_relations_with_point_count(point_to_make_connection)
        if possible_connections > 0:
            for point in self.get_closed_points(point_to_make_connection):
                if max_connections_num - self.get_relations_with_point_count(point) > 0:
                    potential_relation = [point, point_to_make_connection]
                    if point != point_to_make_connection and not self.exist_relation(potential_relation):
                        if not self.have_crosses(potential_relation):
                            self.__relations.append(potential_relation)
                            possible_connections -= 1
                            if possible_connections == 0:
                                return
```
6. **Source code** of my projects can be observed on [my github page](https://github.com/amsuredev)
7. **Education:** Wroclaw University of Computer Science And Technology 2018 - present
8. **Languages**:
* *English:* I have passed one-year cource of english B2 in my university last year.
* *Polish:* C1 
* *Russian:* Native