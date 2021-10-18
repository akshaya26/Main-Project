# Main-Project
Interview Automation System
This project is a prototype  to virtually hold interviews, starting from filling personal details, and automating the task of face to face QA session using a chatbot.
Foolproof malpractise detection is carried out using face recognition via opencv, which automatically terminates the interview in case of multiple malpractise attempts.
The candidate  communicates with a chatbot which is capable of asking relevant questions dynamically based on users answers to previously asked questions.
This is achieved using web scraping and word movers distance to analyse the answer similarity.Based on the similarities, scores are generated.This cumilative score is used to 
filter  out candidates as per recruiting companies requirement.

Input: Personal details and skill set information
Output: Interview scores sent as personalised mail for candidate and available in a dashboard for hiring company.
Operating System: Windows 10, Ubuntu
Programming language: Python 3
Python Framework: Flask
Database:  SQLAlchemy

