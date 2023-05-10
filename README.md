# Démystifions les pratiques du Craft !

Retrouvez l'ensemble des slides [ici](Slides.pdf).

## Quelques sources pour se lancer ou parfaire sa pratique du Craft
- [Software Craft](https://www.dunod.com/sciences-techniques/software-craft-tdd-clean-code-et-autres-pratiques-essentielles) de Cyrille Martraire, Arnaud Thiéfaine, Dorra Bartaguiz, Fabien Hiegel, Houssam Fakih
- [The Pragmatic Programmer: From Journeyman to Master](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X) de Andrew Hunt et David Thomas
- [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.fr/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) de Robert C. Martin
- [Test Driven Development: By Example](https://www.amazon.fr/Test-Driven-Development-Kent-Beck/dp/0321146530) de Kent Beck
- [Refactoring: Improving the Design of Existing Code](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature-dp-0134757599/dp/0134757599/ref=dp_ob_title_bk) de Martin Fowler
- [Working Effectively with Legacy Code](https://www.amazon.fr/FEATHERS-WORK-EFFECT-LEG-CODE/dp/0131177052/ref=sr_1_1?qid=1578305602&refinements=p_27%3AMichael+Feathers&s=english-books&sr=1-1&text=Michael+Feathers) de Michael C. Feathers
- [Head First Design Patterns](https://www.amazon.fr/First-Design-Patterns-Elisabeth-Freeman/dp/0596007124/ref=sr_1_1?qid=1578305892&refinements=p_27%3AElisabeth+Freeman&s=english-books&sr=1-1&text=Elisabeth+Freeman) de Elisabeth Freeman, Eric Freeman, Bert Bates et Kathy Sierra
- [Patterns Of Entreprise Application Architecture](https://www.amazon.fr/Patterns-Enterprise-Application-Architecture-d%C2%B4Espagne/dp/B0073R93MO/ref=asap_bc?ie=UTF8) de Martin Fowler

## TDD - Kata
Une compagnie d'assurance automobile propose à ses clients quatre familles de tarifs identifiables par une couleur, du moins au plus onéreux : tarifs bleu, vert, orange et rouge. Le tarif dépend de la situation du conducteur :
* Un conducteur ou conductrice de moins de 25 ans et titulaire du permis depuis moins de deux ans, se voit attribuer le tarif rouge, si toutefois il n'a jamais été responsable d'accident. Sinon, la compagnie refuse de l'assurer.
* Un conducteur ou conductrice de moins de 25 ans et titulaire du permis depuis plus de deux ans, ou de plus de 25 ans mais titulaire du permis depuis moins de deux ans a le droit au tarif orange s'il n'a jamais provoqué d'accident, au tarif rouge pour un accident, sinon il est refusé.
* Un conducteur ou conductrice de plus de 25 ans titulaire du permis depuis plus de deux ans bénéficie du tarif vert s'il n'est à l'origine d'aucun accident et du tarif orange pour un accident, du tarif rouge pour deux accidents, et refusé au-delà
* De plus, pour encourager la fidélité des clients acceptés, la compagnie propose un contrat de la couleur immédiatement la plus avantageuse s'il est entré dans la maison depuis plus de cinq ans. Ainsi, s'il satisfait à cette exigence, un client normalement "vert" devient "bleu", un client normalement "orange" devient "vert", et le "rouge" devient orange.

*Thomas Boileau - Afup Day Lyon 2023*
