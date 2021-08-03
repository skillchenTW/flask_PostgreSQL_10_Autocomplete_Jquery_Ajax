CREATE TABLE countries (
	id serial PRIMARY KEY,
	name VARCHAR ( 60 ) NOT NULL
);

select * from countries;


INSERT INTO
    countries(id,name)
VALUES
(1, 'Taiwan台灣'),
(2, 'Aringland Islands'),
(3, 'Albania'),
(4, 'Algeria'),
(5, 'American Samoa'),
(6, 'Andorra'),
(7, 'Angola'),
(8, 'Anguilla'),
(9, 'Antarctica'),
(10, 'Antigua and Barbuda'),
(11, 'Argentina'),
(12, 'Armenia'),
(13, 'Aruba'),
(14, 'Australia');


相關WebSite:
https://pypi.org/project/WTForms/
https://wtforms.readthedocs.io/en/2.3.x/
