# sqlOdev8
1)test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
2)Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
3)Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
4)Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.


1) CREATE TABLE employee (
id INTEGER PRIMARY KEY,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)
)

2) insert into employee (id, name, birthday, email) values (1, 'Ealasaid', '23-08-2009', 'eayerst0@uiuc.edu');
insert into employee (id, name, birthday, email) values (2, 'Rabi', '04-11-1992', 'rwishkar1@tumblr.com');
insert into employee (id, name, birthday, email) values (3, 'Leroy', '02-04-2008', 'lboocock2@sohu.com');
insert into employee (id, name, birthday, email) values (4, 'Cynthie', '07-03-1993', 'cvanderplas3@cnet.com');
insert into employee (id, name, birthday, email) values (5, 'Lesli', null, 'lhenriksson4@unblog.fr');
insert into employee (id, name, birthday, email) values (6, 'Kelcey', '08-09-2000', 'kskunes5@earthlink.net');
insert into employee (id, name, birthday, email) values (7, 'Antonin', '27-09-1993', 'agutman6@dot.gov');
insert into employee (id, name, birthday, email) values (8, 'Lizabeth', '04-02-1998', 'lshadfourth7@arizona.edu');
insert into employee (id, name, birthday, email) values (9, 'Thomas', null, 'tmcindrew8@google.es');
insert into employee (id, name, birthday, email) values (10, 'Catriona', '30-09-2018', 'ccrowth9@army.mil');
insert into employee (id, name, birthday, email) values (11, 'Tawsha', '23-08-2011', null);
insert into employee (id, name, birthday, email) values (12, 'Emelina', '24-08-2008', 'echappelowb@devhub.com');
insert into employee (id, name, birthday, email) values (13, 'Madelon', '19-07-2013', 'mutteridgec@jiathis.com');
insert into employee (id, name, birthday, email) values (14, 'Silvia', '23-12-2005', 'spescudd@marketwatch.com');
insert into employee (id, name, birthday, email) values (15, 'Lizabeth', null, 'lcandeye@over-blog.com');
insert into employee (id, name, birthday, email) values (16, 'Bekki', '27-12-2010', 'bjenkinf@mozilla.org');
insert into employee (id, name, birthday, email) values (17, 'Katha', '28-04-2008', 'kslucockg@com.com');
insert into employee (id, name, birthday, email) values (18, 'Fred', '04-12-1992', null);
insert into employee (id, name, birthday, email) values (19, 'Eduardo', null, 'eblythini@youku.com');
insert into employee (id, name, birthday, email) values (20, 'Pier', '25-01-1991', 'pstendellj@macromedia.com');
insert into employee (id, name, birthday, email) values (21, 'Lindsey', null, null);
insert into employee (id, name, birthday, email) values (22, 'Morie', '02-01-1994', null);
insert into employee (id, name, birthday, email) values (23, 'Glen', '02-02-1994', 'gjacobm@goodreads.com');
insert into employee (id, name, birthday, email) values (24, 'Susette', '11-09-2010', 'slipgensn@sbwire.com');
insert into employee (id, name, birthday, email) values (25, 'Britt', '08-11-2004', 'bmanbyo@fda.gov');
insert into employee (id, name, birthday, email) values (26, 'Greggory', '21-09-2009', 'gernshawp@tinypic.com');
insert into employee (id, name, birthday, email) values (27, 'Tally', '16-02-1995', null);
insert into employee (id, name, birthday, email) values (28, 'Jany', '10-02-2019', null);
insert into employee (id, name, birthday, email) values (29, 'Sydney', '30-08-2001', 'salliots@biblegateway.com');
insert into employee (id, name, birthday, email) values (30, 'Erny', '10-05-2008', null);
insert into employee (id, name, birthday, email) values (31, 'Ivar', '29-04-2002', 'ihedworthu@liveinternet.ru');
insert into employee (id, name, birthday, email) values (32, 'Kari', '17-03-2011', 'kstandenv@auda.org.au');
insert into employee (id, name, birthday, email) values (33, 'Valle', '08-06-2017', 'vhenrietw@squarespace.com');
insert into employee (id, name, birthday, email) values (34, 'Dyanne', '02-06-2022', 'dcamillox@pcworld.com');
insert into employee (id, name, birthday, email) values (35, 'Stanleigh', null, 'sbeebisy@rediff.com');
insert into employee (id, name, birthday, email) values (36, 'Sofia', '28-05-1998', 'spurcerz@zimbio.com');
insert into employee (id, name, birthday, email) values (37, 'Freeland', '13-02-2022', 'fcunnow10@yahoo.co.jp');
insert into employee (id, name, birthday, email) values (38, 'Karrie', '17-10-2011', 'kmassie11@com.com');
insert into employee (id, name, birthday, email) values (39, 'Ashton', '02-01-2005', null);
insert into employee (id, name, birthday, email) values (40, 'Connie', '11-12-2012', 'cocrevy13@simplemachines.org');
insert into employee (id, name, birthday, email) values (41, 'Dorthea', '17-06-1999', 'dcamilleri14@technorati.com');
insert into employee (id, name, birthday, email) values (42, 'Olly', '01-09-1991', 'oaronoff15@businessweek.com');
insert into employee (id, name, birthday, email) values (43, 'Hermine', null, 'hdewolfe16@google.com.au');
insert into employee (id, name, birthday, email) values (44, 'Biron', '15-12-2017', 'bdishmon17@skyrock.com');
insert into employee (id, name, birthday, email) values (45, 'Read', '06-12-1991', 'rvicker18@ehow.com');
insert into employee (id, name, birthday, email) values (46, 'Hall', '29-01-2007', 'hcasolla19@telegraph.co.uk');
insert into employee (id, name, birthday, email) values (47, 'Carl', '15-07-2018', 'cmacgille1a@etsy.com');
insert into employee (id, name, birthday, email) values (48, 'Jervis', '19-03-2010', 'jpickthall1b@ebay.com');
insert into employee (id, name, birthday, email) values (49, 'Ingaborg', '21-01-2021', 'isurby1c@ucoz.com');
insert into employee (id, name, birthday, email) values (50, 'Bar', null, 'bregglar1d@weibo.com');

3) a)  update employee
       set name = 'Göker',
	     email = 'sakingoker@gmail.com',
	     birthday = '09-09-1993'
       where id = 5;
   b) update employee
      set name = 'sıla',
	    email = 'kossilakos@gmail.com'
      where id = 6; 
   c) update employee
      set name = 'sena',
	    birthday = '25-10-1997'
      where id = 50;
   d) update employee
      set name = 'Gülay'
      where id = 47;
   e) update employee
      set name = 'Ayhan',
      birthday = '01.09.1962'
      where id = 42;
4) a) DELETE from employee
      where id = 33;
   b) DELETE from employee
      where name = 'Freeland';
   c) DELETE from employee
      where email = 'bdishmon17@skyrock.com';
   d) DELETE from employee
      where birthday = '09-09-1993';
   e) DELETE from employee
      where id = 47;
