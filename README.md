# swql
create table book(book_id integer primary key,title varchar(40),publisher_name varchar(50),pub_year varchar(10));
insert into book values(1,'sql','bb','2004');
insert into book values(2,'atc','aa','2001');
insert into book values(3, 'harry potter','blomsberry','1999');
insert into book values(4 ,'see you at the top ','zig ziglar','1998');
insert into book values(5,' sql','navarthe','2005');                                                    
create table book_copies(book_id integer,branch_id integer,no_of_copies integer,primary key(book_id,branch_id));

select *from book
