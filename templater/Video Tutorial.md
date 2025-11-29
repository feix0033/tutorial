---
title: <% tp.file.title %>
create_date: <% tp.file.creation_date("DD-MM-YYYY HH:mm") %>
last_modify_date: <% tp.file.last_modified_date("DD-MM-YYYY HH:mm") %>
aliases: 
tags:
  - toturial
  - video
tutorial-video: 
tutorial-tutor: 
tutorial-github: 
tutorial-doc: []
---
# <% tp.file.title %>
<% await tp.file.move("video_tutorial/" + tp.file.title + "/" + tp.file.title) %>

<% tp.file.cursor() %>