# database
from db_connection import DB
connection = DB(host='localhost', user='root', password='', database='test')
connection.insert('test',1, 'Andrew Levutsky')
