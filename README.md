# c_configuration_migration_updates

***liporuwcha namespace "c - configuration, migration, updates"***

 ![maintained](https://img.shields.io/badge/maintained-green)
 ![work-in-progress](https://img.shields.io/badge/work_in_progress-yellow)
 ![rustlang](https://img.shields.io/badge/rustlang-orange)
 ![postgres](https://img.shields.io/badge/postgres-orange)
 ![liporuwcha](https://bestia.dev/webpage_hit_counter/get_svg_image/000.svg)

## c - configuration, migration, update

Every project evolves and the code and the database need to be updated. Sometimes it is called "migration". Living with a database is very dynamic. Much more than just living with a program.

The same database can contain more than one project coded by different teams. The order of changes must not be linear. It means, that the team must know what projects are exclusively theirs and what projects are common and must be coordinated with other teams.
When writing the code it must be always careful, that it does not break when a new field is added.

To achieve integrity of the database all the code is concentrated inside the database. So other parts of the project can use common code.

ca - database objects

- caa - postgres server utils
- cab - postgres database utils
- cat - tables
- caf - fields
- cav - view
- cap - procedures  

cj - migration:  
how to migrate every table separately. Ideally without server downtime.

cs - backup and restore
ct - development, testing and production environment

## Open-source and free as a beer

My open-source projects are free as a beer (MIT license).  
I just love programming.  
But I need also to drink. If you find my projects and tutorials helpful, please buy me a beer by donating to my [PayPal](https://paypal.me/LucianoBestia).  
You know the price of a beer in your local bar ;-)  
So I can drink a free beer for your health :-)  
[Na zdravje!](https://translate.google.com/?hl=en&sl=sl&tl=en&text=Na%20zdravje&op=translate) [Alla salute!](https://dictionary.cambridge.org/dictionary/italian-english/alla-salute) [Prost!](https://dictionary.cambridge.org/dictionary/german-english/prost) [Nazdravlje!](https://matadornetwork.com/nights/how-to-say-cheers-in-50-languages/) 🍻

[//bestia.dev](https://bestia.dev)  
[//github.com/bestia-dev](https://github.com/bestia-dev)  
[//bestiadev.substack.com](https://bestiadev.substack.com)  
[//youtube.com/@bestia-dev-tutorials](https://youtube.com/@bestia-dev-tutorials)  
