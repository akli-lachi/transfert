# transfers

This API allows to list the most expensive football transfers that took place between 2000 and 2018. 

This data API is created with Fastapi and the database is SQLAlchemy.

Create database : use insert_database.sql (or database.py)

API: main.py

Endpoints:
/teams/
/leagues/
/players/
/players/{player_id}
/transfers/
/players/{player_id}/transfers/
