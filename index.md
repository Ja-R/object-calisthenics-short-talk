# Object Calisthenics : simplifier le code pour retrouver le métier (short talk)

## Ressources

### Lectures
- _**Object Calisthenics**_ de Jeff Bay, publié dans _The ThoughtWorks Anthology - Essays on Software Technology and Innovation_ (2008)
- _**The Pragmatic Programmer: From Journeyman to Master**_ d’Andy Hunt et Dave Thomas (1999)

### Conférences
- Sur la complexité → _**Dette technique et entropie du logiciel**_ d'Arnaud Lemaire : https://www.youtube.com/watch?v=VKe9EE4MUxk&t=967s
- Sur la séparation des responsabilités → _**Adoptez la clean archigonale**_ de Christophe Breheret-Girardin : https://www.youtube.com/watch?v=GG9WyeerqFA

### Instructions IA

- Exemple d'utilisation pour guider un assistant IA → Awesome copilot instructions : https://github.com/github/awesome-copilot/blob/main/instructions/object-calisthenics.instructions.md
    - À adapter au contexte du projet et aux objectifs recherchés

## Les règles et autres concepts complémentaires

| Rules                                                               | Concepts sous-jacents                                                         |
|:--------------------------------------------------------------------|:------------------------------------------------------------------------------|
| **1. Use only one level of indentation per method.**                | SRP, Extract ‘Til You Drop                                                    |
| **2. Don’t use the else keyword.**                                  | SRP, guard clauses, Polymorphism, KISS                                        |
| **3. Wrap all primitives and strings.**                             | Rich model, SRP, DRY, Rule 7, Rule 9                                          |
| **4. Use only one dot per line.**                                   | Law of Demeter, Tell Don’t ask, SRP, Rule 9                                   |
| **5. Don’t abbreviate.**                                            | Meaningful naming, SRP, Ubiquitous Language                                   |
| **6. Keep all entities small.**                                     | SRP, Extract ‘Til You Drop, Meaningful naming                                 |
| **7. Don’t use any classes with more than two instance variables.** | SRP, Open-Close Principle, Composition Over Inheritance, Polymorphism, Rule 3 |
| **8. Use first-class collection.**                                  | Rule 3                                                                        |
| **9. Don’t use any getters/setters/properties.**                    | Tell Don’t ask, Law of Demeter, SRP, Rich model, DRY                          |
