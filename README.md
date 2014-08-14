# prototype-programme
### a Sails application


The purpose of this prototype is to demostrate how the advanced forms can dynamically be built through configurating the
fields of the programme on a administration page and by simply applying a template without the trouble coding the fields
on the html for each programme.


### Administration Page

In the backoffice, the administrators can view and add programmes: 
http://localhost:1337/programme/view


![Alt text](http://i.imgur.com/ZYpelfB.jpg)


and when the programme is clicked. The details will be displayed, showing all the fields that has been setup.
Fields as broken into sections, administrator can add a section and add a field within a section.

![Alt text](http://i.imgur.com/iJlTiT2.jpg)

The application can spit out a json equivalent of the details of the programme by adding ####&isRest=true
parameter on the url.

![Alt text](http://i.imgur.com/H2jIgg4.jpg)


