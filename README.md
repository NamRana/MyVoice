MyVoice  

Create and edit document with your voice only.

## Table of Contents
1. [Project Aims](#project-aims)
1. [Overview](#overview)
1. [Functionality](#functionality)
1. [Technologies & Frameworks](#technologies--frameworks)


## Project Aims
Writing and editing papers, documents, and emails is an essential task for any modern day student. Yet, the way in which we do so can be inhibitive for some. While keyboards and mice are incredibly useful for most, for those that are missing limbs, hands, digits, or have conditions such as Arthritis in the hand, Parkinson’s, Carpal Tunnel Syndrome, or Essential Tremor, keyboards are practically unusable if not extremely discomforting. The number of Americans that belong to this group is estimated to be over 28 million. 

This problem is amplified by remote and hybrid education. Prior to the pandemic, students had access to disability services, where they could take tests and write papers with the help of university transcribers. However, with the transition to remote learning, these students must now rely on imperfect hacks such as sending audio files, painfully using a keyboard, or avoiding typing altogether. 

We wanted to take this opportunity to develop a tool that would make it easy for students with such conditions to participate in the classroom (and potentially employees in the workplace) without access to disability services.

## Overview
MyVoice is a document editing tool that uses your voice as the primary interface between you and your computer. From start to finish, you can create, edit, format, reorder, and export your documents just like you would on MS Word or Google Docs without ever touching a keyboard or mouse. 

MyVoice is intended to be a desktop application that allows you to write up an essay, an email, or complete a written test by converting your voice into context-aware instructions. By clearly indexing every paragraph and sentence visually, giving voice instructions has never been easier. Once you open up a document, you can simply say a command such as "start typing" or "delete this from paragraph 2" followed by what you would like to type or delete. The supported commands are described below. Once you finish typing, you can tell Speechful to add punctation after a certain word, move your cursor to another paragraph, and most importantly, change words that were misunderstood.

## Functionality
Currently supported voice functionality:
- [x] Create document - "Create new document"
- [x] Save document - "Save"
- [x] Open document - "Open document (document id)"
- [x] Start typing - "Start typing"
- [x] Stop typing  - "Stop typing"
- [x] Change Title - "Change title (new title)"
- [x] Add paragraph - "Add paragraph"
- [x] Real-time punctuation - comma, period, quotaiton are mapped to ,." respectively
- [x] Remove paragraph - "Remove paragraph (index)"
- [x] Remove word - "Remove (word) from paragraph (index)"
- [x] Replace word - "Replace (old word) with (new word) in paragraph (index)"
- [x] Bold word - "Bold (word) in paragraph (index)"
- [x] Move cursor - "Move cursor to paragraph (index)"

Planned functionality:
- [ ] Change size - "Change size of paragraph (index)"
- [ ] Change color - "Change color of paragraph (index)"
- [ ] Make above paragraph functions into sentence functions
- [ ] Move MyVoice to a container such as Electron
- [ ] Export a MyVoice document into common file types
- [ ] Create a tutorial for new users

## Technologies & Frameworks
The front-end of this application is built with [React](https://reactjs.org/). For natural language processing, we are using [Google Speech](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API). Design element dependancies include: [Material-UI](https://material-ui.com/) and [FontAwesome](https://fontawesome.com/).

## Contribute
In order to set up the project for contribution, run:
1. `cd speechful` to enter the `/speechful` directory.
1. `npm install` to install all the dependencies of the project
1. `npm run start` to launch the development server.
1. If it doesn't happen automatically, open `localhost:3000` in your browser.

