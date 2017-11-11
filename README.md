# project7469
opensource project
->Please create database named online_elec in mysql database
->then craete tables named cart,products,sessions and users in the online_elec database
-attributes used in cart are:

attributes         datatype
sid                 int  
id_item            varchar(20)
quantity             int

-attributes used in products are:-

id            int
item          varchar(20)
prize         int
number        int


-attributes used in sessions are:-
sid         varchar(20)
sdata       varchar(20)
sexpire     varchar(20)

-attributes used  in users are:-

name        varchar(20)
surname     varchar(20)
country     varchar(20)
address     varchar(100)
email       varchar(100)
username    varchar(30)
password    varchar(15)


then add some electronic items in products table with available quantity and price :-
insert into products values(1,"tubelight",30,5);
insert into products values(2,"bulb",45,3);
insert into products values(3,"wire",35,6);
insert into products values(4,"copper wire",50,7);
insert into products values(5,"cfl",49,8);
