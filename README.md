# Sparkify_Cassandra
## ETL Pipeline using Cassandra

### Background

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. This project creates an ETL pipeline for Sparkify that is catered to three specific queries to allow for a high availablility on its NoSQL database. 

### Database Schema Design:
The three queries used to develop this database are:
1. Selecting the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Selecting the name of the artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Selecting every user name (first and last) in the music app history who listened to the song 'All Hands Against His Own'

Below are the following tables analysts have access to:
- music_app_history
- user_history 
- song_history 

### Instructions to run (?):
Unfortunately this repo cannot run as is. This project was built during Udacity's Data Engineering Nanodegree and with the help of their internal infrastructure to allow students to build within jupyter notebooks already filled with the data needed and the dbs installed in the vms being used. The file submitted in this repo is merely the CQL and python code needed to run python's cassandra library and interface with the Apache Cassandra database.

